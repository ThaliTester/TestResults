#### Test 51335028f10f918_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028f10f918/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/7F7884A6-4520-49B0-BFB4-6D3C149B51F3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/7F7884A6-4520-49B0-BFB4-6D3C149B51F3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028f10f918/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028f10f918/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/4069A237-FF76-49B2-A475-7C86E9214A7F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51479"
,(lldb)     command script import "/tmp/7F7884A6-4520-49B0-BFB4-6D3C149B51F3/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 14:48:48.105 ThaliTest[399:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-11-20 14:48:48.108 ThaliTest[399:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-20 14:48:48.114 ThaliTest[399:60b] Unlimited access to network resources
,2015-11-20 14:48:48.121 ThaliTest[399:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 14:48:58.759 ThaliTest[399:60b] Resetting plugins due to page load.
,2015-11-20 14:48:59.624 ThaliTest[399:60b] Finished load of: file:///var/mobile/Applications/4069A237-FF76-49B2-A475-7C86E9214A7F/ThaliTest.app/www/index.html
,2015-11-20 14:48:59.803 ThaliTest[399:60b] JXcore Cordova plugin initializing
,2015-11-20 14:48:59.806 ThaliTest[399:6907] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
,Warning: iOS does not support ToggleBluetooth
,We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
toggleWiFi
,my name is : Apple-Iphone5-1_PT738
,attempting to connect to test coordinator
,check test folder
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
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
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
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
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
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
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
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"10000000\",\"conReTryTimeout\":\"1000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 53488
,2015-11-20 14:57:12.194 ThaliTest[399:6907] jxcore: startBroadcasting
,2015-11-20 14:57:12.205 ThaliTest[399:6907] server: starting Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:57:12.209 ThaliTest[399:6907] multipeer session: start timer: 0x1b692af0
2015-11-20 14:57:12.211 ThaliTest[399:6907] THEMultipeerSession initialized peer Apple-Iphone5-1_PT738
,2015-11-20 14:57:12.212 ThaliTest[399:6907] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-20T13:57:12.216Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-20 14:57:12.628 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:57:12.633Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:57:12.633Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:57:12.633Z SendDataConnector.js: do connect now
,2015-11-20 14:57:12.634 ThaliTest[399:6907] jxcore: connect Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:12.635 ThaliTest[399:6907] client session: connect
,2015-11-20 14:57:12.635 ThaliTest[399:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:13.222 ThaliTest[399:60b] client: found peer: Apple-IpadAir2-1_PT9530.n+0V8A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9530.n+0V8A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 14:57:15.120 ThaliTest[399:60b] client: found peer: Apple-Iphone6-1_PT8294.ood35g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8294.ood35g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 14:57:15.300 ThaliTest[399:60b] multipeer session: reset timer
,2015-11-20 14:57:15.302 ThaliTest[399:60b] multipeer session: stop timer
2015-11-20 14:57:15.302 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
2015-11-20 14:57:15.303 ThaliTest[399:60b] server session: connect
2015-11-20 14:57:15.304 ThaliTest[399:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8294
,2015-11-20 14:57:15.305 ThaliTest[399:653b] client session: connected
2015-11-20 14:57:15.306 ThaliTest[399:653b] client session: stateChange:1->2 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:15.310 ThaliTest[399:60b] server: accepting invitation Apple-Iphone6-1_PT8294
,2015-11-20 14:57:15.314 ThaliTest[399:7d0b] client session: fireConnectCallback: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:57:15.315 ThaliTest[399:7d0b] jxcore: connect: success
2015-11-20T13:57:15.318Z SendDataConnector.js: CLIENT connected to 53491, error: null
2015-11-20T13:57:15.318Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:57:15.322 ThaliTest[399:60b] client: relay established
2015-11-20 14:57:15.323 ThaliTest[399:60b] client: new accepted socket: 0x1b75ef20
,2015-11-20T13:57:15.332Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 14:57:17.433 ThaliTest[399:653b] server session: connected
2015-11-20 14:57:17.433 ThaliTest[399:653b] server session: stateChange:1->2 Apple-Iphone6-1_PT8294
,2015-11-20 14:57:17.445 ThaliTest[399:60b] server relay: connected (to port: 53488)
,2015-11-20T13:57:26.145Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:57:26.449Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T13:57:26.463Z SendDataTCPServer.js: TCP/IP server has received 131072 bytes of data
,2015-11-20T13:57:26.466Z SendDataTCPServer.js: TCP/IP server has received 262144 bytes of data
,2015-11-20T13:57:26.468Z SendDataTCPServer.js: TCP/IP server has received 393216 bytes of data
,2015-11-20T13:57:26.471Z SendDataTCPServer.js: TCP/IP server has received 524288 bytes of data
,2015-11-20T13:57:26.473Z SendDataTCPServer.js: TCP/IP server has received 655360 bytes of data
,2015-11-20T13:57:26.478Z SendDataTCPServer.js: TCP/IP server has received 786432 bytes of data
,2015-11-20T13:57:26.481Z SendDataTCPServer.js: TCP/IP server has received 917504 bytes of data
,2015-11-20T13:57:26.484Z SendDataTCPServer.js: TCP/IP server has received 1003020 bytes of data
,2015-11-20 14:57:28.020 ThaliTest[399:653b] client session: not connected Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:57:28.021 ThaliTest[399:653b] client session: onLinkFailure: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:57:28.021 ThaliTest[399:653b] client session: disconnect
2015-11-20 14:57:28.022 ThaliTest[399:653b] client session: stateChange:2->0 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:28.106 ThaliTest[399:653b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:57:28.112Z SendDataTCPServer.js: TCP/IP server has received 1013260 bytes of data
2015-11-20T13:57:28.113Z SendDataConnector.js: CLIENT got error : Error: read ECONNRESET
2015-11-20T13:57:28.114Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T13:57:28.114Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T13:57:28.132Z SendDataTCPServer.js: TCP/IP server has received 1143180 bytes of data
,2015-11-20T13:57:28.936Z SendDataTCPServer.js: TCP/IP server has received 1147560 bytes of data
,2015-11-20T13:57:28.949Z SendDataTCPServer.js: TCP/IP server has received 1154130 bytes of data
,2015-11-20T13:57:28.962Z SendDataTCPServer.js: TCP/IP server has received 1169460 bytes of data
,2015-11-20T13:57:29.031Z SendDataTCPServer.js: TCP/IP server has received 1171650 bytes of data
,2015-11-20T13:57:29.122Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:57:29.122Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:30.130 ThaliTest[399:6907] jxcore: disconnect
2015-11-20 14:57:30.131 ThaliTest[399:6907] jxcore: disconnect: fail
2015-11-20T13:57:30.133Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
20,15-11-20T13:57:30.133Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT9513.+kbAXQ== with availability status: true
2015-11-20T13:57:30.133Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:57:30.133Z SendDataConnector.js: do connect now
2015-11-20 14:57:30.134 ThaliTest[399:6907] jxcore: connect Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:30.134 ThaliTest[399:6907] client session: connect
,2015-11-20 14:57:30.135 ThaliTest[399:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:57:36.148Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T13:57:36.149Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T13:57:36.149Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T13:57:36.959Z SendDataTCPServer.js: TCP/IP server has received 1176030 bytes of data
,2015-11-20T13:57:37.149Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:57:37.150Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:38.157 ThaliTest[399:6907] jxcore: disconnect
,2015-11-20 14:57:38.158 ThaliTest[399:6907] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:38.160 ThaliTest[399:6907] client session: disconnect
,2015-11-20 14:57:38.160 ThaliTest[399:6907] client session: stateChange:1->0 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:38.161 ThaliTest[399:6907] client session: fireConnectCallback: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:38.162 ThaliTest[399:6907] jxcore: connect: fail: Peer disconnected
2015-11-20T13:57:38.162Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-11-20T13:57:38.163Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T13:57:38.163Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20 14:57:38.163 ThaliTest[399:6907] jxcore: disconnect: success
2015-11-20T13:57:38.164Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:57:38.164Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT9513.+kbAXQ== with availability status: true
2015-11-20T13:57:38.164Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
2015,-11-20T13:57:38.164Z SendDataConnector.js: do connect now
,2015-11-20 14:57:38.165 ThaliTest[399:6907] jxcore: connect Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:38.165 ThaliTest[399:6907] client session: connect
,2015-11-20 14:57:38.166 ThaliTest[399:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:57:39.168Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:57:39.169Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:40.170 ThaliTest[399:6907] jxcore: disconnect
,2015-11-20 14:57:40.171 ThaliTest[399:6907] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:40.173 ThaliTest[399:6907] client session: disconnect
2015-11-20 14:57:40.174 ThaliTest[399:6907] client session: stateChange:1->0 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:40.175 ThaliTest[399:6907] client session: fireConnectCallback: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:40.176 ThaliTest[399:6907] jxcore: connect: fail: Peer disconnected
2015-11-20T13:57:40.177Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T13:57:40.177Z SendDataConnector.js: CLIENT Can not Connect: Pee,r disconnected
2015-11-20T13:57:40.178Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20 14:57:40.178 ThaliTest[399:6907] jxcore: disconnect: success
2015-11-20T13:57:40.179Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:57:40.179Z SendDataConnector.js: Connect (retry c,ount 4) to peer Apple-Iphone5s-1_PT9513.+kbAXQ== with availability status: true
2015-11-20T13:57:40.179Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:57:40.180Z SendDataConnector.js: do connect now
,2015-11-20 14:57:40.180 ThaliTest[399:6907] jxcore: connect Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:40.181 ThaliTest[399:6907] client session: connect
,2015-11-20 14:57:40.182 ThaliTest[399:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:57:41.184Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:57:41.184Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:42.193 ThaliTest[399:6907] jxcore: disconnect
,2015-11-20 14:57:42.194 ThaliTest[399:6907] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:42.197 ThaliTest[399:6907] client session: disconnect
,2015-11-20 14:57:42.197 ThaliTest[399:6907] client session: stateChange:1->0 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:42.198 ThaliTest[399:6907] client session: fireConnectCallback: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:42.199 ThaliTest[399:6907] jxcore: connect: fail: Peer disconnected
2015-11-20T13:57:42.200Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T13:57:42.200Z SendDataConnector.js: CLIENT Can not Connect: Pee,r disconnected
,2015-11-20T13:57:42.201Z SendDataConnector.js: CLIENT Stop now
2015-11-20T13:57:42.201Z SendDataConnector.js: Stop data retrieving timer
,2015-11-20 14:57:42.202 ThaliTest[399:6907] jxcore: disconnect
,2015-11-20 14:57:42.202 ThaliTest[399:6907] jxcore: disconnect: fail
,2015-11-20T13:57:42.203Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:42.205Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:42.205Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:57:42.205Z SendDataConnector.js: do connect now
,2015-11-20 14:57:42.206 ThaliTest[399:6907] jxcore: connect Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:42.206 ThaliTest[399:6907] client session: connect
,2015-11-20 14:57:42.207 ThaliTest[399:6907] client session: stateChange:0->1 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:42.211 ThaliTest[399:6907] jxcore: disconnect: success
,2015-11-20T13:57:42.213Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:57:42.213Z SendDataConnector.js: Connect (retry count 0) to peer Apple-IpadAir2-1_PT9530.n+0V8A== with availability status,: true
2015-11-20T13:57:42.213Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:57:42.214Z SendDataConnector.js: do connect now
,2015-11-20 14:57:42.214 ThaliTest[399:6907] jxcore: connect Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:42.216 ThaliTest[399:6907] client: already connect(ing/ed) to Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:42.217 ThaliTest[399:6907] jxcore: connect: fail: Aleady connecting
,2015-11-20T13:57:42.218Z SendDataConnector.js: CLIENT connected to 0, error: Aleady connecting
2015-11-20T13:57:42.218Z SendDataConnector.js: CLIENT Can not Connect: Aleady connecting
,2015-11-20T13:57:42.218Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T13:57:42.701Z SendDataTCPServer.js: TCP/IP server has received 1182600 bytes of data
,2015-11-20T13:57:42.714Z SendDataTCPServer.js: TCP/IP server has received 1230780 bytes of data
,2015-11-20T13:57:42.728Z SendDataTCPServer.js: TCP/IP server has received 1258966 bytes of data
,2015-11-20T13:57:42.742Z SendDataTCPServer.js: TCP/IP server has received 1283340 bytes of data
,2015-11-20T13:57:43.219Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:43.220Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:44.229 ThaliTest[399:6907] jxcore: disconnect
2015-11-20 14:57:44.230 ThaliTest[399:6907] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:57:44.232 ThaliTest[399:6907] client session: disconnect
,2015-11-20 14:57:44.233 ThaliTest[399:6907] client session: stateChange:1->0 Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:57:44.233 ThaliTest[399:6907] client session: fireConnectCallback: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:57:44.234 ThaliTest[399:6907] jxcore: connect: fail: Peer disconnected
,2015-11-20T13:57:44.234Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T13:57:44.235Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T13:57:44.235Z SendDataConnector.js: tryAgain afer: 1000 ms.,
2015-11-20 14:57:44.235 ThaliTest[399:6907] jxcore: disconnect: success
2015-11-20T13:57:44.236Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:57:44.236Z SendDataConnector.js: Connect (retry, count 2) to peer Apple-IpadAir2-1_PT9530.n+0V8A== with availability status: true
2015-11-20T13:57:44.236Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:57:44.236Z SendDataConnector.js: do connect now
,2015-11-20 14:57:44.237 ThaliTest[399:6907] jxcore: connect Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:57:44.237 ThaliTest[399:6907] client session: connect
2015-11-20 14:57:44.238 ThaliTest[399:6907] client session: stateChange:0->1 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:44.246Z SendDataTCPServer.js: TCP/IP server has received 1294290 bytes of data
,2015-11-20T13:57:44.259Z SendDataTCPServer.js: TCP/IP server has received 1307430 bytes of data
,2015-11-20T13:57:44.273Z SendDataTCPServer.js: TCP/IP server has received 1311810 bytes of data
,2015-11-20T13:57:45.237Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:45.237Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:45.304 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 14:57:46.247 ThaliTest[399:6907] jxcore: disconnect
,2015-11-20 14:57:46.248 ThaliTest[399:6907] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:46.249 ThaliTest[399:6907] client session: disconnect
,2015-11-20 14:57:46.249 ThaliTest[399:6907] client session: stateChange:1->0 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:46.250 ThaliTest[399:6907] client session: fireConnectCallback: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:57:46.251 ThaliTest[399:6907] jxcore: connect: fail: Peer disconnected
2015-11-20T13:57:46.252Z SendDataConnector.js: CLIENT c,onnected to 0, error: Peer disconnected
2015-11-20T13:57:46.252Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T13:57:46.252Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20 14:57:46.252 ThaliTest[399:6907] jxcore: d,isconnect: success
2015-11-20T13:57:46.253Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:57:46.253Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT9530.n+0V8A== with, availability status: true
2015-11-20T13:57:46.253Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:57:46.254Z SendDataConnector.js: do connect now
2015-11-20 14:57:46.254 ThaliTest[399:6907] jxcore: conne,ct Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:57:46.255 ThaliTest[399:6907] client session: connect
2015-11-20 14:57:46.255 ThaliTest[399:6907] client session: stateChange:0->1 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:47.261Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:47.261Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:48.271 ThaliTest[399:6907] jxcore: disconnect
,2015-11-20 14:57:48.273 ThaliTest[399:6907] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:48.274 ThaliTest[399:6907] client session: disconnect
,2015-11-20 14:57:48.275 ThaliTest[399:6907] client session: stateChange:1->0 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:48.276 ThaliTest[399:6907] client session: fireConnectCallback: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:48.276 ThaliTest[399:6907] jxcore: connect: fail: Peer disconnected
2015-11-20T13:57:48.277Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-11-20T13:57:48.277Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T13:57:48.277Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20 14:57:48.278 ThaliTest[399:6907] jxcore: disconnect: success
2015-11-20T13:57:48.278Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:48.279Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT9530.n+0V8A== with availability status: true
2015-11-20T13:57:48.279Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015,-11-20T13:57:48.279Z SendDataConnector.js: do connect now
,2015-11-20 14:57:48.279 ThaliTest[399:6907] jxcore: connect Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:48.280 ThaliTest[399:6907] client session: connect
,2015-11-20 14:57:48.281 ThaliTest[399:6907] client session: stateChange:0->1 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:48.340Z SendDataTCPServer.js: TCP/IP server has received 1314000 bytes of data
,2015-11-20T13:57:48.387Z SendDataTCPServer.js: TCP/IP server has received 1331520 bytes of data
,2015-11-20T13:57:48.899Z SendDataTCPServer.js: TCP/IP server has received 1343808 bytes of data
,2015-11-20T13:57:48.912Z SendDataTCPServer.js: TCP/IP server has received 1425690 bytes of data
,2015-11-20T13:57:49.284Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:49.285Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:49.904Z SendDataTCPServer.js: TCP/IP server has received 1427880 bytes of data
,2015-11-20T13:57:49.916Z SendDataTCPServer.js: TCP/IP server has received 1434450 bytes of data
,2015-11-20T13:57:49.928Z SendDataTCPServer.js: TCP/IP server has received 1441020 bytes of data
,2015-11-20T13:57:49.941Z SendDataTCPServer.js: TCP/IP server has received 1449780 bytes of data
,2015-11-20T13:57:49.954Z SendDataTCPServer.js: TCP/IP server has received 1451970 bytes of data
,2015-11-20 14:57:50.288 ThaliTest[399:6907] jxcore: disconnect
,2015-11-20 14:57:50.289 ThaliTest[399:6907] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:50.290 ThaliTest[399:6907] client session: disconnect
,2015-11-20 14:57:50.290 ThaliTest[399:6907] client session: stateChange:1->0 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:50.291 ThaliTest[399:6907] client session: fireConnectCallback: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:50.292 ThaliTest[399:6907] jxcore: connect: fail: Peer disconnected
2015-11-20T13:57:50.292Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-11-20T13:57:50.293Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-20T13:57:50.293Z SendDataConnector.js: CLIENT Stop now
2015-11-20 14:57:50.294 ThaliTest[399:6907] jxcore: disconnect
,2015-11-20 14:57:50.295 ThaliTest[399:6907] jxcore: disconnect: fail
2015-11-20T13:57:50.295Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9530.n+0V8A==
---- round done--------
,device[3]: Apple-Iphone6-1_PT8294.ood35g==
2015-11-20T13:57:50.296Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8294.ood35g==
2015-11-20T13:57:50.297Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8294.ood35g==
20,15-11-20T13:57:50.297Z SendDataConnector.js: do connect now
,2015-11-20 14:57:50.297 ThaliTest[399:6907] jxcore: connect Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:50.298 ThaliTest[399:6907] client session: connect
2015-11-20 14:57:50.299 ThaliTest[399:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:50.304 ThaliTest[399:6907] jxcore: disconnect: success
2015-11-20T13:57:50.305Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8294.ood35g==
2015-11-20T13:57:50.305Z SendDataConnector.js: Connect (retry co,unt 0) to peer Apple-Iphone6-1_PT8294.ood35g== with availability status: true
2015-11-20T13:57:50.306Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8294.ood35g==
2015-11-20T13:57:50.306Z SendDataConnector.js: do connect now
2015-11,-20 14:57:50.306 ThaliTest[399:6907] jxcore: connect Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:50.307 ThaliTest[399:6907] client: already connect(ing/ed) to Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:57:50.308 ThaliTest[399:6907] jxcore: connect: fail: Aleady connecting
2015-11-20T13:57:50.309Z SendDataConnector.js: CLIENT conn,ected to 0, error: Aleady connecting
2015-11-20T13:57:50.309Z SendDataConnector.js: CLIENT Can not Connect: Aleady connecting
2015-11-20T13:57:50.310Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T13:57:51.319Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8294.ood35g==
2015-11-20T13:57:51.320Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:52.330 ThaliTest[399:6907] jxcore: disconnect
,2015-11-20 14:57:52.331 ThaliTest[399:6907] client session: disconnectFromPeer: Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:52.332 ThaliTest[399:6907] client session: disconnect
,2015-11-20 14:57:52.333 ThaliTest[399:6907] client session: stateChange:1->0 Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:52.334 ThaliTest[399:6907] client session: fireConnectCallback: Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:52.335 ThaliTest[399:6907] jxcore: connect: fail: Peer disconnected
2015-11-20T13:57:52.335Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T13:57:52.336Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T13:57:52.336Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20 14:57:52.336 ThaliTest[399:6907] jxcore: disconnect: success
2015-11-20T13:57:52.337Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20T13:57:52.337Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT8294.ood35g== with availability status: true
2015-11-20T13:57:52.338Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8294.ood35g==
2015-1,1-20T13:57:52.338Z SendDataConnector.js: do connect now
,2015-11-20 14:57:52.338 ThaliTest[399:6907] jxcore: connect Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:52.339 ThaliTest[399:6907] client session: connect
,2015-11-20 14:57:52.340 ThaliTest[399:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20T13:57:53.241Z SendDataTCPServer.js: TCP/IP server has received 1456066 bytes of data
,2015-11-20T13:57:53.253Z SendDataTCPServer.js: TCP/IP server has received 1473870 bytes of data
,2015-11-20T13:57:53.288Z SendDataTCPServer.js: TCP/IP server has received 1482630 bytes of data
,2015-11-20T13:57:53.300Z SendDataTCPServer.js: TCP/IP server has received 1500150 bytes of data
,2015-11-20T13:57:53.313Z SendDataTCPServer.js: TCP/IP server has received 1545998 bytes of data
,2015-11-20T13:57:53.326Z SendDataTCPServer.js: TCP/IP server has received 1550520 bytes of data
,2015-11-20T13:57:53.338Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20T13:57:53.338Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20T13:57:53.372Z SendDataTCPServer.js: TCP/IP server has received 1561470 bytes of data
,2015-11-20T13:57:53.385Z SendDataTCPServer.js: TCP/IP server has received 1565850 bytes of data
,2015-11-20T13:57:53.499Z SendDataTCPServer.js: TCP/IP server has received 1568040 bytes of data
,2015-11-20T13:57:53.534Z SendDataTCPServer.js: TCP/IP server has received 1581180 bytes of data
,2015-11-20T13:57:53.616Z SendDataTCPServer.js: TCP/IP server has received 1585560 bytes of data
,2015-11-20 14:57:54.350 ThaliTest[399:6907] jxcore: disconnect
2015-11-20 14:57:54.351 ThaliTest[399:6907] client session: disconnectFromPeer: Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:54.352 ThaliTest[399:6907] client session: disconnect
,2015-11-20 14:57:54.353 ThaliTest[399:6907] client session: stateChange:1->0 Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:54.354 ThaliTest[399:6907] client session: fireConnectCallback: Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:54.355 ThaliTest[399:6907] jxcore: connect: fail: Peer disconnected
,2015-11-20T13:57:54.356Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T13:57:54.356Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-20T13:57:54.357Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20 14:57:54.357 ThaliTest[399:6907] jxcore: disconnect: success
2015-11-20T13:57:54.358Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20T13:57:54.358Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT8294.ood35g== with availability status: true
,2015-11-20T13:57:54.359Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8294.ood35g==
2015-11-20T13:57:54.359Z SendDataConnector.js: do connect now
,2015-11-20 14:57:54.359 ThaliTest[399:6907] jxcore: connect Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:54.360 ThaliTest[399:6907] client session: connect
,2015-11-20 14:57:54.361 ThaliTest[399:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20T13:57:55.363Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8294.ood35g==
2015-11-20T13:57:55.364Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:56.372 ThaliTest[399:6907] jxcore: disconnect
2015-11-20 14:57:56.374 ThaliTest[399:6907] client session: disconnectFromPeer: Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:57:56.375 ThaliTest[399:6907] client session: disconnect
2015-11,-20 14:57:56.376 ThaliTest[399:6907] client session: stateChange:1->0 Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:57:56.376 ThaliTest[399:6907] client session: fireConnectCallback: Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:57:56.377 ThaliTest[399:6907] jxcore: connect: fail: Peer disconnected
,2015-11-20T13:57:56.377Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T13:57:56.378Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T13:57:56.378Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20 14:57:56.378 ThaliTest[399:6907] jxcore: disconnect: success
,2015-11-20T13:57:56.379Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8294.ood35g==
2015-11-20T13:57:56.380Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT8294.ood35g== with availability status: ,true
2015-11-20T13:57:56.380Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8294.ood35g==
2015-11-20T13:57:56.380Z SendDataConnector.js: do connect now
,2015-11-20 14:57:56.380 ThaliTest[399:6907] jxcore: connect Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:57:56.381 ThaliTest[399:6907] client session: connect
,2015-11-20 14:57:56.382 ThaliTest[399:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20T13:57:57.383Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8294.ood35g==
2015-11-20T13:57:57.384Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:58.392 ThaliTest[399:6907] jxcore: disconnect
,2015-11-20 14:57:58.393 ThaliTest[399:6907] client session: disconnectFromPeer: Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:57:58.394 ThaliTest[399:6907] client session: disconnect
2015-11-20 14:57:58.396 ThaliTest[399:6907] client session: stateChange,:1->0 Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:58.396 ThaliTest[399:6907] client session: fireConnectCallback: Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:57:58.397 ThaliTest[399:6907] jxcore: connect: fail: Peer disconnected
,2015-11-20T13:57:58.398Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T13:57:58.398Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T13:57:58.399Z SendDataConnector.js: CLIENT Stop now
,2015-11-20 14:57:58.399 ThaliTest[399:6907] jxcore: disconnect
,2015-11-20 14:57:58.401 ThaliTest[399:6907] jxcore: disconnect: fail
,2015-11-20T13:57:58.402Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8294.ood35g==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT738","time":46217,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT9513.+kbAXQ==","time":29567,"result":"Peer disconnected","connections":4},{"name":"Apple-IpadAir2-1_PT9530.n+0V8A==","time":8088,"result":"Pe,er disconnected","connections":5},{"name":"Apple-Iphone6-1_PT8294.ood35g==","time":8101,"result":"Peer disconnected","connections":5}]}
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items
,sendList failed peers count : 3 [100 %]
- Peer ID : Apple-Iphone5s-1_PT9513.+kbAXQ==, Tried : 4
- Peer ID : Apple-IpadAir2-1_PT9530.n+0V8A==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT8294.ood35g==, Tried : 5
sendList never tried peers count : 0 [0 %]
2,015-11-20T13:57:58.410Z SendDataConnector.js: CLIENT Stop now
,2015-11-20 14:57:58.411 ThaliTest[399:6907] jxcore: disconnect: success
,2015-11-20T13:57:58.876Z SendDataTCPServer.js: TCP/IP server has received 1589940 bytes of data
,2015-11-20T13:57:58.888Z SendDataTCPServer.js: TCP/IP server has received 1594320 bytes of data
,2015-11-20T13:57:58.957Z SendDataTCPServer.js: TCP/IP server has received 1600890 bytes of data
,2015-11-20T13:57:58.969Z SendDataTCPServer.js: TCP/IP server has received 1603080 bytes of data
,2015-11-20T13:57:59.376Z SendDataTCPServer.js: TCP/IP server has received 1605270 bytes of data
,2015-11-20T13:57:59.399Z SendDataTCPServer.js: TCP/IP server has received 1607460 bytes of data
,2015-11-20T13:57:59.950Z SendDataTCPServer.js: TCP/IP server has received 1616220 bytes of data
,2015-11-20T13:58:00.045Z SendDataTCPServer.js: TCP/IP server has received 1622790 bytes of data
,2015-11-20T13:58:00.059Z SendDataTCPServer.js: TCP/IP server has received 1660020 bytes of data
,2015-11-20T13:58:00.072Z SendDataTCPServer.js: TCP/IP server has received 1706010 bytes of data
2015-11-20 14:58:00.071 ThaliTest[399:653b] server session: not connected Apple-Iphone6-1_PT8294
,2015-11-20T13:58:00.085Z SendDataTCPServer.js: TCP/IP server has received 1714770 bytes of data
,2015-11-20 14:58:00.577 ThaliTest[399:60b] multipeer session: reset timer
,2015-11-20 14:58:00.578 ThaliTest[399:60b] multipeer session: stop timer
2015-11-20 14:58:00.579 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
,2015-11-20 14:58:00.579 ThaliTest[399:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT8294)
,2015-11-20 14:58:00.580 ThaliTest[399:60b] server session: disconnect
,2015-11-20 14:58:00.581 ThaliTest[399:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT8294
,2015-11-20 14:58:00.585 ThaliTest[399:60b] server session: connect
,2015-11-20 14:58:00.586 ThaliTest[399:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8294
,2015-11-20T13:58:00.590Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-20T13:58:00.591Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
2015-11-20 14:58:00.590 ThaliTest[399:60b] server: accepting invitation Apple-Iphone6-1_PT8294
,2015-11-20 14:58:03.034 ThaliTest[399:b007] server session: connected
2015-11-20 14:58:03.035 ThaliTest[399:b007] server session: stateChange:1->2 Apple-Iphone6-1_PT8294
,2015-11-20 14:58:03.043 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 14:58:03.044 ThaliTest[399:60b] server relay: 0x155cdf00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x156be170 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 14:58:17.679 ThaliTest[399:b007] server session: not connected Apple-Iphone6-1_PT8294
,2015-11-20 14:58:19.763 ThaliTest[399:60b] multipeer session: reset timer
2015-11-20 14:58:19.764 ThaliTest[399:60b] multipeer session: stop timer
,2015-11-20 14:58:19.765 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
,2015-11-20 14:58:19.766 ThaliTest[399:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT8294)
,2015-11-20 14:58:19.766 ThaliTest[399:60b] server session: disconnect
,2015-11-20 14:58:19.767 ThaliTest[399:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT8294
,2015-11-20 14:58:19.768 ThaliTest[399:60b] server session: connect
2015-11-20 14:58:19.768 ThaliTest[399:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8294
,2015-11-20 14:58:19.773 ThaliTest[399:60b] server: accepting invitation Apple-Iphone6-1_PT8294
,2015-11-20 14:58:21.911 ThaliTest[399:653f] server session: connected
,2015-11-20 14:58:21.913 ThaliTest[399:653f] server session: stateChange:1->2 Apple-Iphone6-1_PT8294
,2015-11-20 14:58:21.924 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 14:58:21.925 ThaliTest[399:60b] server relay: 0x155cdf00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1b72ec20 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 14:58:37.279 ThaliTest[399:af13] server session: not connected Apple-Iphone6-1_PT8294
,2015-11-20 14:58:38.351 ThaliTest[399:60b] multipeer session: reset timer
,2015-11-20 14:58:38.352 ThaliTest[399:60b] multipeer session: stop timer
,2015-11-20 14:58:38.353 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
,2015-11-20 14:58:38.354 ThaliTest[399:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT8294)
,2015-11-20 14:58:38.355 ThaliTest[399:60b] server session: disconnect
,2015-11-20 14:58:38.355 ThaliTest[399:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT8294
,2015-11-20 14:58:38.356 ThaliTest[399:60b] server session: connect
,2015-11-20 14:58:38.358 ThaliTest[399:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8294
,2015-11-20 14:58:38.361 ThaliTest[399:60b] server: accepting invitation Apple-Iphone6-1_PT8294
,2015-11-20 14:58:41.145 ThaliTest[399:760f] server session: connected
,2015-11-20 14:58:41.147 ThaliTest[399:760f] server session: stateChange:1->2 Apple-Iphone6-1_PT8294
,2015-11-20 14:58:41.155 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 14:58:41.156 ThaliTest[399:60b] server relay: 0x155cdf00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1b4eb630 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 14:58:55.556 ThaliTest[399:653f] server session: not connected Apple-Iphone6-1_PT8294
,2015-11-20 14:58:57.504 ThaliTest[399:60b] multipeer session: reset timer
2015-11-20 14:58:57.505 ThaliTest[399:60b] multipeer session: stop timer
,2015-11-20 14:58:57.505 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
2015-11-20 14:58:57.506 ThaliTest[399:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT8294)
,2015-11-20 14:58:57.507 ThaliTest[399:60b] server session: disconnect
,2015-11-20 14:58:57.507 ThaliTest[399:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT8294
2015-11-20 14:58:57.508 ThaliTest[399:60b] server session: connect
2015-11-20 14:58:57.509 ThaliTest[399:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8294
,2015-11-20 14:58:57.513 ThaliTest[399:60b] server: accepting invitation Apple-Iphone6-1_PT8294
,2015-11-20 14:58:59.758 ThaliTest[399:8943] server session: connected
,2015-11-20 14:58:59.759 ThaliTest[399:8943] server session: stateChange:1->2 Apple-Iphone6-1_PT8294
,2015-11-20 14:58:59.768 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 14:58:59.768 ThaliTest[399:60b] server relay: 0x1b5fa8b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1b4eed40 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 14:59:14.321 ThaliTest[399:653f] server session: not connected Apple-Iphone6-1_PT8294
,2015-11-20 14:59:27.507 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 14:59:27.778 ThaliTest[399:60b] client: found peer: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:59:27.786 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:59:29.807 ThaliTest[399:60b] multipeer session: reset timer
2015-11-20 14:59:29.809 ThaliTest[399:60b] multipeer session: stop timer
,2015-11-20 14:59:29.810 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
,2015-11-20 14:59:29.810 ThaliTest[399:60b] server session: connect
,2015-11-20 14:59:29.811 ThaliTest[399:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:29.814 ThaliTest[399:60b] server: accepting invitation Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:30.719 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:59:30.721 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 14:59:32.634 ThaliTest[399:bd1b] server session: connected
,2015-11-20 14:59:32.635 ThaliTest[399:bd1b] server session: stateChange:1->2 Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:32.647 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 14:59:32.647 ThaliTest[399:60b] server relay: 0x1b1b1c00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x155b66d0 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Conne,ction refused} 
,2015-11-20 14:59:33.219 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 14:59:33.221 ThaliTest[399:60b] multipeer session: reset timer
,2015-11-20 14:59:33.223 ThaliTest[399:60b] multipeer session: stop timer
,2015-11-20 14:59:33.224 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
,2015-11-20 14:59:33.225 ThaliTest[399:60b] server session: connect
,2015-11-20 14:59:33.226 ThaliTest[399:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT9530
,2015-11-20 14:59:33.230 ThaliTest[399:60b] server: accepting invitation Apple-IpadAir2-1_PT9530
,2015-11-20 14:59:35.966 ThaliTest[399:8947] server session: connected
,2015-11-20 14:59:35.968 ThaliTest[399:8947] server session: stateChange:1->2 Apple-IpadAir2-1_PT9530
,2015-11-20 14:59:36.228 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 14:59:36.229 ThaliTest[399:60b] server relay: 0x1b4f4c40 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1b67b880 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 14:59:47.304 ThaliTest[399:8947] server session: not connected Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:49.399 ThaliTest[399:60b] multipeer session: reset timer
2015-11-20 14:59:49.400 ThaliTest[399:60b] multipeer session: stop timer
,2015-11-20 14:59:49.401 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
,2015-11-20 14:59:49.402 ThaliTest[399:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9513)
,2015-11-20 14:59:49.403 ThaliTest[399:60b] server session: disconnect
,2015-11-20 14:59:49.403 ThaliTest[399:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:49.404 ThaliTest[399:60b] server session: connect
2015-11-20 14:59:49.405 ThaliTest[399:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:49.408 ThaliTest[399:60b] server: accepting invitation Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:50.050 ThaliTest[399:8947] server session: not connected Apple-IpadAir2-1_PT9530
,2015-11-20 14:59:51.531 ThaliTest[399:bd1b] server session: connected
2015-11-20 14:59:51.533 ThaliTest[399:bd1b] server session: stateChange:1->2 Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:51.543 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 14:59:51.543 ThaliTest[399:60b] server relay: 0x1b4e9a10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1b58a110 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 14:59:52.083 ThaliTest[399:60b] multipeer session: reset timer
,2015-11-20 14:59:52.084 ThaliTest[399:60b] multipeer session: stop timer
,2015-11-20 14:59:52.085 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
2015-11-20 14:59:52.086 ThaliTest[399:60b] server: disconnecting to refresh session (Apple-IpadAir2-1_PT9530)
,2015-11-20 14:59:52.087 ThaliTest[399:60b] server session: disconnect
2015-11-20 14:59:52.087 ThaliTest[399:60b] server session: stateChange:2->0 Apple-IpadAir2-1_PT9530
,2015-11-20 14:59:52.088 ThaliTest[399:60b] server session: connect
2015-11-20 14:59:52.088 ThaliTest[399:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT9530
,2015-11-20 14:59:52.093 ThaliTest[399:60b] server: accepting invitation Apple-IpadAir2-1_PT9530
,2015-11-20 14:59:54.780 ThaliTest[399:8947] server session: connected
,2015-11-20 14:59:54.781 ThaliTest[399:8947] server session: stateChange:1->2 Apple-IpadAir2-1_PT9530
,2015-11-20 14:59:54.830 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 14:59:54.831 ThaliTest[399:60b] server relay: 0x1b4581c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1b39f360 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 15:00:00.991 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 15:00:00.992 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:00:02.034 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:00:06.189 ThaliTest[399:7e0f] server session: not connected Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:08.417 ThaliTest[399:60b] multipeer session: reset timer
2015-11-20 15:00:08.418 ThaliTest[399:60b] multipeer session: stop timer
,2015-11-20 15:00:08.419 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
,2015-11-20 15:00:08.420 ThaliTest[399:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9513)
,2015-11-20 15:00:08.420 ThaliTest[399:60b] server session: disconnect
,2015-11-20 15:00:08.421 ThaliTest[399:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:08.422 ThaliTest[399:60b] server session: connect
2015-11-20 15:00:08.422 ThaliTest[399:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:08.426 ThaliTest[399:60b] server: accepting invitation Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:08.970 ThaliTest[399:bd1b] server session: not connected Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:10.915 ThaliTest[399:7e0f] server session: connected
,2015-11-20 15:00:10.916 ThaliTest[399:7e0f] server session: stateChange:1->2 Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:10.925 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 15:00:10.927 ThaliTest[399:60b] server relay: 0x1b4e9a10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1b24b740 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 15:00:11.061 ThaliTest[399:60b] multipeer session: reset timer
,2015-11-20 15:00:11.062 ThaliTest[399:60b] multipeer session: stop timer
,2015-11-20 15:00:11.063 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
,2015-11-20 15:00:11.064 ThaliTest[399:60b] server: disconnecting to refresh session (Apple-IpadAir2-1_PT9530)
,2015-11-20 15:00:11.065 ThaliTest[399:60b] server session: disconnect
,2015-11-20 15:00:11.065 ThaliTest[399:60b] server session: stateChange:2->0 Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:11.066 ThaliTest[399:60b] server session: connect
,2015-11-20 15:00:11.067 ThaliTest[399:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:11.071 ThaliTest[399:60b] server: accepting invitation Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:14.064 ThaliTest[399:ae23] server session: connected
,2015-11-20 15:00:14.065 ThaliTest[399:ae23] server session: stateChange:1->2 Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:14.105 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 15:00:14.105 ThaliTest[399:60b] server relay: 0x1b4f6ad0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1b621950 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 15:00:25.611 ThaliTest[399:8947] server session: not connected Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:29.247 ThaliTest[399:60b] multipeer session: reset timer
,2015-11-20 15:00:29.248 ThaliTest[399:60b] multipeer session: stop timer
2015-11-20 15:00:29.249 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
,2015-11-20 15:00:29.249 ThaliTest[399:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9513)
,2015-11-20 15:00:29.250 ThaliTest[399:60b] server session: disconnect
,2015-11-20 15:00:29.250 ThaliTest[399:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:29.251 ThaliTest[399:60b] server session: connect
2015-11-20 15:00:29.252 ThaliTest[399:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:29.255 ThaliTest[399:60b] server: accepting invitation Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:29.921 ThaliTest[399:953f] server session: not connected Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:30.300 ThaliTest[399:60b] multipeer session: reset timer
,2015-11-20 15:00:30.302 ThaliTest[399:60b] multipeer session: stop timer
2015-11-20 15:00:30.303 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
,2015-11-20 15:00:30.303 ThaliTest[399:60b] server: disconnecting to refresh session (Apple-IpadAir2-1_PT9530)
2015-11-20 15:00:30.304 ThaliTest[399:60b] server session: disconnect
,2015-11-20 15:00:30.305 ThaliTest[399:60b] server session: stateChange:2->0 Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:30.306 ThaliTest[399:60b] server session: connect
2015-11-20 15:00:30.306 ThaliTest[399:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:30.310 ThaliTest[399:60b] server: accepting invitation Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:32.405 ThaliTest[399:ae23] server session: connected
,2015-11-20 15:00:32.407 ThaliTest[399:ae23] server session: stateChange:1->2 Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:32.419 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 15:00:32.420 ThaliTest[399:60b] server relay: 0x1b415530 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1b267db0 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Conne,ction refused} 
,2015-11-20 15:00:32.977 ThaliTest[399:ae23] server session: connected
,2015-11-20 15:00:32.978 ThaliTest[399:ae23] server session: stateChange:1->2 Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:33.014 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 15:00:33.015 ThaliTest[399:60b] server relay: 0x1b5d1a90 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1b5d2560 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 15:00:47.092 ThaliTest[399:ae23] server session: not connected Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:47.748 ThaliTest[399:953f] server session: not connected Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:49.225 ThaliTest[399:60b] multipeer session: reset timer
2015-11-20 15:00:49.226 ThaliTest[399:60b] multipeer session: stop timer
,2015-11-20 15:00:49.227 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
,2015-11-20 15:00:49.227 ThaliTest[399:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9513)
,2015-11-20 15:00:49.228 ThaliTest[399:60b] server session: disconnect
,2015-11-20 15:00:49.229 ThaliTest[399:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:49.229 ThaliTest[399:60b] server session: connect
,2015-11-20 15:00:49.231 ThaliTest[399:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:49.234 ThaliTest[399:60b] server: accepting invitation Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:49.296 ThaliTest[399:60b] multipeer session: reset timer
,2015-11-20 15:00:49.298 ThaliTest[399:60b] multipeer session: stop timer
,2015-11-20 15:00:49.299 ThaliTest[399:60b] multipeer session: start timer: 0x1b692af0
,2015-11-20 15:00:49.299 ThaliTest[399:60b] server: disconnecting to refresh session (Apple-IpadAir2-1_PT9530)
,2015-11-20 15:00:49.300 ThaliTest[399:60b] server session: disconnect
,2015-11-20 15:00:49.301 ThaliTest[399:60b] server session: stateChange:2->0 Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:49.301 ThaliTest[399:60b] server session: connect
,2015-11-20 15:00:49.302 ThaliTest[399:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:49.928 ThaliTest[399:60b] server: accepting invitation Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:52.089 ThaliTest[399:dd53] server session: connected
,2015-11-20 15:00:52.091 ThaliTest[399:dd53] server session: stateChange:1->2 Apple-Iphone5s-1_PT9513
,2015-11-20 15:00:52.100 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 15:00:52.101 ThaliTest[399:60b] server relay: 0x1b2f9e60 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1b4ce900 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 15:00:52.543 ThaliTest[399:953f] server session: connected
,2015-11-20 15:00:52.544 ThaliTest[399:953f] server session: stateChange:1->2 Apple-IpadAir2-1_PT9530
,2015-11-20 15:00:52.563 ThaliTest[399:60b] server relay: socket disconnected
,2015-11-20 15:00:52.564 ThaliTest[399:60b] server relay: 0x1b69c6d0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1b5dadb0 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 15:01:07.215 ThaliTest[399:953f] server session: not connected Apple-Iphone5s-1_PT9513
,2015-11-20 15:01:12.266 ThaliTest[399:60b] client: lost peer: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 15:01:12.267 ThaliTest[399:60b] client session: onPeerLost: Apple-IpadAir2-1_PT9530.n+0V8A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9530.n+0V8A==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:01:18.198 ThaliTest[399:953f] server session: not connected Apple-IpadAir2-1_PT9530
,2015-11-20 15:01:19.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:01:19.309 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:01:30.090 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 15:01:30.091 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:01:34.756 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:01:49.300 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:01:49.309 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:01:59.971 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:01:59.973 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:02:04.771 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:02:19.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:02:19.310 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:02:29.912 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 15:02:29.913 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:02:34.661 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:02:49.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:02:49.310 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:02:59.912 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:02:59.913 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:03:04.926 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:03:19.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:03:19.310 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:03:30.126 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 15:03:30.127 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:03:34.810 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:03:49.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:03:49.310 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:04:00.001 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 15:04:00.002 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:04:04.797 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:04:19.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:04:19.311 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:04:49.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:04:49.309 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:04:59.909 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:04:59.911 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:05:04.934 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:05:19.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:05:19.309 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:05:30.128 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 15:05:30.129 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:05:34.795 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:05:49.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:05:49.309 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:05:59.992 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 15:05:59.993 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:06:04.657 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:06:19.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:06:19.310 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:06:30.394 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 15:06:30.395 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:06:35.063 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:06:49.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:07:19.300 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:07:19.309 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 15:07:30.124 ThaliTest[399:60b] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 15:07:30.125 ThaliTest[399:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:07:34.790 ThaliTest[399:60b] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:07:49.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:08:19.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:08:49.300 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:09:19.300 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:09:49.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:10:19.300 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:10:49.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:11:19.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:11:49.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:12:19.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:12:49.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:13:19.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:13:49.301 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:14:19.300 ThaliTest[399:60b] multipeer session: restart
,2015-11-20 15:14:49.300 ThaliTest[399:60b] multipeer session: restart

```
