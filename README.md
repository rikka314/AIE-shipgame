# AIE-shipgame
# 🌊 航海贸易游戏

一个基于航线规划与动态经济的策略贸易游戏。玩家通过绘制最优贸易航线，在不同港口间进行买卖，并通过侦查与海盗行为与其他商队互动，最终积累财富与声望。

**[>> 点击查看详细游戏设计文档 <<](https://github.com/rikka314/AIE-shipgame/PLANNING.md)**

## 🎮 游戏特色

- **策略性航线规划**：绘制连接港口的贸易航线，核心规则是**航线不能交叉**。
- **动态经济系统**：港口商品价格随供需关系实时波动，把握低买高卖的时机。
- **多角色玩法**：扮演商人、侦查员或海盗，通过贸易、信息差或战斗获取利益。
- **生动的世界**：NPC商船自主贸易，随机事件（繁荣/萧条）影响全局市场。

## 🚀 快速开始

### 环境要求

- **游戏引擎**: [Unity 2022.3 LTS] 或 [Godot 4.0] （根据你的选择二选一）
- **编程语言**: C#
- **开发工具**: VS Code

## 🏗️ 项目结构（主要文件夹说明）

AIE-shipgame/
├── Assets/
│ ├── Scripts/ # 所有C#脚本
│ ├── Scenes/ # 游戏场景文件
│ ├── Prefabs/ # 可重用的游戏对象（如船只、港口）
│ ├── Art/ # 图片、音效等美术资源
│ └── Data/ # 配置数据（如ports.json）
├── Docs/ # 设计文档、策划案
└── README.md # 你现在正在看的这个文件


## 👨‍💻 开发指南

### 如何开始开发一个新功能？（小白必看）

1.  **创建一个新的分支**
    ```bash
    git checkout -b feature/你的功能名   # 例如：feature/add-trade-ui
    ```

2.  **开始写代码，做你的功能**。

3.  **完成功能后，提交代码**
    ```bash
    git add .
    git commit -m "feat: 添加了交易界面UI"
    git push origin feature/你的功能名
    ```

4.  在GitHub上发起一个 **Pull Request (PR)**，请求将你的代码合并到主分支。

### 主要技术栈

- **前端/游戏客户端**: Unity/Godot (C#)
- **UI系统**: Unity UGUI / Godot Control Nodes
- **数据存储**: JSON (本地存档) - 后期可扩展为服务器数据库

## 🤝 如何参与开发？

我们非常欢迎贡献!了解我们的行为准则以及提交代码的流程。

1.  Fork 本仓库
2.  创建你的功能分支 (`git checkout -b feature/AmazingFeature`)
3.  提交你的改动 (`git commit -m 'Add some AmazingFeature'`)
4.  推送到分支 (`git push origin feature/AmazingFeature`)
5.  开启一个 Pull Request

## 📝 任务清单与进度

我们的开发任务使用 GitHub Issues 进行管理。
**[>> 查看待处理的任务列表 <<](https://github.com/rikka314/AIE-shipgame/TASKLIST.md)**

**核心功能进度:**
- [x] 项目初始化与仓库搭建
- [ ] 地图与港口基础渲染
- [ ] 航线绘制与交叉检测
- [ ] 船只移动系统
- [ ] 基础交易经济系统

## ❓ 常见问题 (FAQ)

**Q: 我是编程新手，如何运行这个项目？**
**A:** 确保安装了正确的Unity/Godot版本，然后按照上面的 **“如何运行游戏？”** 步骤操作即可。

**Q: 我想修改港口数据，应该改哪个文件？**
**A:** 在 `Assets/Data/ports.json` 文件中修改。

## 📄 许可证

本项目采用 [MIT](LICENSE) 许可证。

## 📞 联系我们

- 项目讨论：[GitHub Discussions](https://github.com/rikka314/AIE-shipgame/discussions)
- Bug反馈：[Issues](https://github.com/rikka314/AIE-shipgame/issues)
