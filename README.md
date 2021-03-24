# Phaser Spritesheet Fixer

Phaser Spritesheet Fixer in JavaScript using WebGL. Just select the spritesheet image file, set the tileWidth and tileHeight values and the Web will generate a new image (spritesheet) with a 1px margin in each tile. 

## Web:

https://lrusso.github.io/PhaserSpritesheetFixer/PhaserSpritesheetFixer.htm

## Updating your spritesheet code

```diff
-this.load.spritesheet("dog", dogSprite, 32, 32, 30);
+this.load.spritesheet("dog", dogSprite, 32, 32, 30, 1, 2);
```

## Test.png Spritesheet - Before

![alt screenshot](https://raw.githubusercontent.com/lrusso/PhaserSpritesheetFixer/master/TestBefore.png)

## Test.png Spritesheet - After

![alt screenshot](https://raw.githubusercontent.com/lrusso/PhaserSpritesheetFixer/master/TestAfter.png)

## See also:

https://github.com/lrusso/PhaserSpritesheetGenerator
