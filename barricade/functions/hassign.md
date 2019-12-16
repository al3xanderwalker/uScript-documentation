# hasSign

* Returns: \[boolean\]

> #### Example:

```css
command isSign(){
  permission = "isSign";
  execute(){
    barricade = player.look.getBarricade();
    if(barricade.hasSign()){
       player.message("This barricade is a sign");
    }
    else{
      player.message("This barricade is not a sign");
    }
  }
}
```

