<div align="center">
<img src="https://rishavanand.github.io/static/images/greetings.gif" align="center" style="width: 100%" />
</div>  

My ![Visitor Count](https://profile-counter.glitch.me/Christmas-Wong/count.svg) visitor


# 在这里，你可以看到更多简历上没写的，真实的 YJ <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50">
 YSKMM - You Should Know More about Me 👋
<img src="https://github.com/Yinjie-ZHENG/Yinjie-ZHENG/blob/main/202303299.jpg" width="250"  align='right'>

- 🔭 I’m currently working as **Research Assistant** on **NUS Media Research Lab**

- 🌱 I’m currently learning **CV, deep learning, machine learning**

- 👯 Currently in **Singapore**

- 💬 Ask me about Deep Learning, Python and my projects

- 📫 How to reach me: **e0674482@u.nus.edu**

- 😄 You may like [Zhihu](https://www.zhihu.com/people/zheng-yin-jie-91/posts)
- [![GitHub Thaiane](https://img.shields.io/badge/Stars-7k-lightgrey?logo=github&style=social)](https://github.com/Yinjie-ZHENG)
- [![Zhihu](https://img.shields.io/badge/%E7%9F%A5%E4%B9%8E-Zed%20Ranger-blue)](https://www.zhihu.com/people/zheng-yin-jie-91)
- 
## 教育经历
   
* 新加坡国立大学&emsp;&emsp;&emsp;&emsp;&emsp;2021.01~2023.01&emsp;&emsp;&emsp;&emsp; 计算机科学 - 硕士学位         
* 广东工业大学&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2015.09~2019.07&emsp;&emsp;&emsp;&emsp; 机械设计制造及其自动化-学士学位  

## 项目经验
**基于图像embedding搜索的用于伪造视频检测的自适应建模方法&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2022.10-2023.01**



* **项目描述**: 针对Deepfake检测模型容易受到对抗样本攻击的威胁，基于白盒攻击和度量学习的原理，结合模型微调方法，提出了一种能防御对抗攻击的Deepfake检测技术。该方法在FaceForensics++数据集中，在没有经过对抗样本训练的情况下，面对白盒攻击展现出更强的鲁棒性。该项目通过Pytorch框架实现。
* **项目成果**: Xception模型在经过对抗样本的攻击后，正确率从90.75%降低到1.04%，使用该技术能在没有经过对抗样本训练的情况下，使原有的Xception模型针对对抗攻击的正确率提升8.44%
* **项目角色**：项目负责人
* **项目贡献**：
  1. 设计并实现了提取图像embedding模块；
  2.	设计并实现了基于已提取的图像embedding，结合多种白盒攻击的相似图像搜索方案；
  3.	设计并实现了推理阶段post-training技术在Deepfake检测场景下防御对抗样本攻击的应用；使得该技术能应用于所有Deepfake检测模型（即插即用）；
  4.	项目代码的封装和项目管理工作
> 项目地址 at [Github](https://github.com/Yinjie-ZHENG/Adaptive-Modelling-for-Deepfake-Detection-using-post-train)



**用于防御对抗攻击的自适应建模方法&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 2022.11-2023.01**

* **项目描述**: 针对神经网络容易受到对抗样本攻击的威胁，基于白盒攻击的原理，结合模型微调方法，提出了一种能防御不同类型对抗攻击的技术。在CIFAR-10、MNIST和Tiny ImageNet数据集中，面对白盒攻击具备更强的鲁棒性。该项目通过Pytorch框架实现。
* **项目成果**: 面对不同对抗样本的攻击（Fgsm, Pgd等攻击方法），该技术分别在CIFAR-10，MNIST和Tiny ImageNet数据集获得7.5%，0.82%和1.33%的鲁棒性提升
* **项目角色**：项目负责人
* **项目贡献**：
  1.	设计并实现了推理阶段post-training技术在多分类场景下防御对抗样本攻击的应用；使得该技术能应用于所有防御检测模型（即插即用）；
  2.	实现了可自定义对抗攻击手段的功能，以应对未来需要的多种新的对抗攻击方法；
  3.	项目代码的封装和项目管理工作

> 项目地址 at [Github](https://github.com/Yinjie-ZHENG/Adaptive-Modelling-Against-Adversarial-Attacks-using-post-train)




**伪造视频检测&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 2021.07-2021.12**
* **项目描述**: 多种音视频伪造技术结合对抗扰动方法能骗过大部分检测模型，带来社会性威胁。针对这种挑战，基于Pytorch框架搭建了一个多模态模型，结合频率检测方法、神经网络和多模态融合技术从单帧画面、视频和音频三方面来进行伪造视频检测。
* **项目成果**:该方法在AI Singapore Trusted Media Challenge中最高达到第14的成绩；
* **项目角色**：项目负责人
* **项目贡献**：
  1.	设计并实现了单帧图像的频域特征提取模块；
  2.	设计并实现了语音和视频的特征提取模块；
  3.	实现了将单帧画面、视频和音频三种模态特征的融合方法；
  4.	实现了将代码封装成docker镜像的工作




**基于corresponding search和拉普拉斯变换的人脸表情迁移&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 2021.09-2021.11**
* **项目描述**: 给定默认表情的3D人脸模型，一个包含深度信息的含表情的人脸图片（或两张同表情不同角度的人脸图片）以及部分基点的对应关系；实现将特定目标表情迁移到默认人脸模型的功能
* **项目成果**: 该项目获得的课程评分为A
* **项目角色**：项目组员
* **项目贡献**：
  1.	实现了使用非深度学习的方法进行人脸表情迁移；
  2.	设计并实现了本项目的corresponding search部分；
  3.	通过与组员和Leow Wee Kheng教授的多次有效沟通，展现了良好的团队合作和沟通能力；



**针对陶瓷材料显微结构SEM图片的视觉识别程序开发 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 2019.01-2019.05**
* **项目描述**: 显微结构分析在材料科学领域十分重要，现有的陶瓷材料分析方法多为人工标注和传统阈值分割；本项目提出了针对复杂背景下使用深度学习的图像分割方法
* **项目成果**: 专利 (CN:2019108208000)(实质审查阶段)：一种晶体材料图像识别方法及装置
* **项目角色**：项目负责人
* **项目贡献**：
  1.	使用SEM完成了两种复相陶瓷材料的图像数据采集和数据标注；
  2.	通过EDA分析滤除无效标注，完成数据清洗和数据增强；
  3.	训练多个图像分割模型并融合输出结果，最终对每个晶粒输出分割结果；
  4.	对晶粒的分割结果进行形状拟合，将需要的分析结果（如拟合椭圆的长短轴数据）导出为表格；

> 项目地址 at [Github]()


**帮助健身运动人群快速上传卡路里摄入及消耗的网页设计&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 2021.10-2021.12**
* **项目描述**: 针对健身运动人群对自身健康管理的需要，结合OCR技术和深度学习模型，设计了一个帮助健身运动人群快速上传卡路里摄入及消耗的网页设计。该网页能帮助健身运动人群通过上传自己当天的食物图片、运动APP界面截图自动计算卡路里的摄入及消耗；并通过绑定宠物系统激励并监督健身。
* **项目角色**：项目负责人
* **项目贡献**：
  1.	使用React设计网页前端界面，实现了Google账号登陆的功能；
  2.	使用MongoDB实现了网页后端数据存储；使用python+flask实现了后端计算和模型调用；
  3.	使用OCR检测技术对用户上传的运动APP界面截图自动获取卡路里消耗量；
  4.	使用目标检测模型检测用户上传的食物图片自动获取卡路里摄入量；设计并实现了宠物管理系统，将每日的卡路里消耗量转化为宠物币，宠物币可以购买食物和玩具用以增加宠物的饥饿值和快乐值；


> 项目地址 at [Github]()



# My Skill Set  
<table><tr><td valign="top" width="33%">



### DeepLearning  
<div align="center">  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/pytorch-icon.svg" alt="pytorch" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/python-original.svg" alt="Python" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/c-original.svg" alt="C" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/cplusplus-original.svg" alt="C++" height="50" />   


</div>

</td><td valign="top" width="33%">



### Backend  
<div align="center">  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/linux-original.svg" alt="Linux" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/flask.png" alt="Flask" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/mongodb-original-wordmark.svg" alt="MongoDB" height="50" />  
</div>

</td><td valign="top" width="33%">



### Frontend  
<div align="center">  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/html5-original-wordmark.svg" alt="html5" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/react-original-wordmark.svg" alt="react" height="50" />  
 <img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/css3-original-wordmark.svg" alt="css3" height="50" />  


</div>

</td></tr></table>  

<br/>  
