# minyoung1

#변수 선언
var author='개발하는남자';
String author='개발하는남자';

#Null Safety
String name = '개발하는남자';
String? bookName;

#컬렉션 타입
var numbers = [1, 2, 3];
numbers.add(4);

var fixedList = List<int>.filled(3, 0);

#Set (중복 불가)
var fruits = <String>{'사과', '바나나', '사과'};
print(fruits);

#Map (키-값)
var person = {
  'name': '개발하는남자',
  'age': 37,
};
