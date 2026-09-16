# CST FNF LOOKBOOK

룩북 편집 내용을 **이 저장소 폴더**에 저장하고, GitHub Pages로 게시하는 구조예요.

```
index.html            룩북 화면
data/lookbook.js      [저장] 버튼이 만드는 편집 데이터 (직접 고치지 마세요)
assets/               사진·영상 (같은 사진은 한 번만 저장돼요)
```

## 처음 한 번만

1. **GitHub Desktop**에서 `File → Add local repository`로 이 폴더를 추가하고 `Publish repository`로 올립니다.
2. GitHub 웹에서 저장소 `Settings → Pages`로 들어가 Branch를 `main` / `/(root)`로 저장합니다. 1~2분 뒤 게시 주소가 생겨요.
3. 다른 편집자는 GitHub Desktop에서 `File → Clone repository`로 받아 둡니다.

## 편집하고 게시하기

1. GitHub Desktop에서 **Fetch origin → Pull**로 최신본을 받습니다.
2. 저장소 폴더의 `index.html`을 **Chrome 또는 Edge**로 엽니다.
3. 편집한 뒤 오른쪽 위 **저장**을 누릅니다. 처음에는 폴더 선택창이 뜨니 이 저장소 폴더를 고르고 권한을 허용하세요.
4. GitHub Desktop에서 변경 내용을 확인하고 **Commit → Push**하면 1~2분 뒤 게시 주소에 반영돼요.

## 내보내기

- **HTML 내보내기**: 사진이 모두 들어 있는 파일 하나로 받아요. 로컬에서 열었을 때는 저장소 폴더 연결이 필요해요.
- **PDF 내보내기**: 인쇄 창이 뜨면 대상을 **PDF로 저장**으로 고르세요. A4 가로, 카테고리별로 한 페이지씩 나뉘어요.
- 가먼트 보드에서는 **이 페이지 HTML / 이 페이지 PDF**로 현재 보드만 내보낼 수 있어요.

## 주의

- 편집 전에는 꼭 Pull, 편집 후에는 바로 Push 하세요. 두 사람이 같은 시간에 편집하면 `data/lookbook.js`가 충돌해요.
- 저장하려는 폴더에 화면보다 최근 저장본이 있으면 덮어쓸지 먼저 물어봐요.
- Gemini API 키는 파일에 저장되지 않고 각자 브라우저에만 남아요.
- 무료 GitHub 계정의 Pages는 공개 저장소에서만 쓸 수 있어요. 내부 시안이면 회사 조직 플랜과 공개 범위를 먼저 확인하세요.
