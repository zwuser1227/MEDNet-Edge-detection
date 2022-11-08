# MEDNet

This repository contains the Implementation details of the paper "Edge detection networks inspired by neural mechanisms of selective attention in biological visual cortex".
The address of the paper is at ()

## Citations
If you are using the code/model/data provided here in a publication, please consider citing our paper:
```

```
## Get Start
1、Download our code.<br/>
2、prepare the dataset.<br/>
3、Configure the environment.<br/>
4、If Windows system, please modify the dataset in cfgs.yaml.<br/>
5、Run the "train.py".<br/>

文件夹中包含模型文件（model.py）
训练用文件（train.py）
测试用文件(test,py)
以及其他相关文件(cfgs...)

The folder contains model files (model.py)<br/>
training files (train.py)<br/>
testing files (test.py) and other related files (cfgs ...). 
## Result
BSDS：Test results of this model on BSDS500 data set.<br/>
NYUD：Test results of this model on NYUD data set.<br/>
BIPED：Test results of this model on BIPED data set.<br/>
Other data and procedures will be made public after the paper is received.

## Datsets
We use the links in [RCF](https://github.com/yun-liu/rcf) Repository (really thanks for that).
The augmented BSDS500, PASCAL VOC, and NYUD datasets can be downloaded with:<br/>
```
  wget http://mftp.mmcheng.net/liuyun/rcf/data/HED-BSDS.tar.gz
  wget http://mftp.mmcheng.net/liuyun/rcf/data/PASCAL.tar.gz
  wget http://mftp.mmcheng.net/liuyun/rcf/data/NYUD.tar.gz
```

We use the links in [DexiNed](https://github.com/xavysp/DexiNed) Repository (really thanks for that).<br/>
We used the first version before the second version came out.<br/>
MBIPED Dataset is Here:
```
  https://drive.google.com/drive/folders/1lZuvJxL4dvhVGgiITmZsjUJPBBrFI_bM?usp=sharing
```

Test results on dataset MBIPED:
<center>

|     Methods    |    ODS   |    ODS   |    AP    |
| -------------- | ---------| -------- | -------- |
| [RCF](https://github.com/yun-liu/rcf)      | `.849` | `.861` | `.906` |
| [BDCN](https://github.com/pkuCactus/BDCN)     | `.890` | `.899` | `.934` |
| [DexiNed-f](https://github.com/xavysp/DexiNed)  | `.895` | `.900` | `.927` |
| [DexiNed-a](https://github.com/xavysp/DexiNed)  | `.893` | `.897` | `.940` |
| MEDNet-a-SS| `.896` | `.900` | `.920` |

</center>

# Reference and Acknowledgments
When building our codeWe referenced the repositories as follow:<br/>
1.[DRC](https://github.com/cyj5030/DRC-Release)
2.[RCF](https://github.com/yun-liu/rcf)
3.[HED](https://github.com/xwjabc/hed)
4.[DexiNed](https://github.com/xavysp/DexiNed)