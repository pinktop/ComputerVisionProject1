# ComputerVisionProject1

본 챌린지는 잎의 질병을 분류하는 챌린지입니다. 





## 데이터셋

![캡처](https://user-images.githubusercontent.com/85859441/137592829-909c6077-5207-4235-bb15-2c773bcde151.PNG)

AI Hub와 농진청에서 제공하는 화상병, 건강한 잎, leafspot 이미지를 이용했습니다.
데이터 셋은 vision 폴더에 첨부했습니다


## 테스트 제출 자료

csv 형식의 파일 경로 + 파일 이름과 예측 라벨이 포함된 파일 (Name 컬럼은 열의 값이 사진과 동일해야합니다)

예시 사진) 제출 자료

![캡처](https://user-images.githubusercontent.com/85859441/137592622-858fa11f-682d-4776-861b-346515f5c931.PNG)

라벨은 화상병, 건강한 잎, Leafspot 순으로 각각 0,1,2 입니다 



## 베이스라인

본 챌린지는 '딥러닝 기반 표고버섯 병해충 이미지 분석에 관한 연구'를 베이스라인으로 합니다.
https://www.koreascience.or.kr/article/JAKO202010163508707.pdf

코드는 https://codingcrews.github.io/2019/01/19/cat-dog-resnet/ 를 참고했습니다

## 참고하면 좋을 논문

Unsupervised image translation using adversarial networks for improved plant disease recognition, Computers and Electronics in Agriculture
https://www.sciencedirect.com/science/article/pii/S0168169919315339

Data Augmentation on Plant Leaf Disease Image Dataset Using Image Manipulation and Deep Learning Techniques
https://ieeexplore.ieee.org/document/8971580



