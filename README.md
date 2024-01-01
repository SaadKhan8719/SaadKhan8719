- 👋 Hi, I’m @SaadKhan8719
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
SaadKhan8719/SaadKhan8719 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multiplication Table</title>
</head>
<body>

<h1>Multiplication Table 2</h1>

<table border="1">
    <thead>
        <tr>
            <th>Multiplier</th>
            <th>Result</th>
        </tr>
    </thead>
    <tbody id="multiplicationTableBody">
        <!-- The table body will be filled dynamically using JavaScript -->
    </tbody>
</table>

<script>
    // Function to generate the multiplication table for 2
    function generateMultiplicationTable() {
        var tableBody = document.getElementById("multiplicationTableBody");

        for (var i = 1; i <= 10; i++) {
            var result = 2 * i;

            var row = document.createElement("tr");

            var multiplierCell = document.createElement("td");
            multiplierCell.textContent = "2 * " + i;
            row.appendChild(multiplierCell);

            var resultCell = document.createElement("td");
            resultCell.textContent = result;
            row.appendChild(resultCell);

            tableBody.appendChild(row);
        }
    }

    // Call the function to generate the multiplication table
    generateMultiplicationTable();
</script>

</body>
</html>
