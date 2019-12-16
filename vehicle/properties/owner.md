# owner

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command vehicleOwner(){
  permission = "vehicleOwner";
  execute(){
    vehicle = player.look.getVehicle();
    player.message("Vehicle Owners id:  " + vehicle.owner);
  }
}
```

* Method: \[set\]
* Returns: \[string\]

> #### Example:

```css
command setVehicleOwner(){
  permission = "setVehicleOwner";
  execute(){
    vehicle = player.look.getVehicle();
    vehicle.owner = player.id;
    player.message("Vehicle owner set to you");
  }
}
```

