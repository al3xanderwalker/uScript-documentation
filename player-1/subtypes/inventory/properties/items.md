# items

* Method: \[get\]
* Returns: \[array of items\]

> #### Example:

```css
command items(){
    permission = "items";
    execute(){
      items = player.inventory.items;
      for(item in items){
          player.message("You have a " + item.name);
      }
    }
}
```

