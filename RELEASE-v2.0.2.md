# YoLuster Shorts 釉光影 Docker 本地部署包 v2.0.2

v2.0.2 是一次面向公开 Docker 本地前端体验包的品牌同步与稳定性修复更新。

本次更新重点不是新增一条大的产品功能主线，而是修复下载包中的旧品牌残留、优化包名版本识别，并改善本地体验包的使用稳定性。

## 主要更新

### 1. 品牌统一

- 本地体验包统一使用 `YoLuster Shorts 釉光影`。
- 修复旧 Logo 路径和旧品牌资源残留。
- 修复本地导出文件名中的旧 `yoyoung-shorts-local-*` 前缀。
- 改善旧版本升级后的页面和服务连接兼容性。

### 2. 本地包文件名版本化

旧包名 `docker-local-package-thin-bundle.zip` 不利于用户区分版本。

v2.0.2 起，推荐下载文件改为：

```text
yoluster-shorts-v2.0.2-docker-local-package-thin-bundle.zip
```

用户下载后可以直接从文件名识别版本，减少多个 zip 文件混在一起时的误用风险。

### 3. 本地体验包稳定性

- 优化 Docker 本地体验包的启动流程。
- 补充版本清单与 SHA256 校验文件，方便用户确认下载完整性。
- 改善不同环境下的页面加载与服务连接体验。
- 修复旧品牌文字与旧 Logo 文件残留。

### 4. 兼容性说明

本次保持原有创作流程和使用方式，旧版本用户可以按说明更新体验包。

## 使用方式

1. 下载本版本中的 `yoluster-shorts-v2.0.2-docker-local-package-thin-bundle.zip`。
2. 解压到本地英文路径，例如：`D:\yoluster-shorts`。
3. 安装并启动 Docker Desktop。
4. 按压缩包内 README 配置 `.env` 并运行。
5. 在浏览器打开本地地址使用。

如果你已经部署过旧版本，建议先备份旧目录和个人配置，再解压新版本重新启动。

## 文件校验

下载文件：

```text
releases/v2.0.2/yoluster-shorts-v2.0.2-docker-local-package-thin-bundle.zip
```

SHA256：

```text
05BEE488BF37C2A35B027C13636442D06167A33B0CE3F80DB47CF7803F171150
```

