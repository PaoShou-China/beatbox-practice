# Pocket Rhythm / 口袋节奏 · V3

A bilingual, browser-local Beatbox practice and listening studio. Plain HTML/CSS/JavaScript; no dependencies or build step.

**Live:** https://paoshou-china.github.io/beatbox-practice/

## 功能 / Features

- 中文 / English; responsive grouped page navigation, browser history / direct hash links, focus practice mode.
- Paginated listening (6 cards), classic tutorials (4 cards) and pattern library (12 presets).
- 32 editable rhythm presets; five reference slots B/T/PF/K/O, with real human recordings for all five sounds by default.
- 40–200 BPM, tap tempo, quarter/eighth/triplet/sixteenth grids, eighth-note swing.
- Count-in, silent-bar challenges, gradual tempo ramp, timed sessions.
- Keyboard/pad timing feedback, playback statistics and seven-day chart.
- Named patterns, JSON import/export, text notation input, rotate/reverse/snare swap/skeleton tools.
- Pattern share URLs, text-score download and four-loop selected-pack WAV export.
- Eight classic tutorial cards with original video links and staged companion drills.
- 13 listening cards: solo, battle, loopstation, crew and song; filters, search, random recommendation, favorites, watched status and notes.
- 28-day self-paced learning path, generated daily plans, independent focus timer.
- Selected-pack sound identification challenge; 18 glossary terms and six knowledge cards.
- Journal, daily playback goal, six subjective skill ratings.
- Local audio waveform, A–B loops, playback speed and WAV segment export (10-minute/50 MB limit).
- Full JSON backup/restore of browser-local data (excluding recordings).
- Up to five temporary microphone recordings, five-minute limit, playback speed and download.

## Notes / 说明

默认 B/T/PF/K/O 全部使用真人录音，每类 2 个样本，可切换合成对照包。经典配套谱是原创简化预备练习，不是逐音转录；完整段子以原视频为准。鉴赏提示是本站的观察建议，不是原作者的作品解读。外部视频可能受平台或地区限制。

Timing feedback measures keyboard/click timing, not microphone sound accuracy. Device latency affects results. Ear challenges teach the synthesized sounds only. Skill ratings and learning checkboxes are self-reported.

Data stays in this browser. Download recordings before refreshing and export backups regularly. Restore replaces local data after confirmation. Shared URLs include the current pattern only. WAV exports use the selected pack and exclude your microphone recordings. Focus timer time is separate from studio playback statistics.

Space toggles playback; B/T/P/K/O trigger sounds outside form controls. Hidden tabs pause the studio; the independent focus timer follows wall-clock time.

## Develop / 本地运行

Run `python3 -m http.server 8000` in this directory, then open http://localhost:8000 . Recording requires HTTPS or localhost.

GitHub Pages deploys the main branch root. Edit index.html to update the site.

## Human sample foundation pack

Default demo uses ten real recordings: B/T by ipaghost (CC0-1.0, public HQ MP3 previews), explicitly labelled PF/outward K demonstrations by Spencer X (CC BY 3.0), and annotated open hi-hats by Pepouni from Beatboxset1 (CC BY-SA 3.0). Every sound alternates two samples. No synthesized fallback is used in human mode: missing or failed audio is reported as an error. Pads, sequencer, five-choice ear challenges and WAV export share the selected pack. Exported human WAVs carry source and license credits in a RIFF INFO comment; adapted audio containing O must be shared under CC BY-SA 3.0 with attribution. Source links, exact excerpt times, processing and licensing are in assets/CREDITS.md. Synthetic comparison remains available.

## Practice usability update

- Compact, collapsible practice settings and a persistent studio transport with start/stop and ±5 BPM controls.
- Mobile navigation scrolls in a single row; note grids use four columns on small screens. Touch pads trigger on pointer-down and show immediate pressed feedback.
- Undo/redo for pattern edits and transformations (up to 50 steps; Ctrl/Cmd+Z, Shift+Z or Ctrl/Cmd+Y outside text fields).
- Basic lessons include real-sample previews and one-click 60 BPM isolated drills, with count-in enabled.
- Live audio sources are canceled on stop, and canceled sample loading cannot later start the sequencer.
- Human WAV exports are peak-balanced when needed to avoid hard PCM clipping; license metadata stays embedded.
