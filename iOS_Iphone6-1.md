#### Test 51193821e3da755_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51193821e3da755/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6625D1FF-503D-4136-AEE4-7273DB5E74DA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6625D1FF-503D-4136-AEE4-7273DB5E74DA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51193821e3da755/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51193821e3da755/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4E090073-7346-4C56-88B3-6A8AD6F06086/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50442"
,(lldb)     command script import "/tmp/6625D1FF-503D-4136-AEE4-7273DB5E74DA/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-19 10:40:00.346 ThaliTest[933:609867] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D4D47EE0-7DC7-4B58-BE9A-9DA4937C1399/Library/Cookies/Cookies.binarycookies
,2015-11-19 10:40:00.746 ThaliTest[933:609867] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-19 10:40:00.748 ThaliTest[933:609867] Multi-tasking -> Device: YES, App: YES
,2015-11-19 10:40:00.758 ThaliTest[933:609867] Unlimited access to network resources
,2015-11-19 10:40:00.767 ThaliTest[933:609867] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-19 10:40:04.678 ThaliTest[933:609867] Resetting plugins due to page load.
,2015-11-19 10:40:05.094 ThaliTest[933:609867] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/4E090073-7346-4C56-88B3-6A8AD6F06086/ThaliTest.app/www/index.html
,2015-11-19 10:40:05.218 ThaliTest[933:609867] JXcore Cordova plugin initializing
,2015-11-19 10:40:05.220 ThaliTest[933:610001] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT4558
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
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
found interfaceName: awdl0
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
printNetworkInfo
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
-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
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
found interfaceName: awdl0
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
-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::8013:17ff:fef8:3605
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"1000000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":2,"addressList":[],}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"500000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 55041
,2015-11-19 10:49:08.358 ThaliTest[933:610001] jxcore: startBroadcasting
,2015-11-19 10:49:08.372 ThaliTest[933:610001] server: starting Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:08.373 ThaliTest[933:610001] multipeer session: start timer: 0x1bea2840
2015-11-19 10:49:08.374 ThaliTest[933:610001] THEMultipeerSession init,ialized peer Apple-Iphone6-1_PT4558
2015-11-19 10:49:08.374 ThaliTest[933:610001] jxcore: startBroadcasting: success
StartBroadcasting started ok
TCP/IP server  is bound to : undefined
,2015-11-19 10:49:08.913 ThaliTest[933:609867] client: found peer: Apple-Iphone5s-1_PT9462.AiaXgQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9462.AiaXgQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:49:09.504 ThaliTest[933:609867] client: found peer: Apple-IpadAir2-1_PT6621.ucYn4g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6621.ucYn4g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-19 10:49:13.929 ThaliTest[933:610001] jxcore: disconnect
2015-11-19 10:49:13.930 ThaliTest[933:610001] jxcore: disconnect: fail
Connect (retry count 0) to peer Apple-Iphone5s-1_PT9462.AiaXgQ== with availability status: true
,do connect now
,2015-11-19 10:49:13.932 ThaliTest[933:610001] jxcore: connect Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:49:13.933 ThaliTest[933:610001] client session: connect
2015-11-19 10:49:13.934 ThaliTest[933:610001] client session: stateChange:0->1 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:49:14.739 ThaliTest[933:609867] multipeer session: reset timer
2015-11-19 10:49:14.739 ThaliTest[933:609867] multipeer session: stop timer
2015-11-19 10:49:14.740 ThaliTest[933:609867] multipeer session: start timer: 0x1bea2840
2015-11-19 10:49:14.740 ThaliTest[933:609867] server session: connect
2015-11-19 10:49:14.740 ThaliTest[933:609867] server session: stateChange:0->1 Apple-Iphone5s-1_PT9462
,2015-11-19 10:49:14.743 ThaliTest[933:609867] server: accepting invitation Apple-Iphone5s-1_PT9462
,2015-11-19 10:49:15.689 ThaliTest[933:609867] multipeer session: reset timer
2015-11-19 10:49:15.689 ThaliTest[933:609867] multipeer session: stop timer
2015-11-19 10:49:15.690 ThaliTest[933:609867] multipeer session: start timer: 0x1bea2840
2015-11-19 ,10:49:15.691 ThaliTest[933:609867] server session: connect
2015-11-19 10:49:15.691 ThaliTest[933:609867] server session: stateChange:0->1 Apple-IpadAir2-1_PT6621
,2015-11-19 10:49:15.705 ThaliTest[933:609867] server: accepting invitation Apple-IpadAir2-1_PT6621
,2015-11-19 10:49:17.285 ThaliTest[933:610730] server session: connected
,2015-11-19 10:49:17.286 ThaliTest[933:610730] server session: stateChange:1->2 Apple-Iphone5s-1_PT9462
,2015-11-19 10:49:17.299 ThaliTest[933:609867] server relay: connected (to port: 55041)
TCP/IP server connected
,2015-11-19 10:49:17.399 ThaliTest[933:610730] client session: connected
2015-11-19 10:49:17.400 ThaliTest[933:610730] client session: stateChange:1->2 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:49:17.405 ThaliTest[933:610730] client session: fireConnectCallback: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:49:17.406 ThaliTest[933:610730] jxcore: connect: success
,CLIENT connected to 55046, error: null
,CLIENT starting client 
,2015-11-19 10:49:17.413 ThaliTest[933:609867] client: relay established
2015-11-19 10:49:17.414 ThaliTest[933:609867] client: new accepted socket: 0x1bf17ae0
,CLIENT now sending 1000000 bytes of data
,TCP/IP server has received 131072 bytes of data
TCP/IP server has received 262144 bytes of data
,TCP/IP server has received 393216 bytes of data
,TCP/IP server has received 524288 bytes of data
TCP/IP server has received 556260 bytes of data
,2015-11-19 10:49:18.353 ThaliTest[933:610690] server session: connected
2015-11-19 10:49:18.355 ThaliTest[933:610690] server session: stateChange:1->2 Apple-IpadAir2-1_PT6621
,TCP/IP server connected
,2015-11-19 10:49:18.851 ThaliTest[933:609867] server relay: connected (to port: 55041)
,CLIENT is data received : 0
,TCP/IP server has received 560356 bytes of data
,TCP/IP server has received 6144 bytes of data
,CLIENT is data received : 0
TCP/IP server has received 566500 bytes of data
,TCP/IP server has received 8192 bytes of data
CLIENT is data received : 0
,TCP/IP server has received 104448 bytes of data
CLIENT is data received : 10000
TCP/IP server has received 664804 bytes of data
,TCP/IP server has received 235520 bytes of data
,TCP/IP server has received 260096 bytes of data
TCP/IP server has received 795876 bytes of data
TCP/IP server has received 820452 bytes of data
,TCP/IP server has received 331776 bytes of data
,TCP/IP server has received 951524 bytes of data
,TCP/IP server has received 1000002 bytes of data
,TCP/IP server has received 419840 bytes of data
CLIENT is data received : 20000
,TCP/IP server has received 534528 bytes of data
CLIENT is data received : 30000
,TCP/IP server has received 665600 bytes of data
,TCP/IP server has received 675840 bytes of data
CLIENT is data received : 30000
,TCP/IP server has received 806912 bytes of data
,TCP/IP server has received 882688 bytes of data
,TCP/IP server has received 978930 bytes of data
,TCP/IP server has received 1000002 bytes of data
,CLIENT is data received : 40000
,CLIENT is data received : 50000
,2015-11-19 10:49:29.806 ThaliTest[933:610691] server session: not connected Apple-Iphone5s-1_PT9462
,Receiving data timeout now
CLIENT closeClientSocket
2015-11-19 10:49:29.919 ThaliTest[933:610749] server session: not connected Apple-IpadAir2-1_PT6621
,2015-11-19 10:49:29.922 ThaliTest[933:609867] client: socket closed
2015-11-19 10:49:29.923 ThaliTest[933:609867] client relay: socket disconnected
2015-11-19 10:49:29.923 ThaliTest[933:609867] client relay: 0x1bf17ae0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bf15800 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:49:29.924 ThaliTest[933:609867] client session: socket closed: Apple-Iphone5s-1_PT9462.AiaXgQ==
201,5-11-19 10:49:29.924 ThaliTest[933:609867] client session: onLinkFailure: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:49:29.925 ThaliTest[933:609867] client session: disconnect
2015-11-19 10:49:29.925 ThaliTest[933:609867] client session: stateChange:,2->0 Apple-Iphone5s-1_PT9462.AiaXgQ==
tryAgain afer: 5000 ms.
----------------- closeClientSocket
,CLIENT is closed
2015-11-19 10:49:29.928 ThaliTest[933:609867] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9462.AiaXgQ==
,re-try now : Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:49:39.816 ThaliTest[933:609867] multipeer session: reset timer
2015-11-19 10:49:39.817 ThaliTest[933:609867] multipeer session: stop timer
2015-11-19 10:49:39.818 ThaliTest[933:609867] multipeer session: start timer: 0x1bea2840
2015-11-19 ,10:49:39.818 ThaliTest[933:609867] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9462)
2015-11-19 10:49:39.819 ThaliTest[933:609867] server session: disconnect
2015-11-19 10:49:39.819 ThaliTest[933:609867] server session: stateChange:2->0 ,Apple-Iphone5s-1_PT9462
2015-11-19 10:49:39.823 ThaliTest[933:609867] server session: connect
2015-11-19 10:49:39.823 ThaliTest[933:609867] server session: stateChange:0->1 Apple-Iphone5s-1_PT9462
,TCP/IP server is ended
TCP/IP server is close
2015-11-19 10:49:39.844 ThaliTest[933:609867] server: accepting invitation Apple-Iphone5s-1_PT9462
,2015-11-19 10:49:39.947 ThaliTest[933:610001] jxcore: disconnect
2015-11-19 10:49:39.948 ThaliTest[933:610001] jxcore: disconnect: fail
Connect (retry count 1) to peer Apple-Iphone5s-1_PT9462.AiaXgQ== with availability status: true
do connect now
,2015-11-19 10:49:39.949 ThaliTest[933:610001] jxcore: connect Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:49:39.950 ThaliTest[933:610001] client session: connect
2015-11-19 10:49:39.951 ThaliTest[933:610001] client session: stateChange:0->1 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:49:41.419 ThaliTest[933:609867] multipeer session: reset timer
2015-11-19 10:49:41.419 ThaliTest[933:609867] multipeer session: stop timer
2015-11-19 10:49:41.420 ThaliTest[933:609867] multipeer session: start timer: 0x1bea2840
2015-11-19 ,10:49:41.421 ThaliTest[933:609867] server: disconnecting to refresh session (Apple-IpadAir2-1_PT6621)
2015-11-19 10:49:41.421 ThaliTest[933:609867] server session: disconnect
2015-11-19 10:49:41.422 ThaliTest[933:609867] server session: stateChange:2->0 ,Apple-IpadAir2-1_PT6621
2015-11-19 10:49:41.426 ThaliTest[933:609867] server session: connect
2015-11-19 10:49:41.427 ThaliTest[933:609867] server session: stateChange:0->1 Apple-IpadAir2-1_PT6621
,TCP/IP server is ended
TCP/IP server is close
2015-11-19 10:49:41.441 ThaliTest[933:609867] server: accepting invitation Apple-IpadAir2-1_PT6621
,2015-11-19 10:49:42.046 ThaliTest[933:610781] server session: connected
2015-11-19 10:49:42.047 ThaliTest[933:610781] server session: stateChange:1->2 Apple-Iphone5s-1_PT9462
,2015-11-19 10:49:42.060 ThaliTest[933:609867] server relay: connected (to port: 55041)
TCP/IP server connected
,2015-11-19 10:49:42.493 ThaliTest[933:610783] client session: connected
,2015-11-19 10:49:42.495 ThaliTest[933:610783] client session: stateChange:1->2 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:49:42.500 ThaliTest[933:610781] client session: fireConnectCallback: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:49:42.501 ThaliTest[933:610781] jxcore: connect: success
CLIENT connected to 55052, error: null
CLIENT starting client 
,2015-11-19 10:49:42.507 ThaliTest[933:609867] client: relay established
2015-11-19 10:49:42.507 ThaliTest[933:609867] client: new accepted socket: 0x1bae7f00
,CLIENT now sending 950000 bytes of data
,TCP/IP server has received 131072 bytes of data
,TCP/IP server has received 262144 bytes of data
,TCP/IP server has received 393216 bytes of data
,TCP/IP server has received 524288 bytes of data
,TCP/IP server has received 655360 bytes of data
,TCP/IP server has received 786432 bytes of data
,TCP/IP server has received 917504 bytes of data
,TCP/IP server has received 990002 bytes of data
,CLIENT is data received : 50000
,CLIENT is data received : 50000
,CLIENT is data received : 50000
,CLIENT is data received : 60000
,CLIENT is data received : 70000
,CLIENT is data received : 70000
,CLIENT is data received : 80000
,CLIENT is data received : 90000
,CLIENT is data received : 100000
,2015-11-19 10:49:44.127 ThaliTest[933:610730] server session: connected
2015-11-19 10:49:44.128 ThaliTest[933:610730] server session: stateChange:1->2 Apple-IpadAir2-1_PT6621
,2015-11-19 10:49:44.136 ThaliTest[933:609867] server relay: connected (to port: 55041)
TCP/IP server connected
,TCP/IP server has received 28470 bytes of data
,TCP/IP server has received 45990 bytes of data
,TCP/IP server has received 78840 bytes of data
,TCP/IP server has received 100740 bytes of data
,TCP/IP server has received 131400 bytes of data
,TCP/IP server has received 165730 bytes of data
,TCP/IP server has received 183960 bytes of data
,TCP/IP server has received 205860 bytes of data
,TCP/IP server has received 245280 bytes of data
,TCP/IP server has received 280320 bytes of data
,TCP/IP server has received 291270 bytes of data
,TCP/IP server has received 317550 bytes of data
,TCP/IP server has received 359160 bytes of data
,TCP/IP server has received 385440 bytes of data
,TCP/IP server has received 387630 bytes of data
,TCP/IP server has received 398580 bytes of data
,TCP/IP server has received 418290 bytes of data
,TCP/IP server has received 438000 bytes of data
,TCP/IP server has received 459900 bytes of data
,TCP/IP server has received 479610 bytes of data
,TCP/IP server has received 494940 bytes of data
,TCP/IP server has received 525458 bytes of data
,TCP/IP server has received 558450 bytes of data
,TCP/IP server has received 560640 bytes of data
,TCP/IP server has received 573780 bytes of data
,TCP/IP server has received 593490 bytes of data
,TCP/IP server has received 617580 bytes of data
,TCP/IP server has received 657000 bytes of data
,TCP/IP server has received 692040 bytes of data
,TCP/IP server has received 727080 bytes of data
,TCP/IP server has received 764310 bytes of data
,TCP/IP server has received 803730 bytes of data
,TCP/IP server has received 838770 bytes of data
,TCP/IP server has received 849720 bytes of data
,TCP/IP server has received 884760 bytes of data
,TCP/IP server has received 941700 bytes of data
,TCP/IP server has received 970002 bytes of data
,2015-11-19 10:49:53.394 ThaliTest[933:610780] server session: not connected Apple-Iphone5s-1_PT9462
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,----------------- closeClientSocket
,2015-11-19 10:49:53.985 ThaliTest[933:609867] client: socket closed
CLIENT is closed
2015-11-19 10:49:53.985 ThaliTest[933:609867] client relay: socket disconnected
2015-11-19 10:49:53.986 ThaliTest[933:609867] client relay: 0x1bae7f00 disconnected with, error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1baaed00 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:49:53.986 ThaliTest[933:609867] client session: socket closed: Apple-Iphone5s-1_PT,9462.AiaXgQ==
2015-11-19 10:49:53.987 ThaliTest[933:609867] client session: onLinkFailure: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:49:53.987 ThaliTest[933:609867] client session: disconnect
2015-11-19 10:49:53.988 ThaliTest[933:609867] client ses,sion: stateChange:2->0 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:49:53.990 ThaliTest[933:609867] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:49:55.490 ThaliTest[933:610783] server session: not connected Apple-IpadAir2-1_PT6621
,re-try now : Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:03.526 ThaliTest[933:609867] multipeer session: reset timer
2015-11-19 10:50:03.526 ThaliTest[933:609867] multipeer session: stop timer
2015-11-19 10:50:03.527 ThaliTest[933:609867] multipeer session: start timer: 0x1bea2840
2015-11-19 ,10:50:03.527 ThaliTest[933:609867] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9462)
2015-11-19 10:50:03.528 ThaliTest[933:609867] server session: disconnect
2015-11-19 10:50:03.528 ThaliTest[933:609867] server session: stateChange:2->0 ,Apple-Iphone5s-1_PT9462
2015-11-19 10:50:03.533 ThaliTest[933:609867] server session: connect
2015-11-19 10:50:03.533 ThaliTest[933:609867] server session: stateChange:0->1 Apple-Iphone5s-1_PT9462
TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:50:03.547 ThaliTest[933:609867] server: accepting invitation Apple-Iphone5s-1_PT9462
,2015-11-19 10:50:03.994 ThaliTest[933:610001] jxcore: disconnect
2015-11-19 10:50:03.995 ThaliTest[933:610001] jxcore: disconnect: fail
Connect (retry count 2) to peer Apple-Iphone5s-1_PT9462.AiaXgQ== with availability status: true
do connect now
,2015-11-19 10:50:03.996 ThaliTest[933:610001] jxcore: connect Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:50:03.997 ThaliTest[933:610001] client session: connect
2015-11-19 10:50:03.997 ThaliTest[933:610001] client session: stateChange:0->1 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:05.986 ThaliTest[933:610838] server session: connected
2015-11-19 10:50:05.986 ThaliTest[933:610838] server session: stateChange:1->2 Apple-Iphone5s-1_PT9462
,TCP/IP server connected
2015-11-19 10:50:06.000 ThaliTest[933:609867] server relay: connected (to port: 55041)
,TCP/IP server has received 10950 bytes of data
,TCP/IP server has received 28470 bytes of data
,TCP/IP server has received 50370 bytes of data
,TCP/IP server has received 67890 bytes of data
,TCP/IP server has received 91980 bytes of data
2015-11-19 10:50:06.587 ThaliTest[933:610837] client session: connected
2015-11-19 10:50:06.588 ThaliTest[933:610837] client session: stateChange:1->2 Apple-Iphone5s-1_PT9462.AiaXgQ==
TCP/IP server has rece,ived 94170 bytes of data
2015-11-19 10:50:06.596 ThaliTest[933:609867] multipeer session: reset timer
2015-11-19 10:50:06.597 ThaliTest[933:609867] multipeer session: stop timer
2015-11-19 10:50:06.597 ThaliTest[933:609867] multipeer session: start time,r: 0x1bea2840
2015-11-19 10:50:06.598 ThaliTest[933:609867] server: disconnecting to refresh session (Apple-IpadAir2-1_PT6621)
2015-11-19 10:50:06.598 ThaliTest[933:609867] server session: disconnect
,2015-11-19 10:50:06.599 ThaliTest[933:609867] server session: stateChange:2->0 Apple-IpadAir2-1_PT6621
2015-11-19 10:50:06.604 ThaliTest[933:610783] client session: fireConnectCallback: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:50:06.619 ThaliTest[9,33:610783] jxcore: connect: success
2015-11-19 10:50:06.619 ThaliTest[933:609867] server session: connect
2015-11-19 10:50:06.619 ThaliTest[933:609867] server session: stateChange:0->1 Apple-IpadAir2-1_PT6621
,CLIENT connected to 55058, error: null
CLIENT starting client 
2015-11-19 10:50:06.631 ThaliTest[933:609867] server: accepting invitation Apple-IpadAir2-1_PT6621
2015-11-19 10:50:06.632 ThaliTest[933:609867] client: relay established
2015-11-19 10:50:06.632 ThaliTest[933:609867] client: new accepted socket: 0x1be20c70
,TCP/IP server is ended
,TCP/IP server has received 118260 bytes of data
,CLIENT now sending 900000 bytes of data
,TCP/IP server is close
,TCP/IP server has received 249332 bytes of data
TCP/IP server has received 380404 bytes of data
,TCP/IP server has received 511476 bytes of data
,TCP/IP server has received 642548 bytes of data
,TCP/IP server has received 773620 bytes of data
TCP/IP server has received 904692 bytes of data
,TCP/IP server has received 980002 bytes of data
,CLIENT is data received : 100000
,CLIENT is data received : 100000
,CLIENT is data received : 100000
,CLIENT is data received : 110000
,CLIENT is data received : 120000
,CLIENT is data received : 130000
,CLIENT is data received : 140000
,CLIENT is data received : 140000
,2015-11-19 10:50:09.166 ThaliTest[933:610838] server session: connected
2015-11-19 10:50:09.167 ThaliTest[933:610838] server session: stateChange:1->2 Apple-IpadAir2-1_PT6621
,2015-11-19 10:50:09.173 ThaliTest[933:609867] server relay: connected (to port: 55041)
,TCP/IP server connected
,TCP/IP server has received 17520 bytes of data
,TCP/IP server has received 48180 bytes of data
,TCP/IP server has received 65558 bytes of data
,TCP/IP server has received 81030 bytes of data
,TCP/IP server has received 116070 bytes of data
,TCP/IP server has received 131400 bytes of data
,TCP/IP server has received 159870 bytes of data
,TCP/IP server has received 179580 bytes of data
,TCP/IP server has received 208050 bytes of data
,TCP/IP server has received 245280 bytes of data
,TCP/IP server has received 275940 bytes of data
,TCP/IP server has received 304410 bytes of data
,TCP/IP server has received 356970 bytes of data
,TCP/IP server has received 378870 bytes of data
,TCP/IP server has received 400770 bytes of data
,TCP/IP server has received 424860 bytes of data
,TCP/IP server has received 455520 bytes of data
,TCP/IP server has received 479610 bytes of data
,TCP/IP server has received 523410 bytes of data
,TCP/IP server has received 565020 bytes of data
,TCP/IP server has received 593490 bytes of data
,TCP/IP server has received 637290 bytes of data
,TCP/IP server has received 674520 bytes of data
,TCP/IP server has received 718320 bytes of data
,TCP/IP server has received 766500 bytes of data
,TCP/IP server has received 803730 bytes of data
,TCP/IP server has received 865050 bytes of data
,TCP/IP server has received 919800 bytes of data
,TCP/IP server has received 935130 bytes of data
,TCP/IP server has received 940002 bytes of data
,2015-11-19 10:50:17.682 ThaliTest[933:610781] server session: not connected Apple-Iphone5s-1_PT9462
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:50:18.095 ThaliTest[933:609867] client: socket closed
----------------- closeClientSocket
2015-11-19 10:50:18.096 ThaliTest[933:609867] client relay: socket disconnected
CLIENT is closed
,2015-11-19 10:50:18.098 ThaliTest[933:609867] client relay: 0x1be20c70 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bb5e4f0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-,19 10:50:18.098 ThaliTest[933:609867] client session: socket closed: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:50:18.099 ThaliTest[933:609867] client session: onLinkFailure: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:50:18.099 ThaliTest[933:6098,67] client session: disconnect
2015-11-19 10:50:18.100 ThaliTest[933:609867] client session: stateChange:2->0 Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:50:18.101 ThaliTest[933:609867] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9462,.AiaXgQ==
,2015-11-19 10:50:20.192 ThaliTest[933:610781] server session: not connected Apple-IpadAir2-1_PT6621
,re-try now : Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:28.106 ThaliTest[933:610001] jxcore: disconnect
2015-11-19 10:50:28.106 ThaliTest[933:610001] jxcore: disconnect: fail
Connect (retry count 3) to peer Apple-Iphone5s-1_PT9462.AiaXgQ== with availability status: true
do connect now
2015-11-19 10:50:28.108 ThaliTest[933:610001] jxcore: connect Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:28.108 ThaliTest[933:610001] client session: connect
2015-11-19 10:50:28.110 ThaliTest[933:610001] client session: stateChange:0->1 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:28.632 ThaliTest[933:609867] multipeer session: reset timer
2015-11-19 10:50:28.632 ThaliTest[933:609867] multipeer session: stop timer
2015-11-19 10:50:28.633 ThaliTest[933:609867] multipeer session: start timer: 0x1bea2840
2015-11-19 ,10:50:28.634 ThaliTest[933:609867] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9462)
2015-11-19 10:50:28.634 ThaliTest[933:609867] server session: disconnect
2015-11-19 10:50:28.635 ThaliTest[933:609867] server session: stateChange:2->0 ,Apple-Iphone5s-1_PT9462
,2015-11-19 10:50:28.639 ThaliTest[933:609867] server session: connect
2015-11-19 10:50:28.640 ThaliTest[933:609867] server session: stateChange:0->1 Apple-Iphone5s-1_PT9462
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:50:28.648 ThaliTest[933:609867] server: accepting invitation Apple-Iphone5s-1_PT9462
,2015-11-19 10:50:30.799 ThaliTest[933:610889] server session: connected
2015-11-19 10:50:30.800 ThaliTest[933:610889] server session: stateChange:1->2 Apple-Iphone5s-1_PT9462
,2015-11-19 10:50:30.809 ThaliTest[933:609867] server relay: connected (to port: 55041)
2015-11-19 10:50:30.815 ThaliTest[933:610893] client session: connected
,2015-11-19 10:50:30.817 ThaliTest[933:610893] client session: stateChange:1->2 Apple-Iphone5s-1_PT9462.AiaXgQ==
,TCP/IP server connected
,2015-11-19 10:50:30.826 ThaliTest[933:610900] client session: fireConnectCallback: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:50:30.827 ThaliTest[933:610900] jxcore: connect: success
CLIENT connected to 55064, error: null
CLIENT starting client 
,2015-11-19 10:50:30.831 ThaliTest[933:609867] client: relay established
2015-11-19 10:50:30.832 ThaliTest[933:609867] client: new accepted socket: 0x1baa57a0
,CLIENT now sending 860000 bytes of data
,2015-11-19 10:50:31.154 ThaliTest[933:609867] multipeer session: reset timer
2015-11-19 10:50:31.154 ThaliTest[933:609867] multipeer session: stop timer
2015-11-19 10:50:31.154 ThaliTest[933:609867] multipeer session: start timer: 0x1bea2840
2015-11-19 10:50:31.154 ThaliTest[933:609867] server: disconnecting to refresh session (Apple-IpadAir2-1_PT6621)
2015-11-19 10:50:31.154 ThaliTest[933:609867] server session: disconnect
2015-11-19 10:50:31.155 ThaliTest[933:609867] server session: stateChange:2->0 Apple-IpadAir2-1_PT6621
,2015-11-19 10:50:31.158 ThaliTest[933:609867] server session: connect
2015-11-19 10:50:31.158 ThaliTest[933:609867] server session: stateChange:0->1 Apple-IpadAir2-1_PT6621
,2015-11-19 10:50:31.161 ThaliTest[933:609867] server: accepting invitation Apple-IpadAir2-1_PT6621
,TCP/IP server is ended
,TCP/IP server is close
,TCP/IP server has received 131072 bytes of data
,TCP/IP server has received 262144 bytes of data
,TCP/IP server has received 306600 bytes of data
,CLIENT is data received : 140000
,TCP/IP server has received 337260 bytes of data
,TCP/IP server has received 372300 bytes of data
,TCP/IP server has received 407198 bytes of data
,TCP/IP server has received 446760 bytes of data
,TCP/IP server has received 497130 bytes of data
,TCP/IP server has received 538740 bytes of data
,TCP/IP server has received 584730 bytes of data
,TCP/IP server has received 626340 bytes of data
,TCP/IP server has received 663570 bytes of data
,TCP/IP server has received 694230 bytes of data
,TCP/IP server has received 751170 bytes of data
,TCP/IP server has received 801398 bytes of data
,CLIENT is data received : 140000
,TCP/IP server has received 847530 bytes of data
,TCP/IP server has received 908850 bytes of data
,TCP/IP server has received 965790 bytes of data
,TCP/IP server has received 970002 bytes of data
,2015-11-19 10:50:33.756 ThaliTest[933:610893] server session: connected
2015-11-19 10:50:33.757 ThaliTest[933:610893] server session: stateChange:1->2 Apple-IpadAir2-1_PT6621
,2015-11-19 10:50:33.761 ThaliTest[933:609867] server relay: connected (to port: 55041)
,TCP/IP server connected
,TCP/IP server has received 2190 bytes of data
,TCP/IP server has received 32850 bytes of data
,TCP/IP server has received 59130 bytes of data
,TCP/IP server has received 78840 bytes of data
,TCP/IP server has received 100740 bytes of data
,TCP/IP server has received 127020 bytes of data
,TCP/IP server has received 153300 bytes of data
,TCP/IP server has received 194910 bytes of data
,TCP/IP server has received 232140 bytes of data
,TCP/IP server has received 269370 bytes of data
,TCP/IP server has received 302220 bytes of data
,TCP/IP server has received 337260 bytes of data
,TCP/IP server has received 367920 bytes of data
,TCP/IP server has received 392010 bytes of data
,TCP/IP server has received 420480 bytes of data
,TCP/IP server has received 462090 bytes of data
,TCP/IP server has received 490418 bytes of data
,TCP/IP server has received 547500 bytes of data
,TCP/IP server has received 578160 bytes of data
,TCP/IP server has received 619770 bytes of data
,TCP/IP server has received 654810 bytes of data
,TCP/IP server has received 696420 bytes of data
,TCP/IP server has received 733650 bytes of data
,TCP/IP server has received 779640 bytes of data
,TCP/IP server has received 840960 bytes of data
,TCP/IP server has received 880002 bytes of data
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,----------------- closeClientSocket
2015-11-19 10:50:41.263 ThaliTest[933:609867] client: socket closed
CLIENT is closed
,2015-11-19 10:50:41.263 ThaliTest[933:609867] client relay: socket disconnected
,2015-11-19 10:50:41.264 ThaliTest[933:609867] client relay: 0x1baa57a0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1ba67270 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:50:41.265 ThaliTest[933:609867] client session: socket closed: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:41.265 ThaliTest[933:609867] client session: onLinkFailure: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:41.266 ThaliTest[933:609867] client session: disconnect
,2015-11-19 10:50:41.266 ThaliTest[933:609867] client session: stateChange:2->0 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:41.268 ThaliTest[933:609867] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:42.142 ThaliTest[933:610890] server session: not connected Apple-Iphone5s-1_PT9462
,2015-11-19 10:50:44.827 ThaliTest[933:610838] server session: not connected Apple-IpadAir2-1_PT6621
,re-try now : Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:51.281 ThaliTest[933:610001] jxcore: disconnect
2015-11-19 10:50:51.282 ThaliTest[933:610001] jxcore: disconnect: fail
Connect (retry count 4) to peer Apple-Iphone5s-1_PT9462.AiaXgQ== with availability status: true
do connect now
2015-11-19 10:50:51.284 ThaliTest[933:610001] jxcore: connect Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:51.284 ThaliTest[933:610001] client session: connect
2015-11-19 10:50:51.285 ThaliTest[933:610001] client session: stateChange:0->1 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:52.091 ThaliTest[933:609867] multipeer session: reset timer
2015-11-19 10:50:52.092 ThaliTest[933:609867] multipeer session: stop timer
2015-11-19 10:50:52.093 ThaliTest[933:609867] multipeer session: start timer: 0x1bea2840
2015-11-19 ,10:50:52.094 ThaliTest[933:609867] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9462)
2015-11-19 10:50:52.094 ThaliTest[933:609867] server session: disconnect
2015-11-19 10:50:52.094 ThaliTest[933:609867] server session: stateChange:2->0 ,Apple-Iphone5s-1_PT9462
2015-11-19 10:50:52.098 ThaliTest[933:609867] server session: connect
2015-11-19 10:50:52.098 ThaliTest[933:609867] server session: stateChange:0->1 Apple-Iphone5s-1_PT9462
TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:50:52.116 ThaliTest[933:609867] server: accepting invitation Apple-Iphone5s-1_PT9462
,2015-11-19 10:50:53.910 ThaliTest[933:610900] client session: connected
2015-11-19 10:50:53.910 ThaliTest[933:610900] client session: stateChange:1->2 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:53.920 ThaliTest[933:610838] client session: fireConnectCallback: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:50:53.921 ThaliTest[933:610838] jxcore: connect: success
CLIENT connected to 55069, error: null
CLIENT starting client 
,2015-11-19 10:50:53.926 ThaliTest[933:609867] client: relay established
2015-11-19 10:50:53.926 ThaliTest[933:609867] client: new accepted socket: 0x1bba3160
,CLIENT now sending 860000 bytes of data
,2015-11-19 10:50:54.280 ThaliTest[933:610838] server session: connected
2015-11-19 10:50:54.280 ThaliTest[933:610838] server session: stateChange:1->2 Apple-Iphone5s-1_PT9462
,2015-11-19 10:50:54.291 ThaliTest[933:609867] server relay: connected (to port: 55041)
,TCP/IP server connected
,TCP/IP server has received 15330 bytes of data
,TCP/IP server has received 45990 bytes of data
,TCP/IP server has received 65700 bytes of data
,TCP/IP server has received 87600 bytes of data
,TCP/IP server has received 111690 bytes of data
,TCP/IP server has received 142350 bytes of data
,TCP/IP server has received 166440 bytes of data
,TCP/IP server has received 201480 bytes of data
,TCP/IP server has received 229950 bytes of data
,TCP/IP server has received 238710 bytes of data
,TCP/IP server has received 245280 bytes of data
2015-11-19 10:50:55.290 ThaliTest[933:609867] multipeer session: reset timer
2015-11-19 10:50:55.291 ThaliTest[933:609867] multipeer session: stop timer
2015-11-19 10:50:55.291 ThaliTest[933:609867] multip,eer session: start timer: 0x1bea2840
2015-11-19 10:50:55.292 ThaliTest[933:609867] server: disconnecting to refresh session (Apple-IpadAir2-1_PT6621)
2015-11-19 10:50:55.293 ThaliTest[933:609867] server session: disconnect
2015-11-19 10:50:55.293 ThaliT,est[933:609867] server session: stateChange:2->0 Apple-IpadAir2-1_PT6621
,TCP/IP server is ended
2015-11-19 10:50:55.315 ThaliTest[933:609867] server session: connect
2015-11-19 10:50:55.315 ThaliTest[933:609867] server session: stateChange:0->1 Apple-IpadAir2-1_PT6621
TCP/IP server is close
,2015-11-19 10:50:55.331 ThaliTest[933:609867] server: accepting invitation Apple-IpadAir2-1_PT6621
,TCP/IP server has received 247470 bytes of data
,TCP/IP server has received 251850 bytes of data
,TCP/IP server has received 282510 bytes of data
,TCP/IP server has received 324120 bytes of data
,TCP/IP server has received 348210 bytes of data
,TCP/IP server has received 383250 bytes of data
,TCP/IP server has received 411720 bytes of data
,TCP/IP server has received 446760 bytes of data
,TCP/IP server has received 483990 bytes of data
,TCP/IP server has received 525600 bytes of data
,TCP/IP server has received 562830 bytes of data
,TCP/IP server has received 597870 bytes of data
,TCP/IP server has received 643860 bytes of data
,TCP/IP server has received 692040 bytes of data
,TCP/IP server has received 740220 bytes of data
,TCP/IP server has received 775260 bytes of data
,CLIENT is data received : 140000
,TCP/IP server has received 814680 bytes of data
,TCP/IP server has received 867240 bytes of data
,TCP/IP server has received 937320 bytes of data
,TCP/IP server has received 939510 bytes of data
,TCP/IP server has received 940002 bytes of data
,2015-11-19 10:50:57.881 ThaliTest[933:610944] server session: connected
2015-11-19 10:50:57.882 ThaliTest[933:610944] server session: stateChange:1->2 Apple-IpadAir2-1_PT6621
,2015-11-19 10:50:57.887 ThaliTest[933:609867] server relay: connected (to port: 55041)
TCP/IP server connected
,TCP/IP server has received 2190 bytes of data
,TCP/IP server has received 92444 bytes of data
,TCP/IP server has received 148920 bytes of data
,TCP/IP server has received 173010 bytes of data
,TCP/IP server has received 199290 bytes of data
,TCP/IP server has received 219000 bytes of data
,TCP/IP server has received 238710 bytes of data
,TCP/IP server has received 258420 bytes of data
,TCP/IP server has received 286890 bytes of data
,TCP/IP server has received 310980 bytes of data
,TCP/IP server has received 339450 bytes of data
,TCP/IP server has received 367920 bytes of data
,TCP/IP server has received 396390 bytes of data
,TCP/IP server has received 427050 bytes of data
,TCP/IP server has received 457710 bytes of data
,TCP/IP server has received 486180 bytes of data
,TCP/IP server has received 510270 bytes of data
,TCP/IP server has received 545310 bytes of data
,TCP/IP server has received 580350 bytes of data
,TCP/IP server has received 608820 bytes of data
,TCP/IP server has received 650430 bytes of data
,TCP/IP server has received 689850 bytes of data
,TCP/IP server has received 748980 bytes of data
,TCP/IP server has received 788258 bytes of data
,TCP/IP server has received 840002 bytes of data
,Receiving data timeout now
CLIENT closeClientSocket
,2015-11-19 10:51:04.368 ThaliTest[933:609867] client: socket closed
CLIENT Stop now
Stop data retrieving timer
2015-11-19 10:51:04.369 ThaliTest[933:609867] client relay: socket disconnected
2015-11-19 10:51:04.369 ThaliTest[933:609867] client relay: 0,x1bba3160 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bc0c100 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:51:04.370 ThaliTest[933:609867] client session: socket ,closed: Apple-Iphone5s-1_PT9462.AiaXgQ==
CLIENT Stop now
2015-11-19 10:51:04.370 ThaliTest[933:609867] client session: onLinkFailure: Apple-Iphone5s-1_PT9462.AiaXgQ==
---- round done--------
2015-11-19 10:51:04.371 ThaliTest[933:609867] client session:, disconnect
2015-11-19 10:51:04.373 ThaliTest[933:609867] client session: stateChange:2->0 Apple-Iphone5s-1_PT9462.AiaXgQ==
device[2]: Apple-IpadAir2-1_PT6621.ucYn4g==
----------------- closeClientSocket
CLIENT is closed
2015-11-19 10:51:04.376 ThaliT,est[933:609867] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:51:05.812 ThaliTest[933:610838] server session: not connected Apple-Iphone5s-1_PT9462
,2015-11-19 10:51:08.938 ThaliTest[933:610890] server session: not connected Apple-IpadAir2-1_PT6621
,2015-11-19 10:51:09.381 ThaliTest[933:610001] jxcore: disconnect
2015-11-19 10:51:09.381 ThaliTest[933:610001] jxcore: disconnect: fail
Connect (retry count 0) to peer Apple-IpadAir2-1_PT6621.ucYn4g== with availability status: true
do connect now
,2015-11-19 10:51:09.383 ThaliTest[933:610001] jxcore: connect Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:09.384 ThaliTest[933:610001] client session: connect
2015-11-19 10:51:09.385 ThaliTest[933:610001] client session: stateChange:0->1 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:25.293 ThaliTest[933:609867] multipeer session: restart
,2015-11-19 10:51:25.310 ThaliTest[933:609867] client: found peer: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:25.314 ThaliTest[933:609867] client: found peer: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:51:42.392 ThaliTest[933:611022] client session: not connected Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:42.392 ThaliTest[933:611022] client session: onLinkFailure: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:42.393 ThaliTest[9,33:611022] client session: disconnect
2015-11-19 10:51:42.393 ThaliTest[933:611022] client session: stateChange:1->0 Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:42.394 ThaliTest[933:611022] client session: fireConnectCallback: Apple-IpadAir2-1_PT66,21.ucYn4g==
2015-11-19 10:51:42.394 ThaliTest[933:611022] jxcore: connect: fail: Peer disconnected
,CLIENT connected to 0, error: Peer disconnected
CLIENT Can not Connect: Peer disconnected
tryAgain afer: 5000 ms.
,re-try now : Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:52.416 ThaliTest[933:610001] jxcore: disconnect
2015-11-19 10:51:52.417 ThaliTest[933:610001] jxcore: disconnect: fail
Connect (retry count 1) to peer Apple-IpadAir2-1_PT6621.ucYn4g== with availability status: true
do connect now
,2015-11-19 10:51:52.419 ThaliTest[933:610001] jxcore: connect Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:52.420 ThaliTest[933:610001] client session: connect
2015-11-19 10:51:52.421 ThaliTest[933:610001] client session: stateChange:0->1 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:55.063 ThaliTest[933:611052] client session: connected
,2015-11-19 10:51:55.064 ThaliTest[933:611052] client session: stateChange:1->2 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:55.068 ThaliTest[933:611048] client session: fireConnectCallback: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:55.069 ThaliTest[933:611048] jxcore: connect: success
CLIENT connected to 55076, error: null
CLIENT starting client 
,2015-11-19 10:51:55.074 ThaliTest[933:609867] client: relay established
2015-11-19 10:51:55.075 ThaliTest[933:609867] client: new accepted socket: 0x17689ea0
,CLIENT now sending 1000000 bytes of data
,2015-11-19 10:51:55.293 ThaliTest[933:609867] multipeer session: restart
,2015-11-19 10:51:55.300 ThaliTest[933:609867] client: found peer: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:55.300 ThaliTest[933:609867] client: found peer: Apple-Iphone5s-1_PT9462.AiaXgQ==
,CLIENT is data received : 10000
,CLIENT is data received : 10000
,CLIENT is data received : 10000
,CLIENT is data received : 20000
,CLIENT is data received : 30000
,CLIENT is data received : 40000
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
----------------- closeClientSocket
2015-11-19 10:52:05.733 ThaliTest[933:609867] client: socket closed
2015-11-19 10:52:05.734 ThaliTest[933:609867] client relay: socket disconnected
,2015-11-19 10:52:05.734 ThaliTest[933:609867] client relay: 0x17689ea0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1758b2f0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:52:05.735 ThaliTest[933:609867] client session: socket closed: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:05.735 ThaliTest[933:609867] client session: onLinkFailure: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:05.736 ThaliTest[933:609867] client session: disconnect
,2015-11-19 10:52:05.737 ThaliTest[933:609867] client session: stateChange:2->0 Apple-IpadAir2-1_PT6621.ucYn4g==
,CLIENT is closed
,2015-11-19 10:52:05.740 ThaliTest[933:609867] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT6621.ucYn4g==
,re-try now : Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:15.733 ThaliTest[933:610001] jxcore: disconnect
2015-11-19 10:52:15.734 ThaliTest[933:610001] jxcore: disconnect: fail
Connect (retry count 2) to peer Apple-IpadAir2-1_PT6621.ucYn4g== with availability status: true
do connect now
,2015-11-19 10:52:15.735 ThaliTest[933:610001] jxcore: connect Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:15.736 ThaliTest[933:610001] client session: connect
,2015-11-19 10:52:15.737 ThaliTest[933:610001] client session: stateChange:0->1 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:18.617 ThaliTest[933:611048] client session: connected
2015-11-19 10:52:18.618 ThaliTest[933:611048] client session: stateChange:1->2 Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:18.619 ThaliTest[933:611048] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:18.620 ThaliTest[933:611048] jxcore: connect: success
CLIENT connected to 55080, error: null
CLIENT starting client 
,2015-11-19 10:52:18.626 ThaliTest[933:609867] client: relay established
2015-11-19 10:52:18.626 ThaliTest[933:609867] client: new accepted socket: 0x1bbc3180
,CLIENT now sending 960000 bytes of data
,CLIENT is data received : 40000
,CLIENT is data received : 40000
,CLIENT is data received : 50000
,CLIENT is data received : 60000
,CLIENT is data received : 70000
,CLIENT is data received : 80000
,2015-11-19 10:52:25.291 ThaliTest[933:609867] multipeer session: restart
,2015-11-19 10:52:25.306 ThaliTest[933:609867] client: found peer: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:25.308 ThaliTest[933:609867] client: found peer: Apple-Iphone5s-1_PT9462.AiaXgQ==
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:52:29.279 ThaliTest[933:609867] client: socket closed
----------------- closeClientSocket
2015-11-19 10:52:29.280 ThaliTest[933:609867] client relay: socket disconnected
CLIENT is closed
,2015-11-19 10:52:29.281 ThaliTest[933:609867] client relay: 0x1bbc3180 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x176bde50 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:52:29.281 ThaliTest[933:609867] client session: socket closed: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:29.282 ThaliTest[933:609867] client session: onLinkFailure: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:29.283 ThaliTest[933:609867] client session: disconnect
,2015-11-19 10:52:29.283 ThaliTest[933:609867] client session: stateChange:2->0 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:29.286 ThaliTest[933:609867] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT6621.ucYn4g==
,re-try now : Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:39.303 ThaliTest[933:610001] jxcore: disconnect
2015-11-19 10:52:39.304 ThaliTest[933:610001] jxcore: disconnect: fail
Connect (retry count 3) to peer Apple-IpadAir2-1_PT6621.ucYn4g== with availability status: true
do connect now
,2015-11-19 10:52:39.306 ThaliTest[933:610001] jxcore: connect Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:39.307 ThaliTest[933:610001] client session: connect
2015-11-19 10:52:39.307 ThaliTest[933:610001] client session: stateChange:0->1 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:43.301 ThaliTest[933:611141] client session: connected
2015-11-19 10:52:43.302 ThaliTest[933:611141] client session: stateChange:1->2 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:43.307 ThaliTest[933:611122] client session: fireConnectCallback: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:43.308 ThaliTest[933:611122] jxcore: connect: success
CLIENT connected to 55084, error: null
CLIENT starting client 
,2015-11-19 10:52:43.312 ThaliTest[933:609867] client: relay established
2015-11-19 10:52:43.313 ThaliTest[933:609867] client: new accepted socket: 0x1be46a60
,CLIENT now sending 920000 bytes of data
,CLIENT is data received : 90000
,CLIENT is data received : 90000
,CLIENT is data received : 90000
,CLIENT is data received : 100000
,CLIENT is data received : 110000
,CLIENT is data received : 120000
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
----------------- closeClientSocket
2015-11-19 10:52:53.943 ThaliTest[933:609867] client: socket closed
CLIENT is closed
2015-11-19 10:52:53.943 ThaliTest[933:609867] client relay: socket disconnected
,2015-11-19 10:52:53.944 ThaliTest[933:609867] client relay: 0x1be46a60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bad67c0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:52:53.944 ThaliTest[933:609867] client session: socket closed: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:53.945 ThaliTest[933:609867] client session: onLinkFailure: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:53.945 ThaliTest[933:609867] client session: disconnect
,2015-11-19 10:52:53.946 ThaliTest[933:609867] client session: stateChange:2->0 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:53.949 ThaliTest[933:609867] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:55.291 ThaliTest[933:609867] multipeer session: restart
,2015-11-19 10:52:55.304 ThaliTest[933:609867] client: found peer: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:55.305 ThaliTest[933:609867] client: found peer: Apple-Iphone5s-1_PT9462.AiaXgQ==
,re-try now : Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:53:03.951 ThaliTest[933:610001] jxcore: disconnect
2015-11-19 10:53:03.952 ThaliTest[933:610001] jxcore: disconnect: fail
Connect (retry count 4) to peer Apple-IpadAir2-1_PT6621.ucYn4g== with availability status: true
do connect now
,2015-11-19 10:53:03.953 ThaliTest[933:610001] jxcore: connect Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:53:03.954 ThaliTest[933:610001] client session: connect
,2015-11-19 10:53:03.955 ThaliTest[933:610001] client session: stateChange:0->1 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:53:07.869 ThaliTest[933:611182] client session: connected
2015-11-19 10:53:07.870 ThaliTest[933:611182] client session: stateChange:1->2 Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:53:07.873 ThaliTest[933:611182] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:53:07.874 ThaliTest[933:611182] jxcore: connect: success
CLIENT connected to 55088, error: null
CLIENT starting client 
,2015-11-19 10:53:07.879 ThaliTest[933:609867] client: relay established
2015-11-19 10:53:07.879 ThaliTest[933:609867] client: new accepted socket: 0x1b9c6d30
,CLIENT now sending 880000 bytes of data
,CLIENT is data received : 120000
,CLIENT is data received : 120000
,CLIENT is data received : 130000
,CLIENT is data received : 140000
,CLIENT is data received : 150000
,CLIENT is data received : 160000
,Receiving data timeout now
CLIENT closeClientSocket
,CLIENT Stop now
Stop data retrieving timer
2015-11-19 10:53:18.565 ThaliTest[933:609867] client: socket closed
2015-11-19 10:53:18.566 ThaliTest[933:609867] client relay: socket disconnected
2015-11-19 10:53:18.567 ThaliTest[933:609867] client relay: 0,x1b9c6d30 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bb9d510 {NSLocalizedDescription=Socket closed by remote peer} 
CLIENT Stop now
2015-11-19 10:53:18.567 ThaliTest[933:609867] client, session: socket closed: Apple-IpadAir2-1_PT6621.ucYn4g==
---- round done--------
2015-11-19 10:53:18.568 ThaliTest[933:609867] client session: onLinkFailure: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:53:18.568 ThaliTest[933:609867] client session:, disconnect
weAreDoneNow , resultArray.length: 2
2015-11-19 10:53:18.569 ThaliTest[933:609867] client session: stateChange:2->0 Apple-IpadAir2-1_PT6621.ucYn4g==
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT4558","time":250225,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT9462.AiaXgQ==","time":115450,"result":"DATA-TIMEOUT","connections":5},{"name":"Apple-IpadAir2-1_PT6621.ucYn4g==","time":134191,"result":"DATA-TIMEOUT","connections":5}]}
,2015-11-19 10:53:18.578 ThaliTest[933:609867] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT6621.ucYn4g==
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items
s,endList failed peers count : 2 [100 %]
- Peer ID : Apple-Iphone5s-1_PT9462.AiaXgQ==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6621.ucYn4g==, Tried : 5
sendList never tried peers count : 0 [0 %]
CLIENT Stop now
,----------------- closeClientSocket
,CLIENT is closed
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
,stop current!
,testSendData stopped
,2015-11-19 10:53:18.692 ThaliTest[933:610001] jxcore: stopBroadcasting
,2015-11-19 10:53:18.694 ThaliTest[933:610001] THEMultipeerSession stopping peer
,2015-11-19 10:53:18.695 ThaliTest[933:610001] multipeer session: stop timer
,2015-11-19 10:53:18.697 ThaliTest[933:610001] server session: disconnect
,2015-11-19 10:53:18.698 ThaliTest[933:610001] server session: stateChange:2->0 Apple-IpadAir2-1_PT6621
,2015-11-19 10:53:18.700 ThaliTest[933:610001] server session: disconnect
,2015-11-19 10:53:18.702 ThaliTest[933:610001] server session: stateChange:2->0 Apple-Iphone5s-1_PT9462
,2015-11-19 10:53:18.704 ThaliTest[933:610001] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,TCP/IP server is ended
,TCP/IP server is ended
,TCP/IP server  socket is disconnected
TCP/IP server is close
,TCP/IP server is close
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5s-1_PT9462.AiaXgQ==\",\"time\":115450,\"result\":\"DATA-TIMEOUT\",\"connections\":5},{\"name\":\"Apple,-IpadAir2-1_PT6621.ucYn4g==\",\"time\":134191,\"result\":\"DATA-TIMEOUT\",\"connections\":5}],\"notTriedList\":[]}},\"combined\":{\"sendList\":[]}}","devices":3,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
