"# TIL"

git 사용법

git init
git add .
git status
git commmit -m "commit name"
git branch
git branch add-coach
git branch -m (기존 브랜치명) (새 브랜치명)
git merge add-coach
git remote add origin (원격 저장소 주소)
git branch -M main
git push -u origin main
git remote
git remote remove (origin 등 원격 이름)
git push

html 문법

TAG 이름이다.

<body> 태그에 해야하는 문법들
<strong> 강조 할 단어 </strong> 강조할 때 쓰는 문법

<h1> 오늘의 명언 </h1>  대제목! 제목으로 표현할 때 쓰는 문법 h1, h2
<h2> 오늘의 명언 </h2>  소제목!
<a href="링크"> 도날드 커누스 </a> 링크를 걸어주어 사이트를 열어주는 문법
<a href="링크" target="_blank"> 도날드 커누스 </a> 링크를 걸어주어 새로운 사이트로 열어주는 문법 'href' 와 'target'의 순서가 바뀌어도 똑같이 동작한다.
<li> 단어 </li> 항목들을 구분되게 해주는 문법
<ul> 그룹 </ul> <li> 문법을 순서가 없게 그룹화 해주는 문법
<ol> </ol> 순서가 있는 그룹화 해주는 문법

위쪽까지의 문법들은 웹의 본문에 해당되는 문법들이다

<head> 태그에 해야하는 문법들
<title> 제목 or 기업이름 등등 </title> 웹의 제목을 나타내주는 문법
<meta charset="utf-8"> 글씨가 깨지는 형상을 고쳐주는 문법

문서들을 꾸며주는 부가적인 문법이라고 볼 수 있다

<head>, <body> 태그들은 <html>태그에 포함된다
<Doctype> 어떤 브라우저인지 알려주는 문법(?) 
선언 선택자 종류 태그 선택자, 아이디 선택자(단 한번만), 클래스 선택자(그룹화가능)
#select{font-size: 원하는 크기} id="select" ~~

CSS 문법
<font> 글자를 색칠해주는 코드
<style> 태그의 안에 있는 코드들은 html 문법이 아닌 css 문법
정보와 디자인의 분리
<h1 style="color: red;">Hello World</h1> --> color:red만 css문법
        <style>
            h2{color: blue;} --> 이거만 css 문법
        </style>
색을 표시하는 두가지 방법

선택자 팁 (selector) 는 중요하다

	flex-start (default)	                >>  요소들을 컨테이너의 왼쪽으로 정렬

	flex-end					>>   요소들을 컨테이너의 우측으로 정렬

	center					>> 요소들을 컨테이너의 중앙으로 정렬

	space-between		                >> 요소들 사이에 동일한 간격을 둡니다.

	space-around	        		>> 요소들 주위에 동일한 간격을 둡니다.

	space-evenly(FireFox Only)	        >> 첫번째로 오는 정렬 대상 전에 두개 의 인접한 정렬 대상 사이의 간격과"# TIL2" 
"# TIL2" 
"# TIL2" 
