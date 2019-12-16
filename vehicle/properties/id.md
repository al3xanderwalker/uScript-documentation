# id

* Method: \[get\]
* Returns: \[number\]

> #### Example:

```css
command vehicleId(){
  permission = "vehicleId";
  execute(){
    vehicle = player.look.getVehicle();
    vehicleId = vehicle.id;
    player.message("Vehicles ID: " + vehicleId);
  }
}
```

