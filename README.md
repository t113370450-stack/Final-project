# Final-project
## Student Information
* **Name**: 蘇孟孜
* **Student ID**: 113370450

## Research Question
Does sleep duration significantly predict the likelihood of feeling sad or hopeless among high school students?

This study uses the Youth Risk Behavior Survey 2007 (YRBS 2007) dataset from the U.S. CDC to investigate whether a significant association exists between adolescent sleep duration and the likelihood of feeling sad or hopeless.

## Data Source
* **Dataset**: `YRBS_2007.csv`
* **Source**: U.S. Centers for Disease Control and Prevention (CDC) Youth Risk Behavior Survey (YRBS) 2007.

## Variable Definitions

### Independent Variable
* **Variable Name**: Sleep
* **Description**: Average hours of sleep the high school student gets on an average school night.
* **Coding Scheme**:
  * 1 = 4 hours or less
  * 2 = 5 hours
  * 3 = 6 hours
  * 4 = 7 hours
  * 5 = 8 hours
  * 6 = 9 hours
  * 7 = 10 hours or more
* **Data Type**: Ordinal Variable

### Dependent Variable
* **Variable Name**: Sad_Recoded
* **Description**: Whether the respondent felt sad or hopeless almost every day for two weeks or more in a row during the past 12 months.
* **Coding Scheme**:
  * 1 = Yes
  * 0 = No
* **Data Type**: Binary Variable

## Data Cleaning
This study executed the following data cleaning procedures:
1. Retained two analysis variables: Sleep and Sad_Recoded.
2. Removed missing values.
3. Applied Listwise Deletion.

Final Valid Sample Size:
**N = 12,106**

## Statistical Methodology
This study uses Logistic Regression to analyze whether sleep duration significantly predicts the likelihood of high school students feeling sad or hopeless.

### Statistical Hypotheses
* $H_0$: Sleep duration cannot significantly predict the likelihood of high school students feeling sad or hopeless.
* $H_1$: Sleep duration can significantly predict the likelihood of high school students feeling sad or hopeless.

Significance Level:
$\alpha = 0.05$

## Exploratory Data Analysis (EDA)
The bar chart results show that as sleep duration increases, the percentage of reporting sadness or hopelessness shows a downward trend. Students with shorter sleep duration have a higher percentage of sadness, while students with longer sleep duration show a lower percentage of sadness.

## Logistic Regression Results

| Statistic | Value |
| :--- | :--- |
| Sample Size ($N$) | 12,106 |
| Regression Coefficient ($\beta$) | -0.2475 |
| Odds Ratio ($OR$) | 0.7807 |
| p-value | < 0.001 |
| Pseudo $R^2$ | 0.0187 |

### Interpretation of Results
The regression coefficient for sleep duration is a negative value ($\beta = -0.2475$), indicating that longer sleep duration is associated with a lower likelihood of feeling sad or hopeless.
The odds ratio ($OR = 0.7807$) indicates that for each one-level increase in the sleep category, the odds of feeling sad or hopeless decrease by approximately 21.9%.

## Research Conclusion
The Logistic Regression analysis results show that sleep duration has a significant predictive effect on the likelihood of high school students feeling sad or hopeless ($p < 0.001$).
Since the p-value is smaller than the significance level $\alpha = 0.05$, the null hypothesis is rejected.
Overall, students with shorter sleep duration are more likely to experience feelings of sadness or hopelessness, while more sufficient sleep is associated with a lower risk of negative emotions.

## Project Repository
https://github.com/t113370450-stack/Final-project/tree/main

## Presentation Video
https://youtu.be/pR-4DRYA4W0
---
# Final-project
## Student Information
name：113370450 蘇孟孜

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
