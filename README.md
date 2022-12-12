### 1. JDK 설치
jdk-8u162-windows-x64.exe    		

2.0  \hybridapp 디렉토리 만들기
>cd \
>md hybridapp

### 2. 아파치 앤트 설치
c:\HybridApp\폴더에 apache-ant-1.9.16-bin.zip  다운로드 
알아서 풀기

### 3. Gradle 설치
c:\HybridApp\폴더에 gradle-3.5.zip 다운로드
알아서 풀기

### 4. 안드로이드 플랫폼 패키지 추가 설치
#### Tools
-Android SDK Tools    
-Android SDK Platfor-tools    
-Android SDK Build-tools    

#### Android R(Api 29, R preview)
-SDK Platform Android R Preview    
-Google Play Intel x86 Atom_64_System Image    
-Google APIs intel x86 Atom_64_System Image    
#### Extra
-Android Support Repository    
-Android Auto Desktop head unit emulator    
-Android auto API simulator    
-Google Repository    
-Google USB Driver    
-Google Play Services    
-Android SDK Command-line Tools    
-Intel x86 Emulator Accelerator(HAXM installer)    

### 5. 환경 변수 설정
JAVA_HOME     	
c:\progrqm files\java\jdk1.8--
ANDROID_SDK_ROOT    C:\Users\608\AppData\Local\Android\android-sdk
GRADLE_HOME    C:\gradle-3.5

#### Path 
%JAVA_HOME%\bin;    
%ANDROID_HOME%\tools    
%ANDROID_HOME%\platform-tools    
%ANDROID_HOME%\build-tools    
%ANDROID_HOME%\cmdline-tools\latest\bin    
%ANDROID_HOME\emulator    
%GRADLE_HOME%\bin    
c:\HybridApp\apace-ant-1.9.16\bin    

### 6. Node.js 설치
"node js 설치" 검색 후 다운로드
>node -v
>npm -v
>npm update -g

### 7. 코르도바 설치
>npm install -g phonegap
>npm install -g cordova
>cordova -v
>npm update -g phonegap
>npm update -g cordova

### 8. 안드로이드 스튜디오 설치

안드로이드 코르도바 앱 만들기
>mkdir \HybridProject
>cd \HybridProject
>cordova create test2 com.example.test testApp2 -d
>cd test
>dir
>dir platform
>cordova platform add android
>dir platform

### 9. 안드로이드 스튜디오 build.gradle(:app)

-android 안에
packagingOptions {

        exclude 'META-INF/DEPENDENCIES.txt'

        exclude 'META-INF/LICENSE.txt'

        exclude 'META-INF/NOTICE.txt'

        exclude 'META-INF/NOTICE'

        exclude 'META-INF/LICENSE'

        exclude 'META-INF/DEPENDENCIES'

        exclude 'META-INF/notice.txt'

        exclude 'META-INF/license.txt'

        exclude 'META-INF/dependencies.txt'

        exclude 'META-INF/LGPL2.1'

    }

### 10. AndroidManifest.xml
-application 안에
android:largeHeap="true" 넣기

### 11. C:\Users\[사용자명]\.android 내에 있는 debug.keystore파일 삭제
(삭제가 되지 않을 경우에는 Ctrl+Alt+Del => 작업관리자에서
해당 프로세스 작업 끝내기 후에 삭제)


### 12. AVD  실행 혹은 스마트폰 컴과 연결
>cordova run android --list
>cordova emulate android
  (에뮬레이터에 실행)
>cordova run android
  (기기에 실행)
  
  
# 나의 포트폴리오 앱페이지 



# 코르도바실행화면
<img src="https://user-images.githubusercontent.com/96104937/207129147-d41a13ad-edf0-4103-952a-da0f87821536.PNG" width="20%"> <img src="https://user-images.githubusercontent.com/96104937/207129160-2993578f-a2c3-4fdf-87c6-954591032e2d.PNG" width="20%">
<img src="https://user-images.githubusercontent.com/96104937/207129172-99684f76-60b1-45da-b6a1-995311ef40fe.PNG" width="20%"> <img src="https://user-images.githubusercontent.com/96104937/207129192-a13ef171-1add-4276-9a2f-8fb555c3033e.PNG" width="20%">



# 포트폴리오 웹페이지
<img src="https://user-images.githubusercontent.com/96104937/207130387-7a6cdf63-bfae-4b1d-a5e8-201f561b95ad.PNG" width="90%">
<img src="https://user-images.githubusercontent.com/96104937/207130390-47525016-466c-4bc1-94f9-037493caebf8.PNG" width="90%">
<img src="https://user-images.githubusercontent.com/96104937/207130394-df7af409-54a3-47ca-9e66-149362dc98ca.PNG" width="90%">
<img src="https://user-images.githubusercontent.com/96104937/207130395-e0e61e6a-7ac4-4d32-a960-336ee968b11a.PNG" width="90%">


