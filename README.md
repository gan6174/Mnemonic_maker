# Mnemonic_maker

非常傻逼的口诀生成器，用来辅助记忆背诵。
我们小时候背过这样的组合：
钾钙钠镁铝-捡个大美女
总之就是把关键词的词头编成一句有意义的话，方便记忆。

调用了两个NPL的包，先汉字转拼音。
转成拼音之后做一个全排列，再拼音转汉字。
输出语义得分最高的组合。

样例：

继承的8种形式：特殊、规范、构造、泛化、扩展、限制、变体、结合
输入 特规构泛扩限变结
输出  '特变', '规范', '括线', '结构'
……似乎好记了一点

