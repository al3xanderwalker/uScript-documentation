# avatarUrl

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command avatarUrl(){
    permission = "avatarUrl";
    execute(){();
      player.browserRequest("Your avatar url", player.steam.avatarUrl);
    }
}
```

