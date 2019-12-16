# isSnowing

* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isSnowing(){
  permission = "isSnowing";
  execute(){
    if(server.isSnowing){
      player.message("It is currently snowing!");
    }
    else{
      player.message("It is not currently snowing!");
    }
  }
}
```

