# HSHS_MYS
2024 HSHS 수학과학체험전 github입니다.


<스토리>
배경: 학교
https://github.com/JangUniverse/HSHS_MYS.git 
시작 이벤트:
(시작)
입학
입학한 주인공은 입학하자마자 A, B를 만난다
(1)김동현
-실험실
김동현의 이벤트이다. 화학 수행평가에서 같은 조가 되어 서로에 대해 더 잘 알아간다.
강제 이벤트
(1)B
-도서관
B 이벤트이다. 도서관에서 우연히 마주쳐 서로 수학에 대한 이야기를 하면서 서로를 알아간다.
강제 이벤트
(2)
-교실
분기점:
교실에서 김동현 B가 순차적으로 다녀가면서 각각 자신이 있는 동아리로 와달라고 해준다
(분기점)
동아리 정하기
SOMAT
Choice 김동현
LACE
Choice B

동아리 엔딩:

기: 학교 입학. 동아리 선택
승: 동아리 2중1택, 각 이벤트에 따라 호감도가 변하며 동아리 생활 진행.
전: 동아리 선택받은 히로인은 호감도 쌓이는 %가 더 커지고, 그렇지 못한 히로인은 적은 %로 호감도가 쌓인다. 결국 둘 중 하나를 택해야 하는 분기점을 맞한다.
결: 
1. 배드 엔딩: 두명 다 호감도가 낮아 조건을 충족시키지 못함: 교실에서 둘다 사이가 벌어지며 이야기가 끝남
2. 노멀 엔딩: 둘 중 한명과 사귀게 된다. 다른 한 명은 실망하며 자리를 떠난다. 주인공은 애매한 기분으로 스토리가 끝난다.
3. 히든 엔딩: 둘다 포기할 수 없었던 주인공은 둘과 함께 새로운 동아리를 만든다.
SQL injection을 실행했을 경우, 프로그램이 삭제된다(모니카 오마주)






인물
(김동현): 
인상착의:
머리: 주황색
눈 : 적홍색
안경: X
과학을 좋아한다.
활동적임
목소리: 보편적인 목소리에서 약간 낮은 목소리

(B)
인상착의:
머리: 하늘색
눈: 초록색
안경: O
수학을 좋아한다.
도서관에서 조용히 공부하는 스타일
목소리: 약간 높으면서 조용한 목소리


(C)
인상착의:
머리:
눈:
안경:
정보(코딩)를 좋아한다.


목소리:
()
()


사건

배경

 …..::일단은 미연시에 대한 아이디어가 있으면 단편적인 부분이라도 좋으니 일단 써주세요. 어차피 익명입니다…..

–총 30분–
LLM 소개(알고리즘, 특징), 파일 다운로드와 이미지생성 15분
게임 시연 15분
기타 5분


<게임 관련>
개발 언어:
웹(js, HTML, css)
장점: 툴 사용법을 배울 필요가 없고 상대적으로 자료가 많다. 현장에서 이미지 생성해서 넣기에 용이하다
단점: 학교 컴퓨터에서 돌릴 계획인데 localhost/3000이 죽을 수 있다, 파일을 전부 다운받게 해야한다.

RenPy
장점: 이미 만들어놓은 사람이 많아서 가이드가 잘 되어 있다. 파이썬이라 다른 작업 등이 수월하다
단점: 이미지를 즉석에서 넣기 힘들다.
##Renpy 사용 예정



게임 파일 구조(웹페이지 형식으로 만들 시)
main.js – 분기점이나 어떤 html 페이지 띄울지 지정
Html{
	각 인물마다 html 페이지 1개씩 할당
	각 인물마다 css 페이지 1개씩 할당
	각 인물마다 js 페이지(말? 텍스트? 넘어가는 용도)
	Images{
		주 인물 2 - 3명 정도는 인공지능으로 이미지 즉석 제작, 이름을 1.pdf, 2.pdf 등으로
		저장해놓게 시키기
		나머지는 미리 준비해놓기
}
}