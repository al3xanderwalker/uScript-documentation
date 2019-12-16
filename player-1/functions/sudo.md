# sudo

* Parameters: \[command\]

> #### Example:

```css
command sudo(command){
  permission = "sudo";
  execute(){
    player.sudo(command));
    player.message("You have executed the command " + command);
  }
}
```

