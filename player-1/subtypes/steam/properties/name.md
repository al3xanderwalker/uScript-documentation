# name

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command steamName(){
    permission = "steamName";
    execute(){();
      steamName = player.steam.name;
      player.message("Your steam accounts name is " + steamName);
    }
}
```

