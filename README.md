# 5JO-REPOSITORY

## 5장 서버 내용정리
* ### 5.1 서버 저장소 (장태현)
  ### (내용)
  
* ### 5.2 깃허브 서버 정리 (장태현)
  ### (내용)
  
* ### 5.3 깃허브 연동 및 원격 등록 (김성원, 이세진)
  ### (내용)
  
* ### 5.4 서버 전송 (양준모)
  #### push : 원격 저장소로 커밋된 파일들을 업로드하는 동작
  #### $ git remote -v를 이용하여 원격 저장소와 연결된 서버 목록을 확인
  #### $ git push (원격저장소별칭) (브랜치이름을) 통해 커밋들을 원격저장소에 저장할 수 있다
  #### $ git push origin master으로 보면 origin=원격저장소별칭, master=브랜치이름
  
* ### 5.5 자동으로 내려받기 (김태윤)
  ### (내용)
   
* ### 5.6 수동으로 내려받기 (양준모)
  #### 원격 저장소의 내용을 내려받는 방법은 크케 두가지로 pull(풀)과 fetch(페치)가 있다
  #### pull(풀)은 원격 서버에서 현재 커밋보다 더 최신 커밋 정보가 있을 때 내려받는다
  
  #### 여러 개발자와 협업하는 과정에서 pull 명령어가 자동으로 브랜치 병합을 하지 못하고 충돌이 발생하기도 하는데 이럴때는 페치 방식을 사용해야 한다
  #### fetch(페치)는 원격 저장소에서 코드를 수동으로 내려받는 작업을 한다.
  #### 페치 사용 방법 : $ git fetch 원격저장소URL
  #### pull 명령어와 달리 fetch 명령어를 실행한 후에는 커밋이 추가된 것을 확인할 수 없당. 
  #### 왜냐하면 페치는 원격 저장소의 커밋들만 가지고 왔을 뿐 로컬 저장소에서 어떤 작업도 하지 않기 때문이다.
  #### 내려받은 커밋을 로컬 저장소에 적용하려면 병합 명령을 실행해야 하는데 이떄 merge 명령어를 사용해야한다.
  #### $ git merge 원격저장소별칭/브랜치이름 명령어를 사용하면 수동으로 병합이 된다.
  #### 1. pull명령어 사용 2. pull오류 나면 fetch로 커밋을 가져오고 merge로 가져온 커밋을 병합

Note
   
* ### 5.7 순서 (김태윤)
  ### (내용)
   
* ### 5.8 정리
  ### (내용)
