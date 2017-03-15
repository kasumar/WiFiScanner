# WiFiScanner

支持系统：iOS 8.0 ~ 10.1<br>

主体代码源自：https://github.com/Cykey/wifi<br>

最近想研究下WiFi的扫描及连接，就找到了上面的项目，Theos虽然也能编译成功，但终究还是Xcode工程方便管理代码结构一些。
所以这个项目我所做的事情，就只是：<br>
&ensp;&ensp; 1、将原来的Theos工程改成了Xcode工程<br>
&ensp;&ensp; 2、修改了几句在我的开发环境下编译报错的代码<br>
很惭愧，就做了这么一点微小的工作 ╮(╯_╰)╭

---------------------------------------------------------------------------------------
安装方法1:<br>
&ensp;&ensp; 1、拷贝到iPhone设备的"/Applications"目录下<br>
&ensp;&ensp; 2、变更为root组，chown -R root:wheel /Applications/WiFiScanner.app<br>
&ensp;&ensp; 3、赋予可执行权限，chmod -R 755 /Applications/WiFiScanner.app<br>
&ensp;&ensp; 4、刷新桌面图标，su -c /usr/bin/uicache mobile<br>

安装方法2（本人未进行测试，只是觉得或许可行）:<br>
&ensp;&ensp; 选定开发者证书，通过Xcode直接编译到iPhone设备上<br>

---------------------------------------------------------------------------------------
![shot](https://github.com/kasumar/WiFiScanner/raw/master/screenshot/1.jpg)
![shot](https://github.com/kasumar/WiFiScanner/raw/master/screenshot/2.jpg)
![shot](https://github.com/kasumar/WiFiScanner/raw/master/screenshot/3.jpg)
![shot](https://github.com/kasumar/WiFiScanner/raw/master/screenshot/4.jpg)
