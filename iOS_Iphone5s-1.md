#### Test 513350289b9c5d6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350289b9c5d6/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/94057920-C8B5-4D92-87A2-D79DEC914396/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/94057920-C8B5-4D92-87A2-D79DEC914396/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350289b9c5d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350289b9c5d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/07CACB9C-FC29-485B-B7E3-990D2AE3360F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52801"
,(lldb)     command script import "/tmp/94057920-C8B5-4D92-87A2-D79DEC914396/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 12:30:51.101 ThaliTest[1306:1121087] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ED43AE2D-D9CB-4FB8-993C-797B6326682C/Library/Cookies/Cookies.binarycookies
,2015-11-23 12:30:51.499 ThaliTest[1306:1121087] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 12:30:51.500 ThaliTest[1306:1121087] Multi-tasking -> Device: YES, App: YES
,2015-11-23 12:30:51.509 ThaliTest[1306:1121087] Unlimited access to network resources
,2015-11-23 12:30:51.517 ThaliTest[1306:1121087] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 12:30:55.045 ThaliTest[1306:1121087] Resetting plugins due to page load.
,2015-11-23 12:30:55.482 ThaliTest[1306:1121087] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/07CACB9C-FC29-485B-B7E3-990D2AE3360F/ThaliTest.app/www/index.html
,2015-11-23 12:30:55.637 ThaliTest[1306:1121087] JXcore Cordova plugin initializing
2015-11-23 12:30:55.638 ThaliTest[1306:1121212] JXcore instance initializing
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
toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,my name is : Apple-Iphone5s-1_PT8005
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::7074:a4ff:fea7:2b57
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[],}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 57362
,2015-11-23 12:36:42.122 ThaliTest[1306:1121212] jxcore: startBroadcasting
,2015-11-23 12:36:42.136 ThaliTest[1306:1121212] server: starting Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23 12:36:42.138 ThaliTest[1306:1121212] multipeer session: start timer: 0x19eebc20
,2015-11-23 12:36:42.139 ThaliTest[1306:1121212] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT8005
2015-11-23 12:36:42.140 ThaliTest[1306:1121212] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-23T11:36:42.142Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-23 12:36:42.670 ThaliTest[1306:1121087] client: found peer: Apple-Iphone6-1_PT7664.8o3jhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7664.8o3jhw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7664.8o3jhw==
2015-11-23T11:36:42.680Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23T11:36:42.681Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7664.8o3jhw==
2015-11-23T11:36:42.682Z SendDataConnector.js: do connect now
2015-11-23 12:36:42.684 ThaliTest[1306:1121212] jxcore: connect Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:42.685 ThaliTest[1306:1121212] client session: connect
2015-11-23 12:36:42.687 ThaliTest[1306:1121212] client session: stateChange:0->1 Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:42.776 ThaliTest[1306:1121087] multipeer session: reset timer
2015-11-23 12:36:42.776 ThaliTest[1306:1121087] multipeer session: stop timer
2015-11-23 12:36:42.776 ThaliTest[1306:1121087] multipeer session: start timer: 0x19eebc20
2015-,11-23 12:36:42.777 ThaliTest[1306:1121087] server session: connect
2015-11-23 12:36:42.777 ThaliTest[1306:1121087] server session: stateChange:0->1 Apple-Iphone6-1_PT7664
,2015-11-23 12:36:42.781 ThaliTest[1306:1121087] server: accepting invitation Apple-Iphone6-1_PT7664
,2015-11-23 12:36:43.755 ThaliTest[1306:1121087] client: found peer: Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23 12:36:43.756 ThaliTest[1306:1121087] client: found peer: Apple-Iphone5-1_PT142.u6yj7g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipad,Air2-1_PT6529.Z02MaA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT142.u6yj7g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available,: true
,2015-11-23 12:36:44.965 ThaliTest[1306:1121693] server session: connected
2015-11-23 12:36:44.966 ThaliTest[1306:1121693] server session: stateChange:1->2 Apple-Iphone6-1_PT7664
,2015-11-23 12:36:44.986 ThaliTest[1306:1121087] server relay: connected (to port: 57362)
,2015-11-23T11:36:44.997Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T11:36:45.149Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-11-23T11:36:45.162Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-11-23T11:36:45.181Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-11-23T11:36:45.200Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-11-23T11:36:45.214Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-11-23T11:36:45.334Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 12:36:45.381 ThaliTest[1306:1121703] server session: not connected Apple-Iphone6-1_PT7664
,2015-11-23 12:36:45.406 ThaliTest[1306:1121087] multipeer session: reset timer
2015-11-23 12:36:45.407 ThaliTest[1306:1121087] multipeer session: stop timer
2015-11-23 12:36:45.407 ThaliTest[1306:1121087] multipeer session: start timer: 0x19eebc20
2015-,11-23 12:36:45.408 ThaliTest[1306:1121087] server session: connect
2015-11-23 12:36:45.409 ThaliTest[1306:1121087] server session: stateChange:0->1 Apple-Iphone5-1_PT142
,2015-11-23 12:36:45.421 ThaliTest[1306:1121087] server: accepting invitation Apple-Iphone5-1_PT142
,2015-11-23 12:36:45.793 ThaliTest[1306:1121087] multipeer session: reset timer
2015-11-23 12:36:45.793 ThaliTest[1306:1121087] multipeer session: stop timer
2015-11-23 12:36:45.794 ThaliTest[1306:1121087] multipeer session: start timer: 0x19eebc20
2015-11-23 12:36:45.794 ThaliTest[1306:1121087] server session: connect
2015-11-23 12:36:45.794 ThaliTest[1306:1121087] server session: stateChange:0->1 Apple-IpadAir2-1_PT6529
,2015-11-23 12:36:45.797 ThaliTest[1306:1121087] server: accepting invitation Apple-IpadAir2-1_PT6529
,2015-11-23 12:36:46.089 ThaliTest[1306:1121707] client session: connected
2015-11-23 12:36:46.089 ThaliTest[1306:1121707] client session: stateChange:1->2 Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:46.098 ThaliTest[1306:1121701] client session: fireConnectCallback: Apple-Iphone6-1_PT7664.8o3jhw==
2015-11-23 12:36:46.099 ThaliTest[1306:1121701] jxcore: connect: success
,2015-11-23T11:36:46.102Z SendDataConnector.js: CLIENT connected to 57367, error: null
,2015-11-23T11:36:46.103Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 12:36:46.106 ThaliTest[1306:1121087] client: relay established
,2015-11-23 12:36:46.106 ThaliTest[1306:1121087] client: new accepted socket: 0x19fa6750
,2015-11-23T11:36:46.119Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T11:36:46.409Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-23T11:36:46.420Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-23T11:36:46.433Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-23T11:36:46.446Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-23T11:36:46.459Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-23T11:36:46.459Z SendDataConnector.js: got all data for this round
,2015-11-23T11:36:46.461Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:36:46.461Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 12:36:46.462 ThaliTest[1306:1121212] jxcore: disconnect
2015-11-23 12:36:46.462 ThaliTest[1306:1121212] client session: disconnectFromPeer: Apple-Iphone6-1_PT7664.8o3jhw==
2015-11-23 12:36:46.463 ThaliTest[1306:1121212] client session: disconn,ect
2015-11-23 12:36:46.463 ThaliTest[1306:1121212] client session: stateChange:2->0 Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:46.464 ThaliTest[1306:1121212] jxcore: disconnect: success
2015-11-23T11:36:46.465Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7664.8o3jhw==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23T11:36:46.467Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23T11:36:46.467Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23T11:36:46.467Z SendDataConnector.js: do connect now
2015-11-23 12:36:46.467 ThaliTest[1306:1121212] jxcore: connect Apple-IpadAir2-1_PT6529.Z02MaA==
,2015-11-23 12:36:46.469 ThaliTest[1306:1121212] client session: connect
2015-11-23 12:36:46.469 ThaliTest[1306:1121212] client session: stateChange:0->1 Apple-IpadAir2-1_PT6529.Z02MaA==
,2015-11-23 12:36:47.564 ThaliTest[1306:1121693] server session: connected
2015-11-23 12:36:47.565 ThaliTest[1306:1121693] server session: stateChange:1->2 Apple-Iphone5-1_PT142
,2015-11-23 12:36:47.587 ThaliTest[1306:1121087] server relay: connected (to port: 57362)
2015-11-23T11:36:47.592Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T11:36:47.964Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-11-23T11:36:47.982Z SendDataTCPServer.js: TCP/IP server has received 12896 bytes of data
,2015-11-23T11:36:48.002Z SendDataTCPServer.js: TCP/IP server has received 29760 bytes of data
,2015-11-23T11:36:48.017Z SendDataTCPServer.js: TCP/IP server has received 44640 bytes of data
,2015-11-23T11:36:48.034Z SendDataTCPServer.js: TCP/IP server has received 59520 bytes of data
,2015-11-23T11:36:48.051Z SendDataTCPServer.js: TCP/IP server has received 75392 bytes of data
,2015-11-23T11:36:48.066Z SendDataTCPServer.js: TCP/IP server has received 90272 bytes of data
,2015-11-23T11:36:48.080Z SendDataTCPServer.js: TCP/IP server has received 96224 bytes of data
,2015-11-23T11:36:48.181Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 12:36:48.554 ThaliTest[1306:1121703] server session: connected
2015-11-23 12:36:48.555 ThaliTest[1306:1121703] server session: stateChange:1->2 Apple-IpadAir2-1_PT6529
,2015-11-23 12:36:48.623 ThaliTest[1306:1121087] server relay: connected (to port: 57362)
,2015-11-23T11:36:48.626Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23 12:36:48.735 ThaliTest[1306:1121701] server session: not connected Apple-Iphone5-1_PT142
,2015-11-23T11:36:49.080Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-11-23T11:36:49.132Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-11-23T11:36:49.151Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
2015-11-23T11:36:49.168Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-11-23T11:36:49.183Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 12:36:50.689 ThaliTest[1306:1121706] client session: connected
2015-11-23 12:36:50.690 ThaliTest[1306:1121706] client session: stateChange:1->2 Apple-IpadAir2-1_PT6529.Z02MaA==
,2015-11-23 12:36:50.701 ThaliTest[1306:1121701] server session: not connected Apple-IpadAir2-1_PT6529
,2015-11-23 12:36:50.709 ThaliTest[1306:1121706] client session: fireConnectCallback: Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23 12:36:50.710 ThaliTest[1306:1121706] jxcore: connect: success
2015-11-23T11:36:50.711Z SendDataConnector.js: CLIENT connected, to 57372, error: null
2015-11-23T11:36:50.712Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 12:36:50.715 ThaliTest[1306:1121087] client: relay established
,2015-11-23 12:36:50.716 ThaliTest[1306:1121087] client: new accepted socket: 0x19e708f0
,2015-11-23T11:36:50.728Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T11:36:51.179Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-23T11:36:51.191Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-23T11:36:51.191Z SendDataConnector.js: got all data for this round
,2015-11-23T11:36:51.192Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:36:51.193Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-23 12:36:51.193 ThaliTest[1306:1121212] jxcore: disconnect
,2015-11-23 12:36:51.194 ThaliTest[1306:1121212] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23 12:36:51.194 ThaliTest[1306:1121212] client session: disconnect
2015-11-23 12:36:51.194 ThaliTest[1306:1121212] client session,: stateChange:2->0 Apple-IpadAir2-1_PT6529.Z02MaA==
2015-11-23 12:36:51.197 ThaliTest[1306:1121212] jxcore: disconnect: success
,2015-11-23T11:36:51.198Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6529.Z02MaA==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23T11:36:51.200Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23T11:36:51.201Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23T11:36:51.201Z SendDataConnector.js: do connect now
,2015-11-23 12:36:51.205 ThaliTest[1306:1121212] jxcore: connect Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23 12:36:51.205 ThaliTest[1306:1121212] client session: connect
2015-11-23 12:36:51.206 ThaliTest[1306:1121212] client session: stateChange:0->1 Apple-,Iphone5-1_PT142.u6yj7g==
,2015-11-23 12:36:54.303 ThaliTest[1306:1121701] client session: connected
2015-11-23 12:36:54.303 ThaliTest[1306:1121701] client session: stateChange:1->2 Apple-Iphone5-1_PT142.u6yj7g==
,2015-11-23 12:36:54.485 ThaliTest[1306:1121706] client session: fireConnectCallback: Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23 12:36:54.486 ThaliTest[1306:1121706] jxcore: connect: success
2015-11-23T11:36:54.488Z SendDataConnector.js: CLIENT connected to 57375, error: null
,2015-11-23T11:36:54.488Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 12:36:54.492 ThaliTest[1306:1121087] client: relay established
2015-11-23 12:36:54.492 ThaliTest[1306:1121087] client: new accepted socket: 0x19e70670
,2015-11-23T11:36:54.504Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T11:36:54.857Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-23T11:36:54.868Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-23T11:36:54.904Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-23T11:36:54.905Z SendDataConnector.js: got all data for this round
,2015-11-23T11:36:54.905Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:36:54.905Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-23 12:36:54.906 ThaliTest[1306:1121212] jxcore: disconnect
,2015-11-23 12:36:54.906 ThaliTest[1306:1121212] client session: disconnectFromPeer: Apple-Iphone5-1_PT142.u6yj7g==
,2015-11-23 12:36:54.906 ThaliTest[1306:1121212] client session: disconnect
2015-11-23 12:36:54.907 ThaliTest[1306:1121212] client session: stateChange:2->0 Apple-Iphone5-1_PT142.u6yj7g==
,2015-11-23 12:36:54.908 ThaliTest[1306:1121212] jxcore: disconnect: success
2015-11-23T11:36:54.908Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT142.u6yj7g==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT8005","time":12808,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7664.8o3jhw==","time":3780,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT6529.Z02MaA==","time":4725,"result":"OK","connections":1},{"name":"Apple-Iphone5-1_PT142.u6yj7g==","time":3704,"result":"OK","connections":1}]}
,sendList : 100% : 4725 ms, 99% : 4725 ms, 95 : 4725 ms, 90% : 4725 ms.
,Result count 3, range 3704 ms to  4725 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-23T11:36:54.915Z SendDataConnector.js: CLIENT Stop now
,2015-11-23T11:36:54.915Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-11-23 12:36:59.804 ThaliTest[1306:1121212] jxcore: stopBroadcasting
2015-11-23 12:36:59.805 ThaliTest[1306:1121212] THEMultipeerSession stopping peer
2015-11-23 12:36:59.805 ThaliTest[1306:1121212] multipeer session: stop timer
2015-11-23 12:36:59.,806 ThaliTest[1306:1121212] server session: disconnect
2015-11-23 12:36:59.807 ThaliTest[1306:1121212] server session: stateChange:2->0 Apple-Iphone5-1_PT142
,2015-11-23 12:36:59.875 ThaliTest[1306:1121212] server session: disconnect
2015-11-23 12:36:59.876 ThaliTest[1306:1121212] server session: stateChange:2->0 Apple-IpadAir2-1_PT6529
,2015-11-23 12:36:59.882 ThaliTest[1306:1121212] server session: disconnect
,2015-11-23 12:36:59.883 ThaliTest[1306:1121212] server session: stateChange:2->0 Apple-Iphone6-1_PT7664
,2015-11-23 12:36:59.886 ThaliTest[1306:1121212] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-23T11:36:59.899Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T11:36:59.901Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T11:36:59.901Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T11:36:59.902Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":3704,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":3780,\"re,sult\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6529.Z02MaA==\",\"time\":4725,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT8005.g0Za/,g==\",\"time\":2857,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":2877,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":3192,\"result\":\"OK\",\"connections\":1},{\"na,me\":\"Apple-Iphone5s-1_PT8005.g0Za/g==\",\"time\":3523,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":3655,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":3704,\"result,\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":3780,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6529.Z02MaA==\",\"time\":4200,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6,529.Z02MaA==\",\"time\":4725,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6529.Z02MaA==\",\"time\":5067,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8005.g0Za/g==\",\"time\":5174,\"result\":\"OK\",\"connections,\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":8751,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
