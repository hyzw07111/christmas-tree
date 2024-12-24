# christmas-tree
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>圣诞树</title>
    <style>
        body {
            background: #000;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
            font-family: Arial, sans-serif;
        }
        .tree {
            text-align: center;
            line-height: 1.5;
        }
        .tree .star {
            color: gold;
            font-size: 24px;
        }
        .tree .branch {
            color: green;
        }
        .tree .trunk {
            color: brown;
        }
    </style>
</head>
<body>
    <div class="tree">
        <div class="star">★</div>
        <div class="branch">▲</div>
        <div class="branch">▲▲</div>
        <div class="branch">▲▲▲</div>
        <div class="branch">▲▲▲▲</div>
        <div class="branch">▲▲▲▲▲</div>
        <div class="trunk">||</div>
    </div>
</body>
</html>
