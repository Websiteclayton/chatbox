# chatbox
chatbox
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <iframe src="index.php" width="600" height="400" style="border:10;background:black;color:white;"></iframe>
</body>
</html>
<center>
<div stle="height:100px; width:100px; background-color:blue;color:white;">
    <form action="index.php" method="post">
        <input name="username" placeholder="Enter message">
        <br>
        <button type="submit" name="submit">Send</button>
    </form>
</div>
<?php
    if(isset($_POST['submit'])){
        $name = $_POST['username'];
        echo "<h1 style='color:white;'>".$name."</h1>";
    }
    ?>
    </center>
