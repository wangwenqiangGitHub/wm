# dwm
- 多个窗口实现剪切板复制按键:左键选取复制.中键粘贴

# dwm设置方法
```
# 1.创建dwm.desktop文件,存放在/usr/share/xsession
[Desktop Entry]
Encoding=UTF-8
Name=Dwm
Comment=Dynamic window manager
Exec=dwm
Icon=dwm
Type=XSession
# 2.修改dwm文件，sudo make clean install
```
# dwm快捷键
| 快捷键          | 说明                  |
|-----------------|-----------------------|
| mod j           | 切换聚焦窗口          |
| mod k           | 切换聚焦窗口          |
| mod '           | scratchpad小窗口      |
| mod u           | 隐藏桌面              |
| mod shift u     | 显示隐藏桌面          |
| mod shift f     | 全屏                  |
| mod shift space | 取消全屏              |
| mod ctrl s      | screenkey软件打开关闭 |
| mod s           | 启动dmenu             |

# st快捷键
| 快捷键       | 说明 |
| ctrl shift c | 复制 |
| ctrl shift v | 粘贴 |
