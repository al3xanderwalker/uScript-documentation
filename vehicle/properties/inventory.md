# inventory

* Method: \[get\]
* Returns: \[inventory\]

> #### Example:

```css
command listVehicleItems(){
  permission = "listVehicleItems";
  execute(){
    vehicle = player.look.getVehicle();
    inventory = vehicle.inventory;
    items = inventory.items;
    for(item in items){
      player.message("Vehicle Storage Contains " + item.name);
    }
  }
}
```

