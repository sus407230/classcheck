# 今日缺席名單

這是一個可放到 GitHub Pages 的靜態網站，只有一個 `index.html`，不需要安裝其他軟體。頁面以黑底顯示缺席號碼，號碼會在上方區域移動；輸入號碼按 Enter 可加入，點號碼會播放爆炸效果並移除。

## 在電腦上預覽

直接用瀏覽器開啟 `index.html`。輸入學生號碼後按 Enter 加入；點擊畫面上的號碼可移除。

## 發佈到 GitHub Pages

1. 在 GitHub 建立一個新的 repository（儲存庫），例如 `attendance-list`。若不熟悉 Git，建立時可勾選加入 README。
2. 把這個資料夾裡的 `index.html` 上傳到 repository 的最上層（不要只上傳外層資料夾）。在 GitHub 網頁上可用 **Add file → Upload files**。
3. 開啟 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 選 **Deploy from a branch**；Branch 選 `main`，資料夾選 `/(root)`，按 **Save**。
5. 等待 Pages 發佈完成後，Settings → Pages 會顯示網站網址。

## 資料如何保存

目前名單保存在目前裝置的瀏覽器，並依日期分開。GitHub Pages 會讓不同電腦都能用網址打開網站，但不會讓不同電腦自動共用即時輸入的名單。若只在教室投影的那台電腦輸入、並由該電腦顯示，這個版本即可使用；若要讓多台電腦共用同一份名單，需要再接共享資料庫或表單服務。
