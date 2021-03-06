
# ClassPrep 기술서

### 소개

| 기술 | 설명 |
| -- | -- |
| Codeigniter | PHP Framework |
| Bootstrap | Frontend Framework |
| AWS SDK | AWS Service SDK |
| FPDF | PDF Export Library |
| PHPExcel | Excel Export Library |
| PHPMailer | Mail Service Helper Library  |

| 폰트 | 설명 |
| -- | -- |
| NotoSans | Google |
| FontAwesome | twitter |


### 사용자분류
| 사용자 | 설명 |
| -- | -- |
| 관리자 | . |
| 기관 운영자 | . |
| 강사   | . |
| 조교 | . |
| 학생 | . |  

### 버전관리

| Version | 기능 |
| -- | -- |
| 1.0.0 | 클래스프렙 기초 평가기능 |
| 2.0.0 | 스케쥴링 기능, 질문 모듈 |
| 3.0.0 | 에세이&질문 모듈, 과제 커스터마이징 기능 |
| 3.1.0 | 에세이 모듈과 에세이&질문 모듈에 강사 페이크리뷰 기능 추가 |
| 3.1.1 | 강사페이지 점수 레포트 기능 추가 |
| Continue | 과제 생성 인터페이스 개선(기간 설정) |
|  | 게시판 기능 추가(자료실, 공지사항, 도움말) |
|  | 레포트기능 강화 |

###### V3.1.2 ( 게시판 기능 추가 )
클래스프렙 페이지 GNB에 게시판 탭을 추가한다.   
탭 안에는 자료실, 공지사항, 도움말이 추가된다.   
각 컨텐츠별 성격은 다음과 같다.   
1. 자료실 : 클래스프렙이 제안하는 오프라인 강의 컨텐츠
2. 공지사항 : 시스템 및 버전업 공지사항
3. 도움말 : 클래스프렙 도움말

###### V3.1.3 ( 과제 생성 인터페이스 개선 )
현재 과제 생성 및 수정작업의 인터페이스가 불편하다는 의견을 반영하여 수정   
[현재 적용 라이브러리 링크(Date Range Picker wite the Bootstrap)](http://www.daterangepicker.com/)  
-> 위 같은 방식이 아닌 더 단순한 방법으로 연/월/일/시간/분을 조정하도록 한다. 