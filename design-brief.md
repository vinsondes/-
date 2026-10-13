# 文森（Vinson）个人网站 — 设计 Brief

## 任务
为插画设计兼文创产品设计师「文森 / Vinson」制作个人网站预览（首页单页）。
参考站：kommakomma.is（布局结构 + 动效），名称全部替换为 文森 / Vinson。

## 已确认方向
- 视觉基调：浅色纸感（米白/纸色背景 + 高对比深色文字，温暖克制，北欧极简排印气质）
- 站点范围：首页单页预览（Hero + 精选作品 + 服务 + 关于 + 联系）
- 作品素材：先用 AI 生成占位示例图，仅示意版式与氛围，后续替换为用户的真实作品
- 风格要求：简约、高级、大气、设计元素统一

## 网站板块结构（参考 kommakomma.is）
1. 顶部导航：VINSON 标识 + Work / About / Contact 锚点
2. Hero：大标题 + 一句式定位 + 主视觉大图
3. 定位句：一句式介绍（仿参考站 "…studio created for brands that refuse to blend in"）
4. About：个人简介（插画 × 文创）
5. Featured Projects：作品网格（6 个占位作品，hover 揭示 + 点击查看详情）
6. Services：编号式服务列表（01–05）
7. 合作/认可（占位）
8. Contact + Footer

## 占位作品清单（统一视觉语言）
统一约束：浅米白纸色背景、低饱和暖调、墨色线条、印刷颗粒质感、留白充分、无文字、无水印、当代简约插画/产品摄影。

1. hero-main（16:9）：超现实插画主视觉 — 漂浮纸山岛 + 巨大画笔 + 小小人眺望
2. work-shanhai（4:5）：山海集 · 云端鲸鱼驮山峦的超现实插画
3. work-yue（4:5）：小圆满 · 月亮形圆润 IP 角色抱星星
4. work-shiguang（4:5）：食光 · 茶点包装盒插画（山茶花枝+远山）
5. work-zaowu（1:1）：造物志 · 木质桌面文创产品组合场景
6. work-city（4:5）：城市漫游 · 俯瞰城市街区插画海报
7. work-zhuoqu（1:1）：拙趣 · 布面笔记本+木质铅笔+贴纸文具组合

## 技术方案
- 单文件自包含 HTML（内联 CSS/JS），GSAP + ScrollTrigger（jsDelivr CDN）复刻参考站动效
- 平滑滚动、滚动揭示（标题 mask reveal）、作品卡片 hover、行式列表 hover、克制的自定义 cursor
- 字体：自托管镜像（miaoda.feishu.cn 字体镜像），Noto Serif SC（标题衬线）+ Noto Sans SC（正文）+ 英文衬线点缀
- 配色：纸色 #F2EEE6 / 墨色 #201D18 / 副墨 #6B655A / 强调朱砂 #A63D2F（印章感，呼应中文名）
- 发丝线分隔、无圆角印刷感、grain 噪点 overlay、SVG favicon
- 图片本地相对路径 assets/（本地电脑交付）
