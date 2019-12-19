# minutes

* Parameters: \[length\], \[function\]
* Extra: \[You cannot return a value from these functions yet\]

```css
command minuteDelay(length){ // Declares the 'minuteDelay' command and its parameter 'length'
    permission = "minuteDelay"; // Makes the command require the 'minuteDelay' permission
    execute(){ // Declares the code to be ran if the player has the permission needed
        wait.seconds(length, player.message("This message took " + length + " minutes to send!"));
    } // ^ Sends the message after the specified amount of time 'length' 
}
```

