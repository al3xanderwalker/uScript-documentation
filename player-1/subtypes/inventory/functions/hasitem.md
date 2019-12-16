# hasItem

* Parameters: \[none\]

> #### Example:

```css
command hasItem(itemID){
    permission = "hasItem";
    execute(){
      if(player.hasItem(itemID)){
          player.message("You are currently storing any items with id " + itemID);
      }
      else{
          player.message("You are not currently storing any items with id " + itemID);
      }
    }
}
```

