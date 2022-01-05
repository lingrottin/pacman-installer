# Pacman Install Script

# 此版本不再更新，请前往 [lingrottin / pacman-installer](https://github.com/lingrottin/pacman-installer)

在任意Linux发行版安装ArchLinux的pacman软件包管理器

主要针对apt用户，dnf用户可以直接
`$sudo dnf installer pacman`

pacman-installer使用方法：

`$su -`

`#git clone https://github.com/LGY07/pacman-installer.git`

`#cd ./pacman-installer/`

`#chmod +x ./pacman-installer.sh`

`#./pacman-installer.sh`

[方法2：也可以从这里下载，添加执行权限后运行pacman-installer.sh](https://github.com/LGY07/pacman-installer/releases)

### 更新可能不及时，下载速度可能慢，可以手动更改一些内容:

1.version=[[这里可以更改为****.**.**格式的日期(需要镜像站有的)](http://mirror.rackspace.com/archlinux/iso/)]

2.dir=[这里可以手动指定Pacman的根目录，注意不要在后面加上/]

3."http://mirror.rackspace.com/archlinux/iso/" 可以手动更改到速度较快的镜像站的"/archlinux/iso/"目录

### pacman安装的软件请使用/[Pacman的根目录]/usr/bin/[软件名]来运行
