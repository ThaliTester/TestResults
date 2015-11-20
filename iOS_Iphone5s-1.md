#### Test 5133502893bec48_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502893bec48/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1FE920F1-6ABA-44CF-855C-417EB9774614/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1FE920F1-6ABA-44CF-855C-417EB9774614/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502893bec48/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502893bec48/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/447D2C94-8994-407B-8F37-9C9FC3143B81/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50774"
,(lldb)     command script import "/tmp/1FE920F1-6ABA-44CF-855C-417EB9774614/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 10:49:58.668 ThaliTest[960:758717] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DBDF0FE9-7B4A-42C6-8954-CC6E2F49908B/Library/Cookies/Cookies.binarycookies
,2015-11-20 10:49:59.072 ThaliTest[960:758717] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 10:49:59.072 ThaliTest[960:758717] Multi-tasking -> Device: YES, App: YES
,2015-11-20 10:49:59.081 ThaliTest[960:758717] Unlimited access to network resources
,2015-11-20 10:49:59.086 ThaliTest[960:758717] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 10:50:02.312 ThaliTest[960:758717] Resetting plugins due to page load.
,2015-11-20 10:50:02.741 ThaliTest[960:758717] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/447D2C94-8994-407B-8F37-9C9FC3143B81/ThaliTest.app/www/index.html
,2015-11-20 10:50:02.885 ThaliTest[960:758717] JXcore Cordova plugin initializing
,2015-11-20 10:50:02.887 ThaliTest[960:758847] JXcore instance initializing
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
toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,my name is : Apple-Iphone5s-1_PT4118
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
printNetworkInfo
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
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
-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
printNetworkInfo
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
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c23:38ff:fe26:9405
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":1,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 55499
,2015-11-20 10:59:40.832 ThaliTest[960:758847] jxcore: startBroadcasting
,2015-11-20 10:59:40.846 ThaliTest[960:758847] server: starting Apple-Iphone5s-1_PT4118.XhZL4Q==
,2015-11-20 10:59:40.847 ThaliTest[960:758847] multipeer session: start timer: 0x18ee09f0
2015-11-20 10:59:40.848 ThaliTest[960:758847] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT4118
2015-11-20 10:59:40.849 ThaliTest[960:758847] jxcore: startBroadcasting: success
StartBroadcasting started ok
,TCP/IP server  is bound to : undefined
,2015-11-20 10:59:43.975 ThaliTest[960:758717] client: found peer: Apple-Iphone6-1_PT9036.Dzps4Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9036.Dzps4Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 10:59:48.805 ThaliTest[960:758717] multipeer session: reset timer
2015-11-20 10:59:48.806 ThaliTest[960:758717] multipeer session: stop timer
2015-11-20 10:59:48.807 ThaliTest[960:758717] multipeer session: start timer: 0x18ee09f0
2015-11-20 ,10:59:48.808 ThaliTest[960:758717] server session: connect
2015-11-20 10:59:48.808 ThaliTest[960:758717] server session: stateChange:0->1 Apple-Iphone6-1_PT9036
,2015-11-20 10:59:48.823 ThaliTest[960:758717] server: accepting invitation Apple-Iphone6-1_PT9036
,2015-11-20 10:59:48.996 ThaliTest[960:758847] jxcore: disconnect
2015-11-20 10:59:48.997 ThaliTest[960:758847] jxcore: disconnect: fail
SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone6-1_PT9036.Dzps4Q== with availability status: true
,SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: do connect now
,2015-11-20 10:59:49.001 ThaliTest[960:758847] jxcore: connect Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 10:59:49.002 ThaliTest[960:758847] client session: connect
2015-11-20 10:59:49.002 ThaliTest[960:758847] client session: stateChange:0->1 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 10:59:51.367 ThaliTest[960:759696] server session: connected
2015-11-20 10:59:51.368 ThaliTest[960:759696] server session: stateChange:1->2 Apple-Iphone6-1_PT9036
,2015-11-20 10:59:51.376 ThaliTest[960:758717] server relay: connected (to port: 55499)
TCP/IP server connected
,TCP/IP server has received 4380 bytes of data
,2015-11-20 10:59:51.502 ThaliTest[960:759696] client session: connected
2015-11-20 10:59:51.504 ThaliTest[960:759696] client session: stateChange:1->2 Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 10:59:51.506 ThaliTest[960:759696] client session: fireConne,ctCallback: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 10:59:51.507 ThaliTest[960:759696] jxcore: connect: success
TCP/IP server has received 24090 bytes of data
,SendDataConnector.js: CLIENT connected to 55504, error: null
,SendDataConnector.js: CLIENT starting client 
,2015-11-20 10:59:51.518 ThaliTest[960:758717] client: relay established
2015-11-20 10:59:51.519 ThaliTest[960:758717] client: new accepted socket: 0x18f2e580
TCP/IP server has received 37230 bytes of data
SendDataConnector.js: CLIENT now sending 100000 bytes of data
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,TCP/IP server has received 100002 bytes of data
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: CLIENT is data received : 10000
,SendDataConnector.js: CLIENT is data received : 10000
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: CLIENT is data received : 20000
,SendDataConnector.js: Receiving data timeout now
,SendDataConnector.js: CLIENT closeClientSocket
,SendDataConnector.js: tryAgain afer: 5000 ms.
2015-11-20 11:00:01.915 ThaliTest[960:758717] client: socket closed
SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 11:00:01.916 ThaliTest[960:758717] client relay: socket disconnected
,2015-11-20 11:00:01.917 ThaliTest[960:758717] client relay: 0x18f2e580 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18d15e30 {NSLocalizedDescription=Socket closed by remote peer} 
SendData,Connector.js: CLIENT is closed
2015-11-20 11:00:01.917 ThaliTest[960:758717] client session: socket closed: Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:01.918 ThaliTest[960:758717] client session: onLinkFailure: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:00:01.918 ThaliTest[960:758717] client session: disconnect
2015-11-20 11:00:01.919 ThaliTest[960:758717] client session: stateChang,e:2->0 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:01.922 ThaliTest[960:758717] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:01.935 ThaliTest[960:759739] server session: not connected Apple-Iphone6-1_PT9036
,SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:11.920 ThaliTest[960:758847] jxcore: disconnect
2015-11-20 11:00:11.921 ThaliTest[960:758847] jxcore: disconnect: fail
SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: Co,nnect (retry count 1) to peer Apple-Iphone6-1_PT9036.Dzps4Q== with availability status: true
,SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: do connect now
,2015-11-20 11:00:11.924 ThaliTest[960:758847] jxcore: connect Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:11.925 ThaliTest[960:758847] client session: connect
,2015-11-20 11:00:11.926 ThaliTest[960:758847] client session: stateChange:0->1 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:12.086 ThaliTest[960:758717] multipeer session: reset timer
2015-11-20 11:00:12.087 ThaliTest[960:758717] multipeer session: stop timer
2015-11-20 11:00:12.088 ThaliTest[960:758717] multipeer session: start timer: 0x18ee09f0
2015-11-20 ,11:00:12.088 ThaliTest[960:758717] server: disconnecting to refresh session (Apple-Iphone6-1_PT9036)
2015-11-20 11:00:12.089 ThaliTest[960:758717] server session: disconnect
2015-11-20 11:00:12.090 ThaliTest[960:758717] server session: stateChange:2->0 A,pple-Iphone6-1_PT9036
2015-11-20 11:00:12.093 ThaliTest[960:758717] server session: connect
2015-11-20 11:00:12.094 ThaliTest[960:758717] server session: stateChange:0->1 Apple-Iphone6-1_PT9036
TCP/IP server is ended
TCP/IP server is close
,2015-11-20 11:00:12.119 ThaliTest[960:758717] server: accepting invitation Apple-Iphone6-1_PT9036
,2015-11-20 11:00:14.312 ThaliTest[960:759761] server session: connected
2015-11-20 11:00:14.313 ThaliTest[960:759761] server session: stateChange:1->2 Apple-Iphone6-1_PT9036
,TCP/IP server connected
,2015-11-20 11:00:14.323 ThaliTest[960:758717] server relay: connected (to port: 55499)
,2015-11-20 11:00:14.358 ThaliTest[960:759758] client session: connected
,2015-11-20 11:00:14.361 ThaliTest[960:759758] client session: stateChange:1->2 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:14.365 ThaliTest[960:759758] client session: fireConnectCallback: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:00:14.366 ThaliTest[960:759758] jxcore: connect: success
,SendDataConnector.js: CLIENT connected to 55509, error: null
SendDataConnector.js: CLIENT starting client 
,2015-11-20 11:00:14.372 ThaliTest[960:758717] client: relay established
2015-11-20 11:00:14.373 ThaliTest[960:758717] client: new accepted socket: 0x18ef9a10
,SendDataConnector.js: CLIENT now sending 80000 bytes of data
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,TCP/IP server has received 8760 bytes of data
,TCP/IP server has received 15330 bytes of data
,TCP/IP server has received 52560 bytes of data
,TCP/IP server has received 67890 bytes of data
,SendDataConnector.js: CLIENT is data received : 20000
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: CLIENT is data received : 30000
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: CLIENT is data received : 40000
,TCP/IP server has received 80002 bytes of data
,SendDataConnector.js: Receiving data timeout now
,SendDataConnector.js: CLIENT closeClientSocket
,SendDataConnector.js: tryAgain afer: 5000 ms.
2015-11-20 11:00:24.524 ThaliTest[960:758717] client: socket closed
SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 11:00:24.525 ThaliTest[960:758717] client relay: socket disconnected
,SendDataConnector.js: CLIENT is closed
,2015-11-20 11:00:24.527 ThaliTest[960:758717] client relay: 0x18ef9a10 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18f2f730 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-,20 11:00:24.528 ThaliTest[960:758717] client session: socket closed: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:00:24.528 ThaliTest[960:758717] client session: onLinkFailure: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:00:24.529 ThaliTest[960:758717,] client session: disconnect
2015-11-20 11:00:24.529 ThaliTest[960:758717] client session: stateChange:2->0 Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:00:24.530 ThaliTest[960:758717] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:24.709 ThaliTest[960:759751] server session: not connected Apple-Iphone6-1_PT9036
,SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:34.545 ThaliTest[960:758847] jxcore: disconnect
2015-11-20 11:00:34.546 ThaliTest[960:758847] jxcore: disconnect: fail
SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: Co,nnect (retry count 2) to peer Apple-Iphone6-1_PT9036.Dzps4Q== with availability status: true
SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: do connect now
,2015-11-20 11:00:34.548 ThaliTest[960:758847] jxcore: connect Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:34.549 ThaliTest[960:758847] client session: connect
,2015-11-20 11:00:34.550 ThaliTest[960:758847] client session: stateChange:0->1 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:34.863 ThaliTest[960:758717] multipeer session: reset timer
2015-11-20 11:00:34.863 ThaliTest[960:758717] multipeer session: stop timer
2015-11-20 11:00:34.864 ThaliTest[960:758717] multipeer session: start timer: 0x18ee09f0
2015-11-20 ,11:00:34.865 ThaliTest[960:758717] server: disconnecting to refresh session (Apple-Iphone6-1_PT9036)
2015-11-20 11:00:34.866 ThaliTest[960:758717] server session: disconnect
2015-11-20 11:00:34.867 ThaliTest[960:758717] server session: stateChange:2->0 A,pple-Iphone6-1_PT9036
2015-11-20 11:00:34.874 ThaliTest[960:758717] server session: connect
2015-11-20 11:00:34.874 ThaliTest[960:758717] server session: stateChange:0->1 Apple-Iphone6-1_PT9036
,TCP/IP server is ended
TCP/IP server is close
2015-11-20 11:00:34.892 ThaliTest[960:758717] server: accepting invitation Apple-Iphone6-1_PT9036
,2015-11-20 11:00:36.928 ThaliTest[960:759825] client session: connected
,2015-11-20 11:00:36.930 ThaliTest[960:759825] client session: stateChange:1->2 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:36.932 ThaliTest[960:759825] client session: fireConnectCallback: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:00:36.932 ThaliTest[960:759825] jxcore: connect: success
,SendDataConnector.js: CLIENT connected to 55512, error: null
,SendDataConnector.js: CLIENT starting client 
,2015-11-20 11:00:36.941 ThaliTest[960:758717] client: relay established
2015-11-20 11:00:36.942 ThaliTest[960:758717] client: new accepted socket: 0x18ef5f40
,SendDataConnector.js: CLIENT now sending 60000 bytes of data
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: CLIENT is data received : 50000
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: CLIENT is data received : 60000
,2015-11-20 11:00:37.068 ThaliTest[960:759828] server session: connected
2015-11-20 11:00:37.068 ThaliTest[960:759828] server session: stateChange:1->2 Apple-Iphone6-1_PT9036
,2015-11-20 11:00:37.073 ThaliTest[960:758717] server relay: connected (to port: 55499)
,TCP/IP server connected
,SendDataConnector.js: CLIENT is data received : 60000
,TCP/IP server has received 2190 bytes of data
,TCP/IP server has received 41468 bytes of data
,TCP/IP server has received 50002 bytes of data
,SendDataConnector.js: Receiving data timeout now
,SendDataConnector.js: CLIENT closeClientSocket
,SendDataConnector.js: tryAgain afer: 5000 ms.
,SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20 11:00:47.079 ThaliTest[960:758717] client: socket closed
SendDataConnector.js: CLIENT is closed
2015-11-20 11:00:47.079 ThaliTest[960:758717] client relay: socket disconnected
2015-11-20 11:00:47.080 ThaliTest[960:758717] client relay: 0x18ef,5f40 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18ef7970 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 11:00:47.081 ThaliTest[960:758717] client session: socket close,d: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:00:47.081 ThaliTest[960:758717] client session: onLinkFailure: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:00:47.082 ThaliTest[960:758717] client session: disconnect
2015-11-20 11:00:47.082 ThaliTest[96,0:758717] client session: stateChange:2->0 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:47.085 ThaliTest[960:758717] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:47.252 ThaliTest[960:759816] server session: not connected Apple-Iphone6-1_PT9036
,SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:57.089 ThaliTest[960:758847] jxcore: disconnect
2015-11-20 11:00:57.090 ThaliTest[960:758847] jxcore: disconnect: fail
SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT9036.Dzps4Q== with availability status: true
,SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: do connect now
,2015-11-20 11:00:57.093 ThaliTest[960:758847] jxcore: connect Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:57.094 ThaliTest[960:758847] client session: connect
2015-11-20 11:00:57.095 ThaliTest[960:758847] client session: stateChange:0->1 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:57.396 ThaliTest[960:758717] multipeer session: reset timer
2015-11-20 11:00:57.396 ThaliTest[960:758717] multipeer session: stop timer
2015-11-20 11:00:57.398 ThaliTest[960:758717] multipeer session: start timer: 0x18ee09f0
2015-11-20 ,11:00:57.399 ThaliTest[960:758717] server: disconnecting to refresh session (Apple-Iphone6-1_PT9036)
2015-11-20 11:00:57.399 ThaliTest[960:758717] server session: disconnect
2015-11-20 11:00:57.400 ThaliTest[960:758717] server session: stateChange:2->0 A,pple-Iphone6-1_PT9036
2015-11-20 11:00:57.403 ThaliTest[960:758717] server session: connect
2015-11-20 11:00:57.404 ThaliTest[960:758717] server session: stateChange:0->1 Apple-Iphone6-1_PT9036
,TCP/IP server is ended
TCP/IP server is close
,2015-11-20 11:00:57.414 ThaliTest[960:758717] server: accepting invitation Apple-Iphone6-1_PT9036
,2015-11-20 11:00:59.530 ThaliTest[960:759869] client session: connected
2015-11-20 11:00:59.531 ThaliTest[960:759869] client session: stateChange:1->2 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:00:59.536 ThaliTest[960:759869] server session: connected
,2015-11-20 11:00:59.537 ThaliTest[960:759869] server session: stateChange:1->2 Apple-Iphone6-1_PT9036
,2015-11-20 11:00:59.544 ThaliTest[960:759877] client session: fireConnectCallback: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:00:59.545 ThaliTest[960:759877] jxcore: connect: success
,SendDataConnector.js: CLIENT connected to 55517, error: null
SendDataConnector.js: CLIENT starting client 
2015-11-20 11:00:59.552 ThaliTest[960:758717] server relay: connected (to port: 55499)
2015-11-20 11:00:59.556 ThaliTest[960:758717] client: relay, established
2015-11-20 11:00:59.556 ThaliTest[960:758717] client: new accepted socket: 0x18f3a630
,TCP/IP server connected
,SendDataConnector.js: CLIENT now sending 40000 bytes of data
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,TCP/IP server has received 20002 bytes of data
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: CLIENT is data received : 70000
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: CLIENT is data received : 80000
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: CLIENT is data received : 90000
,SendDataConnector.js: Receiving data timeout now
SendDataConnector.js: CLIENT closeClientSocket
,SendDataConnector.js: tryAgain afer: 5000 ms.
SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 11:01:09.671 ThaliTest[960:758717] client: socket closed
SendDataConnector.js: CLIENT is closed
2015-11-20 11:01:09.672 ThaliTest[960:758,717] client relay: socket disconnected
,2015-11-20 11:01:09.674 ThaliTest[960:758717] client relay: 0x18f3a630 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18ef1fb0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-,20 11:01:09.675 ThaliTest[960:758717] client session: socket closed: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:01:09.675 ThaliTest[960:758717] client session: onLinkFailure: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:01:09.676 ThaliTest[960:758717,] client session: disconnect
2015-11-20 11:01:09.676 ThaliTest[960:758717] client session: stateChange:2->0 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:01:09.679 ThaliTest[960:758717] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:01:09.958 ThaliTest[960:759869] server session: not connected Apple-Iphone6-1_PT9036
,SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:01:19.679 ThaliTest[960:758847] jxcore: disconnect
2015-11-20 11:01:19.679 ThaliTest[960:758847] jxcore: disconnect: fail
SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: Co,nnect (retry count 4) to peer Apple-Iphone6-1_PT9036.Dzps4Q== with availability status: true
,SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
SendDataConnector.js: do connect now
,2015-11-20 11:01:19.682 ThaliTest[960:758847] jxcore: connect Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:01:19.683 ThaliTest[960:758847] client session: connect
,2015-11-20 11:01:19.684 ThaliTest[960:758847] client session: stateChange:0->1 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:01:20.081 ThaliTest[960:758717] multipeer session: reset timer
2015-11-20 11:01:20.082 ThaliTest[960:758717] multipeer session: stop timer
2015-11-20 11:01:20.083 ThaliTest[960:758717] multipeer session: start timer: 0x18ee09f0
2015-11-20 ,11:01:20.084 ThaliTest[960:758717] server: disconnecting to refresh session (Apple-Iphone6-1_PT9036)
2015-11-20 11:01:20.084 ThaliTest[960:758717] server session: disconnect
2015-11-20 11:01:20.085 ThaliTest[960:758717] server session: stateChange:2->0 A,pple-Iphone6-1_PT9036
2015-11-20 11:01:20.088 ThaliTest[960:758717] server session: connect
2015-11-20 11:01:20.089 ThaliTest[960:758717] server session: stateChange:0->1 Apple-Iphone6-1_PT9036
,TCP/IP server is ended
TCP/IP server is close
2015-11-20 11:01:20.100 ThaliTest[960:758717] server: accepting invitation Apple-Iphone6-1_PT9036
,2015-11-20 11:01:22.238 ThaliTest[960:759928] server session: connected
,2015-11-20 11:01:22.242 ThaliTest[960:759928] server session: stateChange:1->2 Apple-Iphone6-1_PT9036
,2015-11-20 11:01:22.247 ThaliTest[960:758717] server relay: connected (to port: 55499)
,TCP/IP server connected
,2015-11-20 11:01:22.287 ThaliTest[960:759922] client session: connected
,2015-11-20 11:01:22.290 ThaliTest[960:759922] client session: stateChange:1->2 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:01:22.297 ThaliTest[960:759928] client session: fireConnectCallback: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:01:22.298 ThaliTest[960:759928] jxcore: connect: success
TCP/IP server has received 8760 bytes of data
SendDataConnector.js:, CLIENT connected to 55523, error: null
SendDataConnector.js: CLIENT starting client 
,2015-11-20 11:01:22.310 ThaliTest[960:758717] client: relay established
2015-11-20 11:01:22.311 ThaliTest[960:758717] client: new accepted socket: 0x18f3f570
,TCP/IP server has received 10002 bytes of data
,SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-20 11:01:22.330 ThaliTest[960:759922] server session: not connected Apple-Iphone6-1_PT9036
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,SendDataConnector.js: CLIENT is data received : 100000
,SendDataConnector.js: got all data for this round
,SendDataConnector.js: CLIENT Stop now
,SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 11:01:22.581 ThaliTest[960:758847] jxcore: disconnect
2015-11-20 11:01:22.582 ThaliTest[960:758847] client session: disconnectFromPeer: Apple-Iphone6-1_PT9036.Dzps4Q==
2015-11-20 11:01:22.583 ThaliTest[960:758847] client session: disconnect
2,015-11-20 11:01:22.583 ThaliTest[960:758847] client session: stateChange:2->0 Apple-Iphone6-1_PT9036.Dzps4Q==
,2015-11-20 11:01:22.587 ThaliTest[960:758847] jxcore: disconnect: success
SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9036.Dzps4Q==
,---- round done--------
weAreDoneNow , resultArray.length: 1
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT4118","time":101782,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT9036.Dzps4Q==","time":98606,"result":"OK","connections":5}]}
,sendList : 100% : 98606 ms, 99% : 98606 ms, 95 : 98606 ms, 90% : 98606 ms.
,Result count 1, range 98606 ms to  98606 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,SendDataConnector.js: CLIENT Stop now
,SendDataConnector.js: CLIENT is closed
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-20 11:01:23.005 ThaliTest[960:758847] jxcore: stopBroadcasting
2015-11-20 11:01:23.005 ThaliTest[960:758847] THEMultipeerSession stopping peer
2015-11-20 11:01:23.005 ThaliTest[960:758847] multipeer session: stop timer
2015-11-20 11:01:23.005 Th,aliTest[960:758847] server session: disconnect
2015-11-20 11:01:23.006 ThaliTest[960:758847] server session: stateChange:2->0 Apple-Iphone6-1_PT9036
,2015-11-20 11:01:23.010 ThaliTest[960:758847] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,TCP/IP server is ended
,TCP/IP server  socket is disconnected
,TCP/IP server is close
,DBG, CoordinatorConnector command called
command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT9036.Dzps4Q==\",\"time\":98606,\"result\":\"OK\",\"connections\":5}],\"sendError\":{\"fa,iledPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT9036.Dzps4Q==\",\"time\":98606,\"result\":\"OK\",\"connections\":5},{\"name\":\"Apple-Iphone5s-1_PT4118.XhZL4Q==\",\"time\":99253,\"result\":\"OK\",\"connections\":5}]}}","devices":2,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
