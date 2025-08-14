# MoonTV V1.0 产品说明

#更新日志

20250813：用户需自行注册用户名与密码，操作流程为：先点击“注册”按钮完成账户注册，再点击“登录”按钮进行账号登录。

#修改说明
Android Studio key密钥位于app目录下

URL设置：app\src\main\java\com\moontv\mm\MainActivity.java 第44行修改。

## 产品简介
MoonTV是一款基于Chrome内核的套壳浏览器应用，专为简化网页访问体验而设计。应用启动后会自动跳转到指定网址，提供沉浸式浏览体验，支持横竖屏自动切换。

## 产品生成
Trae"https://www.trae.cn/"

AI调用"Doubao-seed-1.6,Qwen-3-Coder"

Android Studio"https://developer.android.google.cn/studio?hl=zh-cn"

Gradle"https://gradle.org/"

Java-17"https://www.java.com/zh-CN/"

MoonTV"https://github.com/LunaTechLab/MoonTV"

Cloudflare"https://dash.cloudflare.com/"

## 主要功能
1. **Chrome内核浏览**：采用高性能Chrome内核，确保网页加载快速流畅
2. **自动跳转**：启动应用后自动跳转到指定URL：`https://moontv.jsdh.us.kg/`
3. **沉浸模式**：隐藏系统通知栏和底部导航栏，提供全屏浏览体验
4. **横竖屏支持**：调用系统陀螺仪，自动适应屏幕方向变化
5. **简化界面**：无多余控件，专注于网页内容展示

## 系统要求
- **最低版本**：Android 5.1 (API级别22)
- **最高版本**：Android 15 (API级别35)
- **网络要求**：需要连接互联网

## 权限说明
- `INTERNET`：允许应用访问网络
- `ACCESS_NETWORK_STATE`：允许应用检查网络连接状态

## 使用方法
1. 安装并打开MoonTV应用
2. 应用会自动加载指定网页
3. 可旋转设备切换横竖屏模式
4. 点击返回键可返回上一页

## 技术信息
- **应用包名**：com.moontv.mm
- **构建工具**：Android Studio
- **Gradle版本**：7.4.2

## 版本历史
- **V1.0**：初始版本，包含所有基础功能

## License

本项目采用 MIT 许可证。

## 免责声明

MoonTV-APK 仅作为视频搜索工具，不存储、上传或分发任何视频内容。所有视频均来自第三方 API 接口提供的搜索结果。如有侵权内容，请联系相应的内容提供方。

本项目开发者不对使用本项目产生的任何后果负责。使用本项目时，您必须遵守当地的法律法规。

## 🙏 致谢
