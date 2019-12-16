# explode

* Parameters: \[none\]

> #### Example:

```css
command explodeVehicle(){
  permission = "explodeVehicle";
  execute(){
    vehicle = player.look.getVehicle();
    vehicle.explode();
    player.message("Vehicle Exploded!");
  }
}
```

