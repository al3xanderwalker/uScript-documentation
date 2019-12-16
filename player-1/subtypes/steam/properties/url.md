# url

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command openProfile(){
    permission = "openProfile";
    execute(){();
      player.browserRequest("Your Steam Profile", player.steam.url);
    }
}
```

