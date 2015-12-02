#### Test 5065027859ed96a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027859ed96a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C646E18A-047F-4AE2-B718-B5D7EEBC65FE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C646E18A-047F-4AE2-B718-B5D7EEBC65FE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027859ed96a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027859ed96a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/43924772-2957-4DDF-BC90-60D27C442C57/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59836"
,(lldb)     command script import "/tmp/C646E18A-047F-4AE2-B718-B5D7EEBC65FE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 19:35:56.501 ThaliTest[2359:2208473] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/789B1597-5E01-4E6B-A25B-8693D7B5E053/Library/Cookies/Cookies.binarycookies
,2015-12-02 19:35:56.895 ThaliTest[2359:2208473] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 19:35:56.896 ThaliTest[2359:2208473] Multi-tasking -> Device: YES, App: YES
,2015-12-02 19:35:56.904 ThaliTest[2359:2208473] Unlimited access to network resources
,2015-12-02 19:35:56.910 ThaliTest[2359:2208473] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 19:36:00.582 ThaliTest[2359:2208473] Resetting plugins due to page load.
,2015-12-02 19:36:01.059 ThaliTest[2359:2208473] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/43924772-2957-4DDF-BC90-60D27C442C57/ThaliTest.app/www/index.html
,2015-12-02 19:36:01.272 ThaliTest[2359:2208473] JXcore Cordova plugin initializing
2015-12-02 19:36:01.273 ThaliTest[2359:2208590] JXcore instance initializing
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
  addressList:, [] }
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-02 19:37:03.274 ThaliTest[2359:2208590] jxcore: startBroadcasting
,2015-12-02 19:37:03.288 ThaliTest[2359:2208590] server: starting Apple-Iphone5s-1_PT9098.M4hD8g==
,2015-12-02 19:37:03.289 ThaliTest[2359:2208590] multipeer session: start timer: 0x19ab5620
,2015-12-02 19:37:03.290 ThaliTest[2359:2208590] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT9098
,2015-12-02 19:37:03.291 ThaliTest[2359:2208590] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-02 19:37:03.601 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.061qMA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.061qMA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT8858.061qMA==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT9098","time":336,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT8858.061qMA==","peerAvailable":true,"time":334}]}
,peersList : 100% : 334 ms, 99% : 334 ms, 95 : 334 ms, 90% : 334 ms.
,Result count 1, range 334 ms to  334 ms.
,2015-12-02 19:37:04.373 ThaliTest[2359:2208473] client: found peer: Apple-Iphone5-1_PT4201./LLfqw==
2015-12-02 19:37:04.376 ThaliTest[2359:2208473] client: found peer: Apple-IpadAir2-1_PT7013.zG+Tdw==
,CoordinatorConnector-debug: stop:undefined
,stop tests now !
stop current!
testFindPeers stopped
2015-12-02 19:37:05.076 ThaliTest[2359:2208590] jxcore: stopBroadcasting
,2015-12-02 19:37:05.077 ThaliTest[2359:2208590] THEMultipeerSession stopping peer
,2015-12-02 19:37:05.078 ThaliTest[2359:2208590] multipeer session: stop timer
2015-12-02 19:37:05.079 ThaliTest[2359:2208590] jxcore: stopBroadcasting: success
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
  addressList: ,[] }
,testSendData created [object Object], bt-address length : 0
,check server
,serverPort is 49543
,2015-12-02 19:37:05.149 ThaliTest[2359:2208590] jxcore: startBroadcasting
,2015-12-02 19:37:05.150 ThaliTest[2359:2208590] server: starting Apple-Iphone5s-1_PT9098.7c4Sig==
,2015-12-02 19:37:05.150 ThaliTest[2359:2208590] multipeer session: start timer: 0x15d64d30
2015-12-02 19:37:05.151 ThaliTest[2359:2208590] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT9098
2015-12-02 19:37:05.151 ThaliTest[2359:2208590] jxcore,: startBroadcasting: success
StartBroadcasting started ok
,2015-12-02T18:37:05.153Z SendDataTCPServer.js: TCP/IP server is bound to port: 49543
,2015-12-02 19:37:05.187 ThaliTest[2359:2208473] client: found peer: Apple-IpadAir2-1_PT7013.zG+Tdw==
2015-12-02 19:37:05.188 ThaliTest[2359:2208473] client: found peer: Apple-Iphone5s-1_PT9098.M4hD8g==
2015-12-02 19:37:05.188 ThaliTest[2359:2208473] client: found peer: Apple-Iphone5-1_PT4201./LLfqw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7013.zG+Tdw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
weAreDoneNow , resultArray.length: 0
done, now, sending data to server
CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT9098","time":49,"result":"OK","sendList":[]}
2015-12-02 19:37:05.193 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.061qMA==
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items
,2015-12-02T18:37:05.195Z SendDataConnector.js: CLIENT Stop now
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9098.M4hD8g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4201./LLfqw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.061qMA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 19:37:05.296 ThaliTest[2359:2208473] client: lost peer: Apple-Iphone5s-1_PT9098.M4hD8g==
,2015-12-02 19:37:05.297 ThaliTest[2359:2208473] client session: onPeerLost: Apple-Iphone5s-1_PT9098.M4hD8g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9098.M4hD8g==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-02 19:37:05.319 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,CoordinatorConnector-debug: disconnect:transport close
,2015-12-02 19:37:06.282 ThaliTest[2359:2208473] client: found peer: Apple-Iphone5-1_PT4201.oCX0FA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4201.oCX0FA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 19:37:06.289 ThaliTest[2359:2208473] client: found peer: Apple-IpadAir2-1_PT7013.NFAdNw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7013.NFAdNw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:37:07.920 ThaliTest[2359:2208473] client: lost peer: Apple-Iphone6-1_PT8858.061qMA==
2015-12-02 19:37:07.920 ThaliTest[2359:2208473] client session: onPeerLost: Apple-Iphone6-1_PT8858.061qMA==
2015-12-02 19:37:07.921 ThaliTest[2359:2208473], client: lost peer: Apple-Iphone5-1_PT4201./LLfqw==
2015-12-02 19:37:07.922 ThaliTest[2359:2208473] client session: onPeerLost: Apple-Iphone5-1_PT4201./LLfqw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.061qMA==","peerName":"(null,)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4201./LLfqw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:37:10.084 ThaliTest[2359:2208473] client: lost peer: Apple-IpadAir2-1_PT7013.zG+Tdw==
2015-12-02 19:37:10.085 ThaliTest[2359:2208473] client session: onPeerLost: Apple-IpadAir2-1_PT7013.zG+Tdw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7013.zG+Tdw==","peerName":"(null)","peerAvailable":false}]
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
,2015-12-02 19:37:35.152 ThaliTest[2359:2208473] multipeer session: restart
,2015-12-02 19:37:35.178 ThaliTest[2359:2208473] client: found peer: Apple-IpadAir2-1_PT7013.NFAdNw==
,2015-12-02 19:37:35.180 ThaliTest[2359:2208473] client: found peer: Apple-Iphone5-1_PT4201.oCX0FA==
2015-12-02 19:37:35.181 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:37:48.465 ThaliTest[2359:2208473] client: lost peer: Apple-Iphone6-1_PT8858.nxv6dw==
2015-12-02 19:37:48.466 ThaliTest[2359:2208473] client session: onPeerLost: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-02 19:37:48.891 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:38:05.151 ThaliTest[2359:2208473] multipeer session: restart
,2015-12-02 19:38:05.172 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
,2015-12-02 19:38:05.173 ThaliTest[2359:2208473] client: found peer: Apple-IpadAir2-1_PT7013.NFAdNw==
2015-12-02 19:38:05.175 ThaliTest[2359:2208473] client: found peer: Apple-Iphone5-1_PT4201.oCX0FA==
,2015-12-02 19:38:09.863 ThaliTest[2359:2208473] client: lost peer: Apple-Iphone6-1_PT8858.nxv6dw==
2015-12-02 19:38:09.864 ThaliTest[2359:2208473] client session: onPeerLost: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:38:10.233 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:38:18.455 ThaliTest[2359:2208473] client: lost peer: Apple-Iphone6-1_PT8858.nxv6dw==
2015-12-02 19:38:18.456 ThaliTest[2359:2208473] client session: onPeerLost: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-02 19:38:20.195 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:38:35.151 ThaliTest[2359:2208473] multipeer session: restart
2015-12-02 19:38:35.171 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
,2015-12-02 19:38:35.174 ThaliTest[2359:2208473] client: found peer: Apple-Iphone5-1_PT4201.oCX0FA==
,2015-12-02 19:38:35.179 ThaliTest[2359:2208473] client: found peer: Apple-IpadAir2-1_PT7013.NFAdNw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
2015-12-02 19:38:40.962 ThaliTest[2359:2208473] client: lost peer: Apple-Iphone6-1_PT8858.nxv6dw==
{"type":"connect_error","data":{"type":"TransportError","description":{"code,":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions",:{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
2015-12-02 19:38:40.963 ThaliTest[2359:2208473] client session: onPeerLost: Apple-Iphone6-1_PT8858.nxv6dw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:38:49.020 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:39:05.151 ThaliTest[2359:2208473] multipeer session: restart
,2015-12-02 19:39:05.173 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
2015-12-02 19:39:05.177 ThaliTest[2359:2208473] client: found peer: Apple-Iphone5-1_PT4201.oCX0FA==
2015-12-02 19:39:05.178 ThaliTest[2359:2208473] client,: found peer: Apple-IpadAir2-1_PT7013.NFAdNw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:39:09.966 ThaliTest[2359:2208473] client: lost peer: Apple-Iphone6-1_PT8858.nxv6dw==
2015-12-02 19:39:09.967 ThaliTest[2359:2208473] client session: onPeerLost: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-02 19:39:09.990 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:39:18.463 ThaliTest[2359:2208473] client: lost peer: Apple-Iphone6-1_PT8858.nxv6dw==
2015-12-02 19:39:18.463 ThaliTest[2359:2208473] client session: onPeerLost: Apple-Iphone6-1_PT8858.nxv6dw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-02 19:39:19.030 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:39:35.151 ThaliTest[2359:2208473] multipeer session: restart
,2015-12-02 19:39:35.172 ThaliTest[2359:2208473] client: found peer: Apple-Iphone5-1_PT4201.oCX0FA==
2015-12-02 19:39:35.174 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
2015-12-02 19:39:35.175 ThaliTest[2359:2208473] client: found peer: Apple-IpadAir2-1_PT7013.NFAdNw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:39:39.501 ThaliTest[2359:2208473] client: lost peer: Apple-Iphone6-1_PT8858.nxv6dw==
2015-12-02 19:39:39.502 ThaliTest[2359:2208473] client session: onPeerLost: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-02 19:39:40.956 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:39:48.400 ThaliTest[2359:2208473] client: lost peer: Apple-Iphone6-1_PT8858.nxv6dw==
2015-12-02 19:39:48.401 ThaliTest[2359:2208473] client session: onPeerLost: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:39:50.347 ThaliTest[2359:2208473] client: found peer: Apple-Iphone6-1_PT8858.nxv6dw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8858.nxv6dw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-02 19:40:05.150 ThaliTest[2359:2208473] multipeer session: restart
2015-12-02 19:40:05.158 ThaliTest[2359:2208473] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0x635e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 2359 stopped
* thread #1: tid = 0x21b2d9, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x38dc0df0 <+8>:  blo    0x38dc0e08                ; <+32>
    0x38dc0df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x38dc0df8 <+16>: ldr    r12, [pc, r12]
    0x38dc0dfc <+20>: b      0x38dc0e04                ; <+28>
,* thread #1: tid = 0x21b2d9, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x000635e2 ThaliTest`main + 50

```
