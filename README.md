# 面试题答案小站

这是一个轻量 GitHub Pages 静态站点，只有一个 `index.html`，不需要安装依赖，也不需要构建。

## 本地预览

直接双击 `index.html` 即可浏览。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库，例如 `interview-qa-site`。
2. 把本目录里的文件上传到仓库根目录：
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. 打开仓库 `Settings` -> `Pages`。
4. `Build and deployment` 选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. 保存后等待 1 分钟左右，GitHub 会生成访问链接。

链接格式通常是：

```text
https://你的用户名.github.io/interview-qa-site/
```

## 更新内容

以后如果答案有修改，重新生成或替换 `index.html`，提交到仓库即可自动更新。

## 说明

页面内容来自 `interview_answers_by_company.md`。涉及用户量、Token、成本、并发等数字，请替换成真实数据后再使用。
