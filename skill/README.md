# Event Design Kit｜活動設計 Claude Skill

拿到活動主視覺之後，用 Claude 延伸出整套活動設計：視覺系統、講者素材包、各平台版本、現場物料、雙語活動網站。

來自聊心茶室「精神維他命 Mental Health Festival 2026」的實際製作流程。範例網站：https://chang7856.github.io/mhf-2026/

## 開始前先準備

1. 主視覺和插畫的原檔
2. 一位你喜歡的參考設計師，和他的 IG 或作品集連結
3. 活動資料：名稱、日期、時間、地點、票價、報名連結
4. 講者資料表：姓名、身份、一句 selling point、場次、照片
5. 品牌名稱的正確寫法

## 安裝

**Claude.ai 網頁版／桌面版**
1. 下載 [event-design-kit.zip](https://github.com/chang7856/mhf-2026/raw/main/skill/event-design-kit.zip)，不用解壓縮
2. 打開「設定 → 功能（Capabilities）」，確認「程式碼執行與檔案建立」已開啟
3. 在同一頁的 Skills 區塊按「上傳」，選這個 zip，然後把它打開

**Claude Code**
解壓縮後，把 `event-design-kit` 資料夾放到 `~/.claude/skills/`。

## 使用

1. 開一個新對話，說「幫我做活動設計」
2. 把上面準備的東西一起丟進去
3. Claude 會先列出缺的資料問你，再給你看視覺系統頁
4. 你點頭，它才做下一步：講者素材 → 各平台版本 → 現場物料 → 活動網站

不想裝 skill 也可以：直接把 SKILL.md 裡「直接可用的開場指令」那段貼給 Claude。

## 註記

- Skills 需要 Claude 付費方案（Pro、Max、Team 或 Enterprise）
- 插畫請上傳原檔。Skill 會要求 Claude 照用原圖，不重畫
- 講者介紹、票價、日期等資訊，發布前請自己再核對一次
- 活動網站做完是一個檔案，要自己放上 GitHub Pages 或其他網站空間才能分享

作者：張道芳 Jessie Chang｜https://www.linkedin.com/in/taofang-chang/
