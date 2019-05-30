---
title: "Drop The Beat"
date: 2019-05-13 23:04:05 -0400
categories: [Project]
tags: [pose-estimation,LSTM]
---
# 기간 <br>
2019.03 ~ 2019.04

# AI스피커 기반 모션인식 게임 <br>

카메라, 디스플레이가 탑재된 AI스피커를 이용해 키즈를 대상으로 한 모션 인식 키즈콘텐츠 게임 구현 <br>

tf-pose를 이용해 사람의 관절 좌표를 추출한다. 그리고 minmax scale을 이용해 관절 좌표를 정규화 시킨다. 정규화를 마치면 LSTM 모델에 input으로 해당 좌표들을 넣는다.
### 사용 스택 <br>

`Python` `tensorflow` `Raspberry PI`

<br>

### 관절 추출 오픈소스
```
tf-pose
```

### 모션 인식 모델
```
LSTM
```

![pose1](https://user-images.githubusercontent.com/31815711/58553935-2f5b8680-8251-11e9-9c07-f1213b7052b7.png)
![pose2](https://user-images.githubusercontent.com/31815711/58554030-3a161b80-8251-11e9-9f1c-cece19f903d7.png)
![pose3](https://user-images.githubusercontent.com/31815711/58554055-3c787580-8251-11e9-8733-f7a33fc2607d.png)
![pose4](https://user-images.githubusercontent.com/31815711/58554078-3edacf80-8251-11e9-9daa-bc8a1d1eae41.png)
![pose5](https://user-images.githubusercontent.com/31815711/58554094-40a49300-8251-11e9-8d05-016294d1238c.png)
![pose6](https://user-images.githubusercontent.com/31815711/58554115-4306ed00-8251-11e9-889b-933df3a58bed.png)


소스코드 [DropTheBeat][dropthebeat-gh]

[dropthebeat-gh]:   https://github.com/koseokkyu/AI_tfPose_Project
