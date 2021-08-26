# Media Mix Modeling - Report Service Team
<img src="https://user-images.githubusercontent.com/80456601/130928344-be683b2d-9649-4e89-9393-777024188bf8.png" width="50%" height="50%"/>

- 전체 프로젝트 주제: TV 광고 노출량으로 수입 자동차 브랜드의 등록 대수 예측 모델 구상
- 서비스 팀 목적: 리포팅 서비스 - 트렌드 리포팅과 최적의 채널믹스 추천 모델을 위한 대시보드 시각화 
- 프로젝트 기간: 2021.04.29 - 2021.07.14
- 서비스 팀: 김기성, 김현진
- 서비스 파트 발표자: 김기성 [Service 팀장]
<img src="https://user-images.githubusercontent.com/80456601/130929088-2fea398b-2b31-49c2-9b57-432be71e9338.png" width="50%" height="50%"/>

### 전체 프로젝트 구성 
<img src="https://user-images.githubusercontent.com/80456601/130933722-aa5046d3-5136-4603-a2a9-c02ff77d94e0.png" width="50%" height="50%"/>

#### [전체 프로젝트 발표 내용을 보시려면 여기 클릭](https://www.notion.so/TV-Media-Mix-Modeling-ede55294fa0b40a89e5723970a346f98)
#### [전체 프로젝트 발표 영상을 보시려면 여기 클릭](https://www.youtube.com/watch?v=K8HQ1om6hy8)

### Service 팀 - 대시보드 서비스화
<img src="https://user-images.githubusercontent.com/80456601/130930093-9781ca40-6ae3-4790-ab96-b14213e2ac39.png" width="50%" height="50%"/>

- 목적: DB팀이 구축해준 데이터로 트렌드 리포트와 ML 팀에서 제공해준 자료를 바탕으로 미디어 플랜 제안서를 'Tableau'를 이용하여 대시보드 시각화 표현

### Service 팀이 제공하는 주요 리포팅 사항
<img src="https://user-images.githubusercontent.com/80456601/130930495-0b836590-c2b3-404f-bf7f-519e2f431551.png" width="50%" height="50%"/>

#### 1. 트렌드 리포트 
<img src="https://user-images.githubusercontent.com/80456601/130931799-62a30a7a-82ff-4c99-aa07-fd170680f789.png" width="60%" height="60%"/>

- **리포팅 기준: 2018년 ~ 2021년 4월**
- 한국 수입차 시장의 전반적인 트렌드는 18년 19년에 판매량이 꾸준히 상승하다가, **2021년 1월부터 급격히 늘고** 있다. 
- 이는 **개별소비세 인하 연장 이슈로 국산차보다 수입차가 비교적 저렴해지는 현상의 원인**으로 분석됨. 
- 브랜드별 **시장 점유율은 독일 3사(Benz, BMW, Audi)가 여전히 높고**, 20년 대비 **30대의 구매 비중이 증가**했으며, 친환경 이슈로 **내연기관 자동차보다 하이브리드나 전기차의 구매 비중이 높아짐**.
- 광고주인 도요타 분석에서 주목할 점은 모델별 판매현황, 미니밴 모델인 **'시에나' 판매가 급증**하고, 세단 모델인 **'아발론' 판매가 저조**함. 
- 해당 대시보드에 나와있지 않지만 **광고를 한 모델과 하지 않은 모델의 차이가 있는 것**으로 보입니다. **(추후 추가로 요청해서 대서보드로 구현 할 수 있음으로 사료됨.)**
- 경쟁 브랜드인 '독일 3사'(Benz, BMW, Audi)와 비교했을 때, **'도요타'와 '렉서스**'의 경우 반일 감정으로 판매가 저조했지만 **올해는 광고량이 증가함에 따라 판매량도 동시에 증가한 것으로 나타남**. 
- 하지만 "**도요타**"의 경우 렉서스에 비해 **광고량이 많지 않아 다른 브랜드들의 비해 증가폭이 높지는 않다.** 지금 수입차의 시장 분위기가 좋을 때 **광고와 마케팅을 적극적으로 하면 좋은 결과를 얻을 수 있을 것**이다 라고 광고주에게 제안할 수 있음.

<img src="https://user-images.githubusercontent.com/80456601/130932673-f6fdc4c5-d774-4fb0-a798-00f2da4a9932.png" width="60%" height="60%"/>

- 고객 데모에 따라 신규등록대수 대비 광고노출, **인터넷 검색량**을 비교 분석했을 때, **성별 신규등록대수는 남성비율**이 **연령대 신규등록대수는 40~50대**가 많다. 
- **광고노출량은 여성**이, **연령대는 50대 60대**분들이 많았고, **인터넷 검색량은 남성**이, **연령은 50대~60대**가 많다. 
- 네 번째 대시보드는 **광고주가 실 구매 고객층과 광고 타겟층을 기획할 때 참고 가능**할 것으로 판단됨.
- **도요타의 기존 tv 광고 집행 내역**을 살펴보면, 인기있는 채널은 **tv조선, tvn, ocn 순**  
- **tv조선은 24시 ~ 01시, tvn 22시 ~ 23시 사이, ocn은 17시와 20시에 광고량이 많은 것**을 알 수 있다. 
- 종합해보자면 대체적으로 **채널은 지상파 3사보다 종편, 케이블 채널, 시간은 밤 시간대에 광고를 많이 한 것**을 볼 수 있다. 네 번째 대시보드에서 파악한 타겟 고객에 맞게 채널 및 시간대를 기획할 수 있을 것으로 사료됨.

#### 2. 미디어 플랜 및 채널 믹스 제안 
<img src="https://user-images.githubusercontent.com/80456601/130933393-0c74056d-4459-40f8-9d40-15662344db49.png" width="60%" height="60%"/>

- MMM(Media Mix Model) 모델로 돌려본 예측 결과와 채널 믹스 제안. 참고로 해당 모델은 도요타의 경우 당월 광고효과가 5개월 ~ 6개월 후에 나타냄. 
- 왼쪽 예상판매 트랜드 차트는, X 축은 광고횟수 y축은 예측 판매량을 나타냄.  
- 예측 모델을 바탕으로 미디어 KPI 목표 기준을 **300대, 400대, 500대, 600대로 구성** 구성함.
- 여기서 주목할 점은 예상 광고가 올라가는 횟수는 그렇게 차이가 많이 나지 않지만, 노출량, 특히 노출량이 도달율 +3, +5, +7, +9 이상에서 급격히 수치가 올라 가는 것을 볼 수 있다, 이는 반복적으로 광고를 집행하고 우리 광고를 본 사람들의 비중이 커져야지 KPI 목표에 도달 할 수 있다고 예측함.
- 앞에서 말한 KPI 목표를 설정과 예측을 바탕으로 **300대 KPI 타겟** 기준, 광고수 **1,587 회**, 노출량 **195 GRPs**를 R1 **57%**, R3 **30%**, R5 **14%**, R7 **6%**, R9 **3%** 이 조건을 맞춰 줄 수 있는 추천 채널 믹스 세 가지 제안
  1)  **tvn, ocn, screen 등 인기 케이블 채널을 제안하는 첫 번째 케이스**
  2) **kbs, sbs, mbc 등 3사 지상파 채널이 포함된 두 번째 케이스**
  3) **마지막으로 티비조선, 채널에이 sbs등 종편과 케이블 채널 위주의 세 번째 케이스**
#### 3. 부가 서비스
<img src="https://user-images.githubusercontent.com/80456601/130938242-ab7addb2-ca3e-458b-b06e-33d4510c90f0.png" width="60%" height="60%"/>

- 마지막으로 경쟁 브랜드와 네이버 검색량을 비교 분석할 수 있는 대시보드. 
- 실제값을 자동으로 크롤링해서 데이터 베이스에 넣고, 데이터를 끌고와 대시보드를 통해 우리만의 BI로 한번에 볼 수 있는 장점이 있어 부가 서비스로도 제공할 수 있음. 

### 프로젝트 Service 팀의 성과: 수입차 시장의 트렌드 리포트, 광고주 브랜드 분석 리포트, 광고주 브랜드 TV 광고 집행량 리포트 제공, 목표 판매달성을 위한 최적의 채널 추천 리포트 제공, 네이버 검색량 서비스 제공, 세 가지로 요약
