# prettiya.github.io
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ตัวสร้างตารางค่าความจริง</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>ตัวสร้างตารางค่าความจริง</h1>
        <form id="logicForm">
            <label for="proposition">ใส่โจทย์ตรรกศาสตร์:</label>
            <input type="text" id="proposition" name="proposition" required>
            <button type="submit">สร้างตาราง</button>
        </form>
        <div id="result">
            <h2>ผลลัพธ์:</h2>
            <div id="truthTable"></div>
            <div id="equivalentPropositions"></div>
            <div id="tautologyCheck"></div>
            <div id="negationProposition"></div>
        </div>
    </div>
    <script src="scripts.js"></script>
</body>
</html>
