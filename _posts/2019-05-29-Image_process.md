---
title: "Image Processing"
date: 2019-05-29 21:24:28 -0400
categories: image-process c++ mfc huffman-coding  
---
# 디지털 영상처리 프로젝트 <br>

1. MFC를 이용해 다양한 필터 구현하기
* Noise 추가하기
`Gaussian Noise` `Salt && Pepper Noise`
* Mean Filter 구현
`Arithmetic Filter` `Geometric Filter` `Harmonic Filter` `Contra Harmonic Filter`
* Order-Statistic Filter 구현
`Median Filter` `Adaptive Median Filter`
* PSNR로 노이즈 제거 수치 비교

2. 주파수 도메인 필터 구현
* IDFT(Inverse Discrete Fourier Transform)
>> 이산 푸리에 역변환으로 주파수 성분을 2D 이미지로 변환

* LPF(Low Pass Filter) 
>> 저주파만 통과시키는 필터 구현
`ideal LPF` `butterworth LPF` `gaussian LPF`

* HPF(High Pass Filter)
>> 고주파만 통과시키는 필터 구현
`ideal LPF` `butterworth LPF` `gaussian LPF`

3. Huffman Coding
>> 허프만 코딩을 이용해 이미지 압축&해제

### 사용 스택 <br>

`C++` `MFC`

<br>



소스코드 [image processing][image-processing]

[image-processing]:   https://github.com/godute/image_processing