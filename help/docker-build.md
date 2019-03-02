사용법 : 도커 빌드 [옵션] 경로 | URL | -

Dockerfile에서 이미지 만들기

옵션 :
      --add-host list 사용자 정의 호스트 - IP 매핑 추가 (host : ip)
      --build-arg list 빌드 타임 변수 설정
      --cache-from strings 캐시 소스로 고려할 이미지
      --cgroup-parent string 컨테이너의 선택적 부모 cgroup
      --compress gzip을 사용하여 빌드 컨텍스트를 압축합니다.
      --cpu-period int CPU CFS를 제한합니다.
                                스케줄러) 기간
      --cpu-quota int CPU CFS를 완전히 제한합니다.
                                스케줄러) 할당량
  -c, --cpu-shares int CPU 공유 (상대적 가중치)
      --cpuset-cpus string 실행을 허용 할 CPU (0-3, 0,1)
      --cpuset-mems string 실행을 허용 할 MEM (0-3, 0,1)
      --disable-content-trust 이미지 확인 건너 뛰기 (기본값은 true)
  -f, --file string Dockerfile의 이름입니다 (Default is is
                                'PATH / Dockerfile')
      --force-rm 항상 중간 컨테이너를 제거하십시오.
      --iidfile string 이미지 ID를 파일에 씁니다.
      - 격리 문자열 컨테이너 격리 기술
      --label list 이미지의 메타 데이터를 설정합니다.
  -m, --ememory bytes 메모리 제한
      --memory-swap bytes 스왑 한도가 메모리 + 스왑과 같습니다 :
                                무제한 교환을 가능하게하는 '-1'
      --network string RUN의 네트워킹 모드를 설정합니다.
                                빌드 중 지침 (기본 "기본값")
      --no-cache 이미지를 만들 때 캐시를 사용하지 않습니다.
      --pull 항상 새로운 버전의
                                이미지
  -q, --quiet 빌드 출력 및 인쇄 이미지를 억제합니다.
                                성공 ID
      --rm 다음에 중간 컨테이너를 제거합니다.
                                빌드 성공 (기본값은 true)
      --security-opt strings 보안 옵션
      --shm-size bytes / dev / shm의 크기
  -t, --tag list 이름과 옵션으로 태그를
                                '이름 : 태그'형식
      --target string 빌드 할 빌드 단계를 설정합니다.
      --ulimit ulimit Ulimit 옵션 (기본값 [])