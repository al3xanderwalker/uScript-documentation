# getSign

* Method: \[get\]
* Returns: \[sign\]

> #### Example:

```css
command signSays(){
  permission = "signSays";
  execute(){
    barricade = player.look.getBarricade();
    sign = barricade.getSign();
    text = sign.text;
    player.message("Sign says: " + text);
  }
}
```

