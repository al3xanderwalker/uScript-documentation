# removeItem

* Parameters: \[itemID\], \[amount\]

> #### Example:

```css
command removeItem(itemID, amount){
    permission = "removeItem";
    execute(){
      player.inventory.removeItem(itemID, amount);
      player.message(amount + " items with id " + itemID + " have been removed from your inventory!");
    }
}
```

