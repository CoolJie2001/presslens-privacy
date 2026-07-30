# PressLens Privacy Policy / PressLens 隐私政策

**Effective date / 生效日期: July 30, 2026 / 2026 年 7 月 30 日**

## 中文

PressLens（以下简称“本应用”）是一款用于在屏幕上实时显示键盘快捷键、按键、鼠标点击和滚轮操作的 Windows 桌面应用。本隐私政策说明本应用如何处理相关数据。

### 1. 输入数据的处理

为实现输入可视化功能，本应用会在运行期间访问键盘和鼠标输入事件。输入事件仅在用户设备上实时处理，用于生成屏幕悬浮提示或任务栏显示。

本应用不会读取或记录剪贴板内容、当前窗口标题、正在运行的进程名称或鼠标指针坐标，也不会将键盘或鼠标输入发送到开发者或任何第三方服务器。

### 2. 可选的输入诊断日志

输入诊断日志默认关闭。只有在用户主动启用该功能后，本应用才会将有限的输入诊断信息保存在用户设备本地，包括输入类型、按下或释放状态、时间、修饰键状态以及诊断所需的系统输入标记。

普通可打印字符会被替换为通用的脱敏标记。为诊断快捷键，可保留与 Ctrl、Alt 或 Windows 键组合使用的按键名称。诊断日志不会包含窗口标题、进程名称、剪贴板内容或鼠标指针坐标。

诊断日志保存在：

`%LOCALAPPDATA%\PressLens\Logs\Input`

默认保留期限为 3 天。用户可以在应用设置中将保留期限调整为 1 至 30 天，并可随时使用“清空日志”功能删除日志。

### 3. 应用设置与崩溃日志

本应用会在用户设备本地保存显示选项、输入过滤选项和诊断日志选项等设置。本应用也可能在发生程序错误时生成本地崩溃日志，以帮助诊断问题。上述文件不会由本应用自动上传。

本地文件通常保存在：

`%LOCALAPPDATA%\PressLens`

### 4. 网络传输、共享与出售

本应用不包含用户账户、广告、在线分析或遥测功能。本应用不会通过网络上传本政策所述数据，不会向第三方共享或出售个人数据，也不会将输入数据用于广告、用户画像或跨应用跟踪。

Microsoft Store 可能根据其自身隐私政策处理应用下载、购买、许可、崩溃报告或商店使用数据；该处理由 Microsoft 控制，不属于本应用的数据处理行为。

### 5. 数据控制与删除

用户可以关闭输入诊断日志、使用应用内的“清空日志”功能删除输入诊断日志，或者删除 `%LOCALAPPDATA%\PressLens` 目录来移除本应用保存的本地设置和日志。卸载本应用后，用户也可以检查并手动删除该目录中可能保留的文件。

### 6. 儿童隐私

本应用不面向儿童收集个人数据，也不会有意将任何数据上传给开发者或第三方。

### 7. 政策变更

如果本应用的数据处理方式发生重大变化，本隐私政策将同步更新，并修改页面顶部的生效日期。

### 8. 联系方式

如对本隐私政策有疑问，请通过 PressLens 的 Microsoft Store 商品页面中列出的支持联系方式联系开发者 JasonLuckin。

---

## English

PressLens (the "App") is a Windows desktop application that displays keyboard shortcuts, keystrokes, mouse clicks, and scrolling activity on screen in real time. This Privacy Policy explains how the App handles related data.

### 1. Processing of input data

To provide input visualization, the App accesses keyboard and mouse input events while it is running. These events are processed locally on the user's device solely to produce the on-screen overlay or taskbar display.

The App does not read or record clipboard contents, active window titles, running process names, or mouse pointer coordinates. Keyboard and mouse input is not transmitted to the developer or to any third-party server.

### 2. Optional input diagnostic logs

Input diagnostic logging is disabled by default. Only when the user explicitly enables it does the App store limited diagnostic information locally, including the input type, press or release state, timestamp, modifier-key state, and system input flags needed for diagnostics.

Ordinary printable characters are replaced with a generic redacted marker. For shortcut diagnostics, the name of a key used together with Ctrl, Alt, or the Windows key may be retained. Diagnostic logs do not contain window titles, process names, clipboard contents, or mouse pointer coordinates.

Diagnostic logs are stored at:

`%LOCALAPPDATA%\PressLens\Logs\Input`

The default retention period is 3 days. Users may configure a retention period from 1 to 30 days and may delete the logs at any time using the Clear Logs function in the App.

### 3. App settings and crash logs

The App stores preferences such as display options, input filters, and diagnostic logging settings locally on the user's device. The App may also create a local crash log when an application error occurs to assist with troubleshooting. These files are not automatically uploaded by the App.

Local files are generally stored under:

`%LOCALAPPDATA%\PressLens`

### 4. Network transmission, sharing, and sale

The App does not provide user accounts, advertising, online analytics, or telemetry. The App does not upload the data described in this policy, share or sell personal data, or use input data for advertising, profiling, or cross-app tracking.

Microsoft Store may process download, purchase, licensing, crash-reporting, or Store usage data under Microsoft's own privacy terms. Such processing is controlled by Microsoft and is separate from the App's data handling.

### 5. User control and deletion

Users may disable input diagnostic logging, delete input diagnostic logs using the Clear Logs function, or remove locally stored settings and logs by deleting the `%LOCALAPPDATA%\PressLens` directory. After uninstalling the App, users may also inspect and manually delete any files that remain in that directory.

### 6. Children's privacy

The App is not designed to collect personal data from children and does not knowingly upload any data to the developer or third parties.

### 7. Changes to this policy

If the App's data-handling practices change materially, this Privacy Policy will be updated and the effective date at the top of this page will be revised.

### 8. Contact

For questions about this Privacy Policy, contact the developer, JasonLuckin, using the support contact listed on the PressLens Microsoft Store product page.
