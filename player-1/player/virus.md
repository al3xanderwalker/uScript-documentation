# virus

* Method: \[get\]
* Returns: \[number \(0-100\)\]

> #### Example:

```css
command virus(){
  permission = "virus";
  execute(){
    player.message("You have " + player.virus + "% virus!");
  }
}
```

* Method: \[set\]
* Returns: \[number \(0-100\)\]

> Example:

```css
command setVirus(amount){
  permission = "setVirus";
  execute(){
    amount = toNumber(amount);
    if(amount < 0 or amount > 100){
      player.message("Virus can only be set to a number between 0 and 100!");
    }
    else{
      player.virus = amount;
      player.message("Virus set to " + player.virus + "%");
    }
  }
}
```

