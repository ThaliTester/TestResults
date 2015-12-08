#### Test 52971095c1e9930_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52971095c1e9930/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/9FE531BB-099A-4474-9A8D-EF8A52B79AAC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9FE531BB-099A-4474-9A8D-EF8A52B79AAC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52971095c1e9930/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52971095c1e9930/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C3D3FC37-C84C-4B06-9177-5616F034D9AA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51299"
,(lldb)     command script import "/tmp/9FE531BB-099A-4474-9A8D-EF8A52B79AAC/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 17:45:35.706 ThaliTest[509:304254] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0517214C-A921-4BE7-8F4A-70BE09FC98AF/Library/Cookies/Cookies.binarycookies
,2015-12-08 17:45:36.124 ThaliTest[509:304254] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 17:45:36.126 ThaliTest[509:304254] Multi-tasking -> Device: YES, App: YES
,2015-12-08 17:45:36.136 ThaliTest[509:304254] Unlimited access to network resources
,2015-12-08 17:45:36.150 ThaliTest[509:304254] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 17:45:45.181 ThaliTest[509:304254] Resetting plugins due to page load.
,2015-12-08 17:45:48.990 ThaliTest[509:304254] Finished load of: file:///var/mobile/Containers/Bundle/Application/C3D3FC37-C84C-4B06-9177-5616F034D9AA/ThaliTest.app/www/index.html
,2015-12-08 17:45:49.212 ThaliTest[509:304254] JXcore Cordova plugin initializing
,2015-12-08 17:45:49.213 ThaliTest[509:304559] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT5978
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 52214
,2015-12-08 17:52:35.959 ThaliTest[509:304559] jxcore: startBroadcasting
,2015-12-08 17:52:35.980 ThaliTest[509:304559] server: starting Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:35.981 ThaliTest[509:304559] multipeer session: start timer: 0x18e20cc0
2015-12-08 17:52:35.982 ThaliTest[509:304559] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT5978
2015-12-08 17:52:35.985 ThaliTest[509:304559] jxcore: star,tBroadcasting: success
StartBroadcasting started ok
,2015-12-08T16:52:35.991Z SendDataTCPServer.js: TCP/IP server is bound to port: 52214
,2015-12-08 17:52:37.120 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08T16:52:37.129Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08T16:52:37.130Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08T16:52:37.132Z SendDataConnector.js: do connect now
2015-12-08 17:52:37.133 ThaliTest[509:304559] jxcore: connect Apple-Iphone5-1_PT5966.K,rGtFw==
2015-12-08 17:52:37.134 ThaliTest[509:304559] client session: connect
2015-12-08 17:52:37.135 ThaliTest[509:304559] client session: stateChange:0->1 Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:52:37.253 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1987.2bYzJA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-08 17:52:37.651 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6318.xt9ojg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:52:40.876 ThaliTest[509:304254] multipeer session: reset timer
2015-12-08 17:52:40.876 ThaliTest[509:304254] multipeer session: stop timer
,2015-12-08 17:52:40.877 ThaliTest[509:304254] multipeer session: start timer: 0x18e20cc0
,2015-12-08 17:52:40.877 ThaliTest[509:304254] server session: connect
,2015-12-08 17:52:40.878 ThaliTest[509:304254] server session: stateChange:0->1 Apple-IpadAir2-1_PT6318
2015-12-08 17:52:40.889 ThaliTest[509:304254] server: accepting invitation Apple-IpadAir2-1_PT6318
,2015-12-08 17:52:40.999 ThaliTest[509:305223] client session: connected
2015-12-08 17:52:40.999 ThaliTest[509:305223] client session: stateChange:1->2 Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:52:41.010 ThaliTest[509:305223] client session: fireConnectCallback: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:52:41.012 ThaliTest[509:305223] jxcore: connect: success
2015-12-08T16:52:41.014Z SendDataConnector.js: CLIENT connected to 5,2217, error: null
2015-12-08T16:52:41.014Z SendDataConnector.js: CLIENT starting client 
2015-12-08 17:52:41.020 ThaliTest[509:304254] client: relay established
2015-12-08 17:52:41.021 ThaliTest[509:304254] client: new accepted socket: 0x18c3b9f0
,2015-12-08T16:52:41.033Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:52:41.985Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-08T16:52:41.999Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T16:52:42.000Z SendDataConnector.js: got all data for this round
,2015-12-08T16:52:42.003Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:52:42.004Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-08 17:52:42.006 ThaliTest[509:304559] jxcore: disconnect
,2015-12-08 17:52:42.006 ThaliTest[509:304559] client session: disconnectFromPeer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:52:42.007 ThaliTest[509:304559] client session: disconnect
,2015-12-08 17:52:42.007 ThaliTest[509:304559] client session: stateChange:2->0 Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:52:42.025 ThaliTest[509:304559] jxcore: disconnect: success
2015-12-08T16:52:42.026Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5966.KrGtFw==
---- round done--------
device[2]: Apple-Iphone6-1_PT1987.2bY,zJA==
2015-12-08T16:52:42.030Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08T16:52:42.030Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08T16:52:42.030Z SendDataConnec,tor.js: do connect now
2015-12-08 17:52:42.031 ThaliTest[509:304559] jxcore: connect Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:42.033 ThaliTest[509:304559] client session: connect
2015-12-08 17:52:42.039 ThaliTest[509:304559] client session: stateChange:0->1 Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:44.484 ThaliTest[509:305221] server session: connected
2015-12-08 17:52:44.484 ThaliTest[509:305221] server session: stateChange:1->2 Apple-IpadAir2-1_PT6318
,2015-12-08T16:52:44.517Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08 17:52:44.519 ThaliTest[509:304254] server relay: connected (to port: 52214)
,2015-12-08T16:52:44.923Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-08T16:52:44.939Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-08T16:52:44.959Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-08T16:52:44.978Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-08T16:52:44.998Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-08T16:52:45.014Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:52:45.128 ThaliTest[509:305221] server session: not connected Apple-IpadAir2-1_PT6318
,2015-12-08 17:52:45.181 ThaliTest[509:305221] client session: connected
2015-12-08 17:52:45.181 ThaliTest[509:305221] client session: stateChange:1->2 Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:45.192 ThaliTest[509:305222] client session: fireConnectCallback: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:52:45.192 ThaliTest[509:305222] jxcore: connect: success
2015-12-08T16:52:45.194Z SendDataConnector.js: CLIENT connected to 5,2221, error: null
2015-12-08T16:52:45.194Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:52:45.199 ThaliTest[509:304254] client: relay established
2015-12-08 17:52:45.199 ThaliTest[509:304254] client: new accepted socket: 0x18c39ff0
,2015-12-08T16:52:45.212Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:52:45.546Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-08T16:52:45.586Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-08T16:52:45.648Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T16:52:45.649Z SendDataConnector.js: got all data for this round
,2015-12-08T16:52:45.649Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:52:45.649Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:52:45.650 ThaliTest[509:304559] jxcore: disconnect
2015-12-08 17:52:45.650 ThaliTest[509:304559] client session: disconnectFromPeer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:52:45.650 ThaliTest[509:304559] client session: disconnect
2015-12-08 17:52:45.650 ThaliTest[509:304559] client session: stateChange:2->0 Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:45.657 ThaliTest[509:304559] jxcore: disconnect: success
2015-12-08T16:52:45.657Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1987.2bYzJA==
---- round done--------
device[3]: Apple-IpadAir2-1_PT6318.xt,9ojg==
2015-12-08T16:52:45.658Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08T16:52:45.658Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08T16:52:45.658Z SendDataCon,nector.js: do connect now
2015-12-08 17:52:45.659 ThaliTest[509:304559] jxcore: connect Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:52:45.659 ThaliTest[509:304559] client session: connect
,2015-12-08 17:52:45.659 ThaliTest[509:304559] client session: stateChange:0->1 Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:52:45.704 ThaliTest[509:304254] multipeer session: reset timer
2015-12-08 17:52:45.705 ThaliTest[509:304254] multipeer session: stop timer
2015-12-08 17:52:45.705 ThaliTest[509:304254] multipeer session: start timer: 0x18e20cc0
2015-12-08 17:52:45.705 ThaliTest[509:304254] server session: connect
,2015-12-08 17:52:45.705 ThaliTest[509:304254] server session: stateChange:0->1 Apple-Iphone6-1_PT1987
2015-12-08 17:52:45.712 ThaliTest[509:304254] server: accepting invitation Apple-Iphone6-1_PT1987
,2015-12-08 17:52:46.258 ThaliTest[509:304254] multipeer session: reset timer
2015-12-08 17:52:46.259 ThaliTest[509:304254] multipeer session: stop timer
2015-12-08 17:52:46.259 ThaliTest[509:304254] multipeer session: start timer: 0x18e20cc0
2015-12-08 ,17:52:46.259 ThaliTest[509:304254] server session: connect
2015-12-08 17:52:46.259 ThaliTest[509:304254] server session: stateChange:0->1 Apple-Iphone5-1_PT5966
,2015-12-08 17:52:46.265 ThaliTest[509:304254] server: accepting invitation Apple-Iphone5-1_PT5966
,2015-12-08 17:52:48.331 ThaliTest[509:305274] client session: connected
2015-12-08 17:52:48.331 ThaliTest[509:305274] client session: stateChange:1->2 Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:52:48.358 ThaliTest[509:305221] client session: fireConnectCallback: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:52:48.359 ThaliTest[509:305221] jxcore: connect: success
2015-12-08T16:52:48.360Z SendDataConnector.js: CLIENT connected to ,52224, error: null
2015-12-08T16:52:48.360Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:52:48.366 ThaliTest[509:304254] client: relay established
2015-12-08 17:52:48.366 ThaliTest[509:304254] client: new accepted socket: 0x18c33750
,2015-12-08T16:52:48.380Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08 17:52:48.383 ThaliTest[509:305273] server session: connected
,2015-12-08 17:52:48.384 ThaliTest[509:305273] server session: stateChange:1->2 Apple-Iphone6-1_PT1987
,2015-12-08 17:52:48.393 ThaliTest[509:304254] server relay: connected (to port: 52214)
,2015-12-08T16:52:48.666Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:52:48.699Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-08T16:52:48.885Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T16:52:48.886Z SendDataConnector.js: got all data for this round
,2015-12-08T16:52:48.886Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:52:48.887Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:52:48.888 ThaliTest[509:304559] jxcore: disconnect
,2015-12-08 17:52:48.889 ThaliTest[509:304559] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:52:48.890 ThaliTest[509:304559] client session: disconnect
,2015-12-08 17:52:48.891 ThaliTest[509:304559] client session: stateChange:2->0 Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:52:48.980 ThaliTest[509:304559] jxcore: disconnect: success
,2015-12-08T16:52:48.980Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6318.xt9ojg==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT5978","time":13041,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT5966.KrGtFw==","time":4872,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_,PT1987.2bYzJA==","time":3619,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT6318.xt9ojg==","time":3228,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":1000,00}]}
,sendList : 100% : 4872 ms, 99% : 4872 ms, 95 : 4872 ms, 90% : 4872 ms.
,Result count 3, range 3228 ms to  4872 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-08T16:52:48.992Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:52:48.992Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08T16:52:49.005Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-08T16:52:49.113Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:52:49.191 ThaliTest[509:305274] server session: connected
2015-12-08 17:52:49.191 ThaliTest[509:305274] server session: stateChange:1->2 Apple-Iphone5-1_PT5966
,2015-12-08 17:52:49.194 ThaliTest[509:304254] server relay: connected (to port: 52214)
,2015-12-08T16:52:49.208Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08 17:52:49.229 ThaliTest[509:305273] server session: not connected Apple-Iphone6-1_PT1987
,2015-12-08T16:52:49.781Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-08T16:52:49.800Z SendDataTCPServer.js: TCP/IP server has received 38568 bytes of data
,2015-12-08T16:52:49.818Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-08T16:52:49.844Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-08T16:52:50.434Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-08T16:52:50.449Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:52:50.831 ThaliTest[509:305274] server session: not connected Apple-Iphone5-1_PT5966
,2015-12-08 17:52:52.984 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8010.swwphA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:52:56.879 ThaliTest[509:304254] client: lost peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:52:56.880 ThaliTest[509:304254] client session: onPeerLost: Apple-Iphone5-1_PT8010.swwphA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT8010.swwphA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-08 17:53:16.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 17:53:16.328 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:53:16.333 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
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
,2015-12-08 17:53:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 17:53:46.331 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:53:47.283 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:53:48.944 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,2015-12-08 17:54:16.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 17:54:16.331 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:54:17.212 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:54:17.212 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:54:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 17:54:46.316 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:54:46.329 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-08 17:55:16.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 17:55:16.320 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:55:16.332 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:55:21.671 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:55:24.592 ThaliTest[509:304254] client: lost peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:55:24.592 ThaliTest[509:304254] client session: onPeerLost: Apple-Iphone5-1_PT5966.KrGtFw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:55:27.137 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":true}]
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
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:55:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 17:55:46.323 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:55:46.340 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:55:46.340 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
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
,2015-12-08 17:56:16.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 17:56:16.314 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:56:16.336 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:56:16.342 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:56:39.726 ThaliTest[509:304254] client: lost peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:56:39.727 ThaliTest[509:304254] client session: onPeerLost: Apple-Iphone5-1_PT5966.KrGtFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:56:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 17:56:47.120 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:56:47.121 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5,-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":true}]
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
,2015-12-08 17:57:16.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 17:57:16.314 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:57:16.314 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:57:20.848 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:57:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 17:57:46.302 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:57:46.311 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:57:46.314 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,2015-12-08 17:58:16.260 ThaliTest[509:304254] multipeer session: restart
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:58:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 17:58:46.316 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:58:46.319 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:58:46.794 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,2015-12-08 17:59:16.260 ThaliTest[509:304254] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 17:59:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 17:59:46.312 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:59:46.319 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:59:46.492 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,2015-12-08 18:00:16.260 ThaliTest[509:304254] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-08 18:00:46.260 ThaliTest[509:304254] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:00:47.189 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:00:47.189 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:00:47.190 ThaliTest[509:304254] client: fou,nd peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,2015-12-08 18:01:16.260 ThaliTest[509:304254] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 18:01:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:01:46.312 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:01:46.314 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:01:46.782 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,2015-12-08 18:02:16.260 ThaliTest[509:304254] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 18:02:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:02:46.313 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:02:46.313 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:02:46.468 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,2015-12-08 18:03:16.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:03:16.312 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:03:16.318 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:03:16.319 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 18:03:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:03:47.246 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:03:47.246 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:03:47.247 ThaliTest[509:304254] client: fou,nd peer: Apple-Iphone5-1_PT5966.KrGtFw==
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
,2015-12-08 18:04:16.260 ThaliTest[509:304254] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 18:04:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:04:47.150 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:04:47.152 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:04:47.153 ThaliTest[509:304254] client: fou,nd peer: Apple-Iphone5-1_PT5966.KrGtFw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,2015-12-08 18:05:16.260 ThaliTest[509:304254] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 18:05:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:05:46.308 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:05:46.309 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:05:46.459 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,2015-12-08 18:06:16.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:06:17.303 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:06:17.304 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:06:17.304 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 18:06:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:06:47.119 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:06:47.119 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:06:47.119 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,2015-12-08 18:07:16.260 ThaliTest[509:304254] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 18:07:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:07:46.315 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:07:46.316 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:07:46.548 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,2015-12-08 18:08:16.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:08:17.271 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:08:17.271 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:08:17.272 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 18:08:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:08:47.234 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:08:47.237 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:08:47.237 ThaliTest[509:304254] client: foun,d peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,2015-12-08 18:09:16.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:09:16.315 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:09:16.315 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:09:16.636 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 18:09:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:09:46.316 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:09:46.316 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:09:46.533 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,2015-12-08 18:10:16.260 ThaliTest[509:304254] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 18:10:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:10:47.186 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:10:47.186 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:10:47.187 ThaliTest[509:304254] client: foun,d peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,2015-12-08 18:11:16.260 ThaliTest[509:304254] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 18:11:46.260 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:11:46.305 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:11:46.313 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:11:46.314 ThaliTest[509:304254] client: fou,nd peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,2015-12-08 18:12:16.219 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:12:16.269 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:12:16.270 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:12:16.272 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 18:12:46.219 ThaliTest[509:304254] multipeer session: restart
,2015-12-08 18:12:46.274 ThaliTest[509:304254] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:12:46.283 ThaliTest[509:304254] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:12:46.285 ThaliTest[509:304254] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
