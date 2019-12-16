# destroy

* Parameters: \[none\]

> #### Example:

```css
command destroyVehicle(){
  permission = "destroyVehicle";
  execute(){
    vehicle = player.look.getVehicle();
    vehicle.destroy();
    player.message("Vehicle Destroyed!");
  }
}
```

