# FMDataset
We released dataset which is used on our ICME'19 paper, called Fast sensor Motion Dataset. FMDataset aims to verify the robustness of Dense-SLAM system at different velocities of sensor motion. 
It contains color images, depth images and IMUs gathered by a handheld sensor Intel realsense ZR300. We filtered depth images and saved in "filtered" file.  
It has 14 sequences with 6 different scenes. Download Link:  
**Baidu Drive:** https://pan.baidu.com/s/1g5W1k6vhZM-3JTPQIDmS-A  code: ae79  
**Google Drive:** https://drive.google.com/drive/folders/1oaK3yreUtHjRTx-AVaspcCPGY7YEYBak?usp=sharing

We have also provide **DatasetReader** code for you to easily read our dataset into your project.

#### In the future, we will release dataset collect by Intel realsense D435i and Azure Kinect

# Reference
Our work has got ICME'19 best student paper award, you can found our paper and vido below:  
http://cgcad.thss.tsinghua.edu.cn/xufeng/2019FastFusion.pdf  
http://cgcad.thss.tsinghua.edu.cn/xufeng/zhuzunjie_VIDEO.mp4

# Citation
If you use FMDataset, please cite our ICME 2019 paper:
```
@inproceedings{Zhu2019,
  title={Real-time Indoor Scene Reconstruction with RGBD and Inertial Input},
  author={Zhu, Zunjie and Xu, Feng and Yan, Chenggang and Hao, Xinhong and Ji, Xiangyang and Zhang, Yongdong and Dai, Qionghai},
  booktitle={Proc. IEEE Int. Conf. Multimedia and Expo (ICME’2019), Shanghai, China},
  year={2019}
}
```
