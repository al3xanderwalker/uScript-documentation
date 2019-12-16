# getStorage

* Method: \[get\]
* Returns: \[storage\]

> #### Example:

```css
command openStorage(){
  permission = "openStorage";
  execute(){
    barricade = player.look.getBarricade();
    storage = barricade.getStorage();
    storage.open(player);
    player.message("Storage Opened");
  }
}
```

