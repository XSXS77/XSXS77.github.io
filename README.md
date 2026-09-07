# PDF 报表比对站点

## 目录说明
- `index.html`：可直接部署的网页入口
- `netlify.toml`：Netlify 静态站点配置
- `vercel.json`：Vercel 静态站点配置

## 部署方式
### 方式 1：Netlify
1. 登录 Netlify
2. 选择 Deploy manually / Drag and Drop
3. 把整个 `public-site` 文件夹上传
4. 获得公网网址

### 方式 2：Vercel
1. 新建一个静态站点项目
2. 上传 `public-site` 目录
3. 部署后即可访问网址

### 方式 3：GitHub Pages
1. 把 `public-site` 里的内容放到仓库根目录
2. 打开 Pages
3. 选择分支后发布

## 使用方式
- 在网页中上传两个 PDF 和一个 Excel 模板
- 解析比对后查看结果
- 导出 Excel
