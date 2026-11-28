# 허진영 포트폴리오 (Vol.3)

AI 도구(Claude, Gemini, ChatGPT Codex)를 활용해 기획부터 설계, 구현, 스토어 배포까지 1인으로 진행한 프로젝트를 모은 개인 포트폴리오입니다.

- 사이트: https://herjy6372.github.io/portfolio/
- 개발 블로그: https://herjy6372.github.io/blog/ (프로젝트별 문제 해결 기록, 한국어·영어)
- 메인: `index.html` · 소개 서브페이지: `herjy6372_v3_0_sub.html`

## 수록 프로젝트

| 프로젝트 | 유형 | 주요 기술 | 상태 / 링크 |
|---|---|---|---|
| 나의 할 일 | Flutter 앱 (v1.6.4) | Firebase Auth·Firestore, fl_chart, home_widget·WidgetKit 위젯, flutter_quill 메모 서식, R8 난독화 | [코드](https://github.com/herjy6372/mytodo) · Google Play 비공개 테스트 |
| 성경&찬양 | Flutter 앱 (v1.6.0) | pdfx, CustomPainter 필기, MethodChannel(Android SAF·iOS 문서 선택기), Isolate, 성경 역본 비교 보기, zip 파일 백업/복원(archive), Firestore 보안 규칙 | [코드](https://github.com/herjy6372/churchpraise-app) · [스토어 이미지](https://github.com/herjy6372/churchpraise-app/tree/main/docs/play-store) · Google Play 비공개 테스트 |
| 김천침례교회 | 웹사이트 | HTML/CSS/JS, Firebase Auth·Firestore 보안 규칙(승인 회원 전용 게시판, 에뮬레이터 테스트), GitHub Pages | 개인정보 보호로 비공개 |
| 나의 레시피 | Flutter 앱 | Riverpod, Dio, Hive, TheMealDB | [코드](https://github.com/herjy6372/myrecipe) · Google Play 비공개 테스트 |
| 두근두근 카드 뒤집기 | 웹 미니게임 | Vanilla JS, Firestore 실시간 순위 | [플레이](https://herjy6372.github.io/cardflipmatch/) · [코드](https://github.com/herjy6372/cardflipmatch) |
| 한국 랜덤여행 | Flutter 앱 | CustomPainter·GeoJSON 지도, Provider, Hive, Firebase Auth·Firestore | [코드](https://github.com/herjy6372/randomtravel) · Google Play 비공개 테스트 |

## 구조

```
index.html                  메인 (About · Skills · Portfolio · Contact, 작업과정 모달 포함)
herjy6372_v3_0_sub.html     소개 서브페이지
assets/img/                 사진·미리보기 이미지
assets/cardflipmatch.png    카드 게임 미리보기
```

## 스토어 이미지

Google Play 스토어 등록정보에 올린 이미지(앱 아이콘, 그래픽 이미지, 휴대전화·태블릿 스크린샷)는 이 사이트가 아니라 각 앱 저장소에 보관합니다.

| 프로젝트 | 위치 |
|---|---|
| 성경&찬양 | [churchpraise-app/docs/play-store](https://github.com/herjy6372/churchpraise-app/tree/main/docs/play-store) — `graphics/`(아이콘 512×512, 그래픽 1024×500), `phone/`(1080×1920 6장), `tablet/`(1920×1080 6장, v1.5.0 기준) |

이 사이트의 성경&찬양 미리보기 이미지(`assets/img/pf-praise-compare-20261122.jpg`, `assets/img/praise-*-20261115.jpg`, `assets/img/praise-compare*-20261122.jpg`)는 성경 비교 보기(휴대폰·태블릿 가로)·형광펜·색상 권 선택·여러 절 선택·2027 읽기표가 들어간 최신 화면이고, 앱 저장소의 `docs/screenshots/`와 같은 화면입니다. (스토어 이미지는 v1.5.0 기준) 이미지를 바꿀 때는 브라우저 캐시 때문에 예전 이미지가 보이지 않도록 파일 이름의 날짜를 바꿔 새 이름으로 올립니다.

빌드 과정 없는 정적 사이트이며, 로컬에서는 `python3 -m http.server`로 확인할 수 있습니다.

© 2026 Heo Jinyoung. 개인 포트폴리오용으로 제작되었습니다.
