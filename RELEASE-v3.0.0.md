# YoLuster Shorts v3.0.0

v3.0.0 围绕 AI 短剧从剧本到画面、再到视频结果的完整创作体验进行了集中更新，并同步提供新版 Docker 本地体验包。

## 本次更新

- 完善剧本导入、分集解析与分镜规划流程，让长剧本和多集内容更容易继续推进。
- 优化人物、场景、道具的识别与资产管理，提升参考素材在后续分镜中的延续性。
- 改进分镜图片、连续画面与视频生成之间的衔接，减少重复整理素材和提示词的操作。
- 统一本地端模型服务配置的使用方式，让已填写的模型地址、模型名称和访问凭据能稳定衔接到主要创作流程。
- 优化批量任务、生成状态、历史结果与失败重试体验，让较长的创作流程更稳定、更容易追踪。
- 更新 Docker 本地体验包，保留原有操作习惯，并改善启动与连接体验。

## 下载文件

```text
releases/v3.0.0/yoluster-shorts-v3.0.0-docker-local-package-thin-bundle.zip
```

SHA256：

```text
645A9FE34AA01AB8977012EBF999500B0EE27819C7752E40560373FD53332C69
```

同时提供：

```text
releases/v3.0.0/yoluster-shorts-v3.0.0-docker-local-package-thin-release.json
releases/v3.0.0/yoluster-shorts-v3.0.0-docker-local-package-thin-release.sha256
```

## 使用方式

1. 下载并解压 `yoluster-shorts-v3.0.0-docker-local-package-thin-bundle.zip`。
2. 将 `.env.example` 复制为 `.env`。
3. 按包内说明完成服务地址配置，必要时调整 `LOCAL_WEB_PORT`。
4. 运行：

```powershell
docker compose up -d --build
```

启动后打开：

```text
http://127.0.0.1:<LOCAL_WEB_PORT>
```
