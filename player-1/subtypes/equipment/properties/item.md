# item

* Method: \[get\]
* Returns: \[item\]

> #### Example:

```css
command equippedItem(){
    permission = "equippedItem";
    execute(){
        equipped = player.equipment.item;
        player.message("Your equipped items id is " + equipped.id);
    }
}
```

