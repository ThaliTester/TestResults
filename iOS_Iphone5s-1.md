#### Test 51335028f10f918_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028f10f918/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2DCA3157-E432-431C-AF9A-12488306EA20/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2DCA3157-E432-431C-AF9A-12488306EA20/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028f10f918/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028f10f918/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F8CC896A-CEA9-4B88-BC82-0AD85710F233/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51483"
,(lldb)     command script import "/tmp/2DCA3157-E432-431C-AF9A-12488306EA20/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 14:48:03.222 ThaliTest[1036:788198] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7F3C9510-9743-4B7A-A454-2D20E8F3D417/Library/Cookies/Cookies.binarycookies
,2015-11-20 14:48:03.628 ThaliTest[1036:788198] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 14:48:03.629 ThaliTest[1036:788198] Multi-tasking -> Device: YES, App: YES
,2015-11-20 14:48:03.637 ThaliTest[1036:788198] Unlimited access to network resources
,2015-11-20 14:48:03.643 ThaliTest[1036:788198] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 14:48:07.088 ThaliTest[1036:788198] Resetting plugins due to page load.
,2015-11-20 14:48:07.529 ThaliTest[1036:788198] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/F8CC896A-CEA9-4B88-BC82-0AD85710F233/ThaliTest.app/www/index.html
,2015-11-20 14:48:07.685 ThaliTest[1036:788198] JXcore Cordova plugin initializing
,2015-11-20 14:48:07.686 ThaliTest[1036:788320] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
,Warning: iOS does not support ToggleBluetooth
We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
,toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,my name is : Apple-Iphone5s-1_PT9513
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
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"10000000\",\"conReTryTimeout\":\"1000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 56159
,2015-11-20 14:57:12.630 ThaliTest[1036:788320] jxcore: startBroadcasting
,2015-11-20 14:57:12.643 ThaliTest[1036:788320] server: starting Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:12.645 ThaliTest[1036:788320] multipeer session: start timer: 0x1af88ab0
2015-11-20 14:57:12.646 ThaliTest[1036:788320] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT9513
2015-11-20 14:57:12.647 ThaliTest[1036:788320] jxcore: s,tartBroadcasting: success
StartBroadcasting started ok
2015-11-20T13:57:12.651Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-20 14:57:13.324 ThaliTest[1036:788198] multipeer session: reset timer
2015-11-20 14:57:13.325 ThaliTest[1036:788198] multipeer session: stop timer
2015-11-20 14:57:13.326 ThaliTest[1036:788198] multipeer session: start timer: 0x1af88ab0
2015-11-,20 14:57:13.327 ThaliTest[1036:788198] server session: connect
2015-11-20 14:57:13.328 ThaliTest[1036:788198] server session: stateChange:0->1 Apple-Iphone5-1_PT738
,2015-11-20 14:57:13.340 ThaliTest[1036:788198] server: accepting invitation Apple-Iphone5-1_PT738
,2015-11-20 14:57:13.638 ThaliTest[1036:788198] client: found peer: Apple-IpadAir2-1_PT9530.n+0V8A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9530.n+0V8A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: t,rue
,device[1]: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:57:13.645Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:57:13.646Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9530.n+0V8A==,
2015-11-20T13:57:13.646Z SendDataConnector.js: do connect now
2015-11-20 14:57:13.647 ThaliTest[1036:788320] jxcore: connect Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:13.649 ThaliTest[1036:788320] client session: connect
2015-11-20 14:57:13.650 ThaliTest[1036:788320] client session: stateChange:0->1 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:13.972 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT738.lFO7fw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 14:57:14.270 ThaliTest[1036:788198] multipeer session: reset timer
2015-11-20 14:57:14.270 ThaliTest[1036:788198] multipeer session: stop timer
2015-11-20 14:57:14.271 ThaliTest[1036:788198] multipeer session: start timer: 0x1af88ab0
2015-11-,20 14:57:14.272 ThaliTest[1036:788198] server session: connect
2015-11-20 14:57:14.272 ThaliTest[1036:788198] server session: stateChange:0->1 Apple-IpadAir2-1_PT9530
,2015-11-20 14:57:14.281 ThaliTest[1036:788198] server: accepting invitation Apple-IpadAir2-1_PT9530
,2015-11-20 14:57:15.538 ThaliTest[1036:788198] client: found peer: Apple-Iphone6-1_PT8294.ood35g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8294.ood35g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 14:57:15.722 ThaliTest[1036:789116] server session: connected
2015-11-20 14:57:15.723 ThaliTest[1036:789116] server session: stateChange:1->2 Apple-Iphone5-1_PT738
,2015-11-20 14:57:15.731 ThaliTest[1036:788198] server relay: connected (to port: 56159)
,2015-11-20T13:57:15.737Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 14:57:17.293 ThaliTest[1036:789109] server session: connected
2015-11-20 14:57:17.294 ThaliTest[1036:789109] server session: stateChange:1->2 Apple-IpadAir2-1_PT9530
,2015-11-20 14:57:17.300 ThaliTest[1036:788198] server relay: connected (to port: 56159)
,2015-11-20T13:57:17.310Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 14:57:17.410 ThaliTest[1036:789109] client session: connected
2015-11-20 14:57:17.411 ThaliTest[1036:789109] client session: stateChange:1->2 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:17.416 ThaliTest[1036:789109] client session: fireConnectCallback: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:57:17.417 ThaliTest[1036:789109] jxcore: connect: success
2015-11-20T13:57:17.420Z SendDataConnector.js: CLIENT connected t,o 56164, error: null
2015-11-20T13:57:17.420Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:57:17.425 ThaliTest[1036:788198] client: relay established
2015-11-20 14:57:17.425 ThaliTest[1036:788198] client: new accepted socket: 0x1afa0e70
,2015-11-20T13:57:17.438Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T13:57:22.192Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:22.361Z SendDataTCPServer.js: TCP/IP server has received 131072 bytes of data
,2015-11-20T13:57:22.364Z SendDataTCPServer.js: TCP/IP server has received 262144 bytes of data
,2015-11-20T13:57:22.365Z SendDataTCPServer.js: TCP/IP server has received 393216 bytes of data
,2015-11-20T13:57:22.367Z SendDataTCPServer.js: TCP/IP server has received 524288 bytes of data
,2015-11-20T13:57:22.369Z SendDataTCPServer.js: TCP/IP server has received 655360 bytes of data
,2015-11-20T13:57:22.371Z SendDataTCPServer.js: TCP/IP server has received 786432 bytes of data
,2015-11-20T13:57:22.372Z SendDataTCPServer.js: TCP/IP server has received 805920 bytes of data
,2015-11-20T13:57:32.200Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T13:57:32.200Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T13:57:32.202Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T13:57:32.203Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T13:57:33.210Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:57:33.211Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:34.212 ThaliTest[1036:788320] jxcore: disconnect
2015-11-20 14:57:34.213 ThaliTest[1036:788320] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:57:34.214 ThaliTest[1036:788320] client session: disconnec,t
2015-11-20 14:57:34.214 ThaliTest[1036:788320] client session: stateChange:2->0 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:56.225 ThaliTest[1036:789114] server session: not connected Apple-Iphone5-1_PT738
,2015-11-20 14:58:00.401 ThaliTest[1036:788198] multipeer session: restart
2015-11-20 14:58:00.401 ThaliTest[1036:788320] jxcore: disconnect: success
2015-11-20T13:58:00.401Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT,9530.n+0V8A==
2015-11-20T13:58:00.402Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT9530.n+0V8A== with availability status: true
2015-11-20T13:58:00.402Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9530,.n+0V8A==
2015-11-20T13:58:00.402Z SendDataConnector.js: do connect now
2015-11-20 14:58:00.402 ThaliTest[1036:788320] jxcore: connect Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:58:00.410 ThaliTest[1036:788320] client session: connect
2015-11-20 14,:58:00.410 ThaliTest[1036:788320] client session: stateChange:0->1 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:58:00.423 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:58:00.423 ThaliTest[1036:788198] client: found peer: Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:58:00.425 ThaliTest[1036:788198] client: found peer: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:58:00.437Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
2015-11-20T13:58:00.440Z SendDataTCPServer.js: TCP/IP server has received 936992 bytes of data
2015-11-20T13:58:00.445Z SendDataTCPServer.js: TCP/IP server has received 946080 bytes of data
,2015-11-20 14:58:00.999 ThaliTest[1036:788198] multipeer session: reset timer
2015-11-20 14:58:01.000 ThaliTest[1036:788198] multipeer session: stop timer
2015-11-20 14:58:01.001 ThaliTest[1036:788198] multipeer session: start timer: 0x1af88ab0
2015-11-,20 14:58:01.002 ThaliTest[1036:788198] server: disconnecting to refresh session (Apple-Iphone5-1_PT738)
2015-11-20 14:58:01.003 ThaliTest[1036:788198] server session: disconnect
2015-11-20 14:58:01.003 ThaliTest[1036:788198] server session: stateChange:2,->0 Apple-Iphone5-1_PT738
,2015-11-20 14:58:01.010 ThaliTest[1036:788198] server session: connect
2015-11-20 14:58:01.011 ThaliTest[1036:788198] server session: stateChange:0->1 Apple-Iphone5-1_PT738
,2015-11-20T13:58:01.020Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20 14:58:01.022 ThaliTest[1036:788198] server: accepting invitation Apple-Iphone5-1_PT738
2015-11-20 14:58:01.023 ThaliTest[1036:788198] multipeer session: reset timer
2015-11-20 14:58:01.023 ThaliTest[1036:788198] multipeer session: stop timer
,2015-11-20 14:58:01.024 ThaliTest[1036:788198] multipeer session: start timer: 0x1af88ab0
2015-11-20 14:58:01.024 ThaliTest[1036:788198] server: disconnecting to refresh session (Apple-Iphone5-1_PT738)
2015-11-20 14:58:01.025 ThaliTest[1036:788198] serve,r session: disconnect
2015-11-20 14:58:01.025 ThaliTest[1036:788198] server session: stateChange:1->0 Apple-Iphone5-1_PT738
2015-11-20 14:58:01.026 ThaliTest[1036:788198] server session: connect
2015-11-20 14:58:01.026 ThaliTest[1036:788198] server sess,ion: stateChange:0->1 Apple-Iphone5-1_PT738
,2015-11-20 14:58:01.042 ThaliTest[1036:788198] server: accepting invitation Apple-Iphone5-1_PT738
2015-11-20 14:58:01.044 ThaliTest[1036:788198] multipeer session: reset timer
2015-11-20 14:58:01.044 ThaliTest[1036:788198] multipeer session: stop timer
,2015-11-20 14:58:01.045 ThaliTest[1036:788198] multipeer session: start timer: 0x1af88ab0
2015-11-20 14:58:01.045 ThaliTest[1036:788198] server: disconnecting to refresh session (Apple-Iphone5-1_PT738)
2015-11-20 14:58:01.046 ThaliTest[1036:788198] serve,r session: disconnect
2015-11-20 14:58:01.047 ThaliTest[1036:788198] server session: stateChange:1->0 Apple-Iphone5-1_PT738
2015-11-20 14:58:01.047 ThaliTest[1036:788198] server session: connect
2015-11-20 14:58:01.062 ThaliTest[1036:788198] server sess,ion: stateChange:0->1 Apple-Iphone5-1_PT738
,2015-11-20 14:58:01.080 ThaliTest[1036:788198] server: accepting invitation Apple-Iphone5-1_PT738
,2015-11-20 14:58:11.136 ThaliTest[1036:789240] server session: not connected Apple-Iphone5-1_PT738
,2015-11-20 14:58:31.046 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 14:58:31.076 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:58:31.077 ThaliTest[1036:788198] client: found peer: Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:58:31.079 ThaliTest[1036:788198] client: fo,und peer: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:58:32.037 ThaliTest[1036:789240] client session: not connected Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:58:32.038 ThaliTest[1036:789240] client session: onLinkFailure: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:58:32.039 ThaliTest,[1036:789240] client session: disconnect
2015-11-20 14:58:32.039 ThaliTest[1036:789240] client session: stateChange:1->0 Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:58:32.040 ThaliTest[1036:789240] client session: fireConnectCallback: Apple-IpadAir2-1,_PT9530.n+0V8A==
2015-11-20 14:58:32.040 ThaliTest[1036:789240] jxcore: connect: fail: Peer disconnected
2015-11-20T13:58:32.042Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T13:58:32.042Z SendDataConnector.js: CLIENT, Can not Connect: Peer disconnected
2015-11-20T13:58:32.043Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T13:58:33.054Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:58:33.055Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:58:34.059 ThaliTest[1036:788320] jxcore: disconnect
2015-11-20 14:58:34.060 ThaliTest[1036:788320] jxcore: disconnect: fail
2015-11-20T13:58:34.061Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9530.n+0V8A,==
2015-11-20T13:58:34.061Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT9530.n+0V8A== with availability status: true
,2015-11-20T13:58:34.062Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:58:34.062Z SendDataConnector.js: do connect now
2015-11-20 14:58:34.063 ThaliTest[1036:788320] jxcore: connect Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:58:34.064 ThaliTest[1036:788320] client session: connect
,2015-11-20 14:58:34.065 ThaliTest[1036:788320] client session: stateChange:0->1 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:58:35.860 ThaliTest[1036:788198] client: lost peer: Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:58:35.861 ThaliTest[1036:788198] client session: onPeerLost: Apple-Iphone6-1_PT8294.ood35g==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT8294.ood35g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-20 14:58:37.478 ThaliTest[1036:788198] client: found peer: Apple-Iphone6-1_PT8294.ood35g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8294.ood35g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 14:58:41.153 ThaliTest[1036:788198] client: found peer: Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20T13:58:47.606Z SendDataTCPServer.js: TCP/IP server has received 957030 bytes of data
,2015-11-20T13:58:47.623Z SendDataTCPServer.js: TCP/IP server has received 963600 bytes of data
,2015-11-20T13:58:47.643Z SendDataTCPServer.js: TCP/IP server has received 971792 bytes of data
,2015-11-20T13:58:47.660Z SendDataTCPServer.js: TCP/IP server has received 1003020 bytes of data
,2015-11-20T13:58:47.678Z SendDataTCPServer.js: TCP/IP server has received 1033680 bytes of data
,2015-11-20T13:58:47.695Z SendDataTCPServer.js: TCP/IP server has received 1055580 bytes of data
,2015-11-20T13:58:47.855Z SendDataTCPServer.js: TCP/IP server has received 1084050 bytes of data
,2015-11-20T13:58:47.874Z SendDataTCPServer.js: TCP/IP server has received 1092810 bytes of data
,2015-11-20T13:58:47.902Z SendDataTCPServer.js: TCP/IP server has received 1095000 bytes of data
,2015-11-20T13:58:47.917Z SendDataTCPServer.js: TCP/IP server has received 1097048 bytes of data
,2015-11-20T13:58:47.930Z SendDataTCPServer.js: TCP/IP server has received 1108140 bytes of data
,2015-11-20T13:58:47.972Z SendDataTCPServer.js: TCP/IP server has received 1110330 bytes of data
,2015-11-20T13:58:47.985Z SendDataTCPServer.js: TCP/IP server has received 1127850 bytes of data
,2015-11-20 14:58:48.000 ThaliTest[1036:789329] server session: not connected Apple-IpadAir2-1_PT9530
,2015-11-20T13:58:48.002Z SendDataTCPServer.js: TCP/IP server has received 1145370 bytes of data
,2015-11-20 14:58:51.240 ThaliTest[1036:788198] multipeer session: reset timer
2015-11-20 14:58:51.240 ThaliTest[1036:788198] multipeer session: stop timer
2015-11-20 14:58:51.241 ThaliTest[1036:788198] multipeer session: start timer: 0x1af88ab0
2015-11-,20 14:58:51.242 ThaliTest[1036:788198] server: disconnecting to refresh session (Apple-IpadAir2-1_PT9530)
2015-11-20 14:58:51.242 ThaliTest[1036:788198] server session: disconnect
2015-11-20 14:58:51.243 ThaliTest[1036:788198] server session: stateChange,:2->0 Apple-IpadAir2-1_PT9530
,2015-11-20 14:58:51.247 ThaliTest[1036:788198] server session: connect
,2015-11-20 14:58:51.248 ThaliTest[1036:788198] server session: stateChange:0->1 Apple-IpadAir2-1_PT9530
,2015-11-20 14:58:51.258 ThaliTest[1036:788198] server: accepting invitation Apple-IpadAir2-1_PT9530
2015-11-20T13:58:51.258Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-20 14:58:51.258 ThaliTest[1036:788198] multipeer session: reset timer
2015-,11-20 14:58:51.259 ThaliTest[1036:788198] multipeer session: stop timer
2015-11-20 14:58:51.259 ThaliTest[1036:788198] multipeer session: start timer: 0x1af88ab0
2015-11-20 14:58:51.260 ThaliTest[1036:788198] server: disconnecting to refresh session (App,le-IpadAir2-1_PT9530)
2015-11-20 14:58:51.260 ThaliTest[1036:788198] server session: disconnect
2015-11-20 14:58:51.261 ThaliTest[1036:788198] server session: stateChange:1->0 Apple-IpadAir2-1_PT9530
2015-11-20 14:58:51.261 ThaliTest[1036:788198] server, session: connect
2015-11-20 14:58:51.262 ThaliTest[1036:788198] server session: stateChange:0->1 Apple-IpadAir2-1_PT9530
,2015-11-20 14:58:51.278 ThaliTest[1036:788198] server: accepting invitation Apple-IpadAir2-1_PT9530
,2015-11-20 14:59:01.351 ThaliTest[1036:789300] server session: not connected Apple-IpadAir2-1_PT9530
,2015-11-20 14:59:07.073 ThaliTest[1036:789330] client session: not connected Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:59:07.074 ThaliTest[1036:789330] client session: onLinkFailure: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:59:07.074 ThaliTest,[1036:789330] client session: disconnect
2015-11-20 14:59:07.075 ThaliTest[1036:789330] client session: stateChange:1->0 Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:59:07.075 ThaliTest[1036:789330] client session: fireConnectCallback: Apple-IpadAir2-1,_PT9530.n+0V8A==
2015-11-20 14:59:07.076 ThaliTest[1036:789330] jxcore: connect: fail: Peer disconnected
,2015-11-20T13:59:07.077Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T13:59:07.078Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T13:59:07.078Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T13:59:08.087Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:08.087Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:59:09.029 ThaliTest[1036:788198] client: lost peer: Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:59:09.030 ThaliTest[1036:788198] client session: onPeerLost: Apple-Iphone6-1_PT8294.ood35g==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT8294.ood35g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-20 14:59:09.095 ThaliTest[1036:788320] jxcore: disconnect
2015-11-20 14:59:09.096 ThaliTest[1036:788320] jxcore: disconnect: fail
2015-11-20T13:59:09.097Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9530.n+0V8A,==
2015-11-20T13:59:09.097Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT9530.n+0V8A== with availability status: true
,2015-11-20T13:59:09.098Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:59:09.098Z SendDataConnector.js: do connect now
,2015-11-20 14:59:09.099 ThaliTest[1036:788320] jxcore: connect Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:59:09.101 ThaliTest[1036:788320] client session: connect
2015-11-20 14:59:09.101 ThaliTest[1036:788320] client session: stateChange:0->1 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:59:12.264 ThaliTest[1036:788198] client: found peer: Apple-Iphone6-1_PT8294.ood35g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8294.ood35g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 14:59:15.818 ThaliTest[1036:789511] client session: connected
2015-11-20 14:59:15.820 ThaliTest[1036:789511] client session: stateChange:1->2 Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:59:15.822 ThaliTest[1036:789511] client session: fireC,onnectCallback: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 14:59:15.822 ThaliTest[1036:789511] jxcore: connect: success
2015-11-20T13:59:15.824Z SendDataConnector.js: CLIENT connected to 56178, error: null
2015-11-20T13:59:15.824Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:59:15.829 ThaliTest[1036:788198] client: relay established
2015-11-20 14:59:15.830 ThaliTest[1036:788198] client: new accepted socket: 0x1ae92cc0
,2015-11-20T13:59:15.841Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 14:59:18.885 ThaliTest[1036:788198] client: lost peer: Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:59:18.886 ThaliTest[1036:788198] client session: onPeerLost: Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20T13:59:20.391Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8294.ood35g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-20 14:59:21.562 ThaliTest[1036:788198] multipeer session: restart
2015-11-20T13:59:21.584Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:59:21.585Z SendDataConnector.js: CLIENT is data rece,ived : 550000
,2015-11-20 14:59:21.877 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T13:59:21.880Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:59:21.881Z SendDataConnector,.js: CLIENT is data received : 770000
,2015-11-20T13:59:21.906Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:21.910Z SendDataConnector.js: CLIENT is data received : 780000
,2015-11-20 14:59:22.563 ThaliTest[1036:788198] client: found peer: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:22.575Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:22.575Z SendDataConnector.js: CLIENT is data received : 1870000
,2015-11-20T13:59:22.862Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:22.862Z SendDataConnector.js: CLIENT is data received : 2560000
,2015-11-20T13:59:22.888Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:22.888Z SendDataConnector.js: CLIENT is data received : 2600000
,2015-11-20T13:59:23.100Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:23.101Z SendDataConnector.js: CLIENT is data received : 3300000
,2015-11-20T13:59:24.388Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:59:24.389Z SendDataConnector.js: CLIENT is data received : 4730000
,2015-11-20T13:59:25.250Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:25.251Z SendDataConnector.js: CLIENT is data received : 5520000
,2015-11-20T13:59:25.547Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:25.548Z SendDataConnector.js: CLIENT is data received : 5630000
,2015-11-20T13:59:26.508Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:59:26.509Z SendDataConnector.js: CLIENT is data received : 6040000
,2015-11-20T13:59:27.766Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:27.767Z SendDataConnector.js: CLIENT is data received : 7800000
,2015-11-20T13:59:27.937Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:27.938Z SendDataConnector.js: CLIENT is data received : 8540000
,2015-11-20T13:59:27.984Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:27.985Z SendDataConnector.js: CLIENT is data received : 8730000
,2015-11-20T13:59:28.263Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:59:28.263Z SendDataConnector.js: CLIENT is data received : 9790000
,2015-11-20T13:59:28.312Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:59:28.312Z SendDataConnector.js: CLIENT is data received : 9800000
,2015-11-20T13:59:28.324Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:59:28.324Z SendDataConnector.js: CLIENT is data received : 9840000
,2015-11-20T13:59:28.350Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:28.350Z SendDataConnector.js: CLIENT is data received : 9860000
,2015-11-20T13:59:28.364Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:28.364Z SendDataConnector.js: CLIENT is data received : 9870000
,2015-11-20T13:59:28.527Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:28.529Z SendDataConnector.js: CLIENT is data received : 9880000
,2015-11-20T13:59:28.543Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:59:28.545Z SendDataConnector.js: CLIENT is data received : 9910000
,2015-11-20T13:59:28.558Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:28.559Z SendDataConnector.js: CLIENT is data received : 9930000
,2015-11-20T13:59:28.648Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:28.649Z SendDataConnector.js: CLIENT is data received : 9940000
,2015-11-20T13:59:28.690Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:28.691Z SendDataConnector.js: CLIENT is data received : 9950000
,2015-11-20T13:59:28.704Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:28.705Z SendDataConnector.js: CLIENT is data received : 9960000
,2015-11-20T13:59:28.791Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20T13:59:28.792Z SendDataConnector.js: CLIENT is data received : 9990000
,2015-11-20T13:59:29.053Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:29.053Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T13:59:29.054Z SendDataConnector.js: got all data for this round
,2015-11-20T13:59:29.057Z SendDataConnector.js: CLIENT Stop now
2015-11-20T13:59:29.057Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 14:59:29.058 ThaliTest[1036:788320] jxcore: disconnect
,2015-11-20 14:59:29.060 ThaliTest[1036:788320] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:59:29.061 ThaliTest[1036:788320] client session: disconnect
,2015-11-20 14:59:29.062 ThaliTest[1036:788320] client session: stateChange:2->0 Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:59:29.066 ThaliTest[1036:788320] jxcore: disconnect: success
,2015-11-20T13:59:29.070Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9530.n+0V8A==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:59:29.074Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:59:29.076Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:59:29.077Z SendDataConnector.js: do connect now
,2015-11-20 14:59:29.078 ThaliTest[1036:788320] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:29.080 ThaliTest[1036:788320] client session: connect
,2015-11-20 14:59:29.082 ThaliTest[1036:788320] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:33.050 ThaliTest[1036:789511] client session: connected
2015-11-20 14:59:33.051 ThaliTest[1036:789511] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:33.055 ThaliTest[1036:789329] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:33.056 ThaliTest[1036:789329] jxcore: connect: success
2015-11-20T13:59:33.057Z SendDataConnector.js: CLIENT connected to 56182, error: null
,2015-11-20T13:59:33.058Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:59:33.063 ThaliTest[1036:788198] client: relay established
2015-11-20 14:59:33.064 ThaliTest[1036:788198] client: new accepted socket: 0x16e1dc60
,2015-11-20T13:59:33.075Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T13:59:37.641Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:59:47.644Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T13:59:47.645Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T13:59:47.646Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20 14:59:47.646 ThaliTest[1036:788198] client: socket closed
2015-11-20 14:59:47.647 ThaliTest[1036:788198] client relay: socket disconnected
2015-11-20T13:59:47.648Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 14:59:47.,648 ThaliTest[1036:788198] client relay: 0x16e1dc60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1ad9c980 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 14:59:47.649 Tha,liTest[1036:788198] client session: socket closed: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:47.649 ThaliTest[1036:788198] client session: onLinkFailure: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:47.650 ThaliTest[1036:788198] client session: ,disconnect
2015-11-20 14:59:47.650 ThaliTest[1036:788198] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:47.653 ThaliTest[1036:788198] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:59:48.657Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:59:48.658Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:49.659 ThaliTest[1036:788320] jxcore: disconnect
2015-11-20 14:59:49.660 ThaliTest[1036:788320] jxcore: disconnect: fail
2015-11-20T13:59:49.661Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==,
2015-11-20T13:59:49.661Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT738.lFO7fw== with availability status: true
,2015-11-20T13:59:49.662Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T13:59:49.662Z SendDataConnector.js: do connect now
,2015-11-20 14:59:49.663 ThaliTest[1036:788320] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:49.664 ThaliTest[1036:788320] client session: connect
,2015-11-20 14:59:49.665 ThaliTest[1036:788320] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:51.260 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 14:59:51.946 ThaliTest[1036:789511] client session: connected
2015-11-20 14:59:51.946 ThaliTest[1036:789511] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:51.953 ThaliTest[1036:789593] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:51.954 ThaliTest[1036:789593] jxcore: connect: success
2015-11-20T13:59:51.956Z SendDataConnector.js: CLIENT connected to ,56185, error: null
,2015-11-20T13:59:51.957Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:59:51.960 ThaliTest[1036:788198] client: relay established
2015-11-20 14:59:51.961 ThaliTest[1036:788198] client: new accepted socket: 0x16e1dc60
,2015-11-20T13:59:51.971Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 14:59:52.199 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:52.199 ThaliTest[1036:788198] client: found peer: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20T13:59:56.573Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:06.582Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T14:00:06.583Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T14:00:06.585Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20 15:00:06.585 ThaliTest[1036:788198] client: socket closed
2015-11-20T14:00:06.586Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 15:00:06.586 ThaliT,est[1036:788198] client relay: socket disconnected
,2015-11-20 15:00:06.587 ThaliTest[1036:788198] client relay: 0x16e1dc60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1a918ac0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11,-20 15:00:06.588 ThaliTest[1036:788198] client session: socket closed: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:06.588 ThaliTest[1036:788198] client session: onLinkFailure: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:06.589 ThaliTest[1036:788198] client session: disconnect
2015-11-20 15:00:06.589 ThaliTest[1036:788198] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:06.591 ThaliTest[1036:788198] client session: fireCo,nnectionErrorEvent: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:07.587Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:07.587Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:08.595 ThaliTest[1036:788320] jxcore: disconnect
2015-11-20 15:00:08.596 ThaliTest[1036:788320] jxcore: disconnect: fail
2015-11-20T14:00:08.597Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==,
2015-11-20T14:00:08.597Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT738.lFO7fw== with availability status: true
2015-11-20T14:00:08.597Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:08.598Z SendDataConnector.js: do connect now
2015-11-20 15:00:08.599 ThaliTest[1036:788320] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:08.600 ThaliTest[1036:788320] client session: connect
,2015-11-20 15:00:08.601 ThaliTest[1036:788320] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:11.329 ThaliTest[1036:789593] client session: connected
2015-11-20 15:00:11.330 ThaliTest[1036:789593] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:11.337 ThaliTest[1036:789511] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:11.338 ThaliTest[1036:789511] jxcore: connect: success
2015-11-20T14:00:11.340Z SendDataConnector.js: CLIENT connected to ,56188, error: null
2015-11-20T14:00:11.340Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 15:00:11.344 ThaliTest[1036:788198] client: relay established
2015-11-20 15:00:11.344 ThaliTest[1036:788198] client: new accepted socket: 0x16e1dc60
,2015-11-20T14:00:11.356Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T14:00:15.986Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:22.374 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:00:25.185 ThaliTest[1036:788198] client: found peer: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 15:00:25.186 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:25.989Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T14:00:25.990Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T14:00:25.991Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T14:00:25.992Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 15:00:25.992 ThaliTest[1036:788198] client: socket closed
,2015-11-20 15:00:25.993 ThaliTest[1036:788198] client relay: socket disconnected
2015-11-20 15:00:25.994 ThaliTest[1036:788198] client relay: 0x16e1dc60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" U,serInfo=0x1aade390 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 15:00:25.994 ThaliTest[1036:788198] client session: socket closed: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:25.995 ThaliTest[1036:788198] client session: onLinkFa,ilure: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:25.996 ThaliTest[1036:788198] client session: disconnect
2015-11-20 15:00:25.996 ThaliTest[1036:788198] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:25.998 ThaliT,est[1036:788198] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:26.996Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:26.997Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:28.009 ThaliTest[1036:788320] jxcore: disconnect
2015-11-20 15:00:28.010 ThaliTest[1036:788320] jxcore: disconnect: fail
2015-11-20T14:00:28.011Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==,
2015-11-20T14:00:28.011Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT738.lFO7fw== with availability status: true
2015-11-20T14:00:28.011Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:28.012Z SendDataConnector.js: do connect now
,2015-11-20 15:00:28.013 ThaliTest[1036:788320] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:28.014 ThaliTest[1036:788320] client session: connect
2015-11-20 15:00:28.015 ThaliTest[1036:788320] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:32.821 ThaliTest[1036:789536] client session: connected
2015-11-20 15:00:32.822 ThaliTest[1036:789536] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:32.826 ThaliTest[1036:789536] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:32.827 ThaliTest[1036:789536] jxcore: connect: success
,2015-11-20T14:00:32.829Z SendDataConnector.js: CLIENT connected to 56192, error: null
,2015-11-20T14:00:32.830Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 15:00:32.834 ThaliTest[1036:788198] client: relay established
2015-11-20 15:00:32.834 ThaliTest[1036:788198] client: new accepted socket: 0x1af88760
,2015-11-20T14:00:32.844Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T14:00:37.472Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:47.473Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T14:00:47.473Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T14:00:47.475Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20T14:00:47.475Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 15:00:47.475 ThaliTest[1036:788198] client: socket closed
2015-11-20 15:00:47.476 ThaliT,est[1036:788198] client relay: socket disconnected
2015-11-20 15:00:47.476 ThaliTest[1036:788198] client relay: 0x1af88760 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1aade390 {NSLocalize,dDescription=Socket closed by remote peer} 
,2015-11-20 15:00:47.477 ThaliTest[1036:788198] client session: socket closed: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:47.477 ThaliTest[1036:788198] client session: onLinkFailure: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:47.478 ThaliTest[10,36:788198] client session: disconnect
,2015-11-20 15:00:47.479 ThaliTest[1036:788198] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:47.480 ThaliTest[1036:788198] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:48.480Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:48.480Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:49.483 ThaliTest[1036:788320] jxcore: disconnect
2015-11-20 15:00:49.484 ThaliTest[1036:788320] jxcore: disconnect: fail
2015-11-20T14:00:49.484Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==,
2015-11-20T14:00:49.485Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT738.lFO7fw== with availability status: true
2015-11-20T14:00:49.485Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:49.485Z SendDataConnector.js: do connect now
2015-11-20 15:00:49.486 ThaliTest[1036:788320] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:49.488 ThaliTest[1036:788320] client session: connect
,2015-11-20 15:00:49.489 ThaliTest[1036:788320] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:51.260 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:00:51.283 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:51.284 ThaliTest[1036:788198] client: found peer: Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 15:00:52.504 ThaliTest[1036:789511] client session: connected
2015-11-20 15:00:52.504 ThaliTest[1036:789511] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:52.510 ThaliTest[1036:789511] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:52.511 ThaliTest[1036:789511] jxcore: connect: success
2015-11-20T14:00:52.512Z SendDataConnector.js: CLIENT connected to 56195, error: null
2015-11-20T14:00:52.512Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 15:00:52.518 ThaliTest[1036:788198] client: relay established
2015-11-20 15:00:52.518 ThaliTest[1036:788198] client: new accepted socket: 0x1af88760
,2015-11-20T14:00:52.530Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T14:00:57.129Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:01:07.132Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T14:01:07.133Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T14:01:07.135Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T14:01:07.135Z SendDataConnector.js: Stop data retrieving timer
,2015-11-20 15:01:07.137 ThaliTest[1036:788320] jxcore: disconnect
2015-11-20 15:01:07.137 ThaliTest[1036:788320] client session: disconnectFromPeer: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:01:07.138 ThaliTest[1036:788320] client session: disconnect,
2015-11-20 15:01:07.139 ThaliTest[1036:788320] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:01:07.622 ThaliTest[1036:788320] jxcore: disconnect: success
2015-11-20T14:01:07.624Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==
---- round done--------
2015-11-20T14:01:07.625Z SendDataConn,ector.js: ----------------- closeClientSocket
,2015-11-20 15:01:12.581 ThaliTest[1036:788198] client: lost peer: Apple-IpadAir2-1_PT9530.n+0V8A==
2015-11-20 15:01:12.581 ThaliTest[1036:788198] client session: onPeerLost: Apple-IpadAir2-1_PT9530.n+0V8A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9530.n+0V8A==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 15:01:21.260 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:01:21.368 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:01:51.260 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:01:51.277 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:02:21.258 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:02:21.277 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:02:51.257 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:02:51.278 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:03:21.258 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:03:21.277 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:03:51.258 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:03:51.273 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:04:21.258 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:04:21.279 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:04:51.258 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:04:51.275 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:05:21.256 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:05:21.273 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:05:51.257 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:05:51.277 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:06:21.256 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:06:21.276 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:06:51.256 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:06:51.274 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:07:21.256 ThaliTest[1036:788198] multipeer session: restart
,2015-11-20 15:07:21.275 ThaliTest[1036:788198] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:07:51.255 ThaliTest[1036:788198] multipeer session: restart
2015-11-20 15:07:51.261 ThaliTest[1036:788198] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Firs,t throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0x15693 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of typ,e NSException
,* thread #1: tid = 0xc06e6, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x00015692 ThaliTest`main + 50

```
