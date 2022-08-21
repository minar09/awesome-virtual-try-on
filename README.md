# A Curated List of Awesome Virtual Try-on (VTON) Research
A curated list of awesome research papers, projects, code, dataset, workshops etc. related to virtual try-on (VTON).

- [Image-based (2D) Virtual Try-on](#Image-based-2D-Virtual-Try-on)
- [3D Virtual Try-on](#3D-virtual-try-on)
- [Multi-Pose Guided Virtual Try-on](#Multi-Pose-Guided-Virtual-Try-on)
- [Video Virtual Try-on](#Video-Virtual-Try-on)
- [Non-clothing Virtual Try-on](#non-clothing-virtual-try-on)
- [Pose-Guided Human Synthesis](#pose-guided-human-synthesis)
- [Datasets for Virtual Try-on](#Datasets-for-Virtual-Try-on)
- [Related Conference Workshops](#Related-Conference-Workshops)
- [Demos](#Demos)
- [Related Repositories](#Related-Repositories)


## Image-based (2D) Virtual Try-on
  #### CVPRW 2022
  - Dress Code: High-Resolution Multi-Category Virtual Try-On - [Paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Morelli_Dress_Code_High-Resolution_Multi-Category_Virtual_Try-On_CVPRW_2022_paper.pdf), [Code/Data](https://github.com/aimagelab/dress-code)
  #### WACV 2022
  - C-VTON: Context-Driven Image-Based Virtual Try-On Network - [Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Fele_C-VTON_Context-Driven_Image-Based_Virtual_Try-On_Network_WACV_2022_paper.pdf), [Code/Model/Data](https://github.com/benquick123/C-VTON)
  #### ECCV 2022
  - High-Resolution Virtual Try-On with Misalignment and Occlusion-Handled Conditions - [Paper](https://arxiv.org/abs/2206.14180), [Code/Model](https://github.com/sangyun884/HR-VITON)
  - Single Stage Virtual Try-on via Deformable Attention Flows - [Paper](https://arxiv.org/abs/2207.09161), [Code/Model](https://github.com/OFA-Sys/DAFlow)
  #### CVPR 2022
  - Style-Based Global Appearance Flow for Virtual Try-On - [Paper](https://arxiv.org/abs/2204.01046), [Code/Model](https://github.com/SenHe/Flow-Style-VTON)
  - Weakly Supervised High-Fidelity Clothing Model Generation - [Paper](https://arxiv.org/pdf/2112.07200.pdf), [Code/Model](https://github.com/RuiLiFeng/Deep-Generative-Projection)
  - Dressing in the Wild by Watching Dance Videos - [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Dong_Dressing_in_the_Wild_by_Watching_Dance_Videos_CVPR_2022_paper.html), [Project](https://awesome-wflow.github.io/)
  #### ICCV 2021
  - Dressing in Order: Recurrent Person Image Generation for Pose Transfer, Virtual Try-on and Outfit Editing - [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Cui_Dressing_in_Order_Recurrent_Person_Image_Generation_for_Pose_Transfer_ICCV_2021_paper.pdf), [Code](https://github.com/cuiaiyu/dressing-in-order)
  - ZFlow: Gated Appearance Flow-based Virtual Try-on with 3D Priors - [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Chopra_ZFlow_Gated_Appearance_Flow-Based_Virtual_Try-On_With_3D_Priors_ICCV_2021_paper.pdf)
  - FashionMirror: Co-attention Feature-remapping Virtual Try-on with Sequential Template Poses - [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_FashionMirror_Co-Attention_Feature-Remapping_Virtual_Try-On_With_Sequential_Template_Poses_ICCV_2021_paper.pdf)
  #### CVPR 2021
  - Parser-Free Virtual Try-on via Distilling Appearance Flows - [Paper](https://arxiv.org/pdf/2103.04559.pdf), [Code/Data/Model](https://github.com/geyuying/PF-AFN)
  - VITON-HD: High-Resolution Virtual Try-On via Misalignment-Aware Normalization - [Paper](https://arxiv.org/pdf/2103.16874.pdf), [Code/Model](https://github.com/shadow2496/VITON-HD)
  - Disentangled Cycle Consistency for Highly-realistic Virtual Try-On - [Paper](https://arxiv.org/pdf/2103.09479.pdf), [Code/Data/Model](https://github.com/ChongjianGE/DCTON)
  - Toward Accurate and Realistic Outfits Visualization with Attention to Details - [Paper](https://arxiv.org/abs/2106.06593), [Demo](https://revery.ai/demo.html)

  #### ACCV 2020
  - CloTH-VTON: Clothing Three-dimensional reconstruction for Hybrid image-based Virtual Try-ON - [Paper](https://openaccess.thecvf.com/content/ACCV2020/html/Minar_CloTH-VTON_Clothing_Three-dimensional_reconstruction_for_Hybrid_image-based_Virtual_Try-ON_ACCV_2020_paper.html), [Project](https://minar09.github.io/clothvton/)

  #### ECCV 2020
  - Do Not Mask What You Do Not Need to Mask: a Parser Free Virtual Try-On - [Paper](https://arxiv.org/pdf/2007.02721.pdf)

  #### CVPR 2020
  - Towards Photo-Realistic Virtual Try-On by Adaptively Generating↔Preserving Image Content - [Paper/Code/Data](https://github.com/switchablenorms/DeepFashion_Try_On)
  - Image Based Virtual Try-On Network From Unpaired Data - [Paper](http://openaccess.thecvf.com/content_CVPR_2020/html/Neuberger_Image_Based_Virtual_Try-On_Network_From_Unpaired_Data_CVPR_2020_paper.html)
  - Semantically Multi-modal Image Synthesis - [Paper/Code/Model](https://seanseattle.github.io/SMIS/)

  #### CVPRW 2020
  - CP-VTON+: Clothing Shape and Texture Preserving Image-Based Virtual Try-On - [Paper/Code/Data/Model](https://minar09.github.io/cpvtonplus/)
  - 3D Reconstruction of Clothes using a Human Body Model and its Application to Image-based Virtual Try-On - [Paper/Project](https://minar09.github.io/c3dvton/)

  #### ICCV 2019
  - VTNFP: An Image-Based Virtual Try-On Network With Body and Clothing Feature Preservation - [Paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Yu_VTNFP_An_Image-Based_Virtual_Try-On_Network_With_Body_and_Clothing_ICCV_2019_paper.html)
  - ClothFlow: A Flow-Based Model for Clothed Person Generation - [Paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Han_ClothFlow_A_Flow-Based_Model_for_Clothed_Person_Generation_ICCV_2019_paper.html)

  #### ICCVW 2019
  - UVTON: UV Mapping to Consider the 3D Structure of a Human in Image-Based Virtual Try-On Network, [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Kubo_UVTON_UV_Mapping_to_Consider_the_3D_Structure_of_a_ICCVW_2019_paper.html)
  - LA-VITON: A Network for Looking-Attractive Virtual Try-On - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Lee_LA-VITON_A_Network_for_Looking-Attractive_Virtual_Try-On_ICCVW_2019_paper.html)
  - Robust Cloth Warping via Multi-Scale Patch Adversarial Loss for Virtual Try-On Framework - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/HBU/Ayush_Robust_Cloth_Warping_via_Multi-Scale_Patch_Adversarial_Loss_for_Virtual_ICCVW_2019_paper.html)
  - Powering Virtual Try-On via Auxiliary Human Segmentation Learning - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Ayush_Powering_Virtual_Try-On_via_Auxiliary_Human_Segmentation_Learning_ICCVW_2019_paper.html)
  - Generating High-Resolution Fashion Model Images Wearing Custom Outfits - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Yildirim_Generating_High-Resolution_Fashion_Model_Images_Wearing_Custom_Outfits_ICCVW_2019_paper.html)

  #### ECCV 2018
  - Toward Characteristic-Preserving Image-based Virtual Try-On Network - [Paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Bochao_Wang_Toward_Characteristic-Preserving_Image-based_ECCV_2018_paper.pdf), [Code](https://github.com/sergeywong/cp-vton)
  - SwapNet: Garment Transfer in Single View Images - [Paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Amit_Raj_SwapNet_Garment_Transfer_ECCV_2018_paper.pdf), [Code (community contribution)](https://github.com/andrewjong/SwapNet)

  #### CVPR 2018
  - VITON: An Image-based Virtual Try-on Network - [Paper](https://arxiv.org/abs/1711.08447), [Code/Model](https://github.com/xthan/VITON)

  #### Others
  - A Flow-Based Generative Network for Photo-Realistic Virtual Try-On, IEEE Access 2022 - [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9757136), [Code/Model/Data](https://github.com/gxl-groups/FVNT)
  - Cross-category Virtual Try-on Technology Research Based on PF-AFN, ICVIP 2021 - [Paper](https://dl.acm.org/doi/pdf/10.1145/3511176.3511201?casa_token=RY8suIYfg-8AAAAA:ce3F43Et11IaFISkObmvOedFz5FrH0B6QnSHPu3Ro8_GEOLKGdf8qoww1RY5V9zdGm7T9sxpND15Wcs)
  - Virtual Try-on Network With Attribute Transformation and Local Rendering, IEEE TRANSACTIONS ON MULTIMEDIA, 2021 - [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9397349&casa_token=q6ADdrsxPToAAAAA:5_PjUtYaX9d37HGetPpsvpQApUMhfCitOIOAlDpCSqW57AbRLc3Z3M0CR4vdbHsvdaEQ4qbYTkI)
  - Transform, Warp, and Dress: A New Transformation-guided Model for Virtual Try-on, ACM Trans. Multimedia Comput. Commun. Appl. 2022 - [Paper](https://dl.acm.org/doi/pdf/10.1145/3491226?casa_token=7bTieMExNlkAAAAA%3AjGDdaeAR0HQ-M0ZO2u3olmaVjf3W_XtVgK5wPdgKiPhLP4F1yRUA28c7teapiVedba5FlPrfBTSvnC4)
  - Towards Scalable Unpaired Virtual Try-On via Patch-Routed Spatially-Adaptive GAN, NeurIPS 2021. - [Paper](https://arxiv.org/abs/2111.10544)
  - Arbitrary Virtual Try-On Network: Characteristics Preservation and Trade-off between Body and Clothing - [Paper](https://arxiv.org/abs/2111.12346)
  - PT-VTON: an Image-Based Virtual Try-On Network with Progressive Pose Attention Transfer - [Paper](https://arxiv.org/abs/2111.12167)
  - Data Augmentation using Random Image Cropping for High-resolution Virtual Try-On (VITON-CROP) - [Paper](https://arxiv.org/abs/2111.08270)
  - Per Garment Capture and Synthesis for Real-time Virtual Try-on, UIST 2021 - [Paper](https://arxiv.org/abs/2109.04654), [Project](https://sites.google.com/view/deepmannequin/home)
  - WAS-VTON: Warping Architecture Search for Virtual Try-on Network - [Paper](https://arxiv.org/abs/2108.00386), [Code/Model](https://github.com/xiezhy6/WAS-VTON)
  - Shape Controllable Virtual Try-on for Underwear Models - [Paper](https://arxiv.org/abs/2107.13156)
  - Cloth Interactive Transformer for Virtual Try-On - [Paper](https://arxiv.org/abs/2104.05519), [Code/Model](https://github.com/Amazingren/CIT)
  - CloTH-VTON+: Clothing Three-dimensional reconstruction for Hybrid image-based Virtual Try-ON, IEEE Access 2021 - [Paper](https://ieeexplore.ieee.org/document/9354778), [Project](https://minar09.github.io/clothvtonplus/)
  - VITON-GT: An Image-based Virtual Try-On Model with Geometric Transformations, ICPR 2020 - [Paper](https://iris.unimore.it/retrieve/312578/2020_ICPR_Virtual_Try_On.pdf)
  - TryOnGAN: Body-Aware Try-On via Layered Interpolation, SIGGRAPH 2021 - [Paper/Project](https://tryongan.github.io/tryongan/)
  - VOGUE: Try-On by StyleGAN Interpolation Optimization - [Paper/Project](https://vogue-try-on.github.io/)
  - Deep Virtual Try-on with Clothes Transform, ICS 2018 - [Paper](https://link.springer.com/chapter/10.1007/978-981-13-9190-3_22), [Code](https://github.com/b01902041/Deep-Virtual-Try-on-with-Clothes-Transform)
  - NDNet: Natural Deformation Of Apparel For Better Virtual Try-On Experience, ACM SAC 2021
  - Keypoints-Based 2D Virtual Try-on Network System, JAKO 2020 - [Paper](https://www.koreascience.or.kr/article/JAKO202010163508810.pdf)
  - Virtual Try-On With Generative Adversarial Networks: A Taxonomical Survey - [Book chapter](https://www.igi-global.com/chapter/virtual-try-on-with-generative-adversarial-networks/260791)
  - LGVTON: A Landmark Guided Approach to Virtual Try-On - [Paper](https://arxiv.org/abs/2004.00562v1), [Code](https://github.com/dp-isi/LGVTON)
  - SieveNet: A Unified Framework for Robust Image-Based Virtual Try-On, WACV 2020 - [Paper](http://openaccess.thecvf.com/content_WACV_2020/html/Jandial_SieveNet_A_Unified_Framework_for_Robust_Image-Based_Virtual_Try-On_WACV_2020_paper.html), [Code/Model (community contribution)](https://github.com/levindabhi/SieveNet)
  - GarmentGAN: Photo-realistic Adversarial Fashion Transfer - [Paper](https://arxiv.org/abs/2003.01894)
  - Toward Accurate and Realistic Virtual Try-on Through Shape Matching and Multiple Warps - [Paper](https://arxiv.org/abs/2003.10817)
  - FashionFit Analysis of Mapping 3D Pose and neural body fit for custom virtual try-on, IEEE Access 2020 - [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9091008)
  - Inpainting-Based Virtual Try-on Network for Selective Garment Transfer, IEEE Access 2019 - [Paper](https://ieeexplore.ieee.org/document/8836494)
  - SP-VITON: shape-preserving image-based virtual try-on network, Multimedia Tools and Applications 2019 - [Paper](https://link.springer.com/article/10.1007/s11042-019-08363-w)
  - VITON-GAN: Virtual Try-on Image Generator Trained with Adversarial Loss, Eurographics 2019 Posters - [Paper](https://arxiv.org/abs/1911.07926v1), [Code/Model](https://github.com/shionhonda/viton-gan)
  - Image-Based Virtual Try-on Network with Structural Coherence, ICIP 2019 - [Paper](https://ieeexplore.ieee.org/document/8803811)
  - End-to-End Learning of Geometric Deformations of Feature Maps for Virtual Try-On - [Paper](https://arxiv.org/abs/1906.01347v2)
  - M2E-Try On Net: Fashion from Model to Everyone - [Paper](https://arxiv.org/abs/1811.08599v1)



## 3D Virtual Try-on

  #### WACV 2022
  - Robust 3D Garment Digitization from Monocular 2D Images for 3D Virtual Try-On Systems - [Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Majithia_Robust_3D_Garment_Digitization_From_Monocular_2D_Images_for_3D_WACV_2022_paper.pdf)
  #### ICCV 2021
  - M3D-VTON: A Monocular-to-3D Virtual Try-On Network - [Paper](https://arxiv.org/abs/2108.05126), [Code](https://github.com/fyviezhao/M3D-VTON)
  #### CVPR 2021
  - Self-Supervised Collision Handling via Generative 3D Garment Models for Virtual Try-On - [Paper](https://arxiv.org/abs/2105.06462), [Project](http://mslab.es/projects/SelfSupervisedGarmentCollisions/), [Code](https://github.com/isantesteban/vto-garment-collisions)
  #### ECCV 2020
  - BCNet: Learning Body and Cloth Shape from A Single Image - [Paper](https://arxiv.org/pdf/2004.00214.pdf), [Code/Data](https://github.com/jby1993/BCNet)
  - GAN-based Garment Generation Using Sewing Pattern Images - [Paper/Code/Model/Data](https://gamma.umd.edu/researchdirections/virtualtryon/garmentgeneration/)
  - Deep Fashion3D: A Dataset and Benchmark for 3D Garment Reconstruction from Single Images - [Paper/Data](https://kv2000.github.io/2020/03/25/deepFashion3DRevisited/)
  - SIZER: A Dataset and Model for Parsing 3D Clothing and Learning Size Sensitive 3D Clothing - [Paper/Code/Data](https://virtualhumans.mpi-inf.mpg.de/sizer/)
  - CLOTH3D: Clothed 3D Humans - [Paper](https://arxiv.org/pdf/1912.02792.pdf)

  #### CVPR 2020
  - Learning to Transfer Texture from Clothing Images to 3D Humans - [Paper/Code](http://virtualhumans.mpi-inf.mpg.de/pix2surf/)
  - TailorNet: Predicting Clothing in 3D as a Function of Human Pose, Shape and Garment Style - [Paper/Code/Data](http://virtualhumans.mpi-inf.mpg.de/tailornet/)
  - Learning to Dress 3D People in Generative Clothing - [Paper/Code/Data](https://cape.is.tue.mpg.de/)

  #### ICCV 2019
  - Multi-Garment Net: Learning to Dress 3D People from Images - [Paper/Code/Data](http://virtualhumans.mpi-inf.mpg.de/mgn/)
  - 3DPeople: Modeling the Geometry of Dressed Humans - [Paper](https://arxiv.org/abs/1904.04571)
  - GarNet: A Two-Stream Network for Fast and Accurate 3D Cloth Draping - [Paper/Data](https://www.epfl.ch/labs/cvlab/research/garment-simulation/garnet/)

  #### ECCV 2018
  - DeepWrinkles: Accurate and Realistic Clothing Modeling - [Paper](https://arxiv.org/abs/1808.03417)

  #### CVPR 2018
  - Video Based Reconstruction of 3D People Models - [Paper/Code/Data](http://gvv.mpi-inf.mpg.de/projects/wxu/VideoAvatar/)

  #### Others
  - Point-Based Modeling of Human Clothing - [Paper](https://arxiv.org/pdf/2104.08230.pdf)
  - CloTH-VTON+: Clothing Three-dimensional reconstruction for Hybrid image-based Virtual Try-ON, IEEE Access 2021 - [Paper](https://ieeexplore.ieee.org/document/9354778), [Project](https://minar09.github.io/clothvtonplus/)
  - Physically Based Neural Simulator for Garment Animation - [Paper](https://arxiv.org/pdf/2012.11310.pdf)
  - GarNet++: Improving Fast and Accurate Static3D Cloth Draping by Curvature Loss, IEEE T-PAMI, 2020 - [Paper](https://arxiv.org/abs/2007.10867)
  - DeepCloth: Neural Garment Representation for Shape and Style Editing - [Paper](https://arxiv.org/abs/2011.14619)
  - CloTH-VTON: Clothing Three-dimensional reconstruction for Hybrid image-based Virtual Try-ON, ACCV 2020 - [Paper](https://openaccess.thecvf.com/content/ACCV2020/html/Minar_CloTH-VTON_Clothing_Three-dimensional_reconstruction_for_Hybrid_image-based_Virtual_Try-ON_ACCV_2020_paper.html), [Project](https://minar09.github.io/clothvton/)
  - Fully Convolutional Graph Neural Networks for Parametric Virtual Try-On, ACM SCA 2020 - [Paper/Project](http://mslab.es/projects/FullyConvolutionalGraphVirtualTryOn)
  - DeePSD: Automatic Deep Skinning And Pose Space Deformation For 3D Garment Animation - [Paper](https://arxiv.org/pdf/2009.02715.pdf)
  - 3D Reconstruction of Clothes using a Human Body Model and its Application to Image-based Virtual Try-On, CVPRW 2020 - [Paper/Project](https://minar09.github.io/c3dvton/)
  - Learning-Based Animation of Clothing for Virtual Try-On, Eurographics 2019 - [Paper/Project](http://dancasas.github.io/projects/LearningBasedVirtualTryOn/index.html), [Code](https://github.com/isantesteban/vto-learning-based-animation)
  - Learning an Intrinsic Garment Space for Interactive Authoring of Garment Animation, SIGGRAPH Asia 2019 - [Paper/Code](http://geometry.cs.ucl.ac.uk/projects/2019/garment_authoring/)
  - 3D Virtual Garment Modeling from RGB Images, ISMAR 2019 - [Paper](https://arxiv.org/abs/1908.00114)
  - Deep Garment Image Matting for a Virtual Try-on System, ICCVW 2019 - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Shin_Deep_Garment_Image_Matting_for_a_Virtual_Try-on_System_ICCVW_2019_paper.html)
  - Learning a Shared Shape Space for Multimodal Garment Design, SIGGRAPH Asia 2018 - [Paper/Code/Data](http://geometry.cs.ucl.ac.uk/projects/2018/garment_design/)
  - Detailed Garment Recovery from a Single-View Image, ACM TOG 2018 - [Paper](https://arxiv.org/abs/1608.01250)
  - ClothCap: Seamless 4D Clothing Capture and Retargeting, SIGGRAPH 2017 - [Paper](http://clothcap.is.tue.mpg.de/)
  - Virtual Try-On through Image-Based Rendering, IEEE T-VCG 2013 - [Paper](https://ieeexplore.ieee.org/document/6487501)
  - Markerless Garment Capture, ACM TOG 2008 - [Paper/Data](http://www.cs.ubc.ca/labs/imager/tr/2008/MarkerlessGarmentCapture/)




## Multi-Pose Guided Virtual Try-on

- SPG-VTON: Semantic Prediction Guidance for Multi-pose Virtual Try-on - [Paper](https://arxiv.org/abs/2108.01578)
- Down to the Last Detail: Virtual Try-on with Fine-grained Details, ACM MM 2020 - [Paper](https://dl.acm.org/doi/pdf/10.1145/3394171.3413514), [Code/Model](https://github.com/JDAI-CV/Down-to-the-Last-Detail-Virtual-Try-on-with-Detail-Carving), [ArXiv](https://arxiv.org/abs/1912.06324v2)
- Towards Multi-pose Guided Virtual Try-on Network, ICCV 2019 - [Paper](https://arxiv.org/abs/1902.11026), [Code](https://github.com/thaithanhtuan/MyMGVTON)
- FIT-ME: IMAGE-BASED VIRTUAL TRY-ON WITH ARBITRARY POSES, ICIP 2019 - [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8803681&casa_token=2CL5K9pwy1IAAAAA:OTa5P-h6RWj9BdQVvkxQURR8tDy4Eg1BZynYOizMyQACnE-zL_EHu2xRzyXBOWijP_cItaO4)
- Virtually Trying on New Clothing with Arbitrary Poses, ACM MM 2019 - [Paper](https://dl.acm.org/doi/pdf/10.1145/3343031.3350946?casa_token=w7EzejnZIaEAAAAA:KvDBsi1xYswuQuzEdJO-rsTDvysnSLYlAYi1J2st5lf8lnyotm5-umPKQupGaMEPUGxyBzijUkA9)
- FashionOn: Semantic-guided Image-based Virtual Try-on with Detailed Human and Clothing Information, ACM MM 2019 - [Paper](https://dl.acm.org/doi/pdf/10.1145/3343031.3351075?casa_token=7y85FCo6B-QAAAAA:diZbVYmcSK13bMQ94MzrMG_-VvVG_oNFoGpI8wCBFJ_dHEzYnLBAPn2ZwbAgj_pmOWFMD6_1hOuk)

  
  
  
## Video Virtual Try-on

- MV-TON: Memory-based Video Virtual Try-on network, ACM MM 2021 - [Paper](https://arxiv.org/abs/2108.07502)
- ShineOn: Illuminating Design Choices for Practical Video-based Virtual Clothing Try-on, WACV 2021 Workshop - [Project/Paper/Code](https://gauravkuppa.github.io/publication/2021-01-09-shine-on-1)
- FW-GAN: Flow-Navigated Warping GAN for Video Virtual Try-On, ICCV 2019 - [Paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Dong_FW-GAN_Flow-Navigated_Warping_GAN_for_Video_Virtual_Try-On_ICCV_2019_paper.html)
- Unsupervised Image-to-Video Clothing Transfer, ICCVW 2019 - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Pumarola_Unsupervised_Image-to-Video_Clothing_Transfer_ICCVW_2019_paper.html)
- Garment Replacement in Monocular Video Sequences, ACM TOG 2014 - [Paper](https://dl.acm.org/doi/10.1145/2634212)


## Non-clothing Virtual Try-on
- Deep Graphics Encoder for Real-Time Video Makeup Synthesis from Example, CVPRW 2021 - [Paper](https://arxiv.org/pdf/2105.06407.pdf)
- FITTINTM - Online 3D Shoe Try-on, 3DBODY.TECH 2020 - [Paper](http://www.3dbodyscanning.org/cap/papers/2020/2058revkov.pdf)
- CA-GAN: Weakly Supervised Color Aware GAN for Controllable Makeup Transfer - [Paper](https://arxiv.org/pdf/2008.10298.pdf)
- Regularized Adversarial Training for Single-Shot Virtual Try-On, ICCVW 2019 - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Kikuchi_Regularized_Adversarial_Training_for_Single-Shot_Virtual_Try-On_ICCVW_2019_paper.html)
- Disentangled Makeup Transfer with Generative Adversarial Network - [Paper](https://arxiv.org/pdf/1907.01144v1.pdf)
- PIVTONS: Pose Invariant Virtual Try-On Shoe with Conditional Image Completion, ACCV 2018 - [Paper](https://winstonhsu.info/wp-content/uploads/2018/09/chou18PIVTONS.pdf)
- Virtual Try-on of Eyeglasses using 3D Model of the Head - [Paper](https://dl.acm.org/doi/pdf/10.1145/2087756.2087838)
- A MIXED REALITY SYSTEM FOR VIRTUAL GLASSES TRY-ON - [Paper](https://dl.acm.org/doi/pdf/10.1145/2087756.2087816)
- A virtual try-on system in augmented reality using RGB-D cameras for footwear personalization - [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0278612514000594)




## Pose-Guided Human Synthesis
- InsetGAN for Full-Body Image Generation, CVPR 2022. - [Paper](https://arxiv.org/abs/2203.07293), [Project](http://afruehstueck.github.io/insetgan)
- Dressing in the Wild by Watching Dance Videos, CVPR 2022 - [Paper](https://arxiv.org/abs/2203.15320), [Project](https://awesome-wflow.github.io/)
- Pose with Style: Detail-Preserving Pose-Guided Image Synthesis with Conditional StyleGAN, SIGGRAPH Asia 2021 - [Paper](https://arxiv.org/abs/2109.06166), [Project](https://pose-with-style.github.io/)
- PoNA: Pose-Guided Non-Local Attention for Human Pose Transfer, IEEE T-IP 2020 - [Paper](https://ieeexplore.ieee.org/abstract/document/9222550)
- Pose-Guided High-Resolution Appearance Transfer via Progressive Training - [Paper](https://arxiv.org/pdf/2008.11898.pdf)
- Recapture as You Want - [Paper](https://arxiv.org/pdf/2006.01435.pdf)
- Generating Person Images with Appearance-aware Pose Stylizer, IJCAI 2020 - [Paper](https://arxiv.org/pdf/2007.09077.pdf), [Code](https://github.com/siyuhuang/PoseStylizer)
- Controllable Person Image Synthesis with Attribute-Decomposed GAN, CVPR 2020 - [Paper](https://arxiv.org/pdf/2003.12267.pdf), [Code](https://github.com/menyifang/ADGAN)
- Deep Image Spatial Transformation for Person Image Generation, CVPR 2020 - [Paper](https://arxiv.org/pdf/2003.00696v2.pdf), [Code](https://github.com/RenYurui/Global-Flow-Local-Attention)
- Neural Pose Transfer by Spatially Adaptive Instance Normalization, CVPR 2020 - [Paper](https://arxiv.org/pdf/2003.07254v2.pdf), [Code](https://github.com/jiashunwang/Neural-Pose-Transfer)
- Guided Image-to-Image Translation with Bi-Directional Feature Transformation, ICCV 2019 - [Paper](https://arxiv.org/pdf/1910.11328v1.pdf), [Code](https://github.com/vt-vl-lab/Guided-pix2pix)
- Liquid Warping GAN: A Unified Framework for Human Motion Imitation, Appearance Transfer and Novel View Synthesis, ICCV 2019 - [Paper](https://arxiv.org/pdf/1909.12224.pdf), [Code](https://github.com/svip-lab/impersonator)
- ClothFlow: A Flow-Based Model for Clothed Person Generation, ICCV 2019 - [Paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Han_ClothFlow_A_Flow-Based_Model_for_Clothed_Person_Generation_ICCV_2019_paper.html)
- Progressive Pose Attention for Person Image Generation, CVPR 2019 - [Paper](https://arxiv.org/pdf/1904.03349.pdf), [Code](https://github.com/tengteng95/Pose-Transfer)
- Dense Intrinsic Appearance Flow for Human Pose Transfer, CVPR 2019 - [Paper](https://arxiv.org/pdf/1903.11326v1.pdf), [Code](https://github.com/ly015/intrinsic_flow)
- Unsupervised Person Image Generation with Semantic Parsing Transformation, CVPR 2019, TPAMI 2020 - [Paper](https://arxiv.org/pdf/1904.03379.pdf), [Code](https://github.com/SijieSong/person_generation_spt)
- Pose Guided Fashion Image Synthesis Using Deep Generative Model - [Paper](https://arxiv.org/pdf/1906.07251.pdf)
- Synthesizing Images of Humans in Unseen Poses, CVPR 2018 - [Paper](https://arxiv.org/pdf/1804.07739.pdf), [Code](https://github.com/balakg/posewarp-cvpr2018)
- Soft-Gated Warping-GAN for Pose-Guided Person Image Synthesis, NeurIPS 2018 - [Paper](https://arxiv.org/pdf/1810.11610.pdf)
- Deformable GANs for Pose-based Human Image Generation, CVPR 2018 - [Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Siarohin_Deformable_GANs_for_CVPR_2018_paper.pdf)
- Pose-Normalized Image Generation for Person Re-identification, ECCV 2018 - [Paper](https://arxiv.org/pdf/1712.02225.pdf)
- Disentangled Person Image Generation, CVPR 2018 - [Paper/Code/Data](https://homes.esat.kuleuven.be/~liqianma/CVPR18_DPIG/index.html)
- A Variational U-Net for Conditional Appearance and Shape Generation, CVPR 2018 - [Paper](https://arxiv.org/pdf/1804.04694.pdf), [Code](https://github.com/CompVis/vunet)
- Human Appearance Transfer, CVPR 2018 - [Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zanfir_Human_Appearance_Transfer_CVPR_2018_paper.pdf)
- Pose guided person image generation, NeurIPS 2017 - [Paper](https://arxiv.org/pdf/1705.09368.pdf), [Code](https://github.com/charliememory/Pose-Guided-Person-Image-Generation)




## Datasets for Virtual Try-on

- VITON - [Download](https://drive.google.com/file/d/1MxCUvKxejnwWnoZ-KoCyMCXo3TLhRuTo/view), [Paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Han_VITON_An_Image-Based_CVPR_2018_paper.pdf)
- MPV - [Download](https://drive.google.com/drive/folders/1e3ThRpSj8j9PaCUw8IrqzKPDVJK_grcA), [Paper](https://arxiv.org/abs/1902.11026)
- Deep Fashion3D - [Paper](https://arxiv.org/abs/2003.12753)
- DeepFashion MultiModal - [Download](https://github.com/yumingj/DeepFashion-MultiModal)
- Digital Wardrobe - [Download/Paper/Project](http://virtualhumans.mpi-inf.mpg.de/mgn/)
- TailorNet Dataset - [Download](https://github.com/zycliao/TailorNet_dataset), [Project](http://virtualhumans.mpi-inf.mpg.de/tailornet/)
- CLOTH3D - [Paper](https://arxiv.org/abs/1912.02792)
- 3DPeople - [Project](https://www.albertpumarola.com/research/3DPeople/index.html)
- THUman Dataset - [Project](http://www.liuyebin.com/deephuman/deephuman.html)
- Garment Dataset, Wang et al. 2018 - [Project](http://geometry.cs.ucl.ac.uk/projects/2018/garment_design/)




## Related Conference Workshops

- Workshop on Computer Vision for Fashion, Art and Design: [CVPR 2022](https://sites.google.com/view/cvfad2022/home), [CVPR 2021](https://sites.google.com/zalando.de/cvfad2021/home), [CVPR 2020](https://sites.google.com/view/cvcreative2020), [ICCV 2019](https://sites.google.com/view/cvcreative), [ECCV 2018](https://sites.google.com/view/eccvfashion)
- Workshop on Towards Human-Centric Image/Video Synthesis: [CVPR 2020](https://vuhcs.github.io/), [CVPR 2019](https://vuhcs.github.io/vuhcs-2019/index.html)




## Demos

- Looklet Dressing Room [Business](https://looklet.com), [Demo](https://dressing-room.looklet.com)




## Related Repositories

- [awesome-fashion-ai](https://github.com/ayushidalmia/awesome-fashion-ai)
- [Cool Fashion Papers](https://github.com/lzhbrian/Cool-Fashion-Papers)
- [Clothes-3D](https://github.com/lzhbrian/Clothes-3D)
- [Awesome 3D Human](https://github.com/lijiaman/awesome-3d-human)
- [Awesome 3D reconstruction list](https://github.com/openMVG/awesome_3DReconstruction_list)
- [Human Body Reconstruction](https://github.com/chenweikai/Body_Reconstruction_References)
- [Awesome 3D Body Papers](https://github.com/3DFaceBody/awesome-3dbody-papers)


#### Pull requests are welcome!
