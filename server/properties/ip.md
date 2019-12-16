# ip

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command serverip(){
  permission = "serverip";
  execute(){
    serverip = server.ip;
    player.message("This servers ip is " + serverip);
  }
}
```

