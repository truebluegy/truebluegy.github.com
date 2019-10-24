<table border="0">
  <tr>
    <td width="75%">
      <h1>高杨</h1>
      <p><b>在读博士生</b></p>
      <p><b>学校: 纽约州立布法罗分校计算机科学与工程学院</b></p>
      <p><b>邮箱：ygao36@buffalo.edu</b></p>
    </td>
  </tr>
</table>

# 个人总结 

本人在校期间长期从事生物特征识别和身份认证，物联网感知和安全, 以及机器学习和神经形态计算
相关研究，并对机器学习和深度学习，人机识别对抗，物联网，以及可穿戴和移动计算有深入了解。

# 教育背景

- 纽约州立大学布法罗分校(美国), 计算机科学与工程, 在读博士生2018.1 - 至今
- 纽约州立大学宾汉姆顿大学(美国), 电子和计算机工程, 博士生2015.1 - 2017.12
- 斯蒂文斯理工学院(美国), 电子工程, 硕士2012.9 - 2014.5
- 电子科技大学(成都), 微电子科学与技术, 学士2008.9 - 2012.5




# 科研经历

## 生物识别和认证
### 基于耳道回声的生物特征识别和认证
本项目实现了基于耳机的认证系统开发。通过在耳机内嵌传感器，捕捉耳道内的声学特性。经过事件
监测，滤波，干涉消除等预处理模块，并利用Welch 功率谱密度估计来提取耳道的生物特征信息，最后采
用支持向量机(SVM) 和卷积神经网络(CNN) 对用户的身份进行区分和认证。同时在不同的环境下对系统
鲁棒性进行测试，利用3D 打印技术模拟欺骗式攻击，并对其进行安全性评估。

### 基于心电信号的生物特征识别和认证
本项目首先设计了心电信号认证系统的前端模块。采用定制化的感应电极和片上电路，搭建了低功
耗可穿戴心电传感器。同时开发了后端信号处理模块包括心电信号的降噪预处理，基于小波变换(Wavelet
Transform) 的特征提取和身份认证。设计新增的残差检测模块可有效防御噪声注入式的模板攻击。

### 基于键盘鼠标输入习惯的无感知身份持续认证
本项目旨在开发一套基于多模态的用户身份认证系统，通过结合用户的键入习惯信息，鼠标的滑动信
息，以及手腕上通过智能手环采集的IMU 惯性信息进行多模态建模。利用随机森林(Random Forest) 和时
序采样分析设置动态阈值，实现了高准确率，低延时的无感知持续身份认证。

### 基于光电容积脉搏波的非接触式身份认证
基于人脸识别认证的易被伪造的缺点，本项目旨在开发一款非接触式的持续身份认证系统，通过摄像
头，利用Viola-Jones 和KLT 算法捕捉到用户的脸部信息，采用拉普拉斯金字塔(Laplacian Pyramid) 对脸
部关键区域的图像信息进行增强并提取出动态的光电容积脉搏波的生物特征，最后利用深度神经网络进行
身份识别认证。

## 物联网感知和安全
### 3D 打印防伪技术
本项目通过对3D 打印机加热过程中的热力学特性和控制参数进行建模，运用自编码器(Auto-Encoder)
提取了打印喷头在生产过程中造成的不可控的误差而产生的独特硬件指纹。本项目为3D 打印产品的知识
产权保护提供了可行性分析和验证。

### 3D打印安全监控
本项目旨在开发一套基于FMD 的3D 打印普式监控系统用于检测网络物理攻击。通过对3D 打印机部
署IMU 传感器和摄像头，捕捉打印过程中产生的侧信道信息，并利用卡尔曼滤波(Kalman Filter)，梅尔频
率倒谱系数分析(MFCC) 和Canny 边缘检测算法进行多模态分析，实时还原出的真实的打印行为，检测固
件在3D 打印过程中是否遭受了网络物理攻击。

### 基于ECG 身份识别系统的风险性研究
本项目旨在探索在例如智能手表和手环等可穿戴设备场景下以ECG 为密匙的身份识别系统的潜在风
险。基于公开的数据库，在无需获取用户真实信息的情况下，实现了对其认证系统的破解。首先使用局
部二值模式(LBP) 对数据进行编码，并利用聚类算法对数据集对象进行分类排序，通过自编码器(AE) 和
曲线拟合来实现数据增强，再搭建和训练基于变分自编码器(VAE)，主成分分析(PCA) 和生成对抗网络
(GAN) 的生成模型，进而生成仿冒ECG 样本。

## 机器学习和神经形态计算
### 自主目标跟踪系统
本项目旨在基于图像目标跟踪的场景下，设计采用粒子滤波器(Particle Filter) 和不同神经网络结合
的多种架构，包括堆栈式去噪自编码器(SDAE)，卷积神经网络(CNN) 和回声状态神经网络(Echo State
Network)，并且评估了相应的跟踪准确度和执行效率。

### 对储备池计算网络的认知和研究
本项目旨在探索生物学神经网络和人工神经网络之间的潜在联系，通过用储备池计算网络(Reservoir
Computing) 对大脑活动信号的学习和仿真，对与记忆有关的大脑结构进行建模，从而试图对递归神经网络
(RNN) 中的记忆与表达相关网络特征进行解读。

# 论文发表
1. Yang Gao, Borui Li, Wei Wang, Wenyao Xu, Chi Zhou, Zanpeng Jin. ”Watching and Safeguarding Your 3D Printer: Online Process Monitoring Against Cyber-Physical Attacks.” Proc. ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 2.3 (2018): 108.
2. Yang Gao, Wei Wang, Vir V Phoha, Zhanpeng Jin. ”EarEcho: Using Ear Canal Echo for Wearable Authentication.” Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 3.3 (2019): 81. <a href="https://truebluegy.github.io/EarEcho__Using_Ear_Canal_Echo_for_Wearable_Authentication.pdf" target="_blank">[pdf].</a>
3. Yang Gao, Wei Wang, Borui Li and Zhanpeng Jin. ”Replicating Your Heart: Exploring Presentation Attacks on ECG Biometrics Using Synthesized Heart Waves,” In Proc. 2018 IEEE Conf. Communications and Network Security (CNS). IEEE, 2018. 
4. Omkar Patil, Wei Wang, Yang Gao and Zhanpeng Jin. ”A Non-Contact PPG Biometric System Based on Deep Neural Network,” In Proc. 9th IEEE Int. Conf. Biometrics: Theory, Applications, and Systems (BTAS). IEEE, 2018.
5. Borui Li, Wei Wang, Yang Gao, Vir Phoha and Zhanpeng Jin. ”Hand in Motion: Enhanced Authentication Through Wrist and Mouse Movement,” In Proc. 9th IEEE Int. Conf. Biometrics: Theory, Applications, and Systems (BTAS). IEEE, 2018.
6. Wang, Wei, Yang Gao, and Zhanpeng Jin. ”Interpretive Reservoir: A Preliminary Study on The Association Between Artificial Neural Network and Biological Neural Network.” In Proc. 2018 International Joint Conference on Neural Networks (IJCNN), pp. 1-8. IEEE, 2018.
7. Patil, Omkar R., Wei Wang, Yang Gao, Wenyao Xu, and Zhanpeng Jin. ”A low-cost, camera-based continuous PPG monitoring system using Laplacian pyramid.” Smart Health 9 (2018): 2-11.
8. Yang, Wei, Wei Wang, Yang Gao, and Zhanpeng Jin. ”An Embedded Tracking System with Neural Network Accelerator.” In Proc. 2018 International Joint Conference on Neural Networks (IJCNN), pp. 1-7. IEEE, 2018.
9. Yang, Wei, Wei Wang, Yang Gao, and Zhanpeng Jin. ”A Comparative Study of Object Tracking using CNN and SDAE.” In Proc. 2018 International Joint Conference on Neural Networks (IJCNN), pp. 1-6. IEEE, 2018.
10. Li, Borui, Han Sun, Yang Gao, Vir V. Phoha, and Zhanpeng Jin. ”Enhanced free-text keystroke continuous authentication based on dynamics of wrist motion.” In 2017 IEEE Workshop on Information Forensics and Security (WIFS), pp. 1-6. IEEE, 2017.
11. Patil, Omkar R., Yang Gao, Borui Li, and Zhanpeng Jin. ”CamBP: a camera-based, non-contact blood pressure monitor.” In Proc. 2017 ACM International Joint Conference on Pervasive and Ubiquitous Computing (UbiComp’17), pp. 524-529. ACM, 2017.
12. Yang Gao, Jack P. Lombardi, Varun V. Soman, James Turner, Mark Poliks, Zhanpeng Jin. ”Ultra-Wearable Capacitive Electrode Design for Long-time Monitoring of ECG.” In Proc. 42nd Annual Northeast Biomedical Engineering Conference (NEBEC), 2016.
13. Borui Li, Wei Wang, Yang Gao, Vir V Phoha, Zhanpeng Jin. ”Wrist in Motion: A Seamless Context-aware Continuous Authentication Framework Using Your Clickings and Typings.” IEEE Transactions on Biometrics, Behavior, and Identity Science.
14. Omkar Patil, Wei Wang, Yang Gao and Zhanpeng Jin. ”A Camera-Based Pulse Transit Time Approach for Non-Intrusive Blood Pressure Monitoring.” The 7th IEEE Int. Conf. Healthcare Informatics (ICHI’19). 






