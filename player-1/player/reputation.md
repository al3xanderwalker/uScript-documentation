# reputation

* Method: \[get\]
* Returns: \[number\]

> Example:

```css
command reputation(){
  permission = "reputation";
  execute(){
    player.message("Your reputation is " + player.reputation);
  }
}
```

* Method: \[set\]
* Returns: \[number\]

> Example:

```css
command setReputation(number){
  permission = "setReputation";
  execute(){
    number = toNumber(number);
    player.reputation = number;
    player.message("Your reputation has been changed to " + player.reputation);
  }
}
```

