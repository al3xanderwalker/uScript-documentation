# name

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command vehicleName(){
  permission = "vehicleName";
  execute(){
    vehicle = player.look.getVehicle();
    vehicleName = vehicle.name;
    player.message("Vehicles Name: " + vehicleName);
  }
}
```

