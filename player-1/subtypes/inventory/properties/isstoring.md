# isStoring

* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isStoring(){
    permission = "isStoring";
    execute(){
      if(player.inventory.isStoring){
          player.message("You are storing items!");
      }
      else{
          player.message("You are not storing items!");
      }
    }
}
```

