---
Description: >-
  Sends a message to a specified Discord channel when a player is kicked,
  including the information on who executed the command, the player kicked and
  the reason for them being kicked.
---

# Kick player message to discord

> #### You might want to copy this to another text editing program for easier reading!
>
> #### This example is based on  **Stalker's Staff System**

```css
webhook = "YOUR_WEBHOOK_HERE"; // Defines the webhook url for the message to be sent to.

command kick(targetPlayer,reason){ // Declares the command 'kick' and its arguments 'targetPlayer' and 'reason'
    permission = "kick"; // Makes the command require the user to have the 'kick' permission
    execute(){ // Declares the code to be executed when this command is run with permissions
        if(arguments.count < 2){ // Checks if the player has not specified the correct amount of arguments
            player.message("Proper Usage: /kick (player) (reason)"); // Messages the player the proper usage if they did not specify enough arguments
            return;
        }
    else{ // If the player did specify the correct amount of arguments this code is ran
        target = toPlayer(targetPlayer); // Sets the variable 'target' to the player specified
        target.kick(reason); // Kicks the target player with the specified reason
        arguments.removeAt(0); // Removes the first argument specifed so the player name is not included in the the sent webhook
        message = toString(arguments).replace(",", ""); // Converts the array of arguments to a single string 'message'
        discord.send(str.format("``{0}`` kicked ``{1}`` with reason: ``{2}``",player.name,target.name,message),webhook,dt.now.string,"https://i.imgur.com/izBo7UZ.png"); 
    }} // ^Sends the message to through the webhook to a discord channel along with the players name who executed the command, the target and the reason
}
```

