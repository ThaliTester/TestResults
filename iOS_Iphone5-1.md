#### Test 5133502858c0449_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502858c0449/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/B70573A5-2263-4206-8BC9-5556F9868478/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/B70573A5-2263-4206-8BC9-5556F9868478/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502858c0449/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502858c0449/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/93864661-8788-4844-811B-E6AF2E5AFA7C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51890"
,(lldb)     command script import "/tmp/B70573A5-2263-4206-8BC9-5556F9868478/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-21 11:24:08.128 ThaliTest[432:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-21 11:24:08.131 ThaliTest[432:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-21 11:24:08.138 ThaliTest[432:60b] Unlimited access to network resources
,2015-11-21 11:24:08.146 ThaliTest[432:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-21 11:24:18.816 ThaliTest[432:60b] Resetting plugins due to page load.
,2015-11-21 11:24:19.684 ThaliTest[432:60b] Finished load of: file:///var/mobile/Applications/93864661-8788-4844-811B-E6AF2E5AFA7C/ThaliTest.app/www/index.html
,2015-11-21 11:24:19.863 ThaliTest[432:60b] JXcore Cordova plugin initializing
,(JX_LoopOnce) Did you initialize the JXEngine instance for this thread? (ret_val: 0)
,2015-11-21 11:24:19.866 ThaliTest[432:6807] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,my name is : Apple-Iphone5-1_PT8098
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
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
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
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
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
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
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
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
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
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
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
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
-iface: IPv6 is internal : true, has ip: fe80::1
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
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
,-iface: IPv4 is internal : false, has ip: 192.168.1.121
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::418:447c:f46b:da45
-iface: IPv4 is internal : false, has ip: 192.168.1.121
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::ac01:dbff:fefa:5fea
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[],}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 54845
,2015-11-21 11:32:40.381 ThaliTest[432:6807] jxcore: startBroadcasting
,2015-11-21 11:32:40.393 ThaliTest[432:6807] server: starting Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21 11:32:40.395 ThaliTest[432:6807] multipeer session: start timer: 0x1a750ac0
,2015-11-21 11:32:40.398 ThaliTest[432:6807] THEMultipeerSession initialized peer Apple-Iphone5-1_PT8098
2015-11-21 11:32:40.400 ThaliTest[432:6807] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-21T10:32:40.402Z SendDataTCPServe,r.js: TCP/IP server  is bound to : undefined
,2015-11-21 11:32:40.996 ThaliTest[432:60b] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21T10:32:41.000Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21T10:32:41.000Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21T10:32:41.001Z SendDataConnector.js: do connect now
,2015-11-21 11:32:41.001 ThaliTest[432:6807] jxcore: connect Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:32:41.003 ThaliTest[432:6807] client session: connect
,2015-11-21 11:32:41.003 ThaliTest[432:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:32:41.635 ThaliTest[432:60b] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1308.Xoqqgw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-21 11:32:41.962 ThaliTest[432:60b] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-21 11:32:42.242 ThaliTest[432:60b] multipeer session: reset timer
,2015-11-21 11:32:42.244 ThaliTest[432:60b] multipeer session: stop timer
,2015-11-21 11:32:42.245 ThaliTest[432:60b] multipeer session: start timer: 0x1a750ac0
,2015-11-21 11:32:42.246 ThaliTest[432:60b] server session: connect
,2015-11-21 11:32:42.246 ThaliTest[432:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT497
,2015-11-21 11:32:42.250 ThaliTest[432:60b] server: accepting invitation Apple-Iphone5s-1_PT497
,2015-11-21 11:32:43.711 ThaliTest[432:2233] client session: connected
2015-11-21 11:32:43.713 ThaliTest[432:2233] client session: stateChange:1->2 Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:32:43.717 ThaliTest[432:2233] client session: fireConnectCallback: Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:32:43.718 ThaliTest[432:2233] jxcore: connect: success
,2015-11-21T10:32:43.719Z SendDataConnector.js: CLIENT connected to 54849, error: null
2015-11-21T10:32:43.720Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 11:32:43.722 ThaliTest[432:60b] client: relay established
,2015-11-21 11:32:43.722 ThaliTest[432:60b] client: new accepted socket: 0x1a75b580
,2015-11-21T10:32:43.733Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-21T10:32:44.237Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-21T10:32:44.271Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-21T10:32:44.284Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-21T10:32:44.308Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-21T10:32:44.321Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-21T10:32:44.321Z SendDataConnector.js: got all data for this round
,2015-11-21T10:32:44.324Z SendDataConnector.js: CLIENT Stop now
2015-11-21T10:32:44.324Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 11:32:44.325 ThaliTest[432:6807] jxcore: disconnect
,2015-11-21 11:32:44.326 ThaliTest[432:6807] client session: disconnectFromPeer: Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:32:44.327 ThaliTest[432:6807] client session: disconnect
,2015-11-21 11:32:44.327 ThaliTest[432:6807] client session: stateChange:2->0 Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:32:44.329 ThaliTest[432:6807] jxcore: disconnect: success
2015-11-21T10:32:44.330Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.kxsT+g==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21T10:32:44.332Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21T10:32:44.332Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21T10:32:44.333Z SendDataConnector.js: do connect now
,2015-11-21 11:32:44.333 ThaliTest[432:6807] jxcore: connect Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:32:44.334 ThaliTest[432:6807] client session: connect
2015-11-21 11:32:44.335 ThaliTest[432:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:32:44.755 ThaliTest[432:7f03] server session: connected
2015-11-21 11:32:44.757 ThaliTest[432:7f03] server session: stateChange:1->2 Apple-Iphone5s-1_PT497
,2015-11-21 11:32:44.761 ThaliTest[432:60b] server relay: connected (to port: 54845)
,2015-11-21T10:32:44.767Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T10:32:44.881Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-11-21T10:32:44.898Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-11-21T10:32:44.911Z SendDataTCPServer.js: TCP/IP server has received 74034 bytes of data
,2015-11-21T10:32:44.924Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-21 11:32:44.941 ThaliTest[432:8003] server session: not connected Apple-Iphone5s-1_PT497
,2015-11-21 11:32:47.046 ThaliTest[432:60b] multipeer session: reset timer
,2015-11-21 11:32:47.047 ThaliTest[432:60b] multipeer session: stop timer
,2015-11-21 11:32:47.048 ThaliTest[432:60b] multipeer session: start timer: 0x1a750ac0
,2015-11-21 11:32:47.049 ThaliTest[432:60b] server session: connect
,2015-11-21 11:32:47.049 ThaliTest[432:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT1308
,2015-11-21 11:32:47.053 ThaliTest[432:60b] server: accepting invitation Apple-IpadAir2-1_PT1308
,2015-11-21 11:32:47.410 ThaliTest[432:7b0b] client session: connected
,2015-11-21 11:32:47.411 ThaliTest[432:7b0b] client session: stateChange:1->2 Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:32:47.436 ThaliTest[432:7f03] client session: fireConnectCallback: Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:32:47.437 ThaliTest[432:7f03] jxcore: connect: success
,2015-11-21T10:32:47.438Z SendDataConnector.js: CLIENT connected to 54853, error: null
2015-11-21T10:32:47.438Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 11:32:47.439 ThaliTest[432:60b] client: relay established
,2015-11-21 11:32:47.440 ThaliTest[432:60b] client: new accepted socket: 0x1a765e50
,2015-11-21T10:32:47.452Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-21T10:32:47.925Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-21T10:32:47.961Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-21T10:32:48.415Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-21T10:32:48.484Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-21T10:32:49.050Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-21T10:32:49.063Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-21T10:32:49.063Z SendDataConnector.js: got all data for this round
,2015-11-21T10:32:49.066Z SendDataConnector.js: CLIENT Stop now
2015-11-21T10:32:49.066Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 11:32:49.067 ThaliTest[432:6807] jxcore: disconnect
2015-11-21 11:32:49.068 ThaliTest[432:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21 11:32:49.069 ThaliTest[432:6807] client session: disconnect
2015-11-21 11:32:49.069 ThaliTest[432:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:32:49.073 ThaliTest[432:6807] jxcore: disconnect: success
,2015-11-21T10:32:49.075Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1308.Xoqqgw==
---- round done--------
,device[3]: Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21T10:32:49.079Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21T10:32:49.079Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21T10:32:49.079Z SendDataConnector.js: do connect now
,2015-11-21 11:32:49.081 ThaliTest[432:6807] jxcore: connect Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:32:49.085 ThaliTest[432:6807] client session: connect
,2015-11-21 11:32:49.089 ThaliTest[432:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:32:51.164 ThaliTest[432:7b0b] server session: connected
,2015-11-21 11:32:51.166 ThaliTest[432:7b0b] server session: stateChange:1->2 Apple-IpadAir2-1_PT1308
,2015-11-21 11:32:51.173 ThaliTest[432:60b] server relay: connected (to port: 54845)
,2015-11-21T10:32:51.179Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T10:32:51.236Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-11-21T10:32:51.248Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-11-21T10:32:51.283Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-11-21T10:32:51.298Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-11-21T10:32:51.310Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-11-21T10:32:51.569Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-11-21T10:32:51.581Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-21 11:32:52.148 ThaliTest[432:7b0b] server session: not connected Apple-IpadAir2-1_PT1308
,2015-11-21 11:32:52.162 ThaliTest[432:7b0b] client session: connected
,2015-11-21 11:32:52.163 ThaliTest[432:7b0b] client session: stateChange:1->2 Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:32:52.172 ThaliTest[432:7f03] client session: fireConnectCallback: Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21 11:32:52.173 ThaliTest[432:7f03] jxcore: connect: success
,2015-11-21T10:32:52.175Z SendDataConnector.js: CLIENT connected to 54858, error: null
2015-11-21T10:32:52.175Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 11:32:52.176 ThaliTest[432:60b] client: relay established
,2015-11-21 11:32:52.178 ThaliTest[432:60b] client: new accepted socket: 0x1a76dea0
,2015-11-21T10:32:52.187Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-21T10:32:52.619Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-21T10:32:52.696Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-21T10:32:52.709Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-21T10:32:52.733Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-21T10:32:52.746Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-21T10:32:52.793Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-21T10:32:53.138Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-21T10:32:53.139Z SendDataConnector.js: got all data for this round
,2015-11-21T10:32:53.140Z SendDataConnector.js: CLIENT Stop now
2015-11-21T10:32:53.141Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 11:32:53.142 ThaliTest[432:6807] jxcore: disconnect
,2015-11-21 11:32:53.143 ThaliTest[432:6807] client session: disconnectFromPeer: Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:32:53.144 ThaliTest[432:6807] client session: disconnect
,2015-11-21 11:32:53.144 ThaliTest[432:6807] client session: stateChange:2->0 Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:32:53.147 ThaliTest[432:6807] jxcore: disconnect: success
,2015-11-21T10:32:53.149Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3409.7QVn3g==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT8098","time":12779,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT497.kxsT+g==","time":3323,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT1308.Xoqqgw==","time":4732,"result":"OK","connections":,1},{"name":"Apple-Iphone6-1_PT3409.7QVn3g==","time":4060,"result":"OK","connections":1}]}
,sendList : 100% : 4732 ms, 99% : 4732 ms, 95 : 4732 ms, 90% : 4732 ms.
Result count 3, range 3323 ms to  4732 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-21T10:32:53.157Z SendDataConnector.js: CLIENT Stop now
,2015-11-21 11:33:17.050 ThaliTest[432:60b] multipeer session: restart
,2015-11-21 11:33:17.060 ThaliTest[432:60b] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:33:17.189 ThaliTest[432:60b] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:33:17.192 ThaliTest[432:60b] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:33:28.297 ThaliTest[432:60b] client: lost peer: Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21 11:33:28.299 ThaliTest[432:60b] client session: onPeerLost: Apple-Iphone6-1_PT3409.7QVn3g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":false}]
,2015-11-21 11:33:28.904 ThaliTest[432:60b] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":true}]
,2015-11-21 11:33:46.021 ThaliTest[432:60b] client: lost peer: Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21 11:33:46.022 ThaliTest[432:60b] client session: onPeerLost: Apple-Iphone5s-1_PT497.kxsT+g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":false}]
,2015-11-21 11:33:47.049 ThaliTest[432:60b] multipeer session: restart
,2015-11-21 11:33:47.131 ThaliTest[432:60b] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:33:47.134 ThaliTest[432:60b] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:33:47.211 ThaliTest[432:60b] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":true}]
,2015-11-21 11:33:52.411 ThaliTest[432:60b] client: lost peer: Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21 11:33:52.412 ThaliTest[432:60b] client session: onPeerLost: Apple-Iphone5s-1_PT497.kxsT+g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":false}]
,2015-11-21 11:33:57.125 ThaliTest[432:60b] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":true}]
,2015-11-21 11:34:02.367 ThaliTest[432:60b] client: lost peer: Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:34:02.368 ThaliTest[432:60b] client session: onPeerLost: Apple-Iphone6-1_PT3409.7QVn3g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":false}]
,2015-11-21 11:34:07.035 ThaliTest[432:60b] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":true}]
,2015-11-21 11:34:16.522 ThaliTest[432:60b] client: lost peer: Apple-Iphone5s-1_PT497.kxsT+g==
2015-11-21 11:34:16.523 ThaliTest[432:60b] client session: onPeerLost: Apple-Iphone5s-1_PT497.kxsT+g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":false}]
,2015-11-21 11:34:17.050 ThaliTest[432:60b] multipeer session: restart
,2015-11-21 11:34:17.534 ThaliTest[432:60b] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21 11:34:17.536 ThaliTest[432:60b] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:34:17.542 ThaliTest[432:60b] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":true}]
,2015-11-21 11:34:22.287 ThaliTest[432:60b] client: lost peer: Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:34:22.289 ThaliTest[432:60b] client session: onPeerLost: Apple-Iphone5s-1_PT497.kxsT+g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":false}]
,2015-11-21 11:34:27.125 ThaliTest[432:60b] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.kxsT+g==","peerName":"(null)","peerAvailable":true}]
,2015-11-21 11:34:32.283 ThaliTest[432:60b] client: lost peer: Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21 11:34:32.284 ThaliTest[432:60b] client session: onPeerLost: Apple-Iphone6-1_PT3409.7QVn3g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":false}]
,2015-11-21 11:34:38.485 ThaliTest[432:60b] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":true}]
,2015-11-21 11:34:47.050 ThaliTest[432:60b] multipeer session: restart
,2015-11-21 11:34:47.061 ThaliTest[432:60b] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:34:47.063 ThaliTest[432:60b] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:34:48.598 ThaliTest[432:60b] client: found peer: Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:35:01.228 ThaliTest[432:60b] multipeer session: reset timer
2015-11-21 11:35:01.230 ThaliTest[432:60b] multipeer session: stop timer
,2015-11-21 11:35:01.230 ThaliTest[432:60b] multipeer session: start timer: 0x1a750ac0
,2015-11-21 11:35:01.231 ThaliTest[432:60b] server session: connect
,2015-11-21 11:35:01.231 ThaliTest[432:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT3409
,2015-11-21 11:35:01.235 ThaliTest[432:60b] server: accepting invitation Apple-Iphone6-1_PT3409
,2015-11-21 11:35:02.651 ThaliTest[432:60b] client: lost peer: Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:35:02.652 ThaliTest[432:60b] client session: onPeerLost: Apple-Iphone6-1_PT3409.7QVn3g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":false}]
,2015-11-21 11:35:03.679 ThaliTest[432:60b] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":true}]
,2015-11-21 11:35:03.688 ThaliTest[432:a827] server session: connected
,2015-11-21 11:35:03.689 ThaliTest[432:a827] server session: stateChange:1->2 Apple-Iphone6-1_PT3409
,2015-11-21 11:35:03.699 ThaliTest[432:60b] server relay: connected (to port: 54845)
,2015-11-21T10:35:03.703Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T10:35:03.815Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-11-21T10:35:03.829Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-11-21T10:35:03.843Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-11-21T10:35:03.856Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-21 11:35:03.873 ThaliTest[432:a827] server session: not connected Apple-Iphone6-1_PT3409
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
stop tests now !
stop current!
testSendData stopped
,2015-11-21 11:35:10.464 ThaliTest[432:6807] jxcore: stopBroadcasting
,2015-11-21 11:35:10.464 ThaliTest[432:6807] THEMultipeerSession stopping peer
,2015-11-21 11:35:10.465 ThaliTest[432:6807] multipeer session: stop timer
,2015-11-21 11:35:10.466 ThaliTest[432:6807] server session: disconnect
,2015-11-21 11:35:10.467 ThaliTest[432:6807] server session: stateChange:2->0 Apple-IpadAir2-1_PT1308
,2015-11-21 11:35:10.472 ThaliTest[432:6807] server session: disconnect
2015-11-21 11:35:10.474 ThaliTest[432:6807] server session: stateChange:2->0 Apple-Iphone6-1_PT3409
,2015-11-21 11:35:10.479 ThaliTest[432:6807] server session: disconnect
,2015-11-21 11:35:10.481 ThaliTest[432:6807] server session: stateChange:2->0 Apple-Iphone5s-1_PT497
,2015-11-21 11:35:17.211 ThaliTest[432:6807] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-21T10:35:17.228Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T10:35:17.229Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T10:35:17.230Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T10:35:17.230Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT497.kxsT+g==\",\"time\":3323,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT3409.7QVn3g==\",\"time\":4060,\"r,esult\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT1308.Xoqqgw==\",\"time\":4732,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT8098.G9Yv6,w==\",\"time\":2806,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT8098.G9Yv6w==\",\"time\":2973,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT497.kxsT+g==\",\"time\":2983,\"result\":\"OK\",\"connections\":1},{\"na,me\":\"Apple-Iphone5s-1_PT497.kxsT+g==\",\"time\":3323,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT3409.7QVn3g==\",\"time\":3435,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT3409.7QVn3g==\",\"time\":4060,\"resul,t\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT1308.Xoqqgw==\",\"time\":4220,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT3409.7QVn3g==\",\"time\":4296,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT,1308.Xoqqgw==\",\"time\":4732,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT497.kxsT+g==\",\"time\":4864,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT8098.G9Yv6w==\",\"time\":5119,\"result\":\"OK\",\"connections\,":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
