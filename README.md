# 个人 HTML 小工具

这是一个纯静态 HTML 小工具集合，可以直接部署到 GitHub Pages。

## 工具

- `color-preview.html`：颜色预览工具
- `password-generator.html`：一次生成 10 个强类型密码
- `timestamp-converter.html`：Unix 时间戳与常用日期时间格式双向转换
- `rsa-key-generator.html`：生成或输入一组 RSA 公钥私钥，支持格式化复制、三种导出格式和加解密测试

## GitHub Pages 发布方式

1. 新建一个 GitHub 仓库。
2. 把本文件夹内的所有文件上传到仓库根目录。
3. 进入仓库 `Settings` -> `Pages`。
4. `Build and deployment` 选择 `Deploy from a branch`。
5. 分支选择 `main`，目录选择 `/root`，保存。

发布后访问 GitHub Pages 地址即可打开 `index.html` 首页。
