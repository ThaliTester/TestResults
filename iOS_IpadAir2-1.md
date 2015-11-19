#### Test 5119382166efe78_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5119382166efe78/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/E9336B3D-D25F-42D3-8261-84B335CF3108/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E9336B3D-D25F-42D3-8261-84B335CF3108/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5119382166efe78/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5119382166efe78/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/248009D0-A01B-49D3-B069-0610B8AF9A3A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50280"
,(lldb)     command script import "/tmp/E9336B3D-D25F-42D3-8261-84B335CF3108/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-19 09:50:18.125 ThaliTest[749:783795] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9802B39C-9057-4465-8A83-7D82222B2AD7/Library/Cookies/Cookies.binarycookies
,2015-11-19 09:50:18.415 ThaliTest[749:783795] Apache Cordova native platform version 3.9.2 is starting.
2015-11-19 09:50:18.415 ThaliTest[749:783795] Multi-tasking -> Device: YES, App: YES
,2015-11-19 09:50:18.422 ThaliTest[749:783795] Unlimited access to network resources
,2015-11-19 09:50:18.428 ThaliTest[749:783795] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-19 09:50:22.501 ThaliTest[749:783795] Resetting plugins due to page load.
,2015-11-19 09:50:23.761 ThaliTest[749:783795] Finished load of: file:///var/mobile/Containers/Bundle/Application/248009D0-A01B-49D3-B069-0610B8AF9A3A/ThaliTest.app/www/index.html
,2015-11-19 09:50:23.899 ThaliTest[749:783795] JXcore Cordova plugin initializing
,2015-11-19 09:50:23.900 ThaliTest[749:784002] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
,toggleBluetooth - 
,Warning: iOS does not support ToggleBluetooth
We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,my name is : Apple-IpadAir2-1_PT4426
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false,, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ct]
printNetworkInfo
ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false,, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
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
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4cd3:f4ff:feb9:a4
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"1000000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":2,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"500000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 54898
2015-11-19 10:02:07.341 ThaliTest[749:784002] jxcore: startBroadcasting
,2015-11-19 10:02:07.348 ThaliTest[749:784002] server: starting Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:02:07.349 ThaliTest[749:784002] multipeer session: start timer: 0x1940e970
2015-11-19 10:02:07.350 ThaliTest[749:784002] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT4426
,2015-11-19 10:02:07.350 ThaliTest[749:784002] jxcore: startBroadcasting: success
StartBroadcasting started ok
,TCP/IP server  is bound to : undefined
,2015-11-19 10:02:07.983 ThaliTest[749:783795] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:10.650 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-19 10:02:12.990 ThaliTest[749:784002] jxcore: disconnect
2015-11-19 10:02:12.990 ThaliTest[749:784002] jxcore: disconnect: fail
Connect (retry count 0) to peer Apple-Iphone6-1_PT5791.6xWUmg== with availability status: true
do connect now
2015-11-19 10:02:12.990 ThaliTest[749:784002] jxcore: connect Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:02:12.991 ThaliTest[749:784002] client session: connect
2015-11-19 10:02:12.991 ThaliTest[749:784002] client session: stateChange:0->1 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:13.814 ThaliTest[749:783795] multipeer session: reset timer
2015-11-19 10:02:13.814 ThaliTest[749:783795] multipeer session: stop timer
2015-11-19 10:02:13.814 ThaliTest[749:783795] multipeer session: start timer: 0x1940e970
2015-11-19 10:02:13.814 ThaliTest[749:783795] server session: connect
2015-11-19 10:02:13.814 ThaliTest[749:783795] server session: stateChange:0->1 Apple-Iphone6-1_PT5791
,2015-11-19 10:02:13.816 ThaliTest[749:783795] server: accepting invitation Apple-Iphone6-1_PT5791
,2015-11-19 10:02:16.383 ThaliTest[749:785723] server session: connected
2015-11-19 10:02:16.383 ThaliTest[749:785723] server session: stateChange:1->2 Apple-Iphone6-1_PT5791
,2015-11-19 10:02:16.386 ThaliTest[749:783795] server relay: connected (to port: 54898)
,TCP/IP server connected
,TCP/IP server has received 15330 bytes of data
,TCP/IP server has received 111690 bytes of data
,TCP/IP server has received 118260 bytes of data
,TCP/IP server has received 249332 bytes of data
,TCP/IP server has received 258420 bytes of data
,TCP/IP server has received 275940 bytes of data
,TCP/IP server has received 282510 bytes of data
,TCP/IP server has received 350400 bytes of data
,TCP/IP server has received 354780 bytes of data
,TCP/IP server has received 388542 bytes of data
,TCP/IP server has received 494940 bytes of data
,TCP/IP server has received 551880 bytes of data
,TCP/IP server has received 600060 bytes of data
,TCP/IP server has received 604440 bytes of data
,TCP/IP server has received 606630 bytes of data
,TCP/IP server has received 621960 bytes of data
,TCP/IP server has received 683280 bytes of data
,TCP/IP server has received 716130 bytes of data
,TCP/IP server has received 718320 bytes of data
,TCP/IP server has received 746790 bytes of data
,TCP/IP server has received 821250 bytes of data
,TCP/IP server has received 832200 bytes of data
,TCP/IP server has received 880380 bytes of data
,TCP/IP server has received 930750 bytes of data
,TCP/IP server has received 977854 bytes of data
,TCP/IP server has received 1000002 bytes of data
,2015-11-19 10:02:18.558 ThaliTest[749:785716] client session: connected
2015-11-19 10:02:18.558 ThaliTest[749:785716] client session: stateChange:1->2 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:18.559 ThaliTest[749:785716] client session: fireConnectCallback: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:02:18.559 ThaliTest[749:785716] jxcore: connect: success
CLIENT connected to 54903, error: null
,CLIENT starting client 
,2015-11-19 10:02:18.561 ThaliTest[749:783795] client: relay established
2015-11-19 10:02:18.561 ThaliTest[749:783795] client: new accepted socket: 0x1a988300
,CLIENT now sending 1000000 bytes of data
,CLIENT is data received : 0
,CLIENT is data received : 0
,CLIENT is data received : 0
,CLIENT is data received : 0
,CLIENT is data received : 10000
,CLIENT is data received : 20000
,CLIENT is data received : 20000
,CLIENT is data received : 30000
,CLIENT is data received : 30000
,CLIENT is data received : 40000
,2015-11-19 10:02:28.288 ThaliTest[749:785716] server session: not connected Apple-Iphone6-1_PT5791
,Receiving data timeout now
CLIENT closeClientSocket
,2015-11-19 10:02:30.571 ThaliTest[749:783795] client: socket closed
2015-11-19 10:02:30.571 ThaliTest[749:783795] client relay: socket disconnected
2015-11-19 10:02:30.571 ThaliTest[749:783795] client relay: 0x1a988300 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:02:30.571 ThaliTest[749:783795] client session: socket closed: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:0,2:30.571 ThaliTest[749:783795] client session: onLinkFailure: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:02:30.571 ThaliTest[749:783795] client session: disconnect
2015-11-19 10:02:30.571 ThaliTest[749:783795] client session: stateChange:2->0 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:30.573 ThaliTest[749:783795] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT5791.6xWUmg==
tryAgain afer: 5000 ms.
----------------- closeClientSocket
CLIENT is closed
,re-try now : Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:38.386 ThaliTest[749:783795] multipeer session: reset timer
2015-11-19 10:02:38.387 ThaliTest[749:783795] multipeer session: stop timer
2015-11-19 10:02:38.387 ThaliTest[749:783795] multipeer session: start timer: 0x1940e970
2015-11-19 10:02:38.387 ThaliTest[749:783795] server: disconnecting to refresh session (Apple-Iphone6-1_PT5791)
2015-11-19 10:02:38.387 ThaliTest[749:783795] server session: disconnect
2015-11-19 10:02:38.387 ThaliTest[749:783795] server session: stateChange:2->0 Apple-Iphone6-1_PT5791
,TCP/IP server is ended
,TCP/IP server is close
,2015-11-19 10:02:38.441 ThaliTest[749:783795] server session: connect
2015-11-19 10:02:38.441 ThaliTest[749:783795] server session: stateChange:0->1 Apple-Iphone6-1_PT5791
,2015-11-19 10:02:38.443 ThaliTest[749:783795] server: accepting invitation Apple-Iphone6-1_PT5791
,2015-11-19 10:02:40.590 ThaliTest[749:784002] jxcore: disconnect
,2015-11-19 10:02:40.590 ThaliTest[749:784002] jxcore: disconnect: fail
Connect (retry count 1) to peer Apple-Iphone6-1_PT5791.6xWUmg== with availability status: true
do connect now
,2015-11-19 10:02:40.591 ThaliTest[749:784002] jxcore: connect Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:02:40.591 ThaliTest[749:784002] client session: connect
2015-11-19 10:02:40.591 ThaliTest[749:784002] client session: stateChange:0->1 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:41.332 ThaliTest[749:785797] server session: connected
2015-11-19 10:02:41.332 ThaliTest[749:785797] server session: stateChange:1->2 Apple-Iphone6-1_PT5791
,2015-11-19 10:02:41.336 ThaliTest[749:783795] server relay: connected (to port: 54898)
,TCP/IP server connected
,TCP/IP server has received 4380 bytes of data
,TCP/IP server has received 6570 bytes of data
,TCP/IP server has received 10950 bytes of data
,TCP/IP server has received 13140 bytes of data
,TCP/IP server has received 52052 bytes of data
,TCP/IP server has received 153300 bytes of data
,TCP/IP server has received 155490 bytes of data
,TCP/IP server has received 201480 bytes of data
,TCP/IP server has received 251850 bytes of data
,TCP/IP server has received 256230 bytes of data
,TCP/IP server has received 282510 bytes of data
,TCP/IP server has received 335070 bytes of data
,TCP/IP server has received 337260 bytes of data
,TCP/IP server has received 346020 bytes of data
,TCP/IP server has received 477092 bytes of data
,TCP/IP server has received 486180 bytes of data
,TCP/IP server has received 497130 bytes of data
,TCP/IP server has received 525458 bytes of data
,TCP/IP server has received 567210 bytes of data
,TCP/IP server has received 624150 bytes of data
,TCP/IP server has received 661380 bytes of data
,TCP/IP server has received 667950 bytes of data
,TCP/IP server has received 740220 bytes of data
,TCP/IP server has received 770880 bytes of data
,TCP/IP server has received 840960 bytes of data
,TCP/IP server has received 869430 bytes of data
,TCP/IP server has received 980002 bytes of data
,2015-11-19 10:02:43.295 ThaliTest[749:785797] client session: connected
2015-11-19 10:02:43.295 ThaliTest[749:785797] client session: stateChange:1->2 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:43.297 ThaliTest[749:785797] client session: fireConnectCallback: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:02:43.297 ThaliTest[749:785797] jxcore: connect: success
CLIENT connected to 54908, error: null
CLIENT starting client 
,2015-11-19 10:02:43.299 ThaliTest[749:783795] client: relay established
2015-11-19 10:02:43.299 ThaliTest[749:783795] client: new accepted socket: 0x176514b0
,CLIENT now sending 960000 bytes of data
,CLIENT is data received : 40000
,CLIENT is data received : 40000
,CLIENT is data received : 40000
,CLIENT is data received : 40000
,CLIENT is data received : 50000
,CLIENT is data received : 50000
,CLIENT is data received : 50000
,CLIENT is data received : 50000
,2015-11-19 10:02:53.452 ThaliTest[749:785797] server session: not connected Apple-Iphone6-1_PT5791
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,2015-11-19 10:02:54.602 ThaliTest[749:783795] client: socket closed
2015-11-19 10:02:54.603 ThaliTest[749:783795] client relay: socket disconnected
----------------- closeClientSocket
2015-11-19 10:02:54.603 ThaliTest[749:783795] client relay: 0x176514b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:02:54.603 ThaliTest[749:783795] client session: socket closed: Apple-Iphon,e6-1_PT5791.6xWUmg==
CLIENT is closed
2015-11-19 10:02:54.603 ThaliTest[749:783795] client session: onLinkFailure: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:02:54.603 ThaliTest[749:783795] client session: disconnect
2015-11-19 10:02:54.603 ThaliTest[749:783795] client session: stateChange:2->0 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:54.605 ThaliTest[749:783795] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT5791.6xWUmg==
,re-try now : Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:03.877 ThaliTest[749:783795] multipeer session: reset timer
2015-11-19 10:03:03.877 ThaliTest[749:783795] multipeer session: stop timer
2015-11-19 10:03:03.877 ThaliTest[749:783795] multipeer session: start timer: 0x1940e970
2015-11-19 10:03:03.877 ThaliTest[749:783795] server: disconnecting to refresh session (Apple-Iphone6-1_PT5791)
,2015-11-19 10:03:03.877 ThaliTest[749:783795] server session: disconnect
,2015-11-19 10:03:03.878 ThaliTest[749:783795] server session: stateChange:2->0 Apple-Iphone6-1_PT5791
,2015-11-19 10:03:03.880 ThaliTest[749:783795] server session: connect
2015-11-19 10:03:03.880 ThaliTest[749:783795] server session: stateChange:0->1 Apple-Iphone6-1_PT5791
,2015-11-19 10:03:03.883 ThaliTest[749:783795] server: accepting invitation Apple-Iphone6-1_PT5791
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:03:04.610 ThaliTest[749:784002] jxcore: disconnect
,2015-11-19 10:03:04.610 ThaliTest[749:784002] jxcore: disconnect: fail
Connect (retry count 2) to peer Apple-Iphone6-1_PT5791.6xWUmg== with availability status: true
do connect now
2015-11-19 10:03:04.611 ThaliTest[749:784002] jxcore: connect Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:04.611 ThaliTest[749:784002] client session: connect
2015-11-19 10:03:04.611 ThaliTest[749:784002] client session: stateChange:0->1 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:06.481 ThaliTest[749:785797] server session: connected
2015-11-19 10:03:06.481 ThaliTest[749:785797] server session: stateChange:1->2 Apple-Iphone6-1_PT5791
,2015-11-19 10:03:06.484 ThaliTest[749:783795] server relay: connected (to port: 54898)
,TCP/IP server connected
,TCP/IP server has received 45990 bytes of data
,TCP/IP server has received 50370 bytes of data
,TCP/IP server has received 76650 bytes of data
,TCP/IP server has received 177390 bytes of data
,TCP/IP server has received 260610 bytes of data
,2015-11-19 10:03:07.339 ThaliTest[749:785860] client session: connected
2015-11-19 10:03:07.339 ThaliTest[749:785860] client session: stateChange:1->2 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:07.340 ThaliTest[749:785860] client session: fireConnectCallback: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:07.341 ThaliTest[749:785860] jxcore: connect: success
,CLIENT connected to 54913, error: null
,CLIENT starting client 
,2015-11-19 10:03:07.343 ThaliTest[749:783795] client: relay established
2015-11-19 10:03:07.343 ThaliTest[749:783795] client: new accepted socket: 0x1a96e650
,CLIENT now sending 950000 bytes of data
,TCP/IP server has received 391682 bytes of data
,TCP/IP server has received 522754 bytes of data
,TCP/IP server has received 653826 bytes of data
TCP/IP server has received 784898 bytes of data
,TCP/IP server has received 816870 bytes of data
,TCP/IP server has received 820966 bytes of data
,CLIENT is data received : 50000
,TCP/IP server has received 831206 bytes of data
,TCP/IP server has received 962278 bytes of data
,TCP/IP server has received 970002 bytes of data
CLIENT is data received : 50000
,CLIENT is data received : 50000
,CLIENT is data received : 50000
,CLIENT is data received : 50000
,CLIENT is data received : 60000
,CLIENT is data received : 60000
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:03:18.604 ThaliTest[749:783795] client: socket closed
----------------- closeClientSocket
2015-11-19 10:03:18.604 ThaliTest[749:783795] client relay: socket disconnected
2015-11-19 10:03:18.604 ThaliTest[749:783795,] client relay: 0x1a96e650 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
CLIENT is closed
2015-11-19 10:03:18.604 ThaliTest[749:783795] client session: socket closed: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:18.604 ThaliTest[749:783795] client session: onLinkFailure: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:18.605 ThaliTest[749:783795] client session: disconnect
2015-11-19 10:03:18.605 ThaliTest[749:783795] client session: stateChange:2->0 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:18.609 ThaliTest[749:783795] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:18.614 ThaliTest[749:785860] server session: not connected Apple-Iphone6-1_PT5791
,re-try now : Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:28.609 ThaliTest[749:784002] jxcore: disconnect
2015-11-19 10:03:28.610 ThaliTest[749:784002] jxcore: disconnect: fail
Connect (retry count 3) to peer Apple-Iphone6-1_PT5791.6xWUmg== with availability status: true
do connect now
2015-1,1-19 10:03:28.610 ThaliTest[749:784002] jxcore: connect Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:28.610 ThaliTest[749:784002] client session: connect
2015-11-19 10:03:28.610 ThaliTest[749:784002] client session: stateChange:0->1 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:29.494 ThaliTest[749:783795] multipeer session: reset timer
2015-11-19 10:03:29.494 ThaliTest[749:783795] multipeer session: stop timer
2015-11-19 10:03:29.494 ThaliTest[749:783795] multipeer session: start timer: 0x1940e970
2015-11-19 10:03:29.494 ThaliTest[749:783795] server: disconnecting to refresh session (Apple-Iphone6-1_PT5791)
2015-11-19 10:03:29.494 ThaliTest[749:783795] server session: disconnect
2015-11-19 10:03:29.494 ThaliTest[749:783795] server session: stateChange:2->0 A,pple-Iphone6-1_PT5791
,2015-11-19 10:03:29.495 ThaliTest[749:783795] server session: connect
2015-11-19 10:03:29.496 ThaliTest[749:783795] server session: stateChange:0->1 Apple-Iphone6-1_PT5791
,2015-11-19 10:03:29.498 ThaliTest[749:783795] server: accepting invitation Apple-Iphone6-1_PT5791
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:03:31.662 ThaliTest[749:785930] client session: connected
2015-11-19 10:03:31.662 ThaliTest[749:785930] client session: stateChange:1->2 Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:31.663 ThaliTest[749:785930] client session: fireConnectCallback: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:31.663 ThaliTest[749:785930] jxcore: connect: success
,CLIENT connected to 54917, error: null
CLIENT starting client 
,2015-11-19 10:03:31.665 ThaliTest[749:783795] client: relay established
2015-11-19 10:03:31.665 ThaliTest[749:783795] client: new accepted socket: 0x1a96e650
,CLIENT now sending 940000 bytes of data
,2015-11-19 10:03:32.208 ThaliTest[749:785936] server session: connected
2015-11-19 10:03:32.208 ThaliTest[749:785936] server session: stateChange:1->2 Apple-Iphone6-1_PT5791
,TCP/IP server connected
,2015-11-19 10:03:32.322 ThaliTest[749:783795] server relay: connected (to port: 54898)
,CLIENT is data received : 60000
,TCP/IP server has received 19710 bytes of data
,TCP/IP server has received 31998 bytes of data
,TCP/IP server has received 142350 bytes of data
,TCP/IP server has received 146730 bytes of data
,TCP/IP server has received 150826 bytes of data
,TCP/IP server has received 205860 bytes of data
,TCP/IP server has received 243090 bytes of data
,TCP/IP server has received 254040 bytes of data
,TCP/IP server has received 354780 bytes of data
,TCP/IP server has received 385440 bytes of data
,TCP/IP server has received 387630 bytes of data
,TCP/IP server has received 389820 bytes of data
,TCP/IP server has received 394200 bytes of data
,CLIENT is data received : 70000
,TCP/IP server has received 424860 bytes of data
,TCP/IP server has received 433620 bytes of data
,TCP/IP server has received 462090 bytes of data
,TCP/IP server has received 529980 bytes of data
,CLIENT is data received : 70000
,TCP/IP server has received 578160 bytes of data
,TCP/IP server has received 582540 bytes of data
,TCP/IP server has received 604440 bytes of data
,TCP/IP server has received 665760 bytes of data
,TCP/IP server has received 681090 bytes of data
,TCP/IP server has received 718320 bytes of data
,TCP/IP server has received 777450 bytes of data
,TCP/IP server has received 803730 bytes of data
,TCP/IP server has received 834390 bytes of data
,TCP/IP server has received 873810 bytes of data
,TCP/IP server has received 891330 bytes of data
,TCP/IP server has received 932940 bytes of data
,TCP/IP server has received 940002 bytes of data
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
----------------- closeClientSocket
2015-11-19 10:03:43.293 ThaliTest[749:783795] client: socket closed
2015-11-19 10:03:43.293 ThaliTest[749:783795] client relay: socket disconnected
CLIENT is closed
,2015-11-19 10:03:43.293 ThaliTest[749:783795] client relay: 0x1a96e650 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:03:43,.293 ThaliTest[749:783795] client session: socket closed: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:43.293 ThaliTest[749:783795] client session: onLinkFailure: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:43.293 ThaliTest[749:783795] client session: disconnect
2015-11-19 10:03:43.293 ThaliTest[749:783795] client session: stateChange:2->0 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:43.296 ThaliTest[749:783795] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:43.769 ThaliTest[749:785842] server session: not connected Apple-Iphone6-1_PT5791
,re-try now : Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:53.315 ThaliTest[749:784002] jxcore: disconnect
2015-11-19 10:03:53.315 ThaliTest[749:784002] jxcore: disconnect: fail
,Connect (retry count 4) to peer Apple-Iphone6-1_PT5791.6xWUmg== with availability status: true
do connect now
,2015-11-19 10:03:53.316 ThaliTest[749:784002] jxcore: connect Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:53.316 ThaliTest[749:784002] client session: connect
,2015-11-19 10:03:53.316 ThaliTest[749:784002] client session: stateChange:0->1 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:54.859 ThaliTest[749:783795] multipeer session: reset timer
2015-11-19 10:03:54.859 ThaliTest[749:783795] multipeer session: stop timer
,2015-11-19 10:03:54.859 ThaliTest[749:783795] multipeer session: start timer: 0x1940e970
2015-11-19 10:03:54.859 ThaliTest[749:783795] server: disconnecting to refresh session (Apple-Iphone6-1_PT5791)
2015-11-19 10:03:54.859 ThaliTest[749:783795] server session: disconnect
2015-11-19 10:03:54.859 ThaliTest[749:783795] server session: stateChange:2->0 Apple-Iphone6-1_PT5791
,TCP/IP server is ended
,TCP/IP server is close
,2015-11-19 10:03:54.912 ThaliTest[749:783795] server session: connect
2015-11-19 10:03:54.913 ThaliTest[749:783795] server session: stateChange:0->1 Apple-Iphone6-1_PT5791
,2015-11-19 10:03:54.915 ThaliTest[749:783795] server: accepting invitation Apple-Iphone6-1_PT5791
,2015-11-19 10:03:57.507 ThaliTest[749:785990] server session: connected
2015-11-19 10:03:57.507 ThaliTest[749:785990] server session: stateChange:1->2 Apple-Iphone6-1_PT5791
,2015-11-19 10:03:57.509 ThaliTest[749:783795] server relay: connected (to port: 54898)
,TCP/IP server connected
,2015-11-19 10:03:57.676 ThaliTest[749:785998] client session: connected
2015-11-19 10:03:57.676 ThaliTest[749:785998] client session: stateChange:1->2 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:57.678 ThaliTest[749:785998] client session: fireConnectCallback: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:57.678 ThaliTest[749:785998] jxcore: connect: success
,CLIENT connected to 54923, error: null
CLIENT starting client 
,2015-11-19 10:03:57.680 ThaliTest[749:783795] client: relay established
2015-11-19 10:03:57.680 ThaliTest[749:783795] client: new accepted socket: 0x1940cb60
,CLIENT now sending 930000 bytes of data
,TCP/IP server has received 131072 bytes of data
,TCP/IP server has received 262144 bytes of data
,TCP/IP server has received 393216 bytes of data
,TCP/IP server has received 524288 bytes of data
,TCP/IP server has received 655360 bytes of data
,TCP/IP server has received 786432 bytes of data
,TCP/IP server has received 910002 bytes of data
,CLIENT is data received : 80000
,CLIENT is data received : 80000
,CLIENT is data received : 80000
,CLIENT is data received : 90000
,CLIENT is data received : 100000
,CLIENT is data received : 110000
,Receiving data timeout now
CLIENT closeClientSocket
,2015-11-19 10:04:08.426 ThaliTest[749:783795] client: socket closed
2015-11-19 10:04:08.426 ThaliTest[749:783795] client relay: socket disconnected
2015-11-19 10:04:08.426 ThaliTest[749:783795] client relay: 0x1940cb60 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
CLIENT Stop now
2015-11-19 10:04:08.426 ThaliTest[749:783795] client session: socket closed: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:04:08.426 ThaliTest[749:783795] client session: onLinkFailure: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:04:08.426 ThaliTest[749:783795] client session: disconnect
2015-11-19 10:04:08.426 ThaliTest[749:783795] client session: stateCha,nge:2->0 Apple-Iphone6-1_PT5791.6xWUmg==
Stop data retrieving timer
CLIENT Stop now
---- round done--------
device[2]: Apple-Iphone5s-1_PT5906.NMJf0A==
----------------- closeClientSocket
CLIENT is closed
,2015-11-19 10:04:08.429 ThaliTest[749:783795] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:04:08.472 ThaliTest[749:785990] server session: not connected Apple-Iphone6-1_PT5791
,2015-11-19 10:04:13.437 ThaliTest[749:784002] jxcore: disconnect
,2015-11-19 10:04:13.438 ThaliTest[749:784002] jxcore: disconnect: fail
,Connect (retry count 0) to peer Apple-Iphone5s-1_PT5906.NMJf0A== with availability status: true
,do connect now
,2015-11-19 10:04:13.439 ThaliTest[749:784002] jxcore: connect Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:13.439 ThaliTest[749:784002] client session: connect
2015-11-19 10:04:13.439 ThaliTest[749:784002] client session: stateChange:0->1 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:04:14.782 ThaliTest[749:783795] multipeer session: reset timer
2015-11-19 10:04:14.782 ThaliTest[749:783795] multipeer session: stop timer
2015-11-19 10:04:14.782 ThaliTest[749:783795] multipeer session: start timer: 0x1940e970
2015-11-19 ,10:04:14.782 ThaliTest[749:783795] server session: connect
2015-11-19 10:04:14.782 ThaliTest[749:783795] server session: stateChange:0->1 Apple-Iphone5s-1_PT5906
,2015-11-19 10:04:14.784 ThaliTest[749:783795] server: accepting invitation Apple-Iphone5s-1_PT5906
,2015-11-19 10:04:16.835 ThaliTest[749:786029] client session: connected
2015-11-19 10:04:16.835 ThaliTest[749:786029] client session: stateChange:1->2 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:04:16.837 ThaliTest[749:785995] client session: fireConnectCallback: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:16.837 ThaliTest[749:785995] jxcore: connect: success
,CLIENT connected to 54929, error: null
CLIENT starting client 
2015-11-19 10:04:16.839 ThaliTest[749:783795] client: relay established
2015-11-19 10:04:16.839 ThaliTest[749:783795] client: new accepted socket: 0x1959ca50
,CLIENT now sending 1000000 bytes of data
,2015-11-19 10:04:17.378 ThaliTest[749:786029] server session: connected
2015-11-19 10:04:17.378 ThaliTest[749:786029] server session: stateChange:1->2 Apple-Iphone5s-1_PT5906
,TCP/IP server connected
,2015-11-19 10:04:17.603 ThaliTest[749:783795] server relay: connected (to port: 54898)
,CLIENT is data received : 0
,TCP/IP server has received 28470 bytes of data
,TCP/IP server has received 113880 bytes of data
,TCP/IP server has received 173010 bytes of data
,TCP/IP server has received 243090 bytes of data
,TCP/IP server has received 269370 bytes of data
,CLIENT is data received : 10000
,TCP/IP server has received 335070 bytes of data
,TCP/IP server has received 348210 bytes of data
,TCP/IP server has received 385440 bytes of data
,TCP/IP server has received 398580 bytes of data
,TCP/IP server has received 488370 bytes of data
,TCP/IP server has received 499178 bytes of data
,TCP/IP server has received 538740 bytes of data
,TCP/IP server has received 586920 bytes of data
,TCP/IP server has received 687660 bytes of data
,TCP/IP server has received 775260 bytes of data
,TCP/IP server has received 867240 bytes of data
,TCP/IP server has received 941416 bytes of data
,CLIENT is data received : 10000
,TCP/IP server has received 1000002 bytes of data
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
----------------- closeClientSocket
,2015-11-19 10:04:28.240 ThaliTest[749:783795] client: socket closed
2015-11-19 10:04:28.241 ThaliTest[749:783795] client relay: socket disconnected
2015-11-19 10:04:28.241 ThaliTest[749:783795] client relay: 0x1959ca50 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:04:28.241 ThaliTest[749:783795] client session: socket closed: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:,04:28.241 ThaliTest[749:783795] client session: onLinkFailure: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:28.241 ThaliTest[749:783795] client session: disconnect
2015-11-19 10:04:28.241 ThaliTest[749:783795] client session: stateChange:2->0 Apple-Iphone5s-1_PT5906.NMJf0A==
,CLIENT is closed
,2015-11-19 10:04:28.243 ThaliTest[749:783795] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:04:28.391 ThaliTest[749:785995] server session: not connected Apple-Iphone5s-1_PT5906
,re-try now : Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:04:38.246 ThaliTest[749:784002] jxcore: disconnect
2015-11-19 10:04:38.246 ThaliTest[749:784002] jxcore: disconnect: fail
,Connect (retry count 1) to peer Apple-Iphone5s-1_PT5906.NMJf0A== with availability status: true
do connect now
,2015-11-19 10:04:38.247 ThaliTest[749:784002] jxcore: connect Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:38.247 ThaliTest[749:784002] client session: connect
2015-11-19 10:04:38.248 ThaliTest[749:784002] client session: stateChange:0->1 Apple-Ipho,ne5s-1_PT5906.NMJf0A==
,2015-11-19 10:04:38.890 ThaliTest[749:783795] multipeer session: reset timer
2015-11-19 10:04:38.890 ThaliTest[749:783795] multipeer session: stop timer
2015-11-19 10:04:38.890 ThaliTest[749:783795] multipeer session: start timer: 0x1940e970
2015-11-19 ,10:04:38.890 ThaliTest[749:783795] server: disconnecting to refresh session (Apple-Iphone5s-1_PT5906)
2015-11-19 10:04:38.890 ThaliTest[749:783795] server session: disconnect
2015-11-19 10:04:38.890 ThaliTest[749:783795] server session: stateChange:2->0 Apple-Iphone5s-1_PT5906
,2015-11-19 10:04:38.892 ThaliTest[749:783795] server session: connect
2015-11-19 10:04:38.892 ThaliTest[749:783795] server session: stateChange:0->1 Apple-Iphone5s-1_PT5906
,2015-11-19 10:04:38.895 ThaliTest[749:783795] server: accepting invitation Apple-Iphone5s-1_PT5906
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:04:41.473 ThaliTest[749:786107] server session: connected
2015-11-19 10:04:41.474 ThaliTest[749:786107] server session: stateChange:1->2 Apple-Iphone5s-1_PT5906
,2015-11-19 10:04:41.476 ThaliTest[749:783795] server relay: connected (to port: 54898)
,TCP/IP server connected
,TCP/IP server has received 35040 bytes of data
,TCP/IP server has received 105120 bytes of data
,TCP/IP server has received 168630 bytes of data
,TCP/IP server has received 225570 bytes of data
,2015-11-19 10:04:42.058 ThaliTest[749:786106] client session: connected
2015-11-19 10:04:42.058 ThaliTest[749:786106] client session: stateChange:1->2 Apple-Iphone5s-1_PT5906.NMJf0A==
,TCP/IP server has received 286038 bytes of data
,2015-11-19 10:04:42.064 ThaliTest[749:786106] client session: fireConnectCallback: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:42.064 ThaliTest[749:786106] jxcore: connect: success
,TCP/IP server has received 297840 bytes of data
,CLIENT connected to 54935, error: null
CLIENT starting client 
,2015-11-19 10:04:42.067 ThaliTest[749:783795] client: relay established
2015-11-19 10:04:42.067 ThaliTest[749:783795] client: new accepted socket: 0x194ec490
,TCP/IP server has received 394200 bytes of data
,CLIENT now sending 990000 bytes of data
,TCP/IP server has received 525272 bytes of data
,TCP/IP server has received 656344 bytes of data
,TCP/IP server has received 787416 bytes of data
,TCP/IP server has received 918488 bytes of data
,TCP/IP server has received 1000002 bytes of data
,CLIENT is data received : 10000
,CLIENT is data received : 10000
,CLIENT is data received : 20000
,CLIENT is data received : 20000
,CLIENT is data received : 20000
,CLIENT is data received : 20000
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
----------------- closeClientSocket
,2015-11-19 10:04:52.866 ThaliTest[749:783795] client: socket closed
CLIENT is closed
2015-11-19 10:04:52.867 ThaliTest[749:783795] client relay: socket disconnected
2015-11-19 10:04:52.867 ThaliTest[749:783795] client relay: 0x194ec490 disconnected with, error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:04:52.867 ThaliTest[749:783795] client session: socket closed: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:52.867 ThaliTest[749:783795] client session: onLinkFailure: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:04:52.867 ThaliTest[749:783795] client session: disconnect
2015-11-19 10:04:52.867 ThaliTest[749:783795] client session: state,Change:2->0 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:04:52.869 ThaliTest[749:783795] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:04:53.027 ThaliTest[749:786106] server session: not connected Apple-Iphone5s-1_PT5906
,re-try now : Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:02.879 ThaliTest[749:784002] jxcore: disconnect
,2015-11-19 10:05:02.880 ThaliTest[749:784002] jxcore: disconnect: fail
Connect (retry count 2) to peer Apple-Iphone5s-1_PT5906.NMJf0A== with availability status: true
do connect now
2015-11-19 10:05:02.880 ThaliTest[749:784002] jxcore: connect Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:02.881 ThaliTest[749:784002] client session: connect
,2015-11-19 10:05:02.881 ThaliTest[749:784002] client session: stateChange:0->1 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:03.005 ThaliTest[749:783795] multipeer session: reset timer
2015-11-19 10:05:03.006 ThaliTest[749:783795] multipeer session: stop timer
2015-11-19 10:05:03.006 ThaliTest[749:783795] multipeer session: start timer: 0x1940e970
2015-11-19 ,10:05:03.006 ThaliTest[749:783795] server: disconnecting to refresh session (Apple-Iphone5s-1_PT5906)
2015-11-19 10:05:03.006 ThaliTest[749:783795] server session: disconnect
2015-11-19 10:05:03.006 ThaliTest[749:783795] server session: stateChange:2->0 Apple-Iphone5s-1_PT5906
,2015-11-19 10:05:03.008 ThaliTest[749:783795] server session: connect
2015-11-19 10:05:03.008 ThaliTest[749:783795] server session: stateChange:0->1 Apple-Iphone5s-1_PT5906
TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:05:03.011 ThaliTest[749:783795] server: accepting invitation Apple-Iphone5s-1_PT5906
,2015-11-19 10:05:05.555 ThaliTest[749:786153] server session: connected
2015-11-19 10:05:05.555 ThaliTest[749:786153] server session: stateChange:1->2 Apple-Iphone5s-1_PT5906
,2015-11-19 10:05:05.558 ThaliTest[749:783795] server relay: connected (to port: 54898)
,TCP/IP server connected
,TCP/IP server has received 17520 bytes of data
,TCP/IP server has received 107168 bytes of data
,TCP/IP server has received 183960 bytes of data
,TCP/IP server has received 249660 bytes of data
,TCP/IP server has received 317550 bytes of data
,TCP/IP server has received 372300 bytes of data
,TCP/IP server has received 457710 bytes of data
,2015-11-19 10:05:06.172 ThaliTest[749:786153] client session: connected
,2015-11-19 10:05:06.172 ThaliTest[749:786153] client session: stateChange:1->2 Apple-Iphone5s-1_PT5906.NMJf0A==
,TCP/IP server has received 536124 bytes of data
,2015-11-19 10:05:06.177 ThaliTest[749:786153] client session: fireConnectCallback: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:06.177 ThaliTest[749:786153] jxcore: connect: success
,TCP/IP server has received 547500 bytes of data
,CLIENT connected to 54940, error: null
CLIENT starting client 
,2015-11-19 10:05:06.182 ThaliTest[749:783795] client: relay established
2015-11-19 10:05:06.182 ThaliTest[749:783795] client: new accepted socket: 0x193a1e60
,TCP/IP server has received 634958 bytes of data
,CLIENT now sending 980000 bytes of data
,TCP/IP server has received 766030 bytes of data
,TCP/IP server has received 897102 bytes of data
,TCP/IP server has received 990002 bytes of data
,CLIENT is data received : 20000
,CLIENT is data received : 20000
,CLIENT is data received : 20000
,CLIENT is data received : 30000
,CLIENT is data received : 40000
,CLIENT is data received : 50000
,CLIENT is data received : 60000
,CLIENT is data received : 70000
,Receiving data timeout now
CLIENT closeClientSocket
tryAgain afer: 5000 ms.
,----------------- closeClientSocket
,CLIENT is closed
,2015-11-19 10:05:17.015 ThaliTest[749:783795] client: socket closed
,2015-11-19 10:05:17.016 ThaliTest[749:783795] client relay: socket disconnected
,2015-11-19 10:05:17.016 ThaliTest[749:783795] client relay: 0x193a1e60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:05:17.016 ThaliTest[749:783795] client session: socket closed: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:17.016 ThaliTest[749:783795] client session: onLinkFailure: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:17.017 ThaliTest[749:783795] client session: disconnect
,2015-11-19 10:05:17.017 ThaliTest[749:783795] client session: stateChange:2->0 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:17.020 ThaliTest[749:783795] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:17.139 ThaliTest[749:786225] server session: not connected Apple-Iphone5s-1_PT5906
,re-try now : Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:27.029 ThaliTest[749:784002] jxcore: disconnect
2015-11-19 10:05:27.030 ThaliTest[749:784002] jxcore: disconnect: fail
Connect (retry count 3) to peer Apple-Iphone5s-1_PT5906.NMJf0A== with availability status: true
do connect now
2015-,11-19 10:05:27.030 ThaliTest[749:784002] jxcore: connect Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:27.030 ThaliTest[749:784002] client session: connect
2015-11-19 10:05:27.030 ThaliTest[749:784002] client session: stateChange:0->1 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:27.113 ThaliTest[749:783795] multipeer session: reset timer
2015-11-19 10:05:27.113 ThaliTest[749:783795] multipeer session: stop timer
,2015-11-19 10:05:27.113 ThaliTest[749:783795] multipeer session: start timer: 0x1940e970
2015-11-19 10:05:27.113 ThaliTest[749:783795] server: disconnecting to refresh session (Apple-Iphone5s-1_PT5906)
2015-11-19 10:05:27.113 ThaliTest[749:783795] server session: disconnect
2015-11-19 10:05:27.113 ThaliTest[749:783795] server session: stateChange:2->0 Apple-Iphone5s-1_PT5906
,2015-11-19 10:05:27.115 ThaliTest[749:783795] server session: connect
2015-11-19 10:05:27.115 ThaliTest[749:783795] server session: stateChange:0->1 Apple-Iphone5s-1_PT5906
,2015-11-19 10:05:27.118 ThaliTest[749:783795] server: accepting invitation Apple-Iphone5s-1_PT5906
,TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:05:29.688 ThaliTest[749:786225] server session: connected
2015-11-19 10:05:29.689 ThaliTest[749:786225] server session: stateChange:1->2 Apple-Iphone5s-1_PT5906
,2015-11-19 10:05:29.692 ThaliTest[749:783795] server relay: connected (to port: 54898)
,TCP/IP server connected
,TCP/IP server has received 13140 bytes of data
,TCP/IP server has received 85410 bytes of data
,TCP/IP server has received 157680 bytes of data
,TCP/IP server has received 240900 bytes of data
,TCP/IP server has received 315360 bytes of data
,TCP/IP server has received 381060 bytes of data
,2015-11-19 10:05:30.284 ThaliTest[749:786254] client session: connected
2015-11-19 10:05:30.284 ThaliTest[749:786254] client session: stateChange:1->2 Apple-Iphone5s-1_PT5906.NMJf0A==
,TCP/IP server has received 466470 bytes of data
,2015-11-19 10:05:30.288 ThaliTest[749:786254] client session: fireConnectCallback: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:30.288 ThaliTest[749:786254] jxcore: connect: success
,TCP/IP server has received 468660 bytes of data
,CLIENT connected to 54945, error: null
CLIENT starting client 
,2015-11-19 10:05:30.291 ThaliTest[749:783795] client: relay established
2015-11-19 10:05:30.292 ThaliTest[749:783795] client: new accepted socket: 0x176514b0
,TCP/IP server has received 569400 bytes of data
,CLIENT now sending 930000 bytes of data
,TCP/IP server has received 700472 bytes of data
,TCP/IP server has received 831544 bytes of data
,TCP/IP server has received 960002 bytes of data
,CLIENT is data received : 70000
,CLIENT is data received : 80000
,CLIENT is data received : 80000
,CLIENT is data received : 90000
,CLIENT is data received : 100000
,CLIENT is data received : 110000
,CLIENT is data received : 120000
,CLIENT is data received : 130000
,2015-11-19 10:05:35.606 ThaliTest[749:783795] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:05:35.606 ThaliTest[749:783795] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:05:40.137 ThaliTest[749:783795] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,----------------- closeClientSocket
2015-11-19 10:05:41.022 ThaliTest[749:783795] client: socket closed
CLIENT is closed
,2015-11-19 10:05:41.022 ThaliTest[749:783795] client relay: socket disconnected
2015-11-19 10:05:41.022 ThaliTest[749:783795] client relay: 0x176514b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" Use,rInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:05:41.023 ThaliTest[749:783795] client session: socket closed: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:41.023 ThaliTest[749:783795] client session: onLinkFailure: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:41.023 ThaliTest[749:783795] client session: disconnect
2015-11-19 10:05:41.023 ThaliTest[749:783795] client session: stateChange:2->0 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:41.025 ThaliTest[749:783795] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:42.757 ThaliTest[749:786260] server session: not connected Apple-Iphone5s-1_PT5906
,re-try now : Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:51.028 ThaliTest[749:784002] jxcore: disconnect
2015-11-19 10:05:51.028 ThaliTest[749:784002] jxcore: disconnect: fail
Connect (retry count 4) to peer Apple-Iphone5s-1_PT5906.NMJf0A== with availability status: true
do connect now
2015-11-19 10:05:51.029 ThaliTest[749:784002] jxcore: connect Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:51.029 ThaliTest[749:784002] client session: connect
,2015-11-19 10:05:51.029 ThaliTest[749:784002] client session: stateChange:0->1 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:51.162 ThaliTest[749:783795] multipeer session: reset timer
2015-11-19 10:05:51.162 ThaliTest[749:783795] multipeer session: stop timer
2015-11-19 10:05:51.162 ThaliTest[749:783795] multipeer session: start timer: 0x1940e970
2015-11-19 10:05:51.162 ThaliTest[749:783795] server: disconnecting to refresh session (Apple-Iphone5s-1_PT5906)
2015-11-19 10:05:51.162 ThaliTest[749:783795] server session: disconnect
2015-11-19 10:05:51.162 ThaliTest[749:783795] server session: stateChange:2->0 Apple-Iphone5s-1_PT5906
,2015-11-19 10:05:51.164 ThaliTest[749:783795] server session: connect
2015-11-19 10:05:51.164 ThaliTest[749:783795] server session: stateChange:0->1 Apple-Iphone5s-1_PT5906
TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:05:51.168 ThaliTest[749:783795] server: accepting invitation Apple-Iphone5s-1_PT5906
,2015-11-19 10:05:53.777 ThaliTest[749:786260] server session: connected
2015-11-19 10:05:53.777 ThaliTest[749:786260] server session: stateChange:1->2 Apple-Iphone5s-1_PT5906
,2015-11-19 10:05:53.780 ThaliTest[749:783795] server relay: connected (to port: 54898)
,TCP/IP server connected
,TCP/IP server has received 19710 bytes of data
,TCP/IP server has received 96218 bytes of data
,TCP/IP server has received 168630 bytes of data
,TCP/IP server has received 251850 bytes of data
,2015-11-19 10:05:54.333 ThaliTest[749:786317] client session: connected
2015-11-19 10:05:54.333 ThaliTest[749:786317] client session: stateChange:1->2 Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:05:54.336 ThaliTest[749:786317] client session: fireConnectCallback: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:05:54.336 ThaliTest[749:786317] jxcore: connect: success
,TCP/IP server has received 262800 bytes of data
,CLIENT connected to 54950, error: null
CLIENT starting client 
,2015-11-19 10:05:54.342 ThaliTest[749:783795] client: relay established
2015-11-19 10:05:54.342 ThaliTest[749:783795] client: new accepted socket: 0x195eea10
,TCP/IP server has received 376680 bytes of data
,CLIENT now sending 870000 bytes of data
,TCP/IP server has received 507752 bytes of data
,TCP/IP server has received 638824 bytes of data
,TCP/IP server has received 769896 bytes of data
,TCP/IP server has received 900968 bytes of data
,TCP/IP server has received 930002 bytes of data
,CLIENT is data received : 130000
,CLIENT is data received : 130000
,CLIENT is data received : 140000
,CLIENT is data received : 150000
,CLIENT is data received : 160000
,CLIENT is data received : 160000
,CLIENT is data received : 170000
,CLIENT is data received : 180000
,CLIENT is data received : 190000
,CLIENT is data received : 200000
,CLIENT is data received : 210000
,Receiving data timeout now
CLIENT closeClientSocket
,CLIENT Stop now
,2015-11-19 10:06:05.478 ThaliTest[749:783795] client: socket closed
,Stop data retrieving timer
,2015-11-19 10:06:05.478 ThaliTest[749:783795] client relay: socket disconnected
2015-11-19 10:06:05.479 ThaliTest[749:783795] client relay: 0x195eea10 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" Use,rInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:06:05.479 ThaliTest[749:783795] client session: socket closed: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:06:05.479 ThaliTest[749:783795] client session: onLinkFailure: Apple-,Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:06:05.479 ThaliTest[749:783795] client session: disconnect
2015-11-19 10:06:05.479 ThaliTest[749:783795] client session: stateChange:2->0 Apple-Iphone5s-1_PT5906.NMJf0A==
,CLIENT Stop now
,---- round done--------
,weAreDoneNow , resultArray.length: 2
done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT4426","time":238144,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT5791.6xWUmg==","time":120441,"result":"DATA-TIMEOUT","connections":5},{"name":"Apple-Iphone5s-1_PT5906.NMJf0A==","time":117050,"result":"DATA-TIMEOUT","connections":5}]}
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does, not contain any items
sendList failed peers count : 2 [100 %]
- Peer ID : Apple-Iphone6-1_PT5791.6xWUmg==, Tried : 5
2015-11-19 10:06:05.482 ThaliTest[749:783795] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5906.NMJf0A==
- Peer ID : Apple-Iphone5s-1_PT5906.NMJf0A==, Tried : 5
,sendList never tried peers count : 0 [0 %]
CLIENT Stop now
----------------- closeClientSocket
,CLIENT is closed
,2015-11-19 10:06:05.490 ThaliTest[749:783795] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:06:05.491 ThaliTest[749:783795] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:06:09.097 ThaliTest[749:786317] server session: not connected Apple-Iphone5s-1_PT5906
,2015-11-19 10:06:11.585 ThaliTest[749:783795] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:06:21.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:06:21.173 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:06:21.173 ThaliTest[749:783795] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:06:35.755 ThaliTest[749:783795] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:06:35.755 ThaliTest[749:783795] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:06:51.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:06:51.172 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:06:52.160 ThaliTest[749:783795] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:07:21.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:07:21.173 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:07:21.380 ThaliTest[749:783795] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:07:51.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:07:51.171 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:07:51.172 ThaliTest[749:783795] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:08:21.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:08:21.200 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:08:21.203 ThaliTest[749:783795] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:08:29.615 ThaliTest[749:783795] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:08:29.616 ThaliTest[749:783795] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:08:35.898 ThaliTest[749:783795] client: lost peer: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:08:35.898 ThaliTest[749:783795] client session: onPeerLost: Apple-Iphone5s-1_PT5906.NMJf0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:08:36.947 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:08:51.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:08:51.172 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:09:11.618 ThaliTest[749:783795] client: lost peer: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:09:11.618 ThaliTest[749:783795] client session: onPeerLost: Apple-Iphone5s-1_PT5906.NMJf0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:09:16.748 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:09:21.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:09:21.171 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:09:41.965 ThaliTest[749:783795] client: lost peer: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:09:41.965 ThaliTest[749:783795] client session: onPeerLost: Apple-Iphone5s-1_PT5906.NMJf0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:09:51.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:09:51.406 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:10:08.170 ThaliTest[749:783795] client: lost peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:10:08.170 ThaliTest[749:783795] client session: onPeerLost: Apple-Iphone5s-1_PT5906.NMJf0A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:10:16.630 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:10:21.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:10:21.172 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:10:41.719 ThaliTest[749:783795] client: lost peer: Apple-Iphone5s-1_PT5906.NMJf0A==
2015-11-19 10:10:41.719 ThaliTest[749:783795] client session: onPeerLost: Apple-Iphone5s-1_PT5906.NMJf0A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:10:46.905 ThaliTest[749:783795] client: found peer: Apple-Iphone5s-1_PT5906.NMJf0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5906.NMJf0A==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:10:51.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:11:21.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:11:51.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:12:21.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:12:51.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:13:21.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:13:51.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:14:21.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:14:51.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:15:21.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:15:51.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:16:21.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:16:51.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:17:21.163 ThaliTest[749:783795] multipeer session: restart
,2015-11-19 10:17:51.163 ThaliTest[749:783795] multipeer session: restart

```
