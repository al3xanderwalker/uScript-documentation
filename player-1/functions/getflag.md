# getFlag

* Parameters: \[id\]
* Extra: \[unsure if this is correct usage\]

> #### Example:

```css
command getFlag(id){
  permission = "getFlag";
  execute(){
    flagID = toNumber(id);
    player.getFlag(flagID);
    player.message("You have been given flag with id " + id);
  }
}
```

