# water

* Method: \[get\]
* Returns: \[number \(0-100\)\]

> #### Example:

```css
command water(){
  permission = "water";
  execute(){
    player.message("You have " + player.water + "% water!");
  }
}
```

* Method: \[set\]
* Returns: \[number \(0-100\)\]

> #### Example:

```css
command setWater(amount){
  permission = "setWater";
  execute(){
    amount = toNumber(amount);
    if(amount < 0 or amount > 100){
      player.message("Water can only be set to a number between 0 and 100!");
    }
    else{
      player.water = amount;
      player.message("Water set to " + player.water + "%");
    }
  }
}
```

