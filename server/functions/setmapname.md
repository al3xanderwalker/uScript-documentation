# setMapName

* Parameters: \[string\]
* Extra: \[unsure if this is correct usage\]

> #### Example:

```css
command setMapName(){
  permission = "setMapName";
  execute(){
    mapName = str.join(arguments);
    server.setMapName(mapName);
    player.message("Set server map name to " + mapName);
  }
}
```

