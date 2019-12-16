# group

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command vehicleGroup(){
  permission = "vehicleGroup";
  execute(){
    vehicle = player.look.getVehicle();
    player.message("Vehicles group:  " + vehicle.group);
  }
}
```

* Method: \[set\]
* Returns: \[string\]

> #### Example:

```css
command setVehicleGroup(groupId){
  permission = "setVehicleGroup";
  execute(){
    vehicle = player.look.getVehicle();
    vehicle.group = groupId;
    player.message("Vehicles group set to " + vehicle.group);
  }
}
```

