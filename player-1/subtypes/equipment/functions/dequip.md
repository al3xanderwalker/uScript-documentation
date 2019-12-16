# dequip

* Parameters: \[none\]

> #### Example:

```css
command dequipItem(){
    permission = "dequipItem";
    execute(){
        player.equipment.dequip();
        player.message("Your item has been dequipped!");
    }
}
```

