# Phaser Spritesheet Fixer

Phaser Spritesheet Fixer in JavaScript using WebGL.

## How does it work?

* Select the spritesheet image file.
* Set the tileWidth and tileHeight values.
* Download the generated spritesheet image that will have with a 1px margin in each tile.

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

https://github.com/lrusso/PhaserSpritesheetCutter
