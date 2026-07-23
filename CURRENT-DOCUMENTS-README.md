# 학생·교사 웹 앱 설계 문서 인수인계

이 저장소는 2026년 7월 24일 기준 최신 문서만 모은 1부 1.1 공개 검토판입니다.

1.1판에서는 Callable 인증 누락 처리, Firestore Rules의 승인 멤버십·변경 필드 검사, Gemini Developer API의 연령·약관 중단 조건, Apps Script 맞춤형 인증의 적용 한계와 읽기 경로를 보완했습니다.

## 새 대화에서 읽는 순서

1. `web-app-design-master-index.html`
2. 마스터 인덱스의 `0장 안전 등급`
3. 기술 경로별 필수 문서
4. `firebase-student-teacher-security-baseline.html`을 배포 전 통과 기준으로 확인

### Firebase 필수 경로

1. `github-pages-firebase-vibe-coding-guide.html`
2. `login-oauth-security-audit.html`
3. `firebase-student-teacher-security-baseline.html`

### Apps Script 필수 경로

1. `apps-script-screen-architecture-guide.html`
2. `apps-script-auth-security-audit.html`
3. 접근 코드가 꼭 필요한 저위험 앱만 `apps-script-access-code-security-guide.html`

나머지 문서는 배포 비교, 비밀번호, AI, SOP·CORS, Firestore·Supabase를 더 깊이 확인할 때 선택적으로 읽습니다.

## 새 대화 시작 요청문

첨부한 파일은 학생·교사 웹 앱 설계 문서 프로젝트의 현재 최신본입니다.

먼저 `web-app-design-master-index.html`을 읽어 문서 번호, 확정 원칙과 향후 작업 방향을 파악하세요. 다음으로 `firebase-student-teacher-security-baseline.html`을 읽어 1부의 최종 보안 기준을 확인하세요.

나머지 문서는 현재 작업과 직접 관련된 부분만 선택적으로 참고하세요. 모든 문서를 처음부터 다시 요약하거나 기존 결론을 임의로 변경하지 마세요.

현재 1부는 1.1 공개 검토판입니다. 2부에서는 React·Vite와 Next.js, Git, Netlify와 Vercel, 서버리스 함수, 환경 변수와 API 비밀키, Emulator 테스트, CI 배포, 업데이트와 롤백을 다룹니다.

이후 3부에서는 개인정보 최소 수집, 데이터 보존·삭제, 로그·비용 관찰, 백업·복구, 학년 변경·퇴직자 권한 회수, 사고 대응과 접근성 등 실제 운영 기준을 다룹니다.

새 문서를 만들 때는 기존 DOC 01~12 번호와 파일 이름을 유지하고, 마스터 인덱스도 함께 갱신하세요.

## 포함 문서

- `web-app-design-master-index.html`
- `github-pages-firebase-guide.html`
- `single-github-pages-firebase-guide.html`
- `firebase-password-auth-guide.html`
- `login-oauth-security-audit.html`
- `apps-script-screen-architecture-guide.html`
- `apps-script-auth-security-audit.html`
- `apps-script-access-code-security-guide.html`
- `github-pages-firebase-vibe-coding-guide.html`
- `firebase-gemini-feedback-guide.html`
- `browser-server-sop-cors-guide.html`
- `firestore-rules-supabase-guide.html`
- `firebase-student-teacher-security-baseline.html`

구버전, `-v2` 파일, 취소된 GitHub Pages·Apps Script 하이브리드 문서는 포함하지 않았습니다.
