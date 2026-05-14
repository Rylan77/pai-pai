# 💩 排排 (Pai-Pai)

> 你忠实的拉屎搭子。记录每一次释放，追踪你的肠道节奏。

[中文] 一款轻松的便便记录追踪 App，HTML + Capacitor 打包 Android APK，纯本地存储，无需联网。

---

## ✨ 功能

- **📅 日历记录** — 月视图网格，每天一记，今日日期实色高亮
- **📊 统计图表** — 布里斯托分类、时段分布、心情分布环形图
- **🔬 分析建议** — 肠道健康评分、近7天趋势、周对比、个性化建议
- **🏆 成就系统** — 24 个趣味成就，已解锁自动排前
- **🎨 主题切换** — 暖色 / 绿 / 紫 / 暗黑 四套主题
- **⚙️ 个性化** — 昵称修改、emoji 头像、个人徽章墙
- **📤 数据导入导出** — JSON 格式，纯本地存储不外传
- **🎊 隐藏彩蛋** — 试试快速点击标题上的 💩

## 📸 截图

（请自行截取）

## 🚀 快速开始

```bash
# 克隆
git clone https://github.com/Rylan77/pai-pai.git
cd pai-pai

# 安装依赖
npm install

# 同步 Capacitor
npx cap sync

# 构建 APK（需要 Android SDK）
export ANDROID_HOME="/path/to/android-sdk"
cd android && ./gradlew assembleDebug
```

APK 生成在 `android/app/build/outputs/apk/debug/app-debug.apk`。

## 🛠️ 技术栈

- **前端**: 单文件 HTML + CSS + JS（无框架）
- **打包**: Capacitor 8
- **存储**: IndexedDB（浏览器原生，纯本地）
- **平台**: Android

## 📦 项目结构

```
pai-pai/
├── www/index.html           ← 唯一源文件
├── android/                 ← Capacitor Android 原生项目
├── capacitor.config.json
├── package.json
└── 排排-icon.png            ← App 图标源图
```

## ⚠️ 免责声明

本 App 仅供娱乐与自我记录使用，分析功能不构成医疗建议。如有健康疑虑，请咨询专业医生。

## 👤 制作

- **zane** · 3408732167@qq.com

## 🍌 愿你每天顺畅，遇见的都是第三型
