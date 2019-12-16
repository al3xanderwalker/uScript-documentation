# bleeding



* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isBleeding(){
  permission = "isBleeding";
  execute(){
    if(player.bleeding){
      player.message("You are bleeding!");
    }
    else{
      player.message("You are not bleeding!");
    }
  }
}
```

* Method: \[set\]
* Returns: \[boolean\]

> #### Example:

```css
command toggleBleeding(){
  permission = "toggleBleeding";
  execute(){
    if(player.bleeding){
      player.bleeding = false;
      player.message("Stopped Bleeding!");
    }
    else{
      player.bleeding = true;
      player.message("Started Bleeding!");
    }
  }
}
```

