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
유달헌 수달
