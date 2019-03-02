
Usage:	docker run [OPTIONS] IMAGE [COMMAND] [ARG...]

새 컨테이너에서 명령 실행

옵션 :
      --add-host list 사용자 정의 호스트 - IP 매핑 추가
                                       (호스트 : ip)
  -a, --attach list STDIN, STDOUT 또는 STDERR에 연결합니다.
      --blkio-weight uint16 IO 블록 (상대적 가중치),
                                       10 ~ 1000 또는 0 ~
                                       비활성화 (기본값 0)
      --blkio-weight-device list 블록 IO 가중치 (상대 장치
                                       무게) (기본값 [])
      --cap-add list 리눅스 기능 추가
      --cap-drop list 리눅스 기능을 버린다.
      --cgroup-parent string 선택적 parent cgroup입니다.
                                       컨테이너
      --cidfile string 컨테이너 ID를 파일에 씁니다.
      --cpu-period int CPU CFS를 제한합니다 (완전히 공정합니다.)
                                       스케줄러) 기간
      --cpu-quota int CPU CFS를 완전히 제한합니다.
                                       스케줄러) 할당량
      --cpu-rt-period int CPU 실시간 기간을 다음으로 제한합니다.
                                       마이크로 초
      --cpu-rt-runtime int CPU 실시간 런타임을에서 제한합니다.
                                       마이크로 초
  -c, --cpu-shares int CPU 공유 (상대적 가중치)
      --cpus decimal CPU 수
      --cpuset-cpus string 실행을 허용 할 CPU
                                       (0-3, 0, 1)
      --cpuset-mems string 실행을 허용 할 MEM
                                       (0-3, 0, 1)
  -d, --detach 백그라운드에서 컨테이너를 실행하고
                                       인쇄 컨테이너 ID
      --detach-keys string 키 순서를 겹쳐 쓰십시오.
                                       컨테이너 분리
      --device list 컨테이너에 호스트 장치 추가
      --device-cgroup-rule list 허용 된 cgroup에 규칙을 추가합니다.
                                       장치 목록
      --device-read-bps list 제한 읽기 속도 (초당 바이트 수)
                                       장치에서 (기본값 [])
      --device-read-iops list 제한 읽기 속도 (초당 IO)
                                       장치에서 (기본값 [])
      --device-write-bps list 쓰기 속도 제한 (바이트 당 바이트
                                       두 번째) 장치 (기본값 [])
      --device-write-iops list 쓰기 속도 제한 (IO / 초)
                                       장치에 연결 (기본값 [])
      --disable-content-trust 이미지 확인 건너 뛰기 (기본값은 true)
      --dns list 사용자 정의 DNS 서버 설정
      --dns-option list DNS 옵션 설정
      --dns-search list 사용자 정의 DNS 검색 도메인 설정
      --entrypoint string 기본 ENTRYPOINT를 덮어 씁니다.
                                       이미지
  -e, --env list 환경 변수 설정
      --env-file list 환경 변수 파일에서 읽기
      --expose list 포트 또는 포트 범위를 노출합니다.
      --group-add list 추가 할 그룹을 추가합니다.
      --health-cmd string 건강을 확인하기 위해 실행할 명령입니다.
      - 건강 - 간격 지속 검사가 실행되는 시간
                                       (ms | s | m | h) (기본값 0)
      - 건강 - 재시도 int 연속 실패
                                       건강에 해로운 보고서
      - 건강 - 시작 - 기간 기간 컨테이너가 시작되는 기간
                                       시작하기 전에 초기화
                                       건강 - 재시도 카운트 다운
                                       (ms | s | m | h) (기본값 0)
      --health-timeout duration 하나의 검사를 허용하는 최대 시간
                                       run (ms | s | m | h) (기본값 0)
      --help 인쇄 사용법
  -h, --hostname string 컨테이너 호스트 이름
      --init 컨테이너 내부에서 init을 실행한다.
                                       신호와 수확을 앞당긴다.
                                       프로세스들
  -i, --interactive 접속되어 있지 않아도 STDIN을 열어 둔다.
      --ip 문자열 IPv4 주소 (예 : 172.30.100.104)
      --ip6 문자열 IPv6 주소 (예 : 2001 : db8 :: 33)
      --ipc string 사용할 IPC 모드
      - 격리 문자열 컨테이너 격리 기술
      --kernel-memory bytes 커널 메모리 제한
  -l, --label list 컨테이너에 메타 데이터를 설정합니다.
      --label-file list 레이블로 구분 된 파일을 읽습니다.
      - 링크 목록 다른 컨테이너에 링크 추가
      --link-local-ip list 컨테이너 IPv4 / IPv6 링크 로컬
                                       구애
      --log-driver string 컨테이너에 대한 로깅 드라이버
      --log-opt list 로그 드라이버 옵션
      --mac-address string 컨테이너 MAC 주소 (예 :
                                       92 : d0 : c6 ​​: 0a : 29 : 33)
  -m, --ememory bytes 메모리 제한
      - 메모리 - 예약 바이트 메모리 소프트 한계
      --memory-swap bytes 스왑 한도와 메모리를 더한 값
                                       스왑 : '-1'을 사용하면 무제한 스왑을 사용할 수 있습니다.
      --memory-swappiness int 컨테이너 메모리 swappiness 튜닝
                                       (0 ~ 100) (기본값 -1)
      - 마운트 마운트 파일 시스템 마운트를
                                       컨테이너
      --name string 컨테이너에 이름 지정
      --network string 컨테이너를 네트워크에 연결합니다.
                                       (기본값 "default")
      --network-alias list 네트워크 범위 별 별명을 추가합니다.
                                       컨테이너
      --no-healthcheck 컨테이너 지정을 해제합니다.
                                       건강 체크
      --oom-kill-disable OOM Killer 비활성화
      --oom-score-adj int 호스트의 OOM 환경 설정을 조정합니다 (-1000
                                       ~ 1000)
      --pid 문자열 사용할 PID 네임 스페이스
      --pids-limit int 컨테이너 pids 제한을 조정합니다 (-1
                                       무제한의 경우)
      --privileged 여기에 확장 된 권한을 부여하십시오.
                                       컨테이너
  -p, --publish list 컨테이너의 포트를 공개한다.
                                       주인
  -P, --publish-all 노출 된 모든 포트를에 게시합니다.
                                       무작위 포트
      --read-only 컨테이너의 루트를 마운트합니다.
                                       읽기 전용 파일 시스템
      --restart string 정책을 다시 시작할 때 적용 할 정책입니다.
                                       컨테이너가 종료합니다 (기본값 "no").
      --rm 자동으로 컨테이너를 제거합니다.
                                       그것이 끝날 때
      --runtime string이 컨테이너에 사용할 런타임
      --security-opt list 보안 옵션
      --shm-size bytes / dev / shm의 크기
      --sig-proxy 프록시가
                                       프로세스 (기본값은 true)
      --stop-signal string 컨테이너를 정지시키는 신호
                                       (기본값 "SIGTERM")
      --stop-timeout int a를 멈추게하는 타임 아웃 (초 단위).
                                       컨테이너
      --storage-opt list에 대한 저장소 드라이버 옵션
                                       컨테이너
      --sysctl map Sysctl 옵션 (기본 map [])
      --tmpfs list tmpfs 디렉토리 마운트
  -t, --tty 가상 TTY를 할당합니다.
      --ulimit ulimit Ulimit 옵션 (기본값 [])
  -u, --user string 사용자 이름 또는 UID (형식 :
                                       <name | uid> [: <group | gid>])
      --userns string 사용할 사용자 이름 공간
      - 사용할 문자열 UTS 네임 스페이스
  -v, --volume list 볼륨을 바인드 마운트합니다.
      --volume-driver string 선택적 볼륨 드라이버입니다.
                                       컨테이너
      --volumes-from list 지정된 볼륨에서 볼륨 마운트
                                       컨테이너
  -w, --workdir string 컨테이너 내부 작업 디렉토리
