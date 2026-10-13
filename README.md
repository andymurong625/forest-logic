# 森林逻辑乐园

免费儿童逻辑小游戏，优先适配 iPad，支持 iPhone。144 道题、8 类玩法、Serena 中文配音与离线缓存。

[打开游戏](https://andymurong625.github.io/forest-logic/)

用 Safari 打开游戏，分享 → 添加到主屏幕。首次联网等待“可以离线玩”后再断网。记录只保存在设备，不上传儿童数据。

## 文件

- `site.zip`：完整静态网页和 331 段配音。GitHub Actions 解压并发布到 Pages。
- `source.zip`：TypeScript 源码、题库、测试和安装说明。解压后将 site.zip 中 audio 文件夹复制到 public/audio/，即可本地构建。

配音使用 Qwen3-TTS 1.7B CustomVoice 的 Serena 音色。无广告、账号或付费 API。真实 iPad 的声音与交互效果仍需实机验收。
