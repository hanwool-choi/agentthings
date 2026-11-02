# AI 반도체·인프라·투자 리더 발언 및 시장 맥락 — 원문 검증판 (2026-10-02 ~ 2026-11-02)

> **검증 방법과 한계 (먼저 읽을 것)**
> - 출발점은 이전 노트(`AI 리더 트렌드 발언 2026년 10월/chips_infra_market.md`)다. 그 노트의 모든 항목을 다시 확인했다. 원본 파일은 수정하지 않았다.
> - **네트워크는 일부만 열려 있었다.** 직접 본문을 읽은 곳은 다음뿐이다.
>   - **1차 자료**: microsoft.com IR(FY27 Q1 보도자료, 컨퍼런스콜 전사록), oracle.com/news(AI World 보도자료 3건)
>   - **원문 기사 전문**: thenextweb.com(TNW, 대부분 Reuters·Bloomberg·FT·CNBC를 인용·재정리), techcrunch.com, finance.yahoo.com 기사 1건(Quartz 기사)
> - **접근하지 못한 곳**
>   - 프록시가 차단: sec.gov, cnbc.com, bloomberg.com, reuters.com, trendforce.com, investing.com, investor.oracle.com, intc.com, thestar.com.my 등
>   - 봇 차단(403): investor.tsmc.com, abc.xyz, investor.atmeta.com
>   - 요청 한도 초과(429): finance.yahoo.com 전사록 페이지들
>   - WebFetch: 모든 외부 도메인에서 DNS 해석 실패
>   - **sec.gov, ir.aboutamazon.com, investor.tsmc.com, abc.xyz, investor.atmeta.com, cnbc.com, reuters.com 접근을 세션 네트워크 설정에서 허용해야 완전한 1차 검증이 가능하다.**
> - **표기 규칙**
>   - **✅검증**: 1차 자료나 원문 기사 전문을 직접 읽고 확인함
>   - **✅검증(간접)**: 1차 문서(SEC 6-K/8-K/10-Q, IR 전사록)의 해당 수치를 검색엔진이 발췌해 보여 줬지만 본문은 직접 열지 못함
>   - **⚠️수정**: 이전 노트의 값이 틀렸거나 부정확함 → 바른 값을 적음
>   - **❌확인불가**: 원문을 찾지 못했거나 접근하지 못함
> - 요일 대조: 10-08(목), 10-12(월), 10-14(수), 10-15(목), 10-21(수), 10-22(목), 10-27(화), 10-28(수), 10-29(목), 10-30(금), 10-31(토).

---

## Q1. 반도체 리더(NVIDIA·TSMC·Intel·Broadcom·AMD·Arm·메모리)는 이 기간에 무엇을 말했나

### Takeaway
반도체 리더들은 기간 내내 "수요가 공급보다 크다"고 말했다(TSMC Wei, Broadcom Hock Tan, Intel Lip-Bu Tan, SK hynix). 다만 화제의 중심은 세 가지로 옮겨 갔다.
- **자본(자금조달)과 ROI**: Hock Tan·Lip-Bu Tan(10-12)
- **메모리 가격 급등이 소비자 기기 수요를 깎는 문제**: TSMC Wei의 "2027년 신중", Intel Q4 가이던스 쇼크(10-29)
- **신용 리스크**: NVIDIA Huang의 CoreWeave 옹호(10-15)

NVIDIA는 10월 중순 유럽 순방을 했다. 일정은 파리(10-12) → 스톡홀름(10-15) → 베를린 Invest in Germany Summit(10-19)·GTC Berlin 키노트(10-21)였다. 이전 노트는 GTC Berlin을 놓쳤다. AMD는 OCP Summit(10-12)과 Meta 지분투자(10-27)로 기간 안에 공개 발언이 있었다. Arm Rene Haas의 기간 내 발언은 이번에도 찾지 못했다.

### Cited Findings

#### [1] Broadcom Hock Tan · Intel Lip-Bu Tan — DBS Asia Future Forward Conference(싱가포르), 2026-10-12(월)
- 날짜·장소 ✅검증. TNW 기사(2026-10-13 게재)에 "spoke on Monday at the DBS Asia Future Forward Conference in Singapore"라고 나온다. 패널 주제는 "다음 1조 달러는 어디서 오나"였고, 사회는 DBS CEO 탄수산(Tan Su Shan)이 봤다 — [TNW](https://thenextweb.com/news/broadcom-hock-tan-ai-investors-casino-capital)
- 이전 노트 URL(CNBC·Quartz·Edge Singapore)은 이번에도 접근하지 못했다. TNW가 Bloomberg·CNBC·Business Times·Reuters 보도를 종합한 내용으로 확인했다.
- 인용 검증:
  - ✅ Hock Tan: "What I think might be the biggest constraint is capital." → "가장 큰 제약은 아마 자본일 것이라고 생각합니다."
  - ✅ Hock Tan: "A lot of investors have no clue what they are investing in." → "많은 투자자들은 자신이 무엇에 투자하는지 전혀 모릅니다."
  - ✅ (신규) Hock Tan: 투자자들이 "set very extreme expectations only to find out that it's almost like they are in a casino" → "극단적인 기대를 걸었다가, 거의 카지노에 있는 것과 같다는 걸 알게 된다"
  - ✅ (신규) Hock Tan: "People are just wasting money, spending tokens, trying to understand (AI)." → "사람들은 AI를 이해하려고 토큰을 쓰면서 그냥 돈을 낭비하고 있습니다." 그는 기업 현실을 10분 만에 10달러를 쓰고 아무것도 못 배우는 오락실 아이에 비유했다. "That's what's happening in enterprises today." → "그게 오늘 기업에서 벌어지는 일입니다."
  - ✅ Lip-Bu Tan: "If there's any challenge in the front, it's capital and the cost of capital." → "앞에 놓인 과제가 있다면 자본과 자본비용입니다." 장기적으로는 사람들이 ROI를 보고 싶어 한다고 덧붙였다. 이 부분은 기사에서 간접 인용이다.
  - ⚠️수정: "There is more demand for compute infrastructure than we can supply"는 원문 따옴표 인용으로 확인되지 않았다. TNW는 "demand for computing infrastructure still outstrips supply"(컴퓨팅 인프라 수요가 여전히 공급을 넘는다)라고 **간접 인용**했다. 그 상태가 2029년, 어쩌면 2030년까지 갈 수 있다고 했다.
- 신규 포인트(✅, 같은 출처):
  - Hock Tan은 웨이퍼 부족이 2028~2029년에 풀린다고 봤다.
  - Hock Tan은 AI의 미래 가치가 "picks and shovels"(하드웨어 공급자)보다 프론티어 모델 개발사에 있다고 했다.
  - Hock Tan은 OpenAI의 9월 연환산 매출 500억 달러가 스타트업으로서 "by itself, not that bad"(그 자체로는 나쁘지 않다)라고 평가했다.
  - Lip-Bu Tan은 앞으로 2~3년간 의미 있는 둔화가 없다고 봤다.
  - Lip-Bu Tan은 중국 프론티어 모델(DeepSeek·Kimi·GLM)이 "good enough"(충분히 좋다)이고, 낮은 토큰 비용 덕에 채택 속도가 "very fast"(매우 빠르다)라고 했다(Reuters 인용).
  - 시장 반응: 다음 날(10-13) 아시아 반도체주가 급락했다. KOSPI 장중 -7% 이상, 삼성전자 -9%, SK hynix -10%(Business Insider 인용).
  - 일론 머스크는 X에 "No crying in the casino"라고 썼다.
- ❌확인불가: DBS가 올해 AI 딜 약 S$250억을 주선했다는 내용과 탄수산의 "리스크 재가격 반영" 발언(The Edge Singapore). 원문에 접근하지 못했다.
- 시사점: 칩 공급자 CEO가 "공급 부족"과 "투자자 과열·기업 ROI 부재"를 한 무대에서 동시에 말했다. 버블 논쟁의 축이 수요에서 자본과 수익화로 옮겨 갔음을 보여 준다.

#### [2] TSMC C.C. Wei — Q3 2026 실적 컨퍼런스콜, 2026-10-15(목)
- URL: [TNW(10-17)](https://thenextweb.com/news/tsmc-q3-2026-record-profit-prudent-2027), [TSMC 6-K 보도자료(SEC)](https://www.sec.gov/Archives/edgar/data/0001046179/000104617926000726/a3q26e_withguidancexfinal.htm), [TSMC 6-K 프레젠테이션(SEC)](https://www.sec.gov/Archives/edgar/data/0001046179/000104617926000726/a3q26presentatione.htm), [TSMC 공식 전사록 PDF](https://investor.tsmc.com/english/encrypt/files/encrypt_file/reports/2026-10/eba4fac72873bf546b669bd2b5d973df5c93215d/TSMC%203Q26%20Transcript.pdf)(403으로 접근 실패), [Yahoo 전사록](https://finance.yahoo.com/quote/TSM/earnings/TSM-Q3-2026-earnings_call-709077.html)(429로 접근 실패)
- 날짜: 콜 일자는 ✅검증(간접)이다. 판단 근거는 세 가지다.
  - 이전 노트의 전사록 URL 경로가 2026/10/15다.
  - TNW에 "ASML 실적 하루 뒤"라는 서술이 있다.
  - 10-15가 목요일로 요일이 맞는다.
- 숫자 검증:
  - ✅ Q3 매출 **467.2억 달러**(+41.2% YoY). 대만달러 기준은 NT$1.49조(+51%) — TNW. ✅검증(간접): +16.2% QoQ(SEC 6-K 발췌).
  - ✅ 순이익 NT$7,631억(약 235.9억 달러, +69%), LSEG 추정 NT$7,463억 상회, 6분기 연속 사상 최고 — TNW
  - ✅ 영업이익률 58.7%, HPC 비중 68%, 스마트폰 21%, 3nm 웨이퍼 매출 비중 33% — TNW
  - ✅검증(간접): 매출총이익률 66.4%, 희석 EPS NT$29.43(SEC 6-K 발췌)
  - ✅ Q4 매출 가이던스 **523~543억 달러**(전년 337.3억 달러) — TNW. ✅검증(간접): Q4 매출총이익률 65~67%, 영업이익률 56.5~58.5%(SEC 프레젠테이션 발췌).
  - ✅ "Q4 YoY 약 +58%"는 계산으로 맞다. 가이던스 중간값 533억 ÷ 337.3억 = +58%.
  - ⚠️수정: 2026년 연간 달러 기준 성장률 전망은 **약 44%로 상향**됐다. 직전 분기 표현은 "40% 초반"이 아니라 "**more than 40%**(40% 이상)"이었다 — TNW
  - ✅ (신규) 2026년 capex **600~640억 달러 유지**. CFO Wendell Huang은 2026~2028년 capex가 직전 3년보다 "significantly higher"(상당히 많을 것)라고 했다 — TNW
  - ✅ (신규) 타이난에 3nm 팹을 하나 더 짓는다(2028년 상반기 양산, The Information 인용). 애리조나 2공장은 건설을 마쳤고 2027년 3분기 양산으로 앞당겨졌다. 텍사스 캠퍼스를 검토 중이며, 미국 데이터센터 건설·전력 상황을 직접 점검하는 팀을 보낸다(Bloomberg 인용) — TNW
  - ✅검증(간접): AI 가속기 매출이 2024~2029년 CAGR "50% 중후반"이라는 기존 전망을 넘을 수 있다. CPU는 이 가속기 정의에 들어가지 않는다(Yahoo/Zacks 발췌).
  - ❌확인불가: 북미 고객 비중 79%, 수주잔고 미제시 지적
  - ⚠️수정: "실적이 예상을 넘었는데도 주가 하락"은 시점이 다르다. TNW 기준으로 대만 상장 주식은 **실적 발표 전에** 2% 하락 마감했다. 연준 추가 금리인상 우려에 따른 기술주 동반 약세였다. 실적 후 AI 반도체주가 매도됐다는 서술은 Investing.com(Yahoo 경유) 발췌에만 있다.
- 인용:
  - ✅ C.C. Wei: "Looking ahead, we continue to observe consumer and price-sensitive end-markets segments are being challenged due to the impact of rising component prices and macroeconomic uncertainties. As such, we are being prudent in our business planning going into 2027." → "앞으로도 소비자용·가격 민감 시장은 부품 가격 상승과 거시경제 불확실성의 영향으로 어려움을 겪을 것으로 봅니다. 그래서 2027년 사업 계획은 신중하게 세우고 있습니다." (**이전 노트에서 빠진 핵심 발언**)
  - ✅ C.C. Wei: "We have no intention to leave food on the table for others, and we want to capture every piece of business possible." → "남에게 남겨 줄 몫은 없습니다. 가능한 모든 사업 기회를 잡고 싶습니다." 테라팹(Terafab) 제휴를 하더라도 팹은 TSMC가 운영해야 한다는 맥락에서 나온 말이다.
  - ✅검증(간접): 첨단 공정 수요가 "extremely robust"(극도로 견조하다). "the gap between demand and supply are still quite big"(수요와 공급의 격차는 여전히 상당히 크다)는 Yahoo 요약 발췌로만 확인했다. TNW도 Reuters를 인용해 "demand still far exceeds its supply capacity"(수요가 여전히 공급능력을 크게 넘는다), "AI mega trend"에 둔화 신호가 없다고 썼다.
- 시사점: AI 수요(HPC 68%)에는 낙관을 유지했다. 반면 부품(메모리) 가격 상승이 소비자 시장을 짓누른다는 이유로 **2027년 계획을 '신중'하게 잡았다**. 같은 메시지가 이후 Intel(10-29)과 Microsoft Windows OEM 부진으로 이어졌다.

#### [3] NVIDIA Jensen Huang — 유럽 순방(파리 → 스톡홀름 → 베를린), 2026-10-12 ~ 10-22
- **(a) 파리, 2026-10-12(월)** ✅검증 — [TNW(10-13)](https://thenextweb.com/news/nvidia-huang-europe-2-billion)
  - 한 주 안에 유럽 투자 20억 달러를 발표하겠다고 했다. 지난 1년간 이미 80억 달러를 투자했다(Bloomberg 인용).
  - 프랑스 스타트업 4곳(Doctolib, Genesis AI, Pigment, Entalpic)에 투자한다.
  - 인용: "Europe needs to get in the race." → "유럽도 경쟁에 뛰어들어야 합니다."
  - 오픈소스 모델이 더 싸고, 언어별·주권(sovereignty)에 맞게 커스터마이즈할 수 있다고 강조했다.
- **(b) 스톡홀름, 2026-10-15(목) Bloomberg 인터뷰** ✅검증 — [TNW(10-15)](https://thenextweb.com/news/huang-coreweave-backstop-stockholm), [Bloomberg 영상](https://www.bloomberg.com/news/videos/2026-10-15/huang-downplays-coreweave-concern-after-risk-gauge-soars-video)(접근 실패)
  - **장소 논란 해소**: TNW는 "Jensen Huang said in Stockholm on Thursday"라고 썼다. 베를린·런던 설은 틀렸다. 베를린은 10-19~22 별도 일정이다.
  - 인용 ✅: "CoreWeave's strength is improving every day. I'm optimistic. Their cost of capital is actually decreasing." → "CoreWeave의 체력은 날마다 좋아지고 있습니다. 저는 낙관합니다. 그들의 자본비용은 실제로 내려가고 있습니다."
  - NVIDIA가 CoreWeave를 떠받칠(backstop) 필요가 없다고 했다.
  - ✅ 같은 날 CoreWeave 5년물 CDS가 장중 최대 74.5bp 올라 **1,194.5bp**(사상 최고, ICE Data Services)를 찍었다. 5년 안에 디폴트할 확률을 60% 넘게 반영한 수준이다. 6월에는 452bp였다.
  - ✅ NVIDIA는 CoreWeave 2대 주주로 지분 약 10%다.
  - ✅ CoreWeave 총부채는 6월 기준 약 300억 달러다. 백로그는 7월 기준 994억 달러, 2026년 capex 예산은 310~350억 달러다.
  - ✅ 같은 날 오전 NVIDIA와 Norrsken 재단이 스톡홀름 AI 랩(2027년 개소)을 발표했다.
  - ❌확인불가: 당일 CoreWeave 주가 +5.9%·$69.69 마감. TNW 본문에 없다.
  - ❌확인불가: 인터뷰어가 Emily Chang이라는 점, "AI 주가 급락은 지나갈 것" 발언. TNW에 없고, 해당 출처(AI Weekly)는 접근하지 못했다.
  - ✅ 순환 금융 논쟁: Huang은 이 논리를 "ridiculous"(터무니없다)라고 불렀다. 반면 IMF와 BIS는 시스템 리스크로 지목했다(TNW 서술).
- **(c) 베를린 Invest in Germany Summit, 2026-10-19(월)** ✅검증(신규) — [TNW(10-20)](https://thenextweb.com/news/germany-nvidia-ai-partnership-berlin-summit)
  - 독일 경제부가 NVIDIA와 피지컬 AI(로봇·기계·자동차) MOU를 맺었다. 메르츠 총리가 개막 연설에서 Huang을 직접 언급했다.
  - NVIDIA는 독일 스타트업 4곳(Agile Robots, Avelios Medical, Mirelo, Reflex Aerospace)에 투자하고 Siemens와 AI 공장 협력을 발표했다. 이는 유럽 전체 "약 100억 달러" 약정의 일부다.
- **(d) GTC Berlin 키노트, 2026-10-21(수)** ✅검증(신규) — [TNW(10-21)](https://thenextweb.com/news/huang-gtc-berlin-keynote-protest-nvidia-chips-russian-drones), [TechCrunch(10-23)](https://techcrunch.com/2026/10/23/hottest-toy-for-christmas-nvidia-ceo-plays-with-adorable-microduck-robots-20000-sell/)
  - GTC Berlin은 10-20~22에 열렸다.
  - 키노트에서 Vera Rubin 하드웨어, AI 에이전트용 OpenShell 소프트웨어, 새 데이터센터 설계, 레퍼런스 휴머노이드 로봇을 소개했다.
  - 키노트 시작 약 20분 뒤 시위대(그린피스 로고 배너)가 "러시아 드론의 NVIDIA 칩"을 문제 삼았다.
  - Huang의 대응: "All important issues, but let me get through my keynote." → "모두 중요한 문제지만, 키노트는 마치겠습니다."
  - 이전 노트의 "GTC DC는 기간 밖" 판단은 맞다. 다만 **같은 기간 안에 GTC Berlin이 있었다**는 사실이 빠져 있었다.
- 시사점: Huang은 유럽에서는 '주권 AI·오픈모델'을 팔고, 금융시장에서는 고객사(CoreWeave) 신용을 변호했다. NVIDIA가 공급자이자 주주이자 잠재 보증인이라는 '순환 구조'가 이 달 리스크 담론의 중심에 있었다.

#### [4] Intel Lip-Bu Tan — Q3 2026 실적 발표·콜, 2026-10-29(목)
- URL: [TNW(10-29)](https://thenextweb.com/news/intel-q3-2026-outlook-pc-slump-memory-shortage), [TechCrunch(10-30)](https://techcrunch.com/2026/10/30/intels-stock-crashes-knocking-12b-from-governments-stake/), [Intel 8-K(SEC)](https://www.sec.gov/Archives/edgar/data/0000050863/000005086326000188/q326earningsrelease.htm)(접근 실패), [Intel IR](https://www.intc.com/news-events/press-releases/detail/1786/intel-reports-third-quarter-2026-financial-results)(접근 실패)
- 숫자 검증:
  - ✅ 매출 165억 달러(+21%)
  - ✅ (신규) DCAI 매출 73억 달러(**+78%**). CCG(PC)는 81억 달러(-5%)
  - ✅검증(간접): GAAP EPS 0.60달러, non-GAAP 0.52달러(8-K 발췌)
  - ❌확인불가: "컨센서스 165.6억 달러에 소폭 미달", "non-GAAP EPS 컨센서스 0.41달러"
  - ✅ Q4 가이던스 매출 **150~160억 달러**(컨센서스 약 170억 달러), non-GAAP EPS **0.25달러**(컨센서스 0.43달러)
  - ⚠️(출처 간 차이) Q4 매출총이익률: TechCrunch는 "43%에서 37%로 하락", 검색 발췌는 non-GAAP 38.0%라고 했다. GAAP와 non-GAAP 차이로 보인다.
  - ✅ (신규) Intel은 PC 시장이 2026년 -12%, 2027년 -10% 줄어든다고 예상한다 — TNW
  - ✅ (신규) 주가는 시간외에서 20% 넘게 떨어졌고(Bloomberg 인용), **10-30(금) 약 -28%**로 사상 최악 수준 하락을 기록했다. 미국 정부 지분 가치가 120억 달러 줄었다 — TechCrunch
  - ❌확인불가: Diamond Rapids(18A-P) 샘플링, 14A 0.9 PDK 배포. 원문에 접근하지 못했다.
- 인용:
  - ✅ Lip-Bu Tan(Bloomberg): "Memory pricing went up a lot. I think my prediction is that in 2027 it is going to be a very severe issue to all of us." → "메모리 가격이 많이 올랐습니다. 제 예상으로는 2027년에 이게 우리 모두에게 매우 심각한 문제가 될 겁니다."
  - ✅검증(간접): Lip-Bu Tan(콜): "Year-to-date system endpoint prices have increased significantly, placing additional pressure on already limited IT budgets." → "올해 들어 완제품 시스템 가격이 크게 올라, 이미 빠듯한 IT 예산에 추가 압박을 주고 있습니다."
  - ✅검증(간접): CPU 수요는 PC 역풍에도 "remains robust"(견조하다)이며, 당장의 우선순위는 Xeon 공급 확대라고 했다.
  - ❌확인불가: "likely not fully meet"(고객 수요를 아마 완전히 충족하지 못할 것), "상반기가 하반기보다 어렵다"는 표현
  - Tan은 데이터센터 부문이 일부 원자재 부족과 이스라엘 공장 가동 중단만 없었다면 더 좋았을 것이라고 했다(✅ TNW).
- 시사점: AI 서버 CPU는 공급 부족(DCAI +78%) 상태다. 반면 메모리 인플레이션이 PC 수요를 무너뜨려 가이던스 쇼크로 이어졌다. TSMC Wei의 "2027 신중" 발언이 2주 만에 실적으로 확인된 셈이다.

#### [5] 메모리 — SK hynix Q3(2026-10-28, 수) / Samsung 잠정(10-08)·확정(10-29)
- **SK hynix** — [TNW(10-28)](https://thenextweb.com/news/sk-hynix-q3-2026-record-profit-memory-shortage-2030), [TrendForce](https://www.trendforce.com/news/2026/10/28/news-sk-hynix-3q26-opm-hits-record-80-says-dram-hbm-effectively-sold-out-to-2029-14-lta-customers-signed/)(접근 실패)
  - ✅ 매출 104.6조 원(+328%). 분기 매출이 처음으로 100조 원을 넘었다.
  - ✅ 영업이익 83.3조 원(+632%, 약 620억 달러), 영업이익률 80%
  - ✅ 순이익 39.8조 원(Q2 93.9조 원 대비 -58%). 이전 노트가 지적한 '영업이익과 반대 방향' 문제는 원인이 기사에 설명돼 있지 않다. 이번에도 미확인이다.
  - ✅ 공식 문구: "it expects the structure in which demand exceeds supply to persist through 2030" → "수요가 공급을 넘는 구조가 2030년까지 이어질 것으로 예상한다"
  - ✅ LTA 고객 14곳(대형 클라우드 포함)이 2027~2028년 생산능력의 절반 이상을 커버한다. 계약은 통상 5년이며, 고객별로 합의한 범위 안에서 시장가에 연동된다.
  - ✅ HBM4 양산 출하를 시작했다. 4분기에는 HBM4가 출하량·매출에서 HBM3E를 넘을 것으로 본다.
  - ✅ DRAM 평균가격 전분기 대비 20% 후반 상승, 서버 DDR5 출하 +40% 이상(CNBC 인용)
  - ✅ CFO 김우현: 메모리 가격 상승으로 PC·모바일 출하가 줄 것으로 예상한다(The Register 인용).
  - ✅ 2026년 주주환원은 약 100조 원이다.
  - ✅ 주가는 10-28 +10.89%였다. 다만 전날까지 6월 고점 대비 절반 넘게 하락한 상태였다.
  - ✅ CEO 곽노정: "The customer trust built through our technological competitiveness is leading to long-term contracts, and our business structure is transforming into one with earnings stability and mid-to-long term demand visibility." → "기술 경쟁력으로 쌓은 고객 신뢰가 장기계약으로 이어지고 있고, 사업 구조는 이익 안정성과 중장기 수요 가시성을 갖춘 구조로 바뀌고 있습니다."
  - ⚠️ "DRAM·HBM 2029년까지 사실상 완판"은 TrendForce 기사 제목에만 있다. TNW 원문은 "2027~28년 생산능력의 절반 이상 LTA"와 "2030년까지 공급 부족"까지만 확인된다. "CFO: 내년 HBM 물량·가격 확정" 발언은 ❌확인불가다.
- **Samsung** — [TNW(10-08)](https://thenextweb.com/news/samsung-q3-2026-record-profit-ai-memory)
  - ✅ 잠정 영업이익 약 107.4조 원(약 800억 달러, 전년 12.17조 원 대비 약 +783%). 매출 약 195조 원(+127%)
  - ✅ LSEG 추정 106.1조 원 상회, 4분기 연속 사상 최고. 한국 기업 최초로 분기 영업이익 100조 원을 넘었다.
  - ✅ 메모리 가격 상승으로 Galaxy S26 가격을 미국·한국에서 100달러 올렸다.
  - ✅검증(간접): 10-29 확정 실적. DS부문 매출 147.1조 원, 영업이익 106.5조 원. HBM4 매출이 분기 중 3배 이상 늘었다. 3분기 배당은 주당 4,601원(약 30조 원). 모바일은 적자였다 — [Korea Times](https://www.koreatimes.co.kr/business/companies/20261008/samsung-electronics-1st-korean-firm-to-top-w100-tril-in-quarterly-operating-profit), [머니투데이 영문(10-29)](https://www.mt.co.kr/en/industry/2026/10/29/2026102910001769944)(검색 발췌, 본문 미열람)
  - ❌확인불가: "HBM4 가격 내년 약 2배", "TrendForce 2027 HBM ASP +121%"(서울경제), "Q3 HBM 매출이 SK hynix 추월"(CryptoBriefing, 추정치)
  - ⚠️ 공급 타이트 지속 기간: TNW는 "into 2027"(2027년까지)이라고 썼다. 이전 노트의 "2028년까지"는 확인되지 않았다.

#### [6] AMD Lisa Su — 기간 내 발언 (신규, 이전 노트는 '없음'으로 기록)
- **OCP Global Summit(산호세), 2026-10-12** ✅검증 — [TNW(10-12)](https://thenextweb.com/news/amd-helion-agentic-rack-power), [TNW(10-28) 사진 캡션](https://thenextweb.com/news/amd-1bn-meta-equity-helios-running)
  - Lisa Su가 6세대 EPYC "Verano"를 공개했다.
  - AMD는 AI 에이전트 실행용 오픈 랙 설계 "**Helion**"을 발표했다. CPU 전용 버전은 최대 32,768코어(256코어 Venice·Zen 6 128소켓)다. 혼합 버전은 MI350P 최대 16개다. 파트너 시스템은 11월에 나온다.
  - 학습용 주력은 여전히 Helios(MI455X 72개, HBM4 31TB)다.
  - 발표의 핵심 메시지는 "와트당 에이전트 수"다. 전력 제약을 겨냥한 제품이다.
- **AMD–Meta 파트너십, 2026-10-27(화)** ✅검증 — [TNW(10-28)](https://thenextweb.com/news/amd-1bn-meta-equity-helios-running)
  - AMD가 Meta 주식 공모에 10억 달러를 투자한다. NVIDIA는 30억 달러를 약속했다(CNBC 인용).
  - 첫 Helios 랙이 Meta에서 가동 중이다. Meta는 MI450 초기 설계 고객이며, Meta 전용 커스텀 Instinct GPU를 배치할 예정이다.
  - 인용 ✅ Lisa Su: "With Helios now running at Meta, we are taking that partnership to a new scale in the superintelligence era." → "이제 Helios가 Meta에서 가동되면서, 우리는 초지능 시대에 맞게 파트너십을 새로운 규모로 키우고 있습니다."
  - 인용 ✅ Zuckerberg: "AMD has been a key partner in building out the compute that's running our frontier models." → "AMD는 우리 프론티어 모델을 돌리는 컴퓨트를 구축하는 데 핵심 파트너였습니다."
  - ✅ AMD는 2026년에 펀딩 라운드 25건에 참여했다(2022년 2건). NVIDIA는 121건이다(CNBC·Dealroom 인용).
- (기간 외 맥락) Advancing AI 2026은 7월이다(이전 노트의 "약 8월 추정"은 ⚠️ 7월로 수정) — [TechCrunch 2026-07-23](https://techcrunch.com/2026/07/23/amd-takes-on-nvidia-with-its-helios-ai-rack-scale-system/). AMD는 Anthropic에 최대 50억 달러를 투자한다(7월). OpenAI 6GW 계약은 2025-10이다 — [TechCrunch 2025-10-06](https://techcrunch.com/2025/10/06/amd-to-supply-6gw-of-compute-capacity-to-openai-in-chip-deal-worth-tens-of-billions/)
- ❌확인불가: AMD Q3 실적 발표일. 기간(11-02) 이후로 추정된다.

#### [7] Arm Rene Haas
- ❌확인불가: 2026-10-02~11-02 기간 안의 공개 발언을 찾지 못했다. 2차 검색에서도 4월(SoftBank Group International CEO 겸임 공시) 이후 새로운 발언이 나오지 않았다 — [Wikipedia](https://en.wikipedia.org/wiki/Rene_Haas)(검색 발췌)
- 7월 CNBC 버블 부정 발언(이전 노트)은 기간 외 맥락이며, 이번에 재검증하지 못했다(cnbc.com 차단).

### Inferences
- 10월 반도체 리더 발언의 공통 구조는 이전 노트의 "수요 견조, 금융 불안"에 한 가지를 더해 고쳐야 한다. **"AI 수요 견조 / 메모리 인플레이션이 비AI 수요를 잠식 / 금융 불안"의 3층 구조**다. TSMC의 2027년 신중론, Intel 가이던스 쇼크, SK hynix CFO의 PC·모바일 출하 감소 전망, Microsoft Windows OEM -27%가 모두 같은 방향을 가리킨다.
- AMD(Helion)와 NVIDIA(Vera CPU on OCI)가 같은 달에 '에이전트용 CPU'를 밀었다. AI 워크로드 무게중심이 학습에서 추론·에이전트 실행으로 옮겨 가면서 CPU 수요가 다시 늘고 있다. 이는 Intel DCAI +78%와도 맞는다.
- 칩 공급사가 고객사 지분을 사는 일이 일상이 됐다. NVIDIA 30억·AMD 10억 달러를 Meta 공모에 넣었고, NVIDIA는 CoreWeave 지분 약 10%를 갖고 있다. '순환 금융'은 비판의 대상이면서도 실제로 확대되고 있다.

### Gaps
- TSMC·Intel 콜 전사록 원문(investor.tsmc.com 403, sec.gov·intc.com 차단). Wei의 "extremely robust" 정확한 문맥과 북미 비중 79%는 미확인이다.
- Bloomberg 스톡홀름 인터뷰 영상 전체 대본. 버블 관련 정확한 문구를 확보하지 못했다.
- Arm Haas의 기간 내 발언. AMD 실적은 기간 밖이다.
- SK hynix 순이익 급감(-58%) 원인. 지분법·평가손익 등을 추정할 수 있지만 원문으로 확인하지 못했다.

---

## Q2. 인프라·클라우드 플레이어(Oracle, CoreWeave, OpenAI 연관)는 무엇을 말했고 시장은 어떻게 반응했나

### Takeaway
10월은 OpenAI 매출 정정(10-08)으로 시작해 OpenAI 펀딩 목표 축소(10-31)로 끝났다. 그 사이 CoreWeave 신용 스트레스(CDS 사상 최고 10-15)가 있었다. Oracle은 AI World(10-27, 라스베이거스)에서 **Google TPU 도입과 NVIDIA Vera Rubin 멀티GW 확장**을 함께 발표했다. 이어 Investor Day(10-28)에서 "FY28 하반기 FCF 흑자 전환, FY29 FCF 300억 달러+, 신규 조달 200억 달러 상한"을 제시해 주가가 장중 최대 +14% 올랐다. 이전 노트에 있던 "비NVIDIA 가속기 4계열" 주장은 1차 자료로 확인되지 않았다.

### Cited Findings

#### [8] OpenAI 매출 정정 쇼크 — 2026-10-08(목)
- URL: [Yahoo/Quartz(10-08)](https://finance.yahoo.com/markets/stocks/articles/openai-corrects-annualized-revenue-figure-183756345.html), [TNW(10-09)](https://thenextweb.com/news/openai-revenue-70bn-year-end-50bn-september), [CNBC](https://www.cnbc.com/2026/10/08/open-ai-revenue-nvidia-oracle-coreweave.html)(접근 실패)
- 검증:
  - ✅ 9월 말 연환산 매출은 약 **500억 달러**다. FT가 처음 보도했고 CNBC가 확인했다. 널리 인용된 680억~700억 달러보다 낮다.
  - ✅ Q3 run-rate 성장률 +77%, 엔터프라이즈 +107%(CNBC, 투자자 프레젠테이션)
  - ⚠️ "680억 달러는 파트너 총매출 포함" 설명은 출처마다 다르다. Quartz/CNBC는 "partner gross revenue 포함, Anthropic과 비교하려는 방법론"이라고 했다. TNW/FT는 "OpenAI 투자자들이 Anthropic과 직접 비교하려고 만든 수치"라고 했다. The Information은 "한 투자자의 추정치"라고 했다. CNN 소스는 "70B는 OpenAI에서 나온 수치가 아니다"라고 했다.
  - ✅ (신규) Bloomberg(10-09): OpenAI는 연말 연환산 매출 700억 달러 이상을 투자자에게 전망했다.
  - ✅ (신규) Anthropic은 7월 말 연환산 650억 달러를 넘었다. Q2 분기 매출에서 Anthropic(115억 달러)이 처음으로 OpenAI(67억 달러)를 앞질렀다(Reuters 인용, TNW).
- 주가:
  - ⚠️수정: 출처마다 수치가 다르다.
    - CNN(TNW 인용): Nasdaq Composite **-1.25%**(8월 중순 이후 최악), Oracle **-5.5%**, Intel -5.3%, NVIDIA **-2.9%**
    - Quartz: Oracle -5% 이상, Nasdaq 오후 -1.4%
  - ❌확인불가: "CoreWeave 약 -8%"
- 시사점: 하나의 매출 수치가 인프라 체인 전체 밸류에이션을 흔들었다. 이른바 '단일 고객(OpenAI) 리스크'다. 매출 집계 방식(총액 대 순액)이 AI 랩 비교의 핵심 쟁점이 됐다.

#### [9] CoreWeave — 주가 급락, CEO 메모, CDS 사상 최고
- URL: [TNW(10-15)](https://thenextweb.com/news/huang-coreweave-backstop-stockholm), [The Star/Reuters(10-15)](https://www.thestar.com.my/tech/tech-news/2026/10/15/coreweave-ceo-notes-strong-backlog-in-memo-to-reassure-staff-over-market-scrutiny)(검색 발췌, 본문 미열람), [CNBC 10-19](https://www.cnbc.com/2026/10/19/coreweave-oracle-ai-credit-stress.html)(접근 실패)
- 검증:
  - ✅검증(간접): 10-14(수) CEO 메모가 나왔고, 주가는 약 -15%로 마감했다(Reuters, 검색 발췌).
  - ✅ 10-15 CDS 1,194.5bp(TNW)
  - ⚠️ 메모 인용: 이전 노트의 "We are confident in our backlog which more than supports all of our debt obligations"는 원문 문구로 확인하지 못했다. Reuters 요약은 "the market can misunderstand and act irrationally"(시장은 오해하고 비이성적으로 움직일 수 있다), 그리고 백로그가 부채 상환 의무를 커버한다는 취지였다.
  - Bloomberg에 따르면 메모는 경쟁사(Firmus, AirTrunk, Lambda, Nscale)의 IPO·조달 난항이 CoreWeave에 대한 인식에 영향을 준다고 지적했다(검색 발췌).
  - ✅검증(간접): 2032년 만기 무담보채(12.5억 달러) 수익률이 15% 근처로 올랐다. 6월 30일 기준 부채는 356억 달러, 분기 이자비용은 6.4억 달러다. 백로그는 Q2 말 1,042억 달러다(검색 발췌). TNW의 "백로그 994억 달러(7월)"와는 시점 차이로 보인다.
  - ❌확인불가: "그 전 주에 -24%", "10-27 덴마크 용량 추가 발표 후 CoreWeave·Nebius 약 +4%"(24/7 Wall St. 접근 실패, 검색에서도 덴마크 관련 결과 없음)
  - ✅ (맥락) Meta의 CoreWeave 계약은 총 350억 달러다(TNW 10-26).
- 시사점: GPU 담보 부채의 금리 민감도와 백로그 인식 조건(인도·가용성)이 네오클라우드의 핵심 리스크다. NVIDIA의 공개 옹호는 이 리스크가 공급망 전체의 문제라는 점을 보여 준다.

#### [10] Oracle — AI World 2026(라스베이거스), 2026-10-27(화) / Investor Day 2026-10-28(수)
- **AI World 보도자료 3건(1차 자료, oracle.com)** ✅검증
  - [Oracle Brings Google TPUs to OCI](https://www.oracle.com/news/announcement/ai-world-oracle-brings-google-tpus-to-oracle-cloud-infrastructure-2026-10-27/)
    - OCI는 Google 밖에서 TPU를 제공하는 **최초의 하이퍼스케일러**가 된다. 출시는 **2027년(역년)**이며, 다년간 단계적으로 늘린다. 8세대 TPU(8t 학습용, 8i 추론용)가 언급됐다.
    - 인용 OCI 사장 Mahesh Thiagarajan: "Different AI workloads have different compute needs." → "AI 워크로드마다 필요한 컴퓨트가 다릅니다."
    - 인용 Google Amin Vahdat: "The next generation of AI will require a diverse range of compute." → "차세대 AI에는 다양한 종류의 컴퓨트가 필요합니다."
  - [NVIDIA and Oracle Expand Vera Rubin to Multi-Gigawatt Scale](https://www.oracle.com/news/announcement/ai-world-nvidia-and-oracle-expand-nvidia-vera-rubin-to-multi-gigawatt-scale-2026-10-27/) — **이전 노트 누락 항목**
    - OCI Supercluster를 Vera Rubin NVL72로 **멀티GW 규모**까지 확장한다. Vera Rubin NVL72와 Vera CPU를 OCI에서 정식 출시(GA)했다. HGX Rubin NVL8을 도입할 계획이다.
    - OpenAI는 애빌린(Abilene)의 OCI Supercluster(Blackwell GPU 10만 개 이상)에서 GPT-6 Astra를 학습하고 서비스했다.
    - 인용 NVIDIA Ian Buck: "AI factories must be productive, durable and fungible." → "AI 팩토리는 생산적이고, 오래가며, 용도 전환이 가능해야 합니다."
    - 인용 OpenAI Uday Ruddarraju: Vera CPU를 OCI에서 "bringing ... into production"(실제 운영에 투입 중)이며, 에이전트 샌드박스 워크로드용이다.
  - [Oracle Reinvents Enterprise Computing with OpenAI](https://www.oracle.com/news/announcement/ai-world-oracle-reinvents-enterprise-computing-for-the-ai-era-with-openai-2026-10-27/)
    - Oracle AI Workspace(ChatGPT 플러그인), Oracle AI Security Mesh(OpenAI 사이버 모델), App Composer(Codex), AI SMB Bundle을 발표했다.
    - 인용 Oracle CEO Clay Magouyrk: "OpenAI is transforming how enterprises solve business problems, from chat, to coding, to analytics, to autonomous agents." → "OpenAI는 채팅, 코딩, 분석, 자율 에이전트까지 기업이 업무 문제를 푸는 방식을 바꾸고 있습니다."
    - 인용 Greg Brockman: "putting frontier AI into everyday operations" → "프론티어 AI를 일상 업무에 넣는다"
  - ⚠️수정
    - "AI Security Mesh 10-28 발표"는 날짜가 틀렸다. **10-27 OpenAI 협력 보도자료에 함께 포함**돼 있다(HPCwire 기사가 10-28 게재였을 뿐이다).
    - "2027년부터 Google TPU **임대**"는 정확히는 **OCI에서 Google TPU를 고객에게 제공**하는 것이다(2027년).
    - **"그 외 비NVIDIA 가속기 4개 계열 도입"은 ❌확인불가**다. 1차 보도자료에 없다.
    - "xAI Grok 4.6/4.7 OCI 제공"도 ❌확인불가다(보도자료 목록에서 확인되지 않음).
  - ⚠️ 경영진 체제: 보도자료는 Clay Magouyrk를 "CEO, Oracle"로 표기했다. 공동 CEO인지는 이 자료만으로 확인할 수 없다.
- **Investor Day(10-28)** ✅검증 — [TNW(10-28)](https://thenextweb.com/news/oracle-30b-free-cash-flow-2029-shares-jump), [Oracle IR](https://investor.oracle.com/investor-news/news-details/2026/Oracle-Investor-Day-2026-Accelerating-Value-Creation/default.aspx)(접근 실패, 검색 발췌로 일치 확인) — **이전 노트 누락 항목**
  - CFO Hilary Maxson(4월 합류): FY27~28 capex 정점 이후 **FY28 하반기 FCF 흑자 전환**, **FY29(2029년 5월까지) FCF 300억 달러+**. 애널리스트들은 그 해에도 FCF가 마이너스일 것으로 예상하고 있었다.
  - 신규 조달은 FY30까지 **200억 달러로 제한**한다(주식과 부채 절반씩, 차환 제외).
  - 공식 문구: "Vendor financing, customer-provided hardware and customer prepayments are expected to reduce upfront cash requirements through the transition to positive free cash flow." → "벤더 금융, 고객이 제공하는 하드웨어, 고객 선급금이 FCF 흑자 전환 과정의 선행 현금 소요를 줄일 것으로 예상한다."
  - FY30 매출 목표 2,250억 달러 이상을 유지했다. 향후 2년간 **7GW**를 추가해 FY28 말 10GW를 넘긴다.
  - FY26(2026년 5월까지) FCF는 -237억 달러였고, 데이터센터에 557억 달러를 썼다.
  - 주가는 장중 최대 +14%였다(연초 대비 -33% 상태에서).
  - 인용 Bloomberg Intelligence Anurag Rana: "could ease concern about elevated capital spending beyond the next two years" → "향후 2년 이후 높은 capex에 대한 우려를 덜어 줄 수 있다"
- 신용:
  - ✅ S&P가 7월 Oracle을 투기등급 바로 위 등급(BBB-)으로 낮췄다(TNW: "one notch above junk in July").
  - ❌확인불가: S&P FY2027 FCF -420억 달러 추정, 총부채 1,670억 달러
- 시사점: Oracle은 '멀티 가속기(NVIDIA + Google TPU)'와 '자금조달 규율(조달 상한, 벤더 금융)'을 동시에 내놨다. 그러자 시장은 OpenAI 매출 정정 이후 처음으로 Oracle을 강하게 다시 평가했다. 다만 벤더 금융·고객 제공 하드웨어에 기대는 구조는 순환 금융 논쟁의 연장선이다.

#### [11] OpenAI 펀딩 축소 / Anthropic IPO — 2026-10-26 ~ 10-31
- ✅ (신규) OpenAI 펀딩 목표가 300억에서 **약 200억 달러**로 100억 달러 줄었다(FT 10-30, CNBC 10-31 확인). 지금까지 확보한 금액은 약 110억 달러로, 일부 대형 투자자 관심이 "tepid"(미지근)했다(WSJ). 기업가치는 1.25조 달러(조달 후)로, 처음 제시한 1.4조 달러에서 낮아졌다. 참여 예정 투자자는 MGX, SoftBank, Founders Fund, Coatue, **Sequoia, a16z**다(FT) — [TNW(10-31)](https://thenextweb.com/news/openai-funding-round-20bn-target-cut-ft)
  - ⚠️수정: 이전 노트의 "OpenAI가 자금조달 목표를 100억 달러로 축소"(BigGo)는 틀렸다. **100억 달러를 줄여 약 200억 달러로** 낮춘 것이다.
- ✅ Anthropic은 10-26(월) IPO 신청서를 공개했다. 11월 상장을 계획하며, 기업가치는 최소 1.5조 달러다(FT 인용) — 같은 TNW 기사
- ❌확인불가: CNBC 10-31 "Anthropic's path to the Nasdaq just got a lot bumpier" 본문(cnbc.com 차단)
- ✅ (신규) The Information(10-27): OpenAI가 Google TPU를 살 계획이다(OpenAI는 Reuters에 논평을 거부했다). Alphabet CFO는 TPU 판매 매출이 올해 말 소액, 대부분 2027년에 잡힌다고 했다 — [TNW(10-28)](https://thenextweb.com/news/openai-google-tpu-chips)

### Inferences
- 10월 AI 매도세의 진원지는 'OpenAI 수익화 의문(매출 정정 → 펀딩 축소)'에서 시작했다. 이것이 Oracle·CoreWeave 부채와 하이퍼스케일러 FCF로 이어지는 금융 사슬이었다. 이전 노트의 판단은 유지하되 보강한다. 월말 OpenAI 펀딩 축소로 **사슬의 시작점(AI 랩의 조달 능력) 자체가 약해지는 신호**가 나왔다.
- Oracle·OpenAI·Google 3자 구도가 바뀌었다. Google TPU가 OCI에 들어가고, OpenAI는 TPU 구매를 추진한다. 'NVIDIA 독점'이 깨지는 것이 하드웨어 측 최대 구조 변화다. 동시에 Oracle은 Vera Rubin 멀티GW 확장을 함께 발표해 NVIDIA와의 관계도 유지했다.

### Gaps
- CoreWeave 메모 원문, 덴마크 용량 발표(10-27) 여부, 10월 월간 주가 낙폭
- Oracle Investor Day 원문 보도자료(investor.oracle.com 차단). RPO 최신 수치도 미확인이다.
- CNBC 10-19 기사의 Oracle 채권 수익률 수치

---

## Q3. 투자자·애널리스트(Goldman Sachs, Morgan Stanley, a16z, Sequoia 등)는 AI 버블·capex를 어떻게 봤나

### Takeaway
기간 안에 가장 날카로운 '버블·ROI' 경고는 은행 리서치보다 **실물 경제 데이터 쪽**에서 나왔다.
- Apollo Torsten Slok(10-20·10-24): 비테크 기업에 AI 재무 효과가 "zero"
- Gartner: 2030년까지 3.5조 달러 상각 가능성
- Reuters(10-31): 빅테크 5사 자사주 매입 -83%, 9개월 합계 FCF 적자

반대편에서는 Blackstone Jon Gray가 수요를 "almost parabolic"이라고 했다. Goldman·Morgan Stanley는 2027년 capex 전망을 계속 올리는 쪽이었다. 다만 그들의 10월 리포트 원문은 확인하지 못했다. **a16z·Sequoia의 기간 내 버블 관련 공개 발언은 이번에도 찾지 못했다.** 확인된 것은 두 회사가 OpenAI 축소 라운드에 참여할 예정이라는 사실뿐이다(FT).

### Cited Findings
- **Apollo 수석이코노미스트 Torsten Slok — 노트(10-24, 토)와 10-20 노트** ✅검증 — [TNW(10-26)](https://thenextweb.com/news/apollo-ai-payoff-outside-tech-slok)
  - AI가 기술 섹터 밖 미국 기업에 "zero financial payoff"(재무적 효과 제로)였다.
  - 매그니피센트7의 직원당 매출은 2022년 약 55만 달러에서 약 80만 달러로 늘었다. 나머지 S&P 493은 약 55만 달러, 이익률 약 10%로 정체다.
  - Ramp 데이터상 상위 10% 기업이 OpenAI·Anthropic 지출의 95.6%를 차지한다.
  - 10-20 노트: 기업 토큰 지출 증가가 둔화했다. 컴퓨트 수요는 "only when compute is effectively free"(컴퓨트가 사실상 공짜일 때만) 존재할 수 있다.
  - 인용: "Mainstream corporate America is pulling back and starting to view token spending not as a source of growth but as a cost center that weighs on margins." → "주류 미국 기업들은 물러서고 있고, 토큰 지출을 성장의 원천이 아니라 마진을 깎는 비용센터로 보기 시작했다."
  - 인용: "[T]he AI story will be decided in the S&P 493, not the Mag 7." → "AI 이야기는 매그니피센트7이 아니라 S&P 493에서 결판날 것이다."
  - 같은 기사 맥락: Accenture는 10월 직원 1인당 Claude 지출을 월 29달러로 제한했다.
- **Blackstone 사장 Jon Gray(10월 셋째 주)** ✅검증(TNW가 Bloomberg 인용): AI 버블 경고를 일축하며 수요를 "almost parabolic"(거의 포물선)이라고 했다. Anthropic과 세운 AI 컨설팅 사업에 관한 발언이었다 — [TNW(10-26)](https://thenextweb.com/news/apollo-ai-payoff-outside-tech-slok)
- **Gartner(10월 초)** ✅검증(TNW 서술): 3.5조 달러 규모의 AI 인프라 지출이 2030년까지 상각(write-down)될 수 있다고 경고했다 — 같은 TNW 기사. Gartner 원문은 확인하지 못했다.
- **Reuters 분석(10-31): 빅테크 자사주 매입 -83%** ✅검증(TNW가 Reuters 인용) — [TNW(10-31)](https://thenextweb.com/news/big-tech-buybacks-fall-ai-spending-reuters)
  - 대상: Microsoft·Alphabet·Amazon·Meta·Oracle, 2026년 1~9월
  - 영업현금흐름은 사상 최대 5,429억 달러(+29%)였다. capex는 2배인 **5,569억 달러**로, 2011년 이후 처음으로 영업현금흐름을 넘었다.
  - 합산 FCF는 **-140억 달러**였다(전년 +1,435억 달러).
  - 자사주 매입은 136억 달러(-83%), 주주환원 비율은 9.3%(15년 내 최저)다.
  - Amazon은 3분기에 장기부채 481억 달러를 조달했다. Alphabet은 주식 약 124억 달러, 부채 290억 달러를 조달했다.
  - 인용 Franklin Templeton Ehren Stanhope: "The current regime may increasingly be characterized by greater equity and debt issuance, a request of capital from investors." → "지금 국면은 점점 주식·부채 발행 확대, 즉 투자자에게 자본을 요청하는 국면으로 규정될 수 있다."
- **Bloomberg 집계(10-30): 빅테크 5사 미래 지출 약정 3조 달러+** ✅검증 — [TNW(10-30)](https://thenextweb.com/news/big-tech-3-trillion-ai-spending-commitments)
  - Alphabet 1조 달러+(1년 전의 약 8배), Meta 8,000억 달러+다. 미개시 리스가 1.3조, 기타 주문이 1.9조 달러다.
  - 7월 집계는 4사 약 2.4조 달러였다(Oracle 제외).
- **Reuters(10-30): "Nasdaq faces $2 trillion wipeout in October"** ✅검증(간접): 나스닥100이 10월에 5.8% 넘게 하락해 시총 2조 달러 이상이 증발할 전망이었다(검색 발췌) — [The Star/Reuters](https://www.thestar.com.my/tech/tech-news/2026/10/30/nasdaq-faces-2-trillion-wipeout-in-october-as-ai-spending-fears-deepen), [Investing.com](https://www.investing.com/news/stock-market-news/nasdaq-faces-2-trillion-wipeout-in-october-as-ai-spending-fears-deepen-4988211)(접근 실패)
  - ⚠️ 이 기사 안의 "JPMorgan 2026 글로벌 AI capex 9,000억 달러, Morgan Stanley 2027 1조 달러 돌파"와 "Alphabet 우발채무 +230억 달러"는 ❌확인불가(본문 미열람)다.
  - ✅ 10-30(금) Nasdaq -2.9%, NVIDIA -4%, Broadcom -5% 이상, Qualcomm -11% — [TechCrunch(10-30)](https://techcrunch.com/2026/10/30/cracks-are-emerging-in-the-ai-spending-boom/)
- **Morgan Stanley(10월)** ⚠️ 출처 신뢰도 낮음:
  - 2027년 AI 컴퓨트 투자를 리스 포함 약 1.58조 달러로 올렸다(현금 capex 기준선 약 1.388조 달러) — [iTiger](https://www.itiger.com/news/1138724255), [CryptoBriefing](https://cryptobriefing.com/morgan-stanley-hyperscaler-cash-burn-2027/)(검색 발췌)
  - 하이퍼스케일러 무담보채 발행이 10월 중순까지 약 2,550억 달러라고 했다(같은 출처).
  - 이전 노트의 "2026 9,780억/2027 1.6조 달러(MacIver)"와 수치 계열은 비슷하지만 원문은 ❌확인불가다.
  - ✅ (참고) Morgan Stanley·Goldman Sachs는 Meta의 350억 달러 공모(10-26) 주관사였다 — [TNW](https://thenextweb.com/news/meta-35bn-stock-offering-ai)
- **Goldman Sachs**:
  - ❌확인불가: "Tracking Trillions"(GDP 대비 1.8%/2.5%/2.8%, 2026 기준치 7,650억 달러, Sheridan "2028년 상반기 수급 균형"). 발행일과 원문 모두 미확인이다(goldmansachs.com 차단).
  - (기간 직전 맥락, 2026-09-25 전후) 2027년 하이퍼스케일러 capex 기본 시나리오 약 1.2조 달러(+54%), 상단 1.4조 달러다(roic.ai). 다른 보도는 약 1.1~1.14조 달러다. **출처마다 다르다** — [roic.ai](https://www.roic.ai/news/goldman-sachs-sees-ai-capex-at-12-trillion-by-2027-fueling-debt-financed-buildout-09-25-2026)(검색 발췌)
  - (기간 외, 8월) Goldman은 NVIDIA 주도 5,000억 달러 AI 컴퓨트 금융 플랫폼(Apollo·BlackRock·Blackstone·Brookfield·Goldman·KKR)의 리드 주관사다. Huang은 그중 최대 1,250억 달러(25%)를 백스톱할 수 있다고 했다 — [TNW(08-14)](https://thenextweb.com/news/goldman-nvidia-500bn-financing-role)
  - ❌확인불가: "S&P500 2027년 말 6,500(-21%)" 주장
- **a16z / Sequoia**:
  - ❌확인불가: 기간 내 버블·capex 공개 글이나 발언
  - ✅ 두 회사 모두 OpenAI의 축소 라운드(약 200억 달러, 1.25조 달러 밸류)에 참여할 예정이다(FT, TNW 10-31). 말보다 행동으로 '버블 아님'에 베팅한 것으로 읽힌다.
  - (기간 외) a16z는 AI 물리 계층(칩·네트워킹·데이터센터·로보틱스) 펀드 11억 달러를 결성했다(8월). Sequoia는 AI·재산업화에 100억 달러를 약정했다(8월) — [TNW a16z](https://thenextweb.com/news/a16z-machine-age-fund-1-1bn-hardware), [TNW Sequoia](https://thenextweb.com/news/sequoia-capital-is-putting-10bn-behind-ai-and-reindustrialization)
- **DBS CEO 탄수산(10-12)**: 패널 사회자였다는 점은 ✅이다. 그의 '리스크 재가격 반영' 발언은 ❌확인불가다(The Edge 차단).
- **Michael Burry NVIDIA 숏 확대(9월 경)**: ❌확인불가이며 기간 외다.

### Inferences
- 기간 안의 투자자 논쟁은 "버블이냐 아니냐"에서 **"AI 지출이 S&P 493에서 수익을 내느냐"(수요의 질)**와 **"누가 자본을 대느냐"(자사주 매입에서 주식·부채 발행으로 전환)**로 좁혀졌다. 현금흐름 데이터(capex가 영업현금흐름을 넘음)가 처음으로 이를 숫자로 뒷받침했다.
- 은행권 전망(2027년 1.1조~1.6조 달러)은 정의(리스 포함 여부, 하이퍼스케일러만인지 전체인지) 차이가 매우 크다. 보고서에 인용할 때 반드시 정의를 함께 적어야 한다.

### Gaps
- Goldman·Morgan Stanley·JPMorgan 10월 리포트 원문과 정확한 발행일(원문 사이트 차단)
- a16z(Marc Andreessen, Martin Casado 등)·Sequoia(David Cahn 등)의 10월 발언. 검색에서 찾지 못했다.
- Reuters "Nasdaq $2T wipeout" 본문 세부(JPM/MS 수치)

---

## Q4. 시장 맥락 — 하이퍼스케일러 capex, 전력, HBM/메모리, 데이터센터 딜

### Takeaway
1차 자료와 원문 기사로 확인한 Q3 실적 시즌(10-21~10-29) 내용은 다음과 같다.
- **Meta**: 2026년 capex 1,350~1,450억 달러로 범위를 좁혔다(10-21).
- **Microsoft**: 2026 역년 capex **약 1,700억 달러**(서드파티 용량 지연 반영, 10-28 콜).
- **Alphabet**: 1,950~2,050억 달러 유지(10-28).
- **Amazon**: 약 2,200억 달러 유지(10-29).
- 4사 모두 2027년 증가를 시사했다. 4사 2026년 가이던스 합계는 중간값 기준 약 7,350억 달러다. TechCrunch 표현으로는 "7,400억 달러 이상"이다.
- Alphabet은 FCF 2분기 연속 마이너스로 사상 최악의 하루(10-29, 약 -12%)를 기록했다. 이전 노트의 "IPO 이후 첫 마이너스"는 틀렸다.

### Cited Findings

#### 검증된 하이퍼스케일러 capex·실적 표 (Q3 2026)

| 회사(발표일) | Q3 capex | 2026년 capex 가이던스 | 2027년 언급 | Q3 FCF | 클라우드 매출/성장 | 백로그/RPO | 검증 |
|---|---|---|---|---|---|---|---|
| **Microsoft** FY27 Q1 (10-28 수) | **452억 달러**(금융리스 74억 포함). 현금 PP&E 394억 달러 | **역년 2026 약 1,700억 달러**("due to the 3P capacity delays"). Q2(10~12월) 500억 달러 초과 | FY 하반기(2027년 1~6월) capex 가속(CPU·메모리·스토리지 단가 상승분 포함, GPU, 이연된 3P 용량) | **+186억 달러**(영업현금흐름 580억 달러, +29%) | Microsoft Cloud 639억 달러(+30%), **Azure +48%** | 상업용 RPO **6,770억 달러(+73%)** | ✅ 1차(보도자료+전사록) |
| **Alphabet** (10-28 수) | **514억 달러**(사상 최대, 전년의 2배 이상) | **1,950~2,050억 달러 유지**(7월 설정) | "increase significantly in 2027"(수치 없음) | **-91억 달러**(2분기 연속 마이너스) | Google Cloud **307억 달러(+103%)**, 영업이익 111억 달러 | Cloud 백로그 **5,610억 달러**(2년 안에 55% 넘게 인식) | ✅ 원문기사(TNW·TechCrunch) + ✅간접(10-Q·전사록 발췌) |
| **Amazon** (10-29 목) | 현금 capex 759억 달러(간접). PP&E 매입 773억 달러(전년 351억 달러) | **약 2,200억 달러 유지**(7월 설정) | "meaningfully more"(의미 있게 더) | TTM **-424억 달러**(전년 +148억 달러) | AWS **460억 달러(+39%)**, 영업이익 178억 달러 | AWS 백로그 **5,780억 달러**, run-rate 1,840억 달러 | ✅ 원문기사(TNW) |
| **Meta** (10-21 수) | **349억 달러**(금융리스 원금 포함, 전년 193.7억 달러) | **1,350~1,450억 달러**(기존 1,300~1,450억 달러에서 하단 상향) | 가이던스 없음 | **-21억 달러** | — | 미래 약정 약 8,250억 달러(10-Q, 10-22) | ✅ 원문기사(TNW) + ✅간접(8-K 발췌) |
| **4사 합계(2026 가이던스)** | — | 약 **7,200억~7,500억 달러**(Microsoft 170 + Alphabet 195~205 + Amazon ~220 + Meta 135~145). TechCrunch: "more than $740 billion" | 4사 모두 증가 | — | — | — | 계산 + [TechCrunch](https://techcrunch.com/2026/10/30/cracks-are-emerging-in-the-ai-spending-boom/) |
| 참고: **Oracle** | FY26 데이터센터 지출 557억 달러 | FY27~28 정점, FY29 감소 | FY28 하반기 FCF 흑자, FY29 FCF 300억 달러+ | FY26 -237억 달러 | — | — | ✅ 원문기사(TNW) |
| 참고: **TSMC** | Q3 약 138억 달러(간접) | **600~640억 달러 유지** | 2026~28년 "significantly higher" | — | 매출 467.2억 달러(+41.2%) | — | ✅ 원문기사 |

- 주: Microsoft는 회계연도 기준이다(FY27 = 2026-07~2027-06). Microsoft의 "약 1,700억 달러"는 CFO가 말한 **역년(calendar year) 2026** 수치다.

#### 회사별 검증 상세
- **Microsoft (FY27 Q1, 2026-10-28 수)** — [1차 보도자료](https://www.microsoft.com/en-us/investor/earnings/fy-2027-q1/press-release-webcast), [1차 전사록](https://www.microsoft.com/en-us/investor/events/fy-2027/earnings-fy-2027-q1)
  - ✅ 발표일 10-28(수)이다. 이전 노트의 "10-28 또는 10-29"는 **10-28로 확정**한다.
  - ✅ 매출 923억 달러(+19%), 영업이익 459억 달러(+21%), GAAP EPS 4.92달러, 조정 EPS 4.89달러. "Agents and Infra" 신규 부문 매출 768억 달러(+25%)
  - ⚠️수정: **상업용 RPO = 6,770억 달러, +73%**다. 6,270억 달러·+99%는 틀렸다.
  - ✅ 상업용 예약(bookings) -12%. 전년의 대형 Azure 약정 기저효과 때문이다.
  - ⚠️수정(정밀화): 연간 capex. CFO 원문은 "In Q2, we expect CapEx spend will be over $50 billion. Therefore, for the calendar year, spend should be approximately $170 billion due to the 3P capacity delays noted earlier." → "2분기 capex는 500억 달러를 넘을 것이고, 그래서 역년 기준 지출은 앞서 말한 서드파티 용량 지연 때문에 약 1,700억 달러가 될 것입니다."
    - **1,700억 달러가 최종 확정치**다.
    - 직전 가이던스가 1,750억 달러였는지는 1차 자료로 확인하지 못했다. "due to the 3P capacity delays"라는 표현을 보면 하향인 것은 분명하다.
    - 다른 출처의 "약 1,900억에서 1,750억 달러로, 회계 변경" 설은 근거가 없다.
  - ✅ CFO Amy Hood: "Capital expenditures were $45.2 billion, as some third-party capacity deliveries we expected in Q1 were delayed. Roughly three quarters of our capex was for short-lived assets, primarily CPUs and GPUs, including higher memory and storage costs." → "1분기에 기대했던 일부 서드파티 용량 인도가 늦어져 capex는 452억 달러였습니다. capex의 약 4분의 3은 주로 CPU·GPU 같은 단기 자산이며, 메모리·스토리지 단가 상승분이 포함돼 있습니다."
  - ✅ Hood: "Customer demand continues to exceed available supply." → "고객 수요가 가용 공급을 계속 넘고 있습니다." Q2 Azure 성장률 가이던스는 49~50%(고정환율)이고, 일부 3P GPU-as-a-service 계약은 하반기로 밀렸다.
  - ✅ Hood: "we're feeling good that we're free cash flow positive ... we have lots of options to be able to tap the financing markets when they make sense" → "FCF가 플러스라는 점에 만족하며 ... 적절할 때 금융시장을 활용할 선택지가 많습니다."
  - ✅ Nadella(보도자료): "By helping organizations build and own their own intelligence, and earning trust through agent safety and security, we are translating our innovation into growing adoption and real-world impact across every industry." → "조직이 자체 인텔리전스를 구축·소유하도록 돕고 에이전트 안전·보안으로 신뢰를 얻으면서, 혁신을 모든 산업의 도입 확대와 실질적 성과로 바꾸고 있습니다."
  - ✅ (신규) Maia 200은 Teams·Copilot에서 와트당 토큰이 최대 1.7배다. Maia 300은 선도 GPU 시스템 대비 와트당 토큰 +40%를 목표로 한다(콜).
  - ✅ (신규) Windows OEM 매출 -27%. 재고가 높고 PC 수요가 약하다. Q2에는 30% 중반 감소를 예상한다(메모리발 PC 약세와 같은 흐름).
  - ✅ (신규) 이자비용에 데이터센터 금융리스 이자가 포함돼, 기타손익이 약 -3억 달러로 예상된다.
  - ❌ "FY27 capex 2,550~2,600억 달러"는 이전 노트 판단대로 회사 가이던스가 아니다. 인용하지 말 것.
- **Alphabet (2026-10-28 수)** — [TNW(10-29)](https://thenextweb.com/news/google-cloud-revenue-doubles-q3-2026), [TechCrunch(10-30)](https://techcrunch.com/2026/10/30/cracks-are-emerging-in-the-ai-spending-boom/), [Alphabet 10-Q(SEC)](https://www.sec.gov/Archives/edgar/data/0001652044/000165204426000084/goog-20260930.htm)(접근 실패), [Yahoo 전사록](https://finance.yahoo.com/quote/GOOG/earnings/GOOG-Q3-2026-earnings_call-712854.html)(접근 실패)
  - ✅ 매출 1,276억 달러(+25%, 컨센서스 1,282억 달러에 미달). 광고 820억 달러(예상 834억 달러). 순이익 262억 달러(-25%, 지분투자 손실 87억 달러)
  - ✅ 2026년 capex 1,950~2,050억 달러 유지(7월 설정). 이전 노트의 "1,750~1,850억 달러 / 약 1,700억 달러" 표기는 ⚠️ 틀렸다. 1,800~1,900억 달러는 1분기에 낸 가이던스다(간접).
  - ⚠️수정: FCF는 **-91억 달러**다. "-59억~-90억 달러 출처별 상이"는 -91억 달러로 정리한다. **"IPO 이후 첫 마이너스"도 틀렸다.** TNW·TechCrunch 모두 "second straight/consecutive quarter"(2분기 연속)라고 썼다.
  - ✅ 주가: 시간외 약 -10%, **10-29(목) 약 -12%로 사상 최악의 하루**(시총 약 5,000억 달러 증발) — TechCrunch. 이전 노트의 "-12.6%"는 소수점까지는 확인하지 못했다.
  - ✅검증(간접): CFO Ashkenazi는 "We continue to expect our capex to increase significantly in 2027, and will provide further details on our Q4 call." 취지로 말했다. TNW의 "spending would rise significantly again in 2027 but gave no figure"와 일치한다. "came online only at the very end of Q3" 문구는 ❌확인불가다. 검색 발췌에는 "4분기에 가동되는 서드파티 용량이 단기 클라우드 마진 역풍"이라고만 나온다.
  - ✅ Pichai: "We had a strong quarter and are now on a half-trillion dollar revenue run rate." → "강한 분기였고, 이제 연환산 매출 5,000억 달러 수준입니다." 분당 토큰 처리량은 약 320억 개(1년 전의 4배 이상), Gemini 앱 사용자는 약 10억 명이다.
  - ❌확인불가: "AI 인프라 우발채무 분기 사이 +230억 달러"(Reuters)
- **Amazon (2026-10-29 목)** — [TNW(10-31)](https://thenextweb.com/news/amazon-q3-earnings-aws-39-free-cash-flow-2027-capex), [About Amazon: Jassy](https://www.aboutamazon.com/news/company-news/aws-growth-ai-demand-q3-2026-earnings)(접근 실패), [Amazon IR](https://ir.aboutamazon.com/news-release/news-release-details/2026/Amazon-com-Announces-Third-Quarter-Results/default.aspx)(접근 실패)
  - ✅ 매출 2,019억 달러(+12%), 영업이익 281억 달러(전년 174억 달러), 영업이익률 13.9%(사상 최고). AWS 460억 달러(+39%), AWS 영업이익 178억 달러(전년 114억 달러). AWS 백로그 5,780억 달러, run-rate 1,840억 달러
  - ⚠️수정: EPS 컨센서스는 1.97달러가 아니라 **1.96달러**다(CNBC 인용). 매출 컨센서스는 2,023억 달러였다. 시간외 최대 -7%(Reuters)
  - ✅ 2026년 현금 capex 약 2,200억 달러로, **7월 실적 때 설정한 수치를 유지**했다. Q3 PP&E 매입은 773억 달러다. ✅검증(간접): 현금 capex 759억 달러
  - ✅ (신규) Q3 장기부채 481억 달러 조달. 매입한 AI 하드웨어를 담보로 최대 800억 달러를 빌릴 수 있게 됐다(공시).
  - 인용:
    - ✅ Jassy: "We're installing an AI accelerator about every 14 seconds, and almost as fast as we install capacity, customers are gobbling it up." → "약 14초마다 AI 가속기를 하나씩 설치하고 있는데, 설치하는 속도만큼 고객들이 용량을 빨아들이고 있습니다."
    - ✅ Jassy: "There has never been a trillion dollar revenue business, and we may have two of them in the next 5-10 years." → "매출 1조 달러짜리 사업은 지금까지 없었는데, 우리는 앞으로 5~10년 안에 그런 사업을 두 개 가질 수 있습니다."
    - ✅ Jassy: "We can fund this plan." → "우리는 이 계획을 감당할 자금이 있습니다."
    - ⚠️수정: 이전 노트의 "projected revenue growth rates of over 40% both in 2027 and in 2028"은 원문 문구로 확인되지 않았다. 검색 발췌상 원문은 "We believe that AWS can grow north of 40% in each of 2027 and in 2028 and be a trillion-dollar revenue business in the next five to 10 years"에 가깝다(✅간접). TNW는 "AWS 매출이 2027·2028년 모두 40% 넘게 성장할 것으로 본다"라고 간접 인용했다.
    - ✅ (신규) 2027년 말부터 Trainium을 AWS 밖에서 판매한다.
- **Meta (2026-10-21 수)** — [TNW(10-22)](https://thenextweb.com/news/meta-825b-future-spending-commitments), [TNW(10-26)](https://thenextweb.com/news/meta-35bn-stock-offering-ai), [Meta 8-K(SEC)](https://www.sec.gov/Archives/edgar/data/0001326801/000162828026066700/meta-09302026xexhibit991.htm)(접근 실패, 검색 발췌)
  - ✅ 발표일은 **10-21(수)로 확정**한다. TNW 10-22 기사가 "In its third-quarter results on Wednesday"라고 썼고, 10-Q는 10-22자다.
  - ✅ Q3 capex 349억 달러, FCF -21억 달러. 2026년 capex 1,350~1,450억 달러(기존 1,300~1,450억 달러)
  - ✅검증(간접): 영업이익 129.9억 달러(-37%, 법률 비용 99억 달러, 인프라·서드파티 AI 토큰 비용). Q4 매출 가이던스 730~760억 달러. 연간 비용 가이던스 1,750~1,790억 달러
  - ❌확인불가: 매출 646억 달러(+26%), 영업현금흐름 327.9억 달러. 원문을 확인하지 못했다.
  - ✅ 무의결권 Class C 주식 신설(2027-01-19 효력)
  - ⚠️수정: 주가 반응. TNW 기준 10-22 프리마켓 약 -3%였다. "-7.84%(648.85달러)"는 ❌확인불가다. ✅ Meta 5년물 CDS는 약 119bp로 사상 최고였다(ICE).
  - ⚠️수정: Zuckerberg 인용. 1차 결과문 문구는 "Our investments are paying off, the core business is strong, and we're seeing velocity across the board." → "투자가 성과를 내고 있고, 핵심 사업은 탄탄하며, 모든 영역에서 속도가 붙고 있습니다."(✅ TNW). 이전 노트의 "a major milestone toward personal superintelligence for everyone"은 ❌확인불가다.
  - ✅ (신규) CFO Susan Li: "We expect to continue investing aggressively to support both our core business and emerging AI initiatives." → "핵심 사업과 새 AI 이니셔티브를 함께 뒷받침하기 위해 공격적인 투자를 계속할 것으로 예상합니다." — [TNW(10-30)](https://thenextweb.com/news/big-tech-3-trillion-ai-spending-commitments)
  - ⚠️수정: "약 375억 달러 주식 매각설(미확인)"은 **사실로 확인**됐다. 정확한 내용은 다음과 같다.
    - 10-26(월) 두 건의 공모를 시작했다: 보통주 225억 달러(선도매매)와 의무전환우선주 약 125억 달러, 합계 약 350억 달러다.
    - 보통주는 이후 250억 달러로 증액됐다. 수요는 약 5배였고 주당 625달러에 가격이 정해졌다(Bloomberg). 증액 후 합계는 약 375억 달러다.
    - 2027년 초부터 약 600억 달러 규모의 Class C 시장 매각 프로그램을 계획한다. 전체 계획 규모는 Bloomberg 추산 약 980억 달러다.
    - NVIDIA 30억·AMD 10억 달러 투자를 약속했다.
    - 출처: [TNW(10-26)](https://thenextweb.com/news/meta-35bn-stock-offering-ai), [TNW(10-28)](https://thenextweb.com/news/amd-1bn-meta-equity-helios-running)
  - ✅ (신규) 미래 약정은 약 8,250억 달러다. 해지 불가 계약 4,545억 달러(2027년 만기분 1,214억 달러)와 미개시 리스 3,557억 달러(최장 30년)를 포함한다(10-Q, Bloomberg 집계).

#### 전력·에너지 제약
- ❌확인불가: 아래 이전 노트 항목은 모두 원문 접근에 실패했고, 재검색으로도 1차 확인을 하지 못했다.
  - 미시간 법무장관 Dana Nessel의 DTE 1GW Google 데이터센터 재검토 요청(10-30, Law360)
  - Venture Global–GE Vernova·Baker Hughes 11.5GW(10-15, aggregator)
  - Google–Voltus 1GW 수요반응(10-22, CryptoBriefing)
  - Alliant Energy 1GW 추가(10-31, Whalesbook)
- ✅ (신규, 1차) Oracle Project Jupiter(뉴멕시코) 전력 관련 보도자료(oracle.com/news 목록에서 확인) — [Oracle News](https://www.oracle.com/news/)
  - 10-15: 마이크로그리드 허가 배출량 35% 감축(연료전지 안 수정)
  - 10-22: 자가 전력 공급 계획이 지역 요금 납부자에게 주는 이점 블로그
  - 같은 목록에 El Paso Electric 고객 요금 상쇄 최소 1.55억 달러 제안, 위스콘신 Point Beach 에너지 비용 3억 달러 부담 약속도 있다. 정확한 날짜는 목록에 표시되지 않아 확인하지 못했다.
  - **데이터센터 운영사가 요금 납부자 부담을 직접 흡수하는 쪽**으로 정치적 압력에 대응하고 있다는 신호다.
- ✅ (맥락) 덴마크 송전망 운영자는 3월에 신규 접속을 중단했다. 피크 수요 약 7GW에 대기 프로젝트가 약 60GW였다. 영국·아일랜드·북유럽 데이터센터 의사결정자 300명 조사에서 '전력 확보'가 주권 용량 구축의 최대 장애물로 꼽혔다 — [TNW(10-12)](https://thenextweb.com/news/amd-helion-agentic-rack-power)
- ✅ Oracle은 2년 안에 7GW를 추가해 FY28 말 10GW+를 목표로 한다(Q2 [10]).
- ✅ Microsoft Maia 300의 "와트당 토큰 +40%", AMD Helion의 "와트당 에이전트" 등 **전력 효율이 칩 마케팅의 핵심 지표**가 됐다(1차 전사록, TNW).

#### HBM·메모리 공급 (Q1 [5] 요약)
- ✅ SK hynix 영업이익률 80%, 2030년까지 수요 초과, LTA 14곳이 2027~28년 용량의 절반 이상 커버, DRAM ASP 20% 후반 상승 — [TNW](https://thenextweb.com/news/sk-hynix-q3-2026-record-profit-memory-shortage-2030)
- ✅ Samsung 잠정 영업이익 107.4조 원, Galaxy S26 가격 100달러 인상 — [TNW](https://thenextweb.com/news/samsung-q3-2026-record-profit-ai-memory)
- ✅ 메모리 단가 상승의 파급 효과(1차·원문 확인)
  - Microsoft capex 단가("higher memory and storage costs")
  - Intel PC 시장 -12%/-10% 전망과 Q4 가이던스 쇼크
  - TSMC "2027 신중"
  - Microsoft Windows OEM -27%
- ❌확인불가: 메모리 재고 10일 미만(Shattered.io), HBM4 가격 2배, 2027 HBM ASP +121%

#### 데이터센터·용량·금융 딜 (기간 내, 검증분)

| 날짜 | 딜 | 규모 | 검증 | 출처 |
|---|---|---|---|---|
| 10-12 | AMD Helion 오픈 랙 공개(OCP) | 최대 32,768코어/랙 | ✅ | [TNW](https://thenextweb.com/news/amd-helion-agentic-rack-power) |
| 10-12 | NVIDIA 유럽 투자 20억 달러 예고, 프랑스 4사 투자 | 20억 달러(누적 80억→약 100억 달러) | ✅ | [TNW](https://thenextweb.com/news/nvidia-huang-europe-2-billion) |
| 10-15 | NVIDIA–Norrsken 스톡홀름 AI 랩 | — | ✅ | [TNW](https://thenextweb.com/news/huang-coreweave-backstop-stockholm) |
| 10-19 | 독일 정부–NVIDIA 피지컬 AI MOU, Siemens 협력 | — | ✅ | [TNW](https://thenextweb.com/news/germany-nvidia-ai-partnership-berlin-summit) |
| 10-21 | Meta 미래 약정 공시(10-Q, 10-22자) | 약 8,250억 달러 | ✅ | [TNW](https://thenextweb.com/news/meta-825b-future-spending-commitments) |
| 10-26 | Meta 주식 공모 | 약 350억 → 375억 달러(보통주 250억 달러로 증액) | ✅ | [TNW](https://thenextweb.com/news/meta-35bn-stock-offering-ai) |
| 10-27 | AMD → Meta 지분 10억 달러, NVIDIA → Meta 30억 달러 | 합계 40억 달러 | ✅ | [TNW](https://thenextweb.com/news/amd-1bn-meta-equity-helios-running) |
| 10-27 | Oracle OCI에 Google TPU(2027년) | — | ✅ 1차 | [Oracle](https://www.oracle.com/news/announcement/ai-world-oracle-brings-google-tpus-to-oracle-cloud-infrastructure-2026-10-27/) |
| 10-27 | NVIDIA–Oracle Vera Rubin 멀티GW 확장, Vera CPU GA | 멀티GW | ✅ 1차 | [Oracle](https://www.oracle.com/news/announcement/ai-world-nvidia-and-oracle-expand-nvidia-vera-rubin-to-multi-gigawatt-scale-2026-10-27/) |
| 10-27 | OpenAI의 Google TPU 구매 계획 보도(The Information) | 미공개 | ✅(보도 사실만, 당사자 미확인) | [TNW](https://thenextweb.com/news/openai-google-tpu-chips) |
| 10-28 | Oracle Investor Day: 7GW 추가, 조달 상한 200억 달러 | — | ✅ | [TNW](https://thenextweb.com/news/oracle-30b-free-cash-flow-2029-shares-jump) |
| 10-29 | Amazon, AI 하드웨어 담보 최대 800억 달러 차입 한도 | 800억 달러 | ✅ | [TNW](https://thenextweb.com/news/amazon-q3-earnings-aws-39-free-cash-flow-2027-capex) |
| 10-30 | 빅테크 5사 미래 약정 3조 달러+(Bloomberg 집계) | 3조 달러+ | ✅ | [TNW](https://thenextweb.com/news/big-tech-3-trillion-ai-spending-commitments) |
| 10-31 | OpenAI 펀딩 목표 300억 → 200억 달러(약 110억 달러 확보) | 1.25조 달러 밸류 | ✅ | [TNW](https://thenextweb.com/news/openai-funding-round-20bn-target-cut-ft) |
| 10-27 | CoreWeave 덴마크 용량 추가 | — | ❌ | [24/7 Wall St.](https://247wallst.com/investing/2026/10/27/ai-cloud-stocks-rise-as-coreweave-adds-denmark-capacity-coreweave-and-nebius-climb-4-oracle-ticks-up/)(접근 실패) |
| 10-12 | DBS AI 딜 S$250억 주선 | — | ❌ | (접근 실패) |

- 기간 외 맥락(참고용, 10월 신규 딜 아님)
  - NVIDIA의 OpenAI 오하이오 10GW 캠퍼스 2,500억 달러 백스톱 협상(WSJ 7-26). 8월에 절반 규모로 줄었다 — [TNW(08-15)](https://thenextweb.com/news/nvidia-openai-backstop-halved-13f-spacex-intel)
  - Broadcom의 Anthropic용 600억 달러 이상 부채 조달(Bloomberg 8-20~21) — [TNW](https://thenextweb.com/news/broadcom-60bn-ai-chip-debt-anthropic)
  - 둘 다 10월 딜로 쓰면 안 된다. 다만 TNW(10-13)는 Broadcom 조달을 Hock Tan 발언의 배경으로 언급했다.

### Inferences
- **capex '하향'과 수요 둔화는 다른 이야기다.** Microsoft의 역년 2026 capex 약 1,700억 달러는 1차 전사록상 "3P capacity delays"(서드파티 용량 지연) 때문이다. Hood는 같은 콜에서 "Customer demand continues to exceed available supply"라고 했다. 집행 속도를 정하는 것은 공급 측(서드파티 GPU 용량 인도, 메모리 단가, 전력)이다.
- **시장은 'capex 규모'가 아니라 '자금 출처'로 차별화했다.**
  - FCF 플러스를 지킨 Microsoft와, 조달 상한·흑자 전환 일정을 낸 Oracle(+14%)은 상대적으로 선방했다.
  - FCF가 2분기 연속 마이너스인 Alphabet(-12%)과, 주식 발행으로 조달하는 Meta(CDS 사상 최고)는 벌을 받았다.
  - 빅테크 5사 9개월 합계 FCF가 마이너스로 돌아섰다(Reuters). 자금 조달이 '자사주 매입 → 주식·부채 발행'으로 바뀌었다는 점이 10월의 구조 변화다.
- 메모리 인플레이션은 AI의 '숨은 세금'이 되고 있다. 하이퍼스케일러 capex 단가를 올리고 PC·스마트폰 수요를 깎는다. 그래서 TSMC·Intel의 2027년 가이던스를 보수적으로 만든다.

### Gaps
- Alphabet·Amazon·Meta·TSMC·Intel 1차 IR 문서 본문(sec.gov·IR 사이트 차단/봇 차단). 표의 "✅간접" 항목은 원문으로 다시 확인할 필요가 있다.
- Microsoft의 직전 역년 capex 가이던스(1,750억 달러였는지). 7월 FY26 Q4 콜 전사록으로 확인해야 한다.
- 전력 관련 10월 딜(미시간 AG, Venture Global, Google–Voltus, Alliant). 1차 확인을 하지 못했다.
- 10월 신규 GW급 GPU·데이터센터 계약(Stargate 추가 사이트 등)은 이번 재조사에서도 기간 내 확정 건을 찾지 못했다. 검색 결과는 대부분 2025년 9월 NVIDIA–OpenAI 10GW, 2026년 7~8월 Anthropic–Lambda/Nscale 등 기간 외 건이었다.
