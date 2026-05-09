# elder-trading-3m

基于 Alexander Elder《走进我的交易室 / Come Into My Trading Room》整理的 Codex skill，用于应用埃尔德的 `3M` 交易框架：交易心理（Mind）、交易方法（Method）和资金管理（Money）。

该 skill 适合用于检查交易计划、学习三重滤网系统、复盘交易记录、计算 `2%规则` 与 `6%规则` 风险约束，以及建立交易日记和资金曲线流程。

> 本仓库是学习型框架整理，不包含原书全文，不替代原书阅读，也不构成投资建议。

## 安装

### Windows

```powershell
git clone https://github.com/freesme/elder-trading-3m.git "$env:USERPROFILE\.codex\skills\elder-trading-3m"
```

### macOS / Linux

```bash
git clone https://github.com/freesme/elder-trading-3m.git ~/.codex/skills/elder-trading-3m
```

安装后，重新打开 Codex 会话即可使用。

## 使用

```text
$elder-trading-3m
$elder-trading-3m 三重滤网
$elder-trading-3m 2%规则
$elder-trading-3m 交易日记
$elder-trading-3m ch07
```

也可以让它检查一笔交易计划：

```text
$elder-trading-3m 请按埃尔德体系检查这笔交易：
标的：
方向：
周期：
入场：
止损：
目标：
账户权益：
已有仓位风险：
交易理由：
```

## 内容

- `SKILL.md`：核心框架和主题索引
- `chapters/`：10 个章节参考
- `glossary.md`：术语表
- `patterns.md`：操作流程和模式
- `cheatsheet.md`：速查表
