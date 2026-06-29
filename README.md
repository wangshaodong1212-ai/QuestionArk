# QuestionArk

QuestionArk 是一个用于复习面试题的轻量静态网站，内容按公司分组整理，支持搜索、公司筛选、题目折叠和移动端浏览。

在线访问：

```text
https://wangshaodong1212-ai.github.io/QuestionArk/index.html
```

## 内容

- 12 个公司分组
- 196 道面试题答案
- 覆盖 AI Agent、RAG、前端、后端、数据库、K8S、支付、秒杀、团队协作等方向

## 文件结构

```text
.
├── index.html   # GitHub Pages 站点入口
├── README.md    # 项目说明
└── .nojekyll    # 禁用 Jekyll 处理，保证静态文件原样发布
```

## 本地预览

直接双击 `index.html` 即可在浏览器中打开。

## 后续更新

本项目的页面由本地 Markdown 答案稿生成。推荐流程：

1. 修改本地答案源文件：

```text
outputs/interview_answers_by_company.md
```

2. 重新生成 HTML：

```bash
node work/generate_interview_site.js
```

3. 同步到 GitHub Pages 目录：

```bash
cp outputs/interview_answers_site.html outputs/github-pages-interview-site/index.html
```

4. 发布到 GitHub：

```bash
node work/publish_questionark_github_pages.js
```

页面地址保持不变。

## 注意

涉及用户量、Token、成本、并发、向量库数据量等内容，需要替换成真实数据后再用于面试表达。
