#### Test 51517283acd5ddf_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51517283acd5ddf/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C4E734DB-4C8F-4DA9-88B3-FA0EB3223BFF/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/C4E734DB-4C8F-4DA9-88B3-FA0EB3223BFF/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51517283acd5ddf/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51517283acd5ddf/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/146B1AFB-5A84-4E45-8587-2C7181E98970/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53399"
,(lldb)     command script import "/tmp/C4E734DB-4C8F-4DA9-88B3-FA0EB3223BFF/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 16:37:31.437 ThaliTest[625:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-11-23 16:37:31.440 ThaliTest[625:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-23 16:37:31.447 ThaliTest[625:60b] Unlimited access to network resources
2015-11-23 16:37:31.454 ThaliTest[625:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more, information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 16:37:42.187 ThaliTest[625:60b] Resetting plugins due to page load.
,2015-11-23 16:37:43.063 ThaliTest[625:60b] Finished load of: file:///var/mobile/Applications/146B1AFB-5A84-4E45-8587-2C7181E98970/ThaliTest.app/www/index.html
,2015-11-23 16:37:43.245 ThaliTest[625:60b] JXcore Cordova plugin initializing
,2015-11-23 16:37:43.247 ThaliTest[625:6807] JXcore instance initializing
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
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
toggleWiFi
,my name is : Apple-Iphone5-1_PT4760
,attempting to connect to test coordinator
,check test folder
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
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found inter,faceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c,:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c,:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
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
,-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c,:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::42d:d0ff:fea8:dfa2
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"4000\",\"conReTryCount\":\"1\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"1"}, bt-address lenght : 0
,check server
serverPort is 59773
,2015-11-23 16:47:39.830 ThaliTest[625:6807] jxcore: startBroadcasting
,2015-11-23 16:47:39.845 ThaliTest[625:6807] server: starting Apple-Iphone5-1_PT4760.Nm2EfQ==
,2015-11-23 16:47:39.847 ThaliTest[625:6807] multipeer session: start timer: 0x1c750e40
,2015-11-23 16:47:39.857 ThaliTest[625:6807] THEMultipeerSession initialized peer Apple-Iphone5-1_PT4760
,2015-11-23 16:47:39.859 ThaliTest[625:6807] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,TCP/IP server  is bound to : undefined
,2015-11-23 16:47:40.186 ThaliTest[625:60b] client: found peer: Apple-Iphone5s-1_PT8579.vXjqrg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8579.vXjqrg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT8579.vXjqrg==
,2015-11-23 16:47:40.387 ThaliTest[625:60b] client: found peer: Apple-Iphone6-1_PT7067.RshDjw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7067.RshDjw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 16:47:40.684 ThaliTest[625:60b] client: found peer: 1448287198843.1386.IWfA6g==
,peerAvailabilityChanged [{"peerIdentifier":"1448287198843.1386.IWfA6g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 16:47:40.829 ThaliTest[625:60b] client: found peer: Apple-IpadAir2-1_PT4780.nb956Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4780.nb956Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 16:47:44.194 ThaliTest[625:6807] jxcore: disconnect
,2015-11-23 16:47:44.195 ThaliTest[625:6807] jxcore: disconnect: fail
,Connect (retry count 0) to peer Apple-Iphone5s-1_PT8579.vXjqrg== with availability status: true
,do connect now
,2015-11-23 16:47:44.198 ThaliTest[625:6807] jxcore: connect Apple-Iphone5s-1_PT8579.vXjqrg==
,2015-11-23 16:47:44.199 ThaliTest[625:6807] client session: connect
,2015-11-23 16:47:44.199 ThaliTest[625:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT8579.vXjqrg==
,2015-11-23 16:47:46.728 ThaliTest[625:130b] client session: connected
,2015-11-23 16:47:46.729 ThaliTest[625:130b] client session: stateChange:1->2 Apple-Iphone5s-1_PT8579.vXjqrg==
,2015-11-23 16:47:46.742 ThaliTest[625:7b07] client session: fireConnectCallback: Apple-Iphone5s-1_PT8579.vXjqrg==
,2015-11-23 16:47:46.743 ThaliTest[625:7b07] jxcore: connect: success
,CLIENT connected to 59776, error: null
CLIENT starting client 
,2015-11-23 16:47:46.746 ThaliTest[625:60b] client: relay established
2015-11-23 16:47:46.747 ThaliTest[625:60b] client: new accepted socket: 0x1c75fb90
,CLIENT now sending 100000 bytes of data
,CLIENT is data received : 10000
,CLIENT is data received : 10000
,CLIENT is data received : 20000
,CLIENT is data received : 30000
,CLIENT is data received : 30000
,CLIENT is data received : 40000
,CLIENT is data received : 50000
,Receiving data timeout now
,CLIENT closeClientSocket
,CLIENT Stop now
Stop data retrieving timer
2015-11-23 16:47:57.304 ThaliTest[625:60b] client: socket closed
2015-11-23 16:47:57.304 ThaliTest[625:60b] client relay: socket disconnected
2015-11-23 16:47:57.305 ThaliTest[625:60b] client relay: 0x1c75fb90, disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1e041ad0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-23 16:47:57.306 ThaliTest[625:60b] client session: socket closed: Appl,e-Iphone5s-1_PT8579.vXjqrg==
2015-11-23 16:47:57.307 ThaliTest[625:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT8579.vXjqrg==
,2015-11-23 16:47:57.307 ThaliTest[625:60b] client session: disconnect
2015-11-23 16:47:57.308 ThaliTest[625:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT8579.vXjqrg==
,CLIENT Stop now
,---- round done--------
,device[2]: Apple-Iphone6-1_PT7067.RshDjw==
----------------- closeClientSocket
,2015-11-23 16:47:57.311 ThaliTest[625:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT8579.vXjqrg==
,CLIENT is closed
,2015-11-23 16:48:01.320 ThaliTest[625:6807] jxcore: disconnect
,2015-11-23 16:48:01.321 ThaliTest[625:6807] jxcore: disconnect: fail
Connect (retry count 0) to peer Apple-Iphone6-1_PT7067.RshDjw== with availability status: true
,do connect now
,2015-11-23 16:48:01.324 ThaliTest[625:6807] jxcore: connect Apple-Iphone6-1_PT7067.RshDjw==
,2015-11-23 16:48:01.325 ThaliTest[625:6807] client session: connect
,2015-11-23 16:48:01.325 ThaliTest[625:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7067.RshDjw==
,2015-11-23 16:48:03.974 ThaliTest[625:8507] client session: connected
,2015-11-23 16:48:03.976 ThaliTest[625:8507] client session: stateChange:1->2 Apple-Iphone6-1_PT7067.RshDjw==
,2015-11-23 16:48:03.979 ThaliTest[625:130b] client session: fireConnectCallback: Apple-Iphone6-1_PT7067.RshDjw==
,2015-11-23 16:48:03.980 ThaliTest[625:130b] jxcore: connect: success
,CLIENT connected to 59780, error: null
CLIENT starting client 
,2015-11-23 16:48:03.982 ThaliTest[625:60b] client: relay established
,2015-11-23 16:48:03.983 ThaliTest[625:60b] client: new accepted socket: 0x1c75cd40
,CLIENT now sending 100000 bytes of data
,CLIENT is data received : 10000
,CLIENT is data received : 20000
,CLIENT is data received : 30000
,CLIENT is data received : 40000
,CLIENT is data received : 50000
,CLIENT is data received : 60000
,CLIENT is data received : 70000
,CLIENT is data received : 80000
,2015-11-23 16:48:09.859 ThaliTest[625:60b] multipeer session: restart
,Receiving data timeout now
,CLIENT closeClientSocket
CLIENT Stop now
Stop data retrieving timer
CLIENT Stop now
,---- round done--------
2015-11-23 16:48:15.106 ThaliTest[625:60b] client: socket closed
,2015-11-23 16:48:15.108 ThaliTest[625:60b] client relay: socket disconnected
2015-11-23 16:48:15.109 ThaliTest[625:60b] client relay: 0x1c75cd40 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=,0x1c604160 {NSLocalizedDescription=Socket closed by remote peer} 
device[3]: 1448287198843.1386.IWfA6g==
----------------- closeClientSocket
2015-11-23 16:48:15.110 ThaliTest[625:60b] client session: socket closed: Apple-Iphone6-1_PT7067.RshDjw==
,2015-11-23 16:48:15.110 ThaliTest[625:60b] client session: onLinkFailure: Apple-Iphone6-1_PT7067.RshDjw==
2015-11-23 16:48:15.111 ThaliTest[625:60b] client session: disconnect
2015-11-23 16:48:15.111 ThaliTest[625:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT7067.RshDjw==
,CLIENT is closed
,2015-11-23 16:48:15.113 ThaliTest[625:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7067.RshDjw==
,2015-11-23 16:48:19.119 ThaliTest[625:6807] jxcore: disconnect
,2015-11-23 16:48:19.120 ThaliTest[625:6807] jxcore: disconnect: fail
Connect (retry count 0) to peer 1448287198843.1386.IWfA6g== with availability status: true
,do connect now
,2015-11-23 16:48:19.122 ThaliTest[625:6807] jxcore: connect 1448287198843.1386.IWfA6g==
,2015-11-23 16:48:19.123 ThaliTest[625:6807] client session: connect
,2015-11-23 16:48:19.124 ThaliTest[625:6807] client session: stateChange:0->1 1448287198843.1386.IWfA6g==
,2015-11-23 16:48:20.729 ThaliTest[625:60b] multipeer session: reset timer
2015-11-23 16:48:20.731 ThaliTest[625:60b] multipeer session: stop timer
,2015-11-23 16:48:20.732 ThaliTest[625:60b] multipeer session: start timer: 0x1c750e40
,2015-11-23 16:48:20.732 ThaliTest[625:60b] server session: connect
2015-11-23 16:48:20.733 ThaliTest[625:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT4780
,2015-11-23 16:48:20.737 ThaliTest[625:60b] server: accepting invitation Apple-IpadAir2-1_PT4780
,2015-11-23 16:48:23.296 ThaliTest[625:7b07] server session: connected
,2015-11-23 16:48:23.298 ThaliTest[625:7b07] server session: stateChange:1->2 Apple-IpadAir2-1_PT4780
,2015-11-23 16:48:23.326 ThaliTest[625:60b] server relay: connected (to port: 59773)
TCP/IP server connected
,TCP/IP server has received 6428 bytes of data
,TCP/IP server has received 45990 bytes of data
,TCP/IP server has received 56940 bytes of data
,TCP/IP server has received 67748 bytes of data
,TCP/IP server has received 72270 bytes of data
,TCP/IP server has received 100002 bytes of data
,2015-11-23 16:48:33.900 ThaliTest[625:130f] server session: not connected Apple-IpadAir2-1_PT4780
,2015-11-23 16:48:50.734 ThaliTest[625:60b] multipeer session: restart
,2015-11-23 16:48:50.745 ThaliTest[625:60b] client: found peer: Apple-IpadAir2-1_PT4780.nb956Q==
,2015-11-23 16:48:50.747 ThaliTest[625:60b] client: found peer: Apple-Iphone6-1_PT7067.RshDjw==
,2015-11-23 16:48:50.748 ThaliTest[625:60b] client: found peer: 1448287198843.1386.IWfA6g==
,2015-11-23 16:48:50.748 ThaliTest[625:60b] client: found peer: Apple-Iphone5s-1_PT8579.vXjqrg==
,2015-11-23 16:48:52.120 ThaliTest[625:9a13] client session: not connected 1448287198843.1386.IWfA6g==
2015-11-23 16:48:52.122 ThaliTest[625:9a13] client session: onLinkFailure: 1448287198843.1386.IWfA6g==
,2015-11-23 16:48:52.123 ThaliTest[625:9a13] client session: disconnect
,2015-11-23 16:48:52.124 ThaliTest[625:9a13] client session: stateChange:1->0 1448287198843.1386.IWfA6g==
,2015-11-23 16:48:52.125 ThaliTest[625:9a13] client session: fireConnectCallback: 1448287198843.1386.IWfA6g==
,2015-11-23 16:48:52.125 ThaliTest[625:9a13] jxcore: connect: fail: Peer disconnected
,CLIENT connected to 0, error: Peer disconnected
CLIENT Can not Connect: Peer disconnected
CLIENT Stop now
,CLIENT Stop now
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT4760","time":72308,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8579.vXjqrg==","time":17114,"result":"DATA-TIMEOUT","connections":1},{"name":"Apple-Iphone6-1_PT7067.RshDjw==","time":17794,"result":"DATA-T,IMEOUT","connections":1},{"name":"1448287198843.1386.IWfA6g==","time":37017,"result":"Peer disconnected","connections":1}]}
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items,
sendList failed peers count : 3 [100 %]
- Peer ID : Apple-Iphone5s-1_PT8579.vXjqrg==, Tried : 1
- Peer ID : Apple-Iphone6-1_PT7067.RshDjw==, Tried : 1
- Peer ID : 1448287198843.1386.IWfA6g==, Tried : 1
sendList never tried peers count : 0 [0 %]
CLIENT Stop now
,2015-11-23 16:49:03.705 ThaliTest[625:60b] client: lost peer: Apple-Iphone5s-1_PT8579.vXjqrg==
2015-11-23 16:49:03.707 ThaliTest[625:60b] client session: onPeerLost: Apple-Iphone5s-1_PT8579.vXjqrg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8579.vXjqrg==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 16:49:03.778 ThaliTest[625:60b] client: found peer: Apple-Iphone5s-1_PT8579.vXjqrg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8579.vXjqrg==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
stop tests now !
stop current!
,testSendData stopped
,2015-11-23 16:49:11.407 ThaliTest[625:6807] jxcore: stopBroadcasting
2015-11-23 16:49:11.407 ThaliTest[625:6807] THEMultipeerSession stopping peer
,2015-11-23 16:49:11.408 ThaliTest[625:6807] multipeer session: stop timer
,2015-11-23 16:49:11.409 ThaliTest[625:6807] server session: disconnect
,2015-11-23 16:49:11.409 ThaliTest[625:6807] server session: stateChange:2->0 Apple-IpadAir2-1_PT4780
,2015-11-23 16:49:11.414 ThaliTest[625:6807] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,TCP/IP server is ended
,TCP/IP server  socket is disconnected
,TCP/IP server is close
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5s-1_PT8579.vXjqrg==\",\"time\":17114,\"result\":\"DATA-TIMEOUT\",\"connections\":1},{\"name\":\"Apple-,Iphone6-1_PT7067.RshDjw==\",\"time\":17794,\"result\":\"DATA-TIMEOUT\",\"connections\":1},{\"name\":\"1448287198843.1386.IWfA6g==\",\"time\":37017,\"result\":\"Peer disconnected\",\"connections\":1}],\"notTriedList\":[]}},\"combined\":{\"sendList\":[]}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
