#### Test 52971095ef317fc_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52971095ef317fc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/84919097-02E6-4704-8A63-DB95BEB3EDC3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/84919097-02E6-4704-8A63-DB95BEB3EDC3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52971095ef317fc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52971095ef317fc/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0F87825A-0741-49D8-ACBD-7A66160FBD23/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51168"
,(lldb)     command script import "/tmp/84919097-02E6-4704-8A63-DB95BEB3EDC3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 17:07:36.666 ThaliTest[487:290091] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/27C15B99-887F-44E3-9B29-CBB53553D3F4/Library/Cookies/Cookies.binarycookies
,2015-12-08 17:07:36.679 ThaliTest[487:290091] <CATransformLayer: 0x15648650> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-08 17:07:36.681 ThaliTest[487:290091] <CATransformLayer: 0x1564b240> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-08 17:07:36.682 ThaliTest[487:290091] <CATransformLayer: 0x155672d0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-08 17:07:36.986 ThaliTest[487:290091] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 17:07:36.987 ThaliTest[487:290091] Multi-tasking -> Device: YES, App: YES
,2015-12-08 17:07:36.995 ThaliTest[487:290091] Unlimited access to network resources
,2015-12-08 17:07:37.001 ThaliTest[487:290091] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 17:07:45.721 ThaliTest[487:290091] Resetting plugins due to page load.
,2015-12-08 17:07:49.180 ThaliTest[487:290091] Finished load of: file:///var/mobile/Containers/Bundle/Application/0F87825A-0741-49D8-ACBD-7A66160FBD23/ThaliTest.app/www/index.html
,2015-12-08 17:07:49.321 ThaliTest[487:290091] JXcore Cordova plugin initializing
,2015-12-08 17:07:49.322 ThaliTest[487:290353] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-IpadAir2-1_PT4957
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
,serverPort is 51316
,2015-12-08 17:14:48.044 ThaliTest[487:290353] jxcore: startBroadcasting
,2015-12-08 17:14:48.057 ThaliTest[487:290353] server: starting Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:14:48.059 ThaliTest[487:290353] multipeer session: start timer: 0x175189c0
2015-12-08 17:14:48.059 ThaliTest[487:290353] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT4957
,2015-12-08 17:14:48.061 ThaliTest[487:290353] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-08T16:14:48.064Z SendDataTCPServer.js: TCP/IP server is bound to port: 51316
,2015-12-08 17:14:48.635 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7651.u5AQgA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08T16:14:48.642Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08T16:14:48.642Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08T16:14:48.643Z SendDataConnector.js: do connect now
,2015-12-08 17:14:48.644 ThaliTest[487:290353] jxcore: connect Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:14:48.645 ThaliTest[487:290353] client session: connect
,2015-12-08 17:14:48.645 ThaliTest[487:290353] client session: stateChange:0->1 Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:14:48.675 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8010.swwphA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:14:50.053 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7186.b/2OUQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:14:53.087 ThaliTest[487:291074] client session: connected
2015-12-08 17:14:53.088 ThaliTest[487:291074] client session: stateChange:1->2 Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:14:53.106 ThaliTest[487:291074] client session: fireConnectCallback: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:14:53.107 ThaliTest[487:291074] jxcore: connect: success
,2015-12-08T16:14:53.109Z SendDataConnector.js: CLIENT connected to 51319, error: null
,2015-12-08T16:14:53.110Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:14:53.112 ThaliTest[487:290091] client: relay established
2015-12-08 17:14:53.113 ThaliTest[487:290091] client: new accepted socket: 0x1771d350
,2015-12-08T16:14:53.129Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:14:53.573Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-08T16:14:53.622Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-08T16:14:53.637Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T16:14:53.637Z SendDataConnector.js: got all data for this round
,2015-12-08T16:14:53.639Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:14:53.640Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:14:53.641 ThaliTest[487:290353] jxcore: disconnect
,2015-12-08 17:14:53.642 ThaliTest[487:290353] client session: disconnectFromPeer: Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:14:53.643 ThaliTest[487:290353] client session: disconnect
,2015-12-08 17:14:53.643 ThaliTest[487:290353] client session: stateChange:2->0 Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:14:53.697 ThaliTest[487:290091] multipeer session: reset timer
2015-12-08 17:14:53.697 ThaliTest[487:290091] multipeer session: stop timer
2015-12-08 17:14:53.697 ThaliTest[487:290091] multipeer session: start timer: 0x175189c0
,2015-12-08 17:14:53.698 ThaliTest[487:290091] server session: connect
,2015-12-08 17:14:53.698 ThaliTest[487:290091] server session: stateChange:0->1 Apple-Iphone6-1_PT7651
,2015-12-08 17:14:53.702 ThaliTest[487:290091] server: accepting invitation Apple-Iphone6-1_PT7651
,2015-12-08 17:14:53.717 ThaliTest[487:290353] jxcore: disconnect: success
,2015-12-08T16:14:53.718Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7651.u5AQgA==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08T16:14:53.720Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08T16:14:53.721Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08T16:14:53.721Z SendDataConnector.js: do connect now
,2015-12-08 17:14:53.721 ThaliTest[487:290353] jxcore: connect Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:14:53.722 ThaliTest[487:290353] client session: connect
,2015-12-08 17:14:53.723 ThaliTest[487:290353] client session: stateChange:0->1 Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:14:54.883 ThaliTest[487:290091] multipeer session: reset timer
2015-12-08 17:14:54.883 ThaliTest[487:290091] multipeer session: stop timer
2015-12-08 17:14:54.883 ThaliTest[487:290091] multipeer session: start timer: 0x175189c0
,2015-12-08 17:14:54.884 ThaliTest[487:290091] server session: connect
2015-12-08 17:14:54.884 ThaliTest[487:290091] server session: stateChange:0->1 Apple-Iphone5-1_PT8010
,2015-12-08 17:14:54.890 ThaliTest[487:290091] server: accepting invitation Apple-Iphone5-1_PT8010
,2015-12-08 17:14:56.918 ThaliTest[487:291074] server session: connected
,2015-12-08 17:14:56.918 ThaliTest[487:291074] server session: stateChange:1->2 Apple-Iphone6-1_PT7651
,2015-12-08 17:14:56.982 ThaliTest[487:290091] server relay: connected (to port: 51316)
,2015-12-08T16:14:56.986Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:14:57.300Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-08T16:14:57.314Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-08T16:14:57.330Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:14:57.362 ThaliTest[487:291082] server session: not connected Apple-Iphone6-1_PT7651
,2015-12-08 17:14:57.785 ThaliTest[487:291126] server session: connected
2015-12-08 17:14:57.785 ThaliTest[487:291126] server session: stateChange:1->2 Apple-Iphone5-1_PT8010
,2015-12-08 17:14:57.801 ThaliTest[487:290091] server relay: connected (to port: 51316)
,2015-12-08T16:14:57.809Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08 17:14:58.284 ThaliTest[487:291126] client session: connected
2015-12-08 17:14:58.285 ThaliTest[487:291126] client session: stateChange:1->2 Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:14:58.303 ThaliTest[487:291082] client session: fireConnectCallback: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:14:58.303 ThaliTest[487:291082] jxcore: connect: success
,2015-12-08T16:14:58.305Z SendDataConnector.js: CLIENT connected to 51324, error: null
,2015-12-08T16:14:58.306Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:14:58.309 ThaliTest[487:290091] client: relay established
,2015-12-08 17:14:58.309 ThaliTest[487:290091] client: new accepted socket: 0x15584090
,2015-12-08T16:14:58.322Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:14:58.586Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08T16:14:58.890Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-08T16:14:59.084Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-08T16:14:59.591Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T16:14:59.591Z SendDataConnector.js: got all data for this round
2015-12-08T16:14:59.593Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:14:59.594Z SendDataCo,nnector.js: CLIENT closeClientSocket
,2015-12-08 17:14:59.594 ThaliTest[487:290353] jxcore: disconnect
2015-12-08 17:14:59.596 ThaliTest[487:290353] client session: disconnectFromPeer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:14:59.597 ThaliTest[487:290353] client session: disconnect
,2015-12-08 17:14:59.597 ThaliTest[487:290353] client session: stateChange:2->0 Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:14:59.601 ThaliTest[487:291126] server session: not connected Apple-Iphone5-1_PT8010
,2015-12-08 17:14:59.671 ThaliTest[487:290353] jxcore: disconnect: success
2015-12-08T16:14:59.672Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8010.swwphA==
---- round done--------
,device[3]: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08T16:14:59.674Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08T16:14:59.674Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08T16:14:59.674Z SendDataConnector.js: do connect now
,2015-12-08 17:14:59.675 ThaliTest[487:290353] jxcore: connect Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:14:59.676 ThaliTest[487:290353] client session: connect
2015-12-08 17:14:59.676 ThaliTest[487:290353] client session: stateChange:0->1 Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:15:00.380 ThaliTest[487:290091] multipeer session: reset timer
2015-12-08 17:15:00.380 ThaliTest[487:290091] multipeer session: stop timer
2015-12-08 17:15:00.381 ThaliTest[487:290091] multipeer session: start timer: 0x175189c0
2015-12-08 ,17:15:00.381 ThaliTest[487:290091] server session: connect
,2015-12-08 17:15:00.382 ThaliTest[487:290091] server session: stateChange:0->1 Apple-Iphone5s-1_PT7186
,2015-12-08 17:15:00.392 ThaliTest[487:290091] server: accepting invitation Apple-Iphone5s-1_PT7186
,2015-12-08 17:15:03.168 ThaliTest[487:291111] client session: connected
,2015-12-08 17:15:03.169 ThaliTest[487:291111] client session: stateChange:1->2 Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:15:03.172 ThaliTest[487:291111] client session: fireConnectCallback: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:15:03.172 ThaliTest[487:291111] jxcore: connect: success
,2015-12-08T16:15:03.173Z SendDataConnector.js: CLIENT connected to 51327, error: null
,2015-12-08T16:15:03.174Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:15:03.176 ThaliTest[487:290091] client: relay established
2015-12-08 17:15:03.177 ThaliTest[487:290091] client: new accepted socket: 0x1551ba90
,2015-12-08T16:15:03.190Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:15:03.574Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-08T16:15:03.587Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-08T16:15:03.600Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-08T16:15:03.613Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-08T16:15:03.651Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-08T16:15:03.666Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08 17:15:03.666 ThaliTest[487:291111] server session: connected
2015-12-08 17:15:03.666 ThaliTest[487:291111] server session: stateChange:1->2 Apple-Iphone5s-1_PT7186
,2015-12-08T16:15:03.668Z SendDataConnector.js: got all data for this round
,2015-12-08T16:15:03.669Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:15:03.669Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:15:03.670 ThaliTest[487:290353] jxcore: disconnect
,2015-12-08 17:15:03.671 ThaliTest[487:290353] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:15:03.672 ThaliTest[487:290353] client session: disconnect
,2015-12-08 17:15:03.672 ThaliTest[487:290353] client session: stateChange:2->0 Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:15:03.682 ThaliTest[487:290091] server relay: connected (to port: 51316)
,2015-12-08 17:15:03.746 ThaliTest[487:290353] jxcore: disconnect: success
,2015-12-08T16:15:03.747Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7186.b/2OUQ==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT4957","time":15721,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7651.u5AQgA==","time":4996,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_,PT8010.swwphA==","time":5871,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7186.b/2OUQ==","time":3994,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 5871 ms, 99% : 5871 ms, 95 : 5871 ms, 90% : 5871 ms.
,Result count 3, range 3994 ms to  5871 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-08T16:15:03.758Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:15:03.758Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08T16:15:03.772Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:15:04.577Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-08T16:15:04.592Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-08T16:15:04.644Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-08T16:15:04.656Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-08T16:15:04.770Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-08T16:15:04.784Z SendDataTCPServer.js: TCP/IP server has received 96076 bytes of data
,2015-12-08T16:15:04.801Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:15:04.836 ThaliTest[487:291073] server session: not connected Apple-Iphone5s-1_PT7186
,2015-12-08 17:15:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:15:30.413 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:15:30.413 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:15:30.414 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:16:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:16:00.410 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:16:00.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:16:00.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:16:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:16:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:16:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:16:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:17:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:17:00.401 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:17:00.401 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:17:00.401 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:17:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:17:30.415 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:17:30.415 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:17:30.415 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:18:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:18:00.414 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:18:00.415 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:18:00.415 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:18:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:18:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:18:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:18:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:19:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:19:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:19:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:19:00.412 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:19:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:19:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:19:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:19:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:20:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:20:01.150 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:20:01.151 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:20:01.151 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:20:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:20:30.409 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:20:30.409 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:20:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:21:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:21:00.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:21:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:21:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:21:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:21:30.412 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:21:30.412 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:21:30.412 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:22:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:22:00.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:22:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:22:00.412 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:22:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:22:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:22:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:22:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:23:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:23:00.408 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:23:00.408 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:23:00.408 ThaliTest[487:290091] client: foun,d peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:23:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:23:30.409 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:23:31.200 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:23:31.201 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:24:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:24:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:24:00.412 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:24:00.412 ThaliTest[487:290091] client: foun,d peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:24:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:24:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:24:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:24:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:25:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:25:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:25:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:25:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:25:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:25:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:25:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:25:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:26:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:26:00.413 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:26:00.413 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:26:00.413 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:26:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:26:30.412 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:26:30.413 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:26:30.413 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:27:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:27:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:27:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:27:00.412 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:27:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:27:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:27:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:27:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:28:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:28:00.412 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:28:00.412 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:28:00.412 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:28:30.383 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:28:30.412 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:28:30.412 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:28:30.412 ThaliTest[487:290091] client: foun,d peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:29:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:29:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:29:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:29:00.411 ThaliTest[487:290091] client: foun,d peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:29:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:29:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:29:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:29:30.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:30:00.383 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:30:00.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:30:00.410 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:30:00.410 ThaliTest[487:290091] client: fou,nd peer: Apple-Iphone5-1_PT8010.swwphA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:30:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:30:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:30:30.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:30:30.410 ThaliTest[487:290091] client: fou,nd peer: Apple-Iphone5-1_PT8010.swwphA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:31:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:31:00.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:31:00.410 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:31:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:31:30.383 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:31:30.412 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:31:30.412 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:31:30.412 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:32:00.382 ThaliTest[487:290091] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:32:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:32:30.409 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:32:30.409 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:32:30.409 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:33:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:33:00.410 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:33:00.410 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:33:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:33:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:33:30.408 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:33:30.408 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:33:30.409 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:34:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:34:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:34:00.411 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:34:00.412 ThaliTest[487:290091] client: fou,nd peer: Apple-Iphone5-1_PT8010.swwphA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:34:30.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:34:30.409 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:34:30.409 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:34:30.409 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:35:00.382 ThaliTest[487:290091] multipeer session: restart
,2015-12-08 17:35:00.409 ThaliTest[487:290091] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:35:00.409 ThaliTest[487:290091] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:35:00.409 ThaliTest[487:290091] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==

```
