<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>FIDE Top Player</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f6f8;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        table {
            border-collapse: collapse;
            width: 60%;
            background-color: #ffffff;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        th, td {
            text-align: center;
            padding: 12px 16px;
            border-bottom: 1px solid #ddd;
        }
        th {
            background-color: #0074D9;
            color: white;
        }
        tr:hover {
            background-color: #f1f1f1;
        }
        caption {
            margin-bottom: 10px;
            font-size: 1.5em;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <table>
        <caption>FIDE Top Player</caption>
        <thead>
            <tr>
                <th>ID</th>
                <th>Name</th>
                <th>Federation</th>
                <th>ELO</th>
                <th>Date of Birth</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Sven Magnus Oen Carlsen</td>
                <td>Noruega</td>
                <td>2837</td>
                <td>1990-11-30</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
