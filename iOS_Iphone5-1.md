#### Test 51335028e04ad51_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028e04ad51/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/63B8F9E6-C569-41EC-A9F3-329C2AB25510/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/63B8F9E6-C569-41EC-A9F3-329C2AB25510/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028e04ad51/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028e04ad51/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/9FB02BB2-C4DF-4341-96F1-64C5F5C590AF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52487"
,(lldb)     command script import "/tmp/63B8F9E6-C569-41EC-A9F3-329C2AB25510/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 07:59:24.526 ThaliTest[556:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 07:59:24.530 ThaliTest[556:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-23 07:59:24.536 ThaliTest[556:60b] Unlimited access to network resources
,2015-11-23 07:59:24.544 ThaliTest[556:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 07:59:35.195 ThaliTest[556:60b] Resetting plugins due to page load.
,2015-11-23 07:59:36.054 ThaliTest[556:60b] Finished load of: file:///var/mobile/Applications/9FB02BB2-C4DF-4341-96F1-64C5F5C590AF/ThaliTest.app/www/index.html
,2015-11-23 07:59:36.233 ThaliTest[556:60b] JXcore Cordova plugin initializing
,2015-11-23 07:59:36.234 ThaliTest[556:6707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
,Warning: iOS does not support ToggleBluetooth
,We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
,toggleBluetooth - 
Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
toggleWiFi
,my name is : Apple-Iphone5-1_PT8536
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c,:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[],}
,Start now : testSendData.js
stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 57505
,2015-11-23 08:04:40.268 ThaliTest[556:6707] jxcore: startBroadcasting
,2015-11-23 08:04:40.278 ThaliTest[556:6707] server: starting Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:04:40.280 ThaliTest[556:6707] multipeer session: start timer: 0x1d5f9410
,2015-11-23 08:04:40.282 ThaliTest[556:6707] THEMultipeerSession initialized peer Apple-Iphone5-1_PT8536
2015-11-23 08:04:40.284 ThaliTest[556:6707] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-23T07:04:40.287Z SendDataTCPServe,r.js: TCP/IP server  is bound to : undefined
,2015-11-23 08:04:41.335 ThaliTest[556:60b] multipeer session: reset timer
2015-11-23 08:04:41.335 ThaliTest[556:60b] multipeer session: stop timer
,2015-11-23 08:04:41.336 ThaliTest[556:60b] multipeer session: start timer: 0x1d5f9410
,2015-11-23 08:04:41.337 ThaliTest[556:60b] server session: connect
,2015-11-23 08:04:41.337 ThaliTest[556:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT2253
,2015-11-23 08:04:41.341 ThaliTest[556:60b] server: accepting invitation Apple-IpadAir2-1_PT2253
,2015-11-23 08:04:41.405 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2253.QxwsNA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23T07:04:41.409Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23T07:04:41.410Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23T07:04:41.410Z SendDataConnector.js: do connect now
,2015-11-23 08:04:41.411 ThaliTest[556:6707] jxcore: connect Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:04:41.412 ThaliTest[556:6707] client session: connect
,2015-11-23 08:04:41.412 ThaliTest[556:6707] client session: stateChange:0->1 Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:04:42.394 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-23 08:04:42.808 ThaliTest[556:60b] multipeer session: reset timer
,2015-11-23 08:04:42.810 ThaliTest[556:60b] multipeer session: stop timer
,2015-11-23 08:04:42.810 ThaliTest[556:60b] multipeer session: start timer: 0x1d5f9410
2015-11-23 08:04:42.811 ThaliTest[556:60b] server session: connect
,2015-11-23 08:04:42.812 ThaliTest[556:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT606
,2015-11-23 08:04:42.816 ThaliTest[556:60b] server: accepting invitation Apple-Iphone6-1_PT606
,2015-11-23 08:04:43.180 ThaliTest[556:60b] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8264./5qd6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:04:43.731 ThaliTest[556:60b] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:04:44.112 ThaliTest[556:7713] server session: connected
,2015-11-23 08:04:44.114 ThaliTest[556:7713] server session: stateChange:1->2 Apple-IpadAir2-1_PT2253
,2015-11-23 08:04:44.122 ThaliTest[556:60b] server relay: connected (to port: 57505)
,2015-11-23T07:04:44.134Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T07:04:44.192Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-23T07:04:44.215Z SendDataTCPServer.js: TCP/IP server has received 41528 bytes of data
,2015-11-23T07:04:44.229Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 08:04:44.280 ThaliTest[556:7f07] server session: not connected Apple-IpadAir2-1_PT2253
,2015-11-23 08:04:44.641 ThaliTest[556:7f07] client session: connected
,2015-11-23 08:04:44.643 ThaliTest[556:7f07] client session: stateChange:1->2 Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:04:44.654 ThaliTest[556:7713] client session: fireConnectCallback: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:04:44.655 ThaliTest[556:7713] jxcore: connect: success
,2015-11-23T07:04:44.657Z SendDataConnector.js: CLIENT connected to 57509, error: null
,2015-11-23T07:04:44.657Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 08:04:44.659 ThaliTest[556:60b] client: relay established
,2015-11-23 08:04:44.659 ThaliTest[556:60b] client: new accepted socket: 0x1d513b10
,2015-11-23T07:04:44.670Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T07:04:45.000Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-23 08:04:45.028 ThaliTest[556:751b] server session: connected
,2015-11-23 08:04:45.029 ThaliTest[556:751b] server session: stateChange:1->2 Apple-Iphone6-1_PT606
,2015-11-23T07:04:45.036Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-23 08:04:45.071 ThaliTest[556:60b] server relay: connected (to port: 57505)
2015-11-23T07:04:45.072Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-23T07:04:45.072Z SendDataConnector.js: got all data for this round
,2015-11-23T07:04:45.074Z SendDataConnector.js: CLIENT Stop now
2015-11-23T07:04:45.074Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 08:04:45.076 ThaliTest[556:6707] jxcore: disconnect
,2015-11-23 08:04:45.077 ThaliTest[556:6707] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:04:45.077 ThaliTest[556:6707] client session: disconnect
,2015-11-23 08:04:45.078 ThaliTest[556:6707] client session: stateChange:2->0 Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:04:45.080 ThaliTest[556:6707] jxcore: disconnect: success
,2015-11-23T07:04:45.083Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2253.QxwsNA==
---- round done--------
,device[2]: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23T07:04:45.085Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23T07:04:45.086Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23T07:04:45.086Z SendDataConnector.js: do connect now
,2015-11-23 08:04:45.087 ThaliTest[556:6707] jxcore: connect Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:04:45.088 ThaliTest[556:6707] client session: connect
,2015-11-23 08:04:45.089 ThaliTest[556:6707] client session: stateChange:0->1 Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23T07:04:45.098Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T07:04:45.178Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-11-23T07:04:45.192Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-11-23T07:04:45.507Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-11-23T07:04:45.524Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 08:04:45.549 ThaliTest[556:751b] server session: not connected Apple-Iphone6-1_PT606
,2015-11-23 08:04:48.108 ThaliTest[556:8303] client session: connected
,2015-11-23 08:04:48.108 ThaliTest[556:8303] client session: stateChange:1->2 Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:04:48.116 ThaliTest[556:7f07] client session: fireConnectCallback: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:04:48.117 ThaliTest[556:7f07] jxcore: connect: success
,2015-11-23T07:04:48.119Z SendDataConnector.js: CLIENT connected to 57514, error: null
2015-11-23T07:04:48.119Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 08:04:48.121 ThaliTest[556:60b] client: relay established
,2015-11-23 08:04:48.121 ThaliTest[556:60b] client: new accepted socket: 0x1d69c0f0
,2015-11-23T07:04:48.134Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T07:04:48.306Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-23T07:04:48.318Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-23T07:04:48.330Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-23T07:04:48.609Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-23T07:04:48.621Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-23T07:04:48.622Z SendDataConnector.js: got all data for this round
,2015-11-23T07:04:48.624Z SendDataConnector.js: CLIENT Stop now
2015-11-23T07:04:48.624Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 08:04:48.625 ThaliTest[556:6707] jxcore: disconnect
2015-11-23 08:04:48.626 ThaliTest[556:6707] client session: disconnectFromPeer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:04:48.627 ThaliTest[556:6707] client session: disconnect
,2015-11-23 08:04:48.627 ThaliTest[556:6707] client session: stateChange:2->0 Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:04:48.629 ThaliTest[556:6707] jxcore: disconnect: success
2015-11-23T07:04:48.630Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT606.CSvXcQ==
---- round done--------
,device[3]: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:04:48.633Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:04:48.633Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:04:48.633Z SendDataConnector.js: do connect now
,2015-11-23 08:04:48.634 ThaliTest[556:6707] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:04:48.634 ThaliTest[556:6707] client session: connect
,2015-11-23 08:04:48.635 ThaliTest[556:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:12.811 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:05:21.613 ThaliTest[556:751f] client session: not connected Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:21.615 ThaliTest[556:751f] client session: onLinkFailure: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:21.616 ThaliTest[556:751f] client session: disconnect
,2015-11-23 08:05:21.617 ThaliTest[556:751f] client session: stateChange:1->0 Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:21.618 ThaliTest[556:751f] client session: fireConnectCallback: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:21.618 ThaliTest[556:751f] jxcore: connect: fail: Peer disconnected
2015-11-23T07:05:21.619Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-23T07:05:21.620Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-23T07:05:21.620Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-23T07:05:26.630Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:05:26.631Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:31.642 ThaliTest[556:6707] jxcore: disconnect
2015-11-23 08:05:31.644 ThaliTest[556:6707] jxcore: disconnect: fail
,2015-11-23T07:05:31.645Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:05:31.646Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT8264./5qd6Q== with availability status,: true
2015-11-23T07:05:31.646Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:05:31.646Z SendDataConnector.js: do connect now
,2015-11-23 08:05:31.646 ThaliTest[556:6707] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:31.647 ThaliTest[556:6707] client session: connect
,2015-11-23 08:05:31.648 ThaliTest[556:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:42.812 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:05:42.822 ThaliTest[556:60b] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:05:42.824 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:05:42.825 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:05:50.540 ThaliTest[556:60b] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:05:50.542 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:05:54.693 ThaliTest[556:60b] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:05:54.695 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:05:55.167 ThaliTest[556:60b] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:05:55.301 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:05:58.362 ThaliTest[556:60b] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:05:58.364 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-11-23 08:05:59.885 ThaliTest[556:60b] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:06:04.640 ThaliTest[556:ae17] client session: not connected Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:06:04.641 ThaliTest[556:ae17] client session: onLinkFailure: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:04.642 ThaliTest[556:ae17] client session: disconnect
2015-11-23 08:06:04.643 ThaliTest[556:ae17] client session: stateChange:1->0 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:04.644 ThaliTest[556:ae17] client session: fireConnectCallback: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:04.645 ThaliTest[556:ae17] jxcore: connect: fail: Peer disconnected
2015-11-23T07:06:04.646Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-23T07:06:04.647Z SendDataConnector.js: CLIENT Can not Connect: Pee,r disconnected
2015-11-23T07:06:04.647Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-23T07:06:09.657Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:06:09.658Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:12.812 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:06:12.822 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:06:12.825 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:06:12.825 ThaliTest[556:60b] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:06:14.667 ThaliTest[556:6707] jxcore: disconnect
,2015-11-23 08:06:14.669 ThaliTest[556:6707] jxcore: disconnect: fail
2015-11-23T07:06:14.670Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:06:14.671Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT8264./5qd6Q== with availability status: true
2015-11-23T07:06:14.671Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:06:14.671Z SendDataConnector.js: do connect now
,2015-11-23 08:06:14.672 ThaliTest[556:6707] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:14.672 ThaliTest[556:6707] client session: connect
,2015-11-23 08:06:14.673 ThaliTest[556:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:20.509 ThaliTest[556:60b] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:06:20.510 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:06:28.241 ThaliTest[556:60b] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:06:28.242 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:06:29.763 ThaliTest[556:60b] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:06:29.779 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:06:42.812 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:06:47.659 ThaliTest[556:7f27] client session: not connected Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:06:47.661 ThaliTest[556:7f27] client session: onLinkFailure: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:47.662 ThaliTest[556:7f27] client session: disconnect
2015-11-23 08:06:47.663 ThaliTest[556:7f27] client session: stateChange:1->0 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:47.664 ThaliTest[556:7f27] client session: fireConnectCallback: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:47.664 ThaliTest[556:7f27] jxcore: connect: fail: Peer disconnected
,2015-11-23T07:06:47.665Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-23T07:06:47.666Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-23T07:06:47.666Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-23T07:06:52.676Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:06:52.676Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:57.686 ThaliTest[556:6707] jxcore: disconnect
2015-11-23 08:06:57.688 ThaliTest[556:6707] jxcore: disconnect: fail
,2015-11-23T07:06:57.689Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:06:57.690Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT8264./5qd6Q== with availability status,: true
2015-11-23T07:06:57.690Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:06:57.690Z SendDataConnector.js: do connect now
,2015-11-23 08:06:57.691 ThaliTest[556:6707] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:57.691 ThaliTest[556:6707] client session: connect
,2015-11-23 08:06:57.692 ThaliTest[556:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:07:12.812 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:07:12.822 ThaliTest[556:60b] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:07:12.823 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:07:12.824 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:07:20.657 ThaliTest[556:60b] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:07:20.659 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:07:28.132 ThaliTest[556:60b] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:07:28.134 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:07:29.518 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:07:29.662 ThaliTest[556:60b] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:07:30.681 ThaliTest[556:8a1b] client session: not connected Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:07:30.683 ThaliTest[556:8a1b] client session: onLinkFailure: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:07:30.684 ThaliTest[556:8a1b] client session: disconnect
,2015-11-23 08:07:30.685 ThaliTest[556:8a1b] client session: stateChange:1->0 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:07:30.686 ThaliTest[556:8a1b] client session: fireConnectCallback: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:07:30.686 ThaliTest[556:8a1b] jxcore: connect: fail: Peer disconnected
,2015-11-23T07:07:30.688Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-23T07:07:30.688Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-23T07:07:30.688Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-23T07:07:35.695Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:07:35.696Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:07:40.707 ThaliTest[556:6707] jxcore: disconnect
2015-11-23 08:07:40.708 ThaliTest[556:6707] jxcore: disconnect: fail
,2015-11-23T07:07:40.710Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:07:40.710Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT8264./5qd6Q== with availability status,: true
2015-11-23T07:07:40.710Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:07:40.711Z SendDataConnector.js: do connect now
,2015-11-23 08:07:40.711 ThaliTest[556:6707] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:07:40.712 ThaliTest[556:6707] client session: connect
,2015-11-23 08:07:40.712 ThaliTest[556:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:07:42.812 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:08:12.124 ThaliTest[556:60b] multipeer session: reset timer
,2015-11-23 08:08:12.125 ThaliTest[556:60b] multipeer session: stop timer
,2015-11-23 08:08:12.126 ThaliTest[556:60b] multipeer session: start timer: 0x1d5f9410
,2015-11-23 08:08:12.127 ThaliTest[556:60b] server session: connect
,2015-11-23 08:08:12.127 ThaliTest[556:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT1828
,2015-11-23 08:08:12.130 ThaliTest[556:60b] server: accepting invitation Apple-Iphone5s-1_PT1828
,2015-11-23 08:08:13.684 ThaliTest[556:b013] client session: not connected Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:08:13.686 ThaliTest[556:b013] client session: onLinkFailure: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:08:13.687 ThaliTest[556:b013] client session: disconnect
,2015-11-23 08:08:13.688 ThaliTest[556:b013] client session: stateChange:1->0 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:08:13.689 ThaliTest[556:b013] client session: fireConnectCallback: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:08:13.689 ThaliTest[556:b013] jxcore: connect: fail: Peer disconnected
2015-11-23T07:08:13.690Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-11-23T07:08:13.691Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-23T07:08:13.693Z SendDataConnector.js: CLIENT Stop now
,2015-11-23 08:08:13.694 ThaliTest[556:6707] jxcore: disconnect
,2015-11-23 08:08:13.695 ThaliTest[556:6707] jxcore: disconnect: fail
,2015-11-23T07:08:13.695Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd6Q==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT8536","time":213436,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT2253.QxwsNA==","time":3663,"result":"OK","connections":1},{"name":"Apple-Iphone6-1_PT606.CSvXcQ==","time":3538,"result":"OK","connections":1},{"name":"Apple-Iphone5s-1_PT8264./5qd6Q==","time":205058,"result":"Peer disconnected","connections":5}]}
,sendList : 100% : 3663 ms, 99% : 3663 ms, 95 : 3663 ms, 90% : 3663 ms.
Result count 2, range 3538 ms to  3663 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5s-1_PT8264./5qd6Q==, Tried : 5
,sendList never tried peers count : 0 [0 %]
2015-11-23T07:08:13.702Z SendDataConnector.js: CLIENT Stop now
,2015-11-23 08:08:14.740 ThaliTest[556:b013] server session: connected
,2015-11-23 08:08:14.741 ThaliTest[556:b013] server session: stateChange:1->2 Apple-Iphone5s-1_PT1828
,2015-11-23 08:08:14.750 ThaliTest[556:60b] server relay: connected (to port: 57505)
,2015-11-23T07:08:14.760Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T07:08:15.261Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-11-23T07:08:15.274Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-11-23T07:08:15.290Z SendDataTCPServer.js: TCP/IP server has received 85268 bytes of data
,2015-11-23T07:08:15.304Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 08:08:15.798 ThaliTest[556:962f] server session: not connected Apple-Iphone5s-1_PT1828
,2015-11-23 08:08:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:08:42.334 ThaliTest[556:60b] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:08:42.399 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:08:43.051 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:08:54.093 ThaliTest[556:60b] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:08:54.094 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:08:56.480 ThaliTest[556:60b] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:08:58.342 ThaliTest[556:60b] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:08:58.343 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:09:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:09:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:09:42.138 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:09:42.138 ThaliTest[556:60b] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-23 08:09:45.452 ThaliTest[556:60b] client: lost peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:09:45.454 ThaliTest[556:60b] client session: onPeerLost: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:09:45.455 ThaliTest[556:60b] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2253.QxwsNA==","peerName":"(null)","peerAvailable":false}]
2015-11-23 08:09:45.456 ThaliTest[556,:60b] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:09:52.007 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:09:57.239 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2253.QxwsNA==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:10:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:10:12.138 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:10:12.139 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:10:18.307 ThaliTest[556:60b] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:10:18.309 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:10:23.565 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:10:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:10:42.138 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:10:43.101 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:10:48.290 ThaliTest[556:60b] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:10:48.292 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:10:53.442 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:11:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:11:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:11:42.189 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:11:43.904 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:11:52.481 ThaliTest[556:60b] client: lost peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:11:52.482 ThaliTest[556:60b] client session: onPeerLost: Apple-IpadAir2-1_PT2253.QxwsNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2253.QxwsNA==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:11:53.434 ThaliTest[556:60b] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:11:53.435 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:11:55.060 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2253.QxwsNA==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:11:59.121 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:12:12.128 ThaliTest[556:60b] multipeer session: restart
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,Turning Wifi off
Warning: iOS does not support ToggleWiFi
,We could not turn wifi off! - Warning: iOS does not support ToggleWiFi
Turning Wifi back on
,Warning: iOS does not support ToggleWiFi
We could turn wifi back on! - Warning: iOS does not support ToggleWiFi
toggleWiFi finished
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,2015-11-23 08:12:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:12:42.138 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,2015-11-23 08:12:45.913 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:12:48.331 ThaliTest[556:60b] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:12:48.333 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:12:53.623 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:13:12.127 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:13:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:13:42.137 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:13:43.569 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:13:49.136 ThaliTest[556:60b] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:13:49.137 ThaliTest[556:60b] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:13:53.380 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:d,bff:fefa:5fea
,Turning Wifi off
Warning: iOS does not support ToggleWiFi
We could not turn wifi off! - Warning: iOS does not support ToggleWiFi
Turning Wifi back on
Warning: iOS does not support ToggleWiFi
,We could turn wifi back on! - Warning: iOS does not support ToggleWiFi
toggleWiFi finished
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:d,bff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,2015-11-23 08:14:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:14:12.137 ThaliTest[556:60b] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,2015-11-23 08:14:14.774 ThaliTest[556:60b] client: lost peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:14:14.776 ThaliTest[556:60b] client session: onPeerLost: Apple-IpadAir2-1_PT2253.QxwsNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2253.QxwsNA==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:14:15.012 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2253.QxwsNA==","peerName":"(null)","peerAvailable":true}]
2015-11-23 08:14:15.014 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,2015-11-23 08:14:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:15:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:15:12.681 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:15:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:15:45.045 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,2015-11-23 08:16:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:16:14.392 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:16:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:17:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:17:12.137 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:17:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:17:43.505 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:18:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:18:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:18:58.989 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:19:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:19:12.137 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:19:13.190 ThaliTest[556:60b] client: lost peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:19:13.191 ThaliTest[556:60b] client session: onPeerLost: Apple-IpadAir2-1_PT2253.QxwsNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2253.QxwsNA==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:19:13.718 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2253.QxwsNA==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:d,bff:fefa:5fea
,Turning Wifi off
Warning: iOS does not support ToggleWiFi
We could not turn wifi off! - Warning: iOS does not support ToggleWiFi
Turning Wifi back on
Warning: iOS does not support ToggleWiFi
,We could turn wifi back on! - Warning: iOS does not support ToggleWiFi
toggleWiFi finished
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,2015-11-23 08:19:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:19:42.137 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,2015-11-23 08:20:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:20:12.432 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:20:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:20:42.816 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:21:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:21:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:21:43.621 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:22:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:22:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:22:42.341 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:23:12.127 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:23:12.749 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:23:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:23:43.153 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:24:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:24:42.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:24:43.939 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:25:12.128 ThaliTest[556:60b] multipeer session: restart
,2015-11-23 08:25:12.268 ThaliTest[556:60b] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
2015-11-23 08:25:40.420 ThaliTest[556:6707] jxcore: stopBroadcasting
,2015-11-23 08:25:40.421 ThaliTest[556:6707] THEMultipeerSession stopping peer
2015-11-23 08:25:40.422 ThaliTest[556:6707] multipeer session: stop timer
,2015-11-23 08:25:40.423 ThaliTest[556:6707] server session: disconnect
2015-11-23 08:25:40.423 ThaliTest[556:6707] server session: stateChange:2->0 Apple-IpadAir2-1_PT2253
,2015-11-23 08:25:41.405 ThaliTest[556:6707] server session: disconnect
2015-11-23 08:25:41.405 ThaliTest[556:6707] server session: stateChange:2->0 Apple-Iphone5s-1_PT1828
,2015-11-23 08:25:41.408 ThaliTest[556:6707] server session: disconnect
2015-11-23 08:25:41.408 ThaliTest[556:6707] server session: stateChange:2->0 Apple-Iphone6-1_PT606
,2015-11-23 08:25:41.411 ThaliTest[556:6707] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-23T07:25:41.427Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T07:25:41.429Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T07:25:41.430Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T07:25:41.430Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT606.CSvXcQ==\",\"time\":3538,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT2253.QxwsNA==\",\"time\":3663,\"r,esult\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5s-1_PT8264./5qd6Q==\",\"time\":205058,\"result\":\"Peer disconnected\",\"connections\":5}],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone,5-1_PT8536.VjK3dQ==\",\"time\":2967,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT8536.VjK3dQ==\",\"time\":3054,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT606.CSvXcQ==\",\"time\":3306,\"result\":\"OK\",\"connect,ions\":1},{\"name\":\"Apple-IpadAir2-1_PT2253.QxwsNA==\",\"time\":3327,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT606.CSvXcQ==\",\"time\":3538,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT2253.QxwsNA==\",\"tim,e\":3663,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1828.9cQq2g==\",\"time\":4949,\"result\":\"OK\",\"connections\":1}]}}","devices":3,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop 
```
