#### Test 539786639813e59_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/539786639813e59/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/2F2D13EA-72C8-4674-B98D-66C6FF0BBD51/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2F2D13EA-72C8-4674-B98D-66C6FF0BBD51/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/539786639813e59/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/539786639813e59/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/92EA907E-5354-4D22-8689-0200DD99CCA7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59291"
,(lldb)     command script import "/tmp/2F2D13EA-72C8-4674-B98D-66C6FF0BBD51/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-17 15:09:25.470 ThaliTest[370:228050] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AE639A85-E3A7-40BD-A4FD-6514C08F3F7A/Library/Cookies/Cookies.binarycookies
,2015-12-17 15:09:25.902 ThaliTest[370:228050] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-17 15:09:25.905 ThaliTest[370:228050] Multi-tasking -> Device: YES, App: YES
,2015-12-17 15:09:25.917 ThaliTest[370:228050] Unlimited access to network resources
,2015-12-17 15:09:25.936 ThaliTest[370:228050] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-17 15:09:35.434 ThaliTest[370:228050] Resetting plugins due to page load.
,2015-12-17 15:09:38.904 ThaliTest[370:228050] Finished load of: file:///var/mobile/Containers/Bundle/Application/92EA907E-5354-4D22-8689-0200DD99CCA7/ThaliTest.app/www/index.html
,2015-12-17 15:09:39.085 ThaliTest[370:228050] JXcore Cordova plugin initializing
,2015-12-17 15:09:39.086 ThaliTest[370:228260] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT1480
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 51473
,2015-12-17 15:16:43.683 ThaliTest[370:228260] jxcore: startBroadcasting
,2015-12-17 15:16:43.701 ThaliTest[370:228260] server: starting Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17 15:16:43.703 ThaliTest[370:228260] multipeer session: start timer: 0x15f66480
2015-12-17 15:16:43.706 ThaliTest[370:228260] THEMultipeerSession initialized peer Apple-Iphone6-1_PT1480
,2015-12-17 15:16:43.708 ThaliTest[370:228260] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-17T14:16:43.712Z SendDataTCPServer.js: TCP/IP server is bound to port: 51473
,2015-12-17 15:16:45.239 ThaliTest[370:228050] client: found peer: Apple-IpadAir2-1_PT1563.8yqJeg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1563.8yqJeg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT1563.8yqJeg==
2015-12-17T14:16:45.246Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1563.8yqJeg==
2015-12-17T14:16:45.247Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1563.8yqJeg==,
2015-12-17T14:16:45.247Z SendDataConnector.js: do connect now
2015-12-17 15:16:45.248 ThaliTest[370:228260] jxcore: connect Apple-IpadAir2-1_PT1563.8yqJeg==
2015-12-17 15:16:45.249 ThaliTest[370:228260] client session: connect
2015-12-17 15:16:45.249 T,haliTest[370:228260] client session: stateChange:0->1 Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17 15:16:45.507 ThaliTest[370:228050] multipeer session: reset timer
2015-12-17 15:16:45.508 ThaliTest[370:228050] multipeer session: stop timer
2015-12-17 15:16:45.508 ThaliTest[370:228050] multipeer session: start timer: 0x15f66480
2015-12-17 ,15:16:45.508 ThaliTest[370:228050] server session: connect
2015-12-17 15:16:45.509 ThaliTest[370:228050] server session: stateChange:0->1 Apple-IpadAir2-1_PT1563
,2015-12-17 15:16:45.519 ThaliTest[370:228050] server: accepting invitation Apple-IpadAir2-1_PT1563
,2015-12-17 15:16:46.515 ThaliTest[370:228050] client: found peer: Apple-Iphone5s-1_PT1370.za9tCA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1370.za9tCA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-17 15:16:47.271 ThaliTest[370:228050] client: found peer: Apple-Iphone5-1_PT5479.4UkRdw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5479.4UkRdw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-17 15:16:48.928 ThaliTest[370:228911] server session: connected
2015-12-17 15:16:48.928 ThaliTest[370:228911] server session: stateChange:1->2 Apple-IpadAir2-1_PT1563
,2015-12-17 15:16:48.935 ThaliTest[370:228911] client session: connected
2015-12-17 15:16:48.935 ThaliTest[370:228911] client session: stateChange:1->2 Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17 15:16:48.969 ThaliTest[370:228912] client session: fireConnectCallback: Apple-IpadAir2-1_PT1563.8yqJeg==
2015-12-17 15:16:48.970 ThaliTest[370:228912] jxcore: connect: success
2015-12-17T14:16:48.973Z SendDataTCPServer.js: TCP/IP server connec,ted
2015-12-17T14:16:48.975Z SendDataConnector.js: CLIENT connected to 51476, error: null
2015-12-17T14:16:48.975Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 15:16:48.981 ThaliTest[370:228050] client: relay established
2015-12-17 15:16:48.981 ThaliTest[370:228050] client: new accepted socket: 0x15dbf3d0
,2015-12-17 15:16:48.983 ThaliTest[370:228050] server relay: connected (to port: 51473)
,2015-12-17T14:16:48.994Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T14:16:49.511Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-17T14:16:49.537Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-17T14:16:49.574Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-17T14:16:49.714Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-17T14:16:49.715Z SendDataConnector.js: got all data for this round
,2015-12-17T14:16:49.717Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T14:16:49.719Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:16:49.721 ThaliTest[370:228260] jxcore: disconnect
,2015-12-17 15:16:49.723 ThaliTest[370:228260] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17 15:16:49.724 ThaliTest[370:228260] client session: disconnect
,2015-12-17 15:16:49.725 ThaliTest[370:228260] client session: stateChange:2->0 Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17 15:16:49.826 ThaliTest[370:228260] jxcore: disconnect: success
2015-12-17T14:16:49.827Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1563.8yqJeg==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17T14:16:49.831Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17T14:16:49.831Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1370.za9tCA==,
2015-12-17T14:16:49.832Z SendDataConnector.js: do connect now
2015-12-17 15:16:49.832 ThaliTest[370:228260] jxcore: connect Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17 15:16:49.833 ThaliTest[370:228260] client session: connect
2015-12-17 15:16:49.833 T,haliTest[370:228260] client session: stateChange:0->1 Apple-Iphone5s-1_PT1370.za9tCA==
,2015-12-17T14:16:50.239Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-17T14:16:51.323Z SendDataTCPServer.js: TCP/IP server has received 93662 bytes of data
,2015-12-17T14:16:51.342Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 15:16:51.420 ThaliTest[370:228890] server session: not connected Apple-IpadAir2-1_PT1563
,2015-12-17 15:16:53.194 ThaliTest[370:228890] client session: connected
2015-12-17 15:16:53.194 ThaliTest[370:228890] client session: stateChange:1->2 Apple-Iphone5s-1_PT1370.za9tCA==
,2015-12-17 15:16:53.220 ThaliTest[370:228911] client session: fireConnectCallback: Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17 15:16:53.220 ThaliTest[370:228911] jxcore: connect: success
2015-12-17T14:16:53.222Z SendDataConnector.js: CLIENT connected to ,51480, error: null
2015-12-17T14:16:53.222Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 15:16:53.226 ThaliTest[370:228050] client: relay established
2015-12-17 15:16:53.226 ThaliTest[370:228050] client: new accepted socket: 0x15dc3130
,2015-12-17T14:16:53.237Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T14:16:53.587Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-17T14:16:53.613Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-17T14:16:53.624Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-17T14:16:53.648Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-17T14:16:53.659Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T14:16:53.660Z SendDataConnector.js: got all data for this round
,2015-12-17T14:16:53.660Z SendDataConnector.js: CLIENT Stop now
2015-12-17T14:16:53.661Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:16:53.661 ThaliTest[370:228260] jxcore: disconnect
2015-12-17 15:16:53.661 ThaliTest[370:228260] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17 15:16:53.661 ThaliTest[370:228260] client session: disconnect
2015-12-17 15:16:53.661 ThaliTest[370:228260] client session: stateChange:2->0 Apple-Iphone5s-1_PT1370.za9tCA==
,2015-12-17 15:16:53.727 ThaliTest[370:228260] jxcore: disconnect: success
,2015-12-17T14:16:53.728Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1370.za9tCA==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17T14:16:53.730Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17T14:16:53.730Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17T14:16:53.730Z SendDataConnector.js: do connect now
,2015-12-17 15:16:53.730 ThaliTest[370:228260] jxcore: connect Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:16:53.731 ThaliTest[370:228260] client session: connect
,2015-12-17 15:16:53.731 ThaliTest[370:228260] client session: stateChange:0->1 Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:16:56.708 ThaliTest[370:228050] multipeer session: reset timer
2015-12-17 15:16:56.708 ThaliTest[370:228050] multipeer session: stop timer
2015-12-17 15:16:56.708 ThaliTest[370:228050] multipeer session: start timer: 0x15f66480
2015-12-17 ,15:16:56.709 ThaliTest[370:228050] server session: connect
2015-12-17 15:16:56.709 ThaliTest[370:228050] server session: stateChange:0->1 Apple-Iphone5s-1_PT1370
,2015-12-17 15:16:56.723 ThaliTest[370:228050] server: accepting invitation Apple-Iphone5s-1_PT1370
,2015-12-17 15:16:56.798 ThaliTest[370:228912] client session: connected
2015-12-17 15:16:56.798 ThaliTest[370:228912] client session: stateChange:1->2 Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:16:56.817 ThaliTest[370:228890] client session: fireConnectCallback: Apple-Iphone5-1_PT5479.4UkRdw==
2015-12-17 15:16:56.817 ThaliTest[370:228890] jxcore: connect: success
2015-12-17T14:16:56.818Z SendDataConnector.js: CLIENT connected to 51483, error: null
2015-12-17T14:16:56.818Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 15:16:56.821 ThaliTest[370:228050] client: relay established
2015-12-17 15:16:56.822 ThaliTest[370:228050] client: new accepted socket: 0x15db6320
,2015-12-17T14:16:56.832Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T14:16:57.243Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-17T14:16:57.256Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-17T14:16:57.610Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-17T14:16:57.611Z SendDataConnector.js: got all data for this round
,2015-12-17T14:16:57.613Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T14:16:57.614Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:16:57.616 ThaliTest[370:228260] jxcore: disconnect
,2015-12-17 15:16:57.617 ThaliTest[370:228260] client session: disconnectFromPeer: Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:16:57.619 ThaliTest[370:228260] client session: disconnect
,2015-12-17 15:16:57.620 ThaliTest[370:228260] client session: stateChange:2->0 Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:16:57.711 ThaliTest[370:228260] jxcore: disconnect: success
,2015-12-17T14:16:57.713Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5479.4UkRdw==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT1480","time":14050,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT1563.8yqJeg==","time":4470,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1,_PT1370.za9tCA==","time":3829,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT5479.4UkRdw==","time":3882,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":1000,00}]}
,sendList : 100% : 4470 ms, 99% : 4470 ms, 95 : 4470 ms, 90% : 4470 ms.
,Result count 3, range 3829 ms to  4470 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-17T14:16:57.731Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T14:16:57.732Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:16:59.212 ThaliTest[370:228911] server session: connected
2015-12-17 15:16:59.213 ThaliTest[370:228911] server session: stateChange:1->2 Apple-Iphone5s-1_PT1370
,2015-12-17 15:16:59.247 ThaliTest[370:228050] server relay: connected (to port: 51473)
2015-12-17T14:16:59.251Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T14:16:59.540Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-17T14:16:59.557Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-17T14:16:59.573Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-17T14:16:59.588Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-17T14:16:59.604Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 15:16:59.693 ThaliTest[370:228904] server session: not connected Apple-Iphone5s-1_PT1370
,2015-12-17 15:17:00.985 ThaliTest[370:228050] multipeer session: reset timer
2015-12-17 15:17:00.985 ThaliTest[370:228050] multipeer session: stop timer
2015-12-17 15:17:00.985 ThaliTest[370:228050] multipeer session: start timer: 0x15f66480
,2015-12-17 15:17:00.986 ThaliTest[370:228050] server session: connect
2015-12-17 15:17:00.987 ThaliTest[370:228050] server session: stateChange:0->1 Apple-Iphone5-1_PT5479
2015-12-17 15:17:00.995 ThaliTest[370:228050] server: accepting invitation Apple-Iphone5-1_PT5479
,2015-12-17 15:17:03.629 ThaliTest[370:228904] server session: connected
2015-12-17 15:17:03.629 ThaliTest[370:228904] server session: stateChange:1->2 Apple-Iphone5-1_PT5479
,2015-12-17 15:17:03.660 ThaliTest[370:228050] server relay: connected (to port: 51473)
,2015-12-17T14:17:03.668Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T14:17:04.166Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-17T14:17:04.180Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-17T14:17:04.197Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-17T14:17:04.215Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-17T14:17:04.232Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-17T14:17:04.348Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 15:17:04.426 ThaliTest[370:228911] server session: not connected Apple-Iphone5-1_PT5479
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-12-17 15:17:05.873 ThaliTest[370:228260] jxcore: stopBroadcasting
2015-12-17 15:17:05.874 ThaliTest[370:228260] THEMultipeerSession stopping peer
2015-12-17 15:17:05.875 ThaliTest[370:228260] multipeer session: stop timer
2015-12-17 15:17:05.875 Th,aliTest[370:228260] server session: disconnect
2015-12-17 15:17:05.876 ThaliTest[370:228260] server session: stateChange:2->0 Apple-Iphone5s-1_PT1370
,2015-12-17 15:17:06.015 ThaliTest[370:228260] server session: disconnect
,2015-12-17 15:17:06.017 ThaliTest[370:228260] server session: stateChange:2->0 Apple-Iphone5-1_PT5479
,2015-12-17 15:17:06.022 ThaliTest[370:228260] server session: disconnect
,2015-12-17 15:17:06.023 ThaliTest[370:228260] server session: stateChange:2->0 Apple-IpadAir2-1_PT1563
,2015-12-17 15:17:06.905 ThaliTest[370:228260] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-17T14:17:06.920Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T14:17:06.924Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T14:17:06.926Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T14:17:06.927Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT1370.za9tCA==\",\"time\":3829,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5-1_PT5479.4UkRdw==\",\"time\":3882,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-IpadAir2-1_PT1563.8yqJeg==\",\"time\":4470,\"result\":\"OK\",\"connections\":,1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
