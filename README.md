# Toolbox
不完全的 `material design` 风格，改进仍需学习
## 用法
> 文本加密在上面输入密码和要加密的文本，然后点击加密，字符即可被加密为密文；解密时，将密码输入上面一个文本框，并输入密码，即可解密

> 文件加密需用户自己找到需要加密的文件位置，在读取文件处选中文件，输入密码，然后点击写入文件，输入自定义加密后的文件名；解密时，读取被加密之后的文件，输入密码，然后点击写入，写明解密后的文件名和后缀名，否则文件可能无法被读取

> 图片加密就是文件加密，解密时可以在指定位置预览图片情况

## 如有bug 请多多提issus,欢迎提pr

2023年2月7日，发现安卓13用sui也没有data文件夹，正在修复这个问题
~~没有安卓13的手机，算了不修了~~

## 版本更迭日志：
v2.2.1
修复2.2.0版本中，相机权限申请异常的bug

v2.2.0
添加简易终端，可执行有限的linux指令，添加二维码扫描功能，可扫描后做出反馈，另外对安卓13的兼容性问题也做了弹窗提示

v2.1.1
侧滑栏处加入打开原生文件管理器的选项（给安卓11以上无法访问data文件夹提供的）；把设备信息从侧滑栏处移除，改到了关于页面；修复文件加密页面可能按钮失效的bug

v2.1.0
修改软件图标和名称；大改加解密功能UI,使用CardView实现界面；大改关于应用界面，取消之前的AlertDialog写法，改为使用CardView的界面，同时新加入使用帮助，里面有使用加解密的用法说明

v2.0.0
修改界面颜色，看起来更舒服；修改图标，使之更美观；修改主页面为bing主页

v1.2.0
改进界面观感，修复已知bug

v1.1.1
修复已知bug,优化用户UI

v1.1.0
基本实现加解密字符串与文件的功能
