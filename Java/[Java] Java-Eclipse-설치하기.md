### [Java\] Eclipse 설치하기]



이번 포스팅은 Java언어를 코딩하기 위한 IDE 중 하나인 Eclipse를 설치해보도록 하겠습니다. Eclipse를 설치하고 사용하기 위해서는 Java SE(JDK, JRE)가 필요한데, 이는 이전 포스팅에서 다뤘기에 이번 포스팅에서는 Ecplise 설치만 다루도록 하겠습니다. 혹시 Java SE를 설치하지 않으신 분들은 아래 포스팅을 참고해주시기 바랍니다.

 

[2019/06/01 - [Program/Install\] - [Java] Java 설치 및 환경설정](https://gabii.tistory.com/entry/Java-Java-JDK-설치-및-환경설정)

 

먼저 Java SE가 제대로 설치되어있는지 체크부터 하고 Eclipse 설치를 진행하도록 하겠습니다. Ctrl + R로 실행창을 켜서 cmd라는 명령어를 입력해주세요.

 



![img](https://blog.kakaocdn.net/dn/CAVmm/btqvQE7lYqO/4CYXAxgnkuakYadhfsaKf0/img.jpg)



 

cmd를 열면 아래와 같은 cmd 창이 실행됩니다.

 



![img](https://blog.kakaocdn.net/dn/cK4FrM/btqvNGE3GtL/Z4kGlBk5B1By8wYwelFDwk/img.jpg)



 

cmd 창에 java -version 명령어와 javac -version 명령어를 입력해서 Java SE가 설치되어 있는지를 확인해주세요. 저의 경우 java와 javac 버전 모두 1.8.0_211입니다. Java SE를 설치하는 것 뿐만 아니라 Eclipse를 설치하는데 필요한 Java SE 버전이 필요하기에 이에 유의해 주세요.

 

 

이제 본격적으로 Eclipse를 설치해보도록 하겠습니다. 우선 Eclipse 설치파일을 받기위해 Eclipse 공식 홈페이지인 https://www.eclipse.org/ 로 이동하시면 됩니다.

 



![img](https://blog.kakaocdn.net/dn/cilMwx/btqvPbSnBW3/tirZ9Wj8WFy1FWLCi3pU70/img.jpg)



 

이클립스 홈페이지로 가시면 우측 상단에 Download 버튼이 보이는데 해당 버튼을 눌러주세요.

 

 



![img](https://blog.kakaocdn.net/dn/dpUR2H/btqvRIBqKrt/9kAOkAHllvZFRiBnoO2bj1/img.jpg)



 

이클립스 다운로드로 이동하시면 Get Eclipse IDE 라는 항목이 있는데 Download 64bit를 선택해주시면 됩니다.

 

 



![img](https://blog.kakaocdn.net/dn/mcMue/btqvQDN9jO5/PElhuSm6pPtbqMkT0tsuPk/img.jpg)



 

다운로드 페이지로 이동되어 Download 버튼이 있는데, 이를 선택해주시면 됩니다.

 

 



![img](https://blog.kakaocdn.net/dn/Hls17/btqvP5c57G3/CJLQAiNhxUJD76AUE593d0/img.jpg)



 

이클립스 설치파일 다운로드가 끝나면 위와 같은 installer 화면을 보실 수 있는데, 우측 상단에 떠있는 느낌표를 클릭해주세요.

 

 



![img](https://blog.kakaocdn.net/dn/btGlnu/btqvPK73C3u/7KjcliLFn0PkpIO5JiH9TK/img.jpg)



 

이클립스를 설치하기 전에 인스톨러 자체를 업데이트 해야합니다. 느낌표를 선택하셔서 나오는 가장 위에 있는 UPDATE를 선택해주세요.

 

 



![img](https://blog.kakaocdn.net/dn/bR69GI/btqvRcpeB8u/wUdCaKkqjKPkjOzBtzTukk/img.jpg)



 

업데이트를 위해 라이센스에 동의해주세요.

 

 



![img](https://blog.kakaocdn.net/dn/uJy3A/btqvNij7GqP/mecgrKwjpXtmMFOWb5CkIK/img.jpg)



 

라이센스에 동의하시고 나면 바로 업데이트를 진행합니다.

 

 



![img](https://blog.kakaocdn.net/dn/cNNghz/btqvP46hB83/AzBoSaioR34dlmZZgY4akk/img.jpg)



 

우측 상단에 느낌표가 사라진 것을 확인하시고, Eclipse를 사용하기 위해 Eclipse IDE for Enterprise Java Developers 항목을 선택해주세요.

 

 



![img](https://blog.kakaocdn.net/dn/ecfviN/btqvMI4qslj/8G7Ksv4FBs0oz7XE1oGOO0/img.jpg)



 

설치할 Eclipse IDE 버전과 경로, 컴퓨터 비트에 대해 선택하시고 Install 버튼을 눌러주시면 설치가 시작됩니다.

 

 



![img](https://blog.kakaocdn.net/dn/bjnsa9/btqvPaeUNLB/2nPDU0ZmF9jos4uu6XkHnk/img.jpg)



 

Install 버튼을 누르면 위와 같은 화면이 뜨면서 설치가 진행됩니다.

 

 



![img](https://blog.kakaocdn.net/dn/bwG2lZ/btqvPa0dYzr/Lg8DziyP65AwkwFgSqA2J0/img.jpg)



 

만약 설치 도중 설치 화면 상단에 위 사진과 같은 주황색 창이 떠도 신경쓰지 마시고 놔두면 알아서 진행됩니다. 저의 경우 설치에 5분 ~ 10분정도 소요되었습니다. 컴퓨터 사양 및 네트워크 환경에 따라 설치 소요시간은 다를 수 있으니 참고 바랍니다.

 

 



![img](https://blog.kakaocdn.net/dn/sWnNC/btqvRaLHTok/bWGKIWvBylbGQaKzV5teYK/img.jpg)



 

설치가 완료된 화면입니다. Install 버튼 대신 Launch 버튼이 생겼습니다. 이클립스를 설치하였기에 테스트하기 위해서 Launch 버튼을 눌러주세요.

 

 



![img](https://blog.kakaocdn.net/dn/8Pa0l/btqvRHidI4Z/gnALe33PkEV2pTJ89Njxqk/img.jpg)



 

이클립스가 정상적으로 설치되었다면 위와 같은 이클립스 로딩창이 나타나게 됩니다.

 

 



![img](https://blog.kakaocdn.net/dn/E3uk0/btqvP6QxWAq/Ic3cdEunLOfi9aTMXc1XN0/img.jpg)



 

Visual Studio의 C나 C++을 위한 작업공간을 지정하는 것과 동일하게 Java를 위한 Eclipse는 workspace를 가집니다. 이제부터 프로젝트를 만들면 경로를 바꾸지 않는 한 지금 지정한 workspace에 저장됩니다. 저는 기본 경로로 실행하였는데 경로 변경을 원하시면 Browse를 통해 변경하신 후 Launch 해주시면 됩니다.

 

 



![img](https://blog.kakaocdn.net/dn/kEu19/btqvMIwBWNn/RGm0TIMUFKKpRA7Z3wVdck/img.jpg)



 

Eclipse 설치 후 첫 화면인 Welcome 창인데 저의 경우 하단의 Always show Welcome at start up 체크 박스를 해제하였습니다. 이 화면은 얼마든지 다시 볼 수 있고, 굳이 Welcome 창이 아니더라도 쓸 수 있는 기능들이기에 체크 해제하였습니다.

 

 



![img](https://blog.kakaocdn.net/dn/eb8kQZ/btqvR20KNn9/fWrMNKbecmC9tfYvmQASs0/img.jpg)



 

이제 진짜 Eclipse 첫 화면입니다. Eclipse를 사용하면 이 창에서 코드를 입력하고 출력값을 볼 수 있습니다.

 

 



![img](https://blog.kakaocdn.net/dn/wmD4V/btqvNHjHX6L/AeDeFSC6twKFlydMp4RjY1/img.jpg)



 

첫 자바 코딩과 테스트를 위해서 화면 좌측 상단의 File - New - Other 로 들어가주세요.

 

 



![img](https://blog.kakaocdn.net/dn/bGXfSg/btqvNIpoofC/cLUQBH2Kq79aqKh7ai2FKk/img.jpg)



 

새 창이 하나 뜨는데, 이 창에서 Java Project를 선택하시고 Next를 눌러주세요.

 

 



![img](https://blog.kakaocdn.net/dn/bhPlhA/btqvRIBre2i/nQOIqTRw9BNFODFoWCtKR1/img.jpg)



 

프로젝트 이름은 원하는 것으로 하고 Finish 버튼을 눌러주세요. 만약 다른 경로에 저장하거나 기타 선택 사항이 있으시다면 아래 선택지를 바꾸시면 됩니다.

 

 



![img](https://blog.kakaocdn.net/dn/ben4SY/btqvRbDRtsm/LcP9MQjZGK5pTnmlTmmTv1/img.jpg)



 

Java Perspective를 이용하면 Java를 개발할 때 필요한 창들이 자동으로 배치됩니다. 저는 다른 세팅을 줄이기 위해 Open Perspective로 선택하였습니다. 여기까지 하면 프로젝트 세팅이 끝납니다.

 

 



![img](https://blog.kakaocdn.net/dn/9Ar7q/btqvRIg9HNy/hlBOCXwP7j7U79SsL3NAgk/img.jpg)



 

이제 프로젝트를 만들었으니 코드를 작성하기 위한 Java Class 파일을 만들겠습니다..

 

 



![img](https://blog.kakaocdn.net/dn/JTpzb/btqvRcbIwhd/Ko7Onj5EkxxMllUELS0RKK/img.jpg)



 

좌측 Package Explorer에 src 폴더에서 우측클릭 - New - Class 를 선택해주세요.

 

 



![img](https://blog.kakaocdn.net/dn/d2sOs8/btqvQFkTFIe/HfYR6ZFwWV1CTSQIdiuAyk/img.jpg)



 

만들 클래스 이름을 지정하고 중간의 public static void main(String[] args) 항목을 체크해주세요. main() 을 자동으로 만들어주는 항목입니다. 여기까지 하셨으면 하단의 Finish 로 종료해주세요.

 

 



![img](https://blog.kakaocdn.net/dn/VB9OX/btqvRIuGuzY/QEuCOHPbTonRnK0MkZxQO1/img.jpg)



 

이제 Java 코드를 작성할 준비가 모두 완료되었습니다. 여기까지 하셨다면 위의 사진과 같은 창을 볼 수 있습니다.

 

 



![img](https://blog.kakaocdn.net/dn/b2Nnun/btqvRaybHiz/kcYfpleKoksDrB8gchzwQ0/img.jpg)



 



| 12345 | public class Main {  public static void main(String[] args) {    System.out.println("Hello Java World!");  }} |
| ----- | ------------------------------------------------------------ |
|       |                                                              |

 

C에서의 printf("Hello C World")와 같은 코드를 코드 창에 넣어줍니다. Java 코드는 위의 코드창을 참고해주세요. 코드를 다 작성하셨으면 상단의 Run 버튼 또는 F11 키를 눌러 실행시켜 보겠습니다.

 

 



![img](https://blog.kakaocdn.net/dn/chq6Qf/btqvRbjy84r/Of0WnkwdJVcLHn9CCVzh30/img.jpg)



 

코드를 실행하면 위와 같은 창이 뜨는데, 이는 저장에 대한 알림창으로 항상 저장하기 위해 하단의 Always save resourses before launching 체크박스를 선택하고 OK 해주시면 됩니다.

 

 



![img](https://blog.kakaocdn.net/dn/bMnacZ/btqvRbRr3ZJ/7pDhfqtUgyc9DWSVgd0p7K/img.jpg)



 

자바 실행 결과는 창 하단 콘솔 탭에서 뜹니다. 위 사진과 같이 Hello Java World! 가 콘솔창에 뜬다면 이클립스 설치에 성공한 것입니다.

 

 

이번 포스팅에서는 Java를 코딩할 수 있는 IDE 중 하나인 Eclipse를 설치해보았습니다.

 

모두 고생하셨고 다음 포스팅에서 뵙겠습니당 :))