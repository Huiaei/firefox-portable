# firefox-portable

基于[Libportable](https://github.com/adonais/libportable)组件制作的Firefox Portable版本。

## 第一节 快速使用

1. 在[Release](https://github.com/Huiaei/firefox-portable/releases)下载你想要的版本或者是[最新的Release](https://github.com/Huiaei/firefox-portable/releases/latest)，文件是“core.zip”。
2. 在你喜欢的地方新建一个文件夹，将core.zip打开，你会看到里面有一个“core”文件夹，将文件夹解压到你新建的文件夹里。
3. 打开core文件夹，双击firefox.exe。不出意外的话，你已经成功了，你可以在firefox的地址栏输入“about:support”查看配置文件夹，如果路径是你新建的文件夹，那么恭喜你。

## 第二节 手工制作

1. 首先你需要下载Firefox的安装包和Libportable。
2. 新建一个文件夹。通过压缩软件打开Firefox的安装包，里面会有core文件夹和setup.exe安装程序，将core文件夹解压出来。
3. 解压Libportable文件，将内部文件复制到firefox的core文件内，注意，不是将文件夹复制进去，如果你看见的是文件夹，那么你需要在进入目录，将最里层的文件复制过去。
4. 打开core目录，运行injectpe.bat，按照指示进行操作，完成后即可使用。

## 第三节 配置调整

Libportable提供配置文件进行调整功能，具体请前往[此项目](https://github.com/adonais/libportable)查看。

------

感谢Libportable项目方便了portable版本制作。
