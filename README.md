使用 Terminal 运行如下代码安装xcode
打开“终端”（terminal）这个Mac自带程序
输入：

xcode-select --install

然后敲回车安装

看见Macbook新系统开始保护电池可以设置充到80％自动停止了，用了好几年满电MacBook的换不起电池穷比的我开始慌了，还不想升级系统，四处白嫖写了个脚本让低版本系统的Mac也可以到指定电量自动停止充电。
仅仅是一个测试版本！！


不要将充电限制电量更改到大于100%否则本人不确定会出现什么情况！！！！

使用方法：
把代码直接复制到Mac自带的脚本编辑器（Apple Script）里然后直接运行即可。
如果需要恢复原状把充电截止百分比的16进制数改为64即可


如果不想复制粘贴，可以直接下载那个.scpt文件，用Mac自带的脚本编辑器（AppleScript）运行，在弹出的终端（terminal）窗口输入你的开机密码，输入过程看不到光标，输入完直接敲回车即可。效果是限制充电到80%
