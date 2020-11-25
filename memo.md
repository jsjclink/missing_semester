# The shell
- shebang: 쉘에게 어떤 인터프리터를 쓸 지 첫번째 줄에서 알려주는거
  - #!/usr/local/bin/python 을 첫줄에 쓰면 python example.py이 아니라 ./example.py로 실행 할 수 있음
  - #!/usr/bin/env python [설명: 24:40](https://youtu.be/kgII-YWo3Zw) 
# Shell Tools and Scripting
- Desktop 에 있는 모든 파일 밑 폴더 특정 폴더에 넣기
  - Desktop:~$ mv $(ls | grep '[^shell]') shell
  - shell이라는 폴더에 다 넣는거
  - $(안에 shell 명령어) 하면 명령어 결과 list로 나옴 *command substitution*
  - shell에서 기본적으로 사용하는건 와일드카드 문자(정규표현식과 혼동 x)
    - *.sh ex) aaa.sh sbavav.sh zzzzz.sh ...
    - project? ex) project1 project2 ...
    - [globbing](https://mug896.github.io/bash-shell/exp_and_sub/filename_expansion.html)
  - ~~정규표현식 공부좀..~~
  - shellcheck : 문법체크해줌
  - tldr : man 이랑 비슷한데 example 까지 있음 very useful (too long didnt read)
  - find : 원하는 파일, 폴더 찾아줌 
    - find . -name "*.tmp" -exec rm {} \; *.tmp 찾아서 다 삭제
  

# Editors(vim)

# Data Wrangling

# Command-line Environment

# Version Control(Git)

# Debugging and Profiling

# Metaprogramming

# Security and Cryptography

# Potpourri

# 그냥 링크들
[shell sudo apt-get install password](https://twpower.github.io/165-how-to-use-sudo-password-in-shell-script)

