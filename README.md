# ROUGUANG VIDEO · 柔光影像

纯视频展示站 — https://kylemengkdev.github.io/rouguang-video/

## 加片方法
1. 视频文件放进 `videos/`，封面图（可选）放进 `posters/`
2. 打开 `index.html`，在顶部 `VIDEOS` 数组里加一条：
```js
{ n:'01', title:'片名', src:'videos/xx.mp4', poster:'posters/xx.jpg', dur:'02:15', year:'2026', note:'一句话' }
```
3. 提交推送即可（无构建，纯静态）
