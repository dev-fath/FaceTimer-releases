# FaceTimer

알림을 놓치지 않도록 전체화면으로 알려 주는 맥 메뉴바 앱. (소스는 비공개, 이 저장소에는 배포 파일만 있다)

## 설치

1. [최신 릴리스](https://github.com/dev-fath/FaceTimer-releases/releases/latest)에서 `FaceTimer-<버전>.dmg` 를 받는다.
2. DMG를 열고 FaceTimer를 Applications 폴더로 끌어다 놓는다.
3. 애플 공증을 받지 않은 앱이라 처음 한 번은 직접 허용해야 한다.
   - 실행 → 경고가 뜨면 **시스템 설정 → 개인정보 보호 및 보안 → "그래도 열기"**, 또는
   - 터미널에서 `xattr -dr com.apple.quarantine /Applications/FaceTimer.app`

macOS 14 이상, Apple Silicon·Intel 모두 지원. 이후 업데이트는 앱이 알아서 확인한다 (설정 → 업데이트 확인…).
