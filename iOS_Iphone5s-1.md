#### Test 51335028e04ad51_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028e04ad51/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/342358E7-7CCC-4135-8D6E-9E50251319A0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/342358E7-7CCC-4135-8D6E-9E50251319A0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028e04ad51/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028e04ad51/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8F5F1A43-08BA-416A-8335-439271F9DB5D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52491"
,(lldb)     command script import "/tmp/342358E7-7CCC-4135-8D6E-9E50251319A0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 07:58:40.742 ThaliTest[1260:1095254] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B3BE7FB5-A8F3-44E8-9ACF-BFB0754356ED/Library/Cookies/Cookies.binarycookies
,2015-11-23 07:58:41.154 ThaliTest[1260:1095254] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 07:58:41.156 ThaliTest[1260:1095254] Multi-tasking -> Device: YES, App: YES
,2015-11-23 07:58:41.165 ThaliTest[1260:1095254] Unlimited access to network resources
,2015-11-23 07:58:41.173 ThaliTest[1260:1095254] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 07:58:44.756 ThaliTest[1260:1095254] Resetting plugins due to page load.
,2015-11-23 07:58:45.198 ThaliTest[1260:1095254] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/8F5F1A43-08BA-416A-8335-439271F9DB5D/ThaliTest.app/www/index.html
,2015-11-23 07:58:45.353 ThaliTest[1260:1095254] JXcore Cordova plugin initializing
2015-11-23 07:58:45.356 ThaliTest[1260:1095377] JXcore instance initializing
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
toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
toggleWiFi
,my name is : Apple-Iphone5s-1_PT1828
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[],}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 57033
,2015-11-23 08:04:41.626 ThaliTest[1260:1095377] jxcore: startBroadcasting
,2015-11-23 08:04:41.639 ThaliTest[1260:1095377] server: starting Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:04:41.649 ThaliTest[1260:1095377] multipeer session: start timer: 0x196249b0
,2015-11-23 08:04:41.663 ThaliTest[1260:1095377] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT1828
,2015-11-23 08:04:41.666 ThaliTest[1260:1095377] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-23T07:04:41.673Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-23 08:04:42.188 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8264./5qd6Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:04:42.199Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:04:42.199 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11,-23T07:04:42.201Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:04:42.201Z SendDataConnector.js: do connect now
2015-11-23 08:04:42.202 ThaliTest[1260:1095377] jxcore: connect Apple-Iphone5s-1_PT8264./5qd,6Q==
2015-11-23 08:04:42.203 ThaliTest[1260:1095377] client session: connect
2015-11-23 08:04:42.204 ThaliTest[1260:1095377] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:04:42.368 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8536.VjK3dQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-11-23 08:04:43.040 ThaliTest[1260:1095254] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2253.QxwsNA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-23 08:04:48.153 ThaliTest[1260:1095254] multipeer session: reset timer
2015-11-23 08:04:48.154 ThaliTest[1260:1095254] multipeer session: stop timer
2015-11-23 08:04:48.155 ThaliTest[1260:1095254] multipeer session: start timer: 0x196249b0
2015-,11-23 08:04:48.156 ThaliTest[1260:1095254] server session: connect
2015-11-23 08:04:48.156 ThaliTest[1260:1095254] server session: stateChange:0->1 Apple-IpadAir2-1_PT2253
,2015-11-23 08:04:48.169 ThaliTest[1260:1095254] server: accepting invitation Apple-IpadAir2-1_PT2253
,2015-11-23 08:04:50.932 ThaliTest[1260:1095910] server session: connected
2015-11-23 08:04:50.932 ThaliTest[1260:1095910] server session: stateChange:1->2 Apple-IpadAir2-1_PT2253
,2015-11-23 08:04:51.285 ThaliTest[1260:1095254] server relay: connected (to port: 57033)
2015-11-23T07:04:51.297Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T07:04:51.310Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-11-23T07:04:51.349Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-11-23T07:04:51.363Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-11-23T07:04:51.413Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-11-23T07:04:51.430Z SendDataTCPServer.js: TCP/IP server has received 62516 bytes of data
,2015-11-23T07:04:51.446Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-11-23T07:04:51.485Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-11-23T07:04:51.502Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-11-23T07:04:51.519Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 08:04:51.806 ThaliTest[1260:1095921] server session: not connected Apple-IpadAir2-1_PT2253
,2015-11-23 08:05:15.210 ThaliTest[1260:1096130] client session: not connected Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:15.210 ThaliTest[1260:1096130] client session: onLinkFailure: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:15.211 ThaliTe,st[1260:1096130] client session: disconnect
2015-11-23 08:05:15.211 ThaliTest[1260:1096130] client session: stateChange:1->0 Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:15.212 ThaliTest[1260:1096130] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT8264./5qd6Q==
2015-11-23 08:05:15.212 ThaliTest[1260:1096130] jxcore: connect: fail: Peer disconnected
,2015-11-23T07:05:15.215Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-23T07:05:15.215Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-23T07:05:15.217Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-23 08:05:18.156 ThaliTest[1260:1095254] multipeer session: restart
,2015-11-23 08:05:18.177 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:18.178 ThaliTest[1260:1095254] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:05:18.184 ThaliTest[1260:1095254] clie,nt: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:05:18.185 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23T07:05:20.222Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:05:20.223Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:25.232 ThaliTest[1260:1095377] jxcore: disconnect
2015-11-23 08:05:25.233 ThaliTest[1260:1095377] jxcore: disconnect: fail
2015-11-23T07:05:25.234Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd,6Q==
2015-11-23T07:05:25.235Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT8264./5qd6Q== with availability status: true
,2015-11-23T07:05:25.235Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:05:25.235Z SendDataConnector.js: do connect now
,2015-11-23 08:05:25.236 ThaliTest[1260:1095377] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:05:25.237 ThaliTest[1260:1095377] client session: connect
2015-11-23 08:05:25.238 ThaliTest[1260:1095377] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:05:48.156 ThaliTest[1260:1095254] multipeer session: restart
,2015-11-23 08:05:48.260 ThaliTest[1260:1095254] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:05:48.264 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:48.265 ThaliTest[1260:1095254] clie,nt: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:05:48.267 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:05:54.068 ThaliTest[1260:1095254] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:05:54.069 ThaliTest[1260:1095254] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:05:58.246 ThaliTest[1260:1096288] client session: not connected Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:58.247 ThaliTest[1260:1096288] client session: onLinkFailure: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:58.247 ThaliTe,st[1260:1096288] client session: disconnect
2015-11-23 08:05:58.248 ThaliTest[1260:1096288] client session: stateChange:1->0 Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:05:58.249 ThaliTest[1260:1096288] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT8264./5qd6Q==
2015-11-23 08:05:58.249 ThaliTest[1260:1096288] jxcore: connect: fail: Peer disconnected
2015-11-23T07:05:58.251Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-11-23T07:05:58.251Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-23T07:05:58.252Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-23 08:05:58.499 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23T07:06:03.269Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:06:03.270Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:06:08.287 ThaliTest[1260:1095377] jxcore: disconnect
2015-11-23 08:06:08.288 ThaliTest[1260:1095377] jxcore: disconnect: fail
2015-11-23T07:06:08.289Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd,6Q==
2015-11-23T07:06:08.289Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT8264./5qd6Q== with availability status: true
2015-11-23T07:06:08.289Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:06:08.290Z SendDataConnector.js: do connect now
2015-11-23 08:06:08.290 ThaliTest[1260:1095377] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:06:08.291 ThaliTest[1260:1095377] client session: connect
,2015-11-23 08:06:08.292 ThaliTest[1260:1095377] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:06:15.664 ThaliTest[1260:1095254] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:06:15.665 ThaliTest[1260:1095254] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:06:15.819 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:06:18.155 ThaliTest[1260:1095254] multipeer session: restart
,2015-11-23 08:06:18.183 ThaliTest[1260:1095254] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:06:18.184 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:06:18.188 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:06:18.189 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:06:24.245 ThaliTest[1260:1095254] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:06:24.246 ThaliTest[1260:1095254] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":,10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"a,rraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:06:28.784 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:06:41.300 ThaliTest[1260:1096288] client session: not connected Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:41.300 ThaliTest[1260:1096288] client session: onLinkFailure: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:06:41.302 ThaliTest[1260:1096288] client session: disconnect
2015-11-23 08:06:41.302 ThaliTest[1260:1096288] client session: sta,teChange:1->0 Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:06:41.303 ThaliTest[1260:1096288] client session: fireConnectCallback: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:06:41.303 ThaliTest[1260:1096288] jxcore: connect: fail: Peer disconnected,
2015-11-23T07:06:41.305Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-11-23T07:06:41.305Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-23T07:06:41.306Z SendDataConnector.js: tryAgain afer: 5000 ms.
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23T07:06:46.323Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:06:46.324Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:06:47.637 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:06:48.155 ThaliTest[1260:1095254] multipeer session: restart
,2015-11-23 08:06:48.176 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:06:48.178 ThaliTest[1260:1095254] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:06:48.181 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:06:48.184 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:51.146 ThaliTest[1260:1095254] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:06:51.147 ThaliTest[1260:1095254] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:06:51.334 ThaliTest[1260:1095377] jxcore: disconnect
2015-11-23 08:06:51.335 ThaliTest[1260:1095377] jxcore: disconnect: fail
2015-11-23T07:06:51.336Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd,6Q==
2015-11-23T07:06:51.336Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT8264./5qd6Q== with availability status: true
,2015-11-23T07:06:51.337Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23T07:06:51.338Z SendDataConnector.js: do connect now
,2015-11-23 08:06:51.339 ThaliTest[1260:1095377] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:06:51.340 ThaliTest[1260:1095377] client session: connect
2015-11-23 08:06:51.341 ThaliTest[1260:1095377] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:06:51.465 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:06:52.894 ThaliTest[1260:1095254] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:06:52.895 ThaliTest[1260:1095254] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:07:02.336 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:07:17.517 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:07:18.155 ThaliTest[1260:1095254] multipeer session: restart
,2015-11-23 08:07:18.182 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:07:18.183 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:07:18.184 ThaliTest[1260:1095254] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:07:18.190 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:07:23.282 ThaliTest[1260:1095254] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:07:23.283 ThaliTest[1260:1095254] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-23 08:07:24.345 ThaliTest[1260:1096288] client session: not connected Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:07:24.346 ThaliTest[1260:1096288] client session: onLinkFailure: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:07:24.347 ThaliTe,st[1260:1096288] client session: disconnect
2015-11-23 08:07:24.347 ThaliTest[1260:1096288] client session: stateChange:1->0 Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:07:24.348 ThaliTest[1260:1096288] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT8264./5qd6Q==
2015-11-23 08:07:24.348 ThaliTest[1260:1096288] jxcore: connect: fail: Peer disconnected
,2015-11-23T07:07:24.351Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-23T07:07:24.351Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-23T07:07:24.352Z SendDataConnector.js: tryAgain afer: 5000 ms.
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:07:29.049 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,2015-11-23T07:07:29.371Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23T07:07:29.371Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8264./5qd6Q==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:07:34.384 ThaliTest[1260:1095377] jxcore: disconnect
2015-11-23 08:07:34.385 ThaliTest[1260:1095377] jxcore: disconnect: fail
2015-11-23T07:07:34.385Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd,6Q==
2015-11-23T07:07:34.386Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT8264./5qd6Q== with availability status: true
2015-11-23T07:07:34.386Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8264./5qd6Q==,
,2015-11-23T07:07:34.386Z SendDataConnector.js: do connect now
2015-11-23 08:07:34.387 ThaliTest[1260:1095377] jxcore: connect Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:07:34.388 ThaliTest[1260:1095377] client session: connect
,2015-11-23 08:07:34.389 ThaliTest[1260:1095377] client session: stateChange:0->1 Apple-Iphone5s-1_PT8264./5qd6Q==
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":,10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"a,rraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:07:48.154 ThaliTest[1260:1095254] multipeer session: restart
,2015-11-23 08:07:48.186 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:07:48.187 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:07:48.188 ThaliTest[1260:1095254] client,: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:07:48.590 ThaliTest[1260:1095254] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:07:52.967 ThaliTest[1260:1095254] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:07:52.967 ThaliTest[1260:1095254] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:08:00.629 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
2015-11-23 08:08:07.398 ThaliTest[1260:1096467] client session: not connected Apple-Iphone5s-1_PT8264./5qd6Q==
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH,","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":,false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
2015-11-23 08:08:07.399 ThaliTest[1260:1096467] client session: onLinkFailu,re: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:08:07.400 ThaliTest[1260:1096467] client session: disconnect
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
2015-11-23 08:08:0,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
7.400 ThaliTest[1260:1096467] client session: stateChange:1->0 Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:08:07.402 ThaliTest[1260:1096467] client session: f,ireConnectCallback: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:08:07.403 ThaliTest[1260:1096467] jxcore: connect: fail: Peer disconnected
,2015-11-23T07:08:07.409Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-23T07:08:07.409Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-23T07:08:07.412Z SendDataConnector.js: CLIENT Stop now
2015-11-23 08:08:07.413 ThaliTest[1260:1095377] jxcore: disconnect
,2015-11-23 08:08:07.414 ThaliTest[1260:1095377] jxcore: disconnect: fail
,2015-11-23T07:08:07.415Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8264./5qd6Q==
---- round done--------
device[2]: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23T07:08:07.418Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23T07:08:07.419Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23T07:08:07.419Z SendDataConnector.js: do connect now
2015-11-23 08:08:07.420 ThaliTest[1260:1095377] jxcore: connect Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:08:07.421 ThaliTest[1260:1095377] client session: connect
,2015-11-23 08:08:07.422 ThaliTest[1260:1095377] client session: stateChange:0->1 Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:08:10.532 ThaliTest[1260:1096519] client session: connected
2015-11-23 08:08:10.534 ThaliTest[1260:1096519] client session: stateChange:1->2 Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:08:10.538 ThaliTest[1260:1096540] client session: fireConnectCallback: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:08:10.540 ThaliTest[1260:1096540] jxcore: connect: success
2015-11-23T07:08:10.541Z SendDataConnector.js: CLIENT connected to 57081, error: null
,2015-11-23T07:08:10.541Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 08:08:10.546 ThaliTest[1260:1095254] client: relay established
2015-11-23 08:08:10.546 ThaliTest[1260:1095254] client: new accepted socket: 0x195df0d0
,2015-11-23T07:08:10.557Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T07:08:10.663Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-23T07:08:10.689Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-23T07:08:10.701Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-23T07:08:10.701Z SendDataConnector.js: got all data for this round
,2015-11-23T07:08:10.702Z SendDataConnector.js: CLIENT Stop now
2015-11-23T07:08:10.702Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 08:08:10.703 ThaliTest[1260:1095377] jxcore: disconnect
2015-11-23 08:08:10.703 ThaliTest[1260:1095377] client session: disconnectFromPeer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:08:10.703 ThaliTest[1260:1095377] client session: disconnect
2015-11-23 08:08:10.704 ThaliTest[1260:1095377] client session: stateChange:2->0 Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:08:10.705 ThaliTest[1260:1095377] jxcore: disconnect: success
2015-11-23T07:08:10.706Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT606.CSvXcQ==
---- round done--------
,device[3]: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23T07:08:10.708Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23T07:08:10.708Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23T07:08:10.709Z SendDataConnector.js: do connect now
2015-11-23 08:08:10.709 ThaliTest[1260:1095377] jxcore: connect Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:08:10.709 ThaliTest[1260:1095377] client session: connect
,2015-11-23 08:08:10.709 ThaliTest[1260:1095377] client session: stateChange:0->1 Apple-Iphone5-1_PT8536.VjK3dQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:08:13.744 ThaliTest[1260:1096540] client session: connected
2015-11-23 08:08:13.745 ThaliTest[1260:1096540] client session: stateChange:1->2 Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:08:13.751 ThaliTest[1260:1096541] client session: fireConnectCallback: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:08:13.752 ThaliTest[1260:1096541] jxcore: connect: success
2015-11-23T07:08:13.754Z SendDataConnector.js: CLIENT connected ,to 57085, error: null
2015-11-23T07:08:13.755Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 08:08:13.759 ThaliTest[1260:1095254] client: relay established
,2015-11-23 08:08:13.760 ThaliTest[1260:1095254] client: new accepted socket: 0x195e46a0
,2015-11-23T07:08:13.772Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T07:08:14.278Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-23T07:08:14.291Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-23T07:08:14.305Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-23T07:08:14.786Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-23T07:08:14.787Z SendDataConnector.js: got all data for this round
,2015-11-23T07:08:14.789Z SendDataConnector.js: CLIENT Stop now
2015-11-23T07:08:14.789Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 08:08:14.790 ThaliTest[1260:1095377] jxcore: disconnect
,2015-11-23 08:08:14.791 ThaliTest[1260:1095377] client session: disconnectFromPeer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:08:14.792 ThaliTest[1260:1095377] client session: disconnect
,2015-11-23 08:08:14.793 ThaliTest[1260:1095377] client session: stateChange:2->0 Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:08:14.796 ThaliTest[1260:1095377] jxcore: disconnect: success
2015-11-23T07:08:14.798Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8536.VjK3dQ==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT1828","time":213193,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8264./5qd6Q==","time":205212,"result":"Peer disconnected","connections":5},{"name":"Apple-Iphone6-1_PT606.CSvXcQ==","time":3282,"result":",OK","connections":1},{"name":"Apple-Iphone5-1_PT8536.VjK3dQ==","time":4079,"result":"OK","connections":1}]}
,sendList : 100% : 4079 ms, 99% : 4079 ms, 95 : 4079 ms, 90% : 4079 ms.
Result count 2, range 3282 ms to  4079 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone5s-1_PT8264./5qd6Q==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-11-23T07:08:14.812Z SendDataConnector.js: CLIENT Stop now
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:08:18.154 ThaliTest[1260:1095254] multipeer session: restart
,2015-11-23 08:08:18.178 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:08:18.179 ThaliTest[1260:1095254] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:08:18.182 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-23 08:08:18.185 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:08:41.381 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:08:42.951 ThaliTest[1260:1095254] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:08:42.952 ThaliTest[1260:1095254] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:08:43.477 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:08:48.154 ThaliTest[1260:1095254] multipeer session: restart
,2015-11-23 08:08:48.177 ThaliTest[1260:1095254] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
,2015-11-23 08:08:48.179 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:08:48.183 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:08:48.344 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:09:13.424 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:09:17.615 ThaliTest[1260:1095254] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:09:17.616 ThaliTest[1260:1095254] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
2015-11-23 08:09:17.621 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerNam,e":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:09:18.154 ThaliTest[1260:1095254] multipeer session: restart
,2015-11-23 08:09:18.175 ThaliTest[1260:1095254] client: found peer: Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:09:18.178 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:09:18.180 ThaliTest[1260:1095254] client,: found peer: Apple-Iphone5s-1_PT8264./5qd6Q==
2015-11-23 08:09:18.181 ThaliTest[1260:1095254] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:09:41.089 ThaliTest[1260:1095254] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:09:41.090 ThaliTest[1260:1095254] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
2015-11-23 08:09:41.093 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerNam,e":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:09:43.195 ThaliTest[1260:1095254] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:09:46.678 ThaliTest[1260:1095254] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:09:46.679 ThaliTest[1260:1095254] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,2015-11-23 08:09:48.154 ThaliTest[1260:1095254] multipeer session: restart
2015-11-23 08:09:48.160 ThaliTest[1260:1095254] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0x6f693 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,Process 1260 stopped
* thread #1: tid = 0x10b656, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x38dc0df0 <+8>:  blo    0x38dc0e08                ; <+32>
    0x38dc0df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x38dc0df8 <+16>: ldr    r12, [pc, r12]
    0x38dc0dfc <+20>: b      0x38dc0e04                ; <+28>
,* thread #1: tid = 0x10b656, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x38e3ecc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x38d5c908 libsystem_c.dylib`abort + 76
    frame #3: 0x3808c9c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x380a6670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x3876af24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x380a3de2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x380a38ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x3876add2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x2a7b944c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #13: 0x0006f692 ThaliTest`main + 50

```
