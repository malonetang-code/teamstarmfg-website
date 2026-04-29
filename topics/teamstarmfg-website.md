# Teamstar Manufacturing 网站维护话题

## 基本信息
- **网站地址：** https://www.teamstarmfg.com
- **公司：** 群新工业（隶属伟群制刀工业集团 Wei Qun Cutting Tools Group）
- **行业：** 工业刀具制造（木工、食品、塑胶、服装、纸品、工业等）
- **负责人：** 唐聪恺

## 技术架构
- **托管：** GitHub Pages（自动部署）
- **仓库：** https://github.com/malonetang-code/teamstarmfg-website.git
- **账号：** malonetang-code
- **分支：** main（唯一分支）
- **本地路径：** /Users/malone/projects/teamstarmfg/
- **技术栈：** 纯前端，单个 index.html（HTML/CSS/JS 全内联）
- **域名配置：** CNAME → www.teamstarmfg.com
- **表单服务：** Formspree ID: mbdqlnar → tang@teamstarmfg.com
- **双语：** 中/英，通过 data-lang 属性切换，默认中文

## 部署流程
1. 修改文件（index.html、images/ 等）
2. git add . && git commit -m "描述改动"
3. git push origin main（自动触发部署，1-2 分钟生效）
4. 访问 https://www.teamstarmfg.com 验证

## 联系方式
- 邮箱：info@teamstarmfg.com（对外）/ tang@teamstarmfg.com（表单接收）
- 电话：+86 181-5070-7007
- 地址：福建省漳州市长泰区古农农场顺兴路6号

## 设计规范
- 主色：#1a3a5c（深蓝）
- 强调色：#c8a45a（金色）
- 字体：英文 Inter / 中文 Noto Sans SC
- 风格：现代工业感，卡片式布局，响应式

## 网站板块
1. #home - 首页 Hero
2. #about - 关于我们
3. #products - 产品中心（木工/食品/塑胶/服装/工业）
4. #quality - 品控与服务
5. #locations - 全球布局
6. #contact - 联系我们
7. Footer - 页脚

## 注意事项
- ⚠️ 公司名是「伟群」不是「威群」！
- 所有文本必须写中英文两份（data-lang="zh" 和 data-lang="en"）
- 图片注意压缩，images/ 已有 29MB/393 张
- Formspree 免费版每月 50 次提交限制
- Copyright 年份需要时记得更新
- 完整维护手册参见：WEBSITE_CONTEXT.md

## 维护日志
- 2026-04-29: 初始化话题文件，确认本地项目和网站状态正常
