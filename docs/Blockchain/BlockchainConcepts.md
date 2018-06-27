# 개념

> 블록체인이 대체 무엇인가?

**목차**

- [총론](#총론)
- [합의](#합의)

## 총론

블록체인은 해시, 암호화, 데이터베이스 등 잘 알려진 기술을 적재적소에 조합한 응용기술이다. 네트워크의 보안을 경제적 인센티브로 구현해냈다는 것이 특이점이다. 

사회에서 거래와 같은 상호작용을 하기 위해서는 신뢰가 필요하다. 지금까지는 신뢰를 관장하는 중앙화된 기관 - 정부 또는 신용중개기관 등 - 을 만들고, 해당 기관에 권력과 권한을 위임하는 방법을 통해 신뢰를 확보했다. 다만 신뢰를 확보하기 위해 중앙화된 기관에 힘을 부여하고, 해당 기관이 신뢰를 보증하는 업무를 제대로 수행하는지 '믿어야' 하는 문제점을 안고 있었다.

블록체인은 중앙화된 기관을 거부하고, **암호학적 증명**과 네트워크 구성원 간의 **합의 알고리즘**을 활용해 신뢰를 확보했다. 상대방이 진실하게 행동하기를 기대하기보다는, 설령 시스템 안의 사용자가 부패하거나 믿을 수 없더라도 확실한 신뢰를 보장하고자 하는 시스템이 바로 블록체인이다. 즉 "네트워크 안의 누구도 100% 믿을 수는 없으나, 네트워크를 통한 거래는 안전하다."라는 명제를 암호학, 합의 알고리즘을 바탕으로 구현한 것이다. 신뢰 보증을 자체적으로 해결하는 네트워크라고 요약할 수 있겠다.

최초의 블록체인으로 평가받는 '비트코인'이 대표적인 예시다. 제3기관 없이 신뢰를 확보하는 것, 믿을 수 있는 P2P 거래 체결을 가능하게 하는 것이 비트코인의 근본 철학이었다. 그리고 비트코인을 이용해 실제로 제3기관의 개입 없이 거래가 이루어졌고, 이중 지불이 사실상 불가능한 시스템을 구축함으로써 신뢰를 확보했다. 탈중앙형 P2P 거래 플랫폼으로써 비트코인은 블록체인의 가능성을 처음 제시했다.

"인터넷 기술"이라는 역사 흐름의 일부이지만 인터넷 기반으로 구현되는 새로운 프로토콜 개념이다. 신뢰를 구현하는 과거의 방식 - 중앙화된 기관의 존재 - 을 거부하고 새로운 신뢰 형성 방식을 제시한 네트워크이자 플랫폼이다.

중앙화된 권력 없이 신뢰를 구축할 수 있다는 것은, 그동안 중앙화된 권력을 바탕으로 신뢰를 확보해 온 기존 시스템에 변화를 일으킬 수 있음을 말한다. 대표적인 기존 시스템이 바로 '화폐'다. 한 국가의 중앙은행이 그 가치를 보증하는 거래 수단인 화폐의 역할을 이론적으로는 대체할 수 있게 된 셈이다. 블록체인의 신뢰 생성 과정에서 발생하는 매개인 토큰을 '가상화폐 (정확한 명칭은 암호화폐)'라고 칭한 이유이기도 하다.

중앙화된 권력 없이도 가치를 만들어낼 수 있게 되었다는 건, 개개인에게도 일종의 '조폐권'이 주어졌다는 의미이기도 했다. 따라서 블록체인 플랫폼 위에 '사람들에게 가치를 제공할 수 있는' 애플리케이션(**Dapp**)을 개발하고, 애플리케이션의 소비와 생산에 필요한 '토큰'을 발행하려는 시도가 잇따랐다. 현실 세계에서 화폐를 바탕으로 생산과 소비가 이루어지는 거대한 생태계가 만들어진 것처럼, 블록체인 플랫폼 안에서도 거대한 생태계를 만들어내기 위한 시도가 이루어지고 있다. 

블록체인 플랫폼에서 가치를 제공할 수 있는 애플리케이션을 제작하고, 해당 애플리케이션이 완성되면 사용할 수 있는 토큰을 사람들에게 미리 판매하는 것이 **ICO**.
블록체인 플랫폼 위에서 구동되는 탈중앙화된 애플리케이션(Decentralized Application)이 바로 **Dapp**.
블록체인에 기반해 움직이는 하나의 조직이자 시스템이 바로 탈중앙화된 자율조직(Decentralized Autonomous Organization) **DAO**.
Dapp에서 또는 DAO에서 쓰이는 기축통화이자 가치를 재단하는 척도이며, 탈중앙화된 조직에서 참여자가 자발적으로 행동할 수 있도록 하는 보상이 바로 **토큰**.
Dapp이나 DAO에서 네트워크 참여자의 자발적인 행동이 블록체인 생태계의 활성화를 이끌어낼 수 있도록 하는 토큰 시스템이 **토큰 이코노미**

블록체인은 데이터베이스, 개발 플랫폼, 네트워크 Enabler의 성격을 두루 가지고 있는 복합플랫폼이다. 세계를 획기적으로 바꾸며 생태계를 새로이 구축한 인터넷 / 웹과 같이 거대한 생태계를 구축할 잠재력을 품고 있기도 하다.

## 합의

> Consensus


합의는 **탈중앙화 Architect**를 구성하는 첫 번째 층이다.
이전까지의 신뢰는 '중앙화된 주체'에 의해 구축되었지만, 
탈중앙화를 추구하는 네트워크는 신뢰를 관장하는 거대한 주체는 더 이상 존재하지 않는다. 그렇지만 네트워크를 이용하는 모든 사용자에게는 네트워크를 통해 이루어지는 모든 활동이 '안전하다'는 보장, 즉 신뢰가 필요하다.

신뢰를 통제할 중앙화된 세력을 거부하는 블록체인 시스템에서 '신뢰'를 구축해야 하는 블록체인의 특성상, 블록체인 구성원의 '합의'를 통해 신뢰를 형성해야 한다. 따라서 블록체인 시스템에서 **합의 알고리즘은 네트워크의 근간을 이루는, 절대적으로 중요한 알고리즘**이다.


- '믿을 수 있는 정보'라는 개념의 개관(왜 컨센서스가 필요한지)
- 작업증명(Proof of Work, PoW)
- 지분증명(Proof of Stake, PoS)
- Delegated Proof of Stake(DPoS)
   - BFT