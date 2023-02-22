## 基于`vinceliuice/grub2-themes`修改

## 使用方法

安装主题
```shell
git clone https://github.com/Vinx911/grub2-theme-vinkvin.git
sudo cp -r grub2-theme-vinkvin /usr/share/grub/themes/vinkvin
```

编辑`/etc/default/grub`文件
```shell
sudo vim /etc/default/grub
```

将`GRUB_THEME`改为以下内容
```shell
GRUB_THEME="/usr/share/grub/themes/vinkvin/theme.txt"
```

生成grub
```shell
sudo grub-mkconfig -o /boot/grub/grub.cfg
```