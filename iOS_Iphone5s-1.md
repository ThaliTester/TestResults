#### Test 52445159d291820_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52445159d291820/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A83323CC-01DE-4A34-A4B2-84EE0DBB2A53/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A83323CC-01DE-4A34-A4B2-84EE0DBB2A53/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52445159d291820/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52445159d291820/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8245AE79-9A38-4643-9F1F-E01835A457E9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59953"
,(lldb)     command script import "/tmp/A83323CC-01DE-4A34-A4B2-84EE0DBB2A53/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 21:06:07.792 ThaliTest[2372:2216273] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B6C89247-F556-4DB4-8F09-E859B46BCFA5/Library/Cookies/Cookies.binarycookies
,2015-12-02 21:06:08.211 ThaliTest[2372:2216273] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 21:06:08.213 ThaliTest[2372:2216273] Multi-tasking -> Device: YES, App: YES
,2015-12-02 21:06:08.222 ThaliTest[2372:2216273] Unlimited access to network resources
,2015-12-02 21:06:08.230 ThaliTest[2372:2216273] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 21:06:11.789 ThaliTest[2372:2216273] Resetting plugins due to page load.
,2015-12-02 21:06:12.226 ThaliTest[2372:2216273] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/8245AE79-9A38-4643-9F1F-E01835A457E9/ThaliTest.app/www/index.html
,2015-12-02 21:06:12.384 ThaliTest[2372:2216273] JXcore Cordova plugin initializing
,2015-12-02 21:06:12.385 ThaliTest[2372:2216398] JXcore instance initializing
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
Radios toggled
,my name is : Apple-Iphone5s-1_PT4399
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 49690
,2015-12-02 21:12:28.246 ThaliTest[2372:2216398] jxcore: startBroadcasting
,2015-12-02 21:12:28.259 ThaliTest[2372:2216398] server: starting Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:12:28.261 ThaliTest[2372:2216398] multipeer session: start timer: 0x1a4d24e0
2015-12-02 21:12:28.262 ThaliTest[2372:2216398] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT4399
2015-12-02 21:12:28.262 ThaliTest[2372:2216398] jxcore,: startBroadcasting: success
StartBroadcasting started ok
2015-12-02T20:12:28.266Z SendDataTCPServer.js: TCP/IP server is bound to port: 49690
,2015-12-02 21:12:28.496 ThaliTest[2372:2216273] client: found peer: Apple-Iphone5-1_PT3314.VcnsbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3314.VcnsbA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,device[1]: Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02T20:12:28.503Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02T20:12:28.505Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02T20:12:28.505Z SendDataConnector.js: do connect now
,2015-12-02 21:12:28.507 ThaliTest[2372:2216398] jxcore: connect Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:12:28.507 ThaliTest[2372:2216398] client session: connect
2015-12-02 21:12:28.508 ThaliTest[2372:2216398] client session: stateChange:0->1 Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02 21:12:28.516 ThaliTest[2372:2216273] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 21:12:29.017 ThaliTest[2372:2216273] client: found peer: Apple-IpadAir2-1_PT369.LHPK5g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT369.LHPK5g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 21:12:31.564 ThaliTest[2372:2216941] client session: connected
2015-12-02 21:12:31.565 ThaliTest[2372:2216941] client session: stateChange:1->2 Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02 21:12:31.573 ThaliTest[2372:2216941] client session: fireConnectCallback: Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:12:31.574 ThaliTest[2372:2216941] jxcore: connect: success
,2015-12-02T20:12:31.576Z SendDataConnector.js: CLIENT connected to 49693, error: null
,2015-12-02T20:12:31.577Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:12:31.581 ThaliTest[2372:2216273] client: relay established
2015-12-02 21:12:31.582 ThaliTest[2372:2216273] client: new accepted socket: 0x1a4de4e0
,2015-12-02T20:12:31.597Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T20:12:32.132Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-02T20:12:32.145Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-02T20:12:32.158Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T20:12:32.159Z SendDataConnector.js: got all data for this round
,2015-12-02T20:12:32.160Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:12:32.160Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:12:32.161 ThaliTest[2372:2216398] jxcore: disconnect
2015-12-02 21:12:32.161 ThaliTest[2372:2216398] client session: disconnectFromPeer: Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:12:32.162 ThaliTest[2372:2216398] client session: disconnect
2015-12-02 21:12:32.162 ThaliTest[2372:2216398] client session: stateChange:2->0 Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:12:32.163 ThaliTest[2372:2216398] jxcore: disconnect: success
,2015-12-02T20:12:32.164Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3314.VcnsbA==
,---- round done--------
,device[2]: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:12:32.168Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:12:32.168Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:12:32.168Z SendDataConnector.js: do connect now
,2015-12-02 21:12:32.169 ThaliTest[2372:2216398] jxcore: connect Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:32.170 ThaliTest[2372:2216398] client session: connect
,2015-12-02 21:12:32.171 ThaliTest[2372:2216398] client session: stateChange:0->1 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:35.396 ThaliTest[2372:2216932] client session: connected
2015-12-02 21:12:35.398 ThaliTest[2372:2216932] client session: stateChange:1->2 Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:12:35.402 ThaliTest[2372:2216932] client session: fir,eConnectCallback: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:12:35.402 ThaliTest[2372:2216932] jxcore: connect: success
2015-12-02T20:12:35.405Z SendDataConnector.js: CLIENT connected to 49697, error: null
2015-12-02T20:12:35.405Z SendDataConnector.j,s: CLIENT starting client 
2015-12-02 21:12:35.410 ThaliTest[2372:2216273] client: relay established
2015-12-02 21:12:35.410 ThaliTest[2372:2216273] client: new accepted socket: 0x1a525220
,2015-12-02T20:12:35.422Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02 21:12:35.457 ThaliTest[2372:2216273] multipeer session: reset timer
2015-12-02 21:12:35.458 ThaliTest[2372:2216273] multipeer session: stop timer
2015-12-02 21:12:35.459 ThaliTest[2372:2216273] multipeer session: start timer: 0x1a4d24e0
2015-,12-02 21:12:35.459 ThaliTest[2372:2216273] server session: connect
2015-12-02 21:12:35.460 ThaliTest[2372:2216273] server session: stateChange:0->1 Apple-IpadAir2-1_PT369
,2015-12-02 21:12:35.486 ThaliTest[2372:2216273] server: accepting invitation Apple-IpadAir2-1_PT369
,2015-12-02T20:12:35.826Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T20:12:35.842Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-02T20:12:35.855Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T20:12:35.855Z SendDataConnector.js: got all data for this round
,2015-12-02T20:12:35.856Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T20:12:35.857Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:12:35.857 ThaliTest[2372:2216398] jxcore: disconnect
,2015-12-02 21:12:35.859 ThaliTest[2372:2216398] client session: disconnectFromPeer: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:35.859 ThaliTest[2372:2216398] client session: disconnect
,2015-12-02 21:12:35.861 ThaliTest[2372:2216398] client session: stateChange:2->0 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:35.913 ThaliTest[2372:2216273] multipeer session: reset timer
2015-12-02 21:12:35.913 ThaliTest[2372:2216273] multipeer session: stop timer
2015-12-02 21:12:35.913 ThaliTest[2372:2216273] multipeer session: start timer: 0x1a4d24e0
2015-12-02 21:12:35.913 ThaliTest[2372:2216273] server session: connect
2015-12-02 21:12:35.914 ThaliTest[2372:2216273] server session: stateChange:0->1 Apple-Iphone6-1_PT3258
,2015-12-02 21:12:35.919 ThaliTest[2372:2216273] server: accepting invitation Apple-Iphone6-1_PT3258
,2015-12-02 21:12:35.928 ThaliTest[2372:2216398] jxcore: disconnect: success
,2015-12-02T20:12:35.929Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3258.XmE3ag==
,---- round done--------
,device[3]: Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02T20:12:35.933Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02T20:12:35.933Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02T20:12:35.934Z SendDataConnector.js: do connect now
,2015-12-02 21:12:35.934 ThaliTest[2372:2216398] jxcore: connect Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:35.936 ThaliTest[2372:2216398] client session: connect
,2015-12-02 21:12:35.937 ThaliTest[2372:2216398] client session: stateChange:0->1 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:37.999 ThaliTest[2372:2216943] server session: connected
2015-12-02 21:12:38.000 ThaliTest[2372:2216943] server session: stateChange:1->2 Apple-IpadAir2-1_PT369
,2015-12-02 21:12:38.005 ThaliTest[2372:2216273] server relay: connected (to port: 49690)
2015-12-02T20:12:38.011Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:12:38.333Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-02T20:12:38.351Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-02T20:12:38.368Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-02T20:12:38.387Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-02T20:12:38.403Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 21:12:38.938 ThaliTest[2372:2216938] server session: connected
2015-12-02 21:12:38.939 ThaliTest[2372:2216938] server session: stateChange:1->2 Apple-Iphone6-1_PT3258
2015-12-02 21:12:38.944 ThaliTest[2372:2216273] server relay: connected (to ,port: 49690)
2015-12-02T20:12:38.945Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02 21:12:39.079 ThaliTest[2372:2216941] client session: connected
2015-12-02 21:12:39.080 ThaliTest[2372:2216941] client session: stateChange:1->2 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:39.087 ThaliTest[2372:2216943] client session: fireConnectCallback: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:12:39.088 ThaliTest[2372:2216943] jxcore: connect: success
2015-12-02T20:12:39.089Z SendDataConnector.js: CLIENT connected ,to 49702, error: null
2015-12-02T20:12:39.090Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:12:39.093 ThaliTest[2372:2216273] client: relay established
,2015-12-02 21:12:39.094 ThaliTest[2372:2216273] client: new accepted socket: 0x166acc00
,2015-12-02T20:12:39.107Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T20:12:39.378Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-02T20:12:39.391Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-02T20:12:39.406Z SendDataTCPServer.js: TCP/IP server has received 82936 bytes of data
,2015-12-02T20:12:39.408Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-02T20:12:39.421Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 21:12:39.465 ThaliTest[2372:2216942] server session: not connected Apple-Iphone6-1_PT3258
,2015-12-02 21:12:48.800 ThaliTest[2372:2216942] server session: not connected Apple-IpadAir2-1_PT369
,2015-12-02T20:12:49.413Z SendDataConnector.js: Receiving data timeout now
2015-12-02T20:12:49.413Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:12:49.415Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:12:49.415Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:12:49.416Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:12:49.418 ThaliTest[2372:2216273] client: socket closed
2015-12-02 21:12:49.419 ThaliTest[2372:2216273] client relay: socket disconnected
2015-12-02 21:12:49.419 ThaliTest[2372:2216273] client relay: 0x166acc00 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1a597100 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-02 21:12:49.420 ThaliTest[2372:2216273] client session: socket closed: Apple-IpadAir2-1_PT369.LHPK5g,==
2015-12-02 21:12:49.421 ThaliTest[2372:2216273] client session: onLinkFailure: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:12:49.421 ThaliTest[2372:2216273] client session: disconnect
2015-12-02 21:12:49.421 ThaliTest[2372:2216273] client session: stateChange:2->0 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:49.425 ThaliTest[2372:2216273] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02T20:12:54.426Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02T20:12:54.427Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:58.905 ThaliTest[2372:2216273] multipeer session: reset timer
2015-12-02 21:12:58.906 ThaliTest[2372:2216273] multipeer session: stop timer
2015-12-02 21:12:58.907 ThaliTest[2372:2216273] multipeer session: start timer: 0x1a4d24e0
2015-,12-02 21:12:58.907 ThaliTest[2372:2216273] server: disconnecting to refresh session (Apple-IpadAir2-1_PT369)
2015-12-02 21:12:58.908 ThaliTest[2372:2216273] server session: disconnect
2015-12-02 21:12:58.908 ThaliTest[2372:2216273] server session: stateC,hange:2->0 Apple-IpadAir2-1_PT369
2015-12-02 21:12:58.916 ThaliTest[2372:2216273] server session: connect
2015-12-02 21:12:58.917 ThaliTest[2372:2216273] server session: stateChange:0->1 Apple-IpadAir2-1_PT369
,2015-12-02T20:12:58.927Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-02 21:12:58.933 ThaliTest[2372:2216273] server: accepting invitation Apple-IpadAir2-1_PT369
,2015-12-02 21:12:59.435 ThaliTest[2372:2216398] jxcore: disconnect
2015-12-02 21:12:59.436 ThaliTest[2372:2216398] jxcore: disconnect: fail
2015-12-02T20:12:59.437Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT369.LHPK5,g==
,2015-12-02T20:12:59.438Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT369.LHPK5g== with availability status: true
2015-12-02T20:12:59.438Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT369.LHPK5g==
2015-1,2-02T20:12:59.438Z SendDataConnector.js: do connect now
,2015-12-02 21:12:59.439 ThaliTest[2372:2216398] jxcore: connect Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:59.440 ThaliTest[2372:2216398] client session: connect
,2015-12-02 21:12:59.441 ThaliTest[2372:2216398] client session: stateChange:0->1 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:01.318 ThaliTest[2372:2217017] server session: connected
2015-12-02 21:13:01.319 ThaliTest[2372:2217017] server session: stateChange:1->2 Apple-IpadAir2-1_PT369
,2015-12-02 21:13:01.325 ThaliTest[2372:2216273] server relay: connected (to port: 49690)
2015-12-02T20:13:01.331Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:13:01.370Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-02T20:13:01.383Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-02T20:13:01.395Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02 21:13:01.776 ThaliTest[2372:2217017] client session: connected
2015-12-02 21:13:01.777 ThaliTest[2372:2217017] client session: stateChange:1->2 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:01.783 ThaliTest[2372:2216981] client session: fireConnectCallback: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:13:01.784 ThaliTest[2372:2216981] jxcore: connect: success
2015-12-02T20:13:01.785Z SendDataConnector.js: CLIENT connected ,to 49706, error: null
2015-12-02T20:13:01.786Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:13:01.790 ThaliTest[2372:2216273] client: relay established
2015-12-02 21:13:01.790 ThaliTest[2372:2216273] client: new accepted socket: 0x1a5931a0
,2015-12-02T20:13:01.802Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02 21:13:11.389 ThaliTest[2372:2217015] server session: not connected Apple-IpadAir2-1_PT369
,2015-12-02T20:13:11.875Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:13:11.875Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:11.876Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:11.877Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:13:11.878Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:13:11.879 ThaliTest[2372:2216273] client: socket closed
2015-12-02 21:13:11.880 ThaliTest[2372:2216273] client relay: socket disconnected
2015-12-02 21:13:11.880 ThaliTest[2372:2216273] client relay: 0x1a5931a0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1a558fe0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-02 21:13:11.881 ThaliTest[2372:2216273] client session: socket closed: Apple-IpadAir2-1_PT369.LHPK5g,==
2015-12-02 21:13:11.881 ThaliTest[2372:2216273] client session: onLinkFailure: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:13:11.882 ThaliTest[2372:2216273] client session: disconnect
2015-12-02 21:13:11.882 ThaliTest[2372:2216273] client session: stateChange:2->0 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:11.885 ThaliTest[2372:2216273] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02T20:13:16.889Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02T20:13:16.889Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:21.893 ThaliTest[2372:2216398] jxcore: disconnect
2015-12-02 21:13:21.894 ThaliTest[2372:2216398] jxcore: disconnect: fail
2015-12-02T20:13:21.895Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT369.LHPK5,g==
2015-12-02T20:13:21.896Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT369.LHPK5g== with availability status: true
,2015-12-02T20:13:21.896Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02T20:13:21.896Z SendDataConnector.js: do connect now
,2015-12-02 21:13:21.897 ThaliTest[2372:2216398] jxcore: connect Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:21.898 ThaliTest[2372:2216398] client session: connect
2015-12-02 21:13:21.899 ThaliTest[2372:2216398] client session: stateChange:0->1 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:22.419 ThaliTest[2372:2216273] multipeer session: reset timer
2015-12-02 21:13:22.420 ThaliTest[2372:2216273] multipeer session: stop timer
2015-12-02 21:13:22.420 ThaliTest[2372:2216273] multipeer session: start timer: 0x1a4d24e0
2015-,12-02 21:13:22.421 ThaliTest[2372:2216273] server: disconnecting to refresh session (Apple-IpadAir2-1_PT369)
2015-12-02 21:13:22.421 ThaliTest[2372:2216273] server session: disconnect
2015-12-02 21:13:22.422 ThaliTest[2372:2216273] server session: stateC,hange:2->0 Apple-IpadAir2-1_PT369
2015-12-02 21:13:22.426 ThaliTest[2372:2216273] server session: connect
2015-12-02 21:13:22.426 ThaliTest[2372:2216273] server session: stateChange:0->1 Apple-IpadAir2-1_PT369
2015-12-02T20:13:22.429Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-02 21:13:22.446 ThaliTest[2372:2216273] server: accepting invitation Apple-IpadAir2-1_PT369
,2015-12-02 21:13:24.644 ThaliTest[2372:2217058] client session: connected
2015-12-02 21:13:24.645 ThaliTest[2372:2217058] client session: stateChange:1->2 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:24.650 ThaliTest[2372:2217071] client session: fireConnectCallback: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:13:24.651 ThaliTest[2372:2217071] jxcore: connect: success
2015-12-02T20:13:24.653Z SendDataConnector.js: CLIENT connected to 49709, error: null
,2015-12-02T20:13:24.654Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:13:24.658 ThaliTest[2372:2216273] client: relay established
2015-12-02 21:13:24.659 ThaliTest[2372:2216273] client: new accepted socket: 0x166acc00
,2015-12-02T20:13:24.671Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02 21:13:24.712 ThaliTest[2372:2217058] server session: connected
2015-12-02 21:13:24.713 ThaliTest[2372:2217058] server session: stateChange:1->2 Apple-IpadAir2-1_PT369
,2015-12-02 21:13:24.719 ThaliTest[2372:2216273] server relay: connected (to port: 49690)
,2015-12-02T20:13:24.771Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:13:24.784Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02T20:13:34.771Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:13:34.771Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:34.772Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:34.773Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:13:34.773Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:13:34.775 ThaliTest[2372:2216273] client: socket closed
2015-12-02 21:13:34.776 ThaliTest[2372:2216273] client relay: socket disconnected
2015-12-02 21:13:34.777 ThaliTest[2372:2216273] client relay: 0x166acc00 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x166c5bd0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-02 21:13:34.778 ThaliTest[2372:2216273] client session: socket closed: Apple-IpadAir2-1_PT369.LHPK5g,==
2015-12-02 21:13:34.778 ThaliTest[2372:2216273] client session: onLinkFailure: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:13:34.779 ThaliTest[2372:2216273] client session: disconnect
2015-12-02 21:13:34.779 ThaliTest[2372:2216273] client session: ,stateChange:2->0 Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:13:34.782 ThaliTest[2372:2216273] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:34.927 ThaliTest[2372:2217065] server session: not connected Apple-IpadAir2-1_PT369
,2015-12-02T20:13:39.782Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02T20:13:39.783Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:44.785 ThaliTest[2372:2216398] jxcore: disconnect
2015-12-02 21:13:44.786 ThaliTest[2372:2216398] jxcore: disconnect: fail
,2015-12-02T20:13:44.787Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02T20:13:44.788Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT369.LHPK5g== with availability status: ,true
2015-12-02T20:13:44.789Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02T20:13:44.789Z SendDataConnector.js: do connect now
,2015-12-02 21:13:44.790 ThaliTest[2372:2216398] jxcore: connect Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:44.791 ThaliTest[2372:2216398] client session: connect
,2015-12-02 21:13:44.792 ThaliTest[2372:2216398] client session: stateChange:0->1 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:45.458 ThaliTest[2372:2216273] multipeer session: reset timer
2015-12-02 21:13:45.459 ThaliTest[2372:2216273] multipeer session: stop timer
2015-12-02 21:13:45.459 ThaliTest[2372:2216273] multipeer session: start timer: 0x1a4d24e0
2015-,12-02 21:13:45.460 ThaliTest[2372:2216273] server: disconnecting to refresh session (Apple-IpadAir2-1_PT369)
2015-12-02 21:13:45.460 ThaliTest[2372:2216273] server session: disconnect
2015-12-02 21:13:45.461 ThaliTest[2372:2216273] server session: stateC,hange:2->0 Apple-IpadAir2-1_PT369
2015-12-02 21:13:45.465 ThaliTest[2372:2216273] server session: connect
2015-12-02 21:13:45.465 ThaliTest[2372:2216273] server session: stateChange:0->1 Apple-IpadAir2-1_PT369
,2015-12-02T20:13:45.479Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-02 21:13:45.486 ThaliTest[2372:2216273] server: accepting invitation Apple-IpadAir2-1_PT369
,2015-12-02 21:13:48.100 ThaliTest[2372:2217121] client session: connected
2015-12-02 21:13:48.101 ThaliTest[2372:2217121] client session: stateChange:1->2 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:48.105 ThaliTest[2372:2217121] client session: fireConnectCallback: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:13:48.107 ThaliTest[2372:2217121] jxcore: connect: success
2015-12-02T20:13:48.108Z SendDataConnector.js: CLIENT connected ,to 49715, error: null
2015-12-02T20:13:48.108Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:13:48.112 ThaliTest[2372:2216273] client: relay established
2015-12-02 21:13:48.113 ThaliTest[2372:2216273] client: new accepted socket: 0x1a535750
,2015-12-02T20:13:48.125Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02 21:13:48.191 ThaliTest[2372:2217131] server session: connected
2015-12-02 21:13:48.191 ThaliTest[2372:2217131] server session: stateChange:1->2 Apple-IpadAir2-1_PT369
,2015-12-02 21:13:48.193 ThaliTest[2372:2216273] server relay: connected (to port: 49690)
,2015-12-02T20:13:48.210Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:13:48.283Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02T20:13:58.203Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:13:58.203Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:58.204Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:58.205Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:13:58.205Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:13:58.207 ThaliTest[2372:2216273] client: socket closed
2015-12-02 21:13:58.208 ThaliTest[2372:2216273] client relay: socket disconnected
2015-12-02 21:13:58.208 ThaliTest[2372:2216273] client relay: 0x1a535750 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1a23bec0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-02 21:13:58.209 ThaliTest[2372:2216273] client session: socket closed: Apple-IpadAir2-1_PT369.LHPK5g,==
2015-12-02 21:13:58.210 ThaliTest[2372:2216273] client session: onLinkFailure: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:13:58.210 ThaliTest[2372:2216273] client session: disconnect
2015-12-02 21:13:58.211 ThaliTest[2372:2216273] client session: ,stateChange:2->0 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:58.214 ThaliTest[2372:2216273] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:58.518 ThaliTest[2372:2217123] server session: not connected Apple-IpadAir2-1_PT369
,2015-12-02T20:14:03.213Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02T20:14:03.213Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:14:08.218 ThaliTest[2372:2216398] jxcore: disconnect
2015-12-02 21:14:08.219 ThaliTest[2372:2216398] jxcore: disconnect: fail
2015-12-02T20:14:08.220Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT369.LHPK5,g==
2015-12-02T20:14:08.220Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT369.LHPK5g== with availability status: true
2015-12-02T20:14:08.221Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT369.LHPK5g==
2,015-12-02T20:14:08.221Z SendDataConnector.js: do connect now
,2015-12-02 21:14:08.222 ThaliTest[2372:2216398] jxcore: connect Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:14:08.223 ThaliTest[2372:2216398] client session: connect
,2015-12-02 21:14:08.224 ThaliTest[2372:2216398] client session: stateChange:0->1 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:14:09.533 ThaliTest[2372:2216273] multipeer session: reset timer
2015-12-02 21:14:09.534 ThaliTest[2372:2216273] multipeer session: stop timer
2015-12-02 21:14:09.535 ThaliTest[2372:2216273] multipeer session: start timer: 0x1a4d24e0
2015-,12-02 21:14:09.535 ThaliTest[2372:2216273] server: disconnecting to refresh session (Apple-IpadAir2-1_PT369)
2015-12-02 21:14:09.536 ThaliTest[2372:2216273] server session: disconnect
2015-12-02 21:14:09.536 ThaliTest[2372:2216273] server session: stateC,hange:2->0 Apple-IpadAir2-1_PT369
2015-12-02 21:14:09.539 ThaliTest[2372:2216273] server session: connect
2015-12-02 21:14:09.540 ThaliTest[2372:2216273] server session: stateChange:0->1 Apple-IpadAir2-1_PT369
,2015-12-02T20:14:09.550Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-02 21:14:09.550 ThaliTest[2372:2216273] server: accepting invitation Apple-IpadAir2-1_PT369
,2015-12-02 21:14:11.638 ThaliTest[2372:2217181] client session: connected
2015-12-02 21:14:11.639 ThaliTest[2372:2217181] client session: stateChange:1->2 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:14:11.644 ThaliTest[2372:2217187] client session: fireConnectCallback: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:14:11.646 ThaliTest[2372:2217187] jxcore: connect: success
2015-12-02T20:14:11.647Z SendDataConnector.js: CLIENT connected ,to 49719, error: null
2015-12-02T20:14:11.648Z SendDataConnector.js: CLIENT starting client 
2015-12-02 21:14:11.651 ThaliTest[2372:2216273] client: relay established
2015-12-02 21:14:11.652 ThaliTest[2372:2216273] client: new accepted socket: 0x1a5f259,0
,2015-12-02T20:14:11.665Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02 21:14:11.848 ThaliTest[2372:2217173] server session: connected
2015-12-02 21:14:11.848 ThaliTest[2372:2217173] server session: stateChange:1->2 Apple-IpadAir2-1_PT369
,2015-12-02 21:14:11.850 ThaliTest[2372:2216273] server relay: connected (to port: 49690)
,2015-12-02T20:14:11.854Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:14:11.905Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02 21:14:15.921 ThaliTest[2372:2216273] multipeer session: reset timer
2015-12-02 21:14:15.921 ThaliTest[2372:2216273] multipeer session: stop timer
2015-12-02 21:14:15.922 ThaliTest[2372:2216273] multipeer session: start timer: 0x1a4d24e0
2015-,12-02 21:14:15.923 ThaliTest[2372:2216273] server session: connect
2015-12-02 21:14:15.923 ThaliTest[2372:2216273] server session: stateChange:0->1 Apple-Iphone5-1_PT3314
,2015-12-02 21:14:15.935 ThaliTest[2372:2216273] server: accepting invitation Apple-Iphone5-1_PT3314
,2015-12-02 21:14:18.469 ThaliTest[2372:2217186] server session: connected
2015-12-02 21:14:18.470 ThaliTest[2372:2217186] server session: stateChange:1->2 Apple-Iphone5-1_PT3314
,2015-12-02 21:14:18.476 ThaliTest[2372:2216273] server relay: connected (to port: 49690)
2015-12-02T20:14:18.483Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:14:18.976Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-12-02T20:14:18.990Z SendDataTCPServer.js: TCP/IP server has received 12896 bytes of data
,2015-12-02T20:14:19.005Z SendDataTCPServer.js: TCP/IP server has received 23808 bytes of data
,2015-12-02T20:14:19.021Z SendDataTCPServer.js: TCP/IP server has received 35712 bytes of data
,2015-12-02T20:14:19.040Z SendDataTCPServer.js: TCP/IP server has received 46624 bytes of data
,2015-12-02T20:14:19.053Z SendDataTCPServer.js: TCP/IP server has received 59520 bytes of data
,2015-12-02T20:14:19.069Z SendDataTCPServer.js: TCP/IP server has received 71424 bytes of data
,2015-12-02T20:14:19.083Z SendDataTCPServer.js: TCP/IP server has received 85312 bytes of data
,2015-12-02T20:14:19.098Z SendDataTCPServer.js: TCP/IP server has received 99200 bytes of data
,2015-12-02T20:14:19.112Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02T20:14:21.738Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:14:21.739Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:14:21.740Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:14:21.741Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:14:21.742Z SendDataConnector.js: Stop data retrieving timer
2015-12-02T20:14:21.742Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:14:21.743 ThaliTest[2372:2216398] jxcore: disconnect
,2015-12-02 21:14:21.745 ThaliTest[2372:2216398] client session: disconnectFromPeer: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:14:21.746 ThaliTest[2372:2216398] client session: disconnect
2015-12-02 21:14:21.746 ThaliTest[2372:2216398] client session: stateChange:2->0 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:14:21.750 ThaliTest[2372:2216398] jxcore: disconnect: success
2015-12-02T20:14:21.753Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT369.LHPK5g==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT4399","time":113527,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT3314.VcnsbA==","time":3656,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1,_PT3258.XmE3ag==","time":3688,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT369.LHPK5g==","time":105807,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000}]}
,sendList : 100% : 3688 ms, 99% : 3688 ms, 95 : 3688 ms, 90% : 3688 ms.
,Result count 2, range 3656 ms to  3688 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-IpadAir2-1_PT369.LHPK5g==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-02T20:14:21.778Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T20:14:21.779Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:14:21.780Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:14:22.099 ThaliTest[2372:2217181] server session: not connected Apple-IpadAir2-1_PT369
,2015-12-02 21:14:29.441 ThaliTest[2372:2217186] server session: not connected Apple-Iphone5-1_PT3314
,2015-12-02 21:14:36.256 ThaliTest[2372:2216273] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:14:38.906 ThaliTest[2372:2216273] client: lost peer: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:14:38.906 ThaliTest[2372:2216273] client session: onPeerLost: Apple-Iphone6-1_PT3258.XmE3ag==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 21:14:39.444 ThaliTest[2372:2216273] multipeer session: reset timer
2015-12-02 21:14:39.444 ThaliTest[2372:2216273] multipeer session: stop timer
2015-12-02 21:14:39.445 ThaliTest[2372:2216273] multipeer session: start timer: 0x1a4d24e0
2015-,12-02 21:14:39.446 ThaliTest[2372:2216273] server: disconnecting to refresh session (Apple-Iphone5-1_PT3314)
2015-12-02 21:14:39.446 ThaliTest[2372:2216273] server session: disconnect
2015-12-02 21:14:39.447 ThaliTest[2372:2216273] server session: stateC,hange:2->0 Apple-Iphone5-1_PT3314
2015-12-02 21:14:39.450 ThaliTest[2372:2216273] server session: connect
2015-12-02 21:14:39.451 ThaliTest[2372:2216273] server session: stateChange:0->1 Apple-Iphone5-1_PT3314
,2015-12-02T20:14:39.464Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-02 21:14:39.472 ThaliTest[2372:2216273] server: accepting invitation Apple-Iphone5-1_PT3314
,2015-12-02 21:14:41.683 ThaliTest[2372:2217246] server session: connected
2015-12-02 21:14:41.684 ThaliTest[2372:2217246] server session: stateChange:1->2 Apple-Iphone5-1_PT3314
,2015-12-02 21:14:41.693 ThaliTest[2372:2216273] server relay: connected (to port: 49690)
,2015-12-02T20:14:41.699Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02 21:14:42.028 ThaliTest[2372:2216273] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":true}]
,2015-12-02T20:14:42.050Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02 21:14:51.981 ThaliTest[2372:2217186] server session: not connected Apple-Iphone5-1_PT3314
,2015-12-02 21:15:02.103 ThaliTest[2372:2216273] multipeer session: reset timer
2015-12-02 21:15:02.103 ThaliTest[2372:2216273] multipeer session: stop timer
2015-12-02 21:15:02.104 ThaliTest[2372:2216273] multipeer session: start timer: 0x1a4d24e0
2015-,12-02 21:15:02.105 ThaliTest[2372:2216273] server: disconnecting to refresh session (Apple-Iphone5-1_PT3314)
2015-12-02 21:15:02.105 ThaliTest[2372:2216273] server session: disconnect
2015-12-02 21:15:02.106 ThaliTest[2372:2216273] server session: stateC,hange:2->0 Apple-Iphone5-1_PT3314
2015-12-02 21:15:02.109 ThaliTest[2372:2216273] server session: connect
2015-12-02 21:15:02.110 ThaliTest[2372:2216273] server session: stateChange:0->1 Apple-Iphone5-1_PT3314
2015-12-02T20:15:02.112Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-02 21:15:02.131 ThaliTest[2372:2216273] server: accepting invitation Apple-Iphone5-1_PT3314
,2015-12-02 21:15:04.429 ThaliTest[2372:2217248] server session: connected
2015-12-02 21:15:04.430 ThaliTest[2372:2217248] server session: stateChange:1->2 Apple-Iphone5-1_PT3314
,2015-12-02 21:15:04.437 ThaliTest[2372:2216273] server relay: connected (to port: 49690)
2015-12-02T20:15:04.439Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:15:04.518Z SendDataTCPServer.js: TCP/IP server has received 5952 bytes of data
,2015-12-02T20:15:04.533Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02 21:15:13.619 ThaliTest[2372:2216273] client: lost peer: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:15:13.620 ThaliTest[2372:2216273] client session: onPeerLost: Apple-Iphone6-1_PT3258.XmE3ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 21:15:13.996 ThaliTest[2372:2216273] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 21:15:14.528 ThaliTest[2372:2217186] server session: not connected Apple-Iphone5-1_PT3314
,2015-12-02 21:15:25.054 ThaliTest[2372:2216273] multipeer session: reset timer
2015-12-02 21:15:25.055 ThaliTest[2372:2216273] multipeer session: stop timer
2015-12-02 21:15:25.055 ThaliTest[2372:2216273] multipeer session: start timer: 0x1a4d24e0
2015-,12-02 21:15:25.056 ThaliTest[2372:2216273] server: disconnecting to refresh session (Apple-Iphone5-1_PT3314)
2015-12-02 21:15:25.057 ThaliTest[2372:2216273] server session: disconnect
2015-12-02 21:15:25.058 ThaliTest[2372:2216273] server session: stateC,hange:2->0 Apple-Iphone5-1_PT3314
2015-12-02 21:15:25.062 ThaliTest[2372:2216273] server session: connect
2015-12-02 21:15:25.063 ThaliTest[2372:2216273] server session: stateChange:0->1 Apple-Iphone5-1_PT3314
2015-12-02T20:15:25.067Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-02 21:15:25.087 ThaliTest[2372:2216273] server: accepting invitation Apple-Iphone5-1_PT3314
,2015-12-02 21:15:27.637 ThaliTest[2372:2217340] server session: connected
2015-12-02 21:15:27.638 ThaliTest[2372:2217340] server session: stateChange:1->2 Apple-Iphone5-1_PT3314
,2015-12-02 21:15:27.645 ThaliTest[2372:2216273] server relay: connected (to port: 49690)
,2015-12-02T20:15:27.657Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:15:27.847Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-12-02T20:15:27.863Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02 21:15:37.729 ThaliTest[2372:2217246] server session: not connected Apple-Iphone5-1_PT3314
,2015-12-02 21:15:44.592 ThaliTest[2372:2216273] client: lost peer: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:15:44.592 ThaliTest[2372:2216273] client session: onPeerLost: Apple-Iphone6-1_PT3258.XmE3ag==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 21:15:47.018 ThaliTest[2372:2216273] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 21:15:49.132 ThaliTest[2372:2216273] multipeer session: reset timer
2015-12-02 21:15:49.133 ThaliTest[2372:2216273] multipeer session: stop timer
2015-12-02 21:15:49.133 ThaliTest[2372:2216273] multipeer session: start timer: 0x1a4d24e0
2015-,12-02 21:15:49.134 ThaliTest[2372:2216273] server: disconnecting to refresh session (Apple-Iphone5-1_PT3314)
2015-12-02 21:15:49.134 ThaliTest[2372:2216273] server session: disconnect
2015-12-02 21:15:49.135 ThaliTest[2372:2216273] server session: stateC,hange:2->0 Apple-Iphone5-1_PT3314
2015-12-02 21:15:49.141 ThaliTest[2372:2216273] server session: connect
2015-12-02 21:15:49.142 ThaliTest[2372:2216273] server session: stateChange:0->1 Apple-Iphone5-1_PT3314
,2015-12-02T20:15:49.153Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-02 21:15:49.159 ThaliTest[2372:2216273] server: accepting invitation Apple-Iphone5-1_PT3314
,2015-12-02 21:15:51.749 ThaliTest[2372:2217396] server session: connected
2015-12-02 21:15:51.750 ThaliTest[2372:2217396] server session: stateChange:1->2 Apple-Iphone5-1_PT3314
,2015-12-02 21:15:51.757 ThaliTest[2372:2216273] server relay: connected (to port: 49690)
,2015-12-02T20:15:51.766Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:15:51.920Z SendDataTCPServer.js: TCP/IP server has received 6944 bytes of data
,2015-12-02T20:15:51.934Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02 21:16:01.846 ThaliTest[2372:2217246] server session: not connected Apple-Iphone5-1_PT3314
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
,stop current!
,testSendData stopped
,2015-12-02 21:16:02.178 ThaliTest[2372:2216398] jxcore: stopBroadcasting
2015-12-02 21:16:02.179 ThaliTest[2372:2216398] THEMultipeerSession stopping peer
2015-12-02 21:16:02.180 ThaliTest[2372:2216398] multipeer session: stop timer
2015-12-02 21:16:02.,181 ThaliTest[2372:2216398] server session: disconnect
2015-12-02 21:16:02.181 ThaliTest[2372:2216398] server session: stateChange:2->0 Apple-Iphone5-1_PT3314
,2015-12-02 21:16:02.250 ThaliTest[2372:2216398] server session: disconnect
,2015-12-02 21:16:02.252 ThaliTest[2372:2216398] server session: stateChange:2->0 Apple-Iphone6-1_PT3258
,2015-12-02 21:16:02.257 ThaliTest[2372:2216398] server session: disconnect
,2015-12-02 21:16:02.258 ThaliTest[2372:2216398] server session: stateChange:2->0 Apple-IpadAir2-1_PT369
,2015-12-02 21:16:02.264 ThaliTest[2372:2216398] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-02T20:16:02.281Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T20:16:02.281Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T20:16:02.282Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T20:16:02.282Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT3314.VcnsbA==\",\"time\":3656,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone6-1_PT3258.XmE3ag==\",\"time\":3688,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-IpadAir2-1_PT369.LHPK5g==\",\"time\":105807,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received

```
