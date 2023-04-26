# network_term
 2021 2학년 2학기
 
프로젝트 명 : Network Fighters
작품요약 :
네트워크를 통한 1대1 격투 게임을 완성하였습니다.
각 플레이어의 행동이 매 턴 결과를 만들어내며 그 결과로 각 플레이어 의 체력이 줄어 모든 체력이 준 플레이어가 지게 됩니다.
Server-Client 모델로 완성하였고
서버와 클라이언트 사이의 Stream을 통한 통신 위주로 프로그램이 실행 됩니다
전달하는 메시지의 header 부분에 function들을 정의하여 어떠한 function의 메시지를 받았는지에 따라 각 서버와 클라이언트의 행동이 달라집니다.
세부 내용은 유뷰브 영상과 깃허브에 업로드 하였습니다.
<img width="1279" alt="image" src="https://user-images.githubusercontent.com/60805546/234448502-571c8aed-5034-4235-8ddf-edba56c1b1d7.png">

<img width="1218" alt="image" src="https://user-images.githubusercontent.com/60805546/234448395-20d36ec9-a308-4e55-b95a-0b33ed01d0f6.png">
<img width="1207" alt="image" src="https://user-images.githubusercontent.com/60805546/234448412-9b4bf3a7-1fb4-4529-9385-488ca33c406f.png">

<img width="1021" alt="image" src="https://user-images.githubusercontent.com/60805546/234447897-201cabc1-710e-4e5b-a7fe-e7c5122bd732.png">

# Implementation : 
   - **ClientMainForm.java**   <-- file for clients
   - Function.java
   - GameYesNo.java
   - Lobby.java <-- second frame
   - LoginUi.java <-- first frame
   - MakeNewRoom.java
   - NewPlayerRoom.java
   - PlayerClickPopup.java
   - **Server.java**  <-- run this first
   - WaitRoom.java
  
# Video Description :  https://youtu.be/1l4-oNeiVSM
