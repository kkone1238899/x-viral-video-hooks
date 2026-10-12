# 标题 / 5 秒钩子

> 视频前 5 秒留不住人？这个库收集 X 上实战博主验证过的标题和开场钩子方法，每条都写清楚能帮你解决什么、怎么用它搞钱。
>
> A curated collection of titles & 5-second hooks prompts & skills for viral short videos, gathered from practitioners sharing on X.
> 
> Each entry answers two questions: what problem it solves (and who it's for), and how to make money with it.
> 
> Star counts verified via GitHub API on 2026-10-12. Continuously updated.

## 条目

| 项目 | Star | 一句话（解决什么问题 / 适合谁用） | 怎么用它搞钱 |
|---|---|---|---|
| [rediumvex/ai-video-generator-claude](https://github.com/rediumvex/ai-video-generator-claude) | 410 | 10 个 Claude skill，含 viral hooks（Seedance/Higgsfield） | 爆款混剪接单 |
| [rediumvex/viral-hooks-skill](https://github.com/rediumvex/viral-hooks-skill) | 101 | Claude Code skill：100 个钩子公式 × 10 种心理触发（好奇缺口/反常识/权威背书等），贴脚本出 3 个止滑版开头 | 剪辑单/代运营加"开头诊断"增值服务按条收费 |
| [shixinzhang/tiktok-viral-hooks](https://github.com/shixinzhang/tiktok-viral-hooks) | 33 | 每天拆一条爆款 TikTok：精确 3 秒开场 + 留住人的 retention 动作 + 可复制脚本模板，中英双语 | 照模板日更起号接广告，或整理成钩子题材库卖给剪辑/编剧从业者 |
| [artemnovitckii/content-skills](https://github.com/artemnovitckii/content-skills) | 102 | 5 个 Claude Code skills，其中 viral-hooks 审计开场四大致死点并改写（另含去 AI 味、人声 DNA） | 把 hook 诊断接到脚本代做流程里，做成"开头体检报告"差异化报价 |
| [ehui1226/hookmeter-jev](https://github.com/ehui1226/hookmeter-jev) | 22 | Chrome 插件：毫秒级给 X/Twitter 文案打钩子引力分，写标题时实时测、不断创作心流 | 发帖前全测一遍提点击率，或打包进自媒体培训课卖课 |

### X 实战帖 · 核心提炼

> 以下条目均已提炼：不点链接也能拿走 80% 干货，原帖链接只做署名出处。

### @joshfpocock：13 个免费 Claude skills 含 26 个 hook formulas

> 该帖分享的是作者本人的 GitHub 开源项目，以下根据项目 README 提炼。

**核心提炼**
- 13 个 skills 覆盖 Instagram 全链路：写 Reels、找爆款、写 caption、做轮播、排周计划、修主页……不是单个钩子工具，而是一套账号操作系统
- 26 个钩子公式 + 打分机制：`/ig-reel` 从 26 个公式生成 3 个开头，用 hookscore.py 按 5 个维度（具体性、利害关系、指向性、前置程度等）打分，弱钩子直接毙掉再拍
- 节拍表先行：beats.py 先算每句台词时长、排好时间轴，提前标出 4 个致命问题（钩子超 3 秒、单节拍过长、内容空洞、没有回扣），拍摄前就知道节奏对不对
- 去 AI 味是标配：humanizer 自动清除零宽字符、破折号、154 个 AI 味词汇，再打分确认
- 找爆款的方法：不看绝对播放量，看"超过该账号自己中位数的倍数"——小号的爆款比大号的爆款更有参考价值
- 作者实测结论：打分器能很好地筛掉烂钩子，但选不出哪个"好钩子"会爆——工具用来避坑，不用来押宝

**适用场景**：做 Reels/短视频、每次为开头 3 秒纠结的创作者。

**怎么用它搞钱**：用这套技能批量生产爆款开头做矩阵号，或把"26 钩子公式包"整理卖给内容创作者。

**来源**：[@joshfpocock](https://x.com/joshfpocock/status/2109413987439767596) · 项目：[Jakeschincariol/instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill)

### @joshfpocock：11 个免费 Claude skills 含 21 个 hook formulas

> 该帖分享的是作者本人的 GitHub 开源项目，以下根据项目 README 提炼。

**核心提炼**
- 11 个 skills 覆盖 YouTube 全链路：写脚本、标题+缩略图打包、剪辑决策、评论区运营、留存分析、Shorts 挖掘
- 21 个钩子公式 + 打分：`/yt-script` 从 21 个公式生成 5 个开头并打分，拍之前先筛一遍
- 标题和缩略图当一对来打磨：分开写会导致点击面重复说同一件事，打包检查截断、重复和模糊
- 留存分析找真因：读你的观众留存导出数据，定位观众具体在哪一秒流失、当时在讲什么，而不是凭感觉改
- 剪辑决策表：把 transcript 转成带时间码的剪辑清单（删静音、删 filler、标重拍），剪辑不再靠肉眼
- 长视频里藏着 Shorts：自动找出长视频里适合切 Shorts 的片段并重写开头，一鱼多吃
- 作者的诚实声明：打分是启发式不是预测器，低分值得重看，高分不保证爆

**适用场景**：做 YouTube（长视频+Shorts）、想系统优化点击和留存的创作者。

**怎么用它搞钱**：把流失秒数分析做成"频道体检"代诊服务按次收费。

**来源**：[@joshfpocock](https://x.com/joshfpocock/status/2109000001657450663) · 项目：[Jakeschincariol/youtube-agent-skill](https://github.com/Jakeschincariol/youtube-agent-skill)

### @alexolim_：334+ 验证过的 viral hook 模板

**核心提炼**
- 方法论是亮点：不是凭感觉编的 334 条，是团队分析 10 万+ 真实社媒帖子筛出来的，有数据背书
- "验证过"的含义：这些模板在真实帖子中跑出过数据，不是理论推导
- 领取方式：免费，但要邮箱订阅——用邮箱换模板，典型的获客钩子，学的是这个获客设计也值
- 用法：按场景分类挑模板，填入自己的关键词就是一条新钩子
- 334 这个量级的意义：覆盖足够多场景，不用再为"开头说什么"卡壳

**适用场景**：每天需要大量产出开头、灵感枯竭的内容创作者和代运营。

**怎么用它搞钱**：领回模板库，给客户做"钩子换装"批量代写，或卖给做带货/引流的商家。

**来源**：[@alexolim_](https://x.com/alexolim_/status/2109049029355004159)

## 收录标准

- 来源：X 博主实战分享（原帖 / 评论区 / 引用链）及 GitHub 高星项目
- GitHub 项目条目格式：一句话（解决什么问题 / 适合谁用）+ 一条「怎么用它搞钱」
- X 实战帖条目格式：核心提炼（3-8 条要点，不点链接也能拿走干货）+ 适用场景一句话 + 一条「怎么用它搞钱」+ 原帖链接只做署名出处
- Star 数为 2026-10-12 经 GitHub API 核验；持续收录中
- 去重：同一项目只收录一次，不堆 raw 链接

## 相关分类

- 总索引：[x-viral-video-skills](https://github.com/kkone1238899/x-viral-video-skills) —— 13 个分类导航
- [x-viral-video-scripts](https://github.com/kkone1238899/x-viral-video-scripts) —— 编剧 / 脚本
- [x-viral-video-creative-direction](https://github.com/kkone1238899/x-viral-video-creative-direction) —— 创意总监
- [x-viral-video-directing](https://github.com/kkone1238899/x-viral-video-directing) —— 导演
- [x-viral-video-replication](https://github.com/kkone1238899/x-viral-video-replication) —— 复制爆款
- [x-viral-video-breakdown](https://github.com/kkone1238899/x-viral-video-breakdown) —— 拉片
- [x-viral-video-pipeline](https://github.com/kkone1238899/x-viral-video-pipeline) —— 流水线 / 生产管线
- [x-viral-video-de-ai](https://github.com/kkone1238899/x-viral-video-de-ai) —— 去 AI 味
- [x-viral-video-characters](https://github.com/kkone1238899/x-viral-video-characters) —— 人物构建
- [x-viral-video-editing](https://github.com/kkone1238899/x-viral-video-editing) —— 视听剪辑技巧
- [x-viral-video-prompt-opt](https://github.com/kkone1238899/x-viral-video-prompt-opt) —— 提示词优化
- [x-viral-video-copywriting](https://github.com/kkone1238899/x-viral-video-copywriting) —— 文案
- [x-viral-video-showcase](https://github.com/kkone1238899/x-viral-video-showcase) —— X 病毒视频合集

## 投稿

发现好的标题 / 5 秒钩子 prompt / skill，欢迎提 Issue 或 PR（格式见 CONTRIBUTING.md）。

## 更新日志

- 2026-10-11：首版，1 个项目，持续收录中
- 2026-10-12：首轮早档搜集：X 新增 3 条实战帖（@joshfpocock 13 个 skills 含 26 钩子公式、@joshfpocock 11 个 skills 含 21 钩子公式、@alexolim_ 334+ 验证钩子模板；@Chel2336 漫剧 63 讲已收录于编剧库，此处去重）、GitHub 新增 4 个项目（rediumvex/viral-hooks-skill、shixinzhang/tiktok-viral-hooks、artemnovitckii/content-skills、ehui1226/hookmeter-jev）；全库 star 经 API 核验更新
- 2026-10-12：X 实战帖整改（kk 指令）：3 条 X 条目全部按"提炼入库"标准重写为核心提炼小节（要点+适用场景+搞钱+出处），不再是标题+链接
