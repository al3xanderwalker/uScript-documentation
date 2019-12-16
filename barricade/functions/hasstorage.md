# hasStorage

* Returns: \[boolean\]

> #### Example:

```css
command isStorage(){
  permission = "isStorage";
  execute(){
    barricade = player.look.getBarricade();
    if(barricade.hasStorage()){
       player.message("This barricade is a storage");
    }
    else{
      player.message("This barricade is not a storage");
    }
  }
}
```

