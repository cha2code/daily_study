# 문자열 및 데이터 유무 체크 🧑‍💻

### 🦺 ObjectUtils.isEmpty()

* List로 데이터 조회 시, 조회된 데이터가 없는 경우 NPE 발생을 피하기 위해 사용
* Null 체크 및 빈 문자열 체크가 동시에 가능
* Collection 타입에 사용 : CollectionUtils.isEmpty() (수행하는 방식은 동일함)

### 🦺 StringUtils.hasLength()

* Null 체크 후 String클래스의 isEmpty를 호출하여 길이가 0인지 판별
  * 공백만 있는 문자열도 true를 반환하기 때문에 공백에 상관 없이 null만 판별하고 싶을 때 사용

### 🦺 StringUtils.hasText()

* 객체(Object)가 Null / length > 0 / 공백이 아닌 문자 인지 확인
  * 셋 중 하나라도 만족하면 true, 만족하지 않으면 false 반환
 
[참고사이트](https://creampuffy.tistory.com/120)
