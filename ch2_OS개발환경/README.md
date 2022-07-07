### GCC 설치 확인 테스트

- sudo apt-get install gcc-multilib : 64비트 환경에 32비트 컴파일 파일 없어서 설치
    - gcc  -o  test  test.c  -m64
    - gcc  -o  test  test.c  -m32

### NASM

- THe Netwid Assembler
    - 윈도우 리눅스등 다양한 플랫폼 지원하는 어셈블러
    - 32비트 64비트 지원
- `sudo apt-get install nasm`
    - 설치 확인
    - nasm -version

### QEMU

- 오픈소스 프로세서 에뮬레이터 : 다양한 종류의 프로세서를 소프트웨어적으로 구현
- sudo apt-get install qemu
