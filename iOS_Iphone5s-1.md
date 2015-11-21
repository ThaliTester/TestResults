#### Test 5133502858c0449_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502858c0449/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C336E4E2-E37A-4491-A2EB-D07305F2A0EE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C336E4E2-E37A-4491-A2EB-D07305F2A0EE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502858c0449/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502858c0449/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F2ECB613-671C-4DDA-B43D-809908D300A3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51894"
,(lldb)     command script import "/tmp/C336E4E2-E37A-4491-A2EB-D07305F2A0EE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-21 11:23:24.213 ThaliTest[1116:885357] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0748BC3E-9551-4FEC-8AE9-7D6777DDA0C7/Library/Cookies/Cookies.binarycookies
,2015-11-21 11:23:24.617 ThaliTest[1116:885357] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-21 11:23:24.619 ThaliTest[1116:885357] Multi-tasking -> Device: YES, App: YES
,2015-11-21 11:23:24.627 ThaliTest[1116:885357] Unlimited access to network resources
,2015-11-21 11:23:24.633 ThaliTest[1116:885357] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-21 11:23:28.171 ThaliTest[1116:885357] Resetting plugins due to page load.
,2015-11-21 11:23:28.623 ThaliTest[1116:885357] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/F2ECB613-671C-4DDA-B43D-809908D300A3/ThaliTest.app/www/index.html
,2015-11-21 11:23:28.785 ThaliTest[1116:885357] JXcore Cordova plugin initializing
2015-11-21 11:23:28.787 ThaliTest[1116:885496] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
Warning: iOS does not support ToggleBluetooth
,We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
,toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,my name is : Apple-Iphone5s-1_PT497
,attempting to connect to test coordinator
check test folder
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
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
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
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
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
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found inter,faceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
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
-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,found interfaceName: lo0
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
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:525,3:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 56538
,2015-11-21 11:32:39.584 ThaliTest[1116:885496] jxcore: startBroadcasting
,2015-11-21 11:32:39.597 ThaliTest[1116:885496] server: starting Apple-Iphone5s-1_PT497.kxsT+g==
,2015-11-21 11:32:39.598 ThaliTest[1116:885496] multipeer session: start timer: 0x195883c0
,2015-11-21 11:32:39.600 ThaliTest[1116:885496] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT497
2015-11-21 11:32:39.601 ThaliTest[1116:885496] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-11-21T10:32:39.604Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-21 11:32:40.104 ThaliTest[1116:885357] multipeer session: reset timer
2015-11-21 11:32:40.105 ThaliTest[1116:885357] multipeer session: stop timer
2015-11-21 11:32:40.105 ThaliTest[1116:885357] multipeer session: start timer: 0x195883c0
2015-11-,21 11:32:40.107 ThaliTest[1116:885357] server session: connect
2015-11-21 11:32:40.108 ThaliTest[1116:885357] server session: stateChange:0->1 Apple-Iphone5-1_PT8098
,2015-11-21 11:32:40.121 ThaliTest[1116:885357] server: accepting invitation Apple-Iphone5-1_PT8098
,2015-11-21 11:32:41.081 ThaliTest[1116:885357] client: found peer: Apple-Iphone5-1_PT8098.G9Yv6w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8098.G9Yv6w==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-21 11:32:41.091 ThaliTest[1116:885357] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21 11:32:41.095 ThaliTest[1116:885357] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
device[1]: Apple-Iphone5-1_PT8098.G9Yv6w==
2015-11-21T,10:32:41.097Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21T10:32:41.098Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8098.G9Yv6w==
2015-11-21T10:32:41.099Z SendDataConnector.js: do connect now
,2015-11-21 11:32:41.100 ThaliTest[1116:885496] jxcore: connect Apple-Iphone5-1_PT8098.G9Yv6w==
2015-11-21 11:32:41.101 ThaliTest[1116:885496] client session: connect
2015-11-21 11:32:41.101 ThaliTest[1116:885496] client session: stateChange:0->1 Apple-Iphone5-1_PT8098.G9Yv6w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1308.Xoqqgw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-21 11:32:42.323 ThaliTest[1116:885357] multipeer session: reset timer
2015-11-21 11:32:42.324 ThaliTest[1116:885357] multipeer session: stop timer
2015-11-21 11:32:42.324 ThaliTest[1116:885357] multipeer session: start timer: 0x195883c0
2015-11-,21 11:32:42.325 ThaliTest[1116:885357] server session: connect
2015-11-21 11:32:42.325 ThaliTest[1116:885357] server session: stateChange:0->1 Apple-IpadAir2-1_PT1308
,2015-11-21 11:32:42.334 ThaliTest[1116:885357] server: accepting invitation Apple-IpadAir2-1_PT1308
,2015-11-21 11:32:42.681 ThaliTest[1116:886354] server session: connected
2015-11-21 11:32:42.682 ThaliTest[1116:886354] server session: stateChange:1->2 Apple-Iphone5-1_PT8098
,2015-11-21 11:32:42.696 ThaliTest[1116:885357] server relay: connected (to port: 56538)
,2015-11-21T10:32:42.704Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T10:32:42.854Z SendDataTCPServer.js: TCP/IP server has received 992 bytes of data
,2015-11-21T10:32:42.873Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-11-21T10:32:42.893Z SendDataTCPServer.js: TCP/IP server has received 18848 bytes of data
,2015-11-21T10:32:42.912Z SendDataTCPServer.js: TCP/IP server has received 28768 bytes of data
,2015-11-21T10:32:42.930Z SendDataTCPServer.js: TCP/IP server has received 45632 bytes of data
,2015-11-21T10:32:42.947Z SendDataTCPServer.js: TCP/IP server has received 64480 bytes of data
,2015-11-21T10:32:42.962Z SendDataTCPServer.js: TCP/IP server has received 80352 bytes of data
,2015-11-21T10:32:42.977Z SendDataTCPServer.js: TCP/IP server has received 81344 bytes of data
,2015-11-21T10:32:43.252Z SendDataTCPServer.js: TCP/IP server has received 82336 bytes of data
,2015-11-21T10:32:43.266Z SendDataTCPServer.js: TCP/IP server has received 91264 bytes of data
,2015-11-21T10:32:43.282Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-21 11:32:43.336 ThaliTest[1116:886347] server session: not connected Apple-Iphone5-1_PT8098
,2015-11-21 11:32:43.725 ThaliTest[1116:886344] client session: connected
2015-11-21 11:32:43.726 ThaliTest[1116:886344] client session: stateChange:1->2 Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21 11:32:43.735 ThaliTest[1116:886355] client session: fireConnectCallback: Apple-Iphone5-1_PT8098.G9Yv6w==
2015-11-21 11:32:43.737 ThaliTest[1116:886355] jxcore: connect: success
,2015-11-21T10:32:43.740Z SendDataConnector.js: CLIENT connected to 56542, error: null
2015-11-21T10:32:43.740Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 11:32:43.743 ThaliTest[1116:885357] client: relay established
2015-11-21 11:32:43.744 ThaliTest[1116:885357] client: new accepted socket: 0x19599580
,2015-11-21T10:32:43.757Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-21T10:32:43.876Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-21T10:32:43.889Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-21T10:32:43.903Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-21T10:32:43.903Z SendDataConnector.js: got all data for this round
,2015-11-21T10:32:43.904Z SendDataConnector.js: CLIENT Stop now
2015-11-21T10:32:43.904Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-21 11:32:43.905 ThaliTest[1116:885496] jxcore: disconnect
,2015-11-21 11:32:43.905 ThaliTest[1116:885496] client session: disconnectFromPeer: Apple-Iphone5-1_PT8098.G9Yv6w==
2015-11-21 11:32:43.906 ThaliTest[1116:885496] client session: disconnect
2015-11-21 11:32:43.906 ThaliTest[1116:885496] client session: st,ateChange:2->0 Apple-Iphone5-1_PT8098.G9Yv6w==
2015-11-21 11:32:43.907 ThaliTest[1116:885496] jxcore: disconnect: success
2015-11-21T10:32:43.907Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8098.G9Yv6w==
---- round done--------
device[2]: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21T10:32:43.909Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21T10:32:43.910Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21T10:32:43.910Z SendDataConnector.js: do connect now
,2015-11-21 11:32:43.911 ThaliTest[1116:885496] jxcore: connect Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21 11:32:43.911 ThaliTest[1116:885496] client session: connect
2015-11-21 11:32:43.911 ThaliTest[1116:885496] client session: stateChange:0->1 Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:32:45.034 ThaliTest[1116:886355] server session: connected
2015-11-21 11:32:45.035 ThaliTest[1116:886355] server session: stateChange:1->2 Apple-IpadAir2-1_PT1308
,2015-11-21 11:32:45.056 ThaliTest[1116:885357] server relay: connected (to port: 56538)
2015-11-21T10:32:45.061Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T10:32:45.570Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-11-21T10:32:45.587Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-11-21T10:32:45.604Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-11-21T10:32:45.621Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-11-21T10:32:45.637Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-21 11:32:45.972 ThaliTest[1116:886354] server session: not connected Apple-IpadAir2-1_PT1308
,2015-11-21 11:32:46.990 ThaliTest[1116:886347] client session: connected
2015-11-21 11:32:46.991 ThaliTest[1116:886347] client session: stateChange:1->2 Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:32:47.003 ThaliTest[1116:886355] client session: fireConnectCallback: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21 11:32:47.004 ThaliTest[1116:886355] jxcore: connect: success
2015-11-21T10:32:47.005Z SendDataConnector.js: CLIENT connected to 56546, error: null
,2015-11-21T10:32:47.005Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 11:32:47.009 ThaliTest[1116:885357] client: relay established
2015-11-21 11:32:47.010 ThaliTest[1116:885357] client: new accepted socket: 0x19646690
,2015-11-21T10:32:47.022Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-21T10:32:47.654Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-21T10:32:47.681Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-21T10:32:48.127Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-21T10:32:48.128Z SendDataConnector.js: got all data for this round
,2015-11-21T10:32:48.132Z SendDataConnector.js: CLIENT Stop now
2015-11-21T10:32:48.132Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 11:32:48.134 ThaliTest[1116:885496] jxcore: disconnect
,2015-11-21 11:32:48.136 ThaliTest[1116:885496] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21 11:32:48.137 ThaliTest[1116:885496] client session: disconnect
2015-11-21 11:32:48.137 ThaliTest[1116:885496] client session: stateChange:2->0 Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:32:48.143 ThaliTest[1116:885496] jxcore: disconnect: success
2015-11-21T10:32:48.147Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1308.Xoqqgw==
---- round done--------
device[3]: Apple-Iphone6-1_PT3409.7,QVn3g==
2015-11-21T10:32:48.149Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21T10:32:48.150Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21T10:32:48.150Z SendDataConnector.js: do connect now
,2015-11-21 11:32:48.153 ThaliTest[1116:885496] jxcore: connect Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21 11:32:48.154 ThaliTest[1116:885496] client session: connect
2015-11-21 11:32:48.155 ThaliTest[1116:885496] client session: stateChange:0->1 Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:32:51.190 ThaliTest[1116:886354] client session: connected
2015-11-21 11:32:51.190 ThaliTest[1116:886354] client session: stateChange:1->2 Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:32:51.200 ThaliTest[1116:886344] client session: fireConnectCallback: Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21 11:32:51.200 ThaliTest[1116:886344] jxcore: connect: success
2015-11-21T10:32:51.202Z SendDataConnector.js: CLIENT connected to, 56550, error: null
2015-11-21T10:32:51.202Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 11:32:51.205 ThaliTest[1116:885357] client: relay established
2015-11-21 11:32:51.206 ThaliTest[1116:885357] client: new accepted socket: 0x1964ef90
,2015-11-21T10:32:51.218Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-21T10:32:51.585Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-21T10:32:51.585Z SendDataConnector.js: got all data for this round
,2015-11-21T10:32:51.586Z SendDataConnector.js: CLIENT Stop now
2015-11-21T10:32:51.586Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-21 11:32:51.586 ThaliTest[1116:885496] jxcore: disconnect
2015-11-21 11:32:51.587 ThaliTest[1116:885496] client session: disconnectFromPeer: Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:32:51.587 ThaliTest[1116:885496] client session: disconnect
,2015-11-21 11:32:51.587 ThaliTest[1116:885496] client session: stateChange:2->0 Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21 11:32:51.588 ThaliTest[1116:885496] jxcore: disconnect: success
2015-11-21T10:32:51.589Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3409.7QVn3g==
,---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT497","time":12024,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT8098.G9Yv6w==","time":2806,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT1308.Xoqqgw==","time":4220,"result":"OK","connections":1},{"name":"Apple-Iphone6-1_PT3409.7QVn3g==","time":3435,"result":"OK","connections":1}]}
,sendList : 100% : 4220 ms, 99% : 4220 ms, 95 : 4220 ms, 90% : 4220 ms.
,Result count 3, range 2806 ms to  4220 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-21T10:32:51.595Z SendDataConnector.js: CLIENT Stop now
,2015-11-21 11:33:12.324 ThaliTest[1116:885357] multipeer session: restart
,2015-11-21 11:33:12.440 ThaliTest[1116:885357] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21 11:33:12.441 ThaliTest[1116:885357] client: found peer: Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21 11:33:12.621 ThaliTest[1116:885357] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:33:27.142 ThaliTest[1116:885357] client: lost peer: Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21 11:33:27.142 ThaliTest[1116:885357] client session: onPeerLost: Apple-Iphone6-1_PT3409.7QVn3g==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":false}]
,2015-11-21 11:33:27.875 ThaliTest[1116:885357] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":true}]
,2015-11-21 11:33:36.181 ThaliTest[1116:885357] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:33:42.325 ThaliTest[1116:885357] multipeer session: restart
,2015-11-21 11:33:42.348 ThaliTest[1116:885357] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21 11:33:42.350 ThaliTest[1116:885357] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:33:42.351 ThaliTest[1116:885357] client: found peer: Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21 11:34:04.284 ThaliTest[1116:885357] client: lost peer: Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21 11:34:04.285 ThaliTest[1116:885357] client session: onPeerLost: Apple-Iphone6-1_PT3409.7QVn3g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":false}]
,2015-11-21 11:34:06.007 ThaliTest[1116:885357] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":true}]
,2015-11-21 11:34:12.324 ThaliTest[1116:885357] multipeer session: restart
,2015-11-21 11:34:12.344 ThaliTest[1116:885357] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21 11:34:12.347 ThaliTest[1116:885357] client: found peer: Apple-Iphone5-1_PT8098.G9Yv6w==
2015-11-21 11:34:12.348 ThaliTest[1116:885357] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
,2015-11-21 11:34:37.456 ThaliTest[1116:885357] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:34:42.324 ThaliTest[1116:885357] multipeer session: restart
,2015-11-21 11:34:42.346 ThaliTest[1116:885357] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21 11:34:42.347 ThaliTest[1116:885357] client: found peer: Apple-IpadAir2-1_PT1308.Xoqqgw==
2015-11-21 11:34:42.348 ThaliTest[1116:885357] client: ,found peer: Apple-Iphone5-1_PT8098.G9Yv6w==
,2015-11-21 11:34:57.386 ThaliTest[1116:885357] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
,2015-11-21 11:35:01.095 ThaliTest[1116:885357] client: lost peer: Apple-Iphone6-1_PT3409.7QVn3g==
2015-11-21 11:35:01.096 ThaliTest[1116:885357] client session: onPeerLost: Apple-Iphone6-1_PT3409.7QVn3g==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":false}]
,2015-11-21 11:35:02.647 ThaliTest[1116:885357] client: found peer: Apple-Iphone6-1_PT3409.7QVn3g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3409.7QVn3g==","peerName":"(null)","peerAvailable":true}]
,2015-11-21 11:35:03.405 ThaliTest[1116:885357] multipeer session: reset timer
2015-11-21 11:35:03.406 ThaliTest[1116:885357] multipeer session: stop timer
2015-11-21 11:35:03.407 ThaliTest[1116:885357] multipeer session: start timer: 0x195883c0
2015-11-,21 11:35:03.407 ThaliTest[1116:885357] server session: connect
2015-11-21 11:35:03.408 ThaliTest[1116:885357] server session: stateChange:0->1 Apple-Iphone6-1_PT3409
,2015-11-21 11:35:03.416 ThaliTest[1116:885357] server: accepting invitation Apple-Iphone6-1_PT3409
,2015-11-21 11:35:05.583 ThaliTest[1116:886756] server session: connected
2015-11-21 11:35:05.584 ThaliTest[1116:886756] server session: stateChange:1->2 Apple-Iphone6-1_PT3409
,2015-11-21 11:35:05.594 ThaliTest[1116:885357] server relay: connected (to port: 56538)
2015-11-21T10:35:05.595Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T10:35:05.709Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-11-21T10:35:05.737Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-21T10:35:05.751Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-11-21T10:35:05.770Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-11-21T10:35:05.787Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-11-21T10:35:05.807Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-21 11:35:05.829 ThaliTest[1116:886815] server session: not connected Apple-Iphone6-1_PT3409
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-11-21 11:35:07.008 ThaliTest[1116:885496] jxcore: stopBroadcasting
2015-11-21 11:35:07.009 ThaliTest[1116:885496] THEMultipeerSession stopping peer
2015-11-21 11:35:07.009 ThaliTest[1116:885496] multipeer session: stop timer
2015-11-21 11:35:07.010, ThaliTest[1116:885496] server session: disconnect
2015-11-21 11:35:07.011 ThaliTest[1116:885496] server session: stateChange:2->0 Apple-Iphone5-1_PT8098
,2015-11-21 11:35:07.019 ThaliTest[1116:885496] server session: disconnect
2015-11-21 11:35:07.020 ThaliTest[1116:885496] server session: stateChange:2->0 Apple-IpadAir2-1_PT1308
,2015-11-21 11:35:07.026 ThaliTest[1116:885496] server session: disconnect
,2015-11-21 11:35:07.028 ThaliTest[1116:885496] server session: stateChange:2->0 Apple-Iphone6-1_PT3409
,2015-11-21 11:35:07.037 ThaliTest[1116:885496] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-21T10:35:07.062Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T10:35:07.066Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T10:35:07.071Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T10:35:07.072Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT8098.G9Yv6w==\",\"time\":2806,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT3409.7QVn3g==\",\"time\":3435,\"r,esult\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT1308.Xoqqgw==\",\"time\":4220,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT8098.G9Yv6,w==\",\"time\":2806,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT8098.G9Yv6w==\",\"time\":2973,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT497.kxsT+g==\",\"time\":2983,\"result\":\"OK\",\"connections\":1},{\"na,me\":\"Apple-Iphone5s-1_PT497.kxsT+g==\",\"time\":3323,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT3409.7QVn3g==\",\"time\":3435,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT3409.7QVn3g==\",\"time\":4060,\"resul,t\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT1308.Xoqqgw==\",\"time\":4220,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT3409.7QVn3g==\",\"time\":4296,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT,1308.Xoqqgw==\",\"time\":4732,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT497.kxsT+g==\",\"time\":4864,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT8098.G9Yv6w==\",\"time\":5119,\"result\":\"OK\",\"connections\,":1}]}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
