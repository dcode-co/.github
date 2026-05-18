<div align="center">

# Dcode

**개발자가 처음 다섯 줄 안에 통합을 끝낼 수 있는 인프라를 만듭니다.**

[디코드(Dcode)](https://dcode-labs.com) 가 운영하는 오픈소스 조직입니다.
대표 제품은 ID 인프라 [**logi (1pass.dev)**](https://1pass.dev) — 한국 개발자/소규모 팀이
별도 KYC 없이 5분 안에 "Sign in with logi" 를 붙일 수 있는 OAuth 2.0 + OIDC IdP.

</div>

---

## Products

### 🔐 logi — Identity Provider (1pass.dev)

OAuth 2.0 + OIDC + PKCE. 모바일 우선 (앱-투-앱 핸드오프), 인앱 브라우저 escape, anonymous device login 지원.

| SDK | Repo | Install |
|---|---|---|
| **iOS / macOS** (Swift) | [`logi-auth-swift`](https://github.com/dcode-co/logi-auth-swift) | `.package(url: "https://github.com/dcode-co/logi-auth-swift", from: "0.2.0")` |
| **Android** (Kotlin) | [`logi-auth-android`](https://github.com/dcode-co/logi-auth-android) | `implementation("com.github.dcode-co:logi-auth-android:0.2.0")` |
| **Browser** (TypeScript) | [`logi-auth-browser`](https://github.com/dcode-co/logi-auth-browser) | `npm install @logi-auth/browser` |
| Flutter | _(Q3 2026)_ | — |
| React Native | _(Q3 2026)_ | — |

📖 **개발자 문서**: [docs.1pass.dev](https://docs.1pass.dev)
🧪 **라이브 데모**: [demo.1pass.dev](https://demo.1pass.dev)
🚀 **RP 등록 / 클라이언트 발급**: [start.1pass.dev/developer](https://start.1pass.dev/developer)

---

## Why logi

- **앱-투-앱 first**: Naver/Kakao 스타일의 native app handoff (Universal Links / Android Intent). Web fallback 자동.
- **인앱 브라우저 escape**: 카카오톡·네이버·페이스북 등 8개 인앱 환경에서 OAuth 가 막히지 않도록 escape 라우트 내장.
- **Zero-friction onboarding**: 사업자등록증/심사 없이 dev portal 에서 즉시 client_id 발급.
- **PKCE-only public clients**: 모바일 클라이언트 secret 노출 위험 원천 차단.
- **한국어 우선 docs**: 모든 SDK 문서가 한국어, 영어 quickstart 병기.

---

## Quick links

- 🌐 **회사 사이트**: [dcode-labs.com](https://dcode-labs.com)
- 📧 **연락처**: dcode.labs.kr@gmail.com
- 🐛 **이슈 / 기능 요청**: 각 SDK repo 의 Issues 탭
- 💬 **개발자 커뮤니티**: _(준비 중)_

---

<sub>© Dcode. MIT-licensed unless noted otherwise. 사업자등록번호 280-18-02841.</sub>
