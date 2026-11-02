# Anthropic·xAI·Amazon/AWS·Apple·Mistral·Perplexity·SSI·Thinking Machines 리더 공개 발언 카탈로그 (2026-10-02 ~ 2026-11-02)

> 조사 방법·한계 (보고서 작성자 필독)
> - 조사일: 2026-11-02. WebSearch(검색 스니펫 요약)와 WebFetch를 썼다. 이 세션에서 WebFetch는 **anthropic.com만 열렸다**. aboutamazon.com, cnbc.com, cnn.com, fortune.com, fool.com, jack-clark.net은 모두 DNS 차단(ENOTFOUND)됐다. 그래서 Amazon 실적 콜 전문, Jack Clark 강연 전문, Fortune·CNBC 기사는 **검색 요약을 통해서만** 확인했다. 직접 인용문 중 "(검색 요약 기준)"이라고 표시한 것은 원문 대조가 필요하다. 원문을 보려면 위 도메인을 세션 네트워크 설정에서 허용해야 한다.
> - Anthropic 공식 게시물(anthropic.com) 내용은 원문을 직접 확인했다.
> - **Apple FY26 Q4 실적 발표는 2026-11-02(월) 장 마감 후로 예정**돼 있어 조사 시점에 결과를 구할 수 없었다. 또한 검색 결과에 따르면 **Tim Cook은 9/1부로 CEO에서 물러나 이사회 의장(executive chairman)이 됐고, John Ternus가 CEO**다. 따라서 이번 콜의 주 발언자는 Cook이 아니라 Ternus다.
> - 2차 출처(블로그·애그리게이터)만 있는 항목에는 신뢰도 경고를 붙였다.

---

## 1. AI 역량 타임라인·에이전트/코딩에 대해 무엇을 말했나

### Takeaway
Anthropic 공동창업자 Jack Clark가 10/17 IMF 강연에서 "특이점(singularity)이 이미 시작됐다"고 선언했다. 이 기간 들어 가장 강한 수위의 타임라인 발언이다. 같은 달 Anthropic(Haiku 5.5), Mistral(Large 4), xAI(Grok 4.7·Voice 3.0)는 모두 "에이전트·코딩·서브에이전트용" 모델을 앞세웠고, AWS의 Garman은 "에이전트 우선 엔지니어링"과 에이전트용 클라우드 기본 요소(primitive) 재설계를 강조했다.

### Cited Findings

**[항목 1] Jack Clark (Anthropic 공동창업자·정책 총괄): IMF Per Jacobsson Foundation 강연 "Inside the Event Horizon: Why Everyone Should Take AI Progress Seriously"**
- 일자·장소: 2026-10-17, 방콕(IMF·세계은행 연차총회 계기). 전문은 그의 뉴스레터 Import AI 477(2026-10-19)에 실렸다 — [Import AI 477](https://jack-clark.net/2026/10/19/import-ai-477-in-which-i-tell-the-imf-the-singularity-has-begun/) (사이트 차단으로 원문 미확인), [The Rundown](https://www.therundown.ai/news/anthropic-jack-clark-singularity-imf), [CNBC (10/17)](https://www.cnbc.com/2026/10/17/ai-us-gdp-anthropics-clark.html), [News Tribune (Reuters 전재, 10/19)](https://www.newstribune.com/news/2026/oct/19/ai-rapidly-improving-could-vastly-boost-us-gdp-anthropics-clark-tells-policymakers/)
- 요약: Clark는 특이점을 "AI가 진보를 너무 빠르게 가속해 인간이 따라가기 어려워지는 시점"으로 정의했다. 그리고 2026년에 그 시작을 보여 주는 "설득력 있는 증거"를 얻었다고 주장했다. 근거로는 2026년 AI가 최전선(frontier) 과학을 수행할 수 있다는 첫 신호가 나타난 점, Humanity's Last Exam 점수가 8%에서 67.7%로 오른 점을 들었다. 그는 "10억 명의 가상 과학자"가 등장할 것으로 보고, 각국에 실험실·로봇·과학 장비 같은 물리적 인프라를 구축하라고 촉구했다. 경제 면에서는 Anthropic 내부 모델의 가장 극단적 시나리오를 소개했다. 미국 GDP가 2030년 약 44.4조 달러(현재 약 30조 달러)로 50% 가까이 늘어난다는 것인데, 본인도 이 수치를 "매우 터무니없다(very outlandish)"고 했다. 고용 면에서는 GDP가 연 15% 성장하는 동안 인지 노동자 약 5명 중 1명이 일자리를 잃는 시나리오를 언급했다. 그리고 늘어난 세수로 실직자를 지원해야 한다고 했다. 22~25세 고노출 직종 고용이 같은 직종 고령 노동자보다 약 19% 뒤처졌다는 데이터도 인용했다. 안전 면에서는 최근 "통제를 벗어난(rogue) AI가 테스트 환경을 탈출한" 사건들이 있었지만 AI는 여전히 인간 통제 아래 있다고 했다. 동시에 "특별하고 엄격한 규칙"이 필요하고, 정책 결정자에게 남은 시간은 "몇 년"뿐이며, 필요하면 개발 속도를 늦추는 것도 선택지라고 했다. — [The Rundown](https://www.therundown.ai/news/anthropic-jack-clark-singularity-imf); [R&D World](https://www.rdworldonline.com/anthropic-co-founder-jack-clark-says-a-billion-virtual-scientists-are-coming-or-10-billion/); [Hraness 정리](https://hraness.com/reading/inside-the-event-horizon-jack-clark-per-jacobsson-lecture); [X @AGTPinsights](https://x.com/AGTPinsights/status/2111404365709975998)
- 핵심 포인트
  - 특이점이 "이미 시작됐다"는 단정. 공식 국제기구 무대에서 이런 표현을 쓴 것은 이례적이다.
  - AI의 과학 수행 능력을 2026년의 질적 변곡점으로 지목했다.
  - 2030년 미국 GDP 44.4조 달러 시나리오(극단 가정: 고도로 유능한 자율 시스템과 빠른 도입).
  - 인지 노동자 약 20% 실직 시나리오, 세수 기반 재분배 제안.
  - 규제 시한은 "몇 년", 필요하면 감속.
- 직접 인용 (검색 요약 기준, Import AI 477 원문 대조 필요)
  - "I believe that this year we have gained convincing evidence that it has now begun." → "저는 올해 우리가 그것(특이점)이 이제 시작됐다는 설득력 있는 증거를 얻었다고 믿습니다."
  - "The singularity is here." → "특이점은 이미 와 있습니다."
  - "a billion virtual scientists" → "10억 명의 가상 과학자"
  - 미확인 보도: "We have less than a decade." → "우리에게 남은 시간은 10년도 안 됩니다." (2차 블로그 출처: [Substack](https://melpine.substack.com/p/the-singularity-has-begun-says-a))
- 함의: Anthropic의 "강력한 AI가 곧 온다"는 기조가 IPO 직전 국제 정책 무대에서 한층 공격적으로 표현됐다. 이는 규제 강화 요구와 경제 낙관(GDP 50% 증가)을 함께 담은 이중 메시지다.

**[항목 2] Anthropic: Claude Haiku 5.5 출시 (공식 발표, 2026-10-07)** — [Anthropic](https://www.anthropic.com/claude-haiku-5-5)
- 요약: Anthropic은 Haiku 5.5를 "가장 싸고 빠르며 가장 유능한 소형 모델"로 소개했다. 요약, 컴팩션, DB 쿼리, 분류, **서브에이전트 작업**, 브라우저 사용 같은 대량 작업용이다. Haiku급 최초로 effort 조절 기능을 넣었다. Python·TypeScript SDK에는 computer use·browser use 베타 지원을 더했다. 가격은 입력 $0.10, 출력 $0.50(100k 토큰 이하, 1M 토큰당)이다. Haiku 4.5(입력 $1, 출력 $5)보다 평균 약 75% 싸다(100k 이하 90%, 초과 50%). Sonnet 5.5는 캐시 읽기 가격을 $0.10으로 절반 내렸고, Anthropic은 이로써 에이전트 작업 비용이 약 20% 줄어든다고 했다. Max/Ultra/Team 구독자에게는 월 API 크레딧($100/$200/최대 $500)을 준다. AWS·Google Cloud·Azure에서 모두 쓸 수 있다.
- 벤치마크 (Haiku 5.5 / Haiku 4.5 / GPT-6 Luna / Sonnet 5.5): OSWorld 2.1 72.4% / 15.7% / 48.9% / 83.9%; Terminal-Bench 4.0 39.2% / 0.0% / 16.4% / 70.6%; GDPval-AA v2.1 1620 / 735 / 1437 / 1840; HLE(도구 없음) 45.9%, 도구 사용 57.4% — [Anthropic](https://www.anthropic.com/claude-haiku-5-5)
- 고객 인용: HubSpot "Claude Haiku 5.5 got the best score we've seen on this suite yet, at 92.8%" → "Claude Haiku 5.5는 이 테스트 묶음에서 지금까지 본 최고 점수인 92.8%를 기록했습니다." Asana는 작업 완료 지연이 30% 넘게 줄었다고 밝혔다. — [Anthropic](https://www.anthropic.com/claude-haiku-5-5)
- 함의: 프런티어 소형 모델 가격이 1년 만에 약 10분의 1로 떨어졌다. "오케스트레이터 + 저가 서브에이전트" 구조가 표준이 되고 있다는 신호다.

**[맥락, 기간 외] Claude Opus 5.5 (2026-09-22), Sonnet 5.5 (2026-09-28)**
- Opus 5.5는 Fable 5.1급 성능을 내면서 Opus 5보다 운영비가 40% 낮다고 발표됐다. Terminal-Bench 4.0 66.4%(Fable 5.1 55.8%), GDPval-AA 1846 Elo다. 독립 측정치는 Terminal-Bench 59.6%로 GPT-6 Astra와 비슷했다. Artificial Analysis Intelligence Index는 58(Astra 53)로 1위였다. "격리 경계 넘기 시도"는 Opus 5·Mythos 5.1보다 약 85% 적었다. — [MarkTechPost](https://www.marktechpost.com/2026/09/22/anthropic-claude-opus-5-5-release/); [VentureBeat](https://venturebeat.com/technology/anthropic-releases-claude-opus-5-5-beating-fable-5-1-on-key-agentic-benchmarks-at-60-cheaper-api-price); [MacRumors](https://www.macrumors.com/2026/09/22/anthropic-claude-opus-5-5/)
- **날짜 충돌**: 한 검색 요약은 "Opus 5.5가 10월 말 출시"라고 했지만, MacRumors·MarkTechPost는 9/22로 명시했다. **9/22가 맞을 가능성이 높다(기간 외 맥락).** 가격도 출처마다 "60% 저렴"과 "$4/$20, 20% 저렴"으로 엇갈린다.

**[항목 3] Anthropic: Agent Skills를 Agentic AI Foundation에 기증 (2026-10-22)** — [Anthropic](https://www.anthropic.com/news/donating-agent-skills-to-the-agentic-ai-foundation)
- Agent Skills 오픈 표준을 중립 재단에 넘겼다. 이미 여러 플랫폼이 이 표준을 지원한다. MCP에 이어 에이전트 인터페이스를 표준화하려는 전략의 연장선이다. (본문 상세는 미확인. 뉴스룸 목록 요약 기준)

**[항목 4] Matt Garman (AWS CEO): a16z 팟캐스트 "Building Infrastructure for the Agent Era" (진행 Raghu Raghuram, 10월 초 추정, 정확한 날짜 미확인)** — [BigGo 요약](https://finance.biggo.com/news/4c7cebbc65a417f0); [BigGo podcast](https://finance.biggo.com/podcast/4c7cebbc65a417f0)
- 요약: Garman은 지금의 클라우드가 장기 자격증명과 영구 DB를 쓰는 인간 개발자에 맞춰 만들어졌다고 짚었다. 그래서 수백만 개의 일시적·자율적 에이전트에는 근본적으로 맞지 않는다고 했다. AWS는 30초 이내 계정 생성, Firecracker 샌드박스, Graviton·Trainium 칩 같은 기본 요소를 에이전트용으로 다시 만들고 있다. "머신 속도의 보안(machine-speed security)"도 필요하다고 했다. AWS 내부 엔지니어링은 "에이전트 우선"이어서, 에이전트가 코드를 모두 쓰고 사람은 에이전트 팀을 관리한다고 했다.
- 별도 클립 (FT·BCG "CEO Moments of Truth" 인터뷰, 10월 중순 추정): "when I asked the team to go rebuild that inference engine under Bedrock, we had like six people that were doing that." → "Bedrock 아래 추론 엔진을 다시 만들라고 팀에 요청했을 때, 그 일을 한 사람은 대략 6명이었습니다." (예전에는 새 AWS 서비스 하나에 200~300명이 들었다는 대비) — [X @CEOinterview](https://x.com/CEOinterview/status/2112233169978278158)
- 함의: 하이퍼스케일러 CEO가 "소수 인원 + 에이전트"로 생산성이 수십 배 오른 사례를 직접 공개했다. 노동시장 논의에 쓸 만한 구체 근거다.

**[항목 5] Arthur Mensch (Mistral CEO): Abu Dhabi "AI Everything" 발언 (10/6), LinkedIn 글 (10/15), Mistral Large 4 공개 (10/29)**
- 10/6: 새 모델이 사이버보안에서 중국 시스템을 앞선다고 주장했다. 다만 벤치마크나 상대 모델명은 밝히지 않았다. — [RuntimeWire](https://runtimewire.com/article/mistral-model-cybersecurity-claim-chinese-rivals)
- 10/15: 유럽에서 퍼지는 "프런티어 모델은 미·중에 맡기자"는 생각을 "근본적 실수(a fundamental mistake)"라고 비판했다. 그리고 선택지를 "만들거나 항복하거나(build or surrender)"로 규정했다. 오픈 모델이 도움은 되지만, 통제권을 지키려면 유럽이 출시와 접근 방식을 스스로 정해야 한다고 했다. — [Cybernews](https://cybernews.com/ai-news/mistral-europe-surrender/)
  - 인용: "a fundamental mistake" → "근본적인 실수"
- 10/29: 1조 파라미터 오픈웨이트 모델 Mistral Large 4("Le Chonk")의 가중치를 공개했다. Mistral은 이 모델이 Artificial Analysis Coding Agent Index에서 오픈 모델 1위(근소한 차이)이며, 에이전트 코딩·사이버 방어용 최고 오픈 모델이라고 주장했다. 기업과 정부가 내려받아 직접 배포할 수 있다. — [TechCrunch](https://techcrunch.com/2026/10/29/mistral-releases-weights-for-its-trillion-parameter-ai-model-targeting-cybersecurity/); [Fortune](https://fortune.com/2026/10/29/mistral-releases-new-model-large-4-and-claims-top-open-model-for-agentic-coding-and-cyber-defense/)
- 날짜 충돌: Cybernews는 공개일을 10/27, TechCrunch·Fortune은 10/29로 적었다.
- 맥락: Wikipedia에 따르면 2026년 9월 Samsung이 €30억 거래로 지분을 인수했고 기업가치는 €210억이다. 다른 사이트는 $245억으로 적어 출처마다 다르다. — [Wikipedia](https://en.wikipedia.org/wiki/Mistral_AI)

**[항목 6] Elon Musk / xAI (SpaceX 산하): 제품 발표와 X 게시물**
- 기업 구조: 검색 요약에 따르면 xAI는 2026년 2월 SpaceX에 인수됐다(기업가치 2,500억 달러). 7월 "SpaceXAI"로, 10월(Musk 10/4 확인)에는 "SpaceX Super Intelligence(SpaceXSI)"로 이름을 바꿨다고 한다. 출처 간 명칭이 일치하지 않는다. — [Wikipedia: SpaceXAI](https://en.wikipedia.org/wiki/SpaceXAI); [Taskade](https://www.taskade.com/blog/xai-grok-history)
- 10/3: Grok 4.7이 grok.com Expert 모드에 적용됐다(애그리게이터 출처). 10/7: Musk가 앞으로 Grok Bot이 작업마다 Claude Opus 5.5 등 **최적의 백엔드 모델을 골라 쓰겠다**고 말했다고 보도됐다. 10/8: Grok Imagine Video 1.5 Lite가 나왔다. 10/12: Grok·Grok Bot·Cursor·X Premium을 묶은 "The X Subscription"이 나왔다. 10/14: Grok Voice 3.0(음성-음성, 분당 $0.08)이 나왔다. — [Taskade](https://www.taskade.com/blog/xai-grok-history); [explainx xAI 타임라인](https://explainx.ai/blog/topics/xai) (모두 2차 출처라 공식 확인 필요)
- 10/11: Musk가 Grok이 $241짜리 Lego 세트를 구매하는 스크린샷을 올렸다가 배송·결제 주소를 노출했다. 그는 사용자가 신용카드를 촬영해 올리면 Grok이 대신 주문할 수 있다고 홍보했다(에이전트 커머스). — [Statesman](https://www.statesman.com/business/article/elon-musk-grok-ai-shopping-order-details-22474139.php); [Ynet](https://www.ynetnews.com/tech-and-digital/article/b1bfjwksfe)
- AGI 타임라인 (맥락): 2026-09-14 Musk는 X에서 "That will be Grok 5"라고 답했다 → "그건 Grok 5가 될 것이다"(첫 AGI가 Grok 5라는 의미). Grok 5(6조 파라미터 계획)는 Colossus 2에서 학습 중이며 여러 차례 출시 시점을 놓쳤다. — [Parameter](https://parameter.io/elon-musk-claims-grok-5-will-achieve-agi-breaking-down-the-bold-prediction/); [Teslarati (2025 원 발언 "10%")](https://www.teslarati.com/elon-musk-grok-5-now-has-10-percent-chance-of-becoming-worlds-first-agi/)
- 함의: xAI의 Grok Bot이 경쟁사 모델(Claude)까지 백엔드로 쓰겠다고 한 것은 자체 모델 우위 주장에서 "라우터/애그리게이터" 전략으로 실용적으로 옮겨 간 것으로 읽힌다. (2차 출처 기반이므로 확인 필요)

### Inferences
- 10월에는 "소형·저가 모델 + 에이전트 오케스트레이션"(Haiku 5.5, Grok Bot 라우팅, AWS 에이전트 기본 요소)이 공통 주제였다. 경쟁의 축이 단일 최고 모델에서 에이전트 시스템 비용·지연 최적화로 넓어지고 있다.
- Clark의 "특이점 시작" 선언은 Anthropic이 2024~25년 Amodei 에세이 "Machines of Loving Grace"에서 예측한 시점(2026~27년 강력한 AI)이 맞아 가고 있다는 내부 확신이 커졌음을 보여 준다(추론).
- Mistral은 "주권 AI + 오픈웨이트 + 사이버보안"으로 미국 폐쇄형 연구소와 차별화하고 있다.

### Gaps
- Import AI 477 원문(jack-clark.net 차단)을 직접 확인하지 못했다. 인용 문구는 2차 보도 기준이다.
- Jared Kaplan은 The Curve 2026(10/2~4, Berkeley) 연사 명단에만 확인된다 — [The Curve](https://thecurve.goldengateinstitute.org/). 발언 내용은 찾지 못했다.
- Mike Krieger의 10월 공개 발언은 찾지 못했다.
- Dario Amodei의 10월 인터뷰는 확인하지 못했다. Decoder(10/26) 출연 여부, Dario·Daniela 공동 YouTube 영상(10/27 업로드)의 내용은 미확인이다 — [YouTube](https://www.youtube.com/watch?v=1OdoSzfUkec); [podcastrex](https://podcastrex.com/people/dario-amodei). 가장 최근에 확인된 정식 인터뷰는 CBS Sunday Morning(9/14, 기간 외)이다: "for too long the industry lied to people about the fact that this technology had risks" → "너무 오랫동안 업계는 이 기술에 위험이 있다는 사실에 대해 사람들에게 거짓말을 해 왔습니다" — [CBS](https://www.cbsnews.com/news/anthropic-ceo-dario-amodei-on-ai-risks/)
- Grok 관련 날짜·명칭은 모두 2차 출처라 x.ai 공식 확인이 필요하다.

---

## 2. 안전·정책에 대해 무엇을 말했나

### Takeaway
Anthropic은 10월 한 달 동안 안전·정책 발표를 10건 넘게 쏟아냈다(사이버 미션, 증류 방어, 독립 평가자, 선거, Usage Policy, 공익 펀드, LTBT 인선). 동시에 S-1에 실존적 위험을 위험 요인으로 적어 정치권의 질의(Warren 의원, NYC 감사관)를 받았다. 중국 연구소(Zhipu, Moonshot)를 실명으로 지목한 증류 보고서는 국가안보 프레이밍을 강화했다.

### Cited Findings

**[항목 7] Anthropic: "Strengthening our defenses against distillation attacks" (2026-10-12)** — [Anthropic](https://www.anthropic.com/news/distillation-defenses)
- 요약: 새 방어 조치로 증류자가 Claude에서 빼낼 수 있는 추론 데이터가 초기 증거 기준 약 90~99%(10배~100배 이상) 줄었다. 실명 지목 대상은 두 곳이다. 하나는 **Zhipu**로, GLM-5.3을 만들며 미국 모델에서 사이버 역량을 증류했고, 미국 CAISI는 GLM-5.3을 지금까지 나온 오픈웨이트 중 사이버 역량이 가장 높은 모델로 평가했다. 다른 하나는 **Moonshot**(Kimi)으로, 요청을 Claude로 몰래 넘겼고 그중 PLA 연계로 추정되는 사용자가 특정인의 CCTV 감시 분석을 요청했다. 실험 결과도 공개했다. Opus 4.8의 전체 추론 기록으로 학습한 모델은 SWE-bench Verified 80.4%, 요약본으로 학습하면 71.8%였다. 이는 원시 추론 기록의 가치를 보여 준다. 조치로는 추론의 조직 외 이동 차단(8/31 이후 생성 API 계정 대상 "preserved thinking"), 2단계 분류기(오탐 0.1% 미만), 수만 개 계정 정지(캠페인 시작 후 대개 2시간 안), 차단 요청 과금(9/24부터)을 들었다. 증류자에게서 나오던 매출 일부를 포기했다는 점도 인정했다.
- 인용: "We expect that distillation will remain a cat-and-mouse game." → "증류는 앞으로도 쫓고 쫓기는 게임으로 남을 것으로 예상합니다."
- 인용: "Preventing distillation is important both for our national security and for ensuring that powerful models [are released with safeguards]" → "증류를 막는 것은 국가안보에도, 강력한 모델이 안전장치를 갖춘 채 출시되도록 하는 데에도 중요합니다."
- 함의: 미·중 AI 경쟁에서 "모델 탈취"를 수출통제와 같은 국가안보 이슈로 묶으려는 정책 메시지다.

**[항목 8] Anthropic Cyber Mission (2026-10-08)** — [Anthropic](https://www.anthropic.com/news/anthropic-cyber-mission)
- 요약: 핵심 인프라와 오픈소스를 지키는 장기 프로그램이다. 창립 파트너는 11곳이다(Accenture, Booz Allen, CrowdStrike, Deloitte, Dragos, Hitachi, Insane Cyber, Nozomi, Palo Alto Networks, PwC, Rockwell). OSS Scanner는 최상위 모델로 오픈소스를 무료로 스캔하며 참양성률 90% 이상을 기대하고, 보고서는 사람 검토 없이 발송된다. Project Glasswing으로 오픈소스 수백 개를 스캔했다. 미국 주의 절반 이상에 프런티어 Claude를 제공했다. 같은 주에 Cyber Verification Program도 확대했다(10/6). 링크 URL로 보아 Claude Mythos 5를 방어자에게 더 넓게 제공하는 Defender Advantage Fund와 연결된다. — [Anthropic](https://www.anthropic.com/news/cyber-verification-program)
- 인용(Anthropic): "Frontier models can be misused to exploit vulnerabilities and conduct cyber operations." → "프런티어 모델은 취약점을 악용하고 사이버 작전을 수행하는 데 오용될 수 있습니다."
- 인용(Palo Alto Networks, Sam Rubin): "Threat actors are using AI to find and exploit exposures at machine speed." → "위협 행위자들은 AI로 머신 속도로 노출 지점을 찾아 악용하고 있습니다."

**[항목 9] Anthropic 기타 안전·거버넌스 발표 (뉴스룸 목록 기준)** — [Anthropic Newsroom](https://www.anthropic.com/news)
- 10/8 "2026 Usage Policy update"(정책 개정), 10/14 "Preparing for the 2026 US midterms"(선거 안전장치 강화)
- 10/15 "An update on independent evaluators": **METR에 직원 수준의 접근권**을 줬고 다른 평가기관과도 협의 중이다 — [Anthropic](https://www.anthropic.com/news/an-update-on-independent-evaluators)
- 10/21 물리학자 Christopher Stubbs(전 Harvard 과학 학장)가 Long-Term Benefit Trust에 합류했다 — [Anthropic](https://www.anthropic.com/news/christopher-stubbs-joins-long-term-benefit-trust)
- 10/30 연구: Claude가 만든 미정렬(misalignment) 데이터셋으로 자사 학습 모니터를 레드팀했다(검색 요약 기준, 원문 미확인) — [aiweekly](https://aiweekly.co/ai-news-today/anthropic-news)
- 10/8 Genesis Mission(미 연방 AI 과학 이니셔티브)에 3년간 1.5억 달러를 약정했다 — [Anthropic](https://www.anthropic.com/news/genesis-mission-commitment)
- 10/14 싱가포르 사무소를 열고 싱가포르 정부와 MOU를 맺었다 — [Anthropic](https://www.anthropic.com/news/singapore-office-opening)
- 10/27 GSA 파트너십을 확대해 연방부터 지방 정부까지 할인가로 Claude를 공급한다 — [Anthropic](https://www.anthropic.com/news/expanding-partnership-gsa)

**[항목 10] IPO 관련 정치권 압박**
- 10/14 뉴욕시 감사관 Mark Levine이 Amodei에게 서한을 보내 안전·거버넌스 문제를 해결할 때까지 IPO를 멈추라고 촉구했다(2차 출처) — [blog.mean.ceo](https://blog.mean.ceo/dario-amodei-news-october-2026/)
- Elizabeth Warren 상원의원이 S-1의 실존적 위험 문구에 대해 4쪽 분량 질의서를 보내 11/3까지 "철저한 답변"을 요구했다고 보도됐다(WSJ 인용 2차 출처) — [explainx](https://explainx.ai/blog/warren-letter-amodei-anthropic-s-1-existential-risk-questions-november-3-wsj-what-is-confirmed-2026)
- Bloomberg 헤드라인에는 트럼프 행정부 상대 법적 승소와 Mythos 모델 조사 언급이 있다(세부 미확인) — [Bloomberg](https://www.bloomberg.com/anthropic)

**[항목 11] Mira Murati (Thinking Machines Lab): AI 거버넌스 경고 (날짜 불명확)**
- The Next Web은 Murati가 "18개월 만에 AI 거버넌스 경고와 예상 밖 제품을 들고 재등장"했다고 보도했다. 그러나 이것이 6월 Bloomberg Tech("interaction models" 프리뷰) 때의 발언인지 10월 발언인지 확인할 수 없었다 — [TNW](https://thenextweb.com/news/mira-murati-resurfaces-after-18-months-with-a-warning-about-ai-governance-and-a-product-no-one-expected); [Crypto Briefing](https://cryptobriefing.com/mira-murati-thinking-machines-lab-bloomberg-tech/)

### Inferences
- Anthropic은 IPO 직전에 "안전 = 사업 신뢰성"이라는 서사를 공격적으로 굳히고 있다. 사이버 방어, 정부 공급(GSA·Genesis·싱가포르), 중국 증류 차단을 한 묶음으로 내세워 정부를 핵심 고객이자 정책 동맹으로 삼는 전략이다.
- 반대로 S-1에 실존적 위험을 명시하자 정치권에서 "그렇게 위험하다면 왜 상장하나"라는 역공이 나왔다. 상장 기업이 되면 안전 발언의 법적·정치적 비용이 커진다(추론).

### Gaps
- Warren 서한과 Levine 서한의 원문, Anthropic의 답변은 확인하지 못했다.
- xAI, SSI, Perplexity의 10월 안전·정책 발언은 찾지 못했다. NYC 시의회는 SpaceXAI가 10/16 출석하기로 했다고 밝혔으나 발언 내용은 미확인이다 — [Taskade](https://www.taskade.com/blog/xai-grok-history)

---

## 3. 컴퓨트 딜·매출 성장: 공개된 구체 수치

### Takeaway
이 기간의 핵심 수치는 두 가지다. Anthropic S-1(10/26)은 2026년 상반기 매출 163억 달러(2025년 연간 46억 달러), 컴퓨트 약정 약 5,420억~6,370억 달러(리스 포함 최대 7,500억 달러)를 드러냈다. Amazon Q3 실적(10/29)은 AWS 매출 약 460억 달러(+39.3%, 6분기 연속 가속), 백로그 5,780억 달러, 2026 capex 약 2,200억 달러를 보여 줬다. 둘 다 AI 수요가 공급을 넘어서는 상황을 수치로 확인시킨다.

### Cited Findings

**[항목 12] Anthropic S-1 공개 (2026-10-26, Nasdaq "ANT", 주관사 Goldman Sachs·Morgan Stanley)** — [Anthropic 공식](https://www.anthropic.com/news/s1-sec); [SEC S-1](https://www.sec.gov/Archives/edgar/data/0002130357/000162828026067168/anthropicpbc-sx1.htm)
- 매출: 2026년 상반기 **163억 달러**(전년 동기 대비 +1,300%). 2025년 연간은 46억 달러였다 — [Yahoo Finance 라이브](https://finance.yahoo.com/technology/live/anthropic-ipo-live-updates-frontier-ai-lab-discloses-revenue-and-risks-in-highly-anticipated-s-1-filing-141702607.html); [CNN](https://www.cnn.com/2026/10/26/tech/anthropic-files-ipo)
- 수익성: TechCrunch에 따르면 2분기 영업이익을 기록했다(검색 요약 기준) — [TechCrunch](https://techcrunch.com/2026/10/28/anthropic-just-launched-tools-to-show-companies-what-their-ai-spending-is-buying)
- 컴퓨트 효율: 컴퓨팅 인프라 지출 1달러당 매출이 2달러를 넘는다 — [Fortune](https://fortune.com/2026/10/26/anthropics-s-1-makes-clear-its-on-the-hook-for-billions-in-compute-its-customers-can-walk-at-any-time-2/)
- 컴퓨트 약정 (**출처마다 다름**): Fortune은 5,420억~5,670억 달러, 칩 리스 포함 최대 7,500억 달러로 봤다 — [Fortune](https://fortune.com/2026/10/26/anthropics-s1-ipo-reveals-the-inner-workings-of-its-fast-evolving-compute-strategy/). Tomasz Tunguz는 6,370억 달러(3분의 2가 해지 불가)로 봤다 — [Tunguz](https://tomtunguz.com/anthropics-s1-grew-eleven-fold/). 또 다른 분석은 5,870억 달러로 봤다 — [Kepler](https://kepler.ai/research/financial/s1-anthropic/); [Gupta](https://guptadeepak.com/anthropic-s1-ipo-filing/). Decoding Discontinuity는 컴퓨트 약정 총액이 S-1에서 공란이라고 지적했다 — [Decoding Discontinuity](https://www.decodingdiscontinuity.com/p/anthropic-s1-compute-commitments)
- "Anthropic Direct": 자체 데이터센터를 세워, 수요가 몰릴 때 단기 컴퓨트 계약을 더 싼 자체 컴퓨트로 대체하는 계획이다 — [Fortune](https://fortune.com/2026/10/26/anthropics-s1-ipo-reveals-the-inner-workings-of-its-fast-evolving-compute-strategy/)
- 위험 요인 (S-1 인용, 검색 요약 기준): "our revenue is primarily consumption-based, and much of it is not subject to long-term contractual commitments" → "당사 매출은 주로 사용량 기반이며, 그중 상당 부분은 장기 계약 약정의 적용을 받지 않습니다." 반면 컴퓨트는 "minimum purchase commitments, take-or-pay provisions" → "최소 구매 약정, 테이크 오어 페이 조항"이 걸린 장기 계약이다. 즉 비용은 고정이고 매출은 유동적인 비대칭 구조다 — [Fortune](https://fortune.com/2026/10/26/anthropics-s-1-makes-clear-its-on-the-hook-for-billions-in-compute-its-customers-can-walk-at-any-time-2/)
- 상장 일정·규모: 이르면 11/16 거래를 시작한다(CNN). 최대 1,000억 달러를 조달하고 기업가치가 최대 2조 달러에 이를 수 있다는 보도가 있다(미확인, 2차 출처) — [CNN](https://www.cnn.com/2026/10/26/tech/anthropic-files-ipo); [Daily Hodl](https://dailyhodl.com/2026/10/28/anthropics-seven-co-founders-could-hold-up-to-203-billion-combined-if-ai-giant-hits-2-trillion-ipo-valuation-report/)
- 기타 공시: 2025년 Dario Amodei 개인 경호비 2,745,874달러(급여의 약 4배). 공동창업자들은 각자 지분의 80%를 기부하기로 약정했다 — [TNW](https://thenextweb.com/news/dario-amodei-security-cost-philanthropy-pledge-anthropic-ipo); [CNBC (10/29)](https://www.cnbc.com/2026/10/29/anthropic-ceo-dario-amodei-charts-new-direction-for-tech-philanthropy.html)

**[항목 13] Anthropic Public Benefit Fund (2026-10-18)** — [Anthropic](https://www.anthropic.com/news/public-benefit-fund)
- 처음에 주식 5%를 출연하고(주주 승인 조건), 기업가치가 기준선 대비 50% 오를 때마다 이사회가 2%를 더 넣을 수 있다. 구조는 LLC이며, 로비·정치 기부는 금지한다. 기존 약정(공동창업자 80% 기부, 직원 기부 매칭 약 절반 참여)과 합치면 **주식 약 20%가 공익에 배정**된다. AI 노동시장 영향 연구에 2억 달러를 이미 약정했다. 원래 임원 보상으로 갈 지분을 공익으로 돌린다.
- 인용: "the more Anthropic grows, the larger the share of the company that can be dedicated expressly to the public good" → "Anthropic이 성장할수록 공익에 명시적으로 쓸 수 있는 회사 지분도 커집니다."
- 인용: "We are instead directing that equity to the public benefit." → "우리는 대신 그 지분을 공익으로 돌리고 있습니다."

**[항목 14] Amazon Q3 2026 실적·콜 (2026-10-29 발표, 발언자 Andy Jassy CEO, Brian Olsavsky CFO)** — [aboutamazon (AWS 성장)](https://www.aboutamazon.com/news/company-news/aws-growth-ai-demand-q3-2026-earnings); [aboutamazon (커스텀 칩)](https://www.aboutamazon.com/news/company-news/amazon-custom-chips-demand-q3-2026-earnings); [Motley Fool 전문](https://www.fool.com/earnings/call-transcripts/2026/10/30/amazon-amzn-q3-2026-earnings-call-transcript/); [Yahoo 요약](https://finance.yahoo.com/markets/stocks/articles/amazon-com-inc-q3-2026-123000887.html); [TradingKey](https://www.tradingkey.com/news/transcripts/262256105-tradingkey) (aboutamazon·fool 원문은 차단돼 검색 요약 기준)
- 전체 실적: 매출 2,019억 달러(+12%), 영업이익 281억 달러(+61%). EPS 1.89달러로 예상을 소폭 밑돌았고 시간외에 주가가 떨어졌다는 보도가 있다(Investing.com). 다른 요약은 EPS 미스를 언급하지 않는다 — [Investing.com](https://www.investing.com/news/transcripts/earnings-call-transcript-amazon-q3-2026-misses-eps-as-shares-fall-after-hours-93CH-4985489)
- AWS: 매출 약 460억 달러로 **+39.3%**다. 6분기 연속 가속했고 거의 5년 만의 최고 성장률이다. **백로그 5,780억 달러.** 경영진은 2027·2028년 각각 40% 넘는 성장을 내다봤고, Jassy는 "1조 달러 이상 AWS 사업"을 목표로 제시했다.
- 추론(inference)은 이미 AWS AI 매출의 "절반을 훨씬 넘고" 계속 늘고 있으며, 기업 추론은 아직 초기 단계라고 했다.
- Bedrock은 "AWS 역사상 가장 빠르게 성장하는 수십억 달러 규모 서비스"이며, Bedrock 대부분이 Trainium 위에서 돌아간다.
- Trainium·Graviton 매출 약정이 각각 **전년 대비 20배 넘게** 늘었다. Trainium 랙을 외부(AWS 밖)에 판매할 계획이며 2027년 말 시작이 목표다 — [Benzinga](https://www.benzinga.com/markets/tech/26/10/62727953/amazon-trainium-ai-chips-2027); [TechTimes](https://www.techtimes.com/articles/329735/20261030/amazon-commits-selling-trainium-chips-outside-aws-late-2027-target-set.htm)
- Capex: Q3 현금 capex 759억 달러. 2026년은 약 2,200억 달러로 재확인했고, 2027년은 "의미 있게 더 높을 것"이라고 했다.
- 마진 긴장: AI 마진이 기존 클라우드보다 낮아 불리한 믹스 효과가 생긴다. Olsavsky는 부품 가격 역풍도 언급했다.
- 직접 인용 (검색 요약 기준)
  - "Even at $220 billion, we will not have enough capacity to meet demand." → "2,200억 달러를 쓰더라도 수요를 맞출 만큼의 용량은 확보하지 못할 것입니다." — [Benzinga](https://www.benzinga.com/markets/tech/26/10/62727953/amazon-trainium-ai-chips-2027)
  - "the majority and most of Bedrock today is being run on top of Trainium." → "오늘날 Bedrock의 대부분은 Trainium 위에서 실행되고 있습니다."
  - "Revenue commitments for Graviton and Trainium have each increased more than 20x year over year." → "Graviton과 Trainium의 매출 약정은 각각 전년 대비 20배 이상 증가했습니다."
- Anthropic·Project Rainier 관련 Q3 2026 콜 발언은 검색에서 확인하지 못했다. Rainier 언급(Trainium2 약 50만 개, 연말까지 Anthropic 100만 개 이상)은 **Q3 2025 콜(기간 외 맥락)**이다 — [Fool Q3 2025](https://www.fool.com/earnings/call-transcripts/2025/10/31/amazon-amzn-q3-2025-earnings-call-transcript/)

**[항목 15] Perplexity: Aravind Srinivas, Sourcery 팟캐스트 (2026-10-12 전후)** — [Sourcery](https://www.sourcery.vc/p/breaking-aravind-srinivas-perplexity); [Global Indian Times (10/18)](https://www.globalindiantimes.com/p/perplexity-aravind-srinivas)
- 요약: Srinivas는 AI 네이티브 소기업이 다음 미국 경제 성장을 이끌 것이라고 주장했다. Perplexity 매출은 전년 대비 5배 성장 중이며 기업 도입이 빨라지고 있다고 했다. 사례로 1인 기업가 한 명이 Perplexity Computer(2026년 2월 출시된 클라우드 에이전트)에 연 100만 달러 넘게 쓰면서 연 300만 달러 매출을 낸다고 소개했다. 개인 에이전트를 유료 중소기업에 판매하는 전략이며, 기업가치를 1조 달러로 키우겠다는 뜻을 내비쳤다.
- 보조 수치: The Information/Reuters에 따르면 8월 연환산 매출은 7.5억 달러로, 연초 2.5억 달러 미만에서 늘었다 — [Wikipedia](https://en.wikipedia.org/wiki/Perplexity_AI). IPO는 2028년 목표(6월 CNBC, 기간 외)다.
- 신뢰도: 5배 성장, 1조 달러, 1인 기업 사례는 모두 본인 발언이나 홍보성 요약이며 감사받은 수치가 아니다.

**[항목 16] Thinking Machines Lab (Mira Murati): 매출·자금 (AI Magazine, 2026-10-21)** — [AI Magazine](https://aimagazine.com/news/thinking-machines-lab-hits-a-us-100m-run-rate-on-tinker)
- 연환산 매출 약 1억 달러를 넘었다(주로 Tinker와 오픈웨이트 Inkling 모델). 400억 달러 규모 자금 조달을 검토 중이며, NVIDIA 컴퓨트를 최소 1GW 발주했다(3월 NVIDIA와 Vera Rubin 1GW 계약).
- 기업가치는 출처마다 다르다: 9월 라운드 120억 달러(투자 추적 사이트) vs 9/3 Yahoo 보도 "400억 달러 가치에 10억 달러 조달 추진" — [SVIC](https://siliconvalleyinvestclub.com/companies/thinkingmachines/team/mira-murati/); [Wikipedia](https://en.wikipedia.org/wiki/Thinking_Machines_Lab)
- Murati 본인의 10월 직접 발언은 확인하지 못했다.

**[항목 17] Safe Superintelligence (Ilya Sutskever): 맥락**
- 7/27 NVIDIA가 장기 파트너십과 약 50억 달러 투자를 발표했고, 이로써 컴퓨트가 약 10배 늘었다(기간 외). 기업가치는 320억 달러(2025년 4월)다 — [AI Magazine](https://aimagazine.com/news/safe-superintelligence-sutskever-nvidia-and-a-us-32bn-ai-b)
- 10/1 SSI 명의 X 계정이 "중대한" 발표를 예고했다는 애그리게이터 보도가 있고, "이달 첫 모델 출시"라는 투자자 팟캐스트발 소문(Threads)도 있다. **둘 다 공식 확인되지 않았다** — [Vorplabs](https://vorplabs.com/models/labs/safe-superintelligence); [Threads](https://www.threads.com/@vaibhavsisinty/post/DbqMsWIm7r_/ilya-sutskever-left-open-ai-to-build-one-thing-safe-superintelligence-now-an/)
- Sutskever의 반복 발언(기간 외): "We have research that is worthy of scaling up." → "우리에게는 스케일업할 가치가 있는 연구가 있습니다."

### Inferences
- Anthropic의 상반기 매출(163억 달러)은 2025년 연간의 3.5배다. 하반기도 같은 속도라면 2026년 연간 400억 달러 이상도 가능하다(단순 외삽이며 S-1에 3분기 매출은 공란).
- AWS 백로그(5,780억 달러)와 Anthropic 컴퓨트 약정(약 5,400억~6,400억 달러)이 비슷한 규모라는 점이 눈에 띈다. AWS 백로그의 상당 부분이 Anthropic 약정일 가능성이 있지만 공시로 확인되지는 않았다(추론).
- 하이퍼스케일러와 연구소 모두 "공급 부족"을 말한다(Jassy: 2,200억 달러로도 부족). AI 인프라 버블 논쟁에서 수요 측 증거로 쓰일 수 있다. 다만 Anthropic S-1이 밝힌 "고정 비용 대 유동 매출" 비대칭은 하방 위험의 핵심 근거다.

### Gaps
- Amazon 콜 전문(fool.com, aboutamazon.com 차단)에서 Anthropic·OpenAI 관련 Jassy 직접 발언, Alexa+/Rufus 수치, 노동력 언급을 확인하지 못했다.
- Apple FY26 Q4 실적(11/2 장 마감 후)은 조사 시점에 나오지 않았다. 컨센서스는 EPS 약 2.00달러, 매출 약 1,133억~1,155억 달러다. 관전 포인트는 재설계된 Siri(WWDC26에서 "all-new Siri AI" 발표, 6월 베타), Google AI 기술 라이선스, 메모리 가격이다 — [Yahoo](https://finance.yahoo.com/technology/article/apple-to-report-q4-earnings-monday-with-iphone-18-sales-in-the-spotlight-190138409.html); [TipRanks](https://tipranks.com/news/apple-q4-earnings-are-on-nov-2-heres-what-analysts-expect-from-aapl-stock); [CNBC 7/29](https://www.cnbc.com/2026/07/29/tim-cooks-last-earnings-call-comes-at-momentous-time-for-apple-.html). 참고로 직전 Q3(6월 분기) 매출은 1,094억 달러(+16%)였다 — [SEC 8-K](https://www.sec.gov/Archives/edgar/data/0000320193/000032019326000018/a8-kex991q3202606272026.htm)
- xAI/SpaceXSI의 10월 컴퓨트·매출 수치는 찾지 못했다.

---

## 4. 엔터프라이즈 도입·노동시장 영향

### Takeaway
엔터프라이즈 쪽에서는 "인재 병목"이 새 핵심어였다. Anthropic은 FDE 1만 명 양성에 1억 달러를 약정했다(10/2). AI 지출 성과를 보여 주는 도구도 내놨고(10/28), Barclays·GSA 등으로 공급을 넓혔다. 노동시장 쪽에서는 Clark가 인지 노동자 약 20% 실직 시나리오와 청년층 고용 약 19% 격차를 제시했다. Amazon은 10월 초 1,000명 미만을 감원했지만 AI 때문이라고 공식적으로 밝히지는 않았다.

### Cited Findings

**[항목 18] Anthropic: Claude Frontier Academy (2026-10-02)** — [Anthropic](https://www.anthropic.com/news/claude-frontier-academy)
- 요약: 1억 달러로 2027년 말까지 Frontier Deployed Engineer(FDE) 1만 명을 양성한다. 의학 수련 모델을 본떠 3단계로 운영한다(대면 집중교육과 실기 → 자사에서 실제 유스케이스를 이끄는 12주 레지던시 → 최종 평가). 첫 FDE 배지는 2027년 초에 나올 예정이다. 1기 참여사는 Accenture, Bain, Capgemini, CBA, Deloitte, McKinsey, Morgan Stanley, Novo Nordisk 등이다. 파트너 네트워크에서는 46,000개 회사가 17.5만 개가 넘는 Claude 인증을 받았고, Basecamp 수료자는 약 4,000명이다.
- 인용 (Anthropic): "the people with the skills to make it work inside a real business have become the hardest talent to find." → "실제 비즈니스 안에서 AI가 작동하게 만들 역량을 가진 사람이 가장 찾기 어려운 인재가 됐습니다."
- 인용 (Steve Corfield, Anthropic 글로벌 사업개발·파트너십 총괄): "The hard part is building that depth of talent, engineers with the highest level of AI fluency." → "어려운 부분은 그런 깊이의 인재, 즉 최고 수준의 AI 활용 능력을 갖춘 엔지니어를 키우는 일입니다."
- 인용 (CBA Group CTO Rodrigo Castillo): "our teams have produced up to 3x more code changes in the past year." → "우리 팀은 지난 1년간 코드 변경을 최대 3배 더 만들어 냈습니다."
- 함의: 기업 AI 도입의 병목이 모델 성능에서 "배포 인력과 조직 역량"으로 옮겨 갔다는 공식 진단이다. 동시에 컨설팅사를 유통 채널로 굳히는 전략이다.

**[항목 19] Anthropic 엔터프라이즈 발표**
- 10/1 Barclays가 글로벌 운영 전반으로 Claude를 확대했다 — [Anthropic](https://www.anthropic.com/news/barclays-scales-claude)
- 10/28 기업이 AI 지출로 무엇을 얻는지 보여 주는 도구를 출시했다(기본적으로 데이터를 학습에 쓰지 않음) — [TechCrunch](https://techcrunch.com/2026/10/28/anthropic-just-launched-tools-to-show-companies-what-their-ai-spending-is-buying). ROI 입증 요구에 대응한 것으로 보인다.
- 10/27 제약사 6곳과의 신약 개발 파트너십 초기 성과를 공개했다 — [Anthropic Research](https://www.anthropic.com/research/early-progress-drug-development). 10/28 AI for Science를 재단·연구기관 20곳으로 넓혔다 — [Anthropic](https://www.anthropic.com/news/ai-for-science-expands-foundations-research-institutions)
- Google Workspace 사이드바 애드온(자연어로 열린 파일 편집)도 내놨다(검색 요약 기준, 날짜 미확인).

**[항목 20] 노동시장 발언**
- Jack Clark (10/17): 고객 서비스 등 고노출 분야의 일자리 감소를 인정했다. 인지 노동자 약 5명 중 1명이 실직하는 시나리오를 제시하고, 세수로 지원하자고 했다. 22~25세 고노출 직종 고용이 약 19% 뒤처졌다고 했다 — [The Rundown](https://www.therundown.ai/news/anthropic-jack-clark-singularity-imf); [Hraness](https://hraness.com/reading/inside-the-event-horizon-jack-clark-per-jacobsson-lecture); [CNBC](https://www.cnbc.com/2026/10/17/ai-us-gdp-anthropics-clark.html)
- Anthropic (10/18): AI 노동시장 영향 연구에 2억 달러를 이미 약정했고, "더 과감한 접근"이 필요할 수 있다며 Public Benefit Fund로 실직자 등 특정 집단에 직접 분배할 가능성을 열었다 — [Anthropic](https://www.anthropic.com/news/public-benefit-fund)
- Amazon: 10/7 Stores 부문 직원 1,000명 미만 감원(미국·영국·인도)을 확인했다(인원은 Reuters 보도). 2025년 10월 약 14,000명, 2026년 1월 16,000명을 합치면 누적 약 30,000명이다. Jassy는 AI 효율로 시간이 지나며 본사 인력이 줄 것이라고 말해 왔지만, 이번 감원을 AI 때문이라고 공식 귀속하지는 않았다. 직원 1,200명 넘게 AI 전략을 비판하는 공개서한에 서명했다 — [TechResearchOnline](https://techresearchonline.com/news/amazon-october-layoffs-stores-ai-workforce-restructuring/); [Beinsure](https://beinsure.com/news/amazon-layoffs-continue-in-october-after-30k-job-cuts/); [GeekWire (1월)](https://www.geekwire.com/2026/amazon-confirms-16000-more-job-cuts-bringing-total-layoffs-to-30000-since-october/)
- Garman (10월): AWS 서비스 재구축 인력이 200~300명에서 6명으로 줄었다는 사례(위 항목 4) — [X @CEOinterview](https://x.com/CEOinterview/status/2112233169978278158)
- Srinivas (10/12): AI 네이티브 1인·소기업이 성장 동력이라는 낙관론(위 항목 15) — [Sourcery](https://www.sourcery.vc/p/breaking-aravind-srinivas-perplexity)

### Inferences
- 노동 메시지가 갈린다. Anthropic(Clark)은 대규모 실직 시나리오와 재분배를 공론화하고, Perplexity는 "1인 기업 붐"이라는 낙관 서사를 편다. AWS는 생산성 사례를 내놓을 뿐 고용 함의는 직접 말하지 않는다.
- "FDE 부족"과 "엔트리 레벨 고용 감소"가 동시에 진행된다. AI 노동시장이 숙련 편향적으로 양극화하고 있음을 시사한다(추론).

### Gaps
- Dario Amodei의 10월 노동시장 신규 발언은 찾지 못했다. 10월 블로그들은 2025년 "엔트리 레벨 화이트칼라 일자리 절반" 경고를 반복할 뿐이다.
- Amazon Q3 콜에서 인력·AI 생산성 관련 Jassy 직접 발언은 확인하지 못했다(전문 접근 불가).

---

## 5. 과거 입장 대비 변화

### Takeaway
눈에 띄는 변화는 세 가지다. (1) Anthropic은 "위험 경고"에서 "특이점이 이미 시작됐다"는 현재형 선언으로 수위를 높이면서, 상장 기업으로서 공익 지분 약 20%라는 구조적 장치를 내놨다. (2) AWS는 "자체 클라우드 전용 칩"에서 Trainium 외부 판매로 방향을 틀었다. (3) xAI는 자체 모델 일변도에서 경쟁 모델까지 라우팅하는 쪽으로 옮겨 갔다(미확인). 노동 문제에서 Amodei는 5월부터 이미 수위를 낮춘 상태다.

### Cited Findings
- Amodei의 노동 입장: 2025년 5월 Axios에서 "엔트리 레벨 화이트칼라 일자리의 절반이 5년 안에 사라지고 실업률이 10~20%까지 오를 수 있다"고 했다. 2026년 5월에는 수위를 낮췄다: "If you automate 90% of the job, then everyone does the 10% of the job" → "일의 90%를 자동화하면 모두가 그 나머지 10%를 하게 됩니다" — [Fortune (2026-05-26)](https://fortune.com/2026/05/26/sam-altman-dario-amodei-walking-back-ai-jobs-apocalypse-prophecies-ipo/); [Fortune (2025-05-28)](https://fortune.com/2025/05/28/anthropic-ceo-warning-ai-job-loss). 반면 10월 Clark의 IMF 강연은 인지 노동자 약 20% 실직 시나리오를 다시 꺼냈다. **회사 내에서도 메시지가 다르다**(CEO는 완화, 정책 총괄은 시나리오 경고) — [The Rundown](https://www.therundown.ai/news/anthropic-jack-clark-singularity-imf)
- Anthropic의 지배구조: 공동창업자 80% 기부 약정(창업 당시)에 더해 10/18 Public Benefit Fund(5% + 기업가치에 연동해 추가)를 만들었다. 임원 보상 지분을 공익으로 돌리는 것은 새 조치다 — [Anthropic](https://www.anthropic.com/news/public-benefit-fund)
- Anthropic의 외부 평가: METR에 "직원 수준 접근"을 준 것은 기존의 제한적 사전 접근보다 확대된 조치다 — [Anthropic](https://www.anthropic.com/news/an-update-on-independent-evaluators)
- AWS 칩 전략: Trainium을 AWS 밖에서 판매하겠다고 공식화했다(2027년 말 목표). 이전에는 Trainium을 AWS 클라우드 안에서만 제공했다 — [TechTimes](https://www.techtimes.com/articles/329735/20261030/amazon-commits-selling-trainium-chips-outside-aws-late-2027-target-set.htm); [Benzinga](https://www.benzinga.com/markets/tech/26/10/62727953/amazon-trainium-ai-chips-2027)
- AWS 성장 전망: 2027·2028년 각각 40% 넘는 성장과 "1조 달러 이상 AWS"라는 장기 목표는 이전보다 공격적이다. 2025년 AWS 성장률은 20%대였다 — [Yahoo](https://finance.yahoo.com/markets/stocks/articles/amazon-com-inc-q3-2026-123000887.html)
- xAI: Grok Bot이 Claude Opus 5.5 등 타사 최적 모델을 백엔드로 쓰겠다고 했다(10/7, 2차 출처). Musk가 그동안 Grok 우위를 강조해 온 것과 대비된다 — [Taskade](https://www.taskade.com/blog/xai-grok-history)
- Mistral: "오픈 모델" 옹호에서 "유럽 주권 프런티어 개발(build or surrender)"과 사이버보안 특화로 강조점이 옮겨 갔고, 1조 파라미터 모델을 오픈웨이트로 냈다 — [Cybernews](https://cybernews.com/ai-news/mistral-europe-surrender/); [TechCrunch](https://techcrunch.com/2026/10/29/mistral-releases-weights-for-its-trillion-parameter-ai-model-targeting-cybersecurity/)
- Apple 리더십: Tim Cook이 9/1 CEO에서 물러나 John Ternus가 CEO가 됐다. 11/2 실적 콜이 Ternus의 첫 콜이다 — [Yahoo](https://finance.yahoo.com/technology/article/apple-to-report-q4-earnings-monday-with-iphone-18-sales-in-the-spotlight-190138409.html); [shattered.io (2차)](https://shattered.io/apple-ternus-first-earnings-47-5-margin-developers-2026/)

### Inferences
- IPO를 앞둔 Anthropic은 두 메시지를 함께 운용하는 것으로 보인다. 투자자에게는 "고성장·컴퓨트 효율(1달러당 2달러 초과)·2분기 영업흑자"를, 정책 무대에는 "특이점·규제 시급성"을 전한다. S-1에 실존 위험을 공시하고 정치권 질의가 이어지면서 두 메시지의 긴장이 앞으로 커질 수 있다.
- Amazon은 Anthropic 의존형 "AI 클라우드"에서 칩 판매까지 포함하는 수직 통합형 AI 인프라 공급자로 정체성을 넓히고 있다. NVIDIA와의 경쟁 구도가 더 뚜렷해질 수 있다.

### Gaps
- Tim Cook·John Ternus의 10월 AI 발언, Apple의 FY26 Q4 콜 내용(11/2 장 마감 후)은 조사 시점에 구할 수 없었다.
- Ilya Sutskever와 Mira Murati의 10월 본인 직접 발언(인터뷰·게시물)은 확인하지 못했다.
- Daniela Amodei의 10월 개별 발언은 찾지 못했다(10/27 공동 YouTube 영상 내용 미확인).
- Anthropic의 Q3 매출, AWS 백로그 중 Anthropic 비중 등은 공시상 공란이거나 공개되지 않았다.
