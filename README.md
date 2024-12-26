![header](https://capsule-render.vercel.app/api?type=waving&&&color=timeGradient&height=200&section=header&text=영화산업%20이대로%20괜찮은가?&fontColor=ffffff&fontAlign=63&fontAlignY=30&animation=twinkling&fontSize=50&desc=Team1.%20EDA%20Project&descSize=30&descAlign=80)

## :dart: 주제 : OTT 서비스 변화에 따른 영화 관객 수 및 흥행 장르 변화
> 배우 황정민 수상 소감 中
>   > 영화가 많이 제작이 안 되고 조금 어렵긴 하지만...                
이 배우는 왜 이렇게 말을 했을까?


<img src="https://github.com/user-attachments/assets/31b5d722-1fc4-4ff7-853f-47ce0e9342e4" width="400" height="150"/>  <img src="https://github.com/user-attachments/assets/4a088b2b-8f3b-428f-af94-6e80da0ae8af" width="400" height="150"/>                               
<img src="https://github.com/user-attachments/assets/dbde6505-4fc0-4162-ae8f-9d26b3fe32e5" width="400" height="150"/>  <img src="https://github.com/user-attachments/assets/4d815d95-13ca-4500-b2dd-799223fd65f2" width="400" weight="150/">

위의 뉴스 헤드에서 영화 산업이 그리 좋지 않은 상황이라는 것을 알 수 있다.        
그렇다면 영화 산업에서 주가는 어떨까??           

![image](https://github.com/user-attachments/assets/f08fa30f-c3fa-4917-8a81-dbeb8048e529)
	@@ -19,4 +19,25 @@
그 이유는 무엇일까??             
우리 1팀은 위와 같은 영화 산업 부진의 이유를 OTT의 흥행으로 보고 데이터를 분석하여 시각화하는 EDA project를 진행했다.            
그리하여 우리가 세운 가설과 실제 데이터가 얘기해 주는 결과가 동일한 지 분석해 보았다.
***
### :computer: Skill Set
|Categories|SKills|
|------|------|
|IDE|![Static Badge](https://img.shields.io/badge/linux-%23FCC624?style=plastic&logo=linux&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/ubuntu-22.04-grey?style=plastic&logo=ubuntu&logoColor=ffffff&labelColor=%23E95420) ![Static Badge](https://img.shields.io/badge/vsCode-%232185D0?style=plastic&logo=vscode&logoColor=ffffff) |
|Design|![Static Badge](https://img.shields.io/badge/draw.io-%23F08705?style=plastic&logo=diagramsdotnet&logoColor=ffffff)|
|Programming|![Static Badge](https://img.shields.io/badge/Python-%233776AB?style=plastic&logo=python&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/jupyter-%23F37626?style=plastic&logo=jupyter&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/selenium-%2343B02A?style=plastic&logo=selenium&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/beautifulsoup-grey?style=plastic&logoColor=ffffff)|
|Data|![Static Badge](https://img.shields.io/badge/mysql-%234479A1?style=plastic&logo=mysql&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/amazonrds-%23527FFF?style=plastic&logo=amazonrds&logoColor=ffffff)|
|Analyzing&Visualization|![Static Badge](https://img.shields.io/badge/numpy-%23013243?style=plastic&logo=numpy&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/pandas-%23150458?style=plastic&logo=pandas&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/matplotlib-grey?style=plastic&logo=matplotlib&logoColor=ffffff)|
|Cooperation Tools|![Static Badge](https://img.shields.io/badge/jira-%230052CC?style=plastic&logo=jira&logoColor=ffffff) ![Static Badge](https://img.shields.io/badge/confluence-%23172B4D?style=plastic&logo=confluence&logoColor=ffffff)|

데이터 출처 : [영화 관람객 데이터-KOBIS](https://www.kobis.or.kr/kobis/business/stat/boxs/findYearlyBoxOfficeList.do), [OTT 서비스 이용 데이터-방송통신위원회](https://kcc.go.kr/user.do;jsessionid=49R9Ts8hWujamVPcMQChnvSI9ZFh3vOFNXQJk9CY.servlet-aihgcldhome10?mode=view&page=A05030000&dc=&boardId=1113&cp=1&nop=10&ctx=ALL&searchKey=TITLE&searchVal=OTT&boardSeq=64815)

***

### :hourglass_flowing_sand: 프로젝트 설계 및 개발 계획
- 소주제1 : OTT 서비스 흥행 전/후의 영화 관객수 변화
- 소주제2 : OTT 서비스 사용자 수 변화에 따른 영화 관객수 변화
- 소주제3 : 연도 별 영화 흥행 장르 변화
- 최종 : OTT 서비스 변화에 따른 영화 총 관객수 및 영화 흥행 장르 변화

|기간|계획|
|-----|-----|
|24.12.20 ~ 24.12.24|주제 선정 및 데이터 선별, 개발 계획|
|24.12.25 ~ 24.12.26|시각화 설계 및 데이터 수집, Jira/Confluence 세팅|
|24.12.27|ERD 작성 및 DB 작성 및 데이터 전처리|
|24.12.28 ~ 24.12.30|데이터 분석 및 시각화|
|24.12.31 ~ 24.01.02|최종 정리 및 발표자료 작성, GitHub 정리|

### :sparkles: 구성원 및 역할
|구성원|역할|
|-----|-----|
|심재헌(팀장)|OTT 서비스 사용자 수 변화에 따른 영화 관객수 변화 데이터 분석 및 시각화, AWS DB 관리|
|이정림|연도 별 흥행 영화 장르 데이터 분석 및 시각화, OTT 서비스 변화에 따른 영화 흥행 장르 변화, ReadME 작성|
|임승연| OTT 서비스 흥행 전(5년)/후의 영화 관객수 변화 데이터 분석 및 시각화, ERD 작성|

***

### :bar_chart: 결과 브리핑

***

### :heavy_check_mark: 단계 별 개발 과정, 분석 결과 및 시각화

***

### :bell: 최종 결론 및 개선 방안
