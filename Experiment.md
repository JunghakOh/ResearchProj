### 실험 과정 및 결과
* 재연한 논문 설명
이번 실험의 과제는 참고논문 실험을 재연해 보고, 개선점에 대한 아이디어를 도출하는 것이다.
제가 선정한 참고 논문 A는 "위치기반서비스의 측위시스템 정확도 향상에 관한 연구 분석"([논문 원본 링크](http://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE02500799))이고 교수님께서 함께 분석하라고 하신 논문B는 DeepPositioning:  Intelligent Fusion of Pervasive Magnetic Field and WiFi Fingerprinting for Smartphone Indoor Localization via Deep Learning 분석([논문 원본 링크](https://ieeexplore.ieee.org/document/8260607))
입니다. 

B논문으로 재연 하려고 하였지만  



실험은 Android 9 시스템이 설치된 Sumsung SM-J730K(Galaxy J7) 모델 스마트폰을 이용하여 진행되었다.

cell id와 신호세기 측정을 위해 "Mobile tower cell id tracker"어플리케이션을 사용하였다.[그림1]

...에서 부터 ...까지 이동하면서 cell id 와 signal 수집하였다.

 수집된 정보로 Cell based location detection 방법을 적용해 이동 경로를 구한다음 실제 경로와의 차이를 관찰하였다. 
  
 cell id 로 부터 위치를 얻기 위해 opencell ID 플랫폼을 사용하였다.([Opencell ID 링크](https://opencellid.org))
 
 개인 키를 발급받고 post방식으로 호출하면 위치 정보를 json 파일 형태로 리턴한다.
![그림2:opencellid API설명](./api.PNG)  
 
 


![그림1:데이터 수집에 사용된 어플리케이션](./ap_used.png) 

("Network Info","Network Cell Info Lite"어플리 케이션을 사용하여 데이터 수집 시도했지만 수집된 정보를 엑셀 형태로 저장하는 기능이 없어 최종사용하지 않았다.)


