---
layout: post
title: "Softsquared 1주차 과제-info.plist 속성 조사"
date: 2020-03-19 13:31:38 -0900
category: using-odin
author: Rosa
short-description: 소프트퀘어드 첫주차 과제
---
# 소프트스퀘어드(iOS - 7기) 1주차 과제
## swift project info.plist 속성 조사
---
**info.plist : 어플리케이션을 제작, 사용하는데에 필수적인 기본정보 목록**

abc 순으로 정리

1. Accessibility bundle name(String) 
> tts로 읽혀질때의 앱 이름, tts로 잘못 읽힐때를 방지한다.

2. App can run independently of companion iPhone app (Boolean)
> 사용자가  다른 iOS 앱과는 별개로 watchOS앱을 설치하고 사용할 수 있는지 여부값

3. Application Category (String)
> 앱스토어에서 해당 앱의 카테고리를 정하는 값
> - possible values  
>> public.app-category.business  
public.app-category.developer-tools  
public.app-category.education  
public.app-category.entertainment      
public.app-category.finance  
public.app-category.games  
public.app-category.action-games  
public.app-category.adventure-games  
public.app-category.arcade-games  
public.app-category.board-games 등등. 

4. App Encryption Export Compliance Code (String)
>  App Store Connect 에서 제공하는 Export Compliance Code

5. App Store Connect
>  App Store에서 앱을 등록할 때 사용하는 웹기반 툴

6. App group used for document storage (String)
> Document Picker 확장 및 File Provider 확장에서 접근될 수 있는 공유된 컨테이너의 식별자(?)

7. App is only available as a standalone watchOS app (Boolean)
> 앱이 읽기전용인지 나타내는 값

8. App Transport Security Settings ( Dictionary)
> HTTP 연결에서 기본 보안의 변경사항에 대한 값



