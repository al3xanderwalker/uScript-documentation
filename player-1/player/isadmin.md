# isAdmin

* Method: \[get\]
* Returns: \[boolean\]

> Example:

```css
command isAdmin(){
  permission = "isAdmin";
  execute(){
    if(player.isAdmin){
      player.message("You are an admin!");
    }
    else{
      player.message("You are not an admin!");
    }
  }
}
```

* Method: \[set\]
* Returns: \[boolean\]

> Example:

```css
command toggleAdmin(){
  permission = "toggleAdmin";
  execute(){
    if(player.isAdmin){
      player.isAdmin = false;
      player.message("You are now not admin!");
    }
    else{
      player.isAdmin = true;
      player.message("You are now admin!");
    }
  }
}
```

