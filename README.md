# 口袋节奏 / Beatbox Practice

中文 Beatbox 练习网页，纯静态 HTML / CSS / JavaScript，无依赖、无需构建。

## 功能
- 40–180 BPM 节拍器与点击测速
- 四组练习节奏、8 / 16 格音序器、点击修改节奏
- B / T / PF 合成鼓声示范与键盘打击垫
- 基础音发声提示与练习路线
- 麦克风录音、回听与下载（最长 5 分钟）
- 本机保存设置和累计播放时间，响应式手机布局

## GitHub Pages
1. 创建公开仓库 `beatbox-practice`。
2. 上传本目录内文件，让 `index.html` 位于仓库根目录。
3. 在仓库 Settings → Pages 中，选择 Deploy from a branch。
4. 选择 main 分支和 / (root)，保存。
5. 发布完成后，以 Pages 显示的 URL 为准。若用户名为 PaoShou-China，项目默认地址为 https://paoshou-china.github.io/beatbox-practice/ 。

## 本地运行
直接打开 index.html 可以练习；录音请使用 HTTPS 网站或 localhost。
可以在本目录运行 `python3 -m http.server 8000`，访问 http://localhost:8000 。

## 使用
空格：播放 / 停止；B / T / P：底鼓 / 闭合镲 / 小鼓。
点击节奏格循环切换休止、B、T、PF。更换预设会停止播放。
示范为合成打击乐，不是真人口技录音，也不提供自动音色评分。
推荐录音时戴耳机。录音不会上传，刷新前请下载想保留的练习。
浏览器切到后台时暂停节拍播放，录音需手动停止，或到 5 分钟自动停止。
累计练习时间按节奏播放时间统计。

## 验证范围
已检查 JavaScript 语法；实际浏览器音频与麦克风权限需在部署后确认。
