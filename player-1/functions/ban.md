# ban

* Parameters: \[text\], \[duration\]

> #### Example:

```css
command banMe(reason, length){
  permission = "banMe";
  execute(){
    length = toNumber(length)
    player.ban(reason, length);
  }
}
```

