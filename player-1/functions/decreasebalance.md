# decreaseBalance

* Parameters: \[amount\]
* Requires: Uconomy

> #### Example:

```css
command decreaseBalance(amount){
  permission = "decreaseBalance";
  execute(){
    player.decreaseBalance(amount);
    player.message("Your balance has been decreased by " + amount);
  }
}
```

