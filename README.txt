NOVA VISION V4.1 — BLACK SCREEN FIX

核心修复：
1. 摄像头原始视频直接显示，不再依赖 Canvas/AI 回调才能看到画面。
2. Face Mesh 与 Hands 降频运行，避免老 Mac 同时跑两个模型造成卡死。
3. AI 出错不会隐藏摄像头画面。
4. 增加 CAMERA / FACE AI / HAND AI 状态。
5. 摄像头使用 640x480 上限，针对 2015 Intel Mac 降负载。

部署：
上传 index.html 到 GitHub Pages，使用 HTTPS 打开并允许摄像头权限。
