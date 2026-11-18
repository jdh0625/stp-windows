# STP 스텍피 — Windows 설치 파일 (파일럿)

업무 화면을 클릭하는 대로 기록해서 인수인계·교육·업무 기록 노트(PDF)로 정리해 주는 프로그램의 **Windows 설치 파일**만 올려 두는 곳이에요. 소스 코드는 없어요.

- 설치 안내: https://stp-step.netlify.app/windows
- 받기: 오른쪽 **Releases**에서 PC에 맞는 파일을 받아요.
  - `STP-Stepi-Setup-smb.exe` — 회사 PC(중견·중소기업)
  - `STP-Stepi-Setup-enterprise.exe` — 대기업 PC
  - `STP-Stepi-Setup-worker.exe` — 개인 PC
- 설치 전에 PC 환경을 먼저 점검하고, 막히는 게 있으면 설치하지 않아요. 관리자 권한 없이 내 계정에만 설치돼요.
- 아직 코드 서명 전인 파일럿 버전이라 실행할 때 "Windows의 PC 보호" 창이 뜰 수 있어요. **추가 정보 → 실행**을 누르면 돼요.
- 화면과 기록은 이 PC에만 저장되고 서버로 보내지 않아요. 개인정보 처리방침: https://stp-step.netlify.app/privacy
- 파일이 바뀌지 않았는지는 각 Release에 적힌 SHA-256 값과 비교해 확인할 수 있어요 (PowerShell: `Get-FileHash 파일이름`).

문의: jftgj00625@gmail.com

© STP 스텍피. 이 저장소의 설치 파일은 무단 재배포·수정을 허용하지 않아요.
