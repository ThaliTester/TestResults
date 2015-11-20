#### Test 51335028813a553_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028813a553/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/6DC5A54C-DA99-45B9-B121-033AA3FA03BE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/6DC5A54C-DA99-45B9-B121-033AA3FA03BE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028813a553/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028813a553/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/F585B181-4044-4B6A-903E-F49BA7BBA839/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51168"
,(lldb)     command script import "/tmp/6DC5A54C-DA99-45B9-B121-033AA3FA03BE/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-11-20 13:00:33.623 ThaliTest[378:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 13:00:33.628 ThaliTest[378:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-20 13:00:33.635 ThaliTest[378:60b] Unlimited access to network resources
,2015-11-20 13:00:33.642 ThaliTest[378:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 13:00:44.296 ThaliTest[378:60b] Resetting plugins due to page load.
,2015-11-20 13:00:45.158 ThaliTest[378:60b] Finished load of: file:///var/mobile/Applications/F585B181-4044-4B6A-903E-F49BA7BBA839/ThaliTest.app/www/index.html
,2015-11-20 13:00:45.335 ThaliTest[378:60b] JXcore Cordova plugin initializing
,2015-11-20 13:00:45.337 ThaliTest[378:6a07] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
,Warning: iOS does not support ToggleBluetooth
,We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
toggleWiFi
,my name is : Apple-Iphone5-1_PT2716
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
,-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
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
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac87:63ff:fe65:ccab
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"10000000\",\"conReTryTimeout\":\"1000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":,[]}
Start now : testSendData.js
stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 53117
,2015-11-20 13:10:19.171 ThaliTest[378:6a07] jxcore: startBroadcasting
,2015-11-20 13:10:19.189 ThaliTest[378:6a07] server: starting Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:10:19.200 ThaliTest[378:6a07] multipeer session: start timer: 0x1cef1cb0
,2015-11-20 13:10:19.202 ThaliTest[378:6a07] THEMultipeerSession initialized peer Apple-Iphone5-1_PT2716
,2015-11-20 13:10:19.203 ThaliTest[378:6a07] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-20T12:10:19.205Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-20 13:10:19.534 ThaliTest[378:60b] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:19.538Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:19.539Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:19.607 ThaliTest[378:60b] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:10:20.225 ThaliTest[378:60b] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7072.5zbvNA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:10:20.550 ThaliTest[378:6a07] jxcore: disconnect
,2015-11-20 13:10:20.551 ThaliTest[378:6a07] jxcore: disconnect: fail
2015-11-20T12:10:20.553Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:20.553Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5s-1_PT497.PdI1bg== with availability status: true
2015-11-20T12:10:20.554Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:20.554Z SendDataConnector.js: do connect now
,2015-11-20 13:10:20.554 ThaliTest[378:6a07] jxcore: connect Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:20.555 ThaliTest[378:6a07] client session: connect
,2015-11-20 13:10:20.556 ThaliTest[378:6a07] client session: stateChange:0->1 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:28.261 ThaliTest[378:632f] client session: connected
2015-11-20 13:10:28.263 ThaliTest[378:632f] client session: stateChange:1->2 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:28.267 ThaliTest[378:632f] client session: fireConnectCallback: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:28.268 ThaliTest[378:632f] jxcore: connect: success
,2015-11-20T12:10:28.269Z SendDataConnector.js: CLIENT connected to 53120, error: null
,2015-11-20T12:10:28.270Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:10:28.271 ThaliTest[378:60b] client: relay established
,2015-11-20 13:10:28.271 ThaliTest[378:60b] client: new accepted socket: 0x1ce45400
,2015-11-20T12:10:28.283Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:10:38.727Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:44.347 ThaliTest[378:632f] client session: not connected Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:44.348 ThaliTest[378:632f] client session: onLinkFailure: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:10:44.349 ThaliTest[378:632f] client session: disconnect
,2015-11-20 13:10:44.350 ThaliTest[378:632f] client session: stateChange:2->0 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:44.404Z SendDataConnector.js: CLIENT got error : Error: read ECONNRESET
2015-11-20T12:10:44.405Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:10:44.406Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20 13:10:44.404 ThaliTest[378:632f] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:44.407 ThaliTest[378:60b] client: lost peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:44.409Z SendDataConnector.js: CLIENT is closed
2015-11-20 13:10:44.409 ThaliTest[378:60b] client session: onPeerLost: Apple-Iphone5s-1_PT497.Pd,I1bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":false}]
2015-11-20 13:10:44.410 ThaliTest[378:60b] client: lost peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:10:44.412 ThaliTest[378:60b] client session: onPeerLost: Apple-Iphone6-1_PT2043.OU3s0w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-20 13:10:44.413 ThaliTest[378:60b] client: lost peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:10:44.415 ThaliTest[378:60b] client session: onPeerLost: Apple-IpadAir2-1_PT7072.5zbvNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7072.5zbvNA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-20 13:10:44.755 ThaliTest[378:60b] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:10:45.197 ThaliTest[378:60b] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7072.5zbvNA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20T12:10:45.410Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:45.411Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:46.418 ThaliTest[378:6a07] jxcore: disconnect
,2015-11-20 13:10:46.419 ThaliTest[378:6a07] jxcore: disconnect: fail
2015-11-20T12:10:46.421Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:46.421Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT497.PdI1bg== with availability status: true
2015-11-20T12:10:46.421Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:46.422Z SendDataConnector.js: do connect now
,2015-11-20 13:10:46.422 ThaliTest[378:6a07] jxcore: connect Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:46.423 ThaliTest[378:6a07] client session: connect
,2015-11-20 13:10:46.423 ThaliTest[378:6a07] client session: stateChange:0->1 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:47.692 ThaliTest[378:60b] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:10:48.005 ThaliTest[378:60b] client: lost peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:10:48.006 ThaliTest[378:60b] client session: onPeerLost: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:10:48.007 ThaliTest[378:60b] client: lost peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:10:48.007 ThaliTest[378:60b] client sessio,n: onPeerLost: Apple-Iphone6-1_PT2043.OU3s0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7072.5zbvNA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Ap,ple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":false}]
2015-11-20 13:10:48.009 ThaliTest[378:60b] client: lost peer: Apple-Iphone5s-1_PT497.PdI1bg==
Found peer : (null), Available: false
2015-11-20 13:10:48.009 ThaliTest[378:60b] cli,ent session: onPeerLost: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:10:48.010 ThaliTest[378:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:10:48.011 ThaliTest[378:60b] client session: disconnect
2015-11-20 13:10:48.,012 ThaliTest[378:60b] client session: stateChange:1->0 Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:10:48.012 ThaliTest[378:60b] client session: fireConnectCallback: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:10:48.013 ThaliTest[378:60b] jxcore: connect: fail: Peer disconnected
,2015-11-20T12:10:48.016Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T12:10:48.017Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T12:10:48.017Z SendDataConnector.js: tryAgain afer: 1000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:10:48.053 ThaliTest[378:60b] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7072.5zbvNA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:10:48.091 ThaliTest[378:60b] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:10:48.204 ThaliTest[378:60b] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20T12:10:48.737Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:10:48.737Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T12:10:49.025Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:49.025Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:49.203 ThaliTest[378:60b] multipeer session: restart
,2015-11-20 13:10:50.026 ThaliTest[378:6a07] jxcore: disconnect
,2015-11-20 13:10:50.027 ThaliTest[378:6a07] jxcore: disconnect: fail
,2015-11-20T12:10:50.029Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:50.030Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT497.PdI1bg== with availability status: true
,2015-11-20T12:10:50.030Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:50.030Z SendDataConnector.js: do connect now
,2015-11-20 13:10:50.031 ThaliTest[378:6a07] jxcore: connect Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:50.031 ThaliTest[378:6a07] client session: connect
,2015-11-20 13:10:50.032 ThaliTest[378:6a07] client session: stateChange:0->1 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:19.203 ThaliTest[378:60b] multipeer session: restart
,2015-11-20 13:11:19.213 ThaliTest[378:60b] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:19.215 ThaliTest[378:60b] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:11:19.447 ThaliTest[378:60b] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:23.010 ThaliTest[378:8f33] client session: not connected Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:23.012 ThaliTest[378:8f33] client session: onLinkFailure: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:11:23.014 ThaliTest[378:8f33] client session: disconnect
2015-11-20 13:11:23.015 ThaliTest[378:8f33] client session: stateChange:1->0 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:23.015 ThaliTest[378:8f33] client session: fireConnectCallback: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:11:23.016 ThaliTest[378:8f33] jxcore: connect: fail: Peer disconnected
,2015-11-20T12:11:23.017Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T12:11:23.018Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T12:11:23.018Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:11:24.026Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:24.026Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:25.034 ThaliTest[378:6a07] jxcore: disconnect
,2015-11-20 13:11:25.036 ThaliTest[378:6a07] jxcore: disconnect: fail
2015-11-20T12:11:25.037Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:25.038Z SendDataConnector.js: Connect (retry count, 3) to peer Apple-Iphone5s-1_PT497.PdI1bg== with availability status: true
,2015-11-20T12:11:25.038Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:25.038Z SendDataConnector.js: do connect now
,2015-11-20 13:11:25.039 ThaliTest[378:6a07] jxcore: connect Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:25.039 ThaliTest[378:6a07] client session: connect
,2015-11-20 13:11:25.040 ThaliTest[378:6a07] client session: stateChange:0->1 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:27.923 ThaliTest[378:6343] client session: connected
2015-11-20 13:11:27.924 ThaliTest[378:6343] client session: stateChange:1->2 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:27.927 ThaliTest[378:6343] client session: fireConnectCallback: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:27.929 ThaliTest[378:6343] jxcore: connect: success
,2015-11-20T12:11:27.930Z SendDataConnector.js: CLIENT connected to 53133, error: null
2015-11-20T12:11:27.930Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:11:27.932 ThaliTest[378:60b] client: relay established
2015-11-20 13:11:27.933 ThaliTest[378:60b] client: new accepted socket: 0x1cfa72a0
,2015-11-20T12:11:27.944Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:11:32.071 ThaliTest[378:60b] client: lost peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:11:32.072 ThaliTest[378:60b] client session: onPeerLost: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:11:38.290Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-20 13:11:41.650 ThaliTest[378:60b] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20T12:11:48.013Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:48.015Z SendDataConnector.js: CLIENT is data received : 1670000
,2015-11-20 13:11:50.640 ThaliTest[378:60b] multipeer session: restart
,2015-11-20T12:11:50.648Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:50.648Z SendDataConnector.js: CLIENT is data received : 2540000
,2015-11-20 13:11:55.249 ThaliTest[378:60b] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:55.860 ThaliTest[378:60b] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:11:55.861 ThaliTest[378:60b] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:11:56.449 ThaliTest[378:60b] multipeer session: reset timer
2015-11-20 13:11:56.450 ThaliTest[378:60b] multipeer session: stop timer
2015-11-20 13:11:56.451 ThaliTest[378:60b] multipeer session: start timer: 0x1cef1cb0
2015-11-20 13:11:56.452 ThaliTest[378:60b] server session: connect
,2015-11-20 13:11:56.452 ThaliTest[378:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT7072
,2015-11-20 13:11:56.458 ThaliTest[378:60b] server: accepting invitation Apple-IpadAir2-1_PT7072
,2015-11-20T12:11:58.487Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:58.488Z SendDataConnector.js: CLIENT is data received : 6710000
,2015-11-20T12:11:59.517Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:59.518Z SendDataConnector.js: CLIENT is data received : 6890000
,2015-11-20 13:12:01.951 ThaliTest[378:6343] server session: connected
2015-11-20 13:12:01.952 ThaliTest[378:6343] server session: stateChange:1->2 Apple-IpadAir2-1_PT7072
,2015-11-20T12:12:01.972Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:12:03.125 ThaliTest[378:60b] server relay: connected (to port: 53117)
,2015-11-20T12:12:03.129Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:12:03.130Z SendDataConnector.js: CLIENT is data received : 8940000
,2015-11-20T12:12:05.673Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:12:05.674Z SendDataConnector.js: CLIENT is data received : 9710000
,2015-11-20 13:12:05.773 ThaliTest[378:60b] multipeer session: reset timer
2015-11-20 13:12:05.774 ThaliTest[378:60b] multipeer session: stop timer
,2015-11-20 13:12:05.775 ThaliTest[378:60b] multipeer session: start timer: 0x1cef1cb0
,2015-11-20 13:12:05.775 ThaliTest[378:60b] server session: connect
,2015-11-20 13:12:05.776 ThaliTest[378:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT497
,2015-11-20 13:12:05.780 ThaliTest[378:60b] server: accepting invitation Apple-Iphone5s-1_PT497
,2015-11-20T12:12:05.782Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:12:05.782Z SendDataConnector.js: CLIENT is data received : 9790000
,2015-11-20T12:12:05.794Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:12:05.795Z SendDataConnector.js: CLIENT is data received : 9810000
,2015-11-20T12:12:06.126Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:12:06.127Z SendDataConnector.js: CLIENT is data received : 9840000
,2015-11-20T12:12:06.139Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:12:06.140Z SendDataConnector.js: CLIENT is data received : 9860000
,2015-11-20T12:12:06.163Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:12:06.164Z SendDataConnector.js: CLIENT is data received : 9870000
,2015-11-20T12:12:06.198Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:12:06.199Z SendDataConnector.js: CLIENT is data received : 9880000
,2015-11-20T12:12:06.212Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:12:06.212Z SendDataConnector.js: CLIENT is data received : 9890000
,2015-11-20T12:12:06.224Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:12:06.225Z SendDataConnector.js: CLIENT is data received : 9900000
,2015-11-20T12:12:06.239Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:12:06.239Z SendDataConnector.js: CLIENT is data received : 9910000
,2015-11-20T12:12:06.251Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:12:06.252Z SendDataConnector.js: CLIENT is data received : 9920000
,2015-11-20T12:12:06.264Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:12:06.265Z SendDataConnector.js: CLIENT is data received : 9940000
,2015-11-20T12:12:06.288Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:12:06.289Z SendDataConnector.js: CLIENT is data received : 9960000
,2015-11-20T12:12:06.648Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-11-20T12:12:06.661Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
2015-11-20T12:12:06.662Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:12:06.663Z SendDataConnector.js: CLIENT is data received : 9980000
,2015-11-20T12:12:06.675Z SendDataTCPServer.js: TCP/IP server has received 54608 bytes of data
2015-11-20T12:12:06.676Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:12:06.677Z SendDataConnector.js: ,CLIENT is data received : 10000000
2015-11-20T12:12:06.677Z SendDataConnector.js: got all data for this round
2015-11-20T12:12:06.679Z SendDataConnector.js: CLIENT Stop now
2015-11-20T12:12:06.679Z SendDataConnector.js: CLIENT closeClientSocket
2015-11,-20 13:12:06.680 ThaliTest[378:6a07] jxcore: disconnect
2015-11-20 13:12:06.681 ThaliTest[378:6a07] client session: disconnectFromPeer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:12:06.682 ThaliTest[378:6a07] client session: disconnect
2015-11-20 13:,12:06.682 ThaliTest[378:6a07] client session: stateChange:2->0 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:12:06.692 ThaliTest[378:6a07] jxcore: disconnect: success
2015-11-20T12:12:06.696Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg==
,---- round done--------
device[2]: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:12:06.703Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:12:06.706Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:12:06.721Z SendDataTCPServer.js: TCP/IP server has received 113596 bytes of data
2015-11-20T12:12:06.725Z SendDataConnector.js: CLIENT is closed
,2015-11-20T12:12:06.739Z SendDataTCPServer.js: TCP/IP server has received 159586 bytes of data
,2015-11-20T12:12:06.754Z SendDataTCPServer.js: TCP/IP server has received 197100 bytes of data
,2015-11-20T12:12:06.771Z SendDataTCPServer.js: TCP/IP server has received 236520 bytes of data
,2015-11-20T12:12:06.785Z SendDataTCPServer.js: TCP/IP server has received 266896 bytes of data
,2015-11-20T12:12:06.802Z SendDataTCPServer.js: TCP/IP server has received 284700 bytes of data
,2015-11-20T12:12:06.816Z SendDataTCPServer.js: TCP/IP server has received 295650 bytes of data
,2015-11-20T12:12:06.829Z SendDataTCPServer.js: TCP/IP server has received 336124 bytes of data
,2015-11-20T12:12:06.842Z SendDataTCPServer.js: TCP/IP server has received 378870 bytes of data
,2015-11-20T12:12:06.855Z SendDataTCPServer.js: TCP/IP server has received 424860 bytes of data
,2015-11-20T12:12:07.172Z SendDataTCPServer.js: TCP/IP server has received 438000 bytes of data
,2015-11-20T12:12:07.185Z SendDataTCPServer.js: TCP/IP server has received 459900 bytes of data
,2015-11-20T12:12:07.197Z SendDataTCPServer.js: TCP/IP server has received 477420 bytes of data
,2015-11-20T12:12:07.211Z SendDataTCPServer.js: TCP/IP server has received 496988 bytes of data
,2015-11-20T12:12:07.224Z SendDataTCPServer.js: TCP/IP server has received 516840 bytes of data
,2015-11-20T12:12:07.236Z SendDataTCPServer.js: TCP/IP server has received 540930 bytes of data
,2015-11-20T12:12:07.249Z SendDataTCPServer.js: TCP/IP server has received 562830 bytes of data
,2015-11-20T12:12:07.262Z SendDataTCPServer.js: TCP/IP server has received 580350 bytes of data
,2015-11-20T12:12:07.274Z SendDataTCPServer.js: TCP/IP server has received 602250 bytes of data
,2015-11-20T12:12:07.287Z SendDataTCPServer.js: TCP/IP server has received 635100 bytes of data
,2015-11-20T12:12:07.301Z SendDataTCPServer.js: TCP/IP server has received 681090 bytes of data
,2015-11-20T12:12:07.314Z SendDataTCPServer.js: TCP/IP server has received 707370 bytes of data
,2015-11-20T12:12:07.329Z SendDataTCPServer.js: TCP/IP server has received 738030 bytes of data
,2015-11-20T12:12:07.343Z SendDataTCPServer.js: TCP/IP server has received 772928 bytes of data
,2015-11-20T12:12:07.356Z SendDataTCPServer.js: TCP/IP server has received 803730 bytes of data
,2015-11-20T12:12:07.369Z SendDataTCPServer.js: TCP/IP server has received 853958 bytes of data
,2015-11-20T12:12:07.383Z SendDataTCPServer.js: TCP/IP server has received 880380 bytes of data
,2015-11-20T12:12:07.704Z SendDataTCPServer.js: TCP/IP server has received 886950 bytes of data
,2015-11-20 13:12:07.718 ThaliTest[378:6a07] jxcore: disconnect
2015-11-20 13:12:07.719 ThaliTest[378:6a07] jxcore: disconnect: fail
2015-11-20T12:12:07.721Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2043.OU3s0w==
201,5-11-20T12:12:07.721Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone6-1_PT2043.OU3s0w== with availability status: true
2015-11-20T12:12:07.722Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-2,0T12:12:07.722Z SendDataConnector.js: do connect now
2015-11-20 13:12:07.723 ThaliTest[378:6a07] jxcore: connect Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:12:07.725 ThaliTest[378:6a07] client session: connect
2015-11-20 13:12:07.727 ThaliTest[378:6a,07] client session: stateChange:0->1 Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:12:07.927Z SendDataTCPServer.js: TCP/IP server has received 1018022 bytes of data
2015-11-20T12:12:07.930Z SendDataTCPServer.js: TCP/IP server has received 1149094 bytes of data
2015-11-20T12:12:07.933Z SendDataTCPServer.js: TCP/IP server has received 1280166 bytes of data
,2015-11-20T12:12:07.940Z SendDataTCPServer.js: TCP/IP server has received 1411238 bytes of data
,2015-11-20T12:12:07.943Z SendDataTCPServer.js: TCP/IP server has received 1419120 bytes of data
,2015-11-20T12:12:08.226Z SendDataTCPServer.js: TCP/IP server has received 1425690 bytes of data
,2015-11-20T12:12:08.238Z SendDataTCPServer.js: TCP/IP server has received 1467016 bytes of data
,2015-11-20T12:12:08.254Z SendDataTCPServer.js: TCP/IP server has received 1508910 bytes of data
,2015-11-20T12:12:08.292Z SendDataTCPServer.js: TCP/IP server has received 1522050 bytes of data
,2015-11-20 13:12:08.305 ThaliTest[378:a803] server session: connected
,2015-11-20 13:12:08.306 ThaliTest[378:a803] server session: stateChange:1->2 Apple-Iphone5s-1_PT497
,2015-11-20T12:12:08.309Z SendDataTCPServer.js: TCP/IP server has received 1550236 bytes of data
,2015-11-20 13:12:08.312 ThaliTest[378:60b] server relay: connected (to port: 53117)
,2015-11-20T12:12:08.324Z SendDataTCPServer.js: TCP/IP server has received 1570230 bytes of data
,2015-11-20T12:12:08.327Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:12:08.340Z SendDataTCPServer.js: TCP/IP server has received 1594320 bytes of data
,2015-11-20T12:12:08.354Z SendDataTCPServer.js: TCP/IP server has received 1622790 bytes of data
,2015-11-20T12:12:08.368Z SendDataTCPServer.js: TCP/IP server has received 1644690 bytes of data
,2015-11-20T12:12:08.381Z SendDataTCPServer.js: TCP/IP server has received 1677540 bytes of data
,2015-11-20T12:12:08.393Z SendDataTCPServer.js: TCP/IP server has received 1701630 bytes of data
,2015-11-20T12:12:08.406Z SendDataTCPServer.js: TCP/IP server has received 1727910 bytes of data
,2015-11-20T12:12:08.420Z SendDataTCPServer.js: TCP/IP server has received 1754190 bytes of data
,2015-11-20T12:12:08.433Z SendDataTCPServer.js: TCP/IP server has received 1784850 bytes of data
,2015-11-20T12:12:08.446Z SendDataTCPServer.js: TCP/IP server has received 1811130 bytes of data
,2015-11-20T12:12:08.459Z SendDataTCPServer.js: TCP/IP server has received 1841790 bytes of data
,2015-11-20T12:12:08.472Z SendDataTCPServer.js: TCP/IP server has received 1865880 bytes of data
,2015-11-20T12:12:08.485Z SendDataTCPServer.js: TCP/IP server has received 1889828 bytes of data
,2015-11-20T12:12:08.498Z SendDataTCPServer.js: TCP/IP server has received 1929390 bytes of data
,2015-11-20T12:12:08.512Z SendDataTCPServer.js: TCP/IP server has received 1953338 bytes of data
,2015-11-20T12:12:08.525Z SendDataTCPServer.js: TCP/IP server has received 1981950 bytes of data
,2015-11-20T12:12:08.538Z SendDataTCPServer.js: TCP/IP server has received 2016990 bytes of data
,2015-11-20T12:12:08.550Z SendDataTCPServer.js: TCP/IP server has received 2043128 bytes of data
,2015-11-20T12:12:08.564Z SendDataTCPServer.js: TCP/IP server has received 2078310 bytes of data
,2015-11-20T12:12:08.577Z SendDataTCPServer.js: TCP/IP server has received 2098020 bytes of data
,2015-11-20T12:12:08.635Z SendDataTCPServer.js: TCP/IP server has received 2100210 bytes of data
,2015-11-20T12:12:08.748Z SendDataTCPServer.js: TCP/IP server has received 2106496 bytes of data
,2015-11-20T12:12:08.763Z SendDataTCPServer.js: TCP/IP server has received 2133060 bytes of data
,2015-11-20T12:12:08.778Z SendDataTCPServer.js: TCP/IP server has received 2150580 bytes of data
,2015-11-20T12:12:08.792Z SendDataTCPServer.js: TCP/IP server has received 2176860 bytes of data
,2015-11-20T12:12:08.807Z SendDataTCPServer.js: TCP/IP server has received 2189858 bytes of data
,2015-11-20T12:12:08.820Z SendDataTCPServer.js: TCP/IP server has received 2220660 bytes of data
,2015-11-20T12:12:08.833Z SendDataTCPServer.js: TCP/IP server has received 2251178 bytes of data
,2015-11-20T12:12:08.846Z SendDataTCPServer.js: TCP/IP server has received 2275410 bytes of data
,2015-11-20T12:12:08.859Z SendDataTCPServer.js: TCP/IP server has received 2299358 bytes of data
,2015-11-20T12:12:08.871Z SendDataTCPServer.js: TCP/IP server has received 2330018 bytes of data
,2015-11-20T12:12:08.885Z SendDataTCPServer.js: TCP/IP server has received 2358630 bytes of data
,2015-11-20T12:12:08.898Z SendDataTCPServer.js: TCP/IP server has received 2393670 bytes of data
,2015-11-20T12:12:08.909Z SendDataTCPServer.js: TCP/IP server has received 2415570 bytes of data
,2015-11-20T12:12:08.922Z SendDataTCPServer.js: TCP/IP server has received 2452516 bytes of data
,2015-11-20T12:12:08.935Z SendDataTCPServer.js: TCP/IP server has received 2481270 bytes of data
,2015-11-20T12:12:08.947Z SendDataTCPServer.js: TCP/IP server has received 2498790 bytes of data
,2015-11-20T12:12:08.959Z SendDataTCPServer.js: TCP/IP server has received 2522880 bytes of data
,2015-11-20T12:12:08.972Z SendDataTCPServer.js: TCP/IP server has received 2549160 bytes of data
,2015-11-20T12:12:08.984Z SendDataTCPServer.js: TCP/IP server has received 2579678 bytes of data
,2015-11-20T12:12:08.996Z SendDataTCPServer.js: TCP/IP server has received 2603910 bytes of data
,2015-11-20T12:12:09.010Z SendDataTCPServer.js: TCP/IP server has received 2627858 bytes of data
,2015-11-20T12:12:09.023Z SendDataTCPServer.js: TCP/IP server has received 2651948 bytes of data
,2015-11-20T12:12:09.037Z SendDataTCPServer.js: TCP/IP server has received 2691510 bytes of data
,2015-11-20T12:12:09.051Z SendDataTCPServer.js: TCP/IP server has received 2759400 bytes of data
,2015-11-20T12:12:09.064Z SendDataTCPServer.js: TCP/IP server has received 2801010 bytes of data
,2015-11-20T12:12:09.278Z SendDataTCPServer.js: TCP/IP server has received 2803200 bytes of data
,2015-11-20T12:12:09.291Z SendDataTCPServer.js: TCP/IP server has received 2816340 bytes of data
,2015-11-20T12:12:09.304Z SendDataTCPServer.js: TCP/IP server has received 2844810 bytes of data
,2015-11-20T12:12:09.318Z SendDataTCPServer.js: TCP/IP server has received 2864520 bytes of data
,2015-11-20T12:12:09.331Z SendDataTCPServer.js: TCP/IP server has received 2882040 bytes of data
,2015-11-20T12:12:09.345Z SendDataTCPServer.js: TCP/IP server has received 2901750 bytes of data
,2015-11-20T12:12:09.357Z SendDataTCPServer.js: TCP/IP server has received 2930220 bytes of data
,2015-11-20T12:12:09.370Z SendDataTCPServer.js: TCP/IP server has received 2952120 bytes of data
,2015-11-20T12:12:09.383Z SendDataTCPServer.js: TCP/IP server has received 2978258 bytes of data
,2015-11-20T12:12:09.396Z SendDataTCPServer.js: TCP/IP server has received 2998110 bytes of data
,2015-11-20T12:12:09.408Z SendDataTCPServer.js: TCP/IP server has received 3035198 bytes of data
,2015-11-20T12:12:09.421Z SendDataTCPServer.js: TCP/IP server has received 3063810 bytes of data
,2015-11-20T12:12:09.433Z SendDataTCPServer.js: TCP/IP server has received 3083520 bytes of data
,2015-11-20T12:12:09.447Z SendDataTCPServer.js: TCP/IP server has received 3122230 bytes of data
,2015-11-20T12:12:09.460Z SendDataTCPServer.js: TCP/IP server has received 3153600 bytes of data
,2015-11-20T12:12:09.474Z SendDataTCPServer.js: TCP/IP server has received 3195210 bytes of data
,2015-11-20T12:12:09.488Z SendDataTCPServer.js: TCP/IP server has received 3234630 bytes of data
,2015-11-20T12:12:09.501Z SendDataTCPServer.js: TCP/IP server has received 3269528 bytes of data
,2015-11-20T12:12:09.516Z SendDataTCPServer.js: TCP/IP server has received 3306758 bytes of data
,2015-11-20T12:12:09.528Z SendDataTCPServer.js: TCP/IP server has received 3335228 bytes of data
,2015-11-20T12:12:09.541Z SendDataTCPServer.js: TCP/IP server has received 3359460 bytes of data
,2015-11-20T12:12:09.554Z SendDataTCPServer.js: TCP/IP server has received 3385740 bytes of data
,2015-11-20T12:12:09.568Z SendDataTCPServer.js: TCP/IP server has received 3418590 bytes of data
,2015-11-20T12:12:09.580Z SendDataTCPServer.js: TCP/IP server has received 3442538 bytes of data
,2015-11-20T12:12:09.592Z SendDataTCPServer.js: TCP/IP server has received 3468960 bytes of data
,2015-11-20T12:12:09.605Z SendDataTCPServer.js: TCP/IP server has received 3528090 bytes of data
,2015-11-20T12:12:09.618Z SendDataTCPServer.js: TCP/IP server has received 3556560 bytes of data
,2015-11-20T12:12:09.631Z SendDataTCPServer.js: TCP/IP server has received 3560940 bytes of data
,2015-11-20T12:12:09.710Z SendDataTCPServer.js: TCP/IP server has received 3563130 bytes of data
,2015-11-20T12:12:09.814Z SendDataTCPServer.js: TCP/IP server has received 3589410 bytes of data
,2015-11-20T12:12:09.827Z SendDataTCPServer.js: TCP/IP server has received 3602550 bytes of data
,2015-11-20T12:12:09.840Z SendDataTCPServer.js: TCP/IP server has received 3624450 bytes of data
,2015-11-20T12:12:09.853Z SendDataTCPServer.js: TCP/IP server has received 3641970 bytes of data
,2015-11-20T12:12:09.866Z SendDataTCPServer.js: TCP/IP server has received 3657158 bytes of data
,2015-11-20T12:12:09.879Z SendDataTCPServer.js: TCP/IP server has received 3683438 bytes of data
,2015-11-20T12:12:09.891Z SendDataTCPServer.js: TCP/IP server has received 3705338 bytes of data
,2015-11-20T12:12:09.904Z SendDataTCPServer.js: TCP/IP server has received 3729570 bytes of data
,2015-11-20T12:12:09.918Z SendDataTCPServer.js: TCP/IP server has received 3768990 bytes of data
,2015-11-20T12:12:09.930Z SendDataTCPServer.js: TCP/IP server has received 3799650 bytes of data
,2015-11-20T12:12:09.942Z SendDataTCPServer.js: TCP/IP server has received 3842598 bytes of data
,2015-11-20T12:12:09.960Z SendDataTCPServer.js: TCP/IP server has received 3886540 bytes of data
,2015-11-20T12:12:09.975Z SendDataTCPServer.js: TCP/IP server has received 3924480 bytes of data
,2015-11-20T12:12:09.989Z SendDataTCPServer.js: TCP/IP server has received 3955140 bytes of data
,2015-11-20T12:12:10.005Z SendDataTCPServer.js: TCP/IP server has received 3998940 bytes of data
,2015-11-20T12:12:10.020Z SendDataTCPServer.js: TCP/IP server has received 4051500 bytes of data
,2015-11-20T12:12:10.035Z SendDataTCPServer.js: TCP/IP server has received 4087878 bytes of data
,2015-11-20T12:12:10.048Z SendDataTCPServer.js: TCP/IP server has received 4121580 bytes of data
,2015-11-20T12:12:10.062Z SendDataTCPServer.js: TCP/IP server has received 4161000 bytes of data
,2015-11-20T12:12:10.075Z SendDataTCPServer.js: TCP/IP server has received 4187280 bytes of data
,2015-11-20T12:12:10.087Z SendDataTCPServer.js: TCP/IP server has received 4209180 bytes of data
,2015-11-20T12:12:10.099Z SendDataTCPServer.js: TCP/IP server has received 4231080 bytes of data
,2015-11-20T12:12:10.112Z SendDataTCPServer.js: TCP/IP server has received 4283640 bytes of data
,2015-11-20T12:12:10.126Z SendDataTCPServer.js: TCP/IP server has received 4353720 bytes of data
,2015-11-20T12:12:10.162Z SendDataTCPServer.js: TCP/IP server has received 4355910 bytes of data
,2015-11-20T12:12:10.319Z SendDataTCPServer.js: TCP/IP server has received 4364670 bytes of data
,2015-11-20T12:12:10.332Z SendDataTCPServer.js: TCP/IP server has received 4371240 bytes of data
,2015-11-20T12:12:10.345Z SendDataTCPServer.js: TCP/IP server has received 4393140 bytes of data
,2015-11-20T12:12:10.357Z SendDataTCPServer.js: TCP/IP server has received 4415040 bytes of data
,2015-11-20T12:12:10.369Z SendDataTCPServer.js: TCP/IP server has received 4454460 bytes of data
,2015-11-20T12:12:10.384Z SendDataTCPServer.js: TCP/IP server has received 4478408 bytes of data
,2015-11-20T12:12:10.396Z SendDataTCPServer.js: TCP/IP server has received 4498260 bytes of data
,2015-11-20T12:12:10.409Z SendDataTCPServer.js: TCP/IP server has received 4522208 bytes of data
,2015-11-20T12:12:10.422Z SendDataTCPServer.js: TCP/IP server has received 4544250 bytes of data
,2015-11-20T12:12:10.435Z SendDataTCPServer.js: TCP/IP server has received 4563960 bytes of data
,2015-11-20T12:12:10.449Z SendDataTCPServer.js: TCP/IP server has received 4594620 bytes of data
,2015-11-20T12:12:10.462Z SendDataTCPServer.js: TCP/IP server has received 4627470 bytes of data
,2015-11-20T12:12:10.477Z SendDataTCPServer.js: TCP/IP server has received 4664558 bytes of data
,2015-11-20T12:12:10.492Z SendDataTCPServer.js: TCP/IP server has received 4695360 bytes of data
,2015-11-20T12:12:10.506Z SendDataTCPServer.js: TCP/IP server has received 4728210 bytes of data
,2015-11-20T12:12:10.519Z SendDataTCPServer.js: TCP/IP server has received 4754490 bytes of data
,2015-11-20T12:12:10.531Z SendDataTCPServer.js: TCP/IP server has received 4782960 bytes of data
,2015-11-20T12:12:10.545Z SendDataTCPServer.js: TCP/IP server has received 4818000 bytes of data
,2015-11-20T12:12:10.558Z SendDataTCPServer.js: TCP/IP server has received 4842090 bytes of data
,2015-11-20T12:12:10.570Z SendDataTCPServer.js: TCP/IP server has received 4870418 bytes of data
,2015-11-20T12:12:10.584Z SendDataTCPServer.js: TCP/IP server has received 4899030 bytes of data
,2015-11-20T12:12:10.597Z SendDataTCPServer.js: TCP/IP server has received 4925310 bytes of data
,2015-11-20T12:12:10.609Z SendDataTCPServer.js: TCP/IP server has received 4949258 bytes of data
,2015-11-20T12:12:10.622Z SendDataTCPServer.js: TCP/IP server has received 4986630 bytes of data
,2015-11-20T12:12:10.635Z SendDataTCPServer.js: TCP/IP server has received 5015100 bytes of data
,2015-11-20T12:12:10.648Z SendDataTCPServer.js: TCP/IP server has received 5054520 bytes of data
,2015-11-20T12:12:10.661Z SendDataTCPServer.js: TCP/IP server has received 5100510 bytes of data
,2015-11-20T12:12:10.674Z SendDataTCPServer.js: TCP/IP server has received 5122410 bytes of data
,2015-11-20T12:12:10.733Z SendDataTCPServer.js: TCP/IP server has received 5131170 bytes of data
,2015-11-20T12:12:10.746Z SendDataTCPServer.js: TCP/IP server has received 5139930 bytes of data
,2015-11-20T12:12:10.850Z SendDataTCPServer.js: TCP/IP server has received 5166210 bytes of data
,2015-11-20T12:12:10.866Z SendDataTCPServer.js: TCP/IP server has received 5199060 bytes of data
,2015-11-20T12:12:10.882Z SendDataTCPServer.js: TCP/IP server has received 5236290 bytes of data
,2015-11-20 13:12:10.888 ThaliTest[378:6343] client session: connected
2015-11-20 13:12:10.889 ThaliTest[378:6343] client session: stateChange:1->2 Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:12:10.897Z SendDataTCPServer.js: TCP/IP server has received 5258190 bytes of data
,2015-11-20 13:12:10.903 ThaliTest[378:6343] client session: fireConnectCallback: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:12:10.905 ThaliTest[378:6343] jxcore: connect: success
,2015-11-20T12:12:10.912Z SendDataTCPServer.js: TCP/IP server has received 5271188 bytes of data
2015-11-20T12:12:10.913Z SendDataConnector.js: CLIENT connected to 53140, error: null
2015-11-20T12:12:10.914Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:12:10.918 ThaliTest[378:60b] client: relay established
2015-11-20 13:12:10.919 ThaliTest[378:60b] client: new accepted socket: 0x1cf50f20
,2015-11-20T12:12:10.930Z SendDataTCPServer.js: TCP/IP server has received 5310952 bytes of data
2015-11-20T12:12:10.931Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:12:22.614 ThaliTest[378:8a23] server session: not connected Apple-IpadAir2-1_PT7072
,2015-11-20 13:12:23.464 ThaliTest[378:6343] server session: not connected Apple-Iphone5s-1_PT497
,2015-11-20T12:12:24.731Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:12:24.999Z SendDataTCPServer.js: TCP/IP server has received 5442024 bytes of data
,2015-11-20T12:12:25.004Z SendDataTCPServer.js: TCP/IP server has received 5573096 bytes of data
,2015-11-20T12:12:25.008Z SendDataTCPServer.js: TCP/IP server has received 5704168 bytes of data
,2015-11-20T12:12:25.021Z SendDataTCPServer.js: TCP/IP server has received 5835240 bytes of data
,2015-11-20T12:12:25.027Z SendDataTCPServer.js: TCP/IP server has received 5966312 bytes of data
,2015-11-20T12:12:25.032Z SendDataTCPServer.js: TCP/IP server has received 6097384 bytes of data
,2015-11-20T12:12:25.036Z SendDataTCPServer.js: TCP/IP server has received 6228456 bytes of data
,2015-11-20T12:12:25.039Z SendDataTCPServer.js: TCP/IP server has received 6359528 bytes of data
,2015-11-20T12:12:25.044Z SendDataTCPServer.js: TCP/IP server has received 6490600 bytes of data
,2015-11-20T12:12:25.048Z SendDataTCPServer.js: TCP/IP server has received 6621672 bytes of data
,2015-11-20T12:12:25.052Z SendDataTCPServer.js: TCP/IP server has received 6752744 bytes of data
,2015-11-20T12:12:25.055Z SendDataTCPServer.js: TCP/IP server has received 6883816 bytes of data
,2015-11-20T12:12:25.058Z SendDataTCPServer.js: TCP/IP server has received 7014888 bytes of data
,2015-11-20T12:12:25.062Z SendDataTCPServer.js: TCP/IP server has received 7145960 bytes of data
,2015-11-20T12:12:25.065Z SendDataTCPServer.js: TCP/IP server has received 7277032 bytes of data
,2015-11-20T12:12:25.068Z SendDataTCPServer.js: TCP/IP server has received 7408104 bytes of data
,2015-11-20T12:12:25.071Z SendDataTCPServer.js: TCP/IP server has received 7539176 bytes of data
,2015-11-20T12:12:25.074Z SendDataTCPServer.js: TCP/IP server has received 7670248 bytes of data
,2015-11-20T12:12:25.079Z SendDataTCPServer.js: TCP/IP server has received 7801320 bytes of data
,2015-11-20T12:12:25.082Z SendDataTCPServer.js: TCP/IP server has received 7932392 bytes of data
,2015-11-20T12:12:25.086Z SendDataTCPServer.js: TCP/IP server has received 8063464 bytes of data
,2015-11-20T12:12:25.090Z SendDataTCPServer.js: TCP/IP server has received 8194536 bytes of data
,2015-11-20T12:12:25.094Z SendDataTCPServer.js: TCP/IP server has received 8325608 bytes of data
,2015-11-20T12:12:25.098Z SendDataTCPServer.js: TCP/IP server has received 8456680 bytes of data
,2015-11-20T12:12:25.102Z SendDataTCPServer.js: TCP/IP server has received 8587752 bytes of data
,2015-11-20T12:12:25.124Z SendDataTCPServer.js: TCP/IP server has received 8718824 bytes of data
,2015-11-20T12:12:25.139Z SendDataTCPServer.js: TCP/IP server has received 8849896 bytes of data
,2015-11-20T12:12:25.145Z SendDataTCPServer.js: TCP/IP server has received 8980968 bytes of data
,2015-11-20T12:12:25.148Z SendDataTCPServer.js: TCP/IP server has received 9112040 bytes of data
,2015-11-20T12:12:25.150Z SendDataTCPServer.js: TCP/IP server has received 9243112 bytes of data
,2015-11-20T12:12:25.153Z SendDataTCPServer.js: TCP/IP server has received 9374184 bytes of data
,2015-11-20T12:12:25.155Z SendDataTCPServer.js: TCP/IP server has received 9505256 bytes of data
,2015-11-20T12:12:25.157Z SendDataTCPServer.js: TCP/IP server has received 131072 bytes of data
,2015-11-20T12:12:25.161Z SendDataTCPServer.js: TCP/IP server has received 262144 bytes of data
,2015-11-20T12:12:25.165Z SendDataTCPServer.js: TCP/IP server has received 393216 bytes of data
,2015-11-20T12:12:25.168Z SendDataTCPServer.js: TCP/IP server has received 524288 bytes of data
,2015-11-20T12:12:25.171Z SendDataTCPServer.js: TCP/IP server has received 655360 bytes of data
,2015-11-20T12:12:25.175Z SendDataTCPServer.js: TCP/IP server has received 786432 bytes of data
,2015-11-20T12:12:25.178Z SendDataTCPServer.js: TCP/IP server has received 917504 bytes of data
,2015-11-20T12:12:25.182Z SendDataTCPServer.js: TCP/IP server has received 1048576 bytes of data
,2015-11-20T12:12:25.185Z SendDataTCPServer.js: TCP/IP server has received 1179648 bytes of data
,2015-11-20T12:12:25.189Z SendDataTCPServer.js: TCP/IP server has received 1310720 bytes of data
,2015-11-20T12:12:25.192Z SendDataTCPServer.js: TCP/IP server has received 1441792 bytes of data
,2015-11-20T12:12:25.195Z SendDataTCPServer.js: TCP/IP server has received 1572864 bytes of data
,2015-11-20T12:12:25.198Z SendDataTCPServer.js: TCP/IP server has received 1703936 bytes of data
,2015-11-20T12:12:25.201Z SendDataTCPServer.js: TCP/IP server has received 1835008 bytes of data
,2015-11-20T12:12:25.204Z SendDataTCPServer.js: TCP/IP server has received 1966080 bytes of data
,2015-11-20T12:12:25.207Z SendDataTCPServer.js: TCP/IP server has received 2097152 bytes of data
,2015-11-20T12:12:25.210Z SendDataTCPServer.js: TCP/IP server has received 2228224 bytes of data
,2015-11-20T12:12:25.213Z SendDataTCPServer.js: TCP/IP server has received 2359296 bytes of data
,2015-11-20T12:12:25.216Z SendDataTCPServer.js: TCP/IP server has received 2490368 bytes of data
,2015-11-20T12:12:25.220Z SendDataTCPServer.js: TCP/IP server has received 2621440 bytes of data
,2015-11-20T12:12:25.223Z SendDataTCPServer.js: TCP/IP server has received 2752512 bytes of data
,2015-11-20T12:12:25.225Z SendDataTCPServer.js: TCP/IP server has received 2883584 bytes of data
,2015-11-20T12:12:25.230Z SendDataTCPServer.js: TCP/IP server has received 3014656 bytes of data
,2015-11-20T12:12:25.233Z SendDataTCPServer.js: TCP/IP server has received 3145728 bytes of data
,2015-11-20T12:12:25.236Z SendDataTCPServer.js: TCP/IP server has received 3276800 bytes of data
,2015-11-20T12:12:25.240Z SendDataTCPServer.js: TCP/IP server has received 3407872 bytes of data
,2015-11-20T12:12:25.245Z SendDataTCPServer.js: TCP/IP server has received 3538944 bytes of data
,2015-11-20T12:12:25.248Z SendDataTCPServer.js: TCP/IP server has received 3670016 bytes of data
,2015-11-20T12:12:25.253Z SendDataTCPServer.js: TCP/IP server has received 3801088 bytes of data
,2015-11-20T12:12:25.257Z SendDataTCPServer.js: TCP/IP server has received 3932160 bytes of data
,2015-11-20T12:12:25.259Z SendDataTCPServer.js: TCP/IP server has received 4063232 bytes of data
,2015-11-20T12:12:25.262Z SendDataTCPServer.js: TCP/IP server has received 4194304 bytes of data
,2015-11-20T12:12:25.292Z SendDataTCPServer.js: TCP/IP server has received 9636328 bytes of data
,2015-11-20T12:12:25.296Z SendDataTCPServer.js: TCP/IP server has received 9767400 bytes of data
,2015-11-20T12:12:25.299Z SendDataTCPServer.js: TCP/IP server has received 9898472 bytes of data
,2015-11-20T12:12:25.303Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
2015-11-20T12:12:25.308Z SendDataTCPServer.js: TCP/IP server has received 4325376 bytes of data
2015-11-20T12:12:25.312Z SendDataTCPServer.js: TCP/IP server has received 4456448 bytes of data
,2015-11-20T12:12:25.319Z SendDataTCPServer.js: TCP/IP server has received 4587520 bytes of data
,2015-11-20T12:12:25.323Z SendDataTCPServer.js: TCP/IP server has received 4718592 bytes of data
2015-11-20T12:12:25.326Z SendDataTCPServer.js: TCP/IP server has received 4849664 bytes of data
,2015-11-20T12:12:25.330Z SendDataTCPServer.js: TCP/IP server has received 4980736 bytes of data
,2015-11-20T12:12:25.334Z SendDataTCPServer.js: TCP/IP server has received 5111808 bytes of data
,2015-11-20T12:12:25.338Z SendDataTCPServer.js: TCP/IP server has received 5242880 bytes of data
,2015-11-20T12:12:25.342Z SendDataTCPServer.js: TCP/IP server has received 5373952 bytes of data
,2015-11-20T12:12:25.346Z SendDataTCPServer.js: TCP/IP server has received 5505024 bytes of data
,2015-11-20T12:12:25.350Z SendDataTCPServer.js: TCP/IP server has received 5636096 bytes of data
,2015-11-20T12:12:25.353Z SendDataTCPServer.js: TCP/IP server has received 5767168 bytes of data
,2015-11-20T12:12:25.357Z SendDataTCPServer.js: TCP/IP server has received 5898240 bytes of data
,2015-11-20T12:12:25.361Z SendDataTCPServer.js: TCP/IP server has received 6029312 bytes of data
,2015-11-20T12:12:25.365Z SendDataTCPServer.js: TCP/IP server has received 6160384 bytes of data
,2015-11-20T12:12:25.369Z SendDataTCPServer.js: TCP/IP server has received 6291456 bytes of data
,2015-11-20T12:12:25.373Z SendDataTCPServer.js: TCP/IP server has received 6422528 bytes of data
,2015-11-20T12:12:25.378Z SendDataTCPServer.js: TCP/IP server has received 6553600 bytes of data
,2015-11-20T12:12:25.383Z SendDataTCPServer.js: TCP/IP server has received 6684672 bytes of data
,2015-11-20T12:12:25.400Z SendDataTCPServer.js: TCP/IP server has received 6815744 bytes of data
,2015-11-20T12:12:25.426Z SendDataTCPServer.js: TCP/IP server has received 6946816 bytes of data
,2015-11-20T12:12:25.438Z SendDataTCPServer.js: TCP/IP server has received 7077888 bytes of data
,2015-11-20T12:12:25.442Z SendDataTCPServer.js: TCP/IP server has received 7208960 bytes of data
,2015-11-20T12:12:25.447Z SendDataTCPServer.js: TCP/IP server has received 7340032 bytes of data
,2015-11-20T12:12:25.455Z SendDataTCPServer.js: TCP/IP server has received 7471104 bytes of data
,2015-11-20T12:12:25.459Z SendDataTCPServer.js: TCP/IP server has received 7602176 bytes of data
,2015-11-20T12:12:25.464Z SendDataTCPServer.js: TCP/IP server has received 7733248 bytes of data
,2015-11-20T12:12:25.469Z SendDataTCPServer.js: TCP/IP server has received 7864320 bytes of data
,2015-11-20T12:12:25.474Z SendDataTCPServer.js: TCP/IP server has received 7995392 bytes of data
,2015-11-20T12:12:25.478Z SendDataTCPServer.js: TCP/IP server has received 8126464 bytes of data
,2015-11-20T12:12:25.481Z SendDataTCPServer.js: TCP/IP server has received 8257536 bytes of data
,2015-11-20T12:12:25.487Z SendDataTCPServer.js: TCP/IP server has received 8388608 bytes of data
,2015-11-20T12:12:25.512Z SendDataTCPServer.js: TCP/IP server has received 8420550 bytes of data
,2015-11-20T12:12:25.749Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:12:25.749Z SendDataConnector.js: CLIENT is data received : 210000
,2015-11-20T12:12:25.785Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:12:25.785Z SendDataConnector.js: CLIENT is data received : 220000
,2015-11-20 13:12:26.400 ThaliTest[378:60b] multipeer session: reset timer
2015-11-20 13:12:26.400 ThaliTest[378:60b] multipeer session: stop timer
2015-11-20 13:12:26.402 ThaliTest[378:60b] multipeer session: start timer: 0x1cef1cb0
2015-11-20 13:12:26.,405 ThaliTest[378:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT497)
2015-11-20 13:12:26.405 ThaliTest[378:60b] server session: disconnect
2015-11-20 13:12:26.406 ThaliTest[378:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT,497
2015-11-20T12:12:26.408Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:12:26.408Z SendDataConnector.js: CLIENT is data received : 750000
,2015-11-20T12:12:26.421Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20T12:12:26.422Z SendDataTCPServer.js: TCP/IP server is close
,2015-11-20 13:12:28.288 ThaliTest[378:60b] server session: connect
,2015-11-20 13:12:28.289 ThaliTest[378:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT497
,2015-11-20 13:12:28.292 ThaliTest[378:60b] server: accepting invitation Apple-Iphone5s-1_PT497
,2015-11-20T12:12:28.294Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:12:28.294Z SendDataConnector.js: CLIENT is data received : 930000
,2015-11-20 13:12:29.592 ThaliTest[378:60b] multipeer session: reset timer
,2015-11-20 13:12:29.594 ThaliTest[378:60b] multipeer session: stop timer
2015-11-20 13:12:29.594 ThaliTest[378:60b] multipeer session: start timer: 0x1cef1cb0
2015-11-20T12:12:29.595Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-,1_PT2043.OU3s0w==
2015-11-20 13:12:29.595 ThaliTest[378:60b] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7072)
2015-11-20T12:12:29.596Z SendDataConnector.js: CLIENT is data received : 1930000
2015-11-20 13:12:29.596 ThaliTest[378:60b] s,erver session: disconnect
2015-11-20 13:12:29.597 ThaliTest[378:60b] server session: stateChange:2->0 Apple-IpadAir2-1_PT7072
,2015-11-20 13:12:29.603 ThaliTest[378:60b] server session: connect
,2015-11-20 13:12:29.605 ThaliTest[378:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT7072
,2015-11-20 13:12:29.608 ThaliTest[378:60b] server: accepting invitation Apple-IpadAir2-1_PT7072
,2015-11-20 13:12:29.609 ThaliTest[378:60b] multipeer session: reset timer
2015-11-20 13:12:29.609 ThaliTest[378:60b] multipeer session: stop timer
2015-11-20 13:12:29.610 ThaliTest[378:60b] multipeer session: start timer: 0x1cef1cb0
2015-11-20 13:12:29.,610 ThaliTest[378:60b] server session: connect
2015-11-20T12:12:29.611Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-20 13:12:29.611 ThaliTest[378:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT2043
2015-11-20T12:12:29.612Z SendDataTCPS,erver.js: TCP/IP server is close
,2015-11-20 13:12:29.616 ThaliTest[378:60b] server: accepting invitation Apple-Iphone6-1_PT2043
,2015-11-20T12:12:30.545Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:12:30.545Z SendDataConnector.js: CLIENT is data received : 3070000
,2015-11-20T12:12:31.184Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:12:31.185Z SendDataConnector.js: CLIENT is data received : 3500000
,2015-11-20T12:12:32.783Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:12:32.784Z SendDataConnector.js: CLIENT is data received : 4830000
,2015-11-20T12:12:33.256Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:12:33.257Z SendDataConnector.js: CLIENT is data received : 5130000
,2015-11-20 13:12:33.391 ThaliTest[378:8f37] server session: connected
2015-11-20 13:12:33.393 ThaliTest[378:8f37] server session: stateChange:1->2 Apple-Iphone6-1_PT2043
,2015-11-20T12:12:33.414Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:12:34.615 ThaliTest[378:60b] server relay: connected (to port: 53117)
,2015-11-20T12:12:34.628Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:12:34.629Z SendDataConnector.js: CLIENT is data received : 5240000
,2015-11-20 13:12:35.485 ThaliTest[378:912f] server session: connected
2015-11-20 13:12:35.486 ThaliTest[378:912f] server session: stateChange:1->2 Apple-IpadAir2-1_PT7072
,2015-11-20T12:12:35.507Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:12:35.635 ThaliTest[378:60b] server relay: connected (to port: 53117)
,2015-11-20T12:12:37.582Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-11-20T12:12:37.596Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-11-20T12:12:37.609Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-11-20T12:12:37.622Z SendDataTCPServer.js: TCP/IP server has received 93460 bytes of data
,2015-11-20T12:12:37.638Z SendDataTCPServer.js: TCP/IP server has received 119172 bytes of data
,2015-11-20T12:12:37.651Z SendDataTCPServer.js: TCP/IP server has received 166298 bytes of data
,2015-11-20T12:12:37.664Z SendDataTCPServer.js: TCP/IP server has received 190388 bytes of data
,2015-11-20T12:12:37.677Z SendDataTCPServer.js: TCP/IP server has received 221190 bytes of data
,2015-11-20T12:12:37.690Z SendDataTCPServer.js: TCP/IP server has received 242238 bytes of data
,2015-11-20T12:12:37.703Z SendDataTCPServer.js: TCP/IP server has received 315360 bytes of data
,2015-11-20T12:12:37.717Z SendDataTCPServer.js: TCP/IP server has received 363398 bytes of data
,2015-11-20T12:12:37.730Z SendDataTCPServer.js: TCP/IP server has received 405150 bytes of data
,2015-11-20T12:12:37.760Z SendDataTCPServer.js: TCP/IP server has received 439480 bytes of data
,2015-11-20T12:12:37.775Z SendDataTCPServer.js: TCP/IP server has received 464280 bytes of data
,2015-11-20T12:12:37.789Z SendDataTCPServer.js: TCP/IP server has received 501226 bytes of data
,2015-11-20T12:12:37.803Z SendDataTCPServer.js: TCP/IP server has received 534360 bytes of data
,2015-11-20T12:12:37.818Z SendDataTCPServer.js: TCP/IP server has received 574266 bytes of data
,2015-11-20T12:12:37.834Z SendDataTCPServer.js: TCP/IP server has received 611010 bytes of data
,2015-11-20T12:12:37.848Z SendDataTCPServer.js: TCP/IP server has received 636864 bytes of data
,2015-11-20T12:12:37.862Z SendDataTCPServer.js: TCP/IP server has received 667098 bytes of data
,2015-11-20T12:12:37.875Z SendDataTCPServer.js: TCP/IP server has received 698610 bytes of data
,2015-11-20T12:12:37.889Z SendDataTCPServer.js: TCP/IP server has received 724890 bytes of data
,2015-11-20T12:12:37.900Z SendDataTCPServer.js: TCP/IP server has received 766500 bytes of data
,2015-11-20T12:12:37.914Z SendDataTCPServer.js: TCP/IP server has received 825630 bytes of data
,2015-11-20T12:12:37.952Z SendDataTCPServer.js: TCP/IP server has received 840960 bytes of data
,2015-11-20T12:12:38.025Z SendDataTCPServer.js: TCP/IP server has received 873384 bytes of data
,2015-11-20T12:12:38.037Z SendDataTCPServer.js: TCP/IP server has received 873810 bytes of data
,2015-11-20T12:12:38.095Z SendDataTCPServer.js: TCP/IP server has received 880380 bytes of data
,2015-11-20T12:12:38.109Z SendDataTCPServer.js: TCP/IP server has received 906660 bytes of data
,2015-11-20T12:12:38.122Z SendDataTCPServer.js: TCP/IP server has received 948270 bytes of data
,2015-11-20T12:12:38.138Z SendDataTCPServer.js: TCP/IP server has received 970028 bytes of data
,2015-11-20T12:12:38.150Z SendDataTCPServer.js: TCP/IP server has received 993692 bytes of data
,2015-11-20T12:12:38.163Z SendDataTCPServer.js: TCP/IP server has received 1022588 bytes of data
,2015-11-20T12:12:38.177Z SendDataTCPServer.js: TCP/IP server has received 1059960 bytes of data
,2015-11-20T12:12:38.191Z SendDataTCPServer.js: TCP/IP server has received 1086240 bytes of data
,2015-11-20T12:12:38.205Z SendDataTCPServer.js: TCP/IP server has received 1114710 bytes of data
,2015-11-20T12:12:38.217Z SendDataTCPServer.js: TCP/IP server has received 1134420 bytes of data
,2015-11-20T12:12:38.230Z SendDataTCPServer.js: TCP/IP server has received 1165080 bytes of data
,2015-11-20T12:12:38.243Z SendDataTCPServer.js: TCP/IP server has received 1189028 bytes of data
,2015-11-20T12:12:38.256Z SendDataTCPServer.js: TCP/IP server has received 1225974 bytes of data
,2015-11-20T12:12:38.269Z SendDataTCPServer.js: TCP/IP server has received 1270200 bytes of data
,2015-11-20T12:12:38.283Z SendDataTCPServer.js: TCP/IP server has received 1303050 bytes of data
,2015-11-20T12:12:38.297Z SendDataTCPServer.js: TCP/IP server has received 1344660 bytes of data
,2015-11-20T12:12:38.311Z SendDataTCPServer.js: TCP/IP server has received 1370940 bytes of data
,2015-11-20T12:12:38.325Z SendDataTCPServer.js: TCP/IP server has received 1390508 bytes of data
,2015-11-20T12:12:38.338Z SendDataTCPServer.js: TCP/IP server has received 1434450 bytes of data
,2015-11-20T12:12:38.353Z SendDataTCPServer.js: TCP/IP server has received 1458540 bytes of data
,2015-11-20T12:12:38.367Z SendDataTCPServer.js: TCP/IP server has received 1487010 bytes of data
,2015-11-20T12:12:38.381Z SendDataTCPServer.js: TCP/IP server has received 1515480 bytes of data
,2015-11-20T12:12:38.394Z SendDataTCPServer.js: TCP/IP server has received 1535190 bytes of data
,2015-11-20T12:12:38.406Z SendDataTCPServer.js: TCP/IP server has received 1561470 bytes of data
,2015-11-20T12:12:38.420Z SendDataTCPServer.js: TCP/IP server has received 1600890 bytes of data
,2015-11-20T12:12:38.432Z SendDataTCPServer.js: TCP/IP server has received 1627170 bytes of data
,2015-11-20T12:12:38.445Z SendDataTCPServer.js: TCP/IP server has received 1673160 bytes of data
,2015-11-20T12:12:38.459Z SendDataTCPServer.js: TCP/IP server has received 1712580 bytes of data
,2015-11-20T12:12:38.475Z SendDataTCPServer.js: TCP/IP server has received 1716960 bytes of data
,2015-11-20T12:12:38.488Z SendDataTCPServer.js: TCP/IP server has received 1747336 bytes of data
,2015-11-20T12:12:38.500Z SendDataTCPServer.js: TCP/IP server has received 1749810 bytes of data
,2015-11-20T12:12:38.535Z SendDataTCPServer.js: TCP/IP server has received 1765140 bytes of data
,2015-11-20T12:12:38.640Z SendDataTCPServer.js: TCP/IP server has received 1813178 bytes of data
,2015-11-20T12:12:38.655Z SendDataTCPServer.js: TCP/IP server has received 1826460 bytes of data
,2015-11-20T12:12:38.680Z SendDataTCPServer.js: TCP/IP server has received 1850550 bytes of data
,2015-11-20T12:12:38.692Z SendDataTCPServer.js: TCP/IP server has received 1889970 bytes of data
,2015-11-20T12:12:38.705Z SendDataTCPServer.js: TCP/IP server has received 1903110 bytes of data
,2015-11-20T12:12:38.729Z SendDataTCPServer.js: TCP/IP server has received 1909680 bytes of data
,2015-11-20T12:12:38.742Z SendDataTCPServer.js: TCP/IP server has received 1940340 bytes of data
,2015-11-20T12:12:38.757Z SendDataTCPServer.js: TCP/IP server has received 1960050 bytes of data
,2015-11-20T12:12:38.771Z SendDataTCPServer.js: TCP/IP server has received 1986330 bytes of data
,2015-11-20T12:12:38.784Z SendDataTCPServer.js: TCP/IP server has received 2014658 bytes of data
,2015-11-20T12:12:38.798Z SendDataTCPServer.js: TCP/IP server has received 2054220 bytes of data
,2015-11-20T12:12:38.811Z SendDataTCPServer.js: TCP/IP server has received 2073930 bytes of data
,2015-11-20T12:12:38.825Z SendDataTCPServer.js: TCP/IP server has received 2093498 bytes of data
,2015-11-20T12:12:38.838Z SendDataTCPServer.js: TCP/IP server has received 2119920 bytes of data
,2015-11-20T12:12:38.850Z SendDataTCPServer.js: TCP/IP server has received 2146200 bytes of data
,2015-11-20T12:12:38.863Z SendDataTCPServer.js: TCP/IP server has received 2176860 bytes of data
,2015-11-20T12:12:38.876Z SendDataTCPServer.js: TCP/IP server has received 2198618 bytes of data
,2015-11-20T12:12:38.889Z SendDataTCPServer.js: TCP/IP server has received 2220660 bytes of data
,2015-11-20T12:12:38.901Z SendDataTCPServer.js: TCP/IP server has received 2240370 bytes of data
,2015-11-20T12:12:38.914Z SendDataTCPServer.js: TCP/IP server has received 2268840 bytes of data
,2015-11-20T12:12:38.927Z SendDataTCPServer.js: TCP/IP server has received 2303880 bytes of data
,2015-11-20T12:12:38.939Z SendDataTCPServer.js: TCP/IP server has received 2332208 bytes of data
,2015-11-20T12:12:38.951Z SendDataTCPServer.js: TCP/IP server has received 2380530 bytes of data
,2015-11-20T12:12:38.964Z SendDataTCPServer.js: TCP/IP server has received 2402288 bytes of data
,2015-11-20T12:12:38.976Z SendDataTCPServer.js: TCP/IP server has received 2422140 bytes of data
,2015-11-20T12:12:38.988Z SendDataTCPServer.js: TCP/IP server has received 2448278 bytes of data
,2015-11-20T12:12:39.002Z SendDataTCPServer.js: TCP/IP server has received 2479080 bytes of data
,2015-11-20T12:12:39.015Z SendDataTCPServer.js: TCP/IP server has received 2549160 bytes of data
,2015-11-20T12:12:39.029Z SendDataTCPServer.js: TCP/IP server has received 2590770 bytes of data
,2015-11-20T12:12:39.041Z SendDataTCPServer.js: TCP/IP server has received 2619240 bytes of data
,2015-11-20T12:12:39.166Z SendDataTCPServer.js: TCP/IP server has received 2625384 bytes of data
,2015-11-20T12:12:39.179Z SendDataTCPServer.js: TCP/IP server has received 2653996 bytes of data
,2015-11-20T12:12:39.194Z SendDataTCPServer.js: TCP/IP server has received 2680560 bytes of data
,2015-11-20T12:12:39.208Z SendDataTCPServer.js: TCP/IP server has received 2722170 bytes of data
,2015-11-20T12:12:39.222Z SendDataTCPServer.js: TCP/IP server has received 2744070 bytes of data
,2015-11-20T12:12:39.236Z SendDataTCPServer.js: TCP/IP server has received 2774730 bytes of data
,2015-11-20T12:12:39.248Z SendDataTCPServer.js: TCP/IP server has received 2805390 bytes of data
,2015-11-20T12:12:39.261Z SendDataTCPServer.js: TCP/IP server has received 2844810 bytes of data
,2015-11-20T12:12:39.275Z SendDataTCPServer.js: TCP/IP server has received 2875470 bytes of data
,2015-11-20T12:12:39.288Z SendDataTCPServer.js: TCP/IP server has received 2901608 bytes of data
,2015-11-20T12:12:39.301Z SendDataTCPServer.js: TCP/IP server has received 2930220 bytes of data
,2015-11-20T12:12:39.314Z SendDataTCPServer.js: TCP/IP server has received 2956500 bytes of data
,2015-11-20T12:12:39.327Z SendDataTCPServer.js: TCP/IP server has received 2995778 bytes of data
,2015-11-20T12:12:39.340Z SendDataTCPServer.js: TCP/IP server has received 3020010 bytes of data
,2015-11-20T12:12:39.352Z SendDataTCPServer.js: TCP/IP server has received 3039578 bytes of data
,2015-11-20T12:12:39.365Z SendDataTCPServer.js: TCP/IP server has received 3072428 bytes of data
,2015-11-20T12:12:39.378Z SendDataTCPServer.js: TCP/IP server has received 3101040 bytes of data
,2015-11-20T12:12:39.392Z SendDataTCPServer.js: TCP/IP server has received 3131700 bytes of data
,2015-11-20T12:12:39.406Z SendDataTCPServer.js: TCP/IP server has received 3162360 bytes of data
,2015-11-20T12:12:39.419Z SendDataTCPServer.js: TCP/IP server has received 3190830 bytes of data
,2015-11-20T12:12:39.433Z SendDataTCPServer.js: TCP/IP server has received 3217110 bytes of data
,2015-11-20T12:12:39.447Z SendDataTCPServer.js: TCP/IP server has received 3247486 bytes of data
,2015-11-20T12:12:39.460Z SendDataTCPServer.js: TCP/IP server has received 3280620 bytes of data
,2015-11-20T12:12:39.473Z SendDataTCPServer.js: TCP/IP server has received 3315518 bytes of data
,2015-11-20T12:12:39.488Z SendDataTCPServer.js: TCP/IP server has received 3346320 bytes of data
,2015-11-20T12:12:39.501Z SendDataTCPServer.js: TCP/IP server has received 3390120 bytes of data
,2015-11-20T12:12:39.513Z SendDataTCPServer.js: TCP/IP server has received 3401070 bytes of data
,2015-11-20T12:12:39.525Z SendDataTCPServer.js: TCP/IP server has received 3422970 bytes of data
,2015-11-20T12:12:39.538Z SendDataTCPServer.js: TCP/IP server has received 3440490 bytes of data
,2015-11-20T12:12:39.550Z SendDataTCPServer.js: TCP/IP server has received 3464580 bytes of data
,2015-11-20T12:12:39.564Z SendDataTCPServer.js: TCP/IP server has received 3517140 bytes of data
,2015-11-20T12:12:39.579Z SendDataTCPServer.js: TCP/IP server has received 3536850 bytes of data
,2015-11-20T12:12:39.599Z SendDataTCPServer.js: TCP/IP server has received 3565320 bytes of data
,2015-11-20T12:12:39.628Z SendDataTCPServer.js: TCP/IP server has received 3567510 bytes of data
,2015-11-20T12:12:39.629Z SendDataTCPServer.js: TCP/IP server has received 83280 bytes of data
,2015-11-20T12:12:39.651Z SendDataTCPServer.js: TCP/IP server has received 3569700 bytes of data
,2015-11-20T12:12:39.653Z SendDataTCPServer.js: TCP/IP server has received 190530 bytes of data
,2015-11-20T12:12:39.669Z SendDataTCPServer.js: TCP/IP server has received 3611310 bytes of data
,2015-11-20T12:12:39.683Z SendDataTCPServer.js: TCP/IP server has received 3654968 bytes of data
,2015-11-20T12:12:39.697Z SendDataTCPServer.js: TCP/IP server has received 3687960 bytes of data
,2015-11-20T12:12:39.779Z SendDataTCPServer.js: TCP/IP server has received 208962 bytes of data
,2015-11-20T12:12:39.819Z SendDataTCPServer.js: TCP/IP server has received 242522 bytes of data
,2015-11-20T12:12:39.822Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:12:39.826Z SendDataConnector.js: CLIENT is data received : 5250000
,2015-11-20T12:12:39.860Z SendDataTCPServer.js: TCP/IP server has received 282510 bytes of data
,2015-11-20T12:12:39.888Z SendDataTCPServer.js: TCP/IP server has received 413582 bytes of data
,2015-11-20T12:12:39.890Z SendDataTCPServer.js: TCP/IP server has received 484902 bytes of data
,2015-11-20T12:12:39.893Z SendDataTCPServer.js: TCP/IP server has received 3716430 bytes of data
,2015-11-20T12:12:39.908Z SendDataTCPServer.js: TCP/IP server has received 580350 bytes of data
,2015-11-20T12:12:39.912Z SendDataTCPServer.js: TCP/IP server has received 3744900 bytes of data
,2015-11-20T12:12:39.925Z SendDataTCPServer.js: TCP/IP server has received 3762420 bytes of data
,2015-11-20T12:12:39.937Z SendDataTCPServer.js: TCP/IP server has received 3799650 bytes of data
,2015-11-20T12:12:39.954Z SendDataTCPServer.js: TCP/IP server has received 3843450 bytes of data
,2015-11-20T12:12:39.967Z SendDataTCPServer.js: TCP/IP server has received 3869730 bytes of data
,2015-11-20T12:12:39.980Z SendDataTCPServer.js: TCP/IP server has received 3887108 bytes of data
,2015-11-20T12:12:39.982Z SendDataTCPServer.js: TCP/IP server has received 584730 bytes of data
,2015-11-20T12:12:39.995Z SendDataTCPServer.js: TCP/IP server has received 3926528 bytes of data
,2015-11-20T12:12:40.010Z SendDataTCPServer.js: TCP/IP server has received 3937620 bytes of data
,2015-11-20T12:12:40.011Z SendDataTCPServer.js: TCP/IP server has received 624494 bytes of data
,2015-11-20T12:12:40.027Z SendDataTCPServer.js: TCP/IP server has received 669572 bytes of data
,2015-11-20T12:12:40.040Z SendDataTCPServer.js: TCP/IP server has received 727080 bytes of data
,2015-11-20T12:12:40.042Z SendDataTCPServer.js: TCP/IP server has received 3961710 bytes of data
,2015-11-20T12:12:40.055Z SendDataTCPServer.js: TCP/IP server has received 3987990 bytes of data
,2015-11-20T12:12:40.071Z SendDataTCPServer.js: TCP/IP server has received 4009890 bytes of data
,2015-11-20T12:12:40.072Z SendDataTCPServer.js: TCP/IP server has received 735840 bytes of data
,2015-11-20T12:12:40.085Z SendDataTCPServer.js: TCP/IP server has received 4016460 bytes of data
,2015-11-20T12:12:40.086Z SendDataTCPServer.js: TCP/IP server has received 757740 bytes of data
,2015-11-20T12:12:40.099Z SendDataTCPServer.js: TCP/IP server has received 788400 bytes of data
,2015-11-20T12:12:40.114Z SendDataTCPServer.js: TCP/IP server has received 819060 bytes of data
,2015-11-20T12:12:40.115Z SendDataTCPServer.js: TCP/IP server has received 4020840 bytes of data
,2015-11-20T12:12:40.129Z SendDataTCPServer.js: TCP/IP server has received 838770 bytes of data
,2015-11-20T12:12:40.130Z SendDataTCPServer.js: TCP/IP server has received 4036028 bytes of data
,2015-11-20T12:12:40.144Z SendDataTCPServer.js: TCP/IP server has received 849720 bytes of data
,2015-11-20T12:12:40.144Z SendDataTCPServer.js: TCP/IP server has received 4071980 bytes of data
,2015-11-20T12:12:40.158Z SendDataTCPServer.js: TCP/IP server has received 878190 bytes of data
,2015-11-20T12:12:40.162Z SendDataTCPServer.js: TCP/IP server has received 4101870 bytes of data
,2015-11-20T12:12:40.188Z SendDataTCPServer.js: TCP/IP server has received 4106250 bytes of data
,2015-11-20T12:12:40.205Z SendDataTCPServer.js: TCP/IP server has received 4136910 bytes of data
,2015-11-20T12:12:40.221Z SendDataTCPServer.js: TCP/IP server has received 4147860 bytes of data
,2015-11-20T12:12:40.235Z SendDataTCPServer.js: TCP/IP server has received 4158810 bytes of data
,2015-11-20T12:12:40.237Z SendDataTCPServer.js: TCP/IP server has received 882570 bytes of data
,2015-11-20T12:12:40.253Z SendDataTCPServer.js: TCP/IP server has received 4174140 bytes of data
,2015-11-20T12:12:40.255Z SendDataTCPServer.js: TCP/IP server has received 893520 bytes of data
,2015-11-20T12:12:40.257Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:12:40.257Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:12:40.258Z SendDataConnector.js: got all data for this round
,2015-11-20T12:12:40.258Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:12:40.259Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:12:40.260 ThaliTest[378:6a07] jxcore: disconnect
,2015-11-20 13:12:40.267 ThaliTest[378:6a07] client session: disconnectFromPeer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:12:40.269 ThaliTest[378:6a07] client session: disconnect
,2015-11-20 13:12:40.272 ThaliTest[378:6a07] client session: stateChange:2->0 Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:12:40.279 ThaliTest[378:6a07] jxcore: disconnect: success
,2015-11-20T12:12:40.283Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2043.OU3s0w==
,---- round done--------
,device[3]: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:12:40.289Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:12:40.290Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:12:40.308Z SendDataTCPServer.js: TCP/IP server has received 959220 bytes of data
,2015-11-20T12:12:40.313Z SendDataConnector.js: CLIENT is closed
,2015-11-20T12:12:40.333Z SendDataTCPServer.js: TCP/IP server has received 1000830 bytes of data
,2015-11-20T12:12:40.335Z SendDataTCPServer.js: TCP/IP server has received 4176330 bytes of data
,2015-11-20T12:12:40.348Z SendDataTCPServer.js: TCP/IP server has received 1029300 bytes of data
,2015-11-20T12:12:40.361Z SendDataTCPServer.js: TCP/IP server has received 1048868 bytes of data
,2015-11-20T12:12:40.363Z SendDataTCPServer.js: TCP/IP server has received 4182900 bytes of data
,2015-11-20T12:12:40.388Z SendDataTCPServer.js: TCP/IP server has received 1077480 bytes of data
,2015-11-20T12:12:40.393Z SendDataTCPServer.js: TCP/IP server has received 4213560 bytes of data
,2015-11-20T12:12:40.436Z SendDataTCPServer.js: TCP/IP server has received 1079670 bytes of data
,2015-11-20T12:12:40.446Z SendDataTCPServer.js: TCP/IP server has received 4342770 bytes of data
,2015-11-20T12:12:40.496Z SendDataTCPServer.js: TCP/IP server has received 1101570 bytes of data
,2015-11-20T12:12:40.501Z SendDataTCPServer.js: TCP/IP server has received 4441320 bytes of data
,2015-11-20T12:12:40.524Z SendDataTCPServer.js: TCP/IP server has received 1156036 bytes of data
,2015-11-20T12:12:40.539Z SendDataTCPServer.js: TCP/IP server has received 1214882 bytes of data
,2015-11-20T12:12:40.542Z SendDataTCPServer.js: TCP/IP server has received 4443510 bytes of data
,2015-11-20T12:12:40.555Z SendDataTCPServer.js: TCP/IP server has received 1263346 bytes of data
,2015-11-20T12:12:40.559Z SendDataTCPServer.js: TCP/IP server has received 4445700 bytes of data
,2015-11-20T12:12:40.573Z SendDataTCPServer.js: TCP/IP server has received 1309478 bytes of data
,2015-11-20T12:12:40.575Z SendDataTCPServer.js: TCP/IP server has received 4452270 bytes of data
,2015-11-20T12:12:40.590Z SendDataTCPServer.js: TCP/IP server has received 1335900 bytes of data
,2015-11-20T12:12:40.591Z SendDataTCPServer.js: TCP/IP server has received 4478550 bytes of data
,2015-11-20T12:12:40.606Z SendDataTCPServer.js: TCP/IP server has received 4515780 bytes of data
,2015-11-20T12:12:40.621Z SendDataTCPServer.js: TCP/IP server has received 4557390 bytes of data
,2015-11-20T12:12:40.622Z SendDataTCPServer.js: TCP/IP server has received 1342470 bytes of data
,2015-11-20T12:12:40.634Z SendDataTCPServer.js: TCP/IP server has received 4566150 bytes of data
,2015-11-20T12:12:40.636Z SendDataTCPServer.js: TCP/IP server has received 1370940 bytes of data
,2015-11-20T12:12:40.650Z SendDataTCPServer.js: TCP/IP server has received 4583670 bytes of data
,2015-11-20T12:12:40.652Z SendDataTCPServer.js: TCP/IP server has received 1375320 bytes of data
,2015-11-20 13:12:40.697 ThaliTest[378:60b] client: lost peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:12:40.699 ThaliTest[378:60b] client session: onPeerLost: Apple-Iphone6-1_PT2043.OU3s0w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":false}]
,2015-11-20T12:12:40.759Z SendDataTCPServer.js: TCP/IP server has received 1386270 bytes of data
,2015-11-20T12:12:40.773Z SendDataTCPServer.js: TCP/IP server has received 1392840 bytes of data
2015-11-20T12:12:40.774Z SendDataTCPServer.js: TCP/IP server has received 4603380 bytes of data
,2015-11-20T12:12:40.787Z SendDataTCPServer.js: TCP/IP server has received 1399268 bytes of data
2015-11-20T12:12:40.789Z SendDataTCPServer.js: TCP/IP server has received 4614330 bytes of data
,2015-11-20T12:12:40.803Z SendDataTCPServer.js: TCP/IP server has received 1421310 bytes of data
2015-11-20T12:12:40.805Z SendDataTCPServer.js: TCP/IP server has received 4631850 bytes of data
,2015-11-20T12:12:40.820Z SendDataTCPServer.js: TCP/IP server has received 1431976 bytes of data
2015-11-20T12:12:40.821Z SendDataTCPServer.js: TCP/IP server has received 4651560 bytes of data
,2015-11-20T12:12:40.835Z SendDataTCPServer.js: TCP/IP server has received 1451686 bytes of data
2015-11-20T12:12:40.836Z SendDataTCPServer.js: TCP/IP server has received 4671270 bytes of data
,2015-11-20T12:12:40.850Z SendDataTCPServer.js: TCP/IP server has received 1465110 bytes of data
2015-11-20T12:12:40.851Z SendDataTCPServer.js: TCP/IP server has received 4681794 bytes of data
,2015-11-20T12:12:40.865Z SendDataTCPServer.js: TCP/IP server has received 1500150 bytes of data
,2015-11-20T12:12:40.866Z SendDataTCPServer.js: TCP/IP server has received 4690002 bytes of data
,2015-11-20T12:12:40.879Z SendDataTCPServer.js: TCP/IP server has received 1532858 bytes of data
,2015-11-20T12:12:40.893Z SendDataTCPServer.js: TCP/IP server has received 1570088 bytes of data
,2015-11-20 13:12:40.899 ThaliTest[378:8a23] server session: not connected Apple-IpadAir2-1_PT7072
,2015-11-20T12:12:40.906Z SendDataTCPServer.js: TCP/IP server has received 1589940 bytes of data
,2015-11-20T12:12:40.920Z SendDataTCPServer.js: TCP/IP server has received 1627028 bytes of data
,2015-11-20T12:12:40.933Z SendDataTCPServer.js: TCP/IP server has received 1657830 bytes of data
,2015-11-20T12:12:40.946Z SendDataTCPServer.js: TCP/IP server has received 1690680 bytes of data
,2015-11-20T12:12:40.961Z SendDataTCPServer.js: TCP/IP server has received 1719008 bytes of data
,2015-11-20T12:12:40.975Z SendDataTCPServer.js: TCP/IP server has received 1745430 bytes of data
,2015-11-20T12:12:40.988Z SendDataTCPServer.js: TCP/IP server has received 1776090 bytes of data
,2015-11-20T12:12:41.004Z SendDataTCPServer.js: TCP/IP server has received 1806750 bytes of data
,2015-11-20T12:12:41.020Z SendDataTCPServer.js: TCP/IP server has received 1849840 bytes of data
,2015-11-20T12:12:41.033Z SendDataTCPServer.js: TCP/IP server has received 1898730 bytes of data
,2015-11-20T12:12:41.047Z SendDataTCPServer.js: TCP/IP server has received 1925010 bytes of data
,2015-11-20T12:12:41.063Z SendDataTCPServer.js: TCP/IP server has received 1979760 bytes of data
,2015-11-20T12:12:41.077Z SendDataTCPServer.js: TCP/IP server has received 2006040 bytes of data
,2015-11-20T12:12:41.089Z SendDataTCPServer.js: TCP/IP server has received 2016990 bytes of data
,2015-11-20T12:12:41.101Z SendDataTCPServer.js: TCP/IP server has received 2034510 bytes of data
,2015-11-20T12:12:41.115Z SendDataTCPServer.js: TCP/IP server has received 2078310 bytes of data
,2015-11-20T12:12:41.129Z SendDataTCPServer.js: TCP/IP server has received 2113350 bytes of data
,2015-11-20T12:12:41.142Z SendDataTCPServer.js: TCP/IP server has received 2139488 bytes of data
,2015-11-20T12:12:41.156Z SendDataTCPServer.js: TCP/IP server has received 2141820 bytes of data
,2015-11-20T12:12:41.246Z SendDataTCPServer.js: TCP/IP server has received 2165910 bytes of data
,2015-11-20T12:12:41.260Z SendDataTCPServer.js: TCP/IP server has received 2183430 bytes of data
,2015-11-20T12:12:41.274Z SendDataTCPServer.js: TCP/IP server has received 2211616 bytes of data
,2015-11-20T12:12:41.287Z SendDataTCPServer.js: TCP/IP server has received 2240370 bytes of data
,2015-11-20 13:12:41.302 ThaliTest[378:6a07] jxcore: disconnect
,2015-11-20 13:12:41.304 ThaliTest[378:6a07] jxcore: disconnect: fail
,2015-11-20T12:12:41.305Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:12:41.306Z SendDataConnector.js: Connect (retry count 0) to peer Apple-IpadAir2-1_PT7072.5zbvNA== with availability status: true
2015-11-20T12:12:41.306Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:12:41.306Z SendDataConnector.js: do connect now
,2015-11-20 13:12:41.306 ThaliTest[378:6a07] jxcore: connect Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:12:41.308 ThaliTest[378:6a07] client session: connect
,2015-11-20 13:12:41.309 ThaliTest[378:6a07] client session: stateChange:0->1 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:12:41.315Z SendDataTCPServer.js: TCP/IP server has received 2275410 bytes of data
,2015-11-20T12:12:41.331Z SendDataTCPServer.js: TCP/IP server has received 2284170 bytes of data
,2015-11-20T12:12:41.344Z SendDataTCPServer.js: TCP/IP server has received 2303880 bytes of data
,2015-11-20T12:12:41.357Z SendDataTCPServer.js: TCP/IP server has received 2338920 bytes of data
,2015-11-20T12:12:41.372Z SendDataTCPServer.js: TCP/IP server has received 2377914 bytes of data
,2015-11-20T12:12:41.385Z SendDataTCPServer.js: TCP/IP server has received 2404620 bytes of data
,2015-11-20T12:12:41.398Z SendDataTCPServer.js: TCP/IP server has received 2435280 bytes of data
,2015-11-20T12:12:41.412Z SendDataTCPServer.js: TCP/IP server has received 2472368 bytes of data
,2015-11-20T12:12:41.425Z SendDataTCPServer.js: TCP/IP server has received 2498790 bytes of data
,2015-11-20T12:12:41.439Z SendDataTCPServer.js: TCP/IP server has received 2533688 bytes of data
,2015-11-20 13:12:41.449 ThaliTest[378:60b] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:12:41.452Z SendDataTCPServer.js: TCP/IP server has received 2557920 bytes of data
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
,2015-11-20T12:12:41.464Z SendDataTCPServer.js: TCP/IP server has received 2584058 bytes of data
,2015-11-20T12:12:41.478Z SendDataTCPServer.js: TCP/IP server has received 2623336 bytes of data
,2015-11-20T12:12:41.490Z SendDataTCPServer.js: TCP/IP server has received 2660708 bytes of data
,2015-11-20T12:12:41.503Z SendDataTCPServer.js: TCP/IP server has received 2684940 bytes of data
,2015-11-20T12:12:41.516Z SendDataTCPServer.js: TCP/IP server has received 2702460 bytes of data
,2015-11-20T12:12:41.529Z SendDataTCPServer.js: TCP/IP server has received 2726550 bytes of data
,2015-11-20T12:12:41.542Z SendDataTCPServer.js: TCP/IP server has received 2748450 bytes of data
,2015-11-20T12:12:41.555Z SendDataTCPServer.js: TCP/IP server has received 2774730 bytes of data
,2015-11-20T12:12:41.567Z SendDataTCPServer.js: TCP/IP server has received 2814008 bytes of data
,2015-11-20T12:12:41.581Z SendDataTCPServer.js: TCP/IP server has received 2860140 bytes of data
,2015-11-20T12:12:41.595Z SendDataTCPServer.js: TCP/IP server has received 2888610 bytes of data
,2015-11-20T12:12:41.608Z SendDataTCPServer.js: TCP/IP server has received 2917080 bytes of data
,2015-11-20T12:12:41.622Z SendDataTCPServer.js: TCP/IP server has received 2967450 bytes of data
,2015-11-20T12:12:41.637Z SendDataTCPServer.js: TCP/IP server has received 2978400 bytes of data
,2015-11-20T12:12:41.650Z SendDataTCPServer.js: TCP/IP server has received 3017820 bytes of data
,2015-11-20T12:12:41.666Z SendDataTCPServer.js: TCP/IP server has received 3044100 bytes of data
,2015-11-20T12:12:41.687Z SendDataTCPServer.js: TCP/IP server has received 3076950 bytes of data
,2015-11-20T12:12:41.769Z SendDataTCPServer.js: TCP/IP server has received 3105420 bytes of data
,2015-11-20T12:12:41.787Z SendDataTCPServer.js: TCP/IP server has received 3142650 bytes of data
,2015-11-20T12:12:41.800Z SendDataTCPServer.js: TCP/IP server has received 3153458 bytes of data
,2015-11-20T12:12:41.813Z SendDataTCPServer.js: TCP/IP server has received 3168930 bytes of data
,2015-11-20T12:12:41.826Z SendDataTCPServer.js: TCP/IP server has received 3177406 bytes of data
,2015-11-20T12:12:41.839Z SendDataTCPServer.js: TCP/IP server has received 3223538 bytes of data
,2015-11-20T12:12:41.852Z SendDataTCPServer.js: TCP/IP server has received 3247770 bytes of data
,2015-11-20T12:12:41.867Z SendDataTCPServer.js: TCP/IP server has received 3267480 bytes of data
,2015-11-20T12:12:41.881Z SendDataTCPServer.js: TCP/IP server has received 3304710 bytes of data
,2015-11-20T12:12:41.895Z SendDataTCPServer.js: TCP/IP server has received 3322088 bytes of data
,2015-11-20T12:12:41.908Z SendDataTCPServer.js: TCP/IP server has received 3348510 bytes of data
,2015-11-20T12:12:41.921Z SendDataTCPServer.js: TCP/IP server has received 3376980 bytes of data
,2015-11-20T12:12:41.935Z SendDataTCPServer.js: TCP/IP server has received 3412020 bytes of data
,2015-11-20T12:12:41.947Z SendDataTCPServer.js: TCP/IP server has received 3433778 bytes of data
,2015-11-20T12:12:41.961Z SendDataTCPServer.js: TCP/IP server has received 3455820 bytes of data
,2015-11-20T12:12:41.975Z SendDataTCPServer.js: TCP/IP server has received 3479910 bytes of data
,2015-11-20T12:12:41.989Z SendDataTCPServer.js: TCP/IP server has received 3519330 bytes of data
,2015-11-20T12:12:42.003Z SendDataTCPServer.js: TCP/IP server has received 3539040 bytes of data
,2015-11-20T12:12:42.015Z SendDataTCPServer.js: TCP/IP server has received 3576270 bytes of data
,2015-11-20T12:12:42.029Z SendDataTCPServer.js: TCP/IP server has received 3622260 bytes of data
,2015-11-20T12:12:42.045Z SendDataTCPServer.js: TCP/IP server has received 3656874 bytes of data
,2015-11-20T12:12:42.059Z SendDataTCPServer.js: TCP/IP server has received 3717768 bytes of data
,2015-11-20T12:12:42.072Z SendDataTCPServer.js: TCP/IP server has received 3747090 bytes of data
,2015-11-20T12:12:42.089Z SendDataTCPServer.js: TCP/IP server has received 3797460 bytes of data
,2015-11-20T12:12:42.106Z SendDataTCPServer.js: TCP/IP server has received 3850020 bytes of data
,2015-11-20T12:12:42.120Z SendDataTCPServer.js: TCP/IP server has received 3887250 bytes of data
,2015-11-20T12:12:42.133Z SendDataTCPServer.js: TCP/IP server has received 3920100 bytes of data
,2015-11-20T12:12:42.146Z SendDataTCPServer.js: TCP/IP server has received 3937620 bytes of data
,2015-11-20T12:12:42.160Z SendDataTCPServer.js: TCP/IP server has received 3979088 bytes of data
,2015-11-20T12:12:42.174Z SendDataTCPServer.js: TCP/IP server has received 4005510 bytes of data
,2015-11-20T12:12:42.189Z SendDataTCPServer.js: TCP/IP server has received 4009890 bytes of data
,2015-11-20T12:12:42.201Z SendDataTCPServer.js: TCP/IP server has received 4042740 bytes of data
,2015-11-20T12:12:42.293Z SendDataTCPServer.js: TCP/IP server has received 4075590 bytes of data
,2015-11-20T12:12:42.307Z SendDataTCPServer.js: TCP/IP server has received 4086114 bytes of data
,2015-11-20T12:12:42.319Z SendDataTCPServer.js: TCP/IP server has received 4115010 bytes of data
,2015-11-20T12:12:42.333Z SendDataTCPServer.js: TCP/IP server has received 4143196 bytes of data
,2015-11-20T12:12:42.350Z SendDataTCPServer.js: TCP/IP server has received 4176330 bytes of data
,2015-11-20T12:12:42.364Z SendDataTCPServer.js: TCP/IP server has received 4209180 bytes of data
,2015-11-20T12:12:42.377Z SendDataTCPServer.js: TCP/IP server has received 4228748 bytes of data
,2015-11-20T12:12:42.390Z SendDataTCPServer.js: TCP/IP server has received 4250790 bytes of data
,2015-11-20T12:12:42.404Z SendDataTCPServer.js: TCP/IP server has received 4270500 bytes of data
,2015-11-20T12:12:42.417Z SendDataTCPServer.js: TCP/IP server has received 4289926 bytes of data
,2015-11-20T12:12:42.429Z SendDataTCPServer.js: TCP/IP server has received 4320870 bytes of data
,2015-11-20T12:12:42.442Z SendDataTCPServer.js: TCP/IP server has received 4340438 bytes of data
,2015-11-20T12:12:42.455Z SendDataTCPServer.js: TCP/IP server has received 4375620 bytes of data
,2015-11-20T12:12:42.468Z SendDataTCPServer.js: TCP/IP server has received 4408328 bytes of data
,2015-11-20T12:12:42.481Z SendDataTCPServer.js: TCP/IP server has received 4428180 bytes of data
,2015-11-20T12:12:42.493Z SendDataTCPServer.js: TCP/IP server has received 4447890 bytes of data
,2015-11-20T12:12:42.507Z SendDataTCPServer.js: TCP/IP server has received 4482930 bytes of data
,2015-11-20T12:12:42.519Z SendDataTCPServer.js: TCP/IP server has received 4517828 bytes of data
,2015-11-20T12:12:42.533Z SendDataTCPServer.js: TCP/IP server has received 4559580 bytes of data
,2015-11-20T12:12:42.548Z SendDataTCPServer.js: TCP/IP server has received 4590240 bytes of data
,2015-11-20T12:12:42.560Z SendDataTCPServer.js: TCP/IP server has received 4623090 bytes of data
,2015-11-20T12:12:42.572Z SendDataTCPServer.js: TCP/IP server has received 4649370 bytes of data
,2015-11-20T12:12:42.586Z SendDataTCPServer.js: TCP/IP server has received 4682220 bytes of data
,2015-11-20T12:12:42.600Z SendDataTCPServer.js: TCP/IP server has received 4721498 bytes of data
,2015-11-20T12:12:42.612Z SendDataTCPServer.js: TCP/IP server has received 4750110 bytes of data
,2015-11-20T12:12:42.625Z SendDataTCPServer.js: TCP/IP server has received 4785150 bytes of data
,2015-11-20T12:12:42.638Z SendDataTCPServer.js: TCP/IP server has received 4815810 bytes of data
,2015-11-20T12:12:42.652Z SendDataTCPServer.js: TCP/IP server has received 4833330 bytes of data
,2015-11-20T12:12:42.665Z SendDataTCPServer.js: TCP/IP server has received 4855230 bytes of data
,2015-11-20T12:12:42.678Z SendDataTCPServer.js: TCP/IP server has received 4863990 bytes of data
,2015-11-20T12:12:42.690Z SendDataTCPServer.js: TCP/IP server has received 4885890 bytes of data
,2015-11-20T12:12:42.703Z SendDataTCPServer.js: TCP/IP server has received 4905600 bytes of data
,2015-11-20T12:12:42.716Z SendDataTCPServer.js: TCP/IP server has received 4925310 bytes of data
,2015-11-20T12:12:42.728Z SendDataTCPServer.js: TCP/IP server has received 4958160 bytes of data
,2015-11-20T12:12:42.744Z SendDataTCPServer.js: TCP/IP server has received 5004150 bytes of data
,2015-11-20T12:12:42.758Z SendDataTCPServer.js: TCP/IP server has received 5028240 bytes of data
,2015-11-20T12:12:42.817Z SendDataTCPServer.js: TCP/IP server has received 5050140 bytes of data
,2015-11-20T12:12:42.831Z SendDataTCPServer.js: TCP/IP server has received 5089560 bytes of data
,2015-11-20T12:12:42.845Z SendDataTCPServer.js: TCP/IP server has received 5118030 bytes of data
,2015-11-20T12:12:42.860Z SendDataTCPServer.js: TCP/IP server has received 5152786 bytes of data
,2015-11-20T12:12:42.874Z SendDataTCPServer.js: TCP/IP server has received 5181540 bytes of data
,2015-11-20T12:12:42.887Z SendDataTCPServer.js: TCP/IP server has received 5201250 bytes of data
,2015-11-20T12:12:42.902Z SendDataTCPServer.js: TCP/IP server has received 5225340 bytes of data
,2015-11-20T12:12:42.916Z SendDataTCPServer.js: TCP/IP server has received 5249004 bytes of data
,2015-11-20T12:12:42.930Z SendDataTCPServer.js: TCP/IP server has received 5271330 bytes of data
,2015-11-20T12:12:42.944Z SendDataTCPServer.js: TCP/IP server has received 5295420 bytes of data
,2015-11-20T12:12:42.958Z SendDataTCPServer.js: TCP/IP server has received 5317320 bytes of data
,2015-11-20T12:12:42.971Z SendDataTCPServer.js: TCP/IP server has received 5343600 bytes of data
,2015-11-20T12:12:42.986Z SendDataTCPServer.js: TCP/IP server has received 5365500 bytes of data
,2015-11-20T12:12:43.002Z SendDataTCPServer.js: TCP/IP server has received 5389590 bytes of data
,2015-11-20T12:12:43.015Z SendDataTCPServer.js: TCP/IP server has received 5420250 bytes of data
,2015-11-20T12:12:43.029Z SendDataTCPServer.js: TCP/IP server has received 5459670 bytes of data
,2015-11-20T12:12:43.042Z SendDataTCPServer.js: TCP/IP server has received 5494710 bytes of data
,2015-11-20T12:12:43.145Z SendDataTCPServer.js: TCP/IP server has received 5518800 bytes of data
,2015-11-20T12:12:43.159Z SendDataTCPServer.js: TCP/IP server has received 5547270 bytes of data
,2015-11-20T12:12:43.173Z SendDataTCPServer.js: TCP/IP server has received 5591070 bytes of data
,2015-11-20T12:12:43.187Z SendDataTCPServer.js: TCP/IP server has received 5593260 bytes of data
,2015-11-20T12:12:43.199Z SendDataTCPServer.js: TCP/IP server has received 5597640 bytes of data
,2015-11-20T12:12:43.212Z SendDataTCPServer.js: TCP/IP server has received 5637060 bytes of data
,2015-11-20T12:12:43.226Z SendDataTCPServer.js: TCP/IP server has received 5658960 bytes of data
,2015-11-20T12:12:43.240Z SendDataTCPServer.js: TCP/IP server has received 5698380 bytes of data
,2015-11-20T12:12:43.254Z SendDataTCPServer.js: TCP/IP server has received 5713710 bytes of data
,2015-11-20T12:12:43.269Z SendDataTCPServer.js: TCP/IP server has received 5718090 bytes of data
,2015-11-20T12:12:43.338Z SendDataTCPServer.js: TCP/IP server has received 5731230 bytes of data
,2015-11-20T12:12:43.352Z SendDataTCPServer.js: TCP/IP server has received 5766270 bytes of data
,2015-11-20T12:12:43.367Z SendDataTCPServer.js: TCP/IP server has received 5788170 bytes of data
,2015-11-20T12:12:43.381Z SendDataTCPServer.js: TCP/IP server has received 5812260 bytes of data
,2015-11-20T12:12:43.395Z SendDataTCPServer.js: TCP/IP server has received 5838540 bytes of data
,2015-11-20T12:12:43.409Z SendDataTCPServer.js: TCP/IP server has received 5856060 bytes of data
,2015-11-20T12:12:43.423Z SendDataTCPServer.js: TCP/IP server has received 5880150 bytes of data
,2015-11-20T12:12:43.436Z SendDataTCPServer.js: TCP/IP server has received 5906430 bytes of data
,2015-11-20T12:12:43.450Z SendDataTCPServer.js: TCP/IP server has received 5939280 bytes of data
,2015-11-20T12:12:43.464Z SendDataTCPServer.js: TCP/IP server has received 5980890 bytes of data
,2015-11-20T12:12:43.477Z SendDataTCPServer.js: TCP/IP server has received 6011550 bytes of data
,2015-11-20T12:12:43.488Z SendDataTCPServer.js: TCP/IP server has received 6035214 bytes of data
,2015-11-20T12:12:43.502Z SendDataTCPServer.js: TCP/IP server has received 6070680 bytes of data
,2015-11-20T12:12:43.515Z SendDataTCPServer.js: TCP/IP server has received 6096960 bytes of data
,2015-11-20T12:12:43.529Z SendDataTCPServer.js: TCP/IP server has received 6125004 bytes of data
,2015-11-20T12:12:43.544Z SendDataTCPServer.js: TCP/IP server has received 6162234 bytes of data
,2015-11-20T12:12:43.557Z SendDataTCPServer.js: TCP/IP server has received 6199180 bytes of data
,2015-11-20T12:12:43.571Z SendDataTCPServer.js: TCP/IP server has received 6232598 bytes of data
,2015-11-20T12:12:43.585Z SendDataTCPServer.js: TCP/IP server has received 6271734 bytes of data
,2015-11-20T12:12:43.599Z SendDataTCPServer.js: TCP/IP server has received 6309390 bytes of data
,2015-11-20T12:12:43.613Z SendDataTCPServer.js: TCP/IP server has received 6352906 bytes of data
,2015-11-20T12:12:43.627Z SendDataTCPServer.js: TCP/IP server has received 6376854 bytes of data
,2015-11-20T12:12:43.640Z SendDataTCPServer.js: TCP/IP server has received 6416700 bytes of data
,2015-11-20T12:12:43.653Z SendDataTCPServer.js: TCP/IP server has received 6436268 bytes of data
,2015-11-20T12:12:43.666Z SendDataTCPServer.js: TCP/IP server has received 6488828 bytes of data
,2015-11-20T12:12:43.681Z SendDataTCPServer.js: TCP/IP server has received 6515108 bytes of data
,2015-11-20T12:12:43.695Z SendDataTCPServer.js: TCP/IP server has received 6537150 bytes of data
,2015-11-20T12:12:43.707Z SendDataTCPServer.js: TCP/IP server has received 6559050 bytes of data
,2015-11-20T12:12:43.719Z SendDataTCPServer.js: TCP/IP server has received 6591616 bytes of data
,2015-11-20T12:12:43.732Z SendDataTCPServer.js: TCP/IP server has received 6637890 bytes of data
,2015-11-20T12:12:43.750Z SendDataTCPServer.js: TCP/IP server has received 6666360 bytes of data
,2015-11-20T12:12:43.763Z SendDataTCPServer.js: TCP/IP server has received 6697020 bytes of data
,2015-11-20T12:12:43.776Z SendDataTCPServer.js: TCP/IP server has received 6732060 bytes of data
,2015-11-20T12:12:43.789Z SendDataTCPServer.js: TCP/IP server has received 6769290 bytes of data
,2015-11-20T12:12:43.802Z SendDataTCPServer.js: TCP/IP server has received 6810900 bytes of data
,2015-11-20T12:12:43.815Z SendDataTCPServer.js: TCP/IP server has received 6834990 bytes of data
,2015-11-20T12:12:43.862Z SendDataTCPServer.js: TCP/IP server has received 6845940 bytes of data
,2015-11-20T12:12:43.876Z SendDataTCPServer.js: TCP/IP server has received 6874410 bytes of data
,2015-11-20T12:12:43.890Z SendDataTCPServer.js: TCP/IP server has received 6889740 bytes of data
2015-11-20 13:12:43.890 ThaliTest[378:b80b] client session: connected
2015-11-20 13:12:43.891 ThaliTest[378:b80b] client session: stateChange:1->2 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:12:43.899 ThaliTest[378:8a23] client session: fireConnectCallback: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:12:43.900 ThaliTest[378:8a23] jxcore: connect: success
2015-11-20T12:12:43.901Z SendDataTCPServer.js: TCP/IP server has received 6905070 bytes of data
,2015-11-20T12:12:43.902Z SendDataConnector.js: CLIENT connected to 53146, error: null
2015-11-20T12:12:43.902Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:12:43.905 ThaliTest[378:60b] client: relay established
2015-11-20 13:12:43.906 ThaliTest[378:60b] client: new accepted socket: 0x17d27010
,2015-11-20T12:12:43.916Z SendDataTCPServer.js: TCP/IP server has received 6918210 bytes of data
2015-11-20T12:12:43.918Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:12:54.269 ThaliTest[378:912f] server session: not connected Apple-Iphone6-1_PT2043
,2015-11-20T12:12:55.000Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:12:55.267Z SendDataTCPServer.js: TCP/IP server has received 7049282 bytes of data
,2015-11-20T12:12:55.270Z SendDataTCPServer.js: TCP/IP server has received 7180354 bytes of data
,2015-11-20T12:12:55.273Z SendDataTCPServer.js: TCP/IP server has received 7311426 bytes of data
,2015-11-20T12:12:55.276Z SendDataTCPServer.js: TCP/IP server has received 7442498 bytes of data
,2015-11-20T12:12:55.280Z SendDataTCPServer.js: TCP/IP server has received 7573570 bytes of data
,2015-11-20T12:12:55.282Z SendDataTCPServer.js: TCP/IP server has received 7704642 bytes of data
,2015-11-20T12:12:55.285Z SendDataTCPServer.js: TCP/IP server has received 7835714 bytes of data
,2015-11-20T12:12:55.290Z SendDataTCPServer.js: TCP/IP server has received 7966786 bytes of data
,2015-11-20T12:12:55.293Z SendDataTCPServer.js: TCP/IP server has received 8097858 bytes of data
,2015-11-20T12:12:55.297Z SendDataTCPServer.js: TCP/IP server has received 8228930 bytes of data
,2015-11-20T12:12:55.300Z SendDataTCPServer.js: TCP/IP server has received 8360002 bytes of data
,2015-11-20T12:12:55.304Z SendDataTCPServer.js: TCP/IP server has received 8491074 bytes of data
,2015-11-20T12:12:55.307Z SendDataTCPServer.js: TCP/IP server has received 8622146 bytes of data
,2015-11-20T12:12:55.312Z SendDataTCPServer.js: TCP/IP server has received 8753218 bytes of data
,2015-11-20T12:12:55.316Z SendDataTCPServer.js: TCP/IP server has received 8884290 bytes of data
,2015-11-20T12:12:55.320Z SendDataTCPServer.js: TCP/IP server has received 9015362 bytes of data
,2015-11-20T12:12:55.324Z SendDataTCPServer.js: TCP/IP server has received 9146434 bytes of data
,2015-11-20T12:12:55.327Z SendDataTCPServer.js: TCP/IP server has received 9277506 bytes of data
,2015-11-20T12:12:55.330Z SendDataTCPServer.js: TCP/IP server has received 9408578 bytes of data
,2015-11-20T12:12:55.335Z SendDataTCPServer.js: TCP/IP server has received 9539650 bytes of data
,2015-11-20T12:12:55.337Z SendDataTCPServer.js: TCP/IP server has received 9670722 bytes of data
,2015-11-20T12:12:55.340Z SendDataTCPServer.js: TCP/IP server has received 9801794 bytes of data
,2015-11-20T12:12:55.344Z SendDataTCPServer.js: TCP/IP server has received 9920700 bytes of data
,2015-11-20T12:12:55.367Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20T12:12:55.524Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:12:55.524Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-20T12:12:55.714Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:12:55.714Z SendDataConnector.js: CLIENT is data received : 200000
,2015-11-20T12:12:57.167Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:12:57.168Z SendDataConnector.js: CLIENT is data received : 1690000
,2015-11-20T12:12:57.415Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:12:57.416Z SendDataConnector.js: CLIENT is data received : 1910000
,2015-11-20T12:12:59.182Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:12:59.183Z SendDataConnector.js: CLIENT is data received : 3530000
,2015-11-20 13:12:59.787 ThaliTest[378:60b] multipeer session: restart
2015-11-20 13:12:59.788 ThaliTest[378:60b] client: lost peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:12:59.788 ThaliTest[378:60b] client session: onPeerLost: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:12:59.796Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:12:59.796Z SendDataConnector.js: CLIENT is data received : 4120000
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":false}]
,2015-11-20T12:13:01.979Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:13:01.979Z SendDataConnector.js: CLIENT is data received : 5850000
,2015-11-20T12:13:01.991Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:13:01.991Z SendDataConnector.js: CLIENT is data received : 5870000
,2015-11-20 13:13:02.635 ThaliTest[378:60b] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:13:02.638 ThaliTest[378:60b] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:13:02.641 ThaliTest[378:60b] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:13:02.642 ThaliTest[378:60b] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:13:02.643 ThaliTest[378:60b] multipeer session: reset timer
2015-11-20 13:13:02.643 ThaliTest[378:60b] multipeer session: stop timer
,2015-11-20 13:13:02.644 ThaliTest[378:60b] multipeer session: start timer: 0x1cef1cb0
2015-11-20 13:13:02.645 ThaliTest[378:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT2043)
,2015-11-20 13:13:02.645 ThaliTest[378:60b] server session: disconnect
2015-11-20 13:13:02.647 ThaliTest[378:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT2043
,2015-11-20 13:13:02.651 ThaliTest[378:60b] server session: connect
2015-11-20T12:13:02.653Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-20 13:13:02.653 ThaliTest[378:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT2043
2015-11-20T12:13:02.653Z SendDataTCPServer.js: TCP/IP server is close
,2015-11-20 13:13:02.659 ThaliTest[378:60b] server: accepting invitation Apple-Iphone6-1_PT2043
,2015-11-20T12:13:02.666Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:13:02.666Z SendDataConnector.js: CLIENT is data received : 6370000
,2015-11-20T12:13:04.071Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:13:04.072Z SendDataConnector.js: CLIENT is data received : 7900000
,2015-11-20T12:13:05.566Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:13:05.567Z SendDataConnector.js: CLIENT is data received : 9260000
,2015-11-20T12:13:05.788Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:13:05.789Z SendDataConnector.js: CLIENT is data received : 9450000
,2015-11-20T12:13:06.128Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:13:06.129Z SendDataConnector.js: CLIENT is data received : 9840000
,2015-11-20T12:13:06.141Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:13:06.142Z SendDataConnector.js: CLIENT is data received : 9860000
,2015-11-20T12:13:06.155Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:13:06.155Z SendDataConnector.js: CLIENT is data received : 9900000
,2015-11-20T12:13:06.167Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:13:06.167Z SendDataConnector.js: CLIENT is data received : 9910000
,2015-11-20T12:13:06.179Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:13:06.180Z SendDataConnector.js: CLIENT is data received : 9930000
,2015-11-20T12:13:06.203Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:13:06.204Z SendDataConnector.js: CLIENT is data received : 9940000
,2015-11-20T12:13:06.238Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:13:06.239Z SendDataConnector.js: CLIENT is data received : 9980000
,2015-11-20T12:13:06.252Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:13:06.253Z SendDataConnector.js: CLIENT is data received : 9990000
,2015-11-20T12:13:06.421Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:13:06.422Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:13:06.422Z SendDataConnector.js: got all data for this round
2015-11-20T12:13:06.422Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:13:06.423Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:13:06.424 ThaliTest[378:6a07] jxcore: disconnect
,2015-11-20 13:13:06.425 ThaliTest[378:6a07] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:13:06.425 ThaliTest[378:6a07] client session: disconnect
,2015-11-20 13:13:06.426 ThaliTest[378:6a07] client session: stateChange:2->0 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:13:06.429 ThaliTest[378:6a07] jxcore: disconnect: success
2015-11-20T12:13:06.431Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT2716","time":167272,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT497.PdI1bg==","time":107161,"result":"OK","connections":4},{"name":"Apple-Iphone6-1_PT2043.OU3s0w==","time":33577,"result":"OK","connection,s":1},{"name":"Apple-IpadAir2-1_PT7072.5zbvNA==","time":26141,"result":"OK","connections":1}]}
,sendList : 100% : 107161 ms, 99% : 107161 ms, 95 : 107161 ms, 90% : 107161 ms.
Result count 3, range 26141 ms to  107161 ms.
,sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
,2015-11-20T12:13:06.439Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:13:06.455Z SendDataConnector.js: CLIENT is closed
,2015-11-20 13:13:07.967 ThaliTest[378:912f] server session: connected
,2015-11-20 13:13:07.969 ThaliTest[378:912f] server session: stateChange:1->2 Apple-Iphone6-1_PT2043
,2015-11-20 13:13:07.976 ThaliTest[378:60b] server relay: connected (to port: 53117)
,2015-11-20T12:13:07.985Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:13:10.138Z SendDataTCPServer.js: TCP/IP server has received 24860 bytes of data
,2015-11-20T12:13:10.155Z SendDataTCPServer.js: TCP/IP server has received 114792 bytes of data
,2015-11-20T12:13:10.169Z SendDataTCPServer.js: TCP/IP server has received 140160 bytes of data
,2015-11-20T12:13:10.185Z SendDataTCPServer.js: TCP/IP server has received 170394 bytes of data
,2015-11-20T12:13:10.201Z SendDataTCPServer.js: TCP/IP server has received 203670 bytes of data
,2015-11-20T12:13:10.327Z SendDataTCPServer.js: TCP/IP server has received 207766 bytes of data
,2015-11-20T12:13:10.341Z SendDataTCPServer.js: TCP/IP server has received 249660 bytes of data
,2015-11-20T12:13:10.355Z SendDataTCPServer.js: TCP/IP server has received 271560 bytes of data
,2015-11-20T12:13:10.368Z SendDataTCPServer.js: TCP/IP server has received 310980 bytes of data
,2015-11-20T12:13:10.382Z SendDataTCPServer.js: TCP/IP server has received 354780 bytes of data
,2015-11-20T12:13:10.394Z SendDataTCPServer.js: TCP/IP server has received 378870 bytes of data
,2015-11-20T12:13:10.407Z SendDataTCPServer.js: TCP/IP server has received 404866 bytes of data
,2015-11-20T12:13:10.419Z SendDataTCPServer.js: TCP/IP server has received 405150 bytes of data
,2015-11-20T12:13:10.442Z SendDataTCPServer.js: TCP/IP server has received 416100 bytes of data
,2015-11-20T12:13:10.455Z SendDataTCPServer.js: TCP/IP server has received 442380 bytes of data
,2015-11-20T12:13:10.468Z SendDataTCPServer.js: TCP/IP server has received 462090 bytes of data
,2015-11-20T12:13:10.481Z SendDataTCPServer.js: TCP/IP server has received 490560 bytes of data
,2015-11-20T12:13:10.493Z SendDataTCPServer.js: TCP/IP server has received 512318 bytes of data
,2015-11-20T12:13:10.506Z SendDataTCPServer.js: TCP/IP server has received 543120 bytes of data
,2015-11-20T12:13:10.521Z SendDataTCPServer.js: TCP/IP server has received 562830 bytes of data
,2015-11-20T12:13:10.599Z SendDataTCPServer.js: TCP/IP server has received 578160 bytes of data
,2015-11-20T12:13:10.612Z SendDataTCPServer.js: TCP/IP server has received 600060 bytes of data
,2015-11-20T12:13:10.625Z SendDataTCPServer.js: TCP/IP server has received 624150 bytes of data
,2015-11-20T12:13:10.638Z SendDataTCPServer.js: TCP/IP server has received 648240 bytes of data
,2015-11-20T12:13:10.652Z SendDataTCPServer.js: TCP/IP server has received 687660 bytes of data
,2015-11-20T12:13:10.665Z SendDataTCPServer.js: TCP/IP server has received 702990 bytes of data
,2015-11-20T12:13:10.677Z SendDataTCPServer.js: TCP/IP server has received 709276 bytes of data
,2015-11-20T12:13:10.690Z SendDataTCPServer.js: TCP/IP server has received 738030 bytes of data
,2015-11-20T12:13:10.702Z SendDataTCPServer.js: TCP/IP server has received 764310 bytes of data
,2015-11-20T12:13:10.715Z SendDataTCPServer.js: TCP/IP server has received 777450 bytes of data
,2015-11-20T12:13:10.727Z SendDataTCPServer.js: TCP/IP server has received 799350 bytes of data
,2015-11-20T12:13:10.739Z SendDataTCPServer.js: TCP/IP server has received 821250 bytes of data
,2015-11-20T12:13:10.752Z SendDataTCPServer.js: TCP/IP server has received 838770 bytes of data
,2015-11-20T12:13:10.765Z SendDataTCPServer.js: TCP/IP server has received 865050 bytes of data
,2015-11-20T12:13:10.779Z SendDataTCPServer.js: TCP/IP server has received 891330 bytes of data
,2015-11-20T12:13:10.791Z SendDataTCPServer.js: TCP/IP server has received 915420 bytes of data
,2015-11-20T12:13:10.805Z SendDataTCPServer.js: TCP/IP server has received 941700 bytes of data
,2015-11-20T12:13:10.817Z SendDataTCPServer.js: TCP/IP server has received 963600 bytes of data
,2015-11-20T12:13:10.830Z SendDataTCPServer.js: TCP/IP server has received 989880 bytes of data
,2015-11-20T12:13:10.844Z SendDataTCPServer.js: TCP/IP server has received 1018208 bytes of data
,2015-11-20T12:13:10.856Z SendDataTCPServer.js: TCP/IP server has received 1049010 bytes of data
,2015-11-20T12:13:10.869Z SendDataTCPServer.js: TCP/IP server has received 1079670 bytes of data
,2015-11-20T12:13:10.882Z SendDataTCPServer.js: TCP/IP server has received 1103760 bytes of data
,2015-11-20T12:13:10.895Z SendDataTCPServer.js: TCP/IP server has received 1125660 bytes of data
,2015-11-20T12:13:10.908Z SendDataTCPServer.js: TCP/IP server has received 1151798 bytes of data
,2015-11-20T12:13:10.921Z SendDataTCPServer.js: TCP/IP server has received 1182600 bytes of data
,2015-11-20T12:13:10.934Z SendDataTCPServer.js: TCP/IP server has received 1243778 bytes of data
,2015-11-20T12:13:10.947Z SendDataTCPServer.js: TCP/IP server has received 1276770 bytes of data
,2015-11-20T12:13:11.006Z SendDataTCPServer.js: TCP/IP server has received 1289910 bytes of data
,2015-11-20T12:13:11.019Z SendDataTCPServer.js: TCP/IP server has received 1324950 bytes of data
,2015-11-20T12:13:11.145Z SendDataTCPServer.js: TCP/IP server has received 1326998 bytes of data
,2015-11-20T12:13:11.158Z SendDataTCPServer.js: TCP/IP server has received 1355610 bytes of data
,2015-11-20T12:13:11.172Z SendDataTCPServer.js: TCP/IP server has received 1388460 bytes of data
,2015-11-20T12:13:11.187Z SendDataTCPServer.js: TCP/IP server has received 1423358 bytes of data
,2015-11-20T12:13:11.200Z SendDataTCPServer.js: TCP/IP server has received 1449780 bytes of data
,2015-11-20T12:13:11.214Z SendDataTCPServer.js: TCP/IP server has received 1471538 bytes of data
,2015-11-20T12:13:11.227Z SendDataTCPServer.js: TCP/IP server has received 1500150 bytes of data
,2015-11-20T12:13:11.240Z SendDataTCPServer.js: TCP/IP server has received 1524240 bytes of data
,2015-11-20T12:13:11.254Z SendDataTCPServer.js: TCP/IP server has received 1552710 bytes of data
,2015-11-20T12:13:11.267Z SendDataTCPServer.js: TCP/IP server has received 1578990 bytes of data
,2015-11-20T12:13:11.283Z SendDataTCPServer.js: TCP/IP server has received 1611840 bytes of data
,2015-11-20T12:13:11.295Z SendDataTCPServer.js: TCP/IP server has received 1640310 bytes of data
,2015-11-20T12:13:11.309Z SendDataTCPServer.js: TCP/IP server has received 1673160 bytes of data
,2015-11-20T12:13:11.323Z SendDataTCPServer.js: TCP/IP server has received 1723530 bytes of data
,2015-11-20T12:13:11.336Z SendDataTCPServer.js: TCP/IP server has received 1743240 bytes of data
,2015-11-20T12:13:11.638Z SendDataTCPServer.js: TCP/IP server has received 1745430 bytes of data
,2015-11-20T12:13:11.652Z SendDataTCPServer.js: TCP/IP server has received 1765140 bytes of data
,2015-11-20T12:13:11.665Z SendDataTCPServer.js: TCP/IP server has received 1797990 bytes of data
,2015-11-20T12:13:11.680Z SendDataTCPServer.js: TCP/IP server has received 1822080 bytes of data
,2015-11-20T12:13:11.694Z SendDataTCPServer.js: TCP/IP server has received 1848360 bytes of data
,2015-11-20T12:13:11.709Z SendDataTCPServer.js: TCP/IP server has received 1876830 bytes of data
,2015-11-20T12:13:11.723Z SendDataTCPServer.js: TCP/IP server has received 1907490 bytes of data
,2015-11-20T12:13:11.738Z SendDataTCPServer.js: TCP/IP server has received 1940340 bytes of data
,2015-11-20T12:13:11.750Z SendDataTCPServer.js: TCP/IP server has received 1959624 bytes of data
,2015-11-20T12:13:11.763Z SendDataTCPServer.js: TCP/IP server has received 1988520 bytes of data
,2015-11-20T12:13:11.777Z SendDataTCPServer.js: TCP/IP server has received 2006040 bytes of data
,2015-11-20T12:13:11.790Z SendDataTCPServer.js: TCP/IP server has received 2032178 bytes of data
,2015-11-20T12:13:11.803Z SendDataTCPServer.js: TCP/IP server has received 2058600 bytes of data
,2015-11-20T12:13:11.817Z SendDataTCPServer.js: TCP/IP server has received 2089260 bytes of data
,2015-11-20T12:13:11.830Z SendDataTCPServer.js: TCP/IP server has received 2119920 bytes of data
,2015-11-20T12:13:11.844Z SendDataTCPServer.js: TCP/IP server has received 2163720 bytes of data
,2015-11-20T12:13:11.858Z SendDataTCPServer.js: TCP/IP server has received 2203140 bytes of data
,2015-11-20T12:13:12.169Z SendDataTCPServer.js: TCP/IP server has received 2213948 bytes of data
,2015-11-20T12:13:12.184Z SendDataTCPServer.js: TCP/IP server has received 2250894 bytes of data
,2015-11-20T12:13:12.198Z SendDataTCPServer.js: TCP/IP server has received 2281980 bytes of data
,2015-11-20T12:13:12.211Z SendDataTCPServer.js: TCP/IP server has received 2301690 bytes of data
,2015-11-20T12:13:12.226Z SendDataTCPServer.js: TCP/IP server has received 2336446 bytes of data
,2015-11-20T12:13:12.242Z SendDataTCPServer.js: TCP/IP server has received 2371770 bytes of data
,2015-11-20T12:13:12.256Z SendDataTCPServer.js: TCP/IP server has received 2402430 bytes of data
,2015-11-20T12:13:12.269Z SendDataTCPServer.js: TCP/IP server has received 2426520 bytes of data
,2015-11-20T12:13:12.283Z SendDataTCPServer.js: TCP/IP server has received 2459370 bytes of data
,2015-11-20T12:13:12.296Z SendDataTCPServer.js: TCP/IP server has received 2483460 bytes of data
,2015-11-20T12:13:12.307Z SendDataTCPServer.js: TCP/IP server has received 2511788 bytes of data
,2015-11-20T12:13:12.320Z SendDataTCPServer.js: TCP/IP server has received 2538068 bytes of data
,2015-11-20T12:13:12.333Z SendDataTCPServer.js: TCP/IP server has received 2571060 bytes of data
,2015-11-20T12:13:12.346Z SendDataTCPServer.js: TCP/IP server has received 2599530 bytes of data
,2015-11-20T12:13:12.359Z SendDataTCPServer.js: TCP/IP server has received 2636760 bytes of data
,2015-11-20T12:13:12.373Z SendDataTCPServer.js: TCP/IP server has received 2680560 bytes of data
,2015-11-20T12:13:12.387Z SendDataTCPServer.js: TCP/IP server has received 2715600 bytes of data
,2015-11-20T12:13:12.688Z SendDataTCPServer.js: TCP/IP server has received 2722170 bytes of data
,2015-11-20T12:13:12.701Z SendDataTCPServer.js: TCP/IP server has received 2741880 bytes of data
,2015-11-20T12:13:12.715Z SendDataTCPServer.js: TCP/IP server has received 2768160 bytes of data
,2015-11-20T12:13:12.728Z SendDataTCPServer.js: TCP/IP server has received 2801010 bytes of data
,2015-11-20T12:13:12.743Z SendDataTCPServer.js: TCP/IP server has received 2824958 bytes of data
,2015-11-20T12:13:12.757Z SendDataTCPServer.js: TCP/IP server has received 2857240 bytes of data
,2015-11-20T12:13:12.772Z SendDataTCPServer.js: TCP/IP server has received 2890800 bytes of data
,2015-11-20T12:13:12.786Z SendDataTCPServer.js: TCP/IP server has received 2921460 bytes of data
,2015-11-20T12:13:12.798Z SendDataTCPServer.js: TCP/IP server has received 2943360 bytes of data
,2015-11-20T12:13:12.810Z SendDataTCPServer.js: TCP/IP server has received 2962928 bytes of data
,2015-11-20T12:13:12.824Z SendDataTCPServer.js: TCP/IP server has received 2993730 bytes of data
,2015-11-20T12:13:12.837Z SendDataTCPServer.js: TCP/IP server has received 3022200 bytes of data
,2015-11-20T12:13:12.850Z SendDataTCPServer.js: TCP/IP server has received 3059430 bytes of data
,2015-11-20T12:13:12.864Z SendDataTCPServer.js: TCP/IP server has received 3090002 bytes of data
,2015-11-20 13:13:13.207 ThaliTest[378:b907] server session: not connected Apple-Iphone6-1_PT2043
,2015-11-20 13:13:32.645 ThaliTest[378:60b] multipeer session: restart
,2015-11-20 13:13:32.656 ThaliTest[378:60b] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:13:32.658 ThaliTest[378:60b] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:13:33.214 ThaliTest[378:60b] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:13:43.594 ThaliTest[378:60b] client: lost peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:13:43.595 ThaliTest[378:60b] client session: onPeerLost: Apple-Iphone6-1_PT2043.OU3s0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:13:44.629 ThaliTest[378:60b] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:14:00.933 ThaliTest[378:60b] client: lost peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:14:00.935 ThaliTest[378:60b] client session: onPeerLost: Apple-Iphone5s-1_PT497.PdI1bg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:14:01.891 ThaliTest[378:60b] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:14:02.646 ThaliTest[378:60b] multipeer session: restart
,2015-11-20 13:14:02.657 ThaliTest[378:60b] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:14:02.658 ThaliTest[378:60b] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:14:03.090 ThaliTest[378:60b] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:14:32.646 ThaliTest[378:60b] multipeer session: restart
,2015-11-20 13:14:32.656 ThaliTest[378:60b] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:14:32.658 ThaliTest[378:60b] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:14:33.473 ThaliTest[378:60b] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-11-20 13:14:44.815 ThaliTest[378:6a07] jxcore: stopBroadcasting
,2015-11-20 13:14:44.816 ThaliTest[378:6a07] THEMultipeerSession stopping peer
,2015-11-20 13:14:44.817 ThaliTest[378:6a07] multipeer session: stop timer
,2015-11-20 13:14:44.818 ThaliTest[378:6a07] server session: disconnect
,2015-11-20 13:14:44.818 ThaliTest[378:6a07] server session: stateChange:1->0 Apple-Iphone5s-1_PT497
,2015-11-20 13:14:44.819 ThaliTest[378:6a07] server session: disconnect
2015-11-20 13:14:44.821 ThaliTest[378:6a07] server session: stateChange:2->0 Apple-Iphone6-1_PT2043
,2015-11-20 13:14:44.824 ThaliTest[378:6a07] server session: disconnect
2015-11-20 13:14:44.825 ThaliTest[378:6a07] server session: stateChange:2->0 Apple-IpadAir2-1_PT7072
,2015-11-20 13:14:44.829 ThaliTest[378:6a07] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-20T12:14:44.845Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-20T12:14:44.846Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-20T12:14:44.847Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
2015-11-20T12:14:44.847Z Sen,dDataTCPServer.js: TCP/IP server is close
2015-11-20T12:14:44.847Z SendDataTCPServer.js: TCP/IP server is close
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT7072.5zbvNA==\",\"time\":26141,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":33577,,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":107161,\"result\":\"OK\",\"connections\":4}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT7072.,5zbvNA==\",\"time\":26141,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":29961,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":31099,\"result\":\"OK\",\"connections\":,1},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":31207,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":33577,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT2716.py/N2Q==\",\"time\":52,469,\"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-IpadAir2-1_PT7072.5zbvNA==\",\"time\":57845,\"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":58779,\"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-,IpadAir2-1_PT7072.5zbvNA==\",\"time\":70969,\"result\":\"OK\",\"connections\":3},{\"name\":\"Apple-Iphone5-1_PT2716.py/N2Q==\",\"time\":84289,\"result\":\"OK\",\"connections\":3},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":107161,\"result\":\"OK,\",\"connections\":4}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called
DBG, CoordinatorConnector disconnect called
The Coor
```
