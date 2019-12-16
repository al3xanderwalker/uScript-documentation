# getPlayer

* Returns: \[player\]

> #### Example:

```css
command playerName(){
    permission = "playerName";
    execute(){
      target = player.look.getPlayer();
      player.message("You are looking at a player called " + target.name);
    }
}
```

