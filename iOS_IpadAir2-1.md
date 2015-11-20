#### Test 513350289df1748_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350289df1748/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A251AC61-7C9A-4B61-8E99-61EFA6106573/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A251AC61-7C9A-4B61-8E99-61EFA6106573/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350289df1748/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350289df1748/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/17B3E116-7879-46A4-BD8D-BB0FBC8839FC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51297"
,(lldb)     command script import "/tmp/A251AC61-7C9A-4B61-8E99-61EFA6106573/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 13:36:33.218 ThaliTest[850:955517] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/20767CB6-1E87-4CFC-9986-60FA3DCDC81F/Library/Cookies/Cookies.binarycookies
,2015-11-20 13:36:33.505 ThaliTest[850:955517] Apache Cordova native platform version 3.9.2 is starting.
2015-11-20 13:36:33.506 ThaliTest[850:955517] Multi-tasking -> Device: YES, App: YES
,2015-11-20 13:36:33.512 ThaliTest[850:955517] Unlimited access to network resources
,2015-11-20 13:36:33.518 ThaliTest[850:955517] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 13:36:37.723 ThaliTest[850:955517] Resetting plugins due to page load.
,2015-11-20 13:36:39.165 ThaliTest[850:955517] Finished load of: file:///var/mobile/Containers/Bundle/Application/17B3E116-7879-46A4-BD8D-BB0FBC8839FC/ThaliTest.app/www/index.html
,2015-11-20 13:36:39.313 ThaliTest[850:955517] JXcore Cordova plugin initializing
,2015-11-20 13:36:39.314 ThaliTest[850:955695] JXcore instance initializing
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
,toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,my name is : Apple-IpadAir2-1_PT545
,attempting to connect to test coordinator
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found inter,faceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
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
-iface: IPv6 is internal :, false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
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
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
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
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
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
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
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
found interfaceName: en0
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
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
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,printNetworkInfo
ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
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
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
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
-iface: IPv6 is internal : true, has ip: ::1
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
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
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ,ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"10000000\",\"conReTryTimeout\":\"1000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 55724
,2015-11-20 13:46:16.891 ThaliTest[850:955695] jxcore: startBroadcasting
,2015-11-20 13:46:16.897 ThaliTest[850:955695] server: starting Apple-IpadAir2-1_PT545.qwwthQ==
,2015-11-20 13:46:16.898 ThaliTest[850:955695] multipeer session: start timer: 0x16b29630
2015-11-20 13:46:16.898 ThaliTest[850:955695] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT545
2015-11-20 13:46:16.898 ThaliTest[850:955695] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-20T12:46:16.899Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-20 13:46:17.634 ThaliTest[850:955517] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:17.637Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:17.637Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:46:17.638 ThaliTest[850:955517] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:46:18.076 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6611.klJDeA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 13:46:18.648 ThaliTest[850:955695] jxcore: disconnect
2015-11-20 13:46:18.648 ThaliTest[850:955695] jxcore: disconnect: fail
2015-11-20T12:46:18.648Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:46:18.648Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone6-1_PT8859.CKR/JA== with availability status: true
2015-11-20T12:46:18.649Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:18.649Z SendDataConnector.js: do connect now
,2015-11-20 13:46:18.649 ThaliTest[850:955695] jxcore: connect Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:46:18.650 ThaliTest[850:955695] client session: connect
2015-11-20 13:46:18.650 ThaliTest[850:955695] client session: stateChange:0->1 Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:46:23.418 ThaliTest[850:956804] client session: connected
2015-11-20 13:46:23.418 ThaliTest[850:956804] client session: stateChange:1->2 Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:46:23.420 ThaliTest[850:956804] client session: fireConnectCallback: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:46:23.420 ThaliTest[850:956804] jxcore: connect: success
,2015-11-20T12:46:23.421Z SendDataConnector.js: CLIENT connected to 55728, error: null
,2015-11-20T12:46:23.422Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:46:23.423 ThaliTest[850:955517] client: relay established
2015-11-20 13:46:23.423 ThaliTest[850:955517] client: new accepted socket: 0x18146f50
,2015-11-20T12:46:23.436Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:46:27.776Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:30.733Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:30.733Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-20T12:46:34.198Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:46:34.199Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-20T12:46:35.818Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:35.819Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-20T12:46:40.491Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:40.491Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-20T12:46:40.614Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:40.614Z SendDataConnector.js: CLIENT is data received : 740000
,2015-11-20T12:46:40.653Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:46:40.653Z SendDataConnector.js: CLIENT is data received : 1020000
,2015-11-20T12:46:40.764Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:46:40.765Z SendDataConnector.js: CLIENT is data received : 1030000
,2015-11-20T12:46:40.778Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:40.778Z SendDataConnector.js: CLIENT is data received : 1150000
,2015-11-20T12:46:40.789Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:40.790Z SendDataConnector.js: CLIENT is data received : 1530000
,2015-11-20T12:46:40.803Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:40.803Z SendDataConnector.js: CLIENT is data received : 1550000
,2015-11-20T12:46:40.814Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:40.815Z SendDataConnector.js: CLIENT is data received : 1560000
,2015-11-20T12:46:40.828Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:40.828Z SendDataConnector.js: CLIENT is data received : 2170000
,2015-11-20T12:46:40.841Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:46:40.841Z SendDataConnector.js: CLIENT is data received : 2600000
,2015-11-20T12:46:40.866Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:40.867Z SendDataConnector.js: CLIENT is data received : 2680000
,2015-11-20T12:46:40.892Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:40.892Z SendDataConnector.js: CLIENT is data received : 3250000
,2015-11-20T12:46:40.905Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:46:40.905Z SendDataConnector.js: CLIENT is data received : 4030000
,2015-11-20T12:46:40.930Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:40.931Z SendDataConnector.js: CLIENT is data received : 5210000
,2015-11-20T12:46:40.967Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:40.967Z SendDataConnector.js: CLIENT is data received : 5320000
,2015-11-20T12:46:40.980Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:40.981Z SendDataConnector.js: CLIENT is data received : 5750000
,2015-11-20T12:46:40.994Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:46:40.995Z SendDataConnector.js: CLIENT is data received : 6210000
,2015-11-20T12:46:41.008Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:41.009Z SendDataConnector.js: CLIENT is data received : 6810000
,2015-11-20T12:46:41.022Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:41.022Z SendDataConnector.js: CLIENT is data received : 6920000
,2015-11-20T12:46:41.045Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:41.046Z SendDataConnector.js: CLIENT is data received : 7310000
,2015-11-20T12:46:41.059Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:41.060Z SendDataConnector.js: CLIENT is data received : 8360000
,2015-11-20T12:46:41.070Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:46:41.071Z SendDataConnector.js: CLIENT is data received : 8470000
,2015-11-20T12:46:41.084Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:41.084Z SendDataConnector.js: CLIENT is data received : 8640000
,2015-11-20T12:46:41.102Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:41.103Z SendDataConnector.js: CLIENT is data received : 8690000
,2015-11-20T12:46:41.116Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:41.117Z SendDataConnector.js: CLIENT is data received : 9380000
,2015-11-20T12:46:41.130Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20T12:46:41.130Z SendDataConnector.js: CLIENT is data received : 9460000
,2015-11-20T12:46:41.144Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:41.144Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:46:41.145Z SendDataConnector.js: got all data for this round
,2015-11-20T12:46:41.146Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:46:41.146Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:46:41.146 ThaliTest[850:955695] jxcore: disconnect
2015-11-20 13:46:41.147 ThaliTest[850:955695] client session: disconnectFromPeer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:46:41.147 ThaliTest[850:955695] client session: disconnect
2015-11-20 13:46:41.147 ThaliTest[850:955695] client session: stateChange:2->0 Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20 13:46:41.149 ThaliTest[850:955695] jxcore: disconnect: success
2015-11-20T12:46:41.149Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8859.CKR/JA==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:41.151Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:41.151Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:42.156 ThaliTest[850:955695] jxcore: disconnect
2015-11-20 13:46:42.156 ThaliTest[850:955695] jxcore: disconnect: fail
,2015-11-20T12:46:42.157Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:42.157Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5s-1_PT7169./ZcTuw== with availability status: true
2015-11-20T12:46:42.157Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:42.157Z SendDataConnector.js: do connect now
,2015-11-20 13:46:42.157 ThaliTest[850:955695] jxcore: connect Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:42.158 ThaliTest[850:955695] client session: connect
2015-11-20 13:46:42.158 ThaliTest[850:955695] client session: stateChange:0->1 Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:46.689 ThaliTest[850:956804] client session: connected
2015-11-20 13:46:46.689 ThaliTest[850:956804] client session: stateChange:1->2 Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:46.691 ThaliTest[850:956792] client session: fireConnectCallback: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:46:46.692 ThaliTest[850:956792] jxcore: connect: success
2015-11-20T12:46:46.692Z SendDataConnector.js: CLIENT connected to 55732, error: null
2015-11-20T12:46:46.692Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:46:46.693 ThaliTest[850:955517] client: relay established
2015-11-20 13:46:46.693 ThaliTest[850:955517] client: new accepted socket: 0x16c9c1e0
,2015-11-20T12:46:46.706Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 13:46:46.899 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:46:46.914 ThaliTest[850:955517] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:46:46.915 ThaliTest[850:955517] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:46:46.917 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:46:51.039Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:53.470Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:53.471Z SendDataConnector.js: CLIENT is data received : 470000
,2015-11-20 13:46:53.527 ThaliTest[850:955517] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:53.535Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:53.535Z SendDataConnector.js: CLIENT is data received : 510000
,2015-11-20T12:46:54.968Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:54.968Z SendDataConnector.js: CLIENT is data received : 1540000
,2015-11-20T12:46:55.315Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:46:55.316Z SendDataConnector.js: CLIENT is data received : 2250000
,2015-11-20T12:46:58.426Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:58.426Z SendDataConnector.js: CLIENT is data received : 3410000
,2015-11-20 13:46:59.476 ThaliTest[850:955517] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:46:59.477 ThaliTest[850:955517] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:46:59.478Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:59.479Z SendDataConnector.js: CLIENT is data received : 3970000
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
,2015-11-20T12:46:59.768Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:46:59.769Z SendDataConnector.js: CLIENT is data received : 4680000
,2015-11-20T12:47:00.097Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:00.097Z SendDataConnector.js: CLIENT is data received : 5790000
,2015-11-20T12:47:00.159Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:47:00.160Z SendDataConnector.js: CLIENT is data received : 5960000
,2015-11-20T12:47:00.196Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:00.196Z SendDataConnector.js: CLIENT is data received : 6060000
,2015-11-20T12:47:00.277Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:47:00.277Z SendDataConnector.js: CLIENT is data received : 6370000
,2015-11-20T12:47:02.371Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:02.372Z SendDataConnector.js: CLIENT is data received : 7350000
,2015-11-20T12:47:04.229Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:04.229Z SendDataConnector.js: CLIENT is data received : 8600000
,2015-11-20T12:47:04.326Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:04.326Z SendDataConnector.js: CLIENT is data received : 8840000
,2015-11-20T12:47:04.577Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:04.577Z SendDataConnector.js: CLIENT is data received : 9690000
,2015-11-20T12:47:04.591Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:04.591Z SendDataConnector.js: CLIENT is data received : 9780000
,2015-11-20T12:47:04.604Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:04.605Z SendDataConnector.js: CLIENT is data received : 9870000
,2015-11-20T12:47:04.618Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20T12:47:04.618Z SendDataConnector.js: CLIENT is data received : 9920000
,2015-11-20T12:47:04.632Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:47:04.632Z SendDataConnector.js: CLIENT is data received : 9980000
,2015-11-20T12:47:04.645Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20T12:47:04.645Z SendDataConnector.js: CLIENT is data received : 10000000
2015-11-20T12:47:04.646Z SendDataConnector.js: got all data for this round
,2015-11-20T12:47:04.646Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:47:04.646Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:47:04.647 ThaliTest[850:955695] jxcore: disconnect
2015-11-20 13:47:04.647 ThaliTest[850:955695] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:47:04.647 ThaliTest[850:955695] client session: disconnect
2015-11-20 13:47:04.647 ThaliTest[850:955695] client session: stateChange:2->0 Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:47:04.649 ThaliTest[850:955695] jxcore: disconnect: success
2015-11-20T12:47:04.649Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7169./ZcTuw==
---- round done--------
device[3]: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:04.650Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:04.650Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:05.142 ThaliTest[850:955517] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:47:05.662 ThaliTest[850:955695] jxcore: disconnect
2015-11-20 13:47:05.663 ThaliTest[850:955695] jxcore: disconnect: fail
2015-11-20T12:47:05.663Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6611.klJDeA==11-20T12:47:05.663Z SendDataConnector.js: do connect now

2015-11-20T12:47:05.663Z SendDataConnector.js: Connect (retry count 0) to peer Apple-Iphone5-1_PT6611.klJDeA== with availability status: true
2015-11-20T12:47:05.663Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-,2015-11-20 13:47:05.663 ThaliTest[850:955695] jxcore: connect Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:05.664 ThaliTest[850:955695] client session: connect
2015-11-20 13:47:05.664 ThaliTest[850:955695] client session: stateChange:0->1 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:09.883 ThaliTest[850:956928] client session: connected
2015-11-20 13:47:09.883 ThaliTest[850:956928] client session: stateChange:1->2 Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:09.884 ThaliTest[850:956928] client session: fireConnectCallback: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:09.884 ThaliTest[850:956928] jxcore: connect: success
,2015-11-20T12:47:09.885Z SendDataConnector.js: CLIENT connected to 55736, error: null
2015-11-20T12:47:09.885Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:47:09.886 ThaliTest[850:955517] client: relay established
2015-11-20 13:47:09.886 ThaliTest[850:955517] client: new accepted socket: 0x1813b920
,2015-11-20T12:47:09.899Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T12:47:14.151Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:16.977 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:47:18.931 ThaliTest[850:955517] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:47:18.931 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:18.931 ThaliTest[850:955517] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,2015-11-20T12:47:23.545Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:23.546Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-20T12:47:24.125Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:24.125Z SendDataConnector.js: CLIENT is data received : 3420000
,2015-11-20T12:47:24.199Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:24.199Z SendDataConnector.js: CLIENT is data received : 6680000
,2015-11-20T12:47:25.683Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:25.683Z SendDataConnector.js: CLIENT is data received : 6690000
,2015-11-20T12:47:27.120Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:27.120Z SendDataConnector.js: CLIENT is data received : 6720000
,2015-11-20T12:47:28.531Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:28.532Z SendDataConnector.js: CLIENT is data received : 6730000
,2015-11-20T12:47:29.084Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:29.085Z SendDataConnector.js: CLIENT is data received : 6740000
,2015-11-20T12:47:31.867Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:31.867Z SendDataConnector.js: CLIENT is data received : 8310000
,2015-11-20T12:47:33.670Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:33.670Z SendDataConnector.js: CLIENT is data received : 8320000
,2015-11-20T12:47:34.629Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:34.629Z SendDataConnector.js: CLIENT is data received : 8330000
,2015-11-20T12:47:38.290Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:38.290Z SendDataConnector.js: CLIENT is data received : 8350000
,2015-11-20T12:47:38.640Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:38.641Z SendDataConnector.js: CLIENT is data received : 8360000
,2015-11-20T12:47:38.786Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:38.787Z SendDataConnector.js: CLIENT is data received : 9520000
,2015-11-20T12:47:39.187Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:39.188Z SendDataConnector.js: CLIENT is data received : 9990000
,2015-11-20 13:47:40.409 ThaliTest[850:955517] multipeer session: reset timer
,2015-11-20 13:47:40.409 ThaliTest[850:955517] multipeer session: stop timer
2015-11-20 13:47:40.409 ThaliTest[850:955517] multipeer session: start timer: 0x16b29630
,2015-11-20 13:47:40.410 ThaliTest[850:955517] server session: connect
2015-11-20 13:47:40.410 ThaliTest[850:955517] server session: stateChange:0->1 Apple-Iphone5-1_PT6611
,2015-11-20 13:47:40.412 ThaliTest[850:955517] server: accepting invitation Apple-Iphone5-1_PT6611
,2015-11-20 13:47:43.033 ThaliTest[850:956928] server session: connected
2015-11-20 13:47:43.033 ThaliTest[850:956928] server session: stateChange:1->2 Apple-Iphone5-1_PT6611
,2015-11-20 13:47:43.036 ThaliTest[850:955517] server relay: connected (to port: 55724)
,2015-11-20T12:47:43.053Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T12:47:49.200Z SendDataConnector.js: Receiving data timeout now
2015-11-20T12:47:49.200Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T12:47:49.201Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20 13:47:49.201 ThaliTest[850:955517] client: socket closed
2015-11-20 13:47:49.201 ThaliTest[850:955517] client relay: socket disconnected
,2015-11-20T12:47:49.201Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 13:47:49.201 ThaliTest[850:955517] client relay: 0x1813b920 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" ,UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 13:47:49.202 ThaliTest[850:955517] client session: socket closed: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:49.202 ThaliTest[850:955517] client session: onLinkFailure: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:49.202 ThaliTest[850:955517] client session: disconnect
2015-11-20 13:47:49.202 ThaliTest[850:955517] client session: stateChange:2->0 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:49.204 ThaliTest[850:955517] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:50.204Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:50.205Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:51.217 ThaliTest[850:955695] jxcore: disconnect
2015-11-20 13:47:51.217 ThaliTest[850:955695] jxcore: disconnect: fail
2015-11-20T12:47:51.217Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6611.klJDeA==,
2015-11-20T12:47:51.217Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT6611.klJDeA== with availability status: true
2015-11-20T12:47:51.217Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:51.217Z SendDataConnector.js: do connect now
2015-11-20 13:47:51.217 ThaliTest[850:955695] jxcore: connect Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:51.218 ThaliTest[850:955695] client session: connect
,2015-11-20 13:47:51.218 ThaliTest[850:955695] client session: stateChange:0->1 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:53.775Z SendDataTCPServer.js: TCP/IP server has received 7936 bytes of data
,2015-11-20T12:47:53.788Z SendDataTCPServer.js: TCP/IP server has received 27776 bytes of data
,2015-11-20T12:47:53.894Z SendDataTCPServer.js: TCP/IP server has received 34720 bytes of data
,2015-11-20T12:47:53.908Z SendDataTCPServer.js: TCP/IP server has received 41664 bytes of data
,2015-11-20T12:47:53.921Z SendDataTCPServer.js: TCP/IP server has received 90272 bytes of data
,2015-11-20T12:47:53.971Z SendDataTCPServer.js: TCP/IP server has received 94240 bytes of data
,2015-11-20T12:47:53.984Z SendDataTCPServer.js: TCP/IP server has received 130944 bytes of data
,2015-11-20T12:47:54.045Z SendDataTCPServer.js: TCP/IP server has received 166656 bytes of data
,2015-11-20T12:47:54.059Z SendDataTCPServer.js: TCP/IP server has received 193440 bytes of data
,2015-11-20T12:47:54.083Z SendDataTCPServer.js: TCP/IP server has received 194432 bytes of data
,2015-11-20T12:47:54.109Z SendDataTCPServer.js: TCP/IP server has received 216256 bytes of data
,2015-11-20T12:47:54.122Z SendDataTCPServer.js: TCP/IP server has received 237088 bytes of data
,2015-11-20T12:47:54.172Z SendDataTCPServer.js: TCP/IP server has received 252960 bytes of data
,2015-11-20T12:47:54.185Z SendDataTCPServer.js: TCP/IP server has received 287680 bytes of data
,2015-11-20T12:47:54.199Z SendDataTCPServer.js: TCP/IP server has received 294624 bytes of data
,2015-11-20T12:47:54.235Z SendDataTCPServer.js: TCP/IP server has received 297600 bytes of data
,2015-11-20T12:47:54.248Z SendDataTCPServer.js: TCP/IP server has received 311488 bytes of data
,2015-11-20T12:47:54.310Z SendDataTCPServer.js: TCP/IP server has received 355136 bytes of data
,2015-11-20 13:47:54.313 ThaliTest[850:957040] client session: connected
2015-11-20 13:47:54.313 ThaliTest[850:957040] client session: stateChange:1->2 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:54.323Z SendDataTCPServer.js: TCP/IP server has received 373984 bytes of data
,2015-11-20 13:47:54.325 ThaliTest[850:957038] client session: fireConnectCallback: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:54.325 ThaliTest[850:957038] jxcore: connect: success
2015-11-20T12:47:54.326Z SendDataConnector.js: CLIENT connected to 55741, error: null
2015-11-20T12:47:54.326Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 13:47:54.327 ThaliTest[850:955517] client: relay established
2015-11-20 13:47:54.327 ThaliTest[850:955517] client: new accepted socket: 0x14ea9f00
,2015-11-20T12:47:54.340Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-20T12:47:54.344Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20T12:47:54.369Z SendDataTCPServer.js: TCP/IP server has received 380928 bytes of data
,2015-11-20T12:47:54.382Z SendDataTCPServer.js: TCP/IP server has received 410688 bytes of data
,2015-11-20T12:47:54.432Z SendDataTCPServer.js: TCP/IP server has received 418624 bytes of data
,2015-11-20T12:47:54.445Z SendDataTCPServer.js: TCP/IP server has received 459296 bytes of data
,2015-11-20T12:47:54.493Z SendDataTCPServer.js: TCP/IP server has received 465248 bytes of data
,2015-11-20T12:47:54.506Z SendDataTCPServer.js: TCP/IP server has received 505920 bytes of data
,2015-11-20T12:47:54.521Z SendDataTCPServer.js: TCP/IP server has received 506912 bytes of data
,2015-11-20T12:47:54.546Z SendDataTCPServer.js: TCP/IP server has received 512864 bytes of data
,2015-11-20T12:47:54.559Z SendDataTCPServer.js: TCP/IP server has received 513856 bytes of data
,2015-11-20T12:47:54.573Z SendDataTCPServer.js: TCP/IP server has received 567424 bytes of data
,2015-11-20T12:47:54.611Z SendDataTCPServer.js: TCP/IP server has received 580320 bytes of data
,2015-11-20T12:47:54.625Z SendDataTCPServer.js: TCP/IP server has received 599168 bytes of data
,2015-11-20T12:47:54.636Z SendDataTCPServer.js: TCP/IP server has received 613056 bytes of data
,2015-11-20T12:47:54.650Z SendDataTCPServer.js: TCP/IP server has received 614048 bytes of data
,2015-11-20T12:47:54.675Z SendDataTCPServer.js: TCP/IP server has received 617024 bytes of data
,2015-11-20T12:47:54.688Z SendDataTCPServer.js: TCP/IP server has received 619008 bytes of data
,2015-11-20T12:47:54.699Z SendDataTCPServer.js: TCP/IP server has received 656704 bytes of data
,2015-11-20T12:47:54.713Z SendDataTCPServer.js: TCP/IP server has received 676544 bytes of data
,2015-11-20T12:47:54.727Z SendDataTCPServer.js: TCP/IP server has received 681504 bytes of data
,2015-11-20T12:47:54.765Z SendDataTCPServer.js: TCP/IP server has received 685472 bytes of data
,2015-11-20T12:47:54.778Z SendDataTCPServer.js: TCP/IP server has received 726144 bytes of data
,2015-11-20T12:47:54.791Z SendDataTCPServer.js: TCP/IP server has received 730112 bytes of data
,2015-11-20T12:47:54.828Z SendDataTCPServer.js: TCP/IP server has received 745984 bytes of data
,2015-11-20T12:47:54.840Z SendDataTCPServer.js: TCP/IP server has received 770784 bytes of data
,2015-11-20T12:47:54.925Z SendDataTCPServer.js: TCP/IP server has received 820384 bytes of data
,2015-11-20T12:47:54.939Z SendDataTCPServer.js: TCP/IP server has received 833280 bytes of data
,2015-11-20T12:47:54.974Z SendDataTCPServer.js: TCP/IP server has received 836256 bytes of data
,2015-11-20T12:47:55.012Z SendDataTCPServer.js: TCP/IP server has received 847168 bytes of data
,2015-11-20T12:47:55.025Z SendDataTCPServer.js: TCP/IP server has received 884864 bytes of data
,2015-11-20T12:47:55.039Z SendDataTCPServer.js: TCP/IP server has received 898752 bytes of data
,2015-11-20T12:47:55.098Z SendDataTCPServer.js: TCP/IP server has received 929504 bytes of data
,2015-11-20T12:47:55.111Z SendDataTCPServer.js: TCP/IP server has received 930496 bytes of data
,2015-11-20T12:47:55.124Z SendDataTCPServer.js: TCP/IP server has received 931488 bytes of data
,2015-11-20T12:47:55.163Z SendDataTCPServer.js: TCP/IP server has received 964224 bytes of data
,2015-11-20T12:47:55.176Z SendDataTCPServer.js: TCP/IP server has received 981088 bytes of data
,2015-11-20T12:47:55.295Z SendDataTCPServer.js: TCP/IP server has received 1008864 bytes of data
,2015-11-20T12:47:55.307Z SendDataTCPServer.js: TCP/IP server has received 1022752 bytes of data
,2015-11-20T12:47:55.331Z SendDataTCPServer.js: TCP/IP server has received 1027712 bytes of data
,2015-11-20T12:47:55.355Z SendDataTCPServer.js: TCP/IP server has received 1043584 bytes of data
,2015-11-20T12:47:55.369Z SendDataTCPServer.js: TCP/IP server has received 1077312 bytes of data
,2015-11-20T12:47:55.418Z SendDataTCPServer.js: TCP/IP server has received 1101120 bytes of data
,2015-11-20T12:47:55.431Z SendDataTCPServer.js: TCP/IP server has received 1139808 bytes of data
,2015-11-20T12:47:55.445Z SendDataTCPServer.js: TCP/IP server has received 1149728 bytes of data
,2015-11-20T12:47:55.471Z SendDataTCPServer.js: TCP/IP server has received 1150720 bytes of data
,2015-11-20T12:47:55.484Z SendDataTCPServer.js: TCP/IP server has received 1179488 bytes of data
,2015-11-20T12:47:55.498Z SendDataTCPServer.js: TCP/IP server has received 1185440 bytes of data
,2015-11-20T12:47:55.547Z SendDataTCPServer.js: TCP/IP server has received 1198336 bytes of data
,2015-11-20T12:47:55.559Z SendDataTCPServer.js: TCP/IP server has received 1245952 bytes of data
,2015-11-20T12:47:55.573Z SendDataTCPServer.js: TCP/IP server has received 1247936 bytes of data
,2015-11-20T12:47:55.598Z SendDataTCPServer.js: TCP/IP server has received 1250912 bytes of data
,2015-11-20T12:47:55.653Z SendDataTCPServer.js: TCP/IP server has received 1252896 bytes of data
,2015-11-20T12:47:55.679Z SendDataTCPServer.js: TCP/IP server has received 1261824 bytes of data
,2015-11-20T12:47:55.694Z SendDataTCPServer.js: TCP/IP server has received 1295552 bytes of data
,2015-11-20T12:47:55.733Z SendDataTCPServer.js: TCP/IP server has received 1299520 bytes of data
,2015-11-20T12:47:55.745Z SendDataTCPServer.js: TCP/IP server has received 1329280 bytes of data
,2015-11-20T12:47:55.759Z SendDataTCPServer.js: TCP/IP server has received 1337216 bytes of data
,2015-11-20T12:47:55.797Z SendDataTCPServer.js: TCP/IP server has received 1344160 bytes of data
,2015-11-20T12:47:55.920Z SendDataTCPServer.js: TCP/IP server has received 1356064 bytes of data
,2015-11-20T12:47:55.944Z SendDataTCPServer.js: TCP/IP server has received 1363008 bytes of data
,2015-11-20T12:47:55.954Z SendDataTCPServer.js: TCP/IP server has received 1388800 bytes of data
,2015-11-20T12:47:56.067Z SendDataTCPServer.js: TCP/IP server has received 1393760 bytes of data
,2015-11-20T12:47:56.081Z SendDataTCPServer.js: TCP/IP server has received 1440384 bytes of data
,2015-11-20T12:47:56.133Z SendDataTCPServer.js: TCP/IP server has received 1445344 bytes of data
,2015-11-20T12:47:56.146Z SendDataTCPServer.js: TCP/IP server has received 1473120 bytes of data
,2015-11-20T12:47:56.160Z SendDataTCPServer.js: TCP/IP server has received 1475104 bytes of data
,2015-11-20T12:47:56.184Z SendDataTCPServer.js: TCP/IP server has received 1480064 bytes of data
,2015-11-20T12:47:56.209Z SendDataTCPServer.js: TCP/IP server has received 1508832 bytes of data
,2015-11-20T12:47:56.223Z SendDataTCPServer.js: TCP/IP server has received 1519744 bytes of data
,2015-11-20T12:47:56.235Z SendDataTCPServer.js: TCP/IP server has received 1521728 bytes of data
,2015-11-20T12:47:56.246Z SendDataTCPServer.js: TCP/IP server has received 1522720 bytes of data
,2015-11-20T12:47:56.259Z SendDataTCPServer.js: TCP/IP server has received 1526688 bytes of data
,2015-11-20T12:47:56.270Z SendDataTCPServer.js: TCP/IP server has received 1562400 bytes of data
,2015-11-20T12:47:56.284Z SendDataTCPServer.js: TCP/IP server has received 1588192 bytes of data
,2015-11-20T12:47:56.334Z SendDataTCPServer.js: TCP/IP server has received 1609024 bytes of data
,2015-11-20T12:47:56.348Z SendDataTCPServer.js: TCP/IP server has received 1650688 bytes of data
,2015-11-20T12:47:56.424Z SendDataTCPServer.js: TCP/IP server has received 1680448 bytes of data
,2015-11-20T12:47:56.437Z SendDataTCPServer.js: TCP/IP server has received 1713184 bytes of data
,2015-11-20T12:47:56.463Z SendDataTCPServer.js: TCP/IP server has received 1717152 bytes of data
,2015-11-20T12:47:56.476Z SendDataTCPServer.js: TCP/IP server has received 1729056 bytes of data
,2015-11-20T12:47:56.515Z SendDataTCPServer.js: TCP/IP server has received 1740960 bytes of data
,2015-11-20T12:47:56.528Z SendDataTCPServer.js: TCP/IP server has received 1741952 bytes of data
,2015-11-20T12:47:56.540Z SendDataTCPServer.js: TCP/IP server has received 1778656 bytes of data
,2015-11-20T12:47:56.567Z SendDataTCPServer.js: TCP/IP server has received 1784608 bytes of data
,2015-11-20T12:47:56.589Z SendDataTCPServer.js: TCP/IP server has received 1786592 bytes of data
,2015-11-20T12:47:56.602Z SendDataTCPServer.js: TCP/IP server has received 1824288 bytes of data
,2015-11-20T12:47:56.757Z SendDataTCPServer.js: TCP/IP server has received 1886784 bytes of data
,2015-11-20T12:47:56.796Z SendDataTCPServer.js: TCP/IP server has received 1902656 bytes of data
,2015-11-20T12:47:56.810Z SendDataTCPServer.js: TCP/IP server has received 1943328 bytes of data
,2015-11-20T12:47:56.847Z SendDataTCPServer.js: TCP/IP server has received 1961184 bytes of data
,2015-11-20T12:47:56.860Z SendDataTCPServer.js: TCP/IP server has received 1970112 bytes of data
,2015-11-20T12:47:56.959Z SendDataTCPServer.js: TCP/IP server has received 1974080 bytes of data
,2015-11-20T12:47:57.020Z SendDataTCPServer.js: TCP/IP server has received 1998880 bytes of data
,2015-11-20T12:47:57.022Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20T12:47:57.022Z SendDataConnector.js: CLIENT is data received : 10000000
,2015-11-20T12:47:57.022Z SendDataConnector.js: got all data for this round
2015-11-20T12:47:57.022Z SendDataConnector.js: CLIENT Stop now
2015-11-20T12:47:57.022Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20 13:47:57.023 ThaliTest[850:955695] jxcore: disconnect
2015-11-20 13:47:57.024 ThaliTest[850:955695] client session: disconnectFromPeer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:47:57.024 ThaliTest[850:955695] client session: disconnect
2015-11-20 13:47:57.024 ThaliTest[850:955695] client session: stateChange:2->0 Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:47:57.031 ThaliTest[850:955695] jxcore: disconnect: success
2015-11-20T12:47:57.031Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6611.klJDeA==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT545","time":100150,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT8859.CKR/JA==","time":23512,"result":"OK","connections":1},{"name":"Apple-Iphone5s-1_PT7169./ZcTuw==","time":23498,"result":"OK","connections":1},{"name":"Apple-Iphone5-1_PT6611.klJDeA==","time":52381,"result":"OK","connections":2}]}
,sendList : 100% : 52381 ms, 99% : 52381 ms, 95 : 52381 ms, 90% : 52381 ms.
Result count 3, range 23498 ms to  52381 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-20T12:47:57.039Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T12:47:57.053Z SendDataTCPServer.js: TCP/IP server has received 2027648 bytes of data
,2015-11-20T12:47:57.065Z SendDataTCPServer.js: TCP/IP server has received 2045504 bytes of data
,2015-11-20T12:47:57.127Z SendDataTCPServer.js: TCP/IP server has received 2061376 bytes of data
,2015-11-20T12:47:57.141Z SendDataTCPServer.js: TCP/IP server has received 2071296 bytes of data
,2015-11-20T12:47:57.202Z SendDataTCPServer.js: TCP/IP server has received 2084192 bytes of data
,2015-11-20T12:47:57.216Z SendDataTCPServer.js: TCP/IP server has received 2097088 bytes of data
,2015-11-20T12:47:57.230Z SendDataTCPServer.js: TCP/IP server has received 2107008 bytes of data
,2015-11-20T12:47:57.244Z SendDataTCPServer.js: TCP/IP server has received 2115936 bytes of data
,2015-11-20T12:47:57.255Z SendDataTCPServer.js: TCP/IP server has received 2133792 bytes of data
,2015-11-20T12:47:57.269Z SendDataTCPServer.js: TCP/IP server has received 2135776 bytes of data
,2015-11-20T12:47:57.319Z SendDataTCPServer.js: TCP/IP server has received 2153632 bytes of data
,2015-11-20T12:47:57.333Z SendDataTCPServer.js: TCP/IP server has received 2189344 bytes of data
,2015-11-20T12:47:57.371Z SendDataTCPServer.js: TCP/IP server has received 2194304 bytes of data
,2015-11-20T12:47:57.384Z SendDataTCPServer.js: TCP/IP server has received 2204224 bytes of data
,2015-11-20T12:47:57.397Z SendDataTCPServer.js: TCP/IP server has received 2210176 bytes of data
,2015-11-20T12:47:57.410Z SendDataTCPServer.js: TCP/IP server has received 2211168 bytes of data
,2015-11-20T12:47:57.448Z SendDataTCPServer.js: TCP/IP server has received 2227040 bytes of data
,2015-11-20T12:47:57.462Z SendDataTCPServer.js: TCP/IP server has received 2273664 bytes of data
,2015-11-20T12:47:57.587Z SendDataTCPServer.js: TCP/IP server has received 2309376 bytes of data
,2015-11-20T12:47:57.600Z SendDataTCPServer.js: TCP/IP server has received 2342112 bytes of data
,2015-11-20T12:47:57.613Z SendDataTCPServer.js: TCP/IP server has received 2357984 bytes of data
,2015-11-20T12:47:57.626Z SendDataTCPServer.js: TCP/IP server has received 2373856 bytes of data
,2015-11-20T12:47:57.639Z SendDataTCPServer.js: TCP/IP server has received 2392704 bytes of data
,2015-11-20T12:47:57.653Z SendDataTCPServer.js: TCP/IP server has received 2406592 bytes of data
,2015-11-20T12:47:57.664Z SendDataTCPServer.js: TCP/IP server has received 2423456 bytes of data
,2015-11-20T12:47:57.677Z SendDataTCPServer.js: TCP/IP server has received 2442304 bytes of data
,2015-11-20T12:47:57.691Z SendDataTCPServer.js: TCP/IP server has received 2457184 bytes of data
,2015-11-20T12:47:57.704Z SendDataTCPServer.js: TCP/IP server has received 2478016 bytes of data
,2015-11-20T12:47:57.718Z SendDataTCPServer.js: TCP/IP server has received 2497856 bytes of data
,2015-11-20T12:47:57.731Z SendDataTCPServer.js: TCP/IP server has received 2517696 bytes of data
,2015-11-20T12:47:57.744Z SendDataTCPServer.js: TCP/IP server has received 2530592 bytes of data
,2015-11-20T12:47:57.757Z SendDataTCPServer.js: TCP/IP server has received 2558368 bytes of data
,2015-11-20T12:47:57.771Z SendDataTCPServer.js: TCP/IP server has received 2580192 bytes of data
,2015-11-20T12:47:57.784Z SendDataTCPServer.js: TCP/IP server has received 2582176 bytes of data
,2015-11-20T12:47:57.849Z SendDataTCPServer.js: TCP/IP server has received 2612928 bytes of data
,2015-11-20T12:47:57.864Z SendDataTCPServer.js: TCP/IP server has received 2623840 bytes of data
,2015-11-20T12:47:57.913Z SendDataTCPServer.js: TCP/IP server has received 2632768 bytes of data
,2015-11-20T12:47:57.925Z SendDataTCPServer.js: TCP/IP server has received 2647648 bytes of data
,2015-11-20T12:47:57.939Z SendDataTCPServer.js: TCP/IP server has received 2661536 bytes of data
,2015-11-20T12:47:57.952Z SendDataTCPServer.js: TCP/IP server has received 2678400 bytes of data
,2015-11-20T12:47:57.966Z SendDataTCPServer.js: TCP/IP server has received 2694272 bytes of data
,2015-11-20T12:47:57.978Z SendDataTCPServer.js: TCP/IP server has received 2710144 bytes of data
,2015-11-20T12:47:57.991Z SendDataTCPServer.js: TCP/IP server has received 2728000 bytes of data
,2015-11-20T12:47:58.005Z SendDataTCPServer.js: TCP/IP server has received 2741888 bytes of data
,2015-11-20T12:47:58.016Z SendDataTCPServer.js: TCP/IP server has received 2756768 bytes of data
,2015-11-20T12:47:58.030Z SendDataTCPServer.js: TCP/IP server has received 2766688 bytes of data
,2015-11-20T12:47:58.066Z SendDataTCPServer.js: TCP/IP server has received 2779584 bytes of data
,2015-11-20T12:47:58.080Z SendDataTCPServer.js: TCP/IP server has received 2810336 bytes of data
,2015-11-20T12:47:58.093Z SendDataTCPServer.js: TCP/IP server has received 2829184 bytes of data
,2015-11-20T12:47:58.118Z SendDataTCPServer.js: TCP/IP server has received 2837120 bytes of data
,2015-11-20T12:47:58.131Z SendDataTCPServer.js: TCP/IP server has received 2862912 bytes of data
,2015-11-20T12:47:58.145Z SendDataTCPServer.js: TCP/IP server has received 2864896 bytes of data
,2015-11-20T12:47:58.170Z SendDataTCPServer.js: TCP/IP server has received 2897632 bytes of data
,2015-11-20T12:47:58.184Z SendDataTCPServer.js: TCP/IP server has received 2902592 bytes of data
,2015-11-20 13:47:58.195 ThaliTest[850:955517] multipeer session: reset timer
2015-11-20 13:47:58.196 ThaliTest[850:955517] multipeer session: stop timer
2015-11-20 13:47:58.196 ThaliTest[850:955517] multipeer session: start timer: 0x16b29630
,2015-11-20T12:47:58.197Z SendDataTCPServer.js: TCP/IP server has received 2915488 bytes of data
2015-11-20 13:47:58.197 ThaliTest[850:955517] server session: connect
2015-11-20 13:47:58.197 ThaliTest[850:955517] server session: stateChange:0->1 Apple-Iphone6-1_PT8859
,2015-11-20 13:47:58.200 ThaliTest[850:955517] server: accepting invitation Apple-Iphone6-1_PT8859
,2015-11-20T12:47:58.210Z SendDataTCPServer.js: TCP/IP server has received 2943264 bytes of data
,2015-11-20T12:47:58.224Z SendDataTCPServer.js: TCP/IP server has received 2957152 bytes of data
,2015-11-20T12:47:58.238Z SendDataTCPServer.js: TCP/IP server has received 2974016 bytes of data
,2015-11-20T12:47:58.251Z SendDataTCPServer.js: TCP/IP server has received 2994848 bytes of data
,2015-11-20T12:47:58.265Z SendDataTCPServer.js: TCP/IP server has received 3015680 bytes of data
,2015-11-20T12:47:58.278Z SendDataTCPServer.js: TCP/IP server has received 3033536 bytes of data
,2015-11-20T12:47:58.292Z SendDataTCPServer.js: TCP/IP server has received 3054496 bytes of data
,2015-11-20T12:47:58.308Z SendDataTCPServer.js: TCP/IP server has received 3074208 bytes of data
,2015-11-20T12:47:58.322Z SendDataTCPServer.js: TCP/IP server has received 3088096 bytes of data
,2015-11-20T12:47:58.336Z SendDataTCPServer.js: TCP/IP server has received 3115872 bytes of data
,2015-11-20T12:47:58.350Z SendDataTCPServer.js: TCP/IP server has received 3139680 bytes of data
,2015-11-20T12:47:58.362Z SendDataTCPServer.js: TCP/IP server has received 3158528 bytes of data
,2015-11-20T12:47:58.374Z SendDataTCPServer.js: TCP/IP server has received 3177376 bytes of data
,2015-11-20T12:47:58.388Z SendDataTCPServer.js: TCP/IP server has received 3190272 bytes of data
,2015-11-20T12:47:58.400Z SendDataTCPServer.js: TCP/IP server has received 3206144 bytes of data
,2015-11-20T12:47:58.412Z SendDataTCPServer.js: TCP/IP server has received 3224000 bytes of data
,2015-11-20T12:47:58.426Z SendDataTCPServer.js: TCP/IP server has received 3247808 bytes of data
,2015-11-20T12:47:58.439Z SendDataTCPServer.js: TCP/IP server has received 3248800 bytes of data
,2015-11-20T12:47:58.453Z SendDataTCPServer.js: TCP/IP server has received 3278560 bytes of data
,2015-11-20T12:47:58.502Z SendDataTCPServer.js: TCP/IP server has received 3297408 bytes of data
,2015-11-20T12:47:58.515Z SendDataTCPServer.js: TCP/IP server has received 3310304 bytes of data
,2015-11-20T12:47:58.528Z SendDataTCPServer.js: TCP/IP server has received 3311296 bytes of data
,2015-11-20T12:47:58.542Z SendDataTCPServer.js: TCP/IP server has received 3332128 bytes of data
,2015-11-20T12:47:58.556Z SendDataTCPServer.js: TCP/IP server has received 3339072 bytes of data
,2015-11-20T12:47:58.569Z SendDataTCPServer.js: TCP/IP server has received 3361888 bytes of data
,2015-11-20T12:47:58.583Z SendDataTCPServer.js: TCP/IP server has received 3387680 bytes of data
,2015-11-20T12:47:58.597Z SendDataTCPServer.js: TCP/IP server has received 3399584 bytes of data
,2015-11-20T12:47:58.697Z SendDataTCPServer.js: TCP/IP server has received 3417440 bytes of data
,2015-11-20T12:47:58.714Z SendDataTCPServer.js: TCP/IP server has received 3445216 bytes of data
,2015-11-20T12:47:58.728Z SendDataTCPServer.js: TCP/IP server has received 3462080 bytes of data
,2015-11-20T12:47:58.766Z SendDataTCPServer.js: TCP/IP server has received 3477952 bytes of data
,2015-11-20T12:47:58.828Z SendDataTCPServer.js: TCP/IP server has received 3480000 bytes of data
,2015-11-20T12:47:58.841Z SendDataTCPServer.js: TCP/IP server has received 3499776 bytes of data
,2015-11-20T12:47:58.855Z SendDataTCPServer.js: TCP/IP server has received 3505728 bytes of data
,2015-11-20T12:47:58.890Z SendDataTCPServer.js: TCP/IP server has received 3512672 bytes of data
,2015-11-20T12:47:58.903Z SendDataTCPServer.js: TCP/IP server has received 3541440 bytes of data
,2015-11-20T12:47:59.038Z SendDataTCPServer.js: TCP/IP server has received 3543424 bytes of data
,2015-11-20T12:47:59.089Z SendDataTCPServer.js: TCP/IP server has received 3549376 bytes of data
,2015-11-20T12:47:59.102Z SendDataTCPServer.js: TCP/IP server has received 3569216 bytes of data
,2015-11-20T12:47:59.165Z SendDataTCPServer.js: TCP/IP server has received 3596992 bytes of data
,2015-11-20T12:47:59.217Z SendDataTCPServer.js: TCP/IP server has received 3603936 bytes of data
,2015-11-20T12:47:59.229Z SendDataTCPServer.js: TCP/IP server has received 3604928 bytes of data
,2015-11-20T12:47:59.277Z SendDataTCPServer.js: TCP/IP server has received 3608896 bytes of data
,2015-11-20T12:47:59.290Z SendDataTCPServer.js: TCP/IP server has received 3640640 bytes of data
,2015-11-20T12:47:59.354Z SendDataTCPServer.js: TCP/IP server has received 3652544 bytes of data
,2015-11-20T12:47:59.418Z SendDataTCPServer.js: TCP/IP server has received 3673376 bytes of data
,2015-11-20T12:47:59.479Z SendDataTCPServer.js: TCP/IP server has received 3692224 bytes of data
,2015-11-20T12:47:59.491Z SendDataTCPServer.js: TCP/IP server has received 3731904 bytes of data
,2015-11-20T12:47:59.539Z SendDataTCPServer.js: TCP/IP server has received 3738848 bytes of data
,2015-11-20T12:47:59.552Z SendDataTCPServer.js: TCP/IP server has received 3777536 bytes of data
,2015-11-20T12:47:59.564Z SendDataTCPServer.js: TCP/IP server has received 3788448 bytes of data
,2015-11-20T12:47:59.628Z SendDataTCPServer.js: TCP/IP server has received 3793408 bytes of data
,2015-11-20T12:47:59.639Z SendDataTCPServer.js: TCP/IP server has received 3800352 bytes of data
,2015-11-20T12:47:59.677Z SendDataTCPServer.js: TCP/IP server has received 3841024 bytes of data
,2015-11-20T12:47:59.691Z SendDataTCPServer.js: TCP/IP server has received 3852928 bytes of data
,2015-11-20T12:47:59.717Z SendDataTCPServer.js: TCP/IP server has received 3858880 bytes of data
,2015-11-20T12:47:59.815Z SendDataTCPServer.js: TCP/IP server has received 3921376 bytes of data
,2015-11-20T12:47:59.878Z SendDataTCPServer.js: TCP/IP server has received 3955104 bytes of data
,2015-11-20T12:47:59.891Z SendDataTCPServer.js: TCP/IP server has received 3964032 bytes of data
,2015-11-20T12:47:59.904Z SendDataTCPServer.js: TCP/IP server has received 3983872 bytes of data
,2015-11-20T12:47:59.926Z SendDataTCPServer.js: TCP/IP server has received 3994784 bytes of data
,2015-11-20T12:47:59.940Z SendDataTCPServer.js: TCP/IP server has received 4013632 bytes of data
,2015-11-20T12:47:59.953Z SendDataTCPServer.js: TCP/IP server has received 4021568 bytes of data
,2015-11-20T12:47:59.965Z SendDataTCPServer.js: TCP/IP server has received 4029504 bytes of data
,2015-11-20T12:48:00.017Z SendDataTCPServer.js: TCP/IP server has received 4042400 bytes of data
,2015-11-20T12:48:00.078Z SendDataTCPServer.js: TCP/IP server has received 4075136 bytes of data
,2015-11-20T12:48:00.092Z SendDataTCPServer.js: TCP/IP server has received 4081088 bytes of data
,2015-11-20T12:48:00.137Z SendDataTCPServer.js: TCP/IP server has received 4092992 bytes of data
,2015-11-20T12:48:00.151Z SendDataTCPServer.js: TCP/IP server has received 4112832 bytes of data
,2015-11-20T12:48:00.177Z SendDataTCPServer.js: TCP/IP server has received 4114816 bytes of data
,2015-11-20T12:48:00.202Z SendDataTCPServer.js: TCP/IP server has received 4143584 bytes of data
,2015-11-20T12:48:00.216Z SendDataTCPServer.js: TCP/IP server has received 4156480 bytes of data
,2015-11-20T12:48:00.255Z SendDataTCPServer.js: TCP/IP server has received 4163424 bytes of data
,2015-11-20T12:48:00.268Z SendDataTCPServer.js: TCP/IP server has received 4207072 bytes of data
,2015-11-20T12:48:00.282Z SendDataTCPServer.js: TCP/IP server has received 4218976 bytes of data
,2015-11-20T12:48:00.333Z SendDataTCPServer.js: TCP/IP server has received 4239808 bytes of data
,2015-11-20T12:48:00.346Z SendDataTCPServer.js: TCP/IP server has received 4260640 bytes of data
,2015-11-20T12:48:00.385Z SendDataTCPServer.js: TCP/IP server has received 4272544 bytes of data
,2015-11-20T12:48:00.397Z SendDataTCPServer.js: TCP/IP server has received 4300320 bytes of data
,2015-11-20T12:48:00.411Z SendDataTCPServer.js: TCP/IP server has received 4323136 bytes of data
,2015-11-20T12:48:00.587Z SendDataTCPServer.js: TCP/IP server has received 4326112 bytes of data
,2015-11-20T12:48:00.600Z SendDataTCPServer.js: TCP/IP server has received 4381664 bytes of data
,2015-11-20T12:48:00.614Z SendDataTCPServer.js: TCP/IP server has received 4385632 bytes of data
,2015-11-20T12:48:00.739Z SendDataTCPServer.js: TCP/IP server has received 4399520 bytes of data
,2015-11-20T12:48:00.791Z SendDataTCPServer.js: TCP/IP server has received 4413408 bytes of data
,2015-11-20T12:48:00.803Z SendDataTCPServer.js: TCP/IP server has received 4441184 bytes of data
,2015-11-20T12:48:00.855Z SendDataTCPServer.js: TCP/IP server has received 4443168 bytes of data
,2015-11-20T12:48:00.868Z SendDataTCPServer.js: TCP/IP server has received 4458048 bytes of data
,2015-11-20T12:48:00.903Z SendDataTCPServer.js: TCP/IP server has received 4469952 bytes of data
,2015-11-20T12:48:00.916Z SendDataTCPServer.js: TCP/IP server has received 4472928 bytes of data
,2015-11-20T12:48:00.929Z SendDataTCPServer.js: TCP/IP server has received 4508640 bytes of data
,2015-11-20 13:48:00.930 ThaliTest[850:956804] server session: connected
2015-11-20 13:48:00.931 ThaliTest[850:956804] server session: stateChange:1->2 Apple-Iphone6-1_PT8859
,2015-11-20 13:48:00.933 ThaliTest[850:955517] server relay: socket disconnected
,2015-11-20 13:48:00.933 ThaliTest[850:955517] server relay: 0x16bf0610 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection re,fused} 
,2015-11-20T12:48:00.944Z SendDataTCPServer.js: TCP/IP server has received 4517568 bytes of data
,2015-11-20T12:48:00.994Z SendDataTCPServer.js: TCP/IP server has received 4528480 bytes of data
,2015-11-20T12:48:01.007Z SendDataTCPServer.js: TCP/IP server has received 4532448 bytes of data
,2015-11-20T12:48:01.031Z SendDataTCPServer.js: TCP/IP server has received 4539392 bytes of data
,2015-11-20T12:48:01.235Z SendDataTCPServer.js: TCP/IP server has received 4547328 bytes of data
,2015-11-20T12:48:01.248Z SendDataTCPServer.js: TCP/IP server has received 4555264 bytes of data
,2015-11-20T12:48:01.262Z SendDataTCPServer.js: TCP/IP server has received 4582048 bytes of data
,2015-11-20T12:48:01.276Z SendDataTCPServer.js: TCP/IP server has received 4599904 bytes of data
,2015-11-20T12:48:01.290Z SendDataTCPServer.js: TCP/IP server has received 4600896 bytes of data
,2015-11-20T12:48:01.303Z SendDataTCPServer.js: TCP/IP server has received 4602880 bytes of data
,2015-11-20T12:48:01.315Z SendDataTCPServer.js: TCP/IP server has received 4640576 bytes of data
,2015-11-20T12:48:01.329Z SendDataTCPServer.js: TCP/IP server has received 4653472 bytes of data
,2015-11-20T12:48:01.367Z SendDataTCPServer.js: TCP/IP server has received 4657440 bytes of data
,2015-11-20T12:48:01.379Z SendDataTCPServer.js: TCP/IP server has received 4668352 bytes of data
,2015-11-20T12:48:01.392Z SendDataTCPServer.js: TCP/IP server has received 4719936 bytes of data
,2015-11-20T12:48:01.444Z SendDataTCPServer.js: TCP/IP server has received 4722912 bytes of data
,2015-11-20T12:48:01.457Z SendDataTCPServer.js: TCP/IP server has received 4752672 bytes of data
,2015-11-20T12:48:01.470Z SendDataTCPServer.js: TCP/IP server has received 4753664 bytes of data
,2015-11-20T12:48:01.483Z SendDataTCPServer.js: TCP/IP server has received 4754656 bytes of data
,2015-11-20T12:48:01.509Z SendDataTCPServer.js: TCP/IP server has received 4771520 bytes of data
,2015-11-20T12:48:01.523Z SendDataTCPServer.js: TCP/IP server has received 4815168 bytes of data
,2015-11-20T12:48:01.575Z SendDataTCPServer.js: TCP/IP server has received 4817152 bytes of data
,2015-11-20T12:48:01.591Z SendDataTCPServer.js: TCP/IP server has received 4871712 bytes of data
,2015-11-20T12:48:01.642Z SendDataTCPServer.js: TCP/IP server has received 4904448 bytes of data
,2015-11-20T12:48:01.654Z SendDataTCPServer.js: TCP/IP server has received 4913376 bytes of data
,2015-11-20T12:48:01.667Z SendDataTCPServer.js: TCP/IP server has received 4920320 bytes of data
,2015-11-20T12:48:01.681Z SendDataTCPServer.js: TCP/IP server has received 4923296 bytes of data
,2015-11-20T12:48:01.717Z SendDataTCPServer.js: TCP/IP server has received 4946112 bytes of data
,2015-11-20T12:48:01.731Z SendDataTCPServer.js: TCP/IP server has received 4979840 bytes of data
,2015-11-20T12:48:02.030Z SendDataTCPServer.js: TCP/IP server has received 4983808 bytes of data
,2015-11-20T12:48:02.044Z SendDataTCPServer.js: TCP/IP server has received 5030432 bytes of data
,2015-11-20T12:48:02.058Z SendDataTCPServer.js: TCP/IP server has received 5042336 bytes of data
,2015-11-20T12:48:02.170Z SendDataTCPServer.js: TCP/IP server has received 5069120 bytes of data
,2015-11-20T12:48:02.183Z SendDataTCPServer.js: TCP/IP server has received 5104832 bytes of data
,2015-11-20T12:48:02.247Z SendDataTCPServer.js: TCP/IP server has received 5106816 bytes of data
,2015-11-20T12:48:02.297Z SendDataTCPServer.js: TCP/IP server has received 5134592 bytes of data
,2015-11-20T12:48:02.310Z SendDataTCPServer.js: TCP/IP server has received 5174272 bytes of data
,2015-11-20T12:48:02.322Z SendDataTCPServer.js: TCP/IP server has received 5188160 bytes of data
,2015-11-20T12:48:02.336Z SendDataTCPServer.js: TCP/IP server has received 5195104 bytes of data
,2015-11-20T12:48:02.362Z SendDataTCPServer.js: TCP/IP server has received 5204032 bytes of data
,2015-11-20T12:48:02.375Z SendDataTCPServer.js: TCP/IP server has received 5255616 bytes of data
,2015-11-20T12:48:02.388Z SendDataTCPServer.js: TCP/IP server has received 5257600 bytes of data
,2015-11-20T12:48:02.426Z SendDataTCPServer.js: TCP/IP server has received 5265536 bytes of data
,2015-11-20T12:48:02.438Z SendDataTCPServer.js: TCP/IP server has received 5306208 bytes of data
,2015-11-20T12:48:02.453Z SendDataTCPServer.js: TCP/IP server has received 5321088 bytes of data
,2015-11-20T12:48:02.464Z SendDataTCPServer.js: TCP/IP server has received 5337952 bytes of data
,2015-11-20T12:48:02.476Z SendDataTCPServer.js: TCP/IP server has received 5352832 bytes of data
,2015-11-20T12:48:02.489Z SendDataTCPServer.js: TCP/IP server has received 5367712 bytes of data
,2015-11-20T12:48:02.501Z SendDataTCPServer.js: TCP/IP server has received 5381600 bytes of data
,2015-11-20T12:48:02.515Z SendDataTCPServer.js: TCP/IP server has received 5399456 bytes of data
,2015-11-20T12:48:02.528Z SendDataTCPServer.js: TCP/IP server has received 5419296 bytes of data
,2015-11-20T12:48:02.542Z SendDataTCPServer.js: TCP/IP server has received 5442112 bytes of data
,2015-11-20T12:48:02.556Z SendDataTCPServer.js: TCP/IP server has received 5463936 bytes of data
,2015-11-20T12:48:02.570Z SendDataTCPServer.js: TCP/IP server has received 5483776 bytes of data
,2015-11-20T12:48:02.582Z SendDataTCPServer.js: TCP/IP server has received 5503616 bytes of data
,2015-11-20T12:48:02.596Z SendDataTCPServer.js: TCP/IP server has received 5521472 bytes of data
,2015-11-20T12:48:02.608Z SendDataTCPServer.js: TCP/IP server has received 5539328 bytes of data
,2015-11-20T12:48:02.619Z SendDataTCPServer.js: TCP/IP server has received 5543296 bytes of data
,2015-11-20T12:48:02.631Z SendDataTCPServer.js: TCP/IP server has received 5579008 bytes of data
,2015-11-20T12:48:02.644Z SendDataTCPServer.js: TCP/IP server has received 5594880 bytes of data
,2015-11-20T12:48:02.655Z SendDataTCPServer.js: TCP/IP server has received 5614720 bytes of data
,2015-11-20T12:48:02.666Z SendDataTCPServer.js: TCP/IP server has received 5630592 bytes of data
,2015-11-20T12:48:02.678Z SendDataTCPServer.js: TCP/IP server has received 5649440 bytes of data
,2015-11-20T12:48:02.691Z SendDataTCPServer.js: TCP/IP server has received 5666304 bytes of data
,2015-11-20T12:48:02.705Z SendDataTCPServer.js: TCP/IP server has received 5696064 bytes of data
,2015-11-20T12:48:02.719Z SendDataTCPServer.js: TCP/IP server has received 5709952 bytes of data
,2015-11-20T12:48:02.731Z SendDataTCPServer.js: TCP/IP server has received 5721856 bytes of data
,2015-11-20T12:48:02.768Z SendDataTCPServer.js: TCP/IP server has received 5726816 bytes of data
,2015-11-20T12:48:02.781Z SendDataTCPServer.js: TCP/IP server has received 5745664 bytes of data
,2015-11-20T12:48:02.794Z SendDataTCPServer.js: TCP/IP server has received 5762528 bytes of data
,2015-11-20T12:48:02.807Z SendDataTCPServer.js: TCP/IP server has received 5779392 bytes of data
,2015-11-20T12:48:02.821Z SendDataTCPServer.js: TCP/IP server has received 5797248 bytes of data
,2015-11-20T12:48:02.834Z SendDataTCPServer.js: TCP/IP server has received 5814112 bytes of data
,2015-11-20T12:48:02.845Z SendDataTCPServer.js: TCP/IP server has received 5828992 bytes of data
,2015-11-20T12:48:02.859Z SendDataTCPServer.js: TCP/IP server has received 5846848 bytes of data
,2015-11-20T12:48:02.871Z SendDataTCPServer.js: TCP/IP server has received 5861728 bytes of data
,2015-11-20T12:48:02.884Z SendDataTCPServer.js: TCP/IP server has received 5877600 bytes of data
,2015-11-20T12:48:02.895Z SendDataTCPServer.js: TCP/IP server has received 5895456 bytes of data
,2015-11-20T12:48:02.907Z SendDataTCPServer.js: TCP/IP server has received 5912320 bytes of data
,2015-11-20T12:48:02.920Z SendDataTCPServer.js: TCP/IP server has received 5933152 bytes of data
,2015-11-20T12:48:02.934Z SendDataTCPServer.js: TCP/IP server has received 5956960 bytes of data
,2015-11-20T12:48:02.948Z SendDataTCPServer.js: TCP/IP server has received 5978784 bytes of data
,2015-11-20T12:48:02.960Z SendDataTCPServer.js: TCP/IP server has received 6000608 bytes of data
,2015-11-20T12:48:02.974Z SendDataTCPServer.js: TCP/IP server has received 6021440 bytes of data
,2015-11-20T12:48:02.988Z SendDataTCPServer.js: TCP/IP server has received 6041280 bytes of data
,2015-11-20T12:48:03.002Z SendDataTCPServer.js: TCP/IP server has received 6063104 bytes of data
,2015-11-20T12:48:03.014Z SendDataTCPServer.js: TCP/IP server has received 6075008 bytes of data
,2015-11-20T12:48:03.078Z SendDataTCPServer.js: TCP/IP server has received 6084928 bytes of data
,2015-11-20T12:48:03.091Z SendDataTCPServer.js: TCP/IP server has received 6130560 bytes of data
,2015-11-20T12:48:03.226Z SendDataTCPServer.js: TCP/IP server has received 6137504 bytes of data
,2015-11-20T12:48:03.240Z SendDataTCPServer.js: TCP/IP server has received 6158336 bytes of data
,2015-11-20T12:48:03.254Z SendDataTCPServer.js: TCP/IP server has received 6176192 bytes of data
,2015-11-20T12:48:03.267Z SendDataTCPServer.js: TCP/IP server has received 6191072 bytes of data
,2015-11-20T12:48:03.279Z SendDataTCPServer.js: TCP/IP server has received 6211904 bytes of data
,2015-11-20T12:48:03.294Z SendDataTCPServer.js: TCP/IP server has received 6230752 bytes of data
,2015-11-20T12:48:03.307Z SendDataTCPServer.js: TCP/IP server has received 6248608 bytes of data
,2015-11-20T12:48:03.320Z SendDataTCPServer.js: TCP/IP server has received 6264480 bytes of data
,2015-11-20T12:48:03.334Z SendDataTCPServer.js: TCP/IP server has received 6278368 bytes of data
,2015-11-20T12:48:03.347Z SendDataTCPServer.js: TCP/IP server has received 6300192 bytes of data
,2015-11-20T12:48:03.361Z SendDataTCPServer.js: TCP/IP server has received 6320032 bytes of data
,2015-11-20T12:48:03.375Z SendDataTCPServer.js: TCP/IP server has received 6340864 bytes of data
,2015-11-20T12:48:03.388Z SendDataTCPServer.js: TCP/IP server has received 6358720 bytes of data
,2015-11-20T12:48:03.402Z SendDataTCPServer.js: TCP/IP server has received 6380544 bytes of data
,2015-11-20T12:48:03.414Z SendDataTCPServer.js: TCP/IP server has received 6398400 bytes of data
,2015-11-20T12:48:03.425Z SendDataTCPServer.js: TCP/IP server has received 6415264 bytes of data
,2015-11-20T12:48:03.438Z SendDataTCPServer.js: TCP/IP server has received 6434112 bytes of data
,2015-11-20T12:48:03.451Z SendDataTCPServer.js: TCP/IP server has received 6450976 bytes of data
,2015-11-20T12:48:03.476Z SendDataTCPServer.js: TCP/IP server has received 6479744 bytes of data
,2015-11-20T12:48:03.489Z SendDataTCPServer.js: TCP/IP server has received 6509504 bytes of data
,2015-11-20T12:48:03.551Z SendDataTCPServer.js: TCP/IP server has received 6515456 bytes of data
,2015-11-20T12:48:03.564Z SendDataTCPServer.js: TCP/IP server has received 6548192 bytes of data
,2015-11-20T12:48:03.579Z SendDataTCPServer.js: TCP/IP server has received 6572000 bytes of data
,2015-11-20T12:48:03.740Z SendDataTCPServer.js: TCP/IP server has received 6599776 bytes of data
,2015-11-20T12:48:03.754Z SendDataTCPServer.js: TCP/IP server has received 6630528 bytes of data
,2015-11-20T12:48:03.767Z SendDataTCPServer.js: TCP/IP server has received 6634496 bytes of data
,2015-11-20T12:48:03.879Z SendDataTCPServer.js: TCP/IP server has received 6635488 bytes of data
,2015-11-20T12:48:03.941Z SendDataTCPServer.js: TCP/IP server has received 6659296 bytes of data
,2015-11-20T12:48:03.955Z SendDataTCPServer.js: TCP/IP server has received 6665248 bytes of data
,2015-11-20T12:48:04.005Z SendDataTCPServer.js: TCP/IP server has received 6679136 bytes of data
,2015-11-20T12:48:04.019Z SendDataTCPServer.js: TCP/IP server has received 6696992 bytes of data
,2015-11-20T12:48:04.132Z SendDataTCPServer.js: TCP/IP server has received 6697984 bytes of data
,2015-11-20T12:48:04.144Z SendDataTCPServer.js: TCP/IP server has received 6713856 bytes of data
,2015-11-20T12:48:04.156Z SendDataTCPServer.js: TCP/IP server has received 6759488 bytes of data
,2015-11-20T12:48:04.208Z SendDataTCPServer.js: TCP/IP server has received 6760480 bytes of data
,2015-11-20T12:48:04.329Z SendDataTCPServer.js: TCP/IP server has received 6775360 bytes of data
,2015-11-20T12:48:04.343Z SendDataTCPServer.js: TCP/IP server has received 6816032 bytes of data
,2015-11-20T12:48:04.404Z SendDataTCPServer.js: TCP/IP server has received 6822976 bytes of data
,2015-11-20T12:48:04.522Z SendDataTCPServer.js: TCP/IP server has received 6827936 bytes of data
,2015-11-20T12:48:04.535Z SendDataTCPServer.js: TCP/IP server has received 6869600 bytes of data
,2015-11-20T12:48:04.549Z SendDataTCPServer.js: TCP/IP server has received 6875552 bytes of data
,2015-11-20T12:48:04.585Z SendDataTCPServer.js: TCP/IP server has received 6879520 bytes of data
,2015-11-20T12:48:04.622Z SendDataTCPServer.js: TCP/IP server has received 6886464 bytes of data
,2015-11-20T12:48:04.662Z SendDataTCPServer.js: TCP/IP server has received 6907296 bytes of data
,2015-11-20T12:48:04.675Z SendDataTCPServer.js: TCP/IP server has received 6928128 bytes of data
,2015-11-20T12:48:04.726Z SendDataTCPServer.js: TCP/IP server has received 6939040 bytes of data
,2015-11-20T12:48:04.739Z SendDataTCPServer.js: TCP/IP server has received 6943008 bytes of data
,2015-11-20T12:48:04.791Z SendDataTCPServer.js: TCP/IP server has received 6944992 bytes of data
,2015-11-20T12:48:04.805Z SendDataTCPServer.js: TCP/IP server has received 6960864 bytes of data
,2015-11-20T12:48:04.831Z SendDataTCPServer.js: TCP/IP server has received 6965824 bytes of data
,2015-11-20T12:48:04.844Z SendDataTCPServer.js: TCP/IP server has received 6969792 bytes of data
,2015-11-20T12:48:04.879Z SendDataTCPServer.js: TCP/IP server has received 6981696 bytes of data
,2015-11-20T12:48:04.914Z SendDataTCPServer.js: TCP/IP server has received 6991616 bytes of data
,2015-11-20T12:48:04.928Z SendDataTCPServer.js: TCP/IP server has received 7002528 bytes of data
,2015-11-20T12:48:04.989Z SendDataTCPServer.js: TCP/IP server has received 7017408 bytes of data
,2015-11-20T12:48:05.002Z SendDataTCPServer.js: TCP/IP server has received 7032288 bytes of data
,2015-11-20T12:48:05.015Z SendDataTCPServer.js: TCP/IP server has received 7033280 bytes of data
,2015-11-20T12:48:05.064Z SendDataTCPServer.js: TCP/IP server has received 7065024 bytes of data
,2015-11-20T12:48:05.177Z SendDataTCPServer.js: TCP/IP server has received 7066016 bytes of data
,2015-11-20T12:48:05.188Z SendDataTCPServer.js: TCP/IP server has received 7083872 bytes of data
,2015-11-20T12:48:05.202Z SendDataTCPServer.js: TCP/IP server has received 7085856 bytes of data
,2015-11-20T12:48:05.288Z SendDataTCPServer.js: TCP/IP server has received 7087840 bytes of data
,2015-11-20T12:48:05.500Z SendDataTCPServer.js: TCP/IP server has received 7095776 bytes of data
,2015-11-20T12:48:05.513Z SendDataTCPServer.js: TCP/IP server has received 7104704 bytes of data
,2015-11-20T12:48:05.631Z SendDataTCPServer.js: TCP/IP server has received 7105696 bytes of data
,2015-11-20T12:48:05.644Z SendDataTCPServer.js: TCP/IP server has received 7127520 bytes of data
,2015-11-20T12:48:05.791Z SendDataTCPServer.js: TCP/IP server has received 7128512 bytes of data
,2015-11-20T12:48:05.913Z SendDataTCPServer.js: TCP/IP server has received 7149344 bytes of data
,2015-11-20T12:48:06.270Z SendDataTCPServer.js: TCP/IP server has received 7155296 bytes of data
,2015-11-20T12:48:06.332Z SendDataTCPServer.js: TCP/IP server has received 7158272 bytes of data
,2015-11-20T12:48:06.586Z SendDataTCPServer.js: TCP/IP server has received 7164224 bytes of data
,2015-11-20T12:48:06.599Z SendDataTCPServer.js: TCP/IP server has received 7166208 bytes of data
,2015-11-20T12:48:07.160Z SendDataTCPServer.js: TCP/IP server has received 7187040 bytes of data
,2015-11-20T12:48:07.173Z SendDataTCPServer.js: TCP/IP server has received 7191008 bytes of data
,2015-11-20T12:48:07.495Z SendDataTCPServer.js: TCP/IP server has received 7211840 bytes of data
,2015-11-20T12:48:07.518Z SendDataTCPServer.js: TCP/IP server has received 7220768 bytes of data
,2015-11-20T12:48:07.566Z SendDataTCPServer.js: TCP/IP server has received 7232672 bytes of data
,2015-11-20T12:48:07.579Z SendDataTCPServer.js: TCP/IP server has received 7267392 bytes of data
,2015-11-20T12:48:07.593Z SendDataTCPServer.js: TCP/IP server has received 7283264 bytes of data
,2015-11-20T12:48:08.008Z SendDataTCPServer.js: TCP/IP server has received 7284256 bytes of data
,2015-11-20T12:48:08.021Z SendDataTCPServer.js: TCP/IP server has received 7285248 bytes of data
,2015-11-20T12:48:08.033Z SendDataTCPServer.js: TCP/IP server has received 7306080 bytes of data
,2015-11-20T12:48:08.047Z SendDataTCPServer.js: TCP/IP server has received 7326912 bytes of data
,2015-11-20T12:48:08.061Z SendDataTCPServer.js: TCP/IP server has received 7341792 bytes of data
,2015-11-20T12:48:08.073Z SendDataTCPServer.js: TCP/IP server has received 7363616 bytes of data
,2015-11-20T12:48:08.084Z SendDataTCPServer.js: TCP/IP server has received 7383456 bytes of data
,2015-11-20T12:48:08.098Z SendDataTCPServer.js: TCP/IP server has received 7402304 bytes of data
,2015-11-20T12:48:08.110Z SendDataTCPServer.js: TCP/IP server has received 7416192 bytes of data
,2015-11-20T12:48:08.123Z SendDataTCPServer.js: TCP/IP server has received 7419168 bytes of data
,2015-11-20T12:48:08.136Z SendDataTCPServer.js: TCP/IP server has received 7437024 bytes of data
,2015-11-20T12:48:08.150Z SendDataTCPServer.js: TCP/IP server has received 7448928 bytes of data
,2015-11-20T12:48:08.161Z SendDataTCPServer.js: TCP/IP server has received 7471744 bytes of data
,2015-11-20T12:48:08.175Z SendDataTCPServer.js: TCP/IP server has received 7492576 bytes of data
,2015-11-20T12:48:08.187Z SendDataTCPServer.js: TCP/IP server has received 7497536 bytes of data
,2015-11-20T12:48:08.199Z SendDataTCPServer.js: TCP/IP server has received 7519360 bytes of data
,2015-11-20T12:48:08.213Z SendDataTCPServer.js: TCP/IP server has received 7548128 bytes of data
,2015-11-20T12:48:08.227Z SendDataTCPServer.js: TCP/IP server has received 7579872 bytes of data
,2015-11-20T12:48:08.238Z SendDataTCPServer.js: TCP/IP server has received 7582848 bytes of data
,2015-11-20T12:48:08.527Z SendDataTCPServer.js: TCP/IP server has received 7591776 bytes of data
,2015-11-20T12:48:08.710Z SendDataTCPServer.js: TCP/IP server has received 7594752 bytes of data
,2015-11-20T12:48:08.723Z SendDataTCPServer.js: TCP/IP server has received 7643360 bytes of data
,2015-11-20T12:48:08.737Z SendDataTCPServer.js: TCP/IP server has received 7645344 bytes of data
,2015-11-20 13:48:09.691 ThaliTest[850:955517] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:48:09.691 ThaliTest[850:955517] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
,2015-11-20T12:48:12.247Z SendDataTCPServer.js: TCP/IP server has received 7666176 bytes of data
,2015-11-20T12:48:12.259Z SendDataTCPServer.js: TCP/IP server has received 7688000 bytes of data
,2015-11-20T12:48:12.273Z SendDataTCPServer.js: TCP/IP server has received 7688992 bytes of data
,2015-11-20T12:48:12.284Z SendDataTCPServer.js: TCP/IP server has received 7690976 bytes of data
,2015-11-20T12:48:12.369Z SendDataTCPServer.js: TCP/IP server has received 7691968 bytes of data
,2015-11-20T12:48:12.382Z SendDataTCPServer.js: TCP/IP server has received 7692960 bytes of data
,2015-11-20T12:48:12.395Z SendDataTCPServer.js: TCP/IP server has received 7693952 bytes of data
,2015-11-20T12:48:12.406Z SendDataTCPServer.js: TCP/IP server has received 7700896 bytes of data
,2015-11-20T12:48:12.420Z SendDataTCPServer.js: TCP/IP server has received 7701888 bytes of data
,2015-11-20T12:48:12.924Z SendDataTCPServer.js: TCP/IP server has received 7708832 bytes of data
,2015-11-20T12:48:12.973Z SendDataTCPServer.js: TCP/IP server has received 7709824 bytes of data
,2015-11-20 13:48:13.037 ThaliTest[850:955517] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
,2015-11-20T12:48:13.279Z SendDataTCPServer.js: TCP/IP server has received 7710816 bytes of data
,2015-11-20T12:48:13.349Z SendDataTCPServer.js: TCP/IP server has received 7711808 bytes of data
,2015-11-20T12:48:13.470Z SendDataTCPServer.js: TCP/IP server has received 7722720 bytes of data
,2015-11-20T12:48:13.484Z SendDataTCPServer.js: TCP/IP server has received 7729664 bytes of data
,2015-11-20T12:48:13.497Z SendDataTCPServer.js: TCP/IP server has received 7730656 bytes of data
,2015-11-20T12:48:13.758Z SendDataTCPServer.js: TCP/IP server has received 7731648 bytes of data
,2015-11-20T12:48:13.954Z SendDataTCPServer.js: TCP/IP server has received 7732640 bytes of data
,2015-11-20T12:48:13.967Z SendDataTCPServer.js: TCP/IP server has received 7739584 bytes of data
,2015-11-20T12:48:13.980Z SendDataTCPServer.js: TCP/IP server has received 7740576 bytes of data
,2015-11-20T12:48:14.313Z SendDataTCPServer.js: TCP/IP server has received 7741568 bytes of data
,2015-11-20T12:48:14.324Z SendDataTCPServer.js: TCP/IP server has received 7742560 bytes of data
,2015-11-20T12:48:14.349Z SendDataTCPServer.js: TCP/IP server has received 7750496 bytes of data
,2015-11-20T12:48:14.361Z SendDataTCPServer.js: TCP/IP server has received 7753472 bytes of data
,2015-11-20T12:48:15.470Z SendDataTCPServer.js: TCP/IP server has received 7754464 bytes of data
,2015-11-20 13:48:16.058 ThaliTest[850:957051] server session: not connected Apple-Iphone6-1_PT8859
,2015-11-20T12:48:16.472Z SendDataTCPServer.js: TCP/IP server has received 7779264 bytes of data
,2015-11-20T12:48:16.486Z SendDataTCPServer.js: TCP/IP server has received 7784224 bytes of data
,2015-11-20T12:48:16.499Z SendDataTCPServer.js: TCP/IP server has received 7785216 bytes of data
,2015-11-20T12:48:16.524Z SendDataTCPServer.js: TCP/IP server has received 7801088 bytes of data
,2015-11-20T12:48:16.563Z SendDataTCPServer.js: TCP/IP server has received 7803072 bytes of data
,2015-11-20T12:48:16.576Z SendDataTCPServer.js: TCP/IP server has received 7804064 bytes of data
,2015-11-20T12:48:16.587Z SendDataTCPServer.js: TCP/IP server has received 7810016 bytes of data
,2015-11-20T12:48:17.042Z SendDataTCPServer.js: TCP/IP server has received 7811008 bytes of data
,2015-11-20T12:48:17.055Z SendDataTCPServer.js: TCP/IP server has received 7816960 bytes of data
,2015-11-20T12:48:17.128Z SendDataTCPServer.js: TCP/IP server has received 7828864 bytes of data
,2015-11-20T12:48:17.142Z SendDataTCPServer.js: TCP/IP server has received 7851680 bytes of data
,2015-11-20T12:48:17.156Z SendDataTCPServer.js: TCP/IP server has received 7862592 bytes of data
,2015-11-20T12:48:17.441Z SendDataTCPServer.js: TCP/IP server has received 7871520 bytes of data
,2015-11-20T12:48:17.454Z SendDataTCPServer.js: TCP/IP server has received 7879456 bytes of data
,2015-11-20 13:48:17.511 ThaliTest[850:955517] multipeer session: reset timer
2015-11-20 13:48:17.511 ThaliTest[850:955517] multipeer session: stop timer
2015-11-20 13:48:17.512 ThaliTest[850:955517] multipeer session: start timer: 0x16b29630
2015-11-20 13:48:17.512 ThaliTest[850:955517] server: disconnecting to refresh session (Apple-Iphone6-1_PT8859)
2015-11-20 13:48:17.512 ThaliTest[850:955517] server session: disconnect
2015-11-20 13:48:17.512 ThaliTest[850:955517] server session: stateChange:2->0 A,pple-Iphone6-1_PT8859
,2015-11-20 13:48:17.512 ThaliTest[850:955517] server session: connect
2015-11-20 13:48:17.512 ThaliTest[850:955517] server session: stateChange:0->1 Apple-Iphone6-1_PT8859
,2015-11-20 13:48:17.517 ThaliTest[850:955517] server: accepting invitation Apple-Iphone6-1_PT8859
,2015-11-20T12:48:17.540Z SendDataTCPServer.js: TCP/IP server has received 7886400 bytes of data
,2015-11-20T12:48:17.552Z SendDataTCPServer.js: TCP/IP server has received 7908224 bytes of data
,2015-11-20T12:48:17.565Z SendDataTCPServer.js: TCP/IP server has received 7932032 bytes of data
,2015-11-20T12:48:17.577Z SendDataTCPServer.js: TCP/IP server has received 7941952 bytes of data
,2015-11-20T12:48:17.971Z SendDataTCPServer.js: TCP/IP server has received 7942944 bytes of data
,2015-11-20T12:48:18.044Z SendDataTCPServer.js: TCP/IP server has received 7943936 bytes of data
,2015-11-20T12:48:18.479Z SendDataTCPServer.js: TCP/IP server has received 7946912 bytes of data
,2015-11-20T12:48:18.492Z SendDataTCPServer.js: TCP/IP server has received 7952864 bytes of data
,2015-11-20T12:48:18.506Z SendDataTCPServer.js: TCP/IP server has received 7955840 bytes of data
,2015-11-20T12:48:18.519Z SendDataTCPServer.js: TCP/IP server has received 7959808 bytes of data
,2015-11-20T12:48:18.554Z SendDataTCPServer.js: TCP/IP server has received 7975680 bytes of data
,2015-11-20T12:48:18.568Z SendDataTCPServer.js: TCP/IP server has received 8003456 bytes of data
,2015-11-20T12:48:18.582Z SendDataTCPServer.js: TCP/IP server has received 8005440 bytes of data
,2015-11-20T12:48:19.013Z SendDataTCPServer.js: TCP/IP server has received 8006432 bytes of data
,2015-11-20T12:48:20.065Z SendDataTCPServer.js: TCP/IP server has received 8007424 bytes of data
,2015-11-20T12:48:20.079Z SendDataTCPServer.js: TCP/IP server has received 8038176 bytes of data
,2015-11-20T12:48:20.092Z SendDataTCPServer.js: TCP/IP server has received 8068928 bytes of data
,2015-11-20 13:48:20.113 ThaliTest[850:956804] server session: connected
2015-11-20 13:48:20.113 ThaliTest[850:956804] server session: stateChange:1->2 Apple-Iphone6-1_PT8859
,2015-11-20 13:48:20.115 ThaliTest[850:955517] server relay: socket disconnected
2015-11-20 13:48:20.116 ThaliTest[850:955517] server relay: 0x16bea440 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20T12:48:20.709Z SendDataTCPServer.js: TCP/IP server has received 8069920 bytes of data
,2015-11-20T12:48:20.782Z SendDataTCPServer.js: TCP/IP server has received 8079840 bytes of data
,2015-11-20T12:48:20.976Z SendDataTCPServer.js: TCP/IP server has received 8104640 bytes of data
,2015-11-20T12:48:20.990Z SendDataTCPServer.js: TCP/IP server has received 8125472 bytes of data
,2015-11-20T12:48:21.114Z SendDataTCPServer.js: TCP/IP server has received 8127456 bytes of data
,2015-11-20T12:48:21.230Z SendDataTCPServer.js: TCP/IP server has received 8131424 bytes of data
,2015-11-20T12:48:21.243Z SendDataTCPServer.js: TCP/IP server has received 8132416 bytes of data
,2015-11-20T12:48:21.585Z SendDataTCPServer.js: TCP/IP server has received 8157216 bytes of data
,2015-11-20T12:48:21.623Z SendDataTCPServer.js: TCP/IP server has received 8158208 bytes of data
,2015-11-20T12:48:21.634Z SendDataTCPServer.js: TCP/IP server has received 8193920 bytes of data
,2015-11-20T12:48:21.660Z SendDataTCPServer.js: TCP/IP server has received 8194912 bytes of data
,2015-11-20T12:48:21.973Z SendDataTCPServer.js: TCP/IP server has received 8202848 bytes of data
,2015-11-20T12:48:21.984Z SendDataTCPServer.js: TCP/IP server has received 8257408 bytes of data
,2015-11-20T12:48:22.181Z SendDataTCPServer.js: TCP/IP server has received 8262368 bytes of data
,2015-11-20T12:48:22.194Z SendDataTCPServer.js: TCP/IP server has received 8280224 bytes of data
,2015-11-20T12:48:22.206Z SendDataTCPServer.js: TCP/IP server has received 8298080 bytes of data
,2015-11-20T12:48:22.218Z SendDataTCPServer.js: TCP/IP server has received 8314944 bytes of data
,2015-11-20T12:48:22.232Z SendDataTCPServer.js: TCP/IP server has received 8332800 bytes of data
,2015-11-20T12:48:22.244Z SendDataTCPServer.js: TCP/IP server has received 8349664 bytes of data
,2015-11-20T12:48:22.257Z SendDataTCPServer.js: TCP/IP server has received 8365536 bytes of data
,2015-11-20T12:48:22.269Z SendDataTCPServer.js: TCP/IP server has received 8382400 bytes of data
,2015-11-20T12:48:22.281Z SendDataTCPServer.js: TCP/IP server has received 8397280 bytes of data
,2015-11-20T12:48:22.294Z SendDataTCPServer.js: TCP/IP server has received 8413152 bytes of data
,2015-11-20T12:48:22.306Z SendDataTCPServer.js: TCP/IP server has received 8433984 bytes of data
,2015-11-20T12:48:22.318Z SendDataTCPServer.js: TCP/IP server has received 8454816 bytes of data
,2015-11-20T12:48:22.330Z SendDataTCPServer.js: TCP/IP server has received 8470688 bytes of data
,2015-11-20 13:48:22.338 ThaliTest[850:956804] server session: not connected Apple-Iphone5-1_PT6611
,2015-11-20T12:48:22.344Z SendDataTCPServer.js: TCP/IP server has received 8472672 bytes of data
,2015-11-20 13:48:22.412 ThaliTest[850:955517] multipeer session: reset timer
2015-11-20 13:48:22.412 ThaliTest[850:955517] multipeer session: stop timer
2015-11-20 13:48:22.412 ThaliTest[850:955517] multipeer session: start timer: 0x16b29630
2015-11-20 13:48:22.412 ThaliTest[850:955517] server: disconnecting to refresh session (Apple-Iphone5-1_PT6611)
2015-11-20 13:48:22.412 ThaliTest[850:955517] server session: disconnect
2015-11-20 13:48:22.413 ThaliTest[850:955517] server session: stateChange:2->0 Apple-Iphone5-1_PT6611
,2015-11-20T12:48:22.415Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-20T12:48:22.415Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
2015-11-20 13:48:22.415 ThaliTest[850:955517] server session: connect
2015-11-20 13:48:22.415 ThaliTest[850:955517] server session: stateChange:0->1 Apple-Iphone5-1_PT6611
,2015-11-20 13:48:22.418 ThaliTest[850:955517] server: accepting invitation Apple-Iphone5-1_PT6611
,2015-11-20 13:48:26.898 ThaliTest[850:956804] server session: connected
2015-11-20 13:48:26.898 ThaliTest[850:956804] server session: stateChange:1->2 Apple-Iphone5-1_PT6611
,2015-11-20 13:48:26.901 ThaliTest[850:955517] server relay: socket disconnected
,2015-11-20 13:48:26.901 ThaliTest[850:955517] server relay: 0x16be00c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 13:48:34.723 ThaliTest[850:956804] server session: not connected Apple-Iphone6-1_PT8859
,2015-11-20 13:48:40.491 ThaliTest[850:956804] server session: not connected Apple-Iphone5-1_PT6611
,2015-11-20 13:48:42.213 ThaliTest[850:955517] multipeer session: reset timer
2015-11-20 13:48:42.213 ThaliTest[850:955517] multipeer session: stop timer
2015-11-20 13:48:42.214 ThaliTest[850:955517] multipeer session: start timer: 0x16b29630
,2015-11-20 13:48:42.214 ThaliTest[850:955517] server: disconnecting to refresh session (Apple-Iphone5-1_PT6611)
2015-11-20 13:48:42.214 ThaliTest[850:955517] server session: disconnect
,2015-11-20 13:48:42.214 ThaliTest[850:955517] server session: stateChange:2->0 Apple-Iphone5-1_PT6611
,2015-11-20 13:48:42.214 ThaliTest[850:955517] server session: connect
,2015-11-20 13:48:42.215 ThaliTest[850:955517] server session: stateChange:0->1 Apple-Iphone5-1_PT6611
,2015-11-20 13:48:42.218 ThaliTest[850:955517] server: accepting invitation Apple-Iphone5-1_PT6611
,2015-11-20 13:48:45.208 ThaliTest[850:957154] server session: connected
2015-11-20 13:48:45.208 ThaliTest[850:957154] server session: stateChange:1->2 Apple-Iphone5-1_PT6611
,2015-11-20 13:48:45.210 ThaliTest[850:955517] server relay: socket disconnected
2015-11-20 13:48:45.210 ThaliTest[850:955517] server relay: 0x16bea580 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 13:48:45.785 ThaliTest[850:955517] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:48:45.785 ThaliTest[850:955517] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:48:51.629 ThaliTest[850:955517] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:48:58.838 ThaliTest[850:957154] server session: not connected Apple-Iphone5-1_PT6611
,2015-11-20 13:49:00.550 ThaliTest[850:955517] multipeer session: reset timer
2015-11-20 13:49:00.550 ThaliTest[850:955517] multipeer session: stop timer
,2015-11-20 13:49:00.551 ThaliTest[850:955517] multipeer session: start timer: 0x16b29630
2015-11-20 13:49:00.551 ThaliTest[850:955517] server: disconnecting to refresh session (Apple-Iphone5-1_PT6611)
2015-11-20 13:49:00.551 ThaliTest[850:955517] server session: disconnect
2015-11-20 13:49:00.551 ThaliTest[850:955517] server session: stateChange:2->0 Apple-Iphone5-1_PT6611
,2015-11-20 13:49:00.552 ThaliTest[850:955517] server session: connect
2015-11-20 13:49:00.552 ThaliTest[850:955517] server session: stateChange:0->1 Apple-Iphone5-1_PT6611
,2015-11-20 13:49:00.555 ThaliTest[850:955517] server: accepting invitation Apple-Iphone5-1_PT6611
,2015-11-20 13:49:03.566 ThaliTest[850:957204] server session: connected
2015-11-20 13:49:03.566 ThaliTest[850:957204] server session: stateChange:1->2 Apple-Iphone5-1_PT6611
,2015-11-20 13:49:03.567 ThaliTest[850:955517] server relay: socket disconnected
2015-11-20 13:49:03.567 ThaliTest[850:955517] server relay: 0x16a11430 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 13:49:12.600 ThaliTest[850:955517] multipeer session: reset timer
,2015-11-20 13:49:12.600 ThaliTest[850:955517] multipeer session: stop timer
2015-11-20 13:49:12.600 ThaliTest[850:955517] multipeer session: start timer: 0x16b29630
,2015-11-20 13:49:12.600 ThaliTest[850:955517] server: disconnecting to refresh session (Apple-Iphone6-1_PT8859)
2015-11-20 13:49:12.601 ThaliTest[850:955517] server session: disconnect
2015-11-20 13:49:12.601 ThaliTest[850:955517] server session: stateChange:2->0 Apple-Iphone6-1_PT8859
,2015-11-20 13:49:12.601 ThaliTest[850:955517] server session: connect
2015-11-20 13:49:12.601 ThaliTest[850:955517] server session: stateChange:0->1 Apple-Iphone6-1_PT8859
,2015-11-20 13:49:12.604 ThaliTest[850:955517] server: accepting invitation Apple-Iphone6-1_PT8859
,2015-11-20 13:49:15.173 ThaliTest[850:957204] server session: connected
2015-11-20 13:49:15.174 ThaliTest[850:957204] server session: stateChange:1->2 Apple-Iphone6-1_PT8859
,2015-11-20 13:49:15.176 ThaliTest[850:955517] server relay: socket disconnected
2015-11-20 13:49:15.176 ThaliTest[850:955517] server relay: 0x16d27700 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 13:49:17.137 ThaliTest[850:955517] client: lost peer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:49:17.137 ThaliTest[850:955517] client session: onPeerLost: Apple-Iphone5s-1_PT7169./ZcTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:49:17.182 ThaliTest[850:957154] server session: not connected Apple-Iphone5-1_PT6611
,2015-11-20 13:49:17.186 ThaliTest[850:955517] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:49:19.279 ThaliTest[850:955517] multipeer session: reset timer
2015-11-20 13:49:19.279 ThaliTest[850:955517] multipeer session: stop timer
2015-11-20 13:49:19.279 ThaliTest[850:955517] multipeer session: start timer: 0x16b29630
,2015-11-20 13:49:19.279 ThaliTest[850:955517] server: disconnecting to refresh session (Apple-Iphone5-1_PT6611)
2015-11-20 13:49:19.279 ThaliTest[850:955517] server session: disconnect
,2015-11-20 13:49:19.279 ThaliTest[850:955517] server session: stateChange:2->0 Apple-Iphone5-1_PT6611
,2015-11-20 13:49:19.280 ThaliTest[850:955517] server session: connect
2015-11-20 13:49:19.280 ThaliTest[850:955517] server session: stateChange:0->1 Apple-Iphone5-1_PT6611
,2015-11-20 13:49:19.283 ThaliTest[850:955517] server: accepting invitation Apple-Iphone5-1_PT6611
,2015-11-20 13:49:23.001 ThaliTest[850:957204] server session: connected
2015-11-20 13:49:23.001 ThaliTest[850:957204] server session: stateChange:1->2 Apple-Iphone5-1_PT6611
,2015-11-20 13:49:23.003 ThaliTest[850:955517] server relay: socket disconnected
2015-11-20 13:49:23.003 ThaliTest[850:955517] server relay: 0x14f6beb0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 13:49:30.370 ThaliTest[850:957233] server session: not connected Apple-Iphone6-1_PT8859
,2015-11-20 13:49:32.090 ThaliTest[850:955517] multipeer session: reset timer
2015-11-20 13:49:32.090 ThaliTest[850:955517] multipeer session: stop timer
2015-11-20 13:49:32.090 ThaliTest[850:955517] multipeer session: start timer: 0x16b29630
2015-11-20 ,13:49:32.090 ThaliTest[850:955517] server: disconnecting to refresh session (Apple-Iphone6-1_PT8859)
2015-11-20 13:49:32.090 ThaliTest[850:955517] server session: disconnect
2015-11-20 13:49:32.090 ThaliTest[850:955517] server session: stateChange:2->0 Apple-Iphone6-1_PT8859
2015-11-20 13:49:32.091 ThaliTest[850:955517] server session: connect
2015-11-20 13:49:32.091 ThaliTest[850:955517] server session: stateChange:0->1 Apple-Iphone6-1_PT8859
,2015-11-20 13:49:32.093 ThaliTest[850:955517] server: accepting invitation Apple-Iphone6-1_PT8859
,2015-11-20 13:49:34.888 ThaliTest[850:957262] server session: connected
,2015-11-20 13:49:34.889 ThaliTest[850:957262] server session: stateChange:1->2 Apple-Iphone6-1_PT8859
,2015-11-20 13:49:34.891 ThaliTest[850:955517] server relay: socket disconnected
2015-11-20 13:49:34.891 ThaliTest[850:955517] server relay: 0x16e81ca0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-11-20 13:49:37.828 ThaliTest[850:957259] server session: not connected Apple-Iphone5-1_PT6611
,2015-11-20 13:49:49.344 ThaliTest[850:955517] client: lost peer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:49:49.345 ThaliTest[850:955517] client session: onPeerLost: Apple-Iphone5s-1_PT7169./ZcTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:49:50.584 ThaliTest[850:957267] server session: not connected Apple-Iphone6-1_PT8859
,2015-11-20 13:49:50.654 ThaliTest[850:955517] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:50.654 ThaliTest[850:955517] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:49:51.426 ThaliTest[850:955517] client: found peer: Apple-Iphone6-1_PT8859.CKR/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:49:52.784 ThaliTest[850:955517] client: lost peer: Apple-Iphone6-1_PT8859.CKR/JA==
2015-11-20 13:49:52.784 ThaliTest[850:955517] client session: onPeerLost: Apple-Iphone6-1_PT8859.CKR/JA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8859.CKR/JA==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:49:52.835 ThaliTest[850:955517] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 13:50:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:50:02.101 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
2015-11-20 13:50:02.102 ThaliTest[850:955517] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:50:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:50:32.101 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:50:32.794 ThaliTest[850:955517] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:51:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:51:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:51:32.098 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:51:32.100 ThaliTest[850:955517] client: found peer: Apple-Iphone5s-1_PT7169./ZcTuw==
,2015-11-20 13:51:36.667 ThaliTest[850:955517] client: lost peer: Apple-Iphone5s-1_PT7169./ZcTuw==
2015-11-20 13:51:36.667 ThaliTest[850:955517] client session: onPeerLost: Apple-Iphone5s-1_PT7169./ZcTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7169./ZcTuw==","peerName":"(null)","peerAvailable":false}]
,2015-11-20 13:52:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:52:02.099 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:52:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:52:32.100 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:53:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:53:02.266 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:53:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:53:32.100 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:54:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:54:02.099 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:54:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:54:32.099 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:55:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:55:02.098 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:55:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:56:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:56:02.100 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:56:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:56:32.099 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:57:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:57:02.302 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:57:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:57:32.099 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:58:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:58:03.063 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:58:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:58:32.098 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 13:59:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:59:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 13:59:32.097 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 14:00:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 14:00:02.098 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 14:00:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 14:00:32.099 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 14:01:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 14:01:02.099 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 14:01:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 14:01:32.100 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 14:02:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 14:02:02.481 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 14:02:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 14:02:32.098 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 14:03:02.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 14:03:02.099 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 14:03:32.091 ThaliTest[850:955517] multipeer session: restart
,2015-11-20 14:03:32.274 ThaliTest[850:955517] client: found peer: Apple-Iphone5-1_PT6611.klJDeA==
,2015-11-20 14:04:02.091 ThaliTest[850:955517] multipeer session: restart

```
