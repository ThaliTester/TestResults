#### Test 513350289df1748_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350289df1748/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/901F89CF-1D38-4AFC-98DE-27536E2B4967/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/901F89CF-1D38-4AFC-98DE-27536E2B4967/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350289df1748/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350289df1748/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/81E857FA-4413-4338-A4DA-0C1076DE1924/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51319"
,(lldb)     command script import "/tmp/901F89CF-1D38-4AFC-98DE-27536E2B4967/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 13:37:21.330 ThaliTest[1063:734671] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A4AC7848-D373-446D-B7CA-196884CF19D0/Library/Cookies/Cookies.binarycookies
,2015-11-20 13:37:21.699 ThaliTest[1063:734671] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 13:37:21.700 ThaliTest[1063:734671] Multi-tasking -> Device: YES, App: YES
,2015-11-20 13:37:21.708 ThaliTest[1063:734671] Unlimited access to network resources
,2015-11-20 13:37:21.713 ThaliTest[1063:734671] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 13:37:25.171 ThaliTest[1063:734671] Resetting plugins due to page load.
,2015-11-20 13:37:25.530 ThaliTest[1063:734671] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/81E857FA-4413-4338-A4DA-0C1076DE1924/ThaliTest.app/www/index.html
,2015-11-20 13:37:25.651 ThaliTest[1063:734671] JXcore Cordova plugin initializing
2015-11-20 13:37:25.652 ThaliTest[1063:734798] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT8859
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
found interfaceName: en0
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
-iface: IPv6 is internal : true, has ip: fe80::1
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
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
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
-iface: IPv6 is internal : true, has ip: ::1
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
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"10000000\",\"conReTryTimeout\":\"1000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":,[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 55719
,2015-11-20 13:46:16.951 ThaliTest[1063:734798] jxcore: startBroadcasting
,2015-11-20 13:46:16.966 ThaliTest[1063:734798] server: starting Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:46:16.974 ThaliTest[1063:734798] multipeer session: start timer: 0x19e5afd0
,2015-11-20 13:46:16.981 ThaliTest[1063:734798] THEMultipeerSession initialized peer Apple-Iphone6-1_PT8859
,2015-11-20 13:46:16.983 ThaliTest[1063:734798] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-20T12:46:16.988Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-20 13:46:17.170 ThaliTest[1063:734671] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:17.176Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:17.177Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:17.874 ThaliTest[1063:734671] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6611.klJDeA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:46:17.965 ThaliTest[1063:734671] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT545.qwwthQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tru,e
,2015-11-20 13:46:18.179 ThaliTest[1063:734798] jxcore: disconnect
2015-11-20 13:46:18.180 ThaliTest[1063:734798] jxcore: disconnect: fail
2015-11-20T12:46:18.181Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:18.181Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5s-1_PT7169./ZcTuw== with availability status: true
,2015-11-20T12:46:18.182Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:18.183Z SendDataConnector.js: do connect now
,2015-11-20 13:46:18.184 ThaliTest[1063:734798] jxcore: connect Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:46:18.185 ThaliTest[1063:734798] client session: connect
2015-11-20 13:46:18.185 ThaliTest[1063:734798] client session: stateChange:0->1 Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:19.522 ThaliTest[1063:734671] multipeer session: reset timer
2015-11-20 13:46:19.522 ThaliTest[1063:734671] multipeer session: stop timer
2015-11-20 13:46:19.522 ThaliTest[1063:734671] multipeer session: start timer: 0x19e5afd0
2015-11-20 13:46:19.522 ThaliTest[1063:734671] server session: connect
2015-11-20 13:46:19.522 ThaliTest[1063:734671] server session: stateChange:0->1 Apple-IpadAir2-1_PT545
,2015-11-20 13:46:19.525 ThaliTest[1063:734671] server: accepting invitation Apple-IpadAir2-1_PT545
,2015-11-20 13:46:20.739 ThaliTest[1063:735456] client session: connected
2015-11-20 13:46:20.740 ThaliTest[1063:735456] client session: stateChange:1->2 Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:20.747 ThaliTest[1063:735456] client session: fireConnectCallback: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:46:20.747 ThaliTest[1063:735456] jxcore: connect: success
,2015-11-20T12:46:20.749Z SendDataConnector.js: CLIENT connected to 55723, error: null
,2015-11-20T12:46:20.750Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:46:20.753 ThaliTest[1063:734671] client: relay established
2015-11-20 13:46:20.753 ThaliTest[1063:734671] client: new accepted socket: 0x19e6b2a0
,2015-11-20T12:46:20.766Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:46:23.254 ThaliTest[1063:735462] server session: connected
2015-11-20 13:46:23.255 ThaliTest[1063:735462] server session: stateChange:1->2 Apple-IpadAir2-1_PT545
,2015-11-20 13:46:23.263 ThaliTest[1063:734671] server relay: connected (to port: 55719)
,2015-11-20T12:46:25.053Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:25.197Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:46:25.797Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:25.798Z SendDataConnector.js: CLIENT is data received : 300000
,2015-11-20T12:46:25.918Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:25.919Z SendDataConnector.js: CLIENT is data received : 520000
,2015-11-20T12:46:26.400Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:26.401Z SendDataConnector.js: CLIENT is data received : 1100000
,2015-11-20T12:46:26.859Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:26.859Z SendDataConnector.js: CLIENT is data received : 1580000
,2015-11-20T12:46:26.876Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:26.877Z SendDataConnector.js: CLIENT is data received : 1610000
,2015-11-20T12:46:27.794Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:27.795Z SendDataConnector.js: CLIENT is data received : 2510000
,2015-11-20T12:46:28.052Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
,2015-11-20T12:46:28.053Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:28.054Z SendDataConnector.js: CLIENT is data received : 2820000
,2015-11-20T12:46:29.498Z SendDataTCPServer.js: TCP/IP server has received 10240 bytes of data
,2015-11-20T12:46:29.500Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:29.501Z SendDataConnector.js: CLIENT is data received : 3850000
,2015-11-20T12:46:30.382Z SendDataTCPServer.js: TCP/IP server has received 12288 bytes of data
,2015-11-20T12:46:30.384Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:30.385Z SendDataConnector.js: CLIENT is data received : 4450000
,2015-11-20T12:46:30.431Z SendDataTCPServer.js: TCP/IP server has received 47104 bytes of data
,2015-11-20T12:46:30.434Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:30.435Z SendDataConnector.js: CLIENT is data received : 4550000
,2015-11-20T12:46:33.024Z SendDataTCPServer.js: TCP/IP server has received 49152 bytes of data
,2015-11-20T12:46:33.043Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:33.044Z SendDataConnector.js: CLIENT is data received : 5650000
,2015-11-20T12:46:35.566Z SendDataTCPServer.js: TCP/IP server has received 51200 bytes of data
,2015-11-20T12:46:35.567Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:35.567Z SendDataConnector.js: CLIENT is data received : 6610000
,2015-11-20T12:46:35.625Z SendDataTCPServer.js: TCP/IP server has received 53248 bytes of data
,2015-11-20T12:46:35.626Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:35.626Z SendDataConnector.js: CLIENT is data received : 6730000
,2015-11-20T12:46:37.862Z SendDataTCPServer.js: TCP/IP server has received 63488 bytes of data
,2015-11-20T12:46:37.864Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:37.864Z SendDataConnector.js: CLIENT is data received : 8110000
,2015-11-20T12:46:40.343Z SendDataTCPServer.js: TCP/IP server has received 180224 bytes of data
2015-11-20T12:46:40.349Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:40.350Z SendDataConnector.js,: CLIENT is data received : 9780000
,2015-11-20T12:46:40.381Z SendDataTCPServer.js: TCP/IP server has received 311296 bytes of data
,2015-11-20T12:46:40.405Z SendDataTCPServer.js: TCP/IP server has received 442368 bytes of data
,2015-11-20T12:46:40.414Z SendDataTCPServer.js: TCP/IP server has received 573440 bytes of data
,2015-11-20T12:46:40.419Z SendDataTCPServer.js: TCP/IP server has received 704512 bytes of data
,2015-11-20T12:46:40.424Z SendDataTCPServer.js: TCP/IP server has received 737280 bytes of data
,2015-11-20T12:46:40.438Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:40.439Z SendDataConnector.js: CLIENT is data received : 9860000
,2015-11-20T12:46:40.452Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:40.454Z SendDataConnector.js: CLIENT is data received : 9890000
,2015-11-20T12:46:40.456Z SendDataTCPServer.js: TCP/IP server has received 778240 bytes of data
,2015-11-20T12:46:40.472Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:40.473Z SendDataConnector.js: CLIENT is data received : 9910000
,2015-11-20T12:46:40.475Z SendDataTCPServer.js: TCP/IP server has received 909312 bytes of data
,2015-11-20T12:46:40.481Z SendDataTCPServer.js: TCP/IP server has received 1019904 bytes of data
,2015-11-20T12:46:40.547Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:40.551Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:46:40.554Z SendDataConnector.js: got all data for this round
,2015-11-20T12:46:40.557Z SendDataConnector.js: CLIENT Stop now
2015-11-20T12:46:40.568Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:46:40.569 ThaliTest[1063:734798] jxcore: disconnect
2015-11-20 13:46:40.569 ThaliTest[1063:734798] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:46:40.569 ThaliTest[1063:734798] client session: disconnect
2015-11-20 13:46:40.569 ThaliTest[1063:734798] client session: stateChange:2->0 Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:40.574 ThaliTest[1063:734798] jxcore: disconnect: success
,2015-11-20T12:46:40.577Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:46:40.587Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:46:40.587Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:46:40.596Z SendDataTCPServer.js: TCP/IP server has received 1150976 bytes of data
,2015-11-20T12:46:40.603Z SendDataTCPServer.js: TCP/IP server has received 1282048 bytes of data
,2015-11-20T12:46:40.609Z SendDataTCPServer.js: TCP/IP server has received 1413120 bytes of data
,2015-11-20T12:46:40.613Z SendDataTCPServer.js: TCP/IP server has received 1544192 bytes of data
,2015-11-20T12:46:40.625Z SendDataTCPServer.js: TCP/IP server has received 1675264 bytes of data
,2015-11-20T12:46:40.641Z SendDataTCPServer.js: TCP/IP server has received 1806336 bytes of data
,2015-11-20T12:46:40.644Z SendDataTCPServer.js: TCP/IP server has received 1937408 bytes of data
,2015-11-20T12:46:40.650Z SendDataTCPServer.js: TCP/IP server has received 2068480 bytes of data
,2015-11-20T12:46:40.653Z SendDataTCPServer.js: TCP/IP server has received 2199552 bytes of data
,2015-11-20T12:46:40.657Z SendDataTCPServer.js: TCP/IP server has received 2330624 bytes of data
,2015-11-20T12:46:40.660Z SendDataTCPServer.js: TCP/IP server has received 2461696 bytes of data
,2015-11-20T12:46:40.665Z SendDataTCPServer.js: TCP/IP server has received 2592768 bytes of data
,2015-11-20T12:46:40.669Z SendDataTCPServer.js: TCP/IP server has received 2723840 bytes of data
,2015-11-20T12:46:40.674Z SendDataTCPServer.js: TCP/IP server has received 2854912 bytes of data
,2015-11-20T12:46:40.677Z SendDataTCPServer.js: TCP/IP server has received 2985984 bytes of data
,2015-11-20T12:46:40.679Z SendDataTCPServer.js: TCP/IP server has received 3117056 bytes of data
,2015-11-20T12:46:40.681Z SendDataTCPServer.js: TCP/IP server has received 3248128 bytes of data
,2015-11-20T12:46:40.684Z SendDataTCPServer.js: TCP/IP server has received 3379200 bytes of data
,2015-11-20T12:46:40.687Z SendDataTCPServer.js: TCP/IP server has received 3510272 bytes of data
,2015-11-20T12:46:40.690Z SendDataTCPServer.js: TCP/IP server has received 3641344 bytes of data
,2015-11-20T12:46:40.692Z SendDataTCPServer.js: TCP/IP server has received 3772416 bytes of data
,2015-11-20T12:46:40.694Z SendDataTCPServer.js: TCP/IP server has received 3903488 bytes of data
,2015-11-20T12:46:40.696Z SendDataTCPServer.js: TCP/IP server has received 4034560 bytes of data
,2015-11-20T12:46:40.699Z SendDataTCPServer.js: TCP/IP server has received 4165632 bytes of data
,2015-11-20T12:46:40.701Z SendDataTCPServer.js: TCP/IP server has received 4296704 bytes of data
,2015-11-20T12:46:40.704Z SendDataTCPServer.js: TCP/IP server has received 4427776 bytes of data
,2015-11-20T12:46:40.707Z SendDataTCPServer.js: TCP/IP server has received 4558848 bytes of data
,2015-11-20T12:46:40.710Z SendDataTCPServer.js: TCP/IP server has received 4689920 bytes of data
,2015-11-20T12:46:40.714Z SendDataTCPServer.js: TCP/IP server has received 4820992 bytes of data
,2015-11-20T12:46:40.718Z SendDataTCPServer.js: TCP/IP server has received 4952064 bytes of data
,2015-11-20T12:46:40.720Z SendDataTCPServer.js: TCP/IP server has received 5083136 bytes of data
,2015-11-20T12:46:40.727Z SendDataTCPServer.js: TCP/IP server has received 5214208 bytes of data
,2015-11-20T12:46:40.781Z SendDataTCPServer.js: TCP/IP server has received 5345280 bytes of data
,2015-11-20T12:46:40.804Z SendDataTCPServer.js: TCP/IP server has received 5476352 bytes of data
,2015-11-20T12:46:40.806Z SendDataTCPServer.js: TCP/IP server has received 5607424 bytes of data
,2015-11-20T12:46:40.809Z SendDataTCPServer.js: TCP/IP server has received 5738496 bytes of data
,2015-11-20T12:46:40.812Z SendDataTCPServer.js: TCP/IP server has received 5869568 bytes of data
,2015-11-20T12:46:40.817Z SendDataTCPServer.js: TCP/IP server has received 6000640 bytes of data
,2015-11-20T12:46:40.820Z SendDataTCPServer.js: TCP/IP server has received 6131712 bytes of data
,2015-11-20T12:46:40.822Z SendDataTCPServer.js: TCP/IP server has received 6262784 bytes of data
,2015-11-20T12:46:40.827Z SendDataTCPServer.js: TCP/IP server has received 6393856 bytes of data
,2015-11-20T12:46:40.832Z SendDataTCPServer.js: TCP/IP server has received 6524928 bytes of data
,2015-11-20T12:46:40.835Z SendDataTCPServer.js: TCP/IP server has received 6656000 bytes of data
,2015-11-20T12:46:40.838Z SendDataTCPServer.js: TCP/IP server has received 6787072 bytes of data
,2015-11-20T12:46:40.843Z SendDataTCPServer.js: TCP/IP server has received 6918144 bytes of data
,2015-11-20T12:46:40.850Z SendDataTCPServer.js: TCP/IP server has received 7049216 bytes of data
,2015-11-20T12:46:40.854Z SendDataTCPServer.js: TCP/IP server has received 7180288 bytes of data
,2015-11-20T12:46:40.858Z SendDataTCPServer.js: TCP/IP server has received 7311360 bytes of data
,2015-11-20T12:46:40.863Z SendDataTCPServer.js: TCP/IP server has received 7442432 bytes of data
,2015-11-20T12:46:40.867Z SendDataTCPServer.js: TCP/IP server has received 7573504 bytes of data
,2015-11-20T12:46:40.870Z SendDataTCPServer.js: TCP/IP server has received 7704576 bytes of data
,2015-11-20T12:46:40.874Z SendDataTCPServer.js: TCP/IP server has received 7835648 bytes of data
,2015-11-20T12:46:40.878Z SendDataTCPServer.js: TCP/IP server has received 7966720 bytes of data
,2015-11-20T12:46:40.881Z SendDataTCPServer.js: TCP/IP server has received 8097792 bytes of data
,2015-11-20T12:46:40.884Z SendDataTCPServer.js: TCP/IP server has received 8228864 bytes of data
,2015-11-20T12:46:40.888Z SendDataTCPServer.js: TCP/IP server has received 8359936 bytes of data
,2015-11-20T12:46:40.892Z SendDataTCPServer.js: TCP/IP server has received 8491008 bytes of data
,2015-11-20T12:46:40.898Z SendDataTCPServer.js: TCP/IP server has received 8622080 bytes of data
,2015-11-20T12:46:40.902Z SendDataTCPServer.js: TCP/IP server has received 8753152 bytes of data
,2015-11-20T12:46:40.907Z SendDataTCPServer.js: TCP/IP server has received 8884224 bytes of data
,2015-11-20T12:46:40.911Z SendDataTCPServer.js: TCP/IP server has received 9015296 bytes of data
,2015-11-20T12:46:40.914Z SendDataTCPServer.js: TCP/IP server has received 9146368 bytes of data
,2015-11-20T12:46:40.917Z SendDataTCPServer.js: TCP/IP server has received 9277440 bytes of data
,2015-11-20T12:46:40.922Z SendDataTCPServer.js: TCP/IP server has received 9408512 bytes of data
,2015-11-20T12:46:40.941Z SendDataTCPServer.js: TCP/IP server has received 9539584 bytes of data
,2015-11-20T12:46:40.945Z SendDataTCPServer.js: TCP/IP server has received 9670656 bytes of data
,2015-11-20T12:46:40.948Z SendDataTCPServer.js: TCP/IP server has received 9801728 bytes of data
,2015-11-20T12:46:40.952Z SendDataTCPServer.js: TCP/IP server has received 9932800 bytes of data
,2015-11-20T12:46:40.954Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20 13:46:41.011 ThaliTest[1063:735462] server session: not connected Apple-IpadAir2-1_PT545
,2015-11-20 13:46:41.596 ThaliTest[1063:734798] jxcore: disconnect
2015-11-20 13:46:41.597 ThaliTest[1063:734798] jxcore: disconnect: fail
2015-11-20T12:46:41.597Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6611.klJDeA=,=
2015-11-20T12:46:41.598Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5-1_PT6611.klJDeA== with availability status: true
2015-11-20T12:46:41.598Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:46:41.598Z SendDataConnector.js: do connect now
2015-11-20 13:46:41.599 ThaliTest[1063:734798] jxcore: connect Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:46:41.600 ThaliTest[1063:734798] client session: connect
,2015-11-20 13:46:41.601 ThaliTest[1063:734798] client session: stateChange:0->1 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:46:49.523 ThaliTest[1063:734671] multipeer session: restart
,2015-11-20 13:46:49.626 ThaliTest[1063:734671] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:46:49.626 ThaliTest[1063:734671] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:46:49.627 ThaliTest[1063:734671] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:47:06.555 ThaliTest[1063:734671] multipeer session: reset timer
2015-11-20 13:47:06.555 ThaliTest[1063:734671] multipeer session: stop timer
2015-11-20 13:47:06.556 ThaliTest[1063:734671] multipeer session: start timer: 0x19e5afd0
2015-11-,20 13:47:06.556 ThaliTest[1063:734671] server session: connect
2015-11-20 13:47:06.557 ThaliTest[1063:734671] server session: stateChange:0->1 Apple-Iphone5-1_PT6611
,2015-11-20 13:47:06.568 ThaliTest[1063:734671] server: accepting invitation Apple-Iphone5-1_PT6611
,2015-11-20 13:47:08.828 ThaliTest[1063:735588] server session: connected
2015-11-20 13:47:08.829 ThaliTest[1063:735588] server session: stateChange:1->2 Apple-Iphone5-1_PT6611
,2015-11-20 13:47:08.833 ThaliTest[1063:734671] server relay: connected (to port: 55719)
,2015-11-20T12:47:08.838Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:47:14.609 ThaliTest[1063:735572] client session: not connected Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:14.609 ThaliTest[1063:735572] client session: onLinkFailure: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:14.610 ThaliTest[1,063:735572] client session: disconnect
2015-11-20 13:47:14.610 ThaliTest[1063:735572] client session: stateChange:1->0 Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:14.611 ThaliTest[1063:735572] client session: fireConnectCallback: Apple-Iphone5-1_PT6,611.klJDeA==
2015-11-20 13:47:14.612 ThaliTest[1063:735572] jxcore: connect: fail: Peer disconnected
,2015-11-20T12:47:14.614Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T12:47:14.614Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-20T12:47:14.616Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:47:15.621Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:15.622Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:16.623 ThaliTest[1063:734798] jxcore: disconnect
2015-11-20 13:47:16.624 ThaliTest[1063:734798] jxcore: disconnect: fail
2015-11-20T12:47:16.625Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6611.klJDeA=,=
2015-11-20T12:47:16.625Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT6611.klJDeA== with availability status: true
2015-11-20T12:47:16.626Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6611.klJDeA==
201,5-11-20T12:47:16.626Z SendDataConnector.js: do connect now
,2015-11-20 13:47:16.626 ThaliTest[1063:734798] jxcore: connect Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:16.627 ThaliTest[1063:734798] client session: connect
,2015-11-20 13:47:16.628 ThaliTest[1063:734798] client session: stateChange:0->1 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:21.327 ThaliTest[1063:735597] client session: connected
2015-11-20 13:47:21.328 ThaliTest[1063:735597] client session: stateChange:1->2 Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:21.331 ThaliTest[1063:735597] client session: fireCo,nnectCallback: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:21.332 ThaliTest[1063:735597] jxcore: connect: success
2015-11-20T12:47:21.333Z SendDataTCPServer.js: TCP/IP server has received 1984 bytes of data
2015-11-20T12:47:21.333Z SendDataConnecto,r.js: CLIENT connected to 55730, error: null
2015-11-20T12:47:21.334Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:47:21.336 ThaliTest[1063:734671] client: relay established
2015-11-20 13:47:21.337 ThaliTest[1063:734671] client: new accepted socket: 0x19800290
,2015-11-20T12:47:21.348Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:47:26.116Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:26.291Z SendDataTCPServer.js: TCP/IP server has received 133056 bytes of data
,2015-11-20T12:47:26.300Z SendDataTCPServer.js: TCP/IP server has received 264128 bytes of data
,2015-11-20T12:47:26.302Z SendDataTCPServer.js: TCP/IP server has received 395200 bytes of data
,2015-11-20T12:47:26.304Z SendDataTCPServer.js: TCP/IP server has received 526272 bytes of data
,2015-11-20T12:47:26.305Z SendDataTCPServer.js: TCP/IP server has received 657344 bytes of data
,2015-11-20T12:47:26.315Z SendDataTCPServer.js: TCP/IP server has received 788416 bytes of data
,2015-11-20T12:47:26.316Z SendDataTCPServer.js: TCP/IP server has received 919488 bytes of data
,2015-11-20T12:47:26.318Z SendDataTCPServer.js: TCP/IP server has received 1050560 bytes of data
,2015-11-20T12:47:26.319Z SendDataTCPServer.js: TCP/IP server has received 1181632 bytes of data
,2015-11-20T12:47:26.321Z SendDataTCPServer.js: TCP/IP server has received 1312704 bytes of data
,2015-11-20T12:47:26.323Z SendDataTCPServer.js: TCP/IP server has received 1443776 bytes of data
,2015-11-20T12:47:26.324Z SendDataTCPServer.js: TCP/IP server has received 1574848 bytes of data
,2015-11-20T12:47:26.325Z SendDataTCPServer.js: TCP/IP server has received 1705920 bytes of data
,2015-11-20T12:47:26.327Z SendDataTCPServer.js: TCP/IP server has received 1836992 bytes of data
,2015-11-20T12:47:26.331Z SendDataTCPServer.js: TCP/IP server has received 1968064 bytes of data
,2015-11-20T12:47:26.332Z SendDataTCPServer.js: TCP/IP server has received 2099136 bytes of data
,2015-11-20T12:47:26.334Z SendDataTCPServer.js: TCP/IP server has received 2109984 bytes of data
,2015-11-20T12:47:26.357Z SendDataTCPServer.js: TCP/IP server has received 2118176 bytes of data
,2015-11-20T12:47:26.450Z SendDataTCPServer.js: TCP/IP server has received 2150944 bytes of data
,2015-11-20T12:47:27.110Z SendDataTCPServer.js: TCP/IP server has received 2202144 bytes of data
,2015-11-20T12:47:27.403Z SendDataTCPServer.js: TCP/IP server has received 2212384 bytes of data
,2015-11-20T12:47:27.710Z SendDataTCPServer.js: TCP/IP server has received 2255392 bytes of data
,2015-11-20T12:47:28.123Z SendDataTCPServer.js: TCP/IP server has received 2374176 bytes of data
,2015-11-20T12:47:28.142Z SendDataTCPServer.js: TCP/IP server has received 2505248 bytes of data
,2015-11-20T12:47:28.147Z SendDataTCPServer.js: TCP/IP server has received 2636320 bytes of data
2015-11-20T12:47:28.151Z SendDataTCPServer.js: TCP/IP server has received 2767392 bytes of data
2015-11-20T12:47:28.156Z SendDataTCPServer.js: TCP/IP server has received 2898464 bytes of data
,2015-11-20T12:47:28.163Z SendDataTCPServer.js: TCP/IP server has received 3029536 bytes of data
,2015-11-20T12:47:28.168Z SendDataTCPServer.js: TCP/IP server has received 3136032 bytes of data
,2015-11-20T12:47:28.188Z SendDataTCPServer.js: TCP/IP server has received 3267104 bytes of data
,2015-11-20T12:47:28.196Z SendDataTCPServer.js: TCP/IP server has received 3398176 bytes of data
,2015-11-20T12:47:28.200Z SendDataTCPServer.js: TCP/IP server has received 3529248 bytes of data
,2015-11-20T12:47:28.203Z SendDataTCPServer.js: TCP/IP server has received 3660320 bytes of data
,2015-11-20T12:47:28.207Z SendDataTCPServer.js: TCP/IP server has received 3720992 bytes of data
,2015-11-20T12:47:28.832Z SendDataTCPServer.js: TCP/IP server has received 3745568 bytes of data
,2015-11-20T12:47:29.474Z SendDataTCPServer.js: TCP/IP server has received 3747616 bytes of data
,2015-11-20T12:47:29.799Z SendDataTCPServer.js: TCP/IP server has received 3749664 bytes of data
,2015-11-20T12:47:30.038Z SendDataTCPServer.js: TCP/IP server has received 3815200 bytes of data
,2015-11-20T12:47:30.323Z SendDataTCPServer.js: TCP/IP server has received 3817248 bytes of data
,2015-11-20T12:47:30.337Z SendDataTCPServer.js: TCP/IP server has received 3821344 bytes of data
,2015-11-20T12:47:30.518Z SendDataTCPServer.js: TCP/IP server has received 3823392 bytes of data
,2015-11-20T12:47:31.064Z SendDataTCPServer.js: TCP/IP server has received 3931936 bytes of data
,2015-11-20T12:47:31.265Z SendDataTCPServer.js: TCP/IP server has received 3933984 bytes of data
,2015-11-20T12:47:31.323Z SendDataTCPServer.js: TCP/IP server has received 3956512 bytes of data
,2015-11-20T12:47:31.768Z SendDataTCPServer.js: TCP/IP server has received 3958560 bytes of data
2015-11-20T12:47:31.769Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:31.771Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-20T12:47:32.443Z SendDataTCPServer.js: TCP/IP server has received 3970848 bytes of data
,2015-11-20T12:47:32.459Z SendDataTCPServer.js: TCP/IP server has received 4101920 bytes of data
,2015-11-20T12:47:32.466Z SendDataTCPServer.js: TCP/IP server has received 4232992 bytes of data
2015-11-20T12:47:32.472Z SendDataTCPServer.js: TCP/IP server has received 4329248 bytes of data
,2015-11-20T12:47:32.494Z SendDataTCPServer.js: TCP/IP server has received 4460320 bytes of data
,2015-11-20T12:47:32.500Z SendDataTCPServer.js: TCP/IP server has received 4591392 bytes of data
,2015-11-20T12:47:32.504Z SendDataTCPServer.js: TCP/IP server has received 4636448 bytes of data
,2015-11-20T12:47:32.520Z SendDataTCPServer.js: TCP/IP server has received 4747040 bytes of data
,2015-11-20T12:47:32.537Z SendDataTCPServer.js: TCP/IP server has received 4878112 bytes of data
,2015-11-20T12:47:32.542Z SendDataTCPServer.js: TCP/IP server has received 5009184 bytes of data
,2015-11-20T12:47:32.546Z SendDataTCPServer.js: TCP/IP server has received 5140256 bytes of data
2015-11-20T12:47:32.549Z SendDataTCPServer.js: TCP/IP server has received 5158688 bytes of data
,2015-11-20T12:47:32.562Z SendDataTCPServer.js: TCP/IP server has received 5289760 bytes of data
,2015-11-20T12:47:32.579Z SendDataTCPServer.js: TCP/IP server has received 5420832 bytes of data
,2015-11-20T12:47:32.583Z SendDataTCPServer.js: TCP/IP server has received 5492512 bytes of data
,2015-11-20T12:47:32.598Z SendDataTCPServer.js: TCP/IP server has received 5623584 bytes of data
,2015-11-20T12:47:32.603Z SendDataTCPServer.js: TCP/IP server has received 5754656 bytes of data
,2015-11-20T12:47:32.605Z SendDataTCPServer.js: TCP/IP server has received 5885728 bytes of data
,2015-11-20T12:47:32.609Z SendDataTCPServer.js: TCP/IP server has received 6016800 bytes of data
,2015-11-20T12:47:32.612Z SendDataTCPServer.js: TCP/IP server has received 6035232 bytes of data
,2015-11-20T12:47:32.629Z SendDataTCPServer.js: TCP/IP server has received 6166304 bytes of data
,2015-11-20T12:47:32.632Z SendDataTCPServer.js: TCP/IP server has received 6297376 bytes of data
,2015-11-20T12:47:32.635Z SendDataTCPServer.js: TCP/IP server has received 6428448 bytes of data
,2015-11-20T12:47:32.637Z SendDataTCPServer.js: TCP/IP server has received 6559520 bytes of data
,2015-11-20T12:47:32.640Z SendDataTCPServer.js: TCP/IP server has received 6574976 bytes of data
,2015-11-20T12:47:32.651Z SendDataTCPServer.js: TCP/IP server has received 6575968 bytes of data
,2015-11-20T12:47:32.663Z SendDataTCPServer.js: TCP/IP server has received 6605728 bytes of data
,2015-11-20T12:47:32.702Z SendDataTCPServer.js: TCP/IP server has received 6623584 bytes of data
,2015-11-20T12:47:32.716Z SendDataTCPServer.js: TCP/IP server has received 6625568 bytes of data
,2015-11-20T12:47:32.727Z SendDataTCPServer.js: TCP/IP server has received 6659296 bytes of data
,2015-11-20T12:47:32.741Z SendDataTCPServer.js: TCP/IP server has received 6696992 bytes of data
,2015-11-20T12:47:32.753Z SendDataTCPServer.js: TCP/IP server has received 6711872 bytes of data
,2015-11-20T12:47:32.767Z SendDataTCPServer.js: TCP/IP server has received 6723776 bytes of data
,2015-11-20T12:47:32.780Z SendDataTCPServer.js: TCP/IP server has received 6730720 bytes of data
,2015-11-20T12:47:32.793Z SendDataTCPServer.js: TCP/IP server has received 6763456 bytes of data
,2015-11-20T12:47:32.808Z SendDataTCPServer.js: TCP/IP server has received 6785280 bytes of data
,2015-11-20T12:47:32.821Z SendDataTCPServer.js: TCP/IP server has received 6796192 bytes of data
,2015-11-20T12:47:32.834Z SendDataTCPServer.js: TCP/IP server has received 6811072 bytes of data
,2015-11-20T12:47:32.848Z SendDataTCPServer.js: TCP/IP server has received 6824960 bytes of data
,2015-11-20T12:47:32.861Z SendDataTCPServer.js: TCP/IP server has received 6853728 bytes of data
,2015-11-20T12:47:32.875Z SendDataTCPServer.js: TCP/IP server has received 6856704 bytes of data
,2015-11-20T12:47:32.912Z SendDataTCPServer.js: TCP/IP server has received 6864640 bytes of data
,2015-11-20T12:47:32.925Z SendDataTCPServer.js: TCP/IP server has received 6879520 bytes of data
,2015-11-20T12:47:32.937Z SendDataTCPServer.js: TCP/IP server has received 6894400 bytes of data
,2015-11-20T12:47:32.951Z SendDataTCPServer.js: TCP/IP server has received 6909280 bytes of data
,2015-11-20T12:47:32.964Z SendDataTCPServer.js: TCP/IP server has received 6924160 bytes of data
,2015-11-20T12:47:32.978Z SendDataTCPServer.js: TCP/IP server has received 6937056 bytes of data
,2015-11-20T12:47:32.992Z SendDataTCPServer.js: TCP/IP server has received 6954912 bytes of data
,2015-11-20T12:47:33.005Z SendDataTCPServer.js: TCP/IP server has received 6978720 bytes of data
,2015-11-20T12:47:33.019Z SendDataTCPServer.js: TCP/IP server has received 7001536 bytes of data
,2015-11-20T12:47:33.031Z SendDataTCPServer.js: TCP/IP server has received 7022368 bytes of data
,2015-11-20T12:47:33.044Z SendDataTCPServer.js: TCP/IP server has received 7046176 bytes of data
,2015-11-20T12:47:33.057Z SendDataTCPServer.js: TCP/IP server has received 7073952 bytes of data
,2015-11-20T12:47:33.071Z SendDataTCPServer.js: TCP/IP server has received 7091808 bytes of data
,2015-11-20T12:47:33.117Z SendDataTCPServer.js: TCP/IP server has received 7097760 bytes of data
,2015-11-20T12:47:33.131Z SendDataTCPServer.js: TCP/IP server has received 7112640 bytes of data
,2015-11-20T12:47:33.145Z SendDataTCPServer.js: TCP/IP server has received 7130496 bytes of data
,2015-11-20T12:47:33.158Z SendDataTCPServer.js: TCP/IP server has received 7154304 bytes of data
,2015-11-20T12:47:33.169Z SendDataTCPServer.js: TCP/IP server has received 7176128 bytes of data
,2015-11-20T12:47:33.182Z SendDataTCPServer.js: TCP/IP server has received 7190016 bytes of data
,2015-11-20T12:47:33.195Z SendDataTCPServer.js: TCP/IP server has received 7206880 bytes of data
,2015-11-20T12:47:33.207Z SendDataTCPServer.js: TCP/IP server has received 7221760 bytes of data
,2015-11-20T12:47:33.221Z SendDataTCPServer.js: TCP/IP server has received 7240608 bytes of data
,2015-11-20T12:47:33.235Z SendDataTCPServer.js: TCP/IP server has received 7252512 bytes of data
,2015-11-20T12:47:33.249Z SendDataTCPServer.js: TCP/IP server has received 7273344 bytes of data
,2015-11-20T12:47:33.261Z SendDataTCPServer.js: TCP/IP server has received 7290208 bytes of data
,2015-11-20T12:47:33.273Z SendDataTCPServer.js: TCP/IP server has received 7313024 bytes of data
,2015-11-20T12:47:33.286Z SendDataTCPServer.js: TCP/IP server has received 7335840 bytes of data
,2015-11-20T12:47:33.299Z SendDataTCPServer.js: TCP/IP server has received 7357664 bytes of data
,2015-11-20T12:47:33.312Z SendDataTCPServer.js: TCP/IP server has received 7376512 bytes of data
,2015-11-20T12:47:33.323Z SendDataTCPServer.js: TCP/IP server has received 7401312 bytes of data
,2015-11-20T12:47:33.336Z SendDataTCPServer.js: TCP/IP server has received 7422144 bytes of data
,2015-11-20T12:47:33.350Z SendDataTCPServer.js: TCP/IP server has received 7435040 bytes of data
,2015-11-20T12:47:33.363Z SendDataTCPServer.js: TCP/IP server has received 7462816 bytes of data
,2015-11-20T12:47:33.377Z SendDataTCPServer.js: TCP/IP server has received 7485632 bytes of data
,2015-11-20T12:47:33.389Z SendDataTCPServer.js: TCP/IP server has received 7500512 bytes of data
,2015-11-20T12:47:33.402Z SendDataTCPServer.js: TCP/IP server has received 7526304 bytes of data
,2015-11-20T12:47:33.415Z SendDataTCPServer.js: TCP/IP server has received 7554080 bytes of data
,2015-11-20T12:47:33.427Z SendDataTCPServer.js: TCP/IP server has received 7572928 bytes of data
,2015-11-20T12:47:33.440Z SendDataTCPServer.js: TCP/IP server has received 7587808 bytes of data
,2015-11-20T12:47:33.454Z SendDataTCPServer.js: TCP/IP server has received 7619552 bytes of data
,2015-11-20T12:47:33.467Z SendDataTCPServer.js: TCP/IP server has received 7628480 bytes of data
,2015-11-20T12:47:33.478Z SendDataTCPServer.js: TCP/IP server has received 7649312 bytes of data
,2015-11-20T12:47:33.490Z SendDataTCPServer.js: TCP/IP server has received 7680064 bytes of data
,2015-11-20T12:47:33.505Z SendDataTCPServer.js: TCP/IP server has received 7699904 bytes of data
,2015-11-20T12:47:33.518Z SendDataTCPServer.js: TCP/IP server has received 7718752 bytes of data
,2015-11-20T12:47:33.519Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:33.520Z SendDataConnector.js: CLIENT is data received : 520000
,2015-11-20T12:47:33.533Z SendDataTCPServer.js: TCP/IP server has received 7725696 bytes of data
,2015-11-20T12:47:33.547Z SendDataTCPServer.js: TCP/IP server has received 7759424 bytes of data
,2015-11-20T12:47:33.559Z SendDataTCPServer.js: TCP/IP server has received 7783232 bytes of data
,2015-11-20T12:47:33.573Z SendDataTCPServer.js: TCP/IP server has received 7792160 bytes of data
,2015-11-20T12:47:33.771Z SendDataTCPServer.js: TCP/IP server has received 7799104 bytes of data
,2015-11-20T12:47:33.783Z SendDataTCPServer.js: TCP/IP server has received 7805056 bytes of data
,2015-11-20T12:47:33.798Z SendDataTCPServer.js: TCP/IP server has received 7812992 bytes of data
,2015-11-20T12:47:33.812Z SendDataTCPServer.js: TCP/IP server has received 7820928 bytes of data
,2015-11-20T12:47:33.825Z SendDataTCPServer.js: TCP/IP server has received 7829856 bytes of data
,2015-11-20T12:47:33.838Z SendDataTCPServer.js: TCP/IP server has received 7842752 bytes of data
,2015-11-20T12:47:33.851Z SendDataTCPServer.js: TCP/IP server has received 7850688 bytes of data
,2015-11-20T12:47:33.865Z SendDataTCPServer.js: TCP/IP server has received 7855648 bytes of data
,2015-11-20T12:47:33.878Z SendDataTCPServer.js: TCP/IP server has received 7867552 bytes of data
,2015-11-20T12:47:33.891Z SendDataTCPServer.js: TCP/IP server has received 7884416 bytes of data
,2015-11-20T12:47:33.904Z SendDataTCPServer.js: TCP/IP server has received 7898304 bytes of data
,2015-11-20T12:47:33.918Z SendDataTCPServer.js: TCP/IP server has received 7914176 bytes of data
,2015-11-20T12:47:33.930Z SendDataTCPServer.js: TCP/IP server has received 7926080 bytes of data
,2015-11-20T12:47:33.943Z SendDataTCPServer.js: TCP/IP server has received 7936992 bytes of data
,2015-11-20T12:47:33.955Z SendDataTCPServer.js: TCP/IP server has received 7948896 bytes of data
,2015-11-20T12:47:33.968Z SendDataTCPServer.js: TCP/IP server has received 7973696 bytes of data
,2015-11-20T12:47:33.980Z SendDataTCPServer.js: TCP/IP server has received 8003456 bytes of data
,2015-11-20T12:47:33.995Z SendDataTCPServer.js: TCP/IP server has received 8012384 bytes of data
,2015-11-20T12:47:34.020Z SendDataTCPServer.js: TCP/IP server has received 8024288 bytes of data
,2015-11-20T12:47:34.034Z SendDataTCPServer.js: TCP/IP server has received 8027264 bytes of data
,2015-11-20T12:47:34.293Z SendDataTCPServer.js: TCP/IP server has received 8033216 bytes of data
,2015-11-20T12:47:34.308Z SendDataTCPServer.js: TCP/IP server has received 8043136 bytes of data
,2015-11-20T12:47:34.323Z SendDataTCPServer.js: TCP/IP server has received 8054048 bytes of data
,2015-11-20T12:47:34.338Z SendDataTCPServer.js: TCP/IP server has received 8066944 bytes of data
,2015-11-20T12:47:34.352Z SendDataTCPServer.js: TCP/IP server has received 8076864 bytes of data
,2015-11-20T12:47:34.366Z SendDataTCPServer.js: TCP/IP server has received 8082816 bytes of data
,2015-11-20T12:47:34.381Z SendDataTCPServer.js: TCP/IP server has received 8086784 bytes of data
,2015-11-20T12:47:34.392Z SendDataTCPServer.js: TCP/IP server has received 8098688 bytes of data
,2015-11-20T12:47:34.407Z SendDataTCPServer.js: TCP/IP server has received 8117536 bytes of data
,2015-11-20T12:47:34.421Z SendDataTCPServer.js: TCP/IP server has received 8134400 bytes of data
,2015-11-20T12:47:34.436Z SendDataTCPServer.js: TCP/IP server has received 8147296 bytes of data
,2015-11-20T12:47:34.450Z SendDataTCPServer.js: TCP/IP server has received 8161184 bytes of data
,2015-11-20T12:47:34.464Z SendDataTCPServer.js: TCP/IP server has received 8173088 bytes of data
,2015-11-20T12:47:34.465Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:34.466Z SendDataConnector.js: CLIENT is data received : 1600000
,2015-11-20T12:47:34.478Z SendDataTCPServer.js: TCP/IP server has received 8179040 bytes of data
,2015-11-20T12:47:34.491Z SendDataTCPServer.js: TCP/IP server has received 8194912 bytes of data
,2015-11-20T12:47:34.506Z SendDataTCPServer.js: TCP/IP server has received 8212768 bytes of data
,2015-11-20T12:47:34.520Z SendDataTCPServer.js: TCP/IP server has received 8227648 bytes of data
,2015-11-20T12:47:34.533Z SendDataTCPServer.js: TCP/IP server has received 8244512 bytes of data
,2015-11-20T12:47:34.547Z SendDataTCPServer.js: TCP/IP server has received 8257408 bytes of data
,2015-11-20T12:47:34.810Z SendDataTCPServer.js: TCP/IP server has received 8258400 bytes of data
,2015-11-20T12:47:34.828Z SendDataTCPServer.js: TCP/IP server has received 8267328 bytes of data
,2015-11-20T12:47:34.841Z SendDataTCPServer.js: TCP/IP server has received 8283200 bytes of data
,2015-11-20T12:47:34.856Z SendDataTCPServer.js: TCP/IP server has received 8301056 bytes of data
,2015-11-20T12:47:34.870Z SendDataTCPServer.js: TCP/IP server has received 8305024 bytes of data
,2015-11-20T12:47:34.884Z SendDataTCPServer.js: TCP/IP server has received 8308000 bytes of data
,2015-11-20T12:47:34.897Z SendDataTCPServer.js: TCP/IP server has received 8319904 bytes of data
,2015-11-20T12:47:34.915Z SendDataTCPServer.js: TCP/IP server has received 8329824 bytes of data
,2015-11-20T12:47:34.928Z SendDataTCPServer.js: TCP/IP server has received 8348672 bytes of data
,2015-11-20T12:47:34.942Z SendDataTCPServer.js: TCP/IP server has received 8374464 bytes of data
,2015-11-20T12:47:34.956Z SendDataTCPServer.js: TCP/IP server has received 8392320 bytes of data
,2015-11-20T12:47:34.970Z SendDataTCPServer.js: TCP/IP server has received 8399264 bytes of data
,2015-11-20T12:47:34.983Z SendDataTCPServer.js: TCP/IP server has received 8405216 bytes of data
,2015-11-20T12:47:34.998Z SendDataTCPServer.js: TCP/IP server has received 8415136 bytes of data
,2015-11-20T12:47:35.009Z SendDataTCPServer.js: TCP/IP server has received 8429024 bytes of data
,2015-11-20T12:47:35.025Z SendDataTCPServer.js: TCP/IP server has received 8446880 bytes of data
,2015-11-20T12:47:35.039Z SendDataTCPServer.js: TCP/IP server has received 8460768 bytes of data
,2015-11-20T12:47:35.052Z SendDataTCPServer.js: TCP/IP server has received 8476640 bytes of data
,2015-11-20T12:47:35.066Z SendDataTCPServer.js: TCP/IP server has received 8493504 bytes of data
,2015-11-20T12:47:35.081Z SendDataTCPServer.js: TCP/IP server has received 8513344 bytes of data
,2015-11-20T12:47:35.094Z SendDataTCPServer.js: TCP/IP server has received 8531200 bytes of data
,2015-11-20T12:47:35.108Z SendDataTCPServer.js: TCP/IP server has received 8541120 bytes of data
,2015-11-20T12:47:35.344Z SendDataTCPServer.js: TCP/IP server has received 8546080 bytes of data
,2015-11-20T12:47:35.358Z SendDataTCPServer.js: TCP/IP server has received 8554016 bytes of data
,2015-11-20T12:47:35.434Z SendDataTCPServer.js: TCP/IP server has received 8560960 bytes of data
,2015-11-20T12:47:35.448Z SendDataTCPServer.js: TCP/IP server has received 8570880 bytes of data
,2015-11-20T12:47:35.461Z SendDataTCPServer.js: TCP/IP server has received 8581792 bytes of data
,2015-11-20T12:47:35.475Z SendDataTCPServer.js: TCP/IP server has received 8591712 bytes of data
,2015-11-20T12:47:35.491Z SendDataTCPServer.js: TCP/IP server has received 8602624 bytes of data
,2015-11-20T12:47:35.505Z SendDataTCPServer.js: TCP/IP server has received 8613536 bytes of data
,2015-11-20T12:47:35.520Z SendDataTCPServer.js: TCP/IP server has received 8624448 bytes of data
,2015-11-20T12:47:35.534Z SendDataTCPServer.js: TCP/IP server has received 8637344 bytes of data
,2015-11-20T12:47:35.548Z SendDataTCPServer.js: TCP/IP server has received 8653216 bytes of data
,2015-11-20T12:47:35.562Z SendDataTCPServer.js: TCP/IP server has received 8671072 bytes of data
,2015-11-20T12:47:35.576Z SendDataTCPServer.js: TCP/IP server has received 8686944 bytes of data
,2015-11-20T12:47:35.590Z SendDataTCPServer.js: TCP/IP server has received 8702816 bytes of data
,2015-11-20T12:47:35.603Z SendDataTCPServer.js: TCP/IP server has received 8718688 bytes of data
,2015-11-20T12:47:35.617Z SendDataTCPServer.js: TCP/IP server has received 8725632 bytes of data
,2015-11-20T12:47:35.863Z SendDataTCPServer.js: TCP/IP server has received 8728608 bytes of data
,2015-11-20T12:47:35.875Z SendDataTCPServer.js: TCP/IP server has received 8736544 bytes of data
,2015-11-20T12:47:35.890Z SendDataTCPServer.js: TCP/IP server has received 8739520 bytes of data
,2015-11-20T12:47:35.902Z SendDataTCPServer.js: TCP/IP server has received 8744480 bytes of data
,2015-11-20T12:47:35.914Z SendDataTCPServer.js: TCP/IP server has received 8753408 bytes of data
,2015-11-20T12:47:35.929Z SendDataTCPServer.js: TCP/IP server has received 8765312 bytes of data
,2015-11-20T12:47:35.944Z SendDataTCPServer.js: TCP/IP server has received 8774240 bytes of data
,2015-11-20T12:47:35.958Z SendDataTCPServer.js: TCP/IP server has received 8783168 bytes of data
,2015-11-20T12:47:35.970Z SendDataTCPServer.js: TCP/IP server has received 8794080 bytes of data
,2015-11-20T12:47:35.983Z SendDataTCPServer.js: TCP/IP server has received 8810944 bytes of data
,2015-11-20T12:47:35.998Z SendDataTCPServer.js: TCP/IP server has received 8826816 bytes of data
,2015-11-20T12:47:36.011Z SendDataTCPServer.js: TCP/IP server has received 8844672 bytes of data
,2015-11-20T12:47:36.023Z SendDataTCPServer.js: TCP/IP server has received 8860544 bytes of data
,2015-11-20T12:47:36.037Z SendDataTCPServer.js: TCP/IP server has received 8877408 bytes of data
,2015-11-20T12:47:36.052Z SendDataTCPServer.js: TCP/IP server has received 8891296 bytes of data
,2015-11-20T12:47:36.066Z SendDataTCPServer.js: TCP/IP server has received 8906176 bytes of data
,2015-11-20T12:47:36.078Z SendDataTCPServer.js: TCP/IP server has received 8921056 bytes of data
,2015-11-20T12:47:36.091Z SendDataTCPServer.js: TCP/IP server has received 8935936 bytes of data
,2015-11-20T12:47:36.103Z SendDataTCPServer.js: TCP/IP server has received 8954784 bytes of data
,2015-11-20T12:47:36.116Z SendDataTCPServer.js: TCP/IP server has received 8975616 bytes of data
,2015-11-20T12:47:36.130Z SendDataTCPServer.js: TCP/IP server has received 8984544 bytes of data
,2015-11-20T12:47:36.388Z SendDataTCPServer.js: TCP/IP server has received 8987520 bytes of data
,2015-11-20T12:47:36.401Z SendDataTCPServer.js: TCP/IP server has received 8994464 bytes of data
,2015-11-20T12:47:36.417Z SendDataTCPServer.js: TCP/IP server has received 9002400 bytes of data
,2015-11-20T12:47:36.430Z SendDataTCPServer.js: TCP/IP server has received 9010336 bytes of data
,2015-11-20T12:47:36.445Z SendDataTCPServer.js: TCP/IP server has received 9017280 bytes of data
,2015-11-20T12:47:36.459Z SendDataTCPServer.js: TCP/IP server has received 9021248 bytes of data
,2015-11-20T12:47:36.475Z SendDataTCPServer.js: TCP/IP server has received 9035136 bytes of data
,2015-11-20T12:47:36.500Z SendDataTCPServer.js: TCP/IP server has received 9040096 bytes of data
,2015-11-20T12:47:36.514Z SendDataTCPServer.js: TCP/IP server has received 9063904 bytes of data
,2015-11-20T12:47:36.528Z SendDataTCPServer.js: TCP/IP server has received 9092672 bytes of data
,2015-11-20T12:47:36.540Z SendDataTCPServer.js: TCP/IP server has received 9097632 bytes of data
,2015-11-20T12:47:36.553Z SendDataTCPServer.js: TCP/IP server has received 9098624 bytes of data
,2015-11-20 13:47:36.557 ThaliTest[1063:734671] multipeer session: restart
2015-11-20T12:47:36.569Z SendDataTCPServer.js: TCP/IP server has received 9103584 bytes of data
,2015-11-20 13:47:36.581 ThaliTest[1063:734671] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:36.582 ThaliTest[1063:734671] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:47:36.582 ThaliTest[1063:734671] client: f,ound peer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:36.585Z SendDataTCPServer.js: TCP/IP server has received 9108672 bytes of data
,2015-11-20T12:47:36.598Z SendDataTCPServer.js: TCP/IP server has received 9121440 bytes of data
,2015-11-20T12:47:36.915Z SendDataTCPServer.js: TCP/IP server has received 9125408 bytes of data
,2015-11-20T12:47:36.928Z SendDataTCPServer.js: TCP/IP server has received 9137312 bytes of data
,2015-11-20T12:47:36.942Z SendDataTCPServer.js: TCP/IP server has received 9143264 bytes of data
,2015-11-20T12:47:36.956Z SendDataTCPServer.js: TCP/IP server has received 9154176 bytes of data
,2015-11-20T12:47:36.971Z SendDataTCPServer.js: TCP/IP server has received 9167072 bytes of data
,2015-11-20T12:47:36.987Z SendDataTCPServer.js: TCP/IP server has received 9172032 bytes of data
,2015-11-20T12:47:37.013Z SendDataTCPServer.js: TCP/IP server has received 9173024 bytes of data
,2015-11-20T12:47:37.024Z SendDataTCPServer.js: TCP/IP server has received 9187904 bytes of data
,2015-11-20T12:47:37.038Z SendDataTCPServer.js: TCP/IP server has received 9202784 bytes of data
,2015-11-20T12:47:37.050Z SendDataTCPServer.js: TCP/IP server has received 9217664 bytes of data
,2015-11-20T12:47:37.064Z SendDataTCPServer.js: TCP/IP server has received 9234528 bytes of data
,2015-11-20T12:47:37.078Z SendDataTCPServer.js: TCP/IP server has received 9253376 bytes of data
,2015-11-20T12:47:37.094Z SendDataTCPServer.js: TCP/IP server has received 9269248 bytes of data
,2015-11-20T12:47:37.107Z SendDataTCPServer.js: TCP/IP server has received 9286112 bytes of data
,2015-11-20T12:47:37.120Z SendDataTCPServer.js: TCP/IP server has received 9304960 bytes of data
,2015-11-20T12:47:37.132Z SendDataTCPServer.js: TCP/IP server has received 9327776 bytes of data
,2015-11-20T12:47:37.146Z SendDataTCPServer.js: TCP/IP server has received 9347616 bytes of data
,2015-11-20T12:47:37.159Z SendDataTCPServer.js: TCP/IP server has received 9364480 bytes of data
,2015-11-20T12:47:37.173Z SendDataTCPServer.js: TCP/IP server has received 9376384 bytes of data
,2015-11-20T12:47:37.432Z SendDataTCPServer.js: TCP/IP server has received 9377376 bytes of data
,2015-11-20T12:47:37.446Z SendDataTCPServer.js: TCP/IP server has received 9384320 bytes of data
,2015-11-20T12:47:37.459Z SendDataTCPServer.js: TCP/IP server has received 9393248 bytes of data
,2015-11-20T12:47:37.472Z SendDataTCPServer.js: TCP/IP server has received 9402176 bytes of data
,2015-11-20T12:47:37.487Z SendDataTCPServer.js: TCP/IP server has received 9415072 bytes of data
,2015-11-20T12:47:37.502Z SendDataTCPServer.js: TCP/IP server has received 9425984 bytes of data
,2015-11-20T12:47:37.516Z SendDataTCPServer.js: TCP/IP server has received 9427968 bytes of data
,2015-11-20T12:47:37.542Z SendDataTCPServer.js: TCP/IP server has received 9433920 bytes of data
,2015-11-20T12:47:37.554Z SendDataTCPServer.js: TCP/IP server has received 9447808 bytes of data
,2015-11-20T12:47:37.567Z SendDataTCPServer.js: TCP/IP server has received 9459712 bytes of data
,2015-11-20T12:47:37.580Z SendDataTCPServer.js: TCP/IP server has received 9474592 bytes of data
,2015-11-20T12:47:37.595Z SendDataTCPServer.js: TCP/IP server has received 9491456 bytes of data
,2015-11-20T12:47:37.610Z SendDataTCPServer.js: TCP/IP server has received 9506336 bytes of data
,2015-11-20T12:47:37.623Z SendDataTCPServer.js: TCP/IP server has received 9521216 bytes of data
,2015-11-20T12:47:37.638Z SendDataTCPServer.js: TCP/IP server has received 9542048 bytes of data
,2015-11-20T12:47:37.651Z SendDataTCPServer.js: TCP/IP server has received 9562880 bytes of data
,2015-11-20T12:47:37.664Z SendDataTCPServer.js: TCP/IP server has received 9581728 bytes of data
,2015-11-20T12:47:37.678Z SendDataTCPServer.js: TCP/IP server has received 9605536 bytes of data
,2015-11-20T12:47:37.693Z SendDataTCPServer.js: TCP/IP server has received 9629344 bytes of data
,2015-11-20T12:47:37.707Z SendDataTCPServer.js: TCP/IP server has received 9648192 bytes of data
,2015-11-20T12:47:37.966Z SendDataTCPServer.js: TCP/IP server has received 9654144 bytes of data
,2015-11-20T12:47:37.981Z SendDataTCPServer.js: TCP/IP server has received 9663072 bytes of data
,2015-11-20T12:47:37.995Z SendDataTCPServer.js: TCP/IP server has received 9672992 bytes of data
,2015-11-20T12:47:38.011Z SendDataTCPServer.js: TCP/IP server has received 9676960 bytes of data
,2015-11-20T12:47:38.036Z SendDataTCPServer.js: TCP/IP server has received 9685888 bytes of data
,2015-11-20T12:47:38.051Z SendDataTCPServer.js: TCP/IP server has received 9698784 bytes of data
,2015-11-20T12:47:38.065Z SendDataTCPServer.js: TCP/IP server has received 9709696 bytes of data
,2015-11-20T12:47:38.079Z SendDataTCPServer.js: TCP/IP server has received 9730528 bytes of data
,2015-11-20T12:47:38.096Z SendDataTCPServer.js: TCP/IP server has received 9758304 bytes of data
,2015-11-20T12:47:38.109Z SendDataTCPServer.js: TCP/IP server has received 9772256 bytes of data
,2015-11-20T12:47:38.121Z SendDataTCPServer.js: TCP/IP server has received 9789056 bytes of data
,2015-11-20T12:47:38.123Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:38.124Z SendDataConnector.js: CLIENT is data received : 1630000
,2015-11-20T12:47:38.138Z SendDataTCPServer.js: TCP/IP server has received 9805920 bytes of data
,2015-11-20T12:47:38.153Z SendDataTCPServer.js: TCP/IP server has received 9822784 bytes of data
,2015-11-20T12:47:38.168Z SendDataTCPServer.js: TCP/IP server has received 9837664 bytes of data
,2015-11-20T12:47:38.181Z SendDataTCPServer.js: TCP/IP server has received 9853536 bytes of data
,2015-11-20T12:47:38.182Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:38.183Z SendDataConnector.js: CLIENT is data received : 1640000
,2015-11-20T12:47:38.196Z SendDataTCPServer.js: TCP/IP server has received 9872384 bytes of data
,2015-11-20T12:47:38.197Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:38.198Z SendDataConnector.js: CLIENT is data received : 1650000
,2015-11-20T12:47:38.613Z SendDataTCPServer.js: TCP/IP server has received 9873376 bytes of data
,2015-11-20T12:47:38.615Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:38.615Z SendDataConnector.js: CLIENT is data received : 1730000
,2015-11-20T12:47:38.629Z SendDataTCPServer.js: TCP/IP server has received 9875360 bytes of data
,2015-11-20T12:47:38.630Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:38.631Z SendDataConnector.js: CLIENT is data received : 1740000
,2015-11-20T12:47:38.745Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:38.747Z SendDataConnector.js: CLIENT is data received : 3390000
,2015-11-20T12:47:39.026Z SendDataTCPServer.js: TCP/IP server has received 9884288 bytes of data
,2015-11-20T12:47:39.029Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:39.030Z SendDataConnector.js: CLIENT is data received : 4990000
,2015-11-20T12:47:39.046Z SendDataTCPServer.js: TCP/IP server has received 9900160 bytes of data
,2015-11-20T12:47:39.050Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:39.051Z SendDataConnector.js: CLIENT is data received : 5720000
,2015-11-20T12:47:39.063Z SendDataTCPServer.js: TCP/IP server has received 9915040 bytes of data
,2015-11-20T12:47:39.079Z SendDataTCPServer.js: TCP/IP server has received 9928928 bytes of data
,2015-11-20T12:47:39.091Z SendDataTCPServer.js: TCP/IP server has received 9938848 bytes of data
,2015-11-20T12:47:39.107Z SendDataTCPServer.js: TCP/IP server has received 9941824 bytes of data
,2015-11-20T12:47:39.121Z SendDataTCPServer.js: TCP/IP server has received 9957696 bytes of data
,2015-11-20T12:47:39.135Z SendDataTCPServer.js: TCP/IP server has received 9976544 bytes of data
,2015-11-20T12:47:39.149Z SendDataTCPServer.js: TCP/IP server has received 9992416 bytes of data
,2015-11-20T12:47:39.163Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20T12:47:39.177Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:39.178Z SendDataConnector.js: CLIENT is data received : 9990000
,2015-11-20 13:47:39.182 ThaliTest[1063:735572] server session: not connected Apple-Iphone5-1_PT6611
,2015-11-20T12:47:49.187Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:47:49.187Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:47:49.188Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:47:49.189Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20 13:47:49.190 ThaliTest[1063:734671] client: socket closed
2015-11-20 13:47:49.191 ThaliTest[1063:734671] client relay: socket disconnected
2015-11-20 13:47:49.191 ThaliTest[1063:734671] client relay: 0x19800290 disconnected with error Error Do,main=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19aedf30 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 13:47:49.192 ThaliTest[1063:734671] client session: socket closed: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:49.192 ThaliTest[1063:734671] client session: onLinkFailure: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:49.193 ThaliTest[1063:734671] client session: disconnect
2015-11-20 13:47:49.193 ThaliTest[1063:734671] client session: stateCh,ange:2->0 Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:49.195 ThaliTest[1063:734671] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:50.192Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:50.192Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:51.199 ThaliTest[1063:734798] jxcore: disconnect
2015-11-20 13:47:51.200 ThaliTest[1063:734798] jxcore: disconnect: fail
2015-11-20T12:47:51.200Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6611.klJDeA=,=
2015-11-20T12:47:51.201Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT6611.klJDeA== with availability status: true
2015-11-20T12:47:51.202Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:51.202Z SendDataConnector.js: do connect now
,2015-11-20 13:47:51.203 ThaliTest[1063:734798] jxcore: connect Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:51.204 ThaliTest[1063:734798] client session: connect
2015-11-20 13:47:51.205 ThaliTest[1063:734798] client session: stateChange:0->1 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:54.004 ThaliTest[1063:735670] client session: connected
2015-11-20 13:47:54.005 ThaliTest[1063:735670] client session: stateChange:1->2 Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:54.007 ThaliTest[1063:735670] client session: fireCo,nnectCallback: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:54.008 ThaliTest[1063:735670] jxcore: connect: success
2015-11-20T12:47:54.009Z SendDataConnector.js: CLIENT connected to 55734, error: null
2015-11-20T12:47:54.009Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:47:54.012 ThaliTest[1063:734671] client: relay established
2015-11-20 13:47:54.013 ThaliTest[1063:734671] client: new accepted socket: 0x199262f0
,2015-11-20T12:47:54.024Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-20T12:47:54.040Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:56.858Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:56.859Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:47:56.859Z SendDataConnector.js: got all data for this round
,2015-11-20T12:47:56.860Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:47:56.860Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:47:56.862 ThaliTest[1063:734798] jxcore: disconnect
2015-11-20 13:47:56.862 ThaliTest[1063:734798] client session: disconnectFromPeer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:56.863 ThaliTest[1063:734798] client session: disconnect
2015-11-20 13:47:56.863 ThaliTest[1063:734798] client session: stateChange:2->0 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:56.868 ThaliTest[1063:734798] jxcore: disconnect: success
2015-11-20T12:47:56.871Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6611.klJDeA==
,---- round done--------
device[3]: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:47:56.874Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:47:56.875Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:47:57.876 ThaliTest[1063:734798] jxcore: disconnect
2015-11-20 13:47:57.876 ThaliTest[1063:734798] jxcore: disconnect: fail
2015-11-20T12:47:57.877Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT545.qwwthQ=,=
,2015-11-20T12:47:57.878Z SendDataConnector.js: Connect (retry count 0) to peer Apple-IpadAir2-1_PT545.qwwthQ== with availability status: true
2015-11-20T12:47:57.878Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:47:57.878Z SendDataConnector.js: do connect now
,2015-11-20 13:47:57.879 ThaliTest[1063:734798] jxcore: connect Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:47:57.880 ThaliTest[1063:734798] client session: connect
2015-11-20 13:47:57.881 ThaliTest[1063:734798] client session: stateChange:0->1 Apple-Ip,adAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:00.760 ThaliTest[1063:735572] client session: connected
2015-11-20 13:48:00.761 ThaliTest[1063:735572] client session: stateChange:1->2 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:00.805 ThaliTest[1063:735572] client session: fireConnectCallback: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:00.805 ThaliTest[1063:735572] jxcore: connect: success
2015-11-20T12:48:00.806Z SendDataConnector.js: CLIENT connected to 55737, error: null
,2015-11-20T12:48:00.807Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:48:00.810 ThaliTest[1063:734671] client: relay established
2015-11-20 13:48:00.811 ThaliTest[1063:734671] client: new accepted socket: 0x19a20d30
,2015-11-20T12:48:00.823Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:48:05.073Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:07.569 ThaliTest[1063:734671] multipeer session: restart
,2015-11-20 13:48:08.462 ThaliTest[1063:734671] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:08.471 ThaliTest[1063:734671] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:48:08.472 ThaliTest[1063:734671] client: f,ound peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:48:15.085Z SendDataConnector.js: Receiving data timeout now
2015-11-20T12:48:15.085Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-20T12:48:15.086Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20T12:48:15.087Z SendDataCon,nector.js: ----------------- closeClientSocket
,2015-11-20 13:48:15.807 ThaliTest[1063:734671] client: socket closed
2015-11-20 13:48:15.808 ThaliTest[1063:734671] client relay: socket disconnected
2015-11-20 13:48:15.808 ThaliTest[1063:734671] client relay: 0x19a20d30 disconnected with error Error Do,main=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x156d8790 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 13:48:15.809 ThaliTest[1063:734671] client session: socket closed: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:15.810 ThaliTest[1063:734671] client session: onLinkFailure: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:15.810 ThaliTest[1063:734671] client session: disconnect
2015-11-20 13:48:15.811 ThaliTest[1063:734671] client session: stateCh,ange:2->0 Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:15.812 ThaliTest[1063:734671] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:48:16.100Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:48:16.100Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:17.113 ThaliTest[1063:734798] jxcore: disconnect
2015-11-20 13:48:17.114 ThaliTest[1063:734798] jxcore: disconnect: fail
2015-11-20T12:48:17.115Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT545.qwwthQ=,=
2015-11-20T12:48:17.115Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT545.qwwthQ== with availability status: true
,2015-11-20T12:48:17.115Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:48:17.116Z SendDataConnector.js: do connect now
,2015-11-20 13:48:17.117 ThaliTest[1063:734798] jxcore: connect Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:17.118 ThaliTest[1063:734798] client session: connect
2015-11-20 13:48:17.118 ThaliTest[1063:734798] client session: stateChange:0->1 Apple-Ip,adAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:19.949 ThaliTest[1063:735572] client session: connected
2015-11-20 13:48:19.950 ThaliTest[1063:735572] client session: stateChange:1->2 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:19.956 ThaliTest[1063:735704] client session: fireConnectCallback: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:19.958 ThaliTest[1063:735704] jxcore: connect: success
,2015-11-20T12:48:19.960Z SendDataConnector.js: CLIENT connected to 55741, error: null
2015-11-20T12:48:19.960Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:48:19.963 ThaliTest[1063:734671] client: relay established
2015-11-20 13:48:19.964 ThaliTest[1063:734671] client: new accepted socket: 0x19a00050
,2015-11-20T12:48:19.976Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:48:24.255Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:48:34.256Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:48:34.257Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:48:34.258Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20T12:48:34.258Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 13:48:34.258 ThaliTest[1063:734671] client: socket closed
2015-11-20 13:48:34.259 ThaliTest[1063:734671] client relay: socket disconnected
,2015-11-20 13:48:34.259 ThaliTest[1063:734671] client relay: 0x19a00050 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x155b3350 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11,-20 13:48:34.260 ThaliTest[1063:734671] client session: socket closed: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:34.260 ThaliTest[1063:734671] client session: onLinkFailure: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:34.261 ThaliTest[1063:734671] client session: disconnect
2015-11-20 13:48:34.262 ThaliTest[1063:734671] client session: stateChange:2->0 Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:34.263 ThaliTest[1063:734671] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:48:35.269Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:48:35.269Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:36.280 ThaliTest[1063:734798] jxcore: disconnect
2015-11-20 13:48:36.280 ThaliTest[1063:734798] jxcore: disconnect: fail
2015-11-20T12:48:36.281Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT545.qwwthQ=,=
2015-11-20T12:48:36.281Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT545.qwwthQ== with availability status: true
2015-11-20T12:48:36.282Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:48:36.282Z SendDataConnector.js: do connect now
2015-11-20 13:48:36.283 ThaliTest[1063:734798] jxcore: connect Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:36.284 ThaliTest[1063:734798] client session: connect
,2015-11-20 13:48:36.284 ThaliTest[1063:734798] client session: stateChange:0->1 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:48:36.558 ThaliTest[1063:734671] multipeer session: restart
,2015-11-20 13:48:36.579 ThaliTest[1063:734671] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:48:36.580 ThaliTest[1063:734671] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:36.582 ThaliTest[1063:734671] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:48:48.712 ThaliTest[1063:734671] client: lost peer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:48:48.713 ThaliTest[1063:734671] client session: onPeerLost: Apple-Iphone5s-1_PT7169./ZcTuw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":false}]
2015-11-20 13:48:48.716 ThaliTest[1063:734671] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==",",peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:48:52.390 ThaliTest[1063:734671] client: lost peer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:48:52.391 ThaliTest[1063:734671] client session: onPeerLost: Apple-Iphone5s-1_PT7169./ZcTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:48:57.756 ThaliTest[1063:734671] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:49:06.554 ThaliTest[1063:734671] multipeer session: restart
,2015-11-20 13:49:06.572 ThaliTest[1063:734671] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:06.574 ThaliTest[1063:734671] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:49:06.575 ThaliTest[1063:734671] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:49:09.289 ThaliTest[1063:735805] client session: not connected Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:09.290 ThaliTest[1063:735805] client session: onLinkFailure: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:09.290 ThaliTest[1063:735805] client session: disconnect
,2015-11-20 13:49:09.292 ThaliTest[1063:735805] client session: stateChange:1->0 Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:09.293 ThaliTest[1063:735805] client session: fireConnectCallback: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:09.293 ThaliTest[1063:735805] jxcore: connect: fail: Peer disconnected
,2015-11-20T12:49:09.295Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T12:49:09.295Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-20T12:49:09.295Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:49:10.302Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:10.303Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:11.307 ThaliTest[1063:734798] jxcore: disconnect
2015-11-20 13:49:11.308 ThaliTest[1063:734798] jxcore: disconnect: fail
2015-11-20T12:49:11.309Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT545.qwwthQ=,=
2015-11-20T12:49:11.309Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT545.qwwthQ== with availability status: true
,2015-11-20T12:49:11.310Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:49:11.310Z SendDataConnector.js: do connect now
,2015-11-20 13:49:11.311 ThaliTest[1063:734798] jxcore: connect Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:11.312 ThaliTest[1063:734798] client session: connect
2015-11-20 13:49:11.312 ThaliTest[1063:734798] client session: stateChange:0->1 Apple-Ip,adAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:12.845 ThaliTest[1063:734671] multipeer session: reset timer
2015-11-20 13:49:12.846 ThaliTest[1063:734671] multipeer session: stop timer
2015-11-20 13:49:12.846 ThaliTest[1063:734671] multipeer session: start timer: 0x19e5afd0
2015-11-,20 13:49:12.847 ThaliTest[1063:734671] server session: connect
2015-11-20 13:49:12.847 ThaliTest[1063:734671] server session: stateChange:0->1 Apple-Iphone5s-1_PT7169
,2015-11-20 13:49:12.857 ThaliTest[1063:734671] server: accepting invitation Apple-Iphone5s-1_PT7169
,2015-11-20 13:49:15.008 ThaliTest[1063:735819] client session: connected
2015-11-20 13:49:15.008 ThaliTest[1063:735819] client session: stateChange:1->2 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:15.034 ThaliTest[1063:735818] client session: fireConnectCallback: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:15.035 ThaliTest[1063:735818] jxcore: connect: success
2015-11-20T12:49:15.036Z SendDataConnector.js: CLIENT connected to 55747, error: null
,2015-11-20T12:49:15.036Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:49:15.039 ThaliTest[1063:734671] client: relay established
2015-11-20 13:49:15.040 ThaliTest[1063:734671] client: new accepted socket: 0x155efd20
,2015-11-20T12:49:15.050Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:49:15.098 ThaliTest[1063:735819] server session: connected
,2015-11-20 13:49:15.098 ThaliTest[1063:735819] server session: stateChange:1->2 Apple-Iphone5s-1_PT7169
,2015-11-20 13:49:15.107 ThaliTest[1063:734671] server relay: connected (to port: 55719)
,2015-11-20 13:49:17.672 ThaliTest[1063:734671] client: lost peer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:49:17.672 ThaliTest[1063:734671] client session: onPeerLost: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:49:19.333Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:19.450Z SendDataTCPServer.js: TCP/IP server connected
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:49:19.457 ThaliTest[1063:734671] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":true}]
,2015-11-20T12:49:20.607Z SendDataTCPServer.js: TCP/IP server has received 2048 bytes of data
,2015-11-20T12:49:20.739Z SendDataTCPServer.js: TCP/IP server has received 133120 bytes of data
,2015-11-20T12:49:20.743Z SendDataTCPServer.js: TCP/IP server has received 197100 bytes of data
,2015-11-20T12:49:20.892Z SendDataTCPServer.js: TCP/IP server has received 328172 bytes of data
,2015-11-20T12:49:20.894Z SendDataTCPServer.js: TCP/IP server has received 335070 bytes of data
,2015-11-20T12:49:21.676Z SendDataTCPServer.js: TCP/IP server has received 337118 bytes of data
,2015-11-20T12:49:21.715Z SendDataTCPServer.js: TCP/IP server has received 339166 bytes of data
,2015-11-20T12:49:24.467Z SendDataTCPServer.js: TCP/IP server has received 341214 bytes of data
,2015-11-20T12:49:25.358Z SendDataTCPServer.js: TCP/IP server has received 361694 bytes of data
,2015-11-20T12:49:25.373Z SendDataTCPServer.js: TCP/IP server has received 443614 bytes of data
,2015-11-20T12:49:25.456Z SendDataTCPServer.js: TCP/IP server has received 490718 bytes of data
,2015-11-20T12:49:25.714Z SendDataTCPServer.js: TCP/IP server has received 507102 bytes of data
,2015-11-20T12:49:26.926Z SendDataTCPServer.js: TCP/IP server has received 509150 bytes of data
,2015-11-20T12:49:29.335Z SendDataConnector.js: Receiving data timeout now
2015-11-20T12:49:29.335Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:49:29.337Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:49:29.337Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20 13:49:30.100 ThaliTest[1063:734671] client: socket closed
2015-11-20 13:49:30.100 ThaliTest[1063:734671] client relay: socket disconnected
2015-11-20 13:49:30.100 ThaliTest[1063:734671] client relay: 0x155efd20 disconnected with error Error Do,main=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x15694300 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 13:49:30.101 ThaliTest[1063:734671] client session: socket closed: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:30.101 ThaliTest[1063:734671] client session: onLinkFailure: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:30.101 ThaliTest[1063:734671] client session: disconnect
2015-11-20 13:49:30.102 ThaliTest[1063:734671] client session: stateCh,ange:2->0 Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:30.103 ThaliTest[1063:734671] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:49:30.118Z SendDataTCPServer.js: TCP/IP server has received 640222 bytes of data
,2015-11-20T12:49:30.164Z SendDataTCPServer.js: TCP/IP server has received 771294 bytes of data
2015-11-20T12:49:30.175Z SendDataTCPServer.js: TCP/IP server has received 902366 bytes of data
2015-11-20T12:49:30.179Z SendDataTCPServer.js: TCP/IP server has, received 1033438 bytes of data
,2015-11-20T12:49:30.188Z SendDataTCPServer.js: TCP/IP server has received 1164510 bytes of data
,2015-11-20T12:49:30.195Z SendDataTCPServer.js: TCP/IP server has received 1295582 bytes of data
,2015-11-20T12:49:30.200Z SendDataTCPServer.js: TCP/IP server has received 1426654 bytes of data
,2015-11-20T12:49:30.203Z SendDataTCPServer.js: TCP/IP server has received 1557726 bytes of data
,2015-11-20T12:49:30.209Z SendDataTCPServer.js: TCP/IP server has received 1688798 bytes of data
,2015-11-20T12:49:30.212Z SendDataTCPServer.js: TCP/IP server has received 1721566 bytes of data
,2015-11-20T12:49:30.236Z SendDataTCPServer.js: TCP/IP server has received 1852638 bytes of data
,2015-11-20T12:49:30.242Z SendDataTCPServer.js: TCP/IP server has received 1983710 bytes of data
,2015-11-20T12:49:30.246Z SendDataTCPServer.js: TCP/IP server has received 2114782 bytes of data
,2015-11-20T12:49:30.249Z SendDataTCPServer.js: TCP/IP server has received 2245854 bytes of data
,2015-11-20T12:49:30.254Z SendDataTCPServer.js: TCP/IP server has received 2358494 bytes of data
,2015-11-20T12:49:30.270Z SendDataTCPServer.js: TCP/IP server has received 2489566 bytes of data
,2015-11-20T12:49:30.273Z SendDataTCPServer.js: TCP/IP server has received 2620638 bytes of data
,2015-11-20T12:49:30.275Z SendDataTCPServer.js: TCP/IP server has received 2714846 bytes of data
,2015-11-20T12:49:30.289Z SendDataTCPServer.js: TCP/IP server has received 2845918 bytes of data
,2015-11-20T12:49:30.293Z SendDataTCPServer.js: TCP/IP server has received 2976990 bytes of data
,2015-11-20T12:49:30.297Z SendDataTCPServer.js: TCP/IP server has received 3030238 bytes of data
,2015-11-20T12:49:30.337Z SendDataTCPServer.js: TCP/IP server has received 3161310 bytes of data
,2015-11-20T12:49:30.361Z SendDataTCPServer.js: TCP/IP server has received 3292382 bytes of data
,2015-11-20T12:49:30.382Z SendDataTCPServer.js: TCP/IP server has received 3423454 bytes of data
,2015-11-20T12:49:30.392Z SendDataTCPServer.js: TCP/IP server has received 3554526 bytes of data
,2015-11-20T12:49:30.398Z SendDataTCPServer.js: TCP/IP server has received 3685598 bytes of data
,2015-11-20T12:49:30.405Z SendDataTCPServer.js: TCP/IP server has received 3816670 bytes of data
,2015-11-20T12:49:30.410Z SendDataTCPServer.js: TCP/IP server has received 3947742 bytes of data
,2015-11-20T12:49:30.418Z SendDataTCPServer.js: TCP/IP server has received 4078814 bytes of data
,2015-11-20T12:49:30.423Z SendDataTCPServer.js: TCP/IP server has received 4209886 bytes of data
,2015-11-20T12:49:30.426Z SendDataTCPServer.js: TCP/IP server has received 4340958 bytes of data
,2015-11-20T12:49:30.432Z SendDataTCPServer.js: TCP/IP server has received 4472030 bytes of data
,2015-11-20T12:49:30.437Z SendDataTCPServer.js: TCP/IP server has received 4603102 bytes of data
,2015-11-20T12:49:30.447Z SendDataTCPServer.js: TCP/IP server has received 4734174 bytes of data
,2015-11-20T12:49:30.453Z SendDataTCPServer.js: TCP/IP server has received 4865246 bytes of data
,2015-11-20T12:49:30.462Z SendDataTCPServer.js: TCP/IP server has received 4996318 bytes of data
,2015-11-20T12:49:30.469Z SendDataTCPServer.js: TCP/IP server has received 5127390 bytes of data
,2015-11-20T12:49:30.476Z SendDataTCPServer.js: TCP/IP server has received 5258462 bytes of data
,2015-11-20T12:49:30.484Z SendDataTCPServer.js: TCP/IP server has received 5389534 bytes of data
,2015-11-20T12:49:30.488Z SendDataTCPServer.js: TCP/IP server has received 5415870 bytes of data
,2015-11-20T12:49:30.507Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20T12:49:30.507Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:30.510Z SendDataTCPServer.js: TCP/IP server has received 5485950 bytes of data
,2015-11-20T12:49:30.535Z SendDataTCPServer.js: TCP/IP server has received 5527560 bytes of data
,2015-11-20T12:49:30.553Z SendDataTCPServer.js: TCP/IP server has received 5573550 bytes of data
,2015-11-20T12:49:30.567Z SendDataTCPServer.js: TCP/IP server has received 5621730 bytes of data
,2015-11-20T12:49:30.586Z SendDataTCPServer.js: TCP/IP server has received 5689620 bytes of data
,2015-11-20T12:49:30.605Z SendDataTCPServer.js: TCP/IP server has received 5757368 bytes of data
,2015-11-20T12:49:30.625Z SendDataTCPServer.js: TCP/IP server has received 5818830 bytes of data
,2015-11-20T12:49:30.640Z SendDataTCPServer.js: TCP/IP server has received 5860440 bytes of data
,2015-11-20T12:49:30.659Z SendDataTCPServer.js: TCP/IP server has received 5899860 bytes of data
,2015-11-20T12:49:30.673Z SendDataTCPServer.js: TCP/IP server has received 5937090 bytes of data
,2015-11-20T12:49:30.686Z SendDataTCPServer.js: TCP/IP server has received 5939280 bytes of data
,2015-11-20T12:49:30.698Z SendDataTCPServer.js: TCP/IP server has received 6015930 bytes of data
,2015-11-20T12:49:30.716Z SendDataTCPServer.js: TCP/IP server has received 6077250 bytes of data
,2015-11-20T12:49:30.805Z SendDataTCPServer.js: TCP/IP server has received 6107910 bytes of data
,2015-11-20T12:49:30.820Z SendDataTCPServer.js: TCP/IP server has received 6145140 bytes of data
,2015-11-20T12:49:30.835Z SendDataTCPServer.js: TCP/IP server has received 6193320 bytes of data
,2015-11-20T12:49:30.848Z SendDataTCPServer.js: TCP/IP server has received 6230550 bytes of data
,2015-11-20T12:49:30.862Z SendDataTCPServer.js: TCP/IP server has received 6274350 bytes of data
,2015-11-20T12:49:30.875Z SendDataTCPServer.js: TCP/IP server has received 6329100 bytes of data
,2015-11-20T12:49:30.887Z SendDataTCPServer.js: TCP/IP server has received 6381660 bytes of data
,2015-11-20T12:49:30.901Z SendDataTCPServer.js: TCP/IP server has received 6418890 bytes of data
,2015-11-20T12:49:30.952Z SendDataTCPServer.js: TCP/IP server has received 6440790 bytes of data
,2015-11-20T12:49:30.968Z SendDataTCPServer.js: TCP/IP server has received 6482400 bytes of data
,2015-11-20T12:49:30.987Z SendDataTCPServer.js: TCP/IP server has received 6537150 bytes of data
,2015-11-20T12:49:31.002Z SendDataTCPServer.js: TCP/IP server has received 6580950 bytes of data
,2015-11-20T12:49:31.021Z SendDataTCPServer.js: TCP/IP server has received 6639938 bytes of data
,2015-11-20T12:49:31.038Z SendDataTCPServer.js: TCP/IP server has received 6697020 bytes of data
,2015-11-20T12:49:31.053Z SendDataTCPServer.js: TCP/IP server has received 6758340 bytes of data
,2015-11-20T12:49:31.070Z SendDataTCPServer.js: TCP/IP server has received 6819660 bytes of data
,2015-11-20T12:49:31.084Z SendDataTCPServer.js: TCP/IP server has received 6852510 bytes of data
,2015-11-20T12:49:31.098Z SendDataTCPServer.js: TCP/IP server has received 6894120 bytes of data
,2015-11-20T12:49:31.112Z SendDataTCPServer.js: TCP/IP server has received 6948728 bytes of data
,2015-11-20T12:49:31.127Z SendDataTCPServer.js: TCP/IP server has received 6972960 bytes of data
,2015-11-20T12:49:31.140Z SendDataTCPServer.js: TCP/IP server has received 6994860 bytes of data
,2015-11-20T12:49:31.175Z SendDataTCPServer.js: TCP/IP server has received 7003478 bytes of data
,2015-11-20T12:49:31.190Z SendDataTCPServer.js: TCP/IP server has received 7051800 bytes of data
,2015-11-20T12:49:31.205Z SendDataTCPServer.js: TCP/IP server has received 7086840 bytes of data
,2015-11-20T12:49:31.219Z SendDataTCPServer.js: TCP/IP server has received 7091220 bytes of data
,2015-11-20T12:49:31.232Z SendDataTCPServer.js: TCP/IP server has received 7124070 bytes of data
,2015-11-20T12:49:31.246Z SendDataTCPServer.js: TCP/IP server has received 7145970 bytes of data
,2015-11-20T12:49:31.270Z SendDataTCPServer.js: TCP/IP server has received 7148160 bytes of data
,2015-11-20T12:49:31.282Z SendDataTCPServer.js: TCP/IP server has received 7183200 bytes of data
,2015-11-20T12:49:31.296Z SendDataTCPServer.js: TCP/IP server has received 7218240 bytes of data
,2015-11-20T12:49:31.309Z SendDataTCPServer.js: TCP/IP server has received 7246710 bytes of data
,2015-11-20T12:49:31.324Z SendDataTCPServer.js: TCP/IP server has received 7292700 bytes of data
,2015-11-20T12:49:31.337Z SendDataTCPServer.js: TCP/IP server has received 7310220 bytes of data
,2015-11-20T12:49:31.350Z SendDataTCPServer.js: TCP/IP server has received 7321170 bytes of data
,2015-11-20T12:49:31.362Z SendDataTCPServer.js: TCP/IP server has received 7358400 bytes of data
,2015-11-20T12:49:31.375Z SendDataTCPServer.js: TCP/IP server has received 7391250 bytes of data
,2015-11-20T12:49:31.390Z SendDataTCPServer.js: TCP/IP server has received 7450380 bytes of data
,2015-11-20T12:49:31.405Z SendDataTCPServer.js: TCP/IP server has received 7481040 bytes of data
,2015-11-20T12:49:31.419Z SendDataTCPServer.js: TCP/IP server has received 7500750 bytes of data
,2015-11-20T12:49:31.435Z SendDataTCPServer.js: TCP/IP server has received 7529220 bytes of data
,2015-11-20T12:49:31.451Z SendDataTCPServer.js: TCP/IP server has received 7561928 bytes of data
,2015-11-20T12:49:31.464Z SendDataTCPServer.js: TCP/IP server has received 7610250 bytes of data
,2015-11-20T12:49:31.477Z SendDataTCPServer.js: TCP/IP server has received 7658430 bytes of data
,2015-11-20T12:49:31.491Z SendDataTCPServer.js: TCP/IP server has received 7717560 bytes of data
,2015-11-20T12:49:31.505Z SendDataTCPServer.js: TCP/IP server has received 7761360 bytes of data
,2015-11-20 13:49:31.518 ThaliTest[1063:734798] jxcore: disconnect
,2015-11-20 13:49:31.519 ThaliTest[1063:734798] jxcore: disconnect: fail
2015-11-20T12:49:31.519Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:31.520Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT545.qwwthQ== with availability status: true
,2015-11-20T12:49:31.520Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:31.521Z SendDataConnector.js: do connect now
,2015-11-20 13:49:31.522 ThaliTest[1063:734798] jxcore: connect Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:31.522 ThaliTest[1063:734798] client session: connect
,2015-11-20 13:49:31.522 ThaliTest[1063:734798] client session: stateChange:0->1 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20T12:49:31.530Z SendDataTCPServer.js: TCP/IP server has received 7851150 bytes of data
,2015-11-20T12:49:31.547Z SendDataTCPServer.js: TCP/IP server has received 7905900 bytes of data
,2015-11-20T12:49:31.561Z SendDataTCPServer.js: TCP/IP server has received 7954080 bytes of data
,2015-11-20T12:49:31.612Z SendDataTCPServer.js: TCP/IP server has received 7993500 bytes of data
,2015-11-20T12:49:31.642Z SendDataTCPServer.js: TCP/IP server has received 7995690 bytes of data
,2015-11-20T12:49:31.689Z SendDataTCPServer.js: TCP/IP server has received 8002260 bytes of data
,2015-11-20T12:49:31.702Z SendDataTCPServer.js: TCP/IP server has received 8021970 bytes of data
,2015-11-20T12:49:31.715Z SendDataTCPServer.js: TCP/IP server has received 8063580 bytes of data
,2015-11-20T12:49:31.729Z SendDataTCPServer.js: TCP/IP server has received 8100810 bytes of data
,2015-11-20T12:49:31.741Z SendDataTCPServer.js: TCP/IP server has received 8118330 bytes of data
,2015-11-20T12:49:31.890Z SendDataTCPServer.js: TCP/IP server has received 8135850 bytes of data
,2015-11-20T12:49:31.917Z SendDataTCPServer.js: TCP/IP server has received 8144610 bytes of data
,2015-11-20T12:49:31.929Z SendDataTCPServer.js: TCP/IP server has received 8159940 bytes of data
,2015-11-20T12:49:31.944Z SendDataTCPServer.js: TCP/IP server has received 8175270 bytes of data
,2015-11-20T12:49:31.958Z SendDataTCPServer.js: TCP/IP server has received 8190600 bytes of data
,2015-11-20T12:49:31.973Z SendDataTCPServer.js: TCP/IP server has received 8212500 bytes of data
,2015-11-20T12:49:31.987Z SendDataTCPServer.js: TCP/IP server has received 8238780 bytes of data
,2015-11-20T12:49:32.001Z SendDataTCPServer.js: TCP/IP server has received 8258490 bytes of data
,2015-11-20T12:49:32.013Z SendDataTCPServer.js: TCP/IP server has received 8276010 bytes of data
,2015-11-20T12:49:32.025Z SendDataTCPServer.js: TCP/IP server has received 8297910 bytes of data
,2015-11-20T12:49:32.040Z SendDataTCPServer.js: TCP/IP server has received 8322000 bytes of data
,2015-11-20T12:49:32.054Z SendDataTCPServer.js: TCP/IP server has received 8354850 bytes of data
,2015-11-20T12:49:32.067Z SendDataTCPServer.js: TCP/IP server has received 8378940 bytes of data
,2015-11-20T12:49:32.080Z SendDataTCPServer.js: TCP/IP server has received 8413980 bytes of data
,2015-11-20T12:49:32.094Z SendDataTCPServer.js: TCP/IP server has received 8453400 bytes of data
,2015-11-20T12:49:32.107Z SendDataTCPServer.js: TCP/IP server has received 8490630 bytes of data
,2015-11-20T12:49:32.121Z SendDataTCPServer.js: TCP/IP server has received 8523480 bytes of data
,2015-11-20T12:49:32.135Z SendDataTCPServer.js: TCP/IP server has received 8565090 bytes of data
,2015-11-20T12:49:32.150Z SendDataTCPServer.js: TCP/IP server has received 8606700 bytes of data
,2015-11-20T12:49:32.164Z SendDataTCPServer.js: TCP/IP server has received 8648310 bytes of data
,2015-11-20T12:49:32.179Z SendDataTCPServer.js: TCP/IP server has received 8696490 bytes of data
,2015-11-20T12:49:32.192Z SendDataTCPServer.js: TCP/IP server has received 8744670 bytes of data
,2015-11-20T12:49:32.205Z SendDataTCPServer.js: TCP/IP server has received 8801610 bytes of data
,2015-11-20T12:49:32.219Z SendDataTCPServer.js: TCP/IP server has received 8854170 bytes of data
,2015-11-20T12:49:32.231Z SendDataTCPServer.js: TCP/IP server has received 8902350 bytes of data
,2015-11-20T12:49:32.245Z SendDataTCPServer.js: TCP/IP server has received 8935200 bytes of data
,2015-11-20T12:49:32.259Z SendDataTCPServer.js: TCP/IP server has received 8974620 bytes of data
,2015-11-20T12:49:32.274Z SendDataTCPServer.js: TCP/IP server has received 8996378 bytes of data
,2015-11-20T12:49:32.286Z SendDataTCPServer.js: TCP/IP server has received 9031560 bytes of data
,2015-11-20T12:49:32.299Z SendDataTCPServer.js: TCP/IP server has received 9060030 bytes of data
,2015-11-20T12:49:32.348Z SendDataTCPServer.js: TCP/IP server has received 9103830 bytes of data
,2015-11-20T12:49:32.362Z SendDataTCPServer.js: TCP/IP server has received 9143108 bytes of data
,2015-11-20T12:49:32.375Z SendDataTCPServer.js: TCP/IP server has received 9176100 bytes of data
,2015-11-20T12:49:32.388Z SendDataTCPServer.js: TCP/IP server has received 9210998 bytes of data
,2015-11-20T12:49:32.400Z SendDataTCPServer.js: TCP/IP server has received 9217710 bytes of data
,2015-11-20T12:49:32.411Z SendDataTCPServer.js: TCP/IP server has received 9235230 bytes of data
,2015-11-20T12:49:32.425Z SendDataTCPServer.js: TCP/IP server has received 9272460 bytes of data
,2015-11-20T12:49:32.438Z SendDataTCPServer.js: TCP/IP server has received 9314070 bytes of data
,2015-11-20T12:49:32.449Z SendDataTCPServer.js: TCP/IP server has received 9355680 bytes of data
,2015-11-20T12:49:32.464Z SendDataTCPServer.js: TCP/IP server has received 9362250 bytes of data
,2015-11-20T12:49:32.476Z SendDataTCPServer.js: TCP/IP server has received 9395100 bytes of data
,2015-11-20T12:49:32.491Z SendDataTCPServer.js: TCP/IP server has received 9449708 bytes of data
,2015-11-20T12:49:32.504Z SendDataTCPServer.js: TCP/IP server has received 9478320 bytes of data
,2015-11-20T12:49:32.517Z SendDataTCPServer.js: TCP/IP server has received 9517598 bytes of data
,2015-11-20T12:49:32.531Z SendDataTCPServer.js: TCP/IP server has received 9561540 bytes of data
,2015-11-20T12:49:32.545Z SendDataTCPServer.js: TCP/IP server has received 9570300 bytes of data
,2015-11-20T12:49:32.557Z SendDataTCPServer.js: TCP/IP server has received 9583440 bytes of data
,2015-11-20T12:49:32.569Z SendDataTCPServer.js: TCP/IP server has received 9622860 bytes of data
,2015-11-20T12:49:32.582Z SendDataTCPServer.js: TCP/IP server has received 9657900 bytes of data
,2015-11-20T12:49:32.595Z SendDataTCPServer.js: TCP/IP server has received 9714840 bytes of data
,2015-11-20T12:49:32.609Z SendDataTCPServer.js: TCP/IP server has received 9769590 bytes of data
,2015-11-20T12:49:32.624Z SendDataTCPServer.js: TCP/IP server has received 9804630 bytes of data
,2015-11-20T12:49:32.637Z SendDataTCPServer.js: TCP/IP server has received 9852810 bytes of data
,2015-11-20T12:49:32.651Z SendDataTCPServer.js: TCP/IP server has received 9900990 bytes of data
,2015-11-20T12:49:32.664Z SendDataTCPServer.js: TCP/IP server has received 9944790 bytes of data
,2015-11-20T12:49:32.678Z SendDataTCPServer.js: TCP/IP server has received 9990780 bytes of data
,2015-11-20T12:49:32.692Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20 13:49:34.719 ThaliTest[1063:735805] client session: connected
2015-11-20 13:49:34.719 ThaliTest[1063:735805] client session: stateChange:1->2 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:34.733 ThaliTest[1063:735818] client session: fireConnectCallback: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:34.734 ThaliTest[1063:735818] jxcore: connect: success
2015-11-20T12:49:34.735Z SendDataConnector.js: CLIENT connected to, 55751, error: null
2015-11-20T12:49:34.735Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:49:34.738 ThaliTest[1063:734671] client: relay established
2015-11-20 13:49:34.739 ThaliTest[1063:734671] client: new accepted socket: 0x19a34a60
,2015-11-20T12:49:34.752Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:49:39.013Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:42.726 ThaliTest[1063:735805] server session: not connected Apple-Iphone5s-1_PT7169
,2015-11-20 13:49:44.912 ThaliTest[1063:734671] multipeer session: restart
,2015-11-20 13:49:48.486 ThaliTest[1063:734671] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:49:48.487 ThaliTest[1063:734671] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:48.487 ThaliTest[1063:734671] client: f,ound peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:49:49.017Z SendDataConnector.js: Receiving data timeout now
2015-11-20T12:49:49.017Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:49:49.018Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:49:49.019Z SendDataConnector.js: Stop data retrieving timer
,2015-11-20 13:49:49.020 ThaliTest[1063:734798] jxcore: disconnect
2015-11-20 13:49:49.021 ThaliTest[1063:734798] client session: disconnectFromPeer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:49.021 ThaliTest[1063:734798] client session: disconnect
2015-11-20 13:49:49.022 ThaliTest[1063:734798] client session: stateChange:2->0 Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:49.327 ThaliTest[1063:734671] client: socket closed
2015-11-20 13:49:49.328 ThaliTest[1063:734671] client relay: socket disconnected
2015-11-20 13:49:49.328 ThaliTest[1063:734671] client relay: 0x19a34a60 disconnected with error Error Do,main=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19ca7680 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 13:49:49.329 ThaliTest[1063:734671] client session: socket closed: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:49:49.332 ThaliTest[1063:734671] client session: onLinkFailure: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:49.332 ThaliTest[1063:734798] jxcore: disconnect: success
2015-11-20T12:49:49.333Z SendDataConnector.js: Mobile.Disconnect() ca,llback with peer Apple-IpadAir2-1_PT545.qwwthQ==
Assertion failed: ([self connectionState] != THEPeerSessionStateNotConnected), function -[THEMultipeerClientSession onLinkFailure], file /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.tha,liproject.p2p/THEMultipeerClientSession.m, line 124.
,Process 1063 stopped
* thread #1: tid = 0xb35cf, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x35e14df0 <+8>:  blo    0x35e14e08                ; <+32>
    0x35e14df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x35e14df8 <+16>: ldr    r12, [pc, r12]
    0x35e14dfc <+20>: b      0x35e14e04                ; <+28>
,* thread #1: tid = 0xb35cf, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x35e93cc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x35db0908 libsystem_c.dylib`abort + 76
    frame #3: 0x35d90368 libsystem_c.dylib`__assert_rtn + 92
    frame #4: 0x000b582a ThaliTest`-[THEMultipeerClientSession onLinkFailure] + 290
    frame #5: 0x000b602c ThaliTest`-[THEMultipeerClientSession didDisconnectFromPeer] + 104
    frame #6: 0x000b82b2 ThaliTest`-[THEMultipeerClientSocketRelay socketDidDisconnect:withError:] + 182
    frame #7: 0x000c2a92 ThaliTest`__33-[GCDAsyncSocket closeWithError:]_block_invoke + 70
    frame #8: 0x35d292e2 libdispatch.dylib`<redacted> + 10
    frame #9: 0x35d292ce libdispatch.dylib`<redacted> + 22
    frame #10: 0x35d2cd2e libdispatch.dylib`_dispatch_main_queue_callback_4CF + 1330
    frame #11: 0x26df4608 CoreFoundation`<redacted> + 8
    frame #12: 0x26df2d08 CoreFoundation`<redacted> + 1512
    frame #13: 0x26d3f200 CoreFoundation`CFRunLoopRunSpecific + 476
    frame #14: 0x26d3f012 CoreFoundation`CFRunLoopRunInMode + 106
    frame #15: 0x2e7ca200 GraphicsServices`GSEventRunModal + 136
    frame #16: 0x2a50ba08 UIKit`UIApplicationMain + 1440
    frame #17: 0x000a1692 ThaliTest`main + 50

```
