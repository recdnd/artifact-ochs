# OCHS - journal

Updated: 2026-10-07
Entries: 4
Split: no

---

## 常駐規約 (持續適用, 非 entry)

- 線上域名固定 `ochs.sus.mom`. 正本頁是 `index.html`.
- 這站的 UI 是嘲諷展品, 不是工作台.

---

## 紀錄 (倒序, 最新在上)

### 2026-09-17 -- 不疊 modal, 全站翻譯, AI upsell 與一串陷阱

**Why**
主筆: 它必須看起來非常完整只是噁心, 不是一個做壞了的前端. 外加 AI upsell 小窗 / fab hover tip / 角落小 x / 自動翻譯.

**What**
5f8c844 .. a0601e3: SMS MFA + 兩輪 captcha / 彩虹 favicon + Outlook 式陷阱 / 內建瀏覽器 + 閒置橫幅 / 右下 AI upsell / fab tip + 有限返回 + 9px x / spawn* 改成在最上層 panel 內長 (只有一層 backdrop) + Google Translate 自動翻譯.

**Result**
已推. 細節在 `b-rec/docs/🎀專案開發書/OCHS/01-開發手記.md`.

### 2026-09-16 -- v4 agent 小話撒全元件

**What**
v4 固定句放回原位 + MURMURS 池 44 句由 sprinkle() 撒到標題 / label / 按鈕 / chip / modal / toast / 底欄, 實測 141 句 + 27 個 title.

**Result**
19e824d 已推.

### 2026-09-16 -- 整合版, 加慢動畫

**Why**
主筆: 不需要再 v6 / v7, 做一個整合版, 並且加大各種動畫的緩慢噁心力度.

**What**
只留 `index.html`. 刪掉 ugly_v5 / v6 / v7. 背景漂 / 頂欄液移 / 玻璃呼吸 / 標題爬色 / modal 2.4-2.8s 糊進 / toast 與鈕 stagger / 進度條與內建瀏覽器再放慢.

**Result**
正本一頁.

### 2026-09-16 -- 立項 + GH Pages

**Why**
主筆指定為 OCHS 註冊 rituals, 上線 `ochs.sus.mom`.

**What**
骨架 / CNAME / rituals / port 4444 / repo `recdnd/artifact-ochs`. 現役頁從 ugly v7 拷成 `index.html`.

**Result**
本機與 GitHub Pages 可推. `sus.mom` 當時未開 Porkbun API, DNS 待開通後 `pb.py dns add`.
