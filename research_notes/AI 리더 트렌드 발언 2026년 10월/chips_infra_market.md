# AI 반도체·인프라·투자 리더 발언 및 시장 맥락 (2026-10-02 ~ 2026-11-02)

> **조사 방법 및 한계 (먼저 읽을 것)**
> - 이 세션에서는 WebFetch가 거의 모든 외부 도메인에서 막혔다(fool.com, sec.gov, cnbc.com, finance.yahoo.com, trendforce.com, substack 모두 DNS 미해결). 그래서 **모든 내용은 WebSearch(extended) 결과 요약/스니펫을 근거로 한다**. 원문 전문을 직접 읽어 확인하지 못했다. 인용문은 2차 보도에 실린 문구이며, 매체마다 표현이 조금씩 다를 수 있다.
> - 숫자가 매체마다 다른 경우 따로 표시했다. 1차 자료(IR 보도자료, 10-Q)와 대조하지 못했다.
> - 날짜는 요일까지 맞춰 봤다: 2026-10-12(월), 10-15(목), 10-22(목), 10-28(수), 10-29(목).
> - **NVIDIA GTC DC 2026은 이 기간에 열리지 않았다.** 2026-12-01~03(워크숍 11-30)에 Reagan Building에서 열리고, 키노트는 12-01(화) 오후 2시 ET 예정이다 — [NVIDIA GTC DC](https://www.nvidia.com/gtc/dc/), [HotHardware](https://hothardware.com/news/jensen-huang-nvidia-gtc-washington-keynote-new-ai-reveals). 직전 GTC DC는 2025-10-27~29였다(맥락용) — [Wikipedia](https://en.wikipedia.org/wiki/Nvidia_GTC).
> - AMD Q3 실적(통상 11월 첫째 주)과 NVIDIA Q3 FY27 실적(11월 하순)은 기간 밖일 가능성이 높다. 10월 중 Lisa Su 발언은 찾지 못했다(Gaps 참조).

## Q1. 반도체 리더(NVIDIA·TSMC·Intel·Broadcom·AMD·Arm·메모리)는 무엇을 말했나

### Takeaway
반도체 CEO들은 한목소리로 "수요가 공급보다 크다"고 말했다(TSMC C.C. Wei, Broadcom Hock Tan, Intel Lip-Bu Tan, NVIDIA Jensen Huang). 다만 10월에는 화제가 **칩 부족에서 자본·자금조달 제약과 ROI**로 옮겨 갔다. Hock Tan은 일부 AI 투자자를 "카지노 도박꾼"에 비유했다. 메모리(SK hynix)는 2029~2030년까지 공급 부족이 이어진다고 공언했다.

### Cited Findings

#### [1] Broadcom Hock Tan · Intel Lip-Bu Tan — DBS Asia Future Forward Conference (싱가포르), 2026-10-12(월)
- 형식: 컨퍼런스 대담/패널. DBS 주최.
- URL: [CNBC](https://www.cnbc.com/2026/10/12/intel-broadcom-ceos-warn-capital-crunch-could-become-ai-bottleneck.html), [TheNextWeb](https://thenextweb.com/news/broadcom-hock-tan-ai-investors-casino-capital), [Quartz](https://qz.com/intel-broadcom-ceos-capital-constraint-ai-growth-101226), [The Edge Singapore](https://www.theedgesingapore.com/news/tech/dbs-ceo-tan-says-market-repricing-risks-ai-financing)
- 요약: 두 CEO 모두 AI 확장을 가장 크게 묶을 수 있는 것은 반도체·메모리·전력이 아니라 **자본(자금조달 비용)**이라고 말했다. Hock Tan은 컴퓨트 수요가 공급을 넘는 상황이 2029년, 어쩌면 2030년까지 갈 수 있다고 봤다. Lip-Bu Tan은 앞으로 2~3년 AI 인프라 수요가 크게 꺾이지 않겠지만 결국 시장은 ROI를 요구할 것이라고 했다.
- 주요 포인트:
  - Hock Tan: 최대 제약 = 자본. 수요 > 공급, 2029~2030년까지 지속 가능.
  - Hock Tan: 많은 AI 투자자를 도박꾼에 비유.
  - Lip-Bu Tan: 과제는 자본과 자본비용, 장기적으로는 ROI 검증.
  - DBS CEO 탄수산(Tan Su Shan): 시장이 AI 금융 리스크를 다시 가격에 반영 중이며, 그러면 자금조달 규율이 생길 것. DBS는 올해 AI 딜 약 S$250억을 주선했고 그중 일부만 보유 — [The Edge Singapore](https://www.theedgesingapore.com/news/tech/dbs-ceo-tan-says-market-repricing-risks-ai-financing)
- 인용:
  - Hock Tan: "[What] I think might be the biggest constraint is capital." → "가장 큰 제약은 아마 자본일 것이라고 생각합니다."
  - Hock Tan: "There is more demand for compute infrastructure than we can supply." → "우리가 공급할 수 있는 것보다 컴퓨트 인프라 수요가 더 많습니다."
  - Hock Tan: "A lot of investors have no clue what they are investing in." → "많은 투자자들은 자신이 무엇에 투자하는지 전혀 모릅니다." — [TheNextWeb](https://thenextweb.com/news/broadcom-hock-tan-ai-investors-casino-capital)
  - Lip-Bu Tan: "If there's any challenge in the front, it's capital and the cost of capital, and then the other part is in the longer run, people want to see the ROI." → "앞에 놓인 과제가 있다면 자본과 자본비용이고, 장기적으로는 사람들이 ROI를 보고 싶어 한다는 점입니다."
- 시사점: 공급망 CEO가 직접 '자금조달 병목'을 공개적으로 말한 것은 같은 달 CoreWeave·Oracle 신용 스트레스(아래 Q2)와 정확히 맞물린다. 이제 AI 사이클의 위험 변수는 기술보다 금융 쪽이다.

#### [2] TSMC C.C. Wei — Q3 2026 실적 컨퍼런스콜, 2026-10-15(목)
- URL: [Motley Fool 전사록](https://www.fool.com/earnings/call-transcripts/2026/10/15/tsmc-tsm-q3-2026-earnings-call-transcript/), [TSMC 6-K(SEC)](https://www.sec.gov/Archives/edgar/data/0001046179/000104617926000726/a3q26e_withguidancexfinal.htm), [CRN Asia](https://www.crnasia.com/news/2026/components-and-peripherals/tsmc-third-quarter-revenue-tops-guidance-as-ceo-says-ai-dema), [BigGo Finance](https://finance.biggo.com/news/US_TSM_2026-10-15), [TradingView/Zacks](https://www.tradingview.com/news/zacks:3ddab2816094b:0-tsm-q3-earnings-call-highlights-strong-ai-demand-and-expansion/), [Investing.com](https://www.investing.com/news/transcripts/earnings-call-transcript-tsmc-beats-q3-2026-estimates-as-stock-slips-93CH-4950695)
- 주요 숫자:
  - Q3 매출 **467.2억 달러**, 전년 대비 +41.2%, 전분기 대비 +16.2%. 일부 매체는 468.7억 달러로 보도했으나 TSMC 공식 자료 기준은 467.2억 달러다 — [CRN Asia](https://www.crnasia.com/news/2026/components-and-peripherals/tsmc-third-quarter-revenue-tops-guidance-as-ceo-says-ai-dema), [BigGo](https://finance.biggo.com/news/US_TSM_2026-10-15)
  - HPC(AI 칩 포함) 비중 **68%**.
  - Q4 가이던스: 전년 대비 약 **+58%** 성장 — [BigGo](https://finance.biggo.com/news/US_TSM_2026-10-15)
  - 연간 성장률 전망을 달러 기준 약 **44%**로 상향(전 분기 "40% 초반"에서) — [Tech-Insider](https://tech-insider.org/tsmc-ai-boom-record-profit-2026/) (2차 출처)
  - AI 가속기 매출이 2024~2029년 CAGR "50% 중후반"이라는 기존 전망을 넘을 수 있다고 시사. CPU는 TSMC의 좁은 AI 가속기 정의에 들어가지 않는다고 명확히 했다 — [TradingView/Zacks](https://www.tradingview.com/news/zacks:3ddab2816094b:0-tsm-q3-earnings-call-highlights-strong-ai-demand-and-expansion/)
  - 리스크: 북미 고객 비중 79%. 수주잔고 수치는 제시하지 않았다(애널리스트 지적).
  - 주가는 실적이 예상을 넘었는데도 하락했다 — [Investing.com](https://www.investing.com/news/transcripts/earnings-call-transcript-tsmc-beats-q3-2026-estimates-as-stock-slips-93CH-4950695)
- 인용(2차 보도 기준):
  - AI 수요는 "extremely robust" → "극도로 견조하다"
  - "the gap between demand and supply are still quite big" → "수요와 공급 사이의 격차는 여전히 상당히 크다"(그래서 생산능력을 늘리는 중)
- 시사점: 파운드리 최상단에서는 버블 신호가 보이지 않는다. 다만 북미 소수 고객에 대한 집중도가 높아서, 하이퍼스케일러 capex 속도 조절(Q4 참조)이 TSMC로 그대로 전달될 위험이 있다.
- 참고: 2nm·CoWoS·HBM 관련 세부 내용은 [VLSI.kr 정리](https://www.vlsi.kr/en/tsmc-q3-2026-earnings-18-facts-en/)에 있으나 직접 읽지 못했다.

#### [3] NVIDIA Jensen Huang — Bloomberg 인터뷰(스톡홀름), 2026-10-15(목) 전후
- URL: [Bloomberg 영상(2026-10-15)](https://www.bloomberg.com/news/videos/2026-10-15/huang-downplays-coreweave-concern-after-risk-gauge-soars-video), [TheNextWeb](https://thenextweb.com/news/huang-coreweave-backstop-stockholm), [Quartz](https://qz.com/jensen-huang-coreweave-debt-default-risk-record-101626), [Capital Brief](https://www.capitalbrief.com/newsletter/nvidia-boss-says-coreweave-wont-need-bailout-cded29fb-b7ef-4529-91ce-c66a9cd16920/), [AI Weekly](https://aiweekly.co/alerts/nvidias-huang-tells-bloomberg-ai-market-rout-will-pass), [KuCoin 요약](https://www.kucoin.com/news/flash/nvidia-s-huang-renxiong-dismisses-ai-bubble-concerns-urges-faster-deployment)
- 장소·날짜가 출처마다 다르다: 대부분 스톡홀름(목요일 = 10-15)이라고 하고, Bloomberg 영상 페이지 날짜도 10-15다. 한 aggregator는 "10-16 베를린"이라고 했고, 또 다른 요약은 "10-14 런던"이라고 했다. **스톡홀름 10-15가 가장 신뢰할 만하다.** 인터뷰어는 Emily Chang으로 보도됐다.
- 요약: CoreWeave 5년물 CDS가 사상 최고 1,194.5bp(5년 내 디폴트 확률 60% 넘게 반영)를 찍은 날, Huang은 CoreWeave에 구제(backstop)가 필요 없다고 말했다. CoreWeave의 자본비용은 내려가고 있다고 했다. 현재는 AI 버블이 아니며 수요가 공급을 넘는다고 했고, 다만 언젠가 공급이 수요를 넘을 수 있다는 점은 인정했다. AI 주가 급락은 "지나갈 것"이라고 했다.
- 수치: NVIDIA의 CoreWeave 지분은 약 10%. 당일 CoreWeave 주가는 +5.9%로 $69.69에 마감했다 — [TheNextWeb](https://thenextweb.com/news/huang-coreweave-backstop-stockholm)
- 인용: "CoreWeave's strength is improving every day." → "CoreWeave의 체력은 날마다 좋아지고 있습니다."
- 시사점: 칩 공급자이자 주주인 NVIDIA가 고객사(네오클라우드)의 신용을 공개적으로 변호해야 했다. 이른바 '순환 금융(vendor financing)' 우려를 보여 주는 대표 장면이다.
- (맥락, 기간 외) 약 6주 전 CBS 인터뷰에서 Huang은 "high production ramp" 국면이라고 했다. NVIDIA는 분기 매출 가이던스를 1,080억 달러로 냈다(직전 분기 실적 962억 달러). Michael Burry는 NVIDIA 숏 포지션을 늘렸다 — [BeInCrypto](https://beincrypto.com/nvidia-ceo-ai-production-ramp/)

#### [4] Intel Lip-Bu Tan — Q3 2026 실적 발표·콜, 2026-10-29(목)
- URL: [Intel 8-K 실적 보도자료](https://www.sec.gov/Archives/edgar/data/0000050863/000005086326000188/q326earningsrelease.htm), [MarketBeat](https://www.marketbeat.com/earnings/reports/2026-10-29-intel-co-stock/), [Motley Fool 전사록](https://www.fool.com/earnings/call-transcripts/2026/10/30/intel-intc-q3-2026-earnings-call-transcript/), [StockAnalysis 전사록](https://stockanalysis.com/stocks/intc/transcripts/714242-q3-2026/)
- 주요 숫자:
  - 매출 165억 달러(전년 대비 +21%). 컨센서스 165.6억 달러에 소폭 미달.
  - GAAP EPS 0.60달러, non-GAAP EPS 0.52달러(컨센서스 0.41달러 상회).
  - Q4 가이던스: 매출 150~160억 달러, non-GAAP EPS 0.25달러.
  - DCAI(데이터센터·AI) 부문이 15년 만에 가장 큰 성장. 반면 CCPG(PC)는 메모리 가격 상승과 IT 예산 제약으로 약세.
  - Diamond Rapids(첫 18A-P 서버 제품)를 샘플링 중이며 2027년 양산 예정. Intel 14A 0.9 PDK를 10월에 일부 고객에게 배포.
- 인용(요약 보도): CPU 수요는 "remains robust despite PC-industry headwinds" → "PC 업계 역풍에도 견조하다". 고객 수요를 "likely not fully meet" → "아마 완전히 충족하지 못할 것"이며, 상반기가 하반기보다 더 어렵다고 했다.
- 시사점: 에이전틱 AI와 추론 확산으로 서버 CPU 수요까지 공급 부족 상태다. 동시에 메모리 가격 급등이 PC·소비자 기기 수요를 깎는 '메모리 인플레이션' 부작용이 실적에 나타났다.

#### [5] SK hynix — Q3 2026 실적, 2026-10-28 전후 / Samsung 잠정실적 2026-10-08
- URL: [TrendForce(2026-10-28)](https://www.trendforce.com/news/2026/10/28/news-sk-hynix-3q26-opm-hits-record-80-says-dram-hbm-effectively-sold-out-to-2029-14-lta-customers-signed/), [TheNextWeb](https://thenextweb.com/news/sk-hynix-q3-2026-record-profit-memory-shortage-2030), [Hardware Busters](https://hwbusters.com/news/sk-hynix-earnings-hit-an-80-margin-and-it-says-the-memory-shortage-runs-to-2030/), [서울경제(2026-10-08)](https://en.sedaily.com/finance/2026/10/08/hbm-prices-to-double-as-memory-shortage-drives-samsung), [BuySellRAM](https://www.buysellram.com/blog/what-samsung-and-sk-hynixs-q3-2026-results-reveal-about-the-future-of-ai-memory/), [CryptoBriefing](https://cryptobriefing.com/samsung-overtakes-sk-hynix-hbm4-sales/)
- SK hynix:
  - 분기 매출 처음으로 100조 원 돌파, 영업이익률 약 80%(사상 최고).
  - DRAM·HBM은 2029년까지 사실상 완판. 장기공급계약(LTA) 고객 14곳과 체결, LTA가 2027~2028년 생산능력의 절반 이상을 커버.
  - 수요 초과는 2030년까지 이어진다고 봄.
  - HBM4 양산 출하 시작. DRAM 평균가격은 전분기 대비 20% 후반 상승.
  - CFO: 내년 HBM 물량과 가격은 주요 고객과 이미 확정.
  - 순이익 39.8조 원(전분기 대비 약 -58%, TheNextWeb 보도). 영업이익 급증과 방향이 반대라 원인 확인이 필요하다.
- Samsung:
  - 잠정 영업이익 107.4조 원(서울경제).
  - HBM4 가격은 내년에 약 2배로 오를 전망. TrendForce는 2027년 HBM ASP +121%를 예상.
  - Q3 HBM 매출 약 87억 달러로 SK hynix(약 76억 달러)를 추월했다는 보도가 있으나 **추정치**다(CryptoBriefing).
  - 공급 타이트 지속은 2028년까지로 봄.
- 시사점: 메모리는 AI 공급망에서 가장 가격 결정력이 강한 병목이 됐다. 하이퍼스케일러 capex가 늘어나는 이유 중 상당 부분이 '부품 단가 상승'(Microsoft CFO 발언, Q4 참조)이라는 점과 연결된다.

#### [6] (기간 외 맥락) Arm Rene Haas, AMD Lisa Su
- Arm Haas, 2026-07 CNBC/Fox: AI 컴퓨트 버블론을 일축했다. 공급 제약이 2~3년 지속될 것이고 데이터센터가 Arm의 최대 사업이 될 것이라고 했다 — [CNBC 영상 2026-07-15](https://www.cnbc.com/video/2026/07/15/arm-ceo-rene-haas-says-the-ai-boom-is-supply-constrained-with-robust-demand.html), [Fox](https://www.fox.com/watch/clip/fmc-2k69omcrcqvi4iqt/arm-ceo-rene-haas-dismisses-ai-compute-bubble-fears). 인용: "People who are questioning whether the AI demand is a bubble or the AI demand tops out, it makes no sense to me" → "AI 수요가 버블인지, 정점을 찍었는지 묻는 사람들의 말은 제게 말이 안 됩니다." **10월 발언은 찾지 못했다.** 자체 칩 판매 전략은 [Stratechery 인터뷰](https://stratechery.com/2026/an-interview-with-arm-ceo-rene-haas-about-selling-chips/)를 참고(날짜 미확인).
- AMD Su, Advancing AI 2026(약 2026-08 추정): AI TAM을 2030년 약 2조 달러로 상향했다. MI450·Helios 수요가 당초 예상을 넘는다고 했다 — [Futurum](https://futurumgroup.com/insights/advancing-ai-2026-does-amd-now-build-the-worlds-best-cpus-and-gpus/). OpenAI 6GW 계약(2025-10)과 Meta 6GW 딜(2026-03 보도)은 배경 맥락이다 — [Daily Political](https://www.dailypolitical.com/2026/03/07/advanced-micro-devices-ceo-lisa-su-teases-mi450-ramp-6gw-meta-ai-deal-and-35-growth-target.html)

### Inferences
- 10월 반도체 리더 발언의 공통 구조는 "기술 수요는 견조, 금융은 불안"이다. 버블 논쟁의 축이 '수요가 있나'에서 '누가 돈을 대고 언제 회수하나'로 옮겨 갔다.
- TSMC·SK hynix·Intel 모두 공급 부족을 말한다. 따라서 하이퍼스케일러 capex 집행이 늦어지는 것(Microsoft)은 수요 둔화가 아니라 공급 지연 때문일 가능성이 크다. 다만 금융 경색이 길어지면 네오클라우드(CoreWeave 등) 쪽 주문부터 흔들릴 수 있다.
- 메모리 가격 급등은 PC·스마트폰 등 소비자 부문을 압박한다(Intel CCPG 약세). 'AI가 다른 IT 수요를 잠식'하는 효과가 실적으로 확인되고 있다.

### Gaps
- Lisa Su(AMD)의 10월 공개 발언과 AMD Q3 실적(11-03~04 예상)은 기간 내에서 확인하지 못했다.
- Rene Haas(Arm)의 10월 발언은 찾지 못했다. Arm 실적(통상 11월 초)도 기간 밖으로 보인다.
- TSMC 콜 전사록 원문을 직접 읽지 못했다(fool.com 차단). 연간 capex 수치, CoWoS 증설, 애리조나 관련 발언, 정확한 Q4 매출·마진 가이던스는 확인하지 못했다.
- Jensen Huang의 10월 인터뷰 원문 전체(버블 관련 정확한 문구)는 확보하지 못했다. 장소(스톡홀름/베를린/런던)도 출처마다 다르다.

## Q2. 인프라·클라우드 플레이어(Oracle, CoreWeave, OpenAI 연관)는 무엇을 말했고 시장은 어떻게 반응했나

### Takeaway
10월은 '네오클라우드·OpenAI 연계 신용 리스크'가 터진 달이었다. OpenAI 연환산 매출이 680억 달러가 아니라 약 500억 달러로 정정되자(10-08) Oracle·CoreWeave가 급락했다. CoreWeave의 CDS는 사상 최고를 찍었다. Oracle은 AI World(10-27)에서 Google TPU 등 비NVIDIA 가속기 수용을 발표했다.

### Cited Findings

#### [7] OpenAI 매출 정정 쇼크 — 2026-10-08(목)
- URL: [CNBC](https://www.cnbc.com/2026/10/08/open-ai-revenue-nvidia-oracle-coreweave.html), [Yahoo: OpenAI corrects to $50B](https://finance.yahoo.com/markets/stocks/articles/openai-corrects-annualized-revenue-figure-183756345.html), [Admiral Markets](https://admiralmarkets.com/analytics/traders-blog/openai-revenue-ai-selloff-october-2026)
- 내용:
  - OpenAI는 투자자들에게 9월 말 연환산 매출이 약 **500억 달러**라고 밝혔다. 9월 말 널리 보도된 680억 달러보다 낮다. FT가 처음 보도했고 CNBC가 확인했다.
  - 680억 달러에는 파트너 경유 총매출(gross)이 포함돼 있었다고 한다(Anthropic과 비교하기 쉽게 하려는 목적이었다는 관계자 설명).
  - OpenAI 투자자 자료: Q3 run-rate 성장률 +77%, 엔터프라이즈 부문 +107%.
- 주가: NVIDIA -3%, Oracle 약 -6%(매체별 -5~-6%), CoreWeave 약 -8%. AMD·Broadcom·Intel·SMCI도 하락했고 나스닥은 장중 -1.4%. 유가와 국채금리 상승도 함께 영향을 줬다.
- 시사점: Oracle은 클라우드 백로그의 상당 부분이 OpenAI 계약에 묶여 있다. 그래서 OpenAI 매출 수치 하나가 인프라 체인 전체의 밸류에이션을 흔드는 '단일 고객 리스크'가 드러났다.

#### [8] CoreWeave — 주가 급락, CDS 사상 최고, CEO 메모
- URL: [CNBC 10-19](https://www.cnbc.com/2026/10/19/coreweave-oracle-ai-credit-stress.html), [Taipei Times 10-18](https://www.taipeitimes.com/News/biz/archives/2026/10/18/2003866187), [TheStreet](https://www.thestreet.com/investing/stocks/coreweave-oracle-interest-rate-problem-ai-debt), [24/7 Wall St. 10-27](https://247wallst.com/investing/2026/10/27/ai-cloud-stocks-rise-as-coreweave-adds-denmark-capacity-coreweave-and-nebius-climb-4-oracle-ticks-up/)
- 내용:
  - 10-14 주가 -15.5%, 그 전 주에 -24%. 10-15 CDS 1,194.5bp로 사상 최고(Q1 [3] 참조).
  - 회사채 수익률은 약 15% 근처에 머물렀다(CNBC 10-19 제목).
  - 10-27 덴마크 용량 추가 발표 후 CoreWeave·Nebius 약 +4%.
- 인용(CEO Mike Intrator 메모): "We are confident in our backlog which more than supports all of our debt obligations." → "우리는 백로그에 자신이 있으며, 백로그는 모든 부채 상환 의무를 충분히 뒷받침하고도 남습니다."
- 시사점: 칩 수요 자체보다 GPU 담보 부채 구조의 금리 민감도가 네오클라우드의 핵심 리스크로 부각됐다. Hock Tan·Lip-Bu Tan의 '자본 병목' 발언과 같은 맥락이다.

#### [9] Oracle — AI World 2026 (라스베이거스 추정), 2026-10-27 전후
- URL: [Tech-Insider: Google TPU on OCI](https://tech-insider.org/ca/oracle-oci-google-tpu-ai-accelerators-nvidia-2026), [HPCwire/AIwire 10-28](https://www.hpcwire.com/aiwire/2026/10/28/oracle-advances-enterprise-security-for-the-ai-era/)
- 내용:
  - 2027년부터 자사 데이터센터에서 **Google TPU를 임대**한다. 그 외 비NVIDIA 가속기 4개 계열도 함께 도입할 계획이다.
  - OpenAI 모델·ChatGPT·Codex를 Oracle 앱, 엔터프라이즈 데이터, OCI와 새 Oracle AI Workspace에 통합한다.
  - xAI Grok 4.6/4.7을 OCI에서 온디맨드 추론으로 제공한다.
  - 10-28: OpenAI 기반 "Oracle AI Security Mesh"를 발표했다.
- 신용 맥락:
  - S&P는 7월 Oracle 신용등급을 BBB-(투기등급 바로 위)로 낮췄다.
  - S&P는 FY2027 FCF 적자를 420억 달러로 추정한다. 총부채는 1,670억 달러다(2차 출처 경유, Investing.com 인용).
- 시사점: Oracle은 NVIDIA 단일 의존에서 벗어나 멀티 가속기 전략으로 간다. 동시에 높은 레버리지 때문에 OpenAI 매출 정정 같은 뉴스에 가장 민감한 종목이 됐다.
- 참고: 경영진(Clay Magouyrk·Mike Sicilia 공동 CEO 체제로 추정)의 직접 인용은 확보하지 못했다.

#### [10] Anthropic IPO 맥락 — CNBC 2026-10-31
- [CNBC: "Anthropic's path to the Nasdaq just got a lot bumpier"](https://cnbc.com/2026/10/31/anthropic-ipo-ai-spending.html). 제목만 확인했고 내용은 미확인. 10월 AI 지출 공포가 AI 랩의 IPO 경로에도 부담을 줬다는 취지로 보인다.
- 'OpenAI가 자금조달 목표를 100억 달러로 줄였다'는 BigGo 보도도 있으나 단일 2차 출처라 검증하지 못했다 — [BigGo](https://finance.biggo.com/news/451544c8-6a25-43b4-9cf5-d891a313da76)

### Inferences
- 10월 AI 매도세의 진원지는 반도체가 아니라 'OpenAI 매출 → Oracle/CoreWeave 부채 → 하이퍼스케일러 FCF'로 이어지는 금융 사슬이었다.
- NVIDIA(지분 투자자이자 공급자)가 CoreWeave를 공개적으로 옹호한 것은 공급망 안의 상호 의존(순환 금융)이 시장 리스크 요인으로 인식되고 있다는 증거다.

### Gaps
- Oracle 경영진의 AI World 키노트 직접 인용, OCI RPO 최신 수치(10월 시점)는 확보하지 못했다.
- CoreWeave Q3 실적(통상 11월 중순)은 기간 밖이다.
- CNBC 원문을 직접 읽지 못해 Oracle 채권 수익률 수치를 확인하지 못했다.

## Q3. 투자자·애널리스트(Goldman Sachs, Morgan Stanley, JPMorgan, a16z, Sequoia 등)는 AI 버블·capex를 어떻게 봤나

### Takeaway
월가는 대체로 "버블이라기보다 밸류에이션 조정"이라는 입장이다. Goldman은 AI capex가 GDP 대비 역사적 범위 안에 있다고 본다. 다만 2027년 capex 전망치가 1조 달러를 넘으면서 ROI·부채 의존 리스크에 대한 경고가 커졌다. a16z·Sequoia의 10월 발언은 찾지 못했다.

### Cited Findings
- **Reuters(2026-10-30)**: 나스닥100은 10월 한 달 시총 **2조 달러 넘게 증발**할 전망이었다(월간 -5.8% 이상). 계기는 Alphabet의 하루 약 -12.6%(시총 약 5,000억 달러 증발)였다. AI 인프라 관련 우발채무(contingent commitments)가 분기 사이 230억 달러 늘었고 검색 광고 매출이 예상에 못 미쳤다. **JPMorgan: 2026년 글로벌 AI capex 9,000억 달러. Morgan Stanley: 2027년 1조 달러 돌파.** AI 기업의 부채 조달 의존이 새 리스크로 떠올랐다 — [Investing.com/Reuters](https://www.investing.com/news/stock-market-news/nasdaq-faces-2-trillion-wipeout-in-october-as-ai-spending-fears-deepen-4988211), [Korea Times](https://www.koreatimes.co.kr/world/20261031/nasdaq-faces-2-trillion-wipeout-in-october-as-ai-spending-fears-deepen), [Globe and Mail](https://www.theglobeandmail.com/investing/article-nasdaq-faces-2-trillion-wipeout-in-october-as-ai-spending-fears-deepen/)
- **Goldman Sachs "Tracking Trillions"**(날짜 미확인, 기간 내라고 단정할 수 없음):
  - AI capex 비중은 미국 GDP 대비 2026년 1.8%, 2027년 2.5%, 2028년 2.8%. 과거 기술 투자 붐(2~5%) 범위 안이다.
  - Eric Sheridan: AI 수급 균형은 2028년 상반기에야 올 것.
  - 2026년 AI capex 기준치 7,650억 달러 — [Goldman Sachs](https://www.goldmansachs.com/insights/articles/tracking-trillions-the-assumptions-shaping-scale-of-the-ai-build-out)
- **Goldman(2026-09-24 노트, 기간 직전, aggregator 단일 출처)**: 하이퍼스케일러가 2026~27년 capex를 손익분기하려면 연 약 3,000억 달러의 AI 매출이 필요하다 — [aieatingtheworld](https://www.aieatingtheworld.com/articles/ai-bubble-2026-data-warning-signs-burst-forecasts). 검증하지 못했다.
- **Goldman 9월 전망**: 2027년 하이퍼스케일러 capex 약 1.14조 달러. 컨센서스 표는 약 9,345억 달러 — [CNBC 10-29 경유 검색 요약](https://www.cnbc.com/2026/10/29/microsoft-google-ai-capex-estimates.html)
- **Morgan Stanley "Following AI's $1.6 trillion Money Trail"**: 2026년 capex를 9,780억 달러로, 2027년을 1.6조 달러로 상향했다는 2차 요약이 있다. 그러나 원문은 확인하지 못했고 날짜도 불명이다 — [MacIver Institute](https://www.maciverinstitute.com/research/theres-no-denying-the-ai-bubble-now) (버블론 쪽 성향이 있는 출처)
- **"Goldman: S&P500이 2026년 말 8,250에서 2027년 말 6,500으로 -21%" 주장**: Fortune을 인용한 2차 출처뿐이라 신뢰도가 낮다. 확인하지 못했다 — [useluminix](https://www.useluminix.com/reports/industry-analysis/when-will-the-ai-bubble-burst)
- **DBS CEO 탄수산(10-12)**: 시장이 AI 금융 리스크를 다시 가격에 반영하고 있으며, 이는 금융 규율 강화로 이어질 것 — [The Edge Singapore](https://www.theedgesingapore.com/news/tech/dbs-ceo-tan-says-market-repricing-risks-ai-financing)
- **Michael Burry**: NVIDIA 숏을 확대했다(약 9월 보도, 기간 경계) — [BeInCrypto](https://beincrypto.com/nvidia-ceo-ai-production-ramp/)

### Inferences
- 10월 시장의 메시지는 "AI capex를 줄이라"가 아니라 "FCF가 마이너스가 될 만큼 쓰는 데 대한 프리미엄 축소"다. Alphabet·Meta는 FCF가 마이너스가 되자 급락했고, Microsoft는 FCF를 플러스로 유지했다(Q4 참조). 시장은 같은 지출이라도 자금 출처와 회수 가시성에 따라 차별화하고 있다.
- 전망치 범위가 매우 넓다(2026년 7,300억~9,780억 달러). 이는 범위 정의(하이퍼스케일러만인지 글로벌 전체인지, 현금 capex인지 리스 포함인지) 차이 때문이다. 보고서를 쓸 때 출처별 정의를 함께 표기해야 한다.

### Gaps
- a16z, Sequoia의 2026년 10월 AI 버블·capex 관련 공개 글이나 팟캐스트는 이번 검색에서 찾지 못했다. 이 부분은 별도 조사가 필요하다.
- Goldman·Morgan Stanley 10월 리포트 원문, 그리고 발행일이 기간 내인지는 확인하지 못했다.

## Q4. 시장 맥락 — 하이퍼스케일러 capex, 전력 제약, HBM/메모리, 데이터센터 딜 (수치)

### Takeaway
Q3 실적 시즌(10-21~10-29)에 Amazon(2026년 약 2,200억 달러)과 Meta(1,350~1,450억 달러)는 가이던스를 유지하거나 하단을 올렸다. Microsoft는 GPU 공급 지연으로 2026년 가이던스를 오히려 소폭 낮췄고, Alphabet은 동결했다. 네 회사 모두 2027년 '대폭 증가'를 시사했다. 2026년 빅4 합계는 약 7,200억~7,450억 달러다. 전력·메모리는 다년간 병목으로 굳어졌다.

### Cited Findings

#### 하이퍼스케일러 Q3 실적·capex
- **Amazon (2026-10-29, 목)** — [Amazon IR](https://ir.aboutamazon.com/news-release/news-release-details/2026/Amazon-com-Announces-Third-Quarter-Results/default.aspx), [About Amazon: Jassy](https://www.aboutamazon.com/news/company-news/aws-growth-ai-demand-q3-2026-earnings), [Constellation](https://www.constellationr.com/insights/news/aws-q3-revenue-growth-surges-39-capex-stings-amazons-cash-flow), [DataStudios](https://www.datastudios.org/post/amazon-q3-2026-results-aws-39-percent-growth-46-billion-220-billion-capex)
  - AWS 매출 460억 달러(+39.3%). 6분기 연속 가속으로 약 5년 만에 가장 빠른 성장. AWS 영업이익 178억 달러(마진 38.7%). AWS 백로그 **5,780억 달러**(전년 대비 세 자릿수 % 증가).
  - 전사 매출 2,019억 달러(+12%), 영업이익 281억 달러(마진 13.9%, 사상 최고).
  - Q3 현금 capex 759억 달러(PP&E 매입 기준으로는 772.6억 달러, 정의 차이). 2026년 capex 약 **2,200억 달러** 유지, 2027년 "의미 있는 증가".
  - EPS 1.89달러(예상 1.97달러), 시간외 주가 -7% 넘게 하락.
  - Jassy 인용: AWS는 "projected revenue growth rates of over 40% both in 2027 and in 2028" → "2027년과 2028년 모두 40%를 넘는 매출 성장률을 예상한다"
- **Alphabet (2026-10-28, 수)** — [CNBC 10-28](https://www.cnbc.com/2026/10/28/alphabet-googl-earnings-q3-2026.html), [CNBC 10-29](https://www.cnbc.com/2026/10/29/microsoft-google-ai-capex-estimates.html)
  - 2026년 capex 가이던스 **1,950~2,050억 달러 동결**. 실적·매출 모두 예상에 못 미쳤다.
  - FCF는 마이너스(-90억 달러 이상). 2004년 IPO 이후 첫 마이너스라는 보도도 있으며, 수치는 -59억~-90억 달러로 출처마다 다르다.
  - 시간외 약 -10%, 다음 날 약 -12.6%.
  - CFO Anat Ashkenazi 인용:
    - 외부 컴퓨팅 파워가 "came online only at the very end of Q3" → "3분기 맨 마지막에야 가동됐다"
    - "We continue to expect our capex to increase significantly in 2027, and will provide further details on our Q4 call." → "2027년 capex는 계속 대폭 증가할 것으로 예상하며, 세부 내용은 4분기 콜에서 제시하겠다."
  - 일부 출처는 2026년 가이던스를 1,750~1,850억 달러나 약 1,700억 달러로 표기했다. CNBC의 1,950~2,050억 달러가 가장 신뢰할 만하다.
- **Microsoft (FY27 Q1, 2026-10-28 또는 10-29 발표)** — [CNBC 10-29](https://www.cnbc.com/2026/10/29/microsoft-google-ai-capex-estimates.html), [Gokhshtein](https://gokhshtein.com/news/2026-10-30-microsoft-cuts-ai-capex-5b-as-gpu-delays-show)
  - 2026년(연간) capex 전망을 **1,750억 달러에서 1,700억 달러로 하향**(CNBC). 다른 출처는 "약 1,900억 달러에서 약 1,750억 달러로, 회계 변경 때문"이라고 보도해 수치가 엇갈린다.
  - CFO Amy Hood: 서드파티 AI 칩 공급업체가 지연돼 일부 용량이 2027년 상반기로 밀렸다. 2027년 상반기에 부품 단가 상승과 납기 지연 때문에 capex가 다시 늘 것이다.
  - FCF 186억 달러(플러스지만 2분기 연속 크게 감소).
  - 상업용 RPO: 6,270억 달러(+99%)라는 출처와 6,770억 달러라는 출처가 엇갈린다 — [404K Research](https://404kresearch.substack.com/p/big-tech-q3-capex-deep-dive-2027)
  - FY27 capex 2,550~2,600억 달러라는 수치는 회사 가이던스가 아니라 애널리스트 프리뷰다(인용 금지).
- **Meta (2026-10-21 발표로 보도, 주가 반응은 10-22 목)** — [Tech-Insider](https://tech-insider.org/meta-34-91b-capex-vs-google-search-12-percent-2026/), [Global Data Center Hub](https://www.globaldatacenterhub.com/p/meta-q3-2026-earnings-capex-cash-equity-raise), [StockTitan](https://www.stocktitan.net/articles/meta-q3-2026-earnings-results)
  - 매출 646억 달러(+26%, 사상 최고). Q3 capex 349.1억 달러가 영업현금흐름 327.9억 달러를 넘어 FCF는 -21.2억 달러.
  - 2026년 capex 가이던스를 **1,350~1,450억 달러**로 좁혔다(하단을 1,300억에서 상향). 2027년 가이던스는 없다(외부 추정 약 2,500억 달러).
  - 무의결권 Class C 주식을 신설했고, 10-22 주가 -7.84%(648.85달러).
  - Zuckerberg: 이번 분기는 "a major milestone toward personal superintelligence for everyone" → "모두를 위한 개인 초지능을 향한 중대한 이정표"
  - 약 375억 달러 주식 매각설은 단일 출처라 미확인.
  - 실적 발표일이 10-21인지 10-28인지 확인이 필요하다(일부 검색은 10-28로 질의). 주가 반응일 10-22(목)이 요일과 맞으므로 10-21 발표가 유력하다.
- **빅4 합계**: 2026년 capex 약 7,200억~7,450억 달러 — [YieldTheory](https://www.yieldtheory.app/research/hyperscaler-ai-capex-tracker-2026), [TMT Finance](https://www.tmtfinance.com/intel/2026-hyperscaler-capex-tops-us700bn-analysis), [Tech-Insider 7,250억](https://tech-insider.org/microsoft-meta-google-ai-capex-725-billion-2026/). 클라우드 백로그 합계는 약 1.8조 달러 추정(2차 출처). 2027년은 컨센서스 약 9,345억 달러, Goldman 약 1.14조 달러, Morgan Stanley 1조 달러 이상.

#### 전력·에너지 제약
- 2026-10-30: 미시간 법무장관 Dana Nessel이 DTE Electric의 **1GW Google 데이터센터** 전력 공급 승인을 재검토해 달라고 요청했다. 요구 사항은 요금 납부자 보호 강화 또는 승인 거부다 — [Law360](https://www.law360.com/realestate/articles/2544736)
- 2026-10-15: Venture Global이 GE Vernova·Baker Hughes와 가스발전 아일랜드 최대 16기(각 720MW, 총 약 11.5GW, 컴퓨트 최대 10GW 지원) 프레임 계약을 맺었다. 인도 기간은 2028~2034년이다 — [WeTheFlywheel](https://wetheflywheel.com/en/guides/data-center-power-companies-2026/) (aggregator)
- 2026-10-22: Google이 Voltus와의 수요반응(demand response) 협력을 100MW에서 약 **1GW**로 확대했다. PJM 지역 피크 시 데이터센터 부하를 줄이거나 옮기는 용도다 — [CryptoBriefing](https://cryptobriefing.com/google-demand-response-ai-data-centers/)
- 2026-10-31 보도: Alliant Energy가 이미 계약한 3.4GW(Google·Meta 등)에 더해, 6개월 안에 1GW 추가 계약을 추진한다(2029~2031년 단계적 공급) — [Whalesbook](https://www.whalesbook.com/news/English/energy/Alliant-Energy-Plans-1-GW-Data-Center-Power-Expansion/6ae55c604fc30694db55037f)
- (기간 외 맥락, 2026-08) Georgia Power–OpenAI 3.2GW 데이터센터 계약이 조지아 PSC 심사를 받았다(100MW 넘는 계약은 체결 30일 전 제출) — [The Current GA](https://thecurrentga.org/2026/08/25/psc-deadline-arrives-for-georgia-powers-3-2-gigawatt-openai-data-center-contract/)
- 참고: Hock Tan은 전력보다 자본이 더 큰 제약이라고 봤다(Q1 [1]).

#### HBM·메모리 공급
- SK hynix: 영업이익률 약 80%. DRAM·HBM은 2029년까지 사실상 완판, LTA 14곳, 2027~28년 용량의 절반 이상이 LTA로 묶였다. 부족은 2030년까지 — [TrendForce](https://www.trendforce.com/news/2026/10/28/news-sk-hynix-3q26-opm-hits-record-80-says-dram-hbm-effectively-sold-out-to-2029-14-lta-customers-signed/)
- Samsung: 잠정 영업이익 107.4조 원. HBM4 가격은 내년 약 2배. TrendForce는 2027년 HBM ASP +121%를 예상 — [서울경제](https://en.sedaily.com/finance/2026/10/08/hbm-prices-to-double-as-memory-shortage-drives-samsung)
- DRAM 평균가격은 전분기 대비 20% 후반 상승(SK hynix) — [TheNextWeb](https://thenextweb.com/news/sk-hynix-q3-2026-record-profit-memory-shortage-2030)
- 메모리 재고가 10일 미만으로 떨어졌다는 보도가 있으나 신뢰도가 낮은 출처다 — [Shattered.io](https://shattered.io/memory-chip-shortage-10-days-2026/)
- 메모리 가격 상승은 Intel PC 부문의 약세 요인이고(Q1 [4]), Microsoft capex 단가 상승 요인이기도 하다(Amy Hood).

#### 데이터센터·용량 딜 (10월)
- Oracle: 2027년부터 Google TPU를 임대하고, 비NVIDIA 가속기 4계열을 추가로 도입(10-27).
- CoreWeave: 덴마크 용량 추가(10-27).
- DBS: 2026년 AI 딜 약 S$250억 주선(10-12).
- Venture Global 11.5GW 가스발전 프레임 계약(10-15), Google–Voltus 1GW(10-22).

### Inferences
- Q3 실적의 핵심은 'capex 하향 = 수요 둔화'가 아니라는 점이다. 공급 측(GPU 납기, 메모리 단가, 전력 인허가)이 집행 속도를 정하고 있다. 2027년 capex는 네 회사 모두 '대폭 증가'로 수렴한다.
- 시장은 FCF가 마이너스로 돌아선 기업(Alphabet, Meta)을 강하게 벌주고, AWS처럼 매출 가속이 확인된 곳에도 EPS 미달이면 반응했다. 'capex → 매출' 전환 가시성이 2026년 말 주가의 핵심 변수다.
- 전력은 기술 문제에서 규제·정치 문제로 바뀌고 있다(주 법무장관의 요금 납부자 보호 요구). 그래서 2027~28년 데이터센터 가동 일정에 인허가 리스크가 추가된다.

### Gaps
- 각 하이퍼스케일러 숫자를 10-Q·IR 원문과 대조하지 못했다. 특히 Microsoft의 연간 capex(1,700억 vs 1,750억 달러), Alphabet FCF(-59억 vs -90억 달러), Microsoft RPO(6,270억 vs 6,770억 달러)는 출처마다 다르다.
- Meta 실적 발표 정확한 날짜(10-21 유력)를 1차 자료로 확인하지 못했다.
- 10월 신규 대형 데이터센터 딜(Stargate 추가 사이트, 대형 GW급 GPU 계약 등)은 이번 검색에서 체계적으로 확인하지 못했다.
- Nadella, Pichai, Jassy의 AI 관련 발언(capex 외)은 Jassy 일부 외에는 확보하지 못했다.
