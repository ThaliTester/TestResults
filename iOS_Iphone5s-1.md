#### Test 51335028813a553_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028813a553/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2A4F609E-0F18-4665-93F4-E643A1270D19/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2A4F609E-0F18-4665-93F4-E643A1270D19/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028813a553/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028813a553/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F9D8D12A-18DC-4825-A5F1-46DF92F95B29/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51172"
,(lldb)     command script import "/tmp/2A4F609E-0F18-4665-93F4-E643A1270D19/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 12:59:48.237 ThaliTest[1010:776684] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3D084BDC-D026-40BB-8274-83BC266A98C8/Library/Cookies/Cookies.binarycookies
,2015-11-20 12:59:48.654 ThaliTest[1010:776684] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 12:59:48.655 ThaliTest[1010:776684] Multi-tasking -> Device: YES, App: YES
,2015-11-20 12:59:48.664 ThaliTest[1010:776684] Unlimited access to network resources
,2015-11-20 12:59:48.671 ThaliTest[1010:776684] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 12:59:52.263 ThaliTest[1010:776684] Resetting plugins due to page load.
,2015-11-20 12:59:52.725 ThaliTest[1010:776684] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/F9D8D12A-18DC-4825-A5F1-46DF92F95B29/ThaliTest.app/www/index.html
,2015-11-20 12:59:52.877 ThaliTest[1010:776684] JXcore Cordova plugin initializing
2015-11-20 12:59:52.880 ThaliTest[1010:776807] JXcore instance initializing
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
found interfaceName: en0
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
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
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
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
-iface: IPv6 is internal :, false, has ip: fe80::e429:c7ff:fe67:1f88
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"10000000\",\"conReTryTimeout\":\"1000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 55847
2015-11-20 13:10:17.130 ThaliTest[1010:776807] jxcore: startBroadcasting
,2015-11-20 13:10:17.143 ThaliTest[1010:776807] server: starting Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:17.144 ThaliTest[1010:776807] multipeer session: start timer: 0x18655aa0
2015-11-20 13:10:17.145 ThaliTest[1010:776807] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT497
2015-11-20 13:10:17.146 ThaliTest[1010:776807] jxcore: st,artBroadcasting: success
StartBroadcasting started ok
,2015-11-20T12:10:17.149Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-20 13:10:17.550 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:17.557Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:17.558Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:10:18.167 ThaliTest[1010:776684] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7072.5zbvNA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: t,rue
,2015-11-20 13:10:18.424 ThaliTest[1010:776684] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2716.py/N2Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:10:18.564 ThaliTest[1010:776807] jxcore: disconnect
2015-11-20 13:10:18.565 ThaliTest[1010:776807] jxcore: disconnect: fail
2015-11-20T12:10:18.566Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2043.OU3s0w=,=
,2015-11-20T12:10:18.567Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone6-1_PT2043.OU3s0w== with availability status: true
2015-11-20T12:10:18.567Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-1,1-20T12:10:18.569Z SendDataConnector.js: do connect now
,2015-11-20 13:10:18.570 ThaliTest[1010:776807] jxcore: connect Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:10:18.571 ThaliTest[1010:776807] client session: connect
2015-11-20 13:10:18.572 ThaliTest[1010:776807] client session: stateChange:0->1 Apple-Ip,hone6-1_PT2043.OU3s0w==
,2015-11-20 13:10:18.705 ThaliTest[1010:776684] multipeer session: reset timer
2015-11-20 13:10:18.705 ThaliTest[1010:776684] multipeer session: stop timer
2015-11-20 13:10:18.705 ThaliTest[1010:776684] multipeer session: start timer: 0x18655aa0
2015-11-20 13:10:18.706 ThaliTest[1010:776684] server session: connect
2015-11-20 13:10:18.706 ThaliTest[1010:776684] server session: stateChange:0->1 Apple-Iphone6-1_PT2043
,2015-11-20 13:10:18.711 ThaliTest[1010:776684] server: accepting invitation Apple-Iphone6-1_PT2043
,2015-11-20 13:10:21.018 ThaliTest[1010:777681] server session: connected
2015-11-20 13:10:21.019 ThaliTest[1010:777681] server session: stateChange:1->2 Apple-Iphone6-1_PT2043
,2015-11-20 13:10:21.035 ThaliTest[1010:776684] server relay: connected (to port: 55847)
,2015-11-20T12:10:21.044Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:10:22.406 ThaliTest[1010:777689] client session: connected
2015-11-20 13:10:22.407 ThaliTest[1010:777689] client session: stateChange:1->2 Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:10:22.413 ThaliTest[1010:777676] client session: fireConnectCallback: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:10:22.414 ThaliTest[1010:777676] jxcore: connect: success
,2015-11-20T12:10:22.416Z SendDataConnector.js: CLIENT connected to 55852, error: null
2015-11-20T12:10:22.417Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:10:22.421 ThaliTest[1010:776684] client: relay established
2015-11-20 13:10:22.422 ThaliTest[1010:776684] client: new accepted socket: 0x187c0840
,2015-11-20T12:10:22.432Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:10:24.026 ThaliTest[1010:776684] multipeer session: reset timer
2015-11-20 13:10:24.027 ThaliTest[1010:776684] multipeer session: stop timer
2015-11-20 13:10:24.027 ThaliTest[1010:776684] multipeer session: start timer: 0x18655aa0
2015-11-20 13:10:24.027 ThaliTest[1010:776684] server session: connect
2015-11-20 13:10:24.027 ThaliTest[1010:776684] server session: stateChange:0->1 Apple-Iphone5-1_PT2716
,2015-11-20 13:10:24.031 ThaliTest[1010:776684] server: accepting invitation Apple-Iphone5-1_PT2716
,2015-11-20 13:10:26.198 ThaliTest[1010:777676] server session: connected
2015-11-20 13:10:26.198 ThaliTest[1010:777676] server session: stateChange:1->2 Apple-Iphone5-1_PT2716
,2015-11-20 13:10:26.490 ThaliTest[1010:776684] server relay: connected (to port: 55847)
,2015-11-20T12:10:27.553Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:27.800Z SendDataTCPServer.js: TCP/IP server has received 131072 bytes of data
,2015-11-20T12:10:27.824Z SendDataTCPServer.js: TCP/IP server has received 262144 bytes of data
,2015-11-20T12:10:27.831Z SendDataTCPServer.js: TCP/IP server has received 393216 bytes of data
,2015-11-20T12:10:27.833Z SendDataTCPServer.js: TCP/IP server has received 524288 bytes of data
,2015-11-20T12:10:27.836Z SendDataTCPServer.js: TCP/IP server has received 655360 bytes of data
,2015-11-20T12:10:27.845Z SendDataTCPServer.js: TCP/IP server has received 786432 bytes of data
,2015-11-20T12:10:27.848Z SendDataTCPServer.js: TCP/IP server has received 917504 bytes of data
,2015-11-20T12:10:27.851Z SendDataTCPServer.js: TCP/IP server has received 1048576 bytes of data
,2015-11-20T12:10:27.854Z SendDataTCPServer.js: TCP/IP server has received 1179648 bytes of data
,2015-11-20T12:10:27.859Z SendDataTCPServer.js: TCP/IP server has received 1310720 bytes of data
,2015-11-20T12:10:27.862Z SendDataTCPServer.js: TCP/IP server has received 1441792 bytes of data
,2015-11-20T12:10:27.864Z SendDataTCPServer.js: TCP/IP server has received 1572864 bytes of data
,2015-11-20T12:10:27.866Z SendDataTCPServer.js: TCP/IP server has received 1703936 bytes of data
,2015-11-20T12:10:27.868Z SendDataTCPServer.js: TCP/IP server has received 1835008 bytes of data
,2015-11-20T12:10:27.870Z SendDataTCPServer.js: TCP/IP server has received 1966080 bytes of data
,2015-11-20T12:10:27.872Z SendDataTCPServer.js: TCP/IP server has received 2097152 bytes of data
,2015-11-20T12:10:27.874Z SendDataTCPServer.js: TCP/IP server has received 2228224 bytes of data
,2015-11-20T12:10:27.875Z SendDataTCPServer.js: TCP/IP server has received 2342732 bytes of data
,2015-11-20T12:10:27.877Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:10:28.657Z SendDataTCPServer.js: TCP/IP server has received 2350924 bytes of data
,2015-11-20T12:10:29.869Z SendDataTCPServer.js: TCP/IP server has received 2481996 bytes of data
,2015-11-20T12:10:29.879Z SendDataTCPServer.js: TCP/IP server has received 2584396 bytes of data
,2015-11-20T12:10:34.462Z SendDataTCPServer.js: TCP/IP server has received 2633548 bytes of data
2015-11-20T12:10:34.479Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:34.482Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-20T12:10:34.501Z SendDataTCPServer.js: TCP/IP server has received 2764620 bytes of data
,2015-11-20T12:10:34.505Z SendDataTCPServer.js: TCP/IP server has received 2850636 bytes of data
,2015-11-20T12:10:34.697Z SendDataTCPServer.js: TCP/IP server has received 2852684 bytes of data
,2015-11-20T12:10:35.034Z SendDataTCPServer.js: TCP/IP server has received 2963276 bytes of data
,2015-11-20T12:10:35.063Z SendDataTCPServer.js: TCP/IP server has received 3094348 bytes of data
,2015-11-20T12:10:35.067Z SendDataTCPServer.js: TCP/IP server has received 3180364 bytes of data
,2015-11-20T12:10:42.440Z SendDataTCPServer.js: TCP/IP server has received 3286860 bytes of data
,2015-11-20T12:10:42.448Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:42.449Z SendDataConnector.js: CLIENT is data received : 3080000
,2015-11-20 13:10:42.789 ThaliTest[1010:777688] server session: not connected Apple-Iphone5-1_PT2716
,2015-11-20T12:10:43.691Z SendDataTCPServer.js: TCP/IP server has received 3288908 bytes of data
2015-11-20T12:10:43.692Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:43.693Z SendDataConnector.js: CLIENT is data received : 3090000
,2015-11-20T12:10:44.002Z SendDataTCPServer.js: TCP/IP server has received 3413836 bytes of data
,2015-11-20T12:10:44.018Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:44.019Z SendDataConnector.js: CLIENT is data received : 3560000
,2015-11-20T12:10:44.035Z SendDataTCPServer.js: TCP/IP server has received 3544908 bytes of data
,2015-11-20T12:10:44.044Z SendDataTCPServer.js: TCP/IP server has received 3675980 bytes of data
,2015-11-20T12:10:44.048Z SendDataTCPServer.js: TCP/IP server has received 3759948 bytes of data
,2015-11-20T12:10:44.080Z SendDataTCPServer.js: TCP/IP server has received 3891020 bytes of data
2015-11-20T12:10:44.097Z SendDataTCPServer.js: TCP/IP server has received 4022092 bytes of data
2015-11-20T12:10:44.103Z SendDataTCPServer.js: TCP/IP server has received 4153164 bytes of data
2015-11-20T12:10:44.117Z SendDataTCPServer.js: TCP/IP server has received 4284236 bytes of data
,2015-11-20T12:10:44.145Z SendDataTCPServer.js: TCP/IP server has received 4415308 bytes of data
,2015-11-20T12:10:44.150Z SendDataTCPServer.js: TCP/IP server has received 4546380 bytes of data
,2015-11-20T12:10:44.153Z SendDataTCPServer.js: TCP/IP server has received 4677452 bytes of data
,2015-11-20T12:10:44.154Z SendDataTCPServer.js: TCP/IP server has received 4704076 bytes of data
,2015-11-20T12:10:45.287Z SendDataTCPServer.js: TCP/IP server has received 4706124 bytes of data
,2015-11-20T12:10:46.897Z SendDataTCPServer.js: TCP/IP server has received 4738892 bytes of data
,2015-11-20T12:10:46.901Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:46.902Z SendDataConnector.js: CLIENT is data received : 4100000
,2015-11-20T12:10:47.225Z SendDataTCPServer.js: TCP/IP server has received 4740940 bytes of data
,2015-11-20T12:10:47.227Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:47.228Z SendDataConnector.js: CLIENT is data received : 6830000
,2015-11-20T12:10:47.264Z SendDataTCPServer.js: TCP/IP server has received 4742988 bytes of data
,2015-11-20T12:10:47.265Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:47.265Z SendDataConnector.js: CLIENT is data received : 6960000
,2015-11-20T12:10:47.552Z SendDataTCPServer.js: TCP/IP server has received 4745036 bytes of data
,2015-11-20T12:10:47.553Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:47.553Z SendDataConnector.js: CLIENT is data received : 8150000
,2015-11-20 13:10:48.312 ThaliTest[1010:776684] multipeer session: reset timer
2015-11-20 13:10:48.313 ThaliTest[1010:776684] multipeer session: stop timer
2015-11-20 13:10:48.313 ThaliTest[1010:776684] multipeer session: start timer: 0x18655aa0
2015-11-,20 13:10:48.313 ThaliTest[1010:776684] server: disconnecting to refresh session (Apple-Iphone5-1_PT2716)
2015-11-20 13:10:48.314 ThaliTest[1010:776684] server session: disconnect
2015-11-20 13:10:48.314 ThaliTest[1010:776684] server session: stateChange:,2->0 Apple-Iphone5-1_PT2716
2015-11-20T12:10:48.319Z SendDataTCPServer.js: TCP/IP server has received 4876108 bytes of data
2015-11-20T12:10:48.322Z SendDataTCPServer.js: TCP/IP server has received 5007180 bytes of data
2015-11-20T12:10:48.325Z SendData,TCPServer.js: TCP/IP server has received 5109580 bytes of data
2015-11-20T12:10:48.326Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:48.326Z SendDataConnector.js: CLIENT is data received : 97300,2015-11-20 13:10:48.334 ThaliTest[1010:776684] server session: connect
,2015-11-20 13:10:48.342 ThaliTest[1010:776684] server session: stateChange:0->1 Apple-Iphone5-1_PT2716
00
2015-11-20 13:10:48.348 ThaliTest[1010:776684] server: accepting invitation Apple-Iphone5-1_PT2716
2015-11-20T12:10:48.361Z SendDataTCPServer.js: T,CP/IP server has received 5240652 bytes of data
2015-11-20T12:10:48.367Z SendDataTCPServer.js: TCP/IP server has received 5332812 bytes of data
2015-11-20T12:10:48.371Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:48.372Z SendDataConnector.js: CLIENT is data received : 9860000
,2015-11-20T12:10:48.375Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-20T12:10:48.375Z SendDataTCPServer.js: TCP/IP server is close
2015-11-20T12:10:48.388Z SendDataTCPServer.js: TCP/IP server has received 5463884 bytes of data
,2015-11-20T12:10:48.396Z SendDataTCPServer.js: TCP/IP server has received 5594956 bytes of data
,2015-11-20T12:10:48.404Z SendDataTCPServer.js: TCP/IP server has received 5726028 bytes of data
,2015-11-20T12:10:48.407Z SendDataTCPServer.js: TCP/IP server has received 5857100 bytes of data
,2015-11-20T12:10:48.413Z SendDataTCPServer.js: TCP/IP server has received 5988172 bytes of data
,2015-11-20T12:10:48.417Z SendDataTCPServer.js: TCP/IP server has received 6119244 bytes of data
,2015-11-20T12:10:48.422Z SendDataTCPServer.js: TCP/IP server has received 6250316 bytes of data
,2015-11-20T12:10:48.427Z SendDataTCPServer.js: TCP/IP server has received 6381388 bytes of data
,2015-11-20T12:10:48.431Z SendDataTCPServer.js: TCP/IP server has received 6438732 bytes of data
,2015-11-20T12:10:48.447Z SendDataTCPServer.js: TCP/IP server has received 6569804 bytes of data
,2015-11-20T12:10:48.451Z SendDataTCPServer.js: TCP/IP server has received 6700876 bytes of data
,2015-11-20T12:10:48.453Z SendDataTCPServer.js: TCP/IP server has received 6831948 bytes of data
,2015-11-20T12:10:48.458Z SendDataTCPServer.js: TCP/IP server has received 6963020 bytes of data
,2015-11-20T12:10:48.463Z SendDataTCPServer.js: TCP/IP server has received 7094092 bytes of data
,2015-11-20T12:10:48.467Z SendDataTCPServer.js: TCP/IP server has received 7225164 bytes of data
,2015-11-20T12:10:48.471Z SendDataTCPServer.js: TCP/IP server has received 7356236 bytes of data
,2015-11-20T12:10:48.473Z SendDataTCPServer.js: TCP/IP server has received 7376716 bytes of data
,2015-11-20T12:10:48.489Z SendDataTCPServer.js: TCP/IP server has received 7507788 bytes of data
,2015-11-20T12:10:48.494Z SendDataTCPServer.js: TCP/IP server has received 7638860 bytes of data
,2015-11-20T12:10:48.497Z SendDataTCPServer.js: TCP/IP server has received 7769932 bytes of data
,2015-11-20T12:10:48.501Z SendDataTCPServer.js: TCP/IP server has received 7901004 bytes of data
,2015-11-20T12:10:48.504Z SendDataTCPServer.js: TCP/IP server has received 8032076 bytes of data
,2015-11-20T12:10:48.506Z SendDataTCPServer.js: TCP/IP server has received 8042316 bytes of data
,2015-11-20T12:10:48.555Z SendDataTCPServer.js: TCP/IP server has received 8173388 bytes of data
,2015-11-20T12:10:48.578Z SendDataTCPServer.js: TCP/IP server has received 8304460 bytes of data
,2015-11-20T12:10:48.586Z SendDataTCPServer.js: TCP/IP server has received 8435532 bytes of data
,2015-11-20T12:10:48.590Z SendDataTCPServer.js: TCP/IP server has received 8566604 bytes of data
,2015-11-20T12:10:48.594Z SendDataTCPServer.js: TCP/IP server has received 8697676 bytes of data
,2015-11-20T12:10:48.599Z SendDataTCPServer.js: TCP/IP server has received 8828748 bytes of data
,2015-11-20T12:10:48.605Z SendDataTCPServer.js: TCP/IP server has received 8959820 bytes of data
,2015-11-20T12:10:48.614Z SendDataTCPServer.js: TCP/IP server has received 9090892 bytes of data
,2015-11-20T12:10:48.620Z SendDataTCPServer.js: TCP/IP server has received 9221964 bytes of data
,2015-11-20T12:10:48.623Z SendDataTCPServer.js: TCP/IP server has received 9353036 bytes of data
,2015-11-20T12:10:48.626Z SendDataTCPServer.js: TCP/IP server has received 9484108 bytes of data
,2015-11-20T12:10:48.629Z SendDataTCPServer.js: TCP/IP server has received 9615180 bytes of data
,2015-11-20T12:10:48.632Z SendDataTCPServer.js: TCP/IP server has received 9746252 bytes of data
,2015-11-20T12:10:48.636Z SendDataTCPServer.js: TCP/IP server has received 9877324 bytes of data
,2015-11-20T12:10:48.640Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20T12:10:48.645Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:48.645Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:10:48.645Z SendDataConnector.js: got all data for this round
,2015-11-20T12:10:48.646Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:10:48.646Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:10:48.647 ThaliTest[1010:776807] jxcore: disconnect
,2015-11-20 13:10:48.648 ThaliTest[1010:776807] client session: disconnectFromPeer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:10:48.648 ThaliTest[1010:776807] client session: disconnect
,2015-11-20 13:10:48.649 ThaliTest[1010:776807] client session: stateChange:2->0 Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:10:48.652 ThaliTest[1010:776807] jxcore: disconnect: success
,2015-11-20T12:10:48.655Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2043.OU3s0w==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:10:48.659Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:10:48.660Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:10:48.675Z SendDataConnector.js: CLIENT is closed
,2015-11-20 13:10:48.710 ThaliTest[1010:777676] server session: not connected Apple-Iphone6-1_PT2043
,2015-11-20 13:10:49.303 ThaliTest[1010:776684] multipeer session: reset timer
2015-11-20 13:10:49.304 ThaliTest[1010:776684] multipeer session: stop timer
2015-11-20 13:10:49.305 ThaliTest[1010:776684] multipeer session: start timer: 0x18655aa0
2015-11-,20 13:10:49.305 ThaliTest[1010:776684] server session: connect
2015-11-20 13:10:49.306 ThaliTest[1010:776684] server session: stateChange:0->1 Apple-IpadAir2-1_PT7072
,2015-11-20 13:10:49.313 ThaliTest[1010:776684] server: accepting invitation Apple-IpadAir2-1_PT7072
,2015-11-20 13:10:49.672 ThaliTest[1010:776807] jxcore: disconnect
2015-11-20 13:10:49.673 ThaliTest[1010:776807] jxcore: disconnect: fail
2015-11-20T12:10:49.674Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7072.5zbvNA,==
2015-11-20T12:10:49.674Z SendDataConnector.js: Connect (retry count 0) to peer Apple-IpadAir2-1_PT7072.5zbvNA== with availability status: true
,2015-11-20T12:10:49.675Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:10:49.675Z SendDataConnector.js: do connect now
,2015-11-20 13:10:49.676 ThaliTest[1010:776807] jxcore: connect Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:10:49.677 ThaliTest[1010:776807] client session: connect
,2015-11-20 13:10:49.678 ThaliTest[1010:776807] client session: stateChange:0->1 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:10:54.898 ThaliTest[1010:776684] client: lost peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:10:54.898 ThaliTest[1010:776684] client session: onPeerLost: Apple-Iphone6-1_PT2043.OU3s0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:10:58.092 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:10:58.409 ThaliTest[1010:777750] server session: not connected Apple-Iphone5-1_PT2716
,2015-11-20 13:10:58.645 ThaliTest[1010:777688] server session: connected
2015-11-20 13:10:58.646 ThaliTest[1010:777688] server session: stateChange:1->2 Apple-IpadAir2-1_PT7072
,2015-11-20 13:10:58.677 ThaliTest[1010:776684] server relay: connected (to port: 55847)
,2015-11-20T12:10:58.690Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:10:59.634 ThaliTest[1010:777689] client session: connected
2015-11-20 13:10:59.635 ThaliTest[1010:777689] client session: stateChange:1->2 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:10:59.650 ThaliTest[1010:777750] client session: fireConnectCallback: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:10:59.650 ThaliTest[1010:777750] jxcore: connect: success
,2015-11-20T12:10:59.651Z SendDataConnector.js: CLIENT connected to 55857, error: null
,2015-11-20T12:10:59.654Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:10:59.658 ThaliTest[1010:776684] client: relay established
2015-11-20 13:10:59.659 ThaliTest[1010:776684] client: new accepted socket: 0x14685af0
,2015-11-20T12:10:59.670Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:11:04.334Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,2015-11-20T12:11:04.521Z SendDataTCPServer.js: TCP/IP server has received 131072 bytes of data
,2015-11-20T12:11:04.524Z SendDataTCPServer.js: TCP/IP server has received 251850 bytes of data
,2015-11-20T12:11:04.552Z SendDataTCPServer.js: TCP/IP server has received 266186 bytes of data
,2015-11-20T12:11:04.895Z SendDataTCPServer.js: TCP/IP server has received 274378 bytes of data
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,Turning Wifi off
,Warning: iOS does not support ToggleWiFi
,We could not turn wifi off! - Warning: iOS does not support ToggleWiFi
,Turning Wifi back on
,Warning: iOS does not support ToggleWiFi
We could turn wifi back on! - Warning: iOS does not support ToggleWiFi
toggleWiFi finished
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20T12:11:14.340Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:11:14.340Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:11:14.342Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:11:14.342Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T12:11:14.346Z SendDataConnector.js: CLIENT is closed
,2015-11-20T12:11:15.351Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:15.351Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:16.364 ThaliTest[1010:776807] jxcore: disconnect
2015-11-20 13:11:16.364 ThaliTest[1010:776807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:11:16.365 ThaliTest[1010:776807] client session: disconnec,t
2015-11-20 13:11:16.366 ThaliTest[1010:776807] client session: stateChange:2->0 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:19.219 ThaliTest[1010:777749] server session: not connected Apple-IpadAir2-1_PT7072
,2015-11-20 13:11:19.600 ThaliTest[1010:776684] multipeer session: restart
2015-11-20 13:11:19.604 ThaliTest[1010:776807] jxcore: disconnect: success
2015-11-20T12:11:19.619Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT,7072.5zbvNA==
2015-11-20T12:11:19.620Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT7072.5zbvNA== with availability status: true
2015-11-20T12:11:19.624Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7072,.5zbvNA==
2015-11-20T12:11:19.625Z SendDataConnector.js: do connect now
2015-11-20 13:11:19.627 ThaliTest[1010:776807] jxcore: connect Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:11:19.628 ThaliTest[1010:776807] client session: connect
2015-11-20 13,:11:19.628 ThaliTest[1010:776807] client session: stateChange:0->1 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:19.670 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:11:19.676 ThaliTest[1010:776684] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:11:19.681 ThaliTest[1010:776684] client: ,found peer: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:11:19.701 ThaliTest[1010:776684] multipeer session: reset timer
2015-11-20 13:11:19.702 ThaliTest[1010:776684] multipeer session: stop timer
2015-11-20 13:11:19.702 ThaliTest[1010:776684] multipeer session: start timer: 0x18655aa0
2015-11-,20 13:11:19.702 ThaliTest[1010:776684] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7072)
2015-11-20 13:11:19.703 ThaliTest[1010:776684] server session: disconnect
2015-11-20 13:11:19.703 ThaliTest[1010:776684] server session: stateChange,:2->0 Apple-IpadAir2-1_PT7072
2015-11-20 13:11:19.705 ThaliTest[1010:776684] server session: connect
2015-11-20 13:11:19.706 ThaliTest[1010:776684] server session: stateChange:0->1 Apple-IpadAir2-1_PT7072
,2015-11-20 13:11:19.721 ThaliTest[1010:776684] server: accepting invitation Apple-IpadAir2-1_PT7072
,2015-11-20T12:11:19.741Z SendDataTCPServer.js: TCP/IP server has received 405450 bytes of data
,2015-11-20T12:11:19.751Z SendDataTCPServer.js: TCP/IP server got error : Error: read ECONNRESET
,2015-11-20T12:11:19.751Z SendDataTCPServer.js: TCP/IP server is close
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20 13:11:23.111 ThaliTest[1010:777689] server session: connected
2015-11-20 13:11:23.112 ThaliTest[1010:777689] server session: stateChange:1->2 Apple-IpadAir2-1_PT7072
,2015-11-20 13:11:23.134 ThaliTest[1010:776684] server relay: connected (to port: 55847)
,2015-11-20T12:11:23.141Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:11:23.229 ThaliTest[1010:777749] client session: connected
2015-11-20 13:11:23.229 ThaliTest[1010:777749] client session: stateChange:1->2 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:23.239 ThaliTest[1010:777749] client session: fireConnectCallback: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:11:23.239 ThaliTest[1010:777749] jxcore: connect: success
2015-11-20T12:11:23.240Z SendDataConnector.js: CLIENT connected t,o 55866, error: null
2015-11-20T12:11:23.241Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:11:23.245 ThaliTest[1010:776684] client: relay established
2015-11-20 13:11:23.245 ThaliTest[1010:776684] client: new accepted socket: 0x14685af0
,2015-11-20T12:11:23.257Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:11:23.669 ThaliTest[1010:776684] multipeer session: reset timer
2015-11-20 13:11:23.669 ThaliTest[1010:776684] multipeer session: stop timer
2015-11-20 13:11:23.669 ThaliTest[1010:776684] multipeer session: start timer: 0x18655aa0
2015-11-,20 13:11:23.669 ThaliTest[1010:776684] server: disconnecting to refresh session (Apple-Iphone5-1_PT2716)
2015-11-20 13:11:23.669 ThaliTest[1010:776684] server session: disconnect
2015-11-20 13:11:23.669 ThaliTest[1010:776684] server session: stateChange:1->0 Apple-Iphone5-1_PT2716
,2015-11-20 13:11:23.723 ThaliTest[1010:776684] server session: connect
2015-11-20 13:11:23.724 ThaliTest[1010:776684] server session: stateChange:0->1 Apple-Iphone5-1_PT2716
,2015-11-20 13:11:23.727 ThaliTest[1010:776684] server: accepting invitation Apple-Iphone5-1_PT2716
2015-11-20 13:11:23.727 ThaliTest[1010:776684] multipeer session: reset timer
2015-11-20 13:11:23.727 ThaliTest[1010:776684] multipeer session: stop timer
2015-11-20 13:11:23.728 ThaliTest[1010:776684] multipeer session: start timer: 0x18655aa0
2015-11-20 13:11:23.728 ThaliTest[1010:776684] server: disconnecting to refresh session (Apple-Iphone5-1_PT2716)
2015-11-20 13:11:23.728 ThaliTest[1010:776684] ser,ver session: disconnect
2015-11-20 13:11:23.728 ThaliTest[1010:776684] server session: stateChange:1->0 Apple-Iphone5-1_PT2716
2015-11-20 13:11:23.728 ThaliTest[1010:776684] server session: connect
2015-11-20 13:11:23.729 ThaliTest[1010:776684] server session: stateChange:0->1 Apple-Iphone5-1_PT2716
,2015-11-20 13:11:23.737 ThaliTest[1010:776684] server: accepting invitation Apple-Iphone5-1_PT2716
,2015-11-20 13:11:25.860 ThaliTest[1010:777967] server session: connected
2015-11-20 13:11:25.860 ThaliTest[1010:777967] server session: stateChange:1->2 Apple-Iphone5-1_PT2716
,2015-11-20 13:11:25.870 ThaliTest[1010:776684] server relay: connected (to port: 55847)
,2015-11-20T12:11:28.028Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20T12:11:28.211Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:11:28.212Z SendDataTCPServer.js: TCP/IP server has received 131072 bytes of data
,2015-11-20T12:11:28.214Z SendDataTCPServer.js: TCP/IP server has received 262144 bytes of data
,2015-11-20T12:11:28.216Z SendDataTCPServer.js: TCP/IP server has received 393216 bytes of data
,2015-11-20T12:11:28.218Z SendDataTCPServer.js: TCP/IP server has received 438000 bytes of data
,2015-11-20T12:11:29.001Z SendDataTCPServer.js: TCP/IP server has received 497392 bytes of data
,2015-11-20T12:11:29.020Z SendDataTCPServer.js: TCP/IP server has received 511728 bytes of data
,2015-11-20T12:11:29.668Z SendDataTCPServer.js: TCP/IP server has received 591600 bytes of data
,2015-11-20T12:11:29.673Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:29.674Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-20T12:11:29.689Z SendDataTCPServer.js: TCP/IP server has received 642800 bytes of data
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20T12:11:33.696Z SendDataTCPServer.js: TCP/IP server has received 646896 bytes of data
,2015-11-20T12:11:34.337Z SendDataTCPServer.js: TCP/IP server has received 648944 bytes of data
,2015-11-20 13:11:35.173 ThaliTest[1010:776684] client: lost peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:11:35.174 ThaliTest[1010:776684] client session: onPeerLost: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:11:35.179Z SendDataTCPServer.js: TC,P/IP server has received 650992 bytes of data
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20T12:11:39.676Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:11:39.676Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-20T12:11:39.677Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:11:39.677Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T12:11:39.679Z SendDataConnector.js: CLIENT is closed
,2015-11-20T12:11:39.731Z SendDataTCPServer.js: TCP/IP server has received 653040 bytes of data
,2015-11-20T12:11:40.658Z SendDataTCPServer.js: TCP/IP server has received 655088 bytes of data
,2015-11-20T12:11:40.659Z SendDataTCPServer.js: TCP/IP server has received 2048 bytes of data
,2015-11-20T12:11:40.683Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:40.683Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:41.084Z SendDataTCPServer.js: TCP/IP server has received 657136 bytes of data
,2015-11-20T12:11:41.085Z SendDataTCPServer.js: TCP/IP server has received 4096 bytes of data
,2015-11-20 13:11:41.115 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
2015-11-20 13:11:41.125 ThaliTest[1,010:776684] client: socket closed
2015-11-20 13:11:41.126 ThaliTest[1010:776684] client relay: socket disconnected
2015-11-20 13:11:41.127 ThaliTest[1010:776684] client relay: 0x14685af0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code,=7 "Socket closed by remote peer" UserInfo=0x1854d090 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 13:11:41.128 ThaliTest[1010:776684] client session: socket closed: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:11:41.128 ThaliTest[,1010:776684] client session: onLinkFailure: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:11:41.130 ThaliTest[1010:776684] client session: disconnect
2015-11-20 13:11:41.130 ThaliTest[1010:776684] client session: stateChange:2->0 Apple-IpadAir2-1_PT7072,.5zbvNA==
2015-11-20T12:11:41.132Z SendDataTCPServer.js: TCP/IP server has received 63488 bytes of data
2015-11-20T12:11:41.135Z SendDataTCPServer.js: TCP/IP server has received 716528 bytes of data
,2015-11-20 13:11:41.169 ThaliTest[1010:776684] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:41.184Z SendDataTCPServer.js: TCP/IP server has received 751344 bytes of data
2015-11-20T12:11:41.187Z SendDataTCPServer.js: TCP/IP server has received 112640 bytes of data
,2015-11-20T12:11:41.207Z SendDataTCPServer.js: TCP/IP server has received 851696 bytes of data
,2015-11-20T12:11:41.214Z SendDataTCPServer.js: TCP/IP server has received 243712 bytes of data
,2015-11-20T12:11:41.219Z SendDataTCPServer.js: TCP/IP server has received 352256 bytes of data
,2015-11-20T12:11:41.245Z SendDataTCPServer.js: TCP/IP server has received 896752 bytes of data
,2015-11-20T12:11:41.250Z SendDataTCPServer.js: TCP/IP server has received 483328 bytes of data
,2015-11-20T12:11:41.272Z SendDataTCPServer.js: TCP/IP server has received 614400 bytes of data
,2015-11-20T12:11:41.279Z SendDataTCPServer.js: TCP/IP server has received 745472 bytes of data
,2015-11-20T12:11:41.287Z SendDataTCPServer.js: TCP/IP server has received 807488 bytes of data
,2015-11-20T12:11:41.304Z SendDataTCPServer.js: TCP/IP server has received 1027824 bytes of data
,2015-11-20T12:11:41.306Z SendDataTCPServer.js: TCP/IP server has received 1099504 bytes of data
,2015-11-20T12:11:41.366Z SendDataTCPServer.js: TCP/IP server has received 1230576 bytes of data
,2015-11-20T12:11:41.407Z SendDataTCPServer.js: TCP/IP server has received 1361648 bytes of data
,2015-11-20T12:11:41.435Z SendDataTCPServer.js: TCP/IP server has received 1492720 bytes of data
,2015-11-20T12:11:41.451Z SendDataTCPServer.js: TCP/IP server has received 1623792 bytes of data
,2015-11-20T12:11:41.466Z SendDataTCPServer.js: TCP/IP server has received 1754864 bytes of data
,2015-11-20T12:11:41.471Z SendDataTCPServer.js: TCP/IP server has received 1885936 bytes of data
,2015-11-20T12:11:41.475Z SendDataTCPServer.js: TCP/IP server has received 2017008 bytes of data
,2015-11-20T12:11:41.478Z SendDataTCPServer.js: TCP/IP server has received 2148080 bytes of data
,2015-11-20T12:11:41.482Z SendDataTCPServer.js: TCP/IP server has received 2279152 bytes of data
,2015-11-20T12:11:41.489Z SendDataTCPServer.js: TCP/IP server has received 2410224 bytes of data
,2015-11-20T12:11:41.499Z SendDataTCPServer.js: TCP/IP server has received 2541296 bytes of data
,2015-11-20T12:11:41.502Z SendDataTCPServer.js: TCP/IP server has received 2672368 bytes of data
,2015-11-20T12:11:41.505Z SendDataTCPServer.js: TCP/IP server has received 2803440 bytes of data
,2015-11-20T12:11:41.509Z SendDataTCPServer.js: TCP/IP server has received 2934512 bytes of data
,2015-11-20T12:11:41.513Z SendDataTCPServer.js: TCP/IP server has received 3065584 bytes of data
,2015-11-20T12:11:41.518Z SendDataTCPServer.js: TCP/IP server has received 3196656 bytes of data
,2015-11-20T12:11:41.524Z SendDataTCPServer.js: TCP/IP server has received 3327728 bytes of data
,2015-11-20T12:11:41.531Z SendDataTCPServer.js: TCP/IP server has received 3458800 bytes of data
,2015-11-20T12:11:41.540Z SendDataTCPServer.js: TCP/IP server has received 3589872 bytes of data
,2015-11-20T12:11:41.546Z SendDataTCPServer.js: TCP/IP server has received 3720944 bytes of data
,2015-11-20T12:11:41.558Z SendDataTCPServer.js: TCP/IP server has received 3852016 bytes of data
,2015-11-20T12:11:41.604Z SendDataTCPServer.js: TCP/IP server has received 3983088 bytes of data
,2015-11-20T12:11:41.621Z SendDataTCPServer.js: TCP/IP server has received 4114160 bytes of data
,2015-11-20T12:11:41.649Z SendDataTCPServer.js: TCP/IP server has received 4245232 bytes of data
,2015-11-20T12:11:41.680Z SendDataTCPServer.js: TCP/IP server has received 4376304 bytes of data
,2015-11-20T12:11:41.690Z SendDataTCPServer.js: TCP/IP server has received 4507376 bytes of data
,2015-11-20T12:11:41.703Z SendDataTCPServer.js: TCP/IP server has received 4638448 bytes of data
,2015-11-20T12:11:41.711Z SendDataTCPServer.js: TCP/IP server has received 4769520 bytes of data
,2015-11-20T12:11:41.732Z SendDataTCPServer.js: TCP/IP server has received 4900592 bytes of data
,2015-11-20T12:11:41.740Z SendDataTCPServer.js: TCP/IP server has received 5031664 bytes of data
,2015-11-20T12:11:41.753Z SendDataTCPServer.js: TCP/IP server has received 5162736 bytes of data
,2015-11-20T12:11:41.757Z SendDataTCPServer.js: TCP/IP server has received 5293808 bytes of data
,2015-11-20 13:11:41.773 ThaliTest[1010:776807] jxcore: disconnect
,2015-11-20 13:11:41.774 ThaliTest[1010:776807] jxcore: disconnect: fail
,2015-11-20T12:11:41.778Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:41.778Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT7072.5zbvNA== with availability status: true
,2015-11-20T12:11:41.778Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:41.779Z SendDataConnector.js: do connect now
,2015-11-20 13:11:41.779 ThaliTest[1010:776807] jxcore: connect Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:41.780 ThaliTest[1010:776807] client session: connect
,2015-11-20 13:11:41.781 ThaliTest[1010:776807] client session: stateChange:0->1 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:41.794Z SendDataTCPServer.js: TCP/IP server has received 5424880 bytes of data
,2015-11-20T12:11:41.801Z SendDataTCPServer.js: TCP/IP server has received 5507850 bytes of data
,2015-11-20T12:11:41.805Z SendDataTCPServer.js: TCP/IP server has received 917600 bytes of data
,2015-11-20T12:11:41.823Z SendDataTCPServer.js: TCP/IP server has received 932480 bytes of data
,2015-11-20T12:11:41.836Z SendDataTCPServer.js: TCP/IP server has received 943392 bytes of data
,2015-11-20T12:11:41.852Z SendDataTCPServer.js: TCP/IP server has received 966208 bytes of data
,2015-11-20T12:11:41.978Z SendDataTCPServer.js: TCP/IP server has received 5529750 bytes of data
,2015-11-20T12:11:41.991Z SendDataTCPServer.js: TCP/IP server has received 5591070 bytes of data
,2015-11-20T12:11:42.004Z SendDataTCPServer.js: TCP/IP server has received 5608590 bytes of data
,2015-11-20T12:11:42.067Z SendDataTCPServer.js: TCP/IP server has received 5610780 bytes of data
,2015-11-20T12:11:42.080Z SendDataTCPServer.js: TCP/IP server has received 5650200 bytes of data
,2015-11-20T12:11:42.107Z SendDataTCPServer.js: TCP/IP server has received 5674290 bytes of data
,2015-11-20T12:11:42.120Z SendDataTCPServer.js: TCP/IP server has received 972160 bytes of data
,2015-11-20T12:11:42.156Z SendDataTCPServer.js: TCP/IP server has received 5680860 bytes of data
,2015-11-20T12:11:42.170Z SendDataTCPServer.js: TCP/IP server has received 5715900 bytes of data
,2015-11-20T12:11:42.185Z SendDataTCPServer.js: TCP/IP server has received 5746560 bytes of data
,2015-11-20T12:11:42.198Z SendDataTCPServer.js: TCP/IP server has received 5783790 bytes of data
,2015-11-20T12:11:42.210Z SendDataTCPServer.js: TCP/IP server has received 5805690 bytes of data
,2015-11-20T12:11:42.212Z SendDataTCPServer.js: TCP/IP server has received 981088 bytes of data
,2015-11-20T12:11:42.224Z SendDataTCPServer.js: TCP/IP server has received 5853870 bytes of data
,2015-11-20T12:11:42.225Z SendDataTCPServer.js: TCP/IP server has received 990016 bytes of data
,2015-11-20T12:11:42.236Z SendDataTCPServer.js: TCP/IP server has received 5917380 bytes of data
,2015-11-20T12:11:42.250Z SendDataTCPServer.js: TCP/IP server has received 5950230 bytes of data
,2015-11-20T12:11:42.252Z SendDataTCPServer.js: TCP/IP server has received 996960 bytes of data
,2015-11-20T12:11:42.264Z SendDataTCPServer.js: TCP/IP server has received 5991840 bytes of data
,2015-11-20T12:11:42.265Z SendDataTCPServer.js: TCP/IP server has received 1000928 bytes of data
,2015-11-20T12:11:42.278Z SendDataTCPServer.js: TCP/IP server has received 6011550 bytes of data
,2015-11-20T12:11:42.279Z SendDataTCPServer.js: TCP/IP server has received 1026720 bytes of data
,2015-11-20T12:11:42.292Z SendDataTCPServer.js: TCP/IP server has received 6033450 bytes of data
,2015-11-20T12:11:42.294Z SendDataTCPServer.js: TCP/IP server has received 1044576 bytes of data
,2015-11-20T12:11:42.306Z SendDataTCPServer.js: TCP/IP server has received 6059730 bytes of data
,2015-11-20T12:11:42.307Z SendDataTCPServer.js: TCP/IP server has received 1052512 bytes of data
,2015-11-20T12:11:42.321Z SendDataTCPServer.js: TCP/IP server has received 6079440 bytes of data
,2015-11-20T12:11:42.323Z SendDataTCPServer.js: TCP/IP server has received 1087232 bytes of data
,2015-11-20T12:11:42.338Z SendDataTCPServer.js: TCP/IP server has received 6105578 bytes of data
,2015-11-20T12:11:42.339Z SendDataTCPServer.js: TCP/IP server has received 1105088 bytes of data
,2015-11-20T12:11:42.353Z SendDataTCPServer.js: TCP/IP server has received 6125430 bytes of data
,2015-11-20T12:11:42.355Z SendDataTCPServer.js: TCP/IP server has received 1127904 bytes of data
,2015-11-20T12:11:42.369Z SendDataTCPServer.js: TCP/IP server has received 6136380 bytes of data
,2015-11-20T12:11:42.369Z SendDataTCPServer.js: TCP/IP server has received 1150720 bytes of data
,2015-11-20T12:11:42.504Z SendDataTCPServer.js: TCP/IP server has received 6175800 bytes of data
,2015-11-20T12:11:42.518Z SendDataTCPServer.js: TCP/IP server has received 6221790 bytes of data
,2015-11-20T12:11:42.533Z SendDataTCPServer.js: TCP/IP server has received 6265590 bytes of data
,2015-11-20T12:11:42.632Z SendDataTCPServer.js: TCP/IP server has received 1154688 bytes of data
,2015-11-20T12:11:42.646Z SendDataTCPServer.js: TCP/IP server has received 1175520 bytes of data
,2015-11-20T12:11:42.663Z SendDataTCPServer.js: TCP/IP server has received 1189408 bytes of data
,2015-11-20T12:11:42.734Z SendDataTCPServer.js: TCP/IP server has received 6276540 bytes of data
,2015-11-20T12:11:42.746Z SendDataTCPServer.js: TCP/IP server has received 6294060 bytes of data
,2015-11-20T12:11:42.750Z SendDataTCPServer.js: TCP/IP server has received 1192384 bytes of data
,2015-11-20T12:11:42.767Z SendDataTCPServer.js: TCP/IP server has received 6309390 bytes of data
2015-11-20T12:11:42.769Z SendDataTCPServer.js: TCP/IP server has received 1198336 bytes of data
,2015-11-20T12:11:42.784Z SendDataTCPServer.js: TCP/IP server has received 6331290 bytes of data
,2015-11-20T12:11:42.786Z SendDataTCPServer.js: TCP/IP server has received 1204288 bytes of data
,2015-11-20T12:11:42.801Z SendDataTCPServer.js: TCP/IP server has received 6351000 bytes of data
,2015-11-20T12:11:42.805Z SendDataTCPServer.js: TCP/IP server has received 1226112 bytes of data
,2015-11-20T12:11:42.821Z SendDataTCPServer.js: TCP/IP server has received 6381660 bytes of data
,2015-11-20T12:11:42.824Z SendDataTCPServer.js: TCP/IP server has received 1237024 bytes of data
,2015-11-20T12:11:42.838Z SendDataTCPServer.js: TCP/IP server has received 1260832 bytes of data
,2015-11-20T12:11:42.852Z SendDataTCPServer.js: TCP/IP server has received 1282656 bytes of data
,2015-11-20T12:11:42.854Z SendDataTCPServer.js: TCP/IP server has received 6388230 bytes of data
,2015-11-20T12:11:42.867Z SendDataTCPServer.js: TCP/IP server has received 1290592 bytes of data
,2015-11-20T12:11:42.869Z SendDataTCPServer.js: TCP/IP server has received 6405750 bytes of data
,2015-11-20T12:11:42.884Z SendDataTCPServer.js: TCP/IP server has received 1306464 bytes of data
,2015-11-20T12:11:42.885Z SendDataTCPServer.js: TCP/IP server has received 6425460 bytes of data
,2015-11-20T12:11:42.899Z SendDataTCPServer.js: TCP/IP server has received 1337216 bytes of data
,2015-11-20T12:11:42.901Z SendDataTCPServer.js: TCP/IP server has received 6432030 bytes of data
,2015-11-20T12:11:42.914Z SendDataTCPServer.js: TCP/IP server has received 1342176 bytes of data
,2015-11-20T12:11:42.915Z SendDataTCPServer.js: TCP/IP server has received 6484590 bytes of data
,2015-11-20T12:11:43.027Z SendDataTCPServer.js: TCP/IP server has received 6493350 bytes of data
,2015-11-20T12:11:43.042Z SendDataTCPServer.js: TCP/IP server has received 6530580 bytes of data
,2015-11-20T12:11:43.059Z SendDataTCPServer.js: TCP/IP server has received 6548100 bytes of data
,2015-11-20T12:11:43.174Z SendDataTCPServer.js: TCP/IP server has received 1350112 bytes of data
,2015-11-20T12:11:43.195Z SendDataTCPServer.js: TCP/IP server has received 1355072 bytes of data
,2015-11-20T12:11:43.210Z SendDataTCPServer.js: TCP/IP server has received 1356064 bytes of data
,2015-11-20T12:11:43.226Z SendDataTCPServer.js: TCP/IP server has received 6550290 bytes of data
,2015-11-20T12:11:43.243Z SendDataTCPServer.js: TCP/IP server has received 6559050 bytes of data
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20T12:11:43.270Z SendDataTCPServer.js: TCP/IP server has received 6580950 bytes of data
2015-11-20T12:11:43.274Z SendDataTCPServer.js: TCP/IP server has received 1357056 bytes of data
,2015-11-20T12:11:43.286Z SendDataTCPServer.js: TCP/IP server has received 6596280 bytes of data
,2015-11-20T12:11:43.287Z SendDataTCPServer.js: TCP/IP server has received 1359040 bytes of data
,2015-11-20T12:11:43.300Z SendDataTCPServer.js: TCP/IP server has received 6613800 bytes of data
,2015-11-20T12:11:43.314Z SendDataTCPServer.js: TCP/IP server has received 6635700 bytes of data
,2015-11-20T12:11:43.354Z SendDataTCPServer.js: TCP/IP server has received 6677310 bytes of data
,2015-11-20T12:11:43.361Z SendDataTCPServer.js: TCP/IP server has received 1360032 bytes of data
,2015-11-20T12:11:43.387Z SendDataTCPServer.js: TCP/IP server has received 6756150 bytes of data
,2015-11-20T12:11:43.397Z SendDataTCPServer.js: TCP/IP server has received 1365984 bytes of data
,2015-11-20T12:11:43.412Z SendDataTCPServer.js: TCP/IP server has received 6789000 bytes of data
,2015-11-20T12:11:43.419Z SendDataTCPServer.js: TCP/IP server has received 1413600 bytes of data
,2015-11-20T12:11:43.434Z SendDataTCPServer.js: TCP/IP server has received 1420544 bytes of data
,2015-11-20T12:11:43.543Z SendDataTCPServer.js: TCP/IP server has received 6797760 bytes of data
,2015-11-20T12:11:43.561Z SendDataTCPServer.js: TCP/IP server has received 6850320 bytes of data
,2015-11-20T12:11:43.580Z SendDataTCPServer.js: TCP/IP server has received 6929160 bytes of data
,2015-11-20T12:11:43.632Z SendDataTCPServer.js: TCP/IP server has received 6975150 bytes of data
,2015-11-20T12:11:43.651Z SendDataTCPServer.js: TCP/IP server has received 7027710 bytes of data
,2015-11-20T12:11:43.667Z SendDataTCPServer.js: TCP/IP server has received 7075890 bytes of data
,2015-11-20T12:11:43.686Z SendDataTCPServer.js: TCP/IP server has received 7117500 bytes of data
,2015-11-20T12:11:43.701Z SendDataTCPServer.js: TCP/IP server has received 7165680 bytes of data
,2015-11-20T12:11:43.708Z SendDataTCPServer.js: TCP/IP server has received 1421536 bytes of data
,2015-11-20T12:11:43.720Z SendDataTCPServer.js: TCP/IP server has received 7209480 bytes of data
,2015-11-20T12:11:43.734Z SendDataTCPServer.js: TCP/IP server has received 7244520 bytes of data
,2015-11-20T12:11:43.749Z SendDataTCPServer.js: TCP/IP server has received 7288320 bytes of data
,2015-11-20T12:11:43.765Z SendDataTCPServer.js: TCP/IP server has received 7340596 bytes of data
,2015-11-20T12:11:43.782Z SendDataTCPServer.js: TCP/IP server has received 7386870 bytes of data
,2015-11-20T12:11:43.797Z SendDataTCPServer.js: TCP/IP server has received 7428480 bytes of data
,2015-11-20T12:11:43.814Z SendDataTCPServer.js: TCP/IP server has received 7470090 bytes of data
,2015-11-20T12:11:43.829Z SendDataTCPServer.js: TCP/IP server has received 7520460 bytes of data
,2015-11-20T12:11:43.843Z SendDataTCPServer.js: TCP/IP server has received 7557690 bytes of data
,2015-11-20T12:11:43.858Z SendDataTCPServer.js: TCP/IP server has received 7597110 bytes of data
,2015-11-20T12:11:43.871Z SendDataTCPServer.js: TCP/IP server has received 7632150 bytes of data
,2015-11-20T12:11:43.873Z SendDataTCPServer.js: TCP/IP server has received 1426496 bytes of data
,2015-11-20T12:11:43.884Z SendDataTCPServer.js: TCP/IP server has received 7689090 bytes of data
,2015-11-20T12:11:43.898Z SendDataTCPServer.js: TCP/IP server has received 7697850 bytes of data
,2015-11-20T12:11:44.082Z SendDataTCPServer.js: TCP/IP server has received 7719750 bytes of data
,2015-11-20T12:11:44.098Z SendDataTCPServer.js: TCP/IP server has received 7763550 bytes of data
,2015-11-20T12:11:44.113Z SendDataTCPServer.js: TCP/IP server has received 7772310 bytes of data
,2015-11-20T12:11:44.175Z SendDataTCPServer.js: TCP/IP server has received 7778738 bytes of data
,2015-11-20T12:11:44.189Z SendDataTCPServer.js: TCP/IP server has received 7802970 bytes of data
,2015-11-20T12:11:44.204Z SendDataTCPServer.js: TCP/IP server has received 7822538 bytes of data
,2015-11-20T12:11:44.220Z SendDataTCPServer.js: TCP/IP server has received 7844580 bytes of data
,2015-11-20T12:11:44.222Z SendDataTCPServer.js: TCP/IP server has received 1431456 bytes of data
,2015-11-20T12:11:44.237Z SendDataTCPServer.js: TCP/IP server has received 7853340 bytes of data
,2015-11-20T12:11:44.238Z SendDataTCPServer.js: TCP/IP server has received 1445344 bytes of data
,2015-11-20T12:11:44.252Z SendDataTCPServer.js: TCP/IP server has received 7877288 bytes of data
,2015-11-20T12:11:44.254Z SendDataTCPServer.js: TCP/IP server has received 1450304 bytes of data
,2015-11-20T12:11:44.268Z SendDataTCPServer.js: TCP/IP server has received 7908090 bytes of data
,2015-11-20T12:11:44.282Z SendDataTCPServer.js: TCP/IP server has received 7943130 bytes of data
,2015-11-20T12:11:44.297Z SendDataTCPServer.js: TCP/IP server has received 7967220 bytes of data
,2015-11-20T12:11:44.300Z SendDataTCPServer.js: TCP/IP server has received 1451296 bytes of data
,2015-11-20T12:11:44.314Z SendDataTCPServer.js: TCP/IP server has received 7982550 bytes of data
,2015-11-20T12:11:44.315Z SendDataTCPServer.js: TCP/IP server has received 1464192 bytes of data
,2015-11-20T12:11:44.327Z SendDataTCPServer.js: TCP/IP server has received 8021970 bytes of data
,2015-11-20T12:11:44.342Z SendDataTCPServer.js: TCP/IP server has received 8063580 bytes of data
,2015-11-20T12:11:44.344Z SendDataTCPServer.js: TCP/IP server has received 1467168 bytes of data
,2015-11-20T12:11:44.358Z SendDataTCPServer.js: TCP/IP server has received 8113950 bytes of data
,2015-11-20T12:11:44.360Z SendDataTCPServer.js: TCP/IP server has received 1474112 bytes of data
,2015-11-20T12:11:44.374Z SendDataTCPServer.js: TCP/IP server has received 8153370 bytes of data
,2015-11-20T12:11:44.376Z SendDataTCPServer.js: TCP/IP server has received 1484032 bytes of data
,2015-11-20T12:11:44.598Z SendDataTCPServer.js: TCP/IP server has received 8157750 bytes of data
2015-11-20T12:11:44.615Z SendDataTCPServer.js: TCP/IP server has received 8186220 bytes of data
2015-11-20T12:11:44.635Z SendDataTCPServer.js: TCP/IP server has received 8223450 bytes of data
,2015-11-20T12:11:44.653Z SendDataTCPServer.js: TCP/IP server has received 8262870 bytes of data
,2015-11-20T12:11:44.667Z SendDataTCPServer.js: TCP/IP server has received 8293530 bytes of data
,2015-11-20T12:11:44.695Z SendDataTCPServer.js: TCP/IP server has received 8302290 bytes of data
,2015-11-20T12:11:44.712Z SendDataTCPServer.js: TCP/IP server has received 8339520 bytes of data
,2015-11-20T12:11:44.731Z SendDataTCPServer.js: TCP/IP server has received 8365800 bytes of data
,2015-11-20T12:11:44.749Z SendDataTCPServer.js: TCP/IP server has received 8387700 bytes of data
,2015-11-20T12:11:44.765Z SendDataTCPServer.js: TCP/IP server has received 8409600 bytes of data
,2015-11-20T12:11:44.782Z SendDataTCPServer.js: TCP/IP server has received 8431358 bytes of data
,2015-11-20T12:11:44.800Z SendDataTCPServer.js: TCP/IP server has received 8462160 bytes of data
,2015-11-20T12:11:44.816Z SendDataTCPServer.js: TCP/IP server has received 8505960 bytes of data
,2015-11-20T12:11:44.832Z SendDataTCPServer.js: TCP/IP server has received 8536620 bytes of data
,2015-11-20T12:11:44.846Z SendDataTCPServer.js: TCP/IP server has received 8569470 bytes of data
,2015-11-20T12:11:44.861Z SendDataTCPServer.js: TCP/IP server has received 8595750 bytes of data
,2015-11-20T12:11:44.878Z SendDataTCPServer.js: TCP/IP server has received 8624220 bytes of data
,2015-11-20T12:11:44.893Z SendDataTCPServer.js: TCP/IP server has received 8652690 bytes of data
,2015-11-20T12:11:44.906Z SendDataTCPServer.js: TCP/IP server has received 8694300 bytes of data
,2015-11-20T12:11:44.921Z SendDataTCPServer.js: TCP/IP server has received 8733720 bytes of data
,2015-11-20T12:11:44.934Z SendDataTCPServer.js: TCP/IP server has received 8788470 bytes of data
,2015-11-20T12:11:44.949Z SendDataTCPServer.js: TCP/IP server has received 8805990 bytes of data
,2015-11-20T12:11:45.130Z SendDataTCPServer.js: TCP/IP server has received 8814750 bytes of data
,2015-11-20T12:11:45.146Z SendDataTCPServer.js: TCP/IP server has received 8834460 bytes of data
,2015-11-20T12:11:45.163Z SendDataTCPServer.js: TCP/IP server has received 8851980 bytes of data
,2015-11-20T12:11:45.185Z SendDataTCPServer.js: TCP/IP server has received 8871690 bytes of data
,2015-11-20T12:11:45.203Z SendDataTCPServer.js: TCP/IP server has received 8889210 bytes of data
,2015-11-20T12:11:45.217Z SendDataTCPServer.js: TCP/IP server has received 8906730 bytes of data
,2015-11-20T12:11:45.231Z SendDataTCPServer.js: TCP/IP server has received 8922060 bytes of data
,2015-11-20T12:11:45.244Z SendDataTCPServer.js: TCP/IP server has received 8937390 bytes of data
,2015-11-20T12:11:45.259Z SendDataTCPServer.js: TCP/IP server has received 8946150 bytes of data
,2015-11-20T12:11:45.272Z SendDataTCPServer.js: TCP/IP server has received 8959290 bytes of data
,2015-11-20T12:11:45.291Z SendDataTCPServer.js: TCP/IP server has received 8972430 bytes of data
,2015-11-20T12:11:45.305Z SendDataTCPServer.js: TCP/IP server has received 8989950 bytes of data
,2015-11-20T12:11:45.322Z SendDataTCPServer.js: TCP/IP server has received 9022800 bytes of data
,2015-11-20T12:11:45.338Z SendDataTCPServer.js: TCP/IP server has received 9044700 bytes of data
,2015-11-20T12:11:45.351Z SendDataTCPServer.js: TCP/IP server has received 9049080 bytes of data
,2015-11-20T12:11:45.352Z SendDataTCPServer.js: TCP/IP server has received 1493952 bytes of data
,2015-11-20T12:11:45.366Z SendDataTCPServer.js: TCP/IP server has received 1512800 bytes of data
,2015-11-20T12:11:45.379Z SendDataTCPServer.js: TCP/IP server has received 1524704 bytes of data
,2015-11-20T12:11:45.381Z SendDataTCPServer.js: TCP/IP server has received 9068790 bytes of data
,2015-11-20T12:11:45.394Z SendDataTCPServer.js: TCP/IP server has received 9081930 bytes of data
,2015-11-20T12:11:45.406Z SendDataTCPServer.js: TCP/IP server has received 9099450 bytes of data
,2015-11-20T12:11:45.419Z SendDataTCPServer.js: TCP/IP server has received 9127920 bytes of data
,2015-11-20T12:11:45.432Z SendDataTCPServer.js: TCP/IP server has received 9156390 bytes of data
,2015-11-20T12:11:45.444Z SendDataTCPServer.js: TCP/IP server has received 9180480 bytes of data
,2015-11-20T12:11:45.457Z SendDataTCPServer.js: TCP/IP server has received 9230850 bytes of data
,2015-11-20T12:11:45.471Z SendDataTCPServer.js: TCP/IP server has received 9279030 bytes of data
,2015-11-20T12:11:45.646Z SendDataTCPServer.js: TCP/IP server has received 9285600 bytes of data
,2015-11-20T12:11:45.662Z SendDataTCPServer.js: TCP/IP server has received 9309690 bytes of data
,2015-11-20T12:11:45.678Z SendDataTCPServer.js: TCP/IP server has received 9360060 bytes of data
,2015-11-20T12:11:45.695Z SendDataTCPServer.js: TCP/IP server has received 9399054 bytes of data
,2015-11-20T12:11:45.708Z SendDataTCPServer.js: TCP/IP server has received 9419190 bytes of data
,2015-11-20T12:11:45.725Z SendDataTCPServer.js: TCP/IP server has received 9434378 bytes of data
,2015-11-20T12:11:45.740Z SendDataTCPServer.js: TCP/IP server has received 9452040 bytes of data
,2015-11-20T12:11:45.755Z SendDataTCPServer.js: TCP/IP server has received 9462990 bytes of data
,2015-11-20T12:11:45.768Z SendDataTCPServer.js: TCP/IP server has received 9482700 bytes of data
,2015-11-20T12:11:45.781Z SendDataTCPServer.js: TCP/IP server has received 9487080 bytes of data
,2015-11-20T12:11:45.794Z SendDataTCPServer.js: TCP/IP server has received 1559424 bytes of data
,2015-11-20T12:11:45.811Z SendDataTCPServer.js: TCP/IP server has received 1582240 bytes of data
,2015-11-20T12:11:45.824Z SendDataTCPServer.js: TCP/IP server has received 1587200 bytes of data
,2015-11-20T12:11:45.826Z SendDataTCPServer.js: TCP/IP server has received 9500220 bytes of data
,2015-11-20T12:11:45.840Z SendDataTCPServer.js: TCP/IP server has received 1588192 bytes of data
,2015-11-20T12:11:45.841Z SendDataTCPServer.js: TCP/IP server has received 9511170 bytes of data
,2015-11-20T12:11:45.853Z SendDataTCPServer.js: TCP/IP server has received 1599104 bytes of data
,2015-11-20T12:11:45.856Z SendDataTCPServer.js: TCP/IP server has received 9526500 bytes of data
,2015-11-20T12:11:45.868Z SendDataTCPServer.js: TCP/IP server has received 1612000 bytes of data
,2015-11-20T12:11:45.870Z SendDataTCPServer.js: TCP/IP server has received 9539640 bytes of data
,2015-11-20T12:11:45.882Z SendDataTCPServer.js: TCP/IP server has received 1617952 bytes of data
,2015-11-20T12:11:45.883Z SendDataTCPServer.js: TCP/IP server has received 9568110 bytes of data
,2015-11-20T12:11:45.898Z SendDataTCPServer.js: TCP/IP server has received 1636800 bytes of data
,2015-11-20T12:11:45.899Z SendDataTCPServer.js: TCP/IP server has received 9583440 bytes of data
,2015-11-20T12:11:45.915Z SendDataTCPServer.js: TCP/IP server has received 1651680 bytes of data
,2015-11-20T12:11:45.916Z SendDataTCPServer.js: TCP/IP server has received 9609720 bytes of data
,2015-11-20T12:11:45.929Z SendDataTCPServer.js: TCP/IP server has received 1669536 bytes of data
,2015-11-20T12:11:45.931Z SendDataTCPServer.js: TCP/IP server has received 9629430 bytes of data
,2015-11-20T12:11:45.947Z SendDataTCPServer.js: TCP/IP server has received 1685408 bytes of data
,2015-11-20T12:11:45.950Z SendDataTCPServer.js: TCP/IP server has received 9653520 bytes of data
,2015-11-20T12:11:45.964Z SendDataTCPServer.js: TCP/IP server has received 1711200 bytes of data
,2015-11-20T12:11:45.969Z SendDataTCPServer.js: TCP/IP server has received 9662280 bytes of data
,2015-11-20T12:11:45.984Z SendDataTCPServer.js: TCP/IP server has received 1713184 bytes of data
,2015-11-20T12:11:45.986Z SendDataTCPServer.js: TCP/IP server has received 9738930 bytes of data
,2015-11-20T12:11:46.006Z SendDataTCPServer.js: TCP/IP server has received 1735008 bytes of data
,2015-11-20T12:11:46.008Z SendDataTCPServer.js: TCP/IP server has received 9791490 bytes of data
,2015-11-20T12:11:46.175Z SendDataTCPServer.js: TCP/IP server has received 9802440 bytes of data
,2015-11-20T12:11:46.190Z SendDataTCPServer.js: TCP/IP server has received 9844050 bytes of data
,2015-11-20T12:11:46.203Z SendDataTCPServer.js: TCP/IP server has received 9931650 bytes of data
,2015-11-20T12:11:46.258Z SendDataTCPServer.js: TCP/IP server has received 9940410 bytes of data
,2015-11-20T12:11:46.271Z SendDataTCPServer.js: TCP/IP server has received 9971070 bytes of data
,2015-11-20T12:11:46.285Z SendDataTCPServer.js: TCP/IP server has received 9990002 bytes of data
,2015-11-20T12:11:46.302Z SendDataTCPServer.js: TCP/IP server has received 1736000 bytes of data
,2015-11-20T12:11:46.314Z SendDataTCPServer.js: TCP/IP server has received 1740960 bytes of data
,2015-11-20T12:11:46.329Z SendDataTCPServer.js: TCP/IP server has received 1762784 bytes of data
,2015-11-20T12:11:46.342Z SendDataTCPServer.js: TCP/IP server has received 1775680 bytes of data
,2015-11-20 13:11:46.354 ThaliTest[1010:778011] server session: not connected Apple-IpadAir2-1_PT7072
2015-11-20T12:11:46.356Z SendDataTCPServer.js: TCP/IP server has received 1785600 bytes of data
,2015-11-20T12:11:46.368Z SendDataTCPServer.js: TCP/IP server has received 1802464 bytes of data
,2015-11-20T12:11:46.382Z SendDataTCPServer.js: TCP/IP server has received 1822304 bytes of data
,2015-11-20T12:11:46.397Z SendDataTCPServer.js: TCP/IP server has received 1846112 bytes of data
,2015-11-20T12:11:46.413Z SendDataTCPServer.js: TCP/IP server has received 1871904 bytes of data
,2015-11-20T12:11:46.429Z SendDataTCPServer.js: TCP/IP server has received 1900672 bytes of data
,2015-11-20T12:11:46.441Z SendDataTCPServer.js: TCP/IP server has received 1923488 bytes of data
,2015-11-20T12:11:46.454Z SendDataTCPServer.js: TCP/IP server has received 1936384 bytes of data
,2015-11-20T12:11:46.467Z SendDataTCPServer.js: TCP/IP server has received 1958208 bytes of data
,2015-11-20T12:11:46.480Z SendDataTCPServer.js: TCP/IP server has received 1976064 bytes of data
,2015-11-20T12:11:46.494Z SendDataTCPServer.js: TCP/IP server has received 1995904 bytes of data
,2015-11-20T12:11:46.846Z SendDataTCPServer.js: TCP/IP server has received 1997888 bytes of data
,2015-11-20T12:11:46.862Z SendDataTCPServer.js: TCP/IP server has received 2007808 bytes of data
,2015-11-20T12:11:46.874Z SendDataTCPServer.js: TCP/IP server has received 2016736 bytes of data
,2015-11-20T12:11:46.890Z SendDataTCPServer.js: TCP/IP server has received 2024672 bytes of data
,2015-11-20T12:11:46.905Z SendDataTCPServer.js: TCP/IP server has received 2032608 bytes of data
,2015-11-20T12:11:46.920Z SendDataTCPServer.js: TCP/IP server has received 2040544 bytes of data
,2015-11-20T12:11:46.934Z SendDataTCPServer.js: TCP/IP server has received 2047488 bytes of data
,2015-11-20T12:11:46.948Z SendDataTCPServer.js: TCP/IP server has received 2053440 bytes of data
,2015-11-20T12:11:46.988Z SendDataTCPServer.js: TCP/IP server has received 2070304 bytes of data
,2015-11-20T12:11:47.002Z SendDataTCPServer.js: TCP/IP server has received 2083200 bytes of data
,2015-11-20T12:11:47.016Z SendDataTCPServer.js: TCP/IP server has received 2101056 bytes of data
,2015-11-20T12:11:47.031Z SendDataTCPServer.js: TCP/IP server has received 2124864 bytes of data
,2015-11-20T12:11:47.045Z SendDataTCPServer.js: TCP/IP server has received 2147680 bytes of data
,2015-11-20T12:11:47.369Z SendDataTCPServer.js: TCP/IP server has received 2157600 bytes of data
,2015-11-20T12:11:47.386Z SendDataTCPServer.js: TCP/IP server has received 2164544 bytes of data
,2015-11-20T12:11:47.404Z SendDataTCPServer.js: TCP/IP server has received 2168512 bytes of data
,2015-11-20T12:11:47.420Z SendDataTCPServer.js: TCP/IP server has received 2178432 bytes of data
,2015-11-20T12:11:47.439Z SendDataTCPServer.js: TCP/IP server has received 2189344 bytes of data
,2015-11-20T12:11:47.454Z SendDataTCPServer.js: TCP/IP server has received 2204224 bytes of data
,2015-11-20T12:11:47.468Z SendDataTCPServer.js: TCP/IP server has received 2220096 bytes of data
,2015-11-20T12:11:47.481Z SendDataTCPServer.js: TCP/IP server has received 2233984 bytes of data
,2015-11-20T12:11:47.497Z SendDataTCPServer.js: TCP/IP server has received 2246880 bytes of data
,2015-11-20T12:11:47.510Z SendDataTCPServer.js: TCP/IP server has received 2256800 bytes of data
,2015-11-20T12:11:47.525Z SendDataTCPServer.js: TCP/IP server has received 2271680 bytes of data
,2015-11-20T12:11:47.539Z SendDataTCPServer.js: TCP/IP server has received 2284576 bytes of data
,2015-11-20T12:11:47.553Z SendDataTCPServer.js: TCP/IP server has received 2303424 bytes of data
,2015-11-20T12:11:47.567Z SendDataTCPServer.js: TCP/IP server has received 2327232 bytes of data
,2015-11-20T12:11:47.581Z SendDataTCPServer.js: TCP/IP server has received 2339136 bytes of data
,2015-11-20T12:11:47.890Z SendDataTCPServer.js: TCP/IP server has received 2346080 bytes of data
,2015-11-20T12:11:47.921Z SendDataTCPServer.js: TCP/IP server has received 2352032 bytes of data
,2015-11-20T12:11:47.938Z SendDataTCPServer.js: TCP/IP server has received 2364928 bytes of data
,2015-11-20T12:11:47.954Z SendDataTCPServer.js: TCP/IP server has received 2370880 bytes of data
,2015-11-20T12:11:47.971Z SendDataTCPServer.js: TCP/IP server has received 2385760 bytes of data
,2015-11-20T12:11:47.987Z SendDataTCPServer.js: TCP/IP server has received 2405600 bytes of data
,2015-11-20T12:11:48.002Z SendDataTCPServer.js: TCP/IP server has received 2422464 bytes of data
,2015-11-20T12:11:48.017Z SendDataTCPServer.js: TCP/IP server has received 2434368 bytes of data
,2015-11-20T12:11:48.032Z SendDataTCPServer.js: TCP/IP server has received 2444288 bytes of data
,2015-11-20T12:11:48.046Z SendDataTCPServer.js: TCP/IP server has received 2455200 bytes of data
,2015-11-20T12:11:48.060Z SendDataTCPServer.js: TCP/IP server has received 2466112 bytes of data
,2015-11-20T12:11:48.073Z SendDataTCPServer.js: TCP/IP server has received 2480992 bytes of data
,2015-11-20T12:11:48.087Z SendDataTCPServer.js: TCP/IP server has received 2506784 bytes of data
,2015-11-20T12:11:48.102Z SendDataTCPServer.js: TCP/IP server has received 2530592 bytes of data
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20T12:11:48.416Z SendDataTCPServer.js: TCP/IP server has received 2531584 bytes of data
,2015-11-20 13:11:48.425 ThaliTest[1010:777960] client session: connected
2015-11-20 13:11:48.426 ThaliTest[1010:777960] client session: stateChange:1->2 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:48.432 ThaliTest[1010:777960] client session: fireConnectCallback: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:11:48.433 ThaliTest[1010:777960] jxcore: connect: success
2015-11-20T12:11:48.433Z SendDataConnector.js: CLIENT connected t,o 55875, error: null
2015-11-20T12:11:48.433Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:11:48.435 ThaliTest[1010:776684] client: relay established
2015-11-20 13:11:48.435 ThaliTest[1010:776684] client: new accepted socket: 0x18597680
,2015-11-20T12:11:48.448Z SendDataTCPServer.js: TCP/IP server has received 2540512 bytes of data
,2015-11-20T12:11:48.448Z SendDataConnector.js: CLIENT now sending 9940000 bytes of data
,2015-11-20 13:11:52.518 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:11:53.632 ThaliTest[1010:776684] client: lost peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:11:53.633 ThaliTest[1010:776684] client session: onPeerLost: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:11:54.419Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:54.543 ThaliTest[1010:776684] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20T12:11:54.570Z SendDataTCPServer.js: TCP/IP server has received 2671584 bytes of data
,2015-11-20T12:11:54.578Z SendDataTCPServer.js: TCP/IP server has received 2802656 bytes of data
,2015-11-20T12:11:54.581Z SendDataTCPServer.js: TCP/IP server has received 2933728 bytes of data
,2015-11-20T12:11:54.583Z SendDataTCPServer.js: TCP/IP server has received 3064800 bytes of data
,2015-11-20T12:11:54.585Z SendDataTCPServer.js: TCP/IP server has received 3195872 bytes of data
,2015-11-20T12:11:54.588Z SendDataTCPServer.js: TCP/IP server has received 3326944 bytes of data
,2015-11-20T12:11:54.597Z SendDataTCPServer.js: TCP/IP server has received 3458016 bytes of data
,2015-11-20T12:11:54.599Z SendDataTCPServer.js: TCP/IP server has received 3589088 bytes of data
,2015-11-20T12:11:54.601Z SendDataTCPServer.js: TCP/IP server has received 3720160 bytes of data
,2015-11-20T12:11:54.603Z SendDataTCPServer.js: TCP/IP server has received 3851232 bytes of data
,2015-11-20T12:11:54.612Z SendDataTCPServer.js: TCP/IP server has received 3982304 bytes of data
,2015-11-20T12:11:54.614Z SendDataTCPServer.js: TCP/IP server has received 4113376 bytes of data
,2015-11-20T12:11:54.616Z SendDataTCPServer.js: TCP/IP server has received 4244448 bytes of data
,2015-11-20T12:11:54.630Z SendDataTCPServer.js: TCP/IP server has received 4375520 bytes of data
,2015-11-20T12:11:54.638Z SendDataTCPServer.js: TCP/IP server has received 4506592 bytes of data
,2015-11-20T12:11:54.641Z SendDataTCPServer.js: TCP/IP server has received 4637664 bytes of data
,2015-11-20T12:11:54.643Z SendDataTCPServer.js: TCP/IP server has received 4768736 bytes of data
,2015-11-20T12:11:54.645Z SendDataTCPServer.js: TCP/IP server has received 4899808 bytes of data
,2015-11-20T12:11:54.647Z SendDataTCPServer.js: TCP/IP server has received 5030880 bytes of data
,2015-11-20T12:11:54.651Z SendDataTCPServer.js: TCP/IP server has received 5140640 bytes of data
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:11:54.752 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:11:54.770 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:11:54.771 ThaliTest[1010:776684] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:11:54.774 ThaliTest[1010:776684] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:11:54.787Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:54.790Z SendDataConnector.js: CLIENT is data received : 290000
,2015-11-20T12:11:54.792Z SendDataTCPServer.js: TCP/IP server has received 5261472 bytes of data
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
,2015-11-20T12:11:54.810Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:54.811Z SendDataConnector.js: CLIENT is data received : 420000
,2015-11-20T12:11:55.292Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:55.295Z SendDataConnector.js: CLIENT is data received : 650000
,2015-11-20T12:11:55.306Z SendDataTCPServer.js: TCP/IP server has received 5392544 bytes of data
,2015-11-20T12:11:55.312Z SendDataTCPServer.js: TCP/IP server has received 5484704 bytes of data
,2015-11-20T12:11:55.808Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:55.809Z SendDataConnector.js: CLIENT is data received : 1680000
,2015-11-20T12:11:55.811Z SendDataTCPServer.js: TCP/IP server has received 5486752 bytes of data
,2015-11-20T12:11:55.950Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:55.950Z SendDataConnector.js: CLIENT is data received : 2300000
2015-11-20T12:11:55.952Z SendDataTCPServer.js: TCP/IP server has received 5605536 bytes of data
,2015-11-20T12:11:55.973Z SendDataTCPServer.js: TCP/IP server has received 5736608 bytes of data
2015-11-20T12:11:55.981Z SendDataTCPServer.js: TCP/IP server has received 5867680 bytes of data
2015-11-20T12:11:55.985Z SendDataTCPServer.js: TCP/IP server has received 5998752 bytes of data
,2015-11-20T12:11:55.991Z SendDataTCPServer.js: TCP/IP server has received 6129824 bytes of data
2015-11-20T12:11:55.997Z SendDataTCPServer.js: TCP/IP server has received 6260896 bytes of data
2015-11-20T12:11:56.001Z SendDataTCPServer.js: TCP/IP server h,as received 6391968 bytes of data
,2015-11-20T12:11:56.003Z SendDataTCPServer.js: TCP/IP server has received 6523040 bytes of data
,2015-11-20T12:11:56.004Z SendDataTCPServer.js: TCP/IP server has received 6654112 bytes of data
,2015-11-20T12:11:56.007Z SendDataTCPServer.js: TCP/IP server has received 6711456 bytes of data
,2015-11-20T12:11:56.026Z SendDataTCPServer.js: TCP/IP server has received 6842528 bytes of data
,2015-11-20T12:11:56.028Z SendDataTCPServer.js: TCP/IP server has received 6879520 bytes of data
,2015-11-20T12:11:56.443Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:56.443Z SendDataConnector.js: CLIENT is data received : 3400000
,2015-11-20T12:11:56.444Z SendDataTCPServer.js: TCP/IP server has received 6887712 bytes of data
,2015-11-20T12:11:56.478Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:56.478Z SendDataConnector.js: CLIENT is data received : 3550000
2015-11-20T12:11:56.479Z SendDataTCPServer.js: TCP/IP server has received 6889760 bytes of data
,2015-11-20T12:11:56.513Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:56.514Z SendDataConnector.js: CLIENT is data received : 3670000
2015-11-20T12:11:56.515Z SendDataTCPServer.js: TCP/IP server has received 6955296 bytes of data
,2015-11-20T12:11:56.530Z SendDataTCPServer.js: TCP/IP server has received 7086368 bytes of data
,2015-11-20T12:11:56.531Z SendDataTCPServer.js: TCP/IP server has received 7217440 bytes of data
,2015-11-20T12:11:56.533Z SendDataTCPServer.js: TCP/IP server has received 7298144 bytes of data
,2015-11-20T12:11:56.830Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:56.831Z SendDataConnector.js: CLIENT is data received : 4000000
,2015-11-20T12:11:56.832Z SendDataTCPServer.js: TCP/IP server has received 7300192 bytes of data
,2015-11-20T12:11:57.536Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:57.537Z SendDataConnector.js: CLIENT is data received : 5560000
,2015-11-20T12:11:57.537Z SendDataTCPServer.js: TCP/IP server has received 7306336 bytes of data
,2015-11-20T12:11:57.840Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:57.841Z SendDataConnector.js: CLIENT is data received : 6240000
,2015-11-20T12:11:57.842Z SendDataTCPServer.js: TCP/IP server has received 7308384 bytes of data
,2015-11-20T12:11:58.083Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:58.084Z SendDataConnector.js: CLIENT is data received : 6710000
,2015-11-20T12:11:58.085Z SendDataTCPServer.js: TCP/IP server has received 7328864 bytes of data
,2015-11-20T12:11:59.004Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:59.004Z SendDataConnector.js: CLIENT is data received : 8450000
,2015-11-20T12:11:59.005Z SendDataTCPServer.js: TCP/IP server has received 7332960 bytes of data
,2015-11-20T12:11:59.041Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:59.042Z SendDataConnector.js: CLIENT is data received : 8550000
,2015-11-20T12:11:59.043Z SendDataTCPServer.js: TCP/IP server has received 7335008 bytes of data
,2015-11-20T12:11:59.066Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:59.066Z SendDataConnector.js: CLIENT is data received : 8700000
,2015-11-20T12:11:59.067Z SendDataTCPServer.js: TCP/IP server has received 7337056 bytes of data
,2015-11-20T12:11:59.139Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:59.139Z SendDataConnector.js: CLIENT is data received : 9030000
,2015-11-20T12:11:59.139Z SendDataTCPServer.js: TCP/IP server has received 7339104 bytes of data
,2015-11-20T12:11:59.344Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:59.345Z SendDataConnector.js: CLIENT is data received : 9320000
,2015-11-20T12:11:59.346Z SendDataTCPServer.js: TCP/IP server has received 7341152 bytes of data
,2015-11-20T12:11:59.488Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:59.489Z SendDataConnector.js: CLIENT is data received : 9760000
2015-11-20T12:11:59.494Z SendDataTCPServer.js: TCP/IP serve,r has received 7472224 bytes of data
,2015-11-20T12:11:59.497Z SendDataTCPServer.js: TCP/IP server has received 7603296 bytes of data
,2015-11-20T12:11:59.501Z SendDataTCPServer.js: TCP/IP server has received 7609440 bytes of data
,2015-11-20T12:11:59.514Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:59.514Z SendDataConnector.js: CLIENT is data received : 9770000
2015-11-20T12:11:59.515Z SendDataTCPServer.js: TCP/IP server has received 7740512 bytes of data
2015-11-20T12:11:59.517Z SendDataTCPServer.js: TCP/IP server has received 7789664 bytes of data
,2015-11-20T12:11:59.531Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:59.531Z SendDataConnector.js: CLIENT is data received : 9880000
2015-11-20T12:11:59.532Z SendDataTCPServer.js: TCP/IP server has received 7920736 bytes of data
,2015-11-20T12:11:59.536Z SendDataTCPServer.js: TCP/IP server has received 8051808 bytes of data
,2015-11-20T12:11:59.539Z SendDataTCPServer.js: TCP/IP server has received 8127584 bytes of data
,2015-11-20T12:11:59.553Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:59.553Z SendDataConnector.js: CLIENT is data received : 9900000
2015-11-20T12:11:59.553Z SendDataTCPServer.js: TCP/IP server has received 8258656 bytes of data
,2015-11-20T12:11:59.555Z SendDataTCPServer.js: TCP/IP server has received 8381536 bytes of data
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20T12:11:59.577Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20T12:11:59.578Z SendDataConnector.js: CLIENT is data received : 9960000
,2015-11-20T12:11:59.578Z SendDataTCPServer.js: TCP/IP server has received 8512608 bytes of data
,2015-11-20T12:11:59.580Z SendDataTCPServer.js: TCP/IP server has received 8540128 bytes of data
,2015-11-20T12:11:59.594Z SendDataTCPServer.js: TCP/IP server has received 8561952 bytes of data
,2015-11-20T12:11:59.609Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:59.609Z SendDataConnector.js: CLIENT is data received : 9980000
,2015-11-20T12:11:59.621Z SendDataConnector.js: resetDataTimeout called with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20T12:11:59.623Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:11:59.623Z SendDataConnector.js: got all data for this round
,2015-11-20T12:11:59.623Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:11:59.623Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:11:59.624 ThaliTest[1010:776807] jxcore: disconnect
,2015-11-20 13:11:59.625 ThaliTest[1010:776807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:59.625 ThaliTest[1010:776807] client session: disconnect
,2015-11-20 13:11:59.626 ThaliTest[1010:776807] client session: stateChange:2->0 Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:11:59.627 ThaliTest[1010:776807] jxcore: disconnect: success
,2015-11-20T12:11:59.628Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7072.5zbvNA==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:11:59.631Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:11:59.632Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:11:59.644Z SendDataConnector.js: CLIENT is closed
,2015-11-20T12:11:59.863Z SendDataTCPServer.js: TCP/IP server has received 8562944 bytes of data
,2015-11-20T12:11:59.877Z SendDataTCPServer.js: TCP/IP server has received 8564928 bytes of data
,2015-11-20T12:11:59.914Z SendDataTCPServer.js: TCP/IP server has received 8565920 bytes of data
,2015-11-20T12:11:59.927Z SendDataTCPServer.js: TCP/IP server has received 8580800 bytes of data
,2015-11-20T12:11:59.941Z SendDataTCPServer.js: TCP/IP server has received 8600640 bytes of data
,2015-11-20T12:11:59.954Z SendDataTCPServer.js: TCP/IP server has received 8618496 bytes of data
,2015-11-20T12:11:59.966Z SendDataTCPServer.js: TCP/IP server has received 8638336 bytes of data
,2015-11-20T12:11:59.978Z SendDataTCPServer.js: TCP/IP server has received 8657184 bytes of data
,2015-11-20T12:11:59.993Z SendDataTCPServer.js: TCP/IP server has received 8676032 bytes of data
,2015-11-20T12:12:00.005Z SendDataTCPServer.js: TCP/IP server has received 8688928 bytes of data
,2015-11-20T12:12:00.020Z SendDataTCPServer.js: TCP/IP server has received 8710752 bytes of data
,2015-11-20T12:12:00.041Z SendDataTCPServer.js: TCP/IP server has received 8718688 bytes of data
,2015-11-20T12:12:00.055Z SendDataTCPServer.js: TCP/IP server has received 8781184 bytes of data
,2015-11-20T12:12:00.409Z SendDataTCPServer.js: TCP/IP server has received 8784160 bytes of data
,2015-11-20T12:12:00.425Z SendDataTCPServer.js: TCP/IP server has received 8796064 bytes of data
,2015-11-20T12:12:00.442Z SendDataTCPServer.js: TCP/IP server has received 8809952 bytes of data
,2015-11-20T12:12:00.461Z SendDataTCPServer.js: TCP/IP server has received 8822848 bytes of data
,2015-11-20T12:12:00.480Z SendDataTCPServer.js: TCP/IP server has received 8832768 bytes of data
,2015-11-20T12:12:00.521Z SendDataTCPServer.js: TCP/IP server has received 8833760 bytes of data
,2015-11-20T12:12:00.534Z SendDataTCPServer.js: TCP/IP server has received 8846656 bytes of data
,2015-11-20T12:12:00.549Z SendDataTCPServer.js: TCP/IP server has received 8861536 bytes of data
,2015-11-20T12:12:00.565Z SendDataTCPServer.js: TCP/IP server has received 8875424 bytes of data
,2015-11-20T12:12:00.580Z SendDataTCPServer.js: TCP/IP server has received 8888320 bytes of data
,2015-11-20T12:12:00.594Z SendDataTCPServer.js: TCP/IP server has received 8900224 bytes of data
,2015-11-20 13:12:00.633 ThaliTest[1010:776807] jxcore: disconnect
2015-11-20 13:12:00.634 ThaliTest[1010:776807] jxcore: disconnect: fail
2015-11-20T12:12:00.634Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q=,=
2015-11-20T12:12:00.634Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5-1_PT2716.py/N2Q== with availability status: true
,2015-11-20T12:12:00.635Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:00.635Z SendDataConnector.js: do connect now
,2015-11-20 13:12:00.635 ThaliTest[1010:776807] jxcore: connect Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:00.636 ThaliTest[1010:776807] client session: connect
2015-11-20 13:12:00.637 ThaliTest[1010:776807] client session: stateChange:0->1 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:00.938Z SendDataTCPServer.js: TCP/IP server has received 8904192 bytes of data
,2015-11-20T12:12:00.959Z SendDataTCPServer.js: TCP/IP server has received 8906176 bytes of data
,2015-11-20T12:12:00.974Z SendDataTCPServer.js: TCP/IP server has received 8912128 bytes of data
,2015-11-20T12:12:00.990Z SendDataTCPServer.js: TCP/IP server has received 8921056 bytes of data
,2015-11-20T12:12:01.005Z SendDataTCPServer.js: TCP/IP server has received 8930976 bytes of data
,2015-11-20T12:12:01.022Z SendDataTCPServer.js: TCP/IP server has received 8942880 bytes of data
,2015-11-20T12:12:01.072Z SendDataTCPServer.js: TCP/IP server has received 8943872 bytes of data
,2015-11-20T12:12:01.086Z SendDataTCPServer.js: TCP/IP server has received 8959744 bytes of data
,2015-11-20T12:12:01.100Z SendDataTCPServer.js: TCP/IP server has received 8972640 bytes of data
,2015-11-20T12:12:01.114Z SendDataTCPServer.js: TCP/IP server has received 8985536 bytes of data
,2015-11-20T12:12:01.129Z SendDataTCPServer.js: TCP/IP server has received 9013312 bytes of data
,2015-11-20T12:12:01.143Z SendDataTCPServer.js: TCP/IP server has received 9022240 bytes of data
,2015-11-20T12:12:01.455Z SendDataTCPServer.js: TCP/IP server has received 9023232 bytes of data
,2015-11-20T12:12:01.470Z SendDataTCPServer.js: TCP/IP server has received 9028192 bytes of data
,2015-11-20T12:12:01.484Z SendDataTCPServer.js: TCP/IP server has received 9035136 bytes of data
,2015-11-20T12:12:01.538Z SendDataTCPServer.js: TCP/IP server has received 9048032 bytes of data
,2015-11-20T12:12:01.551Z SendDataTCPServer.js: TCP/IP server has received 9062912 bytes of data
,2015-11-20T12:12:01.566Z SendDataTCPServer.js: TCP/IP server has received 9078784 bytes of data
,2015-11-20T12:12:01.582Z SendDataTCPServer.js: TCP/IP server has received 9093664 bytes of data
,2015-11-20T12:12:01.597Z SendDataTCPServer.js: TCP/IP server has received 9107552 bytes of data
,2015-11-20T12:12:01.610Z SendDataTCPServer.js: TCP/IP server has received 9127392 bytes of data
,2015-11-20T12:12:01.625Z SendDataTCPServer.js: TCP/IP server has received 9139296 bytes of data
,2015-11-20T12:12:01.638Z SendDataTCPServer.js: TCP/IP server has received 9158144 bytes of data
,2015-11-20T12:12:01.653Z SendDataTCPServer.js: TCP/IP server has received 9179968 bytes of data
,2015-11-20T12:12:01.666Z SendDataTCPServer.js: TCP/IP server has received 9189888 bytes of data
,2015-11-20T12:12:01.983Z SendDataTCPServer.js: TCP/IP server has received 9194848 bytes of data
,2015-11-20T12:12:01.998Z SendDataTCPServer.js: TCP/IP server has received 9199808 bytes of data
,2015-11-20T12:12:02.048Z SendDataTCPServer.js: TCP/IP server has received 9203776 bytes of data
,2015-11-20T12:12:02.062Z SendDataTCPServer.js: TCP/IP server has received 9209728 bytes of data
,2015-11-20T12:12:02.077Z SendDataTCPServer.js: TCP/IP server has received 9222624 bytes of data
,2015-11-20T12:12:02.091Z SendDataTCPServer.js: TCP/IP server has received 9233536 bytes of data
,2015-11-20T12:12:02.104Z SendDataTCPServer.js: TCP/IP server has received 9245440 bytes of data
,2015-11-20T12:12:02.118Z SendDataTCPServer.js: TCP/IP server has received 9259328 bytes of data
,2015-11-20T12:12:02.131Z SendDataTCPServer.js: TCP/IP server has received 9272224 bytes of data
,2015-11-20T12:12:02.148Z SendDataTCPServer.js: TCP/IP server has received 9285120 bytes of data
,2015-11-20T12:12:02.163Z SendDataTCPServer.js: TCP/IP server has received 9304960 bytes of data
,2015-11-20T12:12:02.176Z SendDataTCPServer.js: TCP/IP server has received 9323808 bytes of data
,2015-11-20T12:12:02.499Z SendDataTCPServer.js: TCP/IP server has received 9329760 bytes of data
,2015-11-20T12:12:02.515Z SendDataTCPServer.js: TCP/IP server has received 9338688 bytes of data
,2015-11-20T12:12:02.534Z SendDataTCPServer.js: TCP/IP server has received 9346624 bytes of data
,2015-11-20T12:12:02.549Z SendDataTCPServer.js: TCP/IP server has received 9348608 bytes of data
,2015-11-20T12:12:02.565Z SendDataTCPServer.js: TCP/IP server has received 9363488 bytes of data
,2015-11-20T12:12:02.580Z SendDataTCPServer.js: TCP/IP server has received 9374400 bytes of data
,2015-11-20T12:12:02.596Z SendDataTCPServer.js: TCP/IP server has received 9390272 bytes of data
,2015-11-20T12:12:02.613Z SendDataTCPServer.js: TCP/IP server has received 9408128 bytes of data
,2015-11-20T12:12:02.628Z SendDataTCPServer.js: TCP/IP server has received 9421024 bytes of data
,2015-11-20T12:12:02.642Z SendDataTCPServer.js: TCP/IP server has received 9432928 bytes of data
,2015-11-20T12:12:02.658Z SendDataTCPServer.js: TCP/IP server has received 9445824 bytes of data
,2015-11-20T12:12:02.674Z SendDataTCPServer.js: TCP/IP server has received 9458720 bytes of data
,2015-11-20T12:12:02.686Z SendDataTCPServer.js: TCP/IP server has received 9477568 bytes of data
,2015-11-20T12:12:02.699Z SendDataTCPServer.js: TCP/IP server has received 9500384 bytes of data
,2015-11-20T12:12:02.713Z SendDataTCPServer.js: TCP/IP server has received 9518240 bytes of data
,2015-11-20T12:12:03.042Z SendDataTCPServer.js: TCP/IP server has received 9520224 bytes of data
,2015-11-20T12:12:03.057Z SendDataTCPServer.js: TCP/IP server has received 9525184 bytes of data
,2015-11-20T12:12:03.072Z SendDataTCPServer.js: TCP/IP server has received 9530144 bytes of data
,2015-11-20T12:12:03.088Z SendDataTCPServer.js: TCP/IP server has received 9539072 bytes of data
,2015-11-20T12:12:03.103Z SendDataTCPServer.js: TCP/IP server has received 9549984 bytes of data
,2015-11-20T12:12:03.116Z SendDataTCPServer.js: TCP/IP server has received 9560896 bytes of data
,2015-11-20T12:12:03.131Z SendDataTCPServer.js: TCP/IP server has received 9574784 bytes of data
,2015-11-20T12:12:03.144Z SendDataTCPServer.js: TCP/IP server has received 9586688 bytes of data
,2015-11-20T12:12:03.157Z SendDataTCPServer.js: TCP/IP server has received 9601568 bytes of data
,2015-11-20T12:12:03.173Z SendDataTCPServer.js: TCP/IP server has received 9615456 bytes of data
,2015-11-20T12:12:03.189Z SendDataTCPServer.js: TCP/IP server has received 9630336 bytes of data
,2015-11-20T12:12:03.203Z SendDataTCPServer.js: TCP/IP server has received 9647200 bytes of data
,2015-11-20T12:12:03.217Z SendDataTCPServer.js: TCP/IP server has received 9674976 bytes of data
,2015-11-20T12:12:03.231Z SendDataTCPServer.js: TCP/IP server has received 9694816 bytes of data
,2015-11-20T12:12:03.551Z SendDataTCPServer.js: TCP/IP server has received 9697792 bytes of data
,2015-11-20T12:12:03.568Z SendDataTCPServer.js: TCP/IP server has received 9699776 bytes of data
,2015-11-20T12:12:03.587Z SendDataTCPServer.js: TCP/IP server has received 9712672 bytes of data
,2015-11-20T12:12:03.609Z SendDataTCPServer.js: TCP/IP server has received 9720608 bytes of data
,2015-11-20T12:12:03.625Z SendDataTCPServer.js: TCP/IP server has received 9735488 bytes of data
,2015-11-20T12:12:03.640Z SendDataTCPServer.js: TCP/IP server has received 9750368 bytes of data
,2015-11-20T12:12:03.655Z SendDataTCPServer.js: TCP/IP server has received 9763264 bytes of data
,2015-11-20T12:12:03.669Z SendDataTCPServer.js: TCP/IP server has received 9774176 bytes of data
,2015-11-20T12:12:03.684Z SendDataTCPServer.js: TCP/IP server has received 9785088 bytes of data
,2015-11-20T12:12:03.698Z SendDataTCPServer.js: TCP/IP server has received 9796000 bytes of data
,2015-11-20T12:12:03.711Z SendDataTCPServer.js: TCP/IP server has received 9806912 bytes of data
,2015-11-20T12:12:03.728Z SendDataTCPServer.js: TCP/IP server has received 9822784 bytes of data
,2015-11-20T12:12:03.744Z SendDataTCPServer.js: TCP/IP server has received 9837664 bytes of data
,2015-11-20T12:12:03.758Z SendDataTCPServer.js: TCP/IP server has received 9858496 bytes of data
,2015-11-20T12:12:03.770Z SendDataTCPServer.js: TCP/IP server has received 9868416 bytes of data
,2015-11-20T12:12:04.072Z SendDataTCPServer.js: TCP/IP server has received 9869408 bytes of data
,2015-11-20T12:12:04.086Z SendDataTCPServer.js: TCP/IP server has received 9871392 bytes of data
,2015-11-20T12:12:04.100Z SendDataTCPServer.js: TCP/IP server has received 9874368 bytes of data
,2015-11-20T12:12:04.115Z SendDataTCPServer.js: TCP/IP server has received 9876352 bytes of data
,2015-11-20T12:12:04.128Z SendDataTCPServer.js: TCP/IP server has received 9884288 bytes of data
,2015-11-20T12:12:04.144Z SendDataTCPServer.js: TCP/IP server has received 9893216 bytes of data
,2015-11-20T12:12:04.157Z SendDataTCPServer.js: TCP/IP server has received 9902144 bytes of data
,2015-11-20T12:12:04.171Z SendDataTCPServer.js: TCP/IP server has received 9917024 bytes of data
,2015-11-20T12:12:04.184Z SendDataTCPServer.js: TCP/IP server has received 9929920 bytes of data
,2015-11-20T12:12:04.197Z SendDataTCPServer.js: TCP/IP server has received 9941824 bytes of data
,2015-11-20T12:12:04.213Z SendDataTCPServer.js: TCP/IP server has received 9955712 bytes of data
,2015-11-20T12:12:04.229Z SendDataTCPServer.js: TCP/IP server has received 9968608 bytes of data
,2015-11-20T12:12:04.242Z SendDataTCPServer.js: TCP/IP server has received 9983488 bytes of data
,2015-11-20T12:12:04.256Z SendDataTCPServer.js: TCP/IP server has received 9999360 bytes of data
,2015-11-20T12:12:04.270Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20 13:12:04.642 ThaliTest[1010:778011] server session: not connected Apple-Iphone5-1_PT2716
,2015-11-20 13:12:06.239 ThaliTest[1010:777749] client session: connected
2015-11-20 13:12:06.240 ThaliTest[1010:777749] client session: stateChange:1->2 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:06.252 ThaliTest[1010:777967] client session: fireConnectCallback: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:06.252 ThaliTest[1010:777967] jxcore: connect: success
2015-11-20T12:12:06.253Z SendDataConnector.js: CLIENT connected to, 55882, error: null
2015-11-20T12:12:06.254Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:12:06.257 ThaliTest[1010:776684] client: relay established
2015-11-20 13:12:06.258 ThaliTest[1010:776684] client: new accepted socket: 0x18682540
,2015-11-20T12:12:06.270Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:12:10.995Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20T12:12:20.996Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:12:20.997Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:12:20.998Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:12:20.999Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T12:12:21.000Z SendDataConnector.js: CLIENT is closed
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20 13:12:21.359 ThaliTest[1010:776684] client: socket closed
2015-11-20 13:12:21.359 ThaliTest[1010:776684] client relay: socket disconnected
2015-11-20 13:12:21.361 ThaliTest[1010:776684] client relay: 0x18682540 disconnected with error Error Do,main=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x14682bd0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 13:12:21.362 ThaliTest[1010:776684] client session: socket closed: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:21.362 ThaliTest[1010:776684] client session: onLinkFailure: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:21.363 ThaliTest[1010:776684] client session: disconnect
2015-11-20 13:12:21.364 ThaliTest[1010:776684] client session: stateCh,ange:2->0 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:21.389 ThaliTest[1010:776684] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:22.006Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:22.007Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:23.013 ThaliTest[1010:776807] jxcore: disconnect
2015-11-20 13:12:23.013 ThaliTest[1010:776807] jxcore: disconnect: fail
2015-11-20T12:12:23.014Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q=,=
2015-11-20T12:12:23.015Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT2716.py/N2Q== with availability status: true
2015-11-20T12:12:23.015Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:23.015Z SendDataConnector.js: do connect now
,2015-11-20 13:12:23.016 ThaliTest[1010:776807] jxcore: connect Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:23.018 ThaliTest[1010:776807] client session: connect
2015-11-20 13:12:23.019 ThaliTest[1010:776807] client session: stateChange:0->1 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:23.729 ThaliTest[1010:776684] multipeer session: restart
,2015-11-20 13:12:23.752 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:12:23.754 ThaliTest[1010:776684] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:23.756 ThaliTest[1010:776684] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20 13:12:37.555 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20 13:12:50.642 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20 13:12:53.729 ThaliTest[1010:776684] multipeer session: restart
,2015-11-20 13:12:53.750 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:12:53.753 ThaliTest[1010:776684] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
2015-11-20 13:12:53.754 ThaliTest[1010:776684] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:56.027 ThaliTest[1010:777749] client session: not connected Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:56.028 ThaliTest[1010:777749] client session: onLinkFailure: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:56.028 ThaliTest[1,010:777749] client session: disconnect
2015-11-20 13:12:56.029 ThaliTest[1010:777749] client session: stateChange:1->0 Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:56.030 ThaliTest[1010:777749] client session: fireConnectCallback: Apple-Iphone5-1_PT2,716.py/N2Q==
2015-11-20 13:12:56.030 ThaliTest[1010:777749] jxcore: connect: fail: Peer disconnected
,2015-11-20T12:12:56.032Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T12:12:56.033Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T12:12:56.033Z SendDataConnector.js: tryAgain afer: 1000 ms.,
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":,10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"a,rraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfa,ceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20T12:12:57.043Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:57.043Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:58.050 ThaliTest[1010:776807] jxcore: disconnect
2015-11-20 13:12:58.051 ThaliTest[1010:776807] jxcore: disconnect: fail
2015-11-20T12:12:58.052Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q=,=
2015-11-20T12:12:58.053Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT2716.py/N2Q== with availability status: true
2015-11-20T12:12:58.053Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:58.053Z SendDataConnector.js: do connect now
2015-11-20 13:12:58.054 ThaliTest[1010:776807] jxcore: connect Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:58.055 ThaliTest[1010:776807] client session: connect
,2015-11-20 13:12:58.056 ThaliTest[1010:776807] client session: stateChange:0->1 Apple-Iphone5-1_PT2716.py/N2Q==
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::e429:c7ff:fe67:1f88
,2015-11-20 13:13:23.729 ThaliTest[1010:776684] multipeer session: restart
,2015-11-20 13:13:23.796 ThaliTest[1010:776684] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:13:26.285 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:13:26.368 ThaliTest[1010:776684] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:13:31.063 ThaliTest[1010:778142] client session: not connected Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:13:31.064 ThaliTest[1010:778142] client session: onLinkFailure: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:13:31.064 ThaliTest[1010:778142] client session: disconnect
,2015-11-20 13:13:31.065 ThaliTest[1010:778142] client session: stateChange:1->0 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:13:31.066 ThaliTest[1010:778142] client session: fireConnectCallback: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:13:31.067 ThaliTest[1010:778142] jxcore: connect: fail: Peer disconnected
2015-11-20T12:13:31.069Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T12:13:31.071Z SendDataConnector.js: CLIENT Can not Connect: ,Peer disconnected
2015-11-20T12:13:31.071Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:13:32.083Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:13:32.084Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:13:33.096 ThaliTest[1010:776807] jxcore: disconnect
2015-11-20 13:13:33.097 ThaliTest[1010:776807] jxcore: disconnect: fail
2015-11-20T12:13:33.097Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q=,=
2015-11-20T12:13:33.098Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT2716.py/N2Q== with availability status: true
2015-11-20T12:13:33.098Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:13:33.099Z SendDataConnector.js: do connect now
,2015-11-20 13:13:33.100 ThaliTest[1010:776807] jxcore: connect Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:13:33.101 ThaliTest[1010:776807] client session: connect
,2015-11-20 13:13:33.102 ThaliTest[1010:776807] client session: stateChange:0->1 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:13:42.569 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:13:53.729 ThaliTest[1010:776684] multipeer session: restart
,2015-11-20 13:13:53.753 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:13:53.755 ThaliTest[1010:776684] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:13:54.668 ThaliTest[1010:776684] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:14:06.110 ThaliTest[1010:777749] client session: not connected Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:14:06.110 ThaliTest[1010:777749] client session: onLinkFailure: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:14:06.111 ThaliTest[1,010:777749] client session: disconnect
2015-11-20 13:14:06.112 ThaliTest[1010:777749] client session: stateChange:1->0 Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:14:06.113 ThaliTest[1010:777749] client session: fireConnectCallback: Apple-Iphone5-1_PT2,716.py/N2Q==
2015-11-20 13:14:06.113 ThaliTest[1010:777749] jxcore: connect: fail: Peer disconnected
2015-11-20T12:14:06.115Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-11-20T12:14:06.116Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T12:14:06.116Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:14:07.125Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:14:07.126Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:14:08.129 ThaliTest[1010:776807] jxcore: disconnect
2015-11-20 13:14:08.130 ThaliTest[1010:776807] jxcore: disconnect: fail
2015-11-20T12:14:08.131Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q=,=
2015-11-20T12:14:08.132Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT2716.py/N2Q== with availability status: true
,2015-11-20T12:14:08.132Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:14:08.132Z SendDataConnector.js: do connect now
,2015-11-20 13:14:08.133 ThaliTest[1010:776807] jxcore: connect Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:14:08.134 ThaliTest[1010:776807] client session: connect
,2015-11-20 13:14:08.135 ThaliTest[1010:776807] client session: stateChange:0->1 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:14:08.358 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:14:23.727 ThaliTest[1010:776684] multipeer session: restart
,2015-11-20 13:14:23.746 ThaliTest[1010:776684] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:14:23.748 ThaliTest[1010:776684] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:14:24.004 ThaliTest[1010:776684] client: found peer: Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:14:41.141 ThaliTest[1010:778685] client session: not connected Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:14:41.142 ThaliTest[1010:778685] client session: onLinkFailure: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:14:41.143 ThaliTest[1,010:778685] client session: disconnect
2015-11-20 13:14:41.143 ThaliTest[1010:778685] client session: stateChange:1->0 Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:14:41.144 ThaliTest[1010:778685] client session: fireConnectCallback: Apple-Iphone5-1_PT2,716.py/N2Q==
2015-11-20 13:14:41.145 ThaliTest[1010:778685] jxcore: connect: fail: Peer disconnected
,2015-11-20T12:14:41.146Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T12:14:41.147Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T12:14:41.147Z SendDataConnector.js: CLIENT Stop now
2015-1,1-20T12:14:41.148Z SendDataConnector.js: Stop data retrieving timer
,2015-11-20 13:14:41.149 ThaliTest[1010:776807] jxcore: disconnect
,2015-11-20 13:14:41.150 ThaliTest[1010:776807] jxcore: disconnect: fail
,2015-11-20T12:14:41.151Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q==
,---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT497","time":264042,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT2043.OU3s0w==","time":31099,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT7072.5zbvNA==","time":70969,"result":"OK","connection,s":3},{"name":"Apple-Iphone5-1_PT2716.py/N2Q==","time":161519,"result":"Peer disconnected","connections":5}]}
,sendList : 100% : 70969 ms, 99% : 70969 ms, 95 : 70969 ms, 90% : 70969 ms.
,Result count 2, range 31099 ms to  70969 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone5-1_PT2716.py/N2Q==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-11-20T12:14:41.168Z SendDataConnector.js: CLIENT Stop now
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-20 13:14:42.021 ThaliTest[1010:776807] jxcore: stopBroadcasting
2015-11-20 13:14:42.022 ThaliTest[1010:776807] THEMultipeerSession stopping peer
2015-11-20 13:14:42.022 ThaliTest[1010:776807] multipeer session: stop timer
2015-11-20 13:14:42.023, ThaliTest[1010:776807] server session: disconnect
2015-11-20 13:14:42.024 ThaliTest[1010:776807] server session: stateChange:2->0 Apple-IpadAir2-1_PT7072
,2015-11-20 13:14:42.092 ThaliTest[1010:776807] server session: disconnect
,2015-11-20 13:14:42.094 ThaliTest[1010:776807] server session: stateChange:2->0 Apple-Iphone5-1_PT2716
,2015-11-20 13:14:42.098 ThaliTest[1010:776807] server session: disconnect
,2015-11-20 13:14:42.099 ThaliTest[1010:776807] server session: stateChange:2->0 Apple-Iphone6-1_PT2043
,2015-11-20 13:14:42.103 ThaliTest[1010:776807] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-20T12:14:42.118Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20T12:14:42.118Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20T12:14:42.119Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20T12:14:42.119Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,2015-11-20T12:14:42.120Z SendDataTCPServer.js: TCP/IP server is close
,2015-11-20T12:14:42.120Z SendDataTCPServer.js: TCP/IP server is close
,2015-11-20T12:14:42.120Z SendDataTCPServer.js: TCP/IP server is close
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":31099,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7072.5zbvNA==\",\"time\":70969,\"result\":\"OK\",\"connections\":3}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5-1_PT2716.py/N2Q==\",\"time\":161519,\"result\":\"Peer disconnected\",\"connections\":5}],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Ipad,Air2-1_PT7072.5zbvNA==\",\"time\":26141,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":29961,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":31099,\"result\":\"OK\",\",connections\":1},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":31207,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":33577,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT2716.py/N2Q==,\",\"time\":52469,\"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-IpadAir2-1_PT7072.5zbvNA==\",\"time\":57845,\"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":58779,\"result\":\"OK\",\"connections\":2},{\"n,ame\":\"Apple-IpadAir2-1_PT7072.5zbvNA==\",\"time\":70969,\"result\":\"OK\",\"connections\":3},{\"name\":\"Apple-Iphone5-1_PT2716.py/N2Q==\",\"time\":84289,\"result\":\"OK\",\"connections\":3},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":107161,\,"result\":\"OK\",\"connections\":4}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
