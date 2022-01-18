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





