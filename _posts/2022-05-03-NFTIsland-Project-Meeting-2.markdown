---
layout: post
title:  "NFTIsland Project Meeting 2"
date:   2022-05-03 09:56:00 +0900
categories: 
---
미팅 날짜: 2022년 4월 30일

**회의 내용**
1. 클라이톤 KAS 스터디 할 것
2. 화면 구성도 (설계서) 작성
3. 앱명 정하기

**스터디**
1. 크로스 플랫폼의 원리
Flutter가 각 OS 위에 올라간다. Flutter의 경우 Android와 iOS용 코드로 변환(번역) 해준다. (요즘은 Web도 가능하다.) 즉, 하나의 언어로 개발하므로 개발 속도가 빠르다.
2. Flutter 개발을 할 때 iOS language는 무조건 Swift를 선택해야 한다. Object-C는 현재 지원하지 않는다.
3. 우선 Platforms는 Android만 체크하자. iOS는 Mac이 있어야 개발 가능하다. (iOS를 개발하려면 Xcode가 필요한데 이 프로그램은 Mac에서만 실행이 가능하다.)
4. pubspec.yaml 이 파일은 매우 중요하다.
5. https://pub.dev/ 에서 필요한 package가 있는지 확인해보자. 직접 개발하려고 하지 말자. Apple이나 Kakao에서도 하나의 App을 만들기 위해 수십에서 수백개의 Package를 가져다가 사용하는 경우가 대부분이다. 
6. StatefulWidget은 동적인 동작이 필요할 때 사용한다. 동적인 App은 상태를 Monitoring 해야 하는데 이는 State가 담당한다.
7. 코드 정렬할 때는 Ctrl + Alt + L를 누르면 된다.
8. setState() : 변경된 변수들을 실제로 화면에 적용할 때 사용한다. 
```
setState((){
   test = 'Off';
   _color = Colors.amber;
});
```
