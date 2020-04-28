# 학습내용 정리

<h3>컴퓨터가 서버와 통신하는 과정</h3>
<ol>
<li>주소창에 영문 주소를 친다.</li>
<li>DNS에 따라 그 주소가 ip로 바뀐다.</li>
<li>Ip의 규칙에 따라 보내고자 하는 데이터가 패킷 형태로 나누어져서 해당하는 웹 사이트의 네트워크에 접속한다.</li>
<li>네트워크에 도달했을 때 브로드 캐스트를 통해 물리적 주소를 받아와서 해당하는 램카드가 있는 컴퓨터에서 데이터를 가져온다.</li>
<li>웹 서버에 접근 하기 위한 규칙이 tcp이다. 포트라는 걸 사용해야 한다. 랜 카드를 보고 아이피 찾았을 때 티씨피 방식에 따라 접근해야 한다. html을 사용한 주소라면 http 포트를 사용해야 한다. 포트는 우리가 가야 하는 서버의 형태에 따라서 타야 하는 통로의 종류이다.</li>
<li>최종적으로 사이트 페이지가 보인다.</li>
</ol>
<h3>IPv4와 IPv6를 사용하는 이유와 특징들</h3>
<ul>
<li>IPv4를 사용을 하다가 표현할 수 있는 주소의 개수가 부족해서 IPv6를 사용하게 되었다.</li>
<li>IPv4는 패킷이라는 크기가 64kb 크기로 제한, 32bit IP 주소 입력 방식 (40억개)</li>
<li>IPv6은 점보그램옵션 이용하면 제한없이 임의로 큰 크기의 패킷을 사용 가능, 128bit IP 주소 입력 방식(거의 무한대)</li>
</ul>
<h3>HTTP와 HTTPS의 차이점</h3>
<ul>
<li>HTTP 는 웹브라우저(Client)와 서버(Server)간의 텍스트를 교환한다.</li>
<li>HTTPS는 인터넷 상에서 정보를 암호화하는 SSL(Secure Socket Layer)프로토콜을 이용하여 웹브라우저(클라이언트)와 서버가 데이터를 주고 받는 통신 규약이다.</li>
</ul>