사용법 : docker cp [옵션] CONTAINER : SRC_PATH DEST_PATH | -
docker cp [옵션] SRC_PATH | - CONTAINER : DEST_PATH

컨테이너와 로컬 파일 시스템간에 파일 / 폴더 복사

옵션 :
  -a, --archive 아카이브 모드 (모든 uid / gid 정보를 복사)
  -L, --follow-link SRC_PATH의 심볼 링크를 항상 따르십시오.