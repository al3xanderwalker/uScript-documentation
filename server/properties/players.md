# players

* Method: \[get\]
* Returns: \[array of players\]

> #### Example:

```css
command listPlayers(){
  permission = "listPlayers";
  execute(){
    for(player in server.players){
      player.message(player.name);
    }
  }
}
```

