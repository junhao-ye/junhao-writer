# Junhao Writer 來源與適配

| 來源 | 權重 | 採用方式 |
| --- | --- | --- |
| 本次使用者指示 | 直接需求，高 | 使用 Junhao Writer 作為品名，結合獨立理財規劃視角與細膩的對話感。繁體中文沿用使用者語言。 |
| 本機 `khazix-writer` 主檔、`content_methodology.md` 與 `style_examples.md` | 指定參照，高 | 採用素材先行、挑選稿型、具體開頭、回扣主線、原創改稿對照及四層自檢。 |
| 本機 `skill-writer` 與 `junhao-thinking-toolkit` | 封裝與措辭慣例，高 | 採用入口、平面參考檔、維護規格與來源分工。借鑑繁體中文措辭和事實邊界。 |
| 蔡康永談溝通與自我理解，一手訪談 | 風格線索，主題高、完整文風中 | 取從關係出發、避免替人判斷、藉提問讓人看見自身選擇的表達方法。示例另行原創。 [迷誠品訪談，由天下雜誌刊載](https://www.cw.com.tw/index.php/article/5094841?template=fashion) |
| Financial Planning Standards Board，Financial Planning Process | 專業原則，一手，高 | 採用目標優先、質性與量化一起考量、分析風險及假設、比較策略與揭露利益。各地監管與產品事實由個別稿件查核。 [FPSB 理財規劃流程](https://fpsb.org/about-financial-planning/financial-planning-process/) |
| Agent Skills Specification | 格式，一手，高 | 採用與目錄相同的 `name`、清楚的 `description` 和相對路徑。 [Agent Skills 規格](https://agentskills.io/specification) |
| On Substack 與 Substack Help Center | 平台，一手，高 | 採用標題、副標與原生區塊的結構，確認手機／電子郵件預覽、試讀及 Notes 的差異。具體段落長度和刊末邀請屬 Junhao Writer 編輯預設。 [Substack 排版編輯指引](https://on.substack.com/p/posting-consistently-formats-style) · [預覽稿件](https://support.substack.com/hc/en-us/articles/4433990875796-Can-I-see-how-a-post-will-look-like-to-readers-before-publishing) · [測試郵件](https://support.substack.com/hc/en-us/articles/360037832371-How-do-I-send-a-test-email-of-a-post-on-Substack) · [付費試讀](https://support.substack.com/hc/en-us/articles/4407989020308-How-do-I-publish-a-free-preview-of-a-paid-post-on-Substack) · [訂閱按鈕](https://support.substack.com/hc/en-us/articles/21785120910356-What-do-readers-see-when-I-insert-a-Subscribe-now-button-into-a-post-on-Substack) · [Notes](https://support.substack.com/hc/en-us/articles/14564821756308-Getting-started-on-Substack-Notes) |

## 設計決策

- 採用工作流程型寫作技能，主流程留在入口。文風示例、深入財務查核與 Substack 排版各存一檔，按稿件需要載入。完整 Substack 文章另交付副標欄，原生元件的插入說明留在編輯備註。
- `khazix-writer` 的選題門檻改成讀者處境、決策變數與素材。固定口頭禪、篇幅、標點、作者署名與推廣尾部省略。案例與示例全新撰寫，保留技法並歸功於工作流來源。
- 承接 `skill-writer` 的工作流程範例，涵蓋正常輸入、缺關鍵資料時的退路、品質確認和執行邊界。把來源、維護與執行檔分開，避免每次寫作載入背景。

## 覆蓋與限制

| 維度 | 覆蓋 | 驗收情境 |
| --- | --- | --- |
| 素材到成稿、改稿與續寫 | 完整 | 頭期款專欄、從逐字稿起稿、指定只改一段。 |
| 聲音與關係敏感度 | 初版 | 同理提問、文章與客戶信切換、去除道德評分。 |
| 風險、資料不足與失誤修正 | 完整 | 稅務信避免先承諾、明示試算假設、案例去識別。 |
| 格式、觸發、交付 | 完整 | 開啟對應參考檔、區別純試算、輸出可直接使用的正文。 |
| Substack 排版 | 指引與示例 | 手機可掃讀的文章、資訊足夠的付費試讀、可獨立理解的 Notes。 |

本版以原創示例當作校準材料。使用者尚未提供自己的公開稿、已定稿的客戶文字或偏好回饋。這些材料可用於後續校準。現有指定樣板、一手訪談和理財流程已支援初版，繼續蒐集同類公開內容對個人聲音的增益有限。

## 觸發走查

| 測試請求 | 預期 |
| --- | --- |
| 把這份訪談稿寫成談退休生活的電子報 | 使用，從素材找一個生活選擇。 |
| 用 Junhao 的口吻潤一下這封給客戶的信，只改結尾 | 使用，只調整結尾並保留原承諾。 |
| 幫我接著寫這篇夫妻如何談錢的文章 | 使用，承接敘事人稱及未解問題。 |
| 把這篇換工作的理財長文排成 Substack 電子報 | 使用，交付標題欄、副標欄與正文，保留原文觀點。 |
| 從這篇理財文寫一則 Substack Notes | 使用，交付可獨立理解的短文。 |
| 幫我算每月存 1 萬元，10 年後有多少 | 依試算任務處理。 |
| 幫我選一檔 ETF 今天進場 | 依原金融資訊任務處理。 |
| 幫我把這份純技術公告改成一頁摘要 | 缺少相關主題或指定文風，依摘要任務處理。 |
| Substack 的訂閱設定在哪裡？ | 依平台操作問答處理。 |

描述包含素材轉稿、限定幅度的改稿、續寫、常見主題、Substack 排版及個人化決策的邊界。
