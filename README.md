# 모여봐요 찰스의 숲

불멍 메타버스 게임. 브라우저에서 바로 열리는 정적 웹(HTML/JS) 으로 만들고, GitHub Pages 루트 주소에 배포한다.

- 공개 주소(예정): https://myc2102-hue.github.io/
- GitHub 저장소(만들어야 함): `myc2102-hue/myc2102-hue.github.io` — 루트 주소로 쓰려면 저장소 이름이 반드시 이것이어야 함
- 로컬 작업 폴더: `/Users/apple/Desktop/claude/찰스의숲`

## 폴더 구성
```
index.html   진입 페이지(게임 본체)
assets/      이미지·소리·폰트
_notes/      기획 메모(푸시 제외)
```

## 배포 방법 (사용자 터미널)
1. github.com 에서 빈 저장소 `myc2102-hue.github.io` 생성(README 없이).
2. 아래 한 줄 실행:
   ```bash
   cd /Users/apple/Desktop/claude/찰스의숲 && git remote add origin https://myc2102-hue@github.com/myc2102-hue/myc2102-hue.github.io.git && git push -u origin main
   ```
3. 저장소 Settings → Pages → Branch `main` / `/ (root)` 저장. 1~2분 뒤 공개.
4. 이후 수정은 `git push` 만 하면 자동 반영.
