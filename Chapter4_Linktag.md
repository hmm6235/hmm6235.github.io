## 하이퍼 링크?
>> 간단하게 주소 링크라고 생각하자!


ex) <a> </a> 태그 : 하이퍼링크를 걸어주는 태그
>> <a 속성> </a> 

## 속성
>> 태그에 대해 추가적인 정보 제공
>> HTML의 모든 태그는 속성을 가질 수 있음
>> 키 = "값"


ex) 링크 태그
>> <a 링크주소 = "www.google.com">구글</a>

ex) href
>> 클릭시 이동할 링크
>> 연결할 웹사이트 주소를 가지고 있음
>> <a href="http://www.naver.com">Go Naver</a>
>> 여기서 href는 속성의 의미를 가짐!

* URL
>> 인터넷에서 HTML 페이지, CSS문서, 이미지 등 자원(Resource)의 위치를 나타냄
>> href의 속성이 됨


- 절대 URL

: 접근하는 최초 시작점부터 경유한 경로를 모두 기록하여 리소스의 위치를 나타냄

ex) \Users\hmm62\Desktop\LikeLion\first_git

- 상대 URL

: 기준점을 기준으로 상대적인 경로를 기록하여 리소스의 위치를 나타냄

ex) .\first_git 
>> 현재 경로(위치:LikeLion)에서 first_git으로 이동


### href를 이용한 간단한 실습
 ~~~
 <div>
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>젊음 팀 화이팅!</title>
    </head>
    <body>
        <h1> Class Lion 강의 Chapter 4에 대한 요약본 입니다.</h1>
        <a href = https://github.com/hmm6235/hmm6235.github.io/blob/master/Chapter4_Linktag.md>클릭!</a>
    </body>
</html>
 </div>
 ~~~


