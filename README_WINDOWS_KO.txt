Grok Studio Lab - Windows 포터블 버전
=====================================
V5: Gallery 미포함, 확장 Image Editor 버전

실행 방법
---------
1. 압축파일 전체를 원하는 폴더에 풉니다.
2. run_grok_studio_windows.bat 파일을 더블클릭합니다.
3. 잠시 후 기본 브라우저에서 Grok Studio Lab이 열립니다.

별도의 Python 설치는 필요하지 않습니다. python 폴더의 내장 Windows Python을 사용합니다.

문제 확인용 실행
---------------
실행되지 않거나 오류를 확인해야 할 때는
run_grok_studio_windows_console.bat 파일을 실행합니다.

숨김 실행 로그:
grok_studio_data_v5\logs\grok_studio.log

서버 종료:
stop_grok_studio_windows.bat

라이브러리 폴더
---------------
- Set Library Path 버튼을 누르면 Windows 폴더 선택 창이 열립니다.
- Open Folder 버튼을 누르면 Windows 파일 탐색기로 현재 라이브러리 폴더가 열립니다.
- 선택한 라이브러리 경로는 다음 실행에도 유지됩니다.

인증
----
기본 인증 파일 위치:
%USERPROFILE%\.grok\auth.json

사용자가 직접 로그인하여 만든 합법적인 Grok/xAI OAuth 인증 파일이 필요합니다.
앱의 Account 화면에서 다른 인증 파일을 등록하고 전환할 수도 있습니다.

FFmpeg
------
영상의 일시정지 지점부터 Extend 기능을 사용하려면 ffmpeg를 별도로 설치하고
Windows PATH에 추가해야 합니다. 일반 이미지/영상 생성에는 필수가 아닙니다.

주의
----
- grok_studio_data_v5 폴더에는 설정, 계정 스냅샷, 로컬 라이브러리 정보가 저장됩니다.
- 다른 사람에게 재배포할 때는 grok_studio_data_v5 안의 개인 데이터와 로그를 제거하세요.
- 이 앱은 127.0.0.1에서만 실행되는 로컬 웹앱입니다.
