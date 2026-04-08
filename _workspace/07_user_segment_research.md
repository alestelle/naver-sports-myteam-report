# 유저 리서치: 스포츠 앱 유저 세그먼트, 저니, 이탈, 니즈

> 작성일: 2026-04-08
> 목적: CPM 피드백 대응 -- 네이버 스포츠 마이팀 보고서에 유저 관점 보강을 위한 데이터 리서치
> 조사 범위: 글로벌 스포츠 팬 세그먼트, 앱 퍼널/리텐션 벤치마크, 한국 KBO 팬 행동, 이탈 패턴, 유저 니즈 서베이

---

## 1. 스포츠 팬 유저 세그먼트 프레임워크

### 1.1 표준 3-Tier 세그먼트 모델

스포츠 산업에서 가장 널리 사용되는 팬 세그먼트는 행동/감정 몰입도 기준 3단계 분류다.

| 세그먼트 | 정의 | 비중(추정) | 핵심 행동 패턴 |
|---------|------|-----------|--------------|
| **Avid (하드코어)** | 팀 정체성이 자아의 일부. 모든 콘텐츠를 소비하고, 커뮤니티 활동 주도 | 15-20% | 매일 앱 접속, 경기 전/중/후 모두 활성, 유료 구독 전환율 높음 |
| **Casual (캐주얼)** | 진정한 관심이 있으나 일상의 일부까지는 아님. 승/패가 기분에 영향 | 40-50% | 주 2-3회 접속, 경기일 중심, 하이라이트/결과 위주 소비 |
| **Light (라이트)** | 빅이벤트나 포스트시즌에만 관심. 사회적 맥락에서 소비 | 30-40% | 월 1-2회 접속, 포스트시즌/올스타 집중, 알림에 반응 낮음 |

**출처:** [CortexTech Fan Segmentation Guide](https://www.cortextech.io/news/fan-segmentation), [FanLab Fan Factors](https://fanlab.us/fan-factors/), [N3XT Sports](https://www.n3xtsports.com/the-importance-of-fan-segmentation/)

### 1.2 세그먼트별 지출/전환 차이

팬 유형별 지출 성향에는 극적인 차이가 존재한다:

| 항목 | Avid(하드코어) | Casual(캐주얼) | 배율 |
|-----|-------------|--------------|-----|
| 티켓 구매 의향 | 50% | 23% | 2.2x |
| 굿즈 구매 의향 | 50% | 17% | 2.9x |
| TV/스트리밍 구독 의향 | 20% | 4% | 5.0x |

**출처:** [WSC Sports - High-Value Fan Segments](https://wsc-sports.com/blog/industry-insights/how-to-identify-and-activate-high-value-fan-segments/)

**시사점 (네이버 마이팀):** 마이팀 등록 유저는 최소 Casual 이상의 팬으로 분류 가능. 이 유저풀에서 Avid로 전환시키는 것이 핵심 과제이며, Avid 팬의 구독 전환율이 5배 높다는 점은 세그먼트별 차별화된 가치 제안이 필요함을 의미한다.

### 1.3 세대별 팬 소비 차이 (WSC Sports 2025-2026 팬 연구)

WSC Sports가 2025년 10월 미국 스포츠 팬 1,050명(Gen X/Y/Z 각 350명)을 대상으로 수행한 연구 결과:

| 지표 | Gen Z (18-28) | Millennial (29-44) | Gen X (45-60) |
|-----|-------------|-------------------|-------------|
| 매일 스포츠 시청 | - | 약 50% | - |
| 하드코어/레귤러 팬 자인 | - | 85% | - |
| 새 스포츠/팀/선수 팔로우(1년내) | 76% | - | - |
| 주 시청 플랫폼: 스트리밍 | 55% | 65% | - |
| 숏폼(2분 이하) 선호 | Gen X 대비 71% 높음 | - | 기준 |
| 약한 개인화로 인한 구독 해지 경험 | 50%+ (전 세대 평균) | 50%+ | 50%+ |

**핵심 발견:** Gen Z는 팀이 아닌 선수 중심으로 충성도를 형성하며, 숏폼 콘텐츠와 SNS를 통해 팬덤에 진입한다. 반면 밀레니얼은 가장 가치 있는(구독 전환/구매 의향 최고) 동시에 가장 까다로운(개인화 기대치 높음) 세그먼트다.

**출처:** [WSC Sports 2025-2026 Generational Fan Study](https://wsc-sports.com/blog/industry-insights/the-2025-2026-generational-fan-study/), [GlobeNewsWire - WSC Sports Report](https://www.globenewswire.com/news-release/2025/12/03/3198920/0/en/Half-of-Sports-Fans-Across-Generations-Canceled-Streaming-Services-Due-to-Weak-Personalization-WSC-Sports-Report-Finds.html)

---

## 2. 스포츠 앱 유저 저니 & 퍼널

### 2.1 전형적 유저 퍼널과 전환율 벤치마크

```
[발견] → [설치] → [등록/온보딩] → [활성화(Aha moment)] → [리텐션] → [추천]
```

| 퍼널 단계 | 벤치마크 전환율 | 주요 지표 | 비고 |
|----------|--------------|---------|-----|
| 앱스토어 노출 → 설치 | iOS 25%, Android 27.3% | CVR (Conversion Rate) | AppTweak 2024 H1 데이터 |
| 설치 → Day 1 리텐션 | 25-30% (전체 앱 평균) | D1 Retention | 70-75%가 첫날 이탈 |
| Day 1 → Day 7 리텐션 | 10-15% | D7 Retention | 온보딩 품질이 결정적 |
| Day 7 → Day 30 리텐션 | 6-10% (평균), 25-40% (상위) | D30 Retention | 상위 앱은 4-6배 차이 |
| 온보딩 체크리스트 완료율 | 19.2% (SaaS 평균) | Completion Rate | 80% 이상이 온보딩 미완료 |
| B2C 활성화율 | 30-50% | Activation Rate | 가치 인지 성공률 |

**출처:** [UXCam App Conversion Benchmarks](https://uxcam.com/blog/mobile-app-conversion-rate/), [Enable3 Retention Benchmarks 2026](https://enable3.io/blog/app-retention-benchmarks-2025), [Chameleon Onboarding Metrics](https://www.chameleon.io/blog/user-onboarding-metrics)

### 2.2 스포츠 앱 특수 리텐션 패턴

스포츠 앱은 일반 앱과 다른 독특한 리텐션 패턴을 보인다:

| 지표 | 스포츠 앱 | 전체 앱 평균 | 차이 |
|-----|---------|-----------|-----|
| 90일 리텐션 | 27% | 48% | -21%p (시즌성 영향) |
| 연간 리텐션 | 39% | 35% | +4%p (시즌 복귀 효과) |
| 인터랙션율 | 44% | 26% | +18%p (높은 몰입도) |

**해석:** 스포츠 앱은 단기 리텐션은 낮지만(비시즌 이탈), 연간 리텐션은 오히려 높다. 이는 시즌이 돌아오면 유저가 복귀하는 패턴을 의미하며, "이탈"과 "휴면"을 구분해야 한다는 점을 시사한다.

**출처:** [Alchemer 2021 Media App Engagement Benchmarks](https://www.alchemer.com/resources/blog/2021-engagement-benchmarks-for-media-apps/)

### 2.3 주요 이탈 포인트와 원인

| 이탈 포인트 | 이탈률 | 핵심 원인 |
|-----------|-------|---------|
| 설치 직후 (Week 0→1) | ~75% | 가치 인지 실패, 온보딩 복잡, 첫 경험 부족 |
| 퍼널 상단 (Top of funnel) | ~79% | 관심 부족, 필요성 인지 실패 |
| 시즌 종료 후 | 시즌 중 대비 급증 | 콘텐츠 부재, 관심 대상 비활성 |
| 알림 과다 시점 | 주 2-5회 알림 → 46% 옵트아웃 | 알림 피로, 비개인화 콘텐츠 |

**출처:** [Userpilot Drop-off Analysis](https://userpilot.com/blog/drop-off-analysis/), [Retenshun Push Notification Sweet Spot](https://retenshun.com/blog/push-notification-frequency-sweet-spot)

**시사점 (네이버 마이팀):** 마이팀 등록은 온보딩의 핵심 "Aha Moment"가 될 수 있다. 3분 이내 활성화된 유저의 리텐션이 2배 높다는 데이터를 고려하면, 마이팀 등록을 첫 세션 내 완료시키는 것이 중요하다.

---

## 3. 한국 스포츠 앱 사용 패턴

### 3.1 KBO 리그 흥행 현황 (2025)

2025 KBO 리그는 역대 최다 관중 기록을 경신하며 폭발적 성장을 보였다:

| 지표 | 2024 | 2025 | 증감 |
|-----|------|------|-----|
| 정규시즌 누적 관중 | 1,088만 7,705명 | 1,231만 2,519명 | +13.1% |
| 경기당 평균 관중 | 약 15,100명 | 17,100명 | +13.2% |
| 매진 경기 비율 | - | 46% (331/720경기) | - |
| 좌석 점유율 | - | 82.9% | - |
| TV 평균 합산 시청률(8월까지) | 1.07% | 1.17% | +9.3% |

**출처:** [글로벌이코노믹 - 1200만 관중 돌파](https://www.g-enews.com/article/General-News/2025/10/202510051232481137c5fa75ef86_1), [KBO 보도자료](https://www.koreabaseball.com/MediaNews/Notice/View.aspx?bdSe=11665)

### 3.2 야구 앱 이용 현황 (순 이용자 수 기준)

| 순위 | 앱/서비스 | 순 이용자 수 | 특징 |
|-----|---------|-----------|-----|
| 1 | 티빙 (TVING) | 750만명 | KBO 독점 중계권 보유, 6개월간 꾸준한 증가 |
| 2 | 네이버 스포츠 | - | 뉴스/기록/커뮤니티 중심 |
| 3 | KBO STATS | 26만명 | 공식 기록/통계/승부예측 |
| 4 | KBO 공식앱 | 22만명 | 일정/기록/투표/굿즈 |

**출처:** [반론보도닷컴 - 야구 팬들 앱 사용 현황](https://www.banronbodo.com/news/articleView.html?idxno=22997)

### 3.3 팬 유입 경로와 디지털 행동

- **최초 관람자 유입 경로:** 과반 이상이 유튜브를 통해 야구 콘텐츠에 처음 접촉
- **세대별 차이:** 20대 이하는 SNS(인스타/틱톡), 30대는 유튜브 접촉률이 상대적으로 높음
- **10대 팬 증가:** 10대 예매자 비율이 2023년 3% 이하 → 2024년 4.4% → 2025년 4.5%로 꾸준히 증가 (SNS/숏폼 영향)

**출처:** [KBO 보도자료](https://www.koreabaseball.com/MediaNews/Notice/View.aspx?bdSe=11665)

### 3.4 네이버 스포츠 마이팀 기능 현황

네이버 스포츠 마이팀 기능에 대한 유저 피드백 종합:

**긍정적 측면:**
- 설정이 간단하고 한 번 등록하면 편리하게 이용 가능
- 시즌 중 경기 예고, 경기 결과, 구단 알림 등 실시간 정보 제공
- KBO, K리그, NBA 등 복수 리그 지원

**개선 필요 사항:**
- 알림 설정이 복잡 (네이버 앱 설정 > 스포츠 알림 > 푸시 알림 > 구단 알림 > MY팀 알림 등 다단계)
- 일부 기기에서 알림 미수신 문제
- 네이버 앱 내 부가 기능으로 위치하여 독립 앱 대비 접근성 제한

**출처:** [Threads 사용자 설정 가이드](https://www.threads.com/@han_heim/post/DHssuL8z2ld/), [Samsung Community 팁](https://r1.community.samsung.com/t5/%EA%B0%A4%EB%9F%AD%EC%8B%9C-s/%ED%8C%81-oneui7-%EB%84%A4%EC%9D%B4%EB%B2%84-%EC%8A%A4%ED%8F%AC%EC%B8%A0-%EC%95%8C%EB%A6%BC-%EB%B0%9B%EC%95%84%EB%B3%B4%EC%84%B8%EC%9A%94/td-p/32272702)

---

## 4. 구독 해지/이탈 패턴

### 4.1 스포츠 스트리밍 이탈 핵심 데이터

| 지표 | 수치 | 출처 |
|-----|------|-----|
| 시즌 종료 후 구독 해지 의향 | **51%** -- 특정 시즌 동안만 구독하고 해지 | CivicScience 2025 |
| 약한 개인화로 인한 서비스 해지 경험 | **50%+** (전 세대 공통) | WSC Sports 2025 |
| 스포츠 OTT 특수 이탈율 (Q2 2025) | **6.6%** (월간) | StreamTV Insider |
| 유료 스포츠 스트리밍 가입자 증감 (YoY) | **-1%** (Q2 2025) | StreamTV Insider |

**출처:** [CivicScience - Sports Streaming Subscriptions](https://civicscience.com/sports-streaming-subscriptions/), [WSC Sports Report](https://www.globenewswire.com/news-release/2025/12/03/3198920/0/en/), [StreamTV Insider](https://www.streamtvinsider.com/content/us-subscription-streaming-growth-slows-10-q2)

### 4.2 시즌성에 따른 이탈 패턴

```
[시즌 시작] ──────── [시즌 중반] ──────── [시즌 종료/포스트시즌] ──── [비시즌]
   높은 가입        최고 인게이지먼트       이탈 시작 급증           최대 이탈
   
활성 유저 ████████████████████████████████████████████░░░░░░░░░░░░
인게이지먼트 ███████████████████████████████████████████████░░░░░░░░░
이탈률       ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░████████████████
```

**핵심 수치:**
- 스포츠 앱 90일 리텐션: 27% (전체 앱 평균 48% 대비 현저히 낮음)
- 스포츠 앱 연간 리텐션: 39% (전체 앱 평균 35% 대비 높음)
- 이 차이(90일 낮고 연간 높음)가 시즌성 이탈 → 시즌 복귀 패턴을 정량적으로 증명

**DAZN 사례 -- 이탈 방지 전략:**
- 해지 프로세스에 "일시정지(Pause)" 기능 도입
- 도입 이후 재구독 수 **140% 증가**
- 월간 구독료를 $19.99로 올리고 연간 구독은 $99.99 (월 대비 58% 할인)로 연간 전환 유도

**출처:** [Digiday - OTT Seasonal Churn](https://digiday.com/media/how-subscription-ott-services-manage-seasonal-churn/), [Cleeng - OTT Seasonal Churn in Sports](https://blog.cleeng.com/ott-seasonal-churn-in-sports)

### 4.3 알림 피로(Notification Fatigue) 정량 데이터

| 알림 빈도 | 유저 반응 | 수치 |
|----------|---------|-----|
| 주 2-5회 | 옵트아웃(알림 끄기) | **46%** |
| 주 6-10회 | 옵트아웃 | **32%** |
| 일 3회 이상 | 오픈율 5% 이하, 옵트아웃률 주당 5-8% | 급속 피로 |

**단, 스포츠 앱은 예외적으로 높은 알림 수용도:**
- 스포츠/레크리에이션 앱: iOS 옵트인율 업종 2위 (유틸리티 다음)
- 90일간 iOS 스포츠 앱 유저의 **33%가 매일 이상** 푸시 알림 수신
- 스포츠 앱의 이상적 알림 빈도: Daily 또는 Daily+ (Android에서는 Weekly도 유효)

**핵심 인사이트:** 관련성 높은 개인화된 알림 주 5회 > 관련성 낮은 일반 알림 주 2회. 알림 피로의 결정 요인은 빈도가 아닌 관련성(relevance)이다.

**출처:** [Retenshun - Push Notification Sweet Spot](https://retenshun.com/blog/push-notification-frequency-sweet-spot), [Airship - Sports App Push Notification Impact](https://www.airship.com/resources/benchmark-report/how-push-notifications-impact-sports-recreation-app-retention-rates/), [Pushwoosh Push Notification Benchmarks 2025](https://www.pushwoosh.com/blog/push-notification-benchmarks/)

### 4.4 무료 서비스의 이탈 특수성

네이버 스포츠 마이팀은 무료 서비스이므로, 유료 구독과는 다른 이탈 역학이 적용된다:

| 요소 | 유료 구독 | 무료 서비스 (마이팀) |
|-----|---------|-------------------|
| 이탈 비용 | 해지 절차 필요 | 단순 미사용으로 이탈 |
| 이탈 인지 | 해지 시점에 명확 | 점진적 비활성화로 불명확 |
| 복귀 장벽 | 재결제 필요 | 매우 낮음 (앱 재방문만으로 복귀) |
| 시즌성 영향 | 해지→재가입 비용 존재 | 비시즌 자연 이탈, 시즌 시작 시 자연 복귀 |
| 핵심 리텐션 레버 | 가격 대비 가치 | 콘텐츠 품질, 알림 적시성, 습관 형성 |

**일반 구독 서비스 이탈 통계:**
- 비자발적 이탈(involuntary churn): App Store 전체 이탈의 **23%** 이상 (결제 실패 등)
- 자발적 이탈 주요 원인: 가치 미스매치, 가격, UX 문제, 시즌성
- 일반적 월간 이탈 패턴: 11월이 가장 건강하고, 7월에 해지가 집중

**출처:** [Focus Digital - Subscription Churn](https://focus-digital.co/average-churn-rate-subscription-services/), [Churnkey Seasonality Patterns](https://churnkey.co/blog/seasonality-patterns-in-business/), [Purchasely - Subscription Churn](https://www.purchasely.com/blog/subscription-churn)

---

## 5. 유저가 진짜 원하는 것

### 5.1 스포츠 팬이 앱에서 원하는 기능 TOP 리스트

**IBM 글로벌 스포츠 서베이 (2025년 6월, 20,864명, 12개국)**

| 순위 | 원하는 기능/개선사항 | 비율 |
|-----|-------------------|-----|
| 1 | 더 빠른 리캡/하이라이트 | **67%** |
| 2 | 개인화 기능 | **65%** |
| 3 | 선수/팀에 대한 더 많은 접근 | **65%** |
| 4 | AI 기반 인사이트/해설 | **56%** |
| 5 | 실시간 게임/매치 업데이트 (AI 향상) | **35%** |
| 6 | 개인화된 콘텐츠 (AI 향상) | **30%** |

**출처:** [IBM Newsroom - Sports Fan Survey 2025](https://newsroom.ibm.com/2025-08-18-ibm-study-sports-fans-demand-more-dynamic-digital-content,-powered-by-ai)

### 5.2 라이브 이벤트 중 앱 사용 목적

**Deloitte & PwC 디지털 팬 인게이지먼트 조사:**

| 앱 사용 목적 | 비율 |
|------------|-----|
| 실시간 코멘터리/해설 | **44%** |
| 통계/분석 확인 | **41%** |
| 인스타디움 경험 향상 | **35%** |
| 모바일 리플레이 시청 | **77%** (원하는 팬 비율) |
| 다양한 앵글 시청 | **68%** |
| 선수 시점 시청 | **59%** |
| AR 선수 스탯 오버레이 | **35%** |

**출처:** [Deloitte - Fans Want More Tech](https://www.deloitte.com/us/en/insights/industry/technology/fans-want-more-tech-features-during-in-stadium-experience.html), [PwC Digital Fan Engagement](https://www.pwc.com/us/en/industries/tmt/library/digital-fan-engagement-sports.html)

### 5.3 "팀 팔로우 기능"에서 유저가 가장 가치를 느끼는 요소

팀 팔로우/마이팀 기능의 유저 가치를 구성하는 핵심 요소:

| 가치 요소 | 설명 | 효과 |
|----------|-----|-----|
| **개인화된 피드** | 관심 팀/선수 기반 콘텐츠 큐레이션 | 세션 시간 증가, 이탈률 감소 |
| **맞춤 알림** | 경기 시작/종료, 득점, 주요 이벤트 | 앱 재방문률 3x 증가 (알림 수신 유저 vs 미수신) |
| **시간 절약** | 불필요한 정보 필터링, 원하는 정보 즉시 접근 | 검색 시간 감소, 만족도 상승 |
| **커뮤니티 소속감** | 같은 팀 팬과의 교류, 예측/투표 참여 | 비시즌에도 활성 유지 |
| **습관 형성** | 경기일 기준 루틴화된 앱 사용 | 장기 리텐션의 핵심 드라이버 |

**실제 사례 -- Cleveland Cavaliers 앱:**
- 팬이 선호 선수/플레이 유형 선택 → 개인화된 하이라이트 피드 제공
- 결과: 세션당 **20분 이상** 체류, 출시 후 앱 다운로드 급증

**출처:** [PwC Digital Fan Engagement](https://www.pwc.com/us/en/industries/tmt/library/digital-fan-engagement-sports.html), [Gaming-Fans Sports Personalisation](https://gaming-fans.com/2026/03/digital-services-and-personalization-of-the-sports-experience/), [WSC Sports - Personalized Journeys](https://wsc-sports.com/blog/industry-insights/one-fan-many-stories-scaling-personalized-journeys-without-scaling-your-team/)

### 5.4 AI에 대한 팬 수용도

| 지표 | 수치 |
|-----|------|
| AI 통합에 가치를 느끼는 팬 | **85%** |
| AI 생성 스포츠 콘텐츠 신뢰 | **63%** |
| AI 기반 인사이트/해설 원하는 팬 | **56%** |

**출처:** [IBM Sports Fan Survey 2025](https://newsroom.ibm.com/2025-08-18-ibm-study-sports-fans-demand-more-dynamic-digital-content,-powered-by-ai)

### 5.5 세그먼트 교차: 커뮤니티 인게이지먼트의 부상

- 커뮤니티 인게이지먼트를 최우선 콘텐츠로 꼽는 팬 비율: 2024년 9% → 2025년 **11%**
- 멀티디바이스 사용률: 2024년 27% → 2025년 **29%**
- 18-29세 팬의 최우선 콘텐츠: "게임/인터랙티브 콘텐츠" 비율 타 세대 대비 높음

**출처:** [Choicely - Digital Fan Engagement Insights](https://www.choicely.com/blog/digital-fan-engagement-sports-media-consumption)

---

## 6. 네이버 마이팀에 대한 전략적 시사점 종합

### 6.1 유저 세그먼트 적용

```
네이버 스포츠 전체 유저
├── 비등록 유저 (Light 팬): 검색/뉴스로 유입, 마이팀 미등록
│   → 전환 과제: 마이팀 등록 유도 (첫 세션 내 Aha Moment)
├── 마이팀 등록 유저 (Casual 팬): 경기일 중심 사용
│   → 전환 과제: 일상적 사용 습관 형성, Avid로 전환
└── 마이팀 활성 유저 (Avid 팬): 매일 접속, 커뮤니티 활동
    → 유지 과제: 비시즌 콘텐츠, 개인화 심화, 커뮤니티 강화
```

### 6.2 핵심 데이터 기반 권고사항

| 영역 | 데이터 근거 | 권고 |
|-----|-----------|-----|
| 온보딩 | 3분 내 활성화 시 리텐션 2x | 마이팀 등록을 첫 세션 핵심 액션으로 설계 |
| 알림 | 개인화 알림의 옵트아웃률 << 일반 알림 | MY팀 기반 맞춤 알림 품질 강화 |
| 비시즌 | 90일 리텐션 27% vs 연간 39% | 비시즌 콘텐츠(이적/FA/훈련) 및 커뮤니티 기능 |
| 개인화 | 50%+가 약한 개인화로 구독 해지 | 선수 단위 팔로우, 숏폼 하이라이트 큐레이션 |
| Gen Z | 76%가 1년 내 새 팀/선수 팔로우 | 선수 중심 팔로우, 숏폼 콘텐츠 연동 |
| 커뮤니티 | 인게이지먼트 우선순위 상승 (9%→11%) | 팬 간 교류 기능(예측, 투표, 커뮤니티) 강화 |

### 6.3 KBO 시장 기회

- 2025년 1,231만 관중 (역대 최다, YoY +13.1%) -- 팬 베이스 확대 중
- 10대 팬 유입 증가 (3% → 4.5%) -- SNS/숏폼 경유 신규 팬
- 티빙 독점 중계(750만 이용자)와 네이버 스포츠의 보완적 포지셔닝 기회
- KBO AI 챗봇 도입 등 디지털 혁신 가속화

---

## 부록: 주요 출처 목록

### 글로벌 리서치
1. [WSC Sports - 2025-2026 Generational Fan Study](https://wsc-sports.com/blog/industry-insights/the-2025-2026-generational-fan-study/)
2. [IBM - Sports Fan Survey 2025 (20,864명, 12개국)](https://newsroom.ibm.com/2025-08-18-ibm-study-sports-fans-demand-more-dynamic-digital-content,-powered-by-ai)
3. [PwC - Digital Fan Engagement in Sports](https://www.pwc.com/us/en/industries/tmt/library/digital-fan-engagement-sports.html)
4. [Deloitte - Fans Want More Tech](https://www.deloitte.com/us/en/insights/industry/technology/fans-want-more-tech-features-during-in-stadium-experience.html)
5. [WSC Sports - High-Value Fan Segments](https://wsc-sports.com/blog/industry-insights/how-to-identify-and-activate-high-value-fan-segments/)
6. [N3XT Sports - Fan Segmentation](https://www.n3xtsports.com/the-importance-of-fan-segmentation/)
7. [CortexTech - Fan Segmentation Guide](https://www.cortextech.io/news/fan-segmentation)
8. [FanLab - Fan Factors](https://fanlab.us/fan-factors/)

### 앱 벤치마크/퍼널
9. [Enable3 - App Retention Benchmarks 2026](https://enable3.io/blog/app-retention-benchmarks-2025)
10. [UXCam - Mobile App Conversion Rate Benchmarks](https://uxcam.com/blog/mobile-app-conversion-rate/)
11. [Chameleon - User Onboarding Metrics](https://www.chameleon.io/blog/user-onboarding-metrics)
12. [Plotline - Activation Rates by Industry](https://www.plotline.so/blog/activation-rates-mobile-apps-by-industry)
13. [Alchemer - Media App Engagement Benchmarks](https://www.alchemer.com/resources/blog/2021-engagement-benchmarks-for-media-apps/)

### 이탈/알림
14. [Cleeng - OTT Seasonal Churn in Sports](https://blog.cleeng.com/ott-seasonal-churn-in-sports)
15. [Digiday - OTT Seasonal Churn Management](https://digiday.com/media/how-subscription-ott-services-manage-seasonal-churn/)
16. [Retenshun - Push Notification Sweet Spot](https://retenshun.com/blog/push-notification-frequency-sweet-spot)
17. [Airship - Sports App Push Notification Impact](https://www.airship.com/resources/benchmark-report/how-push-notifications-impact-sports-recreation-app-retention-rates/)
18. [Pushwoosh - Push Notification Benchmarks 2025](https://www.pushwoosh.com/blog/push-notification-benchmarks/)
19. [CivicScience - Sports Streaming Subscriptions](https://civicscience.com/sports-streaming-subscriptions/)
20. [Marketing Brew - Sports Streaming Retention](https://www.marketingbrew.com/stories/2025/12/15/sports-programming-streaming-retention-report)

### 한국/KBO
21. [글로벌이코노믹 - KBO 1200만 관중](https://www.g-enews.com/article/General-News/2025/10/202510051232481137c5fa75ef86_1)
22. [KBO 보도자료 - 역대 최다 관중](https://www.koreabaseball.com/MediaNews/Notice/View.aspx?bdSe=11665)
23. [반론보도닷컴 - 야구 팬 앱 사용 현황](https://www.banronbodo.com/news/articleView.html?idxno=22997)
24. [한국일보 - KBO AI 챗봇 도입](https://www.koreadaily.com/article/20260326224813733)

### 팬 인게이지먼트 전략
25. [Choicely - Digital Fan Engagement Insights](https://www.choicely.com/blog/digital-fan-engagement-sports-media-consumption)
26. [Gaming-Fans - Sports Personalisation](https://gaming-fans.com/2026/03/digital-services-and-personalization-of-the-sports-experience/)
27. [SportFirst - Digital Fan Engagement Strategy](https://www.sportsfirst.net/post/digital-fan-engagement-strategy-growth-engineering-sports-teams)
28. [Infobip - Fan Engagement Guide 2025](https://www.infobip.com/blog/fan-engagement)
