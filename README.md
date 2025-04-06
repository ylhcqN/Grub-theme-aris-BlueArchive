# Grub-theme-Tendou-Aris-BlueArchive
## 1.简介(Introduce)
- 1.The grub theme is about Tendou Aris which from the game Blue Archive.
- 1.这是一个天童爱丽丝主题，来自游戏《蔚蓝档案》
- 2.[哔哩哔哩视频介绍](https://www.bilibili.com/video/BV18FzpYSEHQ/)
## 2.预览(Preview)
![image](background.png)
## 3.安装方式(Installation)
- 1.将主题文件解压至“/boot/grub/themes/aris”(注意:主题文件夹的名字不一定为"aris",您不一定需要解压至“/boot/grub/themes”,如果这样请自行修改接下来的操作！)
- 1.Extract the theme file to "/boot/grub/themes/aris" (Note: the name of the theme folder does not have to be "aris", you do not necessarily need to extract it to "/boot/grub/themes", if so, please modify the next operation by yourself!) )
- 2.在“/etc/default/grub”中添加"GRUB_THEME="/boot/grub/themes/aris/theme.txt"
- 2.Add "GRUB_THEME="/boot/grub/themes/aris/theme.txt" to /etc/default/grub".
```sh
sudo nano /etc/default/grub        #使用nanp编辑grub文件。如果没有nano用别的也行
GRUB_THEME="/boot/grub/themes/aris/theme.txt" #添加以下内容
```
- 3.更新grub设置
- 3.Update the GRUB settings
```sh
sudo update-grub #Debian/Ubuntu
sudo grub-mkconfig -o /boot/grub/grub.cfg #Arch
```
## 4.许可(permission)
- 1.本项目遵循GPL-3.0 许可证
- 1.This project is licensed under the GPL-3.0 license
- 2.本项目所使用的美术素材来自《蔚蓝档案》，由NEXON Co., Ltd.版权所有
- 2.The art materials used in this project are from "Blue Archive", copyrighted by NEXON Co., Ltd.

## 5.支持我(Support me)
[bilibili](https://space.bilibili.com/1863500961)