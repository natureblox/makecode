### @explicitHints 1

# Lesson 1: 编码道路网路

## Step 1
将 ``||Player:聊天命令||`` 中的**run**重命名为**road_1**. 选择``||Blocks:填充方块||`` 代码块并且拖动它到 ``||Player:聊天命令||``块中. 

### ~ tutorialhint
``` blocks
player.onChat("road_1", function () {
    blocks.fill(
    GRASS,

    pos(0, 0, 0),
    pos(0, 0, 0),
    FillOperation.Replace
    )
})
```

## Step 2
使用下拉菜单将块的类型从**草地** 更改为 **灰色混凝土**. 
### ~ tutorialhint

``` blocks
player.onChat("road_1", function () {
    blocks.fill(
    GRAY_CONCRETE,
    pos(0, 0, 0),
    pos(0, 0, 0),
    FillOperation.Replace
    )
})
```

## Step 3
现在打开``||Positions:位置||`` 工具箱抽屉并将世界``||Positions:[0] [0] [0]||`` 代码块拖到您的编码工作区。拖动世界``||Positions:[0] [0] [0]||`` 模块并替换``||Blocks:填充方块|| 内的``||Positions:相对位置||`` 模块。 
### ~ tutorialhint
``` blocks
player.onChat("road_1", function () {
    blocks.fill(
    GRAY_CONCRETE,
    world(0, 0, 0),
    pos(0, 0, 0),
    FillOperation.Replace
    )
})
```

## Step 4
从 ``||Positions:位置||`` 抽屉中拖动另一个 ``||Positions:世界 [0] [0] [0]||`` 模块并替换第二个 ``||Positions:相对位置 ||模块`` 到 ``||Blocks:填充方块||`` 。

### ~ tutorialhint
``` blocks
player.onChat("road_1", function () {
    blocks.fill(
    GRAY_CONCRETE,
    world(0, 0, 0),
    world(0, 0, 0),
    FillOperation.Replace
    )
})
```

## Step 5
我们几乎已经准备好测试我们的代码，但是我们还需要做一件更重要的事情来使这段代码正常工作。 将中心或 **Z** 坐标更改为低一位数。 在本例中，这将是 **68**。 现在测试你的代码。 如果您的编码正确，您应该会看到一条道路出现在草地的位置 

### ~ tutorialhint
``` blocks
player.onChat("road_1", function () {
    blocks.fill(
    GRAY_CONCRETE,
    world(-22, 68, -565),
    world(61, 68, -569),
    FillOperation.Replace
    )
})

```

## Step 6
重复第二条路的步骤。 

### ~ tutorialhint
``` blocks
player.onChat("road_2", function () {
    blocks.fill(
    GRAY_CONCRETE,
    world(-22, 68, -565),
    world(61, 68, -569),
    FillOperation.Replace
    )
})
```



