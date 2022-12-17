## 인공지능(AI, Artificial intelligence)

### 인공지능 개요

+ 인공지능은 사람의 지능을 필요로 하는 작업을 수행할 수 있는 컴퓨터 시스템을 지칭하는 말. 
+ 의사결정을 자동화 하는데 중점을 두는 면에서 머신러닝과 공통점을 가짐.

### 인공지능 머신러닝 딥러닝 관계

+ 인공지능, 머신러닝, 딥러닝 구분
  - 기존에는 인공지능과 머신러닝, 딥러닝 사이의 차이를 구분하였음. 
  - 현재는 점점 **인공지능 ⊇ 머신러닝 ⊇ 딥러닝**의 포함관계로 표현하고 있는 추세.
+ 머신러닝은 인간의 행동과 관련이 없을 수 있다는 점에서 인공지능과 차이가 있음.
+ 머신러닝 딥러닝 구분
  - 머신러닝은 입력된 특징들을 매핑시켜 분류나 예측을 수행.
  - 딥러닝은 자료 자체에서 특징을 추출하여 분류 및 예측을 수행한다는 차이가 있음.

##### 학습 자료 특성 기반의 분류

<details>
    <summary>지도학습(Supervised Learning)</summary>
    독립변수와 종속변수의 쌍으로 된 자료가 주어질 때 새로운 자료에 대하여 문제를 풀 수 있는 함수를 찾는 학습방법
</details>

<details>
    <summary>비지도학습(Unsupervised learning)</summary>
    종속변수가 없이 자료들로부터 패턴을 추출하는 학습방법(데이터 마이닝의 군집의 개념)
</details>

<details>
    <summary>반지도학습(Semisupervised learning)</summary>
</details>

##### 인공지능 모델 특성 기반의 분류

<details>
    <summary>머신러닝</summary>
</details>

<details>
    <summary>딥러닝</summary>
    강화학습(Reinforcement learning) : 문제에 대한 직접적인 해답을 주지 않고 경험을 통해 기대값이 최대가 되는 것을 찾는 학습방법
</details>


### 성능평가지표

<details>
    <summary>수치형 성능평가지표</summary>

	평균제곱오차(MSE, Mean square error) : 관측값의 차이가 많을수록 MAE에 비해 높은 패널티 부여

	평균제곱근편차(RMSE, Root mean square error)

	평균절대오차(MAE, Mean absolute error) 

	MAPE(Mean absolute percentage error)

	RMSPE(Root mean square percentage error)

	BIAS

	결정계수(R^2,Coefficient of determination)

	상관계수(Cor 혹은 R 이나 CC, Correlaction coefficient) 

	MAD(Mean absolute deviation)

</details>
<details>
	<summary>이미지/영상 성능평가지표</summary>
		HD(Hausdorff distance)

		AVD(Average hausdorff distance)
</details>

<details>
    <summary>분류 성능평가지표</summary>
	정확도(ACC, Accuracy)

	정밀도(PAG, Precision)

	재현율(POD, Recall 혹은 Probability of detection)

	오보율(FAR, False Alarm ratio)

	임계성공지수(CSI 혹은 IoU, Critical Success Index, Jaccard index, Intersection over Union)

	F1-Score

	ETS(Equitable Threat Score)

	ROC(Receiver operating characteristic)

	AUC(Area under curve)

	Gain AUC

	Area under the Lift Chart

	Area under the precision-recall curve(PRAUC)

	Gini index

	Normalized gini

	Log loss(Cross entropy)

	Multi log loss

	Poisson log loss
</details>

### Framework [Tensorflow(Keras)/Pytorch(Fast AI)/Matlab]
- [pytorch vs tensorflow in 2022](https://www.assemblyai.com/blog/pytorch-vs-tensorflow-in-2022/)
- [MATLAB vs. Python: Which One Is Right for You?](https://www.mathworks.com/products/matlab/matlab-vs-python.html)
- [Tensorflow tutorial guide](https://www.tensorflow.org/tutorials?hl=ko)
- [Tensorflow example](https://github.com/tensorflow/examples)
- [Keras example](https://keras.io/examples/)
- [Which is better for AI Python or R](https://dac.digital/which-is-better-for-ai-python-or-r/)

- [파이토치 한국 사용자 모임](https://pytorch.kr/)

- [Ray Framework](https://docs.ray.io/en/latest/cluster/index.html)


### Machine Learning
- An Introduction to Statistical Learning [PDF - Second Edition](https://www.statlearning.com/)
- PRML [PDF](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) [한글 번역](http://norman3.github.io/prml/) [Python Code](https://github.com/ctgk/PRML)
- MML [PDF](https://mml-book.github.io/) 
- Probabilistic Machine Learning: An Introduction (머피책 1판) [github page](https://probml.github.io/pml-book/book1.html) [PDF](https://github.com/probml/pml-book/releases/latest/download/book1.pdf)
- Probabilistic Machine Learning: Advanced Topics (머피책 2판) [github page](https://probml.github.io/pml-book/book2.html) [PDF](https://github.com/probml/pml2-book/releases/tag/2022-07-29)
- [핸즈온 머신러닝 : 사이킷런, 케라스, 텐서플로 2를 활용한 머신러닝, 딥러닝 완벽 실무 2판 (유튜브)](https://youtube.com/playlist?list=PLJN246lAkhQjX3LOdLVnfdFaCbGouEBeb)
- [머신 러닝 교과서 3판 (유튜브)](https://youtube.com/playlist?list=PLJN246lAkhQiEc-QvvGzUneCWuRnCNKgU)
- [혼자 공부하는 머신러닝 + 딥러닝 (유튜브)](https://youtube.com/playlist?list=PLJN246lAkhQjoU0C4v8FgtbjOIXxSs_4Q)
- [EliceAcademy](https://academy.elice.io/courses/all?category=7&category=9&price=25&tab=course)
    - Do it! 딥러닝 입문
    - 혼자 공부하는 머신러닝 + 딥러닝
    - 모두의 딥러닝
    - 외 일부 도서 무료 제공
- [ML, PCA, DL 등을 전반적으로 설명하는 외국 채널](https://www.youtube.com/c/joshstarmer/featured)
- [xgoost](https://xgboost.readthedocs.io/en/stable/)
- [CatBoost vs LightGBM vs XGBoost 비교 글](https://towardsdatascience.com/catboost-vs-light-gbm-vs-xgboost-5f93620723db)


### Deep Learning
- [Sung Kim 모두를 위한 머신러닝/딥러닝 강의](http://hunkim.github.io/ml/)
	- [모두를 위한 딥러닝 강좌 시즌 1](https://youtube.com/playlist?list=PLlMkM4tgfjnLSOjrEJN31gZATbcj_MpUm)
    - [모두를 위한 RL강좌](https://youtube.com/playlist?list=PLlMkM4tgfjnKsCWav-Z2F-MMFRx-2gMGG)
    - [PR12 딥러닝 논문읽기 모임](https://youtube.com/playlist?list=PLlMkM4tgfjnJhhd4wn5aj8fVTYJwIpWkS)
- [Andrew Ng Supervised Machine Learning: Regression and Classification](https://www.coursera.org/learn/machine-learning)
- [Andrew Ng Coursera 강의 정리](http://www.holehouse.org/mlclass/)
- [CS231n(Convolutional Neural Networks for Visual Recognition)](https://youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv)
- [CS329S(Machine Learning Systems Design)](https://youtu.be/OEiNnfdxBRE)
- 밑바닥부터 시작하는 딥러닝 시리즈 (3편으로 구성)
- [Do It! 딥러닝 입문](https://youtube.com/playlist?list=PLJN246lAkhQgbBx2Kag0wIZedn-P9KcH9)
- [Pytorch로 시작하는 딥러닝 입문](https://wikidocs.net/book/2788)]
- [Dive into Deep Learning](https://ko.d2l.ai/index.html)
- [PYTORCH로 딥러닝하기: 60분만에 끝장내기](https://tutorials.pytorch.kr/beginner/deep_learning_60min_blitz.html)
- [파이토치 한번에 끝내기](https://www.youtube.com/watch?v=k60oT_8lyFw)
- [Deep Learning-Ian Goodfellow](https://www.deeplearningbook.org/) [PDF](https://www.deeplearningbook.org/front_matter.pdf)
- 딥 러닝을 이용한 자연어 처리 입문 [eBook](https://wikidocs.net/book/2155) [Github](https://github.com/ukairia777/tensorflow-nlp-tutorial)

### Reinforcement Learning
- [단단한 강화학습](http://www.yes24.com/Product/Goods/89605439?pid=123487&cosemkid=go15851280278657301&gclid=Cj0KCQjwj7CZBhDHARIsAPPWv3dPo2djMqTHwBb1y8TDKRShLfXjeoxNsv2NEmRJDZ9YxKXixJy9-2oaAuqWEALw_wcB) 영어 원서도 추천
- [UCL Course on RL](https://www.davidsilver.uk/teaching/)
- [CS234: Reinforcement Learning Winter 2022](https://web.stanford.edu/class/cs234/)
- [Spinning Up in Deep RL!](https://spinningup.openai.com/en/latest/)
- [huggingface-RL course](https://huggingface.co/deep-rl-course/unit0/introduction?fw=pt)

### ETC (ex: k8s/MLOps)
- [Kubernetes tutorials](https://kubernetes.io/docs/tutorials/)
- [MLOps 정리 노션](http://bit.ly/zzsza_links)
- [MLOps Contents 모음](https://github.com/MLOpsKR/Awesome-MLOps-Contents)
- [Kubeflow를 통해 더 나은 AI 모델 서빙과 MLOps 실현하기](https://tv.naver.com/v/23650093)
- [Open Neural Network Exchange (ONNX)](https://github.com/onnx/onnx)
- [Airflow vs Kubeflow](https://hevodata.com/learn/kubeflow-vs-airflow/)
- [모두를 위한 MLOps](https://mlops-for-all.github.io/)
