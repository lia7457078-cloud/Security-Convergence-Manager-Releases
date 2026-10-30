# Security Convergence Manager — Windows releases

안보융합원 관리 프로그램의 Windows 무설치 배포 저장소입니다.

## 다운로드

[최신 릴리스](https://github.com/lia7457078-cloud/Security-Convergence-Manager-Releases/releases/latest)에서 `security-convergence-manager-windows-x64.zip`을 내려받아 압축을 모두 푼 뒤 `안보융합관리.exe`를 실행합니다.

자동 업데이트를 지원하는 버전은 시작할 때 새 버전을 확인하고, 내려받은 업데이트를 다음 실행부터 적용합니다. GitHub 로그인·토큰·Git 설치가 필요하지 않습니다. 인터넷에 연결되지 않으면 현재 버전을 계속 사용합니다.

이 저장소에는 프로그램 배포 파일과 서명된 업데이트 명세만 게시합니다. 업무 데이터·학생/교수 명단·사진·계정·노션 연결 토큰·서명 개인키는 포함하지 않습니다. 기존 소스 저장소는 별도 비공개로 관리합니다. 업무 자료의 최초 연결과 사용 권한은 자동 업데이트와 별개입니다.

## 업데이트 검증 파일

- `update-manifest.json`: 버전·파일 크기·SHA-256
- `update-manifest.sig`: 제작자 Ed25519 서명
- `security-convergence-manager-windows-x64.zip`: Windows 실행 파일과 구성 요소

프로그램은 내장 공개키로 서명을 검증한 파일만 적용합니다. Windows의 코드 서명 인증서와는 별개이며, Windows의 보안 설정을 자동으로 변경하지 않습니다.

포함된 오픈소스 구성 요소의 라이선스는 배포 폴더의 `LICENSES`와 `THIRD_PARTY_NOTICES.txt`에서 확인할 수 있습니다.
