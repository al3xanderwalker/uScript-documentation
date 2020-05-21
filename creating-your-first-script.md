---
description: How to create a simple /ping script
---

# Creating your first script

* After installing the uScript loader, a folder called Scripts in your server's Rocket folder will have been generated, this is where the scripts that you want to use should go!

> ## Example Directory: Unturned/Servers/YourServerNameHere/Rocket/Scripts

* Once you have located this directory, you are ready to create your first script! Create a new file, it can be named almost anything you want but **MUST** have the **.uscript** file extension.

> ## Example File Name: cheese.uscript

* Paste the following code into the file

```css
command ping(){
    execute(){
        player.message("Pong!");
    }
}
```

* Save the file and put it your Scripts folder if you haven't already.
* Load your new script by using the command /script load &lt;file name&gt;

> ## Example: /script load cheese.uscript

* Note that all scripts in your Scripts directory will be loaded automatically when your server starts, or when either Rocket or uScript are reloaded using the ``/rocket reload`` command. 
* Test your script! Use the command ``/ping`` and see if you are messaged "Pong!" If so, then you have created your first script!
* If you were messaged "Command not found", then attempt completing the process again, or ask for help in the uScript discord!

> ## Discord Link: [https://discord.gg/MNUgZkr](https://discord.gg/MNUgZkr)

