NOVA VISION V5.1 Camera Diagnostic

这不是最终视觉版本，而是专门排查摄像头问题的诊断版。
它会显示：
- 是否为安全上下文
- getUserMedia 是否存在
- 摄像头权限状态
- 摄像头设备状态
- 浏览器返回的真实错误名
- 实际视频分辨率

使用：
1. 上传 index.html 到 GitHub Pages。
2. 打开 HTTPS 网站。
3. 点击 CHECK CAMERA。
4. 如果失败，不要反复猜权限；直接把左下角 ERROR 那一行截图发回。
5. 如果显示 CAMERA OK，说明摄像头没问题，再继续接 AI。
