# isDriven

* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isDriven(){
  permission = "isDriven";
  execute(){
    vehicle = player.look.getVehicle();
    if(vehicle.isDriven){
      player.message("Vehicle is currently being driven");
    }
    else{
      player.message("Vehicle is not currently being driven");
    }
  }
}
```

