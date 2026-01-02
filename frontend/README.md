# 前端專案安裝與啟動教學

> 本專案使用 **Angular 19**，請依照以下步驟安裝相容版本的工具與套件。

## 1. 安裝 Node.js 與 npm
請至 [Node.js 官方網站](https://nodejs.org/) 下載並安裝 **Node.js 18.x 或 20.x**（建議使用 LTS 版本，安裝後會自動包含 npm）。

## 2. 安裝 Angular CLI 19
打開命令提示字元或 PowerShell，輸入以下指令安裝指定版本的 Angular CLI：
```
npm install -g @angular/cli@19
```

## 3. 安裝專案依賴套件
進入 `/frontend` 資料夾，執行：
```
npm i
```


## 4. 啟動前端專案
在 `/frontend` 資料夾下執行：
```
ng s
```


啟動後可於瀏覽器開啟 [http://localhost:4200](http://localhost:4200) 查看專案。
