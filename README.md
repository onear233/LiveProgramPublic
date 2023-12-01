# LiveProgramPublic
一个直播软件（抹去了敏感信息）
（暂时是一个占位的空repo，完全开发完成并release v1.0.0B版本后会开源到这里）
## 版本命名
采用主版本号.次版本号.修订版本号+字母 命名  
其中字母：  
**A/Alpha**：表示该版本不稳定/严重不稳定，大量Bug仍需修复或功能尚未开发完全  
**B/Beta**：表示该版本已经相对稳定，但仍会有少许不影响使用的Bug  
**C**：表示该版本已经基本稳定，正常状态下没有bug 
第二位或字母（如果有）：
**F**：表示该版本为定制版，仅在小范围内传播，且不开源
## 更新日志（部分）
- V1.0.0A 2023.8.12  
  初版
- V1.0.2B 2023.9.3  
  首个Beta版本，G2信号源正常
- V1.1.0B 2023.10.1  
  完善登录界面相关逻辑
- V1.1.6B 2023.12.1  
  1.退出型号时更稳定
  2.采用Properties存储信息更加安全
  3.播放罗盘目前在播放视频时可以显示
  4.内部逻辑优化
  5.播放时支持截屏
  6.播放罗盘支持退出全屏/全屏
  7.对不正确的Window状态进行了修复
  8.接入Windows通知接口
  9.重写水波纹样式，防止过高的性能占用
  10.支持了播放时静音
  
 -下一版本预计实现
  [-] 自由声音调整
  [-] 颜色更改
  [-] 激进自动开课
  [-] 未播放时的图片展示
  [-] 缓冲时间 
  [-] 播放罗盘支持开启/关闭
  [-] 清除记住的密码
  [-] 播放书签功能
  [-] 暂停功能（提示暂停了多久）
## 引用/参考的开源项目
[MaterialDesignInXamlToolkit](https://github.com/MaterialDesignInXAML/MaterialDesignInXamlToolkit)  
[LibVLCsharp](https://code.videolan.org/videolan/LibVLCSharp)  
[Newtonsoft.JSON](https://github.com/JamesNK/Newtonsoft.Json) 
[FFMpeg](https://github.com/FFmpeg/FFmpeg)
