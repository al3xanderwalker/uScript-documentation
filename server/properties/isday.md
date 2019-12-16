# isDay

* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isDay(){
  permission = "isDay";
  execute(){
    if(server.isDay){
      player.message("It is currently day!");
    }
    else{
      player.message("It is not currently day!");
    }
  }
}
```

