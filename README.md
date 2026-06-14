# Final-project
## Student Information
**name：113370450 蘇孟孜

## 研究問題
睡眠時數是否能顯著預測高中生感到悲傷或絕望的可能性？

本研究使用美國 CDC 2007 年青少年危險行為調查（YRBS 2007）資料集，探討高中生睡眠時數是否與感到悲傷或絕望的可能性存在顯著關聯。

## 資料來源
資料集：YRBS_2007.csv
資料來源：美國疾病管制與預防中心（CDC）Youth Risk Behavior Survey (YRBS) 2007。

## 變數定義

### 自變數（Independent Variable）
變數名稱：Sleep
變數說明：高中生在一般上學日的平均睡眠時數。
編碼方式：
* 1 = 4 小時或以下
* 2 = 5 小時
* 3 = 6 小時
* 4 = 7 小時
* 5 = 8 小時
* 6 = 9 小時
* 7 = 10 小時或以上
資料型態：序位變數（Ordinal Variable）

### 應變數（Dependent Variable）
變數名稱：Sad_Recoded
變數說明：受訪者於過去 12 個月內是否曾連續兩週以上感到悲傷或絕望。
編碼方式：
* 1 = 有
* 0 = 無
資料型態：二元變數（Binary Variable）

## 資料清洗
本研究執行以下資料清洗程序：

1. 保留 Sleep 與 Sad_Recoded 兩項分析變數。
2. 排除缺失值。
3. 採用完全個案刪除法（Listwise Deletion）。

最終有效分析樣本數：
**N = 12,106**

## 統計方法
本研究採用 Logistic Regression 分析睡眠時數是否能顯著預測高中生感到悲傷或絕望的可能性。

### 統計假說
H₀：睡眠時數無法顯著預測高中生感到悲傷或絕望的可能性。
H₁：睡眠時數能夠顯著預測高中生感到悲傷或絕望的可能性。

顯著水準：
α = 0.05

## 探索性資料分析（EDA）
長條圖結果顯示，隨著睡眠時數增加，感到悲傷或絕望的比例呈現下降趨勢。睡眠時間較短的學生具有較高的悲傷比例，而睡眠時間較長的學生則呈現較低的悲傷比例。

## Logistic Regression 分析結果

| 統計量       | 數值      |
| --------- | ------- |
| 樣本數（N）    | 12,106  |
| 迴歸係數（β）   | -0.2475 |
| 勝算比（OR）   | 0.7807  |
| p-value   | < 0.001 |
| Pseudo R² | 0.0187  |

### 結果解釋
睡眠時數的迴歸係數為負值（β = -0.2475），表示睡眠時間越長，感到悲傷或絕望的可能性越低。
勝算比（OR = 0.7807）表示睡眠組別每增加一個等級，感到悲傷或絕望的勝算約下降 21.9%。

## 研究結論
Logistic Regression 分析結果顯示，睡眠時數對高中生感到悲傷或絕望的可能性具有顯著預測效果（p < 0.001）。
由於 p-value 小於顯著水準 α = 0.05，因此拒絕虛無假設。
整體而言，睡眠時間較短的學生較容易出現悲傷或絕望感，而較充足的睡眠則與較低的負面情緒風險有關。

---
## Research Question
Does sleep duration predict the likelihood of feeling sad or hopeless among high school students?

This project uses the YRBS 2007 dataset to examine whether sleep duration is associated with the likelihood of feeling sad or hopeless among high school students.

## Dataset
Dataset: YRBS_2007.csv
Source: Centers for Disease Control and Prevention (CDC), Youth Risk Behavior Survey (YRBS), 2007.

## Variables
### Independent Variable
Sleep
* 1 = 4 hours or less
* 2 = 5 hours
* 3 = 6 hours
* 4 = 7 hours
* 5 = 8 hours
* 6 = 9 hours
* 7 = 10 or more hours
Variable Type: Ordinal Variable

### Dependent Variable
Sad_Recoded
* 1 = Yes
* 0 = No
Variable Type: Binary Variable

## Final Sample Size
N = 12,106

## Statistical Method
Logistic Regression

## Key Results
| Statistic             | Result  |
| --------------------- | ------- |
| Sample Size (N)       | 12,106  |
| Sleep Coefficient (β) | -0.2475 |
| Odds Ratio (OR)       | 0.7807  |
| p-value               | < 0.001 |
| Pseudo R²             | 0.0187  |

## Conclusion
The Logistic Regression analysis showed that sleep duration was a significant predictor of feeling sad or hopeless among high school students (p < 0.001).
Students with shorter sleep durations were more likely to report sadness or hopelessness, whereas longer sleep durations were associated with a lower likelihood of negative emotional outcomes.

## Project Repository

GitHub Repository Link

---

## Presentation Video

YouTube Video Link
