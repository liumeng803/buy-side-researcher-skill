# 买方投资研究员 (Buy-Side Researcher)

Claude Code Skill for investment research. Automatically generates comprehensive investment memos (18,000-30,000 characters) with deep analysis.

## 安装 (Installation)

### 方法1: Claude Code 命令安装
```
/buy-side-researcher
```

### 方法2: Git Clone
```bash
git clone https://github.com/liumeng803/buy-side-researcher-skill.git
```

然后在Claude Code中配置skill路径。

## 功能 (Features)

- **行业识别**: 自动识别成长型/消费型/周期型/金融型公司
- **深度分析**: 11+章节完整投研框架
- **周期模块**: 专为矿业、大宗商品等周期型公司设计
- **反幻觉原则**: 所有数据必须有一手来源
- **行动指引**: 具体可执行的买卖触发条件

## 触发方式

当你说以下内容时会触发：
- "帮我研究/调研/分析[公司名]"
- "投资备忘录"
- "做一次投研"
- "这家公司值得买吗"

## 示例

```
帮我研究兴业银锡
```

## 框架核心模块

| 模块 | 内容 |
|------|------|
| Agent 1 | 商业模式 |
| Agent 2 | 护城河与竞争格局 |
| Agent 3 | 需求侧与市场空间 |
| Agent 4 | 利润池分析 |
| Agent 5 | 组织文化与管理 |
| Agent 6 | 财务深度分析 |
| Agent 7 | 风险+管理层+估值 |
| Agent 8 | 多元视角+估值 |
| Agent C1 | 周期定位与供需(周期公司) |
| Agent C2 | 成本曲线与价格分析(周期公司) |
| Agent C3 | 资本周期与压力测试(周期公司) |

## 来源要求

必须通过联网搜索获取一手信息：
- 年报/10-K/20-F
- 监管文件(SEC/港交所/证监会)
- 权威媒体(FT/WSJ/Bloomberg/Reuters)
- 行业协会报告

禁止使用百度/新浪/搜狐/网易等门户聚合网站作为证据来源。

## 输出

生成Markdown格式投资备忘录，包含：
- 三情景估值
- 五个最致命风险(含触发信号)
- 2×2结论框架
- 具体可执行的买卖触发条件
- 下一步行动清单

## License

MIT

## 作者

liumeng803
