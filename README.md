# pre-learning-2026
IoT 개발자 과정 사전 학습 리퍼지토리

## 1일차
과정 소개

학습 리포지토리 생성 

- 마크다운 학습
  1. 기본 문법
    ```markdown
    # 제목1
    ## 제목2
    ### 제목3
    #### 제목4
    ##### 제목5
    ###### 제목6
    <!--주석(HTML주석 동일)-->
    ```


    2. 기본문법 - 목록
    ```markdown
    - 목록
    * 목록
    1. 숫자 목록
    2. 숫자 목록 
    ```

   3. 기본 문법 - 링크, 이미지
   ```markdown
   
   [네이버](http://naver.com) 
   ![이미지](https://camo.githubusercontent.com/964c6e7cf851b4607cddebae3c83e0f022a92f35fe16c3b22ec26bb0c3e292f2/68747470733a2f2f73736c2e707374617469632e6e65742f6d656c6f6e612f6c6962732f313532322f313532323032302f61613562343862376537663765316536643434635f32303235303130393137343135323633302e6a7067)
   ## 사이즈 조절 이미지
   src: 이미지URL
   width: 이미지 넓이 픽셀 단위 지정
   <!-- img src="이미지URL" width="500">
   ```
   - [네이버](http://naver.com)
 
  
   - ![환수사로고](https://camo.githubusercontent.com/964c6e7cf851b4607cddebae3c83e0f022a92f35fe16c3b22ec26bb0c3e292f2/68747470733a2f2f73736c2e707374617469632e6e65742f6d656c6f6e612f6c6962732f313532322f313532323032302f61613562343862376537663765316536643434635f32303235303130393137343135323633302e6a7067)
  
   - <img src ="https://camo.githubusercontent.com/964c6e7cf851b4607cddebae3c83e0f022a92f35fe16c3b22ec26bb0c3e292f2/68747470733a2f2f73736c2e707374617469632e6e65742f6d656c6f6e612f6c6962732f313532322f313532323032302f61613562343862376537663765316536643434635f32303235303130393137343135323633302e6a7067" width ="100">

- <img width="612" height="531" alt="image" src="https://github.com/user-attachments/assets/a8fc9845-b060-41b3-82b9-586696cac9f1" />

   - 이미지와 링크 차이는 ! 차이다
  4. 기본 문법 - 가로줄
     ```markdown
     ---
     
     ```
  ---

  5. 기본 문법 - 코드 블럭
    - 소스코드를 작성할때 코드하이라이팅, 영역 표시때 사용
    - 백틱(`)을 세번 후 표시 언어를 입력 또는 한번(인라인 코드 블럭)
    ```python
    print('Hello, Python')
    
    ```
   - 일반적인 문장에서 한 단어를 강조 하고 싶을때 ` 인라인 코드 블럭 `을 사용

 6. 기본 문법 - 강조 및 밑줄
  ```markdown
**,~~,__ 사용
  ```
  - 문장을 작성할시 **강조**, ~~취소선~~, __ 밑줄 __을 사용 할수 있다.


- GITHUB 로컬 리포지토리 생성
  1. GIT FOR WINDOWS 설치
    - https://git-scm.com/install/windows 에서 `install for window` 버튼 클릭
    - Git for Windows/x64 Setup. 설치
    - Git 설치 옵션은 기본 그대로 사용 가능
    - cmd 또는 powershell창에서 `git --version` 확인
  3. GITHUB DESKTOP 설치
    - https://desktop.github.com/download/에서 다운로드 클릭, 설치
    - 계정 연동
  
  4. 리포지토리 클론
     - Github Desktop 메뉴 Clone Repository 클릭
     - Github.com 탭에서 저장소 검색, 선택
       Local Path 지정 후 `클론` 버튼 검색


 5. Visual Studio Code 설치
   1. Extensions -> Korean pack for Visual Studio Code 설치

- 추가 설치 프로그램
 1. notepad++ 에디터 - https://notepad-plus-plus.org/downloads/ 설치
 2. 픽픽 -   https://picpick.net/download/beta/ 설치


- **python** 개발 환경 설정
