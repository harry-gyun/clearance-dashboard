# 오프린트미 클리어런스 판매 대시보드

오프린트미 팀블링 어패럴 클리어런스 품목의 판매 현황을 실시간으로 확인할 수 있는 대시보드입니다.

## 기간
2026-02-02 ~ 2026-04-15 (KOR)

## 포함 내용
- 상품별 재고, 판매수량, 잔여재고, 소진율, 매출 테이블
- 주간 판매 추이 라인 차트 (0원 이벤트 / 비이벤트 필터)
- 주간 구성비 스택 차트
- 재고 소진 현황 바 차트
- 매출 비중 도넛 차트

## 배포 방법

### GitHub Pages
1. 이 저장소를 GitHub에 push
2. Settings → Pages → Source: `main` branch, `/ (root)` 선택
3. Save → 배포 완료 후 `https://{username}.github.io/{repo-name}` 에서 확인

### 로컬 확인
`index.html`을 브라우저에서 직접 열면 바로 확인 가능합니다.

## 기술 스택
- HTML / CSS / Vanilla JS
- Chart.js 4.4.1 (CDN)
- Pretendard 폰트 (Google Fonts)
- 다크모드 자동 지원
