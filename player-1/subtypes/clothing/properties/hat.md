# hat

* Method: \[get\]
* Returns: \[item\]

> #### Example:

```css
command hat(){
    permission = "hat";
    execute(){
        hat = player.clothing.hat;
        player.message("Your hats id is " + hat.id);
    }
}
```

