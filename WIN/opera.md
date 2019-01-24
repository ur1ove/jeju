### 오페라 캐시 폴더 위치 변경하기
- 참고 : [http://egloos.zum.com/shirupurito/v/3170745](http://egloos.zum.com/shirupurito/v/3170745)  
- 방법
  1) 오페라를 종료한다  
  2) 오페라 캐시를 삭제한다.(시스템 드라이브:\Users\사용자명\AppData\Local\Opera Software\Opera Stable\Cache)  
  3) 명령어 프롬프트를 실행한다.  
  4) mklink /j "오페라 캐시 경로" "D:\임시(지우지마라)\오페라"  
