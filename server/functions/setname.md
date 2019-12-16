# setName

* Parameters: \[string\]
* Extra: \[unsure if this is correct usage\]

> #### Example:

```css
command setServerName(){
  permission = "setServerName";
  execute(){
    serverName = str.join(arguments);
    server.setName(serverName);
    player.message("Set server name to " + serverName);
  }
}
```

