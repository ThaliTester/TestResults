#### Test 5133502830f515a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502830f515a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/605E8B94-7F8F-40DD-BAEA-4AFE0071601A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/605E8B94-7F8F-40DD-BAEA-4AFE0071601A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502830f515a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502830f515a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0220FA09-5579-4D20-9B90-4E03519EFA30/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55310"
,(lldb)     command script import "/tmp/605E8B94-7F8F-40DD-BAEA-4AFE0071601A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 11:08:04.740 ThaliTest[1284:1710799] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/70FEE1FB-AE98-4840-8A50-23DB9FE815C4/Library/Cookies/Cookies.binarycookies
,2015-11-25 11:08:05.016 ThaliTest[1284:1710799] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 11:08:05.017 ThaliTest[1284:1710799] Multi-tasking -> Device: YES, App: YES
,2015-11-25 11:08:05.023 ThaliTest[1284:1710799] Unlimited access to network resources
,2015-11-25 11:08:05.029 ThaliTest[1284:1710799] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 11:08:09.264 ThaliTest[1284:1710799] Resetting plugins due to page load.
,2015-11-25 11:08:10.697 ThaliTest[1284:1710799] Finished load of: file:///var/mobile/Containers/Bundle/Application/0220FA09-5579-4D20-9B90-4E03519EFA30/ThaliTest.app/www/index.html
,2015-11-25 11:08:10.842 ThaliTest[1284:1710799] JXcore Cordova plugin initializing
,2015-11-25 11:08:10.844 ThaliTest[1284:1710973] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT2339
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 61388
,2015-11-25 11:15:32.705 ThaliTest[1284:1710973] jxcore: startBroadcasting
,2015-11-25 11:15:32.711 ThaliTest[1284:1710973] server: starting Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:15:32.712 ThaliTest[1284:1710973] multipeer session: start timer: 0x16f81e70
,2015-11-25 11:15:32.712 ThaliTest[1284:1710973] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2339
,2015-11-25 11:15:32.712 ThaliTest[1284:1710973] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-25T10:15:32.713Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-25 11:15:33.524 ThaliTest[1284:1710799] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5679.a5FFow==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25T10:15:33.528Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25T10:15:33.528Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25T10:15:33.528Z SendDataConnector.js: do connect now
,2015-11-25 11:15:33.529 ThaliTest[1284:1710973] jxcore: connect Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:15:33.529 ThaliTest[1284:1710973] client session: connect
2015-11-25 11:15:33.529 ThaliTest[1284:1710973] client session: stateChange:0->1 Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:15:33.780 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9949.0t9DBw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 11:15:35.606 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT7626.iyJViA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-11-25 11:15:36.625 ThaliTest[1284:1710799] multipeer session: reset timer
2015-11-25 11:15:36.625 ThaliTest[1284:1710799] multipeer session: stop timer
2015-11-25 11:15:36.625 ThaliTest[1284:1710799] multipeer session: start timer: 0x16f81e70
2015-11-25 11:15:36.625 ThaliTest[1284:1710799] server session: connect
2015-11-25 11:15:36.625 ThaliTest[1284:1710799] server session: stateChange:0->1 Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:36.628 ThaliTest[1284:1710799] server: accepting invitation Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:38.228 ThaliTest[1284:1711729] client session: connected
2015-11-25 11:15:38.228 ThaliTest[1284:1711729] client session: stateChange:1->2 Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:15:38.238 ThaliTest[1284:1711735] client session: fireConnectCallback: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:15:38.238 ThaliTest[1284:1711735] jxcore: connect: success
,2015-11-25T10:15:38.239Z SendDataConnector.js: CLIENT connected to 61392, error: null
2015-11-25T10:15:38.239Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 11:15:38.240 ThaliTest[1284:1710799] client: relay established
2015-11-25 11:15:38.240 ThaliTest[1284:1710799] client: new accepted socket: 0x16cc8a50
,2015-11-25T10:15:38.253Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T10:15:38.376Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T10:15:38.390Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25T10:15:38.403Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T10:15:38.403Z SendDataConnector.js: got all data for this round
,2015-11-25T10:15:38.404Z SendDataConnector.js: CLIENT Stop now
2015-11-25T10:15:38.404Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 11:15:38.405 ThaliTest[1284:1710973] jxcore: disconnect
2015-11-25 11:15:38.405 ThaliTest[1284:1710973] client session: disconnectFromPeer: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:15:38.405 ThaliTest[1284:1710973] client session: disconnect
2015-11-25 11:15:38.405 ThaliTest[1284:1710973] client session: stateChange:2->0 Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:15:38.410 ThaliTest[1284:1710973] jxcore: disconnect: success
2015-11-25T10:15:38.410Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5679.a5FFow==
---- round done--------
device[2]: Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25T10:15:38.411Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25T10:15:38.411Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25T10:15:38.412Z SendDataConnector.js: do connect now
2015-11-25 11:15:38.412 ThaliTest[1284:1710973] jxcore: connect Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25 11:15:38.412 ThaliTest[1284:1710973] client session: connect
2015-11-25 11:15:38.412 ThaliTest[1284:1710973] client session: stateChange:0->1 Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:15:39.279 ThaliTest[1284:1711733] server session: connected
2015-11-25 11:15:39.279 ThaliTest[1284:1711733] server session: stateChange:1->2 Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:39.354 ThaliTest[1284:1710799] server relay: connected (to port: 61388)
,2015-11-25T10:15:39.356Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T10:15:39.408Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-11-25T10:15:39.420Z SendDataTCPServer.js: TCP/IP server has received 69938 bytes of data
,2015-11-25T10:15:39.432Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-11-25T10:15:39.480Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-11-25T10:15:39.493Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 11:15:39.526 ThaliTest[1284:1711737] server session: not connected Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:42.495 ThaliTest[1284:1711732] client session: connected
2015-11-25 11:15:42.495 ThaliTest[1284:1711732] client session: stateChange:1->2 Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:15:42.552 ThaliTest[1284:1711737] client session: fireConnectCallback: Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25 11:15:42.552 ThaliTest[1284:1711737] jxcore: connect: success
2015-11-25T10:15:42.553Z SendDataConnector.js: CLIENT connected, to 61397, error: null
2015-11-25T10:15:42.553Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 11:15:42.554 ThaliTest[1284:1710799] client: relay established
2015-11-25 11:15:42.554 ThaliTest[1284:1710799] client: new accepted socket: 0x16cd7a40
,2015-11-25T10:15:42.567Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T10:15:43.023Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25T10:15:43.049Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T10:15:43.083Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T10:15:43.083Z SendDataConnector.js: got all data for this round
,2015-11-25T10:15:43.084Z SendDataConnector.js: CLIENT Stop now
2015-11-25T10:15:43.084Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 11:15:43.084 ThaliTest[1284:1710973] jxcore: disconnect
2015-11-25 11:15:43.085 ThaliTest[1284:1710973] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25 11:15:43.085 ThaliTest[1284:1710973] client session: disconnect
2015-11-25 11:15:43.086 ThaliTest[1284:1710973] client session: stateChange:2->0 Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:15:43.091 ThaliTest[1284:1710973] jxcore: disconnect: success
2015-11-25T10:15:43.091Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9949.0t9DBw==
---- round done--------
device[3]: Apple-Iphone5-1_PT7626.,iyJViA==
2015-11-25T10:15:43.092Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25T10:15:43.092Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25T10:15:43.092Z SendDataConnector.js: do connect now
2015-11-25 11:15:43.092 ThaliTest[1284:1710973] jxcore: connect Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:15:43.092 ThaliTest[1284:1710973] client session: connect
,2015-11-25 11:15:43.094 ThaliTest[1284:1710973] client session: stateChange:0->1 Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:15:46.063 ThaliTest[1284:1711737] client session: connected
2015-11-25 11:15:46.063 ThaliTest[1284:1711737] client session: stateChange:1->2 Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:15:46.074 ThaliTest[1284:1711737] client session: fireConnectCallback: Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25 11:15:46.074 ThaliTest[1284:1711737] jxcore: connect: success
2015-11-25T10:15:46.075Z SendDataConnector.js: CLIENT connected to 61400, error: null
,2015-11-25T10:15:46.075Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 11:15:46.077 ThaliTest[1284:1710799] client: relay established
2015-11-25 11:15:46.077 ThaliTest[1284:1710799] client: new accepted socket: 0x16ccadd0
,2015-11-25T10:15:46.089Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25 11:15:46.124 ThaliTest[1284:1710799] multipeer session: reset timer
2015-11-25 11:15:46.124 ThaliTest[1284:1710799] multipeer session: stop timer
2015-11-25 11:15:46.124 ThaliTest[1284:1710799] multipeer session: start timer: 0x16f81e70
2015-,11-25 11:15:46.124 ThaliTest[1284:1710799] server session: connect
2015-11-25 11:15:46.124 ThaliTest[1284:1710799] server session: stateChange:0->1 Apple-Iphone5-1_PT7626
,2015-11-25 11:15:46.129 ThaliTest[1284:1710799] server: accepting invitation Apple-Iphone5-1_PT7626
,2015-11-25T10:15:46.187Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T10:15:46.200Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25T10:15:46.212Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T10:15:46.213Z SendDataConnector.js: got all data for this round
,2015-11-25T10:15:46.214Z SendDataConnector.js: CLIENT Stop now
,2015-11-25T10:15:46.214Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 11:15:46.214 ThaliTest[1284:1710973] jxcore: disconnect
2015-11-25 11:15:46.215 ThaliTest[1284:1710973] client session: disconnectFromPeer: Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25 11:15:46.216 ThaliTest[1284:1710973] client session: disconnect
2015-11-25 11:15:46.216 ThaliTest[1284:1710973] client session: stateChange:2->0 Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:15:46.227 ThaliTest[1284:1710973] jxcore: disconnect: success
2015-11-25T10:15:46.228Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT7626.iyJViA==
---- round done--------
weAreDoneNow , resultArray.length: ,3
done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT2339","time":13531,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT5679.a5FFow==","time":4875,"result":"OK","connections":1},{"name":"Apple-Iphone5s-1_PT9949.0t9DBw==","time":4672,"result":"OK","connections":1},{"name":"Apple-Iphone5-1_PT7626.iyJViA==","time":3121,"result":"OK","connections":1}]}
sendList : 100% : 4875 ms, 99% : 4875 ms, 95 : 4875 ms, 90% : 4875 ms.
Result count 3, range 3121 ms to  4875 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-25T10:15:46.235Z SendDataConnector.js: CLIENT Stop now
2015-11-25T10:15:46.235Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 11:15:48.718 ThaliTest[1284:1711729] server session: connected
2015-11-25 11:15:48.718 ThaliTest[1284:1711729] server session: stateChange:1->2 Apple-Iphone5-1_PT7626
,2015-11-25 11:15:48.775 ThaliTest[1284:1710799] server relay: connected (to port: 61388)
,2015-11-25T10:15:48.781Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T10:15:48.878Z SendDataTCPServer.js: TCP/IP server has received 6944 bytes of data
,2015-11-25T10:15:48.912Z SendDataTCPServer.js: TCP/IP server has received 11904 bytes of data
,2015-11-25T10:15:48.926Z SendDataTCPServer.js: TCP/IP server has received 28768 bytes of data
,2015-11-25T10:15:49.192Z SendDataTCPServer.js: TCP/IP server has received 32736 bytes of data
,2015-11-25T10:15:49.244Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
,2015-11-25T10:15:49.255Z SendDataTCPServer.js: TCP/IP server has received 69440 bytes of data
,2015-11-25T10:15:49.442Z SendDataTCPServer.js: TCP/IP server has received 92256 bytes of data
,2015-11-25T10:15:49.456Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 11:15:49.758 ThaliTest[1284:1711729] server session: not connected Apple-Iphone5-1_PT7626
,2015-11-25 11:16:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:16:16.138 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25 11:16:16.138 ThaliTest[1284:1710799] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:16:16.139 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:16:46.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:16:46.136 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:16:46.394 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:16:49.583 ThaliTest[1284:1710799] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:17:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:17:16.137 ThaliTest[1284:1710799] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:17:16.137 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25 11:17:16.137 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:17:43.664 ThaliTest[1284:1710799] client: lost peer: Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25 11:17:43.664 ThaliTest[1284:1710799] client session: onPeerLost: Apple-Iphone5s-1_PT9949.0t9DBw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9949.0t9DBw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 11:17:46.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:17:46.135 ThaliTest[1284:1710799] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:17:46.135 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:17:51.025 ThaliTest[1284:1710799] client: lost peer: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:17:51.025 ThaliTest[1284:1710799] client session: onPeerLost: Apple-Iphone6-1_PT5679.a5FFow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5679.a5FFow==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 11:18:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:18:16.134 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:18:46.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:18:47.044 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:19:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:19:16.133 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:19:46.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:19:46.132 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:20:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:20:16.153 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:20:46.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:20:46.134 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:21:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:21:16.135 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:21:46.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:21:46.312 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:22:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:22:16.134 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:22:46.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:22:47.209 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:23:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:23:16.135 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:23:46.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:23:46.133 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:24:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:24:16.284 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:24:46.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:24:46.134 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:25:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:25:17.048 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:25:46.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:25:46.135 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:26:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:26:16.134 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:26:46.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:26:46.134 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:27:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:27:16.134 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:27:46.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:27:46.972 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:28:16.125 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:28:46.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:28:46.115 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:29:16.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:29:17.177 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:29:46.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:29:46.386 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:30:16.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:30:46.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:30:46.299 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:31:16.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:31:16.116 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:31:46.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:31:46.995 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:32:16.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:32:46.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:32:46.114 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:33:16.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:33:17.163 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:33:46.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:33:46.115 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:34:16.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:34:46.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:34:46.293 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:35:16.107 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:35:16.116 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
,2015-11-25 11:35:46.108 ThaliTest[1284:1710799] multipeer session: restart
,2015-11-25 11:35:47.171 ThaliTest[1284:1710799] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==

```
