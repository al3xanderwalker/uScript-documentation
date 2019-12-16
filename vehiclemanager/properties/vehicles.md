# vehicles

* Method: \[get\]
* Returns: \[array of vehicles\]

> #### Example:

```css
command listAllVehicles(){
  permission = "listAllVehicles";
  execute(){
    vehicles = vehicleManager.vehicles;
    for(vehicle in vehicles){
      player.message("Vehicle name: " + vehicle.name);
    }
  }
}
```

