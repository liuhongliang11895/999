# 落地页静态复刻（技术研究）

## 使用
解压后直接打开 index.html。无需 Node.js、安装依赖或构建。

## 部署到 GitHub Pages
1. 在 GitHub 创建一个仓库（免费账户建议使用公开仓库）。
2. 把本目录内所有文件上传至仓库根目录。不要只上传 ZIP，也不要把 landing-page 文件夹作为额外一层。
3. 进入仓库 Settings → Pages。
4. 在 Build and deployment 中选择 Deploy from a branch。
5. Branch 选择 main，目录选择 / (root)，点击 Save。
6. 等待部署完成，打开 Pages 页面显示的网址。

仓库项目网址形式：https://你的用户名.github.io/仓库名/
原文件名入口：https://你的用户名.github.io/仓库名/connect_leadtwca.html

如果没有 Pages 选项，请确认仓库权限和账户方案是否支持对应的仓库可见性。

## 文件
- index.html：默认首页。
- connect_leadtwca.html：与原页面同名的完整副本。
- styles.css：原页布局、颜色、字体、间距及 860px 响应式断点。
- demo.html：保留的本地演示页，当前按钮已不使用此页。
- .nojekyll：静态文件部署标记。

## 复刻范围与差异
依据 2026-09-08 读取到的 https://risingstargo.shop/connect_leadtwca.html 公开 HTML/CSS。
保留首屏、手机插画、数据卡片、六项福利、三个条件、评价、免责声明、粘性导航和移动端悬浮按钮。
保留原始研究样本文案，并不代表认可其中的收益、认证及评价。
原站 Meta Pixel、追踪像素、Lead 上报、800ms 跳转脚本均未加入。
所有联系按钮固定跳转到 https://s.url99.me/7f10w5o5，不读取 888 仓库的动态配置；加入 noindex,nofollow 元信息。无外部字体、图片、脚本或依赖。
研究包不包含原站的重定向服务或 WhatsApp 业务服务。
未做逐像素截图比对；不同系统字体和 emoji 渲染可能略有差异。

修改首页文案时请同步修改两个 HTML 入口；二者共用 styles.css。