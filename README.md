## FOSS 기말 최종 과제

### 201720680 정제헌
### transifex Mastering Ethereum Translation Project
<hr/>

##### Mastering Ethereum URL : https://www.transifex.com/aantonop/ethereumbook

### Ethereum?
이더리움은 2015년 7월 30일 비탈릭 부테린(Vitalik Buterin)이 개발하였다. 비탈릭 부테린은 가상화폐인 비트코인에 사용된 핵심 기술인 블록체인에 화폐 거래 기록뿐 아니라 계약서 등의 추가 정보를 기록할 수 있다는 점에 착안하여, 전 세계 수많은 사용자들이 보유하고 있는 컴퓨팅 자원을 활용해 이더리움 가상 머신(EVM)을 만들고, 이 플랫폼을 이용하여 SNS, 이메일, 전자투표 등 다양한 정보를 기록하는 시스템을 창안했다. 이더리움은 C++, 자바, 파이썬, GO 등 주요 프로그래밍 언어를 지원한다.
이더리움을 사물 인터넷(IoT)에 적용하면 기계 간 금융 거래도 가능해진다. 예를 들어 고장난 청소로봇이 정비로봇에 돈을 내고 정비를 받고, 청소로봇은 돈을 벌기 위해 정비로봇의 집을 청소하는 것도 가능해진다.

가상 머신
이더리움에서 스마트 계약을 처리하기 위한 가상 머신(EVM)은 모든 형태의 알고리즘을 처리할 수 있는 튜링 기계로서, 먼저 들어온 데이터를 우선적으로 처리하는 스택 구조를 가진다. EVM은 저수준의 기계어에 가까운 바이트 코드만을 실행할 수 있기 때문에 고급 프로그래밍 언어를 실행하기 위해서는 바이트 코드로 컴파일 과정을 거쳐야 한다. 이 가상 머신을 이용하기 위해서는 '가스'라는 대가를 지불해야 한다.
2021년 12월개당 약 500만원에 거래되고 있다.

출처 : https://ko.wikipedia.org/wiki/%EC%9D%B4%EB%8D%94%EB%A6%AC%EC%9B%80

### Ethereum 주제 선정 이유
최근 유행했던 NFT코인의 거래가 대부분 이더리움을 통해 이루어지며 이더리움의 활용방안이 점점 증가하고 있다. 그리고 이더리움의 높은 활용성으로 다양한 이더리움 기반의 토큰과 코인이 개발되었다. 골렘, 어거, 샌드박스 등의 코인은 지금도 코인거래소에서 꾸준히 거래되고 있다. 이더리움과 같은 블록체인 기술이 세상을 어떻게 편리하게 바꿀 수 있을지 흥미가 생겨서 이더리움 번역을 주제로 잡게 되었다.

### 번역 시 주의사항
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

### 번역 방법
* 우선 번역 전 파일을 transifex에서 다운로드 하였다. txt파일로 저장됨을 확인하였고 번역 후 파일 역시 txt파일로 저장되었다.

* 번역하기로 선택한 챕터가 300개의 문장이 있었는데 위에서 언급했던 주의사항들에 부합하는 문장들을 번역하지 않았다. 따라서 총 300개의 문장과 5399개의 단어 중 189문장을 번역하였고 5115개의 단어를 번역하였다. 번역하지 않은 문장은 대부분 괄호 안에 묶여 있고 굉장히 짧아서 많은 단어를 번역할 수 있었다고 생각한다.
![번역 안한 문장](https://user-images.githubusercontent.com/84717789/147364026-4c068dbc-afa0-4dd3-a17b-d45284f64f5b.png)

* 이더리움과 블록체인에서 사용하는 용어들이 영어로 적혀있었기 때문에 바로 와닿지 않아서 번역기의 도움을 받았다. JavaScript, Web3, MetaMask와 같은 고유명사는 되도록 번역하지 않고 원문 그대로 사용하였다.

### 번역 결과
189개의 문장을 번역하였고 5115개의 단어를 번역하였다.
![번역 결과](https://user-images.githubusercontent.com/84717789/147364183-fd357ace-d609-499a-b371-545b6dc538d7.png)
![단어 개수](https://user-images.githubusercontent.com/84717789/147479052-4e98d878-66b3-482f-ad8c-4ed1a0ac0063.png)

### 느낀 점
번역하기로 결정한 3번째 clients 파트는 총 300개의 문장이 있었다. 하지만 위에서 언급한 번역 시 주의사항을 준수하기 위해 대략 100개 정도의 문장은 번역하지 않았다. 번역할 문장이 한 줄 정도로 끝날 줄 알았는데 문장의 길이가 길고 여러 개의 문장이 존재하여 번역하는 데 더 많은 시간이 들었다.

![번역 길이](https://user-images.githubusercontent.com/84717789/147364405-643644ec-cb1c-4b9e-bac8-61cc789ad8a6.png)

그래도 번역을 하면서 이더리움이 어떤 언어와 플랫폼, 라이브러리 등을 사용하는지 대략적으로 공부할 수 있었고 실제로 이더리움의 거래 및 전송을 할 수 있는 어플이 존재한다는 사실도 알게 되었다. 수업을 통해 처음 알게 된 transifex라는 사이트와 번역을 하면서 이더리움과 블록체인 환경에서 사용되는 용어를 공부할 수 있었고 신기한 경험이었다. 대가 없이 오픈소스 환경의 발전을 위해 수 많은 사람들이 자발적으로 기여를 하고 있다는 점이 대단하게 느껴졌다. 오픈소스 수업을 들으면서 배웠던 내용들을 이렇게 직접 번역에 참여하여 오픈소스 환경에 기여했다는 점이 뿌듯했고 앞으로 소프트웨어 산업에 여러모로 도움이 되는 개발자로 성장하고 싶다는 생각을 했다.
