# 파일 구조
```bash
├── data
│   ├── processed
│   └── raw   
├── src
│   ├── feature
│   │   ├── data visualization.ipynb
│   │   └── preprocess.ipynb
│   └── model
│        ├── DNN.ipynb
│        ├── LightGBM.ipynb
│        ├── LightGBM with fft.ipynb
│        ├── Random Forest.ipynb
│        └── Random Forest with fft.ipynb
│   
└── README.MD
``` 

# 데이터 출처

중소벤처기업부, Korea AI Manufacturing Platform(KAMP),CNC머신 AI데이터셋, KAIST(UNIST, 이피엠솔루션즈), 2020.12.14.,https://kamp-ai.kr

# 모델 정확도 비교

|&nbsp;         | Tool Condition | Machining Finalized | Passed Visual Inspection |
|---------------|----------------|---------------------|--------------------------|
| DNN           |         91.81% |              99.53% |                   99.70% |
| LGBM          |         87.30% |             100.00% |                   99.98% |
| LGBM(fft)     |         87.35% |             100.00% |                  100.00% |
| RF            |         92.48% |              99.91% |                   99.95% |
| RF(fft)       |         92.34% |             100.00% |                  100.00% |