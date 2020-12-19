# PyQtClient

PyQt Examples Client For https://github.com/PyQt5/PyQt

It requires both Python35+ and PyQt5 and QtWebKit.

需要 Python35+ PyQt5 和 QtWebKit

## Installing （安装）

install requirements

```
pip install requests -i https://pypi.doubanio.com/simple/
pip install pygit2==0.27.2 -i https://pypi.doubanio.com/simple/
pip install PyQt5 -U -i https://pypi.doubanio.com/simple/
pip install PyQt3D -U -i https://pypi.doubanio.com/simple/
pip install PyQtChart -U -i https://pypi.doubanio.com/simple/
pip install PyQtDataVisualization -U -i https://pypi.doubanio.com/simple/
pip install PyQtPurchasing -U -i https://pypi.doubanio.com/simple/
```

### For Windows

```
pip install PyQtWebKit -U -i https://pypi.doubanio.com/simple/
```

### For RHEL_7_6-X86_64

1. Install Python35+
2. Install Qt5.13.1 to ~/Qt5.13.1
3. clone https://github.com/PyQt5/PyQtWebKit and run `./build.sh`

## Todo

Replace QtWebKit to QtWebEngine

## Notice

If the first boot is slow  第一次运行很慢（因为在clone例子源码）

    1. git clone https://github.com/PyQt5/PyQt.git
    2. move PyQt to PyQtClient\Resources\Data\Projects
    3. start PyQtClient

## ScreenShot

![PyQtClient](ScreenShot/PyQtClient.gif)
