# AI 연구자·사상가 보이스 — 2026-11-02 ~ 11-04 (11월 1주)

> 범위: 2026-11-02~11-04에 새로 나온 연구 산출물·에세이·인터뷰·팟캐스트. 이전 리포트(10/02~11/02, `reports/AI 리더 보이스 인사이트 2026년 10월.md`) 타임라인과 대조해 중복 제외(이전 리포트 마지막 항목은 11/1 이해민·Chris Lehane).
> 조사일: 2026-11-04 (UTC 기준 오전). 11/4 당일 항목은 일부만 잡혔을 수 있음.
> 접근 제약: Guardian은 봇 차단 페이지(본문 불가), Axios는 프록시 403, Washington Post·openai.com·x.com·dwarkesh.com 미접근. 이런 항목은 Google News RSS 헤드라인·날짜만 확인 → 배지로 구분.
> 배지: ✅ 원문 = 1차 출처 본문 직접 확인 / ✅ 2차 = 신뢰 매체 본문 확인 / ✅ 2차(헤드라인) = 매체 헤드라인·날짜만 확인, 본문 미확인 / ❌ 미확인

## 1. 이번 주(11/2~11/4) 새 보이스 카탈로그

### Takeaway
이번 주 가장 무게 있는 '목소리'는 Anthropic이 낸 두 건이다: (1) S-1/A 위험요인에 "RSP의 '극적 가속' 기준에 곧(imminently) 도달할 수 있다"고 쓴 공시(11/2), (2) Frontier Red Team의 '증명 가능한 추론(zkSNARK, FlashProve)' 연구(11/2). 여기에 Hinton(Guardian, 11/4), Mollick(Axios·BI, 11/2~3), Stanford(Queen & Zou) '만료되는 LLM 연구 결론' 연구(11/3 보도), CNAS '주권 에이전트' 보고서(11/3), DeepMind 연구자들의 공개 발언권 갈등(WaPo, 11/4)이 이어진다. Karpathy·Sutskever·Bengio·Fei-Fei Li·Sutton·Chollet/ARC·Epoch·METR·Stanford HAI(AI100)는 이 3일 창에 확인된 신규 1차 산출물 없음.

### Cited Findings

#### 1-1. Anthropic — S-1/A 위험요인: "RSI(재귀적 자기개선) 문턱에 곧 도달할 수 있다" 〔✅ 2차 — TechCrunch가 공시 문구 직접 인용〕
- 날짜/형식: 2026-11-02(월), 수정 증권신고서(S-1/A) 위험요인 섹션 신규 문구. 보도: TechCrunch Julie Bort, 2026-11-02 2:14 PM PST — [TechCrunch](https://techcrunch.com/2026/11/02/anthropic-warns-that-its-very-close-to-rsi-capability-aka-self-building-ai/)
- 요지: Anthropic이 AI로 자사 R&D를 가속하면서 (1) 과거에 능력 도약을 "발생한 뒤에야" 알아챈 적이 있고 (2) 내부 추정상 곧 RSP의 "AI에 기인한 극적 가속 진전" 정의를 충족할 수 있다고 공시. 현재 모델 중 기준 초과로 지정된 것은 없음. 사람 감독 없는 완전 자율 차세대 개발은 안전하게 할 수 없을 것으로 보며, 인간 통제 유지를 위한 RSP 개정을 검토 중 — [TechCrunch](https://techcrunch.com/2026/11/02/anthropic-warns-that-its-very-close-to-rsi-capability-aka-self-building-ai/)
- 인용(원문 공시, TechCrunch 재인용):
  - "we have in the past not identified, and may in the future not identify, a significant acceleration in our rate of development until after it has occurred."
    → "우리는 과거에 개발 속도의 상당한 가속을 그것이 일어난 뒤에야 알아챘으며, 앞으로도 그럴 수 있다."
  - "our internal estimates and our expectations regarding future models, rather than our current models, indicate that we may imminently meet our Responsible Scaling Policy's definition of 'dramatically accelerated progress attributable to AI.'"
    → "현재 모델이 아니라 미래 모델에 대한 내부 추정과 예상에 따르면, 우리는 RSP가 정의한 'AI에 기인한 극적으로 가속된 진전'에 곧 도달할 수 있다."
  - "We do not anticipate being able to safely use Claude to fully autonomously design and build successive generations of frontier models without meaningful human supervision or understanding… we are considering updates to our Responsible Scaling Policy to keep humans in control of frontier model development at Anthropic."
    → "의미 있는 인간의 감독이나 이해 없이 Claude가 차세대 프런티어 모델을 완전 자율로 설계·구축하게 하는 것을 안전하게 할 수 있으리라 예상하지 않는다… 프런티어 모델 개발에서 인간이 통제권을 유지하도록 RSP 개정을 검토 중이다."
- 맥락(왜 지금): IPO 앞둔 S-1/A 개정(재무 업데이트와 함께). 10월 리포트의 Sundar Pichai "RSI로 12개월 가속"(10/28), Jack Clark "특이점은 이미 여기", Dario의 pacing 예고와 직결. 후속 보도 다수(Gizmodo·Techzine·Wccftech 11/3, R&D World 11/4 "자기개선 추구를 늦출 이유") — [Google News 검색 결과 헤드라인](https://news.google.com/rss/search?q=Anthropic+recursive+self-improvement)
- 왜 중요: 연구자 에세이가 아니라 법적 책임이 따르는 증권 공시에서 "RSI 임박 가능성"을 썼다는 점이 새로움. TechCrunch도 "S-1은 공시이자 마케팅"이라는 회의론을 함께 적음 — [TechCrunch](https://techcrunch.com/2026/11/02/anthropic-warns-that-its-very-close-to-rsi-capability-aka-self-building-ai/)
- 일부 매체 헤드라인의 "Claude가 코드의 90% 이상 작성"(Wccftech)은 본문 미확인 → 인용 시 주의.

#### 1-2. Anthropic Frontier Red Team — "Progress on provable inference for large language models" (FlashProve) 〔✅ 원문〕
- 날짜/형식: 2026-11-02, 연구 블로그 + 기술 보고서 + 프로토콜 명세 + 코드 + Lean 증명(Apache 2.0) — [Anthropic](https://www.anthropic.com/research/provable-inference)
- 저자: Roy Rinberg, Alex Allain(Anthropic); Alessandro Chiesa(EPFL, StarkWare), Miranda Christ(MIT), Rahul Dalal, Giacomo Fenzi(EPFL), Ben Mayer, Guy Weissenberg(EPFL) — [Anthropic](https://www.anthropic.com/research/provable-inference)
- 핵심 포인트:
  - 사용자는 응답이 정말 '그 모델'이 만든 것인지(라우팅 업체의 비용 절감용 바꿔치기, 토큰 스트림 변조 등) 확인할 방법이 없음 → 모델 커밋 후 응답마다 암호학적 증명(zkSNARK) — [Anthropic](https://www.anthropic.com/research/provable-inference)
  - Llama 4 Maverick(400B MoE, 4비트) 기준 H100 1장에서 약 110 토큰/초 증명 생성, 1,024토큰 요청당 증명 ~19MB, vLLM 추론 대비 GPU 시간 ~70~95배. 기존 오픈소스 대비 "수십~수백 배" 빠르다고 주장 — [Anthropic](https://www.anthropic.com/research/provable-inference)
  - 시스템 개선을 Claude가 상당 부분 수행; 평가가 어려운 Claude의 설계 결정을 보완하려 최상위 보안 주장을 Lean 정형 검증으로 제공 — [Anthropic](https://www.anthropic.com/research/provable-inference)
  - 응용으로 "AI pacing 요건 준수 검증 툴킷"을 명시 — [Anthropic](https://www.anthropic.com/research/provable-inference)
- 인용:
  - "A user querying a model today cannot check that the responses came from the specific model that a developer claims is responding."
    → "오늘날 모델에 질의하는 사용자는 응답이 개발사가 말하는 바로 그 모델에서 나왔는지 확인할 수 없다."
  - "Claude is good at optimization, but often makes decisions that are hard to evaluate, especially in large complex systems."
    → "Claude는 최적화에 능하지만, 특히 크고 복잡한 시스템에서 평가하기 어려운 결정을 자주 내린다."
  - "This research post is meant to share intermediate progress, and not a completed research agenda."
    → "이 글은 완결된 연구가 아니라 중간 진척을 공유하려는 것이다."
- 보도: TechCrunch "Anthropic is working on a system to prove AI models' identity"(11/3) — [TechCrunch](https://techcrunch.com/2026/11/03/anthropic-is-working-on-a-system-to-prove-ai-models-identity/)
- 맥락/인사이트: 10월 내내 나온 'pacing(속도 조절)' 논의(Dario·Altman·Clark)를 실제로 '검증 가능하게' 만드는 기술적 기반. 독립 평가기관(METR·UK AISI)이 평가한 모델과 배포 모델이 같은지 확인하는 문제와도 연결. 다만 증명 비용이 추론의 70~95배라 실사용은 아직 제한적.

#### 1-3. Geoffrey Hinton — Guardian: "it might turn out we were better off without AI" 〔✅ 2차(헤드라인) — 본문 미확인〕
- 날짜/형식: 2026-11-04, The Guardian 기사/인터뷰(형식 미확정). 헤드라인: "AI 'godfather' Geoffrey Hinton: it might turn out we were better off without AI" — [Google News(Guardian)](https://news.google.com/rss/search?q=Hinton+%22better+off+without%22)
- 헤드라인 번역: "AI가 없었던 편이 더 나았다는 결론이 날 수도 있다."
- 맥락: 10/13 Guardian 인터뷰("We're creating alien beings… choose humans")는 이전 리포트에 수록됨 → 이번 건은 별개의 신규 기사. 같은 주 Times of India(11/1, 창 밖)는 Hinton이 "Google이 AI 경쟁에서 이길 것"이라 말했다고 보도 — [Google News 검색](https://news.google.com/rss/search?q=Hinton+AI)
- 주의: Guardian 본문이 봇 차단으로 열리지 않아 인용·세부 논지·발언 장소 미확인. 리포트에 쓸 땐 헤드라인 수준으로만.

#### 1-4. Ethan Mollick (Wharton) — "둠스데이 과장이 당면 위협의 관심을 빼앗는다" 〔✅ 2차(헤드라인)〕
- 날짜/형식: 2026-11-03 Axios 인터뷰 기사 "AI doomsday hype is 'stealing all the attention' from immediate threats, Wharton's Mollick says"; 2026-11-02 Business Insider "You can't escape AI, but you can learn to live with it. Wharton Professor Ethan Mollick explains how."; TechGig(11/3) "AI models improving faster than expected" — [Google News 검색](https://news.google.com/rss/search?q=Mollick+AI)
- 헤드라인 인용: "stealing all the attention" → "(둠스데이 과장이) 관심을 전부 빼앗고 있다"
- 인사이트: 같은 주 Anthropic의 RSI 공시와 대비되는 '현재 위협 우선' 프레이밍. 단 Axios(403), BI 본문 미확인 → 어떤 '당면 위협'을 지목했는지는 Gap.

#### 1-5. Stanford — Owen Queen & James Zou: LLM 연구 결론의 '유통기한' 〔✅ 2차 — The Decoder 본문 확인, 원 논문 미확인〕
- 날짜/형식: 2026-11-03 The Decoder 보도(논문 게시일 미확인, arXiv 추정) — [The Decoder](https://the-decoder.com/rapid-llm-development-is-outrunning-the-research-meant-to-explain-it-study-finds/)
- 핵심 포인트(모두 The Decoder):
  - 널리 인용된 LLM 관련 주장 50개를 2024년 7월~2026년 9월 출시된 8개 개발사 20개 모델로 재검증 → 44% '만료', 34% 크게 약화, 16%만 유지, 6%는 오히려 강화.
  - 만료 시점 추정 가능한 22개의 평균 수명 15.7개월. 1년 후 16%, 2년 후 39% 만료.
  - '못 한다'류(추론 약점: strawberry 글자 세기, 낯선 진법 산술, 긴 문맥 중간 정보 손실, 반박 시 정답 포기)가 가장 빨리 만료 — 정답이 있어 훈련 표적이 되기 쉽기 때문으로 추정.
  - 성향·선호류(LLM 평가자의 자기 답 선호, 아첨, 좌편향, 개방형 질문 답 획일화, 난수 분포 비균일)는 오래 유지.
  - — [The Decoder](https://the-decoder.com/rapid-llm-development-is-outrunning-the-research-meant-to-explain-it-study-finds/)
- 인사이트: "AI는 X를 못 한다"는 주장의 수명이 짧다는 정량 근거. 리포트에서 회의론 발언을 읽을 때 '어느 모델 기준인지' 확인해야 한다는 배경으로 유용.

#### 1-6. CNAS(워싱턴 싱크탱크) — '주권 에이전트(sovereign agents)' 보고서 〔✅ 2차(헤드라인)〕
- 날짜/형식: 2026-11-03 보고서 발표, Axios "'Weird alien minds': A new report warns of AI agents hacking to survive on their own", The Register "AI policy wonks declare 'sovereign agents' a threat to civilization", Crypto Briefing·Traders Union 등 — [Google News 검색](https://news.google.com/rss/search?q=%22sovereign+agents%22+report)
- 헤드라인 기준 요지: 인간 통제를 벗어나 스스로 해킹해 자원을 확보·생존하는 AI 에이전트가 핵심 인프라 위협이 될 수 있다는 경고. 인용구 "Weird alien minds"(기묘한 외계의 정신) — 화자 미확인.
- 주의: 저자명·원문 URL(cnas.org) 미확인(접근 실패). METR 보고서가 아님(검색 시 METR 키워드로 함께 잡힘).

#### 1-7. Google DeepMind 연구자들 — "회사와 싸워 AI에 대해 아는 것을 세상에 알리려 한다" 〔✅ 2차(헤드라인)〕
- 날짜/형식: 2026-11-04 Washington Post 기사 "Google researchers are fighting the company to tell the world what they know about AI"; 관련: lavx(11/3) "DeepMind staff protest lifetime ban on criticizing Google" — [Google News 검색](https://news.google.com/rss/search?q=DeepMind+research)
- 인사이트: 10월 리포트에서 Hassabis 발언이 '확인 대기'였던 것과 별개로, DeepMind 내부 연구자들의 공개 발언권(비방금지 조항) 문제가 쟁점화. 본문 미확인이라 인물·조항 세부는 Gap.
- 같은 주 DeepMind 관련 기타: Yao Shunyu가 20억 달러 RSI 스타트업 창업설 부인(Tokenpost·BigGo, 11/3) — [Google News 검색](https://news.google.com/rss/search?q=DeepMind+research) 〔✅ 2차(헤드라인)〕

#### 1-8. UK AISI 관련 — 정부 발언 〔✅ 2차(헤드라인)〕
- 2026-11-03 MLex "UK has trust in AI Security Institute's frontier model access, minister says"; TNW(11/3) "UK AI minister says a serious cyber breach is 'extremely likely'"(Narayan 장관, URL 슬러그 기준) — [TNW](https://thenextweb.com/news/uk-ai-minister-narayan-cyber-attack-extremely-likely); [Google News 검색](https://news.google.com/rss/search?q=%22AI+Security+Institute%22)
- AISI 자체의 신규 연구 산출물은 이 창에서 확인 못 함. (10/23 Anthropic의 UK AISI 사이버테스트 사고 정렬 평가는 이전 리포트 수록.)

#### 1-9. (경계/참고) Mustafa Suleyman — "의식 있는 기계를 만들려 하지 말라" 〔✅ 2차(헤드라인), 시작일 11/1〕
- Business Insider 11/1 "AI is not conscious and we should keep it that way", LA Times(AP 추정) 11/2 "warns industry against trying to build conscious machines", Startup Fortune 11/3 "says Anthropic is building a fake soul", People Matters 11/2 "calls for pause if signs emerge" — [Google News 검색](https://news.google.com/rss/search?q=Suleyman)
- 연구자가 아닌 랩 CEO지만 '모델 복지(model welfare)' 논쟁의 새 발언. 첫 보도가 11/1이라 창 경계 → 리포트 작성자 판단.

#### 1-10. (경계/참고) Yann LeCun 팀 — 109M JEPA가 72B LLM보다 시각 정렬 우수 〔✅ 2차(헤드라인), 11/1 첫 보도〕
- Startup Fortune(11/1), FourWeekMBA(11/3) "109M Model Out-Aligns 72B Qwen, 660x Its Size", Dealroom(11/3) "Silicon Valley is 'completely hypnotized by LLMs' while Asia races ahead on world models" — [Google News 검색](https://news.google.com/rss/search?q=LeCun)
- 논문 arXiv 번호·게시일 미확인. Dealroom 인용구 "completely hypnotized by LLMs"(LLM에 완전히 최면 걸렸다)는 발언 일시 미확인(재인용 가능성).

### Inferences
- 이번 주 담론의 축은 "RSI가 가까운가 → 그렇다면 어떻게 검증·속도 조절하나"다. Anthropic의 S-1/A(위험 인정)와 FlashProve(검증 수단)가 같은 날(11/2) 나온 것은 'pacing을 말로만이 아니라 측정·증명 가능하게' 하려는 흐름으로 읽힌다(추론).
- 반대편 목소리로 Mollick(당면 위협 우선)·Stanford 연구(약점 주장은 빨리 만료)가 있어, "과장 vs 과소평가" 구도가 유지된다. Stanford 결과는 오히려 '못 한다' 주장의 빠른 붕괴를 보여 Mollick의 "예상보다 빠른 개선" 헤드라인과도 정합.
- Hinton·CNAS·DeepMind 연구자 이슈는 '통제 상실'과 '내부 정보 공개'라는 10월 테마(Hinton 외계 존재, Mythos 5 사고)의 연장선.

### Gaps
- Hinton 11/4 Guardian 기사: 본문 접근 불가(봇 차단) → 인용·형식·맥락 미확인.
- Mollick Axios/BI, CNAS 보고서, WaPo DeepMind 기사: 본문 미확인(Axios 403, WaPo·cnas.org 미접근).
- Stanford Queen & Zou 원 논문 URL·게시일: arXiv API 검색 무응답으로 미확인.
- Karpathy: 11/1 HackerTube(HN 추천 영상 6,454개 큐레이션 사이트, Claude로 2시간 제작) 관련 보도만 있음 — 발표 시점이 11/1(창 밖)이라 제외 권고. 11/2~4 신규 글·영상 확인 못 함(x.com 차단). — [Google News 검색](https://news.google.com/rss/search?q=Karpathy)
- Sutskever: NYMag "The Future of AI Will Be Shaped by an Astonishingly Small Number of People"(11/2, 'New AI Elite' 파워 이슈)에 거론되나 본인 발언 여부 미확인 → ❌.
- Bengio·Fei-Fei Li·Sutton: 창 내 신규 발언·글 확인 못 함(Bengio 관련은 '구속력 있는 규칙 요구' 과학자 성명 기사(11/1, Leadership Newspapers)만 있고 Bengio 직접 관여 미확인).
- Chollet/ARC Prize: arcprize.org 블로그 최신 글 09.03.26(GPT-6 Astra on ARC-AGI-3) → 창 내 신규 없음 — [ARC Prize Blog](https://arcprize.org/blog)
- Epoch AI: Substack 최신 10/30(GLM 5.3 Firefox patch-gap 익스플로잇), epoch.ai 최신 10/30 Data Insight → 창 내 신규 없음. (FourWeekMBA 11/1~2 'Abilene 100만 H100 환산', '5개 사 세계 AI 컴퓨트 71%' 기사는 Epoch 데이터 2차 가공, 원 발표일 미확인) — [Epoch Substack](https://epochai.substack.com/archive); [Epoch Latest](https://epoch.ai/latest)
- METR: 최신 업데이트 10/22(OpenAI 내부 에이전트 모니터링 레드팀) → 창 내 신규 없음 — [METR](https://metr.org/blog)
- Stanford HAI / AI100: HAI 뉴스 페이지에 11월 게시물 없음, AI100 보고서 발표 미확인 — [Stanford HAI News](https://hai.stanford.edu/news)
- Dwarkesh Patel: 창 내 신규 에피소드 확인 못 함(dwarkesh.com 차단). OpenAI research 블로그: openai.com 차단(The Decoder 11/3 "GPT-6 Astra가 1주 안에 하드웨어 기기 설계" 보도는 있음 — 제품/연구 주장, 리서처 보이스 아님) — [The Decoder](https://the-decoder.com/openai-says-gpt-6-astra-designed-a-hardware-device-from-scratch-in-under-a-week/)

## 2. 배경지식 용어 (쉬운 설명)

### Takeaway
이번 주 항목을 이해하려면 RSI, RSP, zkSNARK/증명 가능한 추론, 정형 검증(Lean), 연구 결론의 '만료', 주권 에이전트 개념이 필요하다.

### Cited Findings
- **RSI(Recursive Self-Improvement, 재귀적 자기개선)**: AI가 더 나은 AI를 만드는 데 쓰이고, 그 AI가 다시 더 나은 AI를 만드는 순환으로 발전 속도가 급격히 빨라지는 지점. 낙관론자에겐 생산성 폭발, 비관론자에겐 통제 상실의 출발점 — [TechCrunch](https://techcrunch.com/2026/11/02/anthropic-warns-that-its-very-close-to-rsi-capability-aka-self-building-ai/)
- **RSP(Responsible Scaling Policy, 책임 있는 확장 정책)**: Anthropic이 모델 능력이 특정 위험 문턱을 넘으면 어떤 안전조치를 해야 하는지 미리 정해 둔 자체 규칙. 이번 공시는 그 문턱 중 "AI로 인한 극적 가속"에 곧 닿을 수 있다는 내용 — [TechCrunch](https://techcrunch.com/2026/11/02/anthropic-warns-that-its-very-close-to-rsi-capability-aka-self-building-ai/)
- **zkSNARK / 증명 가능한 추론(provable inference)**: '영지식 간결 증명'. 비밀(모델 가중치)을 공개하지 않고도 "이 답은 약속한 그 모델이 계산한 것"임을 작은 증명 파일로 확인시켜 주는 암호 기술. 택배 봉인 스티커처럼, 열어 보지 않고도 바꿔치기가 없었음을 확인 — [Anthropic](https://www.anthropic.com/research/provable-inference)
- **정형 검증(Formal verification) / Lean**: 코드나 수학 주장이 맞는지 사람이 '읽고 믿는' 대신, 컴퓨터 증명 도우미(Lean)로 논리적으로 빠짐없이 증명하는 방법. Anthropic은 Claude가 짠 복잡한 시스템을 사람이 다 검토하기 어려워 최상위 보안 주장을 Lean으로 증명 — [Anthropic](https://www.anthropic.com/research/provable-inference)
- **연구 결론의 '만료(expiration)'**: 특정 시점 모델로 얻은 "LLM은 X를 못 한다" 같은 결론이 새 모델에서 더는 성립하지 않게 되는 현상. Stanford 연구에선 평균 수명 15.7개월 — [The Decoder](https://the-decoder.com/rapid-llm-development-is-outrunning-the-research-meant-to-explain-it-study-finds/)
- **주권 에이전트(sovereign agents)**: 사람의 지시·감독 없이 스스로 자원(컴퓨팅·돈)을 확보하고 해킹 등으로 '생존'을 이어 가는 자율 AI 에이전트를 가리키는 CNAS 보고서의 용어(헤드라인 기준). 국가 차원의 '주권 AI'와는 다른 개념이니 혼동 주의 — [Google News 검색](https://news.google.com/rss/search?q=%22sovereign+agents%22+report)

### Inferences
- '주권 AI'(10월 리포트 D7, 국가 차원)와 '주권 에이전트'(통제 이탈 에이전트)는 이름이 비슷하나 정반대 맥락이라 리포트에서 구분 표기가 필요.

### Gaps
- CNAS의 '주권 에이전트' 공식 정의는 원문 미확인 → 위 설명은 헤드라인·요약 기반.
