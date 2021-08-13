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
│        └── Random Forest.ipynb
│   
└── README.MD
``` 

# 데이터 출처

중소벤처기업부, Korea AI Manufacturing Platform(KAMP),CNC머신 AI데이터셋, KAIST(UNIST, 이피엠솔루션즈), 2020.12.14.,https://kamp-ai.kr

# 모델 정확도 비교

|&nbsp;         | Tool Condition | Machining Finalized | Passed Visual Inspection |
|---------------|----------------|---------------------|--------------------------|
| DNN           |         91.88% |              99.57% |                   99.68% |
| LightGBM      |         87.35% |             100.00% |                  100.00% |
| Random Forest |         92.50% |              99.91% |                   99.91% |