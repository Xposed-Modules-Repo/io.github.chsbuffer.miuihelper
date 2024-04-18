<div align="center">
   <h1>MIUI 生活质量提升</h1>
   <p>
       <b><a href="https://github.com/Xposed-Modules-Repo/io.github.chsbuffer.miuihelper/blob/main/README_EN.md">English</a>  丨 简体中文</b>
   </p>
   <a href="https://t.me/miuiqol"><img alt="Telegram 群组" src="https://img.shields.io/badge/Join-Telegram-blue.svg?logo=telegram"></a>
</div>

## 模块说明

此模块改善了我在 MIUI 12~14 以及 HyperOS 的日常使用体验，功能的详细描述可在模块设置内查看。

⭐ 本模块自豪地使用了 [DexKit](https://luckypray.org/DexKit/zh-cn/)，一个高性能运行时 DEX 解析库。

## 模块功能
- 手机管家
  - 应用行为记录显示系统应用（HyperOS 不再需要）
  - 系统应用 WLAN 联网控制
  - 将应用详情中“消除默认操作”改为“默认打开”设置
  - 无视“启用危险选项警告”倒计时直接确认
  - 体检分数锁定100分
- 系统桌面
  - 不隐藏 Google 桌面图标¹
  - 强制启用负一屏选择器（可选择 Google Feed）¹
  - 替换全局搜索为 Google 搜索¹
- 系统界面
  - 不隐藏附近分享磁贴²
  - 不隐藏谷歌钱包磁贴²
  - 去除通知设置白名单
  - 通知更多设置重定向至通知渠道设置（在 Android 14 上不可用）
- 截图
  - 截图保存到 `Pictures/Screenshots`
- 屏幕录制
  - 视频保存到 `Movies/ScreenRecorder`
  - 强制启用原生录音支持
- 小爱翻译
  - 启用 AI字幕（只能识别翻译中文、英文）
- 系统更新
  - 移除OTA验证（同 WooBox for MIUI 移除 OTA 验证）

注：

1. 需要 [Google 应用](https://play.google.com/store/apps/details?id=com.google.android.googlequicksearchbox) 
2. 在国行系统上，部分谷歌移动服务功能被停用。要启用这些功能，需要对系统文件进行修改。更多信息请参阅 Unlock CN GMS 面具模块：[https://github.com/fei-ke/unlock-cn-gms](https://github.com/fei-ke/unlock-cn-gms)
