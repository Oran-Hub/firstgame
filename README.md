# newLive 游戏网站

这是为 oranewlive.com 创建的响应式游戏网站，展示了 "newLive: Goudall" 复古平台游戏。

## 功能

- 响应式设计，适合PC和移动设备
- 使用Tailwind CSS构建的现代UI
- 搜索引擎优化 (SEO) 元素
- 使用苹果设计系统色彩
- 内嵌游戏iframe，直接连接到itch.io平台

## 游戏简介

Goudall是一款复古风格的Gameboy Color平台游戏，玩家扮演巫师Goudall，必须在每个关卡中找到3颗钻石才能打开通往下一关的门。邪恶巫师Walator将Goudall的魔法力量封印在钻石中，并将它们隐藏在地下王国。玩家需要探索20个地下洞穴，收集所有钻石，恢复Goudall的力量。

## 文件结构

- `index.html` - 主网站文件，包含所有HTML、CSS和JavaScript
- `README.md` - 项目文档

## 如何使用

1. 将这些文件上传到你的网络服务器
2. 确保域名 oranewlive.com 指向该服务器
3. 网站将自动加载并显示游戏

## 技术细节

- 使用CDN引入Tailwind CSS (无需本地安装)
- 纯HTML、CSS和JavaScript实现，无需后端
- 内置移动端导航菜单
- 针对SEO优化的元数据
- iframe嵌入itch.io游戏

## 自定义

如需更改网站内容，直接编辑 `index.html` 文件中的文本内容。
如需调整样式，可以修改 `tailwind.config` 部分或添加自定义CSS规则。 