# :pencil2: 필기면접 준비
</br>

### :heavy_check_mark: **HTTP Server vs WAS(Web Application Server) 차이**

  - **HTTP Server(Web server)**   
    \- 일반적으로 인터넷 브라우저를 통해 HTTP를 사용하여 클라이언트 컴퓨터와 통신하는 서버입니다.     
    \- 클라이언트의 웹브라우저로부터 HTTP 요청을 받아 정적인 컨텐츠(.html, .css, .js, .jpng, .png 등)를 제공하는 컴퓨터 프로그램.  
    
    
 HTTP (Hyper Text Transfer Protocol)
웹 사이트에서 사용되는 기본 프로토콜

### :heavy_check_mark: **replaceAll("[a-zA-Z]","").toUpperCase()**
  - **\[a-zA-Z]\(정규식)**   
    \- a-z, A-z까지 정규표현식(Regex)
    
  - **toUpperCase()**    
    \- toUpperCase() 메서드는 문자열을 대문자로 변환한 값을 반환합

### :heavy_check_mark: **extends vs implement 차이**  
  - **extends(상속)**     
    \- extends 키워드를 사용하여 부모클래스를 상속받아 자식클래스에서 부모클래스가 가진 것을 사용할 수 있습니다.  
    \- 부모가 가진 것을 자식에게 물려주는 것을 is a 혹은 kind of 관계라고 부릅니다.  
 
  - **implement(구현)**  
    \- 인터페이스를 상속받아 기능을 재정의(Overriding)하는 것 입니다.

### :heavy_check_mark: **Call by Value vs Call by Reference 차이**  
  - **Call by Value**   
    \- 값에 의한 호출을 의미합니다.   
    \- 전달받은 값을 복사하여 처리하기 때문에 전달받은 값이 변경되어도 원본의 값을 변경되지 않습니다.  
    \- `정리` Call by value는 메서드 호출 시에 사용되는 인자 값의 메모리에 저장되어 있는 값(value)을 복사하여 보낸다.
    
  - **Call by Reference**   
    \- 참조에 의한 호출을 의미합니다.   
    \- 전달받은 값을 직접 참조하기 때문에 값이 변경되면 원본도 같이 변경됩니다.  
    \- `정리` Call by reference는 메서드 호출 시 사용되는 인자 값의 메모리에 저장되어있는 주소(Address)를 복사하여 보낸다.  
    
### :heavy_check_mark: **JSON 타입**  
  - **JSON(JavaScript Object Notation)**  
    \- 키-값이 쌍으로 이루어진 개방형 표준 데이터 포맷입니다. (데이터 교환 형식, 인터넷에서 자료를 주고 받을 때 표현방법)  
    \- 비동기 브라우저/서버 통신(ajax)을 위해 사용하는 데이터 포맷입니다. (JavaScript에서 객체를 만들 때 사용하는 표현식) 
    \- {"key" : "value"}

    #### [`+여기서 잠깐`]() ajax란?  
      \- 페이지 새로고침 없이 서버에 요청을 할 수 있습니다.  
      \- 서버로부터 데이터를 받고 작업을 수행할 수 있습니다. 
      
