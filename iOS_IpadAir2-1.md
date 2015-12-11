#### Test 534296758dfd01f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/534296758dfd01f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/E6D21267-26C8-4125-A0CD-0EBDFC98B73A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E6D21267-26C8-4125-A0CD-0EBDFC98B73A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/534296758dfd01f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/534296758dfd01f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6855F897-8358-4012-8FCC-C8C90905DABF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54404"
,(lldb)     command script import "/tmp/E6D21267-26C8-4125-A0CD-0EBDFC98B73A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 20:05:52.589 ThaliTest[862:747507] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5545648F-B176-40E4-84F9-204A9C77B4C9/Library/Cookies/Cookies.binarycookies
,2015-12-11 20:05:52.607 ThaliTest[862:747507] <CATransformLayer: 0x17d33c80> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-11 20:05:52.607 ThaliTest[862:747507] <CATransformLayer: 0x17f22af0> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-11 20:05:52.608 ThaliTest[862:747507] <CATransformLayer: 0x17f23c50> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-11 20:05:52.930 ThaliTest[862:747507] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 20:05:52.930 ThaliTest[862:747507] Multi-tasking -> Device: YES, App: YES
,2015-12-11 20:05:52.938 ThaliTest[862:747507] Unlimited access to network resources
,2015-12-11 20:05:52.944 ThaliTest[862:747507] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 20:06:01.814 ThaliTest[862:747507] Resetting plugins due to page load.
,2015-12-11 20:06:05.118 ThaliTest[862:747507] Finished load of: file:///var/mobile/Containers/Bundle/Application/6855F897-8358-4012-8FCC-C8C90905DABF/ThaliTest.app/www/index.html
,2015-12-11 20:06:05.260 ThaliTest[862:747507] JXcore Cordova plugin initializing
2015-12-11 20:06:05.261 ThaliTest[862:747795] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Radios toggled
,my name is : Apple-IpadAir2-1_PT818
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 56444
,2015-12-11 20:12:38.019 ThaliTest[862:747795] jxcore: startBroadcasting
,2015-12-11 20:12:38.030 ThaliTest[862:747795] server: starting Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:12:38.031 ThaliTest[862:747795] multipeer session: start timer: 0x19e874c0
,2015-12-11 20:12:38.032 ThaliTest[862:747795] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT818
2015-12-11 20:12:38.032 ThaliTest[862:747795] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-11T19:12:38.035Z SendDataTCPServer.js: TCP/IP server is bound to port: 56444
,2015-12-11 20:12:39.072 ThaliTest[862:747507] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3759.Czrh3A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11T19:12:39.078Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11T19:12:39.079Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11T19:12:39.080Z SendDataConnector.js: do connect now
,2015-12-11 20:12:39.080 ThaliTest[862:747795] jxcore: connect Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:12:39.081 ThaliTest[862:747795] client session: connect
2015-12-11 20:12:39.082 ThaliTest[862:747795] client session: stateChange:0->1 Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:12:40.218 ThaliTest[862:747507] multipeer session: reset timer
2015-12-11 20:12:40.218 ThaliTest[862:747507] multipeer session: stop timer
2015-12-11 20:12:40.218 ThaliTest[862:747507] multipeer session: start timer: 0x19e874c0
2015-12-11 20:12:40.219 ThaliTest[862:747507] server session: connect
,2015-12-11 20:12:40.219 ThaliTest[862:747507] server session: stateChange:0->1 Apple-Iphone6-1_PT3759
,2015-12-11 20:12:40.226 ThaliTest[862:747507] server: accepting invitation Apple-Iphone6-1_PT3759
,2015-12-11 20:12:40.590 ThaliTest[862:747507] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5466.2TZtug==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 20:12:41.855 ThaliTest[862:747507] multipeer session: reset timer
,2015-12-11 20:12:41.856 ThaliTest[862:747507] multipeer session: stop timer
2015-12-11 20:12:41.856 ThaliTest[862:747507] multipeer session: start timer: 0x19e874c0
,2015-12-11 20:12:41.857 ThaliTest[862:747507] server session: connect
2015-12-11 20:12:41.857 ThaliTest[862:747507] server session: stateChange:0->1 Apple-Iphone5s-1_PT5466
,2015-12-11 20:12:41.865 ThaliTest[862:747507] server: accepting invitation Apple-Iphone5s-1_PT5466
,2015-12-11 20:12:42.822 ThaliTest[862:748445] server session: connected
2015-12-11 20:12:42.822 ThaliTest[862:748445] server session: stateChange:1->2 Apple-Iphone6-1_PT3759
,2015-12-11 20:12:42.952 ThaliTest[862:747507] server relay: connected (to port: 56444)
,2015-12-11T19:12:42.962Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T19:12:43.300Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-11 20:12:43.309 ThaliTest[862:748445] client session: connected
2015-12-11 20:12:43.309 ThaliTest[862:748445] client session: stateChange:1->2 Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11T19:12:43.315Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-11T19:12:43.330Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-11T19:12:43.344Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-11 20:12:43.410 ThaliTest[862:748444] client session: fireConnectCallback: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:12:43.410 ThaliTest[862:748444] jxcore: connect: success
,2015-12-11T19:12:43.412Z SendDataTCPServer.js: TCP/IP server has received 61178 bytes of data
,2015-12-11T19:12:43.415Z SendDataConnector.js: CLIENT connected to 56448, error: null
2015-12-11T19:12:43.416Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 20:12:43.418 ThaliTest[862:747507] client: relay established
2015-12-11 20:12:43.418 ThaliTest[862:747507] client: new accepted socket: 0x19f85d50
,2015-12-11T19:12:43.433Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-11T19:12:43.435Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T19:12:43.861Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-11T19:12:43.875Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T19:12:43.875Z SendDataConnector.js: got all data for this round
,2015-12-11T19:12:43.876Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T19:12:43.876Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 20:12:43.877 ThaliTest[862:747795] jxcore: disconnect
2015-12-11 20:12:43.878 ThaliTest[862:747795] client session: disconnectFromPeer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:12:43.878 ThaliTest[862:747795] client session: disconnect
,2015-12-11 20:12:43.878 ThaliTest[862:747795] client session: stateChange:2->0 Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:12:43.943 ThaliTest[862:747795] jxcore: disconnect: success
2015-12-11T19:12:43.943Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3759.Czrh3A==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11T19:12:43.945Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11T19:12:43.946Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11T19:12:43.946Z SendDataConnector.js: do connect now
2015-12-11 20:12:43.946 ThaliTest[862:747795] jxcore: connect Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:12:43.946 ThaliTest[862:747795] client session: connect
,2015-12-11 20:12:43.947 ThaliTest[862:747795] client session: stateChange:0->1 Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11T19:12:44.005Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 20:12:44.073 ThaliTest[862:748444] server session: not connected Apple-Iphone6-1_PT3759
,2015-12-11 20:12:44.086 ThaliTest[862:747507] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4192.mhrLvw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 20:12:44.381 ThaliTest[862:747507] multipeer session: reset timer
2015-12-11 20:12:44.381 ThaliTest[862:747507] multipeer session: stop timer
2015-12-11 20:12:44.381 ThaliTest[862:747507] multipeer session: start timer: 0x19e874c0
2015-12-11 ,20:12:44.382 ThaliTest[862:747507] server session: connect
2015-12-11 20:12:44.382 ThaliTest[862:747507] server session: stateChange:0->1 Apple-Iphone5-1_PT4192
,2015-12-11 20:12:44.386 ThaliTest[862:747507] server: accepting invitation Apple-Iphone5-1_PT4192
,2015-12-11 20:12:45.034 ThaliTest[862:748444] server session: connected
,2015-12-11 20:12:45.034 ThaliTest[862:748444] server session: stateChange:1->2 Apple-Iphone5s-1_PT5466
,2015-12-11 20:12:45.060 ThaliTest[862:747507] server relay: connected (to port: 56444)
,2015-12-11T19:12:45.063Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T19:12:45.363Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-11T19:12:45.379Z SendDataTCPServer.js: TCP/IP server has received 34898 bytes of data
,2015-12-11T19:12:45.400Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 20:12:45.495 ThaliTest[862:748517] server session: not connected Apple-Iphone5s-1_PT5466
,2015-12-11 20:12:47.137 ThaliTest[862:748445] server session: connected
2015-12-11 20:12:47.137 ThaliTest[862:748445] server session: stateChange:1->2 Apple-Iphone5-1_PT4192
,2015-12-11 20:12:47.195 ThaliTest[862:747507] server relay: connected (to port: 56444)
,2015-12-11T19:12:47.201Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T19:12:47.723Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-11T19:12:47.740Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-11T19:12:47.781Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-11T19:12:47.990Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-11T19:12:48.004Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-11T19:12:48.046Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-11T19:12:48.059Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 20:12:48.835 ThaliTest[862:748445] server session: not connected Apple-Iphone5-1_PT4192
,2015-12-11 20:13:13.408 ThaliTest[862:747507] client: lost peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:13:13.408 ThaliTest[862:747507] client session: onPeerLost: Apple-Iphone5-1_PT4192.mhrLvw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4192.mhrLvw==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-11 20:13:14.383 ThaliTest[862:747507] multipeer session: restart
,2015-12-11 20:13:14.409 ThaliTest[862:747507] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:13:14.410 ThaliTest[862:747507] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:13:21.591 ThaliTest[862:747507] client: lost peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:13:21.592 ThaliTest[862:747507] client session: onPeerLost: Apple-Iphone6-1_PT3759.Czrh3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3759.Czrh3A==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 20:13:24.248 ThaliTest[862:747507] client: lost peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:13:24.249 ThaliTest[862:747507] client session: onPeerLost: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:13:24.249 ThaliTest[862:747507] cli,ent session: onLinkFailure: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:13:24.249 ThaliTest[862:747507] client session: disconnect
,2015-12-11 20:13:24.249 ThaliTest[862:747507] client session: stateChange:1->0 Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:14:14.736 ThaliTest[862:748779] XPC connection interrupted
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_timeout called
,Error type "connect_timeout" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_timeout called
,Error type "connect_timeout" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_timeout called
,Error type "connect_timeout" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_timeout called
,Error type "connect_timeout" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_timeout called
,Error type "connect_timeout" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_timeout called
,Error type "connect_timeout" when connecting to the test server
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_timeout called
,Error type "connect_timeout" when connecting to the test server
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,timeout now
dun
,weAreDoneNow , resultArray.length: 1
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT818","time":1000043,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone6-1_PT3759.Czrh3A==","time":4796,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT5466.2TZtug==","time":0,"result":"Fail"}]}
,sendList : 100% : 4796 ms, 99% : 4796 ms, 95 : 4796 ms, 90% : 4796 ms.
Result count 1, range 4796 ms to  4796 ms.
sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 1 [50 %]
,- Peer ID : Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11T19:29:18.062Z SendDataConnector.js: CLIENT Stop now
,2015-12-11 20:29:18.062 ThaliTest[862:747795] jxcore: disconnect
,2015-12-11 20:29:18.063 ThaliTest[862:747795] jxcore: disconnect: fail
,2015-12-11T19:29:18.064Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5466.2TZtug==

```
