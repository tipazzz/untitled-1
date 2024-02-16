# Tutorial Titel

## Schritt Eins @unplugged

Unplugged Tutorial modal.

## Schritt zwei

Fügen Sie den Block ``||игрок: прикоманде чата||`` hinzu und ändern Sie den Befehl in ** text **.

```blocks
player.onChat("text", function () {
})
```

## Schritt drei

Fügen Sie den Block ``||mobs:spawn||`` hinzu, um ein Tier zu spawnen.

```blocks
player.onChat("text", function () {
    mobs.spawn(COW, pos(0, 0, 0))
})
```

## Schritt vier

Gut gemacht!
