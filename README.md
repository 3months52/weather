# 实时天气 Web App

一个简洁美观的实时天气查询网页，基于 心知天气 API 开发，支持城市搜索。（自动定位）

## 功能特性

-  搜索全球任意城市的当前天气
-  显示温度、天气状况、湿度、风速
-  5 天天气预报（每日图标、温度、日期、星期）
-  简洁的卡片式 UI
- （定位功能暂未实现）

## 技术栈

- HTML5 + CSS3
- JavaScript (ES6)
- 心知天气 API
- （浏览器地理定位 API）

### 前置条件

- 现代浏览器（Chrome, Firefox, Edge 等）
- 注册 [心知天气](https://www.seniverse.com/) 获取免费 API 密钥

### 安装步骤

1. **克隆仓库**  
   ```bash
   git clone https://github.com/3months52/weather.git

# 使用说明
## 搜索城市

·在顶部搜索框输入城市名称（例如 “Beijing”、“London”、“北京”）

·按回车键或点击搜索图标

·页面会立即更新当前天气和 5 天预报

·获取当前位置天气

(·点击 “Location” 卡片浏览器会弹出位置授权请求，点击“允许”页面将显示你所在位置的天气)

# 自定义使用
·更换天气图标
·如果你想使用本地图标，可以修改 updateCurrentWeather 和 updateForecast 函数中的图标 URL

·修改背景图
·根据天气状况（如 Clear、Rain）切换背景图片：在 displayWeather 函数中添加 switch 语句，为 document.body 设置不同的 backgroundImage。

·增加更多天气指标
·你可以从 API 返回的数据中提取更多字段（如气压、能见度、日出日落时间），并在页面中添加对应的元素。

# 联系方式
作者：3months52

邮箱：huchengsi666@outlook.com

项目链接：https://github.com/3months52/weather
