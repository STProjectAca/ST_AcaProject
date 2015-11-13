## Spring
* Spring 네이밍 규칙을 표준화하기 위한 페이지입니다.
* 추가할 부분이 있으면 추가 부탁드립니다.

## Pakage Naming
* 소문자로만 이루어진 최소 단위의 명사형 단어 사용
* 부득이하게 단어 조합이 될경우에도 소문자만 사용
 * ex) com.domain.casestudy.boardtype
* [도메인반대열겨/추가구분자]로 패키지네임을 구성한다.

   | Domain Name | Pakage Name	|  
   |:-:|:---------:|
   |stcompany.com/eng|com.stcompany.eng|

	
## Class Naming
* 명사형태의 단어 사용
* 첫 알파벳이 대문자인 카멜케이스를 사용
* 예제
 * class Raster
 * class ImageSprite

## Method Naming
* 동사형태의 단어 사용
* 첫 알파벳이 소문자인 카멜케이스 사용
  1. run()
  1. runFast()
  1. getPerson()
* Dao와 Service는 수행하려는 쿼리 목적을 앞에 붙임
  1. selectMemberList()
  1. insertMember(String id, String name, String gender)
  1. updateMember(String id, String name, String gender)
