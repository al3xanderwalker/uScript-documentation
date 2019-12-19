# seconds

* Parameters: \[length\], \[function\]
* Extra: \[You cannot return a value from these functions yet\]

```css
command secondDelay(length){ // Declares the 'secondDelay' command and its parameter 'length'
    permission = "secondDelay"; // Makes the command require the 'secondDelay' permission
    execute(){ // Declares the code to be ran if the player has the permission needed
        wait.seconds(length, player.message("This message took " + length + " seconds to send!"));
    } // ^ Sends the message after the specified amount of time 'length' 
}
```

