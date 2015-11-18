#### Test 50388019f4ce509_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@422f1fb0 +
I/Prism.WidgetManager( 1249): onLoadItems() +
I/Prism.ItemManager( 1846): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1846): loadItems() com.htc.launcher.pageview.WidgetManager@422de840 +
I/Prism.WidgetManager( 1846): onLoadItems() +
W/asset   ( 1249): Copying FileAsset 0x66c86008 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
I/Prism.WidgetManager( 1249): onLoadItems() -
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@422f1fb0 -
E/cutils-trace( 2288): Error opening trace file: No such file or directory (2)
W/asset   ( 1846): Copying FileAsset 0x684345e8 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
I/Prism.WidgetManager( 1846): onLoadItems() -
I/Prism.ItemManager( 1846): loadItems() com.htc.launcher.pageview.WidgetManager@422de840 -
D/CustomizationManager( 2288): ====startRecUseTime====
D/htc.customization.log.level( 2288):  is 
W/CustomizationLogLevel( 2288): Level value is invalid, use default level 2
D/CustomizationManager( 2288):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 2288): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2288): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2288): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2288): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2288): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2288): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2288): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2288): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2288): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2288): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2288): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2288): Parsing tag category name = system
I/CustomizationCIDLoader( 2288): Parsing tag category name = application
I/CustomizationCIDLoader( 2288): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2288): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2288): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2288): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2288): Parsing tag category name = Settings
D/CustomizationManager( 2288):  Read CID file spent 0.090 (s)
D/CustomizationManager( 2288):  All configurations done spent 0.091 (s)
W/HtcNativeFlag( 2288): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2288): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2288): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2288): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2288
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1124114536
D/PMS     (  905): acquireHCC(42dda028): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(42d32670): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
I/FeedHostManager( 1249): [onPause]
I/FeedProviderManager( 1249): onPause
I/FeedHostManager( 1249): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@423f7430
I/SocialFeedProvider( 1249): +onPause
I/SocialFeedProvider( 1249): -onPause
D/PMS     (  905): acquireWL(42eb3d58): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2299 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
I/TrimMemoryManager( 1249): [trimMemory] 20
W/asset   ( 2299): Copying FileAsset 0x5c775428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/SensorManager(  905): mEventCount = 150
V/WebViewChromiumFactoryProvider( 2299): Binding Chromium to main looper Looper (main, tid 1) {422604e0}
I/LibraryLoader( 2299): Expected native library version number "",actual native library version number ""
I/chromium( 2299): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2299): Initializing chromium process, renderers=0
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/PMS     (  905): acquireWL(42fd0910): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): acquireWL(42fe4ac8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): releaseWL(42fe4ac8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42fe7440:true
D/BluetoothAdapter( 2299): 1109876440: getState() :  mService = null. Returning STATE_OFF
D/PhoneApp( 1218): EVENT_QUERY_MO_PACKAGES
I/Adreno-EGL( 2299): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2299): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2299): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2299): Local Branch: 
I/Adreno-EGL( 2299): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2299): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2299):                  aa63bbd948f41d15fc72f585e
D/PhoneApp( 1218): -- N1 =0
D/PhoneApp( 1218): -- N2 =0
D/PhoneApp( 1218): -- N3 =0
W/chromium( 2299): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/HtcModeClient( 1478): handler message = 4009
I/HtcModeClient( 1478): start to setup the connection
W/dalvikvm( 2299): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2299): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 2299): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2299): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2299): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 2299): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2299): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2299): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2299): CordovaWebView is running on device made by: HTC
W/AwContents( 2299): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  905): Disable input method client, pid=1249
I/InputMethodManagerService(  905): Enable input method client, pid=2299
W/ResourceType( 2299): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 2299): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@422a7220, mServedView=org.apache.cordova.engine.SystemWebView{4226d1f8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 2299): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  905): Displayed com.example.hello/.MainActivity: +218ms
W/XT9_C   ( 1182): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1182): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  905): releaseWL(42eb3d58): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
E/AndroidProtocolHandler( 2299): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 2299): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 2299): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 2299): JniHelper::setJavaVM(0x41e1e010), pthread_self() = 1658291736
D/JX-Cordova( 2299): jxcore cordova android initializing
W/jxcore-log( 2299): Initializing JXcore engine
W/jxcore-log( 2299): JXcore engine is ready
W/jxcore-log( 2299): Starting JXcore engine
W/jxcore-log( 2299): Platform android
W/jxcore-log( 2299): 
W/jxcore-log( 2299): Process ARCH arm
W/jxcore-log( 2299): 
I/jxcore-log( 2299): JXcore Cordova bridge is ready!
I/jxcore-log( 2299): 
W/jxcore-log( 2299): JXcore engine is started
E/jxcore-log( 2299): >> HTC-HTC Desire 820
E/jxcore-log( 2299): 
I/jxcore-log( 2299): Total memory 1964650496
I/jxcore-log( 2299): 
I/jxcore-log( 2299): Free memory 803999744
I/jxcore-log( 2299): 
I/jxcore-log( 2299): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2299): 
I/jxcore-log( 2299): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2299): 
I/jxcore-log( 2299): userPath [ 'www' ]
I/jxcore-log( 2299): 
I/jxcore-log( 2299): Size 720 1184
I/jxcore-log( 2299): 
I/jxcore-log( 2299): Screen Brightness 10
I/jxcore-log( 2299): 
E/jxcore-log( 2299): Dummy Error Log.
E/jxcore-log( 2299): 
,I/jxcore-log( 2299): getBuffer is called!!!!
I/jxcore-log( 2299): 
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(42dda028): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(42d32670): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,V/TransactionService( 2014): 1-Creating TransactionService
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42caede8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
V/TransactionService( 2014): onStartCommand: 1
D/MmsSystemEventReceiver( 2014): unRegisterForConnectionStateChanges
V/TransactionService( 2014): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 2014): Loading previous transactions.
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/AccFlag ( 1218): device_type: 1
D/TransactionService( 2014): Force set service start id to 1
V/TransactionService( 2014): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 2014): unRegisterForConnectionStateChanges
,V/TransactionService( 2014): Destroying TransactionService
I/ActivityManager(  905): Resuming delayed broadcast
,D/TransactionService( 2014): stopSelfResult: true, mLastHandledServiceId: 1
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=2344 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/TransactionService( 2014): 4-Handling incoming message: { when=-15ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,W/ContextImpl( 2344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.powersaver.PowerSaverNotificationReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver
,D/PowerSaverNotificationService( 2344): updateNotification, mToggle = false
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.qualcomm.privinit for broadcast com.qualcomm.privinit/.BootReciever: pid=2357 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  905): killProcessQuiet, pid=1276
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 1276:com.android.printspooler/u0a161 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 1276
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/qcom_priv_settings( 2357): setprop(net.http.threads) = [10]
,D/qcom_priv_settings( 2357): setprop(net.http.idle_cache.size) = [40]
,D/qcom_priv_settings( 2357): setprop(net.dns.cache_size) = [512]
,D/qcom_priv_settings( 2357): setprop(net.dns.cache_ttl) = [600]
,D/qcom_priv_settings( 2357): setprop(net.http.getzip) = [1]
D/qcom_priv_settings( 2357): setprop(net.http.idle_cache.shutdown) = [true]
,D/qcom_priv_settings( 2357): setprop(net.webkit.cache.size) = [12582912]
,D/qcom_priv_settings( 2357): setprop(net.webkit.cache.mindeadsize) = [4194304]
D/qcom_priv_settings( 2357): setprop(net.webkit.cache.maxdeadsize) = [4194304]
,D/qcom_priv_settings( 2357): setprop(net.nw.cache.prioadvstep) = [86400000]
,D/qcom_priv_settings( 2357): setprop(net.nw.cache.weightadvstep) = [3600000]
,D/qcom_priv_settings( 2357): setprop(net.nw.cache.orderby) = [weight]
,D/Process (  905): killProcessQuiet, pid=1981
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 1981:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/RecoverySystem(  905): No recovery log file
,I/ActivityManager(  905): Recipient 1981
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/BootReceiver(  905): Copying audit failures to DropBox
,I/BootReceiver(  905): Checking for fsck errors
,I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=2371 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 2371): onCreate
,D/AlertReceiver( 2371): beginStartingService
,D/Process (  905): killProcessQuiet, pid=1869
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  905): acquireWL(42eb9850): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 2371 10013 null
I/ActivityManager(  905): Killing 1869:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
D/PMS     (  905): acquireWL(42d41a60): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 1478 10014 null
,I/ActivityManager(  905): Delay finish: com.android.providers.calendar/.CalendarReceiver
D/PMS     (  905): releaseWL(42d41a60): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 null
I/ActivityManager(  905): Recipient 1869
D/AlertService( 2371): start to updateAlertNotification!
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertService( 2371): No fired or scheduled alerts
,D/HtcAlertUtils( 2371): -- cancelReminderNotification --
D/HtcAlertUtils( 2371): broadcastExistReminder!
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(42eb9850): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,W/AlertReceiver( 2371): stopSelfResult true
I/ActivityManager(  905): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2389 uid=10016 gids={50016, 3003, 5012, 2001}
,E/UpdateRequestReceiver( 2389): ignoring update request
,E/UpdateRequestReceiver( 2389): ignoring update request
,E/UpdateRequestReceiver( 2389): ignoring update request
,E/UpdateRequestReceiver( 2389): ignoring update request
,E/UpdateRequestReceiver( 2389): ignoring update request
,E/UpdateRequestReceiver( 2389): ignoring update request
,D/Process (  905): killProcessQuiet, pid=1917
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 1917:com.htc.zero:re_proc/u0a34 (adj 15): empty #17
,W/CustomizationIntentService( 1261): failed at default contact creation!
W/CustomizationIntentService( 1261): java.lang.SecurityException: Requesting code from com.htc.contacts (with uid 10041) to be run in process android.process.acore (with uid 10017)
W/CustomizationIntentService( 1261): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1791)
W/CustomizationIntentService( 1261): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1767)
W/CustomizationIntentService( 1261): 	at android.app.ContextImpl.createPackageContextAsUser(ContextImpl.java:2149)
W/CustomizationIntentService( 1261): 	at android.app.ContextImpl.createPackageContext(ContextImpl.java:2136)
W/CustomizationIntentService( 1261): 	at android.content.ContextWrapper.createPackageContext(ContextWrapper.java:644)
W/CustomizationIntentService( 1261): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.handleIntentInternal(CustomizationIntentService.java:142)
W/CustomizationIntentService( 1261): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.onHandleIntent(CustomizationIntentService.java:103)
W/CustomizationIntentService( 1261): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/CustomizationIntentService( 1261): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/CustomizationIntentService( 1261): 	at android.os.Looper.loop(Looper.java:157)
W/CustomizationIntentService( 1261): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/CustomizationIntentService( 1261): handleIntentInternal(): action = com.htc.intent.action.PRELOAD_CONTACTS, original action = android.intent.action.BOOT_COMPLETED, launched by: null
,W/CustomizationIntentService( 1261): AFH Enable: false, LEONCHAME: false
I/ActivityManager(  905): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=2414 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,W/CustomizationIntentService( 1261): hasBeenInit true
W/CustomizationIntentService( 1261): isNewChameleonHFASupported false
W/CustomizationIntentService( 1261): isHFA true
,W/CustomizationIntentService( 1261): setupWizRun 1
,D/DFPI.PIReciver( 2414): onReceiver action:android.intent.action.BOOT_COMPLETED
,D/DFPI    ( 2414): getInstance = com.htc.demoflopackageinstaller.ApkInstallHelper@4226cdb0
,D/DFPI    ( 2414): set install APK prefrence is false
,I/ActivityManager(  905): Delay finish: com.android.providers.downloads/.DownloadReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=2431 uid=10024 gids={50024, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=2125
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2125:com.futuredial/u0a83 (adj 15): empty #17
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 1917
,I/ActivityManager(  905): Recipient 2125
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=2000
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 2000:com.htc.contacts/u0a41 (adj 15): empty #17
,D/FlexNetS( 1478): set2gLowSignalEnablePref: false
,V/FlexNetS( 1478): [DRX] setHigherPowerIn2GPref to: true
,D/FlexNetS( 1478): setSimCardisWhiteList: false
,V/FlexNetS( 1478): setSimCardCamp3GNetworkSignalPref to: false
,D/FlexNetS( 1478): setCampNetworkisBlackList: false
,V/FlexNetS( 1478): [DRX] setHigherPowerIn2GPref to: true
V/FlexNetS( 1478): setRilHandOverW2GEnable: 0
,D/HtcTelephonyManager( 1478): enablePS_W2G_Handover()
,I/SystemUpdateService( 1198): receiver: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver (has extras) }
D/PMS     (  905): acquireWL(42fabdf8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1198 10028 null
I/ActivityManager(  905): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/SystemUpdateService( 1198): cancelUpdate (empty URL)
,I/SystemUpdateService( 1198): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1198, uid=10028, userID:0
I/SystemUpdateService( 1198): cancelUpdate (empty URL)
,I/SystemUpdateService( 1198): active receiver: disabled
I/ActivityManager(  905): Recipient 2000
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1198, uid=10028, userID:0
,I/AdsMeasurementBroadcastReceiver( 1198): Device was rebooted, starting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1198): Unauthorized to start the main service
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): releaseWL(42fabdf8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 null
,D/GCM     ( 1198): COMPAT: Multi user not supported
,D/GCM     ( 1345): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,V/AuthZen ( 1198): Handling intent: android.intent.action.BOOT_COMPLETED
,V/AuthZen ( 1198): [DefaultAuthzenGcmReceiverDelegateService] Handling delegate intent.
,W/ActivityManager(  905): Unable to start service Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.fitness.service.BrokeredFitnessService (has extras) } U=0: not found
,I/GCoreUlr( 1198): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1415): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/PMS     (  905): acquireWL(42aa2c28): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1415 10028 null
,D/PMS     (  905): acquireWL(42fc2418): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,I/AuthZen ( 1198): Fetching signing key...
D/PMS     (  905): releaseWL(42fc2418): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/AuthZen ( 1198): Signing key fetched successfuly!
,I/AuthZen ( 1198): No encryption key found or existing keys are expired for account thalitester@gmail.com
,I/GCoreUlr( 1415): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1415): Unknown pending intent to remove.
,I/GCoreUlr( 1415): Unbound from all location providers
D/PMS     (  905): acquireWL(42e172c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1415 10028 null
D/PMS     (  905): releaseWL(42e172c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  905): releaseWL(42aa2c28): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
,I/AuthZen ( 1198): Starting Enrollment...
,D/PMS     (  905): releaseWL(42fd0910): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/GoogleHttpClient( 1198): Falling back to old SSLCertificateSocketFactory
I/GoogleHttpClient( 1198): Using GMS GoogleHttpClient
,W/GLSActivity( 1198): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1198): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cryptauth
,E/AuthZen ( 1198): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 1198): atk: Failed to get a token for authzen enrollment
E/AuthZen ( 1198): 	at atj.a(SourceFile:122)
E/AuthZen ( 1198): 	at atm.a(SourceFile:158)
E/AuthZen ( 1198): 	at atm.a(SourceFile:83)
E/AuthZen ( 1198): 	at asv.a(SourceFile:93)
E/AuthZen ( 1198): 	at com.google.android.gms.auth.authzen.DefaultAuthzenGcmReceiverDelegateService.onHandleIntent(SourceFile:33)
E/AuthZen ( 1198): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1198): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1198): 	at android.os.Looper.loop(Looper.java:157)
E/AuthZen ( 1198): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2467 uid=10030 gids={50030}
,V/OneTimeInitializerReceiver( 2467): OneTimeInitializerReceiver.onReceive
,I/ActivityManager(  905): Delay finish: com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
V/OneTimeService( 2467): OneTimeService.onHandleIntent
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=2481 uid=10031 gids={50031, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=2146
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2146:com.htc.lucy/u0a62 (adj 15): empty #17
,I/HtcModeClient( 1478): handler message = 4011
,E/HtcModeClient( 1478): Check connection and retry 2 times.
I/ActivityManager(  905): Recipient 2146
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.partnersetup, clsName=com.google.android.partnersetup.PhoneStateReceiver, state=1, flag=1, pid=2481, uid=10031, userID:0
,I/ActivityManager(  905): Delay finish: com.google.android.partnersetup/.GooglePartnerSetup
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=2481, uid=10031, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=2481, uid=10031, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=2481, uid=10031, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=null, state=1, flag=0, pid=2481, uid=10031, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=2481, uid=10031, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=2481, uid=10031, userID:0
,D/PMS     (  905): acquireWL(42fc4888): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
,D/PMS     (  905): releaseWL(42fc4888): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  905): acquireWL(42fc84f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
,D/PMS     (  905): releaseWL(42fc84f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  905): acquireWL(42fcded8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
,D/PMS     (  905): releaseWL(42fcded8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  905): acquireWL(42fd0c60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
,D/PMS     (  905): releaseWL(42fd0c60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  905): acquireWL(42fd49a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
,D/PMS     (  905): releaseWL(42fd49a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  905): acquireWL(42fd7d58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
,D/PMS     (  905): releaseWL(42fd7d58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  905): acquireWL(42fdb478): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
,D/PMS     (  905): releaseWL(42fdb478): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/RlzPingService( 2481): Setting next ping for 1448439153956
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=2164
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2164:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2164
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=2509 uid=10033 gids={50033, 3003, 5012}
,I/ActivityManager(  905): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=2521 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2093
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2093:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2093
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Personalize.BootComple_( 2521): onReceive() + Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.home.personalize/.receiver.BootCompleteInitializer (has extras) }
,E/Personalize.BootComple_( 2521): action android.intent.action.BOOT_COMPLETED
,E/Personalize.Utilities( 2521): SimpleLauncher not found: com.htc.simplelauncher
,E/Personalize.BootComple_( 2521): initialize: false
,E/Personalize.Utilities( 2521): setApplicationEnabled IllegalArgumentException com.htc.simplelauncher
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.home.personalize, clsName=com.htc.home.personalize.SimpleModeEntryActivity, state=2, flag=1, pid=2521, uid=1000, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.simplelauncher, clsName=null, state=2, flag=0, pid=2521, uid=1000, userID:0
,I/ActivityManager(  905): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=2533 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2059
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2059:com.htc.mediamanager/u0a32 (adj 15): empty #17
,V/BootCompletedReceiver( 2533): ensureAndExecuteUserProfiling: ensureAndExecuteUserProfiling 
,I/ActivityManager(  905): Recipient 2059
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AccTypeManager( 2533): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 2533): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 2533): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 2533): Unsupported attribute readOnly
,D/PeopleYouKnow( 2533): receive intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.contacts/.peopleyouknow.PeopleYouKnowReceiver (has extras) }
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=2550 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=2191
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
W/AccTypeManager( 2533): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 2533): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  905): Killing 2191:com.htc.wifidisplay/u0a153 (adj 15): empty #17
,D/AccTypeManager( 2533): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  905): Recipient 2191
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/ExternalAccountType( 2533): Unsupported attribute readOnly
,V/HtcDataRoamingWidget.DisableWidgetReceiver( 2550): ACTION_BOOT_COMPLETED
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.dataroaming, clsName=com.htc.rosiewidgets.dataroaming.HtcSettingWidgetProvider, state=1, flag=1, pid=2550, uid=10042, userID:0
,V/HtcDataStripWidget.DisableWidgetReceiver( 2550): ACTION_BOOT_COMPLETED
,D/Process (  905): killProcessQuiet, pid=1846
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.datastrip, clsName=com.htc.rosiewidgets.datastrip.HtcSettingWidgetProvider, state=1, flag=1, pid=2550, uid=10042, userID:0
,I/ActivityManager(  905): Killing 1846:com.htc.sense.news/u0a75 (adj 15): empty #17
D/DotMatrix( 1548): [EventReceiver] onReceive, version:1.3
,D/DotMatrix( 1107): [SystemUIService] onCreate(), version: 1.3
I/ActivityManager(  905): Start proc com.htc.aurora for broadcast com.htc.aurora/.receiver.BootCompletedReceiver: pid=2562 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,W/dalvikvm( 1107): VFY: unable to resolve interface method 6812: Lcom/android/internal/telephony/ITelephony;.answerRingingCallForSubscriber (J)V
,W/dalvikvm( 1107): VFY: unable to resolve interface method 6824: Lcom/android/internal/telephony/ITelephony;.endCallForSubscriber (J)Z
,D/DotMatrix( 1107): [SystemUIService] EventService api version:1.3
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 1846
,I/ActivityManager(  905): Start proc com.htc.aurora:remote for service com.htc.aurora/.download.DownloadService: pid=2576 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  905): Delay finish: com.htc.aurora/.receiver.BootCompletedReceiver
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.aurora, clsName=com.htc.aurora.download.DownloadReceiver, state=1, flag=1, pid=2576, uid=10047, userID:0
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=2592 uid=10050 gids={50050, 3003, 5012, 1028, 1015, 3002, 3001, 2001, 1023}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.aurora, clsName=com.htc.aurora.download.DownloadReceiver, state=2, flag=1, pid=2576, uid=10047, userID:0
D/Process (  905): killProcessQuiet, pid=1607
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 1607:com.google.android.gms.wearable/u0a28 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 1607
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=2014
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2014:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2014
,I/MediaFocusControl(  905):   Remote Control   registerMediaButtonIntent() for PendingIntent{42c18630: PendingIntentRecord{42b599a0 com.htc.music broadcastIntent}}
,D/DotMatrix( 1548): [EventService] onClientChange, clearing: true
,D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] onClientChange, currEventType: 26
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  905): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=2608 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=2344
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2344:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/ActivityManager(  905): Recipient 2344
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=2622 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2357
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2357:com.qualcomm.privinit/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2357
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 2622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageService( 2622): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 2622): MY_DEBUG = false
,D/PMS     (  905): acquireWL(423bbd38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/ActivityManager(  905): Resuming delayed broadcast
,V/AlarmManager(  905): sending alarm PendingIntent{42bca568: PendingIntentRecord{42a83eb0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1447834355151, Int=900000
,W/ContextImpl( 2622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncServiceReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncServiceReceiver
,D/SmartSyncUtils( 2622): getMobilePolicyEnabled, result = true
W/ContextImpl( 2622): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.startService:228 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.onHandleIntent:75 android.app.IntentService$ServiceHandler.handleMessage:65 
I/ActivityManager(  905): Resuming delayed broadcast
,W/ContextImpl( 2622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,W/ContextImpl( 2622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=2371
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2371:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1403): onHandleIntent, action: android.intent.action.BOOT_COMPLETED, data: null
I/ActivityManager(  905): Recipient 2371
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Bundle  ( 1403): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1403): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:,
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1403): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1403): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1403): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1403): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1403): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1403): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1403): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1403): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1403): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1403): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/FeatureList( 1403): feature
D/FeatureList( 1403): type
,D/FeatureList( 1403): description
,W/Bundle  ( 1403): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1403): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1403): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1403): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1403): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1403): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1403): Attempt to cast generated internal exception:
W/Bundle  ( 1403): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1403): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1403): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1403): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/HABCtrl (  905): ALG=2, lsvalue=40(1th)->90(2th), last_level=-1, lValue=64->64
,D/PluginProvider( 1403): Begin Apply Batch
,E/PluginProvider( 1403): conflict when insert feature, ignored
,D/Process (  905): killProcessQuiet, pid=2389
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2389:com.google.android.configupdater/u0a16 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2389
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PluginProvider( 1403): apply Batch success
,I/[PluginManager]RegisterService( 1403): Notify Carousel that a new TabPlugin has been installed!
,I/ActivityManager(  905): Resuming delayed broadcast
,I/WSP     ( 1403): [Receiver] EVENT - BOOT COMPLETED, is settings existed? true
,D/AutoSetting( 1403): receiver - intent: android.intent.action.BOOT_COMPLETED
,D/HtcAppUPService( 1403): CustomizationReceiver  receieve: android.intent.action.BOOT_COMPLETED
,D/AutoSetting( 1403): service - onStartCommand() action: com.htc.app.autosetting.bootcomplete
D/AutoSetting( 1403): service - onStartCommand() boot completed, remove cache
D/AutoSetting( 1403): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1403): service - handleMessage() setting current location null
D/AutoSetting( 1403): service - handleMessage() removing cache
,D/AutoSetting( 1403): service - AddressCache: clean up all cache
,I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.upservice.HtcUPServiceReceiver
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  905): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1243
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 0(ms)
D/BluetoothManagerService(  905): Message: MESSAGE_DISABLE
,D/WifiManager( 2299): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
,W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: false pid=2299, uid=10355
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 915
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 2(ms)
D/HtcAppUPService( 1403): HtcUPService onCreate()
D/HtcAppUPService( 1403): DatabaseHelper [DatabaseHelper constructor]
D/HtcAppUPService( 1403): PolicyStore [Init] Get cached policy bundle
D/HtcAppUPService( 1403): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.BOOT_COMPLETED cmp=com.htc.sense.hsp/.upservice.HtcUPService }, this = com.htc.sense.hsp.upservice.HtcUPService@42525d40
I/jxcore-log( 2299): ****TEST TOOK:  5036  ms ****
I/jxcore-log( 2299): 
I/jxcore-log( 2299): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2299): 
D/HtcAppUPService( 1403): HtcUPServicePreference Is policy store first run: false
,D/HtcAppUPService( 1403): appid: tellhtc_client, category: usage_report, key: enable, value: 1, due date: -1, current time: 1447834356261, default value: null
D/HtcAppUPService( 1403): HtcUPServicePreference Upload schedule enable? false
W/dalvikvm( 1403): VFY: unable to resolve static field 680 (common_google_play_services_unknown_issue) in Lcom/google/android/gms/R$string;
E/GooglePlayServicesUtil( 1403): The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
E/dalvikvm( 1403): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 1403): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 1403): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 1403): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 1403): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ProviderInstaller( 1403): Installed default security provider GmsCore_OpenSSL
,D/HtcAppUPService( 1403): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.BOOT_COMPLETED
,D/HtcAppUPService( 1403): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
,D/HtcAppUPService( 1403): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@42525d40
I/ActivityManager(  905): Resuming delayed broadcast
,D/HtcAppUPService( 1403): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
I/ActivityManager(  905): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=2651 uid=10055 gids={50055, 1028, 1015, 3003, 5012, 3001, 3002}
,V/BootReceiver( 2651): onReceive: android.intent.action.BOOT_COMPLETED
,D/BootReceiver( 2651): boot completed:
,D/BootReceiver( 2651): isValid:  isEnabledEasyAccess = false, isEnabledQuickDial = false
,D/Process (  905): killProcessQuiet, pid=2414
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.video for broadcast com.htc.video/com.htc.videowidget.videoDMC.DLNAReceiver: pid=2663 uid=10056 gids={50056, 2001, 3002, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  905): Killing 2414:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  905): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=2678 uid=10059 gids={50059, 1028, 1015, 3003, 5012, 1023}
,D/Process (  905): killProcessQuiet, pid=2110
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2110:android.process.media/u0a21 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2110
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2414
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/LMW     ( 2678): [2691][ActionDeviceStorageHandler] onActionBootComplete++
W/LMW     ( 2678): [2691][ActionDeviceStorageHandler] onActionBootComplete--
I/ActivityManager(  905): Delay finish: com.htc.lmw/.StorageBroadcastReceiver
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc android.process.media for broadcast com.android.providers.media/.MediaScannerReceiver: pid=2692 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
D/Process (  905): killProcessQuiet, pid=2431
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2431:com.htc.fm/u0a24 (adj 15): empty #17
,I/DownloadManager( 2692): Enable ItsOn feature: false
,E/cutils-trace( 2648): Error opening trace file: No such file or directory (2)
,D/MediaProvider( 2692): [onCreate]+ 
D/MediaProvider( 2692): [attachVolume] attach internal db
D/MediaProvider( 2692): [DatabaseHelper] version:705, internal:true
,V/MediaProvider( 2692): Attached volume: internal
,D/MediaProvider( 2692): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
D/MediaProvider( 2692): [MP][DEBUG] Storage State: mounted
,D/MediaProvider( 2692): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 2692): [MP][DEBUG] Storage State: removed
,D/MediaProvider( 2692): [MP][DEBUG] Sorting: order:2, path:/storage/usb
,D/MediaProvider( 2692): [MP][DEBUG] Storage State: removed
,D/MediaProvider( 2692): [onCreate] External Storage State = mounted
D/MediaProvider( 2692): [DatabaseHelper] version:705, internal:false
,D/MediaProvider( 2692): [attachVolume] volumeID=11223344,dbName=external-ab4130.db
,V/MediaProvider( 2692): Attached volume: external
,D/MediaProvider( 2692): [onCreate]-
,D/MediaScannerReceiver( 2692): onReceive Intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.media/.MediaScannerReceiver (has extras) }
,D/MediaProviderUtils( 2692): [scanEx]volume:internal,action:android.intent.action.BOOT_COMPLETED
,D/MediaProviderUtils( 2692): [scanEx]volume:customize,action:android.intent.action.BOOT_COMPLETED
,D/MediaProviderUtils( 2692): [scanEx]volume:external,action:android.intent.action.MEDIA_MOUNTED
,D/MediaProviderUtils( 2692): [scanEx]volume:external,action:android.intent.action.MEDIA_MOUNTED
,D/MediaProviderUtils( 2692): [scanEx]volume:external,action:android.intent.action.MEDIA_MOUNTED
I/ActivityManager(  905): Delay finish: com.android.providers.media/.MediaScannerReceiver
,D/MediaScannerServiceEx( 2692): [ServiceHandler][handleMessage]+internal
,D/MediaScannerServiceEx( 2692): [3] stop task - current task is null
,D/MediaScannerServiceEx( 2692): [4] stop task - current task is null
,D/MediaScannerServiceEx( 2692): [5] stop task - current task is null
D/PMS     (  905): acquireWL(42ecc258): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2692 10021 null
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaProvider( 2692): [writeUserBehaviorLog] +
I/ActivityManager(  905): Recipient 2431
,D/MediaProvider( 2692): [writeUserBehaviorLog] -
,D/MediaScannerServiceEx( 2692): getDefaultLocale =en_GB
D/MediaScannerServiceEx( 2692): [scan]+internal,/system/media
,D/MediaScanner( 2692): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
,D/CustomizationManager( 2648): ====startRecUseTime====
D/htc.customization.log.level( 2648):  is 
,W/CustomizationLogLevel( 2648): Level value is invalid, use default level 2
,D/MediaScanner( 2692):  prescan time: 95ms
D/MediaScanner( 2692):     scan time: 30ms
D/MediaScanner( 2692): postscan time: 0ms
D/MediaScanner( 2692):    total time: 125ms
D/MediaScanner( 2692): -----------------------------------------------------------------
D/MediaScanner( 2692): firstscan(media) time: 19ms
D/MediaScanner( 2692): secondscan(non-media) time: 6ms
D/MediaScanner( 2692):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2692):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2692):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2692):  [Total]    File(Image+Video+Audio+Others) in database : 366
,D/MediaScannerServiceEx( 2692): [scan]-
,D/MediaProvider( 2692): [delete][21]
,D/MediaProvider( 2692): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 2692): [recoverParentNodes] - 0
D/MediaProvider( 2692): [update][3]
,D/MediaScannerServiceEx( 2692): [scan] Recover Parent Node is finished!
,D/TAG     ( 2692): mWakeLock.release() at scan()
,D/MediaScannerServiceEx( 2692): [ServiceHandler][handleMessage]+customize
D/PMS     (  905): releaseWL(42ecc258): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/PMS     (  905): acquireWL(42d54948): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2692 10021 null
,D/MediaScannerServiceEx( 2692): getDefaultLocale =en_GB
D/MediaScannerServiceEx( 2692): [scan]+internal,/system/customize/resource
,D/MediaScanner( 2692): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
,D/CustomizationManager( 2648):  Read ACC file spent 0.057 (s)
,D/CIDMapFileReader( 2648): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2648): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2648): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2648): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2648): Parsing tag item name = HTC__032
,D/CIDMapFileReader( 2648): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2648): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2648): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2648): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 2648): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 2648): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 2648): Parsing tag category name = system
,I/CustomizationCIDLoader( 2648): Parsing tag category name = application
,I/CustomizationCIDLoader( 2648): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2648): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2648): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 2648): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 2648): Parsing tag category name = Settings
D/CustomizationManager( 2648):  Read CID file spent 0.103 (s)
,D/CustomizationManager( 2648):  All configurations done spent 0.103 (s)
W/HtcNativeFlag( 2648): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2648): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2648): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 2648): Fail to get flag for type 'language', use default value: -1
,D/MediaScanner( 2692):  prescan time: 23ms
D/MediaScanner( 2692):     scan time: 15ms
D/MediaScanner( 2692): postscan time: 0ms
D/MediaScanner( 2692):    total time: 38ms
D/MediaScanner( 2692): -----------------------------------------------------------------
D/MediaScanner( 2692): firstscan(media) time: 8ms
D/MediaScanner( 2692): secondscan(non-media) time: 7ms
D/MediaScanner( 2692):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2692):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2692):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2692):  [Total]    File(Image+Video+Audio+Others) in database : 366
,D/MediaScannerServiceEx( 2692): [scan]-
,D/MediaProvider( 2692): [delete][3]
,D/MediaProvider( 2692): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 2692): [recoverParentNodes] - 0
D/MediaProvider( 2692): [update][1]
,D/MediaScannerServiceEx( 2692): [scan] Recover Parent Node is finished!
,D/TAG     ( 2692): mWakeLock.release() at scan()
,D/PMS     (  905): releaseWL(42d54948): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 2692): [ServiceHandler][handleMessage]+external
D/MediaScannerServiceEx( 2692): [ServiceHandler][handleMessage] volume: external, action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 2692): ignoreDirectories[ 0 ] = /storage/ext_sd
D/MediaScannerServiceEx( 2692): ignoreDirectories[ 1 ] = /storage/usb
D/MediaScannerServiceEx( 2692): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 2692): [update][3]#0#
D/MediaProvider( 2692): [update][2]#0#
D/MediaProvider( 2692): [update][3]#0#
D/MediaScannerServiceEx( 2692): [deleteRowsEqualVolid]+65537
D/MediaProvider( 2692): [delete][3]#0#
D/MediaScannerServiceEx( 2692): [deleteRowsEqualVolid]-0
,D/PackageManager(  905): deletePackageAsUser: pkg=com.example.hello, pid=2648, uid=2000 user=0
,D/MediaProvider( 2692): [update][11]#1#
D/MediaScannerServiceEx( 2692): [AliveExtStorageRows]-0, 0, 0
,D/MediaScannerServiceEx( 2692): [deleteNonUseAlbumArts]+
,D/MediaScannerServiceEx( 2692): [deleteNonUseAlbumArts]-
,D/MediaScannerServiceEx( 2692): [ServiceHandler][handleMessage][EXTERNAL]-android.intent.action.MEDIA_MOUNTED,[Ljava.lang.String;@424140c8
,D/PMS     (  905): acquireWL(42d38e98): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2692 10021 null
,E/MediaProvider( 2692): no database for attached volume content://media/external
,W/asset   (  905): Copying FileAsset 0x69f4ee50 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  905): killProcessQuiet, pid=2299
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
I/ActivityManager(  905): Killing 2299:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  905): Force removing ActivityRecord{42c1d320 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/InputDispatcher(  905): channel '42d6b370 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  905): channel '42d6b370 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '42d6b370 com.example.hello.MainActivity (s)'
I/WindowManager(  905): WINDOW DIED Window{42d6b370 u0 com.example.hello/com.example.hello.MainActivity}
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
,W/PackageSettings(  905): Skipping PackageSetting{429a2730 com.test.thalitest/10348} due to missing metadata
,I/ActivityManager(  905): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
I/acms    ( 1769): Unregistering com.example.hello
E/acms    ( 1769): Could not unregister removed application com.example.hello
D/DotMatrix( 1548): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1548): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1548): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,W/GeofencerStateMachine( 1415): Ignoring removeGeofence because network location is disabled.
,D/PMS     (  905): acquireWL(42fe6360): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
I/FeedHostManager( 1249): [onResume]
I/FeedProviderManager( 1249): onResume
I/SocialFeedProvider( 1249): +onResume
I/SocialFeedProvider( 1249): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1249): -onResume
I/ConnectivityHelper( 1249): [getCurrentConnectionType] no network connection
D/MediaScannerServiceEx( 2692): getDefaultLocale =en_GB
,D/MediaScannerServiceEx( 2692): [scan]+external,/storage/emulated/0
D/MediaScanner( 2692): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
D/MediaScanner( 2692): Ignore scan directories /storage/ext_sd
D/MediaScanner( 2692): Ignore scan directories /storage/usb
,D/MediaScanner( 2692): Ignore scan directories null
,W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.launcher (1249/10075)
,D/PMS     (  905): releaseWL(42fe6360): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1310): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1310): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/AccTypeManager( 2533): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 2533): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1310): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/AccTypeManager( 2533): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1310): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,E/ExternalAccountType( 2533): Unsupported attribute readOnly
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42d21ba0 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/MtpReceiver( 2692): [MTP][MtpReceiver][onReceive]+
,D/MtpReceiver( 2692): [MP][DEBUG][MtpReceiver] requestFullScanForMTP
,D/MtpReceiver( 2692): [MP][DEBUG][MtpReceiver] requestFullScanForMTP dir = /storage/emulated/0
D/MtpReceiver( 2692): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2692): [MTP][handleMessage][startService]
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/MtpReceiver( 2692): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MediaProvider( 2692): bindService() MTP Service Connection.
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/MtpReceiver( 2692): [MTP][handleMessage]-
I/ActivityManager(  905): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=2723 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,D/MtpService( 2692): updating state; isCurrentUser=true, mMtpLocked=false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 2299 uid 10355
,I/InputMethodManagerService(  905): Enable input method client, pid=1249
W/Binder  ( 1182): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1182): java.lang.NullPointerException
W/Binder  ( 1182): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1182): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1182): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1182): 	at dalvik.system.NativeStart.run(Native Method)
,D/MtpService( 2692): addStorageInternal without MtpServer
,D/MediaProvider( 2692): [update][10]#1#
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
,D/MtpService( 2692): [MTP][onCreate]-
,D/MtpService( 2692): [MTP] startForeground
,E/MediaProvider( 2692): no database for attached volume content://media/external
D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/MediaProvider( 2692): [update][13]#1#
,D/MtpService( 2692): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 2692): TotalSize=1918604,MediaCacheLimit=6000
,D/MtpService( 2692): starting MTP server in MTP mode
,D/MtpService( 2692): addStorageInternal 65537 /storage/emulated/0
,D/MtpService( 2692): [checkStorageState] Storage state - mounted
,D/MtpService( 2692): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
,D/MessageFrequencyProvider( 2723): onCreate
,V/GetPrviateResource( 2723): GetPrviateResource
,V/GetPrviateResource( 2723): GetPrviateResource
,D/MessageCustFlag( 2723): sense_version=6.0
,D/BTAccessoryUtil( 2723): createReceiver
,D/BTAccessoryUtil( 2723): registerReceiver return intent = null
D/MessageCustFlag( 2723): sku_id=99
,W/SystemReader( 2723): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 2723): supportCMAS(SIE)/init? false/true
D/MmsConfig( 2723): networkCode: 
,D/MessageCustFlag( 2723): sku_id=99
D/MmsConfig( 2723): SIE smsPri: null
,D/MmsConfig( 2723): networkCode: 
,D/HtcTelephonyCapability( 2723): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 2723): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 2723): getRATByHtcTelephonyCapability:1
,W/SystemReader( 2723): Cannot find qct_8960_interface, use default value instead
,V/MmsSystemEventReceiver( 2723): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/ExchangePolicystatus( 2723): onReceive()
,D/ExchangePolicystatus( 2723): onReceive(): ACTION_BOOT_COMPLETED
D/MessageUtils( 2723): Text messaging allow status = allow
,D/Messaging( 2723): EAS allow SMS !!!
D/ExchangePolicystatus( 2723): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
,D/Messaging( 2723): EAS allow SMS !!!
,V/SmsReceiverService( 2723): onStart: #1, @1110180968
V/SmsReceiverService( 2723): action: android.intent.action.BOOT_COMPLETED
D/SmsReceiverService( 2723): isCbm: false
D/SmsReceiverService( 2723): isDiscard: false
,D/SettingsManager( 2723): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@42269eb8
D/PMS     (  905): acquireWL(42a9fb98): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 2723 10064 null
,I/ActivityManager(  905): Delay finish: com.htc.sense.mms/.PolicyReceiver
V/SmsReceiverService( 2723): handleBootCompleted
,W/PackageManager(  905): Unable to load service info ResolveInfo{42caf6c8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1218): sku_id=99
,D/SmsReceiverService( 2723): OutBoxSize = 0
D/SmsReceiverService( 2723): sendFirstQueuedMessage start: 0
,D/MessageCustFlag( 2723): sku_id=99
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 61
,D/AccFlag ( 1218): sku_id=99
,D/SmsReceiverService( 2723): sendFirstQueuedMessage end cnt> 0
D/SpaceBufferUtil( 2723): > createBufferFile()
,D/SpaceBufferUtil( 2723): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
,D/SpaceBufferUtil( 2723): < createBufferFile()
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,D/DotMatrix( 1548): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,I/RemoteViews( 1107): com.android.providers.media (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{422a9b20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1107): com.android.providers.media 1 7 0 10
I/RemoteViews( 1107): com.android.providers.media (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{422a9dc8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.android.providers.media 1 7 1 15
,W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,V/AlarmManager(  905): sending alarm PendingIntent{42d07508: PendingIntentRecord{42fb51e8 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=43605, Int=0
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42d62778 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.PolicyReceiver: pid=2753 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
,D/MyReportAgent( 2753): ReportService [##] onCreate(), this = com.htc.reportagent.ReportService@4226b778
,I/ActivityManager(  905): Delay finish: com.htc.reportagent/.receiver.PolicyReceiver
D/MyReportAgent( 2753): ReportService [##] onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.reportagent.action.BOOT_COMPLETE cmp=com.htc.reportagent/.ReportService }, this = com.htc.reportagent.ReportService@4226b778
D/MyReportAgent( 2753): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE

```
