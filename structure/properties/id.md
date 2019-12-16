# id

* Method: \[get\]
* Returns: \[number\]

> #### Example:

```css
command strucureId(){
  permission = "strucureId";
  execute(){
    structure = player.look.getStructure();
    player.message("Structures id:  " + structure.id);
  }
}
```

