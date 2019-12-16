---
description: This command is a very basic version of /tpa in uScript
---

# Basic /tpa command

> #### You might want to copy this to another text editing program for easier reading!

```css
teleportData = array(); // declares a array for data to be stored in

command tpRequest(target){ // Declares the command 'tpRequest' and its parameters 'target'
    permission = "tpRequest"; // Makes the command require the user to have the 'tpRequest' permission to run this command
    execute(){ // Declares the code to be executed when this command is run with permissions
        if(isSet(target)){ // Checks if the target parameter is set, if it is runs the code within the statement
            target = toPlayer(target); // sets the variable 'target' to the player with the name specified by the player, if it can't find a player with the name the variable is set to null
            if(isSet(target)){ // If a player was found then it runs the code inside the statement.
                teleportData.add(array(player, target.id)); // stores the player and the person they are sending the request to in an array
                player.message("Request sent to " + target.name); // Messages the player telling them they have been teleported to the target
                target.message(player.name + " has requested to tp to you!"); // messages the target to tell them they have a request
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

command tpAccept(){ // Declares the command 'tpAccept'
    permission = "tpAccept";// Makes the command require the user to have the 'tpAccept' permission to run this command
    execute(){ // Declares the code to be executed when this command is run with permissions
        requestFound = false; // this variable is set to false so if a request is not found the player is messaged.
        for(value in teleportData){ // for every value in the array 'teleportData' it executes the code within the loop
            if(value[1] == player.id){ // checks if the player has a request including them
                requestFound = true; // sets the variable to true so the player is not messaged with an error.
                target = value[0]; // sets the target variable to the player attempting to tp to them.
                if(isSet(target)){ // checks that the player is still on the server
                    player.message("Request Acccepted!"); // messages the player informing them the request was accepted successfully
                    target.message(player.name + " accepted your request!"); // messages the player who sent the request that it has succeeded
                    target.teleport(player.position); // teleports the person who made the request to the requested player
                }
                else{ // executes this code if the player who made the request has left.
                    player.message("Player who sent request not found"); // messages them that the person could not be found
                }
            }
        }
        if(requestFound == false){ // if the array does not contain a request to the player this code is ran
            player.message("Request Not Found!"); // Informs the player that they have no incoming requests
        }
    }
}
```

