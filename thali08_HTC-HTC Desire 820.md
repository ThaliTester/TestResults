#### Test 50388019c82294c_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1492): handler message = 4009
I/HtcModeClient( 1492): start to setup the connection
,I/SensorManager(  908): mEventCount = 150
E/cutils-trace( 2198): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 2198): ====startRecUseTime====
D/htc.customization.log.level( 2198):  is 
W/CustomizationLogLevel( 2198): Level value is invalid, use default level 2
D/CustomizationManager( 2198):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 2198): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2198): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2198): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2198): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2198): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2198): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2198): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2198): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2198): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2198): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2198): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2198): Parsing tag category name = system
I/CustomizationCIDLoader( 2198): Parsing tag category name = application
I/CustomizationCIDLoader( 2198): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2198): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2198): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2198): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2198): Parsing tag category name = Settings
D/CustomizationManager( 2198):  Read CID file spent 0.088 (s)
D/CustomizationManager( 2198):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 2198): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2198): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2198): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2198): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1115947272
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2198
D/PMS     (  908): acquireHCC(428418a8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
D/PMS     (  908): acquireHCC(42843040): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
D/PMS     (  908): acquireWL(4282e158): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/FeedHostManager( 1250): [onPause]
I/FeedProviderManager( 1250): onPause
I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c5c720
I/SocialFeedProvider( 1250): +onPause
I/SocialFeedProvider( 1250): -onPause
I/ActivityManager(  908): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2209 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
W/asset   ( 2209): Copying FileAsset 0x5c76a428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1250): [trimMemory] 20
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41b5ff70 +
I/Prism.WidgetManager( 1250): onLoadItems() +
I/Prism.ItemManager( 1854): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1854): loadItems() com.htc.launcher.pageview.WidgetManager@41b4cc80 +
I/Prism.WidgetManager( 1854): onLoadItems() +
V/WebViewChromiumFactoryProvider( 2209): Binding Chromium to main looper Looper (main, tid 1) {41ac7f88}
I/LibraryLoader( 2209): Expected native library version number "",actual native library version number ""
I/chromium( 2209): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2209): Initializing chromium process, renderers=0
D/PMS     (  908): acquireWL(42379940): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422953b8:true
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 2209): 1101925664: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  908): acquireWL(425252a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  908): releaseWL(425252a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 2209): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2209): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2209): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2209): Local Branch: 
I/Adreno-EGL( 2209): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2209): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2209):                  aa63bbd948f41d15fc72f585e
W/chromium( 2209): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 2209): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2209): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 2209): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2209): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2209): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 2209): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2209): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2209): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2209): CordovaWebView is running on device made by: HTC
,W/AwContents( 2209): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  908): Disable input method client, pid=1250
W/ResourceType( 2209): No package identifier when getting name for resource number 0x00000064
I/InputMethodManagerService(  908): Enable input method client, pid=2209
I/InputMethodManager( 2209): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b12068, mServedView=org.apache.cordova.engine.SystemWebView{41ad8040 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1188): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1188): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1188): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1188): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 2209): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  908): Displayed com.example.hello/.MainActivity: +265ms
D/PMS     (  908): releaseWL(4282e158): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/asset   ( 1250): Copying FileAsset 0x666cc700 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
I/Prism.WidgetManager( 1250): onLoadItems() -
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41b5ff70 -
E/AndroidProtocolHandler( 2209): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 2209): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/asset   ( 1854): Copying FileAsset 0x6835d1f8 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
I/Prism.WidgetManager( 1854): onLoadItems() -
I/Prism.ItemManager( 1854): loadItems() com.htc.launcher.pageview.WidgetManager@41b4cc80 -
D/JsMessageQueue( 2209): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 2209): JniHelper::setJavaVM(0x415a5048), pthread_self() = 1658129224
D/JX-Cordova( 2209): jxcore cordova android initializing
W/jxcore-log( 2209): Initializing JXcore engine
W/jxcore-log( 2209): JXcore engine is ready
W/jxcore-log( 2209): Starting JXcore engine
D/PhoneApp( 1223): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1223): -- N1 =0
D/PhoneApp( 1223): -- N2 =0
D/PhoneApp( 1223): -- N3 =0
W/jxcore-log( 2209): Platform android
W/jxcore-log( 2209): 
W/jxcore-log( 2209): Process ARCH arm
W/jxcore-log( 2209): 
I/jxcore-log( 2209): JXcore Cordova bridge is ready!
I/jxcore-log( 2209): 
W/jxcore-log( 2209): JXcore engine is started
E/jxcore-log( 2209): >> HTC-HTC Desire 820
E/jxcore-log( 2209): 
I/jxcore-log( 2209): Total memory 1964650496
I/jxcore-log( 2209): 
I/jxcore-log( 2209): Free memory 842833920
I/jxcore-log( 2209): 
I/jxcore-log( 2209): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2209): 
I/jxcore-log( 2209): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2209): 
I/jxcore-log( 2209): userPath [ 'www' ]
I/jxcore-log( 2209): 
I/jxcore-log( 2209): Size 720 1184
I/jxcore-log( 2209): 
I/jxcore-log( 2209): Screen Brightness 10
I/jxcore-log( 2209): 
E/jxcore-log( 2209): Dummy Error Log.
E/jxcore-log( 2209): 
,I/jxcore-log( 2209): getBuffer is called!!!!
I/jxcore-log( 2209): 
,W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(428418a8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  908): releaseHCC(42843040): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{424eec48 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
V/TransactionService( 1953): 1-Creating TransactionService
,V/TransactionService( 1953): onStartCommand: 1
,D/MmsSystemEventReceiver( 1953): unRegisterForConnectionStateChanges
V/TransactionService( 1953): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 1953): Loading previous transactions.
,D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1223): device_type: 1
,D/TransactionService( 1953): Force set service start id to 1
V/TransactionService( 1953): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 1953): unRegisterForConnectionStateChanges
,V/TransactionService( 1953): Destroying TransactionService
I/ActivityManager(  908): Resuming delayed broadcast
,D/TransactionService( 1953): stopSelfResult: true, mLastHandledServiceId: 1
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=2255 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/TransactionService( 1953): 4-Handling incoming message: { when=-27ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,W/ContextImpl( 2255): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.powersaver.PowerSaverNotificationReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver
,D/PowerSaverNotificationService( 2255): updateNotification, mToggle = false
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.qualcomm.privinit for broadcast com.qualcomm.privinit/.BootReciever: pid=2268 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  908): killProcessQuiet, pid=1811
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 1811:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 1811
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/HtcModeClient( 1492): handler message = 4011
E/HtcModeClient( 1492): Check connection and retry 2 times.
,D/qcom_priv_settings( 2268): setprop(net.http.threads) = [10]
,D/qcom_priv_settings( 2268): setprop(net.http.idle_cache.size) = [40]
,D/qcom_priv_settings( 2268): setprop(net.dns.cache_size) = [512]
,D/qcom_priv_settings( 2268): setprop(net.dns.cache_ttl) = [600]
D/qcom_priv_settings( 2268): setprop(net.http.getzip) = [1]
,D/qcom_priv_settings( 2268): setprop(net.http.idle_cache.shutdown) = [true]
,D/qcom_priv_settings( 2268): setprop(net.webkit.cache.size) = [12582912]
,D/qcom_priv_settings( 2268): setprop(net.webkit.cache.mindeadsize) = [4194304]
,D/qcom_priv_settings( 2268): setprop(net.webkit.cache.maxdeadsize) = [4194304]
,D/qcom_priv_settings( 2268): setprop(net.nw.cache.prioadvstep) = [86400000]
,D/qcom_priv_settings( 2268): setprop(net.nw.cache.weightadvstep) = [3600000]
,D/qcom_priv_settings( 2268): setprop(net.nw.cache.orderby) = [weight]
,D/Process (  908): killProcessQuiet, pid=1828
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 1828:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/RecoverySystem(  908): No recovery log file
,I/BootReceiver(  908): Copying audit failures to DropBox
,I/BootReceiver(  908): Checking for fsck errors
,I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=2282 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  908): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=2294 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
,I/DownloadManager( 2294): Enable ItsOn feature: false
,I/ActivityManager(  908): Recipient 1828
,D/CalendarApplication( 2282): onCreate
,D/AlertReceiver( 2282): beginStartingService
,D/Process (  908): killProcessQuiet, pid=1917
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Killing 1917:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/PMS     (  908): acquireWL(425c79a8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 2282 10013 null
D/PMS     (  908): acquireWL(4285fd88): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 1492 10014 null
I/ActivityManager(  908): Recipient 1917
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Delay finish: com.android.providers.calendar/.CalendarReceiver
D/MediaProvider( 2294): [onCreate]+ 
D/MediaProvider( 2294): [attachVolume] attach internal db
D/MediaProvider( 2294): [DatabaseHelper] version:705, internal:true
,V/MediaProvider( 2294): Attached volume: internal
,D/AlertService( 2282): start to updateAlertNotification!
,D/MediaProvider( 2294): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
,D/PMS     (  908): releaseWL(4285fd88): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 null
D/MediaProvider( 2294): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 2294): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 2294): [MP][DEBUG] Storage State: removed
D/MediaProvider( 2294): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/MediaProvider( 2294): [MP][DEBUG] Storage State: removed
D/MediaProvider( 2294): [onCreate] External Storage State = mounted
D/MediaProvider( 2294): [DatabaseHelper] version:705, internal:false
D/MediaProvider( 2294): [attachVolume] volumeID=11223344,dbName=external-ab4130.db
V/MediaProvider( 2294): Attached volume: external
D/MediaProvider( 2294): [onCreate]-
D/AlertService( 2282): No fired or scheduled alerts
D/HtcAlertUtils( 2282): -- cancelReminderNotification --
,D/HtcAlertUtils( 2282): broadcastExistReminder!
,D/DotMatrix( 1538): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(425c79a8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
,W/AlertReceiver( 2282): stopSelfResult true
I/ActivityManager(  908): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2315 uid=10016 gids={50016, 3003, 5012, 2001}
,D/Process (  908): killProcessQuiet, pid=1262
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 1262:com.android.printspooler/u0a161 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 1262
,D/MediaProvider( 2294): [writeUserBehaviorLog] +
,D/MediaProvider( 2294): [writeUserBehaviorLog] -
,E/UpdateRequestReceiver( 2315): ignoring update request
,E/UpdateRequestReceiver( 2315): ignoring update request
,E/UpdateRequestReceiver( 2315): ignoring update request
,E/UpdateRequestReceiver( 2315): ignoring update request
,E/UpdateRequestReceiver( 2315): ignoring update request
,E/UpdateRequestReceiver( 2315): ignoring update request
,D/Process (  908): killProcessQuiet, pid=1979
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 1979:com.htc.showme/u0a82 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 1979
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/CustomizationIntentService( 1274): failed at default contact creation!
W/CustomizationIntentService( 1274): java.lang.SecurityException: Requesting code from com.htc.contacts (with uid 10041) to be run in process android.process.acore (with uid 10017)
W/CustomizationIntentService( 1274): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1791)
W/CustomizationIntentService( 1274): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1767)
W/CustomizationIntentService( 1274): 	at android.app.ContextImpl.createPackageContextAsUser(ContextImpl.java:2149)
W/CustomizationIntentService( 1274): 	at android.app.ContextImpl.createPackageContext(ContextImpl.java:2136)
W/CustomizationIntentService( 1274): 	at android.content.ContextWrapper.createPackageContext(ContextWrapper.java:644)
W/CustomizationIntentService( 1274): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.handleIntentInternal(CustomizationIntentService.java:142)
W/CustomizationIntentService( 1274): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.onHandleIntent(CustomizationIntentService.java:103)
W/CustomizationIntentService( 1274): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/CustomizationIntentService( 1274): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/CustomizationIntentService( 1274): 	at android.os.Looper.loop(Looper.java:157)
W/CustomizationIntentService( 1274): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/CustomizationIntentService( 1274): handleIntentInternal(): action = com.htc.intent.action.PRELOAD_CONTACTS, original action = android.intent.action.BOOT_COMPLETED, launched by: null
,W/CustomizationIntentService( 1274): AFH Enable: false, LEONCHAME: false
,I/ActivityManager(  908): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=2342 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
W/CustomizationIntentService( 1274): hasBeenInit true
W/CustomizationIntentService( 1274): isNewChameleonHFASupported false
W/CustomizationIntentService( 1274): isHFA true
W/CustomizationIntentService( 1274): setupWizRun 1
,D/DFPI.PIReciver( 2342): onReceiver action:android.intent.action.BOOT_COMPLETED
,D/DFPI    ( 2342): getInstance = com.htc.demoflopackageinstaller.ApkInstallHelper@41ad8d60
,D/DFPI    ( 2342): set install APK prefrence is false
,I/ActivityManager(  908): Delay finish: com.android.providers.downloads/.DownloadReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=2359 uid=10024 gids={50024, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=1989
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 1989:com.htc.zero:re_proc/u0a34 (adj 15): empty #17
,D/Process (  908): killProcessQuiet, pid=1890
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 1890:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
,D/FlexNetS( 1492): set2gLowSignalEnablePref: false
,V/FlexNetS( 1492): [DRX] setHigherPowerIn2GPref to: true
,D/FlexNetS( 1492): setSimCardisWhiteList: false
,V/FlexNetS( 1492): setSimCardCamp3GNetworkSignalPref to: false
,D/FlexNetS( 1492): setCampNetworkisBlackList: false
,V/FlexNetS( 1492): [DRX] setHigherPowerIn2GPref to: true
V/FlexNetS( 1492): setRilHandOverW2GEnable: 0
,D/HtcTelephonyManager( 1492): enablePS_W2G_Handover()
,I/ActivityManager(  908): Recipient 1989
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SystemUpdateService( 1201): receiver: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver (has extras) }
D/PMS     (  908): acquireWL(4284f690): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1201 10028 null
I/ActivityManager(  908): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
I/ActivityManager(  908): Recipient 1890
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SystemUpdateService( 1201): cancelUpdate (empty URL)
,I/SystemUpdateService( 1201): active receiver: disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1201, uid=10028, userID:0
,I/SystemUpdateService( 1201): cancelUpdate (empty URL)
,I/SystemUpdateService( 1201): active receiver: disabled
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1201, uid=10028, userID:0
I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): releaseWL(4284f690): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 null
I/AdsMeasurementBroadcastReceiver( 1201): Device was rebooted, starting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1201): Unauthorized to start the main service
,D/GCM     ( 1201): COMPAT: Multi user not supported
,D/GCM     ( 1345): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,V/AuthZen ( 1201): Handling intent: android.intent.action.BOOT_COMPLETED
D/PMS     (  908): releaseWL(42379940): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/AuthZen ( 1201): [DefaultAuthzenGcmReceiverDelegateService] Handling delegate intent.
,W/ActivityManager(  908): Unable to start service Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.fitness.service.BrokeredFitnessService (has extras) } U=0: not found
,I/GCoreUlr( 1201): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1424): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/PMS     (  908): acquireWL(426dd6f8): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1424 10028 null
,D/PMS     (  908): acquireWL(425b0568): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/PMS     (  908): releaseWL(425b0568): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/AuthZen ( 1201): Fetching signing key...
,I/AuthZen ( 1201): Signing key fetched successfuly!
,I/AuthZen ( 1201): No encryption key found or existing keys are expired for account thalitester@gmail.com
,I/GCoreUlr( 1424): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1424): Unknown pending intent to remove.
,I/GCoreUlr( 1424): Unbound from all location providers
D/PMS     (  908): acquireWL(42837008): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1424 10028 null
D/PMS     (  908): releaseWL(42837008): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  908): releaseWL(426dd6f8): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
,I/AuthZen ( 1201): Starting Enrollment...
,I/GoogleHttpClient( 1201): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1201): Using GMS GoogleHttpClient
,W/GLSActivity( 1201): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1201): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cryptauth
,E/AuthZen ( 1201): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 1201): atk: Failed to get a token for authzen enrollment
E/AuthZen ( 1201): 	at atj.a(SourceFile:122)
E/AuthZen ( 1201): 	at atm.a(SourceFile:158)
E/AuthZen ( 1201): 	at atm.a(SourceFile:83)
E/AuthZen ( 1201): 	at asv.a(SourceFile:93)
E/AuthZen ( 1201): 	at com.google.android.gms.auth.authzen.DefaultAuthzenGcmReceiverDelegateService.onHandleIntent(SourceFile:33)
E/AuthZen ( 1201): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1201): 	at android.os.Looper.loop(Looper.java:157)
E/AuthZen ( 1201): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2395 uid=10030 gids={50030}
,V/OneTimeInitializerReceiver( 2395): OneTimeInitializerReceiver.onReceive
,V/OneTimeService( 2395): OneTimeService.onHandleIntent
I/ActivityManager(  908): Delay finish: com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=2409 uid=10031 gids={50031, 3003, 5012}
,D/Process (  908): killProcessQuiet, pid=1854
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 1854:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.partnersetup, clsName=com.google.android.partnersetup.PhoneStateReceiver, state=1, flag=1, pid=2409, uid=10031, userID:0
,I/ActivityManager(  908): Delay finish: com.google.android.partnersetup/.GooglePartnerSetup
,I/ActivityManager(  908): Recipient 1854
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=2409, uid=10031, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=2409, uid=10031, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=2409, uid=10031, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=null, state=1, flag=0, pid=2409, uid=10031, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=2409, uid=10031, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=2409, uid=10031, userID:0
,D/PMS     (  908): acquireWL(4280fc68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
,D/PMS     (  908): releaseWL(4280fc68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  908): acquireWL(425857a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
,D/PMS     (  908): releaseWL(425857a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  908): acquireWL(42588c30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
,D/PMS     (  908): releaseWL(42588c30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  908): acquireWL(42589f40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
,D/PMS     (  908): releaseWL(42589f40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  908): acquireWL(428970c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
,D/PMS     (  908): releaseWL(428970c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  908): acquireWL(42729aa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
,D/PMS     (  908): releaseWL(42729aa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  908): acquireWL(4272cab8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
,D/PMS     (  908): releaseWL(4272cab8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/RlzPingService( 2409): Setting next ping for 1448386964311
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=2051
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2051:com.futuredial/u0a83 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2051
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=2436 uid=10033 gids={50033, 3003, 5012}
,D/Process (  908): killProcessQuiet, pid=1931
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=2448 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Killing 1931:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 1931
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Personalize.BootComple_( 2448): onReceive() + Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.home.personalize/.receiver.BootCompleteInitializer (has extras) }
,E/Personalize.BootComple_( 2448): action android.intent.action.BOOT_COMPLETED
,E/Personalize.Utilities( 2448): SimpleLauncher not found: com.htc.simplelauncher
,E/Personalize.BootComple_( 2448): initialize: false
,E/Personalize.Utilities( 2448): setApplicationEnabled IllegalArgumentException com.htc.simplelauncher
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.home.personalize, clsName=com.htc.home.personalize.SimpleModeEntryActivity, state=2, flag=1, pid=2448, uid=1000, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.simplelauncher, clsName=null, state=2, flag=0, pid=2448, uid=1000, userID:0
,I/ActivityManager(  908): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=2460 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  908): killProcessQuiet, pid=2065
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2065:com.htc.lucy/u0a62 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2065
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/BootCompletedReceiver( 2460): ensureAndExecuteUserProfiling: ensureAndExecuteUserProfiling 
,D/PeopleYouKnow( 2460): receive intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.contacts/.peopleyouknow.PeopleYouKnowReceiver (has extras) }
W/AccTypeManager( 2460): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 2460): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=2477 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,D/Process (  908): killProcessQuiet, pid=2083
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2083:com.android.settings/1000 (adj 15): empty #17
,D/AccTypeManager( 2460): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  908): Recipient 2083
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  908): Client connection lost with reason: 4
,V/HtcDataRoamingWidget.DisableWidgetReceiver( 2477): ACTION_BOOT_COMPLETED
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.dataroaming, clsName=com.htc.rosiewidgets.dataroaming.HtcSettingWidgetProvider, state=1, flag=1, pid=2477, uid=10042, userID:0
,V/HtcDataStripWidget.DisableWidgetReceiver( 2477): ACTION_BOOT_COMPLETED
,D/Process (  908): killProcessQuiet, pid=2103
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/DotMatrix( 1538): [EventReceiver] onReceive, version:1.3
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.datastrip, clsName=com.htc.rosiewidgets.datastrip.HtcSettingWidgetProvider, state=1, flag=1, pid=2477, uid=10042, userID:0
I/ActivityManager(  908): Killing 2103:com.htc.wifidisplay/u0a153 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2103
,E/ExternalAccountType( 2460): Unsupported attribute readOnly
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1110): [SystemUIService] onCreate(), version: 1.3
,I/ActivityManager(  908): Start proc com.htc.aurora for broadcast com.htc.aurora/.receiver.BootCompletedReceiver: pid=2489 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,W/dalvikvm( 1110): VFY: unable to resolve interface method 6812: Lcom/android/internal/telephony/ITelephony;.answerRingingCallForSubscriber (J)V
,W/dalvikvm( 1110): VFY: unable to resolve interface method 6824: Lcom/android/internal/telephony/ITelephony;.endCallForSubscriber (J)Z
W/AccTypeManager( 2460): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 2460): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 2460): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 2460): Unsupported attribute readOnly
,D/DotMatrix( 1110): [SystemUIService] EventService api version:1.3
,I/ActivityManager(  908): Start proc com.htc.aurora:remote for service com.htc.aurora/.download.DownloadService: pid=2503 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  908): Delay finish: com.htc.aurora/.receiver.BootCompletedReceiver
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.aurora, clsName=com.htc.aurora.download.DownloadReceiver, state=1, flag=1, pid=2503, uid=10047, userID:0
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=2519 uid=10050 gids={50050, 3003, 5012, 1028, 1015, 3002, 3001, 2001, 1023}
,D/Process (  908): killProcessQuiet, pid=1660
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.aurora, clsName=com.htc.aurora.download.DownloadReceiver, state=2, flag=1, pid=2503, uid=10047, userID:0
I/ActivityManager(  908): Killing 1660:com.google.android.gms.wearable/u0a28 (adj 15): empty #17
,D/Process (  908): killProcessQuiet, pid=1953
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 1953:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 1953
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MediaFocusControl(  908):   Remote Control   registerMediaButtonIntent() for PendingIntent{42414938: PendingIntentRecord{4226bf68 com.htc.music broadcastIntent}}
D/DotMatrix( 1538): [EventService] onClientChange, clearing: true
D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1538): [EventService] onClientChange, currEventType: 26
,D/DotMatrix( 1538): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  908): killProcessQuiet, pid=2255
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=2534 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
I/ActivityManager(  908): Killing 2255:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
I/ActivityManager(  908): Recipient 2255
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 1660
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=2547 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  908): killProcessQuiet, pid=2268
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2268:com.qualcomm.privinit/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2268
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 2547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 2547): call getInstance()
I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 2547): MY_DEBUG = false
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(423961f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41c0acf8: PendingIntentRecord{423b3fd0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1447782165444, Int=900000
,W/ContextImpl( 2547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncServiceReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncServiceReceiver
,D/SmartSyncUtils( 2547): getMobilePolicyEnabled, result = true
W/ContextImpl( 2547): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.startService:228 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.onHandleIntent:75 android.app.IntentService$ServiceHandler.handleMessage:65 
I/ActivityManager(  908): Resuming delayed broadcast
,W/ContextImpl( 2547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,W/ContextImpl( 2547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=2282
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2282:com.htc.calendar/u0a13 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1407): onHandleIntent, action: android.intent.action.BOOT_COMPLETED, data: null
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  908): Recipient 2282
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Bundle  ( 1407): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1407): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1407): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1407): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1407): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1407): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1407): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1407): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1407): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1407): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1407): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1407): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/FeatureList( 1407): feature
D/FeatureList( 1407): type
,D/FeatureList( 1407): description
,W/Bundle  ( 1407): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1407): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1407): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1407): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1407): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1407): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1407): Attempt to cast generated internal exception:
W/Bundle  ( 1407): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1407): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PluginProvider( 1407): Begin Apply Batch
,E/PluginProvider( 1407): conflict when insert feature, ignored
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  908): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  908): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 0
W/Settings:Agent(  908): >> traceCallingStack()
W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1444
,W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
W/Settings:Agent(  908): 
W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  908): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  908): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  908): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  908): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  908): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  908): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  908): 
,W/Settings:Agent(  908): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  908): Message: MESSAGE_DISABLE
,D/WifiManager( 2209): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  908): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 0
W/Settings:Agent(  908): >> traceCallingStack()
W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1161
W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
W/Settings:Agent(  908): 
,W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  908): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  908): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  908): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  908): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
,W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  908): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  908): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  908): 
,W/Settings:Agent(  908): << traceCallingStack(): 1(ms)
,I/jxcore-log( 2209): ****TEST TOOK:  5036  ms ****
I/jxcore-log( 2209): 
D/WifiService(  908): setWifiEnabled: false pid=2209, uid=10355
E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  908): isSprintWifiRestricted(): false
I/WifiService(  908): isMdmWifiRestricted(): false
D/WifiSettingsStore(  908): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  908): New client listening to asynchronous messages,
I/jxcore-log( 2209): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2209): 
,D/PluginProvider( 1407): apply Batch success
,I/[PluginManager]RegisterService( 1407): Notify Carousel that a new TabPlugin has been installed!
,I/ActivityManager(  908): Resuming delayed broadcast
,I/WSP     ( 1407): [Receiver] EVENT - BOOT COMPLETED, is settings existed? true
,D/AutoSetting( 1407): receiver - intent: android.intent.action.BOOT_COMPLETED
,D/HtcAppUPService( 1407): CustomizationReceiver  receieve: android.intent.action.BOOT_COMPLETED
,D/AutoSetting( 1407): service - onStartCommand() action: com.htc.app.autosetting.bootcomplete
D/AutoSetting( 1407): service - onStartCommand() boot completed, remove cache
D/AutoSetting( 1407): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1407): service - handleMessage() setting current location null
D/AutoSetting( 1407): service - handleMessage() removing cache
,D/AutoSetting( 1407): service - AddressCache: clean up all cache
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.upservice.HtcUPServiceReceiver
,D/HtcAppUPService( 1407): HtcUPService onCreate()
,D/HtcAppUPService( 1407): DatabaseHelper [DatabaseHelper constructor]
,D/HtcAppUPService( 1407): PolicyStore [Init] Get cached policy bundle
,D/HtcAppUPService( 1407): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.BOOT_COMPLETED cmp=com.htc.sense.hsp/.upservice.HtcUPService }, this = com.htc.sense.hsp.upservice.HtcUPService@420a2e80
,D/HtcAppUPService( 1407): HtcUPServicePreference Is policy store first run: false
,D/HtcAppUPService( 1407): appid: tellhtc_client, category: usage_report, key: enable, value: 1, due date: -1, current time: 1447782166574, default value: null
,D/HtcAppUPService( 1407): HtcUPServicePreference Upload schedule enable? false
,W/dalvikvm( 1407): VFY: unable to resolve static field 680 (common_google_play_services_unknown_issue) in Lcom/google/android/gms/R$string;
,E/GooglePlayServicesUtil( 1407): The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,E/dalvikvm( 1407): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 1407): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 1407): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 1407): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
V/JNIHelp ( 1407): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ProviderInstaller( 1407): Installed default security provider GmsCore_OpenSSL
,D/HtcAppUPService( 1407): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.BOOT_COMPLETED
,D/HtcAppUPService( 1407): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
,D/HtcAppUPService( 1407): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@420a2e80
I/ActivityManager(  908): Resuming delayed broadcast
,D/HtcAppUPService( 1407): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
D/Process (  908): killProcessQuiet, pid=2315
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=2576 uid=10055 gids={50055, 1028, 1015, 3003, 5012, 3001, 3002}
I/ActivityManager(  908): Killing 2315:com.google.android.configupdater/u0a16 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2315
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/BootReceiver( 2576): onReceive: android.intent.action.BOOT_COMPLETED
,D/BootReceiver( 2576): boot completed:
,D/BootReceiver( 2576): isValid:  isEnabledEasyAccess = false, isEnabledQuickDial = false
,I/ActivityManager(  908): Start proc com.htc.video for broadcast com.htc.video/com.htc.videowidget.videoDMC.DLNAReceiver: pid=2588 uid=10056 gids={50056, 2001, 3002, 3003, 5012, 1028, 1015, 1023}
,D/Process (  908): killProcessQuiet, pid=2342
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/cutils-trace( 2568): Error opening trace file: No such file or directory (2)
I/ActivityManager(  908): Killing 2342:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 2342
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{4251b7f8 u0 com.google.android.gms/.gcm.GcmService}
,D/Process (  908): killProcessQuiet, pid=2294
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  908): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=2610 uid=10059 gids={50059, 1028, 1015, 3003, 5012, 1023}
I/ActivityManager(  908): Killing 2294:android.process.media/u0a21 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2294
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/LMW     ( 2610): [2623][ActionDeviceStorageHandler] onActionBootComplete++
,W/LMW     ( 2610): [2623][ActionDeviceStorageHandler] onActionBootComplete--
,I/ActivityManager(  908): Start proc android.process.media for broadcast com.android.providers.media/.MediaScannerReceiver: pid=2624 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
,D/Process (  908): killProcessQuiet, pid=2359
,I/ActivityManager(  908): Killing 2359:com.htc.fm/u0a24 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 2359
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DownloadManager( 2624): Enable ItsOn feature: false
,D/CustomizationManager( 2568): ====startRecUseTime====
D/htc.customization.log.level( 2568):  is 
,W/CustomizationLogLevel( 2568): Level value is invalid, use default level 2
,D/MediaProvider( 2624): [onCreate]+ 
D/MediaProvider( 2624): [attachVolume] attach internal db
D/MediaProvider( 2624): [DatabaseHelper] version:705, internal:true
,V/MediaProvider( 2624): Attached volume: internal
,D/MediaProvider( 2624): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
D/MediaProvider( 2624): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 2624): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 2624): [MP][DEBUG] Storage State: removed
D/MediaProvider( 2624): [MP][DEBUG] Sorting: order:2, path:/storage/usb
,D/MediaProvider( 2624): [MP][DEBUG] Storage State: removed
D/MediaProvider( 2624): [onCreate] External Storage State = mounted
D/MediaProvider( 2624): [DatabaseHelper] version:705, internal:false
,D/MediaProvider( 2624): [attachVolume] volumeID=11223344,dbName=external-ab4130.db
,V/MediaProvider( 2624): Attached volume: external
,D/MediaProvider( 2624): [onCreate]-
,D/MediaScannerReceiver( 2624): onReceive Intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.media/.MediaScannerReceiver (has extras) }
,D/MediaProviderUtils( 2624): [scanEx]volume:internal,action:android.intent.action.BOOT_COMPLETED
,D/MediaProviderUtils( 2624): [scanEx]volume:customize,action:android.intent.action.BOOT_COMPLETED
,D/MediaProviderUtils( 2624): [scanEx]volume:external,action:android.intent.action.MEDIA_MOUNTED
,D/MediaProviderUtils( 2624): [scanEx]volume:external,action:android.intent.action.MEDIA_MOUNTED
,D/MediaProviderUtils( 2624): [scanEx]volume:external,action:android.intent.action.MEDIA_MOUNTED
I/ActivityManager(  908): Delay finish: com.android.providers.media/.MediaScannerReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
D/MediaProvider( 2624): [writeUserBehaviorLog] +
,D/MediaProvider( 2624): [writeUserBehaviorLog] -
,D/CustomizationManager( 2568):  Read ACC file spent 0.061 (s)
D/CIDMapFileReader( 2568): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 2568): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2568): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2568): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2568): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2568): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2568): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2568): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2568): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 2568): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 2568): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 2568): Parsing tag category name = system
,I/CustomizationCIDLoader( 2568): Parsing tag category name = application
I/CustomizationCIDLoader( 2568): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2568): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2568): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 2568): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2568): Parsing tag category name = Settings
,D/CustomizationManager( 2568):  Read CID file spent 0.100 (s)
,D/CustomizationManager( 2568):  All configurations done spent 0.100 (s),
W/HtcNativeFlag( 2568): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2568): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2568): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 2568): Fail to get flag for type 'language', use default value: -1,
,D/MediaScannerServiceEx( 2624): [ServiceHandler][handleMessage]+internal
,D/MediaScannerServiceEx( 2624): [3] stop task - current task is null
D/MediaScannerServiceEx( 2624): [4] stop task - current task is null
,D/MediaScannerServiceEx( 2624): [5] stop task - current task is null
,D/MtpReceiver( 2624): [MTP][MtpReceiver][onReceive]+
,D/MtpReceiver( 2624): [MP][DEBUG][MtpReceiver] requestFullScanForMTP
,D/MtpReceiver( 2624): [MP][DEBUG][MtpReceiver] requestFullScanForMTP dir = /storage/emulated/0
D/PMS     (  908): acquireWL(426e8810): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2624 10021 null
,D/PackageManager(  908): deletePackageAsUser: pkg=com.example.hello, pid=2568, uid=2000 user=0
D/MtpReceiver( 2624): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2624): [MTP][handleMessage][startService]
,D/MtpReceiver( 2624): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MediaProvider( 2624): bindService() MTP Service Connection.
,D/MtpReceiver( 2624): [MTP][handleMessage]-
I/ActivityManager(  908): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=2646 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  908): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,D/Process (  908): killProcessQuiet, pid=2209
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/asset   (  908): Copying FileAsset 0x67aaf948 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  908): Killing 2209:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  908): Force removing ActivityRecord{428414a0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  908): Skipping PackageSetting{4229b4a8 com.test.thalitest/10348} due to missing metadata
,D/MediaScannerServiceEx( 2624): getDefaultLocale =en_GB
D/MediaScannerServiceEx( 2624): [scan]+internal,/system/media
,D/MediaScanner( 2624): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
I/ActivityManager(  908): Force stopping com.example.hello appid=10355 user=0: pkg removed
,W/InputDispatcher(  908): channel '4283f340 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  908): channel '4283f340 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
,W/InputDispatcher(  908): Attempted to unregister already unregistered input channel '4283f340 com.example.hello.MainActivity (s)'
I/WindowState(  908): WIN DEATH: Window{4283f340 u0 com.example.hello/com.example.hello.MainActivity}
,D/MtpService( 2624): updating state; isCurrentUser=true, mMtpLocked=false
I/acms    ( 1766): Unregistering com.example.hello
D/DotMatrix( 1538): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1538): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1538): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
E/acms    ( 1766): Could not unregister removed application com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.example.hello
I/FeedHostManager( 1250): [onResume]
I/FeedProviderManager( 1250): onResume
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
I/SocialFeedProvider( 1250): +onResume
I/SocialFeedProvider( 1250): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1250): -onResume
,I/ConnectivityHelper( 1250): [getCurrentConnectionType] no network connection
,W/GeofencerStateMachine( 1424): Ignoring removeGeofence because network location is disabled.
I/WindowManager(  908): WINDOW DIED Window{4283f340 u0 com.example.hello/com.example.hello.MainActivity}
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.launcher (1250/10075)
D/PMS     (  908): acquireWL(42776058): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
,W/SystemReader( 1234): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/MtpService( 2624): addStorageInternal without MtpServer
,D/MtpService( 2624): [MTP][onCreate]-
,D/MessageFrequencyProvider( 2646): onCreate
,D/MtpService( 2624): [MTP] startForeground
,D/PMS     (  908): releaseWL(42776058): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
V/GetPrviateResource( 2646): GetPrviateResource
V/GetPrviateResource( 2646): GetPrviateResource
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
,D/MtpService( 2624): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 2624): TotalSize=1918604,MediaCacheLimit=6000
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,W/AccTypeManager( 2460): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 2460): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/AccTypeManager( 1308): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1308): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/MtpService( 2624): starting MTP server in MTP mode
,D/MtpService( 2624): addStorageInternal 65537 /storage/emulated/0
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,D/MtpService( 2624): [checkStorageState] Storage state - mounted
,D/MtpService( 2624): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
W/Parcel  ( 1234): Reading a NULL string not supported here.
,D/AccTypeManager( 1308): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,D/MessageCustFlag( 2646): sense_version=6.0
,D/BTAccessoryUtil( 2646): createReceiver
,D/BTAccessoryUtil( 2646): registerReceiver return intent = null
D/MessageCustFlag( 2646): sku_id=99
,W/SystemReader( 2646): Cannot find message_ambs_application_id, use default value instead
,D/AccTypeManager( 2460): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
,D/Messaging( 2646): supportCMAS(SIE)/init? false/true
D/MmsConfig( 2646): networkCode: 
D/MessageCustFlag( 2646): sku_id=99
D/MmsConfig( 2646): SIE smsPri: null
,D/MmsConfig( 2646): networkCode: 
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,D/HtcTelephonyCapability( 2646): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 2646): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 2646): getRATByHtcTelephonyCapability:1
,W/SystemReader( 2646): Cannot find qct_8960_interface, use default value instead
,V/MmsSystemEventReceiver( 2646): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/MediaScanner( 2624):  prescan time: 235ms
D/MediaScanner( 2624):     scan time: 39ms
D/MediaScanner( 2624): postscan time: 0ms
D/MediaScanner( 2624):    total time: 274ms
D/MediaScanner( 2624): -----------------------------------------------------------------
D/MediaScanner( 2624): firstscan(media) time: 24ms
D/MediaScanner( 2624): secondscan(non-media) time: 6ms
D/MediaScanner( 2624):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2624):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2624):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2624):  [Total]    File(Image+Video+Audio+Others) in database : 366
,D/MediaScannerServiceEx( 2624): [scan]-
,E/ExternalAccountType( 1308): Unsupported attribute readOnly
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,D/ExchangePolicystatus( 2646): onReceive()
,D/ExchangePolicystatus( 2646): onReceive(): ACTION_BOOT_COMPLETED
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
D/MessageUtils( 2646): Text messaging allow status = allow
,D/Messaging( 2646): EAS allow SMS !!!
,D/MediaProvider( 2624): [delete][31]
,D/MediaProvider( 2624): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
D/MediaProvider( 2624): [recoverParentNodes] - 0
D/MediaProvider( 2624): [update][3]
D/MediaScannerServiceEx( 2624): [scan] Recover Parent Node is finished!
,D/PhoneApp( 1223): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/ExchangePolicystatus( 2646): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
,D/Messaging( 2646): EAS allow SMS !!!
D/PMS     (  908): acquireWL(4234cc60): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 2646 10064 null
,D/TAG     ( 2624): mWakeLock.release() at scan()
,D/MediaScannerServiceEx( 2624): [ServiceHandler][handleMessage]+customize
D/PMS     (  908): releaseWL(426e8810): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
I/ActivityManager(  908): Delay finish: com.htc.sense.mms/.PolicyReceiver
,D/PMS     (  908): acquireWL(42578ae8): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2624 10021 null
V/SmsReceiverService( 2646): onStart: #1, @1102234736
V/SmsReceiverService( 2646): action: android.intent.action.BOOT_COMPLETED
D/SmsReceiverService( 2646): isCbm: false
D/SmsReceiverService( 2646): isDiscard: false
D/SettingsManager( 2646): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41ad5fe8
,E/ExternalAccountType( 2460): Unsupported attribute readOnly
,V/SmsReceiverService( 2646): handleBootCompleted
,D/MediaScannerServiceEx( 2624): getDefaultLocale =en_GB
D/MediaScannerServiceEx( 2624): [scan]+internal,/system/customize/resource
,D/MediaScanner( 2624): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
,D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1223): sku_id=99
,D/SmsReceiverService( 2646): OutBoxSize = 0
D/SmsReceiverService( 2646): sendFirstQueuedMessage start: 0
,D/MessageCustFlag( 2646): sku_id=99
,D/MediaScanner( 2624):  prescan time: 28ms
D/MediaScanner( 2624):     scan time: 19ms
D/MediaScanner( 2624): postscan time: 0ms
D/MediaScanner( 2624):    total time: 47ms
D/MediaScanner( 2624): -----------------------------------------------------------------
D/MediaScanner( 2624): firstscan(media) time: 9ms
D/MediaScanner( 2624): secondscan(non-media) time: 10ms
D/MediaScanner( 2624):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2624):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2624):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2624):  [Total]    File(Image+Video+Audio+Others) in database : 366
,D/MediaScannerServiceEx( 2624): [scan]-
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,D/MediaProvider( 2624): [delete][18]
,D/MediaProvider( 2624): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 56
,D/AccFlag ( 1223): sku_id=99
D/MediaProvider( 2624): [recoverParentNodes] - 0
D/MediaProvider( 2624): [update][7]
D/MediaScannerServiceEx( 2624): [scan] Recover Parent Node is finished!
D/TAG     ( 2624): mWakeLock.release() at scan()
D/MediaScannerServiceEx( 2624): [ServiceHandler][handleMessage]+external
D/MediaScannerServiceEx( 2624): [ServiceHandler][handleMessage] volume: external, action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 2624): ignoreDirectories[ 0 ] = /storage/ext_sd
D/MediaScannerServiceEx( 2624): ignoreDirectories[ 1 ] = /storage/usb
D/PMS     (  908): releaseWL(42578ae8): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/SmsReceiverService( 2646): sendFirstQueuedMessage end cnt> 0
D/SpaceBufferUtil( 2646): > createBufferFile()
D/SpaceBufferUtil( 2646): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
,D/SpaceBufferUtil( 2646): < createBufferFile()
,D/MediaScannerServiceEx( 2624): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 2624): [update][7]#0#
,D/MediaProvider( 2624): [update][3]#0#
D/MediaProvider( 2624): [update][3]#0#
,D/MediaScannerServiceEx( 2624): [deleteRowsEqualVolid]+65537
D/MediaProvider( 2624): [delete][4]#0#
,D/MediaScannerServiceEx( 2624): [deleteRowsEqualVolid]-0
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/MediaProvider( 2624): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
,D/MtpService( 2624): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 2624): [update][17]#1#
,D/MediaScannerServiceEx( 2624): [AliveExtStorageRows]-0, 0, 0
,D/MediaScannerServiceEx( 2624): [deleteNonUseAlbumArts]+
,D/MediaScannerServiceEx( 2624): [deleteNonUseAlbumArts]-
,D/MediaScannerServiceEx( 2624): [ServiceHandler][handleMessage][EXTERNAL]-android.intent.action.MEDIA_MOUNTED,[Ljava.lang.String;@41c91458
,E/MediaProvider( 2624): no database for attached volume content://media/external
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 2209 uid 10355
D/PMS     (  908): acquireWL(424af7a0): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2624 10021 null
I/InputMethodManagerService(  908): Enable input method client, pid=1250
,D/MediaScannerServiceEx( 2624): getDefaultLocale =en_GB
,D/MediaScannerServiceEx( 2624): [scan]+external,/storage/emulated/0
D/MediaScanner( 2624): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
D/MediaScanner( 2624): Ignore scan directories /storage/ext_sd
D/MediaScanner( 2624): Ignore scan directories /storage/usb
,D/MediaScanner( 2624): Ignore scan directories null
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{425419e0 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.PolicyReceiver: pid=2676 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
,W/PackageManager(  908): Unable to load service info ResolveInfo{42081670 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
,D/MyReportAgent( 2676): ReportService [##] onCreate(), this = com.htc.reportagent.ReportService@41ad7888
,D/MyReportAgent( 2676): ReportService [##] onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.reportagent.action.BOOT_COMPLETE cmp=com.htc.reportagent/.ReportService }, this = com.htc.reportagent.ReportService@41ad7888
,D/MyReportAgent( 2676): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE
I/ActivityManager(  908): Delay finish: com.htc.reportagent/.receiver.PolicyReceiver
,D/UPolicy ( 2676): IUserBehaviorLoggingService reference is gotten !
,D/MyReportAgent( 2676): ReportServiceHandler on boot complete event 
,I/HtcModeClient( 1492): handler message = 4011
,E/HtcModeClient( 1492): Check connection and retry 3 times.
,V/MyReportAgent( 2676): ReportServiceHandler register the PowerConnected Listener
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.reportagent, clsName=com.htc.reportagent.receiver.PowerConnectedReceiver, state=1, flag=1, pid=2676, uid=10065, userID:0
,D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  908): start
,D/DotMatrix( 1538): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,I/RemoteViews( 1110): com.android.providers.media (false,0)
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41b17a40 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.android.providers.media 2 10 0 10
,I/RemoteViews( 1110): com.android.providers.media (false,0)
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41b17ce8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.android.providers.media 0 9 1 15
,W/AtomicFile(  908): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  908): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,V/AlarmManager(  908): sending alarm PendingIntent{424cfb38: PendingIntentRecord{426e7ea0 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=44242, Int=0

```
