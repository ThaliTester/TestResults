#### Test 519863404492c11_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/519863404492c11/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/C9A2FAC8-A889-4E92-B134-6EC124C4E68D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C9A2FAC8-A889-4E92-B134-6EC124C4E68D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/519863404492c11/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/519863404492c11/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4A3E7F6D-2C59-401C-9CA2-3D214509438D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49622"
,(lldb)     command script import "/tmp/C9A2FAC8-A889-4E92-B134-6EC124C4E68D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 07:47:12.692 ThaliTest[335:103524] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/448C656E-A942-469D-AE79-C78F0B515501/Library/Cookies/Cookies.binarycookies
,2015-12-07 07:47:13.132 ThaliTest[335:103524] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 07:47:13.134 ThaliTest[335:103524] Multi-tasking -> Device: YES, App: YES
,2015-12-07 07:47:13.144 ThaliTest[335:103524] Unlimited access to network resources
,2015-12-07 07:47:13.158 ThaliTest[335:103524] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 07:47:22.434 ThaliTest[335:103524] Resetting plugins due to page load.
,2015-12-07 07:47:26.328 ThaliTest[335:103524] Finished load of: file:///var/mobile/Containers/Bundle/Application/4A3E7F6D-2C59-401C-9CA2-3D214509438D/ThaliTest.app/www/index.html
,2015-12-07 07:47:26.583 ThaliTest[335:103524] JXcore Cordova plugin initializing
,2015-12-07 07:47:26.584 ThaliTest[335:103736] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
Starting JXcore engine
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
,my name is : Apple-Iphone5s-1_PT7843
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 50114
,2015-12-07 07:54:47.914 ThaliTest[335:103736] jxcore: startBroadcasting
,2015-12-07 07:54:47.939 ThaliTest[335:103736] server: starting Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:54:47.945 ThaliTest[335:103736] multipeer session: start timer: 0x7a92e40
,2015-12-07 07:54:47.951 ThaliTest[335:103736] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT7843
,2015-12-07 07:54:47.954 ThaliTest[335:103736] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-07T06:54:47.960Z SendDataTCPServer.js: TCP/IP server is bound to port: 50114
,2015-12-07 07:54:48.636 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7482.CDxPNA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07T06:54:48.644Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07T06:54:48.648Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07T06:54:48.649Z SendDataConnector.js: do connect now
,2015-12-07 07:54:48.651 ThaliTest[335:103736] jxcore: connect Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:54:48.651 ThaliTest[335:103736] client session: connect
2015-12-07 07:54:48.652 ThaliTest[335:103736] client session: stateChange:0->1 Apple-Iphon,e6-1_PT7482.CDxPNA==
,2015-12-07 07:54:49.472 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1974.yVUIQA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-07 07:54:50.156 ThaliTest[335:103524] multipeer session: reset timer
2015-12-07 07:54:50.156 ThaliTest[335:103524] multipeer session: stop timer
2015-12-07 07:54:50.156 ThaliTest[335:103524] multipeer session: start timer: 0x7a92e40
2015-12-07 0,7:54:50.157 ThaliTest[335:103524] server session: connect
2015-12-07 07:54:50.157 ThaliTest[335:103524] server session: stateChange:0->1 Apple-Iphone6-1_PT7482
,2015-12-07 07:54:50.169 ThaliTest[335:103524] server: accepting invitation Apple-Iphone6-1_PT7482
,2015-12-07 07:54:53.686 ThaliTest[335:104512] server session: connected
2015-12-07 07:54:53.686 ThaliTest[335:104512] server session: stateChange:1->2 Apple-Iphone6-1_PT7482
,2015-12-07 07:54:53.757 ThaliTest[335:103524] server relay: connected (to port: 50114)
2015-12-07T06:54:53.760Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T06:54:54.159Z SendDataTCPServer.js: TCP/IP server has received 21474 bytes of data
,2015-12-07T06:54:54.175Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-07T06:54:54.192Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-07T06:54:54.207Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-07T06:54:54.222Z SendDataTCPServer.js: TCP/IP server has received 78698 bytes of data
,2015-12-07T06:54:54.237Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-07T06:54:54.252Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 07:54:54.344 ThaliTest[335:104489] server session: not connected Apple-Iphone6-1_PT7482
,2015-12-07 07:54:54.933 ThaliTest[335:104490] client session: connected
2015-12-07 07:54:54.934 ThaliTest[335:104490] client session: stateChange:1->2 Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:54:55.189 ThaliTest[335:103524] multipeer session: reset timer
2015-12-07 07:54:55.189 ThaliTest[335:103524] multipeer session: stop timer
2015-12-07 07:54:55.189 ThaliTest[335:103524] multipeer session: start timer: 0x7a92e40
2015-12-07 0,7:54:55.190 ThaliTest[335:103524] server session: connect
2015-12-07 07:54:55.190 ThaliTest[335:103524] server session: stateChange:0->1 Apple-Iphone5-1_PT1974
,2015-12-07 07:54:55.204 ThaliTest[335:103524] server: accepting invitation Apple-Iphone5-1_PT1974
,2015-12-07 07:54:55.256 ThaliTest[335:104490] client session: fireConnectCallback: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:54:55.259 ThaliTest[335:104490] jxcore: connect: success
,2015-12-07T06:54:55.264Z SendDataConnector.js: CLIENT connected to 50118, error: null
2015-12-07T06:54:55.265Z SendDataConnector.js: CLIENT starting client 
2015-12-07 07:54:55.274 ThaliTest[335:103524] client: relay established
2015-12-07 07:54:55.275 ThaliTest[335:103524] client: new accepted socket: 0x8820050
,2015-12-07T06:54:55.286Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T06:54:55.769Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-07T06:54:56.309Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T06:54:56.310Z SendDataConnector.js: got all data for this round
,2015-12-07T06:54:56.313Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T06:54:56.314Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:54:56.318 ThaliTest[335:103736] jxcore: disconnect
,2015-12-07 07:54:56.320 ThaliTest[335:103736] client session: disconnectFromPeer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:54:56.322 ThaliTest[335:103736] client session: disconnect
,2015-12-07 07:54:56.323 ThaliTest[335:103736] client session: stateChange:2->0 Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:54:56.432 ThaliTest[335:103736] jxcore: disconnect: success
,2015-12-07T06:54:56.434Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7482.CDxPNA==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07T06:54:56.440Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07T06:54:56.441Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07T06:54:56.442Z SendDataConnector.js: do connect now
,2015-12-07 07:54:56.444 ThaliTest[335:103736] jxcore: connect Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:54:56.447 ThaliTest[335:103736] client session: connect
,2015-12-07 07:54:56.450 ThaliTest[335:103736] client session: stateChange:0->1 Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:54:57.938 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT12.Gapeow==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-07 07:55:00.105 ThaliTest[335:104489] server session: connected
,2015-12-07 07:55:00.105 ThaliTest[335:104489] server session: stateChange:1->2 Apple-Iphone5-1_PT1974
,2015-12-07 07:55:00.130 ThaliTest[335:103524] server relay: connected (to port: 50114)
,2015-12-07T06:55:00.139Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T06:55:00.704Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-07T06:55:00.721Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-07T06:55:00.739Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-07T06:55:00.761Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-07T06:55:00.778Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-07T06:55:00.793Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 07:55:01.029 ThaliTest[335:104489] client session: connected
2015-12-07 07:55:01.029 ThaliTest[335:104489] client session: stateChange:1->2 Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:55:01.049 ThaliTest[335:104489] server session: not connected Apple-Iphone5-1_PT1974
,2015-12-07 07:55:01.065 ThaliTest[335:104512] client session: fireConnectCallback: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:55:01.066 ThaliTest[335:104512] jxcore: connect: success
2015-12-07T06:55:01.067Z SendDataConnector.js: CLIENT connected to 50122, error: null
,2015-12-07T06:55:01.068Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 07:55:01.074 ThaliTest[335:103524] client: relay established
2015-12-07 07:55:01.074 ThaliTest[335:103524] client: new accepted socket: 0x7aa7ca0
,2015-12-07T06:55:01.087Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T06:55:01.522Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-07T06:55:01.645Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-07T06:55:01.707Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-07T06:55:01.707Z SendDataConnector.js: got all data for this round
,2015-12-07T06:55:01.708Z SendDataConnector.js: CLIENT Stop now
2015-12-07T06:55:01.709Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:55:01.709 ThaliTest[335:103736] jxcore: disconnect
2015-12-07 07:55:01.709 ThaliTest[335:103736] client session: disconnectFromPeer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:55:01.710 ThaliTest[335:103736] client session: disconnect
2015-12-07 07:55:01.710 ThaliTest[335:103736] client session: stateChange:2->0 Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:55:01.783 ThaliTest[335:103736] jxcore: disconnect: success
2015-12-07T06:55:01.784Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1974.yVUIQA==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07T06:55:01.786Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07T06:55:01.786Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07T06:55:01.787Z SendDataConnector.js: do connect now
,2015-12-07 07:55:01.788 ThaliTest[335:103736] jxcore: connect Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:55:01.789 ThaliTest[335:103736] client session: connect
2015-12-07 07:55:01.789 ThaliTest[335:103736] client session: stateChange:0->1 Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:55:05.255 ThaliTest[335:104512] client session: connected
2015-12-07 07:55:05.255 ThaliTest[335:104512] client session: stateChange:1->2 Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:55:05.269 ThaliTest[335:104489] client session: fireConnectCallback: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:55:05.272 ThaliTest[335:104489] jxcore: connect: success
2015-12-07T06:55:05.273Z SendDataConnector.js: CLIENT connected to 50125, error: null
2015-12-07T06:55:05.274Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 07:55:05.278 ThaliTest[335:103524] client: relay established
2015-12-07 07:55:05.279 ThaliTest[335:103524] client: new accepted socket: 0x6bb32c0
,2015-12-07T06:55:05.291Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07 07:55:05.716 ThaliTest[335:103524] multipeer session: reset timer
2015-12-07 07:55:05.717 ThaliTest[335:103524] multipeer session: stop timer
,2015-12-07 07:55:05.717 ThaliTest[335:103524] multipeer session: start timer: 0x7a92e40
,2015-12-07 07:55:05.718 ThaliTest[335:103524] server session: connect
2015-12-07 07:55:05.718 ThaliTest[335:103524] server session: stateChange:0->1 Apple-IpadAir2-1_PT12
,2015-12-07 07:55:05.724 ThaliTest[335:103524] server: accepting invitation Apple-IpadAir2-1_PT12
,2015-12-07T06:55:05.819Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-07T06:55:05.836Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-07T06:55:05.836Z SendDataConnector.js: got all data for this round
,2015-12-07T06:55:05.837Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T06:55:05.838Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:55:05.839 ThaliTest[335:103736] jxcore: disconnect
,2015-12-07 07:55:05.840 ThaliTest[335:103736] client session: disconnectFromPeer: Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:55:05.841 ThaliTest[335:103736] client session: disconnect
,2015-12-07 07:55:05.842 ThaliTest[335:103736] client session: stateChange:2->0 Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:55:05.908 ThaliTest[335:103736] jxcore: disconnect: success
,2015-12-07T06:55:05.909Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT12.Gapeow==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT7843","time":18015,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7482.CDxPNA==","time":7664,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT1974.yVUIQA==","time":5267,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT12.Gapeow==","time":4051,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 7664 ms, 99% : 7664 ms, 95 : 7664 ms, 90% : 7664 ms.
,Result count 3, range 4051 ms to  7664 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-07T06:55:05.920Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T06:55:05.921Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:55:08.334 ThaliTest[335:104490] server session: connected
2015-12-07 07:55:08.334 ThaliTest[335:104490] server session: stateChange:1->2 Apple-IpadAir2-1_PT12
,2015-12-07T06:55:08.349Z SendDataTCPServer.js: TCP/IP server connected
2015-12-07 07:55:08.350 ThaliTest[335:103524] server relay: connected (to port: 50114)
,2015-12-07T06:55:08.818Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-07T06:55:08.835Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-07T06:55:08.851Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-07T06:55:08.870Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-07T06:55:08.888Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-07T06:55:08.904Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-07T06:55:08.920Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 07:55:08.961 ThaliTest[335:104500] server session: not connected Apple-IpadAir2-1_PT12
,2015-12-07 07:55:35.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 07:55:35.784 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:55:35.785 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
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
,2015-12-07 07:56:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 07:56:05.778 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:56:05.780 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
,2015-12-07 07:56:35.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 07:56:35.769 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:56:35.769 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:56:35.774 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 07:57:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 07:57:05.772 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:57:05.773 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:57:05.773 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 07:57:35.719 ThaliTest[335:103524] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 07:57:35.820 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:57:35.820 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:57:35.821 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 07:58:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 07:58:05.789 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:58:05.790 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 07:58:19.636 ThaliTest[335:103524] client: lost peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:58:19.637 ThaliTest[335:103524] client session: onPeerLost: Apple-IpadAir2-1_PT12.Gapeow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT12.Gapeow==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 07:58:22.882 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT12.Gapeow==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 07:58:35.718 ThaliTest[335:103524] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 07:59:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 07:59:05.777 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:59:05.778 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:59:05.778 ThaliTest[335:103524] client: foun,d peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 07:59:35.719 ThaliTest[335:103524] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:00:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:00:05.780 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:00:05.780 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:00:05.781 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 08:00:35.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:00:35.776 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:00:35.777 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:00:36.681 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:01:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:01:05.779 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:01:05.780 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:01:06.625 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:01:35.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:01:35.780 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:01:35.781 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:01:35.781 ThaliTest[335:103524] client: found, peer: Apple-Iphone6-1_PT7482.CDxPNA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:02:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:02:05.789 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:02:05.790 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:02:05.791 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 08:02:35.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:02:35.776 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 08:02:35.784 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:02:35.784 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:03:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:03:06.450 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:03:06.451 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 08:03:06.452 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:03:35.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:03:35.778 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:03:35.779 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:03:35.780 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:04:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:04:05.781 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:04:05.781 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:04:05.784 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:04:35.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:04:35.778 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:04:35.782 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:04:35.785 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:05:05.719 ThaliTest[335:103524] multipeer session: restart
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
,2015-12-07 08:05:35.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:05:35.773 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:05:35.776 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 08:05:35.777 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:06:05.719 ThaliTest[335:103524] multipeer session: restart
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
,2015-12-07 08:06:35.718 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:06:35.776 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:06:35.776 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:06:35.779 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:07:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:07:05.780 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:07:05.780 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:07:05.781 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 08:07:35.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:07:35.781 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:07:35.782 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:07:35.783 ThaliTest[335:103524] client: foun,d peer: Apple-IpadAir2-1_PT12.Gapeow==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:08:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:08:05.781 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:08:05.781 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:08:05.782 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
,2015-12-07 08:08:35.719 ThaliTest[335:103524] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:09:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:09:05.777 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 08:09:05.781 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:09:05.783 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:09:35.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:09:35.779 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:09:35.780 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 08:09:36.449 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:10:05.718 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:10:05.779 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:10:05.779 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:10:05.782 ThaliTest[335:103524] client: found, peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:10:35.719 ThaliTest[335:103524] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:11:05.719 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:11:05.780 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:11:05.781 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:11:05.783 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
,2015-12-07 08:11:35.719 ThaliTest[335:103524] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:12:05.713 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:12:05.772 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:12:05.772 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:12:05.773 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
,2015-12-07 08:12:35.713 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:12:35.776 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:12:35.776 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:12:35.777 ThaliTest[335:103524] client: found, peer: Apple-Iphone5-1_PT1974.yVUIQA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:13:05.713 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:13:05.771 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:13:05.772 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:13:05.772 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:13:35.713 ThaliTest[335:103524] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:14:05.713 ThaliTest[335:103524] multipeer session: restart
,2015-12-07 08:14:05.776 ThaliTest[335:103524] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 08:14:05.780 ThaliTest[335:103524] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:14:05.783 ThaliTest[335:103524] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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

```
