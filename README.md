# 标题 / 5 秒钩子

> 视频前 5 秒留不住人？这个库收集 X 上实战博主验证过的标题和开场钩子方法，每条都写清楚能帮你解决什么、怎么用它搞钱。
>
> A curated collection of titles & 5-second hooks prompts & skills for viral short videos, gathered from practitioners sharing on X.
> 
> Each entry answers two questions: what problem it solves (and who it's for), and how to make money with it.
> 
> Star counts verified via GitHub API on 2026-10-20. Continuously updated.

## 条目

### rediumvex/ai-video-generator-claude

**核心提炼**
- 解决什么问题：AI 视频生成质量差——Seedance 2.0 这类模型吃"电影级细节"（机位/灯光/音效时间轴），普通人只会写两行话，产出通用烂片。
- 核心用法（4 步）：1) 装 skill：clone 到 `~/.claude/skills`，或跑 `python install.py` 按需装；2) 把想法告诉 Claude（如"10 秒 SaaS 产品发布视频，深色 UI、极简风"）；3) 拿到 15–25 行精密提示词（每秒时间轴 + 机位 + 灯光 + 音效层）；4) 粘贴进 Higgsfield 生成视频。
- 什么时候用 / 常见坑：做产品宣传片、SaaS 演示、前后对比片时用；注意技能默认面向 Seedance 2.0 / Higgsfield，换平台要调参数；想法写得越模糊，产出越平庸。

**适用场景**：做 AI 视频、接产品宣传片生成单的创作者。

**怎么用它搞钱**：爆款混剪接单——用这 10 个 skill（viral hooks、SaaS launch、前后对比等）批量产电影级短视频，接品牌产品视频单。

**来源**：[rediumvex/ai-video-generator-claude](https://github.com/rediumvex/ai-video-generator-claude) · ⭐424 · 更新于 2026-10-20

### rediumvex/viral-hooks-skill

**核心提炼**
- 解决什么问题：脚本写完了，开头 3 秒留不住人；想不出多角度开头。
- 核心用法（4 步）：1) 装 skill：clone 到 `.claude/skills/viral-hooks`；2) 把脚本或主题粘给 Claude，说"写 3 个开头"；3) Claude 从 100 个钩子公式 × 10 种心理触发（好奇缺口/反常识/权威背书等）里挑 3 个，填上你的关键词并标注适合平台；4) 挑一条拍——两个钩子尽量选不同类别，一个止滑一个留存。
- 什么时候用 / 常见坑：写 Reels / TikTok / Shorts 脚本前筛开头时用；注意它是启发式筛选器不是预测器——烂钩子筛得掉，好钩子不保证爆。

**适用场景**：短视频创作者、做脚本代写或剪辑接单的人。

**怎么用它搞钱**：剪辑单/代运营加"开头诊断"增值服务按条收费。

**来源**：[rediumvex/viral-hooks-skill](https://github.com/rediumvex/viral-hooks-skill) · ⭐108 · 更新于 2026-10-19

### shixinzhang/tiktok-viral-hooks

**核心提炼**
- 解决什么问题：知道"标题党"没用，但不知道爆款为什么爆——只看标题学不到结构，也没有可复制的模板。
- 核心用法（3 步）：1) 按赛道（娱乐/财经/美妆/美食/科技等）或钩子模式（好奇缺口/反常识/情绪共鸣等）浏览拆解；2) 每条拆解看三件套：精确 3 秒开场原句 + 7/14/21 秒留存动作 + 2 句话的脚本模板；3) 把自己的主题代入模板，当天发。
- 什么时候用 / 常见坑：起新号缺选题、想研究某个赛道打法时用；中英双语；库还在高频更新，挑和你同赛道的拆解抄。

**适用场景**：TikTok / Reels 起号、做赛道研究的创作者。

**怎么用它搞钱**：照模板日更起号接广告，或整理成钩子题材库卖给剪辑/编剧从业者。

**来源**：[shixinzhang/tiktok-viral-hooks](https://github.com/shixinzhang/tiktok-viral-hooks) · ⭐36 · 更新于 2026-10-19

### artemnovitckii/content-skills

**核心提炼**
- 解决什么问题：Claude 写的文案"一看就是 AI 的"——套话、过度解释、翻案句（"不是 X，而是 Y"）、破折号堆积，怎么改都洗不掉味。
- 核心用法（4 步）：1) 免安装也能用：打开任一 skill 的 SKILL.md，全文复制粘到普通 Claude 对话；2) 按链路叠加：dumbify（降到 8 年级阅读难度）→ storytelling（张力-转折-落点结构）→ viral-hooks（审计开场四大致死点并改写）→ anti-ai-writing（去 AI 味终检）；3) voice-dna：喂 ~20 篇自己的旧帖，让 Claude 学你的语气；4) Claude Code 用户装到 `~/.claude/skills` 后自动触发。
- 什么时候用 / 常见坑：写脚本、caption、帖子觉得"太 AI 腔"时用；注意 viral-hooks 的 A-vs-B 对比和 anti-ai-writing 是配套规则，别拆开互否。

**适用场景**：用 Claude 写文案/脚本、苦于 AI 味洗不掉的创作者。

**怎么用它搞钱**：把 hook 诊断接到脚本代做流程里，做成"开头体检报告"差异化报价。

**来源**：[artemnovitckii/content-skills](https://github.com/artemnovitckii/content-skills) · ⭐107 · 更新于 2026-10-18

### ehui1226/hookmeter-jev

**核心提炼**
- 解决什么问题：写帖子时没人告诉你开头够不够抓人；问大模型打分要等 5–10 秒，打断创作心流。
- 核心用法（3 步）：1) 装 Chrome 扩展（开发者模式加载 extension 文件夹），或自己配 API Key（本地 FastAPI / 免费 Cloudflare Worker 一键部署）；2) 在 X / Twitter 输入框写标题，击键瞬间出分：悬念指数、情绪能量、爆款心理学归类、标题党限流预警；3) 按 10 字内的即时修改处方改开头，再发。
- 什么时候用 / 常见坑：每次发帖写标题/开头前实时测；注意核心评分走 TypeSafe JEV API，需要 key；中文输入法做了防抖对齐，拼音输入中不会误请求。

**适用场景**：高频发帖、需要快速验证标题的 X / Twitter 创作者。

**怎么用它搞钱**：发帖前全测一遍提点击率，或打包进自媒体培训课卖课。

**来源**：[ehui1226/hookmeter-jev](https://github.com/ehui1226/hookmeter-jev) · ⭐22 · 更新于 2026-10-01

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

### @CaijingView（财经世界观）：7 个提示词把 Instagram 内容从无聊变爆款（30 天 220 万观看）

**核心提炼**
- 总纲：30 天 220 万次观看，无相机拍摄，全靠"复制（跑通的内容）+ AI"流程——证明钩子/脚本可以用 prompt 批量生产
- 7 个 prompt 组成一条钩子生产线：①开场钩子生成器（喂主题+平台，要 10 个"让人停下滑动手指"的钩子，禁套话鸡汤）②找非显而易见的内容角度（在噪音中杀出重围）③不露脸内容配方 ④紧凑脚本生成（去开场白、零废话）⑤反套路改写（去掉可预测表达和软弱框架）⑥留存向编辑（提完读率、加节奏变化）⑦权威感终稿润色
- 方法论：钩子 prompt 里必须写明"平台+要避免什么"，越具体越好用；把"找角度/写钩子/改脚本/提留存"拆成独立 prompt，比一个大 prompt 更可控
- 如实说明：30 天 220 万为作者自述数据，未经第三方核验；7 个 prompt 的完整原文在帖子评论区线程内

**适用场景**：用 AI 批量做钩子/短视频脚本的内容运营、矩阵号操盘手。

**怎么用它搞钱**：把 7 个 prompt 打包成"AI 钩子生产线"卖给内容创作者，或接矩阵号代运营的钩子外包。

**来源**：[@CaijingView](https://x.com/CaijingView/status/2112018906672189593) · 2026-10-19（原帖经 fxtwitter API 核验真实）

### @publisherinabox：Meta Watchbait 警示——承诺了不兑现的钩子会降权扣收益

**核心提炼**
- 反常识：钩子写得太"勾人"反而被罚——Meta Watchbait 规则下，钩子承诺了、视频没兑现的内容会被降分发、扣收益
- 钩子禁忌①信息断层式（withholding information）：故意制造信息断层逼人看完，如"这种日常食材可能毁了你的晚餐，看到最后才揭晓"；正确做法：先点明关键信息，再用"如何避免失误/做对步骤"给观众留下的理由
- 钩子禁忌②无必要夸张（sensationalism）："这个厨房技巧将永远改变你的人生"类；正确做法：说具体收益，不说永恒改变
- 方法论：钩子=承诺，承诺要在视频前 30 秒兑现；用"信息前置+过程留白"代替"信息断层"
- 如实说明：原帖列出三条 Meta Watchbait 判定标准，本条目收录其中两条已核验细节，第三条见原帖

**适用场景**：做 Facebook 视频投放、靠平台收益的内容出版者，写钩子前的避坑自查。

**怎么用它搞钱**：把 Watchbait 自查清单做成发帖前检查表，卖给做 FB Reels 投放的团队，或接"降权诊断"单。

**来源**：[@publisherinabox](https://x.com/publisherinabox/status/2112258380765024442) · 2026-10-20

### @mingyuanai（明远｜AI商业架构师）：drama ads 钩子三要素——猛、反转、报复感

**核心提炼**
- 行业信号：Seedance 2.5 级别的模型已经能批量产出"整段剧情广告"（drama ads），制作门槛正在消失
- 钩子公式：猛 + 反转 + 报复感——借短剧逻辑做广告开头，本质是注意力生意
- 关键判断：工具抹平的是"会不会做视频"，抹不平的是"懂不懂用户情绪"；情绪抓得住，模型就是加速器
- 对钩子的启示：钩子拼的不再是制作精度，而是对用户情绪（爽点/复仇感/反转期待）的理解深度

**适用场景**：剧情类短视频广告、AI 剧情广告投放创意。

**怎么用它搞钱**：用 Seedance 2.5 批量做 drama ads 钩子 A/B 测试，接品牌效果广告的创意外包，按转化收费。

**来源**：[@mingyuanai](https://x.com/mingyuanai/status/2112192145272479985) · 2026-10-19

### @wangzaimedia：抖音爆款开头的共同公式=危言耸听式反转断言

**核心提炼**
- 案例拆解：密集刷抖音开头后发现爆款共性——"越认真越失败""中小教育出文盲""90%的人都把 AI 用错了""垂直正在杀死你的自媒体"
- 公式提炼：反常识断言 + 危言耸听语气——先否定观众既有认知（越努力越错/你全用错了），制造认知冲突逼人停留
- 为什么有效：断言越绝对、越反直觉，观众越想验证"他凭什么这么说"，停留带来完播，完播带来推流
- 边界提醒：断言必须在视频里自圆其说，否则就是标题党伤号；适合知识/观点类口播

**适用场景**：知识/口播类短视频开头写作，理解反转断言为何有效。

**怎么用它搞钱**：给知识博主批量写"反转断言式"开头按条收费，或做成开头模板包卖给口播创作者。

**来源**：[@wangzaimedia](https://x.com/wangzaimedia/status/2112288008548569409) · 2026-10-20

### @AgiRay1015（AI磊叔）：20 秒 AI 宣传片实测——1.5 秒钩子 + "时长是减出来的"

**核心提炼**
- 总纲：给 Echo 做 20 秒宣传片，一下午迭代 15 版得出的实测公式——"时长是减出来的"（第一版 40 秒，一刀一刀压到 20 秒）
- 时间公式：1.5 秒钩子 + 几个功能各 3 秒 + 2 秒落版——1.5 秒钩子负责"停住"，功能段负责"看懂"，落版负责"记住"
- 真实录屏优先：skill 能理解录屏素材，可实现停顿、文字放大等效果；多用真实素材，少纯生成
- 节奏=疏密对比：正式内容要密、过渡留空再卡点出来；推近让人看清、甩镜把视线交给下一个功能
- 踩点克制：全片定三五个卡点就够，处处都踩等于哪都不响
- 配乐是大问题：大模型给视频配乐做得并不好，音乐要单独处理、跟着切点走
- 迭代纪律：一次只改一层，先画面后音乐——画面一动音乐全得重做，所以画面定稿再碰音乐

**适用场景**：做 AI 产品宣传片、广告片的创作者；钩子设计 + 成片节奏验收自查。

**怎么用它搞钱**：按"20 秒宣传片代制"接单报价，"一次只改一层"的迭代纪律写进交付 SOP 降低返工成本。

**来源**：[@AgiRay1015](https://x.com/AgiRay1015/status/2112525401847374118) · 2026-10-20

### @lisenhai9999（AI搞钱小海）：带货号 AI 短视频脚本全流程——30 秒公式 + 报价单

**核心提炼**
- 总纲：带货短视频用 AI 批量产的完整流程，含市场报价——先定位再生产
- 定位：别做全品类，盯死一个细分（如"厨房好物"）；先让 AI 研究该类目 Top 100 视频的爆款开头，再下笔
- 脚本公式：痛点钩子（3 秒）+ 使用场景（10 秒）+ 效果对比（10 秒）+ 下单冲动（7 秒），每条 30 秒；AI 一次出 10 版，挑 3 版人工改
- 报价参考：脚本按条 50–200 元，整包（脚本+口播稿+标题）500–1500 元
- 红线：所有数据话术必须真人验证过，夸大宣传会被平台永久限流——AI 产出先验再发

**适用场景**：做带货短视频代运营/接单的人；批量出脚本 + 标准化报价。

**怎么用它搞钱**：把公式和报价单做成标准服务包接单，"AI 一次出 10 版"当交付卖点；真人验证环节做成增值质检收费。

**来源**：[@lisenhai9999](https://x.com/lisenhai9999/status/2112492271216058574) · 2026-10-20

### @lisenhai9999（AI搞钱小海）：一条视频赚 5000 的四步 AI 流程

**核心提炼**
- 总纲："一条视频赚 5000 块"的四步法——选题 → 脚本 → 制作 → 分发，全链路
- 选题：AI 工具搜最近 7 天热点话题，选自己熟悉的领域，AI 生成 10 个选题挑最有共鸣的
- 脚本：按"钩子-痛点-解决方案-结尾互动"结构让 AI 写——钩子是脚本结构的第一环
- 制作：AI 数字人工具自动生成口播视频，不用出镜
- 分发：一条视频发抖音、小红书、视频号三个平台，一条内容多平台吃干榨净
- 如实说明：5000 元为作者自述数据，未经第三方核验

**适用场景**：想用 AI 做口播短视频赚钱的新人、矩阵号操盘手。

**怎么用它搞钱**：把四步法做成代运营 SOP 包，按账号月费收费；"钩子-痛点-解决方案-结尾互动"结构当脚本模板卖给口播创作者。

**来源**：[@lisenhai9999](https://x.com/lisenhai9999/status/2112485224961454376) · 2026-10-20

### @XunDavid80270（xun david，评论区）：知识视频 5 段模板——skill 填表法

**核心提炼**
- 总纲：做"卖铲子"的 skill 思路——先把知识视频固定成 5 段模板
- 模板：3 秒钩子 → 概念定义 → 类比动画 → 实际例子 → 一句话总结——钩子永远在第一环
- 架构：skill 只负责把文章填进模板并输出分镜表；换主题只改输入，不改模板
- 难点提示：最难标准化的是"类比动画"那段，模板化要先攻这一段
- 方法论：知识型视频也先抓钩子再讲概念；把结构固定下来，AI 才产得出稳定质量

**适用场景**：做知识付费/知识视频 skill、工作流，想把文章批量转视频的人。

**怎么用它搞钱**：5 段模板做成 skill 或工作流，卖给知识博主当"一键转视频"工具；或按分镜表接单收费。

**来源**：[@XunDavid80270](https://x.com/XunDavid80270/status/2112484651742666806) · 2026-10-20（评论区命中）

## 收录标准

- 来源：X 博主实战分享（原帖 / 评论区 / 引用链）及 GitHub 高星项目
- GitHub 项目条目格式：核心提炼（解决什么问题 / 核心用法 3–5 步：输入→输出、关键步骤 / 什么时候用 / 常见坑）+ 适用场景（适合谁）+ 一条「怎么用它搞钱」+ 来源（项目链接只作来源；star 数与更新时间经 GitHub API 核验）
- X 实战帖条目格式：核心提炼（3-8 条要点，不点链接也能拿走干货）+ 适用场景一句话 + 一条「怎么用它搞钱」+ 原帖链接只做署名出处
- Star 数为 2026-10-20 经 GitHub API 核验；持续收录中
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
- 2026-10-20：早档搜集（优先队列第 9 天）：X 新增 4 条实战帖（@CaijingView 7 提示词钩子生产线 30 天 220 万观看、@publisherinabox Meta Watchbait 钩子三禁忌、@mingyuanai drama ads 钩子三要素猛/反转/报复感、@wangzaimedia 危言耸听式反转断言公式；@dontbesilent2025 账号已不存在无法核查；第 2/4 组关键词无合格命中，未凑数）；GitHub 关键词 viral hooks / video hook prompt / tiktok hooks 无新增（已入库去重、其余 <20★ 或类目不合，宁缺毋滥）；5 个 GitHub 条目 star 经 API 核验刷新（424/108/36/107/22）
- 2026-10-20：晚档搜集（优先队列第 9 天）：X 新增 4 条窗内实战帖（北京时间 15:00 之后；@AgiRay1015 20 秒 AI 宣传片实测 1.5 秒钩子公式+迭代纪律、@lisenhai9999 带货号 AI 短视频脚本 30 秒公式+报价单、@lisenhai9999 一条视频赚 5000 四步 AI 流程、@XunDavid80270 评论区知识视频 5 段模板 skill 填表法；15 组关键词×Latest+10 账号时间线抽查，其余窗内帖按宁缺毋滥剔除、4 条早档帖去重确认无复现；登录态正常、全程只读无互动、未遇真人验证）；GitHub 侧早档已做不重做
