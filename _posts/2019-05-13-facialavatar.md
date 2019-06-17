---
title: "Facial Avatar"
date: 2019-05-13 21:19:28 -0400
categories: [Project]
tags: [face-recognition, dlib ,opencv, opengl]
---
# 기간 <br>
2017.11 ~ 2018.05

# 사용자의 표정을 따라하는 3D 캐릭터 <br>

* dlib를 이용해 얼굴의 특징점 추출
* modern-opengl을 이용해 3D 캐릭터 모델 렌더링
* 사용자의 68개 랜드마크와 3D 캐릭터의 랜드마크 위치값 비교
* 보간법을 사용해 현재 사용자의 표정과 가까운 캐릭터 표정에 더 큰 가중치 부여
* 각 3D 캐릭터의 표정을 섞어 현재 사용자 표정과 유사한 표정 출력

### 사용 스택 <br>

`C++` `dlib` `opencv` `opengl`

![facialavatar1](https://user-images.githubusercontent.com/31815711/58609232-d851c200-82e1-11e9-9207-e4d47815153d.png)
![facialavatar2](https://user-images.githubusercontent.com/31815711/58609233-d851c200-82e1-11e9-976a-b3784009ffc6.png)

<br>



소스코드 [Facial-Avatar][avatar-gh]

[avatar-gh]:   https://github.com/godute/Facial-Avatar
