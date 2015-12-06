#### Test 50242285576d0b0_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/YouTube ( 3034): apps.youtube.datalib.d.b.a:91 Sending from HTTP204 service
D/YouTube ( 3034): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.d with ScheduledExecutorService for repeating execution.
--------- beginning of /dev/log/system
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (3034/10168)
D/YouTube ( 3034): apps.youtube.datalib.offline.b.run:89 Queuing stored offline request.
,D/MediaRouter( 3034): getSelectedRoute
D/YouTube ( 3034): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (3034/10168)
W/BroadcastQueue(  907): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
D/AutoSetting( 1390): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 2992): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2992): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2992): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2992): Cust_ConnectToPC   : spcsc>false
D/        ( 2992): Cust_ConnectToPC   : IPT>true
D/        ( 2992): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2992): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2992): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2992): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2992): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PSReceiver( 2992): onReceive:android.intent.action.USER_PRESENT
D/AutoSetting( 1390): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/SmartNS_PSService( 2992): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 2992): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 2992): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2992):  defaultType:0
I/ActivityManager(  907): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3093 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
D/Process (  907): killProcessQuiet, pid=2794
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2794:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2794
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/browser ( 3093): Browser versionCode = 760001523 versionName = 7.0.2512153020
W/SWE_UI  ( 3093): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3093): Loading: swewebviewchromium
I/LibraryLoader( 3093): Time to load native libraries: 38 ms (timestamps 2272-2310)
I/LibraryLoader( 3093): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3093): Initializing chromium process, renderers=9
I/LibraryLoader( 3093): Expected native library version number "",actual native library version number ""
I/chromium( 3093): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
I/SensorManager(  907): mEventCount = 300
E/cutils-trace( 3090): Error opening trace file: No such file or directory (2)
W/chromium( 3093): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
I/Adreno-EGL( 3093): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3093): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3093): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3093): Local Branch: 
I/Adreno-EGL( 3093): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3093): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3093):                  aa63bbd948f41d15fc72f585e
D/Process (  907): killProcessQuiet, pid=2806
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
V/IccIntentReceiver( 1276): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  907): Killing 2806:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/SIMStateChangeReceiver( 1497): SIM state: ABSENT
I/SIMStateChangeReceiver( 1497): phoneType = 0
I/SIMStateChangeReceiver( 1497): remove notification
I/ActivityManager(  907): Recipient 2806
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 3090): ====startRecUseTime====
D/htc.customization.log.level( 3090):  is 
W/CustomizationLogLevel( 3090): Level value is invalid, use default level 2
I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3139 uid=10031 gids={50031, 3003, 5012}
W/PackageManager(  907): Unable to load service info ResolveInfo{424bf310 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
D/Process (  907): killProcessQuiet, pid=2838
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3151 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  907): Killing 2838:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2838
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 3090):  Read ACC file spent 0.089 (s)
D/CIDMapFileReader( 3090): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3090): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3090): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3090): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3090): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3090): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3090): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3090): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3090): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3090): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3090): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3090): Parsing tag category name = system
I/CustomizationCIDLoader( 3090): Parsing tag category name = application
I/CustomizationCIDLoader( 3090): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3090): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3090): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3090): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3090): Parsing tag category name = Settings
D/CustomizationManager( 3090):  Read CID file spent 0.147 (s)
D/CustomizationManager( 3090):  All configurations done spent 0.147 (s)
W/SystemReader( 2573): Cannot find message_ambs_application_id, use default value instead
W/HtcNativeFlag( 3090): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3090): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3090): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3090): Fail to get flag for type 'language', use default value: -1
D/SmsReceiver( 2573): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2573): onReceive()
D/ExchangePolicystatus( 2573): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2573): onReceive(): else
D/Process (  907): killProcessQuiet, pid=2184
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/HtcBroadcastReceiver( 1223): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  907): Killing 2184:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2184
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3166 uid=10038 gids={50038}
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3090
D/PMS     (  907): acquireHCC(424168a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
W/asset   (  907): Copying FileAsset 0x62a66f88 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1110541480
W/AccTypeManager( 3151): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3151): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): acquireHCC(42353ee0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
D/PMS     (  907): acquireWL(42552130): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1252): [onPause]
I/FeedProviderManager( 1252): onPause
I/FeedHostManager( 1252): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42309788
I/SocialFeedProvider( 1252): +onPause
I/SocialFeedProvider( 1252): -onPause
D/AccTypeManager( 3151): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3184 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3196 uid=10077 gids={50077}
D/Process (  907): killProcessQuiet, pid=2821
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2821:com.htc.cs.dm/u0a98 (adj 15): empty #17
W/asset   ( 3184): Copying FileAsset 0x5c7ab428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
E/ExternalAccountType( 3151): Unsupported attribute readOnly
D/SMSBackup( 3196): Got a database change event
D/Process (  907): killProcessQuiet, pid=2890
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
V/WebViewChromiumFactoryProvider( 3184): Binding Chromium to main looper Looper (main, tid 1) {41b250c8}
I/LibraryLoader( 3184): Expected native library version number "",actual native library version number ""
I/chromium( 3184): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3184): Initializing chromium process, renderers=0
I/ActivityManager(  907): Killing 2890:com.google.android.talk/u0a111 (adj 15): empty #17
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1252): loadItems() com.htc.launcher.pageview.WidgetManager@41bb5010 +
I/Prism.WidgetManager( 1252): onLoadItems() +
I/ActivityManager(  907): Recipient 2890
D/GCM     ( 1342): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/WeatherUtility( 1111): can't get weather sync account
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AccTypeManager( 3151): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3151): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): acquireWL(420a6698): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(4254ce20): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): releaseWL(420a6698): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4257e7d8:true
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3184): 1102293672: getState() :  mService = null. Returning STATE_OFF
D/AccTypeManager( 3151): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Adreno-EGL( 3184): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3184): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3184): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3184): Local Branch: 
I/Adreno-EGL( 3184): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3184): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3184):                  aa63bbd948f41d15fc72f585e
I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3219 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
W/WeatherRequest( 1111): request cur loc, but there is no sys cur
I/ActivityManager(  907): Recipient 2821
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ExternalAccountType( 3151): Unsupported attribute readOnly
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
W/chromium( 3184): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 3184): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3184): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/CalendarApplication( 3219): onCreate
D/ProviderChangeReceiver( 3219): ---------------------------------------------------
D/ProviderChangeReceiver( 3219): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3219): start to updateAlertNotification!
W/dalvikvm( 3184): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3184): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3184): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3184): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3184): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3184): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
W/ContextImpl( 2966): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/SystemWebViewEngine( 3184): CordovaWebView is running on device made by: HTC
D/AlertService( 3219): No fired or scheduled alerts
D/HtcAlertUtils( 3219): -- cancelReminderNotification --
D/HtcAlertUtils( 3219): broadcastExistReminder!
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/Process (  907): killProcessQuiet, pid=2865
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2865:com.htc.backup/1000 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2865
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
I/AdsMeasurementBroadcastReceiver( 1207): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1207): Unauthorized to start the main service
D/RemoteDisplayProvider(  907): start
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3252 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
W/AwContents( 3184): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1252
W/ResourceType( 3184): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3184): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b6be30, mServedView=org.apache.cordova.engine.SystemWebView{41b31dc8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3184): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Enable input method client, pid=3184
I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3266 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +375ms
D/PMS     (  907): releaseWL(42552130): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/WeatherUtility( 3252): can't get weather sync account
I/DemoRecovery.RestoreReceiver( 3266): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/ContextImpl( 3266): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/RestoreService( 3266): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  907): Resuming delayed broadcast
W/WeatherRequest( 3252): request cur loc, but there is no sys cur
W/Settings( 3252): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3282 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
D/Process (  907): killProcessQuiet, pid=2918
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2918:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2918
D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews( 1252): com.htc.widget.weatherclock (true,33751552)
I/RemoteViews.Performance( 1252): com.htc.widget.weatherclock 4 11 17
D/PMS     (  907): acquireWL(4251a5a8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3282 10070 null
D/PMS     (  907): acquireWL(4243e830): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3282 10070 null
D/PMS     (  907): releaseWL(4251a5a8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
I/TrimMemoryManager( 1252): [trimMemory] 20
D/TodoTaskshortcut( 3282): update TASK shortcut>
I/TodoTaskNotifyService( 3282): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): releaseWL(4243e830): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
W/NotifyReceiver( 3282): stopSelfResult true
D/Process (  907): killProcessQuiet, pid=2935
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3298 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  907): Killing 2935:com.htc.htccupd/u0a17 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2935
E/AndroidProtocolHandler( 3184): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3184): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/asset   ( 1252): Copying FileAsset 0x66736c28 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
E/Prism.WidgetManager( 1252): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1252): onLoadItems() -
I/Prism.ItemManager( 1252): loadItems() com.htc.launcher.pageview.WidgetManager@41bb5010 -
I/ActivityManager(  907): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3312 uid=10081 gids={50081, 3003, 5012}
D/JsMessageQueue( 3184): Set native->JS mode to OnlineEventsBridgeMode
D/Process (  907): killProcessQuiet, pid=2980
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 2980:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=2950
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/AdsMeasurementBroadcastReceiver( 1207): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1207): Unauthorized to start the main service
I/ActivityManager(  907): Killing 2950:com.zoodles.kidmode/u0a149 (adj 15): empty #18
I/ActivityManager(  907): Recipient 2980
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SMSBackup( 3196): Got a database change event
I/ActivityManager(  907): Recipient 2950
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3324 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
D/jxcore_app_log( 3184): JniHelper::setJavaVM(0x415fa048), pthread_self() = 1658878480
D/JX-Cordova( 3184): jxcore cordova android initializing
I/ImageRamCache( 3324): create image Cache, size: 31457280.
I/ImageRamCache( 3324): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3324): create image Cache, size: 12582912.
I/FeedSettings( 3324): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3324): GroupBudget 0.500000 0.380000
I/FeedSettings( 3324): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 3324): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 3324): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3324): loadGridSize() with Alternative
D/CustomHighlightReceiver( 3324): [custom highlight] onReceive
D/CustomHighlightService( 3324): [custom highlight] onHandleIntent
D/NewsDB  ( 3324): set custom highlight []
I/ActivityManager(  907): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
W/jxcore-log( 3184): Initializing JXcore engine
W/jxcore-log( 3184): JXcore engine is ready
W/jxcore-log( 3184): Starting JXcore engine
D/CustomHighlightService( 3324): [custom highlight] set tags 
D/Process (  907): killProcessQuiet, pid=3008
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/GCM     ( 1342): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3008:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  907): Resuming delayed broadcast
D/MessagingShortcutReceiver( 2573): keep hiding shortcut bubble
D/MessagingShortcut( 2573): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2573): After query: 0
D/MessagingShortcut( 2573): mPresentUnreadCount: -1
D/MessagingShortcut( 2573): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2573): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1585): [EventService] reorderNotification, total:1
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/ActivityManager(  907): Recipient 3008
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TodoTaskshortcut( 3282): update TASK shortcut>
D/HtcBroadcastReceiver( 1223): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3341 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  907): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
D/MessagingNotification( 2573): New incoming message, can't cancel notification now
D/MessagingNotification( 2573): newMsgCnt: 0, false
D/PhoneApp( 1223): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1223): -- N1 =0
D/PhoneApp( 1223): -- N2 =0
D/PhoneApp( 1223): -- N3 =0
I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3355 uid=10091 gids={50091, 3003, 5012}
D/ContactMessageStore( 1223): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1223): MSG_NOTIFY_CS_TO_SYNC <<
D/MdScBoot( 3341): [7d0.1.] 30@-150904 -> 40@-150933
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3367 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
D/Process (  907): killProcessQuiet, pid=3022
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/Process (  907): killProcessQuiet, pid=3034
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3022:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  907): Killing 3034:com.google.android.youtube/u0a168 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/jxcore-log( 3184): Platform android
W/jxcore-log( 3184): 
W/jxcore-log( 3184): Process ARCH arm
W/jxcore-log( 3184): 
I/ActivityManager(  907): Recipient 3022
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3034
D/MediaRouterService(  907): Client com.google.android.youtube (pid 3034): Died!
I/jxcore-log( 3184): JXcore Cordova bridge is ready!
I/jxcore-log( 3184): 
W/jxcore-log( 3184): JXcore engine is started
E/dalvikvm( 3367): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 3367): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 3367): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 3367): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
V/JNIHelp ( 3367): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
I/Babel   ( 3367): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3367): MmsConfig.loadMmsSettings
E/jxcore-log( 3184): >> HTC-HTC Desire 820
E/jxcore-log( 3184): 
I/jxcore-log( 3184): Total memory 1964650496
I/jxcore-log( 3184): 
I/jxcore-log( 3184): Free memory 713887744
I/jxcore-log( 3184): 
I/jxcore-log( 3184): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3184): 
I/jxcore-log( 3184): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3184): 
I/jxcore-log( 3184): userPath [ 'www' ]
I/jxcore-log( 3184): 
I/jxcore-log( 3184): Size 720 1184
I/jxcore-log( 3184): 
I/jxcore-log( 3184): Screen Brightness 10
I/jxcore-log( 3184): 
E/jxcore-log( 3184): Dummy Error Log.
E/jxcore-log( 3184): 
D/MmsCustomizationProvider( 2573): query uri: content://htc-mms-customization/mms-ua/ua_string
D/MmsCustomizationProvider( 2573): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3367): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 3367): MmsConfig.loadFromDatabase
E/Babel   ( 3367): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3367): MmsConfig.loadFromResources
E/Babel   ( 3367): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3367): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3367, uid=10111, userID:0
W/Settings( 3367): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3367, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3367, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3367, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3367, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3367, uid=10111, userID:0
D/Process (  907): killProcessQuiet, pid=2992
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/GCM     ( 1342): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  907): Killing 2992:com.android.settings/1000 (adj 15): empty #17
D/MtpReceiver( 2239): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2239): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2239): [MTP][handleMessage][startService]
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1758/10178)
I/ProviderInstaller( 3367): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3394 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/MtpReceiver( 2239): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2239): [MTP][handleMessage]-
D/MtpService( 2239): [MTP] startForeground
D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 2239): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2239): TotalSize=1918604,MediaCacheLimit=6000
D/MtpService( 2239): [isMtpConnected] connected: true
I/RemoteViews( 1111): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1111): com.android.providers.media 0 1 10
I/RemoteViews( 1111): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1111): com.android.providers.media 1 1 15
I/ActivityManager(  907): Recipient 2992
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SyncApplication( 3394): Loading default preferences
W/Resources( 3394): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/WifiService(  907): New client listening to asynchronous messages
D/SyncApplication( 3394): Overriding preferences with custom values
D/SyncApplication( 3394): Updating preferences succeeded
E/SyncApplication( 3394): Application created.
D/VolumeInfo( 3394): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3394): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3394): Found 0 mount point(s)
V/VolumeInfo( 3394): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 3394): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 3394): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 3394): Can not create volume ID for unmounted volume null
I/CalendarDefines( 3394): getNewCalendarAuthority()...
D/SyncApplication( 3394): enableAppOperation()+
D/SyncApplication( 3394): enableAppOperation()-
D/HTCUtilities( 3394): isNeorSinged() + 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3394, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3394, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3394): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 3394): isNeorSinged() return false
D/CDMountReceiver( 3394): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3394): USB connected to PC
D/FOTAReceiver( 3394): onReceive() enter 
D/FOTAReceiver( 3394): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3413 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  907): killProcessQuiet, pid=3093
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3093:com.htc.sense.browser/u0a12 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3139
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3139:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3139
D/HtcFingerPrintQuickLaunchProvider( 3413): -onCreate()
V/Settings:HtcSettingsApplication( 3413): [3413/3413] onCreate()
D/TetherSettings( 3413): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3413): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3413): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3413): Cust_ConnectToPC   : spcsc>false
D/        ( 3413): Cust_ConnectToPC   : IPT>true
D/        ( 3413): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3413): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3413): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3413): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3413): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3413): Cust_ConnectToPC   : spcsc>false
D/        ( 3413): Cust_ConnectToPC   : IPT>true
D/        ( 3413): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3413): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3413): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3413): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3413): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3413): usb_cable_connect = 1
D/SmartNS_Utility( 3413): usb_denied = 0
I/SmartNS_NSReceiver( 3413): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3413): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 3413): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 3413): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3413): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3413): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3413):  defaultType:0
I/SmartNS_PSService( 3413): fail notificaiton:false
D/SmartNS_Utility( 3413): usb_cable_connect = 1
D/SmartNS_Utility( 3413): usb_denied = 0
I/SmartNS_PSService( 3413): usb notificaiton:true
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3093
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  907): bSetPropertyMultiRAB:false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3413/1000)
D/SmartNS_Utility( 3413): usb_cable_connect = 1
D/SmartNS_Utility( 3413): usb_denied = 0
I/SmartNS_PSService( 3413): usb notificaiton:true
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  907): bSetPropertyMultiRAB:false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3413/1000)
I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/SmartNS_Utility( 3413): usb_cable_connect = 1
D/SmartNS_Utility( 3413): usb_denied = 0
I/RemoteViews( 1111): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1111): com.android.settings 0 1 10
I/SmartNS_PSService( 3413): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3413): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  907): Resuming delayed broadcast
D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
W/WeatherUtility( 3252): can't get weather sync account
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
I/RemoteViews( 1111): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1111): com.android.settings 1 1 10
D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1252): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1252): com.google.android.googlequicksearchbox 0 0 5
I/ActivityManager(  907): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
I/ActivityManager(  907): Resuming delayed broadcast
D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/RemoteViews( 1252): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1252): pl.k2.droidoaudioteka 1 1 8
I/ActivityManager(  907): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
I/jxcore-log( 3184): getBuffer is called!!!!
I/jxcore-log( 3184): 
D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
W/WeatherRequest( 3252): request cur loc, but there is no sys cur
W/Settings( 3252): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1252): com.htc.widget.weatherclock (true,33751552)
I/HtcModeClient( 1497): handler message = 4011
E/HtcModeClient( 1497): Check connection and retry 5 times.
I/RemoteViews.Performance( 1252): com.htc.widget.weatherclock 0 5 17
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1207/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1207/10028)
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
V/AlarmManager(  907): sending alarm PendingIntent{42474bd8: PendingIntentRecord{424e1df8 com.google.android.gms startService}}, i=null, t=0, cnt=17068, w=84918423, Int=84918423
I/ActivityManager(  907): Resuming delayed broadcast
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1207/10028)
I/AdsMeasurementBroadcastReceiver( 1207): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1207): Unauthorized to start the main service
D/SnetService( 1207): snet destroyed
D/PackageBroadcastService( 1207): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  907): acquireWL(423313b0): PARTIAL_WAKE_LOCK  Icing 0x1 1207 10028 null
D/PMS     (  907): releaseWL(423313b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PeopleContactsSync( 1207): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1207, uid=10028, userID:0
W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(424168a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  907): releaseHCC(42353ee0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3449 uid=10031 gids={50031, 3003, 5012}
I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
I/ActivityManager(  907): Resuming delayed broadcast
D/Process (  907): killProcessQuiet, pid=3151
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3151:com.htc.contacts/u0a41 (adj 15): empty #17
I/[PluginManager]RegisterService( 1390): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/[PluginManager]RegisterService( 1390): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3465 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3465, uid=10073, userID:0
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3151
,D/Finsky  ( 3465): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3465/10073)
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3465/10073)
,D/Finsky  ( 3465): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3465): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3465): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3465, uid=10073, userID:0
,D/Process (  907): killProcessQuiet, pid=3219
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1252): action: android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  907): Killing 3219:com.htc.calendar/u0a13 (adj 15): empty #17
D/Finsky  ( 3465): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3465): [1] 2.run: Finished loading 1 libraries.
,I/IcingCorporaProvider( 2688): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  907): Recipient 3219
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Finsky  ( 3465): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  907): Delaying start of: ServiceRecord{4266f4a0 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,W/asset   ( 2688): Copying FileAsset 0x5cae8f18 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2688): UpdateCorporaTask done [took 49 ms] updated apps [took 49 ms] 
,D/Finsky  ( 3465): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3500 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 3500): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3500 dbg=false s=true
,I/DeviceManagement( 3500): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,D/Process (  907): killProcessQuiet, pid=2966
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3513 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 2966:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2966
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  907): killProcessQuiet, pid=3266
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3266:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3266
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GAV2    ( 3513): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3533 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  907): releaseWL(4254ce20): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/htcbackup-core( 3533): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3533): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3533): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3500): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3500): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[android, com.htc.backup, com.htc.checkinprovider, com.android.location.fused, com.htc.drive.activator, com.android.CSDFunctionG, com.htc.android.htcloglevel, com.htc.backupreset, com.htc.android.htcsetupwizard, com.htc.autobot.cargps.provider, com.htc.lockscreen, com.htc.feedback, com.android.keychain, com.android.inputdevices, com.htc.htcpowermanager, com.htc.smartdim, com.htc.guide, com.qualcomm.timeservice, com.qualcomm.privinit, com.android.settings, com.htc.usage, com.htc.home.personalize, com.htc.mirrorlinkserver, com.android.providers.settings, com.htc.cirmodule]
,I/DeviceManagement( 3500): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/ActivityManager(  907): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3550 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  907): killProcessQuiet, pid=3298
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  907): Killing 3298:com.htc.stock/u0a81 (adj 15): empty #17
I/DeviceManagement( 3500): WorkflowService: Starting workflow service
I/DeviceManagement( 3500): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b615c8] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3500): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3500): ModelRegistry: Loading model meta data from resources...
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3298
,I/DeviceManagement( 3500): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3500): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3550):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  907): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,W/GAV2    ( 3513): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/Process (  907): killProcessQuiet, pid=3312
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3564 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  907): Killing 3312:com.htc.stock:remote/u0a81 (adj 15): empty #17
V/AlarmManager(  907): sending alarm PendingIntent{42480390: PendingIntentRecord{424a4420 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449410976357, Int=0
,I/ActivityManager(  907): Recipient 3312
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,I/DeviceManagement( 3500): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3465): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3465): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/DeviceManagement( 3500): SessionStateController: Checking invariants...
,I/DeviceManagement( 3500): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/DeviceManagement( 3500): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b615c8]
,I/DeviceManagement( 3500): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(425c2748): PARTIAL_WAKE_LOCK  AsyncService 0x1 3564 10160 null
,D/PMS     (  907): acquireWL(425e0bc8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3564 10160 null
,D/PMS     (  907): releaseWL(425c2748): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  907): acquireWL(428567c0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3564 10160 null
D/PMS     (  907): releaseWL(425e0bc8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3596 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3564/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3564/10160)
,D/Settings:HtcWirelessFeatureFlags( 3413): id/is att sku: 99/false
,W/SystemReader( 3413): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3413): Cannot find support_harman, use default value instead
,W/SystemReader( 3413): Cannot find effect_manager_id, use default value instead
,D/Process (  907): killProcessQuiet, pid=3166
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): releaseWL(428567c0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  907): Killing 3166:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,E/Settings:HtcWrapHeaderInfo( 3413): no such activity!
,W/ContextImpl( 3596): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/PowerUsageService( 3596): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3596): MY_DEBUG = false
D/PMS     (  907): acquireWL(427042a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3596 1000 null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3413): The wrap header doesn't exist in header list.
,W/WeatherUtility( 1111): can't get weather sync account
,D/WeatherUtility( 1390): Weather sync is On
,D/WSP     ( 1390): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,W/BatSI   (  907): Couldn't get kernel wake lock stats
E/Settings:HtcWrapHeaderInfo( 3413): updateDevelopment, bPrefShow = true
,W/WeatherUtility( 3252): can't get weather sync account
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,W/WeatherRequest( 3252): request cur loc, but there is no sys cur
,W/Settings( 3252): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Settings:HtcUmcWidgetEnabler( 3413): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportHomeButton]support         :false
,D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1252): com.htc.widget.weatherclock (true,33751552)
,W/FingerprintManager( 3413): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3413): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 3413): Failed to find provider info for com.htc.vowifi
I/RemoteViews.Performance( 1252): com.htc.widget.weatherclock 0 9 17
,I/ActivityManager(  907): Recipient 3166
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3413): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3413): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3413): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3413): [supportHomeButton]support         :false
,W/FingerprintManager( 3413): hasFingerprint() - sSensorCode = 0
,I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 3413): isSupportVoWifi: null
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
E/ActivityThread( 3413): Failed to find provider info for com.htc.vowifi
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3465): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3465): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3465): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3618 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,D/Process (  907): killProcessQuiet, pid=3196
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3196:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3196
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,V/AlarmManager(  907): sending alarm PendingIntent{425c16d8: PendingIntentRecord{42592920 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1449410977872, Int=0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3635 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3324
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3324:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3324
,D/Process (  907): killProcessQuiet, pid=3282
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3282:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3282
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3635): Database version: 95
,W/ContextImpl( 3635): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3635): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/SensorManager(  907): mEventCount = 450
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3635): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3635): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3635): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3635, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 3635): Registered
,I/MediaRouter( 3635): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3654 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (3635/10154)
,D/MediaRouter( 3635): getSelectedRoute
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3635, uid=10154, userID:0
,D/Process (  907): killProcessQuiet, pid=3341
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3341:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3341
,D/DFPI.PIReciver( 3654): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3654): onHandleIntent
,I/DFPI.ApkInstallService( 3654): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3654): check CID = HTC__032
,I/DFPI.ApkInstallService( 3654): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  907): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3670 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3670/10051)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3670): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/SocialFeedProvider( 1252): +disConnect socialManager
,I/SocialFeedProvider( 1252): disconnect socialManager
,I/SocialFeedProvider( 1252): -disConnect socialManager
,I/ActivityManager(  907): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=3688 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  907): sending alarm PendingIntent{41e3ade0: PendingIntentRecord{423a4848 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1449410978494, Int=0
,I/ImageRamCache( 3688): create image Cache, size: 31457280.
I/ImageRamCache( 3688): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3688): create image Cache, size: 12582912.
,I/FeedSettings( 3688): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3688): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3688): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3688): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3688): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3688): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 3688): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3688): last commit ulog time 1449380062667
,I/SocialManager[SocialBiLogHelper]( 3688): skip commit this time
,D/Process (  907): killProcessQuiet, pid=3355
,I/ActivityManager(  907): Killing 3355:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3355
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(427042a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  907): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1251
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): ,	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): ,	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183),
W/System.err(  907): ,	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	,at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412),
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method),
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 2(ms)
,D/BluetoothManagerService(  907): Message: MESSAGE_DISABLE
,D/WifiManager( 3184): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
,D/WifiService(  907): New client listening to asynchronous messages
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
,W/Settings:Agent(  907): >> traceCallingStack()
,W/Settings:Agent(  907): Process.myPid(): 907
,W/Settings:Agent(  907): Process.myTid(): 1104
W/Settings:Agent(  907): Process.myUid(): 1000
,W/Settings:Agent(  907): 
,W/Settings:Agent(  907): 
D/WifiService(  907): setWifiEnabled: false pid=3184, uid=10355
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
,I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true,
W/System.err(  907): java.lang.Throwable: stack dump
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  907): ,	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): ,	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170),
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
,W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
,W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
,W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): ,	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 11(ms)
I/jxcore-log( 3184): ****TEST TOOK:  5065  ms ****
I/jxcore-log( 3184): ,
I/jxcore-log( 3184): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3184): 
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3707 uid=10080 gids={50080, 5001, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3367
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3367:com.google.android.talk/u0a111 (adj 15): empty #17
,I/SoundPicker( 3707): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3707): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3707): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3707): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3707): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3707): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3707): MODE_GSM access default DB
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_cdma),
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3707): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3707): MODE_GSM access default DB
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3367
I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
E/cutils-trace( 3705): Error opening trace file: No such file or directory (2)
,I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/CustomizationManager( 3705): ====startRecUseTime====
D/htc.customization.log.level( 3705):  is 
,W/CustomizationLogLevel( 3705): Level value is invalid, use default level 2
,I/HtcModeClient( 1497): handler message = 4011
,E/HtcModeClient( 1497): Check connection and retry 6 times.
,D/CustomizationManager( 3705):  Read ACC file spent 0.052 (s)
,D/CIDMapFileReader( 3705): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3705): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3705): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3705): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3705): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3705): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3705): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3705): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3705): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3705): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3705): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3705): Parsing tag category name = system
,I/CustomizationCIDLoader( 3705): Parsing tag category name = application
I/CustomizationCIDLoader( 3705): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3705): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 3705): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3705): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3705): Parsing tag category name = Settings
D/CustomizationManager( 3705):  Read CID file spent 0.091 (s)
,D/CustomizationManager( 3705):  All configurations done spent 0.091 (s)
W/HtcNativeFlag( 3705): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3705): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3705): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3705): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=3705, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,D/Process (  907): killProcessQuiet, pid=3184
,W/asset   (  907): Copying FileAsset 0x6346ddb8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Killing 3184:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  907): Force removing ActivityRecord{41c5fbc0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  907): Skipping PackageSetting{42216e28 com.test.thalitest/10348} due to missing metadata
,I/ActivityManager(  907): Force stopping com.example.hello appid=10355 user=0: pkg removed
,W/InputDispatcher(  907): channel '4255dad0 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  907): channel '4255dad0 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '4255dad0 com.example.hello.MainActivity (s)'
I/WindowManager(  907): WINDOW DIED Window{4255dad0 u0 com.example.hello/com.example.hello.MainActivity}
W/WindowManager(  907): Failed looking up window
W/WindowManager(  907): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42799c98 does not exist
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  907): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  907): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  907): WIN DEATH: null
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1585): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1585): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/acms    ( 1776): Unregistering com.example.hello
I/FeedHostManager( 1252): [onResume]
,I/FeedProviderManager( 1252): onResume
I/SocialFeedProvider( 1252): +onResume
I/SocialFeedProvider( 1252): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1252): -onResume
,E/acms    ( 1776): Could not unregister removed application com.example.hello
,D/PMS     (  907): acquireWL(427a9a58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
W/AccTypeManager( 1305): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1305): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ConnectivityHelper( 1252): [getCurrentConnectionType] no network connection
,W/GeofencerStateMachine( 1415): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1252/10075)
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): releaseWL(427a9a58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
I/Prism.ItemManager( 3688): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3688): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1305): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/SystemReader( 1234): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/DFPI.PIReciver( 3654): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/DFPI.ApkInstallService( 3654): onHandleIntent
,I/DFPI.ApkInstallService( 3654): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3654): check CID = HTC__032
,I/DFPI.ApkInstallService( 3654): There is no Demo.apk in sd card or phone storage
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
I/ActivityManager(  907): Resuming delayed broadcast
,E/ExternalAccountType( 1305): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
I/ActivityManager(  907): Waited long enough for: ServiceRecord{426e7168 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
I/ActivityManager(  907): Resuming delayed broadcast
,D/PhoneApp( 1223): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/SoundPicker( 3707): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3707): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3707): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3707): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3707): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3707): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3707): MODE_GSM access default DB
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3707): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3707): MODE_GSM access default DB
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3184 uid 10355
,I/InputMethodManagerService(  907): Enable input method client, pid=1252
W/Binder  ( 1186): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1186): java.lang.NullPointerException
W/Binder  ( 1186): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1186): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1186): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1186): 	at dalvik.system.NativeStart.run(Native Method)
I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 3654): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3654): onHandleIntent
,I/DFPI.ApkInstallService( 3654): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3654): check CID = HTC__032
,I/DFPI.ApkInstallService( 3654): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 3707): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3707): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3707): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3707): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3707): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3707): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3707): MODE_GSM access default DB
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3707): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3707): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3707): MODE_GSM access default DB
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3707): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3707): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3707): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3707): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,E/SharedPreferencesImpl( 3635): Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,E/SQLiteDatabase( 3635): Failed to open database '/data/data/com.google.android.music/databases/music.db'.
E/SQLiteDatabase( 3635): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3635): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3635): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3635): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3635): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3635): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3635): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3635): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3635): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3635): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3635): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3635): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3635): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3635): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3635): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/SQLiteDatabase( 3635): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 3635): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/SQLiteDatabase( 3635): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/SQLiteDatabase( 3635): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/SQLiteDatabase( 3635): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/SQLiteDatabase( 3635): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/SQLiteDatabase( 3635): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/SQLiteDatabase( 3635): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 3635): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3635): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/SQLiteDatabase( 3635): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3635): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 3635): threadid=16: thread exiting with uncaught exception (group=0x416f2e30),
,E/ActivityManager(  907): App crashed! Process: com.google.android.music:main
E/AndroidRuntime( 3635): FATAL EXCEPTION: MediaStoreImportService
E/AndroidRuntime( 3635): Process: com.google.android.music:main, PID: 3635
E/AndroidRuntime( 3635): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3635): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3635): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3635): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3635): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3635): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3635): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3635): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3635): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3635): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3635): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3635): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3635): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3635): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3635): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/AndroidRuntime( 3635): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 3635): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/AndroidRuntime( 3635): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/AndroidRuntime( 3635): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/AndroidRuntime( 3635): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/AndroidRuntime( 3635): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/AndroidRuntime( 3635): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/AndroidRuntime( 3635): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3635): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3635): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/AndroidRuntime( 3635): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3635): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/D,ropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,W/PackageManager(  907): Unable to load service info ResolveInfo{420a8958 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/GAV2    ( 3513): Thread[GAThread,5,main]: No campaign data found.

```
