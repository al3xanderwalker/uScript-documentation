# setFlag

* Parameters: \[id\], \[value\]
* Extra: \[unsure if this is correct usage\]

> #### Example:

```css
command setFlag(id, value){
  permission = "setFlag";
  execute(){
    flagID = toNumber(id);
    player.setFlag(flagID, value);
    player.message("You have been given flag with id " + id + " its value is " + value);
  }
}
```

