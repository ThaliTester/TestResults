#### Test 51335028f10f918_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028f10f918/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F2EBD30A-23BC-4731-BE55-A0FD832F3622/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F2EBD30A-23BC-4731-BE55-A0FD832F3622/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028f10f918/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028f10f918/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EC26FB85-8309-4841-A3CB-68FF6F870012/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51465"
,(lldb)     command script import "/tmp/F2EBD30A-23BC-4731-BE55-A0FD832F3622/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 14:47:11.583 ThaliTest[860:964797] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DAB10F29-71BE-4211-995D-66A825997BB9/Library/Cookies/Cookies.binarycookies
,2015-11-20 14:47:11.863 ThaliTest[860:964797] Apache Cordova native platform version 3.9.2 is starting.
2015-11-20 14:47:11.864 ThaliTest[860:964797] Multi-tasking -> Device: YES, App: YES
,2015-11-20 14:47:11.870 ThaliTest[860:964797] Unlimited access to network resources
,2015-11-20 14:47:11.876 ThaliTest[860:964797] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 14:47:16.037 ThaliTest[860:964797] Resetting plugins due to page load.
,2015-11-20 14:47:17.328 ThaliTest[860:964797] Finished load of: file:///var/mobile/Containers/Bundle/Application/EC26FB85-8309-4841-A3CB-68FF6F870012/ThaliTest.app/www/index.html
,2015-11-20 14:47:17.475 ThaliTest[860:964797] JXcore Cordova plugin initializing
,2015-11-20 14:47:17.476 ThaliTest[860:965001] JXcore instance initializing
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
toggleWiFi
,my name is : Apple-IpadAir2-1_PT9530
,attempting to connect to test coordinator
check test folder
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
found interfaceName: en0
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
-iface: IPv6 is internal : true, has ip: fe80::1
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
found interfaceName: en0
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
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 ,is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
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
-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
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
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
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
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
fo,und interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
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
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
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
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
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
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
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
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
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
found interfaceName: awdl0
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
found interfaceName: awdl0
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
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"10000000\",\"conReTryTimeout\":\"1000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 55886
,2015-11-20 14:57:12.812 ThaliTest[860:965001] jxcore: startBroadcasting
,2015-11-20 14:57:12.818 ThaliTest[860:965001] server: starting Apple-IpadAir2-1_PT9530.n+0V8A==
,2015-11-20 14:57:12.819 ThaliTest[860:965001] multipeer session: start timer: 0x199bfea0
,2015-11-20 14:57:12.820 ThaliTest[860:965001] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT9530
2015-11-20 14:57:12.821 ThaliTest[860:965001] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-20T13:57:12.825Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-20 14:57:13.536 ThaliTest[860:964797] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:57:13.538Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:57:13.539Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==,
2015-11-20T13:57:13.539Z SendDataConnector.js: do connect now
2015-11-20 14:57:13.539 ThaliTest[860:965001] jxcore: connect Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:13.539 ThaliTest[860:965001] client session: connect
,2015-11-20 14:57:13.540 ThaliTest[860:965001] client session: stateChange:0->1 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:14.494 ThaliTest[860:964797] multipeer session: reset timer
2015-11-20 14:57:14.494 ThaliTest[860:964797] multipeer session: stop timer
2015-11-20 14:57:14.494 ThaliTest[860:964797] multipeer session: start timer: 0x199bfea0
2015-11-20 14:57:14.494 ThaliTest[860:964797] server session: connect
2015-11-20 14:57:14.494 ThaliTest[860:964797] server session: stateChange:0->1 Apple-Iphone5s-1_PT9513
,2015-11-20 14:57:14.497 ThaliTest[860:964797] server: accepting invitation Apple-Iphone5s-1_PT9513
,2015-11-20 14:57:14.738 ThaliTest[860:964797] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT738.lFO7fw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 14:57:16.409 ThaliTest[860:964797] client: found peer: Apple-Iphone6-1_PT8294.ood35g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8294.ood35g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-20 14:57:17.519 ThaliTest[860:966202] client session: connected
2015-11-20 14:57:17.520 ThaliTest[860:966202] client session: stateChange:1->2 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:17.531 ThaliTest[860:966202] client session: fireConnectCallback: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:57:17.531 ThaliTest[860:966202] jxcore: connect: success
2015-11-20T13:57:17.532Z SendDataConnector.js: CLIENT connected to 55889, error: null
2015-11-20T13:57:17.532Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:57:17.533 ThaliTest[860:964797] client: relay established
2015-11-20 14:57:17.533 ThaliTest[860:964797] client: new accepted socket: 0x199c6330
,2015-11-20T13:57:17.546Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 14:57:17.638 ThaliTest[860:966193] server session: connected
2015-11-20 14:57:17.639 ThaliTest[860:966193] server session: stateChange:1->2 Apple-Iphone5s-1_PT9513
,2015-11-20 14:57:17.647 ThaliTest[860:964797] server relay: connected (to port: 55886)
,2015-11-20T13:57:21.672Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:57:21.799Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20T13:57:31.673Z SendDataConnector.js: Receiving data timeout now
2015-11-20T13:57:31.673Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T13:57:31.674Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20T13:57:31.674Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T13:57:32.676Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:57:32.676Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:57:33.678 ThaliTest[860:965001] jxcore: disconnect
,2015-11-20 14:57:33.678 ThaliTest[860:965001] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:57:33.678 ThaliTest[860:965001] client session: disconnect
2015-11-20 14:57:33.678 ThaliTest[860:965001] client session: stat,eChange:2->0 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:58:00.794 ThaliTest[860:966292] server session: not connected Apple-Iphone5s-1_PT9513
,2015-11-20 14:58:47.973 ThaliTest[860:965001] jxcore: disconnect: success
2015-11-20T13:58:47.974Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:58:47.974Z SendDataConnector.js: Connect (retry, count 1) to peer Apple-Iphone5s-1_PT9513.+kbAXQ== with availability status: true
2015-11-20T13:58:47.974Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:58:47.974Z SendDataConnector.js: do connect now
2015-11-20 14:58:47.974 ThaliTest[860:965001] jxcore: connect Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:58:47.974 ThaliTest[860:965001] client session: connect
2015-11-20 14:58:47.974 ThaliTest[860:965001] client session: stateChange:0->1 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:58:47.977 ThaliTest[860:964797] multipeer session: restart
,2015-11-20 14:58:47.980 ThaliTest[860:964797] client: lost peer: Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:58:47.980 ThaliTest[860:964797] client session: onPeerLost: Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20T13:58:47.982Z SendDataTCPServer.js: TCP/IP server has received 4096 bytes of data
2015-11-20 14:58:47.983 ThaliTest[860:964797] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:58:47.983 ThaliTest[860:964797] client session: o,nPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:58:47.983 ThaliTest[860:964797] client session: onLinkFailure: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:58:47.983 ThaliTest[860:964797] client session: disconnect
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8294.ood35g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2015-11-20 14:58:47.983 ThaliTest[860:964797] client session: stateChange:1->0 Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:58:47.984 ThaliTest[860:964797] client session: fireConnectCallback: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:58:47.984 ThaliTest[860:964797] jxcore: connect: fail: Peer disconnected
,2015-11-20T13:58:47.988Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T13:58:47.988Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T13:58:47.989Z SendDataConnector.js: tryAgain afer: 1000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20T13:58:48.002Z SendDataTCPServer.js: TCP/IP server has received 131072 bytes of data
,2015-11-20 14:58:48.012 ThaliTest[860:964797] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:58:48.012 ThaliTest[860:964797] client: found peer: Apple-Iphone6-1_PT8294.ood35g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8294.ood35g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-20 14:58:48.015 ThaliTest[860:964797] client: found peer: Apple-Iphone6-1_PT8294.ood35g==
,2015-11-20 14:58:48.017 ThaliTest[860:964797] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:58:48.017 ThaliTest[860:964797] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:58:48.993Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:58:48.993Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:58:49.994 ThaliTest[860:965001] jxcore: disconnect
2015-11-20 14:58:49.994 ThaliTest[860:965001] jxcore: disconnect: fail
2015-11-20T13:58:49.994Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:58:49.994Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT9513.+kbAXQ== with availability status: true
2015-11-20T13:58:49.995Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:58:49.995Z SendDataConnector.js: do connect now
,2015-11-20 14:58:49.995 ThaliTest[860:965001] jxcore: connect Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:58:49.995 ThaliTest[860:965001] client session: connect
2015-11-20 14:58:49.995 ThaliTest[860:965001] client session: stateChange:0->1 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:59:02.410 ThaliTest[860:966405] client session: not connected Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:59:02.410 ThaliTest[860:966405] client session: onLinkFailure: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:59:02.410 ThaliTest[860:966405] client session: disconnect
2015-11-20 14:59:02.410 ThaliTest[860:966405] client session: stateChange:1->0 Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:59:02.418 ThaliTest[860:966405] client session: fireConnectCallback: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:59:02.418 ThaliTest[860:966405] jxcore: connect: fail: Peer disconnected
,2015-11-20T13:59:02.419Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-11-20T13:59:02.419Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-20T13:59:02.419Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T13:59:03.427Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:59:03.427Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:59:04.437 ThaliTest[860:965001] jxcore: disconnect
2015-11-20 14:59:04.437 ThaliTest[860:965001] jxcore: disconnect: fail
,2015-11-20T13:59:04.438Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:59:04.438Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT9513.+kbAXQ== with availability status,: true
2015-11-20T13:59:04.438Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:59:04.438Z SendDataConnector.js: do connect now
,2015-11-20 14:59:04.438 ThaliTest[860:965001] jxcore: connect Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:59:04.439 ThaliTest[860:965001] client session: connect
2015-11-20 14:59:04.439 ThaliTest[860:965001] client session: stateChange:0->1 Apple-Ipho,ne5s-1_PT9513.+kbAXQ==
,2015-11-20 14:59:12.979 ThaliTest[860:964797] multipeer session: reset timer
2015-11-20 14:59:12.979 ThaliTest[860:964797] multipeer session: stop timer
2015-11-20 14:59:12.979 ThaliTest[860:964797] multipeer session: start timer: 0x199bfea0
2015-11-20 14:59:12.979 ThaliTest[860:964797] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9513)
2015-11-20 14:59:12.979 ThaliTest[860:964797] server session: disconnect
,2015-11-20 14:59:12.979 ThaliTest[860:964797] server session: stateChange:2->0 Apple-Iphone5s-1_PT9513
,2015-11-20T13:59:12.989Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-20 14:59:13.034 ThaliTest[860:964797] server session: connect
2015-11-20 14:59:13.034 ThaliTest[860:964797] server session: stateChange:0->1 Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:13.037 ThaliTest[860:964797] server: accepting invitation Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:13.037 ThaliTest[860:964797] multipeer session: reset timer
2015-11-20 14:59:13.037 ThaliTest[860:964797] multipeer session: stop timer
2015-11-20 14:59:13.038 ThaliTest[860:964797] multipeer session: start timer: 0x199bfea0
2015-11-20 ,14:59:13.038 ThaliTest[860:964797] server: disconnecting to refresh session (Apple-Iphone5s-1_PT9513)
2015-11-20 14:59:13.038 ThaliTest[860:964797] server session: disconnect
2015-11-20 14:59:13.038 ThaliTest[860:964797] server session: stateChange:1->0 Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:13.039 ThaliTest[860:964797] server session: connect
2015-11-20 14:59:13.039 ThaliTest[860:964797] server session: stateChange:0->1 Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:13.043 ThaliTest[860:964797] server: accepting invitation Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:16.045 ThaliTest[860:966474] server session: connected
2015-11-20 14:59:16.045 ThaliTest[860:966474] server session: stateChange:1->2 Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:16.056 ThaliTest[860:964797] server relay: connected (to port: 55886)
,2015-11-20T13:59:16.060Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-20 14:59:18.150 ThaliTest[860:964797] client: lost peer: Apple-Iphone6-1_PT8294.ood35g==
2015-11-20 14:59:18.151 ThaliTest[860:964797] client session: onPeerLost: Apple-Iphone6-1_PT8294.ood35g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT8294.ood35g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-20T13:59:20.821Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-20T13:59:20.835Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-11-20T13:59:20.849Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-11-20T13:59:20.862Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-11-20T13:59:20.888Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-11-20T13:59:20.900Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-11-20T13:59:21.222Z SendDataTCPServer.js: TCP/IP server has received 155206 bytes of data
,2015-11-20T13:59:21.236Z SendDataTCPServer.js: TCP/IP server has received 162060 bytes of data
,2015-11-20T13:59:21.249Z SendDataTCPServer.js: TCP/IP server has received 168630 bytes of data
,2015-11-20T13:59:21.262Z SendDataTCPServer.js: TCP/IP server has received 186150 bytes of data
,2015-11-20T13:59:21.287Z SendDataTCPServer.js: TCP/IP server has received 216810 bytes of data
,2015-11-20T13:59:21.301Z SendDataTCPServer.js: TCP/IP server has received 232140 bytes of data
,2015-11-20T13:59:21.350Z SendDataTCPServer.js: TCP/IP server has received 234330 bytes of data
,2015-11-20T13:59:21.412Z SendDataTCPServer.js: TCP/IP server has received 258420 bytes of data
,2015-11-20T13:59:21.425Z SendDataTCPServer.js: TCP/IP server has received 313170 bytes of data
,2015-11-20T13:59:21.441Z SendDataTCPServer.js: TCP/IP server has received 359160 bytes of data
,2015-11-20T13:59:21.453Z SendDataTCPServer.js: TCP/IP server has received 365588 bytes of data
,2015-11-20T13:59:21.466Z SendDataTCPServer.js: TCP/IP server has received 376680 bytes of data
,2015-11-20T13:59:21.479Z SendDataTCPServer.js: TCP/IP server has received 422670 bytes of data
,2015-11-20T13:59:21.493Z SendDataTCPServer.js: TCP/IP server has received 464280 bytes of data
,2015-11-20T13:59:21.748Z SendDataTCPServer.js: TCP/IP server has received 498894 bytes of data
,2015-11-20T13:59:21.763Z SendDataTCPServer.js: TCP/IP server has received 549690 bytes of data
,2015-11-20T13:59:21.800Z SendDataTCPServer.js: TCP/IP server has received 560640 bytes of data
,2015-11-20T13:59:21.813Z SendDataTCPServer.js: TCP/IP server has received 604440 bytes of data
,2015-11-20T13:59:21.876Z SendDataTCPServer.js: TCP/IP server has received 611010 bytes of data
,2015-11-20T13:59:22.036Z SendDataTCPServer.js: TCP/IP server has received 742082 bytes of data
,2015-11-20T13:59:22.038Z SendDataTCPServer.js: TCP/IP server has received 751170 bytes of data
,2015-11-20T13:59:22.064Z SendDataTCPServer.js: TCP/IP server has received 766500 bytes of data
,2015-11-20T13:59:22.077Z SendDataTCPServer.js: TCP/IP server has received 784020 bytes of data
,2015-11-20T13:59:22.102Z SendDataTCPServer.js: TCP/IP server has received 797160 bytes of data
,2015-11-20T13:59:22.115Z SendDataTCPServer.js: TCP/IP server has received 814680 bytes of data
,2015-11-20T13:59:22.129Z SendDataTCPServer.js: TCP/IP server has received 816870 bytes of data
,2015-11-20T13:59:22.143Z SendDataTCPServer.js: TCP/IP server has received 860670 bytes of data
,2015-11-20T13:59:22.206Z SendDataTCPServer.js: TCP/IP server has received 913230 bytes of data
,2015-11-20T13:59:22.233Z SendDataTCPServer.js: TCP/IP server has received 930750 bytes of data
,2015-11-20T13:59:22.271Z SendDataTCPServer.js: TCP/IP server has received 994260 bytes of data
,2015-11-20T13:59:22.285Z SendDataTCPServer.js: TCP/IP server has received 998640 bytes of data
,2015-11-20T13:59:22.334Z SendDataTCPServer.js: TCP/IP server has received 1059960 bytes of data
,2015-11-20T13:59:22.349Z SendDataTCPServer.js: TCP/IP server has received 1090620 bytes of data
,2015-11-20T13:59:22.399Z SendDataTCPServer.js: TCP/IP server has received 1138800 bytes of data
,2015-11-20T13:59:22.413Z SendDataTCPServer.js: TCP/IP server has received 1156320 bytes of data
,2015-11-20T13:59:22.426Z SendDataTCPServer.js: TCP/IP server has received 1160700 bytes of data
,2015-11-20T13:59:22.439Z SendDataTCPServer.js: TCP/IP server has received 1167270 bytes of data
,2015-11-20T13:59:22.464Z SendDataTCPServer.js: TCP/IP server has received 1215308 bytes of data
,2015-11-20T13:59:22.477Z SendDataTCPServer.js: TCP/IP server has received 1237350 bytes of data
,2015-11-20T13:59:22.529Z SendDataTCPServer.js: TCP/IP server has received 1294290 bytes of data
,2015-11-20T13:59:22.545Z SendDataTCPServer.js: TCP/IP server has received 1335900 bytes of data
,2015-11-20T13:59:22.593Z SendDataTCPServer.js: TCP/IP server has received 1392840 bytes of data
,2015-11-20T13:59:22.606Z SendDataTCPServer.js: TCP/IP server has received 1408170 bytes of data
,2015-11-20T13:59:22.619Z SendDataTCPServer.js: TCP/IP server has received 1416930 bytes of data
,2015-11-20T13:59:22.631Z SendDataTCPServer.js: TCP/IP server has received 1449780 bytes of data
,2015-11-20T13:59:22.646Z SendDataTCPServer.js: TCP/IP server has received 1502340 bytes of data
,2015-11-20T13:59:22.660Z SendDataTCPServer.js: TCP/IP server has received 1541760 bytes of data
,2015-11-20T13:59:22.673Z SendDataTCPServer.js: TCP/IP server has received 1572420 bytes of data
,2015-11-20T13:59:22.687Z SendDataTCPServer.js: TCP/IP server has received 1607460 bytes of data
,2015-11-20T13:59:22.700Z SendDataTCPServer.js: TCP/IP server has received 1642358 bytes of data
,2015-11-20T13:59:22.714Z SendDataTCPServer.js: TCP/IP server has received 1686300 bytes of data
,2015-11-20T13:59:22.728Z SendDataTCPServer.js: TCP/IP server has received 1730100 bytes of data
,2015-11-20T13:59:22.741Z SendDataTCPServer.js: TCP/IP server has received 1745430 bytes of data
,2015-11-20T13:59:22.755Z SendDataTCPServer.js: TCP/IP server has received 1800180 bytes of data
,2015-11-20T13:59:22.770Z SendDataTCPServer.js: TCP/IP server has received 1843980 bytes of data
,2015-11-20T13:59:22.784Z SendDataTCPServer.js: TCP/IP server has received 1870260 bytes of data
,2015-11-20T13:59:22.809Z SendDataTCPServer.js: TCP/IP server has received 1896540 bytes of data
,2015-11-20T13:59:22.822Z SendDataTCPServer.js: TCP/IP server has received 1900920 bytes of data
,2015-11-20T13:59:22.836Z SendDataTCPServer.js: TCP/IP server has received 1938150 bytes of data
,2015-11-20T13:59:22.850Z SendDataTCPServer.js: TCP/IP server has received 1968810 bytes of data
,2015-11-20T13:59:22.863Z SendDataTCPServer.js: TCP/IP server has received 2001660 bytes of data
,2015-11-20T13:59:22.877Z SendDataTCPServer.js: TCP/IP server has received 2014800 bytes of data
,2015-11-20T13:59:22.891Z SendDataTCPServer.js: TCP/IP server has received 2073930 bytes of data
,2015-11-20T13:59:22.906Z SendDataTCPServer.js: TCP/IP server has received 2108828 bytes of data
,2015-11-20T13:59:22.920Z SendDataTCPServer.js: TCP/IP server has received 2157150 bytes of data
,2015-11-20T13:59:22.935Z SendDataTCPServer.js: TCP/IP server has received 2205330 bytes of data
,2015-11-20T13:59:22.948Z SendDataTCPServer.js: TCP/IP server has received 2253510 bytes of data
,2015-11-20T13:59:22.961Z SendDataTCPServer.js: TCP/IP server has received 2288550 bytes of data
,2015-11-20T13:59:22.974Z SendDataTCPServer.js: TCP/IP server has received 2310450 bytes of data
,2015-11-20T13:59:22.988Z SendDataTCPServer.js: TCP/IP server has received 2356440 bytes of data
,2015-11-20T13:59:23.014Z SendDataTCPServer.js: TCP/IP server has received 2389290 bytes of data
,2015-11-20T13:59:23.027Z SendDataTCPServer.js: TCP/IP server has received 2419950 bytes of data
,2015-11-20T13:59:23.041Z SendDataTCPServer.js: TCP/IP server has received 2446088 bytes of data
,2015-11-20T13:59:23.056Z SendDataTCPServer.js: TCP/IP server has received 2516310 bytes of data
,2015-11-20T13:59:23.070Z SendDataTCPServer.js: TCP/IP server has received 2560110 bytes of data
,2015-11-20T13:59:23.084Z SendDataTCPServer.js: TCP/IP server has received 2597340 bytes of data
,2015-11-20T13:59:23.099Z SendDataTCPServer.js: TCP/IP server has received 2643330 bytes of data
,2015-11-20T13:59:23.113Z SendDataTCPServer.js: TCP/IP server has received 2665088 bytes of data
,2015-11-20T13:59:23.128Z SendDataTCPServer.js: TCP/IP server has received 2735310 bytes of data
,2015-11-20T13:59:23.144Z SendDataTCPServer.js: TCP/IP server has received 2776920 bytes of data
,2015-11-20T13:59:23.158Z SendDataTCPServer.js: TCP/IP server has received 2796630 bytes of data
,2015-11-20T13:59:23.173Z SendDataTCPServer.js: TCP/IP server has received 2820720 bytes of data
,2015-11-20T13:59:23.186Z SendDataTCPServer.js: TCP/IP server has received 2875470 bytes of data
,2015-11-20T13:59:23.202Z SendDataTCPServer.js: TCP/IP server has received 2945550 bytes of data
,2015-11-20T13:59:23.215Z SendDataTCPServer.js: TCP/IP server has received 3002490 bytes of data
,2015-11-20T13:59:23.231Z SendDataTCPServer.js: TCP/IP server has received 3059430 bytes of data
,2015-11-20T13:59:23.245Z SendDataTCPServer.js: TCP/IP server has received 3107610 bytes of data
,2015-11-20T13:59:23.259Z SendDataTCPServer.js: TCP/IP server has received 3162360 bytes of data
,2015-11-20T13:59:23.273Z SendDataTCPServer.js: TCP/IP server has received 3212730 bytes of data
,2015-11-20T13:59:23.286Z SendDataTCPServer.js: TCP/IP server has received 3260910 bytes of data
,2015-11-20T13:59:23.300Z SendDataTCPServer.js: TCP/IP server has received 3300330 bytes of data
,2015-11-20T13:59:23.314Z SendDataTCPServer.js: TCP/IP server has received 3304710 bytes of data
,2015-11-20T13:59:23.325Z SendDataTCPServer.js: TCP/IP server has received 3370268 bytes of data
,2015-11-20T13:59:23.339Z SendDataTCPServer.js: TCP/IP server has received 3407640 bytes of data
,2015-11-20T13:59:23.352Z SendDataTCPServer.js: TCP/IP server has received 3440490 bytes of data
,2015-11-20T13:59:23.365Z SendDataTCPServer.js: TCP/IP server has received 3477578 bytes of data
,2015-11-20T13:59:23.378Z SendDataTCPServer.js: TCP/IP server has received 3501810 bytes of data
,2015-11-20T13:59:23.392Z SendDataTCPServer.js: TCP/IP server has received 3532470 bytes of data
,2015-11-20T13:59:23.405Z SendDataTCPServer.js: TCP/IP server has received 3574080 bytes of data
,2015-11-20T13:59:23.418Z SendDataTCPServer.js: TCP/IP server has received 3580650 bytes of data
,2015-11-20T13:59:23.431Z SendDataTCPServer.js: TCP/IP server has received 3593790 bytes of data
,2015-11-20T13:59:23.445Z SendDataTCPServer.js: TCP/IP server has received 3646350 bytes of data
,2015-11-20T13:59:23.459Z SendDataTCPServer.js: TCP/IP server has received 3679200 bytes of data
,2015-11-20T13:59:23.472Z SendDataTCPServer.js: TCP/IP server has received 3718620 bytes of data
,2015-11-20T13:59:23.485Z SendDataTCPServer.js: TCP/IP server has received 3744758 bytes of data
,2015-11-20T13:59:23.498Z SendDataTCPServer.js: TCP/IP server has received 3784320 bytes of data
,2015-11-20T13:59:23.512Z SendDataTCPServer.js: TCP/IP server has received 3795270 bytes of data
,2015-11-20T13:59:23.523Z SendDataTCPServer.js: TCP/IP server has received 3834690 bytes of data
,2015-11-20T13:59:23.537Z SendDataTCPServer.js: TCP/IP server has received 3841260 bytes of data
,2015-11-20T13:59:23.587Z SendDataTCPServer.js: TCP/IP server has received 3902580 bytes of data
,2015-11-20T13:59:23.600Z SendDataTCPServer.js: TCP/IP server has received 3944190 bytes of data
,2015-11-20T13:59:23.613Z SendDataTCPServer.js: TCP/IP server has received 3972660 bytes of data
,2015-11-20T13:59:23.626Z SendDataTCPServer.js: TCP/IP server has received 4007700 bytes of data
,2015-11-20T13:59:23.640Z SendDataTCPServer.js: TCP/IP server has received 4016460 bytes of data
,2015-11-20T13:59:23.654Z SendDataTCPServer.js: TCP/IP server has received 4055880 bytes of data
,2015-11-20T13:59:23.669Z SendDataTCPServer.js: TCP/IP server has received 4090920 bytes of data
,2015-11-20T13:59:23.719Z SendDataTCPServer.js: TCP/IP server has received 4139100 bytes of data
,2015-11-20T13:59:23.733Z SendDataTCPServer.js: TCP/IP server has received 4143480 bytes of data
,2015-11-20T13:59:23.779Z SendDataTCPServer.js: TCP/IP server has received 4198230 bytes of data
,2015-11-20T13:59:23.818Z SendDataTCPServer.js: TCP/IP server has received 4206706 bytes of data
,2015-11-20T13:59:23.832Z SendDataTCPServer.js: TCP/IP server has received 4211370 bytes of data
,2015-11-20T13:59:23.845Z SendDataTCPServer.js: TCP/IP server has received 4250790 bytes of data
,2015-11-20T13:59:23.903Z SendDataTCPServer.js: TCP/IP server has received 4263930 bytes of data
,2015-11-20T13:59:23.967Z SendDataTCPServer.js: TCP/IP server has received 4270074 bytes of data
,2015-11-20T13:59:23.981Z SendDataTCPServer.js: TCP/IP server has received 4301160 bytes of data
,2015-11-20T13:59:23.995Z SendDataTCPServer.js: TCP/IP server has received 4313590 bytes of data
,2015-11-20T13:59:24.007Z SendDataTCPServer.js: TCP/IP server has received 4340580 bytes of data
,2015-11-20T13:59:24.033Z SendDataTCPServer.js: TCP/IP server has received 4351530 bytes of data
,2015-11-20T13:59:24.046Z SendDataTCPServer.js: TCP/IP server has received 4362480 bytes of data
,2015-11-20T13:59:24.058Z SendDataTCPServer.js: TCP/IP server has received 4366860 bytes of data
,2015-11-20T13:59:24.071Z SendDataTCPServer.js: TCP/IP server has received 4373430 bytes of data
,2015-11-20T13:59:24.109Z SendDataTCPServer.js: TCP/IP server has received 4404090 bytes of data
,2015-11-20T13:59:24.147Z SendDataTCPServer.js: TCP/IP server has received 4408470 bytes of data
,2015-11-20T13:59:24.196Z SendDataTCPServer.js: TCP/IP server has received 4423800 bytes of data
,2015-11-20T13:59:24.209Z SendDataTCPServer.js: TCP/IP server has received 4434750 bytes of data
,2015-11-20T13:59:24.235Z SendDataTCPServer.js: TCP/IP server has received 4467600 bytes of data
,2015-11-20T13:59:24.249Z SendDataTCPServer.js: TCP/IP server has received 4498260 bytes of data
,2015-11-20T13:59:24.263Z SendDataTCPServer.js: TCP/IP server has received 4504830 bytes of data
,2015-11-20T13:59:24.297Z SendDataTCPServer.js: TCP/IP server has received 4561770 bytes of data
,2015-11-20T13:59:24.371Z SendDataTCPServer.js: TCP/IP server has received 4577100 bytes of data
,2015-11-20T13:59:24.434Z SendDataTCPServer.js: TCP/IP server has received 4627470 bytes of data
,2015-11-20T13:59:24.459Z SendDataTCPServer.js: TCP/IP server has received 4638420 bytes of data
,2015-11-20T13:59:24.560Z SendDataTCPServer.js: TCP/IP server has received 4680030 bytes of data
,2015-11-20T13:59:24.574Z SendDataTCPServer.js: TCP/IP server has received 4734780 bytes of data
,2015-11-20T13:59:24.588Z SendDataTCPServer.js: TCP/IP server has received 4739160 bytes of data
,2015-11-20T13:59:24.613Z SendDataTCPServer.js: TCP/IP server has received 4750110 bytes of data
,2015-11-20T13:59:24.625Z SendDataTCPServer.js: TCP/IP server has received 4774200 bytes of data
,2015-11-20T13:59:24.636Z SendDataTCPServer.js: TCP/IP server has received 4776390 bytes of data
,2015-11-20T13:59:24.649Z SendDataTCPServer.js: TCP/IP server has received 4778580 bytes of data
,2015-11-20T13:59:24.700Z SendDataTCPServer.js: TCP/IP server has received 4780770 bytes of data
,2015-11-20T13:59:24.725Z SendDataTCPServer.js: TCP/IP server has received 4789530 bytes of data
,2015-11-20T13:59:24.761Z SendDataTCPServer.js: TCP/IP server has received 4853040 bytes of data
,2015-11-20T13:59:24.788Z SendDataTCPServer.js: TCP/IP server has received 4855230 bytes of data
,2015-11-20T13:59:24.813Z SendDataTCPServer.js: TCP/IP server has received 4859610 bytes of data
,2015-11-20T13:59:24.825Z SendDataTCPServer.js: TCP/IP server has received 4914360 bytes of data
,2015-11-20T13:59:24.837Z SendDataTCPServer.js: TCP/IP server has received 4942830 bytes of data
,2015-11-20T13:59:24.851Z SendDataTCPServer.js: TCP/IP server has received 4969110 bytes of data
,2015-11-20T13:59:24.899Z SendDataTCPServer.js: TCP/IP server has received 5008530 bytes of data
,2015-11-20T13:59:24.924Z SendDataTCPServer.js: TCP/IP server has received 5010720 bytes of data
,2015-11-20T13:59:24.936Z SendDataTCPServer.js: TCP/IP server has received 5012910 bytes of data
,2015-11-20T13:59:24.950Z SendDataTCPServer.js: TCP/IP server has received 5034810 bytes of data
,2015-11-20T13:59:24.963Z SendDataTCPServer.js: TCP/IP server has received 5067660 bytes of data
,2015-11-20T13:59:24.977Z SendDataTCPServer.js: TCP/IP server has received 5069850 bytes of data
,2015-11-20T13:59:25.000Z SendDataTCPServer.js: TCP/IP server has received 5078610 bytes of data
,2015-11-20T13:59:25.011Z SendDataTCPServer.js: TCP/IP server has received 5085180 bytes of data
,2015-11-20T13:59:25.025Z SendDataTCPServer.js: TCP/IP server has received 5098320 bytes of data
,2015-11-20T13:59:25.050Z SendDataTCPServer.js: TCP/IP server has received 5104890 bytes of data
,2015-11-20T13:59:25.063Z SendDataTCPServer.js: TCP/IP server has received 5107080 bytes of data
,2015-11-20T13:59:25.075Z SendDataTCPServer.js: TCP/IP server has received 5113650 bytes of data
,2015-11-20T13:59:25.113Z SendDataTCPServer.js: TCP/IP server has received 5115840 bytes of data
,2015-11-20T13:59:25.174Z SendDataTCPServer.js: TCP/IP server has received 5146500 bytes of data
,2015-11-20T13:59:25.213Z SendDataTCPServer.js: TCP/IP server has received 5159640 bytes of data
,2015-11-20T13:59:25.226Z SendDataTCPServer.js: TCP/IP server has received 5242860 bytes of data
,2015-11-20T13:59:25.238Z SendDataTCPServer.js: TCP/IP server has received 5245050 bytes of data
,2015-11-20T13:59:25.249Z SendDataTCPServer.js: TCP/IP server has received 5251620 bytes of data
,2015-11-20T13:59:25.263Z SendDataTCPServer.js: TCP/IP server has received 5262570 bytes of data
,2015-11-20T13:59:25.286Z SendDataTCPServer.js: TCP/IP server has received 5347980 bytes of data
,2015-11-20T13:59:25.347Z SendDataTCPServer.js: TCP/IP server has received 5354124 bytes of data
,2015-11-20T13:59:25.360Z SendDataTCPServer.js: TCP/IP server has received 5409300 bytes of data
,2015-11-20T13:59:25.374Z SendDataTCPServer.js: TCP/IP server has received 5411348 bytes of data
,2015-11-20T13:59:25.387Z SendDataTCPServer.js: TCP/IP server has received 5422440 bytes of data
,2015-11-20T13:59:25.400Z SendDataTCPServer.js: TCP/IP server has received 5435580 bytes of data
,2015-11-20T13:59:25.428Z SendDataTCPServer.js: TCP/IP server has received 5477190 bytes of data
,2015-11-20T13:59:25.439Z SendDataTCPServer.js: TCP/IP server has received 5494568 bytes of data
,2015-11-20T13:59:25.453Z SendDataTCPServer.js: TCP/IP server has received 5516610 bytes of data
,2015-11-20T13:59:25.500Z SendDataTCPServer.js: TCP/IP server has received 5529750 bytes of data
,2015-11-20T13:59:25.513Z SendDataTCPServer.js: TCP/IP server has received 5534130 bytes of data
,2015-11-20T13:59:25.537Z SendDataTCPServer.js: TCP/IP server has received 5538510 bytes of data
,2015-11-20T13:59:25.550Z SendDataTCPServer.js: TCP/IP server has received 5575740 bytes of data
,2015-11-20T13:59:25.604Z SendDataTCPServer.js: TCP/IP server has received 5584500 bytes of data
,2015-11-20T13:59:25.617Z SendDataTCPServer.js: TCP/IP server has received 5630490 bytes of data
,2015-11-20T13:59:25.738Z SendDataTCPServer.js: TCP/IP server has received 5637060 bytes of data
,2015-11-20T13:59:25.752Z SendDataTCPServer.js: TCP/IP server has received 5667720 bytes of data
,2015-11-20T13:59:25.814Z SendDataTCPServer.js: TCP/IP server has received 5726850 bytes of data
,2015-11-20T13:59:26.009Z SendDataTCPServer.js: TCP/IP server has received 5770650 bytes of data
,2015-11-20T13:59:26.084Z SendDataTCPServer.js: TCP/IP server has received 5772840 bytes of data
,2015-11-20T13:59:26.158Z SendDataTCPServer.js: TCP/IP server has received 5783790 bytes of data
,2015-11-20T13:59:26.170Z SendDataTCPServer.js: TCP/IP server has received 5792550 bytes of data
,2015-11-20T13:59:26.184Z SendDataTCPServer.js: TCP/IP server has received 5801310 bytes of data
,2015-11-20T13:59:26.269Z SendDataTCPServer.js: TCP/IP server has received 5818830 bytes of data
,2015-11-20T13:59:26.333Z SendDataTCPServer.js: TCP/IP server has received 5851740 bytes of data
,2015-11-20T13:59:26.347Z SendDataTCPServer.js: TCP/IP server has received 5867010 bytes of data
,2015-11-20T13:59:26.626Z SendDataTCPServer.js: TCP/IP server has received 5869200 bytes of data
,2015-11-20T13:59:26.639Z SendDataTCPServer.js: TCP/IP server has received 5945850 bytes of data
,2015-11-20T13:59:26.653Z SendDataTCPServer.js: TCP/IP server has received 5994030 bytes of data
,2015-11-20T13:59:26.666Z SendDataTCPServer.js: TCP/IP server has received 6007170 bytes of data
,2015-11-20T13:59:26.718Z SendDataTCPServer.js: TCP/IP server has received 6040020 bytes of data
,2015-11-20T13:59:26.731Z SendDataTCPServer.js: TCP/IP server has received 6077250 bytes of data
,2015-11-20T13:59:26.791Z SendDataTCPServer.js: TCP/IP server has received 6099008 bytes of data
,2015-11-20T13:59:26.805Z SendDataTCPServer.js: TCP/IP server has received 6112290 bytes of data
,2015-11-20T13:59:27.122Z SendDataTCPServer.js: TCP/IP server has received 6188940 bytes of data
,2015-11-20T13:59:27.246Z SendDataTCPServer.js: TCP/IP server has received 6210840 bytes of data
,2015-11-20T13:59:27.260Z SendDataTCPServer.js: TCP/IP server has received 6243690 bytes of data
,2015-11-20T13:59:27.322Z SendDataTCPServer.js: TCP/IP server has received 6252450 bytes of data
,2015-11-20T13:59:27.481Z SendDataTCPServer.js: TCP/IP server has received 6254640 bytes of data
,2015-11-20T13:59:27.494Z SendDataTCPServer.js: TCP/IP server has received 6278730 bytes of data
,2015-11-20T13:59:27.507Z SendDataTCPServer.js: TCP/IP server has received 6280920 bytes of data
,2015-11-20T13:59:27.520Z SendDataTCPServer.js: TCP/IP server has received 6324720 bytes of data
,2015-11-20T13:59:27.534Z SendDataTCPServer.js: TCP/IP server has received 6375090 bytes of data
,2015-11-20T13:59:27.549Z SendDataTCPServer.js: TCP/IP server has received 6440790 bytes of data
,2015-11-20T13:59:27.563Z SendDataTCPServer.js: TCP/IP server has received 6464880 bytes of data
,2015-11-20T13:59:27.577Z SendDataTCPServer.js: TCP/IP server has received 6484590 bytes of data
,2015-11-20T13:59:27.591Z SendDataTCPServer.js: TCP/IP server has received 6508680 bytes of data
,2015-11-20T13:59:27.603Z SendDataTCPServer.js: TCP/IP server has received 6528390 bytes of data
,2015-11-20T13:59:27.614Z SendDataTCPServer.js: TCP/IP server has received 6545910 bytes of data
,2015-11-20T13:59:27.627Z SendDataTCPServer.js: TCP/IP server has received 6570000 bytes of data
,2015-11-20T13:59:27.640Z SendDataTCPServer.js: TCP/IP server has received 6594090 bytes of data
,2015-11-20T13:59:27.652Z SendDataTCPServer.js: TCP/IP server has received 6626940 bytes of data
,2015-11-20T13:59:27.666Z SendDataTCPServer.js: TCP/IP server has received 6661980 bytes of data
,2015-11-20T13:59:27.680Z SendDataTCPServer.js: TCP/IP server has received 6703590 bytes of data
,2015-11-20T13:59:27.693Z SendDataTCPServer.js: TCP/IP server has received 6727680 bytes of data
,2015-11-20T13:59:27.706Z SendDataTCPServer.js: TCP/IP server has received 6762720 bytes of data
,2015-11-20T13:59:27.720Z SendDataTCPServer.js: TCP/IP server has received 6799950 bytes of data
,2015-11-20T13:59:27.734Z SendDataTCPServer.js: TCP/IP server has received 6839370 bytes of data
,2015-11-20T13:59:27.748Z SendDataTCPServer.js: TCP/IP server has received 6889598 bytes of data
,2015-11-20T13:59:27.763Z SendDataTCPServer.js: TCP/IP server has received 6946680 bytes of data
,2015-11-20T13:59:27.777Z SendDataTCPServer.js: TCP/IP server has received 7001430 bytes of data
,2015-11-20T13:59:27.790Z SendDataTCPServer.js: TCP/IP server has received 7040850 bytes of data
,2015-11-20T13:59:27.805Z SendDataTCPServer.js: TCP/IP server has received 7106550 bytes of data
,2015-11-20T13:59:27.819Z SendDataTCPServer.js: TCP/IP server has received 7152256 bytes of data
,2015-11-20T13:59:27.831Z SendDataTCPServer.js: TCP/IP server has received 7207148 bytes of data
,2015-11-20T13:59:27.845Z SendDataTCPServer.js: TCP/IP server has received 7270800 bytes of data
,2015-11-20T13:59:27.857Z SendDataTCPServer.js: TCP/IP server has received 7332120 bytes of data
,2015-11-20T13:59:27.872Z SendDataTCPServer.js: TCP/IP server has received 7378110 bytes of data
,2015-11-20T13:59:27.884Z SendDataTCPServer.js: TCP/IP server has received 7450380 bytes of data
,2015-11-20T13:59:27.898Z SendDataTCPServer.js: TCP/IP server has received 7491990 bytes of data
,2015-11-20T13:59:27.912Z SendDataTCPServer.js: TCP/IP server has received 7537980 bytes of data
,2015-11-20T13:59:27.925Z SendDataTCPServer.js: TCP/IP server has received 7608060 bytes of data
,2015-11-20T13:59:27.940Z SendDataTCPServer.js: TCP/IP server has received 7662810 bytes of data
,2015-11-20T13:59:27.955Z SendDataTCPServer.js: TCP/IP server has received 7737270 bytes of data
,2015-11-20T13:59:27.967Z SendDataTCPServer.js: TCP/IP server has received 7796400 bytes of data
,2015-11-20T13:59:27.981Z SendDataTCPServer.js: TCP/IP server has received 7851150 bytes of data
,2015-11-20T13:59:27.995Z SendDataTCPServer.js: TCP/IP server has received 7897140 bytes of data
,2015-11-20T13:59:28.010Z SendDataTCPServer.js: TCP/IP server has received 7954080 bytes of data
,2015-11-20T13:59:28.021Z SendDataTCPServer.js: TCP/IP server has received 8000070 bytes of data
,2015-11-20T13:59:28.035Z SendDataTCPServer.js: TCP/IP server has received 8052630 bytes of data
,2015-11-20T13:59:28.047Z SendDataTCPServer.js: TCP/IP server has received 8109570 bytes of data
,2015-11-20T13:59:28.061Z SendDataTCPServer.js: TCP/IP server has received 8157750 bytes of data
,2015-11-20T13:59:28.075Z SendDataTCPServer.js: TCP/IP server has received 8223450 bytes of data
,2015-11-20T13:59:28.089Z SendDataTCPServer.js: TCP/IP server has received 8282438 bytes of data
,2015-11-20T13:59:28.103Z SendDataTCPServer.js: TCP/IP server has received 8350470 bytes of data
,2015-11-20T13:59:28.117Z SendDataTCPServer.js: TCP/IP server has received 8418360 bytes of data
,2015-11-20T13:59:28.132Z SendDataTCPServer.js: TCP/IP server has received 8479680 bytes of data
,2015-11-20T13:59:28.147Z SendDataTCPServer.js: TCP/IP server has received 8543190 bytes of data
,2015-11-20T13:59:28.159Z SendDataTCPServer.js: TCP/IP server has received 8604510 bytes of data
,2015-11-20T13:59:28.175Z SendDataTCPServer.js: TCP/IP server has received 8668020 bytes of data
,2015-11-20T13:59:28.189Z SendDataTCPServer.js: TCP/IP server has received 8733720 bytes of data
,2015-11-20T13:59:28.203Z SendDataTCPServer.js: TCP/IP server has received 8784090 bytes of data
,2015-11-20T13:59:28.216Z SendDataTCPServer.js: TCP/IP server has received 8827890 bytes of data
,2015-11-20T13:59:28.231Z SendDataTCPServer.js: TCP/IP server has received 8884830 bytes of data
,2015-11-20T13:59:28.245Z SendDataTCPServer.js: TCP/IP server has received 8954626 bytes of data
,2015-11-20T13:59:28.259Z SendDataTCPServer.js: TCP/IP server has received 9005280 bytes of data
,2015-11-20T13:59:28.271Z SendDataTCPServer.js: TCP/IP server has received 9062220 bytes of data
,2015-11-20T13:59:28.284Z SendDataTCPServer.js: TCP/IP server has received 9116970 bytes of data
,2015-11-20T13:59:28.297Z SendDataTCPServer.js: TCP/IP server has received 9178290 bytes of data
,2015-11-20T13:59:28.314Z SendDataTCPServer.js: TCP/IP server has received 9261510 bytes of data
,2015-11-20T13:59:28.327Z SendDataTCPServer.js: TCP/IP server has received 9325020 bytes of data
,2015-11-20T13:59:28.343Z SendDataTCPServer.js: TCP/IP server has received 9410288 bytes of data
,2015-11-20T13:59:28.356Z SendDataTCPServer.js: TCP/IP server has received 9482700 bytes of data
,2015-11-20T13:59:28.370Z SendDataTCPServer.js: TCP/IP server has received 9508838 bytes of data
,2015-11-20T13:59:28.383Z SendDataTCPServer.js: TCP/IP server has received 9576870 bytes of data
,2015-11-20T13:59:28.397Z SendDataTCPServer.js: TCP/IP server has received 9651330 bytes of data
,2015-11-20T13:59:28.411Z SendDataTCPServer.js: TCP/IP server has received 9706080 bytes of data
,2015-11-20T13:59:28.425Z SendDataTCPServer.js: TCP/IP server has received 9708270 bytes of data
,2015-11-20T13:59:28.437Z SendDataTCPServer.js: TCP/IP server has received 9752070 bytes of data
,2015-11-20T13:59:28.451Z SendDataTCPServer.js: TCP/IP server has received 9776160 bytes of data
,2015-11-20T13:59:28.464Z SendDataTCPServer.js: TCP/IP server has received 9800250 bytes of data
,2015-11-20T13:59:28.477Z SendDataTCPServer.js: TCP/IP server has received 9802440 bytes of data
,2015-11-20T13:59:28.516Z SendDataTCPServer.js: TCP/IP server has received 9841860 bytes of data
,2015-11-20T13:59:28.527Z SendDataTCPServer.js: TCP/IP server has received 9848430 bytes of data
,2015-11-20T13:59:28.561Z SendDataTCPServer.js: TCP/IP server has received 9859380 bytes of data
,2015-11-20T13:59:28.574Z SendDataTCPServer.js: TCP/IP server has received 9872520 bytes of data
,2015-11-20T13:59:28.722Z SendDataTCPServer.js: TCP/IP server has received 9905370 bytes of data
,2015-11-20T13:59:28.736Z SendDataTCPServer.js: TCP/IP server has received 9918510 bytes of data
,2015-11-20T13:59:28.761Z SendDataTCPServer.js: TCP/IP server has received 9933840 bytes of data
,2015-11-20T13:59:28.846Z SendDataTCPServer.js: TCP/IP server has received 9942600 bytes of data
,2015-11-20T13:59:28.893Z SendDataTCPServer.js: TCP/IP server has received 9951360 bytes of data
,2015-11-20T13:59:28.918Z SendDataTCPServer.js: TCP/IP server has received 9962310 bytes of data
,2015-11-20T13:59:29.004Z SendDataTCPServer.js: TCP/IP server has received 9990780 bytes of data
,2015-11-20T13:59:29.018Z SendDataTCPServer.js: TCP/IP server has received 9992970 bytes of data
,2015-11-20T13:59:29.116Z SendDataTCPServer.js: TCP/IP server has received 9997350 bytes of data
,2015-11-20T13:59:29.277Z SendDataTCPServer.js: TCP/IP server has received 10000002 bytes of data
,2015-11-20 14:59:30.218 ThaliTest[860:966482] server session: not connected Apple-Iphone5s-1_PT9513
,2015-11-20 14:59:31.444 ThaliTest[860:964797] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:59:31.444 ThaliTest[860:964797] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:59:31.444 ThaliTest[860:964797] cli,ent session: onLinkFailure: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:59:31.445 ThaliTest[860:964797] client session: disconnect
2015-11-20 14:59:31.445 ThaliTest[860:964797] client session: stateChange:1->0 Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11,-20 14:59:31.445 ThaliTest[860:964797] client session: fireConnectCallback: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:59:31.445 ThaliTest[860:964797] jxcore: connect: fail: Peer disconnected
2015-11-20T13:59:31.445Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-20T13:59:31.445Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-20T13:59:31.445Z SendDataConnector.js: tryAgain afer: 1000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20T13:59:32.454Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20T13:59:32.454Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:59:33.466 ThaliTest[860:965001] jxcore: disconnect
2015-11-20 14:59:33.466 ThaliTest[860:965001] jxcore: disconnect: fail
2015-11-20T13:59:33.466Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9513.+kbAXQ==,
2015-11-20T13:59:33.467Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT9513.+kbAXQ== with availability status: true
2015-11-20T13:59:33.467Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
20,15-11-20T13:59:33.467Z SendDataConnector.js: do connect now
2015-11-20 14:59:33.467 ThaliTest[860:965001] jxcore: connect Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 14:59:33.467 ThaliTest[860:965001] client: connect: unreachable Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20 14:59:33.468 ThaliTest[860:965001] jxcore: connect: fail: Peer unreachable
,2015-11-20T13:59:33.468Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-20T13:59:33.468Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-11-20T13:59:33.469Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T13:59:33.469Z SendDataConnector.js: Stop data retrieving timer
,2015-11-20 14:59:33.470 ThaliTest[860:965001] jxcore: disconnect
2015-11-20 14:59:33.470 ThaliTest[860:965001] jxcore: disconnect: fail
2015-11-20T13:59:33.470Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9513.+kbAXQ==
---- round done--------
,device[2]: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:59:33.473Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:59:33.473Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T13:59:33.473Z SendDataConnector.js: do connect now
,2015-11-20 14:59:33.474 ThaliTest[860:965001] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:33.474 ThaliTest[860:965001] client session: connect
2015-11-20 14:59:33.474 ThaliTest[860:965001] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:36.613 ThaliTest[860:966536] client session: connected
2015-11-20 14:59:36.613 ThaliTest[860:966536] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:36.616 ThaliTest[860:966478] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:36.616 ThaliTest[860:966478] jxcore: connect: success
2015-11-20T13:59:36.617Z SendDataConnector.js: CLIENT connected to 55899, error: null
2015-11-20T13:59:36.617Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:59:36.620 ThaliTest[860:964797] client: relay established
2015-11-20 14:59:36.620 ThaliTest[860:964797] client: new accepted socket: 0x185bfdf0
,2015-11-20T13:59:36.631Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20 14:59:36.934 ThaliTest[860:964797] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T13:59:40.678Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 14:59:45.271 ThaliTest[860:964797] multipeer session: restart
,2015-11-20 14:59:47.218 ThaliTest[860:964797] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:47.219 ThaliTest[860:964797] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::94d3:cff:fef6:905b
,2015-11-20T13:59:50.679Z SendDataConnector.js: Receiving data timeout now
2015-11-20T13:59:50.679Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T13:59:50.680Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T13:59:50.680Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 14:59:50.680 ThaliTest[860:964797] client: socket closed
,2015-11-20 14:59:50.681 ThaliTest[860:964797] client relay: socket disconnected
2015-11-20 14:59:50.681 ThaliTest[860:964797] client relay: 0x185bfdf0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" Use,rInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-20 14:59:50.681 ThaliTest[860:964797] client session: socket closed: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:50.681 ThaliTest[860:964797] client session: onLinkFailure: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:50.681 ThaliTest[860:964797] client session: disconnect
,2015-11-20 14:59:50.681 ThaliTest[860:964797] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:50.683 ThaliTest[860:964797] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T13:59:51.695Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T13:59:51.695Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:52.699 ThaliTest[860:965001] jxcore: disconnect
2015-11-20 14:59:52.699 ThaliTest[860:965001] jxcore: disconnect: fail
2015-11-20T13:59:52.699Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T13:59:52.699Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT738.lFO7fw== with availability status: true
2015-11-20T13:59:52.699Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T13:59:52.699Z SendDataConnector.js: do connect now
,2015-11-20 14:59:52.700 ThaliTest[860:965001] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 14:59:52.700 ThaliTest[860:965001] client session: connect
,2015-11-20 14:59:52.700 ThaliTest[860:965001] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:55.445 ThaliTest[860:966477] client session: connected
2015-11-20 14:59:55.445 ThaliTest[860:966477] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:55.447 ThaliTest[860:966477] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 14:59:55.447 ThaliTest[860:966477] jxcore: connect: success
2015-11-20T13:59:55.447Z SendDataConnector.js: CLIENT connected to 55904, error: null
2015-11-20T13:59:55.447Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 14:59:55.448 ThaliTest[860:964797] client: relay established
2015-11-20 14:59:55.449 ThaliTest[860:964797] client: new accepted socket: 0x18648610
,2015-11-20T13:59:55.461Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T13:59:59.579Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:01.923 ThaliTest[860:964797] client: lost peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
2015-11-20 15:00:01.923 ThaliTest[860:964797] client session: onPeerLost: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-20T14:00:09.591Z SendDataConnector.js: Receiving data timeout now
2015-11-20T14:00:09.592Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T14:00:09.592Z SendDataConnector.js: tryAgain afer: 1000 ms.
2015-11-20T14:00:09.592Z SendDataConnector.js: ----------------- closeClientSocket
2015-11-20 15:00:09.592 ThaliTest[860:964797] client: socket closed
2015-11-20 15:00:09.593 ThaliTe,st[860:964797] client relay: socket disconnected
2015-11-20 15:00:09.593 ThaliTest[860:964797] client relay: 0x18648610 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=S,ocket closed by remote peer} 
2015-11-20 15:00:09.593 ThaliTest[860:964797] client session: socket closed: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:09.593 ThaliTest[860:964797] client session: onLinkFailure: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:09.593 ThaliTest[860:964797] client session: disconnect
2015-11-20 15:00:09.593 ThaliTest[860:964797] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:09.596 ThaliTest[860:964797] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:10.597Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:10.597Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:11.599 ThaliTest[860:965001] jxcore: disconnect
2015-11-20 15:00:11.599 ThaliTest[860:965001] jxcore: disconnect: fail
2015-11-20T14:00:11.599Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T14:00:11.599Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT738.lFO7fw== with availability status: true
2015-11-20T14:00:11.599Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:11.599Z SendDataConnector.js: do connect now
2015-11-20 15:00:11.600 ThaliTest[860:965001] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:11.600 ThaliTest[860:965001] client session: connect
2015-11-20 15:00:11.600 ThaliTest[860:965001] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:13.039 ThaliTest[860:964797] multipeer session: restart
,2015-11-20 15:00:13.048 ThaliTest[860:964797] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:13.659 ThaliTest[860:964797] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9513.+kbAXQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-20 15:00:14.741 ThaliTest[860:966556] client session: connected
2015-11-20 15:00:14.741 ThaliTest[860:966556] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:14.742 ThaliTest[860:966556] client session: fireConnec,tCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:14.742 ThaliTest[860:966556] jxcore: connect: success
2015-11-20T14:00:14.743Z SendDataConnector.js: CLIENT connected to 55907, error: null
2015-11-20T14:00:14.744Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 15:00:14.745 ThaliTest[860:964797] client: relay established
2015-11-20 15:00:14.745 ThaliTest[860:964797] client: new accepted socket: 0x185bc0e0
,2015-11-20T14:00:14.757Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T14:00:18.902Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:28.911Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T14:00:28.911Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T14:00:28.911Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T14:00:28.912Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20T14:00:29.912Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T14:00:29.912Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:30.502 ThaliTest[860:964797] client: socket closed
2015-11-20 15:00:30.502 ThaliTest[860:964797] client relay: socket disconnected
2015-11-20 15:00:30.502 ThaliTest[860:964797] client relay: 0x185bc0e0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 15:00:30.502 ThaliTest[860:964797] client session: socket closed: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:30.502 ThaliTest[860:964797] client session: onLinkFailure: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:30.502 ThaliTest[860:964797] client session: disconnect
2015-11-20 15:00:30.502 ThaliTest[860:964797] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:30.505 ThaliTest[860:964797] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:30.920 ThaliTest[860:965001] jxcore: disconnect
,2015-11-20 15:00:30.920 ThaliTest[860:965001] jxcore: disconnect: fail
,2015-11-20T14:00:30.920Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T14:00:30.920Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT738.lFO7fw== with availability status: tr,ue
2015-11-20T14:00:30.920Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:30.921Z SendDataConnector.js: do connect now
,2015-11-20 15:00:30.921 ThaliTest[860:965001] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:30.921 ThaliTest[860:965001] client session: connect
,2015-11-20 15:00:30.921 ThaliTest[860:965001] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:33.623 ThaliTest[860:966677] client session: connected
2015-11-20 15:00:33.623 ThaliTest[860:966677] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:33.657 ThaliTest[860:966557] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:33.657 ThaliTest[860:966557] jxcore: connect: success
,2015-11-20T14:00:33.658Z SendDataConnector.js: CLIENT connected to 55910, error: null
,2015-11-20T14:00:33.658Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 15:00:33.659 ThaliTest[860:964797] client: relay established
2015-11-20 15:00:33.659 ThaliTest[860:964797] client: new accepted socket: 0x186e51c0
,2015-11-20T14:00:33.672Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T14:00:37.842Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:43.071 ThaliTest[860:964797] multipeer session: restart
,2015-11-20 15:00:45.267 ThaliTest[860:964797] client: found peer: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:45.267 ThaliTest[860:964797] client: found peer: Apple-Iphone5s-1_PT9513.+kbAXQ==
,2015-11-20T14:00:47.846Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T14:00:47.846Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T14:00:47.847Z SendDataConnector.js: tryAgain afer: 1000 ms.
,2015-11-20T14:00:47.847Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-20 15:00:48.366 ThaliTest[860:964797] client: socket closed
2015-11-20 15:00:48.366 ThaliTest[860:964797] client relay: socket disconnected
2015-11-20 15:00:48.366 ThaliTest[860:964797] client relay: 0x186e51c0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-20 15:00:48.366 ThaliTest[860:964797] client session: socket closed: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:48.366 ThaliTest[860:964797] client session: onLinkFailure: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:48.366 ThaliTest[860:964797] client session: disconnect
2015-11-20 15:00:48.366 ThaliTest[860:964797] client session: stateChange:2->0 Apple-Ipho,ne5-1_PT738.lFO7fw==
,2015-11-20 15:00:48.370 ThaliTest[860:964797] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:00:48.856Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T14:00:48.856Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:49.865 ThaliTest[860:965001] jxcore: disconnect
2015-11-20 15:00:49.866 ThaliTest[860:965001] jxcore: disconnect: fail
2015-11-20T14:00:49.866Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20T14:00:49.866Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT738.lFO7fw== with availability status: true
2015-11-20T14:00:49.866Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT738.lFO7fw==
2015-11-,20T14:00:49.866Z SendDataConnector.js: do connect now
,2015-11-20 15:00:49.867 ThaliTest[860:965001] jxcore: connect Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:49.867 ThaliTest[860:965001] client session: connect
2015-11-20 15:00:49.867 ThaliTest[860:965001] client session: stateChange:0->1 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:53.199 ThaliTest[860:966710] client session: connected
2015-11-20 15:00:53.199 ThaliTest[860:966710] client session: stateChange:1->2 Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:00:53.201 ThaliTest[860:966711] client session: fireConnectCallback: Apple-Iphone5-1_PT738.lFO7fw==
2015-11-20 15:00:53.201 ThaliTest[860:966711] jxcore: connect: success
,2015-11-20T14:00:53.201Z SendDataConnector.js: CLIENT connected to 55914, error: null
,2015-11-20T14:00:53.202Z SendDataConnector.js: CLIENT starting client 
,2015-11-20 15:00:53.203 ThaliTest[860:964797] client: relay established
2015-11-20 15:00:53.203 ThaliTest[860:964797] client: new accepted socket: 0x1839ca40
,2015-11-20T14:00:53.216Z SendDataConnector.js: CLIENT now sending 10000000 bytes of data
,2015-11-20T14:00:57.334Z SendDataConnector.js: resetDataTimeout called with peer Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20T14:01:07.343Z SendDataConnector.js: Receiving data timeout now
,2015-11-20T14:01:07.343Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-20T14:01:07.344Z SendDataConnector.js: CLIENT Stop now
,2015-11-20T14:01:07.344Z SendDataConnector.js: Stop data retrieving timer
,2015-11-20 15:01:07.345 ThaliTest[860:965001] jxcore: disconnect
,2015-11-20 15:01:07.345 ThaliTest[860:965001] client session: disconnectFromPeer: Apple-Iphone5-1_PT738.lFO7fw==
,2015-11-20 15:01:07.345 ThaliTest[860:965001] client session: disconnect
2015-11-20 15:01:07.345 ThaliTest[860:965001] client session: stateChange:2->0 Apple-Iphone5-1_PT738.lFO7fw==
,Assertion failed: (_outputStream != nil), function -[THEMultipeerSocketRelay writeOutputStream], file /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerSocketRelay.m, line 170.
,Process 860 stopped
* thread #1: tid = 0xeb8bd, 0x3732cd24 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x3732cd24 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x3732cd24 <+8>:  blo    0x3732cd3c                ; <+32>
    0x3732cd28 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x3732cd2c <+16>: ldr    r12, [pc, r12]
    0x3732cd30 <+20>: b      0x3732cd38                ; <+28>
,* thread #1: tid = 0xeb8bd, 0x3732cd24 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x3732cd24 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x373ccb5a libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x372c4f50 libsystem_c.dylib`abort + 108
    frame #3: 0x372a46de libsystem_c.dylib`__assert_rtn + 302
    frame #4: 0x00072030 ThaliTest`-[THEMultipeerSocketRelay writeOutputStream] + 252
    frame #5: 0x00072b8c ThaliTest`-[THEMultipeerSocketRelay stream:handleEvent:] + 868
    frame #6: 0x251d4a4a CoreFoundation`<redacted> + 146
    frame #7: 0x251df198 CoreFoundation`<redacted> + 208
    frame #8: 0x251d46d8 CoreFoundation`<redacted> + 320
    frame #9: 0x25210f34 CoreFoundation`<redacted> + 432
    frame #10: 0x25225826 CoreFoundation`<redacted> + 14
    frame #11: 0x252253a8 CoreFoundation`<redacted> + 344
    frame #12: 0x2522377e CoreFoundation`<redacted> + 806
    frame #13: 0x251761e8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #14: 0x25175fdc CoreFoundation`CFRunLoopRunInMode + 108
    frame #15: 0x2e251af8 GraphicsServices`GSEventRunModal + 160
    frame #16: 0x293db17c UIKit`UIApplicationMain + 144
    frame #17: 0x0005c692 ThaliTest`main + 50

```
