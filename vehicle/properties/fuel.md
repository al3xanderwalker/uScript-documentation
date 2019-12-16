# fuel

* Method: \[get\]
* Returns: \[number \(0-100\)\]
* Extra: \[Im making an assumption that this value can only be 0-100\]

> #### Example:

```css
command getFuel(){
  permission = "getFuel";
  execute(){
    vehicle = player.look.getVehicle();
    vehicleFuel = vehicle.fuel;
    player.message("Vehicle fuel: " + vehicleFuel);
  }
}
```

* Method: \[set\]
* Returns: \[number \(0-100\)\]
* Extra: \[Im making an assumption that this value can only be 0-100\]

> #### Example:

```css
command setFuel(amount){
  permission = "setFuel";
  execute(){
    amount = toNumber(amount);
    if(amount < 0 or amount > 100){
      player.message("Fuel can only be set to a number between 0 and 100!");
    }
    else{
      vehicle = player.look.getVehicle();
      vehicle.fuel = amount;
      player.message("Fuel set to " + vehicle.fuel + "%");
    }
  }
}
```

