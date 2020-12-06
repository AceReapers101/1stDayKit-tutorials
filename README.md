# Demonstrable 1stDayHack Notes
## FirstDayKit Installation (Google Colab)
```
!git clone https://github.com/1stDayHack/FDK.git
```
```
!cp -r FDK/* ./
!rm -rf FDK/
```
```
!pip install -r requirements.txt
```
```
OPTIONAL (If detectron2 is needed)
---------------------------------------
import torch
torch.__version__
!python -m pip install detectron2 -f \
https://dl.fbaipublicfiles.com/detectron2/wheels/cu101/torch1.7/index.html
```
```
OPTIONAL (If external model is needed)
---------------------------------------
!pip install gdown
!gdown <gdrive link>
!cp <filename> <path>
!rm <filename>
```
