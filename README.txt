PASS WebApp (홈 화면 추가용) — 사용법

1) 폴더 파일 구성
   - index.html
   - icon.png (앱 아이콘)
   - manifest.json (선택; iOS는 메타 태그로 처리, 안드로이드 호환용)
   - myvideo.mov  ← 여기에 본인 영상 파일을 이 이름으로 넣으세요
   - (선택) myvideo.mp4  ← 크롬/PC 호환까지 원하면 같이 넣으세요

2) 로컬 서버로 열기 (권장)
   - PC에서 이 폴더로 이동한 다음:
     Windows:   python -m http.server 8000
     macOS/리눅스: python3 -m http.server 8000
   - 아이폰 Safari에서 같은 Wi‑Fi로 접속:
     http://<PC아이피>:8000/index.html

3) 홈 화면에 추가
   - 아이폰 Safari 하단 공유 버튼(⬆️) → "홈 화면에 추가" → 추가

4) 실행
   - 홈 화면 아이콘으로 실행 후, 보라 카드 또는 '전체화면 재생' 버튼을 누르면
     동영상(myvideo.mov 또는 mp4)이 전체화면으로 재생됩니다.
