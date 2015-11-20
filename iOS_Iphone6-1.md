#### Test 51335028f10f918_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028f10f918/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3EB749A4-F7C4-4F35-A32E-9D177BD644FD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/3EB749A4-F7C4-4F35-A32E-9D177BD644FD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028f10f918/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028f10f918/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7F236EB1-9C11-4EAD-8B5B-021AC189575A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51481"
,(lldb)     command script import "/tmp/3EB749A4-F7C4-4F35-A32E-9D177BD644FD/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 14:48:00.273 ThaliTest[1074:741160] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A3159FEF-D7F3-4A3A-A3AE-0C4B8D8FE871/Library/Cookies/Cookies.binarycookies
,2015-11-20 14:48:00.620 ThaliTest[1074:741160] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 14:48:00.621 ThaliTest[1074:741160] Multi-tasking -> Device: YES, App: YES
,2015-11-20 14:48:00.629 ThaliTest[1074:741160] Unlimited access to network resources
,2015-11-20 14:48:00.635 ThaliTest[1074:741160] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 14:48:04.243 ThaliTest[1074:741160] Resetting plugins due to page load.
,2015-11-20 14:48:04.591 ThaliTest[1074:741160] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/7F236EB1-9C11-4EAD-8B5B-021AC189575A/ThaliTest.app/www/index.html
,2015-11-20 14:48:04.715 ThaliTest[1074:741160] JXcore Cordova plugin initializing
,2015-11-20 14:48:04.716 ThaliTest[1074:741302] JXcore instance initializing
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
,toggleWiFi
,my name is : Apple-Iphone6-1_PT8294
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
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"10000000\",\"conReTryTimeout\":\"1000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 55855
,2015-11-20 14:57:15.070 ThaliTest[1074:741302] jxcore: startBroadcasting
,2015-11-20 14:57:15.084 ThaliTest[1074:741302] server: starting Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:57:15.089 ThaliTest[1074:741302] multipeer session: start timer: 0x1bea4090
,2015-11-20 14:57:15.098 ThaliTest[1074:741302] THEMultipeerSession initialized peer Apple-Iphone6-1_PT8294
,2015-11-20 14:57:15.099 ThaliTest[1074:741302] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-20T13:57:15.101Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-20 14:57:15.317 ThaliTest[1074:741160] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT738.lFO7fw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T13:57:15.319Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T13:57:15.320Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
2015-,11-20T13:57:15.320Z SendDataConnector.js: do connect now
2015-11-20 14:57:15.320 ThaliTest[1074:741302] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:57:15.320 ThaliTest[1074:741302] client session: connect
,2015-11-20 14:57:15.320 ThaliTest[1074:741302] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:57:15.409 ThaliTest[1074:741160] client: found peer: Apple-IpadAir2-1_PT9530.n+0V8A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9530.n+0V8A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: t,rue
,2015-11-20 14:57:15.540 ThaliTest[1074:741160] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 14:57:17.853 ThaliTest[1074:742025] client session: connected
2015-11-20 14:57:17.853 ThaliTest[1074:742025] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:57:17.859 ThaliTest[1074:742025] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:57:17.860 ThaliTest[1074:742025] jxcore: connect: success
2015-11-20T13:57:17.861Z SendDataConnector.js: CLIENT connected to 55858, error: null
,2015-11-20T13:57:17.862Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:57:17.866 ThaliTest[1074:741160] client: relay established
2015-11-20 14:57:17.867 ThaliTest[1074:741160] client: new accepted socket: 0x17d5f5b0
,2015-11-20T13:57:17.879Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T13:57:22.161Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:57:32.170Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T13:57:32.171Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T13:57:32.173Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T13:57:32.173Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T13:57:33.175Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:57:33.175Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:57:34.181 ThaliTest[1074:741302] jxcore: disconnect
2015-11-20 14:57:34.182 ThaliTest[1074:741302] client session: disconnectFromPeer: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:57:34.183 ThaliTest[1074:741302] client session: disconnect
2015-11-20 14:57:34.183 ThaliTest[1074:741302] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:57:58.776 ThaliTest[1074:741160] multipeer session: restart
2015-11-20 14:57:58.783 ThaliTest[1074:741302] jxcore: disconnect: success
2015-11-20T13:57:58.788Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT7,38.lFO7fw==
2015-11-20T13:57:58.789Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT738.lFO7fw== with availability status: true
2015-11-20T13:57:58.789Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7f,w==
2015-11-20T13:57:58.789Z SendDataConnector.js: do connect now
2015-11-20 14:57:58.790 ThaliTest[1074:741302] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:57:58.790 ThaliTest[1074:741302] client session: connect
2015-11-20 14:57:58.7,91 ThaliTest[1074:741302] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:57:58.809 ThaliTest[1074:741160] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:57:58.809 ThaliTest[1074:741160] client: found peer: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:57:58.812 ThaliTest[1074:741160] client:, found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:00.980 ThaliTest[1074:741160] multipeer session: reset timer
2015-11-20 14:58:00.980 ThaliTest[1074:741160] multipeer session: stop timer
2015-11-20 14:58:00.981 ThaliTest[1074:741160] multipeer session: start timer: 0x1bea4090
2015-11-,20 14:58:00.981 ThaliTest[1074:741160] server session: connect
2015-11-20 14:58:00.982 ThaliTest[1074:741160] server session: stateChange:0->1 Apple-Iphone5-1_PT738
,2015-11-20 14:58:00.994 ThaliTest[1074:741160] server: accepting invitation Apple-Iphone5-1_PT738
2015-11-20 14:58:00.995 ThaliTest[1074:741160] multipeer session: reset timer
2015-11-20 14:58:00.996 ThaliTest[1074:741160] multipeer session: stop timer
,2015-11-20 14:58:00.996 ThaliTest[1074:741160] multipeer session: start timer: 0x1bea4090
2015-11-20 14:58:00.997 ThaliTest[1074:741160] server: disconnecting to refresh session (Apple-Iphone5-1_PT738)
2015-11-20 14:58:00.997 ThaliTest[1074:741160] serve,r session: disconnect
2015-11-20 14:58:00.997 ThaliTest[1074:741160] server session: stateChange:1->0 Apple-Iphone5-1_PT738
2015-11-20 14:58:00.998 ThaliTest[1074:741160] server session: connect
2015-11-20 14:58:01.018 ThaliTest[1074:741160] server sess,ion: stateChange:0->1 Apple-Iphone5-1_PT738
,2015-11-20 14:58:01.031 ThaliTest[1074:741160] server: accepting invitation Apple-Iphone5-1_PT738
2015-11-20 14:58:01.031 ThaliTest[1074:741160] multipeer session: reset timer
2015-11-20 14:58:01.032 ThaliTest[1074:741160] multipeer session: stop timer
,2015-11-20 14:58:01.032 ThaliTest[1074:741160] multipeer session: start timer: 0x1bea4090
2015-11-20 14:58:01.033 ThaliTest[1074:741160] server: disconnecting to refresh session (Apple-Iphone5-1_PT738)
2015-11-20 14:58:01.033 ThaliTest[1074:741160] server session: disconnect
2015-11-20 14:58:01.034 ThaliTest[1074:741160] server session: stateChange:1->0 Apple-Iphone5-1_PT738
2015-11-20 14:58:01.034 ThaliTest[1074:741160] server session: connect
2015-11-20 14:58:01.050 ThaliTest[1074:741160] server session: stateChange:0->1 Apple-Iphone5-1_PT738
,2015-11-20 14:58:01.053 ThaliTest[1074:741160] server: accepting invitation Apple-Iphone5-1_PT738
2015-11-20 14:58:01.053 ThaliTest[1074:741160] multipeer session: reset timer
2015-11-20 14:58:01.054 ThaliTest[1074:741160] multipeer session: stop timer
,2015-11-20 14:58:01.054 ThaliTest[1074:741160] multipeer session: start timer: 0x1bea4090
2015-11-20 14:58:01.054 ThaliTest[1074:741160] server: disconnecting to refresh session (Apple-Iphone5-1_PT738)
2015-11-20 14:58:01.054 ThaliTest[1074:741160] serve,r session: disconnect
2015-11-20 14:58:01.054 ThaliTest[1074:741160] server session: stateChange:1->0 Apple-Iphone5-1_PT738
2015-11-20 14:58:01.054 ThaliTest[1074:741160] server session: connect
2015-11-20 14:58:01.054 ThaliTest[1074:741160] server session: stateChange:0->1 Apple-Iphone5-1_PT738
,2015-11-20 14:58:01.058 ThaliTest[1074:741160] server: accepting invitation Apple-Iphone5-1_PT738
,2015-11-20 14:58:03.438 ThaliTest[1074:741160] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:58:03.454 ThaliTest[1074:742025] client session: connected
2015-11-20 14:58:03.455 ThaliTest[1074:742025] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:03.464 ThaliTest[1074:742104] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:58:03.465 ThaliTest[1074:742104] jxcore: connect: success
2015-11-20T13:58:03.466Z SendDataConnector.js: CLIENT connected to 55862, error: null
2015-11-20T13:58:03.466Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:58:03.470 ThaliTest[1074:741160] client: relay established
2015-11-20 14:58:03.471 ThaliTest[1074:741160] client: new accepted socket: 0x1bead740
,2015-11-20T13:58:03.482Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 14:58:04.522 ThaliTest[1074:741160] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:58:04.522 ThaliTest[1074:741160] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:58:07.834Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-20 14:58:08.647 ThaliTest[1074:741160] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 14:58:12.103 ThaliTest[1074:742113] server session: not connected Apple-Iphone5-1_PT738
,2015-11-20T13:58:17.842Z SendDataConnector.js: Receiving data timeout now
2015-11-20T13:58:17.843Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T13:58:17.845Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20T13:58:17.846Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20 14:58:18.069 ThaliTest[1074:741160] client: socket closed
2015-11-20 14:58:18.069 ThaliTest[1074:741160] client relay: socket disconnected
2015-11-20 14:58:18.070 ThaliTest[1074:741160] client relay: 0x1bead740 disconnected with error Error Do,main=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x17d243d0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 14:58:18.070 ThaliTest[1074:741160] client session: socket closed: Apple-Iphone5-1_PT738.lFO7fw==
2,015-11-20 14:58:18.070 ThaliTest[1074:741160] client session: onLinkFailure: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:58:18.071 ThaliTest[1074:741160] client session: disconnect
2015-11-20 14:58:18.071 ThaliTest[1074:741160] client session: stateChan,ge:2->0 Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:58:18.072 ThaliTest[1074:741160] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:58:18.857Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:58:18.858Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:19.869 ThaliTest[1074:741302] jxcore: disconnect
2015-11-20 14:58:19.870 ThaliTest[1074:741302] jxcore: disconnect: fail
2015-11-20T13:58:19.871Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==,
2015-11-20T13:58:19.871Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT738.lFO7fw== with availability status: true
2015-11-20T13:58:19.871Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:58:19.872Z SendDataConnector.js: do connect now
2015-11-20 14:58:19.872 ThaliTest[1074:741302] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:19.873 ThaliTest[1074:741302] client session: connect
2015-11-20 14:58:19.874 ThaliTest[1074:741302] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:22.329 ThaliTest[1074:742025] client session: connected
,2015-11-20 14:58:22.331 ThaliTest[1074:742025] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:22.333 ThaliTest[1074:742025] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:58:22.333 ThaliTest[1074:742025] jxcore: connect: success
2015-11-20T13:58:22.334Z SendDataConnector.js: CLIENT connected to 55864, error: null
,2015-11-20T13:58:22.335Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:58:22.338 ThaliTest[1074:741160] client: relay established
2015-11-20 14:58:22.339 ThaliTest[1074:741160] client: new accepted socket: 0x1bf30140
,2015-11-20T13:58:22.349Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T13:58:26.661Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:31.494 ThaliTest[1074:741160] multipeer session: restart
,2015-11-20 14:58:33.411 ThaliTest[1074:741160] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:58:33.412 ThaliTest[1074:741160] client: found peer: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:58:33.413 ThaliTest[1074:741160] client:, found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:58:36.669Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T13:58:36.670Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T13:58:36.670Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T13:58:36.671Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T13:58:37.681Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T13:58:37.681Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:37.683 ThaliTest[1074:741160] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:58:37.683 ThaliTest[1074:741160] client: socket closed
2015-11-20 14:58:37.684 ThaliTest[1074:741160] client relay: socket disconnected
201,5-11-20 14:58:37.684 ThaliTest[1074:741160] client relay: 0x1bf30140 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x17d98d10 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20, 14:58:37.684 ThaliTest[1074:741160] client session: socket closed: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:58:37.685 ThaliTest[1074:741160] client session: onLinkFailure: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:58:37.685 ThaliTest[1074:741160], client session: disconnect
2015-11-20 14:58:37.686 ThaliTest[1074:741160] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:58:37.689 ThaliTest[1074:741160] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:38.687 ThaliTest[1074:741302] jxcore: disconnect
2015-11-20 14:58:38.688 ThaliTest[1074:741302] jxcore: disconnect: fail
2015-11-20T13:58:38.689Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==,
2015-11-20T13:58:38.689Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT738.lFO7fw== with availability status: true
2015-11-20T13:58:38.689Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:58:38.690Z SendDataConnector.js: do connect now
,2015-11-20 14:58:38.690 ThaliTest[1074:741302] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:38.692 ThaliTest[1074:741302] client session: connect
,2015-11-20 14:58:38.693 ThaliTest[1074:741302] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:41.562 ThaliTest[1074:742219] client session: connected
2015-11-20 14:58:41.563 ThaliTest[1074:742219] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:41.568 ThaliTest[1074:742219] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:58:41.568 ThaliTest[1074:742219] jxcore: connect: success
2015-11-20T13:58:41.569Z SendDataConnector.js: CLIENT connected to 55868, error: null
2015-11-20T13:58:41.570Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:58:41.573 ThaliTest[1074:741160] client: relay established
2015-11-20 14:58:41.573 ThaliTest[1074:741160] client: new accepted socket: 0x1bb00080
,2015-11-20T13:58:41.585Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T13:58:45.870Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:58:55.876Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T13:58:55.877Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T13:58:55.878Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20 14:58:55.878 ThaliTest[1074:741160] client: socket closed
2015-11-20T13:58:55.879Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 14:58:55.879 ThaliT,est[1074:741160] client relay: socket disconnected
,2015-11-20 14:58:55.879 ThaliTest[1074:741160] client relay: 0x1bb00080 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bdd8020 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11,-20 14:58:55.880 ThaliTest[1074:741160] client session: socket closed: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:55.881 ThaliTest[1074:741160] client session: onLinkFailure: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:58:55.881 ThaliTest[1074:741160] client session: disconnect
,2015-11-20 14:58:55.882 ThaliTest[1074:741160] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:55.884 ThaliTest[1074:741160] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:58:56.879Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:58:56.880Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:57.893 ThaliTest[1074:741302] jxcore: disconnect
2015-11-20 14:58:57.893 ThaliTest[1074:741302] jxcore: disconnect: fail
2015-11-20T13:58:57.894Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==,
2015-11-20T13:58:57.894Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT738.lFO7fw== with availability status: true
2015-11-20T13:58:57.895Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:58:57.895Z SendDataConnector.js: do connect now
,2015-11-20 14:58:57.896 ThaliTest[1074:741302] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:58:57.897 ThaliTest[1074:741302] client session: connect
2015-11-20 14:58:57.898 ThaliTest[1074:741302] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:00.175 ThaliTest[1074:742219] client session: connected
2015-11-20 14:59:00.175 ThaliTest[1074:742219] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:00.181 ThaliTest[1074:742263] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:00.182 ThaliTest[1074:742263] jxcore: connect: success
2015-11-20T13:59:00.183Z SendDataConnector.js: CLIENT connected to ,55870, error: null
2015-11-20T13:59:00.183Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:59:00.187 ThaliTest[1074:741160] client: relay established
2015-11-20 14:59:00.187 ThaliTest[1074:741160] client: new accepted socket: 0x1bea5bd0
,2015-11-20T13:59:00.200Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 14:59:01.053 ThaliTest[1074:741160] multipeer session: restart
,2015-11-20 14:59:01.150 ThaliTest[1074:741160] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:59:01.150 ThaliTest[1074:741160] client: found peer: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:59:01.150 ThaliTest[1074:741160] client:, found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:59:04.492Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:59:14.494Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T13:59:14.495Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T13:59:14.498Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T13:59:14.498Z SendDataConnector.js: Stop data retrieving timer
,2015-11-20 14:59:14.499 ThaliTest[1074:741302] jxcore: disconnect
2015-11-20 14:59:14.500 ThaliTest[1074:741302] client session: disconnectFromPeer: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:14.501 ThaliTest[1074:741302] client session: disconnect
2015-11-20 14:59:14.501 ThaliTest[1074:741302] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:14.723 ThaliTest[1074:741160] client: socket closed
,2015-11-20 14:59:14.726 ThaliTest[1074:741160] client relay: socket disconnected
2015-11-20 14:59:14.728 ThaliTest[1074:741160] client relay: 0x1bea5bd0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" U,serInfo=0x1bdd8020 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 14:59:14.729 ThaliTest[1074:741160] client session: socket closed: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:14.727 ThaliTest[1074:741302] jxcore: disconnect: succ,ess
2015-11-20 14:59:14.729 ThaliTest[1074:741160] client session: onLinkFailure: Apple-Iphone5-1_PT738.lFO7fw==
Assertion failed: ([self connectionState] != THEPeerSessionStateNotConnected), function -[THEMultipeerClientSession onLinkFailure], file /Use,rs/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerClientSession.m, line 124.
2015-11-20T13:59:14.730Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==
---- round done----,----
,Process 1074 stopped
* thread #1: tid = 0xb4f28, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x35e14df0 <+8>:  blo    0x35e14e08                ; <+32>
    0x35e14df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x35e14df8 <+16>: ldr    r12, [pc, r12]
    0x35e14dfc <+20>: b      0x35e14e04                ; <+28>
,* thread #1: tid = 0xb4f28, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x35e93cc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x35db0908 libsystem_c.dylib`abort + 76
    frame #3: 0x35d90368 libsystem_c.dylib`__assert_rtn + 92
    frame #4: 0x0006582a ThaliTest`-[THEMultipeerClientSession onLinkFailure] + 290
    frame #5: 0x0006602c ThaliTest`-[THEMultipeerClientSession didDisconnectFromPeer] + 104
    frame #6: 0x000682b2 ThaliTest`-[THEMultipeerClientSocketRelay socketDidDisconnect:withError:] + 182
    frame #7: 0x00072a92 ThaliTest`__33-[GCDAsyncSocket closeWithError:]_block_invoke + 70
    frame #8: 0x35d292e2 libdispatch.dylib`<redacted> + 10
    frame #9: 0x35d292ce libdispatch.dylib`<redacted> + 22
    frame #10: 0x35d2cd2e libdispatch.dylib`_dispatch_main_queue_callback_4CF + 1330
    frame #11: 0x26df4608 CoreFoundation`<redacted> + 8
    frame #12: 0x26df2d08 CoreFoundation`<redacted> + 1512
    frame #13: 0x26d3f200 CoreFoundation`CFRunLoopRunSpecific + 476
    frame #14: 0x26d3f012 CoreFoundation`CFRunLoopRunInMode + 106
    frame #15: 0x2e7ca200 GraphicsServices`GSEventRunModal + 136
    frame #16: 0x2a50ba08 UIKit`UIApplicationMain + 1440
    frame #17: 0x00051692 ThaliTest`main + 50

```
