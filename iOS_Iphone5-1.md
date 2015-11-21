#### Test 51335028e20f43b_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028e20f43b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AAE7D962-43BA-4BA8-95B2-909BB14658B3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/AAE7D962-43BA-4BA8-95B2-909BB14658B3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028e20f43b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028e20f43b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/E38453BB-A733-47E7-AD58-1355E1A5B3F0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52041"
,(lldb)     command script import "/tmp/AAE7D962-43BA-4BA8-95B2-909BB14658B3/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-21 13:28:13.077 ThaliTest[442:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-21 13:28:13.081 ThaliTest[442:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-21 13:28:13.088 ThaliTest[442:60b] Unlimited access to network resources
,2015-11-21 13:28:13.096 ThaliTest[442:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-21 13:28:23.857 ThaliTest[442:60b] Resetting plugins due to page load.
,2015-11-21 13:28:24.656 ThaliTest[442:60b] Finished load of: file:///var/mobile/Applications/E38453BB-A733-47E7-AD58-1355E1A5B3F0/ThaliTest.app/www/index.html
,2015-11-21 13:28:24.835 ThaliTest[442:60b] JXcore Cordova plugin initializing
,2015-11-21 13:28:24.838 ThaliTest[442:6907] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
,Warning: iOS does not support ToggleBluetooth
,We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
,toggleBluetooth - 
Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
toggleWiFi
,my name is : Apple-Iphone5-1_PT759
,attempting to connect to test coordinator
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c,:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c,:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"1000000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"2\"}","devices":3,"addressList":[,]}
,Start now : testSendData.js
stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"2"}, bt-address lenght : 0
,check server
,serverPort is 55093
,2015-11-21 13:38:22.524 ThaliTest[442:6907] jxcore: startBroadcasting
,2015-11-21 13:38:22.532 ThaliTest[442:6907] server: starting Apple-Iphone5-1_PT759.cZHSYA==
,2015-11-21 13:38:22.534 ThaliTest[442:6907] multipeer session: start timer: 0x1b783400
2015-11-21 13:38:22.535 ThaliTest[442:6907] THEMultipeerSession initialized peer Apple-Iphone5-1_PT759
2015-11-21 13:38:22.536 ThaliTest[442:6907] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-11-21T12:38:22.538Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-21 13:38:23.525 ThaliTest[442:60b] client: found peer: Apple-IpadAir2-1_PT5427.N/zz4w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5427.N/zz4w==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21T12:38:23.530Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5427.N/zz4w==
2015-11-21T12:38:23.530Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5427.N/zz4w==
2015-11-21T12:38:23.530Z SendDataConnector.js: do connect now
2015-11-21 13:38:23.531 ThaliTest[442:6907] jxcore: connect Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:23.532 ThaliTest[442:6907] client session: connect
,2015-11-21 13:38:23.533 ThaliTest[442:6907] client session: stateChange:0->1 Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:23.813 ThaliTest[442:60b] client: found peer: Apple-Iphone6-1_PT8382.HGUadg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8382.HGUadg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-21 13:38:24.190 ThaliTest[442:60b] multipeer session: reset timer
2015-11-21 13:38:24.191 ThaliTest[442:60b] multipeer session: stop timer
2015-11-21 13:38:24.192 ThaliTest[442:60b] multipeer session: start timer: 0x1b783400
2015-11-21 13:38:24.193 ThaliTest[442:60b] server session: connect
2015-11-21 13:38:24.193 ThaliTest[442:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:24.198 ThaliTest[442:60b] server: accepting invitation Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:25.629 ThaliTest[442:60b] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8264./5qd6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-21 13:38:26.381 ThaliTest[442:7433] client session: connected
2015-11-21 13:38:26.383 ThaliTest[442:7433] client session: stateChange:1->2 Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:26.387 ThaliTest[442:7433] client session: fireConnectCallback: Apple-IpadAir2-1_PT5427.N/zz4w==
2015-11-21 13:38:26.387 ThaliTest[442:7433] jxcore: connect: success
,2015-11-21T12:38:26.389Z SendDataConnector.js: CLIENT connected to 55096, error: null
2015-11-21T12:38:26.389Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 13:38:26.391 ThaliTest[442:60b] client: relay established
,2015-11-21 13:38:26.392 ThaliTest[442:60b] client: new accepted socket: 0x1b799af0
,2015-11-21T12:38:26.404Z SendDataConnector.js: CLIENT now sending 1000000 bytes of data
,2015-11-21 13:38:27.043 ThaliTest[442:7433] server session: connected
2015-11-21 13:38:27.043 ThaliTest[442:7433] server session: stateChange:1->2 Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:27.051 ThaliTest[442:60b] server relay: connected (to port: 55093)
,2015-11-21T12:38:27.538Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T12:38:31.283Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-21T12:38:31.283Z SendDataTCPServer.js: TCP/IP server has received 14336 bytes of data
,2015-11-21T12:38:33.624Z SendDataConnector.js: CLIENT is data received : 600000
2015-11-21T12:38:33.625Z SendDataTCPServer.js: TCP/IP server has received 18432 bytes of data
,2015-11-21T12:38:34.624Z SendDataConnector.js: CLIENT is data received : 800000
2015-11-21T12:38:34.625Z SendDataTCPServer.js: TCP/IP server has received 22528 bytes of data
,2015-11-21T12:38:34.640Z SendDataTCPServer.js: TCP/IP server has received 77824 bytes of data
,2015-11-21T12:38:34.655Z SendDataTCPServer.js: TCP/IP server has received 176128 bytes of data
,2015-11-21T12:38:34.675Z SendDataTCPServer.js: TCP/IP server has received 256000 bytes of data
,2015-11-21T12:38:34.680Z SendDataConnector.js: CLIENT is data received : 820000
,2015-11-21 13:38:34.684 ThaliTest[442:60b] multipeer session: reset timer
2015-11-21 13:38:34.685 ThaliTest[442:60b] multipeer session: stop timer
2015-11-21 13:38:34.685 ThaliTest[442:60b] multipeer session: start timer: 0x1b783400
,2015-11-21 13:38:34.686 ThaliTest[442:60b] server session: connect
2015-11-21 13:38:34.687 ThaliTest[442:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT8264
,2015-11-21 13:38:34.694 ThaliTest[442:60b] server: accepting invitation Apple-Iphone5s-1_PT8264
,2015-11-21T12:38:34.697Z SendDataTCPServer.js: TCP/IP server has received 387072 bytes of data
,2015-11-21T12:38:34.701Z SendDataTCPServer.js: TCP/IP server has received 440320 bytes of data
,2015-11-21T12:38:34.704Z SendDataConnector.js: CLIENT is data received : 830000
,2015-11-21T12:38:34.718Z SendDataTCPServer.js: TCP/IP server has received 571392 bytes of data
,2015-11-21T12:38:34.722Z SendDataTCPServer.js: TCP/IP server has received 626688 bytes of data
,2015-11-21T12:38:34.738Z SendDataTCPServer.js: TCP/IP server has received 757760 bytes of data
,2015-11-21T12:38:34.741Z SendDataTCPServer.js: TCP/IP server has received 884736 bytes of data
,2015-11-21T12:38:34.756Z SendDataTCPServer.js: TCP/IP server has received 1000002 bytes of data
,2015-11-21 13:38:35.202 ThaliTest[442:60b] multipeer session: reset timer
,2015-11-21 13:38:35.202 ThaliTest[442:60b] multipeer session: stop timer
2015-11-21 13:38:35.203 ThaliTest[442:60b] multipeer session: start timer: 0x1b783400
,2015-11-21 13:38:35.204 ThaliTest[442:60b] server session: connect
,2015-11-21 13:38:35.204 ThaliTest[442:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8382
,2015-11-21 13:38:35.208 ThaliTest[442:60b] server: accepting invitation Apple-Iphone6-1_PT8382
,2015-11-21T12:38:35.225Z SendDataConnector.js: CLIENT is data received : 850000
,2015-11-21T12:38:35.272Z SendDataConnector.js: CLIENT is data received : 860000
,2015-11-21T12:38:35.330Z SendDataConnector.js: CLIENT is data received : 880000
,2015-11-21T12:38:35.619Z SendDataConnector.js: CLIENT is data received : 890000
,2015-11-21 13:38:35.691 ThaliTest[442:8403] server session: not connected Apple-IpadAir2-1_PT5427
,2015-11-21T12:38:35.731Z SendDataConnector.js: CLIENT is data received : 900000
,2015-11-21T12:38:35.744Z SendDataConnector.js: CLIENT is data received : 930000
,2015-11-21T12:38:36.123Z SendDataConnector.js: CLIENT is data received : 940000
,2015-11-21T12:38:36.137Z SendDataConnector.js: CLIENT is data received : 970000
,2015-11-21T12:38:36.150Z SendDataConnector.js: CLIENT is data received : 1000000
,2015-11-21T12:38:36.150Z SendDataConnector.js: got all data for this round
,2015-11-21T12:38:36.153Z SendDataConnector.js: CLIENT Stop now
2015-11-21T12:38:36.153Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 13:38:36.154 ThaliTest[442:6907] jxcore: disconnect
,2015-11-21 13:38:36.155 ThaliTest[442:6907] client session: disconnectFromPeer: Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:36.156 ThaliTest[442:6907] client session: disconnect
,2015-11-21 13:38:36.156 ThaliTest[442:6907] client session: stateChange:2->0 Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:36.158 ThaliTest[442:6907] jxcore: disconnect: success
2015-11-21T12:38:36.159Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5427.N/zz4w==
---- round done--------
,device[2]: Apple-Iphone6-1_PT8382.HGUadg==
,2015-11-21T12:38:36.161Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8382.HGUadg==
2015-11-21T12:38:36.163Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8382.HGUadg==
2015-11-21T12:38:36.163Z SendDataConnector.js:, do connect now
2015-11-21 13:38:36.163 ThaliTest[442:6907] jxcore: connect Apple-Iphone6-1_PT8382.HGUadg==
,2015-11-21 13:38:36.164 ThaliTest[442:6907] client session: connect
2015-11-21 13:38:36.165 ThaliTest[442:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8382.HGUadg==
,2015-11-21 13:38:37.815 ThaliTest[442:7433] server session: connected
,2015-11-21 13:38:37.817 ThaliTest[442:7433] server session: stateChange:1->2 Apple-Iphone5s-1_PT8264
,2015-11-21T12:38:37.880Z SendDataTCPServer.js: TCP/IP server connected
2015-11-21 13:38:37.880 ThaliTest[442:60b] server relay: connected (to port: 55093)
,2015-11-21 13:38:38.218 ThaliTest[442:7433] server session: connected
,2015-11-21 13:38:38.220 ThaliTest[442:7433] server session: stateChange:1->2 Apple-Iphone6-1_PT8382
,2015-11-21 13:38:38.225 ThaliTest[442:60b] server relay: connected (to port: 55093)
,2015-11-21T12:38:38.235Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T12:38:38.392Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-11-21T12:38:38.405Z SendDataTCPServer.js: TCP/IP server has received 41468 bytes of data
,2015-11-21T12:38:38.419Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-11-21T12:38:38.432Z SendDataTCPServer.js: TCP/IP server has received 111690 bytes of data
,2015-11-21T12:38:38.449Z SendDataTCPServer.js: TCP/IP server has received 153300 bytes of data
,2015-11-21T12:38:38.465Z SendDataTCPServer.js: TCP/IP server has received 177248 bytes of data
,2015-11-21T12:38:38.478Z SendDataTCPServer.js: TCP/IP server has received 192720 bytes of data
,2015-11-21T12:38:38.741Z SendDataTCPServer.js: TCP/IP server has received 226908 bytes of data
,2015-11-21T12:38:38.756Z SendDataTCPServer.js: TCP/IP server has received 260610 bytes of data
,2015-11-21T12:38:38.773Z SendDataTCPServer.js: TCP/IP server has received 279468 bytes of data
2015-11-21T12:38:38.775Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-11-21T12:38:38.788Z SendDataTCPServer.js: TCP/IP server has received 282510 bytes of data
2015-11-21T12:38:38.790Z SendDataTCPServer.js: TCP/IP server has received 56372 bytes of data
,2015-11-21T12:38:38.804Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-11-21T12:38:38.817Z SendDataTCPServer.js: TCP/IP server has received 118260 bytes of data
,2015-11-21T12:38:38.831Z SendDataTCPServer.js: TCP/IP server has received 142350 bytes of data
2015-11-21T12:38:38.832Z SendDataTCPServer.js: TCP/IP server has received 289080 bytes of data
,2015-11-21T12:38:38.844Z SendDataTCPServer.js: TCP/IP server has received 166440 bytes of data
,2015-11-21T12:38:38.857Z SendDataTCPServer.js: TCP/IP server has received 186150 bytes of data
,2015-11-21T12:38:38.858Z SendDataTCPServer.js: TCP/IP server has received 313170 bytes of data
,2015-11-21T12:38:38.872Z SendDataTCPServer.js: TCP/IP server has received 225570 bytes of data
,2015-11-21T12:38:38.874Z SendDataTCPServer.js: TCP/IP server has received 315360 bytes of data
,2015-11-21T12:38:38.886Z SendDataTCPServer.js: TCP/IP server has received 317550 bytes of data
,2015-11-21T12:38:38.899Z SendDataTCPServer.js: TCP/IP server has received 348210 bytes of data
,2015-11-21T12:38:38.901Z SendDataTCPServer.js: TCP/IP server has received 227760 bytes of data
,2015-11-21T12:38:38.913Z SendDataTCPServer.js: TCP/IP server has received 367636 bytes of data
,2015-11-21T12:38:38.917Z SendDataTCPServer.js: TCP/IP server has received 236520 bytes of data
,2015-11-21T12:38:38.930Z SendDataTCPServer.js: TCP/IP server has received 378870 bytes of data
,2015-11-21T12:38:38.932Z SendDataTCPServer.js: TCP/IP server has received 271560 bytes of data
,2015-11-21T12:38:38.946Z SendDataTCPServer.js: TCP/IP server has received 411720 bytes of data
,2015-11-21T12:38:38.948Z SendDataTCPServer.js: TCP/IP server has received 280320 bytes of data
,2015-11-21T12:38:38.961Z SendDataTCPServer.js: TCP/IP server has received 427050 bytes of data
,2015-11-21T12:38:38.964Z SendDataTCPServer.js: TCP/IP server has received 302220 bytes of data
,2015-11-21T12:38:38.977Z SendDataTCPServer.js: TCP/IP server has received 442380 bytes of data
,2015-11-21T12:38:38.979Z SendDataTCPServer.js: TCP/IP server has received 310980 bytes of data
,2015-11-21T12:38:38.993Z SendDataTCPServer.js: TCP/IP server has received 470850 bytes of data
,2015-11-21T12:38:38.994Z SendDataTCPServer.js: TCP/IP server has received 317550 bytes of data
,2015-11-21T12:38:39.005Z SendDataTCPServer.js: TCP/IP server has received 475230 bytes of data
,2015-11-21T12:38:39.006Z SendDataTCPServer.js: TCP/IP server has received 356970 bytes of data
,2015-11-21T12:38:39.019Z SendDataTCPServer.js: TCP/IP server has received 389820 bytes of data
,2015-11-21T12:38:39.299Z SendDataTCPServer.js: TCP/IP server has received 501996 bytes of data
,2015-11-21T12:38:39.314Z SendDataTCPServer.js: TCP/IP server has received 529980 bytes of data
,2015-11-21T12:38:39.373Z SendDataTCPServer.js: TCP/IP server has received 557882 bytes of data
,2015-11-21T12:38:39.387Z SendDataTCPServer.js: TCP/IP server has received 582540 bytes of data
,2015-11-21T12:38:39.411Z SendDataTCPServer.js: TCP/IP server has received 584730 bytes of data
,2015-11-21T12:38:39.425Z SendDataTCPServer.js: TCP/IP server has received 595680 bytes of data
,2015-11-21T12:38:39.437Z SendDataTCPServer.js: TCP/IP server has received 615390 bytes of data
,2015-11-21T12:38:39.467Z SendDataTCPServer.js: TCP/IP server has received 444570 bytes of data
,2015-11-21T12:38:39.482Z SendDataTCPServer.js: TCP/IP server has received 457710 bytes of data
,2015-11-21T12:38:39.496Z SendDataTCPServer.js: TCP/IP server has received 486180 bytes of data
2015-11-21T12:38:39.499Z SendDataTCPServer.js: TCP/IP server has received 626340 bytes of data
,2015-11-21T12:38:39.511Z SendDataTCPServer.js: TCP/IP server has received 494940 bytes of data
2015-11-21T12:38:39.513Z SendDataTCPServer.js: TCP/IP server has received 643860 bytes of data
,2015-11-21T12:38:39.526Z SendDataTCPServer.js: TCP/IP server has received 678332 bytes of data
,2015-11-21T12:38:39.539Z SendDataTCPServer.js: TCP/IP server has received 733650 bytes of data
,2015-11-21T12:38:39.788Z SendDataTCPServer.js: TCP/IP server has received 755550 bytes of data
,2015-11-21T12:38:39.835Z SendDataTCPServer.js: TCP/IP server has received 757740 bytes of data
,2015-11-21T12:38:39.847Z SendDataTCPServer.js: TCP/IP server has received 768690 bytes of data
,2015-11-21T12:38:39.859Z SendDataTCPServer.js: TCP/IP server has received 775260 bytes of data
,2015-11-21T12:38:39.885Z SendDataTCPServer.js: TCP/IP server has received 779640 bytes of data
,2015-11-21T12:38:39.897Z SendDataTCPServer.js: TCP/IP server has received 801540 bytes of data
,2015-11-21T12:38:39.910Z SendDataTCPServer.js: TCP/IP server has received 821250 bytes of data
,2015-11-21T12:38:39.923Z SendDataTCPServer.js: TCP/IP server has received 840960 bytes of data
,2015-11-21T12:38:39.935Z SendDataTCPServer.js: TCP/IP server has received 867240 bytes of data
,2015-11-21T12:38:39.950Z SendDataTCPServer.js: TCP/IP server has received 895710 bytes of data
,2015-11-21T12:38:39.963Z SendDataTCPServer.js: TCP/IP server has received 915420 bytes of data
,2015-11-21T12:38:39.999Z SendDataTCPServer.js: TCP/IP server has received 505890 bytes of data
,2015-11-21T12:38:40.024Z SendDataTCPServer.js: TCP/IP server has received 509986 bytes of data
,2015-11-21T12:38:40.036Z SendDataTCPServer.js: TCP/IP server has received 591300 bytes of data
,2015-11-21T12:38:40.309Z SendDataTCPServer.js: TCP/IP server has received 593490 bytes of data
,2015-11-21T12:38:40.322Z SendDataTCPServer.js: TCP/IP server has received 604440 bytes of data
,2015-11-21T12:38:40.383Z SendDataTCPServer.js: TCP/IP server has received 608820 bytes of data
,2015-11-21T12:38:40.396Z SendDataTCPServer.js: TCP/IP server has received 630578 bytes of data
,2015-11-21T12:38:40.410Z SendDataTCPServer.js: TCP/IP server has received 635100 bytes of data
,2015-11-21T12:38:40.446Z SendDataTCPServer.js: TCP/IP server has received 926228 bytes of data
,2015-11-21T12:38:40.461Z SendDataTCPServer.js: TCP/IP server has received 976740 bytes of data
,2015-11-21T12:38:40.498Z SendDataTCPServer.js: TCP/IP server has received 978930 bytes of data
,2015-11-21T12:38:40.512Z SendDataTCPServer.js: TCP/IP server has received 1000002 bytes of data
,2015-11-21 13:38:40.550 ThaliTest[442:6313] server session: not connected Apple-Iphone5s-1_PT8264
,2015-11-21 13:38:40.560 ThaliTest[442:6313] client session: connected
2015-11-21 13:38:40.560 ThaliTest[442:6313] client session: stateChange:1->2 Apple-Iphone6-1_PT8382.HGUadg==
,2015-11-21 13:38:40.562 ThaliTest[442:6313] client session: fireConnectCallback: Apple-Iphone6-1_PT8382.HGUadg==
2015-11-21 13:38:40.563 ThaliTest[442:6313] jxcore: connect: success
,2015-11-21T12:38:40.566Z SendDataTCPServer.js: TCP/IP server has received 652620 bytes of data
2015-11-21T12:38:40.567Z SendDataConnector.js: CLIENT connected to 55104, error: null
2015-11-21T12:38:40.567Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 13:38:40.570 ThaliTest[442:60b] client: relay established
,2015-11-21 13:38:40.572 ThaliTest[442:60b] client: new accepted socket: 0x1c8a89f0
,2015-11-21T12:38:40.581Z SendDataTCPServer.js: TCP/IP server has received 661380 bytes of data
,2015-11-21T12:38:40.582Z SendDataConnector.js: CLIENT now sending 1000000 bytes of data
,2015-11-21T12:38:41.812Z SendDataTCPServer.js: TCP/IP server has received 792452 bytes of data
,2015-11-21T12:38:41.815Z SendDataTCPServer.js: TCP/IP server has received 923524 bytes of data
,2015-11-21T12:38:41.818Z SendDataTCPServer.js: TCP/IP server has received 1000002 bytes of data
,2015-11-21T12:38:42.114Z SendDataConnector.js: CLIENT is data received : 180000
,2015-11-21T12:38:42.491Z SendDataConnector.js: CLIENT is data received : 310000
,2015-11-21 13:38:42.519 ThaliTest[442:a51f] server session: not connected Apple-Iphone6-1_PT8382
,2015-11-21T12:38:43.584Z SendDataConnector.js: CLIENT is data received : 820000
,2015-11-21T12:38:43.619Z SendDataConnector.js: CLIENT is data received : 840000
,2015-11-21T12:38:43.633Z SendDataConnector.js: CLIENT is data received : 850000
,2015-11-21T12:38:43.645Z SendDataConnector.js: CLIENT is data received : 860000
,2015-11-21T12:38:43.657Z SendDataConnector.js: CLIENT is data received : 880000
,2015-11-21T12:38:43.670Z SendDataConnector.js: CLIENT is data received : 890000
,2015-11-21T12:38:43.682Z SendDataConnector.js: CLIENT is data received : 910000
,2015-11-21T12:38:43.694Z SendDataConnector.js: CLIENT is data received : 920000
,2015-11-21T12:38:43.707Z SendDataConnector.js: CLIENT is data received : 940000
,2015-11-21T12:38:43.719Z SendDataConnector.js: CLIENT is data received : 960000
,2015-11-21T12:38:44.007Z SendDataConnector.js: CLIENT is data received : 990000
,2015-11-21T12:38:44.020Z SendDataConnector.js: CLIENT is data received : 1000000
,2015-11-21T12:38:44.021Z SendDataConnector.js: got all data for this round
,2015-11-21T12:38:44.022Z SendDataConnector.js: CLIENT Stop now
2015-11-21T12:38:44.023Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 13:38:44.024 ThaliTest[442:6907] jxcore: disconnect
,2015-11-21 13:38:44.025 ThaliTest[442:6907] client session: disconnectFromPeer: Apple-Iphone6-1_PT8382.HGUadg==
,2015-11-21 13:38:44.025 ThaliTest[442:6907] client session: disconnect
,2015-11-21 13:38:44.026 ThaliTest[442:6907] client session: stateChange:2->0 Apple-Iphone6-1_PT8382.HGUadg==
,2015-11-21 13:38:44.028 ThaliTest[442:6907] jxcore: disconnect: success
2015-11-21T12:38:44.029Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8382.HGUadg==
---- round done--------
,device[3]: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-21T12:38:44.030Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-21T12:38:44.030Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21T12:38:44.031Z SendDataConnector.js: do connect now
,2015-11-21 13:38:44.031 ThaliTest[442:6907] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-21 13:38:44.032 ThaliTest[442:6907] client session: connect
,2015-11-21 13:38:44.033 ThaliTest[442:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21 13:38:49.340 ThaliTest[442:130b] client session: connected
2015-11-21 13:38:49.342 ThaliTest[442:130b] client session: stateChange:1->2 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21 13:38:49.343 ThaliTest[442:130b] client session: fireConnectCallback: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-21 13:38:49.344 ThaliTest[442:130b] jxcore: connect: success
2015-11-21T12:38:49.345Z SendDataConnector.js: CLIENT connected to 55107, error: null
,2015-11-21T12:38:49.345Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 13:38:49.346 ThaliTest[442:60b] client: relay established
,2015-11-21 13:38:49.347 ThaliTest[442:60b] client: new accepted socket: 0x156d6b50
,2015-11-21T12:38:49.358Z SendDataConnector.js: CLIENT now sending 1000000 bytes of data
,2015-11-21T12:38:50.971Z SendDataConnector.js: CLIENT is data received : 190000
,2015-11-21T12:38:51.557Z SendDataConnector.js: CLIENT is data received : 490000
,2015-11-21T12:38:52.499Z SendDataConnector.js: CLIENT is data received : 810000
,2015-11-21T12:38:52.556Z SendDataConnector.js: CLIENT is data received : 820000
,2015-11-21T12:38:52.568Z SendDataConnector.js: CLIENT is data received : 850000
,2015-11-21T12:38:52.581Z SendDataConnector.js: CLIENT is data received : 870000
,2015-11-21T12:38:52.605Z SendDataConnector.js: CLIENT is data received : 890000
,2015-11-21T12:38:52.882Z SendDataConnector.js: CLIENT is data received : 910000
,2015-11-21T12:38:52.919Z SendDataConnector.js: CLIENT is data received : 940000
,2015-11-21T12:38:52.932Z SendDataConnector.js: CLIENT is data received : 960000
,2015-11-21T12:38:52.968Z SendDataConnector.js: CLIENT is data received : 970000
,2015-11-21T12:38:52.982Z SendDataConnector.js: CLIENT is data received : 980000
,2015-11-21T12:38:52.994Z SendDataConnector.js: CLIENT is data received : 990000
,2015-11-21T12:38:53.018Z SendDataConnector.js: CLIENT is data received : 1000000
,2015-11-21T12:38:53.019Z SendDataConnector.js: got all data for this round
,2015-11-21T12:38:53.021Z SendDataConnector.js: CLIENT Stop now
2015-11-21T12:38:53.021Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-21 13:38:53.022 ThaliTest[442:6907] jxcore: disconnect
,2015-11-21 13:38:53.023 ThaliTest[442:6907] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-21 13:38:53.023 ThaliTest[442:6907] client session: disconnect
,2015-11-21 13:38:53.024 ThaliTest[442:6907] client session: stateChange:2->0 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21 13:38:53.026 ThaliTest[442:6907] jxcore: disconnect: success
2015-11-21T12:38:53.028Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd6Q==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT759","time":30513,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT5427.N/zz4w==","time":12622,"result":"OK","connections":1},{"name":"Apple-Iphone6-1_PT8382.HGUadg==","time":7858,"result":"OK","connections":1},{"name":"Apple-Iphone5s-1_PT8264./5qd6Q==","time":8989,"result":"OK","connections":1}]}
,sendList : 100% : 12622 ms, 99% : 12622 ms, 95 : 12622 ms, 90% : 12622 ms.
Result count 3, range 7858 ms to  12622 ms.
,sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
,2015-11-21T12:38:53.034Z SendDataConnector.js: CLIENT Stop now
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-21 13:38:53.873 ThaliTest[442:6907] jxcore: stopBroadcasting
,2015-11-21 13:38:53.874 ThaliTest[442:6907] THEMultipeerSession stopping peer
,2015-11-21 13:38:53.874 ThaliTest[442:6907] multipeer session: stop timer
,2015-11-21 13:38:53.875 ThaliTest[442:6907] server session: disconnect
,2015-11-21 13:38:53.877 ThaliTest[442:6907] server session: stateChange:2->0 Apple-Iphone5s-1_PT8264
,2015-11-21 13:38:53.880 ThaliTest[442:6907] server session: disconnect
,2015-11-21 13:38:53.881 ThaliTest[442:6907] server session: stateChange:2->0 Apple-Iphone6-1_PT8382
,2015-11-21 13:38:53.885 ThaliTest[442:6907] server session: disconnect
2015-11-21 13:38:53.887 ThaliTest[442:6907] server session: stateChange:2->0 Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:53.893 ThaliTest[442:6907] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-21T12:38:53.909Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T12:38:53.910Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T12:38:53.911Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T12:38:53.912Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT8382.HGUadg==\",\"time\":7858,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8264./5qd6Q==\",\"time\":8989,\",result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT5427.N/zz4w==\",\"time\":12622,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT8264./5,qd6Q==\",\"time\":3824,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8264./5qd6Q==\",\"time\":5219,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8382.HGUadg==\",\"time\":5413,\"result\":\"OK\",\"connections\":1},{,\"name\":\"Apple-IpadAir2-1_PT5427.N/zz4w==\",\"time\":5651,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8382.HGUadg==\",\"time\":6347,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8382.HGUadg==\",\"time\":7858,\",result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT5427.N/zz4w==\",\"time\":8446,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT759.cZHSYA==\",\"time\":8528,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-,1_PT8264./5qd6Q==\",\"time\":8989,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT759.cZHSYA==\",\"time\":10418,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT759.cZHSYA==\",\"time\":11883,\"result\":\"OK\",\"connecti,ons\":1},{\"name\":\"Apple-IpadAir2-1_PT5427.N/zz4w==\",\"time\":12622,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called
DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
The Coordinator has closed!
s
```
