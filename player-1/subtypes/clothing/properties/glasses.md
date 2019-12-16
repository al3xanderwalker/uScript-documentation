# glasses

* Method: \[get\]
* Returns: \[item\]

> #### Example:

```css
command glasses(){
    permission = "glasses";
    execute(){
        glasses = player.clothing.glasses;
        player.message("Your glasses id is " + glasses.id);
    }
}
```

