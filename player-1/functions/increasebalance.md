# increaseBalance

* Parameters: \[amount\]
* Requires: Uconomy

> #### Example:

```css
command increaseBalance(amount){
  permission = "increaseBalance";
  execute(){
    player.increaseBalance(amount);
    player.message("Your balance has been increased by " + amount);
  }
}
```

