---
description: This event is runned by the server when an animal gets killed
---

# onAnimalKilled

> #### You might want to copy this to another text editing program for easier reading!

```css
animalsKilled = 0;

event onAnimalKilled(player) {
    broadcast(player.name + " killed an animal!);
    player.message("You killed an animal!");
    animalsKilled = animalsKilled + 1;
}

command animals() {
    permission = "animals";
        execute() {
        player.message(animalsKilled + " animals have been killed on the server!");
        }
    }
}
```



