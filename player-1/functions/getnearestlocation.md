# getNearestLocation

* Parameters: \[none\]

> #### Example:

```css
command near(){
  permission = "near";
  execute(){
    nearestLocation = player.getNearestLocation();
    player.message("Your nearest location is " + nearestLocation);
  }
}
```

