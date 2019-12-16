# health

* Method: \[get\]
* Returns: \[number \(0-100\)\]

> Example:

```css
command health(){
  permission = "health";
  execute(){
    player.message("You have " + player.health + "% health!");
  }
}
```

* Method: \[set\]
* Returns: \[number \(0-100\)\]

> Example:

```css
command setHealth(amount){
  permission = "setHealth";
  execute(){
    amount = toNumber(amount);
    if(amount < 0 or amount > 100){
      player.message("Health can only be set to a number between 0 and 100!");
    }
    else{
      player.health = amount;
      player.message("Health set to " + player.food + "%");
    }
  }
}
```

