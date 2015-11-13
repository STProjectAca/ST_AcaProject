## Spring
* Spring 네이밍 규칙을 표준화하기 위한 페이지입니다.
* 추가할 부분이 있으면 추가 부탁드립니다.

## Pakage Naming
* 소문자로만 이루어진 최소 단위의 명사형 단어 사용
* 부득이하게 단어 조합이 될경우에도 소문자만 사용
 * ex) com.domain.casestudy.boardtype
* 도메인반대열겨/추가구분자]로 패키지네임을 구성한다.

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

## Interface Naming
* 명사형태의 단어 사용
* 첫 알파벳이 대문자인 카멜케이스를 사용
* 예제
 * class Raster
 * class ImageSprite

## Implement Class Naming
* 인터페이스를 구현하는 클래스가 하나일 경우 인터페이스 명 뒤에 Impl 만 붙인다. 
  1. interface DBConnection -> class DBConnectionImpl : implement DBConnection
* 인터페이스를 구현하는 클래스가 두개이상일 경우 구분자와 Impl를 붙인다. 
  1. DBConnectionMYImpl
  1. DBConnectionMSImpl
  1. DBConnectionOracleImpl

## 변수 Naming
* 명사형태로 카멜케이스로 사용한다.
* 임시변수일 경우i, j, k, m, n 은 interger를 위하여, c,d,e 는 character 용으로 사용한다.

## Constants Naming
* 대문자로 작성하며, 단어간 _ 문자로 구별한다 
 1. static final int MIN_WIDTH = 4;  
 1. static final int GET_THE_CPU=4
