# 第一個錢包：MetaMask 設置指南

## 什麼是 MetaMask？

MetaMask 是最流行的加密錢包，讓你能：
- 安全儲存加密貨幣
- 連接 DeFi 協議
- 購買和管理 NFT
- 與 Web3 網站互動

## 安裝 MetaMask

### 瀏覽器版本（推薦）
1. 到 [metamask.io](https://metamask.io)
2. 點「Download」選擇你的瀏覽器
3. 安裝擴充功能

⚠️ **確認網址是 metamask.io，不是其他！**

### 手機 App
- iOS：App Store 搜尋 MetaMask
- Android：Google Play 搜尋 MetaMask

## 創建錢包（第一次使用）

### Step 1: 開始設置
- 點「Create a new wallet」
- 建立密碼（這是 App 密碼，**不是助記詞**）

### Step 2: 觀看安全影片
- MetaMask 會播放一段安全教學
- **認真看！這很重要**

### Step 3: 記下助記詞
- 點「Reveal Secret Recovery Phrase」
- **這是 12 個英文單字**
- **用筆抄寫在紙上**
- 不要截圖、不要拍照、不要存雲端

### Step 4: 驗證助記詞
- MetaMask 會要求你選出正確順序的單字
- 確認你抄對了

### ✅ 完成！

## 錢包介面介紹

```
┌─────────────────────────┐
│  0x1234...abcd          │  ← 你的地址（點擊複製）
│  0 ETH ($0.00)          │  ← 餘額
│                         │
│  [Buy] [Send] [Swap]    │  ← 主要功能
│                         │
│  Assets    Activity     │  ← 切換資產/交易紀錄
│  ├─ ETH                 │
│  └─ NFTs                │
└─────────────────────────┘
```

## 添加網路

MetaMask 預設只有 Ethereum，你可以添加其他網路：

### 添加 Arbitrum（L2，便宜快速）
1. 點網路下拉（預設顯示「Ethereum Mainnet」）
2. 「Add network」
3. 選「Add a network manually」
4. 填入：
   - Network Name: Arbitrum One
   - RPC URL: https://arb1.arbitrum.io/rpc
   - Chain ID: 42161
   - Currency Symbol: ETH
   - Block Explorer: https://arbiscan.io

### 常用網路設定

| 網路 | Chain ID | RPC URL |
|------|----------|---------|
| Ethereum | 1 | https://ethereum.publicnode.com |
| Arbitrum | 42161 | https://arb1.arbitrum.io/rpc |
| Base | 8453 | https://mainnet.base.org |
| Optimism | 10 | https://mainnet.optimism.io |
| Polygon | 137 | https://polygon-rpc.com |

## 取得第一筆 ETH

### 方法 1: 從交易所轉帳
1. 在幣安/Coinbase 買 ETH
2. 提領到 MetaMask 地址
3. 選擇正確的網路（Ethereum/Arbitrum/Base）

### 方法 2: 直接購買（較貴）
- MetaMask 內建「Buy」功能
- 用信用卡購買（手續費較高）

### 方法 3: 請朋友轉一點
- 要朋友轉 $10-20 的 ETH
- 用於支付 Gas 費用

## 基本操作

### 接收資產
1. 點地址（自動複製）
2. 把地址給對方
3. 確認對方使用正確網路

### 發送資產
1. 點「Send」
2. 貼上對方地址
3. 選擇資產和數量
4. 檢查 Gas 費用
5. 確認交易

### 連接網站
1. 訪問 DeFi 網站（如 Uniswap）
2. 點「Connect Wallet」
3. 選 MetaMask
4. 在跳出的視窗確認

## 重要提醒

### ⚠️ 絕對不要做
- 不要把助記詞給任何人
- 不要在任何網站輸入助記詞
- 不要用截圖/雲端儲存助記詞

### ✅ 應該要做
- 備份助記詞在紙上
- 小額測試再轉大額
- 確認地址正確（頭尾幾個字母）

---

> 💡 **下一步**> > 現在你有錢包了，建議：> 1. 轉入少量 ETH 測試
> 2. 練習發送和接收
> 3. 連接 Uniswap 試試看
> 4. 讀完 [安全須知](security.md) 再投入大額
