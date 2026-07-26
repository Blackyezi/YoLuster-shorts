# YoLuster Shorts v2.1.0

v2.1.0 继续完善从剧本、分镜、图片到视频输出的创作链路，重点放在更完整的视频模型入口、更稳定的本地体验包，以及更清晰的分镜到视频工作流。

## 本次更新

- 扩展视频生成模型入口，覆盖更多图生视频、文生视频和参考图视频工作流。
- 优化分镜脚本到图片、视频输出的衔接，让角色、场景、动作和镜头信息更容易在同一个项目中延续。
- 改进有台词分镜的视频生成体验，方便把对白、镜头运动和画面内容放在同一条创作链路里处理。
- 更新 Windows 本地版安装包，适合希望快速开始体验的用户。
- 更新 Docker 本地体验包，改善启动与服务连接体验。
- 继续整理品牌展示、登录入口、下载包和本地体验说明，让第一次试用更直接。

## 下载文件

```text
releases/v2.1.0/yoluster-shorts-v2.1.0-docker-local-package-thin-bundle.zip
```

SHA256:

```text
4541D5E2654F185CD903F2BE307A33F73D212D6FDDF77386B47FB19E9B161BA2
```

## 使用方式

1. 下载并解压 `yoluster-shorts-v2.1.0-docker-local-package-thin-bundle.zip`。
2. 将 `.env.example` 复制为 `.env`。
3. 按说明填写 `CLOUD_BACKEND_ORIGIN`，必要时调整 `LOCAL_WEB_PORT`。
4. 运行：

```powershell
docker compose up -d --build
```

启动后打开：

```text
http://127.0.0.1:<LOCAL_WEB_PORT>
```

> 这是 v2.1.0 的历史版本记录。旧安装包已经下架，建议下载最新版获得当前功能与修复。

