# Source-Codes-3DVison
Source codes collection for 3d vision 视觉三维重建领域的源码收集

三维重建开源项目汇总，不定期更新。

## SFM
- **openmvg【3.5k stars】【Mozilla Public License Version 2.0】【[https://github.com/openMVG/openMVG](https://github.com/openMVG/openMVG)】**
一个多视几何三维重建算法库，从无序二维影像集恢复相机的三维位姿。SFM（Structure From Motion）经典算法库。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527092742723.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)

- **colmap【3k stars】【new BSD license】【[https://github.com/colmap/colmap](https://github.com/colmap/colmap)】**
一个多视几何三维重建算法库，从无序二维影像集恢复相机的三维位姿（SFM）以及多视立体重建（MVS）。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527092509685.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
- **alicevision【1.8k stars】【MPL2 license】【[https://github.com/alicevision/AliceVision](https://github.com/alicevision/AliceVision)】**
一个开源的摄影测量系统框架
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527092356416.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
## MVS
- **openmvs【1.6k stars】【AGPLv3】【[https://github.com/cdcseacave/openMVS](https://github.com/cdcseacave/openMVS)】**
一个多视立体重建开源算法库，基于带有位姿信息的图像集，重建高质量的纹理模型，效果非常出色。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527225531907.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
- **meshroom【6.5k stars】【MPL2 license】【[https://github.com/alicevision/meshroom](https://github.com/alicevision/meshroom)】**
和OpenMVS库一样，也是基于带有位姿信息的图像集，重建高质量的纹理模型，但是效果没有OpenMVS好，速度更快些。带有图形界面，做的很漂亮。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527230158531.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
## SLAM
### VSLAM
- **orb-slam2【6.2k stars】【GPLv3 license】【[https://github.com/raulmur/ORB_SLAM2](https://github.com/raulmur/ORB_SLAM2)】**
非常经典的 单目/双目/RGBD-slam 算法库
- orb-slam3【2.5k stars】【GPLv3 license】【[https://github.com/UZ-SLAMLab/ORB_SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3)】
第一个能够用单目、立体和RGB-D相机,使用针孔和鱼眼镜头模型进行视觉、视觉惯性和多地图SLAM的系统。
	#### 单目 slam
	- **orb-slam【1.1k stars】【GPLv3 license】【[https://github.com/raulmur/ORB_SLAM](https://github.com/raulmur/ORB_SLAM)】**
	非常经典的单目slam算法库
	#### RGBD slam
	- **KinectFusion【280+ stars】【MIT License】【[https://github.com/chrdiller/KinectFusionLib](https://github.com/chrdiller/KinectFusionLib)】**
	基于KinectFusion论文实现的一个开源算法，paper：KinectFusion: Real-time dense surface mapping and tracking
	- **InfiniTAM∞ v3【680+ stars】【Oxford University Innovation Academic License】【[https://github.com/victorprad/InfiniTAM](https://github.com/victorprad/InfiniTAM)】**
	牛津大学团队做的开源多平台实时大尺度深度融合和跟踪，速度很快，在Windows、Linux、Ios、Android上都可以编译运行，而且速度都还可以。
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021052723092847.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
	- **VoxelHashing【460+ stars】【Creative Commons Attribution-NonCommercial-ShareAlike 3.0 License】【[https://github.com/niessner/VoxelHashing](https://github.com/niessner/VoxelHashing)】**
	基于TSDF体素融合的经典深度融合算法，有CUDA版本，速度很快。
	- **ElasticFusion【1.3k stars】【non-commercial use only】【[https://github.com/mp3guy/ElasticFusion](https://github.com/mp3guy/ElasticFusion)】**
	一个用于RGBD数据的基于Surfel的Fusion算法。适用于室内重建。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527101609923.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
	- **ElasticReconstruction【480+ stars】【MIT license】【[https://github.com/qianyizh/ElasticReconstruction](https://github.com/qianyizh/ElasticReconstruction)】**
	一个用于RGBD数据的基于Voxel的Fusion算法。适用于室内重建。
	![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527232136452.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)

	- **BundleFusion【1k stars】【non-commercial applications】【[https://github.com/niessner/BundleFusion]**(https://github.com/niessner/BundleFusion)】
	一个实时的全局一致的三维重建算法库，基于TSDF，效果是目前Fusion中最好的。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527101706588.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
	- **badslam【400+ stars】【BSD-3-Clause License】【CVPR2019】【[https://github.com/ETH3D/badslam](https://github.com/ETH3D/badslam)】**
	一个基于RGBD数据的实时直接法BA-SLAM算法，适合室外重建，来自苏黎世联邦理工学院（ETH）团队。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210523151446161.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
	- **tsdf-fusion 【400+ stars】 【BSD-2-Clause License】【[https://github.com/andyzeng/tsdf-fusion](https://github.com/andyzeng/tsdf-fusion)】**
	一个将多个已配准的深度图融合为TSDF体素的算法，TSDF体素可以用于Marching Cubes网格构建
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527095350635.png)
## 特征匹配
- **CudaSift【570+ stars】【non-commercial】【[https://github.com/Celebrandil/CudaSift](https://github.com/Celebrandil/CudaSift)】**
一个CUDA实现的快速SIFT算法，SIFT是经典的尺度不变性特征匹配算法
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527102714228.png)
## 立体匹配
- **SemiglobalMatching（SGM）【400+ stars】【MIT License】【[https://github.com/ethan-li-coding/SemiGlobalMatching](https://github.com/ethan-li-coding/SemiGlobalMatching)】**
经典半全局立体匹配算法SGM算法库。效率高适应性强。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527093929761.png)
- **PatchMatchStereo【250+ stars】【MIT License】【[https://github.com/ethan-li-coding/PatchMatchStereo](https://github.com/ethan-li-coding/PatchMatchStereo)】**
经典倾斜平面立体匹配算法库PatchMatch。效果很棒！
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527093911556.png)
-**AD-Cense 【160+ stars】【MIT License】【[https://github.com/ethan-li-coding/AD-Census](https://github.com/ethan-li-coding/AD-Census)】**
经典AD-Census立体匹配算法，效率高，效果好。Intel RealSense D400 Stereo模块算法。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527093850854.png)
## 点云拼接
 - **ICPCUDA【400+ stars】【No License】【[https://github.com/mp3guy/ICPCUDA](https://github.com/mp3guy/ICPCUDA)】**
 一个基于深度图数据（DepthMap）的快速ICP拼接库（CUDA加速），对于VGA尺寸（640x480），在NVIDIA GeForce GTX TITAN X上可达750Hz的速度。作者同时开源了[KinectFusion](https://github.com/mp3guy/ElasticFusion)。
 - **CUDA-ScanMatcher-ICP [100+ stars] [MIT License]【  [https://github.com/botforge/CUDA-ScanMatcher-ICP](https://github.com/botforge/CUDA-ScanMatcher-ICP)】**
  一个基于CUDA的ICP点云拼接算法，适用于激光扫描点云和一般点云。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527095433689.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
- **Super4PCS【300+ stars】【Apache License V2】【[https://github.com/nmellado/Super4PCS](https://github.com/nmellado/Super4PCS)】**
点云粗匹配算法Super4PCS的实现。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527232502495.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
## 网格构建
- **PoissonRecon 【700+ stars】【MIT License】【[https://github.com/mkazhdan/PoissonRecon](https://github.com/mkazhdan/PoissonRecon)】**
泊松重建，一个网格构建算法，输入是带法线的无序点云。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527103440884.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
## 网格处理
- **OpenMesh【BSD 3 clause license】【[https://www.graphics.rwth-aachen.de/software/openmesh/](https://www.graphics.rwth-aachen.de/software/openmesh/)】**
非常经典的一个网格处理库，基于半边数据结构，效率很高，且非常稳定，有很多基础网格算法的实现。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527233028820.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
- **vcglib【560+ stars】【GPLv3.0 License】【[http://vcg.isti.cnr.it/vcglib/](http://vcg.isti.cnr.it/vcglib/)】**
和OpenMesh一样的网格处理基础算法库，也很高效和稳定，比较有名的网格处理软件MeshLib就是用的它。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527233556459.png)
## 点云渲染
- **potree 【2.3k stars】【FreeBSD Licnese】【[https://github.com/potree/potree](https://github.com/potree/potree)】**
一个基于WebGL的大型点云渲染工程，很有意思。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527095334910.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
- **OpenSceneGraph（OSG）【2.2k stars】【 OpenSceneGraph Public License】【[https://github.com/openscenegraph/OpenSceneGraph](https://github.com/openscenegraph/OpenSceneGraph)】**
一个非常成熟好用的跨平台三维数据渲染库，渲染包括点云、网格、纹理模型在内的三维数据，适合在大型软件里作为渲染引擎，还可以处理LOD数据。
