# vanish

* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isVanish(){
  permission = "isVanish";
  execute(){
    if(player.vanish){
      player.message("You are in vanish!");
    }
    else{
      player.message("You are not in vanish!");
    }
  }
}
```

* Method: \[set\]
* Returns: \[boolean\]

> Example:

```css
command toggleVanish(){
  permission = "toggleVanish";
  execute(){
    if(player.vanish){
      player.vanish = false;
      player.message("You are now not in vanish!");
    }
    else{
      player.vanish = true;
      player.message("You are now in vanish!");
    }
  }
}
```

