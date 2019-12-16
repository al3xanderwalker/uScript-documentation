# name

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command serverName(){
  permission = "serverName";
  execute(){
    serverName = server.name;
    player.message("This server is called " + serverName);
  }
}
```

* Method: \[set\]
* Returns: \[string\]

> #### Example:

```css
command setServerName(name){
  permission = "setServerName";
  execute(){
    server.name = name;
    player.message("The servers name has been changed to " + serverName);
  }
}
```

