---
layout: single
title: "21 Lessons From 14 Years at Google（中英对照）"
excerpt: "Addy Osmani 的 21 条谷歌工程心得，中英对照译文。"
original_url: "https://addyosmani.com/blog/21-lessons/"
---

以下为原文与译文对照，块引用部分为原文，译文置于其后。

## 引言
> 原文：When I joined Google ~14 years ago, I thought the job was about writing great code. I was partly right. But the longer I’ve stayed, the more I’ve realized that the engineers who thrive aren’t necessarily the best programmers - they’re the ones who’ve figured out how to navigate everything around the code: the people, the politics, the alignment, the ambiguity.
译文：大约 14 年前加入谷歌时，我以为这份工作就是写出好代码。我只说对了一半。待得越久越发现，真正混得好的工程师不一定是最会写代码的，而是那些懂得处理代码以外一切的人：人、政治、对齐、模糊地带。

> 原文：These lessons are what I wish I’d known earlier. Some would have saved me months of frustration. Others took years to fully understand. None of them are about specific technologies - those change too fast to matter. They’re about the patterns that keep showing up, project after project, team after team.
译文：这些心得是我希望更早知道的。有些能帮我省掉好几个月的挫败；有些花了多年才搞明白。它们都和具体技术无关——技术变化太快了。这些是一个又一个项目、一个又一个团队里不断出现的模式。

> 原文：I’m sharing them because I’ve benefited enormously from engineers who did the same for me. Consider this my attempt to pay it forward.
译文：我分享出来，因为曾经有工程师也这样帮助过我，我受益匪浅。这算是我尽力向前传递的方式。

## 1. 最好的工程师痴迷于解决用户问题。
> 原文：1. The best engineers are obsessed with solving user problems.
译文：1. 最好的工程师痴迷于解决用户问题。

> 原文：It’s seductive to fall in love with a technology and go looking for places to apply it. I’ve done it. Everyone has. But the engineers who create the most value work backwards: they become obsessed with understanding user problems deeply, and let solutions emerge from that understanding.
译文：迷恋某个技术然后找地方套用很有诱惑力。我干过，大家都干过。但创造最大价值的工程师是反向工作的：他们沉迷于深入理解用户问题，让解决方案从理解中自然浮现。

> 原文：User obsession means spending time in support tickets, talking to users, watching users struggle, asking “why” until you hit bedrock. The engineer who truly understands the problem often finds that the elegant solution is simpler than anyone expected.
译文：所谓用户痴迷，就是泡在支持工单里、跟用户聊天、看用户受苦、不断追问“为什么”直到触底。真正理解问题的工程师常常发现，优雅的解法比大家想象得更简单。

> 原文：The engineer who starts with a solution tends to build complexity in search of a justification.
译文：而从解决方案起步的工程师，则往往会为寻找合理性而堆复杂度。

## 2. 做对很便宜，一起做对才是真功夫。
> 原文：2. Being right is cheap. Getting to right together is the real work.
译文：2. 做对很便宜，一起做对才是真功夫。

> 原文：You can win every technical argument and lose the project. I’ve watched brilliant engineers accrue silent resentment by always being the smartest person in the room. The cost shows up later as “mysterious execution issues” and “strange resistance.”
译文：你可以在每次技术争论中获胜，却输掉整个项目。我见过聪明人总是房间里最聪明的人，积累下无声怨气。代价后来以“莫名的执行问题”“诡异的阻力”出现。

> 原文：The skill isn’t being right. It’s entering discussions to align on the problem, creating space for others, and remaining skeptical of your own certainty.
译文：关键能力不是自己对，而是带着对齐问题的心态进入讨论，给别人腾出空间，并对自己的笃定保持怀疑。

> 原文：Strong opinions, weakly held - not because you lack conviction, but because decisions made under uncertainty shouldn’t be welded to identity.
译文：保持强烈但易收的观点——不是因为你缺少信念，而是因为在不确定下做的决定不该和身份绑定。

## 3. 偏向行动，先上船。坏稿能改，空白改不了。
> 原文：3. Bias towards action. Ship. You can edit a bad page, but you can’t edit a blank one.
译文：3. 偏向行动，先上船。坏稿能改，空白改不了。

> 原文：The quest for perfection is paralyzing. I’ve watched engineers spend weeks debating the ideal architecture for something they’ve never built. The perfect solution rarely emerges from thought alone - it emerges from contact with reality. AI can in many ways help here.
译文：追求完美会让人僵住。我见过工程师为了从未做过的东西，争论理想架构争了好几周。完美方案很少靠想出来，而是撞击现实后才浮现。AI 在很多地方能帮忙。

> 原文：First do it, then do it right, then do it better. Get the ugly prototype in front of users. Write the messy first draft of the design doc. Ship the MVP that embarrasses you slightly. You’ll learn more from one week of real feedback than a month of theoretical debate.
译文：先做出来，再做好，再做得更好。把丑陋的原型摆到用户面前；写下凌乱的设计文档初稿；上线让你有点害羞的 MVP。来自一周真实反馈的收获，胜过一个月的理论争论。

> 原文：Momentum creates clarity. Analysis paralysis creates nothing.
译文：动能带来清晰，分析瘫痪什么也带不来。

## 4. 清晰就是资深，聪明反成负担。
> 原文：4. Clarity is seniority. Cleverness is overhead.
译文：4. 清晰就是资深，聪明反成负担。

> 原文：The instinct to write clever code is almost universal among engineers. It feels like proof of competence.
译文：写巧妙代码的冲动几乎是工程师的本能，它看起来能证明能力。

> 原文：But software engineering is what happens when you add time and other programmers. In that environment, clarity isn’t a style preference - it’s operational risk reduction.
译文：但软件工程是真实发生在时间和其他程序员加入之后的事情。在那环境里，清晰不是风格偏好，而是降低运维风险。

> 原文：Your code is a strategy memo to strangers who will maintain it at 2am during an outage. Optimize for their comprehension, not your elegance. The senior engineers I respect most have learned to trade cleverness for clarity, every time.
译文：你的代码是给陌生人看的策略备忘录，他们可能在凌晨 2 点的事故里维护它。优化的对象是他们的理解，而不是你的优雅。我敬佩的资深工程师，总是选择用清晰换掉聪明。

## 5. 新颖是一笔债，利息是故障、招聘和认知负担。
> 原文：5. Novelty is a loan you repay in outages, hiring, and cognitive overhead.
译文：5. 新颖是一笔债，利息是故障、招聘和认知负担。

> 原文：Treat your technology choices like an organization with a small “innovation token” budget. Spend one each time you adopt something materially non-standard. You can’t afford many.
译文：把你的技术选型当作只有几个“创新令牌”的组织。每用一次非标准方案就花掉一枚。你用不起太多。

> 原文：The punchline isn’t “never innovate.” It’s “innovate only where you’re uniquely paid to innovate.” Everything else should default to boring, because boring has known failure modes.
译文：结论不是“别创新”，而是“只在你被付钱去创新的地方创新”。其他一切默认平庸，因为平庸的失败模式是已知的。

> 原文：The “best tool for the job” is often the “least-worst tool across many jobs”-because operating a zoo becomes the real tax.
译文：所谓“最佳工具”往往其实是“跨很多活儿最不差的工具”——因为真正的税来自运营一座动物园。

## 6. 代码不会为你说话，人会。
> 原文：6. Your code doesn’t advocate for you. People do.
译文：6. 代码不会为你说话，人会。

> 原文：Early in my career, I believed great work would speak for itself. I was wrong. Code sits silently in a repository. Your manager mentions you in a meeting, or they don’t. A peer recommends you for a project, or someone else.
译文：职业早期我以为好工作会自己开口。我错了。代码默默躺在仓库里。你的经理会不会在会议上提你；同伴会不会把项目推荐给你，还是给了别人。

> 原文：In large organizations, decisions get made in meetings you’re not invited to, using summaries you didn’t write, by people who have five minutes and twelve priorities. If no one can articulate your impact when you’re not in the room, your impact is effectively optional.
译文：大公司里的决定常在你不在场的会议里做出，用的摘要不是你写的，决定的人只有五分钟十二个优先级。如果没人能在你不在时讲清你的影响力，它就等于可有可无。

> 原文：This isn’t strictly about self-promotion. It’s about making the value chain legible to everyone- including yourself.
译文：这不纯是自我宣传，而是让价值链对所有人——包括你自己——都清晰可见。

## 7. 最好的代码是你不用写的代码。
> 原文：7. The best code is the code you never had to write.
译文：7. 最好的代码是你不用写的代码。

> 原文：We celebrate creation in engineering culture. Nobody gets promoted for deleting code, even though deletion often improves a system more than addition. Every line of code you don’t write is a line you never have to debug, maintain, or explain.
译文：工程文化里我们歌颂创造。没人因为删代码升职，但删减往往比添加更能改善系统。每一行不写的代码都是一行不用调试、维护、解释的代码。

> 原文：Before you build, exhaust the question: “What would happen if we just… didn’t?” Sometimes the answer is “nothing bad,” and that’s your solution.
译文：在动手前，把这个问题问到底：“如果我们就……不做，会怎样？”有时答案是“没啥坏事”，那就是解法。

> 原文：The problem isn’t that engineers can’t write code or use AI to do so. It’s that we’re so good at writing it that we forget to ask whether we should.
译文：问题不是工程师不会写代码或用 AI 写，而是我们太会写了，以至于忘了问自己该不该写。

## 8. 到了一定规模，连你的 Bug 也有用户。
> 原文：8. At scale, even your bugs have users.
译文：8. 到了一定规模，连你的 Bug 也有用户。

> 原文：With enough users, every observable behavior becomes a dependency - regardless of what you promised. Someone is scraping your API, automating your quirks, caching your bugs.
译文：用户够多时，每个可观察行为都会变成依赖——不管你承诺了什么。有人在爬你的 API、自动化你的怪癖、缓存你的 Bug。

> 原文：This creates a career-level insight: you can’t treat compatibility work as “maintenance” and new features as “real work.” Compatibility is product.
译文：这带来一个职业层面的洞见：兼容性工作不能当作“维护”，而新特性才是“真工作”。兼容性本身就是产品。

> 原文：Design your deprecations as migrations with time, tooling, and empathy. Most “API design” is actually “API retirement.”
译文：把废弃设计成迁移：给时间、给工具、给同理心。大多数“API 设计”其实是“API 退役”。

## 9. 多数“慢”团队其实是没对齐的团队。
> 原文：9. Most “slow” teams are actually misaligned teams.
译文：9. 多数“慢”团队其实是没对齐的团队。

> 原文：When a project drags, the instinct is to blame execution: people aren’t working hard enough, the technology is wrong, there aren’t enough engineers. Usually none of that is the real problem.
译文：项目拖延时，本能是怪执行：人不够拼、技术选错、工程师不够。通常都不是根因。

> 原文：In large companies, teams are your unit of concurrency, but coordination costs grow geometrically as teams multiply. Most slowness is actually alignment failure - people building the wrong things, or the right things in incompatible ways.
译文：在大公司，团队是并发单元，但协调成本随团队数呈几何增长。大多数慢其实是对齐失败——要么在做错的事，要么做对的事却互相不兼容。

> 原文：Senior engineers spend more time clarifying direction, interfaces, and priorities than “writing code faster” because that’s where the actual bottleneck lives.
译文：资深工程师花更多时间澄清方向、接口和优先级，而不是“更快写代码”，因为瓶颈就在那。

## 10. 把精力放在能控制的事，忽略你控制不了的。
> 原文：10. Focus on what you can control. Ignore what you can’t.
译文：10. 把精力放在能控制的事，忽略你控制不了的。

> 原文：In a large company, countless variables are outside your control - organizational changes, management decisions, market shifts, product pivots. Dwelling on these creates anxiety without agency.
译文：大公司里无数变量不由你控——组织调整、管理决策、市场波动、产品转向。纠结这些只会制造无力的焦虑。

> 原文：The engineers who stay sane and effective zero in on their sphere of influence. You can’t control whether a reorg happens. You can control the quality of your work, how you respond, and what you learn. When faced with uncertainty, break problems into pieces and identify the specific actions available to you.
译文：能保持理智和效率的工程师聚焦自己的影响圈。你控制不了是否会重组，但你可以控制工作质量、回应方式、学习收获。遇到不确定时，把问题拆开，明确你能做的具体动作。

> 原文：This isn’t passive acceptance but it is strategic focus. Energy spent on what you can’t change is energy stolen from what you can.
译文：这不是被动接受，而是策略性聚焦。花在不能改的事上的能量，就是从能改的事上偷来的。

## 11. 抽象不会消灭复杂，它只把复杂移到你值班那天。
> 原文：11. Abstractions don’t remove complexity. They move it to the day you’re on call.
译文：11. 抽象不会消灭复杂，它只把复杂移到你值班那天。

> 原文：Every abstraction is a bet that you won’t need to understand what’s underneath. Sometimes you win that bet. But something always leaks, and when it does, you need to know what you’re standing on.
译文：每个抽象都是个赌注，赌你不会需要理解底层。有时你会赢。但总会有泄漏，发生时你得知道脚下是什么。

> 原文：Senior engineers keep learning “lower level” things even as stacks get higher. Not out of nostalgia, but out of respect for the moment when the abstraction fails and you’re alone with the system at 3am. Use your stack.
译文：资深工程师即便栈层越来越高，仍然继续学“更低层”的东西。不是怀旧，而是为了那天抽象失效、凌晨三点你独自面对系统时。用好你的栈，

> 原文：But keep a working model of its underlying failure modes.
译文：但也要保有它底层失效模式的工作模型。

## 12. 写作迫使清晰；想学得更好，尝试去教别人。
> 原文：12. Writing forces clarity. The fastest way to learn something better is to try teaching it.
译文：12. 写作迫使清晰；想学得更好，尝试去教别人。

> 原文：Writing forces clarity. When I explain a concept to others - in a doc, a talk, a code review comment, even just chatting with AI - I discover the gaps in my own understanding. The act of making something legible to someone else makes it more legible to me.
译文：写作会迫使你澄清。当我向别人解释一个概念——写文档、做分享、写 CR 评论，甚至跟 AI 聊天——我会发现自己理解的漏洞。让别人看懂的动作，也让自己看得更清楚。

> 原文：This doesn’t mean that you’re going to learn how to be a surgeon by teaching it, but the premise still holds largely true in the software engineering domain.
译文：这并不意味着你靠教书就能学会做外科手术，但在软件工程领域，这个前提大体成立。

> 原文：This isn’t just about being generous with knowledge. It’s a selfish learning hack. If you think you understand something, try to explain it simply. The places where you stumble are the places where your understanding is shallow.
译文：这不仅是慷慨分享的表现，更是自私的学习秘籍。觉得自己懂了？试着简单讲出来。你卡住的地方，就是理解浅的地方。

> 原文：Teaching is debugging your own mental models.
译文：教学是在调试自己的心智模型。

## 13. 让其他工作成为可能的工作无价——也最容易被忽视。
> 原文：13. The work that makes other work possible is priceless - and invisible.
译文：13. 让其他工作成为可能的工作无价——也最容易被忽视。

> 原文：Glue work - documentation, onboarding, cross-team coordination, process improvement - is vital. But if you do it unconsciously, it can stall your technical trajectory and burn you out. The trap is doing it as “helpfulness” rather than treating it as deliberate, bounded, visible impact.
译文：“胶水工作”——写文档、做新人引导、跨团队协作、改进流程——至关重要。但如果无意识地去做，它会拖慢你的技术成长，还会烧光你。陷阱在于把它当“好心”而不是有意、可控、可见的影响。

> 原文：Timebox it. Rotate it. Turn it into artifacts: docs, templates, automation. And make it legible as impact, not as personality trait.
译文：给它设时限，轮换负责，把它产出成文档、模板、自动化。让它被看作影响，而不是性格特质。

> 原文：Priceless and invisible is a dangerous combination for your career.
译文：无价又不可见，对你的职业是危险组合。

## 14. 辩论场场都赢，可能是在积累无声的反对。
> 原文：14. If you win every debate, you’re probably accumulating silent resistance.
译文：14. 辩论场场都赢，可能是在积累无声的反对。

> 原文：I’ve learned to be suspicious of my own certainty. When I “win” too easily, something is usually wrong. People stop fighting you not because you’ve convinced them, but because they’ve given up trying - and they’ll express that disagreement in execution, not meetings.
译文：我学会对自己的笃定保持警惕。当我太容易“赢”，通常哪里不对。人们不再争辩，不是因为你说服了他们，而是因为他们放弃了——他们会在执行中表达反对，而不是在会议里。

> 原文：Real alignment takes longer. You have to actually understand other perspectives, incorporate feedback, and sometimes change your mind publicly.
译文：真正的对齐更耗时。你得真的理解别的视角、吸收反馈，有时还要公开改变主意。

> 原文：The short-term feeling of being right is worth much less than the long-term reality of building things with willing collaborators.
译文：短期的“我对了”远不如长期和愿意合作的伙伴一起构建东西。

## 15. 一旦指标成了目标，它就不再是指标。
> 原文：15. When a measure becomes a target, it stops measuring.
译文：15. 一旦指标成了目标，它就不再是指标。

> 原文：Every metric you expose to management will eventually be gamed. Not through malice, but because humans optimize for what’s measured.
译文：你给管理层看的每个指标最终都会被“优化”。不是恶意，是人性会对可度量的东西做优化。

> 原文：If you track lines of code, you’ll get more lines. If you track velocity, you’ll get inflated estimates.
译文：测代码行数，你就会得到更多行。测速度，你就会得到膨胀的估算。

> 原文：The senior move: respond to every metric request with a pair. One for speed. One for quality or risk. Then insist on interpreting trends, not worshiping thresholds. The goal is insight, not surveillance.
译文：资深的做法：每个指标需求都给一对。一个看速度，一个看质量或风险。然后坚持解读趋势，而不是膜拜阈值。目标是洞察，不是监控。

## 16. 承认不会，比装会更能创造安全感。
> 原文：16. Admitting what you don’t know creates more safety than pretending you do.
译文：16. 承认不会，比装会更能创造安全感。

> 原文：Senior engineers who say “I don’t know” aren’t showing weakness - they’re creating permission. When a leader admits uncertainty, it signals that the room is safe for others to do the same. The alternative is a culture where everyone pretends to understand and problems stay hidden until they explode.
译文：说“我不知道”的资深工程师不是在示弱，而是在给别人许可。领导承认不确定，意味着这个房间允许别人也这么做。否则就会变成人人装懂，问题藏着直到爆炸。

> 原文：I’ve seen teams where the most senior person never admitted confusion, and I’ve seen the damage. Questions don’t get asked. Assumptions don’t get challenged. Junior engineers stay silent because they assume everyone else gets it.
译文：我见过团队里最资深的人从不承认困惑，后果很糟。没人提问，假设不被挑战，初级工程师沉默，因为以为别人都懂。

> 原文：Model curiosity, and you get a team that actually learns.
译文：示范好奇心，你就会得到一个真的在学习的团队。

## 17. 你的人脉会比你任过的所有工作都长寿。
> 原文：17. Your network outlasts every job you’ll ever have.
译文：17. 你的人脉会比你任过的所有工作都长寿。

> 原文：Early in my career, I focused on the work and neglected networking. In hindsight, this was a mistake. Colleagues who invested in relationships - inside and outside the company - reaped benefits for decades.
译文：职业早期我专注在工作本身，忽略了人脉。回头看这是个错误。那些投入关系的人——无论内外部——几十年都在收获。

> 原文：They heard about opportunities first, could build bridges faster, got recommended for roles, and co-founded ventures with people they’d built trust with over years.
译文：他们最先听到机会，能更快搭桥，被推荐岗位，甚至与多年累积信任的伙伴一起创业。

> 原文：Your job isn’t forever, but your network is. Approach it with curiosity and generosity, not transactional hustle.
译文：工作不是永远的，但人脉可以。带着好奇和慷慨去经营，而不是交易式的忙碌。

> 原文：When the time comes to move on, it’s often relationships that open the door.
译文：当你要离开时，往往是关系为你打开门。

## 18. 大多数性能提升来自删掉工作，而不是加聪明。
> 原文：18. Most performance wins come from removing work, not adding cleverness.
译文：18. 大多数性能提升来自删掉工作，而不是加聪明。

> 原文：When systems get slow, the instinct is to add: caching layers, parallel processing, smarter algorithms. Sometimes that’s right. But I’ve seen more performance wins from asking “what are we computing that we don’t need?”
译文：系统变慢时，本能是加东西：缓存层、并行处理、更聪明算法。有时对。但我看到更多性能提升来自问一句：我们在算哪些不需要算的东西？

> 原文：Deleting unnecessary work is almost always more impactful than doing necessary work faster. The fastest code is code that never runs.
译文：删掉无用工作几乎总比把必要工作做得更快更有影响。最快的代码是根本不会运行的代码。

> 原文：Before you optimize, question whether the work should exist at all.
译文：在优化前，先质疑这件事是否该存在。

## 19. 流程的存在是为了降低不确定，而不是制造纸面记录。
> 原文：19. Process exists to reduce uncertainty, not to create paper trails.
译文：19. 流程的存在是为了降低不确定，而不是制造纸面记录。

> 原文：The best process makes coordination easier and failures cheaper. The worst process is bureaucratic theater - it exists not to help but to assign blame when things go wrong.
译文：好的流程让协作更容易、失败成本更低。坏流程是官僚表演——不是为帮助，而是为了出事时能甩锅。

> 原文：If you can’t explain how a process reduces risk or increases clarity, it’s probably just overhead.
译文：如果你解释不出一个流程如何降低风险或提升清晰度，它很可能只是开销。

> 原文：And if people are spending more time documenting their work than doing it, something has gone deeply wrong.
译文：如果大家花在写文档上的时间比做事还多，说明事情已经严重跑偏。

## 20. 到某个节点，时间比钱更值钱。按这个行事。
> 原文：20. Eventually, time becomes worth more than money. Act accordingly.
译文：20. 到某个节点，时间比钱更值钱。按这个行事。

> 原文：Early in your career, you trade time for money - and that’s fine. But at some point, the calculus inverts. You start to realize that time is the non-renewable resource.
译文：职业早期，你用时间换钱——这没问题。但到某个时候，算式会倒过来。你会意识到时间才是不可再生的资源。

> 原文：I’ve watched senior engineers burn out chasing the next promo level, optimizing for a few more percentage points of compensation. Some of them got it. Most of them wondered, afterward, if it was worth what they gave up.
译文：我见过资深工程师为追下一级烧尽自己，只为多几个百分点的报酬。有些人拿到了，多数人在事后想：值得吗？

> 原文：The answer isn’t “don’t work hard.” It’s “know what you’re trading, and make the trade deliberately.”
译文：答案不是“不努力”，而是“搞清你在交换什么，并有意识地交换”。

## 21. 没有捷径，但有复利。
> 原文：21. There are no shortcuts, but there is compounding.
译文：21. 没有捷径，但有复利。

> 原文：Expertise comes from deliberate practice - pushing slightly beyond your current skill, reflecting, repeating. For years. There’s no condensed version.
译文：专业是靠刻意练习得来的——略超出当前能力、反思、重复，持续多年。没有浓缩版。

> 原文：But here’s the hopeful part: learning compounds when it creates new options, not just new trivia. Write - not for engagement, but for clarity. Build reusable primitives. Collect scar tissue into playbooks.
译文：但令人振奋的是：学习在能创造新选项时会复利，而不是靠多背冷知识。写作——不是为了流量，而是为了清晰；搭建可复用的原语；把伤痕整理成手册。

> 原文：The engineer who treats their career as compound interest, not lottery tickets, tends to end up much further ahead.
译文：把职业当作复利，而不是彩票，工程师往往走得更远。

## 结语
> 原文：A final thought
译文：结语

> 原文：Twenty-one lessons sounds like a lot, but they really come down to a few core ideas: stay curious, stay humble, and remember that the work is always about people - the users you’re building for and the teammates you’re building with.
译文：21 条听起来很多，但归根到底只有几个核心：保持好奇，保持谦逊，记得工作始终关乎人——为之构建的用户，以及与你一起构建的队友。

> 原文：A career in engineering is long enough to make plenty of mistakes and still come out ahead. The engineers I admire most aren’t the ones who got everything right - they’re the ones who learned from what went wrong, shared what they discovered, and kept showing up.
译文：工程职业够长，可以犯很多错还能站起来。我敬佩的工程师不是那些从不犯错的，而是那些从错中学习、分享所获、持续出现的人。

> 原文：If you’re early in your journey, know that it gets richer with time. If you’re deep into it, I hope some of these resonate.
译文：如果你还在旅程早期，要知道时间会让它更丰厚。如果你已经走得很深，希望其中一些能让你共鸣。
