# time

* Method: \[get\]
* Returns: \[number\]

> #### Example:

```css
command serverTime(){
  permission = "serverTime";
  execute(){
    serverTime = server.time;
    player.message("The servers time is  " + serverTime);
  }
}
```

* Method: \[set\]
* Returns: \[number\]

> #### Example:

```css
command setServerTime(number){
  permission = "setServerTime";
  execute(){
    newTime = toNumber(number);
    server.time = newTime;
    player.message("The servers time has been changed to " + server.time);
  }
}
```

