
Usage:	docker update [OPTIONS] CONTAINER [CONTAINER...]

하나 이상의 컨테이너 구성 업데이트

옵션 :
      --blkio-weight uint16 IO (상대적 가중치) 차단, 10
                                   및 1000 또는 0으로 설정하면 비활성화 (기본값 0)
      --cpu-period int CPU CFS를 제한합니다 (완전히 공정합니다.)
                                   스케줄러) 기간
      --cpu-quota int CPU CFS를 완전히 제한합니다.
                                   스케줄러) 할당량
      --cpu-rt-period int CPU 실시간 기간을
                                   마이크로 초
      --cpu-rt-runtime int CPU 실시간 런타임을에서 제한합니다.
                                   마이크로 초
  -c, --cpu-shares int CPU 공유 (상대적 가중치)
      --cpus decimal CPU 수
      --cpuset-cpus string 실행을 허용 할 CPU (0-3, 0,1)
      --cpuset-mems string 실행을 허용 할 MEM (0-3, 0,1)
      --kernel-memory bytes 커널 메모리 제한
  -m, --ememory bytes 메모리 제한
      - 메모리 - 예약 바이트 메모리 소프트 한계
      --memory-swap bytes 스왑 한도가 메모리 + 스왑과 같습니다 :
                                   무제한 교환을 가능하게하는 '-1'
      --restart string 정책을 다시 시작할 때 적용 할 정책입니다.
                                   컨테이너 출구