# Teamstar Manufacturing 网站维护话题

## 基本信息
- **网站地址：** https://www.teamstarmfg.com
- **公司：** 群新工业（隶属伟群制刀工业集团 Wei Qun Cutting Tools Group）
- **行业：** 工业刀具制造（木工、食品、塑胶、服装、纸品、工业等）
- **负责人：** 唐聪恺
- **主任务：** 维护 www.teamstarmfg.com 网站

## 技术架构
- **托管：** GitHub Pages（自动部署）
- **仓库：** https://github.com/malonetang-code/teamstarmfg-website.git
- **账号：** malonetang-code
- **分支：** main（唯一分支）
- **本地路径：** /Users/malone/projects/teamstarmfg/
- **技术栈：** 纯前端，单个 index.html（HTML/CSS/JS 全内联，1915行）
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
- 风格：现代工业感，卡片式布局，圆角16px，响应式
- 动画：fade-up 渐入（IntersectionObserver）

## 网站板块（index.html）
| # | Section ID | 中文标题 | 说明 |
|---|-----------|---------|------|
| 1 | #home | 首页 Hero | 大图背景 + 公司标语 + CTA 按钮 |
| 2 | #about | 关于我们 | 公司简介、里程碑数据 |
| 3 | #products | 产品中心 | 5个品类Tab：木工/食品/塑胶/服装/工业 |
| 4 | #quality | 品控与服务 | ISO认证、热处理、涂层、检测 |
| 5 | #locations | 全球布局 | 6大生产基地卡片 |
| 6 | #contact | 联系我们 | 联系信息 + Formspree表单 |
| 7 | Footer | 页脚 | 链接、版权信息 |

## 产品分类
| data-category | 中文 | 图片 |
|---------------|------|------|
| woodworking | 木工业用刀 | product_01.png |
| food | 食品业用刀 | product_04.png |
| plastic | 塑胶业用刀 | product_05.png |
| apparel | 服装业用刀 | product_02.png |
| industrial | 工业用刀（纸品/手动工具/文具/其他） | product_06/07/03.png, page24_Image543.png |

## 已验证的能力（2026-04-29）
- ✅ 读取所有项目文件
- ✅ 修改文字内容（中英文）
- ✅ 修改图片引用路径
- ✅ 添加/删除 HTML 功能块
- ✅ 修改 CSS 样式（内联在 index.html）
- ✅ 修改 JS 脚本（内联在 index.html）
- ✅ Git commit + push 自动部署
- ✅ 创建新文件

## 注意事项
- ⚠️ 公司名是「伟群」不是「威群」！
- 所有文本必须写中英文两份（data-lang="zh" 和 data-lang="en"）
- 图片注意压缩，images/ 已有 29MB/393 张
- Formspree 免费版每月 50 次提交限制
- 完整维护手册参见：WEBSITE_CONTEXT.md
- 新同事也可能来下达修改指令，需正常响应

## 关键文件
- `index.html` — 网站唯一页面（所有 HTML/CSS/JS）
- `images/` — 所有网站图片（393 张）
- `CNAME` — 自定义域名配置
- `WEBSITE_CONTEXT.md` — 完整维护手册（必读！每次新对话先读这个）
- `agent.md` — Agent 职责配置
- `topics/teamstarmfg-website.md` — 本话题文件（维护日志）
- `company_presentation.pptx` — 公司原始PPT（参考资料）

## 维护日志
- 2026-04-29 14:28: 读取 WEBSITE_CONTEXT.md，完整了解网站信息
- 2026-04-29 14:43: 获得文件写入权限
- 2026-04-29 14:44: 创建 agent.md 和本话题文件
- 2026-04-29 14:48: 全面验证能力（读/写/改/Git/部署）全部通过
- 2026-04-29 14:49: 更新 copyright 2025→2026，首次成功 git push 部署
- 2026-04-29 14:54: 更新话题文件，记录完整维护信息
