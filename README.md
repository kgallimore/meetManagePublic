# meetManagePublic
For documentation and issues with the meetmanage extension


SocketIO API:


Data Format | Events
------------ | -------------
`{"computerName": computerName,"data": "Username"}` | "userLeft", "userJoin"
`{"computerName": computerName,"data": {"user": name, "state": bool}}` | "userToggleCamera", "userToggleMute"
`{"computerName": computerName,"data": false \|\| "Username"}`|"toggleFullVideo"
`{"computerName": computerName,"data": {"user": user, "state": bool}}`|"toggleExcludeUser"
`{ "computerName": computerName,"data": bool}`|"toggleGridView","fullscreenChange","toggleElements","togglePinupGrab","toggleCurtain"
