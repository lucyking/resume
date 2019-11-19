# 夏大强 #
>https://github.com/lucyking &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  joehisaishi1943@gmail.com &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  13738020604 

  
#### 学历 ####
- 本科 杭州电子科技大学 电子信息工程 2010.09~2014.06 
- 硕士 杭州电子科技大学 计算机科学与技术 (全日制 学硕) 2014.09~2017.06  

#### 获奖 ####
- 2015华为奖学金 三等奖
- 2015计算机学院一等奖学金 Top10 
- 2015华为软件精英赛杭厦赛区32强
- 2016华为软件精英赛杭厦赛区64强

#### 能力 #####

- Python / PyPI
- Shell Script
- OpenCV / Qt 
- Linux System C/C++
- GCC/GDB / Cross Compile
- CMake / Makefile / Bitbake
- git / svn version control
- Markdown / reStructuredText  

#### 工作经历 ####
Nokia 基带平台开发 2018.04~2019.11 

- new feature / code rebase 
- 处理和解决测试/运营商现场问题   
- 编写脚本解析log 自动生成分析报告
- 编写脚本监测问题讨论邮件流向

海康威视 嵌入式软件开发 2017.04~2018.04

- 旧代码维护优化 / 功能增添
- 不同Android硬件平台移植 
- 模块库交叉编译 / 版本控制 
- 现场故障诊断与排除


网易 自动化测试开发 2015.11~2016.7

- Jenkins / Travis CI  **持续集成**
- Appium / Selenium2   **App/Web端自动化测试**
- RobotFramework **自动化测试框架**
- Netease aircv / AutoamtorX **计算机视觉分析与处理**

#### 项目经验

- **Nokia 移动网络基带项目** ```2018.04~2019.11```
	- 日常维护与new feature / 模块代码版本rebase。 
	- 增加iptables rules到待上市产品，增强设备安全性。
	- 总结组内维护经验，编写脚本自动分析日志并生成报告，提高问题处理效率。
	- 编写脚本监测邮件中问题讨论流向，及时发现新问题，避免人工检查大量邮件。<br><br>

- **海康威视 嵌入式项目** ```2017.04~2018.04```
	- 优化传输协议。将定长传输调整为变长传输，节省带宽，增加传输效率。
	- 增加参数I/O模块。通过JSON/XML格式输入程序参数，使设备避免重复启动，降低维护成本。
	- 引入版本控制系统。部署gitlab管理模块库与定制，提高生产效率。   <br><br>
- **USB打字机**  ```2015.10.24 SegmentFault 1024黑客马拉松 《不能连接电脑的打字机和咸鱼有什么区别》```
	- 运用A/D转换原理，改装油墨打字机，使其能通过USB输出字符。
	- 利用MSP430 ADC12实现输入电压采样,以38译码器，逻辑控制开关控制usb键盘模块实现输出。   <br><br>
- **[基于Kinect 3D摄像头的机器人环境感知和实时避障](https://github.com/lucyking/pickinect)**  ```2014.10.1~2015.6.15```
	- 编写ARM架构的Kienct设备驱动，获取深度摄像头原始数据。
	- 将Y10B格式的深度数据转换成RGB格式，通过OpenCV转换成可视化图像，方便实时监测运行状况。
	- 编写算法解析深度数据，计算附近障碍物的方位和距离，机器人自动避障提供参考信息。<br><br>
- **基于六轴陀螺仪MPU6050姿势解析的AGV惯性导航**  ```2014.9.30~2015.8.15```
	- 编写设备驱动，采集陀螺仪的线加速度和角加速度等原始数据。
	- 编写动态姿势解析函数，去除重力加速度在水平方向的分量。 
	- 应用积分方程推导机器人在水平方向上的行进距离和方位，为自动导航提供坐标参考。<br><br>
- **RobotFramework自动化测试框架** ```2015.11.1~2016.8.5```  
	- 搭建自动化测试框架，实现测试用例**自动化执行**。
	- 移植**OpenCV**至RobotFramework：
		- 解决WebView等部分元素无法定位问题，使测试用例可以实现基于**计算机视觉**的点击操作。	
	- 积极提交lib补丁，官方已接受补丁如下：
		- **Appium** (3900+ stars)
		    - #1 : https://github.com/appium/appium/pull/6283
		    - #2 : https://github.com/appium/appium/pull/5987
		- **RobotFramework-appiumlibrary** (90+ stars)
		    - #1 : https://github.com/jollychang/robotframework-appiumlibrary/pull/81 
	- 在自动化测试中应用Jenkins CI，实现**定时**、**代码提交**等事件触发用例自动执行。
	- 将RobotFramwork Library迁移到github，利用**Travis CI**实现**pypi**版本自动发布。