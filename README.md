# 自用软件


  - 华为手机开启无线调试
    1. 开启开发者模式
    2. 开发人员选项 开启usb调试 开启 连接usb时总是弹出提升 仅充电模式下允许ADB调试
    3. 连接wifi 手机插入typec 找个电脑或者另外一台手机 激活 信任 点击信任
    4. 终端输入 adb tcpip 5555
    5. 终端输入 adb connect 手机ip
 

  - Fongmi/TV
  
    > 感谢Fongmi/TV作者提供了如此好用方便的软件.

    > 很多功能使用频率比较低 比如python js 迅雷等等
    
    > 但这些功能导致软件包超过了30M
    
    > 对软件大小有莫名的强迫症
    
    > 减少软件包的体积,理想的大小是10左右
    
    > 记录下来免得后面忘记了
    
    1. 移除 python js 支持
    2. 移除 thunder   支持
    3. 移除 tvbus force 
    4. 使用了gogole/media 版本,没有使用Fongmi/media fongmi分支 
    5. 支持smb://播放地址
    6. ok版的搜索特性合并过来
    7. 对源后面添加集数显示 
    8. 后续准备移除投屏功能
    9. 后续准备移除弹幕功能
    10. 软件更新地址修改为本仓库
    11. 代码编译降到jdk11
    12. 后续准备使用okcronet 替换 cronet-okhttp
    13. 后续准备替换org.greenrobot:eventbus
