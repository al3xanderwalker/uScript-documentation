# position

* Method: \[get\]
* Returns: \[vector3\]

> #### Example:

```css
command getVehiclePosition(){
  permission = "getVehiclePosition";
  execute(){
    vehicle = player.look.getVehicle();
    player.message("Vehicles Position: X: " + vehicle.position.x + " Y: " + vehicle.position.y + " Z: " + vehicle.position.z);
  }
}
```

