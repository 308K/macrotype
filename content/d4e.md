---
title: "泛用设计实施情况"
layout: "single"
hideMeta: true
disableShare: true

---

我们的目标是「为所有人准备」，因此在设计之初充分应用了**泛用设计**（Design for All, D4A）理念，旨在预防性设计并为所有人提供公平使用的机会。日后我们会专门撰写文章来介绍泛用设计。

目前我们的的泛用设计实施情况如下：

### WCAG（Web内容无障碍指南）

- 我们采取的是WCAG AA+策略，即在满足WCAG 2.2 AA级别的所有要求的前提下，适当吸收更高级（AAA级别）的要求，包括但不限于：
  - [1.4.6 增强对比度（Contrast (Enhanced) (Level AAA)）](https://www.w3.org/WAI/WCAG21/Understanding/contrast-enhanced.html)
  
  - [1.4.8 视觉呈现（Visual Presentation (Level AAA)）](https://www.w3.org/WAI/WCAG21/Understanding/visual-presentation.html)
  
    > 注：此项要求超额完成，本站在文本大小调整至500%时，用户无需水平滚动仍可[在全屏窗口中](https://www.w3.org/WAI/WCAG21/Understanding/visual-presentation.html#dfn-on-a-full-screen-window)顺畅阅读一行文本，但**不建议**这么做。
  
  - [2.2.4 消除打扰（Interruptions (Level AAA)）](https://www.w3.org/WAI/WCAG21/Understanding/interruptions.html)
  
  - [2.4.9 纯文本说明链接目的（Link Purpose (Link Only) (Level AAA)）](https://www.w3.org/WAI/WCAG22/Understanding/link-purpose-link-only.html)
  
  - [2.4.12 更清晰的焦点（Focus Not Obscured (Enhanced) (Level AAA)）](https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-enhanced.html)
  
- 目前本站能通过WCAG 2.2 AAA级别的所有自动化测试；

- 几乎满足未来WCAG 3的要求。

### 针对视觉障碍用户

**充分兼容屏幕阅读器和盲文显示器**。本站在符合WCAG要求的前提下吸收社区最佳实践，优先使用原生HTML语义化标签并尽可能避免使用ARIA，同时提供地标（Landmarks）。

### 针对神经多元用户

本站不含弹窗、横幅、动效、轮播图等任何可能打扰到您的元素（见上条）。同时，我们坚持一篇文章只讲清一个问题，使用短小的段落并控制总字数。如迫不得已，我们会为总字数超过3000字的文章提供内容摘要，最大程度上降低您的认知负担。

### 针对网络状况不佳的用户

- 除了展示新版Unicode字符等**极端必要**的情况外，我们仅使用您本地的字体，不会加载网络字体；
- 我们仅会在服务于写作目的需要时插入图片，不会使用任何无必要的装饰性图片，并严格控制图片体积。

### 针对重视隐私的用户

- 我们不使用Cookies或任何同类技术；
- 我们的网站托管在Cloudflare的基础设施上，并使用同样由Cloudflare提供且承诺隐私优先的Cloudflare Web Analytics，此举能最大程度降低您的个人信息暴露范围；
- 受限于存储成本，我们不会保留日志；

- 我们不会添加任何可能会跟踪用户的社交媒体组件，包括但不限于X（原Twitter）和Meta（原Facebook）的等，仅有的X主页和GitHub仓库链接不含跟踪功能；
- 您可在不启用JavaScript的情况下浏览本站并使用绝大多数功能，除了「搜索」，该功能高度依赖JavaScript。如有必要，您可在任何综合类搜索引擎中使用`site`语句来搜索本站内容。
