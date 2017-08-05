# moople.js---html5-library
Library that makes canvas drawing a little bit easier.


Easy to create canvas
```
var game = new moopleGame(800, 800, "canv", {update: update});

// 800 - width, 800 - height,
// "canv" - canvas id
//  update - function that is called 60 times per second
```

Easy to set background color
```
game.setColor("#27ae60");
game.setBackground('starsky.jpg');
```

Easy to load and add sprite
```
game.loadSprite("Cat.png", "Cat");

var sprite = game.addSprite("Cat", 0, 0, 200, 200); // 0 - x, 0 - y, 200 - width and height
```

Changing size and position
```
game.setSize(sprite, 150, 150);
game.setPos(sprite, 0, 100);
```

Creating canvas text
```
text = game.addText('enemy1', 'mytext', '30px Arial', 'red', 200, 100);
1st parameter - text
2nd parameter - id
3rd parameter - font and size
4th parameter - color
5 and 6 - x and y positions
```
