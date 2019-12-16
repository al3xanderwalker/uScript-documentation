# spawnVehicle

* Parameters: \[vehicleID\], \[vector3\], \[rotation\]
* Extra: \[Rotation should be a number between 0-360\]

> #### Example:

```css
command spawnVehicle(vehicleID){
  permission = "spawnVehicle";
  execute(){
    vehicleID = toNumber(vehicleID);
    vehicleManager.spawnVehicle(vehicleID, player.position, 0)
    player.message("Vehicle Spawned with id: " + vehicleID);
  }
}
```

