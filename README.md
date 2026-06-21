# Orbis

화면 끝에 떠 있는 Windows 데스크톱 AI. Claude와 ChatGPT 구독을 그대로 쓰는 작은 오브입니다.

**홈페이지:** https://poi82999.github.io/orbis/
**다운로드:** [Releases](https://github.com/poi82999/orbis/releases/latest)

이 저장소는 Orbis의 **배포(홈페이지 + 릴리스)** 전용입니다.

## 설치

1. 최신 릴리스 ZIP을 받아 압축을 풉니다.
2. 풀어낸 폴더에서 PowerShell로 실행합니다.

```powershell
powershell -ExecutionPolicy Bypass -File .\scripts\check-environment.ps1 -RequireClaude
powershell -ExecutionPolicy Bypass -File install.ps1
```

설치 후 `Ctrl+Alt+C` 또는 시작 메뉴의 `오르비스`로 엽니다.

## 요구사항

- Windows 10 / 11 (PowerShell 5.1 기본 포함)
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code/quickstart) 설치 및 로그인 (필수)
- ChatGPT 모드: Codex CLI (선택) · 컴퓨터 모드: Node.js (선택)

자세한 사용법은 릴리스 ZIP 안의 `USER_GUIDE.md`를 참고하세요.
