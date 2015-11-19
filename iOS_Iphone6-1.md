#### Test 5119382166efe78_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5119382166efe78/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/FAC32237-58F9-4578-9B4C-B0D000BEF3DF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/FAC32237-58F9-4578-9B4C-B0D000BEF3DF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5119382166efe78/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5119382166efe78/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F61A9315-2726-4F76-9F0E-44FF0D364F8D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50303"
,(lldb)     command script import "/tmp/FAC32237-58F9-4578-9B4C-B0D000BEF3DF/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-19 09:51:05.409 ThaliTest[922:604623] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4B24687B-BB97-4324-B9B2-7EEC97E4E6D8/Library/Cookies/Cookies.binarycookies
,2015-11-19 09:51:05.802 ThaliTest[922:604623] Apache Cordova native platform version 3.9.2 is starting.
2015-11-19 09:51:05.803 ThaliTest[922:604623] Multi-tasking -> Device: YES, App: YES
,2015-11-19 09:51:05.812 ThaliTest[922:604623] Unlimited access to network resources
,2015-11-19 09:51:05.818 ThaliTest[922:604623] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-19 09:51:09.573 ThaliTest[922:604623] Resetting plugins due to page load.
,2015-11-19 09:51:09.981 ThaliTest[922:604623] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/F61A9315-2726-4F76-9F0E-44FF0D364F8D/ThaliTest.app/www/index.html
,2015-11-19 09:51:10.104 ThaliTest[922:604623] JXcore Cordova plugin initializing
2015-11-19 09:51:10.106 ThaliTest[922:604776] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT5791
,attempting to connect to test coordinator
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
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
-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::b87b:99ff:fe6d:8da9
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"1000000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":2,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"500000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 54899
,2015-11-19 10:02:05.999 ThaliTest[922:604776] jxcore: startBroadcasting
,2015-11-19 10:02:06.012 ThaliTest[922:604776] server: starting Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:02:06.013 ThaliTest[922:604776] multipeer session: start timer: 0x1c7431d0
2015-11-19 10:02:06.014 ThaliTest[922:604776] THEMultipeerSession init,ialized peer Apple-Iphone6-1_PT5791
2015-11-19 10:02:06.014 ThaliTest[922:604776] jxcore: startBroadcasting: success
StartBroadcasting started ok
TCP/IP server  is bound to : undefined
,2015-11-19 10:02:06.593 ThaliTest[922:604623] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4426.kvRdCA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[1]: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:02:08.247 ThaliTest[922:604623] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-19 10:02:11.603 ThaliTest[922:604776] jxcore: disconnect
2015-11-19 10:02:11.604 ThaliTest[922:604776] jxcore: disconnect: fail
Connect (retry count 0) to peer Apple-IpadAir2-1_PT4426.kvRdCA== with availability status: true
do connect now
,2015-11-19 10:02:11.606 ThaliTest[922:604776] jxcore: connect Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:02:11.607 ThaliTest[922:604776] client session: connect
2015-11-19 10:02:11.607 ThaliTest[922:604776] client session: stateChange:0->1 Apple-Ipad,Air2-1_PT4426.kvRdCA==
,2015-11-19 10:02:14.158 ThaliTest[922:604623] multipeer session: reset timer
2015-11-19 10:02:14.158 ThaliTest[922:604623] multipeer session: stop timer
2015-11-19 10:02:14.159 ThaliTest[922:604623] multipeer session: start timer: 0x1c7431d0
2015-11-19 ,10:02:14.160 ThaliTest[922:604623] server session: connect
2015-11-19 10:02:14.161 ThaliTest[922:604623] server session: stateChange:0->1 Apple-IpadAir2-1_PT4426
,2015-11-19 10:02:14.170 ThaliTest[922:604623] server: accepting invitation Apple-IpadAir2-1_PT4426
,2015-11-19 10:02:14.453 ThaliTest[922:604623] multipeer session: reset timer
2015-11-19 10:02:14.453 ThaliTest[922:604623] multipeer session: stop timer
2015-11-19 10:02:14.453 ThaliTest[922:604623] multipeer session: start timer: 0x1c7431d0
2015-11-19 10:02:14.454 ThaliTest[922:604623] server session: connect
2015-11-19 10:02:14.454 ThaliTest[922:604623] server session: stateChange:0->1 Apple-Iphone5s-1_PT5906
,2015-11-19 10:02:14.457 ThaliTest[922:604623] server: accepting invitation Apple-Iphone5s-1_PT5906
,2015-11-19 10:02:14.597 ThaliTest[922:605706] client session: connected
2015-11-19 10:02:14.598 ThaliTest[922:605706] client session: stateChange:1->2 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:02:14.610 ThaliTest[922:605706] client session: fireConnectCallback: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:02:14.610 ThaliTest[922:605706] jxcore: connect: success
,CLIENT connected to 54902, error: null
CLIENT starting client 
,2015-11-19 10:02:14.614 ThaliTest[922:604623] client: relay established
2015-11-19 10:02:14.614 ThaliTest[922:604623] client: new accepted socket: 0x1c74bcd0
,CLIENT now sending 1000000 bytes of data
,CLIENT is data received : 0
,CLIENT is data received : 0
,CLIENT is data received : 0
,CLIENT is data received : 10000
,CLIENT is data received : 20000
,CLIENT is data received : 20000
,2015-11-19 10:02:16.753 ThaliTest[922:605685] server session: connected
2015-11-19 10:02:16.754 ThaliTest[922:605685] server session: stateChange:1->2 Apple-Iphone5s-1_PT5906
,2015-11-19 10:02:16.760 ThaliTest[922:604623] server relay: connected (to port: 54899)
2015-11-19 10:02:16.759 ThaliTest[922:605685] server session: connected
2015-11-19 10:02:16.762 ThaliTest[922:605685] server session: stateChange:1->2 Apple-IpadAir2-1_PT4426
,TCP/IP server connected
,2015-11-19 10:02:16.799 ThaliTest[922:604623] server relay: connected (to port: 54899)
,TCP/IP server connected
,TCP/IP server has received 2190 bytes of data
,TCP/IP server has received 8760 bytes of data
,TCP/IP server has received 41610 bytes of data
,TCP/IP server has received 72270 bytes of data
,TCP/IP server has received 98408 bytes of data
,TCP/IP server has received 118260 bytes of data
,TCP/IP server has received 135780 bytes of data
,TCP/IP server has received 153300 bytes of data
,TCP/IP server has received 181770 bytes of data
,TCP/IP server has received 212430 bytes of data
,TCP/IP server has received 240900 bytes of data
,TCP/IP server has received 269370 bytes of data
,TCP/IP server has received 280320 bytes of data
,TCP/IP server has received 302220 bytes of data
,TCP/IP server has received 328500 bytes of data
,TCP/IP server has received 332880 bytes of data
,TCP/IP server has received 335070 bytes of data
,TCP/IP server has received 343830 bytes of data
,TCP/IP server has received 363540 bytes of data
,TCP/IP server has received 370110 bytes of data
,TCP/IP server has received 21900 bytes of data
,TCP/IP server has received 392010 bytes of data
,TCP/IP server has received 52560 bytes of data
,TCP/IP server has received 402960 bytes of data
,TCP/IP server has received 140160 bytes of data
,TCP/IP server has received 418290 bytes of data
,TCP/IP server has received 175200 bytes of data
,TCP/IP server has received 457710 bytes of data
,TCP/IP server has received 481800 bytes of data
,TCP/IP server has received 179580 bytes of data
,TCP/IP server has received 205860 bytes of data
,TCP/IP server has received 227760 bytes of data
,TCP/IP server has received 488370 bytes of data
,TCP/IP server has received 521220 bytes of data
,TCP/IP server has received 569400 bytes of data
,TCP/IP server has received 573780 bytes of data
,TCP/IP server has received 580208 bytes of data
TCP/IP server has received 256230 bytes of data
,TCP/IP server has received 584730 bytes of data
TCP/IP server has received 312886 bytes of data
,TCP/IP server has received 317550 bytes of data
,TCP/IP server has received 589110 bytes of data
,TCP/IP server has received 602250 bytes of data
,TCP/IP server has received 626340 bytes of data
,TCP/IP server has received 641670 bytes of data
,TCP/IP server has received 321788 bytes of data
,TCP/IP server has received 359160 bytes of data
,TCP/IP server has received 374490 bytes of data
,TCP/IP server has received 409530 bytes of data
,TCP/IP server has received 440190 bytes of data
,TCP/IP server has received 643860 bytes of data
,TCP/IP server has received 672046 bytes of data
,TCP/IP server has received 709560 bytes of data
,TCP/IP server has received 722700 bytes of data
,TCP/IP server has received 455520 bytes of data
,TCP/IP server has received 738030 bytes of data
,TCP/IP server has received 481800 bytes of data
,TCP/IP server has received 740220 bytes of data
,TCP/IP server has received 490560 bytes of data
,TCP/IP server has received 764310 bytes of data
,TCP/IP server has received 505890 bytes of data
,TCP/IP server has received 792780 bytes of data
,TCP/IP server has received 519030 bytes of data
,TCP/IP server has received 810300 bytes of data
,TCP/IP server has received 543120 bytes of data
,TCP/IP server has received 595680 bytes of data
,TCP/IP server has received 643860 bytes of data
,TCP/IP server has received 819060 bytes of data
,TCP/IP server has received 646050 bytes of data
,TCP/IP server has received 862860 bytes of data
,TCP/IP server has received 661380 bytes of data
,TCP/IP server has received 886950 bytes of data
,TCP/IP server has received 685470 bytes of data
,TCP/IP server has received 713940 bytes of data
,TCP/IP server has received 891330 bytes of data
,TCP/IP server has received 926370 bytes of data
,TCP/IP server has received 957030 bytes of data
,TCP/IP server has received 976740 bytes of data
,TCP/IP server has received 983310 bytes of data
TCP/IP server has received 733650 bytes of data
,TCP/IP server has received 996450 bytes of data
TCP/IP server has received 759930 bytes of data
,TCP/IP server has received 1000002 bytes of data
,TCP/IP server has received 783878 bytes of data
,TCP/IP server has received 816870 bytes of data
,TCP/IP server has received 845340 bytes of data
,TCP/IP server has received 862860 bytes of data
,TCP/IP server has received 876000 bytes of data
,TCP/IP server has received 882570 bytes of data
,TCP/IP server has received 908850 bytes of data
,TCP/IP server has received 930750 bytes of data
,TCP/IP server has received 941700 bytes of data
,TCP/IP server has received 950318 bytes of data
,TCP/IP server has received 972360 bytes of data
,TCP/IP server has received 996450 bytes of data
,TCP/IP server has received 1000002 bytes of data
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:02:26.344 ThaliTest[922:604623] client: socket closed
2015-11-19 10:02:26.345 ThaliTest[922:604623] client relay: socket disconnected
----------------- closeClientSocket
2015-11-19 10:02:26.345 ThaliTest[922:604623,] client relay: 0x1c74bcd0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x17d9dcd0 {NSLocalizedDescription=Socket closed by remote peer} 
CLIENT is closed
2015-11-19 10:02:26.346 ThaliTest[,922:604623] client session: socket closed: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:02:26.346 ThaliTest[922:604623] client session: onLinkFailure: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:02:26.348 ThaliTest[922:604623] client session: disconnect
,2015-11-19 10:02:26.349 ThaliTest[922:604623] client session: stateChange:2->0 Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:02:26.350 ThaliTest[922:604623] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:02:28.799 ThaliTest[922:605685] server session: not connected Apple-IpadAir2-1_PT4426
,2015-11-19 10:02:29.130 ThaliTest[922:605685] server session: not connected Apple-Iphone5s-1_PT5906
,re-try now : Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:02:36.352 ThaliTest[922:604776] jxcore: disconnect
2015-11-19 10:02:36.353 ThaliTest[922:604776] jxcore: disconnect: fail
Connect (retry count 1) to peer Apple-IpadAir2-1_PT4426.kvRdCA== with availability status: true
do connect now
,2015-11-19 10:02:36.355 ThaliTest[922:604776] jxcore: connect Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:02:36.356 ThaliTest[922:604776] client session: connect
2015-11-19 10:02:36.356 ThaliTest[922:604776] client session: stateChange:0->1 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:02:38.938 ThaliTest[922:604623] multipeer session: reset timer
2015-11-19 10:02:38.939 ThaliTest[922:604623] multipeer session: stop timer
2015-11-19 10:02:38.940 ThaliTest[922:604623] multipeer session: start timer: 0x1c7431d0
2015-11-19 ,10:02:38.940 ThaliTest[922:604623] server: disconnecting to refresh session (Apple-IpadAir2-1_PT4426)
2015-11-19 10:02:38.941 ThaliTest[922:604623] server session: disconnect
2015-11-19 10:02:38.941 ThaliTest[922:604623] server session: stateChange:2->0 ,Apple-IpadAir2-1_PT4426
2015-11-19 10:02:38.944 ThaliTest[922:604623] server session: connect
2015-11-19 10:02:38.945 ThaliTest[922:604623] server session: stateChange:0->1 Apple-IpadAir2-1_PT4426
TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:02:38.964 ThaliTest[922:604623] server: accepting invitation Apple-IpadAir2-1_PT4426
,2015-11-19 10:02:39.102 ThaliTest[922:604623] multipeer session: reset timer
2015-11-19 10:02:39.103 ThaliTest[922:604623] multipeer session: stop timer
2015-11-19 10:02:39.104 ThaliTest[922:604623] multipeer session: start timer: 0x1c7431d0
2015-11-19 ,10:02:39.104 ThaliTest[922:604623] server: disconnecting to refresh session (Apple-Iphone5s-1_PT5906)
2015-11-19 10:02:39.105 ThaliTest[922:604623] server session: disconnect
2015-11-19 10:02:39.105 ThaliTest[922:604623] server session: stateChange:2->0 ,Apple-Iphone5s-1_PT5906
2015-11-19 10:02:39.108 ThaliTest[922:604623] server session: connect
TCP/IP server is ended
TCP/IP server is close
2015-11-19 10:02:39.109 ThaliTest[922:604623] server session: stateChange:0->1 Apple-Iphone5s-1_PT5906
,2015-11-19 10:02:39.125 ThaliTest[922:604623] server: accepting invitation Apple-Iphone5s-1_PT5906
,2015-11-19 10:02:39.551 ThaliTest[922:605751] client session: connected
2015-11-19 10:02:39.552 ThaliTest[922:605751] client session: stateChange:1->2 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:02:39.560 ThaliTest[922:605758] client session: fireConnectCallback: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:02:39.561 ThaliTest[922:605758] jxcore: connect: success
CLIENT connected to 54907, error: null
,CLIENT starting client 
,2015-11-19 10:02:39.565 ThaliTest[922:604623] client: relay established
2015-11-19 10:02:39.566 ThaliTest[922:604623] client: new accepted socket: 0x1c6912b0
,CLIENT now sending 980000 bytes of data
,CLIENT is data received : 20000
,CLIENT is data received : 20000
,CLIENT is data received : 20000
,CLIENT is data received : 20000
,CLIENT is data received : 30000
,2015-11-19 10:02:41.468 ThaliTest[922:605758] server session: connected
2015-11-19 10:02:41.469 ThaliTest[922:605758] server session: stateChange:1->2 Apple-Iphone5s-1_PT5906
,2015-11-19 10:02:41.474 ThaliTest[922:604623] server relay: connected (to port: 54899)
,TCP/IP server connected
,2015-11-19 10:02:41.514 ThaliTest[922:605755] server session: connected
2015-11-19 10:02:41.514 ThaliTest[922:605755] server session: stateChange:1->2 Apple-IpadAir2-1_PT4426
,2015-11-19 10:02:41.522 ThaliTest[922:604623] server relay: connected (to port: 54899)
,TCP/IP server connected
,TCP/IP server has received 15330 bytes of data
,TCP/IP server has received 37230 bytes of data
,TCP/IP server has received 4380 bytes of data
,TCP/IP server has received 54750 bytes of data
TCP/IP server has received 24090 bytes of data
,TCP/IP server has received 94170 bytes of data
,TCP/IP server has received 122640 bytes of data
,TCP/IP server has received 166440 bytes of data
,TCP/IP server has received 177390 bytes of data
,TCP/IP server has received 96360 bytes of data
,TCP/IP server has received 144540 bytes of data
,TCP/IP server has received 164250 bytes of data
,TCP/IP server has received 192720 bytes of data
,TCP/IP server has received 229950 bytes of data
,TCP/IP server has received 267180 bytes of data
,TCP/IP server has received 273750 bytes of data
,TCP/IP server has received 278130 bytes of data
,TCP/IP server has received 304410 bytes of data
,TCP/IP server has received 308790 bytes of data
,TCP/IP server has received 173010 bytes of data
,TCP/IP server has received 201480 bytes of data
,TCP/IP server has received 214620 bytes of data
,TCP/IP server has received 249660 bytes of data
,TCP/IP server has received 264990 bytes of data
,TCP/IP server has received 267180 bytes of data
,TCP/IP server has received 361350 bytes of data
,TCP/IP server has received 273750 bytes of data
,TCP/IP server has received 448950 bytes of data
,TCP/IP server has received 304410 bytes of data
,TCP/IP server has received 453330 bytes of data
,TCP/IP server has received 339450 bytes of data
,TCP/IP server has received 369542 bytes of data
,TCP/IP server has received 470850 bytes of data
,TCP/IP server has received 400770 bytes of data
TCP/IP server has received 475230 bytes of data
,TCP/IP server has received 418290 bytes of data
,TCP/IP server has received 420480 bytes of data
,TCP/IP server has received 483990 bytes of data
,TCP/IP server has received 490560 bytes of data
,TCP/IP server has received 501510 bytes of data
,TCP/IP server has received 446760 bytes of data
,TCP/IP server has received 527790 bytes of data
,TCP/IP server has received 543120 bytes of data
,TCP/IP server has received 468660 bytes of data
,TCP/IP server has received 556260 bytes of data
,TCP/IP server has received 483990 bytes of data
,TCP/IP server has received 573780 bytes of data
,TCP/IP server has received 503700 bytes of data
,TCP/IP server has received 589110 bytes of data
,TCP/IP server has received 525600 bytes of data
,TCP/IP server has received 639480 bytes of data
,TCP/IP server has received 547500 bytes of data
,TCP/IP server has received 595680 bytes of data
,TCP/IP server has received 632910 bytes of data
,TCP/IP server has received 663570 bytes of data
,TCP/IP server has received 665760 bytes of data
,TCP/IP server has received 713940 bytes of data
,TCP/IP server has received 720510 bytes of data
,TCP/IP server has received 742410 bytes of data
,TCP/IP server has received 748980 bytes of data
,TCP/IP server has received 674520 bytes of data
,TCP/IP server has received 694230 bytes of data
,TCP/IP server has received 764310 bytes of data
,TCP/IP server has received 797160 bytes of data
TCP/IP server has received 731460 bytes of data
,TCP/IP server has received 819060 bytes of data
TCP/IP server has received 753360 bytes of data
,TCP/IP server has received 832200 bytes of data
TCP/IP server has received 778504 bytes of data
,TCP/IP server has received 876000 bytes of data
,TCP/IP server has received 805920 bytes of data
,TCP/IP server has received 913230 bytes of data
,TCP/IP server has received 821250 bytes of data
,TCP/IP server has received 941700 bytes of data
,TCP/IP server has received 854100 bytes of data
,TCP/IP server has received 960002 bytes of data
,TCP/IP server has received 880380 bytes of data
,TCP/IP server has received 919800 bytes of data
,TCP/IP server has received 940002 bytes of data
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,2015-11-19 10:02:51.435 ThaliTest[922:604623] client: socket closed
----------------- closeClientSocket
2015-11-19 10:02:51.436 ThaliTest[922:604623] client relay: socket disconnected
CLIENT is closed
2015-11-19 10:02:51.436 ThaliTest[922:604623] clien,t relay: 0x1c6912b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c651af0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:02:51.437 ThaliTest[922:604623] client session: socket closed: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:02:51.437 ThaliTest[922:604623] client session: onLinkFailure: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:02:51.438 ThaliTest[922:604623] client session: disconnect
,2015-11-19 10:02:51.439 ThaliTest[922:604623] client session: stateChange:2->0 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:02:51.440 ThaliTest[922:604623] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:02:52.848 ThaliTest[922:605748] server session: not connected Apple-IpadAir2-1_PT4426
,2015-11-19 10:02:53.243 ThaliTest[922:605748] server session: not connected Apple-Iphone5s-1_PT5906
,re-try now : Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:01.452 ThaliTest[922:604776] jxcore: disconnect
2015-11-19 10:03:01.453 ThaliTest[922:604776] jxcore: disconnect: fail
Connect (retry count 2) to peer Apple-IpadAir2-1_PT4426.kvRdCA== with availability status: true
do connect now
,2015-11-19 10:03:01.454 ThaliTest[922:604776] jxcore: connect Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:01.455 ThaliTest[922:604776] client session: connect
,2015-11-19 10:03:01.456 ThaliTest[922:604776] client session: stateChange:0->1 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:02.961 ThaliTest[922:604623] multipeer session: reset timer
2015-11-19 10:03:02.962 ThaliTest[922:604623] multipeer session: stop timer
2015-11-19 10:03:02.962 ThaliTest[922:604623] multipeer session: start timer: 0x1c7431d0
2015-11-19 ,10:03:02.963 ThaliTest[922:604623] server: disconnecting to refresh session (Apple-IpadAir2-1_PT4426)
2015-11-19 10:03:02.963 ThaliTest[922:604623] server session: disconnect
2015-11-19 10:03:02.964 ThaliTest[922:604623] server session: stateChange:2->0 ,Apple-IpadAir2-1_PT4426
2015-11-19 10:03:02.967 ThaliTest[922:604623] server session: connect
2015-11-19 10:03:02.967 ThaliTest[922:604623] server session: stateChange:0->1 Apple-IpadAir2-1_PT4426
,TCP/IP server is ended
TCP/IP server is close
2015-11-19 10:03:02.984 ThaliTest[922:604623] server: accepting invitation Apple-IpadAir2-1_PT4426
,2015-11-19 10:03:03.234 ThaliTest[922:604623] multipeer session: reset timer
2015-11-19 10:03:03.234 ThaliTest[922:604623] multipeer session: stop timer
2015-11-19 10:03:03.235 ThaliTest[922:604623] multipeer session: start timer: 0x1c7431d0
2015-11-19 ,10:03:03.235 ThaliTest[922:604623] server: disconnecting to refresh session (Apple-Iphone5s-1_PT5906)
2015-11-19 10:03:03.236 ThaliTest[922:604623] server session: disconnect
2015-11-19 10:03:03.236 ThaliTest[922:604623] server session: stateChange:2->0 ,Apple-Iphone5s-1_PT5906
2015-11-19 10:03:03.240 ThaliTest[922:604623] server session: connect
TCP/IP server is ended
TCP/IP server is close
2015-11-19 10:03:03.240 ThaliTest[922:604623] server session: stateChange:0->1 Apple-Iphone5s-1_PT5906
2015-11-,19 10:03:03.254 ThaliTest[922:604623] server: accepting invitation Apple-Iphone5s-1_PT5906
,2015-11-19 10:03:04.683 ThaliTest[922:605758] client session: connected
2015-11-19 10:03:04.684 ThaliTest[922:605758] client session: stateChange:1->2 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:04.708 ThaliTest[922:605812] client session: fireConnectCallback: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:03:04.708 ThaliTest[922:605812] jxcore: connect: success
CLIENT connected to 54912, error: null
CLIENT starting client 
,2015-11-19 10:03:04.713 ThaliTest[922:604623] client: relay established
2015-11-19 10:03:04.713 ThaliTest[922:604623] client: new accepted socket: 0x17d321c0
,CLIENT now sending 970000 bytes of data
,CLIENT is data received : 30000
,2015-11-19 10:03:05.517 ThaliTest[922:605751] server session: connected
2015-11-19 10:03:05.517 ThaliTest[922:605751] server session: stateChange:1->2 Apple-Iphone5s-1_PT5906
,TCP/IP server connected
,2015-11-19 10:03:05.557 ThaliTest[922:605751] server session: connected
2015-11-19 10:03:05.557 ThaliTest[922:605751] server session: stateChange:1->2 Apple-IpadAir2-1_PT4426
,TCP/IP server connected
,2015-11-19 10:03:05.788 ThaliTest[922:604623] server relay: connected (to port: 54899)
2015-11-19 10:03:05.788 ThaliTest[922:604623] server relay: connected (to port: 54899)
CLIENT is data received : 40000
,TCP/IP server has received 15330 bytes of data
,TCP/IP server has received 41610 bytes of data
,TCP/IP server has received 67890 bytes of data
,TCP/IP server has received 89790 bytes of data
,TCP/IP server has received 116070 bytes of data
TCP/IP server has received 157538 bytes of data
,TCP/IP server has received 175200 bytes of data
TCP/IP server has received 6570 bytes of data
,TCP/IP server has received 192720 bytes of data
TCP/IP server has received 30660 bytes of data
,TCP/IP server has received 223380 bytes of data
TCP/IP server has received 52134 bytes of data
,TCP/IP server has received 236520 bytes of data
,TCP/IP server has received 91980 bytes of data
,TCP/IP server has received 240900 bytes of data
,TCP/IP server has received 146730 bytes of data
,TCP/IP server has received 267038 bytes of data
,TCP/IP server has received 291270 bytes of data
,TCP/IP server has received 164250 bytes of data
,TCP/IP server has received 313170 bytes of data
,TCP/IP server has received 201480 bytes of data
,TCP/IP server has received 346020 bytes of data
,TCP/IP server has received 286890 bytes of data
,TCP/IP server has received 387630 bytes of data
,TCP/IP server has received 396390 bytes of data
,TCP/IP server has received 416100 bytes of data
,TCP/IP server has received 310980 bytes of data
,TCP/IP server has received 369684 bytes of data
,TCP/IP server has received 418290 bytes of data
,TCP/IP server has received 392010 bytes of data
,TCP/IP server has received 444570 bytes of data
,TCP/IP server has received 448950 bytes of data
,TCP/IP server has received 464280 bytes of data
,TCP/IP server has received 490560 bytes of data
,TCP/IP server has received 523410 bytes of data
,TCP/IP server has received 569400 bytes of data
,TCP/IP server has received 591300 bytes of data
,TCP/IP server has received 444570 bytes of data
,TCP/IP server has received 497130 bytes of data
,TCP/IP server has received 595680 bytes of data
,TCP/IP server has received 538740 bytes of data
,TCP/IP server has received 621960 bytes of data
,TCP/IP server has received 578160 bytes of data
,TCP/IP server has received 641670 bytes of data
,TCP/IP server has received 595680 bytes of data
,TCP/IP server has received 685470 bytes of data
,TCP/IP server has received 733650 bytes of data
,TCP/IP server has received 768690 bytes of data
,TCP/IP server has received 632910 bytes of data
,TCP/IP server has received 681090 bytes of data
,CLIENT is data received : 50000
,TCP/IP server has received 779640 bytes of data
,TCP/IP server has received 692040 bytes of data
,TCP/IP server has received 706802 bytes of data
TCP/IP server has received 790590 bytes of data
,CLIENT is data received : 60000
,TCP/IP server has received 727080 bytes of data
TCP/IP server has received 821250 bytes of data
,TCP/IP server has received 738030 bytes of data
TCP/IP server has received 867240 bytes of data
,TCP/IP server has received 744600 bytes of data
TCP/IP server has received 876000 bytes of data
,TCP/IP server has received 764310 bytes of data
,TCP/IP server has received 900002 bytes of data
,TCP/IP server has received 777450 bytes of data
,TCP/IP server has received 790590 bytes of data
,TCP/IP server has received 799350 bytes of data
,CLIENT is data received : 60000
TCP/IP server has received 810300 bytes of data
,CLIENT is data received : 60000
TCP/IP server has received 856290 bytes of data
,TCP/IP server has received 884760 bytes of data
,TCP/IP server has received 897900 bytes of data
,TCP/IP server has received 937320 bytes of data
,TCP/IP server has received 950002 bytes of data
,2015-11-19 10:03:12.680 ThaliTest[922:604623] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,----------------- closeClientSocket
,2015-11-19 10:03:16.602 ThaliTest[922:604623] client: socket closed
CLIENT is closed
,2015-11-19 10:03:16.604 ThaliTest[922:604623] client relay: socket disconnected
2015-11-19 10:03:16.605 ThaliTest[922:604623] client relay: 0x17d321c0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" Use,rInfo=0x17e2da00 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:03:16.605 ThaliTest[922:604623] client session: socket closed: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:03:16.606 ThaliTest[922:604623] client session: onLinkFail,ure: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:03:16.606 ThaliTest[922:604623] client session: disconnect
2015-11-19 10:03:16.607 ThaliTest[922:604623] client session: stateChange:2->0 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:16.609 ThaliTest[922:604623] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:16.832 ThaliTest[922:605802] server session: not connected Apple-Iphone5s-1_PT5906
2015-11-19 10:03:16.835 ThaliTest[922:605802] server session: not connected Apple-IpadAir2-1_PT4426
,2015-11-19 10:03:17.882 ThaliTest[922:604623] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,re-try now : Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:26.616 ThaliTest[922:604776] jxcore: disconnect
2015-11-19 10:03:26.617 ThaliTest[922:604776] jxcore: disconnect: fail
Connect (retry count 3) to peer Apple-IpadAir2-1_PT4426.kvRdCA== with availability status: true
do connect now
,2015-11-19 10:03:26.619 ThaliTest[922:604776] jxcore: connect Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:26.620 ThaliTest[922:604776] client session: connect
2015-11-19 10:03:26.621 ThaliTest[922:604776] client session: stateChange:0->1 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:26.974 ThaliTest[922:604623] multipeer session: reset timer
2015-11-19 10:03:26.974 ThaliTest[922:604623] multipeer session: stop timer
2015-11-19 10:03:26.975 ThaliTest[922:604623] multipeer session: start timer: 0x1c7431d0
2015-11-19 ,10:03:26.975 ThaliTest[922:604623] server: disconnecting to refresh session (Apple-IpadAir2-1_PT4426)
2015-11-19 10:03:26.976 ThaliTest[922:604623] server session: disconnect
2015-11-19 10:03:26.976 ThaliTest[922:604623] server session: stateChange:2->0 Apple-IpadAir2-1_PT4426
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:03:27.039 ThaliTest[922:604623] server session: connect
2015-11-19 10:03:27.040 ThaliTest[922:604623] server session: stateChange:0->1 Apple-IpadAir2-1_PT4426
,2015-11-19 10:03:27.045 ThaliTest[922:604623] server: accepting invitation Apple-IpadAir2-1_PT4426
,2015-11-19 10:03:29.879 ThaliTest[922:605860] server session: connected
2015-11-19 10:03:29.880 ThaliTest[922:605860] server session: stateChange:1->2 Apple-IpadAir2-1_PT4426
,2015-11-19 10:03:29.920 ThaliTest[922:604623] server relay: connected (to port: 54899)
,TCP/IP server connected
,2015-11-19 10:03:30.006 ThaliTest[922:604623] multipeer session: reset timer
2015-11-19 10:03:30.007 ThaliTest[922:604623] multipeer session: stop timer
2015-11-19 10:03:30.007 ThaliTest[922:604623] multipeer session: start timer: 0x1c7431d0
2015-11-19 ,10:03:30.008 ThaliTest[922:604623] server: disconnecting to refresh session (Apple-Iphone5s-1_PT5906)
2015-11-19 10:03:30.009 ThaliTest[922:604623] server session: disconnect
2015-11-19 10:03:30.009 ThaliTest[922:604623] server session: stateChange:2->0 ,Apple-Iphone5s-1_PT5906
,TCP/IP server is ended
,TCP/IP server is close
,2015-11-19 10:03:30.067 ThaliTest[922:604623] server session: connect
2015-11-19 10:03:30.068 ThaliTest[922:604623] server session: stateChange:0->1 Apple-Iphone5s-1_PT5906
,2015-11-19 10:03:30.074 ThaliTest[922:604623] server: accepting invitation Apple-Iphone5s-1_PT5906
,TCP/IP server has received 4380 bytes of data
,TCP/IP server has received 24090 bytes of data
,TCP/IP server has received 56940 bytes of data
,TCP/IP server has received 89790 bytes of data
,TCP/IP server has received 124830 bytes of data
,TCP/IP server has received 129210 bytes of data
,2015-11-19 10:03:30.408 ThaliTest[922:605865] client session: connected
,2015-11-19 10:03:30.411 ThaliTest[922:605865] client session: stateChange:1->2 Apple-IpadAir2-1_PT4426.kvRdCA==
,TCP/IP server has received 144540 bytes of data
,TCP/IP server has received 186150 bytes of data
,2015-11-19 10:03:30.441 ThaliTest[922:605865] client session: fireConnectCallback: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:03:30.442 ThaliTest[922:605865] jxcore: connect: success
TCP/IP server has received 201480 bytes of data
CLIENT connected to 54918, error: null
CLIENT starting client 
,2015-11-19 10:03:30.448 ThaliTest[922:604623] client: relay established
2015-11-19 10:03:30.449 ThaliTest[922:604623] client: new accepted socket: 0x17d84510
,TCP/IP server has received 225570 bytes of data
,CLIENT now sending 940000 bytes of data
,TCP/IP server has received 356642 bytes of data
,TCP/IP server has received 487714 bytes of data
,TCP/IP server has received 618786 bytes of data
,TCP/IP server has received 749858 bytes of data
,TCP/IP server has received 880930 bytes of data
,TCP/IP server has received 940002 bytes of data
,CLIENT is data received : 60000
,CLIENT is data received : 60000
,CLIENT is data received : 60000
,CLIENT is data received : 70000
,CLIENT is data received : 80000
,CLIENT is data received : 80000
,CLIENT is data received : 90000
,2015-11-19 10:03:32.204 ThaliTest[922:605868] server session: connected
2015-11-19 10:03:32.205 ThaliTest[922:605868] server session: stateChange:1->2 Apple-Iphone5s-1_PT5906
,2015-11-19 10:03:32.252 ThaliTest[922:604623] server relay: connected (to port: 54899)
,TCP/IP server connected
,TCP/IP server has received 15330 bytes of data
,TCP/IP server has received 39420 bytes of data
,TCP/IP server has received 69938 bytes of data
,TCP/IP server has received 94028 bytes of data
,TCP/IP server has received 113880 bytes of data
,TCP/IP server has received 129210 bytes of data
,TCP/IP server has received 146730 bytes of data
,TCP/IP server has received 168630 bytes of data
,TCP/IP server has received 197100 bytes of data
,TCP/IP server has received 238710 bytes of data
,TCP/IP server has received 256230 bytes of data
,TCP/IP server has received 282510 bytes of data
,TCP/IP server has received 313170 bytes of data
,TCP/IP server has received 356970 bytes of data
,TCP/IP server has received 396390 bytes of data
,TCP/IP server has received 442380 bytes of data
,TCP/IP server has received 490418 bytes of data
,TCP/IP server has received 545310 bytes of data
,TCP/IP server has received 584730 bytes of data
,TCP/IP server has received 630720 bytes of data
,TCP/IP server has received 635100 bytes of data
,TCP/IP server has received 702990 bytes of data
,TCP/IP server has received 727080 bytes of data
,TCP/IP server has received 742410 bytes of data
,TCP/IP server has received 751170 bytes of data
,TCP/IP server has received 781830 bytes of data
,TCP/IP server has received 816870 bytes of data
,TCP/IP server has received 862860 bytes of data
,TCP/IP server has received 880002 bytes of data
,2015-11-19 10:03:41.522 ThaliTest[922:605868] server session: not connected Apple-IpadAir2-1_PT4426
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
----------------- closeClientSocket
2015-11-19 10:03:41.830 ThaliTest[922:604623] client: socket closed
,CLIENT is closed
2015-11-19 10:03:41.831 ThaliTest[922:604623] client relay: socket disconnected
2015-11-19 10:03:41.833 ThaliTest[922:604623] client relay: 0x17d84510 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed b,y remote peer" UserInfo=0x1c72d8e0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:03:41.833 ThaliTest[922:604623] client session: socket closed: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:03:41.834 ThaliTest[922:604623] client s,ession: onLinkFailure: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:03:41.834 ThaliTest[922:604623] client session: disconnect
2015-11-19 10:03:41.835 ThaliTest[922:604623] client session: stateChange:2->0 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:41.836 ThaliTest[922:604623] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:43.609 ThaliTest[922:605860] server session: not connected Apple-Iphone5s-1_PT5906
,re-try now : Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:51.854 ThaliTest[922:604776] jxcore: disconnect
2015-11-19 10:03:51.854 ThaliTest[922:604776] jxcore: disconnect: fail
Connect (retry count 4) to peer Apple-IpadAir2-1_PT4426.kvRdCA== with availability status: true
do connect now
,2015-11-19 10:03:51.856 ThaliTest[922:604776] jxcore: connect Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:03:51.858 ThaliTest[922:604776] client session: connect
2015-11-19 10:03:51.858 ThaliTest[922:604776] client session: stateChange:0->1 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:53.325 ThaliTest[922:604623] multipeer session: reset timer
2015-11-19 10:03:53.326 ThaliTest[922:604623] multipeer session: stop timer
2015-11-19 10:03:53.326 ThaliTest[922:604623] multipeer session: start timer: 0x1c7431d0
2015-11-19 ,10:03:53.326 ThaliTest[922:604623] server: disconnecting to refresh session (Apple-IpadAir2-1_PT4426)
2015-11-19 10:03:53.326 ThaliTest[922:604623] server session: disconnect
2015-11-19 10:03:53.326 ThaliTest[922:604623] server session: stateChange:2->0 Apple-IpadAir2-1_PT4426
2015-11-19 10:03:53.327 ThaliTest[922:604623] server session: connect
2015-11-19 10:03:53.328 ThaliTest[922:604623] server session: stateChange:0->1 Apple-IpadAir2-1_PT4426
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:03:53.331 ThaliTest[922:604623] server: accepting invitation Apple-IpadAir2-1_PT4426
,2015-11-19 10:03:54.648 ThaliTest[922:604623] multipeer session: reset timer
2015-11-19 10:03:54.649 ThaliTest[922:604623] multipeer session: stop timer
2015-11-19 10:03:54.649 ThaliTest[922:604623] multipeer session: start timer: 0x1c7431d0
2015-11-19 ,10:03:54.650 ThaliTest[922:604623] server: disconnecting to refresh session (Apple-Iphone5s-1_PT5906)
2015-11-19 10:03:54.651 ThaliTest[922:604623] server session: disconnect
2015-11-19 10:03:54.651 ThaliTest[922:604623] server session: stateChange:2->0 ,Apple-Iphone5s-1_PT5906
2015-11-19 10:03:54.655 ThaliTest[922:604623] server session: connect
2015-11-19 10:03:54.655 ThaliTest[922:604623] server session: stateChange:0->1 Apple-Iphone5s-1_PT5906
,TCP/IP server is ended
TCP/IP server is close
2015-11-19 10:03:54.673 ThaliTest[922:604623] server: accepting invitation Apple-Iphone5s-1_PT5906
,2015-11-19 10:03:55.726 ThaliTest[922:605860] client session: connected
2015-11-19 10:03:55.727 ThaliTest[922:605860] client session: stateChange:1->2 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:03:55.732 ThaliTest[922:605925] client session: fireConnectCallback: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:03:55.733 ThaliTest[922:605925] jxcore: connect: success
CLIENT connected to 54922, error: null
CLIENT starting client 
,2015-11-19 10:03:55.738 ThaliTest[922:604623] client: relay established
2015-11-19 10:03:55.739 ThaliTest[922:604623] client: new accepted socket: 0x1c741020
,CLIENT now sending 910000 bytes of data
,2015-11-19 10:03:55.894 ThaliTest[922:605925] server session: connected
2015-11-19 10:03:55.894 ThaliTest[922:605925] server session: stateChange:1->2 Apple-IpadAir2-1_PT4426
,2015-11-19 10:03:55.901 ThaliTest[922:604623] server relay: connected (to port: 54899)
,TCP/IP server connected
,TCP/IP server has received 4380 bytes of data
,TCP/IP server has received 72270 bytes of data
,TCP/IP server has received 137970 bytes of data
,TCP/IP server has received 208050 bytes of data
,TCP/IP server has received 260610 bytes of data
,TCP/IP server has received 308790 bytes of data
,TCP/IP server has received 356970 bytes of data
,TCP/IP server has received 405150 bytes of data
,TCP/IP server has received 455378 bytes of data
,TCP/IP server has received 494940 bytes of data
,TCP/IP server has received 512460 bytes of data
,TCP/IP server has received 562830 bytes of data
,TCP/IP server has received 626340 bytes of data
,CLIENT is data received : 100000
,TCP/IP server has received 692040 bytes of data
,CLIENT is data received : 110000
,TCP/IP server has received 753360 bytes of data
,TCP/IP server has received 814680 bytes of data
,CLIENT is data received : 110000
,TCP/IP server has received 879670 bytes of data
,TCP/IP server has received 930002 bytes of data
,2015-11-19 10:03:56.743 ThaliTest[922:605925] server session: connected
2015-11-19 10:03:56.743 ThaliTest[922:605925] server session: stateChange:1->2 Apple-Iphone5s-1_PT5906
,2015-11-19 10:03:56.747 ThaliTest[922:604623] server relay: connected (to port: 54899)
,TCP/IP server connected
,TCP/IP server has received 4380 bytes of data
,TCP/IP server has received 32850 bytes of data
,TCP/IP server has received 56940 bytes of data
,TCP/IP server has received 98550 bytes of data
,TCP/IP server has received 122640 bytes of data
,TCP/IP server has received 153300 bytes of data
,TCP/IP server has received 173010 bytes of data
,TCP/IP server has received 208050 bytes of data
,TCP/IP server has received 238710 bytes of data
,TCP/IP server has received 267180 bytes of data
,TCP/IP server has received 302220 bytes of data
,TCP/IP server has received 335070 bytes of data
,TCP/IP server has received 354780 bytes of data
,TCP/IP server has received 378870 bytes of data
,TCP/IP server has received 424860 bytes of data
,TCP/IP server has received 453330 bytes of data
,TCP/IP server has received 494940 bytes of data
,TCP/IP server has received 529980 bytes of data
,TCP/IP server has received 575970 bytes of data
,TCP/IP server has received 615390 bytes of data
,TCP/IP server has received 650146 bytes of data
,TCP/IP server has received 689850 bytes of data
,TCP/IP server has received 744458 bytes of data
,TCP/IP server has received 797160 bytes of data
,TCP/IP server has received 820002 bytes of data
,Receiving data timeout now
,CLIENT closeClientSocket
,2015-11-19 10:04:06.582 ThaliTest[922:604623] client: socket closed
2015-11-19 10:04:06.583 ThaliTest[922:604623] client relay: socket disconnected
CLIENT Stop now
Stop data retrieving timer
2015-11-19 10:04:06.583 ThaliTest[922:604623] client relay: 0,x1c741020 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x17eed970 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:04:06.584 ThaliTest[922:604623] client session: socket ,closed: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:04:06.584 ThaliTest[922:604623] client session: onLinkFailure: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:04:06.585 ThaliTest[922:604623] client session: disconnect
CLIENT Stop now
2015-11-19 1,0:04:06.585 ThaliTest[922:604623] client session: stateChange:2->0 Apple-IpadAir2-1_PT4426.kvRdCA==
---- round done--------
device[2]: Apple-Iphone5s-1_PT5906.NMJf0A==
,----------------- closeClientSocket
CLIENT is closed
,2015-11-19 10:04:06.587 ThaliTest[922:604623] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:04:06.691 ThaliTest[922:605946] server session: not connected Apple-IpadAir2-1_PT4426
,2015-11-19 10:04:07.740 ThaliTest[922:605946] server session: not connected Apple-Iphone5s-1_PT5906
,2015-11-19 10:04:11.597 ThaliTest[922:604776] jxcore: disconnect
2015-11-19 10:04:11.597 ThaliTest[922:604776] jxcore: disconnect: fail
Connect (retry count 0) to peer Apple-Iphone5s-1_PT5906.NMJf0A== with availability status: true
do connect now
,2015-11-19 10:04:11.599 ThaliTest[922:604776] jxcore: connect Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:11.600 ThaliTest[922:604776] client session: connect
,2015-11-19 10:04:11.601 ThaliTest[922:604776] client session: stateChange:0->1 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:04:24.650 ThaliTest[922:604623] multipeer session: restart
,2015-11-19 10:04:24.671 ThaliTest[922:604623] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:24.673 ThaliTest[922:604623] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:04:44.608 ThaliTest[922:606016] client session: not connected Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:44.609 ThaliTest[922:606016] client session: onLinkFailure: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:44.609 ThaliTest[9,22:606016] client session: disconnect
2015-11-19 10:04:44.610 ThaliTest[922:606016] client session: stateChange:1->0 Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:44.610 ThaliTest[922:606016] client session: fireConnectCallback: Apple-Iphone5s-1_PT59,06.NMJf0A==
2015-11-19 10:04:44.611 ThaliTest[922:606016] jxcore: connect: fail: Peer disconnected
,CLIENT connected to 0, error: Peer disconnected
CLIENT Can not Connect: Peer disconnected
tryAgain afer: 5000 ms.
,re-try now : Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:04:54.627 ThaliTest[922:604776] jxcore: disconnect
2015-11-19 10:04:54.628 ThaliTest[922:604776] jxcore: disconnect: fail
Connect (retry count 1) to peer Apple-Iphone5s-1_PT5906.NMJf0A== with availability status: true
do connect now
,2015-11-19 10:04:54.629 ThaliTest[922:604776] jxcore: connect Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:54.630 ThaliTest[922:604776] client session: connect
,2015-11-19 10:04:54.630 ThaliTest[922:604776] client session: stateChange:0->1 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:04:54.649 ThaliTest[922:604623] multipeer session: restart
,2015-11-19 10:04:54.670 ThaliTest[922:604623] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:54.671 ThaliTest[922:604623] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:24.649 ThaliTest[922:604623] multipeer session: restart
,2015-11-19 10:05:24.666 ThaliTest[922:604623] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:24.667 ThaliTest[922:604623] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:27.638 ThaliTest[922:606098] client session: not connected Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:27.639 ThaliTest[922:606098] client session: onLinkFailure: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:27.639 ThaliTest[9,22:606098] client session: disconnect
2015-11-19 10:05:27.640 ThaliTest[922:606098] client session: stateChange:1->0 Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:27.641 ThaliTest[922:606098] client session: fireConnectCallback: Apple-Iphone5s-1_PT59,06.NMJf0A==
2015-11-19 10:05:27.641 ThaliTest[922:606098] jxcore: connect: fail: Peer disconnected
,CLIENT connected to 0, error: Peer disconnected
CLIENT Can not Connect: Peer disconnected
tryAgain afer: 5000 ms.
,re-try now : Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:37.657 ThaliTest[922:604776] jxcore: disconnect
2015-11-19 10:05:37.658 ThaliTest[922:604776] jxcore: disconnect: fail
Connect (retry count 2) to peer Apple-Iphone5s-1_PT5906.NMJf0A== with availability status: true
do connect now
,2015-11-19 10:05:37.660 ThaliTest[922:604776] jxcore: connect Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:37.661 ThaliTest[922:604776] client session: connect
2015-11-19 10:05:37.661 ThaliTest[922:604776] client session: stateChange:0->1 Apple-Ipho,ne5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:42.058 ThaliTest[922:606126] client session: connected
2015-11-19 10:05:42.059 ThaliTest[922:606126] client session: stateChange:1->2 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:42.063 ThaliTest[922:606130] client session: fireConnectCallback: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:42.064 ThaliTest[922:606130] jxcore: connect: success
CLIENT connected to 54934, error: null
,CLIENT starting client 
,2015-11-19 10:05:42.070 ThaliTest[922:604623] client: relay established
,2015-11-19 10:05:42.071 ThaliTest[922:604623] client: new accepted socket: 0x1c498760
,CLIENT now sending 1000000 bytes of data
,CLIENT is data received : 0
,CLIENT is data received : 0
,CLIENT is data received : 10000
,CLIENT is data received : 20000
,CLIENT is data received : 30000
,CLIENT is data received : 40000
,CLIENT is data received : 50000
,CLIENT is data received : 60000
,CLIENT is data received : 70000
,CLIENT is data received : 80000
,CLIENT is data received : 90000
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
----------------- closeClientSocket
2015-11-19 10:05:53.378 ThaliTest[922:604623] client: socket closed
CLIENT is closed
,2015-11-19 10:05:53.379 ThaliTest[922:604623] client relay: socket disconnected
2015-11-19 10:05:53.380 ThaliTest[922:604623] client relay: 0x1c498760 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" Use,rInfo=0x17da0ae0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:05:53.381 ThaliTest[922:604623] client session: socket closed: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:53.381 ThaliTest[922:604623] client session: onLinkFail,ure: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:53.382 ThaliTest[922:604623] client session: disconnect
2015-11-19 10:05:53.382 ThaliTest[922:604623] client session: stateChange:2->0 Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:53.384 ThaliT,est[922:604623] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:54.649 ThaliTest[922:604623] multipeer session: restart
,2015-11-19 10:05:54.662 ThaliTest[922:604623] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:54.665 ThaliTest[922:604623] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,re-try now : Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:06:03.391 ThaliTest[922:604776] jxcore: disconnect
2015-11-19 10:06:03.392 ThaliTest[922:604776] jxcore: disconnect: fail
Connect (retry count 3) to peer Apple-Iphone5s-1_PT5906.NMJf0A== with availability status: true
do connect now
,2015-11-19 10:06:03.394 ThaliTest[922:604776] jxcore: connect Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:06:03.394 ThaliTest[922:604776] client session: connect
,2015-11-19 10:06:03.395 ThaliTest[922:604776] client session: stateChange:0->1 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:06:09.490 ThaliTest[922:606130] client session: connected
2015-11-19 10:06:09.492 ThaliTest[922:606130] client session: stateChange:1->2 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:06:09.496 ThaliTest[922:606209] client session: fireConnectCallback: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:06:09.497 ThaliTest[922:606209] jxcore: connect: success
CLIENT connected to 54939, error: null
CLIENT starting client 
,2015-11-19 10:06:09.502 ThaliTest[922:604623] client: relay established
2015-11-19 10:06:09.503 ThaliTest[922:604623] client: new accepted socket: 0x1c5b4c40
,CLIENT now sending 910000 bytes of data
,CLIENT is data received : 90000
,CLIENT is data received : 90000
,CLIENT is data received : 90000
,CLIENT is data received : 100000
,CLIENT is data received : 110000
,CLIENT is data received : 120000
,CLIENT is data received : 130000
,CLIENT is data received : 130000
,CLIENT is data received : 140000
,CLIENT is data received : 150000
,CLIENT is data received : 160000
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
----------------- closeClientSocket
2015-11-19 10:06:20.631 ThaliTest[922:604623] client: socket closed
CLIENT is closed
2015-11-19 10:06:20.632 ThaliTest[922:604623] client relay: socket disconnected
,2015-11-19 10:06:20.632 ThaliTest[922:604623] client relay: 0x1c5b4c40 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c2623f0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:06:20.633 ThaliTest[922:604623] client session: socket closed: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:06:20.633 ThaliTest[922:604623] client session: onLinkFailure: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:06:20.634 ThaliTest[,922:604623] client session: disconnect
,2015-11-19 10:06:20.634 ThaliTest[922:604623] client session: stateChange:2->0 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:06:20.636 ThaliTest[922:604623] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:06:24.647 ThaliTest[922:604623] multipeer session: restart
,2015-11-19 10:06:24.660 ThaliTest[922:604623] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:06:25.072 ThaliTest[922:604623] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,re-try now : Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:06:30.639 ThaliTest[922:604776] jxcore: disconnect
2015-11-19 10:06:30.639 ThaliTest[922:604776] jxcore: disconnect: fail
Connect (retry count 4) to peer Apple-Iphone5s-1_PT5906.NMJf0A== with availability status: true
do connect now
,2015-11-19 10:06:30.641 ThaliTest[922:604776] jxcore: connect Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:06:30.642 ThaliTest[922:604776] client session: connect
2015-11-19 10:06:30.642 ThaliTest[922:604776] client session: stateChange:0->1 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:06:32.959 ThaliTest[922:606229] client session: connected
2015-11-19 10:06:32.959 ThaliTest[922:606229] client session: stateChange:1->2 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:06:32.964 ThaliTest[922:606181] client session: fireConnectCallback: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:06:32.965 ThaliTest[922:606181] jxcore: connect: success
CLIENT connected to 54944, error: null
CLIENT starting client 
,2015-11-19 10:06:32.971 ThaliTest[922:604623] client: relay established
2015-11-19 10:06:32.971 ThaliTest[922:604623] client: new accepted socket: 0x1c5f4b50
,CLIENT now sending 840000 bytes of data
,CLIENT is data received : 160000
,CLIENT is data received : 160000
,CLIENT is data received : 170000
,CLIENT is data received : 180000
,CLIENT is data received : 190000
,CLIENT is data received : 200000
,CLIENT is data received : 210000
,CLIENT is data received : 220000
,CLIENT is data received : 230000
,CLIENT is data received : 240000
,Receiving data timeout now
,CLIENT closeClientSocket
CLIENT Stop now
Stop data retrieving timer
2015-11-19 10:06:44.101 ThaliTest[922:604623] client: socket closed
2015-11-19 10:06:44.101 ThaliTest[922:604623] client relay: socket disconnected
CLIENT Stop now
2015-11-19 10:06:4,4.102 ThaliTest[922:604623] client relay: 0x1c5f4b50 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c753930 {NSLocalizedDescription=Socket closed by remote peer} 
---- round done--------
2,015-11-19 10:06:44.103 ThaliTest[922:604623] client session: socket closed: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:06:44.103 ThaliTest[922:604623] client session: onLinkFailure: Apple-Iphone5s-1_PT5906.NMJf0A==
weAreDoneNow , resultArray.length: ,2
2015-11-19 10:06:44.104 ThaliTest[922:604623] client session: disconnect
2015-11-19 10:06:44.105 ThaliTest[922:604623] client session: stateChange:2->0 Apple-Iphone5s-1_PT5906.NMJf0A==
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT5791","time":278119,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT4426.kvRdCA==","time":119985,"result":"DATA-TIMEOUT","connections":5},{"name":"Apple-Iphone5s-1_PT5906.NMJf0A==","time":157511,"result":"DA,TA-TIMEOUT","connections":5}]}
2015-11-19 10:06:44.113 ThaliTest[922:604623] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5906.NMJf0A==
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results li,st does not contain any items
sendList failed peers count : 2 [100 %]
- Peer ID : Apple-IpadAir2-1_PT4426.kvRdCA==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT5906.NMJf0A==, Tried : 5
sendList never tried peers count : 0 [0 %]
CLIENT Stop now
---------,-------- closeClientSocket
,CLIENT is closed
,2015-11-19 10:06:54.647 ThaliTest[922:604623] multipeer session: restart
,2015-11-19 10:06:54.663 ThaliTest[922:604623] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:06:54.664 ThaliTest[922:604623] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:07:24.647 ThaliTest[922:604623] multipeer session: restart
,2015-11-19 10:07:24.663 ThaliTest[922:604623] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:07:24.665 ThaliTest[922:604623] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:07:54.645 ThaliTest[922:604623] multipeer session: restart
,2015-11-19 10:07:54.661 ThaliTest[922:604623] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:07:54.663 ThaliTest[922:604623] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:08:05.775 ThaliTest[922:604623] client: lost peer: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:08:05.776 ThaliTest[922:604623] client session: onPeerLost: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:08:05.777 ThaliTest[922:604623] cli,ent: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5906.NMJf0A==","pee,rName":"(null)","peerAvailable":true}]
,2015-11-19 10:08:24.645 ThaliTest[922:604623] multipeer session: restart
2015-11-19 10:08:24.652 ThaliTest[922:604623] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** First ,throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x26932607 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0x102693 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of type, NSException
,Process 922 stopped
* thread #1: tid = 0x939cf, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x35e14df0 <+8>:  blo    0x35e14e08                ; <+32>
    0x35e14df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x35e14df8 <+16>: ldr    r12, [pc, r12]
    0x35e14dfc <+20>: b      0x35e14e04                ; <+28>
,* thread #1: tid = 0x939cf, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x00102692 ThaliTest`main + 50

```
