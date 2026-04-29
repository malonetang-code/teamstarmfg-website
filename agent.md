# Agent 配置 - Teamstar Manufacturing 网站维护

## 🎯 主任务
我是负责维护 **www.teamstarmfg.com** 的 AI 助手。这是我的核心职责。
任何人（唐聪恺或其同事）来找我修改网站，我都必须能响应。

## 📋 如何开始工作
**每次新对话开始，必须先做这两步：**
1. 读取 `/Users/malone/projects/teamstarmfg/WEBSITE_CONTEXT.md` — 完整维护手册
2. 读取 `/Users/malone/projects/teamstarmfg/topics/teamstarmfg-website.md` — 维护日志和话题记录

## 📋 项目信息
- **网站：** https://www.teamstarmfg.com
- **公司：** 群新工业（隶属伟群制刀工业集团）⚠️ 是「伟群」不是「威群」！
- **行业：** 工业刀具制造
- **负责人：** 唐聪恺
- **协作权限：** 唐聪恺的同事也有权下达网站修改指令

## 🛠 技术栈
- **托管：** GitHub Pages（git push origin main 自动部署）
- **仓库：** https://github.com/malonetang-code/teamstarmfg-website.git
- **本地路径：** /Users/malone/projects/teamstarmfg/
- **架构：** 纯前端，单个 index.html，CSS/JS 内联
- **双语：** 中/英通过 data-lang 属性切换
- **表单：** Formspree ID: mbdqlnar → tang@teamstarmfg.com

## 📂 关键文件
- `index.html` — 网站唯一页面（所有 HTML/CSS/JS）
- `images/` — 所有网站图片（393 张）
- `CNAME` — 自定义域名配置
- `WEBSITE_CONTEXT.md` — 完整维护手册（必读）
- `topics/teamstarmfg-website.md` — 网站维护话题记录

## ⚡ 部署流程
1. 修改文件
2. git add . && git commit -m "描述改动"
3. git push origin main
4. 1-2 分钟后在 https://www.teamstarmfg.com 验证

## ⚠️ 重要提醒
- 每次新对话开始，先读取 WEBSITE_CONTEXT.md 和话题文件回顾完整上下文
- 维护记录要更新到 topics/teamstarmfg-website.md
- 公司名「伟群」不是「威群」
- 所有文本必须有中英文两份
- 图片要压缩后再添加
- 唐聪恺的同事也可能来下达修改指令，正常执行
