 ## 첫번째 실습
 ~~~
 <div>
<!doctype html>
<html>
    <head>
     <meta charset="utf-8">
     <title>First blog</title>
    </head>
    <body>
     <h1>LikeLion web programming</h1>
     <p>웹 프로그래밍 강좌에 오신걸 환영합니다.</p>
    </body>
</html>
 </div>
 ~~~
#### 코드 부가 설명
##### meta charset = "utf-8"
>> 웹문서 파일이 웹브라우저에서 표시되는 과정에서 인코딩할때 지정된 문자코드로 인코딩해라 하는 의미

##### <title>
>> 웹 페이지에서 제목을 담음
 
##### body
>> 문서 내에서 한개만 존재
>> <body> 태그는 문서의 몸통을 나타내는 태그
>> 브라우저 화면에 보이는 것들이 주로 들어감
 
 ## 레이아웃과 관련된 두번째 실습
 
* header
 >> 웹 페이지 혹은 <section>의 소개나 제목을 담기 위해 사용하는 요소
 
 
* nav
 >> 네비게이션 역할을 하는 요소
 
 
* section
 >> 기준에 따라 구획을 구분하기 위해 사용하는 요소
 
 
 ~~~
 <div> 
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>2번째 실습</title>
    <p>젊음팀 화이팅!</p>
</head>

<body>
    <header>
        로고와 이름이 들어갈 자리
    </header>
    <nav>
        <p>사이트 메뉴 자리</p>
    </nav>
    <section>
        <p> 첫번째 기사 자리</p>
        <article>
            <p> 두번째 기사 자리</p>
        </article>
    </section>
    <aside>
        <p> 광고가 들어갈 자리</p>
    </aside>
    <footer>
        <p> 회사 저ㅇ보가 들어갈자리</p>
    </footer>

</body>

</html>
</div>
 ~~~
