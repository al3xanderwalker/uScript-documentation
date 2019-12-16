# isMoving

* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isMoving(){
    permission = "isMoving";
    execute(){();
      if(player.movement.isMoving){
        player.message("You are currently moving!");
      }
      else{
          player.message("You are not currently moving!");
      }
    }
}
```

