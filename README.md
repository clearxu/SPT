# Please note that this repository does not contain any information about any of the authors!




## SPT
### SPT official implementation.
To do：
- [x] Model Code
- [ ] Training code (Coming soon)
- [ ] Testing code (Coming soon)
- [ ] Trained Model (Coming soon)

### Environment:

Option 1:

- Install pytorch

 `conda install pytorch==1.10.1 torchvision==0.11.2 torchaudio=0.10.1 cudatoolkit=10.2 -c pytorch`

- Install the mmsegmentation library and some required packages.

 `pip install mmcv-full==1.4.4 mmsegmentation==0.24.0`
 `pip install scipy timm==0.3.2`


### Downloading and preprocessing Dataset:
According to MMseg: https://github.com/open-mmlab/mmsegmentation/blob/master/docs/en/dataset_prepare.md

### Preparing Pretrained CLIP model:
Download the pretrained model here: Path/to/ViT-B-16.pt
https://openaipublic.azureedge.net/clip/models/5806e77cd80f8b59890b7e101eabd078d9fb84e6937f9e85e4ecb61988df416f/ViT-B-16.pt



### Related Assets \& Acknowledgement

Our work is closely related to the following assets that inspire our implementation. We gratefully thank the authors. 

 - CLIP:  https://github.com/openai/CLIP
 - Maskformer: https://bowenc0221.github.io/maskformer
 - Zegformer: https://github.com/dingjiansw101/ZegFormer
 - zsseg: https://github.com/MendelXu/zsseg.baseline
 - MaskCLIP: https://github.com/chongzhou96/MaskCLIP
 - SegViT: https://github.com/zbwxp/SegVit
 - DenseCLIP: https://github.com/raoyongming/DenseCLIP/blob/master/segmentation/denseclip
 - Visual Prompt Tuning: https://github.com/KMnP/vpt
 - ZegCLIP: https://github.com/ZiqinZhou66/ZegCLIP
 
