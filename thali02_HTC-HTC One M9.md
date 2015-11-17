#### Test 503880196ac79ce_thali02_HTC-HTC One M9 Logs


```--------- beginning of main
11-17 18:30:09.160  1070  1626 D Process : killProcessQuiet, pid=5045
--------- beginning of system
11-17 18:30:09.160  1070  1626 I ActivityManager: Killing 5045:com.google.android.setupwizard/u0a62 (adj 15): empty #17
11-17 18:30:09.160  1070  1626 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
11-17 18:30:09.330  1070  1933 I ActivityManager: Recipient 5045
11-17 18:30:09.380  1070  1933 D Process : killProcessQuiet, pid=5045
11-17 18:30:09.380  1070  1933 W libprocessgroup: failed to open /acct/uid_10062/pid_5045/cgroup.procs: No such file or directory
11-17 18:30:09.380  1070  1933 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:30:09.710  1070  1328 D PMS     : acquireWL(18153fd1): PARTIAL_WAKE_LOCK  *alarm* 0x1 1070 1000 WorkSource{10027}
11-17 18:30:09.710  1070  1328 V AlarmManager: sending alarm PendingIntent{27240a36: PendingIntentRecord{36467d1e com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=53651, Int=0
11-17 18:30:09.710  4928  4928 D AlarmReceiver: ACTION_RESTART_INTENT
11-17 18:30:09.720  4928  4928 D LocalBluetoothProfile: getPriorityOnValue = 100
11-17 18:30:09.730  1070  1070 D PMS     : releaseWL(18153fd1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
11-17 18:30:09.720  4928  4928 D LocalBluetoothProfile: getPriorityOffValue = 0
11-17 18:30:09.720  4928  4928 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
11-17 18:30:09.720  4928  4928 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
11-17 18:30:09.760  4928  5412 D HtcModeClient: start the htcmodeservice thread
11-17 18:30:09.760  4928  5412 D HtcModeClient: initCanAgent
11-17 18:30:09.760  4928  5412 I CANMesgAgentLocalSocket: CANAgent Id = 0
11-17 18:30:09.760  4928  5412 D HtcModeClient: sense info: version = none, id = 2
11-17 18:30:09.760  4928  5412 D HtcModeClient: display info: width = 1080, height = 1776
11-17 18:30:09.760  4928  5412 D HtcModeClient: display info: mode = 10
11-17 18:30:09.760  4928  4928 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
11-17 18:30:09.760  4928  4928 D HtcModeClient: connectState: BT_TURNON_BYME = false
11-17 18:30:09.760  4928  4928 D HtcModeClient: connectState: CONNECTION_READY = false
11-17 18:30:09.760  4928  4928 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
11-17 18:30:09.760  4928  4928 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
11-17 18:30:09.760  4928  4928 D HtcModeClient: connectState: PHONE_PULGIN = false
11-17 18:30:09.760  4928  4928 D HtcModeClient: connectState: Force_AWAKE = false
11-17 18:30:09.760  4928  4928 D HtcModeClient: connectState: PHONE_PULGIN = true
11-17 18:30:09.760  4928  4928 D HtcModeClient: connectState: POWERCONNECTED_READY = true
11-17 18:30:10.050  1070  1109 I ActivityManager: Waited long enough for: ServiceRecord{35d927a9 u0 com.htc.club/com.mcrm.autonotification.NotificationService}
,11-17 18:30:10.760  1070  1109 I ActivityManager: Waited long enough for: ServiceRecord{10de4853 u0 com.nero.android.htc.sync/.PowerDisconService}
11-17 18:30:11.030  1809  3133 I SocialFeedProvider: +disConnect socialManager
11-17 18:30:11.030  1809  3133 I SocialFeedProvider: disconnect socialManager
11-17 18:30:11.040  1809  3133 I SocialFeedProvider: -disConnect socialManager
11-17 18:30:11.110  1070  1328 I ActivityManager: Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5416 uid=10059 gids={50059, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a
11-17 18:30:11.110  1070  1328 D PMS     : acquireWL(2b845c2f): PARTIAL_WAKE_LOCK  *alarm* 0x1 1070 1000 WorkSource{10042}
11-17 18:30:11.110  1070  1328 V AlarmManager: sending alarm PendingIntent{16cbc23c: PendingIntentRecord{582bc5 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1447781411103, Int=0
11-17 18:30:11.110  1070  1070 D PMS     : releaseWL(2b845c2f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10042}
11-17 18:30:11.120  5414  5430 E cutils-trace: Error opening trace file: Permission denied (13)
11-17 18:30:11.190  5414  5414 D CustomizationManager: ====startRecUseTime====
11-17 18:30:11.190  5414  5414 D htc.customization.log.level:  is 
11-17 18:30:11.190  5414  5414 W CustomizationLogLevel: Level value is invalid, use default level 2
11-17 18:30:11.250  5414  5414 D CustomizationManager:  Read ACC file spent 0.035 (s)
11-17 18:30:11.250  5414  5414 D CIDMapFileReader: Parsing tag item name = HTC__001
11-17 18:30:11.250  5414  5414 D CIDMapFileReader: Parsing tag item name = HTC__002
11-17 18:30:11.250  5414  5414 D CIDMapFileReader: Parsing tag item name = HTC__016
11-17 18:30:11.250  5414  5414 D CIDMapFileReader: Parsing tag item name = HTC__031
11-17 18:30:11.250  5414  5414 D CIDMapFileReader: Parsing tag item name = HTC__032
11-17 18:30:11.250  5414  5414 D CIDMapFileReader: Parsing tag item name = HTC__102
11-17 18:30:11.250  5414  5414 D CIDMapFileReader: Parsing tag item name = HTC__A07
11-17 18:30:11.250  5414  5414 D CIDMapFileReader: Parsing tag item name = HTC__J15
11-17 18:30:11.250  5414  5414 D CIDMapFileReader: Parsing tag item name = HTC__M27
11-17 18:30:11.250  5414  5414 D CIDMapFileReader: Parsing tag item name = HTC__Y13
11-17 18:30:11.250  5414  5414 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
11-17 18:30:11.250  5414  5414 I CustomizationCIDLoader: Parsing tag category name = application
11-17 18:30:11.250  5414  5414 I CustomizationCIDLoader: Parsing tag category name = system
11-17 18:30:11.250  5414  5414 I CustomizationCIDLoader: Parsing tag category name = Settings
11-17 18:30:11.250  5414  5414 I CustomizationCIDLoader: Parsing tag category name = ACC
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 42507
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 21902
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 23420
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 22299
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 24002
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 23210
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 23205
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 23806
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 23430
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 23408
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 27205
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 23210:D:0:0
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
11-17 18:30:11.260  5414  5414 I CustomizationCIDLoader: Parsing tag category name = AudioService
11-17 18:30:11.260  5414  5414 D CustomizationManager:  Read CID file spent 0.064 (s)
11-17 18:30:11.260  5414  5414 D CustomizationManager:  All configurations done spent 0.064 (s)
11-17 18:30:11.270  1070  1943 I art     : Explicit concurrent mark sweep GC freed 28230(1458KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.855ms total 135.962ms
11-17 18:30:11.300  1070  1349 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 5414 on display 0
11-17 18:30:11.300  1070  1349 W asset   : Copying FileAsset 0x5596c24ae0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
11-17 18:30:11.300  1070  1147 D PMS     : acquireHCC(3f048c4b): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1070 1000 null
11-17 18:30:11.300  1070  1147 D PMS     : acquireHCC(4b0c628): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1070 1000 null
11-17 18:30:11.300  1070  1349 D PMS     : acquireWL(b0da227): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1070 1000 null
11-17 18:30:11.300  1070  1119 I AnimationUtil: isHTCRecent(HelloWorld/Recent screens.)/1
11-17 18:30:11.310  1809  1809 I FeedHostManager: [onPause]
11-17 18:30:11.310  1809  1809 I FeedProviderManager: onPause
11-17 18:30:11.310  1809  1809 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@814b768
11-17 18:30:11.310  1809  2868 I SocialFeedProvider: +onPause
11-17 18:30:11.310  1809  2868 I SocialFeedProvider: -onPause
11-17 18:30:11.310  1070  1892 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
11-17 18:30:11.320  1070  1943 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5453 uid=10193 gids={50193, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:30:11.330   553   553 I art     : Explicit concurrent mark sweep GC freed 8665(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 141KB/4MB, paused 232us total 10.120ms
11-17 18:30:11.340   553   553 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 141KB/4MB, paused 104us total 8.758ms
11-17 18:30:11.350   553   553 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 141KB/4MB, paused 103us total 7.530ms
11-17 18:30:11.360  5453  5453 W asset   : Copying FileAsset 0xabe3e398 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
11-17 18:30:11.370  1809  1809 I TrimMemoryManager: [trimMemory] 20
11-17 18:30:11.380  1070  1117 D StatusBarManagerService: setSystemUiVisibility(0x0)
11-17 18:30:11.380  1070  1117 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:11.380  1070  1117 D StatusBarManagerService: hiding MENU key
11-17 18:30:11.380  1430  1430 I PhoneStatusBar: setSystemUiNavVisibility(false,false,false)
11-17 18:30:11.400  5416  5416 I ConfigManager: [DM]ConfigManager: ConfigManager init().
11-17 18:30:11.410  5453  5453 I WebViewFactory: Loading com.google.android.webview version 37 (1602158-arm) (code 111201)
11-17 18:30:11.410  5416  5481 I SocialManager[SocialBiLogHelper]: action: com.htc.sense.hsp.HANDLE_ULOG
11-17 18:30:11.410  5416  5481 I SocialManager[SocialBiLogHelper]: last commit ulog time 1447741041110
11-17 18:30:11.410  5416  5481 I SocialManager[SocialBiLogHelper]: skip commit this time
11-17 18:30:11.410  1070  1635 I ActivityManager: Killing 5070:com.htc.themepicker/u0a59 (adj 15): empty #17
11-17 18:30:11.410  1070  1635 D Process : killProcessQuiet, pid=5070
11-17 18:30:11.410  1070  1635 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
11-17 18:30:11.440  5416  5479 I ConfigManager: [DM]ConfigManager: init() => DM PutProfile state is PUT_PROFILE_INIT trigger putProfile process.
11-17 18:30:11.440  5416  5480 I ConfigManager: [DM]ConfigManager: init() => DM GetConfig state is GET_CONFIG_INIT trigger getAppConfig process.
11-17 18:30:11.460  5416  5479 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
11-17 18:30:11.470  5416  5480 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447781411485
11-17 18:30:11.490  5416  5480 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
11-17 18:30:11.490  5416  5480 E ConfigManager: [DM]ConfigManager: Error in init ConfigManager. com.htc.lib1.dm.exception.DMNoConfigException: Cannot load Config from server and has no local cache.
11-17 18:30:11.490  5416  5480 W System.err: com.htc.lib1.dm.exception.DMNoConfigException: Cannot load Config from server and has no local cache.
11-17 18:30:11.490  5416  5480 W System.err: 	at com.htc.lib1.dm.solo.ConfigManager.getAppConfig(ConfigManager.java:365)
11-17 18:30:11.490  5416  5480 W System.err: 	at com.htc.lib1.dm.solo.ConfigManager.access$500(ConfigManager.java:23)
11-17 18:30:11.490  5416  5480 W System.err: 	at com.htc.lib1.dm.solo.ConfigManager$2.run(ConfigManager.java:96)
11-17 18:30:11.490  5416  5480 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:11.490  5416  5480 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:11.490  5416  5480 W System.err: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:11.520  1070  1794 I ActivityManager: Recipient 5070
11-17 18:30:11.520  1070  1794 D Process : killProcessQuiet, pid=5070
11-17 18:30:11.520  1070  1794 W libprocessgroup: failed to open /acct/uid_10059/pid_5070/cgroup.procs: No such file or directory
11-17 18:30:11.520  1070  1794 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,11-17 18:30:11.530  5453  5453 I LibraryLoader: Loading: webviewchromium
,11-17 18:30:11.580  5453  5453 I LibraryLoader: Time to load native libraries: 46 ms (timestamps 5476-5522),
11-17 18:30:11.580  5453  5453 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-17 18:30:11.590  5453  5453 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c584a33},
11-17 18:30:11.590  5453  5453 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-17 18:30:11.590  5453  5453 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0,
,11-17 18:30:11.600  5453  5453 I BrowserStartupController: Initializing chromium process, renderers=0,
,11-17 18:30:11.600  5453  5453 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,11-17 18:30:11.610  5453  5484 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,11-17 18:30:11.620  5453  5453 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,11-17 18:30:11.620  5453  5453 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46784 len=2953
11-17 18:30:11.620  5453  5453 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:34 off:229540 len:643667
,11-17 18:30:11.620  5453  5488 D BluetoothAdapter: 514150896: getState() :  mService = null. Returning STATE_OFF
,11-17 18:30:11.640  5453  5453 I Adreno  : EGLInit: QTI Build: 02/02/15, 7356efb, I9716ce229b,
,11-17 18:30:11.690  5453  5494 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,11-17 18:30:11.690  5453  5453 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup,
,11-17 18:30:11.700  5453  5453 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,11-17 18:30:11.700  5453  5453 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-17 18:30:11.710  5453  5453 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC,
,11-17 18:30:11.720  5453  5453 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:11.720  5453  5453 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,11-17 18:30:11.770  5453  5453 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,11-17 18:30:11.770  4928  5412 I HtcModeClient: handler message = 4011
11-17 18:30:11.770  4928  5412 D HtcModeClient: getConnectionCheckCount first 0
,11-17 18:30:11.770  4928  5412 D HtcModeClient: getConnectionCheckCount count = 3
11-17 18:30:11.770  4928  5412 E HtcModeClient: Check connection and retry 4 times.
11-17 18:30:11.770  4928  5412 D HtcModeClient: setConnectionCheckCount count = 4
11-17 18:30:11.770  4928  5412 D HtcModeClient: setupRestart delayedTime = 3000
,11-17 18:30:11.780  4928  4928 D HtcModeClient: setBtPriority priority = on
11-17 18:30:11.780  4928  4928 D HtcModeClient: unbindBlueToothService
11-17 18:30:11.780  4928  4928 D HtcModeClient: Don't start project servcice
,11-17 18:30:11.780  4928  4928 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
11-17 18:30:11.780  4928  4928 D HtcModeClient: connectState: CONNECTION_READY = false
11-17 18:30:11.780  4928  4928 D SilentMusic: call stop
11-17 18:30:11.780  4928  4928 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,11-17 18:30:11.780  4928  5413 W CANMesgAgentLocalSocket: read the terminate packet, so break
,11-17 18:30:11.790  4928  4928 D HtcModeClient: onDestroy,
11-17 18:30:11.790  1070  1794 D Process : killProcessQuiet, pid=4704
,11-17 18:30:11.790  1070  1794 I ActivityManager: Killing 4704:com.htc.demoflopackageinstaller/u0a12 (adj 15): empty #17
11-17 18:30:11.790  1070  1794 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
,11-17 18:30:11.800  5453  5453 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@121fd29e, mServedView=org.apache.cordova.engine.SystemWebView{2ded017f VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2b98854c
11-17 18:30:11.800  1070  1945 I InputMethodManagerService: Disable input method client, pid=1809
11-17 18:30:11.800  1070  1945 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
11-17 18:30:11.800  1070  1945 I InputMethodManagerService: Enable input method client, pid=5453
11-17 18:30:11.800  1430  1430 I PhoneStatusBar: setImeWindowStatus(false,false)
,11-17 18:30:11.840  5453  5453 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,11-17 18:30:11.840  5453  5512 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,11-17 18:30:11.860  5453  5453 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,11-17 18:30:11.870  1070  1646 I ActivityManager: Recipient 4704
,11-17 18:30:11.880  5453  5504 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font,
11-17 18:30:11.880  5453  5504 I chromium: 
,11-17 18:30:11.890  5453  5504 I chromium: [INFO:SkFontConfigInterface_android.cpp(227)] ---- system font and fallback font files specify a duplicate font /system/fonts/XinGothic-HTC-Regular.ttf, skipping the second occurrence,
11-17 18:30:11.890  5453  5504 I chromium: [INFO:SkFontConfigInterface_android.cpp(227)] ---- system font and fallback font files specify a duplicate font /system/fonts/XinGothic-HTC-Bold.ttf, skipping the second occurrence
,11-17 18:30:11.900  1070  1119 I ActivityManager: Displayed com.example.hello/.MainActivity: +590ms
11-17 18:30:11.900  1070  1794 D PMS     : releaseWL(b0da227): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
11-17 18:30:11.900  1070  1646 D Process : killProcessQuiet, pid=4704
11-17 18:30:11.900  1070  1646 W libprocessgroup: failed to open /acct/uid_10012/pid_4704/cgroup.procs: No such file or directory
11-17 18:30:11.900  1070  1646 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,11-17 18:30:11.920  5453  5453 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
11-17 18:30:11.920  5453  5453 I chromium: 
,11-17 18:30:11.970  5453  5514 D jxcore_app_log: JniHelper::setJavaVM(0xab0799d0), pthread_self() = -1407679944,
11-17 18:30:11.970  5453  5514 D JX-Cordova: jxcore cordova android initializing
,11-17 18:30:11.990  5453  5453 W jxcore-log: Initializing JXcore engine,
11-17 18:30:11.990  5453  5453 W jxcore-log: JXcore engine is ready
,11-17 18:30:11.990  5453  5453 W jxcore-log: Starting JXcore engine
,11-17 18:30:12.080  5453  5453 W jxcore-log: Platform android,
11-17 18:30:12.080  5453  5453 W jxcore-log: 
11-17 18:30:12.080  5453  5453 W jxcore-log: Process ARCH arm
11-17 18:30:12.080  5453  5453 W jxcore-log: 
,11-17 18:30:12.100  5453  5453 I jxcore-log: JXcore Cordova bridge is ready!,
11-17 18:30:12.100  5453  5453 I jxcore-log: 
11-17 18:30:12.100  5453  5453 W jxcore-log: JXcore engine is started
,11-17 18:30:12.130  5453  5453 E jxcore-log: >> HTC-HTC One M9,
11-17 18:30:12.130  5453  5453 E jxcore-log: 
11-17 18:30:12.130  5453  5453 I jxcore-log: Total memory 2860257280
11-17 18:30:12.130  5453  5453 I jxcore-log: 
11-17 18:30:12.130  5453  5453 I jxcore-log: Free memory 181616640
11-17 18:30:12.130  5453  5453 I jxcore-log: 
11-17 18:30:12.130  5453  5453 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:30:12.130  5453  5453 I jxcore-log: 
11-17 18:30:12.130  5453  5453 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:30:12.130  5453  5453 I jxcore-log: 
,11-17 18:30:12.140  5453  5453 I jxcore-log: userPath [ 'www' ]
11-17 18:30:12.140  5453  5453 I jxcore-log: 
,11-17 18:30:12.140  5453  5453 I jxcore-log: Size 1080 1776
11-17 18:30:12.140  5453  5453 I jxcore-log: 
,11-17 18:30:12.140  5453  5453 I jxcore-log: Screen Brightness 142
11-17 18:30:12.140  5453  5453 I jxcore-log: 
11-17 18:30:12.140  5453  5453 E jxcore-log: Dummy Error Log.
11-17 18:30:12.140  5453  5453 E jxcore-log: ,
,11-17 18:30:12.300  1070  1147 D PMS     : releaseHCC(3f048c4b): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,11-17 18:30:12.300  1070  1147 D PMS     : releaseHCC(4b0c628): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,11-17 18:30:12.600  1070  1109 I ActivityManager: Waited long enough for: ServiceRecord{1e4eb84d u0 com.htc.music/com.htc.musicenhancer.EnhancerService}
,11-17 18:30:12.680  5453  5453 I jxcore-log: getBuffer is called!!!!
11-17 18:30:12.680  5453  5453 I jxcore-log: 
,11-17 18:30:13.290  4647  5516 W MediaManager: [DualLensScanUtil]	mmpCursor count is 0
,11-17 18:30:13.290  1070  1946 D Process : killProcessQuiet, pid=4754
11-17 18:30:13.290  1070  1946 I ActivityManager: Killing 4754:com.htc.sdm/u0a64 (adj 15): empty #17
11-17 18:30:13.290  1070  1946 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
,11-17 18:30:13.360  1070  1790 I ActivityManager: Recipient 4754
,11-17 18:30:13.400  1070  1790 D Process : killProcessQuiet, pid=4754,
11-17 18:30:13.400  1070  1790 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 ,
,11-17 18:30:13.400  1070  1790 W libprocessgroup: failed to open /acct/uid_10064/pid_4754/cgroup.procs: No such file or directory
,11-17 18:30:13.670  1070  1143 D AutomaticBrightnessController: setAmbientLux to brighter = 1.0,
,11-17 18:30:14.430  1070  1945 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2283, uid=10020, userID:0
,11-17 18:30:14.430  1070  1626 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2283, uid=10020, userID:0
,11-17 18:30:14.440  2283  4456 I CheckinService: Done disabling old GoogleServicesFramework version
,11-17 18:30:14.440  1070  1943 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2283, uid=10020, userID:0
,11-17 18:30:14.770  1070  1328 D PMS     : acquireWL(33f56cc): PARTIAL_WAKE_LOCK  *alarm* 0x1 1070 1000 WorkSource{10027},
11-17 18:30:14.780  1070  1328 V AlarmManager: sending alarm PendingIntent{1c324d15: PendingIntentRecord{36467d1e com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=58719, Int=0
,11-17 18:30:14.780  4928  4928 D AlarmReceiver: ACTION_RESTART_INTENT
,11-17 18:30:14.780  4928  4928 D LocalBluetoothProfile: getPriorityOnValue = 100,
11-17 18:30:14.780  4928  4928 D LocalBluetoothProfile: getPriorityOffValue = 0
11-17 18:30:14.780  1070  1070 D PMS     : releaseWL(33f56cc): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
11-17 18:30:14.780  4928  4928 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
11-17 18:30:14.780  4928  4928 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1),
,11-17 18:30:14.800  4928  5518 D HtcModeClient: start the htcmodeservice thread
,11-17 18:30:14.800  4928  5518 D HtcModeClient: initCanAgent
11-17 18:30:14.800  4928  5518 I CANMesgAgentLocalSocket: CANAgent Id = 0
11-17 18:30:14.800  4928  5518 D HtcModeClient: sense info: version = none, id = 2
11-17 18:30:14.800  4928  5518 D HtcModeClient: display info: width = 1080, height = 1776
11-17 18:30:14.800  4928  5518 D HtcModeClient: display info: mode = 10
,11-17 18:30:14.810  4928  4928 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
11-17 18:30:14.810  4928  4928 D HtcModeClient: connectState: BT_TURNON_BYME = false
11-17 18:30:14.810  4928  4928 D HtcModeClient: connectState: CONNECTION_READY = false
11-17 18:30:14.810  4928  4928 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
11-17 18:30:14.810  4928  4928 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
11-17 18:30:14.810  4928  4928 D HtcModeClient: connectState: PHONE_PULGIN = false
11-17 18:30:14.810  4928  4928 D HtcModeClient: connectState: Force_AWAKE = false
11-17 18:30:14.810  4928  4928 D HtcModeClient: connectState: PHONE_PULGIN = true
11-17 18:30:14.810  4928  4928 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,11-17 18:30:16.820  4928  5518 I HtcModeClient: handler message = 4011
11-17 18:30:16.820  4928  5518 D HtcModeClient: getConnectionCheckCount first 0
,11-17 18:30:16.820  4928  5518 D HtcModeClient: getConnectionCheckCount count = 4
11-17 18:30:16.820  4928  5518 E HtcModeClient: Check connection and retry 5 times.
11-17 18:30:16.820  4928  5518 D HtcModeClient: setConnectionCheckCount count = 5
11-17 18:30:16.820  4928  5518 D HtcModeClient: setupRestart delayedTime = 3000
11-17 18:30:16.820  4928  4928 D HtcModeClient: setBtPriority priority = on
,11-17 18:30:16.820  4928  4928 D HtcModeClient: unbindBlueToothService
11-17 18:30:16.820  4928  4928 D HtcModeClient: Don't start project servcice
,11-17 18:30:16.830  4928  4928 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
11-17 18:30:16.830  4928  4928 D HtcModeClient: connectState: CONNECTION_READY = false
11-17 18:30:16.830  4928  4928 D SilentMusic: call stop,
11-17 18:30:16.830  4928  4928 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,11-17 18:30:16.830  4928  5519 W CANMesgAgentLocalSocket: read the terminate packet, so break,
11-17 18:30:16.830  4928  4928 D HtcModeClient: onDestroy
,11-17 18:30:17.010  1608  2013 D AutoSetting: service - handleMessage() stop self,
,11-17 18:30:17.040  1608  2013 D AutoSetting: service - handleMessage() quit looper,
11-17 18:30:17.040  1608  1608 D AutoSetting: service - onDestroy() END
,11-17 18:30:17.150  1070  1089 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
11-17 18:30:17.150  1070  1089 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
11-17 18:30:17.150  1070  1089 W Settings:Agent: MONITOR_LOG
11-17 18:30:17.150  1070  1089 W Settings:Agent: name: bluetooth_on
11-17 18:30:17.150  1070  1089 W Settings:Agent: value: 0
11-17 18:30:17.150  1070  1089 W Settings:Agent: >> traceCallingStack()
11-17 18:30:17.150  1070  1089 W Settings:Agent: Process.myPid(): 1070
11-17 18:30:17.150  1070  1089 W Settings:Agent: Process.myTid(): 1089
11-17 18:30:17.150  1070  1089 W Settings:Agent: Process.myUid(): 1000
11-17 18:30:17.150  1070  1089 W Settings:Agent: 
11-17 18:30:17.150  1070  1089 W Settings:Agent: 
11-17 18:30:17.150  1070  1089 W System.err: java.lang.Throwable: stack dump
11-17 18:30:17.160  1070  1089 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
11-17 18:30:17.160  1070  1089 W System.err: 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
11-17 18:30:17.160  1070  1089 W System.err: 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
11-17 18:30:17.160  1070  1089 W System.err: 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
11-17 18:30:17.160  1070  1089 W System.err: 	at android.provider.Settings$Global.putString(Settings.java:7403)
11-17 18:30:17.160  1070  1089 W System.err: 	at android.provider.Settings$Global.putInt(Settings.java:7503)
11-17 18:30:17.160  1070  1089 W System.err: 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:360)
11-17 18:30:17.160  1070  1089 W System.err: 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:644)
11-17 18:30:17.160  1070  1089 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
11-17 18:30:17.160  1070  1089 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:30:17.160  1070  1089 W Settings:Agent: 
11-17 18:30:17.160  1070  1089 W Settings:Agent: << traceCallingStack(): 12(ms)
11-17 18:30:17.160  1070  1118 D BluetoothManagerService: Message: 2
,11-17 18:30:17.180  5453  5453 D WifiManager: setWifiEnabled: Base Package Name=com.example.hello, uid=10193
11-17 18:30:17.180  1070  1341 D WifiService: New client listening to asynchronous messages
11-17 18:30:17.180  1070  1070 E WifiTrafficPoller: ADD_CLIENT: 9
,11-17 18:30:17.180  1070  1900 D WifiService: setWifiEnabled: false pid=5453, uid=10193
,11-17 18:30:17.180  1070  1900 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 18:30:17.190  1070  1900 W Settings:Agent: MONITOR_LOG,
,11-17 18:30:17.190  1070  1900 I WifiService: isSprintWifiRestricted(): false,
,11-17 18:30:17.190  1070  1900 W Settings:Agent: name: wifi_on,
11-17 18:30:17.190  1070  1900 I WifiService: isMdmWifiRestricted(): false
,11-17 18:30:17.190  1070  1900 W Settings:Agent: value: 0
11-17 18:30:17.190  1070  1900 W Settings:Agent: >> traceCallingStack()
,11-17 18:30:17.190  1070  1900 W Settings:Agent: Process.myPid(): 1070
11-17 18:30:17.190  1070  1900 W Settings:Agent: Process.myTid(): 1900,
11-17 18:30:17.190  1070  1900 W Settings:Agent: Process.myUid(): 1000
11-17 18:30:17.190  1070  1900 W Settings:Agent: ,
11-17 18:30:17.190  1070  1900 W Settings:Agent: 
,11-17 18:30:17.190  1070  1900 W System.err: java.lang.Throwable: stack dump
11-17 18:30:17.190  1070  1900 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
,11-17 18:30:17.190  1070  1900 W System.err: 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
11-17 18:30:17.190  1070  1900 W System.err: ,	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
11-17 18:30:17.190  1070  1900 W System.err: 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422),
11-17 18:30:17.190  1070  1900 W System.err: 	at android.provider.Settings$Global.putString(Settings.java:7403)
11-17 18:30:17.190  1070  1900 W System.err: 	at android.provider.Settings$Global.putInt(Settings.java:7503)
11-17 18:30:17.190  1070  1900 W System.err: 	,at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151)
11-17 18:30:17.190  1070  1900 W System.err: 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
11-17 18:30:17.190  1070  1900 W System.err: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1170)
11-17 18:30:17.190  1070  1900 W System.err: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
,11-17 18:30:17.190  1070  1900 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:30:17.190  1070  1900 W Settings:Agent: 
11-17 18:30:17.190  1070  1900 W Settings:Agent: << traceCallingStack(): 2(ms)
11-17 18:30:17.190  1070  1341 D WifiController: handleMessage: E msg.what=155656
11-17 18:30:17.190  5453  5453 I jxcore-log: ****TEST TOOK:  5064  ms ****
11-17 18:30:17.190  5453  5453 I jxcore-log: 
,11-17 18:30:17.190  5453  5453 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:30:17.190  5453  5453 I jxcore-log: 
11-17 18:30:17.190  1070  1341 D WifiController: processMsg: ApStaDisabledState
11-17 18:30:17.200  1070  1341 D WifiController: handleMessage: X
,11-17 18:30:17.540  5521  5524 E cutils-trace: Error opening trace file: Permission denied (13)
,11-17 18:30:17.610  5521  5521 D CustomizationManager: ====startRecUseTime====
,11-17 18:30:17.610  5521  5521 D htc.customization.log.level:  is 
11-17 18:30:17.610  5521  5521 W CustomizationLogLevel: Level value is invalid, use default level 2
,11-17 18:30:17.670  5521  5521 D CustomizationManager:  Read ACC file spent 0.040 (s),
11-17 18:30:17.670  5521  5521 D CIDMapFileReader: Parsing tag item name = HTC__001
11-17 18:30:17.670  5521  5521 D CIDMapFileReader: Parsing tag item name = HTC__002
11-17 18:30:17.670  5521  5521 D CIDMapFileReader: Parsing tag item name = HTC__016
11-17 18:30:17.670  5521  5521 D CIDMapFileReader: Parsing tag item name = HTC__031
11-17 18:30:17.670  5521  5521 D CIDMapFileReader: Parsing tag item name = HTC__032
11-17 18:30:17.670  5521  5521 D CIDMapFileReader: Parsing tag item name = HTC__102
11-17 18:30:17.670  5521  5521 D CIDMapFileReader: Parsing tag item name = HTC__A07
,11-17 18:30:17.670  5521  5521 D CIDMapFileReader: Parsing tag item name = HTC__J15
11-17 18:30:17.670  5521  5521 D CIDMapFileReader: Parsing tag item name = HTC__M27
11-17 18:30:17.670  5521  5521 D CIDMapFileReader: Parsing tag item name = HTC__Y13
11-17 18:30:17.670  5521  5521 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
11-17 18:30:17.670  5521  5521 I CustomizationCIDLoader: Parsing tag category name = application
11-17 18:30:17.670  5521  5521 I CustomizationCIDLoader: Parsing tag category name = system
11-17 18:30:17.670  5521  5521 I CustomizationCIDLoader: Parsing tag category name = Settings
11-17 18:30:17.670  5521  5521 I CustomizationCIDLoader: Parsing tag category name = ACC
11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 42507
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 21902
11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003,
11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 23420
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 22299
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 24002
11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 23210
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 23205
11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 23806
11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 23430
11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 23408,
11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 27205,
11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 23210:D:0:0
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
,11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
11-17 18:30:17.680  5521  5521 I CustomizationCIDLoader: Parsing tag category name = AudioService
,11-17 18:30:17.680  5521  5521 D CustomizationManager:  Read CID file spent 0.068 (s)
11-17 18:30:17.680  5521  5521 D CustomizationManager:  All configurations done spent 0.068 (s)
,11-17 18:30:17.730  1070  1790 D PackageManager: deletePackageAsUser: pkg=com.example.hello, pid=5521, uid=2000 userid=0,
11-17 18:30:17.730  1070  1109 D Process : killProcessQuiet, pid=5453
,11-17 18:30:17.730  1070  1109 I ActivityManager: Force stopping com.example.hello appid=10193 user=-1: uninstall pkg
11-17 18:30:17.730  1070  1109 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6354 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6152 
,11-17 18:30:17.730  1070  1109 I ActivityManager: Killing 5453:com.example.hello/u0a193 (adj 0): stop com.example.hello
,11-17 18:30:17.780  1070  1153 W PackageSettings: Skipping PackageSetting{2dbbf7f6 com.test.thalitest/10192} due to missing metadata,
,11-17 18:30:17.890  1070  1089 I ActivityManager: Recipient 5453
,11-17 18:30:17.890  1553  1553 E InputEventReceiver: Looper::removeFd(34) is failed, result(0), input channel 'ClientState{df29534 uid 10193 pid 5453} (c)'
11-17 18:30:17.890  1070  1341 D WifiService: Client connection lost with reason: 4
11-17 18:30:17.890   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
11-17 18:30:17.890  1070  1628 I WindowState: WIN DEATH: Window{16b74007 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:30:17.940  1070  1109 W ActivityManager: Force removing ActivityRecord{694bf41 u0 com.example.hello/.MainActivity t67}: app died, no saved state,
,11-17 18:30:17.950  1070  1153 I ActivityManager: Force stopping com.example.hello appid=10193 user=0: pkg removed
,11-17 18:30:17.960  1070  1089 W ActivityManager: Spurious death for ProcessRecord{11eed282 5453:com.example.hello/u0a193}, curProc for 5453: null
,11-17 18:30:17.980  2023  2379 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.,
11-17 18:30:17.980  1070  1945 D PMS     : acquireWL(395f6d93): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 2023 10020 WorkSource{10020 com.google.android.gms}
11-17 18:30:17.980  1070  1943 D PMS     : releaseWL(395f6d93): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:30:17.990  1809  1809 I FeedHostManager: [onResume]
11-17 18:30:17.990  1500  1500 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
11-17 18:30:17.990  1809  1809 I FeedProviderManager: onResume
11-17 18:30:17.990  1500  1500 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
11-17 18:30:17.990  1809  2868 I SocialFeedProvider: +onResume
11-17 18:30:17.990  1809  2868 I SocialFeedProvider: updateAccounts - Accounts is no change
11-17 18:30:17.990  1809  2868 I SocialFeedProvider: -onResume
11-17 18:30:17.990  1500  1500 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
11-17 18:30:17.990  1809  1809 I ConnectivityHelper: [getCurrentConnectionType] no network connection
11-17 18:30:17.990  2677  2677 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
11-17 18:30:17.990  2677  2677 D [MirrorLinkServer]MirrorLinkServer: ACTION_PACKAGE_REMOVED intent received
11-17 18:30:18.000  2677  2677 D [MirrorLinkServer]MirrorLinkServer: Counter : 1
11-17 18:30:18.000  2677  2677 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
11-17 18:30:18.000  1070  1331 W SystemReader: Cannot find grip_rejection_width, use default value instead
11-17 18:30:18.010  1070  1117 D StatusBarManagerService: setSystemUiVisibility(0x700)
11-17 18:30:18.010  1070  1117 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:18.010  1070  1117 D StatusBarManagerService: hiding MENU key
11-17 18:30:18.010  3825  3825 I art     : Explicit concurrent mark sweep GC freed 562(36KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 3MB/5MB, paused 399us total 45.410ms
,11-17 18:30:18.010  1987  2359 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,11-17 18:30:18.010  1070  1108 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
11-17 18:30:18.010  2129  5539 D VoicemailCleanupService: Cleaning up data for package: com.example.hello
,11-17 18:30:18.020  1070  1794 I ActivityManager: Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver: pid=5540 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a
11-17 18:30:18.020  1809  1809 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,11-17 18:30:18.020  2677  2677 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_REMOVED
11-17 18:30:18.020  2677  2677 D [MirrorLinkServer]MirrorLinkServer: Application Removed
11-17 18:30:18.020  2677  2677 D [MirrorLinkServer]MirrorLinkServer:  Application removed : com.example.hello
11-17 18:30:18.020  2677  2677 D [MirrorLinkServer]d: onApplicationRemoved
11-17 18:30:18.020  2677  2677 I [MirrorLinkServer]d: Package name found : com.example.hello
,11-17 18:30:18.030  2677  5549 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
11-17 18:30:18.030  1809  1809 I ThreadedRenderer: Defer allocateBuffers to drawing time
11-17 18:30:18.030  1809  2108 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
11-17 18:30:18.030  1809  2108 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,11-17 18:30:18.030  1070  1900 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5453 uid 10193,
,11-17 18:30:18.030  1070  1900 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
11-17 18:30:18.040  1987  2359 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
11-17 18:30:18.030  1070  1900 I InputMethodManagerService: Enable input method client, pid=1809
11-17 18:30:18.040  2677  2677 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
11-17 18:30:18.040  2677  2677 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
11-17 18:30:18.040  2677  2677 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
11-17 18:30:18.040  2677  2677 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
11-17 18:30:18.040  2677  2677 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
,11-17 18:30:18.070  1987  2359 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,11-17 18:30:18.070  1774  1774 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
11-17 18:30:18.070  1070  1108 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,11-17 18:30:18.070  1070  1117 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
11-17 18:30:18.070  1070  1117 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:18.070  1070  1117 D StatusBarManagerService: hiding MENU key
,11-17 18:30:18.110  1809  2223 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447781418124,
11-17 18:30:18.120  1070  1070 I art     : Explicit concurrent mark sweep GC freed 21939(1662KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 15MB/23MB, paused 1.705ms total 151.823ms
11-17 18:30:18.120  1070  1153 I art     : WaitForGcToComplete blocked for 146.605ms for cause Explicit
,11-17 18:30:18.120  1070  1349 I ActivityManager: Killing 5111:com.htc.calendar/u0a7 (adj 15): empty #17
11-17 18:30:18.120  1070  1349 D Process : killProcessQuiet, pid=5111,
11-17 18:30:18.120  1070  1349 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,11-17 18:30:18.140  1809  2223 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
11-17 18:30:18.140  1987  2359 E ExternalAccountType: Unsupported attribute readOnly
,11-17 18:30:18.170  1809  2029 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.,
,11-17 18:30:18.180  1809  2223 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447781418190
,11-17 18:30:18.200  1809  2223 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.,
,11-17 18:30:18.220  1070  2122 I ActivityManager: Recipient 5111
,11-17 18:30:18.230  1809  2030 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:30:18.230  1070  2122 D Process : killProcessQuiet, pid=5111
11-17 18:30:18.230  1070  2122 W libprocessgroup: failed to open /acct/uid_10007/pid_5111/cgroup.procs: No such file or directory
11-17 18:30:18.230  1070  2122 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,11-17 18:30:18.230  1809  1809 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED,
,11-17 18:30:18.230  1608  5563 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
,11-17 18:30:18.240  1809  2223 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447781418254,
,11-17 18:30:18.240  3825  5565 I UpdateIcingCorporaServi: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
11-17 18:30:18.250  1608  5563 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,11-17 18:30:18.250  1070  1153 I art     : Explicit concurrent mark sweep GC freed 6199(358KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 2.268ms total 138.157ms
,11-17 18:30:18.260  1070  1153 W asset   : Copying FileAsset 0x559722a860 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
11-17 18:30:18.270  1070  1945 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5566 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a
,11-17 18:30:18.270  1070  1070 W PackageManager: Unable to load service info ResolveInfo{b7bd142 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
11-17 18:30:18.270  1070  1070 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
11-17 18:30:18.270  1070  1070 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160),
11-17 18:30:18.270  1070  1070 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
11-17 18:30:18.270  1070  1070 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,11-17 18:30:18.280  1809  2223 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,11-17 18:30:18.320  1070  1070 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-17 18:30:18.320  1430  1430 I PhoneStatusBar: setImeWindowStatus(false,false)
11-17 18:30:18.320  5566  5566 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
11-17 18:30:18.320  1070  1385 D TaskPersister: removeObsoleteFile: deleting file=67_task.xml
11-17 18:30:18.320  1430  1430 I PhoneStatusBar: setSystemUiNavVisibility(false,false,false)
,11-17 18:30:18.330  1809  2029 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:30:18.350  1070  1900 D PMS     : acquireWL(202fb111): PARTIAL_WAKE_LOCK  AsyncService 0x1 5245 10126 null,
11-17 18:30:18.350  1809  2223 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447781418359
,11-17 18:30:18.350  1070  1945 D PMS     : releaseWL(202fb111): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,11-17 18:30:18.360  1070  1349 D PMS     : acquireWL(19859002): PARTIAL_WAKE_LOCK  Icing 0x1 2283 10020 WorkSource{10020 com.google.android.gms}
,11-17 18:30:18.370  1070  2122 D PMS     : releaseWL(19859002): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,11-17 18:30:18.380  1070  1945 D PMS     : acquireWL(192e7149): PARTIAL_WAKE_LOCK  Icing 0x1 2283 10020 WorkSource{10020 com.google.android.gms}
,11-17 18:30:18.380  1809  2223 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.,
11-17 18:30:18.380  2283  5589 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
11-17 18:30:18.380  2283  5589 D AccountUtils: Clearing selected account for com.example.hello
,11-17 18:30:18.390  2283  2283 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.gms
,11-17 18:30:18.410  2283  5589 I LocationSettingsChecker: Removing dialog suppression flag for package com.example.hello
,11-17 18:30:18.410  2051  2051 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-17 18:30:18.410  2051  2051 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-17 18:30:18.410  1070  1943 D PMS     : acquireWL(326d4468): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2051 10020 WorkSource{10020 com.google.android.gms},
11-17 18:30:18.420  5172  5172 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.example.hello]
11-17 18:30:18.420  5172  5172 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.example.hello, operation=3}]]
,11-17 18:30:18.430  1809  2030 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
11-17 18:30:18.430  5172  5172 I DeviceManagement: WorkflowService: Starting workflow service
,11-17 18:30:18.430  5172  5593 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@320a9d25] args=[Bundle[mParcelledData.dataSize=108]]
,11-17 18:30:18.430  5172  5593 I DeviceManagement: PackageUpdateWorkflow: ==================================================
11-17 18:30:18.430  5172  5593 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.example.hello, operation=REMOVE
11-17 18:30:18.430  5172  5593 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,11-17 18:30:18.440  5172  5593 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,11-17 18:30:18.440  1070  1090 D PMS     : releaseWL(326d4468): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:30:18.440  1070  1626 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5596 uid=10089 gids={50089, 9997, 3003} abi=arm64-v8a
,11-17 18:30:18.450  1809  2223 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447781418457
,11-17 18:30:18.470  5172  5593 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.example.hello,
11-17 18:30:18.470  3825  5565 I ApplicationLogger: canRun() : Opted Out
11-17 18:30:18.470  2283  5595 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
11-17 18:30:18.470  2283  5595 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,11-17 18:30:18.470  3825  5565 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 230 ms] updated apps [took 228 ms] 
,11-17 18:30:18.480  5172  5618 I DeviceManagement: SessionStateController: Checking invariants...
11-17 18:30:18.480  1809  2223 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,11-17 18:30:18.480  2283  5595 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.example.hello.
11-17 18:30:18.480  2283  5595 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,11-17 18:30:18.490  2283  5595 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
11-17 18:30:18.490  2283  5595 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,11-17 18:30:18.490  2283  5595 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,11-17 18:30:18.490  2283  5595 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1,
11-17 18:30:18.490  2283  5595 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
11-17 18:30:18.490  2283  5595 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
11-17 18:30:18.490  2283  5595 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
11-17 18:30:18.490  2283  5595 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
11-17 18:30:18.490  2283  5595 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,11-17 18:30:18.530  1809  2029 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:30:18.540  2283  5611 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:30:18.550  2283  5611 W BaseAppContext: Using Auth Proxy for data requests.,
11-17 18:30:18.550  1809  2223 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447781418565
,11-17 18:30:18.560  1809  2329 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-17 18:30:18.590  1809  2223 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,11-17 18:30:18.610  1070  1626 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5626 uid=10016 gids={50016, 9997, 1028, 1015, 1023} abi=arm64-v8a
,11-17 18:30:18.610  2283  5634 I GMPM-SVC: App measurement is starting up,
,11-17 18:30:18.620  2283  5638 I PeopleContactsSync: CP2 sync disabled
11-17 18:30:18.620  2283  4027 I Icing   : doRemovePackageData com.example.hello
,11-17 18:30:18.620  1070  1628 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2283, uid=10020, userID:0,
,11-17 18:30:18.640  5172  5618 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,11-17 18:30:18.640  1809  2030 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:30:18.650  1070  2124 D Process : killProcessQuiet, pid=5136
,11-17 18:30:18.650  1070  2124 I ActivityManager: Killing 5136:com.google.android.partnersetup/u0a23 (adj 15): empty #17,
11-17 18:30:18.650  1070  2124 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.attachApplicationLocked:6641 
,11-17 18:30:18.660  1809  2223 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447781418672,
,11-17 18:30:18.680  1809  2223 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,11-17 18:30:18.710  1809  2030 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:30:18.720  1809  2223 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447781418728,
,11-17 18:30:18.730  1070  1794 I ActivityManager: Recipient 5136
,11-17 18:30:18.730  1809  2223 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,11-17 18:30:18.750  1809  2029 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.,
,11-17 18:30:18.760  1070  1794 D Process : killProcessQuiet, pid=5136
,11-17 18:30:18.760  5172  5593 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.example.hello
11-17 18:30:18.760  1070  1794 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:30:18.760  2283  5634 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM events WHERE app_id=?] disk I/O error
11-17 18:30:18.760  1070  1794 W libprocessgroup: failed to open /acct/uid_10023/pid_5136/cgroup.procs: No such file or directory
11-17 18:30:18.760  2283  5634 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/google_app_measurement.db, handle: 0x5596be7760
11-17 18:30:18.760  5172  5593 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
,11-17 18:30:18.760  5172  5593 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.cs.dm/databases/provisioning.db, handle: 0x5596a79480
11-17 18:30:18.760  2283  5634 E GMPM-SVC: Error deleting application data. appId, error: com.example.hello, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.d.d(SourceFile:911)
11-17 18:30:18.760  5172  5593 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@320a9d25]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:30:18.760  5172  5593 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:30:18.770  1809  2223 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447781418777
11-17 18:30:18.770  1070  1946 I ActivityManager: Killing 4809:com.google.android.gm/u0a95 (adj 15): empty #17
11-17 18:30:18.770  5172  5172 I DeviceManagement: WorkflowService: Stopping workflow service
,11-17 18:30:18.770  1070  1946 D Process : killProcessQuiet, pid=4809
11-17 18:30:18.770  1070  1946 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
11-17 18:30:18.770  2283  4448 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml
11-17 18:30:18.770  2283  4448 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml
11-17 18:30:18.780  5626  5626 D ExternalStorage: After updating volumes, found 1 active roots
11-17 18:30:18.790  1809  2223 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
11-17 18:30:18.790  1809  1809 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId 35a5d662-45dc-456f-939b-ea6b69cce551, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null))]
11-17 18:30:18.810  1809  2030 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:30:18.820  1070  1646 I ActivityManager: Recipient 4809
,11-17 18:30:18.820  1070  1646 D Process : killProcessQuiet, pid=4809,
11-17 18:30:18.820  1070  1646 W libprocessgroup: failed to open /acct/uid_10095/pid_4809/cgroup.procs: No such file or directory
,11-17 18:30:18.820  1070  1646 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,11-17 18:30:18.830  1070  1933 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-17 18:30:18.880  5596  5621 D Documents: Update found 7 roots in 336ms
,11-17 18:30:18.880  5596  5652 D Documents: Update found 7 roots in 97ms
,11-17 18:30:18.900  2283  5594 W DriveInitializer: Awaiting to be initialized,
,11-17 18:30:18.900  2283  5654 W DriveInitializer: Background init thread started,
11-17 18:30:18.900  2283  5654 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock154] disk I/O error,
11-17 18:30:18.900  2283  5654 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5596c32b80
11-17 18:30:18.900  2283  5654 E DocListDatabase: Failed to delete from ContentFileDeletionLock154 table
11-17 18:30:18.900  2283  5654 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:30:18.900  2283  5654 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 18:30:18.900  2283  5654 E DocListDatabase: 	,at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
11-17 18:30:18.900  2283  5654 E DocListDatabase: 	,at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-17 18:30:18.900  2283  5654 E DocListDatabase: ,	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 18:30:18.900  2283  5654 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577),
11-17 18:30:18.900  2283  5654 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
11-17 18:30:18.900  2283  5654 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
11-17 18:30:18.900  2283  5654 E DocListDatabase: 	at com.google.android.gms.drive.s.run(SourceFile:62)
,11-17 18:30:18.900  2283  5654 W DriveInitializer: Background init thread ended
11-17 18:30:18.900  2283  5594 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
11-17 18:30:18.900  2283  5594 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5596c32b80
,11-17 18:30:18.900  2283  5654 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
11-17 18:30:18.900  2283  5654 E AndroidRuntime: Process: com.google.android.gms, PID: 2283
11-17 18:30:18.900  2283  5654 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:30:18.900  2283  5654 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 18:30:18.900  2283  5654 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
11-17 18:30:18.900  2283  5654 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-17 18:30:18.900  2283  5654 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 18:30:18.900  2283  5654 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
11-17 18:30:18.900  2283  5654 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
11-17 18:30:18.900  2283  5654 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
11-17 18:30:18.900  2283  5654 E AndroidRuntime: 	at com.google.android.gms.drive.s.run(SourceFile:62)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: disk I/O error (code 3850)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at com.google.android.gms.common.service.f.run(SourceFile:178)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
11-17 18:30:18.900  2283  5594 E DriveAsyncService: ,	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:18.910  1070  2124 E ActivityManager: App crashed! Process: com.google.android.gms
,11-17 18:30:18.910  1070  5655 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:30:18.910  1070  5655 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-17 18:30:18.910  1070  5655 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:30:18.910  1070  5655 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:30:18.910  1070  5655 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:30:18.910  1070  5655 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
11-17 18:30:18.910  1070  5655 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:30:18.910  1070  5655 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12649)
11-17 18:30:18.910  1070  5655 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:30:18.910  1070  5655 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:30:18.910  1070  5655 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:30:18.910  1070  5655 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:30:18.910  1070  5655 E DropBoxManagerService: 	... 5 more
,11-17 18:30:18.940  1070  1117 D StatusBarManagerService: setSystemUiVisibility(0xc0000000)
11-17 18:30:18.940  1070  1117 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
11-17 18:30:18.940  1070  1117 D StatusBarManagerService: hiding MENU key
11-17 18:30:18.940  1430  1430 I PhoneStatusBar: setSystemUiNavVisibility(false,false,false)
,11-17 18:30:19.460  2283  4027 I Icing   : Indexing CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF from com.google.android.googlequicksearchbox
,11-17 18:30:19.520  2283  4027 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
,11-17 18:30:19.520  2283  4027 E Icing   : Could not init tag ds.tag.deleted
,11-17 18:30:19.530  1809  2108 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,11-17 18:30:19.530  1809  2108 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2a30427a +
11-17 18:30:19.530  1809  2108 I Prism.WidgetManager: onLoadItems() +
,11-17 18:30:19.560  1809  2108 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,11-17 18:30:19.560  2283  4027 I Icing   : Indexing done CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF,
,11-17 18:30:19.570  2283  4027 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system,
11-17 18:30:19.570  2283  4027 E Icing   : Writing status failed
,11-17 18:30:19.570  2283  4027 E Icing   : Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
11-17 18:30:19.570  1070  1946 D PMS     : releaseWL(192e7149): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,11-17 18:30:19.660  1809  2108 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,11-17 18:30:19.790  1809  2108 W asset   : Copying FileAsset 0xac6b0550 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,11-17 18:30:19.800   487  1022 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=0 : Operation not permitted,
11-17 18:30:19.800   487  1022 E SurfaceFlinger: eventControl(0, 0) failed Operation not permitted
,11-17 18:30:19.820  1070  1328 D PMS     : acquireWL(15be343f): PARTIAL_WAKE_LOCK  *alarm* 0x1 1070 1000 WorkSource{10027},
11-17 18:30:19.820  1070  1328 V AlarmManager: sending alarm PendingIntent{1da1a10c: PendingIntentRecord{36467d1e com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=63762, Int=0
,11-17 18:30:19.820  4928  4928 D AlarmReceiver: ACTION_RESTART_INTENT
,11-17 18:30:19.820  4928  4928 D LocalBluetoothProfile: getPriorityOnValue = 100
11-17 18:30:19.820  1070  1070 D PMS     : releaseWL(15be343f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
11-17 18:30:19.820  4928  4928 D LocalBluetoothProfile: getPriorityOffValue = 0
11-17 18:30:19.820  4928  4928 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
11-17 18:30:19.820  4928  4928 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,11-17 18:30:19.850  4928  5658 D HtcModeClient: start the htcmodeservice thread,
11-17 18:30:19.850  4928  5658 D HtcModeClient: initCanAgent
11-17 18:30:19.850  4928  5658 I CANMesgAgentLocalSocket: CANAgent Id = 0
,11-17 18:30:19.850  4928  5658 D HtcModeClient: sense info: version = none, id = 2,
11-17 18:30:19.850  4928  5658 D HtcModeClient: display info: width = 1080, height = 1776
,11-17 18:30:19.850  4928  4928 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
11-17 18:30:19.850  4928  5658 D HtcModeClient: display info: mode = 10
11-17 18:30:19.850  4928  4928 D HtcModeClient: connectState: BT_TURNON_BYME = false
11-17 18:30:19.850  4928  4928 D HtcModeClient: connectState: CONNECTION_READY = false
11-17 18:30:19.850  4928  4928 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false,
11-17 18:30:19.850  4928  4928 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
11-17 18:30:19.850  4928  4928 D HtcModeClient: connectState: PHONE_PULGIN = false
11-17 18:30:19.850  4928  4928 D HtcModeClient: connectState: Force_AWAKE = false
11-17 18:30:19.850  4928  4928 D HtcModeClient: connectState: PHONE_PULGIN = true
11-17 18:30:19.850  4928  4928 D HtcModeClient: connectState: POWERCONNECTED_READY = true
```
