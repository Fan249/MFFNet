# MFFNet (Multi-Feature Fusion network)
This repository is the implementaion of our paper "MFFNet: Single Facial Depth Map Refinement Using
Multi-level Feature Fusion".  
  
models/MFF_s3_deploy.prorotxt - network structure (3 stages)  
models/MFF_s3_midd.caffemodel - trained model for middlebury dataset (3 stages)  
models/MFF_s3_syn.caffemodel - trained model for synthetic facial depth dataset (3 stages)  
result/*.png - results on middlebury dataset.  


# Citation
The code and associated files are provided for academic research purposes only. If you find the code useful, please cite:  
```
@article{zhang2022mffnet,
  title={MFFNet: Single facial depth map refinement using multi-level feature fusion},
  author={Zhang, Fan and Liu, Na and Hu, Yongli and Duan, Fuqing},
  journal={Signal Processing: Image Communication},
  volume={103},
  pages={116649},
  year={2022},
  publisher={Elsevier}
}
```

# Dependencies
The models are trained with Caffe and tested on Matlab using MatCaffe. 

