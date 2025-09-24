4주차 배운내용 정리<br>
String? bookName;<br>
print(bookName.length); <-- 이 두줄을 입력하면 오류.<br>
[해결방법]

if(bookName != null {<br>
  print(bookName.length);<br>
  }<

  or

  print(bookName?.length);

  실습은 다트패드를 이용해서 함.
