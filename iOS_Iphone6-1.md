#### Test 5133502893bec48_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502893bec48/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DD2B365B-3B13-47E9-B997-2A93F7F7A543/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DD2B365B-3B13-47E9-B997-2A93F7F7A543/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502893bec48/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502893bec48/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E6984818-A13E-4477-94C8-46E63EBC8E40/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50772"
,(lldb)     command script import "/tmp/DD2B365B-3B13-47E9-B997-2A93F7F7A543/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 10:49:56.669 ThaliTest[1013:717363] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E43D1C7E-1D68-4F2E-97B8-ED394D2CD6CB/Library/Cookies/Cookies.binarycookies
,2015-11-20 10:49:57.051 ThaliTest[1013:717363] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 10:49:57.052 ThaliTest[1013:717363] Multi-tasking -> Device: YES, App: YES
,2015-11-20 10:49:57.061 ThaliTest[1013:717363] Unlimited access to network resources
,2015-11-20 10:49:57.067 ThaliTest[1013:717363] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 10:50:00.740 ThaliTest[1013:717363] Resetting plugins due to page load.
,2015-11-20 10:50:01.210 ThaliTest[1013:717363] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/E6984818-A13E-4477-94C8-46E63EBC8E40/ThaliTest.app/www/index.html
,2015-11-20 10:50:01.410 ThaliTest[1013:717363] JXcore Cordova plugin initializing
,2015-11-20 10:50:01.411 ThaliTest[1013:717516] JXcore instance initializing
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
,toggleWiFi
,my name is : Apple-Iphone6-1_PT9036
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
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
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":1,"addressList":[],}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 55265
2015-11-20 10:59:42.848 ThaliTest[1013:717516] jxcore: startBroadcasting
,2015-11-20 10:59:42.863 ThaliTest[1013:717516] server: starting Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 10:59:42.866 ThaliTest[1013:717516] multipeer session: start timer: 0x1c50c370
2015-11-20 10:59:42.868 ThaliTest[1013:717516] THEMultipeerSession initialized peer Apple-Iphone6-1_PT9036
2015-11-20 10:59:42.869 ThaliTest[1013:717516] jxcore: startBroadcasting: success
StartBroadcasting started ok
TCP/IP server  is bound to : undefined
,2015-11-20 10:59:43.066 ThaliTest[1013:717363] client: found peer: Apple-Iphone5s-1_PT4118.XhZL4Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4118.XhZL4Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 10:59:48.083 ThaliTest[1013:717516] jxcore: disconnect
2015-11-20 10:59:48.084 ThaliTest[1013:717516] jxcore: disconnect: fail
SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5s-1_PT4118.XhZL4Q== with availability status: true
,SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: do connect now
,2015-11-20 10:59:48.088 ThaliTest[1013:717516] jxcore: connect Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 10:59:48.089 ThaliTest[1013:717516] client session: connect
2015-11-20 10:59:48.089 ThaliTest[1013:717516] client session: stateChange:0->1 Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 10:59:49.267 ThaliTest[1013:717363] multipeer session: reset timer
2015-11-20 10:59:49.268 ThaliTest[1013:717363] multipeer session: stop timer
2015-11-20 10:59:49.269 ThaliTest[1013:717363] multipeer session: start timer: 0x1c50c370
2015-11-,20 10:59:49.269 ThaliTest[1013:717363] server session: connect
2015-11-20 10:59:49.270 ThaliTest[1013:717363] server session: stateChange:0->1 Apple-Iphone5s-1_PT4118
,2015-11-20 10:59:49.280 ThaliTest[1013:717363] server: accepting invitation Apple-Iphone5s-1_PT4118
,2015-11-20 10:59:51.362 ThaliTest[1013:718314] client session: connected
2015-11-20 10:59:51.363 ThaliTest[1013:718314] client session: stateChange:1->2 Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 10:59:51.375 ThaliTest[1013:718314] client session: fireConnectCallback: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 10:59:51.376 ThaliTest[1013:718314] jxcore: connect: success
SendDataConnector.js: CLIENT connected to 55269, error: null
,SendDataConnector.js: CLIENT starting client 
,2015-11-20 10:59:51.382 ThaliTest[1013:717363] client: relay established
2015-11-20 10:59:51.382 ThaliTest[1013:717363] client: new accepted socket: 0x1c33bb30
,SendDataConnector.js: CLIENT now sending 100000 bytes of data
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 10:59:51.481 ThaliTest[1013:718324] server session: connected
2015-11-20 10:59:51.481 ThaliTest[1013:718324] server session: stateChange:1->2 Apple-Iphone5s-1_PT4118
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: CLIENT is data received : 10000
,2015-11-20 10:59:51.510 ThaliTest[1013:717363] server relay: connected (to port: 55265)
,TCP/IP server connected
,SendDataConnector.js: CLIENT is data received : 10000
,TCP/IP server has received 23806 bytes of data
,TCP/IP server has received 61320 bytes of data
,TCP/IP server has received 74460 bytes of data
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: CLIENT is data received : 20000
TCP/IP server has received 100002 bytes of data
,SendDataConnector.js: Receiving data timeout now
,SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 11:00:01.892 ThaliTest[1013:717363] client: socket closed
SendDataConnector.js: tryAgain afer: 5000 ms.
2015-11-20 11:00:01.893 ThaliTest[1013:717363] client relay: socket disconnected
SendDataConnector.js: ----------------- closeClientSocket,
2015-11-20 11:00:01.893 ThaliTest[1013:717363] client relay: 0x1c33bb30 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c66e7e0 {NSLocalizedDescription=Socket closed by remote peer} 
SendD,ataConnector.js: CLIENT is closed
,2015-11-20 11:00:01.894 ThaliTest[1013:717363] client session: socket closed: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:00:01.896 ThaliTest[1013:717363] client session: onLinkFailure: Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:01.896 ThaliTest[1013:717363] client session: disconnect
,2015-11-20 11:00:01.897 ThaliTest[1013:717363] client session: stateChange:2->0 Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:01.899 ThaliTest[1013:717363] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:01.938 ThaliTest[1013:718381] server session: not connected Apple-Iphone5s-1_PT4118
,SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:11.913 ThaliTest[1013:717516] jxcore: disconnect
2015-11-20 11:00:11.914 ThaliTest[1013:717516] jxcore: disconnect: fail
SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js:, Connect (retry count 1) to peer Apple-Iphone5s-1_PT4118.XhZL4Q== with availability status: true
,SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: do connect now
,2015-11-20 11:00:11.916 ThaliTest[1013:717516] jxcore: connect Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:11.918 ThaliTest[1013:717516] client session: connect
2015-11-20 11:00:11.919 ThaliTest[1013:717516] client session: stateChange:0->1 Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:12.241 ThaliTest[1013:717363] multipeer session: reset timer
2015-11-20 11:00:12.241 ThaliTest[1013:717363] multipeer session: stop timer
2015-11-20 11:00:12.241 ThaliTest[1013:717363] multipeer session: start timer: 0x1c50c370
2015-11-20 11:00:12.241 ThaliTest[1013:717363] server: disconnecting to refresh session (Apple-Iphone5s-1_PT4118)
2015-11-20 11:00:12.242 ThaliTest[1013:717363] server session: disconnect
2015-11-20 11:00:12.242 ThaliTest[1013:717363] server session: stateChange:2->0 Apple-Iphone5s-1_PT4118
2015-11-20 11:00:12.243 ThaliTest[1013:717363] server session: connect
2015-11-20 11:00:12.243 ThaliTest[1013:717363] server session: stateChange:0->1 Apple-Iphone5s-1_PT4118
,TCP/IP server is ended
TCP/IP server is close
,2015-11-20 11:00:12.247 ThaliTest[1013:717363] server: accepting invitation Apple-Iphone5s-1_PT4118
,2015-11-20 11:00:14.309 ThaliTest[1013:718402] client session: connected
2015-11-20 11:00:14.310 ThaliTest[1013:718402] client session: stateChange:1->2 Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:14.318 ThaliTest[1013:718417] client session: fireConnectCallback: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:00:14.319 ThaliTest[1013:718417] jxcore: connect: success
SendDataConnector.js: CLIENT connected to 55274, error: null
,SendDataConnector.js: CLIENT starting client 
,2015-11-20 11:00:14.325 ThaliTest[1013:717363] client: relay established
2015-11-20 11:00:14.326 ThaliTest[1013:717363] client: new accepted socket: 0x1c675a70
,SendDataConnector.js: CLIENT now sending 80000 bytes of data
,2015-11-20 11:00:14.354 ThaliTest[1013:718417] server session: connected
2015-11-20 11:00:14.355 ThaliTest[1013:718417] server session: stateChange:1->2 Apple-Iphone5s-1_PT4118
,2015-11-20 11:00:14.368 ThaliTest[1013:717363] server relay: connected (to port: 55265)
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,TCP/IP server connected
,TCP/IP server has received 6570 bytes of data
,TCP/IP server has received 21900 bytes of data
,TCP/IP server has received 26280 bytes of data
,TCP/IP server has received 80002 bytes of data
,SendDataConnector.js: CLIENT is data received : 20000
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: CLIENT is data received : 30000
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: CLIENT is data received : 40000
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: CLIENT is data received : 50000
,2015-11-20 11:00:24.559 ThaliTest[1013:718405] server session: not connected Apple-Iphone5s-1_PT4118
,SendDataConnector.js: Receiving data timeout now
,SendDataConnector.js: CLIENT closeClientSocket
,SendDataConnector.js: tryAgain afer: 5000 ms.
,SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20 11:00:24.699 ThaliTest[1013:717363] client: socket closed
SendDataConnector.js: CLIENT is closed
2015-11-20 11:00:24.699 ThaliTest[1013:717363] client relay: socket disconnected
2015-11-20 11:00:24.700 ThaliTest[1013:717363] client relay: 0x1,c675a70 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c507430 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 11:00:24.701 ThaliTest[1013:717363] client session: socket c,losed: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:00:24.701 ThaliTest[1013:717363] client session: onLinkFailure: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:00:24.701 ThaliTest[1013:717363] client session: disconnect
2015-11-20 11:00:24.702 Thal,iTest[1013:717363] client session: stateChange:2->0 Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:24.703 ThaliTest[1013:717363] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:34.629 ThaliTest[1013:717363] multipeer session: reset timer
2015-11-20 11:00:34.630 ThaliTest[1013:717363] multipeer session: stop timer
2015-11-20 11:00:34.630 ThaliTest[1013:717363] multipeer session: start timer: 0x1c50c370
2015-11-,20 11:00:34.631 ThaliTest[1013:717363] server: disconnecting to refresh session (Apple-Iphone5s-1_PT4118)
2015-11-20 11:00:34.632 ThaliTest[1013:717363] server session: disconnect
2015-11-20 11:00:34.632 ThaliTest[1013:717363] server session: stateChange,:2->0 Apple-Iphone5s-1_PT4118
2015-11-20 11:00:34.635 ThaliTest[1013:717363] server session: connect
2015-11-20 11:00:34.636 ThaliTest[1013:717363] server session: stateChange:0->1 Apple-Iphone5s-1_PT4118
TCP/IP server is ended
TCP/IP server is close
,2015-11-20 11:00:34.655 ThaliTest[1013:717363] server: accepting invitation Apple-Iphone5s-1_PT4118
,2015-11-20 11:00:34.718 ThaliTest[1013:717516] jxcore: disconnect
2015-11-20 11:00:34.719 ThaliTest[1013:717516] jxcore: disconnect: fail
SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT4118.XhZL4Q== with availability status: true
,SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: do connect now
,2015-11-20 11:00:34.721 ThaliTest[1013:717516] jxcore: connect Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:00:34.723 ThaliTest[1013:717516] client session: connect
2015-11-20 11:00:34.723 ThaliTest[1013:717516] client session: stateChange:0->1 Apple-I,phone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:36.925 ThaliTest[1013:718451] server session: connected
2015-11-20 11:00:36.926 ThaliTest[1013:718451] server session: stateChange:1->2 Apple-Iphone5s-1_PT4118
,2015-11-20 11:00:36.939 ThaliTest[1013:717363] server relay: connected (to port: 55265)
,TCP/IP server connected
,TCP/IP server has received 13140 bytes of data
,TCP/IP server has received 41610 bytes of data
,2015-11-20 11:00:37.067 ThaliTest[1013:718453] client session: connected
2015-11-20 11:00:37.068 ThaliTest[1013:718453] client session: stateChange:1->2 Apple-Iphone5s-1_PT4118.XhZL4Q==
TCP/IP server has received 56940 bytes of data
,2015-11-20 11:00:37.077 ThaliTest[1013:718450] client session: fireConnectCallback: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:00:37.078 ThaliTest[1013:718450] jxcore: connect: success
TCP/IP server has received 60002 bytes of data
,SendDataConnector.js: CLIENT connected to 55280, error: null
,SendDataConnector.js: CLIENT starting client 
,2015-11-20 11:00:37.086 ThaliTest[1013:717363] client: relay established
2015-11-20 11:00:37.087 ThaliTest[1013:717363] client: new accepted socket: 0x1c678520
,SendDataConnector.js: CLIENT now sending 50000 bytes of data
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: CLIENT is data received : 60000
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: CLIENT is data received : 70000
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: CLIENT is data received : 80000
,SendDataConnector.js: Receiving data timeout now
SendDataConnector.js: CLIENT closeClientSocket
,SendDataConnector.js: tryAgain afer: 5000 ms.
SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 11:00:47.203 ThaliTest[1013:717363] client: socket closed
SendDataConnector.js: CLIENT is closed
2015-11-20 11:00:47.204 ThaliTest[1013:7,17363] client relay: socket disconnected
2015-11-20 11:00:47.205 ThaliTest[1013:717363] client relay: 0x1c678520 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c345510 {NSLocalizedDescripti,on=Socket closed by remote peer} 
,2015-11-20 11:00:47.205 ThaliTest[1013:717363] client session: socket closed: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:00:47.206 ThaliTest[1013:717363] client session: onLinkFailure: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:00:47.206 ThaliTes,t[1013:717363] client session: disconnect
,2015-11-20 11:00:47.207 ThaliTest[1013:717363] client session: stateChange:2->0 Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:00:47.210 ThaliTest[1013:717363] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:47.243 ThaliTest[1013:718482] server session: not connected Apple-Iphone5s-1_PT4118
,SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:57.224 ThaliTest[1013:717516] jxcore: disconnect
2015-11-20 11:00:57.224 ThaliTest[1013:717516] jxcore: disconnect: fail
SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js:, Connect (retry count 3) to peer Apple-Iphone5s-1_PT4118.XhZL4Q== with availability status: true
,SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: do connect now
,2015-11-20 11:00:57.226 ThaliTest[1013:717516] jxcore: connect Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:00:57.228 ThaliTest[1013:717516] client session: connect
2015-11-20 11:00:57.228 ThaliTest[1013:717516] client session: stateChange:0->1 Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:57.398 ThaliTest[1013:717363] multipeer session: reset timer
2015-11-20 11:00:57.399 ThaliTest[1013:717363] multipeer session: stop timer
2015-11-20 11:00:57.399 ThaliTest[1013:717363] multipeer session: start timer: 0x1c50c370
2015-11-,20 11:00:57.400 ThaliTest[1013:717363] server: disconnecting to refresh session (Apple-Iphone5s-1_PT4118)
2015-11-20 11:00:57.401 ThaliTest[1013:717363] server session: disconnect
2015-11-20 11:00:57.401 ThaliTest[1013:717363] server session: stateChange:2->0 Apple-Iphone5s-1_PT4118
,2015-11-20 11:00:57.405 ThaliTest[1013:717363] server session: connect
,2015-11-20 11:00:57.406 ThaliTest[1013:717363] server session: stateChange:0->1 Apple-Iphone5s-1_PT4118
TCP/IP server is ended
TCP/IP server is close
,2015-11-20 11:00:57.415 ThaliTest[1013:717363] server: accepting invitation Apple-Iphone5s-1_PT4118
,2015-11-20 11:00:59.528 ThaliTest[1013:718509] server session: connected
2015-11-20 11:00:59.529 ThaliTest[1013:718509] server session: stateChange:1->2 Apple-Iphone5s-1_PT4118
2015-11-20 11:00:59.530 ThaliTest[1013:718517] client session: connected
201,5-11-20 11:00:59.530 ThaliTest[1013:718517] client session: stateChange:1->2 Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:00:59.539 ThaliTest[1013:717363] server relay: connected (to port: 55265)
,TCP/IP server connected
,2015-11-20 11:00:59.551 ThaliTest[1013:718510] client session: fireConnectCallback: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:00:59.551 ThaliTest[1013:718510] jxcore: connect: success
SendDataConnector.js: CLIENT connected to 55284, error: null
Sen,dDataConnector.js: CLIENT starting client 
,2015-11-20 11:00:59.556 ThaliTest[1013:717363] client: relay established
2015-11-20 11:00:59.557 ThaliTest[1013:717363] client: new accepted socket: 0x1c33c200
,SendDataConnector.js: CLIENT now sending 20000 bytes of data
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,TCP/IP server has received 12288 bytes of data
,TCP/IP server has received 32850 bytes of data
SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: CLIENT is data received : 90000
,TCP/IP server has received 40002 bytes of data
,SendDataConnector.js: Receiving data timeout now
,SendDataConnector.js: CLIENT closeClientSocket
SendDataConnector.js: tryAgain afer: 5000 ms.
2015-11-20 11:01:09.649 ThaliTest[1013:717363] client: socket closed
SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 11:01:09.649 ThaliTes,t[1013:717363] client relay: socket disconnected
SendDataConnector.js: CLIENT is closed
2015-11-20 11:01:09.650 ThaliTest[1013:717363] client relay: 0x1c33c200 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote, peer" UserInfo=0x1c671ac0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-20 11:01:09.650 ThaliTest[1013:717363] client session: socket closed: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:01:09.651 ThaliTest[1013:717363] client session: onLinkFailure: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:01:09.652 ThaliTes,t[1013:717363] client session: disconnect
,2015-11-20 11:01:09.652 ThaliTest[1013:717363] client session: stateChange:2->0 Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:01:09.655 ThaliTest[1013:717363] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:01:09.960 ThaliTest[1013:718539] server session: not connected Apple-Iphone5s-1_PT4118
,SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:01:19.660 ThaliTest[1013:717516] jxcore: disconnect
2015-11-20 11:01:19.661 ThaliTest[1013:717516] jxcore: disconnect: fail
SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT4118.XhZL4Q== with availability status: true
,SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
SendDataConnector.js: do connect now
,2015-11-20 11:01:19.663 ThaliTest[1013:717516] jxcore: connect Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:01:19.664 ThaliTest[1013:717516] client session: connect
2015-11-20 11:01:19.665 ThaliTest[1013:717516] client session: stateChange:0->1 Apple-I,phone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:01:20.080 ThaliTest[1013:717363] multipeer session: reset timer
2015-11-20 11:01:20.080 ThaliTest[1013:717363] multipeer session: stop timer
2015-11-20 11:01:20.081 ThaliTest[1013:717363] multipeer session: start timer: 0x1c50c370
2015-11-,20 11:01:20.082 ThaliTest[1013:717363] server: disconnecting to refresh session (Apple-Iphone5s-1_PT4118)
2015-11-20 11:01:20.083 ThaliTest[1013:717363] server session: disconnect
2015-11-20 11:01:20.083 ThaliTest[1013:717363] server session: stateChange,:2->0 Apple-Iphone5s-1_PT4118
2015-11-20 11:01:20.086 ThaliTest[1013:717363] server session: connect
2015-11-20 11:01:20.087 ThaliTest[1013:717363] server session: stateChange:0->1 Apple-Iphone5s-1_PT4118
TCP/IP server is ended
TCP/IP server is close
,2015-11-20 11:01:20.096 ThaliTest[1013:717363] server: accepting invitation Apple-Iphone5s-1_PT4118
,2015-11-20 11:01:22.236 ThaliTest[1013:718561] client session: connected
2015-11-20 11:01:22.237 ThaliTest[1013:718561] client session: stateChange:1->2 Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:01:22.248 ThaliTest[1013:718559] client session: fireConnectCallback: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:01:22.249 ThaliTest[1013:718559] jxcore: connect: success
SendDataConnector.js: CLIENT connected to 55288, error: null
,SendDataConnector.js: CLIENT starting client 
,2015-11-20 11:01:22.254 ThaliTest[1013:717363] client: relay established
2015-11-20 11:01:22.255 ThaliTest[1013:717363] client: new accepted socket: 0x1c670df0
,SendDataConnector.js: CLIENT now sending 10000 bytes of data
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:01:22.284 ThaliTest[1013:718559] server session: connected
2015-11-20 11:01:22.285 ThaliTest[1013:718559] server session: stateChange:1->2 Apple-Iphone5s-1_PT4118
,2015-11-20 11:01:22.299 ThaliTest[1013:717363] server relay: connected (to port: 55265)
TCP/IP server connected
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,SendDataConnector.js: CLIENT is data received : 100000
,SendDataConnector.js: got all data for this round
,SendDataConnector.js: CLIENT Stop now
,SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 11:01:22.320 ThaliTest[1013:717516] jxcore: disconnect
2015-11-20 11:01:22.321 ThaliTest[1013:717516] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4118.XhZL4Q==
2015-11-20 11:01:22.321 ThaliTest[1013:717516] client session: disconnec,t
2015-11-20 11:01:22.322 ThaliTest[1013:717516] client session: stateChange:2->0 Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 11:01:22.324 ThaliTest[1013:717516] jxcore: disconnect: success
SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4118.XhZL4Q==
,---- round done--------
,weAreDoneNow , resultArray.length: 1
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT9036","time":99499,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT4118.XhZL4Q==","time":99253,"result":"OK","connections":5}]}
,sendList : 100% : 99253 ms, 99% : 99253 ms, 95 : 99253 ms, 90% : 99253 ms.
,Result count 1, range 99253 ms to  99253 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,SendDataConnector.js: CLIENT Stop now
,SendDataConnector.js: CLIENT is closed
,TCP/IP server has received 10002 bytes of data
,2015-11-20 11:01:22.592 ThaliTest[1013:718555] server session: not connected Apple-Iphone5s-1_PT4118
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-20 11:01:23.084 ThaliTest[1013:717516] jxcore: stopBroadcasting
,2015-11-20 11:01:23.085 ThaliTest[1013:717516] THEMultipeerSession stopping peer
,2015-11-20 11:01:23.086 ThaliTest[1013:717516] multipeer session: stop timer
2015-11-20 11:01:23.086 ThaliTest[1013:717516] server session: disconnect
2015-11-20 11:01:23.087 ThaliTest[1013:717516] server session: stateChange:2->0 Apple-Iphone5s-1_PT4118
,2015-11-20 11:01:23.094 ThaliTest[1013:717516] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,TCP/IP server is ended
,TCP/IP server  socket is disconnected
,TCP/IP server is close
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT4118.XhZL4Q==\",\"time\":99253,\"result\":\"OK\",\"connections\":5}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"com,bined\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT9036.Dzps4Q==\",\"time\":98606,\"result\":\"OK\",\"connections\":5},{\"name\":\"Apple-Iphone5s-1_PT4118.XhZL4Q==\",\"time\":99253,\"result\":\"OK\",\"connections\":5}]}}","devices":2,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
