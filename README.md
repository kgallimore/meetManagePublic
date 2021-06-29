# meetManagePublic
For documentation and issues with the meetmanage extension


SocketIO API:

// Data ={
//             "computerName": computerName,
//             "data": "Username"
//         }
socket.on("userLeft", function (data) {})
socket.on("userJoin", function (data) {});

// Data ={
//             "computerName": computerName,
//             "data": {"user": name, "state": bool}
//         }
socket.on("userToggleCamera", function (data) {});
socket.on("userToggleMute", function (data) {});


// Data ={
//             "computerName": computerName,
//             "data": false || "Username"
//         }
socket.on("toggleFullVideo", function (data) {});


// Data ={
//             "computerName": computerName,
//             "data": {"user": user, "state": bool}
//         }
socket.on("toggleExcludeUser", function (data) {});

// Data ={
//             "computerName": computerName,
//             "data": bool
//         }
socket.on("toggleGridView", function (data) {});
socket.on("fullscreenChange", function (data) {});
socket.on("toggleElements", function (data) {});
socket.on("togglePinupGrab", function (data) {});
socket.on("toggleCurtain", function (data) {});
