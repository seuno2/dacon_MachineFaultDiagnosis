# dacon_competition3 기계 고장 진단 분류(anomaly detection)
- training dataset : 기계 fan 소리샘플 1279개, 모두 정상 label
- librosa.mfcc : 음성 &rarr; 벡터 encoding, IsolationForest, pycaret 앙상블
- metric : Macro F1 score = 0.894 / 678팀 중 34등 (top5%)
![image](https://user-images.githubusercontent.com/121914727/229559577-3c522764-1215-4d80-999b-258cf3ce789f.png)
