## matplotlib.pyplot에 대한 사용법

import matplotlib.pyplot as plt

- plt.figure() : figure 생성
- plt.cla() : 축을 지움
- plt.xlim(a, b), plt.ylim(a, b) : [a, b]까지 x축, y축 범위 설정
- plt.plot(x, y, 'b') : x, y 데이터를 설정하고, 'b'는 선의 색깔이 blue # Referece : [선의 종류, 색깔](https://bcho.tistory.com/1201)
- plt.xlabel('text'), plt.ylable('text') : x, y축의 labelling
- plt.text(x, y, 'text', fondict={'size' : 15, 'color' = 'blue' }) : 그래프의 적절한 위치에 텍스트를 표기 --> x, y 위치에 text를 표기, 글씨 크기는 15, 색깔을 파랑
- plt.ion, plt.ioff : 대화형 모드 켬, 끔
- plt.show : 그래프를 보여줌
- plt.pause(0.1) : 0.1초동안 그림이 멈춤 --> 그림을 갱신하기 위한 시간 확보
