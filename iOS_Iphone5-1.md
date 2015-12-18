#### Test 539786633aa3ea0_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/539786633aa3ea0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/EE3728CC-08D9-46A6-B188-C7D284F46D6B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/EE3728CC-08D9-46A6-B188-C7D284F46D6B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/539786633aa3ea0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/539786633aa3ea0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C1F8BD85-14E0-41F9-99CF-8D92929838FB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60025"
,(lldb)     command script import "/tmp/EE3728CC-08D9-46A6-B188-C7D284F46D6B/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 14:25:08.761 ThaliTest[356:409031] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/04AFC355-1252-4449-934B-4D660B1A5B16/Library/Cookies/Cookies.binarycookies
,2015-12-18 14:25:09.283 ThaliTest[356:409031] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 14:25:09.285 ThaliTest[356:409031] Multi-tasking -> Device: YES, App: YES
,2015-12-18 14:25:09.292 ThaliTest[356:409031] Unlimited access to network resources
,2015-12-18 14:25:09.305 ThaliTest[356:409031] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 14:25:19.677 ThaliTest[356:409031] Resetting plugins due to page load.
,2015-12-18 14:25:23.223 ThaliTest[356:409031] Finished load of: file:///var/mobile/Containers/Bundle/Application/C1F8BD85-14E0-41F9-99CF-8D92929838FB/ThaliTest.app/www/index.html
,2015-12-18 14:25:23.433 ThaliTest[356:409031] JXcore Cordova plugin initializing
,2015-12-18 14:25:23.434 ThaliTest[356:409204] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT6006
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 52728
,2015-12-18 14:39:32.595 ThaliTest[356:409204] jxcore: startBroadcasting
,2015-12-18 14:39:32.608 ThaliTest[356:409204] server: starting Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:32.609 ThaliTest[356:409204] multipeer session: start timer: 0x19f9c1c0
2015-12-18 14:39:32.609 ThaliTest[356:409204] THEMultipeerSession initialized peer Apple-Iphone5-1_PT6006
2015-12-18 14:39:32.610 ThaliTest[356:409204] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-18T13:39:32.612Z SendDataTCPServer.js: TCP/IP server is bound to port: 52728
,2015-12-18 14:39:32.634 ThaliTest[356:409031] client: found peer: Apple-Iphone5-1_PT724.734x4g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT724.734x4g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT724.734x4g==
2015-12-18T13:39:32.638Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT724.734x4g==
2015-12-18T13:39:32.638Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT724.734x4g==
2015-,12-18T13:39:32.638Z SendDataConnector.js: do connect now
2015-12-18 14:39:32.639 ThaliTest[356:409204] jxcore: connect Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 14:39:32.639 ThaliTest[356:409204] client session: connect
2015-12-18 14:39:32.640 ThaliTest[356:409204] client session: stateChange:0->1 Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 14:39:35.007 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 14:39:35.067 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT1412.+KloFA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1412.+KloFA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 14:39:35.080 ThaliTest[356:409031] multipeer session: reset timer
2015-12-18 14:39:35.080 ThaliTest[356:409031] multipeer session: stop timer
2015-12-18 14:39:35.080 ThaliTest[356:409031] multipeer session: start timer: 0x19f9c1c0
2015-12-18 ,14:39:35.081 ThaliTest[356:409031] server session: connect
2015-12-18 14:39:35.081 ThaliTest[356:409031] server session: stateChange:0->1 Apple-Iphone5s-1_PT4569
2015-12-18 14:39:35.087 ThaliTest[356:409031] server: accepting invitation Apple-Iphone5s-1_PT4569
,2015-12-18 14:39:35.524 ThaliTest[356:409031] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5907.ktOSYA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 14:39:35.533 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 14:39:37.052 ThaliTest[356:409031] multipeer session: reset timer
2015-12-18 14:39:37.052 ThaliTest[356:409031] multipeer session: stop timer
2015-12-18 14:39:37.052 ThaliTest[356:409031] multipeer session: start timer: 0x19f9c1c0
2015-12-18 14:39:37.053 ThaliTest[356:409031] server session: connect
2015-12-18 14:39:37.053 ThaliTest[356:409031] server session: stateChange:0->1 Apple-Iphone6-1_PT5907
,2015-12-18 14:39:37.061 ThaliTest[356:409031] server: accepting invitation Apple-Iphone6-1_PT5907
,2015-12-18 14:39:37.072 ThaliTest[356:409031] multipeer session: reset timer
2015-12-18 14:39:37.072 ThaliTest[356:409031] multipeer session: stop timer
2015-12-18 14:39:37.073 ThaliTest[356:409031] multipeer session: start timer: 0x19f9c1c0
2015-12-18 ,14:39:37.073 ThaliTest[356:409031] server session: connect
2015-12-18 14:39:37.073 ThaliTest[356:409031] server session: stateChange:0->1 Apple-IpadAir2-1_PT4577
,2015-12-18 14:39:37.088 ThaliTest[356:409031] server: accepting invitation Apple-IpadAir2-1_PT4577
,2015-12-18 14:39:38.570 ThaliTest[356:410625] server session: connected
2015-12-18 14:39:38.570 ThaliTest[356:410625] server session: stateChange:1->2 Apple-Iphone5s-1_PT4569
,2015-12-18 14:39:38.623 ThaliTest[356:409031] server relay: connected (to port: 52728)
,2015-12-18T13:39:38.630Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T13:39:39.030Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-18T13:39:39.082Z SendDataTCPServer.js: TCP/IP server has received 31856 bytes of data
,2015-12-18T13:39:39.099Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-18T13:39:39.118Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 14:39:39.191 ThaliTest[356:410623] server session: not connected Apple-Iphone5s-1_PT4569
,2015-12-18 14:39:40.130 ThaliTest[356:410619] server session: connected
,2015-12-18 14:39:40.130 ThaliTest[356:410619] server session: stateChange:1->2 Apple-Iphone6-1_PT5907
2015-12-18 14:39:40.134 ThaliTest[356:409031] server relay: connected (to port: 52728)
,2015-12-18T13:39:40.142Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18 14:39:40.202 ThaliTest[356:410619] server session: connected
,2015-12-18 14:39:40.202 ThaliTest[356:410619] server session: stateChange:1->2 Apple-IpadAir2-1_PT4577
,2015-12-18 14:39:40.218 ThaliTest[356:409031] server relay: connected (to port: 52728)
,2015-12-18T13:39:40.224Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T13:39:40.601Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-18T13:39:40.616Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-18T13:39:40.620Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-18T13:39:40.635Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-18T13:39:40.661Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18T13:39:40.687Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 14:39:40.724 ThaliTest[356:410625] server session: not connected Apple-IpadAir2-1_PT4577
,2015-12-18 14:39:40.753 ThaliTest[356:410625] server session: not connected Apple-Iphone6-1_PT5907
,2015-12-18 14:39:48.353 ThaliTest[356:409031] client: lost peer: Apple-Iphone5-1_PT724.734x4g==
2015-12-18 14:39:48.353 ThaliTest[356:409031] client session: onPeerLost: Apple-Iphone5-1_PT724.734x4g==
2015-12-18 14:39:48.353 ThaliTest[356:409031] client ,session: onLinkFailure: Apple-Iphone5-1_PT724.734x4g==
2015-12-18 14:39:48.354 ThaliTest[356:409031] client session: disconnect
2015-12-18 14:39:48.354 ThaliTest[356:409031] client session: stateChange:1->0 Apple-Iphone5-1_PT724.734x4g==
2015-12-18 14:3,9:48.355 ThaliTest[356:409031] client session: fireConnectCallback: Apple-Iphone5-1_PT724.734x4g==
2015-12-18 14:39:48.355 ThaliTest[356:409031] jxcore: connect: fail: Peer disconnected
2015-12-18T13:39:48.356Z SendDataConnector.js: CLIENT connected to 0,, error: Peer disconnected
2015-12-18T13:39:48.356Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-18T13:39:48.356Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT724.,734x4g==","peerName":"(null)","peerAvailable":false}]
,2015-12-18T13:39:53.358Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T13:39:53.359Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 14:39:58.371 ThaliTest[356:409204] jxcore: disconnect
2015-12-18 14:39:58.371 ThaliTest[356:409204] jxcore: disconnect: fail
2015-12-18T13:39:58.372Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T13:39:58.372Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT724.734x4g== with availability status: true
2015-12-18T13:39:58.373Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T13:39:58.373Z SendDataConnector.js: do connect now
2015-12-18 14:39:58.374 ThaliTest[356:409204] jxcore: connect Apple-Iphone5-1_PT724.734x4g==
2015-12-18 14:39:58.374 ThaliTest[356:409204] client: connect: unreachable Apple-Iphone5-1_PT724.73,4x4g==
2015-12-18 14:39:58.374 ThaliTest[356:409204] jxcore: connect: fail: Peer unreachable
,2015-12-18T13:39:58.376Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T13:39:58.376Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T13:39:58.376Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18 14:39:58.838 ThaliTest[356:409031] client: lost peer: Apple-IpadAir2-1_PT1412.+KloFA==
2015-12-18 14:39:58.839 ThaliTest[356:409031] client session: onPeerLost: Apple-IpadAir2-1_PT1412.+KloFA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1412.+KloFA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-18 14:40:01.308 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT1412.+KloFA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1412.+KloFA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18T13:40:03.379Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T13:40:03.379Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 14:40:06.274 ThaliTest[356:409031] client: lost peer: Apple-IpadAir2-1_PT1412.+KloFA==
2015-12-18 14:40:06.274 ThaliTest[356:409031] client session: onPeerLost: Apple-IpadAir2-1_PT1412.+KloFA==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT1412.+KloFA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,appEnteredForeground wasn't registered
,2015-12-18 14:40:07.074 ThaliTest[356:409031] multipeer session: restart
,2015-12-18 14:40:07.110 ThaliTest[356:409031] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:40:07.110 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:40:07.113 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:40:08.393 ThaliTest[356:409204] jxcore: disconnect
2015-12-18 14:40:08.393 ThaliTest[356:409204] jxcore: disconnect: fail
2015-12-18T13:40:08.394Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T13:40:08.394Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT724.734x4g== with availability status: true
2015-12-18T13:40:08.395Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT724.734x4g==
2015-12-,18T13:40:08.395Z SendDataConnector.js: do connect now
,2015-12-18 14:40:08.396 ThaliTest[356:409204] jxcore: connect Apple-Iphone5-1_PT724.734x4g==
2015-12-18 14:40:08.396 ThaliTest[356:409204] client: connect: unreachable Apple-Iphone5-1_PT724.734x4g==
2015-12-18 14:40:08.396 ThaliTest[356:409204] jxcore: connect: fail: Peer unreachable
,2015-12-18T13:40:08.397Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T13:40:08.397Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T13:40:08.397Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T13:40:13.406Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T13:40:13.407Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 14:40:18.419 ThaliTest[356:409204] jxcore: disconnect
2015-12-18 14:40:18.420 ThaliTest[356:409204] jxcore: disconnect: fail
2015-12-18T13:40:18.420Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T13:40:18.421Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT724.734x4g== with availability status: true
2015-12-18T13:40:18.421Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T13:40:18.421Z SendDataConnector.js: do connect now
2015-12-18 14:40:18.422 ThaliTest[356:409204] jxcore: connect Apple-Iphone5-1_PT724.734x4g==
2015-12-18 14:40:18.423 ThaliTest[356:409204] client: connect: unreachable Apple-Iphone5-1_PT724.73,4x4g==
2015-12-18 14:40:18.423 ThaliTest[356:409204] jxcore: connect: fail: Peer unreachable
,2015-12-18T13:40:18.423Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T13:40:18.424Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-18T13:40:18.424Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T13:40:23.430Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T13:40:23.431Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 14:40:23.927 ThaliTest[356:409031] client: lost peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:40:23.927 ThaliTest[356:409031] client session: onPeerLost: Apple-Iphone5s-1_PT4569.cwXFvg==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-18 14:40:28.444 ThaliTest[356:409204] jxcore: disconnect
2015-12-18 14:40:28.445 ThaliTest[356:409204] jxcore: disconnect: fail
2015-12-18T13:40:28.445Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T13:40:28.446Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT724.734x4g== with availability status: true
,2015-12-18T13:40:28.447Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT724.734x4g==
2015-12-18T13:40:28.447Z SendDataConnector.js: do connect now
2015-12-18 14:40:28.448 ThaliTest[356:409204] jxcore: connect Apple-Iphone5-1_PT724.734,x4g==
,2015-12-18 14:40:28.448 ThaliTest[356:409204] client: connect: unreachable Apple-Iphone5-1_PT724.734x4g==
2015-12-18 14:40:28.449 ThaliTest[356:409204] jxcore: connect: fail: Peer unreachable
,2015-12-18T13:40:28.449Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-18T13:40:28.449Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-18T13:40:28.451Z SendDataConnector.js: CLIENT Stop now
2015-12-18 14:40:28.451 ThaliTest[356:409204] jxcore: disconnect
2015-12-18 14:40:28.451 ThaliTest[356:409204] jxcore: disconnect: fail
2015-12-18T13:40:28.452Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT724.734x4g==
---- round done--------
,device[2]: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18T13:40:28.453Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18T13:40:28.454Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18T13:40:28.454Z SendDataConnector.js: do connect now
,2015-12-18 14:40:28.455 ThaliTest[356:409204] jxcore: connect Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:40:28.455 ThaliTest[356:409204] client session: connect
2015-12-18 14:40:28.455 ThaliTest[356:409204] client session: stateChange:0->1 Apple-Iphon,e6-1_PT5907.ktOSYA==
,2015-12-18 14:40:28.774 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
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
Error type "connect_error" when connecting to the test server
,2015-12-18 14:40:35.913 ThaliTest[356:410932] client session: connected
2015-12-18 14:40:35.913 ThaliTest[356:410932] client session: stateChange:1->2 Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:40:35.940 ThaliTest[356:410724] client session: fireConnectCallback: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:40:35.941 ThaliTest[356:410724] jxcore: connect: success
,2015-12-18T13:40:35.942Z SendDataConnector.js: CLIENT connected to 52737, error: null
2015-12-18T13:40:35.942Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 14:40:35.944 ThaliTest[356:409031] client: relay established
2015-12-18 14:40:35.945 ThaliTest[356:409031] client: new accepted socket: 0x19ee0a00
,2015-12-18T13:40:35.960Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18 14:40:37.074 ThaliTest[356:409031] multipeer session: restart
,2015-12-18 14:40:37.123 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:40:37.124 ThaliTest[356:409031] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:40:37.130 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18T13:40:37.209Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T13:40:37.210Z SendDataConnector.js: got all data for this round
,2015-12-18T13:40:37.212Z SendDataConnector.js: CLIENT Stop now
2015-12-18T13:40:37.212Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:40:37.214 ThaliTest[356:409204] jxcore: disconnect
2015-12-18 14:40:37.215 ThaliTest[356:409204] client session: disconnectFromPeer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:40:37.215 ThaliTest[356:409204] client session: disconnect
2,015-12-18 14:40:37.215 ThaliTest[356:409204] client session: stateChange:2->0 Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:40:37.222 ThaliTest[356:409204] jxcore: disconnect: success
2015-12-18T13:40:37.222Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5907.ktOSYA==
---- round done--------
device[3]: Apple-Iphone5s-1_PT4569.cw,XFvg==
2015-12-18T13:40:37.223Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18T13:40:37.224Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18T13:40:37.224Z SendDataConnector.js: do connect now
2015-12-18 14:40:37.227 ThaliTest[356:409204] jxcore: connect Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:40:37.227 ThaliTest[356:409204] client session: connect
2015-12-18 14:40:37.227 ThaliTest[356:409204] client session: stateChange:0->1 Apple-Iphone5s-1_PT4569.cwXFvg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:40:40.836 ThaliTest[356:410724] client session: connected
2015-12-18 14:40:40.836 ThaliTest[356:410724] client session: stateChange:1->2 Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:40:40.841 ThaliTest[356:410932] client session: fireConnectCallback: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:40:40.841 ThaliTest[356:410932] jxcore: connect: success
2015-12-18T13:40:40.842Z SendDataConnector.js: CLIENT connected to ,52742, error: null
2015-12-18T13:40:40.842Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 14:40:40.846 ThaliTest[356:409031] client: relay established
,2015-12-18 14:40:40.846 ThaliTest[356:409031] client: new accepted socket: 0x19fa7a70
,2015-12-18T13:40:40.858Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T13:40:41.389Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T13:40:41.416Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T13:40:41.431Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-18T13:40:41.446Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-18T13:40:41.652Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T13:40:41.653Z SendDataConnector.js: got all data for this round
,2015-12-18T13:40:41.655Z SendDataConnector.js: CLIENT Stop now
2015-12-18T13:40:41.655Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-18 14:40:41.656 ThaliTest[356:409204] jxcore: disconnect
,2015-12-18 14:40:41.656 ThaliTest[356:409204] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:40:41.656 ThaliTest[356:409204] client session: disconnect
,2015-12-18 14:40:41.657 ThaliTest[356:409204] client session: stateChange:2->0 Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:40:41.665 ThaliTest[356:409204] jxcore: disconnect: success
2015-12-18T13:40:41.667Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4569.cwXFvg==
---- round done--------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT6006","time":69084,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT724.734x4g==","time":55812,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Ip,hone6-1_PT5907.ktOSYA==","time":8756,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT4569.cwXFvg==","time":4429,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceiv,ed":100000}]}
,sendList : 100% : 8756 ms, 99% : 8756 ms, 95 : 8756 ms, 90% : 8756 ms.
Result count 2, range 4429 ms to  8756 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5-1_PT724.734x4g==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-18T13:40:41.675Z SendDataConnector.js: CLIENT Stop now
2015-12-18T13:40:41.675Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-18 14:40:50.217 ThaliTest[356:409031] client: lost peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:40:50.217 ThaliTest[356:409031] client session: onPeerLost: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:40:50.219 ThaliTest[356:409031] cli,ent: lost peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:40:50.219 ThaliTest[356:409031] client session: onPeerLost: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)",,"peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:40:53.820 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:40:58.578 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:41:07.074 ThaliTest[356:409031] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-18 14:41:07.130 ThaliTest[356:409031] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:41:07.131 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:41:07.131 ThaliTest[356:409031] client: fou,nd peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:41:10.430 ThaliTest[356:409031] client: lost peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:41:10.430 ThaliTest[356:409031] client session: onPeerLost: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-18 14:41:27.827 ThaliTest[356:409031] client: lost peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:41:27.827 ThaliTest[356:409031] client session: onPeerLost: Apple-Iphone5s-1_PT4569.cwXFvg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 14:41:30.875 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-18 14:41:37.074 ThaliTest[356:409031] multipeer session: restart
,2015-12-18 14:41:37.113 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:41:37.116 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAi,r2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-18 14:41:40.364 ThaliTest[356:409031] client: lost peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:41:40.364 ThaliTest[356:409031] client session: onPeerLost: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:41:47.715 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:41:57.581 ThaliTest[356:409031] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-18 14:42:07.074 ThaliTest[356:409031] multipeer session: restart
,2015-12-18 14:42:07.113 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:42:07.114 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:42:25.981 ThaliTest[356:409031] client: lost peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:42:25.981 ThaliTest[356:409031] client session: onPeerLost: Apple-Iphone5s-1_PT4569.cwXFvg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-18 14:42:33.125 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":true}]
,2015-12-18 14:42:37.074 ThaliTest[356:409031] multipeer session: restart
,2015-12-18 14:42:37.106 ThaliTest[356:409031] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:42:37.118 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:42:37.122 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:43:07.074 ThaliTest[356:409031] multipeer session: restart
,2015-12-18 14:43:07.118 ThaliTest[356:409031] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:43:07.122 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:43:07.125 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-18 14:43:37.074 ThaliTest[356:409031] multipeer session: restart
,2015-12-18 14:43:37.114 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:43:37.115 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:43:49.005 ThaliTest[356:409031] client: lost peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:43:49.006 ThaliTest[356:409031] client session: onPeerLost: Apple-Iphone5s-1_PT4569.cwXFvg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:44:07.074 ThaliTest[356:409031] multipeer session: restart
,2015-12-18 14:44:07.115 ThaliTest[356:409031] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:44:07.115 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":true}]
,2015-12-18 14:44:07.121 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-18 14:44:37.074 ThaliTest[356:409031] multipeer session: restart
,2015-12-18 14:44:37.119 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:44:37.120 ThaliTest[356:409031] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:44:37.123 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
Error type "connect_error" when connecting to the test server
,2015-12-18 14:45:07.074 ThaliTest[356:409031] multipeer session: restart
,2015-12-18 14:45:07.116 ThaliTest[356:409031] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:45:07.116 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:45:07.122 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-18 14:45:37.074 ThaliTest[356:409031] multipeer session: restart
,2015-12-18 14:45:37.118 ThaliTest[356:409031] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:45:37.119 ThaliTest[356:409031] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:45:37.123 ThaliTest[356:409031] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-18 14:45:50.485 ThaliTest[356:409031] client: lost peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:45:50.486 ThaliTest[356:409031] client session: onPeerLost: Apple-Iphone6-1_PT5907.ktOSYA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5907.ktOSYA==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:45:59.472 ThaliTest[356:409031] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5907.ktOSYA==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:46:07.074 ThaliTest[356:409031] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-18 14:46:37.074 ThaliTest[356:409031] multipeer session: restart
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
,2015-12-18 14:47:07.074 ThaliTest[356:409031] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-18 14:47:37.074 ThaliTest[356:409031] multipeer session: restart
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
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:48:07.074 ThaliTest[356:409031] multipeer session: restart
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
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-18 14:48:37.074 ThaliTest[356:409031] multipeer session: restart
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
,2015-12-18 14:49:07.074 ThaliTest[356:409031] multipeer session: restart
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
,2015-12-18 14:49:37.074 ThaliTest[356:409031] multipeer session: restart
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
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:50:07.074 ThaliTest[356:409031] multipeer session: restart
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
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-18 14:50:37.005 ThaliTest[356:409031] multipeer session: restart
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
,2015-12-18 14:51:07.005 ThaliTest[356:409031] multipeer session: restart
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
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-18 14:51:37.005 ThaliTest[356:409031] multipeer session: restart
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
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:52:07.005 ThaliTest[356:409031] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-18 14:52:37.005 ThaliTest[356:409031] multipeer session: restart
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
,2015-12-18 14:53:07.005 ThaliTest[356:409031] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-18 14:53:37.005 ThaliTest[356:409031] multipeer session: restart
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

```
