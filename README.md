<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anisa Azad Oishy's Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Anisa Azad Oishy's Portfolio</h1>
        <p>Age: 23</p>
        <p>Currently studying at Daffodil International University, Department of Computer Science and Engineering (CSE).</p>
        
        <h2>Academic Details</h2>
        <table>
            <tr>
                <th>Examination</th>
                <th>Institution</th>
                <th>Year</th>
                <th>GPA</th>
            </tr>
            <tr>
                <td>SSC</td>
                <td>Monipur High School and College</td>
                <td>2019</td>
                <td>5.00</td>
            </tr>
            <tr>
                <td>HSC</td>
                <td>Shaheed Bir Uttam Lt Anwar Girls College</td>
                <td>2021</td>
                <td>5.00</td>
            </tr>
        </table>
    </div>
</body>
</html>
body {
    background-color: #f0f8ff;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
}

.container {
    background-color: #ffffff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    padding: 20px;
    width: 80%;
    max-width: 600px;
    text-align: center;
}

h1 {
    color: #333;
}

h2 {
    color: #555;
    margin-top: 20px;
}

p {
    color: #666;
}

table {
    width: 100%;
    margin-top: 10px;
    border-collapse: collapse;
}

table, th, td {
    border: 1px solid #ddd;
}

th, td {
    padding: 8px;
    text-align: center;
}

th {
    background-color: #4CAF50;
    color: white;
}

td {
    background-color: #f9f9f9;
}


