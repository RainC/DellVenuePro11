[Dell Venue Pro 11 5130] Windows 8.1 Manual Format Guide, Written by RainC, DongGyu Kim.

# 0. 이 글은
*  델 베뉴 프로 5130 모델에서 임의로 포맷하는 방법을 안내한 글 입니다.
*  델 베뉴 사용자가 아니더라도 포맷 하는 방법을 알기 위한 일반 사용자들이 쉽게 따라하실 수 있습니다.
*  델 베뉴 제품이 아니고, 램이 4GB 이상이며, 하드디스크가 2TB 이상이신 분이면 64Bit 를 선택해주시고, 적합한 운영체제를 선택하여 진행하시기 바랍니다.
*  작업 진행에 지장이 있으면 "Windows 8.1 설치 방법" 을 검색해보면서 차근 차근 진행하시기 바랍니다.

# 1. Before Installing (설치 전)
![USB](http://www.busyboo.com/wp-content/uploads/small-usb-drive-clipit.jpg)
*  USB 8GB - 2번에서 사용

![iso](http://cdn.blogsdna.com/wp-content/uploads/2011/08/Windows-8-Native-ISO-Support.png)
*  Windows 8.1 32Bit (Not Pro) 설치 이미지 - 2번에서 만듬

![usbhub](http://cdn.instructables.com/FOY/8BOO/GU1UZB5L/FOY8BOOGU1UZB5L.MEDIUM.jpg)

*  USB 허브 (USB 확장 허브) 

# 2. Windows 8.1 32Bit USB 설치 이미지 만들기
```
http://windows.microsoft.com/en-us/windows-8/create-reset-refresh-media
```
*  링크로 들어가서 Create Media 버튼 눌러서 파일 다운로드 후 실행.
*  언어 - 언어 선택
*  Edition - Windows 8.1
*  Arch - x86

# 2-1. 3DP Net 으로 네트워크 드라이버 파일 준비
```
http://www.3dpchip.com/3dpchip/sub/net_kor.html
```
*  2번 작업이 끝나면 하면 되는 작업이며, 3dp net 을 최신 버젼 다운로드를 클릭하여 네트워크 드라이버를 USB 에 미리 받아둡니다 !!!

# 3. Dell Venue 11 Pro BIOS 접근
*  이 작업은 USB 로 부팅하기 위한 절차입니다.
```
종료한 후 다시 켤 때 볼륨 아래 버튼을 누른 상태로 있으면 BIOS 로 접근합니다.
```

# 4. USB 로 부팅 순서 바꿔주기

![DellVenue-BIOS](http://i.imgur.com/vjDBQd9.png)
*  오른쪽에서 USB 이름이 감지 되면 USB를 1순위로 올려줍니다.
*  부팅 순위를 올리는 방법은 화살표 버튼 클릭을 통하여 부팅 순서를 변경할 수 있습니다.
*  부팅 순서 변경이 끝나면 Apply 버튼을 눌러준 후 Exit 를 누르면 변경사항이 저장됩니다.
*  Image from : https://www.youtube.com/watch?v=4Eeh-YCXpEE

# 5. 설치 화면으로 이동
![DellVenue-WindowInstall](http://res1.windows.microsoft.com/resbox/en/6.3/main/b182803f-2d94-413f-b80f-3ef0ce277ecf_16.png)
*  위 이미지와 같이 언어 선택 , 키보드 설정 화면이 나오면 사용자 설정에 맞게 설정 후 다음으로 이동합니다.
*  Image from : [링크](http://windows.microsoft.com/en-us/windows-8/upgrade-from-windows-vista-xp-tutorial)

# 6. 파티션 설정
![Part](http://res1.windows.microsoft.com/resbox/en/6.3/main/6d886e76-7d91-4de2-b93e-ec65d008a72f_15.png)
*  위 이미지처럼 파티션을 정리 후 다음으로 이동
*  Image from : [링크](http://windows.microsoft.com/en-us/windows-8/upgrade-from-windows-vista-xp-tutorial)

# 7. 설치 작업
![inst](http://res2.windows.microsoft.com/resbox/en/6.3/main/0c78aab0-a1b9-41a5-a996-a552daaf4382_15.png)
*  위 이미지가 나오면 설치 진행 중
*  Image from : [링크](http://windows.microsoft.com/en-us/windows-8/upgrade-from-windows-vista-xp-tutorial)

# 8. 개인화 설정
![private](http://res1.windows.microsoft.com/resbox/en/6.3/main/36852da7-5a42-4dde-ae6e-07ea67d49865_11.png)
*  여기서부터는 사용자 입력, 색상 설정 등등 절차를 거치고 모든 설정이 끝나면 윈도우 포맷이 완료됩니다.

# 9. 인터넷 연결 (Wi-Fi Connect)
*  3DP Net 사용
*  2번에서 준비한 파일을 실행하여 네트워크 드라이버를 설치합니다.
*  인터넷에 연결합니다.

# 9. 드라이버 설치
```
http://www.dell.com/support/article/us/en/19/SLN179161
```
*  링크로 들어가서 드라이버 설치 가이드를 참고하시기 바랍니다.
*  델 베뉴 프로 전용 링크이기 때문에, 다른 사용자는 [링크](http://www.3dpchip.com/3dp/chip_down_kor.php)에서 최신 버젼 다운로드 후 드라이버 설치 진행을 하시기 바랍니다.


# 10. 마칩니다. 읽어주셔서 감사합니다.
*  Pull Request 받습니다.
