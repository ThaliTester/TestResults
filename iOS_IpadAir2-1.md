#### Test 51193821e3da755_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51193821e3da755/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A700099D-3A55-431F-B3BD-8037EFCD1E92/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A700099D-3A55-431F-B3BD-8037EFCD1E92/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51193821e3da755/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51193821e3da755/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/70DD4E5E-3C62-4BEA-A27D-317D3800E316/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50440"
,(lldb)     command script import "/tmp/A700099D-3A55-431F-B3BD-8037EFCD1E92/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-19 10:39:13.172 ThaliTest[760:791114] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E5F0CF47-7412-45DD-AE27-C133FA5B68B2/Library/Cookies/Cookies.binarycookies
,2015-11-19 10:39:13.461 ThaliTest[760:791114] Apache Cordova native platform version 3.9.2 is starting.
2015-11-19 10:39:13.462 ThaliTest[760:791114] Multi-tasking -> Device: YES, App: YES
,2015-11-19 10:39:13.469 ThaliTest[760:791114] Unlimited access to network resources
,2015-11-19 10:39:13.474 ThaliTest[760:791114] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-19 10:39:17.600 ThaliTest[760:791114] Resetting plugins due to page load.
,2015-11-19 10:39:19.046 ThaliTest[760:791114] Finished load of: file:///var/mobile/Containers/Bundle/Application/70DD4E5E-3C62-4BEA-A27D-317D3800E316/ThaliTest.app/www/index.html
,2015-11-19 10:39:19.198 ThaliTest[760:791114] JXcore Cordova plugin initializing
,2015-11-19 10:39:19.199 ThaliTest[760:791309] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
,Warning: iOS does not support ToggleBluetooth
,We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
,toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,my name is : Apple-IpadAir2-1_PT6621
,attempting to connect to test coordinator
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
fo,und interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,ct]
printNetworkInfo
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,ct]
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
fo,und interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c88a:39ff:febf:ee9f
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"1000000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":2,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"500000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 55075
,2015-11-19 10:49:10.158 ThaliTest[760:791309] jxcore: startBroadcasting
,2015-11-19 10:49:10.165 ThaliTest[760:791309] server: starting Apple-IpadAir2-1_PT6621.ucYn4g==
2015-11-19 10:49:10.165 ThaliTest[760:791309] multipeer session: start timer: 0x176d3420
,2015-11-19 10:49:10.166 ThaliTest[760:791309] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6621
2015-11-19 10:49:10.166 ThaliTest[760:791309] jxcore: startBroadcasting: success
StartBroadcasting started ok
TCP/IP server  is bound to : undefined
,2015-11-19 10:49:10.793 ThaliTest[760:791114] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:10.922 ThaliTest[760:791114] client: found peer: Apple-Iphone5s-1_PT9462.AiaXgQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9462.AiaXgQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-19 10:49:15.797 ThaliTest[760:791309] jxcore: disconnect
2015-11-19 10:49:15.798 ThaliTest[760:791309] jxcore: disconnect: fail
,Connect (retry count 0) to peer Apple-Iphone6-1_PT4558.76EyUA== with availability status: true
do connect now
,2015-11-19 10:49:15.799 ThaliTest[760:791309] jxcore: connect Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:15.799 ThaliTest[760:791309] client session: connect
2015-11-19 10:49:15.799 ThaliTest[760:791309] client session: stateChange:0->1 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:20.163 ThaliTest[760:792447] client session: connected
2015-11-19 10:49:20.163 ThaliTest[760:792447] client session: stateChange:1->2 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:20.206 ThaliTest[760:792487] client session: fireConnectCallback: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:20.206 ThaliTest[760:792487] jxcore: connect: success
,CLIENT connected to 55079, error: null
CLIENT starting client 
,2015-11-19 10:49:20.208 ThaliTest[760:791114] client: relay established
2015-11-19 10:49:20.208 ThaliTest[760:791114] client: new accepted socket: 0x155911f0
,CLIENT now sending 1000000 bytes of data
,CLIENT is data received : 10000
,CLIENT is data received : 20000
,CLIENT is data received : 20000
,CLIENT is data received : 20000
,CLIENT is data received : 30000
,Receiving data timeout now
CLIENT closeClientSocket
,2015-11-19 10:49:31.701 ThaliTest[760:791114] client: socket closed
2015-11-19 10:49:31.701 ThaliTest[760:791114] client relay: socket disconnected
2015-11-19 10:49:31.702 ThaliTest[760:791114] client relay: 0x155911f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:49:31.702 ThaliTest[760:791114] client session: socket closed: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:31.702 ThaliTest[760:791114] client session: onLinkFailure: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:31.702 ThaliTest[760:791114] client session: disconnect
2015-11-19 10:49:31.702 ThaliTest[760:791114] client session: stateChange:2->0 Apple-Ip,hone6-1_PT4558.76EyUA==
tryAgain afer: 5000 ms.
,----------------- closeClientSocket
,CLIENT is closed
,2015-11-19 10:49:31.705 ThaliTest[760:791114] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4558.76EyUA==
,re-try now : Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:40.167 ThaliTest[760:791114] multipeer session: restart
,2015-11-19 10:49:40.178 ThaliTest[760:791114] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:40.178 ThaliTest[760:791114] client: found peer: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:49:41.710 ThaliTest[760:791309] jxcore: disconnect
2015-11-19 10:49:41.710 ThaliTest[760:791309] jxcore: disconnect: fail
Connect (retry count 1) to peer Apple-Iphone6-1_PT4558.76EyUA== with availability status: true
do connect now
2015-1,1-19 10:49:41.710 ThaliTest[760:791309] jxcore: connect Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:41.711 ThaliTest[760:791309] client session: connect
2015-11-19 10:49:41.711 ThaliTest[760:791309] client session: stateChange:0->1 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:45.921 ThaliTest[760:792507] client session: connected
,2015-11-19 10:49:45.921 ThaliTest[760:792507] client session: stateChange:1->2 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:45.958 ThaliTest[760:792541] client session: fireConnectCallback: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:45.958 ThaliTest[760:792541] jxcore: connect: success
CLIENT connected to 55084, error: null
CLIENT starting client 
,2015-11-19 10:49:45.960 ThaliTest[760:791114] client: relay established
2015-11-19 10:49:45.960 ThaliTest[760:791114] client: new accepted socket: 0x188b39b0
,CLIENT now sending 970000 bytes of data
,CLIENT is data received : 30000
,CLIENT is data received : 30000
,CLIENT is data received : 40000
,CLIENT is data received : 40000
,CLIENT is data received : 50000
,CLIENT is data received : 60000
,CLIENT is data received : 60000
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,2015-11-19 10:49:56.980 ThaliTest[760:791114] client: socket closed
2015-11-19 10:49:56.980 ThaliTest[760:791114] client relay: socket disconnected
----------------- closeClientSocket
2015-11-19 10:49:56.980 ThaliTest[760:791114] client relay: 0x188b39b,0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:49:56.980 ThaliTest[760:791114] client session: socket closed: Apple-Iphon,e6-1_PT4558.76EyUA==
CLIENT is closed
2015-11-19 10:49:56.980 ThaliTest[760:791114] client session: onLinkFailure: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:49:56.980 ThaliTest[760:791114] client session: disconnect
2015-11-19 10:49:56.980 ThaliTest[760:791114] client session: stateChange:2->0 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:49:56.983 ThaliTest[760:791114] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4558.76EyUA==
,re-try now : Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:06.986 ThaliTest[760:791309] jxcore: disconnect
2015-11-19 10:50:06.986 ThaliTest[760:791309] jxcore: disconnect: fail
,Connect (retry count 2) to peer Apple-Iphone6-1_PT4558.76EyUA== with availability status: true
do connect now
2015-11-19 10:50:06.986 ThaliTest[760:791309] jxcore: connect Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:06.987 ThaliTest[760:791309] client session: connect
2015-11-19 10:50:06.987 ThaliTest[760:791309] client session: stateChange:0->1 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:10.167 ThaliTest[760:791114] multipeer session: restart
,2015-11-19 10:50:10.176 ThaliTest[760:791114] client: found peer: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:50:10.177 ThaliTest[760:791114] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:10.984 ThaliTest[760:792507] client session: connected
2015-11-19 10:50:10.984 ThaliTest[760:792507] client session: stateChange:1->2 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:10.991 ThaliTest[760:792507] client session: fireConnectCallback: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:10.991 ThaliTest[760:792507] jxcore: connect: success
,CLIENT connected to 55089, error: null
,CLIENT starting client 
,2015-11-19 10:50:10.993 ThaliTest[760:791114] client: relay established
2015-11-19 10:50:10.993 ThaliTest[760:791114] client: new accepted socket: 0x188b4910
,CLIENT now sending 940000 bytes of data
,CLIENT is data received : 60000
,CLIENT is data received : 60000
,CLIENT is data received : 60000
,CLIENT is data received : 70000
,CLIENT is data received : 80000
,CLIENT is data received : 90000
,CLIENT is data received : 100000
,CLIENT is data received : 110000
,CLIENT is data received : 120000
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:50:21.836 ThaliTest[760:791114] client: socket closed
2015-11-19 10:50:21.836 ThaliTest[760:791114] client relay: socket disconnected
2015-11-19 10:50:21.836 ThaliTest[760:791114] client relay: 0x188b4910 disconnect,ed with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:50:21.836 ThaliTest[760:791114] client session: socket closed: Apple-Iphone6-1_PT4558.,76EyUA==
2015-11-19 10:50:21.836 ThaliTest[760:791114] client session: onLinkFailure: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:21.836 ThaliTest[760:791114] client session: disconnect
2015-11-19 10:50:21.836 ThaliTest[760:791114] client session: ,stateChange:2->0 Apple-Iphone6-1_PT4558.76EyUA==
----------------- closeClientSocket
CLIENT is closed
,2015-11-19 10:50:21.838 ThaliTest[760:791114] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4558.76EyUA==
,re-try now : Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:31.854 ThaliTest[760:791309] jxcore: disconnect
2015-11-19 10:50:31.854 ThaliTest[760:791309] jxcore: disconnect: fail
,Connect (retry count 3) to peer Apple-Iphone6-1_PT4558.76EyUA== with availability status: true
do connect now
,2015-11-19 10:50:31.856 ThaliTest[760:791309] jxcore: connect Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:31.856 ThaliTest[760:791309] client session: connect
2015-11-19 10:50:31.856 ThaliTest[760:791309] client session: stateChange:0->1 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:35.565 ThaliTest[760:792672] client session: connected
2015-11-19 10:50:35.565 ThaliTest[760:792672] client session: stateChange:1->2 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:35.580 ThaliTest[760:792666] client session: fireConnectCallback: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:35.580 ThaliTest[760:792666] jxcore: connect: success
,CLIENT connected to 55093, error: null
,CLIENT starting client 
,2015-11-19 10:50:35.581 ThaliTest[760:791114] client: relay established
2015-11-19 10:50:35.582 ThaliTest[760:791114] client: new accepted socket: 0x155e1010
,CLIENT now sending 880000 bytes of data
,CLIENT is data received : 120000
,CLIENT is data received : 130000
,CLIENT is data received : 140000
,CLIENT is data received : 150000
,CLIENT is data received : 160000
,CLIENT is data received : 160000
,2015-11-19 10:50:40.167 ThaliTest[760:791114] multipeer session: restart
,2015-11-19 10:50:40.177 ThaliTest[760:791114] client: found peer: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:50:40.178 ThaliTest[760:791114] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,----------------- closeClientSocket
2015-11-19 10:50:46.431 ThaliTest[760:791114] client: socket closed
2015-11-19 10:50:46.431 ThaliTest[760:791114] client relay: socket disconnected
CLIENT is closed
2015-11-19 10:50:46.431 ThaliTest[760:791114] clien,t relay: 0x155e1010 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:50:46.431 ThaliTest[760:791114] client session: socket c,losed: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:46.431 ThaliTest[760:791114] client session: onLinkFailure: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:46.431 ThaliTest[760:791114] client session: disconnect
2015-11-19 10:50:46.431 ThaliTes,t[760:791114] client session: stateChange:2->0 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:46.434 ThaliTest[760:791114] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4558.76EyUA==
,re-try now : Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:56.439 ThaliTest[760:791309] jxcore: disconnect
2015-11-19 10:50:56.439 ThaliTest[760:791309] jxcore: disconnect: fail
Connect (retry count 4) to peer Apple-Iphone6-1_PT4558.76EyUA== with availability status: true
do connect now
2015-1,1-19 10:50:56.440 ThaliTest[760:791309] jxcore: connect Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:56.440 ThaliTest[760:791309] client session: connect
2015-11-19 10:50:56.440 ThaliTest[760:791309] client session: stateChange:0->1 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:59.696 ThaliTest[760:792733] client session: connected
2015-11-19 10:50:59.696 ThaliTest[760:792733] client session: stateChange:1->2 Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:50:59.705 ThaliTest[760:792733] client session: fireConnectCallback: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:50:59.705 ThaliTest[760:792733] jxcore: connect: success
CLIENT connected to 55098, error: null
CLIENT starting client 
,2015-11-19 10:50:59.707 ThaliTest[760:791114] client: relay established
2015-11-19 10:50:59.707 ThaliTest[760:791114] client: new accepted socket: 0x188b4910
,CLIENT now sending 840000 bytes of data
,CLIENT is data received : 160000
,CLIENT is data received : 170000
,CLIENT is data received : 180000
,CLIENT is data received : 190000
,CLIENT is data received : 200000
,CLIENT is data received : 210000
,CLIENT is data received : 220000
,2015-11-19 10:51:10.167 ThaliTest[760:791114] multipeer session: restart
,2015-11-19 10:51:10.177 ThaliTest[760:791114] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:51:10.178 ThaliTest[760:791114] client: found peer: Apple-Iphone5s-1_PT9462.AiaXgQ==
,Receiving data timeout now
,CLIENT closeClientSocket
,2015-11-19 10:51:10.554 ThaliTest[760:791114] client: socket closed
2015-11-19 10:51:10.554 ThaliTest[760:791114] client relay: socket disconnected
2015-11-19 10:51:10.554 ThaliTest[760:791114] client relay: 0x188b4910 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:51:10.554 ThaliTest[760:791114] client session: socket closed: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:51:10.554 ThaliTest[760:791114] client session: onLinkFailure: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:51:10.554 ThaliTest[760:791114] client session: disconnect
2015-11-19 10:51:10.554 ThaliTest[760:791114] client session: stateChange:2->0 Apple-Ip,hone6-1_PT4558.76EyUA==
CLIENT Stop now
Stop data retrieving timer
CLIENT Stop now
,---- round done--------
device[2]: Apple-Iphone5s-1_PT9462.AiaXgQ==
----------------- closeClientSocket
CLIENT is closed
,2015-11-19 10:51:10.558 ThaliTest[760:791114] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4558.76EyUA==
,2015-11-19 10:51:12.945 ThaliTest[760:791114] multipeer session: reset timer
2015-11-19 10:51:12.945 ThaliTest[760:791114] multipeer session: stop timer
2015-11-19 10:51:12.945 ThaliTest[760:791114] multipeer session: start timer: 0x176d3420
2015-11-19 10:51:12.946 ThaliTest[760:791114] server session: connect
2015-11-19 10:51:12.946 ThaliTest[760:791114] server session: stateChange:0->1 Apple-Iphone5s-1_PT9462
,2015-11-19 10:51:12.948 ThaliTest[760:791114] server: accepting invitation Apple-Iphone5s-1_PT9462
,2015-11-19 10:51:15.496 ThaliTest[760:792737] server session: connected
2015-11-19 10:51:15.496 ThaliTest[760:792737] server session: stateChange:1->2 Apple-Iphone5s-1_PT9462
,2015-11-19 10:51:15.506 ThaliTest[760:791114] server relay: connected (to port: 55075)
,TCP/IP server connected
,2015-11-19 10:51:15.563 ThaliTest[760:791309] jxcore: disconnect
2015-11-19 10:51:15.564 ThaliTest[760:791309] jxcore: disconnect: fail
Connect (retry count 0) to peer Apple-Iphone5s-1_PT9462.AiaXgQ== with availability status: true
do connect now
2015-11-19 10:51:15.564 ThaliTest[760:791309] jxcore: connect Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:51:15.564 ThaliTest[760:791309] client session: connect
2015-11-19 10:51:15.564 ThaliTest[760:791309] client session: stateChange:0->1 Apple-Iphone5s-1_PT9462.AiaXgQ==
,TCP/IP server has received 10950 bytes of data
,TCP/IP server has received 82794 bytes of data
,TCP/IP server has received 137970 bytes of data
,TCP/IP server has received 183960 bytes of data
,TCP/IP server has received 258420 bytes of data
,TCP/IP server has received 321930 bytes of data
,TCP/IP server has received 405150 bytes of data
,TCP/IP server has received 451140 bytes of data
,TCP/IP server has received 488370 bytes of data
,TCP/IP server has received 593490 bytes of data
,TCP/IP server has received 637290 bytes of data
,TCP/IP server has received 700800 bytes of data
,TCP/IP server has received 766500 bytes of data
,TCP/IP server has received 832200 bytes of data
,TCP/IP server has received 893236 bytes of data
,TCP/IP server has received 959220 bytes of data
,TCP/IP server has received 1000002 bytes of data
,2015-11-19 10:51:18.594 ThaliTest[760:792785] client session: connected
2015-11-19 10:51:18.594 ThaliTest[760:792785] client session: stateChange:1->2 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:51:18.602 ThaliTest[760:792785] client session: fireConnectCallback: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:51:18.602 ThaliTest[760:792785] jxcore: connect: success
CLIENT connected to 55104, error: null
CLIENT starting client 
,2015-11-19 10:51:18.603 ThaliTest[760:791114] client: relay established
2015-11-19 10:51:18.604 ThaliTest[760:791114] client: new accepted socket: 0x15624170
,CLIENT now sending 1000000 bytes of data
,CLIENT is data received : 0
,CLIENT is data received : 10000
,CLIENT is data received : 20000
,CLIENT is data received : 30000
,CLIENT is data received : 40000
,CLIENT is data received : 50000
,CLIENT is data received : 60000
,CLIENT is data received : 70000
,CLIENT is data received : 80000
,CLIENT is data received : 90000
,CLIENT is data received : 100000
,2015-11-19 10:51:26.278 ThaliTest[760:792784] server session: not connected Apple-Iphone5s-1_PT9462
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:51:29.808 ThaliTest[760:791114] client: socket closed
,2015-11-19 10:51:29.808 ThaliTest[760:791114] client relay: socket disconnected
----------------- closeClientSocket
2015-11-19 10:51:29.808 ThaliTest[760:791114] client relay: 0x15624170 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code,=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:51:29.808 ThaliTest[760:791114] client session: socket closed: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:51:29.809 ThaliTest[760:791114] ,client session: onLinkFailure: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:51:29.809 ThaliTest[760:791114] client session: disconnect
2015-11-19 10:51:29.809 ThaliTest[760:791114] client session: stateChange:2->0 Apple-Iphone5s-1_PT9462.AiaXgQ==
CLIENT is closed
,2015-11-19 10:51:29.811 ThaliTest[760:791114] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9462.AiaXgQ==
,re-try now : Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:51:36.070 ThaliTest[760:791114] client: lost peer: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:51:36.070 ThaliTest[760:791114] client session: onPeerLost: Apple-Iphone6-1_PT4558.76EyUA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:51:36.462 ThaliTest[760:791114] multipeer session: reset timer
2015-11-19 10:51:36.462 ThaliTest[760:791114] multipeer session: stop timer
2015-11-19 10:51:36.462 ThaliTest[760:791114] multipeer session: start timer: 0x176d3420
2015-11-19 10:51:36.463 ThaliTest[760:791114] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9462)
2015-11-19 10:51:36.463 ThaliTest[760:791114] server session: disconnect
2015-11-19 10:51:36.463 ThaliTest[760:791114] server session: stateChange:2->0 Apple-Iphone5s-1_PT9462
,2015-11-19 10:51:36.464 ThaliTest[760:791114] server session: connect
2015-11-19 10:51:36.464 ThaliTest[760:791114] server session: stateChange:0->1 Apple-Iphone5s-1_PT9462
,2015-11-19 10:51:36.467 ThaliTest[760:791114] server: accepting invitation Apple-Iphone5s-1_PT9462
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:51:39.041 ThaliTest[760:792784] server session: connected
2015-11-19 10:51:39.041 ThaliTest[760:792784] server session: stateChange:1->2 Apple-Iphone5s-1_PT9462
,2015-11-19 10:51:39.052 ThaliTest[760:791114] server relay: connected (to port: 55075)
,TCP/IP server connected
,TCP/IP server has received 70080 bytes of data
,TCP/IP server has received 137970 bytes of data
,TCP/IP server has received 223380 bytes of data
,TCP/IP server has received 284700 bytes of data
,TCP/IP server has received 367920 bytes of data
,TCP/IP server has received 450856 bytes of data
,TCP/IP server has received 532170 bytes of data
,TCP/IP server has received 597870 bytes of data
,TCP/IP server has received 670140 bytes of data
,TCP/IP server has received 731460 bytes of data
,TCP/IP server has received 792780 bytes of data
,TCP/IP server has received 851910 bytes of data
,TCP/IP server has received 926370 bytes of data
,TCP/IP server has received 989880 bytes of data
,TCP/IP server has received 990002 bytes of data
,2015-11-19 10:51:39.818 ThaliTest[760:791309] jxcore: disconnect
2015-11-19 10:51:39.818 ThaliTest[760:791309] jxcore: disconnect: fail
Connect (retry count 1) to peer Apple-Iphone5s-1_PT9462.AiaXgQ== with availability status: true
do connect now
,2015-11-19 10:51:39.819 ThaliTest[760:791309] jxcore: connect Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:51:39.819 ThaliTest[760:791309] client session: connect
,2015-11-19 10:51:39.819 ThaliTest[760:791309] client session: stateChange:0->1 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:51:40.201 ThaliTest[760:791114] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:51:42.742 ThaliTest[760:792784] client session: connected
2015-11-19 10:51:42.742 ThaliTest[760:792784] client session: stateChange:1->2 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:51:42.752 ThaliTest[760:792785] client session: fireConnectCallback: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:51:42.752 ThaliTest[760:792785] jxcore: connect: success
CLIENT connected to 55109, error: null
CLIENT starting client 
,2015-11-19 10:51:42.754 ThaliTest[760:791114] client: relay established
2015-11-19 10:51:42.754 ThaliTest[760:791114] client: new accepted socket: 0x177ee3d0
,CLIENT now sending 900000 bytes of data
,CLIENT is data received : 100000
,CLIENT is data received : 100000
,CLIENT is data received : 110000
,CLIENT is data received : 120000
,CLIENT is data received : 130000
,CLIENT is data received : 140000
,CLIENT is data received : 140000
,2015-11-19 10:51:50.075 ThaliTest[760:792819] server session: not connected Apple-Iphone5s-1_PT9462
,Receiving data timeout now
CLIENT closeClientSocket
,2015-11-19 10:51:53.601 ThaliTest[760:791114] client: socket closed
2015-11-19 10:51:53.602 ThaliTest[760:791114] client relay: socket disconnected
2015-11-19 10:51:53.602 ThaliTest[760:791114] client relay: 0x177ee3d0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:51:53.602 ThaliTest[760:791114] client session: socket closed: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:51:53.602 ThaliTest[760:791114] client session: onLinkFailure: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:51:53.602 ThaliTest[760:791114] client session: disconnect
2015-11-19 10:51:53.602 ThaliTest[760:791114] client session: stateChange:2->0 Apple-Iphone5s-1_PT9462.AiaXgQ==
tryAgain afer: 5000 ms.
----------------- closeClientSocket
CLIENT is closed
,2015-11-19 10:51:53.604 ThaliTest[760:791114] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:51:54.313 ThaliTest[760:791114] multipeer session: reset timer
2015-11-19 10:51:54.313 ThaliTest[760:791114] multipeer session: stop timer
2015-11-19 10:51:54.313 ThaliTest[760:791114] multipeer session: start timer: 0x176d3420
2015-11-19 ,10:51:54.313 ThaliTest[760:791114] server session: connect
2015-11-19 10:51:54.313 ThaliTest[760:791114] server session: stateChange:0->1 Apple-Iphone6-1_PT4558
,2015-11-19 10:51:54.315 ThaliTest[760:791114] server: accepting invitation Apple-Iphone6-1_PT4558
,2015-11-19 10:51:56.882 ThaliTest[760:792877] server session: connected
2015-11-19 10:51:56.882 ThaliTest[760:792877] server session: stateChange:1->2 Apple-Iphone6-1_PT4558
,2015-11-19 10:51:56.888 ThaliTest[760:791114] server relay: connected (to port: 55075)
,TCP/IP server connected
,TCP/IP server has received 13140 bytes of data
,TCP/IP server has received 89790 bytes of data
,TCP/IP server has received 197100 bytes of data
,TCP/IP server has received 302220 bytes of data
,TCP/IP server has received 394200 bytes of data
,TCP/IP server has received 494940 bytes of data
,TCP/IP server has received 580350 bytes of data
,TCP/IP server has received 678900 bytes of data
,TCP/IP server has received 774976 bytes of data
,TCP/IP server has received 860528 bytes of data
,TCP/IP server has received 983310 bytes of data
,TCP/IP server has received 1000002 bytes of data
,re-try now : Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:52:00.112 ThaliTest[760:791114] multipeer session: reset timer
2015-11-19 10:52:00.112 ThaliTest[760:791114] multipeer session: stop timer
2015-11-19 10:52:00.112 ThaliTest[760:791114] multipeer session: start timer: 0x176d3420
2015-11-19 10:52:00.112 ThaliTest[760:791114] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9462)
,2015-11-19 10:52:00.112 ThaliTest[760:791114] server session: disconnect
,2015-11-19 10:52:00.113 ThaliTest[760:791114] server session: stateChange:2->0 Apple-Iphone5s-1_PT9462
,2015-11-19 10:52:00.114 ThaliTest[760:791114] server session: connect
2015-11-19 10:52:00.114 ThaliTest[760:791114] server session: stateChange:0->1 Apple-Iphone5s-1_PT9462
,2015-11-19 10:52:00.117 ThaliTest[760:791114] server: accepting invitation Apple-Iphone5s-1_PT9462
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:52:02.669 ThaliTest[760:792840] server session: connected
2015-11-19 10:52:02.670 ThaliTest[760:792840] server session: stateChange:1->2 Apple-Iphone5s-1_PT9462
,2015-11-19 10:52:02.683 ThaliTest[760:791114] server relay: connected (to port: 55075)
,TCP/IP server connected
,TCP/IP server has received 35040 bytes of data
,TCP/IP server has received 100740 bytes of data
,TCP/IP server has received 175200 bytes of data
,TCP/IP server has received 258420 bytes of data
,TCP/IP server has received 328500 bytes of data
,TCP/IP server has received 400770 bytes of data
,TCP/IP server has received 481800 bytes of data
,TCP/IP server has received 554070 bytes of data
,TCP/IP server has received 635100 bytes of data
,TCP/IP server has received 709560 bytes of data
,TCP/IP server has received 801540 bytes of data
,TCP/IP server has received 873810 bytes of data
,TCP/IP server has received 946080 bytes of data
,TCP/IP server has received 950002 bytes of data
,2015-11-19 10:52:03.612 ThaliTest[760:791309] jxcore: disconnect
2015-11-19 10:52:03.613 ThaliTest[760:791309] jxcore: disconnect: fail
Connect (retry count 2) to peer Apple-Iphone5s-1_PT9462.AiaXgQ== with availability status: true
do connect now
2015-11-19 10:52:03.613 ThaliTest[760:791309] jxcore: connect Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:52:03.613 ThaliTest[760:791309] client session: connect
,2015-11-19 10:52:03.613 ThaliTest[760:791309] client session: stateChange:0->1 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:52:06.323 ThaliTest[760:792784] client session: connected
2015-11-19 10:52:06.323 ThaliTest[760:792784] client session: stateChange:1->2 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:52:06.330 ThaliTest[760:792840] client session: fireConnectCallback: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:52:06.330 ThaliTest[760:792840] jxcore: connect: success
CLIENT connected to 55115, error: null
CLIENT starting client 
,2015-11-19 10:52:06.332 ThaliTest[760:791114] client: relay established
,2015-11-19 10:52:06.332 ThaliTest[760:791114] client: new accepted socket: 0x156dbf90
,CLIENT now sending 860000 bytes of data
,CLIENT is data received : 140000
,CLIENT is data received : 140000
,CLIENT is data received : 150000
,CLIENT is data received : 160000
,CLIENT is data received : 170000
,CLIENT is data received : 180000
,CLIENT is data received : 190000
,CLIENT is data received : 200000
,2015-11-19 10:52:07.895 ThaliTest[760:792819] server session: not connected Apple-Iphone6-1_PT4558
,2015-11-19 10:52:13.382 ThaliTest[760:792840] server session: not connected Apple-Iphone5s-1_PT9462
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,2015-11-19 10:52:17.168 ThaliTest[760:791114] client: socket closed
2015-11-19 10:52:17.168 ThaliTest[760:791114] client relay: socket disconnected
2015-11-19 10:52:17.168 ThaliTest[760:791114] client relay: 0x156dbf90 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:52:17.168 ThaliTest[760:791114] client session: socket closed: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:,52:17.168 ThaliTest[760:791114] client session: onLinkFailure: Apple-Iphone5s-1_PT9462.AiaXgQ==
----------------- closeClientSocket
2015-11-19 10:52:17.169 ThaliTest[760:791114] client session: disconnect
2015-11-19 10:52:17.169 ThaliTest[760:791114] client session: stateChange:2->0 Apple-Iphone5s-1_PT9462.AiaXgQ==
,CLIENT is closed
2015-11-19 10:52:17.171 ThaliTest[760:791114] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:52:17.939 ThaliTest[760:791114] multipeer session: reset timer
2015-11-19 10:52:17.939 ThaliTest[760:791114] multipeer session: stop timer
2015-11-19 10:52:17.939 ThaliTest[760:791114] multipeer session: start timer: 0x176d3420
2015-11-19 10:52:17.939 ThaliTest[760:791114] server: disconnecting to refresh session (Apple-Iphone6-1_PT4558)
2015-11-19 10:52:17.939 ThaliTest[760:791114] server session: disconnect
2015-11-19 10:52:17.939 ThaliTest[760:791114] server session: stateChange:2->0 Apple-Iphone6-1_PT4558
,2015-11-19 10:52:17.941 ThaliTest[760:791114] server session: connect
2015-11-19 10:52:17.942 ThaliTest[760:791114] server session: stateChange:0->1 Apple-Iphone6-1_PT4558
,2015-11-19 10:52:17.945 ThaliTest[760:791114] server: accepting invitation Apple-Iphone6-1_PT4558
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:52:20.436 ThaliTest[760:792819] server session: connected
2015-11-19 10:52:20.436 ThaliTest[760:792819] server session: stateChange:1->2 Apple-Iphone6-1_PT4558
,2015-11-19 10:52:20.446 ThaliTest[760:791114] server relay: connected (to port: 55075)
,TCP/IP server connected
,TCP/IP server has received 54324 bytes of data
,TCP/IP server has received 175058 bytes of data
,TCP/IP server has received 262800 bytes of data
,TCP/IP server has received 352590 bytes of data
,TCP/IP server has received 457710 bytes of data
,TCP/IP server has received 565020 bytes of data
,TCP/IP server has received 641386 bytes of data
,TCP/IP server has received 735840 bytes of data
,TCP/IP server has received 803730 bytes of data
,TCP/IP server has received 869430 bytes of data
,TCP/IP server has received 930750 bytes of data
,TCP/IP server has received 960002 bytes of data
,re-try now : Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:52:23.700 ThaliTest[760:791114] multipeer session: reset timer
2015-11-19 10:52:23.700 ThaliTest[760:791114] multipeer session: stop timer
2015-11-19 10:52:23.700 ThaliTest[760:791114] multipeer session: start timer: 0x176d3420
2015-11-19 ,10:52:23.700 ThaliTest[760:791114] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9462)
2015-11-19 10:52:23.700 ThaliTest[760:791114] server session: disconnect
2015-11-19 10:52:23.700 ThaliTest[760:791114] server session: stateChange:2->0 Apple-Iphone5s-1_PT9462
,2015-11-19 10:52:23.701 ThaliTest[760:791114] server session: connect
2015-11-19 10:52:23.701 ThaliTest[760:791114] server session: stateChange:0->1 Apple-Iphone5s-1_PT9462
,2015-11-19 10:52:23.705 ThaliTest[760:791114] server: accepting invitation Apple-Iphone5s-1_PT9462
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:52:26.248 ThaliTest[760:792840] server session: connected
2015-11-19 10:52:26.248 ThaliTest[760:792840] server session: stateChange:1->2 Apple-Iphone5s-1_PT9462
,2015-11-19 10:52:26.254 ThaliTest[760:791114] server relay: connected (to port: 55075)
,TCP/IP server connected
,TCP/IP server has received 34756 bytes of data
,TCP/IP server has received 111690 bytes of data
,TCP/IP server has received 179580 bytes of data
,TCP/IP server has received 247470 bytes of data
,TCP/IP server has received 317550 bytes of data
,TCP/IP server has received 392010 bytes of data
,TCP/IP server has received 479610 bytes of data
,TCP/IP server has received 560640 bytes of data
,TCP/IP server has received 637290 bytes of data
,TCP/IP server has received 718320 bytes of data
,TCP/IP server has received 790590 bytes of data
,TCP/IP server has received 867240 bytes of data
,TCP/IP server has received 920002 bytes of data
,2015-11-19 10:52:27.179 ThaliTest[760:791309] jxcore: disconnect
2015-11-19 10:52:27.179 ThaliTest[760:791309] jxcore: disconnect: fail
Connect (retry count 3) to peer Apple-Iphone5s-1_PT9462.AiaXgQ== with availability status: true
do connect now
,2015-11-19 10:52:27.179 ThaliTest[760:791309] jxcore: connect Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:52:27.180 ThaliTest[760:791309] client session: connect
2015-11-19 10:52:27.180 ThaliTest[760:791309] client session: stateChange:0->1 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:52:29.889 ThaliTest[760:792928] client session: connected
2015-11-19 10:52:29.889 ThaliTest[760:792928] client session: stateChange:1->2 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:52:29.898 ThaliTest[760:792784] client session: fireConnectCallback: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:52:29.898 ThaliTest[760:792784] jxcore: connect: success
CLIENT connected to 55121, error: null
CLIENT starting client 
,2015-11-19 10:52:29.900 ThaliTest[760:791114] client: relay established
2015-11-19 10:52:29.900 ThaliTest[760:791114] client: new accepted socket: 0x1772be90
,CLIENT now sending 800000 bytes of data
,CLIENT is data received : 200000
,CLIENT is data received : 200000
,CLIENT is data received : 200000
,CLIENT is data received : 210000
,CLIENT is data received : 220000
,CLIENT is data received : 220000
,CLIENT is data received : 230000
,CLIENT is data received : 240000
,CLIENT is data received : 250000
,CLIENT is data received : 260000
,CLIENT is data received : 270000
,CLIENT is data received : 280000
,2015-11-19 10:52:31.482 ThaliTest[760:792784] server session: not connected Apple-Iphone6-1_PT4558
,2015-11-19 10:52:32.128 ThaliTest[760:791114] client: lost peer: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:52:32.128 ThaliTest[760:791114] client session: onPeerLost: Apple-Iphone6-1_PT4558.76EyUA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:52:33.121 ThaliTest[760:791114] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:52:37.186 ThaliTest[760:792819] server session: not connected Apple-Iphone5s-1_PT9462
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:52:41.019 ThaliTest[760:791114] client: socket closed
2015-11-19 10:52:41.019 ThaliTest[760:791114] client relay: socket disconnected
----------------- closeClientSocket
2015-11-19 10:52:41.019 ThaliTest[760:791114] client relay: 0x1772be90 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:52:41.019 ThaliTest[760:791114] client session: s,ocket closed: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:52:41.019 ThaliTest[760:791114] client session: onLinkFailure: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:52:41.019 ThaliTest[760:791114] client session: disconnect
2015-11-19 10:52:41.019 ThaliTest[760:791114] client session: stateChange:2->0 Apple-Iphone5s-1_PT9462.AiaXgQ==
,CLIENT is closed
2015-11-19 10:52:41.021 ThaliTest[760:791114] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:52:42.506 ThaliTest[760:791114] multipeer session: reset timer
,2015-11-19 10:52:42.506 ThaliTest[760:791114] multipeer session: stop timer
,2015-11-19 10:52:42.506 ThaliTest[760:791114] multipeer session: start timer: 0x176d3420
2015-11-19 10:52:42.507 ThaliTest[760:791114] server: disconnecting to refresh session (Apple-Iphone6-1_PT4558)
2015-11-19 10:52:42.507 ThaliTest[760:791114] server session: disconnect
2015-11-19 10:52:42.507 ThaliTest[760:791114] server session: stateChange:2->0 Apple-Iphone6-1_PT4558
,2015-11-19 10:52:42.508 ThaliTest[760:791114] server session: connect
2015-11-19 10:52:42.508 ThaliTest[760:791114] server session: stateChange:0->1 Apple-Iphone6-1_PT4558
,2015-11-19 10:52:42.510 ThaliTest[760:791114] server: accepting invitation Apple-Iphone6-1_PT4558
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:52:45.123 ThaliTest[760:792819] server session: connected
2015-11-19 10:52:45.123 ThaliTest[760:792819] server session: stateChange:1->2 Apple-Iphone6-1_PT4558
,2015-11-19 10:52:45.130 ThaliTest[760:791114] server relay: connected (to port: 55075)
,TCP/IP server connected
,TCP/IP server has received 30660 bytes of data
,TCP/IP server has received 118118 bytes of data
,TCP/IP server has received 216810 bytes of data
,TCP/IP server has received 315360 bytes of data
,TCP/IP server has received 415958 bytes of data
,TCP/IP server has received 494940 bytes of data
,TCP/IP server has received 565020 bytes of data
,TCP/IP server has received 630720 bytes of data
,TCP/IP server has received 692040 bytes of data
,TCP/IP server has received 751170 bytes of data
,TCP/IP server has received 801540 bytes of data
,TCP/IP server has received 882570 bytes of data
,TCP/IP server has received 920002 bytes of data
,re-try now : Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:52:47.226 ThaliTest[760:791114] multipeer session: reset timer
2015-11-19 10:52:47.226 ThaliTest[760:791114] multipeer session: stop timer
2015-11-19 10:52:47.226 ThaliTest[760:791114] multipeer session: start timer: 0x176d3420
2015-11-19 ,10:52:47.226 ThaliTest[760:791114] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9462)
2015-11-19 10:52:47.226 ThaliTest[760:791114] server session: disconnect
2015-11-19 10:52:47.226 ThaliTest[760:791114] server session: stateChange:2->0 ,Apple-Iphone5s-1_PT9462
,2015-11-19 10:52:47.228 ThaliTest[760:791114] server session: connect
2015-11-19 10:52:47.228 ThaliTest[760:791114] server session: stateChange:0->1 Apple-Iphone5s-1_PT9462
,2015-11-19 10:52:47.231 ThaliTest[760:791114] server: accepting invitation Apple-Iphone5s-1_PT9462
,TCP/IP server is ended
,TCP/IP server is close
,2015-11-19 10:52:49.921 ThaliTest[760:793040] server session: connected
2015-11-19 10:52:49.922 ThaliTest[760:793040] server session: stateChange:1->2 Apple-Iphone5s-1_PT9462
,2015-11-19 10:52:49.930 ThaliTest[760:791114] server relay: connected (to port: 55075)
,TCP/IP server connected
,TCP/IP server has received 39420 bytes of data
,TCP/IP server has received 111690 bytes of data
,TCP/IP server has received 179580 bytes of data
,TCP/IP server has received 254040 bytes of data
,TCP/IP server has received 321930 bytes of data
,TCP/IP server has received 394200 bytes of data
,TCP/IP server has received 464280 bytes of data
,TCP/IP server has received 532170 bytes of data
,TCP/IP server has received 606488 bytes of data
,TCP/IP server has received 696136 bytes of data
,TCP/IP server has received 770880 bytes of data
,TCP/IP server has received 834390 bytes of data
,TCP/IP server has received 890002 bytes of data
,2015-11-19 10:52:51.030 ThaliTest[760:791309] jxcore: disconnect
2015-11-19 10:52:51.030 ThaliTest[760:791309] jxcore: disconnect: fail
Connect (retry count 4) to peer Apple-Iphone5s-1_PT9462.AiaXgQ== with availability status: true
do connect now
2015-11-19 10:52:51.031 ThaliTest[760:791309] jxcore: connect Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:52:51.031 ThaliTest[760:791309] client session: connect
2015-11-19 10:52:51.031 ThaliTest[760:791309] client session: stateChange:0->1 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:52:53.671 ThaliTest[760:793046] client session: connected
2015-11-19 10:52:53.672 ThaliTest[760:793046] client session: stateChange:1->2 Apple-Iphone5s-1_PT9462.AiaXgQ==
,2015-11-19 10:52:53.679 ThaliTest[760:793039] client session: fireConnectCallback: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:52:53.679 ThaliTest[760:793039] jxcore: connect: success
CLIENT connected to 55127, error: null
CLIENT starting client 
,2015-11-19 10:52:53.681 ThaliTest[760:791114] client: relay established
2015-11-19 10:52:53.681 ThaliTest[760:791114] client: new accepted socket: 0x176db410
,CLIENT now sending 720000 bytes of data
,CLIENT is data received : 280000
,CLIENT is data received : 280000
,CLIENT is data received : 280000
,CLIENT is data received : 290000
,CLIENT is data received : 300000
,CLIENT is data received : 310000
,CLIENT is data received : 320000
,CLIENT is data received : 330000
,2015-11-19 10:52:56.120 ThaliTest[760:793040] server session: not connected Apple-Iphone6-1_PT4558
,2015-11-19 10:53:00.601 ThaliTest[760:793040] server session: not connected Apple-Iphone5s-1_PT9462
,Receiving data timeout now
CLIENT closeClientSocket
,CLIENT Stop now
,2015-11-19 10:53:04.373 ThaliTest[760:791114] client: socket closed
2015-11-19 10:53:04.373 ThaliTest[760:791114] client relay: socket disconnected
,Stop data retrieving timer
2015-11-19 10:53:04.373 ThaliTest[760:791114] client relay: 0x176db410 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote, peer} 
2015-11-19 10:53:04.373 ThaliTest[760:791114] client session: socket closed: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:53:04.373 ThaliTest[760:791114] client session: onLinkFailure: Apple-Iphone5s-1_PT9462.AiaXgQ==
2015-11-19 10:53:04.373 T,haliTest[760:791114] client session: disconnect
2015-11-19 10:53:04.373 ThaliTest[760:791114] client session: stateChange:2->0 Apple-Iphone5s-1_PT9462.AiaXgQ==
CLIENT Stop now
,---- round done--------
weAreDoneNow , resultArray.length: 2
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
2015-11-19 10:53:04.377 ThaliTest[760:791114] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9462.AiaXgQ==
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT6621","time":234223,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT4558.76EyUA==","time":119760,"result":"DATA-TIMEOUT","connections":5},{"name":"Apple-Iphone5s-1_PT9462.AiaXgQ==","time":113816,"result":"DATA-TIMEOUT","connections":5}]}
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items
,sendList failed peers count : 2 [100 %]
- Peer ID : Apple-Iphone6-1_PT4558.76EyUA==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT9462.AiaXgQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
,CLIENT Stop now
,----------------- closeClientSocket
,CLIENT is closed
,2015-11-19 10:53:06.199 ThaliTest[760:791114] client: lost peer: Apple-Iphone6-1_PT4558.76EyUA==
2015-11-19 10:53:06.199 ThaliTest[760:791114] client session: onPeerLost: Apple-Iphone6-1_PT4558.76EyUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:53:07.144 ThaliTest[760:791114] multipeer session: reset timer
2015-11-19 10:53:07.144 ThaliTest[760:791114] multipeer session: stop timer
2015-11-19 10:53:07.144 ThaliTest[760:791114] multipeer session: start timer: 0x176d3420
2015-11-19 ,10:53:07.144 ThaliTest[760:791114] server: disconnecting to refresh session (Apple-Iphone6-1_PT4558)
2015-11-19 10:53:07.144 ThaliTest[760:791114] server session: disconnect
2015-11-19 10:53:07.144 ThaliTest[760:791114] server session: stateChange:2->0 Apple-Iphone6-1_PT4558
,2015-11-19 10:53:07.145 ThaliTest[760:791114] server session: connect
2015-11-19 10:53:07.145 ThaliTest[760:791114] server session: stateChange:0->1 Apple-Iphone6-1_PT4558
,2015-11-19 10:53:07.148 ThaliTest[760:791114] server: accepting invitation Apple-Iphone6-1_PT4558
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:53:09.689 ThaliTest[760:793099] server session: connected
2015-11-19 10:53:09.689 ThaliTest[760:793099] server session: stateChange:1->2 Apple-Iphone6-1_PT4558
,2015-11-19 10:53:09.697 ThaliTest[760:791114] server relay: connected (to port: 55075)
,TCP/IP server connected
,TCP/IP server has received 2190 bytes of data
,TCP/IP server has received 6570 bytes of data
,TCP/IP server has received 8760 bytes of data
,TCP/IP server has received 10950 bytes of data
,TCP/IP server has received 142022 bytes of data
,TCP/IP server has received 148920 bytes of data
,TCP/IP server has received 164108 bytes of data
,TCP/IP server has received 267180 bytes of data
,TCP/IP server has received 354780 bytes of data
,TCP/IP server has received 448950 bytes of data
,TCP/IP server has received 514650 bytes of data
,TCP/IP server has received 571590 bytes of data
,TCP/IP server has received 630720 bytes of data
,TCP/IP server has received 692040 bytes of data
,TCP/IP server has received 755550 bytes of data
,TCP/IP server has received 836438 bytes of data
,TCP/IP server has received 880002 bytes of data
,2015-11-19 10:53:11.256 ThaliTest[760:791114] client: found peer: Apple-Iphone6-1_PT4558.76EyUA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4558.76EyUA==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-11-19 10:53:20.521 ThaliTest[760:791309] jxcore: stopBroadcasting
,2015-11-19 10:53:20.521 ThaliTest[760:791309] THEMultipeerSession stopping peer
2015-11-19 10:53:20.522 ThaliTest[760:791309] multipeer session: stop timer
2015-11-19 10:53:20.522 ThaliTest[760:791309] server session: disconnect
2015-11-19 10:53:20.522 ThaliTest[760:791309] server session: stateChange:2->0 Apple-Iphone6-1_PT4558
,2015-11-19 10:53:20.531 ThaliTest[760:791309] server session: disconnect
,2015-11-19 10:53:20.531 ThaliTest[760:791309] server session: stateChange:2->0 Apple-Iphone5s-1_PT9462
,2015-11-19 10:53:20.592 ThaliTest[760:791309] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,TCP/IP server is ended
,TCP/IP server is ended
,TCP/IP server  socket is disconnected
,TCP/IP server is close
,TCP/IP server is close
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone6-1_PT4558.76EyUA==\",\"time\":119760,\"result\":\"DATA-TIMEOUT\",\"connections\":5},{\"name\":\"Apple-,Iphone5s-1_PT9462.AiaXgQ==\",\"time\":113816,\"result\":\"DATA-TIMEOUT\",\"connections\":5}],\"notTriedList\":[]}},\"combined\":{\"sendList\":[]}}","devices":3,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received

```
