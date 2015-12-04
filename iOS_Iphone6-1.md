#### Test 52539314a265f91_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52539314a265f91/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9FCAA768-806B-42F6-93E1-55AF88CE6520/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9FCAA768-806B-42F6-93E1-55AF88CE6520/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52539314a265f91/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52539314a265f91/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/61C28A54-D3BF-4F42-969F-F13633FF8761/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61307"
,(lldb)     command script import "/tmp/9FCAA768-806B-42F6-93E1-55AF88CE6520/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-04 09:02:56.524 ThaliTest[2741:2301735] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F0A17D5C-4083-4001-823C-E793493BD2FC/Library/Cookies/Cookies.binarycookies
,2015-12-04 09:02:56.877 ThaliTest[2741:2301735] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-04 09:02:56.877 ThaliTest[2741:2301735] Multi-tasking -> Device: YES, App: YES
,2015-12-04 09:02:56.886 ThaliTest[2741:2301735] Unlimited access to network resources
,2015-12-04 09:02:56.891 ThaliTest[2741:2301735] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-04 09:03:00.231 ThaliTest[2741:2301735] Resetting plugins due to page load.
,2015-12-04 09:03:00.556 ThaliTest[2741:2301735] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/61C28A54-D3BF-4F42-969F-F13633FF8761/ThaliTest.app/www/index.html
,2015-12-04 09:03:00.745 ThaliTest[2741:2301735] JXcore Cordova plugin initializing
,2015-12-04 09:03:00.746 ThaliTest[2741:2301870] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT9579
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":2,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 51332
,2015-12-04 09:09:27.922 ThaliTest[2741:2301870] jxcore: startBroadcasting
,2015-12-04 09:09:27.933 ThaliTest[2741:2301870] server: starting Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:27.934 ThaliTest[2741:2301870] multipeer session: start timer: 0x1add2510
,2015-12-04 09:09:27.936 ThaliTest[2741:2301870] THEMultipeerSession initialized peer Apple-Iphone6-1_PT9579
2015-12-04 09:09:27.936 ThaliTest[2741:2301870] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-04T08:09:27.939Z SendDataTCPServer.js: TCP/IP server is bound to port: 51332
,2015-12-04 09:09:28.572 ThaliTest[2741:2301735] multipeer session: reset timer
2015-12-04 09:09:28.572 ThaliTest[2741:2301735] multipeer session: stop timer
2015-12-04 09:09:28.573 ThaliTest[2741:2301735] multipeer session: start timer: 0x1add2510
2015-12-04 09:09:28.574 ThaliTest[2741:2301735] server session: connect
2015-12-04 09:09:28.575 ThaliTest[2741:2301735] server session: stateChange:0->1 Apple-IpadAir2-1_PT2716
,2015-12-04 09:09:28.587 ThaliTest[2741:2301735] server: accepting invitation Apple-IpadAir2-1_PT2716
,2015-12-04 09:09:28.719 ThaliTest[2741:2301735] multipeer session: reset timer
2015-12-04 09:09:28.719 ThaliTest[2741:2301735] multipeer session: stop timer
2015-12-04 09:09:28.720 ThaliTest[2741:2301735] multipeer session: start timer: 0x1add2510
2015-12-04 09:09:28.721 ThaliTest[2741:2301735] server session: connect
2015-12-04 09:09:28.721 ThaliTest[2741:2301735] server session: stateChange:0->1 Apple-Iphone5-1_PT1372
,2015-12-04 09:09:28.731 ThaliTest[2741:2301735] server: accepting invitation Apple-Iphone5-1_PT1372
,2015-12-04 09:09:29.574 ThaliTest[2741:2301735] client: found peer: Apple-IpadAir2-1_PT2716.efpToQ==
2015-12-04 09:09:29.576 ThaliTest[2741:2301735] client: found peer: Apple-Iphone5-1_PT1372.xmPKsQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipa,dAir2-1_PT2716.efpToQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04T08:09:29.583Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04T08:09:29.584Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04T08:09:29.585Z SendDataConnector.js: do connect now
,2015-12-04 09:09:29.586 ThaliTest[2741:2301870] jxcore: connect Apple-IpadAir2-1_PT2716.efpToQ==
2015-12-04 09:09:29.586 ThaliTest[2741:2301870] client session: connect
,2015-12-04 09:09:29.588 ThaliTest[2741:2301870] client session: stateChange:0->1 Apple-IpadAir2-1_PT2716.efpToQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1372.xmPKsQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-04 09:09:31.033 ThaliTest[2741:2302453] server session: connected
2015-12-04 09:09:31.034 ThaliTest[2741:2302453] server session: stateChange:1->2 Apple-Iphone5-1_PT1372
,2015-12-04 09:09:31.039 ThaliTest[2741:2302449] server session: connected
2015-12-04 09:09:31.040 ThaliTest[2741:2302449] server session: stateChange:1->2 Apple-IpadAir2-1_PT2716
,2015-12-04 09:09:31.046 ThaliTest[2741:2301735] server relay: connected (to port: 51332)
,2015-12-04T08:09:31.054Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04 09:09:31.060 ThaliTest[2741:2301735] server relay: connected (to port: 51332)
,2015-12-04T08:09:31.067Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:09:31.279Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-04T08:09:31.293Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-04T08:09:31.310Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-04T08:09:31.325Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-04T08:09:31.340Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04T08:09:31.578Z SendDataTCPServer.js: TCP/IP server has received 12896 bytes of data
,2015-12-04T08:09:31.593Z SendDataTCPServer.js: TCP/IP server has received 24800 bytes of data
,2015-12-04T08:09:31.610Z SendDataTCPServer.js: TCP/IP server has received 42656 bytes of data
,2015-12-04T08:09:31.625Z SendDataTCPServer.js: TCP/IP server has received 58528 bytes of data
,2015-12-04T08:09:31.638Z SendDataTCPServer.js: TCP/IP server has received 64480 bytes of data
,2015-12-04T08:09:31.651Z SendDataTCPServer.js: TCP/IP server has received 73408 bytes of data
,2015-12-04T08:09:31.666Z SendDataTCPServer.js: TCP/IP server has received 84320 bytes of data
,2015-12-04T08:09:31.681Z SendDataTCPServer.js: TCP/IP server has received 95232 bytes of data
,2015-12-04T08:09:31.695Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:09:31.705 ThaliTest[2741:2302449] server session: not connected Apple-Iphone5-1_PT1372
,2015-12-04 09:09:32.181 ThaliTest[2741:2302453] client session: connected
2015-12-04 09:09:32.182 ThaliTest[2741:2302453] client session: stateChange:1->2 Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04 09:09:32.189 ThaliTest[2741:2302453] client session: fireConnectCallback: Apple-IpadAir2-1_PT2716.efpToQ==
2015-12-04 09:09:32.190 ThaliTest[2741:2302453] jxcore: connect: success
,2015-12-04T08:09:32.192Z SendDataConnector.js: CLIENT connected to 51337, error: null
,2015-12-04T08:09:32.193Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:09:32.196 ThaliTest[2741:2301735] client: relay established
2015-12-04 09:09:32.197 ThaliTest[2741:2301735] client: new accepted socket: 0x1ace1490
,2015-12-04T08:09:32.209Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:09:32.666Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-04T08:09:32.679Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-04T08:09:32.703Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-04T08:09:32.703Z SendDataConnector.js: got all data for this round
,2015-12-04T08:09:32.704Z SendDataConnector.js: CLIENT Stop now
,2015-12-04T08:09:32.705Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:09:32.706 ThaliTest[2741:2301870] jxcore: disconnect
,2015-12-04 09:09:32.708 ThaliTest[2741:2301870] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04 09:09:32.709 ThaliTest[2741:2301870] client session: disconnect
,2015-12-04 09:09:32.709 ThaliTest[2741:2301870] client session: stateChange:2->0 Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04 09:09:32.769 ThaliTest[2741:2301870] jxcore: disconnect: success
,2015-12-04T08:09:32.770Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2716.efpToQ==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT1372.xmPKsQ==
,2015-12-04T08:09:32.772Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1372.xmPKsQ==
,2015-12-04T08:09:32.772Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1372.xmPKsQ==
,2015-12-04T08:09:32.773Z SendDataConnector.js: do connect now
,2015-12-04 09:09:32.773 ThaliTest[2741:2301870] jxcore: connect Apple-Iphone5-1_PT1372.xmPKsQ==
,2015-12-04 09:09:32.774 ThaliTest[2741:2301870] client session: connect
,2015-12-04 09:09:32.774 ThaliTest[2741:2301870] client session: stateChange:0->1 Apple-Iphone5-1_PT1372.xmPKsQ==
,2015-12-04 09:09:35.958 ThaliTest[2741:2302453] client session: connected
2015-12-04 09:09:35.958 ThaliTest[2741:2302453] client session: stateChange:1->2 Apple-Iphone5-1_PT1372.xmPKsQ==
2015-12-04 09:09:35.961 ThaliTest[2741:2302453] client session: fir,eConnectCallback: Apple-Iphone5-1_PT1372.xmPKsQ==
2015-12-04 09:09:35.962 ThaliTest[2741:2302453] jxcore: connect: success
,2015-12-04T08:09:35.964Z SendDataConnector.js: CLIENT connected to 51340, error: null
,2015-12-04T08:09:35.965Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:09:35.968 ThaliTest[2741:2301735] client: relay established
2015-12-04 09:09:35.969 ThaliTest[2741:2301735] client: new accepted socket: 0x1acf3890
,2015-12-04T08:09:35.981Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:09:36.331Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-04T08:09:36.344Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-04T08:09:36.344Z SendDataConnector.js: got all data for this round
,2015-12-04T08:09:36.345Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:09:36.345Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-04 09:09:36.345 ThaliTest[2741:2301870] jxcore: disconnect
2015-12-04 09:09:36.345 ThaliTest[2741:2301870] client session: disconnectFromPeer: Apple-Iphone5-1_PT1372.xmPKsQ==
2015-12-04 09:09:36.345 ThaliTest[2741:2301870] client session: disconnect
2015-12-04 09:09:36.346 ThaliTest[2741:2301870] client session: stateChange:2->0 Apple-Iphone5-1_PT1372.xmPKsQ==
,2015-12-04 09:09:36.347 ThaliTest[2741:2301870] jxcore: disconnect: success
2015-12-04T08:09:36.347Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1372.xmPKsQ==
---- round done--------
weAreDoneNow , resultArray.length: 2
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone6-1_PT9579","time":8442,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT2716.efpToQ==","time":3120,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_P,T1372.xmPKsQ==","time":3572,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 3572 ms, 99% : 3572 ms, 95 : 3572 ms, 90% : 3572 ms.
Result count 2, range 3120 ms to  3572 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-04T08:09:36.351Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:09:36.351Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:09:41.618 ThaliTest[2741:2302454] server session: not connected Apple-IpadAir2-1_PT2716
,2015-12-04 09:09:52.645 ThaliTest[2741:2301735] multipeer session: reset timer
2015-12-04 09:09:52.645 ThaliTest[2741:2301735] multipeer session: stop timer
2015-12-04 09:09:52.645 ThaliTest[2741:2301735] multipeer session: start timer: 0x1add2510
2015-,12-04 09:09:52.645 ThaliTest[2741:2301735] server: disconnecting to refresh session (Apple-IpadAir2-1_PT2716)
2015-12-04 09:09:52.645 ThaliTest[2741:2301735] server session: disconnect
2015-12-04 09:09:52.645 ThaliTest[2741:2301735] server session: stateChange:2->0 Apple-IpadAir2-1_PT2716
,2015-12-04 09:09:52.647 ThaliTest[2741:2301735] server session: connect
2015-12-04 09:09:52.648 ThaliTest[2741:2301735] server session: stateChange:0->1 Apple-IpadAir2-1_PT2716
,2015-12-04 09:09:52.650 ThaliTest[2741:2301735] server: accepting invitation Apple-IpadAir2-1_PT2716
,2015-12-04T08:09:52.651Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04 09:09:55.559 ThaliTest[2741:2302515] server session: connected
2015-12-04 09:09:55.560 ThaliTest[2741:2302515] server session: stateChange:1->2 Apple-IpadAir2-1_PT2716
,2015-12-04 09:09:55.584 ThaliTest[2741:2301735] server relay: connected (to port: 51332)
2015-12-04T08:09:55.588Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:09:55.614Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-04T08:09:55.637Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-04T08:09:55.649Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:10:05.617 ThaliTest[2741:2302443] server session: not connected Apple-IpadAir2-1_PT2716
,2015-12-04 09:10:16.826 ThaliTest[2741:2301735] multipeer session: reset timer
2015-12-04 09:10:16.827 ThaliTest[2741:2301735] multipeer session: stop timer
2015-12-04 09:10:16.827 ThaliTest[2741:2301735] multipeer session: start timer: 0x1add2510
2015-,12-04 09:10:16.827 ThaliTest[2741:2301735] server: disconnecting to refresh session (Apple-IpadAir2-1_PT2716)
2015-12-04 09:10:16.827 ThaliTest[2741:2301735] server session: disconnect
2015-12-04 09:10:16.827 ThaliTest[2741:2301735] server session: stateChange:2->0 Apple-IpadAir2-1_PT2716
,2015-12-04 09:10:16.829 ThaliTest[2741:2301735] server session: connect
2015-12-04 09:10:16.829 ThaliTest[2741:2301735] server session: stateChange:0->1 Apple-IpadAir2-1_PT2716
,2015-12-04 09:10:16.832 ThaliTest[2741:2301735] server: accepting invitation Apple-IpadAir2-1_PT2716
,2015-12-04T08:10:16.833Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04 09:10:19.257 ThaliTest[2741:2302555] server session: connected
2015-12-04 09:10:19.258 ThaliTest[2741:2302555] server session: stateChange:1->2 Apple-IpadAir2-1_PT2716
,2015-12-04 09:10:19.321 ThaliTest[2741:2301735] server relay: connected (to port: 51332)
,2015-12-04T08:10:19.330Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:10:19.370Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:10:29.729 ThaliTest[2741:2302555] server session: not connected Apple-IpadAir2-1_PT2716
,2015-12-04 09:10:40.272 ThaliTest[2741:2301735] multipeer session: reset timer
2015-12-04 09:10:40.273 ThaliTest[2741:2301735] multipeer session: stop timer
2015-12-04 09:10:40.273 ThaliTest[2741:2301735] multipeer session: start timer: 0x1add2510
2015-,12-04 09:10:40.274 ThaliTest[2741:2301735] server: disconnecting to refresh session (Apple-IpadAir2-1_PT2716)
2015-12-04 09:10:40.275 ThaliTest[2741:2301735] server session: disconnect
2015-12-04 09:10:40.275 ThaliTest[2741:2301735] server session: state,Change:2->0 Apple-IpadAir2-1_PT2716
2015-12-04 09:10:40.278 ThaliTest[2741:2301735] server session: connect
2015-12-04T08:10:40.282Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-04 09:10:40.278 ThaliTest[2741:2301735] server session: stateChange,:0->1 Apple-IpadAir2-1_PT2716
,2015-12-04 09:10:40.299 ThaliTest[2741:2301735] server: accepting invitation Apple-IpadAir2-1_PT2716
,2015-12-04 09:10:42.844 ThaliTest[2741:2302555] server session: connected
2015-12-04 09:10:42.845 ThaliTest[2741:2302555] server session: stateChange:1->2 Apple-IpadAir2-1_PT2716
,2015-12-04 09:10:42.869 ThaliTest[2741:2301735] server relay: connected (to port: 51332)
2015-12-04T08:10:42.870Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:10:42.958Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:10:52.956 ThaliTest[2741:2302604] server session: not connected Apple-IpadAir2-1_PT2716
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-04 09:11:03.884 ThaliTest[2741:2301735] multipeer session: reset timer
2015-12-04 09:11:03.884 ThaliTest[2741:2301735] multipeer session: stop timer
2015-12-04 09:11:03.884 ThaliTest[2741:2301735] multipeer session: start timer: 0x1add2510
2015-,12-04 09:11:03.885 ThaliTest[2741:2301735] server: disconnecting to refresh session (Apple-IpadAir2-1_PT2716)
2015-12-04 09:11:03.885 ThaliTest[2741:2301735] server session: disconnect
2015-12-04 09:11:03.885 ThaliTest[2741:2301735] server session: stateChange:2->0 Apple-IpadAir2-1_PT2716
2015-12-04 09:11:03.888 ThaliTest[2741:2301735] server session: connect
2015-12-04 09:11:03.890 ThaliTest[2741:2301735] server session: stateChange:0->1 Apple-IpadAir2-1_PT2716
,2015-12-04T08:11:03.894Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-04 09:11:03.895 ThaliTest[2741:2301735] server: accepting invitation Apple-IpadAir2-1_PT2716
,2015-12-04 09:11:06.200 ThaliTest[2741:2302613] server session: connected
2015-12-04 09:11:06.201 ThaliTest[2741:2302613] server session: stateChange:1->2 Apple-IpadAir2-1_PT2716
,2015-12-04 09:11:06.221 ThaliTest[2741:2301735] server relay: connected (to port: 51332)
2015-12-04T08:11:06.222Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:11:06.435Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-04 09:11:16.380 ThaliTest[2741:2302604] server session: not connected Apple-IpadAir2-1_PT2716
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-04 09:11:20.065 ThaliTest[2741:2301870] jxcore: stopBroadcasting
,2015-12-04 09:11:20.066 ThaliTest[2741:2301870] THEMultipeerSession stopping peer
,2015-12-04 09:11:20.067 ThaliTest[2741:2301870] multipeer session: stop timer
2015-12-04 09:11:20.068 ThaliTest[2741:2301870] server session: disconnect
2015-12-04 09:11:20.069 ThaliTest[2741:2301870] server session: stateChange:2->0 Apple-IpadAir2-1_PT2,716
,2015-12-04 09:11:20.075 ThaliTest[2741:2301870] server session: disconnect
2015-12-04 09:11:20.076 ThaliTest[2741:2301870] server session: stateChange:2->0 Apple-Iphone5-1_PT1372
2015-12-04 09:11:20.079 ThaliTest[2741:2301870] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-04T08:11:20.098Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-04T08:11:20.099Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:11:20.100Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT2716.efpToQ==\",\"time\":3120,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5-1_PT1372.xmPKsQ==\",\"time\":3572,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":3,"addressList":[]}
****TE,ST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
