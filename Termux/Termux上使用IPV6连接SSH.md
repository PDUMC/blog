#### 编辑`sshd_config`文件
```shell
vim /data/data/com.termux/files/usr/etc/ssh/sshd_config
```
在文件前面添加
```
AddressFamily any
ListenAddress ::
ListenAddress 0.0.0.0
PrintMotd yes
```