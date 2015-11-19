#### Test 51193821e3da755_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51193821e3da755/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DCF8DAE8-7065-4E2B-A46D-0F3B31E3EE26/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/DCF8DAE8-7065-4E2B-A46D-0F3B31E3EE26/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51193821e3da755/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51193821e3da755/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E79654AC-5B08-42E8-8196-DBCB89B3D326/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50444"
,(lldb)     command script import "/tmp/DCF8DAE8-7065-4E2B-A46D-0F3B31E3EE26/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-19 10:40:02.716 ThaliTest[879:643824] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/46CFBC6D-EE10-4658-82BE-4280CDC5FF4F/Library/Cookies/Cookies.binarycookies
,2015-11-19 10:40:03.132 ThaliTest[879:643824] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-19 10:40:03.134 ThaliTest[879:643824] Multi-tasking -> Device: YES, App: YES
,2015-11-19 10:40:03.142 ThaliTest[879:643824] Unlimited access to network resources
,2015-11-19 10:40:03.149 ThaliTest[879:643824] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-19 10:40:06.879 ThaliTest[879:643824] Resetting plugins due to page load.
,2015-11-19 10:40:07.356 ThaliTest[879:643824] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/E79654AC-5B08-42E8-8196-DBCB89B3D326/ThaliTest.app/www/index.html
,2015-11-19 10:40:07.510 ThaliTest[879:643824] JXcore Cordova plugin initializing
,2015-11-19 10:40:07.512 ThaliTest[879:644015] JXcore instance initializing
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
toggleWiFi
,my name is : Apple-Iphone5s-1_PT9462
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
,-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"1000000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":2,"addressList":[],}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"500000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 55207
,2015-11-19 10:49:08.394 ThaliTest[879:644015] jxcore: startBroadcasting
,2015-11-19 10:49:08.411 ThaliTest[879:644015] server: starting Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:49:08.428 ThaliTest[879:644015] multipeer session: start timer: 0x18fbe270
,2015-11-19 10:49:08.431 ThaliTest[879:644015] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT9462
,2015-11-19 10:49:08.433 ThaliTest[879:644015] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,TCP/IP server  is bound to : undefined
,2015-11-19 10:49:08.912 ThaliTest[879:643824] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,device[1]: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:09.899 ThaliTest[879:643824] client: found peer: Apple-IpadAir2-1_PT6621.ucYn4g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6621.ucYn4g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-19 10:49:13.932 ThaliTest[879:644015] jxcore: disconnect
2015-11-19 10:49:13.933 ThaliTest[879:644015] jxcore: disconnect: fail
Connect (retry count 0) to peer Apple-Iphone6-1_PT4558.76EyUA== with availability status: true
,do connect now
,2015-11-19 10:49:13.936 ThaliTest[879:644015] jxcore: connect Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:13.937 ThaliTest[879:644015] client session: connect
,2015-11-19 10:49:13.939 ThaliTest[879:644015] client session: stateChange:0->1 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:15.263 ThaliTest[879:643824] multipeer session: reset timer
2015-11-19 10:49:15.264 ThaliTest[879:643824] multipeer session: stop timer
2015-11-19 10:49:15.265 ThaliTest[879:643824] multipeer session: start timer: 0x18fbe270
2015-11-19 ,10:49:15.266 ThaliTest[879:643824] server session: connect
2015-11-19 10:49:15.266 ThaliTest[879:643824] server session: stateChange:0->1 Apple-Iphone6-1_PT4558
,2015-11-19 10:49:15.279 ThaliTest[879:643824] server: accepting invitation Apple-Iphone6-1_PT4558
,2015-11-19 10:49:17.285 ThaliTest[879:644792] client session: connected
2015-11-19 10:49:17.286 ThaliTest[879:644792] client session: stateChange:1->2 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:17.293 ThaliTest[879:644792] client session: fireConnectCallback: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:17.294 ThaliTest[879:644792] jxcore: connect: success
CLIENT connected to 55211, error: null
CLIENT starting client 
,2015-11-19 10:49:17.300 ThaliTest[879:643824] client: relay established
2015-11-19 10:49:17.301 ThaliTest[879:643824] client: new accepted socket: 0x18fcd640
,CLIENT now sending 1000000 bytes of data
,2015-11-19 10:49:17.397 ThaliTest[879:644798] server session: connected
2015-11-19 10:49:17.398 ThaliTest[879:644798] server session: stateChange:1->2 Apple-Iphone6-1_PT4558
,2015-11-19 10:49:17.403 ThaliTest[879:643824] server relay: connected (to port: 55207)
,TCP/IP server connected
,TCP/IP server has received 63488 bytes of data
,TCP/IP server has received 194560 bytes of data
,TCP/IP server has received 229950 bytes of data
,TCP/IP server has received 234330 bytes of data
,TCP/IP server has received 249660 bytes of data
,TCP/IP server has received 267180 bytes of data
,TCP/IP server has received 282510 bytes of data
,TCP/IP server has received 315360 bytes of data
,TCP/IP server has received 319740 bytes of data
,TCP/IP server has received 352590 bytes of data
,TCP/IP server has received 370110 bytes of data
,TCP/IP server has received 383250 bytes of data
,TCP/IP server has received 389820 bytes of data
,TCP/IP server has received 407340 bytes of data
,TCP/IP server has received 438000 bytes of data
,TCP/IP server has received 459900 bytes of data
,TCP/IP server has received 481800 bytes of data
,CLIENT is data received : 0
,TCP/IP server has received 503700 bytes of data
,TCP/IP server has received 514650 bytes of data
,TCP/IP server has received 536550 bytes of data
,TCP/IP server has received 540930 bytes of data
,TCP/IP server has received 543120 bytes of data
,TCP/IP server has received 562830 bytes of data
,TCP/IP server has received 573780 bytes of data
,TCP/IP server has received 593490 bytes of data
,TCP/IP server has received 595680 bytes of data
,TCP/IP server has received 606630 bytes of data
,TCP/IP server has received 613200 bytes of data
,TCP/IP server has received 635100 bytes of data
,TCP/IP server has received 652620 bytes of data
,TCP/IP server has received 667950 bytes of data
,TCP/IP server has received 678900 bytes of data
,TCP/IP server has received 694230 bytes of data
,TCP/IP server has received 705180 bytes of data
,TCP/IP server has received 724890 bytes of data
,TCP/IP server has received 744600 bytes of data
,TCP/IP server has received 759930 bytes of data
,TCP/IP server has received 775260 bytes of data
,TCP/IP server has received 790590 bytes of data
,TCP/IP server has received 812490 bytes of data
,TCP/IP server has received 832200 bytes of data
,TCP/IP server has received 862860 bytes of data
,CLIENT is data received : 0
,TCP/IP server has received 886950 bytes of data
,TCP/IP server has received 893520 bytes of data
,CLIENT is data received : 10000
,CLIENT is data received : 10000
,TCP/IP server has received 973392 bytes of data
,TCP/IP server has received 1000002 bytes of data
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:49:29.624 ThaliTest[879:643824] client: socket closed
----------------- closeClientSocket
2015-11-19 10:49:29.625 ThaliTest[879:643824] client relay: socket disconnected
CLIENT is closed
2015-11-19 10:49:29.625 Th,aliTest[879:643824] client relay: 0x18fcd640 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18fc6900 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:49:29.626 ThaliTest[,879:643824] client session: socket closed: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:29.626 ThaliTest[879:643824] client session: onLinkFailure: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:29.627 ThaliTest[879:643824] client session: disconnect
2015-11-19 10:49:29.627 ThaliTest[879:643824] client session: stateChang,e:2->0 Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:29.630 ThaliTest[879:643824] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:29.937 ThaliTest[879:644856] server session: not connected Apple-Iphone6-1_PT4558
,re-try now : Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:39.640 ThaliTest[879:644015] jxcore: disconnect
2015-11-19 10:49:39.642 ThaliTest[879:644015] jxcore: disconnect: fail
Connect (retry count 1) to peer Apple-Iphone6-1_PT4558.76EyUA== with availability status: true
do connect now
,2015-11-19 10:49:39.644 ThaliTest[879:644015] jxcore: connect Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:39.644 ThaliTest[879:644015] client session: connect
2015-11-19 10:49:39.645 ThaliTest[879:644015] client session: stateChange:0->1 Apple-Iphon,e6-1_PT4558.76EyUA==
,2015-11-19 10:49:40.327 ThaliTest[879:643824] multipeer session: reset timer
2015-11-19 10:49:40.328 ThaliTest[879:643824] multipeer session: stop timer
2015-11-19 10:49:40.328 ThaliTest[879:643824] multipeer session: start timer: 0x18fbe270
2015-11-19 ,10:49:40.329 ThaliTest[879:643824] server: disconnecting to refresh session (Apple-Iphone6-1_PT4558)
2015-11-19 10:49:40.329 ThaliTest[879:643824] server session: disconnect
2015-11-19 10:49:40.330 ThaliTest[879:643824] server session: stateChange:2->0 A,pple-Iphone6-1_PT4558
2015-11-19 10:49:40.333 ThaliTest[879:643824] server session: connect
2015-11-19 10:49:40.334 ThaliTest[879:643824] server session: stateChange:0->1 Apple-Iphone6-1_PT4558
TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:49:40.358 ThaliTest[879:643824] server: accepting invitation Apple-Iphone6-1_PT4558
,2015-11-19 10:49:42.047 ThaliTest[879:644873] client session: connected
2015-11-19 10:49:42.048 ThaliTest[879:644873] client session: stateChange:1->2 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:42.054 ThaliTest[879:644873] client session: fireConnectCallback: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:42.055 ThaliTest[879:644873] jxcore: connect: success
CLIENT connected to 55216, error: null
,CLIENT starting client 
,2015-11-19 10:49:42.062 ThaliTest[879:643824] client: relay established
2015-11-19 10:49:42.063 ThaliTest[879:643824] client: new accepted socket: 0x18fb2b10
,CLIENT now sending 990000 bytes of data
,2015-11-19 10:49:42.493 ThaliTest[879:644884] server session: connected
2015-11-19 10:49:42.494 ThaliTest[879:644884] server session: stateChange:1->2 Apple-Iphone6-1_PT4558
,2015-11-19 10:49:42.498 ThaliTest[879:643824] server relay: connected (to port: 55207)
,TCP/IP server connected
,TCP/IP server has received 17520 bytes of data
,TCP/IP server has received 59130 bytes of data
,TCP/IP server has received 113880 bytes of data
,TCP/IP server has received 159870 bytes of data
,TCP/IP server has received 232140 bytes of data
,TCP/IP server has received 293318 bytes of data
,TCP/IP server has received 343830 bytes of data
,TCP/IP server has received 400770 bytes of data
,CLIENT is data received : 20000
,TCP/IP server has received 418290 bytes of data
,TCP/IP server has received 437716 bytes of data
,TCP/IP server has received 453330 bytes of data
,TCP/IP server has received 475230 bytes of data
,TCP/IP server has received 499320 bytes of data
,TCP/IP server has received 519030 bytes of data
,TCP/IP server has received 536550 bytes of data
,TCP/IP server has received 565020 bytes of data
,TCP/IP server has received 591300 bytes of data
,TCP/IP server has received 617580 bytes of data
,TCP/IP server has received 648240 bytes of data
,TCP/IP server has received 676710 bytes of data
,TCP/IP server has received 702990 bytes of data
,TCP/IP server has received 729270 bytes of data
,CLIENT is data received : 20000
,TCP/IP server has received 762120 bytes of data
,TCP/IP server has received 797160 bytes of data
,TCP/IP server has received 834390 bytes of data
,TCP/IP server has received 860670 bytes of data
,TCP/IP server has received 897900 bytes of data
,TCP/IP server has received 941700 bytes of data
,TCP/IP server has received 950002 bytes of data
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
----------------- closeClientSocket
2015-11-19 10:49:53.235 ThaliTest[879:643824] client: socket closed
CLIENT is closed
2015-11-19 10:49:53.236 ThaliTest[879:643824] client relay: socket disconnected
,2015-11-19 10:49:53.236 ThaliTest[879:643824] client relay: 0x18fb2b10 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x14d702c0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:49:53.237 ThaliTest[879:643824] client session: socket closed: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:53.237 ThaliTest[879:643824] client session: onLinkFailure: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:53.238 ThaliTest[879:643824] client session: disconnect
,2015-11-19 10:49:53.239 ThaliTest[879:643824] client session: stateChange:2->0 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:53.241 ThaliTest[879:643824] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:53.994 ThaliTest[879:644870] server session: not connected Apple-Iphone6-1_PT4558
,re-try now : Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:03.249 ThaliTest[879:644015] jxcore: disconnect
2015-11-19 10:50:03.250 ThaliTest[879:644015] jxcore: disconnect: fail
Connect (retry count 2) to peer Apple-Iphone6-1_PT4558.76EyUA== with availability status: true
do connect now
,2015-11-19 10:50:03.252 ThaliTest[879:644015] jxcore: connect Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:03.253 ThaliTest[879:644015] client session: connect
2015-11-19 10:50:03.254 ThaliTest[879:644015] client session: stateChange:0->1 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:04.489 ThaliTest[879:643824] multipeer session: reset timer
2015-11-19 10:50:04.490 ThaliTest[879:643824] multipeer session: stop timer
2015-11-19 10:50:04.490 ThaliTest[879:643824] multipeer session: start timer: 0x18fbe270
2015-11-19 ,10:50:04.491 ThaliTest[879:643824] server: disconnecting to refresh session (Apple-Iphone6-1_PT4558)
2015-11-19 10:50:04.492 ThaliTest[879:643824] server session: disconnect
2015-11-19 10:50:04.493 ThaliTest[879:643824] server session: stateChange:2->0 A,pple-Iphone6-1_PT4558
2015-11-19 10:50:04.496 ThaliTest[879:643824] server session: connect
2015-11-19 10:50:04.496 ThaliTest[879:643824] server session: stateChange:0->1 Apple-Iphone6-1_PT4558
,TCP/IP server is ended
TCP/IP server is close
2015-11-19 10:50:04.516 ThaliTest[879:643824] server: accepting invitation Apple-Iphone6-1_PT4558
,2015-11-19 10:50:05.987 ThaliTest[879:644884] client session: connected
2015-11-19 10:50:05.989 ThaliTest[879:644884] client session: stateChange:1->2 Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:05.991 ThaliTest[879:644884] client session: fireConne,ctCallback: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:05.992 ThaliTest[879:644884] jxcore: connect: success
CLIENT connected to 55221, error: null
,CLIENT starting client 
,2015-11-19 10:50:05.999 ThaliTest[879:643824] client: relay established
2015-11-19 10:50:06.000 ThaliTest[879:643824] client: new accepted socket: 0x18eda210
,CLIENT now sending 980000 bytes of data
,2015-11-19 10:50:06.581 ThaliTest[879:644884] server session: connected
2015-11-19 10:50:06.581 ThaliTest[879:644884] server session: stateChange:1->2 Apple-Iphone6-1_PT4558
,TCP/IP server connected
,2015-11-19 10:50:06.700 ThaliTest[879:643824] server relay: connected (to port: 55207)
,CLIENT is data received : 20000
,TCP/IP server has received 8760 bytes of data
,TCP/IP server has received 30660 bytes of data
,TCP/IP server has received 61320 bytes of data
,TCP/IP server has received 87600 bytes of data
,TCP/IP server has received 107310 bytes of data
,TCP/IP server has received 143972 bytes of data
,TCP/IP server has received 179580 bytes of data
,TCP/IP server has received 210240 bytes of data
,TCP/IP server has received 219000 bytes of data
,TCP/IP server has received 223380 bytes of data
,TCP/IP server has received 234330 bytes of data
,TCP/IP server has received 243090 bytes of data
,TCP/IP server has received 258420 bytes of data
,TCP/IP server has received 275940 bytes of data
,TCP/IP server has received 304410 bytes of data
,CLIENT is data received : 30000
,TCP/IP server has received 337260 bytes of data
,TCP/IP server has received 363540 bytes of data
,CLIENT is data received : 30000
,TCP/IP server has received 396390 bytes of data
,TCP/IP server has received 422670 bytes of data
,TCP/IP server has received 446618 bytes of data
,TCP/IP server has received 473040 bytes of data
,TCP/IP server has received 510270 bytes of data
,TCP/IP server has received 549690 bytes of data
,TCP/IP server has received 580350 bytes of data
,TCP/IP server has received 606488 bytes of data
,TCP/IP server has received 641670 bytes of data
,TCP/IP server has received 670140 bytes of data
,TCP/IP server has received 709560 bytes of data
,TCP/IP server has received 746790 bytes of data
,TCP/IP server has received 792780 bytes of data
,TCP/IP server has received 843150 bytes of data
,TCP/IP server has received 895710 bytes of data
,TCP/IP server has received 900002 bytes of data
,2015-11-19 10:50:13.343 ThaliTest[879:643824] client: lost peer: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:50:13.344 ThaliTest[879:643824] client session: onPeerLost: Apple-IpadAir2-1_PT6621.ucYn4g==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT6621.ucYn4g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-19 10:50:15.476 ThaliTest[879:643824] client: found peer: Apple-IpadAir2-1_PT6621.ucYn4g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6621.ucYn4g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:50:17.670 ThaliTest[879:643824] client: socket closed
----------------- closeClientSocket
2015-11-19 10:50:17.671 ThaliTest[879:643824] client relay: socket disconnected
CLIENT is closed
,2015-11-19 10:50:17.672 ThaliTest[879:643824] client relay: 0x18eda210 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18edee40 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-,19 10:50:17.672 ThaliTest[879:643824] client session: socket closed: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:17.673 ThaliTest[879:643824] client session: onLinkFailure: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:17.673 ThaliTest[879:643824] client session: disconnect
2015-11-19 10:50:17.674 ThaliTest[879:643824] client session: stateChange:2->0 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:17.676 ThaliTest[879:643824] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:18.104 ThaliTest[879:644873] server session: not connected Apple-Iphone6-1_PT4558
,re-try now : Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:27.688 ThaliTest[879:644015] jxcore: disconnect
2015-11-19 10:50:27.689 ThaliTest[879:644015] jxcore: disconnect: fail
Connect (retry count 3) to peer Apple-Iphone6-1_PT4558.76EyUA== with availability status: true
do connect now
,2015-11-19 10:50:27.690 ThaliTest[879:644015] jxcore: connect Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:27.691 ThaliTest[879:644015] client session: connect
2015-11-19 10:50:27.692 ThaliTest[879:644015] client session: stateChange:0->1 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:28.634 ThaliTest[879:643824] multipeer session: reset timer
2015-11-19 10:50:28.635 ThaliTest[879:643824] multipeer session: stop timer
2015-11-19 10:50:28.636 ThaliTest[879:643824] multipeer session: start timer: 0x18fbe270
2015-11-19 ,10:50:28.637 ThaliTest[879:643824] server: disconnecting to refresh session (Apple-Iphone6-1_PT4558)
2015-11-19 10:50:28.637 ThaliTest[879:643824] server session: disconnect
2015-11-19 10:50:28.638 ThaliTest[879:643824] server session: stateChange:2->0 A,pple-Iphone6-1_PT4558
2015-11-19 10:50:28.641 ThaliTest[879:643824] server session: connect
2015-11-19 10:50:28.641 ThaliTest[879:643824] server session: stateChange:0->1 Apple-Iphone6-1_PT4558
TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:50:28.654 ThaliTest[879:643824] server: accepting invitation Apple-Iphone6-1_PT4558
,2015-11-19 10:50:30.800 ThaliTest[879:645269] client session: connected
2015-11-19 10:50:30.801 ThaliTest[879:645269] client session: stateChange:1->2 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:30.809 ThaliTest[879:645273] client session: fireConnectCallback: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:30.810 ThaliTest[879:645273] jxcore: connect: success
CLIENT connected to 55232, error: null
CLIENT starting client 
,2015-11-19 10:50:30.817 ThaliTest[879:643824] client: relay established
2015-11-19 10:50:30.818 ThaliTest[879:643824] client: new accepted socket: 0x18fbd7e0
2015-11-19 10:50:30.818 ThaliTest[879:645273] server session: connected
2015-11-19 10:50:30.819 ThaliTest[879:645273] server session: stateChange:1->2 Apple-Iphone6-1_PT4558
,2015-11-19 10:50:30.828 ThaliTest[879:643824] server relay: connected (to port: 55207)
TCP/IP server connected
CLIENT now sending 970000 bytes of data
,TCP/IP server has received 131072 bytes of data
,TCP/IP server has received 262144 bytes of data
,TCP/IP server has received 393216 bytes of data
,TCP/IP server has received 524288 bytes of data
,TCP/IP server has received 655360 bytes of data
,TCP/IP server has received 786432 bytes of data
,TCP/IP server has received 860002 bytes of data
,CLIENT is data received : 30000
,CLIENT is data received : 40000
,CLIENT is data received : 50000
,CLIENT is data received : 60000
,CLIENT is data received : 60000
,2015-11-19 10:50:41.270 ThaliTest[879:645280] server session: not connected Apple-Iphone6-1_PT4558
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:50:41.987 ThaliTest[879:643824] client: socket closed
----------------- closeClientSocket
2015-11-19 10:50:41.988 ThaliTest[879:643824] client relay: socket disconnected
CLIENT is closed
,2015-11-19 10:50:41.989 ThaliTest[879:643824] client relay: 0x18fbd7e0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x14ef4f10 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-,19 10:50:41.989 ThaliTest[879:643824] client session: socket closed: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:41.990 ThaliTest[879:643824] client session: onLinkFailure: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:41.990 ThaliTest[879:643824] client session: disconnect
2015-11-19 10:50:41.991 ThaliTest[879:643824] client session: stateChange:2->0 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:41.993 ThaliTest[879:643824] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4558.76EyUA==
,re-try now : Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:51.722 ThaliTest[879:643824] multipeer session: reset timer
2015-11-19 10:50:51.723 ThaliTest[879:643824] multipeer session: stop timer
2015-11-19 10:50:51.724 ThaliTest[879:643824] multipeer session: start timer: 0x18fbe270
2015-11-19 ,10:50:51.725 ThaliTest[879:643824] server: disconnecting to refresh session (Apple-Iphone6-1_PT4558)
2015-11-19 10:50:51.725 ThaliTest[879:643824] server session: disconnect
2015-11-19 10:50:51.726 ThaliTest[879:643824] server session: stateChange:2->0 Apple-Iphone6-1_PT4558
,2015-11-19 10:50:51.731 ThaliTest[879:643824] server session: connect
2015-11-19 10:50:51.732 ThaliTest[879:643824] server session: stateChange:0->1 Apple-Iphone6-1_PT4558
TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:50:51.742 ThaliTest[879:643824] server: accepting invitation Apple-Iphone6-1_PT4558
,2015-11-19 10:50:51.995 ThaliTest[879:644015] jxcore: disconnect
2015-11-19 10:50:51.996 ThaliTest[879:644015] jxcore: disconnect: fail
Connect (retry count 4) to peer Apple-Iphone6-1_PT4558.76EyUA== with availability status: true
do connect now
,2015-11-19 10:50:51.998 ThaliTest[879:644015] jxcore: connect Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:52.000 ThaliTest[879:644015] client session: connect
2015-11-19 10:50:52.000 ThaliTest[879:644015] client session: stateChange:0->1 Apple-Iphon,e6-1_PT4558.76EyUA==
,2015-11-19 10:50:53.909 ThaliTest[879:645455] server session: connected
2015-11-19 10:50:53.910 ThaliTest[879:645455] server session: stateChange:1->2 Apple-Iphone6-1_PT4558
,2015-11-19 10:50:53.918 ThaliTest[879:643824] server relay: connected (to port: 55207)
TCP/IP server connected
,2015-11-19 10:50:54.280 ThaliTest[879:645266] client session: connected
2015-11-19 10:50:54.281 ThaliTest[879:645266] client session: stateChange:1->2 Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:54.284 ThaliTest[879:645266] client session: fireConne,ctCallback: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:54.285 ThaliTest[879:645266] jxcore: connect: success
CLIENT connected to 55240, error: null
,CLIENT starting client 
,2015-11-19 10:50:54.293 ThaliTest[879:643824] client: relay established
2015-11-19 10:50:54.293 ThaliTest[879:643824] client: new accepted socket: 0x18fbd7e0
,CLIENT now sending 940000 bytes of data
,TCP/IP server has received 131072 bytes of data
,TCP/IP server has received 262144 bytes of data
,TCP/IP server has received 393216 bytes of data
,TCP/IP server has received 524288 bytes of data
TCP/IP server has received 655360 bytes of data
,TCP/IP server has received 786432 bytes of data
,TCP/IP server has received 860002 bytes of data
,CLIENT is data received : 60000
,CLIENT is data received : 70000
,CLIENT is data received : 80000
,CLIENT is data received : 90000
,CLIENT is data received : 100000
,CLIENT is data received : 100000
,2015-11-19 10:51:04.744 ThaliTest[879:645455] server session: not connected Apple-Iphone6-1_PT4558
,Receiving data timeout now
,CLIENT closeClientSocket
,2015-11-19 10:51:05.795 ThaliTest[879:643824] client: socket closed
2015-11-19 10:51:05.795 ThaliTest[879:643824] client relay: socket disconnected
CLIENT Stop now
Stop data retrieving timer
2015-11-19 10:51:05.796 ThaliTest[879:643824] client relay: 0,x18fbd7e0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18c1b330 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:51:05.797 ThaliTest[879:643824] client session: socket ,closed: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:51:05.797 ThaliTest[879:643824] client session: onLinkFailure: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:51:05.798 ThaliTest[879:643824] client session: disconnect
2015-11-19 10:51:05.798 ThaliTe,st[879:643824] client session: stateChange:2->0 Apple-Iphone6-1_PT4558.76EyUA==
CLIENT Stop now
2015-11-19 10:51:05.804 ThaliTest[879:643824] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4558.76EyUA==
---- round done--------
device[2]: Apple-IpadAir2-1_PT6621.ucYn4g==
,----------------- closeClientSocket
CLIENT is closed
,2015-11-19 10:51:10.810 ThaliTest[879:644015] jxcore: disconnect
,2015-11-19 10:51:10.811 ThaliTest[879:644015] jxcore: disconnect: fail
,Connect (retry count 0) to peer Apple-IpadAir2-1_PT6621.ucYn4g== with availability status: true
do connect now
,2015-11-19 10:51:10.815 ThaliTest[879:644015] jxcore: connect Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:10.816 ThaliTest[879:644015] client session: connect
2015-11-19 10:51:10.817 ThaliTest[879:644015] client session: stateChange:0->1 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:13.676 ThaliTest[879:645454] client session: connected
2015-11-19 10:51:13.677 ThaliTest[879:645454] client session: stateChange:1->2 Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:13.680 ThaliTest[879:645454] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:13.681 ThaliTest[879:645454] jxcore: connect: success
CLIENT connected to 55243, error: null
CLIENT starting client 
,2015-11-19 10:51:13.688 ThaliTest[879:643824] client: relay established
2015-11-19 10:51:13.688 ThaliTest[879:643824] client: new accepted socket: 0x18f8c430
,CLIENT now sending 1000000 bytes of data
,2015-11-19 10:51:13.908 ThaliTest[879:643824] multipeer session: reset timer
2015-11-19 10:51:13.908 ThaliTest[879:643824] multipeer session: stop timer
2015-11-19 10:51:13.908 ThaliTest[879:643824] multipeer session: start timer: 0x18fbe270
2015-11-19 ,10:51:13.909 ThaliTest[879:643824] server session: connect
2015-11-19 10:51:13.909 ThaliTest[879:643824] server session: stateChange:0->1 Apple-IpadAir2-1_PT6621
,2015-11-19 10:51:13.913 ThaliTest[879:643824] server: accepting invitation Apple-IpadAir2-1_PT6621
,CLIENT is data received : 0
,CLIENT is data received : 0
,CLIENT is data received : 0
,CLIENT is data received : 10000
,2015-11-19 10:51:16.774 ThaliTest[879:645454] server session: connected
2015-11-19 10:51:16.775 ThaliTest[879:645454] server session: stateChange:1->2 Apple-IpadAir2-1_PT6621
,TCP/IP server connected
2015-11-19 10:51:16.782 ThaliTest[879:643824] server relay: connected (to port: 55207)
,TCP/IP server has received 6570 bytes of data
,TCP/IP server has received 28044 bytes of data
,TCP/IP server has received 48180 bytes of data
,TCP/IP server has received 65700 bytes of data
,TCP/IP server has received 81030 bytes of data
,TCP/IP server has received 96360 bytes of data
,TCP/IP server has received 113880 bytes of data
,TCP/IP server has received 133590 bytes of data
,TCP/IP server has received 157680 bytes of data
,TCP/IP server has received 175200 bytes of data
,TCP/IP server has received 201480 bytes of data
,TCP/IP server has received 225570 bytes of data
,TCP/IP server has received 243090 bytes of data
,TCP/IP server has received 258420 bytes of data
,TCP/IP server has received 280320 bytes of data
,TCP/IP server has received 315360 bytes of data
,TCP/IP server has received 348210 bytes of data
,TCP/IP server has received 381060 bytes of data
,TCP/IP server has received 409530 bytes of data
,TCP/IP server has received 451140 bytes of data
,TCP/IP server has received 473040 bytes of data
,TCP/IP server has received 510270 bytes of data
,TCP/IP server has received 560640 bytes of data
,TCP/IP server has received 606630 bytes of data
,TCP/IP server has received 674520 bytes of data
,TCP/IP server has received 707370 bytes of data
,TCP/IP server has received 711750 bytes of data
,TCP/IP server has received 727080 bytes of data
,TCP/IP server has received 741842 bytes of data
,TCP/IP server has received 770880 bytes of data
,TCP/IP server has received 801540 bytes of data
,TCP/IP server has received 838770 bytes of data
,TCP/IP server has received 865050 bytes of data
,TCP/IP server has received 900090 bytes of data
,TCP/IP server has received 930750 bytes of data
,TCP/IP server has received 959220 bytes of data
,TCP/IP server has received 985500 bytes of data
,TCP/IP server has received 1000002 bytes of data
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:51:24.445 ThaliTest[879:643824] client: socket closed
----------------- closeClientSocket
2015-11-19 10:51:24.445 ThaliTest[879:643824] client relay: socket disconnected
CLIENT is closed
2015-11-19 10:51:24.446 Th,aliTest[879:643824] client relay: 0x18f8c430 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1896c500 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:51:24.447 ThaliTest[879:643824] client session: socket closed: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:24.447 ThaliTest[879:643824] client session: onLinkFailure: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:24.448 ThaliTest[,879:643824] client session: disconnect
,2015-11-19 10:51:24.448 ThaliTest[879:643824] client session: stateChange:2->0 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:24.450 ThaliTest[879:643824] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:28.268 ThaliTest[879:643824] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:51:28.334 ThaliTest[879:645454] server session: not connected Apple-IpadAir2-1_PT6621
,re-try now : Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:30.367 ThaliTest[879:643824] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:51:34.470 ThaliTest[879:644015] jxcore: disconnect
2015-11-19 10:51:34.471 ThaliTest[879:644015] jxcore: disconnect: fail
Connect (retry count 1) to peer Apple-IpadAir2-1_PT6621.ucYn4g== with availability status: true
do connect now
,2015-11-19 10:51:34.473 ThaliTest[879:644015] jxcore: connect Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:34.475 ThaliTest[879:644015] client session: connect
2015-11-19 10:51:34.476 ThaliTest[879:644015] client session: stateChange:0->1 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:34.644 ThaliTest[879:643824] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:51:37.221 ThaliTest[879:645501] client session: connected
2015-11-19 10:51:37.222 ThaliTest[879:645501] client session: stateChange:1->2 Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:37.225 ThaliTest[879:645501] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:37.226 ThaliTest[879:645501] jxcore: connect: success
CLIENT connected to 55247, error: null
CLIENT starting client 
2015-11-19 10:51:37.231 ThaliTest[879:643824] client: relay established,
2015-11-19 10:51:37.232 ThaliTest[879:643824] client: new accepted socket: 0x14d74670
,CLIENT now sending 990000 bytes of data
,CLIENT is data received : 10000
,CLIENT is data received : 10000
,CLIENT is data received : 10000
,CLIENT is data received : 20000
,CLIENT is data received : 30000
,CLIENT is data received : 40000
,CLIENT is data received : 50000
,2015-11-19 10:51:38.234 ThaliTest[879:643824] multipeer session: reset timer
2015-11-19 10:51:38.235 ThaliTest[879:643824] multipeer session: stop timer
2015-11-19 10:51:38.235 ThaliTest[879:643824] multipeer session: start timer: 0x18fbe270
2015-11-19 ,10:51:38.235 ThaliTest[879:643824] server: disconnecting to refresh session (Apple-IpadAir2-1_PT6621)
2015-11-19 10:51:38.235 ThaliTest[879:643824] server session: disconnect
2015-11-19 10:51:38.235 ThaliTest[879:643824] server session: stateChange:2->0 Apple-IpadAir2-1_PT6621
TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:51:38.292 ThaliTest[879:643824] server session: connect
2015-11-19 10:51:38.293 ThaliTest[879:643824] server session: stateChange:0->1 Apple-IpadAir2-1_PT6621
,2015-11-19 10:51:38.295 ThaliTest[879:643824] server: accepting invitation Apple-IpadAir2-1_PT6621
,2015-11-19 10:51:40.922 ThaliTest[879:645501] server session: connected
2015-11-19 10:51:40.923 ThaliTest[879:645501] server session: stateChange:1->2 Apple-IpadAir2-1_PT6621
,2015-11-19 10:51:40.930 ThaliTest[879:643824] server relay: connected (to port: 55207)
,TCP/IP server connected
,TCP/IP server has received 6570 bytes of data
,TCP/IP server has received 10950 bytes of data
,TCP/IP server has received 32850 bytes of data
,TCP/IP server has received 52560 bytes of data
,TCP/IP server has received 76650 bytes of data
,TCP/IP server has received 98550 bytes of data
,TCP/IP server has received 120450 bytes of data
,TCP/IP server has received 142350 bytes of data
,TCP/IP server has received 170820 bytes of data
,TCP/IP server has received 194910 bytes of data
,TCP/IP server has received 227760 bytes of data
,TCP/IP server has received 249660 bytes of data
,TCP/IP server has received 271560 bytes of data
,TCP/IP server has received 293460 bytes of data
,TCP/IP server has received 321930 bytes of data
,TCP/IP server has received 361350 bytes of data
,TCP/IP server has received 385440 bytes of data
,TCP/IP server has received 411720 bytes of data
,TCP/IP server has received 440190 bytes of data
,TCP/IP server has received 475230 bytes of data
,TCP/IP server has received 508080 bytes of data
,TCP/IP server has received 536550 bytes of data
,TCP/IP server has received 584588 bytes of data
,TCP/IP server has received 619770 bytes of data
,TCP/IP server has received 659190 bytes of data
,TCP/IP server has received 700800 bytes of data
,TCP/IP server has received 748980 bytes of data
,TCP/IP server has received 784020 bytes of data
,TCP/IP server has received 838770 bytes of data
,TCP/IP server has received 884760 bytes of data
,TCP/IP server has received 900002 bytes of data
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
----------------- closeClientSocket
2015-11-19 10:51:47.950 ThaliTest[879:643824] client: socket closed
CLIENT is closed
2015-11-19 10:51:47.951 ThaliTest[879:643824] client relay: socket disconnected
,2015-11-19 10:51:47.953 ThaliTest[879:643824] client relay: 0x14d74670 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18a4da70 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-,19 10:51:47.953 ThaliTest[879:643824] client session: socket closed: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:47.954 ThaliTest[879:643824] client session: onLinkFailure: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:51:47.954 ThaliTest[879:6438,24] client session: disconnect
2015-11-19 10:51:47.955 ThaliTest[879:643824] client session: stateChange:2->0 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:47.957 ThaliTest[879:643824] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:51.920 ThaliTest[879:645564] server session: not connected Apple-IpadAir2-1_PT6621
,re-try now : Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:57.960 ThaliTest[879:644015] jxcore: disconnect
2015-11-19 10:51:57.961 ThaliTest[879:644015] jxcore: disconnect: fail
Connect (retry count 2) to peer Apple-IpadAir2-1_PT6621.ucYn4g== with availability status: true
do connect now
,2015-11-19 10:51:57.962 ThaliTest[879:644015] jxcore: connect Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:51:57.963 ThaliTest[879:644015] client session: connect
,2015-11-19 10:51:57.964 ThaliTest[879:644015] client session: stateChange:0->1 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:00.849 ThaliTest[879:645528] client session: connected
2015-11-19 10:52:00.850 ThaliTest[879:645528] client session: stateChange:1->2 Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:00.855 ThaliTest[879:645528] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:00.856 ThaliTest[879:645528] jxcore: connect: success
,CLIENT connected to 55251, error: null
CLIENT starting client 
,2015-11-19 10:52:00.863 ThaliTest[879:643824] client: relay established
2015-11-19 10:52:00.864 ThaliTest[879:643824] client: new accepted socket: 0x18ec3e40
,CLIENT now sending 950000 bytes of data
,CLIENT is data received : 50000
,CLIENT is data received : 50000
,CLIENT is data received : 60000
,CLIENT is data received : 70000
,CLIENT is data received : 80000
,2015-11-19 10:52:01.911 ThaliTest[879:643824] multipeer session: reset timer
2015-11-19 10:52:01.912 ThaliTest[879:643824] multipeer session: stop timer
2015-11-19 10:52:01.912 ThaliTest[879:643824] multipeer session: start timer: 0x18fbe270
2015-11-19 ,10:52:01.913 ThaliTest[879:643824] server: disconnecting to refresh session (Apple-IpadAir2-1_PT6621)
2015-11-19 10:52:01.913 ThaliTest[879:643824] server session: disconnect
2015-11-19 10:52:01.913 ThaliTest[879:643824] server session: stateChange:2->0 ,Apple-IpadAir2-1_PT6621
2015-11-19 10:52:01.915 ThaliTest[879:643824] server session: connect
2015-11-19 10:52:01.916 ThaliTest[879:643824] server session: stateChange:0->1 Apple-IpadAir2-1_PT6621
,TCP/IP server is ended
TCP/IP server is close
2015-11-19 10:52:01.930 ThaliTest[879:643824] server: accepting invitation Apple-IpadAir2-1_PT6621
,2015-11-19 10:52:04.502 ThaliTest[879:645571] server session: connected
2015-11-19 10:52:04.503 ThaliTest[879:645571] server session: stateChange:1->2 Apple-IpadAir2-1_PT6621
,2015-11-19 10:52:04.512 ThaliTest[879:643824] server relay: connected (to port: 55207)
TCP/IP server connected
,TCP/IP server has received 8618 bytes of data
,TCP/IP server has received 28470 bytes of data
,TCP/IP server has received 67890 bytes of data
,TCP/IP server has received 85410 bytes of data
,TCP/IP server has received 91980 bytes of data
,TCP/IP server has received 105120 bytes of data
,TCP/IP server has received 127020 bytes of data
,TCP/IP server has received 146730 bytes of data
,TCP/IP server has received 164108 bytes of data
,TCP/IP server has received 194910 bytes of data
,TCP/IP server has received 212430 bytes of data
,TCP/IP server has received 245280 bytes of data
,TCP/IP server has received 264990 bytes of data
,TCP/IP server has received 289080 bytes of data
,TCP/IP server has received 306600 bytes of data
,TCP/IP server has received 326310 bytes of data
,TCP/IP server has received 354780 bytes of data
,TCP/IP server has received 398580 bytes of data
,TCP/IP server has received 427050 bytes of data
,TCP/IP server has received 459900 bytes of data
,TCP/IP server has received 488370 bytes of data
,TCP/IP server has received 529980 bytes of data
,TCP/IP server has received 565020 bytes of data
,TCP/IP server has received 600060 bytes of data
,TCP/IP server has received 646050 bytes of data
,TCP/IP server has received 687660 bytes of data
,TCP/IP server has received 735840 bytes of data
,TCP/IP server has received 781830 bytes of data
,TCP/IP server has received 827820 bytes of data
,TCP/IP server has received 860002 bytes of data
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:52:11.547 ThaliTest[879:643824] client: socket closed
----------------- closeClientSocket
2015-11-19 10:52:11.548 ThaliTest[879:643824] client relay: socket disconnected
CLIENT is closed
2015-11-19 10:52:11.549 Th,aliTest[879:643824] client relay: 0x18ec3e40 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18c51fe0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:52:11.549 ThaliTest[879:643824] client session: socket closed: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:11.550 ThaliTest[879:643824] client session: onLinkFailure: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:11.551 ThaliTest[,879:643824] client session: disconnect
,2015-11-19 10:52:11.551 ThaliTest[879:643824] client session: stateChange:2->0 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:11.553 ThaliTest[879:643824] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:15.515 ThaliTest[879:645564] server session: not connected Apple-IpadAir2-1_PT6621
,re-try now : Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:21.562 ThaliTest[879:644015] jxcore: disconnect
2015-11-19 10:52:21.563 ThaliTest[879:644015] jxcore: disconnect: fail
Connect (retry count 3) to peer Apple-IpadAir2-1_PT6621.ucYn4g== with availability status: true
do connect now
,2015-11-19 10:52:21.565 ThaliTest[879:644015] jxcore: connect Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:21.566 ThaliTest[879:644015] client session: connect
2015-11-19 10:52:21.567 ThaliTest[879:644015] client session: stateChange:0->1 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:24.425 ThaliTest[879:645571] client session: connected
2015-11-19 10:52:24.426 ThaliTest[879:645571] client session: stateChange:1->2 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:24.431 ThaliTest[879:645501] client session: fireConnectCallback: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:24.432 ThaliTest[879:645501] jxcore: connect: success
CLIENT connected to 55255, error: null
CLIENT starting client 
,2015-11-19 10:52:24.439 ThaliTest[879:643824] client: relay established
2015-11-19 10:52:24.439 ThaliTest[879:643824] client: new accepted socket: 0x1894b450
,CLIENT now sending 920000 bytes of data
,CLIENT is data received : 80000
,CLIENT is data received : 90000
,CLIENT is data received : 100000
,CLIENT is data received : 110000
,2015-11-19 10:52:25.475 ThaliTest[879:643824] multipeer session: reset timer
2015-11-19 10:52:25.476 ThaliTest[879:643824] multipeer session: stop timer
2015-11-19 10:52:25.476 ThaliTest[879:643824] multipeer session: start timer: 0x18fbe270
2015-11-19 ,10:52:25.476 ThaliTest[879:643824] server: disconnecting to refresh session (Apple-IpadAir2-1_PT6621)
2015-11-19 10:52:25.476 ThaliTest[879:643824] server session: disconnect
2015-11-19 10:52:25.476 ThaliTest[879:643824] server session: stateChange:2->0 Apple-IpadAir2-1_PT6621
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:52:25.533 ThaliTest[879:643824] server session: connect
2015-11-19 10:52:25.534 ThaliTest[879:643824] server session: stateChange:0->1 Apple-IpadAir2-1_PT6621
,2015-11-19 10:52:25.537 ThaliTest[879:643824] server: accepting invitation Apple-IpadAir2-1_PT6621
,2015-11-19 10:52:28.070 ThaliTest[879:645564] server session: connected
2015-11-19 10:52:28.071 ThaliTest[879:645564] server session: stateChange:1->2 Apple-IpadAir2-1_PT6621
,2015-11-19 10:52:28.076 ThaliTest[879:643824] server relay: connected (to port: 55207)
,TCP/IP server connected
,TCP/IP server has received 2190 bytes of data
,TCP/IP server has received 19710 bytes of data
,TCP/IP server has received 41610 bytes of data
,TCP/IP server has received 59130 bytes of data
,TCP/IP server has received 94170 bytes of data
,TCP/IP server has received 116070 bytes of data
,TCP/IP server has received 146730 bytes of data
,TCP/IP server has received 177390 bytes of data
,TCP/IP server has received 201480 bytes of data
,TCP/IP server has received 219000 bytes of data
,TCP/IP server has received 236520 bytes of data
,TCP/IP server has received 258420 bytes of data
,TCP/IP server has received 278130 bytes of data
,TCP/IP server has received 304410 bytes of data
,TCP/IP server has received 328358 bytes of data
,TCP/IP server has received 361208 bytes of data
,TCP/IP server has received 389820 bytes of data
,TCP/IP server has received 420480 bytes of data
,TCP/IP server has received 451140 bytes of data
,TCP/IP server has received 479610 bytes of data
,TCP/IP server has received 512460 bytes of data
,TCP/IP server has received 556260 bytes of data
,TCP/IP server has received 608110 bytes of data
,TCP/IP server has received 674520 bytes of data
,TCP/IP server has received 689850 bytes of data
,TCP/IP server has received 694230 bytes of data
,TCP/IP server has received 711750 bytes of data
,TCP/IP server has received 718320 bytes of data
,TCP/IP server has received 742410 bytes of data
,TCP/IP server has received 762120 bytes of data
,TCP/IP server has received 797160 bytes of data
,TCP/IP server has received 800002 bytes of data
,2015-11-19 10:52:30.749 ThaliTest[879:643824] client: lost peer: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:52:30.750 ThaliTest[879:643824] client session: onPeerLost: Apple-Iphone6-1_PT4558.76EyUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:52:31.299 ThaliTest[879:643824] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":true}]
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,----------------- closeClientSocket
2015-11-19 10:52:35.096 ThaliTest[879:643824] client: socket closed
2015-11-19 10:52:35.096 ThaliTest[879:643824] client relay: socket disconnected
CLIENT is closed
2015-11-19 10:52:35.097 ThaliTest[879:643824] clien,t relay: 0x1894b450 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x14e71940 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:52:35.098 ThaliTest[879:643824] client session: socket closed: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:35.098 ThaliTest[879:643824] client session: onLinkFailure: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:35.099 ThaliTest[879:643824] client session: disconnect
,2015-11-19 10:52:35.100 ThaliTest[879:643824] client session: stateChange:2->0 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:35.102 ThaliTest[879:643824] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:39.201 ThaliTest[879:645651] server session: not connected Apple-IpadAir2-1_PT6621
,2015-11-19 10:52:39.210 ThaliTest[879:643824] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
,re-try now : Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:45.108 ThaliTest[879:644015] jxcore: disconnect
2015-11-19 10:52:45.108 ThaliTest[879:644015] jxcore: disconnect: fail
Connect (retry count 4) to peer Apple-IpadAir2-1_PT6621.ucYn4g== with availability status: true
do connect now
,2015-11-19 10:52:45.110 ThaliTest[879:644015] jxcore: connect Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:45.111 ThaliTest[879:644015] client session: connect
,2015-11-19 10:52:45.112 ThaliTest[879:644015] client session: stateChange:0->1 Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:48.099 ThaliTest[879:645501] client session: connected
2015-11-19 10:52:48.100 ThaliTest[879:645501] client session: stateChange:1->2 Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:48.104 ThaliTest[879:645501] client session: fireConnectCallback: Apple-IpadAir2-1_PT6621.ucYn4g==
,2015-11-19 10:52:48.105 ThaliTest[879:645501] jxcore: connect: success
,CLIENT connected to 55259, error: null
CLIENT starting client 
,2015-11-19 10:52:48.112 ThaliTest[879:643824] client: relay established
,2015-11-19 10:52:48.113 ThaliTest[879:643824] client: new accepted socket: 0x18bb9210
,CLIENT now sending 890000 bytes of data
,CLIENT is data received : 110000
,CLIENT is data received : 120000
,CLIENT is data received : 130000
,CLIENT is data received : 140000
,2015-11-19 10:52:49.330 ThaliTest[879:643824] multipeer session: reset timer
2015-11-19 10:52:49.330 ThaliTest[879:643824] multipeer session: stop timer
2015-11-19 10:52:49.331 ThaliTest[879:643824] multipeer session: start timer: 0x18fbe270
2015-11-19 ,10:52:49.332 ThaliTest[879:643824] server: disconnecting to refresh session (Apple-IpadAir2-1_PT6621)
2015-11-19 10:52:49.332 ThaliTest[879:643824] server session: disconnect
2015-11-19 10:52:49.333 ThaliTest[879:643824] server session: stateChange:2->0 ,Apple-IpadAir2-1_PT6621
2015-11-19 10:52:49.338 ThaliTest[879:643824] server session: connect
2015-11-19 10:52:49.340 ThaliTest[879:643824] server session: stateChange:0->1 Apple-IpadAir2-1_PT6621
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:52:49.358 ThaliTest[879:643824] server: accepting invitation Apple-IpadAir2-1_PT6621
,2015-11-19 10:52:51.849 ThaliTest[879:645653] server session: connected
2015-11-19 10:52:51.850 ThaliTest[879:645653] server session: stateChange:1->2 Apple-IpadAir2-1_PT6621
,2015-11-19 10:52:51.856 ThaliTest[879:643824] server relay: connected (to port: 55207)
TCP/IP server connected
,TCP/IP server has received 19710 bytes of data
,TCP/IP server has received 54182 bytes of data
,TCP/IP server has received 72270 bytes of data
,TCP/IP server has received 96360 bytes of data
,TCP/IP server has received 111690 bytes of data
,TCP/IP server has received 131400 bytes of data
,TCP/IP server has received 159870 bytes of data
,TCP/IP server has received 183818 bytes of data
,TCP/IP server has received 208050 bytes of data
,TCP/IP server has received 234330 bytes of data
,TCP/IP server has received 256230 bytes of data
,TCP/IP server has received 284700 bytes of data
,TCP/IP server has received 317550 bytes of data
,TCP/IP server has received 352590 bytes of data
,TCP/IP server has received 383250 bytes of data
,TCP/IP server has received 407340 bytes of data
,TCP/IP server has received 438000 bytes of data
,TCP/IP server has received 477420 bytes of data
,TCP/IP server has received 505890 bytes of data
,TCP/IP server has received 540930 bytes of data
,TCP/IP server has received 575970 bytes of data
,TCP/IP server has received 619628 bytes of data
,TCP/IP server has received 674520 bytes of data
,TCP/IP server has received 720002 bytes of data
,Receiving data timeout now
,CLIENT closeClientSocket
,CLIENT Stop now
Stop data retrieving timer
2015-11-19 10:52:58.755 ThaliTest[879:643824] client: socket closed
2015-11-19 10:52:58.756 ThaliTest[879:643824] client relay: socket disconnected
2015-11-19 10:52:58.757 ThaliTest[879:643824] client relay: 0,x18bb9210 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18d268b0 {NSLocalizedDescription=Socket closed by remote peer} 
CLIENT Stop now
2015-11-19 10:52:58.757 ThaliTest[879:643824] client, session: socket closed: Apple-IpadAir2-1_PT6621.ucYn4g==
---- round done--------
2015-11-19 10:52:58.758 ThaliTest[879:643824] client session: onLinkFailure: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:52:58.758 ThaliTest[879:643824] client session:, disconnect
weAreDoneNow , resultArray.length: 2
2015-11-19 10:52:58.759 ThaliTest[879:643824] client session: stateChange:2->0 Apple-IpadAir2-1_PT6621.ucYn4g==
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,2015-11-19 10:52:58.767 ThaliTest[879:643824] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT6621.ucYn4g==
-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT9462","time":230390,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT4558.76EyUA==","t,ime":116876,"result":"DATA-TIMEOUT","connections":5},{"name":"Apple-IpadAir2-1_PT6621.ucYn4g==","time":112948,"result":"DATA-TIMEOUT","connections":5}]}
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results li,st does not contain any items
sendList failed peers count : 2 [100 %]
- Peer ID : Apple-Iphone6-1_PT4558.76EyUA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6621.ucYn4g==, Tried : 5
sendList never tried peers count : 0 [0 %]
CLIENT Stop now
----------,------- closeClientSocket
CLIENT is closed
,2015-11-19 10:53:02.682 ThaliTest[879:645701] server session: not connected Apple-IpadAir2-1_PT6621
,2015-11-19 10:53:09.092 ThaliTest[879:643824] client: lost peer: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:53:09.093 ThaliTest[879:643824] client session: onPeerLost: Apple-Iphone6-1_PT4558.76EyUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:53:09.961 ThaliTest[879:643824] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:53:19.333 ThaliTest[879:643824] multipeer session: restart
,2015-11-19 10:53:19.355 ThaliTest[879:643824] client: found peer: Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:53:19.356 ThaliTest[879:643824] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:53:19.548 ThaliTest[879:643824] client: lost peer: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:53:19.549 ThaliTest[879:643824] client session: onPeerLost: Apple-Iphone6-1_PT4558.76EyUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-19 10:53:19.747 ThaliTest[879:644015] jxcore: stopBroadcasting
,2015-11-19 10:53:19.749 ThaliTest[879:644015] THEMultipeerSession stopping peer
,2015-11-19 10:53:19.749 ThaliTest[879:644015] multipeer session: stop timer
2015-11-19 10:53:19.751 ThaliTest[879:644015] server session: disconnect
2015-11-19 10:53:19.751 ThaliTest[879:644015] server session: stateChange:2->0 Apple-IpadAir2-1_PT6621
,2015-11-19 10:53:19.760 ThaliTest[879:644015] server session: disconnect
2015-11-19 10:53:19.763 ThaliTest[879:644015] server session: stateChange:2->0 Apple-Iphone6-1_PT4558
,2015-11-19 10:53:19.768 ThaliTest[879:644015] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,TCP/IP server is ended
,TCP/IP server is ended
,TCP/IP server  socket is disconnected
,TCP/IP server is close
TCP/IP server is close
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone6-1_PT4558.76EyUA==\",\"time\":116876,\"result\":\"DATA-TIMEOUT\",\"connections\":5},{\"name\":\"Apple-,IpadAir2-1_PT6621.ucYn4g==\",\"time\":112948,\"result\":\"DATA-TIMEOUT\",\"connections\":5}],\"notTriedList\":[]}},\"combined\":{\"sendList\":[]}}","devices":3,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
