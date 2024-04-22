# Mindjourney 更新记录

---

### v 5.2 新增了什么内容?



##### 

#### **新的美学系统**

- 图片美观度和清晰度提升
- 文本理解和连贯性略微提高
- 图像多样性增加(有时你可能需要多次尝试才能得到想要的结果，对此表示歉意!)
- 已修复的 --stylize 命令，能够明显改变应用到图像的风格化程度(更像是 V3 版本的效果)。这个命令的取值范围从 --stylize 0 到 --stylize 1000，默认值是 --stylize 100。

#### 新的"高差异性模式"

- 默认开启，使所有的任务展示出更高的差异性。
- 若要切换此模式，请输入 /settings 并点击另一种变异模式。
- 在所有放大的图片下面，你还可以选择你想要的变异强度。

![img](https://cdn.jsdelivr.net/gh/misu198/Midjourney@main/guge/a600751377cfc0a1713448746.png_q900)

![img](https://cdn.jsdelivr.net/gh/misu198/Midjourney@main/guge/ebb7c1732c639631713448746.png_q900)

新的 /shorten 命令

- 这个命令可以让你“分析”一个提示，获取可能无效的词汇建议以及可能关键的词汇。

[学习 shorten]

![img](https://cdn.jsdelivr.net/gh/misu198/Midjourney@main/guge/20a60f6040dfd351713448757.png_q900)

新的 "视角扩大" 功能

- 所有放大的图片下面现在都有 '视角扩大 ' 按钮，你可以用它来重新构建图像
- [视角扩大 1.5倍] 和 [视角扩大 2倍] 按钮能将视角拉远，并在所有侧边填充细节
- [使之成方] 可在两侧添加细节，将非方形的图像转化为方形
- [自定义视角扩大](高级功能)可以弹出一个文本框，让你在视角扩大的同时更改提示、纵横比或精确的放大倍数。要改变纵横比，请设定 --zoom 1，然后将 --ar 修改为你想要的目标。这个选项会尝试移除你之前图像上的黑边。

[学习 zoom out ]

![img](https://cdn.jsdelivr.net/gh/misu198/Midjourney@main/guge/7af7d5ed36537571713448746.png_q900)

请注意：

- 在未来的几周内，我们可能会在没有通知的情况下进行修改。
- 我们默认开启 V5.2 版本以进行最大范围的测试。
- 你可以随时通过输入 /settings 并点击 V5.1 版本进行回退。
- 高变异模式仅限于 V5.2 版本
- /Shorten 命令不支持多个提示

我们希望你喜欢新的实验性功能。请在⁠ ideas-and-features 下给我们反馈，或在⁠ show-and-tell 中展示你的新作品。

祝你玩得开心!<3