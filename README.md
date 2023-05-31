# sass 사용안함, scss를 사용한다. scss -->샤스라고 읽음
![image](https://github.com/yangjungmin/sass/assets/129017040/03664314-0df1-438d-a19e-9f2204503081)

# scss 컴파일
![image](https://github.com/yangjungmin/sass/assets/129017040/01ccb1a7-5202-4157-b265-83580bbad836)

# css 위치변경
![image](https://github.com/yangjungmin/sass/assets/129017040/94d1c1bb-51af-4533-a06c-36634ec9f5c0)

# savaPath:null이면 scss파일과 같은 위치에 style.css가 생긴다.
![image](https://github.com/yangjungmin/sass/assets/129017040/7c8908e0-0181-433e-9109-5e90c738fc80)

# ~은 style.scss를 의미, /는 style.scss가 있는 폴더
![image](https://github.com/yangjungmin/sass/assets/129017040/73f63609-9f50-4420-a058-a06da36323b8)

# scss파일이 있는 폴더의 상위요소에 생성
![image](https://github.com/yangjungmin/sass/assets/129017040/7b6ceb1f-77f3-461b-8431-76d2499ea941)

# 주석처리 방법
# //로 주석처리하면 scss에만 주석메모가 남음
# /*   */ 주석처리방법은 css로 컴파일되어 나타남
![image](https://github.com/yangjungmin/sass/assets/129017040/0afc6d05-d0ee-48d8-896b-72ac6fa29e7f)

# 변수 만들기 --> $로 시작함,(영문, 숫자, -,_)만 사용할 수 있음. 숫자로 시작할 수 없음.
![image](https://github.com/yangjungmin/sass/assets/129017040/5be7f4f0-ca9e-432e-adf5-1498f67db4a7)

#Partials(파샬)
-- 관련된것끼리 묶어서 분리/ 소스에 반복되는 부분들을 분리 분산시켜서 모듈화 시키는 기능

*Partials의 파밍명은_로 시작하며
*불러들일때는 @import '파일명', 이때 파일명에 _는 포함시키지 않고, 확장명도 포함시키지 않는다.

✡️ Scss는 _로 시작하는 파일은 컴파일하지 않는다.

![image](https://github.com/yangjungmin/sass/assets/129017040/1db59abe-1169-4f54-8d43-ca1c703c6a48)

# @import --> 변수가 중복될 때는 아래의 것이 적용된다.
![image](https://github.com/yangjungmin/sass/assets/129017040/dad65bbe-072f-4cf5-a152-24e513a0e5a0)


# @use  --> 변수이름이 같을 때 에러발생, @use를 사용할때는 앞에 파일명을 추가해서 파일명.변수명
![image](https://github.com/yangjungmin/sass/assets/129017040/045ff139-ec1b-462d-8b08-7ee08b0e1fdb)

+추가 -> 확장명을 다 안써줘도 됨 _ 이것도 안적어줘도 됨 그냥 변수명만 써주면 됨
![image](https://github.com/yangjungmin/sass/assets/129017040/c7f18d6b-d455-4a3a-954b-588ca0b2cde7)

# as 뒤에 별명을 붙여서 사용할 수 있다.
![image](https://github.com/yangjungmin/sass/assets/129017040/728b668d-1f71-4e7d-807a-18a62fa50d7c)

#@forward는 파샬을 묶어줌 style.scss에서는 _index.scss를 호출하여 사용함
![image](https://github.com/yangjungmin/sass/assets/129017040/d8d5ce32-f83b-4d9e-8005-c447be3e581d)

# *(와일드카드)를 붙이면 이름을 생략할 수 있음
![image](https://github.com/yangjungmin/sass/assets/129017040/8ffb5b81-e107-4340-b771-67012c595417)





