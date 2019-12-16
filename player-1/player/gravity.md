# gravity

* Method: \[get\]
* Returns: \[number\]

> Example:

```css
command gravity(){
  permission = "gravity";
  execute(){
    player.message("Your gravity is set to " + player.gravity);
  }
}
```

* Method: \[set\]
* Returns: \[number\]

> Example:

```css
command setGravity(amount){
  permission = "setGravity";
  execute(){
    amount = toNumber(amount);
    player.gravity = amount;
    player.message("Gravity set to " + player.gravity);
  }
}
```

