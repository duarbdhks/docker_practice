
Usage:	docker create [OPTIONS] IMAGE [COMMAND] [ARG...]

새 컨테이너 만들기

옵션 :
      --add-host list
                맞춤 호스트 - IP 매핑 추가 (호스트 : ip)
  -a, --attach list
                STDIN, STDOUT 또는 STDERR에 연결
      --blkio-weight uint16
                블록 IO (상대 중량), 10
                및 1000 또는 0으로 설정하면 비활성화 (기본값 0)
      --blkio-weight-device 목록
                IO 중량 차단 (상대 기기
                무게) (기본값 [])
      --cap-add 목록
                Linux 기능 추가
      --cap-drop list
                Linux 기능 중단
      --cgroup-parent string
                컨테이너의 선택적 부모 cgroup
      --cidfile 문자열
                컨테이너 ID를 파일에 씁니다.
      --cpu-period int
                CPU CFS 제한 (완전히 공정한
                스케줄러) 기간
      --cpu-quota int
                CPU CFS 제한 (완전히 공정한
                스케줄러) 할당량
      --cpu-rt-period int
                마이크로 초 단위로 CPU 실시간 기간 제한
      --cpu-rt-runtime int
                마이크로 초 단위로 CPU 실시간 런타임 제한
  -c, --cpu-shares int
                CPU 점유율 (상대적 가중치)
      --cpus 십진수
                CPU 수
      --cpuset-cpus 문자열
                실행을 허용하는 CPU (0-3, 0,1)
      --cpuset-mems 문자열
                실행을 허용 할 MEM (0-3, 0,1)
      - 장치 목록
                컨테이너에 호스트 장치 추가
      --device-cgroup-rule 목록
                허용 된 cgroup에 규칙 추가
                장치 목록
      --device-read-bps list
                읽기 속도 (초당 바이트 수) 제한
                장치 (기본값 [])
      --device-read-iops list
                a에서 읽기 속도 (초당 IO) 제한
                장치 (기본 [])
      --device-write-bps list
                쓰기 속도 (초당 바이트 수) 제한
                장치 (기본값 [])
      --device-write-iops list
                쓰기 속도 (초당 IO)를
                장치 (기본 [])
      --disable-content-trust
                이미지 확인 건너 뛰기 (기본값은 true)
      --dns list
                사용자 지정 DNS 서버 설정
      --dns-option list
                DNS 옵션 설정
      - DNS 검색 목록
                사용자 지정 DNS 검색 도메인 설정
      엔트리 포인트 문자열
                ENTRYPOINT의 기본 ENTRYPOINT를 덮어 씁니다.
                영상
  -e, --env list
                환경 변수 설정
      --env-file list
                환경 변수 파일에서 읽기
      --expose 목록
                포트 또는 포트 범위 노출
      --group-add리스트
                가입 할 그룹을 추가하십시오.
      --health-cmd 문자열
                건강을 확인하기 위해 달리는 명령
      - 건강 간격 기간
                수표를 실행하는 시간
                (ms | s | m | h) (기본값 0)
      - 건강 - 재시도 int
                보고에 연속적으로 실패
                건강에 해로운
      - 건강 시작 기간
                컨테이너 시작 시간
                시작하기 전에 초기화
                건강 - 재시도 카운트 다운 (ms | s | m | h)
                (기본값 0)
      - 건강 타임 아웃 기간
                하나의 수표를 허용하는 최대 시간
                (ms | s | m | h) (기본값 0)
      --도움
                인쇄 사용
  -h, --hostname 문자열
                컨테이너 호스트 이름
      - 시작
                컨테이너 내부에서 init을 실행합니다.
                신호를 전달하고 프로세스를 거듭나 다.
  -i, --interactive
                STDIN을 붙이지 않아도 열어 두십시오.
      --ip 문자열
                IPv4 주소 (예 : 172.30.100.104)
      --ip6 문자열
                IPv6 주소 (예 : 2001 : db8 :: 33)
      --ipc 문자열
                사용할 IPC 모드
      - 분리 문자열
                컨테이너 격리 기술
      - 커널 - 메모리 바이트
                커널 메모리 제한
  -l, --label list
                컨테이너에 메타 데이터 설정
      --label-file list
                레이블로 구분 된 파일을 읽습니다.
      - 링크 목록
                다른 컨테이너에 링크 추가
      --link-local-ip list
                컨테이너 IPv4 / IPv6 링크 로컬 주소
      --log-driver 문자열
                컨테이너에 대한 로깅 드라이버
      --log-opt list
                로그 드라이버 옵션
      --mac-address 문자열
                컨테이너 MAC 주소 (예 :
                92 : d0 : c6 ​​: 0a : 29 : 33)
  -m, - 메모리 바이트
                메모리 제한
      - 메모리 - 예약 바이트
                메모리 소프트 한계
      - 메모리 스왑 바이트
                스왑 한도가 메모리 + 스왑과 같습니다.
                무제한 교환을 가능하게하는 '-1'
      - 메모리 스왑 성 int
                컨테이너 메모리 스왑 (0 ~
                100) (기본값 -1)
      - 마운트 마운트
                컨테이너에 파일 시스템 마운트를 연결하십시오.
      - 이름 문자열
                컨테이너에 이름 지정
      - 네트워크 문자열
                컨테이너를 네트워크에 연결
                (기본값 "default")
      --network-alias 목록
                컨테이너에 대한 네트워크 범위 별명 추가
      - 건강 검진 안함
                컨테이너가 지정한 HEALTHCHECK를 비활성화하십시오.
      - oom-kill-disable
                OOM 킬러 사용 안 함
      --oom-score-adj int
                호스트의 OOM 환경 설정 조정 (-1000 - 1000)
      --pid 문자열
                사용할 PID 네임 스페이스
      --pids-limit int
                컨테이너 pids 한도 조정 (-1로 설정
                제한 없는)
      - 특권
                이 컨테이너에 확장 된 권한을 부여하십시오.
  -p, - 공개 목록
                컨테이너의 포트를 호스트에 게시하십시오.
  -P, - 게시 전체
                노출 된 모든 포트를 임의의 포트에 게시하십시오.
      읽기 전용
                컨테이너의 루트 파일 시스템 마운트
                읽기 전용
      --restart 문자열
                적용 할 정책을 다시 시작하십시오.
                컨테이너가 종료합니다 (기본값 "no").
      --rm
                컨테이너를 자동으로 제거합니다.
                끝내다
      - 실행 시간 문자열
                이 컨테이너에 사용하는 런타임
      --security-opt 목록
                보안 옵션
      --shm-size 바이트
                / dev / shm의 크기
      --stop-signal 문자열
                컨테이너를 멈추게하는 신호 (기본값
                "시터 (SIGTERM)")
      --stop-timeout int
                컨테이너를 중지하는 시간 초과 (초)
      --storage-opt list
                컨테이너의 저장소 드라이버 옵션
      --sysctl map
                Sysctl 옵션 (기본 map [])
      --tmpfs list
                tmpfs 디렉토리 마운트
  -t, --tty
                가상 TTY 할당
      - 울림 ulimit
                Ulimit 옵션 (기본값 [])
  -u, --user 문자열
                사용자 이름 또는 UID (형식 :
                <name | uid> [: <group | gid>])
      - 사용자 문자열
                사용할 사용자 네임 스페이스
      - 너트 문자열
                사용할 UTS 네임 스페이스
  -v, - 볼륨 목록
                볼륨 바인드 마운트
      --volume-driver 문자열
                컨테이너 용 선택적 볼륨 드라이버
      --volumes-from list
                지정된 볼륨에서 볼륨 마운트
                컨테이너
  -w, --workdir 문자열
                컨테이너 내부 작업 디렉토리
