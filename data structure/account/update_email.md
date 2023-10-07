# login_rename.csv
로그인 이름 변경 기록을 담고 있는 파일


## 구조
헤더 | 설명
--|--
time | 이벤트가 발생한 시간
time_utc | UTC 시간으로 표시되는 이벤트가 발생한 시간
ip | 사용자의 IP 주소
city | 사용자의 도시
country | 사용자의 국가
region | 사용자의 지역
asn_id | 사용자의 ASN(Autonomous System Number)
type | 이벤트의 유형
device_software | 사용자의 기기 소프트웨어
logged_in | 사용자가 로그인한지 여부
system_version | 사용자의 시스템 버전
device_os_version | 사용자의 기기 운영 체제 버전
app_version | 사용자의 앱 버전
client_time | 사용자의 클라이언트 시간
platform | 사용자의 플랫폼 (web, mobile)
device_type | 사용자의 기기 유형
device_model | 사용자의 기기 모델
app_window_width | 사용자의 앱 창 폭
device_id | 사용자의 기기 ID
turbo | 사용자가 Turbo 모드를 사용하고 있는지 여부
adv_id | 사용자의 광고 ID
app_build | 사용자의 앱 빌드 번호
app_window_height | 사용자의 앱 창 높이
user_id | 사용자 ID
orientation | 사용자 기기의 방향
login | 로그인한 사용자 이름



## 비고
`asn_id`: 불확실



## 누락 정보
* Type
* Device Software
* System Version
* Device OS Version
* Device Type
* Device Model
* App Window Width
* Turbo
* Adv ID
* App Build
* App Window Height
* Orientation