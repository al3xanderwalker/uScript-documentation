# radioFrequency

* Method: \[get\]
* Returns: \[number\]

> Example:

```css
command radioFrequency(){
  permission = "radioFrequency";
  execute(){
    player.message("You are on radio frequency " + player.radioFrequency);
  }
}
```

* Method: \[set\]
* Returns: \[number\]

> Example:

```css
command setFrequency(number){
  permission = "setFrequency";
  execute(){
    number = toNumber(number);
    player.radioFrequency = number;
    player.message("You are now on frequency " + player.radioFrequency);
  }
}
```

