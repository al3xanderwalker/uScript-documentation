# name

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command barricadeName(){
  permission = "barricadeName";
  execute(){
    barricade = player.look.getBarricade();
    player.message("Barricades name:  " + barricade.name);
  }
}
```

