## Table of Contents

* [Datasets](#datasets)
  * [Video Datasets](#video-datasets)
  * [Image Datasets](#image-datasets)




## Datasets

### Video Datasets

|                     | Release  | Real Videos | Fake Videos | Video Source | Consent? | NumUID | NumGenAlgo | Public Download? |
| :-----------------: | :------: | :---------: | :---------: | :----------: | :------: | :----: | :--------: | :--------------: |
|    FaceForensics    | Mar 2018 |    1004     |    1004     |   YouTube  | N | 1004 | 2 | Y |
|        UADFV        | Nov 2018 |     49      |     49      | YouTube | N | 49 | 1 | ? |
|   Deepfake-TIMIT    | Dec 2018 |     320     |     640     | VidTIMIT | ? | 32 | 2| Y |
|   FaceForensics++   | Jan 2019 |    1000     |    4000     | YouTube | N | 977 | 4| Y |


* **FaceForensics**: [Github](https://github.com/ondyari/FaceForensics/tree/original)
  * Contains more than 500,000
  * Uses Face2Face
  * All videos are downloaded from Youtube and are cut down to short continuous clips that contain mostly frontal faces
  * Two versions: source-to-target or self-reenactment  
  * Frame rate: 30fps
  * Available in 3 quality: raw, HQ, LQ
  * Videos are at least 300 frames long (10s)

* **UADFV**: "Exposing Deep Fakes Using Inconsistent Head Poses." [Paper](https://arxiv.org/abs/1811.00661)
  * 21,694 training frames, 11,058 testing frames = 32,752
  * 30fps 
  * Avg duration 
  * Resolution 294x500
  * 1 Generation algorithm 
  * 1 face
  * Email access (not attempted) 
* **FaceForensic++**: "FaceForensics++: Learning to Detect Manipulated Facial Images." [Paper](https://arxiv.org/abs/1901.08971)    [GitHub](https://github.com/ondyari/FaceForensics)
  * We selected 1,000 video sequences containing 509, 914 images which we use as our pristine data
  * For our dataset, we chose two computer graphics-based approaches (Face2Face and FaceSwap) and two learning- based approaches (DeepFakes and NeuralTextures).
  * Besides the manipulation output, we also compute ground truth masks that indicate whether a pixel has been modified or not, which can be used to train forgery localization methods
  * Available in 3 quality: raw, HQ, LQ

* **EBV**: "In Ictu Oculi: Exposing AI Generated Fake Face Videos by Detecting Eye Blinking." [Paper](https://arxiv.org/abs/1806.02877)    [Download](http://www.cs.albany.edu/~lsw/downloads.html)
* **Deepfake-TIMIT**: "DeepFakes: a New Threat to Face Recognition? Assessment and Detection." [Paper](https://arxiv.org/abs/1812.08685)    [Download](https://conradsanderson.id.au/vidtimit/)
* **DFFD**: "DFFD: Diverse Fake Face Dataset." [Paper](http://cvlab.cse.msu.edu/dffd-diverse-fake-face-dataset.html)    [Download](http://cvlab.cse.msu.edu/dffd-dataset.html)
* **Wild Deepfake**: "WildDeepfake: A Challenging Real-World Dataset for Deepfake Detection." [Paper](https://arxiv.org/abs/2101.01456)    [Download](https://github.com/deepfakeinthewild/deepfake-in-the-wild)
* **Celeb-DF (v1)**: "Celeb-DF: A Large-scale Challenging Dataset for DeepFake Forensics." [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Celeb-DF_A_Large-Scale_Challenging_Dataset_for_DeepFake_Forensics_CVPR_2020_paper.pdf)    [Download](https://github.com/yuezunli/celeb-deepfakeforensics/tree/master/Celeb-DF-v1)
* **Celeb-DF (v2)**: "Celeb-DF: A Large-scale Challenging Dataset for DeepFake Forensics." [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Celeb-DF_A_Large-Scale_Challenging_Dataset_for_DeepFake_Forensics_CVPR_2020_paper.pdf)    [Download](https://github.com/yuezunli/celeb-deepfakeforensics/tree/master/Celeb-DF-v2)
* **DFDC**: "The DeepFake Detection Challenge (DFDC) Dataset." [Paper](https://arxiv.org/abs/2006.07397)    [Download](https://www.kaggle.com/c/deepfake-detection-challenge/data) 
* **Deeper Forensic**: "DeeperForensics-1.0: A Large-Scale Dataset for Real-World Face Forgery Detection." [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Jiang_DeeperForensics-1.0_A_Large-Scale_Dataset_for_Real-World_Face_Forgery_Detection_CVPR_2020_paper.pdf)    [Download](https://github.com/EndlessSora/DeeperForensics-1.0)
* **FaceForensic++**: "FaceForensics++: Learning to Detect Manipulated Facial Images." [Paper](https://arxiv.org/abs/1901.08971)    [Download](https://github.com/ondyari/FaceForensics)
* **DFGC**: "DFGC 2021: A DeepFake Game Competition." [Paper](https://arxiv.org/abs/2106.01217)    [Dowload](https://github.com/bomb2peng/DFGC_starterkit)
* **FFIW-10K**: "Face Forensics in the Wild." [Paper](https://arxiv.org/abs/2103.16076)    [Download](https://github.com/tfzhou/FFIW)
* **ForgeryNet**: "ForgeryNet: A Versatile Benchmark for Comprehensive Forgery Analysis." [Paper](https://arxiv.org/abs/2103.05630)    [Download](https://github.com/yinanhe/forgerynet)





### Image Datasets

* **DFFD**: "On the Detection of Digital Face Manipulation." [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Dang_On_the_Detection_of_Digital_Face_Manipulation_CVPR_2020_paper.pdf)    [Download](http://cvlab.cse.msu.edu/project-ffd.html)
* **FFHQ**: "A Style-Based Generator Architecture for Generative Adversarial Networks." [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Karras_A_Style-Based_Generator_Architecture_for_Generative_Adversarial_Networks_CVPR_2019_paper.pdf)    [Download](https://github.com/NVlabs/ffhq-dataset)
* **iFakeFaceDB**: "GANprintR: Improved Fakes and Evaluation of the State of the Art in Face Manipulation Detection." [Paper](https://arxiv.org/abs/1911.05351)    [Download](https://github.com/socialabubi/iFakeFaceDB)
* **100k Faces Generated by AI (Online)**: [Download](https://generated.photos/datasets)

|             | Real Images |    Fake Images     |
| :---------: | :---------: | :----------------: |
|    DFFD     |   58,703    |      240,336       |
|    FFHQ     |      -      | 70,000 (GAN-based) |
| iFakeFaceDB |      -      | 87,000 (StyleGAN)  |
| 100k Faces  |      -      | 100,000 (StyleGAN) |
| ForgeryNet  |  1,438,201  |     1,457,861      |



## Tools

* **Deepfakes-FaceSwap**: [Github](https://github.com/deepfakes/faceswap)
* **FaceSwap**: [Github](https://github.com/MarekKowalski/FaceSwap/)
* **dfaker**: [Github](https://github.com/dfaker/df)
* **FaceSwap-GAN**: [Github](https://github.com/shaoanlu/faceswap-GAN)
* **Face2Face**: [Github](https://github.com/datitran/face2face-demo)
* **DeepFaceLab**: [Github](https://github.com/iperov/DeepFaceLab)
* **DeepFaceLive**: [Github](https://github.com/iperov/DeepFaceLive)
* **FaceSwap Online**: [Website](https://faceswap.dev/)
* **MyVoiceYourFace**: [Website](https://myvoiceyourface.com/)
* **Online Deepfake Maker**: [Website](https://deepfakesweb.com/)
* **Online Deepfake Video Creator**: [Website](https://mmasked.com/)
* **Generated Photos**: [Website](https://generated.photos/)
