# 학습내용 정리
# Isoori_file
<h3>컴퓨터는 어떻게 동작할까?</h3>
<ol>
<li>컴퓨터는 무엇인가?</li>
</ol>
<ul>
<li>다양한 반복적인 작업들을 대신 해주기 위해서 컴퓨터를 사용한다.
<ul>
<li>비슷한 예시 : 먼 거리를 빨리 가기 위해 자전거를 탄다. / 먼 거리에 있는 사람과 연락하기 위해 휴대폰을 사용한다.</li>
</ul>
</li>
</ul>
<ol start="2">
<li>컴퓨터의 하드웨어</li>
</ol>
<ul>
<li>입력장치
<ul>
<li>키보드</li>
</ul>
</li>
<li>중앙장치
<ul>
<li>CPU
<ul>
<li>로직 게이트 : Boolean(True, False) / AND, OR, NOT -&gt; 컴퓨터의 최소 단위 : 0 또는 1 / 참 또는 거짓을 가진다. -&gt; 1 bit( 0 = false, 1 = true)</li>
</ul>
</li>
<li>Circuits와 Functional Unit
<ul>
<li>로직 게이트 : 1 bit들을 다양하게 조합해서 수리적인 연산과 논산들을 할 수 있게 되는 것이다.</li>
<li>플립플롭 : 데이터를 저장하는 아주 단순한 회로이다. 플립플롭이 그룹을 이루게 되면 64 bit의 데이터를 저장하는 레지스터가 된다.</li>
<li>1 byte = 8 bit</li>
<li>Functional Unit : 회로들이 모여서 구성하게 된다. 수리적, 논리적 연산, 저장 작업 등을 수행한다.</li>
</ul>
</li>
<li>컴포넌트
<ul>
<li>CPU는 컴퓨터를 구매할 때 아주 좋은 포인트가 된다. 진동수가 높을 수록 CPU의 성능이 올라간다. 진동수가 올라갈수록 연산수가 올라간다.</li>
<li>RAM : 컴퓨터가 켜져 있는 동안만 데이터를 저장한다. -&gt; HDD나 SSD에 저장한다.</li>
</ul>
</li>
</ul>
</li>
<li>출력장치
<ul>
<li>모니터</li>
</ul>
</li>
<li>시스템
<ul>
<li>우리가 입력장치를 통해서 중앙 제어 장치를 거쳐 모니터에 우리가 원하는 것을 보여준다.</li>
</ul>
</li>
</ul>
<hr>
<h4>컴퓨터는 무엇일지 정의 내려보기</h4>
<p>원하는 명령을 입력하고, 반복되는 작업을 해결한 뒤 결과를 출력해 받아보기 위해서 사용하는 기계 장치이다.</p>
<hr>
<h4>우리가 생각하는 컴퓨터와 동일하게 동작하는 디바이스들을 찾아보기</h4>
<ol>
<li>스마트폰 : 입력장치, 중앙 제어 장치, 출력장치가 모두 포함되어있고, 논리적 / 수리적 연산을 실행할 수 있기 때문이다.</li>
<li>아날로그 전화기 : 버튼을 눌러 번호라는 값을 입력하면 스피커 장치를 통해 오디오 정보가 출력되는 과정이 컴퓨터의 입출력 과정과 흡사하기 때문이다.</li>
<li>계산기 : 입력 버튼 장치를 통해 숫자값 / 연산자를 입력하면, 수리적 연산이 이루어지고, 모니터 출력장치에 우리가 원하는 결과값이 보이기 때문이다.</li>
</ol>
<hr>
<h4>What is the difference between register and transistor?</h4>
<p>The difference between register and transistor is that the register remembers the pattern, but the transistor doesn’t.</p>
<hr>
<h4>HDD와 SSD의 장단점은 각각 무엇이고, 우리는 언제 HDD를 사용해야 할까?</h4>
<p>HDD의 장점은 저장공간이 많고 싸다는 것이지만, 단점은 충격에 약하고 소음이 발생하고 소비 전력이 높고 발열 문제가 있다는 것이다.
SSD의 장점은 처리속도가 빠르고 작동 소음이 없고 전력 소모가 적다는 것이지만, 단점으로는 수명이 짧고 용량 당 가격이 비싸다는 점이다. 많은 양의 데이터를 저장할 때 HDD를 사용하는 것이 좋다.</p>
<br>
<h3>Git</h3>
<ul>
<li>
<p>Git</p>
<ul>
<li>정의 : 파일의 수정/변경 사항을 추적하는 시스템</li>
<li>이용 방법: 데스크탑, 클라우드 등에 저장한다.</li>
<li>장점 : 개발 같이 여럿이서 수정하는 문서의 팀원 간의 공유 및 공동 작업에 용이함</li>
</ul>
</li>
<li>
<p>관련 용어</p>
<ul>
<li>repositories : 저장 폴더</li>
<li>commits : 파일 변경 내용 기록 -&gt; 커밋을 해 놓으면 문서의 어느 수정 시점으로든 돌아갈 수 있음</li>
<li>branches : 곁가지. 복사본에서 실험해보는 느낌? 실험적인 활동을 하고자 할 때 사용.</li>
</ul>
</li>
<li>
<p>Git / Github의 차이점</p>
<ul>
<li>‘Git’은 변경 사항을 추적하는 ‘시스템’ 을 명명</li>
<li>‘Github’는 변경 사항을 저장할 수 있는 ‘클라우드 서비스’(Gitbucket 등등)을 아우르는 단어.</li>
</ul>
</li>
<li>
<p>Git 유사 경험 ;</p>
<ul>
<li>마인드마이스터에서 기록된 이전의 파일을 다시 불러올 수 있는 것</li>
<li>애플 아이워크에서 수정된 시간대를 찾아가며 기록되어있는 내용의 시점을 변경할 수 있음.</li>
<h1>Git 사용</h1>
<br>
<h4>파일 만들기</h4>
<ul>
<li>New respository (command + N)</li>
<li>파일 이름과 Description을 작성 하고 위치를 설정한다.
<br>
<br></li>
</ul>
<h4>수정</h4>
<ul>
<li><a href="http://README.md">README.md</a> 파일에서 텍스트 편집기를 통해 수정할 수 있다.</li>
<li>원하는 명령어를 작성하고 github에서 Commit 한다.</li>
<li>origin 버튼을 통해 파일 내용이 다른 사람들에게도 수정 된 것을 볼 수 있다.
<br>
<br></li>
</ul>
<h4>branch 병합 충돌시 해결방법!</h4>
<ul>
<li>‘&lt;&lt;&lt;&lt;&lt;&lt;&lt;HEAD’ 부터 ‘=<mark><mark><mark>’ 사이의 구간이 현재 체크 아웃된 파일의 내용이고 ‘</mark></mark></mark>=’ 부터 ‘&gt;&gt;&gt;&gt;&gt;&gt;&gt;서버주소’의 구간이 병합하려는 대상인 브랜치의 코드 내용이다.</li>
<li>Github : 이 정보를 참고로해서 두개의 코드를 병합한 후에 특수기호들을 제거해주면 된다. 작업이 끝나면 파일을 저장.</li>
</ul>
유달헌 수달 수달



<h3>컴퓨터가 서버와 통신하는 과정(디딤영상)</h3>
<ol>
<li>
<p>영문 주소 주소창에 입력</p>
</li>
<li>
<p>Dns를 통해 문자 주소를 ip 주소로 변환.</p>
</li>
</ol>
<ul>
<li>IP 주소(address) : 특정 사이트의 위치 정보를 제공하는 주소.</li>
<li>Ip 종류 : ipv4 / ipv6.</li>
<li>과거엔 ipv4를 썼으나, 공간 부족 문제 등으로 현재는 ipv6 형식 주소 사용.</li>
</ul>
<ol start="3">
<li>
<p>변환한 ip 주소로 보내고자 하는 정보를 전달함. 이 때 데이터는 packet 단위로 나뉘어져 전달됨.
-packet : 긴 편지글이 편지지에 나누어져서 전달함. 여기서 편지지가 편지글을 전달하는 단위라면, packet은 데이터를 전달하는 단위.</p>
</li>
<li>
<p>packet 단위의 데이터가 성공적으로 ip 주소의 네트워크에 접속하면, 브로드캐스트(방송)을 함. 이를 통해 원하는 하드웨어의 랜 카드(하드웨어 주소/위치 개념)를 찾음.</p>
</li>
</ol>
<ul>
<li>ip 주소는 논리적 주소, lan 주소는 물리적 주소라 칭함.</li>
<li>논리적 주소를 물리적 주소로 바꾸는 것을 arp 프로토콜이라고 함.</li>
<li>물리적 주소를 논리적 주소로 바꾸는 건 irp 프로토콜이라고 함.</li>
</ul>
<ol start="5">
<li>해당 하드웨어에서 원하는 데이터를 가져옴.</li>
</ol>
<ul>
<li>웹 서버에 요청할 내용이 html인 경우, 이를 전달하는 프로토콜을 http라고 함.</li>
</ul>
<ol start="6">
<li>결과로 해당 사이트 페이지가 뜨게 됨.(구글, 유튜브 창 등…)</li>
</ol>


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


<h4>Git 학습내용</h4>
<ul>
<li>
<p>Branch란? : 가지라는 뜻으로, 작업을 분기해서 처리하는 경우를 말한다.</p>
</li>
<li>
<p>Branch의 종류 : Camera Branch(새로운 브랜치), Master Branch(원래 있던 브랜치)</p>
</li>
<li>
<p>Branch conflict</p>
</li>
</ul>
<ol>
<li>병합 충돌이 생기는 원인 :  두 계정 사이에 수정이 동시에 벌이지는 경우에 충돌이 자주 생긴다.</li>
</ol>
<ul>
<li>해결방법</li>
</ul>
<ol>
<li>‘&lt;&lt;&lt;&lt;&lt;&lt;&lt;HEAD’ 부터 ‘=<mark><mark><mark>’ 사이의 구간이 현재 체크 아웃된 파일의 내용이고 ‘</mark></mark></mark>=’ 부터 ‘&gt;&gt;&gt;&gt;&gt;&gt;&gt;서버주소’의 구간이 병합하려는 대상인 브랜치의 코드 내용이다.</li>
<li>이 정보를 참고로해서 두개의 코드를 병합한 후에 특수기호들을 제거해주면 된다.</li>
<li>작업이 끝나면 파일을 저장.</li>
</ol>
수달 멀지