# experience

* Method: \[get\]
* Returns: \[number\]

> Example:

```css
command experience(){
  permission = "experience";
  execute(){
    player.message("You have " + player.experience + " experience!");
  }
}
```

* Method: \[set\]
* Returns: \[number\]

> Example:

```css
command setExperience(amount){
  permission = "setExperience";
  execute(){
    amount = toNumber(amount);
    player.experience = amount;
    player.message("Experience set to " + player.experience);
  }
}
```

