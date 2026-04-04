# KJH-Trading

AI 트레이딩 분석과 Pine Script 지표 문서를 함께 정리하는 저장소입니다.

## 문서 바로가기

- [PineScript 트레이딩 가이드](./pinescript/README.md)
- [추세 추적 가이드](./pinescript/%EC%B6%94%EC%84%B8%20%EC%B6%94%EC%A0%81/README.md)
- [비정상 가격 추적 (캔들)](./pinescript/%EB%B9%84%EC%A0%95%EC%83%81%20%EA%B0%80%EA%B2%A9%20%EC%B6%94%EC%A0%81%20(%EC%BA%94%EB%93%A4)/README.md)

## 폴더 구조

- [`pinescript`](./pinescript/README.md): 트레이딩뷰에서 사용하는 지표와 설명서 모음
- [`report`](./report/principle.md): 매매 전략 리포트와 관련 정리

## 현재 포함된 대표 지표

- [`추세 추적`](./pinescript/%EC%B6%94%EC%84%B8%20%EC%B6%94%EC%A0%81/README.md): 스윙 구조와 적응형 VWAP 기반 추세 판단
- [`비정상 가격 추적 (캔들)`](./pinescript/%EB%B9%84%EC%A0%95%EC%83%81%20%EA%B0%80%EA%B2%A9%20%EC%B6%94%EC%A0%81%20(%EC%BA%94%EB%93%A4)/README.md): 비정상 캔들, 다이버전스, ATR 배경 기반 진입 자리 판단
- [`거래량 압력 추적`](./pinescript/%EA%B1%B0%EB%9E%98%EB%9F%89%20%EC%95%95%EB%A0%A5%20%EC%B6%94%EC%A0%81/README.md): 매수/매도 거래량 압력 확인
- [`MACD 다이버전스 추적`](./pinescript/MACD/README.md): 내부 모멘텀과 다이버전스 확인
- [`비정상 가격 추적 (보조)`](./pinescript/%EB%B9%84%EC%A0%95%EC%83%81%20%EA%B0%80%EA%B2%A9%20%EC%B6%94%EC%A0%81%20(%EB%B3%B4%EC%A1%B0)/README.md): cRSI와 MFI 기반 반전 위험 필터

## 사용하는 방법

1. 먼저 [PineScript 트레이딩 가이드](./pinescript/README.md)에서 전체 흐름을 봅니다.
2. 필요하면 각 지표별 README로 들어가 설정과 해석 방법을 확인합니다.
3. 트레이딩뷰 `Pine Editor`에 `.pine` 파일을 붙여넣어 차트에 적용합니다.
4. 전략 메모와 원칙은 [`report`](./report/principle.md) 문서에서 함께 확인합니다.
