#### Test 5119382166efe78_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5119382166efe78/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A6C61A4A-39BA-494A-A96F-F0095AE181F2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A6C61A4A-39BA-494A-A96F-F0095AE181F2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5119382166efe78/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5119382166efe78/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B1C4BA0E-3EF1-452F-9D0A-75BFEC9909E1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50305"
,(lldb)     command script import "/tmp/A6C61A4A-39BA-494A-A96F-F0095AE181F2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-19 09:51:10.409 ThaliTest[865:638338] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/14FA56BE-2534-4530-A33F-B1D1B3983CFF/Library/Cookies/Cookies.binarycookies
,2015-11-19 09:51:10.851 ThaliTest[865:638338] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-19 09:51:10.853 ThaliTest[865:638338] Multi-tasking -> Device: YES, App: YES
,2015-11-19 09:51:10.862 ThaliTest[865:638338] Unlimited access to network resources
,2015-11-19 09:51:10.869 ThaliTest[865:638338] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-19 09:51:14.870 ThaliTest[865:638338] Resetting plugins due to page load.
,2015-11-19 09:51:15.155 ThaliTest[865:638338] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/B1C4BA0E-3EF1-452F-9D0A-75BFEC9909E1/ThaliTest.app/www/index.html
,2015-11-19 09:51:15.346 ThaliTest[865:638338] JXcore Cordova plugin initializing
2015-11-19 09:51:15.347 ThaliTest[865:638459] JXcore instance initializing
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
toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,my name is : Apple-Iphone5s-1_PT5906
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
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found inter,faceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners,":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":,"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:525,3:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Obje,ct]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: en0
-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
-iface: IPv4 is internal : false, has ip: 192.168.1.106
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceiv,ed":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: en0
,-iface: IPv6 is internal : false, has ip: fe80::14a1:5253:204d:5e3a
,-iface: IPv4 is internal : false, has ip: 192.168.1.106
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"1000000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":2,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"500000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 54992
2015-11-19 10:02:07.866 ThaliTest[865:638459] jxcore: startBroadcasting
,2015-11-19 10:02:07.881 ThaliTest[865:638459] server: starting Apple-Iphone5s-1_PT5906.NMJf0A==
,2015-11-19 10:02:07.884 ThaliTest[865:638459] multipeer session: start timer: 0x19fe1fc0
,2015-11-19 10:02:07.905 ThaliTest[865:638459] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT5906
,2015-11-19 10:02:07.906 ThaliTest[865:638459] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,TCP/IP server  is bound to : undefined
,2015-11-19 10:02:08.114 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:09.054 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4426.kvRdCA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-19 10:02:13.126 ThaliTest[865:638459] jxcore: disconnect
2015-11-19 10:02:13.127 ThaliTest[865:638459] jxcore: disconnect: fail
Connect (retry count 0) to peer Apple-Iphone6-1_PT5791.6xWUmg== with availability status: true
,do connect now
,2015-11-19 10:02:13.129 ThaliTest[865:638459] jxcore: connect Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:02:13.131 ThaliTest[865:638459] client session: connect
,2015-11-19 10:02:13.132 ThaliTest[865:638459] client session: stateChange:0->1 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:16.684 ThaliTest[865:639334] client session: connected
2015-11-19 10:02:16.685 ThaliTest[865:639334] client session: stateChange:1->2 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:17.100 ThaliTest[865:639334] client session: fireConnectCallback: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:02:17.101 ThaliTest[865:639334] jxcore: connect: success
CLIENT connected to 54996, error: null
,CLIENT starting client 
,2015-11-19 10:02:17.107 ThaliTest[865:638338] client: relay established
2015-11-19 10:02:17.108 ThaliTest[865:638338] client: new accepted socket: 0x19e6fd10
,CLIENT now sending 1000000 bytes of data
,CLIENT is data received : 0
,CLIENT is data received : 0
,CLIENT is data received : 10000
,CLIENT is data received : 10000
,CLIENT is data received : 10000
,CLIENT is data received : 10000
,CLIENT is data received : 20000
,CLIENT is data received : 30000
,CLIENT is data received : 40000
,CLIENT is data received : 50000
,CLIENT is data received : 60000
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:02:28.950 ThaliTest[865:638338] client: socket closed
----------------- closeClientSocket
2015-11-19 10:02:28.950 ThaliTest[865:638338] client relay: socket disconnected
CLIENT is closed
2015-11-19 10:02:28.951 Th,aliTest[865:638338] client relay: 0x19e6fd10 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19e74e20 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:02:28.952 ThaliTest[,865:638338] client session: socket closed: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:28.952 ThaliTest[865:638338] client session: onLinkFailure: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:02:28.953 ThaliTest[865:638338] client session: disconnect
2015-11-19 10:02:28.953 ThaliTest[865:638338] client session: stateChang,e:2->0 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:28.955 ThaliTest[865:638338] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT5791.6xWUmg==
,re-try now : Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:37.906 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:02:37.930 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:02:37.931 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:38.956 ThaliTest[865:638459] jxcore: disconnect
2015-11-19 10:02:38.956 ThaliTest[865:638459] jxcore: disconnect: fail
Connect (retry count 1) to peer Apple-Iphone6-1_PT5791.6xWUmg== with availability status: true
do connect now
,2015-11-19 10:02:38.958 ThaliTest[865:638459] jxcore: connect Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:38.959 ThaliTest[865:638459] client session: connect
2015-11-19 10:02:38.960 ThaliTest[865:638459] client session: stateChange:0->1 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:41.379 ThaliTest[865:639383] client session: connected
2015-11-19 10:02:41.379 ThaliTest[865:639383] client session: stateChange:1->2 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:41.475 ThaliTest[865:639383] client session: fireConnectCallback: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:02:41.476 ThaliTest[865:639383] jxcore: connect: success
CLIENT connected to 55001, error: null
CLIENT starting client 
,2015-11-19 10:02:41.480 ThaliTest[865:638338] client: relay established
2015-11-19 10:02:41.481 ThaliTest[865:638338] client: new accepted socket: 0x19ef37f0
,CLIENT now sending 940000 bytes of data
,CLIENT is data received : 60000
,CLIENT is data received : 60000
,CLIENT is data received : 70000
,CLIENT is data received : 80000
,CLIENT is data received : 80000
,CLIENT is data received : 90000
,CLIENT is data received : 100000
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
----------------- closeClientSocket
2015-11-19 10:02:52.942 ThaliTest[865:638338] client: socket closed
CLIENT is closed
2015-11-19 10:02:52.943 ThaliTest[865:638338] client relay: socket disconnected
,2015-11-19 10:02:52.944 ThaliTest[865:638338] client relay: 0x19ef37f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x15e6c290 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-,19 10:02:52.945 ThaliTest[865:638338] client session: socket closed: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:52.945 ThaliTest[865:638338] client session: onLinkFailure: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:02:52.946 ThaliTest[865:638338] client session: disconnect
,2015-11-19 10:02:52.947 ThaliTest[865:638338] client session: stateChange:2->0 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:02:52.948 ThaliTest[865:638338] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT5791.6xWUmg==
,re-try now : Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:02.953 ThaliTest[865:638459] jxcore: disconnect
2015-11-19 10:03:02.954 ThaliTest[865:638459] jxcore: disconnect: fail
Connect (retry count 2) to peer Apple-Iphone6-1_PT5791.6xWUmg== with availability status: true
do connect now
,2015-11-19 10:03:02.956 ThaliTest[865:638459] jxcore: connect Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:02.956 ThaliTest[865:638459] client session: connect
,2015-11-19 10:03:02.957 ThaliTest[865:638459] client session: stateChange:0->1 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:05.512 ThaliTest[865:639397] client session: connected
2015-11-19 10:03:05.512 ThaliTest[865:639397] client session: stateChange:1->2 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:05.518 ThaliTest[865:639383] client session: fireConnectCallback: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:05.519 ThaliTest[865:639383] jxcore: connect: success
CLIENT connected to 55005, error: null
CLIENT starting client 
,2015-11-19 10:03:05.524 ThaliTest[865:638338] client: relay established
2015-11-19 10:03:05.525 ThaliTest[865:638338] client: new accepted socket: 0x19e77ca0
,CLIENT now sending 900000 bytes of data
,CLIENT is data received : 100000
,CLIENT is data received : 100000
,CLIENT is data received : 100000
,CLIENT is data received : 110000
,CLIENT is data received : 120000
,CLIENT is data received : 120000
,CLIENT is data received : 120000
,2015-11-19 10:03:07.906 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:03:07.949 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:03:07.951 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:03:16.626 ThaliTest[865:638338] client: socket closed
----------------- closeClientSocket
2015-11-19 10:03:16.627 ThaliTest[865:638338] client relay: socket disconnected
,2015-11-19 10:03:16.628 ThaliTest[865:638338] client relay: 0x19e77ca0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19edab80 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:03:16.628 ThaliTest[865:638338] client session: socket closed: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:16.629 ThaliTest[865:638338] client session: onLinkFailure: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:16.629 ThaliTest[865:638338] client session: disconnect
,2015-11-19 10:03:16.630 ThaliTest[865:638338] client session: stateChange:2->0 Apple-Iphone6-1_PT5791.6xWUmg==
CLIENT is closed
,2015-11-19 10:03:16.633 ThaliTest[865:638338] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT5791.6xWUmg==
,re-try now : Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:26.643 ThaliTest[865:638459] jxcore: disconnect
2015-11-19 10:03:26.644 ThaliTest[865:638459] jxcore: disconnect: fail
Connect (retry count 3) to peer Apple-Iphone6-1_PT5791.6xWUmg== with availability status: true
do connect now
,2015-11-19 10:03:26.646 ThaliTest[865:638459] jxcore: connect Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:26.647 ThaliTest[865:638459] client session: connect
,2015-11-19 10:03:26.648 ThaliTest[865:638459] client session: stateChange:0->1 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:32.196 ThaliTest[865:639567] client session: connected
2015-11-19 10:03:32.197 ThaliTest[865:639567] client session: stateChange:1->2 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:32.204 ThaliTest[865:639453] client session: fireConnectCallback: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:32.205 ThaliTest[865:639453] jxcore: connect: success
CLIENT connected to 55010, error: null
CLIENT starting client 
,2015-11-19 10:03:32.211 ThaliTest[865:638338] client: relay established
2015-11-19 10:03:32.212 ThaliTest[865:638338] client: new accepted socket: 0x19e6fd10
,CLIENT now sending 880000 bytes of data
,CLIENT is data received : 120000
,CLIENT is data received : 120000
,CLIENT is data received : 120000
,CLIENT is data received : 130000
,CLIENT is data received : 140000
,CLIENT is data received : 150000
,CLIENT is data received : 160000
,CLIENT is data received : 170000
,CLIENT is data received : 180000
,CLIENT is data received : 180000
,2015-11-19 10:03:37.904 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:03:37.925 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:03:37.926 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
----------------- closeClientSocket
2015-11-19 10:03:43.231 ThaliTest[865:638338] client: socket closed
CLIENT is closed
,2015-11-19 10:03:43.232 ThaliTest[865:638338] client relay: socket disconnected
2015-11-19 10:03:43.234 ThaliTest[865:638338] client relay: 0x19e6fd10 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" Use,rInfo=0x15e6c210 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:03:43.234 ThaliTest[865:638338] client session: socket closed: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:43.235 ThaliTest[865:638338] client session: onLinkFailu,re: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:43.235 ThaliTest[865:638338] client session: disconnect
2015-11-19 10:03:43.236 ThaliTest[865:638338] client session: stateChange:2->0 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:43.239 ThaliTest[865:638338] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT5791.6xWUmg==
,re-try now : Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:53.246 ThaliTest[865:638459] jxcore: disconnect
2015-11-19 10:03:53.247 ThaliTest[865:638459] jxcore: disconnect: fail
Connect (retry count 4) to peer Apple-Iphone6-1_PT5791.6xWUmg== with availability status: true
do connect now
,2015-11-19 10:03:53.249 ThaliTest[865:638459] jxcore: connect Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:53.249 ThaliTest[865:638459] client session: connect
,2015-11-19 10:03:53.250 ThaliTest[865:638459] client session: stateChange:0->1 Apple-Iphone6-1_PT5791.6xWUmg==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,Turning Wifi off
,Warning: iOS does not support ToggleWiFi
,We could not turn wifi off! - Warning: iOS does not support ToggleWiFi
,Turning Wifi back on
,Warning: iOS does not support ToggleWiFi
,We could turn wifi back on! - Warning: iOS does not support ToggleWiFi
,toggleWiFi finished
,2015-11-19 10:03:56.736 ThaliTest[865:639649] client session: connected
2015-11-19 10:03:56.737 ThaliTest[865:639649] client session: stateChange:1->2 Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:03:56.744 ThaliTest[865:639678] client session: fireConnectCallback: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:03:56.745 ThaliTest[865:639678] jxcore: connect: success
CLIENT connected to 55016, error: null
,CLIENT starting client 
,2015-11-19 10:03:56.750 ThaliTest[865:638338] client: relay established
2015-11-19 10:03:56.750 ThaliTest[865:638338] client: new accepted socket: 0x15e98550
,CLIENT now sending 820000 bytes of data
,CLIENT is data received : 180000
,CLIENT is data received : 180000
,CLIENT is data received : 180000
,CLIENT is data received : 190000
,CLIENT is data received : 200000
,CLIENT is data received : 210000
,CLIENT is data received : 210000
,CLIENT is data received : 220000
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,Receiving data timeout now
CLIENT closeClientSocket
,2015-11-19 10:04:07.554 ThaliTest[865:638338] client: socket closed
2015-11-19 10:04:07.555 ThaliTest[865:638338] client relay: socket disconnected
CLIENT Stop now
Stop data retrieving timer
2015-11-19 10:04:07.556 ThaliTest[865:638338] client relay: 0,x15e98550 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x15e2c3b0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:04:07.556 ThaliTest[865:638338] client session: socket ,closed: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:04:07.557 ThaliTest[865:638338] client session: onLinkFailure: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:04:07.557 ThaliTest[865:638338] client session: disconnect
2015-11-19 10:04:07.558 ThaliTe,st[865:638338] client session: stateChange:2->0 Apple-Iphone6-1_PT5791.6xWUmg==
CLIENT Stop now
---- round done--------
device[2]: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:04:07.560 ThaliTest[865:638338] client session: fireConnectionErrorEvent: ,Apple-Iphone6-1_PT5791.6xWUmg==
----------------- closeClientSocket
,CLIENT is closed
,2015-11-19 10:04:07.904 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:04:08.010 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:04:08.012 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
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
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,2015-11-19 10:04:12.469 ThaliTest[865:638338] multipeer session: reset timer
2015-11-19 10:04:12.470 ThaliTest[865:638338] multipeer session: stop timer
2015-11-19 10:04:12.471 ThaliTest[865:638338] multipeer session: start timer: 0x19fe1fc0
2015-11-19 ,10:04:12.472 ThaliTest[865:638338] server session: connect
2015-11-19 10:04:12.472 ThaliTest[865:638338] server session: stateChange:0->1 Apple-IpadAir2-1_PT4426
,2015-11-19 10:04:12.484 ThaliTest[865:638338] server: accepting invitation Apple-IpadAir2-1_PT4426
,2015-11-19 10:04:12.576 ThaliTest[865:638459] jxcore: disconnect
2015-11-19 10:04:12.577 ThaliTest[865:638459] jxcore: disconnect: fail
Connect (retry count 0) to peer Apple-IpadAir2-1_PT4426.kvRdCA== with availability status: true
do connect now
,2015-11-19 10:04:12.578 ThaliTest[865:638459] jxcore: connect Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:04:12.579 ThaliTest[865:638459] client session: connect
2015-11-19 10:04:12.580 ThaliTest[865:638459] client session: stateChange:0->1 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:04:15.047 ThaliTest[865:639674] server session: connected
2015-11-19 10:04:15.048 ThaliTest[865:639674] server session: stateChange:1->2 Apple-IpadAir2-1_PT4426
,2015-11-19 10:04:15.059 ThaliTest[865:638338] server relay: connected (to port: 54992)
,TCP/IP server connected
,TCP/IP server has received 2190 bytes of data
,TCP/IP server has received 24090 bytes of data
,TCP/IP server has received 43232 bytes of data
,TCP/IP server has received 61320 bytes of data
,TCP/IP server has received 83220 bytes of data
,2015-11-19 10:04:15.594 ThaliTest[865:639683] client session: connected
2015-11-19 10:04:15.597 ThaliTest[865:639683] client session: stateChange:1->2 Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:04:15.605 ThaliTest[865:639683] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:04:15.606 ThaliTest[865:639683] jxcore: connect: success
TCP/IP server has received 89790 bytes of data
,TCP/IP server has received 91980 bytes of data
,CLIENT connected to 55033, error: null
CLIENT starting client 
,2015-11-19 10:04:15.621 ThaliTest[865:638338] client: relay established
2015-11-19 10:04:15.622 ThaliTest[865:638338] client: new accepted socket: 0x19e9c230
,TCP/IP server has received 113880 bytes of data
CLIENT now sending 1000000 bytes of data
,TCP/IP server has received 244952 bytes of data
,TCP/IP server has received 376024 bytes of data
,TCP/IP server has received 507096 bytes of data
,TCP/IP server has received 638168 bytes of data
,TCP/IP server has received 769240 bytes of data
,TCP/IP server has received 900312 bytes of data
,TCP/IP server has received 1000002 bytes of data
,CLIENT is data received : 0
,CLIENT is data received : 0
,CLIENT is data received : 0
,Receiving data timeout now
CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,----------------- closeClientSocket
CLIENT is closed
2015-11-19 10:04:26.380 ThaliTest[865:638338] client: socket closed
2015-11-19 10:04:26.382 ThaliTest[865:638338] client relay: socket disconnected
2015-11-19 10:04:26.383 ThaliTest[865:638338] clien,t relay: 0x19e9c230 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x199a4930 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-19 10:04:26.384 ThaliTest[865:638338] client sessio,n: socket closed: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:04:26.384 ThaliTest[865:638338] client session: onLinkFailure: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:04:26.385 ThaliTest[865:638338] client session: disconnect
2015-11-19 10:04:26,.385 ThaliTest[865:638338] client session: stateChange:2->0 Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:04:26.387 ThaliTest[865:638338] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:04:26.607 ThaliTest[865:639674] server session: not connected Apple-IpadAir2-1_PT4426
,2015-11-19 10:04:26.800 ThaliTest[865:638338] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:04:26.801 ThaliTest[865:638338] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:04:27.654 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:04:29.159 ThaliTest[865:638338] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:04:29.160 ThaliTest[865:638338] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:04:29.685 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
,re-try now : Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:04:36.395 ThaliTest[865:638459] jxcore: disconnect
2015-11-19 10:04:36.396 ThaliTest[865:638459] jxcore: disconnect: fail
Connect (retry count 1) to peer Apple-IpadAir2-1_PT4426.kvRdCA== with availability status: true
do connect now
,2015-11-19 10:04:36.397 ThaliTest[865:638459] jxcore: connect Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:04:36.398 ThaliTest[865:638459] client session: connect
,2015-11-19 10:04:36.399 ThaliTest[865:638459] client session: stateChange:0->1 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:04:37.034 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:04:37.581 ThaliTest[865:638338] multipeer session: reset timer
2015-11-19 10:04:37.582 ThaliTest[865:638338] multipeer session: stop timer
2015-11-19 10:04:37.582 ThaliTest[865:638338] multipeer session: start timer: 0x19fe1fc0
2015-11-19 ,10:04:37.583 ThaliTest[865:638338] server: disconnecting to refresh session (Apple-IpadAir2-1_PT4426)
2015-11-19 10:04:37.583 ThaliTest[865:638338] server session: disconnect
2015-11-19 10:04:37.584 ThaliTest[865:638338] server session: stateChange:2->0 ,Apple-IpadAir2-1_PT4426
2015-11-19 10:04:37.587 ThaliTest[865:638338] server session: connect
2015-11-19 10:04:37.588 ThaliTest[865:638338] server session: stateChange:0->1 Apple-IpadAir2-1_PT4426
,TCP/IP server is ended
,TCP/IP server is close
,2015-11-19 10:04:37.610 ThaliTest[865:638338] server: accepting invitation Apple-IpadAir2-1_PT4426
,2015-11-19 10:04:39.686 ThaliTest[865:639904] client session: connected
2015-11-19 10:04:39.687 ThaliTest[865:639904] client session: stateChange:1->2 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:04:39.695 ThaliTest[865:639674] client session: fireConnectCallback: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:04:39.696 ThaliTest[865:639674] jxcore: connect: success
CLIENT connected to 55036, error: null
CLIENT starting client 
,2015-11-19 10:04:39.701 ThaliTest[865:638338] client: relay established
2015-11-19 10:04:39.702 ThaliTest[865:638338] client: new accepted socket: 0x15d754b0
,CLIENT now sending 1000000 bytes of data
,2015-11-19 10:04:40.267 ThaliTest[865:639904] server session: connected
2015-11-19 10:04:40.268 ThaliTest[865:639904] server session: stateChange:1->2 Apple-IpadAir2-1_PT4426
,TCP/IP server connected
,2015-11-19 10:04:40.319 ThaliTest[865:638338] server relay: connected (to port: 54992)
CLIENT is data received : 0
,TCP/IP server has received 6570 bytes of data
,TCP/IP server has received 26280 bytes of data
,TCP/IP server has received 63510 bytes of data
,TCP/IP server has received 111690 bytes of data
,TCP/IP server has received 161918 bytes of data
,TCP/IP server has received 203670 bytes of data
,TCP/IP server has received 232140 bytes of data
,TCP/IP server has received 271276 bytes of data
,TCP/IP server has received 310980 bytes of data
,TCP/IP server has received 354780 bytes of data
,TCP/IP server has received 409530 bytes of data
,TCP/IP server has received 457710 bytes of data
,TCP/IP server has received 497130 bytes of data
,TCP/IP server has received 549690 bytes of data
,CLIENT is data received : 10000
,TCP/IP server has received 578160 bytes of data
,CLIENT is data received : 10000
,TCP/IP server has received 617580 bytes of data
,TCP/IP server has received 650430 bytes of data
,TCP/IP server has received 709560 bytes of data
,TCP/IP server has received 753360 bytes of data
,TCP/IP server has received 788400 bytes of data
,TCP/IP server has received 843150 bytes of data
,TCP/IP server has received 886950 bytes of data
,TCP/IP server has received 948270 bytes of data
,TCP/IP server has received 961410 bytes of data
,TCP/IP server has received 981120 bytes of data
,TCP/IP server has received 990002 bytes of data
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
2015-11-19 10:04:50.999 ThaliTest[865:638338] client: socket closed
----------------- closeClientSocket
2015-11-19 10:04:51.000 ThaliTest[865:638338] client relay: socket disconnected
CLIENT is closed
2015-11-19 10:04:51.000 Th,aliTest[865:638338] client relay: 0x15d754b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19cf6cc0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:04:51.001 ThaliTest[865:638338] client session: socket closed: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:04:51.002 ThaliTest[865:638338] client session: onLinkFailure: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:04:51.002 ThaliTest[,865:638338] client session: disconnect
,2015-11-19 10:04:51.003 ThaliTest[865:638338] client session: stateChange:2->0 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:04:51.004 ThaliTest[865:638338] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:04:51.241 ThaliTest[865:639943] server session: not connected Apple-IpadAir2-1_PT4426
,re-try now : Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:04:58.186 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:05:01.007 ThaliTest[865:638459] jxcore: disconnect
2015-11-19 10:05:01.008 ThaliTest[865:638459] jxcore: disconnect: fail
Connect (retry count 2) to peer Apple-IpadAir2-1_PT4426.kvRdCA== with availability status: true
do connect now
,2015-11-19 10:05:01.010 ThaliTest[865:638459] jxcore: connect Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:01.011 ThaliTest[865:638459] client session: connect
2015-11-19 10:05:01.011 ThaliTest[865:638459] client session: stateChange:0->1 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:01.690 ThaliTest[865:638338] multipeer session: reset timer
2015-11-19 10:05:01.691 ThaliTest[865:638338] multipeer session: stop timer
2015-11-19 10:05:01.691 ThaliTest[865:638338] multipeer session: start timer: 0x19fe1fc0
2015-11-19 ,10:05:01.692 ThaliTest[865:638338] server: disconnecting to refresh session (Apple-IpadAir2-1_PT4426)
2015-11-19 10:05:01.693 ThaliTest[865:638338] server session: disconnect
2015-11-19 10:05:01.693 ThaliTest[865:638338] server session: stateChange:2->0 ,Apple-IpadAir2-1_PT4426
2015-11-19 10:05:01.698 ThaliTest[865:638338] server session: connect
2015-11-19 10:05:01.698 ThaliTest[865:638338] server session: stateChange:0->1 Apple-IpadAir2-1_PT4426
,TCP/IP server is ended
TCP/IP server is close
2015-11-19 10:05:01.718 ThaliTest[865:638338] server: accepting invitation Apple-IpadAir2-1_PT4426
,2015-11-19 10:05:03.767 ThaliTest[865:639970] client session: connected
2015-11-19 10:05:03.768 ThaliTest[865:639970] client session: stateChange:1->2 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:03.774 ThaliTest[865:639990] client session: fireConnectCallback: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:05:03.775 ThaliTest[865:639990] jxcore: connect: success
CLIENT connected to 55040, error: null
CLIENT starting client 
,2015-11-19 10:05:03.780 ThaliTest[865:638338] client: relay established
2015-11-19 10:05:03.781 ThaliTest[865:638338] client: new accepted socket: 0x19d59c60
,CLIENT now sending 990000 bytes of data
,CLIENT is data received : 10000
,2015-11-19 10:05:04.375 ThaliTest[865:639970] server session: connected
2015-11-19 10:05:04.376 ThaliTest[865:639970] server session: stateChange:1->2 Apple-IpadAir2-1_PT4426
,TCP/IP server connected
,CLIENT is data received : 10000
,2015-11-19 10:05:04.436 ThaliTest[865:638338] server relay: connected (to port: 54992)
,CLIENT is data received : 10000
,TCP/IP server has received 6570 bytes of data
,TCP/IP server has received 28470 bytes of data
,TCP/IP server has received 63510 bytes of data
,TCP/IP server has received 105120 bytes of data
,TCP/IP server has received 153300 bytes of data
,TCP/IP server has received 190530 bytes of data
,CLIENT is data received : 20000
,TCP/IP server has received 229950 bytes of data
,TCP/IP server has received 269370 bytes of data
,TCP/IP server has received 321930 bytes of data
,TCP/IP server has received 367920 bytes of data
,TCP/IP server has received 413910 bytes of data
,TCP/IP server has received 451140 bytes of data
,TCP/IP server has received 492750 bytes of data
,TCP/IP server has received 519030 bytes of data
,TCP/IP server has received 556260 bytes of data
,CLIENT is data received : 30000
,TCP/IP server has received 586920 bytes of data
,TCP/IP server has received 604440 bytes of data
,TCP/IP server has received 646050 bytes of data
,TCP/IP server has received 696420 bytes of data
,TCP/IP server has received 748980 bytes of data
,TCP/IP server has received 784020 bytes of data
,CLIENT is data received : 40000
,TCP/IP server has received 834390 bytes of data
,TCP/IP server has received 884760 bytes of data
,TCP/IP server has received 941700 bytes of data
,TCP/IP server has received 980002 bytes of data
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,----------------- closeClientSocket
2015-11-19 10:05:15.170 ThaliTest[865:638338] client: socket closed
2015-11-19 10:05:15.171 ThaliTest[865:638338] client relay: socket disconnected
CLIENT is closed
,2015-11-19 10:05:15.171 ThaliTest[865:638338] client relay: 0x19d59c60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19c05db0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-,19 10:05:15.172 ThaliTest[865:638338] client session: socket closed: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:15.173 ThaliTest[865:638338] client session: onLinkFailure: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:05:15.173 ThaliTest[865:638338] client session: disconnect
,2015-11-19 10:05:15.174 ThaliTest[865:638338] client session: stateChange:2->0 Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:05:15.176 ThaliTest[865:638338] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:15.353 ThaliTest[865:639991] server session: not connected Apple-IpadAir2-1_PT4426
,re-try now : Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:25.174 ThaliTest[865:638459] jxcore: disconnect
2015-11-19 10:05:25.175 ThaliTest[865:638459] jxcore: disconnect: fail
Connect (retry count 3) to peer Apple-IpadAir2-1_PT4426.kvRdCA== with availability status: true
do connect now
,2015-11-19 10:05:25.177 ThaliTest[865:638459] jxcore: connect Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:25.178 ThaliTest[865:638459] client session: connect
,2015-11-19 10:05:25.179 ThaliTest[865:638459] client session: stateChange:0->1 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:25.792 ThaliTest[865:638338] multipeer session: reset timer
2015-11-19 10:05:25.793 ThaliTest[865:638338] multipeer session: stop timer
2015-11-19 10:05:25.793 ThaliTest[865:638338] multipeer session: start timer: 0x19fe1fc0
2015-11-19 ,10:05:25.794 ThaliTest[865:638338] server: disconnecting to refresh session (Apple-IpadAir2-1_PT4426)
2015-11-19 10:05:25.795 ThaliTest[865:638338] server session: disconnect
2015-11-19 10:05:25.795 ThaliTest[865:638338] server session: stateChange:2->0 ,Apple-IpadAir2-1_PT4426
2015-11-19 10:05:25.804 ThaliTest[865:638338] server session: connect
TCP/IP server is ended
TCP/IP server is close
2015-11-19 10:05:25.804 ThaliTest[865:638338] server session: stateChange:0->1 Apple-IpadAir2-1_PT4426
,2015-11-19 10:05:25.825 ThaliTest[865:638338] server: accepting invitation Apple-IpadAir2-1_PT4426
,2015-11-19 10:05:27.900 ThaliTest[865:640041] client session: connected
2015-11-19 10:05:27.901 ThaliTest[865:640041] client session: stateChange:1->2 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:27.907 ThaliTest[865:639991] client session: fireConnectCallback: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:05:27.908 ThaliTest[865:639991] jxcore: connect: success
CLIENT connected to 55044, error: null
CLIENT starting client 
,2015-11-19 10:05:27.915 ThaliTest[865:638338] client: relay established
2015-11-19 10:05:27.915 ThaliTest[865:638338] client: new accepted socket: 0x199e64d0
,CLIENT now sending 960000 bytes of data
,2015-11-19 10:05:28.487 ThaliTest[865:639991] server session: connected
2015-11-19 10:05:28.489 ThaliTest[865:639991] server session: stateChange:1->2 Apple-IpadAir2-1_PT4426
,TCP/IP server connected
,2015-11-19 10:05:28.557 ThaliTest[865:638338] server relay: connected (to port: 54992)
,CLIENT is data received : 40000
,TCP/IP server has received 15330 bytes of data
,TCP/IP server has received 65700 bytes of data
,TCP/IP server has received 113880 bytes of data
,TCP/IP server has received 157680 bytes of data
,TCP/IP server has received 201480 bytes of data
,TCP/IP server has received 240900 bytes of data
,TCP/IP server has received 280178 bytes of data
,TCP/IP server has received 317550 bytes of data
,TCP/IP server has received 356970 bytes of data
,TCP/IP server has received 398438 bytes of data
,TCP/IP server has received 435810 bytes of data
,TCP/IP server has received 479610 bytes of data
,TCP/IP server has received 516840 bytes of data
,TCP/IP server has received 562830 bytes of data
,TCP/IP server has received 600060 bytes of data
,CLIENT is data received : 50000
,TCP/IP server has received 639480 bytes of data
,CLIENT is data received : 60000
,TCP/IP server has received 685470 bytes of data
,TCP/IP server has received 738030 bytes of data
,TCP/IP server has received 786210 bytes of data
,CLIENT is data received : 70000
,TCP/IP server has received 821250 bytes of data
,TCP/IP server has received 869430 bytes of data
,TCP/IP server has received 911040 bytes of data
,TCP/IP server has received 930002 bytes of data
,2015-11-19 10:05:29.573 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:05:37.974 ThaliTest[865:638338] multipeer session: reset timer
2015-11-19 10:05:37.974 ThaliTest[865:638338] multipeer session: stop timer
2015-11-19 10:05:37.975 ThaliTest[865:638338] multipeer session: start timer: 0x19fe1fc0
2015-11-19 ,10:05:37.976 ThaliTest[865:638338] server session: connect
2015-11-19 10:05:37.976 ThaliTest[865:638338] server session: stateChange:0->1 Apple-Iphone6-1_PT5791
,2015-11-19 10:05:37.984 ThaliTest[865:638338] server: accepting invitation Apple-Iphone6-1_PT5791
,2015-11-19 10:05:38.152 ThaliTest[865:638338] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:05:38.153 ThaliTest[865:638338] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:05:38.354 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
,Receiving data timeout now
,CLIENT closeClientSocket
,tryAgain afer: 5000 ms.
,----------------- closeClientSocket
2015-11-19 10:05:39.191 ThaliTest[865:638338] client: socket closed
,2015-11-19 10:05:39.192 ThaliTest[865:638338] client relay: socket disconnected
,2015-11-19 10:05:39.193 ThaliTest[865:638338] client relay: 0x199e64d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19c25c00 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-19 10:05:39.194 ThaliTest[865:638338] client session: socket closed: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:39.195 ThaliTest[865:638338] client session: onLinkFailure: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:05:39.195 ThaliTest[865:638338] client session: disconnect
,2015-11-19 10:05:39.196 ThaliTest[865:638338] client session: stateChange:2->0 Apple-IpadAir2-1_PT4426.kvRdCA==
,CLIENT is closed
,2015-11-19 10:05:39.199 ThaliTest[865:638338] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:42.052 ThaliTest[865:640037] server session: connected
2015-11-19 10:05:42.053 ThaliTest[865:640037] server session: stateChange:1->2 Apple-Iphone6-1_PT5791
,2015-11-19 10:05:42.062 ThaliTest[865:638338] server relay: connected (to port: 54992)
TCP/IP server connected
,TCP/IP server has received 10950 bytes of data
,TCP/IP server has received 30660 bytes of data
,TCP/IP server has received 52560 bytes of data
,TCP/IP server has received 67890 bytes of data
,TCP/IP server has received 83220 bytes of data
,TCP/IP server has received 98408 bytes of data
,TCP/IP server has received 120450 bytes of data
,TCP/IP server has received 140160 bytes of data
,TCP/IP server has received 166440 bytes of data
,TCP/IP server has received 192720 bytes of data
,TCP/IP server has received 216810 bytes of data
,TCP/IP server has received 238710 bytes of data
,TCP/IP server has received 260610 bytes of data
,TCP/IP server has received 280320 bytes of data
,TCP/IP server has received 315360 bytes of data
,TCP/IP server has received 350400 bytes of data
,TCP/IP server has received 378728 bytes of data
,TCP/IP server has received 416100 bytes of data
,TCP/IP server has received 451140 bytes of data
,TCP/IP server has received 492750 bytes of data
,TCP/IP server has received 540930 bytes of data
,TCP/IP server has received 562830 bytes of data
,TCP/IP server has received 611010 bytes of data
,TCP/IP server has received 613200 bytes of data
,TCP/IP server has received 648240 bytes of data
,TCP/IP server has received 663570 bytes of data
,TCP/IP server has received 678900 bytes of data
,TCP/IP server has received 692040 bytes of data
,TCP/IP server has received 720510 bytes of data
,TCP/IP server has received 744600 bytes of data
,TCP/IP server has received 770880 bytes of data
,TCP/IP server has received 799208 bytes of data
,TCP/IP server has received 819060 bytes of data
,TCP/IP server has received 847388 bytes of data
,TCP/IP server has received 873810 bytes of data
,TCP/IP server has received 908850 bytes of data
,TCP/IP server has received 937320 bytes of data
,TCP/IP server has received 970028 bytes of data
,TCP/IP server has received 1000002 bytes of data
,re-try now : Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:45.822 ThaliTest[865:640158] server session: not connected Apple-IpadAir2-1_PT4426
,2015-11-19 10:05:49.208 ThaliTest[865:638459] jxcore: disconnect
2015-11-19 10:05:49.209 ThaliTest[865:638459] jxcore: disconnect: fail
Connect (retry count 4) to peer Apple-IpadAir2-1_PT4426.kvRdCA== with availability status: true
do connect now
,2015-11-19 10:05:49.211 ThaliTest[865:638459] jxcore: connect Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:05:49.212 ThaliTest[865:638459] client session: connect
2015-11-19 10:05:49.213 ThaliTest[865:638459] client session: stateChange:0->1 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:49.904 ThaliTest[865:638338] multipeer session: reset timer
2015-11-19 10:05:49.905 ThaliTest[865:638338] multipeer session: stop timer
2015-11-19 10:05:49.906 ThaliTest[865:638338] multipeer session: start timer: 0x19fe1fc0
2015-11-19 ,10:05:49.907 ThaliTest[865:638338] server: disconnecting to refresh session (Apple-IpadAir2-1_PT4426)
2015-11-19 10:05:49.907 ThaliTest[865:638338] server session: disconnect
2015-11-19 10:05:49.908 ThaliTest[865:638338] server session: stateChange:2->0 ,Apple-IpadAir2-1_PT4426
2015-11-19 10:05:49.911 ThaliTest[865:638338] server session: connect
2015-11-19 10:05:49.912 ThaliTest[865:638338] server session: stateChange:0->1 Apple-IpadAir2-1_PT4426
,TCP/IP server is ended
TCP/IP server is close
2015-11-19 10:05:49.932 ThaliTest[865:638338] server: accepting invitation Apple-IpadAir2-1_PT4426
,2015-11-19 10:05:51.988 ThaliTest[865:640243] client session: connected
2015-11-19 10:05:51.989 ThaliTest[865:640243] client session: stateChange:1->2 Apple-IpadAir2-1_PT4426.kvRdCA==
,2015-11-19 10:05:51.998 ThaliTest[865:640243] client session: fireConnectCallback: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:05:51.999 ThaliTest[865:640243] jxcore: connect: success
CLIENT connected to 55049, error: null
CLIENT starting client 
,2015-11-19 10:05:52.003 ThaliTest[865:638338] client: relay established
2015-11-19 10:05:52.004 ThaliTest[865:638338] client: new accepted socket: 0x19c2d9b0
,CLIENT now sending 930000 bytes of data
,2015-11-19 10:05:52.540 ThaliTest[865:640242] server session: connected
2015-11-19 10:05:52.541 ThaliTest[865:640242] server session: stateChange:1->2 Apple-IpadAir2-1_PT4426
,2015-11-19 10:05:52.565 ThaliTest[865:638338] server relay: connected (to port: 54992)
,TCP/IP server connected
,CLIENT is data received : 70000
,CLIENT is data received : 80000
,TCP/IP server has received 8760 bytes of data
,TCP/IP server has received 24090 bytes of data
CLIENT is data received : 90000
,TCP/IP server has received 43800 bytes of data
,TCP/IP server has received 78840 bytes of data
,TCP/IP server has received 111548 bytes of data
,TCP/IP server has received 131258 bytes of data
,TCP/IP server has received 157680 bytes of data
,TCP/IP server has received 186150 bytes of data
,TCP/IP server has received 219000 bytes of data
,TCP/IP server has received 249660 bytes of data
,TCP/IP server has received 289080 bytes of data
,TCP/IP server has received 326310 bytes of data
,TCP/IP server has received 354780 bytes of data
,TCP/IP server has received 400770 bytes of data
,TCP/IP server has received 448950 bytes of data
,TCP/IP server has received 490560 bytes of data
,TCP/IP server has received 525600 bytes of data
,CLIENT is data received : 90000
,TCP/IP server has received 569400 bytes of data
,TCP/IP server has received 600060 bytes of data
,TCP/IP server has received 621960 bytes of data
,TCP/IP server has received 667950 bytes of data
,TCP/IP server has received 724890 bytes of data
,TCP/IP server has received 762120 bytes of data
,TCP/IP server has received 764168 bytes of data
,TCP/IP server has received 784020 bytes of data
,TCP/IP server has received 801540 bytes of data
,TCP/IP server has received 816870 bytes of data
,2015-11-19 10:05:53.616 ThaliTest[865:640016] server session: not connected Apple-Iphone6-1_PT5791
,TCP/IP server has received 834390 bytes of data
,TCP/IP server has received 858196 bytes of data
,TCP/IP server has received 870002 bytes of data
,2015-11-19 10:05:59.381 ThaliTest[865:638338] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:05:59.382 ThaliTest[865:638338] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:05:59.451 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
,Receiving data timeout now
,CLIENT closeClientSocket
,CLIENT Stop now
Stop data retrieving timer
2015-11-19 10:06:03.072 ThaliTest[865:638338] client: socket closed
2015-11-19 10:06:03.073 ThaliTest[865:638338] client relay: socket disconnected
CLIENT Stop now
2015-11-19 10:06:03.074 ThaliTest[865:638338,] client relay: 0x19c2d9b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x15d2e070 {NSLocalizedDescription=Socket closed by remote peer} 
---- round done--------
2015-11-19 10:06:03.074 Tha,liTest[865:638338] client session: socket closed: Apple-IpadAir2-1_PT4426.kvRdCA==
2015-11-19 10:06:03.075 ThaliTest[865:638338] client session: onLinkFailure: Apple-IpadAir2-1_PT4426.kvRdCA==
weAreDoneNow , resultArray.length: 2
2015-11-19 10:06:03.075, ThaliTest[865:638338] client session: disconnect
2015-11-19 10:06:03.076 ThaliTest[865:638338] client session: stateChange:2->0 Apple-IpadAir2-1_PT4426.kvRdCA==
done, now sending data to server
DBG, CoordinatorConnector sendData called
,2015-11-19 10:06:03.078 ThaliTest[865:638338] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT4426.kvRdCA==
-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT5906","time":235225,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT5791.6xWUmg==","t,ime":119433,"result":"DATA-TIMEOUT","connections":5},{"name":"Apple-IpadAir2-1_PT4426.kvRdCA==","time":115509,"result":"DATA-TIMEOUT","connections":5}]}
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results li,st does not contain any items
sendList failed peers count : 2 [100 %]
- Peer ID : Apple-Iphone6-1_PT5791.6xWUmg==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT4426.kvRdCA==, Tried : 5
sendList never tried peers count : 0 [0 %]
CLIENT Stop now
,----------------- closeClientSocket
CLIENT is closed
,2015-11-19 10:06:07.331 ThaliTest[865:638338] multipeer session: reset timer
2015-11-19 10:06:07.332 ThaliTest[865:638338] multipeer session: stop timer
2015-11-19 10:06:07.332 ThaliTest[865:638338] multipeer session: start timer: 0x19fe1fc0
2015-11-19 ,10:06:07.333 ThaliTest[865:638338] server: disconnecting to refresh session (Apple-Iphone6-1_PT5791)
2015-11-19 10:06:07.333 ThaliTest[865:638338] server session: disconnect
2015-11-19 10:06:07.334 ThaliTest[865:638338] server session: stateChange:2->0 A,pple-Iphone6-1_PT5791
2015-11-19 10:06:07.337 ThaliTest[865:638338] server session: connect
2015-11-19 10:06:07.338 ThaliTest[865:638338] server session: stateChange:0->1 Apple-Iphone6-1_PT5791
TCP/IP server is ended
TCP/IP server is close
,2015-11-19 10:06:07.361 ThaliTest[865:638338] server: accepting invitation Apple-Iphone6-1_PT5791
,2015-11-19 10:06:09.486 ThaliTest[865:640016] server session: connected
2015-11-19 10:06:09.487 ThaliTest[865:640016] server session: stateChange:1->2 Apple-Iphone6-1_PT5791
,2015-11-19 10:06:09.496 ThaliTest[865:638338] server relay: connected (to port: 54992)
,TCP/IP server connected
,TCP/IP server has received 8760 bytes of data
,TCP/IP server has received 39420 bytes of data
,TCP/IP server has received 61320 bytes of data
,TCP/IP server has received 70080 bytes of data
,TCP/IP server has received 109500 bytes of data
,TCP/IP server has received 144540 bytes of data
,TCP/IP server has received 168488 bytes of data
,TCP/IP server has received 203670 bytes of data
,TCP/IP server has received 225570 bytes of data
,TCP/IP server has received 243090 bytes of data
,TCP/IP server has received 262800 bytes of data
,TCP/IP server has received 295650 bytes of data
,TCP/IP server has received 315360 bytes of data
,TCP/IP server has received 361350 bytes of data
,TCP/IP server has received 413910 bytes of data
,TCP/IP server has received 438000 bytes of data
,TCP/IP server has received 442380 bytes of data
,TCP/IP server has received 453330 bytes of data
,TCP/IP server has received 464280 bytes of data
,TCP/IP server has received 483990 bytes of data
,TCP/IP server has received 508080 bytes of data
,TCP/IP server has received 532170 bytes of data
,2015-11-19 10:06:10.433 ThaliTest[865:640241] server session: not connected Apple-IpadAir2-1_PT4426
,TCP/IP server has received 556260 bytes of data
,TCP/IP server has received 575970 bytes of data
,TCP/IP server has received 597870 bytes of data
,TCP/IP server has received 617580 bytes of data
,TCP/IP server has received 646050 bytes of data
,TCP/IP server has received 681090 bytes of data
,TCP/IP server has received 705180 bytes of data
,TCP/IP server has received 729270 bytes of data
,TCP/IP server has received 759788 bytes of data
,TCP/IP server has received 792780 bytes of data
,TCP/IP server has received 819060 bytes of data
,TCP/IP server has received 854100 bytes of data
,TCP/IP server has received 900090 bytes of data
,TCP/IP server has received 910002 bytes of data
,2015-11-19 10:06:20.805 ThaliTest[865:640242] server session: not connected Apple-Iphone6-1_PT5791
,2015-11-19 10:06:27.699 ThaliTest[865:638338] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:06:27.700 ThaliTest[865:638338] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:06:29.720 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:06:30.807 ThaliTest[865:638338] multipeer session: reset timer
2015-11-19 10:06:30.807 ThaliTest[865:638338] multipeer session: stop timer
2015-11-19 10:06:30.808 ThaliTest[865:638338] multipeer session: start timer: 0x19fe1fc0
2015-11-19 ,10:06:30.808 ThaliTest[865:638338] server: disconnecting to refresh session (Apple-Iphone6-1_PT5791)
2015-11-19 10:06:30.809 ThaliTest[865:638338] server session: disconnect
2015-11-19 10:06:30.809 ThaliTest[865:638338] server session: stateChange:2->0 A,pple-Iphone6-1_PT5791
2015-11-19 10:06:30.814 ThaliTest[865:638338] server session: connect
2015-11-19 10:06:30.815 ThaliTest[865:638338] server session: stateChange:0->1 Apple-Iphone6-1_PT5791
,TCP/IP server is ended
TCP/IP server is close
2015-11-19 10:06:30.836 ThaliTest[865:638338] server: accepting invitation Apple-Iphone6-1_PT5791
,2015-11-19 10:06:32.954 ThaliTest[865:640390] server session: connected
2015-11-19 10:06:32.954 ThaliTest[865:640390] server session: stateChange:1->2 Apple-Iphone6-1_PT5791
,2015-11-19 10:06:32.963 ThaliTest[865:638338] server relay: connected (to port: 54992)
TCP/IP server connected
,TCP/IP server has received 4380 bytes of data
,TCP/IP server has received 24090 bytes of data
,TCP/IP server has received 59130 bytes of data
,TCP/IP server has received 76650 bytes of data
,TCP/IP server has received 100598 bytes of data
,TCP/IP server has received 124830 bytes of data
,TCP/IP server has received 159870 bytes of data
,TCP/IP server has received 181770 bytes of data
,TCP/IP server has received 203670 bytes of data
,TCP/IP server has received 225570 bytes of data
,TCP/IP server has received 249660 bytes of data
,TCP/IP server has received 271560 bytes of data
,TCP/IP server has received 293460 bytes of data
,TCP/IP server has received 321788 bytes of data
,TCP/IP server has received 356970 bytes of data
,TCP/IP server has received 392010 bytes of data
,TCP/IP server has received 433478 bytes of data
,TCP/IP server has received 466328 bytes of data
,TCP/IP server has received 505890 bytes of data
,TCP/IP server has received 538740 bytes of data
,TCP/IP server has received 597870 bytes of data
,TCP/IP server has received 648240 bytes of data
,TCP/IP server has received 650430 bytes of data
,TCP/IP server has received 661380 bytes of data
,TCP/IP server has received 674520 bytes of data
,TCP/IP server has received 676710 bytes of data
,TCP/IP server has received 692040 bytes of data
,TCP/IP server has received 718178 bytes of data
,TCP/IP server has received 748838 bytes of data
,TCP/IP server has received 773070 bytes of data
,TCP/IP server has received 799350 bytes of data
,TCP/IP server has received 825630 bytes of data
,TCP/IP server has received 840002 bytes of data
,2015-11-19 10:06:36.661 ThaliTest[865:638338] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:06:36.662 ThaliTest[865:638338] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:06:37.581 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:06:44.393 ThaliTest[865:640359] server session: not connected Apple-Iphone6-1_PT5791
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,Turning Wifi off
,Warning: iOS does not support ToggleWiFi
,We could not turn wifi off! - Warning: iOS does not support ToggleWiFi
Turning Wifi back on
Warning: iOS does not support ToggleWiFi
,We could turn wifi back on! - Warning: iOS does not support ToggleWiFi
toggleWiFi finished
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,2015-11-19 10:06:56.452 ThaliTest[865:638338] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:06:56.453 ThaliTest[865:638338] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
2015-11-19 10:06:56.455 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:07:00.809 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:07:00.827 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:07:00.831 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,2015-11-19 10:07:27.375 ThaliTest[865:638338] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:07:27.376 ThaliTest[865:638338] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
2015-11-19 10:07:27.379 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName,":"(null)","peerAvailable":true}]
,2015-11-19 10:07:30.523 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:07:30.809 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:07:30.825 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
,2015-11-19 10:07:31.134 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,2015-11-19 10:07:57.383 ThaliTest[865:638338] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:07:57.383 ThaliTest[865:638338] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:07:58.303 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":true}]
,2015-11-19 10:08:00.809 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:08:00.921 ThaliTest[865:638338] client: found peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:08:00.924 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":,10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"a,rraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":,10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"a,rraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,2015-11-19 10:08:27.727 ThaliTest[865:638338] client: lost peer: Apple-Iphone6-1_PT5791.6xWUmg==
2015-11-19 10:08:27.728 ThaliTest[865:638338] client session: onPeerLost: Apple-Iphone6-1_PT5791.6xWUmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT5791.6xWUmg==","peerName":"(null)","peerAvailable":false}]
,2015-11-19 10:08:30.809 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:08:30.957 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,2015-11-19 10:09:00.808 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:09:01.278 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,2015-11-19 10:09:30.808 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:09:30.828 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, ha,s ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,2015-11-19 10:10:00.808 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:10:01.091 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
-iface: IPv6 is internal : true, has ip: ::1
-iface: IPv4 is internal : true, has ip: 127.0.0.1
-iface: IPv6 is internal : true, has ip: fe80::1
found interfaceName: awdl0
-iface: IPv6 is internal : false, ha,s ip: fe80::4013:ccff:fed5:254b
,2015-11-19 10:10:30.808 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:10:30.827 ThaliTest[865:638338] client: found peer: Apple-IpadAir2-1_PT4426.kvRdCA==
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
,printNetworkInfo
found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,DBG, CoordinatorConnector connect_error called
,Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived,":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object,]
printNetworkInfo
,found interfaceName: lo0
,-iface: IPv6 is internal : true, has ip: ::1
,-iface: IPv4 is internal : true, has ip: 127.0.0.1
,-iface: IPv6 is internal : true, has ip: fe80::1
,found interfaceName: awdl0
,-iface: IPv6 is internal : false, has ip: fe80::4013:ccff:fed5:254b
,2015-11-19 10:11:00.808 ThaliTest[865:638338] multipeer session: restart
,2015-11-19 10:11:00.816 ThaliTest[865:638338] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** First throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297, 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0x87693 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,* thread #1: tid = 0x9bd82, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x38e3ecc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x38d5c908 libsystem_c.dylib`abort + 76
    frame #3: 0x3808c9c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x380a6670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x3876af24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x380a3de2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x380a38ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x3876add2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x2a7b944c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #13: 0x00087692 ThaliTest`main + 50

```
