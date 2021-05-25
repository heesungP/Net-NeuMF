# Node2Vec_NCF
for KIISS

#  ■ Net-NeuMF model structure
![image](https://user-images.githubusercontent.com/67678405/119464566-d199a080-bd7d-11eb-9f7f-8677b4848d84.png)


### 실험 결과 K=10

|Emb|Model|Precision|Recall|mAP|nDCG|
|:--------:|:------:|:------:|:------:|:------:|:------:|
|32|NeuMF|0.2452|0.5991|0.4215|0.5523|
|32|Net-NeuMF|0.2459|0.6023|0.4256|0.5571|
|64|NeuMF|0.2474|0.6058|0.4304|0.5652|
|64|Net-NeuMF|0.2516|0.6121|0.4404|0.5690|
|128|NeuMF|0.2504|0.6131|0.4487|0.5743|
|128|Net-NeuMF|0.2510|0.6144|0.4495|0.5785|



### data/
- 필요한 데이터 여기로

### pretrain/
- 모델 여기에 저장해서 불러오기


### No module named 'gensim'
```
conda install -c anaconda gensim
```

