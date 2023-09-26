# 只是個時鐘
只是個小時鐘而已，也可以自己把時間或日期的 `<div>` 拔掉，只顯示時間或日期，  
保留 `<div data-time></div>` 表示只顯示時間；  
保留 `<div data-date></div>` 表示只顯示日期；  

# 預覽結果
![Image](https://image.haer0248.me/jvp1sR.png)

# 下載
下載 index.html 並存放到您的本機位置（檔案不可以刪除或移動，否則 OBS 會找不到檔案）  
放入 OBS：
1. 選擇「瀏覽器」，勾選「本機檔案」，選擇您的檔案存放位置
2. 將檔案「拖曳」進入 OBS

建議寬高：
寬 `300` 高 `150`

# 設定字體
- 前往 https://fonts.google.com/ 選擇字體後依照指示進行設定

1. 選擇想要的字體後，點選旁邊的 +
*(粗一點就選 Medium 以上，預設請選 Regular)*
![Image](https://image.haer0248.me/K9fJ5E.png)

2. 旁邊會跳出 `Review`，在 `Use on the web` 選擇 `@import`
*(沒有自動跳出來可以按最上方的購物袋)*
![Image](https://image.haer0248.me/Ea1rwf.png)

3. 覆蓋下方 `@import` 網址
![Image](https://image.haer0248.me/k087EF.png)

4. 在 `CSS rules to specify families` 中複製，覆蓋下方 `*` 中的 `font-family: ... ;`
![Image](https://image.haer0248.me/QFv6sY.png) 
![Image](https://image.haer0248.me/Hf0dhm.png)

# 背景 (CSS)
如果覺得背景太深，可以刪除幾行 `text-shadow` ，反之太淺可以新增。

預設參數
```css
text-shadow:
    1px 1px 10px var(--background-color),
    1px 1px 10px var(--background-color),
    1px 1px 10px var(--background-color),
    1px 1px 10px var(--background-color);
```
