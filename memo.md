# The shell
- shebang: 쉘에게 어떤 인터프리터를 쓸 지 첫번째 줄에서 알려주는거
  - #!/usr/local/bin/python 을 첫줄에 쓰면 python example.py이 아니라 ./example.py로 실행 할 수 있음 
# Shell Tools and Scripting
- Desktop 에 있는 모든 파일 밑 폴더 특정 폴더에 넣기
  - Desktop:~$ mv $(ls | grep '[^shell]') shell
  - shell이라는 폴더에 다 넣는거
  - $(안에 shell 명령어) 하면 명령어 결과 list로 나옴 *command substitution*
  - shell에서 기본적으로 사용하는건 와일드카드 문자(정규표현식과 혼동 x)
    - *.sh ex) aaa.sh sbavav.sh zzzzz.sh ...
    - project? ex) project1 project2 ...
    - [globbing](https://mug896.github.io/bash-shell/exp_and_sub/filename_expansion.html)
  - 정규표현식 공부좀..

# Editors(vim)

# Data Wrangling

# Command-line Environment

# Version Control(Git)

# Debugging and Profiling

# Metaprogramming

# Security and Cryptography

# Potpourri
