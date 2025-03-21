## 📚 1st agile
### 🔍 주식 데이터 수집 및 사용자 친화적 시각화 시스템 구축 🔍
<br>
<h4>📌 설명</h4> 

본 프로젝트의 1차 목표는 증권사의 API와 다양한 데이터 소스를 활용하여 주식 예측에 필요한 과거 데이터를 수집, 가공 및 데이터베이스 설계 후, 이를 Django 프레임워크와 연동하여 사용자에게 시각적으로 이해하기 쉬운 주식 데이터를 제공하는 웹 애플리케이션을 구축하는 것이다.
사용자는 주식 데이터를 통해 시계열 분석, RSI 지표를 확인하고, 주요 기업의 과거 데이터를 시각화하여 투자 판단에 필요한 인사이트를 얻을 수 있다.
<br><br>



#### 📌 프로젝트 주요 내용
⓵ **데이터 수집 및 가공**
> 한국투자증권 API를 통해 과거 주식 데이터를 수집하여 단기, 중기, 장기 투자에 필요한 데이터를 준비<br>
> RSI 계산 함수를 `Python`으로 작성하여, 과매수/과매도 상태를 파악할 수 있는 주요 지표 생성<br>
> 네이버 주식 데이터를 활용하여 분당 주식 차트 데이터를 실시간으로 수집<br>
> 크롤링을 통해 AI 투자와 관련된 주요 기업 리스트와 종목 코드를 확보

⓶ **사용자 화면 시각화**
> 메인 페이지 : 서비스 소개와 네비게이션 바를 포함하여 사용자에게 직관적인 첫 화면 제공<br>
> 차트 인덱스 페이지 : 기업별 과거 데이터를 조회할 수 있는 가이드 제공<br>
> 차트 그래프 페이지: `ApexChart`를 활용하여 기업별 데이터를 차트로 시각화.

⓷ **데이터베이스 설계** 
> `AWS RDS`와 `MySQL`을 사용하여 주식 데이터를 저장 및 관리<br>
> `.env` 파일을 활용하여 `Django`와 `MySQL` 간의 안전한 연결 구현<br>
> 
<br>

#### 📌 프로젝트 주요 사용기술
⓵ 데이터 수집 및 전처리  
> `Python`: 데이터 수집 및 분석.<br><br>
> `BeautifulSoup`, `Requests`: 웹 크롤링 및 API 활용.<br><br>
> `Pandas`, `Numpy`: 데이터 정제 및 가공.  

⓶ 데이터베이스  
> `MySQL`: 데이터 저장 및 관리.<br><br>
> `AWS RDS`: 클라우드 기반 데이터베이스 운영.<br>  

⓷ 웹 프레임워크 및 시각화  
> `Django`: 백엔드 및 웹 애플리케이션 개발.<br>  
> `HTML`, `CSS`, `JavaScript`: 사용자 인터페이스 및 상호작용 구현.<br>  
> `ApexChart`: 주식 데이터 시각화.<br>  

<br>   

#### 📚 프로젝트 결과


<br>

#### 🎯 프로젝트 주요 가치 및 활용점
> 이 프로젝트는 주식 데이터를 효율적으로 수집, 정제 및 시각화하여 사용자에게 투자 판단에 필요한 정보를 제공하는 것을 목표로 하였다.
단순 데이터 제공을 넘어, 사용자 경험을 고려한 UI와 투자 지표 계산을 통해 개인 투자자들에게 실질적인 도움을 줄 수 있는 서비스로 발전 가능성을 확인할 수 있었다.<br><br>
> 개인적으로, 데이터베이스 설계, AWS 배포, 웹 프레임워크(Django)를 활용한 프로젝트를 통해 데이터 수집에서 시각화까지의 전체 개발 과정을 경험할 수 있었다.
팀원들과의 협업을 통해 효율적인 역할 분담과 커뮤니케이션의 중요성을 배우는 소중한 기회가 되었으며, 이를 기반으로 차후 프로젝트의 방향성을 명확히 설정할 수 있었다.

<br><br>
