# 日历订阅工具

自动生成中国节假日、农历、节气、宜忌等日历订阅文件 (`.ics`)

## 功能

- 🇨🇳 **中国节假日** - 法定节假日 + 调休安排
- 🌙 **农历日历** - 农历日期 + 传统节日
- ☀️ **二十四节气** - 完整二十四节气
- 📋 **宜忌日历** - 每日宜忌（传统黄历）
- 🎉 **普通节日** - 公历节日 + 国际节日

## 订阅地址

访问 https://JwOKR.github.io/calendar-ics-generator 获取订阅链接

## 本地使用

```bash
# 安装依赖
npm install

# 生成日历文件
node src/index.js

# 指定年份范围
node src/index.js --years 2024-2027

# 启动本地服务
node src/index.js --serve
```

## 自动更新

- 每天北京时间凌晨2点自动生成最新日历文件
- 自动部署到 GitHub Pages
