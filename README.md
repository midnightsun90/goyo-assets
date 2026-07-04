# goyo-assets

고요(GOYO) 정적 자산 호스팅.

| 경로 | 용도 |
|---|---|
| `app/content.json` | 앱 원격 콘텐츠 (버전 비교 후 적용) |
| `post-NN/slide-N.jpg` | 인스타그램 캐러셀 이미지 (Graph API용) |

갱신: Buddhism 리포에서 `npm run content:publish --prefix goyo-app` 실행 → `content/publish/content.json`을 이 리포 `app/content.json`으로 복사 후 push.
