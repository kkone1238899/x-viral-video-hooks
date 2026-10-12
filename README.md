# 标题 / 5 秒钩子

> 视频前 5 秒留不住人？这个库收集 X 上实战博主验证过的标题和开场钩子方法，每条都写清楚能帮你解决什么、怎么用它搞钱。
>
> A curated collection of titles & 5-second hooks prompts & skills for viral short videos, gathered from practitioners sharing on X.
> 
> Each entry answers two questions: what problem it solves (and who it's for), and how to make money with it.
> 
> Star counts verified via GitHub API on 2026-10-12. Continuously updated.

## 条目

### rediumvex/ai-video-generator-claude

**核心提炼**
- 解决什么问题：AI 视频生成质量差——Seedance 2.0 这类模型吃"电影级细节"（机位/灯光/音效时间轴），普通人只会写两行话，产出通用烂片。
- 核心用法（4 步）：1) 装 skill：clone 到 `~/.claude/skills`，或跑 `python install.py` 按需装；2) 把想法告诉 Claude（如"10 秒 SaaS 产品发布视频，深色 UI、极简风"）；3) 拿到 15–25 行精密提示词（每秒时间轴 + 机位 + 灯光 + 音效层）；4) 粘贴进 Higgsfield 生成视频。
- 什么时候用 / 常见坑：做产品宣传片、SaaS 演示、前后对比片时用；注意技能默认面向 Seedance 2.0 / Higgsfield，换平台要调参数；想法写得越模糊，产出越平庸。

**适用场景**：做 AI 视频、接产品宣传片生成单的创作者。

**怎么用它搞钱**：爆款混剪接单——用这 10 个 skill（viral hooks、SaaS launch、前后对比等）批量产电影级短视频，接品牌产品视频单。

**来源**：[rediumvex/ai-video-generator-claude](https://github.com/rediumvex/ai-video-generator-claude) · ⭐410 · 更新于 2026-08-11

### rediumvex/viral-hooks-skill

**核心提炼**
- 解决什么问题：脚本写完了，开头 3 秒留不住人；想不出多角度开头。
- 核心用法（4 步）：1) 装 skill：clone 到 `.claude/skills/viral-hooks`；2) 把脚本或主题粘给 Claude，说"写 3 个开头"；3) Claude 从 100 个钩子公式 × 10 种心理触发（好奇缺口/反常识/权威背书等）里挑 3 个，填上你的关键词并标注适合平台；4) 挑一条拍——两个钩子尽量选不同类别，一个止滑一个留存。
- 什么时候用 / 常见坑：写 Reels / TikTok / Shorts 脚本前筛开头时用；注意它是启发式筛选器不是预测器——烂钩子筛得掉，好钩子不保证爆。

**适用场景**：短视频创作者、做脚本代写或剪辑接单的人。

**怎么用它搞钱**：剪辑单/代运营加"开头诊断"增值服务按条收费。

**来源**：[rediumvex/viral-hooks-skill](https://github.com/rediumvex/viral-hooks-skill) · ⭐101 · 更新于 2026-05-05

### shixinzhang/tiktok-viral-hooks

**核心提炼**
- 解决什么问题：知道"标题党"没用，但不知道爆款为什么爆——只看标题学不到结构，也没有可复制的模板。
- 核心用法（3 步）：1) 按赛道（娱乐/财经/美妆/美食/科技等）或钩子模式（好奇缺口/反常识/情绪共鸣等）浏览拆解；2) 每条拆解看三件套：精确 3 秒开场原句 + 7/14/21 秒留存动作 + 2 句话的脚本模板；3) 把自己的主题代入模板，当天发。
- 什么时候用 / 常见坑：起新号缺选题、想研究某个赛道打法时用；中英双语；库还在高频更新，挑和你同赛道的拆解抄。

**适用场景**：TikTok / Reels 起号、做赛道研究的创作者。

**怎么用它搞钱**：照模板日更起号接广告，或整理成钩子题材库卖给剪辑/编剧从业者。

**来源**：[shixinzhang/tiktok-viral-hooks](https://github.com/shixinzhang/tiktok-viral-hooks) · ⭐33 · 更新于 2026-10-12

### artemnovitckii/content-skills

**核心提炼**
- 解决什么问题：Claude 写的文案"一看就是 AI 的"——套话、过度解释、翻案句（"不是 X，而是 Y"）、破折号堆积，怎么改都洗不掉味。
- 核心用法（4 步）：1) 免安装也能用：打开任一 skill 的 SKILL.md，全文复制粘到普通 Claude 对话；2) 按链路叠加：dumbify（降到 8 年级阅读难度）→ storytelling（张力-转折-落点结构）→ viral-hooks（审计开场四大致死点并改写）→ anti-ai-writing（去 AI 味终检）；3) voice-dna：喂 ~20 篇自己的旧帖，让 Claude 学你的语气；4) Claude Code 用户装到 `~/.claude/skills` 后自动触发。
- 什么时候用 / 常见坑：写脚本、caption、帖子觉得"太 AI 腔"时用；注意 viral-hooks 的 A-vs-B 对比和 anti-ai-writing 是配套规则，别拆开互否。

**适用场景**：用 Claude 写文案/脚本、苦于 AI 味洗不掉的创作者。

**怎么用它搞钱**：把 hook 诊断接到脚本代做流程里，做成"开头体检报告"差异化报价。

**来源**：[artemnovitckii/content-skills](https://github.com/artemnovitckii/content-skills) · ⭐102 · 更新于 2026-06-20

### ehui1226/hookmeter-jev

**核心提炼**
- 解决什么问题：写帖子时没人告诉你开头够不够抓人；问大模型打分要等 5–10 秒，打断创作心流。
- 核心用法（3 步）：1) 装 Chrome 扩展（开发者模式加载 extension 文件夹），或自己配 API Key（本地 FastAPI / 免费 Cloudflare Worker 一键部署）；2) 在 X / Twitter 输入框写标题，击键瞬间出分：悬念指数、情绪能量、爆款心理学归类、标题党限流预警；3) 按 10 字内的即时修改处方改开头，再发。
- 什么时候用 / 常见坑：每次发帖写标题/开头前实时测；注意核心评分走 TypeSafe JEV API，需要 key；中文输入法做了防抖对齐，拼音输入中不会误请求。

**适用场景**：高频发帖、需要快速验证标题的 X / Twitter 创作者。

**怎么用它搞钱**：发帖前全测一遍提点击率，或打包进自媒体培训课卖课。

**来源**：[ehui1226/hookmeter-jev](https://github.com/ehui1226/hookmeter-jev) · ⭐22 · 更新于 2026-09-21

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
- 数据驱动：系统分析 100,000+ 社媒帖子，提取"已验证跑通"的 hooks，非经验编造
- 核心主张：UGC 获客关键变量在开头；334+ 模板=把爆款开头结构抽象成可复用句式
- 适用对象：消费级 App 创始人，目标曝光（attention）+安装量（installs）
- 信任状：团队用高产量 UGC 方法论帮"数十个"App 登顶 App Store 第一
- 获客模式即案例：免费资料包换邮箱（lead magnet），5,000+ App 创始人已加入其增长社区
- 如实说明：帖子正文无模板方法细节，334 模板本体在邮件订阅后领取页，未编造

**适用场景**：每天需要大量产出开头、灵感枯竭的内容创作者和代运营。

**怎么用它搞钱**：领回模板库，给客户做"钩子换装"批量代写，或卖给做带货/引流的商家。

**来源**：[@alexolim_](https://x.com/alexolim_/status/2109049029355004159)

## 收录标准

- 来源：X 博主实战分享（原帖 / 评论区 / 引用链）及 GitHub 高星项目
- GitHub 项目条目格式：核心提炼（解决什么问题 / 核心用法 3–5 步：输入→输出、关键步骤 / 什么时候用 / 常见坑）+ 适用场景（适合谁）+ 一条「怎么用它搞钱」+ 来源（项目链接只作来源；star 数与更新时间经 GitHub API 核验）
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
- 2026-10-12：GitHub 项目条目升级（kk 指令）：5 个表格行按铁律改写为核心提炼小节（解决问题 / 核心用法 3–5 步 / 什么时候用 / 常见坑 + 适用场景 + 怎么用它搞钱 + 来源），star 数与更新时间经 API 核验；新项目搜索无达标（宁缺毋滥，未补）
- 2026-10-12：X 实战帖整改（kk 指令）：3 条 X 条目全部按"提炼入库"标准重写为核心提炼小节（要点+适用场景+搞钱+出处），不再是标题+链接
