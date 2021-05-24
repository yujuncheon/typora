### Git 환경설정



![img](https://blog.kakaocdn.net/dn/lsqlm/btqRqaEk4KF/F4QzowYitEMTStfrQjbCL1/img.png)



**1.** Git이 정상적으로 설치되어있다면 위와 같이 Git Bash가 설치 되어 있을것입니다. GIt Bash를 실행시켜 줍니다.

 

```
$git config --global user.name "Name명" $git config --global user.email "메일주소" 
```

**2.** 깃을 처음 설치하면 Name과 Email이 Null로 되어있을겁니다. 설치받은 GitBash를 열어서 위의 명령어를 쳐 설정을 해줍시다. 

```
$git config --list 
```

**3.** 위의 명령어를 입력하여 Name과 Email이 제대로 들어갔는지 확인할 수 있습니다.