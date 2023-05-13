<p align="center">
  <img width="18%" align="center" src="https://raw.githubusercontent.com/zhiyiYo/PyQt-Fluent-Widgets/master/docs/source/_static/logo.png" alt="logo">
</p>
  <h1 align="center">
  PyQt-Fluent-Widgets-Arm
</h1>
<p align="center">
  A fluent design widgets library based on PyQt5 for Arm64
</p>

<p align="center">
  <a style="text-decoration:none">
    <img src="https://img.shields.io/badge/Platform-%20Linux%20-blue?color=#4ec820" alt="Platform Linux"/>
  </a>

  <a style="text-decoration:none">
    <img src="https://img.shields.io/badge/License-GPLv3-blue?color=#4ec820" alt="GPLv3"/>
  </a>
</p>


![Interface](https://raw.githubusercontent.com/zhiyiYo/PyQt-Fluent-Widgets/master/docs/source/_static/Interface.jpg)

Support for component adaptation of pyqt5 built on source code.
## Build PyQt5 5.15.0
  [PyQt5 5.15.0 source code](https://files.pythonhosted.org/packages/8c/90/82c62bbbadcca98e8c6fa84f1a638de1ed1c89e85368241e9cc43fcbc320/PyQt5-5.15.0.tar.gz)

```
sudo apt-get install qt5-default libqt5svg5-dev  qtmultimedia5-dev libqt5x11extras5-dev libqt5remoteobjects5-dev libqt5xmlpatterns5-dev
```



```
pip install sip pyqt5-sip 
cd PyQt5-5.15.0
python3 configure.py
make
make install
```



## Install

To install lite version (`AcrylicLabel` is not available):
```shell
cd PyQt-Fluent-Widgets-Arm
python ./setup.py install
```

> **Warning**
> Only pyqt5 is supported.



## Run Example
After installing PyQt-Fluent-Widgets package using pip, you can run any demo in the examples directory, for example:
```python
cd examples/gallery
python demo.py
```

## Documentation
Want to know more about PyQt-Fluent-Widgets? Please read the [help document](https://pyqt-fluent-widgets.readthedocs.io/) 👈

## Video Demonstration
Check out this [▶ example video](https://www.bilibili.com/video/BV12c411L73q) that shows off what PyQt-Fluent-Widgets are capable of 🎉

## Work with QtDesigner
You can use PyQt-Fluent-Widgets in QtDesigner directly by running `python ./tools/designer.py`. If the operation is successful, you should be able to see the PyQt-Fluent-Widgets in the sidebar of QtDesigner.
> **Note**
> It is recommended to install pyqt5-tools and PyQt-Fluent-Widgets in a virtual environment. Please make sure **PyQt-Frameless-Window >= 0.2.7**.

## See Also
Here are some projects that use PyQt-Fluent-Widgets:
* [**zhiyiYo/Groove**: A cross-platform music player based on PyQt5](https://github.com/zhiyiYo/Groove)
* [**zhiyiYo/Alpha-Gobang-Zero**: A gobang robot based on reinforcement learning](https://github.com/zhiyiYo/Alpha-Gobang-Zero)

## Reference
* [**Windows design**: Design guidelines and toolkits for creating native app experiences](https://learn.microsoft.com/zh-cn/windows/apps/design/)
* [**Microsoft/WinUI-Gallery**: An app demonstrates the controls available in WinUI and the Fluent Design System](https://github.com/microsoft/WinUI-Gallery)

## License
PyQt-Fluent-Widgets is licensed under [GPLv3](./LICENSE).

Copyright © 2021 by zhiyiYo.
