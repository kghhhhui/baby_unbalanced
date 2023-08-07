# baby_unbalanced
### 데이터 불균형 관련

#### 01) audiomentations library  
: 오디오 데이터 증강을 위한 파이썬 라이브러리  
: Albumentations에서 영감을 얻었으며, 딥러닝에 유용하고 CPU에서 실행됨  
: 이중 오디오 및 다중 채널 오디오를 지원  
: audiomentations 라이브러리를 사용하여 Gaussian 노이즈, 시간 스트레칭 및 피치 쉬프트와 같은 변형을 오디오 데이터에 적용.  
: 다양한 오디오 증강 기법을 제공하며, 원하는 대로 파이프라인을 구성하여 사용이 가능.  
=> 데이터 분류를 인식하는데에는 영향을 미치지 않으면서, 음성의 개수는 늘릴 수 있는 Transforms을 이용해 데이터를 증강시켜 데이터 불균형 문제 해소?

1. audiomentations_ex : 예제 이용하여 실행
2. audiomentations_baby : 예제 이용하여 baby 음성 넣어 실행.  


#### 02) specAugment  
: 음성 처리 및 음성 인식 작업에서 사용되는 데이터 증강 기법 중 하나  
: 주로 스펙트로그램(음성의 주파수 및 시간 정보를 표현하는 그래프) 데이터에 적용되며, 모델의 일반화 성능을 향상시키는 데 도움  
:  음성 데이터의 불규칙성 및 다양성을 높이는 데 사용되며, 특히 오버피팅을 줄이고 모델의 강인성을 향상시키는 데 도움  
