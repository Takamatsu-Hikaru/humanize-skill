# GitHub 参考与选择

核对日期：2026-10-12。以下是本技能创建时阅读的上游文档，工具能力和入口以后可能变化，实际使用前按需核对。技能主体根据用户的真实编辑案例独立编写，未复制上游实现，也不自动安装这些仓库。

## 文案

[blader/humanizer](https://github.com/blader/humanizer) · [技能正文](https://github.com/blader/humanizer/blob/main/SKILL.md)

借鉴其关注文章结构、保留作者语气和事实的做法。这里更重视中文指南的叙事、资源组织和用户提供的 before / after。不上来套一张禁词表，不使用检测分数，也不默认向用户展示草稿、自评、终稿三轮内容。

## 文章配图

[baoyu-article-illustrator](https://github.com/JimLiu/baoyu-skills/blob/main/skills/baoyu-article-illustrator/SKILL.md)

值得参考的是根据内容选择插图位置，并协调图的形式、风格和颜色。本技能自行判断图的需要和密度，不默认每节一张。需要原图、截图或精确机制图时，按材料选工具，不把文章配图等同于生成装饰插画。上游的初始化和确认流程没有作为本技能的依赖导入。

## 公众号转换

[baoyu-markdown-to-html](https://github.com/JimLiu/baoyu-skills/blob/main/skills/baoyu-markdown-to-html/SKILL.md)

上游提供带内联样式的 HTML 转换及可选文末引用，也涉及公式和图表的呈现。实际选择该工具时读取当前安装版本，检查输出的图片是否仍是待替换占位符。主题名称不能代替视觉判断，按用户已有排版样例选择和调整。

[doocs/md](https://github.com/doocs/md) · [在线编辑器](https://md.doocs.org/)

适合 Markdown 的公众号预览和样式调整。创建本技能时已阅读仓库说明；尚未在用户的公众号账号内做导入验证。需要交互式排版时可使用其编辑器，已有本地流程时不必专门迁移。不要因为编辑器有很多样式，就将所有装饰放进同一篇文章。

## 使用范围

本技能默认不依赖上述仓库的安装状态。需要新依赖时按当前任务、运行环境和适用安装规则处理。排版、保存公众号草稿和正式群发是不同动作，用户的当前授权决定执行范围；创建这个技能本身不执行这些外部操作。
