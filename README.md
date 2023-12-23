# PixelDream
Class Project for Computer Vision

## Setup
Create a new conda environment
```
conda create --name myenv

```
Activate the conda environment
```
conda activate myenv
```
Install the required packages using the requirements.txt file
```
pip install -r requirements.txt
```

## Downloading the checkpoints
The base checkpoint can be downloaded here : https://drive.google.com/file/d/1MxrmTXib5JSLN8RdjG_1hsAC5ahgT9Hc/view?usp=drive_link

The LoRA checkpoint can be downloaded here : https://drive.google.com/file/d/1HzlFKp9uwAZfvmm9Z3BNxd7nenD1YM3D/view?usp=drive_link

## Inference
Modify the paths in the inference.py and they should point to the downloaded checkpoint files
```
python inference.py
```
This will generate and save the image in the same directory

## Training
Run the bash file and training parameters can be adjusted according to the required training parameters
```
bash train.sh
```
