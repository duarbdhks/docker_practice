
Usage:	docker logs [OPTIONS] CONTAINER

컨테이너 로그 가져 오기

옵션 :
      --details 로그에 제공되는 세부 정보 표시
  -f, --follow 로그 출력을 따른다.
      --since string 타임 스탬프 이후의 로그 표시 (예 :
                       2013-01-02T13 : 23 : 37) 또는 상대 (예 : 42m, 42minutes)
      --tail string 로그 끝에서 표시 할 줄 수
                       (기본값은 "all")
  -t, --timestamps 타임 스탬프를 보여준다.
      --until string 타임 스탬프 이전에 로그를 표시합니다 (예 : 2013-01-02T13 : 23 : 37) 또는 상대 (예 : 42m, 42minutes)