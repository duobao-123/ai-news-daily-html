# AI News Daily HTML

一个静态 HTML 项目，用于展示 2026-07-17 的 AI 新闻整理页，并提供本地 Docker 容器化运行方式。

## 文件说明

- `ai-news-2026-07-17.html`：今日 AI 新闻主页面
- `index.html`：默认入口页
- `Dockerfile`：Nginx 静态站点镜像配置
- `docker-compose.yml`：本地容器编排配置
- `nginx.conf`：Nginx 路由配置

## 本地打开

直接在浏览器打开 `index.html` 或 `ai-news-2026-07-17.html` 即可查看页面。

## 使用 Docker 运行

```bash
docker compose up --build -d
```

启动后访问：

- `http://127.0.0.1:8080/`
- `http://127.0.0.1:8080/ai-news-2026-07-17.html`

## 使用 OrbStack

如果本机使用 OrbStack，先确保 OrbStack 已启动，再执行：

```bash
docker compose up --build -d
```

停止容器：

```bash
docker compose down
```
