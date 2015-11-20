#### Test 513350289df1748_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350289df1748/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/93D358C4-6C04-445B-AB91-ABFCA707FE36/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/93D358C4-6C04-445B-AB91-ABFCA707FE36/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350289df1748/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350289df1748/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/DDE9667A-FB2D-4268-B149-BA6C4637A95C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51317"
,(lldb)     command script import "/tmp/93D358C4-6C04-445B-AB91-ABFCA707FE36/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 13:38:10.321 ThaliTest[390:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 13:38:10.325 ThaliTest[390:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-20 13:38:10.332 ThaliTest[390:60b] Unlimited access to network resources
,2015-11-20 13:38:10.339 ThaliTest[390:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 13:38:21.021 ThaliTest[390:60b] Resetting plugins due to page load.
,2015-11-20 13:38:21.884 ThaliTest[390:60b] Finished load of: file:///var/mobile/Applications/DDE9667A-FB2D-4268-B149-BA6C4637A95C/ThaliTest.app/www/index.html
,2015-11-20 13:38:22.062 ThaliTest[390:60b] JXcore Cordova plugin initializing
,2015-11-20 13:38:22.064 ThaliTest[390:6607] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT6611
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
,-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
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
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
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
,found interfaceName: en0
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
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::d81d:17ff:fea1:b66
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"10000000\",\"conReTryTimeout\":\"1000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":,[]}
,Start now : testSendData.js
stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 53278
,2015-11-20 13:46:18.842 ThaliTest[390:6607] jxcore: startBroadcasting
,2015-11-20 13:46:18.852 ThaliTest[390:6607] server: starting Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:46:18.854 ThaliTest[390:6607] multipeer session: start timer: 0x1a648c70
2015-11-20 13:46:18.857 ThaliTest[390:6607] THEMultipeerSession initialized peer Apple-Iphone5-1_PT6611
2015-11-20 13:46:18.858 ThaliTest[390:6607] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-20T12:46:18.863Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-20 13:46:19.191 ThaliTest[390:60b] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:19.196Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:19.196Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:19.266 ThaliTest[390:60b] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:46:20.065 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT545.qwwthQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:46:20.203 ThaliTest[390:6607] jxcore: disconnect
,2015-11-20 13:46:20.204 ThaliTest[390:6607] jxcore: disconnect: fail
,2015-11-20T12:46:20.206Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:20.207Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5s-1_PT7169./ZcTuw== with availability status: true
,2015-11-20T12:46:20.207Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:20.207Z SendDataConnector.js: do connect now
,2015-11-20 13:46:20.208 ThaliTest[390:6607] jxcore: connect Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:20.209 ThaliTest[390:6607] client session: connect
,2015-11-20 13:46:20.209 ThaliTest[390:6607] client session: stateChange:0->1 Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:22.715 ThaliTest[390:710b] client session: connected
,2015-11-20 13:46:22.716 ThaliTest[390:710b] client session: stateChange:1->2 Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:22.727 ThaliTest[390:6237] client session: fireConnectCallback: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:46:22.728 ThaliTest[390:6237] jxcore: connect: success
,2015-11-20T12:46:22.729Z SendDataConnector.js: CLIENT connected to 53281, error: null
2015-11-20T12:46:22.729Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:46:22.731 ThaliTest[390:60b] client: relay established
,2015-11-20 13:46:22.732 ThaliTest[390:60b] client: new accepted socket: 0x1a63b300
,2015-11-20T12:46:22.743Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:46:33.243Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:34.136Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:34.137Z SendDataConnector.js: CLIENT is data received : 190000
,2015-11-20T12:46:34.635Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:34.636Z SendDataConnector.js: CLIENT is data received : 410000
,2015-11-20T12:46:38.395Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:38.396Z SendDataConnector.js: CLIENT is data received : 1920000
,2015-11-20T12:46:39.737Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:39.738Z SendDataConnector.js: CLIENT is data received : 2430000
,2015-11-20T12:46:42.310Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:42.311Z SendDataConnector.js: CLIENT is data received : 3470000
,2015-11-20T12:46:43.529Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:43.530Z SendDataConnector.js: CLIENT is data received : 4000000
,2015-11-20T12:46:44.763Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:44.764Z SendDataConnector.js: CLIENT is data received : 4640000
,2015-11-20T12:46:45.218Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:45.218Z SendDataConnector.js: CLIENT is data received : 4770000
,2015-11-20 13:46:49.365 ThaliTest[390:60b] multipeer session: restart
2015-11-20T12:46:49.367Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:49.367Z SendDataConnector.js: CLIENT is data received, : 6370000
,2015-11-20T12:46:50.930Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:50.931Z SendDataConnector.js: CLIENT is data received : 7000000
,2015-11-20 13:46:55.276 ThaliTest[390:60b] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:46:55.278 ThaliTest[390:60b] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:46:55.278Z SendDataConnector.js: resetDataTimeout, called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:55.279Z SendDataConnector.js: CLIENT is data received : 8210000
,2015-11-20 13:46:57.171 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:46:57.185Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:57.186Z SendDataConnector.js: CLIENT is data received : 8770000
,2015-11-20 13:46:59.771 ThaliTest[390:60b] multipeer session: reset timer
2015-11-20 13:46:59.771 ThaliTest[390:60b] multipeer session: stop timer
2015-11-20 13:46:59.772 ThaliTest[390:60b] multipeer session: start timer: 0x1a648c70
,2015-11-20 13:46:59.773 ThaliTest[390:60b] server session: connect
2015-11-20 13:46:59.774 ThaliTest[390:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8859
,2015-11-20T12:46:59.778Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:59.779Z SendDataConnector.js: CLIENT is data received : 9850000
,2015-11-20 13:46:59.782 ThaliTest[390:60b] server: accepting invitation Apple-Iphone6-1_PT8859
,2015-11-20T12:47:00.177Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:00.179Z SendDataConnector.js: CLIENT is data received : 9860000
,2015-11-20T12:47:00.191Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:47:00.191Z SendDataConnector.js: CLIENT is data received : 9890000
,2015-11-20T12:47:00.216Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:00.217Z SendDataConnector.js: CLIENT is data received : 9910000
,2015-11-20T12:47:00.307Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:00.308Z SendDataConnector.js: CLIENT is data received : 9940000
,2015-11-20T12:47:00.320Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:47:00.321Z SendDataConnector.js: CLIENT is data received : 9960000
,2015-11-20T12:47:00.368Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:47:00.368Z SendDataConnector.js: CLIENT is data received : 9980000
,2015-11-20T12:47:00.691Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:47:00.691Z SendDataConnector.js: CLIENT is data received : 10000000
2015-11-20T12:47:00.691Z SendDataConnector.js: got all data for this round
,2015-11-20T12:47:00.692Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:47:00.692Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:47:00.693 ThaliTest[390:6607] jxcore: disconnect
,2015-11-20 13:47:00.694 ThaliTest[390:6607] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:47:00.694 ThaliTest[390:6607] client session: disconnect
,2015-11-20 13:47:00.695 ThaliTest[390:6607] client session: stateChange:2->0 Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:47:00.697 ThaliTest[390:6607] jxcore: disconnect: success
,2015-11-20T12:47:00.698Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7169./ZcTuw==
---- round done--------
,device[2]: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:00.704Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:00.704Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:00.793 ThaliTest[390:60b] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:00.794 ThaliTest[390:60b] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:47:01.714 ThaliTest[390:6607] jxcore: disconnect
,2015-11-20 13:47:01.716 ThaliTest[390:6607] jxcore: disconnect: fail
2015-11-20T12:47:01.718Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:01.718Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone6-1_PT8859.CKR/JA== with availability status: true
2015-11-20T12:47:01.718Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:01.719Z SendDataConnector.js: do connect now
,2015-11-20 13:47:01.719 ThaliTest[390:6607] jxcore: connect Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:01.720 ThaliTest[390:6607] client: connect: unreachable Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:47:01.721 ThaliTest[390:6607] jxcore: connect: fail: Peer unreachable
2015-11-20T12:47:01.721Z SendDataConnector.js: CLIENT connected t,o 0, error: Peer unreachable
2015-11-20T12:47:01.722Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-11-20T12:47:01.722Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:47:02.729Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:02.730Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:03.736 ThaliTest[390:6607] jxcore: disconnect
,2015-11-20 13:47:03.737 ThaliTest[390:6607] jxcore: disconnect: fail
2015-11-20T12:47:03.738Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:03.739Z SendDataConnector.js: Connect (retry count, 1) to peer Apple-Iphone6-1_PT8859.CKR/JA== with availability status: true
2015-11-20T12:47:03.739Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:03.739Z SendDataConnector.js: do connect now
2015-11-20 13:47:03.740 ThaliTest[390:6607] jxcore: connect Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:03.740 ThaliTest[390:6607] client: connect: unreachable Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:03.741 ThaliTest[390:6607] jxcore: connect: fail: Peer unreachable
2015-11-20T12:47:03.742Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-20T12:47:03.742Z SendDataConnector.js: CLIENT Can not Connect: Peer ,unreachable
,2015-11-20T12:47:03.742Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:47:04.749Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:04.750Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:05.758 ThaliTest[390:6607] jxcore: disconnect
,2015-11-20 13:47:05.759 ThaliTest[390:6607] jxcore: disconnect: fail
2015-11-20T12:47:05.761Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:05.761Z SendDataConnector.js: Connect (retry count, 2) to peer Apple-Iphone6-1_PT8859.CKR/JA== with availability status: true
2015-11-20T12:47:05.762Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:05.762Z SendDataConnector.js: do connect now
2015-11-20 13:47:05.762 ThaliTest[390:6607] jxcore: connect Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:05.763 ThaliTest[390:6607] client: connect: unreachable Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:05.763 ThaliTest[390:6607] jxcore: connect: fail: Peer unreachable
2015-11-20T12:47:05.764Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-20T12:47:05.764Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-11-20T12:47:05.764Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:47:06.773Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:06.773Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:07.086 ThaliTest[390:60b] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:47:07.774 ThaliTest[390:6607] jxcore: disconnect
2015-11-20 13:47:07.775 ThaliTest[390:6607] jxcore: disconnect: fail
,2015-11-20T12:47:07.777Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:07.777Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT8859.CKR/JA== with availability status: ,true
2015-11-20T12:47:07.777Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:07.778Z SendDataConnector.js: do connect now
,2015-11-20 13:47:07.778 ThaliTest[390:6607] jxcore: connect Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:07.779 ThaliTest[390:6607] client session: connect
,2015-11-20 13:47:07.779 ThaliTest[390:6607] client session: stateChange:0->1 Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:09.176 ThaliTest[390:60b] multipeer session: reset timer
2015-11-20 13:47:09.177 ThaliTest[390:60b] multipeer session: stop timer
,2015-11-20 13:47:09.178 ThaliTest[390:60b] multipeer session: start timer: 0x1a648c70
,2015-11-20 13:47:09.179 ThaliTest[390:60b] server session: connect
2015-11-20 13:47:09.180 ThaliTest[390:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT545
,2015-11-20 13:47:09.183 ThaliTest[390:60b] server: accepting invitation Apple-IpadAir2-1_PT545
,2015-11-20 13:47:10.844 ThaliTest[390:851b] client session: connected
,2015-11-20 13:47:10.846 ThaliTest[390:851b] client session: stateChange:1->2 Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:10.966 ThaliTest[390:9007] client session: fireConnectCallback: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:10.967 ThaliTest[390:9007] jxcore: connect: success
,2015-11-20T12:47:10.968Z SendDataConnector.js: CLIENT connected to 53287, error: null
2015-11-20T12:47:10.969Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:47:10.970 ThaliTest[390:60b] client: relay established
,2015-11-20 13:47:10.971 ThaliTest[390:60b] client: new accepted socket: 0x1a2678f0
,2015-11-20T12:47:10.981Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:47:11.820 ThaliTest[390:851b] server session: connected
2015-11-20 13:47:11.821 ThaliTest[390:851b] server session: stateChange:1->2 Apple-IpadAir2-1_PT545
,2015-11-20 13:47:11.829 ThaliTest[390:60b] server relay: connected (to port: 53278)
,2015-11-20 13:47:20.156 ThaliTest[390:60b] multipeer session: reset timer
2015-11-20 13:47:20.157 ThaliTest[390:60b] multipeer session: stop timer
2015-11-20 13:47:20.157 ThaliTest[390:60b] multipeer session: start timer: 0x1a648c70
2015-11-20 13:47:20.,158 ThaliTest[390:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT8859)
2015-11-20 13:47:20.158 ThaliTest[390:60b] server session: disconnect
2015-11-20 13:47:20.159 ThaliTest[390:60b] server session: stateChange:1->0 Apple-Iphone6-1_PT8,859
2015-11-20 13:47:20.160 ThaliTest[390:60b] server session: connect
2015-11-20 13:47:20.160 ThaliTest[390:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8859
,2015-11-20 13:47:20.167 ThaliTest[390:60b] server: accepting invitation Apple-Iphone6-1_PT8859
,2015-11-20T12:47:22.759Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:22.947 ThaliTest[390:9c0b] server session: connected
2015-11-20 13:47:22.948 ThaliTest[390:9c0b] server session: stateChange:1->2 Apple-Iphone6-1_PT8859
,2015-11-20T12:47:23.094Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:47:23.109Z SendDataTCPServer.js: TCP/IP server has received 131072 bytes of data
,2015-11-20T12:47:23.112Z SendDataTCPServer.js: TCP/IP server has received 262144 bytes of data
,2015-11-20T12:47:23.115Z SendDataTCPServer.js: TCP/IP server has received 393216 bytes of data
,2015-11-20T12:47:23.120Z SendDataTCPServer.js: TCP/IP server has received 524288 bytes of data
,2015-11-20T12:47:23.124Z SendDataTCPServer.js: TCP/IP server has received 655360 bytes of data
,2015-11-20T12:47:23.128Z SendDataTCPServer.js: TCP/IP server has received 786432 bytes of data
,2015-11-20T12:47:23.133Z SendDataTCPServer.js: TCP/IP server has received 917504 bytes of data
2015-11-20T12:47:23.136Z SendDataTCPServer.js: TCP/IP server has received 1048576 bytes of data
,2015-11-20T12:47:23.139Z SendDataTCPServer.js: TCP/IP server has received 1179648 bytes of data
,2015-11-20T12:47:23.145Z SendDataTCPServer.js: TCP/IP server has received 1310720 bytes of data
,2015-11-20T12:47:23.149Z SendDataTCPServer.js: TCP/IP server has received 1441792 bytes of data
,2015-11-20T12:47:23.154Z SendDataTCPServer.js: TCP/IP server has received 1572864 bytes of data
,2015-11-20T12:47:23.159Z SendDataTCPServer.js: TCP/IP server has received 1703936 bytes of data
,2015-11-20T12:47:23.162Z SendDataTCPServer.js: TCP/IP server has received 1835008 bytes of data
,2015-11-20T12:47:23.166Z SendDataTCPServer.js: TCP/IP server has received 1966080 bytes of data
,2015-11-20T12:47:23.169Z SendDataTCPServer.js: TCP/IP server has received 2097152 bytes of data
,2015-11-20T12:47:23.172Z SendDataTCPServer.js: TCP/IP server has received 2228224 bytes of data
,2015-11-20T12:47:23.175Z SendDataTCPServer.js: TCP/IP server has received 2359296 bytes of data
,2015-11-20T12:47:23.178Z SendDataTCPServer.js: TCP/IP server has received 2490368 bytes of data
,2015-11-20T12:47:23.182Z SendDataTCPServer.js: TCP/IP server has received 2621440 bytes of data
,2015-11-20T12:47:23.185Z SendDataTCPServer.js: TCP/IP server has received 2752512 bytes of data
,2015-11-20T12:47:23.189Z SendDataTCPServer.js: TCP/IP server has received 2883584 bytes of data
,2015-11-20T12:47:23.194Z SendDataTCPServer.js: TCP/IP server has received 3014656 bytes of data
,2015-11-20T12:47:23.196Z SendDataTCPServer.js: TCP/IP server has received 3124988 bytes of data
,2015-11-20T12:47:23.224Z SendDataTCPServer.js: TCP/IP server has received 3256060 bytes of data
,2015-11-20T12:47:23.228Z SendDataTCPServer.js: TCP/IP server has received 3387132 bytes of data
,2015-11-20T12:47:23.234Z SendDataTCPServer.js: TCP/IP server has received 3518204 bytes of data
,2015-11-20T12:47:23.255Z SendDataTCPServer.js: TCP/IP server has received 3649276 bytes of data
,2015-11-20T12:47:23.282Z SendDataTCPServer.js: TCP/IP server has received 3780348 bytes of data
,2015-11-20T12:47:23.292Z SendDataTCPServer.js: TCP/IP server has received 3911420 bytes of data
,2015-11-20T12:47:23.294Z SendDataTCPServer.js: TCP/IP server has received 4042492 bytes of data
,2015-11-20T12:47:23.299Z SendDataTCPServer.js: TCP/IP server has received 4173564 bytes of data
,2015-11-20T12:47:23.302Z SendDataTCPServer.js: TCP/IP server has received 4304636 bytes of data
,2015-11-20T12:47:23.308Z SendDataTCPServer.js: TCP/IP server has received 4435708 bytes of data
,2015-11-20T12:47:23.312Z SendDataTCPServer.js: TCP/IP server has received 4566780 bytes of data
,2015-11-20T12:47:23.315Z SendDataTCPServer.js: TCP/IP server has received 4697852 bytes of data
,2015-11-20T12:47:23.318Z SendDataTCPServer.js: TCP/IP server has received 4828924 bytes of data
,2015-11-20T12:47:23.321Z SendDataTCPServer.js: TCP/IP server has received 4959996 bytes of data
,2015-11-20T12:47:23.323Z SendDataTCPServer.js: TCP/IP server has received 5091068 bytes of data
,2015-11-20T12:47:23.326Z SendDataTCPServer.js: TCP/IP server has received 5222140 bytes of data
,2015-11-20T12:47:23.328Z SendDataTCPServer.js: TCP/IP server has received 5353212 bytes of data
,2015-11-20T12:47:23.331Z SendDataTCPServer.js: TCP/IP server has received 5484284 bytes of data
,2015-11-20T12:47:23.333Z SendDataTCPServer.js: TCP/IP server has received 5615356 bytes of data
,2015-11-20T12:47:23.336Z SendDataTCPServer.js: TCP/IP server has received 5746428 bytes of data
,2015-11-20T12:47:23.338Z SendDataTCPServer.js: TCP/IP server has received 5877500 bytes of data
,2015-11-20T12:47:23.341Z SendDataTCPServer.js: TCP/IP server has received 6008572 bytes of data
,2015-11-20T12:47:23.343Z SendDataTCPServer.js: TCP/IP server has received 6139644 bytes of data
,2015-11-20T12:47:23.348Z SendDataTCPServer.js: TCP/IP server has received 6270716 bytes of data
,2015-11-20T12:47:23.351Z SendDataTCPServer.js: TCP/IP server has received 6401788 bytes of data
,2015-11-20T12:47:23.360Z SendDataTCPServer.js: TCP/IP server has received 6532860 bytes of data
,2015-11-20T12:47:23.363Z SendDataTCPServer.js: TCP/IP server has received 6663932 bytes of data
,2015-11-20T12:47:23.365Z SendDataTCPServer.js: TCP/IP server has received 6690450 bytes of data
,2015-11-20T12:47:23.442Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:47:24.388Z SendDataTCPServer.js: TCP/IP server has received 6694546 bytes of data
,2015-11-20 13:47:24.393 ThaliTest[390:60b] server relay: connected (to port: 53278)
,2015-11-20T12:47:24.400Z SendDataTCPServer.js: TCP/IP server has received 6698642 bytes of data
,2015-11-20T12:47:25.768Z SendDataTCPServer.js: TCP/IP server has received 6731410 bytes of data
,2015-11-20T12:47:27.566Z SendDataTCPServer.js: TCP/IP server has received 6749842 bytes of data
,2015-11-20T12:47:28.891Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:28.892Z SendDataConnector.js: CLIENT is data received : 20000
2015-11-20T12:47:28.892Z SendDataTCPServer.js: TCP/IP server has received 4096 bytes of data
,2015-11-20T12:47:28.893Z SendDataTCPServer.js: TCP/IP server has received 6753938 bytes of data
,2015-11-20T12:47:30.461Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:30.462Z SendDataConnector.js: CLIENT is data received : 3720000
,2015-11-20T12:47:30.462Z SendDataTCPServer.js: TCP/IP server has received 6758034 bytes of data
2015-11-20T12:47:30.463Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
,2015-11-20T12:47:31.014Z SendDataTCPServer.js: TCP/IP server has received 6766226 bytes of data
,2015-11-20T12:47:31.068Z SendDataTCPServer.js: TCP/IP server has received 6768274 bytes of data
,2015-11-20T12:47:31.080Z SendDataTCPServer.js: TCP/IP server has received 6780562 bytes of data
,2015-11-20T12:47:31.163Z SendDataTCPServer.js: TCP/IP server has received 6858386 bytes of data
,2015-11-20T12:47:31.177Z SendDataTCPServer.js: TCP/IP server has received 6989458 bytes of data
,2015-11-20T12:47:31.180Z SendDataTCPServer.js: TCP/IP server has received 7120530 bytes of data
,2015-11-20T12:47:31.183Z SendDataTCPServer.js: TCP/IP server has received 7251602 bytes of data
,2015-11-20T12:47:31.186Z SendDataTCPServer.js: TCP/IP server has received 7354002 bytes of data
,2015-11-20T12:47:31.200Z SendDataTCPServer.js: TCP/IP server has received 7485074 bytes of data
,2015-11-20T12:47:31.203Z SendDataTCPServer.js: TCP/IP server has received 7616146 bytes of data
,2015-11-20T12:47:31.205Z SendDataTCPServer.js: TCP/IP server has received 7663250 bytes of data
,2015-11-20T12:47:31.218Z SendDataTCPServer.js: TCP/IP server has received 7794322 bytes of data
,2015-11-20T12:47:31.221Z SendDataTCPServer.js: TCP/IP server has received 7925394 bytes of data
,2015-11-20T12:47:31.228Z SendDataTCPServer.js: TCP/IP server has received 8056466 bytes of data
,2015-11-20T12:47:31.230Z SendDataTCPServer.js: TCP/IP server has received 8185490 bytes of data
,2015-11-20T12:47:31.234Z SendDataTCPServer.js: TCP/IP server has received 30720 bytes of data
,2015-11-20T12:47:31.248Z SendDataTCPServer.js: TCP/IP server has received 8316562 bytes of data
,2015-11-20T12:47:31.251Z SendDataTCPServer.js: TCP/IP server has received 8326802 bytes of data
,2015-11-20T12:47:31.252Z SendDataTCPServer.js: TCP/IP server has received 53248 bytes of data
,2015-11-20T12:47:31.264Z SendDataTCPServer.js: TCP/IP server has received 57344 bytes of data
,2015-11-20T12:47:31.294Z SendDataTCPServer.js: TCP/IP server has received 188416 bytes of data
,2015-11-20T12:47:31.311Z SendDataTCPServer.js: TCP/IP server has received 319488 bytes of data
,2015-11-20T12:47:31.320Z SendDataTCPServer.js: TCP/IP server has received 450560 bytes of data
,2015-11-20T12:47:31.326Z SendDataTCPServer.js: TCP/IP server has received 581632 bytes of data
,2015-11-20T12:47:31.335Z SendDataTCPServer.js: TCP/IP server has received 712704 bytes of data
,2015-11-20T12:47:31.340Z SendDataTCPServer.js: TCP/IP server has received 843776 bytes of data
,2015-11-20T12:47:31.343Z SendDataTCPServer.js: TCP/IP server has received 974848 bytes of data
,2015-11-20T12:47:31.346Z SendDataTCPServer.js: TCP/IP server has received 1105920 bytes of data
,2015-11-20T12:47:31.349Z SendDataTCPServer.js: TCP/IP server has received 1236992 bytes of data
,2015-11-20T12:47:31.412Z SendDataTCPServer.js: TCP/IP server has received 1368064 bytes of data
,2015-11-20T12:47:31.418Z SendDataTCPServer.js: TCP/IP server has received 1499136 bytes of data
,2015-11-20T12:47:31.423Z SendDataTCPServer.js: TCP/IP server has received 1597440 bytes of data
,2015-11-20T12:47:33.459Z SendDataTCPServer.js: TCP/IP server has received 8328850 bytes of data
,2015-11-20T12:47:33.481Z SendDataTCPServer.js: TCP/IP server has received 8355474 bytes of data
2015-11-20T12:47:33.485Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:33.486Z SendDataConnector.js: CLIENT is data received : 3820000
2015-11-20T12:47:33.487Z SendDataTCPServer.js: TCP/IP server has received 1626112 bytes of data
,2015-11-20T12:47:35.605Z SendDataTCPServer.js: TCP/IP server has received 8359570 bytes of data
2015-11-20T12:47:35.606Z SendDataTCPServer.js: TCP/IP server has received 1630208 bytes of data
,2015-11-20T12:47:35.607Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:35.607Z SendDataConnector.js: CLIENT is data received : 7650000
,2015-11-20T12:47:36.562Z SendDataTCPServer.js: TCP/IP server has received 8373906 bytes of data
,2015-11-20T12:47:36.564Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:36.566Z SendDataConnector.js: CLIENT is data received : 8150000
,2015-11-20T12:47:36.567Z SendDataTCPServer.js: TCP/IP server has received 1654784 bytes of data
,2015-11-20T12:47:36.579Z SendDataTCPServer.js: TCP/IP server has received 8384146 bytes of data
,2015-11-20T12:47:40.222Z SendDataTCPServer.js: TCP/IP server has received 8388242 bytes of data
2015-11-20T12:47:40.223Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:40.223Z SendDataConnector.js: CLIENT is data received : 9760000
,2015-11-20T12:47:40.224Z SendDataTCPServer.js: TCP/IP server has received 1658880 bytes of data
,2015-11-20T12:47:40.282Z SendDataTCPServer.js: TCP/IP server has received 8392338 bytes of data
2015-11-20T12:47:40.284Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:40.284Z SendDataConnector.js,: CLIENT is data received : 9840000
,2015-11-20T12:47:40.300Z SendDataTCPServer.js: TCP/IP server has received 8400530 bytes of data
2015-11-20T12:47:40.301Z SendDataTCPServer.js: TCP/IP server has received 1671168 bytes of data
,2015-11-20T12:47:40.316Z SendDataTCPServer.js: TCP/IP server has received 8484498 bytes of data
2015-11-20T12:47:40.320Z SendDataTCPServer.js: TCP/IP server has received 1697792 bytes of data
2015-11-20T12:47:40.321Z SendDataConnector.js: resetDataTimeou,t called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:40.321Z SendDataConnector.js: CLIENT is data received : 9850000
,2015-11-20T12:47:40.335Z SendDataTCPServer.js: TCP/IP server has received 8539794 bytes of data
,2015-11-20T12:47:40.337Z SendDataTCPServer.js: TCP/IP server has received 1730560 bytes of data
,2015-11-20T12:47:40.428Z SendDataTCPServer.js: TCP/IP server has received 8570514 bytes of data
,2015-11-20T12:47:40.464Z SendDataTCPServer.js: TCP/IP server has received 1861632 bytes of data
,2015-11-20T12:47:40.466Z SendDataTCPServer.js: TCP/IP server has received 1992704 bytes of data
,2015-11-20T12:47:40.470Z SendDataTCPServer.js: TCP/IP server has received 2123776 bytes of data
,2015-11-20T12:47:40.473Z SendDataTCPServer.js: TCP/IP server has received 2254848 bytes of data
,2015-11-20T12:47:40.476Z SendDataTCPServer.js: TCP/IP server has received 2385920 bytes of data
,2015-11-20T12:47:40.479Z SendDataTCPServer.js: TCP/IP server has received 2516992 bytes of data
,2015-11-20T12:47:40.482Z SendDataTCPServer.js: TCP/IP server has received 2648064 bytes of data
,2015-11-20T12:47:40.485Z SendDataTCPServer.js: TCP/IP server has received 2779136 bytes of data
,2015-11-20T12:47:40.489Z SendDataTCPServer.js: TCP/IP server has received 2910208 bytes of data
,2015-11-20T12:47:40.492Z SendDataTCPServer.js: TCP/IP server has received 3041280 bytes of data
,2015-11-20T12:47:40.496Z SendDataTCPServer.js: TCP/IP server has received 3172352 bytes of data
,2015-11-20T12:47:40.499Z SendDataTCPServer.js: TCP/IP server has received 3303424 bytes of data
,2015-11-20T12:47:40.502Z SendDataTCPServer.js: TCP/IP server has received 3407872 bytes of data
,2015-11-20T12:47:40.627Z SendDataTCPServer.js: TCP/IP server has received 8701586 bytes of data
,2015-11-20T12:47:40.635Z SendDataTCPServer.js: TCP/IP server has received 8832658 bytes of data
,2015-11-20T12:47:40.650Z SendDataTCPServer.js: TCP/IP server has received 8963730 bytes of data
,2015-11-20T12:47:40.666Z SendDataTCPServer.js: TCP/IP server has received 9094802 bytes of data
,2015-11-20T12:47:40.675Z SendDataTCPServer.js: TCP/IP server has received 9225874 bytes of data
,2015-11-20T12:47:40.695Z SendDataTCPServer.js: TCP/IP server has received 9356946 bytes of data
,2015-11-20T12:47:40.702Z SendDataTCPServer.js: TCP/IP server has received 9488018 bytes of data
,2015-11-20T12:47:40.706Z SendDataTCPServer.js: TCP/IP server has received 9619090 bytes of data
,2015-11-20T12:47:40.730Z SendDataTCPServer.js: TCP/IP server has received 9750162 bytes of data
,2015-11-20T12:47:40.736Z SendDataTCPServer.js: TCP/IP server has received 9881234 bytes of data
,2015-11-20T12:47:40.802Z SendDataTCPServer.js: TCP/IP server has received 9981586 bytes of data
,2015-11-20T12:47:40.834Z SendDataTCPServer.js: TCP/IP server has received 3538944 bytes of data
,2015-11-20T12:47:40.840Z SendDataTCPServer.js: TCP/IP server has received 3670016 bytes of data
,2015-11-20T12:47:40.844Z SendDataTCPServer.js: TCP/IP server has received 3801088 bytes of data
,2015-11-20T12:47:40.850Z SendDataTCPServer.js: TCP/IP server has received 3932160 bytes of data
,2015-11-20T12:47:40.853Z SendDataTCPServer.js: TCP/IP server has received 4063232 bytes of data
,2015-11-20T12:47:40.856Z SendDataTCPServer.js: TCP/IP server has received 4194304 bytes of data
,2015-11-20T12:47:40.860Z SendDataTCPServer.js: TCP/IP server has received 4325376 bytes of data
,2015-11-20T12:47:40.869Z SendDataTCPServer.js: TCP/IP server has received 4456448 bytes of data
,2015-11-20T12:47:40.874Z SendDataTCPServer.js: TCP/IP server has received 4587520 bytes of data
,2015-11-20T12:47:40.886Z SendDataTCPServer.js: TCP/IP server has received 4718592 bytes of data
,2015-11-20T12:47:40.889Z SendDataTCPServer.js: TCP/IP server has received 4849664 bytes of data
,2015-11-20T12:47:40.892Z SendDataTCPServer.js: TCP/IP server has received 4980736 bytes of data
,2015-11-20T12:47:40.896Z SendDataTCPServer.js: TCP/IP server has received 5111808 bytes of data
,2015-11-20T12:47:40.919Z SendDataTCPServer.js: TCP/IP server has received 5242880 bytes of data
,2015-11-20T12:47:40.947Z SendDataTCPServer.js: TCP/IP server has received 5373952 bytes of data
,2015-11-20T12:47:40.955Z SendDataTCPServer.js: TCP/IP server has received 5505024 bytes of data
,2015-11-20T12:47:40.960Z SendDataTCPServer.js: TCP/IP server has received 5636096 bytes of data
,2015-11-20T12:47:40.983Z SendDataTCPServer.js: TCP/IP server has received 5767168 bytes of data
,2015-11-20T12:47:40.998Z SendDataTCPServer.js: TCP/IP server has received 5898240 bytes of data
,2015-11-20T12:47:41.009Z SendDataTCPServer.js: TCP/IP server has received 6029312 bytes of data
,2015-11-20T12:47:41.021Z SendDataTCPServer.js: TCP/IP server has received 6160384 bytes of data
,2015-11-20T12:47:41.028Z SendDataTCPServer.js: TCP/IP server has received 6291456 bytes of data
,2015-11-20T12:47:41.037Z SendDataTCPServer.js: TCP/IP server has received 6422528 bytes of data
,2015-11-20T12:47:41.043Z SendDataTCPServer.js: TCP/IP server has received 6553600 bytes of data
,2015-11-20T12:47:41.049Z SendDataTCPServer.js: TCP/IP server has received 6684672 bytes of data
,2015-11-20T12:47:41.052Z SendDataTCPServer.js: TCP/IP server has received 6815744 bytes of data
,2015-11-20T12:47:41.060Z SendDataTCPServer.js: TCP/IP server has received 6946816 bytes of data
,2015-11-20T12:47:41.066Z SendDataTCPServer.js: TCP/IP server has received 7077888 bytes of data
,2015-11-20T12:47:41.072Z SendDataTCPServer.js: TCP/IP server has received 7208960 bytes of data
,2015-11-20T12:47:41.078Z SendDataTCPServer.js: TCP/IP server has received 7340032 bytes of data
,2015-11-20T12:47:41.085Z SendDataTCPServer.js: TCP/IP server has received 7471104 bytes of data
,2015-11-20T12:47:41.089Z SendDataTCPServer.js: TCP/IP server has received 7602176 bytes of data
,2015-11-20T12:47:41.092Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:41.093Z SendDataConnector.js: CLIENT is data received : 9870000
,2015-11-20T12:47:41.117Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20T12:47:41.123Z SendDataTCPServer.js: TCP/IP server has received 7733248 bytes of data
,2015-11-20T12:47:41.142Z SendDataTCPServer.js: TCP/IP server has received 7864320 bytes of data
,2015-11-20T12:47:41.146Z SendDataTCPServer.js: TCP/IP server has received 7995392 bytes of data
,2015-11-20T12:47:41.149Z SendDataTCPServer.js: TCP/IP server has received 8126464 bytes of data
,2015-11-20T12:47:41.152Z SendDataTCPServer.js: TCP/IP server has received 8257536 bytes of data
,2015-11-20T12:47:41.158Z SendDataTCPServer.js: TCP/IP server has received 8388608 bytes of data
,2015-11-20T12:47:41.167Z SendDataTCPServer.js: TCP/IP server has received 8519680 bytes of data
,2015-11-20T12:47:41.170Z SendDataTCPServer.js: TCP/IP server has received 8650752 bytes of data
,2015-11-20T12:47:41.176Z SendDataTCPServer.js: TCP/IP server has received 8781824 bytes of data
,2015-11-20T12:47:41.179Z SendDataTCPServer.js: TCP/IP server has received 8912896 bytes of data
,2015-11-20T12:47:41.184Z SendDataTCPServer.js: TCP/IP server has received 9043968 bytes of data
,2015-11-20T12:47:41.187Z SendDataTCPServer.js: TCP/IP server has received 9175040 bytes of data
,2015-11-20T12:47:41.192Z SendDataTCPServer.js: TCP/IP server has received 9306112 bytes of data
,2015-11-20T12:47:41.203Z SendDataTCPServer.js: TCP/IP server has received 9412608 bytes of data
,2015-11-20T12:47:41.225Z SendDataTCPServer.js: TCP/IP server has received 9543680 bytes of data
,2015-11-20T12:47:41.228Z SendDataTCPServer.js: TCP/IP server has received 9586688 bytes of data
2015-11-20T12:47:41.231Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:41.233Z SendDataConnector.js: CLIENT is data received : 9940000
,2015-11-20T12:47:41.247Z SendDataTCPServer.js: TCP/IP server has received 9717760 bytes of data
,2015-11-20T12:47:41.252Z SendDataTCPServer.js: TCP/IP server has received 9848832 bytes of data
,2015-11-20T12:47:41.256Z SendDataTCPServer.js: TCP/IP server has received 9916416 bytes of data
2015-11-20T12:47:41.258Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:47:41.259Z SendDataConnector.js: CLIENT is data received : 9990000
,2015-11-20T12:47:41.272Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20T12:47:41.274Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:41.275Z SendDataConnector.js: CLIENT is data received : 10000000
2015-11-20T12:47:41.275Z SendDataConnector.js: got all data for this round
,2015-11-20T12:47:41.275Z SendDataConnector.js: CLIENT Stop now
2015-11-20T12:47:41.275Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:47:41.276 ThaliTest[390:6607] jxcore: disconnect
,2015-11-20 13:47:41.277 ThaliTest[390:6607] client session: disconnectFromPeer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:47:41.278 ThaliTest[390:6607] client session: disconnect
,2015-11-20 13:47:41.278 ThaliTest[390:6607] client session: stateChange:2->0 Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:41.280 ThaliTest[390:6607] jxcore: disconnect: success
,2015-11-20T12:47:41.283Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA==
,---- round done--------
device[3]: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:47:41.286Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:47:41.286Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:47:41.578 ThaliTest[390:60b] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:41.580 ThaliTest[390:60b] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:47:42.288 ThaliTest[390:6607] jxcore: disconnect
,2015-11-20 13:47:42.290 ThaliTest[390:6607] jxcore: disconnect: fail
2015-11-20T12:47:42.292Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:47:42.292Z SendDataConnector.js: Connect (retry count 0) to peer Apple-IpadAir2-1_PT545.qwwthQ== with availability status: true
2015-11-20T12:47:42.293Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:47:42.293Z SendDataConnector.js: do connect now
,2015-11-20 13:47:42.293 ThaliTest[390:6607] jxcore: connect Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:47:42.294 ThaliTest[390:6607] client session: connect
,2015-11-20 13:47:42.295 ThaliTest[390:6607] client session: stateChange:0->1 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:47:42.704 ThaliTest[390:60b] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:47:44.971 ThaliTest[390:b30f] client session: connected
,2015-11-20 13:47:44.973 ThaliTest[390:b30f] client session: stateChange:1->2 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:47:44.979 ThaliTest[390:b30f] client session: fireConnectCallback: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:47:44.981 ThaliTest[390:b30f] jxcore: connect: success
,2015-11-20T12:47:44.982Z SendDataConnector.js: CLIENT connected to 53292, error: null
2015-11-20T12:47:44.982Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:47:44.984 ThaliTest[390:60b] client: relay established
,2015-11-20 13:47:44.984 ThaliTest[390:60b] client: new accepted socket: 0x1a290140
,2015-11-20T12:47:44.995Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:47:50.159 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:47:51.255 ThaliTest[390:b30f] server session: not connected Apple-IpadAir2-1_PT545
,2015-11-20 13:47:51.601 ThaliTest[390:b30f] server session: not connected Apple-Iphone6-1_PT8859
,2015-11-20 13:47:53.469 ThaliTest[390:60b] multipeer session: reset timer
2015-11-20 13:47:53.470 ThaliTest[390:60b] multipeer session: stop timer
2015-11-20 13:47:53.470 ThaliTest[390:60b] multipeer session: start timer: 0x1a648c70
2015-11-20 13:47:53.,471 ThaliTest[390:60b] server: disconnecting to refresh session (Apple-IpadAir2-1_PT545)
2015-11-20 13:47:53.471 ThaliTest[390:60b] server session: disconnect
2015-11-20 13:47:53.472 ThaliTest[390:60b] server session: stateChange:2->0 Apple-IpadAir2-1_PT545
,2015-11-20 13:47:53.477 ThaliTest[390:60b] server session: connect
2015-11-20 13:47:53.477 ThaliTest[390:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT545
,2015-11-20 13:47:53.482 ThaliTest[390:60b] server: accepting invitation Apple-IpadAir2-1_PT545
,2015-11-20 13:47:53.766 ThaliTest[390:60b] multipeer session: reset timer
2015-11-20 13:47:53.767 ThaliTest[390:60b] multipeer session: stop timer
,2015-11-20 13:47:53.768 ThaliTest[390:60b] multipeer session: start timer: 0x1a648c70
2015-11-20 13:47:53.768 ThaliTest[390:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT8859)
,2015-11-20 13:47:53.769 ThaliTest[390:60b] server session: disconnect
2015-11-20 13:47:53.769 ThaliTest[390:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT8859
,2015-11-20 13:47:53.772 ThaliTest[390:60b] server session: connect
,2015-11-20 13:47:53.773 ThaliTest[390:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8859
,2015-11-20 13:47:53.777 ThaliTest[390:60b] server: accepting invitation Apple-Iphone6-1_PT8859
,2015-11-20T12:47:55.436Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:47:55.706Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20T12:47:55.706Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20 13:47:56.054 ThaliTest[390:5e1f] server session: connected
2015-11-20 13:47:56.055 ThaliTest[390:5e1f] server session: stateChange:1->2 Apple-Iphone6-1_PT8859
,2015-11-20T12:47:56.066Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:47:56.067Z SendDataConnector.js: CLIENT is data received : 220000
,2015-11-20T12:47:56.124Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:47:56.248 ThaliTest[390:851b] server session: connected
,2015-11-20 13:47:56.250 ThaliTest[390:851b] server session: stateChange:1->2 Apple-IpadAir2-1_PT545
,2015-11-20T12:47:56.292Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:47:56.445 ThaliTest[390:60b] server relay: connected (to port: 53278)
2015-11-20 13:47:56.446 ThaliTest[390:60b] server relay: connected (to port: 53278)
2015-11-20T12:47:56.451Z SendDataConnector.js: resetDataTimeout called with peer Apple,-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:47:56.451Z SendDataConnector.js: CLIENT is data received : 460000
,2015-11-20T12:47:56.466Z SendDataTCPServer.js: TCP/IP server has received 10002 bytes of data
,2015-11-20T12:47:56.467Z SendDataTCPServer.js: TCP/IP server has received 10002 bytes of data
,2015-11-20T12:47:58.820Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:47:58.821Z SendDataConnector.js: CLIENT is data received : 1970000
,2015-11-20 13:47:58.971 ThaliTest[390:b30f] server session: not connected Apple-Iphone6-1_PT8859
,2015-11-20 13:47:58.983 ThaliTest[390:b30f] server session: not connected Apple-IpadAir2-1_PT545
,2015-11-20T12:47:59.965Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:47:59.966Z SendDataConnector.js: CLIENT is data received : 2740000
,2015-11-20T12:48:00.743Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:48:00.744Z SendDataConnector.js: CLIENT is data received : 3480000
,2015-11-20T12:48:03.010Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:48:03.010Z SendDataConnector.js: CLIENT is data received : 4530000
,2015-11-20T12:48:04.428Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:48:04.429Z SendDataConnector.js: CLIENT is data received : 5350000
,2015-11-20T12:48:05.280Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:48:05.280Z SendDataConnector.js: CLIENT is data received : 6260000
,2015-11-20T12:48:06.629Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:48:06.629Z SendDataConnector.js: CLIENT is data received : 6890000
,2015-11-20T12:48:16.631Z SendDataConnector.js: Receiving data timeout now
2015-11-20T12:48:16.631Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-20T12:48:16.631Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20T12:48:16.632Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T12:48:17.639Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:48:17.639Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:18.644 ThaliTest[390:6607] jxcore: disconnect
2015-11-20 13:48:18.645 ThaliTest[390:6607] client session: disconnectFromPeer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:18.647 ThaliTest[390:6607] client session: disconnect
,2015-11-20 13:48:18.648 ThaliTest[390:6607] client session: stateChange:2->0 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:24.270 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:48:24.271 ThaliTest[390:6607] jxcore: disconnect: success
2015-11-20T12:48:24.275Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:48:24.275Z SendDataConnector.js: Connect (retry co,unt 1) to peer Apple-IpadAir2-1_PT545.qwwthQ== with availability status: true
2015-11-20T12:48:24.276Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:48:24.276Z SendDataConnector.js: do connect now
2015-11,-20 13:48:24.276 ThaliTest[390:6607] jxcore: connect Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:24.277 ThaliTest[390:6607] client session: connect
,2015-11-20 13:48:24.281 ThaliTest[390:6607] client session: stateChange:0->1 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:24.288 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:24.612 ThaliTest[390:60b] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:48:24.622 ThaliTest[390:60b] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:48:28.472 ThaliTest[390:623b] client session: connected
,2015-11-20 13:48:28.474 ThaliTest[390:623b] client session: stateChange:1->2 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:28.845 ThaliTest[390:851b] client session: fireConnectCallback: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:28.846 ThaliTest[390:851b] jxcore: connect: success
,2015-11-20T12:48:28.846Z SendDataConnector.js: CLIENT connected to 53300, error: null
2015-11-20T12:48:28.847Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:48:28.849 ThaliTest[390:60b] client: relay established
,2015-11-20 13:48:28.850 ThaliTest[390:60b] client: new accepted socket: 0x1a347630
,2015-11-20T12:48:28.860Z SendDataConnector.js: CLIENT now sending 3110000 bytes of data
,2015-11-20T12:48:32.098Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:48:42.099Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:48:42.100Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-20T12:48:42.101Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20T12:48:42.102Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 13:48:42.101 ThaliTest[390:60b] client: socket closed
,2015-11-20 13:48:42.103 ThaliTest[390:60b] client relay: socket disconnected
2015-11-20 13:48:42.104 ThaliTest[390:60b] client relay: 0x1a347630 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=,0x14df7b60 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-20 13:48:42.105 ThaliTest[390:60b] client session: socket closed: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:42.105 ThaliTest[390:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:42.106 ThaliTest[390:60b], client session: disconnect
,2015-11-20 13:48:42.106 ThaliTest[390:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:42.108 ThaliTest[390:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:48:43.105Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:48:43.106Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:43.529 ThaliTest[390:60b] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:48:43.530 ThaliTest[390:60b] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:48:44.107 ThaliTest[390:6607] jxcore: disconnect
2015-11-20 13:48:44.108 ThaliTest[390:6607] jxcore: disconnect: fail
,2015-11-20T12:48:44.110Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:48:44.110Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT545.qwwthQ== with availability status: ,true
2015-11-20T12:48:44.111Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:48:44.111Z SendDataConnector.js: do connect now
,2015-11-20 13:48:44.111 ThaliTest[390:6607] jxcore: connect Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:44.112 ThaliTest[390:6607] client session: connect
,2015-11-20 13:48:44.113 ThaliTest[390:6607] client session: stateChange:0->1 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:44.525 ThaliTest[390:60b] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:48:47.147 ThaliTest[390:623b] client session: connected
,2015-11-20 13:48:47.148 ThaliTest[390:623b] client session: stateChange:1->2 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:47.155 ThaliTest[390:623b] client session: fireConnectCallback: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:47.156 ThaliTest[390:623b] jxcore: connect: success
,2015-11-20T12:48:47.157Z SendDataConnector.js: CLIENT connected to 53303, error: null
,2015-11-20T12:48:47.157Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:48:47.158 ThaliTest[390:60b] client: relay established
2015-11-20 13:48:47.159 ThaliTest[390:60b] client: new accepted socket: 0x1a303e50
,2015-11-20T12:48:47.170Z SendDataConnector.js: CLIENT now sending 3110000 bytes of data
,2015-11-20 13:48:47.723 ThaliTest[390:60b] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:48:47.723 ThaliTest[390:60b] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:48:50.411Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:48:54.041 ThaliTest[390:60b] multipeer session: restart
2015-11-20 13:48:54.042 ThaliTest[390:60b] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:48:58.145 ThaliTest[390:60b] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:48:58.146 ThaliTest[390:60b] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:48:58.148 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:00.416Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:49:00.417Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:49:00.418Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20T12:49:00.419Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 13:49:00.419 ThaliTest[390:60b] client: socket closed
,2015-11-20 13:49:00.420 ThaliTest[390:60b] client relay: socket disconnected
,2015-11-20 13:49:00.421 ThaliTest[390:60b] client relay: 0x1a303e50 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x14d15d00 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-20 13:49:00.422 ThaliTest[390:60b] client session: socket closed: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:00.422 ThaliTest[390:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:00.423 ThaliTest[390:60b] client session: disconnect
,2015-11-20 13:49:00.423 ThaliTest[390:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:00.426 ThaliTest[390:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:01.424Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:01.425Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:02.431 ThaliTest[390:6607] jxcore: disconnect
,2015-11-20 13:49:02.432 ThaliTest[390:6607] jxcore: disconnect: fail
2015-11-20T12:49:02.434Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:02.434Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT545.qwwthQ== with availability status: true
2015-11-20T12:49:02.435Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:02.435Z SendDataConnector.js: do connect now
,2015-11-20 13:49:02.435 ThaliTest[390:6607] jxcore: connect Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:02.436 ThaliTest[390:6607] client session: connect
,2015-11-20 13:49:02.437 ThaliTest[390:6607] client session: stateChange:0->1 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:05.501 ThaliTest[390:af17] client session: connected
,2015-11-20 13:49:05.503 ThaliTest[390:af17] client session: stateChange:1->2 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:05.527 ThaliTest[390:623b] client session: fireConnectCallback: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:05.528 ThaliTest[390:623b] jxcore: connect: success
,2015-11-20T12:49:05.529Z SendDataConnector.js: CLIENT connected to 53307, error: null
,2015-11-20T12:49:05.529Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:49:05.530 ThaliTest[390:60b] client: relay established
,2015-11-20 13:49:05.531 ThaliTest[390:60b] client: new accepted socket: 0x1a56fae0
,2015-11-20T12:49:05.542Z SendDataConnector.js: CLIENT now sending 3110000 bytes of data
,2015-11-20T12:49:08.797Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:18.798Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:49:18.798Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-20T12:49:18.799Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20T12:49:18.800Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 13:49:18.800 ThaliTest[390:60b] client: socket closed
,2015-11-20 13:49:18.801 ThaliTest[390:60b] client relay: socket disconnected
2015-11-20 13:49:18.802 ThaliTest[390:60b] client relay: 0x1a56fae0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=,0x14dd05f0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 13:49:18.803 ThaliTest[390:60b] client session: socket closed: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:18.803 ThaliTest[390:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:18.804 ThaliTest[390:60b] client session: disconnect
2015-11-20 13:49:18.804 ThaliTest[390:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:18.807 ThaliTest[390:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:19.803Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:19.804Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:20.810 ThaliTest[390:6607] jxcore: disconnect
,2015-11-20 13:49:20.812 ThaliTest[390:6607] jxcore: disconnect: fail
2015-11-20T12:49:20.813Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:49:20.814Z SendDataConnector.js: Connect (retry count, 4) to peer Apple-IpadAir2-1_PT545.qwwthQ== with availability status: true
,2015-11-20T12:49:20.814Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:49:20.814Z SendDataConnector.js: do connect now
,2015-11-20 13:49:20.814 ThaliTest[390:6607] jxcore: connect Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:20.815 ThaliTest[390:6607] client session: connect
,2015-11-20 13:49:20.816 ThaliTest[390:6607] client session: stateChange:0->1 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:23.769 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:49:23.779 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:23.848 ThaliTest[390:60b] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:23.862 ThaliTest[390:60b] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:49:24.898 ThaliTest[390:b30f] client session: connected
,2015-11-20 13:49:24.899 ThaliTest[390:b30f] client session: stateChange:1->2 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:25.020 ThaliTest[390:623b] client session: fireConnectCallback: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:25.021 ThaliTest[390:623b] jxcore: connect: success
,2015-11-20T12:49:25.022Z SendDataConnector.js: CLIENT connected to 53312, error: null
2015-11-20T12:49:25.022Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:49:25.023 ThaliTest[390:60b] client: relay established
,2015-11-20 13:49:25.025 ThaliTest[390:60b] client: new accepted socket: 0x1a6c4610
,2015-11-20T12:49:25.036Z SendDataConnector.js: CLIENT now sending 3110000 bytes of data
,2015-11-20T12:49:28.278Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:38.284Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:49:38.285Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:49:38.286Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:49:38.286Z SendDataConnector.js: Stop data retrieving timer
,2015-11-20 13:49:38.288 ThaliTest[390:6607] jxcore: disconnect
2015-11-20 13:49:38.289 ThaliTest[390:6607] client session: disconnectFromPeer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:38.289 ThaliTest[390:6607] client session: disconnect
2015-11-20 13:49:38.290 ThaliTest[390:6607] client session: stateChange:2->0 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:39.763 ThaliTest[390:6607] jxcore: disconnect: success
2015-11-20T12:49:39.765Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT545.qwwthQ==
---- round done--------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT6611","time":200936,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT7169./ZcTuw==","time":41504,"result":"OK","connections":1},{"name":"Apple-Iphone6-1_PT8859.CKR/JA==","time":40580,"result":"OK","connections":4},{"name":"Apple-IpadAir2-1_PT545.qwwthQ==","time":118481,"result":"DATA-TIMEOUT","connections":5}]}
,sendList : 100% : 41504 ms, 99% : 41504 ms, 95 : 41504 ms, 90% : 41504 ms.
,Result count 2, range 40580 ms to  41504 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-IpadAir2-1_PT545.qwwthQ==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-11-20T12:49:39.787Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:49:39.790Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20 13:49:53.769 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:49:53.781 ThaliTest[390:60b] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:49:53.782 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:53.783 ThaliTest[390:60b] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:56.390 ThaliTest[390:60b] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:56.392 ThaliTest[390:60b] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:50:01.623 ThaliTest[390:60b] multipeer session: reset timer
2015-11-20 13:50:01.625 ThaliTest[390:60b] multipeer session: stop timer
2015-11-20 13:50:01.626 ThaliTest[390:60b] multipeer session: start timer: 0x1a648c70
,2015-11-20 13:50:01.626 ThaliTest[390:60b] server session: connect
,2015-11-20 13:50:01.627 ThaliTest[390:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:01.630 ThaliTest[390:60b] server: accepting invitation Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:03.866 ThaliTest[390:7d0b] server session: connected
,2015-11-20 13:50:03.867 ThaliTest[390:7d0b] server session: stateChange:1->2 Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:04.007 ThaliTest[390:60b] server relay: socket disconnected
2015-11-20 13:50:04.007 ThaliTest[390:60b] server relay: 0x1a6b96c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1a4e2800 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 13:50:18.544 ThaliTest[390:6247] server session: not connected Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:21.056 ThaliTest[390:60b] multipeer session: reset timer
,2015-11-20 13:50:21.058 ThaliTest[390:60b] multipeer session: stop timer
,2015-11-20 13:50:21.059 ThaliTest[390:60b] multipeer session: start timer: 0x1a648c70
,2015-11-20 13:50:21.060 ThaliTest[390:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7169)
,2015-11-20 13:50:21.060 ThaliTest[390:60b] server session: disconnect
,2015-11-20 13:50:21.061 ThaliTest[390:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT7169
2015-11-20 13:50:21.062 ThaliTest[390:60b] server session: connect
,2015-11-20 13:50:21.062 ThaliTest[390:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:21.066 ThaliTest[390:60b] server: accepting invitation Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:23.292 ThaliTest[390:7337] server session: connected
,2015-11-20 13:50:23.293 ThaliTest[390:7337] server session: stateChange:1->2 Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:23.309 ThaliTest[390:60b] server relay: socket disconnected
,2015-11-20 13:50:23.310 ThaliTest[390:60b] server relay: 0x1a51ee80 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1a234de0 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 13:50:25.748 ThaliTest[390:60b] client: lost peer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:50:25.749 ThaliTest[390:60b] client session: onPeerLost: Apple-Iphone5s-1_PT7169./ZcTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:50:26.742 ThaliTest[390:60b] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:50:37.928 ThaliTest[390:881f] server session: not connected Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:39.977 ThaliTest[390:60b] multipeer session: reset timer
2015-11-20 13:50:39.978 ThaliTest[390:60b] multipeer session: stop timer
,2015-11-20 13:50:39.979 ThaliTest[390:60b] multipeer session: start timer: 0x1a648c70
,2015-11-20 13:50:39.980 ThaliTest[390:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7169)
,2015-11-20 13:50:39.980 ThaliTest[390:60b] server session: disconnect
2015-11-20 13:50:39.981 ThaliTest[390:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:39.982 ThaliTest[390:60b] server session: connect
,2015-11-20 13:50:39.983 ThaliTest[390:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:39.987 ThaliTest[390:60b] server: accepting invitation Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:42.105 ThaliTest[390:7f2f] server session: connected
,2015-11-20 13:50:42.107 ThaliTest[390:7f2f] server session: stateChange:1->2 Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:42.116 ThaliTest[390:60b] server relay: socket disconnected
,2015-11-20 13:50:42.117 ThaliTest[390:60b] server relay: 0x1a4b00d0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1a4caef0 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 13:50:57.212 ThaliTest[390:7337] server session: not connected Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:59.271 ThaliTest[390:60b] multipeer session: reset timer
2015-11-20 13:50:59.271 ThaliTest[390:60b] multipeer session: stop timer
,2015-11-20 13:50:59.272 ThaliTest[390:60b] multipeer session: start timer: 0x1a648c70
,2015-11-20 13:50:59.273 ThaliTest[390:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7169)
,2015-11-20 13:50:59.273 ThaliTest[390:60b] server session: disconnect
,2015-11-20 13:50:59.274 ThaliTest[390:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:59.275 ThaliTest[390:60b] server session: connect
,2015-11-20 13:50:59.276 ThaliTest[390:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7169
,2015-11-20 13:50:59.280 ThaliTest[390:60b] server: accepting invitation Apple-Iphone5s-1_PT7169
,2015-11-20 13:51:01.488 ThaliTest[390:bb37] server session: connected
,2015-11-20 13:51:01.490 ThaliTest[390:bb37] server session: stateChange:1->2 Apple-Iphone5s-1_PT7169
,2015-11-20 13:51:01.499 ThaliTest[390:60b] server relay: socket disconnected
,2015-11-20 13:51:01.500 ThaliTest[390:60b] server relay: 0x14e479d0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x14e5f8e0 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 13:51:16.155 ThaliTest[390:b24b] server session: not connected Apple-Iphone5s-1_PT7169
,2015-11-20 13:51:18.325 ThaliTest[390:60b] multipeer session: reset timer
,2015-11-20 13:51:18.326 ThaliTest[390:60b] multipeer session: stop timer
2015-11-20 13:51:18.327 ThaliTest[390:60b] multipeer session: start timer: 0x1a648c70
,2015-11-20 13:51:18.328 ThaliTest[390:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7169)
,2015-11-20 13:51:18.329 ThaliTest[390:60b] server session: disconnect
,2015-11-20 13:51:18.329 ThaliTest[390:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT7169
,2015-11-20 13:51:18.330 ThaliTest[390:60b] server session: connect
,2015-11-20 13:51:18.332 ThaliTest[390:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7169
,2015-11-20 13:51:18.335 ThaliTest[390:60b] server: accepting invitation Apple-Iphone5s-1_PT7169
,2015-11-20 13:51:20.813 ThaliTest[390:b24b] server session: connected
,2015-11-20 13:51:20.815 ThaliTest[390:b24b] server session: stateChange:1->2 Apple-Iphone5s-1_PT7169
,2015-11-20 13:51:20.823 ThaliTest[390:60b] server relay: socket disconnected
,2015-11-20 13:51:20.823 ThaliTest[390:60b] server relay: 0x1a4173b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo=0x1a5844e0 {NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 13:51:35.481 ThaliTest[390:7163] server session: not connected Apple-Iphone5s-1_PT7169
,2015-11-20 13:51:38.605 ThaliTest[390:60b] client: lost peer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:51:38.607 ThaliTest[390:60b] client session: onPeerLost: Apple-Iphone5s-1_PT7169./ZcTuw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:51:45.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:51:45.742 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:52:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:52:45.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:52:45.742 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:53:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:53:45.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:53:45.741 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:54:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:54:15.741 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:54:45.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:54:45.742 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:55:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:55:45.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:55:45.742 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:56:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:56:45.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:56:45.743 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:57:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:57:45.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:57:45.741 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:58:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:58:15.742 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:58:45.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:58:45.743 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:59:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:59:45.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 13:59:45.741 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 14:00:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 14:00:45.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 14:00:45.741 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 14:01:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 14:01:45.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 14:01:45.742 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 14:02:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 14:02:15.742 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 14:02:45.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 14:03:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 14:03:15.743 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 14:03:45.731 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 14:03:45.741 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 14:04:15.732 ThaliTest[390:60b] multipeer session: restart
,2015-11-20 14:04:15.741 ThaliTest[390:60b] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==

```
