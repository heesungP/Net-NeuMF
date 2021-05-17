# Node2Vec_NCF
for KIISS

### 실험 결과 K=10

|모델(64emb)|precision|recall|
|:--------:|:------:|:------:|
|base-[1]|0.2477|0.6095|
|base-[2]|0.2463|0.6072|
|node-[1]|0.2502|0.6126|
|node-[2]|0.2506|0.6116|



|모델(128emb)|precision|recall|
|:--------:|:------:|:------:|
|base-[1]|0.2513|0.6145|
|base-[2]|0.2479|0.6091|
|node-[1]|0.2498|0.6126|

- base : modified version (NeuMF.py)
- node : apply user and item embedding in mlp layer (NeuMF_node_nogmf.py)

### data/
- 필요한 데이터 여기로

### pretrain/
- 모델 여기에 저장해서 불러오기


### No module named 'gensim'
```
conda install -c anaconda gensim
```


### update history

[사용안함] base-NCF-00.ipynb (in code_history/)

-> lookup table 설정(전체 데이터셋)과 
output 뽑을때 cat code로 evaluation 진행하여
수정했음 -> base-NCF-00-mod.ipynb
