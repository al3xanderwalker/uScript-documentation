# speed

* Method: \[get\]
* Returns: \[number\]

> Example:

```css
command speed(){
  permission = "speed";
  execute(){
    player.message("Your speed is set to " + player.speed);
  }
}
```

* Method: \[set\]
* Returns: \[number\]

> Example:

```css
command setSpeed(amount){
  permission = "setSpeed";
  execute(){
    amount = toNumber(amount);
    player.speed = amount;
    player.message("Speed set to " + player.speed);
  }
}
```

