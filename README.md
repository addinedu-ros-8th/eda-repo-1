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
- 최종: 영화 산업의 전체적인 매츨이 줄었으나 특정 장르들과 특정 상영관에 대해서는 매출이 변화가 크지 않거나 증가할 것이다. 

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

## :bar_chart: 결과 브리핑

***

## :heavy_check_mark: 단계 별 개발 과정, 분석 결과 및 시각화
### 1. 설계 및 데이터 수집

#### 전체 ERD 
![image](https://github.com/user-attachments/assets/d2b4e225-d585-44a3-94d2-ff8360304f8e)



### 1. 영화 연도별 매출 추이 

#### 1-1. 연도별 관객수 
![image](https://github.com/user-attachments/assets/2ee900fc-eb8d-4bd7-a2b9-49de3e20d0ca)

#### 1-2. 연도별 매출수 
![image](https://github.com/user-attachments/assets/f5a5dd9c-7e48-45f0-8748-7f508b0995a0)

#### 1-3. 연도별 스크린 수
![image](https://github.com/user-attachments/assets/d9796aef-a09d-4f7a-ae80-c1d431a5746b)



### 2. 영화 장르 추이 

#### 2-1. OTT 이전/이후 관객수 
![image](https://github.com/user-attachments/assets/17b2b91a-60d9-4b42-bd0a-3b3b99dda2c5)

#### 2-2. OTT 이전/이후 개봉 영화 개수
![image](https://github.com/user-attachments/assets/51908a08-b839-4808-ad4c-8596ef0de20d)

#### 2-3. OTT 이전/ 이후 매출 
![image](https://github.com/user-attachments/assets/867e9d0c-5f18-4da1-82b7-e16881c427b5)


### 3. 특별 상영관 변화 추이(변경 가능성 有)

#### 3-1. 
![image](https://github.com/user-attachments/assets/daf4023f-8ef7-4b81-9adb-92803de347bb)

![image](https://github.com/user-attachments/assets/51ea82c3-d3d3-46d2-9a4c-4bc3839eb608)



***

## :bell: 최종 결론 및 개선 방안

### 


### 
