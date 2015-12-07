#### Test 519863404492c11_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/519863404492c11/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/DEFF8111-DB95-4277-B488-8316965B39EF/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/DEFF8111-DB95-4277-B488-8316965B39EF/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/519863404492c11/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/519863404492c11/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/39D28375-77B5-48B8-B979-504EC0F9F675/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49584"
,(lldb)     command script import "/tmp/DEFF8111-DB95-4277-B488-8316965B39EF/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 07:45:55.233 ThaliTest[327:124966] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DF1170B7-6B8D-4A92-8C4C-0A1954400188/Library/Cookies/Cookies.binarycookies
,2015-12-07 07:45:55.367 ThaliTest[327:124966] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 07:45:55.369 ThaliTest[327:124966] Multi-tasking -> Device: YES, App: YES
,2015-12-07 07:45:55.375 ThaliTest[327:124966] Unlimited access to network resources
,2015-12-07 07:45:55.390 ThaliTest[327:124966] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 07:46:06.514 ThaliTest[327:124966] Resetting plugins due to page load.
,2015-12-07 07:46:10.160 ThaliTest[327:124966] Finished load of: file:///var/mobile/Containers/Bundle/Application/39D28375-77B5-48B8-B979-504EC0F9F675/ThaliTest.app/www/index.html
,2015-12-07 07:46:10.375 ThaliTest[327:124966] JXcore Cordova plugin initializing
,2015-12-07 07:46:10.377 ThaliTest[327:125159] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,my name is : Apple-Iphone5-1_PT1974
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 50611
,2015-12-07 07:54:48.256 ThaliTest[327:125159] jxcore: startBroadcasting
,2015-12-07 07:54:48.275 ThaliTest[327:125159] server: starting Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:54:48.277 ThaliTest[327:125159] multipeer session: start timer: 0x1cf62820
2015-12-07 07:54:48.278 ThaliTest[327:125159] THEMultipeerSession initialized peer Apple-Iphone5-1_PT1974
2015-12-07 07:54:48.278 ThaliTest[327:125159] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-07T06:54:48.281Z SendDataTCPServer.js: TCP/IP server is bound to port: 50611
,2015-12-07 07:54:48.847 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7482.CDxPNA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07T06:54:48.854Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07T06:54:48.854Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7482.CDxPNA==
20,15-12-07T06:54:48.855Z SendDataConnector.js: do connect now
2015-12-07 07:54:48.855 ThaliTest[327:125159] jxcore: connect Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:54:48.856 ThaliTest[327:125159] client session: connect
2015-12-07 07:54:48.857 ThaliTest[327:125159] client session: stateChange:0->1 Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:54:49.013 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7843.gS16eg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-07 07:54:53.120 ThaliTest[327:126456] client session: connected
2015-12-07 07:54:53.120 ThaliTest[327:126456] client session: stateChange:1->2 Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:54:53.156 ThaliTest[327:126455] client session: fireConnectCallback: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:54:53.156 ThaliTest[327:126455] jxcore: connect: success
2015-12-07T06:54:53.157Z SendDataConnector.js: CLIENT connected to 50614, error: null
,2015-12-07T06:54:53.159Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 07:54:53.166 ThaliTest[327:124966] client: relay established
2015-12-07 07:54:53.166 ThaliTest[327:124966] client: new accepted socket: 0x1cf71990
2015-12-07 07:54:53.169 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07T06:54:53.171Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT12.Gapeow==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-07T06:54:54.577Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-07T06:54:54.590Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T06:54:54.591Z SendDataConnector.js: got all data for this round
,2015-12-07T06:54:54.594Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T06:54:54.594Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:54:54.595 ThaliTest[327:125159] jxcore: disconnect
2015-12-07 07:54:54.596 ThaliTest[327:125159] client session: disconnectFromPeer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:54:54.596 ThaliTest[327:125159] client session: disconnect
2015-12-07 07:54:54.596 ThaliTest[327:125159] client session: stateChange:2->0 Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:54:54.608 ThaliTest[327:125159] jxcore: disconnect: success
2015-12-07T06:54:54.609Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7482.CDxPNA==
---- round done--------
device[2]: Apple-Iphone5s-1_PT7843.gS,16eg==
2015-12-07T06:54:54.612Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07T06:54:54.612Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07T06:54:54.613Z SendDataConnector.js: do connect now
,2015-12-07 07:54:54.613 ThaliTest[327:125159] jxcore: connect Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:54:54.621 ThaliTest[327:125159] client session: connect
,2015-12-07 07:54:54.630 ThaliTest[327:125159] client session: stateChange:0->1 Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:54:54.649 ThaliTest[327:124966] multipeer session: reset timer
,2015-12-07 07:54:54.649 ThaliTest[327:124966] multipeer session: stop timer
,2015-12-07 07:54:54.650 ThaliTest[327:124966] multipeer session: start timer: 0x1cf62820
,2015-12-07 07:54:54.651 ThaliTest[327:124966] server session: connect
,2015-12-07 07:54:54.653 ThaliTest[327:124966] server session: stateChange:0->1 Apple-Iphone6-1_PT7482
,2015-12-07 07:54:54.666 ThaliTest[327:124966] server: accepting invitation Apple-Iphone6-1_PT7482
,2015-12-07 07:54:57.763 ThaliTest[327:126456] server session: connected
2015-12-07 07:54:57.764 ThaliTest[327:126456] server session: stateChange:1->2 Apple-Iphone6-1_PT7482
,2015-12-07T06:54:57.805Z SendDataTCPServer.js: TCP/IP server connected
2015-12-07 07:54:57.809 ThaliTest[327:124966] server relay: connected (to port: 50611)
,2015-12-07 07:54:57.819 ThaliTest[327:124966] multipeer session: reset timer
2015-12-07 07:54:57.819 ThaliTest[327:124966] multipeer session: stop timer
2015-12-07 07:54:57.819 ThaliTest[327:124966] multipeer session: start timer: 0x1cf62820
2015-12-07 ,07:54:57.819 ThaliTest[327:124966] server session: connect
2015-12-07 07:54:57.819 ThaliTest[327:124966] server session: stateChange:0->1 Apple-Iphone5s-1_PT7843
,2015-12-07 07:54:57.829 ThaliTest[327:124966] server: accepting invitation Apple-Iphone5s-1_PT7843
,2015-12-07T06:54:58.243Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-07T06:54:58.264Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-07T06:54:58.283Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 07:54:58.334 ThaliTest[327:126456] server session: not connected Apple-Iphone6-1_PT7482
,2015-12-07 07:55:00.026 ThaliTest[327:126526] client session: connected
2015-12-07 07:55:00.027 ThaliTest[327:126526] client session: stateChange:1->2 Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:55:00.028 ThaliTest[327:126526] client session: fireConnectCallback: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:55:00.029 ThaliTest[327:126526] jxcore: connect: success
,2015-12-07T06:55:00.034Z SendDataConnector.js: CLIENT connected to 50618, error: null
2015-12-07T06:55:00.034Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 07:55:00.037 ThaliTest[327:124966] client: relay established
,2015-12-07 07:55:00.040 ThaliTest[327:124966] client: new accepted socket: 0x1cf5fff0
,2015-12-07T06:55:00.050Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T06:55:00.625Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-07T06:55:00.648Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-07T06:55:00.858Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-07T06:55:00.872Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-07T06:55:00.873Z SendDataConnector.js: got all data for this round
2015-12-07T06:55:00.873Z SendDataConnector.js: CLIENT Stop now
2015-12-07T06:55:00.874Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:55:00.874 ThaliTest[327:125159] jxcore: disconnect
,2015-12-07 07:55:00.875 ThaliTest[327:125159] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:55:00.876 ThaliTest[327:125159] client session: disconnect
2015-12-07 07:55:00.877 ThaliTest[327:125159] client session: stateChange:2->0 Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:55:00.893 ThaliTest[327:125159] jxcore: disconnect: success
2015-12-07T06:55:00.894Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7843.gS16eg==
---- round done--------
device[3]: Apple-IpadAir2-1_PT12.Gap,eow==
2015-12-07T06:55:00.896Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07T06:55:00.896Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07T06:55:00.896Z SendDataConnector.js: do connect now
,2015-12-07 07:55:00.896 ThaliTest[327:125159] jxcore: connect Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:55:00.901 ThaliTest[327:125159] client session: connect
2015-12-07 07:55:00.902 ThaliTest[327:125159] client session: stateChange:0->1 Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:55:00.944 ThaliTest[327:126525] server session: connected
,2015-12-07 07:55:00.945 ThaliTest[327:126525] server session: stateChange:1->2 Apple-Iphone5s-1_PT7843
,2015-12-07 07:55:00.954 ThaliTest[327:124966] server relay: connected (to port: 50611)
,2015-12-07T06:55:00.980Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07 07:55:01.387 ThaliTest[327:124966] multipeer session: reset timer
2015-12-07 07:55:01.388 ThaliTest[327:124966] multipeer session: stop timer
2015-12-07 07:55:01.389 ThaliTest[327:124966] multipeer session: start timer: 0x1cf62820
2015-12-07 ,07:55:01.391 ThaliTest[327:124966] server session: connect
2015-12-07T06:55:01.393Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
2015-12-07 07:55:01.393 ThaliTest[327:124966] server session: stateChange:0->1 Apple-IpadAir2-1_PT12,
2015-12-07 07:55:01.408 ThaliTest[327:124966] server: accepting invitation Apple-IpadAir2-1_PT12
2015-12-07T06:55:01.414Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-07T06:55:01.429Z SendDataTCPServer.js: TCP/IP server has received 51424 bytes of data
,2015-12-07T06:55:01.446Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-07T06:55:01.542Z SendDataTCPServer.js: TCP/IP server has received 84558 bytes of data
,2015-12-07T06:55:01.556Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 07:55:01.639 ThaliTest[327:126569] server session: not connected Apple-Iphone5s-1_PT7843
,2015-12-07 07:55:04.672 ThaliTest[327:126526] client session: connected
,2015-12-07 07:55:04.672 ThaliTest[327:126526] client session: stateChange:1->2 Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:55:04.686 ThaliTest[327:126526] client session: fireConnectCallback: Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:55:04.687 ThaliTest[327:126526] jxcore: connect: success
,2015-12-07T06:55:04.688Z SendDataConnector.js: CLIENT connected to 50622, error: null
,2015-12-07T06:55:04.688Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 07:55:04.691 ThaliTest[327:124966] client: relay established
,2015-12-07 07:55:04.693 ThaliTest[327:124966] client: new accepted socket: 0x1ccc95c0
,2015-12-07 07:55:04.701 ThaliTest[327:126526] server session: connected
,2015-12-07 07:55:04.701 ThaliTest[327:126526] server session: stateChange:1->2 Apple-IpadAir2-1_PT12
,2015-12-07T06:55:04.702Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07 07:55:04.718 ThaliTest[327:124966] server relay: connected (to port: 50611)
,2015-12-07T06:55:05.277Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T06:55:05.290Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-07T06:55:05.291Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07T06:55:05.311Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-07T06:55:05.333Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-07 07:55:05.348 ThaliTest[327:126456] server session: not connected Apple-IpadAir2-1_PT12
,2015-12-07T06:55:05.364Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-07T06:55:05.579Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T06:55:05.580Z SendDataConnector.js: got all data for this round
,2015-12-07T06:55:05.581Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T06:55:05.581Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:55:05.583 ThaliTest[327:125159] jxcore: disconnect
2015-12-07 07:55:05.583 ThaliTest[327:125159] client session: disconnectFromPeer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:55:05.584 ThaliTest[327:125159] client session: disconnect
2015-12-07 07:55:05.584 ThaliTest[327:125159] client session: stateChange:2->0 Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:55:05.595 ThaliTest[327:125159] jxcore: disconnect: success
2015-12-07T06:55:05.595Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT12.Gapeow==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone5-1_PT1974","time":17353,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7482.CDxPNA==","time":5738,"result":"OK","connections":1,"doneRo,unds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7843.gS16eg==","time":6261,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT12.Gapeow==","time":4684,"result":,"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 6261 ms, 99% : 6261 ms, 95 : 6261 ms, 90% : 6261 ms.
Result count 3, range 4684 ms to  6261 ms.
sendList failed peers count : 0 [0 %]
sendList never trie,d peers count : 0 [0 %]
2015-12-07T06:55:05.603Z SendDataConnector.js: CLIENT Stop now
2015-12-07T06:55:05.603Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:55:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 07:55:31.433 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:55:31.434 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:55:47.224 ThaliTest[327:124966] client: lost peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:55:47.225 ThaliTest[327:124966] client session: onPeerLost: Apple-Iphone5s-1_PT7843.gS16eg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7843.gS16eg==","peerName":"(null)","peerAvailable":false}]
,2015-12-07 07:55:55.632 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7843.gS16eg==","peerName":"(null)","peerAvailable":true}]
,2015-12-07 07:56:01.290 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:56:01.392 ThaliTest[327:124966] multipeer session: restart
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 07:56:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 07:56:31.427 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:56:31.427 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:56:31.428 ThaliTest[327:124966] client: found, peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 07:57:01.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 07:57:01.429 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:57:01.429 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:57:01.430 ThaliTest[327:124966] client: foun,d peer: Apple-Iphone6-1_PT7482.CDxPNA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 07:57:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 07:57:31.426 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:57:31.427 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:57:31.427 ThaliTest[327:124966] client: found, peer: Apple-Iphone5s-1_PT7843.gS16eg==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 07:58:01.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 07:58:01.428 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:58:01.428 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:58:01.429 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 07:58:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 07:58:31.430 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:58:31.430 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 07:58:31.432 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 07:59:01.392 ThaliTest[327:124966] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 07:59:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 07:59:31.428 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:59:31.428 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:59:31.428 ThaliTest[327:124966] client: foun,d peer: Apple-Iphone6-1_PT7482.CDxPNA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 08:00:01.392 ThaliTest[327:124966] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:00:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:00:31.429 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:00:31.429 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:00:31.430 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:01:01.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:01:01.432 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:01:01.432 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 08:01:01.434 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:01:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:01:31.430 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:01:31.430 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:01:31.431 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-07 08:02:01.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:02:01.430 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:02:01.430 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:02:01.431 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 08:02:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:02:31.430 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:02:31.431 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:02:31.431 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 08:03:01.392 ThaliTest[327:124966] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 08:03:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:03:31.429 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:03:31.430 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 08:03:31.433 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 08:04:01.392 ThaliTest[327:124966] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 08:04:31.393 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:04:31.435 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 08:04:31.436 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:04:31.437 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 08:05:01.392 ThaliTest[327:124966] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 08:05:01.436 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:05:01.437 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:05:01.437 ThaliTest[327:124966] client: foun,d peer: Apple-Iphone6-1_PT7482.CDxPNA==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 08:05:31.392 ThaliTest[327:124966] multipeer session: restart
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
Error type "connect_error" when connecting to the test server
,2015-12-07 08:06:01.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:06:01.428 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:06:01.429 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:06:01.431 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 08:06:31.392 ThaliTest[327:124966] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 08:06:31.695 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:06:31.696 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:06:31.696 ThaliTest[327:124966] client: found, peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:07:01.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:07:01.428 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:07:01.428 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:07:01.430 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
,2015-12-07 08:07:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:07:31.433 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:07:31.434 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 08:07:31.434 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
Error type "connect_error" when connecting to the test server
,2015-12-07 08:08:01.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:08:01.430 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:08:01.430 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:08:01.430 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 08:08:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:08:31.430 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:08:31.430 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 08:08:31.434 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:09:01.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:09:01.426 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 08:09:01.431 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:09:01.431 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 08:09:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:09:31.431 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:09:31.432 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:09:31.432 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:10:01.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:10:01.429 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:10:01.429 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:10:01.430 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 08:10:31.392 ThaliTest[327:124966] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 08:11:01.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:11:01.426 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:11:01.426 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:11:01.427 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 08:11:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:11:31.433 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 08:11:31.435 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:11:31.435 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 08:12:01.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:12:01.430 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:12:01.430 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:12:01.430 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
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
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 08:12:31.392 ThaliTest[327:124966] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 08:13:01.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:13:01.425 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:13:01.427 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:13:01.428 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 08:13:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:13:31.431 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:13:31.431 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:13:31.433 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:14:01.392 ThaliTest[327:124966] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 08:14:31.392 ThaliTest[327:124966] multipeer session: restart
,2015-12-07 08:14:31.428 ThaliTest[327:124966] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 08:14:31.428 ThaliTest[327:124966] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:14:31.429 ThaliTest[327:124966] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server

```
