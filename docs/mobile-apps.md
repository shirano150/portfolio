# 📱 개인 모바일 앱 프로젝트

!!! note ""
    AI를 이용해 기획·디자인·개발한 개인 모바일 앱 모음입니다. 대부분 Flutter로 만들었고, 일부 게임은 Flutter Flame과 Unity로 제작했습니다.

    **전체 27개** · Flutter 25개 · Unity 2개 · 게임 5개

## 스토어 출시 앱

<span class="muted">앱스토어 · 구글 플레이에 배포되어 업데이트 중인 앱</span>

<div class="app-grid">
<div class="app-card"><img src="../assets/images/apps/stock_diary.svg" alt="하루수익 아이콘" loading="lazy"><h3>하루수익</h3><p class="app-meta">TradeNote · v1.2.3 · <span class="st-live">● 스토어 출시</span></p><p>주식·코인 매매를 기록하고 수익을 캘린더와 그래프로 돌아보는 투자 일지 앱.</p><ul><li>일·기간별 수익 캘린더, 누적 수익 그래프</li><li>매매 복기, CSV 백업·복원, 생체 인증 잠금</li><li>홈 화면 위젯, 광고 제거 인앱 결제</li></ul><p class="app-stack"><span class="app-platform">iOS · Android</span> | Hive, fl_chart, Firebase, IAP, WidgetKit</p></div>
<div class="app-card"><img src="../assets/images/apps/trade_note.svg" alt="코인루프 아이콘" loading="lazy"><h3>코인루프</h3><p class="app-meta">CoinLoop · v0.1.2 · <span class="st-live">● 스토어 출시</span></p><p>코인 거래를 기록하고 복기하며 매매 습관을 개선하는 트레이딩 저널.</p><ul><li>빠른 저장과 복기 작성 분리</li><li>차트 캡처 첨부, 매매 회고</li><li>인앱 결제·리뷰 요청</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | Hive, image_picker, IAP</p></div>
<div class="app-card"><img src="../assets/images/apps/dayscore.svg" alt="오늘점수 아이콘" loading="lazy"><h3>오늘점수</h3><p class="app-meta">DayScore · v0.1.1 · <span class="st-live">● 스토어 출시</span></p><p>하루를 점수와 짧은 일기로 남기고 히트맵 캘린더로 패턴을 보는 기록 앱.</p><ul><li>점수 히트맵 캘린더, 기록 패턴 통계</li><li>홈 화면 위젯, 기록 알림</li><li>4개 언어, 프리미엄 구독</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | home_widget, IAP, l10n</p></div>
<div class="app-card"><img src="../assets/images/apps/spent_today.svg" alt="Spent Today 아이콘" loading="lazy"><h3>Spent Today</h3><p class="app-meta">오늘 쓴 돈 · v0.0.2 · <span class="st-live">● 스토어 출시</span></p><p>차분하고 미니멀한 하루 지출 기록 앱.</p><ul><li>오늘 지출 빠른 입력</li><li>캘린더·월간 합계 보기</li><li>다국어 지원</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | shared_prefs, l10n, AdMob</p></div>
<div class="app-card"><img src="../assets/images/apps/pic_size.svg" alt="이미지핏 아이콘" loading="lazy"><h3>이미지핏</h3><p class="app-meta">ImageFit · v1.1.0 · <span class="st-live">● 스토어 출시</span></p><p>사진의 픽셀 크기, 파일 용량, 저장 포맷을 한 화면에서 조절하는 편집 도구.</p><ul><li>정확한 리사이즈와 SNS·문서용 프리셋</li><li>용량 제한 압축, JPG·PNG·HEIC·WebP 변환</li><li>EXIF 개인정보 삭제, 7개 언어 스토어</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | image, exif, IAP</p></div>
<div class="app-card"><img src="../assets/images/apps/barcode_reader.svg" alt="바코드 스캐너 노트 아이콘" loading="lazy"><h3>바코드 스캐너 노트</h3><p class="app-meta">BarcodeNote · v1.0.7 · <span class="st-live">● 스토어 출시</span></p><p>바코드·QR을 스캔하고 결과를 기록으로 모아 관리하는 앱.</p><ul><li>카메라 실시간 스캔</li><li>스캔 기록 검색·공유·삭제</li><li>링크 열기 설정, 보상형 광고</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | mobile_scanner, Hive, Firebase</p></div>
<div class="app-card"><img src="../assets/images/apps/lotto_plus.svg" alt="로또플러스 아이콘" loading="lazy"><h3>로또플러스</h3><p class="app-meta">Lotto+ · v1.0.1 · <span class="st-live">● 스토어 출시</span></p><p>조건에 맞는 번호를 생성·보관하고 당첨 결과와 통계를 조회하는 로또 기록 앱.</p><ul><li>조건부 번호 생성, 조합 보관</li><li>회차별 당첨 결과·통계</li><li>당첨 판매점 지도, 자체 FastAPI 서버 연동</li></ul><p class="app-stack"><span class="app-platform">Android</span> | Riverpod, Kakao Map, FastAPI</p></div>
<div class="app-card"><img src="../assets/images/apps/weight_log.svg" alt="몸무게 기록 아이콘" loading="lazy"><h3>몸무게 기록</h3><p class="app-meta">Weightlog · v0.0.1 · <span class="st-live">● 스토어 출시</span></p><p>달력 중심으로 체중을 기록하고 기간별 통계를 보는 앱.</p><ul><li>달력에서 바로 기록</li><li>기간별 변화 통계</li><li>하단 탭: 달력·통계·기간</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | Flutter 3.41</p></div>
<div class="app-card"><img src="../assets/images/apps/daily_receipt.svg" alt="Daily Receipt 아이콘" loading="lazy"><h3>Daily Receipt</h3><p class="app-meta">영수증 가계부 · v1.0.1 · <span class="st-live">● 스토어 출시</span></p><p>영수증 감성의 화면으로 예산과 지출을 관리하는 가계부 앱.</p><ul><li>월·카테고리별 예산</li><li>계좌·자산 이체 관리</li><li>CSV 가져오기</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | Hive, file_selector</p></div>
</div>

## 생산성 · 라이프로그

<span class="muted">기록, 회고, 일정, 습관을 돕는 앱</span>

<div class="app-grid">
<div class="app-card"><img src="../assets/images/apps/daycue.svg" alt="DayCue 아이콘" loading="lazy"><h3>DayCue</h3><p class="app-meta">일정 위험 코치 · <span class="st-dev">● 개발 중</span></p><p>오늘 일정의 위험 신호를 살피고 다음 행동을 제안하는 온디바이스 AI 앱.</p><ul><li>일정 위험·빈 시간 찾기</li><li>다음 행동, 출발 시점 제안</li><li>Apple Intelligence 기반 요약</li></ul><p class="app-stack"><span class="app-platform">iOS 26</span> | Foundation Models, WidgetKit</p></div>
<div class="app-card"><img src="../assets/images/apps/dumio.svg" alt="Dumio 아이콘" loading="lazy"><h3>Dumio</h3><p class="app-meta">브레인 덤프 · <span class="st-dev">● 개발 중</span></p><p>흩어진 생각을 먼저 쏟아내고 요약·분류·다음 행동으로 정리해 주는 앱.</p><ul><li>텍스트·음성으로 빠른 캡처</li><li>아이디어·할 일·일기 등으로 분류</li><li>온디바이스 AI로 Today 액션 생성</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | speech_to_text, Foundation Models</p></div>
<div class="app-card"><img src="../assets/images/apps/session_zero.svg" alt="TabOff 아이콘" loading="lazy"><h3>TabOff</h3><p class="app-meta">Safari 세션 관리 · <span class="st-dev">● 개발 중</span></p><p>Safari 확장과 연결해 프라이버시 브라우징 세션을 정리하는 앱.</p><ul><li>Safari Web Extension 연동</li><li>탭 수 확인·세션 종료</li><li>5개 언어 지원</li></ul><p class="app-stack"><span class="app-platform">iOS 16.4+</span> | Safari Extension, gen-l10n</p></div>
<div class="app-card"><img src="../assets/images/apps/counter.svg" alt="카운터 아이콘" loading="lazy"><h3>카운터</h3><p class="app-meta">Counter · <span class="st-dev">● 개발 중</span></p><p>개인·그룹 활동 횟수를 세고 통계로 보여주는 iPhone 앱.</p><ul><li>원탭 카운트</li><li>개인·그룹 활동 통계</li><li>코발트 블루 테마</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | sqflite</p></div>
<div class="app-card"><img src="../assets/images/apps/pilltime.svg" alt="알약시간 아이콘" loading="lazy"><h3>알약시간</h3><p class="app-meta">Pill Time · <span class="st-proto">● 프로토타입</span></p><p>복약 일정과 기록을 관리하는 복약 알림 앱 UI 프로토타입.</p><ul><li>오늘 복약·복용 확인</li><li>캘린더·약 목록·상세</li><li>복약 통계</li></ul><p class="app-stack"><span class="app-platform">iOS · Android</span> | fl_chart</p></div>
</div>

## 금융 · 쇼핑 · 도구

<span class="muted">가계부, 가격 정보, 계산기</span>

<div class="app-grid">
<div class="app-card"><img src="../assets/images/apps/moamoa.svg" alt="모아모아 아이콘" loading="lazy"><h3>모아모아</h3><p class="app-meta">MoaMoa · <span class="st-dev">● 개발 중</span></p><p>매일의 지출을 모아 소비를 한눈에 보여주는 가계부 앱.</p><ul><li>달력·내역·통계 탭</li><li>월 예산 설정</li><li>Android·iOS·Web 지원</li></ul><p class="app-stack"><span class="app-platform">iOS · Android · Web</span> | shared_prefs, file_picker</p></div>
<div class="app-card"><img src="../assets/images/apps/cartcue.svg" alt="살까말까 아이콘" loading="lazy"><h3>살까말까</h3><p class="app-meta">CartCue · <span class="st-dev">● 개발 중</span></p><p>KAMIS 농산물 가격을 바탕으로 장보기 시점을 쉽게 알려 주는 앱.</p><ul><li>품목별 최신 가격 신호</li><li>소매·도매 기준 전환</li><li>공공 API 실데이터</li></ul><p class="app-stack"><span class="app-platform">iOS · Android</span> | KAMIS API, http</p></div>
</div>

## 게임

<span class="muted">Flutter · Unity로 만든 캐주얼 게임</span>

<div class="app-grid">
<div class="app-card"><img src="../assets/images/apps/poker_game.svg" alt="Poker Game 아이콘" loading="lazy"><h3>Poker Game</h3><p class="app-meta">보스 배틀 비디오포커 · <span class="st-proto">● 프로토타입</span></p><p>보스와 대치하며 홀드·드로우와 특수 카드로 싸우는 비디오포커 로그라이크.</p><ul><li>보스 배틀 전투</li><li>특수 카드 교체</li><li>기획서 v0.1 기반 프로토타입</li></ul><p class="app-stack"><span class="app-platform">iOS · Android</span> | Flutter</p></div>
<div class="app-card"><img src="../assets/images/apps/cube_tower.svg" alt="Cube Tower 아이콘" loading="lazy"><h3>Cube Tower</h3><p class="app-meta">물리 쌓기 · <span class="st-dev">● 개발 중</span></p><p>큐브를 던져 탑 위에 쌓는 세로형 물리 쌓기 게임.</p><ul><li>물리 기반 쌓기</li><li>복구 기회 후 이어 하기</li><li>아래층 안정화 시스템</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | Unity 6</p></div>
<div class="app-card"><img src="../assets/images/apps/potato_cut.svg" alt="Potato Cut 아이콘" loading="lazy"><h3>Potato Cut</h3><p class="app-meta">감자 자르기 · <span class="st-proto">● 프로토타입</span></p><p>세로로 놓인 감자를 일정한 두께로 잘라 쌓는 모바일 게임 프로토타입.</p><ul><li>타이밍 자르기</li><li>두께 정확도 판정</li><li>9:16 세로 화면</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | Unity 6</p></div>
</div>

## 서비스 중지

<span class="muted">개발 또는 출시 후 서비스를 중단한 앱</span>

<div class="app-grid">
<div class="app-card"><img src="../assets/images/apps/decisionLog.svg" alt="선택노트 아이콘" loading="lazy"><h3>선택노트</h3><p class="app-meta">Decision Log · <span class="st-stop">● 서비스 중지</span></p><p>결정을 기록하고 나중에 결과를 돌아보는 로컬 우선 회고 앱.</p><ul><li>결정 기록과 검토 시점 알림</li><li>결과 회고·요약</li><li>Pro 일회성 인앱 결제</li></ul><p class="app-stack"><span class="app-platform">iOS · Android</span> | Hive, Notifications, IAP</p></div>
<div class="app-card"><img src="../assets/images/apps/pinmemo.svg" alt="핀메모 아이콘" loading="lazy"><h3>핀메모</h3><p class="app-meta">PinMemo · <span class="st-stop">● 서비스 중지</span></p><p>텍스트·사진·손그림으로 꾸민 메모를 iPhone 잠금 화면에 띄우는 앱.</p><ul><li>글자·색상·종이 스타일 꾸미기</li><li>사진 첨부와 자유 그리기</li><li>Live Activity로 잠금 화면 표시</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | Live Activity, Swift 연동</p></div>
<div class="app-card"><img src="../assets/images/apps/moru.svg" alt="모루데이 아이콘" loading="lazy"><h3>모루데이</h3><p class="app-meta">MoruDay · <span class="st-stop">● 서비스 중지</span></p><p>오늘의 감정과 비워낼 생각을 적어 마음을 가볍게 하는 감정 기록 앱.</p><ul><li>10가지 감정 선택</li><li>비워낼 생각 기록</li><li>기록 모아보기, 알림</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | Hive, l10n</p></div>
<div class="app-card"><img src="../assets/images/apps/day_keep.svg" alt="DayKeep 아이콘" loading="lazy"><h3>DayKeep</h3><p class="app-meta">유통기한 관리 · <span class="st-stop">● 서비스 중지</span></p><p>식품·생활용품의 만료일을 등록하고 임박 시 알려 주는 앱.</p><ul><li>사진과 함께 항목 등록</li><li>만료 임박·지난 항목 필터</li><li>알림 시간 설정·재예약</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | Hive, Local Notifications</p></div>
<div class="app-card"><img src="../assets/images/apps/stock_mate.svg" alt="Stock Mate 아이콘" loading="lazy"><h3>Stock Mate</h3><p class="app-meta">주식 계산기 · <span class="st-stop">● 서비스 중지</span></p><p>추가 매수 평단가, 손익분기, 목표 수익을 계산하는 주식 도우미.</p><ul><li>물타기·평단가 계산</li><li>수수료·세금 반영 손익분기</li><li>종목 조회와 계산 저장</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | Hive</p></div>
<div class="app-card"><img src="../assets/images/apps/ad_monitor.svg" alt="Ad Monitor 아이콘" loading="lazy"><h3>Ad Monitor</h3><p class="app-meta">AdMob 수익 모니터 · <span class="st-stop">● 서비스 중지</span></p><p>AdMob API로 내 앱들의 광고 수익을 모아 보는 대시보드.</p><ul><li>Google 계정 OAuth 로그인</li><li>수익 리포트·통계</li><li>환율 변환</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | AdMob API, googleapis</p></div>
<div class="app-card"><img src="../assets/images/apps/ball_forge.svg" alt="Brick Forge 아이콘" loading="lazy"><h3>Brick Forge</h3><p class="app-meta">Break. Build. Repeat. · <span class="st-stop">● 서비스 중지</span></p><p>공을 쏘아 벽돌을 깨고 업그레이드 카드로 빌드를 만드는 로그라이트 벽돌깨기.</p><ul><li>업그레이드 카드 선택·리롤</li><li>라인볼 등 특수 볼</li><li>위험선 도달 시 게임 오버</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | Flame, audioplayers</p></div>
<div class="app-card"><img src="../assets/images/apps/math_blast.svg" alt="Math Blast 아이콘" loading="lazy"><h3>Math Blast</h3><p class="app-meta">Connect · Calculate · Blast · <span class="st-stop">● 서비스 중지</span></p><p>숫자 블록을 연결해 계산하고 터뜨리는 수학 퍼즐 게임.</p><ul><li>미션·무제한 모드</li><li>최고 기록, 사운드·진동</li><li>기호 변경·섞기</li></ul><p class="app-stack"><span class="app-platform">iOS</span> | Flame, Hive</p></div>
</div>

---

<span class="muted">아이콘이 단색 이니셜인 앱은 아직 전용 앱 아이콘을 만들지 않은 프로젝트입니다.</span>
