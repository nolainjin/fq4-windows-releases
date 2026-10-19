# First Queen IV Unity — Windows 설치

[**Windows 설치 파일 다운로드 · 2026.10.19.2**](https://github.com/nolainjin/fq4-windows-releases/releases/download/v2026.10.19.2/FQ4-Setup-2026.10.19.2-x64.exe)

[전체 배포 버전](https://github.com/nolainjin/fq4-windows-releases/releases)

## 설치 방법

1. 위 링크에서 `FQ4-Setup-2026.10.19.2-x64.exe`를 다운로드합니다(약 621MB).
2. 실행 중인 게임을 종료한 뒤 설치 파일을 실행합니다.
3. 설치 완료 후 시작 메뉴의 **First Queen IV Unity**를 실행합니다.

Node.js, npm, Git 설치는 필요하지 않습니다. Windows 10 build 19043 이상과 x64 실행 환경이 필요합니다. 기본 설치 위치는 `%LOCALAPPDATA%\Programs\FQ4Unity`입니다.

## 이번 버전

게임 데이터를 무손실 압축해 설치 payload를 약 930MB에서 794MB로 줄였습니다(14.56% 감소). 설치 EXE는 중첩 압축 때문에 약 590MB에서 621MB로 증가했습니다. 기존 리소스의 해상도와 음원, 게임 규칙은 유지했습니다.

Windows VM에서 업데이트·재설치 및 자동 렌더링을 검증했습니다. 실제 OS 게임 입력, 물리 GPU·오디오, 장기 플레이와 FPS는 미검증입니다. 상세 범위는 [검증 요약](VERIFICATION.md)을 참고하세요.

## 파일 확인

다운로드한 파일의 SHA256:

```text
ba07d30f61a1170024db724c2929ede51a1af8b40d94b3d7a7a0c47eb9d4bc58
```

PowerShell에서 확인할 수 있습니다.

```powershell
Get-FileHash .\FQ4-Setup-2026.10.19.2-x64.exe -Algorithm SHA256
```

이 저장소는 Windows 설치본과 배포 안내를 제공합니다.
