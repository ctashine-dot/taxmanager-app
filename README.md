# TaxManager

세무사무소 거래처 관리 앱의 정적 배포본입니다.
GitHub Pages 로 서비스됩니다 → https://ctashine-dot.github.io/taxmanager-app/

## 자료는 이 저장소에 없습니다

거래처·신고·수수료 자료는 Firebase Realtime Database 에 **사용자 계정별로**
저장되며, 본인 계정만 읽고 쓸 수 있도록 보안 규칙으로 잠겨 있습니다.
이 저장소에는 화면 코드만 있습니다.

포함된 Firebase 설정값(apiKey 등)은 공개를 전제로 설계된 클라이언트 식별자이며,
그 자체로는 데이터에 접근할 수 없습니다.

## 구성

| 파일 | 용도 |
|---|---|
| `index.html` | 앱 본체 (단일 파일) |
| `manifest.json` | 홈 화면 추가(PWA) |
| `sw.js` | 오프라인 캐시 |
| `cmaps/` | 한글 PDF 신고서 텍스트 추출용 |

개발 저장소: `ctashine-dot/taxmanager` (비공개)
