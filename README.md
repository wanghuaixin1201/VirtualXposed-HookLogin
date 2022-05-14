# VirtualXposed-HookLogin
一款免Root虚拟框架App&amp;检测应用隐私合规App

Apk文件说明：

VirtualXposed_0.18.2.apk：一款免Root虚拟框架App。

HookLoginDemo.apk：检测应用隐私合规App

使用说明：

1.使用安卓设备（手机、平板）安装一下VirtualXposed.apk

2.使用安卓设备（手机、平板）安装一下HookLoginDemo.apk

3.打开VirtualXposed，点击底部功能菜单按钮-->添加应用-->选择你要检测的应用和Hooklogin应用-->点击安装

![VirtualXposed功能菜单按钮](https://user-images.githubusercontent.com/24582883/168406844-9f18ffdf-1faa-4842-9c52-f5331bab9b69.jpg)
![选择需要检测应用和Hooklogin](https://user-images.githubusercontent.com/24582883/168407253-1d367706-2d43-4354-9140-a5eb9b4f9075.jpg)



4.进入模块管理中，将新添加的Hooklogin模块进行勾选，其次在VirtualXposed设置页面点击重启

![Hooklogin模块进行勾选](https://user-images.githubusercontent.com/24582883/168406974-ece2a307-f232-4a5d-90d9-0171a9556ab5.jpg)
![设置页面点击重启](https://user-images.githubusercontent.com/24582883/168407010-bc632fcd-334e-4932-a8f1-d62a440d68c2.jpg)



5.从VirtualXposed中打开你要检测的应用

![打开你要检测的应用](https://user-images.githubusercontent.com/24582883/168407295-bbe3649e-f26e-4e20-b1a1-316e3b6c8f11.jpg)



6.从Android Studio的logcat中过滤HookLogin的字样，就可以看到对应的应用调用了哪些方法以及是哪些sdk进行调用的了

![Android Studio日志](https://user-images.githubusercontent.com/24582883/168407700-cd576bb7-b8dd-4188-9b97-e8d0ec4120e4.png)



注： 有些同学如果出现点击模块管理无法进入的情况，请确认下是否Android版本过高，因为VirtualXposed支持Android 5-10 的版本

