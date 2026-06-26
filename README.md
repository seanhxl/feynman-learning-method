# 这是搬运自X的一个博主的方法论，在github没有找到对应的仓库，所以用Claude直接做了一个skill，侵删；
# 原文链接：https://waytoagi.feishu.cn/wiki/YobbwjzFdiYxNVkHjuZcio2Cnhh 


# 费曼学习法 Skill for Claude

一个 Claude skill，用 4 轮对话在 20 分钟内带你走完完整的费曼学习法流程。

## 做了什么

传统的费曼学习法是独自完成的——写解释、找缺口、翻资料。这个 skill 让 Claude 扮演一个"知道怎么教你的导师"：它在第 2 轮写示范解释，在第 3 轮逐句批改你的理解，在第 4 轮用类比把观点锁进长期记忆。

整个过程叠加了三种被认知科学验证的学习效应：被教者效应、检索练习和有益难度。

## 安装

1. 下载 `SKILL.md`
2. 在 Claude 中导入该 skill（通过设置 → Skills → 导入）
3. 在对话中输入 `/feynman-learning-method` 即可调用

## 用法

```
/feynman-learning-method
```

然后告诉 Claude 你想学什么主题，它会带着你跑完 4 轮：

| 轮次 | 你在做什么 |
|------|-----------|
| 概念地图 | Claude 提取 5 个核心观点 |
| 12 岁孩子测试 | 你用自己的话解释每个观点 |
| 缺口定位 | Claude 逐句批改，找出你"以为懂了"的地方 |
| 类比锁定 | 每个观点 2 个类比 + 浓缩句 |

总耗时约 20 分钟。

## 适用场景

- 读完一本书 / 学完一门课
- 面试准备
- 会议前快速弄懂一个概念
- 读完研究论文
- 任何你"点头但没真正理解"的东西

## 科学依据

- Protégé Effect — Koh, Lee & Lim (2018)：教别人比单纯学习得分高 10%-20%
- Retrieval Practice — Karpicke & Blunt (2011, *Science*)：提取信息比重读信息有效得多
- Desirable Difficulty — Bjork (1994, UCLA)：感觉费劲的学习才更深

## 许可

MIT
