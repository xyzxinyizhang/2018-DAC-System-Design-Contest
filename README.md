# 2018 DAC System Design Contest
# Overview
The 2018 System Design Contest features embedded system implementation of neural network based object detection for drones. Contestants will receive training dataset provided by our industry sponsor DJI, and a hidden dataset will be used to evaluate the performance of the designs in terms of accuracy and power. Contestants will compete in two different categories: FPGA and GPU, and grand cash awards will be given to the top three teams in each category. In addition, our industry sponsor Xilinx and Nvidia will provide a limited number of teams successfully registered with a free design kit (on a first-come-first-served basis). The award ceremony will be held at 2018 IEEE/ACM Design Automation Conference. The contest detail can be found at [DAC webpage](http://www.cse.cuhk.edu.hk/~byu/2018-DAC-HDC/index.html "悬停显示"). The contest supporting source code can be found [here](https://github.com/yunqu/dac_2018 "悬停显示").
# ORGANIZING COMMITTEE
Yiyu Shi, Chair
University of Notre Dame

Jingtong Hu, Co-Chair
University of Pittsburgh

Christopher Rowen, DAC Representative
Cognite Ventures

Cong Zhao, Industry Liaison
DJI

Bei Yu, Publicity
Chinese University of Hong Kong
# SPONSOR
DJI; XILINX; NVIDIA
# DATASET
The contest dataset is provided from DJI, captured by unmanned aerial vehicles(UAV).
This dataset contains12  classes  of  images  and  95  sub-categories.  For  each  sub-category,  70%  of  the  images  are  provided  for  training  and30%  are  reserved  for  evaluation.
in  this  dataset,  most  of  the  images  have a object size __1-2%__ of the captured images (640x360), which is a main character of UAV-view images(ILSVRC with average object ratio 17%, PASCAL VOC with average object ratio 20%,). 

The 70% dataset is open source and can be download [here](https://pitt.box.com/s/756141768nn92cj0dkfbg6dan17c4h4q "悬停显示").
A sample dataset can be download [here](https://pitt.box.com/s/cq6edt2zm99s1zwa37u56gctpk1qtgpa "悬停显示").

# FPGA WINNERS (PYNQ-Z1)
***
#### First Place
[TGIIF](https://github.com/hirayaku/DAC2018-TGIIF "悬停显示") - Tsinghua University  
Shulin Zeng, Weicong Chen, Tianhao Huang, Yujun Lin, Weizhe Meng, Zhenhua Zhu, Yu Wang
***
#### Second Place
[systemsETHZ](https://github.com/fpgasystems/spooNN "悬停显示") - ETH Zurich  
Kaan Kara, Ce Zhang, Gustavo Alonso
***
#### Third Place
[iSmart2](https://github.com/onioncc/iSmartDNN "悬停显示") - University of Illinois at Urbana-Champaign  
Cong Hao, Yuhong Li, Sitao Huang, Xiaofan Zhang, Tianqi Gao, Jinjun Xiong, Kyle Rupnow, Huafeng Yu, Wen-Mei Hwu, Deming Chen
***
The detailed ranking can be found [here](http://www.cse.cuhk.edu.hk/~byu/2018-DAC-HDC/ranking.html#may "悬停显示")
# GPU WINNERS (TX-2)
***
#### First Place
[ICT-CAS](https://github.com/lvhao7896/DAC2018 "悬停显示") - Institute of Computing Technology, Chinese Academy of Science   
Hao Lu, Xuyi Cai, Xiandong Zhao, Ying Wang
***
#### Second Place
[DeepZ](https://github.com/jndeng/DACSDC-DeepZ "悬停显示") - Zhejiang University  
Jianing Deng, Cheng Zhuo
***
#### Third Place
[SDU-Legend](https://github.com/xiaoyuuuuu/dac-hdc-2018-object-detection-in-Jetson-TX2 "悬停显示") - Shandong University  
Chuanqi Zang, Jie Liu, Yueming Hao, Shiqing Li, Miao Yu, Yanbo Zhao, Mingyi Li, Pengfei Xue, Xiaoyu Qin, Lei Ju, Xin Li, Mengying Zhao, Hongjun Dai
***
The detailed ranking can be found [here](http://www.cse.cuhk.edu.hk/~byu/2018-DAC-HDC/ranking.html#may "悬停显示")
