## FOSS 기말 최종 과제

### 201720680 정제헌
### transifex Mastering Ethereum Translation Project
<hr/>

##### Mastering Ethereum URL : https://www.transifex.com/aantonop/ethereumbook

#### Ethereum?
이더리움은 2015년 7월 30일 비탈릭 부테린(Vitalik Buterin)이 개발하였다. 비탈릭 부테린은 가상화폐인 비트코인에 사용된 핵심 기술인 블록체인에 화폐 거래 기록뿐 아니라 계약서 등의 추가 정보를 기록할 수 있다는 점에 착안하여, 전 세계 수많은 사용자들이 보유하고 있는 컴퓨팅 자원을 활용해 이더리움 가상 머신(EVM)을 만들고, 이 플랫폼을 이용하여 SNS, 이메일, 전자투표 등 다양한 정보를 기록하는 시스템을 창안했다. 이더리움은 C++, 자바, 파이썬, GO 등 주요 프로그래밍 언어를 지원한다.
이더리움을 사물 인터넷(IoT)에 적용하면 기계 간 금융 거래도 가능해진다. 예를 들어 고장난 청소로봇이 정비로봇에 돈을 내고 정비를 받고, 청소로봇은 돈을 벌기 위해 정비로봇의 집을 청소하는 것도 가능해진다.

가상 머신
이더리움에서 스마트 계약을 처리하기 위한 가상 머신(EVM)은 모든 형태의 알고리즘을 처리할 수 있는 튜링 기계로서, 먼저 들어온 데이터를 우선적으로 처리하는 스택 구조를 가진다. EVM은 저수준의 기계어에 가까운 바이트 코드만을 실행할 수 있기 때문에 고급 프로그래밍 언어를 실행하기 위해서는 바이트 코드로 컴파일 과정을 거쳐야 한다. 이 가상 머신을 이용하기 위해서는 '가스'라는 대가를 지불해야 한다.
2021년 12월개당 약 500만원에 거래되고 있다.

출처 : https://ko.wikipedia.org/wiki/%EC%9D%B4%EB%8D%94%EB%A6%AC%EC%9B%80

#### Ethereum 주제 선정 이유
최근 유행했던 NFT코인의 거래가 대부분 이더리움을 통해 이루어지며 이더리움의 활용방안이 점점 증가하고 있다. 그리고 이더리움의 높은 활용성으로 다양한 이더리움 기반의 토큰과 코인이 개발되었다. 골렘, 어거, 샌드박스 등의 코인은 지금도 코인거래소에서 꾸준히 거래되고 있다. 이더리움과 같은 블록체인 기술이 세상을 어떻게 편리하게 바꿀 수 있을지 흥미가 생겨서 이더리움 번역을 주제로 잡게 되었다.

#### 번역 시 주의사항
Please do not translate the markup codes:
[TIP], [WARNING], [NOTE]

Do not translate the heading markers or index references:
[[ch1_introduction]], [[example6_2]]
these are anchors for references elsewhere in the document:
<<ch1_introduction>>
which become links and text references.

In the index reference data:
((("ethereum client", id="ix_ch03-asciidoc0", range="startofrange")))
only translate the index words themselves: "ethereum client", do not translate the index reference data:
id="ix_ch03-asciidoc0", range="startofrange"

Do not translate command line commands and source code

Do not translate image file names and code example filenames

Do not translate bitcoin-cli command names or other commands

Avoid translating anything inside brackets or between formatting markers:
[,],[[,]],((,)),<<,>>,{,},+,+

번역 책임자의 요구사항이다. 소스코드, 참조, 인덱스 등의 문장은 되도록 번역하지 않도록 해야 한다. 명령어 또한 마찬가지이다.
