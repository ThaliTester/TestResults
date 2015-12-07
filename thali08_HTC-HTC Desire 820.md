#### Test 502422852e23b2c_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41f1cfd8 +
I/Prism.WidgetManager( 1249): onLoadItems() +
W/PackageManager(  909): Unable to load service info ResolveInfo{42bc1ba8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
E/Prism.WidgetManager( 1249): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1249): onLoadItems() -
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41f1cfd8 -
D/ContactMessageStore( 1224): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1224): MSG_NOTIFY_CS_TO_SYNC <<
D/PhoneApp( 1224): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1224): -- N1 =0
D/PhoneApp( 1224): -- N2 =0
D/PhoneApp( 1224): -- N3 =0
I/GAV2    ( 2822): Thread[GAThread,5,main]: No campaign data found.
--------- beginning of /dev/log/system
D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  909): start
I/ActivityManager(  909): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3080 uid=10038 gids={50038}
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3093 uid=10077 gids={50077}
D/Process (  909): killProcessQuiet, pid=2790
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 2790:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2790
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SMSBackup( 3093): Got a database change event
I/ActivityManager(  909): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3107 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
D/Process (  909): killProcessQuiet, pid=2822
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 2822:com.google.android.gm/u0a107 (adj 15): empty #17
D/browser ( 3107): Browser versionCode = 760001523 versionName = 7.0.2512153020
W/SWE_UI  ( 3107): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3107): Loading: swewebviewchromium
I/LibraryLoader( 3107): Time to load native libraries: 34 ms (timestamps 4230-4264)
I/LibraryLoader( 3107): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3107): Initializing chromium process, renderers=9
I/LibraryLoader( 3107): Expected native library version number "",actual native library version number ""
I/chromium( 3107): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  909): Recipient 2822
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/HtcModeClient( 1471): handler message = 4011
E/HtcModeClient( 1471): Check connection and retry 5 times.
E/cutils-trace( 3100): Error opening trace file: No such file or directory (2)
W/chromium( 3107): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
I/Adreno-EGL( 3107): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3107): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3107): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3107): Local Branch: 
I/Adreno-EGL( 3107): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3107): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3107):                  aa63bbd948f41d15fc72f585e
D/CustomizationManager( 3100): ====startRecUseTime====
D/htc.customization.log.level( 3100):  is 
W/CustomizationLogLevel( 3100): Level value is invalid, use default level 2
D/Process (  909): killProcessQuiet, pid=2181
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
V/IccIntentReceiver( 1274): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  909): Killing 2181:com.android.defcontainer/u0a19 (adj 15): empty #17
I/SIMStateChangeReceiver( 1471): SIM state: ABSENT
I/SIMStateChangeReceiver( 1471): phoneType = 0
I/SIMStateChangeReceiver( 1471): remove notification
I/ActivityManager(  909): Recipient 2181
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3153 uid=10091 gids={50091, 3003, 5012}
V/AlarmManager(  909): sending alarm PendingIntent{41e8ab38: PendingIntentRecord{427b5d08 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=54114, Int=0
I/ActivityManager(  909): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3164 uid=10031 gids={50031, 3003, 5012}
D/CustomizationManager( 3100):  Read ACC file spent 0.072 (s)
D/CIDMapFileReader( 3100): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3100): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3100): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3100): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3100): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3100): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3100): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3100): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3100): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3100): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3100): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3100): Parsing tag category name = system
I/CustomizationCIDLoader( 3100): Parsing tag category name = application
I/CustomizationCIDLoader( 3100): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3100): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3100): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3100): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3100): Parsing tag category name = Settings
D/CustomizationManager( 3100):  Read CID file spent 0.120 (s)
D/CustomizationManager( 3100):  All configurations done spent 0.120 (s)
W/HtcNativeFlag( 3100): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3100): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3100): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3100): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3100
D/PMS     (  909): acquireHCC(42a3a888): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
W/asset   (  909): Copying FileAsset 0x693acf30 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1115182152
D/PMS     (  909): acquireHCC(42b116b8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
D/PMS     (  909): acquireWL(4299e998): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/FeedHostManager( 1249): [onPause]
I/FeedProviderManager( 1249): onPause
I/FeedHostManager( 1249): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42137d28
I/SocialFeedProvider( 1249): +onPause
I/SocialFeedProvider( 1249): -onPause
I/ActivityManager(  909): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3183 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  909): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3195 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
I/ActivityManager(  909): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3207 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
D/Process (  909): killProcessQuiet, pid=2859
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 2859:com.htc.backup/1000 (adj 15): empty #17
I/TrimMemoryManager( 1249): [trimMemory] 20
W/asset   ( 3195): Copying FileAsset 0x5c8d6c90 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
V/WebViewChromiumFactoryProvider( 3195): Binding Chromium to main looper Looper (main, tid 1) {41e8eba8}
I/LibraryLoader( 3195): Expected native library version number "",actual native library version number ""
I/chromium( 3195): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3195): Initializing chromium process, renderers=0
D/PMS     (  909): acquireWL(42af91d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  909): acquireWL(42ad59d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4284c248:true
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3195): 1105872288: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  909): releaseWL(42af91d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/SystemReader( 2568): Cannot find message_ambs_application_id, use default value instead
I/Adreno-EGL( 3195): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3195): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3195): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3195): Local Branch: 
I/Adreno-EGL( 3195): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3195): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3195):                  aa63bbd948f41d15fc72f585e
D/SmsReceiver( 2568): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2568): onReceive()
D/ExchangePolicystatus( 2568): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2568): onReceive(): else
D/Process (  909): killProcessQuiet, pid=2805
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/HtcBroadcastReceiver( 1224): onReceive: android.intent.action.SIM_STATE_CHANGED
D/MdScBoot( 3153): [7e8.1.] 30@-150724 -> 40@-150754
I/ActivityManager(  909): Killing 2805:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 2859
I/ActivityManager(  909): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3231 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/Process (  909): killProcessQuiet, pid=2882
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/Process (  909): killProcessQuiet, pid=2909
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 2882:com.google.android.talk/u0a111 (adj 15): empty #17
I/ActivityManager(  909): Killing 2909:com.htc.backupreset/1000 (adj 15): empty #17
W/chromium( 3195): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/ActivityManager(  909): Recipient 2909
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 3195): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3195): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3195): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3195): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3195): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3195): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3195): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3195): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 3195): CordovaWebView is running on device made by: HTC
,D/CalendarApplication( 3231): onCreate
D/ProviderChangeReceiver( 3231): ---------------------------------------------------
,D/ProviderChangeReceiver( 3231): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3231): start to updateAlertNotification!
,W/AccTypeManager( 3207): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3207): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/ContextImpl( 2958): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AlertService( 3231): No fired or scheduled alerts
,D/HtcAlertUtils( 3231): -- cancelReminderNotification --
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,D/HtcAlertUtils( 3231): broadcastExistReminder!
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/AdsMeasurementBroadcastReceiver( 1201): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1201): Unauthorized to start the main service
,D/Process (  909): killProcessQuiet, pid=2926
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 2926:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2926
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AccTypeManager( 3207): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  909): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3262 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,I/ActivityManager(  909): Recipient 2805
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 2882
,E/ExternalAccountType( 3207): Unsupported attribute readOnly
,W/AccTypeManager( 3207): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3207): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AwContents( 3195): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  909): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3283 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
D/AccTypeManager( 3207): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/WeatherUtility( 3262): can't get weather sync account
,E/ExternalAccountType( 3207): Unsupported attribute readOnly
W/ResourceType( 3195): No package identifier when getting name for resource number 0x00000064
I/InputMethodManagerService(  909): Disable input method client, pid=1249
,I/InputMethodManagerService(  909): Enable input method client, pid=3195
I/InputMethodManager( 3195): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ed5928, mServedView=org.apache.cordova.engine.SystemWebView{41e9b8c0 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 3195): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  909): Displayed com.example.hello/.MainActivity: +351ms
I/DemoRecovery.RestoreReceiver( 3283): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/ContextImpl( 3283): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/RestoreService( 3283): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
D/PMS     (  909): releaseWL(4299e998): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3297 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=2942
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 2942:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,W/WeatherRequest( 3262): request cur loc, but there is no sys cur
,W/Settings( 3262): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1249): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1249): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1249): com.htc.widget.weatherclock 0 7 17
,D/PMS     (  909): acquireWL(426b7e08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3297 10070 null
,D/PMS     (  909): acquireWL(42530fe8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3297 10070 null
,D/PMS     (  909): releaseWL(426b7e08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  909): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3297): update TASK shortcut>
,I/TodoTaskNotifyService( 3297): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  909): releaseWL(42530fe8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
,W/NotifyReceiver( 3297): stopSelfResult true
,D/Process (  909): killProcessQuiet, pid=2971
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3312 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  909): Killing 2971:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2942
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 2971
,E/AndroidProtocolHandler( 3195): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium( 3195): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager(  909): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3326 uid=10081 gids={50081, 3003, 5012}
,D/JsMessageQueue( 3195): Set native->JS mode to OnlineEventsBridgeMode
,D/Process (  909): killProcessQuiet, pid=3012
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Process (  909): killProcessQuiet, pid=2998
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/AdsMeasurementBroadcastReceiver( 1201): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1201): Unauthorized to start the main service
I/ActivityManager(  909): Killing 3012:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  909): Killing 2998:org.simalliance.openmobileapi.service/9987 (adj 15): empty #18
,D/SMSBackup( 3093): Got a database change event
I/ActivityManager(  909): Recipient 2998
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3012
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3339 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ImageRamCache( 3339): create image Cache, size: 31457280.
I/ImageRamCache( 3339): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3339): create image Cache, size: 12582912.
,I/FeedSettings( 3339): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3339): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3339): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3339): changeLocale(): en_GB
,D/jxcore_app_log( 3195): JniHelper::setJavaVM(0x41a49010), pthread_self() = 1658187496
,D/JX-Cordova( 3195): jxcore cordova android initializing
,I/Prism.AllAppsOptionsMa_( 3339): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3339): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3339): [custom highlight] onReceive
,D/CustomHighlightService( 3339): [custom highlight] onHandleIntent
,I/ActivityManager(  909): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/NewsDB  ( 3339): set custom highlight []
,D/CustomHighlightService( 3339): [custom highlight] set tags 
,D/MessagingShortcutReceiver( 2568): keep hiding shortcut bubble
D/MessagingShortcut( 2568): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2568): After query: 0
D/MessagingShortcut( 2568): mPresentUnreadCount: -1
,D/MessagingShortcut( 2568): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2568): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/ActivityManager(  909): Resuming delayed broadcast
D/DotMatrix( 1524): [EventService] reorderNotification, total:0
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3297): update TASK shortcut>
I/ActivityManager(  909): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1224): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,D/Process (  909): killProcessQuiet, pid=3024
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 3024:com.google.android.youtube/u0a168 (adj 15): empty #17
,W/jxcore-log( 3195): Initializing JXcore engine
,W/jxcore-log( 3195): JXcore engine is ready
I/ActivityManager(  909): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,D/MdScBoot( 3153): [da0.1.] 40@-150754
,W/jxcore-log( 3195): Starting JXcore engine
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3358 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/ActivityManager(  909): Recipient 3024
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  909): Client com.google.android.youtube (pid 3024): Died!
,D/MessagingNotification( 2568): New incoming message, can't cancel notification now
,D/MessagingNotification( 2568): newMsgCnt: 0, false
,I/Babel   ( 3358): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3358): MmsConfig.loadMmsSettings
,E/dalvikvm( 3358): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 3358): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 3358): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 3358): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 3358): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/MmsCustomizationProvider( 2568): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2568): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3358): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3358): MmsConfig.loadFromDatabase
,E/Babel   ( 3358): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3358): MmsConfig.loadFromResources
E/Babel   ( 3358): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3358): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3358, uid=10111, userID:0
,W/Settings( 3358): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/jxcore-log( 3195): Platform android
W/jxcore-log( 3195): 
,W/jxcore-log( 3195): Process ARCH arm,
W/jxcore-log( 3195): 
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3358, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3358, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3358, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3358, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3358, uid=10111, userID:0
D/Process (  909): killProcessQuiet, pid=2983
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  909): Killing 2983:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2983
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MtpReceiver( 2235): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2235): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2235): [MTP][handleMessage][startService]
D/MtpReceiver( 2235): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2235): [MTP][handleMessage]-
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1757/10178)
,D/MtpService( 2235): [MTP] startForeground
I/ActivityManager(  909): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3384 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/DotMatrix( 1524): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,D/MtpService( 2235): updating state; isCurrentUser=true, mMtpLocked=false
,I/RemoteViews( 1110): com.android.providers.media (false,0)
,D/MtpDatabase( 2235): TotalSize=1918604,MediaCacheLimit=6000
I/RemoteViews.Performance( 1110): com.android.providers.media 1 1 10
,I/RemoteViews( 1110): com.android.providers.media (false,0)
I/jxcore-log( 3195): JXcore Cordova bridge is ready!
I/jxcore-log( 3195): 
,W/jxcore-log( 3195): JXcore engine is started
,I/ProviderInstaller( 3358): Installed default security provider GmsCore_OpenSSL
,I/RemoteViews.Performance( 1110): com.android.providers.media 2 2 15
,D/MtpService( 2235): [isMtpConnected] connected: true
,E/jxcore-log( 3195): >> HTC-HTC Desire 820
E/jxcore-log( 3195): 
,D/SyncApplication( 3384): Loading default preferences
,I/jxcore-log( 3195): Total memory 1964650496
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Free memory 714121216
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): userPath [ 'www' ]
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Size 720 1184
I/jxcore-log( 3195): 
,W/Resources( 3384): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/jxcore-log( 3195): Screen Brightness 10
I/jxcore-log( 3195): 
,E/jxcore-log( 3195): Dummy Error Log.
E/jxcore-log( 3195): 
,D/WifiService(  909): New client listening to asynchronous messages
,D/SyncApplication( 3384): Overriding preferences with custom values
,D/SyncApplication( 3384): Updating preferences succeeded
,E/SyncApplication( 3384): Application created.
D/VolumeInfo( 3384): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3384): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3384): Found 0 mount point(s)
,V/VolumeInfo( 3384): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3384): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3384): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3384): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3384): getNewCalendarAuthority()...
,D/SyncApplication( 3384): enableAppOperation()+
,D/SyncApplication( 3384): enableAppOperation()-
,D/HTCUtilities( 3384): isNeorSinged() + 
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3384, uid=10008, userID:0
W/PackageManager(  909): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3384, uid=10008, userID:0
W/PackageManager(  909): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3384): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3384): isNeorSinged() return false
D/CDMountReceiver( 3384): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3384): USB connected to PC
,D/FOTAReceiver( 3384): onReceive() enter 
,D/FOTAReceiver( 3384): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  909): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3403 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  909): killProcessQuiet, pid=3107
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 3107:com.htc.sense.browser/u0a12 (adj 15): empty #17
,D/HtcFingerPrintQuickLaunchProvider( 3403): -onCreate()
,V/Settings:HtcSettingsApplication( 3403): [3403/3403] onCreate()
,D/TetherSettings( 3403): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3403): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3403): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3403): Cust_ConnectToPC   : spcsc>false
D/        ( 3403): Cust_ConnectToPC   : IPT>true
,D/        ( 3403): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3403): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3403): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3403): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3403): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3403): Cust_ConnectToPC   : spcsc>false
D/        ( 3403): Cust_ConnectToPC   : IPT>true
D/        ( 3403): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3403): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3403): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3403): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3403): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3403): usb_cable_connect = 1
,D/SmartNS_Utility( 3403): usb_denied = 0
I/SmartNS_NSReceiver( 3403): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3403): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3403): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 3403): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3403): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 3403): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3403):  defaultType:0
,I/SmartNS_PSService( 3403): fail notificaiton:false
D/SmartNS_Utility( 3403): usb_cable_connect = 1
D/SmartNS_Utility( 3403): usb_denied = 0
,I/SmartNS_PSService( 3403): usb notificaiton:true
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  909): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 3403): usb_cable_connect = 1
D/SmartNS_Utility( 3403): usb_denied = 0
,I/SmartNS_PSService( 3403): usb notificaiton:true
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/ActivityManager(  909): Delay finish: com.android.settings/.PSReceiver
D/ConnectivityService(  909): getActiveNetworkInfo called by com.android.settings (3403/1000)
D/DotMatrix( 1524): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  909): bSetPropertyMultiRAB:false
,I/RemoteViews( 1110): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1110): com.android.settings 1 1 10
D/SmartNS_Utility( 3403): usb_cable_connect = 1
,D/SmartNS_Utility( 3403): usb_denied = 0
,I/RemoteViews( 1110): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1110): com.android.settings 1 1 10
,D/DotMatrix( 1524): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/SmartNS_PSService( 3403): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3403): USB Plugged, Set USBPlugged=  truePSenabled:false
D/ConnectivityService(  909): getActiveNetworkInfo called by com.android.settings (3403/1000)
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3107
D/Process (  909): killProcessQuiet, pid=3164
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 3164:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3164
,W/WeatherUtility( 3262): can't get weather sync account
D/AppWidgetHostView( 1249): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
I/RemoteViews( 1249): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1249): com.google.android.googlequicksearchbox 1 1 5
D/AppWidgetHostView( 1249): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/ActivityManager(  909): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
I/ActivityManager(  909): Resuming delayed broadcast
I/RemoteViews( 1249): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1249): pl.k2.droidoaudioteka 1 1 8
W/WeatherRequest( 3262): request cur loc, but there is no sys cur
W/Settings( 3262): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppWidgetHostView( 1249): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1249): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  909): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
I/RemoteViews.Performance( 1249): com.htc.widget.weatherclock 1 5 17
D/LocationManagerService(  909): getAllProviders()=[passive, gps, network]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1201/10028)
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1201/10028)
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
,V/AlarmManager(  909): sending alarm PendingIntent{42a6fed8: PendingIntentRecord{42bb5b50 com.google.android.gms startService}}, i=null, t=0, cnt=17069, w=84918423, Int=84918423
,I/ActivityManager(  909): Resuming delayed broadcast
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1201/10028)
,I/AdsMeasurementBroadcastReceiver( 1201): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1201): Unauthorized to start the main service
,D/SnetService( 1201): snet destroyed
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 1201): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/PMS     (  909): acquireWL(428deeb8): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/PMS     (  909): releaseWL(428deeb8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 1201): CP2 sync disabled
,I/jxcore-log( 3195): getBuffer is called!!!!
I/jxcore-log( 3195): 
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1201, uid=10028, userID:0
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3437 uid=10031 gids={50031, 3003, 5012}
,I/SensorManager(  909): mEventCount = 450
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
,D/PMS     (  909): releaseHCC(42a3a888): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(42b116b8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/ActivityManager(  909): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,D/Process (  909): killProcessQuiet, pid=3183
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 3183:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/[PluginManager]RegisterService( 1376): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1376): handle notify Blinkfeed plugin client changed
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Recipient 3183
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3453 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3453, uid=10073, userID:0
,D/Finsky  ( 3453): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  909): getAllNetworkInfo called by com.android.vending (3453/10073)
,D/ConnectivityService(  909): getAllNetworkInfo called by com.android.vending (3453/10073)
,D/Finsky  ( 3453): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3453): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3453): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3453, uid=10073, userID:0
,D/Process (  909): killProcessQuiet, pid=3207
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1249): action: android.intent.action.PACKAGE_ADDED
,D/Finsky  ( 3453): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3453): [1] 2.run: Finished loading 1 libraries.
I/ActivityManager(  909): Killing 3207:com.htc.contacts/u0a41 (adj 15): empty #17
,I/IcingCorporaProvider( 2683): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Finsky  ( 3453): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  909): Delaying start of: ServiceRecord{42a9d950 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,D/PMS     (  909): acquireWL(42aba260): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/PMS     (  909): releaseWL(42aba260): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(428e8d90): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3207
,D/PMS     (  909): releaseWL(428e8d90): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(426c7908): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/PMS     (  909): releaseWL(426c7908): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(422c66f0): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/PMS     (  909): releaseWL(422c66f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(4212ff58): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/PMS     (  909): releaseWL(4212ff58): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(4200f420): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/Process (  909): killProcessQuiet, pid=3231
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3231:com.htc.calendar/u0a13 (adj 15): empty #17
D/PMS     (  909): releaseWL(4200f420): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  909): Recipient 3231
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(42504e30): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/Finsky  ( 3453): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PMS     (  909): releaseWL(42504e30): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3490 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  909): acquireWL(42969670): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/PMS     (  909): releaseWL(42969670): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(4273ed70): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/PMS     (  909): releaseWL(4273ed70): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/DeviceManagement( 3490): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3490 dbg=false s=true
I/DeviceManagement( 3490): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3503 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=2958
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 2958:com.android.settings:remote/1000 (adj 15): empty #17
D/PMS     (  909): acquireWL(4278b910): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
D/PMS     (  909): releaseWL(4278b910): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 2958
,D/PMS     (  909): acquireWL(427a1be8): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/PMS     (  909): releaseWL(427a1be8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2683): Copying FileAsset 0x6369e410 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2683): UpdateCorporaTask done [took 438 ms] updated apps [took 438 ms] 
,I/SocialFeedProvider( 1249): +disConnect socialManager
,I/SocialFeedProvider( 1249): disconnect socialManager
,W/GAV2    ( 3503): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SocialFeedProvider( 1249): -disConnect socialManager
I/ActivityManager(  909): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3523 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/AlarmManager(  909): sending alarm PendingIntent{41edb390: PendingIntentRecord{41edb358 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1449497277804, Int=0
,I/SocialManager[SocialBiLogHelper]( 3339): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3339): last commit ulog time 1449467994035
,I/SocialManager[SocialBiLogHelper]( 3339): skip commit this time
,D/PMS     (  909): releaseWL(42ad59d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/htcbackup-core( 3523): ModelRegistry: Loading model meta data from resources...
,V/AlarmManager(  909): sending alarm PendingIntent{427b4210: PendingIntentRecord{42ba2550 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449497277900, Int=0
,W/ContextImpl( 3523): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3490): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3490): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.drive.activator, com.htc.htcpowermanager, com.qualcomm.privinit, com.android.keychain, com.htc.android.htcloglevel, com.android.settings, com.htc.smartdim, com.htc.feedback, com.android.location.fused, com.htc.mirrorlinkserver, com.htc.backupreset, com.qualcomm.timeservice, com.htc.autobot.cargps.provider, com.htc.cirmodule, com.htc.lockscreen, com.htc.guide, com.htc.backup, android, com.android.CSDFunctionG, com.htc.checkinprovider, com.android.inputdevices, com.htc.android.htcsetupwizard, com.htc.usage, com.htc.home.personalize, com.android.providers.settings]
,I/DeviceManagement( 3490): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/ActivityManager(  909): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3544 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/DeviceManagement( 3490): WorkflowService: Starting workflow service
,I/DeviceManagement( 3490): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41ec9640] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3490): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3490): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3490): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3490): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3544):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  909): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,W/GLSUser ( 1343): GoogleAccountDataService.getToken()
,I/GoogleHttpClient( 1343): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1343): Using GMS GoogleHttpClient
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1343): GoogleAccountDataService.getToken()
I/ActivityManager(  909): Resuming delayed broadcast
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  909): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3559 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,W/GAV2    ( 3503): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/Process (  909): killProcessQuiet, pid=3283
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3283:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3283
,W/Finsky  ( 3453): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/DeviceManagement( 3490): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Finsky  ( 3453): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/DeviceManagement( 3490): SessionStateController: Checking invariants...
,I/DeviceManagement( 3490): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3490): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41ec9640]
,I/DeviceManagement( 3490): WorkflowService: Stopping workflow service
,D/Process (  909): killProcessQuiet, pid=3312
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3312:com.htc.stock/u0a81 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3312
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(42ae40f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3559 10160 null
,D/PMS     (  909): releaseWL(42ae40f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  909): acquireWL(42ae6c00): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3559 10160 null
,D/PMS     (  909): acquireWL(4286e7b8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3559 10160 null
,D/PMS     (  909): releaseWL(42ae6c00): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3587 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (3559/10160)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (3559/10160)
,D/Settings:HtcWirelessFeatureFlags( 3403): id/is att sku: 99/false
,W/SystemReader( 3403): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3403): Cannot find support_harman, use default value instead
,W/SystemReader( 3403): Cannot find effect_manager_id, use default value instead
,D/Process (  909): killProcessQuiet, pid=3326
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  909): releaseWL(4286e7b8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  909): Killing 3326:com.htc.stock:remote/u0a81 (adj 15): empty #17
,E/Settings:HtcWrapHeaderInfo( 3403): no such activity!
,I/ActivityManager(  909): Recipient 3326
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3403): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3403): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3403): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportRecentAppsButton]support         :false
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportHomeButton]support         :false
,W/FingerprintManager( 3403): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,W/GLSUser ( 1343): GoogleAccountDataService.getToken()
,E/Settings:HtcVoWifiWidgetEnabler( 3403): isSupportVoWifi: null
,D/PowerUsageService( 3587): call getInstance()
I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3403): Failed to find provider info for com.htc.vowifi
W/ContextImpl( 3587): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PowerUsageList:PowerUsageHelper( 3587): MY_DEBUG = false
,D/PMS     (  909): acquireWL(42b6d118): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3587 1000 null
W/WeatherUtility( 1110): can't get weather sync account
D/WeatherUtility( 1376): Weather sync is On
,D/WSP     ( 1376): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,W/Finsky  ( 3453): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3453): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3453): [1] DailyHygiene.reschedule: Giving up. (failures=6)
I/ActivityManager(  909): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
W/WeatherUtility( 3262): can't get weather sync account
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3403): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3403): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 3403): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3403): [supportHomeButton]support         :false
,W/FingerprintManager( 3403): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3403): isSupportVoWifi: null
I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3403): Failed to find provider info for com.htc.vowifi
,W/WeatherRequest( 3262): request cur loc, but there is no sys cur
,W/Settings( 3262): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1249): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1249): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1249): com.htc.widget.weatherclock 1 9 17
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3610 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,D/Process (  909): killProcessQuiet, pid=3080
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3080:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3080
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/HtcModeClient( 1471): handler message = 4011
,E/HtcModeClient( 1471): Check connection and retry 6 times.
,V/AlarmManager(  909): sending alarm PendingIntent{4286bbb8: PendingIntentRecord{429d3e70 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1449497279637, Int=0
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3627 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=3093
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3093:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/Process (  909): killProcessQuiet, pid=3297
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3297:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3093
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3297
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{427a5a48 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/MusicStore( 3627): Database version: 95
,W/ContextImpl( 3627): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3627): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3627): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3627): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3627): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3627, uid=10154, userID:0
,V/AlarmManager(  909): sending alarm PendingIntent{42490988: PendingIntentRecord{4248fa58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=59540, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,I/ClockThread( 1110): now=1449497280005 next=59995
D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
D/MediaRouterService(  909): Client com.google.android.music (pid 3627): Registered
,I/MediaRouter( 3627): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
,I/ActivityManager(  909): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3646 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.music (3627/10154)
,D/MediaRouter( 3627): getSelectedRoute
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3627, uid=10154, userID:0
,D/Process (  909): killProcessQuiet, pid=3153
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/DFPI.PIReciver( 3646): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  909): Killing 3153:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/DFPI.ApkInstallService( 3646): onHandleIntent
,I/DFPI.ApkInstallService( 3646): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 3646): check CID = HTC__032
,I/DFPI.ApkInstallService( 3646): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  909): Recipient 3153
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3662 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  909): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3677 uid=10080 gids={50080, 5001, 1028, 1015}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.musicenhancer (3662/10051)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3662): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/SoundPicker( 3677): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3677): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3677): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3677): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3677): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3677): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  909): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3677): MODE_GSM access default DB
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3677): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3677): MODE_GSM access default DB
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Killing 3358:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=3358
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/DFPI.PIReciver( 3646): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3646): onHandleIntent
,I/DFPI.ApkInstallService( 3646): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3646): check CID = HTC__032
,I/DFPI.ApkInstallService( 3646): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  909): Recipient 3358
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Resuming delayed broadcast
,I/SoundPicker( 3677): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3677): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3677): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  909): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3677): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3677): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3677): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3677): MODE_GSM access default DB
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
,I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3677): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3677): MODE_GSM access default DB
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/PMS     (  909): releaseWL(42b6d118): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 3646): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3646): onHandleIntent
,I/DFPI.ApkInstallService( 3646): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3646): check CID = HTC__032
,I/DFPI.ApkInstallService( 3646): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/SoundPicker( 3677): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3677): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3677): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3677): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3677): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3677): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3677): MODE_GSM access default DB
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3677): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3677): MODE_GSM access default DB
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  909): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.fla,c
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3627): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=3701 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  909): Delay finish: com.htc.task/.TodoTaskReceiver
,D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  909): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  909): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 0
W/Settings:Agent(  909): >> traceCallingStack()
,W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 919
W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
,W/Settings:Agent(  909): 
W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  909): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  909): 
,W/Settings:Agent(  909): << traceCallingStack(): 7(ms)
,D/BluetoothManagerService(  909): Message: MESSAGE_DISABLE
,D/WifiManager( 3195): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
,W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  909): Settings:Agentname: wifi_on
D/WifiService(  909): New client listening to asynchronous messages
D/WifiService(  909): setWifiEnabled: false pid=3195, uid=10355
E/WifiService(  909): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  909): isSprintWifiRestricted(): false
I/WifiService(  909): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  909): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 0
W/Settings:Agent(  909): >> traceCallingStack()
W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 1103
W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  909): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  909): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  909): 
W/Settings:Agent(  909): << traceCallingStack(): 4(ms)
I/jxcore-log( 3195): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3195): 
I/ActivityManager(  909): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3715 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/TelephonyReceiver( 1224): bind: true
,D/Process (  909): killProcessQuiet, pid=2568
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/DFPI.PIReciver( 3646): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 2568:com.htc.sense.mms/u0a64 (adj 15): empty #17
I/ActivityManager(  909): remove PR=com.htc.sense.mms/.util.GenericMessagesProvider oop
I/ActivityManager(  909): Remove died provider record at: com.htc.sense.mms(2568)
I/DFPI.ApkInstallService( 3646): onHandleIntent
,I/DFPI.ApkInstallService( 3646): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3646): check CID = HTC__032
,I/DFPI.ApkInstallService( 3646): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Recipient 2568
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Start proc com.htc.sense.mms for restart com.htc.sense.mms: pid=3731 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/SoundPicker( 3677): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3677): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3677): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3677): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3677): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3677): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3677): MODE_GSM access default DB
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3677): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3677): MODE_GSM access default DB
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  909): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/MessageFrequencyProvider( 3731): onCreate
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,V/GetPrviateResource( 3731): GetPrviateResource
,V/GetPrviateResource( 3731): GetPrviateResource
,D/GenericMessagesProvider( 3731): query uri: content://htc-messages/wappush/count
,E/SQLiteLog( 3731): (14) cannot open file at line 30190 of [00bb9c9ce4]
,E/SQLiteLog( 3731): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3677): getActualDefaultRingtoneUri(context, 4)
E/SQLiteConnection( 3731): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 3731): DB info: errno = 2, errno message = No such file or directory
,I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/EASAppSvc( 3715): [ NA ]- onCreate()
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
E/SQLiteDatabase( 3731): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 3731): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 3731): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 3731): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3731): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3731): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 3731): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 3731): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 3731): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 3731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 3731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 3731): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
,W/System.err( 3731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 3731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 3731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 3731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 3731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 3731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 3731): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 3731): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 3731): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
,W/System.err( 3731): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 3731): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err( 3731): 	at dalvik.system.NativeStart.run(Native Method)
,D/TelephonyReceiver( 1224): switchBindHtcMsgCursor: null
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/EASAppSvc( 3715): [ NA ]> onUpgrade: version = 63
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,D/ORMLib  ( 3701): put()
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3677): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3677): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3677): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/Process (  909): killProcessQuiet, pid=3384
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3384:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3384
D/WifiService(  909): Client connection lost with reason: 4
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/WifiService(  909): New client listening to asynchronous messages
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.android.mail (3715/10063)
I/EASAppSvc( 3715): [ NA ]- onDestroy()
,D/MessageCustFlag( 3731): sense_version=6.0
I/EASAppSvc( 3715): [ NA ]> uninitEASService
,D/BTAccessoryUtil( 3731): createReceiver
,D/BTAccessoryUtil( 3731): registerReceiver return intent = null
D/MessageCustFlag( 3731): sku_id=99
,W/SystemReader( 3731): Cannot find message_ambs_application_id, use default value instead
D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.htc.android.mail (3715/10063)
D/ConnectivityService(  909): getNetworkInfo networkType=55 called by com.htc.android.mail (3715/10063)
,D/Messaging( 3731): supportCMAS(SIE)/init? false/true
D/MmsConfig( 3731): networkCode: 
,D/MessageCustFlag( 3731): sku_id=99
D/MmsConfig( 3731): SIE smsPri: null
,D/MmsConfig( 3731): networkCode: 
,D/HtcTelephonyCapability( 3731): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 3731): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 3731): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3731): Cannot find qct_8960_interface, use default value instead
,I/MediaStoreImporter( 3627): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): acquireWL(4286c7a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
,D/PMS     (  909): releaseWL(4286c7a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  909): acquireWL(421398d8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1471 10014 null
,I/ActivityManager(  909): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  909): releaseWL(421398d8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3760 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/Process (  909): killProcessQuiet, pid=3437
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/TelephonyReceiver( 1224): bind: false
,D/TelephonyReceiver( 1224): switchBindHtcMsgCursor: null
I/ActivityManager(  909): Killing 3437:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3437
,I/ActivityManager(  909): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3773 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,E/cutils-trace( 3744): Error opening trace file: No such file or directory (2)
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/EASRequestController( 3715): [ NA ]release
,I/EASAppSvc( 3715): [ NA ]< uninitEASService
,I/EASAppSvc( 3715): [ NA ]- onCreate()
,I/EASAppSvc( 3715): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.android.mail (3715/10063)
D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.htc.android.mail (3715/10063)
D/ConnectivityService(  909): getNetworkInfo networkType=55 called by com.htc.android.mail (3715/10063)
,D/ORMLib  ( 3701): put()
,W/GAV2    ( 3773): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/EASAppSvc( 3715): [ NA ]- onDestroy()
,I/EASAppSvc( 3715): [ NA ]> uninitEASService
,I/EASRequestController( 3715): [ NA ]release
,I/ActivityManager(  909): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3808 uid=10067 gids={50067, 3003, 5012}
I/EASAppSvc( 3715): [ NA ]< uninitEASService
,I/ActivityManager(  909): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  909): acquireWL(42886520): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/PMS     (  909): releaseWL(42886520): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/CustomizationManager( 3744): ====startRecUseTime====
D/htc.customization.log.level( 3744):  is 
,W/CustomizationLogLevel( 3744): Level value is invalid, use default level 2
,D/Process (  909): killProcessQuiet, pid=3503
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3503:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/ORMLib  ( 3701): put()
,D/Process (  909): killProcessQuiet, pid=3523
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3523:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  909): Recipient 3503
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(42bb0d80): PARTIAL_WAKE_LOCK  Icing 0x1 1201 10028 null
,D/PMS     (  909): releaseWL(42bb0d80): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/CustomizationManager( 3744):  Read ACC file spent 0.065 (s)
,D/CIDMapFileReader( 3744): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3744): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3744): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3744): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3744): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3744): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3744): Parsing tag item name = HTC__016
,I/Gmail   ( 3773): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/CIDMapFileReader( 3744): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3744): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3744): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3744): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3744): Parsing tag category name = system
I/CustomizationCIDLoader( 3744): Parsing tag category name = application
,I/CustomizationCIDLoader( 3744): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3744): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3744): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3744): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3744): Parsing tag category name = Settings
D/CustomizationManager( 3744):  Read CID file spent 0.109 (s)
I/Gmail   ( 3773): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/CustomizationManager( 3744):  All configurations done spent 0.109 (s)
W/HtcNativeFlag( 3744): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3744): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3744): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3744): Fail to get flag for type 'language', use default value: -1
,D/DotMatrix( 1524): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/Gmail   ( 3773): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/NotificationService(  909): notification sound not played, stream=5 volume=0 always=false,
I/Gmail   ( 3773): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/RemoteViews( 1110): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41ed8148 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.htc.updater 2 10 1 10
,I/RemoteViews( 1110): com.htc.updater (true,33751552)
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3523
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41fdb660 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.htc.updater 1 7 0 10
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gm/.GmailReceiver
,D/PackageManager(  909): deletePackageAsUser: pkg=com.example.hello, pid=3744, uid=2000 user=0
,I/ActivityManager(  909): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,D/Process (  909): killProcessQuiet, pid=3195
,W/asset   (  909): Copying FileAsset 0x6c50b258 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/ActivityManager(  909): Killing 3195:com.example.hello/u0a355 (adj 0): stop com.example.hello
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  909): handleTopAppChanged(): The previous AP is died unexpectedly.
W/ActivityManager(  909): Force removing ActivityRecord{42a3a918 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/PackageSettings(  909): Skipping PackageSetting{42629060 com.test.thalitest/10348} due to missing metadata
,D/AutoSetting( 1376): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1376): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1376): service - requestNLP() NetworkLocationProvider not enabled
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  909): channel '426e9f60 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  909): channel '426e9f60 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  909): Attempted to unregister already unregistered input channel '426e9f60 com.example.hello.MainActivity (s)'
D/WifiService(  909): Client connection lost with reason: 4
I/WindowState(  909): WIN DEATH: Window{426e9f60 u0 com.example.hello/com.example.hello.MainActivity}
I/WindowManager(  909): WINDOW DIED Window{426e9f60 u0 com.example.hello/com.example.hello.MainActivity}
,I/FeedHostManager( 1249): [onResume]
,I/FeedProviderManager( 1249): onResume
,I/SocialFeedProvider( 1249): +onResume
I/ConnectivityHelper( 1249): [getCurrentConnectionType] no network connection
,I/SocialFeedProvider( 1249): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1249): -onResume
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.launcher (1249/10075)
,I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
I/acms    ( 1775): Unregistering com.example.hello
,E/acms    ( 1775): Could not unregister removed application com.example.hello
W/GeofencerStateMachine( 1408): Ignoring removeGeofence because network location is disabled.
,D/DotMatrix( 1524): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
I/Prism.ItemManager( 3339): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3339): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/DotMatrix( 1524): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1524): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
D/PMS     (  909): acquireWL(42bbfdd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1408 10028 null
,D/PMS     (  909): releaseWL(42bbfdd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1304): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1304): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  909): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gm/.GmailReceiver
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,D/AccTypeManager( 1304): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/NotifUtils( 3773): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,W/SystemReader( 1235): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,E/ExternalAccountType( 1304): Unsupported attribute readOnly
,I/NotifUtils( 3773): validateNotifications - cancelling account 61035162 / folder -317575340
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,D/PhoneApp( 1224): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/Process (  909): killProcessQuiet, pid=3339
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 3339:com.htc.sense.news/u0a75 (adj 15): empty #17
I/ActivityManager(  909): Delay finish: com.google.android.gms/.playlog.uploader.UploaderAlarmReceiver
,I/ActivityManager(  909): Recipient 3339
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 3195 uid 10355
,W/Binder  ( 1186): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1186): java.lang.NullPointerException
W/Binder  ( 1186): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1186): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1186): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1186): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  909): Enable input method client, pid=1249
,V/AlarmManager(  909): sending alarm PendingIntent{41ed4db0: PendingIntentRecord{428bb710 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1449497282088, Int=0
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3859 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/PackageManager(  909): Unable to load service info ResolveInfo{42a540c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
,I/Babel   ( 3859): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3859): MmsConfig.loadMmsSettings
,E/dalvikvm( 3859): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 3859): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 3859): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 3859): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 3859): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/MmsCustomizationProvider( 3731): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3731): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3859): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3859): MmsConfig.loadFromDatabase
,E/SQLiteDatabase( 3859): Failed to open database '/data/data/com.google.android.talk/databases/apn.db'.
E/SQLiteDatabase( 3859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3859): 	at cr.dT(SourceFile:414)
E/SQLiteDatabase( 3859): 	at cr.e(SourceFile:384)
E/SQLiteDatabase( 3859): 	at cs.run(SourceFile:211)
,W/dalvikvm( 3859): threadid=13: thread exiting with uncaught exception (group=0x41a5ae30)
,E/ActivityManager(  909): App crashed! Process: com.google.android.talk
E/AndroidRuntime( 3859): FATAL EXCEPTION: Thread-404
E/AndroidRuntime( 3859): Process: com.google.android.talk, PID: 3859
E/AndroidRuntime( 3859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3859): 	at cr.dT(SourceFile:414)
E/AndroidRuntime( 3859): 	at cr.e(SourceFile:384)
E/AndroidRuntime( 3859): 	at cs.run(SourceFile:211)
,E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3859, uid=10111, userID:0
,W/Settings( 3859): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3859, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3859, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3859, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3859, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3859, uid=10111, userID:0
D/PMS     (  909): acquireWL(42875360): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3859 10111 null
I/ActivityManager(  909): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,E/SQLiteDatabase( 3859): Failed to open database '/data/data/com.google.android.talk/databases/babel1.db'.
E/SQLiteDatabase( 3859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.content.ao.getWritableDatabase(SourceFile:3088)
E/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.content.ao.hW(SourceFile:3108)
E/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.content.t.<init>(SourceFile:297)
E/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.phone.cn.run(SourceFile:328)
E/SQLiteDatabase( 3859): 	at java.lang.Thread.run(Thread.java:864)
W/Babel   ( 3859): [EsDatabaseHelper] getWritableDatabase threw exception: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/dalvikvm( 3859): threadid=15: thread exiting with uncaught exception (group=0x41a5ae30)
,E/Babel   ( 3859): Uncaught exception in background thread Thread[Thread-408,5,main]
,E/Babel   ( 3859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/Babel   ( 3859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/Babel   ( 3859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/Babel   ( 3859): 	at com.google.android.apps.babel.content.ao.getWritableDatabase(SourceFile:3088)
E/Babel   ( 3859): 	at com.google.android.apps.babel.content.ao.hW(SourceFile:3108)
E/Babel   ( 3859): 	at com.google.android.apps.babel.content.t.<init>(SourceFile:297)
E/Babel   ( 3859): 	at com.google.android.apps.babel.phone.cn.run(SourceFile:328)
E/Babel   ( 3859): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 3859): Failed to open database '/data/data/com.google.android.talk/databases/babel1.db'.
E/SQLiteDatabase( 3859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.content.ao.getWritableDatabase(SourceFile:3088)
E/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.content.ao.hW(SourceFile:3108)
E/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.service.au.<init>(SourceFile:101)
E/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.service.au.aV(SourceFile:65)
E/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.phone.EsApplication.L(SourceFile:607)
E/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.realtimechat.bn.a(SourceFile:187)
E,/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.realtimechat.bn.a(SourceFile:165)
E/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.realtimechat.RealTimeChatService.t(SourceFile:3147)
E/SQLiteDatabase( 3859): 	at com.google.android.apps.babel.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:691)
E/SQLiteDatabase( 3859): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3859): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3859): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3859): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Babel   ( 3859): [EsDatabaseHelper] getWritableDatabase threw exception: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/dalvikvm( 3859): threadid=14: thread exiting with uncaught exception (group=0x41a5ae30)
,E/Babel   ( 3859): Uncaught exception in background thread Thread[IntentService[RealTimeChatService],5,main]
,E/Babel   ( 3859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/Babel   ( 3859): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/Babel   ( 3859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/Babel   ( 3859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/Babel   ( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/Babel   ( 3859): 	at com.google.android.apps.babel.content.ao.getWritableDatabase(SourceFile:3088)
E/Babel   ( 3859): 	at com.google.android.apps.babel.content.ao.hW(SourceFile:3108)
E/Babel   ( 3859): 	at com.google.android.apps.babel.service.au.<init>(SourceFile:101)
E/Babel   ( 3859): 	at com.google.android.apps.babel.service.au.aV(SourceFile:65)
E/Babel   ( 3859): 	at com.google.android.apps.babel.phone.EsApplication.L(SourceFile:607)
E/Babel   ( 3859): 	at com.google.android.apps.babel.realtimechat.bn.a(SourceFile:187)
E/Babel   ( 3859): 	at com.google.android.apps.babel.realtimechat.bn.a(SourceFile:165)
E/Babel   ( 3859): 	at com.google.android.apps.babel.realtimechat.RealTimeChatService.t(SourceFile:3147)
E/Babel   ( 3859): 	at com.google.android.apps.babel.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:691)
E/Babel   ( 3859): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Babel   ( 3859): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Babel   ( 3859): 	at android.os.Looper.loop(Looper.java:157)
E/Babel   ( 3859): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime_2_crash( 3859): crash in the same process: Thread-408
E/AndroidRuntime_2_crash( 3859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 3859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime_2_crash( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime_2_crash( 3859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 3859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime_2_crash( 3859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime_2_crash( 3859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime_2_crash( 3859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime_2_crash( 3859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime_2_crash( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime_2_crash( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime_2_crash( 3859): 	at com.google.android.apps.babel.content.ao.getWritableDatabase(SourceFile:3088)
E/AndroidRuntime_2_crash( 3859): 	at com.google.android.apps.babel.content.ao.hW(SourceFile:3108)
E/AndroidRuntime_2_crash( 3859): 	at com.google.android.apps.babel.content.t.<init>(SourceF,ile:297)
E/AndroidRuntime_2_crash( 3859): 	at com.google.android.apps.babel.phone.cn.run(SourceFile:328)
E/AndroidRuntime_2_crash( 3859): 	at java.lang.Thread.run(Thread.java:864)
,I/ProviderInstaller( 3859): Installed default security provider GmsCore_OpenSSL
E/AndroidRuntime_3_crash( 3859): crash in the same process: IntentService[RealTimeChatService]
E/AndroidRuntime_3_crash( 3859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 3859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime_3_crash( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime_3_crash( 3859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 3859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime_3_crash( 3859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime_3_crash( 3859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime_3_crash( 3859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime_3_crash( 3859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime_3_crash( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime_3_crash( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime_3_crash( 3859): 	at com.google.android.apps.babel.content.ao.getWritableDatabase(SourceFile:3088)
E/AndroidRuntime_3_crash( 3859): 	at com.google.android.apps.babel.content.ao.hW(SourceFile:3108)
E/AndroidRuntime_3_crash( 3859): 	at com.google.android.apps.babel.service.au.<init>(SourceFile:101)
E/AndroidRuntime_3_crash( 3859): 	at com.google.android.apps.babel.service.au.aV(SourceFile:65)
E/AndroidRuntime_3_crash( 3859): 	at com.google.android.apps.babel.phone.EsApplication.L(SourceFile:607)
E/AndroidRuntime_3_crash( 3859): 	at com.google.android.apps.babel.realtimechat.bn.a(SourceFile:187)
E/AndroidRuntime_3_crash( 3859): 	at com.google.android.apps.babel.realtimechat.bn.a(SourceFile:165)
E/AndroidRuntime_3_crash( 3859): 	at com.google.android.apps.babel.realtimechat.RealTimeChatService.t(SourceFile:3147)
E/AndroidRuntime_3_crash( 3859): 	at com.google.android.apps.babel.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:691)
E/AndroidRuntime_3_crash( 3859): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime_3_crash( 3859): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime_3_crash( 3859): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime_3_crash( 3859): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,W/AtomicFile(  909): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  909): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/Messaging( 3731): mNeedToUpdateDate2 start
,D/MmsConfig( 3731): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 3731): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3731): 
D/MmsAsyncWorkHandler( 3731): HM tk = 20001
,D/ReportIndicatorCache( 3731): MSG_QUERY_REPORTS >>
,D/SettingsManager( 3731): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41e92440
,I/Messaging( 3731): mccmnc> 
,D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1224):  phoneType = -1
,D/DraftCache( 3731): [DraftCache/1] DraftCache.constructor
D/DraftCache( 3731): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1224): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 3731): networkCode: 
,D/Messaging( 3731): ViewCache CreatePreloadOnlyConversationList
,D/PhoneStorageUtil( 3731): HtcWrapEnvironment.getSupportedStorages() >1
,D/PhoneStorageUtil( 3731): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 3731): createReceiver
,D/MessageCustFlag( 3731): sense_version=6.0
,D/Jerry   ( 3731): start to preload cursor >>>>>>>
,D/TelephUtils( 1224): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
V/MmsProvider( 1224): Update uri=content://mms, match=0
,V/MmsProvider( 1224): selection=st=129 AND m_type!=134
D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1224):  phoneType = -1
,D/MmsSmsV2Provider( 1224): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 3731): Reset downloading state: 0
,V/MmsSystemEventReceiver( 3731): TransactionService is going to be woken up.
,D/Messaging( 3731): mNeedToUpdateDate2: false
I/ActivityManager(  909): Delaying start of: ServiceRecord{42782850 u0 com.htc.sense.mms/.transaction.TransactionService}
,D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1224):  phoneType = -1
,D/Messaging( 3731): ViewCache CreatePreload
,D/Messaging( 3731): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 3731): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 3731): def_index: 0
,D/MsgPreferenceUtils( 3731): globalIndex = 1
,D/MsgPreferenceUtils( 3731): phone state: true
D/MsgPreferenceUtils( 3731): sd state: false
,D/MsgPreferenceUtils( 3731): vIndex = 0
,D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1224):  phoneType = -1
,D/MmsSmsV2Provider( 1224): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1224): sku_id=99
,D/DraftCache( 3731): [DraftCache/382] rebuildCache
D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1224):  phoneType = -1
,D/MmsSmsV2Provider( 1224): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 3731): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/Jerry   ( 1224): URI_DRAFT
,D/DraftCache( 3731): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 3731): [DraftCache/382] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 3731): 
D/MmsAsyncWorkHandler( 3731): HM tk = 20002
,D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1224): sku_id=99
,D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1224): sku_id=99

```
