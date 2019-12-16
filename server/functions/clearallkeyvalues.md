# clearAllKeyValues

* Parameters: \[none\]

> #### Example:

```css
command resetServerInfo(number){
  permission = "resetServerInfo";
  execute(){
    server.clearAllKeyValues();
    player.message("The server information has been reset!");
  }
}
```

