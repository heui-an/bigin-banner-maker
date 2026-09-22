# 동봉 폰트

이 도구는 배너를 캔버스에 직접 그리기 때문에, 피그마 템플릿이 쓰는 폰트가
브라우저에 로드되어 있어야 결과가 원본과 같아진다. 그래서 폰트를 함께 둔다.

| 파일 | 서체 | 라이선스 |
|---|---|---|
| `fonts/Pretendard-Regular.woff2` | Pretendard Regular | SIL Open Font License 1.1 |
| `fonts/Pretendard-SemiBold.woff2` | Pretendard SemiBold | SIL Open Font License 1.1 |
| `fonts/Pretendard-Bold.woff2` | Pretendard Bold | SIL Open Font License 1.1 |
| `fonts/GmarketSansBold.woff` | Gmarket Sans Bold | G마켓 무료 폰트 라이선스 |

- Pretendard — https://github.com/orioncactus/pretendard (OFL 1.1)
- Gmarket Sans — G마켓 브랜드 사이트에서 무료 배포. 판매·유료 재배포는 금지되며,
  포함 시 출처 표기가 필요하다. 공개 저장소에 동봉하기 전에 최신 라이선스 전문을
  확인할 것.

폰트를 저장소에서 빼려면 `fonts/`를 `.gitignore`에 추가하고, 사용자가 직접
같은 경로에 내려받도록 안내하면 된다. `index.html`의 `@font-face`는
`fonts/` 상대 경로만 참조한다.
