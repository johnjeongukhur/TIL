# 20220330

## 🔑 키워드
```
#20220330 #회고 #메모리관리 #메모리누수 #Xcode_Memory_Graph_Debugger
``` 

## Todo   
✅ - Done   
🟧 - Proceeding   
⬜ - To do   
```   
🟧 이론으로만 알아오던 RC(Reference Counting) XCode Memory Graph Debugger로 메모리 누수를 찾고 고쳐보기
```   


## 🏋️‍♀️ 회고
```
앱 테스트 중 이상한 점을 발견하게 되어 Xcode의 'Memory Graph Debugger' 툴을 사용해보았다.
〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️
Tool을 사용했더니 실제로 메모리를 최적화하라는 알림창이 떴고 이걸 해결하기 위해 방법을 찾아보고 있다.
〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️
또한 예상치도 않게 3가지 타입의 메모리 누수가 생겼는데 이를 어떻게 해결할지 고민이다.
〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️

이론으로만 알아오던 Class RC(Reference Counting)를 직접 눈으로 볼 수 있어 신기했다.
〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️
추후 하단의 메모리 누수 고치는 법을 익혀 봐야겠다.
〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️
```

- 참고   
[[번역]iOS: Xcode의 메모리 그래프 디버거로 메모리 누수 식별하기_tucan9389's blog](https://blog.canapio.com/130), [[원본]iOS — Identifying Memory Leaks using the Xcode Memory Graph Debugger](https://zendesk.engineering/ios-identifying-memory-leaks-using-the-xcode-memory-graph-debugger-e84f097b9d15)   
[Everything you need to know about Memory Leaks in iOS](https://ali-akhtar.medium.com/all-about-memory-leaks-in-ios-cdd450d0cc34)   
[Memory Leaks in Swift](https://medium.com/@leandromperez/memory-leaks-in-swift-bfd5f95f3a74)   
   
- 개인 기록노트   
[Memory Graph Debugger_Notion](https://johnjeongukhur.notion.site/XCode-Memory-Management-f1e64160ebd04d0a8507c56e887be4a6)


