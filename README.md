# 허진영 포트폴리오 (Vol.3)

AI 도구(Claude, Gemini, ChatGPT Codex)를 활용해 기획부터 설계, 구현, 스토어 배포까지 1인으로 진행한 프로젝트를 모은 개인 포트폴리오입니다.

- 사이트: https://herjy6372.github.io/portfolio/
- 메인: `index.html` · 소개 서브페이지: `herjy6372_v3_0_sub.html`

## 수록 프로젝트

| 프로젝트 | 유형 | 주요 기술 | 상태 / 링크 |
|---|---|---|---|
| 나의 할 일 | Flutter 앱 | Firebase Auth·Firestore, fl_chart, 5단계 RBAC | Google Play 비공개 테스트 |
| 교회찬양집 | Flutter 앱 | pdfx, CustomPainter 필기, MethodChannel, Isolate | Google Play 비공개 테스트 |
| 김천침례교회 | 웹사이트 | HTML/CSS/JS, Firebase, GitHub Pages | 개인정보 보호로 비공개 |
| 나의 레시피 | Flutter 앱 | Riverpod, Dio, Hive, TheMealDB | [코드](https://github.com/herjy6372/myrecipe) · Google Play 비공개 테스트 |
| 두근두근 카드 뒤집기 | 웹 미니게임 | Vanilla JS, Firestore 실시간 순위 | [플레이](https://herjy6372.github.io/cardflipmatch/) · [코드](https://github.com/herjy6372/cardflipmatch) |
| 한국 랜덤여행 | Flutter 앱 | CustomPainter·GeoJSON 지도, Provider, Hive, Firebase Auth·Firestore | Google Play 비공개 테스트 |

## 구조

```
index.html                  메인 (About · Skills · Portfolio · Contact, 작업과정 모달 포함)
herjy6372_v3_0_sub.html     소개 서브페이지
assets/img/                 사진·미리보기 이미지
assets/cardflipmatch.png    카드 게임 미리보기
```

빌드 과정 없는 정적 사이트이며, 로컬에서는 `python3 -m http.server`로 확인할 수 있습니다.

© 2026 Heo Jinyoung. 개인 포트폴리오용으로 제작되었습니다.
