#### Test 539786637913587_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/539786637913587/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/0DB595CC-6A3A-462E-AA8B-FEAB5919CD9C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0DB595CC-6A3A-462E-AA8B-FEAB5919CD9C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/539786637913587/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/539786637913587/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EC95193E-3CAF-4A80-9ECE-68DF9C0EAD54/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59919"
,(lldb)     command script import "/tmp/0DB595CC-6A3A-462E-AA8B-FEAB5919CD9C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 13:45:20.694 ThaliTest[423:339132] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/390ED4E2-A914-4847-81DC-DF201B3EF05C/Library/Cookies/Cookies.binarycookies
,2015-12-18 13:45:21.155 ThaliTest[423:339132] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 13:45:21.157 ThaliTest[423:339132] Multi-tasking -> Device: YES, App: YES
,2015-12-18 13:45:21.167 ThaliTest[423:339132] Unlimited access to network resources
,2015-12-18 13:45:21.186 ThaliTest[423:339132] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 13:45:30.226 ThaliTest[423:339132] Resetting plugins due to page load.
,2015-12-18 13:45:34.185 ThaliTest[423:339132] Finished load of: file:///var/mobile/Containers/Bundle/Application/EC95193E-3CAF-4A80-9ECE-68DF9C0EAD54/ThaliTest.app/www/index.html
,2015-12-18 13:45:34.403 ThaliTest[423:339132] JXcore Cordova plugin initializing
,2015-12-18 13:45:34.405 ThaliTest[423:339336] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
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
,my name is : Apple-Iphone5s-1_PT4751
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
,serverPort is 50895
,2015-12-18 13:53:32.198 ThaliTest[423:339336] jxcore: startBroadcasting
,2015-12-18 13:53:32.224 ThaliTest[423:339336] server: starting Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18 13:53:32.226 ThaliTest[423:339336] multipeer session: start timer: 0x186ccca0
2015-12-18 13:53:32.226 ThaliTest[423:339336] THEMultipeerSession ini,tialized peer Apple-Iphone5s-1_PT4751
2015-12-18 13:53:32.227 ThaliTest[423:339336] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-18T12:53:32.231Z SendDataTCPServer.js: TCP/IP server is bound to port: 50895
,2015-12-18 13:53:33.300 ThaliTest[423:339132] client: found peer: Apple-Iphone6-1_PT215.JwJUFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT215.JwJUFw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[1]: Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18T12:53:33.308Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18T12:53:33.312Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18T12:53:33.313Z SendDataConnector.js: d,o connect now
2015-12-18 13:53:33.314 ThaliTest[423:339336] jxcore: connect Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18 13:53:33.314 ThaliTest[423:339336] client session: connect
2015-12-18 13:53:33.315 ThaliTest[423:339336] client session: stateChange:0-,>1 Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:53:33.517 ThaliTest[423:339132] client: found peer: Apple-IpadAir2-1_PT1412.+KloFA==
2015-12-18 13:53:33.518 ThaliTest[423:339132] client: found peer: Apple-Iphone5-1_PT724.734x4g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2,-1_PT1412.+KloFA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT724.734x4g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 13:53:33.998 ThaliTest[423:339132] multipeer session: reset timer
2015-12-18 13:53:33.998 ThaliTest[423:339132] multipeer session: stop timer
2015-12-18 13:53:33.999 ThaliTest[423:339132] multipeer session: start timer: 0x186ccca0
2015-12-18 ,13:53:33.999 ThaliTest[423:339132] server session: connect
2015-12-18 13:53:34.000 ThaliTest[423:339132] server session: stateChange:0->1 Apple-Iphone5-1_PT724
,2015-12-18 13:53:34.013 ThaliTest[423:339132] server: accepting invitation Apple-Iphone5-1_PT724
,2015-12-18 13:53:34.075 ThaliTest[423:339132] multipeer session: reset timer
2015-12-18 13:53:34.076 ThaliTest[423:339132] multipeer session: stop timer
2015-12-18 13:53:34.076 ThaliTest[423:339132] multipeer session: start timer: 0x186ccca0
2015-12-18 ,13:53:34.077 ThaliTest[423:339132] server session: connect
2015-12-18 13:53:34.077 ThaliTest[423:339132] server session: stateChange:0->1 Apple-IpadAir2-1_PT1412
,2015-12-18 13:53:34.101 ThaliTest[423:339132] server: accepting invitation Apple-IpadAir2-1_PT1412
,2015-12-18 13:53:36.614 ThaliTest[423:340275] client session: connected
2015-12-18 13:53:36.615 ThaliTest[423:340275] client session: stateChange:1->2 Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:53:36.637 ThaliTest[423:340275] client session: fireConnectCallback: Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18 13:53:36.637 ThaliTest[423:340275] jxcore: connect: success
2015-12-18T12:53:36.639Z SendDataConnector.js: CLIENT connected to 50,898, error: null
2015-12-18T12:53:36.640Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 13:53:36.644 ThaliTest[423:339132] client: relay established
2015-12-18 13:53:36.645 ThaliTest[423:339132] client: new accepted socket: 0x18794230
,2015-12-18T12:53:36.660Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T12:53:36.992Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T12:53:37.006Z SendDataConnector.js: CLIENT is data received : 40000
2015-12-18 13:53:37.007 ThaliTest[423:340275] server session: connected
2015-12-18 13:53:37.007 ThaliTest[423:340275] server session: stateChange:1->2 Apple-Iphone5-1_PT724
,2015-12-18T12:53:37.019Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18T12:53:37.031Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-18 13:53:37.036 ThaliTest[423:339132] server relay: connected (to port: 50895)
,2015-12-18T12:53:37.045Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T12:53:37.046Z SendDataConnector.js: got all data for this round
2015-12-18T12:53:37.048Z SendDataConnector.js: CLIENT Stop now
2015-12-18T12:53:37.049Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-18 13:53:37.050 ThaliTest[423:339336] jxcore: disconnect
2015-12-18 13:53:37.050 ThaliTest[423:339336] client session: disconnectFromPeer: Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18 13:53:37.050 ThaliTest[423:,339336] client session: disconnect
2015-12-18 13:53:37.050 ThaliTest[423:339336] client session: stateChange:2->0 Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:53:37.063 ThaliTest[423:339336] jxcore: disconnect: success
,2015-12-18T12:53:37.065Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT215.JwJUFw==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18T12:53:37.079Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18T12:53:37.080Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18T12:53:37.081Z SendDataConnector.js: do connect now
,2015-12-18 13:53:37.084 ThaliTest[423:340284] server session: connected
2015-12-18 13:53:37.085 ThaliTest[423:340284] server session: stateChange:1->2 Apple-IpadAir2-1_PT1412
,2015-12-18 13:53:37.088 ThaliTest[423:339336] jxcore: connect Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:53:37.088 ThaliTest[423:339336] client session: connect
,2015-12-18 13:53:37.090 ThaliTest[423:339336] client session: stateChange:0->1 Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18T12:53:37.096Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18 13:53:37.108 ThaliTest[423:339132] server relay: connected (to port: 50895)
,2015-12-18T12:53:37.115Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T12:53:37.470Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-18T12:53:37.487Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-18T12:53:37.507Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-18T12:53:37.525Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-18T12:53:37.562Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
2015-12-18T12:53:37.564Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-18T12:53:37.588Z SendDataTCPServer.js: TCP/IP server has received 33478 bytes of data
,2015-12-18T12:53:37.647Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18T12:53:37.667Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-18T12:53:37.682Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 13:53:37.729 ThaliTest[423:340284] server session: not connected Apple-IpadAir2-1_PT1412
,2015-12-18 13:53:37.746 ThaliTest[423:340284] server session: not connected Apple-Iphone5-1_PT724
,2015-12-18 13:53:40.632 ThaliTest[423:340284] client session: connected
2015-12-18 13:53:40.632 ThaliTest[423:340284] client session: stateChange:1->2 Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:53:40.678 ThaliTest[423:340275] client session: fireConnectCallback: Apple-IpadAir2-1_PT1412.+KloFA==
2015-12-18 13:53:40.678 ThaliTest[423:340275] jxcore: connect: success
2015-12-18T12:53:40.679Z SendDataConnector.js: CLIENT connected to 50903, error: null
2015-12-18T12:53:40.680Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 13:53:40.686 ThaliTest[423:339132] client: relay established
2015-12-18 13:53:40.686 ThaliTest[423:339132] client: new accepted socket: 0x186dc830
,2015-12-18T12:53:40.697Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T12:53:41.171Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-18T12:53:41.209Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T12:53:41.209Z SendDataConnector.js: got all data for this round
,2015-12-18T12:53:41.210Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T12:53:41.211Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 13:53:41.212 ThaliTest[423:339336] jxcore: disconnect
,2015-12-18 13:53:41.213 ThaliTest[423:339336] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:53:41.214 ThaliTest[423:339336] client session: disconnect
,2015-12-18 13:53:41.215 ThaliTest[423:339336] client session: stateChange:2->0 Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:53:41.284 ThaliTest[423:339336] jxcore: disconnect: success
,2015-12-18T12:53:41.285Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1412.+KloFA==
---- round done--------
,device[3]: Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T12:53:41.286Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T12:53:41.287Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T12:53:41.288Z SendDataConnector.js: do connect now
,2015-12-18 13:53:41.288 ThaliTest[423:339336] jxcore: connect Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 13:53:41.290 ThaliTest[423:339336] client session: connect
,2015-12-18 13:53:41.290 ThaliTest[423:339336] client session: stateChange:0->1 Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 13:53:44.431 ThaliTest[423:340276] client session: connected
2015-12-18 13:53:44.431 ThaliTest[423:340276] client session: stateChange:1->2 Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 13:53:44.447 ThaliTest[423:340274] client session: fireConnectCallback: Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 13:53:44.449 ThaliTest[423:340274] jxcore: connect: success
2015-12-18T12:53:44.451Z SendDataConnector.js: CLIENT connected to 50906, error: null
2015-12-18T12:53:44.456Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 13:53:44.460 ThaliTest[423:339132] client: relay established
2015-12-18 13:53:44.462 ThaliTest[423:339132] client: new accepted socket: 0x18794630
,2015-12-18T12:53:44.475Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T12:53:44.830Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T12:53:44.878Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T12:53:44.878Z SendDataConnector.js: got all data for this round
,2015-12-18T12:53:44.879Z SendDataConnector.js: CLIENT Stop now
2015-12-18T12:53:44.879Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-18 13:53:44.880 ThaliTest[423:339336] jxcore: disconnect
,2015-12-18 13:53:44.880 ThaliTest[423:339336] client session: disconnectFromPeer: Apple-Iphone5-1_PT724.734x4g==
2015-12-18 13:53:44.880 ThaliTest[423:339336] client session: disconnect
2015-12-18 13:53:44.880 ThaliTest[423:339336] client session: stateChange:2->0 Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 13:53:44.886 ThaliTest[423:339336] jxcore: disconnect: success
,2015-12-18T12:53:44.888Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT724.734x4g==
,---- round done--------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT4751","time":12710,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT215.JwJUFw==","time":3734,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT1412.+KloFA==","time":4130,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT724.734x4g==","time":3591,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000,}]}
sendList : 100% : 4130 ms, 99% : 4130 ms, 95 : 4130 ms, 90% : 4130 ms.
Result count 3, range 3591 ms to  4130 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-18T12:53:44.894Z SendDataConnector.js: CLIEN,T Stop now
2015-12-18T12:53:44.894Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 13:54:04.078 ThaliTest[423:339132] multipeer session: restart
,2015-12-18 13:54:31.245 ThaliTest[423:339132] multipeer session: reset timer
2015-12-18 13:54:31.246 ThaliTest[423:339132] multipeer session: stop timer
2015-12-18 13:54:31.246 ThaliTest[423:339132] multipeer session: start timer: 0x186ccca0
2015-12-18 ,13:54:31.247 ThaliTest[423:339132] server session: connect
2015-12-18 13:54:31.247 ThaliTest[423:339132] server session: stateChange:0->1 Apple-Iphone6-1_PT215
,2015-12-18 13:54:31.259 ThaliTest[423:339132] server: accepting invitation Apple-Iphone6-1_PT215
,2015-12-18 13:54:34.218 ThaliTest[423:340646] server session: connected
2015-12-18 13:54:34.218 ThaliTest[423:340646] server session: stateChange:1->2 Apple-Iphone6-1_PT215
,2015-12-18 13:54:34.236 ThaliTest[423:339132] server relay: connected (to port: 50895)
,2015-12-18T12:54:34.248Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T12:54:34.615Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-18T12:54:34.633Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-18T12:54:34.653Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-18T12:54:34.672Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-18T12:54:34.687Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-18T12:54:34.703Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-18T12:54:34.718Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 13:54:34.802 ThaliTest[423:340699] server session: not connected Apple-Iphone6-1_PT215
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
,stop current!
,testSendData stopped
,2015-12-18 13:54:53.509 ThaliTest[423:339336] jxcore: stopBroadcasting
2015-12-18 13:54:53.510 ThaliTest[423:339336] THEMultipeerSession stopping peer
2015-12-18 13:54:53.511 ThaliTest[423:339336] multipeer session: stop timer
2015-12-18 13:54:53.511 Th,aliTest[423:339336] server session: disconnect
2015-12-18 13:54:53.512 ThaliTest[423:339336] server session: stateChange:2->0 Apple-Iphone6-1_PT215
2015-12-18 13:54:53.520 ThaliTest[423:339336] server session: disconnect
2015-12-18 13:54:53.521 ThaliTes,t[423:339336] server session: stateChange:2->0 Apple-Iphone5-1_PT724
,2015-12-18 13:54:53.534 ThaliTest[423:339336] server session: disconnect
2015-12-18 13:54:53.535 ThaliTest[423:339336] server session: stateChange:2->0 Apple-IpadAir2-1_PT1412
,2015-12-18 13:54:53.654 ThaliTest[423:339336] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-18T12:54:53.674Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T12:54:53.676Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T12:54:53.678Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T12:54:53.679Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT724.734x4g==\",\"time\":3591,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{,\"name\":\"Apple-Iphone6-1_PT215.JwJUFw==\",\"time\":3734,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-IpadAir2-1_PT1412.+KloFA==\",\"time\":4130,\"result\":\"OK\",\"connections\":1,\,"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received

```
