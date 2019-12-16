# health

* Method: \[get\]
* Returns: \[number \(0-100\)\]
* Extra: \[Im making an assumption that this value can only be 0-100\]

> #### Example:

```css
command getVehicleHealth(){
  permission = "getVehicleHealth";
  execute(){
    vehicle = player.look.getVehicle();
    vehicleHealth = vehicle.health;
    player.message("Vehicle health: " + vehicleHealth);
  }
}
```

* Method: \[set\]
* Returns: \[number \(0-100\)\]
* Extra: \[Im making an assumption that this value can only be 0-100\]

> #### Example:

```css
command setVehicleHealth(amount){
  permission = "setVehicleHealth";
  execute(){
    amount = toNumber(amount);
    if(amount < 0 or amount > 100){
      player.message("Vehicle health can only be set to a number between 0 and 100!");
    }
    else{
      vehicle = player.look.getVehicle();
      vehicle.health = amount;
      player.message("Vehicle Health set to " + vehicle.health + "%");
    }
  }
}
```

