# isOpen

* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isStorageOpen(){
  permission = "isStorageOpen";
  execute(){
    barricade = player.look.getBarricade();
    storage = barricade.getStorage();
    if(storage.isOpen){
      player.message("Storage is open");
    }
    else{
      player.message("Storage is not open");
    }
  }
}
```

