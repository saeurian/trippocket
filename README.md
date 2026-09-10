# Trip Pocket — GitHub Pages 배포용

이 폴더의 파일을 GitHub 저장소 최상단(root)에 업로드하세요.

필수 파일
- `index.html`
- `.nojekyll`

배포 순서
1. GitHub에서 새 Repository 생성 (예: `trip-pocket`)
2. 이 폴더의 파일을 Repository 최상단에 업로드하고 Commit
3. Repository → Settings → Pages
4. Build and deployment → Source: `Deploy from a branch`
5. Branch: `main`, Folder: `/(root)` → Save
6. 잠시 후 `https://사용자명.github.io/trip-pocket/` 형태로 접속

주의
- 현재 앱 데이터는 브라우저 localStorage에 저장되므로 기기 간 자동 공유는 아직 되지 않습니다.
- GitHub Pages 배포 후 Google Maps API 키의 Website referrer 제한을 Pages 주소로 설정하는 것을 권장합니다.
- HTML에 비밀키나 서비스 계정 키를 직접 넣지 마세요.
