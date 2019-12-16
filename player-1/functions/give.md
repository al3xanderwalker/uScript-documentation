# give

* Parameters: \[itemID\], \[amount\]

> #### Example:

```css
command giveMe(itemID, amount){
  permission = "giveMe";
  execute(){
    player.give(itemID, amount);
    player.message("You have been given " + amount + " Items with ID " + itemID);
  }
}
```

