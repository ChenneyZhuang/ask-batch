# ask-batch 批量提问

Every piecemeal question costs the user a context switch; a dozen of them cost a morning. Park, group, ask once.

每个碎片问题都让用户切换一次上下文；十几个碎片问题毁掉一个上午。先存、分组、一次问完。

## Why / 为什么

Agents ask questions the moment they hit uncertainty — which fragments the user's day into interruption-shaped confetti and hides the pattern: **the same decision context produces most of the questions**. Batching fixes both: the user answers in one sitting, and the grouped questions reveal which single decision unblocks half of them.

agent 一碰到不确定就发问——把用户的一天切成 INTERRUPTION 碎纸屑，还掩盖了一个规律：**大多数问题来自同一个决策上下文**。批量提问两个都修：用户一次答完，分组让"一个决定解锁一半问题"显形。

## The method / 方法

1. **Park, do not ask.** Questions land in a running parked list (in the session notes or a `questions.md`), each with its context line. Work continues on everything unblocked.
2. **Group by decision context.** "All the fields the report header needs" is one group; "one thing about the DB and one about lunch" is two.
3. **Propose defaults.** Every question ships with a default answer: "I will assume X unless you say otherwise." The user can rubber-stamp a whole group in seconds.
4. **Ask once per group.** One message, numbered questions, the answer format stated ("1: A/B, 2: free text"), and the deadline by which the default applies.
5. **Record the answers.** Answers land back into the parked list's context and the actual work; unanswered groups apply defaults at the stated deadline — visibly, never silently.

## The line that matters / 一条关键边界

**Blocking is different from uncertain.** A true blocker (cannot proceed without the answer) asks immediately, alone. Everything else waits for the batch. Agents that treat all uncertainty as blocking produce the drip this skill exists to stop.

**阻塞和不确定是两回事。**真阻塞（没有答案就无法继续）立刻单独问。其余全部等批量。把所有不确定都当阻塞的 agent，制造了这个 skill 要治的滴漏。

## Honest limitations / 如实说明局限

- Over-batching is a real failure mode: a day-old question that blocks one line of work should have been asked immediately.
- Defaults replace reading the room; for emotionally loaded contexts, ask sooner and in person.

过度批量是真实的失败模式：一条挡住一行代码的陈年问题就该立刻问。默认值替代不了察言观色；情绪浓的场合，早点问、当面问。

## Install / 安装

```bash
npx skills add ChenneyZhuang/ask-batch
```

Per-agent paths: [COMPATIBILITY.md](COMPATIBILITY.md). MIT. v0.1.0.

各 agent 安装路径见 COMPATIBILITY.md。MIT 许可，v0.1.0。
