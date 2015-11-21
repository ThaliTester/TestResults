#### Test 51335028e20f43b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028e20f43b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/187A6101-B9A7-4C22-B785-B4770D13A6B6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/187A6101-B9A7-4C22-B785-B4770D13A6B6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028e20f43b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028e20f43b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F1C0563B-E011-4B28-9D1D-2BD835AB59B9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52043"
,(lldb)     command script import "/tmp/187A6101-B9A7-4C22-B785-B4770D13A6B6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-21 13:27:25.652 ThaliTest[1171:845220] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8BC863A4-E129-445E-8FEB-0DF4F6D5B20D/Library/Cookies/Cookies.binarycookies
,2015-11-21 13:27:26.035 ThaliTest[1171:845220] Apache Cordova native platform version 3.9.2 is starting.
2015-11-21 13:27:26.036 ThaliTest[1171:845220] Multi-tasking -> Device: YES, App: YES
,2015-11-21 13:27:26.044 ThaliTest[1171:845220] Unlimited access to network resources
,2015-11-21 13:27:26.050 ThaliTest[1171:845220] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-21 13:27:29.538 ThaliTest[1171:845220] Resetting plugins due to page load.
,2015-11-21 13:27:29.862 ThaliTest[1171:845220] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/F1C0563B-E011-4B28-9D1D-2BD835AB59B9/ThaliTest.app/www/index.html
,2015-11-21 13:27:29.991 ThaliTest[1171:845220] JXcore Cordova plugin initializing
,2015-11-21 13:27:29.992 ThaliTest[1171:845353] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
Warning: iOS does not support ToggleBluetooth
,We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
,toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,my name is : Apple-Iphone6-1_PT8382
,attempting to connect to test coordinator
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
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
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
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
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
-iface: IPv6 is internal : true, has ip: fe80::1
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"1000000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"2\"}","devices":3,"addressList":[,]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"2"}, bt-address lenght : 0
,check server
,serverPort is 56295
,2015-11-21 13:38:22.164 ThaliTest[1171:845353] jxcore: startBroadcasting
,2015-11-21 13:38:22.177 ThaliTest[1171:845353] server: starting Apple-Iphone6-1_PT8382.HGUadg==
,2015-11-21 13:38:22.183 ThaliTest[1171:845353] multipeer session: start timer: 0x1bfab800
2015-11-21 13:38:22.185 ThaliTest[1171:845353] THEMultipeerSession initialized peer Apple-Iphone6-1_PT8382
2015-11-21 13:38:22.186 ThaliTest[1171:845353] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-11-21T12:38:22.189Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-21 13:38:22.443 ThaliTest[1171:845220] client: found peer: Apple-IpadAir2-1_PT5427.N/zz4w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5427.N/zz4w==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT5427.N/zz4w==
2015-11-21T12:38:22.450Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5427.N/zz4w==
2015-11-21T12:38:22.451Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5427.N/zz4w==,
2015-11-21T12:38:22.451Z SendDataConnector.js: do connect now
2015-11-21 13:38:22.452 ThaliTest[1171:845353] jxcore: connect Apple-IpadAir2-1_PT5427.N/zz4w==
2015-11-21 13:38:22.452 ThaliTest[1171:845353] client session: connect
,2015-11-21 13:38:22.453 ThaliTest[1171:845353] client session: stateChange:0->1 Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:22.550 ThaliTest[1171:845220] client: found peer: Apple-Iphone5-1_PT759.cZHSYA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT759.cZHSYA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-21 13:38:24.461 ThaliTest[1171:845220] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8264./5qd6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: t,rue
,2015-11-21 13:38:24.581 ThaliTest[1171:845220] multipeer session: reset timer
2015-11-21 13:38:24.582 ThaliTest[1171:845220] multipeer session: stop timer
2015-11-21 13:38:24.582 ThaliTest[1171:845220] multipeer session: start timer: 0x1bfab800
2015-11-,21 13:38:24.583 ThaliTest[1171:845220] server session: connect
2015-11-21 13:38:24.584 ThaliTest[1171:845220] server session: stateChange:0->1 Apple-Iphone5s-1_PT8264
,2015-11-21 13:38:24.595 ThaliTest[1171:845220] server: accepting invitation Apple-Iphone5s-1_PT8264
,2015-11-21 13:38:26.021 ThaliTest[1171:846344] client session: connected
2015-11-21 13:38:26.022 ThaliTest[1171:846344] client session: stateChange:1->2 Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:26.032 ThaliTest[1171:846348] client session: fireConnectCallback: Apple-IpadAir2-1_PT5427.N/zz4w==
2015-11-21 13:38:26.033 ThaliTest[1171:846348] jxcore: connect: success
,2015-11-21T12:38:26.035Z SendDataConnector.js: CLIENT connected to 56298, error: null
,2015-11-21T12:38:26.036Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 13:38:26.039 ThaliTest[1171:845220] client: relay established
2015-11-21 13:38:26.039 ThaliTest[1171:845220] client: new accepted socket: 0x1bee8150
,2015-11-21T12:38:26.052Z SendDataConnector.js: CLIENT now sending 1000000 bytes of data
,2015-11-21 13:38:26.834 ThaliTest[1171:846344] server session: connected
2015-11-21 13:38:26.834 ThaliTest[1171:846344] server session: stateChange:1->2 Apple-Iphone5s-1_PT8264
,2015-11-21T12:38:26.861Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21 13:38:29.690 ThaliTest[1171:845220] server relay: connected (to port: 56295)
,2015-11-21T12:38:29.703Z SendDataTCPServer.js: TCP/IP server has received 4096 bytes of data
,2015-11-21T12:38:30.543Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
,2015-11-21T12:38:30.590Z SendDataTCPServer.js: TCP/IP server has received 47104 bytes of data
2015-11-21T12:38:30.604Z SendDataConnector.js: CLIENT is data received : 140000
,2015-11-21T12:38:30.619Z SendDataTCPServer.js: TCP/IP server has received 178176 bytes of data
2015-11-21T12:38:30.625Z SendDataTCPServer.js: TCP/IP server has received 307200 bytes of data
2015-11-21T12:38:30.636Z SendDataConnector.js: CLIENT is data received : 270000
,2015-11-21T12:38:30.651Z SendDataTCPServer.js: TCP/IP server has received 438272 bytes of data
2015-11-21T12:38:30.655Z SendDataTCPServer.js: TCP/IP server has received 569344 bytes of data
2015-11-21T12:38:30.659Z SendDataTCPServer.js: TCP/IP server has received 663552 bytes of data
,2015-11-21T12:38:30.678Z SendDataTCPServer.js: TCP/IP server has received 794624 bytes of data
,2015-11-21T12:38:30.683Z SendDataTCPServer.js: TCP/IP server has received 925696 bytes of data
,2015-11-21T12:38:30.687Z SendDataTCPServer.js: TCP/IP server has received 1000002 bytes of data
,2015-11-21T12:38:30.828Z SendDataConnector.js: CLIENT is data received : 650000
,2015-11-21 13:38:30.832 ThaliTest[1171:846348] server session: not connected Apple-Iphone5s-1_PT8264
,2015-11-21T12:38:30.843Z SendDataConnector.js: CLIENT is data received : 900000
,2015-11-21T12:38:30.857Z SendDataConnector.js: CLIENT is data received : 960000
,2015-11-21T12:38:30.895Z SendDataConnector.js: CLIENT is data received : 1000000
,2015-11-21T12:38:30.895Z SendDataConnector.js: got all data for this round
,2015-11-21T12:38:30.898Z SendDataConnector.js: CLIENT Stop now
2015-11-21T12:38:30.898Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 13:38:30.900 ThaliTest[1171:845353] jxcore: disconnect
,2015-11-21 13:38:30.901 ThaliTest[1171:845353] client session: disconnectFromPeer: Apple-IpadAir2-1_PT5427.N/zz4w==
2015-11-21 13:38:30.902 ThaliTest[1171:845353] client session: disconnect
2015-11-21 13:38:30.902 ThaliTest[1171:845353] client session: s,tateChange:2->0 Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:30.905 ThaliTest[1171:845353] jxcore: disconnect: success
2015-11-21T12:38:30.910Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5427.N/zz4w==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT759.cZHSYA==
2015-11-21T12:38:30.913Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT759.cZHSYA==
2015-11-21T12:38:30.914Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT759.cZHSYA==
,2015-11-21T12:38:30.914Z SendDataConnector.js: do connect now
,2015-11-21 13:38:30.914 ThaliTest[1171:845353] jxcore: connect Apple-Iphone5-1_PT759.cZHSYA==
2015-11-21 13:38:30.916 ThaliTest[1171:845353] client session: connect
2015-11-21 13:38:30.916 ThaliTest[1171:845353] client session: stateChange:0->1 Apple-Iph,one5-1_PT759.cZHSYA==
,2015-11-21 13:38:34.750 ThaliTest[1171:845220] multipeer session: reset timer
2015-11-21 13:38:34.751 ThaliTest[1171:845220] multipeer session: stop timer
2015-11-21 13:38:34.751 ThaliTest[1171:845220] multipeer session: start timer: 0x1bfab800
2015-11-,21 13:38:34.752 ThaliTest[1171:845220] server session: connect
2015-11-21 13:38:34.752 ThaliTest[1171:845220] server session: stateChange:0->1 Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:34.762 ThaliTest[1171:845220] server: accepting invitation Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:36.111 ThaliTest[1171:845220] multipeer session: reset timer
2015-11-21 13:38:36.112 ThaliTest[1171:845220] multipeer session: stop timer
2015-11-21 13:38:36.112 ThaliTest[1171:845220] multipeer session: start timer: 0x1bfab800
2015-11-,21 13:38:36.113 ThaliTest[1171:845220] server session: connect
2015-11-21 13:38:36.114 ThaliTest[1171:845220] server session: stateChange:0->1 Apple-Iphone5-1_PT759
,2015-11-21 13:38:36.125 ThaliTest[1171:845220] server: accepting invitation Apple-Iphone5-1_PT759
,2015-11-21 13:38:37.045 ThaliTest[1171:846349] client session: connected
2015-11-21 13:38:37.046 ThaliTest[1171:846349] client session: stateChange:1->2 Apple-Iphone5-1_PT759.cZHSYA==
,2015-11-21 13:38:37.056 ThaliTest[1171:846376] client session: fireConnectCallback: Apple-Iphone5-1_PT759.cZHSYA==
2015-11-21 13:38:37.057 ThaliTest[1171:846376] jxcore: connect: success
2015-11-21T12:38:37.059Z SendDataConnector.js: CLIENT connected to 56302, error: null
2015-11-21T12:38:37.059Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 13:38:37.063 ThaliTest[1171:845220] client: relay established
2015-11-21 13:38:37.063 ThaliTest[1171:845220] client: new accepted socket: 0x1bed8470
,2015-11-21T12:38:37.075Z SendDataConnector.js: CLIENT now sending 1000000 bytes of data
,2015-11-21 13:38:37.433 ThaliTest[1171:846376] server session: connected
2015-11-21 13:38:37.434 ThaliTest[1171:846376] server session: stateChange:1->2 Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:37.440 ThaliTest[1171:845220] server relay: connected (to port: 56295)
,2015-11-21T12:38:37.602Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T12:38:37.808Z SendDataConnector.js: CLIENT is data received : 300000
,2015-11-21 13:38:39.251 ThaliTest[1171:846377] server session: connected
2015-11-21 13:38:39.252 ThaliTest[1171:846377] server session: stateChange:1->2 Apple-Iphone5-1_PT759
,2015-11-21T12:38:39.261Z SendDataTCPServer.js: TCP/IP server has received 2048 bytes of data
,2015-11-21T12:38:39.263Z SendDataConnector.js: CLIENT is data received : 630000
,2015-11-21T12:38:39.675Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21 13:38:39.764 ThaliTest[1171:845220] server relay: connected (to port: 56295)
2015-11-21T12:38:39.804Z SendDataTCPServer.js: TCP/IP server has received 133120 bytes of data
,2015-11-21T12:38:39.812Z SendDataTCPServer.js: TCP/IP server has received 264192 bytes of data
,2015-11-21T12:38:39.821Z SendDataTCPServer.js: TCP/IP server has received 321536 bytes of data
,2015-11-21T12:38:39.827Z SendDataConnector.js: CLIENT is data received : 660000
,2015-11-21T12:38:39.843Z SendDataTCPServer.js: TCP/IP server has received 452608 bytes of data
,2015-11-21T12:38:39.849Z SendDataTCPServer.js: TCP/IP server has received 581632 bytes of data
,2015-11-21T12:38:39.870Z SendDataTCPServer.js: TCP/IP server has received 712704 bytes of data
,2015-11-21T12:38:39.875Z SendDataTCPServer.js: TCP/IP server has received 843776 bytes of data
,2015-11-21T12:38:39.880Z SendDataTCPServer.js: TCP/IP server has received 935936 bytes of data
,2015-11-21T12:38:39.896Z SendDataTCPServer.js: TCP/IP server has received 1000002 bytes of data
,2015-11-21 13:38:39.954 ThaliTest[1171:846401] server session: not connected Apple-IpadAir2-1_PT5427
,2015-11-21T12:38:40.707Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-11-21T12:38:40.722Z SendDataTCPServer.js: TCP/IP server has received 19840 bytes of data
,2015-11-21T12:38:40.736Z SendDataTCPServer.js: TCP/IP server has received 34720 bytes of data
,2015-11-21T12:38:40.751Z SendDataTCPServer.js: TCP/IP server has received 51584 bytes of data
,2015-11-21T12:38:40.766Z SendDataTCPServer.js: TCP/IP server has received 64480 bytes of data
,2015-11-21T12:38:40.778Z SendDataTCPServer.js: TCP/IP server has received 70432 bytes of data
,2015-11-21T12:38:40.805Z SendDataTCPServer.js: TCP/IP server has received 76384 bytes of data
,2015-11-21T12:38:40.819Z SendDataTCPServer.js: TCP/IP server has received 88288 bytes of data
,2015-11-21T12:38:40.835Z SendDataTCPServer.js: TCP/IP server has received 96224 bytes of data
,2015-11-21T12:38:40.848Z SendDataTCPServer.js: TCP/IP server has received 105152 bytes of data
,2015-11-21T12:38:40.863Z SendDataTCPServer.js: TCP/IP server has received 118048 bytes of data
,2015-11-21T12:38:40.877Z SendDataTCPServer.js: TCP/IP server has received 131936 bytes of data
,2015-11-21T12:38:40.891Z SendDataTCPServer.js: TCP/IP server has received 143840 bytes of data
,2015-11-21T12:38:40.903Z SendDataTCPServer.js: TCP/IP server has received 155744 bytes of data
,2015-11-21T12:38:40.916Z SendDataTCPServer.js: TCP/IP server has received 167648 bytes of data
,2015-11-21T12:38:40.930Z SendDataTCPServer.js: TCP/IP server has received 182528 bytes of data
,2015-11-21T12:38:40.945Z SendDataTCPServer.js: TCP/IP server has received 193440 bytes of data
,2015-11-21T12:38:40.957Z SendDataTCPServer.js: TCP/IP server has received 201376 bytes of data
,2015-11-21T12:38:40.958Z SendDataConnector.js: CLIENT is data received : 670000
,2015-11-21T12:38:40.972Z SendDataTCPServer.js: TCP/IP server has received 221216 bytes of data
,2015-11-21T12:38:40.986Z SendDataTCPServer.js: TCP/IP server has received 239072 bytes of data
,2015-11-21T12:38:41.000Z SendDataTCPServer.js: TCP/IP server has received 258912 bytes of data
,2015-11-21T12:38:41.238Z SendDataTCPServer.js: TCP/IP server has received 264864 bytes of data
,2015-11-21T12:38:41.252Z SendDataTCPServer.js: TCP/IP server has received 268832 bytes of data
,2015-11-21T12:38:41.266Z SendDataTCPServer.js: TCP/IP server has received 283712 bytes of data
,2015-11-21T12:38:41.283Z SendDataTCPServer.js: TCP/IP server has received 295616 bytes of data
,2015-11-21T12:38:41.301Z SendDataTCPServer.js: TCP/IP server has received 312480 bytes of data
,2015-11-21T12:38:41.315Z SendDataTCPServer.js: TCP/IP server has received 325376 bytes of data
,2015-11-21T12:38:41.329Z SendDataTCPServer.js: TCP/IP server has received 334304 bytes of data
,2015-11-21T12:38:41.331Z SendDataConnector.js: CLIENT is data received : 1000000
,2015-11-21T12:38:41.332Z SendDataConnector.js: got all data for this round
,2015-11-21T12:38:41.334Z SendDataConnector.js: CLIENT Stop now
,2015-11-21T12:38:41.334Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 13:38:41.336 ThaliTest[1171:845353] jxcore: disconnect
,2015-11-21 13:38:41.337 ThaliTest[1171:845353] client session: disconnectFromPeer: Apple-Iphone5-1_PT759.cZHSYA==
,2015-11-21 13:38:41.339 ThaliTest[1171:845353] client session: disconnect
,2015-11-21 13:38:41.340 ThaliTest[1171:845353] client session: stateChange:2->0 Apple-Iphone5-1_PT759.cZHSYA==
,2015-11-21 13:38:41.344 ThaliTest[1171:845353] jxcore: disconnect: success
,2015-11-21T12:38:41.346Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT759.cZHSYA==
,---- round done--------
,device[3]: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21T12:38:41.350Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21T12:38:41.352Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21T12:38:41.353Z SendDataConnector.js: do connect now
,2015-11-21 13:38:41.354 ThaliTest[1171:845353] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21 13:38:41.356 ThaliTest[1171:845353] client session: connect
,2015-11-21 13:38:41.357 ThaliTest[1171:845353] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21T12:38:41.393Z SendDataTCPServer.js: TCP/IP server has received 339264 bytes of data
,2015-11-21T12:38:41.407Z SendDataTCPServer.js: TCP/IP server has received 355136 bytes of data
,2015-11-21T12:38:41.419Z SendDataTCPServer.js: TCP/IP server has received 391840 bytes of data
,2015-11-21T12:38:41.433Z SendDataTCPServer.js: TCP/IP server has received 395808 bytes of data
,2015-11-21T12:38:41.469Z SendDataTCPServer.js: TCP/IP server has received 397792 bytes of data
,2015-11-21T12:38:41.480Z SendDataTCPServer.js: TCP/IP server has received 423584 bytes of data
,2015-11-21T12:38:41.493Z SendDataTCPServer.js: TCP/IP server has received 457312 bytes of data
,2015-11-21T12:38:41.506Z SendDataTCPServer.js: TCP/IP server has received 462272 bytes of data
,2015-11-21T12:38:41.793Z SendDataTCPServer.js: TCP/IP server has received 475168 bytes of data
,2015-11-21T12:38:41.806Z SendDataTCPServer.js: TCP/IP server has received 485088 bytes of data
,2015-11-21T12:38:41.819Z SendDataTCPServer.js: TCP/IP server has received 497984 bytes of data
,2015-11-21T12:38:41.835Z SendDataTCPServer.js: TCP/IP server has received 506912 bytes of data
,2015-11-21T12:38:41.848Z SendDataTCPServer.js: TCP/IP server has received 510880 bytes of data
,2015-11-21T12:38:41.863Z SendDataTCPServer.js: TCP/IP server has received 520800 bytes of data
,2015-11-21T12:38:41.876Z SendDataTCPServer.js: TCP/IP server has received 535680 bytes of data
,2015-11-21T12:38:41.890Z SendDataTCPServer.js: TCP/IP server has received 551552 bytes of data
,2015-11-21T12:38:41.902Z SendDataTCPServer.js: TCP/IP server has received 568416 bytes of data
,2015-11-21T12:38:41.916Z SendDataTCPServer.js: TCP/IP server has received 580320 bytes of data
,2015-11-21T12:38:41.929Z SendDataTCPServer.js: TCP/IP server has received 595200 bytes of data
,2015-11-21T12:38:41.943Z SendDataTCPServer.js: TCP/IP server has received 612064 bytes of data
,2015-11-21T12:38:41.957Z SendDataTCPServer.js: TCP/IP server has received 625952 bytes of data
,2015-11-21T12:38:41.970Z SendDataTCPServer.js: TCP/IP server has received 646784 bytes of data
,2015-11-21T12:38:41.985Z SendDataTCPServer.js: TCP/IP server has received 674560 bytes of data
,2015-11-21T12:38:42.000Z SendDataTCPServer.js: TCP/IP server has received 693408 bytes of data
,2015-11-21T12:38:42.014Z SendDataTCPServer.js: TCP/IP server has received 717216 bytes of data
,2015-11-21T12:38:42.028Z SendDataTCPServer.js: TCP/IP server has received 736064 bytes of data
,2015-11-21T12:38:42.304Z SendDataTCPServer.js: TCP/IP server has received 738048 bytes of data
,2015-11-21T12:38:42.317Z SendDataTCPServer.js: TCP/IP server has received 749952 bytes of data
,2015-11-21T12:38:42.331Z SendDataTCPServer.js: TCP/IP server has received 763840 bytes of data
,2015-11-21T12:38:42.348Z SendDataTCPServer.js: TCP/IP server has received 775744 bytes of data
,2015-11-21T12:38:42.363Z SendDataTCPServer.js: TCP/IP server has received 785664 bytes of data
,2015-11-21T12:38:42.377Z SendDataTCPServer.js: TCP/IP server has received 796576 bytes of data
,2015-11-21T12:38:42.395Z SendDataTCPServer.js: TCP/IP server has received 808480 bytes of data
,2015-11-21T12:38:42.409Z SendDataTCPServer.js: TCP/IP server has received 818400 bytes of data
,2015-11-21T12:38:42.423Z SendDataTCPServer.js: TCP/IP server has received 834272 bytes of data
,2015-11-21T12:38:42.442Z SendDataTCPServer.js: TCP/IP server has received 846176 bytes of data
,2015-11-21T12:38:42.456Z SendDataTCPServer.js: TCP/IP server has received 863040 bytes of data
,2015-11-21T12:38:42.471Z SendDataTCPServer.js: TCP/IP server has received 881888 bytes of data
,2015-11-21T12:38:42.485Z SendDataTCPServer.js: TCP/IP server has received 892800 bytes of data
,2015-11-21T12:38:42.498Z SendDataTCPServer.js: TCP/IP server has received 905696 bytes of data
,2015-11-21T12:38:42.511Z SendDataTCPServer.js: TCP/IP server has received 923552 bytes of data
,2015-11-21T12:38:42.523Z SendDataTCPServer.js: TCP/IP server has received 938432 bytes of data
,2015-11-21T12:38:42.536Z SendDataTCPServer.js: TCP/IP server has received 956288 bytes of data
,2015-11-21T12:38:42.551Z SendDataTCPServer.js: TCP/IP server has received 966208 bytes of data
,2015-11-21T12:38:42.562Z SendDataTCPServer.js: TCP/IP server has received 985056 bytes of data
,2015-11-21T12:38:42.576Z SendDataTCPServer.js: TCP/IP server has received 991008 bytes of data
,2015-11-21T12:38:42.832Z SendDataTCPServer.js: TCP/IP server has received 1000002 bytes of data
,2015-11-21 13:38:42.862 ThaliTest[1171:846349] server session: not connected Apple-Iphone5-1_PT759
,2015-11-21 13:38:44.054 ThaliTest[1171:846348] client session: connected
,2015-11-21 13:38:44.055 ThaliTest[1171:846348] client session: stateChange:1->2 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21 13:38:44.183 ThaliTest[1171:846348] client session: fireConnectCallback: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-21 13:38:44.184 ThaliTest[1171:846348] jxcore: connect: success
2015-11-21T12:38:44.185Z SendDataConnector.js: CLIENT connected to 56308, error: null
,2015-11-21T12:38:44.185Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 13:38:44.188 ThaliTest[1171:845220] client: relay established
2015-11-21 13:38:44.189 ThaliTest[1171:845220] client: new accepted socket: 0x1bede8a0
,2015-11-21T12:38:44.200Z SendDataConnector.js: CLIENT now sending 1000000 bytes of data
,2015-11-21T12:38:44.779Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-21T12:38:44.826Z SendDataConnector.js: CLIENT is data received : 300000
,2015-11-21T12:38:45.045Z SendDataConnector.js: CLIENT is data received : 740000
,2015-11-21T12:38:45.118Z SendDataConnector.js: CLIENT is data received : 840000
,2015-11-21T12:38:45.160Z SendDataConnector.js: CLIENT is data received : 880000
,2015-11-21T12:38:45.175Z SendDataConnector.js: CLIENT is data received : 1000000
,2015-11-21T12:38:45.176Z SendDataConnector.js: got all data for this round
,2015-11-21T12:38:45.176Z SendDataConnector.js: CLIENT Stop now
,2015-11-21T12:38:45.177Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 13:38:45.177 ThaliTest[1171:845353] jxcore: disconnect
,2015-11-21 13:38:45.178 ThaliTest[1171:845353] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21 13:38:45.179 ThaliTest[1171:845353] client session: disconnect
,2015-11-21 13:38:45.179 ThaliTest[1171:845353] client session: stateChange:2->0 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21 13:38:45.238 ThaliTest[1171:845353] jxcore: disconnect: success
,2015-11-21T12:38:45.239Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd6Q==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT8382","time":23090,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT5427.N/zz4w==","time":8446,"result":"OK","connections":1},{"name":"Apple-Iphone5-1_PT759.cZHSYA==","time":10418,"result":"OK","connections":1},{"name":"Apple-Iphone5s-1_PT8264./5qd6Q==","time":3824,"result":"OK","connections":1}]}
,sendList : 100% : 10418 ms, 99% : 10418 ms, 95 : 10418 ms, 90% : 10418 ms.
,Result count 3, range 3824 ms to  10418 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-21T12:38:45.246Z SendDataConnector.js: CLIENT Stop now
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-21 13:38:53.573 ThaliTest[1171:845353] jxcore: stopBroadcasting
,2015-11-21 13:38:53.575 ThaliTest[1171:845353] THEMultipeerSession stopping peer
,2015-11-21 13:38:53.575 ThaliTest[1171:845353] multipeer session: stop timer
2015-11-21 13:38:53.576 ThaliTest[1171:845353] server session: disconnect
2015-11-21 13:38:53.577 ThaliTest[1171:845353] server session: stateChange:2->0 Apple-Iphone5s-1_PT8264
,2015-11-21 13:38:53.646 ThaliTest[1171:845353] server session: disconnect
,2015-11-21 13:38:53.648 ThaliTest[1171:845353] server session: stateChange:2->0 Apple-Iphone5-1_PT759
,2015-11-21 13:38:53.651 ThaliTest[1171:845353] server session: disconnect
,2015-11-21 13:38:53.654 ThaliTest[1171:845353] server session: stateChange:2->0 Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:53.657 ThaliTest[1171:845353] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-21T12:38:53.672Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T12:38:53.672Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T12:38:53.673Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-21T12:38:53.673Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT8264./5qd6Q==\",\"time\":3824,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT5427.N/zz4w==\",\"time\":8446,\,"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT759.cZHSYA==\",\"time\":10418,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT8264./5q,d6Q==\",\"time\":3824,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8264./5qd6Q==\",\"time\":5219,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8382.HGUadg==\",\"time\":5413,\"result\":\"OK\",\"connections\":1},{\,"name\":\"Apple-IpadAir2-1_PT5427.N/zz4w==\",\"time\":5651,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8382.HGUadg==\",\"time\":6347,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8382.HGUadg==\",\"time\":7858,\"r,esult\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT5427.N/zz4w==\",\"time\":8446,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT759.cZHSYA==\",\"time\":8528,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8264./5qd6Q==\",\"time\":8989,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT759.cZHSYA==\",\"time\":10418,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT759.cZHSYA==\",\"time\":11883,\"result\":\"OK\",\"connectio,ns\":1},{\"name\":\"Apple-IpadAir2-1_PT5427.N/zz4w==\",\"time\":12622,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
