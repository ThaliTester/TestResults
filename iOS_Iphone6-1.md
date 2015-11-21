#### Test 5133502858c0449_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502858c0449/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0A777DA2-753C-4BA1-8FC2-5A283FD7AF10/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0A777DA2-753C-4BA1-8FC2-5A283FD7AF10/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502858c0449/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502858c0449/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/88A23132-DAFE-4C14-83C7-56363F554490/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51892"
,(lldb)     command script import "/tmp/0A777DA2-753C-4BA1-8FC2-5A283FD7AF10/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-21 11:23:20.993 ThaliTest[1154:834935] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3E6CF39E-CF39-40B9-AC30-BE2A38079E52/Library/Cookies/Cookies.binarycookies
,2015-11-21 11:23:21.370 ThaliTest[1154:834935] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-21 11:23:21.371 ThaliTest[1154:834935] Multi-tasking -> Device: YES, App: YES
,2015-11-21 11:23:21.379 ThaliTest[1154:834935] Unlimited access to network resources
,2015-11-21 11:23:21.385 ThaliTest[1154:834935] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-21 11:23:25.073 ThaliTest[1154:834935] Resetting plugins due to page load.
,2015-11-21 11:23:25.414 ThaliTest[1154:834935] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/88A23132-DAFE-4C14-83C7-56363F554490/ThaliTest.app/www/index.html
,2015-11-21 11:23:25.537 ThaliTest[1154:834935] JXcore Cordova plugin initializing
,2015-11-21 11:23:25.538 ThaliTest[1154:835072] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
,Warning: iOS does not support ToggleBluetooth
We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
We could not set WiFi! - Warning: iOS does not support ToggleWiFi
toggleWiFi
,my name is : Apple-Iphone6-1_PT3409
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
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
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
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::82a:bff:fea6:1c06
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
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
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
found interfaceName: awdl0
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
found interfaceName: awdl0
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
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
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 56143
2015-11-21 11:32:40.587 ThaliTest[1154:835072] jxcore: startBroadcasting
,2015-11-21 11:32:40.602 ThaliTest[1154:835072] server: starting Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:32:40.603 ThaliTest[1154:835072] multipeer session: start timer: 0x1aa24350
2015-11-21 11:32:40.605 ThaliTest[1154:835072] THEMultipeerSession initialized peer Apple-Iphone6-1_PT3409
2015-11-21 11:32:40.605 ThaliTest[1154:835072] jxcore: st,artBroadcasting: success
StartBroadcasting started ok
,2015-11-21T10:32:40.610Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-21 11:32:40.732 ThaliTest[1154:834935] client: found peer: Apple-Iphone6-1_PT1827.PMdwog==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1827.PMdwog==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21T10:32:40.738Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21T10:32:40.739Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21T10:32:40.740Z SendDataConnector.js: do connect now
,2015-11-21 11:32:40.740 ThaliTest[1154:835072] jxcore: connect Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 11:32:40.742 ThaliTest[1154:835072] client session: connect
2015-11-21 11:32:40.742 ThaliTest[1154:835072] client session: stateChange:0->1 Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 11:32:40.928 ThaliTest[1154:834935] client: found peer: Apple-Iphone5-1_PT8098.G9Yv6w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8098.G9Yv6w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-21 11:32:41.003 ThaliTest[1154:834935] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-21 11:32:42.027 ThaliTest[1154:834935] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1308.Xoqqgw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-21 11:32:48.478 ThaliTest[1154:834935] multipeer session: reset timer
2015-11-21 11:32:48.479 ThaliTest[1154:834935] multipeer session: stop timer
2015-11-21 11:32:48.479 ThaliTest[1154:834935] multipeer session: start timer: 0x1aa24350
2015-11-,21 11:32:48.480 ThaliTest[1154:834935] server session: connect
2015-11-21 11:32:48.480 ThaliTest[1154:834935] server session: stateChange:0->1 Apple-Iphone5-1_PT8098
,2015-11-21 11:32:48.493 ThaliTest[1154:834935] server: accepting invitation Apple-Iphone5-1_PT8098
,2015-11-21 11:32:49.007 ThaliTest[1154:834935] multipeer session: reset timer
2015-11-21 11:32:49.008 ThaliTest[1154:834935] multipeer session: stop timer
2015-11-21 11:32:49.008 ThaliTest[1154:834935] multipeer session: start timer: 0x1aa24350
2015-11-,21 11:32:49.009 ThaliTest[1154:834935] server session: connect
2015-11-21 11:32:49.009 ThaliTest[1154:834935] server session: stateChange:0->1 Apple-Iphone5s-1_PT497
,2015-11-21 11:32:49.020 ThaliTest[1154:834935] server: accepting invitation Apple-Iphone5s-1_PT497
,2015-11-21 11:32:51.135 ThaliTest[1154:835810] server session: connected
,2015-11-21 11:32:51.136 ThaliTest[1154:835810] server session: stateChange:1->2 Apple-Iphone5-1_PT8098
,2015-11-21 11:32:51.144 ThaliTest[1154:834935] server relay: connected (to port: 56143)
,2015-11-21T10:32:51.151Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21 11:32:51.192 ThaliTest[1154:835841] server session: connected
2015-11-21 11:32:51.192 ThaliTest[1154:835841] server session: stateChange:1->2 Apple-Iphone5s-1_PT497
,2015-11-21 11:32:51.198 ThaliTest[1154:834935] server relay: connected (to port: 56143)
,2015-11-21T10:32:51.204Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T10:32:51.308Z SendDataTCPServer.js: TCP/IP server has received 11904 bytes of data
,2015-11-21T10:32:51.323Z SendDataTCPServer.js: TCP/IP server has received 16864 bytes of data
,2015-11-21T10:32:51.325Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-11-21T10:32:51.343Z SendDataTCPServer.js: TCP/IP server has received 24800 bytes of data
,2015-11-21T10:32:51.346Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-11-21T10:32:51.358Z SendDataTCPServer.js: TCP/IP server has received 25792 bytes of data
2015-11-21T10:32:51.359Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-11-21T10:32:51.375Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-11-21T10:32:51.390Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-21 11:32:51.597 ThaliTest[1154:835813] server session: not connected Apple-Iphone5s-1_PT497
,2015-11-21T10:32:51.653Z SendDataTCPServer.js: TCP/IP server has received 32736 bytes of data
,2015-11-21T10:32:51.667Z SendDataTCPServer.js: TCP/IP server has received 41664 bytes of data
,2015-11-21T10:32:51.686Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-11-21T10:32:51.700Z SendDataTCPServer.js: TCP/IP server has received 73408 bytes of data
,2015-11-21T10:32:51.740Z SendDataTCPServer.js: TCP/IP server has received 86304 bytes of data
,2015-11-21T10:32:51.754Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-21 11:32:52.122 ThaliTest[1154:835813] server session: not connected Apple-Iphone5-1_PT8098
,2015-11-21 11:32:52.259 ThaliTest[1154:834935] multipeer session: reset timer
2015-11-21 11:32:52.259 ThaliTest[1154:834935] multipeer session: stop timer
2015-11-21 11:32:52.260 ThaliTest[1154:834935] multipeer session: start timer: 0x1aa24350
2015-11-,21 11:32:52.260 ThaliTest[1154:834935] server session: connect
2015-11-21 11:32:52.261 ThaliTest[1154:834935] server session: stateChange:0->1 Apple-IpadAir2-1_PT1308
,2015-11-21 11:32:52.271 ThaliTest[1154:834935] server: accepting invitation Apple-IpadAir2-1_PT1308
,2015-11-21 11:32:54.981 ThaliTest[1154:835810] server session: connected
2015-11-21 11:32:54.982 ThaliTest[1154:835810] server session: stateChange:1->2 Apple-IpadAir2-1_PT1308
,2015-11-21T10:32:54.992Z SendDataTCPServer.js: TCP/IP server connected
2015-11-21 11:32:54.992 ThaliTest[1154:834935] server relay: connected (to port: 56143)
,2015-11-21T10:32:55.389Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-11-21T10:32:55.405Z SendDataTCPServer.js: TCP/IP server has received 37088 bytes of data
,2015-11-21T10:32:55.421Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-11-21T10:32:55.439Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-11-21T10:32:55.455Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-21 11:32:55.518 ThaliTest[1154:835841] server session: not connected Apple-IpadAir2-1_PT1308
,2015-11-21 11:33:13.741 ThaliTest[1154:835833] client session: not connected Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:33:13.742 ThaliTest[1154:835833] client session: onLinkFailure: Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:33:13.742 ThaliTest[1,154:835833] client session: disconnect
2015-11-21 11:33:13.742 ThaliTest[1154:835833] client session: stateChange:1->0 Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:33:13.743 ThaliTest[1154:835833] client session: fireConnectCallback: Apple-Iphone6-1_PT1,827.PMdwog==
2015-11-21 11:33:13.743 ThaliTest[1154:835833] jxcore: connect: fail: Peer disconnected
,2015-11-21T10:33:13.746Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-21T10:33:13.746Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-21T10:33:13.747Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-21T10:33:18.755Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21T10:33:18.756Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 11:33:22.262 ThaliTest[1154:834935] multipeer session: restart
,2015-11-21 11:33:22.285 ThaliTest[1154:834935] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21 11:33:22.286 ThaliTest[1154:834935] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21 11:33:22.287 ThaliTest[1154:834935] client: ,found peer: Apple-Iphone5-1_PT8098.G9Yv6w==
2015-11-21 11:33:22.288 ThaliTest[1154:834935] client: found peer: Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 11:33:23.764 ThaliTest[1154:835072] jxcore: disconnect
2015-11-21 11:33:23.765 ThaliTest[1154:835072] jxcore: disconnect: fail
2015-11-21T10:33:23.766Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1827.PMdwog=,=
,2015-11-21T10:33:23.767Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT1827.PMdwog== with availability status: true
2015-11-21T10:33:23.767Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21T10:33:23.767Z SendDataConnector.js: do connect now
,2015-11-21 11:33:23.768 ThaliTest[1154:835072] jxcore: connect Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:33:23.769 ThaliTest[1154:835072] client session: connect
2015-11-21 11:33:23.770 ThaliTest[1154:835072] client session: stateChange:0->1 Apple-Ip,hone6-1_PT1827.PMdwog==
,2015-11-21 11:33:44.109 ThaliTest[1154:834935] client: lost peer: Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21 11:33:44.109 ThaliTest[1154:834935] client session: onPeerLost: Apple-Iphone5s-1_PT497.kxsT+g==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-21 11:33:47.137 ThaliTest[1154:834935] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tru,e
,2015-11-21 11:33:52.262 ThaliTest[1154:834935] multipeer session: restart
,2015-11-21 11:33:52.285 ThaliTest[1154:834935] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21 11:33:52.286 ThaliTest[1154:834935] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21 11:33:52.287 ThaliTest[1154:834935] client: found peer: Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21 11:33:52.288 ThaliTest[1154:834935] client: found peer: Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 11:33:56.777 ThaliTest[1154:835948] client session: not connected Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:33:56.778 ThaliTest[1154:835948] client session: onLinkFailure: Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:33:56.778 ThaliTest[1,154:835948] client session: disconnect
2015-11-21 11:33:56.779 ThaliTest[1154:835948] client session: stateChange:1->0 Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:33:56.780 ThaliTest[1154:835948] client session: fireConnectCallback: Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:33:56.780 ThaliTest[1154:835948] jxcore: connect: fail: Peer disconnected
,2015-11-21T10:33:56.782Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-11-21T10:33:56.783Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-21T10:33:56.783Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-21T10:34:01.784Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21T10:34:01.785Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 11:34:06.790 ThaliTest[1154:835072] jxcore: disconnect
2015-11-21 11:34:06.790 ThaliTest[1154:835072] jxcore: disconnect: fail
2015-11-21T10:34:06.791Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1827.PMdwog=,=
2015-11-21T10:34:06.792Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT1827.PMdwog== with availability status: true
,2015-11-21T10:34:06.792Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21T10:34:06.792Z SendDataConnector.js: do connect now
,2015-11-21 11:34:06.793 ThaliTest[1154:835072] jxcore: connect Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 11:34:06.794 ThaliTest[1154:835072] client session: connect
2015-11-21 11:34:06.795 ThaliTest[1154:835072] client session: stateChange:0->1 Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 11:34:14.921 ThaliTest[1154:834935] client: lost peer: Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21 11:34:14.922 ThaliTest[1154:834935] client session: onPeerLost: Apple-Iphone5s-1_PT497.kxsT+g==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-21 11:34:17.045 ThaliTest[1154:834935] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tru,e
,2015-11-21 11:34:22.258 ThaliTest[1154:834935] multipeer session: restart
,2015-11-21 11:34:22.280 ThaliTest[1154:834935] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21 11:34:22.282 ThaliTest[1154:834935] client: found peer: Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21 11:34:22.284 ThaliTest[1154:834935] client: found peer: Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 11:34:22.407 ThaliTest[1154:834935] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:34:39.799 ThaliTest[1154:836035] client session: not connected Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:34:39.800 ThaliTest[1154:836035] client session: onLinkFailure: Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:34:39.800 ThaliTest[1,154:836035] client session: disconnect
2015-11-21 11:34:39.801 ThaliTest[1154:836035] client session: stateChange:1->0 Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:34:39.801 ThaliTest[1154:836035] client session: fireConnectCallback: Apple-Iphone6-1_PT1,827.PMdwog==
2015-11-21 11:34:39.802 ThaliTest[1154:836035] jxcore: connect: fail: Peer disconnected
,2015-11-21T10:34:39.804Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-21T10:34:39.804Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-21T10:34:39.805Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-21T10:34:44.817Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21T10:34:44.818Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 11:34:45.236 ThaliTest[1154:834935] client: lost peer: Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:34:45.236 ThaliTest[1154:834935] client session: onPeerLost: Apple-Iphone6-1_PT1827.PMdwog==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1827.PMdwog==","peerName":"(null)","peerAvailable":false}]
,2015-11-21 11:34:49.820 ThaliTest[1154:835072] jxcore: disconnect
2015-11-21 11:34:49.821 ThaliTest[1154:835072] jxcore: disconnect: fail
2015-11-21T10:34:49.821Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21T10:34:49.822Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT1827.PMdwog== with availability status: true
,2015-11-21T10:34:49.822Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21T10:34:49.822Z SendDataConnector.js: do connect now
2015-11-21 11:34:49.823 ThaliTest[1154:835072] jxcore: connect Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 11:34:49.826 ThaliTest[1154:835072] client: connect: unreachable Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:34:49.826 ThaliTest[1154:835072] jxcore: connect: fail: Peer unreachable
2015-11-21T10:34:49.827Z SendDataConnector.js: CLIENT conne,cted to 0, error: Peer unreachable
2015-11-21T10:34:49.827Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-11-21T10:34:49.828Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-21 11:34:52.259 ThaliTest[1154:834935] multipeer session: restart
,2015-11-21 11:34:52.377 ThaliTest[1154:834935] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21 11:34:52.378 ThaliTest[1154:834935] client: found peer: Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21 11:34:52.740 ThaliTest[1154:834935] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21T10:34:54.838Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21T10:34:54.839Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1827.PMdwog==
,2015-11-21 11:34:59.841 ThaliTest[1154:835072] jxcore: disconnect
2015-11-21 11:34:59.842 ThaliTest[1154:835072] jxcore: disconnect: fail
2015-11-21T10:34:59.843Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1827.PMdwog=,=
2015-11-21T10:34:59.843Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT1827.PMdwog== with availability status: true
2015-11-21T10:34:59.843Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1827.PMdwog==
201,5-11-21T10:34:59.844Z SendDataConnector.js: do connect now
2015-11-21 11:34:59.845 ThaliTest[1154:835072] jxcore: connect Apple-Iphone6-1_PT1827.PMdwog==
2015-11-21 11:34:59.845 ThaliTest[1154:835072] client: connect: unreachable Apple-Iphone6-1_PT1827.P,Mdwog==
2015-11-21 11:34:59.846 ThaliTest[1154:835072] jxcore: connect: fail: Peer unreachable
2015-11-21T10:34:59.846Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-21T10:34:59.847Z SendDataConnector.js: CLIENT Can not Co,nnect: Peer unreachable
2015-11-21T10:34:59.855Z SendDataConnector.js: CLIENT Stop now
2015-11-21 11:34:59.856 ThaliTest[1154:835072] jxcore: disconnect
2015-11-21 11:34:59.857 ThaliTest[1154:835072] jxcore: disconnect: fail
2015-11-21T10:34:59.857Z Se,ndDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1827.PMdwog==
---- round done--------
device[2]: Apple-Iphone5-1_PT8098.G9Yv6w==
2015-11-21T10:34:59.860Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT8098.G9,Yv6w==
2015-11-21T10:34:59.860Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8098.G9Yv6w==
2015-11-21T10:34:59.860Z SendDataConnector.js: do connect now
2015-11-21 11:34:59.861 ThaliTest[1154:835072] jxcore: connect Apple-Iphone5-1,_PT8098.G9Yv6w==
2015-11-21 11:34:59.861 ThaliTest[1154:835072] client session: connect
2015-11-21 11:34:59.862 ThaliTest[1154:835072] client session: stateChange:0->1 Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21 11:35:02.659 ThaliTest[1154:836257] client session: connected
2015-11-21 11:35:02.660 ThaliTest[1154:836257] client session: stateChange:1->2 Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21 11:35:02.664 ThaliTest[1154:836257] client session: fireConnectCallback: Apple-Iphone5-1_PT8098.G9Yv6w==
2015-11-21 11:35:02.665 ThaliTest[1154:836257] jxcore: connect: success
2015-11-21T10:35:02.666Z SendDataConnector.js: CLIENT connected to, 56165, error: null
2015-11-21T10:35:02.667Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 11:35:02.671 ThaliTest[1154:834935] client: relay established
2015-11-21 11:35:02.671 ThaliTest[1154:834935] client: new accepted socket: 0x1aa12e50
,2015-11-21T10:35:02.684Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-21T10:35:02.807Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-21T10:35:02.820Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-21T10:35:02.833Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-21T10:35:02.833Z SendDataConnector.js: got all data for this round
,2015-11-21T10:35:02.834Z SendDataConnector.js: CLIENT Stop now
2015-11-21T10:35:02.834Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-21 11:35:02.834 ThaliTest[1154:835072] jxcore: disconnect
,2015-11-21 11:35:02.835 ThaliTest[1154:835072] client session: disconnectFromPeer: Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21 11:35:02.835 ThaliTest[1154:835072] client session: disconnect
2015-11-21 11:35:02.835 ThaliTest[1154:835072] client session: stateChange:2->0 Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21 11:35:02.837 ThaliTest[1154:835072] jxcore: disconnect: success
2015-11-21T10:35:02.837Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8098.G9Yv6w==
---- round done--------
device[3]: Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21T10:35:02.838Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21T10:35:02.838Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21T10:35:02.838Z SendDataConnector.js: do connect now
,2015-11-21 11:35:02.838 ThaliTest[1154:835072] jxcore: connect Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:35:02.840 ThaliTest[1154:835072] client session: connect
,2015-11-21 11:35:02.840 ThaliTest[1154:835072] client session: stateChange:0->1 Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:35:05.585 ThaliTest[1154:836257] client session: connected
2015-11-21 11:35:05.585 ThaliTest[1154:836257] client session: stateChange:1->2 Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:35:05.590 ThaliTest[1154:836045] client session: fireConnectCallback: Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21 11:35:05.591 ThaliTest[1154:836045] jxcore: connect: success
2015-11-21T10:35:05.592Z SendDataConnector.js: CLIENT connected to, 56169, error: null
,2015-11-21T10:35:05.593Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 11:35:05.597 ThaliTest[1154:834935] client: relay established
2015-11-21 11:35:05.597 ThaliTest[1154:834935] client: new accepted socket: 0x1aa05bf0
,2015-11-21T10:35:05.608Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-21T10:35:05.770Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-21T10:35:05.783Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-21T10:35:05.795Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-21T10:35:05.821Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-21T10:35:05.821Z SendDataConnector.js: got all data for this round
,2015-11-21T10:35:05.822Z SendDataConnector.js: CLIENT Stop now
2015-11-21T10:35:05.822Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-21 11:35:05.822 ThaliTest[1154:835072] jxcore: disconnect
,2015-11-21 11:35:05.823 ThaliTest[1154:835072] client session: disconnectFromPeer: Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:35:05.823 ThaliTest[1154:835072] client session: disconnect
2015-11-21 11:35:05.823 ThaliTest[1154:835072] client session: stateChange:2->0 Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:35:05.824 ThaliTest[1154:835072] jxcore: disconnect: success
2015-11-21T10:35:05.825Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.kxsT+g==
,---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT3409","time":145255,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT1827.PMdwog==","time":139113,"result":"Peer unreachable","connections":5},{"name":"Apple-Iphone5-1_PT8098.G9Yv6w==","time":2973,"result":"OK","connections":1},{"name":"Apple-Iphone5s-1_PT497.kxsT+g==","time":2983,"result":"OK","connections":1}]}
,sendList : 100% : 2983 ms, 99% : 2983 ms, 95 : 2983 ms, 90% : 2983 ms.
Result count 2, range 2973 ms to  2983 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone6-1_PT1827.PMdwog==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-11-21T10:35:05.830Z SendDataConnector.js: CLIENT Stop now
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-21 11:35:07.105 ThaliTest[1154:835072] jxcore: stopBroadcasting
2015-11-21 11:35:07.106 ThaliTest[1154:835072] THEMultipeerSession stopping peer
2015-11-21 11:35:07.107 ThaliTest[1154:835072] multipeer session: stop timer
,2015-11-21 11:35:07.107 ThaliTest[1154:835072] server session: disconnect
2015-11-21 11:35:07.111 ThaliTest[1154:835072] server session: stateChange:2->0 Apple-Iphone5-1_PT8098
,2015-11-21 11:35:07.118 ThaliTest[1154:835072] server session: disconnect
2015-11-21 11:35:07.118 ThaliTest[1154:835072] server session: stateChange:2->0 Apple-IpadAir2-1_PT1308
,2015-11-21 11:35:07.123 ThaliTest[1154:835072] server session: disconnect
2015-11-21 11:35:07.124 ThaliTest[1154:835072] server session: stateChange:2->0 Apple-Iphone5s-1_PT497
,2015-11-21 11:35:07.129 ThaliTest[1154:835072] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-21T10:35:07.154Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T10:35:07.156Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T10:35:07.158Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T10:35:07.158Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT8098.G9Yv6w==\",\"time\":2973,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT497.kxsT+g==\",\"time\":2983,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone6-1_PT1827.PMdwog==\",\"time\":139113,\"result\":\"Peer unreachable\",\"connections\":5}],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5-,1_PT8098.G9Yv6w==\",\"time\":2806,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT8098.G9Yv6w==\",\"time\":2973,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT497.kxsT+g==\",\"time\":2983,\"result\":\"OK\",\"connecti,ons\":1},{\"name\":\"Apple-Iphone5s-1_PT497.kxsT+g==\",\"time\":3323,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT3409.7QVn3g==\",\"time\":3435,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT3409.7QVn3g==\",\"time\,":4060,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT1308.Xoqqgw==\",\"time\":4220,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT3409.7QVn3g==\",\"time\":4296,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple,-IpadAir2-1_PT1308.Xoqqgw==\",\"time\":4732,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT497.kxsT+g==\",\"time\":4864,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT8098.G9Yv6w==\",\"time\":5119,\"result\":\"OK\",,\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
