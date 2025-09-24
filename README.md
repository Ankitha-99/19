<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1> Event via EventListener </h1>
    <button id="btn">ClickMe</button>
    <p id="msg" class="out"></p>
    <script>
        document.getElementById("btn").addEventListener("click",function(){
            document.getElementById("msg").innerText="Handled with EventListener";
        })
    </script>
</body>
</html>
