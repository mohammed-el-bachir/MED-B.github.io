<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Sign up</title>
</head>
<body>
    <form class="form" action="<?=$_SERVER['PHP_SELF'];?>" method="POST">
        <?php include 'errors.php';?>
        <div class="name_form">

            <input type="text" name="name" autocomplete="off" required id="name">
            <label for="name" class="label_name"><span class="content_name">User Name</span></label>


        </div>
        <div class="name_form">

            <input type="email" name="email" autocomplete="off" required id="email">
            <label for="name" class="label_name"><span class="content_email">Email</span></label>


        </div>
        <div class="name_form">

            <input type="password" name="password" autocomplete="off" required id="password">
            <label for="name" class="label_name"><span class="content_name">Password</span></label>


        </div>
        <div class="name_form">

            <input type="password" name="confipass" autocomplete="off" required id="confipass">
            <label for="name" class="label_name"><span class="content_name">Confirm Password</span></label>


        </div>
        <input type="submit" name="Sign" value="Sign up" >
        
         <?php  include("success.php") ?>




    </form>
</body>
</html>
