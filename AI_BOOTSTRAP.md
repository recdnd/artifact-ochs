# AI Bootstrap - OCHS

**讀取順序**

1. **What this is** → `../sov/cyc/artifacts/ochs.md`
2. **Where I am** → `cyc/journal.md` 最近 3 條
3. **How it should look** → `--` (exhibit is the anti-pattern; 噁心度表 is the inverse)
4. **How to act** → machine specs: `01-deploy`, `02-localhost`, `11-hosting`

**當前焦點**: exhibit 正本只有 `index.html` (整合版)

**戒律**: 不要把這站修成「好前端」. DNS 走 porkbread `sus.mom` 的 `ochs` CNAME. 不上 API keys.

**雙語**: 中文是正本, 英文走 `index.html` 裡的 `I18N_EN` 手翻字典 (非中文瀏覽器自動切英文). 新加任何中文字串 (含 agent 小話 / toast / 橫幅 / alert) 要同時加一條英文; `?lang=en` 打開後 console 看 `I18N_MISS` 應為空.
