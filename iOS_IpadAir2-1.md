#### Test 51335028e04ad51_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028e04ad51/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/70FA2FA0-F742-4B00-9426-A2109F68FCC7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/70FA2FA0-F742-4B00-9426-A2109F68FCC7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028e04ad51/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028e04ad51/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9EF39C96-762D-450C-9DD6-733CBAC1B235/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52485"
,(lldb)     command script import "/tmp/70FA2FA0-F742-4B00-9426-A2109F68FCC7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 07:57:48.532 ThaliTest[1007:1368702] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D00F6937-B96B-4C09-959F-2B0A810A372A/Library/Cookies/Cookies.binarycookies
,2015-11-23 07:57:48.823 ThaliTest[1007:1368702] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 07:57:48.824 ThaliTest[1007:1368702] Multi-tasking -> Device: YES, App: YES
,2015-11-23 07:57:48.830 ThaliTest[1007:1368702] Unlimited access to network resources
,2015-11-23 07:57:48.836 ThaliTest[1007:1368702] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 07:57:53.077 ThaliTest[1007:1368702] Resetting plugins due to page load.
,2015-11-23 07:57:54.541 ThaliTest[1007:1368702] Finished load of: file:///var/mobile/Containers/Bundle/Application/9EF39C96-762D-450C-9DD6-733CBAC1B235/ThaliTest.app/www/index.html
,2015-11-23 07:57:54.679 ThaliTest[1007:1368702] JXcore Cordova plugin initializing
2015-11-23 07:57:54.680 ThaliTest[1007:1368898] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
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
,my name is : Apple-IpadAir2-1_PT2253
,attempting to connect to test coordinator
,check test folder
found test : ./testFindPeers.js
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
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 ,is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
fo,und interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c90,8:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 ,is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
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
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 56654
2015-11-23 08:04:40.045 ThaliTest[1007:1368898] jxcore: startBroadcasting
,2015-11-23 08:04:40.051 ThaliTest[1007:1368898] server: starting Apple-IpadAir2-1_PT2253.QxwsNA==
2015-11-23 08:04:40.051 ThaliTest[1007:1368898] multipeer session: start timer: 0x1898ec20
,2015-11-23 08:04:40.052 ThaliTest[1007:1368898] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2253
,2015-11-23 08:04:40.053 ThaliTest[1007:1368898] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-23T07:04:40.054Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-23 08:04:41.081 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8536.VjK3dQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23T07:04:41.083Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23T07:04:41.084Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23T07:04:41.084Z SendDataConnector.js: do connect now
2015-11-23 08:04:41.084 ThaliTest[1007:1368898] jxcore: connect Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:04:41.085 ThaliTest[1007:1368898] client session: connect
2015-11-23 08:04:41.085 ThaliTest[1007:1368898] client session: stateChange:0->1 Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:04:41.405 ThaliTest[1007:1368702] multipeer session: reset timer
2015-11-23 08:04:41.405 ThaliTest[1007:1368702] multipeer session: stop timer
,2015-11-23 08:04:41.405 ThaliTest[1007:1368702] multipeer session: start timer: 0x1898ec20
,2015-11-23 08:04:41.406 ThaliTest[1007:1368702] server session: connect
2015-11-23 08:04:41.407 ThaliTest[1007:1368702] server session: stateChange:0->1 Apple-Iphone5-1_PT8536
2015-11-23 08:04:41.410 ThaliTest[1007:1368702] server: accepting invitation Apple-Iphone5-1_PT8536
,2015-11-23 08:04:42.832 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-23 08:04:43.819 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-23 08:04:43.927 ThaliTest[1007:1369762] client session: connected
2015-11-23 08:04:43.927 ThaliTest[1007:1369762] client session: stateChange:1->2 Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:04:43.930 ThaliTest[1007:1369759] client session: fireConnectCallback: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:04:43.930 ThaliTest[1007:1369759] jxcore: connect: success
2015-11-23T07:04:43.930Z SendDataConnector.js: CLIENT connected ,to 56657, error: null
2015-11-23T07:04:43.931Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 08:04:43.932 ThaliTest[1007:1368702] client: relay established
2015-11-23 08:04:43.932 ThaliTest[1007:1368702] client: new accepted socket: 0x1899e8b0
,2015-11-23T07:04:43.946Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T07:04:44.037Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-23T07:04:44.050Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-23T07:04:44.050Z SendDataConnector.js: got all data for this round
,2015-11-23T07:04:44.051Z SendDataConnector.js: CLIENT Stop now
,2015-11-23T07:04:44.051Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 08:04:44.054 ThaliTest[1007:1368898] jxcore: disconnect
2015-11-23 08:04:44.055 ThaliTest[1007:1368898] client session: disconnectFromPeer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:04:44.055 ThaliTest[1007:1368898] client session: disconnect
2015-11-23 08:04:44.055 ThaliTest[1007:1368898] client session: stateChange:2->0 Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:04:44.061 ThaliTest[1007:1368898] jxcore: disconnect: success
2015-11-23T07:04:44.061Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8536.VjK3dQ==
---- round done--------
device[2]: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23T07:04:44.062Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23T07:04:44.062Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23T07:04:44.062Z SendDataConnect,or.js: do connect now
2015-11-23 08:04:44.062 ThaliTest[1007:1368898] jxcore: connect Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:04:44.062 ThaliTest[1007:1368898] client session: connect
2015-11-23 08:04:44.062 ThaliTest[1007:1368898] client session: stateChange:0->1 Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:04:44.460 ThaliTest[1007:1369757] server session: connected
2015-11-23 08:04:44.460 ThaliTest[1007:1369757] server session: stateChange:1->2 Apple-Iphone5-1_PT8536
,2015-11-23 08:04:44.464 ThaliTest[1007:1368702] server relay: connected (to port: 56654)
2015-11-23T07:04:44.468Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T07:04:44.741Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-11-23T07:04:44.757Z SendDataTCPServer.js: TCP/IP server has received 42656 bytes of data
,2015-11-23T07:04:44.770Z SendDataTCPServer.js: TCP/IP server has received 52576 bytes of data
,2015-11-23T07:04:44.807Z SendDataTCPServer.js: TCP/IP server has received 55552 bytes of data
,2015-11-23T07:04:44.820Z SendDataTCPServer.js: TCP/IP server has received 83328 bytes of data
,2015-11-23T07:04:44.846Z SendDataTCPServer.js: TCP/IP server has received 84320 bytes of data
,2015-11-23T07:04:44.870Z SendDataTCPServer.js: TCP/IP server has received 95232 bytes of data
,2015-11-23T07:04:44.883Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 08:04:44.945 ThaliTest[1007:1369755] server session: not connected Apple-Iphone5-1_PT8536
,2015-11-23 08:04:45.786 ThaliTest[1007:1368702] multipeer session: reset timer
2015-11-23 08:04:45.787 ThaliTest[1007:1368702] multipeer session: stop timer
2015-11-23 08:04:45.787 ThaliTest[1007:1368702] multipeer session: start timer: 0x1898ec20
,2015-11-23 08:04:45.787 ThaliTest[1007:1368702] server session: connect
2015-11-23 08:04:45.787 ThaliTest[1007:1368702] server session: stateChange:0->1 Apple-Iphone6-1_PT606
,2015-11-23 08:04:45.789 ThaliTest[1007:1368702] server: accepting invitation Apple-Iphone6-1_PT606
,2015-11-23 08:04:47.039 ThaliTest[1007:1369755] client session: connected
2015-11-23 08:04:47.039 ThaliTest[1007:1369755] client session: stateChange:1->2 Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:04:47.040 ThaliTest[1007:1369755] client session: fireConnectCallback: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:04:47.040 ThaliTest[1007:1369755] jxcore: connect: success
2015-11-23T07:04:47.040Z SendDataConnector.js: CLIENT connected to 56662, error: null
2015-11-23T07:04:47.040Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 08:04:47.041 ThaliTest[1007:1368702] client: relay established
2015-11-23 08:04:47.041 ThaliTest[1007:1368702] client: new accepted socket: 0x189abd80
,2015-11-23T07:04:47.054Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T07:04:47.143Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-23T07:04:47.157Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-23T07:04:47.170Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-23T07:04:47.368Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-23T07:04:47.368Z SendDataConnector.js: got all data for this round
,2015-11-23T07:04:47.369Z SendDataConnector.js: CLIENT Stop now
2015-11-23T07:04:47.369Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 08:04:47.369 ThaliTest[1007:1368898] jxcore: disconnect
2015-11-23 08:04:47.370 ThaliTest[1007:1368898] client session: disconnectFromPeer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:04:47.370 ThaliTest[1007:1368898] client session: disconnect
2015-11-23 08:04:47.370 ThaliTest[1007:1368898] client session: stateChange:2->0 Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:04:47.374 ThaliTest[1007:1368898] jxcore: disconnect: success
2015-11-23T07:04:47.374Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT606.CSvXcQ==
---- round done--------
device[3]: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23T07:04:47.375Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23T07:04:47.375Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23T07:04:47.375Z SendDataConnector.js: do connect now
2015-11-23 08:04:47.376 ThaliTest[1007:1368898] jxcore: connect Apple-Iphone5s-1_PT18,28.9cQq2g==
2015-11-23 08:04:47.376 ThaliTest[1007:1368898] client session: connect
2015-11-23 08:04:47.376 ThaliTest[1007:1368898] client session: stateChange:0->1 Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:04:48.536 ThaliTest[1007:1369751] server session: connected
2015-11-23 08:04:48.536 ThaliTest[1007:1369751] server session: stateChange:1->2 Apple-Iphone6-1_PT606
,2015-11-23 08:04:48.541 ThaliTest[1007:1368702] server relay: connected (to port: 56654)
,2015-11-23T07:04:48.551Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-23T07:04:48.650Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-11-23T07:04:48.661Z SendDataTCPServer.js: TCP/IP server has received 34330 bytes of data
,2015-11-23T07:04:48.675Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-23 08:04:48.701 ThaliTest[1007:1369805] server session: not connected Apple-Iphone6-1_PT606
,2015-11-23 08:04:51.866 ThaliTest[1007:1369751] client session: connected
2015-11-23 08:04:51.866 ThaliTest[1007:1369751] client session: stateChange:1->2 Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:04:51.868 ThaliTest[1007:1369751] client session: fireConnectCallback: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:04:51.868 ThaliTest[1007:1369751] jxcore: connect: success
2015-11-23T07:04:51.869Z SendDataConnector.js: CLIENT connected to 56667, error: null
2015-11-23T07:04:51.869Z SendDataConnector.js: CLIENT starting client 
,2015-11-23 08:04:51.870 ThaliTest[1007:1368702] client: relay established
2015-11-23 08:04:51.870 ThaliTest[1007:1368702] client: new accepted socket: 0x175d7b90
,2015-11-23T07:04:51.882Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-23T07:04:52.297Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-23T07:04:52.311Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-23T07:04:52.323Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-23T07:04:52.324Z SendDataConnector.js: got all data for this round
,2015-11-23T07:04:52.324Z SendDataConnector.js: CLIENT Stop now
2015-11-23T07:04:52.324Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-23 08:04:52.325 ThaliTest[1007:1368898] jxcore: disconnect
,2015-11-23 08:04:52.325 ThaliTest[1007:1368898] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:04:52.325 ThaliTest[1007:1368898] client session: disconnect
2015-11-23 08:04:52.326 ThaliTest[1007:1368898] client session,: stateChange:2->0 Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:04:52.329 ThaliTest[1007:1368898] jxcore: disconnect: success
,2015-11-23T07:04:52.331Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1828.9cQq2g==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT2253","time":12293,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT8536.VjK3dQ==","time":2967,"result":"OK","connections":1},{"name":"Apple-Iphone6-1_PT606.CSvXcQ==","time":3306,"result":"OK","connections":1,},{"name":"Apple-Iphone5s-1_PT1828.9cQq2g==","time":4949,"result":"OK","connections":1}]}
sendList : 100% : 4949 ms, 99% : 4949 ms, 95 : 4949 ms, 90% : 4949 ms.
Result count 3, range 2967 ms to  4949 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-23T07:04:52.335Z SendDataConnector.js: CLIENT Stop now
,2015-11-23 08:05:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:05:15.801 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:05:15.801 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:05:15.801 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:05:24.631 ThaliTest[1007:1368702] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:05:24.631 ThaliTest[1007:1368702] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:05:27.195 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:05:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:05:45.799 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:05:45.799 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:05:45.800 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:05:54.508 ThaliTest[1007:1368702] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:05:54.508 ThaliTest[1007:1368702] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:05:54.508 ThaliTest[1007:1368702] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:05:54.508 ThaliTest[1007:1368702] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(nul,l)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:05:59.302 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:05:59.693 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:06:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:06:15.800 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:06:15.801 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:06:16.569 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:06:20.406 ThaliTest[1007:1368702] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:06:20.406 ThaliTest[1007:1368702] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:06:24.518 ThaliTest[1007:1368702] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:06:24.518 ThaliTest[1007:1368702] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:06:25.510 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:06:26.519 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:06:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:06:45.799 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:06:45.799 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:06:45.799 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:06:58.140 ThaliTest[1007:1368702] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:06:58.140 ThaliTest[1007:1368702] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:07:04.299 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:07:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:07:15.799 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:07:15.881 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:07:15.881 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:07:24.275 ThaliTest[1007:1368702] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:07:24.275 ThaliTest[1007:1368702] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:07:25.395 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:07:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:07:45.800 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:07:45.800 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:07:45.800 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:07:57.880 ThaliTest[1007:1368702] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:07:57.881 ThaliTest[1007:1368702] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:08:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:08:15.797 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:08:15.798 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:08:16.592 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:08:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:09:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:09:15.796 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:09:15.797 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:09:15.893 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:09:21.908 ThaliTest[1007:1368702] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:09:21.908 ThaliTest[1007:1368702] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:09:22.936 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:09:28.278 ThaliTest[1007:1368702] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:09:28.278 ThaliTest[1007:1368702] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:09:33.071 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":true}]
,2015-11-23 08:09:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:09:45.801 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:09:45.801 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:09:45.803 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5s-1_PT1828.9cQq2g==
,2015-11-23 08:09:52.290 ThaliTest[1007:1368702] client: lost peer: Apple-Iphone5s-1_PT1828.9cQq2g==
2015-11-23 08:09:52.290 ThaliTest[1007:1368702] client session: onPeerLost: Apple-Iphone5s-1_PT1828.9cQq2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1828.9cQq2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-23 08:10:15.788 ThaliTest[1007:1368702] multipeer session: restart
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,2015-11-23 08:10:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:10:45.798 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:10:45.798 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:11:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:11:15.798 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:11:16.420 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:11:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:11:45.797 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:11:45.807 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:12:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:12:15.797 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:12:16.345 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:12:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:12:45.798 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:12:45.798 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:13:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:13:16.106 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,2015-11-23 08:13:16.110 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:13:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:13:45.798 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
2015-11-23 08:13:45.798 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,Turning Wifi off
,Warning: iOS does not support ToggleWiFi
,We could not turn wifi off! - Warning: iOS does not support ToggleWiFi
,Turning Wifi back on
,Warning: iOS does not support ToggleWiFi
,We could turn wifi back on! - Warning: iOS does not support ToggleWiFi
,toggleWiFi finished
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,2015-11-23 08:14:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:14:15.797 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6,ff:fee8:b438
,2015-11-23 08:14:17.851 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,2015-11-23 08:14:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:14:45.796 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:14:45.797 ThaliTest[1007:1368702] client: found peer: Apple-Iphone6-1_PT606.CSvXcQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,2015-11-23 08:15:00.279 ThaliTest[1007:1368702] client: lost peer: Apple-Iphone6-1_PT606.CSvXcQ==
2015-11-23 08:15:00.279 ThaliTest[1007:1368702] client session: onPeerLost: Apple-Iphone6-1_PT606.CSvXcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT606.CSvXcQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,2015-11-23 08:15:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:15:16.670 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::10c4:c908:11f8:b632
-iface: IPv4 is internal : false, has ip: 192.168.1.125
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::fca6:6ff:fee8:b438
,2015-11-23 08:15:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:15:45.796 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:16:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:16:15.796 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:16:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:17:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:17:15.795 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:17:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:17:46.462 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:18:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:18:15.796 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:18:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:18:46.219 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:19:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:19:15.796 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:19:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:19:46.023 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:20:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:20:15.796 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:20:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:20:45.796 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:21:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:21:15.796 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:21:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:21:45.795 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:22:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:22:15.962 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:22:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:22:45.797 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:23:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:23:16.740 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:23:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:23:45.795 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:24:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:24:16.496 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:24:45.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:24:45.796 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,2015-11-23 08:25:15.788 ThaliTest[1007:1368702] multipeer session: restart
,2015-11-23 08:25:15.796 ThaliTest[1007:1368702] client: found peer: Apple-Iphone5-1_PT8536.VjK3dQ==
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-11-23 08:25:40.095 ThaliTest[1007:1368898] jxcore: stopBroadcasting
2015-11-23 08:25:40.095 ThaliTest[1007:1368898] THEMultipeerSession stopping peer
2015-11-23 08:25:40.095 ThaliTest[1007:1368898] multipeer session: stop timer
2015-11-23 08:25:40.095 ThaliTest[1007:1368898] server session: disconnect
2015-11-23 08:25:40.095 ThaliTest[1007:1368898] server session: stateChange:2->0 Apple-Iphone5-1_PT8536
,2015-11-23 08:25:40.099 ThaliTest[1007:1368898] server session: disconnect
2015-11-23 08:25:40.099 ThaliTest[1007:1368898] server session: stateChange:2->0 Apple-Iphone6-1_PT606
,2015-11-23 08:25:40.102 ThaliTest[1007:1368898] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-23T07:25:40.118Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-23T07:25:40.118Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-23T07:25:40.119Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT8536.VjK3dQ==\",\"time\":2967,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT606.CSvXcQ==\",\"time\":3306,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1828.9cQq2g==\",\"time\":4949,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT8536.VjK3dQ,==\",\"time\":2967,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT8536.VjK3dQ==\",\"time\":3054,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT606.CSvXcQ==\",\"time\":3306,\"result\":\"OK\",\"connections\":1},{\"name,\":\"Apple-IpadAir2-1_PT2253.QxwsNA==\",\"time\":3327,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT606.CSvXcQ==\",\"time\":3538,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT2253.QxwsNA==\",\"time\":3663,\"result,\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1828.9cQq2g==\",\"time\":4949,\"result\":\"OK\",\"connections\":1}]}}","devices":3,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
