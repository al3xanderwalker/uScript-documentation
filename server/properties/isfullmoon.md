# isFullMoon

* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isFullMoon(){
  permission = "isFullMoon";
  execute(){
    if(server.isFullMoon){
      player.message("It is currently a full moon!");
    }
    else{
      player.message("It is not currently a full moon!");
    }
  }
}
```

