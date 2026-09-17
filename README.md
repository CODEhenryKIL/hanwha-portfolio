# 길민규 · 서비스·사업기획 포트폴리오

한화생명 개인 지원용 슬라이드 포트폴리오. HTML, CSS, JavaScript로 구성한 정적 사이트입니다.

- 방향키와 스와이프로 슬라이드 이동
- 목차, 전체 슬라이드 보기, 확대·전체 화면, 텍스트 읽기
- 16페이지 PDF 다운로드
- 별도 설치나 빌드 없이 GitHub Pages에서 실행

## 배포

GitHub 저장소 Settings → Pages → Deploy from a branch → main / (root).
로컬에서는 이 폴더에서 `python3 -m http.server 4173` 실행 후 `http://localhost:4173`을 엽니다.

## 파일

- `index.html`: 사이트 레이아웃, 스타일, 슬라이드 정보 및 동작
- `assets/slides/`: 1920×1080 원본 비율의 웹용 슬라이드
- `assets/thumbs/`: 목차 미리보기
- `portfolio.pdf`: 다운로드용 PDF
- `assets/fonts/`: Pretendard 폰트와 라이선스

회사 공식 제작물이 아닌 개인 지원용 자료입니다. 폰트 외 콘텐츠의 권리는 각 원저작자에게 있습니다.
