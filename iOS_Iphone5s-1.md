#### Test 55311151a2306df_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55311151a2306df/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/A9E9E2D3-4811-4E74-9992-9E77884E63A7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A9E9E2D3-4811-4E74-9992-9E77884E63A7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55311151a2306df/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55311151a2306df/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/13D11546-9FBB-43FD-9BD0-AC483F9A288A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49486"
,(lldb)     command script import "/tmp/A9E9E2D3-4811-4E74-9992-9E77884E63A7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-01-07 09:36:53.815 ThaliTest[1410:3026272] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4CFE676B-E945-446D-9344-BC0ED2F7A487/Library/Cookies/Cookies.binarycookies
,2016-01-07 09:36:54.198 ThaliTest[1410:3026272] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-07 09:36:54.200 ThaliTest[1410:3026272] Multi-tasking -> Device: YES, App: YES
,2016-01-07 09:36:54.209 ThaliTest[1410:3026272] Unlimited access to network resources
,2016-01-07 09:36:54.221 ThaliTest[1410:3026272] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-07 09:37:03.263 ThaliTest[1410:3026272] Resetting plugins due to page load.
,2016-01-07 09:37:07.174 ThaliTest[1410:3026272] Finished load of: file:///var/mobile/Containers/Bundle/Application/13D11546-9FBB-43FD-9BD0-AC483F9A288A/ThaliTest.app/www/index.html
,2016-01-07 09:37:07.393 ThaliTest[1410:3026272] JXcore Cordova plugin initializing
,2016-01-07 09:37:07.395 ThaliTest[1410:3026488] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2016-01-07 09:37:08.699 ThaliTest[1410:3026272] THREAD WARNING: ['JXcore'] took '90.395020' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-07 09:41:50.630 ThaliTest[1410:3026488] jxcore: startBroadcasting
,2016-01-07 09:41:50.650 ThaliTest[1410:3026488] server: starting Apple-Iphone5s-1.TWDlRQ==
2016-01-07 09:41:50.652 ThaliTest[1410:3026488] multipeer session: start timer: 0x15611220
2016-01-07 09:41:50.652 ThaliTest[1410:3026488] THEMultipeerSession init,ialized peer Apple-Iphone5s-1
2016-01-07 09:41:50.653 ThaliTest[1410:3026488] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-07 09:41:50.978 ThaliTest[1410:3026272] client: found peer: Apple-IpadAir2-1.ujszBw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.ujszBw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1.ujszBw==, peerAvailable: true
,2016-01-07 09:41:51.389 ThaliTest[1410:3026272] client: found peer: Apple-Iphone5-1.Xe0AvA==
2016-01-07 09:41:51.390 ThaliTest[1410:3026272] client: found peer: Apple-Iphone6-1.qqPEfA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.Xe0AvA==,","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1.Xe0AvA==, peerAvailable: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.qqPEfA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1.qqPEfA==, peerAvailable: true
,2016-01-07 09:42:20.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:42:50.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:42:50.709 ThaliTest[1410:3026272] client: found peer: Apple-Iphone5-1.Xe0AvA==
2016-01-07 09:42:50.710 ThaliTest[1410:3026272] client: found peer: Apple-IpadAir2-1.ujszBw==
,2016-01-07 09:42:51.700 ThaliTest[1410:3026272] client: found peer: Apple-Iphone6-1.qqPEfA==
,2016-01-07 09:43:11.356 ThaliTest[1410:3026272] client: lost peer: Apple-Iphone5-1.Xe0AvA==
2016-01-07 09:43:11.357 ThaliTest[1410:3026272] client session: onPeerLost: Apple-Iphone5-1.Xe0AvA==
2016-01-07 09:43:11.357 ThaliTest[1410:3026272] client: lost ,peer: Apple-IpadAir2-1.ujszBw==
2016-01-07 09:43:11.358 ThaliTest[1410:3026272] client session: onPeerLost: Apple-IpadAir2-1.ujszBw==
2016-01-07 09:43:11.358 ThaliTest[1410:3026272] client: lost peer: Apple-Iphone6-1.qqPEfA==
2016-01-07 09:43:11.358 Tha,liTest[1410:3026272] client session: onPeerLost: Apple-Iphone6-1.qqPEfA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.Xe0AvA==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.ujszB,w==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.qqPEfA==","peerName":"(null)","peerAvailable":false}]
,2016-01-07 09:43:20.654 ThaliTest[1410:3026272] multipeer session: restart
,timeout now
,weAreDoneNow
,done, now sending data to server
,2016-01-07 09:43:50.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:44:20.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:44:50.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:45:20.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:45:50.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:46:20.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:46:50.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:47:20.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:47:50.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:48:20.653 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:48:50.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:49:20.654 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:49:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:50:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:50:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:51:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:51:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:52:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:52:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:53:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:53:50.637 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:54:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:54:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:55:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:55:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:56:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:56:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:57:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:57:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:58:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:58:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:59:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 09:59:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 10:00:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 10:00:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 10:01:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 10:01:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 10:02:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 10:02:50.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 10:03:20.638 ThaliTest[1410:3026272] multipeer session: restart
,2016-01-07 10:03:50.638 ThaliTest[1410:3026272] multipeer session: restart

```
