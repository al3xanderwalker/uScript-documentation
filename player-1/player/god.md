# god

* Method: \[get\]
* Returns: \[boolean\]

> Example:

```css
command isGod(){
  permission = "isGod";
  execute(){
    if(player.god){
      player.message("You are in god mode!");
    }
    else{
      player.message("You are not in god mode!");
    }
  }
}
```

* Method: \[set\]
* Returns: \[boolean\]

> Example:

```css
command toggleGod(){
  permission = "toggleGod";
  execute(){
    if(player.god){
      player.god = false;
      player.message("God disabled!");
    }
    else{
      player.god = true;
      player.message("God enabled!");
    }
  }
}
```

