# popTires

* Parameters: \[none\]

> #### Example:

```css
command popTires(){
  permission = "popTires";
  execute(){
    vehicle = player.look.getVehicle();
    vehicle.popTires();
    player.message("Vehicle Tires Popped!");
  }
}
```

