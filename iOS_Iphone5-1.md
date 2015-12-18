#### Test 539786637913587_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/539786637913587/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D9B35B1E-278A-43F2-A511-166136AEB1F7/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D9B35B1E-278A-43F2-A511-166136AEB1F7/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/539786637913587/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/539786637913587/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1EAC9DD9-20B2-4CC5-93EB-565CCAA9E899/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59889"
,(lldb)     command script import "/tmp/D9B35B1E-278A-43F2-A511-166136AEB1F7/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 13:43:53.594 ThaliTest[347:403080] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D8382AAA-8E1E-4982-B2F4-FC8D2696FA4F/Library/Cookies/Cookies.binarycookies
,2015-12-18 13:43:53.718 ThaliTest[347:403080] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 13:43:53.720 ThaliTest[347:403080] Multi-tasking -> Device: YES, App: YES
,2015-12-18 13:43:53.725 ThaliTest[347:403080] Unlimited access to network resources
,2015-12-18 13:43:53.736 ThaliTest[347:403080] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 13:44:04.515 ThaliTest[347:403080] Resetting plugins due to page load.
,2015-12-18 13:44:08.101 ThaliTest[347:403080] Finished load of: file:///var/mobile/Containers/Bundle/Application/1EAC9DD9-20B2-4CC5-93EB-565CCAA9E899/ThaliTest.app/www/index.html
,2015-12-18 13:44:08.310 ThaliTest[347:403080] JXcore Cordova plugin initializing
,2015-12-18 13:44:08.311 ThaliTest[347:403274] JXcore instance initializing
Initializing JXcore engine
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
,my name is : Apple-Iphone5-1_PT724
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
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
,serverPort is 52505
,2015-12-18 13:53:32.191 ThaliTest[347:403274] jxcore: startBroadcasting
,2015-12-18 13:53:32.205 ThaliTest[347:403274] server: starting Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 13:53:32.205 ThaliTest[347:403274] multipeer session: start timer: 0x19ecdd00
,2015-12-18 13:53:32.206 ThaliTest[347:403274] THEMultipeerSession initialized peer Apple-Iphone5-1_PT724
,2015-12-18 13:53:32.207 ThaliTest[347:403274] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-18T12:53:32.209Z SendDataTCPServer.js: TCP/IP server is bound to port: 52505
,2015-12-18 13:53:33.304 ThaliTest[347:403080] client: found peer: Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18 13:53:33.305 ThaliTest[347:403080] client: found peer: Apple-Iphone6-1_PT215.JwJUFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s,-1_PT4751.qR8AbA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[1]: Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18T12:53:33.309Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4751.qR8AbA==
2015-,12-18T12:53:33.310Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18T12:53:33.310Z SendDataConnector.js: do connect now
2015-12-18 13:53:33.310 ThaliTest[347:403274] jxcore: connect Apple-Iphone5s-1_PT4751.qR8A,bA==
2015-12-18 13:53:33.310 ThaliTest[347:403274] client session: connect
2015-12-18 13:53:33.311 ThaliTest[347:403274] client session: stateChange:0->1 Apple-Iphone5s-1_PT4751.qR8AbA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT215.JwJUFw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 13:53:33.418 ThaliTest[347:403080] client: found peer: Apple-IpadAir2-1_PT1412.+KloFA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1412.+KloFA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 13:53:37.021 ThaliTest[347:404794] client session: connected
2015-12-18 13:53:37.022 ThaliTest[347:404794] client session: stateChange:1->2 Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18 13:53:37.024 ThaliTest[347:404794] client session: fireConn,ectCallback: Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18 13:53:37.024 ThaliTest[347:404794] jxcore: connect: success
2015-12-18T12:53:37.025Z SendDataConnector.js: CLIENT connected to 52508, error: null
2015-12-18T12:53:37.026Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 13:53:37.030 ThaliTest[347:403080] client: relay established
2015-12-18 13:53:37.030 ThaliTest[347:403080] client: new accepted socket: 0x19f9c780
,2015-12-18T12:53:37.043Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T12:53:37.651Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T12:53:37.670Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-18T12:53:37.685Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T12:53:37.686Z SendDataConnector.js: got all data for this round
,2015-12-18T12:53:37.689Z SendDataConnector.js: CLIENT Stop now
2015-12-18T12:53:37.689Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 13:53:37.691 ThaliTest[347:403274] jxcore: disconnect
,2015-12-18 13:53:37.692 ThaliTest[347:403274] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18 13:53:37.694 ThaliTest[347:403274] client session: disconnect
,2015-12-18 13:53:37.695 ThaliTest[347:403274] client session: stateChange:2->0 Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18 13:53:37.791 ThaliTest[347:403274] jxcore: disconnect: success
,2015-12-18T12:53:37.794Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4751.qR8AbA==
,---- round done--------
,device[2]: Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18T12:53:37.796Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18T12:53:37.796Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18T12:53:37.796Z SendDataConnector.js: do connect now
,2015-12-18 13:53:37.798 ThaliTest[347:403274] jxcore: connect Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18 13:53:37.798 ThaliTest[347:403274] client session: connect
2015-12-18 13:53:37.799 ThaliTest[347:403274] client session: stateChange:0->1 Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:53:38.115 ThaliTest[347:403080] multipeer session: reset timer
2015-12-18 13:53:38.115 ThaliTest[347:403080] multipeer session: stop timer
2015-12-18 13:53:38.115 ThaliTest[347:403080] multipeer session: start timer: 0x19ecdd00
2015-12-18 13:53:38.115 ThaliTest[347:403080] server session: connect
2015-12-18 13:53:38.116 ThaliTest[347:403080] server session: stateChange:0->1 Apple-IpadAir2-1_PT1412
,2015-12-18 13:53:38.122 ThaliTest[347:403080] server: accepting invitation Apple-IpadAir2-1_PT1412
,2015-12-18 13:53:41.158 ThaliTest[347:404794] client session: connected
2015-12-18 13:53:41.158 ThaliTest[347:404794] client session: stateChange:1->2 Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:53:41.223 ThaliTest[347:404800] server session: connected
2015-12-18 13:53:41.223 ThaliTest[347:404800] server session: stateChange:1->2 Apple-IpadAir2-1_PT1412
,2015-12-18 13:53:41.230 ThaliTest[347:404794] client session: fireConnectCallback: Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18 13:53:41.235 ThaliTest[347:404794] jxcore: connect: success
2015-12-18T12:53:41.238Z SendDataConnector.js: CLIENT connected to 52511, error: null
2015-12-18T12:53:41.239Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 13:53:41.243 ThaliTest[347:403080] client: relay established
2015-12-18 13:53:41.243 ThaliTest[347:403080] client: new accepted socket: 0x19fa7670
,2015-12-18 13:53:41.247 ThaliTest[347:403080] server relay: connected (to port: 52505)
,2015-12-18T12:53:41.255Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T12:53:41.255Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18 13:53:41.379 ThaliTest[347:403080] multipeer session: reset timer
2015-12-18 13:53:41.379 ThaliTest[347:403080] multipeer session: stop timer
2015-12-18 13:53:41.379 ThaliTest[347:403080] multipeer session: start timer: 0x19ecdd00
2015-12-18 ,13:53:41.380 ThaliTest[347:403080] server session: connect
2015-12-18 13:53:41.380 ThaliTest[347:403080] server session: stateChange:0->1 Apple-Iphone5s-1_PT4751
2015-12-18 13:53:41.387 ThaliTest[347:403080] server: accepting invitation Apple-Iphone5s-1_PT4751
,2015-12-18T12:53:41.901Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18T12:53:41.970Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18 13:53:42.203 ThaliTest[347:404794] server session: not connected Apple-IpadAir2-1_PT1412
,2015-12-18T12:53:42.210Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-18T12:53:42.262Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T12:53:42.262Z SendDataConnector.js: got all data for this round
,2015-12-18T12:53:42.264Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T12:53:42.265Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 13:53:42.267 ThaliTest[347:403274] jxcore: disconnect
,2015-12-18 13:53:42.268 ThaliTest[347:403274] client session: disconnectFromPeer: Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:53:42.269 ThaliTest[347:403274] client session: disconnect
,2015-12-18 13:53:42.270 ThaliTest[347:403274] client session: stateChange:2->0 Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:53:42.360 ThaliTest[347:403274] jxcore: disconnect: success
2015-12-18T12:53:42.360Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT215.JwJUFw==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT1412.+KloFA==
2015-12-18T12:53:42.363Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1412.+KloFA==
2015-12-18T12:53:42.363Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1412.+KloFA==,
2015-12-18T12:53:42.364Z SendDataConnector.js: do connect now
2015-12-18 13:53:42.364 ThaliTest[347:403274] jxcore: connect Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:53:42.366 ThaliTest[347:403274] client session: connect
2015-12-18 13:53:42.366 ThaliTest[347:403274] client session: stateChange:0->1 Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:53:44.437 ThaliTest[347:404860] server session: connected
2015-12-18 13:53:44.437 ThaliTest[347:404860] server session: stateChange:1->2 Apple-Iphone5s-1_PT4751
,2015-12-18 13:53:44.444 ThaliTest[347:403080] server relay: connected (to port: 52505)
2015-12-18T12:53:44.449Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T12:53:44.812Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-18T12:53:44.824Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-18T12:53:44.839Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-18T12:53:44.854Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-18T12:53:44.871Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 13:53:44.927 ThaliTest[347:404794] server session: not connected Apple-Iphone5s-1_PT4751
,2015-12-18 13:53:45.891 ThaliTest[347:404798] client session: connected
2015-12-18 13:53:45.892 ThaliTest[347:404798] client session: stateChange:1->2 Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:53:45.921 ThaliTest[347:404860] client session: fireConnectCallback: Apple-IpadAir2-1_PT1412.+KloFA==
2015-12-18 13:53:45.921 ThaliTest[347:404860] jxcore: connect: success
2015-12-18T12:53:45.921Z SendDataConnector.js: CLIENT connected to 52516, error: null
2015-12-18T12:53:45.922Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 13:53:45.924 ThaliTest[347:403080] client: relay established
,2015-12-18 13:53:45.925 ThaliTest[347:403080] client: new accepted socket: 0x19e74500
,2015-12-18T12:53:45.937Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T12:53:46.492Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-18T12:53:46.591Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-18T12:53:46.616Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T12:53:46.617Z SendDataConnector.js: got all data for this round
,2015-12-18T12:53:46.619Z SendDataConnector.js: CLIENT Stop now
2015-12-18T12:53:46.619Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 13:53:46.620 ThaliTest[347:403274] jxcore: disconnect
2015-12-18 13:53:46.620 ThaliTest[347:403274] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1412.+KloFA==
2015-12-18 13:53:46.621 ThaliTest[347:403274] client session: disconnect
2015-12-18 13:53:46.621 ThaliTest[347:403274] client session: stateChange:2->0 Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:53:46.641 ThaliTest[347:403274] jxcore: disconnect: success
2015-12-18T12:53:46.641Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1412.+KloFA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone5-1_PT724","time":14461,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT4751.qR8AbA==","time":4379,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataR,eceived":100000},{"name":"Apple-Iphone6-1_PT215.JwJUFw==","time":4467,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT1412.+KloFA==","time":4254,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4467 ms, 99% : 4467 ms, 95 : 4467 ms, 90% : 4467 ms.
Result count 3, range 4254 ms to  4467 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-18T12:53:46.654Z SendDataConnector.js: CLIENT Stop now
2015-12-18T12:53:46.654Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 13:54:11.381 ThaliTest[347:403080] multipeer session: restart
,2015-12-18 13:54:11.426 ThaliTest[347:403080] client: found peer: Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18 13:54:11.426 ThaliTest[347:403080] client: found peer: Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18 13:54:11.428 ThaliTest[347:403080] client: found peer: Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:54:41.220 ThaliTest[347:403080] client: lost peer: Apple-IpadAir2-1_PT1412.+KloFA==
2015-12-18 13:54:41.220 ThaliTest[347:403080] client session: onPeerLost: Apple-IpadAir2-1_PT1412.+KloFA==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT1412.+KloFA==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 13:54:41.381 ThaliTest[347:403080] multipeer session: restart
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-12-18 13:54:41.654 ThaliTest[347:403274] jxcore: stopBroadcasting
2015-12-18 13:54:41.654 ThaliTest[347:403274] THEMultipeerSession stopping peer
2015-12-18 13:54:41.654 ThaliTest[347:403274] multipeer session: stop timer
2015-12-18 13:54:41.655 ThaliTest[347:403274] server session: disconnect
2015-12-18 13:54:41.655 ThaliTest[347:403274] server session: stateChange:2->0 Apple-Iphone5s-1_PT4751
,2015-12-18 13:54:41.662 ThaliTest[347:403274] server session: disconnect
2015-12-18 13:54:41.663 ThaliTest[347:403274] server session: stateChange:2->0 Apple-IpadAir2-1_PT1412
,2015-12-18 13:54:41.671 ThaliTest[347:403274] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-18T12:54:41.687Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T12:54:41.689Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T12:54:41.690Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT1412.+KloFA==\",\"time\":4254,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5s-1_PT4751.qR8AbA==\",\"time\":4379,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone6-1_PT215.JwJUFw==\",\"time\":4467,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
