# addItem

* Parameters: \[itemID\], \[amount\]

> #### Example:

```css
command addItem(itemID, amount){
    permission = "addItem";
    execute(){
      player.inventory.addItem(itemID, amount);
      player.message("You have been given " + amount + " items with ID " + itemID);
    }
}
```

