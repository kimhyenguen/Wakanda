# [1팀] Week 1 · 문화권 조사 보고서

> **인공지능과 경영 · 11주차 협동학습**
> Global AI Ethics Simulator — Week 1 산출물 템플릿
> © 2026 강송희 교수 · CC BY-NC 4.0

---

## 1. 팀 · 배정 문화권

| 항목 | 내용 |
|---|---|
| 팀명 | 1팀 |
| 배정 문화권 | AFREECA
| 작성일 | 2026-11-23 |
| 작성자 | 김영환, 2023316006 |

## 2. 근거 자료 (최소 2건 · URL 필수)

| # | 자료명 | 출처 유형 | URL | 인용 요지 |
|---|---|---|---|---|
| 1 | Hofstede Insights: AFRICA  | 학술 DB | https://www.theculturefactor.com/country-comparison-tool?countries=ghana%2Ckenya%2Cnigeria | 개인주의(IDV) 동아프리카 27·서아프리카 20, 권력거리(PDI) 64~77, 불확실성 회피(UAI) 52~54, 쾌락 추구(IVR) 동아프리카 40·서아프리카 78 |
| 2 | World Values Survey Wave 7 | 국제 조사 | https://www.worldvaluessurvey.org/WVSContents.jsp| Inglehart–Welze | 아프리카 문화권은 전통적·종교적 가치(Traditional values)가 강한 영역에 위치 |
| 3 | (추가) | | | |

## 3. 프레임워크별 문화 해석

| Framework | 문화적 근거 요약 (2~3줄) | 제안 가중치 |
|---|---|---|
| **emotion**  | 쾌락 추구(IVR) 점수가 동아프리카 40, 서아프리카 78로 지역 간 편차가 커서 근거가 약함. 그래서 가장 낮게 설정. | 0.15 |
| **social**   | Ubuntu("우리가 있기에 내가 있다")처럼 공동체와 관계를 중시함. Hofstede 개인주의 점수가 동아프리카 27, 서아프리카 20으로 매우 낮아 집단 중심. 권력거리도 64~77로 높아 위계와 관계, 체면이 중요. | 0.4 |
| **moral**    | 불확실성 회피 점수가 52~54로 중간 수준. 규칙과 의무를 꽤 중시하지만 아주 엄격하지는 않아 두 번째로 설정. | 0.25 |
| **identity** | WVS 조사에서 아프리카는 전통·종교적 가치가 강한 쪽에 속함. 신념은 중요하지만 social, moral보다 선택에 덜 직접적이라고 판단. | 0.2 |
| **합계**     | | **1.00** |

> ⚠️ 합계는 반드시 1.00 이어야 합니다. `python scripts/validate_scenarios.py` 로 자동 검증됩니다.

## 4. 가설 (Value-Check 대상)

> **H1.** 우리 문화권(KOREA) 에이전트는 S1(Trolley) 시나리오에서 옵션 **B(방관)** 를 200 에피소드 부근에서 수렴 선택할 것이다.
>
> **H2.** identity 가중치가 높은 문화권일수록 다양성(diversity) 지표가 낮게 수렴할 것이다.
>
> **H3.** ε-decay 가 진행됨에 따라 초기 100 에피소드 대비 최종 100 에피소드의 entropy 는 0.3 이하로 감소할 것이다.

## 5. AI 사용 로그 (핵심 3건 이상 요약)

> 전체 로그는 `logs/ai_usage_log.md` 를 참조.

| Entry | Non-AI 초안 요약 | AI 응답 요약 | 최종 채택 사유 |
|---|---|---|---|
| #1 | | | |
| #2 | | | |
| #3 | | | |

## 6. GitHub 워크플로 증거

- Fork/Clone 명령 로그: (스크린샷 첨부)
- `dev` 브랜치 첫 커밋 SHA: `xxxxxxx`
- 첫 PR 링크: https://github.com/<org>/<repo>/pull/1

---

### 🔍 자기 점검 체크리스트

- [ ] 근거 URL 2건 이상 인용
- [ ] 가중치 합계 = 1.00
- [ ] 가설 3개 이상 (검증 가능한 문장)
- [ ] GitHub PR 생성 및 리뷰어 배정
- [ ] AI 사용 로그 3-entry 이상
