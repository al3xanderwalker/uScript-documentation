---
description: How to create a simple /ping script
---

# Creating your first script

* After installing the uscript loader a folder called Scripts in your servers Rocket folder will have been generated, this is where all your scripts go.

> #### Example Directory: Unturned/Servers/Your\_Servers\_Name/Rocket/Scripts

* Once you have located this directory you are ready to create your first script! Create a new file, it can be named almost anything you want but **MUST** have the **.uscript** file extension

> #### Example File Name: Example.uscript

* Paste the following code into the file

```css
command ping(){
    execute(){
        player.message("Pong!");
    }
}
```

* Save the file and put it your Scripts folder if you havent already.
* Load your new script by using the command /script load &lt;file name&gt;

> #### Example: /script load Example.uscript

* Note that all scripts in your Scripts directory will be loaded automatically when your server starts or when either Rocket or uScript are reloading using the /rocket reload command. 
* Test your script! Use the command /ping and see if you are messaged Pong! if so then you have created your first script!
* If you got messaged Command not found then try completing the process again or ask for help in the uScript discord!

> #### Discord: [https://discord.gg/MNUgZkr](https://discord.gg/MNUgZkr)



