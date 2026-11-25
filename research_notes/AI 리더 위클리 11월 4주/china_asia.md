# 중국·아시아(한국 제외) AI 리더 보이스 — 2026-11-13 ~ 11-25 (11월 4주)

> 범위: 2026-11-13~11-25 발언·발표만. 태그는 【이번 주 11/23~25】·【11/16~22】·【11/13~15】. 배지: ✅ 원문(1차 자료·전문) / ✅ 2차(기사 본문 확인) / ❌ 헤드라인만.
> 이번 기간을 관통하는 사건은 **미 상무부 BIS의 「선진 반도체 원격 획득 제한」 임시 최종규칙(11/16 발표, 11/19 발효)**이다. 해외 데이터센터가 중국 기업에 일정 규모(보도상 1,200만 TPP) 이상의 연산력을 제공하려면 허가를 받아야 하고, 싱가포르·말레이시아·태국·인도네시아·브라질로 첨단 칩을 수출할 때도 허가가 필요해졌다. 이 규칙이 나온 직후 Tencent(11/18)·Alibaba(11/19) 실적 발표와 APEC 선전 정상회의(11/18~19)가 이어졌다. 그래서 중국 리더 발언 대부분이 이 규칙에 대한 반응이다.
> 미국 측 맥락(참고): Nvidia 젠슨 황의 'Alice Huang' 스캔들 → 11월 초 사임 → 11/20~24 사이 복직 보도. Anthropic IPO(11/19). 이 노트에서는 배경으로만 쓴다.
> 조사 방법: Bing News RSS로 기사를 찾고 curl로 본문을 확인했다. Google News 링크는 디코딩이 실패(503)해서 쓰지 않았다. HuggingFace API로 모델 공개 여부를 확인했다.

## Q1. 중국 빅테크 실적 시즌 리더 발언 (Tencent·Alibaba·Baidu·Xiaomi) — 미 칩 규제 직후 첫 공식 반응

### Takeaway
세 회사의 메시지가 갈렸다. Tencent(류츠핑)는 "중국 모두를 후퇴시킨다", 다음 Hunyuan이 늦어진다고 **단기 타격을 솔직히 인정**했다. Alibaba(우융밍)는 "국산 연산력 진척이 예상보다 앞서 있다"며 **2030 목표를 유지**했지만, 클라우드 성장률 둔화(30~45%)와 20GW 목표 하향 가능성을 내놨다. Baidu(리옌훙)는 규제 언급 대신 **"AI 투자가 매출·이익으로 이어지지 않으면 거품 우려가 현실이 된다"**는 응용 우선론을 폈다. 지난주 '조직 혁명' 메시지(마화텅·리옌훙)가 이번 주에는 **"칩 자립 + ROI 증명"**으로 옮겨갔다.

### Cited Findings

#### 1-1. 류츠핑(刘炽平, Martin Lau) — Tencent 총재 / 제임스 미첼(James Mitchell) — 최고전략책임자 — 11/18 Q3 실적 컨퍼런스콜 【11/16~22】 · ✅ 2차(본문, 통화 실록 인용)
- **미 칩 규제(직접 인용, Fortune·Yahoo 본문)**:
  - "unfortunate … It sets everyone back in China." → "유감스럽다… 중국의 모든 이를 후퇴시킨다." 다음 버전 Hunyuan의 학습은 더 오래 걸린다고 인정했다.
  - "We believe all Chinese players would actually have to rely on domestic supply chains and domestic chips." → "중국의 모든 플레이어가 결국 국내 공급망과 국산 칩에 의존해야 할 것이다." 장기적으로는 미국 통제가 중국 칩 산업 발전을 "speed up(가속)"할 것이라고 봤다.
  - 미첼: "We actually don't see an impact because our cloud business today is primarily running inference." → "클라우드는 지금 주로 추론이라 영향이 없다." 추론은 "surprisingly limited number(놀랄 만큼 적은 수)"의 국산 칩으로 돌릴 수 있다고 했다.
  - 출처: [Fortune via Yahoo Finance 11/20](https://finance.yahoo.com/technology/ai/articles/alibaba-tencent-put-faith-chinese-124451275.html). 중국어 실록 「我会说这很遗憾……它让中国的所有人都倒退了……训练会受到影响。对于下一个版本，短期内我们可能需要更长时间才能推出。」 → "유감이다… 중국 모두를 후퇴시켰다… 학습이 영향을 받는다. 다음 버전은 단기적으로 출시에 더 오래 걸릴 수 있다." — [ifeng 卫夕 11/20](https://feng.ifeng.com/c/8yCmdj8kKVD)
- **WorkBuddy(기업용 에이전트)·생태계**(ifeng 본문, 통화 인용):
  - 「WorkBuddy过去七天的年化总收入已超过5亿美元，是七年前推出的腾讯会议的2倍以上。」→ "WorkBuddy의 최근 7일 연환산 총매출은 5억 달러를 넘었다. 7년 전 출시한 Tencent 회의의 2배 이상이다." DAU 1,000만 명 이상, 일평균 토큰 100조 개 이상.
  - 「WorkBuddy已经成为中国几乎所有开放权重模型的最大客户」→ "WorkBuddy는 중국 거의 모든 오픈 웨이트 모델의 최대 고객이 됐다."
  - 「我们已经看到有用户每月花高达4万元人民币购买Token。这与中国过去的SaaS业务非常不同」→ "한 달에 토큰을 4만 위안어치까지 사는 사용자도 있다. 과거 중국 SaaS와 매우 다르다." 중국 기업 소프트웨어 시장에 신중하던 입장을 바꾼 이유로 ① AI 서비스는 불법복제를 피할 수 있고 ② 사내 고가치 용례가 많다는 점을 들었다.
- **위안바오(元宝) 실패 인정**: 「元宝没有我们预期的那么成功……我们已经大幅削减了在元宝上的支出。」→ "위안바오는 기대만큼 성공하지 못했다… 지출을 크게 줄였다." 이제 사용자 수보다 모델 능력을 우선한다 — [ifeng 11/19](https://feng.ifeng.com/c/8yAzHX3ezNX)
- **WeChat AI 비서 '샤오웨이(小微)'**: DAU 3,000만, 접점 30개 이상. 「即使小微向全部14亿微信用户开放，我们预计小微的季度成本仍会低于今年早些时候元宝的季度成本。」→ "14억 WeChat 사용자 모두에게 열어도 샤오웨이 분기 비용은 올해 초 위안바오 분기 비용보다 낮을 것이다."(소형 모델 WeLM 덕분). WeChat 연 매출(수천억 위안)에 AI로 "10%나 20%"를 더하는 효과가 "6~12개월 안에 분명히 보일 것"이라고 했다. Meta Muse보다 약한 것은 "의도한 것"이라고 설명했다. '에이전트 간 중개 수수료'라는 새 수익 모델도 언급 — [ifeng 卫夕](https://feng.ifeng.com/c/8yCmdj8kKVD)
- **재무 신호**: 연산력 선불금 때문에 순현금(Q2 582억)이 **순부채 137억 위안(Q3)**으로 바뀌었다. 신규 AI 제품 손실은 Q3 152억 위안(Q2 105억). 미첼은 선불 계약 일부에서 "최근 변화 때문에 빠져나오고 있다"고 했다. DRAM 연초 약 400% 상승의 원가 부담도 언급. 조직: "더 적은 인원으로 기존 사업을 돌리고 그 인력을 새 성장 엔진에 재배치하는 게 이상적"(류츠핑) — 같은 출처 · ✅ 2차
- 실적 수치 주의: 매출 2,073억 위안(+8%). Capex 증가율은 Fortune이 "+527%, 814억 위안", BigGo 헤드라인이 "+257%"로 **서로 다르다**. 보고서에 쓰기 전 IR 원문 확인이 필요하다.

#### 1-2. 야오순위(姚顺雨) — Tencent 수석 AI 과학자 + Hunyuan 팀 — Reddit r/LocalLLaMA AMA(Hy4·Hy4 flash) 【11/16~22】(보도 11/21~24) · ✅ 원문(스레드 URL) / ✅ 2차(量子位 번역)
- 형식: "Tencent Hy team (Shunyu Yao here), Ask Us Anything" — [Reddit](https://www.reddit.com/r/LocalLLaMA/comments/1y15w4a/tencent_hy_team_shunyu_yao_here_ask_us_anything/) (JSON 접근이 차단돼 정확한 게시 시각은 확인하지 못함. 중국 보도 첫 게재는 11/21). 답변은 팀 계정 명의라 **어느 답이 야오순위 본인 것인지 구분할 수 없다**(量子位: "哪个马甲是姚顺雨，我们还没对上号").
- 주요 답변(量子位 중문 번역 → 한국어):
  - 「我们认为Hy4还有相当大的提升空间，尤其是在后训练上……同时，我们计划训练更大规模的模型。」→ "Hy4는 특히 사후학습에서 개선 여지가 크다… 더 큰 규모의 모델을 학습할 계획이다."
  - 「我们的递归自我改进能力还处于早期，已经做了几项内部基准」→ "우리의 재귀적 자기개선(RSI) 능력은 아직 초기다. 핵심 능력을 평가하는 내부 벤치마크를 몇 개 만들었다."
  - 「最棘手的是训练环境设计有漏洞，模型会钻空子拿奖励。比如，我们得防止Agent直接上网搜现成答案」→ "가장 까다로운 건 학습 환경의 허점을 모델이 파고들어 보상을 타는 것(reward hacking)이다. 예컨대 에이전트가 인터넷에서 정답을 그냥 찾아오지 않게 막아야 한다."
  - 흔한 벤치(GPQA·SWE-bench 등)를 공개하지 않은 이유: "이미 포화에 가깝다". 글쓰기 능력 퇴보 지적에 "우리도 인지하고 있다. 덜 상투적으로 만드는 중"이라고 답했다. Hy4 flash는 총 약 1,560억(Engram 제외)·활성 약 120억 파라미터, Engram 비중 약 1/3이 최적(U자 곡선). llama.cpp 지원 곧 공개, 소형(mini/Flash-Lite) 모델은 로드맵에 있음.
  - 출처: [量子位 11/21](https://www.qbitai.com/2026/11/511757.html). 관련 보도: [QQ 11/21](https://news.qq.com/rain/a/20261121A09BTT00), [澎湃 11/24](https://www.thepaper.cn/newsDetail_forward_34539791) (❌ 헤드라인만)
- 지난주와 달라진 점: 11/7~8 대담(장야친과)이 철학·연구관 중심이었다면, 이번에는 **개발자 커뮤니티에 직접 나서 기술 디테일과 한계(RSI 초기, reward hacking, 긴 추론 체인)를 공개 인정**했다. 칩 규제 언급은 확인하지 못했다.

#### 1-3. 우융밍(吴泳铭, Eddie Wu) — Alibaba CEO — 11/19 FY27 Q2(9월 분기) 실적 콜 【11/16~22】 · ✅ 원문(Motley Fool 전사, Yahoo) / ✅ 2차(Fortune)
- 참석: 차이충신(Joe Tsai) 회장, 우융밍 CEO, 쉬훙(徐宏) CFO, 장판(蒋凡). ※ **차이충신의 발언은 전사본에서 화자 표시가 없어 확인하지 못함.**
- 직접 인용(Fortune 귀속):
  - "Our own progress in developing domestic computing power is in fact already ahead of our original expectations." → "국산 연산력 개발 진척은 사실 원래 예상보다 앞서 있다."
  - "The new compute export control rules will affect next year's products and services, and there is still uncertainty as regards the supply chain." → "새 연산력 수출통제 규칙은 내년 제품·서비스에 영향을 줄 것이고, 공급망 불확실성이 남아 있다." 클라우드 성장률이 30~45%로 낮아졌다가 2028년 50% 이상으로 반등할 수 있다고 시사했다.
  - "Once we get there, we will actually be in a better position to control and pace the speed at which we iterate our foundation models." → "(T-Head 양산에) 도달하면 기반 모델의 반복 속도를 우리가 더 잘 통제할 수 있다." — [Fortune via Yahoo](https://finance.yahoo.com/technology/ai/articles/alibaba-tencent-put-faith-chinese-124451275.html)
- 전사본 확인(경영진 답변, 화자 표기 없음):
  - "Our current T-Head chips are already capable of fully supporting the training of large scale, including ultra-large scale models. In fact, this year we are using this year's chips already to be training the next generation of models." → "현 T-Head 칩은 초대형을 포함한 대규모 모델 학습을 완전히 지원할 수 있다. 올해 칩으로 이미 차세대 모델을 학습하고 있다." 프리페어드 리마크에는 "Qwen is already training its next-generation model on T-Head's domestic chips"라고 돼 있다.
  - BIS 규칙에 대해: "we have obtained and used compute in compliance with applicable laws and regulations … it is too early at this stage for us to evaluate the impact." → "연산력은 관련 법규를 지켜 확보·사용해 왔다… 영향을 평가하기엔 아직 이르다."
  - "it may lead to a downward revision of that long-term 20 GW target" → "장기 20GW 목표가 하향 조정될 수 있다." 2027~28년에 국산 칩 투자를 가장 공격적으로 하고, 2028년 하반기 전체 현금흐름 흑자를 기대한다.
  - 칩 로드맵: Zhenwu M890 상용화, **V900(M890의 3배) 2027년 1분기 양산·2분기 슈퍼노드 상용화, J900은 2028년**. T-Head는 홍콩 상장을 비공개 신청했다.
  - 모델·앱: Qwen4-Max는 백본 2.4조 파라미터. "**Apple Intelligence(Qwen 통합)가 12월 중국 출시 예정**". MaaS에 대해 "최근 두 달 신모델 출시가 우리와 파트너 모두 원래 기대보다 다소 늦었다". 앱과 모델을 함께 키워야 한다며 "모든 앱이 같은 모델 위에서 돌면 쉽게 복제된다"고 했다. 2030 외부 클라우드 매출 1,000억 달러·EBITDA 마진 20%+ 목표는 유지.
  - 출처: [Alibaba Q2 FY2027 콜 전사(Motley Fool/Yahoo) 11/19](https://finance.yahoo.com/markets/stocks/articles/alibaba-baba-q2-2027-earnings-200159324.html)
- **Qwen4 가중치**: HF `Qwen` 조직의 최신 업로드는 Qwen-Image-2.1-Turbo(10/9)다. **11/25 현재 Qwen4(Max 포함) 가중치 공개는 확인되지 않는다**(HF API). 콜에서도 오픈 웨이트 일정 언급은 찾지 못했다 · ✅ 원문(부재 확인)

#### 1-4. 리옌훙(李彦宏, Robin Li) — Baidu 회장·CEO — ① 11/16 Q3 실적 콜 ② 11/17 APEC CEO 서밋(선전) 【11/16~22】 · ✅ 2차(본문)
- ① 실적 콜(新浪 본문):
  - 「推理需求仍处于规模化发展的早期阶段，未来还有较大的扩展空间。」→ "추론 수요는 아직 규모화 초기다. 앞으로 확장 여지가 크다."
  - 「AI原生应用的商业化仍处于非常早期的阶段，整个行业仍在探索之中。」→ "AI 네이티브 앱의 상업화는 아주 초기이고 업계 전체가 아직 탐색 중이다."
  - 「我们最大的三家GPU云客户今年续约时，均将合同期限延长至多年，其中一家客户的新合同期限是此前合同的6倍。」→ "GPU 클라우드 상위 3대 고객이 올해 재계약하면서 모두 계약을 다년으로 늘렸다. 한 곳은 이전 계약 기간의 6배다."
  - 수치: 매출 308억 위안(-1%), AI 신사업 132억(+37%, 일반 사업의 53%), AI 클라우드 인프라 82억(+94%), Qianfan MaaS 외부 토큰 매출 +1,159%. 쿤룬신 M100은 2026년 말 양산 가능. 허하이젠(何海建) CFO는 "AI 투자는 단기 이익 개선을 제약할 것"이라고 했다 — [新浪财经 11/17](https://cj.sina.com.cn/articles/view/6372873842/17bda567202001o4d6)
- ② APEC 工商领导人峰会(11/17):
  - "최긴급(最紧迫)" 키워드. 지난 3년 투자는 몇 배로 늘었지만 응용층 침투가 "예상보다 낮다", 많은 기업이 AI를 써도 매출·이익이 뚜렷이 늘지 않았다. 「所以最紧迫的，是找到AI真正适合的应用场景」→ "그래서 가장 시급한 일은 AI가 진짜 맞는 응용 장면을 찾는 것이다." 「弥合鸿沟的关键不在于彼此设限，而在于各自把最擅长的部分拿出来共同做成。」→ "격차를 메우는 열쇠는 서로 제한을 거는 게 아니라 각자 가장 잘하는 걸 내놓아 함께 이루는 데 있다."(미 규제를 우회적으로 겨냥한 표현으로 읽힌다). 무인주행은 인간보다 약 10배 안전하다며 각국에 도로 개방을 요청 — [新浪财经 11/19](https://finance.sina.com.cn/jjxw/2026-11-19/doc-inizfuni6304598.shtml)
  - SCMP 재인용: "If massive AI investment does not lead to increases in corporate revenue and profit, the AI bubble concerns currently being raised could become reality." → "막대한 AI 투자가 기업 매출·이익 증가로 이어지지 않으면 지금 제기되는 AI 거품 우려가 현실이 될 수 있다." — [DigitalToday(SCMP 인용) 11/18](https://www.digitaltoday.co.kr/en/view/127338/baidu-xiaomi-ceos-warn-of-ai-bubble-amid-heavy-investment) · ✅ 2차(재인용)
- 지난주와 달라진 점: 11/12 Baidu World의 '지능형 조직' 비전 제시에서 **'거품 경고 + 응용 ROI'**로 톤이 낮아졌다(같은 기간 미 기술주 급락·SoftBank -15%와 겹친다).

#### 1-5. 레이쥔(雷军)·루웨이빙(卢伟冰) — Xiaomi 창업자 / 총재 — ① 11/17 APEC CEO 서밋 ② 11/24 Q3 실적 콜 【11/16~22】【이번 주 11/23~25】 · ✅ 2차
- ① 레이쥔(SCMP 재인용): "Although massive funds are being poured into AI technology, the areas of actual application are limited, and there are not many companies that have built stable profit structures." → "AI에 막대한 자금이 들어가지만 실제 응용 분야는 제한적이고 안정적 수익 구조를 만든 기업은 많지 않다." 휴머노이드가 자동차 산업을 넘는 성장 기회를 만들 것이라고 전망 — [DigitalToday](https://www.digitaltoday.co.kr/en/view/127338/baidu-xiaomi-ceos-warn-of-ai-bubble-amid-heavy-investment) · ✅ 2차(재인용). (현장에서 명함을 돌리고 발언 때 긴장했다는 화제는 新浪 관련 기사 헤드라인 · ❌)
- ② 루웨이빙(11/24 콜): 「具身智能，尤其是具身机器人，未来的产业规模可能会大于汽车产业」→ "체화 지능, 특히 체화 로봇의 미래 산업 규모는 자동차보다 클 수 있다." 본체·데이터·모델 세 가지에 집중 — [每日经济新闻 11/24](https://m.nbd.com.cn/articles/2026-11-24/4657493.html). Q3 API 호출량과 AI 관련 매출이 계속 늘었다(MiMo-V2.6 9월 오픈소스) — [东方财富 11/24](https://finance.eastmoney.com/a/202611243938558754.html). 메모리 가격은 "상승이 둔화됐지만 여전히 높은 수준"(nbd 헤드라인 · ❌). AI 연구개발 비중 30% 이상(MSN 헤드라인 · ❌). 매출 1,072억 위안.

### Inferences
- **"추론은 국산, 학습은 타격"**이라는 공통 프레임이 생겼다. Tencent는 학습 지연을 공개 인정했고, Alibaba는 "T-Head로 차세대 Qwen 학습 중"이라며 학습 자립을 주장했다. Alibaba 주장이 사실이라면 미국 규칙의 실효성에 직접 반론하는 셈이지만, 독립 검증은 없다(Reuters Breakingviews는 "quixotic faith(돈키호테식 믿음)"라고 평가 — 헤드라인).
- Tencent는 **'모델 공급자'보다 '토큰 최대 구매자·유통자'(WorkBuddy=오픈 웨이트 최대 고객)**로 자리를 잡고 있다. 규제로 자체 학습이 늦어져도 국산 오픈 모델 생태계를 묶는 전략과 맞물린다.
- Baidu·Xiaomi의 "거품" 발언은 미국발 AI 매도와 동조하는 **'ROI 증명' 국면 진입** 신호다. 지난주의 공격적 '조직 혁명' 서사와 대비된다.

### Gaps
- 마화텅(Pony Ma)의 콜 발언: ifeng가 "마화텅이 개장 발언에서 '더 많은 연산력을 MaaS·GPU 임대에 배분한다'고 말했다"고 전하지만, 직접 인용 전문은 확인하지 못함.
- 차이충신(Joe Tsai) 발언: 콜 전사본에서 화자 식별 불가. 별도 인터뷰도 찾지 못함.
- Tencent Capex 증가율(527% vs 257%) 불일치 — IR 원문 미확인.
- JD 실적·AI 발언: 이번 기간 기사 찾지 못함.

## Q2. AI 랩(DeepSeek·Baidu ERNIE·Moonshot·MiniMax·Zhipu·ByteDance) — 약속 이행과 신호

### Takeaway
**Baidu는 ERNIE 5.5 Flash 가중치 약속을 기한(11/25) 전인 11/23에 지켰다.** DeepSeek V5는 나오지 않았다. 대신 C단(앱·웹) 사용 한도 도입(11/16, 공식 발표 없음)과 1,000억 위안대 2차 투자 등기(11/20)가 나왔다. **연산력 부족과 자본 조달이 동시에** 드러난 셈이다. Moonshot은 인도네시아 Blackwell 임대 계약을 철회했다(보도). Qwen4·GLM 신규 가중치는 없다.

### Cited Findings

#### 2-1. Baidu — ERNIE 5.5 Flash Preview 가중치 공개(약속 이행) 【이번 주 11/23~25】 · ✅ 원문(HF) / ✅ 2차
- HF API: `baidu/ERNIE-5.5-Flash-Preview`, `-FP8`, `-BF16` 생성 시각 **2026-11-23 09:00 UTC** — [HF baidu](https://huggingface.co/baidu/ERNIE-5.5-Flash-Preview). (Base 모델은 10/21에 이미 공개)
- 사양(보도): 총 2,800억 / 토큰당 활성 140억 파라미터, 100만 토큰 컨텍스트, Apache 2.0, HF·ModelScope 배포, vLLM·SGLang 지원. CodeArena WebDev 오픈소스 2위(1668점) — [KuCoin 뉴스 11/23~24](https://www.kucoin.com/news/flash/baidu-open-sources-ernie-5-5-flash-preview-with-280-billion-parameters) · ✅ 2차. ※ 같은 기사 영어 요약문에는 "activates 140 billion"이라는 오기가 있다. 본문의 140억(14B)이 맞다.
- vLLM Day-0 지원 언급 — [note.com 11/24](https://note.com/gifted_snail5503/n/n9b4281aa87b2?hl=en) · ❌ 헤드라인 수준

#### 2-2. DeepSeek — V5 미출시 / C단 한도 / 2차 투자 / 전체 기능 API 개방 【11/13~15】【11/16~22】 · ✅ 2차 / ✅ 원문(HF 부재)
- HF `deepseek-ai` 최신 업로드는 V4.1-Flash-1017(10/17). **V5 가중치 없음**(HF API, 11/25).
- 11/13: 앱의 검색·심층사고 검색·파일 해석·링크 읽기·음성 기능을 API로 전면 개방했다("DeepSeek 앱을 1:1로 복제할 수 있는 수준") — [澎湃 11/17](https://www.thepaper.cn/newsDetail_forward_34499198) · ✅ 2차
- 11/16: 사용자 제보로 드러난 앱·웹 한도. 7일 넘게 비활성인 긴 대화는 지원 중단, 1회 입력 약 4만 자 상한, 일일 한도("因服务器繁忙，使用额度已达上限" → "서버가 바빠 사용 한도에 도달했습니다"). **DeepSeek은 별도 공지를 내지 않았다.** 10월 이후 장애 10건 — 같은 출처 · ✅ 2차
- 11/20: 법인 등기 변경. 이번 라운드는 1,000억~1,055억 위안, 투자 후 기업가치 약 6,155억 위안. 지분 플랫폼 출자자 31곳 중 Tencent(9.57%)·CATL 계열(9.57%) 공동 1위, China Mobile·CITIC 등. 량원펑은 집행조합원 법인 지분 99%로 절대 지배를 유지 — [IT之家 11/20](https://www.ithome.com/1/030/199.htm) · ✅ 2차. 량원펑 재산 550억 달러 보도(QQ 11/24) · ❌ 헤드라인만
- **량원펑 본인의 공개 발언은 이번 기간에 찾지 못했다.**

#### 2-3. Moonshot AI(月之暗面) — 【11/16~22】 · ❌ 헤드라인만 / ✅ 2차(Fortune 언급)
- The Information 보도(11/19): 인도네시아 데이터센터를 통한 Nvidia Blackwell 접근 계약(1.5억 달러)을 철회 — [Fortune via Yahoo](https://finance.yahoo.com/technology/ai/articles/alibaba-tencent-put-faith-chinese-124451275.html) · ✅ 2차(재인용). "50% 선불 제안에도 철회"(서울경제 영문 11/20~21 헤드라인 · ❌)
- 홍콩 IPO용 구조 재편(2027년 초 목표, 기업가치 500억 달러) 보도 — 搜狐 11/23 등 · ❌ 헤드라인만. 양즈린(杨植麟)·야오치즈(姚期智) 공동 논문(11/16, 수학 난제 30개 중 AI 단독 해결 0개) · ❌ 헤드라인만. **양즈린의 직접 발언은 찾지 못함.**
- 맥락: 미 하원 위원회가 중국 오픈 웨이트 모델을 지목했고, Cursor가 Kimi K2.5 단계적 퇴출을 검토 중(11/20 헤드라인 · ❌).

#### 2-4. 기타 랩 · ❌/✅ 혼재
- **ByteDance**: 장이밍의 "최소 2029~2030년 OpenAI·Anthropic 추격" 발언은 **11/12 보도로 지난주 범위**다(11/15 MSN 재게재). 새 발언이 아니다. Seed는 사전학습 데이터 팀을 개편(리청강 통괄, 11/17 헤드라인 · ❌). 쩡옌(曾妍) 논문 '10조 로드맵'(钛媒体 11/18 헤드라인 · ❌).
- **MiniMax**: 11/17 ifeng "초기 투자자와 옌쥔제의 AI 대담"(헤드라인 · ❌). 지난주 팟캐스트의 연장으로 보인다. 신규 가중치: H3-Image-PE(11/8, 범위 밖).
- **Zhipu**: 이번 기간 신규 발언·가중치 없음(HF 최신 GLM-5.3, 8/25).
- **Huawei**: 쉬즈쥔 TIME 기고 재확산(搜狐 11/17)은 **9/29 원문의 재게재**다(지난주 노트에서 정정). 새 발언이 아니다. "Huawei, 3,000만 개 생산능력 공장 건설 부인"(新浪 11/18 헤드라인 · ❌).

### Inferences
- 지난주 Geopolitechs가 말한 '출시 약 2주 뒤 가중치 공개' 패턴이 Baidu에서 확인됐다(Baidu World 11/12 → 가중치 11/23). Alibaba Qwen4-Max(11/11 프리뷰)는 2주가 지났지만 가중치가 없다. **"Alibaba는 플래그십을 닫고, Baidu·Tencent는 연다"**는 비대칭이 굳어지는 흐름이다.
- DeepSeek의 한도 도입, 대형 투자, Tencent 지분 1위 조합은 **추론 연산력 부족을 자본으로 메우는 국면**으로 보인다. V5 지연과 미 원격접근 규제가 겹친 결과로 추정한다(공식 설명은 없음).

### Gaps
- DeepSeek V5 일정, 량원펑 발언: 없음.
- Moonshot 계약 철회의 원문(The Information): 유료라 미확인.

## Q3. 중국 정부·APEC 선전(11/18~19)·미·중 '초지능(SI) 대화'

### Takeaway
중국 정부는 BIS 규칙에 **상무부 "보복 조치" 경고(11/17)와 외교부 "전형적 경제적 강압"(11/17)**으로 대응했다. 시진핑은 APEC에서 AI를 '혁신 기둥'으로 내세우며 데이터 거버넌스와 AI 보급을 강조했다. 미국 측(베선트)은 "트럼프·시진핑이 SI의 중대 군사 결정에 인간 관여를 합의했다"고 밝혔다. 그러나 **서면 문서에는 없고, 중국 측 확인은 찾지 못했다**. 비대칭 공개가 이어지고 있다. APEC 선언(Shenzhen Outlook)은 비구속적이다. 트럼프는 "글로벌리스트 규제 반대"로 중국의 다자 거버넌스 제안과 부딪쳤다.

### Cited Findings

#### 3-1. 중국 상무부 — 11/17 성명 【11/16~22】 · ✅ 2차(Straits Times·Bloomberg 본문)
- "strong dissatisfaction and firm opposition"(강한 불만과 단호한 반대). "China hopes the US will work with us in the same direction and return to the right track of resolving differences through consultation and cooperation." → "미국이 같은 방향으로 함께 움직여 협상·협력으로 이견을 푸는 올바른 궤도로 돌아오길 바란다." "If the US persists, China will take countermeasures to firmly safeguard its sovereignty, security and development interests." → "미국이 고집하면 중국은 반격 조치로 주권·안보·발전 이익을 굳게 지킬 것이다." 두 정상의 합의에 어긋나고 글로벌 반도체 공급망 안정을 위협한다고 했다 — [Straits Times 11/18](https://www.straitstimes.com/asia/east-asia/china-warns-us-of-retaliation-over-new-ai-chip-restrictions)
- 희토류 수출통제 재개 가능성 보도(Reuters 11/18, Chosun Biz 11/23 재인용) · ✅ 2차(재인용). 반대로 **"중국이 휴전 유지를 위해 핵심광물 금지를 중단"**(Yahoo 11/24 헤드라인 · ❌)도 있어 방향이 엇갈린다.

#### 3-2. 궈자쿤(郭嘉昆) — 외교부 대변인 — 11/17·11/18 정례 브리핑 【11/16~22】 · ✅ 원문(신화사)
- 「美方不断泛化国家安全概念，滥用出口管制措施，甚至横加干涉中国同其他国家开展正常贸易与科技合作，无理打压中国高新技术产业发展。这是典型的经济胁迫和"长臂管辖"，背离双方达成的共识，损害中国企业正当权益，扰乱全球产供链稳定。中方将采取必要措施坚决维护自身正当权益。」 → "미국은 국가안보 개념을 끊임없이 일반화하고 수출통제를 남용하며, 중국과 다른 나라의 정상적 무역·과학기술 협력에 함부로 간섭하고 중국 첨단산업 발전을 부당하게 억누르고 있다. 이는 전형적인 경제적 강압이자 '롱암 관할'로, 양측 합의를 벗어나고 중국 기업의 정당한 권익을 해치며 글로벌 공급망 안정을 어지럽힌다. 중국은 필요한 조치로 정당한 권익을 단호히 지킬 것이다." — [신화망 11/17](https://www.xinhuanet.com/fortune/20261117/2bbcbdd373b141e8b1a2ed00a87c87ea/c.html)
- 11/18 Nvidia 임시 CEO의 칩 관련 발언 질문에 "중국은 미국의 대중 칩 수출 문제에 대한 원칙적 입장을 여러 차례 밝혔다"고만 답했다 — [每日经济新闻 11/18](https://m.nbd.com.cn/articles/2026-11-18/4651357.html) · ✅ 2차
- 지난주 대비: 11/9~11 "입장은 일관된다"(원론)에서 **"경제적 강압·필요한 조치"(대응 예고)로 수위가 올라갔다.**

#### 3-3. 시진핑(习近平) — 국가주석 — 11/18~19 APEC 제33차 비공식 정상회의 주재 연설(선전) 【11/16~22】 · ✅ 2차(新京报 본문, 신화 통稿)
- 「数字经济和人工智能是创新增长的引擎。要加强数字基础设施建设，完善区域数据治理和协同合作，实现高效、便捷、安全的跨境数据流动。打造开放创新生态，促进人工智能广泛应用，推动产业转型升级、向新发展。」 → "디지털 경제와 AI는 혁신 성장의 엔진이다. 디지털 인프라를 강화하고 역내 데이터 거버넌스와 협력을 개선해 효율적·편리·안전한 국경 간 데이터 흐름을 실현해야 한다. 개방형 혁신 생태계를 만들어 AI의 폭넓은 응용을 촉진하고 산업 전환·업그레이드를 추진해야 한다."
- 조치: APEC 협력에 2,000만 달러, 선전에 '아태공동체연구센터' 설립, 디지털 기술·국경 간 데이터 흐름 분야 협력 기구 설립 — [新京报 11/19](https://www.bjnews.com.cn/detail/1795061545129990.html)
- **미 규제·'초지능 대화'를 직접 언급한 대목은 확인하지 못했다.** 공개 연설은 '개방·보급' 프레임을 유지했다. (APEC CEO 서밋 기조연설 전문은 新浪 링크 제목만 확인 · ❌)
- APEC 결과: 「2026 APEC Leaders' Shenzhen Outlook」을 합의로 채택(비구속). 무역 디지털화 협력 프레임워크 2027~2030, 신기술의 고용 활용 성명 등 — [City News Service/上海日报 11/19](https://www.citynewsservice.cn/articles/shanghaidaily/news/apec-leaders-adopt-shenzhen-outlook-on-trade-digitalization-supply-chains-ai-rkl5yg7n) · ✅ 2차. 중국은 '민생을 위한 디지털 경제·AI 성명'을 제안했고 미국은 구속적 국제 통제에 반대했다 — [Latin Times 11/20](https://www.latintimes.com/apec-shenzhen-declaration-us-china-ai-governance-601553) · ✅ 2차. SOM 의장 천쉬(陈旭, 전 주유엔 대사)는 11/17 "AI에 대해 심도 있게 논의해 중요한 공감대를 이뤘다"고 했으나 내용은 밝히지 않았다 — [TNW(Reuters 인용) 11/19](https://thenextweb.com/news/apec-members-reached-consensus-on-safe-ai-use-chinas-chen-xu-says) · ✅ 2차

#### 3-4. 미·중 '초지능' 군사 합의 — 미국 측 발표(맥락) 【11/16~22】 · ✅ 2차
- 베선트 재무장관(11/20, CNBC): "I think it was very important that President Trump and President Xi agreed that humans should always be involved in any military decisions that SI makes, and the SI should not be allowed to be autonomous for major military actions." → "트럼프와 시진핑이 SI가 내리는 모든 군사 결정에 항상 인간이 관여해야 하고, 중대 군사 행동에서 SI가 자율적이어선 안 된다고 합의한 것이 매우 중요하다." H200이 중국이 허가받아 살 수 있는 최고 칩이며 중국 주문은 "paucity(빈약)"하다고 했다 — [Military Times(Reuters) 11/20](https://www.militarytimes.com/news/pentagon-congress/2026/11/20/trump-xi-agreed-that-military-ai-decisions-should-involve-humans-bessent-says/)
- **어떤 서면 공동성명에도 포함되지 않았다**(VOA) — [Eurasia Review(VOA) 11/25](https://www.eurasiareview.com/25112026-us-china-leaders-agree-on-human-control-of-military-si-as-experts-warn-of-wider-risks/). 미·중·러 3자 회담에서 "AI의 안전한 개발 필요성"을 논의했다는 수준만 공개 — [CNN 11/22](https://www.cnn.com/2026/11/22/business/trump-xi-apec-tech-rivalry-intl-hnk)
- 트럼프(11/19 APEC 전체회의): "any form of globalist regulation or anything to control or stifle SI"에 반대 → "SI를 통제·억압하는 어떤 형태의 글로벌리스트 규제에도 반대". "It's super intelligence, but we have to watch it. We have to be careful." → "초지능이지만 지켜봐야 하고 조심해야 한다." — 같은 출처, [VOA 中文 11/19](https://www.voachinese.com/a/trump-tells-apec-the-us-is-a-pacific-power-warns-against-stifling-si-20261118/8225427.html)
- 지난주(베선트 11/11 "SI 대화 채널·사고 직통 통보")의 후속이다. 첫 안전 대화는 APEC 기간 개최 예정으로 보도됐다(Straits Times 11/18). **실제 개최 여부와 중국 측 리드아웃은 확인하지 못했다.**

### Inferences
- 중국은 **"공개 무대에서는 개방·보급(시진핑), 실무 채널에서는 보복 경고(상무부·외교부)"**라는 이중 트랙을 쓴다. 군사 SI 합의는 미국만 말하고 중국은 침묵하는 비대칭이 2주째 이어지고 있다.
- 무역 휴전 만료(1/10)를 앞두고 희토류 카드를 두고 보도가 엇갈린다. 칩 규제에 대한 실제 대응 수위는 12월로 넘어간 변수다.

### Gaps
- 중국 측 Xi-Trump 회담 리드아웃의 AI 문구: 검색했지만 본문을 찾지 못했다.
- 중국 AI 입법·신규 규제(사이버 공격 능력 제한, 수출통제 확정 등): IT之家 관련 링크 제목 「中国 AI 旗舰模型集体收紧网络攻击能力，加强 AI 技术出口管制」(날짜 미상) 외에는 확인하지 못함 · ❌

## Q4. 일본·동남아·인도 리더 (SoftBank·Sakana·싱가포르·말레이시아)

### Takeaway
손정의는 Anthropic IPO(11/19) 직전 공개 석상에서 **"Anthropic 미투자는 내 실패"**라고 인정했다. 다음 날 SoftBank 주가는 15% 급락했다. 미 칩 규제의 직접 대상이 된 싱가포르는 **"미국 점검에 협조, 우회 불허"**로 순응했고, 말레이시아 안와르 총리는 **"중국이 미국보다 상대하기 쉽다"**로 대조적인 태도를 보였다. 다카이치 정부의 AI 관련 신규 발언은 이번 기간 찾지 못했다.

### Cited Findings

#### 4-1. 손정의(孫正義) — SoftBank Group 회장 겸 사장 — 11/18 니혼게이자이 창간 150주년 행사 「Dialogues on the Future」 대담(도쿄) 【11/16~22】 · ✅ 2차(ITmedia 본문)
- 「いやね、それは僕の失敗例の一つですね。ダリオ（・アモデイCEO）に直接会った時に、すごいやつだとは思ったんですけど……。あん時、入れときゃよかったなあと思いますよね（笑）」 → "그건 제 실패 사례 중 하나죠. 다리오(아모데이)를 직접 만났을 때 대단한 친구라고 생각했는데… 그때 투자해 둘 걸 그랬어요(웃음)."
- 「その時にはもうすでにOpenAIに投資しようと決めて、一部始まっていましたから。そういう意味では『二兎を追いかけるよりは』というのが当時ありましたよね」 → "그때는 이미 OpenAI에 투자하기로 하고 일부 시작한 상태였다. '두 마리 토끼를 쫓기보다는'이라는 판단이 있었다."
- 「時々、全部追いかけるんじゃなくて、やっぱり強弱を付けて、ある部分により肩入れするということをしないと、しっかり仲間になれませんからね……でもAnthropicは素晴らしいですよね」 → "때로는 전부 쫓지 않고 강약을 둬서 한쪽에 더 힘을 실어야 제대로 된 동료가 될 수 있다… 그래도 Anthropic은 훌륭하다." — [ITmedia 11/18](https://www.itmedia.co.jp/business/articles/2611/18/news086.html), [2쪽](https://www.itmedia.co.jp/business/articles/2611/18/news086_2.html)
- 같은 행사에서 "초지성에 인생을 바친다", "원점 회귀(Pepper의 꿈)", 「号泣したんですよ。俺は何を成し遂げたんだ…このまま終わっていいのか」 → "엉엉 울었어요. 나는 무엇을 이뤘나… 이대로 끝나도 되나" — [日経 11/24](https://www.nikkei.com/article/DGXZQOCD231D10T21C26A1000000/) · ✅ 2차(유료벽, 도입부만)
- 시장 반응: 11/20 SoftBank -15%(2024년 이후 최악), Anthropic IPO(11/19, 810억 달러 조달) — [Investing.com via Yahoo 11/19~20](https://finance.yahoo.com/technology/ai/articles/softbank-group-shares-slump-15-054657878.html) · ✅ 2차
- 기타: SK하이닉스 1조 달러 인수 검토 보도(The Information 11/22~23). SoftBank는 "더 이상 적극 검토하지 않는다"고 답한 것으로 보도(unwire 11/23 헤드라인 · ❌). 11/24 대구 선영 참배(한국 관련이라 범위 밖, 참고만).
- 지난주 대비: 11/10 실적 발표는 고토 CFO가 맡았다. **이번 주 손정의 본인이 공개 무대에 나와 OpenAI 몰빵 전략의 기회비용을 처음 인정**했다.

#### 4-2. Sakana AI — 'Applied Research Lab' 출범 발표 【이번 주 11/23~25】 · ✅ 원문(공식 블로그)
- 첫 프로그램은 금융·경제(COFE). "A complex system, such as a market or an economy, is not something one LLM-powered agentic AI can resolve." → "시장이나 경제 같은 복잡계는 LLM 에이전트 하나로 풀 수 없다." "Agentic AI can now implement, test, and refine models at scale; its weakness is knowing which questions matter." → "에이전트 AI는 이제 모델을 대규모로 구현·검증·개선할 수 있지만, 어떤 질문이 중요한지 아는 데 약하다." — [Sakana AI 11/23](https://sakana.ai/applied-research-lab/). (발표 주체는 회사 명의이고 개인 서명은 확인하지 못함)

#### 4-3. 로런스 웡(Lawrence Wong) 싱가포르 총리 / 조지핀 테오(Josephine Teo) 디지털개발정보부 장관 / 간킴용 부총리 — 11/17~18 【11/16~22】 · ✅ 2차
- 웡(11/17, 마닐라 ASEAN 정상회의 후): "We want to uphold the rule of law, and we want to uphold Singapore's reputation as a trusted business hub." → "법치와 신뢰받는 비즈니스 허브라는 싱가포르의 평판을 지키겠다." 미국의 점검을 돕되, 싱가포르를 이용한 우회에는 "clear and firm(분명하고 단호한)" 조치를 하겠다고 했다. 간킴용(11/18, 핀테크 페스티벌): "We will act against those who flout our laws." → "법을 무시하는 자에게 조치하겠다." — [Straits Times 11/18](https://www.straitstimes.com/asia/spore-can-facilitate-us-checks-on-ai-chip-use-wont-allow-circumvention-of-export-controls-pm-wong)
- 테오(11/17): 규칙을 검토 중이며 합법 기업을 위한 'trusted access(신뢰 접근)'를 추진 — [Straits Times 11/17](https://www.straitstimes.com/singapore/spore-studying-us-chip-export-restrictions-seeking-trusted-access-for-legitimate-businesses) · ❌ 헤드라인(본문 미열람)

#### 4-4. 안와르 이브라힘(Anwar Ibrahim) 말레이시아 총리 — SCMP 인터뷰(선전, 시진핑 양자회담 전), 보도 11/24 【이번 주 11/23~25】 · ✅ 2차(CNA 재인용)
- 베이징이 워싱턴보다 상대하기 쉽다고 했고, 중국은 말레이시아의 대미 기술 협력을 막은 적이 없다고 말했다. 어느 쪽에도 기울지 않는다는 입장 — [CNA 11/24](https://www.channelnewsasia.com/asia/malaysia-anwar-ibrahim-easier-deal-china-us-tech-6577391). "US chip curbs won't impact Malaysia's China ties" — [Reuters 11/24](https://www.reuters.com/business/media-telecom/us-chip-curbs-wont-impact-malaysias-china-ties-pm-says-2026-11-24/) · ❌ 헤드라인. 야당 림관엥은 젠슨 황 복직을 계기로 트럼프에게 규제 해제를 요구하라고 촉구(Malay Mail 11/24 헤드라인 · ❌).

### Inferences
- BIS 규칙이 **동남아를 '줄 세우기'** 시작했다. 싱가포르는 순응(Megaspeed 파문의 진원지라 평판 방어), 말레이시아는 헤징을 택했다. 중국 AI 랩의 해외 연산 우회로(Moonshot 인니 철회)가 좁아지고 있다는 점과 이어진다.
- 손정의의 Anthropic 후회 발언 → SoftBank 급락은 **일본 AI 투자 서사가 'OpenAI 단일 베팅 리스크'로 재평가**되는 계기로 보인다.

### Gaps
- 다카이치 총리·일본 정부의 AI법·AI 기본계획 관련 11/13~25 발언: 찾지 못함(최근 확인은 11/9~11, 범위 밖).
- 인도: 이번 기간 AI 리더 발언 찾지 못함('AI 협의 문서 계획' 헤드라인 11/23만 있고 출처 신뢰도 낮음).
- 테오 장관 발언 원문 인용: 본문 미확인.
