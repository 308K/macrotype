+++
title = "除了日本地图「🗾」还有没有地图/疆域Emoji？"
date = 2026-04-20
categories = ["字符编码"]
tags = ["绘文字"]

+++

 答案是没有了。这个Emoji进入Unicode仅出于向后兼容考虑，它本身不符合Unicode收录字符的原则，日后Unicode也不会接受新的国家版图/地图轮廓Emoji提案。
2009年1月，谷歌和苹果向Unicode提交了一个草案[L2/09-026](https://unicode.org/L2/L2009/09026-emoji-proposed.pdf)，意在使Unicode兼容早期日本手机运营商（KDDI、DoCoMo、SoftBank）的自有Emoji，MAP OF JAPAN（当时的码位是`U+1F3D9`）也在列，用于兼容KDDI Shift-JIS的码位`F3C7`和SoftBank Shift-JIS的码位`FBA1`（完整列表见[L2/09-078](https://www.unicode.org/L2/L2009/09078-emoji-sources.txt)和[N3728R](https://www.unicode.org/wg2/docs/n3728.pdf)）。

在2009年中期的ISO/WG2和Unicode技术委员会会议上，委员们对于如何处理这些「过于具有本土特色」的Emoji产生了分歧。有一段时间，委员会倾向于把这类符号当成纯粹的、无具体语境的向后兼容占位符，不赋予其明确名称。因此，在这一时期的草案中，它的名字被改成了`EMOJI COMPATIBILITY SYMBOL-4`，并且码位被挪到了`U+1F563`。

到了2009年下半年，情况再次发生反转。包括爱尔兰和德国在内的国家工作组提出强烈抗议，认为使用无意义的编号违反了Unicode字符命名的标准原则。他们要求名字必须反映符号的字面视觉外观，而不是它的抽象概念或用途。由于它在视觉上本质上只是日本列岛的图形剪影，于是名字定为`SILHOUETTE OF JAPAN`，同时为了给其他符号腾位置，它从`U+1F563`被移到了现在的`U+1F5FE`。（[L2/09-412](https://www.unicode.org/L2/L2009/09412-n3722.pdf)）
可以看看它和它的邻居，都是经历了相同提案周期的难兄难弟：

```
U+1F5FB 🗻 MOUNT FUJI
U+1F5FC 🗼 TOKYO TOWER
U+1F5FD 🗽 STATUE OF LIBERTY
U+1F5FE 🗾 SILHOUETTE OF JAPAN
U+1F5FF 🗿 MOYAI
```

另外，为了满足表达国家身份的需求，且不用给每个国家画地图或分配单独的国旗码位，Unicode使用[Emoji Flag Sequence / Regional indicator symbol](https://en.wikipedia.org/wiki/Regional_indicator_symbol)来解决，比如中国国旗（🇨🇳）在底层其实是两个字母符号 🇨 和 🇳 拼合而成的。这是一种可扩展的技术解决方案。

