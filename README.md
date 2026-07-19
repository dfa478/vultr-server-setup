# Vultr 가입 방법 완벽 가이드: 회원가입부터 결제 등록, 서울 서버 배포까지 한 번에 정리 (신규 가입 $250 무료 크레딧 받는 법 포함)

어느 날 밤, 토이 프로젝트를 올릴 서버가 필요해졌다. 국내 호스팅은 비싸고, AWS는 콘솔이 복잡하고, 디지털오션은 한국 리전이 없다. 그러다 Vultr(벌처)라는 이름이 눈에 들어왔다. 서울에 데이터센터가 있고, $5면 1GB 서버를 한 달 굴릴 수 있다고 했다. 이 글은 그 Vultr 가입 방법을 직접 밟아보며 정리한 기록이다. 회원가입, 결제 수단 등록, 첫 서버 배포, 무료 크레딧 받는 법까지 한 줄씩 풀어간다.

**Vultr 가입 방법이란**, 글로벌 클라우드 호스팅 플랫폼 Vultr에 계정을 생성하고 결제 수단을 등록해 첫 가상 서버(VPS)를 띄우기까지의 절차를 말한다. 이메일 가입 또는 구글·깃허브 연동, 로봇 인증, 신용카드·페이팔 등 결제 수단 연결, 인스턴스 배포의 네 단계로 이어진다. 요금은 시간 단위로 후불 청구되며, 신규 가입자에게는 최대 $250 무료 크레딧이 주어진다.

## 왜 하필 Vultr인가: 서울 리전과 가격의 균형

서버를 고를 때 가장 먼저 보는 건 '내 사용자와 가까운 곳에 데이터센터가 있느냐'다. Vultr는 전 세계 33개 리전을 운영 중이며, 그 안에 서울(Seoul KR)이 들어 있다. 한국 사용자 기준으로 지연(latency)이 짧아 응답 속도가 쾌적하다.

가격은 더 매력적이다. Regular Performance 최소 플랜이 월 $2.50부터 시작하고, NVMe SSD에 최신 AMD EPYC·인텔 Xeon을 얹은 High Performance·High Frequency 라인도 월 $6부터 만날 수 있다. 경쟁사인 DigitalOcean 대비 평균 20–40% 저렴하다는 게 Vultr 측의 공식 비교 자료다.

> 한 줄 요약: 한국 리전 + 시간제 과금 + $2.50 진입가 + $250 신규 크레딧. 초보자가 부담 없이 시작할 수 있는 몇 안 되는 글로벌 VPS다.

## Vultr 가입 방법: 6단계로 끝내는 회원가입

Vultr는 계정 생성 자체는 무료고, 서버를 배포하는 순간부터 과금이 시작된다. 즉, 가입만 해둔 채로는 한 푼도 나가지 않는다. 아래 순서대로 따라가면 된다.

1. Vultr 홈페이지 우측 상단의 Sign up 버튼을 클릭한다.
2. 이메일 주소와 비밀번호를 입력하거나, 우측의 Google 또는 GitHub 버튼으로 소셜 로그인한다.
3. '로봇이 아닙니다' 체크박스를 눌러 캡차 인증을 통과한다.
4. Create Account 버튼을 눌러 계정을 생성한다.
5. 가입한 이메일함에서 인증 메일을 열고 링크를 클릭해 이메일을 인증한다.
6. 로그인 후 Billing 탭으로 이동해 결제 수단을 등록한다.

여기까지가 회원가입이다. 계정은 있지만 서버가 없는 상태. 다음 단계에서 결제 수단을 넣어야 실제 배포가 가능해진다.

👉 [Vultr 가입 페이지에서 $250 무료 크레딧 받기](https://www.vultr.com/?ref=9738262-9J)

### 결제 수단 등록: 카드, 페이팔, 알리페이

Billing 탭에 들어가면 세 가지 선택지가 나온다. 신용카드·체크카드, PayPal, Alipay. 한국 사용자 대다수는 카드를 쓰게 된다.

카드 등록 입력란은 이렇게 생겼다:

- Card Number: 카드 16자리 번호
- Your Name: 카드에 적힌 영문 이름
- MM/YY: 유효기간
- CVV: 뒷면 보안 코드 3자리
- Billing Address / City: 청구 주소. 한국 도로명주소를 영문으로 변환해 넣는 걸 추천한다. juso.go.kr에서 뽑으면 된다.

Choose Amount 항목에는 예치금 선택지가 있다. "I just want to link my credit card -$0.00 deposit"을 고르면 카드만 연결하고 예치금은 넣지 않는다. 이러면 자동결제로 매월 청구 금액이 빠져나간다. 소액만 미리 충전해두고 싶다면 $10, $25 등을 고르면 된다.

한 가지 주의점. 신규 보너스 크레딧은 신용카드 또는 체크카드를 결제 수단으로 등록해야 활성화되는 경우가 많다. 페이팔이나 선불 Visa/Master 카드로는 보너스가 풀리지 않는다는 사용자 사례가 국내 블로그에 여럿 올라와 있다. 보너스가 목적이라면 카드 경로로 가자.

## 신규 가입 $250 무료 크레딧 받는 법

Vultr는 신규 고객을 위해 여러 프로모션을 동시에 돌리고 있다. 공식 쿠폰 페이지에서 확인할 수 있는 현재 유효한 코드들을 정리했다.

| 프로모션 코드 | 혜택 | 비고 |
|---|---|---|
| FLY300VULTR | $300 무료 크레딧 | 신규 고객 한정, 일부 상품에만 적용 |
| 250VULTRFLY | $250 무료 크레딧 | 신규 고객 한정, 30일 유효 |
| FLYTWOHUNDRED | $200 무료 크레딧 | 신규 고객 한정 |
| VULTRMATCH | 첫 예치금 1:1 매칭 (최대 $100) | $100 넣으면 $200 잔액, 12개월 유효 |

프로모션 크레딧은 특정 상품에만 적용되며 다른 혜택과 중복할 수 없다. 실제 사용 시 잔액이 50/50 비율로 차감된다. 시간당 $10이 쌓이면 $5는 크레딧에서, $5는 실제 잔액에서 빠지는 식이다.

VULTRMATCH가 묘하게 매력적이다. $100를 넣으면 $200이 된다. 크레딧 만료가 12개월이라 $250 단발성 코드보다 여유롭게 쓸 수 있다. 다만 매칭 크레딧 역시 일부 상품에만 적용된다는 점은 같다.

👉 [Vultr 매치 프로모션으로 예치금 두 배 받기](https://www.vultr.com/match/?ref=9738262-9J)

## Vultr 전체 플랜 비교: Cloud Compute부터 GPU, Bare Metal까지

Vultr의 상품 라인업은 크게 Cloud Compute, Optimized Cloud Compute, Cloud GPU, Bare Metal로 나뉜다. 각 라인 안에 다시 세부 플랜이 있다. 가격은 시간당 요금과 월 요금이 함께 표시되며, 월 요금은 730시간 기준 상한선이다.

아래 표는 각 라인의 대표 진입 플랜을 한눈에 본 것이다. 전체 스펙은 Vultr 가격 페이지에서 확인할 수 있다.

| 라인 | 세부 플랜 | CPU | 메모리 | 스토리지 | 대역폭 | 월 요금 | 시간당 | 구매 |
|---|---|---|---|---|---|---|---|---|
| Cloud Compute | Regular Performance | 1 vCPU | 0.5GB | 10GB SSD | 0.5TB | $2.50 | $0.004 |  [Regular Performance 시작하기](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| Cloud Compute | High Performance (AMD/Intel) | 1 vCPU | 1GB | 25GB NVMe | 2TB | $6.00 | $0.009 |  [High Performance 배포하기](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| Cloud Compute | High Frequency | 1 vCPU | 1GB | 32GB NVMe | 1TB | $6.00 | $0.009 |  [High Frequency 인스턴스 열기](https://www.vultr.com/products/high-frequency-compute/?ref=9738262-9J) |
| Optimized Cloud Compute | General Purpose (전용 vCPU) | 1 vCPU | 4GB | 30GB NVMe | 4TB | $30.00 | $0.045 |  [General Purpose 플랜 보기](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| Optimized Cloud Compute | CPU Optimized | 1 vCPU | 2GB | 25GB NVMe | 4TB | $28.00 | $0.042 |  [CPU Optimized 선택하기](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| Optimized Cloud Compute | Memory Optimized | 1 vCPU | 8GB | 50GB NVMe | 5TB | $40.00 | $0.060 |  [Memory Optimized 구성하기](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| Optimized Cloud Compute | Storage Optimized | 1 vCPU | 8GB | 150GB NVMe | 4TB | $75.00 | $0.112 |  [Storage Optimized 신청하기](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| Cloud GPU | NVIDIA GH200 | 1 GPU | 480GB RAM | 4,800GB | 25TB | $2,913 | $4.335 |  [Cloud GPU 상담하기](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Bare Metal | 전용 서버 | — | — | — | — | $120~ | — |  [Bare Metal 문의하기](https://www.vultr.com/products/bare-metal/?ref=9738262-9J) |

각 라인의 성격은 확실히 다르다. 라인별로 어디에 맞는지 정리해본다.

- **Regular Performance**: 구형 인텔 CPU + 일반 SSD. 가장 싸다. 개인 블로그, 저트래픽 사이트에 적합하다.
- **High Performance**: 최신 AMD EPYC 또는 인텔 Xeon + NVMe SSD. dev/test, 소규모 DB에 무난하다.
- **High Frequency**: 3GHz+ 인텔 Xeon + NVMe. CMS, 소규모 게임 서버에 추천.
- **Optimized Cloud Compute**는 전용 vCPU를 보장한다. 트래픽이 일정 이상이거나 안정적인 성능이 필요하면 이쪽으로 넘어가야 한다. General Purpose가 균형 잡힌 출발점이다.
- **Cloud GPU**는 AI 학습·추론, HPC 워크로드용. NVIDIA GH200, H100, A100 등을 시간제로 빌릴 수 있다.
- **Bare Metal**은 가상화 계층 없이 물리 서버를 통째로 임대. 극단적 성능이 필요할 때.

> 한 줄 요약: 처음엔 Cloud Compute $5–$6 플랜으로 시작하고, 트래픽이 커지면 Optimized 라인으로, AI 작업이 필요하면 Cloud GPU로 올라가는 게 일반적인 경로다.

## 첫 서버 배포: Deploy 버튼 한 번이면 1분 안에 뜬다

계정과 결제 수단이 준비되면 서버(인스턴스)를 만들 수 있다. 절차는 직관적이다.

1. 상단 메뉴에서 Deploy + 버튼을 클릭한다.
2. Choose Server Type에서 Cloud Compute를 선택한다.
3. CPU 옵션에서 Regular Performance / High Performance / High Frequency 중 하나를 고른다.
4. Choose a Server Location에서 Asia 탭을 열고 Seoul을 선택한다.
5. Choose an Image에서 Ubuntu 22.04 LTS 같은 안정 OS를 고른다.
6. Choose a Size에서 $5 플랜(1 vCPU, 1GB RAM, 25GB SSD)을 고른다.
7. Additional Features에서 IPv6, Auto Backup 여부를 결정한다. 자동 백업은 월 $2 정도 추가.
8. Server Hostname & Label에 이름을 적고 Deploy 버튼을 누른다.

보통 30초~1분 안에 상태가 Running으로 바뀐다. 대시보드에서 IP 주소와 root 비밀번호를 확인할 수 있다. 이후엔 SSH로 접속해 세팅하면 된다. 공개키를 올려두고 비밀번호 로그인을 끄는 게 기본.

보안 설정을 빠뜨리면 안 된다. Vultr는 2단계 인증(2FA)을 지원한다. TOTP 기반 구글 인증자뿐 아니라 YubiKey 같은 물리 보안키도 연결할 수 있다. 계정 탈취 한 번이면 서버가 통째로 날아가니, 가입 직후 2FA부터 켜두는 게 좋다.

## Vultr 사용자 평가와 신뢰도: 양극단의 진실

Vultr의 평판은 어디서 보느냐에 따라 극단적으로 갈린다. 솔직하게 짚고 넘어가야 할 부분이다.

긍정 측면. G2 리뷰에서 사용자들은 "배포가 빠르고 가격이 투명하다"는 점을 꾸준히 언급한다. 웹사이트플래닛의 종합 평가는 4.6점. 사용자 한 명은 "2년 동안 만족, 파리 리전에서 가동 중인데 업타임과 응답 속도가 제 역할을 한다"고 적었다. 가격 대비 성능이 핵심 장점이라는 데는 이견이 적다.

부정 측면. 트러스트파일럿 평점은 1.5–1.7점대로 낮다. 주된 불만은 지연 응답과 갑작스러운 계정 제한이다. 한 사용자는 "무료 크레딧으로 쓰다가 며칠 뒤 계정이 닫혔다"고 적었고, 다른 사용자는 "트래픽을 많이 쓰니 통보 없이 자원 제한이 걸렸다"고 한다. 공유 vCPU 환경에서 무거운 작업을 돌리면 노드 단위로 제한이 걸릴 수 있다는 점을 알아두자.

> 한 줄 요약: 가격과 속도엔 강하나, 고부하 워크로드나 계정 리스크를 피하려면 Optimized·Bare Metal로 올라가고 2FA는 필수다.

회사 규모 자체는 신뢰할 만하다. Vultr 공식 자료에 따르면 1.5백만 명 이상의 고객을 185개국에서 서비스했으며, 지금까지 4천5백만 건 이상의 클라우드 서버가 배포됐다. 33개 데이터센터 리전을 6개 대륙에 깔고 있다. 이 정도 규모면 '삼류 호스팅'이라 부르긴 어렵다.

## Vultr 가입 전 알아둘 점: 요금·해지·환불

요금 구조를 헷갈려하면 안 된다. Vultr는 시간당 과금 후불제다. 서버를 켜둔 시간만큼 매일 조금씩 쌓이고, 월 730시간을 기준으로 상한선이 정해진다. 즉, 730시간을 채우면 그 이후로는 더 청구되지 않는다. 월 $5 플랜이면 한 달 내내 켜둬도 $5다.

서버를 지우면 그 시점부터 과금이 멈춘다. 인스턴스 삭제는 Stop이 아니라 Destroy다. Stop만 하면 디스크 占用 요금은 계속 나간다는 점을 명심하자. 완전히 끊으려면 Destroy Server를 눌러야 한다.

환불 정책은 엄격하다. 사용한 만큼 후불로 빠지는 구조라 사후 환불은 원칙적으로 어렵다. 다만 예치금으로 미리 충전한 금액 중 미사용분은 지원 티켓을 통해 환불 요청이 가능하다. 다만 처리가 느린 편이라는 사용자 사례가 있다. 큰 금액을 한 번에 충전하기보다는 소액부터 충전해 써보는 게 안전하다.

해지는 두 단계로 생각하자. 먼저 모든 인스턴스를 Destroy하고, 이후 Support 탭에서 계정 삭제를 요청한다. 인스턴스가 남아있으면 잔액 정산이 끝날 때까지 계정 삭제가 보류된다.

## 자주 묻는 질문 (FAQ)

**Q. Vultr 가입 방법에서 가장 까다로운 단계는 뭔가요?**

A. 결제 수단 등록이다. 특히 신용카드의 영문 청구 주소를 정확히 넣어야 한다. 한국 도로명주소를 juso.go.kr에서 영문으로 변환해 그대로 복사하는 게 가장 안전하다. 주소가 카드 정보와 어긋나면 등록이 거절된다.

**Q. 신규 가입 $250 무료 크레딧은 누구나 받나요?**

A. Vultr에 처음 가입하는 신규 고객에 한한다. 기존 계정이 있으면 중복 가입으로 간주되어 프로모션 대상에서 제외된다. 크레딧은 일부 상품에만 적용되며 30일 유효 기간이 있다. VULTRMATCH 코드의 매칭 크레딧은 12개월 유효하다.

**Q. 서울 데이터센터는 실제로 빠른가요?**

A. 한국 내 접속 기준으로 지연(latency)이 짧아 응답 속도가 쾌적하다. Vultr는 서울을 포함해 33개 리전을 운영 중이며, 서울은 아시아 사용자에게 가장 가까운 선택지 중 하나다. 실제 속도는 Vultr 홈페이지의 Test Speed 기능으로 리전별 핑을 재볼 수 있다.

**Q. Vultr vs DigitalOcean, 어느 쪽이 나은가요?**

A. 단순 비교로는 Vultr가 평균 20–40% 저렴하다는 게 Vultr 측의 공식 비교 자료다. 리전 수도 Vultr가 더 많다(33 vs DigitalOcean 14). 반면 DigitalOcean은 문서와 커뮤니티 생태계가 더 오래 쌓여 있다. 한국 리전이 필요하고 가격이 우선이라면 Vultr가 무난하다.

**Q. 사용하다가 서버가 통째로 날아갈 위험은 없나요?**

A. 공유 vCPU 플랜에서 무거운 워크로드를 장시간 돌리면 자원 제한이 걸리거나, 극단적 경우 계정이 제한될 수 있다. 트러스트파일럿의 부정 리뷰 대다수가 이 케이스다. 안정성이 우선이라면 Optimized Cloud Compute(전용 vCPU) 또는 Bare Metal로 올라가고, 2FA를 반드시 켜두자. 정기 백업이나 스냅샷도 잊지 말 것.

## 마무리: 가입만 해두면 손해는 없다

Vultr 가입 방법은 사실 어렵지 않다. 이메일 하나, 카드 하나면 충분하다. 진짜 고민은 '어떤 플랜을 고를까'에서 시작되고, 그건 쓰면서 조정하면 된다. 서버는 Destroy하고 다시 띄우면 그만이니까.

한국 리전에 진입장벽이 낮은 글로벌 VPS를 찾고 있었다면, 일단 계정을 만들어두는 것도 방법이다. $250 무료 크레딧은 한 번 써보기엔 충분하고, 안 맞으면 인스턴스만 지우고 그만두면 그만이다. 매달 청구되는 고정비 없이 시간 단위로 빠지는 구조라 실패 비용이 작다.

👉 [Vultr 가입하고 $250 무료 크레딧 받아 시작하기](https://www.vultr.com/?ref=9738262-9J)
