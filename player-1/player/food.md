# food

* Method: \[get\]
* Returns: \[number \(0-100\)\]

> Example:

```css
command food(){
  permission = "food";
  execute(){
    player.message("You have " + player.food + "% food!");
  }
}
```

* Method: \[set\]
* Returns: \[number \(0-100\)\]

> Example:

```css
command setFood(amount){
  permission = "setFood";
  execute(){
    amount = toNumber(amount);
    if(amount < 0 or amount > 100){
      player.message("Food can only be set to a number between 0 and 100!");
    }
    else{
      player.food = amount;
      player.message("Food set to " + player.food + "%");
    }
  }
}
```

