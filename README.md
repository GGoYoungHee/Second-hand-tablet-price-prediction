# Second-hand-tablet-price-prediction
[Paper] An Analysis of Price Influencing Factors for Used Tablets

at Journal of Industrial Convergence.


# 분석 과정
## 1. 데이터 전처리

- 가장 힘들었음, Real World data는 생각보다 노이즈가 엄청엄청 많았고, 거래에서 박스만 파는 경우(이건 대체 왜 파는지 모르겠음... $5근처 정도로 팔던데)와 같이 태블릿 판매 섹션에 이런 데이터가 들어오는 지도 모르겠고, 태블릿을 판매하는 경우인데 pc탭에서 발견되는 경우도 종종 있었다. 따라서 태블릿 판매 섹션에서만 데이터를 보는 게 아니라 전 섹션에서 데이터를 한번씩 훓는 과정이 필요했다. 
- real world data는 너무나도 방대해서 excel에서 직접 접근하는 것도 로드하지 못했다. python을 이용하여 전처리를 하였고, 진짜 이 과정에서 에너지도 많이 소비하고 시간도 엄청 많이 걸렸다.

## 2. 모델링
a)
</br>
b)
</br>
c)
</br>
d)

## 3. 모형 비교
- 모형을 비교하는 metric은 RMSE를 선택하였고, 

## 4. 최종 모형 선택
- 모형 4 선택됨


# 느낀점
- 여태 했던 프로젝트 중, 가장 긴 호흡을 가지고 했던 프로젝트이다. 프로젝트 중간에 중단되었던 기간이 빈번해서, 체크포인팅과 기록이 무엇보다 중요했었다.
- GIGO를 여실히 느꼈던 작업, 데이터 분석에서 데이터 전처리 과정이 왜 90% 정도를 차지하는 지를 알 것 같다.
- 한 문장을 쓸 때마다 그 문장의 근거를 찾아내는 것도 시간이 꽤 걸렸다. 사실 다른 논문을 읽을 때에는 선행연구 부분을 자세하게 안 읽고 넘어가고 출처도 대충 보고 넘어갔지만, 막상 논문을 직접 써 보니까 이 부분이 꽤나 시간을 많이 차지하였다. 연구직은 내가 원하는 결과 혹은 자료가 나올 때 까지 참고 기다리는 인내심과 체력이 중요한 요인인 것 같다.


<!--
- 평균은 생각보다 믿을 만한 수치가 아니다! -> 분산...?

- GIGO 를 여실히 느끼는중,,, 
  -> 데이터로 이야기하자! 
    원본 데이터를 볼 수 있어야 함, 
    말이 되는 데이터!!
  -> data cleaning 의 중요성,, 이래서 NLP를 이용해 데이터 정제하는 ML 을 많이 쓰는구나,,,
 -> 이제 NLP를 좀 좋아해봐야겠다!

- EDA는 marginal distribution을 파악하기 위한 과정!
  
- 미팅 전후 준비 확실하게!!
   -> 결과보다는 과정위주로 발표! 교수님 설득한다는 마인드로 하기기!, 
  -> 피드백 받는 부분 있으면 내용 꼼꼼히 정리하고 앞으로 어떻게 하면 같은 내용에       
    정리  !  !  는 받 는해야할 지민 해  !F하!   ?볼가족분것다    꼼 ! ㅠ , 려  석  그냥서료a에대 생고 으t만
 ED @
-> 인코딩 왜저래~~ 다 까먹었당 블로그에 정리할 때 다시 생각해봐야겠다

- 꾸준히, 그리고 효율적으로 일하기!


- 무엇보다 중요한건 멘탈 부여잡기!
   -> 스스로 중심을잡자!,  남들과 비교하지 않기~~ 내 주위에는 아웃라이어들이 많다고 생각!!
   -> 근데 객관적으로 사실임,, 
   -> 통계로 밥 벌어먹고 살 수 있을까...? -> 당연당연~~ 
  
- 큰 그림을 볼 줄 아는 능력을 기르자!
   -> 항상 줄기를 잊지 말기
  -> 왜?라는 의문을 갖도록 하자! 수동적인 자세 X
   -> 큰 그림 속에서 지금 내가 하고 있는 것이 뭘하고 있는 건지, 
     왜 하는건지 정확하게 파악하기

- 한정된 집중력/체력을 어디에, 언제, 얼만큼 쓸 것인지를 정하는 것도 능력임

- 논리적으로 생각하는 법
- real-world 데이터는 생각보다 힘드러~~
--!>
