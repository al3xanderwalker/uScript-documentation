---
description: This command is essentially /tp <player> in uScript
---

# Basic /tp Command

> #### You might want to copy this to another text editing program for easier reading!

```css
command tpTo(target){ // Declares the command 'tpTo' and its parameters 'target'
    permission = "tpTo"; // Makes the command require the user to have the 'tpTo' permission to run this command
    execute(){ // Declares the code to be executed when this command is run with permissions
        if(isSet(target)){ // Checks if the target parameter is set, if it is runs the code within the statement
            target = toPlayer(target); // sets the variable 'target' to the player with the name specified by the player, if it can't find a player with the name the variable is set to null
            if(isSet(target)){ // If a player was found then it runs the code inside the statement.
                player.teleport(target.position); // Teleports the player to the target players position.
                player.message("You have teleported to " + target.name); // Messages the player telling them they have been teleported to the target
            }
            else{ // If the player was not found and target was set to null this code will be executed
                player.message("Target not found"); // Messages the player saying the target player was not found
            }
        }
        else{ // If the player has not specified the target this code will be executed
            player.message("Usage: /tpTo <PlayerName>"); // Messages the player the correct usage of the command
        }
    }
}
```



