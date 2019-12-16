# clear

* Parameters: \[none\]

> #### Example:

```css
command clearInventory(){
    permission = "clearInventory";
    execute(){
      player.inventory.clear();
      player.message("Your inventory has been cleared!");
    }
}
```

