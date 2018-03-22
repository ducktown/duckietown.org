---
layout: page
title: Duckietown高中版本
permalink: initiatives/duckietown-hs/index.html
---

<html>
  <body>
    <p> DuckietownHS是面向高中的Duckietown版本. <img src='/media/dthslogo.jpg' style="width:250px;height:196px;" align="right"/>

我们的目标是建造和编程能够在Duckietown的街道上自主移动的duckiebots。<br>

与Duckietown项目不同的是，duckiebotHS不使用摄像头作为传感器，而是使用红外传感器进行感知，进行车道保持。使用陀螺仪和加速计帮助确定车辆的运行情况。使用基于“飞行时间”测量原理的测距传感器，以避免障碍物碰撞。<br>

十字路口由在道路上水平排列的交通灯进行控制，无人车通过位于底盘底部的颜色传感器读取颜色。<br>

基本任务是让车辆自动驾驶，并识别路标。除了交通信号灯外，还有提供关于十字路口信息的路牌，路牌上写着通过红外传感器读出的信息。<p>

DuckiebotHS硬件系统有<br>

- STM32控制器：搭载有 ARM®32-bit Cortex®-M4 CPU以及FPU  <a href="http://www.st.com/content/st_com/en/products/evaluation-tools/product-evaluation-tools/mcu-eval-tools/stm32-mcu-eval-tools/stm32-mcu-nucleo/nucleo-f401re.html">NUCLEO-F401RE</a><br>

- 低压双刷直流电机驱动扩展板  <a href="http://www.st.com/en/ecosystems/x-nucleo-ihm12a1.html">X-NUCLEO-IHM12A1</a><br>

- MEMS和环境传感器扩展板  <a href="http://www.st.com/en/ecosystems/x-nucleo-iks01a2.html">X-NUCLEO-IKS01A2</a><br>

- 测距传感器  <a href="http://www.st.com/en/ecosystems/x-nucleo-53l0a1.html">X-NUCLEO-53L0A1</a>.<br>

目前此项目主要有意大利的非营利组织 <a href="http://www.perlatecnica.it">Perlatecnica</a> 进行开发。点击<a href="https://www.facebook.com/duckietownhs">Here</a> 浏览DuckitownHS Facebook。页面。<br>

详细硬件介绍，请参考： <a href="https://github.com/duckietown/duckietown-hs/tree/master/Docs/Specs">硬件信息</a><br>

 如果你添加了新的接口及设备，请告知 duckietownhs@gmail.com，将会添加到slack project.
</p>
<img src='/media/dthslogo2.jpg'  width="250"/>  
<h1>Company Partners</h1>
<p><img src='/media/logo-bluenet-vettoriale.png' style="width:150px;" align="left"/>
<a href="http://bluenetita.business.site/">Bluenet</a>
</p>


</body>
</html>
