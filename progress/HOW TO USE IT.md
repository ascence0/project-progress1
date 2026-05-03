# 如何用 GitHub 写任务进展并附带图片和代码（零基础版）

## 1. 准备工作：注册 GitHub 账号
- 打开 [GitHub.com](https://github.com)，点击 **Sign up**，用邮箱注册（免费账号即可）。
- 建议下载安装 [GitHub Desktop](https://desktop.github.com/)（图形化工具，不用记命令）。也可只用网页版，但桌面版上传文件更方便。下面会说明两种方式。

## 2. 创建一个仓库（Repository）
仓库就是你的项目文件夹，用来存放代码、文档、图片等。

### 网页版操作：
1. 登录 GitHub，点击右上角 **+** → **New repository**。
2. 填写仓库名称，例如 `project-progress`。
3. 描述可选，选择 **Public**（公开）或 **Private**（私有）。
4. 勾选 **Add a README file**（会生成一个首页文件）。
5. 点击 **Create repository**。

现在你就有了一个空仓库。

## 3. 写第一篇任务进展（用 Markdown 格式）
进展报告写在 `.md` 文件里。Markdown 是一种轻量级标记语言，可以轻松排版。

### 方法 A：直接在 GitHub 网页上创建文件
1. 在仓库主页，点击 **Add file** → **Create new file**。
2. 在文件名输入框输入 `progress/2026-05-03.md`，这样会自动创建 `progress` 文件夹并按日期命名。
3. 在下方编辑区输入内容，例如：

```markdown
# 2026-05-03 任务进展

## 今日完成
- 完成了用户登录接口开发
- 修复了令牌过期问题

## 遇到问题
- 数据库连接池配置需要优化

## 明日计划
- 编写单元测试
