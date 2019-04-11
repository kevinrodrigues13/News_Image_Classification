# News_Image_Classification

## Required Dependencies
```
Cuda
Python
Pytorch
```
## Step to train model

` python Train.py --cuda `

## Step to test model
` python Pred.py --image_dir test --model model_best.pth.tar --output_csvpath result.csv --cuda `

## Step to create visualztions on predictions from model 
`python Resultvisualization.py`
