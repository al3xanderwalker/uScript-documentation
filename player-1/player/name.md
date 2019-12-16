# name

* Method: \[get\]
* Returns: \[string\]

> Example:

```css
command name(){
  permission = "name";
  execute(){
    player.message("Your name is " player.name);
  }
}
```

* Method: \[set\]
* Returns: \[string\]

> Example:

```css
command setName(newName){
  permission = "setName";
  execute(){
    player.name = newName;
    player.message("Name set to " + player.name);
  }
}
```

