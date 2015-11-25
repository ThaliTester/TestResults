#### Test 5133502830f515a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502830f515a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/39BDFCAD-5CC4-4042-8CA5-F91385C33DB0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/39BDFCAD-5CC4-4042-8CA5-F91385C33DB0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502830f515a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502830f515a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0D5B5B6D-28E7-49C1-BBC8-D64F073BB9E4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55328"
,(lldb)     command script import "/tmp/39BDFCAD-5CC4-4042-8CA5-F91385C33DB0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 11:08:55.345 ThaliTest[1594:1357223] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D89430F6-DAE3-4D1B-AB92-749969DCA4C6/Library/Cookies/Cookies.binarycookies
,2015-11-25 11:08:55.767 ThaliTest[1594:1357223] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 11:08:55.768 ThaliTest[1594:1357223] Multi-tasking -> Device: YES, App: YES
,2015-11-25 11:08:55.777 ThaliTest[1594:1357223] Unlimited access to network resources
,2015-11-25 11:08:55.785 ThaliTest[1594:1357223] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 11:08:59.355 ThaliTest[1594:1357223] Resetting plugins due to page load.
,2015-11-25 11:08:59.810 ThaliTest[1594:1357223] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/0D5B5B6D-28E7-49C1-BBC8-D64F073BB9E4/ThaliTest.app/www/index.html
,2015-11-25 11:08:59.966 ThaliTest[1594:1357223] JXcore Cordova plugin initializing
2015-11-25 11:08:59.967 ThaliTest[1594:1357344] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT9949
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[],}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 61856
,2015-11-25 11:15:32.195 ThaliTest[1594:1357344] jxcore: startBroadcasting
,2015-11-25 11:15:32.209 ThaliTest[1594:1357344] server: starting Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:15:32.210 ThaliTest[1594:1357344] multipeer session: start timer: 0x19fa8720
,2015-11-25 11:15:32.211 ThaliTest[1594:1357344] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:32.212 ThaliTest[1594:1357344] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-25T10:15:32.220Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-25 11:15:33.000 ThaliTest[1594:1357223] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5679.a5FFow==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25T10:15:33.008Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25T10:15:33.009Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5679.a5FFow==
20,15-11-25T10:15:33.009Z SendDataConnector.js: do connect now
,2015-11-25 11:15:33.010 ThaliTest[1594:1357344] jxcore: connect Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:15:33.011 ThaliTest[1594:1357344] client session: connect
,2015-11-25 11:15:33.012 ThaliTest[1594:1357344] client session: stateChange:0->1 Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:15:33.178 ThaliTest[1594:1357223] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 11:15:33.412 ThaliTest[1594:1357223] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT7626.iyJViA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-11-25 11:15:35.516 ThaliTest[1594:1357929] client session: connected
2015-11-25 11:15:35.517 ThaliTest[1594:1357929] client session: stateChange:1->2 Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:15:35.525 ThaliTest[1594:1357923] client session: fireConnectCallback: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:15:35.526 ThaliTest[1594:1357923] jxcore: connect: success
2015-11-25T10:15:35.527Z SendDataConnector.js: CLIENT connected ,to 61859, error: null
2015-11-25T10:15:35.528Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 11:15:35.533 ThaliTest[1594:1357223] client: relay established
2015-11-25 11:15:35.533 ThaliTest[1594:1357223] client: new accepted socket: 0x19fbaac0
,2015-11-25T10:15:35.546Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T10:15:35.656Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-25T10:15:35.669Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T10:15:35.680Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T10:15:35.693Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-25T10:15:35.706Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-25T10:15:35.718Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T10:15:35.718Z SendDataConnector.js: got all data for this round
,2015-11-25T10:15:35.719Z SendDataConnector.js: CLIENT Stop now
2015-11-25T10:15:35.720Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 11:15:35.720 ThaliTest[1594:1357344] jxcore: disconnect
,2015-11-25 11:15:35.721 ThaliTest[1594:1357344] client session: disconnectFromPeer: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:15:35.721 ThaliTest[1594:1357344] client session: disconnect
2015-11-25 11:15:35.721 ThaliTest[1594:1357344] client session:, stateChange:2->0 Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:15:35.723 ThaliTest[1594:1357344] jxcore: disconnect: success
,2015-11-25T10:15:35.723Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5679.a5FFow==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25T10:15:35.728Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25T10:15:35.729Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25T10:15:35.729Z SendDataConnector.js: do connect now
,2015-11-25 11:15:35.729 ThaliTest[1594:1357344] jxcore: connect Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:15:35.730 ThaliTest[1594:1357344] client session: connect
,2015-11-25 11:15:35.731 ThaliTest[1594:1357344] client session: stateChange:0->1 Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:15:38.664 ThaliTest[1594:1357223] multipeer session: reset timer
2015-11-25 11:15:38.665 ThaliTest[1594:1357223] multipeer session: stop timer
2015-11-25 11:15:38.666 ThaliTest[1594:1357223] multipeer session: start timer: 0x19fa8720
2015-11-25 11:15:38.666 ThaliTest[1594:1357223] server session: connect
2015-11-25 11:15:38.667 ThaliTest[1594:1357223] server session: stateChange:0->1 Apple-Iphone5-1_PT7626
,2015-11-25 11:15:38.675 ThaliTest[1594:1357223] server: accepting invitation Apple-Iphone5-1_PT7626
,2015-11-25 11:15:38.718 ThaliTest[1594:1357929] client session: connected
2015-11-25 11:15:38.719 ThaliTest[1594:1357929] client session: stateChange:1->2 Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:15:38.723 ThaliTest[1594:1357929] client session: fi,reConnectCallback: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:15:38.724 ThaliTest[1594:1357929] jxcore: connect: success
,2015-11-25T10:15:38.725Z SendDataConnector.js: CLIENT connected to 61862, error: null
2015-11-25T10:15:38.727Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 11:15:38.731 ThaliTest[1594:1357223] client: relay established
2015-11-25 11:15:38.732 ThaliTest[1594:1357223] client: new accepted socket: 0x19ed3fe0
,2015-11-25T10:15:38.743Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T10:15:38.851Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T10:15:38.886Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-25T10:15:38.949Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T10:15:38.949Z SendDataConnector.js: got all data for this round
,2015-11-25T10:15:38.950Z SendDataConnector.js: CLIENT Stop now
2015-11-25T10:15:38.950Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 11:15:38.950 ThaliTest[1594:1357344] jxcore: disconnect
2015-11-25 11:15:38.951 ThaliTest[1594:1357344] cli,ent session: disconnectFromPeer: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:15:38.951 ThaliTest[1594:1357344] client session: disconnect
2015-11-25 11:15:38.951 ThaliTest[1594:1357344] client session: stateChange:2->0 Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:15:38.952 ThaliTest[1594:1357344] jxcore: disconnect: success
2015-11-25T10:15:38.952Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2339.pNGAWw==
---- round done--------
device[3]: Apple-Iphone5-1_PT7626.,iyJViA==
2015-11-25T10:15:38.953Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25T10:15:38.954Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25T10:15:38.954Z SendDataConnector.js: do connect now
2015-11-25 11:15:38.954 ThaliTest[1594:1357344] jxcore: connect Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25 11:15:38.954 ThaliTest[1594:1357344] client session: connect
2015-11-25 11:15:38.955 ThaliTest[1594:1357344] client session: stateChange:0->1 Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:15:38.974 ThaliTest[1594:1357223] multipeer session: reset timer
2015-11-25 11:15:38.974 ThaliTest[1594:1357223] multipeer session: stop timer
2015-11-25 11:15:38.974 ThaliTest[1594:1357223] multipeer session: start timer: 0x19fa8720
2015-,11-25 11:15:38.975 ThaliTest[1594:1357223] server session: connect
2015-11-25 11:15:38.975 ThaliTest[1594:1357223] server session: stateChange:0->1 Apple-IpadAir2-1_PT2339
,2015-11-25 11:15:38.982 ThaliTest[1594:1357223] server: accepting invitation Apple-IpadAir2-1_PT2339
,2015-11-25 11:15:41.309 ThaliTest[1594:1357929] server session: connected
2015-11-25 11:15:41.310 ThaliTest[1594:1357929] server session: stateChange:1->2 Apple-Iphone5-1_PT7626
,2015-11-25 11:15:41.318 ThaliTest[1594:1357223] server relay: connected (to port: 61856)
,2015-11-25T10:15:41.323Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25 11:15:41.416 ThaliTest[1594:1357935] client session: connected
2015-11-25 11:15:41.417 ThaliTest[1594:1357935] client session: stateChange:1->2 Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:15:41.424 ThaliTest[1594:1357935] client session: fireConnectCallback: Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25 11:15:41.426 ThaliTest[1594:1357935] jxcore: connect: success
2015-11-25T10:15:41.427Z SendDataConnector.js: CLIENT connected ,to 61866, error: null
2015-11-25T10:15:41.428Z SendDataConnector.js: CLIENT starting client 
2015-11-25 11:15:41.431 ThaliTest[1594:1357223] client: relay established
2015-11-25 11:15:41.432 ThaliTest[1594:1357223] client: new accepted socket: 0x19ecc390
,2015-11-25T10:15:41.444Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T10:15:41.549Z SendDataTCPServer.js: TCP/IP server has received 77376 bytes of data
,2015-11-25T10:15:41.798Z SendDataTCPServer.js: TCP/IP server has received 81344 bytes of data
,2015-11-25T10:15:41.814Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25T10:15:41.839Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T10:15:41.853Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T10:15:41.876Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25 11:15:41.886 ThaliTest[1594:1357935] server session: not connected Apple-Iphone5-1_PT7626
,2015-11-25T10:15:41.889Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-25T10:15:41.930Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T10:15:41.931Z SendDataConnector.js: got all data for this round
,2015-11-25T10:15:41.933Z SendDataConnector.js: CLIENT Stop now
2015-11-25T10:15:41.933Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 11:15:41.934 ThaliTest[1594:1357344] jxcore: disconnect
,2015-11-25 11:15:41.935 ThaliTest[1594:1357344] client session: disconnectFromPeer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:15:41.936 ThaliTest[1594:1357344] client session: disconnect
,2015-11-25 11:15:41.936 ThaliTest[1594:1357344] client session: stateChange:2->0 Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:15:41.939 ThaliTest[1594:1357935] server session: connected
2015-11-25 11:15:41.940 ThaliTest[1594:1357935] server session: stateChange:1->2 Apple-IpadAir2-1_PT2339
,2015-11-25 11:15:41.944 ThaliTest[1594:1357223] server relay: connected (to port: 61856)
,2015-11-25 11:15:41.947 ThaliTest[1594:1357344] jxcore: disconnect: success
,2015-11-25T10:15:41.954Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT7626.iyJViA==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT9949","time":9780,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT5679.a5FFow==","time":2711,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT2339.pNGAWw==","time":3220,"result":"OK","connections":,1},{"name":"Apple-Iphone5-1_PT7626.iyJViA==","time":2977,"result":"OK","connections":1}]}
,sendList : 100% : 3220 ms, 99% : 3220 ms, 95 : 3220 ms, 90% : 3220 ms.
,Result count 3, range 2711 ms to  3220 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-25T10:15:41.968Z SendDataConnector.js: CLIENT Stop now
,2015-11-25T10:15:41.969Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25T10:15:41.983Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T10:15:42.066Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-11-25T10:15:42.082Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-11-25T10:15:42.095Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-11-25T10:15:42.335Z SendDataTCPServer.js: TCP/IP server has received 54466 bytes of data
,2015-11-25T10:15:42.353Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-11-25T10:15:42.369Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 11:15:42.542 ThaliTest[1594:1357935] server session: not connected Apple-IpadAir2-1_PT2339
,2015-11-25 11:16:08.976 ThaliTest[1594:1357223] multipeer session: restart
,2015-11-25 11:16:09.094 ThaliTest[1594:1357223] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:16:09.095 ThaliTest[1594:1357223] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:16:09.139 ThaliTest[1594:1357223] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:16:38.976 ThaliTest[1594:1357223] multipeer session: restart
,2015-11-25 11:16:39.002 ThaliTest[1594:1357223] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25 11:16:39.003 ThaliTest[1594:1357223] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:16:39.004 ThaliTest[1594:1357223] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-11-25 11:17:08.975 ThaliTest[1594:1357223] multipeer session: restart
,2015-11-25 11:17:09.002 ThaliTest[1594:1357223] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25 11:17:09.003 ThaliTest[1594:1357223] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:17:09.004 ThaliTest[1594:1357223] clien,t: found peer: Apple-Iphone6-1_PT5679.a5FFow==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-11-25 11:17:16.891 ThaliTest[1594:1357223] client: lost peer: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:17:16.892 ThaliTest[1594:1357223] client session: onPeerLost: Apple-Iphone6-1_PT5679.a5FFow==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT5679.a5FFow==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 11:17:17.325 ThaliTest[1594:1357223] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5679.a5FFow==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-11-25 11:17:22.285 ThaliTest[1594:1357223] client: lost peer: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:17:22.286 ThaliTest[1594:1357223] client session: onPeerLost: Apple-Iphone6-1_PT5679.a5FFow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5679.a5FFow==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-11-25 11:17:23.480 ThaliTest[1594:1357223] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5679.a5FFow==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-11-25 11:17:38.974 ThaliTest[1594:1357223] multipeer session: restart
2015-11-25 11:17:38.980 ThaliTest[1594:1357223] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0x3d5e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 1594 stopped
* thread #1: tid = 0x14b5a7, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x38dc0df0 <+8>:  blo    0x38dc0e08                ; <+32>
    0x38dc0df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x38dc0df8 <+16>: ldr    r12, [pc, r12]
    0x38dc0dfc <+20>: b      0x38dc0e04                ; <+28>
,* thread #1: tid = 0x14b5a7, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x0003d5e2 ThaliTest`main + 50

```
