# meetManagePublic
For documentation and issues with the meetmanage extension


SocketIO API:


Data Format | Events
------------ | -------------
`{"data": String}` | "userLeft", "computerError"
`{"computerName": String, "currentState": Object}` | "registerComputer"
`{"data": {"user": name, "state": bool}}` | "userToggleCamera", "userToggleMute", "toggleExcludeUser"
`{"data": bool \|\| "Username"}`|"toggleFullVideo"
`{"data": {"key": String, "value": any}`|"updateCurrentState"
