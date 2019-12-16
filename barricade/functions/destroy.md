# destroy

* Parameters: \[none\]

> #### Example:

```css
command destroyBarricade(){
  permission = "destroyBarricade";
  execute(){
    barricade = player.look.getBarricade();
    barricade.destroy();
    player.message("Barricade Destroyed!");
  }
}
```

