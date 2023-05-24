# ✨Open Source SW✨
- __리눅스 명령어__ 중에서 __top, ps, jobs, kill__ 명령어에 대해서 __조사__ 해보자!

<br/>

# 목차
1. 🔴TOP
2. 🟡PS
3. 🟣JOBS
4. 🔵KILL

<br/>
<br/>
<br/>

## 🔴top - Display tasks
>시스템 프로세스/메모리 사용 현황을 실시간으로 출력한다.

<br/>

+ __사용예시__

![image](https://github.com/jinhug/Open-Source-SW/assets/84608707/0a9e5e4a-375a-44e6-8810-ed3e030ea64e)

<br/>
<br/>
<br/>

## 🟡ps - Report a snapshot of current processes
>현재 실행중인 프로세스를 보여주는 명령어.
>>PID , TTY, TIME, CMD  4가지 항목을 보여준다.

<br/>

+ __사용예시__

![image](https://github.com/jinhug/Open-Source-SW/assets/84608707/1b7a4b9c-70e1-44e1-94f2-92740e1aadc7)

+ #### 📒 ps 명령어 옵션
```
- r : 현재 실행중인 프로세서를 보여준다.

- S : 20초 미만의 짧게 잠듦(sleep) 

- D : 디스크 입출력 대기 같은 인터럽트할 수 없는 대기상태.

- T : 일시 정지.

- Z : 좀비(zombi) 프로세서
>좀비(zomb) 상태라는 것은 프로세서가 사라질 때 시그널 처리의 문제로 완전히 소멸되지 못한 상태를 말한다. 
대개는 _ aux 옵션을 많이 사용한다. 이 중 필요한 프로세스에 대한 결과만 선택적으 보고자 한다면 grep 명령을 같이 사용한다.

-e : 모든 프로세스를 보여 준다.

-i : 상세내역을 보여준다.

-ef : 모든 프로세스의 모든정보 표시.
```

<br/>
<br/>
<br/>

## 🟣jobs - List active jobs
>작업이 중지된 상태나 백그라운드로 진행 중인 상태를 표시.

<br/>

+ __사용예시__

![image](https://github.com/jinhug/Open-Source-SW/assets/84608707/1767f6ad-4146-491c-8ebe-657b88a009e7)

<br/>

*xlogo : GUI 시스템에서 제공하는 샘플 프로그램*

<br/>
<br/>
<br/>

## 🔵kill - Send a signal to a process
>프로세스에 종료 시그널을 보낸다.

<br/>

+ ### 📘 kill 명령어 옵션
```
-9 : 강제 종료
-15 : 작업 종료
```

<br/>

+ __사용예시__

1. ps -efc 명령어 입력을 통해 프로세스 정보 표시

![image](https://github.com/jinhug/Open-Source-SW/assets/84608707/245715d3-1802-418d-b2a4-6eb1ef84e034)

<br/>

2. 프로세스마다 고유의 PID 값을 확인

![image](https://github.com/jinhug/Open-Source-SW/assets/84608707/827f75d2-6f01-449d-bee6-3ada6ddc1fe2)

<br/>

3. kill 명령어를 사용해 프로세스에 종료 시그널을 보낸다.

![image](https://github.com/jinhug/Open-Source-SW/assets/84608707/22d92311-885a-433a-82ae-93811ba3fa24)

<br/>
<br/>
<br/>

# 감사합니다!
  학과 : 컴퓨터공학과
  학번 : 20233075
  이름 : 이진형

<br/>
<br/>

[출처:나무지기 블로그](https://m.blog.naver.com/jjune095/221242495248 "블로그로 이동합니다.")
<br/>
[출처:방구석 티스토리](https://m.blog.naver.com/jjune095/221242495248 "티스토로 이동합니다.")

