# 本项目食用指南

1. 根据 [tModLoader官方文档](https://github.com/tModLoader/tModLoader/wiki/Developing-with-Visual-Studio)
安装Visual Studio，注意安装时选择`.NET desktop development`
![截图](/md/1.jpg)  

2. 根据 [tModLoader官方教程](https://github.com/tModLoader/tModLoader/wiki/Basic-tModLoader-Modding-Guide)
创建你的模组  

3. 将本项目的 **\*.tt** 文件丢到模组文件夹中。  
   * 进行粘贴和每次保存、运行时均会有如下提示，点击确定即可
    ![安全提示](/md/安全提示.jpg)  

4. 此时在文件夹中出现与 **\*.tt** 文件同名的 **\*.cs** 文件，即为生成的代码文件。  

5. 修改变量区的变量来调整你需要的参数
![变量区](/md/变量区.jpg)  

6. 对修改好的 **\*.tt** 进行保存或切换页面均会自动将修改应用到对应的 **\*.cs** 文件上
7. 将生成的文件 **\*.cs** 文件重命名，保持与文件内类名一致，此时对 **\*.tt** 文件的修改将不再应用到已重命名的文件，你可以重新对 **\*.tt** 文件进行编辑来生成新的代码文件
8. 根据自己的需求对由特殊事件（如左键点击）触发的函数进行内容编写，如果没需求可以不写
![自己改](/md/自己改.jpg)
9. 代码部分就完成了，接着把贴图文件丢到代码所在的文件夹并保证他们具有相同的文件名（后缀不同）
10. 理论上就可以跑了