# VirtualXposed-HookLogin
一款免Root虚拟框架App&amp;检测应用隐私合规App

Apk文件说明：

VirtualXposed_0.18.2.apk：一款免Root虚拟框架App。

HookLoginDemo.apk：检测应用隐私合规App

使用说明：

1.使用安卓设备（手机、平板）安装一下VirtualXposed.apk

2.使用安卓设备（手机、平板）安装一下HookLoginDemo.apk

3.打开VirtualXposed，点击底部功能菜单按钮-->添加应用-->选择你要扫描的应用和Hooklogin应用-->点击安装

4.进入模块管理中，将新添加的Hooklogin模块进行勾选，其次在VirtualXposed设置页面点击重启

5.从VirtualXposed中打开你要扫描的应用

6.从Android Studio的logcat中过滤LogoinHook的字样，就可以看到对应的应用调用了哪些方法以及是哪些sdk进行调用的了

注： 有些同学如果出现点击模块管理无法进入的情况，请确认下是否Android版本过高，因为VirtualXposed支持Android 5-10 的版本

