#### Test 513350289b9c5d6_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350289b9c5d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/66C25260-858C-4C83-BC30-DC3967716E14/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/66C25260-858C-4C83-BC30-DC3967716E14/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350289b9c5d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350289b9c5d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A2CD7345-D9A3-42F8-BA92-6A66406E5A9E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52795"
,(lldb)     command script import "/tmp/66C25260-858C-4C83-BC30-DC3967716E14/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 12:30:01.306 ThaliTest[1058:1403090] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1ADE63F4-B1EF-41C3-B786-CD263C723CD2/Library/Cookies/Cookies.binarycookies
,2015-11-23 12:30:01.600 ThaliTest[1058:1403090] Apache Cordova native platform version 3.9.2 is starting.
2015-11-23 12:30:01.600 ThaliTest[1058:1403090] Multi-tasking -> Device: YES, App: YES
,2015-11-23 12:30:01.607 ThaliTest[1058:1403090] Unlimited access to network resources
,2015-11-23 12:30:01.613 ThaliTest[1058:1403090] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 12:30:05.799 ThaliTest[1058:1403090] Resetting plugins due to page load.
,2015-11-23 12:30:07.099 ThaliTest[1058:1403090] Finished load of: file:///var/mobile/Containers/Bundle/Application/A2CD7345-D9A3-42F8-BA92-6A66406E5A9E/ThaliTest.app/www/index.html
,2015-11-23 12:30:07.245 ThaliTest[1058:1403090] JXcore Cordova plugin initializing
,2015-11-23 12:30:07.246 ThaliTest[1058:1403258] JXcore instance initializing
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
Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,my name is : Apple-IpadAir2-1_PT6529
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
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 ,is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
,-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
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
-iface: IPv6 is internal : false, has ip: fe80::c4ef:94ff:fe2e:4182
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 57051
,2015-11-23 12:36:43.132 ThaliTest[1058:1403258] jxcore: startBroadcasting
,2015-11-23 12:36:43.138 ThaliTest[1058:1403258] server: starting Apple-IpadAir2-1_PT6529.Z02MaA==
,2015-11-23 12:36:43.139 ThaliTest[1058:1403258] multipeer session: start timer: 0x16f7e8c0
2015-11-23 12:36:43.139 ThaliTest[1058:1403258] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6529
,2015-11-23 12:36:43.140 ThaliTest[1058:1403258] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-23T11:36:43.143Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-23 12:36:43.359 ThaliTest[1058:1403090] client: found peer: Apple-Iphone6-1_PT7664.8o3jhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7664.8o3jhw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23T11:36:43.362Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23T11:36:43.365Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23T11:36:43.365Z SendDataConnector.js: do connect now
,2015-11-23 12:36:43.365 ThaliTest[1058:1403258] jxcore: connect Apple-Iphone6-1_PT7664.8o3jhw==
2015-11-23 12:36:43.366 ThaliTest[1058:1403258] client session: connect
2015-11-23 12:36:43.366 ThaliTest[1058:1403258] client session: stateChange:0->1 Apple,-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:43.829 ThaliTest[1058:1403090] client: found peer: Apple-Iphone5s-1_PT8005.g0Za/g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8005.g0Za/g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-23 12:36:44.641 ThaliTest[1058:1403090] client: found peer: Apple-Iphone5-1_PT142.u6yj7g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT142.u6yj7g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 12:36:46.320 ThaliTest[1058:1404097] client session: connected
2015-11-23 12:36:46.320 ThaliTest[1058:1404097] client session: stateChange:1->2 Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:46.327 ThaliTest[1058:1404097] client session: fireConnectCallback: Apple-Iphone6-1_PT7664.8o3jhw==
2015-11-23 12:36:46.327 ThaliTest[1058:1404097] jxcore: connect: success
,2015-11-23T11:36:46.328Z SendDataConnector.js: CLIENT connected to 57054, error: null
2015-11-23T11:36:46.328Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 12:36:46.329 ThaliTest[1058:1403090] client: relay established
2015-11-23 12:36:46.329 ThaliTest[1058:1403090] client: new accepted socket: 0x16d91e10
,2015-11-23T11:36:46.342Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T11:36:46.421Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-23T11:36:46.556Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-23T11:36:46.556Z SendDataConnector.js: got all data for this round
,2015-11-23T11:36:46.557Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:36:46.558Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 12:36:46.558 ThaliTest[1058:1403258] jxcore: disconnect
2015-11-23 12:36:46.559 ThaliTest[1058:1403258] client session: disconnectFromPeer: Apple-Iphone6-1_PT7664.8o3jhw==
2015-11-23 12:36:46.559 ThaliTest[1058:1403258] client session: disconnect
2015-11-23 12:36:46.559 ThaliTest[1058:1403258] client session: stateChange:2->0 Apple-Iphone6-1_PT7664.8o3jhw==
,2015-11-23 12:36:46.563 ThaliTest[1058:1403258] jxcore: disconnect: success
2015-11-23T11:36:46.563Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7664.8o3jhw==
---- round done--------
device[2]: Apple-Iphone5s-1_PT8005.g0Za/g==
2015-11-23T11:36:46.564Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8005.g0Za/g==
2015-11-23T11:36:46.564Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8005.g0Za/g==
2015-11-23T11:36:46.564Z SendDataConnector.js: do connect now
,2015-11-23 12:36:46.565 ThaliTest[1058:1403258] jxcore: connect Apple-Iphone5s-1_PT8005.g0Za/g==
2015-11-23 12:36:46.566 ThaliTest[1058:1403258] client session: connect
2015-11-23 12:36:46.566 ThaliTest[1058:1403258] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23 12:36:46.918 ThaliTest[1058:1403090] multipeer session: reset timer
,2015-11-23 12:36:46.918 ThaliTest[1058:1403090] multipeer session: stop timer
2015-11-23 12:36:46.919 ThaliTest[1058:1403090] multipeer session: start timer: 0x16f7e8c0
2015-11-23 12:36:46.919 ThaliTest[1058:1403090] server session: connect
2015-11-23 1,2:36:46.919 ThaliTest[1058:1403090] server session: stateChange:0->1 Apple-Iphone6-1_PT7664
,2015-11-23 12:36:46.924 ThaliTest[1058:1403090] server: accepting invitation Apple-Iphone6-1_PT7664
,2015-11-23 12:36:48.135 ThaliTest[1058:1403090] multipeer session: reset timer
,2015-11-23 12:36:48.136 ThaliTest[1058:1403090] multipeer session: stop timer
2015-11-23 12:36:48.136 ThaliTest[1058:1403090] multipeer session: start timer: 0x16f7e8c0
2015-11-23 12:36:48.136 ThaliTest[1058:1403090] server session: connect
2015-11-23 12:36:48.136 ThaliTest[1058:1403090] server session: stateChange:0->1 Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:48.139 ThaliTest[1058:1403090] server: accepting invitation Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:49.668 ThaliTest[1058:1404096] client session: connected
2015-11-23 12:36:49.668 ThaliTest[1058:1404096] client session: stateChange:1->2 Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23 12:36:49.670 ThaliTest[1058:1404096] client session: fireConnectCallback: Apple-Iphone5s-1_PT8005.g0Za/g==
2015-11-23 12:36:49.670 ThaliTest[1058:1404096] jxcore: connect: success
2015-11-23T11:36:49.670Z SendDataConnector.js: CLIENT connected to 57058, error: null
,2015-11-23T11:36:49.671Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 12:36:49.671 ThaliTest[1058:1403090] client: relay established
2015-11-23 12:36:49.672 ThaliTest[1058:1403090] client: new accepted socket: 0x16d8f2b0
,2015-11-23T11:36:49.685Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23 12:36:50.085 ThaliTest[1058:1403090] multipeer session: reset timer
2015-11-23 12:36:50.085 ThaliTest[1058:1403090] multipeer session: stop timer
2015-11-23 12:36:50.085 ThaliTest[1058:1403090] multipeer session: start timer: 0x16f7e8c0
2015-11-23 12:36:50.085 ThaliTest[1058:1403090] server session: connect
2015-11-23 12:36:50.085 ThaliTest[1058:1403090] server session: stateChange:0->1 Apple-Iphone5-1_PT142
,2015-11-23 12:36:50.087 ThaliTest[1058:1403090] server: accepting invitation Apple-Iphone5-1_PT142
,2015-11-23 12:36:50.097 ThaliTest[1058:1404109] server session: connected
2015-11-23 12:36:50.097 ThaliTest[1058:1404109] server session: stateChange:1->2 Apple-Iphone6-1_PT7664
,2015-11-23 12:36:50.131 ThaliTest[1058:1403090] server relay: connected (to port: 57051)
,2015-11-23T11:36:50.134Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T11:36:50.208Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-11-23T11:36:50.222Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-11-23T11:36:50.585Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-11-23T11:36:50.600Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 12:36:50.654 ThaliTest[1058:1404120] server session: not connected Apple-Iphone6-1_PT7664
,2015-11-23T11:36:50.712Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-23T11:36:50.725Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-23T11:36:51.188Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-23T11:36:51.738Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-23T11:36:51.738Z SendDataConnector.js: got all data for this round
2015-11-23T11:36:51.738Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:36:51.739Z SendDataCo,nnector.js: CLIENT closeClientSocket
,2015-11-23 12:36:51.739 ThaliTest[1058:1403258] jxcore: disconnect
,2015-11-23 12:36:51.739 ThaliTest[1058:1403258] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8005.g0Za/g==
2015-11-23 12:36:51.740 ThaliTest[1058:1403258] client session: disconnect
2015-11-23 12:36:51.740 ThaliTest[1058:1403258] client session: stateChange:2->0 Apple-Iphone5s-1_PT8005.g0Za/g==
,2015-11-23 12:36:51.743 ThaliTest[1058:1403258] jxcore: disconnect: success
2015-11-23T11:36:51.744Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8005.g0Za/g==
---- round done--------
device[3]: Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23T11:36:51.744Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT142.u6yj7g==
,2015-11-23T11:36:51.744Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT142.u6yj7g==
,2015-11-23T11:36:51.745Z SendDataConnector.js: do connect now
2015-11-23 12:36:51.745 ThaliTest[1058:1403258] jxcore: connect Apple-Iphone5-1_PT142.u6yj7g==
2015-11-23 12:36:51.745 ThaliTest[1058:1403258] client session: connect
2015-11-23 12:36:51.746 ThaliTest[1058:1403258] client session: stateChange:0->1 Apple-Iphone5-1_PT142.u6yj7g==
,2015-11-23 12:36:51.757 ThaliTest[1058:1404101] server session: connected
,2015-11-23 12:36:51.757 ThaliTest[1058:1404101] server session: stateChange:1->2 Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:51.762 ThaliTest[1058:1403090] server relay: connected (to port: 57051)
,2015-11-23T11:36:51.767Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T11:36:52.218Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-11-23T11:36:52.233Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 12:36:52.261 ThaliTest[1058:1404096] server session: not connected Apple-Iphone5s-1_PT8005
,2015-11-23 12:36:52.754 ThaliTest[1058:1404096] server session: connected
2015-11-23 12:36:52.754 ThaliTest[1058:1404096] server session: stateChange:1->2 Apple-Iphone5-1_PT142
,2015-11-23 12:36:52.757 ThaliTest[1058:1403090] server relay: connected (to port: 57051)
,2015-11-23T11:36:52.765Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T11:36:53.856Z SendDataTCPServer.js: TCP/IP server has received 992 bytes of data
,2015-11-23T11:36:53.868Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-11-23T11:36:54.342Z SendDataTCPServer.js: TCP/IP server has received 63488 bytes of data
,2015-11-23T11:36:54.353Z SendDataTCPServer.js: TCP/IP server has received 66464 bytes of data
,2015-11-23T11:36:54.366Z SendDataTCPServer.js: TCP/IP server has received 78368 bytes of data
,2015-11-23T11:36:54.378Z SendDataTCPServer.js: TCP/IP server has received 88288 bytes of data
,2015-11-23T11:36:54.391Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 12:36:55.431 ThaliTest[1058:1404121] server session: not connected Apple-Iphone5-1_PT142
,2015-11-23 12:36:58.509 ThaliTest[1058:1404096] client session: connected
2015-11-23 12:36:58.509 ThaliTest[1058:1404096] client session: stateChange:1->2 Apple-Iphone5-1_PT142.u6yj7g==
,2015-11-23 12:36:58.512 ThaliTest[1058:1404121] client session: fireConnectCallback: Apple-Iphone5-1_PT142.u6yj7g==
,2015-11-23 12:36:58.512 ThaliTest[1058:1404121] jxcore: connect: success
,2015-11-23T11:36:58.513Z SendDataConnector.js: CLIENT connected to 57064, error: null
2015-11-23T11:36:58.513Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 12:36:58.514 ThaliTest[1058:1403090] client: relay established
2015-11-23 12:36:58.514 ThaliTest[1058:1403090] client: new accepted socket: 0x16d962e0
,2015-11-23T11:36:58.527Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T11:37:00.481Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-23T11:37:00.494Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-23T11:37:00.495Z SendDataConnector.js: got all data for this round
,2015-11-23T11:37:00.495Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:37:00.495Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 12:37:00.496 ThaliTest[1058:1403258] jxcore: disconnect
,2015-11-23 12:37:00.496 ThaliTest[1058:1403258] client session: disconnectFromPeer: Apple-Iphone5-1_PT142.u6yj7g==
,2015-11-23 12:37:00.496 ThaliTest[1058:1403258] client session: disconnect
2015-11-23 12:37:00.497 ThaliTest[1058:1403258] client session: stateChange:2->0 Apple-Iphone5-1_PT142.u6yj7g==
,2015-11-23 12:37:00.501 ThaliTest[1058:1403258] jxcore: disconnect: success
2015-11-23T11:37:00.501Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT142.u6yj7g==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT6529","time":17374,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7664.8o3jhw==","time":3192,"result":"OK","connections":1},{"nam,e":"Apple-Iphone5s-1_PT8005.g0Za/g==","time":5174,"result":"OK","connections":1},{"name":"Apple-Iphone5-1_PT142.u6yj7g==","time":8751,"result":"OK","connections":1}]}
sendList : 100% : 8751 ms, 99% : 8751 ms, 95 : 8751 ms, 90% : 8751 ms.
Result count 3, ,range 3192 ms to  8751 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-23T11:37:00.505Z SendDataConnector.js: CLIENT Stop now
2015-11-23T11:37:00.506Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-23 12:37:00.946 ThaliTest[1058:1403258] jxcore: stopBroadcasting
,2015-11-23 12:37:00.946 ThaliTest[1058:1403258] THEMultipeerSession stopping peer
,2015-11-23 12:37:00.946 ThaliTest[1058:1403258] multipeer session: stop timer
,2015-11-23 12:37:00.946 ThaliTest[1058:1403258] server session: disconnect
,2015-11-23 12:37:00.947 ThaliTest[1058:1403258] server session: stateChange:2->0 Apple-Iphone5s-1_PT8005
2015-11-23 12:37:00.949 ThaliTest[1058:1403258] server session: disconnect
2015-11-23 12:37:00.949 ThaliTest[1058:1403258] server session: stateChange:2->0 Apple-Iphone5-1_PT142
,2015-11-23 12:37:01.010 ThaliTest[1058:1403258] server session: disconnect
2015-11-23 12:37:01.010 ThaliTest[1058:1403258] server session: stateChange:2->0 Apple-Iphone6-1_PT7664
,2015-11-23 12:37:01.012 ThaliTest[1058:1403258] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-23T11:37:01.027Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T11:37:01.027Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T11:37:01.028Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-23T11:37:01.028Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":3192,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8005.g0Za/g==\",\"time\":5174,\",result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":8751,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT8005.g0Za/g==\",\"time\":2857,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":2877,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":3192,\"result\":\"OK\",\"connections\":1},{\"na,me\":\"Apple-Iphone5s-1_PT8005.g0Za/g==\",\"time\":3523,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":3655,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":3704,\"result,\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT7664.8o3jhw==\",\"time\":3780,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6529.Z02MaA==\",\"time\":4200,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6,529.Z02MaA==\",\"time\":4725,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT6529.Z02MaA==\",\"time\":5067,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8005.g0Za/g==\",\"time\":5174,\"result\":\"OK\",\"connections,\":1},{\"name\":\"Apple-Iphone5-1_PT142.u6yj7g==\",\"time\":8751,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
