#### Test 513350289b9c5d6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350289b9c5d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5FF6BBD0-EAE2-4B46-AC03-E3D6840BF512/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/5FF6BBD0-EAE2-4B46-AC03-E3D6840BF512/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350289b9c5d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350289b9c5d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DA9086A0-8F5A-40A6-9178-84A96E377AC2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52799"
,(lldb)     command script import "/tmp/5FF6BBD0-EAE2-4B46-AC03-E3D6840BF512/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 12:30:48.059 ThaliTest[1361:1059962] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B8665FEB-1CE3-409D-BF8D-7CCDEC43F85C/Library/Cookies/Cookies.binarycookies
,2015-11-23 12:30:48.461 ThaliTest[1361:1059962] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 12:30:48.462 ThaliTest[1361:1059962] Multi-tasking -> Device: YES, App: YES
,2015-11-23 12:30:48.472 ThaliTest[1361:1059962] Unlimited access to network resources
,2015-11-23 12:30:48.477 ThaliTest[1361:1059962] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 12:30:52.072 ThaliTest[1361:1059962] Resetting plugins due to page load.
,2015-11-23 12:30:52.416 ThaliTest[1361:1059962] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/DA9086A0-8F5A-40A6-9178-84A96E377AC2/ThaliTest.app/www/index.html
,2015-11-23 12:30:52.539 ThaliTest[1361:1059962] JXcore Cordova plugin initializing
,2015-11-23 12:30:52.540 ThaliTest[1361:1060097] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
Warning: iOS does not support ToggleBluetooth
We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
,toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,my name is : Apple-Iphone6-1_PT7664
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
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
-iface: IPv4 is internal : false, has ip: 192.168.1.126
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10fe:7f1b:7de:ecb2
,-iface: IPv4 is internal : false, has ip: 192.168.1.126
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
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
,-iface: IPv6 is internal : false, has ip: fe80::bc01:b1ff:fe9c:586a
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 56887
2015-11-23 12:36:42.093 ThaliTest[1361:1060097] jxcore: startBroadcasting
,2015-11-23 12:36:42.107 ThaliTest[1361:1060097] server: starting Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:42.109 ThaliTest[1361:1060097] multipeer session: start timer: 0x1b67fe60
,2015-11-23 12:36:42.110 ThaliTest[1361:1060097] THEMultipeerSession initialized peer Apple-Iphone6-1_PT7664
2015-11-23 12:36:42.111 ThaliTest[1361:1060097] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-23T11:36:42.113Z SendData,TCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-23 12:36:42.477 ThaliTest[1361:1059962] multipeer session: reset timer
2015-11-23 12:36:42.477 ThaliTest[1361:1059962] multipeer session: stop timer
2015-11-23 12:36:42.478 ThaliTest[1361:1059962] multipeer session: start timer: 0x1b67fe60
2015-,11-23 12:36:42.479 ThaliTest[1361:1059962] server session: connect
2015-11-23 12:36:42.479 ThaliTest[1361:1059962] server session: stateChange:0->1 Apple-Iphone5-1_PT142
,2015-11-23 12:36:42.490 ThaliTest[1361:1059962] server: accepting invitation Apple-Iphone5-1_PT142
2015-11-23 12:36:42.498 ThaliTest[1361:1059962] client: found peer: Apple-Iphone5s-1_PT8005.g0Za/g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne5s-1_PT8005.g0Za/g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[1]: Apple-Iphone5s-1_PT8005.g0Za/g==
2015-11-23T11:36:42.509Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8005.g0Za/g==
2,015-11-23T11:36:42.510Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8005.g0Za/g==
2015-11-23T11:36:42.510Z SendDataConnector.js: do connect now
2015-11-23 12:36:42.511 ThaliTest[1361:1060097] jxcore: connect Apple-Iphone5s-1_PT800,5.g0Za/g==
2015-11-23 12:36:42.511 ThaliTest[1361:1060097] client session: connect
2015-11-23 12:36:42.512 ThaliTest[1361:1060097] client session: stateChange:0->1 Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23 12:36:42.786 ThaliTest[1361:1059962] multipeer session: reset timer
2015-11-23 12:36:42.786 ThaliTest[1361:1059962] multipeer session: stop timer
2015-11-23 12:36:42.786 ThaliTest[1361:1059962] multipeer session: start timer: 0x1b67fe60
2015-,11-23 12:36:42.786 ThaliTest[1361:1059962] server session: connect
2015-11-23 12:36:42.787 ThaliTest[1361:1059962] server session: stateChange:0->1 Apple-IpadAir2-1_PT6529
,2015-11-23 12:36:42.792 ThaliTest[1361:1059962] server: accepting invitation Apple-IpadAir2-1_PT6529
,2015-11-23 12:36:43.056 ThaliTest[1361:1059962] client: found peer: Apple-IpadAir2-1_PT6529.Z02MaA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6529.Z02MaA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 12:36:43.430 ThaliTest[1361:1059962] client: found peer: Apple-Iphone5-1_PT142.u6yj7g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT142.u6yj7g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 12:36:43.870 ThaliTest[1361:1059962] multipeer session: reset timer
2015-11-23 12:36:43.871 ThaliTest[1361:1059962] multipeer session: stop timer
2015-11-23 12:36:43.871 ThaliTest[1361:1059962] multipeer session: start timer: 0x1b67fe60
2015-,11-23 12:36:43.872 ThaliTest[1361:1059962] server session: connect
2015-11-23 12:36:43.872 ThaliTest[1361:1059962] server session: stateChange:0->1 Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:43.883 ThaliTest[1361:1059962] server: accepting invitation Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:44.805 ThaliTest[1361:1060607] server session: connected
2015-11-23 12:36:44.806 ThaliTest[1361:1060607] server session: stateChange:1->2 Apple-Iphone5-1_PT142
,2015-11-23 12:36:44.815 ThaliTest[1361:1059962] server relay: connected (to port: 56887)
2015-11-23T11:36:44.816Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T11:36:44.969Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-11-23 12:36:44.969 ThaliTest[1361:1060605] client session: connected
,2015-11-23 12:36:44.971 ThaliTest[1361:1060605] client session: stateChange:1->2 Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23 12:36:44.979 ThaliTest[1361:1060605] client session: fireConnectCallback: Apple-Iphone5s-1_PT8005.g0Za/g==
2015-11-23 12:36:44.980 ThaliTest[1361:1060605] jxcore: connect: success
2015-11-23T11:36:44.983Z SendDataTCPServer.js: TCP/IP server ha,s received 8928 bytes of data
2015-11-23T11:36:44.986Z SendDataConnector.js: CLIENT connected to 56891, error: null
2015-11-23T11:36:44.986Z SendDataConnector.js: CLIENT starting client 
2015-11-23 12:36:44.990 ThaliTest[1361:1059962] client: relay esta,blished
2015-11-23 12:36:44.991 ThaliTest[1361:1059962] client: new accepted socket: 0x1b68f4a0
,2015-11-23T11:36:45.004Z SendDataTCPServer.js: TCP/IP server has received 20832 bytes of data
,2015-11-23T11:36:45.008Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T11:36:45.142Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23T11:36:45.182Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-23T11:36:45.196Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-23 12:36:45.200 ThaliTest[1361:1060605] server session: not connected Apple-Iphone5-1_PT142
,2015-11-23T11:36:45.206Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-23T11:36:45.220Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-23 12:36:45.265 ThaliTest[1361:1060605] server session: connected
2015-11-23 12:36:45.265 ThaliTest[1361:1060605] server session: stateChange:1->2 Apple-IpadAir2-1_PT6529
,2015-11-23 12:36:45.267 ThaliTest[1361:1059962] server relay: connected (to port: 56887)
,2015-11-23T11:36:45.269Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T11:36:45.340Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-11-23T11:36:45.353Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-11-23T11:36:45.365Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-11-23T11:36:45.366Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-23T11:36:45.366Z SendDataConnector.js: got all data for this round
,2015-11-23T11:36:45.367Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:36:45.367Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 12:36:45.368 ThaliTest[1361:1060097] jxcore: disconnect
2015-11-23 12:36:45.369 ThaliTest[1361:1060097] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8005.g0Za/g==
2015-11-23 12:36:45.369 ThaliTest[1361:1060097] client session: disconnect
2015-11-23 12:36:45.369 ThaliTest[1361:1060097] client session: stateChange:2->0 Apple-Iphone5s-1_PT8005.g0Za/g==
2015-11-23 12:36:45.371 ThaliTest[1361:1060097] jxcore: disconnect: success
2015-11-23T11:36:45.371Z SendDataConnector.js: Mobile.Disc,onnect() callback with peer Apple-Iphone5s-1_PT8005.g0Za/g==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23T11:36:45.373Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6529.Z02MaA==
,2015-11-23T11:36:45.374Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23T11:36:45.375Z SendDataConnector.js: do connect now
,2015-11-23 12:36:45.375 ThaliTest[1361:1060097] jxcore: connect Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23 12:36:45.376 ThaliTest[1361:1060097] client session: connect
2015-11-23 12:36:45.376 ThaliTest[1361:1060097] client session: stateChange:0->1 Apple-IpadAir2-1_PT6529.Z02MaA==
,2015-11-23T11:36:45.393Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 12:36:46.087 ThaliTest[1361:1060605] server session: connected
2015-11-23 12:36:46.088 ThaliTest[1361:1060605] server session: stateChange:1->2 Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:46.093 ThaliTest[1361:1059962] server relay: connected (to port: 56887)
,2015-11-23T11:36:46.103Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T11:36:46.389Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-11-23T11:36:46.410Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-11-23T11:36:46.425Z SendDataTCPServer.js: TCP/IP server has received 67748 bytes of data
,2015-11-23T11:36:46.438Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 12:36:46.467 ThaliTest[1361:1060593] server session: not connected Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:49.044 ThaliTest[1361:1060593] client session: connected
2015-11-23 12:36:49.045 ThaliTest[1361:1060593] client session: stateChange:1->2 Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23 12:36:49.047 ThaliTest[1361:1060593] client session: fi,reConnectCallback: Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23 12:36:49.048 ThaliTest[1361:1060593] jxcore: connect: success
2015-11-23T11:36:49.049Z SendDataConnector.js: CLIENT connected to 56896, error: null
2015-11-23T11:36:49.049Z SendDataConnector,.js: CLIENT starting client 
2015-11-23 12:36:49.051 ThaliTest[1361:1059962] client: relay established
2015-11-23 12:36:49.052 ThaliTest[1361:1059962] client: new accepted socket: 0x1b698110
,2015-11-23T11:36:49.062Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T11:36:49.179Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-23T11:36:49.572Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-23T11:36:49.573Z SendDataConnector.js: got all data for this round
,2015-11-23T11:36:49.574Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:36:49.575Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-23 12:36:49.576 ThaliTest[1361:1060097] jxcore: disconnect
,2015-11-23 12:36:49.576 ThaliTest[1361:1060097] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6529.Z02MaA==
,2015-11-23 12:36:49.577 ThaliTest[1361:1060097] client session: disconnect
2015-11-23 12:36:49.578 ThaliTest[1361:1060097] client session: stateChange:2->0 Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23 12:36:49.580 ThaliTest[1361:1060097] jxcore: disconnec,t: success
2015-11-23T11:36:49.581Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6529.Z02MaA==
---- round done--------
device[3]: Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23T11:36:49.583Z SendDataConnector.js: Start cal,led with peer Apple-Iphone5-1_PT142.u6yj7g==
,2015-11-23T11:36:49.583Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23T11:36:49.585Z SendDataConnector.js: do connect now
,2015-11-23 12:36:49.587 ThaliTest[1361:1060097] jxcore: connect Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23 12:36:49.588 ThaliTest[1361:1060097] client session: connect
2015-11-23 12:36:49.589 ThaliTest[1361:1060097] client session: stateChange:0->1 Apple-,Iphone5-1_PT142.u6yj7g==
,2015-11-23 12:36:52.808 ThaliTest[1361:1060580] client session: connected
2015-11-23 12:36:52.808 ThaliTest[1361:1060580] client session: stateChange:1->2 Apple-Iphone5-1_PT142.u6yj7g==
,2015-11-23 12:36:52.814 ThaliTest[1361:1060589] client session: fireConnectCallback: Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23 12:36:52.816 ThaliTest[1361:1060589] jxcore: connect: success
,2015-11-23T11:36:52.818Z SendDataConnector.js: CLIENT connected to 56899, error: null
2015-11-23T11:36:52.818Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 12:36:52.821 ThaliTest[1361:1059962] client: relay established
2015-11-23 12:36:52.822 ThaliTest[1361:1059962] client: new accepted socket: 0x16df4020
,2015-11-23T11:36:52.834Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T11:36:52.958Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-23T11:36:53.237Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-23T11:36:53.238Z SendDataConnector.js: got all data for this round
,2015-11-23T11:36:53.239Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:36:53.239Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 12:36:53.240 ThaliTest[1361:1060097] jxcore: disconnect
2015-11-23 12:36:53.241 ThaliTest[1361:1060097] client session: disconnectFromPeer: Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23 12:36:53.241 ThaliTest[1361:1060097] client session: disconne,ct
2015-11-23 12:36:53.241 ThaliTest[1361:1060097] client session: stateChange:2->0 Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23 12:36:53.243 ThaliTest[1361:1060097] jxcore: disconnect: success
2015-11-23T11:36:53.244Z SendDataConnector.js: Mobile.Disconne,ct() callback with peer Apple-Iphone5-1_PT142.u6yj7g==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT7664","time":11168,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8005.g0Za/g==","time":2857,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT6529.Z02MaA==","time":4200,"result":"OK","connections",:1},{"name":"Apple-Iphone5-1_PT142.u6yj7g==","time":3655,"result":"OK","connections":1}]}
,sendList : 100% : 4200 ms, 99% : 4200 ms, 95 : 4200 ms, 90% : 4200 ms.
,Result count 3, range 2857 ms to  4200 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-23T11:36:53.254Z SendDataConnector.js: CLIENT Stop now
,2015-11-23T11:36:53.254Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 12:36:56.524 ThaliTest[1361:1060593] server session: not connected Apple-IpadAir2-1_PT6529
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-23 12:36:59.788 ThaliTest[1361:1060097] jxcore: stopBroadcasting
,2015-11-23 12:36:59.789 ThaliTest[1361:1060097] THEMultipeerSession stopping peer
,2015-11-23 12:36:59.790 ThaliTest[1361:1060097] multipeer session: stop timer
,2015-11-23 12:36:59.791 ThaliTest[1361:1060097] server session: disconnect
2015-11-23 12:36:59.791 ThaliTest[1361:1060097] server session: stateChange:2->0 Apple-IpadAir2-1_PT6529
2015-11-23 12:36:59.799 ThaliTest[1361:1060097] server session: disconnect,
2015-11-23 12:36:59.799 ThaliTest[1361:1060097] server session: stateChange:2->0 Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:59.803 ThaliTest[1361:1060097] server session: disconnect
2015-11-23 12:36:59.804 ThaliTest[1361:1060097] server session: stateChange:2->0 Apple-Iphone5-1_PT142
,2015-11-23 12:36:59.868 ThaliTest[1361:1060097] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-23T11:36:59.887Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T11:36:59.888Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T11:36:59.890Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T11:36:59.891Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT8005.g0Za/g==\",\"time\":2857,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":3655,\"r,esult\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6529.Z02MaA==\",\"time\":4200,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT8005.g0Za,/g==\",\"time\":2857,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":2877,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":3192,\"result\":\"OK\",\"connections\":1},{\"n,ame\":\"Apple-Iphone5s-1_PT8005.g0Za/g==\",\"time\":3523,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":3655,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":3704,\"resul,t\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":3780,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6529.Z02MaA==\",\"time\":4200,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT,6529.Z02MaA==\",\"time\":4725,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6529.Z02MaA==\",\"time\":5067,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8005.g0Za/g==\",\"time\":5174,\"result\":\"OK\",\"connection,s\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":8751,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
