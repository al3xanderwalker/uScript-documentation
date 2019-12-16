# setDescription

* Parameters: \[string\]
* Extra: \[unsure if this is correct usage\]

> #### Example:

```css
command setDescription(){
  permission = "setDescription";
  execute(){
    description = str.join(arguments);
    server.setDescription(description);
    player.message("Set server description to " + description);
  }
}
```

