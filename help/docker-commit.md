사용법 : docker commit [옵션] 컨테이너 [REPOSITORY [: TAG]]

컨테이너의 변경 사항으로 새 이미지 만들기

옵션 :
  -a, --author string 저자 (예 : "John Hannibal Smith
                         <hannibal@a-team.com> ")
  -c, --change list 생성 된 이미지에 Dockerfile 명령을 적용합니다.
  -m, --message string 커밋 메시지
  -p, --pause 커밋 중에 컨테이너를 일시 중지합니다 (기본값은 true).