# setBotPlayerCount

* Parameters: \[string\]
* Extra: \[unsure if this is correct usage\]

> #### Example:

```css
command setBotPlayerCount(amount){
  permission = "setBotPlayerCount";
  execute(){
    count = toNumber(amount);
    server.setBotPlayerCount(count);
    player.message("Set server bot count to " + count);
  }
}
```

