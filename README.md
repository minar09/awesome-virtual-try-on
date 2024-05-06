# A Curated List of Awesome Virtual Try-on (VTON) Research! <img src='awesome.png' width='37'>
A curated list of awesome research papers, projects, code, datasets, workshops, etc. related to virtual try-on (VTON).

- [Prompt-based Virtual Try-on](#Prompt-based-Virtual-Try-on)
- [Image-based (2D) Virtual Try-on](#Image-based-2D-Virtual-Try-on)
- [3D Virtual Try-on](#3D-virtual-try-on)
- [Mix-and-match Virtual Try-On](#Mix-and-match-Virtual-Try-on)
- [In-the-wild Virtual Try-On](#In-the-wild-Virtual-Try-on)
- [Multi-Pose Guided Virtual Try-on](#Multi-Pose-Guided-Virtual-Try-on)
- [Video Virtual Try-on](#Video-Virtual-Try-on)
- [Non-clothing Virtual Try-on](#non-clothing-virtual-try-on)
- [Pose-Guided Human Synthesis](#pose-guided-human-synthesis)
- [Datasets for Virtual Try-on](#Datasets-for-Virtual-Try-on)
- [Related Conference Workshops](#Related-Conference-Workshops)
- [Demos](#Demos)
- [Related Repositories](#Related-Repositories)


## Prompt-based Virtual Try-on
  #### ControlNet
  - [ControlNet](https://github.com/lllyasviel/ControlNet) - Hint: Use the clothing image as the image input and provide the human description in the text prompt or vice versa.
  - [EditAnything](https://github.com/sail-sg/EditAnything) - Hint: Use a reference fashion image as input and provide your desired changes in the text prompt.

  #### Stable-Diffusion
  - [Stable-DreamFusion](https://github.com/ashawkey/stable-dreamfusion) - Hint: Use the Image-conditioned 3D Generation option to edit your fashion images.
  - [ThreeStudio](https://github.com/threestudio-project/threestudio) - Hint: Use different models for generating output from the image-conditioned text prompts for fashion image editing.


## Image-based (2D) Virtual Try-on
  #### CVPR 2024
  - StableVITON: Learning Semantic Correspondence with Latent Diffusion Model for Virtual Try-On - [Project](https://rlawjdghek.github.io/StableVITON/), [Code/Data/Model](https://github.com/rlawjdghek/StableVITON)
  - CAT-DM: Controllable Accelerated Virtual Try-on with Diffusion Model - [Paper](https://arxiv.org/pdf/2311.18405.pdf), [Project](https://github.com/zengjianhao/CAT-DM)

  #### AAAI 2024
  - Towards Squeezing-Averse Virtual Try-On via Sequential Deformation - [Paper](https://arxiv.org/abs/2312.15861), [Code](https://github.com/SHShim0513/SD-VITON)
  
  #### WACV 2024
  - Wearing the Same Outfit in Different Ways -- A Controllable Virtual Try-on Method - [Paper](https://arxiv.org/abs/2211.16989)
  - GC-VTON: Predicting Globally Consistent and Occlusion Aware Local Flows with Neighborhood Integrity Preservation for Virtual Try-on - [Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Rawal_GC-VTON_Predicting_Globally_Consistent_and_Occlusion_Aware_Local_Flows_With_WACV_2024_paper.pdf)

  #### ICCV 2023
  - Multimodal Garment Designer: Human-Centric Latent Diffusion Models for Fashion Image Editing - [Paper](https://arxiv.org/abs/2304.02051), [Code](https://github.com/aimagelab/multimodal-garment-designer)
  - Size Does Matter: Size-aware Virtual Try-on via Clothing-oriented Transformation Try-on Network - [Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_Size_Does_Matter_Size-aware_Virtual_Try-on_via_Clothing-oriented_Transformation_Try-on_ICCV_2023_paper.pdf), [Code](https://github.com/cotton6/COTTON-size-does-matter)
  - Virtual Try-On with Pose-Garment Keypoints Guided Inpainting - [Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Virtual_Try-On_with_Pose-Garment_Keypoints_Guided_Inpainting_ICCV_2023_paper.pdf), [Code](https://github.com/lizhi-ntu/KGI)
  
  #### CVPR 2023
  - GP-VTON: Towards General Purpose Virtual Try-on via Collaborative Local-Flow Global-Parsing Learning - [Paper](https://arxiv.org/pdf/2303.13756.pdf), [Code](https://github.com/xiezhy6/GP-VTON), [Project](https://github.com/xiezhy6/GP-VTON)
  - Linking Garment with Person via Semantically Associated Landmarks for Virtual Try-On - [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Yan_Linking_Garment_With_Person_via_Semantically_Associated_Landmarks_for_Virtual_CVPR_2023_paper.pdf)
  - TryOnDiffusion: A Tale of Two UNets - [Paper](https://arxiv.org/pdf/2306.08276.pdf), [Project](https://tryondiffusion.github.io/)
  
  #### NeurIPS 2022
  - Towards Hard-pose Virtual Try-on via 3D-aware Global Correspondence Learning - [Paper](https://arxiv.org/pdf/2211.14052.pdf), [Project](https://neurips.cc/virtual/2022/poster/54642)
  
  #### WACV 2022
  - C-VTON: Context-Driven Image-Based Virtual Try-On Network - [Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Fele_C-VTON_Context-Driven_Image-Based_Virtual_Try-On_Network_WACV_2022_paper.pdf), [Code/Model/Data](https://github.com/benquick123/C-VTON)
  
  #### ECCV 2022
  - Dress Code: High-Resolution Multi-Category Virtual Try-On - [Paper](https://arxiv.org/pdf/2204.08532.pdf), [Code/Data](https://github.com/aimagelab/dress-code)
  - High-Resolution Virtual Try-On with Misalignment and Occlusion-Handled Conditions - [Paper](https://arxiv.org/abs/2206.14180), [Code/Model](https://github.com/sangyun884/HR-VITON)
  - Single Stage Virtual Try-on via Deformable Attention Flows - [Paper](https://arxiv.org/abs/2207.09161), [Code/Model](https://github.com/OFA-Sys/DAFlow)
  
  #### CVPR 2022
  - Full-Range Virtual Try-On with Recurrent Tri-Level Transform - [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_Full-Range_Virtual_Try-On_With_Recurrent_Tri-Level_Transform_CVPR_2022_paper.pdf), [Project](https://lzqhardworker.github.io/RT-VTON/)
  - Style-Based Global Appearance Flow for Virtual Try-On - [Paper](https://arxiv.org/abs/2204.01046), [Code/Model](https://github.com/SenHe/Flow-Style-VTON)
  - Weakly Supervised High-Fidelity Clothing Model Generation - [Paper](https://arxiv.org/pdf/2112.07200.pdf), [Code/Model](https://github.com/RuiLiFeng/Deep-Generative-Projection)
  - Dressing in the Wild by Watching Dance Videos - [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Dong_Dressing_in_the_Wild_by_Watching_Dance_Videos_CVPR_2022_paper.html), [Project](https://awesome-wflow.github.io/)
  
  #### CVPRW 2022
  - Dual-Branch Collaborative Transformer for Virtual Try-On - [Paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Fenocchi_Dual-Branch_Collaborative_Transformer_for_Virtual_Try-On_CVPRW_2022_paper.pdf)
  - Dress Code: High-Resolution Multi-Category Virtual Try-On - [Paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Morelli_Dress_Code_High-Resolution_Multi-Category_Virtual_Try-On_CVPRW_2022_paper.pdf), [Code/Data](https://github.com/aimagelab/dress-code)
  
  #### ICCV 2021
  - Dressing in Order: Recurrent Person Image Generation for Pose Transfer, Virtual Try-on and Outfit Editing - [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Cui_Dressing_in_Order_Recurrent_Person_Image_Generation_for_Pose_Transfer_ICCV_2021_paper.pdf), [Code](https://github.com/cuiaiyu/dressing-in-order), [Colab](https://colab.research.google.com/drive/1WfeKTPtt3qtlcTlrX47J03mxUzbVvyrL?usp=sharing)
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
  - Magic Clothing: Controllable Garment-Driven Image Synthesis - [Paper](https://arxiv.org/abs/2404.09512), [Code](https://github.com/ShineChen1024/MagicClothing)
  - IDM-VTON: Improving Diffusion Models for Authentic Virtual Try-on in the Wild - [Demo](https://huggingface.co/spaces/yisol/IDM-VTON), [Paper](https://arxiv.org/abs/2403.05139), [Project](https://idm-vton.github.io/)
  - OOTDiffusion: Outfitting Fusion based Latent Diffusion for Controllable Virtual Try-on - [Code](https://github.com/levihsu/OOTDiffusion)
  - Outfit Anyone: Ultra-high quality virtual try-on for Any Clothing and Any Person - [Project](https://humanaigc.github.io/outfit-anyone/)
  - Street TryOn: Learning In-the-Wild Virtual Try-On from Unpaired Person Images -[Paper](https://arxiv.org/pdf/2311.16094.pdf), [Data](https://github.com/cuiaiyu/street-tryon-benchmark)
  - FICE: Text-Conditioned Fashion Image Editing With Guided GAN Inversion - [Paper](https://arxiv.org/abs/2301.02110), [Code](https://github.com/martinpernus/fice)
  - OccluMix: Towards De-Occlusion Virtual Try-on by Semantically-Guided Mixup, TMM 2023 - [Paper](https://arxiv.org/abs/2301.00965), [Code](https://github.com/jychen9811/doc-vton)
  - Taming the Power of Diffusion Models for High-Quality Virtual Try-On with Appearance Flow, ACM Multimedia 2023 - [Paper](https://arxiv.org/abs/2308.06101), [Code](https://github.com/bcmi/DCI-VTON-Virtual-Try-On)
  - LaDI-VTON: Latent Diffusion Textual-Inversion Enhanced Virtual Try-On, ACM Multimedia 2023 - [Paper](https://arxiv.org/abs/2305.13501), [Code](https://github.com/miccunifi/ladi-vton)
  - Limb-Aware Virtual Try-On Network with Progressive Clothing Warping, IEEE Multimedia 2023 - [Paper](https://ieeexplore.ieee.org/abstract/document/10152500)
  - FashionTex: Controllable Virtual Try-on with Text and Texture, SIGGRAPH 2023 - [Paper](https://arxiv.org/pdf/2305.04451.pdf)
  - DreamPaint: Few-Shot Inpainting of E-Commerce Items for Virtual Try-On without 3D Modeling - [Paper](https://arxiv.org/pdf/2305.01257.pdf)
  - PG-VTON: A Novel Image-Based Virtual Try-On Method via Progressive Inference Paradigm - [Paper](https://arxiv.org/pdf/2304.08956.pdf), [Code](https://github.com/NerdFNY/PGVTON)
  - Fill in Fabrics: Body-Aware Self-Supervised Inpainting for Image-Based Virtual Try-On, BMVC 2022 - [Paper](https://arxiv.org/pdf/2210.00918.pdf), [Code/Model/Data](https://github.com/hasibzunair/fifa-tryon)
  - Probing TryOnGAN, CODS-COMAD 2022 - [Paper](https://arxiv.org/pdf/2201.01703.pdf)
  - FitGAN: Fit- and Shape-Realistic Generative Adversarial Networks for Fashion - [Paper](https://arxiv.org/pdf/2206.11768.pdf)
  - Spatial Transformation for Image Composition via Correspondence Learning - [Paper](https://arxiv.org/pdf/2207.02398.pdf)
  - PASTA-GAN++: A Versatile Framework for High-Resolution Unpaired Virtual Try-on - [Paper](https://arxiv.org/pdf/2207.13475.pdf)
  - Significance of Skeleton-based Features in Virtual Try-On - [Paper](https://arxiv.org/pdf/2208.08076.pdf)
  - You can try without visiting: a comprehensive survey on virtually try-on outfits, Multimedia Tools and Applications - [Paper](https://link.springer.com/article/10.1007/s11042-022-12802-6)
  - High fidelity virtual try-on network via semantic adaptation and distributed componentization, Computational Visual Media 2022 - [Paper](https://link.springer.com/content/pdf/10.1007/s41095-021-0264-2.pdf)
  - St-Vton: Self-Supervised Vision Transformer for Image-Based Virtual Try-On - [Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4140115)
  - Photo-Realistic Virtual Try-On with Enhanced Warping Module, Advances in Intelligent Systems and Computing 2022 - [Paper](https://link.springer.com/chapter/10.1007/978-981-16-5157-1_66)
  - Virtual Try-On Using Augmented Reality - [Paper](https://link.springer.com/chapter/10.1007/978-981-19-1122-4_54)
  - WG-VITON: Wearing-Guide Virtual Try-On for Top and Bottom Clothes - [Paper](https://arxiv.org/pdf/2205.04759.pdf)
  - VTNCT: an image-based virtual try-on network by combining feature with pixel transformation, The Visual Computer 2022 - [Paper](https://link.springer.com/article/10.1007/s00371-022-02480-8)
  - RMGN: A Regional Mask Guided Network for Parser-free Virtual Try-on, IJCAI-ECAI 2022 - [Paper](https://arxiv.org/pdf/2204.11258.pdf), [Code/Model/Data](https://github.com/jokerlc/RMGN-VITON)
  - A Flow-Based Generative Network for Photo-Realistic Virtual Try-On, IEEE Access 2022 - [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9757136), [Code/Model/Data](https://github.com/gxl-groups/FVNT)
  - An Efficient Style Virtual Try on Network for Clothing Business Industry - [Paper](https://arxiv.org/pdf/2105.13183.pdf)
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

  #### NeurIPS 2022
  - ULNeF: Untangled Layered Neural Fields for Mix-and-Match Virtual Try-On - [Paper](https://neurips.cc/virtual/2022/poster/53336), [Project](https://mslab.es/projects/ULNeF/)

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
  - DM-VTON: Distilled Mobile Real-time Virtual Try-On, ISMAR 2023 - [Paper](https://arxiv.org/abs/2308.13798), [Code](https://github.com/KiseKloset/DM-VTON)
  - Three stages of 3D virtual try-on network with appearance flow and shape field, The Visual Computer 2023 - [Paper](https://link.springer.com/article/10.1007/s00371-023-02946-3)
  - Robust 3D Garment Digitization from Monocular 2D Images for 3D Virtual Try-On Systems, 2021 - [Paper](https://arxiv.org/pdf/2111.15140.pdf)
  - REALISTIC MONOCULAR-TO-3D VIRTUAL TRY-ON VIA MULTI-SCALE CHARACTERISTICS CAPTURE, ICASSP 2022 - [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9747277&casa_token=EALQVtpxonwAAAAA:GKEdQBbsji39XrEgGiSk7pJWgRB1KAH2me79_hsuaPSYTUfVn76h3Jyavxuk57CCWI6HYPRhRUk)
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


## Mix-and-match Virtual Try-on
  - Wearing the Same Outfit in Different Ways -- A Controllable Virtual Try-on Method, WACV 2024 -[Paper](https://arxiv.org/abs/2211.16989)
  - Dressing in Order: Recurrent Person Image Generation for Pose Transfer, Virtual Try-on and Outfit Editing, ICCV 2021 -[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Cui_Dressing_in_Order_Recurrent_Person_Image_Generation_for_Pose_Transfer_ICCV_2021_paper.pdf), [Code](https://github.com/cuiaiyu/dressing-in-order), [Colab](https://colab.research.google.com/drive/1WfeKTPtt3qtlcTlrX47J03mxUzbVvyrL?usp=sharing)
  - Toward Accurate and Realistic Outfits Visualization with Attention to Details, CVPR 2021 -[Paper](https://arxiv.org/pdf/2106.06593.pdf)
  - Image Based Virtual Try-on Network from Unpaired Data, CVPR 2020 - [Paper](https://assets.amazon.science/1a/2b/7a4dd8264ce19a959559da799aff/scipub-1281.pdf), [Code](https://github.com/trinanjan12/Image-Based-Virtual-Try-on-Network-from-Unpaired-Data)

## In-the-wild Virtual Try-on
 - Street TryOn: Learning In-the-Wild Virtual Try-On from Unpaired Person Images -[Paper](https://arxiv.org/pdf/2311.16094.pdf), [Data](https://github.com/cuiaiyu/street-tryon-benchmark)
 - Dressing in the Wild by Watching Dance Videos, CVPR 2022 - [Paper](https://arxiv.org/abs/2203.15320), [Project](https://awesome-wflow.github.io/)

## Multi-Pose Guided Virtual Try-on

- CF-VTON: Multi-Pose Virtual Try-on with Cross-Domain Fusion, ICASSP 2023 - [Paper](https://ieeexplore.ieee.org/abstract/document/10095176)
- Multiple Pose Virtual Try-On Based on 3D Clothing Reconstruction, IEEE Access 2021 - [Paper](https://ieeexplore.ieee.org/document/9512041)
- SPG-VTON: Semantic Prediction Guidance for Multi-pose Virtual Try-on - [Paper](https://arxiv.org/abs/2108.01578)
- Down to the Last Detail: Virtual Try-on with Fine-grained Details, ACM MM 2020 - [Paper](https://dl.acm.org/doi/pdf/10.1145/3394171.3413514), [Code/Model](https://github.com/JDAI-CV/Down-to-the-Last-Detail-Virtual-Try-on-with-Detail-Carving), [ArXiv](https://arxiv.org/abs/1912.06324v2)
- Towards Multi-pose Guided Virtual Try-on Network, ICCV 2019 - [Paper](https://arxiv.org/abs/1902.11026), [Code](https://github.com/thaithanhtuan/MyMGVTON)
- FIT-ME: IMAGE-BASED VIRTUAL TRY-ON WITH ARBITRARY POSES, ICIP 2019 - [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8803681&casa_token=2CL5K9pwy1IAAAAA:OTa5P-h6RWj9BdQVvkxQURR8tDy4Eg1BZynYOizMyQACnE-zL_EHu2xRzyXBOWijP_cItaO4)
- Virtually Trying on New Clothing with Arbitrary Poses, ACM MM 2019 - [Paper](https://dl.acm.org/doi/pdf/10.1145/3343031.3350946?casa_token=w7EzejnZIaEAAAAA:KvDBsi1xYswuQuzEdJO-rsTDvysnSLYlAYi1J2st5lf8lnyotm5-umPKQupGaMEPUGxyBzijUkA9)
- FashionOn: Semantic-guided Image-based Virtual Try-on with Detailed Human and Clothing Information, ACM MM 2019 - [Paper](https://dl.acm.org/doi/pdf/10.1145/3343031.3351075?casa_token=7y85FCo6B-QAAAAA:diZbVYmcSK13bMQ94MzrMG_-VvVG_oNFoGpI8wCBFJ_dHEzYnLBAPn2ZwbAgj_pmOWFMD6_1hOuk)

  
  
  
## Video Virtual Try-on

- ClothFormer: Taming Video Virtual Try-on in All Module, CVPR 2022 - [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Jiang_ClothFormer_Taming_Video_Virtual_Try-On_in_All_Module_CVPR_2022_paper.pdf), [Code](https://github.com/luxiangju-PersonAI/ClothFormer), [Project](https://cloth-former.github.io/)
- MV-TON: Memory-based Video Virtual Try-on network, ACM MM 2021 - [Paper](https://arxiv.org/abs/2108.07502)
- ShineOn: Illuminating Design Choices for Practical Video-based Virtual Clothing Try-on, WACV 2021 Workshop - [Project/Paper/Code](https://gauravkuppa.github.io/publication/2021-01-09-shine-on-1)
- FW-GAN: Flow-Navigated Warping GAN for Video Virtual Try-On, ICCV 2019 - [Paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Dong_FW-GAN_Flow-Navigated_Warping_GAN_for_Video_Virtual_Try-On_ICCV_2019_paper.html)
- Unsupervised Image-to-Video Clothing Transfer, ICCVW 2019 - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Pumarola_Unsupervised_Image-to-Video_Clothing_Transfer_ICCVW_2019_paper.html)
- Garment Replacement in Monocular Video Sequences, ACM TOG 2014 - [Paper](https://dl.acm.org/doi/10.1145/2634212)

## Video-to-Image Virtual Try-on

- DPV-VTON : Detail-Preserving Video-based Virtual Try-On, ICMIP 2023 - [Paper](https://dl.acm.org/doi/10.1145/3599589.3599599) 


## Non-clothing Virtual Try-on
- Real-time Virtual-Try-On from a Single Example Image through Deep Inverse Graphics and Learned Differentiable Renderers, EUROGRAPHICS 2022 - [Paper](https://arxiv.org/pdf/2205.06305.pdf)
- ARShoe: Real-Time Augmented Reality Shoe Try-on System on Smartphones, ACM Multimedia 2021 - [Paper](https://arxiv.org/pdf/2108.10515.pdf)
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
- Cross Attention Based Style Distribution for Controllable Person Image Synthesis, ECCV 2022 - [Paper](https://arxiv.org/pdf/2208.00712.pdf)
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
- StreetTryOn - [Download](https://github.com/cuiaiyu/street-tryon-benchmark)
- CLOTH4D, CVPR 2023 - [Download](https://github.com/AemikaChow/CLOTH4D)
- DressCode - [Download](https://docs.google.com/forms/d/e/1FAIpQLSeWVzxWcj3JSALtthuw-2QDAbf2ymiK37sA4pRQD4tZz2vqsw/viewform), [Paper](https://arxiv.org/pdf/2204.08532.pdf)
- VITON-HD - [Download](https://www.dropbox.com/s/10bfat0kg4si1bu/zalando-hd-resized.zip?dl=0), [Project](https://psh01087.github.io/VITON-HD/)
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

- Outfit Anyone-in-the-Wild - [Demo](https://huggingface.co/spaces/selfit-camera/OutfitAnyone-in-the-Wild), [Docs](https://github.com/selfitcamera/Outfit-Anyone-in-the-Wild)
- Outfit Anyone - [Demo](https://huggingface.co/spaces/HumanAIGC/OutfitAnyone), [Docs](https://github.com/HumanAIGC/OutfitAnyone)
- Looklet Dressing Room [Business](https://looklet.com), [Demo](https://dressing-room.looklet.com)
- TINT platform for virtual try-on of everything face-related (makeup, glasses, earrings, jewelry, etc.) [Business](https://www.banuba.com/solutions/e-commerce/virtual-try-on), [Demo](https://banuba.com/solutions/e-commerce/virtual-makeup-demo/).




## Related Repositories

- [awesome-fashion-ai](https://github.com/ayushidalmia/awesome-fashion-ai)
- [Cool Fashion Papers](https://github.com/lzhbrian/Cool-Fashion-Papers)
- [Clothes-3D](https://github.com/lzhbrian/Clothes-3D)
- [Awesome 3D Human](https://github.com/lijiaman/awesome-3d-human)
- [Awesome 3D reconstruction list](https://github.com/openMVG/awesome_3DReconstruction_list)
- [Human Body Reconstruction](https://github.com/chenweikai/Body_Reconstruction_References)
- [Awesome 3D Body Papers](https://github.com/3DFaceBody/awesome-3dbody-papers)
- [Awesome pose transfer](https://github.com/Zhangjinso/Awesome-pose-transfer)


#### Pull requests are welcome!
