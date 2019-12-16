# stance

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command stance(){
  permission = "stance";
  execute(){
    player.message("Your current stance is " + player.stance);
  }
}
```

* Method: \[set\]
* Returns: \[string\]

> #### Example:

```css
command stance(){
  permission = "stance";
  execute(){
    player.stance = "prone";
    player.message("Your stance has been set to " + player.stance);
  }
}
```

