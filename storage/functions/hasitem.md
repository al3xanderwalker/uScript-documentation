# hasItem

* Parameters: \[number\]
* Returns: \[boolean\]
* Extra: \[Again i am unsure on the parameters for this?\]

> #### Example:

```css
command storageContains(itemID){
  permission = "storageContains";
  execute(){
    barricade = player.look.getBarricade();
    storage = barricade.getStorage();
    if(storage.hasItem(itemID)){
      player.message("The storage contains the specified item");
    }
    else{
      player.message("The storage does not contain the specified item");
    }
  }
}
```

