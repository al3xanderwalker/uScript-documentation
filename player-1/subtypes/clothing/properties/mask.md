# mask

* Method: \[get\]
* Returns: \[item\]

> #### Example:

```css
command mask(){
    permission = "mask";
    execute(){
        mask = player.clothing.mask;
        player.message("Your mask id is " + mask.id);
    }
}
```

