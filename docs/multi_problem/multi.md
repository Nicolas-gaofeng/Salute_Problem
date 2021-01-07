1. 找到电脑版微信的安装目录，方法如下：右键点击桌面上“电脑版微信”的图标，然后选择“属性”

2. 在弹出的窗口中点击“快捷方式”，找到下方的“打开文件所在位置”

![image-20210107123910183](https://gitee.com/zgf1366/pic_store/raw/master/img/20210107123910.png)

3. 复制资源管理器中的地址，如图，我的是D:\software\Tencent\WeChat

![image-20210107124738143](https://gitee.com/zgf1366/pic_store/raw/master/img/20210107124738.png)

4. 在空白处单击右键，新建→文本文档

![image-20210107124054925](https://gitee.com/zgf1366/pic_store/raw/master/img/20210107124055.png)

5. 双击打开新建好的“新建文本文档.txt”，输入以下内容，注意，微信的地址应该换成自己的安装地址。

```text
@echo off

start "" "D:\software\Tencent\WeChat\WeChat.exe"

start "" "D:\software\Tencent\WeChat\WeChat.exe"

exit
```



6. 右键选中文档，选择重命名，修改名称后缀文件类型为".bat",文件前缀可自定义。

![image-20210107124248114](https://gitee.com/zgf1366/pic_store/raw/master/img/20210107124248.png)

7. 在桌面双击打开“应用多开.bat”→稍等片刻就出现两个微信登录界面了。

8. 有时候想多开qq或者其他软件，不想一个一个点开，同样可以以这种方式，只需要更改地址就可，例如多开qq。

```text
@echo off

start "" "D:\software\Tencent\QQ\Bin\QQ.exe"

start "" "D:\software\Tencent\QQ\Bin\QQ.exe"

exit
```

