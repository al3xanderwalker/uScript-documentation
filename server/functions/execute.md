# execute

* Parameters: \[command\]

> #### Example:

```css
command execute(){
  permission = "execute";
  execute(){
    command = str.join(arguments);
    server.execute(command);
    player.message("Server has executed command " + command);
  }
}
```

