# isRaining

* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isRaining(){
  permission = "isRaining";
  execute(){
    if(server.isRaining){
      player.message("It is currently raining!");
    }
    else{
      player.message("It is not currently raining!");
    }
  }
}
```

