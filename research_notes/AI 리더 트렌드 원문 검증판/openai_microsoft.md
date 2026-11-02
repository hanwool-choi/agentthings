# OpenAI·Microsoft 리더 공개 발언 — 원문 검증판 (2026-10-02 ~ 2026-11-02)

> **검증 방법·한계 (반드시 먼저 읽을 것)**
> - "네트워크가 열렸다"는 전제와 달리, 이번 세션에서도 대부분 도메인이 프록시 정책으로 막혀 있었다(403 / DNS 실패). 막힌 곳: openai.com, politico.com, fortune.com, forbes.com, cnbc.com, bloomberg.com, ft.com, theinformation.com, fool.com, stockanalysis.com, benzinga.com, sec.gov, youtube.com, singjupost.com, cheekypint.substack.com/transistor.fm, axios.com, time.com, datacenterdynamics.com, tomshardware.com, fastcompany.com, ukstories.microsoft.com, geekwire.com, theverge.com 등.
> - 실제로 원문을 연 출처: **microsoft.com IR(FY27 Q1 보도자료, 컨퍼런스콜 이벤트 페이지 녹취)**, **TechCrunch**, **The Next Web(TNW)**, **The Decoder**, **SiliconANGLE**(일부). 이들은 대부분 1차 원문(팟캐스트·X 게시물·블로그·공시)을 직접 인용한 기사다. 1차 원문 자체(YouTube, Politico, X, openai.com 블로그)는 열지 못했다.
> - 판정 기준: ✅검증 = 1차 원문 또는 원문을 직접 인용한 기사 본문에서 문구·숫자 확인 / ⚠️수정 = 확인했으나 이전 노트 값·날짜·맥락이 틀려 수정 / ❌확인불가 = 접근 가능한 출처에서 확인하지 못함(틀렸다는 뜻이 아님).
> - Microsoft IR 녹취 인용은 WebFetch 도구가 인용 길이를 125자로 잘라 일부 문장이 부분 인용이다.
> - 기간 밖 항목은 **[기간 외·맥락]**으로 표시했다.
> - 차단된 도메인을 열려면 세션 네트워크 설정에서 허용해야 한다.

---

## 핵심 질문 1: 이전 노트 항목별 원문 대조 결과 (✅/⚠️/❌)

### Takeaway
이전 노트의 큰 줄기(Politico 인터뷰, Cheeky Pint, 내부 브리핑 유출, Microsoft FY27 Q1 수치, Nadella 20VC, Suleyman MAI-DxO, Brockman 슈퍼PAC)는 대부분 사실로 확인됐다. 다만 틀린 곳이 여럿 있다. ① "데이터센터 내용연수 15→25년"은 보도자료와 녹취 어디에도 없다. ② Altman의 "speed limit" 발언은 Berman 인터뷰가 아니라 **내부 회의 발언(The Information 보도)**이다. ③ Suleyman의 "학습 1회 1,000억 달러·5~6개 연구소" 발언은 인용한 TechCrunch 기사에 없다. ④ Kevin Weil은 2026년 4월 이미 OpenAI를 떠났다. ⑤ "GPU를 녹이는" 시나리오에 대해 Altman은 "완결성을 위해 언급"했을 뿐이고 "terrible"하다고 평했다.

### Cited Findings

#### [검증 1] Altman — Politico 'Decoded' 첫 회 인터뷰 (진행 Brendan Bordelon)
| 이전 노트 내용 | 판정 | 근거·수정 |
|---|---|---|
| 게재일 2026-10-04 | ⚠️ | TNW(10/5 08:28 UTC)는 Decoded를 "새 일간 테크 뉴스레터·팟캐스트로, 월요일 출범"이라고 썼다. 2026-10-05가 월요일이다. 10/4(일) 선공개, 10/5 정식 출범으로 보는 것이 맞다. Politico 원문은 열지 못했다 — [TNW](https://thenextweb.com/news/sam-altman-ai-risks-politico-anthropic) |
| "we believe that the world should accept some bad things happening for the benefits of this technology and people having the agency." | ✅ | TNW가 그대로 인용 — [TNW](https://thenextweb.com/news/sam-altman-ai-risks-politico-anthropic) |
| "a completely unacceptable tradeoff"가 'Anthropic식 접근'을 가리킨다 | ⚠️ | 원문 맥락은 다르다. "AI가 너무 위험하니 한 연구소가 보유하고 이익을 나눠 줘야 한다는 견해"에 대해 "이해는 하지만 동의하지 않는다"며 한 말이다. TNW 표기는 "a completely unacceptable trade-off" — [TNW](https://thenextweb.com/news/sam-altman-ai-risks-politico-anthropic) |
| "I think there's a lot of daylight" | ❌ | TNW는 "OpenAI와 Anthropic이 AI 규칙에서 여전히 상당히 다르다"고 간접 서술만 했다. 'daylight'라는 단어는 확인하지 못했다. |
| 수용 불가 대상: "a serious loss of control to AI" | ✅ | [TNW](https://thenextweb.com/news/sam-altman-ai-risks-politico-anthropic) |
| Anthropic 대변인 반박(규제안은 프런티어 모델에만 적용) | ✅ | 같은 출처 |
| 트럼프 행정부 자발적 안전 협약 맥락 | ✅ | Politico가 "백악관에서 서명한 AI 안전 협약"과 "트럼프의 'superintelligence' 명칭 변경 명령"도 다뤘다고 TNW가 전했다. 협약 서명일은 9/29이고, Brockman이 서명자다 — [TNW 10/21](https://thenextweb.com/news/openai-brockman-ai-safeguards-leading-the-future-pac) |
| OpenAI 정책이 Anthropic 쪽으로 이동했다는 분석 | ✅(취지) | TNW 부제: "Amodei의 감속 요구를 지지했음에도 규제에서는 격차가 남아 있다". 인터뷰 3주 전 Amodei 에세이가 나왔고, Altman은 같은 날 지지하면서 외부 테스터에게 직원과 같은 접근권을 주겠다고 했다 — [TNW](https://thenextweb.com/news/sam-altman-ai-risks-politico-anthropic), [TNW 9/12 맥락](https://thenextweb.com/news/altman-matches-pacing-eu-antitrust) |
| Fortune·Forbes·Slashdot·Common Dreams·Benzinga 보도 | ❌ | 해당 도메인 차단으로 원문 대조 불가 |

#### [검증 2] Altman — Matthew Berman YouTube 인터뷰 (2026-10-21)
| 이전 노트 내용 | 판정 | 근거·수정 |
|---|---|---|
| 10/21 공개, 제목 "RSI, AI Consciousness, OpenAI's New Hardware, Compute…" | ❌(정황상 개연성 있음) | YouTube와 singjupost가 막혔다. 제3자 GitHub 팩트체크 로그(jfredson/agi-zeitgeist PR #42)의 검색 스니펫에만 이 제목과 날짜가 나온다 — [GitHub PR](https://github.com/jfredson/agi-zeitgeist/pull/42), [singjupost(미접속)](https://singjupost.com/sam-altman-on-rsi-ai-consciousness-openais-new-hardware-transcript/) |
| RSI "속도 제한(speed limit)" 발언 | ⚠️ | 접근 가능한 출처에서 'speed limit'은 **내부 회의 발언**으로만 나온다. The Information 보도를 인용한 The Decoder(10/20)는 "Altman이 AI 개발 'speed limit'에 대한 실행 가능한 제안이 너무 적다고 내부에서 불평했다"고 썼다. Berman 인터뷰 발언인지는 확인하지 못했다 — [The Decoder](https://the-decoder.com/sam-altman-reportedly-pitched-three-endgames-for-ai-safety-one-involving-a-single-firm-melting-everyone-elses-gpus/) |
| Dots 관련 발언 | ⚠️ | Dots를 자세히 다룬 인터뷰는 Every 팟캐스트(Dan Shipper, DevDay 현장 녹화, **2026-09-30 공개 = 기간 외**)다. Berman 인터뷰에서 Dots가 나왔는지는 확인하지 못했다 — [Every](https://every.to/podcast/how-sam-altman-uses-dots-to-take-back-his-time) (검색 스니펫) |
| "OpenAI의 강점은 새 모델을 먼저 얻는 것"(Dealroom) | ❌ | Dealroom 차단 |

#### [검증 3] Altman — Stripe "Cheeky Pint" 팟캐스트 (진행 John Collison)
| 이전 노트 내용 | 판정 | 근거·수정 |
|---|---|---|
| 2026-10-29 공개 | ✅ | TNW(10/29 20:04 UTC) "released on Thursday" — 10/29가 목요일 — [TNW](https://thenextweb.com/news/sam-altman-openai-robots-self-replicating-data-centres-cheeky-pint) |
| 1GW당 5년 TCO 약 700억 달러, 200억 달러 목표 | ✅(표현 수정) | "추정치는 다양하다"며 건설과 5년 운영에 700억 달러라는 수치를 썼고, 200억 달러면 "much happier"라고 했다. 공식 목표라기보다 희망치다 — [TNW](https://thenextweb.com/news/sam-altman-openai-robots-self-replicating-data-centres-cheeky-pint) |
| "And so we'll try to make a lot of really cheap compute" | ✅ | 같은 출처 |
| 수학 증명 비용 "order $10 million", "maybe a little more" | ✅ | 나비에-스토크스 증명 비용. 수학 작업 전체가 수억 달러에 이른다는 Collison의 말에도 동의했다("much more other discovery than what we have published"를 포함한다고 함) — 같은 출처 |
| 단일 초지능 반대 / 에이전트 팀 | ✅ | "I would much rather intuitively have a trillion AIs of slightly superhuman intelligence join society than one AI of 1 trillion IQ join society." 'agent swarms'라는 말은 싫어하고 'agent teams'를 선호한다고 했다 — 같은 출처 |
| 샌드박싱은 미해결 | ✅ | "I think sandboxing works to a point. Then I think monitoring works to a further point." — 같은 출처 |
| 로봇으로 데이터센터 건설·"자기 복제 데이터센터" | ✅ | Altman 본인의 표현이다: "There's very little, relatively little talk about self-replicating data centers." 이것이 "within grasp"라고도 했다 — 같은 출처 |
| 메모리 업체 FCF 약 1,000억 달러 | ❌ | TNW에 없다. 대신 "I think the invisible hand is failing right now"(메모리 업체들이 과잉 투자로 파산할 뻔한 기억 때문에 증설에 조심스럽다는 맥락)를 확인했다. |
| "That feels too low"(토큰 지출 1%) | ❌ | TNW에 없음 |
| 로컬 메모리 "quite terrible" | ⚠️(2차) | TechCrunch 관련 검색 결과에 Tom's Hardware 기사 제목("OpenAI CEO says it's 'quite terrible' for your PC to have RAM")이 나오지만 원문은 차단 — [Tom's Hardware(미접속)](https://www.tomshardware.com/tech-industry/data-centers/openai-ceo-says-its-quite-terrible-for-your-pc-to-have-ram-sam-altman-says-data-centers-offer-better-utilization) |

#### [검증 4] Altman — 내부 직원 브리핑 '세 가지 엔드게임' (The Information 보도)
| 이전 노트 내용 | 판정 | 근거·수정 |
|---|---|---|
| Forbes 10/22 인용 | ⚠️ | 확인 가능한 최초 보도는 The Decoder **10/20**이다. 발언 시점은 "지난주"이므로 10/12~16 주로 추정된다 — [The Decoder](https://the-decoder.com/sam-altman-reportedly-pitched-three-endgames-for-ai-safety-one-involving-a-single-firm-melting-everyone-elses-gpus/) |
| 세 경로 중 하나가 경쟁사 GPU를 "녹이는" 결말 | ✅(구체화) | ① IAEA형 국제 감시기구 ② "Demis Plan": 주요 연구소 합병이나 CERN형 단일 기구 ③ "Eliezer Plan": 한 개발사가 자기개선 AI로 경제력을 쥐고 남의 컴퓨트를 차단하거나 극단적으로는 꺼 버리는 시나리오 — 같은 출처 |
| "내부적으로 일극 시나리오를 진지하게 검토"(이전 노트 시사점) | ⚠️ | 보도에 따르면 Altman은 ③을 "완결성을 위해서만" 언급했고 "terrible"하다고 했다. 한 소식통은 Yudkowsky와 Anthropic의 관계를 들어 경쟁사를 겨냥한 농담으로 받아들였다 — 같은 출처 + 검색 스니펫 |
| 1년 안에 경로 선택 | ✅ | "OpenAI plans to pick a path within the next year" — 같은 출처 |

#### [검증 5] Microsoft FY27 Q1 실적 (2026-10-28) — Nadella·Hood
1차 출처: [Microsoft IR 보도자료](https://www.microsoft.com/en-us/investor/earnings/fy-2027-q1/press-release-webcast), [IR 컨퍼런스콜 이벤트 페이지(녹취 포함)](https://www.microsoft.com/en-us/investor/events/fy-2027/earnings-fy-2027-q1), 녹취 단축 링크 https://aka.ms/transcriptfy27q1

| 이전 노트 내용 | 판정 | 1차 원문 값 |
|---|---|---|
| 매출 923억 달러 +19% | ✅ | 922.79억 달러(+19%). 영업이익 459.15억 달러(+21%, 고정환율 +22%) |
| Azure 약 332억 달러 +48% | ✅ | 331.65억 달러, +48% |
| Microsoft Cloud 630억 달러 초과 | ✅(정밀화) | **639억 달러, +30%**(고정환율 +31%). Nadella: 성장이 "accelerating to 30% YoY"(X 스레드) |
| Q2 Azure 가이던스 고정환율 49~50% | ✅ | "In Azure, we expect revenue growth of 49 to 50% in constant currency". Q2 총매출 가이던스 960억~971억 달러(+18~19%) |
| 컨센서스 45.1%(StreetAccount) | ❌ | CNBC 차단 |
| 분기 capex 452억 달러, 제3자 용량 지연 | ✅ | Hood: "Capital expenditures were $45.2 billion, as some third-party capacity deliveries we expected in Q1 were delayed." 금융리스 74억 달러. 약 4분의 3이 단기 자산(CPU·GPU) |
| 예상치 약 507억 달러 | ⚠️ | 확인하지 못했다. TechCrunch는 "회사가 제시했던 500억 달러보다 적다"고 썼다 — [TechCrunch 10/30](https://techcrunch.com/2026/10/30/cracks-are-emerging-in-the-ai-spending-boom/) |
| 2026 역년 capex 약 1,700억 달러 | ✅ | "for the calendar year, spend should be approximately $170 billion due to the 3P capacity delays noted earlier." 연간 기준은 **역년(calendar year)**이다. 'FY27'과 혼동하면 안 된다. |
| Q2 capex 500억 달러 초과 | ✅ | "In Q2, we expect CapEx spend will be over $50 billion." |
| 데이터센터·건물 내용연수 15년→25년 | ❌ | 보도자료와 녹취 모두에 언급이 없다. 10-Q에 있을 가능성은 있으나 sec.gov가 막혀 확인하지 못했다. 최종 보고서에서는 빼거나 '미검증'으로 표기할 것을 권한다. Hood 인용 "operating history and expected use of these assets"도 ❌ |
| 상업용 RPO 6,770억 달러 +73%, 가중평균 2.3년, 12개월 내 약 30% | ✅ | "…grew 73% to $677 billion…"; "weighted average duration of 2.3 years"; "roughly 30% will be recognized in revenue in the next 12 months, up 29% year-over-year." OpenAI 비중은 공개되지 않았다. |
| 상업 예약 감소 | ✅(수치 추가) | "Commercial bookings decreased 12% and 11% in constant currency driven by the impact from large Azure commitments" (전년의 대형 약정 효과) |
| OpenAI 투자 순이익 +2.07억 달러(EPS +0.03) / 전년 31억 달러 손실 | ✅ | 전년 손실의 EPS 영향 −0.41달러. Non-GAAP는 이를 제외한다. GAAP EPS 4.92달러(+32%), GAAP 순이익 366억 달러(+32%) |
| 조정 EPS 4.89달러 +18% | ✅ | Non-GAAP 순이익 364억 달러(+18%) |
| "the new OS for work" | ✅ | "We think of Copilot as the new OS for work." |
| Copilot 일간 사용자 QoQ 약 +50%, YoY 5배 이상 | ✅ | QoQ 약 50%는 녹취에서, YoY 5배는 Nadella의 콜 직후 X 스레드에서 나왔다(TNW 인용) — [TNW](https://thenextweb.com/news/copilot-daily-users-nadella-foundry-agent-365) |
| 5만 석 이상 고객 8배 이상 | ✅ | 녹취와 X 스레드 모두 |
| 질의의 90%가 auto mode | ✅ | "90 percent of Copilot queries use Auto mode, which dynamically routes tasks across models" |
| 멀티모델 고객 5배 | ✅ | "the number of customers building agentic solutions with multiple models increased 5X year over year." |
| "We saw that with some of the OpenAI models in the last quarter. They were fantastic models." | ✅ | 이어지는 말: "…and we're obviously very thrilled about the progress OpenAI has made with Astra" (Goldman Sachs Gabriela Borges 질문에 대한 답) |
| "고객은 Anthropic과 OpenAI가 경쟁하길 원한다" | ✅ | "you want, in fact, Anthropic and OpenAI, by the way, to compete for your workload" |
| "to get more from the infrastructure we already have by optimizing across…" | ⚠️(부분) | 녹취에서 확인된 부분은 "we continue to get more from the infrastructure we already have"까지다. 뒷부분은 인용 길이 제한 때문에 확인하지 못했다. |
| 수요가 공급을 초과 | ✅ | Hood: "Customer demand continues to exceed available supply." (TNW 표기 "We still have demand that exceeds supply"는 다른 발언이거나 요약일 수 있다) |
| 총 Copilot 좌석 수 미갱신 | ✅ | Hood: "we did not disclose… an update on the Copilot number this quarter." |
| 시간외 주가 약 +4% | ❌ | 확인하지 못함 |

#### [검증 6] Nadella — London 기조연설 (2026-10-21)
- ⚠️ 행사명은 'AI Tour'가 아니라 **"Microsoft Frontier Tour London"**이다. 검색 결과에 Microsoft UK Stories 기사 "Microsoft Frontier Tour London: Building trust in the agentic AI era"와 Computer Weekly 기사가 나오지만, 둘 다 원문 접근이 차단됐다. 검색 요약에 따르면 Nadella는 Darren Hardman(Microsoft UK CEO)과 함께 등단했고, "AI 모델을 새로운 형태의 내부자(new forms of insiders)로 보고 제로 트러스트 아키텍처로 감싸라"고 했으며, easyJet·Unilever·Rolls-Royce·NHS 사례를 들었다 — [UK Stories(미접속)](https://ukstories.microsoft.com/features/microsoft-frontier-tour-london-building-trust-in-the-agentic-ai-era/), [Computer Weekly(미접속)](https://www.computerweekly.com/news/366652713/Microsoft-Frontier-Tour-London-Agentic-AI-governance-in-the-spotlight)
- ❌ 이전 노트의 "세 가지 과제(인간 루프·지식 통제·신뢰)"는 원문으로 확인하지 못했다.

#### [검증 7] Nadella — 20VC 팟캐스트 (진행 Harry Stebbings)
| 이전 노트 내용 | 판정 | 근거·수정 |
|---|---|---|
| 공개일 10/26 | ⚠️ | TNW(10/28)는 "new episode"라고만 했다. 정확한 공개일은 확인하지 못했다(10/26~28 사이로 추정) — [TNW](https://thenextweb.com/news/satya-nadella-ai-alignment-20vc) |
| "I used to always think that, you know, alignment will just fall out. I no longer believe that." | ✅ | TNW 표기: "I used to always think that alignment will just fall out. I no longer believe that. So I think this alignment thing may be a harder, different problem." |
| AI 모델을 내부자 위험으로(X 게시물) | ✅(날짜 추가) | X 장문 게시물은 **2026-10-10(토)**. Bloomberg 10/10 보도, TNW 10/12 — [TNW](https://thenextweb.com/news/nadella-ai-models-insider-risks-emergency-brake) |
| Agent 365로 모든 에이전트에 ID 부여·호출 기록 | ✅ | Agent 365와 Perception이 각 에이전트에 ID를 주고 도구·모델 호출을 위변조 불가능한 로그로 남긴다고 했다 — TNW |
| "매우 잔혹한 가격 전쟁" | ❌ | 접근 가능한 출처에 없다. TNW 기준 확인된 것은 "대부분의 AI 사용은 개방형과 폐쇄형을 아우르는 다수 경쟁 모델의 값싼 범용 토큰(cheap commodity tokens) 위에서 돌아갈 것"이라는 전망이다. |
| 5년 내 자체 평가 벤치마크가 핵심 자산 | ❌ | 36Kr 차단 |
| MAI 모델 오픈웨이트 미공개 | ✅ | MAI 모델은 "licensed weights"로, 평범한 소프트웨어 사업으로 판매한다 — TNW |

#### [검증 8] Suleyman — MAI-DxO Science 논문 (2026-10-22, 목)
- ✅ 2026-10-22(목) Science 게재. MAI-DxO는 의사 패널처럼 작동하는 다중 에이전트 오케스트레이션이다. NEJM 복잡 사례 시뮬레이션에서 정답률 83%를 기록했고, 참고자료를 쓴 일반의·내과의는 36%였다(전문의는 비교 대상이 아니었다). Mayo Clinic과 의료 파운데이션 모델을 함께 훈련하고 있으며 "내년" 출시가 목표다 — [TechCrunch](https://techcrunch.com/2026/10/22/microsofts-mustafa-suleyman-says-its-ai-outperforms-doctors-on-hard-cases-as-he-chases-medical-superintelligence/)
- ⚠️ 이전 노트는 "일반의보다 나은"이라고만 했다. 정확히는 **"두 배 이상 자주 정답"**이다. 성능 향상의 상당 부분은 기반 모델(OpenAI GPT-5와 GPT-5.5에서 최고 성적)에서 나왔고, 응급실 사례에서는 개선이 거의 없었다는 한계가 기사에 함께 실렸다.
- ❌→⚠️ [기간 외·맥락]으로 실었던 "학습 1회 수백억~1,000억 달러, 감당 가능한 연구소 5~6곳"은 이 TechCrunch 기사에 **없다**. 출처를 다시 찾아야 한다. 9월 말 Suleyman 발언으로 확인된 것은 Bloomberg 인터뷰의 "통제 레드라인"이다(아래 맥락 참고).

#### [검증 9] Brockman — 슈퍼PAC 'Leading the Future' 2차 기부 철회
- ⚠️ 보도 날짜: NYT(Theodore Schleifer·Mike Isaac) **2026-09-30(수)**, TNW 10/1. 본인의 공개 발언은 없다. NYT가 입수한 6월 사내 Slack 메시지: "I also want to say that I feel terrible about the fact that LTF keeps reflecting on the company and become so much of a distraction for people here… We've donated $25m so far, and have no plans to donate more at this time." ("LTF가 계속 회사 이미지에 영향을 주고 이곳 사람들에게 큰 방해가 된 것이 정말 마음이 무겁다… 지금까지 2,500만 달러를 기부했고, 현재로선 더 기부할 계획이 없다.") — [TNW](https://thenextweb.com/news/greg-brockman-leading-the-future-super-pac-second-25m)

#### [검증 10] 기간 외·맥락 항목
- DevDay(9/29)의 ChatGPT 주간 사용자 12억 명: ✅. 같은 자리에서 ChatGPT Work·Codex 주간 사용자 3,500만 명 이상, OpenAI 제품을 쓰는 기업 250만 곳도 발표했다 — [The Decoder](https://the-decoder.com/openai-revenue-keeps-surging-as-company-seeks-30-billion-in-fresh-capital/)
- Altman의 Fortune IPO 발언 "ill-advised moment to go public": ✅(부분 문구, TechCrunch 검색 요약). IPO는 2027년 초로 연기됐다 — [TechCrunch 10/8](https://techcrunch.com/2026/10/08/openais-revenue-is-reportedly-20-billion-less-than-previously-projected/)
- Pachocki "An Alien Mind" 문구 "no lab has solved alignment and monitoring to a sufficient degree": ⚠️ 검색 스니펫으로만 확인. Axios는 차단.
- Mark Chen "80% of the way": ⚠️ 검색 스니펫으로만 확인. TIME은 차단.
- Fidji Simo: ✅ 3개월 병가가 기대대로 되지 않아 애플리케이션 부문 CEO에서 물러나 파트타임 고문으로 남았다(만성질환). Brockman이 제품 전략을 넘겨받았다 — [TNW](https://thenextweb.com/news/fidji-simo-steps-down-from-openais-number-two-job) (검색 요약)
- **Kevin Weil: ⚠️ 중요 정정.** 2026년 4월 Bill Peebles(Sora), Srinivas Narayanan(엔터프라이즈 CTO)과 같은 날 OpenAI를 떠났다. 그가 이끌던 OpenAI for Science는 독립 조직으로 남아 있지 않다. 따라서 기간 내 'OpenAI 임원으로서의' 발언은 있을 수 없다 — [TNW](https://thenextweb.com/news/openai-departures-kevin-weil-sora-peebles-enterprise-pivot), [The Decoder](https://the-decoder.com/openai-loses-three-executives-in-one-swoop-as-restructuring-reshapes-its-product-lineup/) (검색 요약)

### Inferences
- 이전 노트의 오류는 대부분 ① 2차 요약에서 나온 숫자(내용연수 25년, 컨센서스, 메모리 FCF)나 ② 발언 장소를 혼동한 경우('speed limit')에서 생겼다. 1차 IR 자료로 확인한 Microsoft 숫자는 사실상 모두 맞았다.
- 'GPU 녹이기' 시나리오를 근거로 "OpenAI가 일극 시나리오를 진지하게 검토한다"고 해석하는 것은 보도 원문과 맞지 않으므로 최종 보고서에서 빼야 한다.

### Gaps
- Politico 원문, Berman 인터뷰 YouTube와 녹취, Cheeky Pint 전체 녹취(Substack), 20VC 원본, Fortune·Forbes 기사는 도메인 차단으로 원문 대조를 하지 못했다.
- Microsoft 10-Q 원문(내용연수, OpenAI 관련 공시)은 sec.gov 차단으로 확인하지 못했다. OpenAI 관련 10-Q 수치는 TechCrunch 인용으로 대체했다(아래).

---

## 핵심 질문 2: 이전 노트가 놓친 기간 내 발언·공식 발표 (재스윕 결과, 날짜순)

### Takeaway
이전 노트가 놓친 기간 내 핵심 자료는 다음과 같다. **Nadella의 X 장문 게시물(10/10, "모델을 내부자 위험으로, 비상 브레이크")**, **Altman의 Stanford GSB 대담(10월 셋째 주, "패치로는 못 막는다, 좁은 의미의 초지능은 이미 있다, 속도 조절을 다시 생각해야")**, **Altman의 Politico 정치자금 발언("Something's clearly not working")**, **Brockman의 Google Cloud(10/21)·Oracle(10/27) 제휴 발언**, OpenAI 공식 발표(10/26 ETH 반증 주장·GPT-6.1 Terra, 10/29 Model Spec 개정), Microsoft의 OpenAI 매출 공시(분기 100억 달러), GitHub Universe(10/28), Microsoft 6만 명 대상 자발적 퇴직(10/26), 채권 발행(10/29), OpenAI Chris Lehane의 'AI speed limits'·'AI compute campuses' 구상(11/1).

### Cited Findings

#### [신규 A] Altman — Politico Decoded 같은 인터뷰, 정치자금 발언 (2026-10-04~05)
- 형식/매체: Politico Decoded 팟캐스트 첫 회. 보도: [TNW 10/5](https://thenextweb.com/news/sam-altman-ai-money-politics-not-working)
- 요약: Altman은 AI 업계가 미국 정치에 쏟아붓는 돈이 기술에 대한 대중 인식을 개선하지 못했다고 평가했다. 사람들은 AI 도구를 즐겨 쓰면서도 일자리와 소수에 집중된 권력을 불안해하며, 정치 지출로는 그 불안이 풀리지 않는다고 했다. 업계 상당 부분이 이 불안에 '둔감(tone-deaf)'하다고도 했다. Brockman의 2,500만 달러 기부와 2차 기부 철회 보도를 묻자 "보도를 보지 못했고 답하고 싶지 않다"고 했다. 자신은 과거 개별 후보를 후원했지만 지금은 하지 않는다고 했는데, AI가 너무 중심적인 산업이 됐고 OpenAI가 정부와 거래하기 때문이라고 설명했다. 2028년 대선 전에 업계가 정치 지출을 줄이자고 합의해야 하느냐는 질문에는, 정치 자금이 훨씬 줄기를 바라지만 업계가 일방적으로 무장해제할 힘은 없다고 봤다. 다만 전체 정치 자금을 줄이는 방안은 지지하겠다고 했다. Gavin Newsom 주지사를 높이 평가했다.
- 인용: "Something's clearly not working." — "뭔가가 분명히 작동하지 않고 있다."
- 시사점: '규제는 가볍게'(검증 1) 발언과 같은 인터뷰에서 '정치자금 회의론'과 '일자리·권력 집중 불안'을 인정했다. 이는 11월 중간선거 이후 OpenAI의 PR 재정비 구상(신규 M)과 이어진다.

#### [신규 B] Nadella — X 장문 게시물 "AI 모델을 내부자 위험으로" (2026-10-10, 토)
- 형식/매체: X 장문 아티클. 보도: [TNW 10/12](https://thenextweb.com/news/nadella-ai-models-insider-risks-emergency-brake), [Bloomberg 10/10(미접속)](https://www.bloomberg.com/news/articles/2026-10-10/microsoft-ceo-nadella-calls-for-emergency-brake-on-advanced-ai)
- 요약: Nadella는 기업이 배포하는 모든 고급 AI 모델이 침해될 수 있다고 가정하고 처음부터 격리해야 한다고 주장했다. 전통적 소프트웨어는 특정 코드 경로까지 추적할 수 있지만, 지금의 모델은 행동을 학습 데이터나 가중치와 연결할 수 없다. 그런데도 기업은 민감한 데이터와 "mission-critical actions"를 맡기고 있으며, 모델 제공사의 보증이 그 책임을 없애 주지 않는다고 했다. 해법으로 폐쇄형이든 오픈웨이트든 프런티어 모델을 '내부자 위험'으로 다루자고 했다. 악의가 있어서가 아니라, 중요 시스템에 접근하는 유능한 행위자는 누구든 실수하거나 공격자에게 탈취될 수 있기 때문이다. 7개 원칙을 제시했다. 단일 모델이 중요한 결과의 유일한 의존처가 되거나 스스로를 검증하지 않을 것, 모든 의미 있는 행동에 "tamper-proof human readable evidence"를 남길 것, 시스템 전체를 상시 테스트할 것, 모델의 접근 범위는 기업이 정할 것, 감사가 감사 대상 모델에 의존하지 않을 것, 격리(비상 브레이크), 사고 공개다. 투명한 추론 공개는 "non-negotiable"이지만 그것만으로는 충분하지 않다고 했다. Suleyman은 이 글을 공유하며 초지능은 "must be contained"라고 했고, Elon Musk와 Ted Lieu 하원의원도 반응했다. 글 전체에 트럼프가 정부 기관에 쓰도록 지시한 용어 "Super Intelligence"를 썼다.
- 인용:
  - "Think of it like an emergency brake. An authorized person should always be able to pause or shut down a model mid-task." — "비상 브레이크라고 생각하라. 권한 있는 사람은 언제든 작업 도중의 모델을 일시 중지하거나 끌 수 있어야 한다."
  - "We need to separate the supply of intelligence from the authority over it." — "지능의 공급과 그에 대한 권한을 분리해야 한다."
  - "The most trustworthy Super Intelligence system will not be the one with the model we trust most. It will be the one that enables us to trust the model the least." — "가장 신뢰할 만한 초지능 시스템은 우리가 가장 신뢰하는 모델을 가진 시스템이 아니라, 모델을 가장 덜 신뢰해도 되게 해 주는 시스템일 것이다."
- 후속: 10/19 Microsoft Security EVP Hayete Gallot가 블로그에서 "에이전트를 내부자로 다루라"고 했고, Microsoft 365 E7에 Dynamic Permissions와 Dynamic Agent Risk 같은 기능을 발표했다. 부CISO Terrell Cox: "At Microsoft, we are already operating in a world of hundreds of thousands of agents." — [TNW 10/19](https://thenextweb.com/news/microsoft-365-e7-ai-agents-dynamic-permissions)
- 시사점: 20VC의 '정렬 낙관론 철회'(검증 7), Frontier Tour 런던 연설(검증 6), 실적 콜의 Agent 365·Perception과 이어지는 Microsoft의 10월 일관 메시지다. "모델은 범용재, 신뢰·통제 레이어가 Microsoft의 해자"라는 전략이다.

#### [신규 C] Nadella — 20VC 추가 발언 (검증 7 보강)
- 출처: [TNW 10/28](https://thenextweb.com/news/satya-nadella-ai-alignment-20vc)
- 요약: Nadella는 2018~19년 스케일링 법칙을 믿었고, 그 시절 Amodei, Sutskever, Altman, Brockman, Musk가 "one happy family"였다고 회고했다. 스케일링은 예상대로 작동했지만 정렬은 따라오지 않았다고 했다. 정렬은 주로 학습 단계에서, 어쩌면 사전학습에서부터 이뤄져야 한다고 봤다. 사슬형 사고(CoT)는 믿을 수 없으며, 신뢰할 만한 파트너에게 평문으로 공개돼야 한다고 했다. 폐쇄형 모델 제작사가 투명성의 필요를 인정하지 않으면 고객이 오픈웨이트로 이동할 수 있다고 경고했다.
- 인용:
  - "I don't think you can even RL your way to alignment." — "강화학습만으로 정렬에 도달할 수 있다고도 생각하지 않는다."
  - "If you really want to have agents that are more capable and yet less aligned, then you need to have a trust system that you can rely on." — "더 유능하지만 덜 정렬된 에이전트를 원한다면 의지할 수 있는 신뢰 시스템이 필요하다."
  - "We know that the chain of thought itself can be unfaithful, and in fact it can be made worse when the model company says, 'Well, it's unfaithful and I'm going to hide it.'" — "사슬형 사고 자체가 충실하지 않을 수 있다는 걸 우리는 안다. 모델 회사가 '어차피 충실하지 않으니 숨기겠다'고 하면 오히려 더 나빠질 수 있다."
  - "An unaligned open-weight Chinese model will probably attack even China." — "정렬되지 않은 중국산 오픈웨이트 모델은 아마 중국까지 공격할 것이다."
- 시사점: CoT를 숨기는 프런티어 연구소(이름은 밝히지 않았다)를 겨냥했다. OpenAI Astra의 CoT 가시성 논란(9월)과 같은 시기다.

#### [신규 D] OpenAI 인프라 조직 개편 — Uday Ruddarraju (2026-10-14)
- 출처: [TNW 10/14](https://thenextweb.com/news/openai-ruddarraju-compute-infrastructure) (Bloomberg 인용)
- 요약: 전 xAI 인프라 책임자 Ruddarraju(2025년 7월 입사, 2026년 7월 컴퓨트 CTO)가 컴퓨트와 인프라 사업을 통합해 맡는다. Sachin Katti는 몇 주 안에 물러나 고문으로 남는다. Katti가 맡던 GPT-Infra(OpenAI 모델로 반도체 설계 등)는 칩 책임자 Richard Ho에게 넘어간다. OpenAI가 투자자에게 보여 준 컴퓨트 청구서 8,560억 달러 대부분은 미국에서 쓰인다.
- 인용: Ruddarraju "Sachin has done an incredible job maintaining the commercial partnerships"; Katti "I'm proud of what we've built and have total confidence in Uday and the team."
- [기간 외·맥락] Richard Ho(하드웨어 책임자)의 More Than Moore 인터뷰(9/30 공개, TNW 10/5): 자사 AI 모델이 Jalapeño 칩 설계를 고쳐 다이 면적을 13% 넘게 줄였지만 "I still don't 100% trust them"이라고 했다. 업계의 진짜 병목은 전력이나 메모리가 아니라 경영진과 투자자가 AI가 얼마나 커질지 보지 못해 너무 작게 베팅하는 것이라고 했다. "Because we still need GPUs, and we want GPUs to get better." — [TNW](https://thenextweb.com/news/openai-jalapeno-chip-richard-ho-ai-design)

#### [신규 E] Altman — Stanford GSB "View From The Top" 대담 (10월 셋째 주, 10/19~23 추정)
- 형식/매체: Stanford GSB 공개 대담(진행 MBA 학생 Claudia Chen), GSB 공식 YouTube 공개(원본 영상 미접속). 보도: [TNW 10/26](https://thenextweb.com/news/sam-altman-patch-all-the-bugs-ai-cybersecurity-stanford). TNW는 "last week", "PHP2Shell 취약점 주간"이라고 표현했다. 정확한 날짜는 확인하지 못했다.
- 요약: 경영자가 AI 위험 중 무엇을 챙겨야 하느냐는 질문에 Altman은 사이버보안을 꼽았다. 조직과 국가와 개인이 아직 위협을 진지하게 받아들이지 않는다고 했다. 올해 초 "Mythos freakout" 때 사람들은 버그 몇 개를 고치고 모델이 찾을 것은 다 찾았다고 여겼지만, 모델은 계속 좋아졌고 리더 대부분은 "somewhat moved on" 했다고 지적했다. 버그를 하나씩 패치하는 방식으로는 더 이상 버틸 수 없고, 같은 AI로 만든 새로운 방어막으로 전환해야 한다고 했다. 지난 6개월이 자기 신념을 시험했다며, 수학 추론에서는 OpenAI가 "in some narrow senses" 이미 초지능을 갖고 있다고 했다. 정렬은 지금까지 예상보다 쉬웠지만 계속 그럴지는 모르며, 세계 일부 AI 진영이 정렬을 과신해 "too willing to run ahead" 하고 있다고 경고했다. 사회에는 꽤 높은 수준까지 오픈웨이트 모델이 필요하지만, OpenAI 최고 내부 모델의 가중치는 "anytime soon" 공개할 수 없다고 했다. 일자리에 대해서는 "a job apocalypse"를 예상하지 않으며, 많은 작업과 일부 직종이 바뀔 것이라고 했다. OpenAI 수학 성과가 나온 뒤 며칠 만에 수학자들이 "we're cooked"에서 새로운 경력 계획으로 옮겨 갔다는 일화도 들었다. 다음 투자처로는 로봇을 만드는 로봇, 데이터센터를 짓는 데이터센터, Jalapeño 칩과 후속작, 팹·전력·장비 공급망을 들었다.
- 인용:
  - "I no longer think we're going to be able to just patch all the bugs. I think we're going to have to completely switch the defense model to sort of using the same technology for sort of a new kind of defense shield." — "이제 모든 버그를 그냥 패치할 수 있을 거라고 생각하지 않는다. 같은 기술을 써서 새로운 종류의 방어막을 만드는 쪽으로 방어 모델을 완전히 바꿔야 할 것이다."
  - "I think it's a huge safety and security issue, and I am somewhat astonished at how relatively little attention it's getting." — "엄청난 안전·보안 문제인데, 상대적으로 관심을 너무 못 받고 있어서 다소 놀랍다."
  - "We're going to have to make some changes to how we think about pacing progress from here." — "앞으로 진보의 속도를 어떻게 조절할지에 대한 생각을 일부 바꿔야 할 것이다."
- 시사점: 기간 내 Altman이 **일자리**("job apocalypse 아님")와 **초지능 도달**("좁은 의미로 이미")을 가장 명시적으로 언급한 자리다. 이전 노트 Gaps의 "일자리 발언 없음"과 "AGI 시간표 발언 없음"을 일부 메운다. '속도 조절' 언급은 내부 'speed limit' 불평(검증 2·4)과 같은 흐름이다.

#### [신규 F] Brockman — OpenAI 모델·Codex의 Google Cloud 공급 (2026-10-21, 수)
- 형식/매체: 공동 발표, OpenAI 블로그와 Google 블로그(원문 미접속). 보도: [TNW 10/21](https://thenextweb.com/news/openai-models-codex-google-cloud)
- 요약: GPT-6 Astra, GPT-6.1 Sol, GPT-6 Luna를 Google Cloud Model Garden에 비공개 프리뷰로 제공한다. 몇 주 안에 정식 출시할 계획이다. 이로써 OpenAI 모델이 미국 3대 클라우드에 모두 올라갔다(AWS는 Microsoft 독점 라이선스가 끝난 뒤인 4월부터). OpenAI는 "Microsoft remains OpenAI's primary cloud partner"라고 밝혔다.
- 인용: Brockman "This partnership is an important step in making our most capable models and Codex available where customers are already building." — "이 파트너십은 가장 유능한 모델과 Codex를 고객이 이미 개발하고 있는 곳에서 쓸 수 있게 하는 중요한 단계다."
- 시사점: OpenAI의 탈(脫)Microsoft 멀티클라우드화가 완성됐다. 같은 시기 Nadella의 멀티모델 발언("Anthropic과 OpenAI가 경쟁하길 원한다")과 대칭을 이룬다.

#### [신규 G] OpenAI의 공격적 할인 (The Information 2026-10-24 보도)
- 출처: [TNW 10/26](https://thenextweb.com/news/openai-discounts-anthropic-customers-replit-rippling)
- 요약: Replit은 OpenAI가 30% 넘는 할인을 제시하자 AI 지출 대부분을 Anthropic에서 OpenAI로 옮겼다(연 1억 달러 이상 계약). Rippling CEO Parker Conrad에 따르면 코딩 작업 중 OpenAI 비중이 5월 16%에서 52%로 늘었고, Anthropic은 57%에서 18%로 줄었다. DataCamp는 비용이 80~90% 줄었다. 한 은행은 ChatGPT 좌석을 사용자당 7달러 미만에 쓰고 있다. 9/22 OpenAI는 Sol과 Luna로 GPT-6 가격을 절반으로 내렸다.
- 시사점: 리더 본인의 발언은 아니지만, Nadella의 "범용 토큰"과 Hood의 "예상보다 높은 토큰 가격"(신규 J)과 함께 기간 내 **가격 경쟁**의 실체를 보여 준다.

#### [신규 H] OpenAI 공식 발표 (2026-10-26, 월) — ETH 반증 주장, 국소 평활 추측, 4차원 양자장론 존재 증명
- 출처: OpenAI 블로그(미접속), [TNW 10/26](https://thenextweb.com/news/openai-exponential-time-hypothesis-false-kakeya-yang-mills)
- 요약: OpenAI는 내부 모델이 10/16 지수 시간 가설(ETH)의 반증을 찾았고 다음 날 Lean으로 검증했다고 발표했다. ETH 제안자인 Impagliazzo·Paturi와 MIT의 Ryan Williams가 독립 검증을 이끈다(NDA 없음, 무보수). 이들은 "Our involvement should not be taken as certification of the claim."이라고 밝혔다. 수학에서는 국소 평활 추측(Sogge, 1991)을 전 차원에서 증명했다고 했고, 이것으로 Kakeya 추측과 Stein 제한 추측도 해결된다고 주장했다. 물리학에서는 QCD를 포함한 4차원 양자장론의 존재를 증명했다고 했다(밀레니엄 문제인 Yang-Mills 존재 포함). 이 결과는 David Gross가 이끄는 그룹이 검토한다. OpenAI는 10/6에 수학 논문 722편을 공개했다.
- 시사점: Altman의 "수학에서는 좁은 의미의 초지능"(신규 E)과 Cheeky Pint의 "공개하지 않은 발견이 훨씬 많다"(검증 3)를 뒷받침하는 공식 주장이다. 모두 **미검증 주장** 단계다.

#### [신규 I] OpenAI GPT-6.1 Terra 출시 (2026-10-26)
- 출처: OpenAI 발표(미접속), [TNW 10/26](https://thenextweb.com/news/openai-gpt-6-1-terra-computer-use)
- 요약: 화면을 읽고 클릭하는 컴퓨터 사용 중심의 중간급 모델(Sol·Astra 아래, Luna 위)이다. API 가격은 입력 100만 토큰당 1달러, 출력 5달러로 GPT-5.6 Terra의 절반이다. OpenAI 자체 테스트에서 Claude Opus 5.5 대비 약 9분의 1 비용이라고 했다. Preparedness Framework 사이버 능력 "Critical" 등급이다. 지난달에는 GPT-6.1 Astra를 내부 안전 테스트 실패로 취소했다.
- 시사점: DevDay 이후 '같은 능력을 더 싸게' 기조가 이어지고 있다. 이전 노트 Gaps의 "기간 내 가격 정책 변화 없음"은 틀렸다.

#### [신규 J] Microsoft FY27 Q1 콜의 추가 발언 (검증 5 보강, 10/28)
- 출처: [Microsoft IR 이벤트 페이지 녹취](https://www.microsoft.com/en-us/investor/events/fy-2027/earnings-fy-2027-q1)
- Nadella(인프라): "Accelerating demand led to us adding 24 new data centers across five continents this quarter." / "with a fungible fleet that allows us to dynamically allocate capacity to the highest-value opportunities" / "Maia 200 is already delivering up to 1.7 times more tokens per watt across AI experiences in Teams and Copilot." GW 수치는 언급하지 않았다.
- Nadella(MAI): "Our goal is to advance the cost to outcome frontier" / "delivering capabilities comparable to leading models within three to six months of their release" / "we recently completed pre-training MAI-Base-2, which outperforms other open weight models we tested". 선두 모델이 나온 뒤 3~6개월 안에 비슷한 능력을 따라잡겠다는 '패스트 팔로어' 전략을 공식화했다.
- Nadella(GitHub·에이전트): "Agent generated PRs have increased 6X over the past six months." / "agents now open more than a third of all PRs on the platform." / "Over 50 million agents are now in the registry, up over 30 percent quarter over quarter."
- Nadella(수요 성격, Bernstein Mark Moerdler 질문): "The breadth finally does feel like the enterprise workloads." / "It's a decade-long thing, and that's what I've been waiting for." — 기업 워크로드로 수요가 넓어지고 있다고 봤다.
- Nadella(인프라 풀): "we have one pool, and we want to get the pool to be as efficient and fungible."
- Hood(가격): "We had higher token pricing than we expected in the quarter." — "이번 분기 토큰 가격이 예상보다 높았다." (UBS Karl Keirstead 질문)
- Hood(마진): 영업이익률이 약 50%로 소폭 올랐고, Q2에는 전년 대비 소폭 하락할 것이라고 했다. "the best solution here is revenue growth."
- Hood(M365 소비형 과금): "it will be a slower move outside of coding" — 코딩 밖으로의 소비형 과금 전환은 더디게 진행될 것이라고 했다.
- Hood(자금 조달): "we have a lot of flexibility in terms of our capacity to raise financing." 리스를 활용하고 있으며 부채 시장은 "we haven't yet… tap that"이라고 했다. FY27 잉여현금흐름 흑자를 유지할 것으로 예상한다. 자발적 퇴직 프로그램 비용 추정치를 가이던스에 포함했다.
- 운영현금흐름 580억 달러, 잉여현금흐름 186억 달러(TNW 기준 −27%), 주주환원 102억 달러. Foundry 고객 12만 곳 이상(매출 3배 이상), Fabric 유료 고객 4.4만 곳 이상.
- 세그먼트 재편: FY27부터 'Agents and Infra'(768억 달러, +25%)와 'Devices and Consumer'(155억 달러, −3%) 2개 세그먼트로 바꿨다. Windows OEM·디바이스 −22%, Xbox 콘텐츠·서비스 −2% — [보도자료](https://www.microsoft.com/en-us/investor/earnings/fy-2027-q1/press-release-webcast)

#### [신규 K] Nadella — 실적 발표 직후 X 스레드와 LinkedIn (10/28)
- 출처: [TNW 10/29](https://thenextweb.com/news/copilot-daily-users-nadella-foundry-agent-365), [TNW GitHub Universe](https://thenextweb.com/news/github-universe-copilot-fusion-octoverse-agents)
- 요약: Chat, Cowork, Autopilot, Code를 하나로 묶은 "biggest update to Copilot to date"를 발표했다. 사용자 만족도는 전분기 대비 약 20% 올랐고, 사용량 기반 Copilot 유료 고객은 75% 넘게 늘었다(Fortune 인용). Foundry에서는 멀티모델 고객이 5배, 오픈소스 모델 매출이 10배가 됐다. Microsoft IQ 고객은 약 6만 곳(전분기 대비 +25%)이다. Agent 365와 Windows를 결합한 MXC 위에서 OpenAI Codex, Anthropic Claude Code, Meta Muse가 돌아간다. Hood는 M365 E7이 "millions of paid seats"에 이르렀다고 했다.
- 인용:
  - "Just wrapped our earnings call. It was a fast start to our fiscal year." — "실적 콜을 막 마쳤다. 회계연도를 빠르게 시작했다."
  - "The next frontier is maximizing intelligence per task while continuously optimizing for cost and performance." — "다음 프런티어는 비용과 성능을 끊임없이 최적화하면서 작업당 지능을 극대화하는 것이다."
  - "We're separating intelligence from authority." — "우리는 지능과 권한을 분리하고 있다."
  - "…helping every organization stand up their own infinite SaaS factory." — "모든 조직이 자기만의 무한 SaaS 공장을 세우도록 돕는다."
  - GitHub Copilot Fusion(LinkedIn): 프런티어급 품질을 40% 더 빠르게, 최대 77% 더 싸게 제공한다.

#### [신규 L] GitHub Universe (10/28) — Jay Parikh (Microsoft CoreAI EVP)
- 출처: [TNW](https://thenextweb.com/news/github-universe-copilot-fusion-octoverse-agents), [GitHub 블로그(미접속)](https://github.blog/news-insights/company-news/github-universe-2026-evolving-every-layer-of-the-stack/)
- 요약: Copilot Fusion은 작업 단계마다 모델 조합을 고른다. Parikh에 따르면 Fusion Max는 Artificial Analysis Coding Agent Index에서 Claude Opus 5.5 Max와 2점 이내로 근접했고, 비용은 절반, 작업당 시간은 40% 짧았다. GitHub Enterprise 고객은 별도 구독 없이 모든 Copilot 기능을 쓰고 사용한 AI 크레딧만큼 낸다. Octoverse에 따르면 9월 PR의 40% 이상이 에이전트 초안으로 시작했다(3월 17%, 9월 한 달 1.1억 건). 연간 푸시는 179억 회, 개발자는 2.25억 명이다.
- 인용: Parikh "I think all the software we've written to date will amount to less than 1% of the software we'll write in the next five years." — "지금까지 작성한 모든 소프트웨어는 앞으로 5년간 작성할 소프트웨어의 1%도 안 될 것이다."

#### [신규 M] Microsoft의 OpenAI 관련 공시 (10-Q, 10/28)
- 출처: [TechCrunch 10/28](https://techcrunch.com/2026/10/28/microsoft-recorded-10-billion-in-revenue-from-openai/) (10-Q 인용, sec.gov 원문 미접속)
- 내용: 9월 분기에 OpenAI와의 상업 계약(수익 공유 포함)으로 100억 달러 매출을 올렸다. 총매출의 약 11%로, 실적 콜에서 Goldman Sachs 애널리스트도 "OpenAI at 11% of revenue"를 언급했다. FY26 연간은 241억 달러다. OpenAI 미수금은 72억 달러로 6월 60억 달러에서 늘었다. 지분율은 6월 약 25%에서 9월 24%로 낮아졌다(2025년 10월 재자본화 직후 약 27%). 2026년 4월 합의로 OpenAI는 상한 내에서 2030년까지 수익 공유를 계속한다.
- 시사점: 표면적으로는 경쟁이 심해지는 가운데서도 Microsoft 매출의 11%가 OpenAI에서 나온다. 수주잔고 집중 리스크를 판단할 직접 근거다.

#### [신규 N] Microsoft 인력·지배구조·자금조달 (10/21~10/29)
- 10/21(수) 연례 위임장: Stripe의 John Collison을 이사 후보로 지명했다. Nadella 보수 패키지는 9,060만 달러로 전년 9,640만 달러보다 약 6% 줄었는데, Xbox 매출 감소가 현금 보너스를 깎았다(The Information). 주총은 12/8 — [TNW 10/23](https://thenextweb.com/news/john-collison-microsoft-board-nadella-pay)
- 10/26 자발적 퇴직(Voluntary Exit Offer): 최고인사책임자 Amy Coleman이 메모로 발표했다. 대상은 약 6만 명(전체 22.3만 명의 약 4분의 1)이고, Copilot·CoreAI·Windows·Xbox 등이 포함되며 영업 조직은 빠진다. 인용: "This offer gives eligible employees who may be considering a future outside the company a new choice to make that transition now with support." 회사는 정리해고를 대체하지 않으며 인력 축소 신호도 아니라고 했다 — [TNW 10/26](https://thenextweb.com/news/microsoft-buyouts-60000-employees-voluntary-exit-offer)
- 10/29 채권: 2017년 이후 첫 미국 우량 회사채로 최소 250억 달러, 최대 10개 트랜치, 만기 2~40년이다(Bloomberg). 실적 콜에서 Hood가 "부채 시장은 아직 쓰지 않았다"고 한 바로 다음 날이다 — [TNW 10/29](https://thenextweb.com/news/microsoft-25-billion-bond-sale-first-since-2017)
- 시사점: AI 투자 재원을 위해 인건비 구조조정과 차입을 병행하기 시작했다. "AI 때문에 일자리가 줄어드느냐"는 질문에 대한 Microsoft의 공식 답은 "인력 축소 신호가 아니다"다.

#### [신규 O] Brockman — Oracle AI World OpenAI 제휴 (10/27)
- 출처: [TNW 10/28](https://thenextweb.com/news/oracle-ai-world-google-tpus-openai-chatgpt)
- 요약: Oracle 업무 앱(Fusion, NetSuite, DB)에 ChatGPT 플러그인과 Codex 기반 App Composer, OpenAI 사이버 모델 기반 AI Security Mesh를 넣는다. OpenAI Jalapeño 칩도 OCI에서 운용한다(CNBC). 같은 날 The Information은 OpenAI가 Google TPU를 구매할 계획이라고 보도했다 — [TNW](https://thenextweb.com/news/openai-google-tpu-chips)
- 인용: Brockman "More businesses are choosing OpenAI as we make it easier to put AI to work through the tools and systems they already use." — "기존 도구와 시스템에서 AI를 쓰기 쉽게 만들수록 더 많은 기업이 OpenAI를 선택하고 있다."

#### [신규 P] OpenAI Model Spec 전면 개정 (10/29)
- 출처: OpenAI 블로그(미접속), [TNW 10/29](https://thenextweb.com/news/openai-model-spec-five-values-update)
- 요약: Model Spec을 다섯 가치로 재편했다. 인간 의도에 대한 충실성, 피해 최소화, 정직·투명성, 인간 주체성, 배려다. 스타일 규칙 대부분을 없앴고, 모델 호칭을 "the assistant"에서 "GPT"로 바꿨다. 아첨을 하지 말라는 지침을 넣었다. OpenAI는 모델이 Spec을 "do not yet fully reflect" 한다고 인정했다.
- 인용(OpenAI): "As our models get smarter and take more consequential actions in the world, it becomes increasingly important that they go beyond just interpreting the specific instructions they receive." — "모델이 똑똑해지고 세상에서 더 중대한 행동을 할수록, 받은 구체적 지시를 해석하는 데서 그치지 않는 것이 점점 더 중요해진다."

#### [신규 Q] OpenAI 안전 연구원 해고 관련 공식 입장 (WSJ 10/22 보도)
- 출처: [TNW 10/25](https://thenextweb.com/news/openai-safety-researchers-fired-signal-chats-greenblatt-wsj)
- 요약: 9월에 해고된 안전 연구원 3명(Tomek Korbak, Mikita Balesni, Jasmine Wang)이 유출 조사 과정에서 개인 휴대폰 검사를 받았다. Pachocki는 Astra의 CoT 가시성을 다룬 9/1 The Information 보도를 "confused"라고 평했고, 이 보도가 유출 조사의 발단이었다. 기간 내 Pachocki 본인의 새 공개 발언은 찾지 못했다.
- 인용(OpenAI 회사 입장): 해고는 "not for raising safety concerns or speaking out." — "안전 우려 제기나 공개 발언 때문이 아니었다." Korbak(X): "Best explanation I have for our firing: talking to auditors was too much safety, disappearing messages were too much security, and we should have paced ourselves."

#### [신규 R] OpenAI Chris Lehane(글로벌 대외협력 책임자) — 중간선거 이후 PR 구상 (Axios, 11/1)
- 출처: [TechCrunch 11/1](https://techcrunch.com/2026/11/01/openai-might-rebrand-its-data-centers-as-ai-compute-campuses/)
- 요약: 11/3 중간선거(민주당 하원 탈환이 유력) 이후 'PR 공세'를 준비 중이다. AI "speed limits" 개발, AI가 일상에서 사람에게 힘을 실어 준다는 인식 확산, 글로벌 표준 주도, 데이터센터를 "AI compute campuses"로 이름 바꾸기를 논의하고 있다.
- 인용: Lehane "Communities should hold companies responsible and accountable so they really and truly get a transformative benefit from these projects." — "지역사회는 기업에 책임을 물어 이 프로젝트에서 진정으로 변혁적인 혜택을 얻어야 한다."
- 시사점: 내부의 'speed limit' 불평(검증 4)이 대외 정책 의제로 공식화되는 단계다.

#### [신규 S] Kevin Scott (Microsoft CTO) — Fast Company 기사 (10/28)
- ⚠️ 원문은 차단됐고 검색 요약으로만 확인했다. Scott과 Suleyman이 가속기, 코드 생성, 맞춤형 모델이 Microsoft의 소프트웨어 개발 방식을 바꾸고 있다고 설명했다. Scott은 "for net-new things, all of that code is getting written by AI right now"라는 취지로 말했다. 문구는 미검증이다 — [Fast Company(미접속)](https://www.fastcompany.com/91607730/microsoft-ai-copilot-autopilot-kevin-scott-charles-lamanna-mustafa-suleyman)

#### [신규 T] OpenAI 매출·자금조달 수치 (모두 보도, OpenAI 공식 공시 없음)
- FT(10/8): OpenAI는 투자자들에게 9월 말 연환산 매출이 "approaching $50 billion"(순액 기준)이라고 말했다. 앞서 보도된 약 700억 달러는 "attempts by OpenAI's own investors to produce a direct comparison with Anthropic's annualised revenues"에서 나온 수치다. 보도 다음 날 나스닥은 1.25% 떨어졌다 — [TechCrunch 10/8](https://techcrunch.com/2026/10/08/openais-revenue-is-reportedly-20-billion-less-than-previously-projected/), [TNW 10/9](https://thenextweb.com/news/openai-revenue-70bn-year-end-50bn-september)
- Bloomberg(10/9): 연말 연환산 매출이 700억 달러 이상에 이를 것으로 예상하며, 성장은 엔터프라이즈가 이끈다. CNBC: 3분기 총 런레이트 +77%, 엔터프라이즈 +107%. The Information: CFO Sarah Friar가 6월 말부터 9월 말까지 런레이트가 70% 늘었다고 말했다 — [TNW 10/9](https://thenextweb.com/news/openai-revenue-70bn-year-end-50bn-september), [The Decoder](https://the-decoder.com/openai-revenue-keeps-surging-as-company-seeks-30-billion-in-fresh-capital/)
- ⚠️ 이전 노트의 "8월 ARR 400억 달러 이상"은 Bloomberg와 The Information 보도로 확인했다. 다만 이 수치에는 Microsoft가 Azure에서 OpenAI 모델을 팔 때 받던 매출(4월 계약 갱신으로 중단)이 섞여 있었다는 단서가 붙는다 — 같은 TNW
- 회계 기준 차이: Anthropic은 클라우드 파트너 매출을 총액으로, OpenAI는 자기 몫만 순액으로 잡는다. 둘 다 US GAAP 범위 안이다(Axios) — [The Decoder](https://the-decoder.com/openai-revenue-keeps-surging-as-company-seeks-30-billion-in-fresh-capital/)
- 자금조달: 1.25조 달러(프리머니)에 최대 300억 달러를 모으는 중이며 Coatue와 UAE가 주도한다(CNBC 10/22). 앞서 Bloomberg는 1.4조 달러를 보도했다. FT(10/30~31)는 목표를 200억 달러로 낮췄고 1차 클로징은 그보다 적을 것이라고 했다. WSJ는 지금까지 110억 달러를 확보했고 일부 대형 투자자의 반응이 "tepid"라고 했다. 2026년 3월 조달 당시 기업가치는 8,520억 달러(포스트)였고, IPO 서류는 6월에 비공개로 제출했다 — [TechCrunch 10/22](https://techcrunch.com/2026/10/22/openai-working-on-new-30b-raise-at-1-25t-valuation-ahead-of-ipo/), [TechCrunch 10/31](https://techcrunch.com/2026/10/31/openai-reportedly-lowers-funding-target-for-new-round/)

### Inferences
- 10월 두 회사 리더의 공통 키워드는 **'통제·격리(containment)'**와 **'속도 조절(pacing)'**이다. Nadella는 비상 브레이크와 내부자 위험을, Suleyman은 "must be contained"를, Altman은 패치 불가능성과 pacing 재고, 단일 모델 지능 제한을 말했고, Lehane은 speed limits를 말했다. 동시에 상업 측면에서는 할인, 가격 인하, 멀티클라우드, 대규모 차입으로 확장 속도를 늦추지 않는다. '수사는 감속, 사업은 가속'의 이중 구조다.
- Microsoft 메시지는 "모델은 교체 가능, 우리는 신뢰 레이어와 오케스트레이션"으로 정리된다(auto mode 90%, Fusion, Agent 365, MAI 3~6개월 팔로어 전략). OpenAI는 Google, Oracle, AWS로 유통망을 넓혀 Microsoft 의존을 줄이고 있다. 그래도 Microsoft 매출의 11%가 OpenAI에서 나오므로 상호 의존은 여전히 크다.
- 시장 측면에서는 OpenAI 매출 '하향 정정'(10/8), 자금조달 목표 축소(10/31), 빅테크 FCF 악화와 주가 급락(10/30)이 겹쳐 AI 투자 회의론이 커졌다. Microsoft는 FCF 흑자를 낸 유일한 하이퍼스케일러였다(TechCrunch 10/30). 리더 발언을 해석할 때 이 시장 배경을 함께 봐야 한다.

### Gaps
- Kevin Weil(4월 퇴사), Fidji Simo(7월 이후 파트타임 고문)는 기간 내 OpenAI 리더로서의 공개 발언이 없을 가능성이 크다. Mark Chen과 Jakub Pachocki도 기간 내 새 공개 발언을 찾지 못했다(Pachocki는 9월 보도를 "confused"라고 평한 것만 확인).
- Amy Hood의 실적 콜 외 발언(컨퍼런스 등), Kevin Scott의 Fast Company 원문, Altman의 X 게시물은 원문을 확인하지 못했다(x.com은 JS 렌더링이 필요하고, 그 밖의 도메인은 차단).
- Stanford GSB 대담의 정확한 녹화·공개일, 20VC 에피소드의 정확한 공개일은 확인하지 못했다.
- Microsoft Ignite 2026(통상 11월 중순)은 기간 밖일 가능성이 높으며 확인하지 않았다.

---

## 핵심 질문 3: 숫자 총괄표와 이전 입장 대비 변화

### Takeaway
기간 내 '공식' 숫자는 Microsoft IR 자료가 거의 전부이며, 모두 1차 원문으로 확인했다. OpenAI 숫자는 공식 공시가 없고 FT, Bloomberg, CNBC, The Information 보도뿐이다(9월 말 순액 기준 약 500억 달러, 연말 700억 달러 이상 목표). 입장 변화 측면에서는 Nadella의 정렬 낙관론 철회와 Altman의 "좁은 의미의 초지능 도달·pacing 재고"가 가장 뚜렷하다.

### Cited Findings
**A. Microsoft FY27 Q1 (1차 원문 확인)** — [보도자료](https://www.microsoft.com/en-us/investor/earnings/fy-2027-q1/press-release-webcast), [녹취](https://www.microsoft.com/en-us/investor/events/fy-2027/earnings-fy-2027-q1)

| 항목 | 값 |
|---|---|
| 매출 | 922.79억 달러 (+19%) |
| 영업이익 | 459.15억 달러 (+21%) |
| 순이익 GAAP / Non-GAAP | 366.29억 달러 (+32%) / 364.22억 달러 (+18%) |
| EPS GAAP / Non-GAAP | 4.92달러 (+32%) / 4.89달러 (+18%) |
| Microsoft Cloud | 639억 달러 (+30%) |
| Azure | 331.65억 달러 (+48%) |
| M365 상업 클라우드 | +17% (고정환율 +18%) |
| 상업 RPO | 6,770억 달러 (+73%), 가중평균 2.3년, 12개월 내 약 30% |
| 상업 예약 | −12% (고정환율 −11%) |
| Capex(리스 포함) / 금융리스 | 452억 달러 / 74억 달러 |
| 운영현금흐름 / FCF / 주주환원 | 580억 / 186억 / 102억 달러 |
| OpenAI 투자 손익 | +2.07억 달러(EPS +0.03). 전년 −31억 달러(EPS −0.41) |
| OpenAI 관련 매출(10-Q, TechCrunch) | 분기 100억 달러, FY26 241억 달러, 미수금 72억 달러, 지분 약 24% |
| Q2 가이던스 | 매출 960억~971억 달러, Azure +49~50%(고정환율), capex 500억 달러 초과 |
| 2026 역년 capex | 약 1,700억 달러 |
| 운영 지표 | 신규 데이터센터 24곳(5개 대륙), Agent 레지스트리 5,000만 개 이상(QoQ +30%), Foundry 고객 12만 곳 이상, Maia 200 토큰/W 최대 1.7배, 에이전트 PR 6개월간 6배 |

**B. OpenAI (보도 기반)**
- 9월 말 연환산 매출 약 500억 달러(순액, FT), 연말 700억 달러 이상 예상(Bloomberg), Q3 런레이트 +77%, 엔터프라이즈 +107%(CNBC) — [TNW](https://thenextweb.com/news/openai-revenue-70bn-year-end-50bn-september)
- 투자자에게 제시한 컴퓨트 청구서 8,560억 달러 — [TNW](https://thenextweb.com/news/openai-ruddarraju-compute-infrastructure)
- 1GW 컴퓨트 5년 비용 약 700억 달러(Altman 추정), 200억 달러면 "much happier". 나비에-스토크스 증명 컴퓨트 약 1,000만 달러 — [TNW](https://thenextweb.com/news/sam-altman-openai-robots-self-replicating-data-centres-cheeky-pint)
- GPT-6.1 Terra API 입력 1달러, 출력 5달러(100만 토큰당) — [TNW](https://thenextweb.com/news/openai-gpt-6-1-terra-computer-use)
- 자금조달: 300억 달러/1.25조 달러 → 목표 200억 달러로 하향, 110억 달러 확보(WSJ) — [TechCrunch](https://techcrunch.com/2026/10/31/openai-reportedly-lowers-funding-target-for-new-round/)

**C. 입장 변화**
- Nadella: 2018~19년 "alignment will just fall out" → 2026년 10월 "I no longer believe that". 모델 범용화 발언은 이전과 이어지지만, 이번에는 "신뢰 시스템"과 내부자 위험을 해법으로 내놨다 — [TNW](https://thenextweb.com/news/satya-nadella-ai-alignment-20vc), [TNW](https://thenextweb.com/news/nadella-ai-models-insider-risks-emergency-brake)
- Altman: 9월 Amodei의 감속 요구 지지, 안전을 이유로 한 IPO 연기 → 10월 Politico "일부 해악 감수, 가벼운 규제" → Stanford "pacing을 다시 생각해야, 정렬은 지금까진 예상보다 쉬웠지만 장담 못 한다, 좁은 의미의 초지능은 이미" → Cheeky Pint "단일 모델이 얼마나 똑똑해질지 한도에 합의해야". 안전 수사가 갈수록 구체화된다 — [TNW](https://thenextweb.com/news/sam-altman-patch-all-the-bugs-ai-cybersecurity-stanford), [TNW](https://thenextweb.com/news/sam-altman-openai-robots-self-replicating-data-centres-cheeky-pint)
  - 인용: "We are going to have to agree to some limits about how smart we let these single models get." — "단일 모델이 얼마나 똑똑해지도록 허용할지에 대해 어떤 한도에 합의해야 할 것이다." (Cheeky Pint)
- Altman(산업 내러티브 반성): 업계는 왜 이 기술의 잠재적 하방이 감수할 가치가 있는지 제대로 설명하지 못했다고 했다. 사람들은 일자리 없는 미래와 "a crazy surveillance state"를 떠올리고, 이는 "a terrible sales pitch"라고 했다 — [TNW](https://thenextweb.com/news/sam-altman-openai-robots-self-replicating-data-centres-cheeky-pint)
- Suleyman: 9월 Bloomberg 인터뷰 "Unless we can prove ahead of time that we can control it… we should reject it… that should be a red line"([TNW 9/28, 기간 외·맥락](https://thenextweb.com/news/microsoft-suleyman-red-line-ai-control-bloomberg)) → 10월 Nadella 게시물 공유와 "must be contained", 의료 초지능 성과 발표. 수사가 통제 레드라인에서 도메인 특화 초지능으로 구체화됐다.
  - Suleyman(10/22): "I really believe that in 2027, we will be on the verge of a coding style breakthrough for medical records." — "2027년에 의료 기록 분야에서 코딩 같은 돌파구 직전에 있을 것이라고 정말 믿는다." / 의료 모델이 "24~36개월 안에 능력이 한 자릿수(10배) 좋아질 것" — [TechCrunch](https://techcrunch.com/2026/10/22/microsofts-mustafa-suleyman-says-its-ai-outperforms-doctors-on-hard-cases-as-he-chases-medical-superintelligence/)
- Brockman: 9/29 트럼프 자발적 안전 협약에 서명(안전 장치 지지). 그러나 그가 2,500만 달러를 낸 Leading the Future는 엄격한 규제에 반대하는 후보 48명 이상을 지원 중이다(Reuters, 10/21) — [TNW](https://thenextweb.com/news/openai-brockman-ai-safeguards-leading-the-future-pac)

### Inferences
- 리더 발언의 공통 변화는 "정렬은 스케일로 해결된다"에서 "정렬은 별개의 어려운 문제이니 외부 통제(격리, 감사, 속도 한도)가 필요하다"로의 이동이다. 이 변화가 Microsoft에서는 보안·거버넌스 제품 매출(Agent 365, E7, Perception)로, OpenAI에서는 정책 PR(speed limits)로 바뀌고 있다.
- 일자리: Altman은 "job apocalypse는 없다", Microsoft는 "6만 명 자발적 퇴직은 인력 축소 신호가 아니다"라고 했다. 두 회사 모두 AI와 고용 감소의 연결을 공식적으로 부정한다. 다만 Microsoft가 AI 투자 재원 마련과 동시에 인력 구조를 조정한다는 사실 자체가 시장이 받아들이는 신호다(추론).

### Gaps
- Microsoft의 GW 단위 용량, OpenAI의 기간 내 GW 수치는 1차 자료에서 확인하지 못했다.
- OpenAI가 매출을 공식 공시한 적은 없다. FT, Bloomberg, CNBC 원문도 직접 열지 못했다(TechCrunch, TNW, The Decoder의 인용으로 대체).
- 데이터센터 내용연수 변경 여부는 10-Q 원문으로 확인해야 한다.
