# eat-guide

다이어리 QR코드 연결용 고정 주소 저장소입니다.

| 고정 주소 (QR에 넣는 주소) | 연결 대상 (구글 드라이브 PDF) | 수정할 파일 |
|---|---|---|
| https://sj-parkk.github.io/eat-guide/term1/ | 공공급식통합플랫폼 회원관리 운영지침 | `term1/index.html` |
| https://sj-parkk.github.io/eat-guide/term2/ | 공공급식통합플랫폼 이용약관 | `term2/index.html` |

기본 주소(https://sj-parkk.github.io/eat-guide/)는 두 문서의 목록 페이지입니다.

## 관리 방법
- PDF 내용 수정: 구글 드라이브에서 '파일 정보 → 버전 관리 → 새 버전 업로드' (이 저장소는 수정 불필요)
- 연결 대상 변경: 해당 파일의 드라이브 링크 2곳을 수정 후 커밋
- 문서 추가: 새 폴더(예: `term3`)를 만들고 `term1/index.html`을 복사해 링크만 교체

## 주의
- 저장소 이름·폴더 이름·GitHub 사용자명·공개 설정을 변경하거나 저장소를 삭제하면 QR코드가 작동하지 않습니다.

## QR코드 이미지 (`qr/` 폴더)
| 파일 | 담긴 주소 | 비고 |
|---|---|---|
| `qr/term1.png` | https://sj-parkk.github.io/eat-guide/term1/ | GitHub 주소 직접 연결 (권장) |
| `qr/term2.png` | https://sj-parkk.github.io/eat-guide/term2/ | GitHub 주소 직접 연결 (권장) |
| `qr/term1_naver.jpg` | https://m.site.naver.com/2ixLk | 네이버 QR — 네이버 서비스·계정에 추가 의존 |
| `qr/term2_naver.jpg` | https://m.site.naver.com/2ixLJ | 네이버 QR — 네이버 서비스·계정에 추가 의존 |
