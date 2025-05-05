<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulir Pengguna</title>
</head>
<body>

    <h1>Formulir Pengguna</h1>

    <form id="userForm">
        <label for="name">Nama:</label><br>
        <input type="text" id="name" name="name" required><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <button type="submit">Kirim</button>
    </form>

    <script src="formValidasi.js"></script>

</body>
</html>
