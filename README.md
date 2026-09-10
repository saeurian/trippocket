# Trip Pocket Cloud v33

GitHub에는 `index.html`만 교체하면 됩니다.

v33 변경사항
- Google Maps API key를 HTML에서 완전히 제거
- Google Maps key를 localStorage에도 저장하지 않음
- Supabase 로그인 후 `get_google_maps_key()` RPC로 메모리에만 로드
- 앱 소유자와 소유자가 공유한 여행의 멤버만 공용 Google Maps key 사용 가능
- 로그아웃 시 페이지를 새로고침하여 메모리의 Maps 연결도 정리
- 기존 Supabase 여행 공유/자동동기화/여행 삭제/UI 유지

주의
- 별도로 제공된 `trip-pocket-supabase-v33-google-maps-secret.sql`은 Supabase SQL Editor에서만 실행하세요.
- SQL 파일은 절대 GitHub 저장소에 업로드하지 마세요.
