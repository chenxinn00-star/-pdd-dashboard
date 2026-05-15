# 拼多多数据看板 GitHub Pages 发布包

这个文件夹用于发布公开可访问的静态看板。

包含文件：

- `index.html`：看板网页，由原来的 `dashboard.html` 复制而来
- `pdd_data.json`：看板读取的数据文件

不要上传以下文件：

- `cookies.json`
- `fetch_pdd.py`
- `update_cookie.py`
- `log.txt`
- `data/api-debug.json`

发布方式：

1. 在 GitHub 新建一个公开仓库。
2. 上传本文件夹里的 `index.html` 和 `pdd_data.json`。
3. 进入仓库 `Settings` -> `Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`。
6. 保存后等待几分钟，GitHub 会生成公开网址。

以后数据更新后，只需要重新上传新的 `pdd_data.json`。
