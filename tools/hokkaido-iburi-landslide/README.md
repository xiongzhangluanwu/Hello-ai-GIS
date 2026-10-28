# 北海道札幌厚真町滑坡空间分析工具 v4.53

## 更新说明
- 地质图完全本地化（産総研 WMS 下载为 base64 嵌入）
- 地层点击查询本地化（20 个代码中文映射表）
- 图例颜色同步 WMS 实际颜色
- 地图固定标注（6 个关键地层）
- 火山碎屑术语标准化（修正日式汉字"火砕"）

## 文件大小
- HTML 单文件：约 515 KB（含 base64 地质图）
- ZIP 离线包：约 375 KB

## 下载方式
由于文件过大（>500KB），超出 MCP 工具推送限制，请通过以下方式获取：

### 方式一：直接下载（推荐）
从 Kimi 输出目录下载最新文件：
- `北海道札幌厚真町滑坡空间分析工具_v4.53.html`
- `滑坡空间分析工具_离线包_v4.53.zip`

### 方式二：Git 推送
```bash
git clone https://github.com/xiongzhangluanwu/Hello-ai-GIS.git
cd Hello-ai-GIS/tools/hokkaido-iburi-landslide
# 将下载的 HTML 文件复制到此目录
cp /path/to/北海道札幌厚真町滑坡空间分析工具_v4.53.html ./index.html
git add index.html
git commit -m "v4.53: 地质图本地化 + 地层中文化"
git push origin main
```

---
上海市建平中学校本 AI+GIS 试验项目
