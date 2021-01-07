## 下载

1. 官网地址

   http://www.sublimetext.com/3

   打开链接，选择对应系统的版本下载即可。（本人电脑是win10 64位，下载Windows 64bit ）

   ![image-20210106231938447](https://gitee.com/zgf1366/pic_store/raw/master/img/20210106231938.png)

2. 百度网盘地址

   链接：https://pan.baidu.com/s/1gcetAataEgauPvA8XglhZw  提取码：z1or 

## 安装

1. 下载[Windows 64 bit](http://c758482.r82.cf2.rackcdn.com/Sublime Text Build 3065 x64 Setup.exe)后，双击即可安装。（注意勾选Add to explorer context menu，这样Sublime Text可以被添加到右键中，在右键单击文件时，可以直接使用Sublime Text打开）

2. 安装好后不要着急打开，在D:\program files\Sublime Text 3\下创建一个Data目录（和Packages目录同级），再打开Sublime Text 3后，将默认装在该Data目录下，否则会默认安装到C盘。

## 破解

打开sublime text,点击Help--Enter License ，输入以下破解码，完成注册。

以下破解码亲测有效 2021-01-07

```txt
----- BEGIN LICENSE -----
Member J2TeaM
Single User License
EA7E-1011316
D7DA350E 1B8B0760 972F8B60 F3E64036
B9B4E234 F356F38F 0AD1E3B7 0E9C5FAD
FA0A2ABE 25F65BD8 D51458E5 3923CE80
87428428 79079A01 AA69F319 A1AF29A4
A684C2DC 0B1583D4 19CBD290 217618CD
5653E0A0 BACE3948 BB2EE45E 422D2C87
DD9AF44B 99C49590 D2DBDEE1 75860FD2
8C8BB2AD B2ECE5A4 EFC08AF2 25A9B864
------ END LICENSE ------
```

## Package Control

1. 打开sublime Text3，使用快捷键Ctrl+Shift+P调出命令面板，输入install 调出 Install Package 选项并回车，提示以下错误信息：

```text
error: An error occurred installing Package Control
Please check the Console for details
Visit https://packagecontrol.io/installation 243 for manual instructions
```

2. 按照提示访问 https://packagecontrol.io/installation，根据页面中的提示，在D:\program files\Sublime Text 3\Data下创建了Installed Packages目录，并把在该页面下载的Package Control.sublime-package放到刚刚创建的Installed Packages目录中，重启sublime Text3。（备注：如果该链接访问不了，可以到百度网盘里下载文件。链接：https://pan.baidu.com/s/1m6tn1-Ql0taIX3t3cWWv5w 
   提取码：mtfb）

3. 再次打开sublime Text3，使用快捷键Ctrl+Shift+P调出命令面板，输入install 调出 Install Package 选项并回车，可能出现以下错误。不急，只要再配置一个文件即可（channel_v3.json，该文件也在百度网盘里）。

![img](https://gitee.com/zgf1366/pic_store/raw/master/img/20210106232633.png)

4. 下载channel_v3.json后放在电脑某个目录下（我是放在：D:\program files\Sublime Text 3\Data\channel_v3.json）。打开sublime Text3，依次选择Preferences>>Package Settings>>Package Control>>Setting- User，下面我们修改channels的参数，指定channel_v3.json文件的路径，如下图所示：

![img](https://gitee.com/zgf1366/pic_store/raw/master/img/20210106232810.png)

保存后重启Sublime Text 3，使用快捷键Ctrl+Shift+P调出命令面板，输入install 调出 Install Package 选项并回车，发现已经可以正常使用了。

## 汉化

1. 首先，打开SublimeText 3 软件。如图：

![image-20210106232933184](https://gitee.com/zgf1366/pic_store/raw/master/img/20210106232933.png)

2. 接着，在SublimeText 3菜单栏中，找到“Preference”，在弹出的下拉菜单中找到的“Package Control”。如图：

![image-20210106233010700](https://gitee.com/zgf1366/pic_store/raw/master/img/20210106233010.png)

3. 接着，打开“package control” ，在弹出的下框输入“install”，搜索会自动联想到“install package”点击进入。如图：

![image-20210106233027759](https://gitee.com/zgf1366/pic_store/raw/master/img/20210106233027.png)

4. 等待系统自动搜索完成，弹出安装对话框。如图：

![image-20210106233051696](https://gitee.com/zgf1366/pic_store/raw/master/img/20210106233051.png)

5. 接着，在弹出的界面中，在搜索框中输入“chinese”，在弹出的下拉菜单中找到“ChineseLocalizations”，点击安装。如图：

![image-20210106233113469](https://gitee.com/zgf1366/pic_store/raw/master/img/20210106233113.png)

6. 等待系统自动安装完成。接着，系统安装完成后会出现如下界面，然后菜单等英文就会自动切换成中文界面。如图

![image-20210106233142367](https://gitee.com/zgf1366/pic_store/raw/master/img/20210106233142.png)

7. 如果，想要切换会原本的英文状态，在菜单栏中找到“帮助”，在弹出的下拉菜单中，选择“Language”，在弹出的下拉菜单中，选择“English”，即可。如图：

![image-20210106233203472](https://gitee.com/zgf1366/pic_store/raw/master/img/20210106233203.png)

8. 至此，SublimeText 3 汉化完成。

## 替换

在ctrl+h界面alt+r开启正则，之后用\n表示换行符