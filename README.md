# 🔥 坦克大战 (Tank Battle)

一个基于 HTML5 Canvas 的坦克大战游戏，纯前端实现，无需任何依赖。

## 🎮 在线试玩

直接在浏览器中打开 `index.html` 即可开始游戏。

## 🕹️ 操作说明

| 按键 | 功能 |
|------|------|
| `W` / `↑` | 向上移动 |
| `S` / `↓` | 向下移动 |
| `A` / `←` | 向左移动 |
| `D` / `→` | 向右移动 |
| `空格` | 射击 |
| `P` | 暂停/继续 |

## ✨ 游戏特性

- **玩家坦克**：流畅的移动和射击体验
- **敌人 AI**：自动寻路、随机移动、自动射击
- **地形系统**：
  - 🧱 砖墙（可被子弹摧毁）
  - ⬜ 钢墙（不可摧毁）
  - 💧 水域（不可通过）
  - 🌿 草丛（可隐藏）
- **粒子特效**：爆炸、子弹击中、屏幕震动
- **关卡系统**：每关敌人数量和难度递增
- **分数系统**：消灭敌人获得分数

## 🚀 本地运行

```bash
# 克隆仓库
git clone <仓库地址>

# 进入目录
cd tank-battle

# 用浏览器打开
start index.html
```

或者使用任意本地静态服务器：

```bash
# Python 3
python -m http.server 8080

# Node.js
npx serve .
```

然后在浏览器访问 `http://localhost:8080`

## 📁 项目结构

```
.
├── index.html    # 主游戏文件（包含 HTML + CSS + JavaScript）
└── README.md     # 项目说明
```

## 🛠️ 技术栈

- HTML5 Canvas
- Vanilla JavaScript (ES6+)
- CSS3

## 📄 开源协议

MIT License
