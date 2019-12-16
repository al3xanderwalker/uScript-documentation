# id

* Method: \[get\]
* Returns: \[number\]

> #### Example:

```css
command barricadeId(){
  permission = "barricadeId";
  execute(){
    barricade = player.look.getBarricade();
    player.message("barricades id:  " + barricade.id);
  }
}
```

