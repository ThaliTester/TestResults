#### Test 51335028813a553_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028813a553/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/D432787E-5C01-4853-85E0-8B5EAE61AFEF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D432787E-5C01-4853-85E0-8B5EAE61AFEF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028813a553/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028813a553/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7F3C4D20-B74D-42AE-B19C-B2525333D8F5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51166"
,(lldb)     command script import "/tmp/D432787E-5C01-4853-85E0-8B5EAE61AFEF/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 12:58:56.760 ThaliTest[841:950162] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/984E9E9C-99A4-45E0-A140-CBF5C6AA0024/Library/Cookies/Cookies.binarycookies
,2015-11-20 12:58:57.042 ThaliTest[841:950162] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 12:58:57.042 ThaliTest[841:950162] Multi-tasking -> Device: YES, App: YES
,2015-11-20 12:58:57.048 ThaliTest[841:950162] Unlimited access to network resources
,2015-11-20 12:58:57.054 ThaliTest[841:950162] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 12:59:01.186 ThaliTest[841:950162] Resetting plugins due to page load.
,2015-11-20 12:59:02.480 ThaliTest[841:950162] Finished load of: file:///var/mobile/Containers/Bundle/Application/7F3C4D20-B74D-42AE-B19C-B2525333D8F5/ThaliTest.app/www/index.html
,2015-11-20 12:59:02.632 ThaliTest[841:950162] JXcore Cordova plugin initializing
,2015-11-20 12:59:02.633 ThaliTest[841:950353] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
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
,my name is : Apple-IpadAir2-1_PT7072
,attempting to connect to test coordinator
,check test folder
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
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
fo,und interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false,, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false,, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
fo,und interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
fo,und interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ct]
ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c90,8:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false,, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,found interfaceName: lo0
ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c90,8:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ct]
,ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"10000000\",\"conReTryTimeout\":\"1000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 55592
,2015-11-20 13:10:17.209 ThaliTest[841:950353] jxcore: startBroadcasting
,2015-11-20 13:10:17.216 ThaliTest[841:950353] server: starting Apple-IpadAir2-1_PT7072.5zbvNA==
,2015-11-20 13:10:17.218 ThaliTest[841:950353] multipeer session: start timer: 0x90c1d00
2015-11-20 13:10:17.218 ThaliTest[841:950353] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7072
2015-11-20 13:10:17.219 ThaliTest[841:950353] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-20T12:10:17.220Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-20 13:10:17.745 ThaliTest[841:950162] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:17.747Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:17.748Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:10:17.979 ThaliTest[841:950162] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:10:18.760 ThaliTest[841:950353] jxcore: disconnect
2015-11-20 13:10:18.761 ThaliTest[841:950353] jxcore: disconnect: fail
2015-11-20T12:10:18.761Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:18.761Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone6-1_PT2043.OU3s0w== with availability status: true
,2015-11-20T12:10:18.761Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:18.762Z SendDataConnector.js: do connect now
,2015-11-20 13:10:18.762 ThaliTest[841:950353] jxcore: connect Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:10:18.762 ThaliTest[841:950353] client session: connect
2015-11-20 13:10:18.763 ThaliTest[841:950353] client session: stateChange:0->1 Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:10:20.881 ThaliTest[841:950162] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2716.py/N2Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-20 13:10:23.641 ThaliTest[841:951659] client session: connected
2015-11-20 13:10:23.641 ThaliTest[841:951659] client session: stateChange:1->2 Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:10:23.642 ThaliTest[841:951659] client session: fireConnectCallback: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:10:23.642 ThaliTest[841:951659] jxcore: connect: success
,2015-11-20T12:10:23.643Z SendDataConnector.js: CLIENT connected to 55595, error: null
,2015-11-20T12:10:23.644Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:10:23.645 ThaliTest[841:950162] client: relay established
2015-11-20 13:10:23.645 ThaliTest[841:950162] client: new accepted socket: 0x90cca30
,2015-11-20T12:10:23.657Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:10:27.974Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:33.580Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:33.581Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-20T12:10:34.804Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:34.804Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-20T12:10:39.927Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:39.927Z SendDataConnector.js: CLIENT is data received : 1270000
,2015-11-20T12:10:40.386Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:40.386Z SendDataConnector.js: CLIENT is data received : 3960000
,2015-11-20T12:10:42.442Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:42.442Z SendDataConnector.js: CLIENT is data received : 5510000
,2015-11-20T12:10:43.762Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:43.762Z SendDataConnector.js: CLIENT is data received : 5520000
,2015-11-20T12:10:45.008Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:45.008Z SendDataConnector.js: CLIENT is data received : 6340000
,2015-11-20T12:10:45.448Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:45.449Z SendDataConnector.js: CLIENT is data received : 6690000
,2015-11-20T12:10:46.489Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:46.489Z SendDataConnector.js: CLIENT is data received : 6710000
,2015-11-20T12:10:47.008Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:47.009Z SendDataConnector.js: CLIENT is data received : 6760000
,2015-11-20T12:10:47.079Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:47.079Z SendDataConnector.js: CLIENT is data received : 7010000
,2015-11-20 13:10:47.219 ThaliTest[841:950162] multipeer session: restart
,2015-11-20 13:10:47.231 ThaliTest[841:950162] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:10:47.231 ThaliTest[841:950162] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:10:47.233 ThaliTest[841:950162] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:10:47.243Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:47.243Z SendDataConnector.js: CLIENT is data received : 7460000
,2015-11-20T12:10:47.364Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:47.364Z SendDataConnector.js: CLIENT is data received : 7730000
,2015-11-20T12:10:47.413Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:47.414Z SendDataConnector.js: CLIENT is data received : 8210000
,2015-11-20T12:10:47.498Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:47.498Z SendDataConnector.js: CLIENT is data received : 8430000
,2015-11-20T12:10:47.534Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:47.534Z SendDataConnector.js: CLIENT is data received : 8740000
,2015-11-20T12:10:47.547Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:10:47.548Z SendDataConnector.js: CLIENT is data received : 8860000
,2015-11-20T12:10:47.701Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20T12:10:47.702Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:10:47.702Z SendDataConnector.js: got all data for this round
,2015-11-20T12:10:47.703Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:10:47.703Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:10:47.704 ThaliTest[841:950353] jxcore: disconnect
2015-11-20 13:10:47.704 ThaliTest[841:950353] client session: disconnectFromPeer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:10:47.704 ThaliTest[841:950353] client session: disconnect
2015-11-20 13:10:47.704 ThaliTest[841:950353] client session: stateChange:2->0 Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:10:47.706 ThaliTest[841:950353] jxcore: disconnect: success
2015-11-20T12:10:47.707Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2043.OU3s0w==
,---- round done--------
device[2]: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:47.709Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:47.709Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:10:47.724Z SendDataConnector.js: CLIENT is closed
,2015-11-20 13:10:48.717 ThaliTest[841:950353] jxcore: disconnect
2015-11-20 13:10:48.717 ThaliTest[841:950353] jxcore: disconnect: fail
2015-11-20T12:10:48.717Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg==,
2015-11-20T12:10:48.717Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5s-1_PT497.PdI1bg== with availability status: true
2015-11-20T12:10:48.717Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:10:48.717Z SendDataConnector.js: do connect now
,2015-11-20 13:10:48.717 ThaliTest[841:950353] jxcore: connect Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:10:48.718 ThaliTest[841:950353] client session: connect
,2015-11-20 13:10:48.718 ThaliTest[841:950353] client session: stateChange:0->1 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:49.888 ThaliTest[841:950162] multipeer session: reset timer
2015-11-20 13:10:49.888 ThaliTest[841:950162] multipeer session: stop timer
2015-11-20 13:10:49.888 ThaliTest[841:950162] multipeer session: start timer: 0x90c1d00
2015-11-20 13:10:49.888 ThaliTest[841:950162] server session: connect
2015-11-20 13:10:49.888 ThaliTest[841:950162] server session: stateChange:0->1 Apple-Iphone5s-1_PT497
,2015-11-20 13:10:49.894 ThaliTest[841:950162] server: accepting invitation Apple-Iphone5s-1_PT497
,2015-11-20 13:10:50.007 ThaliTest[841:950162] multipeer session: reset timer
2015-11-20 13:10:50.007 ThaliTest[841:950162] multipeer session: stop timer
,2015-11-20 13:10:50.008 ThaliTest[841:950162] multipeer session: start timer: 0x90c1d00
2015-11-20 13:10:50.008 ThaliTest[841:950162] server session: connect
,2015-11-20 13:10:50.008 ThaliTest[841:950162] server session: stateChange:0->1 Apple-Iphone6-1_PT2043
,2015-11-20 13:10:50.011 ThaliTest[841:950162] server: accepting invitation Apple-Iphone6-1_PT2043
,2015-11-20 13:10:53.435 ThaliTest[841:951657] server session: connected
2015-11-20 13:10:53.435 ThaliTest[841:951657] server session: stateChange:1->2 Apple-Iphone6-1_PT2043
,2015-11-20 13:10:53.438 ThaliTest[841:950162] server relay: connected (to port: 55592)
,2015-11-20T12:10:53.442Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:10:58.082Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-11-20T12:10:58.096Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-11-20T12:10:58.135Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-11-20T12:10:58.148Z SendDataTCPServer.js: TCP/IP server has received 120450 bytes of data
,2015-11-20T12:10:58.161Z SendDataTCPServer.js: TCP/IP server has received 192720 bytes of data
,2015-11-20T12:10:58.176Z SendDataTCPServer.js: TCP/IP server has received 197100 bytes of data
,2015-11-20T12:10:58.262Z SendDataTCPServer.js: TCP/IP server has received 203670 bytes of data
,2015-11-20T12:10:58.689Z SendDataTCPServer.js: TCP/IP server has received 205860 bytes of data
,2015-11-20 13:10:58.801 ThaliTest[841:951659] client session: connected
2015-11-20 13:10:58.801 ThaliTest[841:951659] client session: stateChange:1->2 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:10:58.802 ThaliTest[841:951659] client session: fireConnectCallback: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:10:58.802 ThaliTest[841:951659] jxcore: connect: success
2015-11-20T12:10:58.803Z SendDataConnector.js: CLIENT connected to 55601, error: null
2015-11-20T12:10:58.803Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:10:58.804 ThaliTest[841:950162] client: relay established
2015-11-20 13:10:58.804 ThaliTest[841:950162] client: new accepted socket: 0x955f710
,2015-11-20T12:10:58.816Z SendDataTCPServer.js: TCP/IP server has received 214620 bytes of data
,2015-11-20T12:10:58.816Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:10:59.775 ThaliTest[841:951657] server session: connected
,2015-11-20 13:10:59.775 ThaliTest[841:951657] server session: stateChange:1->2 Apple-Iphone5s-1_PT497
,2015-11-20 13:10:59.783 ThaliTest[841:950162] server relay: connected (to port: 55592)
,2015-11-20T12:11:03.810Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:03.950Z SendDataTCPServer.js: TCP/IP server has received 345692 bytes of data
,2015-11-20T12:11:03.952Z SendDataTCPServer.js: TCP/IP server has received 476764 bytes of data
,2015-11-20T12:11:03.954Z SendDataTCPServer.js: TCP/IP server has received 607836 bytes of data
,2015-11-20T12:11:03.956Z SendDataTCPServer.js: TCP/IP server has received 738908 bytes of data
,2015-11-20T12:11:03.958Z SendDataTCPServer.js: TCP/IP server has received 869980 bytes of data
,2015-11-20T12:11:03.961Z SendDataTCPServer.js: TCP/IP server has received 1001052 bytes of data
,2015-11-20T12:11:03.963Z SendDataTCPServer.js: TCP/IP server has received 1132124 bytes of data
,2015-11-20T12:11:03.966Z SendDataTCPServer.js: TCP/IP server has received 1263196 bytes of data
,2015-11-20T12:11:03.969Z SendDataTCPServer.js: TCP/IP server has received 1394268 bytes of data
,2015-11-20T12:11:03.971Z SendDataTCPServer.js: TCP/IP server has received 1525340 bytes of data
,2015-11-20T12:11:03.975Z SendDataTCPServer.js: TCP/IP server has received 1656412 bytes of data
,2015-11-20T12:11:03.977Z SendDataTCPServer.js: TCP/IP server has received 1787484 bytes of data
,2015-11-20T12:11:03.979Z SendDataTCPServer.js: TCP/IP server has received 1918556 bytes of data
,2015-11-20T12:11:03.981Z SendDataTCPServer.js: TCP/IP server has received 1964146 bytes of data
,2015-11-20T12:11:03.982Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:11:03.997Z SendDataTCPServer.js: TCP/IP server has received 2095218 bytes of data
,2015-11-20T12:11:04.000Z SendDataTCPServer.js: TCP/IP server has received 2226290 bytes of data
,2015-11-20T12:11:04.002Z SendDataTCPServer.js: TCP/IP server has received 2357362 bytes of data
,2015-11-20T12:11:04.005Z SendDataTCPServer.js: TCP/IP server has received 2454848 bytes of data
,2015-11-20T12:11:04.019Z SendDataTCPServer.js: TCP/IP server has received 2585920 bytes of data
,2015-11-20T12:11:04.021Z SendDataTCPServer.js: TCP/IP server has received 2716992 bytes of data
,2015-11-20T12:11:04.023Z SendDataTCPServer.js: TCP/IP server has received 2848064 bytes of data
,2015-11-20T12:11:04.026Z SendDataTCPServer.js: TCP/IP server has received 2934600 bytes of data
,2015-11-20T12:11:04.041Z SendDataTCPServer.js: TCP/IP server has received 3065672 bytes of data
,2015-11-20T12:11:04.043Z SendDataTCPServer.js: TCP/IP server has received 3196744 bytes of data
,2015-11-20T12:11:04.045Z SendDataTCPServer.js: TCP/IP server has received 3327816 bytes of data
,2015-11-20T12:11:04.048Z SendDataTCPServer.js: TCP/IP server has received 3357128 bytes of data
,2015-11-20T12:11:04.061Z SendDataTCPServer.js: TCP/IP server has received 3488200 bytes of data
,2015-11-20T12:11:04.065Z SendDataTCPServer.js: TCP/IP server has received 3619272 bytes of data
,2015-11-20T12:11:04.067Z SendDataTCPServer.js: TCP/IP server has received 3740378 bytes of data
,2015-11-20T12:11:04.082Z SendDataTCPServer.js: TCP/IP server has received 3871450 bytes of data
,2015-11-20T12:11:04.086Z SendDataTCPServer.js: TCP/IP server has received 4002522 bytes of data
,2015-11-20T12:11:04.088Z SendDataTCPServer.js: TCP/IP server has received 4133594 bytes of data
,2015-11-20T12:11:04.090Z SendDataTCPServer.js: TCP/IP server has received 4264666 bytes of data
,2015-11-20T12:11:04.092Z SendDataTCPServer.js: TCP/IP server has received 4344960 bytes of data
,2015-11-20T12:11:04.106Z SendDataTCPServer.js: TCP/IP server has received 4476032 bytes of data
,2015-11-20T12:11:04.108Z SendDataTCPServer.js: TCP/IP server has received 4553010 bytes of data
,2015-11-20T12:11:05.100Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:05.100Z SendDataConnector.js: CLIENT is data received : 10000
2015-11-20T12:11:05.101Z SendDataTCPServer.js: TCP/IP server has received 4555058 bytes of data
,2015-11-20T12:11:15.109Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T12:11:15.110Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:11:15.110Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:11:15.111Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T12:11:15.112Z SendDataConnector.js: CLIENT is closed
,2015-11-20T12:11:16.117Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:16.117Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:17.122 ThaliTest[841:950353] jxcore: disconnect
,2015-11-20 13:11:17.123 ThaliTest[841:950353] client session: disconnectFromPeer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:11:17.123 ThaliTest[841:950353] client session: disconnect
2015-11-20 13:11:17.123 ThaliTest[841:950353] client session: stateChange:2->0 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:19.281 ThaliTest[841:950353] jxcore: disconnect: success
2015-11-20T12:11:19.282Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:19.282Z SendDataConnector.js: Connect (retry ,count 1) to peer Apple-Iphone5s-1_PT497.PdI1bg== with availability status: true
2015-11-20T12:11:19.282Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:19.282Z SendDataConnector.js: do connect now
2015-11-20 13:11:19.282 ThaliTest[841:950353] jxcore: connect Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:11:19.282 ThaliTest[841:950353] client session: connect
,2015-11-20 13:11:19.282 ThaliTest[841:950353] client session: stateChange:0->1 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:19.290Z SendDataTCPServer.js: TCP/IP server has received 2048 bytes of data
,2015-11-20T12:11:19.317Z SendDataTCPServer.js: TCP/IP server has received 90112 bytes of data
,2015-11-20T12:11:19.325Z SendDataTCPServer.js: TCP/IP server has received 4686130 bytes of data
,2015-11-20T12:11:19.330Z SendDataTCPServer.js: TCP/IP server has received 4817202 bytes of data
,2015-11-20T12:11:19.336Z SendDataTCPServer.js: TCP/IP server has received 4858162 bytes of data
,2015-11-20T12:11:19.360Z SendDataTCPServer.js: TCP/IP server has received 221184 bytes of data
,2015-11-20T12:11:19.366Z SendDataTCPServer.js: TCP/IP server has received 352256 bytes of data
,2015-11-20T12:11:19.369Z SendDataTCPServer.js: TCP/IP server has received 483328 bytes of data
,2015-11-20T12:11:19.373Z SendDataTCPServer.js: TCP/IP server has received 557056 bytes of data
,2015-11-20T12:11:19.374Z SendDataTCPServer.js: TCP/IP server has received 4989234 bytes of data
,2015-11-20T12:11:19.378Z SendDataTCPServer.js: TCP/IP server has received 5120306 bytes of data
,2015-11-20T12:11:19.380Z SendDataTCPServer.js: TCP/IP server has received 5148978 bytes of data
,2015-11-20T12:11:19.395Z SendDataTCPServer.js: TCP/IP server has received 688128 bytes of data
,2015-11-20T12:11:19.402Z SendDataTCPServer.js: TCP/IP server has received 738030 bytes of data
,2015-11-20T12:11:19.404Z SendDataTCPServer.js: TCP/IP server has received 5280050 bytes of data
,2015-11-20T12:11:19.410Z SendDataTCPServer.js: TCP/IP server has received 5411122 bytes of data
,2015-11-20T12:11:19.413Z SendDataTCPServer.js: TCP/IP server has received 5542194 bytes of data
,2015-11-20T12:11:19.415Z SendDataTCPServer.js: TCP/IP server has received 5609778 bytes of data
,2015-11-20T12:11:19.441Z SendDataTCPServer.js: TCP/IP server has received 755266 bytes of data
,2015-11-20T12:11:19.442Z SendDataTCPServer.js: TCP/IP server has received 5740850 bytes of data
,2015-11-20T12:11:19.449Z SendDataTCPServer.js: TCP/IP server has received 5871922 bytes of data
,2015-11-20T12:11:19.456Z SendDataTCPServer.js: TCP/IP server has received 6002994 bytes of data
,2015-11-20T12:11:19.459Z SendDataTCPServer.js: TCP/IP server has received 6134066 bytes of data
,2015-11-20T12:11:19.462Z SendDataTCPServer.js: TCP/IP server has received 6265138 bytes of data
,2015-11-20T12:11:19.468Z SendDataTCPServer.js: TCP/IP server has received 6396210 bytes of data
,2015-11-20T12:11:19.478Z SendDataTCPServer.js: TCP/IP server has received 6527282 bytes of data
,2015-11-20T12:11:19.485Z SendDataTCPServer.js: TCP/IP server has received 6658354 bytes of data
,2015-11-20T12:11:19.488Z SendDataTCPServer.js: TCP/IP server has received 6789426 bytes of data
,2015-11-20T12:11:19.491Z SendDataTCPServer.js: TCP/IP server has received 6920498 bytes of data
,2015-11-20T12:11:19.497Z SendDataTCPServer.js: TCP/IP server has received 7051570 bytes of data
,2015-11-20T12:11:19.502Z SendDataTCPServer.js: TCP/IP server has received 7182642 bytes of data
,2015-11-20T12:11:19.506Z SendDataTCPServer.js: TCP/IP server has received 7313714 bytes of data
,2015-11-20T12:11:19.509Z SendDataTCPServer.js: TCP/IP server has received 7444786 bytes of data
,2015-11-20T12:11:19.512Z SendDataTCPServer.js: TCP/IP server has received 7575858 bytes of data
,2015-11-20T12:11:19.517Z SendDataTCPServer.js: TCP/IP server has received 7678140 bytes of data
,2015-11-20T12:11:19.535Z SendDataTCPServer.js: TCP/IP server has received 770880 bytes of data
,2015-11-20T12:11:19.623Z SendDataTCPServer.js: TCP/IP server has received 7686900 bytes of data
,2015-11-20T12:11:19.638Z SendDataTCPServer.js: TCP/IP server has received 7702230 bytes of data
,2015-11-20T12:11:19.654Z SendDataTCPServer.js: TCP/IP server has received 7743840 bytes of data
,2015-11-20T12:11:19.670Z SendDataTCPServer.js: TCP/IP server has received 7778880 bytes of data
,2015-11-20T12:11:19.685Z SendDataTCPServer.js: TCP/IP server has received 7811730 bytes of data
,2015-11-20T12:11:19.699Z SendDataTCPServer.js: TCP/IP server has received 7816110 bytes of data
,2015-11-20T12:11:19.700Z SendDataTCPServer.js: TCP/IP server has received 784020 bytes of data
,2015-11-20T12:11:19.712Z SendDataTCPServer.js: TCP/IP server has received 843008 bytes of data
,2015-11-20T12:11:19.727Z SendDataTCPServer.js: TCP/IP server has received 878190 bytes of data
,2015-11-20T12:11:19.743Z SendDataTCPServer.js: TCP/IP server has received 7919040 bytes of data
,2015-11-20T12:11:19.759Z SendDataTCPServer.js: TCP/IP server has received 7956270 bytes of data
,2015-11-20T12:11:19.761Z SendDataTCPServer.js: TCP/IP server has received 900090 bytes of data
,2015-11-20T12:11:19.774Z SendDataTCPServer.js: TCP/IP server has received 7986646 bytes of data
,2015-11-20T12:11:19.777Z SendDataTCPServer.js: TCP/IP server has received 935130 bytes of data
,2015-11-20 13:11:19.788 ThaliTest[841:951837] server session: not connected Apple-Iphone5s-1_PT497
,2015-11-20T12:11:19.793Z SendDataTCPServer.js: TCP/IP server has received 8087670 bytes of data
,2015-11-20T12:11:19.807Z SendDataTCPServer.js: TCP/IP server has received 8181840 bytes of data
,2015-11-20T12:11:19.824Z SendDataTCPServer.js: TCP/IP server has received 8247540 bytes of data
,2015-11-20 13:11:19.830 ThaliTest[841:951837] server session: not connected Apple-Iphone6-1_PT2043
,2015-11-20 13:11:19.893 ThaliTest[841:950162] multipeer session: reset timer
,2015-11-20 13:11:19.893 ThaliTest[841:950162] multipeer session: stop timer
2015-11-20 13:11:19.894 ThaliTest[841:950162] multipeer session: start timer: 0x90c1d00
,2015-11-20 13:11:19.894 ThaliTest[841:950162] server: disconnecting to refresh session (Apple-Iphone6-1_PT2043)
2015-11-20 13:11:19.894 ThaliTest[841:950162] server session: disconnect
2015-11-20 13:11:19.894 ThaliTest[841:950162] server session: stateChange:2->0 Apple-Iphone6-1_PT2043
,2015-11-20 13:11:19.896 ThaliTest[841:950162] server session: connect
2015-11-20 13:11:19.896 ThaliTest[841:950162] server session: stateChange:0->1 Apple-Iphone6-1_PT2043
,2015-11-20 13:11:19.899 ThaliTest[841:950162] server: accepting invitation Apple-Iphone6-1_PT2043
2015-11-20T12:11:19.900Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-20T12:11:19.901Z SendDataTCPServer.js: TCP/IP server is close
,2015-11-20 13:11:20.178 ThaliTest[841:950162] multipeer session: reset timer
2015-11-20 13:11:20.178 ThaliTest[841:950162] multipeer session: stop timer
2015-11-20 13:11:20.178 ThaliTest[841:950162] multipeer session: start timer: 0x90c1d00
2015-11-20 1,3:11:20.178 ThaliTest[841:950162] server: disconnecting to refresh session (Apple-Iphone5s-1_PT497)
2015-11-20 13:11:20.178 ThaliTest[841:950162] server session: disconnect
2015-11-20 13:11:20.178 ThaliTest[841:950162] server session: stateChange:2->0 Apple-Iphone5s-1_PT497
,2015-11-20 13:11:20.181 ThaliTest[841:950162] server session: connect
2015-11-20 13:11:20.181 ThaliTest[841:950162] server session: stateChange:0->1 Apple-Iphone5s-1_PT497
,2015-11-20T12:11:20.184Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-20T12:11:20.185Z SendDataTCPServer.js: TCP/IP server is close
2015-11-20 13:11:20.191 ThaliTest[841:950162] server: accepting invitation Apple-Iphone5s-1_PT497
,2015-11-20 13:11:22.855 ThaliTest[841:951659] server session: connected
2015-11-20 13:11:22.855 ThaliTest[841:951659] server session: stateChange:1->2 Apple-Iphone6-1_PT2043
,2015-11-20 13:11:22.858 ThaliTest[841:950162] server relay: connected (to port: 55592)
,2015-11-20T12:11:22.869Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:11:23.246 ThaliTest[841:951837] client session: connected
2015-11-20 13:11:23.246 ThaliTest[841:951837] client session: stateChange:1->2 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:23.305 ThaliTest[841:951837] client session: fireConnectCallback: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:11:23.305 ThaliTest[841:951837] jxcore: connect: success
,2015-11-20T12:11:23.305Z SendDataConnector.js: CLIENT connected to 55607, error: null
2015-11-20T12:11:23.306Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:11:23.307 ThaliTest[841:950162] client: relay established
2015-11-20 13:11:23.307 ThaliTest[841:950162] client: new accepted socket: 0x95d7250
,2015-11-20T12:11:23.319Z SendDataConnector.js: CLIENT now sending 9990000 bytes of data
,2015-11-20 13:11:23.366 ThaliTest[841:951841] server session: connected
2015-11-20 13:11:23.366 ThaliTest[841:951841] server session: stateChange:1->2 Apple-Iphone5s-1_PT497
,2015-11-20 13:11:23.367 ThaliTest[841:950162] server relay: connected (to port: 55592)
,2015-11-20T12:11:27.714Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:27.828Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:11:27.829Z SendDataTCPServer.js: TCP/IP server has received 131072 bytes of data
,2015-11-20T12:11:27.831Z SendDataTCPServer.js: TCP/IP server has received 208050 bytes of data
,2015-11-20T12:11:28.822Z SendDataTCPServer.js: TCP/IP server has received 55296 bytes of data
,2015-11-20T12:11:28.825Z SendDataTCPServer.js: TCP/IP server has received 263346 bytes of data
,2015-11-20T12:11:29.340Z SendDataTCPServer.js: TCP/IP server has received 69632 bytes of data
,2015-11-20T12:11:29.341Z SendDataTCPServer.js: TCP/IP server has received 277682 bytes of data
,2015-11-20T12:11:29.341Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:29.342Z SendDataConnector.js: CLIENT is data received : 450000
,2015-11-20 13:11:33.578 ThaliTest[841:950162] client: lost peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:11:33.578 ThaliTest[841:950162] client session: onPeerLost: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:11:33.580Z SendDataTCPServer.js: TCP/IP server has received 77824 bytes of data
2015-11-20T12:11:33.581Z SendDataTCPServer.js: TCP/IP server has received 285874 bytes of data
2015-11-20T12:11:33.581Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:33.582Z SendDataConnector.js: CLIENT is data received : 470000
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":false}]
,2015-11-20T12:11:34.101Z SendDataTCPServer.js: TCP/IP server has received 79872 bytes of data
2015-11-20T12:11:34.102Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:34.102Z SendDataConnector.js: CLIENT is data received : 520000
,2015-11-20T12:11:34.103Z SendDataTCPServer.js: TCP/IP server has received 287922 bytes of data
,2015-11-20T12:11:34.639Z SendDataTCPServer.js: TCP/IP server has received 90112 bytes of data
,2015-11-20T12:11:34.640Z SendDataTCPServer.js: TCP/IP server has received 298162 bytes of data
,2015-11-20T12:11:39.601Z SendDataTCPServer.js: TCP/IP server has received 94208 bytes of data
,2015-11-20T12:11:39.602Z SendDataTCPServer.js: TCP/IP server has received 302258 bytes of data
,2015-11-20T12:11:39.602Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:39.603Z SendDataConnector.js: CLIENT is data received : 580000
,2015-11-20T12:11:39.626Z SendDataTCPServer.js: TCP/IP server has received 304306 bytes of data
,2015-11-20T12:11:39.627Z SendDataTCPServer.js: TCP/IP server has received 96256 bytes of data
,2015-11-20 13:11:39.698 ThaliTest[841:950162] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:11:39.702Z SendDataTCPServer.js: TCP/IP server has received 98304 bytes of data
,2015-11-20T12:11:39.702Z SendDataTCPServer.js: TCP/IP server has received 306354 bytes of data
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
,2015-11-20T12:11:40.654Z SendDataTCPServer.js: TCP/IP server has received 308402 bytes of data
,2015-11-20T12:11:40.655Z SendDataTCPServer.js: TCP/IP server has received 100352 bytes of data
,2015-11-20 13:11:41.652 ThaliTest[841:951837] server session: not connected Apple-Iphone5s-1_PT497
,2015-11-20T12:11:41.725Z SendDataTCPServer.js: TCP/IP server has received 316594 bytes of data
,2015-11-20T12:11:41.726Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:41.726Z SendDataConnector.js: CLIENT is data received : 3760000
,2015-11-20T12:11:41.726Z SendDataTCPServer.js: TCP/IP server has received 108544 bytes of data
,2015-11-20T12:11:41.749Z SendDataTCPServer.js: TCP/IP server has received 373938 bytes of data
,2015-11-20T12:11:41.751Z SendDataTCPServer.js: TCP/IP server has received 167936 bytes of data
,2015-11-20T12:11:41.764Z SendDataTCPServer.js: TCP/IP server has received 375986 bytes of data
2015-11-20T12:11:41.764Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:41.765Z SendDataConnector.js: CLIENT is data received : 3770000
,2015-11-20T12:11:41.910Z SendDataTCPServer.js: TCP/IP server has received 380082 bytes of data
,2015-11-20T12:11:41.911Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:41.912Z SendDataConnector.js: CLIENT is data received : 4610000
2015-11-20T12:11:41.912Z SendDataTCPServer.js: TCP/IP server has received 184320 bytes of data
,2015-11-20T12:11:41.925Z SendDataTCPServer.js: TCP/IP server has received 416946 bytes of data
,2015-11-20T12:11:41.926Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:41.927Z SendDataConnector.js: CLIENT is data received : 4630000
,2015-11-20T12:11:41.927Z SendDataTCPServer.js: TCP/IP server has received 208896 bytes of data
,2015-11-20T12:11:42.885Z SendDataTCPServer.js: TCP/IP server has received 418994 bytes of data
,2015-11-20T12:11:42.886Z SendDataTCPServer.js: TCP/IP server has received 210944 bytes of data
,2015-11-20T12:11:42.886Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:42.887Z SendDataConnector.js: CLIENT is data received : 6280000
,2015-11-20T12:11:43.376Z SendDataTCPServer.js: TCP/IP server has received 421042 bytes of data
2015-11-20T12:11:43.376Z SendDataTCPServer.js: TCP/IP server has received 212992 bytes of data
,2015-11-20T12:11:43.377Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:43.377Z SendDataConnector.js: CLIENT is data received : 6560000
,2015-11-20T12:11:43.999Z SendDataTCPServer.js: TCP/IP server has received 231424 bytes of data
,2015-11-20T12:11:44.001Z SendDataTCPServer.js: TCP/IP server has received 474290 bytes of data
,2015-11-20T12:11:44.002Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:44.003Z SendDataConnector.js: CLIENT is data received : 7570000
,2015-11-20T12:11:44.015Z SendDataTCPServer.js: TCP/IP server has received 560306 bytes of data
,2015-11-20T12:11:44.566Z SendDataTCPServer.js: TCP/IP server has received 568498 bytes of data
2015-11-20T12:11:44.566Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:44.567Z SendDataConnector.js: CLIENT is data received : 8120000
,2015-11-20 13:11:45.348 ThaliTest[841:950162] multipeer session: reset timer
2015-11-20 13:11:45.349 ThaliTest[841:950162] multipeer session: stop timer
2015-11-20 13:11:45.349 ThaliTest[841:950162] multipeer session: start timer: 0x90c1d00
2015-11-20 13:11:45.349 ThaliTest[841:950162] server: disconnecting to refresh session (Apple-Iphone5s-1_PT497)
2015-11-20 13:11:45.349 ThaliTest[841:950162] server session: disconnect
2015-11-20 13:11:45.350 ThaliTest[841:950162] server session: stateChange:2->0 Apple-Iphone5s-1_PT497
,2015-11-20T12:11:45.356Z SendDataTCPServer.js: TCP/IP server has received 593074 bytes of data
,2015-11-20T12:11:45.357Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:45.357Z SendDataConnector.js: CLIENT is data received : 8900000
,2015-11-20T12:11:45.358Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20T12:11:45.358Z SendDataTCPServer.js: TCP/IP server is close
,2015-11-20 13:11:45.406 ThaliTest[841:950162] server session: connect
2015-11-20 13:11:45.407 ThaliTest[841:950162] server session: stateChange:0->1 Apple-Iphone5s-1_PT497
,2015-11-20 13:11:45.410 ThaliTest[841:950162] server: accepting invitation Apple-Iphone5s-1_PT497
,2015-11-20T12:11:45.419Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:45.419Z SendDataConnector.js: CLIENT is data received : 8940000
,2015-11-20T12:11:45.628Z SendDataTCPServer.js: TCP/IP server has received 601266 bytes of data
,2015-11-20T12:11:45.629Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:45.630Z SendDataConnector.js: CLIENT is data received : 9290000
,2015-11-20T12:11:46.133Z SendDataTCPServer.js: TCP/IP server has received 681138 bytes of data
,2015-11-20T12:11:46.140Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:46.140Z SendDataConnector.js: CLIENT is data received : 9710000
,2015-11-20T12:11:46.156Z SendDataTCPServer.js: TCP/IP server has received 812210 bytes of data
,2015-11-20T12:11:46.160Z SendDataTCPServer.js: TCP/IP server has received 943282 bytes of data
,2015-11-20T12:11:46.166Z SendDataTCPServer.js: TCP/IP server has received 1074354 bytes of data
,2015-11-20T12:11:46.170Z SendDataTCPServer.js: TCP/IP server has received 1205426 bytes of data
,2015-11-20T12:11:46.175Z SendDataTCPServer.js: TCP/IP server has received 1336498 bytes of data
,2015-11-20T12:11:46.178Z SendDataTCPServer.js: TCP/IP server has received 1467570 bytes of data
,2015-11-20T12:11:46.181Z SendDataTCPServer.js: TCP/IP server has received 1598642 bytes of data
,2015-11-20T12:11:46.184Z SendDataTCPServer.js: TCP/IP server has received 1649842 bytes of data
,2015-11-20T12:11:46.186Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:46.187Z SendDataConnector.js: CLIENT is data received : 9800000
,2015-11-20T12:11:46.201Z SendDataTCPServer.js: TCP/IP server has received 1780914 bytes of data
,2015-11-20T12:11:46.203Z SendDataTCPServer.js: TCP/IP server has received 1911986 bytes of data
,2015-11-20T12:11:46.205Z SendDataTCPServer.js: TCP/IP server has received 2012338 bytes of data
,2015-11-20T12:11:46.220Z SendDataTCPServer.js: TCP/IP server has received 2143410 bytes of data
,2015-11-20T12:11:46.223Z SendDataTCPServer.js: TCP/IP server has received 2274482 bytes of data
,2015-11-20T12:11:46.227Z SendDataTCPServer.js: TCP/IP server has received 2405554 bytes of data
,2015-11-20T12:11:46.229Z SendDataTCPServer.js: TCP/IP server has received 2536626 bytes of data
,2015-11-20T12:11:46.232Z SendDataTCPServer.js: TCP/IP server has received 2667698 bytes of data
,2015-11-20T12:11:46.237Z SendDataTCPServer.js: TCP/IP server has received 2798770 bytes of data
,2015-11-20T12:11:46.240Z SendDataTCPServer.js: TCP/IP server has received 2929842 bytes of data
,2015-11-20T12:11:46.243Z SendDataTCPServer.js: TCP/IP server has received 3001522 bytes of data
,2015-11-20T12:11:46.259Z SendDataTCPServer.js: TCP/IP server has received 3132594 bytes of data
,2015-11-20T12:11:46.265Z SendDataTCPServer.js: TCP/IP server has received 3263666 bytes of data
,2015-11-20T12:11:46.267Z SendDataTCPServer.js: TCP/IP server has received 3394738 bytes of data
,2015-11-20T12:11:46.269Z SendDataTCPServer.js: TCP/IP server has received 3525810 bytes of data
,2015-11-20T12:11:46.271Z SendDataTCPServer.js: TCP/IP server has received 3656882 bytes of data
,2015-11-20T12:11:46.274Z SendDataTCPServer.js: TCP/IP server has received 3787954 bytes of data
,2015-11-20T12:11:46.279Z SendDataTCPServer.js: TCP/IP server has received 3919026 bytes of data
,2015-11-20T12:11:46.283Z SendDataTCPServer.js: TCP/IP server has received 4041906 bytes of data
,2015-11-20T12:11:46.300Z SendDataTCPServer.js: TCP/IP server has received 4172978 bytes of data
,2015-11-20T12:11:46.303Z SendDataTCPServer.js: TCP/IP server has received 4304050 bytes of data
,2015-11-20T12:11:46.307Z SendDataTCPServer.js: TCP/IP server has received 4435122 bytes of data
,2015-11-20T12:11:46.313Z SendDataTCPServer.js: TCP/IP server has received 4566194 bytes of data
,2015-11-20T12:11:46.315Z SendDataTCPServer.js: TCP/IP server has received 4697266 bytes of data
,2015-11-20T12:11:46.318Z SendDataTCPServer.js: TCP/IP server has received 4828338 bytes of data
,2015-11-20T12:11:46.322Z SendDataTCPServer.js: TCP/IP server has received 4959410 bytes of data
,2015-11-20T12:11:46.325Z SendDataTCPServer.js: TCP/IP server has received 5090482 bytes of data
,2015-11-20T12:11:46.327Z SendDataTCPServer.js: TCP/IP server has received 5164210 bytes of data
,2015-11-20T12:11:46.343Z SendDataTCPServer.js: TCP/IP server has received 5295282 bytes of data
,2015-11-20T12:11:46.346Z SendDataTCPServer.js: TCP/IP server has received 5426354 bytes of data
,2015-11-20T12:11:46.350Z SendDataTCPServer.js: TCP/IP server has received 5557426 bytes of data
,2015-11-20T12:11:46.353Z SendDataTCPServer.js: TCP/IP server has received 5688498 bytes of data
,2015-11-20T12:11:46.357Z SendDataTCPServer.js: TCP/IP server has received 5819570 bytes of data
,2015-11-20T12:11:46.359Z SendDataTCPServer.js: TCP/IP server has received 5950642 bytes of data
,2015-11-20T12:11:46.361Z SendDataTCPServer.js: TCP/IP server has received 6081714 bytes of data
,2015-11-20T12:11:46.365Z SendDataTCPServer.js: TCP/IP server has received 6212786 bytes of data
,2015-11-20T12:11:46.368Z SendDataTCPServer.js: TCP/IP server has received 6319282 bytes of data
,2015-11-20T12:11:46.389Z SendDataTCPServer.js: TCP/IP server has received 6450354 bytes of data
,2015-11-20T12:11:46.392Z SendDataTCPServer.js: TCP/IP server has received 6581426 bytes of data
,2015-11-20T12:11:46.394Z SendDataTCPServer.js: TCP/IP server has received 6640818 bytes of data
,2015-11-20T12:11:46.395Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:46.395Z SendDataConnector.js: CLIENT is data received : 9940000
,2015-11-20T12:11:46.407Z SendDataTCPServer.js: TCP/IP server has received 6749362 bytes of data
,2015-11-20T12:11:46.410Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20T12:11:46.410Z SendDataConnector.js: CLIENT is data received : 9980000
,2015-11-20T12:11:46.423Z SendDataTCPServer.js: TCP/IP server has received 6880434 bytes of data
,2015-11-20T12:11:46.426Z SendDataTCPServer.js: TCP/IP server has received 7011506 bytes of data
,2015-11-20T12:11:46.429Z SendDataTCPServer.js: TCP/IP server has received 7142578 bytes of data
,2015-11-20T12:11:46.439Z SendDataTCPServer.js: TCP/IP server has received 7273650 bytes of data
,2015-11-20T12:11:46.444Z SendDataTCPServer.js: TCP/IP server has received 7404722 bytes of data
,2015-11-20T12:11:46.448Z SendDataTCPServer.js: TCP/IP server has received 7535794 bytes of data
,2015-11-20T12:11:46.451Z SendDataTCPServer.js: TCP/IP server has received 7666866 bytes of data
,2015-11-20T12:11:46.455Z SendDataTCPServer.js: TCP/IP server has received 7797938 bytes of data
,2015-11-20T12:11:46.457Z SendDataTCPServer.js: TCP/IP server has received 7929010 bytes of data
,2015-11-20T12:11:46.461Z SendDataTCPServer.js: TCP/IP server has received 8060082 bytes of data
,2015-11-20T12:11:46.463Z SendDataTCPServer.js: TCP/IP server has received 8191154 bytes of data
,2015-11-20T12:11:46.466Z SendDataTCPServer.js: TCP/IP server has received 8295602 bytes of data
,2015-11-20T12:11:46.468Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:11:46.469Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:11:46.469Z SendDataConnector.js: got all data for this round
,2015-11-20T12:11:46.470Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:11:46.470Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:11:46.471 ThaliTest[841:950353] jxcore: disconnect
,2015-11-20 13:11:46.472 ThaliTest[841:950353] client session: disconnectFromPeer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:46.472 ThaliTest[841:950353] client session: disconnect
,2015-11-20 13:11:46.473 ThaliTest[841:950353] client session: stateChange:2->0 Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:11:46.485 ThaliTest[841:950353] jxcore: disconnect: success
,2015-11-20T12:11:46.486Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT497.PdI1bg==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:11:46.490Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:11:46.491Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:11:46.506Z SendDataTCPServer.js: TCP/IP server has received 8426674 bytes of data
,2015-11-20T12:11:46.513Z SendDataTCPServer.js: TCP/IP server has received 8557746 bytes of data
,2015-11-20T12:11:46.529Z SendDataTCPServer.js: TCP/IP server has received 8688818 bytes of data
,2015-11-20T12:11:46.537Z SendDataTCPServer.js: TCP/IP server has received 8819890 bytes of data
,2015-11-20T12:11:46.543Z SendDataTCPServer.js: TCP/IP server has received 8950962 bytes of data
,2015-11-20T12:11:46.552Z SendDataTCPServer.js: TCP/IP server has received 9082034 bytes of data
,2015-11-20T12:11:46.558Z SendDataTCPServer.js: TCP/IP server has received 9213106 bytes of data
,2015-11-20T12:11:46.564Z SendDataTCPServer.js: TCP/IP server has received 9344178 bytes of data
,2015-11-20T12:11:46.570Z SendDataTCPServer.js: TCP/IP server has received 9475250 bytes of data
,2015-11-20T12:11:46.576Z SendDataTCPServer.js: TCP/IP server has received 9606322 bytes of data
,2015-11-20T12:11:46.583Z SendDataTCPServer.js: TCP/IP server has received 9737394 bytes of data
,2015-11-20T12:11:46.589Z SendDataTCPServer.js: TCP/IP server has received 9790002 bytes of data
,2015-11-20T12:11:46.592Z SendDataConnector.js: CLIENT is closed
,2015-11-20 13:11:46.673 ThaliTest[841:951830] server session: not connected Apple-Iphone6-1_PT2043
,2015-11-20 13:11:47.492 ThaliTest[841:950353] jxcore: disconnect
2015-11-20 13:11:47.492 ThaliTest[841:950353] jxcore: disconnect: fail
2015-11-20T12:11:47.492Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:11:47.492Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5-1_PT2716.py/N2Q== with availability status: true
2015-11-20T12:11:47.492Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:11:47.492Z SendDataConnector.js: do connect now
,2015-11-20 13:11:47.493 ThaliTest[841:950353] jxcore: connect Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:11:47.493 ThaliTest[841:950353] client session: connect
2015-11-20 13:11:47.493 ThaliTest[841:950353] client session: stateChange:0->1 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:11:48.561 ThaliTest[841:951734] server session: connected
2015-11-20 13:11:48.562 ThaliTest[841:951734] server session: stateChange:1->2 Apple-Iphone5s-1_PT497
,2015-11-20 13:11:48.563 ThaliTest[841:950162] server relay: connected (to port: 55592)
,2015-11-20T12:11:48.564Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:11:53.758 ThaliTest[841:950162] client: lost peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:11:53.758 ThaliTest[841:950162] client session: onPeerLost: Apple-Iphone6-1_PT2043.OU3s0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:11:54.311 ThaliTest[841:950162] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
,2015-11-20T12:11:54.781Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-11-20T12:11:54.796Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-11-20T12:11:54.832Z SendDataTCPServer.js: TCP/IP server has received 100740 bytes of data
,2015-11-20T12:11:54.846Z SendDataTCPServer.js: TCP/IP server has received 179580 bytes of data
,2015-11-20T12:11:54.859Z SendDataTCPServer.js: TCP/IP server has received 234330 bytes of data
,2015-11-20T12:11:54.874Z SendDataTCPServer.js: TCP/IP server has received 328500 bytes of data
,2015-11-20T12:11:54.889Z SendDataTCPServer.js: TCP/IP server has received 363540 bytes of data
,2015-11-20T12:11:55.337Z SendDataTCPServer.js: TCP/IP server has received 494612 bytes of data
,2015-11-20T12:11:55.340Z SendDataTCPServer.js: TCP/IP server has received 503700 bytes of data
,2015-11-20T12:11:55.365Z SendDataTCPServer.js: TCP/IP server has received 534360 bytes of data
,2015-11-20T12:11:55.379Z SendDataTCPServer.js: TCP/IP server has received 591300 bytes of data
,2015-11-20T12:11:55.395Z SendDataTCPServer.js: TCP/IP server has received 641670 bytes of data
,2015-11-20T12:11:55.409Z SendDataTCPServer.js: TCP/IP server has received 654810 bytes of data
,2015-11-20T12:11:55.422Z SendDataTCPServer.js: TCP/IP server has received 685470 bytes of data
,2015-11-20T12:11:55.437Z SendDataTCPServer.js: TCP/IP server has received 733650 bytes of data
,2015-11-20T12:11:55.450Z SendDataTCPServer.js: TCP/IP server has received 759930 bytes of data
,2015-11-20T12:11:55.464Z SendDataTCPServer.js: TCP/IP server has received 816870 bytes of data
,2015-11-20T12:11:55.480Z SendDataTCPServer.js: TCP/IP server has received 895710 bytes of data
,2015-11-20T12:11:55.495Z SendDataTCPServer.js: TCP/IP server has received 957030 bytes of data
,2015-11-20T12:11:55.509Z SendDataTCPServer.js: TCP/IP server has received 1016160 bytes of data
,2015-11-20T12:11:55.524Z SendDataTCPServer.js: TCP/IP server has received 1022730 bytes of data
,2015-11-20T12:11:55.548Z SendDataTCPServer.js: TCP/IP server has received 1055580 bytes of data
,2015-11-20T12:11:55.562Z SendDataTCPServer.js: TCP/IP server has received 1066530 bytes of data
,2015-11-20T12:11:55.573Z SendDataTCPServer.js: TCP/IP server has received 1103760 bytes of data
,2015-11-20T12:11:55.586Z SendDataTCPServer.js: TCP/IP server has received 1182600 bytes of data
,2015-11-20T12:11:55.601Z SendDataTCPServer.js: TCP/IP server has received 1224210 bytes of data
,2015-11-20T12:11:55.761Z SendDataTCPServer.js: TCP/IP server has received 1250490 bytes of data
,2015-11-20T12:11:55.835Z SendDataTCPServer.js: TCP/IP server has received 1294290 bytes of data
,2015-11-20T12:11:55.848Z SendDataTCPServer.js: TCP/IP server has received 1327140 bytes of data
,2015-11-20T12:11:55.861Z SendDataTCPServer.js: TCP/IP server has received 1405980 bytes of data
,2015-11-20T12:11:55.878Z SendDataTCPServer.js: TCP/IP server has received 1447590 bytes of data
,2015-11-20T12:11:55.891Z SendDataTCPServer.js: TCP/IP server has received 1489200 bytes of data
,2015-11-20T12:11:55.903Z SendDataTCPServer.js: TCP/IP server has received 1541760 bytes of data
,2015-11-20T12:11:55.917Z SendDataTCPServer.js: TCP/IP server has received 1609650 bytes of data
,2015-11-20T12:11:55.931Z SendDataTCPServer.js: TCP/IP server has received 1673160 bytes of data
,2015-11-20T12:11:55.945Z SendDataTCPServer.js: TCP/IP server has received 1723530 bytes of data
,2015-11-20T12:11:55.959Z SendDataTCPServer.js: TCP/IP server has received 1773900 bytes of data
,2015-11-20T12:11:55.974Z SendDataTCPServer.js: TCP/IP server has received 1815510 bytes of data
,2015-11-20T12:11:55.989Z SendDataTCPServer.js: TCP/IP server has received 1876830 bytes of data
,2015-11-20T12:11:56.004Z SendDataTCPServer.js: TCP/IP server has received 1944578 bytes of data
,2015-11-20T12:11:56.016Z SendDataTCPServer.js: TCP/IP server has received 2001660 bytes of data
,2015-11-20T12:11:56.028Z SendDataTCPServer.js: TCP/IP server has received 2060790 bytes of data
,2015-11-20T12:11:56.042Z SendDataTCPServer.js: TCP/IP server has received 2135250 bytes of data
,2015-11-20T12:11:56.057Z SendDataTCPServer.js: TCP/IP server has received 2194380 bytes of data
,2015-11-20T12:11:56.069Z SendDataTCPServer.js: TCP/IP server has received 2240370 bytes of data
,2015-11-20T12:11:56.081Z SendDataTCPServer.js: TCP/IP server has received 2284170 bytes of data
,2015-11-20T12:11:56.095Z SendDataTCPServer.js: TCP/IP server has received 2306070 bytes of data
,2015-11-20T12:11:56.265Z SendDataTCPServer.js: TCP/IP server has received 2352060 bytes of data
,2015-11-20T12:11:56.281Z SendDataTCPServer.js: TCP/IP server has received 2444040 bytes of data
,2015-11-20T12:11:56.294Z SendDataTCPServer.js: TCP/IP server has received 2472510 bytes of data
,2015-11-20T12:11:56.308Z SendDataTCPServer.js: TCP/IP server has received 2542590 bytes of data
,2015-11-20T12:11:56.323Z SendDataTCPServer.js: TCP/IP server has received 2614860 bytes of data
,2015-11-20T12:11:56.350Z SendDataTCPServer.js: TCP/IP server has received 2671800 bytes of data
,2015-11-20T12:11:56.366Z SendDataTCPServer.js: TCP/IP server has received 2765970 bytes of data
,2015-11-20T12:11:56.381Z SendDataTCPServer.js: TCP/IP server has received 2796630 bytes of data
,2015-11-20T12:11:56.407Z SendDataTCPServer.js: TCP/IP server has received 2803200 bytes of data
,2015-11-20T12:11:56.420Z SendDataTCPServer.js: TCP/IP server has received 2833860 bytes of data
,2015-11-20T12:11:56.434Z SendDataTCPServer.js: TCP/IP server has received 2908320 bytes of data
,2015-11-20T12:11:56.450Z SendDataTCPServer.js: TCP/IP server has received 3009060 bytes of data
,2015-11-20T12:11:56.465Z SendDataTCPServer.js: TCP/IP server has received 3050670 bytes of data
,2015-11-20T12:11:56.479Z SendDataTCPServer.js: TCP/IP server has received 3072570 bytes of data
,2015-11-20T12:11:56.492Z SendDataTCPServer.js: TCP/IP server has received 3136080 bytes of data
,2015-11-20T12:11:56.505Z SendDataTCPServer.js: TCP/IP server has received 3232440 bytes of data
,2015-11-20T12:11:56.521Z SendDataTCPServer.js: TCP/IP server has received 3293760 bytes of data
,2015-11-20T12:11:56.534Z SendDataTCPServer.js: TCP/IP server has received 3324420 bytes of data
,2015-11-20T12:11:56.548Z SendDataTCPServer.js: TCP/IP server has received 3337560 bytes of data
,2015-11-20T12:11:56.561Z SendDataTCPServer.js: TCP/IP server has received 3396690 bytes of data
,2015-11-20T12:11:56.575Z SendDataTCPServer.js: TCP/IP server has received 3431730 bytes of data
,2015-11-20T12:11:56.592Z SendDataTCPServer.js: TCP/IP server has received 3488386 bytes of data
,2015-11-20T12:11:56.607Z SendDataTCPServer.js: TCP/IP server has received 3560940 bytes of data
,2015-11-20T12:11:56.622Z SendDataTCPServer.js: TCP/IP server has received 3611310 bytes of data
,2015-11-20T12:11:56.638Z SendDataTCPServer.js: TCP/IP server has received 3637590 bytes of data
,2015-11-20T12:11:56.651Z SendDataTCPServer.js: TCP/IP server has received 3703290 bytes of data
,2015-11-20T12:11:56.799Z SendDataTCPServer.js: TCP/IP server has received 3720668 bytes of data
,2015-11-20T12:11:56.812Z SendDataTCPServer.js: TCP/IP server has received 3727380 bytes of data
,2015-11-20T12:11:56.883Z SendDataTCPServer.js: TCP/IP server has received 3760230 bytes of data
,2015-11-20T12:11:56.898Z SendDataTCPServer.js: TCP/IP server has received 3804030 bytes of data
,2015-11-20T12:11:56.916Z SendDataTCPServer.js: TCP/IP server has received 3876016 bytes of data
,2015-11-20T12:11:56.932Z SendDataTCPServer.js: TCP/IP server has received 3935146 bytes of data
,2015-11-20T12:11:56.945Z SendDataTCPServer.js: TCP/IP server has received 3996750 bytes of data
,2015-11-20T12:11:56.959Z SendDataTCPServer.js: TCP/IP server has received 4018508 bytes of data
,2015-11-20T12:11:56.971Z SendDataTCPServer.js: TCP/IP server has received 4062450 bytes of data
,2015-11-20T12:11:56.983Z SendDataTCPServer.js: TCP/IP server has received 4110630 bytes of data
,2015-11-20T12:11:56.997Z SendDataTCPServer.js: TCP/IP server has received 4165380 bytes of data
,2015-11-20T12:11:57.012Z SendDataTCPServer.js: TCP/IP server has received 4228890 bytes of data
,2015-11-20T12:11:57.026Z SendDataTCPServer.js: TCP/IP server has received 4301160 bytes of data
,2015-11-20T12:11:57.038Z SendDataTCPServer.js: TCP/IP server has received 4358100 bytes of data
,2015-11-20T12:11:57.052Z SendDataTCPServer.js: TCP/IP server has received 4403948 bytes of data
,2015-11-20T12:11:57.064Z SendDataTCPServer.js: TCP/IP server has received 4526730 bytes of data
,2015-11-20T12:11:57.081Z SendDataTCPServer.js: TCP/IP server has received 4531110 bytes of data
,2015-11-20T12:11:57.095Z SendDataTCPServer.js: TCP/IP server has received 4614330 bytes of data
,2015-11-20T12:11:57.108Z SendDataTCPServer.js: TCP/IP server has received 4684410 bytes of data
,2015-11-20T12:11:57.121Z SendDataTCPServer.js: TCP/IP server has received 4719450 bytes of data
,2015-11-20T12:11:57.389Z SendDataTCPServer.js: TCP/IP server has received 4734780 bytes of data
,2015-11-20T12:11:57.401Z SendDataTCPServer.js: TCP/IP server has received 4800480 bytes of data
,2015-11-20T12:11:57.415Z SendDataTCPServer.js: TCP/IP server has received 4870560 bytes of data
,2015-11-20T12:11:57.430Z SendDataTCPServer.js: TCP/IP server has received 4881510 bytes of data
,2015-11-20T12:11:57.443Z SendDataTCPServer.js: TCP/IP server has received 4892460 bytes of data
,2015-11-20T12:11:57.456Z SendDataTCPServer.js: TCP/IP server has received 4903410 bytes of data
,2015-11-20T12:11:57.468Z SendDataTCPServer.js: TCP/IP server has received 4925026 bytes of data
,2015-11-20T12:11:57.483Z SendDataTCPServer.js: TCP/IP server has received 4975680 bytes of data
,2015-11-20T12:11:57.496Z SendDataTCPServer.js: TCP/IP server has received 5015100 bytes of data
,2015-11-20T12:11:57.512Z SendDataTCPServer.js: TCP/IP server has received 5065470 bytes of data
,2015-11-20T12:11:57.525Z SendDataTCPServer.js: TCP/IP server has received 5109270 bytes of data
,2015-11-20T12:11:57.538Z SendDataTCPServer.js: TCP/IP server has received 5159640 bytes of data
,2015-11-20T12:11:57.551Z SendDataTCPServer.js: TCP/IP server has received 5196870 bytes of data
,2015-11-20T12:11:57.577Z SendDataTCPServer.js: TCP/IP server has received 5240670 bytes of data
,2015-11-20T12:11:57.590Z SendDataTCPServer.js: TCP/IP server has received 5301990 bytes of data
,2015-11-20T12:11:57.603Z SendDataTCPServer.js: TCP/IP server has received 5369738 bytes of data
,2015-11-20T12:11:57.615Z SendDataTCPServer.js: TCP/IP server has received 5429010 bytes of data
,2015-11-20T12:11:57.629Z SendDataTCPServer.js: TCP/IP server has received 5496758 bytes of data
,2015-11-20T12:11:57.645Z SendDataTCPServer.js: TCP/IP server has received 5577930 bytes of data
,2015-11-20T12:11:57.659Z SendDataTCPServer.js: TCP/IP server has received 5667436 bytes of data
,2015-11-20T12:11:57.674Z SendDataTCPServer.js: TCP/IP server has received 5729040 bytes of data
,2015-11-20T12:11:57.688Z SendDataTCPServer.js: TCP/IP server has received 5801310 bytes of data
,2015-11-20T12:11:57.702Z SendDataTCPServer.js: TCP/IP server has received 5803500 bytes of data
,2015-11-20T12:11:57.841Z SendDataTCPServer.js: TCP/IP server has received 5838398 bytes of data
,2015-11-20T12:11:57.854Z SendDataTCPServer.js: TCP/IP server has received 5917380 bytes of data
,2015-11-20T12:11:57.869Z SendDataTCPServer.js: TCP/IP server has received 5978700 bytes of data
,2015-11-20T12:11:57.882Z SendDataTCPServer.js: TCP/IP server has received 6015930 bytes of data
,2015-11-20T12:11:57.899Z SendDataTCPServer.js: TCP/IP server has received 6046590 bytes of data
,2015-11-20T12:11:57.911Z SendDataTCPServer.js: TCP/IP server has received 6055350 bytes of data
,2015-11-20T12:11:57.924Z SendDataTCPServer.js: TCP/IP server has received 6070680 bytes of data
,2015-11-20T12:11:57.937Z SendDataTCPServer.js: TCP/IP server has received 6121050 bytes of data
,2015-11-20T12:11:57.952Z SendDataTCPServer.js: TCP/IP server has received 6182370 bytes of data
,2015-11-20T12:11:57.967Z SendDataTCPServer.js: TCP/IP server has received 6239310 bytes of data
,2015-11-20T12:11:57.982Z SendDataTCPServer.js: TCP/IP server has received 6256830 bytes of data
,2015-11-20T12:11:57.996Z SendDataTCPServer.js: TCP/IP server has received 6283110 bytes of data
,2015-11-20T12:11:58.010Z SendDataTCPServer.js: TCP/IP server has received 6309390 bytes of data
,2015-11-20T12:11:58.022Z SendDataTCPServer.js: TCP/IP server has received 6359760 bytes of data
,2015-11-20T12:11:58.037Z SendDataTCPServer.js: TCP/IP server has received 6436410 bytes of data
,2015-11-20T12:11:58.051Z SendDataTCPServer.js: TCP/IP server has received 6478020 bytes of data
,2015-11-20T12:11:58.065Z SendDataTCPServer.js: TCP/IP server has received 6482400 bytes of data
,2015-11-20T12:11:58.078Z SendDataTCPServer.js: TCP/IP server has received 6559050 bytes of data
,2015-11-20T12:11:58.094Z SendDataTCPServer.js: TCP/IP server has received 6624750 bytes of data
,2015-11-20T12:11:58.203Z SendDataTCPServer.js: TCP/IP server has received 6646650 bytes of data
,2015-11-20T12:11:58.217Z SendDataTCPServer.js: TCP/IP server has received 6707970 bytes of data
,2015-11-20T12:11:58.355Z SendDataTCPServer.js: TCP/IP server has received 6718920 bytes of data
,2015-11-20T12:11:58.369Z SendDataTCPServer.js: TCP/IP server has received 6808710 bytes of data
,2015-11-20T12:11:58.382Z SendDataTCPServer.js: TCP/IP server has received 6861128 bytes of data
,2015-11-20T12:11:58.395Z SendDataTCPServer.js: TCP/IP server has received 6889598 bytes of data
,2015-11-20T12:11:58.409Z SendDataTCPServer.js: TCP/IP server has received 6920400 bytes of data
,2015-11-20T12:11:58.422Z SendDataTCPServer.js: TCP/IP server has received 6940110 bytes of data
,2015-11-20T12:11:58.471Z SendDataTCPServer.js: TCP/IP server has received 6944490 bytes of data
,2015-11-20T12:11:58.482Z SendDataTCPServer.js: TCP/IP server has received 6966390 bytes of data
,2015-11-20T12:11:58.496Z SendDataTCPServer.js: TCP/IP server has received 6999098 bytes of data
,2015-11-20T12:11:58.508Z SendDataTCPServer.js: TCP/IP server has received 7016760 bytes of data
,2015-11-20T12:11:58.533Z SendDataTCPServer.js: TCP/IP server has received 7032090 bytes of data
,2015-11-20T12:11:58.558Z SendDataTCPServer.js: TCP/IP server has received 7034280 bytes of data
,2015-11-20T12:11:58.571Z SendDataTCPServer.js: TCP/IP server has received 7043040 bytes of data
,2015-11-20T12:11:58.595Z SendDataTCPServer.js: TCP/IP server has received 7067130 bytes of data
,2015-11-20T12:11:58.609Z SendDataTCPServer.js: TCP/IP server has received 7097790 bytes of data
,2015-11-20T12:11:58.622Z SendDataTCPServer.js: TCP/IP server has received 7132830 bytes of data
,2015-11-20T12:11:58.636Z SendDataTCPServer.js: TCP/IP server has received 7198530 bytes of data
,2015-11-20T12:11:58.649Z SendDataTCPServer.js: TCP/IP server has received 7264230 bytes of data
,2015-11-20T12:11:58.662Z SendDataTCPServer.js: TCP/IP server has received 7325408 bytes of data
,2015-11-20T12:11:58.678Z SendDataTCPServer.js: TCP/IP server has received 7410960 bytes of data
,2015-11-20T12:11:58.693Z SendDataTCPServer.js: TCP/IP server has received 7465710 bytes of data
,2015-11-20T12:11:58.708Z SendDataTCPServer.js: TCP/IP server has received 7524840 bytes of data
,2015-11-20T12:11:58.721Z SendDataTCPServer.js: TCP/IP server has received 7579590 bytes of data
,2015-11-20T12:11:58.734Z SendDataTCPServer.js: TCP/IP server has received 7651860 bytes of data
,2015-11-20T12:11:58.750Z SendDataTCPServer.js: TCP/IP server has received 7730700 bytes of data
,2015-11-20T12:11:58.763Z SendDataTCPServer.js: TCP/IP server has received 7750410 bytes of data
,2015-11-20T12:11:58.886Z SendDataTCPServer.js: TCP/IP server has received 7767930 bytes of data
,2015-11-20T12:11:58.900Z SendDataTCPServer.js: TCP/IP server has received 7792020 bytes of data
,2015-11-20T12:11:58.912Z SendDataTCPServer.js: TCP/IP server has received 7820490 bytes of data
,2015-11-20T12:11:58.925Z SendDataTCPServer.js: TCP/IP server has received 7851150 bytes of data
,2015-11-20T12:11:58.937Z SendDataTCPServer.js: TCP/IP server has received 7886190 bytes of data
,2015-11-20T12:11:58.951Z SendDataTCPServer.js: TCP/IP server has received 7894950 bytes of data
,2015-11-20T12:11:58.962Z SendDataTCPServer.js: TCP/IP server has received 7907948 bytes of data
,2015-11-20T12:11:58.977Z SendDataTCPServer.js: TCP/IP server has received 7927800 bytes of data
,2015-11-20T12:11:58.988Z SendDataTCPServer.js: TCP/IP server has received 7943130 bytes of data
,2015-11-20T12:11:59.002Z SendDataTCPServer.js: TCP/IP server has received 7989120 bytes of data
,2015-11-20T12:11:59.015Z SendDataTCPServer.js: TCP/IP server has received 8046060 bytes of data
,2015-11-20T12:11:59.028Z SendDataTCPServer.js: TCP/IP server has received 8105190 bytes of data
,2015-11-20T12:11:59.042Z SendDataTCPServer.js: TCP/IP server has received 8140230 bytes of data
,2015-11-20T12:11:59.056Z SendDataTCPServer.js: TCP/IP server has received 8179650 bytes of data
,2015-11-20T12:11:59.067Z SendDataTCPServer.js: TCP/IP server has received 8219070 bytes of data
,2015-11-20T12:11:59.081Z SendDataTCPServer.js: TCP/IP server has received 8260680 bytes of data
,2015-11-20T12:11:59.094Z SendDataTCPServer.js: TCP/IP server has received 8308860 bytes of data
,2015-11-20T12:11:59.106Z SendDataTCPServer.js: TCP/IP server has received 8365800 bytes of data
,2015-11-20T12:11:59.120Z SendDataTCPServer.js: TCP/IP server has received 8389890 bytes of data
,2015-11-20T12:11:59.134Z SendDataTCPServer.js: TCP/IP server has received 8418360 bytes of data
,2015-11-20T12:11:59.149Z SendDataTCPServer.js: TCP/IP server has received 8490630 bytes of data
,2015-11-20T12:11:59.163Z SendDataTCPServer.js: TCP/IP server has received 8576040 bytes of data
,2015-11-20T12:11:59.176Z SendDataTCPServer.js: TCP/IP server has received 8641456 bytes of data
,2015-11-20T12:11:59.189Z SendDataTCPServer.js: TCP/IP server has received 8707440 bytes of data
,2015-11-20T12:11:59.204Z SendDataTCPServer.js: TCP/IP server has received 8784090 bytes of data
,2015-11-20T12:11:59.217Z SendDataTCPServer.js: TCP/IP server has received 8849790 bytes of data
,2015-11-20T12:11:59.231Z SendDataTCPServer.js: TCP/IP server has received 8908920 bytes of data
,2015-11-20T12:11:59.245Z SendDataTCPServer.js: TCP/IP server has received 8968050 bytes of data
,2015-11-20T12:11:59.257Z SendDataTCPServer.js: TCP/IP server has received 9035940 bytes of data
,2015-11-20T12:11:59.271Z SendDataTCPServer.js: TCP/IP server has received 9108210 bytes of data
,2015-11-20T12:11:59.407Z SendDataTCPServer.js: TCP/IP server has received 9123540 bytes of data
,2015-11-20T12:11:59.421Z SendDataTCPServer.js: TCP/IP server has received 9180480 bytes of data
,2015-11-20T12:11:59.433Z SendDataTCPServer.js: TCP/IP server has received 9198000 bytes of data
,2015-11-20T12:11:59.447Z SendDataTCPServer.js: TCP/IP server has received 9246180 bytes of data
,2015-11-20T12:11:59.461Z SendDataTCPServer.js: TCP/IP server has received 9307500 bytes of data
,2015-11-20T12:11:59.476Z SendDataTCPServer.js: TCP/IP server has received 9351300 bytes of data
,2015-11-20T12:11:59.488Z SendDataTCPServer.js: TCP/IP server has received 9379770 bytes of data
,2015-11-20T12:11:59.502Z SendDataTCPServer.js: TCP/IP server has received 9384150 bytes of data
,2015-11-20T12:11:59.515Z SendDataTCPServer.js: TCP/IP server has received 9427950 bytes of data
,2015-11-20T12:11:59.530Z SendDataTCPServer.js: TCP/IP server has received 9465180 bytes of data
,2015-11-20T12:11:59.543Z SendDataTCPServer.js: TCP/IP server has received 9482700 bytes of data
,2015-11-20T12:11:59.557Z SendDataTCPServer.js: TCP/IP server has received 9502410 bytes of data
,2015-11-20T12:11:59.569Z SendDataTCPServer.js: TCP/IP server has received 9530880 bytes of data
,2015-11-20T12:11:59.582Z SendDataTCPServer.js: TCP/IP server has received 9605340 bytes of data
,2015-11-20T12:11:59.596Z SendDataTCPServer.js: TCP/IP server has received 9697320 bytes of data
,2015-11-20T12:11:59.610Z SendDataTCPServer.js: TCP/IP server has received 9771780 bytes of data
,2015-11-20T12:11:59.625Z SendDataTCPServer.js: TCP/IP server has received 9819960 bytes of data
,2015-11-20T12:11:59.637Z SendDataTCPServer.js: TCP/IP server has received 9835290 bytes of data
,2015-11-20T12:11:59.649Z SendDataTCPServer.js: TCP/IP server has received 9868140 bytes of data
,2015-11-20T12:11:59.663Z SendDataTCPServer.js: TCP/IP server has received 9874710 bytes of data
,2015-11-20T12:11:59.676Z SendDataTCPServer.js: TCP/IP server has received 9883470 bytes of data
,2015-11-20T12:11:59.689Z SendDataTCPServer.js: TCP/IP server has received 9896610 bytes of data
,2015-11-20T12:11:59.702Z SendDataTCPServer.js: TCP/IP server has received 9903180 bytes of data
,2015-11-20T12:11:59.715Z SendDataTCPServer.js: TCP/IP server has received 9905370 bytes of data
,2015-11-20T12:11:59.727Z SendDataTCPServer.js: TCP/IP server has received 9916320 bytes of data
,2015-11-20T12:11:59.741Z SendDataTCPServer.js: TCP/IP server has received 9940002 bytes of data
,2015-11-20 13:11:59.769 ThaliTest[841:951917] server session: not connected Apple-Iphone5s-1_PT497
,2015-11-20 13:12:00.027 ThaliTest[841:951917] client session: connected
2015-11-20 13:12:00.027 ThaliTest[841:951917] client session: stateChange:1->2 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:00.029 ThaliTest[841:951830] client session: fireConnectCallback: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:00.029 ThaliTest[841:951830] jxcore: connect: success
2015-11-20T12:12:00.030Z SendDataConnector.js: CLIENT connected to 55612, error: null
,2015-11-20T12:12:00.030Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:12:00.032 ThaliTest[841:950162] client: relay established
2015-11-20 13:12:00.032 ThaliTest[841:950162] client: new accepted socket: 0x908dad0
,2015-11-20T12:12:00.044Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:12:04.351Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:05.332Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:05.333Z SendDataConnector.js: CLIENT is data received : 540000
,2015-11-20T12:12:05.359Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:05.359Z SendDataConnector.js: CLIENT is data received : 580000
,2015-11-20T12:12:06.415Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:06.416Z SendDataConnector.js: CLIENT is data received : 1570000
,2015-11-20T12:12:07.408Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:07.408Z SendDataConnector.js: CLIENT is data received : 2860000
,2015-11-20T12:12:08.025Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:08.025Z SendDataConnector.js: CLIENT is data received : 3800000
,2015-11-20T12:12:08.468Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:08.468Z SendDataConnector.js: CLIENT is data received : 4450000
,2015-11-20T12:12:08.681Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:08.682Z SendDataConnector.js: CLIENT is data received : 4920000
,2015-11-20T12:12:09.007Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:09.007Z SendDataConnector.js: CLIENT is data received : 5270000
,2015-11-20T12:12:10.671Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:10.671Z SendDataConnector.js: CLIENT is data received : 5310000
,2015-11-20 13:12:15.350 ThaliTest[841:950162] multipeer session: restart
,2015-11-20 13:12:15.362 ThaliTest[841:950162] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:12:15.362 ThaliTest[841:950162] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:15.363 ThaliTest[841:950162] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:12:20.678Z SendDataConnector.js: Receiving data timeout now
2015-11-20T12:12:20.678Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:12:20.679Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T12:12:20.679Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20 13:12:20.679 ThaliTest[841:950162] client: socket closed
2015-11-20T12:12:20.679Z SendDataConnector.js: CLIENT is closed
,2015-11-20 13:12:20.680 ThaliTest[841:950162] client relay: socket disconnected
,2015-11-20 13:12:20.680 ThaliTest[841:950162] client relay: 0x908dad0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 13:12:20.,680 ThaliTest[841:950162] client session: socket closed: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:20.680 ThaliTest[841:950162] client session: onLinkFailure: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:20.680 ThaliTest[841:950162] client session: disconnect
2015-11-20 13:12:20.681 ThaliTest[841:950162] client session: stateChange:2->0 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:20.682 ThaliTest[841:950162] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:21.678Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:21.679Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:22.681 ThaliTest[841:950353] jxcore: disconnect
2015-11-20 13:12:22.681 ThaliTest[841:950353] jxcore: disconnect: fail
2015-11-20T12:12:22.681Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q==,
2015-11-20T12:12:22.681Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT2716.py/N2Q== with availability status: true
2015-11-20T12:12:22.681Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-,11-20T12:12:22.681Z SendDataConnector.js: do connect now
,2015-11-20 13:12:22.681 ThaliTest[841:950353] jxcore: connect Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:22.682 ThaliTest[841:950353] client session: connect
2015-11-20 13:12:22.682 ThaliTest[841:950353] client session: stateChange:0->1 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:33.562 ThaliTest[841:951830] client session: connected
2015-11-20 13:12:33.562 ThaliTest[841:951830] client session: stateChange:1->2 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:33.566 ThaliTest[841:951917] client session: fireConnectCallback: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:12:33.566 ThaliTest[841:951917] jxcore: connect: success
2015-11-20T12:12:33.566Z SendDataConnector.js: CLIENT connected to 55616, error: null
,2015-11-20T12:12:33.566Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:12:33.568 ThaliTest[841:950162] client: relay established
2015-11-20 13:12:33.568 ThaliTest[841:950162] client: new accepted socket: 0xa276a0
,2015-11-20T12:12:33.580Z SendDataConnector.js: CLIENT now sending 4690000 bytes of data
,2015-11-20T12:12:35.593Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:35.766Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:35.766Z SendDataConnector.js: CLIENT is data received : 5500000
,2015-11-20T12:12:35.885Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:35.886Z SendDataConnector.js: CLIENT is data received : 5810000
,2015-11-20T12:12:35.911Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:35.911Z SendDataConnector.js: CLIENT is data received : 5880000
,2015-11-20T12:12:36.239Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:36.240Z SendDataConnector.js: CLIENT is data received : 6300000
,2015-11-20T12:12:36.521Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:36.522Z SendDataConnector.js: CLIENT is data received : 6910000
,2015-11-20T12:12:36.921Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:36.922Z SendDataConnector.js: CLIENT is data received : 7430000
,2015-11-20T12:12:37.040Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:37.041Z SendDataConnector.js: CLIENT is data received : 7640000
,2015-11-20T12:12:37.318Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:37.319Z SendDataConnector.js: CLIENT is data received : 8050000
,2015-11-20T12:12:37.355Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:37.355Z SendDataConnector.js: CLIENT is data received : 8150000
,2015-11-20T12:12:37.610Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:37.610Z SendDataConnector.js: CLIENT is data received : 8710000
,2015-11-20T12:12:38.484Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:38.484Z SendDataConnector.js: CLIENT is data received : 9520000
,2015-11-20T12:12:38.578Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:38.579Z SendDataConnector.js: CLIENT is data received : 9650000
,2015-11-20T12:12:38.591Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:38.591Z SendDataConnector.js: CLIENT is data received : 9740000
,2015-11-20T12:12:38.615Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:38.615Z SendDataConnector.js: CLIENT is data received : 9750000
,2015-11-20T12:12:38.796Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:38.797Z SendDataConnector.js: CLIENT is data received : 9790000
,2015-11-20T12:12:38.810Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:38.810Z SendDataConnector.js: CLIENT is data received : 9830000
,2015-11-20T12:12:38.822Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:38.823Z SendDataConnector.js: CLIENT is data received : 9890000
,2015-11-20T12:12:38.861Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:38.862Z SendDataConnector.js: CLIENT is data received : 9910000
,2015-11-20T12:12:38.875Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:38.875Z SendDataConnector.js: CLIENT is data received : 9920000
,2015-11-20T12:12:38.888Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:38.888Z SendDataConnector.js: CLIENT is data received : 9940000
,2015-11-20T12:12:38.902Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:38.903Z SendDataConnector.js: CLIENT is data received : 9950000
,2015-11-20T12:12:38.916Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:38.916Z SendDataConnector.js: CLIENT is data received : 9960000
,2015-11-20T12:12:38.929Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20T12:12:38.929Z SendDataConnector.js: CLIENT is data received : 9990000
,2015-11-20T12:12:38.955Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20T12:12:38.955Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:12:38.955Z SendDataConnector.js: got all data for this round
,2015-11-20T12:12:38.956Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:12:38.956Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:12:38.956 ThaliTest[841:950353] jxcore: disconnect
2015-11-20 13:12:38.957 ThaliTest[841:950353] client session: disconnectFromPeer: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:38.957 ThaliTest[841:950353] client session: disconnect
2015-11-20 13:12:38.957 ThaliTest[841:950353] client session: stateChange:2->0 Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:12:38.960 ThaliTest[841:950353] jxcore: disconnect: success
2015-11-20T12:12:38.960Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2716.py/N2Q==
---- round done--------
weAreDoneNow , resultArray.length: 3,
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT7072","time":141758,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT2043.OU3s0w==","time":29961,"result":"OK","connections":1},{"n,ame":"Apple-Iphone5s-1_PT497.PdI1bg==","time":58779,"result":"OK","connections":2},{"name":"Apple-Iphone5-1_PT2716.py/N2Q==","time":52469,"result":"OK","connections":2}]}
sendList : 100% : 58779 ms, 99% : 58779 ms, 95 : 58779 ms, 90% : 58779 ms.
Result count 3, range 29961 ms to  58779 ms.
sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
2015-11-20T12:12:38.965Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:12:38.980Z SendDataConnector.js: CLIENT is closed
,2015-11-20 13:12:39.416 ThaliTest[841:950162] multipeer session: reset timer
2015-11-20 13:12:39.417 ThaliTest[841:950162] multipeer session: stop timer
,2015-11-20 13:12:39.417 ThaliTest[841:950162] multipeer session: start timer: 0x90c1d00
,2015-11-20 13:12:39.417 ThaliTest[841:950162] server session: connect
2015-11-20 13:12:39.417 ThaliTest[841:950162] server session: stateChange:0->1 Apple-Iphone5-1_PT2716
,2015-11-20 13:12:39.420 ThaliTest[841:950162] server: accepting invitation Apple-Iphone5-1_PT2716
,2015-11-20 13:12:41.964 ThaliTest[841:951917] server session: connected
2015-11-20 13:12:41.965 ThaliTest[841:951917] server session: stateChange:1->2 Apple-Iphone5-1_PT2716
,2015-11-20 13:12:41.989 ThaliTest[841:950162] server relay: connected (to port: 55592)
,2015-11-20T12:12:41.997Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 13:12:45.770 ThaliTest[841:950162] client: lost peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:12:45.770 ThaliTest[841:950162] client session: onPeerLost: Apple-Iphone6-1_PT2043.OU3s0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":false}]
,2015-11-20T12:12:53.531Z SendDataTCPServer.js: TCP/IP server has received 41664 bytes of data
,2015-11-20T12:12:53.543Z SendDataTCPServer.js: TCP/IP server has received 68448 bytes of data
,2015-11-20T12:12:53.557Z SendDataTCPServer.js: TCP/IP server has received 86304 bytes of data
,2015-11-20T12:12:53.570Z SendDataTCPServer.js: TCP/IP server has received 103168 bytes of data
,2015-11-20T12:12:53.581Z SendDataTCPServer.js: TCP/IP server has received 117056 bytes of data
,2015-11-20T12:12:53.595Z SendDataTCPServer.js: TCP/IP server has received 123008 bytes of data
,2015-11-20T12:12:53.702Z SendDataTCPServer.js: TCP/IP server has received 137888 bytes of data
,2015-11-20T12:12:53.715Z SendDataTCPServer.js: TCP/IP server has received 180544 bytes of data
,2015-11-20T12:12:53.755Z SendDataTCPServer.js: TCP/IP server has received 197408 bytes of data
,2015-11-20T12:12:53.768Z SendDataTCPServer.js: TCP/IP server has received 208320 bytes of data
,2015-11-20T12:12:53.794Z SendDataTCPServer.js: TCP/IP server has received 230144 bytes of data
,2015-11-20T12:12:53.811Z SendDataTCPServer.js: TCP/IP server has received 242048 bytes of data
,2015-11-20T12:12:53.862Z SendDataTCPServer.js: TCP/IP server has received 279744 bytes of data
,2015-11-20T12:12:53.876Z SendDataTCPServer.js: TCP/IP server has received 282720 bytes of data
,2015-11-20T12:12:54.011Z SendDataTCPServer.js: TCP/IP server has received 319424 bytes of data
,2015-11-20T12:12:54.025Z SendDataTCPServer.js: TCP/IP server has received 345216 bytes of data
,2015-11-20T12:12:54.063Z SendDataTCPServer.js: TCP/IP server has received 363072 bytes of data
,2015-11-20T12:12:54.075Z SendDataTCPServer.js: TCP/IP server has received 378944 bytes of data
,2015-11-20T12:12:54.088Z SendDataTCPServer.js: TCP/IP server has received 395808 bytes of data
,2015-11-20T12:12:54.101Z SendDataTCPServer.js: TCP/IP server has received 401760 bytes of data
,2015-11-20T12:12:54.113Z SendDataTCPServer.js: TCP/IP server has received 414656 bytes of data
,2015-11-20T12:12:54.124Z SendDataTCPServer.js: TCP/IP server has received 451360 bytes of data
,2015-11-20T12:12:54.136Z SendDataTCPServer.js: TCP/IP server has received 465248 bytes of data
,2015-11-20T12:12:54.149Z SendDataTCPServer.js: TCP/IP server has received 481120 bytes of data
,2015-11-20T12:12:54.160Z SendDataTCPServer.js: TCP/IP server has received 494016 bytes of data
,2015-11-20T12:12:54.172Z SendDataTCPServer.js: TCP/IP server has received 508896 bytes of data
,2015-11-20T12:12:54.184Z SendDataTCPServer.js: TCP/IP server has received 525760 bytes of data
,2015-11-20T12:12:54.198Z SendDataTCPServer.js: TCP/IP server has received 544608 bytes of data
,2015-11-20T12:12:54.211Z SendDataTCPServer.js: TCP/IP server has received 563456 bytes of data
,2015-11-20T12:12:54.225Z SendDataTCPServer.js: TCP/IP server has received 584288 bytes of data
,2015-11-20T12:12:54.237Z SendDataTCPServer.js: TCP/IP server has received 600160 bytes of data
,2015-11-20T12:12:54.250Z SendDataTCPServer.js: TCP/IP server has received 618016 bytes of data
,2015-11-20T12:12:54.263Z SendDataTCPServer.js: TCP/IP server has received 629920 bytes of data
,2015-11-20T12:12:54.274Z SendDataTCPServer.js: TCP/IP server has received 633888 bytes of data
,2015-11-20T12:12:54.286Z SendDataTCPServer.js: TCP/IP server has received 648768 bytes of data
,2015-11-20T12:12:54.300Z SendDataTCPServer.js: TCP/IP server has received 664640 bytes of data
,2015-11-20T12:12:54.314Z SendDataTCPServer.js: TCP/IP server has received 675552 bytes of data
,2015-11-20T12:12:54.328Z SendDataTCPServer.js: TCP/IP server has received 703328 bytes of data
,2015-11-20T12:12:54.377Z SendDataTCPServer.js: TCP/IP server has received 708288 bytes of data
,2015-11-20T12:12:54.390Z SendDataTCPServer.js: TCP/IP server has received 755904 bytes of data
,2015-11-20T12:12:54.405Z SendDataTCPServer.js: TCP/IP server has received 763840 bytes of data
,2015-11-20T12:12:54.430Z SendDataTCPServer.js: TCP/IP server has received 775744 bytes of data
,2015-11-20T12:12:54.506Z SendDataTCPServer.js: TCP/IP server has received 781696 bytes of data
,2015-11-20T12:12:54.520Z SendDataTCPServer.js: TCP/IP server has received 834272 bytes of data
,2015-11-20T12:12:54.533Z SendDataTCPServer.js: TCP/IP server has received 850144 bytes of data
,2015-11-20T12:12:54.546Z SendDataTCPServer.js: TCP/IP server has received 864032 bytes of data
,2015-11-20T12:12:54.559Z SendDataTCPServer.js: TCP/IP server has received 880896 bytes of data
,2015-11-20T12:12:54.571Z SendDataTCPServer.js: TCP/IP server has received 896768 bytes of data
,2015-11-20T12:12:54.584Z SendDataTCPServer.js: TCP/IP server has received 915616 bytes of data
,2015-11-20T12:12:54.598Z SendDataTCPServer.js: TCP/IP server has received 935456 bytes of data
,2015-11-20T12:12:54.610Z SendDataTCPServer.js: TCP/IP server has received 953312 bytes of data
,2015-11-20T12:12:54.623Z SendDataTCPServer.js: TCP/IP server has received 974144 bytes of data
,2015-11-20T12:12:54.637Z SendDataTCPServer.js: TCP/IP server has received 997952 bytes of data
,2015-11-20T12:12:54.651Z SendDataTCPServer.js: TCP/IP server has received 1021760 bytes of data
,2015-11-20T12:12:54.663Z SendDataTCPServer.js: TCP/IP server has received 1042592 bytes of data
,2015-11-20T12:12:54.676Z SendDataTCPServer.js: TCP/IP server has received 1063424 bytes of data
,2015-11-20T12:12:54.689Z SendDataTCPServer.js: TCP/IP server has received 1086240 bytes of data
,2015-11-20T12:12:54.701Z SendDataTCPServer.js: TCP/IP server has received 1105088 bytes of data
,2015-11-20T12:12:54.714Z SendDataTCPServer.js: TCP/IP server has received 1124928 bytes of data
,2015-11-20T12:12:54.727Z SendDataTCPServer.js: TCP/IP server has received 1147744 bytes of data
,2015-11-20T12:12:54.741Z SendDataTCPServer.js: TCP/IP server has received 1169568 bytes of data
,2015-11-20T12:12:54.754Z SendDataTCPServer.js: TCP/IP server has received 1192384 bytes of data
,2015-11-20T12:12:54.766Z SendDataTCPServer.js: TCP/IP server has received 1212224 bytes of data
,2015-11-20T12:12:54.778Z SendDataTCPServer.js: TCP/IP server has received 1233056 bytes of data
,2015-11-20T12:12:54.792Z SendDataTCPServer.js: TCP/IP server has received 1255872 bytes of data
,2015-11-20T12:12:54.804Z SendDataTCPServer.js: TCP/IP server has received 1277696 bytes of data
,2015-11-20T12:12:54.817Z SendDataTCPServer.js: TCP/IP server has received 1296544 bytes of data
,2015-11-20T12:12:54.831Z SendDataTCPServer.js: TCP/IP server has received 1304480 bytes of data
,2015-11-20T12:12:54.842Z SendDataTCPServer.js: TCP/IP server has received 1320352 bytes of data
,2015-11-20T12:12:54.854Z SendDataTCPServer.js: TCP/IP server has received 1360032 bytes of data
,2015-11-20T12:12:54.866Z SendDataTCPServer.js: TCP/IP server has received 1373920 bytes of data
,2015-11-20T12:12:54.903Z SendDataTCPServer.js: TCP/IP server has received 1386816 bytes of data
,2015-11-20T12:12:54.916Z SendDataTCPServer.js: TCP/IP server has received 1414592 bytes of data
,2015-11-20T12:12:54.929Z SendDataTCPServer.js: TCP/IP server has received 1416576 bytes of data
,2015-11-20T12:12:54.953Z SendDataTCPServer.js: TCP/IP server has received 1418560 bytes of data
,2015-11-20T12:12:55.037Z SendDataTCPServer.js: TCP/IP server has received 1444352 bytes of data
,2015-11-20T12:12:55.050Z SendDataTCPServer.js: TCP/IP server has received 1479072 bytes of data
,2015-11-20T12:12:55.076Z SendDataTCPServer.js: TCP/IP server has received 1483040 bytes of data
,2015-11-20T12:12:55.088Z SendDataTCPServer.js: TCP/IP server has received 1502880 bytes of data
,2015-11-20T12:12:55.101Z SendDataTCPServer.js: TCP/IP server has received 1517760 bytes of data
,2015-11-20T12:12:55.113Z SendDataTCPServer.js: TCP/IP server has received 1532640 bytes of data
,2015-11-20T12:12:55.125Z SendDataTCPServer.js: TCP/IP server has received 1549504 bytes of data
,2015-11-20T12:12:55.138Z SendDataTCPServer.js: TCP/IP server has received 1565376 bytes of data
,2015-11-20T12:12:55.152Z SendDataTCPServer.js: TCP/IP server has received 1582240 bytes of data
,2015-11-20T12:12:55.163Z SendDataTCPServer.js: TCP/IP server has received 1601088 bytes of data
,2015-11-20T12:12:55.176Z SendDataTCPServer.js: TCP/IP server has received 1616960 bytes of data
,2015-11-20T12:12:55.187Z SendDataTCPServer.js: TCP/IP server has received 1630848 bytes of data
,2015-11-20T12:12:55.199Z SendDataTCPServer.js: TCP/IP server has received 1647712 bytes of data
,2015-11-20T12:12:55.211Z SendDataTCPServer.js: TCP/IP server has received 1668544 bytes of data
,2015-11-20T12:12:55.224Z SendDataTCPServer.js: TCP/IP server has received 1688384 bytes of data
,2015-11-20T12:12:55.237Z SendDataTCPServer.js: TCP/IP server has received 1702272 bytes of data
,2015-11-20T12:12:55.249Z SendDataTCPServer.js: TCP/IP server has received 1721120 bytes of data
,2015-11-20T12:12:55.262Z SendDataTCPServer.js: TCP/IP server has received 1738976 bytes of data
,2015-11-20T12:12:55.276Z SendDataTCPServer.js: TCP/IP server has received 1760800 bytes of data
,2015-11-20T12:12:55.289Z SendDataTCPServer.js: TCP/IP server has received 1782624 bytes of data
,2015-11-20T12:12:55.303Z SendDataTCPServer.js: TCP/IP server has received 1804448 bytes of data
,2015-11-20T12:12:55.315Z SendDataTCPServer.js: TCP/IP server has received 1823296 bytes of data
,2015-11-20T12:12:55.327Z SendDataTCPServer.js: TCP/IP server has received 1842144 bytes of data
,2015-11-20T12:12:55.341Z SendDataTCPServer.js: TCP/IP server has received 1862976 bytes of data
,2015-11-20T12:12:55.354Z SendDataTCPServer.js: TCP/IP server has received 1870912 bytes of data
,2015-11-20T12:12:55.426Z SendDataTCPServer.js: TCP/IP server has received 1885792 bytes of data
,2015-11-20T12:12:55.440Z SendDataTCPServer.js: TCP/IP server has received 1894720 bytes of data
,2015-11-20T12:12:55.452Z SendDataTCPServer.js: TCP/IP server has received 1914560 bytes of data
,2015-11-20T12:12:55.467Z SendDataTCPServer.js: TCP/IP server has received 1933408 bytes of data
,2015-11-20T12:12:55.583Z SendDataTCPServer.js: TCP/IP server has received 1939360 bytes of data
,2015-11-20T12:12:55.596Z SendDataTCPServer.js: TCP/IP server has received 1984000 bytes of data
,2015-11-20T12:12:55.609Z SendDataTCPServer.js: TCP/IP server has received 1995904 bytes of data
,2015-11-20T12:12:55.656Z SendDataTCPServer.js: TCP/IP server has received 1997888 bytes of data
,2015-11-20T12:12:55.668Z SendDataTCPServer.js: TCP/IP server has received 2015744 bytes of data
,2015-11-20T12:12:55.681Z SendDataTCPServer.js: TCP/IP server has received 2032608 bytes of data
,2015-11-20T12:12:55.693Z SendDataTCPServer.js: TCP/IP server has received 2048480 bytes of data
,2015-11-20T12:12:55.706Z SendDataTCPServer.js: TCP/IP server has received 2067328 bytes of data
,2015-11-20T12:12:55.720Z SendDataTCPServer.js: TCP/IP server has received 2085184 bytes of data
,2015-11-20T12:12:55.733Z SendDataTCPServer.js: TCP/IP server has received 2102048 bytes of data
,2015-11-20T12:12:55.746Z SendDataTCPServer.js: TCP/IP server has received 2119904 bytes of data
,2015-11-20T12:12:55.759Z SendDataTCPServer.js: TCP/IP server has received 2135776 bytes of data
,2015-11-20T12:12:55.773Z SendDataTCPServer.js: TCP/IP server has received 2154624 bytes of data
,2015-11-20T12:12:55.786Z SendDataTCPServer.js: TCP/IP server has received 2176448 bytes of data
,2015-11-20T12:12:55.801Z SendDataTCPServer.js: TCP/IP server has received 2198272 bytes of data
,2015-11-20T12:12:55.812Z SendDataTCPServer.js: TCP/IP server has received 2216128 bytes of data
,2015-11-20T12:12:55.824Z SendDataTCPServer.js: TCP/IP server has received 2232992 bytes of data
,2015-11-20T12:12:55.837Z SendDataTCPServer.js: TCP/IP server has received 2254816 bytes of data
,2015-11-20T12:12:55.850Z SendDataTCPServer.js: TCP/IP server has received 2275648 bytes of data
,2015-11-20T12:12:55.867Z SendDataTCPServer.js: TCP/IP server has received 2292512 bytes of data
,2015-11-20T12:12:55.893Z SendDataTCPServer.js: TCP/IP server has received 2322336 bytes of data
,2015-11-20T12:12:55.907Z SendDataTCPServer.js: TCP/IP server has received 2324256 bytes of data
,2015-11-20T12:12:55.955Z SendDataTCPServer.js: TCP/IP server has received 2341184 bytes of data
,2015-11-20T12:12:55.969Z SendDataTCPServer.js: TCP/IP server has received 2359968 bytes of data
,2015-11-20T12:12:56.090Z SendDataTCPServer.js: TCP/IP server has received 2373856 bytes of data
,2015-11-20T12:12:56.103Z SendDataTCPServer.js: TCP/IP server has received 2420480 bytes of data
,2015-11-20T12:12:56.117Z SendDataTCPServer.js: TCP/IP server has received 2422464 bytes of data
,2015-11-20T12:12:56.191Z SendDataTCPServer.js: TCP/IP server has received 2428416 bytes of data
,2015-11-20T12:12:56.202Z SendDataTCPServer.js: TCP/IP server has received 2447264 bytes of data
,2015-11-20T12:12:56.214Z SendDataTCPServer.js: TCP/IP server has received 2464128 bytes of data
,2015-11-20T12:12:56.227Z SendDataTCPServer.js: TCP/IP server has received 2482976 bytes of data
,2015-11-20T12:12:56.239Z SendDataTCPServer.js: TCP/IP server has received 2499840 bytes of data
,2015-11-20T12:12:56.251Z SendDataTCPServer.js: TCP/IP server has received 2516704 bytes of data
,2015-11-20T12:12:56.265Z SendDataTCPServer.js: TCP/IP server has received 2522656 bytes of data
,2015-11-20T12:12:56.276Z SendDataTCPServer.js: TCP/IP server has received 2539520 bytes of data
,2015-11-20T12:12:56.291Z SendDataTCPServer.js: TCP/IP server has received 2576224 bytes of data
,2015-11-20T12:12:56.316Z SendDataTCPServer.js: TCP/IP server has received 2593088 bytes of data
,2015-11-20T12:12:56.329Z SendDataTCPServer.js: TCP/IP server has received 2615904 bytes of data
,2015-11-20T12:12:56.342Z SendDataTCPServer.js: TCP/IP server has received 2636736 bytes of data
,2015-11-20T12:12:56.355Z SendDataTCPServer.js: TCP/IP server has received 2654592 bytes of data
,2015-11-20T12:12:56.368Z SendDataTCPServer.js: TCP/IP server has received 2676416 bytes of data
,2015-11-20T12:12:56.381Z SendDataTCPServer.js: TCP/IP server has received 2695264 bytes of data
,2015-11-20T12:12:56.394Z SendDataTCPServer.js: TCP/IP server has received 2714112 bytes of data
,2015-11-20T12:12:56.407Z SendDataTCPServer.js: TCP/IP server has received 2716096 bytes of data
,2015-11-20T12:12:56.418Z SendDataTCPServer.js: TCP/IP server has received 2749824 bytes of data
,2015-11-20T12:12:56.432Z SendDataTCPServer.js: TCP/IP server has received 2754784 bytes of data
,2015-11-20T12:12:56.445Z SendDataTCPServer.js: TCP/IP server has received 2762720 bytes of data
,2015-11-20T12:12:56.470Z SendDataTCPServer.js: TCP/IP server has received 2769664 bytes of data
,2015-11-20T12:12:56.483Z SendDataTCPServer.js: TCP/IP server has received 2808352 bytes of data
,2015-11-20T12:12:56.498Z SendDataTCPServer.js: TCP/IP server has received 2816288 bytes of data
,2015-11-20T12:12:56.511Z SendDataTCPServer.js: TCP/IP server has received 2817280 bytes of data
,2015-11-20T12:12:56.612Z SendDataTCPServer.js: TCP/IP server has received 2851008 bytes of data
,2015-11-20T12:12:56.626Z SendDataTCPServer.js: TCP/IP server has received 2856960 bytes of data
,2015-11-20T12:12:56.675Z SendDataTCPServer.js: TCP/IP server has received 2864896 bytes of data
,2015-11-20T12:12:56.687Z SendDataTCPServer.js: TCP/IP server has received 2882752 bytes of data
,2015-11-20T12:12:56.699Z SendDataTCPServer.js: TCP/IP server has received 2896640 bytes of data
,2015-11-20T12:12:56.711Z SendDataTCPServer.js: TCP/IP server has received 2913504 bytes of data
,2015-11-20T12:12:56.725Z SendDataTCPServer.js: TCP/IP server has received 2922432 bytes of data
,2015-11-20T12:12:56.738Z SendDataTCPServer.js: TCP/IP server has received 2930368 bytes of data
,2015-11-20T12:12:56.749Z SendDataTCPServer.js: TCP/IP server has received 2971040 bytes of data
,2015-11-20T12:12:56.761Z SendDataTCPServer.js: TCP/IP server has received 2984928 bytes of data
,2015-11-20T12:12:56.772Z SendDataTCPServer.js: TCP/IP server has received 2997824 bytes of data
,2015-11-20T12:12:56.784Z SendDataTCPServer.js: TCP/IP server has received 3014688 bytes of data
,2015-11-20T12:12:56.796Z SendDataTCPServer.js: TCP/IP server has received 3031552 bytes of data
,2015-11-20T12:12:56.808Z SendDataTCPServer.js: TCP/IP server has received 3050400 bytes of data
,2015-11-20T12:12:56.820Z SendDataTCPServer.js: TCP/IP server has received 3069248 bytes of data
,2015-11-20T12:12:56.833Z SendDataTCPServer.js: TCP/IP server has received 3088096 bytes of data
,2015-11-20T12:12:56.847Z SendDataTCPServer.js: TCP/IP server has received 3109920 bytes of data
,2015-11-20T12:12:56.861Z SendDataTCPServer.js: TCP/IP server has received 3131744 bytes of data
,2015-11-20T12:12:56.875Z SendDataTCPServer.js: TCP/IP server has received 3152576 bytes of data
,2015-11-20T12:12:56.887Z SendDataTCPServer.js: TCP/IP server has received 3170432 bytes of data
,2015-11-20T12:12:56.898Z SendDataTCPServer.js: TCP/IP server has received 3187296 bytes of data
,2015-11-20T12:12:56.911Z SendDataTCPServer.js: TCP/IP server has received 3208128 bytes of data
,2015-11-20T12:12:56.924Z SendDataTCPServer.js: TCP/IP server has received 3221024 bytes of data
,2015-11-20T12:12:56.938Z SendDataTCPServer.js: TCP/IP server has received 3246816 bytes of data
,2015-11-20T12:12:56.952Z SendDataTCPServer.js: TCP/IP server has received 3251776 bytes of data
,2015-11-20T12:12:56.963Z SendDataTCPServer.js: TCP/IP server has received 3261696 bytes of data
,2015-11-20T12:12:56.977Z SendDataTCPServer.js: TCP/IP server has received 3298400 bytes of data
,2015-11-20T12:12:56.989Z SendDataTCPServer.js: TCP/IP server has received 3304352 bytes of data
,2015-11-20T12:12:57.027Z SendDataTCPServer.js: TCP/IP server has received 3337088 bytes of data
,2015-11-20T12:12:57.041Z SendDataTCPServer.js: TCP/IP server has received 3366848 bytes of data
,2015-11-20T12:12:57.054Z SendDataTCPServer.js: TCP/IP server has received 3367840 bytes of data
,2015-11-20T12:12:57.130Z SendDataTCPServer.js: TCP/IP server has received 3371808 bytes of data
,2015-11-20T12:12:57.142Z SendDataTCPServer.js: TCP/IP server has received 3415456 bytes of data
,2015-11-20T12:12:57.157Z SendDataTCPServer.js: TCP/IP server has received 3424384 bytes of data
,2015-11-20T12:12:57.169Z SendDataTCPServer.js: TCP/IP server has received 3438272 bytes of data
,2015-11-20T12:12:57.184Z SendDataTCPServer.js: TCP/IP server has received 3443232 bytes of data
,2015-11-20T12:12:57.196Z SendDataTCPServer.js: TCP/IP server has received 3469024 bytes of data
,2015-11-20T12:12:57.210Z SendDataTCPServer.js: TCP/IP server has received 3497792 bytes of data
,2015-11-20T12:12:57.224Z SendDataTCPServer.js: TCP/IP server has received 3510688 bytes of data
,2015-11-20T12:12:57.237Z SendDataTCPServer.js: TCP/IP server has received 3526560 bytes of data
,2015-11-20 13:12:57.241 ThaliTest[841:950162] client: lost peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:12:57.241 ThaliTest[841:950162] client session: onPeerLost: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20T12:12:57.242Z SendDataTCPServer.js: TCP/IP server has received 3534496 bytes of data
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":false}]
,2015-11-20T12:12:57.256Z SendDataTCPServer.js: TCP/IP server has received 3550368 bytes of data
,2015-11-20T12:12:57.267Z SendDataTCPServer.js: TCP/IP server has received 3563264 bytes of data
,2015-11-20T12:12:57.279Z SendDataTCPServer.js: TCP/IP server has received 3579136 bytes of data
,2015-11-20T12:12:57.293Z SendDataTCPServer.js: TCP/IP server has received 3600960 bytes of data
,2015-11-20T12:12:57.306Z SendDataTCPServer.js: TCP/IP server has received 3620800 bytes of data
,2015-11-20T12:12:57.321Z SendDataTCPServer.js: TCP/IP server has received 3641632 bytes of data
,2015-11-20T12:12:57.334Z SendDataTCPServer.js: TCP/IP server has received 3661472 bytes of data
,2015-11-20T12:12:57.346Z SendDataTCPServer.js: TCP/IP server has received 3680320 bytes of data
,2015-11-20T12:12:57.359Z SendDataTCPServer.js: TCP/IP server has received 3701152 bytes of data
,2015-11-20T12:12:57.372Z SendDataTCPServer.js: TCP/IP server has received 3720992 bytes of data
,2015-11-20T12:12:57.385Z SendDataTCPServer.js: TCP/IP server has received 3740832 bytes of data
,2015-11-20T12:12:57.398Z SendDataTCPServer.js: TCP/IP server has received 3759680 bytes of data
,2015-11-20T12:12:57.409Z SendDataTCPServer.js: TCP/IP server has received 3778528 bytes of data
,2015-11-20T12:12:57.424Z SendDataTCPServer.js: TCP/IP server has received 3800352 bytes of data
,2015-11-20T12:12:57.435Z SendDataTCPServer.js: TCP/IP server has received 3818208 bytes of data
,2015-11-20T12:12:57.447Z SendDataTCPServer.js: TCP/IP server has received 3830112 bytes of data
,2015-11-20T12:12:57.471Z SendDataTCPServer.js: TCP/IP server has received 3858880 bytes of data
,2015-11-20T12:12:57.485Z SendDataTCPServer.js: TCP/IP server has received 3865824 bytes of data
,2015-11-20T12:12:57.523Z SendDataTCPServer.js: TCP/IP server has received 3882688 bytes of data
,2015-11-20T12:12:57.536Z SendDataTCPServer.js: TCP/IP server has received 3892608 bytes of data
,2015-11-20T12:12:57.670Z SendDataTCPServer.js: TCP/IP server has received 3893600 bytes of data
,2015-11-20T12:12:57.683Z SendDataTCPServer.js: TCP/IP server has received 3943200 bytes of data
,2015-11-20T12:12:57.697Z SendDataTCPServer.js: TCP/IP server has received 3945184 bytes of data
,2015-11-20T12:12:57.721Z SendDataTCPServer.js: TCP/IP server has received 3948160 bytes of data
,2015-11-20T12:12:57.733Z SendDataTCPServer.js: TCP/IP server has received 3966016 bytes of data
,2015-11-20T12:12:57.747Z SendDataTCPServer.js: TCP/IP server has received 3984864 bytes of data
,2015-11-20T12:12:57.759Z SendDataTCPServer.js: TCP/IP server has received 4000736 bytes of data
,2015-11-20T12:12:57.772Z SendDataTCPServer.js: TCP/IP server has received 4019584 bytes of data
,2015-11-20T12:12:57.785Z SendDataTCPServer.js: TCP/IP server has received 4034464 bytes of data
,2015-11-20T12:12:57.797Z SendDataTCPServer.js: TCP/IP server has received 4050336 bytes of data
,2015-11-20T12:12:57.809Z SendDataTCPServer.js: TCP/IP server has received 4067200 bytes of data
,2015-11-20T12:12:57.822Z SendDataTCPServer.js: TCP/IP server has received 4084064 bytes of data
,2015-11-20T12:12:57.836Z SendDataTCPServer.js: TCP/IP server has received 4102912 bytes of data
,2015-11-20T12:12:57.850Z SendDataTCPServer.js: TCP/IP server has received 4122752 bytes of data
,2015-11-20T12:12:57.863Z SendDataTCPServer.js: TCP/IP server has received 4137632 bytes of data
,2015-11-20T12:12:57.935Z SendDataTCPServer.js: TCP/IP server has received 4149536 bytes of data
,2015-11-20T12:12:57.945Z SendDataTCPServer.js: TCP/IP server has received 4177312 bytes of data
,2015-11-20T12:12:57.959Z SendDataTCPServer.js: TCP/IP server has received 4200128 bytes of data
,2015-11-20T12:12:58.230Z SendDataTCPServer.js: TCP/IP server has received 4205088 bytes of data
,2015-11-20T12:12:58.252Z SendDataTCPServer.js: TCP/IP server has received 4206080 bytes of data
,2015-11-20T12:12:58.265Z SendDataTCPServer.js: TCP/IP server has received 4207072 bytes of data
,2015-11-20T12:12:58.278Z SendDataTCPServer.js: TCP/IP server has received 4208064 bytes of data
,2015-11-20T12:12:58.290Z SendDataTCPServer.js: TCP/IP server has received 4209056 bytes of data
,2015-11-20T12:12:58.316Z SendDataTCPServer.js: TCP/IP server has received 4210048 bytes of data
,2015-11-20T12:12:58.329Z SendDataTCPServer.js: TCP/IP server has received 4211040 bytes of data
,2015-11-20T12:12:58.342Z SendDataTCPServer.js: TCP/IP server has received 4225920 bytes of data
,2015-11-20T12:12:58.355Z SendDataTCPServer.js: TCP/IP server has received 4236832 bytes of data
,2015-11-20T12:12:58.378Z SendDataTCPServer.js: TCP/IP server has received 4274528 bytes of data
,2015-11-20T12:12:58.392Z SendDataTCPServer.js: TCP/IP server has received 4289408 bytes of data
,2015-11-20T12:12:58.405Z SendDataTCPServer.js: TCP/IP server has received 4309248 bytes of data
,2015-11-20T12:12:58.419Z SendDataTCPServer.js: TCP/IP server has received 4329088 bytes of data
,2015-11-20T12:12:58.431Z SendDataTCPServer.js: TCP/IP server has received 4347936 bytes of data
,2015-11-20T12:12:58.445Z SendDataTCPServer.js: TCP/IP server has received 4368768 bytes of data
,2015-11-20T12:12:58.458Z SendDataTCPServer.js: TCP/IP server has received 4387616 bytes of data
,2015-11-20T12:12:58.472Z SendDataTCPServer.js: TCP/IP server has received 4410432 bytes of data
,2015-11-20T12:12:58.486Z SendDataTCPServer.js: TCP/IP server has received 4432256 bytes of data
,2015-11-20T12:12:58.499Z SendDataTCPServer.js: TCP/IP server has received 4442176 bytes of data
,2015-11-20T12:12:58.612Z SendDataTCPServer.js: TCP/IP server has received 4444160 bytes of data
,2015-11-20T12:12:58.625Z SendDataTCPServer.js: TCP/IP server has received 4455072 bytes of data
,2015-11-20 13:12:58.712 ThaliTest[841:950162] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":true}]
,2015-11-20T12:12:58.726Z SendDataTCPServer.js: TCP/IP server has received 4498720 bytes of data
,2015-11-20T12:12:58.738Z SendDataTCPServer.js: TCP/IP server has received 4504672 bytes of data
,2015-11-20T12:12:58.750Z SendDataTCPServer.js: TCP/IP server has received 4514592 bytes of data
,2015-11-20T12:12:58.764Z SendDataTCPServer.js: TCP/IP server has received 4534432 bytes of data
,2015-11-20T12:12:58.778Z SendDataTCPServer.js: TCP/IP server has received 4551296 bytes of data
,2015-11-20T12:12:58.789Z SendDataTCPServer.js: TCP/IP server has received 4565184 bytes of data
,2015-11-20T12:12:58.803Z SendDataTCPServer.js: TCP/IP server has received 4583040 bytes of data
,2015-11-20T12:12:58.815Z SendDataTCPServer.js: TCP/IP server has received 4599904 bytes of data
,2015-11-20T12:12:58.830Z SendDataTCPServer.js: TCP/IP server has received 4618752 bytes of data
,2015-11-20T12:12:58.843Z SendDataTCPServer.js: TCP/IP server has received 4640576 bytes of data
,2015-11-20T12:12:58.856Z SendDataTCPServer.js: TCP/IP server has received 4659424 bytes of data
,2015-11-20T12:12:58.870Z SendDataTCPServer.js: TCP/IP server has received 4683232 bytes of data
,2015-11-20T12:12:58.883Z SendDataTCPServer.js: TCP/IP server has received 4704064 bytes of data
,2015-11-20T12:12:58.897Z SendDataTCPServer.js: TCP/IP server has received 4727872 bytes of data
,2015-11-20T12:12:58.910Z SendDataTCPServer.js: TCP/IP server has received 4747712 bytes of data
,2015-11-20T12:12:58.923Z SendDataTCPServer.js: TCP/IP server has received 4769536 bytes of data
,2015-11-20T12:12:58.937Z SendDataTCPServer.js: TCP/IP server has received 4794336 bytes of data
,2015-11-20T12:12:58.951Z SendDataTCPServer.js: TCP/IP server has received 4817152 bytes of data
,2015-11-20T12:12:58.963Z SendDataTCPServer.js: TCP/IP server has received 4836992 bytes of data
,2015-11-20T12:12:58.975Z SendDataTCPServer.js: TCP/IP server has received 4854848 bytes of data
,2015-11-20T12:12:58.989Z SendDataTCPServer.js: TCP/IP server has received 4875680 bytes of data
,2015-11-20T12:12:59.003Z SendDataTCPServer.js: TCP/IP server has received 4896512 bytes of data
,2015-11-20T12:12:59.015Z SendDataTCPServer.js: TCP/IP server has received 4914368 bytes of data
,2015-11-20T12:12:59.028Z SendDataTCPServer.js: TCP/IP server has received 4915360 bytes of data
,2015-11-20T12:12:59.050Z SendDataTCPServer.js: TCP/IP server has received 4931232 bytes of data
,2015-11-20T12:12:59.256Z SendDataTCPServer.js: TCP/IP server has received 4937184 bytes of data
,2015-11-20T12:12:59.268Z SendDataTCPServer.js: TCP/IP server has received 4977856 bytes of data
,2015-11-20T12:12:59.281Z SendDataTCPServer.js: TCP/IP server has received 4978848 bytes of data
,2015-11-20T12:12:59.294Z SendDataTCPServer.js: TCP/IP server has received 4993728 bytes of data
,2015-11-20T12:12:59.319Z SendDataTCPServer.js: TCP/IP server has received 5021504 bytes of data
,2015-11-20T12:12:59.331Z SendDataTCPServer.js: TCP/IP server has received 5034400 bytes of data
,2015-11-20T12:12:59.343Z SendDataTCPServer.js: TCP/IP server has received 5052256 bytes of data
,2015-11-20T12:12:59.357Z SendDataTCPServer.js: TCP/IP server has received 5073088 bytes of data
,2015-11-20T12:12:59.371Z SendDataTCPServer.js: TCP/IP server has received 5092928 bytes of data
,2015-11-20T12:12:59.383Z SendDataTCPServer.js: TCP/IP server has received 5109792 bytes of data
,2015-11-20T12:12:59.395Z SendDataTCPServer.js: TCP/IP server has received 5127648 bytes of data
,2015-11-20T12:12:59.409Z SendDataTCPServer.js: TCP/IP server has received 5147488 bytes of data
,2015-11-20T12:12:59.421Z SendDataTCPServer.js: TCP/IP server has received 5165344 bytes of data
,2015-11-20T12:12:59.434Z SendDataTCPServer.js: TCP/IP server has received 5187168 bytes of data
,2015-11-20T12:12:59.448Z SendDataTCPServer.js: TCP/IP server has received 5210976 bytes of data
,2015-11-20T12:12:59.460Z SendDataTCPServer.js: TCP/IP server has received 5231808 bytes of data
,2015-11-20T12:12:59.474Z SendDataTCPServer.js: TCP/IP server has received 5253632 bytes of data
,2015-11-20T12:12:59.486Z SendDataTCPServer.js: TCP/IP server has received 5273472 bytes of data
,2015-11-20T12:12:59.499Z SendDataTCPServer.js: TCP/IP server has received 5292320 bytes of data
,2015-11-20T12:12:59.511Z SendDataTCPServer.js: TCP/IP server has received 5311168 bytes of data
,2015-11-20T12:12:59.525Z SendDataTCPServer.js: TCP/IP server has received 5331008 bytes of data
,2015-11-20T12:12:59.538Z SendDataTCPServer.js: TCP/IP server has received 5339936 bytes of data
,2015-11-20T12:12:59.552Z SendDataTCPServer.js: TCP/IP server has received 5355808 bytes of data
,2015-11-20T12:12:59.564Z SendDataTCPServer.js: TCP/IP server has received 5394496 bytes of data
,2015-11-20T12:12:59.577Z SendDataTCPServer.js: TCP/IP server has received 5395488 bytes of data
,2015-11-20T12:12:59.662Z SendDataTCPServer.js: TCP/IP server has received 5404416 bytes of data
,2015-11-20T12:12:59.675Z SendDataTCPServer.js: TCP/IP server has received 5424256 bytes of data
,2015-11-20T12:12:59.689Z SendDataTCPServer.js: TCP/IP server has received 5430208 bytes of data
,2015-11-20T12:12:59.762Z SendDataTCPServer.js: TCP/IP server has received 5441120 bytes of data
,2015-11-20T12:12:59.775Z SendDataTCPServer.js: TCP/IP server has received 5458976 bytes of data
,2015-11-20T12:12:59.789Z SendDataTCPServer.js: TCP/IP server has received 5480800 bytes of data
,2015-11-20T12:12:59.801Z SendDataTCPServer.js: TCP/IP server has received 5498656 bytes of data
,2015-11-20T12:12:59.812Z SendDataTCPServer.js: TCP/IP server has received 5513536 bytes of data
,2015-11-20T12:12:59.825Z SendDataTCPServer.js: TCP/IP server has received 5530400 bytes of data
,2015-11-20T12:12:59.839Z SendDataTCPServer.js: TCP/IP server has received 5549248 bytes of data
,2015-11-20T12:12:59.852Z SendDataTCPServer.js: TCP/IP server has received 5566112 bytes of data
,2015-11-20T12:12:59.865Z SendDataTCPServer.js: TCP/IP server has received 5582976 bytes of data
,2015-11-20T12:12:59.878Z SendDataTCPServer.js: TCP/IP server has received 5602816 bytes of data
,2015-11-20T12:12:59.891Z SendDataTCPServer.js: TCP/IP server has received 5623648 bytes of data
,2015-11-20T12:12:59.903Z SendDataTCPServer.js: TCP/IP server has received 5642496 bytes of data
,2015-11-20T12:12:59.917Z SendDataTCPServer.js: TCP/IP server has received 5662336 bytes of data
,2015-11-20T12:12:59.931Z SendDataTCPServer.js: TCP/IP server has received 5673248 bytes of data
,2015-11-20T12:12:59.944Z SendDataTCPServer.js: TCP/IP server has received 5680192 bytes of data
,2015-11-20T12:12:59.955Z SendDataTCPServer.js: TCP/IP server has received 5724832 bytes of data
,2015-11-20T12:12:59.971Z SendDataTCPServer.js: TCP/IP server has received 5749632 bytes of data
,2015-11-20T12:12:59.985Z SendDataTCPServer.js: TCP/IP server has received 5769472 bytes of data
,2015-11-20T12:12:59.998Z SendDataTCPServer.js: TCP/IP server has received 5791296 bytes of data
,2015-11-20T12:13:00.011Z SendDataTCPServer.js: TCP/IP server has received 5804192 bytes of data
,2015-11-20T12:13:00.024Z SendDataTCPServer.js: TCP/IP server has received 5828992 bytes of data
,2015-11-20T12:13:00.036Z SendDataTCPServer.js: TCP/IP server has received 5847840 bytes of data
,2015-11-20T12:13:00.049Z SendDataTCPServer.js: TCP/IP server has received 5866688 bytes of data
,2015-11-20T12:13:00.061Z SendDataTCPServer.js: TCP/IP server has received 5873632 bytes of data
,2015-11-20T12:13:00.074Z SendDataTCPServer.js: TCP/IP server has received 5876608 bytes of data
,2015-11-20T12:13:00.272Z SendDataTCPServer.js: TCP/IP server has received 5879584 bytes of data
,2015-11-20T12:13:00.283Z SendDataTCPServer.js: TCP/IP server has received 5924224 bytes of data
,2015-11-20T12:13:00.297Z SendDataTCPServer.js: TCP/IP server has received 5939104 bytes of data
,2015-11-20T12:13:00.334Z SendDataTCPServer.js: TCP/IP server has received 5951008 bytes of data
,2015-11-20T12:13:00.347Z SendDataTCPServer.js: TCP/IP server has received 5969856 bytes of data
,2015-11-20T12:13:00.361Z SendDataTCPServer.js: TCP/IP server has received 5987712 bytes of data
,2015-11-20T12:13:00.374Z SendDataTCPServer.js: TCP/IP server has received 6005568 bytes of data
,2015-11-20T12:13:00.388Z SendDataTCPServer.js: TCP/IP server has received 6014496 bytes of data
,2015-11-20T12:13:00.401Z SendDataTCPServer.js: TCP/IP server has received 6021440 bytes of data
,2015-11-20 13:13:00.409 ThaliTest[841:950162] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20T12:13:00.410Z SendDataTCPServer.js: TCP/IP server has received 6047232 bytes of data
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2043.OU3s0w==","peerName":"(null)","peerAvailable":true}]
,2015-11-20T12:13:00.422Z SendDataTCPServer.js: TCP/IP server has received 6072032 bytes of data
,2015-11-20T12:13:00.435Z SendDataTCPServer.js: TCP/IP server has received 6085920 bytes of data
,2015-11-20T12:13:00.446Z SendDataTCPServer.js: TCP/IP server has received 6102784 bytes of data
,2015-11-20T12:13:00.458Z SendDataTCPServer.js: TCP/IP server has received 6121632 bytes of data
,2015-11-20T12:13:00.471Z SendDataTCPServer.js: TCP/IP server has received 6142464 bytes of data
,2015-11-20T12:13:00.483Z SendDataTCPServer.js: TCP/IP server has received 6163296 bytes of data
,2015-11-20T12:13:00.496Z SendDataTCPServer.js: TCP/IP server has received 6187104 bytes of data
,2015-11-20T12:13:00.510Z SendDataTCPServer.js: TCP/IP server has received 6209920 bytes of data
,2015-11-20T12:13:00.522Z SendDataTCPServer.js: TCP/IP server has received 6229760 bytes of data
,2015-11-20T12:13:00.534Z SendDataTCPServer.js: TCP/IP server has received 6248608 bytes of data
,2015-11-20T12:13:00.547Z SendDataTCPServer.js: TCP/IP server has received 6270432 bytes of data
,2015-11-20T12:13:00.560Z SendDataTCPServer.js: TCP/IP server has received 6293248 bytes of data
,2015-11-20T12:13:00.573Z SendDataTCPServer.js: TCP/IP server has received 6316064 bytes of data
,2015-11-20T12:13:00.587Z SendDataTCPServer.js: TCP/IP server has received 6339872 bytes of data
,2015-11-20T12:13:00.601Z SendDataTCPServer.js: TCP/IP server has received 6340864 bytes of data
,2015-11-20T12:13:00.667Z SendDataTCPServer.js: TCP/IP server has received 6373600 bytes of data
,2015-11-20T12:13:00.680Z SendDataTCPServer.js: TCP/IP server has received 6403360 bytes of data
,2015-11-20T12:13:00.818Z SendDataTCPServer.js: TCP/IP server has received 6409312 bytes of data
,2015-11-20T12:13:00.831Z SendDataTCPServer.js: TCP/IP server has received 6447008 bytes of data
,2015-11-20T12:13:00.846Z SendDataTCPServer.js: TCP/IP server has received 6465856 bytes of data
,2015-11-20T12:13:00.897Z SendDataTCPServer.js: TCP/IP server has received 6467840 bytes of data
,2015-11-20T12:13:00.910Z SendDataTCPServer.js: TCP/IP server has received 6486688 bytes of data
,2015-11-20T12:13:00.923Z SendDataTCPServer.js: TCP/IP server has received 6501568 bytes of data
,2015-11-20T12:13:00.936Z SendDataTCPServer.js: TCP/IP server has received 6520416 bytes of data
,2015-11-20T12:13:00.949Z SendDataTCPServer.js: TCP/IP server has received 6536288 bytes of data
,2015-11-20T12:13:00.963Z SendDataTCPServer.js: TCP/IP server has received 6555136 bytes of data
,2015-11-20T12:13:00.977Z SendDataTCPServer.js: TCP/IP server has received 6573984 bytes of data
,2015-11-20T12:13:00.990Z SendDataTCPServer.js: TCP/IP server has received 6590848 bytes of data
,2015-11-20T12:13:01.004Z SendDataTCPServer.js: TCP/IP server has received 6607712 bytes of data
,2015-11-20T12:13:01.018Z SendDataTCPServer.js: TCP/IP server has received 6626560 bytes of data
,2015-11-20T12:13:01.030Z SendDataTCPServer.js: TCP/IP server has received 6643424 bytes of data
,2015-11-20T12:13:01.042Z SendDataTCPServer.js: TCP/IP server has received 6662272 bytes of data
,2015-11-20T12:13:01.056Z SendDataTCPServer.js: TCP/IP server has received 6683104 bytes of data
,2015-11-20T12:13:01.070Z SendDataTCPServer.js: TCP/IP server has received 6698976 bytes of data
,2015-11-20T12:13:01.084Z SendDataTCPServer.js: TCP/IP server has received 6720800 bytes of data
,2015-11-20T12:13:01.098Z SendDataTCPServer.js: TCP/IP server has received 6737664 bytes of data
,2015-11-20T12:13:01.111Z SendDataTCPServer.js: TCP/IP server has received 6757504 bytes of data
,2015-11-20T12:13:01.124Z SendDataTCPServer.js: TCP/IP server has received 6758496 bytes of data
,2015-11-20T12:13:01.148Z SendDataTCPServer.js: TCP/IP server has received 6783296 bytes of data
,2015-11-20T12:13:01.161Z SendDataTCPServer.js: TCP/IP server has received 6820992 bytes of data
,2015-11-20T12:13:01.175Z SendDataTCPServer.js: TCP/IP server has received 6821984 bytes of data
,2015-11-20T12:13:01.188Z SendDataTCPServer.js: TCP/IP server has received 6829920 bytes of data
,2015-11-20T12:13:01.202Z SendDataTCPServer.js: TCP/IP server has received 6839840 bytes of data
,2015-11-20T12:13:01.213Z SendDataTCPServer.js: TCP/IP server has received 6866624 bytes of data
,2015-11-20T12:13:01.227Z SendDataTCPServer.js: TCP/IP server has received 6876544 bytes of data
,2015-11-20T12:13:01.324Z SendDataTCPServer.js: TCP/IP server has received 6892416 bytes of data
,2015-11-20T12:13:01.335Z SendDataTCPServer.js: TCP/IP server has received 6921184 bytes of data
,2015-11-20T12:13:01.349Z SendDataTCPServer.js: TCP/IP server has received 6942016 bytes of data
,2015-11-20T12:13:01.360Z SendDataTCPServer.js: TCP/IP server has received 6957888 bytes of data
,2015-11-20T12:13:01.372Z SendDataTCPServer.js: TCP/IP server has received 6971776 bytes of data
,2015-11-20T12:13:01.384Z SendDataTCPServer.js: TCP/IP server has received 6984672 bytes of data
,2015-11-20T12:13:01.396Z SendDataTCPServer.js: TCP/IP server has received 6999552 bytes of data
,2015-11-20T12:13:01.410Z SendDataTCPServer.js: TCP/IP server has received 7018400 bytes of data
,2015-11-20T12:13:01.422Z SendDataTCPServer.js: TCP/IP server has received 7033280 bytes of data
,2015-11-20T12:13:01.435Z SendDataTCPServer.js: TCP/IP server has received 7050144 bytes of data
,2015-11-20T12:13:01.448Z SendDataTCPServer.js: TCP/IP server has received 7068000 bytes of data
,2015-11-20T12:13:01.461Z SendDataTCPServer.js: TCP/IP server has received 7088832 bytes of data
,2015-11-20T12:13:01.472Z SendDataTCPServer.js: TCP/IP server has received 7106688 bytes of data
,2015-11-20T12:13:01.486Z SendDataTCPServer.js: TCP/IP server has received 7126528 bytes of data
,2015-11-20T12:13:01.498Z SendDataTCPServer.js: TCP/IP server has received 7146368 bytes of data
,2015-11-20T12:13:01.511Z SendDataTCPServer.js: TCP/IP server has received 7163232 bytes of data
,2015-11-20T12:13:01.524Z SendDataTCPServer.js: TCP/IP server has received 7184064 bytes of data
,2015-11-20T12:13:01.537Z SendDataTCPServer.js: TCP/IP server has received 7202912 bytes of data
,2015-11-20T12:13:01.548Z SendDataTCPServer.js: TCP/IP server has received 7222752 bytes of data
,2015-11-20T12:13:01.561Z SendDataTCPServer.js: TCP/IP server has received 7241600 bytes of data
,2015-11-20T12:13:01.573Z SendDataTCPServer.js: TCP/IP server has received 7260448 bytes of data
,2015-11-20T12:13:01.586Z SendDataTCPServer.js: TCP/IP server has received 7279296 bytes of data
,2015-11-20T12:13:01.599Z SendDataTCPServer.js: TCP/IP server has received 7298144 bytes of data
,2015-11-20T12:13:01.610Z SendDataTCPServer.js: TCP/IP server has received 7316000 bytes of data
,2015-11-20T12:13:01.624Z SendDataTCPServer.js: TCP/IP server has received 7336832 bytes of data
,2015-11-20T12:13:01.637Z SendDataTCPServer.js: TCP/IP server has received 7355680 bytes of data
,2015-11-20T12:13:01.650Z SendDataTCPServer.js: TCP/IP server has received 7356672 bytes of data
,2015-11-20T12:13:01.676Z SendDataTCPServer.js: TCP/IP server has received 7389408 bytes of data
,2015-11-20T12:13:01.690Z SendDataTCPServer.js: TCP/IP server has received 7428096 bytes of data
,2015-11-20T12:13:01.703Z SendDataTCPServer.js: TCP/IP server has received 7430080 bytes of data
,2015-11-20T12:13:01.715Z SendDataTCPServer.js: TCP/IP server has received 7431072 bytes of data
,2015-11-20T12:13:01.727Z SendDataTCPServer.js: TCP/IP server has received 7450912 bytes of data
,2015-11-20T12:13:01.741Z SendDataTCPServer.js: TCP/IP server has received 7469760 bytes of data
,2015-11-20T12:13:01.755Z SendDataTCPServer.js: TCP/IP server has received 7481664 bytes of data
,2015-11-20T12:13:01.767Z SendDataTCPServer.js: TCP/IP server has received 7500512 bytes of data
,2015-11-20T12:13:01.852Z SendDataTCPServer.js: TCP/IP server has received 7533248 bytes of data
,2015-11-20T12:13:01.866Z SendDataTCPServer.js: TCP/IP server has received 7560032 bytes of data
,2015-11-20T12:13:01.891Z SendDataTCPServer.js: TCP/IP server has received 7575904 bytes of data
,2015-11-20T12:13:01.904Z SendDataTCPServer.js: TCP/IP server has received 7592768 bytes of data
,2015-11-20T12:13:01.916Z SendDataTCPServer.js: TCP/IP server has received 7609632 bytes of data
,2015-11-20T12:13:01.930Z SendDataTCPServer.js: TCP/IP server has received 7626496 bytes of data
,2015-11-20T12:13:01.944Z SendDataTCPServer.js: TCP/IP server has received 7643360 bytes of data
,2015-11-20T12:13:01.955Z SendDataTCPServer.js: TCP/IP server has received 7659232 bytes of data
,2015-11-20T12:13:01.967Z SendDataTCPServer.js: TCP/IP server has received 7674112 bytes of data
,2015-11-20T12:13:01.978Z SendDataTCPServer.js: TCP/IP server has received 7688992 bytes of data
,2015-11-20T12:13:01.991Z SendDataTCPServer.js: TCP/IP server has received 7705856 bytes of data
,2015-11-20T12:13:02.003Z SendDataTCPServer.js: TCP/IP server has received 7723712 bytes of data
,2015-11-20T12:13:02.015Z SendDataTCPServer.js: TCP/IP server has received 7742560 bytes of data
,2015-11-20T12:13:02.029Z SendDataTCPServer.js: TCP/IP server has received 7764384 bytes of data
,2015-11-20T12:13:02.041Z SendDataTCPServer.js: TCP/IP server has received 7784224 bytes of data
,2015-11-20T12:13:02.054Z SendDataTCPServer.js: TCP/IP server has received 7806048 bytes of data
,2015-11-20T12:13:02.067Z SendDataTCPServer.js: TCP/IP server has received 7826880 bytes of data
,2015-11-20T12:13:02.078Z SendDataTCPServer.js: TCP/IP server has received 7845728 bytes of data
,2015-11-20T12:13:02.091Z SendDataTCPServer.js: TCP/IP server has received 7866560 bytes of data
,2015-11-20T12:13:02.105Z SendDataTCPServer.js: TCP/IP server has received 7888384 bytes of data
,2015-11-20T12:13:02.117Z SendDataTCPServer.js: TCP/IP server has received 7904256 bytes of data
,2015-11-20T12:13:02.130Z SendDataTCPServer.js: TCP/IP server has received 7926080 bytes of data
,2015-11-20T12:13:02.144Z SendDataTCPServer.js: TCP/IP server has received 7942944 bytes of data
,2015-11-20T12:13:02.157Z SendDataTCPServer.js: TCP/IP server has received 7952864 bytes of data
,2015-11-20T12:13:02.368Z SendDataTCPServer.js: TCP/IP server has received 7954848 bytes of data
,2015-11-20T12:13:02.380Z SendDataTCPServer.js: TCP/IP server has received 7976672 bytes of data
,2015-11-20T12:13:02.392Z SendDataTCPServer.js: TCP/IP server has received 7993536 bytes of data
,2015-11-20T12:13:02.405Z SendDataTCPServer.js: TCP/IP server has received 8014368 bytes of data
,2015-11-20T12:13:02.418Z SendDataTCPServer.js: TCP/IP server has received 8029248 bytes of data
,2015-11-20T12:13:02.431Z SendDataTCPServer.js: TCP/IP server has received 8045120 bytes of data
,2015-11-20T12:13:02.443Z SendDataTCPServer.js: TCP/IP server has received 8060992 bytes of data
,2015-11-20T12:13:02.456Z SendDataTCPServer.js: TCP/IP server has received 8076864 bytes of data
,2015-11-20T12:13:02.468Z SendDataTCPServer.js: TCP/IP server has received 8092736 bytes of data
,2015-11-20T12:13:02.480Z SendDataTCPServer.js: TCP/IP server has received 8110592 bytes of data
,2015-11-20T12:13:02.492Z SendDataTCPServer.js: TCP/IP server has received 8128448 bytes of data
,2015-11-20T12:13:02.505Z SendDataTCPServer.js: TCP/IP server has received 8149280 bytes of data
,2015-11-20T12:13:02.518Z SendDataTCPServer.js: TCP/IP server has received 8171104 bytes of data
,2015-11-20T12:13:02.532Z SendDataTCPServer.js: TCP/IP server has received 8196896 bytes of data
,2015-11-20T12:13:02.546Z SendDataTCPServer.js: TCP/IP server has received 8219712 bytes of data
,2015-11-20T12:13:02.558Z SendDataTCPServer.js: TCP/IP server has received 8240544 bytes of data
,2015-11-20T12:13:02.570Z SendDataTCPServer.js: TCP/IP server has received 8262368 bytes of data
,2015-11-20T12:13:02.584Z SendDataTCPServer.js: TCP/IP server has received 8284192 bytes of data
,2015-11-20T12:13:02.596Z SendDataTCPServer.js: TCP/IP server has received 8304032 bytes of data
,2015-11-20T12:13:02.610Z SendDataTCPServer.js: TCP/IP server has received 8325856 bytes of data
,2015-11-20T12:13:02.635Z SendDataTCPServer.js: TCP/IP server has received 8358592 bytes of data
,2015-11-20T12:13:02.648Z SendDataTCPServer.js: TCP/IP server has received 8389344 bytes of data
,2015-11-20T12:13:02.661Z SendDataTCPServer.js: TCP/IP server has received 8406208 bytes of data
,2015-11-20T12:13:02.672Z SendDataTCPServer.js: TCP/IP server has received 8423072 bytes of data
,2015-11-20T12:13:02.686Z SendDataTCPServer.js: TCP/IP server has received 8441920 bytes of data
,2015-11-20T12:13:02.700Z SendDataTCPServer.js: TCP/IP server has received 8442912 bytes of data
,2015-11-20T12:13:02.711Z SendDataTCPServer.js: TCP/IP server has received 8471680 bytes of data
,2015-11-20T12:13:02.725Z SendDataTCPServer.js: TCP/IP server has received 8491520 bytes of data
,2015-11-20T12:13:02.776Z SendDataTCPServer.js: TCP/IP server has received 8512352 bytes of data
,2015-11-20T12:13:02.790Z SendDataTCPServer.js: TCP/IP server has received 8513344 bytes of data
,2015-11-20T12:13:02.909Z SendDataTCPServer.js: TCP/IP server has received 8558976 bytes of data
,2015-11-20T12:13:02.925Z SendDataTCPServer.js: TCP/IP server has received 8575840 bytes of data
,2015-11-20T12:13:02.974Z SendDataTCPServer.js: TCP/IP server has received 8577824 bytes of data
,2015-11-20T12:13:02.986Z SendDataTCPServer.js: TCP/IP server has received 8594688 bytes of data
,2015-11-20T12:13:02.997Z SendDataTCPServer.js: TCP/IP server has received 8610560 bytes of data
,2015-11-20T12:13:03.011Z SendDataTCPServer.js: TCP/IP server has received 8617504 bytes of data
,2015-11-20T12:13:03.022Z SendDataTCPServer.js: TCP/IP server has received 8625440 bytes of data
,2015-11-20T12:13:03.034Z SendDataTCPServer.js: TCP/IP server has received 8657184 bytes of data
,2015-11-20T12:13:03.047Z SendDataTCPServer.js: TCP/IP server has received 8659168 bytes of data
,2015-11-20T12:13:03.061Z SendDataTCPServer.js: TCP/IP server has received 8678016 bytes of data
,2015-11-20T12:13:03.073Z SendDataTCPServer.js: TCP/IP server has received 8694880 bytes of data
,2015-11-20T12:13:03.085Z SendDataTCPServer.js: TCP/IP server has received 8711744 bytes of data
,2015-11-20T12:13:03.099Z SendDataTCPServer.js: TCP/IP server has received 8732576 bytes of data
,2015-11-20T12:13:03.111Z SendDataTCPServer.js: TCP/IP server has received 8749440 bytes of data
,2015-11-20T12:13:03.123Z SendDataTCPServer.js: TCP/IP server has received 8769280 bytes of data
,2015-11-20T12:13:03.135Z SendDataTCPServer.js: TCP/IP server has received 8789120 bytes of data
,2015-11-20T12:13:03.149Z SendDataTCPServer.js: TCP/IP server has received 8809952 bytes of data
,2015-11-20T12:13:03.161Z SendDataTCPServer.js: TCP/IP server has received 8826816 bytes of data
,2015-11-20T12:13:03.175Z SendDataTCPServer.js: TCP/IP server has received 8848640 bytes of data
,2015-11-20T12:13:03.188Z SendDataTCPServer.js: TCP/IP server has received 8869472 bytes of data
,2015-11-20T12:13:03.202Z SendDataTCPServer.js: TCP/IP server has received 8889312 bytes of data
,2015-11-20T12:13:03.215Z SendDataTCPServer.js: TCP/IP server has received 8901216 bytes of data
,2015-11-20T12:13:03.229Z SendDataTCPServer.js: TCP/IP server has received 8909152 bytes of data
,2015-11-20T12:13:03.241Z SendDataTCPServer.js: TCP/IP server has received 8937920 bytes of data
,2015-11-20T12:13:03.304Z SendDataTCPServer.js: TCP/IP server has received 8965696 bytes of data
,2015-11-20T12:13:03.441Z SendDataTCPServer.js: TCP/IP server has received 9001408 bytes of data
,2015-11-20T12:13:03.454Z SendDataTCPServer.js: TCP/IP server has received 9025216 bytes of data
,2015-11-20T12:13:03.490Z SendDataTCPServer.js: TCP/IP server has received 9062912 bytes of data
,2015-11-20T12:13:03.504Z SendDataTCPServer.js: TCP/IP server has received 9078784 bytes of data
,2015-11-20T12:13:03.517Z SendDataTCPServer.js: TCP/IP server has received 9094656 bytes of data
,2015-11-20T12:13:03.531Z SendDataTCPServer.js: TCP/IP server has received 9113504 bytes of data
,2015-11-20T12:13:03.544Z SendDataTCPServer.js: TCP/IP server has received 9130368 bytes of data
,2015-11-20T12:13:03.556Z SendDataTCPServer.js: TCP/IP server has received 9148224 bytes of data
,2015-11-20T12:13:03.569Z SendDataTCPServer.js: TCP/IP server has received 9167072 bytes of data
,2015-11-20T12:13:03.581Z SendDataTCPServer.js: TCP/IP server has received 9184928 bytes of data
,2015-11-20T12:13:03.592Z SendDataTCPServer.js: TCP/IP server has received 9202784 bytes of data
,2015-11-20T12:13:03.604Z SendDataTCPServer.js: TCP/IP server has received 9221632 bytes of data
,2015-11-20T12:13:03.616Z SendDataTCPServer.js: TCP/IP server has received 9236512 bytes of data
,2015-11-20T12:13:03.629Z SendDataTCPServer.js: TCP/IP server has received 9258336 bytes of data
,2015-11-20T12:13:03.641Z SendDataTCPServer.js: TCP/IP server has received 9274208 bytes of data
,2015-11-20T12:13:03.652Z SendDataTCPServer.js: TCP/IP server has received 9290080 bytes of data
,2015-11-20T12:13:03.667Z SendDataTCPServer.js: TCP/IP server has received 9312896 bytes of data
,2015-11-20T12:13:03.681Z SendDataTCPServer.js: TCP/IP server has received 9331744 bytes of data
,2015-11-20T12:13:03.693Z SendDataTCPServer.js: TCP/IP server has received 9351584 bytes of data
,2015-11-20T12:13:03.707Z SendDataTCPServer.js: TCP/IP server has received 9374400 bytes of data
,2015-11-20T12:13:03.719Z SendDataTCPServer.js: TCP/IP server has received 9393248 bytes of data
,2015-11-20T12:13:03.731Z SendDataTCPServer.js: TCP/IP server has received 9411104 bytes of data
,2015-11-20T12:13:03.745Z SendDataTCPServer.js: TCP/IP server has received 9415072 bytes of data
,2015-11-20T12:13:03.758Z SendDataTCPServer.js: TCP/IP server has received 9430944 bytes of data
,2015-11-20T12:13:03.771Z SendDataTCPServer.js: TCP/IP server has received 9453760 bytes of data
,2015-11-20T12:13:03.810Z SendDataTCPServer.js: TCP/IP server has received 9457728 bytes of data
,2015-11-20T12:13:03.824Z SendDataTCPServer.js: TCP/IP server has received 9483520 bytes of data
,2015-11-20T12:13:03.947Z SendDataTCPServer.js: TCP/IP server has received 9493440 bytes of data
,2015-11-20T12:13:03.959Z SendDataTCPServer.js: TCP/IP server has received 9526176 bytes of data
,2015-11-20T12:13:03.973Z SendDataTCPServer.js: TCP/IP server has received 9547008 bytes of data
,2015-11-20T12:13:03.986Z SendDataTCPServer.js: TCP/IP server has received 9558912 bytes of data
,2015-11-20T12:13:03.997Z SendDataTCPServer.js: TCP/IP server has received 9573792 bytes of data
,2015-11-20T12:13:04.011Z SendDataTCPServer.js: TCP/IP server has received 9590656 bytes of data
,2015-11-20T12:13:04.022Z SendDataTCPServer.js: TCP/IP server has received 9605536 bytes of data
,2015-11-20T12:13:04.034Z SendDataTCPServer.js: TCP/IP server has received 9620416 bytes of data
,2015-11-20T12:13:04.048Z SendDataTCPServer.js: TCP/IP server has received 9639264 bytes of data
,2015-11-20T12:13:04.061Z SendDataTCPServer.js: TCP/IP server has received 9656128 bytes of data
,2015-11-20T12:13:04.075Z SendDataTCPServer.js: TCP/IP server has received 9674976 bytes of data
,2015-11-20T12:13:04.088Z SendDataTCPServer.js: TCP/IP server has received 9695808 bytes of data
,2015-11-20T12:13:04.100Z SendDataTCPServer.js: TCP/IP server has received 9713664 bytes of data
,2015-11-20T12:13:04.111Z SendDataTCPServer.js: TCP/IP server has received 9730528 bytes of data
,2015-11-20T12:13:04.124Z SendDataTCPServer.js: TCP/IP server has received 9751360 bytes of data
,2015-11-20T12:13:04.136Z SendDataTCPServer.js: TCP/IP server has received 9768224 bytes of data
,2015-11-20T12:13:04.148Z SendDataTCPServer.js: TCP/IP server has received 9785088 bytes of data
,2015-11-20T12:13:04.159Z SendDataTCPServer.js: TCP/IP server has received 9802944 bytes of data
,2015-11-20T12:13:04.171Z SendDataTCPServer.js: TCP/IP server has received 9821792 bytes of data
,2015-11-20T12:13:04.184Z SendDataTCPServer.js: TCP/IP server has received 9841632 bytes of data
,2015-11-20T12:13:04.196Z SendDataTCPServer.js: TCP/IP server has received 9861472 bytes of data
,2015-11-20T12:13:04.210Z SendDataTCPServer.js: TCP/IP server has received 9880320 bytes of data
,2015-11-20T12:13:04.221Z SendDataTCPServer.js: TCP/IP server has received 9895200 bytes of data
,2015-11-20T12:13:04.234Z SendDataTCPServer.js: TCP/IP server has received 9913056 bytes of data
,2015-11-20T12:13:04.246Z SendDataTCPServer.js: TCP/IP server has received 9929920 bytes of data
,2015-11-20T12:13:04.257Z SendDataTCPServer.js: TCP/IP server has received 9944800 bytes of data
,2015-11-20T12:13:04.270Z SendDataTCPServer.js: TCP/IP server has received 9945792 bytes of data
,2015-11-20T12:13:04.283Z SendDataTCPServer.js: TCP/IP server has received 9975552 bytes of data
,2015-11-20T12:13:04.297Z SendDataTCPServer.js: TCP/IP server has received 9993408 bytes of data
,2015-11-20T12:13:04.348Z SendDataTCPServer.js: TCP/IP server has received 9994400 bytes of data
,2015-11-20T12:13:04.485Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20 13:13:04.506 ThaliTest[841:951917] server session: not connected Apple-Iphone5-1_PT2716
,2015-11-20 13:13:09.418 ThaliTest[841:950162] multipeer session: restart
,2015-11-20 13:13:09.429 ThaliTest[841:950162] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:13:09.430 ThaliTest[841:950162] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:13:09.430 ThaliTest[841:950162] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:13:39.418 ThaliTest[841:950162] multipeer session: restart
,2015-11-20 13:13:39.429 ThaliTest[841:950162] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
2015-11-20 13:13:39.429 ThaliTest[841:950162] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:13:39.429 ThaliTest[841:950162] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
,2015-11-20 13:13:59.226 ThaliTest[841:950162] client: lost peer: Apple-Iphone5s-1_PT497.PdI1bg==
2015-11-20 13:13:59.226 ThaliTest[841:950162] client session: onPeerLost: Apple-Iphone5s-1_PT497.PdI1bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:14:00.222 ThaliTest[841:950162] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT497.PdI1bg==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:14:09.418 ThaliTest[841:950162] multipeer session: restart
,2015-11-20 13:14:09.429 ThaliTest[841:950162] client: found peer: Apple-Iphone5-1_PT2716.py/N2Q==
,2015-11-20 13:14:09.484 ThaliTest[841:950162] client: found peer: Apple-Iphone6-1_PT2043.OU3s0w==
2015-11-20 13:14:09.484 ThaliTest[841:950162] client: found peer: Apple-Iphone5s-1_PT497.PdI1bg==
,2015-11-20 13:14:39.418 ThaliTest[841:950162] multipeer session: restart
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-11-20 13:14:42.303 ThaliTest[841:950353] jxcore: stopBroadcasting
,2015-11-20 13:14:42.303 ThaliTest[841:950353] THEMultipeerSession stopping peer
,2015-11-20 13:14:42.304 ThaliTest[841:950353] multipeer session: stop timer
,2015-11-20 13:14:42.304 ThaliTest[841:950353] server session: disconnect
2015-11-20 13:14:42.304 ThaliTest[841:950353] server session: stateChange:2->0 Apple-Iphone6-1_PT2043
,2015-11-20 13:14:42.307 ThaliTest[841:950353] server session: disconnect
2015-11-20 13:14:42.307 ThaliTest[841:950353] server session: stateChange:2->0 Apple-Iphone5-1_PT2716
,2015-11-20 13:14:42.313 ThaliTest[841:950353] server session: disconnect
2015-11-20 13:14:42.313 ThaliTest[841:950353] server session: stateChange:2->0 Apple-Iphone5s-1_PT497
,2015-11-20 13:14:42.317 ThaliTest[841:950353] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-20T12:14:42.332Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20T12:14:42.332Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20T12:14:42.333Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20T12:14:42.333Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,2015-11-20T12:14:42.333Z SendDataTCPServer.js: TCP/IP server is close
,2015-11-20T12:14:42.333Z SendDataTCPServer.js: TCP/IP server is close
,2015-11-20T12:14:42.334Z SendDataTCPServer.js: TCP/IP server is close
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":29961,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT2716.py/N2Q==\",\"time\":52469,\,"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":58779,\"result\":\"OK\",\"connections\":2}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT7072.5z,bvNA==\",\"time\":26141,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":29961,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":31099,\"result\":\"OK\",\"connections\":1},,{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":31207,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT2043.OU3s0w==\",\"time\":33577,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT2716.py/N2Q==\",\"time\":5246,9,\"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-IpadAir2-1_PT7072.5zbvNA==\",\"time\":57845,\"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":58779,\"result\":\"OK\",\"connections\":2},{\"name\":\"Apple-Ip,adAir2-1_PT7072.5zbvNA==\",\"time\":70969,\"result\":\"OK\",\"connections\":3},{\"name\":\"Apple-Iphone5-1_PT2716.py/N2Q==\",\"time\":84289,\"result\":\"OK\",\"connections\":3},{\"name\":\"Apple-Iphone5s-1_PT497.PdI1bg==\",\"time\":107161,\"result\":\"OK\",,\"connections\":4}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
