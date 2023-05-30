[sass 사용 거의 안함. scss를 사용한다.(사스라고 읽음)]


## ⭐Visual Studio에서 확장 프로그램 설치(Live Sass Compiler)
  ![image](https://github.com/Parksejin412/sass_memo/assets/129017065/2b5dca5c-2397-40ff-9b31-36e38c4608e9)
  
-----------------------------------------------------------------------------------------------------------------
## ⭐scss 컴파일해서 style.css 만들기 
   ✔️ style.scss 파일 만들기 -> new 터미널 클릭 -> 아래쪽 wathing...클릭 -> style.css 파일 생성 확인 -> index.html에서 style.css 연결하기  
   
  ![image](https://github.com/Parksejin412/sass_memo/assets/129017065/64a58edf-f762-42cf-aa4b-a54656578cba)
  
-----------------------------------------------------------------------------------------------------------------  
## ⭐css 위치 변경하기
  ✔️ 톱니바퀴 아이콘 클릭 -> settings -> 검색창에 sass 검색 ->Formats -> Edit in settings.json 클릭
  
  ![image](https://github.com/Parksejin412/sass_memo/assets/129017065/59cb9fc6-2ae4-4dd2-a9e5-7de1f2e9570d)

  ![image](https://github.com/Parksejin412/sass_memo/assets/129017065/3b0fec3c-8035-425c-91eb-e498fe9ab0aa)
  
-----------------------------------------------------------------------------------------------------------------  
## ⭐settings.jason
   ✔️savePath:null => scss파일과 같은 위치에 style.css가 생성.
   
  ![image](https://github.com/Parksejin412/sass_memo/assets/129017065/1c9142c1-e814-4d9e-b586-68c031907693)
  
  ✔️savePath:"~/css" => css파일안에 style.css가 생성
  
  ![image](https://github.com/Parksejin412/sass_memo/assets/129017065/8ee655cb-d8ba-44a9-8ab2-caec9001597d)
  
  ![image](https://github.com/Parksejin412/sass_memo/assets/129017065/c6d4511b-866b-4c90-9726-b16eeff750b2)
  
  ✔️savePath:"~/../" => scss파일이 있는 폴더의 상위 요소에 생성
  
  ![image](https://github.com/Parksejin412/sass_memo/assets/129017065/d5d1162b-de86-4693-986e-538115a84d93)
  
  ![image](https://github.com/Parksejin412/sass_memo/assets/129017065/ac875045-5d5f-48ab-a52f-e2b9a669726a)
  
  💡 " ~ " => style.scss를 의미   " / " =>style.scss가 있는 폴더
  
-----------------------------------------------------------------------------------------------------------------
## ⭐주석문 작성하기
  ✔️ /*     * / style.css에 컴파일 되어 나타남.
  ✔️ // style.css에 컴파일 되지 않음.
      
  ![image](https://github.com/Parksejin412/sass_memo/assets/129017065/1d7c5926-3d46-48aa-ae77-a123cc767ed5)
  
-----------------------------------------------------------------------------------------------------------------
## ⭐변수선언
  ✔️$로 시작 ->영문,숫자,_ ,- 만 사용할 수 있음 숫자로 시작X
  
![image](https://github.com/Parksejin412/sass_memo/assets/129017065/94b6751d-767d-4b82-b933-9f5270194605)

![image](https://github.com/Parksejin412/sass_memo/assets/129017065/c04145f4-99df-46a9-a65c-b9bf64305030)

  ✔️ & => 상위 클래스명 부르기
  
![image](https://github.com/Parksejin412/sass_memo/assets/129017065/1ef33b48-4d36-493f-9a8c-7e5f198b616d) 

-----------------------------------------------------------------------------------------------------------------
## ⭐Partials(파샬)
  💡 관련된 것 끼리 묶어서 분리/ 소스에 반복되는 부분들을 분리 분산시켜서 모듈화 시키는 기능
  
  ✔️ Partials의 파일명은 _ 로 시작
  
  ✔️ 불러들일때 -> @import'파일명' -> '파일명'은 _ 은 포함X, 확장명 포함X
  
  ✔️ scss는 _ 로 시작하는 파일은 컴파일X
  
  ![image](https://github.com/Parksejin412/sass_memo/assets/129017065/9ce729d4-17ec-4f9e-b483-34c10d3beae4)

