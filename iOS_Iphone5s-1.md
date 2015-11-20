#### Test 513350289df1748_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350289df1748/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5C9BA89D-B4C0-40E7-ACA4-171694E9296A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5C9BA89D-B4C0-40E7-ACA4-171694E9296A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350289df1748/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350289df1748/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C603163F-5886-4399-AD05-29FE9D606944/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51321"
,(lldb)     command script import "/tmp/5C9BA89D-B4C0-40E7-ACA4-171694E9296A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 13:37:24.882 ThaliTest[1024:781290] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/248DC8E4-BE44-4258-B5BE-C872D913CF6C/Library/Cookies/Cookies.binarycookies
,2015-11-20 13:37:25.306 ThaliTest[1024:781290] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 13:37:25.307 ThaliTest[1024:781290] Multi-tasking -> Device: YES, App: YES
,2015-11-20 13:37:25.316 ThaliTest[1024:781290] Unlimited access to network resources
,2015-11-20 13:37:25.324 ThaliTest[1024:781290] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 13:37:29.176 ThaliTest[1024:781290] Resetting plugins due to page load.
,2015-11-20 13:37:29.658 ThaliTest[1024:781290] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/C603163F-5886-4399-AD05-29FE9D606944/ThaliTest.app/www/index.html
,2015-11-20 13:37:29.815 ThaliTest[1024:781290] JXcore Cordova plugin initializing
2015-11-20 13:37:29.816 ThaliTest[1024:781408] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT7169
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
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
-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
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
serverPort is 56010
2015-11-20 13:46:16.756 ThaliTest[1024:781408] jxcore: startBroadcasting
,2015-11-20 13:46:16.771 ThaliTest[1024:781408] server: starting Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:16.773 ThaliTest[1024:781408] multipeer session: start timer: 0x1b68e5a0
2015-11-20 13:46:16.773 ThaliTest[1024:781408] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT7169
2015-11-20 13:46:16.774 ThaliTest[1024:781408] jxcore: s,tartBroadcasting: success
StartBroadcasting started ok
,2015-11-20T12:46:16.777Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-20 13:46:16.793 ThaliTest[1024:781290] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:46:16.806Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:46:16.808Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:46:17.165 ThaliTest[1024:781290] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:46:17.811 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:46:17.812 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:46:17.813Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg=,=
,2015-11-20T12:46:17.813Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5s-1_PT497.PdI1bg== with availability status: true
,2015-11-20T12:46:17.815Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:46:17.816Z SendDataConnector.js: do connect now
,2015-11-20 13:46:17.817 ThaliTest[1024:781408] jxcore: connect Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:46:17.818 ThaliTest[1024:781408] client session: connect
2015-11-20 13:46:17.818 ThaliTest[1024:781408] client session: stateChange:0->1 Apple-Ip,hone5s-1_PT497.PdI1bg==
,2015-11-20 13:46:17.872 ThaliTest[1024:781290] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6611.klJDeA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:46:17.966 ThaliTest[1024:781290] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT545.qwwthQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tru,e
,2015-11-20 13:46:18.177 ThaliTest[1024:781290] multipeer session: reset timer
2015-11-20 13:46:18.178 ThaliTest[1024:781290] multipeer session: stop timer
2015-11-20 13:46:18.178 ThaliTest[1024:781290] multipeer session: start timer: 0x1b68e5a0
2015-11-,20 13:46:18.179 ThaliTest[1024:781290] server session: connect
2015-11-20 13:46:18.179 ThaliTest[1024:781290] server session: stateChange:0->1 Apple-Iphone5-1_PT6611
,2015-11-20 13:46:18.194 ThaliTest[1024:781290] server: accepting invitation Apple-Iphone5-1_PT6611
,2015-11-20 13:46:18.547 ThaliTest[1024:781290] multipeer session: reset timer
2015-11-20 13:46:18.548 ThaliTest[1024:781290] multipeer session: stop timer
2015-11-20 13:46:18.548 ThaliTest[1024:781290] multipeer session: start timer: 0x1b68e5a0
2015-11-,20 13:46:18.549 ThaliTest[1024:781290] server session: connect
2015-11-20 13:46:18.549 ThaliTest[1024:781290] server session: stateChange:0->1 Apple-Iphone6-1_PT8859
2015-11-20 13:46:18.565 ThaliTest[1024:781290] server: accepting invitation Apple-Iphone,6-1_PT8859
,2015-11-20 13:46:20.617 ThaliTest[1024:782114] server session: connected
2015-11-20 13:46:20.619 ThaliTest[1024:782114] server session: stateChange:1->2 Apple-Iphone5-1_PT6611
,2015-11-20 13:46:20.628 ThaliTest[1024:781290] server relay: connected (to port: 56010)
,2015-11-20T12:46:20.636Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:46:20.738 ThaliTest[1024:782114] server session: connected
2015-11-20 13:46:20.739 ThaliTest[1024:782114] server session: stateChange:1->2 Apple-Iphone6-1_PT8859
,2015-11-20T12:46:20.750Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:46:20.751 ThaliTest[1024:781290] server relay: connected (to port: 56010)
,2015-11-20T12:46:25.239Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-11-20T12:46:25.256Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-11-20T12:46:25.276Z SendDataTCPServer.js: TCP/IP server has received 67606 bytes of data
,2015-11-20T12:46:25.295Z SendDataTCPServer.js: TCP/IP server has received 113738 bytes of data
,2015-11-20T12:46:25.311Z SendDataTCPServer.js: TCP/IP server has received 122640 bytes of data
,2015-11-20T12:46:25.635Z SendDataTCPServer.js: TCP/IP server has received 133590 bytes of data
,2015-11-20T12:46:25.652Z SendDataTCPServer.js: TCP/IP server has received 140160 bytes of data
,2015-11-20T12:46:25.693Z SendDataTCPServer.js: TCP/IP server has received 162060 bytes of data
,2015-11-20T12:46:25.710Z SendDataTCPServer.js: TCP/IP server has received 179580 bytes of data
,2015-11-20T12:46:25.725Z SendDataTCPServer.js: TCP/IP server has received 199290 bytes of data
,2015-11-20T12:46:25.741Z SendDataTCPServer.js: TCP/IP server has received 229950 bytes of data
,2015-11-20T12:46:25.757Z SendDataTCPServer.js: TCP/IP server has received 284700 bytes of data
,2015-11-20T12:46:25.775Z SendDataTCPServer.js: TCP/IP server has received 297556 bytes of data
,2015-11-20T12:46:25.791Z SendDataTCPServer.js: TCP/IP server has received 319740 bytes of data
,2015-11-20T12:46:25.807Z SendDataTCPServer.js: TCP/IP server has received 343830 bytes of data
,2015-11-20T12:46:25.823Z SendDataTCPServer.js: TCP/IP server has received 365730 bytes of data
,2015-11-20T12:46:25.839Z SendDataTCPServer.js: TCP/IP server has received 389820 bytes of data
,2015-11-20T12:46:25.854Z SendDataTCPServer.js: TCP/IP server has received 422386 bytes of data
,2015-11-20T12:46:25.871Z SendDataTCPServer.js: TCP/IP server has received 453330 bytes of data
,2015-11-20T12:46:25.887Z SendDataTCPServer.js: TCP/IP server has received 486180 bytes of data
,2015-11-20T12:46:25.903Z SendDataTCPServer.js: TCP/IP server has received 519030 bytes of data
,2015-11-20T12:46:25.918Z SendDataTCPServer.js: TCP/IP server has received 556118 bytes of data
,2015-11-20T12:46:25.932Z SendDataTCPServer.js: TCP/IP server has received 582540 bytes of data
,2015-11-20T12:46:25.946Z SendDataTCPServer.js: TCP/IP server has received 619770 bytes of data
,2015-11-20T12:46:25.961Z SendDataTCPServer.js: TCP/IP server has received 672330 bytes of data
,2015-11-20T12:46:25.976Z SendDataTCPServer.js: TCP/IP server has received 724890 bytes of data
,2015-11-20T12:46:26.157Z SendDataTCPServer.js: TCP/IP server has received 733650 bytes of data
,2015-11-20T12:46:26.171Z SendDataTCPServer.js: TCP/IP server has received 744600 bytes of data
,2015-11-20T12:46:26.187Z SendDataTCPServer.js: TCP/IP server has received 755550 bytes of data
,2015-11-20T12:46:26.202Z SendDataTCPServer.js: TCP/IP server has received 766500 bytes of data
,2015-11-20T12:46:26.217Z SendDataTCPServer.js: TCP/IP server has received 779640 bytes of data
,2015-11-20T12:46:26.235Z SendDataTCPServer.js: TCP/IP server has received 810158 bytes of data
,2015-11-20T12:46:26.249Z SendDataTCPServer.js: TCP/IP server has received 827820 bytes of data
,2015-11-20T12:46:26.262Z SendDataTCPServer.js: TCP/IP server has received 849720 bytes of data
,2015-11-20T12:46:26.277Z SendDataTCPServer.js: TCP/IP server has received 865050 bytes of data
,2015-11-20T12:46:26.291Z SendDataTCPServer.js: TCP/IP server has received 889140 bytes of data
,2015-11-20T12:46:26.304Z SendDataTCPServer.js: TCP/IP server has received 928560 bytes of data
,2015-11-20T12:46:26.321Z SendDataTCPServer.js: TCP/IP server has received 949892 bytes of data
,2015-11-20T12:46:26.337Z SendDataTCPServer.js: TCP/IP server has received 998640 bytes of data
,2015-11-20T12:46:26.353Z SendDataTCPServer.js: TCP/IP server has received 1033680 bytes of data
,2015-11-20T12:46:26.369Z SendDataTCPServer.js: TCP/IP server has received 1064198 bytes of data
,2015-11-20T12:46:26.383Z SendDataTCPServer.js: TCP/IP server has received 1099380 bytes of data
,2015-11-20T12:46:26.396Z SendDataTCPServer.js: TCP/IP server has received 1127850 bytes of data
,2015-11-20T12:46:26.411Z SendDataTCPServer.js: TCP/IP server has received 1153988 bytes of data
,2015-11-20T12:46:26.424Z SendDataTCPServer.js: TCP/IP server has received 1193550 bytes of data
,2015-11-20T12:46:26.438Z SendDataTCPServer.js: TCP/IP server has received 1235160 bytes of data
,2015-11-20T12:46:26.455Z SendDataTCPServer.js: TCP/IP server has received 1289910 bytes of data
,2015-11-20T12:46:26.469Z SendDataTCPServer.js: TCP/IP server has received 1329330 bytes of data
,2015-11-20T12:46:26.484Z SendDataTCPServer.js: TCP/IP server has received 1390650 bytes of data
,2015-11-20T12:46:26.500Z SendDataTCPServer.js: TCP/IP server has received 1395030 bytes of data
,2015-11-20T12:46:26.689Z SendDataTCPServer.js: TCP/IP server has received 1403790 bytes of data
,2015-11-20T12:46:26.705Z SendDataTCPServer.js: TCP/IP server has received 1416788 bytes of data
,2015-11-20T12:46:26.721Z SendDataTCPServer.js: TCP/IP server has received 1425690 bytes of data
,2015-11-20T12:46:26.734Z SendDataTCPServer.js: TCP/IP server has received 1443210 bytes of data
,2015-11-20T12:46:26.748Z SendDataTCPServer.js: TCP/IP server has received 1460730 bytes of data
,2015-11-20T12:46:26.763Z SendDataTCPServer.js: TCP/IP server has received 1493580 bytes of data
,2015-11-20T12:46:26.779Z SendDataTCPServer.js: TCP/IP server has received 1519860 bytes of data
,2015-11-20T12:46:26.793Z SendDataTCPServer.js: TCP/IP server has received 1539570 bytes of data
,2015-11-20T12:46:26.807Z SendDataTCPServer.js: TCP/IP server has received 1559280 bytes of data
,2015-11-20T12:46:26.822Z SendDataTCPServer.js: TCP/IP server has received 1578990 bytes of data
,2015-11-20T12:46:26.838Z SendDataTCPServer.js: TCP/IP server has received 1611840 bytes of data
,2015-11-20T12:46:26.851Z SendDataTCPServer.js: TCP/IP server has received 1646880 bytes of data
,2015-11-20T12:46:26.866Z SendDataTCPServer.js: TCP/IP server has received 1701630 bytes of data
,2015-11-20T12:46:26.881Z SendDataTCPServer.js: TCP/IP server has received 1725720 bytes of data
,2015-11-20T12:46:26.895Z SendDataTCPServer.js: TCP/IP server has received 1732290 bytes of data
,2015-11-20T12:46:26.957Z SendDataTCPServer.js: TCP/IP server has received 1738718 bytes of data
,2015-11-20T12:46:26.972Z SendDataTCPServer.js: TCP/IP server has received 1756380 bytes of data
,2015-11-20T12:46:26.987Z SendDataTCPServer.js: TCP/IP server has received 1780470 bytes of data
,2015-11-20T12:46:27.002Z SendDataTCPServer.js: TCP/IP server has received 1802370 bytes of data
,2015-11-20T12:46:27.017Z SendDataTCPServer.js: TCP/IP server has received 1838890 bytes of data
,2015-11-20T12:46:27.032Z SendDataTCPServer.js: TCP/IP server has received 1872450 bytes of data
,2015-11-20T12:46:27.209Z SendDataTCPServer.js: TCP/IP server has received 1887780 bytes of data
,2015-11-20T12:46:27.224Z SendDataTCPServer.js: TCP/IP server has received 1900920 bytes of data
,2015-11-20T12:46:27.239Z SendDataTCPServer.js: TCP/IP server has received 1914060 bytes of data
,2015-11-20T12:46:27.258Z SendDataTCPServer.js: TCP/IP server has received 1935960 bytes of data
,2015-11-20T12:46:27.276Z SendDataTCPServer.js: TCP/IP server has received 1960050 bytes of data
,2015-11-20T12:46:27.291Z SendDataTCPServer.js: TCP/IP server has received 1973190 bytes of data
,2015-11-20T12:46:27.307Z SendDataTCPServer.js: TCP/IP server has received 1999328 bytes of data
,2015-11-20T12:46:27.323Z SendDataTCPServer.js: TCP/IP server has received 2025750 bytes of data
,2015-11-20T12:46:27.339Z SendDataTCPServer.js: TCP/IP server has received 2052030 bytes of data
,2015-11-20T12:46:27.355Z SendDataTCPServer.js: TCP/IP server has received 2073930 bytes of data
,2015-11-20T12:46:27.371Z SendDataTCPServer.js: TCP/IP server has received 2100210 bytes of data
,2015-11-20T12:46:27.386Z SendDataTCPServer.js: TCP/IP server has received 2122110 bytes of data
,2015-11-20T12:46:27.402Z SendDataTCPServer.js: TCP/IP server has received 2150580 bytes of data
,2015-11-20T12:46:27.416Z SendDataTCPServer.js: TCP/IP server has received 2181240 bytes of data
,2015-11-20T12:46:27.431Z SendDataTCPServer.js: TCP/IP server has received 2209568 bytes of data
,2015-11-20T12:46:27.444Z SendDataTCPServer.js: TCP/IP server has received 2235990 bytes of data
,2015-11-20T12:46:27.457Z SendDataTCPServer.js: TCP/IP server has received 2257890 bytes of data
,2015-11-20T12:46:27.469Z SendDataTCPServer.js: TCP/IP server has received 2284170 bytes of data
,2015-11-20T12:46:27.484Z SendDataTCPServer.js: TCP/IP server has received 2312640 bytes of data
,2015-11-20T12:46:27.497Z SendDataTCPServer.js: TCP/IP server has received 2345490 bytes of data
,2015-11-20T12:46:27.510Z SendDataTCPServer.js: TCP/IP server has received 2391480 bytes of data
,2015-11-20T12:46:27.523Z SendDataTCPServer.js: TCP/IP server has received 2448420 bytes of data
,2015-11-20T12:46:27.537Z SendDataTCPServer.js: TCP/IP server has received 2468130 bytes of data
,2015-11-20T12:46:27.722Z SendDataTCPServer.js: TCP/IP server has received 2470320 bytes of data
,2015-11-20T12:46:27.737Z SendDataTCPServer.js: TCP/IP server has received 2479080 bytes of data
,2015-11-20T12:46:27.751Z SendDataTCPServer.js: TCP/IP server has received 2494410 bytes of data
,2015-11-20T12:46:27.768Z SendDataTCPServer.js: TCP/IP server has received 2511930 bytes of data
,2015-11-20T12:46:27.784Z SendDataTCPServer.js: TCP/IP server has received 2531640 bytes of data
,2015-11-20T12:46:27.800Z SendDataTCPServer.js: TCP/IP server has received 2544780 bytes of data
,2015-11-20T12:46:27.840Z SendDataTCPServer.js: TCP/IP server has received 2549160 bytes of data
,2015-11-20T12:46:27.859Z SendDataTCPServer.js: TCP/IP server has received 2566680 bytes of data
,2015-11-20T12:46:27.879Z SendDataTCPServer.js: TCP/IP server has received 2590770 bytes of data
,2015-11-20T12:46:27.894Z SendDataTCPServer.js: TCP/IP server has received 2610480 bytes of data
,2015-11-20T12:46:27.912Z SendDataTCPServer.js: TCP/IP server has received 2634570 bytes of data
,2015-11-20T12:46:27.931Z SendDataTCPServer.js: TCP/IP server has received 2660850 bytes of data
,2015-11-20T12:46:27.948Z SendDataTCPServer.js: TCP/IP server has received 2687130 bytes of data
,2015-11-20T12:46:27.964Z SendDataTCPServer.js: TCP/IP server has received 2715600 bytes of data
,2015-11-20T12:46:27.978Z SendDataTCPServer.js: TCP/IP server has received 2744070 bytes of data
,2015-11-20T12:46:27.994Z SendDataTCPServer.js: TCP/IP server has received 2770350 bytes of data
,2015-11-20T12:46:28.009Z SendDataTCPServer.js: TCP/IP server has received 2792250 bytes of data
,2015-11-20T12:46:28.024Z SendDataTCPServer.js: TCP/IP server has received 2818530 bytes of data
,2015-11-20T12:46:28.040Z SendDataTCPServer.js: TCP/IP server has received 2827290 bytes of data
,2015-11-20T12:46:28.255Z SendDataTCPServer.js: TCP/IP server has received 2833860 bytes of data
,2015-11-20T12:46:28.269Z SendDataTCPServer.js: TCP/IP server has received 2851380 bytes of data
,2015-11-20T12:46:28.289Z SendDataTCPServer.js: TCP/IP server has received 2873280 bytes of data
,2015-11-20T12:46:28.310Z SendDataTCPServer.js: TCP/IP server has received 2888610 bytes of data
,2015-11-20T12:46:28.328Z SendDataTCPServer.js: TCP/IP server has received 2908320 bytes of data
,2015-11-20T12:46:28.346Z SendDataTCPServer.js: TCP/IP server has received 2930220 bytes of data
,2015-11-20T12:46:28.362Z SendDataTCPServer.js: TCP/IP server has received 2956500 bytes of data
,2015-11-20T12:46:28.375Z SendDataTCPServer.js: TCP/IP server has received 2978400 bytes of data
,2015-11-20T12:46:28.390Z SendDataTCPServer.js: TCP/IP server has received 2995920 bytes of data
,2015-11-20T12:46:28.407Z SendDataTCPServer.js: TCP/IP server has received 3013440 bytes of data
,2015-11-20T12:46:28.421Z SendDataTCPServer.js: TCP/IP server has received 3033150 bytes of data
,2015-11-20T12:46:28.436Z SendDataTCPServer.js: TCP/IP server has received 3068190 bytes of data
,2015-11-20T12:46:28.452Z SendDataTCPServer.js: TCP/IP server has received 3094470 bytes of data
,2015-11-20T12:46:28.467Z SendDataTCPServer.js: TCP/IP server has received 3111990 bytes of data
,2015-11-20T12:46:28.507Z SendDataTCPServer.js: TCP/IP server has received 3118560 bytes of data
,2015-11-20T12:46:28.522Z SendDataTCPServer.js: TCP/IP server has received 3144840 bytes of data
,2015-11-20T12:46:28.538Z SendDataTCPServer.js: TCP/IP server has received 3173310 bytes of data
,2015-11-20T12:46:28.554Z SendDataTCPServer.js: TCP/IP server has received 3203970 bytes of data
,2015-11-20T12:46:28.569Z SendDataTCPServer.js: TCP/IP server has received 3239010 bytes of data
,2015-11-20T12:46:28.584Z SendDataTCPServer.js: TCP/IP server has received 3254340 bytes of data
,2015-11-20T12:46:28.779Z SendDataTCPServer.js: TCP/IP server has received 3260910 bytes of data
,2015-11-20T12:46:28.795Z SendDataTCPServer.js: TCP/IP server has received 3276240 bytes of data
,2015-11-20T12:46:28.811Z SendDataTCPServer.js: TCP/IP server has received 3293760 bytes of data
,2015-11-20T12:46:28.824Z SendDataTCPServer.js: TCP/IP server has received 3304710 bytes of data
,2015-11-20T12:46:28.840Z SendDataTCPServer.js: TCP/IP server has received 3326610 bytes of data
,2015-11-20T12:46:28.858Z SendDataTCPServer.js: TCP/IP server has received 3344130 bytes of data
,2015-11-20T12:46:28.873Z SendDataTCPServer.js: TCP/IP server has received 3363840 bytes of data
,2015-11-20T12:46:28.888Z SendDataTCPServer.js: TCP/IP server has received 3394500 bytes of data
,2015-11-20T12:46:28.905Z SendDataTCPServer.js: TCP/IP server has received 3422970 bytes of data
,2015-11-20T12:46:28.920Z SendDataTCPServer.js: TCP/IP server has received 3433920 bytes of data
,2015-11-20T12:46:28.936Z SendDataTCPServer.js: TCP/IP server has received 3438300 bytes of data
,2015-11-20T12:46:28.950Z SendDataTCPServer.js: TCP/IP server has received 3461538 bytes of data
,2015-11-20T12:46:28.966Z SendDataTCPServer.js: TCP/IP server has received 3504000 bytes of data
,2015-11-20T12:46:28.983Z SendDataTCPServer.js: TCP/IP server has received 3532470 bytes of data
,2015-11-20T12:46:28.998Z SendDataTCPServer.js: TCP/IP server has received 3563130 bytes of data
,2015-11-20T12:46:29.037Z SendDataTCPServer.js: TCP/IP server has received 3569700 bytes of data
,2015-11-20T12:46:29.052Z SendDataTCPServer.js: TCP/IP server has received 3598170 bytes of data
,2015-11-20T12:46:29.071Z SendDataTCPServer.js: TCP/IP server has received 3628830 bytes of data
,2015-11-20T12:46:29.087Z SendDataTCPServer.js: TCP/IP server has received 3635400 bytes of data
,2015-11-20T12:46:29.300Z SendDataTCPServer.js: TCP/IP server has received 3639638 bytes of data
,2015-11-20T12:46:29.316Z SendDataTCPServer.js: TCP/IP server has received 3657300 bytes of data
,2015-11-20T12:46:29.334Z SendDataTCPServer.js: TCP/IP server has received 3674820 bytes of data
,2015-11-20T12:46:29.351Z SendDataTCPServer.js: TCP/IP server has received 3694530 bytes of data
,2015-11-20T12:46:29.367Z SendDataTCPServer.js: TCP/IP server has received 3712050 bytes of data
,2015-11-20T12:46:29.385Z SendDataTCPServer.js: TCP/IP server has received 3733950 bytes of data
,2015-11-20T12:46:29.398Z SendDataTCPServer.js: TCP/IP server has received 3753660 bytes of data
,2015-11-20T12:46:29.413Z SendDataTCPServer.js: TCP/IP server has received 3779940 bytes of data
,2015-11-20T12:46:29.428Z SendDataTCPServer.js: TCP/IP server has received 3797460 bytes of data
,2015-11-20T12:46:29.445Z SendDataTCPServer.js: TCP/IP server has received 3821550 bytes of data
,2015-11-20T12:46:29.461Z SendDataTCPServer.js: TCP/IP server has received 3847830 bytes of data
,2015-11-20T12:46:29.490Z SendDataTCPServer.js: TCP/IP server has received 3854400 bytes of data
,2015-11-20T12:46:29.504Z SendDataTCPServer.js: TCP/IP server has received 3876300 bytes of data
,2015-11-20T12:46:29.521Z SendDataTCPServer.js: TCP/IP server has received 3913530 bytes of data
,2015-11-20T12:46:29.561Z SendDataTCPServer.js: TCP/IP server has received 3915720 bytes of data
,2015-11-20T12:46:29.577Z SendDataTCPServer.js: TCP/IP server has received 3931050 bytes of data
,2015-11-20T12:46:29.590Z SendDataTCPServer.js: TCP/IP server has received 3944190 bytes of data
,2015-11-20T12:46:29.604Z SendDataTCPServer.js: TCP/IP server has received 3968280 bytes of data
,2015-11-20T12:46:29.620Z SendDataTCPServer.js: TCP/IP server has received 3972660 bytes of data
,2015-11-20T12:46:29.831Z SendDataTCPServer.js: TCP/IP server has received 3990180 bytes of data
,2015-11-20T12:46:29.847Z SendDataTCPServer.js: TCP/IP server has received 4009890 bytes of data
,2015-11-20T12:46:29.876Z SendDataTCPServer.js: TCP/IP server has received 4042740 bytes of data
,2015-11-20T12:46:29.893Z SendDataTCPServer.js: TCP/IP server has received 4055880 bytes of data
,2015-11-20T12:46:29.912Z SendDataTCPServer.js: TCP/IP server has received 4084350 bytes of data
,2015-11-20T12:46:29.932Z SendDataTCPServer.js: TCP/IP server has received 4121580 bytes of data
,2015-11-20T12:46:29.947Z SendDataTCPServer.js: TCP/IP server has received 4143480 bytes of data
,2015-11-20T12:46:29.964Z SendDataTCPServer.js: TCP/IP server has received 4165380 bytes of data
,2015-11-20T12:46:29.979Z SendDataTCPServer.js: TCP/IP server has received 4189470 bytes of data
,2015-11-20T12:46:29.993Z SendDataTCPServer.js: TCP/IP server has received 4217940 bytes of data
,2015-11-20T12:46:30.011Z SendDataTCPServer.js: TCP/IP server has received 4242030 bytes of data
,2015-11-20T12:46:30.028Z SendDataTCPServer.js: TCP/IP server has received 4268310 bytes of data
,2015-11-20T12:46:30.044Z SendDataTCPServer.js: TCP/IP server has received 4307588 bytes of data
,2015-11-20T12:46:30.061Z SendDataTCPServer.js: TCP/IP server has received 4344960 bytes of data
,2015-11-20T12:46:30.076Z SendDataTCPServer.js: TCP/IP server has received 4384380 bytes of data
,2015-11-20T12:46:30.090Z SendDataTCPServer.js: TCP/IP server has received 4410660 bytes of data
,2015-11-20T12:46:30.107Z SendDataTCPServer.js: TCP/IP server has received 4450080 bytes of data
,2015-11-20T12:46:30.124Z SendDataTCPServer.js: TCP/IP server has received 4491690 bytes of data
,2015-11-20T12:46:30.138Z SendDataTCPServer.js: TCP/IP server has received 4531110 bytes of data
,2015-11-20T12:46:30.153Z SendDataTCPServer.js: TCP/IP server has received 4546440 bytes of data
,2015-11-20T12:46:30.385Z SendDataTCPServer.js: TCP/IP server has received 4555200 bytes of data
,2015-11-20T12:46:30.404Z SendDataTCPServer.js: TCP/IP server has received 4566150 bytes of data
,2015-11-20T12:46:30.419Z SendDataTCPServer.js: TCP/IP server has received 4574910 bytes of data
,2015-11-20T12:46:30.433Z SendDataTCPServer.js: TCP/IP server has received 4588050 bytes of data
,2015-11-20T12:46:30.450Z SendDataTCPServer.js: TCP/IP server has received 4601190 bytes of data
,2015-11-20T12:46:30.470Z SendDataTCPServer.js: TCP/IP server has received 4620900 bytes of data
,2015-11-20T12:46:30.485Z SendDataTCPServer.js: TCP/IP server has received 4642658 bytes of data
,2015-11-20T12:46:30.503Z SendDataTCPServer.js: TCP/IP server has received 4673460 bytes of data
,2015-11-20T12:46:30.518Z SendDataTCPServer.js: TCP/IP server has received 4701930 bytes of data
,2015-11-20T12:46:30.534Z SendDataTCPServer.js: TCP/IP server has received 4726020 bytes of data
,2015-11-20T12:46:30.552Z SendDataTCPServer.js: TCP/IP server has received 4752300 bytes of data
,2015-11-20T12:46:30.567Z SendDataTCPServer.js: TCP/IP server has received 4769820 bytes of data
,2015-11-20T12:46:30.585Z SendDataTCPServer.js: TCP/IP server has received 4798290 bytes of data
,2015-11-20T12:46:30.600Z SendDataTCPServer.js: TCP/IP server has received 4828950 bytes of data
,2015-11-20T12:46:30.614Z SendDataTCPServer.js: TCP/IP server has received 4866180 bytes of data
,2015-11-20T12:46:30.631Z SendDataTCPServer.js: TCP/IP server has received 4912170 bytes of data
,2015-11-20T12:46:30.648Z SendDataTCPServer.js: TCP/IP server has received 4953780 bytes of data
,2015-11-20T12:46:30.661Z SendDataTCPServer.js: TCP/IP server has received 4993200 bytes of data
,2015-11-20T12:46:30.676Z SendDataTCPServer.js: TCP/IP server has received 5010720 bytes of data
,2015-11-20T12:46:30.915Z SendDataTCPServer.js: TCP/IP server has received 5021670 bytes of data
,2015-11-20T12:46:30.933Z SendDataTCPServer.js: TCP/IP server has received 5047950 bytes of data
,2015-11-20T12:46:30.949Z SendDataTCPServer.js: TCP/IP server has received 5052330 bytes of data
,2015-11-20T12:46:30.965Z SendDataTCPServer.js: TCP/IP server has received 5074230 bytes of data
,2015-11-20T12:46:30.988Z SendDataTCPServer.js: TCP/IP server has received 5085180 bytes of data
,2015-11-20T12:46:31.002Z SendDataTCPServer.js: TCP/IP server has received 5091750 bytes of data
,2015-11-20T12:46:31.017Z SendDataTCPServer.js: TCP/IP server has received 5104890 bytes of data
,2015-11-20T12:46:31.033Z SendDataTCPServer.js: TCP/IP server has received 5115840 bytes of data
,2015-11-20T12:46:31.046Z SendDataTCPServer.js: TCP/IP server has received 5128980 bytes of data
,2015-11-20T12:46:31.061Z SendDataTCPServer.js: TCP/IP server has received 5153070 bytes of data
,2015-11-20T12:46:31.079Z SendDataTCPServer.js: TCP/IP server has received 5188110 bytes of data
,2015-11-20T12:46:31.095Z SendDataTCPServer.js: TCP/IP server has received 5214390 bytes of data
,2015-11-20T12:46:31.109Z SendDataTCPServer.js: TCP/IP server has received 5242860 bytes of data
,2015-11-20T12:46:31.125Z SendDataTCPServer.js: TCP/IP server has received 5275710 bytes of data
,2015-11-20T12:46:31.141Z SendDataTCPServer.js: TCP/IP server has received 5286660 bytes of data
,2015-11-20T12:46:31.155Z SendDataTCPServer.js: TCP/IP server has received 5323890 bytes of data
,2015-11-20T12:46:31.170Z SendDataTCPServer.js: TCP/IP server has received 5337030 bytes of data
,2015-11-20T12:46:31.184Z SendDataTCPServer.js: TCP/IP server has received 5350170 bytes of data
,2015-11-20T12:46:31.197Z SendDataTCPServer.js: TCP/IP server has received 5358930 bytes of data
,2015-11-20T12:46:31.415Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-11-20T12:46:31.437Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-11-20T12:46:31.455Z SendDataTCPServer.js: TCP/IP server has received 26784 bytes of data
,2015-11-20T12:46:31.472Z SendDataTCPServer.js: TCP/IP server has received 41664 bytes of data
,2015-11-20T12:46:31.491Z SendDataTCPServer.js: TCP/IP server has received 49600 bytes of data
,2015-11-20T12:46:31.505Z SendDataTCPServer.js: TCP/IP server has received 58528 bytes of data
,2015-11-20T12:46:31.523Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-11-20T12:46:31.551Z SendDataTCPServer.js: TCP/IP server has received 68448 bytes of data
,2015-11-20T12:46:31.569Z SendDataTCPServer.js: TCP/IP server has received 80352 bytes of data
,2015-11-20T12:46:31.625Z SendDataTCPServer.js: TCP/IP server has received 90272 bytes of data
,2015-11-20T12:46:31.628Z SendDataTCPServer.js: TCP/IP server has received 5422440 bytes of data
,2015-11-20T12:46:31.659Z SendDataTCPServer.js: TCP/IP server has received 94240 bytes of data
,2015-11-20T12:46:31.664Z SendDataTCPServer.js: TCP/IP server has received 5485158 bytes of data
,2015-11-20T12:46:31.690Z SendDataTCPServer.js: TCP/IP server has received 112096 bytes of data
,2015-11-20T12:46:31.699Z SendDataTCPServer.js: TCP/IP server has received 5534130 bytes of data
,2015-11-20T12:46:31.724Z SendDataTCPServer.js: TCP/IP server has received 151776 bytes of data
,2015-11-20T12:46:31.737Z SendDataTCPServer.js: TCP/IP server has received 156736 bytes of data
,2015-11-20T12:46:31.944Z SendDataTCPServer.js: TCP/IP server has received 163680 bytes of data
,2015-11-20T12:46:31.961Z SendDataTCPServer.js: TCP/IP server has received 173600 bytes of data
,2015-11-20T12:46:31.978Z SendDataTCPServer.js: TCP/IP server has received 184512 bytes of data
,2015-11-20T12:46:31.993Z SendDataTCPServer.js: TCP/IP server has received 190464 bytes of data
,2015-11-20T12:46:32.010Z SendDataTCPServer.js: TCP/IP server has received 199392 bytes of data
,2015-11-20T12:46:32.024Z SendDataTCPServer.js: TCP/IP server has received 207328 bytes of data
,2015-11-20T12:46:32.043Z SendDataTCPServer.js: TCP/IP server has received 215264 bytes of data
,2015-11-20T12:46:32.057Z SendDataTCPServer.js: TCP/IP server has received 226176 bytes of data
,2015-11-20T12:46:32.073Z SendDataTCPServer.js: TCP/IP server has received 242048 bytes of data
,2015-11-20T12:46:32.088Z SendDataTCPServer.js: TCP/IP server has received 253952 bytes of data
,2015-11-20T12:46:32.103Z SendDataTCPServer.js: TCP/IP server has received 268832 bytes of data
,2015-11-20T12:46:32.118Z SendDataTCPServer.js: TCP/IP server has received 285696 bytes of data
,2015-11-20T12:46:32.132Z SendDataTCPServer.js: TCP/IP server has received 294624 bytes of data
,2015-11-20T12:46:32.147Z SendDataTCPServer.js: TCP/IP server has received 306528 bytes of data
,2015-11-20T12:46:32.152Z SendDataTCPServer.js: TCP/IP server has received 5538510 bytes of data
,2015-11-20T12:46:32.163Z SendDataTCPServer.js: TCP/IP server has received 318432 bytes of data
,2015-11-20T12:46:32.177Z SendDataTCPServer.js: TCP/IP server has received 342240 bytes of data
,2015-11-20T12:46:32.189Z SendDataTCPServer.js: TCP/IP server has received 359104 bytes of data
,2015-11-20T12:46:32.202Z SendDataTCPServer.js: TCP/IP server has received 368032 bytes of data
,2015-11-20T12:46:32.216Z SendDataTCPServer.js: TCP/IP server has received 377952 bytes of data
,2015-11-20T12:46:32.228Z SendDataTCPServer.js: TCP/IP server has received 386880 bytes of data
,2015-11-20T12:46:32.242Z SendDataTCPServer.js: TCP/IP server has received 407712 bytes of data
,2015-11-20T12:46:32.256Z SendDataTCPServer.js: TCP/IP server has received 417632 bytes of data
,2015-11-20T12:46:32.475Z SendDataTCPServer.js: TCP/IP server has received 5560410 bytes of data
2015-11-20T12:46:32.481Z SendDataTCPServer.js: TCP/IP server has received 424576 bytes of data
,2015-11-20T12:46:32.496Z SendDataTCPServer.js: TCP/IP server has received 5575740 bytes of data
,2015-11-20T12:46:32.499Z SendDataTCPServer.js: TCP/IP server has received 437472 bytes of data
,2015-11-20T12:46:32.517Z SendDataTCPServer.js: TCP/IP server has received 5586690 bytes of data
,2015-11-20T12:46:32.525Z SendDataTCPServer.js: TCP/IP server has received 445408 bytes of data
,2015-11-20T12:46:32.545Z SendDataTCPServer.js: TCP/IP server has received 5597640 bytes of data
2015-11-20T12:46:32.547Z SendDataTCPServer.js: TCP/IP server has received 446400 bytes of data
,2015-11-20T12:46:32.561Z SendDataTCPServer.js: TCP/IP server has received 5608590 bytes of data
2015-11-20T12:46:32.562Z SendDataTCPServer.js: TCP/IP server has received 457312 bytes of data
,2015-11-20T12:46:32.575Z SendDataTCPServer.js: TCP/IP server has received 5612970 bytes of data
,2015-11-20T12:46:32.577Z SendDataTCPServer.js: TCP/IP server has received 482112 bytes of data
,2015-11-20T12:46:32.590Z SendDataTCPServer.js: TCP/IP server has received 489056 bytes of data
,2015-11-20T12:46:32.606Z SendDataTCPServer.js: TCP/IP server has received 493024 bytes of data
,2015-11-20T12:46:32.608Z SendDataTCPServer.js: TCP/IP server has received 5652390 bytes of data
,2015-11-20T12:46:32.635Z SendDataTCPServer.js: TCP/IP server has received 509888 bytes of data
,2015-11-20T12:46:32.637Z SendDataTCPServer.js: TCP/IP server has received 5678670 bytes of data
,2015-11-20T12:46:32.653Z SendDataTCPServer.js: TCP/IP server has received 525760 bytes of data
,2015-11-20T12:46:32.667Z SendDataTCPServer.js: TCP/IP server has received 533696 bytes of data
,2015-11-20T12:46:32.681Z SendDataTCPServer.js: TCP/IP server has received 544608 bytes of data
,2015-11-20T12:46:32.710Z SendDataTCPServer.js: TCP/IP server has received 5702760 bytes of data
,2015-11-20T12:46:32.724Z SendDataTCPServer.js: TCP/IP server has received 5709330 bytes of data
,2015-11-20T12:46:32.725Z SendDataTCPServer.js: TCP/IP server has received 555520 bytes of data
,2015-11-20T12:46:32.737Z SendDataTCPServer.js: TCP/IP server has received 556512 bytes of data
,2015-11-20T12:46:33.062Z SendDataTCPServer.js: TCP/IP server has received 5720280 bytes of data
,2015-11-20T12:46:33.078Z SendDataTCPServer.js: TCP/IP server has received 5739990 bytes of data
,2015-11-20T12:46:33.095Z SendDataTCPServer.js: TCP/IP server has received 5750940 bytes of data
,2015-11-20T12:46:33.149Z SendDataTCPServer.js: TCP/IP server has received 567424 bytes of data
,2015-11-20T12:46:33.165Z SendDataTCPServer.js: TCP/IP server has received 572384 bytes of data
,2015-11-20T12:46:33.194Z SendDataTCPServer.js: TCP/IP server has received 5759558 bytes of data
,2015-11-20T12:46:33.208Z SendDataTCPServer.js: TCP/IP server has received 5772840 bytes of data
,2015-11-20T12:46:33.230Z SendDataTCPServer.js: TCP/IP server has received 5781600 bytes of data
,2015-11-20T12:46:33.250Z SendDataTCPServer.js: TCP/IP server has received 5790076 bytes of data
,2015-11-20T12:46:33.253Z SendDataTCPServer.js: TCP/IP server has received 577344 bytes of data
,2015-11-20T12:46:33.271Z SendDataTCPServer.js: TCP/IP server has received 5801310 bytes of data
,2015-11-20T12:46:33.273Z SendDataTCPServer.js: TCP/IP server has received 586272 bytes of data
,2015-11-20T12:46:33.291Z SendDataTCPServer.js: TCP/IP server has received 5814450 bytes of data
2015-11-20T12:46:33.293Z SendDataTCPServer.js: TCP/IP server has received 592224 bytes of data
,2015-11-20T12:46:33.308Z SendDataTCPServer.js: TCP/IP server has received 5836350 bytes of data
2015-11-20T12:46:33.311Z SendDataTCPServer.js: TCP/IP server has received 603136 bytes of data
,2015-11-20T12:46:33.328Z SendDataTCPServer.js: TCP/IP server has received 5858250 bytes of data
,2015-11-20T12:46:33.332Z SendDataTCPServer.js: TCP/IP server has received 618016 bytes of data
,2015-11-20T12:46:33.348Z SendDataTCPServer.js: TCP/IP server has received 5877960 bytes of data
,2015-11-20T12:46:33.353Z SendDataTCPServer.js: TCP/IP server has received 626944 bytes of data
,2015-11-20T12:46:33.368Z SendDataTCPServer.js: TCP/IP server has received 5895480 bytes of data
,2015-11-20T12:46:33.370Z SendDataTCPServer.js: TCP/IP server has received 638848 bytes of data
,2015-11-20T12:46:33.388Z SendDataTCPServer.js: TCP/IP server has received 5930520 bytes of data
,2015-11-20T12:46:33.403Z SendDataTCPServer.js: TCP/IP server has received 5934900 bytes of data
,2015-11-20T12:46:33.492Z SendDataTCPServer.js: TCP/IP server has received 639840 bytes of data
2015-11-20T12:46:33.493Z SendDataTCPServer.js: TCP/IP server has received 5939280 bytes of data
,2015-11-20T12:46:33.509Z SendDataTCPServer.js: TCP/IP server has received 643808 bytes of data
,2015-11-20T12:46:33.511Z SendDataTCPServer.js: TCP/IP server has received 5943660 bytes of data
,2015-11-20T12:46:33.526Z SendDataTCPServer.js: TCP/IP server has received 648768 bytes of data
,2015-11-20T12:46:33.542Z SendDataTCPServer.js: TCP/IP server has received 653728 bytes of data
,2015-11-20T12:46:33.558Z SendDataTCPServer.js: TCP/IP server has received 673568 bytes of data
,2015-11-20T12:46:33.573Z SendDataTCPServer.js: TCP/IP server has received 681504 bytes of data
,2015-11-20T12:46:33.663Z SendDataTCPServer.js: TCP/IP server has received 686464 bytes of data
,2015-11-20T12:46:33.681Z SendDataTCPServer.js: TCP/IP server has received 697376 bytes of data
,2015-11-20T12:46:33.699Z SendDataTCPServer.js: TCP/IP server has received 707296 bytes of data
,2015-11-20T12:46:33.714Z SendDataTCPServer.js: TCP/IP server has received 719200 bytes of data
,2015-11-20T12:46:33.733Z SendDataTCPServer.js: TCP/IP server has received 728128 bytes of data
,2015-11-20T12:46:33.748Z SendDataTCPServer.js: TCP/IP server has received 735072 bytes of data
,2015-11-20T12:46:33.764Z SendDataTCPServer.js: TCP/IP server has received 744000 bytes of data
,2015-11-20T12:46:33.779Z SendDataTCPServer.js: TCP/IP server has received 753920 bytes of data
,2015-11-20T12:46:33.795Z SendDataTCPServer.js: TCP/IP server has received 766816 bytes of data
,2015-11-20T12:46:33.808Z SendDataTCPServer.js: TCP/IP server has received 777728 bytes of data
,2015-11-20T12:46:33.821Z SendDataTCPServer.js: TCP/IP server has received 790624 bytes of data
,2015-11-20T12:46:33.837Z SendDataTCPServer.js: TCP/IP server has received 801536 bytes of data
,2015-11-20T12:46:33.850Z SendDataTCPServer.js: TCP/IP server has received 810464 bytes of data
,2015-11-20T12:46:33.864Z SendDataTCPServer.js: TCP/IP server has received 819392 bytes of data
,2015-11-20T12:46:33.878Z SendDataTCPServer.js: TCP/IP server has received 833280 bytes of data
,2015-11-20T12:46:33.890Z SendDataTCPServer.js: TCP/IP server has received 848160 bytes of data
,2015-11-20T12:46:33.905Z SendDataTCPServer.js: TCP/IP server has received 868000 bytes of data
,2015-11-20T12:46:33.920Z SendDataTCPServer.js: TCP/IP server has received 889824 bytes of data
,2015-11-20T12:46:33.934Z SendDataTCPServer.js: TCP/IP server has received 890816 bytes of data
,2015-11-20T12:46:33.947Z SendDataTCPServer.js: TCP/IP server has received 898752 bytes of data
,2015-11-20T12:46:33.960Z SendDataTCPServer.js: TCP/IP server has received 914624 bytes of data
,2015-11-20T12:46:33.973Z SendDataTCPServer.js: TCP/IP server has received 932480 bytes of data
,2015-11-20T12:46:33.988Z SendDataTCPServer.js: TCP/IP server has received 951328 bytes of data
,2015-11-20T12:46:34.002Z SendDataTCPServer.js: TCP/IP server has received 970176 bytes of data
,2015-11-20T12:46:34.019Z SendDataTCPServer.js: TCP/IP server has received 979104 bytes of data
,2015-11-20T12:46:34.023Z SendDataTCPServer.js: TCP/IP server has received 5995854 bytes of data
,2015-11-20T12:46:34.040Z SendDataTCPServer.js: TCP/IP server has received 1002912 bytes of data
,2015-11-20T12:46:34.041Z SendDataTCPServer.js: TCP/IP server has received 6002790 bytes of data
,2015-11-20T12:46:34.054Z SendDataTCPServer.js: TCP/IP server has received 1029696 bytes of data
,2015-11-20T12:46:34.067Z SendDataTCPServer.js: TCP/IP server has received 1041600 bytes of data
,2015-11-20T12:46:34.089Z SendDataTCPServer.js: TCP/IP server has received 1043584 bytes of data
,2015-11-20T12:46:34.103Z SendDataTCPServer.js: TCP/IP server has received 1057472 bytes of data
,2015-11-20T12:46:34.118Z SendDataTCPServer.js: TCP/IP server has received 1063424 bytes of data
2015-11-20T12:46:34.119Z SendDataTCPServer.js: TCP/IP server has received 6033308 bytes of data
,2015-11-20T12:46:34.132Z SendDataTCPServer.js: TCP/IP server has received 1079296 bytes of data
,2015-11-20T12:46:34.134Z SendDataTCPServer.js: TCP/IP server has received 6035640 bytes of data
,2015-11-20T12:46:34.147Z SendDataTCPServer.js: TCP/IP server has received 1103104 bytes of data
,2015-11-20T12:46:34.160Z SendDataTCPServer.js: TCP/IP server has received 1122944 bytes of data
,2015-11-20T12:46:34.176Z SendDataTCPServer.js: TCP/IP server has received 6042210 bytes of data
,2015-11-20T12:46:34.189Z SendDataTCPServer.js: TCP/IP server has received 6094770 bytes of data
,2015-11-20T12:46:34.204Z SendDataTCPServer.js: TCP/IP server has received 6143010 bytes of data
,2015-11-20T12:46:34.219Z SendDataTCPServer.js: TCP/IP server has received 6156090 bytes of data
,2015-11-20T12:46:34.221Z SendDataTCPServer.js: TCP/IP server has received 1124928 bytes of data
,2015-11-20T12:46:34.236Z SendDataTCPServer.js: TCP/IP server has received 6182370 bytes of data
,2015-11-20T12:46:34.238Z SendDataTCPServer.js: TCP/IP server has received 1134848 bytes of data
,2015-11-20T12:46:34.251Z SendDataTCPServer.js: TCP/IP server has received 6226170 bytes of data
,2015-11-20T12:46:34.253Z SendDataTCPServer.js: TCP/IP server has received 1136832 bytes of data
,2015-11-20T12:46:34.266Z SendDataTCPServer.js: TCP/IP server has received 6261210 bytes of data
,2015-11-20T12:46:34.267Z SendDataTCPServer.js: TCP/IP server has received 1147744 bytes of data
,2015-11-20T12:46:34.281Z SendDataTCPServer.js: TCP/IP server has received 6280920 bytes of data
,2015-11-20T12:46:34.306Z SendDataTCPServer.js: TCP/IP server has received 6294060 bytes of data
,2015-11-20T12:46:34.330Z SendDataTCPServer.js: TCP/IP server has received 1158656 bytes of data
,2015-11-20T12:46:34.343Z SendDataTCPServer.js: TCP/IP server has received 1176512 bytes of data
,2015-11-20T12:46:34.385Z SendDataTCPServer.js: TCP/IP server has received 1180480 bytes of data
,2015-11-20T12:46:34.399Z SendDataTCPServer.js: TCP/IP server has received 1184448 bytes of data
,2015-11-20T12:46:34.503Z SendDataTCPServer.js: TCP/IP server has received 1193376 bytes of data
,2015-11-20T12:46:34.522Z SendDataTCPServer.js: TCP/IP server has received 1206272 bytes of data
,2015-11-20T12:46:34.540Z SendDataTCPServer.js: TCP/IP server has received 1209248 bytes of data
2015-11-20T12:46:34.542Z SendDataTCPServer.js: TCP/IP server has received 6296250 bytes of data
,2015-11-20T12:46:34.558Z SendDataTCPServer.js: TCP/IP server has received 1210240 bytes of data
,2015-11-20T12:46:34.561Z SendDataTCPServer.js: TCP/IP server has received 6309390 bytes of data
,2015-11-20T12:46:34.577Z SendDataTCPServer.js: TCP/IP server has received 1214208 bytes of data
2015-11-20T12:46:34.578Z SendDataTCPServer.js: TCP/IP server has received 6315960 bytes of data
,2015-11-20T12:46:34.592Z SendDataTCPServer.js: TCP/IP server has received 1220160 bytes of data
,2015-11-20T12:46:34.594Z SendDataTCPServer.js: TCP/IP server has received 6359760 bytes of data
,2015-11-20T12:46:34.612Z SendDataTCPServer.js: TCP/IP server has received 1238016 bytes of data
,2015-11-20T12:46:34.627Z SendDataTCPServer.js: TCP/IP server has received 1248928 bytes of data
,2015-11-20T12:46:34.640Z SendDataTCPServer.js: TCP/IP server has received 1261824 bytes of data
,2015-11-20T12:46:34.655Z SendDataTCPServer.js: TCP/IP server has received 1272736 bytes of data
,2015-11-20T12:46:34.670Z SendDataTCPServer.js: TCP/IP server has received 1274720 bytes of data
,2015-11-20T12:46:34.683Z SendDataTCPServer.js: TCP/IP server has received 1278688 bytes of data
,2015-11-20T12:46:34.697Z SendDataTCPServer.js: TCP/IP server has received 1292576 bytes of data
,2015-11-20T12:46:34.716Z SendDataTCPServer.js: TCP/IP server has received 1300512 bytes of data
,2015-11-20T12:46:34.718Z SendDataTCPServer.js: TCP/IP server has received 6381660 bytes of data
,2015-11-20T12:46:34.735Z SendDataTCPServer.js: TCP/IP server has received 1315392 bytes of data
,2015-11-20T12:46:34.737Z SendDataTCPServer.js: TCP/IP server has received 6394800 bytes of data
,2015-11-20T12:46:34.751Z SendDataTCPServer.js: TCP/IP server has received 1343168 bytes of data
,2015-11-20T12:46:34.765Z SendDataTCPServer.js: TCP/IP server has received 1345152 bytes of data
,2015-11-20T12:46:34.790Z SendDataTCPServer.js: TCP/IP server has received 1360032 bytes of data
,2015-11-20T12:46:34.805Z SendDataTCPServer.js: TCP/IP server has received 1363008 bytes of data
,2015-11-20T12:46:34.941Z SendDataTCPServer.js: TCP/IP server has received 1364000 bytes of data
,2015-11-20T12:46:34.956Z SendDataTCPServer.js: TCP/IP server has received 1370944 bytes of data
,2015-11-20T12:46:34.973Z SendDataTCPServer.js: TCP/IP server has received 1380864 bytes of data
,2015-11-20T12:46:34.996Z SendDataTCPServer.js: TCP/IP server has received 1388800 bytes of data
,2015-11-20T12:46:35.043Z SendDataTCPServer.js: TCP/IP server has received 1393760 bytes of data
2015-11-20T12:46:35.046Z SendDataTCPServer.js: TCP/IP server has received 6476720 bytes of data
,2015-11-20T12:46:35.065Z SendDataTCPServer.js: TCP/IP server has received 1409632 bytes of data
,2015-11-20T12:46:35.067Z SendDataTCPServer.js: TCP/IP server has received 6534960 bytes of data
,2015-11-20T12:46:35.085Z SendDataTCPServer.js: TCP/IP server has received 1428480 bytes of data
,2015-11-20T12:46:35.103Z SendDataTCPServer.js: TCP/IP server has received 1444352 bytes of data
,2015-11-20T12:46:35.117Z SendDataTCPServer.js: TCP/IP server has received 1457248 bytes of data
,2015-11-20T12:46:35.132Z SendDataTCPServer.js: TCP/IP server has received 1459232 bytes of data
,2015-11-20T12:46:35.158Z SendDataTCPServer.js: TCP/IP server has received 1471136 bytes of data
,2015-11-20T12:46:35.174Z SendDataTCPServer.js: TCP/IP server has received 1488000 bytes of data
,2015-11-20T12:46:35.188Z SendDataTCPServer.js: TCP/IP server has received 1496928 bytes of data
,2015-11-20T12:46:35.189Z SendDataTCPServer.js: TCP/IP server has received 6539198 bytes of data
,2015-11-20T12:46:35.205Z SendDataTCPServer.js: TCP/IP server has received 1502880 bytes of data
,2015-11-20T12:46:35.220Z SendDataTCPServer.js: TCP/IP server has received 6602850 bytes of data
,2015-11-20T12:46:35.240Z SendDataTCPServer.js: TCP/IP server has received 1520736 bytes of data
,2015-11-20T12:46:35.242Z SendDataTCPServer.js: TCP/IP server has received 6607230 bytes of data
,2015-11-20T12:46:35.257Z SendDataTCPServer.js: TCP/IP server has received 1535616 bytes of data
,2015-11-20T12:46:35.272Z SendDataTCPServer.js: TCP/IP server has received 1550496 bytes of data
,2015-11-20T12:46:35.286Z SendDataTCPServer.js: TCP/IP server has received 1553472 bytes of data
,2015-11-20T12:46:35.311Z SendDataTCPServer.js: TCP/IP server has received 6613800 bytes of data
,2015-11-20T12:46:35.327Z SendDataTCPServer.js: TCP/IP server has received 1555456 bytes of data
,2015-11-20T12:46:35.352Z SendDataTCPServer.js: TCP/IP server has received 1562400 bytes of data
,2015-11-20T12:46:35.365Z SendDataTCPServer.js: TCP/IP server has received 1573312 bytes of data
,2015-11-20T12:46:35.379Z SendDataTCPServer.js: TCP/IP server has received 1588192 bytes of data
,2015-11-20T12:46:35.394Z SendDataTCPServer.js: TCP/IP server has received 1601088 bytes of data
,2015-11-20T12:46:35.408Z SendDataTCPServer.js: TCP/IP server has received 1615968 bytes of data
,2015-11-20T12:46:35.423Z SendDataTCPServer.js: TCP/IP server has received 6618180 bytes of data
,2015-11-20T12:46:35.437Z SendDataTCPServer.js: TCP/IP server has received 6629130 bytes of data
,2015-11-20T12:46:35.515Z SendDataTCPServer.js: TCP/IP server has received 6637606 bytes of data
,2015-11-20T12:46:35.536Z SendDataTCPServer.js: TCP/IP server has received 6657600 bytes of data
,2015-11-20T12:46:35.555Z SendDataTCPServer.js: TCP/IP server has received 6690450 bytes of data
,2015-11-20T12:46:35.576Z SendDataTCPServer.js: TCP/IP server has received 6721110 bytes of data
,2015-11-20T12:46:35.592Z SendDataTCPServer.js: TCP/IP server has received 6743010 bytes of data
,2015-11-20T12:46:35.609Z SendDataTCPServer.js: TCP/IP server has received 6773670 bytes of data
,2015-11-20T12:46:35.626Z SendDataTCPServer.js: TCP/IP server has received 6797760 bytes of data
,2015-11-20T12:46:35.642Z SendDataTCPServer.js: TCP/IP server has received 6821850 bytes of data
,2015-11-20T12:46:35.657Z SendDataTCPServer.js: TCP/IP server has received 6839370 bytes of data
,2015-11-20T12:46:35.660Z SendDataTCPServer.js: TCP/IP server has received 1621920 bytes of data
,2015-11-20T12:46:35.675Z SendDataTCPServer.js: TCP/IP server has received 6852510 bytes of data
,2015-11-20T12:46:35.679Z SendDataTCPServer.js: TCP/IP server has received 1628864 bytes of data
,2015-11-20T12:46:35.690Z SendDataTCPServer.js: TCP/IP server has received 6887550 bytes of data
,2015-11-20T12:46:35.706Z SendDataTCPServer.js: TCP/IP server has received 6898500 bytes of data
,2015-11-20T12:46:35.707Z SendDataTCPServer.js: TCP/IP server has received 1640768 bytes of data
,2015-11-20T12:46:35.722Z SendDataTCPServer.js: TCP/IP server has received 6946680 bytes of data
,2015-11-20T12:46:35.735Z SendDataTCPServer.js: TCP/IP server has received 6964200 bytes of data
,2015-11-20T12:46:35.736Z SendDataTCPServer.js: TCP/IP server has received 1652672 bytes of data
,2015-11-20T12:46:35.750Z SendDataTCPServer.js: TCP/IP server has received 7003620 bytes of data
,2015-11-20T12:46:35.767Z SendDataTCPServer.js: TCP/IP server has received 7016760 bytes of data
,2015-11-20T12:46:35.768Z SendDataTCPServer.js: TCP/IP server has received 1673504 bytes of data
,2015-11-20T12:46:35.781Z SendDataTCPServer.js: TCP/IP server has received 7018950 bytes of data
2015-11-20T12:46:35.782Z SendDataTCPServer.js: TCP/IP server has received 1704256 bytes of data
,2015-11-20T12:46:35.797Z SendDataTCPServer.js: TCP/IP server has received 7075890 bytes of data
,2015-11-20T12:46:35.801Z SendDataTCPServer.js: TCP/IP server has received 1713184 bytes of data
,2015-11-20T12:46:35.816Z SendDataTCPServer.js: TCP/IP server has received 7104360 bytes of data
,2015-11-20T12:46:35.817Z SendDataTCPServer.js: TCP/IP server has received 1724096 bytes of data
,2015-11-20T12:46:35.831Z SendDataTCPServer.js: TCP/IP server has received 1739968 bytes of data
,2015-11-20T12:46:35.844Z SendDataTCPServer.js: TCP/IP server has received 1754848 bytes of data
,2015-11-20T12:46:35.857Z SendDataTCPServer.js: TCP/IP server has received 1775680 bytes of data
,2015-11-20T12:46:35.917Z SendDataTCPServer.js: TCP/IP server has received 1784608 bytes of data
,2015-11-20T12:46:35.954Z SendDataTCPServer.js: TCP/IP server has received 1788576 bytes of data
,2015-11-20T12:46:35.968Z SendDataTCPServer.js: TCP/IP server has received 1801472 bytes of data
,2015-11-20T12:46:35.983Z SendDataTCPServer.js: TCP/IP server has received 1819328 bytes of data
,2015-11-20T12:46:35.997Z SendDataTCPServer.js: TCP/IP server has received 1837184 bytes of data
,2015-11-20T12:46:36.010Z SendDataTCPServer.js: TCP/IP server has received 1847104 bytes of data
,2015-11-20T12:46:36.024Z SendDataTCPServer.js: TCP/IP server has received 1855040 bytes of data
,2015-11-20T12:46:36.036Z SendDataTCPServer.js: TCP/IP server has received 1857024 bytes of data
,2015-11-20T12:46:36.126Z SendDataTCPServer.js: TCP/IP server has received 7117500 bytes of data
,2015-11-20T12:46:36.142Z SendDataTCPServer.js: TCP/IP server has received 7139400 bytes of data
,2015-11-20T12:46:36.162Z SendDataTCPServer.js: TCP/IP server has received 7154730 bytes of data
,2015-11-20T12:46:36.181Z SendDataTCPServer.js: TCP/IP server has received 7183200 bytes of data
,2015-11-20T12:46:36.194Z SendDataTCPServer.js: TCP/IP server has received 7209480 bytes of data
,2015-11-20T12:46:36.217Z SendDataTCPServer.js: TCP/IP server has received 7246710 bytes of data
,2015-11-20T12:46:36.234Z SendDataTCPServer.js: TCP/IP server has received 1863968 bytes of data
,2015-11-20T12:46:36.251Z SendDataTCPServer.js: TCP/IP server has received 7255470 bytes of data
,2015-11-20T12:46:36.252Z SendDataTCPServer.js: TCP/IP server has received 1919520 bytes of data
,2015-11-20T12:46:36.268Z SendDataTCPServer.js: TCP/IP server has received 7277370 bytes of data
,2015-11-20T12:46:36.302Z SendDataTCPServer.js: TCP/IP server has received 1932416 bytes of data
,2015-11-20T12:46:36.324Z SendDataTCPServer.js: TCP/IP server has received 1956992 bytes of data
,2015-11-20T12:46:36.338Z SendDataTCPServer.js: TCP/IP server has received 1984992 bytes of data
,2015-11-20T12:46:36.351Z SendDataTCPServer.js: TCP/IP server has received 7332120 bytes of data
,2015-11-20T12:46:36.373Z SendDataTCPServer.js: TCP/IP server has received 1986976 bytes of data
,2015-11-20T12:46:36.375Z SendDataTCPServer.js: TCP/IP server has received 7415340 bytes of data
,2015-11-20T12:46:36.394Z SendDataTCPServer.js: TCP/IP server has received 2009792 bytes of data
,2015-11-20T12:46:36.397Z SendDataTCPServer.js: TCP/IP server has received 7417530 bytes of data
,2015-11-20T12:46:36.411Z SendDataTCPServer.js: TCP/IP server has received 2029632 bytes of data
,2015-11-20T12:46:36.426Z SendDataTCPServer.js: TCP/IP server has received 2043520 bytes of data
,2015-11-20T12:46:36.464Z SendDataTCPServer.js: TCP/IP server has received 7421910 bytes of data
,2015-11-20T12:46:36.477Z SendDataTCPServer.js: TCP/IP server has received 2054432 bytes of data
,2015-11-20T12:46:36.490Z SendDataTCPServer.js: TCP/IP server has received 2070304 bytes of data
,2015-11-20T12:46:36.506Z SendDataTCPServer.js: TCP/IP server has received 2090144 bytes of data
,2015-11-20T12:46:36.522Z SendDataTCPServer.js: TCP/IP server has received 7470090 bytes of data
,2015-11-20T12:46:36.536Z SendDataTCPServer.js: TCP/IP server has received 7485420 bytes of data
,2015-11-20T12:46:36.538Z SendDataTCPServer.js: TCP/IP server has received 2106016 bytes of data
,2015-11-20T12:46:36.552Z SendDataTCPServer.js: TCP/IP server has received 2129824 bytes of data
,2015-11-20T12:46:36.577Z SendDataTCPServer.js: TCP/IP server has received 2140736 bytes of data
,2015-11-20T12:46:36.590Z SendDataTCPServer.js: TCP/IP server has received 2156608 bytes of data
,2015-11-20T12:46:36.604Z SendDataTCPServer.js: TCP/IP server has received 2171488 bytes of data
,2015-11-20T12:46:36.644Z SendDataTCPServer.js: TCP/IP server has received 7516080 bytes of data
,2015-11-20T12:46:36.659Z SendDataTCPServer.js: TCP/IP server has received 7518270 bytes of data
,2015-11-20T12:46:36.660Z SendDataTCPServer.js: TCP/IP server has received 2184384 bytes of data
,2015-11-20T12:46:36.673Z SendDataTCPServer.js: TCP/IP server has received 2203232 bytes of data
,2015-11-20T12:46:36.687Z SendDataTCPServer.js: TCP/IP server has received 2207200 bytes of data
,2015-11-20T12:46:36.719Z SendDataTCPServer.js: TCP/IP server has received 2218112 bytes of data
,2015-11-20T12:46:36.721Z SendDataTCPServer.js: TCP/IP server has received 7540170 bytes of data
,2015-11-20T12:46:36.738Z SendDataTCPServer.js: TCP/IP server has received 2220096 bytes of data
,2015-11-20T12:46:36.740Z SendDataTCPServer.js: TCP/IP server has received 7544550 bytes of data
,2015-11-20T12:46:36.755Z SendDataTCPServer.js: TCP/IP server has received 2234976 bytes of data
,2015-11-20T12:46:36.769Z SendDataTCPServer.js: TCP/IP server has received 2253824 bytes of data
,2015-11-20T12:46:36.798Z SendDataTCPServer.js: TCP/IP server has received 7561360 bytes of data
,2015-11-20T12:46:36.812Z SendDataTCPServer.js: TCP/IP server has received 7562070 bytes of data
,2015-11-20T12:46:36.816Z SendDataTCPServer.js: TCP/IP server has received 2261760 bytes of data
,2015-11-20T12:46:36.833Z SendDataTCPServer.js: TCP/IP server has received 2274656 bytes of data
,2015-11-20T12:46:36.848Z SendDataTCPServer.js: TCP/IP server has received 2291520 bytes of data
,2015-11-20T12:46:36.852Z SendDataTCPServer.js: TCP/IP server has received 7566450 bytes of data
,2015-11-20T12:46:36.866Z SendDataTCPServer.js: TCP/IP server has received 2314336 bytes of data
,2015-11-20T12:46:36.907Z SendDataTCPServer.js: TCP/IP server has received 7593358 bytes of data
,2015-11-20T12:46:36.923Z SendDataTCPServer.js: TCP/IP server has received 7603680 bytes of data
,2015-11-20T12:46:36.972Z SendDataTCPServer.js: TCP/IP server has received 7662526 bytes of data
,2015-11-20T12:46:36.990Z SendDataTCPServer.js: TCP/IP server has received 7662810 bytes of data
,2015-11-20T12:46:37.063Z SendDataTCPServer.js: TCP/IP server has received 7690428 bytes of data
,2015-11-20T12:46:37.082Z SendDataTCPServer.js: TCP/IP server has received 7763550 bytes of data
,2015-11-20T12:46:37.129Z SendDataTCPServer.js: TCP/IP server has received 7772310 bytes of data
,2015-11-20T12:46:37.146Z SendDataTCPServer.js: TCP/IP server has received 7792020 bytes of data
,2015-11-20T12:46:37.237Z SendDataTCPServer.js: TCP/IP server has received 7805160 bytes of data
,2015-11-20T12:46:37.257Z SendDataTCPServer.js: TCP/IP server has received 7807350 bytes of data
,2015-11-20T12:46:37.259Z SendDataTCPServer.js: TCP/IP server has received 2322272 bytes of data
,2015-11-20T12:46:37.275Z SendDataTCPServer.js: TCP/IP server has received 2328224 bytes of data
,2015-11-20T12:46:37.292Z SendDataTCPServer.js: TCP/IP server has received 2339136 bytes of data
,2015-11-20T12:46:37.314Z SendDataTCPServer.js: TCP/IP server has received 2346080 bytes of data
,2015-11-20T12:46:37.328Z SendDataTCPServer.js: TCP/IP server has received 2367904 bytes of data
,2015-11-20T12:46:37.343Z SendDataTCPServer.js: TCP/IP server has received 2376832 bytes of data
,2015-11-20T12:46:37.344Z SendDataTCPServer.js: TCP/IP server has received 7820490 bytes of data
,2015-11-20T12:46:37.359Z SendDataTCPServer.js: TCP/IP server has received 7857720 bytes of data
,2015-11-20T12:46:37.378Z SendDataTCPServer.js: TCP/IP server has received 7892618 bytes of data
,2015-11-20T12:46:37.398Z SendDataTCPServer.js: TCP/IP server has received 7923420 bytes of data
,2015-11-20T12:46:37.413Z SendDataTCPServer.js: TCP/IP server has received 7949700 bytes of data
,2015-11-20T12:46:37.428Z SendDataTCPServer.js: TCP/IP server has received 2390720 bytes of data
,2015-11-20T12:46:37.443Z SendDataTCPServer.js: TCP/IP server has received 2408576 bytes of data
,2015-11-20T12:46:37.445Z SendDataTCPServer.js: TCP/IP server has received 7951890 bytes of data
,2015-11-20T12:46:37.458Z SendDataTCPServer.js: TCP/IP server has received 2426432 bytes of data
,2015-11-20T12:46:37.459Z SendDataTCPServer.js: TCP/IP server has received 7960650 bytes of data
,2015-11-20T12:46:37.473Z SendDataTCPServer.js: TCP/IP server has received 2440320 bytes of data
,2015-11-20T12:46:37.500Z SendDataTCPServer.js: TCP/IP server has received 2446272 bytes of data
,2015-11-20T12:46:37.514Z SendDataTCPServer.js: TCP/IP server has received 2447264 bytes of data
,2015-11-20T12:46:37.528Z SendDataTCPServer.js: TCP/IP server has received 2463136 bytes of data
,2015-11-20T12:46:37.541Z SendDataTCPServer.js: TCP/IP server has received 2471072 bytes of data
,2015-11-20T12:46:37.543Z SendDataTCPServer.js: TCP/IP server has received 7965030 bytes of data
,2015-11-20T12:46:37.558Z SendDataTCPServer.js: TCP/IP server has received 7991310 bytes of data
,2015-11-20T12:46:37.573Z SendDataTCPServer.js: TCP/IP server has received 8028398 bytes of data
,2015-11-20T12:46:37.588Z SendDataTCPServer.js: TCP/IP server has received 8032920 bytes of data
,2015-11-20T12:46:37.650Z SendDataTCPServer.js: TCP/IP server has received 8048250 bytes of data
,2015-11-20T12:46:37.676Z SendDataTCPServer.js: TCP/IP server has received 8078768 bytes of data
,2015-11-20T12:46:37.695Z SendDataTCPServer.js: TCP/IP server has received 8100810 bytes of data
,2015-11-20T12:46:37.789Z SendDataTCPServer.js: TCP/IP server has received 8113950 bytes of data
,2015-11-20T12:46:37.806Z SendDataTCPServer.js: TCP/IP server has received 8144610 bytes of data
,2015-11-20T12:46:37.822Z SendDataTCPServer.js: TCP/IP server has received 8170890 bytes of data
,2015-11-20T12:46:37.845Z SendDataTCPServer.js: TCP/IP server has received 8210310 bytes of data
,2015-11-20T12:46:37.863Z SendDataTCPServer.js: TCP/IP server has received 8214690 bytes of data
,2015-11-20T12:46:37.927Z SendDataTCPServer.js: TCP/IP server has received 2473056 bytes of data
,2015-11-20T12:46:37.944Z SendDataTCPServer.js: TCP/IP server has received 2480000 bytes of data
,2015-11-20T12:46:37.960Z SendDataTCPServer.js: TCP/IP server has received 2495872 bytes of data
,2015-11-20T12:46:37.982Z SendDataTCPServer.js: TCP/IP server has received 2510752 bytes of data
,2015-11-20T12:46:38.006Z SendDataTCPServer.js: TCP/IP server has received 2524640 bytes of data
,2015-11-20T12:46:38.020Z SendDataTCPServer.js: TCP/IP server has received 2529600 bytes of data
,2015-11-20T12:46:38.023Z SendDataTCPServer.js: TCP/IP server has received 8221260 bytes of data
,2015-11-20T12:46:38.042Z SendDataTCPServer.js: TCP/IP server has received 2533568 bytes of data
,2015-11-20T12:46:38.046Z SendDataTCPServer.js: TCP/IP server has received 8254110 bytes of data
,2015-11-20T12:46:38.060Z SendDataTCPServer.js: TCP/IP server has received 2535552 bytes of data
,2015-11-20T12:46:38.061Z SendDataTCPServer.js: TCP/IP server has received 8267250 bytes of data
,2015-11-20T12:46:38.078Z SendDataTCPServer.js: TCP/IP server has received 2546464 bytes of data
,2015-11-20T12:46:38.081Z SendDataTCPServer.js: TCP/IP server has received 8276010 bytes of data
,2015-11-20T12:46:38.097Z SendDataTCPServer.js: TCP/IP server has received 2571264 bytes of data
,2015-11-20T12:46:38.113Z SendDataTCPServer.js: TCP/IP server has received 2578208 bytes of data
,2015-11-20T12:46:38.115Z SendDataTCPServer.js: TCP/IP server has received 8308860 bytes of data
,2015-11-20T12:46:38.130Z SendDataTCPServer.js: TCP/IP server has received 8330760 bytes of data
,2015-11-20T12:46:38.145Z SendDataTCPServer.js: TCP/IP server has received 8339520 bytes of data
,2015-11-20T12:46:38.160Z SendDataTCPServer.js: TCP/IP server has received 8359230 bytes of data
,2015-11-20T12:46:38.174Z SendDataTCPServer.js: TCP/IP server has received 8365800 bytes of data
,2015-11-20T12:46:38.187Z SendDataTCPServer.js: TCP/IP server has received 2584160 bytes of data
,2015-11-20T12:46:38.251Z SendDataTCPServer.js: TCP/IP server has received 2589248 bytes of data
,2015-11-20T12:46:38.266Z SendDataTCPServer.js: TCP/IP server has received 2603008 bytes of data
,2015-11-20T12:46:38.281Z SendDataTCPServer.js: TCP/IP server has received 2613920 bytes of data
,2015-11-20T12:46:38.296Z SendDataTCPServer.js: TCP/IP server has received 2618880 bytes of data
2015-11-20T12:46:38.297Z SendDataTCPServer.js: TCP/IP server has received 8382894 bytes of data
,2015-11-20T12:46:38.316Z SendDataTCPServer.js: TCP/IP server has received 2642688 bytes of data
,2015-11-20T12:46:38.318Z SendDataTCPServer.js: TCP/IP server has received 8398650 bytes of data
,2015-11-20T12:46:38.332Z SendDataTCPServer.js: TCP/IP server has received 2644672 bytes of data
,2015-11-20T12:46:38.459Z SendDataTCPServer.js: TCP/IP server has received 2654592 bytes of data
2015-11-20T12:46:38.460Z SendDataTCPServer.js: TCP/IP server has received 8405220 bytes of data
,2015-11-20T12:46:38.474Z SendDataTCPServer.js: TCP/IP server has received 2670464 bytes of data
,2015-11-20T12:46:38.492Z SendDataTCPServer.js: TCP/IP server has received 2671456 bytes of data
2015-11-20T12:46:38.495Z SendDataTCPServer.js: TCP/IP server has received 8420550 bytes of data
,2015-11-20T12:46:38.511Z SendDataTCPServer.js: TCP/IP server has received 8440260 bytes of data
,2015-11-20T12:46:38.540Z SendDataTCPServer.js: TCP/IP server has received 2682368 bytes of data
,2015-11-20T12:46:38.556Z SendDataTCPServer.js: TCP/IP server has received 2683360 bytes of data
,2015-11-20T12:46:38.647Z SendDataTCPServer.js: TCP/IP server has received 2696256 bytes of data
,2015-11-20T12:46:38.665Z SendDataTCPServer.js: TCP/IP server has received 2703200 bytes of data
,2015-11-20T12:46:38.679Z SendDataTCPServer.js: TCP/IP server has received 2715104 bytes of data
,2015-11-20T12:46:38.700Z SendDataTCPServer.js: TCP/IP server has received 2724032 bytes of data
,2015-11-20T12:46:38.716Z SendDataTCPServer.js: TCP/IP server has received 2739904 bytes of data
,2015-11-20T12:46:38.732Z SendDataTCPServer.js: TCP/IP server has received 2748832 bytes of data
,2015-11-20T12:46:38.744Z SendDataTCPServer.js: TCP/IP server has received 2754784 bytes of data
,2015-11-20T12:46:38.758Z SendDataTCPServer.js: TCP/IP server has received 2765696 bytes of data
,2015-11-20T12:46:38.773Z SendDataTCPServer.js: TCP/IP server has received 2776608 bytes of data
,2015-11-20T12:46:38.786Z SendDataTCPServer.js: TCP/IP server has received 2787520 bytes of data
,2015-11-20T12:46:38.800Z SendDataTCPServer.js: TCP/IP server has received 2803392 bytes of data
,2015-11-20T12:46:38.815Z SendDataTCPServer.js: TCP/IP server has received 2821248 bytes of data
,2015-11-20T12:46:38.829Z SendDataTCPServer.js: TCP/IP server has received 2834144 bytes of data
,2015-11-20T12:46:38.844Z SendDataTCPServer.js: TCP/IP server has received 2842080 bytes of data
,2015-11-20T12:46:38.858Z SendDataTCPServer.js: TCP/IP server has received 2853984 bytes of data
,2015-11-20T12:46:38.873Z SendDataTCPServer.js: TCP/IP server has received 2872832 bytes of data
,2015-11-20T12:46:38.935Z SendDataTCPServer.js: TCP/IP server has received 8442450 bytes of data
,2015-11-20T12:46:39.012Z SendDataTCPServer.js: TCP/IP server has received 8449020 bytes of data
,2015-11-20T12:46:39.026Z SendDataTCPServer.js: TCP/IP server has received 8457780 bytes of data
,2015-11-20T12:46:39.045Z SendDataTCPServer.js: TCP/IP server has received 8461876 bytes of data
,2015-11-20T12:46:39.064Z SendDataTCPServer.js: TCP/IP server has received 8473110 bytes of data
,2015-11-20T12:46:39.079Z SendDataTCPServer.js: TCP/IP server has received 8492820 bytes of data
,2015-11-20T12:46:39.097Z SendDataTCPServer.js: TCP/IP server has received 8521290 bytes of data
,2015-11-20T12:46:39.115Z SendDataTCPServer.js: TCP/IP server has received 8541000 bytes of data
,2015-11-20T12:46:39.140Z SendDataTCPServer.js: TCP/IP server has received 8565090 bytes of data
,2015-11-20T12:46:39.163Z SendDataTCPServer.js: TCP/IP server has received 8595750 bytes of data
,2015-11-20T12:46:39.179Z SendDataTCPServer.js: TCP/IP server has received 8602320 bytes of data
,2015-11-20T12:46:39.219Z SendDataTCPServer.js: TCP/IP server has received 2882752 bytes of data
,2015-11-20T12:46:39.239Z SendDataTCPServer.js: TCP/IP server has received 2888704 bytes of data
,2015-11-20T12:46:39.255Z SendDataTCPServer.js: TCP/IP server has received 2914496 bytes of data
,2015-11-20T12:46:39.272Z SendDataTCPServer.js: TCP/IP server has received 2920448 bytes of data
,2015-11-20T12:46:39.295Z SendDataTCPServer.js: TCP/IP server has received 2932352 bytes of data
,2015-11-20T12:46:39.309Z SendDataTCPServer.js: TCP/IP server has received 2940288 bytes of data
,2015-11-20T12:46:39.338Z SendDataTCPServer.js: TCP/IP server has received 2949216 bytes of data
,2015-11-20T12:46:39.363Z SendDataTCPServer.js: TCP/IP server has received 2954176 bytes of data
,2015-11-20T12:46:39.364Z SendDataTCPServer.js: TCP/IP server has received 8641598 bytes of data
,2015-11-20T12:46:39.389Z SendDataTCPServer.js: TCP/IP server has received 2962112 bytes of data
,2015-11-20T12:46:39.413Z SendDataTCPServer.js: TCP/IP server has received 8656502 bytes of data
,2015-11-20T12:46:39.430Z SendDataTCPServer.js: TCP/IP server has received 2967072 bytes of data
,2015-11-20T12:46:39.433Z SendDataTCPServer.js: TCP/IP server has received 8784090 bytes of data
,2015-11-20T12:46:39.475Z SendDataTCPServer.js: TCP/IP server has received 2976000 bytes of data
,2015-11-20T12:46:39.477Z SendDataTCPServer.js: TCP/IP server has received 8873880 bytes of data
,2015-11-20T12:46:39.497Z SendDataTCPServer.js: TCP/IP server has received 2997824 bytes of data
,2015-11-20T12:46:39.499Z SendDataTCPServer.js: TCP/IP server has received 8876070 bytes of data
,2015-11-20T12:46:39.514Z SendDataTCPServer.js: TCP/IP server has received 3018656 bytes of data
,2015-11-20T12:46:39.517Z SendDataTCPServer.js: TCP/IP server has received 8878260 bytes of data
,2015-11-20T12:46:39.530Z SendDataTCPServer.js: TCP/IP server has received 3034528 bytes of data
,2015-11-20T12:46:39.532Z SendDataTCPServer.js: TCP/IP server has received 8884830 bytes of data
,2015-11-20T12:46:39.547Z SendDataTCPServer.js: TCP/IP server has received 3060320 bytes of data
,2015-11-20T12:46:39.565Z SendDataTCPServer.js: TCP/IP server has received 3085120 bytes of data
,2015-11-20T12:46:39.569Z SendDataTCPServer.js: TCP/IP server has received 8904540 bytes of data
,2015-11-20T12:46:39.584Z SendDataTCPServer.js: TCP/IP server has received 3099008 bytes of data
,2015-11-20T12:46:39.585Z SendDataTCPServer.js: TCP/IP server has received 8961480 bytes of data
,2015-11-20T12:46:39.601Z SendDataTCPServer.js: TCP/IP server has received 9022800 bytes of data
,2015-11-20T12:46:39.750Z SendDataTCPServer.js: TCP/IP server has received 3106944 bytes of data
,2015-11-20T12:46:39.767Z SendDataTCPServer.js: TCP/IP server has received 3134720 bytes of data
,2015-11-20T12:46:39.772Z SendDataTCPServer.js: TCP/IP server has received 9042510 bytes of data
,2015-11-20T12:46:39.815Z SendDataTCPServer.js: TCP/IP server has received 3135712 bytes of data
,2015-11-20T12:46:39.818Z SendDataTCPServer.js: TCP/IP server has received 9055650 bytes of data
,2015-11-20T12:46:39.839Z SendDataTCPServer.js: TCP/IP server has received 3210112 bytes of data
,2015-11-20T12:46:39.848Z SendDataTCPServer.js: TCP/IP server has received 9109690 bytes of data
,2015-11-20T12:46:39.865Z SendDataTCPServer.js: TCP/IP server has received 3212096 bytes of data
,2015-11-20T12:46:39.866Z SendDataTCPServer.js: TCP/IP server has received 9147630 bytes of data
,2015-11-20T12:46:39.880Z SendDataTCPServer.js: TCP/IP server has received 9165150 bytes of data
,2015-11-20T12:46:39.897Z SendDataTCPServer.js: TCP/IP server has received 9213330 bytes of data
,2015-11-20T12:46:39.899Z SendDataTCPServer.js: TCP/IP server has received 3213088 bytes of data
,2015-11-20T12:46:39.913Z SendDataTCPServer.js: TCP/IP server has received 9241800 bytes of data
,2015-11-20T12:46:39.915Z SendDataTCPServer.js: TCP/IP server has received 3215072 bytes of data
,2015-11-20T12:46:39.928Z SendDataTCPServer.js: TCP/IP server has received 9276840 bytes of data
,2015-11-20T12:46:39.930Z SendDataTCPServer.js: TCP/IP server has received 3216064 bytes of data
,2015-11-20T12:46:39.942Z SendDataTCPServer.js: TCP/IP server has received 9318450 bytes of data
,2015-11-20T12:46:39.943Z SendDataTCPServer.js: TCP/IP server has received 3217056 bytes of data
,2015-11-20T12:46:39.955Z SendDataTCPServer.js: TCP/IP server has received 9349110 bytes of data
,2015-11-20T12:46:39.957Z SendDataTCPServer.js: TCP/IP server has received 3219040 bytes of data
,2015-11-20T12:46:39.968Z SendDataTCPServer.js: TCP/IP server has received 9401670 bytes of data
,2015-11-20T12:46:39.971Z SendDataTCPServer.js: TCP/IP server has received 3221024 bytes of data
,2015-11-20T12:46:39.985Z SendDataTCPServer.js: TCP/IP server has received 9406050 bytes of data
,2015-11-20T12:46:39.986Z SendDataTCPServer.js: TCP/IP server has received 3257728 bytes of data
,2015-11-20T12:46:40.004Z SendDataTCPServer.js: TCP/IP server has received 9421380 bytes of data
,2015-11-20T12:46:40.006Z SendDataTCPServer.js: TCP/IP server has received 3298400 bytes of data
,2015-11-20T12:46:40.022Z SendDataTCPServer.js: TCP/IP server has received 9436710 bytes of data
,2015-11-20T12:46:40.025Z SendDataTCPServer.js: TCP/IP server has received 3329152 bytes of data
,2015-11-20T12:46:40.041Z SendDataTCPServer.js: TCP/IP server has received 9441090 bytes of data
,2015-11-20T12:46:40.041Z SendDataTCPServer.js: TCP/IP server has received 3362880 bytes of data
,2015-11-20T12:46:40.056Z SendDataTCPServer.js: TCP/IP server has received 9469560 bytes of data
,2015-11-20T12:46:40.058Z SendDataTCPServer.js: TCP/IP server has received 3380736 bytes of data
,2015-11-20T12:46:40.071Z SendDataTCPServer.js: TCP/IP server has received 9500220 bytes of data
,2015-11-20T12:46:40.073Z SendDataTCPServer.js: TCP/IP server has received 3393632 bytes of data
,2015-11-20T12:46:40.085Z SendDataTCPServer.js: TCP/IP server has received 9515550 bytes of data
,2015-11-20T12:46:40.086Z SendDataTCPServer.js: TCP/IP server has received 3417440 bytes of data
,2015-11-20T12:46:40.101Z SendDataTCPServer.js: TCP/IP server has received 9552780 bytes of data
,2015-11-20T12:46:40.103Z SendDataTCPServer.js: TCP/IP server has received 3433312 bytes of data
,2015-11-20T12:46:40.117Z SendDataTCPServer.js: TCP/IP server has received 9627240 bytes of data
,2015-11-20T12:46:40.123Z SendDataTCPServer.js: TCP/IP server has received 3438272 bytes of data
,2015-11-20T12:46:40.136Z SendDataTCPServer.js: TCP/IP server has received 9673230 bytes of data
,2015-11-20T12:46:40.140Z SendDataTCPServer.js: TCP/IP server has received 3447200 bytes of data
,2015-11-20T12:46:40.154Z SendDataTCPServer.js: TCP/IP server has received 9712650 bytes of data
,2015-11-20T12:46:40.157Z SendDataTCPServer.js: TCP/IP server has received 3459104 bytes of data
,2015-11-20T12:46:40.170Z SendDataTCPServer.js: TCP/IP server has received 9749880 bytes of data
,2015-11-20T12:46:40.172Z SendDataTCPServer.js: TCP/IP server has received 3474976 bytes of data
,2015-11-20T12:46:40.187Z SendDataTCPServer.js: TCP/IP server has received 9776160 bytes of data
,2015-11-20T12:46:40.189Z SendDataTCPServer.js: TCP/IP server has received 3494816 bytes of data
,2015-11-20T12:46:40.203Z SendDataTCPServer.js: TCP/IP server has received 9804630 bytes of data
,2015-11-20T12:46:40.204Z SendDataTCPServer.js: TCP/IP server has received 3510688 bytes of data
,2015-11-20T12:46:40.217Z SendDataTCPServer.js: TCP/IP server has received 9817770 bytes of data
,2015-11-20T12:46:40.218Z SendDataTCPServer.js: TCP/IP server has received 3516640 bytes of data
,2015-11-20T12:46:40.231Z SendDataTCPServer.js: TCP/IP server has received 3538464 bytes of data
,2015-11-20T12:46:40.244Z SendDataTCPServer.js: TCP/IP server has received 3551360 bytes of data
,2015-11-20T12:46:40.245Z SendDataTCPServer.js: TCP/IP server has received 9830910 bytes of data
,2015-11-20T12:46:40.259Z SendDataTCPServer.js: TCP/IP server has received 3558304 bytes of data
,2015-11-20T12:46:40.271Z SendDataTCPServer.js: TCP/IP server has received 9839670 bytes of data
,2015-11-20T12:46:40.298Z SendDataTCPServer.js: TCP/IP server has received 9855000 bytes of data
,2015-11-20T12:46:40.310Z SendDataTCPServer.js: TCP/IP server has received 9861570 bytes of data
,2015-11-20T12:46:40.311Z SendDataTCPServer.js: TCP/IP server has received 3575168 bytes of data
,2015-11-20T12:46:40.323Z SendDataTCPServer.js: TCP/IP server has received 9865950 bytes of data
,2015-11-20T12:46:40.324Z SendDataTCPServer.js: TCP/IP server has received 3595008 bytes of data
,2015-11-20T12:46:40.338Z SendDataTCPServer.js: TCP/IP server has received 9872520 bytes of data
,2015-11-20T12:46:40.339Z SendDataTCPServer.js: TCP/IP server has received 3623776 bytes of data
,2015-11-20T12:46:40.354Z SendDataTCPServer.js: TCP/IP server has received 3654528 bytes of data
,2015-11-20T12:46:40.367Z SendDataTCPServer.js: TCP/IP server has received 3672384 bytes of data
,2015-11-20T12:46:40.380Z SendDataTCPServer.js: TCP/IP server has received 3687264 bytes of data
2015-11-20T12:46:40.381Z SendDataTCPServer.js: TCP/IP server has received 9874710 bytes of data
,2015-11-20T12:46:40.393Z SendDataTCPServer.js: TCP/IP server has received 3702144 bytes of data
,2015-11-20T12:46:40.408Z SendDataTCPServer.js: TCP/IP server has received 3717024 bytes of data
,2015-11-20T12:46:40.409Z SendDataTCPServer.js: TCP/IP server has received 9883470 bytes of data
,2015-11-20T12:46:40.421Z SendDataTCPServer.js: TCP/IP server has received 3729920 bytes of data
,2015-11-20T12:46:40.422Z SendDataTCPServer.js: TCP/IP server has received 9894420 bytes of data
,2015-11-20T12:46:40.433Z SendDataTCPServer.js: TCP/IP server has received 3736864 bytes of data
,2015-11-20T12:46:40.434Z SendDataTCPServer.js: TCP/IP server has received 9914130 bytes of data
,2015-11-20T12:46:40.448Z SendDataTCPServer.js: TCP/IP server has received 3743808 bytes of data
,2015-11-20T12:46:40.449Z SendDataTCPServer.js: TCP/IP server has received 9966690 bytes of data
,2015-11-20T12:46:40.464Z SendDataTCPServer.js: TCP/IP server has received 3758688 bytes of data
,2015-11-20T12:46:40.466Z SendDataTCPServer.js: TCP/IP server has received 9995160 bytes of data
,2015-11-20T12:46:40.479Z SendDataTCPServer.js: TCP/IP server has received 3779520 bytes of data
,2015-11-20T12:46:40.481Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20T12:46:40.494Z SendDataTCPServer.js: TCP/IP server has received 3801344 bytes of data
,2015-11-20T12:46:40.508Z SendDataTCPServer.js: TCP/IP server has received 3823168 bytes of data
,2015-11-20T12:46:40.522Z SendDataTCPServer.js: TCP/IP server has received 3844000 bytes of data
,2015-11-20T12:46:40.560Z SendDataTCPServer.js: TCP/IP server has received 3847968 bytes of data
,2015-11-20T12:46:40.572Z SendDataTCPServer.js: TCP/IP server has received 3855904 bytes of data
,2015-11-20 13:46:40.580 ThaliTest[1024:782126] server session: not connected Apple-Iphone6-1_PT8859
,2015-11-20T12:46:40.586Z SendDataTCPServer.js: TCP/IP server has received 3862848 bytes of data
,2015-11-20T12:46:40.598Z SendDataTCPServer.js: TCP/IP server has received 3888640 bytes of data
,2015-11-20T12:46:40.612Z SendDataTCPServer.js: TCP/IP server has received 3918400 bytes of data
,2015-11-20T12:46:41.050Z SendDataTCPServer.js: TCP/IP server has received 3924352 bytes of data
,2015-11-20T12:46:41.068Z SendDataTCPServer.js: TCP/IP server has received 3936256 bytes of data
,2015-11-20T12:46:41.084Z SendDataTCPServer.js: TCP/IP server has received 3954112 bytes of data
,2015-11-20T12:46:41.099Z SendDataTCPServer.js: TCP/IP server has received 3967008 bytes of data
,2015-11-20T12:46:41.114Z SendDataTCPServer.js: TCP/IP server has received 3980896 bytes of data
,2015-11-20T12:46:41.378Z SendDataTCPServer.js: TCP/IP server has received 3981888 bytes of data
,2015-11-20T12:46:41.394Z SendDataTCPServer.js: TCP/IP server has received 3996768 bytes of data
,2015-11-20T12:46:41.410Z SendDataTCPServer.js: TCP/IP server has received 3999744 bytes of data
,2015-11-20T12:46:41.425Z SendDataTCPServer.js: TCP/IP server has received 4006688 bytes of data
,2015-11-20T12:46:41.443Z SendDataTCPServer.js: TCP/IP server has received 4017600 bytes of data
,2015-11-20T12:46:41.459Z SendDataTCPServer.js: TCP/IP server has received 4034464 bytes of data
,2015-11-20T12:46:41.475Z SendDataTCPServer.js: TCP/IP server has received 4050336 bytes of data
,2015-11-20T12:46:41.488Z SendDataTCPServer.js: TCP/IP server has received 4066208 bytes of data
,2015-11-20T12:46:41.503Z SendDataTCPServer.js: TCP/IP server has received 4083072 bytes of data
,2015-11-20T12:46:41.519Z SendDataTCPServer.js: TCP/IP server has received 4110848 bytes of data
,2015-11-20T12:46:41.534Z SendDataTCPServer.js: TCP/IP server has received 4127712 bytes of data
,2015-11-20T12:46:41.601Z SendDataTCPServer.js: TCP/IP server has received 4131680 bytes of data
,2015-11-20T12:46:41.618Z SendDataTCPServer.js: TCP/IP server has received 4149536 bytes of data
,2015-11-20T12:46:41.632Z SendDataTCPServer.js: TCP/IP server has received 4166400 bytes of data
,2015-11-20T12:46:41.646Z SendDataTCPServer.js: TCP/IP server has received 4172352 bytes of data
,2015-11-20T12:46:41.885Z SendDataTCPServer.js: TCP/IP server has received 4181280 bytes of data
,2015-11-20T12:46:41.900Z SendDataTCPServer.js: TCP/IP server has received 4195168 bytes of data
,2015-11-20T12:46:41.933Z SendDataTCPServer.js: TCP/IP server has received 4201120 bytes of data
,2015-11-20T12:46:41.948Z SendDataTCPServer.js: TCP/IP server has received 4213024 bytes of data
,2015-11-20T12:46:41.966Z SendDataTCPServer.js: TCP/IP server has received 4225920 bytes of data
,2015-11-20T12:46:41.982Z SendDataTCPServer.js: TCP/IP server has received 4237824 bytes of data
,2015-11-20T12:46:41.996Z SendDataTCPServer.js: TCP/IP server has received 4255680 bytes of data
,2015-11-20T12:46:42.011Z SendDataTCPServer.js: TCP/IP server has received 4270560 bytes of data
,2015-11-20T12:46:42.026Z SendDataTCPServer.js: TCP/IP server has received 4294368 bytes of data
,2015-11-20T12:46:42.042Z SendDataTCPServer.js: TCP/IP server has received 4309248 bytes of data
,2015-11-20T12:46:42.058Z SendDataTCPServer.js: TCP/IP server has received 4329088 bytes of data
,2015-11-20T12:46:42.072Z SendDataTCPServer.js: TCP/IP server has received 4342976 bytes of data
,2015-11-20T12:46:42.084Z SendDataTCPServer.js: TCP/IP server has received 4363808 bytes of data
,2015-11-20T12:46:42.098Z SendDataTCPServer.js: TCP/IP server has received 4383648 bytes of data
,2015-11-20T12:46:42.112Z SendDataTCPServer.js: TCP/IP server has received 4405472 bytes of data
,2015-11-20T12:46:42.127Z SendDataTCPServer.js: TCP/IP server has received 4419360 bytes of data
,2015-11-20T12:46:42.140Z SendDataTCPServer.js: TCP/IP server has received 4449120 bytes of data
,2015-11-20T12:46:42.155Z SendDataTCPServer.js: TCP/IP server has received 4455072 bytes of data
,2015-11-20T12:46:42.402Z SendDataTCPServer.js: TCP/IP server has received 4457056 bytes of data
,2015-11-20T12:46:42.418Z SendDataTCPServer.js: TCP/IP server has received 4460032 bytes of data
,2015-11-20T12:46:42.433Z SendDataTCPServer.js: TCP/IP server has received 4464992 bytes of data
,2015-11-20T12:46:42.447Z SendDataTCPServer.js: TCP/IP server has received 4468960 bytes of data
,2015-11-20T12:46:42.462Z SendDataTCPServer.js: TCP/IP server has received 4475904 bytes of data
,2015-11-20T12:46:42.477Z SendDataTCPServer.js: TCP/IP server has received 4482848 bytes of data
,2015-11-20T12:46:42.491Z SendDataTCPServer.js: TCP/IP server has received 4490784 bytes of data
,2015-11-20T12:46:42.504Z SendDataTCPServer.js: TCP/IP server has received 4502688 bytes of data
,2015-11-20T12:46:42.518Z SendDataTCPServer.js: TCP/IP server has received 4518560 bytes of data
,2015-11-20T12:46:42.534Z SendDataTCPServer.js: TCP/IP server has received 4531456 bytes of data
,2015-11-20T12:46:42.547Z SendDataTCPServer.js: TCP/IP server has received 4540384 bytes of data
,2015-11-20T12:46:42.562Z SendDataTCPServer.js: TCP/IP server has received 4552288 bytes of data
,2015-11-20T12:46:42.577Z SendDataTCPServer.js: TCP/IP server has received 4563200 bytes of data
,2015-11-20T12:46:42.590Z SendDataTCPServer.js: TCP/IP server has received 4573120 bytes of data
,2015-11-20T12:46:42.603Z SendDataTCPServer.js: TCP/IP server has received 4586016 bytes of data
,2015-11-20T12:46:42.617Z SendDataTCPServer.js: TCP/IP server has received 4604864 bytes of data
,2015-11-20T12:46:42.631Z SendDataTCPServer.js: TCP/IP server has received 4623712 bytes of data
,2015-11-20T12:46:42.645Z SendDataTCPServer.js: TCP/IP server has received 4639584 bytes of data
,2015-11-20T12:46:42.660Z SendDataTCPServer.js: TCP/IP server has received 4659424 bytes of data
,2015-11-20T12:46:42.675Z SendDataTCPServer.js: TCP/IP server has received 4672320 bytes of data
,2015-11-20T12:46:42.921Z SendDataTCPServer.js: TCP/IP server has received 4673312 bytes of data
,2015-11-20T12:46:42.937Z SendDataTCPServer.js: TCP/IP server has received 4677280 bytes of data
,2015-11-20T12:46:42.953Z SendDataTCPServer.js: TCP/IP server has received 4683232 bytes of data
,2015-11-20T12:46:42.969Z SendDataTCPServer.js: TCP/IP server has received 4693152 bytes of data
,2015-11-20T12:46:42.984Z SendDataTCPServer.js: TCP/IP server has received 4702080 bytes of data
,2015-11-20T12:46:42.999Z SendDataTCPServer.js: TCP/IP server has received 4705056 bytes of data
,2015-11-20T12:46:43.024Z SendDataTCPServer.js: TCP/IP server has received 4715968 bytes of data
,2015-11-20T12:46:43.040Z SendDataTCPServer.js: TCP/IP server has received 4739776 bytes of data
,2015-11-20T12:46:43.056Z SendDataTCPServer.js: TCP/IP server has received 4769536 bytes of data
,2015-11-20T12:46:43.105Z SendDataTCPServer.js: TCP/IP server has received 4771520 bytes of data
,2015-11-20T12:46:43.120Z SendDataTCPServer.js: TCP/IP server has received 4778464 bytes of data
,2015-11-20T12:46:43.134Z SendDataTCPServer.js: TCP/IP server has received 4783424 bytes of data
,2015-11-20T12:46:43.148Z SendDataTCPServer.js: TCP/IP server has received 4791360 bytes of data
,2015-11-20T12:46:43.164Z SendDataTCPServer.js: TCP/IP server has received 4804256 bytes of data
,2015-11-20T12:46:43.178Z SendDataTCPServer.js: TCP/IP server has received 4819136 bytes of data
,2015-11-20T12:46:43.194Z SendDataTCPServer.js: TCP/IP server has received 4837984 bytes of data
,2015-11-20T12:46:43.208Z SendDataTCPServer.js: TCP/IP server has received 4849888 bytes of data
,2015-11-20T12:46:43.456Z SendDataTCPServer.js: TCP/IP server has received 4852864 bytes of data
,2015-11-20T12:46:43.475Z SendDataTCPServer.js: TCP/IP server has received 4864768 bytes of data
,2015-11-20T12:46:43.491Z SendDataTCPServer.js: TCP/IP server has received 4866752 bytes of data
,2015-11-20T12:46:43.507Z SendDataTCPServer.js: TCP/IP server has received 4868736 bytes of data
,2015-11-20T12:46:43.524Z SendDataTCPServer.js: TCP/IP server has received 4877664 bytes of data
2015-11-20T12:46:43.539Z SendDataTCPServer.js: TCP/IP server has received 4883616 bytes of data
2015-11-20T12:46:43.555Z SendDataTCPServer.js: TCP/IP server h,as received 4893536 bytes of data
2015-11-20T12:46:43.569Z SendDataTCPServer.js: TCP/IP server has received 4901472 bytes of data
,2015-11-20T12:46:43.597Z SendDataTCPServer.js: TCP/IP server has received 4905440 bytes of data
,2015-11-20T12:46:43.610Z SendDataTCPServer.js: TCP/IP server has received 4937184 bytes of data
,2015-11-20T12:46:43.627Z SendDataTCPServer.js: TCP/IP server has received 4956032 bytes of data
,2015-11-20T12:46:43.643Z SendDataTCPServer.js: TCP/IP server has received 4973888 bytes of data
,2015-11-20T12:46:43.657Z SendDataTCPServer.js: TCP/IP server has received 4991744 bytes of data
,2015-11-20T12:46:43.671Z SendDataTCPServer.js: TCP/IP server has received 5014560 bytes of data
,2015-11-20T12:46:43.686Z SendDataTCPServer.js: TCP/IP server has received 5021504 bytes of data
,2015-11-20 13:46:43.776 ThaliTest[1024:781290] multipeer session: reset timer
2015-11-20 13:46:43.777 ThaliTest[1024:781290] multipeer session: stop timer
2015-11-20 13:46:43.778 ThaliTest[1024:781290] multipeer session: start timer: 0x1b68e5a0
2015-11-,20 13:46:43.779 ThaliTest[1024:781290] server session: connect
2015-11-20 13:46:43.779 ThaliTest[1024:781290] server session: stateChange:0->1 Apple-IpadAir2-1_PT545
,2015-11-20 13:46:43.787 ThaliTest[1024:781290] server: accepting invitation Apple-IpadAir2-1_PT545
,2015-11-20T12:46:43.980Z SendDataTCPServer.js: TCP/IP server has received 5023488 bytes of data
,2015-11-20T12:46:43.995Z SendDataTCPServer.js: TCP/IP server has received 5037376 bytes of data
,2015-11-20T12:46:44.012Z SendDataTCPServer.js: TCP/IP server has received 5051264 bytes of data
,2015-11-20T12:46:44.028Z SendDataTCPServer.js: TCP/IP server has received 5060192 bytes of data
,2015-11-20T12:46:44.043Z SendDataTCPServer.js: TCP/IP server has received 5064160 bytes of data
,2015-11-20T12:46:44.070Z SendDataTCPServer.js: TCP/IP server has received 5071104 bytes of data
,2015-11-20T12:46:44.087Z SendDataTCPServer.js: TCP/IP server has received 5079040 bytes of data
,2015-11-20T12:46:44.103Z SendDataTCPServer.js: TCP/IP server has received 5098880 bytes of data
,2015-11-20T12:46:44.120Z SendDataTCPServer.js: TCP/IP server has received 5118720 bytes of data
,2015-11-20T12:46:44.135Z SendDataTCPServer.js: TCP/IP server has received 5135584 bytes of data
,2015-11-20T12:46:44.149Z SendDataTCPServer.js: TCP/IP server has received 5146496 bytes of data
,2015-11-20T12:46:44.163Z SendDataTCPServer.js: TCP/IP server has received 5158400 bytes of data
,2015-11-20T12:46:44.177Z SendDataTCPServer.js: TCP/IP server has received 5165344 bytes of data
,2015-11-20T12:46:44.189Z SendDataTCPServer.js: TCP/IP server has received 5174272 bytes of data
,2015-11-20T12:46:44.203Z SendDataTCPServer.js: TCP/IP server has received 5190144 bytes of data
,2015-11-20T12:46:44.218Z SendDataTCPServer.js: TCP/IP server has received 5204032 bytes of data
,2015-11-20T12:46:44.232Z SendDataTCPServer.js: TCP/IP server has received 5229824 bytes of data
,2015-11-20T12:46:44.247Z SendDataTCPServer.js: TCP/IP server has received 5256608 bytes of data
,2015-11-20T12:46:44.260Z SendDataTCPServer.js: TCP/IP server has received 5260576 bytes of data
,2015-11-20T12:46:44.510Z SendDataTCPServer.js: TCP/IP server has received 5266528 bytes of data
,2015-11-20T12:46:44.523Z SendDataTCPServer.js: TCP/IP server has received 5271488 bytes of data
,2015-11-20T12:46:44.549Z SendDataTCPServer.js: TCP/IP server has received 5276448 bytes of data
,2015-11-20T12:46:44.564Z SendDataTCPServer.js: TCP/IP server has received 5282400 bytes of data
,2015-11-20T12:46:44.578Z SendDataTCPServer.js: TCP/IP server has received 5288352 bytes of data
,2015-11-20T12:46:44.592Z SendDataTCPServer.js: TCP/IP server has received 5298272 bytes of data
,2015-11-20T12:46:44.607Z SendDataTCPServer.js: TCP/IP server has received 5308192 bytes of data
,2015-11-20T12:46:44.620Z SendDataTCPServer.js: TCP/IP server has received 5320096 bytes of data
,2015-11-20T12:46:44.633Z SendDataTCPServer.js: TCP/IP server has received 5331008 bytes of data
,2015-11-20T12:46:44.648Z SendDataTCPServer.js: TCP/IP server has received 5343904 bytes of data
,2015-11-20T12:46:44.663Z SendDataTCPServer.js: TCP/IP server has received 5361760 bytes of data
,2015-11-20T12:46:44.677Z SendDataTCPServer.js: TCP/IP server has received 5379616 bytes of data
,2015-11-20T12:46:44.691Z SendDataTCPServer.js: TCP/IP server has received 5393504 bytes of data
,2015-11-20T12:46:44.704Z SendDataTCPServer.js: TCP/IP server has received 5410368 bytes of data
,2015-11-20T12:46:44.718Z SendDataTCPServer.js: TCP/IP server has received 5430208 bytes of data
,2015-11-20T12:46:44.731Z SendDataTCPServer.js: TCP/IP server has received 5448064 bytes of data
,2015-11-20T12:46:44.745Z SendDataTCPServer.js: TCP/IP server has received 5472864 bytes of data
,2015-11-20T12:46:44.761Z SendDataTCPServer.js: TCP/IP server has received 5505600 bytes of data
,2015-11-20T12:46:44.776Z SendDataTCPServer.js: TCP/IP server has received 5508576 bytes of data
,2015-11-20T12:46:45.035Z SendDataTCPServer.js: TCP/IP server has received 5511552 bytes of data
,2015-11-20T12:46:45.048Z SendDataTCPServer.js: TCP/IP server has received 5515520 bytes of data
,2015-11-20T12:46:45.064Z SendDataTCPServer.js: TCP/IP server has received 5519488 bytes of data
,2015-11-20T12:46:45.076Z SendDataTCPServer.js: TCP/IP server has received 5523456 bytes of data
,2015-11-20T12:46:45.090Z SendDataTCPServer.js: TCP/IP server has received 5527424 bytes of data
,2015-11-20T12:46:45.103Z SendDataTCPServer.js: TCP/IP server has received 5529408 bytes of data
,2015-11-20T12:46:45.118Z SendDataTCPServer.js: TCP/IP server has received 5534368 bytes of data
,2015-11-20T12:46:45.133Z SendDataTCPServer.js: TCP/IP server has received 5545280 bytes of data
,2015-11-20T12:46:45.145Z SendDataTCPServer.js: TCP/IP server has received 5557184 bytes of data
,2015-11-20T12:46:45.157Z SendDataTCPServer.js: TCP/IP server has received 5573056 bytes of data
,2015-11-20T12:46:45.171Z SendDataTCPServer.js: TCP/IP server has received 5587936 bytes of data
,2015-11-20T12:46:45.185Z SendDataTCPServer.js: TCP/IP server has received 5603808 bytes of data
,2015-11-20T12:46:45.198Z SendDataTCPServer.js: TCP/IP server has received 5614720 bytes of data
,2015-11-20T12:46:45.210Z SendDataTCPServer.js: TCP/IP server has received 5624640 bytes of data
,2015-11-20T12:46:45.223Z SendDataTCPServer.js: TCP/IP server has received 5639520 bytes of data
,2015-11-20T12:46:45.238Z SendDataTCPServer.js: TCP/IP server has received 5656384 bytes of data
,2015-11-20T12:46:45.252Z SendDataTCPServer.js: TCP/IP server has received 5674240 bytes of data
,2015-11-20T12:46:45.265Z SendDataTCPServer.js: TCP/IP server has received 5689120 bytes of data
,2015-11-20T12:46:45.278Z SendDataTCPServer.js: TCP/IP server has received 5706976 bytes of data
,2015-11-20T12:46:45.292Z SendDataTCPServer.js: TCP/IP server has received 5728800 bytes of data
,2015-11-20T12:46:45.306Z SendDataTCPServer.js: TCP/IP server has received 5736736 bytes of data
,2015-11-20T12:46:45.553Z SendDataTCPServer.js: TCP/IP server has received 5738720 bytes of data
,2015-11-20T12:46:45.568Z SendDataTCPServer.js: TCP/IP server has received 5744672 bytes of data
,2015-11-20T12:46:45.583Z SendDataTCPServer.js: TCP/IP server has received 5750624 bytes of data
,2015-11-20T12:46:45.600Z SendDataTCPServer.js: TCP/IP server has received 5757568 bytes of data
,2015-11-20T12:46:45.613Z SendDataTCPServer.js: TCP/IP server has received 5758560 bytes of data
,2015-11-20T12:46:45.627Z SendDataTCPServer.js: TCP/IP server has received 5759552 bytes of data
,2015-11-20T12:46:45.640Z SendDataTCPServer.js: TCP/IP server has received 5766496 bytes of data
,2015-11-20T12:46:45.653Z SendDataTCPServer.js: TCP/IP server has received 5777408 bytes of data
,2015-11-20T12:46:45.666Z SendDataTCPServer.js: TCP/IP server has received 5791296 bytes of data
,2015-11-20T12:46:45.680Z SendDataTCPServer.js: TCP/IP server has received 5802208 bytes of data
,2015-11-20T12:46:45.695Z SendDataTCPServer.js: TCP/IP server has received 5814112 bytes of data
,2015-11-20T12:46:45.712Z SendDataTCPServer.js: TCP/IP server has received 5828000 bytes of data
,2015-11-20T12:46:45.728Z SendDataTCPServer.js: TCP/IP server has received 5843872 bytes of data
,2015-11-20T12:46:45.743Z SendDataTCPServer.js: TCP/IP server has received 5859744 bytes of data
,2015-11-20T12:46:45.757Z SendDataTCPServer.js: TCP/IP server has received 5879584 bytes of data
,2015-11-20T12:46:45.773Z SendDataTCPServer.js: TCP/IP server has received 5898432 bytes of data
,2015-11-20T12:46:45.788Z SendDataTCPServer.js: TCP/IP server has received 5915296 bytes of data
,2015-11-20T12:46:45.803Z SendDataTCPServer.js: TCP/IP server has received 5935136 bytes of data
,2015-11-20T12:46:45.817Z SendDataTCPServer.js: TCP/IP server has received 5938112 bytes of data
,2015-11-20T12:46:46.079Z SendDataTCPServer.js: TCP/IP server has received 5943072 bytes of data
,2015-11-20T12:46:46.094Z SendDataTCPServer.js: TCP/IP server has received 5950016 bytes of data
,2015-11-20T12:46:46.109Z SendDataTCPServer.js: TCP/IP server has received 5958944 bytes of data
,2015-11-20T12:46:46.122Z SendDataTCPServer.js: TCP/IP server has received 5963904 bytes of data
,2015-11-20T12:46:46.139Z SendDataTCPServer.js: TCP/IP server has received 5974816 bytes of data
,2015-11-20T12:46:46.154Z SendDataTCPServer.js: TCP/IP server has received 5979776 bytes of data
,2015-11-20T12:46:46.181Z SendDataTCPServer.js: TCP/IP server has received 5990688 bytes of data
,2015-11-20T12:46:46.194Z SendDataTCPServer.js: TCP/IP server has received 6002592 bytes of data
,2015-11-20T12:46:46.209Z SendDataTCPServer.js: TCP/IP server has received 6015488 bytes of data
,2015-11-20T12:46:46.224Z SendDataTCPServer.js: TCP/IP server has received 6026400 bytes of data
,2015-11-20T12:46:46.237Z SendDataTCPServer.js: TCP/IP server has received 6039296 bytes of data
,2015-11-20T12:46:46.251Z SendDataTCPServer.js: TCP/IP server has received 6052192 bytes of data
,2015-11-20T12:46:46.265Z SendDataTCPServer.js: TCP/IP server has received 6062112 bytes of data
,2015-11-20T12:46:46.278Z SendDataTCPServer.js: TCP/IP server has received 6078976 bytes of data
,2015-11-20T12:46:46.290Z SendDataTCPServer.js: TCP/IP server has received 6095840 bytes of data
,2015-11-20T12:46:46.303Z SendDataTCPServer.js: TCP/IP server has received 6101792 bytes of data
,2015-11-20T12:46:46.316Z SendDataTCPServer.js: TCP/IP server has received 6120640 bytes of data
,2015-11-20T12:46:46.330Z SendDataTCPServer.js: TCP/IP server has received 6127584 bytes of data
,2015-11-20 13:46:46.527 ThaliTest[1024:782114] server session: connected
2015-11-20 13:46:46.528 ThaliTest[1024:782114] server session: stateChange:1->2 Apple-IpadAir2-1_PT545
,2015-11-20 13:46:46.551 ThaliTest[1024:781290] server relay: connected (to port: 56010)
2015-11-20T12:46:46.557Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:46:46.641Z SendDataTCPServer.js: TCP/IP server has received 6128576 bytes of data
,2015-11-20T12:46:46.658Z SendDataTCPServer.js: TCP/IP server has received 6133536 bytes of data
,2015-11-20T12:46:46.674Z SendDataTCPServer.js: TCP/IP server has received 6139488 bytes of data
,2015-11-20T12:46:46.690Z SendDataTCPServer.js: TCP/IP server has received 6149408 bytes of data
,2015-11-20T12:46:46.706Z SendDataTCPServer.js: TCP/IP server has received 6158336 bytes of data
,2015-11-20T12:46:46.723Z SendDataTCPServer.js: TCP/IP server has received 6167264 bytes of data
,2015-11-20T12:46:46.741Z SendDataTCPServer.js: TCP/IP server has received 6176192 bytes of data
,2015-11-20T12:46:46.755Z SendDataTCPServer.js: TCP/IP server has received 6187104 bytes of data
,2015-11-20T12:46:46.772Z SendDataTCPServer.js: TCP/IP server has received 6200992 bytes of data
,2015-11-20T12:46:46.786Z SendDataTCPServer.js: TCP/IP server has received 6211904 bytes of data
,2015-11-20T12:46:46.800Z SendDataTCPServer.js: TCP/IP server has received 6221824 bytes of data
,2015-11-20T12:46:46.814Z SendDataTCPServer.js: TCP/IP server has received 6235712 bytes of data
,2015-11-20T12:46:46.829Z SendDataTCPServer.js: TCP/IP server has received 6249600 bytes of data
,2015-11-20T12:46:46.843Z SendDataTCPServer.js: TCP/IP server has received 6267456 bytes of data
,2015-11-20T12:46:46.857Z SendDataTCPServer.js: TCP/IP server has received 6284320 bytes of data
,2015-11-20T12:46:46.871Z SendDataTCPServer.js: TCP/IP server has received 6304160 bytes of data
,2015-11-20T12:46:47.127Z SendDataTCPServer.js: TCP/IP server has received 6306144 bytes of data
,2015-11-20T12:46:47.139Z SendDataTCPServer.js: TCP/IP server has received 6310112 bytes of data
,2015-11-20T12:46:47.155Z SendDataTCPServer.js: TCP/IP server has received 6315072 bytes of data
,2015-11-20T12:46:47.169Z SendDataTCPServer.js: TCP/IP server has received 6323008 bytes of data
,2015-11-20T12:46:47.184Z SendDataTCPServer.js: TCP/IP server has received 6326976 bytes of data
,2015-11-20T12:46:47.198Z SendDataTCPServer.js: TCP/IP server has received 6333920 bytes of data
,2015-11-20T12:46:47.214Z SendDataTCPServer.js: TCP/IP server has received 6345824 bytes of data
,2015-11-20T12:46:47.231Z SendDataTCPServer.js: TCP/IP server has received 6357728 bytes of data
,2015-11-20T12:46:47.245Z SendDataTCPServer.js: TCP/IP server has received 6369632 bytes of data
,2015-11-20T12:46:47.261Z SendDataTCPServer.js: TCP/IP server has received 6379552 bytes of data
,2015-11-20T12:46:47.273Z SendDataTCPServer.js: TCP/IP server has received 6390464 bytes of data
,2015-11-20T12:46:47.288Z SendDataTCPServer.js: TCP/IP server has received 6403360 bytes of data
,2015-11-20T12:46:47.301Z SendDataTCPServer.js: TCP/IP server has received 6414272 bytes of data
,2015-11-20T12:46:47.315Z SendDataTCPServer.js: TCP/IP server has received 6427168 bytes of data
,2015-11-20T12:46:47.327Z SendDataTCPServer.js: TCP/IP server has received 6439072 bytes of data
,2015-11-20T12:46:47.365Z SendDataTCPServer.js: TCP/IP server has received 6446016 bytes of data
,2015-11-20T12:46:47.380Z SendDataTCPServer.js: TCP/IP server has received 6456928 bytes of data
,2015-11-20T12:46:47.394Z SendDataTCPServer.js: TCP/IP server has received 6458912 bytes of data
,2015-11-20T12:46:47.655Z SendDataTCPServer.js: TCP/IP server has received 6467840 bytes of data
,2015-11-20T12:46:47.675Z SendDataTCPServer.js: TCP/IP server has received 6482720 bytes of data
,2015-11-20T12:46:47.688Z SendDataTCPServer.js: TCP/IP server has received 6491648 bytes of data
,2015-11-20T12:46:47.704Z SendDataTCPServer.js: TCP/IP server has received 6510496 bytes of data
,2015-11-20T12:46:47.722Z SendDataTCPServer.js: TCP/IP server has received 6517440 bytes of data
,2015-11-20T12:46:47.738Z SendDataTCPServer.js: TCP/IP server has received 6528352 bytes of data
,2015-11-20T12:46:47.754Z SendDataTCPServer.js: TCP/IP server has received 6543232 bytes of data
,2015-11-20T12:46:47.767Z SendDataTCPServer.js: TCP/IP server has received 6559104 bytes of data
,2015-11-20T12:46:47.784Z SendDataTCPServer.js: TCP/IP server has received 6577952 bytes of data
,2015-11-20T12:46:47.798Z SendDataTCPServer.js: TCP/IP server has received 6590848 bytes of data
,2015-11-20T12:46:47.812Z SendDataTCPServer.js: TCP/IP server has received 6601760 bytes of data
,2015-11-20T12:46:47.827Z SendDataTCPServer.js: TCP/IP server has received 6616640 bytes of data
,2015-11-20T12:46:47.843Z SendDataTCPServer.js: TCP/IP server has received 6634496 bytes of data
,2015-11-20T12:46:47.857Z SendDataTCPServer.js: TCP/IP server has received 6645408 bytes of data
,2015-11-20T12:46:47.882Z SendDataTCPServer.js: TCP/IP server has received 6649376 bytes of data
,2015-11-20T12:46:47.895Z SendDataTCPServer.js: TCP/IP server has received 6707904 bytes of data
,2015-11-20T12:46:47.911Z SendDataTCPServer.js: TCP/IP server has received 6727744 bytes of data
,2015-11-20T12:46:47.926Z SendDataTCPServer.js: TCP/IP server has received 6728736 bytes of data
,2015-11-20T12:46:48.176Z SendDataTCPServer.js: TCP/IP server has received 6732704 bytes of data
,2015-11-20T12:46:48.194Z SendDataTCPServer.js: TCP/IP server has received 6738656 bytes of data
,2015-11-20T12:46:48.207Z SendDataTCPServer.js: TCP/IP server has received 6745600 bytes of data
,2015-11-20T12:46:48.223Z SendDataTCPServer.js: TCP/IP server has received 6753536 bytes of data
,2015-11-20T12:46:48.236Z SendDataTCPServer.js: TCP/IP server has received 6758496 bytes of data
,2015-11-20T12:46:48.249Z SendDataTCPServer.js: TCP/IP server has received 6764448 bytes of data
,2015-11-20T12:46:48.265Z SendDataTCPServer.js: TCP/IP server has received 6775360 bytes of data
,2015-11-20T12:46:48.278Z SendDataTCPServer.js: TCP/IP server has received 6784288 bytes of data
,2015-11-20T12:46:48.290Z SendDataTCPServer.js: TCP/IP server has received 6793216 bytes of data
,2015-11-20T12:46:48.305Z SendDataTCPServer.js: TCP/IP server has received 6809088 bytes of data
,2015-11-20T12:46:48.319Z SendDataTCPServer.js: TCP/IP server has received 6824960 bytes of data
,2015-11-20T12:46:48.335Z SendDataTCPServer.js: TCP/IP server has received 6841824 bytes of data
,2015-11-20T12:46:48.351Z SendDataTCPServer.js: TCP/IP server has received 6857696 bytes of data
,2015-11-20T12:46:48.366Z SendDataTCPServer.js: TCP/IP server has received 6871584 bytes of data
,2015-11-20T12:46:48.378Z SendDataTCPServer.js: TCP/IP server has received 6883488 bytes of data
,2015-11-20T12:46:48.391Z SendDataTCPServer.js: TCP/IP server has received 6899360 bytes of data
,2015-11-20T12:46:48.407Z SendDataTCPServer.js: TCP/IP server has received 6912256 bytes of data
,2015-11-20T12:46:48.421Z SendDataTCPServer.js: TCP/IP server has received 6927136 bytes of data
,2015-11-20T12:46:48.435Z SendDataTCPServer.js: TCP/IP server has received 6940032 bytes of data
,2015-11-20T12:46:48.699Z SendDataTCPServer.js: TCP/IP server has received 6944000 bytes of data
,2015-11-20T12:46:48.714Z SendDataTCPServer.js: TCP/IP server has received 6950944 bytes of data
,2015-11-20T12:46:48.730Z SendDataTCPServer.js: TCP/IP server has received 6958880 bytes of data
,2015-11-20T12:46:48.744Z SendDataTCPServer.js: TCP/IP server has received 6967808 bytes of data
,2015-11-20T12:46:48.762Z SendDataTCPServer.js: TCP/IP server has received 6975744 bytes of data
,2015-11-20T12:46:48.776Z SendDataTCPServer.js: TCP/IP server has received 6981696 bytes of data
,2015-11-20T12:46:48.790Z SendDataTCPServer.js: TCP/IP server has received 6982688 bytes of data
,2015-11-20T12:46:48.804Z SendDataTCPServer.js: TCP/IP server has received 6995584 bytes of data
,2015-11-20T12:46:48.818Z SendDataTCPServer.js: TCP/IP server has received 7007488 bytes of data
,2015-11-20T12:46:48.831Z SendDataTCPServer.js: TCP/IP server has received 7020384 bytes of data
,2015-11-20T12:46:48.845Z SendDataTCPServer.js: TCP/IP server has received 7033280 bytes of data
,2015-11-20T12:46:48.861Z SendDataTCPServer.js: TCP/IP server has received 7045184 bytes of data
,2015-11-20T12:46:48.875Z SendDataTCPServer.js: TCP/IP server has received 7055104 bytes of data
,2015-11-20T12:46:48.889Z SendDataTCPServer.js: TCP/IP server has received 7071968 bytes of data
,2015-11-20T12:46:48.901Z SendDataTCPServer.js: TCP/IP server has received 7091808 bytes of data
,2015-11-20T12:46:48.917Z SendDataTCPServer.js: TCP/IP server has received 7109664 bytes of data
,2015-11-20T12:46:48.931Z SendDataTCPServer.js: TCP/IP server has received 7127520 bytes of data
,2015-11-20T12:46:48.945Z SendDataTCPServer.js: TCP/IP server has received 7146368 bytes of data
,2015-11-20T12:46:48.957Z SendDataTCPServer.js: TCP/IP server has received 7150336 bytes of data
,2015-11-20T12:46:49.217Z SendDataTCPServer.js: TCP/IP server has received 7152384 bytes of data
,2015-11-20T12:46:49.235Z SendDataTCPServer.js: TCP/IP server has received 7163232 bytes of data
,2015-11-20T12:46:49.251Z SendDataTCPServer.js: TCP/IP server has received 7174144 bytes of data
,2015-11-20T12:46:49.269Z SendDataTCPServer.js: TCP/IP server has received 7187040 bytes of data
,2015-11-20T12:46:49.282Z SendDataTCPServer.js: TCP/IP server has received 7192992 bytes of data
,2015-11-20T12:46:49.299Z SendDataTCPServer.js: TCP/IP server has received 7195968 bytes of data
,2015-11-20T12:46:49.313Z SendDataTCPServer.js: TCP/IP server has received 7206880 bytes of data
,2015-11-20T12:46:49.328Z SendDataTCPServer.js: TCP/IP server has received 7223744 bytes of data
,2015-11-20T12:46:49.340Z SendDataTCPServer.js: TCP/IP server has received 7237632 bytes of data
,2015-11-20T12:46:49.355Z SendDataTCPServer.js: TCP/IP server has received 7256480 bytes of data
,2015-11-20T12:46:49.371Z SendDataTCPServer.js: TCP/IP server has received 7272352 bytes of data
,2015-11-20T12:46:49.384Z SendDataTCPServer.js: TCP/IP server has received 7286240 bytes of data
,2015-11-20T12:46:49.399Z SendDataTCPServer.js: TCP/IP server has received 7303104 bytes of data
,2015-11-20T12:46:49.414Z SendDataTCPServer.js: TCP/IP server has received 7320960 bytes of data
,2015-11-20T12:46:49.428Z SendDataTCPServer.js: TCP/IP server has received 7338816 bytes of data
,2015-11-20T12:46:49.441Z SendDataTCPServer.js: TCP/IP server has received 7353696 bytes of data
,2015-11-20T12:46:49.454Z SendDataTCPServer.js: TCP/IP server has received 7371552 bytes of data
,2015-11-20T12:46:49.468Z SendDataTCPServer.js: TCP/IP server has received 7388416 bytes of data
,2015-11-20T12:46:49.481Z SendDataTCPServer.js: TCP/IP server has received 7413216 bytes of data
,2015-11-20T12:46:49.496Z SendDataTCPServer.js: TCP/IP server has received 7415200 bytes of data
,2015-11-20T12:46:49.748Z SendDataTCPServer.js: TCP/IP server has received 7418176 bytes of data
,2015-11-20T12:46:49.763Z SendDataTCPServer.js: TCP/IP server has received 7432064 bytes of data
,2015-11-20T12:46:49.784Z SendDataTCPServer.js: TCP/IP server has received 7442976 bytes of data
,2015-11-20T12:46:49.799Z SendDataTCPServer.js: TCP/IP server has received 7443968 bytes of data
,2015-11-20T12:46:49.825Z SendDataTCPServer.js: TCP/IP server has received 7452896 bytes of data
,2015-11-20T12:46:49.840Z SendDataTCPServer.js: TCP/IP server has received 7463808 bytes of data
,2015-11-20T12:46:49.854Z SendDataTCPServer.js: TCP/IP server has received 7484640 bytes of data
,2015-11-20T12:46:49.869Z SendDataTCPServer.js: TCP/IP server has received 7495552 bytes of data
,2015-11-20T12:46:49.883Z SendDataTCPServer.js: TCP/IP server has received 7513408 bytes of data
,2015-11-20T12:46:49.896Z SendDataTCPServer.js: TCP/IP server has received 7523328 bytes of data
,2015-11-20T12:46:49.909Z SendDataTCPServer.js: TCP/IP server has received 7539264 bytes of data
,2015-11-20T12:46:49.924Z SendDataTCPServer.js: TCP/IP server has received 7555072 bytes of data
,2015-11-20T12:46:49.939Z SendDataTCPServer.js: TCP/IP server has received 7565984 bytes of data
,2015-11-20T12:46:49.951Z SendDataTCPServer.js: TCP/IP server has received 7582848 bytes of data
,2015-11-20T12:46:49.967Z SendDataTCPServer.js: TCP/IP server has received 7600704 bytes of data
,2015-11-20T12:46:49.980Z SendDataTCPServer.js: TCP/IP server has received 7616576 bytes of data
,2015-11-20T12:46:49.994Z SendDataTCPServer.js: TCP/IP server has received 7634432 bytes of data
,2015-11-20T12:46:50.007Z SendDataTCPServer.js: TCP/IP server has received 7655264 bytes of data
,2015-11-20T12:46:50.024Z SendDataTCPServer.js: TCP/IP server has received 7680064 bytes of data
,2015-11-20T12:46:50.273Z SendDataTCPServer.js: TCP/IP server has received 7684032 bytes of data
,2015-11-20T12:46:50.288Z SendDataTCPServer.js: TCP/IP server has received 7687008 bytes of data
,2015-11-20T12:46:50.320Z SendDataTCPServer.js: TCP/IP server has received 7689984 bytes of data
,2015-11-20T12:46:50.336Z SendDataTCPServer.js: TCP/IP server has received 7704864 bytes of data
,2015-11-20T12:46:50.353Z SendDataTCPServer.js: TCP/IP server has received 7712800 bytes of data
,2015-11-20T12:46:50.369Z SendDataTCPServer.js: TCP/IP server has received 7727680 bytes of data
,2015-11-20T12:46:50.384Z SendDataTCPServer.js: TCP/IP server has received 7746528 bytes of data
,2015-11-20T12:46:50.399Z SendDataTCPServer.js: TCP/IP server has received 7763392 bytes of data
,2015-11-20T12:46:50.415Z SendDataTCPServer.js: TCP/IP server has received 7776288 bytes of data
,2015-11-20T12:46:50.432Z SendDataTCPServer.js: TCP/IP server has received 7795136 bytes of data
,2015-11-20T12:46:50.448Z SendDataTCPServer.js: TCP/IP server has received 7811008 bytes of data
,2015-11-20T12:46:50.461Z SendDataTCPServer.js: TCP/IP server has received 7826880 bytes of data
,2015-11-20T12:46:50.473Z SendDataTCPServer.js: TCP/IP server has received 7840768 bytes of data
,2015-11-20T12:46:50.485Z SendDataTCPServer.js: TCP/IP server has received 7854656 bytes of data
,2015-11-20T12:46:50.498Z SendDataTCPServer.js: TCP/IP server has received 7868544 bytes of data
,2015-11-20T12:46:50.513Z SendDataTCPServer.js: TCP/IP server has received 7870528 bytes of data
,2015-11-20T12:46:50.527Z SendDataTCPServer.js: TCP/IP server has received 7889376 bytes of data
,2015-11-20T12:46:50.540Z SendDataTCPServer.js: TCP/IP server has received 7893344 bytes of data
,2015-11-20T12:46:50.802Z SendDataTCPServer.js: TCP/IP server has received 7904256 bytes of data
,2015-11-20T12:46:50.818Z SendDataTCPServer.js: TCP/IP server has received 7917152 bytes of data
,2015-11-20 13:46:50.823 ThaliTest[1024:782114] client session: not connected Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:46:50.824 ThaliTest[1024:782114] client session: onLinkFailure: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:46:50.825 ThaliTest[1,024:782114] client session: disconnect
2015-11-20 13:46:50.826 ThaliTest[1024:782114] client session: stateChange:1->0 Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:46:50.827 ThaliTest[1024:782114] client session: fireConnectCallback: Apple-Iphone5s-1_PT,497.PdI1bg==
2015-11-20 13:46:50.828 ThaliTest[1024:782114] jxcore: connect: fail: Peer disconnected
,2015-11-20T12:46:50.832Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-11-20T12:46:50.833Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-20T12:46:50.835Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:46:50.848Z SendDataTCPServer.js: TCP/IP server has received 7920128 bytes of data
,2015-11-20T12:46:50.862Z SendDataTCPServer.js: TCP/IP server has received 7925088 bytes of data
,2015-11-20T12:46:50.876Z SendDataTCPServer.js: TCP/IP server has received 7932032 bytes of data
,2015-11-20T12:46:50.891Z SendDataTCPServer.js: TCP/IP server has received 7941952 bytes of data
,2015-11-20T12:46:50.905Z SendDataTCPServer.js: TCP/IP server has received 7952864 bytes of data
,2015-11-20T12:46:50.918Z SendDataTCPServer.js: TCP/IP server has received 7967744 bytes of data
,2015-11-20T12:46:50.932Z SendDataTCPServer.js: TCP/IP server has received 7981632 bytes of data
,2015-11-20T12:46:50.947Z SendDataTCPServer.js: TCP/IP server has received 7996512 bytes of data
,2015-11-20T12:46:50.961Z SendDataTCPServer.js: TCP/IP server has received 8011392 bytes of data
,2015-11-20T12:46:50.976Z SendDataTCPServer.js: TCP/IP server has received 8031232 bytes of data
,2015-11-20T12:46:50.992Z SendDataTCPServer.js: TCP/IP server has received 8050080 bytes of data
,2015-11-20T12:46:51.004Z SendDataTCPServer.js: TCP/IP server has received 8053056 bytes of data
,2015-11-20T12:46:51.042Z SendDataTCPServer.js: TCP/IP server has received 8064960 bytes of data
,2015-11-20T12:46:51.056Z SendDataTCPServer.js: TCP/IP server has received 8066944 bytes of data
,2015-11-20T12:46:51.318Z SendDataTCPServer.js: TCP/IP server has received 10808 bytes of data
,2015-11-20T12:46:51.336Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-11-20T12:46:51.369Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-11-20T12:46:51.404Z SendDataTCPServer.js: TCP/IP server has received 137970 bytes of data
,2015-11-20T12:46:51.419Z SendDataTCPServer.js: TCP/IP server has received 153300 bytes of data
,2015-11-20T12:46:51.437Z SendDataTCPServer.js: TCP/IP server has received 164250 bytes of data
,2015-11-20T12:46:51.439Z SendDataTCPServer.js: TCP/IP server has received 8080832 bytes of data
,2015-11-20T12:46:51.453Z SendDataTCPServer.js: TCP/IP server has received 170820 bytes of data
,2015-11-20T12:46:51.454Z SendDataTCPServer.js: TCP/IP server has received 8100672 bytes of data
,2015-11-20T12:46:51.469Z SendDataTCPServer.js: TCP/IP server has received 175200 bytes of data
,2015-11-20T12:46:51.470Z SendDataTCPServer.js: TCP/IP server has received 8119520 bytes of data
,2015-11-20T12:46:51.485Z SendDataTCPServer.js: TCP/IP server has received 186150 bytes of data
,2015-11-20T12:46:51.486Z SendDataTCPServer.js: TCP/IP server has received 8120512 bytes of data
,2015-11-20T12:46:51.499Z SendDataTCPServer.js: TCP/IP server has received 205860 bytes of data
,2015-11-20T12:46:51.502Z SendDataTCPServer.js: TCP/IP server has received 8123488 bytes of data
,2015-11-20T12:46:51.513Z SendDataTCPServer.js: TCP/IP server has received 225570 bytes of data
,2015-11-20T12:46:51.515Z SendDataTCPServer.js: TCP/IP server has received 8124480 bytes of data
,2015-11-20T12:46:51.528Z SendDataTCPServer.js: TCP/IP server has received 236520 bytes of data
,2015-11-20T12:46:51.529Z SendDataTCPServer.js: TCP/IP server has received 8129440 bytes of data
,2015-11-20T12:46:51.710Z SendDataTCPServer.js: TCP/IP server has received 243090 bytes of data
,2015-11-20T12:46:51.726Z SendDataTCPServer.js: TCP/IP server has received 260610 bytes of data
,2015-11-20T12:46:51.742Z SendDataTCPServer.js: TCP/IP server has received 278130 bytes of data
,2015-11-20T12:46:51.758Z SendDataTCPServer.js: TCP/IP server has received 280320 bytes of data
,2015-11-20T12:46:51.773Z SendDataTCPServer.js: TCP/IP server has received 289080 bytes of data
,2015-11-20T12:46:51.788Z SendDataTCPServer.js: TCP/IP server has received 302220 bytes of data
,2015-11-20T12:46:51.838Z SendDataTCPServer.js: TCP/IP server has received 304410 bytes of data
,2015-11-20T12:46:51.853Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:46:51.854Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:46:51.855Z SendDataTCPServer.js: TCP/IP serv,er has received 313170 bytes of data
,2015-11-20T12:46:51.868Z SendDataTCPServer.js: TCP/IP server has received 324120 bytes of data
,2015-11-20T12:46:51.886Z SendDataTCPServer.js: TCP/IP server has received 337260 bytes of data
,2015-11-20T12:46:51.901Z SendDataTCPServer.js: TCP/IP server has received 361350 bytes of data
,2015-11-20T12:46:52.007Z SendDataTCPServer.js: TCP/IP server has received 363540 bytes of data
,2015-11-20T12:46:52.022Z SendDataTCPServer.js: TCP/IP server has received 372300 bytes of data
,2015-11-20T12:46:52.043Z SendDataTCPServer.js: TCP/IP server has received 392010 bytes of data
,2015-11-20T12:46:52.048Z SendDataTCPServer.js: TCP/IP server has received 8133408 bytes of data
,2015-11-20T12:46:52.068Z SendDataTCPServer.js: TCP/IP server has received 394200 bytes of data
,2015-11-20T12:46:52.069Z SendDataTCPServer.js: TCP/IP server has received 8143328 bytes of data
,2015-11-20T12:46:52.090Z SendDataTCPServer.js: TCP/IP server has received 8154240 bytes of data
,2015-11-20T12:46:52.107Z SendDataTCPServer.js: TCP/IP server has received 8158208 bytes of data
,2015-11-20T12:46:52.110Z SendDataTCPServer.js: TCP/IP server has received 409530 bytes of data
,2015-11-20T12:46:52.128Z SendDataTCPServer.js: TCP/IP server has received 8169120 bytes of data
,2015-11-20T12:46:52.130Z SendDataTCPServer.js: TCP/IP server has received 429240 bytes of data
,2015-11-20T12:46:52.146Z SendDataTCPServer.js: TCP/IP server has received 446760 bytes of data
,2015-11-20T12:46:52.173Z SendDataTCPServer.js: TCP/IP server has received 451140 bytes of data
,2015-11-20T12:46:52.188Z SendDataTCPServer.js: TCP/IP server has received 455520 bytes of data
,2015-11-20T12:46:52.202Z SendDataTCPServer.js: TCP/IP server has received 459900 bytes of data
,2015-11-20T12:46:52.366Z SendDataTCPServer.js: TCP/IP server has received 8171104 bytes of data
,2015-11-20T12:46:52.380Z SendDataTCPServer.js: TCP/IP server has received 8180032 bytes of data
,2015-11-20T12:46:52.396Z SendDataTCPServer.js: TCP/IP server has received 8191936 bytes of data
,2015-11-20T12:46:52.715Z SendDataTCPServer.js: TCP/IP server has received 8192928 bytes of data
,2015-11-20T12:46:52.729Z SendDataTCPServer.js: TCP/IP server has received 8198880 bytes of data
,2015-11-20T12:46:52.730Z SendDataTCPServer.js: TCP/IP server has received 462090 bytes of data
,2015-11-20T12:46:52.746Z SendDataTCPServer.js: TCP/IP server has received 8207808 bytes of data
,2015-11-20T12:46:52.761Z SendDataTCPServer.js: TCP/IP server has received 8210784 bytes of data
,2015-11-20T12:46:52.762Z SendDataTCPServer.js: TCP/IP server has received 468660 bytes of data
,2015-11-20T12:46:52.776Z SendDataTCPServer.js: TCP/IP server has received 8211776 bytes of data
2015-11-20T12:46:52.778Z SendDataTCPServer.js: TCP/IP server has received 470850 bytes of data
,2015-11-20T12:46:52.793Z SendDataTCPServer.js: TCP/IP server has received 488370 bytes of data
,2015-11-20T12:46:52.807Z SendDataTCPServer.js: TCP/IP server has received 505890 bytes of data
,2015-11-20T12:46:52.849Z SendDataTCPServer.js: TCP/IP server has received 516556 bytes of data
,2015-11-20 13:46:52.864 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:46:52.865 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:46:52.865Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg=,=
2015-11-20T12:46:52.866Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT497.PdI1bg== with availability status: true
,2015-11-20T12:46:52.866Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:46:52.867Z SendDataConnector.js: do connect now
2015-11-20 13:46:52.867 ThaliTest[1024:781408] jxcore: connect Apple-Iphone5s-1_PT497.,PdI1bg==
,2015-11-20 13:46:52.869 ThaliTest[1024:781408] client session: connect
,2015-11-20 13:46:52.869 ThaliTest[1024:781408] client session: stateChange:0->1 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:46:52.903Z SendDataTCPServer.js: TCP/IP server has received 562830 bytes of data
,2015-11-20T12:46:52.954Z SendDataTCPServer.js: TCP/IP server has received 586920 bytes of data
,2015-11-20T12:46:52.995Z SendDataTCPServer.js: TCP/IP server has received 588968 bytes of data
,2015-11-20T12:46:53.007Z SendDataTCPServer.js: TCP/IP server has received 591300 bytes of data
,2015-11-20T12:46:53.155Z SendDataTCPServer.js: TCP/IP server has received 8214752 bytes of data
,2015-11-20T12:46:53.173Z SendDataTCPServer.js: TCP/IP server has received 8225664 bytes of data
,2015-11-20T12:46:53.189Z SendDataTCPServer.js: TCP/IP server has received 8241536 bytes of data
,2015-11-20T12:46:53.203Z SendDataTCPServer.js: TCP/IP server has received 8257408 bytes of data
,2015-11-20T12:46:53.215Z SendDataTCPServer.js: TCP/IP server has received 8261376 bytes of data
,2015-11-20T12:46:53.216Z SendDataTCPServer.js: TCP/IP server has received 600060 bytes of data
,2015-11-20T12:46:53.288Z SendDataTCPServer.js: TCP/IP server has received 608820 bytes of data
,2015-11-20T12:46:53.327Z SendDataTCPServer.js: TCP/IP server has received 624150 bytes of data
,2015-11-20T12:46:53.345Z SendDataTCPServer.js: TCP/IP server has received 630720 bytes of data
,2015-11-20T12:46:53.377Z SendDataTCPServer.js: TCP/IP server has received 643860 bytes of data
,2015-11-20T12:46:53.395Z SendDataTCPServer.js: TCP/IP server has received 654810 bytes of data
,2015-11-20T12:46:53.416Z SendDataTCPServer.js: TCP/IP server has received 659190 bytes of data
,2015-11-20T12:46:53.430Z SendDataTCPServer.js: TCP/IP server has received 670140 bytes of data
,2015-11-20T12:46:53.447Z SendDataTCPServer.js: TCP/IP server has received 676710 bytes of data
,2015-11-20T12:46:53.451Z SendDataTCPServer.js: TCP/IP server has received 8270304 bytes of data
,2015-11-20T12:46:53.470Z SendDataTCPServer.js: TCP/IP server has received 696420 bytes of data
,2015-11-20T12:46:53.478Z SendDataTCPServer.js: TCP/IP server has received 8274272 bytes of data
,2015-11-20T12:46:53.492Z SendDataTCPServer.js: TCP/IP server has received 700800 bytes of data
,2015-11-20T12:46:53.588Z SendDataTCPServer.js: TCP/IP server has received 702990 bytes of data
,2015-11-20T12:46:53.921Z SendDataTCPServer.js: TCP/IP server has received 711750 bytes of data
,2015-11-20T12:46:53.941Z SendDataTCPServer.js: TCP/IP server has received 720510 bytes of data
,2015-11-20T12:46:53.955Z SendDataTCPServer.js: TCP/IP server has received 731460 bytes of data
,2015-11-20T12:46:54.130Z SendDataTCPServer.js: TCP/IP server has received 8279232 bytes of data
,2015-11-20T12:46:54.134Z SendDataTCPServer.js: TCP/IP server has received 742410 bytes of data
,2015-11-20T12:46:54.153Z SendDataTCPServer.js: TCP/IP server has received 8287168 bytes of data
2015-11-20T12:46:54.156Z SendDataTCPServer.js: TCP/IP server has received 755550 bytes of data
2015-11-20T12:46:54.174Z SendDataTCPServer.js: TCP/IP server ha,s received 8293120 bytes of data
2015-11-20T12:46:54.174Z SendDataTCPServer.js: TCP/IP server has received 766500 bytes of data
,2015-11-20T12:46:54.192Z SendDataTCPServer.js: TCP/IP server has received 8298080 bytes of data
2015-11-20T12:46:54.194Z SendDataTCPServer.js: TCP/IP server has received 788116 bytes of data
,2015-11-20T12:46:54.212Z SendDataTCPServer.js: TCP/IP server has received 8316928 bytes of data
,2015-11-20T12:46:54.222Z SendDataTCPServer.js: TCP/IP server has received 799350 bytes of data
,2015-11-20T12:46:54.240Z SendDataTCPServer.js: TCP/IP server has received 8341728 bytes of data
,2015-11-20T12:46:54.341Z SendDataTCPServer.js: TCP/IP server has received 808110 bytes of data
,2015-11-20T12:46:54.359Z SendDataTCPServer.js: TCP/IP server has received 819060 bytes of data
,2015-11-20T12:46:54.374Z SendDataTCPServer.js: TCP/IP server has received 832200 bytes of data
,2015-11-20T12:46:54.390Z SendDataTCPServer.js: TCP/IP server has received 845340 bytes of data
,2015-11-20T12:46:54.410Z SendDataTCPServer.js: TCP/IP server has received 851910 bytes of data
,2015-11-20T12:46:54.422Z SendDataTCPServer.js: TCP/IP server has received 856290 bytes of data
,2015-11-20T12:46:54.436Z SendDataTCPServer.js: TCP/IP server has received 867240 bytes of data
,2015-11-20T12:46:54.450Z SendDataTCPServer.js: TCP/IP server has received 889140 bytes of data
,2015-11-20T12:46:54.467Z SendDataTCPServer.js: TCP/IP server has received 906660 bytes of data
,2015-11-20T12:46:54.484Z SendDataTCPServer.js: TCP/IP server has received 926370 bytes of data
,2015-11-20T12:46:54.508Z SendDataTCPServer.js: TCP/IP server has received 930750 bytes of data
,2015-11-20T12:46:54.512Z SendDataTCPServer.js: TCP/IP server has received 8363552 bytes of data
,2015-11-20T12:46:54.533Z SendDataTCPServer.js: TCP/IP server has received 932940 bytes of data
,2015-11-20T12:46:54.539Z SendDataTCPServer.js: TCP/IP server has received 8387360 bytes of data
,2015-11-20T12:46:54.558Z SendDataTCPServer.js: TCP/IP server has received 939510 bytes of data
,2015-11-20T12:46:54.561Z SendDataTCPServer.js: TCP/IP server has received 8420096 bytes of data
,2015-11-20T12:46:54.588Z SendDataTCPServer.js: TCP/IP server has received 965790 bytes of data
,2015-11-20T12:46:54.609Z SendDataTCPServer.js: TCP/IP server has received 8438944 bytes of data
,2015-11-20T12:46:54.642Z SendDataTCPServer.js: TCP/IP server has received 1096862 bytes of data
,2015-11-20T12:46:54.653Z SendDataTCPServer.js: TCP/IP server has received 1227934 bytes of data
,2015-11-20T12:46:54.660Z SendDataTCPServer.js: TCP/IP server has received 1311810 bytes of data
,2015-11-20T12:46:54.680Z SendDataTCPServer.js: TCP/IP server has received 1322760 bytes of data
,2015-11-20T12:46:54.682Z SendDataTCPServer.js: TCP/IP server has received 8463744 bytes of data
,2015-11-20T12:46:54.695Z SendDataTCPServer.js: TCP/IP server has received 1401660 bytes of data
,2015-11-20T12:46:54.701Z SendDataTCPServer.js: TCP/IP server has received 8465728 bytes of data
,2015-11-20T12:46:54.715Z SendDataTCPServer.js: TCP/IP server has received 1454160 bytes of data
,2015-11-20T12:46:54.718Z SendDataTCPServer.js: TCP/IP server has received 8501440 bytes of data
,2015-11-20T12:46:54.732Z SendDataTCPServer.js: TCP/IP server has received 1504530 bytes of data
,2015-11-20T12:46:54.745Z SendDataTCPServer.js: TCP/IP server has received 1535190 bytes of data
,2015-11-20T12:46:54.759Z SendDataTCPServer.js: TCP/IP server has received 1585560 bytes of data
,2015-11-20T12:46:54.772Z SendDataTCPServer.js: TCP/IP server has received 1611840 bytes of data
,2015-11-20T12:46:54.790Z SendDataTCPServer.js: TCP/IP server has received 1627170 bytes of data
,2015-11-20T12:46:54.792Z SendDataTCPServer.js: TCP/IP server has received 8526240 bytes of data
,2015-11-20T12:46:54.806Z SendDataTCPServer.js: TCP/IP server has received 1666448 bytes of data
,2015-11-20T12:46:54.808Z SendDataTCPServer.js: TCP/IP server has received 8528224 bytes of data
,2015-11-20T12:46:54.820Z SendDataTCPServer.js: TCP/IP server has received 1708200 bytes of data
,2015-11-20T12:46:54.833Z SendDataTCPServer.js: TCP/IP server has received 1743240 bytes of data
,2015-11-20T12:46:54.847Z SendDataTCPServer.js: TCP/IP server has received 1767330 bytes of data
,2015-11-20T12:46:54.853Z SendDataTCPServer.js: TCP/IP server has received 8536160 bytes of data
,2015-11-20T12:46:54.865Z SendDataTCPServer.js: TCP/IP server has received 1793610 bytes of data
,2015-11-20T12:46:54.868Z SendDataTCPServer.js: TCP/IP server has received 8546080 bytes of data
,2015-11-20T12:46:54.882Z SendDataTCPServer.js: TCP/IP server has received 1822080 bytes of data
,2015-11-20T12:46:54.885Z SendDataTCPServer.js: TCP/IP server has received 8553024 bytes of data
,2015-11-20T12:46:54.901Z SendDataTCPServer.js: TCP/IP server has received 1824270 bytes of data
,2015-11-20T12:46:54.905Z SendDataTCPServer.js: TCP/IP server has received 8585760 bytes of data
,2015-11-20T12:46:54.920Z SendDataTCPServer.js: TCP/IP server has received 1833030 bytes of data
,2015-11-20T12:46:54.921Z SendDataTCPServer.js: TCP/IP server has received 8612544 bytes of data
,2015-11-20T12:46:54.936Z SendDataTCPServer.js: TCP/IP server has received 1892160 bytes of data
,2015-11-20T12:46:54.953Z SendDataTCPServer.js: TCP/IP server has received 1940340 bytes of data
,2015-11-20T12:46:54.955Z SendDataTCPServer.js: TCP/IP server has received 8613536 bytes of data
,2015-11-20T12:46:54.968Z SendDataTCPServer.js: TCP/IP server has received 1957860 bytes of data
,2015-11-20T12:46:54.969Z SendDataTCPServer.js: TCP/IP server has received 8644288 bytes of data
,2015-11-20T12:46:54.985Z SendDataTCPServer.js: TCP/IP server has received 1981950 bytes of data
,2015-11-20T12:46:54.986Z SendDataTCPServer.js: TCP/IP server has received 8674048 bytes of data
,2015-11-20T12:46:54.999Z SendDataTCPServer.js: TCP/IP server has received 2001660 bytes of data
,2015-11-20T12:46:55.001Z SendDataTCPServer.js: TCP/IP server has received 8691904 bytes of data
,2015-11-20T12:46:55.015Z SendDataTCPServer.js: TCP/IP server has received 2019180 bytes of data
,2015-11-20T12:46:55.017Z SendDataTCPServer.js: TCP/IP server has received 8710752 bytes of data
,2015-11-20T12:46:55.029Z SendDataTCPServer.js: TCP/IP server has received 2032320 bytes of data
2015-11-20T12:46:55.030Z SendDataTCPServer.js: TCP/IP server has received 8728608 bytes of data
,2015-11-20T12:46:55.043Z SendDataTCPServer.js: TCP/IP server has received 2058600 bytes of data
2015-11-20T12:46:55.045Z SendDataTCPServer.js: TCP/IP server has received 8747456 bytes of data
,2015-11-20T12:46:55.058Z SendDataTCPServer.js: TCP/IP server has received 2073930 bytes of data
,2015-11-20T12:46:55.059Z SendDataTCPServer.js: TCP/IP server has received 8766304 bytes of data
,2015-11-20T12:46:55.074Z SendDataTCPServer.js: TCP/IP server has received 2117730 bytes of data
,2015-11-20T12:46:55.089Z SendDataTCPServer.js: TCP/IP server has received 2130870 bytes of data
,2015-11-20T12:46:55.091Z SendDataTCPServer.js: TCP/IP server has received 8777216 bytes of data
,2015-11-20T12:46:55.105Z SendDataTCPServer.js: TCP/IP server has received 2159340 bytes of data
,2015-11-20T12:46:55.106Z SendDataTCPServer.js: TCP/IP server has received 8787136 bytes of data
,2015-11-20T12:46:55.123Z SendDataTCPServer.js: TCP/IP server has received 2205330 bytes of data
,2015-11-20T12:46:55.126Z SendDataTCPServer.js: TCP/IP server has received 8797056 bytes of data
,2015-11-20T12:46:55.138Z SendDataTCPServer.js: TCP/IP server has received 2251320 bytes of data
,2015-11-20T12:46:55.140Z SendDataTCPServer.js: TCP/IP server has received 8802016 bytes of data
,2015-11-20T12:46:55.152Z SendDataTCPServer.js: TCP/IP server has received 2279506 bytes of data
,2015-11-20T12:46:55.154Z SendDataTCPServer.js: TCP/IP server has received 8810944 bytes of data
,2015-11-20T12:46:55.168Z SendDataTCPServer.js: TCP/IP server has received 2321400 bytes of data
,2015-11-20T12:46:55.171Z SendDataTCPServer.js: TCP/IP server has received 8818880 bytes of data
,2015-11-20T12:46:55.183Z SendDataTCPServer.js: TCP/IP server has received 2349870 bytes of data
,2015-11-20T12:46:55.185Z SendDataTCPServer.js: TCP/IP server has received 8832768 bytes of data
,2015-11-20T12:46:55.198Z SendDataTCPServer.js: TCP/IP server has received 2384910 bytes of data
,2015-11-20T12:46:55.206Z SendDataTCPServer.js: TCP/IP server has received 8853600 bytes of data
,2015-11-20T12:46:55.220Z SendDataTCPServer.js: TCP/IP server has received 2387100 bytes of data
,2015-11-20T12:46:55.221Z SendDataTCPServer.js: TCP/IP server has received 8880384 bytes of data
,2015-11-20T12:46:55.241Z SendDataTCPServer.js: TCP/IP server has received 2398050 bytes of data
,2015-11-20T12:46:55.245Z SendDataTCPServer.js: TCP/IP server has received 8923040 bytes of data
,2015-11-20T12:46:55.260Z SendDataTCPServer.js: TCP/IP server has received 2409000 bytes of data
,2015-11-20T12:46:55.261Z SendDataTCPServer.js: TCP/IP server has received 8948832 bytes of data
,2015-11-20T12:46:55.276Z SendDataTCPServer.js: TCP/IP server has received 2430900 bytes of data
,2015-11-20T12:46:55.280Z SendDataTCPServer.js: TCP/IP server has received 8975616 bytes of data
,2015-11-20T12:46:55.298Z SendDataTCPServer.js: TCP/IP server has received 2446230 bytes of data
,2015-11-20T12:46:55.300Z SendDataTCPServer.js: TCP/IP server has received 9000416 bytes of data
,2015-11-20T12:46:55.316Z SendDataTCPServer.js: TCP/IP server has received 2452800 bytes of data
,2015-11-20T12:46:55.316Z SendDataTCPServer.js: TCP/IP server has received 9025216 bytes of data
,2015-11-20T12:46:55.331Z SendDataTCPServer.js: TCP/IP server has received 2486988 bytes of data
,2015-11-20T12:46:55.333Z SendDataTCPServer.js: TCP/IP server has received 9036128 bytes of data
,2015-11-20T12:46:55.348Z SendDataTCPServer.js: TCP/IP server has received 2579820 bytes of data
,2015-11-20T12:46:55.350Z SendDataTCPServer.js: TCP/IP server has received 9039104 bytes of data
,2015-11-20T12:46:55.363Z SendDataTCPServer.js: TCP/IP server has received 2590770 bytes of data
,2015-11-20T12:46:55.364Z SendDataTCPServer.js: TCP/IP server has received 9063904 bytes of data
,2015-11-20T12:46:55.377Z SendDataTCPServer.js: TCP/IP server has received 2647710 bytes of data
,2015-11-20T12:46:55.381Z SendDataTCPServer.js: TCP/IP server has received 9072832 bytes of data
,2015-11-20T12:46:55.393Z SendDataTCPServer.js: TCP/IP server has received 9097632 bytes of data
,2015-11-20T12:46:55.407Z SendDataTCPServer.js: TCP/IP server has received 2673990 bytes of data
,2015-11-20T12:46:55.422Z SendDataTCPServer.js: TCP/IP server has received 2682750 bytes of data
,2015-11-20T12:46:55.424Z SendDataTCPServer.js: TCP/IP server has received 9115488 bytes of data
,2015-11-20T12:46:55.438Z SendDataTCPServer.js: TCP/IP server has received 9128384 bytes of data
,2015-11-20T12:46:55.451Z SendDataTCPServer.js: TCP/IP server has received 2702460 bytes of data
,2015-11-20T12:46:55.466Z SendDataTCPServer.js: TCP/IP server has received 9134336 bytes of data
,2015-11-20T12:46:55.479Z SendDataTCPServer.js: TCP/IP server has received 9160128 bytes of data
,2015-11-20T12:46:55.493Z SendDataTCPServer.js: TCP/IP server has received 9180960 bytes of data
,2015-11-20T12:46:55.494Z SendDataTCPServer.js: TCP/IP server has received 2704650 bytes of data
,2015-11-20T12:46:55.506Z SendDataTCPServer.js: TCP/IP server has received 9188896 bytes of data
,2015-11-20T12:46:55.545Z SendDataTCPServer.js: TCP/IP server has received 2706840 bytes of data
,2015-11-20T12:46:55.571Z SendDataTCPServer.js: TCP/IP server has received 2728740 bytes of data
,2015-11-20T12:46:55.619Z SendDataTCPServer.js: TCP/IP server has received 9191872 bytes of data
2015-11-20T12:46:55.620Z SendDataTCPServer.js: TCP/IP server has received 2739690 bytes of data
,2015-11-20T12:46:55.632Z SendDataTCPServer.js: TCP/IP server has received 9197824 bytes of data
,2015-11-20T12:46:55.634Z SendDataTCPServer.js: TCP/IP server has received 2755020 bytes of data
,2015-11-20T12:46:55.648Z SendDataTCPServer.js: TCP/IP server has received 9217664 bytes of data
,2015-11-20T12:46:55.649Z SendDataTCPServer.js: TCP/IP server has received 2761590 bytes of data
,2015-11-20T12:46:55.661Z SendDataTCPServer.js: TCP/IP server has received 9241472 bytes of data
2015-11-20T12:46:55.662Z SendDataTCPServer.js: TCP/IP server has received 2765970 bytes of data
,2015-11-20T12:46:55.675Z SendDataTCPServer.js: TCP/IP server has received 9260320 bytes of data
,2015-11-20T12:46:55.676Z SendDataTCPServer.js: TCP/IP server has received 2770350 bytes of data
,2015-11-20T12:46:55.689Z SendDataTCPServer.js: TCP/IP server has received 2790060 bytes of data
,2015-11-20T12:46:55.700Z SendDataTCPServer.js: TCP/IP server has received 2794440 bytes of data
,2015-11-20T12:46:55.933Z SendDataTCPServer.js: TCP/IP server has received 2807580 bytes of data
,2015-11-20T12:46:55.947Z SendDataTCPServer.js: TCP/IP server has received 2827290 bytes of data
,2015-11-20T12:46:55.965Z SendDataTCPServer.js: TCP/IP server has received 9268256 bytes of data
,2015-11-20T12:46:55.977Z SendDataTCPServer.js: TCP/IP server has received 9281152 bytes of data
,2015-11-20T12:46:55.979Z SendDataTCPServer.js: TCP/IP server has received 2829480 bytes of data
,2015-11-20T12:46:55.994Z SendDataTCPServer.js: TCP/IP server has received 9295040 bytes of data
2015-11-20T12:46:55.996Z SendDataTCPServer.js: TCP/IP server has received 2842620 bytes of data
,2015-11-20T12:46:56.012Z SendDataTCPServer.js: TCP/IP server has received 9305952 bytes of data
2015-11-20T12:46:56.013Z SendDataTCPServer.js: TCP/IP server has received 2853570 bytes of data
,2015-11-20T12:46:56.027Z SendDataTCPServer.js: TCP/IP server has received 9322816 bytes of data
,2015-11-20T12:46:56.029Z SendDataTCPServer.js: TCP/IP server has received 2866710 bytes of data
,2015-11-20T12:46:56.153Z SendDataTCPServer.js: TCP/IP server has received 9323808 bytes of data
2015-11-20T12:46:56.157Z SendDataTCPServer.js: TCP/IP server has received 2875470 bytes of data
,2015-11-20T12:46:56.172Z SendDataTCPServer.js: TCP/IP server has received 2882040 bytes of data
,2015-11-20T12:46:56.192Z SendDataTCPServer.js: TCP/IP server has received 2888610 bytes of data
2015-11-20T12:46:56.193Z SendDataTCPServer.js: TCP/IP server has received 9329760 bytes of data
,2015-11-20T12:46:56.224Z SendDataTCPServer.js: TCP/IP server has received 2914890 bytes of data
,2015-11-20T12:46:56.246Z SendDataTCPServer.js: TCP/IP server has received 9373408 bytes of data
,2015-11-20T12:46:56.290Z SendDataTCPServer.js: TCP/IP server has received 2930220 bytes of data
,2015-11-20T12:46:56.296Z SendDataTCPServer.js: TCP/IP server has received 9421024 bytes of data
,2015-11-20T12:46:56.315Z SendDataTCPServer.js: TCP/IP server has received 2965260 bytes of data
,2015-11-20T12:46:56.332Z SendDataTCPServer.js: TCP/IP server has received 2995920 bytes of data
,2015-11-20T12:46:56.358Z SendDataTCPServer.js: TCP/IP server has received 9426976 bytes of data
,2015-11-20T12:46:56.373Z SendDataTCPServer.js: TCP/IP server has received 9455744 bytes of data
,2015-11-20T12:46:56.389Z SendDataTCPServer.js: TCP/IP server has received 9475584 bytes of data
2015-11-20T12:46:56.391Z SendDataTCPServer.js: TCP/IP server has received 3013440 bytes of data
,2015-11-20T12:46:56.403Z SendDataTCPServer.js: TCP/IP server has received 9484512 bytes of data
,2015-11-20T12:46:56.404Z SendDataTCPServer.js: TCP/IP server has received 3024390 bytes of data
,2015-11-20T12:46:56.418Z SendDataTCPServer.js: TCP/IP server has received 3048338 bytes of data
,2015-11-20T12:46:56.431Z SendDataTCPServer.js: TCP/IP server has received 3068190 bytes of data
,2015-11-20T12:46:56.458Z SendDataTCPServer.js: TCP/IP server has received 9488480 bytes of data
,2015-11-20T12:46:56.474Z SendDataTCPServer.js: TCP/IP server has received 9496416 bytes of data
,2015-11-20T12:46:56.478Z SendDataTCPServer.js: TCP/IP server has received 3070380 bytes of data
,2015-11-20T12:46:56.491Z SendDataTCPServer.js: TCP/IP server has received 9514272 bytes of data
2015-11-20T12:46:56.493Z SendDataTCPServer.js: TCP/IP server has received 3085710 bytes of data
,2015-11-20T12:46:56.507Z SendDataTCPServer.js: TCP/IP server has received 9537088 bytes of data
,2015-11-20T12:46:56.522Z SendDataTCPServer.js: TCP/IP server has received 9547008 bytes of data
,2015-11-20T12:46:56.537Z SendDataTCPServer.js: TCP/IP server has received 3087900 bytes of data
,2015-11-20T12:46:56.548Z SendDataTCPServer.js: TCP/IP server has received 3107610 bytes of data
,2015-11-20T12:46:56.719Z SendDataTCPServer.js: TCP/IP server has received 9548000 bytes of data
,2015-11-20T12:46:56.735Z SendDataTCPServer.js: TCP/IP server has received 9551968 bytes of data
,2015-11-20T12:46:56.740Z SendDataTCPServer.js: TCP/IP server has received 3109800 bytes of data
,2015-11-20T12:46:56.758Z SendDataTCPServer.js: TCP/IP server has received 9555936 bytes of data
2015-11-20T12:46:56.762Z SendDataTCPServer.js: TCP/IP server has received 3118560 bytes of data
,2015-11-20T12:46:56.780Z SendDataTCPServer.js: TCP/IP server has received 9562880 bytes of data
,2015-11-20T12:46:56.797Z SendDataTCPServer.js: TCP/IP server has received 9579744 bytes of data
2015-11-20T12:46:56.800Z SendDataTCPServer.js: TCP/IP server has received 3120750 bytes of data
,2015-11-20T12:46:56.818Z SendDataTCPServer.js: TCP/IP server has received 9587680 bytes of data
2015-11-20T12:46:56.820Z SendDataTCPServer.js: TCP/IP server has received 3135086 bytes of data
,2015-11-20T12:46:56.835Z SendDataTCPServer.js: TCP/IP server has received 9616448 bytes of data
,2015-11-20T12:46:56.837Z SendDataTCPServer.js: TCP/IP server has received 3151410 bytes of data
,2015-11-20T12:46:56.878Z SendDataTCPServer.js: TCP/IP server has received 9617440 bytes of data
,2015-11-20T12:46:56.893Z SendDataTCPServer.js: TCP/IP server has received 3153600 bytes of data
,2015-11-20T12:46:56.919Z SendDataTCPServer.js: TCP/IP server has received 3164550 bytes of data
,2015-11-20T12:46:56.937Z SendDataTCPServer.js: TCP/IP server has received 3182070 bytes of data
,2015-11-20T12:46:56.953Z SendDataTCPServer.js: TCP/IP server has received 3184260 bytes of data
,2015-11-20T12:46:56.954Z SendDataTCPServer.js: TCP/IP server has received 9624384 bytes of data
,2015-11-20T12:46:56.977Z SendDataTCPServer.js: TCP/IP server has received 3193020 bytes of data
,2015-11-20T12:46:56.992Z SendDataTCPServer.js: TCP/IP server has received 3228060 bytes of data
,2015-11-20T12:46:56.995Z SendDataTCPServer.js: TCP/IP server has received 9629344 bytes of data
,2015-11-20T12:46:57.009Z SendDataTCPServer.js: TCP/IP server has received 3236820 bytes of data
,2015-11-20T12:46:57.011Z SendDataTCPServer.js: TCP/IP server has received 9638272 bytes of data
,2015-11-20T12:46:57.024Z SendDataTCPServer.js: TCP/IP server has received 3243390 bytes of data
,2015-11-20T12:46:57.025Z SendDataTCPServer.js: TCP/IP server has received 9648192 bytes of data
,2015-11-20T12:46:57.038Z SendDataTCPServer.js: TCP/IP server has received 9663072 bytes of data
,2015-11-20T12:46:57.054Z SendDataTCPServer.js: TCP/IP server has received 9673984 bytes of data
,2015-11-20T12:46:57.055Z SendDataTCPServer.js: TCP/IP server has received 3254340 bytes of data
,2015-11-20T12:46:57.071Z SendDataTCPServer.js: TCP/IP server has received 9679936 bytes of data
,2015-11-20T12:46:57.072Z SendDataTCPServer.js: TCP/IP server has received 3265290 bytes of data
,2015-11-20T12:46:57.088Z SendDataTCPServer.js: TCP/IP server has received 9680928 bytes of data
,2015-11-20T12:46:57.089Z SendDataTCPServer.js: TCP/IP server has received 3276240 bytes of data
,2015-11-20T12:46:57.104Z SendDataTCPServer.js: TCP/IP server has received 9685888 bytes of data
,2015-11-20T12:46:57.117Z SendDataTCPServer.js: TCP/IP server has received 9700768 bytes of data
,2015-11-20T12:46:57.134Z SendDataTCPServer.js: TCP/IP server has received 9718624 bytes of data
,2015-11-20T12:46:57.153Z SendDataTCPServer.js: TCP/IP server has received 9753344 bytes of data
,2015-11-20T12:46:57.167Z SendDataTCPServer.js: TCP/IP server has received 9756320 bytes of data
,2015-11-20T12:46:57.168Z SendDataTCPServer.js: TCP/IP server has received 3278430 bytes of data
,2015-11-20T12:46:57.192Z SendDataTCPServer.js: TCP/IP server has received 9766240 bytes of data
,2015-11-20T12:46:57.210Z SendDataTCPServer.js: TCP/IP server has received 3287190 bytes of data
,2015-11-20T12:46:57.227Z SendDataTCPServer.js: TCP/IP server has received 3291570 bytes of data
,2015-11-20T12:46:57.228Z SendDataTCPServer.js: TCP/IP server has received 9784096 bytes of data
,2015-11-20T12:46:57.497Z SendDataTCPServer.js: TCP/IP server has received 3295950 bytes of data
,2015-11-20T12:46:57.526Z SendDataTCPServer.js: TCP/IP server has received 9788064 bytes of data
,2015-11-20T12:46:57.541Z SendDataTCPServer.js: TCP/IP server has received 9793024 bytes of data
,2015-11-20T12:46:57.544Z SendDataTCPServer.js: TCP/IP server has received 3298140 bytes of data
,2015-11-20T12:46:57.559Z SendDataTCPServer.js: TCP/IP server has received 9803936 bytes of data
,2015-11-20T12:46:57.574Z SendDataTCPServer.js: TCP/IP server has received 9814848 bytes of data
,2015-11-20T12:46:57.592Z SendDataTCPServer.js: TCP/IP server has received 9825760 bytes of data
,2015-11-20T12:46:57.612Z SendDataTCPServer.js: TCP/IP server has received 9831712 bytes of data
,2015-11-20T12:46:57.614Z SendDataTCPServer.js: TCP/IP server has received 3300330 bytes of data
,2015-11-20T12:46:57.631Z SendDataTCPServer.js: TCP/IP server has received 9836672 bytes of data
,2015-11-20T12:46:57.633Z SendDataTCPServer.js: TCP/IP server has received 3326610 bytes of data
,2015-11-20T12:46:57.651Z SendDataTCPServer.js: TCP/IP server has received 9846592 bytes of data
,2015-11-20T12:46:57.676Z SendDataTCPServer.js: TCP/IP server has received 3330990 bytes of data
,2015-11-20T12:46:57.696Z SendDataTCPServer.js: TCP/IP server has received 3361650 bytes of data
,2015-11-20T12:46:57.700Z SendDataTCPServer.js: TCP/IP server has received 9847584 bytes of data
,2015-11-20T12:46:57.714Z SendDataTCPServer.js: TCP/IP server has received 3368220 bytes of data
,2015-11-20T12:46:57.715Z SendDataTCPServer.js: TCP/IP server has received 9864448 bytes of data
,2015-11-20T12:46:57.732Z SendDataTCPServer.js: TCP/IP server has received 9887264 bytes of data
,2015-11-20T12:46:57.748Z SendDataTCPServer.js: TCP/IP server has received 9909088 bytes of data
,2015-11-20T12:46:57.751Z SendDataTCPServer.js: TCP/IP server has received 3383124 bytes of data
,2015-11-20T12:46:57.768Z SendDataTCPServer.js: TCP/IP server has received 3412020 bytes of data
,2015-11-20T12:46:57.886Z SendDataTCPServer.js: TCP/IP server has received 3414210 bytes of data
,2015-11-20T12:46:57.945Z SendDataTCPServer.js: TCP/IP server has received 3420780 bytes of data
,2015-11-20T12:46:57.961Z SendDataTCPServer.js: TCP/IP server has received 3440490 bytes of data
,2015-11-20T12:46:58.124Z SendDataTCPServer.js: TCP/IP server has received 9917024 bytes of data
,2015-11-20T12:46:58.128Z SendDataTCPServer.js: TCP/IP server has received 3442680 bytes of data
,2015-11-20T12:46:58.150Z SendDataTCPServer.js: TCP/IP server has received 9936864 bytes of data
,2015-11-20 13:46:58.162 ThaliTest[1024:781290] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:46:58.162 ThaliTest[1024:781290] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:46:58.166Z SendDataTCPServer.js: TC,P/IP server has received 9943808 bytes of data
2015-11-20T12:46:58.169Z SendDataTCPServer.js: TCP/IP server has received 9946784 bytes of data
2015-11-20T12:46:58.170Z SendDataTCPServer.js: TCP/IP server has received 3449250 bytes of data
peerAvailabili,tyChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-20T12:46:58.198Z SendDataTCPServer.js: TCP/IP server has received 9964640 bytes of data
,2015-11-20T12:46:58.205Z SendDataTCPServer.js: TCP/IP server has received 3464580 bytes of data
,2015-11-20T12:46:58.220Z SendDataTCPServer.js: TCP/IP server has received 9977536 bytes of data
,2015-11-20T12:46:58.224Z SendDataTCPServer.js: TCP/IP server has received 3484290 bytes of data
,2015-11-20T12:46:58.238Z SendDataTCPServer.js: TCP/IP server has received 9987456 bytes of data
,2015-11-20T12:46:58.239Z SendDataTCPServer.js: TCP/IP server has received 3499620 bytes of data
,2015-11-20T12:46:58.255Z SendDataTCPServer.js: TCP/IP server has received 9995392 bytes of data
,2015-11-20T12:46:58.262Z SendDataTCPServer.js: TCP/IP server has received 3517140 bytes of data
,2015-11-20T12:46:58.277Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20T12:46:58.281Z SendDataTCPServer.js: TCP/IP server has received 3525900 bytes of data
,2015-11-20T12:46:58.295Z SendDataTCPServer.js: TCP/IP server has received 3556560 bytes of data
,2015-11-20T12:46:58.324Z SendDataTCPServer.js: TCP/IP server has received 3558750 bytes of data
,2015-11-20T12:46:58.486Z SendDataTCPServer.js: TCP/IP server has received 3560940 bytes of data
,2015-11-20T12:46:58.524Z SendDataTCPServer.js: TCP/IP server has received 3574080 bytes of data
,2015-11-20T12:46:58.539Z SendDataTCPServer.js: TCP/IP server has received 3576270 bytes of data
,2015-11-20T12:46:58.612Z SendDataTCPServer.js: TCP/IP server has received 3582840 bytes of data
,2015-11-20T12:46:58.626Z SendDataTCPServer.js: TCP/IP server has received 3585030 bytes of data
,2015-11-20T12:46:58.641Z SendDataTCPServer.js: TCP/IP server has received 3598170 bytes of data
2015-11-20 13:46:58.646 ThaliTest[1024:782126] server session: not connected Apple-Iphone5-1_PT6611
,2015-11-20T12:46:58.654Z SendDataTCPServer.js: TCP/IP server has received 3602550 bytes of data
,2015-11-20T12:46:58.682Z SendDataTCPServer.js: TCP/IP server has received 3611310 bytes of data
,2015-11-20T12:46:58.696Z SendDataTCPServer.js: TCP/IP server has received 3620070 bytes of data
,2015-11-20T12:46:58.718Z SendDataTCPServer.js: TCP/IP server has received 3631020 bytes of data
,2015-11-20T12:46:58.733Z SendDataTCPServer.js: TCP/IP server has received 3637590 bytes of data
,2015-11-20T12:46:58.845Z SendDataTCPServer.js: TCP/IP server has received 3639780 bytes of data
,2015-11-20T12:46:58.859Z SendDataTCPServer.js: TCP/IP server has received 3655110 bytes of data
,2015-11-20T12:46:58.961Z SendDataTCPServer.js: TCP/IP server has received 3666060 bytes of data
,2015-11-20T12:46:58.976Z SendDataTCPServer.js: TCP/IP server has received 3668250 bytes of data
,2015-11-20T12:46:58.991Z SendDataTCPServer.js: TCP/IP server has received 3692340 bytes of data
,2015-11-20T12:46:59.009Z SendDataTCPServer.js: TCP/IP server has received 3725190 bytes of data
,2015-11-20T12:46:59.086Z SendDataTCPServer.js: TCP/IP server has received 3727380 bytes of data
,2015-11-20T12:46:59.101Z SendDataTCPServer.js: TCP/IP server has received 3744900 bytes of data
,2015-11-20T12:46:59.118Z SendDataTCPServer.js: TCP/IP server has received 3764610 bytes of data
,2015-11-20T12:46:59.135Z SendDataTCPServer.js: TCP/IP server has received 3777750 bytes of data
,2015-11-20T12:46:59.149Z SendDataTCPServer.js: TCP/IP server has received 3779940 bytes of data
,2015-11-20T12:46:59.172Z SendDataTCPServer.js: TCP/IP server has received 3788700 bytes of data
,2015-11-20T12:46:59.190Z SendDataTCPServer.js: TCP/IP server has received 3814980 bytes of data
,2015-11-20T12:46:59.208Z SendDataTCPServer.js: TCP/IP server has received 3838928 bytes of data
,2015-11-20T12:46:59.224Z SendDataTCPServer.js: TCP/IP server has received 3858638 bytes of data
,2015-11-20T12:46:59.242Z SendDataTCPServer.js: TCP/IP server has received 3869730 bytes of data
,2015-11-20T12:46:59.256Z SendDataTCPServer.js: TCP/IP server has received 3885060 bytes of data
,2015-11-20T12:46:59.274Z SendDataTCPServer.js: TCP/IP server has received 3913388 bytes of data
,2015-11-20T12:46:59.291Z SendDataTCPServer.js: TCP/IP server has received 3935430 bytes of data
,2015-11-20T12:46:59.310Z SendDataTCPServer.js: TCP/IP server has received 3970470 bytes of data
,2015-11-20T12:46:59.328Z SendDataTCPServer.js: TCP/IP server has received 3994560 bytes of data
,2015-11-20T12:46:59.345Z SendDataTCPServer.js: TCP/IP server has received 4023030 bytes of data
,2015-11-20T12:46:59.362Z SendDataTCPServer.js: TCP/IP server has received 4047120 bytes of data
,2015-11-20T12:46:59.376Z SendDataTCPServer.js: TCP/IP server has received 4077780 bytes of data
,2015-11-20T12:46:59.391Z SendDataTCPServer.js: TCP/IP server has received 4104060 bytes of data
,2015-11-20T12:46:59.406Z SendDataTCPServer.js: TCP/IP server has received 4143480 bytes of data
,2015-11-20T12:46:59.421Z SendDataTCPServer.js: TCP/IP server has received 4189470 bytes of data
,2015-11-20T12:46:59.439Z SendDataTCPServer.js: TCP/IP server has received 4226700 bytes of data
,2015-11-20T12:46:59.453Z SendDataTCPServer.js: TCP/IP server has received 4261740 bytes of data
,2015-11-20T12:46:59.468Z SendDataTCPServer.js: TCP/IP server has received 4292400 bytes of data
,2015-11-20T12:46:59.484Z SendDataTCPServer.js: TCP/IP server has received 4344960 bytes of data
,2015-11-20T12:46:59.501Z SendDataTCPServer.js: TCP/IP server has received 4417230 bytes of data
,2015-11-20T12:46:59.519Z SendDataTCPServer.js: TCP/IP server has received 4480740 bytes of data
,2015-11-20T12:46:59.535Z SendDataTCPServer.js: TCP/IP server has received 4522066 bytes of data
,2015-11-20T12:46:59.552Z SendDataTCPServer.js: TCP/IP server has received 4570530 bytes of data
,2015-11-20T12:46:59.566Z SendDataTCPServer.js: TCP/IP server has received 4627470 bytes of data
,2015-11-20T12:46:59.578Z SendDataTCPServer.js: TCP/IP server has received 4669080 bytes of data
,2015-11-20T12:46:59.594Z SendDataTCPServer.js: TCP/IP server has received 4706310 bytes of data
,2015-11-20T12:46:59.611Z SendDataTCPServer.js: TCP/IP server has received 4752300 bytes of data
,2015-11-20T12:46:59.624Z SendDataTCPServer.js: TCP/IP server has received 4791720 bytes of data
,2015-11-20T12:46:59.638Z SendDataTCPServer.js: TCP/IP server has received 4844138 bytes of data
,2015-11-20T12:46:59.652Z SendDataTCPServer.js: TCP/IP server has received 4881510 bytes of data
,2015-11-20T12:46:59.667Z SendDataTCPServer.js: TCP/IP server has received 4931880 bytes of data
,2015-11-20T12:46:59.682Z SendDataTCPServer.js: TCP/IP server has received 4982250 bytes of data
,2015-11-20T12:46:59.697Z SendDataTCPServer.js: TCP/IP server has received 5041380 bytes of data
,2015-11-20T12:46:59.712Z SendDataTCPServer.js: TCP/IP server has received 5078610 bytes of data
,2015-11-20T12:46:59.725Z SendDataTCPServer.js: TCP/IP server has received 5126790 bytes of data
,2015-11-20T12:46:59.739Z SendDataTCPServer.js: TCP/IP server has received 5179350 bytes of data
,2015-11-20T12:46:59.752Z SendDataTCPServer.js: TCP/IP server has received 5216580 bytes of data
,2015-11-20T12:46:59.766Z SendDataTCPServer.js: TCP/IP server has received 5260380 bytes of data
,2015-11-20T12:46:59.779Z SendDataTCPServer.js: TCP/IP server has received 5297610 bytes of data
,2015-11-20T12:46:59.791Z SendDataTCPServer.js: TCP/IP server has received 5347980 bytes of data
,2015-11-20T12:46:59.804Z SendDataTCPServer.js: TCP/IP server has received 5389590 bytes of data
,2015-11-20T12:46:59.817Z SendDataTCPServer.js: TCP/IP server has received 5437770 bytes of data
,2015-11-20T12:46:59.830Z SendDataTCPServer.js: TCP/IP server has received 5481570 bytes of data
,2015-11-20T12:46:59.844Z SendDataTCPServer.js: TCP/IP server has received 5525370 bytes of data
,2015-11-20T12:46:59.856Z SendDataTCPServer.js: TCP/IP server has received 5562600 bytes of data
,2015-11-20T12:46:59.870Z SendDataTCPServer.js: TCP/IP server has received 5608590 bytes of data
,2015-11-20T12:46:59.883Z SendDataTCPServer.js: TCP/IP server has received 5648010 bytes of data
,2015-11-20T12:46:59.897Z SendDataTCPServer.js: TCP/IP server has received 5696190 bytes of data
,2015-11-20T12:46:59.912Z SendDataTCPServer.js: TCP/IP server has received 5753130 bytes of data
,2015-11-20T12:46:59.924Z SendDataTCPServer.js: TCP/IP server has received 5788170 bytes of data
,2015-11-20T12:46:59.938Z SendDataTCPServer.js: TCP/IP server has received 5827590 bytes of data
,2015-11-20T12:46:59.950Z SendDataTCPServer.js: TCP/IP server has received 5862630 bytes of data
,2015-11-20T12:46:59.965Z SendDataTCPServer.js: TCP/IP server has received 5919570 bytes of data
,2015-11-20T12:46:59.978Z SendDataTCPServer.js: TCP/IP server has received 5956800 bytes of data
,2015-11-20T12:46:59.992Z SendDataTCPServer.js: TCP/IP server has received 6000600 bytes of data
,2015-11-20T12:47:00.006Z SendDataTCPServer.js: TCP/IP server has received 6035640 bytes of data
,2015-11-20T12:47:00.021Z SendDataTCPServer.js: TCP/IP server has received 6059730 bytes of data
,2015-11-20T12:47:00.034Z SendDataTCPServer.js: TCP/IP server has received 6079440 bytes of data
,2015-11-20T12:47:00.048Z SendDataTCPServer.js: TCP/IP server has received 6147330 bytes of data
,2015-11-20T12:47:00.061Z SendDataTCPServer.js: TCP/IP server has received 6193320 bytes of data
,2015-11-20T12:47:00.073Z SendDataTCPServer.js: TCP/IP server has received 6228360 bytes of data
,2015-11-20T12:47:00.085Z SendDataTCPServer.js: TCP/IP server has received 6278730 bytes of data
,2015-11-20T12:47:00.099Z SendDataTCPServer.js: TCP/IP server has received 6331290 bytes of data
,2015-11-20T12:47:00.111Z SendDataTCPServer.js: TCP/IP server has received 6368520 bytes of data
,2015-11-20T12:47:00.125Z SendDataTCPServer.js: TCP/IP server has received 6394800 bytes of data
,2015-11-20T12:47:00.137Z SendDataTCPServer.js: TCP/IP server has received 6432030 bytes of data
,2015-11-20T12:47:00.150Z SendDataTCPServer.js: TCP/IP server has received 6473640 bytes of data
,2015-11-20T12:47:00.162Z SendDataTCPServer.js: TCP/IP server has received 6519630 bytes of data
,2015-11-20T12:47:00.175Z SendDataTCPServer.js: TCP/IP server has received 6554670 bytes of data
,2015-11-20T12:47:00.190Z SendDataTCPServer.js: TCP/IP server has received 6594090 bytes of data
,2015-11-20T12:47:00.204Z SendDataTCPServer.js: TCP/IP server has received 6655410 bytes of data
,2015-11-20T12:47:00.217Z SendDataTCPServer.js: TCP/IP server has received 6679500 bytes of data
,2015-11-20T12:47:00.231Z SendDataTCPServer.js: TCP/IP server has received 6732060 bytes of data
,2015-11-20T12:47:00.244Z SendDataTCPServer.js: TCP/IP server has received 6734250 bytes of data
,2015-11-20T12:47:00.269Z SendDataTCPServer.js: TCP/IP server has received 6756150 bytes of data
,2015-11-20T12:47:00.283Z SendDataTCPServer.js: TCP/IP server has received 6791190 bytes of data
,2015-11-20T12:47:00.298Z SendDataTCPServer.js: TCP/IP server has received 6819660 bytes of data
,2015-11-20T12:47:00.311Z SendDataTCPServer.js: TCP/IP server has received 6828420 bytes of data
,2015-11-20T12:47:00.323Z SendDataTCPServer.js: TCP/IP server has received 6856890 bytes of data
,2015-11-20T12:47:00.337Z SendDataTCPServer.js: TCP/IP server has received 6876600 bytes of data
,2015-11-20T12:47:00.350Z SendDataTCPServer.js: TCP/IP server has received 6885360 bytes of data
,2015-11-20T12:47:00.363Z SendDataTCPServer.js: TCP/IP server has received 6887550 bytes of data
,2015-11-20T12:47:00.387Z SendDataTCPServer.js: TCP/IP server has received 6891930 bytes of data
,2015-11-20T12:47:00.423Z SendDataTCPServer.js: TCP/IP server has received 6898500 bytes of data
,2015-11-20T12:47:00.436Z SendDataTCPServer.js: TCP/IP server has received 6902880 bytes of data
,2015-11-20T12:47:00.450Z SendDataTCPServer.js: TCP/IP server has received 6905070 bytes of data
,2015-11-20T12:47:00.461Z SendDataTCPServer.js: TCP/IP server has received 6916020 bytes of data
,2015-11-20T12:47:00.473Z SendDataTCPServer.js: TCP/IP server has received 6942300 bytes of data
,2015-11-20T12:47:00.484Z SendDataTCPServer.js: TCP/IP server has received 6944490 bytes of data
,2015-11-20T12:47:00.533Z SendDataTCPServer.js: TCP/IP server has received 6962010 bytes of data
,2015-11-20T12:47:00.709Z SendDataTCPServer.js: TCP/IP server has received 6966390 bytes of data
,2015-11-20T12:47:00.724Z SendDataTCPServer.js: TCP/IP server has received 6979530 bytes of data
,2015-11-20T12:47:00.740Z SendDataTCPServer.js: TCP/IP server has received 6994860 bytes of data
,2015-11-20T12:47:00.759Z SendDataTCPServer.js: TCP/IP server has received 7021140 bytes of data
,2015-11-20T12:47:00.778Z SendDataTCPServer.js: TCP/IP server has received 7038660 bytes of data
,2015-11-20T12:47:00.795Z SendDataTCPServer.js: TCP/IP server has received 7058370 bytes of data
,2015-11-20T12:47:00.812Z SendDataTCPServer.js: TCP/IP server has received 7082460 bytes of data
,2015-11-20T12:47:00.838Z SendDataTCPServer.js: TCP/IP server has received 7084650 bytes of data
,2015-11-20T12:47:01.023Z SendDataTCPServer.js: TCP/IP server has received 7086840 bytes of data
,2015-11-20T12:47:01.068Z SendDataTCPServer.js: TCP/IP server has received 7102170 bytes of data
,2015-11-20T12:47:01.087Z SendDataTCPServer.js: TCP/IP server has received 7124070 bytes of data
,2015-11-20T12:47:01.104Z SendDataTCPServer.js: TCP/IP server has received 7152540 bytes of data
,2015-11-20T12:47:01.124Z SendDataTCPServer.js: TCP/IP server has received 7178820 bytes of data
,2015-11-20T12:47:01.143Z SendDataTCPServer.js: TCP/IP server has received 7189770 bytes of data
,2015-11-20T12:47:01.157Z SendDataTCPServer.js: TCP/IP server has received 7209480 bytes of data
,2015-11-20T12:47:01.175Z SendDataTCPServer.js: TCP/IP server has received 7213860 bytes of data
,2015-11-20T12:47:01.188Z SendDataTCPServer.js: TCP/IP server has received 7224810 bytes of data
,2015-11-20T12:47:01.266Z SendDataTCPServer.js: TCP/IP server has received 7227000 bytes of data
,2015-11-20T12:47:01.279Z SendDataTCPServer.js: TCP/IP server has received 7233570 bytes of data
,2015-11-20T12:47:01.295Z SendDataTCPServer.js: TCP/IP server has received 7251090 bytes of data
,2015-11-20T12:47:01.310Z SendDataTCPServer.js: TCP/IP server has received 7255470 bytes of data
,2015-11-20T12:47:01.361Z SendDataTCPServer.js: TCP/IP server has received 7257660 bytes of data
,2015-11-20T12:47:01.413Z SendDataTCPServer.js: TCP/IP server has received 7279560 bytes of data
,2015-11-20T12:47:01.492Z SendDataTCPServer.js: TCP/IP server has received 7281750 bytes of data
,2015-11-20T12:47:01.519Z SendDataTCPServer.js: TCP/IP server has received 7286130 bytes of data
,2015-11-20T12:47:01.534Z SendDataTCPServer.js: TCP/IP server has received 7288320 bytes of data
,2015-11-20T12:47:01.547Z SendDataTCPServer.js: TCP/IP server has received 7294890 bytes of data
,2015-11-20T12:47:01.589Z SendDataTCPServer.js: TCP/IP server has received 7303650 bytes of data
,2015-11-20T12:47:01.610Z SendDataTCPServer.js: TCP/IP server has received 7318980 bytes of data
,2015-11-20T12:47:01.628Z SendDataTCPServer.js: TCP/IP server has received 7321170 bytes of data
,2015-11-20T12:47:01.643Z SendDataTCPServer.js: TCP/IP server has received 7334310 bytes of data
,2015-11-20T12:47:01.671Z SendDataTCPServer.js: TCP/IP server has received 7347450 bytes of data
,2015-11-20T12:47:01.695Z SendDataTCPServer.js: TCP/IP server has received 7375920 bytes of data
,2015-11-20T12:47:01.715Z SendDataTCPServer.js: TCP/IP server has received 7386870 bytes of data
,2015-11-20T12:47:01.730Z SendDataTCPServer.js: TCP/IP server has received 7393440 bytes of data
,2015-11-20T12:47:01.745Z SendDataTCPServer.js: TCP/IP server has received 7415340 bytes of data
,2015-11-20T12:47:01.761Z SendDataTCPServer.js: TCP/IP server has received 7417530 bytes of data
,2015-11-20T12:47:02.208Z SendDataTCPServer.js: TCP/IP server has received 7419720 bytes of data
,2015-11-20T12:47:02.234Z SendDataTCPServer.js: TCP/IP server has received 7432860 bytes of data
,2015-11-20T12:47:02.251Z SendDataTCPServer.js: TCP/IP server has received 7437240 bytes of data
,2015-11-20T12:47:02.266Z SendDataTCPServer.js: TCP/IP server has received 7459140 bytes of data
,2015-11-20T12:47:02.280Z SendDataTCPServer.js: TCP/IP server has received 7478850 bytes of data
,2015-11-20T12:47:02.298Z SendDataTCPServer.js: TCP/IP server has received 7513890 bytes of data
,2015-11-20T12:47:02.314Z SendDataTCPServer.js: TCP/IP server has received 7527030 bytes of data
,2015-11-20T12:47:02.332Z SendDataTCPServer.js: TCP/IP server has received 7529220 bytes of data
,2015-11-20T12:47:02.401Z SendDataTCPServer.js: TCP/IP server has received 7563692 bytes of data
,2015-11-20T12:47:02.417Z SendDataTCPServer.js: TCP/IP server has received 7577400 bytes of data
,2015-11-20T12:47:02.509Z SendDataTCPServer.js: TCP/IP server has received 7583970 bytes of data
,2015-11-20T12:47:02.523Z SendDataTCPServer.js: TCP/IP server has received 7586160 bytes of data
,2015-11-20T12:47:02.550Z SendDataTCPServer.js: TCP/IP server has received 7594920 bytes of data
,2015-11-20T12:47:02.564Z SendDataTCPServer.js: TCP/IP server has received 7597110 bytes of data
,2015-11-20T12:47:02.584Z SendDataTCPServer.js: TCP/IP server has received 7609682 bytes of data
,2015-11-20T12:47:02.600Z SendDataTCPServer.js: TCP/IP server has received 7638720 bytes of data
,2015-11-20T12:47:02.628Z SendDataTCPServer.js: TCP/IP server has received 7640910 bytes of data
,2015-11-20T12:47:02.643Z SendDataTCPServer.js: TCP/IP server has received 7651860 bytes of data
,2015-11-20T12:47:02.659Z SendDataTCPServer.js: TCP/IP server has received 7675950 bytes of data
,2015-11-20T12:47:02.673Z SendDataTCPServer.js: TCP/IP server has received 7680330 bytes of data
,2015-11-20T12:47:02.737Z SendDataTCPServer.js: TCP/IP server has received 7682520 bytes of data
,2015-11-20T12:47:02.755Z SendDataTCPServer.js: TCP/IP server has received 7693186 bytes of data
,2015-11-20T12:47:02.775Z SendDataTCPServer.js: TCP/IP server has received 7717560 bytes of data
,2015-11-20T12:47:02.847Z SendDataTCPServer.js: TCP/IP server has received 7728510 bytes of data
,2015-11-20T12:47:02.864Z SendDataTCPServer.js: TCP/IP server has received 7752600 bytes of data
,2015-11-20T12:47:02.889Z SendDataTCPServer.js: TCP/IP server has received 7778880 bytes of data
,2015-11-20T12:47:02.907Z SendDataTCPServer.js: TCP/IP server has received 7798590 bytes of data
,2015-11-20T12:47:02.925Z SendDataTCPServer.js: TCP/IP server has received 7809540 bytes of data
,2015-11-20T12:47:02.939Z SendDataTCPServer.js: TCP/IP server has received 7827060 bytes of data
,2015-11-20T12:47:02.954Z SendDataTCPServer.js: TCP/IP server has received 7857720 bytes of data
,2015-11-20T12:47:02.974Z SendDataTCPServer.js: TCP/IP server has received 7877430 bytes of data
,2015-11-20T12:47:02.990Z SendDataTCPServer.js: TCP/IP server has received 7881810 bytes of data
,2015-11-20T12:47:03.003Z SendDataTCPServer.js: TCP/IP server has received 7901520 bytes of data
,2015-11-20T12:47:03.055Z SendDataTCPServer.js: TCP/IP server has received 7903710 bytes of data
,2015-11-20T12:47:03.095Z SendDataTCPServer.js: TCP/IP server has received 7921230 bytes of data
,2015-11-20T12:47:03.114Z SendDataTCPServer.js: TCP/IP server has received 7947510 bytes of data
,2015-11-20T12:47:03.133Z SendDataTCPServer.js: TCP/IP server has received 7960650 bytes of data
,2015-11-20T12:47:03.197Z SendDataTCPServer.js: TCP/IP server has received 7962840 bytes of data
,2015-11-20T12:47:03.238Z SendDataTCPServer.js: TCP/IP server has received 7967220 bytes of data
,2015-11-20T12:47:03.252Z SendDataTCPServer.js: TCP/IP server has received 7971600 bytes of data
,2015-11-20T12:47:03.341Z SendDataTCPServer.js: TCP/IP server has received 7973790 bytes of data
,2015-11-20T12:47:03.379Z SendDataTCPServer.js: TCP/IP server has received 7980360 bytes of data
,2015-11-20T12:47:03.396Z SendDataTCPServer.js: TCP/IP server has received 8006640 bytes of data
,2015-11-20T12:47:03.463Z SendDataTCPServer.js: TCP/IP server has received 8008830 bytes of data
,2015-11-20T12:47:03.491Z SendDataTCPServer.js: TCP/IP server has received 8013210 bytes of data
,2015-11-20T12:47:03.508Z SendDataTCPServer.js: TCP/IP server has received 8039490 bytes of data
2015-11-20T12:47:03.524Z SendDataTCPServer.js: TCP/IP server has received 8061390 bytes of data
,2015-11-20T12:47:03.541Z SendDataTCPServer.js: TCP/IP server has received 8100810 bytes of data
,2015-11-20T12:47:03.562Z SendDataTCPServer.js: TCP/IP server has received 8124900 bytes of data
,2015-11-20T12:47:03.617Z SendDataTCPServer.js: TCP/IP server has received 8140230 bytes of data
,2015-11-20T12:47:03.634Z SendDataTCPServer.js: TCP/IP server has received 8155560 bytes of data
,2015-11-20T12:47:03.649Z SendDataTCPServer.js: TCP/IP server has received 8162130 bytes of data
,2015-11-20T12:47:03.664Z SendDataTCPServer.js: TCP/IP server has received 8177460 bytes of data
,2015-11-20T12:47:03.680Z SendDataTCPServer.js: TCP/IP server has received 8179650 bytes of data
,2015-11-20T12:47:03.696Z SendDataTCPServer.js: TCP/IP server has received 8186220 bytes of data
,2015-11-20T12:47:03.713Z SendDataTCPServer.js: TCP/IP server has received 8205930 bytes of data
,2015-11-20T12:47:03.733Z SendDataTCPServer.js: TCP/IP server has received 8223450 bytes of data
,2015-11-20T12:47:03.750Z SendDataTCPServer.js: TCP/IP server has received 8238780 bytes of data
,2015-11-20T12:47:03.767Z SendDataTCPServer.js: TCP/IP server has received 8249730 bytes of data
,2015-11-20T12:47:03.781Z SendDataTCPServer.js: TCP/IP server has received 8265060 bytes of data
,2015-11-20T12:47:03.799Z SendDataTCPServer.js: TCP/IP server has received 8295720 bytes of data
,2015-11-20T12:47:03.816Z SendDataTCPServer.js: TCP/IP server has received 8335140 bytes of data
,2015-11-20T12:47:03.833Z SendDataTCPServer.js: TCP/IP server has received 8367990 bytes of data
,2015-11-20T12:47:03.847Z SendDataTCPServer.js: TCP/IP server has received 8392080 bytes of data
,2015-11-20T12:47:03.863Z SendDataTCPServer.js: TCP/IP server has received 8413980 bytes of data
,2015-11-20T12:47:03.878Z SendDataTCPServer.js: TCP/IP server has received 8429310 bytes of data
,2015-11-20T12:47:03.892Z SendDataTCPServer.js: TCP/IP server has received 8435880 bytes of data
,2015-11-20T12:47:03.920Z SendDataTCPServer.js: TCP/IP server has received 8449020 bytes of data
,2015-11-20T12:47:03.935Z SendDataTCPServer.js: TCP/IP server has received 8473110 bytes of data
,2015-11-20T12:47:03.951Z SendDataTCPServer.js: TCP/IP server has received 8497200 bytes of data
,2015-11-20T12:47:03.969Z SendDataTCPServer.js: TCP/IP server has received 8501580 bytes of data
,2015-11-20T12:47:03.981Z SendDataTCPServer.js: TCP/IP server has received 8503770 bytes of data
,2015-11-20T12:47:03.996Z SendDataTCPServer.js: TCP/IP server has received 8525670 bytes of data
,2015-11-20T12:47:04.013Z SendDataTCPServer.js: TCP/IP server has received 8551950 bytes of data
,2015-11-20T12:47:04.029Z SendDataTCPServer.js: TCP/IP server has received 8573850 bytes of data
,2015-11-20T12:47:04.044Z SendDataTCPServer.js: TCP/IP server has received 8595750 bytes of data
,2015-11-20T12:47:04.060Z SendDataTCPServer.js: TCP/IP server has received 8615460 bytes of data
,2015-11-20T12:47:04.077Z SendDataTCPServer.js: TCP/IP server has received 8643930 bytes of data
,2015-11-20T12:47:04.094Z SendDataTCPServer.js: TCP/IP server has received 8670210 bytes of data
,2015-11-20T12:47:04.109Z SendDataTCPServer.js: TCP/IP server has received 8707440 bytes of data
,2015-11-20T12:47:04.125Z SendDataTCPServer.js: TCP/IP server has received 8755620 bytes of data
,2015-11-20T12:47:04.139Z SendDataTCPServer.js: TCP/IP server has received 8801610 bytes of data
,2015-11-20T12:47:04.152Z SendDataTCPServer.js: TCP/IP server has received 8843220 bytes of data
,2015-11-20T12:47:04.165Z SendDataTCPServer.js: TCP/IP server has received 8908756 bytes of data
,2015-11-20T12:47:04.181Z SendDataTCPServer.js: TCP/IP server has received 8972146 bytes of data
,2015-11-20T12:47:04.198Z SendDataTCPServer.js: TCP/IP server has received 9000190 bytes of data
,2015-11-20T12:47:04.213Z SendDataTCPServer.js: TCP/IP server has received 9110400 bytes of data
,2015-11-20T12:47:04.228Z SendDataTCPServer.js: TCP/IP server has received 9191430 bytes of data
,2015-11-20T12:47:04.242Z SendDataTCPServer.js: TCP/IP server has received 9254940 bytes of data
,2015-11-20T12:47:04.256Z SendDataTCPServer.js: TCP/IP server has received 9283410 bytes of data
,2015-11-20T12:47:04.272Z SendDataTCPServer.js: TCP/IP server has received 9335970 bytes of data
,2015-11-20T12:47:04.288Z SendDataTCPServer.js: TCP/IP server has received 9375390 bytes of data
,2015-11-20T12:47:04.301Z SendDataTCPServer.js: TCP/IP server has received 9410430 bytes of data
,2015-11-20T12:47:04.313Z SendDataTCPServer.js: TCP/IP server has received 9447660 bytes of data
,2015-11-20T12:47:04.325Z SendDataTCPServer.js: TCP/IP server has received 9495556 bytes of data
,2015-11-20T12:47:04.338Z SendDataTCPServer.js: TCP/IP server has received 9544020 bytes of data
,2015-11-20T12:47:04.352Z SendDataTCPServer.js: TCP/IP server has received 9581250 bytes of data
,2015-11-20T12:47:04.367Z SendDataTCPServer.js: TCP/IP server has received 9629430 bytes of data
,2015-11-20T12:47:04.382Z SendDataTCPServer.js: TCP/IP server has received 9692940 bytes of data
,2015-11-20T12:47:04.398Z SendDataTCPServer.js: TCP/IP server has received 9758640 bytes of data
,2015-11-20T12:47:04.412Z SendDataTCPServer.js: TCP/IP server has received 9802298 bytes of data
,2015-11-20T12:47:04.426Z SendDataTCPServer.js: TCP/IP server has received 9870330 bytes of data
,2015-11-20T12:47:04.441Z SendDataTCPServer.js: TCP/IP server has received 9916320 bytes of data
,2015-11-20T12:47:04.455Z SendDataTCPServer.js: TCP/IP server has received 9946980 bytes of data
,2015-11-20T12:47:04.468Z SendDataTCPServer.js: TCP/IP server has received 9990780 bytes of data
,2015-11-20T12:47:04.482Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20 13:47:04.493 ThaliTest[1024:782126] server session: not connected Apple-IpadAir2-1_PT545
,2015-11-20 13:47:04.986 ThaliTest[1024:781290] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tru,e
,2015-11-20 13:47:13.780 ThaliTest[1024:781290] multipeer session: restart
,2015-11-20 13:47:13.898 ThaliTest[1024:781290] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:13.899 ThaliTest[1024:781290] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:47:13.900 ThaliTest[1024:781290] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:13.900 ThaliTest[1024:781290] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:47:25.903 ThaliTest[1024:782267] client session: not connected Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:47:25.903 ThaliTest[1024:782267] client session: onLinkFailure: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:47:25.904 ThaliTest[1,024:782267] client session: disconnect
2015-11-20 13:47:25.905 ThaliTest[1024:782267] client session: stateChange:1->0 Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:47:25.906 ThaliTest[1024:782267] client session: fireConnectCallback: Apple-Iphone5s-1_PT,497.PdI1bg==
2015-11-20 13:47:25.906 ThaliTest[1024:782267] jxcore: connect: fail: Peer disconnected
,2015-11-20T12:47:25.908Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T12:47:25.909Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T12:47:25.909Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:47:26.911Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:47:26.912Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:47:27.918 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:47:27.919 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:47:27.919Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg=,=
2015-11-20T12:47:27.920Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT497.PdI1bg== with availability status: true
2015-11-20T12:47:27.920Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:47:27.920Z SendDataConnector.js: do connect now
,2015-11-20 13:47:27.921 ThaliTest[1024:781408] jxcore: connect Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:47:27.922 ThaliTest[1024:781408] client session: connect
2015-11-20 13:47:27.923 ThaliTest[1024:781408] client session: stateChange:0->1 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:47:38.479 ThaliTest[1024:781290] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:41.623 ThaliTest[1024:781290] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:47:43.779 ThaliTest[1024:781290] multipeer session: restart
,2015-11-20 13:47:43.808 ThaliTest[1024:781290] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:47:43.809 ThaliTest[1024:781290] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:47:43.810 ThaliTest[1024:781290] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:43.812 ThaliTest[1024:781290] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:48:00.933 ThaliTest[1024:782326] client session: not connected Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:48:00.934 ThaliTest[1024:782326] client session: onLinkFailure: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:48:00.934 ThaliTest[1,024:782326] client session: disconnect
2015-11-20 13:48:00.935 ThaliTest[1024:782326] client session: stateChange:1->0 Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:48:00.935 ThaliTest[1024:782326] client session: fireConnectCallback: Apple-Iphone5s-1_PT,497.PdI1bg==
2015-11-20 13:48:00.936 ThaliTest[1024:782326] jxcore: connect: fail: Peer disconnected
2015-11-20T12:48:00.937Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-11-20T12:48:00.938Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T12:48:00.938Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:48:01.948Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:48:01.949Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:48:02.956 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:48:02.956 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:48:02.957Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg=,=
2015-11-20T12:48:02.958Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT497.PdI1bg== with availability status: true
2015-11-20T12:48:02.958Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:48:02.958Z SendDataConnector.js: do connect now
,2015-11-20 13:48:02.959 ThaliTest[1024:781408] jxcore: connect Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:48:02.960 ThaliTest[1024:781408] client session: connect
2015-11-20 13:48:02.961 ThaliTest[1024:781408] client session: stateChange:0->1 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:48:13.779 ThaliTest[1024:781290] multipeer session: restart
,2015-11-20 13:48:13.807 ThaliTest[1024:781290] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:13.808 ThaliTest[1024:781290] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:48:13.809 ThaliTest[1024:781290] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:48:14.648 ThaliTest[1024:781290] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:48:35.968 ThaliTest[1024:782417] client session: not connected Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:48:35.969 ThaliTest[1024:782417] client session: onLinkFailure: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:48:35.970 ThaliTest[1,024:782417] client session: disconnect
2015-11-20 13:48:35.970 ThaliTest[1024:782417] client session: stateChange:1->0 Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:48:35.971 ThaliTest[1024:782417] client session: fireConnectCallback: Apple-Iphone5s-1_PT,497.PdI1bg==
2015-11-20 13:48:35.971 ThaliTest[1024:782417] jxcore: connect: fail: Peer disconnected
,2015-11-20T12:48:35.973Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T12:48:35.974Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T12:48:35.974Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:48:36.977Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:48:36.978Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:48:37.988 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:48:37.989 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:48:37.989Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg=,=
2015-11-20T12:48:37.990Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT497.PdI1bg== with availability status: true
,2015-11-20T12:48:37.990Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:48:37.991Z SendDataConnector.js: do connect now
,2015-11-20 13:48:37.992 ThaliTest[1024:781408] jxcore: connect Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:48:37.993 ThaliTest[1024:781408] client session: connect
2015-11-20 13:48:37.993 ThaliTest[1024:781408] client session: stateChange:0->1 Apple-Ip,hone5s-1_PT497.PdI1bg==
,2015-11-20 13:48:41.377 ThaliTest[1024:781290] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:48:41.378 ThaliTest[1024:781290] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2015-11-20 13:48:41.382 ThaliTest[1024:781290] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":",Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:48:43.779 ThaliTest[1024:781290] multipeer session: restart
,2015-11-20 13:48:43.877 ThaliTest[1024:781290] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:48:43.878 ThaliTest[1024:781290] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:48:43.881 ThaliTest[1024:781290] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:48:43.882 ThaliTest[1024:781290] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:49:11.003 ThaliTest[1024:782637] client session: not connected Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:49:11.004 ThaliTest[1024:782637] client session: onLinkFailure: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:49:11.004 ThaliTest[1,024:782637] client session: disconnect
2015-11-20 13:49:11.005 ThaliTest[1024:782637] client session: stateChange:1->0 Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:49:11.005 ThaliTest[1024:782637] client session: fireConnectCallback: Apple-Iphone5s-1_PT,497.PdI1bg==
2015-11-20 13:49:11.006 ThaliTest[1024:782637] jxcore: connect: fail: Peer disconnected
,2015-11-20T12:49:11.008Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T12:49:11.008Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-20T12:49:11.010Z SendDataConnector.js: CLIENT Stop now
,2015-11-20 13:49:11.011 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:49:11.012 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:49:11.013Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg==
,---- round done--------
device[2]: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:11.017Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:11.018Z SendDataConnector.js: ReStart called with peer Apple-Iphone,6-1_PT8859.CKR/JA==
,2015-11-20 13:49:12.019 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:49:12.019 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:49:12.021Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:12.022Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone6-1_PT8859.CKR/JA== with availability status: true
2015-11-20T12:49:12.022Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-1,1-20T12:49:12.022Z SendDataConnector.js: do connect now
,2015-11-20 13:49:12.023 ThaliTest[1024:781408] jxcore: connect Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:12.024 ThaliTest[1024:781408] client session: connect
2015-11-20 13:49:12.025 ThaliTest[1024:781408] client session: stateChange:0->1 Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:13.779 ThaliTest[1024:781290] multipeer session: restart
,2015-11-20 13:49:13.849 ThaliTest[1024:781290] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:13.850 ThaliTest[1024:781290] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:49:13.851 ThaliTest[1024:781290] client: f,ound peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:13.853 ThaliTest[1024:781290] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:49:15.092 ThaliTest[1024:782641] client session: connected
2015-11-20 13:49:15.093 ThaliTest[1024:782641] client session: stateChange:1->2 Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:15.538 ThaliTest[1024:782637] client session: fireConnectCallback: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:15.539 ThaliTest[1024:782637] jxcore: connect: success
2015-11-20T12:49:15.541Z SendDataConnector.js: CLIENT connected to 56039, error: null
,2015-11-20T12:49:15.542Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:49:15.545 ThaliTest[1024:781290] client: relay established
2015-11-20 13:49:15.546 ThaliTest[1024:781290] client: new accepted socket: 0x1c850590
,2015-11-20T12:49:15.558Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:49:20.198Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:23.489Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:23.490Z SendDataConnector.js: CLIENT is data received : 210000
,2015-11-20T12:49:25.479Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:25.480Z SendDataConnector.js: CLIENT is data received : 440000
,2015-11-20T12:49:29.974Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:29.975Z SendDataConnector.js: CLIENT is data received : 480000
,2015-11-20T12:49:30.502Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:30.503Z SendDataConnector.js: CLIENT is data received : 3890000
,2015-11-20T12:49:30.714Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:30.715Z SendDataConnector.js: CLIENT is data received : 5930000
,2015-11-20T12:49:31.046Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:31.047Z SendDataConnector.js: CLIENT is data received : 6630000
,2015-11-20T12:49:31.453Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:31.454Z SendDataConnector.js: CLIENT is data received : 7500000
,2015-11-20T12:49:31.874Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:31.875Z SendDataConnector.js: CLIENT is data received : 8110000
,2015-11-20T12:49:31.995Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:31.997Z SendDataConnector.js: CLIENT is data received : 8200000
,2015-11-20T12:49:32.095Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:32.096Z SendDataConnector.js: CLIENT is data received : 8400000
,2015-11-20T12:49:32.641Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:32.641Z SendDataConnector.js: CLIENT is data received : 9790000
,2015-11-20T12:49:32.655Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:32.655Z SendDataConnector.js: CLIENT is data received : 9840000
,2015-11-20T12:49:32.669Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:32.670Z SendDataConnector.js: CLIENT is data received : 9890000
,2015-11-20T12:49:32.684Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:32.684Z SendDataConnector.js: CLIENT is data received : 9930000
,2015-11-20T12:49:32.696Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:32.696Z SendDataConnector.js: CLIENT is data received : 9980000
,2015-11-20T12:49:32.707Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:32.708Z SendDataConnector.js: CLIENT is data received : 9990000
,2015-11-20T12:49:42.709Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:49:42.710Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:49:42.713Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20 13:49:42.713 ThaliTest[1024:781290] client: socket closed
2015-11-20 13:49:42.714 ThaliTest[1024:781290] client relay: socket disconnected
2015-11-20T12:49:42.714Z SendDat,aConnector.js: ----------------- closeClientSocket
2015-11-20 13:49:42.715 ThaliTest[1024:781290] client relay: 0x1c850590 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b78c490 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-20 13:49:42.715 ThaliTest[1024:781290] client session: socket closed: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:42.716 ThaliTest[1024:781290] client session: onLinkFailure: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:42.717 ThaliTest[,1024:781290] client session: disconnect
2015-11-20 13:49:42.717 ThaliTest[1024:781290] client session: stateChange:2->0 Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:42.719 ThaliTest[1024:781290] client session: fireConnectionErrorEvent: Apple-Iphone6,-1_PT8859.CKR/JA==
,2015-11-20T12:49:43.715Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:43.715Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:43.779 ThaliTest[1024:781290] multipeer session: restart
,2015-11-20 13:49:44.453 ThaliTest[1024:781290] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:44.456 ThaliTest[1024:781290] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:49:44.457 ThaliTest[1024:781290] client: f,ound peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:49:44.458 ThaliTest[1024:781290] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:49:44.727 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:49:44.728 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:49:44.728Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA=,=
2015-11-20T12:49:44.729Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT8859.CKR/JA== with availability status: true
2015-11-20T12:49:44.729Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:44.729Z SendDataConnector.js: do connect now
2015-11-20 13:49:44.730 ThaliTest[1024:781408] jxcore: connect Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:44.731 ThaliTest[1024:781408] client session: connect
,2015-11-20 13:49:44.732 ThaliTest[1024:781408] client session: stateChange:0->1 Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:52.145 ThaliTest[1024:781290] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:52.146 ThaliTest[1024:781290] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:52.146 ThaliTest[1024:781290] cl,ient session: onLinkFailure: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:52.147 ThaliTest[1024:781290] client session: disconnect
2015-11-20 13:49:52.147 ThaliTest[1024:781290] client session: stateChange:1->0 Apple-Iphone6-1_PT8859.CKR/JA==
2015-1,1-20 13:49:52.148 ThaliTest[1024:781290] client session: fireConnectCallback: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:52.148 ThaliTest[1024:781290] jxcore: connect: fail: Peer disconnected
2015-11-20T12:49:52.150Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer disconnected
2015-11-20T12:49:52.150Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T12:49:52.151Z SendDataConnector.js: tryAgain afer: 1000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
,2015-11-20T12:49:53.160Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:53.160Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:54.169 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:49:54.169 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:49:54.170Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA=,=
2015-11-20T12:49:54.171Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT8859.CKR/JA== with availability status: true
,2015-11-20T12:49:54.171Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:54.171Z SendDataConnector.js: do connect now
2015-11-20 13:49:54.172 ThaliTest[1024:781408] jxcore: connect Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:54.173 ThaliTest[1024:781408] client: connect: unreachable Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:54.173 ThaliTest[1024:781408] jxcore: connect: fail: Peer unreachable
,2015-11-20T12:49:54.175Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-20T12:49:54.175Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-11-20T12:49:54.176Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:49:55.182Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:55.182Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:56.189 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:49:56.190 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:49:56.191Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA=,=
2015-11-20T12:49:56.191Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT8859.CKR/JA== with availability status: true
,2015-11-20T12:49:56.192Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:56.192Z SendDataConnector.js: do connect now
,2015-11-20 13:49:56.193 ThaliTest[1024:781408] jxcore: connect Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:56.194 ThaliTest[1024:781408] client: connect: unreachable Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:56.194 ThaliTest[1024:781408] jxco,re: connect: fail: Peer unreachable
2015-11-20T12:49:56.195Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-20T12:49:56.195Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-11-20T12:49:56.196Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:49:57.196Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:49:57.197Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:58.206 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:49:58.207 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:49:58.207Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA=,=
2015-11-20T12:49:58.208Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT8859.CKR/JA== with availability status: true
,2015-11-20T12:49:58.208Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:49:58.209Z SendDataConnector.js: do connect now
,2015-11-20 13:49:58.209 ThaliTest[1024:781408] jxcore: connect Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:58.210 ThaliTest[1024:781408] client: connect: unreachable Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:49:58.211 ThaliTest[1024:781408] jxcore: connect: fail: Peer unreachable
,2015-11-20T12:49:58.212Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-20T12:49:58.212Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-11-20T12:49:58.213Z SendDataConnector.js: CLIENT Stop now
2015-11-20T12:49:58.213Z SendDataConnector.js: Stop data retrieving timer
,2015-11-20 13:49:58.214 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:49:58.214 ThaliTest[1024:781408] jxcore: disconnect: fail
,2015-11-20T12:49:58.215Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:49:58.222Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:49:58.223Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:49:59.232 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:49:59.233 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:49:59.233Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6611.klJDeA=,=
2015-11-20T12:49:59.234Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5-1_PT6611.klJDeA== with availability status: true
2015-11-20T12:49:59.234Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:49:59.235Z SendDataConnector.js: do connect now
,2015-11-20 13:49:59.237 ThaliTest[1024:781408] jxcore: connect Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:49:59.238 ThaliTest[1024:781408] client session: connect
2015-11-20 13:49:59.238 ThaliTest[1024:781408] client session: stateChange:0->1 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:01.767 ThaliTest[1024:782708] client session: connected
2015-11-20 13:50:01.768 ThaliTest[1024:782708] client session: stateChange:1->2 Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:01.771 ThaliTest[1024:782708] client session: fireCo,nnectCallback: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:01.772 ThaliTest[1024:782708] jxcore: connect: success
2015-11-20T12:50:01.774Z SendDataConnector.js: CLIENT connected to 56046, error: null
,2015-11-20T12:50:01.774Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:50:01.778 ThaliTest[1024:781290] client: relay established
2015-11-20 13:50:01.779 ThaliTest[1024:781290] client: new accepted socket: 0x1c843a90
,2015-11-20T12:50:01.791Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:50:06.412Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:14.230 ThaliTest[1024:781290] multipeer session: restart
,2015-11-20 13:50:15.429 ThaliTest[1024:781290] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:15.432 ThaliTest[1024:781290] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:50:15.433 ThaliTest[1024:781290] client: f,ound peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:50:16.423Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:50:16.424Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:50:16.426Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20 13:50:16.426 ThaliTest[1024:781290] client: socket closed
2015-11-20T12:50:16.427Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 13:50:16.427 ThaliT,est[1024:781290] client relay: socket disconnected
2015-11-20 13:50:16.427 ThaliTest[1024:781290] client relay: 0x1c843a90 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b7a4120 {NSLocalize,dDescription=Socket closed by remote peer} 
,2015-11-20 13:50:16.428 ThaliTest[1024:781290] client session: socket closed: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:16.429 ThaliTest[1024:781290] client session: onLinkFailure: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:16.429 ThaliTest[1024:781290] client session: disconnect
,2015-11-20 13:50:16.430 ThaliTest[1024:781290] client session: stateChange:2->0 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:16.431 ThaliTest[1024:781290] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:50:17.433Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:50:17.434Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:18.440 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:50:18.441 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:50:18.442Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6611.klJDeA=,=
2015-11-20T12:50:18.442Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT6611.klJDeA== with availability status: true
2015-11-20T12:50:18.442Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:50:18.443Z SendDataConnector.js: do connect now
2015-11-20 13:50:18.443 ThaliTest[1024:781408] jxcore: connect Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:18.444 ThaliTest[1024:781408] client session: connect
,2015-11-20 13:50:18.445 ThaliTest[1024:781408] client session: stateChange:0->1 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:21.192 ThaliTest[1024:782772] client session: connected
,2015-11-20 13:50:21.192 ThaliTest[1024:782772] client session: stateChange:1->2 Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:21.196 ThaliTest[1024:782772] client session: fireConnectCallback: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:21.197 ThaliTest[1024:782772] jxcore: connect: success
,2015-11-20T12:50:21.200Z SendDataConnector.js: CLIENT connected to 56050, error: null
2015-11-20T12:50:21.200Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:50:21.203 ThaliTest[1024:781290] client: relay established
2015-11-20 13:50:21.204 ThaliTest[1024:781290] client: new accepted socket: 0x1b524e60
,2015-11-20T12:50:21.216Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:50:25.803Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:50:35.806Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:50:35.807Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:50:35.808Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:50:35.809Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20 13:50:35.810 ThaliTest[1024:781290] client: socket closed
2015-11-20 13:50:35.811 ThaliTest[1024:781290] client relay: socket disconnected
2015-11-20 13:50:35.812 ThaliTest[1024:781290] client relay: 0x1b524e60 disconnected with error Error Do,main=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b690980 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 13:50:35.812 ThaliTest[1024:781290] client session: socket closed: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:35.813 ThaliTest[1024:781290] client session: onLinkFailure: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:35.813 ThaliTest[1024:781290] client session: disconnect
2015-11-20 13:50:35.814 ThaliTest[1024:781290] client session: stateCh,ange:2->0 Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:35.815 ThaliTest[1024:781290] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:50:36.815Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:50:36.816Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:37.820 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:50:37.821 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:50:37.822Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6611.klJDeA=,=
2015-11-20T12:50:37.822Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT6611.klJDeA== with availability status: true
2015-11-20T12:50:37.822Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:50:37.823Z SendDataConnector.js: do connect now
2015-11-20 13:50:37.823 ThaliTest[1024:781408] jxcore: connect Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:37.824 ThaliTest[1024:781408] client session: connect
,2015-11-20 13:50:37.826 ThaliTest[1024:781408] client session: stateChange:0->1 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:40.003 ThaliTest[1024:782772] client session: connected
2015-11-20 13:50:40.004 ThaliTest[1024:782772] client session: stateChange:1->2 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:40.009 ThaliTest[1024:782753] client session: fireConnectCallback: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:40.010 ThaliTest[1024:782753] jxcore: connect: success
2015-11-20T12:50:40.011Z SendDataConnector.js: CLIENT connected to 56052, error: null
2015-11-20T12:50:40.012Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:50:40.016 ThaliTest[1024:781290] client: relay established
2015-11-20 13:50:40.017 ThaliTest[1024:781290] client: new accepted socket: 0x1b524e60
,2015-11-20T12:50:40.029Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:50:43.777 ThaliTest[1024:781290] multipeer session: restart
,2015-11-20 13:50:43.790 ThaliTest[1024:781290] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:43.791 ThaliTest[1024:781290] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
2015-11-20 13:50:43.791 ThaliTest[1024:781290] client: f,ound peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:50:44.737Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:50:54.743Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:50:54.744Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:50:54.745Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20 13:50:54.745 ThaliTest[1024:781290] client: socket closed
2015-11-20T12:50:54.745Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 13:50:54.746 ThaliT,est[1024:781290] client relay: socket disconnected
2015-11-20 13:50:54.747 ThaliTest[1024:781290] client relay: 0x1b524e60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1759d120 {NSLocalize,dDescription=Socket closed by remote peer} 
2015-11-20 13:50:54.748 ThaliTest[1024:781290] client session: socket closed: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:54.748 ThaliTest[1024:781290] client session: onLinkFailure: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:54.749 ThaliTest[1024:781290] client session: disconnect
2015-11-20 13:50:54.749 ThaliTest[1024:781290] client session: stateCh,ange:2->0 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:54.751 ThaliTest[1024:781290] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:50:55.749Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:50:55.750Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:56.758 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:50:56.758 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:50:56.759Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6611.klJDeA=,=
2015-11-20T12:50:56.760Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT6611.klJDeA== with availability status: true
,2015-11-20T12:50:56.760Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:50:56.760Z SendDataConnector.js: do connect now
,2015-11-20 13:50:56.761 ThaliTest[1024:781408] jxcore: connect Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:56.762 ThaliTest[1024:781408] client session: connect
2015-11-20 13:50:56.763 ThaliTest[1024:781408] client session: stateChange:0->1 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:59.385 ThaliTest[1024:782703] client session: connected
2015-11-20 13:50:59.386 ThaliTest[1024:782703] client session: stateChange:1->2 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:59.392 ThaliTest[1024:782772] client session: fireConnectCallback: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:59.393 ThaliTest[1024:782772] jxcore: connect: success
2015-11-20T12:50:59.394Z SendDataConnector.js: CLIENT connected to, 56056, error: null
2015-11-20T12:50:59.395Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:50:59.398 ThaliTest[1024:781290] client: relay established
,2015-11-20 13:50:59.399 ThaliTest[1024:781290] client: new accepted socket: 0x1b2890f0
,2015-11-20T12:50:59.411Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:51:04.022Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:51:13.777 ThaliTest[1024:781290] multipeer session: restart
,2015-11-20 13:51:13.804 ThaliTest[1024:781290] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:51:13.805 ThaliTest[1024:781290] client: found peer: Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:51:13.807 ThaliTest[1024:781290] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:51:14.033Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:51:14.034Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:51:14.036Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20T12:51:14.036Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 13:51:14.036 ThaliTest[1024:781290] client: socket closed
2015-11-20 13:51:14.037 ThaliT,est[1024:781290] client relay: socket disconnected
,2015-11-20 13:51:14.037 ThaliTest[1024:781290] client relay: 0x1b2890f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1763f4c0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11,-20 13:51:14.038 ThaliTest[1024:781290] client session: socket closed: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:51:14.039 ThaliTest[1024:781290] client session: onLinkFailure: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:51:14.039 ThaliTest[1024:781290] client session: disconnect
2015-11-20 13:51:14.040 ThaliTest[1024:781290] client session: stateCh,ange:2->0 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:51:14.042 ThaliTest[1024:781290] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:51:15.046Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:51:15.046Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:51:16.053 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:51:16.054 ThaliTest[1024:781408] jxcore: disconnect: fail
2015-11-20T12:51:16.054Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6611.klJDeA=,=
,2015-11-20T12:51:16.056Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT6611.klJDeA== with availability status: true
2015-11-20T12:51:16.056Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-1,1-20T12:51:16.057Z SendDataConnector.js: do connect now
,2015-11-20 13:51:16.058 ThaliTest[1024:781408] jxcore: connect Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:51:16.059 ThaliTest[1024:781408] client session: connect
2015-11-20 13:51:16.059 ThaliTest[1024:781408] client session: stateChange:0->1 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:51:18.709 ThaliTest[1024:782870] client session: connected
2015-11-20 13:51:18.710 ThaliTest[1024:782870] client session: stateChange:1->2 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:51:18.715 ThaliTest[1024:782821] client session: fireConnectCallback: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:51:18.716 ThaliTest[1024:782821] jxcore: connect: success
2015-11-20T12:51:18.718Z SendDataConnector.js: CLIENT connected to 56060, error: null
,2015-11-20T12:51:18.720Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:51:18.724 ThaliTest[1024:781290] client: relay established
2015-11-20 13:51:18.724 ThaliTest[1024:781290] client: new accepted socket: 0x1b524e60
,2015-11-20T12:51:18.737Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:51:23.338Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:51:33.344Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:51:33.346Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:51:33.347Z SendDataConnector.js: CLIENT Stop now
2015-11-20 13:51:33.348 ThaliTest[1024:781290] client: socket closed
2015-11-20T12:51:33.349Z SendDataConnector.js: Stop data retrieving timer
2015-11-20 13:51:33.349 ThaliTest[1024:781290] ,client relay: socket disconnected
2015-11-20 13:51:33.350 ThaliTest[1024:781290] client relay: 0x1b524e60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c846b90 {NSLocalizedDescription=Sock,et closed by remote peer} 
2015-11-20 13:51:33.350 ThaliTest[1024:781408] jxcore: disconnect
2015-11-20 13:51:33.350 ThaliTest[1024:781290] client session: socket closed: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:51:33.351 ThaliTest[1024:781408] client session: disconnectFromPeer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:51:33.351 ThaliTest[1024:781408] client session: disconnect
2015-11-20 13:51:33.352 ThaliTest[1024:781408] client session: st,ateChange:2->0 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:51:33.354 ThaliTest[1024:781290] client session: onLinkFailure: Apple-Iphone5-1_PT6611.klJDeA==
,Assertion failed: ([self connectionState] != THEPeerSessionStateNotConnected), function -[THEMultipeerClientSession onLinkFailure], file /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerClientSession.m, line 12,4.
2015-11-20 13:51:33.354 ThaliTest[1024:781408] jxcore: disconnect: success
,Process 1024 stopped
* thread #1: tid = 0xbebea, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x38dc0df0 <+8>:  blo    0x38dc0e08                ; <+32>
    0x38dc0df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x38dc0df8 <+16>: ldr    r12, [pc, r12]
    0x38dc0dfc <+20>: b      0x38dc0e04                ; <+28>
,* thread #1: tid = 0xbebea, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x38e3ecc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x38d5c908 libsystem_c.dylib`abort + 76
    frame #3: 0x38d3c368 libsystem_c.dylib`__assert_rtn + 92
    frame #4: 0x0011382a ThaliTest`-[THEMultipeerClientSession onLinkFailure] + 290
    frame #5: 0x0011402c ThaliTest`-[THEMultipeerClientSession didDisconnectFromPeer] + 104
    frame #6: 0x001162b2 ThaliTest`-[THEMultipeerClientSocketRelay socketDidDisconnect:withError:] + 182
    frame #7: 0x00120a92 ThaliTest`__33-[GCDAsyncSocket closeWithError:]_block_invoke + 70
    frame #8: 0x38cd52e2 libdispatch.dylib`<redacted> + 10
    frame #9: 0x38cd52ce libdispatch.dylib`<redacted> + 22
    frame #10: 0x38cd8d2e libdispatch.dylib`_dispatch_main_queue_callback_4CF + 1330
    frame #11: 0x2a86d618 CoreFoundation`<redacted> + 8
    frame #12: 0x2a86bd18 CoreFoundation`<redacted> + 1512
    frame #13: 0x2a7b93b0 CoreFoundation`CFRunLoopRunSpecific + 476
    frame #14: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #15: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #16: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #17: 0x000ff692 ThaliTest`main + 50

```
