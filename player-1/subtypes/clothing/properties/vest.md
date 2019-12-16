# vest

* Method: \[get\]
* Returns: \[item\]

> #### Example:

```css
command vest(){
    permission = "vest";
    execute(){
        vest = player.clothing.vest;
        player.message("Your vest id is " + vest.id);
    }
}
```

