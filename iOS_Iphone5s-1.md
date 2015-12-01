#### Test 52320939cae1769_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52320939cae1769/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8DE03BEF-F39A-400B-AFB6-27A9A3FFB73A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8DE03BEF-F39A-400B-AFB6-27A9A3FFB73A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52320939cae1769/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52320939cae1769/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/41E2002D-0558-4173-9453-684030835C86/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58816"
,(lldb)     command script import "/tmp/8DE03BEF-F39A-400B-AFB6-27A9A3FFB73A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-01 23:01:31.460 ThaliTest[2234:2105907] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/25ECCCA0-9960-4FE2-B3F9-B4FF2273BB97/Library/Cookies/Cookies.binarycookies
,2015-12-01 23:01:31.867 ThaliTest[2234:2105907] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-01 23:01:31.868 ThaliTest[2234:2105907] Multi-tasking -> Device: YES, App: YES
,2015-12-01 23:01:31.876 ThaliTest[2234:2105907] Unlimited access to network resources
,2015-12-01 23:01:31.883 ThaliTest[2234:2105907] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-01 23:01:35.320 ThaliTest[2234:2105907] Resetting plugins due to page load.
,2015-12-01 23:01:35.764 ThaliTest[2234:2105907] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/41E2002D-0558-4173-9453-684030835C86/ThaliTest.app/www/index.html
,2015-12-01 23:01:36.031 ThaliTest[2234:2105907] JXcore Cordova plugin initializing
2015-12-01 23:01:36.032 ThaliTest[2234:2106040] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT9471
,attempting to connect to test coordinator
,check test folder
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 64695
,2015-12-01 23:08:19.423 ThaliTest[2234:2106040] jxcore: startBroadcasting
,2015-12-01 23:08:19.435 ThaliTest[2234:2106040] server: starting Apple-Iphone5s-1_PT9471.ZBmsZA==
,2015-12-01 23:08:19.436 ThaliTest[2234:2106040] multipeer session: start timer: 0x19d46fd0
2015-12-01 23:08:19.437 ThaliTest[2234:2106040] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT9471
2015-12-01 23:08:19.438 ThaliTest[2234:2106040] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-01T22:08:19.445Z SendDataTCPServer.js: TCP/IP server is bound to port: 64695
,2015-12-01 23:08:19.647 ThaliTest[2234:2105907] client: found peer: Apple-Iphone6-1_PT8318.eAU97Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8318.eAU97Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01T22:08:19.655Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01T22:08:19.655Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01T22:08:19.656Z SendDataConnector.js: do connect now
,2015-12-01 23:08:19.656 ThaliTest[2234:2106040] jxcore: connect Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01 23:08:19.656 ThaliTest[2234:2106040] client session: connect
2015-12-01 23:08:19.657 ThaliTest[2234:2106040] client session: stateChange:0->1 Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01 23:08:20.112 ThaliTest[2234:2105907] client: found peer: Apple-Iphone5-1_PT2043.ooMPSg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2043.ooMPSg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-01 23:08:20.154 ThaliTest[2234:2105907] client: found peer: Apple-IpadAir2-1_PT2654.X9QXJA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2654.X9QXJA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 23:08:22.810 ThaliTest[2234:2106649] client session: connected
2015-12-01 23:08:22.810 ThaliTest[2234:2106649] client session: stateChange:1->2 Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01 23:08:22.814 ThaliTest[2234:2106649] client session: fireConnectCallback: Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01 23:08:22.815 ThaliTest[2234:2106649] jxcore: connect: success
,2015-12-01T22:08:22.817Z SendDataConnector.js: CLIENT connected to 64698, error: null
,2015-12-01T22:08:22.819Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 23:08:22.824 ThaliTest[2234:2105907] client: relay established
2015-12-01 23:08:22.824 ThaliTest[2234:2105907] client: new accepted socket: 0x19c455c0
,2015-12-01T22:08:22.839Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T22:08:23.337Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-01T22:08:23.351Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-01T22:08:23.364Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-01T22:08:33.373Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T22:08:33.374Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T22:08:33.377Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T22:08:33.377Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T22:08:33.378Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 23:08:33.381 ThaliTest[2234:2105907] client: socket closed
2015-12-01 23:08:33.381 ThaliTest[2234:2105907] client relay: socket disconnected
2015-12-01 23:08:33.382 ThaliTest[2234:2105907] client relay: 0x19c455c0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x15eba610 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-01 23:08:33.383 ThaliTest[2234:2105907] client session: socket closed: Apple-Iphone6-1_PT8318.eAU97Q,==
2015-12-01 23:08:33.383 ThaliTest[2234:2105907] client session: onLinkFailure: Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01 23:08:33.384 ThaliTest[2234:2105907] client session: disconnect
2015-12-01 23:08:33.384 ThaliTest[2234:2105907] client session: stateChange:2->0 Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01 23:08:33.387 ThaliTest[2234:2105907] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT8318.eAU97Q==

```
