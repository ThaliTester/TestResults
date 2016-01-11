#### Test 5563415007e42e9_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1113): WifiActivity: 1
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,--------- beginning of /dev/log/main
E/cutils-trace( 2430): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 2430): ====startRecUseTime====
D/htc.customization.log.level( 2430):  is 
W/CustomizationLogLevel( 2430): Level value is invalid, use default level 2
D/CustomizationManager( 2430):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 2430): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2430): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2430): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2430): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2430): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2430): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2430): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2430): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2430): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2430): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2430): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2430): Parsing tag category name = system
I/CustomizationCIDLoader( 2430): Parsing tag category name = application
I/CustomizationCIDLoader( 2430): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2430): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2430): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2430): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2430): Parsing tag category name = Settings
D/CustomizationManager( 2430):  Read CID file spent 0.088 (s)
D/CustomizationManager( 2430):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 2430): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2430): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2430): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2430): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2430
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1115723600
D/PMS     (  905): acquireHCC(422df110): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(425c66f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b3f640
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
D/PMS     (  905): acquireWL(4268fa38): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2441 uid=10356 gids={50356, 3003, 5012}
I/TrimMemoryManager( 1270): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 2441): Binding Chromium to main looper Looper (main, tid 1) {41aaffd8}
I/LibraryLoader( 2441): Expected native library version number "",actual native library version number ""
I/chromium( 2441): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2441): Initializing chromium process, renderers=0
E/AudioManagerAndroid( 2441): BLUETOOTH permission is missing!
D/PMS     (  905): acquireWL(428431f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): acquireWL(4284fb48): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): releaseWL(4284fb48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 2441): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2441): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2441): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2441): Local Branch: 
I/Adreno-EGL( 2441): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2441): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2441):                  aa63bbd948f41d15fc72f585e
W/chromium( 2441): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 2441): VFY: unable to resolve virtual method 145: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2441): VFY: unable to resolve virtual method 140: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 2441): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2441): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2441): VFY: unable to resolve virtual method 198: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 2441): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2441): VFY: unable to resolve virtual method 156: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2441): VFY: unable to resolve virtual method 161: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2441): CordovaWebView is running on device made by: HTC
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
,W/AwContents( 2441): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1270
,W/ResourceType( 2441): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 2441): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41af4948, mServedView=org.apache.cordova.engine.SystemWebView{41abcc28 VFEDH.C. .F...... 0,0-720,1134 #64}
W/XT9_C   ( 1206): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1206): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  905): Enable input method client, pid=2441
,D/PMS     (  905): releaseWL(4268fa38): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  905): Displayed com.example.hello/.MainActivity: +249ms
,I/chromium( 2441): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 2441): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 2441): Set native->JS mode to OnlineEventsBridgeMode
,V/AlarmManager(  905): sending alarm PendingIntent{423188d8: PendingIntentRecord{4243e620 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=37966, Int=0
,V/TransactionService( 2129): 1-Creating TransactionService
V/TransactionService( 2129): onStartCommand: 1
,D/MmsSystemEventReceiver( 2129): unRegisterForConnectionStateChanges
V/TransactionService( 2129): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 2129): Loading previous transactions.
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1242): device_type: 1
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{4256da58 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
D/TransactionService( 2129): Force set service start id to 1
V/TransactionService( 2129): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 2129): unRegisterForConnectionStateChanges
,V/TransactionService( 2129): Destroying TransactionService
I/ActivityManager(  905): Resuming delayed broadcast
,D/TransactionService( 2129): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 2129): 4-Handling incoming message: { when=-12ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=2486 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/HtcModeClient( 1506): handler message = 4011
,E/HtcModeClient( 1506): Check connection and retry 2 times.
,W/ContextImpl( 2486): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.powersaver.PowerSaverNotificationReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver
,D/PowerSaverNotificationService( 2486): updateNotification, mToggle = false
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.qualcomm.privinit for broadcast com.qualcomm.privinit/.BootReciever: pid=2499 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2000
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2000:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2000
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/qcom_priv_settings( 2499): setprop(net.http.threads) = [10]
,D/qcom_priv_settings( 2499): setprop(net.http.idle_cache.size) = [40]
,D/qcom_priv_settings( 2499): setprop(net.dns.cache_size) = [512]
,D/qcom_priv_settings( 2499): setprop(net.dns.cache_ttl) = [600]
,D/qcom_priv_settings( 2499): setprop(net.http.getzip) = [1]
D/qcom_priv_settings( 2499): setprop(net.http.idle_cache.shutdown) = [true]
,D/qcom_priv_settings( 2499): setprop(net.webkit.cache.size) = [12582912]
D/qcom_priv_settings( 2499): setprop(net.webkit.cache.mindeadsize) = [4194304]
,D/qcom_priv_settings( 2499): setprop(net.webkit.cache.maxdeadsize) = [4194304]
D/qcom_priv_settings( 2499): setprop(net.nw.cache.prioadvstep) = [86400000]
,D/qcom_priv_settings( 2499): setprop(net.nw.cache.weightadvstep) = [3600000]
,D/qcom_priv_settings( 2499): setprop(net.nw.cache.orderby) = [weight]
,D/Process (  905): killProcessQuiet, pid=1282
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/RecoverySystem(  905): No recovery log file
I/ActivityManager(  905): Killing 1282:com.android.printspooler/u0a161 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 1282
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=2513 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/BootReceiver(  905): Copying audit failures to DropBox
,I/BootReceiver(  905): Checking for fsck errors
,I/ActivityManager(  905): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=2526 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
,I/DownloadManager( 2526): Enable ItsOn feature: false
,D/CalendarApplication( 2513): onCreate
,D/AlertReceiver( 2513): beginStartingService
,D/MediaProvider( 2526): [onCreate]+ 
D/MediaProvider( 2526): [attachVolume] attach internal db
D/MediaProvider( 2526): [DatabaseHelper] version:705, internal:true
V/MediaProvider( 2526): Attached volume: internal
,D/Process (  905): killProcessQuiet, pid=2094
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  905): acquireWL(425bb638): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 2513 10013 null
I/ActivityManager(  905): Killing 2094:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/MediaProvider( 2526): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
D/MediaProvider( 2526): [MP][DEBUG] Storage State: mounted
,D/MediaProvider( 2526): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 2526): [MP][DEBUG] Storage State: removed
,D/MediaProvider( 2526): [MP][DEBUG] Sorting: order:2, path:/storage/usb
,D/MediaProvider( 2526): [MP][DEBUG] Storage State: removed
,D/MediaProvider( 2526): [onCreate] External Storage State = mounted
D/MediaProvider( 2526): [DatabaseHelper] version:705, internal:false
,D/MediaProvider( 2526): [attachVolume] volumeID=11223344,dbName=external-ab4130.db
,V/MediaProvider( 2526): Attached volume: external
,D/MediaProvider( 2526): [onCreate]-
D/PMS     (  905): acquireWL(427df1c0): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 1506 10014 null
,D/AlertService( 2513): start to updateAlertNotification!
I/ActivityManager(  905): Delay finish: com.android.providers.calendar/.CalendarReceiver
D/PMS     (  905): releaseWL(427df1c0): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 null
,D/AlertService( 2513): No fired or scheduled alerts
,D/HtcAlertUtils( 2513): -- cancelReminderNotification --
,D/HtcAlertUtils( 2513): broadcastExistReminder!
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(425bb638): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,W/AlertReceiver( 2513): stopSelfResult true
I/ActivityManager(  905): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2547 uid=10016 gids={50016, 3003, 5012, 2001}
,D/MediaProvider( 2526): [writeUserBehaviorLog] +
,D/Process (  905): killProcessQuiet, pid=2155
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2155:com.htc.zero:re_proc/u0a34 (adj 15): empty #17
,D/MediaProvider( 2526): [writeUserBehaviorLog] -
,I/ActivityManager(  905): Recipient 2094
,E/UpdateRequestReceiver( 2547): ignoring update request
,E/UpdateRequestReceiver( 2547): ignoring update request
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/UpdateRequestReceiver( 2547): ignoring update request
E/UpdateRequestReceiver( 2547): ignoring update request
E/UpdateRequestReceiver( 2547): ignoring update request
E/UpdateRequestReceiver( 2547): ignoring update request
,D/Process (  905): killProcessQuiet, pid=2167
,I/ActivityManager(  905): Killing 2167:com.htc.showme/u0a82 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Recipient 2167
,W/CustomizationIntentService( 1294): failed at default contact creation!
W/CustomizationIntentService( 1294): java.lang.SecurityException: Requesting code from com.htc.contacts (with uid 10041) to be run in process android.process.acore (with uid 10017)
W/CustomizationIntentService( 1294): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1791)
W/CustomizationIntentService( 1294): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1767)
W/CustomizationIntentService( 1294): 	at android.app.ContextImpl.createPackageContextAsUser(ContextImpl.java:2149)
W/CustomizationIntentService( 1294): 	at android.app.ContextImpl.createPackageContext(ContextImpl.java:2136)
W/CustomizationIntentService( 1294): 	at android.content.ContextWrapper.createPackageContext(ContextWrapper.java:644)
W/CustomizationIntentService( 1294): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.handleIntentInternal(CustomizationIntentService.java:142)
W/CustomizationIntentService( 1294): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.onHandleIntent(CustomizationIntentService.java:103)
W/CustomizationIntentService( 1294): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/CustomizationIntentService( 1294): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/CustomizationIntentService( 1294): 	at android.os.Looper.loop(Looper.java:157)
W/CustomizationIntentService( 1294): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/CustomizationIntentService( 1294): handleIntentInternal(): action = com.htc.intent.action.PRELOAD_CONTACTS, original action = android.intent.action.BOOT_COMPLETED, launched by: null
,W/CustomizationIntentService( 1294): AFH Enable: false, LEONCHAME: false
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/CustomizationIntentService( 1294): hasBeenInit true
W/CustomizationIntentService( 1294): isNewChameleonHFASupported false
W/CustomizationIntentService( 1294): isHFA true
,W/CustomizationIntentService( 1294): setupWizRun 1
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2155
I/ActivityManager(  905): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=2574 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/DFPI.PIReciver( 2574): onReceiver action:android.intent.action.BOOT_COMPLETED
,D/DFPI    ( 2574): getInstance = com.htc.demoflopackageinstaller.ApkInstallHelper@41ab2930
,D/DFPI    ( 2574): set install APK prefrence is false
I/ActivityManager(  905): Delay finish: com.android.providers.downloads/.DownloadReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=2591 uid=10024 gids={50024, 3003, 5012, 1028, 1015}
D/Process (  905): killProcessQuiet, pid=2069
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2069:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
,D/Process (  905): killProcessQuiet, pid=2271
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/FlexNetS( 1506): set2gLowSignalEnablePref: false
V/FlexNetS( 1506): [DRX] setHigherPowerIn2GPref to: true
,D/FlexNetS( 1506): setSimCardisWhiteList: false
V/FlexNetS( 1506): setSimCardCamp3GNetworkSignalPref to: false
D/FlexNetS( 1506): setCampNetworkisBlackList: false
V/FlexNetS( 1506): [DRX] setHigherPowerIn2GPref to: true
I/ActivityManager(  905): Killing 2271:com.futuredial/u0a83 (adj 15): empty #17
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2271
V/FlexNetS( 1506): setRilHandOverW2GEnable: 0
D/HtcTelephonyManager( 1506): enablePS_W2G_Handover()
,D/PMS     (  905): acquireWL(42684238): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2216 10028 null
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
,D/PMS     (  905): releaseHCC(422df110): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(425c66f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.checkin.EventLogService$Receiver
,D/PMS     (  905): acquireWL(425c1b20): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2216 10028 null
,I/EventLogService( 2216): Aggregate from 1452525953409 (log), 1452525934708 (data)
D/PMS     (  905): releaseWL(42684238): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/ActivityManager(  905): Recipient 2069
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/EventLogAggregator( 2216): Unknown tag: install_package_attempt
W/EventLogAggregator( 2216): Unknown tag: snet
,W/EventLogAggregator( 2216): Unknown tag: snet_gcore
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): releaseWL(425c1b20): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,I/SystemUpdateService( 2216): receiver: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver (has extras) }
D/PMS     (  905): acquireWL(425ea750): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2216 10028 null
I/ActivityManager(  905): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/SystemUpdateService( 2216): cancelUpdate (empty URL)
,I/SystemUpdateService( 2216): active receiver: disabled
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2216, uid=10028, userID:0
I/SystemUpdateService( 2216): cancelUpdate (empty URL)
,I/SystemUpdateService( 2216): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2216, uid=10028, userID:0
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): releaseWL(425ea750): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 null
I/AdsMeasurementBroadcastReceiver( 2216): Device was rebooted, starting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2216): Unauthorized to start the main service
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/GCM     ( 2216): COMPAT: Multi user not supported
D/GCM     ( 1367): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,V/AuthZen ( 2216): Handling intent: android.intent.action.BOOT_COMPLETED
,V/AuthZen ( 2216): [DefaultAuthzenGcmReceiverDelegateService] Handling delegate intent.
,W/ActivityManager(  905): Unable to start service Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.fitness.service.BrokeredFitnessService (has extras) } U=0: not found
,I/GCoreUlr( 2216): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1438): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/PMS     (  905): acquireWL(4262d678): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1438 10028 null
,D/PMS     (  905): acquireWL(425ef628): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,I/AuthZen ( 2216): Fetching signing key...
,D/PMS     (  905): releaseWL(425ef628): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/AuthZen ( 2216): Signing key fetched successfuly!
,I/AuthZen ( 2216): No encryption key found or existing keys are expired for account thalitester@gmail.com
,I/GCoreUlr( 1438): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1438): Unknown pending intent to remove.
D/PMS     (  905): acquireWL(42828f90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1438 10028 null
,I/GCoreUlr( 1438): Unbound from all location providers
D/PMS     (  905): releaseWL(42828f90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  905): releaseWL(4262d678): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
,I/AuthZen ( 2216): Starting Enrollment...
,I/GoogleHttpClient( 2216): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2216): Using GMS GoogleHttpClient
,W/GLSActivity( 2216): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 2216): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cryptauth
,E/AuthZen ( 2216): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 2216): atk: Failed to get a token for authzen enrollment
E/AuthZen ( 2216): 	at atj.a(SourceFile:122)
E/AuthZen ( 2216): 	at atm.a(SourceFile:158)
E/AuthZen ( 2216): 	at atm.a(SourceFile:83)
E/AuthZen ( 2216): 	at asv.a(SourceFile:93)
E/AuthZen ( 2216): 	at com.google.android.gms.auth.authzen.DefaultAuthzenGcmReceiverDelegateService.onHandleIntent(SourceFile:33)
E/AuthZen ( 2216): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 2216): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 2216): 	at android.os.Looper.loop(Looper.java:157)
E/AuthZen ( 2216): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2629 uid=10030 gids={50030}
,V/OneTimeInitializerReceiver( 2629): OneTimeInitializerReceiver.onReceive
,V/OneTimeService( 2629): OneTimeService.onHandleIntent
I/ActivityManager(  905): Delay finish: com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=2107
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=2643 uid=10031 gids={50031, 3003, 5012}
I/ActivityManager(  905): Killing 2107:com.htc.contacts/u0a41 (adj 15): empty #17
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.partnersetup, clsName=com.google.android.partnersetup.PhoneStateReceiver, state=1, flag=1, pid=2643, uid=10031, userID:0
,I/ActivityManager(  905): Delay finish: com.google.android.partnersetup/.GooglePartnerSetup
,D/PMS     (  905): acquireWL(427adf48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1438 10028 null
,D/PMS     (  905): releaseWL(427adf48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=2643, uid=10031, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=2643, uid=10031, userID:0
,D/PMS     (  905): acquireWL(4279bb28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1438 10028 null
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=2643, uid=10031, userID:0
,I/ActivityManager(  905): Recipient 2107
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=null, state=1, flag=0, pid=2643, uid=10031, userID:0
,D/PMS     (  905): releaseWL(4279bb28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=2643, uid=10031, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=2643, uid=10031, userID:0
,D/PMS     (  905): acquireWL(427fdf58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1438 10028 null
,D/PMS     (  905): releaseWL(427fdf58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  905): acquireWL(42701708): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1438 10028 null
,D/PMS     (  905): releaseWL(42701708): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  905): acquireWL(426fa940): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1438 10028 null
,D/PMS     (  905): releaseWL(426fa940): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  905): acquireWL(427030b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1438 10028 null
,D/PMS     (  905): releaseWL(427030b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  905): acquireWL(42705768): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1438 10028 null
,D/PMS     (  905): releaseWL(42705768): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/RlzPingService( 2643): Setting next ping for 1453132602515
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=2286
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2286:com.htc.lucy/u0a62 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2286
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=2669 uid=10033 gids={50033, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=2254
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=2681 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Killing 2254:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2254
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/PMS     (  905): releaseWL(428431f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/Personalize.BootComple_( 2681): onReceive() + Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.home.personalize/.receiver.BootCompleteInitializer (has extras) }
,E/Personalize.BootComple_( 2681): action android.intent.action.BOOT_COMPLETED
,E/Personalize.Utilities( 2681): SimpleLauncher not found: com.htc.simplelauncher
,E/Personalize.BootComple_( 2681): initialize: false
,E/Personalize.Utilities( 2681): setApplicationEnabled IllegalArgumentException com.htc.simplelauncher
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.home.personalize, clsName=com.htc.home.personalize.SimpleModeEntryActivity, state=2, flag=1, pid=2681, uid=1000, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.simplelauncher, clsName=null, state=2, flag=0, pid=2681, uid=1000, userID:0
,I/ActivityManager(  905): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=2693 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
D/Process (  905): killProcessQuiet, pid=2032
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2032:com.htc.sense.news/u0a75 (adj 15): empty #17
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,V/BootCompletedReceiver( 2693): ensureAndExecuteUserProfiling: ensureAndExecuteUserProfiling 
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PeopleYouKnow( 2693): receive intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.contacts/.peopleyouknow.PeopleYouKnowReceiver (has extras) }
W/AccTypeManager( 2693): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 2693): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  905): Recipient 2032
,D/Process (  905): killProcessQuiet, pid=2327
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=2710 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
I/ActivityManager(  905): Killing 2327:com.htc.wifidisplay/u0a153 (adj 15): empty #17
,D/AccTypeManager( 2693): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  905): Recipient 2327
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/HtcDataRoamingWidget.DisableWidgetReceiver( 2710): ACTION_BOOT_COMPLETED
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.dataroaming, clsName=com.htc.rosiewidgets.dataroaming.HtcSettingWidgetProvider, state=1, flag=1, pid=2710, uid=10042, userID:0
,V/HtcDataStripWidget.DisableWidgetReceiver( 2710): ACTION_BOOT_COMPLETED
E/ExternalAccountType( 2693): Unsupported attribute readOnly
,D/Process (  905): killProcessQuiet, pid=2307
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/DotMatrix( 1584): [EventReceiver] onReceive, version:1.3
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.datastrip, clsName=com.htc.rosiewidgets.datastrip.HtcSettingWidgetProvider, state=1, flag=1, pid=2710, uid=10042, userID:0
I/ActivityManager(  905): Killing 2307:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2307
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1113): [SystemUIService] onCreate(), version: 1.3
,W/dalvikvm( 1113): VFY: unable to resolve interface method 6812: Lcom/android/internal/telephony/ITelephony;.answerRingingCallForSubscriber (J)V
,I/ActivityManager(  905): Start proc com.htc.aurora for broadcast com.htc.aurora/.receiver.BootCompletedReceiver: pid=2723 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
W/dalvikvm( 1113): VFY: unable to resolve interface method 6824: Lcom/android/internal/telephony/ITelephony;.endCallForSubscriber (J)Z
W/AccTypeManager( 2693): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 2693): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 2693): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/DotMatrix( 1113): [SystemUIService] EventService api version:1.3
,E/ExternalAccountType( 2693): Unsupported attribute readOnly
,I/ActivityManager(  905): Start proc com.htc.aurora:remote for service com.htc.aurora/.download.DownloadService: pid=2737 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  905): Delay finish: com.htc.aurora/.receiver.BootCompletedReceiver
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.aurora, clsName=com.htc.aurora.download.DownloadReceiver, state=1, flag=1, pid=2737, uid=10047, userID:0
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=2753 uid=10050 gids={50050, 3003, 5012, 1028, 1015, 3002, 3001, 2001, 1023}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.aurora, clsName=com.htc.aurora.download.DownloadReceiver, state=2, flag=1, pid=2737, uid=10047, userID:0
,D/Process (  905): killProcessQuiet, pid=1750
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 1750:com.google.android.gms.wearable/u0a28 (adj 15): empty #17
,D/Process (  905): killProcessQuiet, pid=2129
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2129:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/MediaFocusControl(  905):   Remote Control   registerMediaButtonIntent() for PendingIntent{4245fbb8: PendingIntentRecord{42358c10 com.htc.music broadcastIntent}}
,V/Avrcp   ( 1640): New genId = 1, clearing = 1
D/DotMatrix( 1584): [EventService] onClientChange, clearing: true
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] onClientChange, currEventType: 26
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  905): killProcessQuiet, pid=2486
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=2768 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
I/ActivityManager(  905): Killing 2486:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
I/ActivityManager(  905): Recipient 2486
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 1750
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=2781 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2499
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2499:com.qualcomm.privinit/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2499
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2129
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 2781): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 2781): call getInstance()
I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 2781): MY_DEBUG = false
,I/ActivityManager(  905): Resuming delayed broadcast
,V/AlarmManager(  905): sending alarm PendingIntent{41dda4e0: PendingIntentRecord{41ddade0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452527803649, Int=900000
,W/ContextImpl( 2781): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncServiceReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncServiceReceiver
,D/SmartSyncUtils( 2781): getMobilePolicyEnabled, result = true
W/ContextImpl( 2781): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.startService:228 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.onHandleIntent:75 android.app.IntentService$ServiceHandler.handleMessage:65 
I/ActivityManager(  905): Resuming delayed broadcast
,W/ContextImpl( 2781): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,W/ContextImpl( 2781): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=2513
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2513:com.htc.calendar/u0a13 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1402): onHandleIntent, action: android.intent.action.BOOT_COMPLETED, data: null
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  905): Recipient 2513
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Bundle  ( 1402): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1402): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/WIFI_ICON( 1113): WifiActivity: 1
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/Bundle  ( 1402): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1402): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/FeatureList( 1402): feature
D/FeatureList( 1402): type
,D/FeatureList( 1402): description
,W/Bundle  ( 1402): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1402): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1402): Attempt to cast generated internal exception:
W/Bundle  ( 1402): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1402): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PluginProvider( 1402): Begin Apply Batch
,E/PluginProvider( 1402): conflict when insert feature, ignored
,D/PluginProvider( 1402): apply Batch success
,I/[PluginManager]RegisterService( 1402): Notify Carousel that a new TabPlugin has been installed!
,I/ActivityManager(  905): Resuming delayed broadcast
,I/WSP     ( 1402): [Receiver] EVENT - BOOT COMPLETED, is settings existed? true
,D/AutoSetting( 1402): receiver - intent: android.intent.action.BOOT_COMPLETED
,D/HtcAppUPService( 1402): CustomizationReceiver  receieve: android.intent.action.BOOT_COMPLETED
,D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.bootcomplete
,D/AutoSetting( 1402): service - onStartCommand() boot completed, remove cache
D/AutoSetting( 1402): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1402): service - handleMessage() removing cache
,D/AutoSetting( 1402): service - AddressCache: clean up all cache
,D/AutoSetting( 1402): service - handleMessage() setting current location null
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.upservice.HtcUPServiceReceiver
I/ActivityManager(  905): Waited long enough for: ServiceRecord{42418c38 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager(  905): Resuming delayed broadcast
,D/HtcAppUPService( 1402): HtcUPService onCreate()
,D/HtcAppUPService( 1402): DatabaseHelper [DatabaseHelper constructor]
,D/HtcAppUPService( 1402): PolicyStore [Init] Get cached policy bundle
,D/HtcAppUPService( 1402): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.BOOT_COMPLETED cmp=com.htc.sense.hsp/.upservice.HtcUPService }, this = com.htc.sense.hsp.upservice.HtcUPService@41cedfc8
,D/HtcAppUPService( 1402): HtcUPServicePreference Is policy store first run: false
I/ActivityManager(  905): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=2803 uid=10055 gids={50055, 1028, 1015, 3003, 5012, 3001, 3002}
,D/HtcAppUPService( 1402): appid: tellhtc_client, category: usage_report, key: enable, value: 1, due date: -1, current time: 1452527804823, default value: null
,D/HtcAppUPService( 1402): HtcUPServicePreference Upload schedule enable? false
,W/dalvikvm( 1402): VFY: unable to resolve static field 680 (common_google_play_services_unknown_issue) in Lcom/google/android/gms/R$string;
,E/GooglePlayServicesUtil( 1402): The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,V/BootReceiver( 2803): onReceive: android.intent.action.BOOT_COMPLETED
,D/BootReceiver( 2803): boot completed:
,D/BootReceiver( 2803): isValid:  isEnabledEasyAccess = false, isEnabledQuickDial = false
,E/dalvikvm( 1402): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 1402): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,D/Process (  905): killProcessQuiet, pid=2547
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/dalvikvm( 1402): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 1402): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
I/ActivityManager(  905): Start proc com.htc.video for broadcast com.htc.video/com.htc.videowidget.videoDMC.DLNAReceiver: pid=2818 uid=10056 gids={50056, 2001, 3002, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  905): Killing 2547:com.google.android.configupdater/u0a16 (adj 15): empty #17
,V/JNIHelp ( 1402): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2547
,I/ActivityManager(  905): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=2833 uid=10059 gids={50059, 1028, 1015, 3003, 5012, 1023}
,D/Process (  905): killProcessQuiet, pid=2574
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2574:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2574
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ProviderInstaller( 1402): Installed default security provider GmsCore_OpenSSL
,D/HtcAppUPService( 1402): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.BOOT_COMPLETED
,D/HtcAppUPService( 1402): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
,W/LMW     ( 2833): [2847][ActionDeviceStorageHandler] onActionBootComplete++
,D/HtcAppUPService( 1402): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@41cedfc8
,D/HtcAppUPService( 1402): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
,D/MediaScannerReceiver( 2526): onReceive Intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.media/.MediaScannerReceiver (has extras) }
,D/MediaProviderUtils( 2526): [scanEx]volume:internal,action:android.intent.action.BOOT_COMPLETED
,W/LMW     ( 2833): [2847][ActionDeviceStorageHandler] onActionBootComplete--
I/ActivityManager(  905): Delay finish: com.htc.lmw/.StorageBroadcastReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
D/MediaProviderUtils( 2526): [scanEx]volume:customize,action:android.intent.action.BOOT_COMPLETED
D/MediaProviderUtils( 2526): [scanEx]volume:external,action:android.intent.action.MEDIA_MOUNTED
D/MediaProviderUtils( 2526): [scanEx]volume:external,action:android.intent.action.MEDIA_MOUNTED
D/MediaProviderUtils( 2526): [scanEx]volume:external,action:android.intent.action.MEDIA_MOUNTED
,D/Process (  905): killProcessQuiet, pid=2591
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2591:com.htc.fm/u0a24 (adj 15): empty #17
,D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage]+internal
,D/MediaScannerServiceEx( 2526): [3] stop task - current task is null
,D/MediaScannerServiceEx( 2526): [4] stop task - current task is null
,D/MediaScannerServiceEx( 2526): [5] stop task - current task is null
,D/PMS     (  905): acquireWL(422fdc78): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2526 10021 null
D/MtpReceiver( 2526): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2526): [MP][DEBUG][MtpReceiver] requestFullScanForMTP
D/MtpReceiver( 2526): [MP][DEBUG][MtpReceiver] requestFullScanForMTP dir = /storage/emulated/0
D/MtpReceiver( 2526): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2526): [MTP][handleMessage][startService]
,D/MtpReceiver( 2526): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MediaProvider( 2526): bindService() MTP Service Connection.
,I/ActivityManager(  905): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=2850 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
D/MtpReceiver( 2526): [MTP][handleMessage]-
,D/MediaScannerServiceEx( 2526): getDefaultLocale =en_GB
D/MediaScannerServiceEx( 2526): [scan]+internal,/system/media
,D/MediaScanner( 2526): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
,D/MtpService( 2526): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpService( 2526): addStorageInternal without MtpServer
,D/MtpService( 2526): [MTP][onCreate]-
I/ActivityManager(  905): Recipient 2591
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MtpService( 2526): [MTP] startForeground
D/MtpService( 2526): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2526): TotalSize=1918604,MediaCacheLimit=6000
D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 2526): starting MTP server in MTP mode
D/MtpService( 2526): addStorageInternal 65537 /storage/emulated/0
I/RemoteViews( 1113): com.android.providers.media (false,0)
D/MtpService( 2526): [checkStorageState] Storage state - mounted
D/MtpService( 2526): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41af5ca8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1113): com.android.providers.media 3 10 0 10
I/RemoteViews( 1113): com.android.providers.media (false,0)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41af5f50 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/MessageFrequencyProvider( 2850): onCreate
,I/RemoteViews.Performance( 1113): com.android.providers.media 1 10 1 15
,V/GetPrviateResource( 2850): GetPrviateResource
,V/GetPrviateResource( 2850): GetPrviateResource
,D/MediaScanner( 2526):  prescan time: 108ms
,D/MediaScanner( 2526):     scan time: 33ms
D/MediaScanner( 2526): postscan time: 0ms
D/MediaScanner( 2526):    total time: 141ms
D/MediaScanner( 2526): -----------------------------------------------------------------
,D/MessageCustFlag( 2850): sense_version=6.0
D/MediaScanner( 2526): firstscan(media) time: 20ms
D/MediaScanner( 2526): secondscan(non-media) time: 8ms
D/MediaScanner( 2526):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2526):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2526):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2526):  [Total]    File(Image+Video+Audio+Others) in database : 366
,D/MediaScannerServiceEx( 2526): [scan]-
,D/BTAccessoryUtil( 2850): createReceiver
,D/BTAccessoryUtil( 2850): registerReceiver return intent = null
D/MessageCustFlag( 2850): sku_id=99
,W/SystemReader( 2850): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 2850): supportCMAS(SIE)/init? false/true
D/MmsConfig( 2850): networkCode: 
,D/MessageCustFlag( 2850): sku_id=99
D/MmsConfig( 2850): SIE smsPri: null
,D/MmsConfig( 2850): networkCode: 
,D/HtcTelephonyCapability( 2850): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 2850): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 2850): getRATByHtcTelephonyCapability:1
,W/SystemReader( 2850): Cannot find qct_8960_interface, use default value instead
,V/MmsSystemEventReceiver( 2850): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/ExchangePolicystatus( 2850): onReceive()
,D/ExchangePolicystatus( 2850): onReceive(): ACTION_BOOT_COMPLETED
D/MessageUtils( 2850): Text messaging allow status = allow
,D/Messaging( 2850): EAS allow SMS !!!
D/ExchangePolicystatus( 2850): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
,D/Messaging( 2850): EAS allow SMS !!!
D/PMS     (  905): acquireWL(424639a8): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 2850 10064 null
,V/SmsReceiverService( 2850): onStart: #1, @1102120728
V/SmsReceiverService( 2850): action: android.intent.action.BOOT_COMPLETED
D/SmsReceiverService( 2850): isCbm: false
,D/SmsReceiverService( 2850): isDiscard: false
,D/SettingsManager( 2850): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41aba0e8
,I/ActivityManager(  905): Delay finish: com.htc.sense.mms/.PolicyReceiver
V/SmsReceiverService( 2850): handleBootCompleted
D/MediaProvider( 2526): [delete][44]
D/MediaProvider( 2526): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 2526): [recoverParentNodes] - 0
D/MediaProvider( 2526): [update][2]
D/MediaScannerServiceEx( 2526): [scan] Recover Parent Node is finished!
,D/TAG     ( 2526): mWakeLock.release() at scan()
,D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage]+customize
D/PMS     (  905): releaseWL(422fdc78): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/PMS     (  905): acquireWL(42621150): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2526 10021 null
,D/MediaScannerServiceEx( 2526): getDefaultLocale =en_GB
,D/MediaScannerServiceEx( 2526): [scan]+internal,/system/customize/resource
,D/MediaScanner( 2526): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1242): sku_id=99
D/SmsReceiverService( 2850): OutBoxSize = 0
,D/SmsReceiverService( 2850): sendFirstQueuedMessage start: 0
,D/MessageCustFlag( 2850): sku_id=99
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1242): sku_id=99
,D/SmsReceiverService( 2850): sendFirstQueuedMessage end cnt> 0
D/SpaceBufferUtil( 2850): > createBufferFile()
,D/SpaceBufferUtil( 2850): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
,D/SpaceBufferUtil( 2850): < createBufferFile()
,D/MediaScanner( 2526):  prescan time: 26ms
D/MediaScanner( 2526):     scan time: 18ms
D/MediaScanner( 2526): postscan time: 0ms
D/MediaScanner( 2526):    total time: 44ms
D/MediaScanner( 2526): -----------------------------------------------------------------
D/MediaScanner( 2526): firstscan(media) time: 9ms
D/MediaScanner( 2526): secondscan(non-media) time: 8ms
D/MediaScanner( 2526):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2526):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2526):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2526):  [Total]    File(Image+Video+Audio+Others) in database : 366
,D/MediaScannerServiceEx( 2526): [scan]-
,D/MediaProvider( 2526): [delete][10]
,D/MediaProvider( 2526): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 2526): [recoverParentNodes] - 0
D/MediaProvider( 2526): [update][1]
,D/MediaScannerServiceEx( 2526): [scan] Recover Parent Node is finished!
,D/TAG     ( 2526): mWakeLock.release() at scan()
D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage]+external
D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage] volume: external, action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 2526): ignoreDirectories[ 0 ] = /storage/ext_sd
,D/MediaScannerServiceEx( 2526): ignoreDirectories[ 1 ] = /storage/usb
,D/MediaScannerServiceEx( 2526): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 2526): [update][4]#0#
,D/MediaProvider( 2526): [update][3]#0#
,D/PMS     (  905): releaseWL(42621150): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaProvider( 2526): [update][3]#0#
D/MediaScannerServiceEx( 2526): [deleteRowsEqualVolid]+65537
D/MediaProvider( 2526): [delete][4]#0#
D/MediaScannerServiceEx( 2526): [deleteRowsEqualVolid]-0
,D/MediaProvider( 2526): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
,D/MtpService( 2526): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 2526): [update][10]#1#
,D/MediaScannerServiceEx( 2526): [AliveExtStorageRows]-0, 0, 0
,D/MediaScannerServiceEx( 2526): [deleteNonUseAlbumArts]+
,D/MediaScannerServiceEx( 2526): [deleteNonUseAlbumArts]-
,D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage][EXTERNAL]-android.intent.action.MEDIA_MOUNTED,[Ljava.lang.String;@41c7ddb8
,E/MediaProvider( 2526): no database for attached volume content://media/external
D/PMS     (  905): acquireWL(42632b00): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2526 10021 null
,D/MediaScannerServiceEx( 2526): getDefaultLocale =en_GB
D/MediaScannerServiceEx( 2526): [scan]+external,/storage/emulated/0
D/MediaScanner( 2526): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
D/MediaScanner( 2526): Ignore scan directories /storage/ext_sd
D/MediaScanner( 2526): Ignore scan directories /storage/usb
,D/MediaScanner( 2526): Ignore scan directories null
,D/MediaScanner( 2526):  prescan time: 162ms
D/MediaScanner( 2526):     scan time: 340ms
D/MediaScanner( 2526): postscan time: 3ms
D/MediaScanner( 2526):    total time: 505ms
D/MediaScanner( 2526): -----------------------------------------------------------------
D/MediaScanner( 2526): firstscan(media) time: 234ms
D/MediaScanner( 2526): secondscan(non-media) time: 106ms
D/MediaScanner( 2526):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2526):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2526):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2526):  [Total]    File(Image+Video+Audio+Others) in database : 468
,D/MediaScannerServiceEx( 2526): [scan]-,
I/ActivityManager(  905): Waited long enough for: ServiceRecord{42611e68 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/ActivityManager(  905): Resuming delayed broadcast
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/MediaProvider( 2526): [delete][21]
,D/MediaProvider( 2526): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
,I/ActivityManager(  905): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.PolicyReceiver: pid=2878 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/MediaProvider( 2526): [recoverParentNodes] - 0
D/MediaProvider( 2526): [update][6]
D/MediaScannerServiceEx( 2526): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 2526): [updateImage]+
,D/MediaScannerServiceEx( 2526): [updateImage]-0
,D/TAG     ( 2526): mWakeLock.release() at scan()
,D/MediaScannerServiceEx( 2526): [3] scan finished
,D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage]+external
D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage] volume: external, action: android.intent.action.MEDIA_MOUNTED, Id: 1, path: /storage/ext_sd
D/MediaScannerServiceEx( 2526): ignoreDirectories[ 0 ] = /storage/emulated/0
,D/MediaScannerServiceEx( 2526): ignoreDirectories[ 1 ] = /storage/usb
,E/MediaScannerServiceEx( 2526): Process mounted intent for unmounted storage/storage/ext_sd
D/PMS     (  905): releaseWL(42632b00): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 2526): [disAliveExtStorageRows]+131073
,D/MyReportAgent( 2878): ReportService [##] onCreate(), this = com.htc.reportagent.ReportService@41abb9a0
,I/ActivityManager(  905): Delay finish: com.htc.reportagent/.receiver.PolicyReceiver
D/MediaProvider( 2526): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/MediaProvider( 2526): [update][24]#1#
D/MyReportAgent( 2878): ReportService [##] onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.reportagent.action.BOOT_COMPLETE cmp=com.htc.reportagent/.ReportService }, this = com.htc.reportagent.ReportService@41abb9a0
D/MyReportAgent( 2878): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE
D/MediaProvider( 2526): [update][3]#0#
D/MediaScannerServiceEx( 2526): [disAliveExtStorageRows]--1
D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage][EXTERNAL]-android.intent.action.MEDIA_MOUNTED,null
D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage]+external
D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage] volume: external, action: android.intent.action.MEDIA_MOUNTED, Id: 2, path: /storage/usb
D/MediaScannerServiceEx( 2526): ignoreDirectories[ 0 ] = /storage/emulated/0
D/MediaScannerServiceEx( 2526): ignoreDirectories[ 1 ] = /storage/ext_sd
E/MediaScannerServiceEx( 2526): Process mounted intent for unmounted storage/storage/usb
D/MediaScannerServiceEx( 2526): [disAliveExtStorageRows]+196609
D/MediaProvider( 2526): [sendStorageAddedIfNeed]: /storage/usb : unmounted
D/MediaProvider( 2526): [update][3]#1#
D/UPolicy ( 2878): IUserBehaviorLoggingService reference is gotten !
D/MediaProvider( 2526): [update][3]#0#
D/MediaScannerServiceEx( 2526): [disAliveExtStorageRows]--1
D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage][EXTERNAL]-android.intent.action.MEDIA_MOUNTED,null
D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage]+external
D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage] volume: external, action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 2526): ignoreDirectories[ 0 ] = /storage/ext_sd
D/MediaScannerServiceEx( 2526): ignoreDirectories[ 1 ] = /storage/usb
D/MediaScannerServiceEx( 2526): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 2526): [update][3]#0#
D/MediaProvider( 2526): [update][3]#0#
D/MyReportAgent( 2878): ReportServiceHandler on boot complete event 
D/MediaProvider( 2526): [update][3]#0#
D/MediaScannerServiceEx( 2526): [deleteRowsEqualVolid]+65537
D/MediaProvider( 2526): [delete][4]#0#
D/MediaScannerServiceEx( 2526): [deleteRowsEqualVolid]-0
D/MediaProvider( 2526): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 2526): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 2526): [update][4]#1#
D/MediaScannerServiceEx( 2526): [AliveExtStorageRows]-0, 0, 0
D/MediaScannerServiceEx( 2526): [deleteNonUseAlbumArts]+
D/MediaScannerServiceEx( 2526): [deleteNonUseAlbumArts]-
,D/MediaScannerServiceEx( 2526): [ServiceHandler][handleMessage][EXTERNAL]-android.intent.action.MEDIA_MOUNTED,[Ljava.lang.String;@41d306d0
,D/PMS     (  905): acquireWL(42840618): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2526 10021 null
E/MediaProvider( 2526): no database for attached volume content://media/external
,D/MediaScannerServiceEx( 2526): getDefaultLocale =en_GB
D/MediaScannerServiceEx( 2526): [scan]+external,/storage/emulated/0
D/MediaScanner( 2526): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
D/MediaScanner( 2526): Ignore scan directories /storage/ext_sd
D/MediaScanner( 2526): Ignore scan directories /storage/usb
,D/MediaScanner( 2526): Ignore scan directories null
,V/MyReportAgent( 2878): ReportServiceHandler register the PowerConnected Listener
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.reportagent, clsName=com.htc.reportagent.receiver.PowerConnectedReceiver, state=1, flag=1, pid=2878, uid=10065, userID:0
,I/HtcModeClient( 1506): handler message = 4011
,E/HtcModeClient( 1506): Check connection and retry 3 times.
,D/MediaScanner( 2526):  prescan time: 44ms
,D/MediaScanner( 2526):     scan time: 267ms
D/MediaScanner( 2526): postscan time: 2ms
D/MediaScanner( 2526):    total time: 313ms
D/MediaScanner( 2526): -----------------------------------------------------------------
D/MediaScanner( 2526): firstscan(media) time: 192ms
,D/MediaScanner( 2526): secondscan(non-media) time: 75ms
D/MediaScanner( 2526):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2526):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
,D/MediaScanner( 2526):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2526):  [Total]    File(Image+Video+Audio+Others) in database : 468
,D/MediaScannerServiceEx( 2526): [scan]-
,D/MediaProvider( 2526): [delete][10]
,D/MediaProvider( 2526): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 2526): [recoverParentNodes] - 0
D/MediaProvider( 2526): [update][2]
D/MediaScannerServiceEx( 2526): [scan] Recover Parent Node is finished!
,D/MediaScannerServiceEx( 2526): [updateImage]+
,D/MediaScannerServiceEx( 2526): [updateImage]-0
,D/TAG     ( 2526): mWakeLock.release() at scan()
,D/PMS     (  905): releaseWL(42840618): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 2526): [6] scan finished
,D/HtcBroadcastReceiver( 1242): onReceive: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2895 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,V/AlarmManager(  905): sending alarm PendingIntent{425e1940: PendingIntentRecord{426d0e50 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=43879, Int=0
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=2895, uid=10073, userID:0
,D/Finsky  ( 2895): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (2895/10073)
,D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (2895/10073)
,D/Finsky  ( 2895): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 2895): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2895): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=2895, uid=10073, userID:0
,D/Volley  ( 2895): [247] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 2895): [251] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=2927 uid=10077 gids={50077}
,D/Process (  905): killProcessQuiet, pid=2629
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2629:com.google.android.onetimeinitializer/u0a30 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2629
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 2895): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2895): [1] 2.run: Finished loading 1 libraries.
,D/SMSBackup( 2927): Got ACTION_BOOT_COMPLETED event
,D/SMSBackup( 2927): setCheckAlarm
,D/SMSBackup( 2927): Next check is scheduled at 60s from now
,D/Finsky  ( 2895): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Process (  905): killProcessQuiet, pid=2643
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 2643:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1242, uid=1001, userID:0
,I/ActivityManager(  905): Delay finish: com.android.stk/.BootCompletedReceiver
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2643,
,D/Finsky  ( 2895): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=2943 uid=10082 gids={50082, 3003, 5012, 1028, 1015}
,I/[AppShowMeDebug]BootCompletedReceiver( 2943): received boot complete
,I/[AppShowMeDebug]BootCompletedReceiver( 2943): push flag is false, skip check
D/Process (  905): killProcessQuiet, pid=2669
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=2958 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
I/ActivityManager(  905): Killing 2669:com.htc.csrecommend/u0a33 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2669
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Delay finish: com.htc.updater/.UpdaterBootCompleteReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=2972 uid=10085 gids={50085, 3003, 5012, 3001, 1028, 3002, 1015}
,D/Process (  905): killProcessQuiet, pid=2681
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2681:com.htc.home.personalize/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2681
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=2988 uid=10031 gids={50031, 3003, 5012},
,D/LocationManagerService(  905): getProviders()=[passive]
,I/ContactAccountLoggerTas( 2972): canRun() : Opted Out
,D/Messaging( 2850): mNeedToUpdateDate2 start
,D/MmsConfig( 2850): packageName: com.htc.vvm.att does not exist
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$ApplicationLaunchReceiver, state=1, flag=1, pid=2972, uid=10085, userID:0
D/ReportIndicatorCache( 2850): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 2850): 
D/MmsAsyncWorkHandler( 2850): HM tk = 20001
D/ReportIndicatorCache( 2850): MSG_QUERY_REPORTS >>
I/Messaging( 2850): mccmnc> 
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1242):  phoneType = -1
D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 2850): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 2850): [DraftCache/1] refresh
,D/MmsConfig( 2850): networkCode: 
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1242):  phoneType = -1
,I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver
D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 2850): ViewCache CreatePreloadOnlyConversationList
D/Messaging( 2850): mNeedToUpdateDate2: false
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1242):  phoneType = -1
D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/AccFlag ( 1242): sku_id=99
,D/MessageCustFlag( 2850): sense_version=6.0
,W/GAV2    ( 2972): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/Jerry   ( 2850): start to preload cursor >>>>>>>
,D/DraftCache( 2850): [DraftCache/235] rebuildCache
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1242):  phoneType = -1
D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/PhoneStorageUtil( 2850): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 2850): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 2850): createReceiver
,W/GAV2    ( 2972): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ContactAccountLoggerTas( 2972): canRun() : Opted Out
,D/TelephUtils( 1242): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
V/MmsProvider( 1242): Update uri=content://mms, match=0
,V/MmsProvider( 1242): selection=st=129 AND m_type!=134
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1242):  phoneType = -1
D/Messaging( 2850): Reset downloading state: 0
,V/MmsSystemEventReceiver( 2850): TransactionService is going to be woken up.
,D/Messaging( 2850): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,V/TransactionService( 2850): 1-Creating TransactionService
,W/dalvikvm( 2972): method Lcom/google/android/search/core/state/QueryState;.a incorrectly overrides package-private method with same name in Lcfl;
V/TransactionService( 2850): onStartCommand: 1
,D/MmsSystemEventReceiver( 2850): unRegisterForConnectionStateChanges
V/TransactionService( 2850): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 2850): Loading previous transactions.
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/Jerry   ( 1242): URI_DRAFT
D/Messaging( 2850): ViewCache CreatePreload
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1242): device_type: 1
,D/Messaging( 2850): ViewCache CreatePreloadOnlyMultipleOpsList
D/TransactionService( 2850): Force set service start id to 1
V/TransactionService( 2850): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 2850): unRegisterForConnectionStateChanges
,V/TransactionService( 2850): Destroying TransactionService
,D/Cust_MMSMS( 2850): _has_set_default_values_2=true
,D/TransactionService( 2850): stopSelfResult: true, mLastHandledServiceId: 1
D/DraftCache( 2850): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 2850): [DraftCache/235] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 2850): 
D/MmsAsyncWorkHandler( 2850): HM tk = 20002
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1242): sku_id=99
,V/TransactionService( 2850): 4-Handling incoming message: { when=-8ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 2850): def_index: 0
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MsgPreferenceUtils( 2850): globalIndex = 1
,D/AccFlag ( 1242): sku_id=99
D/WifiService(  905): New client listening to asynchronous messages
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/MsgPreferenceUtils( 2850): phone state: true
D/MsgPreferenceUtils( 2850): sd state: false
D/MsgPreferenceUtils( 2850): vIndex = 0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2972): Registered
,I/MediaRouter( 2972): Found default route: MediaRouter.RouteInfo{ uniqueId=android/kb:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/Process (  905): killProcessQuiet, pid=2693
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/ActivityManager(  905): Killing 2693:com.htc.contacts/u0a41 (adj 15): empty #17
D/MediaRouter( 2972): getSelectedRoute
,I/ActivityManager(  905): Recipient 2693,
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/SmsReceiverService( 2850): updateNotificationAndShortcutStatus: 
,D/MessagingNotification( 2850): New incoming message, can't cancel notification now
,D/MessagingNotification( 2850): newMsgCnt: 0, false
I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=2710
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2710:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,D/PMS     (  905): releaseWL(424639a8): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
,I/ActivityManager(  905): Recipient 2710
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3041 uid=10090 gids={50090, 3003, 5012, 1028}
,I/ActivityManager(  905): Delay finish: com.htc.android.worldclock/.alarmclock.AlarmReceiver
,I/WorldClock.Global( 3041): isHtcDevice = true
,D/PMS     (  905): acquireWL(41ee9ab8): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 3041 10090 null
,W/WorldClock.AlarmService( 3041): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException
,I/WorldClock.AlarmUtils( 3041): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 3041): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 3041): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1113): receive(android.intent.action.ALARM_CHANGED,1,false),
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): releaseWL(41ee9ab8): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
,I/ActivityManager(  905): Delay finish: com.htc.android.worldclock/.stopwatch.StopwatchReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,I/WorldClock.Global( 3041): isHtcDevice = true
I/ActivityManager(  905): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.mobiledata for broadcast com.htc.mobiledata/com.htc.omacp.OmaCPPushReceiver: pid=3061 uid=10091 gids={50091, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=2723
I/ActivityManager(  905): Killing 2723:com.htc.aurora/u0a47 (adj 15): empty #17
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 2723
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/OmaCPPushReceiverV2( 3061): initialCheck: sku=99, result=false
,I/ActivityManager(  905): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3073 uid=10091 gids={50091, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=2737,
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2737:com.htc.aurora:remote/u0a47 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2737
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=3089 uid=10098 gids={50098, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=2753
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2753:com.htc.music:mediaplaybackservice/u0a50 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2753
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/DeviceManagement( 3089): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3089 dbg=false s=true
,I/DeviceManagement( 3089): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
,I/DeviceManagement( 3089): WorkflowService: Starting workflow service
I/DeviceManagement( 3089): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41add3e0] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 3089): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3089): BootCompletedWorkflow: Boot completed
,I/DeviceManagement( 3089): BootCompletedWorkflow: ==================================================
,I/DeviceManagement( 3089): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  905): Delay finish: com.htc.cs.dm/.receiver.BootCompletedReceiver
,I/DeviceManagement( 3089): BackgroundController: *** Update after boot...
,I/DeviceManagement( 3089): SessionStateController: Checking invariants...
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,I/DeviceManagement( 3089): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 3089): SessionStateController: Checking invariants...
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:43, mTXpacketCount:40, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/DeviceManagement( 3089): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 3089): Perf: *** Cache update - start...
I/DeviceManagement( 3089): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 3089): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 3089): EnabledAppController: Enabled app scan is pending...
,I/DeviceManagement( 3089): Perf: Scan enabled apps - start...
,I/DeviceManagement( 3089): EnabledAppBuilder: Examining 267 installed apps for DM enabled apps...
,I/DeviceManagement( 3089): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, versionCode=621000240, versionName=6.0.787896
,I/DeviceManagement( 3089): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=234300090, versionName=2.1.784944
,I/DeviceManagement( 3089): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, versionCode=333000980, versionName=3.0.820350
,I/DeviceManagement( 3089): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031431, versionName=6.3.855736
,I/DeviceManagement( 3089): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=639001000, versionName=6.0.811021
,I/DeviceManagement( 3089): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, versionCode=129300230, versionName=1.1.840085
,I/DeviceManagement( 3089): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=441001820, versionName=4.0.840038
,I/DeviceManagement( 3089): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=231000600, versionName=2.0.787746
,I/DeviceManagement( 3089): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
,I/DeviceManagement( 3089): EnabledAppBuilder: Found 9 DM enabled apps.
,I/DeviceManagement( 3089): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
,I/DeviceManagement( 3089): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,I/DeviceManagement( 3089): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
,I/DeviceManagement( 3089): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
,I/DeviceManagement( 3089): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
,I/DeviceManagement( 3089): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
,I/DeviceManagement( 3089): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,I/DeviceManagement( 3089): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,I/DeviceManagement( 3089): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
,I/DeviceManagement( 3089): Perf: Scan enabled apps - complete: 744 ms
I/DeviceManagement( 3089): Perf: *** Enabled app cache update - complete: 745 ms
,I/DeviceManagement( 3089): Perf: *** Config cache update - start...
I/DeviceManagement( 3089): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 3089): ConfigCacheController: *** Updating stale config cache entries...
I/DeviceManagement( 3089): ConfigCacheController: *** Update config cache: updating 0 entries...
,I/DeviceManagement( 3089): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 3089): AlarmController: Scheduling TTL alarm for: 2016.01.11 at 17:04:28.463 CET (due to: com.htc.reportagent)
,I/DeviceManagement( 3089): Perf: *** Config cache update - complete: 126 ms
,I/DeviceManagement( 3089): Perf: *** Cache update - complete: 871 ms
,I/DeviceManagement( 3089): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41add3e0]
,I/DeviceManagement( 3089): WorkflowService: Stopping workflow service
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=3089, uid=10098, userID:0
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3107 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=2768
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2768:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2768
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GAV2    ( 3107): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/PMS     (  905): acquireWL(4251e570): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,I/Icing   ( 2216): Storage manager: low false usage 1.67MB avail 7.46GB capacity 7.85GB
I/ActivityManager(  905): Delay finish: com.google.android.gm/.GoogleMailDeviceStartupReceiver
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=3107, uid=10107, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=3107, uid=10107, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=3107, uid=10107, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=3107, uid=10107, userID:0
,W/Icing   ( 2216): Docstore bad crc 0xa3a985db vs 0xd1ccc170
,I/Gmail   ( 3107): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,E/Icing   ( 2216): Lite index docid 80 ahead of clip 79
,I/Gmail   ( 3107): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3107): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3107): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/Icing   ( 2216): Error while loading LangUtil; unable to load Cld2DetectLanguage: undefined symbol: IcingExtCld2DetectLanguage
,I/Icing   ( 2216): updateResources: need to parse gfv{com.google.android.gms}
,I/Icing   ( 2216): Internal init done: storage state 0
,I/Icing   ( 2216): 13 corpora need re-polling
,I/Icing   ( 2216): Post-init done
,D/MyReportAgent( 2878): ReportService [##] onDestroy(), this =com.htc.reportagent.ReportService@41abb9a0
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/HtcModeClient( 1506): handler message = 4011
,E/HtcModeClient( 1506): Check connection and retry 4 times.
,D/PMS     (  905): acquireWL(424aa918): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 3107 10107 null
,I/Gmail   ( 3107): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,D/PMS     (  905): acquireWL(424aa918): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 3107 10107 null
I/Gmail   ( 3107): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,D/PMS     (  905): acquireWL(424aa918): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 3107 10107 null
,I/Gmail   ( 3107): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=3107, uid=10107, userID:0
I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=2781
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2781:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/ActivityManager(  905): Delay finish: com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver
,I/ActivityManager(  905): Recipient 2781
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=3144 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/htcbackup-core( 3144): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3144): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3144): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3089): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3089): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.qualcomm.timeservice, com.qualcomm.privinit, com.htc.lockscreen, com.htc.checkinprovider, com.htc.home.personalize, com.android.settings, android, com.htc.backupreset, com.htc.guide, com.htc.htcpowermanager, com.android.CSDFunctionG, com.android.inputdevices, com.htc.cirmodule, com.htc.android.htcloglevel, com.android.keychain, com.htc.feedback, com.htc.usage, com.htc.mirrorlinkserver, com.android.providers.settings, com.android.location.fused, com.htc.android.htcsetupwizard, com.htc.drive.activator, com.htc.smartdim, com.htc.backup, com.htc.autobot.cargps.provider]
,I/DeviceManagement( 3089): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/DeviceManagement( 3089): WorkflowService: Starting workflow service
I/DeviceManagement( 3089): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41de8798] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3089): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3089): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3089): SessionStateController: Checking invariants...
,W/ContextImpl( 3144): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
,I/DeviceManagement( 3089): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3089): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41de8798]
,I/DeviceManagement( 3089): WorkflowService: Stopping workflow service
,I/Icing   ( 2216): Indexing 8DE9E393F90B6C584E1520317D3A5B8F674486CB from com.google.android.music
,I/Icing   ( 2216): Indexing BB587E213BBC0BFFE2BCE580EE28DBD95DF1453A from com.google.android.googlequicksearchbox
,I/ActivityManager(  905): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=3165 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/MusicStore( 3165): Database version: 95
,I/htcbackup-core( 3144): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2016.01.05 at 14:02:16.961 CET] interval end=[2016.01.12 at 14:02:16.961 CET]
,W/ContextImpl( 3165): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=3182 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  905): killProcessQuiet, pid=2803
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2803:com.htc.HTCSpeaker/u0a55 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2803
,W/ContextImpl( 3165): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3165): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/WIFI_ICON( 1113): WifiActivity: 0
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3165): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3165): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3165, uid=10154, userID:0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.music (pid 3165): Registered
,I/MediaRouter( 3165): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,I/NetworkMonitor( 3165): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (3165/10154)
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/MediaRouter( 3165): getSelectedRoute
,I/NetworkMonitor( 3165): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3165/10154)
,I/Icing   ( 2216): Indexing done 8DE9E393F90B6C584E1520317D3A5B8F674486CB
,D/Process (  905): killProcessQuiet, pid=2818
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/dalvikvm( 3182): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 3182): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
I/ActivityManager(  905): Killing 2818:com.htc.video/u0a56 (adj 15): empty #17
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3165, uid=10154, userID:0
E/dalvikvm( 3182): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 3182): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,V/JNIHelp ( 3182): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
I/ActivityManager(  905): Recipient 2818
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/Babel   ( 3182): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3182): MmsConfig.loadMmsSettings
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/MmsCustomizationProvider( 2850): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2850): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3182): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3182): MmsConfig.loadFromDatabase
,E/Babel   ( 3182): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3182): MmsConfig.loadFromResources
,E/Babel   ( 3182): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3182): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3182, uid=10111, userID:0
,W/Settings( 3182): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3182, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3182, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3182, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3182, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3182, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3182, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3182, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3182, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3182, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3182, uid=10111, userID:0
,V/Babel   ( 3182): babel boot account: thalitester@gmail.com
,V/Babel   ( 3182): babel boot account: SMS
,I/Icing   ( 2216): Indexing done BB587E213BBC0BFFE2BCE580EE28DBD95DF1453A
,I/Icing   ( 2216): Indexing 5EB2E284CF4EDD4D9B15EDEF20DB018AA0F516E7 from com.google.android.googlequicksearchbox
,I/Icing   ( 2216): Indexing E64FD610CFD41F0314A767D821A892F56CB42075 from com.google.android.music
,I/Icing   ( 2216): Indexing 5FBF329EEA3762588FCFDF656F4760D667A6CE6F from com.google.android.gm
,I/Icing   ( 2216): Indexing 9FB268AF627D3B41F001A4A526DEFACC43F8B349 from com.google.android.googlequicksearchbox
,D/Process (  905): killProcessQuiet, pid=2833
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/Icing   ( 2216): Indexing 6BF2A10538AC784430D015DFDEF5FFD283FAB129 from com.google.android.music
,I/Icing   ( 2216): Indexing DE908E4E28DE5B4AA6C050388663D6A709656700 from com.google.android.music
I/ActivityManager(  905): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=3213 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  905): Killing 2833:com.htc.lmw/u0a59 (adj 15): empty #17
I/Icing   ( 2216): Indexing 8F8DB811889A44B12F43D8D64E4CC542F3AA7E00 from com.google.android.googlequicksearchbox
I/Icing   ( 2216): Indexing 49968A4243E824BEB83FE6AC9EB06AABE3EC6FA2 from com.google.android.apps.books
I/Icing   ( 2216): Indexing FB19DFDA39B50591853B1A565AE2C70C24160BE0 from com.google.android.videos
I/Icing   ( 2216): Indexing 3E78574859FB8ED28F43D3ECB139F4117F00AB29 from com.google.android.googlequicksearchbox
I/Icing   ( 2216): Indexing FDD14680FAC7BB46102C8E9974495DEFD88BF950 from com.google.android.videos
,I/ProviderInstaller( 3182): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  905): Recipient 2833
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  905): sending alarm PendingIntent{42576d68: PendingIntentRecord{427b1c10 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=49634, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{424ef058: PendingIntentRecord{42582318 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=49640, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{424e7458: PendingIntentRecord{41d4d8d0 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=49503, Int=259200000
,V/AlarmManager(  905): sending alarm PendingIntent{41d72620: PendingIntentRecord{423e5fa0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=49655, Int=0
,I/Icing   ( 2216): Indexing done 5EB2E284CF4EDD4D9B15EDEF20DB018AA0F516E7
,D/Process (  905): killProcessQuiet, pid=2405
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=3231 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/ActivityManager(  905): Killing 2405:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2405
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Delay finish: com.htc.htccupd/.HtcCupdReceiver
I/GAV2    ( 2972): Thread[GAThread,5,main]: No campaign data found.
,I/HtcCupdXmlParser( 3231): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
D/ActivityThread( 3231): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2216/10028)
,I/Icing   ( 2216): Indexing done E64FD610CFD41F0314A767D821A892F56CB42075
,I/HtcCupdXmlParser( 3231): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,I/Icing   ( 2216): Indexing done 5FBF329EEA3762588FCFDF656F4760D667A6CE6F
,I/AlarmManager(  905): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
,I/AlarmManager(  905): [AlarmQueuing] post alarm-list load task
,I/AlarmManager(  905): [AlarmQueuing] init alarm queuing list
,I/ActivityManager(  905): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=3248 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=2878
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2878:com.htc.reportagent/u0a65 (adj 15): empty #17
,D/ResetNotifyBootCompleteReceiver( 1242): Receive bootcomplete intent
,W/ContextImpl( 1242): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2878
,I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@4285c4a0
,I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@423b96e0
,I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@424bd478
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  905): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  905): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  905): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
,I/AlarmManager(  905): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
,D/Process (  905): killProcessQuiet, pid=2927
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=3262 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 2927:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/Icing   ( 2216): Indexing done 9FB268AF627D3B41F001A4A526DEFACC43F8B349
,D/AppTag  ( 3262): getInstance(Context context)
,D/AppTag  ( 3262): getInstance(Context context)
,D/AppTag  ( 3262): onCreate()
,D/QXDM2SD:HtcNative( 1242): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,I/ActivityManager(  905): Recipient 2927
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3277 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/Settings:HtcSettingsApplication( 3277): [3277/3277] onCreate()
W/ContextImpl( 3277): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/Icing   ( 2216): Indexing done 6BF2A10538AC784430D015DFDEF5FFD283FAB129
,D/Process (  905): killProcessQuiet, pid=2895
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
I/ActivityManager(  905): Killing 2895:com.android.vending/u0a73 (adj 15): empty #17
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=3290 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2943
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 2943:com.htc.showme/u0a82 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2943
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2895
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3290): -onCreate()
,V/Settings:HtcSettingsApplication( 3290): [3290/3290] onCreate()
,I/Icing   ( 2216): Indexing done DE908E4E28DE5B4AA6C050388663D6A709656700
W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/TetherSettings( 3290): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3290): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3290): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3290): Cust_ConnectToPC   : spcsc>false
D/        ( 3290): Cust_ConnectToPC   : IPT>true
,D/        ( 3290): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3290): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3290): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3290): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3290): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3290): Cust_ConnectToPC   : spcsc>false
D/        ( 3290): Cust_ConnectToPC   : IPT>true
D/        ( 3290): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3290): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3290): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3290): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3290): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,I/SmartNS_Utility( 3290): setISNotification
,D/SmartNS_Utility( 3290): usb_cable_connect = 1
,D/SmartNS_Utility( 3290): usb_denied = 0
,I/SmartNS_PSService( 3290): usb notificaiton:true
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 3290): usb_cable_connect = 1
D/SmartNS_Utility( 3290): usb_denied = 0
,I/SmartNS_PSService( 3290): usb notificaiton:true
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (3290/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (3290/1000)
D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/Process (  905): killProcessQuiet, pid=2958
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/RemoteViews( 1113): com.android.settings (true,33751552)
I/ActivityManager(  905): Killing 2958:com.htc.updater/u0a84 (adj 15): empty #17
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41b2eca8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.android.settings 2 9 1 10
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2958
,I/RemoteViews( 1113): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1113): com.android.settings 3 1 10
,I/Icing   ( 2216): Indexing done 8F8DB811889A44B12F43D8D64E4CC542F3AA7E00
I/ActivityManager(  905): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=3305 uid=9987 gids={49987}
,W/ActivityManager(  905): Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{42572dd8 2216:com.google.android.gms/u0a28} (pid=2216, uid=10028) that is not exported from uid 10094
I/SensorManager(  905): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@41d30538, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41d30538, eanble = 1, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42077c00
W/SensorService(  905): Listener[1] = com.android.server.power.DisplayPowerController$10@421470e8
W/SensorService(  905): Listener[2] = com.htc.smartdim.sensor_eye@41d30538
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  905): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@41d30538, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): enable: get sensor name = CM36282 Proximity sensor
,E/Icing   ( 2216): Cursor call threw an exception
E/Icing   ( 2216): java.lang.SecurityException: Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{42572dd8 2216:com.google.android.gms/u0a28} (pid=2216, uid=10028) that is not exported from uid 10094
E/Icing   ( 2216): 	at android.os.Parcel.readException(Parcel.java:1474)
E/Icing   ( 2216): 	at android.os.Parcel.readException(Parcel.java:1428)
E/Icing   ( 2216): 	at android.app.ActivityManagerProxy.getContentProvider(ActivityManagerNative.java:3037)
E/Icing   ( 2216): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:4999)
E/Icing   ( 2216): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2483)
E/Icing   ( 2216): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1448)
E/Icing   ( 2216): 	at android.content.ContentResolver.acquireUnstableContentProviderClient(ContentResolver.java:1522)
E/Icing   ( 2216): 	at gfg.a(SourceFile:33)
E/Icing   ( 2216): 	at gdl.a(SourceFile:125)
E/Icing   ( 2216): 	at gdm.a(SourceFile:105)
E/Icing   ( 2216): 	at gdn.a(SourceFile:405)
E/Icing   ( 2216): 	at gdn.b(SourceFile:333)
E/Icing   ( 2216): 	at gdr.c(SourceFile:261)
E/Icing   ( 2216): 	at gdr.a(SourceFile:255)
E/Icing   ( 2216): 	at ghz.d(SourceFile:73)
E/Icing   ( 2216): 	at ghu.run(SourceFile:250)
E/Icing   ( 2216): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/Icing   ( 2216): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/Icing   ( 2216): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/Icing   ( 2216): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/Icing   ( 2216): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Icing   ( 2216): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Icing   ( 2216): 	at ghy.run(SourceFile:50)
E/Icing   ( 2216): 	at java.lang.Thread.run(Thread.java:864)
,E/Icing   ( 2216): Aborting indexing of corpus 49968A4243E824BEB83FE6AC9EB06AABE3EC6FA2
,I/Icing   ( 2216): Indexing done 49968A4243E824BEB83FE6AC9EB06AABE3EC6FA2
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{42365d48 u0 ReceiverList{422bd4d0 905 system/1000/u0 local:41c03948}}
,I/ActivityManager(  905): Start proc com.google.android.videos for content provider com.google.android.videos/.search.IcingContentProvider: pid=3319 uid=10165 gids={50165, 3003, 5012, 1028, 1015, 3002}
,D/PMS     (  905): releaseWL(424aa918): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
,D/NfcUiccLockService( 3305): -- To check whether previous opened channel needed to be closed ...
,I/ActivityManager(  905): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=3331 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
,D/Process (  905): killProcessQuiet, pid=2988
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2988:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 3
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41d30538, eanble = 1, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42077c00
W/SensorService(  905): Listener[1] = com.android.server.power.DisplayPowerController$10@421470e8
W/SensorService(  905): Listener[2] = com.htc.smartdim.sensor_eye@41d30538
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  905): Recipient 2988
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=3041
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3343 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 3041:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3041
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.htc.aurora
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO",
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.videos (3319/10165)
,E/YouTube ( 3343): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/PlayMovies( 3319): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/libc    ( 3343): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,D/libc    ( 3343): [NET] getaddrinfo-, SUCCESS
,D/YouTube ( 3343): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,W/PackageManager(  905): Unable to load service info ResolveInfo{425928f8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.videos (pid 3319): Registered
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,I/MediaRouter( 3319): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PlayMovies( 3319): MediaRouteManager.maybeRestoreRoute:188 sessionRestore routeId: 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.videos (3319/10165)
,D/PlayMovies( 3319): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (3343/10168)
,D/PlayMovies( 3319): TransferService.onCreate:52 creating transfer service
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3343): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.videos (3319/10165)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.videos (3319/10165)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=com.google.android.videos.pinning.TransferService$Receiver, state=1, flag=1, pid=3319, uid=10165, userID:0
,D/MediaRouter( 3319): getSelectedRoute
,D/PlayMovies( 3319): MediaRouteManager.onRouteAdded:140 new route added android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE
,D/PlayMovies( 3319): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.videos (3319/10165)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.videos (3319/10165)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.videos (3319/10165)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3319): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.videos/files/Movies
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 3343): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,I/Icing   ( 2216): Indexing done FB19DFDA39B50591853B1A565AE2C70C24160BE0
,D/YouTube ( 3343): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=com.google.android.videos.pinning.TransferService$Receiver, state=2, flag=1, pid=3319, uid=10165, userID:0
,D/Process (  905): killProcessQuiet, pid=3061
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3061:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3061
,D/YouTube ( 3343): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,D/YouTube ( 3343): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.youtube (pid 3343): Registered
,I/MediaRouter( 3343): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/Icing   ( 2216): Indexing done FDD14680FAC7BB46102C8E9974495DEFD88BF950
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/YouTube ( 3343): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 3343): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=-Zm9l0GJkxYlG4JM5Qtk9A&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1452527814&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.youtube (3343/10168)
,D/libc    ( 3343): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3343): [NET] getaddrinfo-,err=8
D/libc    ( 3343): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3343): [NET] getaddrinfo-, 1
,D/libc    ( 3343): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =fdba +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3343): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 3343): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  905): Delay finish: com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver
D/MediaRouter( 3343): getSelectedRoute
,D/YouTube ( 3343): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3343): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
,D/YouTube ( 3343): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
,D/YouTube ( 3343): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (3343/10168)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (3343/10168)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 43
D/libc    (  363): [NET]res_nsend:resplen=96
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3343): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (3343/10168)
,D/YouTube ( 3343): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3343): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 3343): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,D/Process (  905): killProcessQuiet, pid=3073
I/ActivityManager(  905): Resuming delayed broadcast
W/BroadcastQueue(  905): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/ActivityManager(  905): Killing 3073:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  905): Recipient 3073
,I/Icing   ( 2216): Indexing done 3E78574859FB8ED28F43D3ECB139F4117F00AB29
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1402): receiver - intent: android.intent.action.USER_PRESENT
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
D/TetherSettings( 3290): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3290): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3290): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3290): Cust_ConnectToPC   : spcsc>false
D/        ( 3290): Cust_ConnectToPC   : IPT>true
D/        ( 3290): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3290): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3290): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3290): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3290): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3290): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): releaseWL(4251e570): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  905): Delay finish: com.android.settings/.PSReceiver
,I/SmartNS_PSService( 3290): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3290): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3290):  defaultType:0
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(426df690): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,I/ActivityManager(  905): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3419 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/PMS     (  905): releaseWL(426df690): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(42622508): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(42622508): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(422df0a0): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/browser ( 3419): Browser versionCode = 760001523 versionName = 7.0.2512153020
D/PMS     (  905): releaseWL(422df0a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/GoogleConversionPing( 3343): Ping responded with response code 200
,W/SWE_UI  ( 3419): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3419): Loading: swewebviewchromium
,I/LibraryLoader( 3419): Time to load native libraries: 34 ms (timestamps 4210-4244)
,I/LibraryLoader( 3419): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3419): Initializing chromium process, renderers=9
I/LibraryLoader( 3419): Expected native library version number "",actual native library version number ""
,I/chromium( 3419): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,I/SensorManager(  905): mEventCount = 300
,I/Adreno-EGL( 3419): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3419): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3419): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3419): Local Branch: 
I/Adreno-EGL( 3419): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3419): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3419):                  aa63bbd948f41d15fc72f585e
,D/Process (  905): killProcessQuiet, pid=3107
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,V/IccIntentReceiver( 1294): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  905): Killing 3107:com.google.android.gm/u0a107 (adj 15): empty #17
,I/SIMStateChangeReceiver( 1506): SIM state: ABSENT
I/SIMStateChangeReceiver( 1506): phoneType = 0
,I/SIMStateChangeReceiver( 1506): remove notification
,I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3459 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  905): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3471 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=3144
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3144:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3144
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemReader( 2850): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  905): Recipient 3107
,D/SmsReceiver( 2850): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2850): onReceive()
D/ExchangePolicystatus( 2850): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2850): onReceive(): else
,D/Process (  905): killProcessQuiet, pid=3089
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Killing 3089:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/HtcBroadcastReceiver( 1242): onReceive: android.intent.action.SIM_STATE_CHANGED
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3486 uid=10038 gids={50038}
,W/AccTypeManager( 3471): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3471): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3501 uid=10077 gids={50077}
,D/Process (  905): killProcessQuiet, pid=3182
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3182:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3089
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SMSBackup( 3501): Got a database change event
,D/AccTypeManager( 3471): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/Process (  905): killProcessQuiet, pid=3213
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3213:com.htc.backupreset/1000 (adj 15): empty #17
,W/WeatherUtility( 1113): can't get weather sync account
I/ActivityManager(  905): Recipient 3213
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3515 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,W/WeatherRequest( 1113): request cur loc, but there is no sys cur
,I/ActivityManager(  905): Recipient 3182
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/ExternalAccountType( 3471): Unsupported attribute readOnly
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,W/AccTypeManager( 3471): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3471): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41b3ef10 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,D/CalendarApplication( 3515): onCreate
D/ProviderChangeReceiver( 3515): ---------------------------------------------------
D/ProviderChangeReceiver( 3515): ProviderChangeReceiver onReceive, start to update notification!
,D/AccTypeManager( 3471): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/AlertService( 3515): start to updateAlertNotification!
,W/ContextImpl( 3277): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/AlertService( 3515): No fired or scheduled alerts
D/HtcAlertUtils( 3515): -- cancelReminderNotification --
D/HtcAlertUtils( 3515): broadcastExistReminder!
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/ExternalAccountType( 3471): Unsupported attribute readOnly
,D/Process (  905): killProcessQuiet, pid=3165
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Killing 3165:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WIFI_ICON( 1113): WifiActivity: 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ActivityManager(  905): Recipient 3165
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  905): Client com.google.android.music (pid 3165): Died!
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2526/10021)
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3532 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [5][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/ACRA    ( 3532): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 3532): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 3532): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 3532): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 3532): Preparing secondary program dexes.
V/DexLibLoader( 3532): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 3532): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3532): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3532): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 3532): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 3532): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 3532): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 3532): Dex already copied
D/OdexVerifier( 3532): Odex verification is skipped.
,V/DexLibLoader( 3532): Creating class loader
,W/asset   ( 1270): Copying FileAsset 0x638fe1f0 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,V/DexLibLoader( 3532): Finished creating class loader
V/DexLibLoader( 3532): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 3532): Dex already copied
D/OdexVerifier( 3532): Odex verification is skipped.
,V/DexLibLoader( 3532): Creating class loader
E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1270): onLoadItems() -
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41b3ef10 -
,V/DexLibLoader( 3532): Finished creating class loader
V/DexLibLoader( 3532): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 3532): Dex already copied
D/OdexVerifier( 3532): Odex verification is skipped.
,V/DexLibLoader( 3532): Creating class loader
,V/DexLibLoader( 3532): Finished creating class loader
,V/DexLibLoader( 3532): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 3532): Dex already copied
D/OdexVerifier( 3532): Odex verification is skipped.
,V/DexLibLoader( 3532): Creating class loader
,V/DexLibLoader( 3532): Finished creating class loader
,V/DexLibLoader( 3532): Verifying classes from secondary dexes.
,D/DexLibLoader( 3532): DexLibLoader.ensureDexLoaded took 99 ms
,D/PhoneApp( 1242): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1242): -- N1 =0
,D/PhoneApp( 1242): -- N2 =0
,D/PhoneApp( 1242): -- N3 =0
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  905): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3545 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  905): sending alarm PendingIntent{41dae4e8: PendingIntentRecord{425701b8 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=53384, Int=0
,I/ActivityManager(  905): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3559 uid=10091 gids={50091, 3003, 5012}
,D/MdScBoot( 3545): [728.1.] 30@-165625 -> 40@-165656
,D/Process (  905): killProcessQuiet, pid=3231
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  905): killProcessQuiet, pid=3248
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3231:com.htc.htccupd/u0a17 (adj 15): empty #17
I/ActivityManager(  905): Killing 3248:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  905): Recipient 3231
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3248
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1506): handler message = 4011
,E/HtcModeClient( 1506): Check connection and retry 5 times.
,W/dalvikvm( 3532): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3532): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3532): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3532): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3532): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3532): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3532): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3532): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3532): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 3532): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 3532): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3532/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3532): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 3532): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 3532): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=3262
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3262:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,D/PMS     (  905): acquireWL(42770250): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2216 10028 null
,I/ActivityManager(  905): Recipient 3262
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42749688): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(42770250): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2216/10028)
,D/GCM     ( 1367): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1367/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1367/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1367/10028)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/PMS     (  905): releaseWL(42749688): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1402): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2216/10028)
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3580 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
,D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1402): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1402): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1402): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1402): service - handleMessage() setting current location null
D/AutoSetting( 1402): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1402): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
,W/fb4a(:<default>):UserScope( 3532): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 3532): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 3532): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 3580): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3580): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3580): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3580): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3595 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3305
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3305:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (3580/10078)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (3580/10078)
,D/PMS     (  905): acquireWL(425af278): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2216 10028 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (3580/10078)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3532): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/PMS     (  905): acquireWL(4259ac08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2216 10028 null
D/PMS     (  905): releaseWL(425af278): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I/ActivityManager(  905): Recipient 3305
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2216/10028)
,I/CheckinService( 2216): Preparing to send checkin request
,I/EventLogService( 2216): Accumulating logs since 1452527801778
,I/GoogleHttpClient( 2216): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2216): Using GMS GoogleHttpClient
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3613 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3331
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
E/dalvikvm( 3532): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 3532): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3532): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 3532): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3532): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 3532): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
I/ActivityManager(  905): Killing 3331:com.android.smith/u0a163 (adj 15): empty #17
D/WifiService(  905): New client listening to asynchronous messages
I/ActivityManager(  905): Recipient 3331
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2216/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2216/10028)
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 3532): Grow heap (frag case) to 9.970MB for 84664-byte allocation
E/dalvikvm( 3532): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 3532): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3532): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/dalvikvm( 3532): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 3532): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3613): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3613): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/GAV2    ( 3613): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3613): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3613): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 3532): Grow heap (frag case) to 9.984MB for 28144-byte allocation
,W/dalvikvm( 3532): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3532): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 3532): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3532): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 3532): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3532): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 3532): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,I/dalvikvm-heap( 3532): Grow heap (frag case) to 10.027MB for 39954-byte allocation
,I/GoogleHttpClient( 1367): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1367): Using GMS GoogleHttpClient
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (3613/10151)
I/dalvikvm-heap( 3532): Grow heap (frag case) to 10.103MB for 79892-byte allocation
V/WebViewChromiumFactoryProvider( 3613): Binding Chromium to main looper Looper (main, tid 1) {41aa52f8}
I/NotificationStore( 1367): System rebooted after Notification storage file was last written
I/LibraryLoader( 3613): Expected native library version number "",actual native library version number ""
I/NotificationStore( 1367): Deleting the file
I/chromium( 3613): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3613): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(42420c48): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  905): acquireWL(42302d90): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  905): releaseWL(42420c48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
E/AudioManagerAndroid( 3613): BLUETOOTH permission is missing!
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/Adreno-EGL( 3613): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3613): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3613): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3613): Local Branch: 
I/Adreno-EGL( 3613): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3613): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3613):                  aa63bbd948f41d15fc72f585e
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2216): awaiting user notification for token
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41b08318 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 2 7 3 12
,I/NSApplication( 3613): Starting up...
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (3613/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (3613/10151)
,I/ActivityManager(  905): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3651 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3319
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3319:com.google.android.videos/u0a165 (adj 15): empty #17
,I/dalvikvm-heap( 3532): Grow heap (frag case) to 10.289MB for 75760-byte allocation
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3663 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3532/10026)
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{424e8b80 u0 ReceiverList{424b9988 3532 com.facebook.katana/10026/u0 remote:4233bec0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{424e8b80 u0 ReceiverList{424b9988 3532 com.facebook.katana/10026/u0 remote:4233bec0}}
D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4258f860 u0 ReceiverList{4258f800 3532 com.facebook.katana/10026/u0 remote:41d18228}}
,I/ActivityManager(  905): Recipient 3319
,D/MediaRouterService(  905): Client com.google.android.videos (pid 3319): Died!
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MultiDex( 3663): install
,I/MultiDex( 3663): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,I/MultiDex( 3663): loading existing secondary dex files
,I/MultiDex( 3663): load found 1 secondary dex files
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3532/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3532/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3532/10026)
I/MultiDex( 3663): install done
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,I/ProviderInstaller( 3663): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  905): acquireWL(42599728): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1438 10028 null
,D/PMS     (  905): releaseWL(42599728): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/GCoreFlp( 1438): Unknown pending intent to remove.
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(4255cfa8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1438 10028 null
D/PMS     (  905): releaseWL(4255cfa8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3651/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3651/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3651/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3651/10160)
D/PMS     (  905): acquireWL(42580018): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3651 10160 null
,D/Process (  905): killProcessQuiet, pid=3343
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 3532): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/ActivityManager(  905): Killing 3343:com.google.android.youtube/u0a168 (adj 15): empty #17
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0,
D/AlertReceiver( 3515): beginStartingService
,W/ContextImpl( 3532): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/PMS     (  905): acquireWL(423a9068): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3515 10013 null
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(425af850): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3651 10160 null
D/PMS     (  905): acquireWL(42685aa0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2216 10028 null
D/PMS     (  905): releaseWL(42580018): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/PMS     (  905): releaseWL(42685aa0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/AlertService( 3515): start to updateAlertNotification!
,D/AlertService( 3515): No fired or scheduled alerts
,D/HtcAlertUtils( 3515): -- cancelReminderNotification --
,D/HtcAlertUtils( 3515): broadcastExistReminder!
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  905): releaseWL(423a9068): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
W/AlertReceiver( 3515): stopSelfResult true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=3696 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,W/WeatherRequest( 1113): request cur loc, but there is no sys cur
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/PMS     (  905): releaseWL(425af850): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/ActivityManager(  905): Recipient 3343
,D/MediaRouterService(  905): Client com.google.android.youtube (pid 3343): Died!
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3711 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 3696): can't get weather sync account
,I/dalvikvm-heap( 3651): Grow heap (frag case) to 15.217MB for 1821008-byte allocation
,W/WeatherRequest( 3696): request cur loc, but there is no sys cur
,W/Settings( 3696): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1270): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1270): com.htc.widget.weatherclock 1 14 17
,D/PMS     (  905): acquireWL(4276ce00): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3711 10070 null
,D/PMS     (  905): acquireWL(42816bb8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3711 10070 null
,D/PMS     (  905): releaseWL(4276ce00): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/TodoTaskshortcut( 3711): update TASK shortcut>
I/ActivityManager(  905): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3727 uid=10090 gids={50090, 3003, 5012, 1028}
,I/TodoTaskNotifyService( 3711): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 3711): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 3711): stopSelfResult true
,I/WorldClock.Global( 3727): isHtcDevice = true
D/Process (  905): killProcessQuiet, pid=3290
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  905): releaseWL(42816bb8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Killing 3290:com.android.settings/1000 (adj 15): empty #17
,I/WorldClock.Global( 3727): isHtcDevice = true
W/ContextImpl( 3277): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 3727): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 3727): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 3727): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1113): receive(android.intent.action.ALARM_CHANGED,1,false)
I/ActivityManager(  905): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3742 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  905): Recipient 3290
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=3419
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3419:com.htc.sense.browser/u0a12 (adj 15): empty #17
,D/TimeService( 3742): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452527818497
,D/Process (  905): killProcessQuiet, pid=3459
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Killing 3459:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/AdsMeasurementBroadcastReceiver( 2216): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2216): Unauthorized to start the main service
I/ActivityManager(  905): Recipient 3459
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 3696): can't get weather sync account
,I/ActivityManager(  905): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3758 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,W/WeatherRequest( 3696): request cur loc, but there is no sys cur
,W/Settings( 3696): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DemoRecovery.RestoreReceiver( 3758): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3758): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1270): com.htc.widget.weatherclock (true,33751552)
,I/RestoreService( 3758): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
,I/RemoteViews.Performance( 1270): com.htc.widget.weatherclock 1 7 17
I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(425656a0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3711 10070 null
D/PMS     (  905): acquireWL(42563260): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3711 10070 null
D/PMS     (  905): releaseWL(425656a0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  905): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3711): update TASK shortcut>
,I/TodoTaskNotifyService( 3711): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/ActivityManager(  905): Recipient 3419
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): releaseWL(42563260): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,W/Settings( 3663): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/NotifyReceiver( 3711): stopSelfResult true
,D/Process (  905): killProcessQuiet, pid=3471
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3775 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  905): Killing 3471:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3471
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3787 uid=10081 gids={50081, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=3501
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Process (  905): killProcessQuiet, pid=3486
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/AdsMeasurementBroadcastReceiver( 2216): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2216): Unauthorized to start the main service
I/ActivityManager(  905): Killing 3501:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
I/ActivityManager(  905): Killing 3486:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #18
I/ActivityManager(  905): Recipient 3501
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3486
I/BroadcastQueue(  905): Schedule to resend BroadcastRecord{4257c690 u0 com.htc.mms.DB_CHANGE callingPid=1242 callingUid=1001} for ResolveInfo{4257c150 com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent m=0x108000} of com.htc.widget.hmsproc1
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3799 uid=10038 gids={50038}
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3812 uid=10077 gids={50077}
,D/Process (  905): killProcessQuiet, pid=3532
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3532:com.facebook.katana/u0a26 (adj 15): empty #17
,D/SMSBackup( 3812): Got a database change event
,I/ActivityManager(  905): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3826 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  905): killProcessQuiet, pid=3545
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3545:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3545
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Adreno-EGL( 3663): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3663): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3663): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3663): Local Branch: 
I/Adreno-EGL( 3663): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3663): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3663):                  aa63bbd948f41d15fc72f585e
,I/ImageRamCache( 3826): create image Cache, size: 31457280.
I/ImageRamCache( 3826): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3826): create image Cache, size: 12582912.
,I/FeedSettings( 3826): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3826): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3826): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3826): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3826): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3826): loadGridSize() with Alternative
,I/ActivityManager(  905): Recipient 3532
,D/CustomHighlightReceiver( 3826): [custom highlight] onReceive
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
D/PMS     (  905): acquireWL(41fb5270): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1438 10028 null
D/PMS     (  905): acquireWL(41ee4688): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1438 10028 null
,D/CustomHighlightService( 3826): [custom highlight] onHandleIntent
,D/NewsDB  ( 3826): set custom highlight []
I/ActivityManager(  905): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/PMS     (  905): releaseWL(41fb5270): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  905): releaseWL(41ee4688): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/CustomHighlightService( 3826): [custom highlight] set tags 
,D/Process (  905): killProcessQuiet, pid=3559
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Killing 3559:com.htc.mobiledata/u0a91 (adj 15): empty #17
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  905): Recipient 3559
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/WIFI_ICON( 1113): WifiActivity: 3
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ActivityManager(  905): Resuming delayed broadcast
D/MessagingShortcutReceiver( 2850): keep hiding shortcut bubble
D/MessagingShortcut( 2850): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2850): After query: 0
D/MessagingShortcut( 2850): mPresentUnreadCount: -1
D/MessagingShortcut( 2850): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2850): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/Adreno-EGL( 3663): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3663): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3663): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3663): Local Branch: 
I/Adreno-EGL( 3663): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3663): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3663):                  aa63bbd948f41d15fc72f585e
D/DotMatrix( 1584): [EventService] reorderNotification, total:0
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3711): update TASK shortcut>
I/ActivityManager(  905): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1242): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3846 uid=10091 gids={50091, 3003, 5012}
,I/Adreno-EGL( 3663): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3663): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3663): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3663): Local Branch: 
I/Adreno-EGL( 3663): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3663): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3663):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  905): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
D/MessagingNotification( 2850): New incoming message, can't cancel notification now
D/MessagingNotification( 2850): newMsgCnt: 0, false
,I/ActivityManager(  905): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3860 uid=10091 gids={50091, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (3663/10028)
,D/MdScBoot( 3846): [718.1.] 40@-165656
I/ActivityManager(  905): Resuming delayed broadcast
,D/SMSBackup( 3812): Got a database change event
,D/Process (  905): killProcessQuiet, pid=3580
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  905): killProcessQuiet, pid=3595
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3580:com.google.android.setupwizard/u0a78 (adj 15): empty #17
I/ActivityManager(  905): Killing 3595:com.android.chrome/u0a96 (adj 15): empty #17
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinTask( 2216): Sending checkin request (8902 bytes)
I/ActivityManager(  905): Recipient 3580
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3595
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MtpReceiver( 2526): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2526): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2526): [MTP][handleMessage][startService]
,I/ActivityManager(  905): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3873 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/MtpReceiver( 2526): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2526): [MTP][handleMessage]-
,W/ActivityThread( 2216): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/MtpService( 2526): [MTP] startForeground
D/MtpService( 2526): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2526): TotalSize=1918604,MediaCacheLimit=6000
I/RemoteViews( 1113): com.android.providers.media (false,0)
D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews.Performance( 1113): com.android.providers.media 3 2 10
D/MtpService( 2526): [isMtpConnected] connected: true
,I/RemoteViews( 1113): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1113): com.android.providers.media 1 2 15
D/PMS     (  905): acquireWL(41adfcc8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3651 10160 null
,D/libc    ( 2216): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2216): [NET] getaddrinfo-,err=8
D/libc    ( 2216): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2216): [NET] getaddrinfo-, 1
,D/libc    ( 2216): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3726 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/PMS     (  905): releaseWL(41adfcc8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
,D/SyncApplication( 3873): Loading default preferences
,W/Resources( 3873): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 215
D/libc    (  363): [NET]res_nsend:resplen=84
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2216): [NET] getaddrinfo_proxy-, success
,D/WifiService(  905): New client listening to asynchronous messages
,D/SyncApplication( 3873): Overriding preferences with custom values,
,D/libc    ( 2216): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2216): [NET] getaddrinfo-,err=8
,D/SyncApplication( 3873): Updating preferences succeeded
,E/SyncApplication( 3873): Application created.
D/VolumeInfo( 3873): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3873): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3873): Found 0 mount point(s)
,V/VolumeInfo( 3873): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3873): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3873): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3873): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3873): getNewCalendarAuthority()...
,D/SyncApplication( 3873): enableAppOperation()+
,D/SyncApplication( 3873): enableAppOperation()-
,D/HTCUtilities( 3873): isNeorSinged() + 
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3873, uid=10008, userID:0
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3873, uid=10008, userID:0
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3873): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3873): isNeorSinged() return false
,D/CDMountReceiver( 3873): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3873): USB connected to PC
,D/FOTAReceiver( 3873): onReceive() enter 
,D/FOTAReceiver( 3873): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/Process (  905): killProcessQuiet, pid=3613
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3897 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Killing 3613:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3613
,D/Process (  905): killProcessQuiet, pid=3515
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3515:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3515
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3897): -onCreate()
,V/Settings:HtcSettingsApplication( 3897): [3897/3897] onCreate()
,D/TetherSettings( 3897): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3897): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 3897): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3897): Cust_ConnectToPC   : spcsc>false
,D/        ( 3897): Cust_ConnectToPC   : IPT>true
,D/        ( 3897): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3897): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 3897): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3897): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3897): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3897): Cust_ConnectToPC   : spcsc>false
D/        ( 3897): Cust_ConnectToPC   : IPT>true
D/        ( 3897): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3897): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3897): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3897): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3897): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3897): usb_cable_connect = 1
,D/SmartNS_Utility( 3897): usb_denied = 0
,I/SmartNS_NSReceiver( 3897): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3897): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3897): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 3897): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3897): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3897): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3897):  defaultType:0
,I/SmartNS_PSService( 3897): fail notificaiton:false
,D/SmartNS_Utility( 3897): usb_cable_connect = 1
D/SmartNS_Utility( 3897): usb_denied = 0
,I/SmartNS_PSService( 3897): usb notificaiton:true
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (3897/1000)
,I/ActivityManager(  905): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/SmartNS_Utility( 3897): usb_cable_connect = 1
D/SmartNS_Utility( 3897): usb_denied = 0
I/SmartNS_PSService( 3897): usb notificaiton:true
I/RemoteViews( 1113): com.android.settings (true,33751552)
V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/RemoteViews.Performance( 1113): com.android.settings 2 1 10
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (3897/1000)
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/ActivityManager(  905): Resuming delayed broadcast
D/SmartNS_Utility( 3897): usb_cable_connect = 1
,D/SmartNS_Utility( 3897): usb_denied = 0
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/RemoteViews( 1113): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1113): com.android.settings 1 0 10
I/SmartNS_PSService( 3897): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3897): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/ActivityManager(  905): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,W/WeatherUtility( 3696): can't get weather sync account
I/ActivityManager(  905): Resuming delayed broadcast
,D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1270): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1270): com.google.android.googlequicksearchbox 0 1 5
,W/WeatherRequest( 3696): request cur loc, but there is no sys cur
,W/Settings( 3696): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  905): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
,D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
,I/RemoteViews( 1270): pl.k2.droidoaudioteka (false,0)
,I/RemoteViews.Performance( 1270): pl.k2.droidoaudioteka 1 0 8
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(4257f7e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/PMS     (  905): acquireWL(422de0f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  905): releaseWL(422de0f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1270): com.htc.widget.weatherclock (true,33751552)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
I/RemoteViews.Performance( 1270): com.htc.widget.weatherclock 2 8 17
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(4257f7e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2216/10028)
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2216/10028)
D/PMS     (  905): acquireWL(424ea438): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1506 10014 null
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=5 [17][1][0]
I/ActivityManager(  905): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
D/PMS     (  905): releaseWL(424ea438): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,D/PackageBroadcastService( 2216): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1113): com.google.android.gms (false,0)
I/SocialFeedProvider( 1270): +disConnect socialManager
,I/SocialFeedProvider( 1270): disconnect socialManager
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/SocialFeedProvider( 1270): -disConnect socialManager
,I/RemoteViews.Performance( 1113): com.google.android.gms 1 5 12
D/PMS     (  905): acquireWL(426208d0): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,W/CheckinRequestBuilder( 2216): awaiting user notification for token
D/PMS     (  905): releaseWL(426208d0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,V/AlarmManager(  905): sending alarm PendingIntent{4233c838: PendingIntentRecord{4233c088 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=57378, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,I/CheckinTask( 2216): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2216): Unable to close GMS GoogleHttpClient
,I/PeopleContactsSync( 2216): CP2 sync disabled
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2216/10028)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2216, uid=10028, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2216/10028)
,D/PMS     (  905): releaseWL(4259ac08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 2216): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bf3850 that was originally bound here
E/ActivityThread( 2216): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bf3850 that was originally bound here
E/ActivityThread( 2216): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2216): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2216): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2216): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2216): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2216): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2216): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2216): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2216): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2216): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2216): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2216): 	at bks.a(SourceFile:298)
E/ActivityThread( 2216): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2216): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2216): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2216): 	at java.lang.Thread.run(Thread.java:864)
,I/ClockThread( 1113): now=1452527820132 next=59868
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3927 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  905): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3727
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/[PluginManager]RegisterService( 1402): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1402): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Killing 3727:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Recipient 3727
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3943 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3943, uid=10073, userID:0
,D/Finsky  ( 3943): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3943/10073)
,D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3943/10073)
,D/Finsky  ( 3943): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3943): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3943): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3943, uid=10073, userID:0
,D/Process (  905): killProcessQuiet, pid=3277
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Killing 3277:com.android.settings:remote/1000 (adj 15): empty #17
D/Finsky  ( 3943): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3943): [1] 2.run: Finished loading 1 libraries.
,D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_ADDED
I/ActivityManager(  905): Recipient 3277
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2972): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Finsky  ( 3943): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  905): Delaying start of: ServiceRecord{426193e0 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
D/PMS     (  905): acquireWL(424bf1a0): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(424bf1a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): releaseWL(42302d90): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/AlarmManager(  905): sending alarm PendingIntent{41cdb948: PendingIntentRecord{42447728 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=58094, Int=0
,D/PMS     (  905): acquireWL(4236d520): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(4236d520): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(4230c440): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null,
,D/PMS     (  905): releaseWL(4230c440): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(41ef2cc0): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/Process (  905): killProcessQuiet, pid=3742,
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3742:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/PMS     (  905): releaseWL(41ef2cc0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  905): Recipient 3742
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3943): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PMS     (  905): acquireWL(41acddc8): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(41acddc8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  905): acquireWL(423140c8): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(423140c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3980 uid=10098 gids={50098, 3003, 5012}
,I/SocialManager[SocialBiLogHelper]( 3826): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3826): last commit ulog time 1452491635921
,I/SocialManager[SocialBiLogHelper]( 3826): skip commit this time
V/AlarmManager(  905): sending alarm PendingIntent{4238e1f8: PendingIntentRecord{425eb4a0 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452527820876, Int=0
D/PMS     (  905): acquireWL(424e8c48): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(424e8c48): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(42349858): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(42349858): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(42557bf0): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,I/DeviceManagement( 3980): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3980 dbg=false s=true
,I/DeviceManagement( 3980): PackageUpdateReceiver: vvv Package added: [com.example.hello]
D/PMS     (  905): releaseWL(42557bf0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3995 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/Process (  905): killProcessQuiet, pid=3758
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3758:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/PMS     (  905): acquireWL(42010b30): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,I/ActivityManager(  905): Recipient 3758
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(42010b30): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ContactLoggerTask( 2972): canRun() : Disabled
,I/IcingCorporaProvider( 2972): UpdateCorporaTask done [took 461 ms] updated apps [took 431 ms] updated contacts [took 30 ms]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/HtcModeClient( 1506): handler message = 4011
,E/HtcModeClient( 1506): Check connection and retry 6 times.
,I/ActivityManager(  905): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=4012 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (3995/10100)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (3995/10100)
,W/GAV2    ( 3995): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/AlarmManager(  905): sending alarm PendingIntent{424c7e90: PendingIntentRecord{425208f8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452527821578, Int=0
,I/htcbackup-core( 4012): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 4012): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
W/ContextImpl( 4012): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3980): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3980): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.qualcomm.timeservice, com.qualcomm.privinit, com.htc.lockscreen, com.htc.checkinprovider, com.htc.home.personalize, com.android.settings, android, com.htc.backupreset, com.htc.guide, com.htc.htcpowermanager, com.android.CSDFunctionG, com.android.inputdevices, com.htc.cirmodule, com.htc.android.htcloglevel, com.android.keychain, com.htc.feedback, com.htc.usage, com.htc.mirrorlinkserver, com.android.providers.settings, com.android.location.fused, com.htc.android.htcsetupwizard, com.htc.drive.activator, com.htc.smartdim, com.htc.backup, com.htc.autobot.cargps.provider]
W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,I/DeviceManagement( 3980): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/DeviceManagement( 3980): WorkflowService: Starting workflow service
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  905): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4038 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/DeviceManagement( 3980): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41ae8488] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 3980): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/DeviceManagement( 3980): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3980): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3980): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 4038):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  905): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3943): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3943): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/ActivityManager(  905): Resuming delayed broadcast
,W/GAV2    ( 3995): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  905): acquireWL(425c6ad0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3651 10160 null
,D/PMS     (  905): releaseWL(425c6ad0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/DeviceManagement( 3980): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/Process (  905): killProcessQuiet, pid=3775
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  905): Killing 3775:com.htc.stock/u0a81 (adj 15): empty #17
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=37 rxSum=29} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  905): onDataStallAlarm: tag=19602 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19603 delay=15s
I/ActivityManager(  905): Recipient 3775
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,D/LocationManagerService(  905): getAllProviders()=[passive, gps, network]
,I/ActivityManager(  905): Resuming delayed broadcast
,I/DeviceManagement( 3980): SessionStateController: Checking invariants...
,D/Settings:HtcWirelessFeatureFlags( 3897): id/is att sku: 99/false
,W/SystemReader( 3897): Cannot find devicepolicy_lower_fp_quality, use default value instead
I/ActivityManager(  905): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,I/DeviceManagement( 3980): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
W/SystemReader( 3897): Cannot find support_harman, use default value instead
,W/SystemReader( 3897): Cannot find effect_manager_id, use default value instead
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2216/10028)
,I/DeviceManagement( 3980): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41ae8488]
,I/DeviceManagement( 3980): WorkflowService: Stopping workflow service
I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3787
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,E/Settings:HtcWrapHeaderInfo( 3897): no such activity!
I/ActivityManager(  905): Killing 3787:com.htc.stock:remote/u0a81 (adj 15): empty #17
I/ActivityManager(  905): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
I/ActivityManager(  905): Recipient 3787
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2216/10028)
V/AlarmManager(  905): sending alarm PendingIntent{4251c090: PendingIntentRecord{4251be38 com.google.android.gms startService}}, i=null, t=0, cnt=17104, w=84918423, Int=84918423
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(42573f00): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2216 10028 null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3897): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3897): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3897): isSupportMusicChannel(): false
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2216/10028)
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportHomeButton]support         :false
,W/FingerprintManager( 3897): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3897): isSupportVoWifi: null
I/ActivityManager(  905): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3897): Failed to find provider info for com.htc.vowifi
,I/AdsMeasurementBroadcastReceiver( 2216): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2216): Unauthorized to start the main service
,D/SnetService( 2216): snet destroyed
I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4071 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3897): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3897): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3897): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3897): [supportHomeButton]support         :false
,W/FingerprintManager( 3897): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3897): isSupportVoWifi: null
,D/PowerUsageService( 4071): call getInstance()
I/ActivityManager(  905): Cannot resolve ContentProvider=com.htc.vowifi
W/ContextImpl( 4071): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread( 3897): Failed to find provider info for com.htc.vowifi
I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 4071): MY_DEBUG = false
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3943): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3943): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3943): [1] DailyHygiene.reschedule: Scheduling new run in 98 minutes (failures=3)
,D/Process (  905): killProcessQuiet, pid=2850
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2850:com.htc.sense.mms/u0a64 (adj 15): empty #17
I/ActivityManager(  905): Waited long enough for: ServiceRecord{424e4c40 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Recipient 2850
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42642c00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4071 1000 null
,I/ActivityManager(  905): Delay finish: com.htc.task/.TodoTaskReceiver
,D/PMS     (  905): releaseWL(42573f00): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,W/WeatherUtility( 1113): can't get weather sync account
,D/WeatherUtility( 1402): Weather sync is On
,D/WSP     ( 1402): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,I/ActivityManager(  905): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,W/WeatherUtility( 3696): can't get weather sync account
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/ActivityManager(  905): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=4092 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,W/WeatherRequest( 3696): request cur loc, but there is no sys cur
,W/Settings( 3696): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1270): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  905): Resuming delayed broadcast
,W/BatSI   (  905): Couldn't get kernel wake lock stats
I/RemoteViews.Performance( 1270): com.htc.widget.weatherclock 1 7 17
,I/ActivityManager(  905): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=4106 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,I/EASAppSvc( 4092): [ NA ]- onCreate()
,I/EASAppSvc( 4092): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3711): put()
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.android.mail (4092/10063)
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.htc.android.mail (4092/10063)
,D/ConnectivityService(  905): getNetworkInfo networkType=55 called by com.htc.android.mail (4092/10063)
,I/SensorManager(  905): mEventCount = 450
,I/EASAppSvc( 4092): [ NA ]- onDestroy()
,I/EASAppSvc( 4092): [ NA ]> uninitEASService
,I/EASRequestController( 4092): [ NA ]release
,I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/EASAppSvc( 4092): [ NA ]< uninitEASService
I/EASAppSvc( 4092): [ NA ]- onCreate()
I/EASAppSvc( 4092): [ NA ]> onUpgrade: version = 63
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.android.mail (4092/10063)
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.htc.android.mail (4092/10063)
,D/ConnectivityService(  905): getNetworkInfo networkType=55 called by com.htc.android.mail (4092/10063)
,D/ORMLib  ( 3711): put()
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4139 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3846
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3846:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3846
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/EASAppSvc( 4092): [ NA ]- onDestroy()
I/EASAppSvc( 4092): [ NA ]> uninitEASService
,I/EASRequestController( 4092): [ NA ]release
I/ActivityManager(  905): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4151 uid=10067 gids={50067, 3003, 5012}
,I/EASAppSvc( 4092): [ NA ]< uninitEASService
,D/Process (  905): killProcessQuiet, pid=3860
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 3860:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/MusicStore( 4139): Database version: 95
,I/ActivityManager(  905): Recipient 3860
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4139): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ORMLib  ( 3711): put()
,W/ContextImpl( 4139): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4139): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4139): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4139): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4139, uid=10154, userID:0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.music (pid 4139): Registered
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
I/MediaRouter( 4139): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  905): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/NetworkMonitor( 4139): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4139/10154)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/MediaRouter( 4139): getSelectedRoute
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,I/NetworkMonitor( 4139): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4139/10154)
,I/ActivityManager(  905): Resuming delayed broadcast
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4139, uid=10154, userID:0
D/TelephonyReceiver( 1242): bind: true
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/Process (  905): killProcessQuiet, pid=3799
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Killing 3799:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Recipient 3799
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=4180 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
I/ActivityManager(  905): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=4192 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/DFPI.PIReciver( 4192): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 4192): onHandleIntent
,I/DFPI.ApkInstallService( 4192): Media Scan Finished Case 
,D/MessageFrequencyProvider( 4180): onCreate
,I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 4192): check CID = HTC__032
,I/DFPI.ApkInstallService( 4192): There is no Demo.apk in sd card or phone storage
,V/GetPrviateResource( 4180): GetPrviateResource
,V/GetPrviateResource( 4180): GetPrviateResource
D/Process (  905): killProcessQuiet, pid=3812
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GenericMessagesProvider( 4180): query uri: content://htc-messages/wappush/count
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Killing 3812:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
E/SQLiteLog( 4180): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 4180): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 4180): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 4180): DB info: errno = 2, errno message = No such file or directory
E/SQLiteDatabase( 4180): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 4180): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 4180): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 4180): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4180): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4180): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 4180): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 4180): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 4180): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 4180): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 4180): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 4180): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 4180): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 4180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 4180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 4180): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 4180): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 4180): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 4180): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 4180): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 4180): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  905): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=4208 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
D/Process (  905): killProcessQuiet, pid=3873
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
I/ActivityManager(  905): Killing 3873:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/ActivityManager(  905): Recipient 3873
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (4208/10051)
,I/ActivityManager(  905): Recipient 3812
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (4208/10051)
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{4256a970 u0 ReceiverList{4256a910 4208 com.htc.musicenhancer/10051/u0 remote:4256a618}}
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4208): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,D/MessageCustFlag( 4180): sense_version=6.0
,D/BTAccessoryUtil( 4180): createReceiver
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/BTAccessoryUtil( 4180): registerReceiver return intent = null
D/MessageCustFlag( 4180): sku_id=99
W/SystemReader( 4180): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4180): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4180): networkCode: 
,D/MessageCustFlag( 4180): sku_id=99
D/MmsConfig( 4180): SIE smsPri: null
,D/MmsConfig( 4180): networkCode: 
,D/HtcTelephonyCapability( 4180): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4180): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4180): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4180): Cannot find qct_8960_interface, use default value instead
,V/AlarmManager(  905): sending alarm PendingIntent{425b28b0: PendingIntentRecord{427108a8 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1452527823360, Int=0
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=4227 uid=10080 gids={50080, 5001, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3927
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3927:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3927
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 4227): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4227): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4227): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 4227): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4227): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 4227): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  905): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 4227): MODE_GSM access default DB
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 4227): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4227): MODE_GSM access default DB
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3826
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3826:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3826
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DFPI.PIReciver( 4192): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 4192): onHandleIntent
,I/DFPI.ApkInstallService( 4192): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4192): check CID = HTC__032
,I/DFPI.ApkInstallService( 4192): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/SoundPicker( 4227): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4227): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4227): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 4227): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4227): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4227): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4227): MODE_GSM access default DB
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9,
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 4227): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4227): MODE_GSM access default DB,
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  905): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/DFPI.PIReciver( 4192): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 4192): onHandleIntent
I/DFPI.ApkInstallService( 4192): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4192): check CID = HTC__032
,I/DFPI.ApkInstallService( 4192): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/SoundPicker( 4227): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4227): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.google.android.videos
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/SoundPicker( 4227): SoundPickerReceiver [onReceive] startService
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/SoundPicker( 4227): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4227): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4227): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4227): MODE_GSM access default DB
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 4227): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4227): MODE_GSM access default DB
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  905): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1270): AllAppsMgr addApps, already exist: ApplicationInfo(id=19, title=Play Movies & TV, componentNameComponentInfo{com.google.android.videos/com.google.android.youtube.videos.EntryPoint} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
E/ExternalAccountType( 1327): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/Launcher( 1270): Deferring update until onResume
,D/Launcher( 1270): waitUntilResume // bindAppsUpdated
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  905): Resuming delayed broadcast
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/ActivityManager(  905): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  905): releaseWL(42642c00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/MediaStoreImporter( 4139): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 4192): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  905): Resuming delayed broadcast
I/DFPI.ApkInstallService( 4192): onHandleIntent
,I/DFPI.ApkInstallService( 4192): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4192): check CID = HTC__032
,I/DFPI.ApkInstallService( 4192): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3995
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SoundPicker( 4227): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/ContextImpl( 4227): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/ActivityManager(  905): Killing 3995:com.google.android.apps.docs/u0a100 (adj 15): empty #17
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/SoundPicker( 4227): SoundPickerReceiver [onReceive] startService
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 4227): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4227): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4227): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4227): MODE_GSM access default DB
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 4227): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4227): MODE_GSM access default DB
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:66, mTXpacketCount:43, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,D/AutoSetting( 1402): service - mRequestRunnable: screen on delay 10s, request NLP now
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
D/AutoSetting( 1402): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1402): service - requestNLP() NetworkLocationProvider not enabled
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4227): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4227): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 4227): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4227): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  905): Recipient 3995
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/PackageManager(  905): Unable to load service info ResolveInfo{425da9a0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
,I/MediaStoreImporter( 4139): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(425f44d0): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1506 10014 null
I/ActivityManager(  905): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  905): releaseWL(425f44d0): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4252 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/Process (  905): killProcessQuiet, pid=4012
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/TelephonyReceiver( 1242): bind: false
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
I/ActivityManager(  905): Killing 4012:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4012
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4265 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,W/GAV2    ( 4265): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  905): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  905): acquireWL(425e5518): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(425e5518): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(425c3930): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  905): notification sound not played, stream=5 volume=0 always=false
,D/Process (  905): killProcessQuiet, pid=3943
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/RemoteViews( 1113): com.htc.updater (true,33751552)
I/ActivityManager(  905): Killing 3943:com.android.vending/u0a73 (adj 15): empty #17
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41e689b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.updater 3 9 0 10
,I/RemoteViews( 1113): com.htc.updater (true,33751552)
D/PMS     (  905): releaseWL(425c3930): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41e60498 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.updater 0 9 0 10
I/ActivityManager(  905): Delay finish: com.google.android.gm/.GmailReceiver
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/ActivityManager(  905): Recipient 3943
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Gmail   ( 4265): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4265): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4265): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4265): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.gm/.GmailReceiver
,I/NotifUtils( 4265): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/NotifUtils( 4265): validateNotifications - cancelling account 61035162 / folder -317575340
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4306 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Babel   ( 4306): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4306): MmsConfig.loadMmsSettings
,E/dalvikvm( 4306): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4306): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 4306): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4306): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4306): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/MmsCustomizationProvider( 4180): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 4180): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4306): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4306): MmsConfig.loadFromDatabase
,E/Babel   ( 4306): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4306): MmsConfig.loadFromResources
,E/Babel   ( 4306): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4306): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4306, uid=10111, userID:0
,W/Settings( 4306): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4306, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4306, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4306, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4306, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4306, uid=10111, userID:0
D/PMS     (  905): acquireWL(426fec10): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4306 10111 null
I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4306): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  905): releaseWL(426fec10): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(427912e8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4306 10111 null
,I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/Messaging( 4180): mNeedToUpdateDate2 start
,D/MmsConfig( 4180): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4180): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4180): 
D/MmsAsyncWorkHandler( 4180): HM tk = 20001
D/ReportIndicatorCache( 4180): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4180): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41ab8598
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,I/Messaging( 4180): mccmnc> 
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DraftCache( 4180): [DraftCache/1] DraftCache.constructor
D/PMS     (  905): acquireWL(42713fc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(42713fc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DraftCache( 4180): [DraftCache/1] refresh
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MmsConfig( 4180): networkCode: 
,D/Messaging( 4180): ViewCache CreatePreloadOnlyConversationList
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,D/Messaging( 4180): mNeedToUpdateDate2: false
D/PMS     (  905): releaseWL(427912e8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PhoneStorageUtil( 4180): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4180): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4180): createReceiver
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(427a1e90): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4306 10111 null
,I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
D/MessageCustFlag( 4180): sense_version=6.0
D/Jerry   ( 4180): start to preload cursor >>>>>>>
D/TelephUtils( 1242): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
V/MmsProvider( 1242): Update uri=content://mms, match=0
V/MmsProvider( 1242): selection=st=129 AND m_type!=134
D/Messaging( 4180): Reset downloading state: 0
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/AccFlag ( 1242): sku_id=99
V/MmsSystemEventReceiver( 4180): TransactionService is going to be woken up.
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  905): Delaying start of: ServiceRecord{42842e20 u0 com.htc.sense.mms/.transaction.TransactionService}
D/DraftCache( 4180): [DraftCache/430] rebuildCache
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1242):  phoneType = -1
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1242):  phoneType = -1
D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 4180): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/Jerry   ( 1242): URI_DRAFT
D/Messaging( 4180): ViewCache CreatePreload
D/Messaging( 4180): ViewCache CreatePreloadOnlyMultipleOpsList
D/DraftCache( 4180): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4180): [DraftCache/430] rebuildCache time: 1
D/MmsAsyncWorkHandler( 4180): 
D/MmsAsyncWorkHandler( 4180): HM tk = 20002
D/Cust_MMSMS( 4180): _has_set_default_values_2=true
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1242): sku_id=99
D/MsgPreferenceUtils( 4180): def_index: 0
D/MsgPreferenceUtils( 4180): globalIndex = 1
D/MsgPreferenceUtils( 4180): phone state: true
D/MsgPreferenceUtils( 4180): sd state: false
D/MsgPreferenceUtils( 4180): vIndex = 0
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/AccFlag ( 1242): sku_id=99
,D/PMS     (  905): releaseWL(427a1e90): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4306/10111)
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41b3ef10 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4306): UserRecoverableAuthException.
,E/Babel   ( 4306): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4306): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4306): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4306): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4306): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4306): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4306): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4306): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4306): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4306): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4306): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4306): Error getting auth token
,E/Babel   ( 4306): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4306): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4306): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4306): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4306): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4306): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4306): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4306): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4306): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4306): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4306): Account registration failedRedacted-21
E/Babel   ( 4306): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4306): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4306): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4306): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4306): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4306): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4306): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4306): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4306): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4306): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4306): Account sign in complete with state 106account: Redacted-21
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4306/10111)
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Babel   ( 4306): Unexpected exception while authenticating.
,E/Babel   ( 4306): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4306): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4306): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4306): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4306): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4306): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4306): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4306): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4306): 	at java.lang.Thread.run(Thread.java:864)
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41bf80f8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 0 6 3 12
,E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1270): onLoadItems() -
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41b3ef10 -
,D/PhoneApp( 1242): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1242): -- N1 =0
,D/PhoneApp( 1242): -- N2 =0
,D/PhoneApp( 1242): -- N3 =0
,I/HtcModeClient( 1506): handler message = 4011
,E/HtcModeClient( 1506): Check connection and retry 7 times.
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,V/AlarmManager(  905): sending alarm PendingIntent{42747be0: PendingIntentRecord{4268fda0 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1452527827409, Int=0
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/TransactionService( 4180): 1-Creating TransactionService
,V/TransactionService( 4180): onStartCommand: 1
,D/MmsSystemEventReceiver( 4180): unRegisterForConnectionStateChanges
V/TransactionService( 4180): 4-Handling incoming message: { when=-2ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4180): Loading previous transactions.
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1242): device_type: 1
D/TransactionService( 4180): Force set service start id to 1
V/TransactionService( 4180): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4180): unRegisterForConnectionStateChanges
D/TransactionService( 4180): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4180): Destroying TransactionService
,V/TransactionService( 4180): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/Process (  905): killProcessQuiet, pid=4038
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Resuming delayed broadcast
D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
I/ActivityManager(  905): Killing 4038:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4038
,D/ConnectivityService(  905): Done.
,D/PackageBroadcastService( 2216): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
D/ConnectivityService(  905): Setting timer for 720seconds
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PeopleContactsSync( 2216): CP2 sync disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2216, uid=10028, userID:0
D/PMS     (  905): acquireWL(41b67d20): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
I/[PluginManager]RegisterService( 1402): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1402): handle notify Blinkfeed plugin client changed
D/PMS     (  905): releaseWL(41b67d20): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4375 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4375, uid=10073, userID:0
,D/Finsky  ( 4375): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4375/10073)
,D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4375/10073)
,D/Finsky  ( 4375): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4375): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4375): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4375, uid=10073, userID:0
,D/Finsky  ( 4375): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4375): [1] 2.run: Finished loading 1 libraries.,
,D/Process (  905): killProcessQuiet, pid=3651
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3651:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/IcingCorporaProvider( 2972): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Finsky  ( 4375): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  905): Delaying start of: ServiceRecord{424d11e0 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,I/IcingCorporaProvider( 2972): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
,D/Finsky  ( 4375): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  905): Resuming delayed broadcast
W/BroadcastQueue(  905): Exception when sending broadcast to ComponentInfo{com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor}
W/BroadcastQueue(  905): android.os.TransactionTooLargeException
W/BroadcastQueue(  905): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  905): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:966)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:246)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:974)
W/BroadcastQueue(  905): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:15076)
W/BroadcastQueue(  905): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:401)
W/BroadcastQueue(  905): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
W/BroadcastQueue(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/BroadcastQueue(  905): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  905): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4413 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  905): sending alarm PendingIntent{423a7088: PendingIntentRecord{423267a8 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1452527829226, Int=0
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(42328888): PARTIAL_WAKE_LOCK  AsyncService 0x1 4413 10160 null
,D/PMS     (  905): releaseWL(42328888): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  905): acquireWL(421bde98): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4413 10160 null
,I/ActivityManager(  905): Delay finish: com.google.android.gsf/.settings.GoogleLocationSettings$LocationSettingsChangedListener
,D/PMS     (  905): acquireWL(4255a938): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4413 10160 null
,D/PMS     (  905): releaseWL(421bde98): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4413/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4413/10160)
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(4255a938): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3980
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3980:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  905): Recipient 3980
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42769c00): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3711 10070 null
,D/PMS     (  905): acquireWL(422fe4f8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3711 10070 null
,D/PMS     (  905): releaseWL(42769c00): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 3711): java.lang.NullPointerException
W/System.err( 3711): java.lang.NullPointerException
W/System.err( 3711): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3711): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3711): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3711): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3711): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3711): stopSelfResult true
I/ActivityManager(  905): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  905): releaseWL(422fe4f8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(427e3de0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3711 10070 null
D/PMS     (  905): acquireWL(425cdca8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3711 10070 null
I/ActivityManager(  905): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
,D/PMS     (  905): releaseWL(427e3de0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 3711): java.lang.NullPointerException
W/System.err( 3711): java.lang.NullPointerException
W/System.err( 3711): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3711): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3711): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3711): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3711): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3711): stopSelfResult true
D/PMS     (  905): releaseWL(425cdca8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(4266b258): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3711 10070 null
E/TodoTaskNotifyService( 3711): java.lang.NullPointerException
W/System.err( 3711): java.lang.NullPointerException
,W/System.err( 3711): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3711): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3711): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3711): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3711): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  905): acquireWL(4240c398): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3711 10070 null
D/PMS     (  905): releaseWL(4266b258): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  905): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  905): releaseWL(4240c398): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3711): stopSelfResult true
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  905): Resuming delayed broadcast
,I/GCM     ( 1367): GCM config loaded
,D/PMS     (  905): acquireWL(42619850): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(425723b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/ActivityManager(  905): Delay finish: com.htc.task/.TodoReceiver
,D/PMS     (  905): releaseWL(42619850): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(425723b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T],
I/GAV2    ( 4265): Thread[GAThread,5,main]: No campaign data found.
,D/TodoTaskshortcut( 3711): update TASK shortcut>
,V/AlarmManager(  905): sending alarm PendingIntent{41ef2650: PendingIntentRecord{425208f8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452527830010, Int=0
,I/GAV4    ( 4306): Thread[GAThread,5,main]: No campaign data found.
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4375): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4375): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  905): Resuming delayed broadcast
I/SensorManager(  905): mEventCount = 601
I/WSP     ( 1402): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
D/WeatherUtility( 1402): Weather sync is On
,I/WSP     ( 1402): [Receiver] next auto-sync alarm event is 60 mins later, at time: Mon Jan 11 17:57:10 CET 2016
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2216): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
,I/PeopleContactsSync( 2216): CP2 sync disabled
D/PMS     (  905): acquireWL(4258e3f0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1402 10053 null
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2216, uid=10028, userID:0
,D/PMS     (  905): acquireWL(42579980): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  905): releaseWL(42579980): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/Finsky  ( 4375): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4375): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4375): [1] DailyHygiene.reschedule: Scheduling new run in 271 minutes (failures=4)
,D/Process (  905): killProcessQuiet, pid=4071
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4071:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4071
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1506): handler message = 4011
,E/HtcModeClient( 1506): Check connection and retry 8 times.
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/PMS     (  905): acquireWL(42443310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(42443310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/CalendarProvider2( 1506): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1506): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  905): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1402): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.videos
,I/[PluginManager]RegisterService( 1402): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/IcingCorporaProvider( 2972): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2972): UpdateCorporaTask done [took 87 ms] updated apps [took 87 ms] 
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(42655f80): PARTIAL_WAKE_LOCK  AsyncService 0x1 4413 10160 null
,D/PMS     (  905): releaseWL(42655f80): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4470 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 4470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3897): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3897): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3897): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3897): Cust_ConnectToPC   : spcsc>false
D/        ( 3897): Cust_ConnectToPC   : IPT>true
D/        ( 3897): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3897): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3897): Index of the first 1 = -1
W/ContextImpl( 3897): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3897): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3897): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3897): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3897): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3897): [ACC]android_networking:tethering_guard_support=false
,D/Process (  905): killProcessQuiet, pid=3696
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4483 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
I/ActivityManager(  905): Killing 3696:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3696
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SyncApplication( 4483): Loading default preferences
,W/Resources( 4483): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  905): New client listening to asynchronous messages
,D/SyncApplication( 4483): Overriding preferences with custom values
,D/SyncApplication( 4483): Updating preferences succeeded
,E/SyncApplication( 4483): Application created.
D/VolumeInfo( 4483): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4483): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4483): Found 0 mount point(s)
,V/VolumeInfo( 4483): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4483): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4483): getNewCalendarAuthority()...
D/VolumeInfo( 4483): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 4483): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4483): enableAppOperation()+
,D/SyncApplication( 4483): enableAppOperation()-
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4483, uid=10008, userID:0
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4483, uid=10008, userID:0
,W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 4483): isNeorSinged() + 
,D/HTCUtilities( 4483): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4483): isNeorSinged() return false
,D/CDMountReceiver( 4483): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4483): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/CDMountReceiver( 4483): enable CD Auto-mount: true
,D/HTCUtilities( 4483): enable auto-mount
,D/HTCUtilities( 4483): enable auto-mount
,I/RemoteViews( 1113): com.nero.android.htc.sync (false,0)
I/ActivityManager(  905): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  905): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  905): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): releaseWL(42629cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41e746f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.nero.android.htc.sync 1 12 3 11
,I/RemoteViews( 1113): com.nero.android.htc.sync (false,0)
D/PMS     (  905): acquireWL(42505000): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4139 10154 null
I/ActivityManager(  905): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41eab078 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,W/ContextImpl( 4139): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/RemoteViews.Performance( 1113): com.nero.android.htc.sync 0 10 3 16
,W/ContextImpl( 4139): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4139, uid=10154, userID:0
,I/MusicLeanback( 4139): Conditions not met for autocaching.
,I/MusicLeanback( 4139): Stop autocaching.
D/PMS     (  905): releaseWL(42505000): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 4106): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  905): killProcessQuiet, pid=4092
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Killing 4092:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4512 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 4512): onCreate
D/ProviderChangeReceiver( 4512): ---------------------------------------------------
,D/ProviderChangeReceiver( 4512): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4512): start to updateAlertNotification!
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
D/WIFI_ICON( 1113): WifiActivity: 1
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  905): Recipient 4092
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4527 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=4151
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4151:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4151
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AlertService( 4512): No fired or scheduled alerts
D/HtcAlertUtils( 4512): -- cancelReminderNotification --
D/HtcAlertUtils( 4512): broadcastExistReminder!
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4527): [4527/4527] onCreate()
W/ContextImpl( 4527): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=4192
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  905): Killing 4192:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4192
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1506): handler message = 4011
,E/HtcModeClient( 1506): Check connection and retry 9 times.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  905): acquireWL(427a7c60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=37 rxSum=29} preTxRxSum={txSum=37 rxSum=29}
D/WifiDataStallTracker(  905): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=19603 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19604 delay=15s
V/AlarmManager(  905): sending alarm PendingIntent{4283fc80: PendingIntentRecord{4243e620 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=74263, Int=0
D/PMS     (  905): releaseWL(427a7c60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/SensorManager(  905): mEventCount = 750
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{4257e3e8 u0 com.htc.musicenhancer/.EnhancerService}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:66, mTXpacketCount:66, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/PMS     (  905): releaseWL(4258e3f0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/HtcModeClient( 1506): handler message = 4011
,E/HtcModeClient( 1506): Check connection and retry 10 times.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  905): mEventCount = 900
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>,
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
D/PMS     (  905): acquireWL(42714d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10073}
V/AlarmManager(  905): sending alarm PendingIntent{425d5838: PendingIntentRecord{424a3e40 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452527845155, Int=0
D/PMS     (  905): releaseWL(42714d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/Finsky  ( 4375): [1] 5.onFinished: Installation state replication succeeded.
,I/HtcModeClient( 1506): handler message = 4011
,E/HtcModeClient( 1506): Check connection and retry 11 times.
,D/AutoSetting( 1402): service - mHandler: update timezone
,D/AutoSetting( 1402): service - handleMessage() stop self
,D/AutoSetting( 1402): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=3663
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 3663:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
D/AutoSetting( 1402): service - handleMessage() quit looper
,D/AutoSetting( 1506): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1506): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1506): service - onCreate(),
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1506): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1506): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1506): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1506): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1506): service - mHandler: update timezone
,D/AutoSetting( 1506): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1506): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1506): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1506): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
I/ActivityManager(  905): Recipient 3663
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41f3fc48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 3 8 3 11
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1113): WifiActivity: 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1506): handler message = 4011
,E/HtcModeClient( 1506): Check connection and retry 12 times.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/SensorManager(  905): mEventCount = 1050
D/WIFI_ICON( 1113): WifiActivity: 1
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  905): acquireWL(42685430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=38 rxSum=30} preTxRxSum={txSum=37 rxSum=29}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=19604 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19605 delay=15s
V/AlarmManager(  905): sending alarm PendingIntent{4256f4f0: PendingIntentRecord{4243e620 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=89273, Int=0
D/PMS     (  905): releaseWL(42685430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:67, mTXpacketCount:66, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/HtcModeClient( 1506): handler message = 4011
,E/HtcModeClient( 1506): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1506): Don't start project servcice
,D/HtcModeClient( 1506): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1506): connectState: CONNECTION_READY = false
,D/SilentMusic( 1506): call stop
,D/HtcModeClient( 1506): close connection
,W/HtcModeClient( 1506): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1506): read the terminate packet, so break
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/SensorManager(  905): mEventCount = 1200
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WIFI_ICON( 1113): WifiActivity: 0
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42807b40 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1113): WifiActivity: 0
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/SensorManager(  905): mEventCount = 1350
,D/PMS     (  905): acquireWL(42566c38): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(42566c38): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(4268f810): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(4268f810): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(427e0050): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(427e0050): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(42637bc0): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
,D/PMS     (  905): releaseWL(42637bc0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/PMS     (  905): acquireWL(4282fbe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
V/AlarmManager(  905): sending alarm PendingIntent{425ec4d8: PendingIntentRecord{4243e620 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104284, Int=0
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=39 rxSum=31} preTxRxSum={txSum=38 rxSum=30}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=19605 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19606 delay=15s
D/PMS     (  905): releaseWL(4282fbe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4552 uid=10077 gids={50077}
D/PMS     (  905): acquireWL(425fc860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
,V/AlarmManager(  905): sending alarm PendingIntent{424c9948: PendingIntentRecord{424a4cf0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452527866971, Int=60000
,D/PMS     (  905): releaseWL(425fc860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4552): SMSBackupAgentService started
,D/SMSBackup( 4552): Checking restore status
D/SMSBackup( 4552): Restore complete
,D/SMSBackup( 4552): cancelCheckAlarm
,D/SMSBackup( 4552): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  905): killProcessQuiet, pid=4227
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4227:com.htc.sdm/u0a80 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4227
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:70, mTXpacketCount:67, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  905): mEventCount = 1500
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421470e8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421470e8, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42077c00
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@41d30538
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,W/PMS     (  905): mWirelessDisplayManager is null
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 377ms
D/PMS     (  905): nativeSetInteractive:false
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@426449d8)
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
D/PMS     (  905): OOBE c monitor 11
D/PMN     (  905): wakingUp
,I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
,I/IntentController( 1113): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1253): ScreenObserver: OFF
,D/NfcService( 1253): applyRouting - 0
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
I/InputMethodManagerService(  905): Disable input method client, pid=2441
D/PMS     (  905): acquireWL(42645a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
I/WindowManager(  905): No lock screen! windowToken=null
W/ResourceType( 2441): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 2441): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41abcc28 VFEDH.C. .F...... 0,0-720,1134 #64}
,D/NfcService( 1253): applyRouting -2
D/PMS     (  905): acquireWL(42646228): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMN     (  905): onScreenOn
,D/PMS     (  905): releaseWL(42646228): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(42645a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19607 delay=15s
D/PowerUI ( 1113): closing low battery warning: level=100
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/MtpService( 2526): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2526): [MTP][onReceive]-
,D/NfcService( 1253): applyRouting - 0
,D/NfcService( 1253): applyRouting -2
D/PMS     (  905): acquireWL(4265d648): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
,I/ClockThread( 1113): stop update clock
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): SET_SCREEN_ON:On
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1173): BG scan when screen On
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): Match BG scan, scan!
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
D/PMS     (  905): releaseWL(4265d648): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/ContextImpl( 4470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  905): updateScreenOn: false
,D/SmartSyncUtils( 4470): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(42852b60): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4470 1000 null
,D/SmartSyncUtils( 4470): getMobilePolicyEnabled, result = true
,D/AutoSetting( 1402): receiver - intent: android.intent.action.USER_PRESENT
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): releaseWL(42852b60): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AutoSetting( 1402): service - onCreate()
D/TetherSettings( 3897): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3897): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3897): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3897): Cust_ConnectToPC   : spcsc>false
D/        ( 3897): Cust_ConnectToPC   : IPT>true
D/        ( 3897): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3897): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3897): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3897): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3897): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PSReceiver( 3897): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1402): service - AddressCache: using context: com.htc.Weather
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
I/SmartNS_PSService( 3897): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3897): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/SmartNS_PSService( 3897):  defaultType:0
,D/LocationManagerService(  905): request 425a4498 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,W/ContextImpl( 3897): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1799): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1799): onScreenOn: 1452527874849
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1799): onScreenOn: 1452527874849
D/PMS     (  905): acquireWL(427fe6c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1438 10028 null
D/PMS     (  905): releaseWL(427fe6c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42077c00
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42077c00, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@41d30538
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(42708e20): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42708e20): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19607 mDataStallAlarmIntent=PendingIntent{41c50688: PendingIntentRecord{4243e620 android broadcastIntent}}
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/PMS     (  905): acquireWL(4284e408): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
,W/ContextImpl( 4470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4470): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4470): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4470): getMobilePolicyEnabled, result = true
D/WifiService(  905): New client listening to asynchronous messages
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): SET_SCREEN_ON:Off
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1173): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1173): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41d30538
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41d30538, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41d30538, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41d30538
,V/SRS_Proc(  370): ParamSet string: screen_state=off
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4213ba48 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4213ba48 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  905): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  905): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  905): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  905): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  905): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  905): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  905): 	at dalvik.system.NativeStart.main(Native Method)
D/NetworkPolicy(  905): updateScreenOn: false
,D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4284e408): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/ContactMessageStore( 1242): start background delete task...
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1799): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1799): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1799): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1799): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1799): onScreenOff
D/PMS     (  905): acquireWL(42822670): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1438 10028 null
D/PMS     (  905): releaseWL(42822670): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1402): service - mHandler: cancel location update
,D/AutoSetting( 1402): service -           changes count: 0
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1506): service - handleMessage() stop self
,D/AutoSetting( 1506): service - onDestroy() END
,D/AutoSetting( 1506): service - handleMessage() quit looper
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-91
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1173): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1173): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1173): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1173): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1173): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wp,a_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-91
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1173): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1173): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1173): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1173): Add randomness: count=16 entropy=10
D/wpa_supplicant( 1173): Add randomness: count=17 entropy=11
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: DISCONNECTED -> INACT,IVE
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1173): reply (811) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000115162276
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000115162298
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000115162308
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000115162318
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000115162328
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-91
I/wpa_supplicant( 1173): tsf=0000000115162338
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1173): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/HTCRequest(  905): WifiMonitor,:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiP2pService(  905): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@427c43b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@427c43b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@427c43b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 115162276, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 115162298, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 115162308, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 115162318, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 115162328, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -91, frequency: 2437, timestamp: 115162338, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10,
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  69, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(426fb2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4233c838: PendingIntentRecord{4233c088 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=117377, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(426fb2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  905): killProcessQuiet, pid=4208
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4208:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4208
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{427fc010 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  905): acquireWL(426e8220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(426e8220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
D/wpa_supplicant( 1173): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=18 entropy=12
D/wpa_supplicant( 1173): Add randomness: count=19 entropy=13
D/wpa_supplicant( 1173): Add randomness: count=20 entropy=14
D/wpa_supplicant( 1173): Add randomness: count=21 entropy=15
D/wpa_supplicant( 1173): Add randomness: count=22 entropy=16
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
,I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1173): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
,I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
D/wpa_supplicant( 1173): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=23 entropy=17
D/wpa_supplicant( 1173): Add randomness: count=24 entropy=18
,D/wpa_supplicant( 1173): Add randomness: count=25 entropy=19
D/wpa_supplicant( 1173): Add randomness: count=26 entropy=20
D/wpa_supplicant( 1173): Add randomness: count=27 entropy=21
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1173): reply (811) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000115162276
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000133533677
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77,
I/wpa_supplicant( 1173): tsf=0000000133533691
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000133533701
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-86
I/wpa_supplicant( 1173): tsf=0000000133533713
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-91
I/wpa_supplicant( 1173): tsf=0000000115162338
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1173): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1173): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 115162276, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 133533677, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 133533691, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 133533701, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 133533713, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -91, frequency: 2437, timestamp: 115162338, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(42677a30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42483d80: PendingIntentRecord{424885e8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141151, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{42405d48: PendingIntentRecord{4257d658 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142409, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(42679b18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1367/10028)
,D/PMS     (  905): releaseWL(42677a30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  905): acquireWL(427428a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/AutoSetting( 1402): service - handleMessage() stop self
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =150b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  905): releaseWL(427428a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1402): service - handleMessage() quit looper
,D/AutoSetting( 1402): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=4252
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4252:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4252
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4,
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): releaseWL(42679b18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-84
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=28 entropy=22
D/wpa_supplicant( 1173): Add randomness: count=29 entropy=23
D/wpa_supplicant( 1173): Add randomness: count=30 entropy=24
D/wpa_supplicant( 1173): Add randomness: count=31 entropy=25
D/wpa_supplicant( 1173): Add randomness: count=32 entropy=26
D/wpa_supplicant( 1173): Add randomness: count=33 entropy=27
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie,_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-84
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=34 entropy=28
D/wpa_supplicant( 1173): Add randomness: count=35 entropy=29
D/wpa_supplicant( 1173): Add randomness: count=36 entropy=30
D/wpa_supplicant( 1173): Add randomness: count=37 entropy=31
D/wpa_supplicant( 1173): Add randomness: count=38 entropy=32
D/wpa_supplicant( 1173): Add randomness: count=39 entropy=33
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1173): reply (813) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000151924525
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000151924552
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
,I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000151924563
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000151924572
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000151924594
,I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000151924582
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ####
D/WifiP2pService(  905): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 151924525, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 151924552, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 151924563, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 151924572, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 151924594, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 151924582, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42624800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42624800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2216/10028)
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=40 entropy=34
D/wpa_supplicant( 1173): Add randomness: count=41 entropy=35
D/wpa_supplicant( 1173): Add randomness: count=42 entropy=36
D/wpa_supplicant( 1173): Add randomness: count=43 entropy=37
D/wpa_supplicant( 1173): Add randomness: count=44 entropy=38
D/wpa_supplicant( 1173): Add randomness: count=45 entropy=39
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1173): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 r,sn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=46 entropy=40
D/wpa_supplicant( 1173): Add randomness: count=47 entropy=41
D/wpa_supplicant( 1173): Add randomness: count=48 entropy=42
D/wpa_supplicant( 1173): Add randomness: count=49 entropy=43
D/wpa_supplicant( 1173): Add randomness: count=50 entropy=44
D/wpa_supplicant( 1173): Add randomness: count=51 entropy=45
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1,173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1173): reply (813) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000170112209
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000170112235
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000170112247
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000170112257
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000170112268
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-87
I/wpa_supplicant( 1173): tsf=0000000151924582
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ####
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 170112209, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 170112235, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 170112247, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 170112257, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 170112268, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 151924582, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList,
,V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(422df360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{426f7668: PendingIntentRecord{42420020 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=175240, Int=0
,D/PMS     (  905): releaseWL(422df360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(42049d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4233c838: PendingIntentRecord{4233c088 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=177378, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42049d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
,D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=52 entropy=46
D/wpa_supplicant( 1173): Add randomness: count=53 entropy=47
D/wpa_supplicant( 1173): Add randomness: count=54 entropy=48
D/wpa_supplicant( 1173): Add randomness: count=55 entropy=49
D/wpa_supplicant( 1173): Add randomness: count=56 entropy=50
D/wpa_supplicant( 1173): Add randomness: count=57 entropy=51
D/wpa_supplicant( 1173): Add randomness: count=58 entropy=52
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1173): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:1,2:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=59 entropy=53
D/wpa_supplicant( 1173): Add randomness: count=60 entropy=54
D/wpa_supplicant( 1173): Add randomness: count=61 entropy=55
D/wpa_supplicant( 1173): Add randomness: count=62 entropy=56
D/wpa_supplicant( 1173): Add randomness: count=63 entropy=57
D/wpa_supplicant( 1173): Add randomness: count=64 entropy=58
D/wpa_supplicant( 1173): Add randomness: count=65 entropy=59
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1173): reply (926) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000188425164
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====,
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000188425202
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000188425213
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
,I/wpa_supplicant( 1173): tsf=0000000188425222
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000188425232
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-87
I/wpa_supplicant( 1173): tsf=0000000151924582
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-58
I/wpa_supplicant( 1173): tsf=0000000188425190
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1173): ssid=01ABC
I/wpa_supplicant( 1173): ####
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 188425164, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 188425202, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 188425213, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 188425222, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 188425232, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 151924582, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 188425190, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 7 to mScanResults
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(425af440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(425af440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-76
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=66 entropy=60
D/wpa_supplicant( 1173): Add randomness: count=67 entropy=61
D/wpa_supplicant( 1173): Add randomness: count=68 entropy=62
D/wpa_supplicant( 1173): Add randomness: count=69 entropy=63
D/wpa_supplicant( 1173): Add randomness: count=70 entropy=64
D/wpa_supplicant( 1173): Add randomness: count=71 entropy=65
D/wpa_supplicant( 1173): Add randomness: count=72 entropy=66
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1173): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:1,2:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-76
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=73 entropy=67
D/wpa_supplicant( 1173): Add randomness: count=74 entropy=68
D/wpa_supplicant( 1173): Add randomness: count=75 entropy=69
D/wpa_supplicant( 1173): Add randomness: count=76 entropy=70
D/wpa_supplicant( 1173): Add randomness: count=77 entropy=71
D/wpa_supplicant( 1173): Add randomness: count=78 entropy=72
D/wpa_supplicant( 1173): Add randomness: count=79 entropy=73
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1173): reply (926) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000206704508
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000206704547
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-76
I/wpa_supplicant( 1173): tsf=0000000206704557
,I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000206704660
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
,I/wpa_supplicant( 1173): tsf=0000000206704567
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-87
I/wpa_supplicant( 1173): tsf=0000000151924582
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-58
I/wpa_supplicant( 1173): tsf=0000000206704536
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1173): ssid=01ABC
I/wpa_supplicant( 1173): ####
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 206704508, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 206704547, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2452, timestamp: 206704557, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 206704660, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 206704567, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 151924582, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 206704536, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 7 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4265bcd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(4265bcd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-76
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-90
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=80 entropy=74
D/wpa_supplicant( 1173): Add randomness: count=81 entropy=75
D/wpa_supplicant( 1173): Add randomness: count=82 entropy=76
D/wpa_supplicant( 1173): Add randomness: count=83 entropy=77
D/wpa_supplicant( 1173): Add randomness: count=84 entropy=78
D/wpa_supplicant( 1173): Add randomness: count=85 entropy=79
D/wpa_supplicant( 1173): Add randomness: count=86 entropy=80
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1173): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie,_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-76
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-90
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=87 entropy=81
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1173): Add randomness: count=88 entropy=82
D/wpa_supplicant( 1173): Add randomness: count=89 entropy=83
D/wpa_supplicant( 1173): Add randomness: count=90 entropy=84
D/wpa_supplicant( 1173): Add randomness: count=91 entropy=85
D/wpa_supplicant( 1173): Add randomness: count=92 entropy=86
D/wpa_supplicant( 1173): Add randomness: count=93 entropy=87
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplic,ant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1173): reply (1071) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000225033961
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000225033998
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-76
I/wpa_supplicant( 1173): tsf=0000000225034008
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000225034018
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000225034028
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1,173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-87
I/wpa_supplicant( 1173): tsf=0000000151924582
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-58
I/wpa_supplicant( 1173): tsf=0000000225033987
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1173): ssid=01ABC
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=8
I/wpa_supplicant( 1173): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-90
I/wpa_supplicant( 1173): tsf=0000000225034037
I/wpa_supplicant( 1173): f
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 225033961, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 225033998, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2452, timestamp: 225034008, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 225034018, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 225034028, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 151924582, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  905): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 225033987, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -90, frequency: 2437, timestamp: 225034037, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 8 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList,
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  67, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (8) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  905): acquireWL(4265c890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4233c838: PendingIntentRecord{4233c088 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=237377, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4265c890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-76
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-82
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-89
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=94 entropy=88
D/wpa_supplicant( 1173): Add randomness: count=95 entropy=89
D/wpa_supplicant( 1173): Add randomness: count=96 entropy=90
D/wpa_supplicant( 1173): Add randomness: count=97 entropy=91
D/wpa_supplicant( 1173): Add randomness: count=98 entropy=92
D/wpa_supplicant( 1173): Add randomness: count=99 entropy=93
D/wpa_supplicant( 1173): Add randomness: count=100 entropy=94
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 11,73): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-76
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-82
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-89
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=101 entropy=95
D/wpa_supplicant( 1173): Add randomness: count=102 entropy=96
D/wpa_supplicant( 1173): Add randomness: count=103 entropy=97
D/wpa_supplicant( 1173): Add randomness: count=104 entropy=98
D/wpa_supplicant( 1173): Add randomness: count=105 entropy=99
D/wpa_supplicant( 1173): Add randomness: count=106 entropy=100
D/wpa_supplicant( 1173): Add randomness: count=107 entropy=101
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1173): reply (1071) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000243344192
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000243344220
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-76
I/wpa_supplicant( 1173): tsf=0000000243344231,
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000225034018
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000243344241
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-82
I/wpa_supplicant( 1173): tsf=0000000243344261
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-58
I/wpa_supplicant( 1173): tsf=0000000225033987
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1173): ssid=01ABC
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=8
I/wpa_supplicant( 1173): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-89
I/wpa_supplicant( 1173): tsf=0000000243344273
I/wpa_supplicant( 1173): f
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 243344192, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 243344220, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2452, timestamp: 243344231, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 225034018, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 243344241, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -82, frequency: 2437, timestamp: 243344261, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 225033987, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 7: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2437, timestamp: 243344273, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 8 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  6 [-82], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-89], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (8) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4265a0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4265a0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=108 entropy=102
D/wpa_supplicant( 1173): Add randomness: count=109 entropy=103
D/wpa_supplicant( 1173): Add randomness: count=110 entropy=104
D/wpa_supplicant( 1173): Add randomness: count=111 entropy=105
D/wpa_supplicant( 1173): Add randomness: count=112 entropy=106
D/wpa_supplicant( 1173): Add randomness: count=113 entropy=107
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:,34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=114 entropy=108
D/wpa_supplicant( 1173): Add randomness: count=115 entropy=109
D/wpa_supplicant( 1173): Add randomness: count=116 entropy=110
D/wpa_supplicant( 1173): Add randomness: count=117 entropy=111
D/wpa_supplicant( 1173): Add randomness: count=118 entropy=112
D/wpa_supplicant( 1173): Add randomness: count=119 entropy=113
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
,I/wpa_supplicant( 1173): reply (958) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000261654859
,I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000261654885
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000261654896
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000261654906
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
,I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000261654927
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000261654916
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=8
I/wpa_supplicant( 1173): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-89
I/wpa_supplicant( 1173): tsf=0000000243344273
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1173): ####
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 261654859, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 261654885, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 261654896, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 261654906, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 261654927, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 261654916, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2437, timestamp: 243344273, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 7 to mScanResults
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  6 [-84], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-89], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter,
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=120 entropy=114
D/wpa_supplicant( 1173): Add randomness: count=121 entropy=115
D/wpa_supplicant( 1173): Add randomness: count=122 entropy=116
D/wpa_supplicant( 1173): Add randomness: count=123 entropy=117
D/wpa_supplicant( 1173): Add randomness: count=124 entropy=118
D/wpa_supplicant( 1173): Add randomness: count=125 entropy=119
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:,34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=126 entropy=120
D/wpa_supplicant( 1173): Add randomness: count=127 entropy=121
D/wpa_supplicant( 1173): Add randomness: count=128 entropy=122
D/wpa_supplicant( 1173): Add randomness: count=129 entropy=123
D/wpa_supplicant( 1173): Add randomness: count=130 entropy=124
D/wpa_supplicant( 1173): Add randomness: count=131 entropy=125
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wla,n0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1173): reply (813) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000261654859
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000279974137
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000279974148
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000279974157
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000279974177
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000279974167
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 261654859, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 279974137, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 279974148, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 279974157, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 279974177, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 279974167, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults,
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  905): acquireWL(42650a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4233c838: PendingIntentRecord{4233c088 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=297377, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42650a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=132 entropy=126
D/wpa_supplicant( 1173): Add randomness: count=133 entropy=127
D/wpa_supplicant( 1173): Add randomness: count=134 entropy=128
D/wpa_supplicant( 1173): Add randomness: count=135 entropy=129
D/wpa_supplicant( 1173): Add randomness: count=136 entropy=130
D/wpa_supplicant( 1173): Add randomness: count=137 entropy=131
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:,34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=138 entropy=132
D/wpa_supplicant( 1173): Add randomness: count=139 entropy=133
D/wpa_supplicant( 1173): Add randomness: count=140 entropy=134
D/wpa_supplicant( 1173): Add randomness: count=141 entropy=135
D/wpa_supplicant( 1173): Add randomness: count=142 entropy=136
D/wpa_supplicant( 1173): Add randomness: count=143 entropy=137
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1173): reply (813) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000298274132
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000298274158
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000298274170
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000298274179
,I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-86
I/wpa_supplicant( 1173): tsf=0000000298274199
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000298274189
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ####
,D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 298274132, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 298274158, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 298274170, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 298274179, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 298274199, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 298274189, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  75, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(427bee90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427bee90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=144 entropy=138
D/wpa_supplicant( 1173): Add randomness: count=145 entropy=139
D/wpa_supplicant( 1173): Add randomness: count=146 entropy=140
D/wpa_supplicant( 1173): Add randomness: count=147 entropy=141
D/wpa_supplicant( 1173): Add randomness: count=148 entropy=142
D/wpa_supplicant( 1173): Add randomness: count=149 entropy=143
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:,34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=150 entropy=144
D/wpa_supplicant( 1173): Add randomness: count=151 entropy=145
D/wpa_supplicant( 1173): Add randomness: count=152 entropy=146
D/wpa_supplicant( 1173): Add randomness: count=153 entropy=147
D/wpa_supplicant( 1173): Add randomness: count=154 entropy=148
D/wpa_supplicant( 1173): Add randomness: count=155 entropy=149
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1173): reply (813) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000316604231
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000316604257
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
,I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000316604268
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000316604278
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000316604287
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-87
I/wpa_supplicant( 1173): tsf=0000000316604297,
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiP2pService(  905): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 316604231, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 316604257, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 316604268, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 316604278, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 316604287, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  905): Only print Top 10 in ApScanList,
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 316604297, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-89
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=156 entropy=150
D/wpa_supplicant( 1173): Add randomness: count=157 entropy=151
D/wpa_supplicant( 1173): Add randomness: count=158 entropy=152
D/wpa_supplicant( 1173): Add randomness: count=159 entropy=153
D/wpa_supplicant( 1173): Add randomness: count=160 entropy=154
D/wpa_supplicant( 1173): Add randomness: count=161 entropy=155
D/wpa_supplicant( 1173): Add randomness: count=162 entropy=156
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_s,upplicant( 1173): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-89
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=163 entropy=157
D/wpa_supplicant( 1173): Add randomness: count=164 entropy=158
D/wpa_supplicant( 1173): Add randomness: count=165 entropy=159
D/wpa_supplicant( 1173): Add randomness: count=166 entropy=160
D/wpa_supplicant( 1173): Add randomness: count=167 entropy=161
D/wpa_supplicant( 1173): Add randomness: count=168 entropy=162
D/wpa_supplicant( 1173): Add randomness: count=169 entropy=163
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blackli,st=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  905): getDiscoveryDongleList
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1173): reply (958) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000334944735
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
,I/wpa_supplicant( 1173): tsf=0000000334944763
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000316604268
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000334944783
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000334944793
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-87
I/wpa_supplicant( 1173): tsf=0000000334944802
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=9
I/wpa_supplicant( 1173): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-89
I/wpa_supplicant( 1173): tsf=0000000334944814
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1173): ####
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 334944735, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 334944763, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 316604268, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 334944783, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 334944793, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 334944802, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 s,eries, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2437, timestamp: 334944814, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 7 to mScanResults
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-89], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=170 entropy=164
D/wpa_supplicant( 1173): Add randomness: count=171 entropy=165
D/wpa_supplicant( 1173): Add randomness: count=172 entropy=166
D/wpa_supplicant( 1173): Add randomness: count=173 entropy=167
D/wpa_supplicant( 1173): Add randomness: count=174 entropy=168
D/wpa_supplicant( 1173): Add randomness: count=175 entropy=169
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:,34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=176 entropy=170
D/wpa_supplicant( 1173): Add randomness: count=177 entropy=171
D/wpa_supplicant( 1173): Add randomness: count=178 entropy=172
D/wpa_supplicant( 1173): Add randomness: count=179 entropy=173
D/wpa_supplicant( 1173): Add randomness: count=180 entropy=174
D/wpa_supplicant( 1173): Add randomness: count=181 entropy=175
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
,I/wpa_supplicant( 1173): reply (958) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000353274044
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000353274071
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
,I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000353274081
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000353274091
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====,
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000353274101
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-87
I/wpa_supplicant( 1173): tsf=0000000353274110
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=9
I/wpa_supplicant( 1173): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-89
I/wpa_supplicant( 1173): tsf=0000000334944814
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1173): ####
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 353274044, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 353274071, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 353274081, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 353274091, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 353274101, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 353274110, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2437, timestamp: 334944814, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 7 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0,
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-89], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (7) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4269c850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4233c838: PendingIntentRecord{4233c088 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=357378, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4269c850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,W/GLSActivity( 1367): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1367): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1367): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1367): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1367): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1367): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1367): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1367): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4375): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4375): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4375): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4375): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4375): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4375): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4375): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4375): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41ab99b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 5 15 5 12
,D/libc    ( 4375): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4375): [NET] getaddrinfo-,err=8
D/libc    ( 4375): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4375): [NET] getaddrinfo-, 1
,D/libc    ( 4375): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =591e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4375): [NET] getaddrinfo_proxy-, success
I/global  ( 4375): call createSocket() return a new socket.
D/libc    ( 4375): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4375): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4375): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4375): [NET] getaddrinfo-,err=8
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-89
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=182 entropy=176
D/wpa_supplicant( 1173): Add randomness: count=183 entropy=177
D/wpa_supplicant( 1173): Add randomness: count=184 entropy=178
D/wpa_supplicant( 1173): Add randomness: count=185 entropy=179
D/wpa_supplicant( 1173): Add randomness: count=186 entropy=180
D/wpa_supplicant( 1173): Add randomness: count=187 entropy=181
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rs,n_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-89
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=188 entropy=182
D/wpa_supplicant( 1173): Add randomness: count=189 entropy=183
D/wpa_supplicant( 1173): Add randomness: count=190 entropy=184
D/wpa_supplicant( 1173): Add randomness: count=191 entropy=185
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1173): Add randomness: count=192 entropy=186
D/wpa_supplicant( 1173): Add randomness: count=193 entropy=187
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 ,what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1173): reply (958) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000371614163
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000371614189
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000371614200
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000371614210
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====,
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000371614220
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-87
I/wpa_supplicant( 1173): tsf=0000000353274110
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=9
I/wpa_supplicant( 1173): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-89
I/wpa_supplicant( 1173): tsf=0000000371614229
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1173): ####
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 371614163, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 371614189, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 371614200, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 371614210, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 371614220, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 353274110, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2437, timestamp: 371614229, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 7 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-89], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(429071c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(429071c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1173): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=194 entropy=188
D/wpa_supplicant( 1173): Add randomness: count=195 entropy=189
D/wpa_supplicant( 1173): Add randomness: count=196 entropy=190
D/wpa_supplicant( 1173): Add randomness: count=197 entropy=191
D/wpa_supplicant( 1173): Add randomness: count=198 entropy=192
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating sc,an results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1173): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=199 entropy=193
D/wpa_supplicant( 1173): Add randomness: count=200 entropy=194
D/wpa_supplicant( 1173): Add randomness: count=201 entropy=195
D/wpa_supplicant( 1173): Add randomness: count=202 entropy=196
D/wpa_supplicant( 1173): Add randomness: count=203 entropy=197
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
,W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
,I/wpa_supplicant( 1173): reply (811) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000389771836
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
,I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000389771862
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000389771874
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
,I/wpa_supplicant( 1173): tsf=0000000389771884
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000389771893
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=9
I/wpa_supplicant( 1173): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-89
I/wpa_supplicant( 1173): tsf=0000000371614229
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1173): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 389771836, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 389771862, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 389771874, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 389771884, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 389771893, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2437, timestamp: 371614229, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-89], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42927c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(42927c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,TIME-OUT KILL (timeout was 360000ms),E/cutils-trace( 4596): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4596): ====startRecUseTime====
D/htc.customization.log.level( 4596):  is 
W/CustomizationLogLevel( 4596): Level value is invalid, use default level 2
D/CustomizationManager( 4596):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4596): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4596): Parsing tag category name = system
I/CustomizationCIDLoader( 4596): Parsing tag category name = application
I/CustomizationCIDLoader( 4596): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4596): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4596): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4596): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4596): Parsing tag category name = Settings
D/CustomizationManager( 4596):  Read CID file spent 0.091 (s)
D/CustomizationManager( 4596):  All configurations done spent 0.091 (s)
W/HtcNativeFlag( 4596): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4596): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4596): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4596): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.example.hello, pid=4596, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.example.hello appid=10356 user=-1: uninstall pkg
D/Process (  905): killProcessQuiet, pid=2441
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905): Killing 2441:com.example.hello/u0a356 (adj 0): stop com.example.hello
I/ActivityManager(  905):   Force finishing activity ActivityRecord{42380ef0 u0 com.example.hello/.MainActivity t2}
E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1206): !!! FAILED BINDER TRANSACTION !!!
W/PackageSettings(  905): Skipping PackageSetting{421c33e8 com.test.thalitest/10348} due to missing metadata
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 2441 uid 10356
I/WindowState(  905): WIN DEATH: Window{426017f8 u0 com.example.hello/com.example.hello.MainActivity}
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=204 entropy=198
D/wpa_supplicant( 1173): Add randomness: count=205 entropy=199
D/wpa_supplicant( 1173): Add randomness: count=206 entropy=200
D/wpa_supplicant( 1173): Add randomness: count=207 entropy=201
D/wpa_supplicant( 1173): Add randomness: count=208 entropy=202
D/wpa_supplicant( 1173): Add randomness: count=209 entropy=203
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/wpa_supplicant( 1173): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=210 entropy=204
D/wpa_supplicant( 1173): Add randomness: count=211 entropy=205
D/wpa_supplicant( 1173): Add randomness: count=212 entropy=206
D/wpa_supplicant( 1173): Add randomness: count=213 entropy=207
D/wpa_supplicant( 1173): Add randomness: count=214 entropy=208
D/wpa_supplicant( 1173): Add randomness: count=215 entropy=209
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1173): reply (814) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000408121992
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
I/wpa_supplicant( 1173): tsf=0000000408122012
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000408122019
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-85
I/wpa_supplicant( 1173): tsf=0000000408122026
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000408122032
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=10
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-88
I/wpa_supplicant( 1173): tsf=0000000408122038
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ####
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 408121992, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 408122012, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 408122019, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 408122026, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 408122032, distance: ?(cm), distanceSd: ?(cm)
I/ActivityManager(  905): Force stopping com.example.hello appid=10356 user=0: pkg removed
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  905): Only print Top 10 in ApScanList
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 408122038, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/DotMatrix( 1584): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1584): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
I/acms    ( 1874): Unregistering com.example.hello
E/acms    ( 1874): Could not unregister removed application com.example.hello
W/GeofencerStateMachine( 1438): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(42669c98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1438 10028 null
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/WirelessDisplayService(  905): getDiscoveryDongleList
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): releaseWL(42669c98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Launcher( 1270): Deferring update until onResume
D/Launcher( 1270): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1294): Cleaning up data for package: com.example.hello
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PackageBroadcastService( 2216): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/ActivityManager(  905): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4612 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/MultiDex( 4612): install
E/ExternalAccountType( 1327): Unsupported attribute readOnly
I/MultiDex( 4612): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  905): Delaying start of: ServiceRecord{425797a8 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/MultiDex( 4612): loading existing secondary dex files
I/MultiDex( 4612): load found 1 secondary dex files
I/MultiDex( 4612): install done
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PeopleContactsSync( 2216): CP2 sync disabled
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2216, uid=10028, userID:0
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  905): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4630 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/Icing   ( 2216): doRemovePackageData com.example.hello
D/PMS     (  905): acquireWL(4240ca20): PARTIAL_WAKE_LOCK  Icing 0x1 2216 10028 null
D/PMS     (  905): releaseWL(4240ca20): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4612): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/MultiDex( 4630): install
I/MultiDex( 4630): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  905): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4630): loading existing secondary dex files
I/MultiDex( 4630): load found 1 secondary dex files
I/MultiDex( 4630): install done
I/ProviderInstaller( 4630): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  905): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1402): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
I/[PluginManager]RegisterService( 1402): handle notify Blinkfeed plugin client changed
D/Process (  905): killProcessQuiet, pid=4306
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  905): Killing 4306:com.google.android.talk/u0a111 (adj 15): empty #17
I/IcingCorporaProvider( 2972): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4650 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4612): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4612): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4612): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4612): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4612): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4612): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4612): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4612): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4612): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4612): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4612): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4612): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4612): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4612): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4612): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4612): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4612): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4612): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4612): threadid=12: thread exiting with uncaught exception (group=0x41679e30)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4612): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4612): Process: com.google.android.gms.drive, PID: 4612
E/AndroidRuntime( 4612): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4612): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4612): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4612): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4612): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4612): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4612): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4612): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4612): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4612): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4612): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4612): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4612): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4612): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4612): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4612): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4612): 	at ctn.run(SourceFile:985)
E/SQLiteLog( 2972): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2972): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x6369c960
W/dalvikvm( 2972): threadid=14: thread exiting with uncaught exception (group=0x41679e30)
D/Process ( 4612): killProcess, pid=4612
D/Process ( 4612): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2972): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2972): Process: com.google.android.googlequicksearchbox:search, PID: 2972
E/AndroidRuntime( 2972): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2972): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2972): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2972): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2972): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2972): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2972): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2972): 	at cid.d(PG:186)
E/AndroidRuntime( 2972): 	at clo.g(PG:594)
E/AndroidRuntime( 2972): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2972): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2972): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2972): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2972): 	at clr.tL(PG:827)
E/AndroidRuntime( 2972): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2972): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2972): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2972): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2972): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2972): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
I/ActivityManager(  905): Recipient 4612
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.gms.drive (pid 4612) has died.
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
D/Process ( 2972): killProcess, pid=2972
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/Process ( 2972): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  905): Recipient 2972
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2972): Died!
I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 2972) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
I/ActivityManager(  905): Recipient 4306
W/PackageManager(  905): Unable to load service info ResolveInfo{4262fb98 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (6) end of scan result ==
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteDatabase( 4650): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4650): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4650): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4650): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4650): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4650): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4650): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4650): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4650): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4650): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4650): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4650): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4650): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4650): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4650): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4650): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4650): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4650): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4650): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4650): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4650): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4650): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4650): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4650): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4650): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4650): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4650): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4650): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4650): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4650): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4650): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4650): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4650): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4650): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4650): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4650): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4650): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4650): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4650): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4650): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4650): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4650): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4650): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4650): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4650): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4650): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4650): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4650): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4650): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4650): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4650): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4650): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4650): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4650): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4650): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4650): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4650): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4650): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4650): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4650): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4650): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4650): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4650): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4650): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4650): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4650): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4650): threadid=11: thread exiting with uncaught exception (group=0x41679e30)
E/AndroidRuntime( 4650): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4650): Process: com.google.android.apps.docs, PID: 4650
E/AndroidRuntime( 4650): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4650): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4650): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4650): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4650): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4650): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4650): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4650): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
D/Process ( 4650): killProcess, pid=4650
D/Process ( 4650): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4671 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Recipient 4650
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  905): killProcessQuiet, pid=4180
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4180:com.htc.sense.mms/u0a64 (adj 15): empty #17
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4650) has died.
W/ContextImpl( 4671): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4671): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4671): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4671): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4671): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4671): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4671): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4671): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4671): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4671): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4671): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4671): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4671): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4671): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4671): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4671): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4671): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4671): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4671): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4671): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4671): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4671): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4671): threadid=10: thread exiting with uncaught exception (group=0x41679e30)
E/ActivityManager(  905): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4671): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4671): Process: com.android.keychain, PID: 4671
E/AndroidRuntime( 4671): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4671): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4671): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4671): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4671): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4671): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4671): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4671): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4671): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4684 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4671): killProcess, pid=4671
D/Process ( 4671): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452528171926.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
I/ActivityManager(  905): Recipient 4671
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4671) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10575ms
D/AppTag  ( 4684): getInstance(Context context)
D/AppTag  ( 4684): getInstance(Context context)
D/AppTag  ( 4684): onCreate()
I/ActivityManager(  905): Recipient 4180
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): acquireWL(4266cae0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4413 10160 null
D/PMS     (  905): releaseWL(4266cae0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4702 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4702): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4702 dbg=false s=true
I/DeviceManagement( 4702): PackageUpdateReceiver: vvv Package removed: [com.example.hello]
I/DeviceManagement( 4702): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.example.hello, operation=3}]]
I/DeviceManagement( 4702): WorkflowService: Starting workflow service
I/DeviceManagement( 4702): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41adaef8] args=[Bundle[mParcelledData.dataSize=116]]
I/DeviceManagement( 4702): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4702): PackageUpdateWorkflow: Package update: package=com.example.hello, operation=REMOVE
I/DeviceManagement( 4702): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4702): ModelRegistry: Loading model meta data from resources...
I/DeviceManagement( 4702): BackgroundController: *** Processing package remove for appID=com.example.hello
I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4717 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4702): SessionStateController: Checking invariants...
D/Documents( 4717): Loading roots for com.android.providers.downloads.documents
D/Documents( 4717): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4717): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4717): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4717): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4717): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4717): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4717): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4717): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4717): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4717): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4717): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4717): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4717): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4717): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4717): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4717): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4717): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4717): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4717): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4717): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4717): 	at dalvik.system.NativeStart.main(Native Method)

```
