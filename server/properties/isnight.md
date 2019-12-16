# isNight

* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isNight(){
  permission = "isNight";
  execute(){
    if(server.isNight){
      player.message("It is currently night!");
    }
    else{
      player.message("It is not currently night!");
    }
  }
}
```

