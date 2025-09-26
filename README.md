# 社交链接资料卡片 (Social Links Profile)

![Design preview for the Social links profile coding challenge](./preview.jpg)

### 项目概览与展示
欢迎查看我完成的个人项目——社交链接资料卡片。这是一个设计简约、功能完备的数字名片，旨在将我在各大平台的所有社交和专业链接聚合到一个统一的界面中。该项目采用了暗色主题设计，使用鲜明的黄绿色作为强调色，突显地点信息和交互元素。最终成品在视觉上具有很强的聚焦感，用户可以一眼找到所有关键信息。

您可以点击以下链接查看最终效果：
- 代码仓库 (GitHub Repo): https://github.com/yylPro/social-links-profile.git

### 技术实现与亮点
本项目完全基于原生 HTML5 和 CSS3 构建，重点解决了前端布局中的两大挑战：精确居中和响应式设计。

#### 核心布局技术
- 完美居中方案： 我利用 Flexbox 布局，在 body 容器上设置垂直 (column) 和水平居中。关键在于在卡片 (.profile-card) 上使用了 margin: auto;，这让卡片在垂直和水平方向上都能够自动分配剩余空间，实现绝对居中。
- 元素分离： 页面底部的版权信息通过 margin-top: auto; 被优雅地推到视口底部，与主体卡片内容保持清晰的物理分离。

#### 代码实践与优化
- 语义化结构： 我使用了 <main>、<header>、<nav> 和 <ul> 等语义化标签来组织内容，确保代码结构清晰，利于可访问性 (A11Y)。
- 间距管理： 链接按钮列表 (.social-links-list) 使用了现代 Flexbox 属性 gap (16px)，避免了传统 margin 方案带来的边距清除问题。
- 交互设计： 为所有按钮设计了平滑的 悬停（:hover） 和 焦点（:focus） 过渡效果，提升了用户操作的反馈感。


