### [Java\] Java 설치 및 환경설정



이번 포스팅은 Java(Eclipse 등)를 사용하기 위한 Java 1.8.0 버전을 설치하고 환경변수 설정까지 해보도록 하겠습니다.

(정확한 명칭은 Java SE Development Kit 8로 JDK와 JRE를 포함하여 설치를 진행합니다.)



 

우선 Java 설치 파일을 받기 위해 Java를 제공하는 Oracle 공식 홈페이지인 https://www.oracle.com/ 페이지나 Java 1.8.0 다운로드 페이지인 https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html 로 이동하시면 됩니다.

 



![img](https://blog.kakaocdn.net/dn/k6SlX/btqvKDalXFf/ATNGunMAJqOG0LsMVOiYDK/img.jpg)



 

저는 설치 파일을 바로 받을 수 있도록 두번째 url로 접속하여 위와 같은 페이지에 접속할 수 있었습니다.

 

페이지 하단의 Java SE Development Kit 8u211 박스의 Accept License Agreement 항목을 체크해주시고, 각자 컴퓨터 OS에 해당하는 설치파일을 다운받으시면 됩니다. 저의 경우 Windows 64bit 환경이기에 마지막 항목을 다운받았습니다.



(exe파일을 다운받으실 때 Oracle에 로그인을 해주셔야 합니다. 혹시 없으시다면 빠르게 계정을 만드시고 다운받아주세요.)

 

 



![img](https://blog.kakaocdn.net/dn/bOJIhE/btqvLZDyhfC/oWYzK6rC0K4knm8dISGkG1/img.jpg)



 

컴퓨터에 맞게 Java SE 설치파일을 받으시고 실행하시면 위와 같은 창이 뜨게 됩니다. Next 버튼을 눌러 넘어가주세요.

 

 



![img](https://blog.kakaocdn.net/dn/d65yBV/btqvL1Blfmr/EJrvqxdES8xGVfi1lzZ6W1/img.jpg)



 

저의 경우 jdk의 경로를 디폴트로 하였는데, 만약 경로 변경이 필요하시면 Change 버튼을 선택해 바꿔주시고 Next 버튼을 눌러 다음 단계로 넘어갑니다.

 

 



![img](https://blog.kakaocdn.net/dn/bkF9Ys/btqvLSkktAL/4vL71JhKyZX3mlZhbxjToK/img.jpg)



 

다음은 jre 설치 경로를 설정하는 단계인데, jre 또한 설치 경로를 변경하시면 변경하시고 그렇지 않다면 디폴트로 설정하고 다음 단계로 넘어가시면 됩니다.

 

 



![img](https://blog.kakaocdn.net/dn/bmElVo/btqvLZ4D692/i8ZZlzvEdxhVjE060aZHy0/img.jpg)



 

jre까지 경로를 지정해주면 위와 같은 상태바가 뜨게 되는데, 잠깐동안 기다려주시면 됩니다.

 

 



![img](https://blog.kakaocdn.net/dn/645y7/btqvLRMvmGs/OHiIoZ9pTYKhMHdQU3b0P0/img.jpg)



 

Java SE가 정상적으로 설치되었다는 창이 뜨면 Java SE의 설치는 완료 된 것입니다. 

 



![img](https://blog.kakaocdn.net/dn/kOP7D/btqvL9FU4bG/C7vTQId9KrTSvxCfU2BX41/img.jpg)



 

우선 Java SE가 설치된 경로에 jdk와 jre 모두 잘 설치 되었는지 확인해주시고, 경로를 확인해주세요. 해당 경로를 통해 환경 변수를 설정해야하기에 복사해두시는 것을 추천드립니다.

 

 



![img](https://blog.kakaocdn.net/dn/beKAjo/btqvMwOpIPE/FHKxbivGxyXt73D3oSZK30/img.jpg)



 

환경변수 편집을 위해 Ctrl+R 키를 눌러 실행창을 띄워주시고, stsdm.cpl 명령어를 입력해주세요.

 

 



![img](https://blog.kakaocdn.net/dn/mC6TF/btqvJKONo25/As9rqW2bkv3jGsPkCjIff0/img.jpg)



 

환경변수 창이 뜨면 하단의 새로 만들기를 눌러 설치한 Java SE의 경로를 잡아줍니다.

 



![img](https://blog.kakaocdn.net/dn/uc19q/btqvJUwSImS/H827KbxWNfWjMHkVKAXrRK/img.jpg)



 

변수 이름에는 **JAVA_HOME** 을, 변수 값에는 전에 확인한 jdk 경로인 **C:\Program Files\Java\jdk1.8.0_211** 를 붙여넣어 줍니다. (경로는 각자가 지정한 jdk 경로를 붙여넣어주시면 됩니다. 제가 넣은 경로는 Java SE를 설치할 때 디폴트로 설정된 경로입니다.) 이후 확인을 눌러 해당 사항을 저장해주세요.

 

 



![img](https://blog.kakaocdn.net/dn/pM22e/btqvJ5SsP7V/okUDOKQscMW6Xpzmyhkl91/img.jpg)



 

환경 변수 창으로 돌아가면 시스템 변수에 JAVA_HOME이라는 새 변수가 입력된 것을 확인할 수 있습니다.

 

 



![img](https://blog.kakaocdn.net/dn/Ew9tW/btqvLRTgReI/5ONblKosST8fDOiFWKcjW1/img.jpg)



 

다음은 jdk 환경 변수를 설정한 것과 동일하게 시스템 변수를 새로 만들어줍니다. 변수 이름은 **classpath**, 변수 값은 **%classpath%;** 입니다. **(%와 ; 기호와 띄어쓰기에 주의해주세요.)**

 

 



![img](https://blog.kakaocdn.net/dn/b6ZExL/btqvJJWBXrE/rE8r9SkFHG5bVWp8H5kzu1/img.jpg)



 

시스템 변수에 classpath라는 변수가 추가된 것을 확인할 수 있습니다.

 

 



![img](https://blog.kakaocdn.net/dn/brfXMD/btqvJTdFUYR/bHGnHu1kgyccQZ2xnxx3S1/img.jpg)



 

환경 변수 편집 마지막 단계로 시스템 변수에 원래 존재하는 Path 변수를 편집하도록 하겠습니다. 하단의 편집을 선택해 편집창으로 들어가주세요.

 

 



![img](https://blog.kakaocdn.net/dn/CZEmd/btqvJTkrEaL/5aQXEL6TkmAnW1e5Udgor1/img.jpg)



 

Path 변수 편집창에서 새로 만들기를 선택해주세요.

 

 



![img](https://blog.kakaocdn.net/dn/yAA5S/btqvMw1XevH/kVs3Y94C9YPdC6eWcCxxG1/img.jpg)



 

새로 만들기를 통해 **%JAVA_HOME%\bin** 을 입력해주시고, 해당 변수를 **위로 이동 버튼을 통해 가장 위로 올려주세요.**

 



![img](https://blog.kakaocdn.net/dn/6g4DZ/btqvLSxRO3o/FqiJZTGV7KsHIkEeCADAE1/img.jpg)



 

가장 상위로 올린 모습으로 이와 동일하게 해당 변수가 가장 위로 올라갔으면 확인을 선택해 저장해주세요.

 

 



![img](https://blog.kakaocdn.net/dn/rcjEb/btqvJ550e3h/8G59FtmneSShtj26v70jg0/img.jpg)



 

Path 변수가 위와 같이 변경되었으면 환경 변수 편집창에서 확인을 눌러 저장해주시고 빠져나오시면 됩니다.

 

 

Java SE가 제대로 설치되었는지, 환경 변수가 제대로 잡혔는지 확인하기 위해 **Ctrl + R 로 실행창을 켜서 cmd 라는 명령어를 입력해주세요.**

 



![img](https://blog.kakaocdn.net/dn/064sb/btqvLQ09SMc/CetjYduFm59Ou8sHr3xIs1/img.jpg)



 

cmd를 열면 아래와 같은 cmd 창이 실행됩니다.

 

 



![img](https://blog.kakaocdn.net/dn/3wnnO/btqvL81iAm4/rnZX62QbWkTb2r2IkAv3Ck/img.jpg)



 

cmd 창에 **java -version** 명령어와 **javac -version** 를 입력해서 지금 설치한 Java SE 환경의 버전과 동일한지 위의 사진처럼 체크해 줍니다. 둘 모두 1.8.0_211버전이 출력되는지를 확인해주세요.

 

cmd에서의 출력이 위 사진과 동일하다면 Java SE 1.8.0 버전 설치를 성공적으로 마친 것입니다.

 

 

이번 포스팅에서는 Java SE 설치와 환경설정까지 진행하였습니다.

 

다음 포스팅에서 봐요 :))