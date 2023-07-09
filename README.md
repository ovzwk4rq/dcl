# dcl

Dennis Ritchie 와 Brian Kernighan 의 책 The C Programming Language 의 5장 12절의 프로그램을 보고 재귀하향파서를 보다 잘 이해하기 위해 직접 구현해봐야겠다는 생각으로 만든 프로그램.  

책에 나온 프로그램과의 차이점  
* 책에 나온 프로그램은 함수의 파라미터가 없는 경우만을 해석하지만 이 프로그램은 함수의 파라미터가 있는 경우도 해석함.
* 책에서 ungetch 함수를 사용했는데 그게 불필요하고 지저분하다고 느껴서 사용하지 않음.
* 책에 나온 프로그램은 틀린 선언에 대해 syntax error 라고만 출력하지만 이 프로그램은 어디에서 어떤 문제가 발생했는지 에러 메시지 출력.

실행 방법  
표준 입력으로 해석하고자 하는 선언을 넣으면 그 뜻을 영어로 읽어서 출력함.
