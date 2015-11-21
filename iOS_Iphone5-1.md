#### Test 51335028aa5f981_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028aa5f981/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DD92476D-5E5E-4AE4-9A9D-3A384DC7B40C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/DD92476D-5E5E-4AE4-9A9D-3A384DC7B40C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028aa5f981/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028aa5f981/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/D4AE1CDE-2CAE-4A6C-87C3-E48A780CD2F0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51750"
,(lldb)     command script import "/tmp/DD92476D-5E5E-4AE4-9A9D-3A384DC7B40C/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-21 10:32:12.939 ThaliTest[424:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-21 10:32:12.942 ThaliTest[424:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-21 10:32:12.948 ThaliTest[424:60b] Unlimited access to network resources
,2015-11-21 10:32:12.955 ThaliTest[424:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-21 10:32:23.643 ThaliTest[424:60b] Resetting plugins due to page load.
,2015-11-21 10:32:24.515 ThaliTest[424:60b] Finished load of: file:///var/mobile/Applications/D4AE1CDE-2CAE-4A6C-87C3-E48A780CD2F0/ThaliTest.app/www/index.html
,2015-11-21 10:32:24.698 ThaliTest[424:60b] JXcore Cordova plugin initializing
,2015-11-21 10:32:24.700 ThaliTest[424:6707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
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
,my name is : Apple-Iphone5-1_PT9936
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
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c,:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
,-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c,:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
,-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
,-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
,-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[],}
,Start now : testSendData.js
stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 54694
,2015-11-21 10:40:27.693 ThaliTest[424:6707] jxcore: startBroadcasting
,2015-11-21 10:40:27.704 ThaliTest[424:6707] server: starting Apple-Iphone5-1_PT9936.bcHQBQ==
2015-11-21 10:40:27.706 ThaliTest[424:6707] multipeer session: start timer: 0x1a69e410
2015-11-21 10:40:27.708 ThaliTest[424:6707] THEMultipeerSession initialize,d peer Apple-Iphone5-1_PT9936
2015-11-21 10:40:27.709 ThaliTest[424:6707] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-21T09:40:27.712Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-21 10:40:28.614 ThaliTest[424:60b] client: found peer: Apple-Iphone6-1_PT1827.PMdwog==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1827.PMdwog==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21T09:40:28.618Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21T09:40:28.618Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21T09:40:28.618Z SendDataConnector.js: do connect now
,2015-11-21 10:40:28.619 ThaliTest[424:6707] jxcore: connect Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 10:40:28.620 ThaliTest[424:6707] client session: connect
,2015-11-21 10:40:28.620 ThaliTest[424:6707] client session: stateChange:0->1 Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 10:40:28.631 ThaliTest[424:60b] client: found peer: Apple-Iphone5s-1_PT7804.JHi/bQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7804.JHi/bQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-21 10:40:28.748 ThaliTest[424:60b] multipeer session: reset timer
,2015-11-21 10:40:28.749 ThaliTest[424:60b] multipeer session: stop timer
2015-11-21 10:40:28.749 ThaliTest[424:60b] multipeer session: start timer: 0x1a69e410
,2015-11-21 10:40:28.750 ThaliTest[424:60b] server session: connect
2015-11-21 10:40:28.751 ThaliTest[424:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT1827
,2015-11-21 10:40:28.755 ThaliTest[424:60b] server: accepting invitation Apple-Iphone6-1_PT1827
,2015-11-21 10:40:28.963 ThaliTest[424:60b] multipeer session: reset timer
,2015-11-21 10:40:28.965 ThaliTest[424:60b] multipeer session: stop timer
2015-11-21 10:40:28.966 ThaliTest[424:60b] multipeer session: start timer: 0x1a69e410
,2015-11-21 10:40:28.967 ThaliTest[424:60b] server session: connect
,2015-11-21 10:40:28.967 ThaliTest[424:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7804
,2015-11-21 10:40:28.971 ThaliTest[424:60b] server: accepting invitation Apple-Iphone5s-1_PT7804
,2015-11-21 10:40:29.867 ThaliTest[424:60b] client: found peer: Apple-IpadAir2-1_PT437.LS+Gxg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT437.LS+Gxg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-21 10:40:30.993 ThaliTest[424:7533] server session: connected
2015-11-21 10:40:30.995 ThaliTest[424:7533] server session: stateChange:1->2 Apple-Iphone6-1_PT1827
,2015-11-21 10:40:31.000 ThaliTest[424:60b] server relay: connected (to port: 54694)
,2015-11-21T09:40:31.011Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21 10:40:31.111 ThaliTest[424:7533] server session: connected
2015-11-21 10:40:31.114 ThaliTest[424:7533] server session: stateChange:1->2 Apple-Iphone5s-1_PT7804
,2015-11-21 10:40:31.119 ThaliTest[424:60b] server relay: connected (to port: 54694)
,2015-11-21T09:40:31.126Z SendDataTCPServer.js: TCP/IP server connected
2015-11-21T09:40:31.127Z SendDataTCPServer.js: TCP/IP server has received 10808 bytes of data
,2015-11-21T09:40:31.140Z SendDataTCPServer.js: TCP/IP server has received 36946 bytes of data
,2015-11-21T09:40:31.152Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-11-21T09:40:31.165Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-11-21 10:40:31.185 ThaliTest[424:8403] client session: connected
,2015-11-21 10:40:31.187 ThaliTest[424:8403] client session: stateChange:1->2 Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 10:40:31.190 ThaliTest[424:8403] client session: fireConnectCallback: Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 10:40:31.191 ThaliTest[424:8403] jxcore: connect: success
,2015-11-21T09:40:31.192Z SendDataConnector.js: CLIENT connected to 54699, error: null
,2015-11-21T09:40:31.193Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 10:40:31.194 ThaliTest[424:60b] client: relay established
2015-11-21 10:40:31.194 ThaliTest[424:60b] client: new accepted socket: 0x1a7cb300
,2015-11-21T09:40:31.206Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-21T09:40:31.380Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-21T09:40:31.422Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-21T09:40:31.437Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-21T09:40:31.438Z SendDataConnector.js: got all data for this round
,2015-11-21 10:40:31.440 ThaliTest[424:7533] server session: not connected Apple-Iphone5s-1_PT7804
,2015-11-21 10:40:31.446 ThaliTest[424:a617] server session: not connected Apple-Iphone6-1_PT1827
,2015-11-21T09:40:31.448Z SendDataConnector.js: CLIENT Stop now
,2015-11-21T09:40:31.449Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 10:40:31.451 ThaliTest[424:6707] jxcore: disconnect
,2015-11-21 10:40:31.455 ThaliTest[424:6707] client session: disconnectFromPeer: Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 10:40:31.458 ThaliTest[424:6707] client session: disconnect
,2015-11-21 10:40:31.459 ThaliTest[424:6707] client session: stateChange:2->0 Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 10:40:31.467 ThaliTest[424:6707] jxcore: disconnect: success
,2015-11-21T09:40:31.474Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1827.PMdwog==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT7804.JHi/bQ==
2015-11-21T09:40:31.476Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7804.JHi/bQ==
,2015-11-21T09:40:31.476Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7804.JHi/bQ==
,2015-11-21T09:40:31.478Z SendDataConnector.js: do connect now
,2015-11-21 10:40:31.479 ThaliTest[424:6707] jxcore: connect Apple-Iphone5s-1_PT7804.JHi/bQ==
,2015-11-21 10:40:31.480 ThaliTest[424:6707] client session: connect
,2015-11-21 10:40:31.481 ThaliTest[424:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT7804.JHi/bQ==
,2015-11-21 10:40:33.605 ThaliTest[424:60b] multipeer session: reset timer
2015-11-21 10:40:33.606 ThaliTest[424:60b] multipeer session: stop timer
,2015-11-21 10:40:33.608 ThaliTest[424:60b] multipeer session: start timer: 0x1a69e410
,2015-11-21 10:40:33.608 ThaliTest[424:60b] server session: connect
,2015-11-21 10:40:33.609 ThaliTest[424:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT437
,2015-11-21 10:40:33.612 ThaliTest[424:60b] server: accepting invitation Apple-IpadAir2-1_PT437
,2015-11-21 10:40:33.960 ThaliTest[424:7533] client session: connected
2015-11-21 10:40:33.962 ThaliTest[424:7533] client session: stateChange:1->2 Apple-Iphone5s-1_PT7804.JHi/bQ==
,2015-11-21 10:40:33.964 ThaliTest[424:7533] client session: fireConnectCallback: Apple-Iphone5s-1_PT7804.JHi/bQ==
,2015-11-21 10:40:33.965 ThaliTest[424:7533] jxcore: connect: success
,2015-11-21T09:40:33.966Z SendDataConnector.js: CLIENT connected to 54702, error: null
2015-11-21T09:40:33.967Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 10:40:33.968 ThaliTest[424:60b] client: relay established
2015-11-21 10:40:33.969 ThaliTest[424:60b] client: new accepted socket: 0x1a7d1d10
,2015-11-21T09:40:33.979Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-21T09:40:34.193Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-21T09:40:34.206Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-21T09:40:34.495Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-21T09:40:34.519Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-21T09:40:34.519Z SendDataConnector.js: got all data for this round
,2015-11-21T09:40:34.521Z SendDataConnector.js: CLIENT Stop now
2015-11-21T09:40:34.522Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 10:40:34.522 ThaliTest[424:6707] jxcore: disconnect
,2015-11-21 10:40:34.523 ThaliTest[424:6707] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7804.JHi/bQ==
,2015-11-21 10:40:34.524 ThaliTest[424:6707] client session: disconnect
,2015-11-21 10:40:34.524 ThaliTest[424:6707] client session: stateChange:2->0 Apple-Iphone5s-1_PT7804.JHi/bQ==
,2015-11-21 10:40:34.526 ThaliTest[424:6707] jxcore: disconnect: success
2015-11-21T09:40:34.527Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7804.JHi/bQ==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT437.LS+Gxg==
,2015-11-21T09:40:34.531Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT437.LS+Gxg==
,2015-11-21T09:40:34.531Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT437.LS+Gxg==
,2015-11-21T09:40:34.532Z SendDataConnector.js: do connect now
,2015-11-21 10:40:34.532 ThaliTest[424:6707] jxcore: connect Apple-IpadAir2-1_PT437.LS+Gxg==
2015-11-21 10:40:34.533 ThaliTest[424:6707] client session: connect
2015-11-21 10:40:34.533 ThaliTest[424:6707] client session: stateChange:0->1 Apple-IpadAir2-1_PT437.LS+Gxg==
,2015-11-21 10:40:36.565 ThaliTest[424:7533] server session: connected
,2015-11-21 10:40:36.568 ThaliTest[424:7533] server session: stateChange:1->2 Apple-IpadAir2-1_PT437
,2015-11-21 10:40:36.571 ThaliTest[424:60b] server relay: connected (to port: 54694)
2015-11-21T09:40:36.573Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T09:40:36.641Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-11-21T09:40:36.654Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-11-21T09:40:36.671Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-11-21T09:40:36.685Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-21 10:40:36.713 ThaliTest[424:a617] server session: not connected Apple-IpadAir2-1_PT437
,2015-11-21 10:40:43.444 ThaliTest[424:7533] client session: connected
2015-11-21 10:40:43.446 ThaliTest[424:7533] client session: stateChange:1->2 Apple-IpadAir2-1_PT437.LS+Gxg==
,2015-11-21 10:40:43.448 ThaliTest[424:7533] client session: fireConnectCallback: Apple-IpadAir2-1_PT437.LS+Gxg==
2015-11-21 10:40:43.448 ThaliTest[424:7533] jxcore: connect: success
,2015-11-21T09:40:43.450Z SendDataConnector.js: CLIENT connected to 54706, error: null
2015-11-21T09:40:43.450Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 10:40:43.451 ThaliTest[424:60b] client: relay established
,2015-11-21 10:40:43.452 ThaliTest[424:60b] client: new accepted socket: 0x1a6b7730
,2015-11-21T09:40:43.463Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-21T09:40:43.903Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-21T09:40:44.037Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-21T09:40:44.062Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-21T09:40:44.119Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-21T09:40:44.132Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-21T09:40:44.133Z SendDataConnector.js: got all data for this round
,2015-11-21T09:40:44.134Z SendDataConnector.js: CLIENT Stop now
2015-11-21T09:40:44.135Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 10:40:44.135 ThaliTest[424:6707] jxcore: disconnect
,2015-11-21 10:40:44.136 ThaliTest[424:6707] client session: disconnectFromPeer: Apple-IpadAir2-1_PT437.LS+Gxg==
,2015-11-21 10:40:44.137 ThaliTest[424:6707] client session: disconnect
,2015-11-21 10:40:44.137 ThaliTest[424:6707] client session: stateChange:2->0 Apple-IpadAir2-1_PT437.LS+Gxg==
,2015-11-21 10:40:44.139 ThaliTest[424:6707] jxcore: disconnect: success
2015-11-21T09:40:44.140Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT437.LS+Gxg==
---- round done--------
,weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT9936","time":16457,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT1827.PMdwog==","time":2823,"result":"OK","connections":1},{"name":"Apple-Iphone5s-1_PT7804.JHi/bQ==","time":3044,"result":"OK","connections":,1},{"name":"Apple-IpadAir2-1_PT437.LS+Gxg==","time":9602,"result":"OK","connections":1}]}
,sendList : 100% : 9602 ms, 99% : 9602 ms, 95 : 9602 ms, 90% : 9602 ms.
Result count 3, range 2823 ms to  9602 ms.
,sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
,2015-11-21T09:40:44.146Z SendDataConnector.js: CLIENT Stop now
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,DBG, CoordinatorConnector command called
command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT1827.PMdwog==\",\"time\":2823,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT7804.JHi/bQ==\",\"time\":3044,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT437.LS+Gxg==\",\"time\":9602,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT7804.JHi/bQ==\",\"time\":2692,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT1827.PMdwog==\",\"time\":2823,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT9936.bcHQBQ==\",\"time\":2916,\"result\":\"OK\",\"connections\":1},{\"n,ame\":\"Apple-Iphone5-1_PT9936.bcHQBQ==\",\"time\":2922,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT7804.JHi/bQ==\",\"time\":3044,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT1827.PMdwog==\",\"time\":3146,\"res,ult\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT9936.bcHQBQ==\",\"time\":3213,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT1827.PMdwog==\",\"time\":3331,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_P,T437.LS+Gxg==\",\"time\":3658,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT7804.JHi/bQ==\",\"time\":4057,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT437.LS+Gxg==\",\"time\":4183,\"result\":\"OK\",\"connections,\":1},{\"name\":\"Apple-IpadAir2-1_PT437.LS+Gxg==\",\"time\":9602,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
Coordin
```
