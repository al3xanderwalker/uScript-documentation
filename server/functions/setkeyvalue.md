# setKeyValue

* Parameters: \[string\_key\], \[string\_value\]
* Extra: \[unsure if this is correct usage\]

> #### Server Configuration Keys:

Lines are important you need to set a specific amount of line for your text or it wont show up. \(Set lines to 0 to hide text\)

"rocketplugins" - Server Rocket plugins list text.

"Browser\_Server\_Count" - Server description line count.

"Browser\_Server\_Line" - Server description text.

"Browser\_Workshop\_Count" - Workshop list line count.

"Browser\_Workshop\_Line" - Workshop list text.

"Browser\_Config\_Count" - Server configuration line count.

"Browser\_Config\_Line" - Server configuration text.

> #### Example:

```css
command setKeyValue(key, value){
  permission = "setBotPlayerCount";
  execute(){
    server.setKeyValue(key, value);
    player.message("Set server key value " + key + " to " + value);
  }
}
```

