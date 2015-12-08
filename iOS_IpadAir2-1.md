#### Test 52971095c1e9930_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52971095c1e9930/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/080FA62D-555B-4CA8-AD98-537932498779/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/080FA62D-555B-4CA8-AD98-537932498779/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52971095c1e9930/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52971095c1e9930/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/50D03069-47D7-4B06-8E71-ED376A5B3485/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51295"
,(lldb)     command script import "/tmp/080FA62D-555B-4CA8-AD98-537932498779/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 17:45:35.362 ThaliTest[501:296217] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AD118EC8-C798-4BCC-ADCA-2D30BD64AD5E/Library/Cookies/Cookies.binarycookies
,2015-12-08 17:45:35.374 ThaliTest[501:296217] <CATransformLayer: 0x16645d90> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-08 17:45:35.375 ThaliTest[501:296217] <CATransformLayer: 0x16545d30> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-08 17:45:35.375 ThaliTest[501:296217] <CATransformLayer: 0x16546ea0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-08 17:45:35.662 ThaliTest[501:296217] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 17:45:35.663 ThaliTest[501:296217] Multi-tasking -> Device: YES, App: YES
,2015-12-08 17:45:35.671 ThaliTest[501:296217] Unlimited access to network resources
,2015-12-08 17:45:35.677 ThaliTest[501:296217] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 17:45:44.670 ThaliTest[501:296217] Resetting plugins due to page load.
,2015-12-08 17:45:47.234 ThaliTest[501:296217] Finished load of: file:///var/mobile/Containers/Bundle/Application/50D03069-47D7-4B06-8E71-ED376A5B3485/ThaliTest.app/www/index.html
,2015-12-08 17:45:47.378 ThaliTest[501:296217] JXcore Cordova plugin initializing
,2015-12-08 17:45:47.379 ThaliTest[501:296545] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-IpadAir2-1_PT6318
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
,serverPort is 51701
,2015-12-08 17:52:39.075 ThaliTest[501:296545] jxcore: startBroadcasting
,2015-12-08 17:52:39.089 ThaliTest[501:296545] server: starting Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:52:39.091 ThaliTest[501:296545] multipeer session: start timer: 0x18756900
2015-12-08 17:52:39.091 ThaliTest[501:296545] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6318
,2015-12-08 17:52:39.092 ThaliTest[501:296545] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-08T16:52:39.095Z SendDataTCPServer.js: TCP/IP server is bound to port: 51701
,2015-12-08 17:52:40.115 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1987.2bYzJA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08T16:52:40.122Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08T16:52:40.123Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08T16:52:40.123Z SendDataConnector.js: do connect now
,2015-12-08 17:52:40.124 ThaliTest[501:296545] jxcore: connect Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:40.125 ThaliTest[501:296545] client session: connect
,2015-12-08 17:52:40.125 ThaliTest[501:296545] client session: stateChange:0->1 Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:40.238 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5978.hVAckA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:52:40.257 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-08 17:52:43.219 ThaliTest[501:297224] client session: connected
,2015-12-08 17:52:43.220 ThaliTest[501:297224] client session: stateChange:1->2 Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:43.269 ThaliTest[501:297223] client session: fireConnectCallback: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:52:43.270 ThaliTest[501:297223] jxcore: connect: success
,2015-12-08T16:52:43.271Z SendDataConnector.js: CLIENT connected to 51704, error: null
,2015-12-08T16:52:43.272Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:52:43.274 ThaliTest[501:296217] client: relay established
2015-12-08 17:52:43.275 ThaliTest[501:296217] client: new accepted socket: 0x18758310
,2015-12-08T16:52:43.291Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:52:43.562Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-08T16:52:43.597Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T16:52:43.597Z SendDataConnector.js: got all data for this round
,2015-12-08T16:52:43.598Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:52:43.598Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:52:43.599 ThaliTest[501:296545] jxcore: disconnect
,2015-12-08 17:52:43.600 ThaliTest[501:296545] client session: disconnectFromPeer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:52:43.600 ThaliTest[501:296545] client session: disconnect
2015-12-08 17:52:43.600 ThaliTest[501:296545] client session: stateChange:2->0 Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:43.603 ThaliTest[501:296545] jxcore: disconnect: success
2015-12-08T16:52:43.603Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1987.2bYzJA==
,---- round done--------
device[2]: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08T16:52:43.604Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08T16:52:43.604Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08T16:52:43.604Z SendDataConnector.js: do connect now
,2015-12-08 17:52:43.605 ThaliTest[501:296545] jxcore: connect Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:43.605 ThaliTest[501:296545] client session: connect
,2015-12-08 17:52:43.605 ThaliTest[501:296545] client session: stateChange:0->1 Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:45.567 ThaliTest[501:296217] multipeer session: reset timer
2015-12-08 17:52:45.568 ThaliTest[501:296217] multipeer session: stop timer
2015-12-08 17:52:45.568 ThaliTest[501:296217] multipeer session: start timer: 0x18756900
2015-12-08 ,17:52:45.568 ThaliTest[501:296217] server session: connect
,2015-12-08 17:52:45.569 ThaliTest[501:296217] server session: stateChange:0->1 Apple-Iphone5-1_PT5966
,2015-12-08 17:52:45.577 ThaliTest[501:296217] server: accepting invitation Apple-Iphone5-1_PT5966
2015-12-08 17:52:45.578 ThaliTest[501:296217] multipeer session: reset timer
2015-12-08 17:52:45.578 ThaliTest[501:296217] multipeer session: stop timer
20,15-12-08 17:52:45.578 ThaliTest[501:296217] multipeer session: start timer: 0x18756900
2015-12-08 17:52:45.579 ThaliTest[501:296217] server session: connect
2015-12-08 17:52:45.579 ThaliTest[501:296217] server session: stateChange:0->1 Apple-Iphone6-1_PT1987
,2015-12-08 17:52:45.586 ThaliTest[501:296217] server: accepting invitation Apple-Iphone6-1_PT1987
,2015-12-08 17:52:47.623 ThaliTest[501:297230] client session: connected
2015-12-08 17:52:47.624 ThaliTest[501:297230] client session: stateChange:1->2 Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:47.669 ThaliTest[501:297223] client session: fireConnectCallback: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:52:47.670 ThaliTest[501:297223] jxcore: connect: success
,2015-12-08T16:52:47.671Z SendDataConnector.js: CLIENT connected to 51707, error: null
,2015-12-08T16:52:47.672Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:52:47.675 ThaliTest[501:296217] client: relay established
2015-12-08 17:52:47.675 ThaliTest[501:296217] client: new accepted socket: 0x184c1f90
,2015-12-08T16:52:47.688Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:52:48.117Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-08T16:52:48.131Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-08T16:52:48.191Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T16:52:48.191Z SendDataConnector.js: got all data for this round
,2015-12-08T16:52:48.193Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:52:48.193Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:52:48.194 ThaliTest[501:296545] jxcore: disconnect
2015-12-08 17:52:48.194 ThaliTest[501:296545] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:52:48.194 ThaliTest[501:296545] client session: disconnect
2015-12-08 17:52:48.195 ThaliTest[501:296545] client session: stateChange:2->0 Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:48.202 ThaliTest[501:296545] jxcore: disconnect: success
2015-12-08T16:52:48.203Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5978.hVAckA==
---- round done--------
,device[3]: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08T16:52:48.204Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08T16:52:48.204Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5966.KrGtFw==
20,15-12-08T16:52:48.204Z SendDataConnector.js: do connect now
2015-12-08 17:52:48.205 ThaliTest[501:296545] jxcore: connect Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:52:48.207 ThaliTest[501:296545] client session: connect
2015-12-08 17:52:48.207 Thali,Test[501:296545] client session: stateChange:0->1 Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:52:48.254 ThaliTest[501:297231] server session: connected
2015-12-08 17:52:48.255 ThaliTest[501:297231] server session: stateChange:1->2 Apple-Iphone6-1_PT1987
,2015-12-08 17:52:48.279 ThaliTest[501:297223] server session: connected
2015-12-08 17:52:48.279 ThaliTest[501:297223] server session: stateChange:1->2 Apple-Iphone5-1_PT5966
,2015-12-08 17:52:48.283 ThaliTest[501:296217] server relay: connected (to port: 51701)
,2015-12-08T16:52:48.287Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08 17:52:48.298 ThaliTest[501:296217] server relay: connected (to port: 51701)
,2015-12-08T16:52:48.301Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:52:48.616Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-08T16:52:48.630Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-08T16:52:48.643Z SendDataTCPServer.js: TCP/IP server has received 67748 bytes of data
,2015-12-08T16:52:48.656Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:52:48.713 ThaliTest[501:297230] server session: not connected Apple-Iphone6-1_PT1987
,2015-12-08 17:52:48.886 ThaliTest[501:296217] multipeer session: reset timer
2015-12-08 17:52:48.886 ThaliTest[501:296217] multipeer session: stop timer
2015-12-08 17:52:48.887 ThaliTest[501:296217] multipeer session: start timer: 0x18756900
,2015-12-08 17:52:48.887 ThaliTest[501:296217] server session: connect
2015-12-08 17:52:48.887 ThaliTest[501:296217] server session: stateChange:0->1 Apple-Iphone5s-1_PT5978
,2015-12-08 17:52:48.890 ThaliTest[501:296217] server: accepting invitation Apple-Iphone5s-1_PT5978
,2015-12-08T16:52:49.173Z SendDataTCPServer.js: TCP/IP server has received 43516 bytes of data
,2015-12-08T16:52:49.188Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-08T16:52:49.239Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-08T16:52:49.254Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:52:49.362 ThaliTest[501:297272] server session: not connected Apple-Iphone5-1_PT5966
,2015-12-08 17:52:50.979 ThaliTest[501:297223] client session: connected
,2015-12-08 17:52:50.980 ThaliTest[501:297223] client session: stateChange:1->2 Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:52:50.984 ThaliTest[501:297223] client session: fireConnectCallback: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:52:50.984 ThaliTest[501:297223] jxcore: connect: success
,2015-12-08T16:52:50.985Z SendDataConnector.js: CLIENT connected to 51712, error: null
2015-12-08T16:52:50.986Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:52:50.989 ThaliTest[501:296217] client: relay established
2015-12-08 17:52:50.990 ThaliTest[501:296217] client: new accepted socket: 0x1982bb70
,2015-12-08T16:52:51.004Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:52:51.295Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-08T16:52:51.331Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T16:52:51.332Z SendDataConnector.js: got all data for this round
,2015-12-08T16:52:51.332Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:52:51.332Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:52:51.333 ThaliTest[501:296545] jxcore: disconnect
2015-12-08 17:52:51.333 ThaliTest[501:296545] client session: disconnectFromPeer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:52:51.333 ThaliTest[501:296545] client session: disconnect
2015-12-08 17:52:51.333 ThaliTest[501:296545] client session: stateChange:2->0 Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:52:51.336 ThaliTest[501:296545] jxcore: disconnect: success
,2015-12-08T16:52:51.338Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5966.KrGtFw==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT6318","time":12280,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT1987.2bYzJA==","time":3476,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1,_PT5978.hVAckA==","time":4588,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT5966.KrGtFw==","time":3128,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4588 ms, 99% : 4588 ms, 95 : 4588 ms, 90% : 4588 ms.
,Result count 3, range 3128 ms to  4588 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-08T16:52:51.347Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:52:51.348Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:52:51.455 ThaliTest[501:297230] server session: connected
2015-12-08 17:52:51.457 ThaliTest[501:297230] server session: stateChange:1->2 Apple-Iphone5s-1_PT5978
,2015-12-08 17:52:51.472 ThaliTest[501:296217] server relay: connected (to port: 51701)
,2015-12-08T16:52:51.481Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:52:51.795Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-08T16:52:51.811Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-08T16:52:51.960Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-08T16:52:51.986Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-08T16:52:52.003Z SendDataTCPServer.js: TCP/IP server has received 96076 bytes of data
,2015-12-08T16:52:52.018Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:52:52.285 ThaliTest[501:297292] server session: not connected Apple-Iphone5s-1_PT5978
,2015-12-08 17:53:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:53:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:53:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:53:18.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:53:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:53:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:53:48.916 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:53:48.954 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:54:18.887 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:54:18.915 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:54:18.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:54:18.916 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-08 17:54:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:54:48.911 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:54:48.912 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:54:49.210 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:55:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:55:18.916 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:55:18.916 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:55:18.917 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:55:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:55:48.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:55:48.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:55:49.622 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:56:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:56:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:56:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:56:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:56:50.324 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:57:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:57:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:57:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:57:18.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:57:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:57:48.912 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:57:48.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:57:52.744 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:58:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:58:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:58:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:58:18.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:58:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:58:48.912 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:58:48.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:58:50.008 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:59:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 17:59:18.917 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:59:18.918 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:59:18.920 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:59:48.888 ThaliTest[501:296217] multipeer session: restart
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,2015-12-08 17:59:49.630 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:59:49.712 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-08 17:59:50.571 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
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
,2015-12-08 18:00:18.887 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:00:18.912 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:00:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:00:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
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
,2015-12-08 18:00:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:00:48.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:00:48.916 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:00:49.347 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,2015-12-08 18:01:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:01:18.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:01:18.915 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:01:18.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:01:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:01:48.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:01:48.916 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:01:49.292 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:02:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:02:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:02:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:02:18.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:02:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:02:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:02:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:02:49.163 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:03:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:03:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:03:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:03:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:03:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:03:48.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:03:48.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:03:48.973 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:04:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:04:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:04:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:04:18.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:04:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:04:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:04:48.917 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:04:49.377 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:05:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:05:18.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:05:18.915 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:05:18.916 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:05:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:05:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:05:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:05:49.120 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-08 18:06:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:06:18.916 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:06:18.916 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:06:18.917 ThaliTest[501:296217] client: foun,d peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:06:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:06:48.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:06:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:06:49.317 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:07:18.887 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:07:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:07:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:07:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:07:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:07:48.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:07:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:07:49.111 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:08:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:08:18.912 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:08:18.912 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:08:18.913 ThaliTest[501:296217] client: foun,d peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:08:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:08:48.912 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:08:48.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:08:49.383 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:09:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:09:18.912 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:09:18.912 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:09:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:09:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:09:48.912 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:09:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:09:49.134 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-08 18:10:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:10:18.912 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:10:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:10:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:10:48.887 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:10:48.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:10:48.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:10:49.043 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:11:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:11:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:11:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:11:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:11:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:11:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:11:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:11:48.914 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:12:18.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:12:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:12:18.913 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:12:18.914 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:12:48.888 ThaliTest[501:296217] multipeer session: restart
,2015-12-08 18:12:48.916 ThaliTest[501:296217] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:12:48.916 ThaliTest[501:296217] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:12:48.917 ThaliTest[501:296217] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==

```
