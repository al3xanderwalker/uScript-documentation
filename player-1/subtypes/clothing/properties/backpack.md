# backpack

* Method: \[get\]
* Returns: \[item\]

> #### Example:

```css
command backpack(){
    permission = "backpack";
    execute(){
        backpack = player.clothing.backpack;
        player.message("Your backpacks id is " + backpack.id);
    }
}
```

