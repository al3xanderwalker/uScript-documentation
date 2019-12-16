# getVehicle

* Returns: \[vehicle\]

> #### Example:

```css
command structurePosition(){
    permission = "structurePosition";
    execute(){
      vehicle = player.look.getVehicle();
      player.message("Vehicles Name: " + vehicle.name);
    }
}
```

