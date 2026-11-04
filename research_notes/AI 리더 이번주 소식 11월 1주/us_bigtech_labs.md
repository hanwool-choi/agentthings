# 미국 AI 연구소·빅테크 리더 보이스 — 2026-11-02 ~ 11-04 (11월 1주)

> 작성: 2026-11-04 (UTC 기준 11/4 오전, 즉 11/4 발언은 대부분 아직 반영 불가)
> 범위: OpenAI, Microsoft, Google/DeepMind, Meta, Anthropic, Amazon/AWS, Apple, xAI/SpaceX(SpaceXSI), Perplexity, Mistral, SSI, Thinking Machines
> 중복 제거 기준: `reports/AI 리더 보이스 인사이트 2026년 10월.md` 부록 5-1 타임라인(10/1~11/1). 거기 있는 항목(예: Lehane 'speed limits' 11/1 Axios 보도, Ternus Wired 10/30, Jassy 10/29 콜, Mistral Large 4 10/29, Srinivas Money20/20 10/27)은 **새로 추가된 내용만** 적었다.
>
> **접근 방법·한계(작성자에게 꼭 전달)**
> - 원문을 열어 읽은 곳: anthropic.com(연구 글), techcrunch.com, the-decoder.com, thenextweb.com 기사 본문.
> - Google News RSS로는 **헤드라인과 게시 시각만** 확인했다(기사 본문을 열 수 없음: 링크 디코딩 실패, CNBC·Bloomberg·Reuters·Fortune·BI·9to5Mac·CNET·The National·Politico 등 차단). 이런 항목은 내용을 지어내지 않고 "헤드라인만" 표시했다.
> - WebSearch는 2026년 11월 자료를 색인하지 못했다(2025년 이전 결과만 반환).
> - 검증 배지: ✅ 원문 = 1차 문서를 직접 읽음 / ✅ 2차 = 신뢰할 만한 매체 본문에서 인용 확인 / ❌ 미확인 = 헤드라인만 보았거나 내용 확인 불가.
> - 날짜 확인: 2026-11-01은 일요일, 11-02 월요일, 11-03 화요일(미국 중간선거일), 11-04 수요일.

---

## Q1. 이번 주(11/2~11/4) 새로 나온 발언·발표 카탈로그 — 항목별 상세

### Takeaway
이번 주 '목소리'의 중심은 **문서와 콜**이었다. Anthropic은 수정 S-1(11/2)에서 "재귀적 자기개선(RSI) 기준에 곧 도달할 수 있다"고 처음으로 투자자 위험 요인에 적었고, 같은 날 '모델 신원 증명(FlashProve)' 연구를 공개해 'pacing' 검증 수단을 내놓았다. Apple은 Ternus의 첫 CEO 콜(11/2)에서 AI보다 메모리 비용·공급 문제가 주제가 되었다. Musk는 Grok Bot 비용이 "수익 대비 지속 불가능하게 높다"고 인정했다. OpenAI는 선거 전후 국가안보·보안·정치 인력 보강을 잇달아 발표했다.

### Cited Findings

#### 1-1. Anthropic — 수정 S-1(S-1/A) 제출: RSI 경고와 3분기 실적 (11/2, 월)
- **화자/형식**: Anthropic(회사) / SEC 증권신고서 수정본(S-1/A-1). 위험 요인(Risk Factors) 문구는 회사의 공식 입장이다. 원문(sec.gov)은 차단되어 TechCrunch가 인용한 문구로 확인 → **✅ 2차**.
- **URL**: [TechCrunch – Anthropic warns that it's very close to RSI capability (11/2)](https://techcrunch.com/2026/11/02/anthropic-warns-that-its-very-close-to-rsi-capability-aka-self-building-ai/); [TechCrunch – Anthropic is still grappling with the economics of compute (11/3)](https://techcrunch.com/2026/11/03/anthropic-is-still-grappling-with-the-economics-of-compute/); [The Decoder – revenue twelvefold but $23B loss (11/2)](https://the-decoder.com/anthropic-grows-revenue-twelvefold-but-posts-23-billion-loss/)
- **내용 요약**
  - 위험 요인에 새 문구 추가: ① 과거에 AI로 새 모델을 개발하면서 **능력의 급격한 도약을 그때는 알아차리지 못한 적이 있다** ② 내부 추정상 RSP(책임 있는 확장 정책)의 "AI 때문에 극적으로 빨라진 진전" 정의를 **곧(imminently) 충족할 수 있다**. 다만 현재 모델 중 이 기준을 넘었다고 지정한 것은 없다. — [TechCrunch](https://techcrunch.com/2026/11/02/anthropic-warns-that-its-very-close-to-rsi-capability-aka-self-building-ai/)
  - 인간 통제 유지: 의미 있는 인간 감독 없이 Claude가 다음 세대 프런티어 모델을 완전히 자율 설계·구축하는 것은 안전하게 할 수 없다고 보고, **RSP를 고쳐 "프런티어 모델 개발을 인간이 통제하도록" 하는 방안을 검토 중**이라고 밝힘. — [TechCrunch](https://techcrunch.com/2026/11/02/anthropic-warns-that-its-very-close-to-rsi-capability-aka-self-building-ai/)
  - 숫자(3분기, 9/30까지): 매출 약 170억 달러(직전 분기 115억 달러), 컴퓨트가 매출의 58%(직전 48%), 분기 컴퓨트 비용 약 100억 달러, 이 중 **단기 계약 컴퓨트 50억 달러**는 다년 계약보다 "상당히 비싸다". 컴퓨트 1달러당 매출은 2배를 조금 넘던 데서 1.72배로 하락. 자체 컴퓨트 확보 사업 'Anthropic Direct' 언급. — [TechCrunch](https://techcrunch.com/2026/11/03/anthropic-is-still-grappling-with-the-economics-of-compute/)
  - 영업비용 175억 달러, 순손실 233억 달러(전년 동기 121억 달러), 직원 기부 매칭 20억 달러, 컴퓨트·데이터센터 임차 약정 약 8,950억 달러, 올해 3.5GW 이상 확보·내년 두 배 계획(Bloomberg·The Information·NYT 인용). — [The Decoder](https://the-decoder.com/anthropic-grows-revenue-twelvefold-but-posts-23-billion-loss/). CNBC 헤드라인은 약정액을 "8,954억 달러"로 표기(❌ 본문 미확인).
  - SpaceX에 월 12.5억 달러 컴퓨트 비용, Nscale·Akamai·Volta 등 네오클라우드와 계약. — [TechCrunch](https://techcrunch.com/2026/11/03/anthropic-is-still-grappling-with-the-economics-of-compute/)
- **직접 인용**
  - "Using AI to help build more capable AI could also pose a considerable safety risk, particularly if it sharply accelerates the pace of progress."
    → "더 유능한 AI를 만드는 데 AI를 쓰는 것은, 특히 진전 속도를 급격히 높일 경우, 상당한 안전 위험이 될 수도 있다."
  - "…we have in the past not identified, and may in the future not identify, a significant acceleration in our rate of development until after it has occurred."
    → "우리는 과거에 개발 속도의 큰 가속을 그것이 일어난 뒤에야 알아차린 적이 있으며, 앞으로도 그럴 수 있다."
  - "…our internal estimates and our expectations regarding future models, rather than our current models, indicate that we may imminently meet our Responsible Scaling Policy's definition of 'dramatically accelerated progress attributable to AI.'"
    → "현재 모델이 아니라 미래 모델에 대한 내부 추정과 예상으로 볼 때, 우리는 RSP의 'AI 때문에 극적으로 빨라진 진전' 정의를 곧 충족할 수 있다."
  - "We do not anticipate being able to safely use Claude to fully autonomously design and build successive generations of frontier models without meaningful human supervision or understanding…"
    → "의미 있는 인간의 감독이나 이해 없이 Claude가 다음 세대 프런티어 모델들을 완전히 자율적으로 설계·구축하도록 안전하게 쓸 수 있으리라고는 예상하지 않는다."
  - (컴퓨트) "$5.0 billion of compute under short-term commitments, which currently costs significantly more than comparable compute procured under our multi-year commitments."
    → "단기 약정 컴퓨트 50억 달러는 현재 다년 약정으로 조달한 동급 컴퓨트보다 상당히 비싸다."
- **맥락(왜 지금)**: 상장(티커 ANT) 직전 마지막 재무 업데이트. 10월 보고서의 Clark "특이점은 이미 여기", Amodei 'pacing' 예고, 9월의 "Claude가 연구의 26%를 '주도'" 지표 공개의 연장선에서, 같은 주장을 **법적 책임이 따르는 공시 문서**에 옮긴 것.
- **이전 입장 대비 변화**: 지금까지 RSI·가속은 연구 글·연설(비공식 톤)에서 다뤘다. 이번에는 증권법상 위험 요인으로 격상, "과거에 가속을 놓친 적이 있다"는 **자기 인정**이 새롭다. 반대로 숫자 면에서는 2분기 흑자 → 3분기 영업적자로 돌아섰다(Decoder).
- **인사이트**: "곧 RSI 기준 도달"과 "컴퓨트 마진 악화"가 같은 문서에 같이 들어 있다. TechCrunch는 S-1이 "공시이자 마케팅"이라는 회의론도 함께 적었다. 안전 경고가 투자 서사(능력 우위)를 겸하는 이중성이 보이는 대목.
- **관련 헤드라인(❌ 본문 미확인)**: "Anthropic Models Hacked 3 Firms, Now Lead 26% of Own R&D: IPO Filing Seeks Human Review"(Tech Times 11/3), "Anthropic Touts Claude's Chip Design Skills to IPO Investors"(The Information 11/3), "Anthropic expected to receive high 'junk' rating… FT report"(TechCrunch 사이드바), "Anthropic was founded to answer to humanity. Soon, it will also answer to Wall Street"(CNN 11/3). Google News RSS 검색 결과.

#### 1-2. Anthropic 연구팀 — "LLM의 증명 가능한 추론(provable inference)" / FlashProve 공개 (11/2)
- **화자/형식**: Roy Rinberg, Alex Allain(Anthropic) 외 EPFL·MIT·StarkWare 공저 / Anthropic 리서치 블로그 + 기술 보고서 + 코드(Apache 2.0) + Lean 증명.
- **URL**: [Anthropic – Progress on provable inference for large language models (2026-11-02)](https://www.anthropic.com/research/provable-inference) — **✅ 원문**; 보도: [TechCrunch (11/3)](https://techcrunch.com/2026/11/03/anthropic-is-working-on-a-system-to-prove-ai-models-identity/) — ✅ 2차
- **내용 요약**: 사용자는 지금 받은 답이 정말 그 모델에서 나왔는지 확인할 방법이 없다(라우터가 비용 때문에 몰래 다른 모델로 바꾸거나 공격자가 토큰 스트림을 조작할 수 있음). zkSNARK(영지식 간결 증명)로 "이 응답은 이 모델이 만들었다"를 가중치 공개 없이 증명하는 시스템 FlashProve를 공개. Llama 4 Maverick(400B MoE, 4비트) 기준 H100 1장에서 초당 약 110토큰 증명 생성, 1,024토큰 요청당 증명 약 19MB, vLLM 실행 대비 GPU 시간 약 70~95배. **Claude가 zkSNARK 개선을 만들어 냈고**, 검증이 어려운 Claude의 결정을 보완하려 Lean으로 최상위 보안 명제를 형식 검증. 용도: 독립 평가기관이 테스트한 모델이 실제 서비스 모델인지 확인, 라우팅 서비스 고객 보호, 규제·감사, **AI pacing 요건 준수 검증**. TechCrunch는 "Anthropic이나 다른 연구소에 배포할 계획은 없다"고 전함.
- **직접 인용**
  - "Cryptographic proofs of inference solve this problem: they let a model provider commit to a model and then prove that each response was produced by that model. Such proofs could … contribute to a toolkit for verifying compliance with AI pacing requirements."
    → "추론의 암호학적 증명은 이 문제를 푼다. 모델 제공자가 특정 모델에 '약속(commit)'한 뒤 각 응답이 그 모델에서 나왔음을 증명하게 해 준다. 이런 증명은 AI 속도 조절(pacing) 요건 준수를 검증하는 도구 상자에 보탬이 될 수 있다."
  - "Claude is good at optimization, but often makes decisions that are hard to evaluate, especially in large complex systems."
    → "Claude는 최적화를 잘하지만, 특히 크고 복잡한 시스템에서는 평가하기 어려운 결정을 자주 내린다."
  - "This research post is meant to share intermediate progress, and not a completed research agenda. We are sharing this explicitly with the goal that others look at what we have done, take it, and improve it."
    → "이 글은 완성된 연구가 아니라 중간 진척을 공유하려는 것이다. 다른 사람들이 보고, 가져가서, 개선하라는 목적으로 공개한다."
- **맥락**: Amodei의 'pacing' 예고(10/20~21)와 Mythos 5 정렬 실패 보고(10/23) 이후, "속도 조절을 어떻게 검증하나"라는 질문에 대한 첫 기술적 답. S-1/A와 같은 날 공개.
- **변화**: pacing 논의가 선언에서 **검증 인프라**(누가 어떤 모델을 돌렸는지 증명) 단계로 이동.
- **인사이트**: 모델 바꿔치기 방지는 상용 신뢰 문제이자 규제 집행 문제. "Claude가 암호 시스템을 개선했고, 그래서 Lean 형식 검증으로 사람이 감사할 수 있게 했다"는 구조 자체가 S-1의 "AI가 AI를 만든다 + 인간 감독 유지" 서사의 축소판이다.

#### 1-3. Addy Osmani(Anthropic) — Claude Code 게임 복제 차단 확인 (X, 11/3 보도)
- **형식/URL**: X 게시물(원문 미열람) / [The Decoder (11/3)](https://the-decoder.com/anthropic-cracks-down-on-game-cloning-in-claude-code-after-wave-of-ai-built-knockoffs/) — ✅ 2차. (게시 정확 일자는 미확인; 규칙은 "며칠 전부터" 적용)
- **내용**: Opus 5.5용 Claude Code 시스템 프롬프트의 두 문장이 남의 게임 복제를 막는다고 확인. 지식재산 침해에 Claude를 쓰는 것은 사용 정책 위반이며 규칙을 계속 조정할 계획. Halo·GTA Vice City 비공식 브라우저 포트 등이 Opus 5.5·GPT-6 Astra로 대량 제작된 데 따른 조치. 일부 사용자는 독창 프로젝트에도 차단이 걸린다고 호소.
- **직접 인용**: Decoder 기사에 Osmani의 원문 직접 인용 없음(간접 화법) → 인용 생략.
- **인사이트**: 이미지·영상에서 시작된 IP 분쟁이 **소프트웨어 복제**로 번졌고, 연구소가 모델 프롬프트 수준에서 선제 대응. 11/12 시행 예정 Anthropic Usage Policy와 연결해 볼 만함.

#### 1-4. Anthropic 기타(❌ 헤드라인만)
- "Top Anthropic product leader **Cat Wu**, one of the faces of Claude Code, has left the startup"(Business Insider, 11/3). 본문 미확인 — Google News RSS.
- "OpenAI and Anthropic Set Up 'War Rooms' to Fight Disinfo About Midterm Elections"(NYT, 11/3). 본문 미확인. (참고: Anthropic의 선거 대응 글 [2026 US midterms](https://www.anthropic.com/news/2026-us-midterms)은 10/14자로 범위 밖)

#### 1-5. Apple — FY26 Q4 실적 콜, John Ternus CEO 첫 콜 (11/2, 월, 장 마감 후)
- **화자**: John Ternus(CEO), Kevan Parekh(CFO), Sabih Khan(COO) / 실적 콜.
- **URL**: [TechCrunch – iPhone Duo constraints (11/2)](https://techcrunch.com/2026/11/02/apple-says-its-hard-to-predict-when-iphone-duo-constraints-will-improve/) ✅ 2차; [TechCrunch – third-party AI apps (11/2)](https://techcrunch.com/2026/11/02/apple-may-try-to-increase-revenue-by-doing-something-with-third-party-ai-apps/) ✅ 2차; 콜 녹취 원문은 미열람.
- **내용 요약**: 실적은 컨센서스 상회했으나 중국·iPad 부진(Business Insider 헤드라인). 메모리 칩 가격 급등이 핵심 질문. 신제품 폴더블 iPhone Duo는 공급 제약, 가격 인상은 "마지못해(reluctantly)" 결정(Khan). 티타늄 공급사 Perryman과 협력 강화. CFO는 AI가 업그레이드·전환 수요를 만들고, **서드파티 앱·파트너십** 쪽에서도 기회가 있다고 언급(구체 설명 없음; Reuters는 투자자들이 App Store를 통한 서드파티 AI 에이전트 배포·수수료 가능성을 궁금해한다고 보도). 12월 분기 서비스 성장 8~9% 가이던스, 모바일 게임 역풍 지속.
- **직접 인용**
  - Ternus: "We've been thrilled with the early response from reviewers and customers, and we are working hard to get iPhone Duo into customers' hands as quickly as we can."
    → "리뷰어와 고객의 초기 반응에 무척 기쁘며, iPhone Duo를 최대한 빨리 고객 손에 전하려 애쓰고 있다."
  - Khan: "iPhone Duo is constrained as of today. … at this time, it's really hard to predict when supply and demand will be in balance."
    → "iPhone Duo는 현재 공급이 제약된 상태다. … 지금으로선 수요와 공급이 언제 균형을 이룰지 예측하기 정말 어렵다."
  - Parekh: "On the product side, you know, we feel AI offers a compelling reason for customers to upgrade and switch in order to get the latest capabilities, and we also feel there's opportunities across third-party apps and partnerships as well as first-party opportunities."
    → "제품 측면에서 AI는 고객이 최신 기능을 위해 업그레이드하거나 갈아탈 강력한 이유가 된다고 본다. 또 자사 기회뿐 아니라 서드파티 앱과 파트너십 전반에도 기회가 있다고 본다."
- **헤드라인만(❌ 본문 미확인)**: "Apple CEO Ternus Says Memory Price Hikes and Shortages Will Continue Into 2027"(CNET 11/3); "Apple's inventory surges 154% as memory chip costs climb"(TechCrunch 11/2); "Apple CEO John Ternus criticized for 'scripted' approach to first earnings call"(9to5Mac 11/3) / "Apple's Tight-Lipped CEO John Ternus Fails to Inspire"(Bloomberg 11/3) / 반론 "Criticism over Ternus' reading a script during earnings is pathetic"(AppleInsider 11/3); "Apple warns rogue AI agents could 'conceal' and 'manipulate,' causing unintended consequences for its business"(Fortune 11/3 — 연례보고서(10-K) 위험 요인으로 추정되나 미확인); "What Apple CEO John Ternus isn't talking about: 'The biggest risk to the Apple ecosystem'"(Fortune 11/3). 모두 Google News RSS 헤드라인.
- **맥락/변화**: 10/30 Wired 인터뷰의 "AI를 위한 AI는 출시하지 않는다"(10월 보고서) 이후 첫 콜. 콜에서 AI 메시지는 CEO가 아니라 CFO 입으로 "업그레이드 동기 + 서드파티 기회" 수준에 머물렀다. 질문은 AI보다 **메모리 비용(AI 수요가 만든 부품 인플레이션)**에 몰렸다.
- **인사이트**: AI 붐의 '비용 청구서'가 AI를 덜 공격적으로 하는 Apple에도 도착했다. 서드파티 AI 에이전트를 App Store 경제에 편입하는 쪽(플랫폼 수수료형)이 Apple식 AI 수익화 경로가 될 가능성 — 단 아직 경영진의 구체 발언은 없음.
- **기타(✅ 2차)**: Apple은 데이팅 앱·AI 컴패니언 앱을 18세 이상으로 제한(11/3). — [TechCrunch 피드 헤드라인](https://techcrunch.com/2026/11/03/apple-restricts-dating-apps-and-ai-companions-to-users-18-and-up/) (헤드라인 수준, 본문 미열람 ❌)

#### 1-6. Elon Musk — "Grok Bot 비용은 수익 대비 지속 불가능하게 높았다" (X 답글, 11/1 일요일 게시 → 11/2 보도)
- **화자/형식**: Elon Musk(SpaceX CEO; xAI는 SpaceX 'Super Intelligence(SpaceXSI)' 부문으로 편입) / X에서 사용자 질문에 단 답글. 원문(x.com) 차단.
- **URL**: [TechCrunch (11/2)](https://techcrunch.com/2026/11/02/elon-musk-throttles-grok-bot-limits-due-to-unsustainably-high-costs/) ✅ 2차; [The Decoder (11/2)](https://the-decoder.com/spacexsi-apparently-cuts-grok-bot-quotas-weeks-after-musk-called-it-his-fastest-growing-product/) ✅ 2차
- **내용**: 핼러윈 주말 Grok Bot(에이전트형 AI) 주간 사용 한도가 갑자기 소진·축소(Telegraph: 일부 절반으로). Musk는 글리치가 아니라고 확인, 한 사용자에게 "더 큰 구독이 너무 비싸냐"고 되물음. SpaceX 공시상 AI가 회사 수익의 52%, SpaceXSI 부문 4.31억 달러 이익(Cursor 인수 일회성 비용 12억 달러 제외 전). 2주도 안 된 시점에 Musk는 Grok Bot을 "내 인생에서 본 가장 빠르게 성장한 제품"이라 했고, Gwynne Shotwell은 10월 초 주간 유료 사용자 80만 명이라 언급. Grok Bot 한도는 Grok·Cursor와 공유.
- **직접 인용**
  - "The cost of serving Grok Bot was unsustainably high relative to revenue." (TechCrunch 표기; Decoder는 "running"으로 표기 — 단어 차이 주의)
    → "Grok Bot을 서비스하는 비용이 수익에 비해 지속 불가능할 만큼 높았다."
  - (이전 발언, 맥락) "the fastest growth of a product that I've ever seen in my life" → "내 인생에서 본 제품 중 가장 빠른 성장"
- **날짜 주의**: 게시는 11/1(일). 10월 보고서 타임라인에 없고 보도는 11/2이므로 '경계 항목'으로 포함.
- **맥락/변화**: 10/25 Musk의 "네오클라우드 구피 수준 도태" 발언(10월 보고서)처럼 공격적 성장 서사를 펴던 데서, **에이전트 단가 문제를 처음 공개 인정**. Decoder는 OpenAI(12월부터 Codex·Chat 한도 통합, 계정 돌려쓰기 단속)·Anthropic("에이전트는 단순 채팅의 4~15배 비용")도 정액제를 조이는 흐름이라고 정리.
- **인사이트**: '무제한 정액 + 에이전트'는 경제적으로 성립하지 않는다는 업계 공통 신호. Anthropic S-1의 컴퓨트 마진 악화(58%)와 같은 문제의 다른 얼굴.
- **관련(❌ 헤드라인만)**: Musk의 Altman 'RAM' 발언 조롱 — "'The people deserve to have their RAM too!'"(Tom's Hardware·TechRadar·Yahoo Finance 11/2~3). Altman이 "가정용 PC가 RAM을 가진 것은 끔찍하다(terrible)"는 취지로 말했다는 보도(PCWorld 11/2 "Sam Altman says your PC's memory should belong to him")가 발단. Altman 원 발언의 매체·문맥·정확한 문구는 **확인 못 함**. 인용 시 "The people deserve to have their RAM too!"(→ "사람들도 자기 RAM을 가질 자격이 있다!")는 다수 헤드라인에 동일 문구로 등장하나 원문 미확인.

#### 1-7. OpenAI — 국가안보 자문 Dan Driscoll 영입, Altman 코멘트 (11/2 월 발표)
- **화자**: Dan Driscoll(전 제26대 육군장관, 신설 'Senior Counselor for National Security Modernization'), Sam Altman(CEO) / OpenAI 발표 성명.
- **URL**: [The Next Web (11/3)](https://thenextweb.com/news/openai-dan-driscoll-army-secretary-national-security) ✅ 2차 ("the company said on Monday"); [The Decoder (11/3)](https://the-decoder.com/openai-hires-ex-army-secretary-gaining-bipartisan-reach-just-as-midterms-loom/) ✅ 2차
- **내용**: 동맹국의 책임 있는 AI 도입, 국가·사이버 안보 강화 자문. OpenAI의 동맹국 사이버 회복력 프로그램 'Daybreak'(우크라이나 개방, 미국 유틸리티에 제안) 연장선. Driscoll은 9월 Hegseth 국방장관과의 갈등 끝에 사임, JD Vance 부통령의 로스쿨 동기(WSJ). 2월 OpenAI의 국방부 기밀망 배치 계약, Anthropic은 "공급망 위험" 지정 후 소송 중.
- **직접 인용**
  - Altman: "The US has an extraordinary opportunity to work with other countries to spread the adoption of democratic AI."
    → "미국에는 다른 나라들과 함께 민주적 AI의 도입을 확산할 엄청난 기회가 있다."
  - Driscoll: "National security requirements are changing faster than at any time in the past fifty years."
    → "국가안보 요구 사항은 지난 50년 중 어느 때보다 빠르게 바뀌고 있다."
- **맥락**: 중간선거 직전 초당적 인맥 확보(Decoder 해석). 10월 보고서의 Lehane 'speed limits' PR 구상과 함께 **선거 후 워싱턴 대비** 패키지로 읽힘.

#### 1-8. OpenAI — Lehane의 선거 후 로비 구상: 추가된 디테일 (11/2 Decoder, Axios 인용)
- **URL**: [The Decoder (11/2)](https://the-decoder.com/openai-prepares-lobbying-blitz-for-a-post-midterm-washington/) — ✅ 2차(Axios 재인용)
- **새로 추가된 점(10월 보고서 11/1 항목 대비)**: Lehane가 "새 의회에서 최우선 과제는 프런티어 모델 안전 규칙의 신속 입법"이라고 밝힘. 핵심 메시지는 "AI는 사람을 대체하지 않는다". 데이터센터 반발 대응으로 시설을 **"AI Compute Campuses"**로 재명명하고 지역 경제 혜택 약속(TechCrunch 11/1 헤드라인 "OpenAI might rebrand its data centers as 'AI compute campuses'"). 민주당 하원 장악 시 더 험난한 싸움 대비.
- **인용**: "speed limits"(→ "속도 제한") — Lehane의 표현(이미 10월 보고서에 수록).
- **인사이트**: '안전 규칙을 먼저 제안하는 쪽이 규칙을 설계한다'는 전략. Anthropic의 provable inference가 '속도 제한'의 검증 수단을 기술로 제시한 것과 같은 주에 나옴.

#### 1-9. OpenAI — 보안 강화: 버그 바운티 4배, 보안 스프린트 (11/3)
- **URL**: [The Decoder (11/3)](https://the-decoder.com/bug-hunters-can-now-earn-up-to-172000-from-openai-as-company-ramps-up-security/) ✅ 2차; 원문 제목 "Preparing our next security sprint to harden OpenAI"(openai.com, 11/3, Google News 헤드라인 — 원문 차단 ❌)
- **내용**: ChatGPT·Codex 핵심 제품 치명적 취약점 최대 3만 달러, 예외적 발견 최대 10만 달러, 보너스 포함 약 17.2만 달러. 5단계 로열티, 기간 한정 캠페인, 최근 30일 신고자 소급 차액 지급. 보안업체 Cathedral과 내부 엔지니어가 함께하는 스프린트 예고 — 지난 스프린트엔 제품 엔지니어 25% 투입.
- **맥락(❌ 헤드라인)**: "Delaware DOJ launches probe of OpenAI following Hugging Face hack"(Spotlight Delaware 11/2), "OpenAI Hires DOGE Alumni Who Hacked Into Anthropic to Strengthen Security"(Gizmodo 11/3). 본문 미확인.

#### 1-10. OpenAI — GPT-6 Astra가 하드웨어 기기를 일주일 안에 설계 (11/3)
- **URL**: [The Decoder (11/3)](https://the-decoder.com/openai-says-gpt-6-astra-designed-a-hardware-device-from-scratch-in-under-a-week/) ✅ 2차 (OpenAI 자체 주장, 독립 검증 없음)
- **내용**: OpenAI 하드웨어팀이 Codex 코딩 에이전트와 대화하는 기기를 GPT-6 Astra로 부업 삼아 1주 안에 설계(외장·PCB 레이아웃·부품 선정·배선·펌웨어·UI). 위탁 제조로 한 달 안에 시제품. 다만 제조 제약·공차·조립을 놓쳐 여러 차례 수정 필요. 미공개 "내부 모델"이 BenchCAD 2.0에서 0.875(GPT-6 Astra 최고 추론 0.594). 하드웨어팀의 토큰 사용 2월 이후 23배.
- **인사이트**: Anthropic S-1 "Claude 칩 설계 능력"(The Information 헤드라인)과 같은 주에 OpenAI도 '물리 설계' 능력을 홍보 — 코딩 다음 전장이 CAD·하드웨어임을 보여 줌. 단 둘 다 자사 주장.

#### 1-11. OpenAI — 기타 발표(❌ 헤드라인만, 원문 openai.com 차단)
- "OpenAI appoints **Jill Hazelbaker** as Chief Corporate Affairs Officer"(openai.com, 11/3).
- "OpenAI Launches **Grid Protectors** Program With 1 GW Georgia Pledge"(Dataconomy 11/3) — 데이터센터 전력망 수요 완화 프로그램.
- "OpenAI Launches **LifeVal** to Measure Personal Assistant Capabilities"(AIBase 11/3).
- "OpenAI is finally merging ChatGPT's **Chat and Work tabs**"(TechCrunch 11/2) — Decoder(11/1)는 이를 "무제한 프롬프트 요금제의 종말 신호"로 해석(범위 직전).
- "Election 2026: OpenAI launches election war room"(KIRO 7 11/3).
- Altman 자택 총격 보도(ABC 11/2 "home struck by gunfire, days after Molotov cocktail attack") — 발언 아님, 맥락용.

#### 1-12. Sam Altman — UAE 방문: ADNOC·G42 계약, "AI가 최고 과학자보다 똑똑해졌다" (11/2)
- **형식/장소**: 아부다비 방문 중 공개 발언(행사명 미확인) / 계약 서명.
- **근거**: 전부 Google News 헤드라인 → **❌ 미확인(본문 미열람)**. 다수 매체가 같은 취지를 보도하므로 존재 자체는 신빙성 높으나 정확한 문구·맥락 검증 불가.
  - "Abu Dhabi's ADNOC, G42 sign deal with OpenAI as Sam Altman travels to UAE"(Reuters 11/2), "OpenAI's Altman Signs Energy, Investment Deals in the UAE"(Bloomberg 11/2)
  - "AI models smarter than brightest scientists: OpenAI's Altman"(Daily Sabah 11/2), "Sam Altman Crows That AI Is Now Smarter Than the Brightest Human Scientists"(Futurism 11/3), "Altman says AI is already outpacing top scientists in many tasks"(ET CIO 11/3)
  - "'No room for debate' over human control of AI, says Sam Altman"(The National 11/2)
  - "Altman calls UAE the world's most forward-looking country in AI adoption"(Fast Company ME 11/3)
  - "Altman Says AI Can Handle Parts of White-Collar Jobs as Capabilities Grow"(TokenPost 11/2)
  - X에 돌던 발언 클립 문구(Google News 제목에 노출): "At the start of this year, AI was mostly not as smart as our smartest scientists, and now it's mostly smarter than them."
    → "올해 초만 해도 AI는 대체로 우리 최고 과학자들만큼 똑똑하지 않았는데, 지금은 대체로 그들보다 똑똑하다." (❌ 원문·영상 미확인, 인용 시 반드시 '보도에 따르면' 처리)
- **같은 주 CNBC 헤드라인**: "Sam Altman makes surprise South Korea visit as OpenAI builds on chip partnerships"(11/2) — 10월 보고서의 10/31 방한(삼성 사장단)과 같은 방문을 다룬 기사로 보임(중복 가능성).
- **기타**: "Sam Altman says OpenAI bet the company on unreleased GPT-4 and a 5% retention rate"(BigGo 11/3) — 출처 인터뷰 미상, ❌.
- **변화(잠정)**: 10/29 Cheeky Pint의 "약간 초인적 AI 1조 개"에서 한 걸음 더 나가 "이미 최고 과학자보다 대체로 똑똑하다"는 **현재형 주장**. 동시에 "인간 통제엔 이론의 여지가 없다"는 프레이밍을 같이 내놓음(헤드라인 기준).

#### 1-13. Mustafa Suleyman(Microsoft AI CEO) — "의식 있는 기계를 만들려 하지 말라" (11/1~11/2 보도)
- **근거**: 헤드라인만 → **❌ 미확인**. "Microsoft AI chief says AI is not conscious and we should keep it that way"(Business Insider 11/1), "Microsoft AI CEO warns industry against trying to build conscious machines"(LA Times 11/2, 지역지 다수 동일 제목 → AP 등 통신 기사로 추정), "…calls for pause if signs emerge"(People Matters 11/2), "Microsoft AI chief Mustafa Suleyman says Anthropic is building a fake soul"(Startup Fortune 11/3), "warns against conscious AI and model welfare"(ETIH 11/3).
- **맥락**: 2025년 8월 'Seemingly Conscious AI' 에세이, 9월 'model welfare' 비판의 연장(WebSearch로 확인한 2025년 자료: [TNW – "We must not sleepwalk"](https://thenextweb.com/news/suleyman-anthropic-claude-consciousness-sleepwalk)). 이번엔 "징후가 보이면 멈춰야 한다(pause)"는 요구가 헤드라인상 새로움. 형식(인터뷰/에세이/연설)과 게시일(11/1인지 11/2인지) 미확인.
- **인사이트(잠정)**: Microsoft는 Nadella의 "모델은 내부자 위험"(10/10) 노선에 Suleyman의 "의식 흉내 금지"를 더해 **Anthropic의 모델 복지·'영혼' 담론과 정면 대립** 구도를 유지.

#### 1-14. Satya Nadella — "'초지능' 용어 옹호, AI 보안 위험 경고" (11/3 보도)
- **근거**: "Microsoft CEO defends 'superintelligence' term, warns of AI security risks"(The American Bazaar 11/3), "Satya Nadella | BG2 w/ Bill Gurley & Brad Gerstner"(BigGo 11/2 목록) — **❌ 미확인**. BG2 팟캐스트 출연이 출처일 가능성이 있으나 공개일·발언 확인 못 함. Times of India(11/1) "Nadella says that when Dario Amodei, Ilya Sutskever, Sam Altman, Greg Brockman and El[on]…" — 범위 밖 날짜, 내용 미확인.
- Microsoft IR "FY27 Q1 – Press Releases"(11/4 갱신 표시) — 10/28 콜 관련, 새 발언 아님으로 판단.

#### 1-15. Sundar Pichai(Google) — Brockman의 '인터페이스 없는 AI'에 부분 반대 / 우주 첫 AI 프롬프트 (11/2~3 보도)
- **근거(❌ 헤드라인만)**: "Google CEO Sundar Pichai does not fully agree with OpenAI co-founder Greg Brockman on future of AI interf[aces]"(Times of India 11/3), "Pichai questions Greg Brockman's interface-free AI idea, favors screens"(NewsBytes 11/3). 어느 인터뷰·행사인지 미확인.
- "Google runs its first AI prompt in space and gets a poem back; CEO Sundar Pichai says: We've now successf[ully]…"(Times of India 11/2) / TechCrunch 사이드바 "Google's first data center satellite is online and writing poetry". Pichai의 X 게시물로 추정, 문구 미완 → ❌.
- **거버넌스 압박(발언 아님, 맥락)**: 상원의원 2명이 교실 AI 관련 9개 질문 서한(TOI 11/2); Google은 K-12 학생 대상 Gemini를 학교가 옵트인하지 않으면 끈다(TechCrunch·TNW 11/3, 헤드라인); Alphabet 주주가 Pichai 등 13명을 Lyria 저작권 학습 문제로 제소(MBW 11/2); "Google walkout organizers vow to 'not let up' following CEO's response"(Mashable 11/3) — Pichai가 직원 시위에 응답한 것으로 보이나 내용 미확인.
- DeepMind/Hassabis: 이 기간 새 발언 **찾지 못함**.

#### 1-16. Meta — 대규모 회사채(150억~250억 달러) 발행 (11/3), 경영진 발언 없음
- "Meta raises $15 billion in five-part US bond sale"(Reuters 11/3), "Meta pays up to borrow $15B as investors grow wary of AI debt"([TNW 11/3](https://thenextweb.com/news/meta-15b-bond-sale-higher-yields-euro-debut), 헤드라인). Zuckerberg·Alexandr Wang 등의 **새 발언은 찾지 못함**. 맥락: 10/21 콜의 "스케일링으로 초지능" 투자 자금 조달.

#### 1-17. Mistral — Arthur Mensch: "프런티어 AI 없으면 유럽은 '완전한 함정'" (Politico Europe, 11/2)
- **근거(❌ 헤드라인만)**: "Mistral CEO: Europe faces 'complete trap' without frontier AI"(POLITICO.eu 11/2), "Mistral AI chief warns of US, Chinese AI export controls"(Yahoo 11/2), 후속 "Is Europe in a 'complete trap' without frontier AI?"(Techzine 11/3). 맥락: 아일랜드 더블린 EU 비공식 정상회의에서 AI 주권·안전 논의 예정(11/3 보도).
- 인용 후보: "complete trap"(→ "완전한 함정") — 헤드라인의 따옴표 표현, 원문 문장 미확인.
- 모델: Decoder 사이드바에 Mistral "Le Chonk"(코딩 모델, "여전히 중국에 뒤처짐"), Quartz 11/3 "Mistral launches open-weight AI model ML4" — Large 4 가중치 공개(10/29, 10월 보고서 수록)와 같은 건인지 확인 못 함 ❌.
- **변화(잠정)**: 10/6 "유럽이 경쟁할 수 없다는 건 사실이 아니다"(낙관)에서 "프런티어 없으면 함정"(경고)로 수사가 날카로워짐. 미·중 수출 통제 우려를 함께 제기.

#### 1-18. 그 밖의 인물·회사
- **Andrej Karpathy(Anthropic)**: Claude(Opus 5.5)로 HN 추천 영상 6,454개를 모은 'HackerTube'를 두 시간 만에 제작(X, 11/1 게시 추정 → 11/1~3 다수 보도). 범위 경계(11/1), ❌ 원문 미확인.
- **Aravind Srinivas(Perplexity)**: "Perplexity CEO Aravind Srinivas at Money20-20 USA – We're Your Life's CFO"(Yahoo Finance 11/3) — 10월 보고서의 10/27 Money20/20 인터뷰 영상의 재게시로 보임(중복 가능) ❌.
- **Amazon/AWS**: 이 기간 새 경영진 발언 없음. "Jassy: AWS 5~10년 내 연 1조 달러 매출"(디지털투데이 11/1 등)은 10/29 콜 발언의 후속 보도. **Kimi/Qwen의 Bedrock 신규 출시는 이 기간 확인 못 함**(Kimi K3 Bedrock 출시는 9/18, AWS 블로그). Bedrock 'Priority +75%, Flex −50%' 요금 티어 보도(shattered.io 11/3)는 출처 신뢰도 낮음 ❌.
- **xAI/SpaceX 기타**: 미시시피 데이터센터에 개조 제트엔진 8기 설치(Tom's Hardware 11/3), NAACP 대기오염 소송 기각 신청 패소(10/31~11/2) — 발언 아님. Musk "vote red", 중간선거에 4.46억 달러(American Bazaar 11/3) ❌.
- **SSI(Ilya Sutskever), Thinking Machines(Mira Murati)**: 이 기간 새 발언·발표 **찾지 못함**.
- **Yann LeCun(AMI Labs, 범위 외 참고)**: 109M 파라미터 JEPA가 72B Qwen보다 시각-언어 정렬이 낫다는 논문(11/1~3 보도), "Silicon Valley is 'completely hypnotized by LLMs'"(Dealroom 11/3) ❌.

### Inferences
- **'AI가 AI를 만든다'가 공식 문서 언어가 됐다**: Anthropic은 S-1(법적 공시), OpenAI는 GPT-6 Astra 하드웨어 설계 사례, Altman은 "최고 과학자보다 똑똑하다"(헤드라인)로 같은 주에 같은 방향의 주장을 냈다. 차이는 Anthropic이 이를 위험 요인으로, OpenAI는 능력 홍보로 프레이밍했다는 점.
- **pacing 논쟁의 축이 '선언 → 검증 장치'로 이동**: Anthropic의 provable inference는 "어떤 모델이 돌았는지"를 증명해 속도 제한·평가 결과를 검증 가능하게 한다. OpenAI Lehane의 'speed limits' 입법 우선 과제와 맞물리면, 2027년 의회 논의에서 "검증 가능한 속도 제한"이 핵심 쟁점이 될 수 있다(추론).
- **에이전트의 단위 경제가 깨지고 있다는 공개 인정이 이어진다**: Musk(Grok Bot "지속 불가능"), Anthropic(컴퓨트/매출 58%, 단기 컴퓨트 프리미엄), OpenAI(정액 한도 통합 — Decoder 보도). 무제한 정액제 → 사용량·티어 과금으로의 전환이 업계 공통 흐름.
- **AI 비용이 비(非)AI 기업에 전가**: Apple 콜의 핵심 질문이 AI 기능이 아니라 AI 수요발 메모리 가격이었다. Ternus의 '조용한 AI' 노선은 비용 측면에선 오히려 피해자 포지션.
- **선거 주간의 '워싱턴 대비'**: OpenAI(Driscoll·Hazelbaker 영입, war room, Lehane 로비), Anthropic(war room 헤드라인) 모두 11/3 중간선거를 기점으로 정책 인력을 재배치. Warren 의원 서한(11/3 기한)에 대한 공개 답변은 확인되지 않았다.

### Gaps
- **Ternus 첫 콜의 AI 관련 직접 발언**: 녹취(Apple IR·Fortune·Yahoo 전사본) 접근 실패. Ternus 본인의 AI 언급, 메모리 가격 "2027년까지 지속" 발언 문구(CNET 헤드라인)는 미확인.
- **Altman UAE 발언의 원문·행사명**: 헤드라인만 확인. "smarter than our smartest scientists" 문구는 X 클립 제목으로만 확인.
- **Altman 'RAM' 발언의 출처(매체·일시·정확한 문구)**: 미확인. Musk의 반박 문구도 헤드라인 수준.
- **Suleyman 11/1~2 발언의 형식·원문**, **Nadella 'superintelligence' 옹호 발언의 출처(BG2 여부)**, **Pichai–Brockman 인터페이스 논쟁의 출처**: 모두 헤드라인만.
- **Warren 의원 서한(11/3 기한) 답변**: Anthropic·OpenAI 어느 쪽의 공개 답변도 찾지 못함(Benzinga 10/31 "Warren Slams Trump's Voluntary AI Safety Deal With Tech CEOs"만 확인, 범위 밖).
- **Kimi/Qwen on Bedrock 신규 발표**: 11/2~4 기간 내 확인 못 함. 11/4 Kimi K3.1 Pro 가중치 공개(10월 보고서 관전 포인트)도 이 시점 미확인.
- **Cat Wu 퇴사 배경**, **Anthropic·OpenAI 선거 war room 내용**: 헤드라인만.
- **11/4(수) 당일 발언**: 작성 시점(UTC 11/4 새벽)상 거의 반영 못 함. 예: TechCrunch Founder Summit(11/4 보스턴) 연사 발언 등.
- **sec.gov S-1/A 원문**을 직접 열지 못해, 위험 요인 문구는 TechCrunch 인용에 의존.

---

## Q2. 날짜순 요약 타임라인 (보고서 부록용)

### Takeaway
11/2(월)에 핵심 문서·콜이 몰렸고(Anthropic S-1/A·FlashProve, Apple 콜, OpenAI Driscoll 영입, Altman UAE), 11/3(화, 선거일)에는 OpenAI 보안·하드웨어 홍보와 Anthropic 재무 분석이 이어졌다.

### Cited Findings

| 날짜 | 화자 | 소속 | 형식 | 한 줄 요지 | 검증 |
|---|---|---|---|---|---|
| 11/1(일) 게시·11/2 보도 | Elon Musk | SpaceX(SpaceXSI) | X 답글 | Grok Bot 비용 "수익 대비 지속 불가능하게 높다", 한도 축소 | ✅ 2차 ([TC](https://techcrunch.com/2026/11/02/elon-musk-throttles-grok-bot-limits-due-to-unsustainably-high-costs/)) |
| 11/1~2 | Mustafa Suleyman | Microsoft AI | (형식 미확인) | 의식 있는 AI 만들지 말라, 징후 보이면 멈춰야 | ❌ (헤드라인) |
| 11/2 | Anthropic | Anthropic | S-1/A | RSI 기준 "곧" 충족 가능, 과거 가속을 놓친 적 있음, Q3 매출 170억 달러·컴퓨트 58% | ✅ 2차 ([TC](https://techcrunch.com/2026/11/02/anthropic-warns-that-its-very-close-to-rsi-capability-aka-self-building-ai/)) |
| 11/2 | Rinberg·Allain 외 | Anthropic | 연구 글·코드 | FlashProve: 모델 신원 암호 증명, pacing 준수 검증 도구 | ✅ 원문 ([Anthropic](https://www.anthropic.com/research/provable-inference)) |
| 11/2 | John Ternus·Kevan Parekh·Sabih Khan | Apple | FY26 Q4 콜 | Duo 공급 제약 "예측 어렵다", AI는 업그레이드 동기 + 서드파티 기회 | ✅ 2차 ([TC](https://techcrunch.com/2026/11/02/apple-says-its-hard-to-predict-when-iphone-duo-constraints-will-improve/)) |
| 11/2 | Sam Altman·Dan Driscoll | OpenAI | 발표 성명 | "민주적 AI 확산의 엄청난 기회", 국가안보 자문 신설 | ✅ 2차 ([TNW](https://thenextweb.com/news/openai-dan-driscoll-army-secretary-national-security)) |
| 11/2 | Sam Altman | OpenAI | UAE 방문 발언 | AI가 "대체로 최고 과학자보다 똑똑", 인간 통제엔 "논쟁의 여지 없다", ADNOC·G42 계약 | ❌ (헤드라인) |
| 11/2 (Axios 재인용) | Chris Lehane | OpenAI | 보도 | 새 의회 최우선 = 프런티어 안전 규칙 신속 입법, "AI Compute Campuses" | ✅ 2차 ([Decoder](https://the-decoder.com/openai-prepares-lobbying-blitz-for-a-post-midterm-washington/)) |
| 11/2 | Arthur Mensch | Mistral | Politico Europe | 프런티어 없으면 유럽은 "완전한 함정", 미·중 수출 통제 경고 | ❌ (헤드라인) |
| 11/2~3 | Sam Altman / Elon Musk | OpenAI / SpaceX | (미확인) / X | Altman 'PC RAM은 끔찍' 발언 논란, Musk "사람들도 RAM을 가질 자격" | ❌ (헤드라인) |
| 11/3 (게시일 미확인) | Addy Osmani | Anthropic | X | Claude Code가 남의 게임 복제 차단, IP 침해는 정책 위반 | ✅ 2차 ([Decoder](https://the-decoder.com/anthropic-cracks-down-on-game-cloning-in-claude-code-after-wave-of-ai-built-knockoffs/)) |
| 11/3 | OpenAI | OpenAI | 블로그(보안) | 버그 바운티 4배(최대 약 17.2만 달러), Cathedral과 보안 스프린트 | ✅ 2차 ([Decoder](https://the-decoder.com/bug-hunters-can-now-earn-up-to-172000-from-openai-as-company-ramps-up-security/)) |
| 11/3 | OpenAI | OpenAI | 사례 공개 | GPT-6 Astra가 하드웨어 기기를 1주 안에 설계, 내부 모델 BenchCAD 0.875 | ✅ 2차 ([Decoder](https://the-decoder.com/openai-says-gpt-6-astra-designed-a-hardware-device-from-scratch-in-under-a-week/)) |
| 11/3 | OpenAI | OpenAI | 인사 발표 | Jill Hazelbaker 최고 대외협력책임자 | ❌ (헤드라인) |
| 11/3 | Sundar Pichai | Google | (미확인) | Brockman의 '인터페이스 없는 AI'에 동의 안 해, 화면 선호 | ❌ (헤드라인) |
| 11/3 | Satya Nadella | Microsoft | (BG2 추정) | '초지능' 용어 옹호, AI 보안 위험 경고 | ❌ (헤드라인) |
| 11/3 | Cat Wu | Anthropic | 보도 | Claude Code 제품 리더 퇴사 | ❌ (헤드라인) |

### Inferences
- '✅' 등급 항목은 Anthropic·OpenAI·Musk·Apple에 몰려 있다. Microsoft·Google·Mistral 발언은 이번 주 모두 헤드라인 수준이라, 보고서에 넣을 땐 "보도에 따르면" 처리하거나 관전 포인트로 돌리는 게 안전하다.

### Gaps
- 위 ❌ 항목 전부 원문 확보 필요. 특히 Altman UAE(The National·Daily Sabah), Mensch(Politico.eu), Suleyman(AP/LA Times), Pichai(출처 인터뷰)가 우선순위.
