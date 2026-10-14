# sindang

오늘의 운세 웹앱. 점술가를 고르면 생년월일 기반으로 오늘의 운세를 보여줍니다.

- 단일 파일(`index.html`)로 동작하며 점술가 이미지는 base64로 내장되어 있습니다.
- `assets/hosts/`에는 원본 이미지(webp)가 들어 있습니다. 영상으로 교체하려면 같은 이름의 mp4를 넣고 `index.html`의 `<img class="photo">`를 `<video autoplay loop muted playsinline>`으로 바꾸면 됩니다.
- 결과는 생년월일 + 성별 + 시진 + 점술가 + 날짜를 시드로 하는 결정적 난수와 문장 풀에서 생성됩니다.

## 배포
GitHub Pages (main 브랜치 루트)
