# shirt

* Method: \[get\]
* Returns: \[item\]

> #### Example:

```css
command shirt(){
    permission = "shirt";
    execute(){
        shirt = player.clothing.shirt;
        player.message("Your shirt id is " + shirt.id);
    }
}
```

