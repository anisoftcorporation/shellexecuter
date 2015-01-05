<?php

$script_path="/home/anirbanb2004/labx";
$script_name="createFolder.sh";

$name = $_REQUEST['name'];

$command="nohup sh ".$script_path."/".$script_name." ".$name." &";

echo $command;
$output = shell_exec($command);


?>
