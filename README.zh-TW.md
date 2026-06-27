# FUTU 自定義指標

適用於 FUTU 交易平臺（Mai 語言）的自定義技術分析指標。

**鳴謝：** 本指標靈感來自 FUTU 平台上的 "泡泡龍講投資"（bubbledragon_investment）圖表，感謝他的啟發！  
**參考文件：** [FUTU Mai 語言文件](https://www.futufin.com/cn/hant/support/topic1_541)

## 安裝方法

1. 打開 FUTU 交易平臺
2. 選擇任意股票 → 圖表 → 指標 → 自定義，點擊 '創建新的自定義指標'
3. 點擊 'Mai 語言'，將 `COLOR.ftindex` 中的腳本貼上進去，然後點擊 '應用'
4. 指標將出現在您的自定義指標列表中

## 指標

### COLOR.ftindex - 移動平均線雲

一種趨勢跟蹤指標，在兩條移動平均線之間顯示彩色雲層。

**功能特點：**
- 通過雲層可視化顯示價格趨勢強度
- 紅色雲層表示牛市趨勢（MA1 > MA2）
- 綠色雲層表示熊市趨勢（MA1 < MA2）
- 白色和黃色線條分別表示 MA1 和 MA2

**參數說明：**
- `P1`: 第一條移動平均線的週期
- `P2`: 第二條移動平均線的週期

**使用方法：**
將此指標應用於任何圖表，根據雲層寬度和顏色判斷趨勢方向和強度。

## 截圖

![安裝指南](screenshots/installation-01.png)

![移動平均線雲指標示例 1](screenshots/screenshot-example-01.png)

![移動平均線雲指標示例 2](screenshots/screenshot-example-02.png)
