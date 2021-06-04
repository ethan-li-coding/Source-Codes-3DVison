# Source-Codes-3DVison
Source codes collection for 3d vision 视觉三维重建领域的源码收集

三维重建开源代码汇总，不定期更新。

[1 SFM](#sfm)<br>
[2 MVS](#mvs)<br>
[3 SLAM](#slam)<br>
[4 特征匹配](#特征匹配)<br>
[5 立体匹配](#立体匹配)<br>
[6 点云拼接](#点云拼接)<br>
[7 网格构建](#网格构建)<br>
[8 点云网格处理](#点云网格处理)<br>
[9 纹理映射](#纹理映射)<br>
[10 点云渲染](#点云渲染)<br>

## SFM
- **openmvg【3.5k stars】【Mozilla Public License Version 2.0】【[https://github.com/openMVG/openMVG](https://github.com/openMVG/openMVG)】**<br>
一个多视几何三维重建算法库，从无序二维影像集恢复相机的三维位姿。SFM（Structure From Motion）经典算法库。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527092742723.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)

- **colmap【3k stars】【new BSD license】【[https://github.com/colmap/colmap](https://github.com/colmap/colmap)】**<br>
一个多视几何三维重建算法库，从无序二维影像集恢复相机的三维位姿（SFM）以及多视立体重建（MVS）。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527092509685.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
- **alicevision【1.8k stars】【MPL2 license】【[https://github.com/alicevision/AliceVision](https://github.com/alicevision/AliceVision)】**<br>
一个开源的摄影测量系统框架。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527092356416.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
## MVS
- **openmvs【1.6k stars】【AGPLv3】【[https://github.com/cdcseacave/openMVS](https://github.com/cdcseacave/openMVS)】**<br>
一个多视立体重建开源算法库，基于带有位姿信息的图像集，重建高质量的纹理模型，效果非常出色。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527225531907.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
- **meshroom【6.5k stars】【MPL2 license】【[https://github.com/alicevision/meshroom](https://github.com/alicevision/meshroom)】**<br>
和OpenMVS库一样，也是基于带有位姿信息的图像集，重建高质量的纹理模型，但是效果没有OpenMVS好，速度更快些。带有图形界面，做的很漂亮。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527230158531.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
## SLAM
### VSLAM
- **orb-slam2【6.2k stars】【GPLv3 license】【[https://github.com/raulmur/ORB_SLAM2](https://github.com/raulmur/ORB_SLAM2)】**<br>
非常经典的 单目/双目/RGBD-slam 算法库<br>
- **orb-slam3【2.5k stars】【GPLv3 license】【[https://github.com/UZ-SLAMLab/ORB_SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3)】**<br>
第一个能够用单目、立体和RGB-D相机,使用针孔和鱼眼镜头模型进行视觉、视觉惯性和多地图SLAM的系统。<br>
	#### 单目 slam
	- **orb-slam【1.1k stars】【GPLv3 license】【[https://github.com/raulmur/ORB_SLAM](https://github.com/raulmur/ORB_SLAM)】**<br>
	非常经典的单目slam算法库<br>
	#### RGBD slam
	- **KinectFusion【280+ stars】【MIT License】【[https://github.com/chrdiller/KinectFusionLib](https://github.com/chrdiller/KinectFusionLib)】**<br>
	基于KinectFusion论文实现的一个开源算法，paper：KinectFusion: Real-time dense surface mapping and tracking<br>
	- **InfiniTAM∞ v3【680+ stars】【Oxford University Innovation Academic License】【[https://github.com/victorprad/InfiniTAM](https://github.com/victorprad/InfiniTAM)】**<br>
	牛津大学团队做的开源多平台实时大尺度深度融合和跟踪，速度很快，在Windows、Linux、Ios、Android上都可以编译运行，而且速度都还可以。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021052723092847.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
	- **VoxelHashing【460+ stars】【Creative Commons Attribution-NonCommercial-ShareAlike 3.0 License】【[https://github.com/niessner/VoxelHashing](https://github.com/niessner/VoxelHashing)】**<br>
	基于TSDF体素融合的经典深度融合算法，有CUDA版本，速度很快。<br>
	- **ElasticFusion【1.3k stars】【non-commercial use only】【[https://github.com/mp3guy/ElasticFusion](https://github.com/mp3guy/ElasticFusion)】**<br>
	一个用于RGBD数据的基于Surfel的Fusion算法。适用于室内重建。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527101609923.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
	- **ElasticReconstruction【480+ stars】【MIT license】【[https://github.com/qianyizh/ElasticReconstruction](https://github.com/qianyizh/ElasticReconstruction)】**<br>
	一个用于RGBD数据的基于Voxel的Fusion算法。适用于室内重建。<br>
	![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527232136452.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)

	- **BundleFusion【1k stars】【non-commercial applications】【[https://github.com/niessner/BundleFusion](https://github.com/niessner/BundleFusion)】**<br>
	一个实时的全局一致的三维重建算法库，基于TSDF，效果是目前Fusion中最好的。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527101706588.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
	- **badslam【400+ stars】【BSD-3-Clause License】【CVPR2019】【[https://github.com/ETH3D/badslam](https://github.com/ETH3D/badslam)】**<br>
	一个基于RGBD数据的实时直接法BA-SLAM算法，适合室外重建，来自苏黎世联邦理工学院（ETH）团队。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210523151446161.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
	- **tsdf-fusion 【400+ stars】 【BSD-2-Clause License】【[https://github.com/andyzeng/tsdf-fusion](https://github.com/andyzeng/tsdf-fusion)】**<br>
	一个将多个已配准的深度图融合为TSDF体素的算法，TSDF体素可以用于Marching Cubes网格构建<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527095350635.png)
## 特征匹配
- **CudaSift【570+ stars】【non-commercial】【[https://github.com/Celebrandil/CudaSift](https://github.com/Celebrandil/CudaSift)】**<br>
一个CUDA实现的快速SIFT算法，SIFT是经典的尺度不变性特征匹配算法<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527102714228.png)
## 立体匹配
- **SemiglobalMatching（SGM）【400+ stars】【MIT License】【[https://github.com/ethan-li-coding/SemiGlobalMatching](https://github.com/ethan-li-coding/SemiGlobalMatching)】**<br>
经典半全局立体匹配算法SGM算法库。效率高适应性强。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527093929761.png)
- **PatchMatchStereo【250+ stars】【MIT License】【[https://github.com/ethan-li-coding/PatchMatchStereo](https://github.com/ethan-li-coding/PatchMatchStereo)】**<br>
经典倾斜平面立体匹配算法库PatchMatch。效果很棒！<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527093911556.png)
-**AD-Cense 【160+ stars】【MIT License】【[https://github.com/ethan-li-coding/AD-Census](https://github.com/ethan-li-coding/AD-Census)】**<br>
经典AD-Census立体匹配算法，效率高，效果好。Intel RealSense D400 Stereo模块算法。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527093850854.png)
## 点云拼接
 - **ICPCUDA【400+ stars】【No License】【[https://github.com/mp3guy/ICPCUDA](https://github.com/mp3guy/ICPCUDA)】**<br>
 一个基于深度图数据（DepthMap）的快速ICP拼接库（CUDA加速），对于VGA尺寸（640x480），在NVIDIA GeForce GTX TITAN X上可达750Hz的速度。作者同时开源了[KinectFusion](https://github.com/mp3guy/ElasticFusion)。<br>
 - **CUDA-ScanMatcher-ICP [100+ stars] [MIT License]【  [https://github.com/botforge/CUDA-ScanMatcher-ICP](https://github.com/botforge/CUDA-ScanMatcher-ICP)】**<br>
  一个基于CUDA的ICP点云拼接算法，适用于激光扫描点云和一般点云。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527095433689.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
- **Super4PCS【300+ stars】【Apache License V2】【[https://github.com/nmellado/Super4PCS](https://github.com/nmellado/Super4PCS)】**<br>
点云粗匹配算法Super4PCS的实现。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527232502495.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
## 网格构建
- **PoissonRecon 【700+ stars】【MIT License】【[https://github.com/mkazhdan/PoissonRecon](https://github.com/mkazhdan/PoissonRecon)】**<br>
泊松重建，一个网格构建算法，输入是带法线的无序点云。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527103440884.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
## 点云网格处理
- **pcl【6.3k stars】【BSD License】【[https://github.com/PointCloudLibrary/pcl](https://github.com/PointCloudLibrary/pcl)】**<br>
这大概是使用最广泛的点云处理算法库，你可以用它来显示图片、显示点云，它还实现了非常多的点云处理算法，如点云滤波、点云配准、点云分割等，它的官方网站是[https://pointclouds.org/](https://pointclouds.org/)。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210604092243655.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
- **OpenMesh【BSD 3 clause license】【[https://www.graphics.rwth-aachen.de/software/openmesh/](https://www.graphics.rwth-aachen.de/software/openmesh/)】**<br>
非常经典的一个网格处理库，基于半边数据结构，效率很高，且非常稳定，有很多基础网格算法的实现。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527233028820.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
- **vcglib【560+ stars】【GPLv3.0 License】【[http://vcg.isti.cnr.it/vcglib/](http://vcg.isti.cnr.it/vcglib/)】**<br>
和OpenMesh一样的网格处理基础算法库，也很高效和稳定，比较有名的网格处理软件MeshLib就是用的它。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527233556459.png)
## 纹理映射
- **mvs-texturing【500+ stars】【BSD 3-Clause License】【[https://github.com/nmoehrle/mvs-texturing](https://github.com/nmoehrle/mvs-texturing)】**<br>
一个用于多视立体重建的纹理映射算法库，OpenMVS、MVE都是使用这个算法来做纹理映射。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210604091307842.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
- **UVAtlas【500+ stars】【MIT License】【[https://github.com/microsoft/UVAtlas](https://github.com/microsoft/UVAtlas)】**<br>
微软开源的一个自动UV展开算法，UV展开可以用于将网格映射到一张二维UV图上，网格映射的纹理就可以用一张UV图来组织，提高纹理图的利用率。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210604091745365.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)

## 点云渲染
- **potree 【2.3k stars】【FreeBSD Licnese】【[https://github.com/potree/potree](https://github.com/potree/potree)】**<br>
一个基于WebGL的大型点云渲染工程，很有意思。<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210527095334910.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3JzX2x5cw==,size_16,color_FFFFFF,t_70)
- **OpenSceneGraph（OSG）【2.2k stars】【 OpenSceneGraph Public License】【[https://github.com/openscenegraph/OpenSceneGraph](https://github.com/openscenegraph/OpenSceneGraph)】**<br>
一个非常成熟好用的跨平台三维数据渲染库，渲染包括点云、网格、纹理模型在内的三维数据，适合在大型软件里作为渲染引擎，还可以处理LOD数据。<br>
- **Pangolin【1.3k stars】【MIT License】【[https://github.com/stevenlovegrove/Pangolin](https://github.com/stevenlovegrove/Pangolin)】**<br>
一个轻量级的跨平台三维渲染库，可用于slam相关项目的渲染引擎。<br>
