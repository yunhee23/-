# 경복궁 문화유산 탐방 · jQuery Mobile 3단계 실습

- `경복궁_jQueryMobile_3단계_강의교안.html` : 교수자·학생용 HTML 강의교안
- `STEP_01/index.html` : 홈 화면·소개·접이식 설명
- `STEP_02/index.html` : 1단계 + 외부 영상·로컬 MP4·오디오 페이지 2개
- `STEP_03/index.html` : 2단계 + 12개 이미지 갤러리·확대 팝업
- `assets/` : 교육용 일러스트 JPG 12개, MP4 1개, 창작 샘플 MP3 2개, 공통 CSS/JS
- `vendor/` : 첨부 샘플에 포함되어 있던 jQuery 3.7.1(MIT) 오프라인 보조 라이브러리

## 사용
1. ZIP 압축을 풀어 상위 폴더 구조를 그대로 유지합니다.
2. VS Code의 Live Server에서 STEP_01/index.html을 실행한 후 STEP_02, STEP_03 순서로 실습합니다.
3. 인터넷 연결 시 jQuery 1.11.1 + jQuery Mobile 1.4.5 CDN으로 작동합니다.
4. 인터넷 차단 시 포함된 jQuery Core 3.7.1과 교육용 보조 CSS/JS로 주요 화면 전환과 멀티미디어 및 갤러리 실습을 계속할 수 있습니다. 이 경우 jQuery Mobile 고유 위젯 렌더링은 작동하지 않으며 스타일이 일부 다릅니다.
5. 외부 유튜브 동영상만 인터넷 접속과 제공자의 임베딩 정책을 필요로 합니다. MP4/MP3/JPG는 별도 접속 없이 이용할 수 있습니다.

## 유의
- 원본 실습 HTML에 있던 `cordova.js`는 Cordova 패키징 시 자동 주입되는 파일이므로 일반 브라우저 실습에서는 제거했습니다.
- 실습 파일의 사진은 실제 촬영 이미지가 아닌 교육용 창작 일러스트입니다.
- MP4는 이미지 슬라이드 데모이고 MP3는 실습용 창작 멜로디입니다.
- jQuery Mobile 1.4.5는 2014년 배포된 레거시 버전입니다. 최신 서비스에는 별도 기술 평가가 필요합니다.
- 문서의 경복궁 역사 소개는 간략화되어 있습니다. 공식 자료는 https://royal.khs.go.kr/ROYAL/contents/menuInfo-gbg.do 를 확인하세요.
- jQuery Mobile 공식 다운로드: https://jquerymobile.com/download/
- 동영상 출처: Korea Heritage Service 공개 유튜브 온라인 궁궐 탐방 (링크 임베드만 사용): https://www.youtube.com/watch?v=ItHgCMU200o
