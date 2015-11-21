#### Test 51335028e20f43b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028e20f43b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CA593395-1303-42EB-9981-0CE135B5D418/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CA593395-1303-42EB-9981-0CE135B5D418/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028e20f43b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028e20f43b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3BB140ED-09FE-4080-A00D-CC10A4E15477/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52045"
,(lldb)     command script import "/tmp/CA593395-1303-42EB-9981-0CE135B5D418/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-21 13:27:29.521 ThaliTest[1131:896237] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/65A39DA5-7168-495F-916E-BB7555CDD980/Library/Cookies/Cookies.binarycookies
,2015-11-21 13:27:29.942 ThaliTest[1131:896237] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-21 13:27:29.943 ThaliTest[1131:896237] Multi-tasking -> Device: YES, App: YES
,2015-11-21 13:27:29.952 ThaliTest[1131:896237] Unlimited access to network resources
,2015-11-21 13:27:29.960 ThaliTest[1131:896237] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-21 13:27:33.737 ThaliTest[1131:896237] Resetting plugins due to page load.
,2015-11-21 13:27:34.112 ThaliTest[1131:896237] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/3BB140ED-09FE-4080-A00D-CC10A4E15477/ThaliTest.app/www/index.html
,2015-11-21 13:27:34.264 ThaliTest[1131:896237] JXcore Cordova plugin initializing
,2015-11-21 13:27:34.266 ThaliTest[1131:896363] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT8264
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
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
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
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::49:45ff:fe35:c69
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"1000000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"2\"}","devices":3,"addressList":[,]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"2"}, bt-address lenght : 0
,check server
,serverPort is 56692
,2015-11-21 13:38:24.071 ThaliTest[1131:896363] jxcore: startBroadcasting
,2015-11-21 13:38:24.086 ThaliTest[1131:896363] server: starting Apple-Iphone5s-1_PT8264./5qd6Q==
,2015-11-21 13:38:24.087 ThaliTest[1131:896363] multipeer session: start timer: 0x1977a510
2015-11-21 13:38:24.088 ThaliTest[1131:896363] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT8264
,2015-11-21 13:38:24.090 ThaliTest[1131:896363] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-21T12:38:24.097Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-21 13:38:24.451 ThaliTest[1131:896237] client: found peer: Apple-Iphone6-1_PT8382.HGUadg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8382.HGUadg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tru,e
device[1]: Apple-Iphone6-1_PT8382.HGUadg==
2015-11-21T12:38:24.462Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8382.HGUadg==
2015-11-21T12:38:24.466Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8382.HGUadg==,
,2015-11-21T12:38:24.467Z SendDataConnector.js: do connect now
,2015-11-21 13:38:24.469 ThaliTest[1131:896237] client: found peer: Apple-Iphone5-1_PT759.cZHSYA==
2015-11-21 13:38:24.468 ThaliTest[1131:896363] jxcore: connect Apple-Iphone6-1_PT8382.HGUadg==
,2015-11-21 13:38:24.470 ThaliTest[1131:896237] client: found peer: Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:24.472 ThaliTest[1131:896363] client session: connect
2015-11-21 13:38:24.472 ThaliTest[1131:896363] client session: stateChange:0->1 Apple-Iphone6-1_PT8382.HGUadg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT759.cZHSYA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5427.N/zz4w==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-21 13:38:26.837 ThaliTest[1131:897369] client session: connected
,2015-11-21 13:38:26.839 ThaliTest[1131:897369] client session: stateChange:1->2 Apple-Iphone6-1_PT8382.HGUadg==
,2015-11-21 13:38:26.843 ThaliTest[1131:897369] client session: fireConnectCallback: Apple-Iphone6-1_PT8382.HGUadg==
2015-11-21 13:38:26.844 ThaliTest[1131:897369] jxcore: connect: success
2015-11-21T12:38:26.846Z SendDataConnector.js: CLIENT connected to, 56696, error: null
2015-11-21T12:38:26.846Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 13:38:26.851 ThaliTest[1131:896237] client: relay established
2015-11-21 13:38:26.852 ThaliTest[1131:896237] client: new accepted socket: 0x19780be0
,2015-11-21T12:38:26.863Z SendDataConnector.js: CLIENT now sending 1000000 bytes of data
,2015-11-21T12:38:30.793Z SendDataConnector.js: CLIENT is data received : 290000
,2015-11-21T12:38:30.809Z SendDataConnector.js: CLIENT is data received : 1000000
,2015-11-21T12:38:30.810Z SendDataConnector.js: got all data for this round
,2015-11-21T12:38:30.813Z SendDataConnector.js: CLIENT Stop now
2015-11-21T12:38:30.813Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-21 13:38:30.815 ThaliTest[1131:896363] jxcore: disconnect
,2015-11-21 13:38:30.817 ThaliTest[1131:896363] client session: disconnectFromPeer: Apple-Iphone6-1_PT8382.HGUadg==
,2015-11-21 13:38:30.817 ThaliTest[1131:896363] client session: disconnect
2015-11-21 13:38:30.818 ThaliTest[1131:896363] client session: stateChange:2->0 Apple-Iphone6-1_PT8382.HGUadg==
,2015-11-21 13:38:30.822 ThaliTest[1131:896363] jxcore: disconnect: success
2015-11-21T12:38:30.826Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8382.HGUadg==
,---- round done--------
device[2]: Apple-Iphone5-1_PT759.cZHSYA==
,2015-11-21T12:38:30.830Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT759.cZHSYA==
,2015-11-21T12:38:30.830Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT759.cZHSYA==
,2015-11-21T12:38:30.831Z SendDataConnector.js: do connect now
,2015-11-21 13:38:30.832 ThaliTest[1131:896363] jxcore: connect Apple-Iphone5-1_PT759.cZHSYA==
2015-11-21 13:38:30.832 ThaliTest[1131:896363] client session: connect
2015-11-21 13:38:30.833 ThaliTest[1131:896363] client session: stateChange:0->1 Apple-Iph,one5-1_PT759.cZHSYA==
,2015-11-21 13:38:36.642 ThaliTest[1131:897365] client session: connected
2015-11-21 13:38:36.643 ThaliTest[1131:897365] client session: stateChange:1->2 Apple-Iphone5-1_PT759.cZHSYA==
,2015-11-21 13:38:36.706 ThaliTest[1131:897373] client session: fireConnectCallback: Apple-Iphone5-1_PT759.cZHSYA==
2015-11-21 13:38:36.707 ThaliTest[1131:897373] jxcore: connect: success
2015-11-21T12:38:36.709Z SendDataConnector.js: CLIENT connected to 56699, error: null
,2015-11-21T12:38:36.709Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 13:38:36.713 ThaliTest[1131:896237] client: relay established
2015-11-21 13:38:36.714 ThaliTest[1131:896237] client: new accepted socket: 0x15d9be50
,2015-11-21T12:38:36.726Z SendDataConnector.js: CLIENT now sending 1000000 bytes of data
,2015-11-21T12:38:38.343Z SendDataConnector.js: CLIENT is data received : 580000
,2015-11-21T12:38:38.716Z SendDataConnector.js: CLIENT is data received : 760000
,2015-11-21T12:38:38.730Z SendDataConnector.js: CLIENT is data received : 780000
,2015-11-21T12:38:38.759Z SendDataConnector.js: CLIENT is data received : 790000
,2015-11-21T12:38:38.776Z SendDataConnector.js: CLIENT is data received : 800000
,2015-11-21T12:38:38.791Z SendDataConnector.js: CLIENT is data received : 820000
,2015-11-21T12:38:39.251Z SendDataConnector.js: CLIENT is data received : 870000
,2015-11-21T12:38:39.267Z SendDataConnector.js: CLIENT is data received : 920000
,2015-11-21T12:38:39.318Z SendDataConnector.js: CLIENT is data received : 980000
,2015-11-21T12:38:39.357Z SendDataConnector.js: CLIENT is data received : 1000000
,2015-11-21T12:38:39.358Z SendDataConnector.js: got all data for this round
,2015-11-21T12:38:39.359Z SendDataConnector.js: CLIENT Stop now
2015-11-21T12:38:39.360Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 13:38:39.363 ThaliTest[1131:896363] jxcore: disconnect
2015-11-21 13:38:39.364 ThaliTest[1131:896363] client session: disconnectFromPeer: Apple-Iphone5-1_PT759.cZHSYA==
2015-11-21 13:38:39.364 ThaliTest[1131:896363] client session: disconnect
2015-11-21 13:38:39.365 ThaliTest[1131:896363] client session: stateChange:2->0 Apple-Iphone5-1_PT759.cZHSYA==
,2015-11-21 13:38:39.368 ThaliTest[1131:896363] jxcore: disconnect: success
2015-11-21T12:38:39.370Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT759.cZHSYA==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT5427.N/zz4w==
2015-11-21T12:38:39.375Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5427.N/zz4w==
2015-11-21T12:38:39.375Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21T12:38:39.375Z SendDataConnector.js: do connect now
,2015-11-21 13:38:39.376 ThaliTest[1131:896363] jxcore: connect Apple-IpadAir2-1_PT5427.N/zz4w==
2015-11-21 13:38:39.377 ThaliTest[1131:896363] client session: connect
2015-11-21 13:38:39.378 ThaliTest[1131:896363] client session: stateChange:0->1 Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:40.137 ThaliTest[1131:896237] multipeer session: reset timer
2015-11-21 13:38:40.138 ThaliTest[1131:896237] multipeer session: stop timer
2015-11-21 13:38:40.139 ThaliTest[1131:896237] multipeer session: start timer: 0x1977a510
2015-11-,21 13:38:40.139 ThaliTest[1131:896237] server session: connect
2015-11-21 13:38:40.140 ThaliTest[1131:896237] server session: stateChange:0->1 Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:40.152 ThaliTest[1131:896237] server: accepting invitation Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:41.590 ThaliTest[1131:896237] multipeer session: reset timer
2015-11-21 13:38:41.591 ThaliTest[1131:896237] multipeer session: stop timer
2015-11-21 13:38:41.591 ThaliTest[1131:896237] multipeer session: start timer: 0x1977a510
2015-11-,21 13:38:41.592 ThaliTest[1131:896237] server session: connect
2015-11-21 13:38:41.593 ThaliTest[1131:896237] server session: stateChange:0->1 Apple-Iphone6-1_PT8382
,2015-11-21 13:38:41.605 ThaliTest[1131:896237] server: accepting invitation Apple-Iphone6-1_PT8382
,2015-11-21 13:38:42.342 ThaliTest[1131:897419] client session: connected
2015-11-21 13:38:42.343 ThaliTest[1131:897419] client session: stateChange:1->2 Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:42.408 ThaliTest[1131:897365] client session: fireConnectCallback: Apple-IpadAir2-1_PT5427.N/zz4w==
2015-11-21 13:38:42.408 ThaliTest[1131:897365] jxcore: connect: success
2015-11-21T12:38:42.410Z SendDataConnector.js: CLIENT connected t,o 56702, error: null
2015-11-21T12:38:42.410Z SendDataConnector.js: CLIENT starting client 
,2015-11-21 13:38:42.414 ThaliTest[1131:896237] client: relay established
2015-11-21 13:38:42.415 ThaliTest[1131:896237] client: new accepted socket: 0x19239340
,2015-11-21T12:38:42.427Z SendDataConnector.js: CLIENT now sending 1000000 bytes of data
,2015-11-21 13:38:42.860 ThaliTest[1131:897419] server session: connected
2015-11-21 13:38:42.861 ThaliTest[1131:897419] server session: stateChange:1->2 Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:42.870 ThaliTest[1131:896237] server relay: connected (to port: 56692)
,2015-11-21 13:38:42.916 ThaliTest[1131:896237] multipeer session: reset timer
2015-11-21 13:38:42.916 ThaliTest[1131:896237] multipeer session: stop timer
2015-11-21 13:38:42.916 ThaliTest[1131:896237] multipeer session: start timer: 0x1977a510
2015-11-,21 13:38:42.917 ThaliTest[1131:896237] server session: connect
2015-11-21 13:38:42.917 ThaliTest[1131:896237] server session: stateChange:0->1 Apple-Iphone5-1_PT759
,2015-11-21 13:38:42.926 ThaliTest[1131:896237] server: accepting invitation Apple-Iphone5-1_PT759
,2015-11-21T12:38:42.941Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T12:38:43.652Z SendDataTCPServer.js: TCP/IP server has received 12288 bytes of data
,2015-11-21 13:38:44.055 ThaliTest[1131:897365] server session: connected
2015-11-21 13:38:44.056 ThaliTest[1131:897365] server session: stateChange:1->2 Apple-Iphone6-1_PT8382
,2015-11-21T12:38:44.074Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21 13:38:44.464 ThaliTest[1131:896237] server relay: connected (to port: 56692)
,2015-11-21T12:38:44.488Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
,2015-11-21T12:38:44.630Z SendDataConnector.js: CLIENT is data received : 210000
,2015-11-21T12:38:44.645Z SendDataTCPServer.js: TCP/IP server has received 163840 bytes of data
,2015-11-21T12:38:44.650Z SendDataTCPServer.js: TCP/IP server has received 294912 bytes of data
2015-11-21T12:38:44.655Z SendDataTCPServer.js: TCP/IP server has received 329728 bytes of data
,2015-11-21T12:38:44.670Z SendDataTCPServer.js: TCP/IP server has received 460800 bytes of data
,2015-11-21T12:38:44.675Z SendDataTCPServer.js: TCP/IP server has received 577536 bytes of data
,2015-11-21T12:38:44.691Z SendDataTCPServer.js: TCP/IP server has received 626340 bytes of data
,2015-11-21T12:38:44.704Z SendDataTCPServer.js: TCP/IP server has received 646050 bytes of data
,2015-11-21T12:38:44.719Z SendDataTCPServer.js: TCP/IP server has received 650430 bytes of data
2015-11-21T12:38:44.719Z SendDataTCPServer.js: TCP/IP server has received 12430 bytes of data
,2015-11-21T12:38:44.746Z SendDataTCPServer.js: TCP/IP server has received 120450 bytes of data
,2015-11-21T12:38:44.777Z SendDataTCPServer.js: TCP/IP server has received 251522 bytes of data
,2015-11-21T12:38:44.782Z SendDataTCPServer.js: TCP/IP server has received 343830 bytes of data
,2015-11-21T12:38:44.786Z SendDataTCPServer.js: TCP/IP server has received 657000 bytes of data
,2015-11-21T12:38:44.800Z SendDataTCPServer.js: TCP/IP server has received 392010 bytes of data
,2015-11-21T12:38:44.802Z SendDataTCPServer.js: TCP/IP server has received 672330 bytes of data
,2015-11-21T12:38:44.814Z SendDataTCPServer.js: TCP/IP server has received 713798 bytes of data
,2015-11-21T12:38:44.832Z SendDataTCPServer.js: TCP/IP server has received 735840 bytes of data
,2015-11-21T12:38:44.846Z SendDataTCPServer.js: TCP/IP server has received 786210 bytes of data
,2015-11-21T12:38:44.861Z SendDataTCPServer.js: TCP/IP server has received 792780 bytes of data
,2015-11-21T12:38:44.887Z SendDataTCPServer.js: TCP/IP server has received 410868 bytes of data
,2015-11-21T12:38:44.901Z SendDataTCPServer.js: TCP/IP server has received 532170 bytes of data
,2015-11-21T12:38:44.950Z SendDataTCPServer.js: TCP/IP server has received 551880 bytes of data
,2015-11-21T12:38:44.966Z SendDataTCPServer.js: TCP/IP server has received 612206 bytes of data
,2015-11-21T12:38:44.983Z SendDataTCPServer.js: TCP/IP server has received 707370 bytes of data
,2015-11-21T12:38:45.001Z SendDataTCPServer.js: TCP/IP server has received 825630 bytes of data
,2015-11-21T12:38:45.016Z SendDataTCPServer.js: TCP/IP server has received 744600 bytes of data
,2015-11-21T12:38:45.019Z SendDataTCPServer.js: TCP/IP server has received 932940 bytes of data
,2015-11-21T12:38:45.025Z SendDataConnector.js: CLIENT is data received : 1000000
,2015-11-21T12:38:45.026Z SendDataConnector.js: got all data for this round
,2015-11-21T12:38:45.029Z SendDataConnector.js: CLIENT Stop now
2015-11-21T12:38:45.029Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-21 13:38:45.030 ThaliTest[1131:896363] jxcore: disconnect
,2015-11-21 13:38:45.032 ThaliTest[1131:896363] client session: disconnectFromPeer: Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:45.033 ThaliTest[1131:896363] client session: disconnect
,2015-11-21 13:38:45.034 ThaliTest[1131:896363] client session: stateChange:2->0 Apple-IpadAir2-1_PT5427.N/zz4w==
,2015-11-21 13:38:45.050 ThaliTest[1131:896363] jxcore: disconnect: success
,2015-11-21T12:38:45.055Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5427.N/zz4w==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT8264","time":21003,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT8382.HGUadg==","time":6347,"result":"OK","connections":1},{"name":"Apple-Iphone5-1_PT759.cZHSYA==","time":8528,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT5427.N/zz4w==","time":5651,"result":"OK","connections":1}]}
,sendList : 100% : 8528 ms, 99% : 8528 ms, 95 : 8528 ms, 90% : 8528 ms.
,Result count 3, range 5651 ms to  8528 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-21T12:38:45.080Z SendDataConnector.js: CLIENT Stop now
,2015-11-21T12:38:45.101Z SendDataTCPServer.js: TCP/IP server has received 836580 bytes of data
,2015-11-21T12:38:45.107Z SendDataTCPServer.js: TCP/IP server has received 1000002 bytes of data
,2015-11-21T12:38:45.151Z SendDataTCPServer.js: TCP/IP server has received 967652 bytes of data
,2015-11-21T12:38:45.159Z SendDataTCPServer.js: TCP/IP server has received 1000002 bytes of data
,2015-11-21 13:38:45.165 ThaliTest[1131:897373] server session: not connected Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:45.181 ThaliTest[1131:897365] server session: not connected Apple-Iphone6-1_PT8382
,2015-11-21 13:38:48.046 ThaliTest[1131:897373] server session: connected
2015-11-21 13:38:48.048 ThaliTest[1131:897373] server session: stateChange:1->2 Apple-Iphone5-1_PT759
,2015-11-21 13:38:48.222 ThaliTest[1131:896237] server relay: connected (to port: 56692)
,2015-11-21T12:38:48.230Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-21T12:38:49.308Z SendDataTCPServer.js: TCP/IP server has received 7936 bytes of data
,2015-11-21T12:38:49.324Z SendDataTCPServer.js: TCP/IP server has received 18848 bytes of data
,2015-11-21T12:38:49.343Z SendDataTCPServer.js: TCP/IP server has received 28768 bytes of data
,2015-11-21T12:38:49.357Z SendDataTCPServer.js: TCP/IP server has received 45632 bytes of data
,2015-11-21T12:38:49.373Z SendDataTCPServer.js: TCP/IP server has received 60512 bytes of data
,2015-11-21T12:38:49.388Z SendDataTCPServer.js: TCP/IP server has received 77376 bytes of data
,2015-11-21T12:38:49.404Z SendDataTCPServer.js: TCP/IP server has received 81344 bytes of data
,2015-11-21T12:38:49.625Z SendDataTCPServer.js: TCP/IP server has received 87296 bytes of data
,2015-11-21T12:38:49.642Z SendDataTCPServer.js: TCP/IP server has received 94240 bytes of data
,2015-11-21T12:38:49.698Z SendDataTCPServer.js: TCP/IP server has received 104160 bytes of data
,2015-11-21T12:38:49.712Z SendDataTCPServer.js: TCP/IP server has received 114080 bytes of data
,2015-11-21T12:38:49.725Z SendDataTCPServer.js: TCP/IP server has received 128960 bytes of data
,2015-11-21T12:38:49.739Z SendDataTCPServer.js: TCP/IP server has received 146816 bytes of data
,2015-11-21T12:38:49.754Z SendDataTCPServer.js: TCP/IP server has received 157728 bytes of data
,2015-11-21T12:38:49.766Z SendDataTCPServer.js: TCP/IP server has received 174592 bytes of data
,2015-11-21T12:38:49.781Z SendDataTCPServer.js: TCP/IP server has received 189600 bytes of data
,2015-11-21T12:38:49.795Z SendDataTCPServer.js: TCP/IP server has received 206336 bytes of data
,2015-11-21T12:38:49.809Z SendDataTCPServer.js: TCP/IP server has received 217248 bytes of data
,2015-11-21T12:38:49.822Z SendDataTCPServer.js: TCP/IP server has received 235104 bytes of data
,2015-11-21T12:38:49.836Z SendDataTCPServer.js: TCP/IP server has received 250976 bytes of data
,2015-11-21T12:38:49.849Z SendDataTCPServer.js: TCP/IP server has received 267840 bytes of data
,2015-11-21T12:38:49.861Z SendDataTCPServer.js: TCP/IP server has received 282720 bytes of data
,2015-11-21T12:38:49.874Z SendDataTCPServer.js: TCP/IP server has received 302560 bytes of data
,2015-11-21T12:38:49.887Z SendDataTCPServer.js: TCP/IP server has received 324384 bytes of data
,2015-11-21T12:38:49.901Z SendDataTCPServer.js: TCP/IP server has received 332320 bytes of data
,2015-11-21T12:38:50.143Z SendDataTCPServer.js: TCP/IP server has received 334304 bytes of data
,2015-11-21T12:38:50.158Z SendDataTCPServer.js: TCP/IP server has received 339264 bytes of data
,2015-11-21T12:38:50.172Z SendDataTCPServer.js: TCP/IP server has received 345216 bytes of data
,2015-11-21T12:38:50.190Z SendDataTCPServer.js: TCP/IP server has received 352160 bytes of data
,2015-11-21T12:38:50.215Z SendDataTCPServer.js: TCP/IP server has received 355136 bytes of data
,2015-11-21T12:38:50.229Z SendDataTCPServer.js: TCP/IP server has received 364064 bytes of data
,2015-11-21T12:38:50.243Z SendDataTCPServer.js: TCP/IP server has received 372000 bytes of data
,2015-11-21T12:38:50.256Z SendDataTCPServer.js: TCP/IP server has received 384896 bytes of data
,2015-11-21T12:38:50.270Z SendDataTCPServer.js: TCP/IP server has received 395808 bytes of data
,2015-11-21T12:38:50.285Z SendDataTCPServer.js: TCP/IP server has received 408704 bytes of data
,2015-11-21T12:38:50.298Z SendDataTCPServer.js: TCP/IP server has received 421600 bytes of data
,2015-11-21T12:38:50.312Z SendDataTCPServer.js: TCP/IP server has received 431520 bytes of data
,2015-11-21T12:38:50.325Z SendDataTCPServer.js: TCP/IP server has received 443424 bytes of data
,2015-11-21T12:38:50.340Z SendDataTCPServer.js: TCP/IP server has received 458304 bytes of data
,2015-11-21T12:38:50.354Z SendDataTCPServer.js: TCP/IP server has received 477152 bytes of data
,2015-11-21T12:38:50.367Z SendDataTCPServer.js: TCP/IP server has received 494016 bytes of data
,2015-11-21T12:38:50.380Z SendDataTCPServer.js: TCP/IP server has received 503936 bytes of data
,2015-11-21T12:38:50.396Z SendDataTCPServer.js: TCP/IP server has received 521792 bytes of data
,2015-11-21T12:38:50.410Z SendDataTCPServer.js: TCP/IP server has received 528736 bytes of data
,2015-11-21T12:38:50.670Z SendDataTCPServer.js: TCP/IP server has received 532704 bytes of data
,2015-11-21T12:38:50.688Z SendDataTCPServer.js: TCP/IP server has received 540640 bytes of data
,2015-11-21T12:38:50.704Z SendDataTCPServer.js: TCP/IP server has received 547584 bytes of data
,2015-11-21T12:38:50.721Z SendDataTCPServer.js: TCP/IP server has received 555520 bytes of data
,2015-11-21T12:38:50.736Z SendDataTCPServer.js: TCP/IP server has received 565440 bytes of data
,2015-11-21T12:38:50.749Z SendDataTCPServer.js: TCP/IP server has received 573376 bytes of data
,2015-11-21T12:38:50.765Z SendDataTCPServer.js: TCP/IP server has received 576352 bytes of data
,2015-11-21T12:38:50.778Z SendDataTCPServer.js: TCP/IP server has received 584288 bytes of data
,2015-11-21T12:38:50.792Z SendDataTCPServer.js: TCP/IP server has received 597184 bytes of data
,2015-11-21T12:38:50.807Z SendDataTCPServer.js: TCP/IP server has received 609088 bytes of data
,2015-11-21T12:38:50.819Z SendDataTCPServer.js: TCP/IP server has received 620000 bytes of data
,2015-11-21T12:38:50.834Z SendDataTCPServer.js: TCP/IP server has received 633888 bytes of data
,2015-11-21T12:38:50.848Z SendDataTCPServer.js: TCP/IP server has received 649760 bytes of data
,2015-11-21T12:38:50.862Z SendDataTCPServer.js: TCP/IP server has received 663648 bytes of data
,2015-11-21T12:38:50.874Z SendDataTCPServer.js: TCP/IP server has received 676544 bytes of data
,2015-11-21T12:38:50.887Z SendDataTCPServer.js: TCP/IP server has received 695392 bytes of data
,2015-11-21T12:38:50.902Z SendDataTCPServer.js: TCP/IP server has received 713248 bytes of data
,2015-11-21T12:38:50.916Z SendDataTCPServer.js: TCP/IP server has received 729120 bytes of data
,2015-11-21T12:38:50.930Z SendDataTCPServer.js: TCP/IP server has received 750944 bytes of data
,2015-11-21T12:38:50.944Z SendDataTCPServer.js: TCP/IP server has received 772768 bytes of data
,2015-11-21T12:38:51.204Z SendDataTCPServer.js: TCP/IP server has received 780704 bytes of data
,2015-11-21T12:38:51.219Z SendDataTCPServer.js: TCP/IP server has received 787648 bytes of data
,2015-11-21T12:38:51.232Z SendDataTCPServer.js: TCP/IP server has received 791616 bytes of data
,2015-11-21T12:38:51.257Z SendDataTCPServer.js: TCP/IP server has received 795584 bytes of data
,2015-11-21T12:38:51.282Z SendDataTCPServer.js: TCP/IP server has received 797568 bytes of data
,2015-11-21T12:38:51.298Z SendDataTCPServer.js: TCP/IP server has received 805504 bytes of data
,2015-11-21T12:38:51.316Z SendDataTCPServer.js: TCP/IP server has received 811456 bytes of data
,2015-11-21T12:38:51.331Z SendDataTCPServer.js: TCP/IP server has received 820384 bytes of data
,2015-11-21T12:38:51.347Z SendDataTCPServer.js: TCP/IP server has received 830304 bytes of data
,2015-11-21T12:38:51.362Z SendDataTCPServer.js: TCP/IP server has received 847168 bytes of data
,2015-11-21T12:38:51.378Z SendDataTCPServer.js: TCP/IP server has received 866016 bytes of data
,2015-11-21T12:38:51.395Z SendDataTCPServer.js: TCP/IP server has received 878912 bytes of data
,2015-11-21T12:38:51.411Z SendDataTCPServer.js: TCP/IP server has received 892800 bytes of data
,2015-11-21T12:38:51.429Z SendDataTCPServer.js: TCP/IP server has received 906688 bytes of data
,2015-11-21T12:38:51.444Z SendDataTCPServer.js: TCP/IP server has received 917600 bytes of data
,2015-11-21T12:38:51.458Z SendDataTCPServer.js: TCP/IP server has received 940416 bytes of data
,2015-11-21T12:38:51.473Z SendDataTCPServer.js: TCP/IP server has received 956288 bytes of data
,2015-11-21T12:38:51.719Z SendDataTCPServer.js: TCP/IP server has received 962240 bytes of data
,2015-11-21T12:38:51.733Z SendDataTCPServer.js: TCP/IP server has received 964224 bytes of data
,2015-11-21T12:38:51.759Z SendDataTCPServer.js: TCP/IP server has received 966208 bytes of data
,2015-11-21T12:38:51.776Z SendDataTCPServer.js: TCP/IP server has received 974144 bytes of data
,2015-11-21T12:38:51.791Z SendDataTCPServer.js: TCP/IP server has received 982080 bytes of data
,2015-11-21T12:38:51.806Z SendDataTCPServer.js: TCP/IP server has received 991008 bytes of data
,2015-11-21T12:38:51.821Z SendDataTCPServer.js: TCP/IP server has received 999936 bytes of data
,2015-11-21T12:38:51.834Z SendDataTCPServer.js: TCP/IP server has received 1000002 bytes of data
,2015-11-21 13:38:51.865 ThaliTest[1131:897440] server session: not connected Apple-Iphone5-1_PT759
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-21 13:38:52.792 ThaliTest[1131:896363] jxcore: stopBroadcasting
2015-11-21 13:38:52.793 ThaliTest[1131:896363] THEMultipeerSession stopping peer
2015-11-21 13:38:52.794 ThaliTest[1131:896363] multipeer session: stop timer
2015-11-21 13:38:52.794, ThaliTest[1131:896363] server session: disconnect
2015-11-21 13:38:52.795 ThaliTest[1131:896363] server session: stateChange:2->0 Apple-Iphone6-1_PT8382
,2015-11-21 13:38:52.802 ThaliTest[1131:896363] server session: disconnect
2015-11-21 13:38:52.803 ThaliTest[1131:896363] server session: stateChange:2->0 Apple-Iphone5-1_PT759
,2015-11-21 13:38:52.807 ThaliTest[1131:896363] server session: disconnect
,2015-11-21 13:38:52.808 ThaliTest[1131:896363] server session: stateChange:2->0 Apple-IpadAir2-1_PT5427
,2015-11-21 13:38:53.086 ThaliTest[1131:896363] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-21T12:38:53.105Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T12:38:53.107Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T12:38:53.108Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-21T12:38:53.109Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT5427.N/zz4w==\",\"time\":5651,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8382.HGUadg==\",\"time\":6347,\",result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT759.cZHSYA==\",\"time\":8528,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT8264./5qd6,Q==\",\"time\":3824,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8264./5qd6Q==\",\"time\":5219,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8382.HGUadg==\",\"time\":5413,\"result\":\"OK\",\"connections\":1},{\"n,ame\":\"Apple-IpadAir2-1_PT5427.N/zz4w==\",\"time\":5651,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8382.HGUadg==\",\"time\":6347,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8382.HGUadg==\",\"time\":7858,\"res,ult\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT5427.N/zz4w==\",\"time\":8446,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT759.cZHSYA==\",\"time\":8528,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_P,T8264./5qd6Q==\",\"time\":8989,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT759.cZHSYA==\",\"time\":10418,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT759.cZHSYA==\",\"time\":11883,\"result\":\"OK\",\"connections,\":1},{\"name\":\"Apple-IpadAir2-1_PT5427.N/zz4w==\",\"time\":12622,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received

```
