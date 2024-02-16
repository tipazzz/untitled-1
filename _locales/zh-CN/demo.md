＃教程标题

## 第一步@unplugged

拔掉教程模态。

## 第二步

添加 ``||player:on chat command||`` 块，并将命令更改为** text **。

```blocks
player.onChat("text", function () {
})
```

## 第三步

添加“ || mobs：spawn ||”块以生成动物。

```blocks
player.onChat（“ text”，function（）{
     mobs.spawn（COW，pos（0，0，0））
}）
```

## 第四步

做得好！
