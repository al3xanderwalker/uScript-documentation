# jumpHeight

* Method: \[get\]
* Returns: \[number\]

> Example:

```css
command jumpHeight(){
  permission = "jumpHeight";
  execute(){
    player.message("Your Jump Height is set to " + player.jumpHeight);
  }
}
```

* Method: \[set\]
* Returns: \[number\]

> Example:

```css
command setJumpHeight(amount){
  permission = "setJumpHeight";
  execute(){
    amount = toNumber(amount);
    player.jumpHeight = amount;
    player.message("Jump Height set to " + player.jumpHeight);
  }
}
```

