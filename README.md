<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>나만의 채팅</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="main-container">
        <!-- Chat List -->
        <div class="chat-list" id="chatList">
            <div class="chat-room" data-room="1">
                <span class="title">가까운 사람</span>
                
            </div>
            <div class="chat-room" data-room="2">
                <span class="title">먼 사람</span>
                
            </div>
        </div>

        <!-- Chat Container -->
        <div class="chat-container" id="chatContainer">
            <div class="back-button" id="backButton">뒤로가기</div>
            <div class="chat-window" id="chatWindow">
                <div class="drag-distance" id="dragDistance">거리: 0</div>
                <!-- 채팅 메시지가 표시될 영역 -->
                <div id="specialMessage" class="special-message"></div> <!-- 친밀도에 따른 메시지 -->
            </div>
            <div class="input-container">
                <input type="text" id="chatInput" placeholder="메시지를 입력하세요...">
                <button id="sendButton">전송</button>
            </div>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
