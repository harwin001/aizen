<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surprise Link</title>
    <script>
        function showMessage() {
            alert("Everything was part of my plan");
        }
    </script>
</head>
<body>
    <a href="#" onclick="showMessage(); return false;">Click me!</a>
</body>
</html>
