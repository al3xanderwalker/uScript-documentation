# damage

* Parameters: \[amount\]

> #### Example:

```css
command damage(amount){
  permission = "damage";
  execute(){
    amount = toNumber(amount);
    player.damage(amount);
    player.message("You have been damaged for " + amount + " health!");
  }
}
```

