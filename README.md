# 霓虹贪吃蛇

一个单文件的 HTML5 小游戏，打开就能玩，不需要任何依赖或构建步骤。

🎮 在线试玩：https://mingnandeng-web.github.io/neon-snake/

## 玩法

- 方向键 / `WASD` 控制方向
- `空格` 或 `P` 暂停 / 继续
- 手机在画面上滑动即可转向
- 吃到光点变长，撞墙或咬到自己就结束
- 每吃 5 个光点速度提升一档，最快 65ms 一步
- 最高分保存在浏览器 localStorage 中

## 本地运行

双击 `index.html`，或在终端执行：

```bash
open index.html
```

## 技术说明

- 纯原生 JavaScript + Canvas 2D，无第三方库
- 蛇身使用插值渲染，移动平滑不卡格
- 音效由 WebAudio 实时合成，没有音频资源文件
- 适配桌面与移动端，支持高分屏（devicePixelRatio）
