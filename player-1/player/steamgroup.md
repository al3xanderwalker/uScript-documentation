# steamGroup

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command steamGroup(){
  permission = "steamGroup";
  execute(){
    player.message("Your steam group is " + player.steamGroup);
  }
}
```

* Method: \[set\]
* Returns: \[string\]
* Extra: \[unsure if this is correct usage\]

> Example:

```css
command setSteamGroup(group){
  permission = "setSteamGroup";
  execute(){
    player.steamGroup = group
    player.message("Your steam group has been set to " + player.steamGroup);
  }
}
```

