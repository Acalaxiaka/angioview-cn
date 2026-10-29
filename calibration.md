# 冠脉解剖校准报告（angioview-cn）

## 参考来源
1. SYNTAX Score 官方段定义（AHA 分段 ARTS 改良，16 段）：https://syntaxscore.org/index.php/tutorial/definitions ；https://officialsyntaxscore.com/index.php/tutorial/definitions
2. Sianos G, et al. The SYNTAX Score: an angiographic tool grading the complexity of coronary artery disease. EuroIntervention 2005：https://eurointervention.pcronline.com/article/the-syntax-score-an-angiographic-tool-grading-the-complexity-of-coronary-artery-disease
3. Dodge JT Jr, et al. Lumen diameter of normal human coronary arteries. Circulation 1992;86:232–246：https://www.ahajournals.org/doi/10.1161/01.cir.86.1.232 （PubMed 1535570）

## 关键参考值
- 管径（Dodge）：LM 4.5±0.5 mm；pLAD 3.7±0.4；dLAD 1.9±0.4；pLCx 3.4（右优势）/4.2（左优势）；pRCA 3.9（右优势）/2.8（左优势）。分支管径随分支长度增大。
- 段定义（SYNTAX）：1 pRCA（开口→至锐缘距离一半）；2 mRCA（→锐缘）；3 dRCA（锐缘→PDA 起点）；4 PDA（后室间沟）；16 PLB（十字交叉远端）；5 LM；6 pLAD（含第一大间隔支）；7 mLAD；8 LAD 心尖段（可绕过心尖）；9/10 D1/D2；11 pLCx（至 OM1 起点）；12 中间支，12a/12b OM；13 dLCx（左房室沟后段）；14 左室后侧支；15 L-PDA（左优势）。
- 走行关系：LAD 前室间沟→心尖并常绕至膈面；LCx 左房室沟；RCA 右房室沟→锐缘→十字交叉；PDA 后室间沟。冠脉开口位于主动脉窦内、窦管交界下方。LM 一般长约 10 mm（5–15 mm）。LAD–LCx 夹角常见 60–90°。

## 模型对照与修改
| 项目 | 原模型 | 修改 |
|---|---|---|
| 管径比例 | LAD/D/OM 偏粗，dLAD≈LM 的 56% | 按 Dodge 比例：LM .34 → pLAD .28、mLAD .22、dLAD .145（≈1.9/4.5）、D1 .17、D2 .13、OM1 .17、OM2 .14；pLCx 右优势 .26 / 左优势 .32；pRCA 右优势 .30 / 左优势 .21 |
| LM 长度 | 约 1.9 cm（模型 1 单位≈1.3 cm） | 分叉点前移，LM ≈1.0–1.2 cm |
| LAD 远段 | 止于心尖前方 | 延伸绕过心尖至膈面（段8 "to or beyond apex"） |
| 段号 | 无 | 选中血管标签显示 "ABBR 中文 · 段N"（如 pLAD 前降支近段 · 段6；L-PDA · 段15） |
| 开口位置 | LM 左冠窦、RCA 右冠窦、窦管交界下 | 已符合，未改 |
| RCA/PDA/LCx 走行 | 房室沟/室间沟 | 已符合，未改 |

## 局限
- 心脏为简化 SDF 模型，比例为示意；1 单位≈1.3 cm 为按左室长轴估算。
- 间隔支（S）、AM、conus、SN、AVN、RV 支在 SYNTAX 中无独立段号，不显示段号。
- 未建模中间支（段12）；未区分 9a/10a/16a–c。
- 仅供教学参考。
