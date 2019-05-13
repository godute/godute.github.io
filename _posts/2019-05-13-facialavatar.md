---
title: "Facial Avatar"
date: 2019-05-13 21:19:28 -0400
categories: face-recognition face-verification facenet joint-bayesian 
---
# 사용자의 표정을 따라하는 3D 캐릭터 <br>

dlib를 이용해 얼굴의 특징점 추출<br>
modern-opengl을 이용해 3D 캐릭터 모델 렌더링<br>
사용자의 68개 랜드마크와 3D 캐릭터의 랜드마크 위치값 비교<br>
보간법을 사용해 현재 사용자의 표정과 가까운 캐릭터 표정에 더 큰 가중치 부여<br>
각 3D 캐릭터의 표정을 섞어 현재 사용자 표정과 유사한 표정 출력<br>

### 사용 스택 <br>

`C++` `dlib` `opencv` `opengl`

<br>



소스코드 [Facial-Avatar][avatar-gh]

[avatar-gh]:   https://github.com/godute/Facial-Avatar
