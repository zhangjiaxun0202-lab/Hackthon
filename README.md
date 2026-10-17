# Hackthon · Beauty Archive


这个仓库保存 Beauty Archive 美妆图鉴交互原型及其迭代资料。


当前整理后的内容分为三部分：


- beauty-archive-source/：早期单文件交互原型，作为基线版本保留。
- releases/：已验证的暖棕色 Liquid Glass 版本发布包。
- docs/：项目结构、资料来源、视觉规范、验证记录和使用边界。


## 当前版本


**Beauty Archive · Warm Liquid Glass · 2026-10-17**


这一版延续原有 29 个界面和本地演示流程，加入：


- 暖棕色 Liquid Glass 视觉系统
- 半透明玻璃卡片、浮动导航和深咖主操作
- 页面切换、弹层上浮、导航激活和按压反馈动效
- prefers-reduced-motion 动效降级
- 原有产品图鉴、妆容记录、画像、导师匹配、积分和重置流程


发布包：


[GitHub Release 下载包](https://github.com/zhangjiaxun0202-lab/Hackthon/releases/download/v2026.10.17-liquid-glass/Beauty-Archive-Warm-Liquid-Glass-2026-10-17.zip)


SHA-256：


808c51826d1a734619b0ec9db9193caaaa19113ac9b1953299ae9410f4e3b8b4


## 本地预览


解压发布包后，在解压目录启动任意静态服务器：


    python3 -m http.server 8766
