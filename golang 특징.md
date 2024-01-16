class 문법이 없다. 
return을 사용하면, return 이후의 코드는 실행되지 않는다. 

`nil`: 
**- nil은 포인터, 인터페이스, 맵, 슬라이스, 채널, 함수의 zero value이다.**
**- zero value는 명시적인 초기값을 할당하지 않고 변수를 만들었을 때 해당 변수가 갖게 되는 값이다.**
예) string의 nil 은 ''
빈 값과, 애초에 아무것도 없는 것은 다르다. zero value는 애초에 아무것도 없는 값인 것 
zero value 로 사용되지만, 다른 보통의 프로그램 언어에서의 Null과는 다르다. 
nil check ex: 
`slice == nil` or `map == nil`. 
