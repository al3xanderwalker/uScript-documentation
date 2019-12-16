# pants

* Method: \[get\]
* Returns: \[item\]

> #### Example:

```css
command pants(){
    permission = "pants";
    execute(){
        pants = player.clothing.pants;
        player.message("Your pants id is " + pants.id);
    }
}
```

