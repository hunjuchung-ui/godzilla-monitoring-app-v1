# 고질라 모니터링 웹앱

수동 현재가 입력형 고질라 모니터링 웹앱입니다.

## 로컬 실행

```bash
npm install
npm run dev
```

## Vercel 배포

1. 이 폴더를 GitHub 저장소에 업로드
2. Vercel에서 Import Project
3. Framework Preset: Vite
4. Build Command: `npm run build`
5. Output Directory: `dist`
6. Deploy

## 기능

- 보유종목 박스
- 아나패스 매수가 16,950원 / 70주 손익 자동 계산
- 현재가 상태 표시: 🔴 ⚫️ 🔵 🟡
- 고질라 점수순 모니터링
- 매수구간 우선 정렬
- 번외 관리 종목
