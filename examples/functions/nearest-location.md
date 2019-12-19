---
description: Tells the player the nearest location of the target player after 2 minutes
---

# Nearest Location

> #### You might want to copy this to another text editing program for easier reading!

```css
function waitLocation(caller, target){ // // Declares the function and its parameters to be called from elsewhere
    nearestLocation = target.getNearestLocation(); // sets the variable to the targets nearest location
    caller.message(target.name + "'s nearest location is " + nearestLocation); // Messages the player who called the command with the target location
}
command getNearest(target){ // Declares the command 'getNearest' and its parameters 'target'
    permission = "getNearest"; // Makes the command require the 'getNearest' Permission
    execute(){ // This code will be ran if the player has permissions
        if(isSet(target)){
            target = toPlayer(target); // sets the target variable to the player specified
            if(isSet(target)){ 
                wait.seconds(120, waitLocation(player, target)); // waits 120 seconds(2 Minutes) then calls the function waitLocation with the parameters 'player' as the caller and 'target' as the target
            }
            else{
                player.message("Target player could not be found");
            }
        }
        else{
            player.message("You did not specify a player");
        }
    }
}
```



