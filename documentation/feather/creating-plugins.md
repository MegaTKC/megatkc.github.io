# Creating Plugins 
Create plugins to spice up your Feather / Pocketmine server!

## Step 1 - Create a php file. 
The php file can be renamed to anything you want. Just make sure it has the .php at the end of the filename.

## Step 2
Open up the file

## Step 3
```
<?php
/*
__PocketMine Plugin__
name=plugin
version=0.1
author=yourname
class=MyFirstPlugin
apiversion=5
*/
class MyFirstPlugin implements Plugin{
    public function __construct(ServerAPI $api, $server=false){
    }
    public function init(){
    }
    public function __destruct(){
    }
}
```

The api has to be set to 5 to be able to work with Feather-v0.1-alpha or Pocketmine-alpha-1.2.2.

## Step 4
Save the file and drag it into your pocketmine or feather ```plugins``` directory.

## Step 5 
Run your Feather / Pocketmine server! Enjoy!
