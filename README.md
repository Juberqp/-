# 리눅스 명령어들

### -top
현재 OS에 상태 정보를 출력하는 명령어.  

##### 출력되는 정보
> System time : 시스템 현재 시간
> System : 서버가 구동된 시간
> User : 현재 시스템에 연결된 사용자의 수
> Load average : CPU 부하에 관련된 지표

### -ps
현재 실행 중인 프로세스를 보여준다.

##### 옵션
> -e : 현재 사용자뿐만 아니라 다른 사용자들이 구동시킨 모든 프로세스를 보여줌  
> -f : 보다 상세한 정보를 제공 (Full format)  
> -ㅣ : -f 보다 더 상세한 정보를 저공 (Full format)

##### 출력 되는 정보
> UID : 프로세스를 실행한 사용자 ID  
> PID : 프로세스에 부여된 ID  
> C : CPU 사용량 (%)

### -jobs
