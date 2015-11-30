#### Test 519863409bc5c94_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/519863409bc5c94/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D385A9CA-2922-4EB8-A0A1-DBB1A59D08DA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D385A9CA-2922-4EB8-A0A1-DBB1A59D08DA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/519863409bc5c94/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/519863409bc5c94/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/29EFA7BE-ECF0-40D2-8342-170F45101210/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58056"
,(lldb)     command script import "/tmp/D385A9CA-2922-4EB8-A0A1-DBB1A59D08DA/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-30 11:49:20.274 ThaliTest[2089:1932918] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F4341719-AB0A-4969-A803-09A45EC38D2D/Library/Cookies/Cookies.binarycookies
,2015-11-30 11:49:20.689 ThaliTest[2089:1932918] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-30 11:49:20.690 ThaliTest[2089:1932918] Multi-tasking -> Device: YES, App: YES
,2015-11-30 11:49:20.699 ThaliTest[2089:1932918] Unlimited access to network resources
,2015-11-30 11:49:20.707 ThaliTest[2089:1932918] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-30 11:49:24.154 ThaliTest[2089:1932918] Resetting plugins due to page load.
,2015-11-30 11:49:24.615 ThaliTest[2089:1932918] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/29EFA7BE-ECF0-40D2-8342-170F45101210/ThaliTest.app/www/index.html
,2015-11-30 11:49:24.768 ThaliTest[2089:1932918] JXcore Cordova plugin initializing
2015-11-30 11:49:24.769 ThaliTest[2089:1933126] JXcore instance initializing
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone5s-1_PT7955
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 63999
,2015-11-30 11:55:56.847 ThaliTest[2089:1933126] jxcore: startBroadcasting
,2015-11-30 11:55:56.860 ThaliTest[2089:1933126] server: starting Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:55:56.861 ThaliTest[2089:1933126] multipeer session: start timer: 0x19d92160
2015-11-30 11:55:56.862 ThaliTest[2089:1933126] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT7955
2015-11-30 11:55:56.863 ThaliTest[2089:1933126] jxcore,: startBroadcasting: success
StartBroadcasting started ok
,2015-11-30T10:55:56.866Z SendDataTCPServer.js: TCP/IP server is bound to port: 63999
,2015-11-30 11:55:57.481 ThaliTest[2089:1932918] multipeer session: reset timer
2015-11-30 11:55:57.482 ThaliTest[2089:1932918] multipeer session: stop timer
2015-11-30 11:55:57.482 ThaliTest[2089:1932918] multipeer session: start timer: 0x19d92160
2015-,11-30 11:55:57.483 ThaliTest[2089:1932918] server session: connect
2015-11-30 11:55:57.484 ThaliTest[2089:1932918] server session: stateChange:0->1 Apple-Iphone5-1_PT2455
,2015-11-30 11:55:57.497 ThaliTest[2089:1932918] server: accepting invitation Apple-Iphone5-1_PT2455
,2015-11-30 11:55:58.023 ThaliTest[2089:1932918] multipeer session: reset timer
2015-11-30 11:55:58.024 ThaliTest[2089:1932918] multipeer session: stop timer
2015-11-30 11:55:58.024 ThaliTest[2089:1932918] multipeer session: start timer: 0x19d92160
2015-,11-30 11:55:58.025 ThaliTest[2089:1932918] server session: connect
2015-11-30 11:55:58.026 ThaliTest[2089:1932918] server session: stateChange:0->1 Apple-IpadAir2-1_PT4872
,2015-11-30 11:55:58.038 ThaliTest[2089:1932918] server: accepting invitation Apple-IpadAir2-1_PT4872
,2015-11-30 11:55:58.053 ThaliTest[2089:1932918] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2455.0R5G/g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30T10:55:58.056Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30T10:55:58.056Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30T10:55:58.057Z SendDataConnector.js: do connect now
2015-11-30 11:55:58.057 ThaliTest[2089:1933126] jxcore: connect Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:55:58.058 ThaliTest[2089:1933126] client session: connect
,2015-11-30 11:55:58.058 ThaliTest[2089:1933126] client session: stateChange:0->1 Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:55:58.653 ThaliTest[2089:1932918] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4872.+CDkQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-11-30 11:55:59.941 ThaliTest[2089:1933688] server session: connected
2015-11-30 11:55:59.943 ThaliTest[2089:1933688] server session: stateChange:1->2 Apple-Iphone5-1_PT2455
,2015-11-30 11:55:59.951 ThaliTest[2089:1932918] server relay: connected (to port: 63999)
2015-11-30T10:55:59.956Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30 11:55:59.991 ThaliTest[2089:1932918] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-11-30T10:56:00.479Z SendDataTCPServer.js: TCP/IP server has received 10912 bytes of data
,2015-11-30 11:56:00.486 ThaliTest[2089:1933676] client session: connected
,2015-11-30 11:56:00.487 ThaliTest[2089:1933676] client session: stateChange:1->2 Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:56:00.492 ThaliTest[2089:1933676] client session: fireConnectCallback: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:56:00.492 ThaliTest[2089:1933676] jxcore: connect: success
,2015-11-30T10:56:00.494Z SendDataTCPServer.js: TCP/IP server has received 26784 bytes of data
,2015-11-30T10:56:00.497Z SendDataConnector.js: CLIENT connected to 64003, error: null
2015-11-30T10:56:00.497Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:56:00.501 ThaliTest[2089:1932918] client: relay established
2015-11-30 11:56:00.501 ThaliTest[2089:1932918] client: new accepted socket: 0x19da8580
,2015-11-30T10:56:00.516Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
,2015-11-30T10:56:00.517Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30 11:56:00.600 ThaliTest[2089:1933703] server session: connected
2015-11-30 11:56:00.600 ThaliTest[2089:1933703] server session: stateChange:1->2 Apple-IpadAir2-1_PT4872
,2015-11-30 11:56:00.607 ThaliTest[2089:1932918] server relay: connected (to port: 63999)
,2015-11-30T10:56:00.790Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30T10:56:00.793Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T10:56:00.974Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-11-30T10:56:00.995Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30 11:56:01.062 ThaliTest[2089:1933690] server session: not connected Apple-Iphone5-1_PT2455
,2015-11-30T10:56:01.063Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-30 11:56:01.068 ThaliTest[2089:1933690] server session: not connected Apple-IpadAir2-1_PT4872
,2015-11-30T10:56:01.075Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-30T10:56:01.075Z SendDataConnector.js: got all data for this round
,2015-11-30T10:56:01.076Z SendDataConnector.js: CLIENT Stop now
,2015-11-30T10:56:01.077Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:56:01.078 ThaliTest[2089:1933126] jxcore: disconnect
,2015-11-30 11:56:01.079 ThaliTest[2089:1933126] client session: disconnectFromPeer: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:56:01.080 ThaliTest[2089:1933126] client session: disconnect
,2015-11-30 11:56:01.080 ThaliTest[2089:1933126] client session: stateChange:2->0 Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:56:01.140 ThaliTest[2089:1933126] jxcore: disconnect: success
2015-11-30T10:56:01.141Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2455.0R5G/g==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT4872.+CDkQA==
2015-11-30T10:56:01.142Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4872.+CDkQA==
2015-11-30T10:56:01.142Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4872.+CDkQA==,
2015-11-30T10:56:01.143Z SendDataConnector.js: do connect now
2015-11-30 11:56:01.143 ThaliTest[2089:1933126] jxcore: connect Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:01.144 ThaliTest[2089:1933126] client session: connect
2015-11-30 11:56:01.144 ThaliTest[2089:1933126] client session: stateChange:0->1 Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:04.197 ThaliTest[2089:1933685] client session: connected
2015-11-30 11:56:04.198 ThaliTest[2089:1933685] client session: stateChange:1->2 Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:04.244 ThaliTest[2089:1933685] client session: fireConnectCallback: Apple-IpadAir2-1_PT4872.+CDkQA==
2015-11-30 11:56:04.245 ThaliTest[2089:1933685] jxcore: connect: success
2015-11-30T10:56:04.247Z SendDataConnector.js: CLIENT connected, to 64007, error: null
2015-11-30T10:56:04.248Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:56:04.252 ThaliTest[2089:1932918] client: relay established
,2015-11-30 11:56:04.252 ThaliTest[2089:1932918] client: new accepted socket: 0x19e61c30
,2015-11-30T10:56:04.264Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T10:56:04.929Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-30T10:56:05.328Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-30T10:56:05.328Z SendDataConnector.js: got all data for this round
,2015-11-30T10:56:05.330Z SendDataConnector.js: CLIENT Stop now
2015-11-30T10:56:05.330Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30 11:56:05.331 ThaliTest[2089:1933126] jxcore: disconnect
,2015-11-30 11:56:05.332 ThaliTest[2089:1933126] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:05.333 ThaliTest[2089:1933126] client session: disconnect
,2015-11-30 11:56:05.334 ThaliTest[2089:1933126] client session: stateChange:2->0 Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:05.339 ThaliTest[2089:1933126] jxcore: disconnect: success
2015-11-30T10:56:05.340Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4872.+CDkQA==
---- round done--------
device[3]: Apple-Iphone6-1_PT7389.,2i+JNA==
2015-11-30T10:56:05.344Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:56:05.345Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T10:56:05.345Z SendDataConnector.js: do connect now
2015-11-30 11:56:05.346 ThaliTest[2089:1933126] jxcore: connect Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:56:05.347 ThaliTest[2089:1933126] client session: connect
,2015-11-30 11:56:05.347 ThaliTest[2089:1933126] client session: stateChange:0->1 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:56:07.817 ThaliTest[2089:1933688] client session: connected
2015-11-30 11:56:07.817 ThaliTest[2089:1933688] client session: stateChange:1->2 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:56:07.825 ThaliTest[2089:1933688] client session: fireConnectCallback: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:56:07.826 ThaliTest[2089:1933688] jxcore: connect: success
2015-11-30T10:56:07.828Z SendDataConnector.js: CLIENT connected ,to 64011, error: null
2015-11-30T10:56:07.828Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:56:07.832 ThaliTest[2089:1932918] client: relay established
2015-11-30 11:56:07.833 ThaliTest[2089:1932918] client: new accepted socket: 0x19c017b0
,2015-11-30T10:56:07.842Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T10:56:08.379Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-30T10:56:08.379Z SendDataConnector.js: got all data for this round
,2015-11-30T10:56:08.379Z SendDataConnector.js: CLIENT Stop now
2015-11-30T10:56:08.380Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30 11:56:08.380 ThaliTest[2089:1933126] jxcore: disconnect
,2015-11-30 11:56:08.380 ThaliTest[2089:1933126] client session: disconnectFromPeer: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:56:08.380 ThaliTest[2089:1933126] client session: disconnect
,2015-11-30 11:56:08.381 ThaliTest[2089:1933126] client session: stateChange:2->0 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:56:08.384 ThaliTest[2089:1933126] jxcore: disconnect: success
2015-11-30T10:56:08.384Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7389.2i+JNA==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT7955","time":11555,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT2455.0R5G/g==","time":3020,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT4872.+CDkQA==","time":4187,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT7389.2i+JNA==","time":3034,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 4187 ms, 99% : 4187 ms, 95 : 4187 ms, 90% : 4187 ms.
Result count 3, range 3020 ms to  4187 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-30T10:56:08.389Z SendDataConnector.js: CLIENT Stop now
2015-11-30T10:56:08.389Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:56:08.891 ThaliTest[2089:1932918] multipeer session: reset timer
2015-11-30 11:56:08.892 ThaliTest[2089:1932918] multipeer session: stop timer
2015-11-30 11:56:08.892 ThaliTest[2089:1932918] multipeer session: start timer: 0x19d92160
2015-,11-30 11:56:08.893 ThaliTest[2089:1932918] server session: connect
2015-11-30 11:56:08.894 ThaliTest[2089:1932918] server session: stateChange:0->1 Apple-Iphone6-1_PT7389
,2015-11-30 11:56:08.905 ThaliTest[2089:1932918] server: accepting invitation Apple-Iphone6-1_PT7389
,2015-11-30 11:56:11.019 ThaliTest[2089:1933683] server session: connected
2015-11-30 11:56:11.019 ThaliTest[2089:1933683] server session: stateChange:1->2 Apple-Iphone6-1_PT7389
,2015-11-30 11:56:11.030 ThaliTest[2089:1932918] server relay: connected (to port: 63999)
,2015-11-30T10:56:11.037Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T10:56:11.454Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-11-30T10:56:11.469Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-11-30T10:56:11.488Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-11-30T10:56:11.508Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-11-30T10:56:11.526Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-11-30T10:56:11.541Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30 11:56:38.893 ThaliTest[2089:1932918] multipeer session: restart
,2015-11-30 11:56:39.811 ThaliTest[2089:1932918] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
2015-11-30 11:56:39.813 ThaliTest[2089:1932918] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:56:39.837 ThaliTest[2089:1932918] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:57:01.763 ThaliTest[2089:1933954] server session: not connected Apple-Iphone6-1_PT7389
,2015-11-30 11:57:08.894 ThaliTest[2089:1932918] multipeer session: restart
,2015-11-30 11:57:09.264 ThaliTest[2089:1932918] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:57:09.265 ThaliTest[2089:1932918] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
2015-11-30 11:57:09.266 ThaliTest[2089:1932918] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:57:11.835 ThaliTest[2089:1932918] multipeer session: reset timer
2015-11-30 11:57:11.837 ThaliTest[2089:1932918] multipeer session: stop timer
2015-11-30 11:57:11.837 ThaliTest[2089:1932918] multipeer session: start timer: 0x19d92160
2015-,11-30 11:57:11.838 ThaliTest[2089:1932918] server: disconnecting to refresh session (Apple-Iphone6-1_PT7389)
2015-11-30 11:57:11.838 ThaliTest[2089:1932918] server session: disconnect
2015-11-30 11:57:11.839 ThaliTest[2089:1932918] server session: stateC,hange:2->0 Apple-Iphone6-1_PT7389
,2015-11-30T10:57:11.857Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-30 11:57:11.903 ThaliTest[2089:1932918] server session: connect
2015-11-30 11:57:11.905 ThaliTest[2089:1932918] server session: stateChange:0->1 Apple-Iphone6-1_PT7389
,2015-11-30 11:57:11.911 ThaliTest[2089:1932918] server: accepting invitation Apple-Iphone6-1_PT7389
,2015-11-30 11:57:14.078 ThaliTest[2089:1934004] server session: connected
2015-11-30 11:57:14.079 ThaliTest[2089:1934004] server session: stateChange:1->2 Apple-Iphone6-1_PT7389
,2015-11-30 11:57:14.088 ThaliTest[2089:1932918] server relay: connected (to port: 63999)
,2015-11-30T10:57:14.095Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T10:57:14.353Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-30 11:57:15.101 ThaliTest[2089:1932918] client: lost peer: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:57:15.102 ThaliTest[2089:1932918] client session: onPeerLost: Apple-Iphone6-1_PT7389.2i+JNA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:57:19.156 ThaliTest[2089:1933985] server session: not connected Apple-Iphone6-1_PT7389
,2015-11-30 11:57:19.739 ThaliTest[2089:1932918] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 11:57:41.839 ThaliTest[2089:1932918] multipeer session: restart
,2015-11-30 11:57:41.861 ThaliTest[2089:1932918] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:57:41.863 ThaliTest[2089:1932918] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:57:42.212 ThaliTest[2089:1932918] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:57:43.554 ThaliTest[2089:1932918] client: lost peer: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:57:43.554 ThaliTest[2089:1932918] client session: onPeerLost: Apple-Iphone6-1_PT7389.2i+JNA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:57:45.271 ThaliTest[2089:1932918] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 11:58:11.839 ThaliTest[2089:1932918] multipeer session: restart
,2015-11-30 11:58:11.845 ThaliTest[2089:1932918] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** First throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c42,97 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0xc95e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 2089 stopped
* thread #1: tid = 0x1d7e76, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x38dc0df0 <+8>:  blo    0x38dc0e08                ; <+32>
    0x38dc0df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x38dc0df8 <+16>: ldr    r12, [pc, r12]
    0x38dc0dfc <+20>: b      0x38dc0e04                ; <+28>
,* thread #1: tid = 0x1d7e76, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x000c95e2 ThaliTest`main + 50

```
