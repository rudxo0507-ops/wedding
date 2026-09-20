# Wedding Photo Share

모바일 전용 사진·영상 공유 페이지입니다.

- 신랑: 고경환
- 신부: 박수진
- 예식일: 2026.10.17
- 공개 페이지 경로: `/wedding/photo-share/`
- 사진/동영상은 Google Drive 비공개 폴더로 업로드
- Google Drive 폴더 자체는 공개하지 않음

## 남은 설정

`photo-share/config.js`의 `backendUrl`에 현재 작동 중인 Google Apps Script 웹앱 `/exec` 주소를 입력해야 합니다.

Apps Script에는 GitHub Pages용 `bridge.html` 및 bridge용 `doGet` 구성이 필요합니다.
