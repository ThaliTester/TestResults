#### Test 51335028e04ad51_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028e04ad51/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DE28C70F-3002-45F0-A947-038DAD7A5C2E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DE28C70F-3002-45F0-A947-038DAD7A5C2E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028e04ad51/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028e04ad51/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FAA6ABD3-F2E5-40FB-9C97-27E274BDC8B5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52489"
,(lldb)     command script import "/tmp/DE28C70F-3002-45F0-A947-038DAD7A5C2E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 07:58:37.530 ThaliTest[1311:1034546] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F01EEF04-B06A-46BB-B2FA-5F09595ADADF/Library/Cookies/Cookies.binarycookies
,2015-11-23 07:58:37.920 ThaliTest[1311:1034546] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 07:58:37.921 ThaliTest[1311:1034546] Multi-tasking -> Device: YES, App: YES
,2015-11-23 07:58:37.928 ThaliTest[1311:1034546] Unlimited access to network resources
,2015-11-23 07:58:37.935 ThaliTest[1311:1034546] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 07:58:41.529 ThaliTest[1311:1034546] Resetting plugins due to page load.
,2015-11-23 07:58:41.893 ThaliTest[1311:1034546] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/FAA6ABD3-F2E5-40FB-9C97-27E274BDC8B5/ThaliTest.app/www/index.html
,2015-11-23 07:58:42.014 ThaliTest[1311:1034546] JXcore Cordova plugin initializing
2015-11-23 07:58:42.016 ThaliTest[1311:1034688] JXcore instance initializing
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
,toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
toggleWiFi
,my name is : Apple-Iphone6-1_PT606
,attempting to connect to test coordinator
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found inter,faceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 56544
,2015-11-23 08:04:41.113 ThaliTest[1311:1034688] jxcore: startBroadcasting
,2015-11-23 08:04:41.125 ThaliTest[1311:1034688] server: starting Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:04:41.126 ThaliTest[1311:1034688] multipeer session: start timer: 0x19e4c050
2015-11-23 08:04:41.127 ThaliTest[1311:1034688] THEMultipeerSession, initialized peer Apple-Iphone6-1_PT606
2015-11-23 08:04:41.127 ThaliTest[1311:1034688] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-23T07:04:41.130Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-23 08:04:41.482 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8536.VjK3dQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23T07:04:41.492Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23T07:04:41.493Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8536.VjK3dQ==
20,15-11-23T07:04:41.493Z SendDataConnector.js: do connect now
2015-11-23 08:04:41.494 ThaliTest[1311:1034688] jxcore: connect Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:04:41.496 ThaliTest[1311:1034688] client session: connect
,2015-11-23 08:04:41.497 ThaliTest[1311:1034688] client session: stateChange:0->1 Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:04:41.499 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2253.QxwsNA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:04:42.194 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8264./5qd6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:04:42.741 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-11-23 08:04:43.436 ThaliTest[1311:1034546] multipeer session: reset timer
2015-11-23 08:04:43.436 ThaliTest[1311:1034546] multipeer session: stop timer
2015-11-23 08:04:43.437 ThaliTest[1311:1034546] multipeer session: start timer: 0x19e4c050
2015-,11-23 08:04:43.438 ThaliTest[1311:1034546] server session: connect
2015-11-23 08:04:43.438 ThaliTest[1311:1034546] server session: stateChange:0->1 Apple-IpadAir2-1_PT2253
,2015-11-23 08:04:43.449 ThaliTest[1311:1034546] server: accepting invitation Apple-IpadAir2-1_PT2253
,2015-11-23 08:04:44.071 ThaliTest[1311:1035255] client session: connected
2015-11-23 08:04:44.072 ThaliTest[1311:1035255] client session: stateChange:1->2 Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:04:44.076 ThaliTest[1311:1035255] client session: fireConnectCallback: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:04:44.077 ThaliTest[1311:1035255] jxcore: connect: success
,2015-11-23T07:04:44.079Z SendDataConnector.js: CLIENT connected to 56547, error: null
,2015-11-23T07:04:44.079Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 08:04:44.083 ThaliTest[1311:1034546] client: relay established
2015-11-23 08:04:44.084 ThaliTest[1311:1034546] client: new accepted socket: 0x19e4aaa0
,2015-11-23T07:04:44.093Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T07:04:44.507Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-23T07:04:44.521Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-23T07:04:44.546Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-23T07:04:44.546Z SendDataConnector.js: got all data for this round
,2015-11-23T07:04:44.548Z SendDataConnector.js: CLIENT Stop now
2015-11-23T07:04:44.548Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 08:04:44.550 ThaliTest[1311:1034688] jxcore: disconnect
2015-11-23 08:04:44.550 ThaliTest[1311:1034688] client session: disconnectFromPeer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:04:44.551 ThaliTest[1311:1034688] client session: disconnect
2015-11-23 08:04:44.551 ThaliTest[1311:1034688] client session: stateChange:2->0 Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:04:44.554 ThaliTest[1311:1034688] jxcore: disconnect: success
2015-11-23T07:04:44.556Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8536.VjK3dQ==
,---- round done--------
device[2]: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23T07:04:44.559Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23T07:04:44.559Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23T07:04:44.559Z SendDataConnector.js: do connect now
,2015-11-23 08:04:44.559 ThaliTest[1311:1034688] jxcore: connect Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:04:44.560 ThaliTest[1311:1034688] client session: connect
2015-11-23 08:04:44.561 ThaliTest[1311:1034688] client session: stateChange:0->1 Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:04:44.589 ThaliTest[1311:1034546] multipeer session: reset timer
2015-11-23 08:04:44.590 ThaliTest[1311:1034546] multipeer session: stop timer
2015-11-23 08:04:44.590 ThaliTest[1311:1034546] multipeer session: start timer: 0x19e4c050
2015-11-23 08:04:44.590 ThaliTest[1311:1034546] server session: connect
2015-11-23 08:04:44.590 ThaliTest[1311:1034546] server session: stateChange:0->1 Apple-Iphone5-1_PT8536
,2015-11-23 08:04:44.596 ThaliTest[1311:1034546] server: accepting invitation Apple-Iphone5-1_PT8536
,2015-11-23 08:04:46.231 ThaliTest[1311:1035229] server session: connected
2015-11-23 08:04:46.231 ThaliTest[1311:1035229] server session: stateChange:1->2 Apple-IpadAir2-1_PT2253
,2015-11-23 08:04:46.242 ThaliTest[1311:1034546] server relay: connected (to port: 56544)
,2015-11-23T07:04:46.252Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T07:04:46.315Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-11-23T07:04:46.332Z SendDataTCPServer.js: TCP/IP server has received 58988 bytes of data
,2015-11-23T07:04:46.346Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-11-23T07:04:46.359Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-11-23T07:04:46.373Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 08:04:46.588 ThaliTest[1311:1035255] server session: not connected Apple-IpadAir2-1_PT2253
,2015-11-23 08:04:47.119 ThaliTest[1311:1035229] server session: connected
2015-11-23 08:04:47.120 ThaliTest[1311:1035229] server session: stateChange:1->2 Apple-Iphone5-1_PT8536
,2015-11-23 08:04:47.128 ThaliTest[1311:1034546] server relay: connected (to port: 56544)
,2015-11-23T07:04:47.138Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T07:04:47.279Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-11-23T07:04:47.292Z SendDataTCPServer.js: TCP/IP server has received 16864 bytes of data
,2015-11-23T07:04:47.307Z SendDataTCPServer.js: TCP/IP server has received 32736 bytes of data
,2015-11-23T07:04:47.323Z SendDataTCPServer.js: TCP/IP server has received 41664 bytes of data
,2015-11-23T07:04:47.337Z SendDataTCPServer.js: TCP/IP server has received 55552 bytes of data
,2015-11-23T07:04:47.353Z SendDataTCPServer.js: TCP/IP server has received 74400 bytes of data
,2015-11-23T07:04:47.370Z SendDataTCPServer.js: TCP/IP server has received 90272 bytes of data
,2015-11-23T07:04:47.383Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 08:04:47.671 ThaliTest[1311:1035225] server session: not connected Apple-Iphone5-1_PT8536
,2015-11-23 08:04:47.730 ThaliTest[1311:1035256] client session: connected
2015-11-23 08:04:47.731 ThaliTest[1311:1035256] client session: stateChange:1->2 Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:04:47.740 ThaliTest[1311:1035221] client session: fireConnectCallback: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:04:47.741 ThaliTest[1311:1035221] jxcore: connect: success
2015-11-23T07:04:47.743Z SendDataConnector.js: CLIENT connected to 56552, error: null
,2015-11-23T07:04:47.743Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 08:04:47.747 ThaliTest[1311:1034546] client: relay established
2015-11-23 08:04:47.747 ThaliTest[1311:1034546] client: new accepted socket: 0x19f6b9f0
,2015-11-23T07:04:47.759Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T07:04:47.860Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-23T07:04:47.872Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-23T07:04:47.886Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-23T07:04:47.886Z SendDataConnector.js: got all data for this round
,2015-11-23T07:04:47.886Z SendDataConnector.js: CLIENT Stop now
,2015-11-23T07:04:47.887Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 08:04:47.887 ThaliTest[1311:1034688] jxcore: disconnect
,2015-11-23 08:04:47.888 ThaliTest[1311:1034688] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:04:47.889 ThaliTest[1311:1034688] client session: disconnect
,2015-11-23 08:04:47.889 ThaliTest[1311:1034688] client session: stateChange:2->0 Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:04:47.893 ThaliTest[1311:1034688] jxcore: disconnect: success
,2015-11-23T07:04:47.895Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2253.QxwsNA==
,---- round done--------
,device[3]: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:04:47.897Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:04:47.897Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:04:47.898Z SendDataConnector.js: do connect now
,2015-11-23 08:04:47.899 ThaliTest[1311:1034688] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:04:47.900 ThaliTest[1311:1034688] client session: connect
,2015-11-23 08:04:47.901 ThaliTest[1311:1034688] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:14.589 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:05:14.611 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:14.612 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:05:14.615 ThaliTest[1311:1034546] clie,nt: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:05:14.616 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:05:20.915 ThaliTest[1311:1035264] client session: not connected Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:20.915 ThaliTest[1311:1035264] client session: onLinkFailure: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:20.917 ThaliTest[1311:1035264] client session: disconnect
2015-11-23 08:05:20.918 ThaliTest[1311:1035264] client session: stateChange:1->0 Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:20.918 ThaliTest[1311:1035264] client session: fireConnectCallback: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:20.919 ThaliTest[1311:1035264] jxcore: connect: fail: Peer disconnected
,2015-11-23T07:05:20.921Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-23T07:05:20.921Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-23T07:05:20.922Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-23T07:05:25.923Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:05:25.924Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:27.842 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:27.843 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5s-1_PT8264./5qd6Q==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT8264./5qd6Q==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:05:30.935 ThaliTest[1311:1034688] jxcore: disconnect
2015-11-23 08:05:30.936 ThaliTest[1311:1034688] jxcore: disconnect: fail
2015-11-23T07:05:30.937Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:05:30.938Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT8264./5qd6Q== with availability status: true
2015-11-23T07:05:30.938Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:05:30.939Z SendDataConnector.js: do connect now
,2015-11-23 08:05:30.940 ThaliTest[1311:1034688] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:30.941 ThaliTest[1311:1034688] client: connect: unreachable Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:30.942 ThaliTest[1311:1034688], jxcore: connect: fail: Peer unreachable
2015-11-23T07:05:30.942Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-23T07:05:30.943Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-11-23T07:05:30.943Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-23T07:05:35.950Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:05:35.950Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:40.957 ThaliTest[1311:1034688] jxcore: disconnect
2015-11-23 08:05:40.958 ThaliTest[1311:1034688] jxcore: disconnect: fail
2015-11-23T07:05:40.958Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd,6Q==
2015-11-23T07:05:40.959Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT8264./5qd6Q== with availability status: true
,2015-11-23T07:05:40.959Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:05:40.960Z SendDataConnector.js: do connect now
,2015-11-23 08:05:40.961 ThaliTest[1311:1034688] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:40.961 ThaliTest[1311:1034688] client: connect: unreachable Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:40.962 ThaliTest[1311:1034688], jxcore: connect: fail: Peer unreachable
2015-11-23T07:05:40.962Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-23T07:05:40.963Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-11-23T07:05:40.963Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-23 08:05:44.589 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:05:44.603 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:05:44.604 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:05:44.607 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23T07:05:45.966Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:05:45.967Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:50.980 ThaliTest[1311:1034688] jxcore: disconnect
2015-11-23 08:05:50.980 ThaliTest[1311:1034688] jxcore: disconnect: fail
2015-11-23T07:05:50.981Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd,6Q==
2015-11-23T07:05:50.982Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT8264./5qd6Q== with availability status: true
,2015-11-23T07:05:50.982Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:05:50.982Z SendDataConnector.js: do connect now
,2015-11-23 08:05:50.983 ThaliTest[1311:1034688] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:50.984 ThaliTest[1311:1034688] client: connect: unreachable Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:50.985 ThaliTest[1311:1034688], jxcore: connect: fail: Peer unreachable
2015-11-23T07:05:50.985Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-23T07:05:50.986Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-11-23T07:05:50.986Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-23 08:05:53.187 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:05:53.188 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:05:54.174 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-11-23T07:05:55.996Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:05:55.996Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:57.897 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:05:57.898 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:05:58.892 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-11-23 08:06:01.006 ThaliTest[1311:1034688] jxcore: disconnect
2015-11-23 08:06:01.007 ThaliTest[1311:1034688] jxcore: disconnect: fail
2015-11-23T07:06:01.008Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd,6Q==
2015-11-23T07:06:01.008Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT8264./5qd6Q== with availability status: true
,2015-11-23T07:06:01.009Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:06:01.009Z SendDataConnector.js: do connect now
,2015-11-23 08:06:01.010 ThaliTest[1311:1034688] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:06:01.011 ThaliTest[1311:1034688] client: connect: unreachable Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:06:01.012 ThaliTest[1311:1034688] jxcore: connect: fail: Peer unreachable
2015-11-23T07:06:01.012Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-11-23T07:06:01.013Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-11-23T07:06:01.015Z SendDataConnector.js: CLIENT Stop now
2015-11-23 08:06:01.015 ThaliTest[1311:1034688] jxcore: disconnect
2015-11-23 08:06:01.016 ThaliTest[1311:1034688] jxcore: disconnect: fail
2015-11-23T07:06:01.017Z SendDataConnector.js: Mob,ile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd6Q==
---- round done--------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT606","time":79921,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT8536.VjK3dQ==","time":3054,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT2253.QxwsNA==","time":3327,"result":"OK","connections":1,},{"name":"Apple-Iphone5s-1_PT8264./5qd6Q==","time":73116,"result":"Peer unreachable","connections":5}]}
,sendList : 100% : 3327 ms, 99% : 3327 ms, 95 : 3327 ms, 90% : 3327 ms.
,Result count 2, range 3054 ms to  3327 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone5s-1_PT8264./5qd6Q==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-11-23T07:06:01.029Z SendDataConnector.js: CLIENT Stop now
,2015-11-23 08:06:14.589 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:06:14.607 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:06:14.609 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:06:14.611 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:06:20.384 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:06:22.505 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:06:22.506 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:06:23.004 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-23 08:06:27.901 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:06:27.902 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-11-23 08:06:28.768 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:06:44.587 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:06:44.604 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:06:44.607 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:06:44.608 ThaliTest[1311:1034546] clie,nt: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:06:52.357 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:06:52.358 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:06:52.895 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-11-23 08:06:57.892 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:06:57.893 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:06:58.648 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-11-23 08:07:14.587 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:07:14.604 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:07:14.606 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:07:14.608 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:07:22.515 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:07:22.516 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:07:22.888 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-11-23 08:07:27.898 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:07:27.899 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:07:29.048 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:07:44.587 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:07:44.605 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:07:44.605 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:07:44.607 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:07:53.159 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:08:08.381 ThaliTest[1311:1034546] multipeer session: reset timer
2015-11-23 08:08:08.382 ThaliTest[1311:1034546] multipeer session: stop timer
2015-11-23 08:08:08.383 ThaliTest[1311:1034546] multipeer session: start timer: 0x19e4c050
2015-,11-23 08:08:08.384 ThaliTest[1311:1034546] server session: connect
2015-11-23 08:08:08.384 ThaliTest[1311:1034546] server session: stateChange:0->1 Apple-Iphone5s-1_PT1828
,2015-11-23 08:08:08.395 ThaliTest[1311:1034546] server: accepting invitation Apple-Iphone5s-1_PT1828
,2015-11-23 08:08:10.531 ThaliTest[1311:1035733] server session: connected
2015-11-23 08:08:10.532 ThaliTest[1311:1035733] server session: stateChange:1->2 Apple-Iphone5s-1_PT1828
,2015-11-23 08:08:10.543 ThaliTest[1311:1034546] server relay: connected (to port: 56544)
,2015-11-23T07:08:10.554Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T07:08:10.642Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-11-23T07:08:10.656Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-11-23T07:08:10.673Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-11-23T07:08:10.688Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 08:08:10.711 ThaliTest[1311:1035807] server session: not connected Apple-Iphone5s-1_PT1828
,2015-11-23 08:08:38.385 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:08:38.497 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:08:38.498 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:08:38.499 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:08:53.252 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:08:53.253 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:08:54.488 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:09:00.869 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:09:00.870 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:09:08.385 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:09:08.398 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:09:08.402 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:09:08.869 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,Turning Wifi off
,Warning: iOS does not support ToggleWiFi
,We could not turn wifi off! - Warning: iOS does not support ToggleWiFi
Turning Wifi back on
,Warning: iOS does not support ToggleWiFi
,We could turn wifi back on! - Warning: iOS does not support ToggleWiFi
,toggleWiFi finished
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,2015-11-23 08:09:20.995 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,2015-11-23 08:09:24.139 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,2015-11-23 08:09:32.003 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,2015-11-23 08:09:38.382 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:09:38.400 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:09:38.401 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:09:38.404 ThaliTest[1311:1034546] clie,nt: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,2015-11-23 08:09:48.278 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:09:48.280 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5-1_PT8536.VjK3dQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8536.VjK3dQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:09:50.879 ThaliTest[1311:1034546] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:09:50.879 ThaliTest[1311:1034546] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:09:51.010 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8536.VjK3dQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,2015-11-23 08:10:08.382 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:10:08.404 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:10:08.405 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,2015-11-23 08:10:38.382 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:10:38.399 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:10:38.400 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":,10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"a,rraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,2015-11-23 08:11:08.382 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:11:08.395 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:11:08.397 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":,10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"a,rraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":,10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"a,rraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,2015-11-23 08:11:38.382 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:11:38.424 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:11:38.426 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":,10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"a,rraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,2015-11-23 08:12:08.380 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:12:08.402 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:12:08.404 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:12:38.380 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:12:38.395 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:12:38.555 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:13:08.380 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:13:08.496 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:13:08.497 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,2015-11-23 08:13:38.380 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:13:38.497 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:13:39.358 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:14:08.380 ThaliTest[1311:1034546] multipeer session: restart
,2015-11-23 08:14:08.397 ThaliTest[1311:1034546] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:14:08.767 ThaliTest[1311:1034546] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:14:38.380 ThaliTest[1311:1034546] multipeer session: restart
2015-11-23 08:14:38.388 ThaliTest[1311:1034546] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x26932607 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0xc7693 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 1311 stopped
* thread #1: tid = 0xfc932, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x35e14df0 <+8>:  blo    0x35e14e08                ; <+32>
    0x35e14df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x35e14df8 <+16>: ldr    r12, [pc, r12]
    0x35e14dfc <+20>: b      0x35e14e04                ; <+28>
,* thread #1: tid = 0xfc932, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x35e93cc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x35db0908 libsystem_c.dylib`abort + 76
    frame #3: 0x350a79c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x350c1670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x35798f24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x350bede2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x350be8ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x35798dd2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x26d3f29c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x26d3f012 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x2e7ca200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2a50ba08 UIKit`UIApplicationMain + 1440
    frame #13: 0x000c7692 ThaliTest`main + 50

```
