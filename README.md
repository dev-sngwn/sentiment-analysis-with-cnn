# CNN을 이용한 한국어 영화 리뷰 감정 분석기
![ex screenshot](./img/model.png)
- CNN을 활용한 한국어 영화 리뷰 감정 분석기

## Requirements
- Keras
- Numpy
- [BPEmb](https://github.com/bheinzerling/bpemb)
  
## Dataset
- [Naver Sentiment Movie Corpus v1.0](https://github.com/e9t/nsmc)

## Performance
　|(2,3,4,5)|(7,7,7,7)|(2,3,4,5)+SPT|(7,7,7,7)+SPT|(2,3,4,5)+NSPT|(7,7,7,7)+NSPT|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Acc|85.8|-|-|-|-|-|

- SPT: Static Pre-Trained Weight
- NSPT: Non-Static Pre-Trained Weight


    
## Reference
- [A Sensitivity Analysis of (and Practitioners' Guide to) Convolutional Neural Networks for Sentence Classification](https://arxiv.org/abs/1510.03820)

## License
