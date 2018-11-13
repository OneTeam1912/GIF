# GIF
使用Python生成GIF图
首先，安装imageio库，pip3 install imageio
安装完后，分为三个步骤：
1、读取静态图到列表，作为GIF动态图的每一帧。
2、设置输入（静态图）、输出（GIF）和必要的参数，这里设置每一帧间隔时间为duration=1秒。
3、然后调用imageio库的函数mimsave()即可。
