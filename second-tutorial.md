# Create Enemies

## Introduction @unplugged

Create enemies and spawn them at random locations!

## Step 1

Add an ``||game:on game update every||`` block to the workspace.

```blocks
game.onUpdateInterval(500, function () {
})
```

## Step 2

Use a ``||custom:makeEnemySprite||`` block to make some enemies.

```blocks
game.onUpdateInterval(500, function () {
    // @highlight
    custom.makeEnemySprite(5)
})
```
