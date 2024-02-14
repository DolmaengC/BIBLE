# 웹뷰앱 - 블로그 앱
조코딩님 유튜브 따라서 만들었습니다.
https://www.youtube.com/watch?v=yjPl8Injlbw&t=1362s 

![app_screen](https://github.com/DolmaengC/WebViewApp_Blog/assets/107832431/cd2a090c-6cbf-4859-815c-55906c33d4fe)

---
## Error report
1. PS C:\Test\my-app> eas build -p android --profile preview
eas : 이 시스템에서 스크립트를 실행할 수 없으므로 C:\Users\korea\AppData\Roaming\npm\eas.ps1 파일을 로드할 수 없습니다. 자세한 내용은 about_Execution_Policies(https://go.microsoft.com/fwlink/?LinkID=135170)를 참조하십시오. 위치 줄:1 문자:1
+ ~~~
  + CategoryInfo          : 보안 오류: (:) [], PSSecurityException
  + FullyQualifiedErrorId : UnauthorizedAccess

보안 정책때문에 에러가 난거라 정책 바꿔주면 해결 됨.
아래 링크 참고해서 해결 (관리자 모드로 해야됨) 
https://oyeahhh.tistory.com/170  