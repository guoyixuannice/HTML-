在实验室扒出来一台旧电脑，突发奇想后在上面装了ubuntu15.04，本来就抱着折腾的心态，所以就可劲的捣鼓了。基本的配置装完后，就开始准备在图形折腾，毕竟人总喜欢美的东西。
#安装经典菜单指示器
```sudo add-apt-repository ppa:diesch/testing
```sudo apt-get update
```sudo install classicmenu-indicator
#安装系统指示器 syspeek
```sudo add-apt-repository ppa:nilarimogard/webupd8
```sudo apt-get update
```sudo apt-get install syspeek
#安装Cairo-Dock并启用桌面视觉效果
Cairo-Dock是一款比较灵巧的桌面启动条，有点类似与MAC
```sudo apt-get install cairo-dock cair-dock-plug-ins
#安装Compiz包启用cube效果
```sudo apt-get install compiz compizconfig-settings-manager compiz-plugins-extra
安装好后用ctrl+alt+鼠标左键来看效果
