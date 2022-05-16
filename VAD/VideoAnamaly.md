# Video Anomalies 

## Review : Representation learning for VAD 
[https://www.mdpi.com/2313-433X/4/2/36 MDPI 2018 pdf] : An overview of representation learning methods for unsupervised and semi-supervised anomaly detection in videos, 
B Ravi Kiran, Dilip Mathew Thomas, and Ranjith Parakkal, UncannyVision. 


## Representation learning for reconstruction
**Family of methods** : Principal component analysis (PCA), Auto-Encoders (AEs, CAEs, Contractive AEs, Stacked AEs, Denoising AEs), Restricted Boltzman Machines (RBMs).
- Learning Temporal Regularity in Video CVPR 2016 [https://arxiv.org/pdf/1604.04574.pdf pdf]
- Energy-based Models for Video Anomaly Detection PAKDD 2017 [https://arxiv.org/pdf/1708.05211.pdf pdf]
- Abnormal Event Detection in Videos using Spatiotemporal Autoencoder [https://arxiv.org/pdf/1701.01546.pdf pdf]
- Anomaly Detection with Robust Deep Auto-encoders KDD 2017 [http://www.kdd.org/kdd2017/papers/view/anomaly-detection-with-robust-deep-auto-encoders pdf]
- Robust, Deep and Inductive Anomaly Detection, Robust Convolutional AE (RCVAE) 2017 [https://arxiv.org/pdf/1704.06743.pdf pdf]
- Outlier Detection Using Replicator Neural Networks 2002 [http://ai2-s2-pdfs.s3.amazonaws.com/87a0/9c777dcecab4883e328669ef2af1ba8dd7be.pdf pdf]

~~~
{}{img_left}{../images/Models_VAD.png}{Models}{550}{250}
~~~

**Related Work** : 
- Contractive Auto-Encoders 
[http://www.iro.umontreal.ca/~lisa/pointeurs/ICML2011_explicit_invariance.pdf pdf], 
[http://techtalks.tv/talks/a-generative-process-for-contractive-auto-encoders/57301/ talk], 
- C3D [http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Tran_Learning_Spatiotemporal_Features_ICCV_2015_paper.pdf pdf], '
- NADE [http://proceedings.mlr.press/v15/larochelle11a/larochelle11a.pdf pdf], 
- MADE [https://arxiv.org/pdf/1502.03509v2.pdf pdf], 
- Deep AutoRegressive Networks 2014 [https://arxiv.org/pdf/1310.8499.pdf pdf] 

## Predictive modeling : Video as temporal patterns 
**Family of methods** : Linear Models, Convolutional LSTMs, CNN-LSTMs : 
- Anomaly Detection in Video Using Predictive Convolutional LSTM Networks Dec 2016 [https://arxiv.org/pdf/1612.00390.pdf pdf]
- DeepAnomaly: Combining BG Sub. & Deep Learning for Anomalies 2016 [http://www.mdpi.com/1424-8220/16/11/1904 pdf]
- Video anomaly detection using deep incremental slow feature analysis network [http://ieeexplore.ieee.org/document/7503634/ link]

~~~
{}{img_left}{images/ConvLSTM.png}{ConvLSTM}{550}{325}
~~~

**Related Work**
- Adversarial LSTM Networks [http://web.engr.oregonstate.edu/~sinisa/research/publications/cvpr17_summarization.pdf CVPR 2017], 
- Video Representations using LSTMs : [https://arxiv.org/pdf/1502.04681.pdf pdf] 
[https://www.slideshare.net/JunhoCho1/161209-unsupervised-learning-of-video-representations-using-lstms Slides], 
- Deep multi-scale video prediction [https://arxiv.org/pdf/1511.05440.pdf pdf], 
- ST-video autoencoder with differentiable memory [https://arxiv.org/pdf/1511.06309.pdf pdf], 
[https://www.robots.ox.ac.uk/seminars/Extra/2016_07_25_VioricaPatraucean.pdf Slides], 
- CortexNet: Robust Visual Temporal Representations [https://arxiv.org/pdf/1706.02735.pdf pdf] 
- PredNet: Deep Predictive Coding Networks [https://cbmm.mit.edu/sites/default/files/publications/CBMM-Memo-064.pdf pdf], 
[https://coxlab.github.io/prednet/ project], 
- Video prediction papers : 
[https://arxiv.org/abs/1504.08023 pdf], [http://ai.stanford.edu/~dahuang/papers/iccv17-vfid.pdf pdf], 
[http://carlvondrick.com/transformer.pdf pdf], IncSFA [https://arxiv.org/pdf/1112.2113.pdf pdf].

## Generative Models 
**Family of methods** : Variational Autoencoders(VAEs), Generative Adversarial Networks(GANs), Adversarial Auto-Encoders(AAEs)
- Variational Autoencoder based Anomaly Detection using Reconstruction Probability TR2015 
[http://dm.snu.ac.kr/static/docs/TR/SNUDM-TR-2015-03.pdf pdf] 
- Training Adversarial Discriminators for Cross-channel Abnormal Events Jun 2017
[https://arxiv.org/pdf/1706.07680.pdf pdf] 
- Adversarial Autoencoders for Anomalous Event Detection in Images [https://scholarworks.iupui.edu/handle/1805/12352 Thesis]
- Unsupervised Anomaly Detection with GANs to Guide Marker Discovery 
[https://arxiv.org/pdf/1703.05921.pdf pdf] 

~~~
{}{img_left}{images/CrossChan_GAN.png}{CrossChan_GAN}{550}{325}
~~~

**Related Work**
- VAE: Auto-Encoding Variational Bayes  [https://arxiv.org/pdf/1312.6114.pdf pdf],[https://arxiv.org/pdf/1606.05908.pdf Tut], 
- Split-Brain Autoencoders [https://arxiv.org/pdf/1611.09842.pdf CVPR2017], 
- GANs [https://arxiv.org/abs/1406.2661 pdf][https://www.youtube.com/watch?v=RvgYvHyT15E NIPS Workshop], 
- BiGAN [https://arxiv.org/pdf/1605.09782.pdf pdf], Adversarial Autoencoders (AAEs) [https://arxiv.org/pdf/1511.05644.pdf pdf], 
- InfoGAN [https://arxiv.org/pdf/1606.03657v1.pdf pdf], McGan [https://arxiv.org/pdf/1702.08398.pdf pdf]
- Recursive estimation of generative video models [https://pdfs.semanticscholar.org/d156/e74448a71e70ac73222167117a90e2ab93ef.pdf pdf]

**Other models**
- Spatio-Temporal Multiresolution Model for VAD [https://arxiv.org/pdf/1401.3291.pdf pdf], [https://pdfs.semanticscholar.org/c6b3/edc63af38d7fe489474752d28ccee29ff8b1.pdf Thesis], 
- Temporal Multi-Scale Models for Flow and Acceleration [http://www.umiacs.umd.edu/~yaser/cvpr97_OF.pdf pdf]

**Established Arch. for unsupervised video tasks**
- Early, Late, Slow Fusion [https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/42455.pdf pdf],  
- Two-Stream CNNs   [https://arxiv.org/pdf/1406.2199.pdf pdf],
- Disentangled Representations from Video [https://sites.google.com/view/drnet-paper DRnet],
- Video and unsupervised Learning [https://www.youtube.com/watch?v=ekyBklxwQMU CS231],
[http://cs231n.stanford.edu/slides/2016/winter1516_lecture14.pdf Slides],
- Activity Recognition and Unsupervised Learning [https://comp150dl.github.io/lectures/lecture12.pdf slides]


**Video anomaly detection evaluation** : 
ROC Curves and EER [https://www.cs.ubc.ca/~murphyk/Teaching/CS340-Fall07/ROC.pdf pdf], 
[https://link.springer.com/chapter/10.1007/978-1-84996-202-5_5 link]

**Other Applications**: 
Detecting Events by Density Ratio Estimation 
[http://www.ri.cmu.edu/pub_files/2012/10/paper_id_337.pdf pdf], Video Behavior Profiling for AD 
[http://www.eecs.qmul.ac.uk/~sgg/papers/XiangGong_PAMI08.pdf pdf] 


**Video Anomlay Detection Datasets**:
- UCSD Ped : [http://www.svcl.ucsd.edu/projects/anomaly/dataset.htm link], 
- CUHK-Avenue Dataset [http://www.cse.cuhk.edu.hk/leojia/projects/detectabnormal/dataset.html link]
- Subway Entry & exit [http://www.cim.mcgill.ca/~javan/index_files/Dominant_behavior.html link]
- Idiap Traffic Junction dataset [http://www.idiap.ch/~odobez/RESSOURCES/DataRelease-TrafficJunction.php link]
- UMN Dataset [http://mha.cs.umn.edu/ link]

**Other datasets (action recognition, surveillance)**:
- PETS 2016 [http://www.cvg.reading.ac.uk/PETS2016/ link],
- MIT Traffic dataset [http://www.ee.cuhk.edu.hk/~xgwang/MITtraffic.html link] (for ped detection),
- Human activity recongnition [http://romisatriawahono.net/lecture/rm/survey/computer%20vision/Chaquet%20-%20Human%20Activity%20Recognition%20-%202013.pdf link] ,
- Extracting Temporal Motifs [http://www.idiap.ch/paper/2053/realdata.html link] ,
- HMDB:[http://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/ link],
- UCF101 [http://crcv.ucf.edu/data/UCF101.php link],
- VIRAT  [http://www.viratdata.org/ link], [http://ieeexplore.ieee.org/document/5995586/ paper],
- A collection of datasets available at V.Nagarajans site [https://sites.google.com/site/vjagan/home/action_datasets link],<br />

## VAD with Hand engineered features
- Anomaly Detection in Crowded Scenes (mixture of dynamic textures) 
[http://www.svcl.ucsd.edu/publications/conference/2010/cvpr2010/cvpr_anomaly_2010.pdf pdf], 
[https://www.researchgate.net/profile/Nuno_Vasconcelos2/publication/239943156_Anomaly_Detection_and_Localization_in_Crowded_Scenes/links/552e9d9b0cf2d495071a6a0f.pdf PAMI 2014] [http://videolectures.net/cvpr2010_mahadevan_adcs video]  
- Optical Acceleration for Motion Description in Videos 
[http://openaccess.thecvf.com/content_cvpr_2017_workshops/w20/papers/Edison_Optical_Acceleration_for_CVPR_2017_paper.pdf pdf]  
- On the Essence of Unsupervised Detection of Anomalous Motion 2017 [https://www.comp.nus.edu.sg/~leowwk/papers/caip2017-anomaly.pdf pdf]
- Discriminative FWK for AD in Videos [https://arxiv.org/pdf/1609.08938.pdf pdf], Abnormal Event Detection at 150 FPS 2013 [http://shijianping.me/abnormal_iccv13.pdf pdf] 
- Real-Time Anomaly Detection and Localization in Crowded Scenes 2015 
[https://arxiv.org/pdf/1511.06936.pdf pdf]
- Video Anomaly Detection Hierarchical Feature Representation 2015 [http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Cheng_Video_Anomaly_Detection_2015_CVPR_paper.pdf pdf]
- Localized Anomaly Detection via Hierarchical Integrated Activity Discovery 2013
[http://www.vanaheim-project.eu/assets/ChockalingamEmonetOdobez-AVSS-2013.pdf pdf] 
- Histograms of OF Orientation and Magnitude to Detect Anomalous Events in Videos
[http://www.ssig.dcc.ufmg.br/wp-content/uploads/2015/06/paper_camera_ready.pdf pdf]
- VAD Based on Local Statistical Aggregates [http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.703.7756&rep=rep1&type=pdf pdf], 
AD Using Dense Trajectories [http://pages.cs.wisc.edu/~kma/downloads/anomaly-detection.pdf pdf]
- Online Detection of Unusual Events in Videos via Dynamic Sparse Coding CVPR 2011 
[http://vision.stanford.edu/pdf/ZhaoFeiFeiXing_CVPR2011.pdf pdf]
-  Textures of Optical Flow for Real-Time AD [https://eprints.qut.edu.au/41572/1/PID1829439.pdf pdf], AD with Bayesian Nonparametrics 2016 
[https://arxiv.org/pdf/1606.08455.pdf pdf]
- Topic Models for Scene Analysis and Abnormality Detection 2009 ICCV-VS WKSHpP[http://www.idiap.ch/~odobez/publications/VaradarajanOdobez-ICCV-VS_2009.pdf pdf], [https://www.youtube.com/watch?v=AZTNPlFLojY Talk 2015]
- Learning Object Motion Patterns for Anomaly & Improved Object Detection 2008 CVPR 
[http://vision.eecs.ucf.edu/papers/cvpr2008/3.pdf pdf]
- Analysis of Persistent Motion Patterns Using the 3D Structure Tensor 2005
