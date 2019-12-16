# inventory

* Method: \[get\]
* Returns: \[inventory\]

> #### Example:

```css
command listItems(){
  permission = "listItems";
  execute(){
    barricade = player.look.getBarricade();
    storage = barricade.getStorage();
    items = storage.inventory.items;
    for(item in items){
      player.message("Storage Contains " + item.name);
    }
  }
}
```

