#### Test 51335028813a553_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028813a553/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DD492ACF-D1E6-4FA2-9C26-3AF7530EAFC6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DD492ACF-D1E6-4FA2-9C26-3AF7530EAFC6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028813a553/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028813a553/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5189E657-0FF2-4CB6-8633-DA00DB14EE47/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51170"
,(lldb)     command script import "/tmp/DD492ACF-D1E6-4FA2-9C26-3AF7530EAFC6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 12:59:44.152 ThaliTest[1046:729992] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/75289376-9088-4A3D-95D2-96FD0DFD7F68/Library/Cookies/Cookies.binarycookies
,2015-11-20 12:59:44.518 ThaliTest[1046:729992] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 12:59:44.519 ThaliTest[1046:729992] Multi-tasking -> Device: YES, App: YES
,2015-11-20 12:59:44.527 ThaliTest[1046:729992] Unlimited access to network resources
,2015-11-20 12:59:44.533 ThaliTest[1046:729992] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 12:59:47.999 ThaliTest[1046:729992] Resetting plugins due to page load.
,2015-11-20 12:59:48.392 ThaliTest[1046:729992] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/5189E657-0FF2-4CB6-8633-DA00DB14EE47/ThaliTest.app/www/index.html
,2015-11-20 12:59:48.517 ThaliTest[1046:729992] JXcore Cordova plugin initializing
2015-11-20 12:59:48.519 ThaliTest[1046:730123] JXcore instance initializing
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
We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,my name is : Apple-Iphone6-1_PT2043
,attempting to connect to test coordinator
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
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
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
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
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"10000000\",\"conReTryTimeout\":\"1000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":,[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 55575
2015-11-20 13:10:17.098 ThaliTest[1046:730123] jxcore: startBroadcasting
,2015-11-20 13:10:17.113 ThaliTest[1046:730123] server: starting Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:10:17.115 ThaliTest[1046:730123] multipeer session: start timer: 0x193ec200
,2015-11-20 13:10:17.116 ThaliTest[1046:730123] THEMultipeerSession initialized peer Apple-Iphone6-1_PT2043
2015-11-20 13:10:17.117 ThaliTest[1046:730123] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-11-20T12:10:17.124Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-20 13:10:17.475 ThaliTest[1046:729992] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tru,e
,device[1]: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:17.480Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:17.481Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:18.166 ThaliTest[1046:729992] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7072.5zbvNA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:10:18.423 ThaliTest[1046:729992] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2716.py/N2Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tru,e
,2015-11-20 13:10:18.484 ThaliTest[1046:730123] jxcore: disconnect
2015-11-20 13:10:18.485 ThaliTest[1046:730123] jxcore: disconnect: fail
2015-11-20T12:10:18.485Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg=,=
,2015-11-20T12:10:18.486Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5s-1_PT497.PdI1bg== with availability status: true
,2015-11-20T12:10:18.487Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:18.487Z SendDataConnector.js: do connect now
,2015-11-20 13:10:18.488 ThaliTest[1046:730123] jxcore: connect Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:10:18.489 ThaliTest[1046:730123] client session: connect
2015-11-20 13:10:18.490 ThaliTest[1046:730123] client session: stateChange:0->1 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:19.198 ThaliTest[1046:729992] multipeer session: reset timer
2015-11-20 13:10:19.199 ThaliTest[1046:729992] multipeer session: stop timer
2015-11-20 13:10:19.200 ThaliTest[1046:729992] multipeer session: start timer: 0x193ec200
2015-11-,20 13:10:19.200 ThaliTest[1046:729992] server session: connect
2015-11-20 13:10:19.201 ThaliTest[1046:729992] server session: stateChange:0->1 Apple-Iphone5s-1_PT497
,2015-11-20 13:10:19.212 ThaliTest[1046:729992] server: accepting invitation Apple-Iphone5s-1_PT497
,2015-11-20 13:10:20.794 ThaliTest[1046:729992] multipeer session: reset timer
2015-11-20 13:10:20.794 ThaliTest[1046:729992] multipeer session: stop timer
2015-11-20 13:10:20.795 ThaliTest[1046:729992] multipeer session: start timer: 0x193ec200
2015-11-,20 13:10:20.796 ThaliTest[1046:729992] server session: connect
2015-11-20 13:10:20.796 ThaliTest[1046:729992] server session: stateChange:0->1 Apple-IpadAir2-1_PT7072
,2015-11-20 13:10:20.806 ThaliTest[1046:729992] server: accepting invitation Apple-IpadAir2-1_PT7072
,2015-11-20 13:10:21.019 ThaliTest[1046:730939] client session: connected
2015-11-20 13:10:21.020 ThaliTest[1046:730939] client session: stateChange:1->2 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:21.027 ThaliTest[1046:730942] client session: fireConnectCallback: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:10:21.027 ThaliTest[1046:730942] jxcore: connect: success
,2015-11-20T12:10:21.029Z SendDataConnector.js: CLIENT connected to 55578, error: null
2015-11-20T12:10:21.030Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:10:21.033 ThaliTest[1046:729992] client: relay established
2015-11-20 13:10:21.034 ThaliTest[1046:729992] client: new accepted socket: 0x197743f0
,2015-11-20T12:10:21.046Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:10:22.406 ThaliTest[1046:730944] server session: connected
2015-11-20 13:10:22.406 ThaliTest[1046:730944] server session: stateChange:1->2 Apple-Iphone5s-1_PT497
,2015-11-20 13:10:22.411 ThaliTest[1046:729992] server relay: connected (to port: 55575)
,2015-11-20 13:10:23.504 ThaliTest[1046:730963] server session: connected
2015-11-20 13:10:23.505 ThaliTest[1046:730963] server session: stateChange:1->2 Apple-IpadAir2-1_PT7072
,2015-11-20 13:10:23.524 ThaliTest[1046:729992] server relay: connected (to port: 55575)
,2015-11-20T12:10:25.439Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:25.598Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:10:25.599Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:10:29.835Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:29.836Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-20T12:10:29.838Z SendDataTCPServer.js: TCP/IP server has received 2048 bytes of data
,2015-11-20T12:10:29.838Z SendDataTCPServer.js: TCP/IP server has received 2048 bytes of data
,2015-11-20T12:10:31.787Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:31.788Z SendDataConnector.js: CLIENT is data received : 2350000
,2015-11-20T12:10:31.790Z SendDataTCPServer.js: TCP/IP server has received 4096 bytes of data
2015-11-20T12:10:31.792Z SendDataTCPServer.js: TCP/IP server has received 4096 bytes of data
,2015-11-20T12:10:32.378Z SendDataTCPServer.js: TCP/IP server has received 61440 bytes of data
2015-11-20T12:10:32.382Z SendDataTCPServer.js: TCP/IP server has received 67584 bytes of data
,2015-11-20T12:10:32.399Z SendDataTCPServer.js: TCP/IP server has received 67584 bytes of data
,2015-11-20T12:10:33.435Z SendDataTCPServer.js: TCP/IP server has received 79872 bytes of data
2015-11-20T12:10:33.444Z SendDataTCPServer.js: TCP/IP server has received 100352 bytes of data
,2015-11-20T12:10:33.463Z SendDataTCPServer.js: TCP/IP server has received 188416 bytes of data
,2015-11-20T12:10:33.469Z SendDataTCPServer.js: TCP/IP server has received 188416 bytes of data
,2015-11-20T12:10:37.532Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:37.533Z SendDataConnector.js: CLIENT is data received : 2630000
2015-11-20T12:10:37.538Z SendDataTCPServer.js: TCP/IP server, has received 319488 bytes of data
,2015-11-20T12:10:37.565Z SendDataTCPServer.js: TCP/IP server has received 450560 bytes of data
,2015-11-20T12:10:37.573Z SendDataTCPServer.js: TCP/IP server has received 524288 bytes of data
,2015-11-20T12:10:37.579Z SendDataTCPServer.js: TCP/IP server has received 319488 bytes of data
,2015-11-20T12:10:37.585Z SendDataTCPServer.js: TCP/IP server has received 450560 bytes of data
,2015-11-20T12:10:37.594Z SendDataTCPServer.js: TCP/IP server has received 540672 bytes of data
,2015-11-20T12:10:37.618Z SendDataTCPServer.js: TCP/IP server has received 671744 bytes of data
,2015-11-20T12:10:37.649Z SendDataTCPServer.js: TCP/IP server has received 802816 bytes of data
,2015-11-20T12:10:37.655Z SendDataTCPServer.js: TCP/IP server has received 933888 bytes of data
,2015-11-20T12:10:37.719Z SendDataTCPServer.js: TCP/IP server has received 1064960 bytes of data
,2015-11-20T12:10:37.731Z SendDataTCPServer.js: TCP/IP server has received 1196032 bytes of data
,2015-11-20T12:10:37.741Z SendDataTCPServer.js: TCP/IP server has received 1327104 bytes of data
,2015-11-20T12:10:37.745Z SendDataTCPServer.js: TCP/IP server has received 1458176 bytes of data
,2015-11-20T12:10:37.754Z SendDataTCPServer.js: TCP/IP server has received 1589248 bytes of data
,2015-11-20T12:10:37.757Z SendDataTCPServer.js: TCP/IP server has received 1720320 bytes of data
,2015-11-20T12:10:37.766Z SendDataTCPServer.js: TCP/IP server has received 1851392 bytes of data
,2015-11-20T12:10:37.785Z SendDataTCPServer.js: TCP/IP server has received 1982464 bytes of data
,2015-11-20T12:10:37.814Z SendDataTCPServer.js: TCP/IP server has received 2113536 bytes of data
,2015-11-20T12:10:37.823Z SendDataTCPServer.js: TCP/IP server has received 2174670 bytes of data
,2015-11-20T12:10:37.840Z SendDataTCPServer.js: TCP/IP server has received 655360 bytes of data
,2015-11-20T12:10:37.851Z SendDataTCPServer.js: TCP/IP server has received 786432 bytes of data
,2015-11-20T12:10:37.856Z SendDataTCPServer.js: TCP/IP server has received 917504 bytes of data
,2015-11-20T12:10:37.860Z SendDataTCPServer.js: TCP/IP server has received 1048576 bytes of data
,2015-11-20T12:10:37.864Z SendDataTCPServer.js: TCP/IP server has received 1179648 bytes of data
,2015-11-20T12:10:37.872Z SendDataTCPServer.js: TCP/IP server has received 1310720 bytes of data
,2015-11-20T12:10:37.875Z SendDataTCPServer.js: TCP/IP server has received 1441792 bytes of data
,2015-11-20T12:10:37.878Z SendDataTCPServer.js: TCP/IP server has received 1572864 bytes of data
,2015-11-20T12:10:37.881Z SendDataTCPServer.js: TCP/IP server has received 1703936 bytes of data
,2015-11-20T12:10:37.886Z SendDataTCPServer.js: TCP/IP server has received 1835008 bytes of data
,2015-11-20T12:10:37.889Z SendDataTCPServer.js: TCP/IP server has received 1966080 bytes of data
,2015-11-20T12:10:37.892Z SendDataTCPServer.js: TCP/IP server has received 2097152 bytes of data
,2015-11-20T12:10:37.895Z SendDataTCPServer.js: TCP/IP server has received 2228224 bytes of data
,2015-11-20T12:10:37.899Z SendDataTCPServer.js: TCP/IP server has received 2359296 bytes of data
,2015-11-20T12:10:37.903Z SendDataTCPServer.js: TCP/IP server has received 2490368 bytes of data
,2015-11-20T12:10:37.905Z SendDataTCPServer.js: TCP/IP server has received 2621440 bytes of data
,2015-11-20T12:10:37.908Z SendDataTCPServer.js: TCP/IP server has received 2752512 bytes of data
,2015-11-20T12:10:37.912Z SendDataTCPServer.js: TCP/IP server has received 2883584 bytes of data
,2015-11-20T12:10:37.914Z SendDataTCPServer.js: TCP/IP server has received 3014656 bytes of data
,2015-11-20T12:10:37.917Z SendDataTCPServer.js: TCP/IP server has received 3145728 bytes of data
,2015-11-20T12:10:37.921Z SendDataTCPServer.js: TCP/IP server has received 3276800 bytes of data
,2015-11-20T12:10:37.923Z SendDataTCPServer.js: TCP/IP server has received 3407872 bytes of data
,2015-11-20T12:10:37.926Z SendDataTCPServer.js: TCP/IP server has received 3538944 bytes of data
,2015-11-20T12:10:37.929Z SendDataTCPServer.js: TCP/IP server has received 3670016 bytes of data
,2015-11-20T12:10:37.932Z SendDataTCPServer.js: TCP/IP server has received 3801088 bytes of data
,2015-11-20T12:10:37.935Z SendDataTCPServer.js: TCP/IP server has received 3823740 bytes of data
,2015-11-20T12:10:37.964Z SendDataTCPServer.js: TCP/IP server has received 3876300 bytes of data
,2015-11-20T12:10:37.978Z SendDataTCPServer.js: TCP/IP server has received 3880680 bytes of data
,2015-11-20T12:10:38.035Z SendDataTCPServer.js: TCP/IP server has received 3882870 bytes of data
,2015-11-20T12:10:38.060Z SendDataTCPServer.js: TCP/IP server has received 3885060 bytes of data
,2015-11-20T12:10:38.330Z SendDataTCPServer.js: TCP/IP server has received 3893820 bytes of data
,2015-11-20T12:10:38.370Z SendDataTCPServer.js: TCP/IP server has received 3937620 bytes of data
,2015-11-20T12:10:38.535Z SendDataTCPServer.js: TCP/IP server has received 3942000 bytes of data
,2015-11-20T12:10:38.560Z SendDataTCPServer.js: TCP/IP server has received 3955140 bytes of data
,2015-11-20T12:10:38.841Z SendDataTCPServer.js: TCP/IP server has received 3961710 bytes of data
,2015-11-20T12:10:40.669Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:40.669Z SendDataConnector.js: CLIENT is data received : 2860000
2015-11-20T12:10:40.671Z SendDataTCPServer.js: TCP/IP server has received 2176718 bytes of data
,2015-11-20T12:10:40.672Z SendDataTCPServer.js: TCP/IP server has received 3963758 bytes of data
,2015-11-20T12:10:41.628Z SendDataTCPServer.js: TCP/IP server has received 2283214 bytes of data
2015-11-20T12:10:41.633Z SendDataTCPServer.js: TCP/IP server has received 4086638 bytes of data
,2015-11-20T12:10:41.653Z SendDataTCPServer.js: TCP/IP server has received 2414286 bytes of data
2015-11-20T12:10:41.657Z SendDataTCPServer.js: TCP/IP server has received 2475726 bytes of data
2015-11-20T12:10:41.659Z SendDataTCPServer.js: TCP/IP server h,as received 4217710 bytes of data
2015-11-20T12:10:41.676Z SendDataTCPServer.js: TCP/IP server has received 4348782 bytes of data
,2015-11-20T12:10:41.685Z SendDataTCPServer.js: TCP/IP server has received 4463470 bytes of data
,2015-11-20T12:10:41.717Z SendDataTCPServer.js: TCP/IP server has received 2606798 bytes of data
,2015-11-20T12:10:41.720Z SendDataTCPServer.js: TCP/IP server has received 2737870 bytes of data
,2015-11-20T12:10:41.723Z SendDataTCPServer.js: TCP/IP server has received 2868942 bytes of data
,2015-11-20T12:10:41.731Z SendDataTCPServer.js: TCP/IP server has received 3000014 bytes of data
,2015-11-20T12:10:41.734Z SendDataTCPServer.js: TCP/IP server has received 3077838 bytes of data
,2015-11-20T12:10:41.736Z SendDataTCPServer.js: TCP/IP server has received 4594542 bytes of data
,2015-11-20T12:10:41.751Z SendDataTCPServer.js: TCP/IP server has received 4725614 bytes of data
,2015-11-20T12:10:41.775Z SendDataTCPServer.js: TCP/IP server has received 4856686 bytes of data
,2015-11-20T12:10:41.782Z SendDataTCPServer.js: TCP/IP server has received 4987758 bytes of data
,2015-11-20T12:10:41.786Z SendDataTCPServer.js: TCP/IP server has received 5118830 bytes of data
,2015-11-20T12:10:41.791Z SendDataTCPServer.js: TCP/IP server has received 5249902 bytes of data
,2015-11-20T12:10:41.799Z SendDataTCPServer.js: TCP/IP server has received 5380974 bytes of data
,2015-11-20T12:10:41.802Z SendDataTCPServer.js: TCP/IP server has received 5512046 bytes of data
,2015-11-20T12:10:41.837Z SendDataTCPServer.js: TCP/IP server has received 5643118 bytes of data
,2015-11-20T12:10:41.845Z SendDataTCPServer.js: TCP/IP server has received 5774190 bytes of data
,2015-11-20T12:10:41.849Z SendDataTCPServer.js: TCP/IP server has received 5905262 bytes of data
,2015-11-20T12:10:41.853Z SendDataTCPServer.js: TCP/IP server has received 6036334 bytes of data
,2015-11-20T12:10:41.855Z SendDataTCPServer.js: TCP/IP server has received 6167406 bytes of data
,2015-11-20T12:10:41.857Z SendDataTCPServer.js: TCP/IP server has received 6298478 bytes of data
,2015-11-20T12:10:41.860Z SendDataTCPServer.js: TCP/IP server has received 6341486 bytes of data
,2015-11-20T12:10:41.875Z SendDataTCPServer.js: TCP/IP server has received 3208910 bytes of data
,2015-11-20T12:10:41.877Z SendDataTCPServer.js: TCP/IP server has received 3339982 bytes of data
,2015-11-20T12:10:41.879Z SendDataTCPServer.js: TCP/IP server has received 3471054 bytes of data
,2015-11-20T12:10:41.883Z SendDataTCPServer.js: TCP/IP server has received 3514950 bytes of data
,2015-11-20T12:10:43.085Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:43.087Z SendDataConnector.js: CLIENT is data received : 2920000
,2015-11-20T12:10:43.088Z SendDataTCPServer.js: TCP/IP server has received 3516998 bytes of data
2015-11-20T12:10:43.089Z SendDataTCPServer.js: TCP/IP server has received 6343534 bytes of data
,2015-11-20T12:10:43.723Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:43.725Z SendDataConnector.js: CLIENT is data received : 2930000
2015-11-20T12:10:43.727Z SendDataTCPServer.js: TCP/IP server, has received 3560006 bytes of data
,2015-11-20T12:10:43.761Z SendDataTCPServer.js: TCP/IP server has received 3691078 bytes of data
2015-11-20T12:10:43.767Z SendDataTCPServer.js: TCP/IP server has received 3727942 bytes of data
,2015-11-20T12:10:43.769Z SendDataTCPServer.js: TCP/IP server has received 6474606 bytes of data
,2015-11-20T12:10:43.774Z SendDataTCPServer.js: TCP/IP server has received 6554478 bytes of data
,2015-11-20T12:10:45.251Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:45.253Z SendDataConnector.js: CLIENT is data received : 4180000
2015-11-20T12:10:45.255Z SendDataTCPServer.js: TCP/IP server has received 3779142 bytes of data
2015-11-20T12:10:45.262Z SendDataTCPServer.js: TCP/IP server has received 6685550 bytes of data
2015-11-20T12:10:45.271Z SendDataTCPServer.js: TCP/IP server has received 6699886 bytes of data
,2015-11-20T12:10:45.285Z SendDataTCPServer.js: TCP/IP server has received 3910214 bytes of data
,2015-11-20T12:10:45.289Z SendDataTCPServer.js: TCP/IP server has received 4041286 bytes of data
,2015-11-20T12:10:45.292Z SendDataTCPServer.js: TCP/IP server has received 4072006 bytes of data
,2015-11-20T12:10:45.577Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:45.578Z SendDataConnector.js: CLIENT is data received : 4190000
,2015-11-20T12:10:45.579Z SendDataTCPServer.js: TCP/IP server has received 4074054 bytes of data
,2015-11-20T12:10:45.580Z SendDataTCPServer.js: TCP/IP server has received 6701934 bytes of data
,2015-11-20T12:10:46.234Z SendDataTCPServer.js: TCP/IP server has received 4088390 bytes of data
2015-11-20T12:10:46.249Z SendDataTCPServer.js: TCP/IP server has received 6806382 bytes of data
,2015-11-20T12:10:46.277Z SendDataTCPServer.js: TCP/IP server has received 4219462 bytes of data
,2015-11-20T12:10:46.282Z SendDataTCPServer.js: TCP/IP server has received 4272710 bytes of data
,2015-11-20T12:10:46.286Z SendDataTCPServer.js: TCP/IP server has received 6896494 bytes of data
,2015-11-20T12:10:46.686Z SendDataTCPServer.js: TCP/IP server has received 4274758 bytes of data
,2015-11-20T12:10:46.687Z SendDataTCPServer.js: TCP/IP server has received 6898542 bytes of data
,2015-11-20T12:10:46.875Z SendDataTCPServer.js: TCP/IP server has received 7005038 bytes of data
2015-11-20T12:10:46.888Z SendDataTCPServer.js: TCP/IP server has received 4405830 bytes of data
2015-11-20T12:10:46.898Z SendDataTCPServer.js: TCP/IP server h,as received 4475462 bytes of data
,2015-11-20T12:10:46.948Z SendDataTCPServer.js: TCP/IP server has received 7136110 bytes of data
2015-11-20T12:10:46.962Z SendDataTCPServer.js: TCP/IP server has received 7267182 bytes of data
2015-11-20T12:10:46.966Z SendDataTCPServer.js: TCP/IP server has received 7398254 bytes of data
,2015-11-20T12:10:47.048Z SendDataTCPServer.js: TCP/IP server has received 7529326 bytes of data
,2015-11-20T12:10:47.102Z SendDataTCPServer.js: TCP/IP server has received 7660398 bytes of data
,2015-11-20T12:10:47.106Z SendDataTCPServer.js: TCP/IP server has received 7717742 bytes of data
,2015-11-20T12:10:47.107Z SendDataTCPServer.js: TCP/IP server has received 4606534 bytes of data
,2015-11-20T12:10:47.110Z SendDataTCPServer.js: TCP/IP server has received 4737606 bytes of data
,2015-11-20T12:10:47.113Z SendDataTCPServer.js: TCP/IP server has received 4868678 bytes of data
,2015-11-20T12:10:47.116Z SendDataTCPServer.js: TCP/IP server has received 4999750 bytes of data
,2015-11-20T12:10:47.119Z SendDataTCPServer.js: TCP/IP server has received 5130822 bytes of data
,2015-11-20T12:10:47.122Z SendDataTCPServer.js: TCP/IP server has received 5261894 bytes of data
,2015-11-20T12:10:47.128Z SendDataTCPServer.js: TCP/IP server has received 5392966 bytes of data
,2015-11-20T12:10:47.130Z SendDataTCPServer.js: TCP/IP server has received 5524038 bytes of data
,2015-11-20T12:10:47.146Z SendDataTCPServer.js: TCP/IP server has received 5655110 bytes of data
,2015-11-20T12:10:47.151Z SendDataTCPServer.js: TCP/IP server has received 5786182 bytes of data
,2015-11-20T12:10:47.155Z SendDataTCPServer.js: TCP/IP server has received 5917254 bytes of data
,2015-11-20T12:10:47.163Z SendDataTCPServer.js: TCP/IP server has received 6048326 bytes of data
,2015-11-20T12:10:47.165Z SendDataTCPServer.js: TCP/IP server has received 6179398 bytes of data
,2015-11-20T12:10:47.167Z SendDataTCPServer.js: TCP/IP server has received 6310470 bytes of data
,2015-11-20T12:10:47.171Z SendDataTCPServer.js: TCP/IP server has received 6441542 bytes of data
,2015-11-20T12:10:47.174Z SendDataTCPServer.js: TCP/IP server has received 6572614 bytes of data
,2015-11-20T12:10:47.176Z SendDataTCPServer.js: TCP/IP server has received 6703686 bytes of data
,2015-11-20T12:10:47.180Z SendDataTCPServer.js: TCP/IP server has received 6830662 bytes of data
,2015-11-20T12:10:47.203Z SendDataTCPServer.js: TCP/IP server has received 7848814 bytes of data
,2015-11-20T12:10:47.207Z SendDataTCPServer.js: TCP/IP server has received 7979886 bytes of data
,2015-11-20T12:10:47.210Z SendDataTCPServer.js: TCP/IP server has received 8110958 bytes of data
,2015-11-20T12:10:47.214Z SendDataTCPServer.js: TCP/IP server has received 8211310 bytes of data
,2015-11-20T12:10:47.216Z SendDataTCPServer.js: TCP/IP server has received 6961734 bytes of data
,2015-11-20T12:10:47.218Z SendDataTCPServer.js: TCP/IP server has received 7092806 bytes of data
,2015-11-20T12:10:47.284Z SendDataTCPServer.js: TCP/IP server has received 7223878 bytes of data
,2015-11-20T12:10:47.299Z SendDataTCPServer.js: TCP/IP server has received 7354950 bytes of data
,2015-11-20T12:10:47.307Z SendDataTCPServer.js: TCP/IP server has received 7486022 bytes of data
,2015-11-20T12:10:47.318Z SendDataTCPServer.js: TCP/IP server has received 7617094 bytes of data
,2015-11-20T12:10:47.326Z SendDataTCPServer.js: TCP/IP server has received 7748166 bytes of data
,2015-11-20T12:10:47.331Z SendDataTCPServer.js: TCP/IP server has received 7765740 bytes of data
,2015-11-20T12:10:47.332Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:47.332Z SendDataConnector.js: CLIENT is data received : 4710000
,2015-11-20T12:10:47.344Z SendDataTCPServer.js: TCP/IP server has received 8342382 bytes of data
,2015-11-20T12:10:47.350Z SendDataTCPServer.js: TCP/IP server has received 8473454 bytes of data
,2015-11-20T12:10:47.356Z SendDataTCPServer.js: TCP/IP server has received 8604526 bytes of data
,2015-11-20T12:10:47.364Z SendDataTCPServer.js: TCP/IP server has received 8735598 bytes of data
,2015-11-20T12:10:47.369Z SendDataTCPServer.js: TCP/IP server has received 8866670 bytes of data
,2015-11-20T12:10:47.375Z SendDataTCPServer.js: TCP/IP server has received 8997742 bytes of data
,2015-11-20T12:10:47.379Z SendDataTCPServer.js: TCP/IP server has received 9128814 bytes of data
,2015-11-20T12:10:47.382Z SendDataTCPServer.js: TCP/IP server has received 9259886 bytes of data
,2015-11-20T12:10:47.385Z SendDataTCPServer.js: TCP/IP server has received 9390958 bytes of data
,2015-11-20T12:10:47.388Z SendDataTCPServer.js: TCP/IP server has received 9522030 bytes of data
,2015-11-20T12:10:47.393Z SendDataTCPServer.js: TCP/IP server has received 9653102 bytes of data
,2015-11-20T12:10:47.399Z SendDataTCPServer.js: TCP/IP server has received 9784174 bytes of data
,2015-11-20T12:10:47.409Z SendDataTCPServer.js: TCP/IP server has received 9915246 bytes of data
,2015-11-20T12:10:47.414Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20T12:10:47.416Z SendDataTCPServer.js: TCP/IP server has received 7896812 bytes of data
,2015-11-20T12:10:47.422Z SendDataTCPServer.js: TCP/IP server has received 7905900 bytes of data
,2015-11-20T12:10:47.438Z SendDataTCPServer.js: TCP/IP server has received 7932180 bytes of data
,2015-11-20T12:10:47.456Z SendDataTCPServer.js: TCP/IP server has received 8004450 bytes of data
,2015-11-20T12:10:47.471Z SendDataTCPServer.js: TCP/IP server has received 8037158 bytes of data
,2015-11-20T12:10:47.493Z SendDataTCPServer.js: TCP/IP server has received 8124900 bytes of data
,2015-11-20T12:10:47.510Z SendDataTCPServer.js: TCP/IP server has received 8144610 bytes of data
,2015-11-20T12:10:47.523Z SendDataTCPServer.js: TCP/IP server has received 8151180 bytes of data
,2015-11-20T12:10:47.537Z SendDataTCPServer.js: TCP/IP server has received 8186220 bytes of data
,2015-11-20T12:10:47.564Z SendDataTCPServer.js: TCP/IP server has received 8205930 bytes of data
,2015-11-20 13:10:47.578 ThaliTest[1046:730944] server session: not connected Apple-IpadAir2-1_PT7072
,2015-11-20T12:10:47.579Z SendDataTCPServer.js: TCP/IP server has received 8306670 bytes of data
,2015-11-20T12:10:47.596Z SendDataTCPServer.js: TCP/IP server has received 8311050 bytes of data
,2015-11-20T12:10:47.620Z SendDataTCPServer.js: TCP/IP server has received 8346090 bytes of data
,2015-11-20T12:10:47.639Z SendDataTCPServer.js: TCP/IP server has received 8422740 bytes of data
,2015-11-20T12:10:47.668Z SendDataTCPServer.js: TCP/IP server has received 8525670 bytes of data
,2015-11-20T12:10:47.686Z SendDataTCPServer.js: TCP/IP server has received 8565090 bytes of data
,2015-11-20T12:10:47.703Z SendDataTCPServer.js: TCP/IP server has received 8582610 bytes of data
,2015-11-20T12:10:47.716Z SendDataTCPServer.js: TCP/IP server has received 8630790 bytes of data
,2015-11-20T12:10:47.733Z SendDataTCPServer.js: TCP/IP server has received 8672400 bytes of data
,2015-11-20T12:10:47.746Z SendDataTCPServer.js: TCP/IP server has received 8718390 bytes of data
,2015-11-20T12:10:47.760Z SendDataTCPServer.js: TCP/IP server has received 8746860 bytes of data
,2015-11-20T12:10:47.774Z SendDataTCPServer.js: TCP/IP server has received 8762190 bytes of data
,2015-11-20T12:10:47.785Z SendDataTCPServer.js: TCP/IP server has received 8801610 bytes of data
,2015-11-20T12:10:47.801Z SendDataTCPServer.js: TCP/IP server has received 8847600 bytes of data
,2015-11-20T12:10:47.816Z SendDataTCPServer.js: TCP/IP server has received 8904540 bytes of data
,2015-11-20T12:10:47.833Z SendDataTCPServer.js: TCP/IP server has received 8952720 bytes of data
,2015-11-20T12:10:47.848Z SendDataTCPServer.js: TCP/IP server has received 8998710 bytes of data
,2015-11-20T12:10:47.864Z SendDataTCPServer.js: TCP/IP server has received 9042368 bytes of data
,2015-11-20T12:10:47.882Z SendDataTCPServer.js: TCP/IP server has received 9049080 bytes of data
,2015-11-20T12:10:47.894Z SendDataTCPServer.js: TCP/IP server has received 9077550 bytes of data
,2015-11-20T12:10:47.908Z SendDataTCPServer.js: TCP/IP server has received 9103830 bytes of data
,2015-11-20T12:10:47.923Z SendDataTCPServer.js: TCP/IP server has received 9119160 bytes of data
,2015-11-20T12:10:47.937Z SendDataTCPServer.js: TCP/IP server has received 9130110 bytes of data
,2015-11-20T12:10:47.951Z SendDataTCPServer.js: TCP/IP server has received 9141060 bytes of data
,2015-11-20T12:10:47.965Z SendDataTCPServer.js: TCP/IP server has received 9154200 bytes of data
,2015-11-20T12:10:47.978Z SendDataTCPServer.js: TCP/IP server has received 9167340 bytes of data
,2015-11-20T12:10:48.021Z SendDataTCPServer.js: TCP/IP server has received 9211140 bytes of data
,2015-11-20T12:10:48.058Z SendDataTCPServer.js: TCP/IP server has received 9228660 bytes of data
,2015-11-20T12:10:48.071Z SendDataTCPServer.js: TCP/IP server has received 9257130 bytes of data
,2015-11-20T12:10:48.085Z SendDataTCPServer.js: TCP/IP server has received 9294360 bytes of data
,2015-11-20T12:10:48.098Z SendDataTCPServer.js: TCP/IP server has received 9327210 bytes of data
,2015-11-20T12:10:48.112Z SendDataTCPServer.js: TCP/IP server has received 9366630 bytes of data
,2015-11-20T12:10:48.131Z SendDataTCPServer.js: TCP/IP server has received 9397290 bytes of data
,2015-11-20T12:10:48.159Z SendDataTCPServer.js: TCP/IP server has received 9421380 bytes of data
,2015-11-20T12:10:48.172Z SendDataTCPServer.js: TCP/IP server has received 9467370 bytes of data
,2015-11-20T12:10:48.186Z SendDataTCPServer.js: TCP/IP server has received 9526358 bytes of data
,2015-11-20T12:10:48.206Z SendDataTCPServer.js: TCP/IP server has received 9581250 bytes of data
,2015-11-20T12:10:48.223Z SendDataTCPServer.js: TCP/IP server has received 9640380 bytes of data
,2015-11-20T12:10:48.237Z SendDataTCPServer.js: TCP/IP server has received 9675420 bytes of data
,2015-11-20T12:10:48.249Z SendDataTCPServer.js: TCP/IP server has received 9703890 bytes of data
,2015-11-20T12:10:48.263Z SendDataTCPServer.js: TCP/IP server has received 9727980 bytes of data
,2015-11-20T12:10:48.275Z SendDataTCPServer.js: TCP/IP server has received 9780540 bytes of data
,2015-11-20T12:10:48.288Z SendDataTCPServer.js: TCP/IP server has received 9819960 bytes of data
,2015-11-20T12:10:48.300Z SendDataTCPServer.js: TCP/IP server has received 9857190 bytes of data
,2015-11-20T12:10:48.314Z SendDataTCPServer.js: TCP/IP server has received 9872520 bytes of data
,2015-11-20T12:10:48.315Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:48.315Z SendDataConnector.js: CLIENT is data received : 4740000
,2015-11-20T12:10:48.524Z SendDataTCPServer.js: TCP/IP server has received 9914900 bytes of data
,2015-11-20T12:10:48.538Z SendDataTCPServer.js: TCP/IP server has received 9966690 bytes of data
,2015-11-20T12:10:48.554Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20T12:10:48.556Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:48.556Z SendDataConnector.js: CLIENT is data received : 6290000
,2015-11-20T12:10:48.595Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:48.596Z SendDataConnector.js: CLIENT is data received : 7000000
,2015-11-20T12:10:48.609Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:48.610Z SendDataConnector.js: CLIENT is data received : 7380000
,2015-11-20T12:10:48.624Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:48.624Z SendDataConnector.js: CLIENT is data received : 8050000
,2015-11-20T12:10:48.638Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:48.638Z SendDataConnector.js: CLIENT is data received : 8440000
,2015-11-20T12:10:48.651Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:48.651Z SendDataConnector.js: CLIENT is data received : 8750000
2015-11-20 13:10:48.655 ThaliTest[1046:730971] server session: not connected Apple-Iphone5s-1_PT497
,2015-11-20T12:10:48.666Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:48.667Z SendDataConnector.js: CLIENT is data received : 8940000
,2015-11-20T12:10:48.681Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:48.681Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:10:48.681Z SendDataConnector.js: got all data for this round
,2015-11-20T12:10:48.682Z SendDataConnector.js: CLIENT Stop now
2015-11-20T12:10:48.682Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:10:48.684 ThaliTest[1046:730123] jxcore: disconnect
2015-11-20 13:10:48.684 ThaliTest[1046:730123] client session: disconnectFromPeer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:10:48.685 ThaliTest[1046:730123] client session: disconnect
2015-11-20 13:10:48.685 ThaliTest[1046:730123] client session: stateChange:2->0 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:48.687 ThaliTest[1046:730123] jxcore: disconnect: success
2015-11-20T12:10:48.688Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg==
,---- round done--------
device[2]: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:10:48.691Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:10:48.691Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:10:48.705Z SendDataConnector.js: CLIENT is closed
,2015-11-20 13:10:49.697 ThaliTest[1046:730123] jxcore: disconnect
2015-11-20 13:10:49.698 ThaliTest[1046:730123] jxcore: disconnect: fail
2015-11-20T12:10:49.698Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7072.5zbvNA,==
2015-11-20T12:10:49.699Z SendDataConnector.js: Connect (retry count 0) to peer Apple-IpadAir2-1_PT7072.5zbvNA== with availability status: true
,2015-11-20T12:10:49.699Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:10:49.699Z SendDataConnector.js: do connect now
,2015-11-20 13:10:49.700 ThaliTest[1046:730123] jxcore: connect Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:10:49.701 ThaliTest[1046:730123] client session: connect
2015-11-20 13:10:49.702 ThaliTest[1046:730123] client session: stateChange:0->1 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:10:50.796 ThaliTest[1046:729992] multipeer session: restart
,2015-11-20 13:10:50.890 ThaliTest[1046:729992] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:10:50.891 ThaliTest[1046:729992] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:10:50.892 ThaliTest[1046:729992] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:53.227 ThaliTest[1046:730971] client session: connected
2015-11-20 13:10:53.228 ThaliTest[1046:730971] client session: stateChange:1->2 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:10:53.309 ThaliTest[1046:730944] client session: fireConnectCallback: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:10:53.310 ThaliTest[1046:730944] jxcore: connect: success
,2015-11-20T12:10:53.312Z SendDataConnector.js: CLIENT connected to 55584, error: null
,2015-11-20T12:10:53.313Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:10:53.315 ThaliTest[1046:729992] client: relay established
2015-11-20 13:10:53.316 ThaliTest[1046:729992] client: new accepted socket: 0x193e7070
,2015-11-20T12:10:53.331Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:10:57.696Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:10:58.818Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:10:58.822Z SendDataConnector.js: CLIENT is data received : 210000
,2015-11-20T12:11:08.831Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:11:08.832Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:11:08.833Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:11:08.834Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T12:11:08.836Z SendDataConnector.js: CLIENT is closed
,2015-11-20T12:11:09.839Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:09.839Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:10.851 ThaliTest[1046:730123] jxcore: disconnect
2015-11-20 13:11:10.851 ThaliTest[1046:730123] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:11:10.851 ThaliTest[1046:730123] client session: disconnect
2015-11-20 13:11:10.852 ThaliTest[1046:730123] client session: stateChange:2->0 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:19.685 ThaliTest[1046:730123] jxcore: disconnect: success
2015-11-20T12:11:19.686Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:19.687Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT7072.5zbvNA== with availability status: true
2015-11-20T12:11:19.687Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:19.687Z SendDataConnector.js: do connect now
,2015-11-20 13:11:19.688 ThaliTest[1046:730123] jxcore: connect Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:11:19.689 ThaliTest[1046:730123] client session: connect
2015-11-20 13:11:19.689 ThaliTest[1046:730123] client session: stateChange:0->1 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:20.797 ThaliTest[1046:729992] multipeer session: restart
,2015-11-20 13:11:20.815 ThaliTest[1046:729992] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:11:20.815 ThaliTest[1046:729992] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:20.816 ThaliTest[1046:729992] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:22.720 ThaliTest[1046:730944] client session: connected
2015-11-20 13:11:22.720 ThaliTest[1046:730944] client session: stateChange:1->2 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:22.730 ThaliTest[1046:730944] client session: fireConnectCallback: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:11:22.731 ThaliTest[1046:730944] jxcore: connect: success
2015-11-20T12:11:22.732Z SendDataConnector.js: CLIENT connected to 55588, error: null
2015-11-20T12:11:22.733Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:11:22.735 ThaliTest[1046:729992] client: relay established
2015-11-20 13:11:22.736 ThaliTest[1046:729992] client: new accepted socket: 0x1975ae10
,2015-11-20T12:11:22.748Z SendDataConnector.js: CLIENT now sending 9790000 bytes of data
,2015-11-20T12:11:26.973Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:29.922Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:29.925Z SendDataConnector.js: CLIENT is data received : 470000
,2015-11-20T12:11:33.944Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:33.945Z SendDataConnector.js: CLIENT is data received : 490000
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,Turning Wifi off
,Warning: iOS does not support ToggleWiFi
,We could not turn wifi off! - Warning: iOS does not support ToggleWiFi
,Turning Wifi back on
,Warning: iOS does not support ToggleWiFi
,We could turn wifi back on! - Warning: iOS does not support ToggleWiFi
,toggleWiFi finished
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,2015-11-20T12:11:40.770Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:40.771Z SendDataConnector.js: CLIENT is data received : 510000
,2015-11-20T12:11:42.892Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:42.892Z SendDataConnector.js: CLIENT is data received : 590000
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":,10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"a,rraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,2015-11-20T12:11:44.274Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:44.274Z SendDataConnector.js: CLIENT is data received : 680000
,2015-11-20T12:11:45.251Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:45.252Z SendDataConnector.js: CLIENT is data received : 770000
,2015-11-20T12:11:45.645Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:45.645Z SendDataConnector.js: CLIENT is data received : 800000
,2015-11-20T12:11:46.175Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:46.176Z SendDataConnector.js: CLIENT is data received : 1870000
,2015-11-20T12:11:46.191Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:46.192Z SendDataConnector.js: CLIENT is data received : 3600000
,2015-11-20T12:11:46.205Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.206Z SendDataConnector.js: CLIENT is data received : 5370000
,2015-11-20T12:11:46.233Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:46.234Z SendDataConnector.js: CLIENT is data received : 5780000
,2015-11-20T12:11:46.248Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:46.250Z SendDataConnector.js: CLIENT is data received : 6470000
,2015-11-20T12:11:46.263Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.263Z SendDataConnector.js: CLIENT is data received : 6530000
,2015-11-20T12:11:46.277Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.279Z SendDataConnector.js: CLIENT is data received : 6850000
,2015-11-20T12:11:46.293Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.293Z SendDataConnector.js: CLIENT is data received : 6960000
,2015-11-20T12:11:46.307Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.308Z SendDataConnector.js: CLIENT is data received : 7250000
,2015-11-20T12:11:46.322Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.323Z SendDataConnector.js: CLIENT is data received : 7480000
,2015-11-20T12:11:46.336Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:46.336Z SendDataConnector.js: CLIENT is data received : 8160000
,2015-11-20T12:11:46.350Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.351Z SendDataConnector.js: CLIENT is data received : 8510000
,2015-11-20T12:11:46.387Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.388Z SendDataConnector.js: CLIENT is data received : 8640000
,2015-11-20T12:11:46.404Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.406Z SendDataConnector.js: CLIENT is data received : 8820000
,2015-11-20T12:11:46.420Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.422Z SendDataConnector.js: CLIENT is data received : 9040000
,2015-11-20T12:11:46.437Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.440Z SendDataConnector.js: CLIENT is data received : 9150000
,2015-11-20T12:11:46.461Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.466Z SendDataConnector.js: CLIENT is data received : 9370000
,2015-11-20T12:11:46.481Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.483Z SendDataConnector.js: CLIENT is data received : 9520000
,2015-11-20T12:11:46.496Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.498Z SendDataConnector.js: CLIENT is data received : 9700000
,2015-11-20T12:11:46.510Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.512Z SendDataConnector.js: CLIENT is data received : 9990000
,2015-11-20T12:11:46.525Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:46.526Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:11:46.526Z SendDataConnector.js: got all data for this round
,2015-11-20T12:11:46.527Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:11:46.527Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:11:46.528 ThaliTest[1046:730123] jxcore: disconnect
,2015-11-20 13:11:46.529 ThaliTest[1046:730123] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:46.530 ThaliTest[1046:730123] client session: disconnect
,2015-11-20 13:11:46.531 ThaliTest[1046:730123] client session: stateChange:2->0 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:46.534 ThaliTest[1046:730123] jxcore: disconnect: success
,2015-11-20T12:11:46.536Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:11:46.541Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:11:46.541Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:11:46.557Z SendDataConnector.js: CLIENT is closed
,2015-11-20 13:11:47.552 ThaliTest[1046:730123] jxcore: disconnect
2015-11-20 13:11:47.553 ThaliTest[1046:730123] jxcore: disconnect: fail
2015-11-20T12:11:47.554Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q=,=
2015-11-20T12:11:47.554Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5-1_PT2716.py/N2Q== with availability status: true
2015-11-20T12:11:47.555Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:11:47.555Z SendDataConnector.js: do connect now
,2015-11-20 13:11:47.556 ThaliTest[1046:730123] jxcore: connect Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:11:47.557 ThaliTest[1046:730123] client session: connect
2015-11-20 13:11:47.558 ThaliTest[1046:730123] client session: stateChange:0->1 Apple-Iphone5-1_PT2716.py/N2Q==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,2015-11-20 13:11:50.797 ThaliTest[1046:729992] multipeer session: restart
,2015-11-20 13:11:50.819 ThaliTest[1046:729992] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:11:50.820 ThaliTest[1046:729992] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:11:50.822 ThaliTest[1046:729992] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
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
,-iface: IPv6 is internal : false, has ip: fe80::286a:58ff:fe89:cb
,2015-11-20 13:12:06.551 ThaliTest[1046:729992] multipeer session: reset timer
2015-11-20 13:12:06.552 ThaliTest[1046:729992] multipeer session: stop timer
2015-11-20 13:12:06.553 ThaliTest[1046:729992] multipeer session: start timer: 0x193ec200
2015-11-,20 13:12:06.553 ThaliTest[1046:729992] server session: connect
2015-11-20 13:12:06.554 ThaliTest[1046:729992] server session: stateChange:0->1 Apple-Iphone5-1_PT2716
,2015-11-20 13:12:06.560 ThaliTest[1046:729992] server: accepting invitation Apple-Iphone5-1_PT2716
,2015-11-20 13:12:08.836 ThaliTest[1046:731223] server session: connected
2015-11-20 13:12:08.836 ThaliTest[1046:731223] server session: stateChange:1->2 Apple-Iphone5-1_PT2716
,2015-11-20 13:12:08.841 ThaliTest[1046:729992] server relay: connected (to port: 55575)
,2015-11-20T12:12:08.849Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:12:20.564 ThaliTest[1046:731520] client session: not connected Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:20.565 ThaliTest[1046:731520] client session: onLinkFailure: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:20.566 ThaliTest[1,046:731520] client session: disconnect
2015-11-20 13:12:20.566 ThaliTest[1046:731520] client session: stateChange:1->0 Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:20.567 ThaliTest[1046:731520] client session: fireConnectCallback: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:20.567 ThaliTest[1046:731520] jxcore: connect: fail: Peer disconnected
,2015-11-20T12:12:20.571Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T12:12:20.571Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-20T12:12:20.572Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:12:21.579Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:21.579Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:22.587 ThaliTest[1046:730123] jxcore: disconnect
2015-11-20 13:12:22.588 ThaliTest[1046:730123] jxcore: disconnect: fail
2015-11-20T12:12:22.589Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:22.589Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT2716.py/N2Q== with availability status: true
,2015-11-20T12:12:22.590Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:22.590Z SendDataConnector.js: do connect now
,2015-11-20 13:12:22.591 ThaliTest[1046:730123] jxcore: connect Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:22.592 ThaliTest[1046:730123] client session: connect
2015-11-20 13:12:22.592 ThaliTest[1046:730123] client session: stateChange:0->1 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:23.400Z SendDataTCPServer.js: TCP/IP server has received 5952 bytes of data
,2015-11-20T12:12:23.415Z SendDataTCPServer.js: TCP/IP server has received 17856 bytes of data
,2015-11-20T12:12:23.432Z SendDataTCPServer.js: TCP/IP server has received 32736 bytes of data
,2015-11-20T12:12:23.444Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-11-20T12:12:23.458Z SendDataTCPServer.js: TCP/IP server has received 67456 bytes of data
,2015-11-20T12:12:23.472Z SendDataTCPServer.js: TCP/IP server has received 73408 bytes of data
,2015-11-20T12:12:23.533Z SendDataTCPServer.js: TCP/IP server has received 80352 bytes of data
,2015-11-20T12:12:23.546Z SendDataTCPServer.js: TCP/IP server has received 89280 bytes of data
,2015-11-20T12:12:23.560Z SendDataTCPServer.js: TCP/IP server has received 101184 bytes of data
,2015-11-20T12:12:23.575Z SendDataTCPServer.js: TCP/IP server has received 114080 bytes of data
,2015-11-20T12:12:23.592Z SendDataTCPServer.js: TCP/IP server has received 127968 bytes of data
,2015-11-20T12:12:23.606Z SendDataTCPServer.js: TCP/IP server has received 137888 bytes of data
,2015-11-20T12:12:23.620Z SendDataTCPServer.js: TCP/IP server has received 154752 bytes of data
,2015-11-20T12:12:23.635Z SendDataTCPServer.js: TCP/IP server has received 172608 bytes of data
,2015-11-20T12:12:23.650Z SendDataTCPServer.js: TCP/IP server has received 194432 bytes of data
,2015-11-20T12:12:23.665Z SendDataTCPServer.js: TCP/IP server has received 206336 bytes of data
,2015-11-20T12:12:23.680Z SendDataTCPServer.js: TCP/IP server has received 221216 bytes of data
,2015-11-20T12:12:23.718Z SendDataTCPServer.js: TCP/IP server has received 229152 bytes of data
,2015-11-20T12:12:23.730Z SendDataTCPServer.js: TCP/IP server has received 248000 bytes of data
,2015-11-20T12:12:23.744Z SendDataTCPServer.js: TCP/IP server has received 269824 bytes of data
,2015-11-20T12:12:23.758Z SendDataTCPServer.js: TCP/IP server has received 292640 bytes of data
,2015-11-20T12:12:23.774Z SendDataTCPServer.js: TCP/IP server has received 312480 bytes of data
,2015-11-20T12:12:23.786Z SendDataTCPServer.js: TCP/IP server has received 333312 bytes of data
,2015-11-20T12:12:23.801Z SendDataTCPServer.js: TCP/IP server has received 359104 bytes of data
,2015-11-20T12:12:23.876Z SendDataTCPServer.js: TCP/IP server has received 365056 bytes of data
,2015-11-20T12:12:23.979Z SendDataTCPServer.js: TCP/IP server has received 370016 bytes of data
,2015-11-20T12:12:23.995Z SendDataTCPServer.js: TCP/IP server has received 384896 bytes of data
,2015-11-20T12:12:24.010Z SendDataTCPServer.js: TCP/IP server has received 397792 bytes of data
,2015-11-20T12:12:24.025Z SendDataTCPServer.js: TCP/IP server has received 413664 bytes of data
,2015-11-20T12:12:24.039Z SendDataTCPServer.js: TCP/IP server has received 428544 bytes of data
,2015-11-20T12:12:24.052Z SendDataTCPServer.js: TCP/IP server has received 433504 bytes of data
,2015-11-20T12:12:24.069Z SendDataTCPServer.js: TCP/IP server has received 447392 bytes of data
,2015-11-20T12:12:24.082Z SendDataTCPServer.js: TCP/IP server has received 460288 bytes of data
,2015-11-20T12:12:24.095Z SendDataTCPServer.js: TCP/IP server has received 478144 bytes of data
,2015-11-20T12:12:24.109Z SendDataTCPServer.js: TCP/IP server has received 495008 bytes of data
,2015-11-20T12:12:24.122Z SendDataTCPServer.js: TCP/IP server has received 508896 bytes of data
,2015-11-20T12:12:24.134Z SendDataTCPServer.js: TCP/IP server has received 518816 bytes of data
,2015-11-20T12:12:24.148Z SendDataTCPServer.js: TCP/IP server has received 521792 bytes of data
,2015-11-20T12:12:24.160Z SendDataTCPServer.js: TCP/IP server has received 536672 bytes of data
,2015-11-20T12:12:24.177Z SendDataTCPServer.js: TCP/IP server has received 554528 bytes of data
,2015-11-20T12:12:24.189Z SendDataTCPServer.js: TCP/IP server has received 568416 bytes of data
,2015-11-20T12:12:24.203Z SendDataTCPServer.js: TCP/IP server has received 582304 bytes of data
,2015-11-20T12:12:24.219Z SendDataTCPServer.js: TCP/IP server has received 596192 bytes of data
,2015-11-20T12:12:24.232Z SendDataTCPServer.js: TCP/IP server has received 611072 bytes of data
,2015-11-20T12:12:24.244Z SendDataTCPServer.js: TCP/IP server has received 631904 bytes of data
,2015-11-20T12:12:24.257Z SendDataTCPServer.js: TCP/IP server has received 650752 bytes of data
,2015-11-20T12:12:24.269Z SendDataTCPServer.js: TCP/IP server has received 667616 bytes of data
,2015-11-20T12:12:24.284Z SendDataTCPServer.js: TCP/IP server has received 687456 bytes of data
,2015-11-20T12:12:24.298Z SendDataTCPServer.js: TCP/IP server has received 713248 bytes of data
,2015-11-20T12:12:24.312Z SendDataTCPServer.js: TCP/IP server has received 739040 bytes of data
,2015-11-20T12:12:24.326Z SendDataTCPServer.js: TCP/IP server has received 765824 bytes of data
,2015-11-20T12:12:24.338Z SendDataTCPServer.js: TCP/IP server has received 788640 bytes of data
,2015-11-20T12:12:24.352Z SendDataTCPServer.js: TCP/IP server has received 801536 bytes of data
,2015-11-20T12:12:24.378Z SendDataTCPServer.js: TCP/IP server has received 822368 bytes of data
,2015-11-20T12:12:24.392Z SendDataTCPServer.js: TCP/IP server has received 839232 bytes of data
,2015-11-20T12:12:24.419Z SendDataTCPServer.js: TCP/IP server has received 847168 bytes of data
,2015-11-20T12:12:24.432Z SendDataTCPServer.js: TCP/IP server has received 869984 bytes of data
,2015-11-20T12:12:24.496Z SendDataTCPServer.js: TCP/IP server has received 871968 bytes of data
,2015-11-20T12:12:24.508Z SendDataTCPServer.js: TCP/IP server has received 886848 bytes of data
,2015-11-20T12:12:24.523Z SendDataTCPServer.js: TCP/IP server has received 901728 bytes of data
,2015-11-20T12:12:24.535Z SendDataTCPServer.js: TCP/IP server has received 918592 bytes of data
,2015-11-20T12:12:24.549Z SendDataTCPServer.js: TCP/IP server has received 932016 bytes of data
,2015-11-20T12:12:26.535Z SendDataTCPServer.js: TCP/IP server has received 940944 bytes of data
,2015-11-20T12:12:26.550Z SendDataTCPServer.js: TCP/IP server has received 956816 bytes of data
,2015-11-20T12:12:26.565Z SendDataTCPServer.js: TCP/IP server has received 967728 bytes of data
,2015-11-20T12:12:26.579Z SendDataTCPServer.js: TCP/IP server has received 982608 bytes of data
,2015-11-20T12:12:26.594Z SendDataTCPServer.js: TCP/IP server has received 994512 bytes of data
,2015-11-20T12:12:26.609Z SendDataTCPServer.js: TCP/IP server has received 995504 bytes of data
,2015-11-20T12:12:26.623Z SendDataTCPServer.js: TCP/IP server has received 1000464 bytes of data
,2015-11-20T12:12:26.639Z SendDataTCPServer.js: TCP/IP server has received 1001456 bytes of data
,2015-11-20T12:12:26.703Z SendDataTCPServer.js: TCP/IP server has received 1003440 bytes of data
,2015-11-20T12:12:26.716Z SendDataTCPServer.js: TCP/IP server has received 1012368 bytes of data
,2015-11-20T12:12:26.731Z SendDataTCPServer.js: TCP/IP server has received 1022288 bytes of data
,2015-11-20T12:12:26.744Z SendDataTCPServer.js: TCP/IP server has received 1031216 bytes of data
,2015-11-20T12:12:26.760Z SendDataTCPServer.js: TCP/IP server has received 1043120 bytes of data
,2015-11-20T12:12:26.776Z SendDataTCPServer.js: TCP/IP server has received 1053040 bytes of data
,2015-11-20T12:12:26.788Z SendDataTCPServer.js: TCP/IP server has received 1064944 bytes of data
,2015-11-20T12:12:26.803Z SendDataTCPServer.js: TCP/IP server has received 1075856 bytes of data
,2015-11-20T12:12:26.816Z SendDataTCPServer.js: TCP/IP server has received 1088752 bytes of data
,2015-11-20T12:12:26.829Z SendDataTCPServer.js: TCP/IP server has received 1103632 bytes of data
,2015-11-20T12:12:26.842Z SendDataTCPServer.js: TCP/IP server has received 1115536 bytes of data
,2015-11-20T12:12:26.855Z SendDataTCPServer.js: TCP/IP server has received 1129424 bytes of data
,2015-11-20T12:12:26.868Z SendDataTCPServer.js: TCP/IP server has received 1147280 bytes of data
,2015-11-20T12:12:26.881Z SendDataTCPServer.js: TCP/IP server has received 1159184 bytes of data
,2015-11-20T12:12:26.893Z SendDataTCPServer.js: TCP/IP server has received 1176048 bytes of data
,2015-11-20T12:12:26.907Z SendDataTCPServer.js: TCP/IP server has received 1191920 bytes of data
,2015-11-20T12:12:26.921Z SendDataTCPServer.js: TCP/IP server has received 1216720 bytes of data
,2015-11-20T12:12:26.934Z SendDataTCPServer.js: TCP/IP server has received 1233584 bytes of data
,2015-11-20T12:12:26.947Z SendDataTCPServer.js: TCP/IP server has received 1255408 bytes of data
,2015-11-20T12:12:26.960Z SendDataTCPServer.js: TCP/IP server has received 1276240 bytes of data
,2015-11-20T12:12:26.987Z SendDataTCPServer.js: TCP/IP server has received 1283184 bytes of data
,2015-11-20T12:12:26.999Z SendDataTCPServer.js: TCP/IP server has received 1306000 bytes of data
,2015-11-20T12:12:27.012Z SendDataTCPServer.js: TCP/IP server has received 1314928 bytes of data
,2015-11-20T12:12:27.024Z SendDataTCPServer.js: TCP/IP server has received 1329808 bytes of data
,2015-11-20T12:12:27.037Z SendDataTCPServer.js: TCP/IP server has received 1354608 bytes of data
,2015-11-20T12:12:27.051Z SendDataTCPServer.js: TCP/IP server has received 1373456 bytes of data
,2015-11-20T12:12:27.125Z SendDataTCPServer.js: TCP/IP server has received 1382384 bytes of data
,2015-11-20T12:12:27.138Z SendDataTCPServer.js: TCP/IP server has received 1398256 bytes of data
,2015-11-20T12:12:27.150Z SendDataTCPServer.js: TCP/IP server has received 1412144 bytes of data
,2015-11-20T12:12:27.164Z SendDataTCPServer.js: TCP/IP server has received 1427024 bytes of data
,2015-11-20T12:12:27.176Z SendDataTCPServer.js: TCP/IP server has received 1440912 bytes of data
,2015-11-20T12:12:27.190Z SendDataTCPServer.js: TCP/IP server has received 1455792 bytes of data
,2015-11-20T12:12:27.202Z SendDataTCPServer.js: TCP/IP server has received 1469680 bytes of data
,2015-11-20T12:12:27.214Z SendDataTCPServer.js: TCP/IP server has received 1486544 bytes of data
,2015-11-20T12:12:27.228Z SendDataTCPServer.js: TCP/IP server has received 1507376 bytes of data
,2015-11-20T12:12:27.242Z SendDataTCPServer.js: TCP/IP server has received 1531184 bytes of data
,2015-11-20T12:12:27.255Z SendDataTCPServer.js: TCP/IP server has received 1551024 bytes of data
,2015-11-20T12:12:27.267Z SendDataTCPServer.js: TCP/IP server has received 1570864 bytes of data
,2015-11-20T12:12:27.280Z SendDataTCPServer.js: TCP/IP server has received 1589712 bytes of data
,2015-11-20T12:12:27.292Z SendDataTCPServer.js: TCP/IP server has received 1607568 bytes of data
,2015-11-20T12:12:27.304Z SendDataTCPServer.js: TCP/IP server has received 1624432 bytes of data
,2015-11-20T12:12:27.317Z SendDataTCPServer.js: TCP/IP server has received 1644272 bytes of data
,2015-11-20T12:12:27.329Z SendDataTCPServer.js: TCP/IP server has received 1660144 bytes of data
,2015-11-20T12:12:27.341Z SendDataTCPServer.js: TCP/IP server has received 1674032 bytes of data
,2015-11-20T12:12:27.354Z SendDataTCPServer.js: TCP/IP server has received 1692880 bytes of data
,2015-11-20T12:12:27.367Z SendDataTCPServer.js: TCP/IP server has received 1710736 bytes of data
,2015-11-20T12:12:27.379Z SendDataTCPServer.js: TCP/IP server has received 1728592 bytes of data
,2015-11-20T12:12:27.391Z SendDataTCPServer.js: TCP/IP server has received 1746448 bytes of data
,2015-11-20T12:12:27.404Z SendDataTCPServer.js: TCP/IP server has received 1766288 bytes of data
,2015-11-20T12:12:27.417Z SendDataTCPServer.js: TCP/IP server has received 1787120 bytes of data
,2015-11-20T12:12:27.430Z SendDataTCPServer.js: TCP/IP server has received 1806960 bytes of data
,2015-11-20T12:12:27.443Z SendDataTCPServer.js: TCP/IP server has received 1815888 bytes of data
,2015-11-20T12:12:27.456Z SendDataTCPServer.js: TCP/IP server has received 1847632 bytes of data
,2015-11-20T12:12:27.468Z SendDataTCPServer.js: TCP/IP server has received 1868464 bytes of data
,2015-11-20T12:12:27.482Z SendDataTCPServer.js: TCP/IP server has received 1887312 bytes of data
,2015-11-20T12:12:27.494Z SendDataTCPServer.js: TCP/IP server has received 1912112 bytes of data
,2015-11-20T12:12:27.508Z SendDataTCPServer.js: TCP/IP server has received 1930960 bytes of data
,2015-11-20T12:12:27.521Z SendDataTCPServer.js: TCP/IP server has received 1937904 bytes of data
,2015-11-20T12:12:27.533Z SendDataTCPServer.js: TCP/IP server has received 1966672 bytes of data
,2015-11-20T12:12:27.547Z SendDataTCPServer.js: TCP/IP server has received 1980560 bytes of data
,2015-11-20T12:12:27.647Z SendDataTCPServer.js: TCP/IP server has received 1990480 bytes of data
,2015-11-20T12:12:27.661Z SendDataTCPServer.js: TCP/IP server has received 2012304 bytes of data
,2015-11-20T12:12:27.678Z SendDataTCPServer.js: TCP/IP server has received 2034128 bytes of data
,2015-11-20T12:12:27.693Z SendDataTCPServer.js: TCP/IP server has received 2045040 bytes of data
,2015-11-20T12:12:27.707Z SendDataTCPServer.js: TCP/IP server has received 2062896 bytes of data
,2015-11-20T12:12:27.722Z SendDataTCPServer.js: TCP/IP server has received 2082736 bytes of data
,2015-11-20T12:12:27.736Z SendDataTCPServer.js: TCP/IP server has received 2104560 bytes of data
,2015-11-20T12:12:27.748Z SendDataTCPServer.js: TCP/IP server has received 2125392 bytes of data
,2015-11-20T12:12:27.760Z SendDataTCPServer.js: TCP/IP server has received 2143248 bytes of data
,2015-11-20T12:12:27.772Z SendDataTCPServer.js: TCP/IP server has received 2160112 bytes of data
,2015-11-20T12:12:27.785Z SendDataTCPServer.js: TCP/IP server has received 2178960 bytes of data
,2015-11-20T12:12:27.797Z SendDataTCPServer.js: TCP/IP server has received 2198800 bytes of data
,2015-11-20T12:12:27.809Z SendDataTCPServer.js: TCP/IP server has received 2216656 bytes of data
,2015-11-20T12:12:27.821Z SendDataTCPServer.js: TCP/IP server has received 2236496 bytes of data
,2015-11-20T12:12:27.834Z SendDataTCPServer.js: TCP/IP server has received 2259312 bytes of data
,2015-11-20T12:12:27.846Z SendDataTCPServer.js: TCP/IP server has received 2282128 bytes of data
,2015-11-20T12:12:27.859Z SendDataTCPServer.js: TCP/IP server has received 2299984 bytes of data
,2015-11-20T12:12:27.870Z SendDataTCPServer.js: TCP/IP server has received 2318832 bytes of data
,2015-11-20T12:12:27.883Z SendDataTCPServer.js: TCP/IP server has received 2339664 bytes of data
,2015-11-20T12:12:27.896Z SendDataTCPServer.js: TCP/IP server has received 2359504 bytes of data
,2015-11-20T12:12:27.909Z SendDataTCPServer.js: TCP/IP server has received 2380336 bytes of data
,2015-11-20T12:12:27.921Z SendDataTCPServer.js: TCP/IP server has received 2402160 bytes of data
,2015-11-20T12:12:27.934Z SendDataTCPServer.js: TCP/IP server has received 2422992 bytes of data
,2015-11-20T12:12:27.945Z SendDataTCPServer.js: TCP/IP server has received 2443824 bytes of data
,2015-11-20T12:12:27.958Z SendDataTCPServer.js: TCP/IP server has received 2466640 bytes of data
,2015-11-20T12:12:27.970Z SendDataTCPServer.js: TCP/IP server has received 2476560 bytes of data
,2015-11-20T12:12:27.983Z SendDataTCPServer.js: TCP/IP server has received 2506320 bytes of data
,2015-11-20T12:12:27.995Z SendDataTCPServer.js: TCP/IP server has received 2533104 bytes of data
,2015-11-20T12:12:28.008Z SendDataTCPServer.js: TCP/IP server has received 2534096 bytes of data
,2015-11-20T12:12:28.033Z SendDataTCPServer.js: TCP/IP server has received 2538064 bytes of data
,2015-11-20T12:12:28.045Z SendDataTCPServer.js: TCP/IP server has received 2555920 bytes of data
,2015-11-20T12:12:28.058Z SendDataTCPServer.js: TCP/IP server has received 2574768 bytes of data
,2015-11-20T12:12:28.071Z SendDataTCPServer.js: TCP/IP server has received 2588656 bytes of data
,2015-11-20T12:12:28.084Z SendDataTCPServer.js: TCP/IP server has received 2593616 bytes of data
,2015-11-20T12:12:28.097Z SendDataTCPServer.js: TCP/IP server has received 2618416 bytes of data
,2015-11-20T12:12:28.111Z SendDataTCPServer.js: TCP/IP server has received 2619408 bytes of data
,2015-11-20T12:12:28.172Z SendDataTCPServer.js: TCP/IP server has received 2624368 bytes of data
,2015-11-20T12:12:28.184Z SendDataTCPServer.js: TCP/IP server has received 2637264 bytes of data
,2015-11-20T12:12:28.199Z SendDataTCPServer.js: TCP/IP server has received 2651152 bytes of data
,2015-11-20T12:12:28.210Z SendDataTCPServer.js: TCP/IP server has received 2663056 bytes of data
,2015-11-20T12:12:28.222Z SendDataTCPServer.js: TCP/IP server has received 2682896 bytes of data
,2015-11-20T12:12:28.235Z SendDataTCPServer.js: TCP/IP server has received 2700752 bytes of data
,2015-11-20T12:12:28.249Z SendDataTCPServer.js: TCP/IP server has received 2719600 bytes of data
,2015-11-20T12:12:28.262Z SendDataTCPServer.js: TCP/IP server has received 2736464 bytes of data
,2015-11-20T12:12:28.274Z SendDataTCPServer.js: TCP/IP server has received 2754320 bytes of data
,2015-11-20T12:12:28.286Z SendDataTCPServer.js: TCP/IP server has received 2773168 bytes of data
,2015-11-20T12:12:28.299Z SendDataTCPServer.js: TCP/IP server has received 2792016 bytes of data
,2015-11-20T12:12:28.310Z SendDataTCPServer.js: TCP/IP server has received 2807888 bytes of data
,2015-11-20T12:12:28.322Z SendDataTCPServer.js: TCP/IP server has received 2827728 bytes of data
,2015-11-20T12:12:28.335Z SendDataTCPServer.js: TCP/IP server has received 2850544 bytes of data
,2015-11-20T12:12:28.348Z SendDataTCPServer.js: TCP/IP server has received 2873360 bytes of data
,2015-11-20T12:12:28.360Z SendDataTCPServer.js: TCP/IP server has received 2893200 bytes of data
,2015-11-20T12:12:28.372Z SendDataTCPServer.js: TCP/IP server has received 2915024 bytes of data
,2015-11-20T12:12:28.385Z SendDataTCPServer.js: TCP/IP server has received 2934864 bytes of data
,2015-11-20T12:12:28.398Z SendDataTCPServer.js: TCP/IP server has received 2957680 bytes of data
,2015-11-20T12:12:28.412Z SendDataTCPServer.js: TCP/IP server has received 2978512 bytes of data
,2015-11-20T12:12:28.422Z SendDataTCPServer.js: TCP/IP server has received 2995376 bytes of data
,2015-11-20T12:12:28.435Z SendDataTCPServer.js: TCP/IP server has received 3012240 bytes of data
,2015-11-20T12:12:28.447Z SendDataTCPServer.js: TCP/IP server has received 3032080 bytes of data
,2015-11-20T12:12:28.459Z SendDataTCPServer.js: TCP/IP server has received 3050928 bytes of data
,2015-11-20T12:12:28.471Z SendDataTCPServer.js: TCP/IP server has received 3070768 bytes of data
,2015-11-20T12:12:28.483Z SendDataTCPServer.js: TCP/IP server has received 3088624 bytes of data
,2015-11-20T12:12:28.495Z SendDataTCPServer.js: TCP/IP server has received 3090608 bytes of data
,2015-11-20T12:12:28.595Z SendDataTCPServer.js: TCP/IP server has received 3092592 bytes of data
,2015-11-20T12:12:28.608Z SendDataTCPServer.js: TCP/IP server has received 3108464 bytes of data
,2015-11-20T12:12:28.620Z SendDataTCPServer.js: TCP/IP server has received 3126320 bytes of data
,2015-11-20T12:12:28.632Z SendDataTCPServer.js: TCP/IP server has received 3146160 bytes of data
,2015-11-20T12:12:28.646Z SendDataTCPServer.js: TCP/IP server has received 3153104 bytes of data
,2015-11-20T12:12:28.706Z SendDataTCPServer.js: TCP/IP server has received 3154096 bytes of data
,2015-11-20T12:12:28.718Z SendDataTCPServer.js: TCP/IP server has received 3161040 bytes of data
,2015-11-20T12:12:28.732Z SendDataTCPServer.js: TCP/IP server has received 3168976 bytes of data
,2015-11-20T12:12:28.757Z SendDataTCPServer.js: TCP/IP server has received 3170960 bytes of data
,2015-11-20T12:12:28.771Z SendDataTCPServer.js: TCP/IP server has received 3183856 bytes of data
,2015-11-20T12:12:28.786Z SendDataTCPServer.js: TCP/IP server has received 3202704 bytes of data
,2015-11-20T12:12:28.799Z SendDataTCPServer.js: TCP/IP server has received 3215600 bytes of data
,2015-11-20T12:12:28.812Z SendDataTCPServer.js: TCP/IP server has received 3228496 bytes of data
,2015-11-20T12:12:28.824Z SendDataTCPServer.js: TCP/IP server has received 3242384 bytes of data
,2015-11-20T12:12:28.836Z SendDataTCPServer.js: TCP/IP server has received 3255280 bytes of data
,2015-11-20T12:12:28.849Z SendDataTCPServer.js: TCP/IP server has received 3268176 bytes of data
,2015-11-20T12:12:28.863Z SendDataTCPServer.js: TCP/IP server has received 3282064 bytes of data
,2015-11-20T12:12:28.876Z SendDataTCPServer.js: TCP/IP server has received 3299920 bytes of data
,2015-11-20T12:12:28.889Z SendDataTCPServer.js: TCP/IP server has received 3316784 bytes of data
,2015-11-20T12:12:28.901Z SendDataTCPServer.js: TCP/IP server has received 3334640 bytes of data
,2015-11-20T12:12:28.913Z SendDataTCPServer.js: TCP/IP server has received 3352496 bytes of data
,2015-11-20T12:12:28.926Z SendDataTCPServer.js: TCP/IP server has received 3368368 bytes of data
,2015-11-20T12:12:28.938Z SendDataTCPServer.js: TCP/IP server has received 3387216 bytes of data
,2015-11-20T12:12:28.951Z SendDataTCPServer.js: TCP/IP server has received 3405072 bytes of data
,2015-11-20T12:12:28.964Z SendDataTCPServer.js: TCP/IP server has received 3427888 bytes of data
,2015-11-20T12:12:28.978Z SendDataTCPServer.js: TCP/IP server has received 3458640 bytes of data
,2015-11-20T12:12:28.990Z SendDataTCPServer.js: TCP/IP server has received 3480464 bytes of data
,2015-11-20T12:12:29.004Z SendDataTCPServer.js: TCP/IP server has received 3498320 bytes of data
,2015-11-20T12:12:29.016Z SendDataTCPServer.js: TCP/IP server has received 3500304 bytes of data
,2015-11-20T12:12:29.029Z SendDataTCPServer.js: TCP/IP server has received 3521136 bytes of data
,2015-11-20T12:12:29.042Z SendDataTCPServer.js: TCP/IP server has received 3545936 bytes of data
,2015-11-20T12:12:29.056Z SendDataTCPServer.js: TCP/IP server has received 3549904 bytes of data
,2015-11-20T12:12:29.240Z SendDataTCPServer.js: TCP/IP server has received 3550896 bytes of data
,2015-11-20T12:12:29.253Z SendDataTCPServer.js: TCP/IP server has received 3555856 bytes of data
,2015-11-20T12:12:29.267Z SendDataTCPServer.js: TCP/IP server has received 3564784 bytes of data
,2015-11-20T12:12:29.280Z SendDataTCPServer.js: TCP/IP server has received 3575696 bytes of data
,2015-11-20T12:12:29.295Z SendDataTCPServer.js: TCP/IP server has received 3581648 bytes of data
,2015-11-20T12:12:29.307Z SendDataTCPServer.js: TCP/IP server has received 3582640 bytes of data
,2015-11-20T12:12:29.321Z SendDataTCPServer.js: TCP/IP server has received 3592560 bytes of data
,2015-11-20T12:12:29.335Z SendDataTCPServer.js: TCP/IP server has received 3608432 bytes of data
,2015-11-20T12:12:29.349Z SendDataTCPServer.js: TCP/IP server has received 3624304 bytes of data
,2015-11-20T12:12:29.361Z SendDataTCPServer.js: TCP/IP server has received 3628272 bytes of data
,2015-11-20T12:12:29.373Z SendDataTCPServer.js: TCP/IP server has received 3641168 bytes of data
,2015-11-20T12:12:29.388Z SendDataTCPServer.js: TCP/IP server has received 3650096 bytes of data
,2015-11-20T12:12:29.401Z SendDataTCPServer.js: TCP/IP server has received 3662992 bytes of data
,2015-11-20T12:12:29.414Z SendDataTCPServer.js: TCP/IP server has received 3676880 bytes of data
,2015-11-20T12:12:29.428Z SendDataTCPServer.js: TCP/IP server has received 3694736 bytes of data
,2015-11-20T12:12:29.440Z SendDataTCPServer.js: TCP/IP server has received 3712592 bytes of data
,2015-11-20T12:12:29.453Z SendDataTCPServer.js: TCP/IP server has received 3724496 bytes of data
,2015-11-20T12:12:29.465Z SendDataTCPServer.js: TCP/IP server has received 3737392 bytes of data
,2015-11-20T12:12:29.477Z SendDataTCPServer.js: TCP/IP server has received 3752272 bytes of data
,2015-11-20T12:12:29.489Z SendDataTCPServer.js: TCP/IP server has received 3767152 bytes of data
,2015-11-20T12:12:29.502Z SendDataTCPServer.js: TCP/IP server has received 3783024 bytes of data
,2015-11-20T12:12:29.515Z SendDataTCPServer.js: TCP/IP server has received 3799888 bytes of data
,2015-11-20T12:12:29.528Z SendDataTCPServer.js: TCP/IP server has received 3822704 bytes of data
,2015-11-20T12:12:29.539Z SendDataTCPServer.js: TCP/IP server has received 3842544 bytes of data
,2015-11-20T12:12:29.553Z SendDataTCPServer.js: TCP/IP server has received 3869328 bytes of data
,2015-11-20T12:12:29.566Z SendDataTCPServer.js: TCP/IP server has received 3886192 bytes of data
,2015-11-20T12:12:29.589Z SendDataTCPServer.js: TCP/IP server has received 3888176 bytes of data
,2015-11-20T12:12:29.601Z SendDataTCPServer.js: TCP/IP server has received 3904048 bytes of data
,2015-11-20T12:12:29.613Z SendDataTCPServer.js: TCP/IP server has received 3920912 bytes of data
,2015-11-20T12:12:29.625Z SendDataTCPServer.js: TCP/IP server has received 3927856 bytes of data
,2015-11-20T12:12:29.749Z SendDataTCPServer.js: TCP/IP server has received 3929840 bytes of data
,2015-11-20T12:12:29.765Z SendDataTCPServer.js: TCP/IP server has received 3943728 bytes of data
,2015-11-20T12:12:29.781Z SendDataTCPServer.js: TCP/IP server has received 3956624 bytes of data
,2015-11-20T12:12:29.796Z SendDataTCPServer.js: TCP/IP server has received 3971504 bytes of data
,2015-11-20T12:12:29.809Z SendDataTCPServer.js: TCP/IP server has received 3985392 bytes of data
,2015-11-20T12:12:29.823Z SendDataTCPServer.js: TCP/IP server has received 3990352 bytes of data
,2015-11-20T12:12:29.836Z SendDataTCPServer.js: TCP/IP server has received 3993328 bytes of data
,2015-11-20T12:12:29.849Z SendDataTCPServer.js: TCP/IP server has received 4009200 bytes of data
,2015-11-20T12:12:29.861Z SendDataTCPServer.js: TCP/IP server has received 4022096 bytes of data
,2015-11-20T12:12:29.874Z SendDataTCPServer.js: TCP/IP server has received 4034992 bytes of data
,2015-11-20T12:12:29.886Z SendDataTCPServer.js: TCP/IP server has received 4050864 bytes of data
,2015-11-20T12:12:29.898Z SendDataTCPServer.js: TCP/IP server has received 4067728 bytes of data
,2015-11-20T12:12:29.911Z SendDataTCPServer.js: TCP/IP server has received 4088560 bytes of data
,2015-11-20T12:12:29.926Z SendDataTCPServer.js: TCP/IP server has received 4100464 bytes of data
,2015-11-20T12:12:29.939Z SendDataTCPServer.js: TCP/IP server has received 4115344 bytes of data
,2015-11-20T12:12:29.953Z SendDataTCPServer.js: TCP/IP server has received 4139152 bytes of data
,2015-11-20T12:12:29.965Z SendDataTCPServer.js: TCP/IP server has received 4158000 bytes of data
,2015-11-20T12:12:29.979Z SendDataTCPServer.js: TCP/IP server has received 4178832 bytes of data
,2015-11-20T12:12:29.993Z SendDataTCPServer.js: TCP/IP server has received 4200656 bytes of data
,2015-11-20T12:12:30.006Z SendDataTCPServer.js: TCP/IP server has received 4219504 bytes of data
,2015-11-20T12:12:30.019Z SendDataTCPServer.js: TCP/IP server has received 4242320 bytes of data
,2015-11-20T12:12:30.031Z SendDataTCPServer.js: TCP/IP server has received 4259184 bytes of data
,2015-11-20T12:12:30.044Z SendDataTCPServer.js: TCP/IP server has received 4283984 bytes of data
,2015-11-20T12:12:30.055Z SendDataTCPServer.js: TCP/IP server has received 4307792 bytes of data
,2015-11-20T12:12:30.069Z SendDataTCPServer.js: TCP/IP server has received 4318704 bytes of data
,2015-11-20T12:12:30.081Z SendDataTCPServer.js: TCP/IP server has received 4329616 bytes of data
,2015-11-20T12:12:30.095Z SendDataTCPServer.js: TCP/IP server has received 4331600 bytes of data
,2015-11-20T12:12:30.108Z SendDataTCPServer.js: TCP/IP server has received 4346480 bytes of data
,2015-11-20T12:12:30.120Z SendDataTCPServer.js: TCP/IP server has received 4366320 bytes of data
,2015-11-20T12:12:30.134Z SendDataTCPServer.js: TCP/IP server has received 4368304 bytes of data
,2015-11-20T12:12:30.280Z SendDataTCPServer.js: TCP/IP server has received 4374256 bytes of data
,2015-11-20T12:12:30.293Z SendDataTCPServer.js: TCP/IP server has received 4383184 bytes of data
,2015-11-20T12:12:30.305Z SendDataTCPServer.js: TCP/IP server has received 4392112 bytes of data
,2015-11-20T12:12:30.319Z SendDataTCPServer.js: TCP/IP server has received 4400048 bytes of data
,2015-11-20T12:12:30.333Z SendDataTCPServer.js: TCP/IP server has received 4409968 bytes of data
,2015-11-20T12:12:30.346Z SendDataTCPServer.js: TCP/IP server has received 4419888 bytes of data
,2015-11-20T12:12:30.360Z SendDataTCPServer.js: TCP/IP server has received 4430800 bytes of data
,2015-11-20T12:12:30.372Z SendDataTCPServer.js: TCP/IP server has received 4434768 bytes of data
,2015-11-20T12:12:30.383Z SendDataTCPServer.js: TCP/IP server has received 4451632 bytes of data
,2015-11-20T12:12:30.396Z SendDataTCPServer.js: TCP/IP server has received 4464528 bytes of data
,2015-11-20T12:12:30.409Z SendDataTCPServer.js: TCP/IP server has received 4483376 bytes of data
,2015-11-20T12:12:30.422Z SendDataTCPServer.js: TCP/IP server has received 4498256 bytes of data
,2015-11-20T12:12:30.436Z SendDataTCPServer.js: TCP/IP server has received 4515120 bytes of data
,2015-11-20T12:12:30.449Z SendDataTCPServer.js: TCP/IP server has received 4528016 bytes of data
,2015-11-20T12:12:30.461Z SendDataTCPServer.js: TCP/IP server has received 4549840 bytes of data
,2015-11-20T12:12:30.474Z SendDataTCPServer.js: TCP/IP server has received 4569680 bytes of data
,2015-11-20T12:12:30.487Z SendDataTCPServer.js: TCP/IP server has received 4587536 bytes of data
,2015-11-20T12:12:30.499Z SendDataTCPServer.js: TCP/IP server has received 4604400 bytes of data
,2015-11-20T12:12:30.512Z SendDataTCPServer.js: TCP/IP server has received 4624240 bytes of data
,2015-11-20T12:12:30.526Z SendDataTCPServer.js: TCP/IP server has received 4643088 bytes of data
,2015-11-20T12:12:30.538Z SendDataTCPServer.js: TCP/IP server has received 4660944 bytes of data
,2015-11-20T12:12:30.551Z SendDataTCPServer.js: TCP/IP server has received 4678800 bytes of data
,2015-11-20T12:12:30.563Z SendDataTCPServer.js: TCP/IP server has received 4697648 bytes of data
,2015-11-20T12:12:30.576Z SendDataTCPServer.js: TCP/IP server has received 4718480 bytes of data
,2015-11-20T12:12:30.588Z SendDataTCPServer.js: TCP/IP server has received 4725424 bytes of data
,2015-11-20T12:12:30.602Z SendDataTCPServer.js: TCP/IP server has received 4753200 bytes of data
,2015-11-20T12:12:30.614Z SendDataTCPServer.js: TCP/IP server has received 4754192 bytes of data
,2015-11-20T12:12:30.627Z SendDataTCPServer.js: TCP/IP server has received 4767088 bytes of data
,2015-11-20T12:12:30.641Z SendDataTCPServer.js: TCP/IP server has received 4768080 bytes of data
,2015-11-20T12:12:30.663Z SendDataTCPServer.js: TCP/IP server has received 4792880 bytes of data
,2015-11-20T12:12:30.677Z SendDataTCPServer.js: TCP/IP server has received 4793872 bytes of data
,2015-11-20T12:12:30.688Z SendDataTCPServer.js: TCP/IP server has received 4813712 bytes of data
,2015-11-20T12:12:30.701Z SendDataTCPServer.js: TCP/IP server has received 4834544 bytes of data
,2015-11-20T12:12:30.714Z SendDataTCPServer.js: TCP/IP server has received 4854384 bytes of data
,2015-11-20T12:12:30.728Z SendDataTCPServer.js: TCP/IP server has received 4856368 bytes of data
,2015-11-20T12:12:30.787Z SendDataTCPServer.js: TCP/IP server has received 4858352 bytes of data
,2015-11-20T12:12:30.799Z SendDataTCPServer.js: TCP/IP server has received 4869264 bytes of data
,2015-11-20T12:12:30.813Z SendDataTCPServer.js: TCP/IP server has received 4885136 bytes of data
,2015-11-20T12:12:30.825Z SendDataTCPServer.js: TCP/IP server has received 4900016 bytes of data
,2015-11-20T12:12:30.839Z SendDataTCPServer.js: TCP/IP server has received 4904976 bytes of data
,2015-11-20T12:12:30.851Z SendDataTCPServer.js: TCP/IP server has received 4918864 bytes of data
,2015-11-20T12:12:30.866Z SendDataTCPServer.js: TCP/IP server has received 4932752 bytes of data
,2015-11-20T12:12:30.879Z SendDataTCPServer.js: TCP/IP server has received 4947632 bytes of data
,2015-11-20T12:12:30.891Z SendDataTCPServer.js: TCP/IP server has received 4965488 bytes of data
,2015-11-20T12:12:30.904Z SendDataTCPServer.js: TCP/IP server has received 4979376 bytes of data
,2015-11-20T12:12:30.918Z SendDataTCPServer.js: TCP/IP server has received 4998224 bytes of data
,2015-11-20T12:12:30.932Z SendDataTCPServer.js: TCP/IP server has received 5014096 bytes of data
,2015-11-20T12:12:30.945Z SendDataTCPServer.js: TCP/IP server has received 5032944 bytes of data
,2015-11-20T12:12:30.959Z SendDataTCPServer.js: TCP/IP server has received 5051792 bytes of data
,2015-11-20T12:12:30.972Z SendDataTCPServer.js: TCP/IP server has received 5066672 bytes of data
,2015-11-20T12:12:30.986Z SendDataTCPServer.js: TCP/IP server has received 5089488 bytes of data
,2015-11-20T12:12:31.049Z SendDataTCPServer.js: TCP/IP server has received 5090480 bytes of data
,2015-11-20T12:12:31.062Z SendDataTCPServer.js: TCP/IP server has received 5112304 bytes of data
,2015-11-20T12:12:31.076Z SendDataTCPServer.js: TCP/IP server has received 5131152 bytes of data
,2015-11-20T12:12:31.186Z SendDataTCPServer.js: TCP/IP server has received 5133136 bytes of data
,2015-11-20T12:12:31.210Z SendDataTCPServer.js: TCP/IP server has received 5140080 bytes of data
,2015-11-20T12:12:31.227Z SendDataTCPServer.js: TCP/IP server has received 5158928 bytes of data
,2015-11-20T12:12:31.243Z SendDataTCPServer.js: TCP/IP server has received 5175792 bytes of data
,2015-11-20T12:12:31.260Z SendDataTCPServer.js: TCP/IP server has received 5198608 bytes of data
,2015-11-20T12:12:31.274Z SendDataTCPServer.js: TCP/IP server has received 5210512 bytes of data
,2015-11-20T12:12:31.323Z SendDataTCPServer.js: TCP/IP server has received 5221424 bytes of data
,2015-11-20 13:12:31.332 ThaliTest[1046:731536] client session: connected
2015-11-20 13:12:31.333 ThaliTest[1046:731536] client session: stateChange:1->2 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:31.339Z SendDataTCPServer.js: TCP/IP server has received 5228368 bytes of data
,2015-11-20 13:12:31.353 ThaliTest[1046:731536] client session: fireConnectCallback: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:31.354 ThaliTest[1046:731536] jxcore: connect: success
,2015-11-20T12:12:31.355Z SendDataTCPServer.js: TCP/IP server has received 5231344 bytes of data
2015-11-20T12:12:31.357Z SendDataConnector.js: CLIENT connected to 55611, error: null
2015-11-20T12:12:31.358Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:12:31.362 ThaliTest[1046:729992] client: relay established
2015-11-20 13:12:31.363 ThaliTest[1046:729992] client: new accepted socket: 0x19456a10
,2015-11-20T12:12:31.374Z SendDataTCPServer.js: TCP/IP server has received 5242256 bytes of data
,2015-11-20T12:12:31.377Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:12:36.554 ThaliTest[1046:729992] multipeer session: restart
,2015-11-20 13:12:36.668 ThaliTest[1046:729992] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:36.669 ThaliTest[1046:729992] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:12:36.669 ThaliTest[1046:729992] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:12:37.339Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:37.465Z SendDataTCPServer.js: TCP/IP server has received 5373328 bytes of data
,2015-11-20T12:12:37.473Z SendDataTCPServer.js: TCP/IP server has received 5504400 bytes of data
,2015-11-20T12:12:37.475Z SendDataTCPServer.js: TCP/IP server has received 5635472 bytes of data
,2015-11-20T12:12:37.477Z SendDataTCPServer.js: TCP/IP server has received 5766544 bytes of data
,2015-11-20T12:12:37.479Z SendDataTCPServer.js: TCP/IP server has received 5897616 bytes of data
,2015-11-20T12:12:37.485Z SendDataTCPServer.js: TCP/IP server has received 6028688 bytes of data
,2015-11-20T12:12:37.487Z SendDataTCPServer.js: TCP/IP server has received 6159760 bytes of data
,2015-11-20T12:12:37.489Z SendDataTCPServer.js: TCP/IP server has received 6290832 bytes of data
,2015-11-20T12:12:37.491Z SendDataTCPServer.js: TCP/IP server has received 6421904 bytes of data
,2015-11-20T12:12:37.496Z SendDataTCPServer.js: TCP/IP server has received 6552976 bytes of data
,2015-11-20T12:12:37.498Z SendDataTCPServer.js: TCP/IP server has received 6684048 bytes of data
,2015-11-20T12:12:37.501Z SendDataTCPServer.js: TCP/IP server has received 6815120 bytes of data
,2015-11-20T12:12:37.502Z SendDataTCPServer.js: TCP/IP server has received 6946192 bytes of data
,2015-11-20T12:12:37.506Z SendDataTCPServer.js: TCP/IP server has received 7077264 bytes of data
,2015-11-20T12:12:37.508Z SendDataTCPServer.js: TCP/IP server has received 7208336 bytes of data
,2015-11-20T12:12:37.509Z SendDataTCPServer.js: TCP/IP server has received 7339408 bytes of data
,2015-11-20T12:12:37.511Z SendDataTCPServer.js: TCP/IP server has received 7470480 bytes of data
,2015-11-20T12:12:37.513Z SendDataTCPServer.js: TCP/IP server has received 7601552 bytes of data
,2015-11-20T12:12:37.515Z SendDataTCPServer.js: TCP/IP server has received 7732624 bytes of data
,2015-11-20T12:12:37.517Z SendDataTCPServer.js: TCP/IP server has received 7863696 bytes of data
,2015-11-20T12:12:37.519Z SendDataTCPServer.js: TCP/IP server has received 7994768 bytes of data
,2015-11-20T12:12:37.521Z SendDataTCPServer.js: TCP/IP server has received 8125840 bytes of data
,2015-11-20T12:12:37.522Z SendDataTCPServer.js: TCP/IP server has received 8256912 bytes of data
,2015-11-20T12:12:37.524Z SendDataTCPServer.js: TCP/IP server has received 8387984 bytes of data
,2015-11-20T12:12:37.526Z SendDataTCPServer.js: TCP/IP server has received 8519056 bytes of data
,2015-11-20T12:12:37.528Z SendDataTCPServer.js: TCP/IP server has received 8650128 bytes of data
,2015-11-20T12:12:37.529Z SendDataTCPServer.js: TCP/IP server has received 8781200 bytes of data
,2015-11-20T12:12:37.531Z SendDataTCPServer.js: TCP/IP server has received 8912272 bytes of data
,2015-11-20T12:12:37.533Z SendDataTCPServer.js: TCP/IP server has received 9043344 bytes of data
,2015-11-20T12:12:37.534Z SendDataTCPServer.js: TCP/IP server has received 9174416 bytes of data
,2015-11-20T12:12:37.536Z SendDataTCPServer.js: TCP/IP server has received 9305488 bytes of data
,2015-11-20T12:12:37.537Z SendDataTCPServer.js: TCP/IP server has received 9436560 bytes of data
,2015-11-20T12:12:37.553Z SendDataTCPServer.js: TCP/IP server has received 9567632 bytes of data
,2015-11-20T12:12:37.555Z SendDataTCPServer.js: TCP/IP server has received 9698704 bytes of data
,2015-11-20T12:12:37.556Z SendDataTCPServer.js: TCP/IP server has received 9829776 bytes of data
,2015-11-20T12:12:37.558Z SendDataTCPServer.js: TCP/IP server has received 9960848 bytes of data
,2015-11-20T12:12:37.559Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20T12:12:37.751Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:37.751Z SendDataConnector.js: CLIENT is data received : 190000
,2015-11-20T12:12:38.188Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:38.190Z SendDataConnector.js: CLIENT is data received : 880000
,2015-11-20 13:12:38.220 ThaliTest[1046:731538] server session: not connected Apple-Iphone5-1_PT2716
,2015-11-20T12:12:38.883Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:38.884Z SendDataConnector.js: CLIENT is data received : 1630000
,2015-11-20T12:12:39.139Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:39.140Z SendDataConnector.js: CLIENT is data received : 2140000
,2015-11-20T12:12:39.445Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:39.446Z SendDataConnector.js: CLIENT is data received : 2640000
,2015-11-20T12:12:39.755Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:39.756Z SendDataConnector.js: CLIENT is data received : 3150000
,2015-11-20T12:12:39.997Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:39.997Z SendDataConnector.js: CLIENT is data received : 3620000
,2015-11-20T12:12:40.334Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:40.336Z SendDataConnector.js: CLIENT is data received : 4240000
,2015-11-20T12:12:40.815Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:40.816Z SendDataConnector.js: CLIENT is data received : 5150000
,2015-11-20T12:12:40.863Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:40.863Z SendDataConnector.js: CLIENT is data received : 5230000
,2015-11-20T12:12:41.561Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:41.563Z SendDataConnector.js: CLIENT is data received : 6320000
,2015-11-20T12:12:41.578Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:41.578Z SendDataConnector.js: CLIENT is data received : 6350000
,2015-11-20T12:12:41.899Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:41.900Z SendDataConnector.js: CLIENT is data received : 6910000
,2015-11-20T12:12:51.903Z SendDataConnector.js: Receiving data timeout now
2015-11-20T12:12:51.904Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:12:51.905Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20 13:12:51.905 ThaliTest[1046:729992] client: socket closed
2015-11-20T12:12:51.906Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 13:12:51.906 ThaliT,est[1046:729992] client relay: socket disconnected
2015-11-20T12:12:51.907Z SendDataConnector.js: CLIENT is closed
,2015-11-20 13:12:51.907 ThaliTest[1046:729992] client relay: 0x19456a10 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x193e0570 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11,-20 13:12:51.907 ThaliTest[1046:729992] client session: socket closed: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:51.908 ThaliTest[1046:729992] client session: onLinkFailure: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:51.908 ThaliTest[1046:729992] client session: disconnect
2015-11-20 13:12:51.909 ThaliTest[1046:729992] client session: stateChange:2->0 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:51.911 ThaliTest[1046:729992] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:52.917Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:52.918Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:53.927 ThaliTest[1046:730123] jxcore: disconnect
2015-11-20 13:12:53.927 ThaliTest[1046:730123] jxcore: disconnect: fail
,2015-11-20T12:12:53.928Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:53.929Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT2716.py/N2Q== with availability status: true
,2015-11-20T12:12:53.930Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:53.930Z SendDataConnector.js: do connect now
,2015-11-20 13:12:53.931 ThaliTest[1046:730123] jxcore: connect Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:53.932 ThaliTest[1046:730123] client session: connect
2015-11-20 13:12:53.932 ThaliTest[1046:730123] client session: stateChange:0->1 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:57.582 ThaliTest[1046:729992] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:13:05.906 ThaliTest[1046:731607] client session: connected
2015-11-20 13:13:05.907 ThaliTest[1046:731607] client session: stateChange:1->2 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:13:05.912 ThaliTest[1046:731536] client session: fireConnectCallback: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:13:05.913 ThaliTest[1046:731536] jxcore: connect: success
2015-11-20T12:13:05.915Z SendDataConnector.js: CLIENT connected to, 55615, error: null
2015-11-20T12:13:05.915Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:13:05.918 ThaliTest[1046:729992] client: relay established
2015-11-20 13:13:05.919 ThaliTest[1046:729992] client: new accepted socket: 0x14e13690
,2015-11-20T12:13:05.931Z SendDataConnector.js: CLIENT now sending 3090000 bytes of data
,2015-11-20 13:13:06.551 ThaliTest[1046:729992] multipeer session: restart
,2015-11-20 13:13:06.561 ThaliTest[1046:729992] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:13:06.561 ThaliTest[1046:729992] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:13:06.564 ThaliTest[1046:729992] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:13:07.302Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:13:08.300Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:13:08.301Z SendDataConnector.js: CLIENT is data received : 7160000
,2015-11-20T12:13:08.366Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:13:08.367Z SendDataConnector.js: CLIENT is data received : 7290000
,2015-11-20T12:13:08.813Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:13:08.814Z SendDataConnector.js: CLIENT is data received : 7970000
,2015-11-20T12:13:09.617Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:13:09.618Z SendDataConnector.js: CLIENT is data received : 8680000
,2015-11-20T12:13:09.779Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:13:09.779Z SendDataConnector.js: CLIENT is data received : 9000000
,2015-11-20T12:13:10.712Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:13:10.713Z SendDataConnector.js: CLIENT is data received : 9770000
,2015-11-20T12:13:10.726Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:13:10.727Z SendDataConnector.js: CLIENT is data received : 9800000
,2015-11-20T12:13:10.738Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:13:10.739Z SendDataConnector.js: CLIENT is data received : 9830000
,2015-11-20T12:13:10.751Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:13:10.752Z SendDataConnector.js: CLIENT is data received : 9850000
,2015-11-20T12:13:10.764Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:13:10.764Z SendDataConnector.js: CLIENT is data received : 9870000
,2015-11-20T12:13:10.779Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:13:10.780Z SendDataConnector.js: CLIENT is data received : 9910000
,2015-11-20T12:13:10.793Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:13:10.794Z SendDataConnector.js: CLIENT is data received : 9940000
,2015-11-20T12:13:10.806Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:13:10.807Z SendDataConnector.js: CLIENT is data received : 9980000
,2015-11-20T12:13:10.819Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:13:10.820Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:13:10.821Z SendDataConnector.js: got all data for this round
,2015-11-20T12:13:10.821Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:13:10.822Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:13:10.823 ThaliTest[1046:730123] jxcore: disconnect
2015-11-20 13:13:10.824 ThaliTest[1046:730123] client session: disconnectFromPeer: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:13:10.824 ThaliTest[1046:730123] client session: disconnect,
2015-11-20 13:13:10.825 ThaliTest[1046:730123] client session: stateChange:2->0 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:13:10.827 ThaliTest[1046:730123] jxcore: disconnect: success
2015-11-20T12:13:10.830Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q==
,---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT2043","time":173751,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT497.PdI1bg==","time":31207,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT7072.5zbvNA==","time":57845,"result":"OK","connections":2},{"name":"Apple-Iphone5-1_PT2716.py/N2Q==","time":84289,"result":"OK","connections":3}]}
,sendList : 100% : 84289 ms, 99% : 84289 ms, 95 : 84289 ms, 90% : 84289 ms.
,Result count 3, range 31207 ms to  84289 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-20T12:13:10.843Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:13:10.858Z SendDataConnector.js: CLIENT is closed
,2015-11-20 13:13:36.552 ThaliTest[1046:729992] multipeer session: restart
,2015-11-20 13:13:36.570 ThaliTest[1046:729992] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:13:36.571 ThaliTest[1046:729992] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:13:36.573 ThaliTest[1046:729992] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:13:59.965 ThaliTest[1046:729992] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:14:06.552 ThaliTest[1046:729992] multipeer session: restart
,2015-11-20 13:14:06.569 ThaliTest[1046:729992] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:14:06.570 ThaliTest[1046:729992] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:14:06.776 ThaliTest[1046:729992] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:14:28.658 ThaliTest[1046:729992] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:14:31.932 ThaliTest[1046:729992] client: lost peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:14:31.932 ThaliTest[1046:729992] client session: onPeerLost: Apple-Iphone5s-1_PT497.PdI1bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:14:36.552 ThaliTest[1046:729992] multipeer session: restart
,2015-11-20 13:14:36.569 ThaliTest[1046:729992] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:14:36.570 ThaliTest[1046:729992] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:14:37.054 ThaliTest[1046:729992] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-11-20 13:14:42.702 ThaliTest[1046:730123] jxcore: stopBroadcasting
2015-11-20 13:14:42.702 ThaliTest[1046:730123] THEMultipeerSession stopping peer
2015-11-20 13:14:42.703 ThaliTest[1046:730123] multipeer session: stop timer
2015-11-20 13:14:42.704, ThaliTest[1046:730123] server session: disconnect
2015-11-20 13:14:42.704 ThaliTest[1046:730123] server session: stateChange:2->0 Apple-IpadAir2-1_PT7072
,2015-11-20 13:14:42.711 ThaliTest[1046:730123] server session: disconnect
2015-11-20 13:14:42.712 ThaliTest[1046:730123] server session: stateChange:2->0 Apple-Iphone5-1_PT2716
,2015-11-20 13:14:42.716 ThaliTest[1046:730123] server session: disconnect
,2015-11-20 13:14:42.722 ThaliTest[1046:730123] server session: stateChange:2->0 Apple-Iphone5s-1_PT497
,2015-11-20 13:14:42.790 ThaliTest[1046:730123] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-20T12:14:42.810Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20T12:14:42.812Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20T12:14:42.814Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20T12:14:42.815Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,2015-11-20T12:14:42.815Z SendDataTCPServer.js: TCP/IP server is close
,2015-11-20T12:14:42.816Z SendDataTCPServer.js: TCP/IP server is close
,2015-11-20T12:14:42.816Z SendDataTCPServer.js: TCP/IP server is close
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":31207,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7072.5zbvNA==\",\"time\":57845,\"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-Iphone5-1_PT2716.py/N2Q==\",\"time\":84289,\"result\":\"OK\",\"connections\":3}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT7072.5zbvNA==\",\"time\":26141,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":29961,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":31099,\"result\":\"OK\",\"connections\":1,},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":31207,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":33577,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT2716.py/N2Q==\",\"time\":52469,\"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-IpadAir2-1_PT7072.5zbvNA==\",\"time\":57845,\"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":58779,\"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-I,padAir2-1_PT7072.5zbvNA==\",\"time\":70969,\"result\":\"OK\",\"connections\":3},{\"name\":\"Apple-Iphone5-1_PT2716.py/N2Q==\",\"time\":84289,\"result\":\"OK\",\"connections\":3},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":107161,\"result\":\"OK\,",\"connections\":4}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
