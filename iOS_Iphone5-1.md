#### Test 513350289b9c5d6_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350289b9c5d6/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/69A59EF0-86E3-4398-AE37-39674A46CC21/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/69A59EF0-86E3-4398-AE37-39674A46CC21/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350289b9c5d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350289b9c5d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/892EC244-49AA-4FBE-AAC9-C92EE7F42653/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52797"
,(lldb)     command script import "/tmp/69A59EF0-86E3-4398-AE37-39674A46CC21/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 12:31:35.573 ThaliTest[590:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 12:31:35.576 ThaliTest[590:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-23 12:31:35.582 ThaliTest[590:60b] Unlimited access to network resources
,2015-11-23 12:31:35.588 ThaliTest[590:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 12:31:46.245 ThaliTest[590:60b] Resetting plugins due to page load.
,2015-11-23 12:31:47.120 ThaliTest[590:60b] Finished load of: file:///var/mobile/Applications/892EC244-49AA-4FBE-AAC9-C92EE7F42653/ThaliTest.app/www/index.html
,2015-11-23 12:31:47.308 ThaliTest[590:60b] JXcore Cordova plugin initializing
,2015-11-23 12:31:47.310 ThaliTest[590:6807] JXcore instance initializing
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
,toggleBluetooth - 
Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
toggleWiFi
,my name is : Apple-Iphone5-1_PT142
,attempting to connect to test coordinator
check test folder
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
,-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
,-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
,-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
,-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
,-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
,-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
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
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4009:44ff:fe71:c4e1
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 58070
,2015-11-23 12:36:43.407 ThaliTest[590:6807] jxcore: startBroadcasting
,2015-11-23 12:36:43.420 ThaliTest[590:6807] server: starting Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23 12:36:43.422 ThaliTest[590:6807] multipeer session: start timer: 0x1aed4420
2015-11-23 12:36:43.423 ThaliTest[590:6807] THEMultipeerSession initialized, peer Apple-Iphone5-1_PT142
2015-11-23 12:36:43.423 ThaliTest[590:6807] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-11-23T11:36:43.427Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-23 12:36:43.607 ThaliTest[590:60b] client: found peer: Apple-Iphone6-1_PT7664.8o3jhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7664.8o3jhw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7664.8o3jhw==
2015-11-23T11:36:43.611Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7664.8o3jhw==
2015-11-23T11:36:43.612Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23T11:36:43.612Z SendDataConnector.js: do connect now
,2015-11-23 12:36:43.612 ThaliTest[590:6807] jxcore: connect Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:43.613 ThaliTest[590:6807] client session: connect
,2015-11-23 12:36:43.614 ThaliTest[590:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:43.957 ThaliTest[590:60b] client: found peer: Apple-Iphone5s-1_PT8005.g0Za/g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8005.g0Za/g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 12:36:44.359 ThaliTest[590:60b] client: found peer: Apple-IpadAir2-1_PT6529.Z02MaA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6529.Z02MaA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 12:36:46.105 ThaliTest[590:8303] client session: connected
,2015-11-23 12:36:46.107 ThaliTest[590:8303] client session: stateChange:1->2 Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:46.117 ThaliTest[590:8303] client session: fireConnectCallback: Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:46.118 ThaliTest[590:8303] jxcore: connect: success
,2015-11-23T11:36:46.120Z SendDataConnector.js: CLIENT connected to 58073, error: null
,2015-11-23T11:36:46.120Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 12:36:46.121 ThaliTest[590:60b] client: relay established
,2015-11-23 12:36:46.122 ThaliTest[590:60b] client: new accepted socket: 0x1ad1f200
,2015-11-23T11:36:46.133Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T11:36:46.338Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-23T11:36:46.474Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-23T11:36:46.486Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-23T11:36:46.487Z SendDataConnector.js: got all data for this round
,2015-11-23T11:36:46.489Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:36:46.490Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 12:36:46.491 ThaliTest[590:6807] jxcore: disconnect
,2015-11-23 12:36:46.491 ThaliTest[590:6807] client session: disconnectFromPeer: Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:46.492 ThaliTest[590:6807] client session: disconnect
,2015-11-23 12:36:46.493 ThaliTest[590:6807] client session: stateChange:2->0 Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:46.497 ThaliTest[590:6807] jxcore: disconnect: success
2015-11-23T11:36:46.498Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7664.8o3jhw==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23T11:36:46.501Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8005.g0Za/g==
2015-11-23T11:36:46.501Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23T11:36:46.502Z SendDataConnector.js: do connect now
,2015-11-23 12:36:46.502 ThaliTest[590:6807] jxcore: connect Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23 12:36:46.504 ThaliTest[590:6807] client session: connect
2015-11-23 12:36:46.505 ThaliTest[590:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23 12:36:48.868 ThaliTest[590:740b] client session: connected
2015-11-23 12:36:48.869 ThaliTest[590:740b] client session: stateChange:1->2 Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23 12:36:48.871 ThaliTest[590:740b] client session: fireConnectCallback: Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23 12:36:48.872 ThaliTest[590:740b] jxcore: connect: success
,2015-11-23T11:36:48.873Z SendDataConnector.js: CLIENT connected to 58077, error: null
,2015-11-23T11:36:48.873Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 12:36:48.875 ThaliTest[590:60b] client: relay established
,2015-11-23 12:36:48.875 ThaliTest[590:60b] client: new accepted socket: 0x1ad1c290
,2015-11-23T11:36:48.886Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T11:36:49.309Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-23T11:36:49.454Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-23T11:36:49.467Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-23T11:36:50.023Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-23T11:36:50.024Z SendDataConnector.js: got all data for this round
,2015-11-23T11:36:50.025Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:36:50.026Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 12:36:50.027 ThaliTest[590:6807] jxcore: disconnect
2015-11-23 12:36:50.028 ThaliTest[590:6807] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23 12:36:50.029 ThaliTest[590:6807] client session: disconnect
2015-11-23 12:36:50.029 ThaliTest[590:6807] client session: stateChange:2->0 Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23 12:36:50.032 ThaliTest[590:6807] jxcore: disconnect: success
2015-11-23T11:36:50.033Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8005.g0Za/g==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23T11:36:50.034Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23T11:36:50.034Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6529.Z02MaA==,
2015-11-23T11:36:50.034Z SendDataConnector.js: do connect now
,2015-11-23 12:36:50.035 ThaliTest[590:6807] jxcore: connect Apple-IpadAir2-1_PT6529.Z02MaA==
,2015-11-23 12:36:50.036 ThaliTest[590:6807] client session: connect
2015-11-23 12:36:50.036 ThaliTest[590:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT6529.Z02MaA==
,2015-11-23 12:36:51.393 ThaliTest[590:60b] multipeer session: reset timer
,2015-11-23 12:36:51.394 ThaliTest[590:60b] multipeer session: stop timer
,2015-11-23 12:36:51.396 ThaliTest[590:60b] multipeer session: start timer: 0x1aed4420
,2015-11-23 12:36:51.396 ThaliTest[590:60b] server session: connect
,2015-11-23 12:36:51.397 ThaliTest[590:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT7664
,2015-11-23 12:36:51.400 ThaliTest[590:60b] server: accepting invitation Apple-Iphone6-1_PT7664
,2015-11-23 12:36:52.585 ThaliTest[590:60b] multipeer session: reset timer
,2015-11-23 12:36:52.586 ThaliTest[590:60b] multipeer session: stop timer
,2015-11-23 12:36:52.587 ThaliTest[590:60b] multipeer session: start timer: 0x1aed4420
,2015-11-23 12:36:52.588 ThaliTest[590:60b] server session: connect
,2015-11-23 12:36:52.589 ThaliTest[590:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:52.592 ThaliTest[590:60b] server: accepting invitation Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:52.999 ThaliTest[590:8303] client session: connected
,2015-11-23 12:36:53.000 ThaliTest[590:8303] client session: stateChange:1->2 Apple-IpadAir2-1_PT6529.Z02MaA==
,2015-11-23 12:36:53.019 ThaliTest[590:8303] client session: fireConnectCallback: Apple-IpadAir2-1_PT6529.Z02MaA==
,2015-11-23 12:36:53.020 ThaliTest[590:8303] jxcore: connect: success
,2015-11-23T11:36:53.021Z SendDataConnector.js: CLIENT connected to 58080, error: null
,2015-11-23T11:36:53.022Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 12:36:53.023 ThaliTest[590:60b] client: relay established
2015-11-23 12:36:53.023 ThaliTest[590:60b] client: new accepted socket: 0x1aef57a0
,2015-11-23T11:36:53.034Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23 12:36:54.109 ThaliTest[590:141b] server session: connected
,2015-11-23 12:36:54.111 ThaliTest[590:141b] server session: stateChange:1->2 Apple-Iphone6-1_PT7664
,2015-11-23T11:36:54.120Z SendDataTCPServer.js: TCP/IP server connected
2015-11-23 12:36:54.120 ThaliTest[590:60b] server relay: connected (to port: 58070)
,2015-11-23T11:36:54.234Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-11-23T11:36:54.248Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-11-23T11:36:54.263Z SendDataTCPServer.js: TCP/IP server has received 58988 bytes of data
,2015-11-23T11:36:54.276Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23T11:36:54.554Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-23 12:36:54.560 ThaliTest[590:141b] server session: not connected Apple-Iphone6-1_PT7664
,2015-11-23 12:36:55.085 ThaliTest[590:60b] multipeer session: reset timer
2015-11-23 12:36:55.086 ThaliTest[590:60b] multipeer session: stop timer
2015-11-23 12:36:55.086 ThaliTest[590:60b] multipeer session: start timer: 0x1aed4420
2015-11-23 12:36:55.,087 ThaliTest[590:60b] server session: connect
2015-11-23 12:36:55.087 ThaliTest[590:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT6529
,2015-11-23 12:36:55.093 ThaliTest[590:60b] server: accepting invitation Apple-IpadAir2-1_PT6529
,2015-11-23T11:36:55.100Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-23T11:36:55.101Z SendDataConnector.js: got all data for this round
2015-11-23T11:36:55.103Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:36:55.103Z SendDataCo,nnector.js: CLIENT closeClientSocket
2015-11-23 12:36:55.104 ThaliTest[590:6807] jxcore: disconnect
2015-11-23 12:36:55.104 ThaliTest[590:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23 12:36:55.105 ThaliTest[590:6807] client session: disconnect
2015-11-23 12:36:55.106 ThaliTest[590:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT6529.Z02MaA==
,2015-11-23 12:36:55.113 ThaliTest[590:6807] jxcore: disconnect: success
2015-11-23T11:36:55.115Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6529.Z02MaA==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT142","time":11718,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7664.8o3jhw==","time":2877,"result":"OK","connections":1},{"name":"Apple-Iphone5s-1_PT8005.g0Za/g==","time":3523,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT6529.Z02MaA==","time":5067,"result":"OK","connections":1}]}
,sendList : 100% : 5067 ms, 99% : 5067 ms, 95 : 5067 ms, 90% : 5067 ms.
Result count 3, range 2877 ms to  5067 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-23T11:36:55.123Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:36:55.123Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 12:36:55.776 ThaliTest[590:2907] server session: connected
2015-11-23 12:36:55.777 ThaliTest[590:2907] server session: stateChange:1->2 Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:55.781 ThaliTest[590:60b] server relay: connected (to port: 58070)
,2015-11-23T11:36:55.783Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T11:36:56.117Z SendDataTCPServer.js: TCP/IP server has received 28328 bytes of data
,2015-11-23T11:36:56.132Z SendDataTCPServer.js: TCP/IP server has received 58988 bytes of data
,2015-11-23T11:36:56.145Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 12:36:56.213 ThaliTest[590:8303] server session: not connected Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:58.754 ThaliTest[590:8303] server session: connected
,2015-11-23 12:36:58.755 ThaliTest[590:8303] server session: stateChange:1->2 Apple-IpadAir2-1_PT6529
,2015-11-23 12:36:58.760 ThaliTest[590:60b] server relay: connected (to port: 58070)
,2015-11-23T11:36:58.769Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T11:36:59.268Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-11-23T11:36:59.280Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-23T11:36:59.295Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-11-23T11:36:59.309Z SendDataTCPServer.js: TCP/IP server has received 85126 bytes of data
,2015-11-23T11:36:59.324Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 12:37:00.759 ThaliTest[590:141b] server session: not connected Apple-IpadAir2-1_PT6529
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-23 12:37:01.094 ThaliTest[590:6807] jxcore: stopBroadcasting
,2015-11-23 12:37:01.095 ThaliTest[590:6807] THEMultipeerSession stopping peer
,2015-11-23 12:37:01.096 ThaliTest[590:6807] multipeer session: stop timer
,2015-11-23 12:37:01.096 ThaliTest[590:6807] server session: disconnect
2015-11-23 12:37:01.097 ThaliTest[590:6807] server session: stateChange:2->0 Apple-Iphone5s-1_PT8005
,2015-11-23 12:37:01.101 ThaliTest[590:6807] server session: disconnect
,2015-11-23 12:37:01.103 ThaliTest[590:6807] server session: stateChange:2->0 Apple-IpadAir2-1_PT6529
,2015-11-23 12:37:01.107 ThaliTest[590:6807] server session: disconnect
,2015-11-23 12:37:01.108 ThaliTest[590:6807] server session: stateChange:2->0 Apple-Iphone6-1_PT7664
,2015-11-23 12:37:01.113 ThaliTest[590:6807] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-23T11:37:01.131Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T11:37:01.135Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T11:37:01.136Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T11:37:01.136Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":2877,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8005.g0Za/g==\",\"time\":3523,\",result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6529.Z02MaA==\",\"time\":5067,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT8005.g0Z,a/g==\",\"time\":2857,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":2877,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":3192,\"result\":\"OK\",\"connections\":1},{\",name\":\"Apple-Iphone5s-1_PT8005.g0Za/g==\",\"time\":3523,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":3655,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":3704,\"resu,lt\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":3780,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6529.Z02MaA==\",\"time\":4200,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_P,T6529.Z02MaA==\",\"time\":4725,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6529.Z02MaA==\",\"time\":5067,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8005.g0Za/g==\",\"time\":5174,\"result\":\"OK\",\"connectio,ns\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":8751,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
Coordi
```
