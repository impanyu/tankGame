# tankGame
A tank shooting game implemented using WebRTC/javascript/HTML5.All datas between browsers make use of RTCDataChannel(direct P2P, not through server). All animations are drawn on HTML canvas, no extra framework/engine used.Use http to signal between client and server.Server is implemented using node.js.Have several technics to sync the state between two clients,like,the states of tanks,shots.Develop my own algorithm for collision detection, which is key points bump detection.This algorithm is suitable for rectangle collision detection.
