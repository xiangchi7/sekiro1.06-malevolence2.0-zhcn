# 只狼 mod「Malevolence」简体中文汉化 · Simplified Chinese Localization

**v2.0 · 2026-11** — 对应 mod「Sekiro Malevolence 2.0」。当前版本，与 Releases 里的 zip 是同一份
(current version, matching mod **Sekiro Malevolence 2.0**)

[中文](#中文) · [English](#english)

---

## 中文

为 *Sekiro: Shadows Die Twice* 的 mod「Malevolence」提供的简体中文语言包。
只替换 `msg\zhocn\` 下两个文本包，不改模型、参数、脚本，可随时删除还原。

### v2.0 更新

- 对齐 mod 2.0 的英文文本：新增条目全部汉化，改写的条目重新翻译。
- 新增潜在技能 **Rebounding Blade → 回刃**（道具名、技能名、技能说明、开关提示一致）。
- 新增异常状态帮助页：专注 / 不动架势 / 适应 / 幽界。
- 师范清正 2.0 新增对白 40 条、「无限城守卫 师范清正」等改动处已同步。
- 英文删去段落的条目（琉璃枪袭、爆竹机关·远投）中文同步删去，不再多出原文没有的句子。

### 安装

1. 运行 `install.cmd`（自动定位 Steam 库、备份 `*.bak`；找不到时把 `mods` 文件夹拖上去），
   或手动把 `msg` 复制进 `...\Sekiro\mods\`。`install.cmd /check` 只显示检测路径，不写文件。
2. 标题画面 → `Language` → `Text` → 简体中文 → 重启游戏。

回滚：`restore.cmd`，或删除 `mods\msg\zhocn\` 下这两个文件。

### 已知限制

1. EULA、版权与地区法律声明保留英文。
2. `OK`、`Mild`、若干 `WWW` 占位串保留原样。
3. 英文包另有 4 张表在中文包里缺失（`メニュー共通テキスト`、`メニューその他`、`項目ヘルプ`、
   `テキスト表示用タグ一覧`），内容为 Dark Souls 3 遗留文本；mod 未改动，官方简中同样没有，
   中文客户端不读取，对显示无影响。
4. 说明文的分段沿用官方简中；部分条目的中文段落空行比英文少，官方文本本身如此。

### 目录

```
msg/zhocn/item.msgbnd.dcx   道具/招式/敌人等文本
msg/zhocn/menu.msgbnd.dcx   菜单、对白、字幕等文本
install.cmd / restore.cmd
```

### 声明

- 需自备正版游戏与该 mod；本仓库仅含文本资源。
- 游戏文本版权归 FromSoftware / Activision；与 mod 原作者无关，接到要求即撤下。
- 译文为 AI 辅助并统一术语。报错请附表名、条目 id 与截图。

---

## English

Simplified Chinese language pack for the *Sekiro: Shadows Die Twice* mod **"Malevolence"**.
Replaces two text bundles under `msg\zhocn\` only — no models, params or scripts; remove it any time.

### v2.0 changes

- Re-synced to the mod's 2.0 English text: every new entry translated, rewritten entries retranslated.
- New Latent Skill **Rebounding Blade → 回刃** (item name, skill name, description and toggle labels match).
- New status-effect help pages: 专注 (Focused) / 不动架势 (Hyperstance) / 适应 (Adapt) / 幽界 (Astral Realm).
- 40 new Shihan Kiyomasa lines plus the reworked "Infinity Castle Warden" entry.
- Entries whose English lost a paragraph (Lazulite Spear Assault, Firecracker Mechanic - Distant Cast)
  lost the corresponding Chinese sentence too — no text the mod does not have.

### Installation

1. Run `install.cmd` (finds the Steam library, backs up `*.bak`; drag your `mods` folder onto it if needed),
   or copy `msg` into `...\Sekiro\mods\`. `install.cmd /check` only prints the detected path.
2. Title screen → `Language` → `Text` → Simplified Chinese → restart.

Rollback: `restore.cmd`, or delete the two files under `mods\msg\zhocn\`.

### Known limitations

1. EULA, copyright and regional legal notices stay in English.
2. `OK`, `Mild` and a few `WWW` placeholder strings are left as-is.
3. Four tables present in the English bundle are absent from both the Chinese one and the official
   Chinese localization (`メニュー共通テキスト`, `メニューその他`, `項目ヘルプ`, `テキスト表示用タグ一覧`);
   they hold Dark Souls 3 leftovers, untouched by the mod and never read by the Chinese client.
4. Chinese paragraph breaks follow the official CN text; some entries keep fewer blank lines than the
   English version, exactly as the official localization does.

### Layout

```
msg/zhocn/item.msgbnd.dcx   items, Combat Arts, enemies
msg/zhocn/menu.msgbnd.dcx   menus, dialogue, subtitles
install.cmd / restore.cmd
```

### Notes

- Requires your own copy of the game and the mod; this repository contains text resources only.
- Game text is copyright FromSoftware / Activision. Not affiliated with the mod author; removed on request.
- Translations were produced with AI assistance and reviewed for terminology. Report issues with
  table name, entry id and a screenshot.
