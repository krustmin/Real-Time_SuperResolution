# Real-Time Super Resolution Ver.3.0 # 
 - This code aims to convert FHD to 4K within 60 FPS on low-level GPUs or low-level NPU.
 - In this version, FHD to 4K real-time (60 FPS) operation is possible on the nvida gtx 1060 without optimization(float32)
 - It is not necessary to use TensorCore for real-time opration. (cuda is enough)
 - Model Compression has not done. (pruning, disillation or other technic)
 - Based on the profiler, inference speed for FHD to 4K is 5ms with rtx 3xxx seriese(float32) 
 - Support various denoising.


# ToDO #
 - Support Real-Time Diffusion.
 - Support Colorization, Restoration
  
 - Testing on low-level AMD GPU.
 - I/O optimization for my hobby inference code.
 - Support video player version filter.
 
 - Replace existing images with ver.3.0 images.


# Real-Time Super Resolution (Ver.1.0 + 2.0) (Complete) # 

~~- This code aims to convert FHD to 4K within 60 FPS on low-level GPUs or low-level NPU~~

~~- Support various denoising.~~



### Animations ###
- Source : Blu-ray Disc
- FHD to 4K

![output_00002900](https://user-images.githubusercontent.com/24447550/177022256-6b882bb8-8f13-4284-9f17-75d2c4d79967.jpg)


### Movies ##
- Source : Youtube
- FHD to 4K

![output_00000053](https://user-images.githubusercontent.com/24447550/177022263-b1604f0b-2c3e-4b20-904d-c91717a059b7.jpg)
![output_00001610](https://user-images.githubusercontent.com/24447550/177022268-f699fa2b-5a5b-43ec-bc59-7f9bc336c7b2.jpg)
![output_00000510](https://user-images.githubusercontent.com/24447550/177022270-c35b2488-7127-4a70-8c75-278157b8971d.jpg)


### Extra - Classic Game broadcast ###
- Source : Youtube, provided by ott
- 360p to 720p

<img width="955" alt="game" src="https://user-images.githubusercontent.com/24447550/177022272-cfdc3b5c-e97c-469f-97f4-d931aa052f25.png">



