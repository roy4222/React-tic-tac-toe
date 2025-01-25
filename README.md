# 井字遊戲 (Tic-Tac-Toe)

這是一個使用 React + Vite 開發的網頁版井字遊戲。

## 專案說明

這個專案是一個經典的井字遊戲（圈圈叉叉）的現代網頁實現。遊戲支援兩位玩家在同一台電腦上輪流進行遊戲。

## 技術架構

本專案使用以下技術開發：
- React - 使用者介面框架
- Vite - 前端建構工具
- 專案使用了兩個官方插件：
  - [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) - 使用 Babel 實現快速刷新
  - [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) - 使用 SWC 實現快速刷新

## 安裝與運行

1. 安裝依賴套件：
```bash
npm install
```

2. 啟動開發伺服器：
```bash
npm run dev
```

3. 建置生產版本：
```bash
npm run build
```

## 遊戲功能

- 支援兩位玩家輪流下棋
- 自動判斷獲勝條件
- 顯示當前玩家回合
- 遊戲結束時顯示獲勝者
- 支援重新開始遊戲

## 開發相關

- 使用 `npm run dev` 啟動開發模式，支援熱更新（HMR）
- 專案包含 ESLint 規則，確保程式碼品質
- 使用 Vite 作為建構工具，提供更快的開發體驗
