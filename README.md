# 骰宝
这是一款骰宝类游戏
游戏功能：
1. 可选择不同砝码进行投注
2. 点击‘确认下注’自动开奖、计算奖金、派奖，生成历史号码；
3. ‘追注’：自动添加上一次的投注号码,；
4. ‘连投’：选择号码后，添加连续投注期数、中奖是否停止；
该游戏是通过Jquery插件写的，有一定JS基础的应该都是可以做出来的，简单介绍一下思路：
1. 左键添加投注、右键撤销投注：
点击桌面对应区块，在body里生成对应金额的砝码，然后进行位置变化形成投注动画，添加砝码的同时创建一个json存放砝码的属性， 添加到数组中，以方便其他功能的实现。
2. 开奖：
让骰子不停的进行位置的随机变化，形成摇骰子开奖的效果。
3. 判断是否中奖、派奖、添加开奖号码：
把开奖号码添加都数组中，然后进行判断是否中奖。
# 打赏
请我喝杯奶茶吧
<img src="https://leeseean.github.io/source-zone/zfb.jpg" />
<img src="https://leeseean.github.io/source-zone/wx.png" />
