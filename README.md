<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title>Тікаюча кнопка</title>
</head>
<body>
    <style>
         body {
        background: violet
    }
    </style>
   
    <h2>Який в тебе настрій?</h2>

    <input type="button" value="Чудовий!" onClick="yes()">
   
    <div id="A" style="position:absolute; left:100px; top:67px;">
        <input type="button" value="Не дуже" onMouseover="run()">
    </div>
   
    <script>
    function yes() {
        alert("(ﾉ◕ヮ◕)ﾉ*:･ﾟ✧");
    }
    function run() {
        let n = document.getElementById("A");
        n.style.left = Math.random() * 300 + "px";
        n.style.top = Math.random() * 300 + "px";
    }
    </script>  
   
</body>
</html>
