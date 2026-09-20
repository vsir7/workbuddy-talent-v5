# WorkBuddy 人才版 V5

这是可直接推送到 GitHub 仓库的完整 HTML 演示目录。

## 在线预览

使用 GitHub Pages 时，将发布来源设置为仓库根目录，入口文件为 `index.html`。

## 本地预览

请通过本地 HTTP 服务打开，避免浏览器对 `file://` 视频播放的限制：

```bash
python3 -m http.server 8000
```

然后访问 `http://127.0.0.1:8000/`。

## 目录说明

- `index.html`：V5 演示入口，页面代码、字体及主要图片已内嵌。
- `assets/workbuddy-v5/videos/`：三个产品演示视频。
- `assets/workbuddy-v5/posters/`：视频封面。
- `assets/workbuddy-v5/mascots/`：WorkBuddy 虚拟人物素材。
- `assets/workbuddy-v5/experts/`：专家团人物素材。
- `assets/workbuddy-v5/`：二维码、品牌主视觉、生成说明及其他源素材。
- `FILE_MANIFEST.sha256`：文件完整性校验清单。

## GitHub 文件限制

当前单个视频均小于 GitHub 的 100 MB 单文件限制，可直接提交。视频文件较大，首次推送需要一定时间。
