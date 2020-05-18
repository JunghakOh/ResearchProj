### 실험 과정 및 결과

실험은 Android 9 시스템이 설치된 Sumsung SM-J730K(Galaxy J7) 모델 스마트폰을 이용하여 진행되었다.

cell id와 신호세기 측정을 위해 "Mobile tower cell id tracker"어플리케이션을 사용하였다.[그림1]

...에서 부터 ...까지 이동하면서 cell id 와 signal 수집하였다.

 수집된 정보로 Cell based location detection 방법을 적용해 이동 경로를 구한다음 실제 경로와의 차이를 관찰하였다. 
  
 cell id 로 부터 위치를 얻기 위해 opencell ID 플랫폼을 사용하였다.([Opencell ID 링크](https://opencellid.org))
 


![그림1:데이터 수집에 사용된 어플리케이션](./ap_used.png) 

("Network Info","Network Cell Info Lite"어플리 케이션을 사용하여 데이터 수집 시도했지만 수집된 정보를 엑셀 형태로 저장하는 기능이 없어 최종사용하지 않았다.)


