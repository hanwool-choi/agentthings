# Google/Alphabet/DeepMind 및 Meta 리더 공개 발언 (2026-10-02 ~ 2026-11-02)

> **조사 방법과 한계 (먼저 읽을 것)**
> - 이 세션에서는 WebFetch가 모든 외부 호스트(fool.com, finance.yahoo.com, blog.google, q4cdn.com 등)에서 DNS 차단되어 원문을 열 수 없었다. 아래 내용은 전부 **WebSearch(확장 모드) 결과의 요약과 발췌**를 근거로 했다. 따라서 "직접 인용"은 검색 결과에 나온 문장이며, 공식 트랜스크립트 원문과 한 단어씩 대조하지는 못했다. 최종 보고서에 쓰기 전에 1차 출처(아래 URL)와 대조해야 한다.
> - 1차 출처 URL(검증용):
>   - Alphabet Q3 2026 트랜스크립트 PDF: https://s206.q4cdn.com/479360582/files/doc_events/2026/Oct/28/2026_Q3_Earnings_Transcript.pdf
>   - Pichai Q3 발언 블로그: https://blog.google/company-news/inside-google/message-ceo/alphabet-earnings-q3-2026/
>   - Meta Q3 2026 트랜스크립트 PDF: https://s21.q4cdn.com/399680738/files/content_files/META-Q3-2026-Earnings-Call-Transcript.pdf
>   - Gemini 4 Carbon 발표 블로그: https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-carbon/
> - 조사한 범위: Alphabet·Meta Q3 실적 발표(핵심), Gemini 4 Carbon 발표, Hassabis, Alexandr Wang/MSL, LeCun(AMI Labs), Thomas Kurian, Josh Woodward, Susan Li. **Koray Kavukcuoglu, Jeff Dean, Nat Friedman, Chris Cox의 이 기간 발언은 확인하지 못했다**(검색 예산 문제로 미검색이거나 결과 없음. 아래 Gaps 참고).

---

## 1. 아이템 카탈로그 (날짜순)

### [A] Yann LeCun – Fortune 인터뷰 (2026-10-01, **기간 경계 하루 전: 맥락용**)
- **화자/역할:** Yann LeCun, AMI Labs(Advanced Machine Intelligence Labs) 창업자/Executive Chairman (전 Meta 수석 AI 과학자)
- **형식/매체:** 인터뷰 기사, Fortune
- **URL:** https://fortune.com/2026/10/01/ai-godfather-yann-lecun-has-zero-concerns-about-human-extinction-says-anthropic-ceo-dario-amodei-is-deuded/
- **요약:** LeCun은 AMI에 직원이 약 60명 있고, 자신이 고안한 JEPA 아키텍처로 "월드 모델"을 만들고 있다고 설명했다. JEPA는 픽셀이나 단어를 생성하지 않고 네트워크 내부의 표현 공간에서 데이터를 예측한다. 그는 인류 멸종 위험에 대해 "zero concerns(전혀 우려하지 않는다)"고 했고, Anthropic CEO Dario Amodei를 "deluded(망상에 빠졌다)"고 비판했다.
- **핵심 포인트:**
  - LLM 스케일링으로는 인간 수준 지능에 도달하지 못한다는 기존 입장을 유지했다.
  - JEPA 기반 월드 모델에 베팅하고 있다.
  - AI 존재론적 위험론을 정면으로 반박했다.
- **인용 (기사 헤드라인/요약 기준):** "zero concerns" about human extinction → 인류 멸종에 대해 "전혀 우려하지 않는다"
- **함의:** 업계의 "superintelligence" 담론에 맞서는 대표적인 반대 목소리다. Meta가 같은 시기에 "스케일링을 통한 초지능"을 내세운 것과 대조된다(아래 [F]).

### [A-2] Yann LeCun – La Tribune Événements 등 (약 2026-10 초, 정확한 날짜 미확인)
- **URL:** 검색 요약에서만 확인했고 원문 URL은 확보하지 못했다. 관련 요약: https://www.startuphub.ai/ai-news/ai-research/2026/yann-lecun-says-flying-trimarans-will-beat-llms
- **요약:** LeCun은 출범 6개월이 지났지만 AMI에 아직 출시할 제품이 없다고 말했다. 연구 인력은 50~60명이고 파리, 뉴욕, 몬트리올, 싱가포르에 분산되어 있다. 그는 LLM을 "단동선(monohull)"에, JEPA 월드 모델을 "날아오르는 삼동선(flying trimaran)"에 비유했다. 또 먼저 논문을 공개(publish first)하겠다고 했다.
- 관련 X 클립(날짜 미확인): "The AI world is totally LLM-pilled. Everyone's building the same machine. Same hole, different shovels." → "AI 업계는 완전히 LLM에 중독됐다. 모두가 같은 기계를 만든다. 같은 구멍을 다른 삽으로 파는 셈이다." 그는 이런 쏠림의 원인으로 연구소들이 서로 엔지니어를 빼가기 때문에 다른 접근법에 베팅할 여유가 없다는 점을 들었다. — https://x.com/AiEvolutio58513/status/2100275237787201992 (2차 계정이며 날짜 검증 불가)
- **함의:** 날짜를 확정할 수 없으므로 "10월 초로 추정"이라고 표기해야 한다.

### [B] Alexandr Wang – Founders Podcast (2026-10-11) / Zuckerberg·Wang – Cheeky Pint (2026-10-12)
- **화자:** Alexandr Wang (Meta Chief AI Officer, Meta Superintelligence Labs 리더), Mark Zuckerberg
- **형식:** 팟캐스트
- **URL:** Cheeky Pint 요약 https://cheekypint.substack.com/p/muse-wonder-zuckerberg-and-wangs ; 관련 요약 https://www.thepodcastsummary.com/episodes/S6l3aRsecuE/ ("Creating Muse: The Fastest-Growing AI Product Since ChatGPT")
- **요약 (검색 요약 기준, 원문 미확인):** Wang은 Meta가 엔터프라이즈 코딩 도구보다 **소비자 에이전트**에 집중하는 이유를 설명했다(Founders Podcast, 10/11). 10/12 Cheeky Pint 에피소드는 Zuckerberg와 Wang이 출연해 Muse Wonder를 다뤘다.
- **함의:** Meta는 2026년 7월 Muse 코딩 제품으로 코딩 시장에 진입했다(맥락: https://www.cnbc.com/2026/07/09/meta-jumps-into-ai-coding-market-to-chase-anthropic-and-openai.html). 그런데 10월에는 다시 소비자 에이전트를 중심에 두는 메시지로 바뀐 것으로 보인다. 단, 팟캐스트 원문은 확인하지 못했다.

### [C] Meta – Muse Spark Open 오픈 웨이트 공개 (2026-10-15)
- **URL:** https://en.wikipedia.org/wiki/Meta_Superintelligence_Labs (2차 출처). 1차 Meta 발표는 확보하지 못했다.
- **내용:** 816B 총 파라미터, 42B 활성 파라미터의 MoE 모델이다. 실적 발표 요약에 따르면 이 분기에 Muse Spark 1.2/1.3, Muse Code, 오픈 웨이트 모델 2종(Muse Glimmer, Muse Spark Open), Muse Voice를 출시했다. — https://www.alphaspread.com/security/nasdaq/meta/earnings-calls/q3-2026
- **함의:** Meta는 최상위 프런티어 모델(Muse Wonder)은 닫아 두고, 하위·중간 모델만 "오픈 웨이트"로 공개하는 **이원화 전략**을 쓰는 것으로 보인다. Llama 시절의 "전면 오픈소스" 기조와 비교하면 후퇴한 것이다(추론).

### [D] Muse Wonder 출시 (2026-10 중순, 정확한 날짜 미확인)
- **URL:** https://chatgptiseatingtheworld.com/2026/10/17/alexandr-wang-gave-meta-its-mojo-back-with-launch-of-muse-muse-wonder/ (블로그, 10/17)
- **내용:** Zuckerberg는 실적 보도자료에서 이를 "our first frontier model(우리의 첫 프런티어 모델)"이라고 불렀다. 블로그에 따르면 일부 벤치마크에서 Anthropic, OpenAI, Google의 최상위 모델과 맞먹는다고 Meta가 주장했다. **벤치마크 주장은 1차 출처로 검증하지 못했다.**

### [E] Meta Q3 2026 실적 발표 (2026-10-21) — 핵심 아이템
- **화자:** Mark Zuckerberg (CEO), Susan Li (CFO)
- **형식:** 실적 컨퍼런스콜
- **URL:** 트랜스크립트 PDF https://s21.q4cdn.com/399680738/files/content_files/META-Q3-2026-Earnings-Call-Transcript.pdf ; CNBC 라이브 https://www.cnbc.com/2026/10/21/meta-earnings-q3-2026-live-updates.html ; Benzinga https://www.benzinga.com/markets/earnings/26/10/62517271/mark-zuckerberg-superintelligence-scaling-meta-bigger-models ; https://www.benzinga.com/markets/tech/26/10/62518027/zuckerberg-meta-personal-superintelligencem ; Investing.com https://www.investing.com/news/transcripts/earnings-call-transcript-meta-beats-q3-2026-estimates-as-ai-push-lifts-shares-93CH-4964260 ; Alpha Spread https://www.alphaspread.com/security/nasdaq/meta/earnings-calls/q3-2026 ; Winzheng https://www.winzheng.com/en/article/meta-q3-2026-capex-exceeds-operating-cash-flow
- **요약:**
  Zuckerberg는 이번 분기를 "모두를 위한 개인 초지능(personal superintelligence)"으로 가는 진전으로 규정했다. 그 중심에는 Muse 개인 에이전트(9/8 공개 출시)와 첫 프런티어 모델 Muse Wonder가 있다. 그는 개인 초지능을 회사의 "North Star(북극성)"라고 불렀고, Reality Labs의 작업도 이제 개인 초지능을 최우선으로 한다고 했다. 장기적인 경로는 Muse와 개인 에이전트라고 설명했다. 기술 경로로는 "스케일링을 통해 초지능을 만들 것"이라며 "사다리를 체계적으로 올라가고 있다"고 말했다. 또 오늘날 수준의 지능을 1년 안에 더 작은 모델로 "몇 분의 1 비용"에 제공할 수 있을 것으로 본다고 했다.
  사용 지표도 공개했다. 미국·캐나다에서 지난 한 달 반 동안 1,000만 명 이상이 Muse 개인 에이전트를 설정했고, 그중 약 25%가 매일 사용한다. 최대 사용 사례는 쇼핑이며 평균 구매액은 200달러를 넘는다.
  Susan Li는 Muse의 비용 구조를 구체적으로 밝히지 않았다. 다만 "꽤 컴퓨팅 비용이 크다"고 했고, 그래서 아직 전 세계에 출시하지 않았다고 설명했다. 그는 내년에 비용 효율을 10배 이상 개선할 것으로 예상했다. 수익화는 대부분 사용자에게 무료로 두고, ① 기업이 내는 커머스 수수료, ② 고급 모델이나 추가 토큰 사용에 대한 유료 구독, ③ 비즈니스·업무용 구독으로 할 계획이다. 2027년 지출은 계획 수립이 아직 초기이고 유동적이라며 Q4 콜에서 정량 가이던스를 주겠다고 했다. 다만 공격적인 투자가 2027년에도 계속될 것이라고 언급했다.
- **공개된 숫자:**
  - 매출 646억 달러(전년 대비 +26%)
  - 보고 EPS 3.83달러. 99억 달러(9.89B) 소송 합의 비용(2026년 8월 주 법무장관 합의)을 제외하면 조정 EPS 7.40달러. 컨센서스 수치는 출처마다 3.57달러와 5.75달러로 엇갈린다.
  - Q3 총비용 516억 달러(+68%). 2026년 총비용 가이던스는 1,750억~1,790억 달러.
  - Q3 capex 349억 달러(+80%). 영업현금흐름 328억 달러를 초과했다. FCF는 -21억 달러(전년 +106억 달러).
  - 2026년 capex 가이던스는 1,350억~1,450억 달러로, 기존 1,300억~1,450억 달러에서 하단을 올렸다.
  - 영업이익률은 약 20%(소송 비용 제외 시 약 35%).
  - 직원 수는 약 66,000명으로 2분기 대비 12% 줄었다(2026년 5월 감원 반영).
  - 컴퓨팅: "향후 몇 년간 10억 명 이상에게 서비스할 용량을 구축 중"이다.
  - 비용 증가 요인으로 법률 비용, 인프라 비용, **외부 AI 토큰 비용(third-party AI token costs)**이 꼽혔다. 이 내용은 품질이 낮은 3차 트랜스크립트 요약에서 나왔으므로 검증이 필요하다.
  - 의결권 없는 신규 Class C 주식 발표 — https://www.stocktitan.net/articles/meta-q3-2026-earnings-results
- **직접 인용 (검색 결과 발췌, 원문 대조 필요):**
  - "build superintelligence through scaling" → "스케일링을 통해 초지능을 구축한다" (Zuckerberg)
  - "methodically working our way up the ladder" → "사다리를 체계적으로 한 단계씩 올라가고 있다" (Zuckerberg)
  - "launching Muse and Muse Wonder, our first frontier model" → "Muse와 우리의 첫 프런티어 모델인 Muse Wonder를 출시했다" (Zuckerberg, 보도자료)
  - (10M+ users) "have set up Muse personal agents" → "(1,000만 명 이상이) Muse 개인 에이전트를 설정했다" (Zuckerberg)
  - "On the compute side, we are building out the capacity to serve more than 1 billion people over the next few years." → "컴퓨팅 측면에서 우리는 향후 몇 년 안에 10억 명 이상에게 서비스할 수 있는 용량을 구축하고 있다." (Li)
  - "we do not have sort of specific numbers to share around the cost structure of Muse today, but of course it is, as Mark said, pretty compute expensive." → "현재 Muse의 비용 구조에 대해 공유할 구체적인 수치는 없지만, Mark가 말했듯 당연히 꽤 컴퓨팅 비용이 크다." (Li)
  - "we expect to improve its cost efficiency by more than 10x in the next year" → "내년에 비용 효율을 10배 이상 개선할 것으로 예상한다" (Li)
  - "We ended Q3 with over 66,000 employees, down 12% from Q2 following the May 2026 headcount reduction." → "2026년 5월 인력 감축 이후 3분기 말 직원 수는 66,000명 이상으로, 2분기 대비 12% 감소했다." (Li)
- **함의:**
  - capex가 영업현금흐름을 넘어서 FCF가 마이너스로 돌아섰다. AI 투자가 "현금흐름으로 감당하는 단계"를 넘어섰다는 신호다.
  - 컴퓨팅 비용이 소비자 출시 범위를 직접 제약하고 있다(미국·캐나다 한정).
  - 인력이 줄어드는 가운데 capex는 늘고 있다. "사람에서 컴퓨팅으로" 자원을 재배분하는 흐름이다.
- **주의:** 첫 검색 결과에 나온 SEC 8-K 링크(meta-03312026xexhibit991)는 **Q1 자료**이므로 Q3 근거로 쓰면 안 된다.

### [F] "Superintelligence" 용어 논란 보도 (CNBC, 2026-10-30)
- **URL:** https://www.cnbc.com/2026/10/30/trump-tech-allies-swap-ai-for-super-intelligence-in-earnings-calls.html ; https://tech.slashdot.org/story/26/10/31/0615204/which-tech-companies-started-using-trumps-phrase-super-intelligence
- **요약:** CNBC는 Trump 대통령이 행정부 부처에서 "artificial intelligence"를 "super intelligence"로 바꾸라고 지시한 지 한 달 만에 Musk와 Zuckerberg가 실적 콜에서 이 용어를 따라 썼다고 보도했다. 반면 다른 매체들은 Zuckerberg가 이미 2025-07-30 "Personal Superintelligence for Everyone" 글에서 같은 용어를 썼다고 지적했다. 즉 이번 용어 사용을 정치적 동조로 볼 근거는 약하다.
- **함의:** 해석이 갈린다. 보고서에서는 양쪽 주장을 모두 제시해야 한다.

### [G] Alphabet Q3 2026 실적 발표 (2026-10-28) — 핵심 아이템
- **화자:** Sundar Pichai (CEO), Anat Ashkenazi (CFO), Philipp Schindler (CBO). Thomas Kurian의 결과 관련 코멘트는 diginomica가 보도했다.
- **형식:** 실적 컨퍼런스콜 + CEO 블로그 발언문
- **URL:** 트랜스크립트 PDF https://s206.q4cdn.com/479360582/files/doc_events/2026/Oct/28/2026_Q3_Earnings_Transcript.pdf ; CEO 발언 https://blog.google/company-news/inside-google/message-ceo/alphabet-earnings-q3-2026/ ; Benzinga https://www.benzinga.com/news/26/10/62679903/alphabet-q3-2026-earnings-call-transcript ; Investing.com https://www.investing.com/news/transcripts/earnings-call-transcript-alphabet-q3-2026-profit-miss-sparks-10-afterhours-drop-93CH-4981037 ; BigGo https://finance.biggo.com/news/US_GOOG_2026-10-28 ; FourWeekMBA https://fourweekmba.com/ai-google-cloud-revenue-doubles-to-30-7b-as-capex-hits-51-4b/ ; datastudios https://www.datastudios.org/post/alphabet-q3-2026-results-google-cloud-doubles-30-7-billion-capex-51-billion ; ppc.land https://ppc.land/gemini-app-gains-350m-users-in-a-year-to-pass-1bn-alphabet-says/ ; diginomica https://diginomica.com/google-cloud-soars-tpu-focus-comes-fore-ceo-thomas-kurian-sets-out-stall
- **요약:**
  Alphabet은 매출 1,276억 달러(+25%), 영업이익 406억 달러(+30%)를 발표했다. 성장은 AI가 이끈 검색과 Google Cloud(+103%)가 주도했다. Cloud 매출은 307억 달러로 사상 최대였고, AI 인프라와 함께 **TPU 시스템 판매**가 의미 있게 기여했다. Cloud 영업이익률은 23.7%에서 36.2%로 올랐다.
  Pichai는 Gemini 앱 월간 사용자가 10억 명을 넘었다고 밝혔다(1년 전 약 6.5억 명). 그는 Gemini 앱을 "Google 역사상 가장 빠르게 성장한 제품"이라고 불렀다. 1st-party 모델 API는 분당 약 320억 토큰을 처리하며, 이는 전 분기 대비 40%, 전년 대비 4배 이상 많은 수준이다.
  공급 제약 때문에 3분기 말부터 **외부(third-party) 컴퓨팅 용량을 쓰기 시작했고** 4분기에 사용량을 늘리고 있다. 경영진은 이 때문에 단기적으로 마진 역풍이 있을 것이라고 경고했다.
  capex는 Q3에 514억 달러였다. 2026년 가이던스 1,950억~2,050억 달러는 유지했고, 2027년에는 "상당히(significantly) 증가"할 것이라며 상세 내용은 Q4 콜에서 밝히겠다고 했다. Q3 FCF는 -91억 달러였다. 원인은 capex, TPU 재고 투자, EU 집행위원회 벌금 52억 달러 납부다.
  같은 날 Gemini 4 Carbon을 발표했고(아래 [H]), Pichai는 콜에서 Carbon의 **증류(distilled) 버전**을 개발 중이라고 언급했다.
- **공개된 숫자:**
  - 매출 1,276억 달러(+25%), 영업이익 406억 달러(+30%)
  - Google Cloud 매출 307억 달러(+103%), 영업이익률 36.2%(전년 23.7%)
  - Q3 capex 514억 달러. 2026년 capex 1,950억~2,050억 달러 유지. 2027년은 "상당히 증가".
  - FCF -91억 달러
  - Gemini 앱 MAU 10억 명 이상(1년 전 약 6.5억 명). 1년간 약 3.5억 명 증가(ppc.land 헤드라인).
  - 1st-party API 처리량: 분당 약 320억 토큰(전 분기 대비 +40%, 전년 대비 4배 이상)
  - (맥락, I/O 2026년 5월) 전체 서비스 기준 월 3.2경(quadrillion) 토큰 이상. **이번 기간의 수치가 아니다.**
  - 백로그: 총 백로그의 55%를 조금 넘는 금액을 24개월 안에 매출로 인식할 것으로 예상한다. FourWeekMBA는 7월의 5,140억 달러보다 470억 달러 늘었다고 계산했지만 이는 사이트 자체 계산이며 **1차 출처로 미확인**이다.
  - Kurian: 자사 클라우드에서 시작한 의미 있는 TPU 고객이 100곳 이상이다(diginomica).
- **직접 인용 (검색 결과 발췌, 원문 대조 필요):**
  - "first-party model APIs are now processing nearly 32 billion tokens per minute — 40% more than last quarter and more than four times what we processed a year ago" → "1st-party 모델 API는 현재 분당 약 320억 토큰을 처리하고 있다. 이는 지난 분기보다 40% 많고, 1년 전 처리량의 4배가 넘는다." (Pichai)
  - "The Gemini app is now at one billion users and is the fastest-growing product in Google's history." → "Gemini 앱은 이제 사용자 10억 명에 도달했으며, Google 역사상 가장 빠르게 성장한 제품이다." (Pichai)
  - "We're also seeing strong demand for our TPU systems across a wide range of customers" → "광범위한 고객들 사이에서 TPU 시스템에 대한 강한 수요도 보고 있다." (Pichai, FourWeekMBA 인용 – 2차)
  - "working hard to bring more capacity online to meet this long-term demand" → "이 장기 수요를 맞추기 위해 더 많은 용량을 가동하려고 열심히 노력하고 있다." (Pichai, 2차)
  - "In Google Cloud, we expect TPU system sales to continue to scale in Q4 ... once we sign that agreement, you'll first see that showing up in our backlog." → "Google Cloud에서 TPU 시스템 판매가 4분기에도 계속 확대될 것으로 예상한다. … 계약을 체결하면 그 금액은 먼저 백로그에 나타난다." (트랜스크립트 PDF 발췌로 문장이 단편적이다)
- **함의:**
  - TPU가 내부 자산에서 **외부 판매 사업**으로 바뀌었다. 클라우드 매출이 2배로 늘어난 주요 동인이다.
  - 자체 TPU를 보유하고도 외부 컴퓨팅을 빌릴 만큼 수요가 공급을 앞선다. 2026년 4월(Q1) 콜의 "compute constrained" 발언과 같은 흐름이 이어지고 있다.
  - FCF가 마이너스로 돌아서고 2027년 capex가 "상당히 증가"할 예정이다. Meta와 함께 하이퍼스케일러 투자가 현금흐름을 넘어서는 국면에 들어섰다.
- **상충:** Investing.com은 "이익 미스로 시간외 10% 하락"(조정 EPS 2.12달러 vs 예상 3.02달러)이라고 보도했다. 그러나 다른 출처는 강한 실적으로 다뤘다. 주가 반응과 EPS 비교는 검증이 필요하다.

### [H] Gemini 4 Carbon 발표 (2026-10-28)
- **화자:** Google/Google DeepMind. Demis Hassabis(X 게시물). Pichai(실적 콜에서 증류 버전 언급).
- **형식:** 공식 블로그, X 게시물
- **URL:** https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-carbon/ ; Hassabis X https://x.com/demishassabis/status/2115489550256746502 ; Forbes(10/30) https://www.forbes.com/sites/janakirammsv/2026/10/30/google-limits-gemini-4-carbon-to-vetted-cyber-defenders/ ; The Elec https://www.thelec.net/news/articleView.html?idxno=15128 ; BigGo https://finance.biggo.com/news/d80ab5e2-0f44-436e-93d7-ddfd9619cbe5 ; Platformer https://www.platformer.news/thursday-newsletter-6/
- **요약:** Google은 Gemini 4 Carbon을 자사 최강 모델로 소개하며 소프트웨어 엔지니어링과 사이버보안에 초점을 맞췄다. Artificial Analysis Intelligence Index에서 59점으로 Claude Opus 5.5를 넘어 1위에 올랐다. Google 발표에 따르면 WebDev Arena에서 Elo +89, 1768점으로 4위다. BigGo에 따르면 SEC-bench Pro 취약점 탐지에서 88.2%를 기록했다. 접근은 매우 제한적이다. 발표 주부터 일부 사이버 방어 인력(cyber defenders)에게만 제공하고, 이후 Fairwind Program을 통해 신뢰할 수 있는 파트너에게 점진적으로 넓힌다. 개발자, 기업, 일반 소비자 대상 출시일은 없다. 모델 카드도 아직 없다. 계획된 API 도입 가격은 Argon과 같은 입력 100만 토큰당 2달러, 출력 10달러다.
  - 맥락: Gemini 4 Argon은 2026-09-30 발표되어 **기간 밖**이고, 10-13에 유료 사용자에게 공개되었다(기간 내).
- **인용:** "Iterating at lightning speed! Gemini 4 Carbon is SOTA across key benchmarks and combines frontier capabilities with deep safety & security research." → "번개 같은 속도로 반복하고 있다! Gemini 4 Carbon은 주요 벤치마크에서 최고 수준(SOTA)이며, 프런티어 역량과 깊이 있는 안전·보안 연구를 결합했다." (Hassabis, X, 2026-10-28)
- **함의:** 사이버 공격·방어 역량이 강한 프런티어 모델을 "검증된 방어자에게 먼저" 내놓는 단계적 출시가 등장했다. 일반 공개보다 위험 관리를 앞세운 출시 방식이다. Platformer는 이를 신모델 출시가 계속 지연되던 흐름에서 반등할 가능성으로 해석했다. 평가는 엇갈려서, 일부는 "Argon을 약간 개선한 버전"이라고 본다.

### [I] Thomas Kurian – 실적 관련 코멘트 (diginomica, 2026-10-30 전후)
- **URL:** https://diginomica.com/google-cloud-soars-tpu-focus-comes-fore-ceo-thomas-kurian-sets-out-stall
- **내용:** Kurian은 TPU 시스템 수요가 광범위한 고객에 걸쳐 강하고, Google이 규모를 키우는 동안 이 흐름이 계속될 것으로 예상한다고 했다. Google Cloud에서 시작한 의미 있는 TPU 고객이 100곳 이상이다. 독립 인터뷰는 확인하지 못했다.
- 맥락(기간 밖): 2026년 4월 Stratechery 인터뷰에서 Kurian은 "질문에 답하는 단계에서 워크플로 자동화로" 넘어가는 에이전트 전략을 제시했다. 또 경쟁 AI 연구소와 금융사를 포함한 외부에 TPU 판매를 늘리고 있다고 밝혔다. — https://stratechery.com/2026/an-interview-with-google-cloud-ceo-thomas-kurian-about-the-agentic-moment/

---

## 2. 핵심 질문별 정리

## Gemini/Llama(Muse) 로드맵, 초지능 연구소, 에이전트, 월드 모델, 검색·광고, capex·컴퓨팅, TPU, 오픈 vs 클로즈드, 일자리에 대해 무엇을 말했나

### Takeaway
Google은 Gemini 4 세대(Argon → Carbon → 증류 버전)와 TPU 외부 판매를 앞세워 "컴퓨팅 공급 부족 속 고성장"을 강조했다. Meta는 Llama 브랜드 대신 MSL의 Muse 계열을 내세워 "스케일링을 통한 개인 초지능"과 소비자 에이전트를 북극성으로 삼았다. LeCun은 그 반대편에서 LLM 스케일링 회의론과 JEPA 월드 모델을 고수했다.

### Cited Findings
- **Gemini 로드맵:** Gemini 4 Argon은 9/30 발표(기간 밖), 10/13 유료 사용자 공개. Gemini 4 Carbon은 10/28 발표되었고 사이버 방어자 한정으로 제공하며 일반 출시일은 없다 — [Google Blog](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-carbon/), [Forbes](https://www.forbes.com/sites/janakirammsv/2026/10/30/google-limits-gemini-4-carbon-to-vetted-cyber-defenders/)
- Pichai는 Carbon의 증류 버전을 개발 중이라고 밝혔다 — [검색 요약; Google Blog/실적 콜](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-carbon/)
- Carbon은 AA Intelligence Index 59점으로 1위, SEC-bench Pro 88.2%를 기록했다 — [The Elec](https://www.thelec.net/news/articleView.html?idxno=15128), [BigGo](https://finance.biggo.com/news/d80ab5e2-0f44-436e-93d7-ddfd9619cbe5)
- **Meta 로드맵:** Muse Wonder는 "첫 프런티어 모델"이다. 이번 분기 Muse Spark 1.2/1.3, Muse Code, Muse Voice, 오픈 웨이트 2종(Muse Glimmer, Muse Spark Open)을 출시했다 — [Alpha Spread](https://www.alphaspread.com/security/nasdaq/meta/earnings-calls/q3-2026), [Benzinga](https://www.benzinga.com/markets/earnings/26/10/62517271/mark-zuckerberg-superintelligence-scaling-meta-bigger-models)
- Muse Spark Open(10/15)은 816B 총/42B 활성 파라미터 MoE이며 오픈 웨이트다 — [Wikipedia: MSL](https://en.wikipedia.org/wiki/Meta_Superintelligence_Labs)
- **초지능:** Zuckerberg는 "build superintelligence through scaling"이라고 말했고, 개인 초지능을 "North Star"로 규정했다 — [Benzinga](https://www.benzinga.com/markets/earnings/26/10/62517271/mark-zuckerberg-superintelligence-scaling-meta-bigger-models), [Benzinga 2](https://www.benzinga.com/markets/tech/26/10/62518027/zuckerberg-meta-personal-superintelligencem)
- **에이전트:** Muse 개인 에이전트는 미국·캐나다에서 1,000만 명 이상이 설정했고 일간 사용률은 약 25%다. 최대 사용 사례는 쇼핑이며 평균 구매액은 200달러 이상이다 — [Benzinga/트랜스크립트 요약](https://www.benzinga.com/markets/tech/26/10/62518027/zuckerberg-meta-personal-superintelligencem)
- Wang은 엔터프라이즈 코딩보다 소비자 에이전트에 집중한다고 설명했다(Founders Podcast, 10/11). 원문은 미확인 — [Wikipedia: Alexandr Wang](https://en.wikipedia.org/wiki/Alexandr_Wang)
- **월드 모델:** LeCun은 AMI(약 60명)가 JEPA 월드 모델을 만들고 있으며 아직 출시할 제품은 없다고 했다 — [Fortune, 10/01](https://fortune.com/2026/10/01/ai-godfather-yann-lecun-has-zero-concerns-about-human-extinction-says-anthropic-ceo-dario-amodei-is-deuded/), [StartupHub](https://www.startuphub.ai/ai-news/ai-research/2026/yann-lecun-says-flying-trimarans-will-beat-llms)
- **검색·광고:** Alphabet의 성장은 "AI가 이끈 검색"과 Cloud가 주도했다. 세부 검색 지표(AI Mode/AI Overviews 사용자)는 이번 검색에서 확인하지 못했다 — [Investing.com](https://www.investing.com/news/transcripts/earnings-call-transcript-alphabet-q3-2026-profit-miss-sparks-10-afterhours-drop-93CH-4981037)
- Meta 매출 +26%는 광고 수요 강세와 가격 상승 덕분이다. Muse는 대부분 무료로 두고 커머스 수수료와 구독으로 수익화할 계획이다 — [CNBC](https://www.cnbc.com/2026/10/21/meta-earnings-q3-2026-live-updates.html), [Alpha Spread](https://www.alphaspread.com/security/nasdaq/meta/earnings-calls/q3-2026)
- **TPU:** Cloud 성장에서 TPU 시스템 판매의 기여가 의미 있었고, 4분기에도 계속 확대될 것으로 예상한다. TPU 고객은 100곳 이상이다 — [Alphabet 트랜스크립트 PDF](https://s206.q4cdn.com/479360582/files/doc_events/2026/Oct/28/2026_Q3_Earnings_Transcript.pdf), [diginomica](https://diginomica.com/google-cloud-soars-tpu-focus-comes-fore-ceo-thomas-kurian-sets-out-stall)
- **외부 컴퓨팅:** Alphabet은 공급 제약 때문에 3분기 말부터 외부 컴퓨팅을 쓰기 시작했다 — [BigGo](https://finance.biggo.com/news/US_GOOG_2026-10-28). Meta는 비용 증가 요인으로 외부 AI 토큰 비용과 외부 클라우드를 꼽았다(저품질 출처로 검증 필요) — [Investing.com](https://www.investing.com/news/transcripts/earnings-call-transcript-meta-beats-q3-2026-estimates-as-ai-push-lifts-shares-93CH-4964260)
- **일자리:** Meta 직원은 66,000명 이상으로 2분기 대비 12% 줄었다(5월 감원) — [Yahoo/트랜스크립트 요약](https://finance.yahoo.com/markets/stocks/articles/meta-platforms-inc-meta-q3-230130937.html)
- **AI 위험:** LeCun은 멸종 위험에 대해 "zero concerns"라고 했고 Amodei를 "deluded"라고 비판했다 — [Fortune](https://fortune.com/2026/10/01/ai-godfather-yann-lecun-has-zero-concerns-about-human-extinction-says-anthropic-ceo-dario-amodei-is-deuded/)

### Inferences
- Meta는 최상위 모델을 닫아 두고 그 아래 계층만 오픈 웨이트로 푸는 "계층형 개방"으로 이동했다. "Llama"라는 이름이 이번 기간 발언에서 보이지 않는 것도 그 신호다.
- 두 회사 모두 "모델 성능"보다 **서비스 비용(컴퓨팅)**을 병목으로 지목했다. Google은 외부 컴퓨팅을 빌리고, Meta는 Muse 지역 출시를 제한하면서 비용 효율 10배 개선을 목표로 삼았다.
- Google은 Carbon 출시에서 "역량보다 안전 관리"를 앞세웠다. 사이버 역량이 출시 정책을 좌우하는 변수가 되었음을 보여 준다.

### Gaps
- Hassabis, Koray Kavukcuoglu, Jeff Dean, Josh Woodward의 이 기간 인터뷰나 팟캐스트를 찾지 못했다(Hassabis는 X 게시물만 확인). DeepMind의 월드 모델(Genie 등) 관련 새 발언도 미확인이다.
- Nat Friedman, Chris Cox의 이 기간 공개 발언은 미검색이거나 결과가 없다.
- Alphabet 콜에서 Schindler가 말한 AI Mode/AI Overviews 사용자 수, 검색 매출 성장률, YouTube, 유료 구독 수치는 이번 검색에서 확보하지 못했다.
- Meta AI(구 앱) MAU, Hyperion/Prometheus 데이터센터 진척, Reality Labs 수치, 안경 관련 발언은 미확인이다.
- Muse Wonder의 정확한 출시일과 벤치마크는 1차 출처로 미확인이다.

## 공개된 구체적 숫자 (capex, 토큰, 사용자, 클라우드 매출)

### Takeaway
Alphabet은 2026년 capex 1,950억~2,050억 달러(2027년 "상당히 증가"), Cloud 307억 달러(+103%), Gemini 앱 10억 MAU 이상, API 분당 약 320억 토큰을 공개했다. Meta는 2026년 capex 1,350억~1,450억 달러(하단 상향), Q3 capex 349억 달러로 영업현금흐름 초과, Muse 에이전트 1,000만 명 이상을 공개했다. 두 회사 모두 Q3 FCF가 마이너스였다.

### Cited Findings
- Alphabet: 매출 1,276억 달러(+25%), 영업이익 406억 달러, Cloud 307억 달러(+103%), Cloud 영업이익률 36.2% — [Investing.com](https://www.investing.com/news/transcripts/earnings-call-transcript-alphabet-q3-2026-profit-miss-sparks-10-afterhours-drop-93CH-4981037), [BigGo](https://finance.biggo.com/news/US_GOOG_2026-10-28)
- Alphabet capex: Q3 514억 달러, 2026년 1,950억~2,050억 달러 유지, 2027년 상당히 증가 — [datastudios](https://www.datastudios.org/post/alphabet-q3-2026-results-google-cloud-doubles-30-7-billion-capex-51-billion), [Benzinga](https://www.benzinga.com/news/26/10/62679903/alphabet-q3-2026-earnings-call-transcript)
- Alphabet FCF -91억 달러(EU 벌금 52억 달러 포함) — [BigGo](https://finance.biggo.com/news/US_GOOG_2026-10-28)
- Gemini 앱 MAU 10억 명 이상(1년 전 약 6.5억 명), API 분당 약 320억 토큰 — [ppc.land](https://ppc.land/gemini-app-gains-350m-users-in-a-year-to-pass-1bn-alphabet-says/), [Google Blog CEO 발언](https://blog.google/company-news/inside-google/message-ceo/alphabet-earnings-q3-2026/)
- 백로그 중 55%를 조금 넘는 금액을 24개월 안에 인식할 예정. 총액(7월 5,140억 달러 + 470억 달러)은 FourWeekMBA 계산이며 미검증 — [FourWeekMBA](https://fourweekmba.com/ai-google-cloud-revenue-doubles-to-30-7b-as-capex-hits-51-4b/)
- Meta: 매출 646억 달러(+26%), Q3 capex 349억 달러(+80%), 영업현금흐름 328억 달러, FCF -21억 달러 — [Winzheng](https://www.winzheng.com/en/article/meta-q3-2026-capex-exceeds-operating-cash-flow), [CNBC](https://www.cnbc.com/2026/10/21/meta-earnings-q3-2026-live-updates.html)
- Meta 2026년 capex 1,350억~1,450억 달러(기존 1,300억~1,450억 달러), 총비용 1,750억~1,790억 달러, 소송 비용 99억 달러 — [Benzinga](https://www.benzinga.com/markets/earnings/26/10/62517271/mark-zuckerberg-superintelligence-scaling-meta-bigger-models), [Alpha Spread](https://www.alphaspread.com/security/nasdaq/meta/earnings-calls/q3-2026)
- Muse 에이전트 1,000만 명 이상 설정, 일간 사용률 약 25%, Muse 비용 효율 10배 이상 개선 목표 — [Benzinga](https://www.benzinga.com/markets/tech/26/10/62518027/zuckerberg-meta-personal-superintelligencem), [Yahoo 요약](https://finance.yahoo.com/markets/stocks/articles/meta-platforms-inc-meta-q3-230130937.html)
- 두 회사 합산 2026년 capex 가이던스 중간값은 약 3,400억 달러다(1,950억 달러 + 1,400억 달러, 필자 계산).

### Inferences
- Alphabet의 Cloud 영업이익률이 크게 오른 것은 TPU 하드웨어 판매가 고마진 매출원이 되고 있음을 시사한다(추정).
- Meta의 2027년 정량 가이던스는 Q4 콜(2027년 1월 말 예상)에서 나온다. Alphabet도 같다. 다음 업데이트 시점이 겹친다.

### Gaps
- Alphabet 실적의 일부 수치(EPS 미스 여부, 시간외 -10%)는 출처 간에 상충한다. Investing.com의 EPS 2.12달러 vs 3.02달러 비교는 다른 출처와 맞지 않는다.
- Meta의 EPS 컨센서스(3.57달러 vs 5.75달러)도 출처마다 다르다.

## 이전 입장 대비 변화

### Takeaway
(1) Meta는 Llama 오픈소스 중심에서 MSL·Muse 프런티어 모델(클로즈드)과 오픈 웨이트 하위 모델로 이원화했고, 메시지도 "스케일링 초지능"과 소비자 에이전트로 옮겼다. (2) Google은 "compute constrained"(4월) 상태에서 외부 컴퓨팅 임대(10월)로 한 단계 더 나아갔고, TPU 외부 판매를 본격 사업화했다. (3) 두 회사 모두 FCF가 마이너스로 돌아섰다. (4) 프런티어 모델 출시가 사이버보안을 명분으로 한 제한적 출시로 바뀌었다.

### Cited Findings
- 2026년 4월(Q1) Pichai는 "we are compute constrained in the near term… our cloud revenue would have been higher if you were able to meet the demand"(단기적으로 컴퓨팅 제약 상태이며, 수요를 충족할 수 있었다면 클라우드 매출이 더 높았을 것)라고 했다(맥락) — [Fool Q1 트랜스크립트](https://www.fool.com/earnings/call-transcripts/2026/04/29/alphabet-googl-q1-2026-earnings-call-transcript/). 10월(Q3)에는 외부 컴퓨팅 사용을 시작했다 — [BigGo](https://finance.biggo.com/news/US_GOOG_2026-10-28)
- Q2 콜에서 경영진은 TPU 시스템 매출이 주로 2027년에 늘어날 것이라고 했는데, Q3에는 이미 Cloud 성장에 의미 있게 기여했다. 예상보다 빨라진 것으로 보인다 — [FourWeekMBA](https://fourweekmba.com/ai-google-cloud-revenue-doubles-to-30-7b-as-capex-hits-51-4b/)
- Meta의 "personal superintelligence" 표현은 2025-07-30 글부터 있었으므로 새 표현이 아니다. 다만 CNBC는 Trump 행정명령 이후의 용어 동조로 해석했다 — [CNBC](https://www.cnbc.com/2026/10/30/trump-tech-allies-swap-ai-for-super-intelligence-in-earnings-calls.html)
- Meta는 2026년 7월 코딩 시장에 진입했다가 10월에는 소비자 에이전트 중심 메시지를 냈다(Wang) — [CNBC 7월](https://www.cnbc.com/2026/07/09/meta-jumps-into-ai-coding-market-to-chase-anthropic-and-openai.html), [Wikipedia: Alexandr Wang](https://en.wikipedia.org/wiki/Alexandr_Wang)
- Meta의 2026년 capex 하단은 1,300억 달러에서 1,350억 달러로 올라갔다 — [Benzinga](https://www.benzinga.com/markets/earnings/26/10/62517271/mark-zuckerberg-superintelligence-scaling-meta-bigger-models)
- LeCun은 2026년 1월 MIT Tech Review 인터뷰 이후 입장이 일관되며 변화가 없다 — [MIT Technology Review](https://www.technologyreview.com/2026/01/22/1131661/yann-lecuns-new-venture-ami-labs/)

### Inferences
- LeCun이 떠난 뒤 Meta가 "스케일링으로 초지능"을 공식 노선으로 내세운 것은 LeCun의 회의론과 정반대 방향으로 선명하게 결별했음을 보여 준다.
- Google은 "AI가 검색을 잠식한다"는 우려에 맞서, 검색과 Cloud를 함께 성장시키는 이야기로 전환하는 데 성공했다. 다만 검색 세부 지표는 미확인이다.

### Gaps
- Hassabis의 AGI 시점 전망(이전 약 2030년 50%)이 이 기간에 바뀌었는지 확인하지 못했다. 검색된 Hassabis 인터뷰는 전부 2025년~2026년 초 자료다(예: https://www.bigtechnology.com/p/google-deepmind-ceo-demis-hassabis-946, https://www.fortune.com/2026/02/11/google-ai-boss-demis-hassabis-4-step-plan-return-golden-era). 이들은 기간 밖이다.
- WebFetch가 차단되어 모든 직접 인용을 공식 트랜스크립트와 단어 단위로 대조하지 못했다. 보고서 작성 전에 대조해야 한다.
