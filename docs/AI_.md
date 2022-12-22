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