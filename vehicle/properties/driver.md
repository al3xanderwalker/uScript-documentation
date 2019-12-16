# driver

* Method: \[get\]
* Returns: \[player\]

> #### Example:

```css
command driversName(){
  permission = "driversName";
  execute(){
    vehicle = player.look.getVehicle();
    driverName = vehicle.driver.name;
    player.message("Drivers name: " + driverName);
  }
}
```

