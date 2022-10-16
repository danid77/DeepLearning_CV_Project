<h1> DeepLearning_CV_Project</h1>

<h2> 주관: 중소기업벤처부 이어드림 스쿨 2기</h2>

---

<br>
\<!-- ![image]('https://github.com/danid77/DeepLearning_CV_Project/blob/main/imgs/national-cancer-institute-LnvCEXQwC-o-unsplash.jpg') -->
<h2>Thyroid cancer image classification</h2>

<h3> 기획의도</h3>
보건복지부 조사에 따르면, 우리나라의 암 발생률 중 가장 높은 비율을 차지하고 있는 암이 갑상선 암입니다. 
갑상선 암의 대표적인 진단 방법은 동위원소검사, 조직검사, 초음파 검사 입니다. 

동위원소검사는 미량의 유용한 방사성 동위원소가 표지된 방사성의약품을 인체내에 주사하여 신체의 해부학적 및 생리학적 상태를 진단, 평가하여 질병을 진단하고 수집된 영상은 컴퓨터를 이용하여 정량분석을 통하여 형태학적인 이상뿐 아니라 기능적 이상도 동시에 얻을 수 있습니다. 하지만 현재는 효용성이 없어 특별한 경우를 제외하고 잘 이용되지 않습니다.

조직검사는 인체에서 발생하는 모든 질병 종양, 암, 염증, 감염, 면역질환 등에 대해 질병이 의심되는 부위의 조직을 떼어내어 슬라이드로 만든 후 광학 현미경으로 관찰 판독하여 질병에 대한 최종 진단을 내리는 검사입니다. 갑상선 조직 검사(세침흡인 세포검사)는 정확도가 95%에 이릅니다. 하지만 결과가 나오기까지 질병에 따라 다르지만 보통 대략 3일 정도 소요되기 때문에 시간이 오래 걸립니다.

초음파 검사는 인체에 무해한 초음파(음파의 일종)를 몸 안에 투과시킨 후 반사초음파를 이용하여 모니터에 영상을 나타내는 검사로서 간, 담낭, 췌장, 비장, 혈관계를 포함한 질병의 유무, 병소의 크기와 양상을 진단합니다. 모니터 영상으로 검사를 진행하기 때문에 간편하게 검사할 수 있고, 작은 혹을 찾아내는데 유용합니다. 하지만 암일 경우 주위 조직으로서의 침범유무, 림프절 전이 유무를 알아내는데 도움이 되지만 암을 확진하기는 어렵습니다.

위와 같은 방법으로 갑상선 암을 진단하기에 사용하지 않거나 정확도는 높으나 시간이 오래걸리는 단점 그리고 시간은 오래걸리지 않으나 정확도가 비교적 낮은 진단 방법입니다. 하지만 비교적 간편하고, 시간이 적게 드는 초음파 검사를 통하여 암과 양성 종양을 판별할 수 있는 인공지능 모델이 있다면 다른 치명적인 질병들에 대해 전문가의 비율을 늘릴 수 있어 더 많은 생명을 살릴 수 있을 것이라 생각합니다.

결론적으로 우리는 결론적으로 DeepLearning CNN을 활용해 암 진단의 정확도를 높여 오진을 내릴 수 있는 확률을 낮추자는 점에 초점을 맞추어 프로젝트를 진행했습니다.
<br>



---


|  프로젝트 순서 |     내용    |
|:------------------:| -----|
|문제 정의|Thyroid cancer image classification|
|데이터 수집|Thyroid cancer image Data |   
|데이터 전처리|Cancer image Crop,  Augmentation|
|모델 학습|Modeling : EfficientNetB4, EfficientNetB5, EfficientNetB7, ResNet-158, ResNet-152, ResNet-101, VGG16, VGG19|
|모델 평가|AUROC Curve|
|모델 성능 향상| 하이퍼파라미터, 데이터 전처리 |


<br>

<h3> Basic information</h3>

**공식기간: 2022.07.21 ~ 2022.08.05**

- 인원 : 3명
- 팀장 : 장세훈
- 팀원 : 강다호, 진승범
- 데이터 : Thyroid cancer image Data
- 역할 :  ImageDataGenerator로 data Augmentation, Modeling, AUROC curve 모델 성능 비교, Heatmap - Grad-CAM으로 갑상선 암 위치 파악, Presentation
- 협업장소 : 스파크 플러스
- 소통 : 스파크 플러스, Slack
- 저장소 : git
- 개발환경 : vscode, jupyter notebook, Anaconda
- 언어 : python 3.8
- 라이브러리 : numpy, pandas, sklearn, catboost, cv2, os, math, scipy, PIL, scikitplot, tensorflow.keras
- 시각화 라이브러리 : seaborn, matplotlib
