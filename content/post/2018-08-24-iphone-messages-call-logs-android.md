---
title: 如何将iphone中的短信（messages）和通话记录（call logs）导入到android手机
author: 张振国
date: '2018-08-24'
slug: iphone-messages-call-logs-android
categories:
  - life
tags:
  - 手机
  - messages
  - 通话记录
  - 转移
---

因为最近买了华为的手机，需要将旧的iphone上面的短信和通话记录导入到
新的手机上。新手机是Android系统。

如果旧手机是android系统，如果用的又是AT & T的服务，那么这个可以用
[AT & T Mobile Transfer](https://www.att.com/features/mobile-transfer.html) 这个APP。但是如果旧手机是iphone，这个办法就不可行了。

今天我就来介绍一下如何用[iSMS2Droid](https://play.google.com/store/apps/details?id=org.faked.isms2droid)这个APP来转移短信和通话记录。具体步骤如下：

1. 用iTunes备份iphone到你的电脑上（Mac或者Windows系统都行）。关于如何备份可以参考这个链接https://support.apple.com/en-us/ht203977或者google search。

2. 备份结束后，打开备份文件夹，位置应该在： 
    a. Mac: ~/Library/Application Support/MobileSync/Backup/
    b. Windows: C:\Users\USERNAME\AppData\Roaming\Apple Computer\MobileSync\Backup\ (USERNAME是你的电脑用户名)。

3. 在这个备份文件夹里面，有很多子文件夹。我们需要找到以下两个文件：
    a. 3d0d7e5fb2ce288813306e4d4636395e047a3d28 (含有你的短信)
    b. 5a4935c78a5255723f707230a451d79c540d2741 (含有你的通话记录)
最简单的找到这两个文件的办法就是拷贝上面的文件名，然后在文件夹的
搜索框里面搜索。

4. 拷贝这两个文件到新的Android手机上面，记住在新手机上的存储位置，
后面会用到。也可以通过电子邮件或者google drive等方式通过网络传递
到Android手机上面。

5. 在新手机上安装[iSMS2Droid](https://play.google.com/store/apps/details?id=org.faked.isms2droid)，然后打开该App。

6. 点击“Import Messages”或者“Import Call Log”，然后根据提示找到对应已经拷贝的
文件（上面第3步）来导入相关信息。在这个过程中，可能会提示将iSMS2Droid设置
成默认程序，选择是，信息转移完后可以改回去。

7. 然后你就在新手机上看到你的信息和通话记录了。倍感亲切吧 :smile:.

以上步骤使用的是中文操作系统和手机软件，中文的应该是相同步骤，请参考操作。

## 参考链接

1. https://isms2droid.com/
2. https://forums.republicwireless.com/t/moving-from-iphone-to-android-how-to-move-call-logs-and-text-messages/19882




