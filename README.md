

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
