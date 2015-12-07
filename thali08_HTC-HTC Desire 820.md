#### Test 50242285e707819_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
W/PackageManager(  906): Unable to load service info ResolveInfo{431528f8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@424bb060 +
I/Prism.WidgetManager( 1247): onLoadItems() +
D/ContactMessageStore( 1220): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1220): MSG_NOTIFY_CS_TO_SYNC <<
E/cutils-trace( 3079): Error opening trace file: No such file or directory (2)
W/asset   ( 1247): Copying FileAsset 0x680bc948 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
E/Prism.WidgetManager( 1247): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1247): onLoadItems() -
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@424bb060 -
D/CustomizationManager( 3079): ====startRecUseTime====
D/htc.customization.log.level( 3079):  is 
W/CustomizationLogLevel( 3079): Level value is invalid, use default level 2
I/GAV2    ( 2822): Thread[GAThread,5,main]: No campaign data found.
D/CustomizationManager( 3079):  Read ACC file spent 0.077 (s)
D/CIDMapFileReader( 3079): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3079): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3079): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3079): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3079): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3079): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3079): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3079): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3079): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3079): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3079): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3079): Parsing tag category name = system
I/CustomizationCIDLoader( 3079): Parsing tag category name = application
I/CustomizationCIDLoader( 3079): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3079): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3079): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3079): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3079): Parsing tag category name = Settings
D/CustomizationManager( 3079):  Read CID file spent 0.131 (s)
D/CustomizationManager( 3079):  All configurations done spent 0.131 (s)
W/HtcNativeFlag( 3079): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3079): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3079): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3079): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
D/PMS     (  906): acquireHCC(42f37470): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3079
D/PMS     (  906): acquireHCC(430e3950): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6744aef0 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1125387840
D/PMS     (  906): acquireWL(42f46020): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
D/PhoneApp( 1220): EVENT_QUERY_MO_PACKAGES
I/FeedHostManager( 1247): [onPause]
I/FeedProviderManager( 1247): onPause
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42988fa8
D/PhoneApp( 1220): -- N1 =0
D/PhoneApp( 1220): -- N2 =0
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
D/PhoneApp( 1220): -- N3 =0
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3092 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
D/GCM     ( 1347): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/WeatherUtility( 1109): can't get weather sync account
W/asset   ( 3092): Copying FileAsset 0x5c7cdc80 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/WeatherRequest( 1109): request cur loc, but there is no sys cur
I/TrimMemoryManager( 1247): [trimMemory] 20
I/ActivityManager(  906): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3106 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
V/WebViewChromiumFactoryProvider( 3092): Binding Chromium to main looper Looper (main, tid 1) {42423d08}
I/LibraryLoader( 3092): Expected native library version number "",actual native library version number ""
I/chromium( 3092): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3092): Initializing chromium process, renderers=0
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/PMS     (  906): acquireWL(430e2da8): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  906): acquireWL(4303d050): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42998528:true
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3092): 1111739568: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  906): releaseWL(430e2da8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/HtcModeClient( 1477): handler message = 4011
E/HtcModeClient( 1477): Check connection and retry 5 times.
I/Adreno-EGL( 3092): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3092): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3092): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3092): Local Branch: 
I/Adreno-EGL( 3092): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3092): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3092):                  aa63bbd948f41d15fc72f585e
D/browser ( 3106): Browser versionCode = 760001523 versionName = 7.0.2512153020
W/SWE_UI  ( 3106): SWE using SurfaceView - Multi-Process
W/chromium( 3092): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/LibraryLoader( 3106): Loading: swewebviewchromium
W/dalvikvm( 3092): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3092): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3092): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3092): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3092): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3092): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3092): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3092): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3092): CordovaWebView is running on device made by: HTC
I/LibraryLoader( 3106): Time to load native libraries: 34 ms (timestamps 7881-7915)
I/LibraryLoader( 3106): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3106): Initializing chromium process, renderers=9
I/LibraryLoader( 3106): Expected native library version number "",actual native library version number ""
I/chromium( 3106): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,W/AwContents( 3092): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Disable input method client, pid=1247
W/ResourceType( 3092): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3092): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@4246e038, mServedView=org.apache.cordova.engine.SystemWebView{42433fd0 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  906): Enable input method client, pid=3092
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3092): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +271ms
D/PMS     (  906): releaseWL(42f46020): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/chromium( 3106): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
I/chromium( 3092): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3092): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/Adreno-EGL( 3106): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3106): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3106): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3106): Local Branch: 
I/Adreno-EGL( 3106): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3106): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3106):                  aa63bbd948f41d15fc72f585e
D/Process (  906): killProcessQuiet, pid=2790
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
V/IccIntentReceiver( 1277): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1477): SIM state: ABSENT
I/SIMStateChangeReceiver( 1477): phoneType = 0
I/SIMStateChangeReceiver( 1477): remove notification
I/ActivityManager(  906): Killing 2790:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2790
D/JsMessageQueue( 3092): Set native->JS mode to OnlineEventsBridgeMode
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3175 uid=10031 gids={50031, 3003, 5012}
I/ActivityManager(  906): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3187 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
D/Process (  906): killProcessQuiet, pid=2822
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2822:com.google.android.gm/u0a107 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2822
D/jxcore_app_log( 3092): JniHelper::setJavaVM(0x41fe7010), pthread_self() = 1658760184
D/JX-Cordova( 3092): jxcore cordova android initializing
I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3198 uid=10091 gids={50091, 3003, 5012}
V/AlarmManager(  906): sending alarm PendingIntent{42cd6510: PendingIntentRecord{42e33400 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=53722, Int=0
W/SystemReader( 2561): Cannot find message_ambs_application_id, use default value instead
D/SmsReceiver( 2561): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2561): onReceive()
D/ExchangePolicystatus( 2561): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2561): onReceive(): else
D/Process (  906): killProcessQuiet, pid=2859
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/HtcBroadcastReceiver( 1220): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  906): Killing 2859:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3216 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  906): Recipient 2859
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3230 uid=10091 gids={50091, 3003, 5012}
W/jxcore-log( 3092): Initializing JXcore engine
W/jxcore-log( 3092): JXcore engine is ready
W/jxcore-log( 3092): Starting JXcore engine
W/AccTypeManager( 3187): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3187): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/CalendarApplication( 3216): onCreate
D/ProviderChangeReceiver( 3216): ---------------------------------------------------
D/ProviderChangeReceiver( 3216): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3216): start to updateAlertNotification!
W/ContextImpl( 2958): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/AccTypeManager( 3187): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3248 uid=10038 gids={50038}
D/AlertService( 3216): No fired or scheduled alerts
D/HtcAlertUtils( 3216): -- cancelReminderNotification --
D/HtcAlertUtils( 3216): broadcastExistReminder!
D/DotMatrix( 1535): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/Process (  906): killProcessQuiet, pid=2805
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2805:com.htc.cs.dm/u0a98 (adj 15): empty #17
E/ExternalAccountType( 3187): Unsupported attribute readOnly
W/jxcore-log( 3092): Platform android
W/jxcore-log( 3092): 
W/jxcore-log( 3092): Process ARCH arm
W/jxcore-log( 3092): 
D/MdScBoot( 3198): [b50.1.] 30@-153528 -> 40@-153558
D/Process (  906): killProcessQuiet, pid=2882
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/Process (  906): killProcessQuiet, pid=2209
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2882:com.google.android.talk/u0a111 (adj 15): empty #17
I/ActivityManager(  906): Killing 2209:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2209
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AccTypeManager( 3187): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3187): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/Process (  906): killProcessQuiet, pid=2914
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3261 uid=10077 gids={50077}
I/ActivityManager(  906): Killing 2914:com.htc.backupreset/1000 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/jxcore-log( 3092): JXcore Cordova bridge is ready!
I/jxcore-log( 3092): 
W/jxcore-log( 3092): JXcore engine is started
D/AccTypeManager( 3187): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  906): Recipient 2914
E/ExternalAccountType( 3187): Unsupported attribute readOnly
D/SMSBackup( 3261): Got a database change event
D/Process (  906): killProcessQuiet, pid=2929
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/AdsMeasurementBroadcastReceiver( 1200): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1200): Unauthorized to start the main service
I/ActivityManager(  906): Killing 2929:com.htc.htccupd/u0a17 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2929
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3273 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
E/jxcore-log( 3092): >> HTC-HTC Desire 820
E/jxcore-log( 3092): 
I/jxcore-log( 3092): Total memory 1964650496
I/jxcore-log( 3092): 
I/jxcore-log( 3092): Free memory 725086208
I/jxcore-log( 3092): 
I/jxcore-log( 3092): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3092): 
I/jxcore-log( 3092): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3092): 
I/jxcore-log( 3092): userPath [ 'www' ]
I/jxcore-log( 3092): 
I/jxcore-log( 3092): Size 720 1184
I/jxcore-log( 3092): 
I/jxcore-log( 3092): Screen Brightness 10
I/jxcore-log( 3092): 
E/jxcore-log( 3092): Dummy Error Log.
E/jxcore-log( 3092): 
I/ActivityManager(  906): Recipient 2805
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2882
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/AdsMeasurementBroadcastReceiver( 1200): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1200): Unauthorized to start the main service
I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3288 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3273): can't get weather sync account
I/DemoRecovery.RestoreReceiver( 3288): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/ContextImpl( 3288): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/RestoreService( 3288): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3302 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=2944
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2944:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WeatherRequest( 3273): request cur loc, but there is no sys cur
W/Settings( 3273): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  906): Recipient 2944
D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 0 6 17
D/PMS     (  906): acquireWL(42bf9f48): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3302 10070 null
D/PMS     (  906): acquireWL(42be48c8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3302 10070 null
D/PMS     (  906): releaseWL(42bf9f48): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 3302): update TASK shortcut>
I/TodoTaskNotifyService( 3302): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1535): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): releaseWL(42be48c8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 3302): stopSelfResult true
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3317 uid=10081 gids={50081, 3003, 5012}
D/Process (  906): killProcessQuiet, pid=2971
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2971:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2971
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3329 uid=10081 gids={50081, 3003, 5012}
D/Process (  906): killProcessQuiet, pid=2998
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 2998:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2998
D/SMSBackup( 3261): Got a database change event
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3342 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
D/Process (  906): killProcessQuiet, pid=3012
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3012:com.android.smith/u0a163 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3012
I/ImageRamCache( 3342): create image Cache, size: 31457280.
I/ImageRamCache( 3342): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3342): create image Cache, size: 12582912.
I/FeedSettings( 3342): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3342): GroupBudget 0.500000 0.380000
I/FeedSettings( 3342): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 3342): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 3342): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3342): loadGridSize() with Alternative
D/CustomHighlightReceiver( 3342): [custom highlight] onReceive
D/CustomHighlightService( 3342): [custom highlight] onHandleIntent
I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/NewsDB  ( 3342): set custom highlight []
D/CustomHighlightService( 3342): [custom highlight] set tags 
D/Process (  906): killProcessQuiet, pid=3024
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/GCM     ( 1347): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3024:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/MessagingShortcutReceiver( 2561): keep hiding shortcut bubble
D/MessagingShortcut( 2561): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2561): After query: 0
D/MessagingShortcut( 2561): mPresentUnreadCount: -1
D/MessagingShortcut( 2561): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2561): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1535): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1535): [EventService] reorderNotification, total:0
D/DotMatrix( 1535): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1535): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 3302): update TASK shortcut>
D/HtcBroadcastReceiver( 1220): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
D/MdScBoot( 3198): [c8.1.] 40@-153558
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3360 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/ActivityManager(  906): Recipient 3024
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.youtube (pid 3024): Died!
I/Babel   ( 3360): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3360): MmsConfig.loadMmsSettings
E/dalvikvm( 3360): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 3360): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 3360): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 3360): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
V/JNIHelp ( 3360): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
D/MmsCustomizationProvider( 2561): query uri: content://htc-mms-customization/mms-ua/ua_string
D/MmsCustomizationProvider( 2561): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3360): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 3360): MmsConfig.loadFromDatabase
I/jxcore-log( 3092): getBuffer is called!!!!
I/jxcore-log( 3092): 
E/Babel   ( 3360): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3360): MmsConfig.loadFromResources
E/Babel   ( 3360): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3360): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3360, uid=10111, userID:0
W/Settings( 3360): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3360, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3360, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3360, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3360, uid=10111, userID:0
D/MessagingNotification( 2561): New incoming message, can't cancel notification now
D/Process (  906): killProcessQuiet, pid=2983
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/MessagingNotification( 2561): newMsgCnt: 0, false
D/GCM     ( 1347): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3360, uid=10111, userID:0
I/ActivityManager(  906): Killing 2983:com.android.settings/1000 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2983
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1759/10178)
D/MtpReceiver( 2237): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2237): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2237): [MTP][handleMessage][startService]
D/MtpReceiver( 2237): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2237): [MTP][handleMessage]-
D/MtpService( 2237): [MTP] startForeground
I/RemoteViews( 1109): com.android.providers.media (false,0)
D/DotMatrix( 1535): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3386 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
I/RemoteViews.Performance( 1109): com.android.providers.media 2 1 10
I/RemoteViews( 1109): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1109): com.android.providers.media 1 1 15
D/MtpService( 2237): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2237): TotalSize=1918604,MediaCacheLimit=6000
D/MtpService( 2237): [isMtpConnected] connected: true
I/ProviderInstaller( 3360): Installed default security provider GmsCore_OpenSSL
D/SyncApplication( 3386): Loading default preferences
W/Resources( 3386): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/WifiService(  906): New client listening to asynchronous messages
D/SyncApplication( 3386): Overriding preferences with custom values
D/SyncApplication( 3386): Updating preferences succeeded
E/SyncApplication( 3386): Application created.
D/VolumeInfo( 3386): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3386): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3386): Found 0 mount point(s)
V/VolumeInfo( 3386): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 3386): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 3386): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 3386): Can not create volume ID for unmounted volume null
I/CalendarDefines( 3386): getNewCalendarAuthority()...
D/SyncApplication( 3386): enableAppOperation()+
D/SyncApplication( 3386): enableAppOperation()-
D/HTCUtilities( 3386): isNeorSinged() + 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3386, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3386, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3386): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 3386): isNeorSinged() return false
D/CDMountReceiver( 3386): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3386): USB connected to PC
D/FOTAReceiver( 3386): onReceive() enter 
D/FOTAReceiver( 3386): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3405 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  906): killProcessQuiet, pid=3106
I/ActivityManager(  906): Killing 3106:com.htc.sense.browser/u0a12 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/HtcFingerPrintQuickLaunchProvider( 3405): -onCreate()
V/Settings:HtcSettingsApplication( 3405): [3405/3405] onCreate()
D/TetherSettings( 3405): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3405): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3405): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3405): Cust_ConnectToPC   : spcsc>false
D/        ( 3405): Cust_ConnectToPC   : IPT>true
D/        ( 3405): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3405): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3405): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3405): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3405): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3405): Cust_ConnectToPC   : spcsc>false
D/        ( 3405): Cust_ConnectToPC   : IPT>true
D/        ( 3405): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3405): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3405): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3405): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3405): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3405): usb_cable_connect = 1
D/SmartNS_Utility( 3405): usb_denied = 0
I/SmartNS_NSReceiver( 3405): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3405): USB = true hasTethered = false isNSOpening: false
I/ActivityManager(  906): Recipient 3106
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PSReceiver( 3405): onReceive:com.htc.intent.action.USB_CONNECT2PC
I/SmartNS_PSService( 3405): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3405): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3405):  defaultType:0
I/SmartNS_PSService( 3405): fail notificaiton:false
D/SmartNS_Utility( 3405): usb_cable_connect = 1
D/SmartNS_Utility( 3405): usb_denied = 0
I/SmartNS_PSService( 3405): usb notificaiton:true
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
W/ContextImpl( 3405): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.PSReceiver
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  906): bSetPropertyMultiRAB:false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3405/1000)
I/RemoteViews( 1109): com.android.settings (true,33751552)
D/DotMatrix( 1535): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 3405): usb_cable_connect = 1
D/SmartNS_Utility( 3405): usb_denied = 0
I/SmartNS_PSService( 3405): usb notificaiton:true
I/RemoteViews.Performance( 1109): com.android.settings 1 3 10
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  906): bSetPropertyMultiRAB:false
D/SmartNS_Utility( 3405): usb_cable_connect = 1
D/SmartNS_Utility( 3405): usb_denied = 0
D/DotMatrix( 1535): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/SmartNS_PSService( 3405): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3405): USB Plugged, Set USBPlugged=  truePSenabled:false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3405/1000)
I/ActivityManager(  906): Resuming delayed broadcast
I/RemoteViews( 1109): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1109): com.android.settings 2 1 10
D/Process (  906): killProcessQuiet, pid=3175
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3175:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3175
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WeatherUtility( 3273): can't get weather sync account
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1247): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1247): com.google.android.googlequicksearchbox 0 1 5
,I/ActivityManager(  906): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
W/WeatherRequest( 3273): request cur loc, but there is no sys cur
W/Settings( 3273): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/RemoteViews( 1247): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1247): pl.k2.droidoaudioteka 0 1 8
D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 1 5 17
D/LocationManagerService(  906): getAllProviders()=[passive, gps, network]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(42f37470): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  906): releaseHCC(430e3950): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
V/AlarmManager(  906): sending alarm PendingIntent{42ba3890: PendingIntentRecord{42f3a470 com.google.android.gms startService}}, i=null, t=0, cnt=17069, w=84918423, Int=84918423
I/ActivityManager(  906): Resuming delayed broadcast
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
I/AdsMeasurementBroadcastReceiver( 1200): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1200): Unauthorized to start the main service
D/SnetService( 1200): snet destroyed
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3432 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 3432): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
D/PowerUsageService( 3432): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3432): MY_DEBUG = false
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4245af10: PendingIntentRecord{42966668 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=55424, Int=0
,I/ClockThread( 1109): now=1449498960034 next=59966
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3187
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3187:com.htc.contacts/u0a41 (adj 15): empty #17
D/PMS     (  906): acquireWL(42fc1290): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3432 1000 null
,W/WeatherUtility( 1109): can't get weather sync account
,D/WeatherUtility( 1382): Weather sync is On
,D/WSP     ( 1382): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3449 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/WeatherUtility( 3273): can't get weather sync account
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/WeatherRequest( 3273): request cur loc, but there is no sys cur
,W/Settings( 3273): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 1 10 17
,I/ActivityManager(  906): Recipient 3187
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SensorManager(  906): mEventCount = 450
,D/PMS     (  906): releaseWL(4303d050): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3467 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 3216:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3216
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3216
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3467): Database version: 95
,W/ContextImpl( 3467): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,V/AlarmManager(  906): sending alarm PendingIntent{42cb7fc8: PendingIntentRecord{42db1328 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1449498961241, Int=0
,D/Process (  906): killProcessQuiet, pid=3230
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3230:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3230
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 3467): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3467): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3467): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3467): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3467, uid=10154, userID:0
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.music (pid 3467): Registered
,I/MediaRouter( 3467): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/DFPI.PIReciver( 3288): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (3467/10154)
I/DFPI.ApkInstallService( 3288): onHandleIntent
,I/DFPI.ApkInstallService( 3288): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3288): check CID = HTC__032
,I/DFPI.ApkInstallService( 3288): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,D/MediaRouter( 3467): getSelectedRoute
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3467, uid=10154, userID:0
,I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3489 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3489/10051)
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3489): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,I/SocialFeedProvider( 1247): +disConnect socialManager
,I/SocialFeedProvider( 1247): disconnect socialManager
,I/SocialFeedProvider( 1247): -disConnect socialManager
,D/PMS     (  906): releaseWL(42fc1290): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3508 uid=10080 gids={50080, 5001, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=2958
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2958:com.android.settings:remote/1000 (adj 15): empty #17
,I/SoundPicker( 3508): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3508): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3508): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3508): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3508): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3508): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3508): MODE_GSM access default DB
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3508): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3508): MODE_GSM access default DB
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  906): Recipient 2958
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3317
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3317:com.htc.stock/u0a81 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3317
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 1200): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/PMS     (  906): acquireWL(42e58060): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  906): releaseWL(42e58060): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 1200): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1200, uid=10028, userID:0
,I/HtcModeClient( 1477): handler message = 4011
,E/HtcModeClient( 1477): Check connection and retry 6 times.
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3529 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3329:com.htc.stock:remote/u0a81 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3329
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/[PluginManager]RegisterService( 1382): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1382): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Recipient 3329
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3545 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3545, uid=10073, userID:0
,D/Finsky  ( 3545): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3545/10073)
,D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3545/10073)
,D/Finsky  ( 3545): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,V/AlarmManager(  906): sending alarm PendingIntent{42d5bb30: PendingIntentRecord{42dd0b88 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1449498961680, Int=0
,W/Settings( 3545): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3545): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SocialManager[SocialBiLogHelper]( 3342): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3342): last commit ulog time 1449467994035
,I/SocialManager[SocialBiLogHelper]( 3342): skip commit this time
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3545, uid=10073, userID:0
,D/Process (  906): killProcessQuiet, pid=3248
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1247): action: android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  906): Killing 3248:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
D/Finsky  ( 3545): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3545): [1] 2.run: Finished loading 1 libraries.
,I/IcingCorporaProvider( 2682): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  906): Recipient 3248
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Finsky  ( 3545): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  906): Delaying start of: ServiceRecord{42ee0718 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,D/PMS     (  906): acquireWL(430589f0): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42cb4f48 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/PMS     (  906): releaseWL(430589f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/Finsky  ( 3545): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PMS     (  906): acquireWL(42e6fff0): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  906): releaseWL(42e6fff0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(4317c4a8): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  906): releaseWL(4317c4a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3584 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  906): acquireWL(42eae900): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  906): releaseWL(42eae900): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/DeviceManagement( 3584): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3584 dbg=false s=true
,I/DeviceManagement( 3584): PackageUpdateReceiver: vvv Package added: [com.example.hello]
D/PMS     (  906): acquireWL(42f416f8): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
I/ActivityManager(  906): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
,D/Process (  906): killProcessQuiet, pid=3261
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3261:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/PMS     (  906): releaseWL(42f416f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3261
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3597 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  906): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1263
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,D/PMS     (  906): acquireWL(42802290): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
D/BluetoothManagerService(  906): Message: MESSAGE_DISABLE
,D/WifiManager( 3092): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: false pid=3092, uid=10355
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1327
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 2(ms)
,I/jxcore-log( 3092): ****TEST TOOK:  5046  ms ****
I/jxcore-log( 3092): 
,I/jxcore-log( 3092): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3092): 
D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/PMS     (  906): releaseWL(42802290): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  906): acquireWL(42e531b0): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  906): releaseWL(42e531b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42e474c8): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  906): releaseWL(42e474c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42ebb7f0): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  906): releaseWL(42ebb7f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(431160c0): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  906): releaseWL(431160c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42e6b4e8): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  906): releaseWL(42e6b4e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2682): Copying FileAsset 0x64429b98 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2682): UpdateCorporaTask done [took 427 ms] updated apps [took 427 ms] 
,E/cutils-trace( 3610): Error opening trace file: No such file or directory (2)
,W/GAV2    ( 3597): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  906): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3627 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/htcbackup-core( 3627): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3627): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3627): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3584): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
D/CustomizationManager( 3610): ====startRecUseTime====
D/htc.customization.log.level( 3610):  is 
,W/CustomizationLogLevel( 3610): Level value is invalid, use default level 2
,I/DeviceManagement( 3584): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.smartdim, com.htc.htcpowermanager, com.htc.drive.activator, com.htc.mirrorlinkserver, com.htc.lockscreen, com.android.providers.settings, com.htc.feedback, com.htc.checkinprovider, com.qualcomm.timeservice, com.android.keychain, com.android.inputdevices, com.htc.autobot.cargps.provider, com.htc.home.personalize, android, com.android.location.fused, com.htc.guide, com.htc.android.htcsetupwizard, com.qualcomm.privinit, com.htc.backup, com.htc.cirmodule, com.htc.usage, com.android.CSDFunctionG, com.android.settings, com.htc.android.htcloglevel, com.htc.backupreset]
,I/DeviceManagement( 3584): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
D/Process (  906): killProcessQuiet, pid=3302
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3643 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  906): Killing 3302:com.htc.task/u0a70 (adj 15): empty #17
I/DeviceManagement( 3584): WorkflowService: Starting workflow service
I/DeviceManagement( 3584): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@42461538] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 3584): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3584): ModelRegistry: Loading model meta data from resources...
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3302
,I/DeviceManagement( 3584): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3584): SessionStateController: Checking invariants...
,D/CustomizationManager( 3610):  Read ACC file spent 0.064 (s)
,D/CIDMapFileReader( 3610): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3610): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3610): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3610): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3610): Parsing tag item name = HTC__032
,D/CIDMapFileReader( 3610): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3610): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3610): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3610): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3610): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3610): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3610): Parsing tag category name = system
,I/CustomizationCIDLoader( 3610): Parsing tag category name = application
I/CustomizationCIDLoader( 3610): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 3610): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3610): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3610): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3610): Parsing tag category name = Settings
D/CustomizationManager( 3610):  Read CID file spent 0.111 (s)
,D/CustomizationManager( 3610):  All configurations done spent 0.111 (s)
W/HtcNativeFlag( 3610): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3610): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3610): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3610): Fail to get flag for type 'language', use default value: -1
,D/HtcCupdReceiver(Provider)( 3643):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  906): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,I/DeviceManagement( 3584): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,D/PackageManager(  906): deletePackageAsUser: pkg=com.example.hello, pid=3610, uid=2000 user=0
,V/AlarmManager(  906): sending alarm PendingIntent{430f8620: PendingIntentRecord{4314e970 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449498964409, Int=0
,I/ActivityManager(  906): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,D/Process (  906): killProcessQuiet, pid=3092
,W/asset   (  906): Copying FileAsset 0x63065be8 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  906): Killing 3092:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  906): Force removing ActivityRecord{430e3998 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  906): Skipping PackageSetting{42b15f78 com.test.thalitest/10348} due to missing metadata
,I/ActivityManager(  906): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/DeviceManagement( 3584): SessionStateController: Checking invariants...
,I/ActivityManager(  906): Resuming delayed broadcast
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1535): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
I/Prism.ItemManager( 3342): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1310): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,I/Prism.ItemManager( 3342): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1535): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1535): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,D/PMS     (  906): acquireWL(43068fa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1400 10028 null
W/GeofencerStateMachine( 1400): Ignoring removeGeofence because network location is disabled.
I/acms    ( 1777): Unregistering com.example.hello
,E/acms    ( 1777): Could not unregister removed application com.example.hello
,D/AccTypeManager( 1310): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(43068fa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3664 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,W/GAV2    ( 3597): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/WindowState(  906): WIN DEATH: Window{42ecebf8 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  906): Client connection lost with reason: 4
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/FeedHostManager( 1247): [onResume]
,I/FeedProviderManager( 1247): onResume
,I/SocialFeedProvider( 1247): +onResume
,D/AccTypeManager( 1310): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/SocialFeedProvider( 1247): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1247): -onResume
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
,I/ConnectivityHelper( 1247): [getCurrentConnectionType] no network connection
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1247/10075)
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
,W/SystemReader( 1234): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
,I/DeviceManagement( 3584): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,E/ExternalAccountType( 1310): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,W/GLSUser ( 1347): GoogleAccountDataService.getToken()
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/DeviceManagement( 3584): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@42461538]
I/DeviceManagement( 3584): WorkflowService: Stopping workflow service
,D/Process (  906): killProcessQuiet, pid=3198
,I/ActivityManager(  906): Killing 3198:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 3092 uid 10355
,I/InputMethodManagerService(  906): Enable input method client, pid=1247
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,W/Binder  ( 1185): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1185): java.lang.NullPointerException
W/Binder  ( 1185): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1185): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1185): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1185): 	at dalvik.system.NativeStart.run(Native Method)
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3198
,D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,W/GLSActivity( 1347): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1347): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1347): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  906): acquireWL(42eb71e0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3664 10160 null
,D/PMS     (  906): releaseWL(42eb71e0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  906): acquireWL(42d5b8a8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3664 10160 null
,D/PMS     (  906): acquireWL(42e01f40): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3664 10160 null
,D/PMS     (  906): releaseWL(42d5b8a8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3664/10160)
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3664/10160)
,D/PMS     (  906): releaseWL(42e01f40): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/DFPI.PIReciver( 3288): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3288): onHandleIntent
,I/DFPI.ApkInstallService( 3288): Media Scan Finished Case 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 3288): check CID = HTC__032
,I/DFPI.ApkInstallService( 3288): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
,I/SoundPicker( 3508): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3508): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3508): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3508): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3508): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3508): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3508): MODE_GSM access default DB
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3508): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3508): MODE_GSM access default DB
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
D/Settings:HtcWirelessFeatureFlags( 3405): id/is att sku: 99/false
,W/SystemReader( 3405): Cannot find devicepolicy_lower_fp_quality, use default value instead
W/SystemReader( 3405): Cannot find support_harman, use default value instead
W/SystemReader( 3405): Cannot find effect_manager_id, use default value instead
I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
E/Settings:HtcWrapHeaderInfo( 3405): no such activity!
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3405): The wrap header doesn't exist in header list.
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/TelephonyReceiver( 1220): bind: true
,E/Settings:HtcWrapHeaderInfo( 3405): updateDevelopment, bPrefShow = true
I/ActivityManager(  906): Resuming delayed broadcast
,E/Settings:HtcUmcWidgetEnabler( 3405): isSupportMusicChannel(): false
,I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=3702 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
D/GenericMessagesProvider( 2561): query uri: content://htc-messages/wappush/count
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportHomeButton]support         :false
,W/FingerprintManager( 3405): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
E/Settings:HtcVoWifiWidgetEnabler( 3405): isSupportVoWifi: null
E/SQLiteLog( 2561): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 2561): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 2561): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 2561): DB info: errno = 2, errno message = No such file or directory
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 3405): Failed to find provider info for com.htc.vowifi
E/SQLiteDatabase( 2561): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2561): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2561): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2561): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2561): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2561): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2561): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2561): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2561): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2561): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2561): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2561): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2561): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2561): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2561): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2561): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2561): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2561): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2561): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 2561): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2561): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 2561): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 2561): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2561): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2561): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2561): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2561): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2561): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2561): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/PackageManager(  906): Unable to load service info ResolveInfo{430676d8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handle,r.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 2561): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 2561): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 2561): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 2561): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2561): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 2561): 	at dalvik.system.NativeStart.run(Native Method)
D/TelephonyReceiver( 1220): switchBindHtcMsgCursor: null
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoTaskReceiver
E/SQLiteDatabase( 3702): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 3702): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3702): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3702): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3702): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3702): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3702): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3702): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3702): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3702): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3702): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3702): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 3702): 	at com.htc.task.dm.TaskSource.specificPkg(TaskSource.java:78)
E/SQLiteDatabase( 3702): 	at com.htc.task.sm.LocalTaskSource.updateIfNecessary(LocalTaskSource.java:41)
E/SQLiteDatabase( 3702): 	at com.htc.task.sm.TaskSourceManager.reloadAll(TaskSourceManager.java:97)
E/SQLiteDatabase( 3702): 	at com.htc.task.TodoService.reloadTaskSource(TodoService.java:415)
E/SQLiteDatabase( 3702): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:103)
E/SQLiteDatabase( 3702): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3702): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3702): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3702): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 3702): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 3702): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3702): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3702): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3702): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3702): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3702): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3702): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3702): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3702): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3702): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3702): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 3702): 	at com.htc.task.dm.TaskSource.specificPkg(TaskSource.java:78)
E/SQLiteOpenHelper( 3702): 	at com.htc.task.sm.LocalTaskSource.updateIfNecessary(LocalTaskSource.java:41)
E/SQLiteOpenHelper( 3702): 	at com.htc.task.sm.TaskSourceManager.reloadAll(TaskSourceManager.java:97)
E/SQLiteOpenHelper( 3702): 	at com.htc.task.TodoService.reloadTaskSource(TodoService.java:415)
E/SQLiteOpenHelper( 3702): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:103)
E/SQLiteOpenHelper( 3702): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3702): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3702): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3702): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 3702): Opened MyDB.db in read-only mode
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3715 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3405): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3405): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3405): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3405): [supportHomeButton]support         :false
,I/ActivityManager(  906): Resuming delayed broadcast
W/FingerprintManager( 3405): hasFingerprint() - sSensorCode = 0
,D/DFPI.PIReciver( 3288): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,E/Settings:HtcVoWifiWidgetEnabler( 3405): isSupportVoWifi: null
I/DFPI.ApkInstallService( 3288): onHandleIntent
,I/DFPI.ApkInstallService( 3288): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3288): check CID = HTC__032
,I/DFPI.ApkInstallService( 3288): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
E/ActivityThread( 3405): Failed to find provider info for com.htc.vowifi
I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3360
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3360:com.google.android.talk/u0a111 (adj 15): empty #17
,I/SoundPicker( 3508): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3508): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3508): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/ActivityManager(  906): Recipient 3360
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3508): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3508): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3508): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3508): MODE_GSM access default DB
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3508): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3508): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3508): MODE_GSM access default DB
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3508): SoundPicke,rUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3508): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/EASAppSvc( 3715): [ NA ]- onCreate()
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/EASAppSvc( 3715): [ NA ]> onUpgrade: version = 63
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,D/ORMLib  ( 3702): put()
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
E/DBProvider( 3702): not an error (code 0): Could not open the database in read/write mode.
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,W/System.err( 3702): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,W/System.err( 3702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/System.err( 3702): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/System.err( 3702): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/System.err( 3702): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 3702): 	at com.htc.task.dm.DBProvider.update(DBProvider.java:532)
W/System.err( 3702): 	at com.htc.task.APICProviderDecorator.update(APICProviderDecorator.java:490)
W/System.err( 3702): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
,W/System.err( 3702): 	at android.content.ContentProviderClient.update(ContentProviderClient.java:251)
,E/SQLiteDatabase( 3715): Failed to open database '/data/data/com.htc.android.mail/databases/mail.db'.
E/SQLiteDatabase( 3715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3715): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3715): 	at com.htc.android.mail.MailProvider$DatabaseWrapper.getReadableDatabase(MailProvider.java:5265)
E/SQLiteDatabase( 3715): 	at com.htc.android.mail.MailProvider$DatabaseWrapper.query(MailProvider.java:5330)
E/SQLiteDatabase( 3715): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2502)
E/SQLiteDatabase( 3715): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3715): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3715): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3715): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3715): 	at com.htc.android.mail.eassvc.EASAppSvc.createExchangeSources(EASAppSvc.java:3746)
E/SQLiteDatabase( 3715): 	at com.htc.android.mail.eassvc.EASAppSvc.initExchangeSources(EASAppSvc.java:3726)
E/SQLiteDatabase( 3715): 	at com.htc.android.mail.eassvc.EASAppSvc.access$1700(EASAppSvc.java:140)
E/SQLiteDatabase( 3715): 	at com.htc.android.mail.eassvc.EASAppSvc$MainHandlerThread.run(EASAppSvc.java:2265)
W/System.err( 3702): 	at com.htc.orm.Model.put(Model.java:143)
W/System.err( 3702): 	at com.htc.orm.Model.put(Model.java:170)
W/System.err( 3702): 	at com.htc.task.sm.PluginUpdatedServiceConnection.updateDB(PluginUpdatedServiceConnection.java:195)
W/System.err( 3702): 	at com.htc.task.sm.PluginUpdatedServiceConnection$1.run(PluginUpdatedServiceConnection.java:125)
,W/System.err( 3702): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteOpenHelper( 3715): Couldn't open mail.db for writing (will try read-only):
E/SQLiteOpenHelper( 3715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3715): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3715): 	at com.htc.android.mail.MailProvider$DatabaseWrapper.getReadableDatabase(MailProvider.java:5265)
E/SQLiteOpenHelper( 3715): 	at com.htc.android.mail.MailProvider$DatabaseWrapper.query(MailProvider.java:5330)
E/SQLiteOpenHelper( 3715): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2502)
E/SQLiteOpenHelper( 3715): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 3715): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 3715): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 3715): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 3715): 	at com.htc.android.mail.eassvc.EASAppSvc.createExchangeSources(EASAppSvc.java:3746)
E/SQLiteOpenHelper( 3715): 	at com.htc.android.mail.eassvc.EASAppSvc.initExchangeSources(EASAppSvc.java:3726)
E/SQLiteOpenHelper( 3715): 	at com.htc.android.mail.eassvc.EASAppSvc.access$1700(EASAppSvc.java:140)
E/SQLiteOpenHelper( 3715): 	at com.htc.android.mail.eassvc.EASAppSvc$MainHandlerThread.run(EASAppSvc.java:2265)
I/EASAppSvc( 3715): [ NA ]- onDestroy()
I/EASAppSvc( 3715): [ NA ]> uninitEASService
,I/SoundPicker( 3508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,W/SQLiteOpenHelper( 3715): Opened mail.db in read-only mode
,I/ActivityManager(  906): Resuming delayed broadcast
,E/SharedPreferencesImpl( 3467): Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3715/10063)
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/WifiService(  906): New client listening to asynchronous messages
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3715/10063)
,E/SQLiteDatabase( 3467): Failed to open database '/data/data/com.google.android.music/databases/music.db'.
E/SQLiteDatabase( 3467): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3467): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3467): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3467): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3467): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3467): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3467): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3467): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3467): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3467): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3467): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3467): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3467): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3467): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3467): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/SQLiteDatabase( 3467): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 3467): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/SQLiteDatabase( 3467): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/SQLiteDatabase( 3467): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/SQLiteDatabase( 3467): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/SQLiteDatabase( 3467): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/SQLiteDatabase( 3467): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/SQLiteDatabase( 3467): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 3467): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3467): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/SQLiteDatabase( 3467): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3467): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 3467): threadid=16: thread exiting with uncaught exception (group=0x41ff8e30)
D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3715/10063)
,W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,E/ActivityManager(  906): App crashed! Process: com.google.android.music:main
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/AndroidRuntime( 3467): FATAL EXCEPTION: MediaStoreImportService
E/AndroidRuntime( 3467): Process: com.google.android.music:main, PID: 3467
E/AndroidRuntime( 3467): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3467): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3467): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3467): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3467): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3467): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3467): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3467): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3467): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3467): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3467): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3467): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3467): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3467): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3467): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/AndroidRuntime( 3467): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 3467): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/AndroidRuntime( 3467): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/AndroidRuntime( 3467): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/AndroidRuntime( 3467): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/AndroidRuntime( 3467): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/AndroidRuntime( 3467): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/AndroidRuntime( 3467): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3467): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3467): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/AndroidRuntime( 3467): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3467): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
,W/GLSUser ( 1347): GoogleAccountDataService.getToken()
,W/GLSActivity( 1347): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1347): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1347): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3545): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3545): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,E/SQLiteDatabase( 3545): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 3545): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3545): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3545): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3545): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3545): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3545): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3545): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3545): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3545): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3545): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3545): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 3545): 	at com.google.android.finsky.library.Libraries$3.run(Libraries.java:235)
E/SQLiteDatabase( 3545): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 3545): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3545): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3545): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 3545): threadid=25: thread exiting with uncaught exception (group=0x41ff8e30)
,E/ActivityManager(  906): App crashed! Process: com.android.vending
E/AndroidRuntime( 3545): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 3545): Process: com.android.vending, PID: 3545
E/AndroidRuntime( 3545): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3545): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3545): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3545): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3545): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3545): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3545): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3545): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3545): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3545): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3545): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 3545): 	at com.google.android.finsky.library.Libraries$3.run(Libraries.java:235)
E/AndroidRuntime( 3545): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3545): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3545): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3545): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
,I/EASRequestController( 3715): [ NA ]release
,I/EASAppSvc( 3715): [ NA ]< uninitEASService
,I/EASAppSvc( 3715): [ NA ]- onCreate()
,I/EASAppSvc( 3715): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3715/10063)
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3715/10063)
D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3715/10063)
,D/ORMLib  ( 3702): put()
E/DBProvider( 3702): not an error (code 0): Could not open the database in read/write mode.
,W/System.err( 3702): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
,W/System.err( 3702): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/System.err( 3702): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/System.err( 3702): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/System.err( 3702): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 3702): 	at com.htc.task.dm.DBProvider.update(DBProvider.java:532)
W/System.err( 3702): 	at com.htc.task.APICProviderDecorator.update(APICProviderDecorator.java:490)
W/System.err( 3702): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/System.err( 3702): 	at android.content.ContentProviderClient.update(ContentProviderClient.java:251)
W/System.err( 3702): 	at com.htc.orm.Model.put(Model.java:143)
W/System.err( 3702): 	at com.htc.orm.Model.put(Model.java:170)
W/System.err( 3702): 	at com.htc.task.sm.PluginUpdatedServiceConnection.updateDB(PluginUpdatedServiceConnection.java:195)
W/System.err( 3702): 	at com.htc.task.sm.PluginUpdatedServiceConnection$1.run(PluginUpdatedServiceConnection.java:125)
,W/System.err( 3702): 	at java.lang.Thread.run(Thread.java:864)
I/EASAppSvc( 3715): [ NA ]- onDestroy()
,I/EASAppSvc( 3715): [ NA ]> uninitEASService
,I/EASRequestController( 3715): [ NA ]release
,I/EASAppSvc( 3715): [ NA ]< uninitEASService
,I/ActivityManager(  906): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3758 uid=10067 gids={50067, 3003, 5012}
,D/Process (  906): killProcessQuiet, pid=3386
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3386:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3386
,D/WifiService(  906): Client connection lost with reason: 4
,D/ORMLib  ( 3702): put()
,E/DBProvider( 3702): not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3702): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 3702): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
,W/System.err( 3702): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/System.err( 3702): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/System.err( 3702): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 3702): 	at com.htc.task.dm.DBProvider.update(DBProvider.java:532)
W/System.err( 3702): 	at com.htc.task.APICProviderDecorator.update(APICProviderDecorator.java:490)
W/System.err( 3702): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/System.err( 3702): 	at android.content.ContentProviderClient.update(ContentProviderClient.java:251)
W/System.err( 3702): 	at com.htc.orm.Model.put(Model.java:143)
W/System.err( 3702): 	at com.htc.orm.Model.put(Model.java:170)
W/System.err( 3702): 	at com.htc.task.sm.PluginUpdatedServiceConnection.updateDB(PluginUpdatedServiceConnection.java:195)
W/System.err( 3702): 	at com.htc.task.sm.PluginUpdatedServiceConnection$1.run(PluginUpdatedServiceConnection.java:125)
W/System.err( 3702): 	at java.lang.Thread.run(Thread.java:864)
,D/AutoSetting( 1382): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1382): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1382): service - requestNLP() NetworkLocationProvider not enabled
,W/GLSUser ( 1347): GoogleAccountDataService.getToken()
,W/GLSActivity( 1347): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1347): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1347): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3545): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3545): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3545): [1] DailyHygiene.reschedule: Scheduling new run in 97 minutes (failures=3)
,E/SharedPreferencesImpl( 3545): Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
,D/Process (  906): killProcessQuiet, pid=3432
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3432:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3432
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 3342): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3342): loadItems() com.htc.launcher.pageview.WidgetManager@4249cb90 +
,I/Prism.WidgetManager( 3342): onLoadItems() +

```
