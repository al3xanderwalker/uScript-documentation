# arrested



* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isArrested(){
  permission = "isArrested";
  execute(){
    if(player.arrested){
      player.message("You are arrested!");
    }
    else{
      player.message("You are not arrested!");
    }
  }
}
```

