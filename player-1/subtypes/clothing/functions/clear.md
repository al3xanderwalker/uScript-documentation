# clear

* Parameters: \[none\]

> #### Example:

```css
command clearClothing(){
    permission = "clearClothing";
    execute(){
        player.clothing.clear();
        player.message("Your clothing has been cleared!");
    }
}
```

