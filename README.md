# 资料分享

## 项目目的

该项目主要分享一些专业相关的资料<br>

## 使用方法

如需要下载单个文件，请点到该文件的页面再进行下载<br>

## STM32模板

### STM32工程模板的结构如下：<br>
    （某型号）
        Core：STM32库函数驱动
        FWLib：STM32库函数源文件
        Hardware：放置工程中需要用到的模块的源文件
        OBJ：放置编译产生的文件
        SYSTEM：包含正点原子的常用的三个文件
        User：工程文件所在文件夹

工程模板采用`7Zip`打包，请使用`7Zip`或其他可以解压`7z`后缀压缩包的工具进行解压<br>
`7Zip`开源软件下载地址：https://www.7-zip.org/<br>

如出现`未作任何修改但编译出现错误或警告`，欢迎在该文件下方留言指正<br>
或发送邮件至http://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=bulijie233@vip.qq.com<br>

## STM32CubeMX
这些资料均来自于MOOC课程`基于STM32CubeMX和HAL驱动库的嵌入式系统设计`<br>课程地址为：https://www.icourse163.org/course/UESTC-1207429802<br>
以下为该课程的部分公告<br>1、在老师的B站上发布了STM32CubeIDE的使用视频以及STM32的HAL库使用经验总结，会不定时更新视频和文档。<br>
2、关于STM32F411核心板的设计，我们也在B站上发布了由立创EDA莫工设计的STM32F411核心板案例，欢迎大家观看。<br>
3、老师的B站Up号：QiQiangUESTC<br>
4、关于CubeMX软件更深入的学习，可以参考官方文档UM1718，文档可在意法半导体的官网上下载。<br>
5、STM32CubeMX软件的下载地址：http://www.st.com/en/development-tools/stm32cubemx.html?sc=stm32cubemx<br>
6、MDK-ARM软件的下载地址：http://www.keil.com/download/product/<br>
7、在进行CubeMX软件学习之前，建议在桌面上新建一个名为CubeMX的文件夹，用于存放本书所有的例程代码。对于STM32微控制器的外设学习，可以再建立子文件夹：按照外设名建立，如GPIO、EXTI、TIMER、UART等。再次强调：CubeMX建立的工程必须存放在英文路径下
