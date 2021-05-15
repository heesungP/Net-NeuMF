# Node2Vec_NCF
for KIISS

### 실험 결과 K=10

|모델(32emb)|precision|recall|
|:--------:|:------:|:------:|
|base-[1]|0.2427|0.5935|
|base-[2]|0.2440|0.5978|


|모델(64emb)|precision|recall|
|:--------:|:------:|:------:|
|base-[1]|0.2477|0.6095|
|base-[2]|0.2463|0.6072|
|node-[1*]|0.2481|0.6088|
|node-[2*]|0.2476|0.6103|


|모델(128emb)|precision|recall|
|:--------:|:------:|:------:|
|base-[1]|0.2513|0.6145|
|base-[2]|0.2479|0.6091|
|node-[1*]|0.2429|0.6078|
|node-[2*]|0.2431|0.6041|

- base : modified version
- \* : course의 embedding만 반영된 결과 (2,862개)
- \** : trainable = False의 결과

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
