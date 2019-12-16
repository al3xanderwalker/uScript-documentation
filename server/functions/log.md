# log

* Parameters: \[text\]

> #### Example:

```css
command log(){
  permission = "log";
  execute(){
    message = str.join(arguments);
    server.log(message);
    player.message("Logged message:  " + message);
  }
}
```

