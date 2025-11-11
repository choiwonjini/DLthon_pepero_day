# DLthon_pepero_day
This is a repository for Aiffel DLthon  
---
- Team name : pepero_day  
- Teamates : 김완수, 이수호, 이영석, 최원진  
---
# Structure of this repository
```bash
DLthon_pepero_day/
├── configs/
├── Data/
│   └── aiffel-dl-thon-dktc-online-15
│       └── ~.csv
├── Images/
├── models/
│   ├── 1D_CNN.ipynb
│   ├── bi_GRU.ipynb
│   ├── boemikbert_base.ipynb
│   └── decoder_only.ipynb
├── dataset.py
├── preprocessing.py
├── README.md
├── tokenization.py
├── eda.py
└── utils.py
```
---
- folders
    - Data : Kaggle에서 다운받은 원본 데이터셋
    - configs : 모델 설정, 데이터 경로 등 프로젝트의 주요 설정 값들을 저장하는 파일을 담는 디렉토리
    - Images : 결과 리포트나 발표 자료에 사용될 이미지 파일을 담는 디렉토리
    - modles : 다양한 모델 아키텍처 실험 및 관리를 위한 디렉토리
- files
    - dataset.py : 데이터셋을 불러오고, 모델 입력으로 사용할 수 있는 형태로 변환
    - preprocessing.py : 원본 데이터에 대한 전처리
    - tokenization.py : 텍스트 데이터에 대한 토큰화 진행
    - eda.py : 데이터셋의 분포 확인
    - utils.py : 여러 파일에서 공통적으로 사용되는 유용한 함수를 모아놓은 모듈