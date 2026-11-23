# Acacia Launcher

Windows용 로블록스 런처입니다. 이 저장소는 배포용이고, 실행 파일은 [Releases](../../releases/latest)에 있습니다.

## 설치

1. [최신 릴리즈](../../releases/latest)에서 `AcaciaLauncher.exe`를 받습니다.
2. 실행하면 `%LocalAppData%\AcaciaLauncher`에 설치됩니다. 관리자 권한이 필요 없습니다.
3. SmartScreen 경고가 나오면 '추가 정보' → '실행'을 누릅니다 (코드 서명이 없는 exe).

받은 파일은 PowerShell에서 `Get-FileHash .\AcaciaLauncher.exe -Algorithm SHA256`으로 확인하고, 결과가 릴리즈 노트의 SHA256과 같을 때만 실행하세요.

요구 사항: Windows 10 또는 11 (64비트).

## 계정 정보

로블록스 로그인 쿠키, 비밀번호, 브라우저 저장 정보를 읽거나 보내지 않습니다. 로그인도 하지 않습니다.

## 파일

- `allowlist.json`: 런처가 실행할 때 받아 가는 FastFlag 허용 목록입니다.

## 라이선스

GPL-3.0 ([LICENSE](LICENSE)). 로블록스와 관계없는 비공식 프로그램입니다.
