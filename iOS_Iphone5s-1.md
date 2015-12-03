#### Test 506502782cf4552_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502782cf4552/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/857C0202-971F-45B2-98E2-B7B3E8B53A65/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/857C0202-971F-45B2-98E2-B7B3E8B53A65/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502782cf4552/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502782cf4552/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/139A0E49-C92A-44F1-9BA3-BBB803C14C69/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60061"
,(lldb)     command script import "/tmp/857C0202-971F-45B2-98E2-B7B3E8B53A65/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 00:47:16.601 ThaliTest[2392:2234828] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EE15CF2F-BDA6-4E7B-BB01-1109F180E282/Library/Cookies/Cookies.binarycookies
,2015-12-03 00:47:17.026 ThaliTest[2392:2234828] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 00:47:17.028 ThaliTest[2392:2234828] Multi-tasking -> Device: YES, App: YES
,2015-12-03 00:47:17.037 ThaliTest[2392:2234828] Unlimited access to network resources
,2015-12-03 00:47:17.045 ThaliTest[2392:2234828] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 00:47:20.753 ThaliTest[2392:2234828] Resetting plugins due to page load.
,2015-12-03 00:47:21.049 ThaliTest[2392:2234828] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/139A0E49-C92A-44F1-9BA3-BBB803C14C69/ThaliTest.app/www/index.html
,2015-12-03 00:47:21.238 ThaliTest[2392:2234828] JXcore Cordova plugin initializing
,2015-12-03 00:47:21.239 ThaliTest[2392:2234955] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,Test app app.js loaded
,CoordinatorConnector-debug: connect:undefined
Coordinator is now connected to the server!
,CoordinatorConnector-debug: start:[object Object]
,{ testName: 'testFindPeers.js',
  testData: 
   { servertimeout: 1200000,
     timeout: 1000000,
     rounds: 1,
     dataTimeout: 10000,
     dataAmount: 100000,
     conReTryTimeout: 5000,
     conReTryCount: 5 },
  device: null,
  addressList: [] }
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-03 00:48:22.011 ThaliTest[2392:2234955] jxcore: startBroadcasting
,2015-12-03 00:48:22.025 ThaliTest[2392:2234955] server: starting Apple-Iphone5s-1_PT6234.wFQ0hQ==
2015-12-03 00:48:22.026 ThaliTest[2392:2234955] multipeer session: start timer: 0x19265ad0
2015-12-03 00:48:22.027 ThaliTest[2392:2234955] THEMultipeerSessi,on initialized peer Apple-Iphone5s-1_PT6234
,2015-12-03 00:48:22.028 ThaliTest[2392:2234955] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-03 00:48:22.365 ThaliTest[2392:2234828] client: found peer: Apple-Iphone6-1_PT3207.li3uFQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3207.li3uFQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT3207.li3uFQ==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT6234","time":364,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT3207.li3uFQ==","peerAvailable":true,"time":360}]}
,peersList : 100% : 360 ms, 99% : 360 ms, 95 : 360 ms, 90% : 360 ms.
,Result count 1, range 360 ms to  360 ms.
,2015-12-03 00:48:22.794 ThaliTest[2392:2234828] client: found peer: Apple-IpadAir2-1_PT6410.mb/urg==
,2015-12-03 00:48:22.989 ThaliTest[2392:2234828] client: found peer: Apple-Iphone5-1_PT1924.Z4IzFQ==
,CoordinatorConnector-debug: stop:undefined
,stop tests now !
stop current!
testFindPeers stopped
,2015-12-03 00:48:23.722 ThaliTest[2392:2234955] jxcore: stopBroadcasting
2015-12-03 00:48:23.722 ThaliTest[2392:2234955] THEMultipeerSession stopping peer
2015-12-03 00:48:23.723 ThaliTest[2392:2234955] multipeer session: stop timer
2015-12-03 00:48:23.,724 ThaliTest[2392:2234955] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,CoordinatorConnector-debug: start:[object Object]
,{ testName: 'testSendData.js',
  testData: 
   { servertimeout: 1200000,
     timeout: 1000000,
     rounds: 1,
     dataTimeout: 10000,
     dataAmount: 100000,
     conReTryTimeout: 5000,
     conReTryCount: 5 },
  device: null,
  addressList: [] }
,testSendData created [object Object], bt-address length : 0
,check server
,serverPort is 49796
,2015-12-03 00:48:23.785 ThaliTest[2392:2234955] jxcore: startBroadcasting
,2015-12-03 00:48:23.786 ThaliTest[2392:2234955] server: starting Apple-Iphone5s-1_PT6234.CrVPvA==
,2015-12-03 00:48:23.788 ThaliTest[2392:2234955] multipeer session: start timer: 0x155baaf0
,2015-12-03 00:48:23.790 ThaliTest[2392:2234955] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT6234
,2015-12-03 00:48:23.791 ThaliTest[2392:2234955] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-02T23:48:23.794Z SendDataTCPServer.js: TCP/IP server is bound to port: 49796
,2015-12-03 00:48:23.833 ThaliTest[2392:2234828] client: found peer: Apple-Iphone5s-1_PT6234.wFQ0hQ==
2015-12-03 00:48:23.834 ThaliTest[2392:2234828] client: found peer: Apple-Iphone6-1_PT3207.li3uFQ==
2015-12-03 00:48:23.835 ThaliTest[2392:2234828] clien,t: found peer: Apple-Iphone5-1_PT1924.Z4IzFQ==
2015-12-03 00:48:23.835 ThaliTest[2392:2234828] client: found peer: Apple-IpadAir2-1_PT6410.mb/urg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6234.wFQ0hQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,[]
,weAreDoneNow, resultArray.length: 0
,sendReportNow
,{ roundsToDo: 1,
  doneRounds: 0,
  toSendDataAmount: 100000,
  reTryTimeout: 5000,
  reTryMaxCount: 5,
  dataTimeOut: 10000,
  clientSocket: null,
  reTryTimer: null,
  receivedCounter: 0,
  tryRounds: 0,
  resultArray: [],
  connectionCount: 0,
  _events: { done: [Function], debug: [Function] } }
,done, now sending data to server
,CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT6234","time":62,"result":"OK","sendList":[]}
,sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
,Results list does not contain any items
,2015-12-02T23:48:23.843Z SendDataConnector.js: CLIENT Stop now
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3207.li3uFQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1924.Z4IzFQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6410.mb/urg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03 00:48:23.901 ThaliTest[2392:2234828] client: found peer: Apple-Iphone6-1_PT3207.pNHQUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3207.pNHQUA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 00:48:23.977 ThaliTest[2392:2234828] client: lost peer: Apple-Iphone5s-1_PT6234.wFQ0hQ==
2015-12-03 00:48:23.977 ThaliTest[2392:2234828] client session: onPeerLost: Apple-Iphone5s-1_PT6234.wFQ0hQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6234.wFQ0hQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,CoordinatorConnector-debug: disconnect:transport close
,2015-12-03 00:48:24.865 ThaliTest[2392:2234828] client: found peer: Apple-Iphone5-1_PT1924.buCz3Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1924.buCz3Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03 00:48:24.895 ThaliTest[2392:2234828] client: found peer: Apple-IpadAir2-1_PT6410.tFWzig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6410.tFWzig==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03 00:48:25.534 ThaliTest[2392:2234828] client: lost peer: Apple-Iphone6-1_PT3207.li3uFQ==
2015-12-03 00:48:25.534 ThaliTest[2392:2234828] client session: onPeerLost: Apple-Iphone6-1_PT3207.li3uFQ==
2015-12-03 00:48:25.535 ThaliTest[2392:2234828], client: lost peer: Apple-IpadAir2-1_PT6410.mb/urg==
2015-12-03 00:48:25.536 ThaliTest[2392:2234828] client session: onPeerLost: Apple-IpadAir2-1_PT6410.mb/urg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3207.li3uFQ==","peerName":"(nu,ll)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6410.mb/urg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 00:48:26.990 ThaliTest[2392:2234828] client: lost peer: Apple-Iphone5-1_PT1924.Z4IzFQ==
2015-12-03 00:48:26.990 ThaliTest[2392:2234828] client session: onPeerLost: Apple-Iphone5-1_PT1924.Z4IzFQ==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5-1_PT1924.Z4IzFQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 00:48:53.789 ThaliTest[2392:2234828] multipeer session: restart
2015-12-03 00:48:53.794 ThaliTest[2392:2234828] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0x3a5e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 2392 stopped
* thread #1: tid = 0x2219cc, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x38dc0df0 <+8>:  blo    0x38dc0e08                ; <+32>
    0x38dc0df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x38dc0df8 <+16>: ldr    r12, [pc, r12]
    0x38dc0dfc <+20>: b      0x38dc0e04                ; <+28>
,* thread #1: tid = 0x2219cc, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x0003a5e2 ThaliTest`main + 50

```
