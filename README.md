# knowhow

### 즐겨찾기 

1. 파일내용검색

현재 위치에서 하위디 렉토리까지 키워드가 포함된 파일 검색

```
find . -name "*.ini" | xargs grep abc
```

2. Screen
```
screen -list   # 이전에 작업했었던 screen 리스트가 있으면 세션명과 함께 리스트를 보여줍니다
```

```
screen -r session_name # 이전에 세션이 있을 경우 -r 다음에 오는 세션명으로 이전 작업을 불러옵니다.
```

screen command options
```
Ctrl-a, c : (create) 새로운 쉘이 생기면서 그 쉘로 이동
Ctrl-a, a : 바로 전 창으로 이동
Ctrl-a, n : (next) 다음 창으로 이동
Ctrl-a, p : (previous) 이전 창으로 이동
Ctrl-a, 숫자 : 숫자에 해당하는 창으로 이동
Ctrl-a, ' : 창번호 또는 창이름으로 이동 ( ' => 싱글 쿼테이션 )
Ctrl-a, " : 창번호를 보여준다. ( " => 더블 쿼테이션 )
Ctrl-a, A : 현재 창의 title을 수정
Ctrl-a, w : 창 리스트 보여주기
Ctrl-a, esc : Copy 모드로 전환. Copy 모드에서는 vi의 이동키로 이동을 할 수 있다.
Crtl-a, [ 커서 이동을 할 수 있고 특정 블럭을 복사하는 기능으로 사용한다.
먼저 시작 위치에서 space 바를 누르고 끝 위치에서 space 바를 누르면 해당 부분이 buffer로 복사된다.
Ctrl-a, ] : buffer의 내용을 stdin으로 쏟아 넣는다.
이 기능은 vi의 입력모드에서 사용하면 유용하다.
Ctrl-a, :(콜론) : 명령행 모드로 전환
Ctrl-a, d : (detach) 현재 작업을 유지하면서 screen 세션에서 빠져나옴
세션이 종료 되지 않습니다.
Ctrl-a, x : lock screen
아래 부분은 창을 나눠서 사용하는 명령입니다.
Ctrl-a, S : (split) 창을 나눔 (region)
Ctrl-a, Tab : 다른 region으로 이동
Ctrl-a, Q : 현재 region을 제외한 나머지 숨기기
```

```
exit  # session exit
```
