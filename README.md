# Awesome-Object-Tracking [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
This is a collection of people, papers, blogs, etc. related to object tracking.


# People & Lab

- [Haibin Ling (凌海滨)](http://www.dabi.temple.edu/~hbling/), Temple University
- [Tianzhu Zhang（张天柱）](http://nlpr-web.ia.ac.cn/mmc/homepage/tzzhang/index.html)，中科院自动化所
- [Huchuan Lu (卢湖川)](http://ice.dlut.edu.cn/lu/),大连理工大学
- [WU Yi (吴毅)](https://sites.google.com/site/wuyi2018/),南京信息科技大学
- [Martin Danelljan](http://users.isy.liu.se/cvl/marda26/)
- [Luca Bertinetto](http://www.robots.ox.ac.uk/~luca/index.html)

# Paper

## ICCV 2017
- Parallel Tracking and Verifying: A Framework for Real-Time and High Accuracy Visual Tracking.
  - Heng Fan and Haibin Ling. IEEE International Conference on Computer Vision (ICCV), 2017.
  - [[Paper](http://www.dabi.temple.edu/~hbling/code/PTAV/PTAV_ICCV17.pdf)][[Supplementary Material](http://www.dabi.temple.edu/~hbling/code/PTAV/PTAV_ICCV17_Supp.pdf)][[C++ Parallel Code](http://www.dabi.temple.edu/~hbling/code/PTAV/parallel_ptav_v1.zip)][[Matlab Serial Code (including siamese caffe model, ~800M)](http://www.dabi.temple.edu/~hbling/code/PTAV/serial_ptav_v1.zip)][[Tracking Results](http://www.dabi.temple.edu/~hbling/code/PTAV/ptavresults.zip)]


- Convolutional Residual Learning for Visual Tracking
  - Yibing Song, Chao Ma, Lijun Gong, Jiawei Zhang, Rynson Lau and Ming-Hsuan Yang
  - [[project]](https://www.cs.cityu.edu.hk/%7Eyibisong/iccv17/index.html)

- Need for Speed: A Benchmark for Higher Frame Rate Object Tracking
  - Hamed Kiani, Ashton Fagg, Chen Huang, Deva Ramanan, and Simon Lucey
  - [[Paper]](http://www.hamedkiani.com/uploads/5/1/8/8/51882963/435.pdf) [[Sup. Material]](http://www.hamedkiani.com/uploads/5/1/8/8/51882963/435_sup.pdf) [[Project page]](http://ci2cv.net/nfs/index.html)

- Learning Background-Aware Correlation Filters for Visual Tracking
  - Hamed Kiani, Ashton Fagg, and  Simon Lucey
  - [[Paper] ](http://www.hamedkiani.com/uploads/5/1/8/8/51882963/436.pdf) [[Sup. Material]](http://www.hamedkiani.com/uploads/5/1/8/8/51882963/436_sup.pdf)  [[Project Page]](http://www.hamedkiani.com/bacf.html)

- **p-tracker:** Tracking as Online Decision-Making: Learning a Policy From Streaming Videos With Reinforcement Learning
  - J. Supancic, D. Ramanan
  - [[paper]](https://arxiv.org/abs/1707.04991) [[supp](http://openaccess.thecvf.com/content_ICCV_2017/supplemental/Supancic_Tracking_as_Online_ICCV_2017_supplemental.pdf)]



## CVPR 2017
- Context-Aware Correlation Filter Tracking. (Oral)
  - Matthias Mueller, Neil Smith, Bernard Ghanem.
  -  [[paper](http://link.zhihu.com/?target=https%3A//ivul.kaust.edu.sa/Documents/Publications/2017/Context-Aware%2520Correlation%2520Filter%2520Tracking.pdf)][[project](http://link.zhihu.com/?target=https%3A//ivul.kaust.edu.sa/Pages/pub-ca-cf-tracking.aspx)][[github](github.com/thias15/Context-Aware-CF-Tracking)]

- ECO: Efficient Convolution Operators for Tracking
  - Martin Danelljan, Goutam Bhat, Fahad Shahbaz Khan, Michael Felsberg
  - [[paper]](http://arxiv.org/pdf/1611.09224.pdf)[[project]](www.cvl.isy.liu.se/research/objrec/visualtracking/ecotrack/index.html)[[github]](http://github.com/martin-danelljan/ECO)

- Discriminative Correlation Filter with Channel and Spatial Reliability
  - Alan Lukežič, Tomáš Vojíř, Luka Čehovin, Jiří Matas, Matej Kristan
  - [[paper]](http://arxiv.org/pdf/1611.08461v1.pdf)[[github]](https://github.com/alanlukezic/csr-dcf)

- Large Margin Object Tracking with Circulant Feature Maps
  - Mengmeng Wang, Yong Liu, Zeyi Huang
  - [[paper]](http://arxiv.org/pdf/1703.05020.pdf)[[zhihu]](https://zhuanlan.zhihu.com/p/25761718)

- Multi-task Correlation Particle Filter for Robust Visual Tracking
  - Tianzhu Zhang, Changsheng Xu, Ming-Hsuan Yang
  - [[paper]](http://link.zhihu.com/?target=http%3A//nlpr-web.ia.ac.cn/mmc/homepage/tzzhang/Project_Tianzhu/zhang_mcpf/CVPR2017/1758.pdf)[[project]](http://nlpr-web.ia.ac.cn/mmc/homepage/tzzhang/mcpf.html)

- End-to-end representation learning for Correlation Filter based tracking
  - Jack Valmadre, Luca Bertinetto, João F. Henriques, Andrea Vedaldi, Philip H. S. Torr
  - [[paper]](http://arxiv.org/pdf/1704.06036v1.pdf)][[project]](http://www.robots.ox.ac.uk/%7Eluca/cfnet.html)[[github]](http://github.com/bertinetto/cfnet)

- Attentional Correlation Filter Network for Adaptive Visual Tracking
  - Jongwon Choi, Hyung Jin Chang, Sangdoo Yun, Tobias Fischer, Yiannis Demiris, and Jin Young Choi
  - [[paper]](http://.google.com/file/d/0B0ZkG8zaRQoLUHdlTGNtUWFjd1E/view)][[project]](http://sites.google.com/site/jwchoivision/home/acfn-1)[[test code]](http://drive.google.com/file/d/0B0ZkG8zaRQoLQUswbW9qSWFaU0U/view%3Fusp%3Ddrive_web)[[training code]](http://drive.google.com/file/d/0B0ZkG8zaRQoLZVVranBnbHlydnM/view%3Fusp%3Ddrive_web)


## CVPR 2016
- MDNet: Learning Multi-Domain Convolutional Neural Networks for Visual Tracking
  - Hyeonseob Nam, and Bohyung Han
  - [[Paper]](https://arxiv.org/abs/1510.07945)[[Project]](http://cvlab.postech.ac.kr/research/mdnet/)[[github]](https://github.com/HyeonseobNam/py-MDNet)

- Staple: Complementary Learners for Real-Time Tracking
  - Luca Bertinetto, Jack Valmadre, Stuart Golodetz, Ondrej Miksik, Philip H. S. Torr
  - [[paper]](http://arxiv.org/abs/1512.01355)[[poster]](http://www.robots.ox.ac.uk/~luca/stuff/poster_staple.pdf)[[github]](https://github.com/bertinetto/staple)[[result]](http://www.robots.ox.ac.uk/~luca/stuff/staple_results/all.zip)

- SINT: Siamese Instance Search for Tracking
  - Ran Tao, Efstratios Gavves, and Arnold W.M. Smeulders
  - [[paper]](https://staff.science.uva.nl/r.tao/pub/TaoCVPR2016.pdf)[[project]](https://staff.fnwi.uva.nl/r.tao/projects/SINT/SINT_proj.html)[[github]](https://github.com/taotaoorange/SINT)

- **STCT:** STCT: Sequentially Training Convolutional Networks for Visual Tracking
  - Wang, Lijun and Ouyang, Wanli and Wang, Xiaogang and Lu, Huchuan
  - [[paper](http://www.ee.cuhk.edu.hk/~wlouyang/Papers/WangLJ_CVPR16.pdf)][[github](https://github.com/scott89/STCT)]

## ECCV 2016

- Fully-Convolutional Siamese Networks for Object Tracking
  - [[paper]](http://arxiv.org/abs/1606.09549)[[github]](https://github.com/bertinetto/siamese-fc)[[project]](http://www.robots.ox.ac.uk/%7Eluca/siamese-fc.html)

- **SiameseFC:** Fully-Convolutional Siamese Networks for Object Tracking (workshop)
  - Luca Bertinetto, Jack Valmadre, João F. Henriques, Andrea Vedaldi, Philip H.S. Torr
  - [[paper](http://120.52.73.78/arxiv.org/pdf/1606.09549v2.pdf)][[project](http://www.robots.ox.ac.uk/~luca/siamese-fc.html)][[github](https://github.com/bertinetto/siamese-fc)]

- **GOTURN:** Learning to Track at 100 FPS with Deep Regression Networks
  - David Held, Sebastian Thrun, Silvio Savarese
  - [[paper](http://davheld.github.io/GOTURN/GOTURN.pdf)][[project](http://davheld.github.io/GOTURN/GOTURN.html)][[github](https://github.com/davheld/GOTURN)]

- **C-COT:** Beyond Correlation Filters: Learning Continuous Convolution Operators for Visual Tracking
  - Martin Danelljan, Andreas Robinson, Fahad Khan, Michael Felsberg
  - [[paper](http://www.cvl.isy.liu.se/research/objrec/visualtracking/conttrack/C-COT_ECCV16.pdf)][[project](http://www.cvl.isy.liu.se/research/objrec/visualtracking/conttrack/index.html)][[github](https://github.com/martin-danelljan/Continuous-ConvOp)]



## ICCV 2015

- **SRDCF:** Learning Spatially Regularized Correlation Filters for Visual Tracking
  - Martin Danelljan, Gustav Häger, Fahad Khan, Michael Felsberg
  - [[paper](https://www.cvl.isy.liu.se/research/objrec/visualtracking/regvistrack/SRDCF_ICCV15.pdf)][[project](https://www.cvl.isy.liu.se/research/objrec/visualtracking/regvistrack/)]

- **DeepSRDCF:** Convolutional Features for Correlation Filter Based Visual Tracking (workshop)
  - Martin Danelljan, Gustav Häger, Fahad Khan, Michael Felsberg
  - [[paper](https://www.cvl.isy.liu.se/research/objrec/visualtracking/regvistrack/ConvDCF_ICCV15_VOTworkshop.pdf)][[project](https://www.cvl.isy.liu.se/research/objrec/visualtracking/regvistrack/)]

- **CF2:** Hierarchical Convolutional Features for Visual Tracking
  - Chao Ma, Jia-Bin Huang, Xiaokang Yang and Ming-Hsuan Yang
  - [[paper](http://faculty.ucmerced.edu/mhyang/papers/iccv15_tracking.pdf)][[project](https://sites.google.com/site/jbhuang0604/publications/cf2)][[github](https://github.com/jbhuang0604/CF2)]

- Understanding and Diagnosing Visual Tracking Systems
  - Naiyan Wang, Jianping Shi, Dit-Yan Yeung and Jiaya Jia
  - [[paper](http://winsty.net/papers/diagnose.pdf)][[project](http://winsty.net/tracker_diagnose.html)][[code](http://winsty.net/diagnose/diagnose_code.zip)]

- **FCNT:** Visual Tracking with Fully Convolutional Networks
  - Lijun Wang, Wanli Ouyang, Xiaogang Wang, and Huchuan Lu
  - [[paper](http://202.118.75.4/lu/Paper/ICCV2015/iccv15_lijun.pdf)][[project](http://scott89.github.io/FCNT/)][[github](https://github.com/scott89/FCNT)]

## CVPR 2015

- **MUSTer:** MUlti-Store Tracker (MUSTer): A Cognitive Psychology Inspired Approach to Object Tracking
  - Zhibin Hong, Zhe Chen, Chaohui Wang, Xue Mei, Danil Prokhorov, Dacheng Tao
  - [[paper](http://openaccess.thecvf.com/content_cvpr_2015/papers/Hong_MUlti-Store_Tracker_MUSTer_2015_CVPR_paper.pdf)][[project](https://sites.google.com/site/multistoretrackermuster/)]

- **LCT:** Long-term Correlation Tracking
  - Chao Ma, Xiaokang Yang, Chongyang Zhang, Ming-Hsuan Yang
  -   [[paper](http://openaccess.thecvf.com/content_cvpr_2015/papers/Ma_Long-Term_Correlation_Tracking_2015_CVPR_paper.pdf)][[project](https://sites.google.com/site/chaoma99/cvpr15_tracking)][[github](https://github.com/chaoma99/lct-tracker)]

- **DAT:** In Defense of Color-based Model-free Tracking
  - Horst Possegger, Thomas Mauthner, and Horst Bischof
  - [[paper](https://lrs.icg.tugraz.at/pubs/possegger_cvpr15.pdf)]
  [[project](https://www.tugraz.at/institute/icg/research/team-bischof/lrs/downloads/dat)]
  [[code](https://lrs.icg.tugraz.at/downloads/dat-v1.0.zip)]

- **RPT:** Reliable Patch Trackers: Robust Visual Tracking by Exploiting Reliable Patches
  - Yang Li, Jianke Zhu and Steven C.H. Hoi
  - [[paper](https://github.com/ihpdep/ihpdep.github.io/raw/master/papers/cvpr15_rpt.pdf)][[github](https://github.com/ihpdep/rpt)]

# Awesome blogs and websites

## Zhihu Articles
- [CVPR2017跟踪相关文章介绍](https://zhuanlan.zhihu.com/p/27335895)
- [目标跟踪综述](https://www.jiqizhixin.com/articles/2017-05-14)

## GitHub [:octocat:](https://github.com/sdsy888/Awesome-Object-Tracking/tree/master)
[Collection of recent bench  trackers](https://github.com/foolwood/benchmark_results)

To be continued...
