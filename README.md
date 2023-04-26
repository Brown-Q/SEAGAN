## Environment
```
python==3.6.13
apex==0.1
pytorch==1.7.1
torch_geometric==2.0.2
networkx==2.5.1
cuda==11.2
```
## Running
```
1.download glove.6B.zip from https://nlp.stanford.edu/projects/glove/
2.unzip glove.6B.zip into data/ (glove.6B.300d.txt will be used)
3.CUDA_VISIBLE_DEVICES=0 python train.py --data data/DBP15K --lang EN_FR_15K_V1
```

