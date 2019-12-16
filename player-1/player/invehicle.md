# inVehicle

* Method: \[get\]
* Returns: \[boolean\]

> Example:

```css
command inVehicle(){
  permission = "inVehicle";
  execute(){
    if(player.inVehicle){
      player.message("You are in a vehicle!");
    }
    else{
      player.message("You are not in a vehicle!");
    }
  }
}
```

