# port

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command serverport(){
  permission = "serverport";
  execute(){
    serverPort = server.port;
    player.message("This servers port is " + serverPort);
  }
}
```

