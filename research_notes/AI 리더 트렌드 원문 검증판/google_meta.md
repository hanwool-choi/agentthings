# Google/Alphabet/DeepMind 및 Meta 리더 공개 발언 — 원문 검증판 (2026-10-02 ~ 2026-11-02)

> **방법·한계 (먼저 읽을 것)**
> - WebFetch는 이번에도 모든 외부 호스트에서 DNS 차단됐다. 대신 프록시 경유 `curl`로 일부 호스트에 접속할 수 있었고, 여기서 1차 원문을 확보했다.
>   - **접근 가능:** blog.google, deepmind.google, about.fb.com, fortune.com(실적 콜 전문 포함), finance.yahoo.com, diginomica.com, techcrunch.com, huggingface.co
>   - **차단:** q4cdn PDF, abc.xyz, investor.atmeta.com, sec.gov, cnbc, benzinga, investing.com, x.com 게시물, youtube, substack, bigtechnology, forbes, wikipedia 등
> - **실적 콜 원문:** Fortune이 공개한 전체 트랜스크립트를 사용했다. 화자 표기가 있는 음성 전사본이다.
>   - Alphabet: https://fortune.com/company/alphabet/earnings/q3-2026/ (2026-10-28 16:30 EDT)
>   - Meta: https://fortune.com/company/facebook/earnings/q3-2026/ (2026-10-21 16:30 EDT)
>   - 회사 IR의 공식 PDF와 한 단어씩 대조하지는 못했다. 다만 Pichai 발언은 Google 공식 블로그의 "edited transcript"와 내용이 일치함을 확인했다.
> - **검증 표기:** ✅검증 = 1차 원문과 일치 / ⚠️수정 = 원문과 다르며 수정값을 적음 / ❌확인불가 = 원문 접근 실패 또는 원문에 없음
> - 기간 밖 자료는 "(맥락)"으로 표시했다.

---

## Q1. 기존 노트(검색 스니펫 기반) 항목별 원문 검증 결과

### Takeaway
기존 노트의 **핵심 숫자(매출·Cloud·capex·FCF·토큰·사용자)는 대부분 원문과 일치**했다. 그러나 화자 귀속과 세부 사항은 여러 곳에서 틀렸다.
- Meta의 "10억 명 이상에게 서비스할 컴퓨팅 구축"과 "비용 효율 10배 이상 개선"은 **Susan Li가 아니라 Zuckerberg**의 발언이다.
- Muse Wonder 출시일은 **10/12**다.
- Gemini 4 Carbon 발표문의 작성자는 **Koray Kavukcuoglu**다.
- Cloud 백로그는 **5,610억 달러**로 원문에 명시되어 있다.
- 콜에서 TPU 고객 100곳 이상을 말한 사람은 Kurian이 맞다. 하지만 별도 인터뷰가 아니라 **실적 콜에 처음 직접 참석해 한 발언**이다.

### Cited Findings

#### [A] LeCun – Fortune 인터뷰 (2026-10-01, 기간 하루 전: 맥락)
- ✅ 기사 날짜는 2026-10-01이다. AMI Labs 직원은 "now 60-some employees", 본사는 파리, 뉴욕·몬트리올·싱가포르에 인력이 있다. JEPA 기반 월드 모델을 만들고 있다 — [Fortune](https://fortune.com/2026/10/01/ai-godfather-yann-lecun-has-zero-concerns-about-human-extinction-says-anthropic-ceo-dario-amodei-is-deuded/)
- ⚠️ **"zero concerns"의 대상 수정:** 원문에서 LeCun이 "zero concerns"라고 한 대상은 **최근 잇따른 rogue AI 사고**(OpenAI 에이전트의 Hugging Face 자율 해킹 등)다. 인류 멸종에 대해서는 "isn't worried 'at all'"이라고 했다.
  - 원문: "Those agents are doing exactly what they've been asked to do… The sandboxes were leaky and horribly designed."
  - 번역: "그 에이전트들은 요청받은 일을 정확히 하고 있을 뿐이다. 샌드박스에 구멍이 있었고 끔찍하게 설계됐다."
  - 출처: [Fortune](https://fortune.com/2026/10/01/ai-godfather-yann-lecun-has-zero-concerns-about-human-extinction-says-anthropic-ceo-dario-amodei-is-deuded/)
- ✅ Amodei에 대해 "I think he's completely deluded"(완전히 망상에 빠졌다고 본다)라고 했고, 이후 "crazy"라고도 불렀다. 동시에 Amodei가 "honest(정직하다)"는 점은 인정했다. 그의 핵심 우려는 **규제 포획(regulatory capture)**이다 — [Fortune](https://fortune.com/2026/10/01/ai-godfather-yann-lecun-has-zero-concerns-about-human-extinction-says-anthropic-ceo-dario-amodei-is-deuded/)
  - 원문: "claiming AI is too dangerous to put in our hands… saying open-source [models] are too dangerous—this is regulatory capture"
  - 번역: "AI가 우리 손에 쥐여 주기엔 너무 위험하다, 오픈소스가 너무 위험하다고 주장하는 것은 규제 포획이다."
- 신규 세부:
  - LeCun은 Meta의 Muse 에이전트를 쓰고 있으며, 이름을 "Hal"이라고 붙였다.
  - 기사는 Trump가 "this week" AI를 "super intelligence"로 부르게 하는 행정명령에 서명했다고 기술했다. 이는 [F] 항목의 배경이다.
  - 출처: [Fortune](https://fortune.com/2026/10/01/ai-godfather-yann-lecun-has-zero-concerns-about-human-extinction-says-anthropic-ceo-dario-amodei-is-deuded/)

#### [A-2] LeCun – La Tribune Événements / "flying trimaran"
- ❌ 원문(La Tribune)과 StartupHub 모두 프록시에서 차단됐다.
- 검색 결과에 따르면 StartupHub 기사는 **2026-10-02** 자 기사다. 요지는 세 가지다.
  - AMI는 출범 약 6개월이며 아직 출시할 제품이 없다.
  - JEPA를 "flying trimaran(날아오르는 삼동선)"에 비유했다.
  - LLM은 행동의 결과를 예측하지 못하므로 진정한 지능이 아니다.
  - 출처: [StartupHub(검색 요약)](https://www.startuphub.ai/ai-news/ai-research/2026/yann-lecun-says-flying-trimarans-will-beat-llms)
- ❌ X 클립 "LLM-pilled… Same hole, different shovels"는 날짜와 원 출처를 검증하지 못했다. 사용하지 말 것.

#### [B] Alexandr Wang 팟캐스트 / Zuckerberg·Wang Cheeky Pint
- ⚠️ **프로그램명 수정:** 기존 노트의 "Founders Podcast"는 정확하지 않다. 검색 결과는 **David Senra 팟캐스트**(Senra는 Founders 진행자) 에피소드 "Creating Muse: The Fastest-Growing AI Product Since ChatGPT"로 나타난다. 날짜는 10/11이다.
  - 출처: [davidsenra.com](https://www.davidsenra.com/episode/alexandr-wang), [YouTube](https://www.youtube.com/watch?v=S6l3aRsecuE), [podscripts](https://podscripts.co/podcasts/david-senra/creating-muse-the-fastest-growing-ai-product-since-chatgpt-alexandr-wang-meta)
  - 원문 페이지는 모두 차단되어 내용은 검색 요약에 근거한다.
  - 요약된 내용: 200명 미만 팀이 약 7개월 만에 Muse를 만들었다. 코딩 경쟁과 파라미터 경쟁을 피하고 소비자 개인 에이전트에 베팅했다. 개인 에이전트를 "razor's edge(칼날 위)" 제품이라고 표현했다 — [Futu](https://news.futunn.com/en/post/1000860791/alexandr-wang-on-building-muse-a-team-of-under-200)
- ❌ Cheeky Pint(10/12) Zuckerberg·Wang 에피소드는 substack이 차단되어 확인하지 못했다.

#### [C] Muse Spark Open 오픈 웨이트 (2026-10-15)
- ✅ Hugging Face 블로그 날짜는 2026-10-15다. 모델 ID는 `meta-models/Muse-Spark-Open-816B-A42B`(총 816B, 활성 42B MoE)이고, 라이선스는 "muse-model-license"다. safetensors 기준 총 파라미터는 약 822B로 표시된다.
  - 출처: [HF 블로그](https://huggingface.co/blog/meta-muse-spark-open), [HF 모델카드](https://huggingface.co/meta-models/Muse-Spark-Open-816B-A42B)
- 검색 요약(PyTorch 블로그, 미열람): 1M 컨텍스트, 텍스트·이미지·비디오·오디오 입력. Meta는 이를 "most capable US open weights model"이라고 부르면서도 "가장 강력한 모델은 대체로 닫아 둘 것"이라고 했다 — [PyTorch(검색)](https://pytorch.org/blog/muse-spark-open/)
- ✅ Zuckerberg는 콜에서 "In the last few months, we've shipped Muse Spark 1.2 and 1.3, Muse Code, two open weights models with Muse Glimmer and Muse Spark Open, and also Muse Voice."라고 했다 — [Meta 콜 전문](https://fortune.com/company/facebook/earnings/q3-2026/)
  - ⚠️ 원문 표현은 "이번 분기"가 아니라 "지난 몇 달"이다. Muse Glimmer는 8월 출시다(맥락: [CNBC 8/10](https://www.cnbc.com/2026/08/10/meta-muse-glimmer-open-weight-ai.html), 미열람).

#### [D] Muse Wonder 출시
- ⚠️ **출시일은 2026-10-12다**(about.fb.com 게시 시각 2026-10-12T17:08 UTC).
  - 시리즈는 **Muse Wonder와 Muse Wonder Full** 두 가지다.
  - 출시 당일 Meta Model API와 Muse Code로 제공됐고, Muse에는 구독자부터 순차 적용된다.
  - 새 기능은 "Active Memory"와 "Active Focus"다.
  - "Meta Superintelligence Scaling Framework" 기준에 따라 출시했다.
  - 출처: [Meta Newsroom](https://about.fb.com/news/2026/10/introducing-muse-wonder-models/)
  - 원문: "Fourteen months ago, we began an overhaul of our AI efforts, and in that time we've gone from rebuilding our foundations to pushing the frontier."
  - 번역: "14개월 전 우리는 AI 노력을 전면 재정비하기 시작했고, 그동안 기반 재건에서 프런티어 개척으로 나아갔다."
  - 원문: "This is a major step toward personal superintelligence for everyone"
  - 번역: "모두를 위한 개인 초지능으로 가는 중대한 한 걸음"
- ✅ 콜에서 Zuckerberg는 "We shipped Muse Wonder as our first frontier model"(우리의 첫 프런티어 모델로 Muse Wonder를 출시했다)라고 했다 — [Meta 콜 전문](https://fortune.com/company/facebook/earnings/q3-2026/)
- ❌ "Anthropic/OpenAI/Google 최상위 모델에 필적" 같은 벤치마크 수치는 원문 뉴스룸에 없다. 연구 블로그(ai.meta.com)는 차단됐다.

#### [E] Meta Q3 2026 실적 콜 (2026-10-21) — 숫자·인용 검증 (출처: [Meta 콜 전문](https://fortune.com/company/facebook/earnings/q3-2026/))

**숫자:**
- ✅ 매출 646억 달러(+26%), 광고 631억 달러(+26%), FoA 기타 매출 11억 달러(+59%), RL 매출 4.43억 달러(-6%)
- ✅ 총비용 516억 달러(+68%), 소송 비용 99억 달러(2026년 8월 다주 법무장관 합의)
- ✅ 영업이익 130억 달러(-37%), 영업이익률 20%. 소송 비용을 제외하면 영업이익은 +11%다.
- ✅ 순이익 99억 달러, EPS 3.83달러, 세율 24%
- ✅ capex 349억 달러(금융리스 원금 포함), FCF -21억 달러, 현금 824억 달러, 부채 837억 달러
- ✅ 2026년 capex 1,350억~1,450억 달러. 원문 표현은 "narrowed from our prior outlook of $130 billion-$145 billion"(기존 전망에서 범위를 좁혔다)이다. 2026년 총비용은 1,750억~1,790억 달러다.
- ⚠️ 영업현금흐름 328억 달러는 원문에 직접 나오지 않는다. capex 349억 달러와 FCF -21억 달러로부터 역산한 값이다(필자 계산과 일치). capex "+80%"도 원문에 없다.
- ❌ 조정 EPS 7.40달러와 컨센서스(3.57달러/5.75달러)는 원문에 없다. 소송 비용 제외 영업이익률 약 35%는 원문에 없고, 계산하면 (130+99)/646 ≈ 35.4%다(추론).
- ✅ 직원 수 원문: "We ended Q3 with over 66,000 employees, down 12% from Q2 following the May 2026 headcount reduction."
- ✅ 외부 AI 토큰 비용 원문(Li): "Year-over-year growth was primarily driven by legal-related costs, infrastructure costs, and third-party AI token costs. The growth in infrastructure costs was driven by higher third-party cloud spend, depreciation, and data center operating costs."
  - 번역: "전년 대비 증가는 주로 법률 비용, 인프라 비용, 외부 AI 토큰 비용 때문이다. 인프라 비용 증가는 외부 클라우드 지출, 감가상각, 데이터센터 운영비 증가에서 왔다."
  - 기존 노트에서 "저품질 출처"로 분류했던 내용이 원문으로 확인됐다.
- ✅ 의결권 없는 신주(Class C, 사실상 2대1 분할, 2027년 1월 말 거래 개시)를 발표했다. TechCrunch는 NYT를 인용해 이 신주가 캘리포니아 억만장자세(Prop 40) 납부용이라는 목적도 있다고 보도했다 — [TechCrunch 10/22](https://techcrunch.com/2026/10/22/mark-zuckerbergs-creative-plan-to-pay-californias-proposed-billionaire-tax-without-losing-control-of-meta/)

**인용·화자 귀속:**
- ✅ "My view is that we will be able to build superintelligence through scaling, so we are methodically working our way up the ladder there." (Zuckerberg)
  - 번역: "내 견해로는 스케일링을 통해 초지능을 만들 수 있다. 그래서 우리는 그 사다리를 체계적으로 한 단계씩 올라가고 있다."
- ⚠️ **화자 수정 (Li → Zuckerberg):** "On the compute side, we are building out the capacity to serve more than 1 billion people over the next few years." 이 문장은 Zuckerberg의 모두 발언이다.
- ⚠️ **화자 수정 (Li → Zuckerberg):** "In the near term, Muse is very compute-intensive to run, but we expect to improve its cost efficiency by more than 10x in the next year, which will enable it to be profitable once the revenue lines are at scale."
  - 번역: "단기적으로 Muse는 운영에 컴퓨팅이 매우 많이 들지만, 내년에 비용 효율을 10배 이상 개선해 매출이 규모를 갖추면 흑자가 가능할 것으로 본다."
  - 같은 내용을 Li도 말했다: "we expect to improve compute cost efficiency by more than tenfold over the next year, driven by better utilization of off-peak capacity, more efficient models, and inference optimization"(비피크 시간대 용량 활용 개선, 더 효율적인 모델, 추론 최적화로 내년 컴퓨팅 비용 효율을 10배 이상 개선할 것으로 예상한다).
- ⚠️ Li의 비용 구조 발언은 "sort of"가 빠진 문장이 원문이다: "We do not have specific numbers to share around the cost structure of Muse today, but of course it is, as Mark said, pretty compute expensive."
- ✅ Muse 사용자 원문: "In just a month and a half, more than 10 million people in the U.S. and Canada have set up Muse personal agents… About 25% of people who have set up Muse use it on any given day."
  - 번역: "불과 한 달 반 만에 미국·캐나다에서 1,000만 명 이상이 Muse 개인 에이전트를 설정했다. 설정한 사람의 약 25%가 매일 사용한다."
- ⚠️ 쇼핑 수치는 기존 노트보다 정확한 원문으로 바꾼다.
  - Zuckerberg: "The most common use case for Muse is shopping, with more than a quarter of people who are using Muse engaging in this with an average purchase size of over $200."(Muse의 가장 흔한 사용 사례는 쇼핑이며, Muse 사용자의 4분의 1 이상이 쇼핑에 쓰고 평균 구매액은 200달러를 넘는다.)
  - Li: 주간 활성 사용자의 25% 이상이 쇼핑에 사용한다.
  - Mahaney 질문에 대한 답: 이 수치에는 여행이 포함된다.
- ❌ "9/8 공개 출시" 날짜는 원문에 없다. 원문은 "a month and a half"(한 달 반)라고만 했다.

#### [F] "Superintelligence" 용어 논란 (CNBC 10/30)
- ❌ CNBC 원문은 차단됐다. 2차 출처에 따르면 CNBC는 Trump가 연방 기관에 "super intelligence" 사용을 지시한 지 약 한 달 뒤 Musk와 Zuckerberg가 실적 콜에서 이 용어를 썼다고 보도했다.
  - 출처: [CNBC(미열람)](https://www.cnbc.com/2026/10/30/trump-tech-allies-swap-ai-for-super-intelligence-in-earnings-calls.html), [Newsweek(검색)](https://www.newsweek.com/which-tech-leaders-adopting-trumps-super-intelligence-rebrand-12555825)
- ✅ 반론 근거는 원문에서 확인된다. Zuckerberg는 콜에서 "it was more than a year ago that I think I wrote the letter about personal superintelligence as the North Star"라고 말했다(1년 넘게 전에 개인 초지능을 북극성으로 삼는 글을 썼다). 행정명령 이전부터 쓰던 용어라는 뜻이다 — [Meta 콜 전문](https://fortune.com/company/facebook/earnings/q3-2026/)
- ✅ 행정명령 시점은 Fortune 10/01 기사의 "signed an executive order this week renaming it 'super intelligence'"(이번 주 AI를 'super intelligence'로 바꿔 부르는 행정명령에 서명했다)라는 문장으로 9월 말임을 교차 확인했다 — [Fortune](https://fortune.com/2026/10/01/ai-godfather-yann-lecun-has-zero-concerns-about-human-extinction-says-anthropic-ceo-dario-amodei-is-deuded/)

#### [G] Alphabet Q3 2026 실적 콜 (2026-10-28) — 검증 (출처: [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/), [Pichai 발언 블로그](https://blog.google/company-news/inside-google/message-ceo/alphabet-earnings-q3-2026/))

**숫자:**
- ✅ 매출 1,276억 달러(+25%), 영업이익 406억 달러(+30%), 영업이익률 31.8%
- ✅ Cloud 매출 307억 달러(+103%), Cloud 영업이익 111억 달러(3배 이상), 영업이익률 23.7%→36.2%
- ✅ capex 514억 달러. 2026년 1,950억~2,050억 달러 유지. 원문 "We continue to expect our CapEx to increase significantly in 2027"(2027년 capex가 상당히 증가할 것으로 계속 예상한다).
- ✅ FCF -91억 달러. 원인은 capex, TPU 시스템 재고 축적, 2018년 EC 벌금 52억 달러 현금 납부다. 영업현금흐름은 423억 달러다.
- ✅ 외부 컴퓨팅(Ashkenazi):
  - "The third-party bridging capacity… came online only at the very end of Q3"(외부 브리징 용량은 3분기 맨 끝에야 가동됐다)
  - "given the supply-constrained environment, we started utilizing third-party compute capacity at the end of Q3 and will ramp usage in Q4. We expect margin headwinds in the near term"(공급 제약 환경 때문에 3분기 말 외부 컴퓨팅 용량을 쓰기 시작했고 4분기에 사용을 늘린다. 단기 마진 역풍을 예상한다)
- ⚠️ **백로그 확정값:** 원문 "Google Cloud's backlog was $561 billion in the third quarter… We expect to recognize just over 55% of the total backlog as revenues over the next 24 months."(3분기 Cloud 백로그는 5,610억 달러이며, 향후 24개월 안에 55%를 조금 넘는 금액을 매출로 인식할 것으로 예상한다). FourWeekMBA의 계산(5,140억+470억)과 일치한다.
- ✅ 토큰 원문: "Our first-party model APIs are now processing nearly 32 billion tokens per minute, 40% more than last quarter and more than four times what we processed a year ago."
- ✅ Gemini 앱 원문: "The Gemini app is now at 1 billion users and is the fastest-growing product in Google's history."
  - ❌ "1년 전 약 6.5억 명"과 "1년간 +3.5억 명"은 콜 원문에 없다. ppc.land 헤드라인에서 나온 값으로 미검증이다.
- ✅ 증류 원문(Pichai, Nowak 질문 답변): "We are working on distilled versions of our Carbon models so that we can deploy it across a billion-user scale efficiently"(Carbon 모델의 증류 버전을 개발 중이며, 10억 명 규모에 효율적으로 배포하기 위해서다)
- ⚠️ 기존 노트의 TPU "Q4 … backlog" 인용은 **두 발언을 이어 붙인 것**이다.
  - Ashkenazi 가이던스: "we expect TPU system sales to continue to scale in Q4, followed by a meaningful revenue ramp in 2027"(TPU 시스템 판매가 4분기에도 확대되고, 2027년에 의미 있는 매출 증가가 뒤따를 것으로 예상한다)
  - Sandler 질문에 대한 Ashkenazi 답변: "once we sign that agreement you'll first see that showing up in our backlog"(계약을 체결하면 그 금액은 먼저 백로그에 나타난다)
- ⚠️ "TPU 수요 강세" 문장 "we are seeing strong demand for our TPU systems across a wide range of customers…"는 Kurian이 아니라 **Pichai의 발언**이다.
- ⚠️ EPS: Yahoo/Benzinga는 EPS 2.12달러(예상 3.02달러), 매출 1,275.8억 달러(예상 1,282억 달러)로 "미스"라고 보도했다 — [Yahoo/Benzinga 10/30](https://finance.yahoo.com/technology/ai/articles/google-search-revenue-growth-slows-100020621.html)
  - 원문 확인: 순이익과 EPS 감소 원인은 "Other income and expenses was negative $8.2 billion, due primarily to unrealized loss from our investment in SpaceX"(기타손익 -82억 달러, 주로 SpaceX 투자의 미실현 손실)다.
  - ❌ "시간외 -10%"는 미검증이다.

#### [H] Gemini 4 Carbon (2026-10-28)
- ⚠️ **발표 블로그 작성자: Koray Kavukcuoglu**(SVP, Google DeepMind & Chief AI Architect, Google). 기존 노트에서 Kavukcuoglu를 "발언 미확인"으로 둔 것은 수정한다 — [Google Blog](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-carbon/)
- ✅ 확인된 사항:
  - AA Intelligence Index **v5.0** 1위(59점)
  - WebDev Arena +89 Elo, 4위(1768)
  - SEC-bench Pro 88.2%, ExploitGym 54.8%, CWE-bench 71.0%
  - 사이버 방어자 일부에게 먼저 제공하고 Fairwind Program으로 확대. 미국 정부의 자발적 사전 출시 테스트에 참여
  - 가격 입력 100만 토큰당 2달러, 출력 10달러, 캐시 입력 95% 할인
  - 출처: [Google Blog](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-carbon/)
- ⚠️ "Claude Opus 5.5를 넘어 1위"라는 비교 대상은 Google 원문에 없다(The Elec 등 2차 해석).
- ❌ "모델 카드 없음"은 원문에서 확인할 수 없었다.
- 신규 안전 지표(원문):
  - Terminal-Bench 4.0 성공적 치팅 0.0%, 치팅 시도 0.4%
  - 내부 라이브 코딩에서 고심각도 misalignment 경보 약 80% 감소
  - 근거 없는 주장 약 2배 감소
  - Gray Swan IPI 공격 성공률 0.0%(Argon은 0.7%)
  - Chrome 팀 보고: 다른 연구소 대형 모델 대비 패치 품질 10배 이상
  - 출처: [Google Blog](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-carbon/)
- ❌ Hassabis X 게시물("Iterating at lightning speed!…")은 x.com이 차단되어 원문을 확인하지 못했다(검색 스니펫만 있음): https://x.com/demishassabis/status/2115489550256746502
- ❌ Forbes 10/30, Platformer는 미열람이다.

#### [H-2] Gemini 4 Argon (맥락 및 기간 내 정식 출시)
- ✅ 9/30에 Fairwind 대상 공개(기간 밖)했다 — [DeepMind](https://deepmind.google/blog/gemini-4-argon-our-next-era-of-frontier-intelligence/)
- ⚠️ **10/13 공개 범위 수정:** "유료 사용자 공개"보다 범위가 넓다. 원문: "now globally available today for developers and enterprises via the API in AI Studio and Gemini platform, for Google AI Ultra subscribers in Google Antigravity, and Google AI Ultra and Pro subscribers in the Gemini app and AI Mode in Search." Vals Index 1위다. 작성자는 Koray Kavukcuoglu다 — [DeepMind/Google 10/13](https://deepmind.google/blog/introducing-gemini-4-argon/)

#### [I] Thomas Kurian
- ⚠️ diginomica(10/29) 기사는 독립 인터뷰가 아니라 **실적 콜 발언 정리**다. Pichai는 콜에서 "I am excited to welcome Thomas to the call"(Thomas를 콜에 맞이하게 되어 기쁘다)라고 소개했다 — [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/)
- ✅/⚠️ TPU 고객 수는 원문 안에서 두 가지로 나온다. 모두 발언은 "Nearly 100 customers use TPUs today"(현재 약 100곳이 TPU를 쓴다), Q&A는 "We have over 100 significant TPU customers who start in our cloud"(자사 클라우드에서 시작한 의미 있는 TPU 고객이 100곳 이상)다. 보고서에서는 "약 100곳"으로 쓰는 것이 안전하다.
- ⚠️ diginomica는 Alphabet 매출 성장률을 "16%"로 썼는데 이는 오류다. 원문은 +25%다 — [diginomica](https://diginomica.com/google-cloud-soars-tpu-focus-comes-fore-ceo-thomas-kurian-sets-out-stall)

### Inferences
- 기존 노트의 숫자 신뢰도는 높았다. 반면 **화자 귀속과 날짜는 스니펫 기반이라 오류가 많았다.** 최종 보고서는 인용마다 이 검증판의 화자를 써야 한다.
- 콜 전사본(Fortune)과 Benzinga/Yahoo 기사 사이에 인용 차이가 있다. Schindler의 AI Mode 발언이 대표적이다(Q2 Gaps 참고). 보고서는 콜 전사본을 우선해야 한다.

### Gaps
- Alphabet과 Meta의 공식 IR PDF(q4cdn)와 SEC 8-K는 차단되어 Fortune 전사본과 대조하지 못했다.
- x.com 게시물(Hassabis, Wang, Woodward)은 모두 원문 미확인이다.

---

## Q2. 기간 내 아이템 카탈로그 (재조사 포함, 날짜순)

### Takeaway
이번 재조사로 기간 내 핵심 이벤트를 새로 확인했다.
- Google: Genie 4(10/27), Argon 정식 출시(10/13), Pichai Big Technology 팟캐스트(10/20), AI Mode 광고 글로벌 확대(10/28), Connected Apps 플랫폼(10/28), 실적 콜의 검색 세부 지표(쿼리 성장 5년래 최고, AI Mode 쿼리 3배 길이, 시각 검색 월 500억 건), "RSI(재귀적 자기개선) 가속" 발언
- Meta: Muse Wonder(10/12), 3.64B 일간 사용자, Meta AI 1인당 참여 2배, Muse의 안경 탑재(11월), Personal Agent Protocol, Meta Enterprise 플랫폼

Jeff Dean, Chris Cox, Nat Friedman의 기간 내 발언은 여전히 찾지 못했다.

### Cited Findings

#### 1) 2026-10-06 — DeepMind, EmbeddingGemma 2 (오픈 경량 멀티모달 임베딩)
- 형식: DeepMind 블로그. RSS 제목과 날짜만 확인했다 — [DeepMind](https://deepmind.google/blog/embeddinggemma-2-an-open-lightweight-multimodal-embedding-model/)

#### 2) 2026-10-07 — Santosh Janardhan(Meta 인프라 총괄) 데이터센터 영상
- 형식: Meta 뉴스룸 영상. 크리에이터 Tom Shaw와 대담했다.
- 주제: 기가와트 단위 전력, 칩 선택, 자체 데이터센터의 이점. 같은 달 "debunking the biggest data center myths" 게시물도 올라왔다 — [Meta Newsroom](https://about.fb.com/news/2026/10/meta-data-centers-ai-approach/)
- ❌ Hyperion/Prometheus 진척 수치는 이 게시물과 콜 원문 어디에도 없다.

#### 3) 2026-10-11 — Josh Woodward(VP, Google Labs·Gemini 앱·AI Studio), Lenny's Podcast
- 제목: "Why every company now needs to think and operate like a lab team"
- 주제: 랩 방식 조직 운영, 아이디어를 접을 시점, 개인 비서 비전
- ❌ 원문 미열람(유료이며 차단). 출처: [Lenny's Newsletter](https://www.lennysnewsletter.com/p/why-every-company-now-needs-to-think), [Apple Podcasts](https://podcasts.apple.com/us/podcast/why-every-company-now-needs-to-think-and-operate-like/id1627920305?i=1000795263758)

#### 4) 2026-10-11 — Alexandr Wang(Meta Chief AI Officer), David Senra 팟캐스트
- 위 [B] 참고. ❌ 원문 미열람.

#### 5) 2026-10-12 — Meta, Muse Wonder / Muse Wonder Full 출시
- 위 [D] 참고. ✅ — [Meta Newsroom](https://about.fb.com/news/2026/10/introducing-muse-wonder-models/)

#### 6) 2026-10-13 — Gemini 4 Argon 정식 출시 + Argon for Robotics + Argon 안전 보고
- 화자: Koray Kavukcuoglu(블로그 작성자)
- 핵심 포인트:
  - Antigravity에서 Argon을 쓴 팀은 에이전트 코드 제출이 35% 넘게 늘고 롤백이 약 3분의 1 줄었다.
  - Chrome의 약 600만 줄 레거시 분리 작업을 몇 달에서 몇 주로 단축했다.
  - Gemma 4 E2B 추론을 2.85배 가속했다.
  - 가격은 입력 2달러, 출력 10달러다.
- 출처: [DeepMind 10/13](https://deepmind.google/blog/introducing-gemini-4-argon/), [Argon for Robotics](https://deepmind.google/blog/gemini-4-argon-for-robotics/), [Argon 안전](https://deepmind.google/blog/developing-gemini-4-argon-responsibly-and-safely/)

#### 7) 2026-10-14 / 10-15 — DeepMind 기타 발표
- 싱가포르 정부와 온디바이스 사기 탐지 모델 협력(10/14)
- Antigravity로 항균 펩타이드 탐색(10/15)
- RSS 제목만 확인 — [DeepMind 10/14](https://deepmind.google/blog/on-device-ai-scam-detection-mddi/), [DeepMind 10/15](https://deepmind.google/blog/accelerating-antimicrobial-discovery/)

#### 8) 2026-10-15 — Meta, Muse Spark Open 오픈 웨이트
- 위 [C] 참고. ✅

#### 9) 2026-10-20 — Sundar Pichai, Big Technology Podcast(진행 Alex Kantrowitz)
- ❌ 원문(bigtechnology.com, YouTube, Apple)은 모두 차단됐다. 검색 요약에 따른 내용:
  - 2027년분 컴퓨팅 요청을 지금 받으면 "incredibly difficult(대단히 어렵다)". 현재 용량은 2024년 약정을 반영한 것이다.
  - Argon을 서비스하는 데도 여전히 용량이 제약된다.
  - Argon은 첫 72시간 동안 Gemini 3의 3배 토큰을 처리했다.
  - 출처: [Big Technology](https://www.bigtechnology.com/p/sundar-pichai-googles-frontier-imperative), [Scuttlebutt 요약](https://getscuttlebutt.substack.com/p/sundar-pichai-a-2027-compute-request)
- ✅ 간접 검증: 10/28 콜에서 JPMorgan Anmuth가 "on a recent podcast, you said that 2027 could be the golden age of productivity for Google"(최근 팟캐스트에서 2027년이 Google 생산성의 황금기가 될 수 있다고 하셨는데)라고 질문했다. Pichai는 이를 받아 "a golden year ahead(앞으로의 황금의 해)"라고 재확인했다 — [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/)

#### 10) 2026-10-21 — Meta Q3 실적 콜 (Zuckerberg, Li) — 신규 포인트 (출처: [Meta 콜 전문](https://fortune.com/company/facebook/earnings/q3-2026/), [Yahoo/GuruFocus 요약](https://finance.yahoo.com/markets/stocks/articles/meta-platforms-inc-meta-q3-230130937.html))

**요약:** Zuckerberg는 Muse가 "clear product market fit(명확한 제품-시장 적합성)"을 얻었다고 판단했다. 이제 "scale the product, grow revenue, and optimize compute costs(제품 확장, 매출 성장, 컴퓨팅 비용 최적화)"라는 운영 단계에 들어간다고 선언했다. 그 외 포인트:
- 수익화는 평소 플레이북보다 이르게 시작한다.
- Meta Enterprise 플랫폼(CJ Desai 총괄)으로 고마진 추론 수요를 흡수한다.
- Reality Labs도 개인 초지능에 집중한다.

**핵심 포인트 (원문 기반):**
- Family of Apps 일간 사용자는 3.64B다. Threads가 월간 활성에서 X를 추월했다. WhatsApp은 "becoming an increasingly important platform for agents(에이전트를 위한 플랫폼으로 점점 중요해지고 있다)"고 했다.
- "engagement per person in Meta AI has more than doubled since April when we started rolling out our new models"(새 모델을 내놓기 시작한 4월 이후 Meta AI의 1인당 참여가 2배 이상 늘었다). ❌ Meta AI MAU 수치는 공개하지 않았다.
- Muse Wonder 적용 후 품질, 참여, 유지율이 개선됐다. 무료 등급 기본 모델은 Muse Spark이고, Wonder는 유료 등급에서 제공한다. Wonder의 효율 버전을 개발 중이다.
- 출시 예고: "Muse is coming to Meta Glasses starting next month"(다음 달부터 Meta 안경에 Muse 탑재), Muse confidential VM("even Meta cannot see your content", Meta도 사용자 콘텐츠를 볼 수 없음), Muse Charm(1년 안에 컨셉에서 주머니 속 기기까지 간 하드웨어).
- Reality Labs: 2026년 손실 180억~190억 달러, 2027년 약 150억 달러로 축소 예상, VR은 "major breakthroughs(중대한 돌파구)"가 있을 때만 신제품을 낸다.
- 효율 전망 원문: "I just expect that we will be able to deliver the same intelligence that we have now in Muse Wonder or frankly, any of the current frontier models at a fraction of the cost in a smaller model a year from today."
  - 번역: "지금 Muse Wonder, 솔직히 말해 현재 어떤 프런티어 모델이 가진 것과 같은 지능을 1년 뒤에는 더 작은 모델로 몇 분의 1 비용에 제공할 수 있을 것으로 본다."
- 내부 적용: Muse Wonder로 추천·광고 시스템을 자율적으로 개선하는 평가(eval)를 구축했다. 콘텐츠 이해 모델을 Muse 계열로 옮겨 처리 단가를 80% 넘게 줄였다(Li).
- 광고 지표:
  - 노출 +10%, 광고 단가 +14%
  - 파트너십 광고 연환산 150억 달러 돌파(+97%)
  - Meta One 구독·체험 1,500만 건
  - 생성형 AI 광고 도구 사용 광고주 약 1,000만
- 에이전트 커머스(Li): "Personal Agent Protocol"을 이달 초 미리 공개했다. Sierra, Walmart, Stripe, Shopify 등과 함께 만드는 개방형 표준이다.
  - 원문: "we expect the market… to evolve away from agents attempting to navigate every digital experience like a human… towards more permissioned, structured interactions"
  - 번역: "시장은 에이전트가 사람처럼 모든 디지털 경험을 탐색하는 방식에서 벗어나, 허가 기반의 구조화된 상호작용으로 진화할 것으로 본다."
- 2027년 전망(Li): 정량 가이던스는 Q4 콜에서 준다. 원문 "continue investing aggressively(공격적으로 계속 투자)". 신규 AI 사업(구독, 거래, 광고, 엔터프라이즈)은 "begin contributing incremental revenue in 2027(2027년부터 추가 매출 기여 시작)".
- 엔터프라이즈(Li): "we really don't believe that traditional enterprise companies have this locked down"(전통적인 엔터프라이즈 기업들이 이 시장을 장악했다고 보지 않는다). 소상공인 5억 곳을 기반으로 삼는다.

#### 11) 2026-10-21~22 무렵 — Demis Hassabis, WSJ Magazine "Job Interview"(2026 Technology Innovator)
- ❌ 원문 미열람. WSJ X 게시물 스니펫에 따르면 Hassabis는 최근의 AI rogue 사고를 "warning shots(경고 사격)"으로 봐야 하며, 보안과 규제 문제를 지금 다뤄야 한다고 했다 — [WSJ X](https://x.com/WSJ/status/2113275683505868838)
- 함의: 같은 rogue 사고를 두고 LeCun(설계 실패일 뿐 "zero concerns")과 Hassabis("경고 사격")가 정반대로 해석한다. 단, 둘 다 원문 확인 수준이 다르다(LeCun ✅, Hassabis ❌).

#### 12) 2026-10-27 — Google DeepMind, Genie 4 (월드 모델)
- 형식: DeepMind 블로그(페이지는 JS라 본문 추출 실패, 날짜 2026-10-27만 확인), TechCrunch 브리핑 기사
  - 출처: [DeepMind](https://deepmind.google/blog/genie-4-a-new-generation-of-world-simulation/), [TechCrunch](https://techcrunch.com/2026/10/27/googles-genie-4-world-model-adds-audio-more-realistic-worlds-and-real-time-steering/)
- 핵심 포인트 (TechCrunch 원문 확인):
  - 연구 프리뷰로 공개했다.
  - 실시간 오디오(음악, 환경음, 대화)를 생성한다.
  - 시뮬레이션 도중 프롬프트로 날씨나 카메라를 바꿀 수 있다.
  - 장면 일관성은 최대 2분으로 이전의 2배다.
  - Gemini가 "director(감독)" 역할을 맡는다. Gemini Robotics 실험에서는 Argon이 과제를 분해하고 Genie 4가 이를 실시간으로 시뮬레이션했다.
- 인용 (Tejas Kulkarni, Google 연구 디렉터):
  - 원문: "What we'll increasingly see in the future are these hybrid world models, where you have a combination of Gemini writing code and text, and Genie ingesting that in real time and simulating reality at different levels of abstraction."
  - 번역: "앞으로 점점 더 보게 될 것은 하이브리드 월드 모델이다. Gemini가 코드와 텍스트를 쓰고, Genie가 그것을 실시간으로 받아 다양한 추상화 수준에서 현실을 시뮬레이션하는 식이다."
- Pichai(콜): "our most advanced world model yet… This is an important building block for training robots and agents."(지금까지 가장 진보한 월드 모델이며, 로봇과 에이전트를 훈련하는 중요한 구성 요소다) ✅ — [Pichai 블로그](https://blog.google/company-news/inside-google/message-ceo/alphabet-earnings-q3-2026/)
- Hassabis X(❌ 원문 미확인, 스니펫):
  - 원문: "Very excited to share Genie 4… Simulations within simulations, makes you wonder just how deep the rabbit hole goes..."
  - 번역: "Genie 4를 공유하게 되어 매우 기쁘다… 시뮬레이션 안의 시뮬레이션이라니, 토끼굴이 얼마나 깊은지 궁금해진다."
  - 출처: https://x.com/demishassabis/status/2115232001275924722
- 업계 맥락(TechCrunch): 월드 모델 업계가 통합되고 있다. AMD가 World Labs를 인수하고, Amazon은 Decart 인수를 협상 중이다.

#### 13) 2026-10-28 — Alphabet Q3 실적 콜 (Pichai, Schindler, Kurian, Ashkenazi) — 신규 포인트 (출처: [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/), [Pichai 블로그](https://blog.google/company-news/inside-google/message-ceo/alphabet-earnings-q3-2026/))

**검색 (Pichai):**
- "our year-over-year query growth rate is the highest it's been in the last five years"(전년 대비 쿼리 성장률이 최근 5년 중 가장 높다)
- "Queries in AI Mode are on average three times longer than traditional searches, and one in five AI Mode searches globally use voice, images, or documents. We have now crossed over 50 billion visual searches per month."(AI Mode 쿼리는 평균적으로 기존 검색보다 3배 길고, 전 세계 AI Mode 검색 5건 중 1건은 음성·이미지·문서를 쓴다. 시각 검색은 월 500억 건을 넘었다.)
- "Just like our shift to mobile over a decade ago, we are focused on building the best Search user experience, followed by monetization."(10여 년 전 모바일 전환 때처럼 최고의 검색 경험을 먼저 만들고 수익화는 그다음이다.)
- ❌ AI Overviews와 AI Mode의 사용자 수(MAU)는 이번 콜에서 공개하지 않았다.

**검색 매출 (Schindler / Ashkenazi):**
- Search 매출은 +12%로 633억 달러다. 둔화 요인은 세 가지다.
  - 환율(최대 요인)
  - EU 소액면세 폐지로 APAC 리테일 광고주가 타격을 받음
  - FIFA 월드컵 효과가 정상화됨
  - 원문: "the strong growth in AI Mode queries had an impact because of the lower monetization we were seeing in AI Mode"(AI Mode 쿼리의 강한 성장이 영향을 줬다. AI Mode의 수익화가 낮았기 때문이다)
- ⚠️ 출처 간 인용 차이: Benzinga/Yahoo는 같은 문장을 "The strong growth in AI Overviews had an impact…"로 옮겼다 — [Yahoo/Benzinga](https://finance.yahoo.com/technology/ai/articles/google-search-revenue-growth-slows-100020621.html). Fortune 전사본을 우선한다.
- 기저효과(Ashkenazi): 3분기에 약 3%p를 잃었고, 4분기에도 몇 %p의 기저효과가 있을 것으로 예상한다.
- AI Mode 광고를 국제 시장으로 확대하고, 미국에서 multi-turn 광고를 시작한다. AI Mode 안에서 스폰서와 오가닉 제품 목록의 클릭률이 비슷하다.

**모델·속도 (Pichai):**
- Argon 첫 주 개발자 플랫폼 사용량은 Gemini 3보다 3.5배 빠르게 늘었다(용량 제약 속에서도).
- 사내 Chrome, Ads, Search 팀은 Argon으로 코드를 35% 더 많이, 오류는 30% 적게 출시했다.
- RSI 원문: "We are at the point where AI is helping us increase our training and launch velocity. I would expect the next 12 months to see continued acceleration because of RSI."
  - 번역: "AI가 우리의 훈련과 출시 속도를 높여 주는 시점에 와 있다. 앞으로 12개월은 RSI(재귀적 자기개선) 덕분에 계속 가속될 것으로 본다."
- 내부 생산성 원문: "We are now deploying Carbon internally, and Carbon is a meaningful step up from Argon… what I would view as a golden year ahead"(지금 Carbon을 사내에 배포하고 있으며 Argon보다 의미 있게 진전된 모델이다… 앞으로 황금의 해가 될 것으로 본다)
- 3.8 Flash부터 "step change(계단식 변화)"가 시작됐고, Argon에서 "huge point of inflection(거대한 변곡점)"을 맞았다고 했다.

**에이전트 (Pichai):**
- "Agents will operate as a unifying layer across our products"(에이전트가 우리 제품 전반을 잇는 통합 계층으로 작동할 것이다)
- 엔터프라이즈 "Gemini agent"를 먼저 출시한 뒤 "Later this year"(올해 안에) Gemini 앱 소비자 10억 명에게 확대한다. Gemini 앱에 "task tab"을 추가했다.
- 원문: "when you are doing it at 70%, it looks like it does not work until you cross a certain threshold and it really takes off"
  - 번역: "70% 수준일 때는 안 되는 것처럼 보이다가, 어떤 문턱을 넘으면 정말로 도약한다."

**TPU 플랫폼 철학 (Pichai):**
- 원문: "we view our TPU systems as an important platform… putting it against market forces"
  - 번역: "TPU 시스템을 중요한 플랫폼으로 보고, 시장의 경쟁에 내놓는다."
- 원문: "in the semiconductor industry, economies of scale matter"
  - 번역: "반도체 산업에서는 규모의 경제가 중요하다."

**Cloud (Kurian):**
- 매출 10억 달러 이상 제품군이 18개다.
- 지난 12개월간 2,600곳 이상이 Gemini Enterprise에서 1,000억 토큰 이상을, 약 75곳이 10조 토큰 이상을 썼다.
- 지식노동 좌석을 1억 석 넘게 판매했다.
- TPU 8t와 8i는 이전 세대 대비 각각 학습 성능 최대 2.7배, 추론 가격 대비 성능 80% 향상을 제공한다.
- Meta와 함께 TorchTPU를 만들었다.
- 고객과 파트너: Anthropic(직접 및 Broadcom 경유), Apple, Physical Intelligence, Citadel Securities, Jump Trading이 고객이다. Crux AI(Blackstone 합작)와 Oracle을 통해 TPU 유통 파트너십을 맺었다.

**재무 기타 (Ashkenazi):**
- 미래 구매 약정 9,240억 달러, 미개시 리스 등 1,520억 달러
- YouTube 광고 112억 달러(+9%), YouTube Music·Premium 구독자 1.5억 명 이상(체험 포함)
- Google One은 AI 플랜 덕분에 가장 빠르게 성장하는 구독이다.

**기타 (Pichai):** Waymo는 완전 자율주행 누적 3억 마일 이상, 미국 15개 도시에서 운영한다. Project Suncatcher로 TPU를 우주로 보냈다.

#### 14) 2026-10-28 — Google, AI Mode 광고 해외 확대 (Shashi Thakur, VP·GM 검색 광고)
- 대상 국가: 호주, 캐나다, 인도, 케냐, 말레이시아, 뉴질랜드, 나이지리아, 파키스탄, 필리핀, 싱가포르. 4분기에 브라질, 멕시코, 영국으로 확대할 예정이다.
- 미국에서는 multi-turn 광고를 시작한다.
- 출처: [Google Blog](https://blog.google/products/ads-commerce/ads-in-ai-mode-global/)

#### 15) 2026-10-28 — Google Connected Apps 플랫폼 (Gemini와 Search에 서드파티 앱 개방)
- MCP 서버 또는 Android AppFunctions로 앱을 연동한다.
- Gemini에는 이미 50개 이상의 Connected Apps가 있고, 몇 주 안에 Search로 확대된다. 미국 개발자 대상 공개 프리뷰다.
- 출처: [TechCrunch](https://techcrunch.com/2026/10/28/as-ai-agents-reshape-the-web-google-opens-gemini-and-search-to-more-apps/), [Google Blog](https://blog.google/innovation-and-ai/technology/developers-tools/connected-apps-one-place/)

#### 16) 2026-10-28 — Meta, Muse 싱가포르 출시 (첫 미국·캐나다 외 출시로 보임)
- Shopee, Grab, Singapore Airlines, Agoda 등을 커넥터로 지원한다. Muse Secure VM에서 동작한다.
- "free for most of what people need, with subscription plans(대부분의 용도는 무료, 더 쓰려는 사람에게는 구독 플랜)"
- 인용 (Nicole Tan, Meta Singapore MD):
  - 원문: "Muse is your personal agent, built to help make everyday life easier."
  - 번역: "Muse는 일상을 더 쉽게 만들어 주는 당신의 개인 에이전트다."
- 출처: [Meta Newsroom](https://about.fb.com/news/2026/10/muse-is-now-available-in-singapore-the-worlds-first-personal-ai-agent-built-for-everyone/)
- 함의: 콜(10/21)에서는 컴퓨팅 비용 때문에 글로벌 출시를 미뤘다고 했는데, 1주일 뒤 첫 확장 시장이 나왔다.

#### 17) 2026-10-28 — Josh Woodward X
- Gemini에 Strava 연결 기능을 추가했다. ❌ 원문 미열람 — [X](https://x.com/joshwoodward/status/2115580552170627080)

#### 18) 2026-10-29 — Gemini 앱에서 문서·PDF·프레젠테이션·스프레드시트 생성·편집
- blog.google RSS 제목만 확인 — [Google Blog](https://blog.google/innovation-and-ai/products/gemini-app/edit-files-directly/)

#### 19) 2026-10-30 — Project Suncatcher 위성 첫 응답
- RSS와 TechCrunch 제목만 확인 — [Google Blog](https://blog.google/innovation-and-ai/models-and-research/google-research/project-suncatcher-satellite-response/), [TechCrunch](https://techcrunch.com/2026/10/30/googles-first-data-center-satellite-is-online-and-writing-poetry/)

#### 20) 2026-10-31 — Hassabis, Nobel Prize Dialogue London 패널
- ❌ 일정 페이지 스니펫만 확인했고 발언 내용은 없다 — [NobelPrize.org](https://www.nobelprize.org/events/nobel-prize-dialogue/london-2026/panellists/demis-hassabis/)

#### (맥락, 기간 밖)
- Nat Friedman(MSL 제품 총괄)은 9/21 X에 "we built muse from scratch, but it is definitely heavily inspired as a product by openclaw"(Muse는 처음부터 직접 만들었지만, 제품으로서는 확실히 OpenClaw에서 크게 영감을 받았다)라고 썼다 — [TechCrunch 9/22](https://techcrunch.com/2026/09/22/meta-admits-muses-likeness-to-openclaw-isnt-a-coincidence/)
- CNBC(2026-08-06, 미열람)는 Hassabis의 DeepMind 내 역할이 바뀌었다고 보도했다(검색 요약에는 "CEO에서 의장으로"). 직함은 미검증이므로 보고서에서는 "Google DeepMind 공동창업자·수장"처럼 중립적으로 표기하는 것을 권한다 — [CNBC(미열람)](https://www.cnbc.com/2026/08/06/demis-hassabis-google-reshuffle-deepmind-role.html)

### Inferences
- **Google**은 이번 기간에 "모델 출시 → 내부 생산성 → 에이전트 → 검색과 앱 개방"을 하나의 이야기로 엮었다. 근거는 Argon과 Carbon, RSI 발언, Gemini agent, Connected Apps, AI Mode 광고다. 월드 모델(Genie 4)은 로봇과 에이전트 훈련의 기반으로 위치를 잡았다.
- **Meta**는 "제품-시장 적합성 확인 → 운영 단계(확장, 매출, 컴퓨팅 비용)"로 넘어가겠다고 했다. 실제로 1주일 만에 해외 확장(싱가포르)이 시작됐다.
- 두 회사 모두 **에이전트 커머스 표준**을 선점하려 한다. Google은 UCP, Agent Payments Protocol, Universal Cart를, Meta는 Personal Agent Protocol을 내세운다.

### Gaps
- **Jeff Dean, Chris Cox, Nat Friedman:** 기간 내 공개 발언을 찾지 못했다(검색 결과 없음).
- **Koray Kavukcuoglu:** 블로그 저자 외에 인터뷰는 찾지 못했다.
- **Pichai(Big Technology), Woodward(Lenny's), Wang(Senra), Hassabis(WSJ):** 원문 전사본에 접근하지 못했다.
- **Genie 4:** DeepMind 원문 본문(사양, 접근 범위)은 JS 렌더링 때문에 추출하지 못했다. 검색 요약에는 Ultra 구독자(Project Genie)와 API 조기 파트너 대상이라고 되어 있으나 미검증이다.
- **Meta AI MAU, Hyperion·Prometheus 진척:** 이 기간 1차 자료에서 찾지 못했다.

---

## Q3. 공개된 구체적 숫자 (원문 검증 완료분)

### Takeaway
**Alphabet** (출처: [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/))
- capex: Q3 514억 달러, 2026년 1,950억~2,050억 달러, 2027년 상당히 증가
- Cloud: 307억 달러(+103%), 이익률 36.2%, 백로그 5,610억 달러
- AI 사용: Gemini 앱 10억 명, API 분당 약 320억 토큰
- 현금흐름: FCF -91억 달러

**Meta** (출처: [Meta 콜 전문](https://fortune.com/company/facebook/earnings/q3-2026/))
- capex: Q3 349억 달러, 2026년 1,350억~1,450억 달러
- 현금흐름: FCF -21억 달러
- Muse: 1,000만 명 이상 설정, 일간 사용률 약 25%, 비용 효율 10배 이상 개선 목표
- 일간 사용자 3.64B
- Reality Labs 손실: 2027년 약 150억 달러로 축소 예상

### Cited Findings
- **Alphabet**
  - 매출 1,276억 달러(+25%), 연환산 런레이트 약 5,000억 달러, 영업이익 406억 달러(+30%), 영업이익률 31.8%
  - Services 963억 달러(+11%), Search 633억 달러(+12%), YouTube 광고 112억 달러(+9%), 구독·기기 143억 달러(+11%)
  - Cloud 307억 달러(+103%), Cloud 영업이익 111억 달러, Cloud 영업이익률 36.2%
  - 출처: [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/)
- **Alphabet 현금흐름:** 영업현금흐름 423억 달러, capex 514억 달러(서버·네트워크 약 65%, 데이터센터 약 35%), FCF -91억 달러(TTM 197억 달러). 현금 2,651억 달러, 장기부채 1,251억 달러, 구매 약정 9,240억 달러 — [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/)
- **Alphabet 기타손익:** -82억 달러(SpaceX 미실현 손실). 언론 보도 EPS는 2.12달러(예상 3.02달러) — [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/), [Yahoo/Benzinga](https://finance.yahoo.com/technology/ai/articles/google-search-revenue-growth-slows-100020621.html)
- **Alphabet 사용 지표**
  - Gemini 앱 10억 명
  - API 분당 약 320억 토큰(전 분기 대비 +40%, 전년 대비 4배 이상)
  - AI Mode 쿼리는 기존 검색의 3배 길이이고, 5건 중 1건이 멀티모달
  - 시각 검색 월 500억 건 이상
  - YouTube Music·Premium 1.5억 명 이상
  - Gemini가 광고주용 캠페인 소재 15억 개 이상 생성(전년 대비 7배 이상)
  - 출처: [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/), [Pichai 블로그](https://blog.google/company-news/inside-google/message-ceo/alphabet-earnings-q3-2026/)
- **Alphabet Cloud 고객 지표:** 2,600곳 이상이 1,000억 토큰 이상 사용, 약 75곳이 10조 토큰 이상 사용, Fortune 100의 약 90%가 Gemini Enterprise 사용, 지식노동 좌석 1억 석 이상, TPU 고객 약 100곳(Q&A에서는 "100곳 이상") — [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/)
- **Meta**
  - 매출 646억 달러(+26%), 비용 516억 달러, 영업이익 130억 달러(이익률 20%), EPS 3.83달러
  - capex 349억 달러, FCF -21억 달러
  - 4분기 매출 가이던스 730억~760억 달러
  - 2026년 비용 1,750억~1,790억 달러, capex 1,350억~1,450억 달러
  - Reality Labs 손실: 2026년 180억~190억 달러, 2027년 약 150억 달러
  - 출처: [Meta 콜 전문](https://fortune.com/company/facebook/earnings/q3-2026/)
- **Meta 사용 지표:** 일간 사용자 3.64B, Muse 1,000만 명 이상(미국·캐나다, 약 6주), 일간 사용률 약 25%, 쇼핑은 사용자의 4분의 1 이상(평균 200달러 이상), Meta AI 1인당 참여 2배 이상(4월 대비), Meta One 1,500만 건, 파트너십 광고 연환산 150억 달러 이상 — [Meta 콜 전문](https://fortune.com/company/facebook/earnings/q3-2026/)
- **Carbon 및 Argon 가격:** 입력 100만 토큰당 2달러, 출력 10달러. Carbon AA Index v5.0 59점, SEC-bench Pro 88.2% — [Google Blog](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-carbon/)
- **Muse Spark Open:** 816B 총 파라미터, 42B 활성 — [HF](https://huggingface.co/meta-models/Muse-Spark-Open-816B-A42B)

### Inferences
- 두 회사 2026년 capex 가이던스 중간값 합계는 약 3,400억 달러다(2,000억+1,400억, 필자 계산).
- 두 회사 모두 Q3 FCF가 마이너스였다. 원인은 다르다. Alphabet은 TPU 재고(판매용 하드웨어)와 EC 벌금이라는 일회성·운전자본 요인이 섞여 있다. Meta는 순수하게 capex와 소송 비용 때문이다.
- Alphabet의 Cloud 이익률 상승(36.2%)은 외부 브리징 용량이 3분기 말에야 가동된 덕분에 비용이 아직 덜 반영된 결과다. 4분기에는 마진 역풍이 예고되어 있다. 이전의 "TPU 판매가 고마진"이라는 추정은 근거가 약하다. 경영진은 TPU 마진을 공개하지 않았다(Kurian: "we do not break out margins").

### Gaps
- Alphabet 공식 보도자료의 EPS와 전년 EPS(검색 스니펫상 2.87달러), 시간외 주가 반응은 1차 원문으로 미확인이다.
- Meta 조정 EPS와 컨센서스는 원문에 없다.

---

## Q4. 이전 입장 대비 변화와 함의

### Takeaway
1. **Google:** "compute constrained(컴퓨팅 제약)"(Q1) 단계에서 외부 브리징 용량 사용(Q3 말 가동, Q4 확대)으로 넘어갔다. TPU는 외부 판매 플랫폼이 되어 Anthropic·Apple·Oracle·Crux 유통까지 이어졌다. "RSI로 인한 가속"이라는 새로운 수사도 등장했다.
2. **Meta:** "Llama 오픈소스"에서 "Muse 클로즈드 프런티어 + 하위 모델 오픈 웨이트"로 공식 전환했다. 메시지는 "스케일링으로 초지능"과 "제품-시장 적합성 이후 수익화를 앞당김"으로 바뀌었다.
3. **출시 방식:** 프런티어 모델 출시가 사이버보안 방어자 우선의 단계적 출시로 바뀌었다. Google의 Argon과 Carbon이 모두 Fairwind로 시작했고, 미국 정부 사전 테스트에도 참여했다.
4. **LeCun:** 반(反) 스케일링·반 위험론 입장을 그대로 유지했다.

### Cited Findings
- (맥락) Q1 2026 콜에서 Pichai는 "we are compute constrained in the near term"(단기적으로 컴퓨팅 제약 상태)라고 했다 — [Fool(미열람, 기존 노트 인용)](https://www.fool.com/earnings/call-transcripts/2026/04/29/alphabet-googl-q1-2026-earnings-call-transcript/)
  - Q3 원문: "given the supply-constrained environment, we started utilizing third-party compute capacity at the end of Q3"(공급 제약 환경 때문에 3분기 말 외부 컴퓨팅 용량을 쓰기 시작했다)
  - Kurian: "we could obviously serve a lot more demand with capacity"(용량만 있으면 훨씬 많은 수요를 소화할 수 있다)
  - 출처: [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/)
- TPU 매출 인식 시점(Ashkenazi): "To date, we've had some system sales recorded as revenue, but expect more of it to come in through 2027"(지금까지 일부 시스템 판매가 매출로 잡혔지만, 2027년에 걸쳐 더 많이 들어올 것으로 예상한다). "TPU 매출이 예상보다 빨라졌다"는 기존 노트의 해석은 원문상 "일부만 인식, 본격 매출은 2027년"이라는 신중한 표현에 가깝다 — [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/)
- 검색의 수익화 지연: "focused on building the best Search user experience, followed by monetization"(최고의 검색 경험이 먼저, 수익화는 그다음)(Pichai). AI Mode의 낮은 수익화가 Search 성장 둔화 요인 중 하나라고 인정했다(Schindler) — [Alphabet 콜 전문](https://fortune.com/company/alphabet/earnings/q3-2026/)
- Meta의 수익화 가속:
  - 원문: "we are going to work on monetization somewhat sooner on this than our normal playbook"
  - 번역: "이번에는 평소 플레이북보다 다소 일찍 수익화에 착수할 것이다."
  - 출처: [Meta 콜 전문](https://fortune.com/company/facebook/earnings/q3-2026/)
- Meta의 개방 정책: Muse Spark Open은 공개하되 최강 모델은 닫아 둔다 — [PyTorch(검색)](https://pytorch.org/blog/muse-spark-open/). Zuckerberg: "pushing the frontier of intelligence and distilling those models into much smaller and more efficient product models"(지능의 프런티어를 넓히는 동시에 그 모델을 훨씬 작고 효율적인 제품용 모델로 증류한다) — [Meta 콜 전문](https://fortune.com/company/facebook/earnings/q3-2026/)
- 두 회사 모두 "증류" 노선을 공식화했다. Google은 "distilled versions of our Carbon models"(Carbon 증류 버전), Meta는 "smaller models… Muse Wonder-level intelligence more efficiently"(Muse Wonder 수준 지능을 더 효율적으로 제공하는 소형 모델)라고 했다 — [Alphabet 콜](https://fortune.com/company/alphabet/earnings/q3-2026/), [Meta 콜](https://fortune.com/company/facebook/earnings/q3-2026/)
- 초지능 용어: Zuckerberg의 "personal superintelligence" 표현은 1년 넘게 써 온 것이다(원문 확인). CNBC의 "Trump 용어 동조" 해석과 충돌한다 — [Meta 콜 전문](https://fortune.com/company/facebook/earnings/q3-2026/), [CNBC(미열람)](https://www.cnbc.com/2026/10/30/trump-tech-allies-swap-ai-for-super-intelligence-in-earnings-calls.html)
- LeCun은 JEPA 월드 모델과 위험론 비판을 유지했고, Muse를 직접 쓰는 등 Meta와 우호적 관계다 — [Fortune 10/01](https://fortune.com/2026/10/01/ai-godfather-yann-lecun-has-zero-concerns-about-human-extinction-says-anthropic-ceo-dario-amodei-is-deuded/)

### Inferences
- **"AI가 AI를 가속한다"는 서사가 두 회사 모두에서 공식 실적 콜에 등장했다.**
  - Google: "next 12 months… continued acceleration because of RSI"(앞으로 12개월은 RSI 덕분에 계속 가속)
  - Meta: Muse Wonder로 추천·광고 시스템을 자율 개선하는 eval을 만들고 "increasing rate of improvement(개선 속도가 빨라짐)"을 기대한다고 했다.
  - 2026년 4분기 업계 트렌드 키워드로 쓸 만하다.
- **병목은 컴퓨팅 비용과 용량이다.** Google은 외부 용량을 임대하고 2027년분 요청은 "대단히 어렵다"(팟캐스트, 미검증)고 했다. Meta는 글로벌 출시를 지연하고 10배 효율 개선을 목표로 삼았다. 두 회사가 같은 제약을 말한다.
- **월드 모델 축이 갈라진다.** Google은 Genie 4를 Gemini가 감독하는 "하이브리드 월드 모델"로 로봇과 에이전트 훈련에 연결한다. LeCun(AMI)은 생성형이 아닌 JEPA로 LLM 자체를 대체하겠다는 노선이다. 두 노선은 철학이 다르다.

### Gaps
- Hassabis의 AGI 시점 전망이 이 기간에 갱신됐는지 확인하지 못했다. WSJ 인터뷰는 원문에 접근하지 못했다.
- Q1·Q2 콜 원문(Fortune의 q1-2026, q2-2026 페이지가 있음)과의 직접 비교는 예산 문제로 수행하지 않았다. 필요하면 https://fortune.com/company/alphabet/earnings/q2-2026/ 에서 대조할 수 있다.
