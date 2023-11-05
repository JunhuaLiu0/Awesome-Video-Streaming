# Awesome Video Streaming and Analysis
Awesome-Video-Streaming-and-Analysis is a curated list of awesome frameworks, applications, and systems dedicated to video streaming and analysis (processing). 

With the emergence of the metaverse, an increasing number of related projects and technologies have emerged. However, many existing repositories have not been updated for some time, making it challenging to find current and relevant information. To address this gap, this repository provides an up-to-date and comprehensive collection of papers, resources, and techniques for video streaming and analysis.

Published Scope: \
Streaming and analysis: SIGCOMM, NSDI, MobiCom, INFOCOM, MM, VR, WWW, MMSys, OSDI, NOSSDAV \
Video processing: CVPR, ECCV, ICCV, TCSVT, TMM, ToG, TVCG, TIP, Siggraph, Vis \
*Noting that this repo mainly starts from a perspective of networking. 

I also pack the [conference proceedings about multimedia networking](https://github.com/JunhuaLiu0/Awesome-Video-Streaming-and-Analysis/blob/main/proceedings.pdf) into a single pdf.

## Table of Contents
- [Resources](#resources)
  - [Related Resources](#related-resources)
  - [Related Lectures](#related-lectures)
  - [Tutorial and Workshops](#tutorial-and-workshops)
- [2D Videos](#2d-videos)
  - [Video Streaming](#video-streaming)
  - [Live Video Streaming](#live-video-streaming)
  - [Super Resolution in Video Streaming](#super-resolution-in-video-streaming)
  - [Video Telephony](#video-telephony)
  - [Architectural Support for Video Streaming](#architectural-support-for-video-streaming)
  - [Layered Video Coding and Streaming](#layered-video-coding-and-streaming)
- [360-degree Videos](#360-degree-videos)
  - [360-degree Video Streaming](#360-degree-video-streaming)
  - [Live 360-degree Video Streaming](#live-360-degree-video-streaming)  
  - [360-degree Video System](#360-degree-video-system)
  - [Viewport Prediction](#viewport-prediction)
  - [360-degree Video Datasets](#360-degree-video-datasets)   
- [Volumetric Videos](#volumetric-videos)
  - [Volumetric Video Streaming](#volumetric-video-streaming)
  - [Six DoF Viewport Prediction](#six-dof-viewport-prediction)  
  - [Virtual Reality](#virtual-reality)
  - [Volumetric Video Datasets](#volumetric-video-datasets)
- [Quality of Experience](#quality-of-experience)
- [Video Processing](#video-processing)
  - [Video Analysis](#video-analysis)
  - [Video Analysis for 3D Multimedia](#video-analysis-for-3d-multimedia)  
  - [Video Coding with Deep Learning](#video-coding-with-deep-learning)
  - [Volumetric Video Coding and Compression](#volumetric-video-coding-and-compression)
  - [Other Video Coding](#other-video-coding)
  - [Multimedia 3D Processing](#multimedia-3d-processing)
  - [Security and Privacy Related](#security-and-privacy-related)  
  - [Video Classification](#video-classification) 
- [Tools](#tools)
- [Multimedia Libraries](#multimedia-libraries)


## Resources
Back to [Table of Contents](#table-of-contents)
### Related Resources
Related repo: [Paper-Lit](https://github.com/VideoForage/Video-Lit), [Video-Streaming-Research-Papers](https://github.com/jinyucn/Video-Streaming-Research-Papers), [Deep image/video compression](https://ustc-fvc.github.io/deep-compression.html), [Awesome-360-vision](https://github.com/hsientzucheng/awesome-360-vision), [Awesome-Streaming](https://github.com/manuzhang/awesome-streaming), [Awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF), [Weekly-NeRF](https://github.com/sjtuytc/LargeScaleNeRFPytorch/blob/main/docs/weekly_nerf.md), [Awesome-ARKit](https://github.com/olucurious/Awesome-ARKit), [Awesome-iot](https://github.com/phodal/awesome-iot), [3D Machine learning](https://github.com/timzhang642/3D-Machine-Learning), [audio-video-streaming](https://github.com/0voice/audio_video_streaming), [Awesome Point cloud Analysis](https://github.com/Yochengliu/awesome-point-cloud-analysis), [Awesome-System-for-Machine-Learning](https://github.com/HuaizhengZhang/Awesome-System-for-Machine-Learning), [Awesome-Deep-Neural-Network-Compression](https://github.com/csyhhu/Awesome-Deep-Neural-Network-Compression)


### Related Lectures
[EE364a-Convex optimization a](https://web.stanford.edu/class/ee364a/courseinfo.html), [EE364b-Convex optimization b](https://see.stanford.edu/Course/EE364B), [CS349D: Cloud Computing techniques](https://web.stanford.edu/class/cs349d/), [CSC348K-visual computing system](https://cars.stanford.edu/courses/2021-2022-cs-348k), [EE267-virtual reality](https://web.stanford.edu/class/ee267/), [EE359-wireless communication](https://web.stanford.edu/class/ee359/), [EE398A-Image and Video Compression](https://web.stanford.edu/class/ee398a/index.htm), [CS244 Advanced topics in networking](https://web.stanford.edu/class/archive/cs/cs244/cs244.1156/index.html#:~:text=CS244%3A%20Advanced%20Topics%20in%20Networking%2C%20Spring%202020%201,per%20week%29%2C%20and%20discuss%20them%20in%20class.%20), [ECE 5578 Multimedia Communication](https://sites.google.com/view/ece5578-fall2022), [34702 Topics in Networks: Machine Learning for Networking and Systems](https://people.cs.uchicago.edu/~junchenj/34702-winter23/)

### Tutorial and Workshops
SIGCOMM 23 [Workshop on Emerging Multimedia Systems](https://conferences.sigcomm.org/sigcomm/2023/workshop-ems.html)
Several Special Issues in IEEE Network 23
MM 22: Advances In Quality Assessment Of Video Streaming Systems: Algorithms, Methods, Tools; Short Video Streaming Challenge

MM 21: Deep Learning for Visual Data Compression

MMSys 23, NTIRE 2023 Challenge on 360° Omnidirectional Image and Video Super-Resolution

[OmniCV2022](https://sites.google.com/view/omnicv2022), [GAZE2022](https://gazeworkshop.github.io/2022/), 19 MM Grand Challenge:

Limited by the author's knowledge, this section awaits replenishment.

* Some articles may be repeated.*
## 2D Videos
Back to [Table of Contents](#table-of-contents)
### Video Streaming
* [Enabling High Quality Real-Time Communications with Adaptive Frame-Rate.]() [NSDI'23]
* [Dashlet: Taming Swipe Uncertainty for Robust Short Video Streaming](https://www-users.cse.umn.edu/~fengqian/paper/salientvr_tmc23.pdf) [NSDI'23]
* [Robust Saliency-Driven Quality Adaptation for Mobile 360-Degree Video Streaming](https://www-users.cse.umn.edu/~fengqian/paper/salientvr_tmc23.pdf) [TMC'23]
* [Buffer Awareness Neural Adaptive Video Streaming for Avoiding Extra Buffer Consumption](https://godka.github.io/#) [INFOCOM 23]
* [SJA: Server-driven Joint Adaptation of Loss and Bitrate for Multi-Party Realtime Video Streaming]() [INFOCOM 23]
* [EAVS: Edge-assisted Adaptive Video Streaming with Fine-grained Serverless Pipelines]() [INFOCOM 23]
+ [RDladder: Resolution-Duration Ladder for VBR-encoded Videos via Imitation Learning]() [INFOCOM 23]
* [Swift: Adaptive Video Streaming with Layered Neural Codecs](https://www3.cs.stonybrook.edu/~mdasari/papers/nsdi-2022-paper.pdf) [NSDI'22]
* [Zwei: A Self-play Reinforcement Learning Framework for Video Transmission Services](https://ieeexplore.ieee.org/document/9371417) [TMM 22]
* [Lumos: towards Better Video Streaming QoE through Accurate Throughput Prediction](https://ieeexplore.ieee.org/document/9796948) [INFOCOM 22]
* [SenSei: Aligning Video Streaming Quality with Dynamic User Sensitivity](https://www.usenix.org/system/files/nsdi21-zhang.pdf) [NSDI'21]
+ [OnRL: Improving Mobile Video Telephony via Online Reinforcement Learning](https://www.microsoft.com/en-us/research/uploads/prod/2021/02/mobicom21-final80.pdf) [Mobicom 21]
+ [Llama: A Heterogeneous & Serverless Framework for
Auto-Tuning Video Analytics Pipelines](https://web.stanford.edu/~faromero/llama.pdf) [SoCC 21]
* [Deep Reinforced Bitrate Ladders for Adaptive Video Streaming](https://godka.github.io/nossdav2021-final42.pdf) [NOSSDAV 21]
+ [PECAM: Privacy-Enhanced Video Streaming and Analytics via
Securely-Reversible Transformation](https://dl.acm.org/doi/10.1145/3372224.3419186) [Mobicom 20]
* [Interpreting Deep Learning-Based Networking Systems](https://dl.acm.org/doi/10.1145/3387514.3405859) [Sigcomm 20] 
* [Learning in situ: a randomized experiment in video streaming](https://arxiv.org/pdf/1906.01113.pdf) [NSDI'20]
* [Grad: Learning for Overhead-aware Adaptive Video Streaming with Scalable Video Coding](http://jhc.sjtu.edu.cn/~bjiang/papers/Liu_MM2020_Grad.pdf) [MM'20]
* [PERM: Neural Adaptive Video Streaming with Multi-path Transmission]() [INFOCOM'20]
* [Self-play Reinforcement Learning for Video Transmission](https://godka.github.io/nossdav20.pdf) [NOSSDAV 20]
* [End-to-End Transport for Video QoE Fairness](http://web.cs.ucla.edu/~ravi/CS219_F19/papers/minerva.pdf) [SIGCOMM'19]
+ [Jigsaw: Robust Live 4K Video Streaming](https://www.cs.utexas.edu/~jianhe/jigsaw-mobicom19.pdf) [Mobicom 19]
* [PiTree: Practical Implementation of ABR Algorithms Using Decision Trees]() [MM'19] [[Code](https://github.com/transys-project/pitree/)] [[Dataset](https://github.com/transys-project/pitree-dataset/)]
* [Comyco: Quality-aware Adaptive Video Streaming via Imitation Learning](https://arxiv.org/pdf/1908.02270.pdf) [MM'19] 
+ [Intelligent Edge-Assisted Crowdcast with Deep Reinforcement Learning for Personalized QoE](https://ieeexplore.ieee.org/document/8737456/) [Infocom 19]
* [Requet: Real-Time QoE Detection for Encrypted YouTube Traffic](https://wimnet.ee.columbia.edu/wp-content/uploads/2019/02/MMsys19_Requet.pdf) [MMSys'19][[Data](https://github.com/Wimnet/RequetDataSet)]
+ [Intelligent Edge-Assisted Crowdcast with Deep Reinforcement Learning for Personalized QoE](https://ieeexplore.ieee.org/document/8737456/) [Infocom 19] [DeepCast]
+ [QFlow: A Reinforcement Learning Approach to High QoE Video Streaming over Wireless Networks](https://arxiv.org/abs/1901.00959) [Mobihoc 19]
+ [Edge Computing Assisted Adaptive Mobile Video Streaming](https://ieeexplore.ieee.org/document/8395060) [TMC 19
* [Oboe: Auto-tuning Video ABR Algorithms to Network Conditions](https://engineering.purdue.edu/~isl/papers/sigcomm18-final128.pdf) [SIGCOMM'18]
* [Neural Adaptive Content-aware Internet Video Delivery](https://www.usenix.org/system/files/osdi18-yeo.pdf) [OSDI'18]
* [ABR Streaming of VBR-encoded Videos: Characterization, Challenges, and Solutions](https://www-users.cs.umn.edu/~fengqian/paper/vbr_conext18.pdf) [CoNEXT'18]
* [Understanding Video Management Planes](https://engineering.purdue.edu/~isl/papers/imc2018.pdf) [IMC'18]
* [From Theory to Practice: Improving Bitrate Adaptation in the DASH Reference Player](https://www.akamai.com/us/en/multimedia/documents/technical-publication/improving-bitrate-adaptation-in-the-dash-reference-player.pdf) [MMSys'18]
* [VideoNOC: assessing video QoE for network operators using passive measurements](https://www.cc.gatech.edu/~tmangla3/papers/VideoNOC_MMSys2018.pdf) [MMSys'18]
+ [Intelligent Edge-Assisted Crowdcast with Deep Reinforcement Learning for Personalized QoE](https://ieeexplore.ieee.org/document/8737456/) [Infocom 19] [DeepCast]
+ [QFlow: A Reinforcement Learning Approach to High QoE Video Streaming over Wireless Networks](https://arxiv.org/abs/1901.00959) [Mobihoc 19]
+ [Edge Computing Assisted Adaptive Mobile Video Streaming](https://ieeexplore.ieee.org/document/8395060) [TMC 19]
* [Disk|Crypt|Net: rethinking the stack for high-performance video streaming](https://www.cl.cam.ac.uk/~rnw24/papers/201708-sigcomm-diskcryptnet.pdf) [SIGCOMM'17]
* [Neural Adaptive Video Streaming with Pensieve](https://people.csail.mit.edu/hongzi/content/publications/Pensieve-Sigcomm17.pdf) [SIGCOMM'17][[Code](https://github.com/hongzimao/pensieve)]
* [Pytheas: Enabling Data-Driven QoE Optimization Using Group-Based Exploration-Exploitation](https://www.usenix.org/system/files/conference/nsdi17/nsdi17-jiang_0.pdf) [NSDI'17]
* [Dissecting VOD Services for Cellular: Performance, Root Causes and Best Practices](https://conferences.sigcomm.org/imc/2017/papers/imc17-final111.pdf) [IMC'17]
* [CS2P: Improving Video Bitrate Selection and Adaptation with Data-Driven Throughput Prediction](https://users.ece.cmu.edu/~vsekar/papers/sigcomm16_cs2p.pdf) [SIGCOMM'16]
* [MP-DASH: Adaptive Video Streaming Over Preference-Aware Multipath](http://www.research.att.com/ecms/dam/sites/labs_research/content/publications/VA_MP-DASH_Adaptive_Video_Streaming.pdf) [CoNEXT'16]
* [DASH2M: Exploring HTTP/2 for Internet Streaming to Mobile Devices](https://dl.acm.org/citation.cfm?id=2964313) [MM'16]
* [mDASH: A Markov Decision-Based Rate Adaptation Approach for Dynamic HTTP Streaming](https://ieeexplore.ieee.org/iel7/6046/4456689/07393865.pdf) [TMM 16]
* [BOLA: Near-Optimal Bitrate Adaptation for Online Videos](https://arxiv.org/pdf/1601.06748.pdf) [INFOCOM'16]
* [A Control-Theoretic Approach for Dynamic Adaptive Video Streaming over HTTP](https://users.ece.cmu.edu/~vsekar/papers/sigcomm15_mpcdash.pdf) [SIGCOMM'15]
* [Can Accurate Predictions Improve Video Streaming in Cellular Networks?](http://www.cs.jhu.edu/~xinjin/files/HotMobile15_VideoStreaming.pdf) [HotMobile'15]
* [A Control-Theoretic Approach to Rate Adaption for DASH Over Multiple Content Distribution Servers](https://ieeexplore.ieee.org/document/6662391) [TCSVT 14]
* [A Buffer-Based Approach to Rate Adaptation: Evidence from a Large Video Streaming Service](http://yuba.stanford.edu/~nickm/papers/sigcomm2014-video.pdf) [SIGCOMM'14]
* [Improving Fairness, Efficiency, and Stability in HTTP-based Adaptive Video Streaming with FESTIVE](https://conferences.sigcomm.org/co-next/2012/eproceedings/conext/p97.pdf) [CoNEXT'12]

| Year | Method                                                       | Detail                                  |
| ---- | ------------------------------------------------------------ | --------------------------------------- |
| 21   | [Fugu](https://www.usenix.org/system/files/nsdi20-paper-yan.pdf)  [NSDI 21] | DNN (bandwidth prediction)+DP (control) |
| 20   | [OnRL](https://dl.acm.org/doi/10.1145/3372224.3419186)  [Mobicom 20] | Online RL                               |
| 20   | [Stick](https://godka.github.io/Infocom_20_Stick.pdf)  [Infocom 20] | Buffer-based+Learning-based             |
| 19   | [Comyco](https://arxiv.org/pdf/1908.02270)  [MM 19], [Concerto](https://dl.acm.org/doi/10.1145/3300061.3345430)  [Mobicom 19] | Imitation Learning                      |
| 19   | [PiTree](https://zilimeng.com/papers/pitree-mm19.pdf)  [MM 19] | Explainable Learning                    |
| 18   | [Oboe](https://engineering.purdue.edu/~isl/papers/sigcomm18-final128.pdf)  [Sigcomm 18] | Auto-tuning parameters                  |
| 17   | [Pensieve](https://people.csail.mit.edu/hongzi/content/publications/Pensieve-Sigcomm17.pdf)  [Sigcomm 17] [Update](https://openreview.net/pdf?id=SJlCkwN8iV) [ICML 19] | Reinforcement Learning                  |
| 16   | [CS2P](https://cs.cmu.edu/~junchenj/cs2p.pdf)  [Sigcomm 16]  |                                         |
| 16   | [BOLA](https://arxiv.org/pdf/1601.06748.pdf)  [Infocom 16]   | Buffer-Based+Lyapunov Optimization      |
| 15   | [MPC](https://conferences.sigcomm.org/sigcomm/2015/pdf/papers/p325.pdf)  [Sigcomm 15] | MPC                                     |
| 14   | [Buffer-Based](https://web.stanford.edu/class/cs244/papers/sigcomm2014-video.pdf)  [Sigcomm 14] | Buffer-Based                            |
| 12   | [Rate-Based](https://dl.acm.org/doi/10.1145/2413176.2413189)  [CoNEXT 12] | Rate-Based                              |


### Live Video Streaming
+ [ARTEMIS: Adaptive bitrate ladder optimization for live video streaming](https://dspace.networks.imdea.org/bitstream/handle/20.500.12761/1760/ARTEMIS_Adaptive_Bitrate_Ladder_Optimization_for_Live_Video_Streaming_NSDI_2024_accepted_version.pdf?sequence=1&isAllowed=y) [NSDI 24]
+ [Who is the Rising Star? Demystifying the Promising Streamers in Crowdsourced Live Streaming](https://godka.github.io/#) [Infocom'23]
+ [AggCast: Practical Cost-effective Scheduling for Large-scale Cloud-edge Crowdsourced Live Streaming](https://godka.github.io/#) [MM'22]
+ [Low Latency Live Streaming Implementation in DASH and HLS]() [MM'22]
+ [Opte: Online per-title encoding for live video streaming](https://ieeexplore.ieee.org/abstract/document/9746745/) [ICASSP'22]
+ [Towards Optimal Low-Latency Live Video Streaming](https://ieeexplore.ieee.org/abstract/document/9459436) [ToN'21]
+ [ReCLive: Real-Time Classification and QoE Inference of Live Video Streaming Services](https://ieeexplore.ieee.org/abstract/document/9521288) [IWQoS'21]
+ [A Low-Latency MPTCP Scheduler for Live Video Streaming in Mobile Networks](https://ieeexplore.ieee.org/abstract/document/9440790) [TWC'21]
+ [Look Ahead at the First-mile in Livecast with Crowdsourced Highlight Prediction](https://www2.cs.sfu.ca/~jcliu/Papers/LookAhead20.pdf) [Infocom 20]
+ [Neural-Enhanced Live Streaming: Improving Live Video Ingest via Online Learning](https://dl.acm.org/doi/abs/10.1145/3387514.3405856) [Sigcomm 20] [LiveNas]
+ [MultiLive: Adaptive Bitrate Control for Low-delay Multi-party Interactive Live Streaming](http://www.ece.sunysb.edu/~xwang/public/paper/MultiLive.pdf) [Infocom 20]
+ [Vabis: Video Adaptation Bitrate System for Time-Critical Live Streaming](https://jackkosaian.github.io/files/papers/sigcomm2019vantage.pdf) [TMM 20]
+ [Optimizing Social Welfare of Live Video Streaming Services in Mobile Edge Computing](https://ieeexplore.ieee.org/document/8653413) [TMC 20]
+ [Intelligent Edge-Assisted Crowdcast with Deep Reinforcement Learning for Personalized QoE](https://ieeexplore.ieee.org/document/8737456/) [Infocom 19] [DeepCast]
+ [Vantage: Optimizing video upload for time-shifted viewing of social live stream](https://jackkosaian.github.io/files/papers/sigcomm2019vantage.pdf) [Sigcomm 19]
+ [Edge-based Transcoding for Adaptive Live Video Streaming](https://www.usenix.org/conference/hotedge19/presentation/dogga) [HotEdge 19]
+ [QARC: Video Quality Aware Rate Control for Real-Time Video Streaming based on Deep Reinforcement Learning](https://dl.acm.org/doi/abs/10.1145/3240508.3240545) [MM 18]
+ [Characterizing User Behaviors in Mobile Personal Livecast: Towards an Edge Computing-assisted Paradigm](https://dl.acm.org/doi/10.1145/3219751) [ToMM 18]
+ [Cloud-Assisted Crowdsourced Livecast](https://dl.acm.org/doi/10.1145/3095755) [ToMM 17]
+ [Coping With Heterogeneous Video Contributors and Viewers in Crowdsourced Live Streaming: A Cloud-Based Approach](https://www2.cs.sfu.ca/~jcliu/Papers/HeterogeneousVideo.pdf) [TMM 16]
+ [When Crowd Meets Big Video Data: Cloud-Edge Collaborative Transcoding for Personal Livecast](https://ieeexplore.ieee.org/document/8478387) [TNSE 15]


### Super Resolution in Video Streaming
+ [NeuriCam: Key-Frame Video Super-Resolution and Colorization for IoT Cameras]() [Mobicom 23]
+ [Collaborative Streaming and Super Resolution Adaptation for Mobile Immersive Videos]() [INFOCOM 23]
+ [YuZu: Neural-Enhanced Volumetric Video Streaming](https://www-users.cse.umn.edu/~fengqian/paper/yuzu_nsdi22.pdf)  [NSDI 22]
+ [Efficient Video Compression via Content-Adaptive Super-Resolution](https://arxiv.org/abs/2104.02322) [ICCV 21]
+ [Efficient Volumetric Video Streaming Through Super Resolution](https://dl.acm.org/doi/10.1145/3446382.3448663) [HotMobile 21]
+ [SplitSR: An End-to-End Approach to Super-Resolution on Mobile Devices](https://ubicomplab.cs.washington.edu/pdfs/splitsr.pdf)  [IMWUT 21]
+ [Neural-Enhanced Live Streaming: Improving Live Video Ingest via Online Learning](https://dl.acm.org/doi/abs/10.1145/3387514.3405856) [Sigcomm 20] [LiveNas]
+ [NEMO: Enabling Neural-enhanced Video Streaming on Commodity Mobile Devices](https://dl.acm.org/doi/10.1145/3372224.3419185) [Mobicom 20]
+ [Streaming 360-Degree Videos Using Super-Resolution](https://ieeexplore.ieee.org/document/9155477) [Infocom 20] [[code]](https://github.com/VideoForage/Video-Super-Resolution)
+ [SR360: Boosting 360-Degree Video Streaming with Super-Resolution](https://dl.acm.org/doi/abs/10.1145/3386290.3396929) [Nossdav 20]
+ [Improving Quality of Experience by Adaptive Video Streaming with Super-Resolution](https://ieeexplore.ieee.org/document/9155384) [Infocom 20]
+ [Streaming 360◦ Videos using Super-resolution]()  [Infocom 20]
+ [Supremo: Cloud-Assisted Low-Latency Super-Resolution in Mobile Devices](https://arxiv.org/pdf/1908.07985)  [TMC 20]
+ [MobiSR: Effcient OnDevice Super-Resolution through Heterogeneous Mobile Processors](https://arxiv.org/pdf/1908.07985)  [Mobicom 19]
+ [Dejavu: Enhancing Videoconferencing with Prior Knowledge](http://panhu.me/pdf/2019/Dejavu.pdf)  [HotMobile 19]
+ [Bridging the Edge-Cloud Barrier for Real-time Advanced Vision Analytics](https://www.usenix.org/system/files/hotcloud19-paper-wang.pdf)  [HotCloud 19]
+ [Neural Adaptive Content-aware Internet Video Delivery](https://www.usenix.org/system/files/osdi18-yeo.pdf) [OSDI 18] [NAS] [[code]](https://github.com/kaist-ina/NAS_public)


### Video Telephony
* [NEMO: Enabling Neural-enhanced Video Streaming on Commodity Mobile Devices]() [MobiCom'20]
* [OnRL: Improving Mobile Video Telephony via Online Reinforcement Learning]() [MobiCom'20]
* [LiveNAS - Neural-Enhanced Live Streaming: Improving Live Video Ingest via Online Learning]() [SIGCOMM'20]
* [Jigsaw: Robust Live 4K Video Streaming](http://www.cs.utexas.edu/~jianhe/jigsaw-mobicom19.pdf) [MobiCom'19]
* [Learning to Coordinate Video Codec with Transport Protocol for Mobile Video Telephony](https://dl.acm.org/citation.cfm?id=3345430) [MobiCom'19]
* [Vantage: optimizing video upload for time-shifted viewing of social live streams](https://dl.acm.org/citation.cfm?id=3342064) [SIGCOMM'19]
* [Salsify: Low-Latency Network Video Through Tighter Integration Between a Video Codec and a Transport Protocol](https://cs.stanford.edu/~keithw/salsify-paper.pdf) [NSDI'18]
* [Encoding, Fast and Slow: Low-Latency Video Processing Using Thousands of Tiny Threads](https://www.usenix.org/system/files/conference/nsdi17/nsdi17-fouladi.pdf) [NSDI'17]
* [POI360: Panoramic Mobile Video Telephony over LTE Cellular Networks](http://xyzhang.ucsd.edu/papers/XXie_CoNEXT17_POI360.pdf) [CoNEXT'17]

## Architectural Support for Video Streaming
* [Warehouse-Scale Video Acceleration: Co-design and Deployment in the Wild](https://www.gwern.net/docs/cs/2021-ranganathan.pdf) [ASPLOS'21]
* [Deja View: Spatio-Temporal Compute Reuse for Energy-Efficient 360° VR Video Streaming](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a241/466100a241.pdf) [ISCA '20]
* [Distilling the Essence of Raw Video to Reduce Memory Usage and Energy at Edge Devices](https://dl.acm.org/doi/10.1145/3352460.3358298) [MICRO '19]
* [Race-To-Sleep + Content Caching + Display Caching: A Recipe for Energy-eficient Video Streaming on Handhelds](https://dl.acm.org/doi/10.1145/3123939.3123948) [MICRO '17]

### Layered Video Coding and Streaming
* [Grad: Learning for Overhead-aware Adaptive Video Streaming with Scalable Video Coding](http://jhc.sjtu.edu.cn/~bjiang/papers/Liu_MM2020_Grad.pdf) [ACM MM'20]
* [LBP: Robust Rate Adaptation Algorithm for SVC Video Streaming](https://arxiv.org/pdf/1805.00041.pdf) [IEEE/ACM ToN'19]
* [Layer-Assisted Adaptive Video Streaming](https://dl.acm.org/doi/pdf/10.1145/3210445.3210454) [ACM NOSSDAV'18]
* [Layered Coding vs. Multiple Descriptions for Video Streaming over Multiple Paths](https://web.stanford.edu/~bgirod/pdfs/ChakareskiACM03.pdf) [ACM MM'03]
* [Two-Layer Coding of Video Signals for VBR Networks](https://web.stanford.edu/~bgirod/pdfs/ChakareskiACM03.pdf) [IEEE JSAC'1989]
* [Multiple Description Coding](https://github.com/mdasari823/Multiple-Description-Coding)

## 360-degree Videos
Back to [Table of Contents](#table-of-contents)
### 360-degree Video Streaming
+ [Robust Saliency-Driven Quality Adaptation for Mobile 360-Degree Video Streaming]() [TMC 23]
+ [Energy-Efficient 360-Degree Video Streaming on Multicore-Based Mobile Devices]() [INFOCOM 23]
+ [OmniSense: Towards Edge-Assisted Online Analytics for 360-Degree Videos]() [INFOCOM 23]
+ [Sophon: Super-Resolution Enhanced 360°Video Streaming with Visual Saliency-aware Prefetch](https://dl.acm.org/doi/pdf/10.1145/3503161.3547750) [MM 22]
+ [Personalized 360-Degree Video Streaming: A Meta-Learning Approach](https://dl.acm.org/doi/pdf/10.1145/3503161.3548047) [MM 22]
+ [Improving Generalization for Neural Adaptive Video Streaming via Meta Reinforcement Learning](https://dl.acm.org/doi/pdf/10.1145/3503161.3548331) [MM 22]
+ [SalientVR: Saliency-Driven Mobile 360-Degree Video Streaming with Gaze Information](https://www-users.cse.umn.edu/~fengqian/paper/salientvr_mobicom22.pdf)  [Mobicom 22]
+ [Popularity-Aware 360-Degree Video Streaming](http://mcn.cse.psu.edu/paper/xianda/infocom-xianda21.pdf)  [Infocom 21]
+ [Robust 360° Video Streaming via Non-Linear Sampling](https://www.cs.purdue.edu/cgvlab/papers/popescu/2021InfoCommCOREPopescu.pdf)  [Infocom 21] 
+ [AdaP-360: User-Adaptive Area-of-Focus Projections for Bandwidth-Efficient 360-Degree Video Streaming](http://www.cs.binghamton.edu/~yaoliu/publications/mm20-adap360.pdf) [MM 20]
+ [QuRate: Power-Efficient Mobile Immersive Video Streaming](https://dl.acm.org/doi/pdf/10.1145/3339825.3391863) [MMsys 20]
+ [Deja View: Spatio-Temporal Compute Reuse for Energy-Efficient 360° VR Video Streaming](https://ieeexplore.ieee.org/document/9138937/)  [ISCA 20]
+ [SR360: Boosting 360-Degree Video Streaming with Super-Resolution](https://dl.acm.org/doi/abs/10.1145/3386290.3396929)  [NOSSDAV 20]
+ [Streaming 360-Degree Videos Using Super-Resolution](https://www3.cs.stonybrook.edu/~mdasari/assets/pdf/infocom20.pdf)  [Infocom 20]
+ [Tile Rate Allocation for 360-Degree Tiled Adaptive Video Streaming](https://dl.acm.org/doi/pdf/10.1145/3394171.3413550)  [MM 20]
+ [EPASS360: QoE-aware 360-degree Video Streaming over Mobile Devices](https://ieeexplore.ieee.org/document/9024132)  [TMC 20]
+ [DRL360: 360-degree Video Streaming with Deep Reinforcement Learning](https://ieeexplore.ieee.org/document/8737361)  [Infocom 19]
+ [Pano: Optimizing 360° Video Streaming with a Better Understanding of Quality Perception](https://people.cs.uchicago.edu/~junchenj/docs/360StreamingQuality_SIGCOMM.pdf)  [Sigcomm 19]
+ [Proactive Caching for Vehicular Multi-View 3D Video Streaming via Deep Reinforcement Learning](https://ieeexplore.ieee.org/document/8677285)  [TWC 19]
+ [CLS: A Cross-user Learning based System for Improving QoE in 360-degree Video Adaptive Streaming](https://www.icst.pku.edu.cn/NetVideo/docs/20201104111337969645.pdf) [MM18]
+ [Viewport-Driven Rate-Distortion Optimized 360° Video Streaming](https://ieeexplore.ieee.org/abstract/document/8422859) [ICC 18]\
+ [360-Degree Innovations for Panoramic Video Streaming]()  [HotNets 18]
+ [360ProbDASH: Improving QoE of 360 Video Streaming Using Tile-based HTTP Adaptive Streaming](https://www.icst.pku.edu.cn/NetVideo/docs/20201104112437185498.pdf) [MM 17]
+ [Adaptive 360-Degree Video Streaming using Scalable Video Coding](https://dl.acm.org/citation.cfm?id=3123414) [MM 17]

### Live 360-degree Video Streaming

+ [SphericRTC: A System for Content-Adaptive Real-Time 360-Degree Video Communication](https://dl.acm.org/doi/10.1145/3394171.3413999)  [MM 20]
+ [An Analysis of Delay in Live 360° Video Streaming Systems](https://ece.northeastern.edu/fac-ece/dkoutsonikolas/publications/multimedia20.pdf)  [MM 20]
+ [Low-latency FoV-adaptive Coding and Streaming for Interactive 360°  Video Streaming](https://dl.acm.org/doi/pdf/10.1145/3394171.3413751)  [MM 20]
+ [Flocking-based Live Streaming of 360-degree Video](https://dl.acm.org/doi/abs/10.1145/3339825.3391856)  [MMsys 20]
+ [Mobile Streaming of Live 360-Degree Videos](https://www2.cs.sfu.ca/~mhefeeda/Papers/tmm20_vrcast.pdf)  [TMM 20]
+ [MA360: MULTI-AGENT DEEP REINFORCEMENT LEARNING BASED LIVE 360-DEGREE VIDEO STREAMING ON EDGE](https://www.icst.pku.edu.cn/NetVideo/docs/20201026174450838459.pdf)  [ICME 20]
+ [A Measurement Study of YouTube 360° Live Video Streaming](https://zyan.gsucreate.org/papers/360measure_nossdav19.pdf)  [NOSSDAV 19]
+ [Event-driven Stitching for Tile-based Live 360 Video Streaming](https://zyan.gsucreate.org/papers/livetexture_mmsys19.pdf)  [MMsys 19]
+ [RATS: Adaptive 360-degree Live Streaming](https://dl.acm.org/doi/10.1145/3304109.3323837)  [MMsys 19]
+ [LIME: Understanding Commercial 360° Live Video Streaming Services](https://bohan00.github.io/share/LIME_MMSys19.pdf)  [MMSys 19]

### 360-degree Video System

+ [How to Evaluate Mobile 360° Video Streaming Systems?](http://www.cse.buffalo.edu/faculty/dimitrio/publications/hotmobile20.pdf)  [HotMobile 20]
+ [Freedom: Fast Recovery Enhanced VR Delivery Over Mobile Networks](https://dl.acm.org/doi/pdf/10.1145/3307334.3326087)  [MobiSys 19]
+ [Tile-based Caching Optimization for 360° Videos](http://graphics.cs.aueb.gr/graphics/docs/papers/MOBIHOC-2019.pdf)  [Mobihoc 19]
+ [A Two-Tier System for On-Demand Streaming of 360 Degree Video Over Dynamic Networks](https://par.nsf.gov/servlets/purl/10105313)  [TCSVT 19]
+ [Flare: Practical Viewport-Adaptive 360-Degree Video Streaming for Mobile Devices](https://www.research.att.com/ecms/dam/sites/labs_research/content/publications/N_Flare_Practical_Viewport_Adaptive_360Degree_Video_Streaming.pdf)  [Mobicom 18]
+ [Rubiks: Practical 360-Degree Streaming for Smartphones](https://www.cs.utexas.edu/~mubashir/papers/rubiks_mobisys.pdf)  [MobiSys 18]
+ [Creating the Perfect Illusion : What will it take to Create Life-Like Virtual Reality Headsets?](https://www.microsoft.com/en-us/research/uploads/prod/2018/02/perfectillusion.pdf)  [HotMobile 18]
+ [POI360: Panoramic Mobile Video Telephony over LTE Cellular Networks](http://xyzhang.ucsd.edu/papers/XXie_CoNEXT17_POI360.pdf)  [CoNEXT 17]
+ [VR is on the Edge: How to Deliver 360° Videos in Mobile Networks](https://dl.acm.org/doi/10.1145/3097895.3097901)  [VR/AR Network 17]
+ [VR/AR Immersive Communication: Caching, Edge Computing, and Transmission Trade-Offs](https://dl.acm.org/doi/pdf/10.1145/3097895.3097902)  [VR/AR Network 17]

### Viewport Prediction
+ [Personalized 360-Degree Video Streaming: A Meta-Learning Approach](https://dl.acm.org/doi/pdf/10.1145/3503161.3548047) [MM 22]
+ [Subtitle-based Viewport Prediction for 360-degree Virtual Tourism Video](https://ieeexplore.ieee.org/document/9904420) 
+ [Graph Learning Based Head Movement Predictionfor Interactive 360 Video Streaming](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9416230)  [TIP 21]
+ [Motion-Prediction-based Wireless Scheduling for Multi-User Panoramic Video
Streaming]()  [Infocom 21]
+ [PARIMA: Viewport Adaptive 360-Degree Video Streaming](https://arxiv.org/pdf/2103.00981) [WWW 21]
+ [LiveDeep: Online Viewport Prediction for Live Virtual Reality Streaming Using Lifelong Deep Learning](http://ieeexplore.ieee.org/document/9089486/)  [VR 20]
+ [Viewport Prediction for 360° Videos: A Clustering Approach](https://dl.acm.org/doi/pdf/10.1145/3386290.3396934)  [NOSSDAV 20]
+ [A Spherical Convolution Approach for Learning Long Term Viewport Prediction in 360 Immersive Video](https://aaai.org/ojs/index.php/AAAI/article/view/7377/7241)  [AAAI 20]
+ [Sparkle: User-Aware Viewport Prediction in 360-degree Video Streaming](https://ieeexplore.ieee.org/document/9238515)  [TMM 20]
+ [DGaze: CNN-Based Gaze Prediction in Dynamic Scenes](https://ieeexplore.ieee.org/document/8998375)  [TVCG 20]
+ [Very Long Term Field of View Prediction for 360-degree Video Streaming](https://arxiv.org/pdf/1902.01439)  [MIPR 19]
+ [LADDERNET: KNOWLEDGE TRANSFER BASED VIEWPOINT PREDICTION IN 360° VIDEO](https://ieeexplore.ieee.org/document/8682776)  [ICASSP 19]
+ [SPHERICAL CLUSTERING OF USERS NAVIGATING 360! CONTENT](https://ir.cwi.nl/pub/28575/28575.pdf)  [ICASSP 19] 
+ [Viewport Prediction for Live 360-Degree Mobile Video Streaming Using User-Content Hybrid Motion Tracking](https://dl.acm.org/doi/10.1145/3328914)  [IMWUT 19]
+ [Your Attention is Unique: Detecting 360-Degree Video Saliency in Head-Mounted Display for Head Movement Prediction](https://dl.acm.org/doi/10.1145/3240508.3240669)  [MM 18]
+ [Gaze Prediction in Dynamic 360° Immersive Videos](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_Gaze_Prediction_in_CVPR_2018_paper.pdf)  [CVPR 18]
+ [CUB360: EXPLOITING CROSS-USERS BEHAVIORS FOR VIEWPORT PREDICTION IN 360 VIDEO ADAPTIVE STREAMING](https://ieeexplore.ieee.org/document/8486606)  [ICME 18]
+ [Predictive View Generation to Enable Mobile 360-degree and VR Experiences](http://esdat.ucsd.edu/sites/esdat.ucsd.edu/files/publications/SIGCOMM_workshop_predictive_view.pdf)  [VR/AR Network 18]
+ [Fixation Prediction for 360° Video Streaming to Head-Mounted Displays](https://2017.acmmmsys.org/wp-content/uploads/2017/05/Cheng-Hsin-Hsu.pdf)  [NOSSDAV 17]
+ [Predicting Head Movement in Panoramic Video: A Deep Reinforcement Learning Approach](https://arxiv.org/pdf/1710.10755)  [TPAMI 15]


### 360-degree Video Datasets

+ [A Taxonomy and Dataset for 360° Videos](https://arxiv.org/pdf/1905.03823)  [MMSys 19]
+ [360-degree Video Gaze Behaviour: A Ground-Truth Data Set and a Classification Algorithm for Eye Movements](https://dl.acm.org/doi/10.1145/3343031.3350947)  [MM 19]
+ [Gaze Prediction in Dynamic 360° Immersive Videos](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_Gaze_Prediction_in_CVPR_2018_paper.pdf)  [CVPR 18]
+ [A Dataset of Head and Eye Movements for 360° Videos](https://hal.archives-ouvertes.fr/hal-01994923/document)  [MMSys 18]
+ [360° Video Viewing Dataset in Head-Mounted Virtual Reality](https://dl.acm.org/doi/10.1145/3083187.3083219)  [MMSys 17]
+ [360-Degree Video Head Movement Dataset](https://dl.acm.org/doi/10.1145/3083187.3083215)  [MMSys 17]
+ [A Dataset of Head and Eye Movements for 360 Degree Images](https://dl.acm.org/doi/10.1145/3083187.3083218)  [MMSys 17]
+ [A Dataset for Exploring User Behaviors in VR Spherical Video Streaming](https://dl.acm.org/doi/10.1145/3083187.3083210)  [MMSys 17]


## Volumetric Videos
Back to [Table of Contents](#table-of-contents)
### Volumetric Video Streaming
+ Habitus: Boosting Mobile Immersive Content Delivery through Full-body Pose Tracking and Multipath Networking [NSDI 24]
+ Progressive Frame Patching for FoV-based Point Cloud Video Streaming [Arxiv 23]
+ [G-PCC++: Enhanced Geometry-based Point Cloud Compression](https://dl.acm.org/doi/pdf/10.1145/3581783.3613827) [MM 23]
+ [Addressing Scalability for Real-time Multiuser Holo-portation: Introducing and Assessing a Multipoint Control Unit (MCU) for Volumetric Video](https://dl.acm.org/doi/pdf/10.1145/3581783.3613777) [MM 23]
+ [Hermes: Leveraging Implicit Inter-Frame Correlation for Bandwidth-Efficient Mobile Volumetric Video Streaming](https://dl.acm.org/doi/pdf/10.1145/3581783.3613907) [MM 23]
+ Enabling Low Bit-Rate MPEG V-PCC-encoded Volumetric Video Streaming with Sub-sampling [MMSys 23]
+ LiveVV: Human-Centered Live Volumetric Video Streaming System [Arxiv 23]
+ Spatial Perceptual Quality Aware Adaptive Volumetric Video Streaming [Globecom 23]
+ PatchVVC: A Real-time Compression Framework for Streaming Volumetric Videos [MMSys 23]
+ Hermes: Leveraging Implicit Inter-Frame Correlation for Bandwidth-Efficient Mobile Volumetric Video Streaming [MM 23]
+ Understanding User Behavior in Volumetric Video Watching: Dataset, Analysis and Prediction [MM 23]
+ Mobile Volumetric Video Streaming System through Implicit Neural Representation [Sigcomm EMS 23]
+ [FarfetchFusion: Towards Fully Mobile Live 3D Telepresence Platform](https://dl.acm.org/doi/abs/10.1145/3570361.3592525) [MobiCom 23]
+ [MetaStream: Live Volumetric Content Capture, Creation, Delivery, and Rendering in Real Time](https://dl.acm.org/doi/pdf/10.1145/3570361.3592530) [MobiCom 23]
+ Immersive media technologies [Review 23]
+ [CaV3: Cache-assisted Viewport Adaptive Volumetric Video Streaming](https://ieeexplore.ieee.org/document/10108421) [VR 23]
+ FRAS: Federated Reinforcement Learning empowered Adaptive Point Cloud Video Streaming [Arxiv 23]
+ [Volumetric video streaming: Current approaches and implementations](https://arxiv.org/abs/2209.01982) [Review 22]
+ [YuZu: Neural-Enhanced Volumetric Video Streaming](https://www-users.cse.umn.edu/~fengqian/paper/yuzu_nsdi22.pdf)  [NSDI 22]
+ [Vues: Practical Volumetric Video Streaming through Multiview Transcoding](https://www-users.cse.umn.edu/~fengqian/paper/vues_mobicom22.pdf)  [Mobicom 22]
+ [Optimal Volumetric Video Streaming with Hybrid Saliency based Tiling](https://ieeexplore.ieee.org/document/9720162)  [TMM 22]
+ [Dynamic Point Cloud Compression with Cross-Sectional Approach](https://arxiv.org/abs/2204.11409)  [Arxiv 22]
+ [A QoE Model in Point Cloud Video Streaming](https://arxiv.org/abs/2111.02985)  [Arxiv 22]
+ [FRAS: Federated Reinforcement Learning empowered Adaptive Point Cloud Video Streaming](https://arxiv.org/abs/2207.07394)  [Arxiv 22]
+ [From Capturing to Rendering: Volumetric Media Delivery with Six Degrees of Freedom](https://ieeexplore.ieee.org/document/9247522)  [Review 22]
+ [Innovating Multi-user Volumetric Video Streaming through Cross-layer Design](https://dl.acm.org/doi/pdf/10.1145/3484266.3487396)  [HotNets 21]
+ [Efficient Volumetric Video Streaming Through Super Resolution](https://dl.acm.org/doi/10.1145/3446382.3448663)  [HotMobile 21]
+ [Point Cloud Video Streaming: Challenges and Solutions](https://ieeexplore.ieee.org/abstract/document/9537928)  [IEEE Network 21]
+ [AITransfer: Progressive AI-powered Transmission for Real-Time Point Cloud Video Streaming] ()
+ [GROOT: A Real-time Streaming System of High-Fidelity Volumetric Videos](https://juheonyi.github.io/files/GROOT.pdf)  [Mobicom 20]
+ [ViVo: Visibility-Aware Mobile Volumetric Video Streaming](https://www-users.cs.umn.edu/~fengqian/paper/vivo_mobicom20.pdf)  [Mobicom 20]
+ [Towards Viewport-dependent 6DoF 360 Video Tiled Streaming for Virtual Reality Systems](https://dl.acm.org/doi/10.1145/3394171.3413712)  [MM 20]
+ [User Centered Adaptive Streaming of Dynamic Point Clouds with Low Complexity Tiling](https://ir.cwi.nl/pub/30378/30378.pdf)  [MM 20]
+ [Towards Viewport-dependent 6DoF 360 Video Tiled Streaming for Virtual Reality Systems](https://dl.acm.org/doi/pdf/10.1145/3394171.3413712)  [MM 20]
+ [VVSec: Securing Volumetric Video Streaming via Benign Use of Adversarial Perturbation](https://dl.acm.org/doi/pdf/10.1145/3394171.3413639)  [MM 20]
+ [A Pipeline for Multiparty Volumetric Video Conferencing: Transmission of Point Clouds over Low Latency DASH](https://repository.tudelft.nl/islandora/object/uuid:4a0178a3-971b-491a-b856-014d091f188e/datastream/OBJ/download)  [MMsys 20]
+ [Cloud Rendering-based Volumetric Video Streaming System for Mixed Reality Services](https://arxiv.org/pdf/2003.02526)  [MMsys 20]
+ [Low-latency Cloud-based Volumetric Video Streaming Using Head Motion Prediction](https://arxiv.org/pdf/2001.06466)  [NOSSDAV 20]
+ [Emerging MPEG Standards for Point Cloud Compression](https://ir.cwi.nl/pub/29040/Emerging-MPEG-Standards-for-Point-Cloud-Compression.pdf)  [TCSVT 19]
+ [Toward Practical Volumetric Video Streaming on Commodity Smartphones]()  [HotMobile 19]
+ [Rate-Utility Optimized Streaming of Volumetric Media for Augmented Reality](https://arxiv.org/pdf/1804.09864) [arxiv 18]
+ [Design, Implementation, and Evaluation of a Point Cloud Codec for Tele-Immersive Video](https://core.ac.uk/download/pdf/206494004.pdf)  [TCSVT 17]

### Virtual Reality
Several mediums for volumetric video including point cloud, mesh, voxel, NeRF, light fields, radiance fields.....
Virtual reality papers research how to render with low latency in edge/cloud architecture. They often render small objects in mobile devices and render heavy background in the server. 
NeRF-based Volumetric Video: \
+ [NeRFPlayer: A Streamable Dynamic Scene Representation with Decomposed Neural Radiance Fields](https://arxiv.org/abs/2210.15947)  [Arxiv 22]
+ [Streamable Neural Fields](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136800580.pdf) [ECCV 22]
+ [Streaming Radiance Fields for 3D Video Synthesis](https://arxiv.org/pdf/2210.14831.pdf) [Nips 22]
6DoF VR Video
+ [Q-VR: System-Level Design for Future Mobile Collaborative Virtual Reality](https://arxiv.org/ftp/arxiv/papers/2102/2102.13191.pdf)  [ASPLOS 21]

+ [Coterie: Exploiting Frame Similarity to Enable High-Quality Multiplayer VR on Commodity Mobile](https://dl.acm.org/doi/abs/10.1145/3373376.3378516) [ASPLOS 20]
+ [Firefly: Untethered Multi-user VR for Commodity Mobile Devices](https://www.usenix.org/conference/atc20/presentation/liu-xing) [ATC 20]
+ [Mobile VR on Edge Cloud: A Latency-Driven Design](https://dl.acm.org/doi/10.1145/3304109.3306217) [MMSys 19]
+ [MUVR: Supporting Multi-User Mobile Virtual Reality with Resource Constrained Edge Cloud](https://ieeexplore.ieee.org/document/8567653/) [Egde Computing 18]
+ [Cutting the Cord: Designing a High-quality Untethered VR System with Low Latency Remote Rendering](https://dl.acm.org/doi/10.1145/3210240.3210313)  [MobiSys 18]
+ [Furion: Engineering High-Quality Immersive Virtual Reality on Today’s Mobile Devices](http://www.cse.psu.edu/~gxc27/teach/597/Furion.pdf) [Mobicom 17]
+ [CloudVR: Cloud Accelerated Interactive Mobile Virtual Reality](https://dl.acm.org/doi/pdf/10.1145/3240508.3240620)  [MM 17]
+ [Enabling High-Quality Untethered Virtual Reality](https://cs.uwaterloo.ca/~oabari/Papers/NSDI17.pdf) [NSDI 17]
+ [FlashBack: Immersive Virtual Reality on Mobile Devices via Rendering Memoization](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/flashback_mobisys2016.pdf) [MobiSys 16]


### Volumetric Video Datasets
Dynamic Point Cloud 
+ VOLVQAD: An MPEG V-PCC Volumetric Video Quality Assessment Dataset [MMSys 23]
+ A Dynamic Point Cloud Dataset for Immersive Applications [MMSys 23]
+ [FSVVD: A Dataset of Full Scene Volumetric Video](https://cuhksz-inml.github.io/full_scene_volumetric_video_dataset/) [MMSys 23]
+ A 6DoF VR Dataset of 3D VirtualWorld for Privacy-Preserving Approach and Utility-Privacy Tradeoff [MMSys 23]
+ [CWIPC-SXR: Point Cloud dynamic human dataset for Social XR](https://dl.acm.org/doi/pdf/10.1145/3458305.3478452) [MMSys 22]
+ [JPEG Pleno Database: 8i Voxelized Full Bodiess](http://plenodb.jpeg.org/pc/8ilabs/) [Dataset 17]
+ [JPEG Pleno Database: Microsoft Voxelized Upper Bodies - A Voxelized Point Cloud Datasets](http://plenodb.jpeg.org/pc/8ilabs/) [Dataset]
+ [Sketchfab](https://sketchfab.com/) [Website]

Others:
+ [JPEG Pleno Database](http://plenodb.jpeg.org/) [Website]


### Quality of Experience
+ [Rebuffering but not Suffering: Exploring Continuous-Time Quantitative QoE by User's Exiting Behaviors]() [INFOCOM 23]
+ [Adaptive Bitrate with User-level QoE Preference for Video Streaming]() [Infocom 22]
+ [VSiM: Improving QoE Fairness for Video Streaming in Mobile Environments]() [Infocom 22]
+ [360ProbDASH: Improving QoE of 360 Video Streaming Using Tile-based HTTP 
Adaptive Streaming]() [Infocom 22]
+ [CLS: A Cross-user Learning based System for Improving QoE in 360-degree Video 
Adaptive Streaming]() [Infocom 22]
+ [360°Mulsemedia: A Way to Improve Subjective QoE in 360° Videos]() [Infocom 22]
+ [Lumos: towards Better Video Streaming QoE through Accurate Throughput
Prediction]() [Infocom 22]
+ [Coal Not Diamonds: How Memory Pressure Falters Mobile Video QoE]() [CoNext'22]
+ [XLINK: QoE-Driven Multi-Path QUIC Transport in Large-scale Video Services]() [SIGCOMM'21]
+ [End-to-End Transport for Video QoE Fairness]() [SIGCOMM 20]
+ [Impact of Device Performance on Mobile Internet QoE]() [IMC'18]
+ [Intelligent Edge-Assisted Crowdcast with Deep Reinforcement Learning for Personalized QoE] (Infocom 19)
+ [Rldish: Edge-Assisted QoE Optimization of HTTP Live Streaming with Reinforcement Learning]() [Infocom 20]



### Video Processing
Back to [Table of Contents](#table-of-contents)
### Video Analysis
* RECL: Responsive Resource-Efficient Continuous Learning for Video Analytics [NSDI 23]
* Boggart: Towards General-Purpose Acceleration of Retrospective Video Analytics [NSDI 23]
* Gemel: Model Merging for Memory-Efficient, Real-Time Video Analytics at the Edge [NSDI 23]
* SEPE Dataset: K Video Sequences and Images for Analysis and Development [MMSys 23]
* [Minimizing packet retransmission for real-time video analytics](https://alex-q-z.github.io/files/saliency_hotmobile22.pdf) [SoCC 23]
* [Crowd^2: Multi-agent Bandit-based Dispatch for Video Analytics upon Crowdsourcing]() [INFOCOM 23]
* [Owl: A Pre-and Post-processing Framework for Video Analytics in Low-light Surroundings]() [INFOCOM 23]
* [AccMPEG: Optimizing Video Encoding for Accurate Video Analytics](https://proceedings.mlsys.org/paper/2022/file/98f13708210194c475687be6106a3b84-Paper.pdf) [MLSys 22]
* [DAO: Dynamic Adaptive Offloading for Video Analytics](https://dl.acm.org/doi/pdf/10.1145/3503161.3548249) [MM'22]
* [Ekya: Continuous Learning of Video Analytics Models on Edge Compute Servers](https://www.usenix.org/system/files/nsdi22-paper-bhardwaj.pdf) [NSDI 22]
* [Privid: Practical, Privacy-Preserving Video Analytics Queries](https://www.usenix.org/conference/nsdi22/presentation/cangialosi) [NSDI 22]
* [Understanding the Potential of Server-Driven Edge Video Analytics](https://dl.acm.org/doi/pdf/10.1145/3542929.3563502) [HotMobile 22]
* [Video Analytics with Zero-streaming Cameras](https://www.usenix.org/conference/atc21/presentation/xu) [ATC 21]
* [Elf: Accelerate High-resolution Mobile Deep Vision with Content-aware Parallel Offloading](https://www.msra.cn/wp-content/uploads/2021/03/mobicom21-elf.pdf) [ATC 21]
* [Enabling Edge-Cloud Video Analytics for Robotic Applications](https://www.usenix.org/system/files/nsdi22-paper-bhardwaj.pdf) [TCC 22]
* [Enabling Edge-Cloud Video Analytics for Robotic Applications](https://www.cse.ust.hk/~ywanggf/public/files/runespoor-infocom21.pdf) [INFOCOM'21]
* [Real-Time Deep Video Analytics on Mobile Devices](https://dl.acm.org/doi/pdf/10.1145/3466772.3467037) [MobiHoc'21]
* [Soudain: Online Adaptive Profile Configuration for Real-time Video Analytics](https://dl.acm.org/doi/pdf/10.1145/3466772.3467037) [IWQoS'21]
* [CrossRoI: Cross-camera Region of Interest Optimization for Efficient Real Time Video Analytics at Scale](https://dl.acm.org/doi/pdf/10.1145/3458305.3463381) [MMSys'21]
* [Vision Paper: Towards Software-Defined Video Analytics with Cross-Camera Collaboration](https://dl.acm.org/doi/pdf/10.1145/3485730.3493453) [SenSys'21]
* [Server-Driven Video Streaming for Deep Learning Inference](https://people.cs.uchicago.edu/~junchenj/docs/DDS-Sigcomm20.pdf) [SIGCOMM'20]
* [Distream: scaling live video analytics with workload-adaptive distributed edge intelligence](https://dl.acm.org/doi/pdf/10.1145/3384419.3430721) [Sensys'20]
* [Reducto: On-Camera Filtering for Resource-Efficient Real-Time Video Analytics](http://web.cs.ucla.edu/~harryxu/papers/li-sigcomm20.pdf) [SIGCOMM'20]
* [Joint Configuration Adaptation and Bandwidth Allocation for Edge-based Real-time Video Analytics](https://ieeexplore.ieee.org/document/9155524) [Infocom'20]
* [Scaling Video Analytics on Constrained Edge Nodes](https://hyeontaek.com/papers/ff-sysml2019.pdf) [SysML'19]
* [AWStream: adaptive wide-area streaming analytics](https://awstream.github.io/paper/awstream.pdf) [SIGCOMM'18]
* [Chameleon: Scalable Adaptation of Video Analytics](http://people.cs.uchicago.edu/~junchenj/docs/Chameleon_SIGCOMM_CameraReady.pdf) [SIGCOMM'18]
* [Focus: Querying Large Video Datasets with Low Latency and Low Cost](https://www.usenix.org/system/files/osdi18-hsieh.pdf) [OSDI'18]
* [Live Video Analytics at Scale with Approximation and Delay-Tolerance](https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/zhang) [NSDI'17]
* [Glimpse: Continuous, Real-Time Object Recognition on Mobile Devices](https://dl.acm.org/doi/10.1145/2809695.2809711) [Sensys'15]
* [The Design and Implementation of a Wireless Video Surveillance System](https://old.sigmobile.org/mobicom/2015/papers/p426-zhangA.pdf) [Mobicom'15]

### Video Analysis for 3D Vision
* [DeepMix: Mobility-aware, Lightweight, and Hybrid 3D Object Detection for Headsets](https://arxiv.org/abs/2201.08812) [Mobisys'22]
* [Hybrid Mobile Vision for Emerging Applications](https://www-users.cse.umn.edu/~fengqian/paper/hybrid_vision_hotmobile22.pdf) [HotMobile'22]

### Video Coding with Deep Learning
This part is also known Neural video compression:
This [repo](https://ustc-fvc.github.io/deep-compression.html) is currently the most comprehensive list of papers about image/video coding with deep learning
* Structure-Preserving Motion Estimation for Learned Video Compression [MM'22]
* Learning-Based Video Coding with Joint Deep Compression and Enhancement [MM'22]
* [Efficient Video Compression via Content-Adaptive Super-Resolution](https://openaccess.thecvf.com/content/ICCV2021/papers/Khani_Efficient_Video_Compression_via_Content-Adaptive_Super-Resolution_ICCV_2021_paper.pdf) [ICCV'21] [[Code](https://github.com/AdaptiveVC/SRVC)]
* [Online-trained Upsampler for Deep Low Complexity Video Compression](https://openaccess.thecvf.com/content/ICCV2021/papers/Klopp_Online-Trained_Upsampler_for_Deep_Low_Complexity_Video_Compression_ICCV_2021_paper.pdf) [ICCV'21]
* [ELF-VC: Efficient Learned Flexible-Rate Video Coding](https://arxiv.org/pdf/2104.14335.pdf) [arxiv'21]
* [Learning for Video Compression with Hierarchical Quality and Recurrent Enhancement](https://arxiv.org/pdf/2003.01966.pdf) [CVPR'20]
* [Learned Video Compression](https://arxiv.org/pdf/1811.06981.pdf) [ICCV'19]
* [DVC: An End-to-end Deep Video Compression Framework](https://github.com/GuoLusjtu/DVC) [CVPR'19]
* [Deep Learning-Based Video Coding: A Review and A Case Study](https://arxiv.org/pdf/1904.12462.pdf) [arxiv'19]
* [Video Compression through Image Interpolation](https://www.philkr.net/papers/2018-09-02-eccv/2018-09-02-eccv.pdf) [ECCV'18]

A list of summary of represented works for interested readers:

1. end to end optimized image compression(End-to-end VAE)
2. Hyperprior(modeling p(y,z|x), intro the distribution of prior hyperparameter)
3. Joint Autoregressive and Hierarchical Priors for Learned Image Compression 
4. Integer Network for data compression with latent variable models
5. channel wise autoregressive entropy models for learned image compression(diferent slice model slice dependence gg20c)
6. learned image compression with discretized gaussian mixture likehoods and attention moduels(GMM entropy model + attention cheng2020)
7. context adaptive entropy model for end to end optimized image compression(bits consuming and bits free entropy model)
8. Learned Variable-Rate Multi-Frequency Image Compression using Modulated Generalized Octave Convolution(lamda sigmoid)
9. Variable Rate Deep Image Compression With a Conditional Autoencoder（using lambda to fine model parameters，conditional autoencoder）
10. YOU ONLY TRAIN ONCE: LOSS-CONDITIONAL TRAINING OF DEEP NETWORKS（conditional training）
11. A Hybriad image codec with learned residuals(local attention，octave convolution, residual compression)
12. Learned image compression with residual coding
13. End-to-End Learned ROI Image Compression(encoder + importance map)
14. Learning Convolutional Networks for Content-weighted Image Compression(importance map + binary feature map)
15. Conditional probability model for deep image compression
16. generative adversarial networks for extreme learned image compression
17. towards conceptual compression（convolutional hyperprior）
18. Learn to inpaint for image compression(inpaint + residual compression)
19. deep generative models for distribution preserving lossy compression(gan)

### Volumetric Video Coding and Compression

### Other Video Coding
* [Revisiting Video Saliency: A Large-scale Benchmark and a New Model](https://zpascal.net/cvpr2018/Wang_Revisiting_Video_Saliency_CVPR_2018_paper.pdf) [CVPR'18]
* [A semiautomatic saliency model and its application to video compression](http://compression.ru/video/savam/pdf/A_semiautomatic_saliency_model_and_its_application_to_video_compression_ICCP_2017_0.pdf) [ICCP'17]

### Multimedia 3D Processing

* [AccuMO: Accuracy-Centric Multitask Offloading in Edge-Assisted Mobile Augmented Reality]() [MobiCom'23]
* [MetaStream: Live Volumetric Content Capture, Creation, Delivery, and Rendering in Real Time]() [MobiCom'23]

### Security and Privacy Related

[Unique Identification of 50,000+ Virtual Reality Users from Head & Hand Motion Data](https://arxiv.org/pdf/2302.08927.pdf) [Arxiv 23]

### Video Classification
* [YouTube-8M: A Large-Scale Video Classification
Benchmark](https://arxiv.org/pdf/1609.08675.pdf)[arxiv'16]
* [Beyond Short Snippets: Deep Networks for Video Classification](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Ng_Beyond_Short_Snippets_2015_CVPR_paper.pdf) [CVPR'15]
* [Large-scale Video Classification with Convolutional Neural Networks](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/42455.pdf) [CVPR'14]


## Tools
Back to [Table of Contents](#table-of-contents)
Following are the tools and libraries that are useful to build your ideas on top of.
## Multimedia Libraries
* [FFMPEG](https://ffmpeg.org/): A multimedia library with a collection of diverse video codecs, filters, and video streaming capabilities.
* [GPAC](https://github.com/gpac/gpac): A multimedia library that has decoding, rendering and displaying support. It also has support for 360 degree video delivery. It comes with MP4Box to package the video into DASH format segments and MP4Client a video player with adaptive video streaming solutions
* [x265](https://github.com/videolan/x265): Open source implementation H.265 video codec.
* [OBS Studio](https://obsproject.com/): Open source broadcaster software. It is useful to stream live videos on platforms such as Facebook and Periscope etc.
* [SVT Encoders](https://github.com/OpenVisualCloud): Software (multithreaded CPU) implementation of HEVC, VP9 and AV1 encoders.
* [Saliency-aware Video Codec](https://github.com/msu-video-group/x264_saliency_mod): X264 implementation of saliency-aware video compression.
* [SHVC](https://hevc.hhi.fraunhofer.de/shvc): Layered coding - scalable extentions for H.265/HEVC
* [SVC](https://avc.hhi.fraunhofer.de/svc): Layered coding - scalable extensions for H.264/AVC
* [VVC](https://jvet.hhi.fraunhofer.de/): Reference implementation of H.266/VVC 

## Multimedia Libraries
* [NeRFstudio](https://github.com/nerfstudio-project/nerfstudio): A collaboration friendly studio for NeRFs
* [FFMPEG](https://ffmpeg.org/): A multimedia library with a collection of diverse video codecs, filters, and video streaming capabilities.
* [GPAC](https://github.com/gpac/gpac): A multimedia library that has decoding, rendering and displaying support. It also has support for 360 degree video delivery. It comes with MP4Box to package the video into DASH format segments and MP4Client a video player with adaptive video streaming solutions
* [x265](https://github.com/videolan/x265): Open source implementation H.265 video codec.
* [OBS Studio](https://obsproject.com/): Open source broadcaster software. It is useful to stream live videos on platforms such as Facebook and Periscope etc.
* [SVT Encoders](https://github.com/OpenVisualCloud): Software (multithreaded CPU) implementation of HEVC, VP9 and AV1 encoders.
* [Saliency-aware Video Codec](https://github.com/msu-video-group/x264_saliency_mod): X264 implementation of saliency-aware video compression.
* [SHVC](https://hevc.hhi.fraunhofer.de/shvc): Layered coding - scalable extentions for H.265/HEVC
* [SVC](https://avc.hhi.fraunhofer.de/svc): Layered coding - scalable extensions for H.264/AVC
* [VVC](https://jvet.hhi.fraunhofer.de/): Reference implementation of H.266/VVC 


