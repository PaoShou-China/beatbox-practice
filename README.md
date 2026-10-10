# Pocket Rhythm / 口袋节奏

A bilingual, browser-local Beatbox practice studio. Built with plain HTML/CSS/JavaScript; no dependencies or build step.

**Live:** https://paoshou-china.github.io/beatbox-practice/

## 中文

右上角切换中文 / English。支持：
- 12 组节奏预设、随机节奏、逐格编辑
- 40–200 BPM、点击测速、总音量
- 四分 / 八分 / 三连 / 十六分细分，八分摇摆比例
- 预备拍、静音挑战、渐进加速、目标 BPM 上限
- 1 / 2 / 5 / 10 分钟限时训练
- B / T / PF / K / O 五种合成鼓声与基础音学习卡
- 打击垫 / 键盘时机偏差与平均绝对偏差
- 命名保存节奏、载入、删除、JSON 导入导出（最多 50 组）
- 最多 5 段临时录音、慢速 / 加速回听、下载
- 累计练习时间和近 7 天练习图

键盘：空格启停；B / T / P / K / O 触发鼓声。焦点位于输入控件或按钮时快捷键不接管。

示范音是合成打击乐，不是真人口技。跟拍反馈测量按键 / 点击时机，不分析麦克风音色或指定音符匹配，设备延迟会影响偏差。
录音不会上传；最多每段 5 分钟，刷新页面前请下载。设置、命名节奏与练习统计保存在本机浏览器。
限时训练从按下开始计时，包含预备拍。切到后台暂停练习，录音需手动停止或等 5 分钟自动停止。

## English

Use the top-right language switch. Features include 12 presets, editable and random patterns, 40–200 BPM, tap tempo, quarter/eighth/triplet/sixteenth grids, eighth-note swing, count-in, silent-bar challenges, progressive tempo with a ceiling, timed sessions, five drum pads, sound learning cards, pad timing feedback, named patterns, JSON import/export, temporary recordings, playback speed, downloads, and a seven-day practice chart.

Space toggles playback; B/T/P/K/O trigger drum sounds unless a form control is focused.
Timing feedback measures keyboard/click offsets, not microphone audio or pattern accuracy. Synthesized drums are rhythm references. Audio is never uploaded. Download recordings before refreshing.

## Develop / 本地运行

Run `python3 -m http.server 8000` in this directory, then open http://localhost:8000 . Recording requires HTTPS or localhost.

GitHub Pages deploys the main branch root. Edit index.html to update the site.

## Classic routines / 经典段子教学

Eight bilingual lesson cards: Boots and Cats, BTK, Wind, Put Your Hands Up, Roxorloops, Skiller breathing, Make It Bun Dem, and Alem snare/humming.

Each card includes a linked original tutorial, learning focus, three practice steps and companion drum drills at skeleton, slow and suggested tempos. Filter by difficulty or video language.

Companion drills are original simplified practice arrangements for this website, not verified note-for-note transcriptions of the routines. Full routines and special sounds must be learned from the linked teacher. Video titles and links were checked through web search on 2026-10-10; some pages restrict automated retrieval, so actual playback may depend on region, login and platform availability.

Sources: Kenny Urban / Lessonface; Binibining Beats / YouTube; Qualia and beatboxer小脑 / Bilibili. Videos open externally and are not downloaded or rehosted.
