# locked

* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isLocked(){
  permission = "isLocked";
  execute(){
    vehicle = player.look.getVehicle();
    if(vehicle.locked){
      player.message("Vehicle is currently locked");
    }
    else{
      player.message("Vehicle is not currently locked");
    }
  }
}
```

* Method: \[set\]
* Returns: \[boolean\]

> #### Example:

```css
command toggleLocked(){
  permission = "toggleLocked";
  execute(){
    vehicle = player.look.getVehicle();
    if(vehicle.locked){
      vehicle.locked = false;
      player.message("Vehicle has been unlocked");
    }
    else{
      vehicle.locked = true;
      player.message("Vehicle has been locked");
    }
  }
}
```

