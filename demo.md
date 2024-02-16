# Заголовок

## Step One @unplugged

Unplugged tutorial modal.

## Step Two

Add the ``||player:on chat command||`` block and change the command to **text**.

```blocks
player.onChat("text", function () {
})
```

## Step Three

Add the ``||mobs:spawn||`` block to spawn an animal.

```blocks
player.onChat("text", function () {
    mobs.spawn(COW, pos(0, 0, 0))
})
```

## Step Four

Good job!