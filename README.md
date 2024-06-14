# To-Do-List
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="todo-list">
            <h1>ToDo List</h1>
            <div class="row">
                <input type="text" id="input-box" placeholder="Enter your task">
                <button onclick="Add()">Add</button>
            </div>
            <ul id="List-container">
            </ul>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
