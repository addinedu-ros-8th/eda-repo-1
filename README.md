![header](https://capsule-render.vercel.app/api?type=waving&&&color=timeGradient&height=200&section=header&text=영화산업%20이대로%20괜찮은가?&fontColor=ffffff&fontAlign=63&fontAlignY=30&animation=twinkling&fontSize=50&desc=Team1.%20EDA%20Project&descSize=30&descAlign=80)

# :dart: 주제 : OTT의 출현과 코로나를 겪으면서의 영화 산업 변화
> 배우 황정민 수상 소감 中
>   > 영화가 많이 제작이 안 되고 조금 어렵긴 하지만...                
이 배우는 왜 이렇게 말을 했을까?


<img src="https://github.com/user-attachments/assets/31b5d722-1fc4-4ff7-853f-47ce0e9342e4" width="400" height="150"/>  <img src="https://github.com/user-attachments/assets/4a088b2b-8f3b-428f-af94-6e80da0ae8af" width="400" height="150"/>                               
<img src="https://github.com/user-attachments/assets/dbde6505-4fc0-4162-ae8f-9d26b3fe32e5" width="400" height="150"/>  <img src="https://github.com/user-attachments/assets/4d815d95-13ca-4500-b2dd-799223fd65f2" width="400" weight="150/">                                               
위의 뉴스 헤드에서 영화 산업이 그리 좋지 않은 상황이라는 것을 알 수 있다.                                   

영화 산업에서 가장 큰 변화는 아마 OTT의 출현과 코로나라고 생각한다.                           
![image](https://github.com/user-attachments/assets/a6cd10a3-c6df-4e6b-9dcd-d82e75ed3c9e)                                    
가장 대표적인 OTT인 NETFLIX가 서비스를 시작한 연도는 2016년으로 확인이 되는데 OTT 산업들이 인기를 얻기 시작하고 다양한 OTT 서비스들이 나오기 시작한 것은 2019-2020년도 코로나 시기부터로 보인다. 
                                               
우리 1조는 OTT의 인기로 인해 영화 산업이 크게 타격을 입은 것은 코로나 이후인 2019년도로 보고 그로 인해 코로나가 회복된 지금까지 영화관에서 인기있는 장르와 상영 방식이 코로나 이전과 비교해서 차이가 있을것이다는 가설을 세워 이를 확인하고자 데이터 분석과 시각화를 진행했다.
***
## :computer: Skill Set
|Categories|SKills|
|------|------|
|IDE|![Static Badge](https://img.shields.io/badge/linux-%23FCC624?style=plastic&logo=linux&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/ubuntu-22.04-grey?style=plastic&logo=ubuntu&logoColor=ffffff&labelColor=%23E95420) ![Static Badge](https://img.shields.io/badge/vsCode-%232185D0?style=plastic&logo=vscode&logoColor=ffffff) |
|Design|![Static Badge](https://img.shields.io/badge/ERD%20Cloud-%237F52FF?style=plastic)|
|Programming|![Static Badge](https://img.shields.io/badge/Python-%233776AB?style=plastic&logo=python&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/jupyter-%23F37626?style=plastic&logo=jupyter&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/selenium-%2343B02A?style=plastic&logo=selenium&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/beautifulsoup-grey?style=plastic&logoColor=ffffff)|
|Data|![Static Badge](https://img.shields.io/badge/mysql-%234479A1?style=plastic&logo=mysql&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/amazonrds-%23527FFF?style=plastic&logo=amazonrds&logoColor=ffffff)|
|Analyzing&Visualization|![Static Badge](https://img.shields.io/badge/numpy-%23013243?style=plastic&logo=numpy&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/pandas-%23150458?style=plastic&logo=pandas&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/matplotlib-grey?style=plastic&logo=matplotlib&logoColor=ffffff)|
|Cooperation Tools|![Static Badge](https://img.shields.io/badge/jira-%230052CC?style=plastic&logo=jira&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/confluence-%23172B4D?style=plastic&logo=confluence&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/slack-%234A154B?style=plastic&logo=slack)
|

데이터 출처 : [영화 관람객 데이터-KOBIS](https://www.kobis.or.kr/kobis/business/stat/boxs/findYearlyBoxOfficeList.do), [OTT 서비스 이용 데이터-방송통신위원회](https://kcc.go.kr/user.do?mode=view&page=A05030000&dc=&boardId=1113&cp=1&nop=10&ctx=ALL&searchKey=TITLE&searchVal=OTT&boardSeq=64815), [지표누리e-나라지표 문화사업 현황](https://www.index.go.kr/unity/potal/main/EachDtlPageDetail.do?idx_cd=2752), [KCTIdata 공연 티켓 판매건수 및 티켓 판매액](https://data.kcti.re.kr/data/%EB%AC%B8%ED%99%94%20%E2%80%A2%20%EC%BD%98%ED%85%90%EC%B8%A0/%EA%B3%B5%EC%97%B0_%ED%8B%B0%EC%BC%93%ED%8C%90%EB%A7%A4%EA%B1%B4%EC%88%98_%EB%B0%8F_%ED%8B%B0%EC%BC%93%ED%8C%90%EB%A7%A4%EC%95%A1)

***

## :hourglass_flowing_sand: 프로젝트 설계 및 개발 계획
- 소주제1 : 영화 산업의 연도별 추이를 통한 OTT와 코로나 이후의 영화 매출 추이 확인
- 소주제2 : OTT와 코로나 이후의 장르 흥행 추이 확인
- 소주제3 : 장르 흥행 추이에 따른 특별상영관 매출 추이
- 최종: 전체 분석 후 결론 도출, 가설 확인


|기간|계획|
|-----|-----|
|24.12.20 ~ 24.12.24|주제 선정 및 데이터 선별, 개발 계획|
|24.12.25 ~ 24.12.26|시각화 설계 및 데이터 수집, Jira/Confluence 세팅|
|24.12.27|ERD 작성 및 DB 작성 및 데이터 전처리|
|24.12.28 ~ 25.01.01|데이터 분석 및 시각화|
|25.01.02|최종 정리 및 발표자료 작성, GitHub 정리|

## :sparkles: 구성원 및 역할
|구성원|역할|
|-----|-----|
|심재헌(팀장)| 영화 스크린타입 데이터 추출 및 분석&시각화|
|이정림| 영화, 장르 추이 분석 및 시각화, ReadME 작성, AWS DB 관리, 발표자료 작성|
|임승연| OTT 및 영화 장르 흥행 차이 분석 및 시각화, ERD 작성, AWS DB 관리|

***
## 가설
1. 코로나 이후 영화 산업에서 급격한 변화가 보일 것이다.
2. 장르에 따라서 변화 추이가 다를 것이다.
3. 특별상영관에서 상영하는 영화 개수가 늘었을 것이다. 

***
## :bar_chart: 결과 브리핑

***

## :heavy_check_mark: 단계 별 개발 과정, 분석 결과 및 시각화
### 1. 설계 및 데이터 수집

#### 전체 ERD 
![image](https://github.com/user-attachments/assets/d2b4e225-d585-44a3-94d2-ff8360304f8e)
전체 영화 장르에 스크린타입에 Foreign Key를 주고 연결 

***movie TABLE***
![image](https://github.com/user-attachments/assets/86566dc1-aba6-43f6-af55-f1d3314f4eb6)

박스오피스 top 50
(2014~2023)
영화의 전체 차트
year:개봉년도
month:개봉년도
sale: 매출 
audience:관객수
screen : 스크린수
screen_number : 상영횟수


***screen TABLE***
![image](https://github.com/user-attachments/assets/a70bcee9-76f6-4fd8-8598-c892115ef35d)

특별상영관 data
name : 영화 이름
year : 개봉 년도 
screen_type : 스크린 종류
screening : 스크린별 상영횟수
sale : 스크린별 매출
audience :  스크린별 관객수




### 2. OTT별 매출액 비교 
![image](https://github.com/user-attachments/assets/d64dbe53-5c1d-4cc7-b795-35ef93cdb622)
넷플릭스가 나머지 OTT에 비해 압도적으로 강세. 따라서 OTT 흥행 시기를 넷플릭스를 기준으로 잡게 됨

### 3. 영화 연도별 추이 

#### 전체 추이 정리
|시기|사건|추이|
|-----|-----|-----|
|2016|Netflix 한국 서비스 시작|약간의 하락세, 금방 회복|
|2019|코로나 시작 직전 |가장 높은 위치|
|2020|코로나 시작 시점 |급격한 하락|


#### 3-1. 연도별 관객수 
![image](https://github.com/user-attachments/assets/2ee900fc-eb8d-4bd7-a2b9-49de3e20d0ca)

#### 3-2. 연도별 매출수 
![image](https://github.com/user-attachments/assets/f5a5dd9c-7e48-45f0-8748-7f508b0995a0)

#### 3-3. 연도별 스크린 수
![image](https://github.com/user-attachments/assets/d9796aef-a09d-4f7a-ae80-c1d431a5746b)

#### 3-4. 영화 연도별 분석 결론

관객수가 코로나 시작 시기인 2020년에 크게 떨어지고 회복이 더디게 되는 모습에서 OTT의 영향을 받았다는 것을 확인 가능했다.
회복이 되고는 있으므로 영화관 자체가 사라지지는 않을것으로 판단 가능했다.

### 4. 영화 장르 추이 

#### 4-1. OTT 이전/이후 장르별 관객수 
![image](https://github.com/user-attachments/assets/17b2b91a-60d9-4b42-bd0a-3b3b99dda2c5)
예외없이 모든 장르에서 코로나 이후로 줄었음을 확인 가능했다.
코로나 이전 OTT로 인한 변화는 뚜렷한 경향성이 보이지 않았다.


#### 4-2. OTT 이전/이후 장르별 개봉 영화 개수
![image](https://github.com/user-attachments/assets/51908a08-b839-4808-ad4c-8596ef0de20d)
관객수 그래프와 경향성이 비슷하다.
미스터리, 뮤지컬, 멜로/로맨스, 애니메이션은 다른 경향을 띄고 있다.

#### 4-3. OTT 이전/ 이후 장르별 매출 
![image](https://github.com/user-attachments/assets/867e9d0c-5f18-4da1-82b7-e16881c427b5)
매출은 관람객보다 상영한 영화의 개수의 추이를 따라 간다.

#### 4-4. 영화 장르별 분석 결론
다른 장르 들은 하락세인 와중에 멜로/로맨스, 뮤지컬, 미스터리는 상승되었다.관객 수와 이외의 시각화에서 경향이 다른 것은 상영관 별 가격 차이로 인해 기인한 것으로 판단된다.



### 5. 특별 상영관 변화 추이(변경 가능성 有)

#### 5-1. 상영 타입별 스크린 수 총합
![image](https://github.com/user-attachments/assets/daf4023f-8ef7-4b81-9adb-92803de347bb)
3D 좌석 수는 감소했으나 코로나 영향이 큰 2020, 2021년을 제외하고 4D와 Imax는 꾸준히 증가함.


#### 5-2. 상영 타입별 매출액
![image](https://github.com/user-attachments/assets/51ea82c3-d3d3-46d2-9a4c-4bc3839eb608)
매출액도 스크린 수와 비슷한 경향을 보이고 있다. 2020, 2021년을 제외하고 imax 타입의 스크린의 매출은 증가했다.

#### 5-3. 상영 타입별 분석 결론
사람들이 OTT 산업이 발전한 이후 이전에 비해 특별 상영관 선호도가 높아졌다.
영화관에 가서 좀 더 몰입감 있고 좋은 화면, 재밌고 흥미로운 경험을 하고 싶어하는 경향이 있음을 알 수 있다.


***

### 단계별 분석결과

#### 1. 분석 전에 세운 가설과 결론 분석
1. 코로나 이후 영화 산업에서 급격한 변화가 보일 것이다. 
2. 장르에 따라서 변화 추이가 다를 것이다.
3. 특별상영관에서 상영하는 영화 개수가 늘었을 것이다.

모든 가설이 다 사실이었음. 
다만 생각지 못한 멜로/로맨스, 판타지 등의 장르도 지속적인 수요가 있는 것으로 보였다.

#### 2. 이벤트 성 상영 
영화관의 존재 이유가 예전엔 영화의 시청이 주요 목적이었지만 이제는 **함께** 즐길 수 있는 **문화 생황**에 초점이 맞춰져 변화하고 있다. 
![image](https://github.com/user-attachments/assets/7e385565-4ff7-4134-b8a0-96878c584c11)

#### 3. 영화관과 OTT 산업의 방향성
한국 리서치 조사결과 OTT 등의 동영상 컨텐츠는 대체로 혼자 시청한다의 비율이 높았다. 
![image](https://github.com/user-attachments/assets/7a2e0448-4acd-41d4-808e-f0a793f83ff0)
OTT는 좀 더 **시청**에 초점이 맞춰져 있다면
영화관은 단순한 영화 시청의 목적보단 4D, IMAX 등의 특별한 상영관들의 매출이 증가함으로 보아 **문화 생활**에 점점 초점이 맞춰 변화하고 있다. 

## :bell: 최종 결론 및 개선 방안
* 사람들이 **OTT 산업이 발전한 이후** 이전에 비해 **특별 상영관 선호도가 높아졌다.**
* 영화관에 가서 좀 더 **몰입감 있고 좋은 화면, 재밌고 흥미로운 경험**을 하고 싶어하는 경향이 있음을 알 수 있다.

### 
## 개선 방안 
1. 영화와 OTT Top 20 순위를 찾아 순위에 대한 가중치 추가, 영화와 시리즈를 구분 지어 장르 분석
2. 장르 분석에서 관객수와 매출, 상영 횟수의 경향이 다른 경우의 정확한 원인을 분석
3. 유튜브의 영화 요약 정리 영상 등 영화 산업에 영향을 미치는 다른 요소들도 분석


### 
