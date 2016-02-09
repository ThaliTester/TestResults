#### Test 5841644866d9c0e_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5841644866d9c0e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/DED1DBD5-08A7-4A31-B7C3-1D4C239872B0/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/DED1DBD5-08A7-4A31-B7C3-1D4C239872B0/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5841644866d9c0e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5841644866d9c0e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F1BD30B9-A67E-4E0E-8F02-31436F454CD8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52857"
,(lldb)     command script import "/tmp/DED1DBD5-08A7-4A31-B7C3-1D4C239872B0/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-02-09 13:07:11.572 ThaliTest[2819:8632106] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/78070CE7-0033-48AC-B558-3AB61E7E6C39/Library/Cookies/Cookies.binarycookies
,2016-02-09 13:07:11.686 ThaliTest[2819:8632106] Apache Cordova native platform version 4.0.1 is starting.
,2016-02-09 13:07:11.689 ThaliTest[2819:8632106] Multi-tasking -> Device: YES, App: YES
,2016-02-09 13:07:11.707 ThaliTest[2819:8632106] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 13:07:13.664 ThaliTest[2819:8632106] Using UIWebView
,2016-02-09 13:07:13.670 ThaliTest[2819:8632106] [CDVTimer][handleopenurl] 0.319004ms
,2016-02-09 13:07:13.675 ThaliTest[2819:8632106] [CDVTimer][intentandnavigationfilter] 4.655004ms
2016-02-09 13:07:13.675 ThaliTest[2819:8632106] [CDVTimer][gesturehandler] 0.263035ms
2016-02-09 13:07:13.676 ThaliTest[2819:8632106] [CDVTimer][TotalPluginStartup] 6.253958ms
,2016-02-09 13:07:21.616 ThaliTest[2819:8632106] Resetting plugins due to page load.
,2016-02-09 13:07:25.529 ThaliTest[2819:8632106] Finished load of: file:///var/mobile/Containers/Bundle/Application/F1BD30B9-A67E-4E0E-8F02-31436F454CD8/ThaliTest.app/www/index.html
,2016-02-09 13:07:25.740 ThaliTest[2819:8632106] JXcore Cordova plugin initializing
,2016-02-09 13:07:25.744 ThaliTest[2819:8632424] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1BD30B9-A67E-4E0E-8F02-31436F454CD8/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1BD30B9-A67E-4E0E-8F02-31436F454CD8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1BD30B9-A67E-4E0E-8F02-31436F454CD8/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1BD30B9-A67E-4E0E-8F02-31436F454CD8/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1BD30B9-A67E-4E0E-8F02-31436F454CD8/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1BD30B9-A67E-4E0E-8F02-31436F454CD8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1BD30B9-A67E-4E0E-8F02-31436F454CD8/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1BD30B9-A67E-4E0E-8F02-31436F454CD8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1BD30B9-A67E-4E0E-8F02-31436F454CD8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,# teardown

,ok 2 firstPromise setTimeout

,ok 3 firstPromise result

,ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

,ok 6 secondPromise result

,ok 7 secondPromise testValue

,ok 8 thirdPromise in promise

,ok 9 thirdPromise result

,ok 10 thirdPromise testValue

,# setup

,# basic

,# teardown

,ok 11 sane

,# setup

,# another

,# teardown

,ok 12 sane

,# setup

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

ok 16 should be equal

,ok 17 should not throw

,# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

,ok 21 should be equal

,ok 22 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,# teardown

,ok 23 should be equal

,# setup

,# failed to get mobile documents path

,# teardown

,ok 24 should be equal

,# setup

,# #init should register the peerAvailabilityChanged event

,# teardown

,ok 25 should be equal

,ok 26 should be equal

,ok 27 should be equal

,# setup

,# #init should register the networkChanged event

,# teardown

,ok 28 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 29 should throw

,# setup

,# #startBroadcasting should throw on empty string device name

,# teardown

,ok 30 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 31 should throw

,# setup

,# #startBroadcasting should throw on NaN port

,# teardown

,ok 32 should throw

,# setup

,# #startBroadcasting should throw on negative port

,# teardown

,ok 33 should throw

,# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 34 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 35 should be equal

,ok 36 should be equal

,ok 37 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

,ok 39 should be equal

,ok 40 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

,ok 42 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

,ok 46 should be equal

,ok 47 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

,ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

,ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

ok 53 should be equal

,# setup

,# #start should fail if called twice in a row

,# teardown

,ok 54 specific error should be received

,# setup

,# #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 55 specific error should be returned

,# setup

,# should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 56 error should be null

,ok 57 error should be null

,# setup

,# should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 58 error should be null

,ok 59 error should be null

,# setup

,# should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 60 error should be null

,ok 61 error should be null

,# setup

,# #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 62 specific error should be returned

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-09 13:17:04.742 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:04.751 ThaliTest[2819:8632424] server: starting 1455020224742.2819.ZmjwDg==
,2016-02-09 13:17:04.752 ThaliTest[2819:8632424] multipeer session: start timer: 0x1bc9f030
2016-02-09 13:17:04.753 ThaliTest[2819:8632424] THEMultipeerSession initialized peer 1455020224742.2819
,2016-02-09 13:17:04.754 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

2016-02-09 13:17:04.757 ThaliTest[2819:8632424] jxcore: stopBroadcasting
2016-02-09 13:17:04.757 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
2016-02-09 13:17:04.757 ThaliTest[2,819:8632424] multipeer session: stop timer
,2016-02-09 13:17:04.759 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

2016-02-09 13:17:04.762 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:04.771 ThaliTest[2819:8632424] server: starting 1455020224761.2819.6RilfQ==
2016-02-09 13:17:04.772 ThaliTest[2819:8632424] multipeer session: start timer: 0x1bca2030
2016-02-09 13:17:04.772 ThaliTest[2819:8632424] THEMultipeerSession in,itialized peer 1455020224761.2819
2016-02-09 13:17:04.772 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-02-09 13:17:04.774 ThaliTest[2819:8632424] jxcore: stopBroadcasting,
2016-02-09 13:17:04.774 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
2016-02-09 13:17:04.775 ThaliTest[2819:8632424] multipeer session: stop timer
2016-02-09 13:17:04.775 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
ok 66 Shou,ld be able to call stopBroadcasting without error

2016-02-09 13:17:04.777 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:04.785 ThaliTest[2819:8632424] server: starting 1455020224776.2819.RtPzsQ==
2016-02-09 13:17:04.786 ThaliTest[2819:8632424] multipeer session: start timer: 0x1565f740
2016-02-09 13:17:04.786 ThaliTest[2819:8632424] THEMultipeerSession in,itialized peer 1455020224776.2819
2016-02-09 13:17:04.789 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
ok 67 Should be able to call startBroadcasting without error

2016-02-09 13:17:04.792 ThaliTest[2819:8632424] jxcore: stopBroadcasting,
2016-02-09 13:17:04.793 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
2016-02-09 13:17:04.793 ThaliTest[2819:8632424] multipeer session: stop timer
2016-02-09 13:17:04.793 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
ok 68 Shou,ld be able to call stopBroadcasting without error

2016-02-09 13:17:04.795 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:04.807 ThaliTest[2819:8632424] server: starting 1455020224795.2819.5VwXaA==
,2016-02-09 13:17:04.819 ThaliTest[2819:8632424] multipeer session: start timer: 0x15591640
,2016-02-09 13:17:04.825 ThaliTest[2819:8632424] THEMultipeerSession initialized peer 1455020224795.2819
,2016-02-09 13:17:04.827 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-09 13:17:04.830 ThaliTest[2819:8632424] jxcore: stopBroadcasting
,2016-02-09 13:17:04.831 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
,2016-02-09 13:17:04.832 ThaliTest[2819:8632424] multipeer session: stop timer
,2016-02-09 13:17:04.835 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 13:17:04.840 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:04.844 ThaliTest[2819:8632424] server: starting 1455020224839.2819.K99x/Q==
,2016-02-09 13:17:04.849 ThaliTest[2819:8632424] multipeer session: start timer: 0x15665e60
,2016-02-09 13:17:04.855 ThaliTest[2819:8632424] THEMultipeerSession initialized peer 1455020224839.2819
,2016-02-09 13:17:04.855 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-09 13:17:04.858 ThaliTest[2819:8632424] jxcore: stopBroadcasting
,2016-02-09 13:17:04.858 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
,2016-02-09 13:17:04.859 ThaliTest[2819:8632424] multipeer session: stop timer
,2016-02-09 13:17:04.863 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 13:17:04.867 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:04.869 ThaliTest[2819:8632424] server: starting 1455020224866.2819.n3048Q==
,2016-02-09 13:17:04.872 ThaliTest[2819:8632424] multipeer session: start timer: 0x15659e80
,2016-02-09 13:17:04.877 ThaliTest[2819:8632424] THEMultipeerSession initialized peer 1455020224866.2819
,2016-02-09 13:17:04.879 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-09 13:17:04.881 ThaliTest[2819:8632424] jxcore: stopBroadcasting
,2016-02-09 13:17:04.882 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
,2016-02-09 13:17:04.883 ThaliTest[2819:8632424] multipeer session: stop timer
,2016-02-09 13:17:04.887 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 13:17:04.890 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:04.893 ThaliTest[2819:8632424] server: starting 1455020224890.2819.r/2WSw==
,2016-02-09 13:17:04.896 ThaliTest[2819:8632424] multipeer session: start timer: 0x1bca2590
,2016-02-09 13:17:04.901 ThaliTest[2819:8632424] THEMultipeerSession initialized peer 1455020224890.2819
,2016-02-09 13:17:04.902 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-09 13:17:04.905 ThaliTest[2819:8632424] jxcore: stopBroadcasting
,2016-02-09 13:17:04.906 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
,2016-02-09 13:17:04.907 ThaliTest[2819:8632424] multipeer session: stop timer
,2016-02-09 13:17:04.910 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-09 13:17:04.914 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:04.916 ThaliTest[2819:8632424] server: starting 1455020224913.2819.IR/J9g==
,2016-02-09 13:17:04.919 ThaliTest[2819:8632424] multipeer session: start timer: 0x1a2df540
,2016-02-09 13:17:04.921 ThaliTest[2819:8632424] THEMultipeerSession initialized peer 1455020224913.2819
,2016-02-09 13:17:04.922 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-09 13:17:04.929 ThaliTest[2819:8632424] jxcore: stopBroadcasting
,2016-02-09 13:17:04.930 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
,2016-02-09 13:17:04.931 ThaliTest[2819:8632424] multipeer session: stop timer
,2016-02-09 13:17:04.935 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 13:17:04.938 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:04.941 ThaliTest[2819:8632424] server: starting 1455020224938.2819.Vw6U0Q==
,2016-02-09 13:17:04.944 ThaliTest[2819:8632424] multipeer session: start timer: 0x15591640
,2016-02-09 13:17:04.951 ThaliTest[2819:8632424] THEMultipeerSession initialized peer 1455020224938.2819
,2016-02-09 13:17:04.952 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 13:17:04.955 ThaliTest[2819:8632424] jxcore: stopBroadcasting
,2016-02-09 13:17:04.955 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
,2016-02-09 13:17:04.956 ThaliTest[2819:8632424] multipeer session: stop timer
,2016-02-09 13:17:04.960 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 13:17:04.963 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:04.966 ThaliTest[2819:8632424] server: starting 1455020224962.2819.Tv8g/g==
,2016-02-09 13:17:04.969 ThaliTest[2819:8632424] multipeer session: start timer: 0x1bca2f40
,2016-02-09 13:17:04.974 ThaliTest[2819:8632424] THEMultipeerSession initialized peer 1455020224962.2819
,2016-02-09 13:17:04.977 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 13:17:04.979 ThaliTest[2819:8632424] jxcore: stopBroadcasting
,2016-02-09 13:17:04.980 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
,2016-02-09 13:17:04.981 ThaliTest[2819:8632424] multipeer session: stop timer
,2016-02-09 13:17:04.984 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 13:17:14.576 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:14.578 ThaliTest[2819:8632424] server: starting 1455020234575.2819.KfrjFA==
2016-02-09 13:17:14.578 ThaliTest[2819:8632424] multipeer session: start timer: 0x1bca4000
2016-02-09 13:17:14.579 ThaliTest[2819:8632424] THEMultipeerSession in,itialized peer 1455020234575.2819
2016-02-09 13:17:14.579 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-09 13:17:14.581 ThaliTest[2819:8632424] jxcore: startBroadcasting
2016-02-09 13:17:14.581 ThaliTest[2819:8632424] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

2016-02-09 13:17:14.583 ThaliTest[2819:8632424] jxcore: stopBroadcasting
2016-02-09 13:17:14.583 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
2016-02-09 13:17:14.583 ThaliTest[2819:8632424] multip,eer session: stop timer
2016-02-09 13:17:14.584 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 13:17:41.579 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:41.582 ThaliTest[2819:8632424] server: starting 1455020261579.2819.iSefsQ==
2016-02-09 13:17:41.583 ThaliTest[2819:8632424] multipeer session: start timer: 0x1a5388b0
2016-02-09 13:17:41.583 ThaliTest[2819:8632424] THEMultipeerSession in,itialized peer 1455020261579.2819
2016-02-09 13:17:41.583 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

2016-02-09 13:17:41.584 ThaliTest[2819:8632424] jxcore: connect foobar
2,016-02-09 13:17:41.585 ThaliTest[2819:8632424] client: unknown peer foobar
2016-02-09 13:17:41.585 ThaliTest[2819:8632424] jxcore: connect: fail: Unknown peer
ok 87 Should not connect to a bad peer

,2016-02-09 13:17:41.587 ThaliTest[2819:8632424] jxcore: stopBroadcasting
2016-02-09 13:17:41.589 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
2016-02-09 13:17:41.589 ThaliTest[2819:8632424] multipeer session: stop timer
2016-02-09 13:17:41.,589 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
ok 88 Should be able to call stopBroadcasting without error

,# setup
,
,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 13:17:50.990 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:17:50.992 ThaliTest[2819:8632424] server: starting 1455020270989.2819.QzPoNQ==
2016-02-09 13:17:50.993 ThaliTest[2819:8632424] multipeer session: start timer: 0x1a5f6240
2016-02-09 13:17:50.993 ThaliTest[2819:8632424] THEMultipeerSession in,itialized peer 1455020270989.2819
2016-02-09 13:17:50.993 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
ok 89 Should be able to call startBroadcasting without error

2016-02-09 13:17:50.995 ThaliTest[2819:8632424] jxcore: disconnect
2016-,02-09 13:17:50.995 ThaliTest[2819:8632424] jxcore: disconnect: fail
ok 90 Disconnect should fail to a non-existant peer 

2016-02-09 13:17:50.997 ThaliTest[2819:8632424] jxcore: stopBroadcasting
2016-02-09 13:17:50.997 ThaliTest[2819:8632424] THEMultip,eerSession stopping peer
2016-02-09 13:17:50.997 ThaliTest[2819:8632424] multipeer session: stop timer
2016-02-09 13:17:50.997 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
ok 91 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 13:18:03.272 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:18:03.274 ThaliTest[2819:8632424] server: starting 1455020283271.2819.w22JdQ==
2016-02-09 13:18:03.274 ThaliTest[2819:8632424] multipeer session: start timer: 0x1bca9e80
2016-02-09 13:18:03.274 ThaliTest[2819:8632424] THEMultipeerSession in,itialized peer 1455020283271.2819
2016-02-09 13:18:03.274 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-09 13:18:07.084 ThaliTest[2819:8632106] client: found peer: 1455020277385.1069.XMv4Kw==
2016-02-09 13:18:07.086 ThaliTest[2819:8632424] jxcore: connect 1455020277385.1069.XMv4Kw==
2016-02-09 13:18:07.086 ThaliTest[2819:8632424] client session: co,nnect
2016-02-09 13:18:07.086 ThaliTest[2819:8632424] client session: stateChange:0->1 1455020277385.1069.XMv4Kw==
,2016-02-09 13:18:07.144 ThaliTest[2819:8632106] multipeer session: reset timer
2016-02-09 13:18:07.144 ThaliTest[2819:8632106] multipeer session: stop timer
2016-02-09 13:18:07.145 ThaliTest[2819:8632106] multipeer session: start timer: 0x1bca9e80
2016-,02-09 13:18:07.145 ThaliTest[2819:8632106] server session: connect
2016-02-09 13:18:07.145 ThaliTest[2819:8632106] server session: stateChange:0->1 1455020277385.1069
,2016-02-09 13:18:07.151 ThaliTest[2819:8632106] server: accepting invitation 1455020277385.1069
,2016-02-09 13:18:10.023 ThaliTest[2819:8633714] server session: connected
2016-02-09 13:18:10.023 ThaliTest[2819:8633714] server session: stateChange:1->2 1455020277385.1069
,2016-02-09 13:18:10.043 ThaliTest[2819:8632106] server relay: socket disconnected
2016-02-09 13:18:10.044 ThaliTest[2819:8632106] server relay: 0x1b96f590 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 13:18:10.074 ThaliTest[2819:8633792] server session: not connected 1455020277385.1069
,2016-02-09 13:18:10.216 ThaliTest[2819:8633792] client session: connected
2016-02-09 13:18:10.216 ThaliTest[2819:8633792] client session: stateChange:1->2 1455020277385.1069.XMv4Kw==
,2016-02-09 13:18:10.237 ThaliTest[2819:8633714] client session: fireConnectCallback: 1455020277385.1069.XMv4Kw==
2016-02-09 13:18:10.237 ThaliTest[2819:8633714] jxcore: connect: success
ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 13:18:10.240 ThaliTest[2819:8632424] jxcore: disconnect
2016-02-09 13:18:10.241 ThaliTest[2819:8632424] client session: disconnectFromPeer: 1455020277385.1069.XMv4Kw==
2016-02-09 13:18:10.241 ThaliTest[2819:8632424] client session: disconnect,
2016-02-09 13:18:10.241 ThaliTest[2819:8632424] client session: stateChange:2->0 1455020277385.1069.XMv4Kw==
,2016-02-09 13:18:10.253 ThaliTest[2819:8632424] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 13:18:10.772 ThaliTest[2819:8632424] jxcore: stopBroadcasting
2016-02-09 13:18:10.772 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
2016-02-09 13:18:10.773 ThaliTest[2819:8632424] multipeer session: stop timer
2016-02-09 13:18:10.,773 ThaliTest[2819:8632424] server session: disconnect
2016-02-09 13:18:10.773 ThaliTest[2819:8632424] server session: stateChange:2->0 1455020277385.1069
2016-02-09 13:18:10.774 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 13:18:11.172 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:18:11.174 ThaliTest[2819:8632424] server: starting 1455020291171.2819.HjYL0w==
2016-02-09 13:18:11.175 ThaliTest[2819:8632424] multipeer session: start timer: 0x1bcaf020
2016-02-09 13:18:11.175 ThaliTest[2819:8632424] THEMultipeerSession in,itialized peer 1455020291171.2819
2016-02-09 13:18:11.175 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
ok 96 Should be able to call startBroadcasting without error

,2016-02-09 13:18:12.011 ThaliTest[2819:8632106] client: found peer: 1455020277385.1069.XMv4Kw==
2016-02-09 13:18:12.012 ThaliTest[2819:8632424] jxcore: connect 1455020277385.1069.XMv4Kw==
2016-02-09 13:18:12.012 ThaliTest[2819:8632424] client session: connect
2016-02-09 13:18:12.012 ThaliTest[2819:8632424] client session: stateChange:0->1 1455020277385.1069.XMv4Kw==
,2016-02-09 13:18:12.265 ThaliTest[2819:8632106] client: found peer: 1455020293046.1069.9oddgg==
2016-02-09 13:18:12.266 ThaliTest[2819:8632424] jxcore: connect 1455020293046.1069.9oddgg==
2016-02-09 13:18:12.266 ThaliTest[2819:8632424] client session: co,nnect
2016-02-09 13:18:12.267 ThaliTest[2819:8632424] client session: stateChange:0->1 1455020293046.1069.9oddgg==
,2016-02-09 13:18:12.463 ThaliTest[2819:8632106] multipeer session: reset timer
2016-02-09 13:18:12.463 ThaliTest[2819:8632106] multipeer session: stop timer
2016-02-09 13:18:12.463 ThaliTest[2819:8632106] multipeer session: start timer: 0x1bcaf020
2016-02-09 13:18:12.463 ThaliTest[2819:8632106] server session: connect
2016-02-09 13:18:12.463 ThaliTest[2819:8632106] server session: stateChange:0->1 1455020293046.1069
,2016-02-09 13:18:12.470 ThaliTest[2819:8632106] server: accepting invitation 1455020293046.1069
,2016-02-09 13:18:15.209 ThaliTest[2819:8633752] server session: connected
,2016-02-09 13:18:15.210 ThaliTest[2819:8633752] server session: stateChange:1->2 1455020293046.1069
,2016-02-09 13:18:15.219 ThaliTest[2819:8633751] client session: connected
,2016-02-09 13:18:15.219 ThaliTest[2819:8633751] client session: stateChange:1->2 1455020293046.1069.9oddgg==
,2016-02-09 13:18:15.251 ThaliTest[2819:8632106] server relay: socket disconnected
2016-02-09 13:18:15.251 ThaliTest[2819:8632106] server relay: 0x1a7a5bd0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 13:18:15.283 ThaliTest[2819:8633714] client session: fireConnectCallback: 1455020293046.1069.9oddgg==
,2016-02-09 13:18:15.284 ThaliTest[2819:8633714] jxcore: connect: success
,ok 97 Should be able to connect without error

,ok 98 Port should be within range

,2016-02-09 13:18:15.288 ThaliTest[2819:8632424] jxcore: connect 1455020293046.1069.9oddgg==
,2016-02-09 13:18:15.288 ThaliTest[2819:8632424] client: already connect(ing/ed) to 1455020293046.1069.9oddgg==
,2016-02-09 13:18:15.289 ThaliTest[2819:8632424] jxcore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

,2016-02-09 13:18:15.293 ThaliTest[2819:8632424] jxcore: disconnect
,2016-02-09 13:18:15.293 ThaliTest[2819:8632424] client session: disconnectFromPeer: 1455020293046.1069.9oddgg==
,2016-02-09 13:18:15.294 ThaliTest[2819:8632424] client session: disconnect
,2016-02-09 13:18:15.294 ThaliTest[2819:8632424] client session: stateChange:2->0 1455020293046.1069.9oddgg==
,2016-02-09 13:18:15.302 ThaliTest[2819:8633751] server session: not connected 1455020293046.1069
,2016-02-09 13:18:15.333 ThaliTest[2819:8632424] jxcore: disconnect: success
,ok 100 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup
,
,calling stopBroadcasting

,2016-02-09 13:18:15.797 ThaliTest[2819:8632424] jxcore: stopBroadcasting
2016-02-09 13:18:15.797 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
2016-02-09 13:18:15.797 ThaliTest[2819:8632424] multipeer session: stop timer
2016-02-09 13:18:15.,797 ThaliTest[2819:8632424] client session: disconnect
2016-02-09 13:18:15.798 ThaliTest[2819:8632424] client session: stateChange:1->0 1455020277385.1069.XMv4Kw==
2016-02-09 13:18:15.798 ThaliTest[2819:8632424] server session: disconnect
2016-02-09 13:,18:15.798 ThaliTest[2819:8632424] server session: stateChange:2->0 1455020293046.1069
2016-02-09 13:18:15.799 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 13:18:16.324 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:18:16.326 ThaliTest[2819:8632424] server: starting 1455020296324.2819.TAsZlw==
2016-02-09 13:18:16.327 ThaliTest[2819:8632424] multipeer session: start timer: 0x1b91bea0
2016-02-09 13:18:16.327 ThaliTest[2819:8632424] THEMultipeerSession initialized peer 1455020296324.2819
2016-02-09 13:18:16.328 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-09 13:18:17.010 ThaliTest[2819:8632106] client: found peer: 1455020293046.1069.9oddgg==
2016-02-09 13:18:17.011 ThaliTest[2819:8632424] jxcore: connect 1455020293046.1069.9oddgg==
2016-02-09 13:18:17.012 ThaliTest[2819:8632424] client session: co,nnect
2016-02-09 13:18:17.012 ThaliTest[2819:8632424] client session: stateChange:0->1 1455020293046.1069.9oddgg==
,2016-02-09 13:18:17.042 ThaliTest[2819:8632106] client: found peer: 1455020297766.1069.PYsssg==
2016-02-09 13:18:17.043 ThaliTest[2819:8632424] jxcore: connect 1455020297766.1069.PYsssg==
2016-02-09 13:18:17.043 ThaliTest[2819:8632424] client session: connect
2016-02-09 13:18:17.044 ThaliTest[2819:8632424] client session: stateChange:0->1 1455020297766.1069.PYsssg==
,2016-02-09 13:18:17.414 ThaliTest[2819:8632106] multipeer session: reset timer
2016-02-09 13:18:17.414 ThaliTest[2819:8632106] multipeer session: stop timer
2016-02-09 13:18:17.414 ThaliTest[2819:8632106] multipeer session: start timer: 0x1b91bea0
2016-,02-09 13:18:17.414 ThaliTest[2819:8632106] server session: connect
2016-02-09 13:18:17.415 ThaliTest[2819:8632106] server session: stateChange:0->1 1455020297766.1069
,2016-02-09 13:18:17.423 ThaliTest[2819:8632106] server: accepting invitation 1455020297766.1069
,2016-02-09 13:18:17.623 ThaliTest[2819:8632106] client: lost peer: 1455020293046.1069.9oddgg==
2016-02-09 13:18:17.624 ThaliTest[2819:8632106] client session: onPeerLost: 1455020293046.1069.9oddgg==
2016-02-09 13:18:17.624 ThaliTest[2819:8632106] client ,session: onLinkFailure: 1455020293046.1069.9oddgg==
2016-02-09 13:18:17.624 ThaliTest[2819:8632106] client session: disconnect
2016-02-09 13:18:17.624 ThaliTest[2819:8632106] client session: stateChange:1->0 1455020293046.1069.9oddgg==
2016-02-09 13:18:,17.624 ThaliTest[2819:8632106] client session: fireConnectCallback: 1455020293046.1069.9oddgg==
2016-02-09 13:18:17.625 ThaliTest[2819:8632106] jxcore: connect: fail: Peer disconnected
,2016-02-09 13:18:18.630 ThaliTest[2819:8632424] jxcore: connect 1455020293046.1069.9oddgg==
2016-02-09 13:18:18.631 ThaliTest[2819:8632424] client: connect: unreachable 1455020293046.1069.9oddgg==
2016-02-09 13:18:18.632 ThaliTest[2819:8632424] jxcore: connect: fail: Peer unreachable
,2016-02-09 13:18:20.129 ThaliTest[2819:8633792] client session: connected
,2016-02-09 13:18:20.129 ThaliTest[2819:8633792] client session: stateChange:1->2 1455020297766.1069.PYsssg==
,2016-02-09 13:18:20.133 ThaliTest[2819:8633792] client session: fireConnectCallback: 1455020297766.1069.PYsssg==
2016-02-09 13:18:20.133 ThaliTest[2819:8633792] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-09 13:18:20.136 ThaliTest[2819:8632424] jxcore: disconnect
2016-02-09 13:18:20.136 ThaliTest[2819:8632424] client session: disconnectFromPeer: 1455020297766.1069.PYsssg==
,2016-02-09 13:18:20.136 ThaliTest[2819:8632424] client session: disconnect
2016-02-09 13:18:20.136 ThaliTest[2819:8632424] client session: stateChange:2->0 1455020297766.1069.PYsssg==
,2016-02-09 13:18:20.207 ThaliTest[2819:8632424] jxcore: disconnect: success
,ok 104 Should be able to disconnect without error

,2016-02-09 13:18:20.210 ThaliTest[2819:8632424] jxcore: disconnect
2016-02-09 13:18:20.210 ThaliTest[2819:8632424] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 13:18:20.524 ThaliTest[2819:8633852] server session: connected
2016-02-09 13:18:20.525 ThaliTest[2819:8633852] server session: stateChange:1->2 1455020297766.1069
,2016-02-09 13:18:20.529 ThaliTest[2819:8632106] server relay: socket disconnected
2016-02-09 13:18:20.529 ThaliTest[2819:8632106] server relay: 0x1bcbe540 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 13:18:20.720 ThaliTest[2819:8633851] server session: not connected 1455020297766.1069
,calling stopBroadcasting

,2016-02-09 13:18:21.059 ThaliTest[2819:8632424] jxcore: stopBroadcasting
2016-02-09 13:18:21.060 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
2016-02-09 13:18:21.060 ThaliTest[2819:8632424] multipeer session: stop timer
2016-02-09 13:18:21.061 ThaliTest[2819:8632424] server session: disconnect
2016-02-09 13:18:21.061 ThaliTest[2819:8632424] server session: stateChange:2->0 1455020297766.1069
,2016-02-09 13:18:21.063 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 50389

,2016-02-09 13:18:23.921 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:18:23.924 ThaliTest[2819:8632424] server: starting 1455020303921.2819.aUWkkg==
2016-02-09 13:18:23.924 ThaliTest[2819:8632424] multipeer session: start timer: 0x1a7f5fd0
2016-02-09 13:18:23.924 ThaliTest[2819:8632424] THEMultipeerSession in,itialized peer 1455020303921.2819
2016-02-09 13:18:23.924 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
ok 106 Should be able to call startBroadcasting without error

,2016-02-09 13:18:23.967 ThaliTest[2819:8632106] client: found peer: 1455020304597.1069.F5tE5A==
2016-02-09 13:18:23.968 ThaliTest[2819:8632424] jxcore: connect 1455020304597.1069.F5tE5A==
2016-02-09 13:18:23.968 ThaliTest[2819:8632424] client session: co,nnect
2016-02-09 13:18:23.969 ThaliTest[2819:8632424] client session: stateChange:0->1 1455020304597.1069.F5tE5A==
,2016-02-09 13:18:26.859 ThaliTest[2819:8632106] multipeer session: reset timer
2016-02-09 13:18:26.860 ThaliTest[2819:8632106] multipeer session: stop timer
2016-02-09 13:18:26.860 ThaliTest[2819:8632106] multipeer session: start timer: 0x1a7f5fd0
2016-,02-09 13:18:26.860 ThaliTest[2819:8632106] server session: connect
2016-02-09 13:18:26.860 ThaliTest[2819:8632106] server session: stateChange:0->1 1455020304597.1069
,2016-02-09 13:18:26.867 ThaliTest[2819:8632106] server: accepting invitation 1455020304597.1069
,2016-02-09 13:18:27.530 ThaliTest[2819:8633852] client session: connected
2016-02-09 13:18:27.530 ThaliTest[2819:8633852] client session: stateChange:1->2 1455020304597.1069.F5tE5A==
,2016-02-09 13:18:27.535 ThaliTest[2819:8633852] client session: fireConnectCallback: 1455020304597.1069.F5tE5A==
2016-02-09 13:18:27.535 ThaliTest[2819:8633852] jxcore: connect: success
ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-09 13:18:27.540 ThaliTest[2819:8632106] client: relay established
2016-02-09 13:18:27.540 ThaliTest[2819:8632106] client: new accepted socket: 0x1568f8e0
,data in 2119

,data in 9855

,data in 14235

,data in 22995

,data in 27233

,data in 32850

,data in 33874

,data in 43800

,data in 44895

,data in 52560

,data in 64392

,data in 74460

,data in 76650

,data in 83149

,data in 88695

,data in 95265

,data in 104025

,data in 110595

,data in 111690

,data in 117094

,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 13:18:28.660 ThaliTest[2819:8632424] jxcore: disconnect
2016-02-09 13:18:28.660 ThaliTest[2819:8632424] client session: disconnectFromPeer: 1455020304597.1069.F5tE5A==
2016-02-09 13:18:28.660 ThaliTest[2819:8632424] client session: disconnect,
2016-02-09 13:18:28.660 ThaliTest[2819:8632424] client session: stateChange:2->0 1455020304597.1069.F5tE5A==
,2016-02-09 13:18:28.672 ThaliTest[2819:8632424] jxcore: disconnect: success
ok 110 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 13:18:29.450 ThaliTest[2819:8633852] server session: connected
2016-02-09 13:18:29.450 ThaliTest[2819:8633852] server session: stateChange:1->2 1455020304597.1069
,2016-02-09 13:18:29.513 ThaliTest[2819:8632106] server relay: connected (to port: 50389)
,2016-02-09 13:18:31.096 ThaliTest[2819:8633842] server session: not connected 1455020304597.1069
,calling stopBroadcasting

,2016-02-09 13:18:32.055 ThaliTest[2819:8632424] jxcore: stopBroadcasting
2016-02-09 13:18:32.056 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
2016-02-09 13:18:32.056 ThaliTest[2819:8632424] multipeer session: stop timer
2016-02-09 13:18:32.,056 ThaliTest[2819:8632424] server session: disconnect
2016-02-09 13:18:32.056 ThaliTest[2819:8632424] server session: stateChange:2->0 1455020304597.1069
,2016-02-09 13:18:32.061 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 50395

,2016-02-09 13:18:32.523 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:18:32.525 ThaliTest[2819:8632424] server: starting 1455020312522.2819.yh5DEw==
2016-02-09 13:18:32.525 ThaliTest[2819:8632424] multipeer session: start timer: 0x15648b80
2016-02-09 13:18:32.526 ThaliTest[2819:8632424] THEMultipeerSession in,itialized peer 1455020312522.2819
2016-02-09 13:18:32.526 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
ok 111 Should be able to call startBroadcasting without error

,2016-02-09 13:18:33.197 ThaliTest[2819:8632106] client: found peer: 1455020304597.1069.F5tE5A==
[{"peerIdentifier":"1455020304597.1069.F5tE5A==","peerName":"(null)","peerAvailable":true}]

2016-02-09 13:18:33.199 ThaliTest[2819:8632424] jxcore: connect ,1455020304597.1069.F5tE5A==
2016-02-09 13:18:33.199 ThaliTest[2819:8632424] client session: connect
2016-02-09 13:18:33.199 ThaliTest[2819:8632424] client session: stateChange:0->1 1455020304597.1069.F5tE5A==
,2016-02-09 13:18:33.222 ThaliTest[2819:8632106] client: found peer: 1455020314026.1069.hXy/gA==
,[{"peerIdentifier":"1455020314026.1069.hXy/gA==","peerName":"(null)","peerAvailable":true}]
,
,2016-02-09 13:18:33.230 ThaliTest[2819:8632424] jxcore: connect 1455020314026.1069.hXy/gA==
,2016-02-09 13:18:33.232 ThaliTest[2819:8632424] client session: connect
,2016-02-09 13:18:33.233 ThaliTest[2819:8632424] client session: stateChange:0->1 1455020314026.1069.hXy/gA==
,2016-02-09 13:18:33.560 ThaliTest[2819:8632106] multipeer session: reset timer
2016-02-09 13:18:33.560 ThaliTest[2819:8632106] multipeer session: stop timer
2016-02-09 13:18:33.561 ThaliTest[2819:8632106] multipeer session: start timer: 0x15648b80
2016-02-09 13:18:33.561 ThaliTest[2819:8632106] server session: connect
2016-02-09 13:18:33.561 ThaliTest[2819:8632106] server session: stateChange:0->1 1455020314026.1069
,2016-02-09 13:18:33.571 ThaliTest[2819:8632106] server: accepting invitation 1455020314026.1069
,2016-02-09 13:18:36.965 ThaliTest[2819:8633953] server session: connected
2016-02-09 13:18:36.965 ThaliTest[2819:8633953] server session: stateChange:1->2 1455020314026.1069
,2016-02-09 13:18:36.969 ThaliTest[2819:8633752] client session: connected
2016-02-09 13:18:36.969 ThaliTest[2819:8633752] client session: stateChange:1->2 1455020314026.1069.hXy/gA==
,2016-02-09 13:18:36.992 ThaliTest[2819:8633852] client session: fireConnectCallback: 1455020314026.1069.hXy/gA==
,2016-02-09 13:18:36.992 ThaliTest[2819:8633852] jxcore: connect: success
ok 112 Should be able to connect without error

,ok 113 Port should be within range

,ok 114 First connect should succeed

,2016-02-09 13:18:36.997 ThaliTest[2819:8632106] server relay: connected (to port: 50395)
,2016-02-09 13:18:37.037 ThaliTest[2819:8632106] client: relay established
2016-02-09 13:18:37.037 ThaliTest[2819:8632106] client: new accepted socket: 0x1bc48190
,ok 115 the test messages should be equal

,ok 116 First send should succeed

,2016-02-09 13:18:37.090 ThaliTest[2819:8632106] client: socket closed
2016-02-09 13:18:37.090 ThaliTest[2819:8632106] client relay: socket disconnected
2016-02-09 13:18:37.091 ThaliTest[2819:8632106] client relay: 0x1bc48190 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 13:18:37.091 ThaliTest[2819:8632106] client session: socket closed: 1455020314026.1069.hXy/gA==
,2016-02-09 13:18:37.091 ThaliTest[2819:8632106] client session: onLinkFailure: 1455020314026.1069.hXy/gA==
,2016-02-09 13:18:37.093 ThaliTest[2819:8632106] client session: disconnect
,2016-02-09 13:18:37.094 ThaliTest[2819:8632106] client session: stateChange:2->0 1455020314026.1069.hXy/gA==
,2016-02-09 13:18:37.110 ThaliTest[2819:8632106] client session: fireConnectionErrorEvent: 1455020314026.1069.hXy/gA==
,2016-02-09 13:18:37.113 ThaliTest[2819:8632424] jxcore: connect 1455020314026.1069.hXy/gA==
,2016-02-09 13:18:37.117 ThaliTest[2819:8632424] client session: connect
,2016-02-09 13:18:37.118 ThaliTest[2819:8632424] client session: stateChange:0->1 1455020314026.1069.hXy/gA==
,2016-02-09 13:18:37.178 ThaliTest[2819:8633953] server session: not connected 1455020314026.1069
,2016-02-09 13:18:37.284 ThaliTest[2819:8632106] multipeer session: reset timer
2016-02-09 13:18:37.285 ThaliTest[2819:8632106] multipeer session: stop timer
2016-02-09 13:18:37.285 ThaliTest[2819:8632106] multipeer session: start timer: 0x15648b80
2016-,02-09 13:18:37.285 ThaliTest[2819:8632106] server: disconnecting to refresh session (1455020314026.1069)
2016-02-09 13:18:37.285 ThaliTest[2819:8632106] server session: disconnect
2016-02-09 13:18:37.285 ThaliTest[2819:8632106] server session: stateChang,e:2->0 1455020314026.1069
,2016-02-09 13:18:37.288 ThaliTest[2819:8632106] server session: connect
,2016-02-09 13:18:37.289 ThaliTest[2819:8632106] server session: stateChange:0->1 1455020314026.1069
,2016-02-09 13:18:37.298 ThaliTest[2819:8632106] server: accepting invitation 1455020314026.1069
,2016-02-09 13:18:41.582 ThaliTest[2819:8633953] client session: connected
,2016-02-09 13:18:41.582 ThaliTest[2819:8633953] client session: stateChange:1->2 1455020314026.1069.hXy/gA==
,2016-02-09 13:18:41.606 ThaliTest[2819:8633953] server session: connected
2016-02-09 13:18:41.607 ThaliTest[2819:8633953] server session: stateChange:1->2 1455020314026.1069
,2016-02-09 13:18:41.823 ThaliTest[2819:8633851] client session: fireConnectCallback: 1455020314026.1069.hXy/gA==
2016-02-09 13:18:41.823 ThaliTest[2819:8633851] jxcore: connect: success
ok 117 Should be able to connect without error

ok 118 Port should be within range

ok 119 Second connect should succeed

,2016-02-09 13:18:41.849 ThaliTest[2819:8632106] client: relay established
2016-02-09 13:18:41.849 ThaliTest[2819:8632106] client: new accepted socket: 0x1b85f900
,2016-02-09 13:18:41.914 ThaliTest[2819:8632106] server relay: connected (to port: 50395)
,ok 120 the test messages should be equal

,ok 121 Second send should succeed

# setup

,2016-02-09 13:18:42.382 ThaliTest[2819:8632106] client: socket closed
2016-02-09 13:18:42.382 ThaliTest[2819:8632106] client relay: socket disconnected
2016-02-09 13:18:42.383 ThaliTest[2819:8632106] client relay: 0x1b85f900 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 13:18:42.383 ThaliTest[2819:8632106] client session: socket closed: 1455020314026.1069.hXy/gA==
2016-02-09 ,13:18:42.383 ThaliTest[2819:8632106] client session: onLinkFailure: 1455020314026.1069.hXy/gA==
2016-02-09 13:18:42.384 ThaliTest[2819:8632106] client session: disconnect
2016-02-09 13:18:42.384 ThaliTest[2819:8632106] client session: stateChange:2->0 14,55020314026.1069.hXy/gA==
,2016-02-09 13:18:42.393 ThaliTest[2819:8632106] client session: fireConnectionErrorEvent: 1455020314026.1069.hXy/gA==
,2016-02-09 13:18:43.145 ThaliTest[2819:8633852] server session: not connected 1455020314026.1069
,2016-02-09 13:18:44.347 ThaliTest[2819:8632106] client: lost peer: 1455020314026.1069.hXy/gA==
2016-02-09 13:18:44.347 ThaliTest[2819:8632106] client session: onPeerLost: 1455020314026.1069.hXy/gA==
[{"peerIdentifier":"1455020314026.1069.hXy/gA==","peerName":"(null)","peerAvailable":false}]

,calling stopBroadcasting

,2016-02-09 13:18:44.602 ThaliTest[2819:8632424] jxcore: stopBroadcasting
2016-02-09 13:18:44.602 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
2016-02-09 13:18:44.602 ThaliTest[2819:8632424] multipeer session: stop timer
2016-02-09 13:18:44.,603 ThaliTest[2819:8632424] client session: disconnect
2016-02-09 13:18:44.603 ThaliTest[2819:8632424] client session: stateChange:1->0 1455020304597.1069.F5tE5A==
2016-02-09 13:18:44.603 ThaliTest[2819:8632424] server session: disconnect
2016-02-09 13:,18:44.603 ThaliTest[2819:8632424] server session: stateChange:2->0 1455020314026.1069
,2016-02-09 13:18:44.616 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/78070CE7-0033-48AC-B558-3AB61E7E6C39/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 122 starting event should occur in right order

,2016-02-09 13:18:52.702 ThaliTest[2819:8632424] jxcore: startBroadcasting
,2016-02-09 13:18:52.704 ThaliTest[2819:8632424] server: starting flx5zPBhMQqht-ogO2lzJw.G89/9g==
2016-02-09 13:18:52.704 ThaliTest[2819:8632424] multipeer session: start timer: 0x1a7762b0
2016-02-09 13:18:52.705 ThaliTest[2819:8632424] THEMultipeerSessio,n initialized peer flx5zPBhMQqht-ogO2lzJw
2016-02-09 13:18:52.705 ThaliTest[2819:8632424] jxcore: startBroadcasting: success
ok 123 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 124 stopping event sh,ould occur in right order

About to call stopBroadcasting

,2016-02-09 13:18:52.708 ThaliTest[2819:8632424] jxcore: stopBroadcasting
2016-02-09 13:18:52.708 ThaliTest[2819:8632424] THEMultipeerSession stopping peer
2016-02-09 13:18:52.708 ThaliTest[2819:8632424] multipeer session: stop timer
2016-02-09 13:18:52.,709 ThaliTest[2819:8632424] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 125 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity


```
