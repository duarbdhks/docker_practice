
Usage:	docker exec [OPTIONS] CONTAINER COMMAND [ARG...]

실행중인 컨테이너에서 명령 실행

옵션 :
  -d, --detach 분리 모드 : 백그라운드에서 명령 실행
      --detach-keys string a를 분리하기위한 키 순서를 겹쳐 쓰십시오.
                             컨테이너
  -e, --env list 환경 변수 설정
  -i, --interactive 접속되어 있지 않아도 STDIN을 열어 둔다.
      --privileged 명령에 확장 권한을 부여하십시오.
  -t, --tty 가상 TTY를 할당합니다.
  -u, --user string 사용자 이름 또는 UID (형식 :
                             <name | uid> [: <group | gid>])
  -w, --workdir string 컨테이너 내부 작업 디렉토리