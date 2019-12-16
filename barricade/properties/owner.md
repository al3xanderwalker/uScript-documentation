# owner

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command barricadeOwner(){
  permission = "barricadeOwner";
  execute(){
    barricade = player.look.getBarricade();
    player.message("Barricades owners steam id:  " + barricade.owner);
  }
}
```

* Method: \[set\]
* Returns: \[string\]

> #### Example:

```css
command setbarricadeOwner(ownerId){
  permission = "setbarricadeOwner";
  execute(){
    barricade = player.look.getBarricade();
    barricade.owner = ownerId;
    player.message("Barricades owner set to " + barricade.owner);
  }
}
```

