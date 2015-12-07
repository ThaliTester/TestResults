#### Test 519863404492c11_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/519863404492c11/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/5E0FB247-73FA-4C79-8890-ABBFDC79EA7E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5E0FB247-73FA-4C79-8890-ABBFDC79EA7E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/519863404492c11/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/519863404492c11/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5801E1CE-CF92-4281-B0B9-706AB568F91D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49618"
,(lldb)     command script import "/tmp/5E0FB247-73FA-4C79-8890-ABBFDC79EA7E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 07:47:10.270 ThaliTest[297:91137] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8ABA2308-2C02-4CA8-8D53-E24F76952255/Library/Cookies/Cookies.binarycookies
,2015-12-07 07:47:10.287 ThaliTest[297:91137] <CATransformLayer: 0x1457bf00> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-07 07:47:10.287 ThaliTest[297:91137] <CATransformLayer: 0x14773200> - changing property mask,sToBounds in transform-only layer, will have no effect
2015-12-07 07:47:10.288 ThaliTest[297:91137] <CATransformLayer: 0x14774370> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-07 07:47:10.583 ThaliTest[297:91137] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 07:47:10.583 ThaliTest[297:91137] Multi-tasking -> Device: YES, App: YES
,2015-12-07 07:47:10.591 ThaliTest[297:91137] Unlimited access to network resources
,2015-12-07 07:47:10.596 ThaliTest[297:91137] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 07:47:19.107 ThaliTest[297:91137] Resetting plugins due to page load.
,2015-12-07 07:47:22.471 ThaliTest[297:91137] Finished load of: file:///var/mobile/Containers/Bundle/Application/5801E1CE-CF92-4281-B0B9-706AB568F91D/ThaliTest.app/www/index.html
,2015-12-07 07:47:22.617 ThaliTest[297:91137] JXcore Cordova plugin initializing
,2015-12-07 07:47:22.618 ThaliTest[297:91397] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-IpadAir2-1_PT12
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
,serverPort is 49780
,2015-12-07 07:54:47.553 ThaliTest[297:91397] jxcore: startBroadcasting
,2015-12-07 07:54:47.565 ThaliTest[297:91397] server: starting Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:54:47.568 ThaliTest[297:91397] multipeer session: start timer: 0x167cf220
,2015-12-07 07:54:47.568 ThaliTest[297:91397] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT12
,2015-12-07 07:54:47.570 ThaliTest[297:91397] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-12-07T06:54:47.574Z SendDataTCPServer.js: TCP/IP server is bound to port: 49780
,2015-12-07 07:54:54.098 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7482.CDxPNA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07T06:54:54.105Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07T06:54:54.106Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07T06:54:54.107Z SendDataConnector.js: do connect now
,2015-12-07 07:54:54.108 ThaliTest[297:91397] jxcore: connect Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:54:54.109 ThaliTest[297:91397] client session: connect
2015-12-07 07:54:54.109 ThaliTest[297:91397] client session: stateChange:0->1 Apple-Iphone6-,1_PT7482.CDxPNA==
,2015-12-07 07:54:54.599 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1974.yVUIQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-07 07:54:58.560 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7843.gS16eg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-07 07:54:59.623 ThaliTest[297:91137] multipeer session: reset timer
2015-12-07 07:54:59.624 ThaliTest[297:91137] multipeer session: stop timer
2015-12-07 07:54:59.624 ThaliTest[297:91137] multipeer session: start timer: 0x167cf220
,2015-12-07 07:54:59.626 ThaliTest[297:91137] server session: connect
,2015-12-07 07:54:59.626 ThaliTest[297:91137] server session: stateChange:0->1 Apple-Iphone6-1_PT7482
,2015-12-07 07:54:59.634 ThaliTest[297:91137] server: accepting invitation Apple-Iphone6-1_PT7482
,2015-12-07 07:55:00.594 ThaliTest[297:92177] client session: connected
2015-12-07 07:55:00.595 ThaliTest[297:92177] client session: stateChange:1->2 Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:55:00.600 ThaliTest[297:92177] client session: fireConnectCallback: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:55:00.601 ThaliTest[297:92177] jxcore: connect: success
,2015-12-07T06:55:00.603Z SendDataConnector.js: CLIENT connected to 49783, error: null
,2015-12-07T06:55:00.603Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 07:55:00.610 ThaliTest[297:91137] client: relay established
2015-12-07 07:55:00.610 ThaliTest[297:91137] client: new accepted socket: 0x178da960
,2015-12-07T06:55:00.625Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T06:55:01.110Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-07T06:55:01.125Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-07T06:55:01.137Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-07T06:55:01.151Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T06:55:01.152Z SendDataConnector.js: got all data for this round
,2015-12-07T06:55:01.153Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T06:55:01.154Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:55:01.155 ThaliTest[297:91397] jxcore: disconnect
,2015-12-07 07:55:01.156 ThaliTest[297:91397] client session: disconnectFromPeer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:55:01.156 ThaliTest[297:91397] client session: disconnect
,2015-12-07 07:55:01.156 ThaliTest[297:91397] client session: stateChange:2->0 Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:55:01.222 ThaliTest[297:91397] jxcore: disconnect: success
,2015-12-07T06:55:01.223Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7482.CDxPNA==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07T06:55:01.226Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07T06:55:01.227Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07T06:55:01.227Z SendDataConnector.js:, do connect now
,2015-12-07 07:55:01.228 ThaliTest[297:91397] jxcore: connect Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:55:01.228 ThaliTest[297:91397] client session: connect
2015-12-07 07:55:01.229 ThaliTest[297:91397] client session: stateChange:0->1 Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:55:01.768 ThaliTest[297:91137] multipeer session: reset timer
2015-12-07 07:55:01.768 ThaliTest[297:91137] multipeer session: stop timer
2015-12-07 07:55:01.769 ThaliTest[297:91137] multipeer session: start timer: 0x167cf220
2015-12-07 07:55:01.769 ThaliTest[297:91137] server session: connect
,2015-12-07 07:55:01.769 ThaliTest[297:91137] server session: stateChange:0->1 Apple-Iphone5-1_PT1974
,2015-12-07 07:55:01.775 ThaliTest[297:91137] server: accepting invitation Apple-Iphone5-1_PT1974
,2015-12-07 07:55:02.793 ThaliTest[297:91137] multipeer session: reset timer
2015-12-07 07:55:02.793 ThaliTest[297:91137] multipeer session: stop timer
2015-12-07 07:55:02.794 ThaliTest[297:91137] multipeer session: start timer: 0x167cf220
,2015-12-07 07:55:02.794 ThaliTest[297:91137] server session: connect
,2015-12-07 07:55:02.794 ThaliTest[297:91137] server session: stateChange:0->1 Apple-Iphone5s-1_PT7843
,2015-12-07 07:55:02.802 ThaliTest[297:91137] server: accepting invitation Apple-Iphone5s-1_PT7843
,2015-12-07 07:55:03.521 ThaliTest[297:92177] server session: connected
2015-12-07 07:55:03.522 ThaliTest[297:92177] server session: stateChange:1->2 Apple-Iphone6-1_PT7482
,2015-12-07 07:55:03.694 ThaliTest[297:91137] server relay: connected (to port: 49780)
,2015-12-07T06:55:03.699Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T06:55:03.994Z SendDataTCPServer.js: TCP/IP server has received 10808 bytes of data
,2015-12-07T06:55:04.009Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-07T06:55:04.023Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 07:55:04.250 ThaliTest[297:92177] server session: not connected Apple-Iphone6-1_PT7482
,2015-12-07 07:55:05.418 ThaliTest[297:92177] server session: connected
2015-12-07 07:55:05.419 ThaliTest[297:92177] server session: stateChange:1->2 Apple-Iphone5-1_PT1974
,2015-12-07 07:55:05.425 ThaliTest[297:91137] server relay: connected (to port: 49780)
,2015-12-07T06:55:05.431Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07 07:55:05.446 ThaliTest[297:92304] client session: connected
2015-12-07 07:55:05.446 ThaliTest[297:92304] client session: stateChange:1->2 Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:55:05.449 ThaliTest[297:92304] client session: fireConnectCallback: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:55:05.450 ThaliTest[297:92304] jxcore: connect: success
,2015-12-07T06:55:05.451Z SendDataConnector.js: CLIENT connected to 49788, error: null
,2015-12-07T06:55:05.451Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 07:55:05.453 ThaliTest[297:91137] client: relay established
2015-12-07 07:55:05.453 ThaliTest[297:91137] client: new accepted socket: 0x178df000
,2015-12-07T06:55:05.466Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07 07:55:05.895 ThaliTest[297:92304] server session: connected
2015-12-07 07:55:05.895 ThaliTest[297:92304] server session: stateChange:1->2 Apple-Iphone5s-1_PT7843
,2015-12-07 07:55:05.908 ThaliTest[297:91137] server relay: connected (to port: 49780)
,2015-12-07T06:55:05.918Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T06:55:06.019Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-07T06:55:06.034Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-07T06:55:06.048Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-07T06:55:06.049Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-07T06:55:06.050Z SendDataConnector.js: got all data for this round
,2015-12-07T06:55:06.052Z SendDataConnector.js: CLIENT Stop now
2015-12-07T06:55:06.052Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:55:06.053 ThaliTest[297:91397] jxcore: disconnect
2015-12-07 07:55:06.053 ThaliTest[297:91397] client session: disconnectFromPeer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:55:06.054 ThaliTest[297:91397] client session: disconnect
2015-12-07 07:55:06.055 ThaliTest[297:91397] client session: stateChange:2->0 Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:55:06.065 ThaliTest[297:91397] jxcore: disconnect: success
,2015-12-07T06:55:06.065Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1974.yVUIQA==
,---- round done--------
device[3]: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07T06:55:06.070Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07T06:55:06.070Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07T06:55:06.070Z SendDataConnector.js: do connect now
,2015-12-07 07:55:06.071 ThaliTest[297:91397] jxcore: connect Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:55:06.073 ThaliTest[297:91397] client session: connect
,2015-12-07 07:55:06.074 ThaliTest[297:91397] client session: stateChange:0->1 Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07T06:55:06.098Z SendDataTCPServer.js: TCP/IP server has received 84842 bytes of data
,2015-12-07T06:55:06.114Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 07:55:06.371 ThaliTest[297:92304] server session: not connected Apple-Iphone5-1_PT1974
,2015-12-07T06:55:06.449Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-07T06:55:06.462Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-07T06:55:06.477Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 07:55:06.505 ThaliTest[297:92177] server session: not connected Apple-Iphone5s-1_PT7843
,2015-12-07 07:55:08.967 ThaliTest[297:92180] client session: connected
2015-12-07 07:55:08.968 ThaliTest[297:92180] client session: stateChange:1->2 Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:55:08.989 ThaliTest[297:92304] client session: fireConnectCallback: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:55:08.990 ThaliTest[297:92304] jxcore: connect: success
,2015-12-07T06:55:08.991Z SendDataConnector.js: CLIENT connected to 49792, error: null
,2015-12-07T06:55:08.992Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 07:55:08.997 ThaliTest[297:91137] client: relay established
2015-12-07 07:55:08.997 ThaliTest[297:91137] client: new accepted socket: 0x165de160
,2015-12-07T06:55:09.010Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T06:55:09.500Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-07T06:55:09.513Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-07T06:55:09.525Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-07T06:55:09.551Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-07T06:55:09.565Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T06:55:09.565Z SendDataConnector.js: got all data for this round
,2015-12-07T06:55:09.567Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T06:55:09.568Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:55:09.569 ThaliTest[297:91397] jxcore: disconnect
,2015-12-07 07:55:09.570 ThaliTest[297:91397] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:55:09.570 ThaliTest[297:91397] client session: disconnect
,2015-12-07 07:55:09.571 ThaliTest[297:91397] client session: stateChange:2->0 Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:55:09.579 ThaliTest[297:91397] jxcore: disconnect: success
2015-12-07T06:55:09.580Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7843.gS16eg==
---- round done--------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT12","time":22044,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7482.CDxPNA==","time":7046,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT,1974.yVUIQA==","time":4823,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7843.gS16eg==","time":3496,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 7046 ms, 99% : 7046 ms, 95 : 7046 ms, 90% : 7046 ms.
Result count 3, range 3496 ms to  7046 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-07T06:55:09.588Z SendDataConnector.js: CLIEN,T Stop now
2015-12-07T06:55:09.588Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:55:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 07:55:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:55:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:55:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:56:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 07:56:02.829 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:56:02.829 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:56:02.835 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:56:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 07:57:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 07:57:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:57:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:57:02.827 ThaliTest[297:91137] client: found p,eer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:57:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 07:58:02.794 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 07:58:02.821 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:58:02.821 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:58:02.822 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:58:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 07:58:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:58:32.825 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:58:32.825 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:59:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 07:59:02.825 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:59:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:59:02.827 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:59:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 07:59:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:59:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:59:32.830 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:00:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:00:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:00:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:00:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
,2015-12-07 08:00:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:00:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:00:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:00:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:01:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:01:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:01:02.827 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:01:02.827 ThaliTest[297:91137] client: found ,peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:01:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:01:32.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:01:32.826 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:01:32.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:02:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:02:02.825 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:02:02.825 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:02:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:02:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:02:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:02:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:02:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:03:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:03:02.823 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:03:02.823 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:03:02.824 ThaliTest[297:91137] client: found p,eer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:03:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:03:32.827 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:03:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:03:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:04:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:04:03.631 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:04:03.632 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:04:03.632 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:04:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:04:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:04:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:04:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:05:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:05:02.822 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:05:02.822 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:05:02.823 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:05:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:05:32.823 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:05:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:05:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:06:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:06:02.827 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:06:02.827 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:06:02.827 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
,2015-12-07 08:06:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:06:32.827 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:06:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:06:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-07 08:07:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:07:02.823 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:07:02.823 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:07:02.824 ThaliTest[297:91137] client: found ,peer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 08:07:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:07:32.825 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:07:32.825 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:07:32.825 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 08:08:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:08:02.828 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:08:02.828 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:08:02.828 ThaliTest[297:91137] client: found ,peer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 08:08:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:08:32.827 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:08:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:08:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 08:09:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:09:02.825 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:09:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:09:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 08:09:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:09:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:09:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:09:32.824 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 08:10:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:10:02.825 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:10:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:10:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:10:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:10:32.821 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:10:32.821 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 08:10:32.822 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:11:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:11:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 08:11:02.828 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:11:02.828 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
,2015-12-07 08:11:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:11:32.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:11:32.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 08:11:32.828 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
,2015-12-07 08:12:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:12:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:12:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:12:02.827 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:12:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:12:32.825 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:12:32.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:12:32.826 ThaliTest[297:91137] client: found ,peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
,2015-12-07 08:13:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:13:02.827 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:13:02.827 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:13:02.827 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,2015-12-07 08:13:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:13:32.827 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:13:32.827 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:13:32.827 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 08:14:02.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:14:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:14:02.826 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:14:02.827 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 08:14:32.795 ThaliTest[297:91137] multipeer session: restart
,2015-12-07 08:14:32.825 ThaliTest[297:91137] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:14:32.825 ThaliTest[297:91137] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 08:14:32.826 ThaliTest[297:91137] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==

```
