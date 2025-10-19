# yuto-horigome-skate-analysis
Analysis of Yuto Horigome's competitive strategy using public data.
---
# 🛹 堀米雄斗の「勝負強さ」の解剖：データが示す極限下のパフォーマンス

このリポジトリは、堀米雄斗選手（ストリートスケートボード）のオリンピック決勝における試技データを定量的に分析し、**極限状況における精神力と戦略**を可視化したポートフォリオです。

---

## 📊 主要な洞察（Key Insights）

分析結果から、堀米選手が**「追い込まれるほど強くなる」**特性を持つことが示されました。

### 1. 圧倒的な勝負強さ：プレッシャーを支配する

堀米選手は、一般的な成功率を大きく超える**「異常なまでの勝負強さ」**を発揮しています。

| 指標 | 成功率/スコア | 背景・インサイト |
| :--- | :--- | :--- |
| **最終試技の成功率** | **100.00%** (2/2) | **試技番号5回目**（最も追い込まれる状況）での成功率は驚異の100%。ラストトリックを必ず決め切る**精神力の証明**です。 |
| **追い込まれた状況の成功率** | **75.00%** (3/4) | 試技前の順位が4位以下（表彰台圏外）だった場合の成功率は75.00%。**「負けられない」状況でパフォーマンスを向上**させる特性を示します。 |

### 2. リカバリー力の高さ：失敗を引きずらない

失敗直後のリカバリー能力を比較すると、精神的な強さが際立ちます。

| 状況 | 成功率 | 比較 |
| :--- | :--- | :--- |
| **通常時成功率** | 66.67% (4/6) | 失敗直後ではないトライでの基本成功率。 |
| **失敗後の成功率** | **50.00%** (2/4) | 失敗後のトライでの成功率。通常時より低いものの、**失敗から即座に立ち直る**ための重要なベースラインです。 |
| **全トリック成功率** | *60.00%* (6/10) | 全試技の総成功率。 |

### 3. 戦略的アプローチ：ライバルが強い時ほどスコアが高い

ライバルがハイレベルなパフォーマンスを発揮している状況を抽出した結果、堀米選手は**「勝つためにスコアを上げる」**戦略的なアプローチを取っていることが推測されます。

| ライバルがトップの時の成功時平均スコア | Nyjah Huston | Jagger Eaton | Kelvin Hoefler | 全体平均 |
| :--- | :--- | :--- | :--- | :--- |
| **平均点** | 94.16 | **95.19** | 91.65 | *93.84* |

特に Jagger Eaton 選手がトップにいる時、平均スコアが**95点超**と最も高くなっており、トップレベルのプレッシャーが**最高難度のトリック成功**を促していると分析できます。

---

## 🛠️ データソースと分析手法

### 使用データセット
* **ファイル名**: `horigome_raw_data.csv`
* **データ期間**: **東京2020** (2021年7月) **と パリ2024** (2024年7月) の**決勝試技のみ**を対象。
* **内容**: オリンピックの決勝における、試技ごとの詳細なログデータ（スコア、順位、トライ回数など）。
* [**データセットへのリンク**](https://github.com/Mina-StreetDataLog/yuto-horigome-skate-analysis/blob/main/horigome_raw_data.csv) 👈 

### 定義した指標
* **リカバリー力**: 試技前の結果が「失敗」であった場合の次の試技の成功率。
* **追い込まれた状況**: 試技前の順位が4位以下（表彰台圏外）と定義。
* **`trick_difficulty`**: (注記) トリックの客観的な難易度を定量化する統一基準がないため、この列は現在ブランクです。

### ツールと環境
* Google Sheets (データクレンジング, 集計)
* GitHub (ポートフォリオ公開)

---

## 📜 ライセンス

This project is licensed under the **MIT License**. データは自由に利用、改変、再配布が可能です。利用の際は、原作者（Mina-StreetDataLog）へのクレジットを明記してください。


---
# 🇺🇸 English Report: 🛹Yuto Horigome's Clutch Performance Dissected

This repository presents a quantitative analysis of Yuto Horigome's attempts in Olympic finals, revealing his **mental fortitude and competitive strategy** under pressure.

## 📊　Key Insights
The analysis results clearly demonstrate Yuto Horigome's characteristic of thriving under pressure.
### 1. Exceptional Clutch Performance: Dominating Under Pressure
Horigome exhibits extraordinary mental toughness (clutch performance), significantly exceeding general success rates in high-stakes situations.
| Metric | Success Rate/Score | Insight |
| :--- | :--- | :--- |
| **Final Attempt Success Rate** | **100.00%** (2/2) | A staggering 100% success rate on the **5th and final attempt**, which represents the most pressured moment. This is a clear indicator of **extreme mental fortitude**. |
| **Success Rate When Pressed** | **75.00%** (3/4) | The success rate is 75.00% when his rank before the attempt was 4th or lower (outside the podium contention). This demonstrates his ability to **elevate performance when facing a must-win situation**. |
### 2. Heightened Recovery: Bouncing Back from Failure

The comparison of success rates reveals Horigome's mental resilience and ability to reset after an unsuccessful attempt effectively.

| Situation | Success Rate | Comparison/Insight |
| :--- | :--- | :--- |
| **Normal Success Rate** | 66.67% (4/6) | The baseline success rate when the preceding attempt was not a failure. |
| **Post-Failure Success Rate** | **50.00%** (2/4) | The success rate on the attempt immediately following a failure. Although lower than the normal rate, this still indicates a crucial ability to **recover quickly** and maintain composure. |
| **Overall Trick Success Rate** | *60.00%* (6/10) | The total success rate across all attempts. |

### 3. Strategic Approach: Higher Scores Against Strong Rivals

By isolating situations where key rivals held the top spot, the data suggests Horigome employs a **strategic "score elevation" approach** to win.

| Rival Holding Top Rank (Successful Attempts) | Nyjah Huston | Jagger Eaton | Kelvin Hoefler | Overall Average |
| :--- | :--- | :--- | :--- | :--- |
| **Average Score** | 94.16 | **95.19** | 91.65 | *93.84* |

The average score is highest (**over 95 points**) when Jagger Eaton is in the lead, indicating that the pressure of facing the world's best drives him to **successfully execute the highest difficulty tricks**.
---

## 🛠️ Data Source and Methodology

### Data Set Used
* **File Name**: `horigome_raw_data.csv`
* **Data Period**: Only the **Final Attempts** from **Tokyo 2020** (July 2021) and **Paris 2024** (July 2024) are included.
* **Content**: Detailed log data for each trick attempt in the Olympic finals (score, rank, try count, etc.).
* [**Link to Data Set**](https://github.com/Mina-StreetDataLog/yuto-horigome-skate-analysis/blob/main/horigome_raw_data.csv)

### Defined Metrics
* **Recovery Power (Recovery Rate)**: The success rate of an attempt immediately following a failure.
* **Under Pressure Situation**: Defined as an attempt where the rank before the try was 4th or lower (outside of podium contention).
* **`trick_difficulty`**: (Note) This column is currently blank due to the lack of an objective, standardized metric for quantifying trick difficulty.

### Tools and Environment
* Google Sheets (Data Cleaning, Aggregation)
* GitHub (Portfolio Publication)

---

## 📜 License

This project is licensed under the **MIT License**. The data is free to use, modify, and redistribute. Please credit the original creator (Mina-StreetDataLog) when using the data.
