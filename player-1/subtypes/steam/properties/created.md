# created

* Method: \[get\]
* Returns: \[datetime\]

> #### Example:

```css
command yearCreated(){
    permission = "yearCreated";
    execute(){();
      created = player.steam.created;
      player.message("Your account was created on " + created.string);
    }
}
```

