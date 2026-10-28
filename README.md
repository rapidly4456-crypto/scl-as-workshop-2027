# AS Strategy Workshop 2027 — 모바일 안내 사이트

정적 사이트(HTML/JS)라서 GitHub Pages에 그대로 올리면 됩니다.

## 파일
- `index.html` — 화면과 동작 (홈 · 일정 · 분임조 · 좌석 · 참석자)
- `data.js` — 일정, 분임조, 참석인원, 좌석 좌표 등 **내용은 전부 여기**에 있습니다. 내용이 바뀌면 이 파일만 수정하세요.
- `assets/` — PPT에서 가져온 이미지

## GitHub Pages 배포
1. GitHub에서 새 저장소 생성 (예: `scl-as-workshop-2027`)
2. 이 `site` 폴더 안의 파일들을 저장소 루트에 업로드 (Add file → Upload files)
3. Settings → Pages → Source: `Deploy from a branch`, Branch: `main` / `(root)` → Save
4. 1~2분 후 `https://<계정>.github.io/scl-as-workshop-2027/` 로 접속

> 저장소가 Public이면 참석자 이름이 누구에게나 공개됩니다.
