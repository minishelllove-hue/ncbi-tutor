NCBI AI Tutor PWA 설치/배포 안내

구성 파일
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

중요
PWA 설치 기능과 Service Worker는 file:// 로 직접 열 때가 아니라 HTTPS 웹서버(또는 localhost)에서 제공할 때 정상 작동합니다.

아이폰: Safari에서 접속 → 공유 → 홈 화면에 추가
안드로이드: Chrome에서 접속 → 앱 설치 또는 홈 화면에 추가

현재 AI 대화는 외부 API를 호출하지 않는 규칙형 학습 도우미입니다.
