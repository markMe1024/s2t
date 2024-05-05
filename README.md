# s2t：docx文件批量简繁转换

这是一个用于批量将文件从简体转换为繁体（或反之）的工具。可将选定的文件夹及其子文件夹内全部docx文件进行简繁转换，转换后的文件会覆盖原有文件。



## 安装和使用

1. 克隆仓库到本地：

   ```
   git clone git@github.com:markMe1024/s2t.git
   ```

   

2. 安装依赖：

   ```
   cd s2t	
   pip3 install python-docx opencc-python-reimplemented 
   ```

   

3. 运行项目：

   ```
   python3 converter.py
   ```

   

4. 在应用程序中，选择要转换的文件夹，然后点击相应按钮。

   

## 许可证

本项目基于 MIT 许可证。



## 其他

1. setup.py和logo.icns这两个文件，是用来py2app打包mac应用用的，本地执行python代码不需要关心。
2. wipe_off_img文件夹内资源，和简繁转换无关，提供批量去除docx文件中的图片功能。
