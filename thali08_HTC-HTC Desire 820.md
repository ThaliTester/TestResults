#### Test 502422853393492_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/AutoSetting( 1395): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 2955): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2955): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2955): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2955): Cust_ConnectToPC   : spcsc>false
D/        ( 2955): Cust_ConnectToPC   : IPT>true
D/        ( 2955): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2955): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2955): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2955): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2955): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
--------- beginning of /dev/log/system
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PSReceiver( 2955): onReceive:android.intent.action.USER_PRESENT
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
W/ContextImpl( 2955): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/SmartNS_PSService( 2955): onReceive:android.intent.action.USER_PRESENT
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
W/Settings( 2955): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2955):  defaultType:0
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
E/cutils-trace( 3064): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3064): ====startRecUseTime====
D/htc.customization.log.level( 3064):  is 
W/CustomizationLogLevel( 3064): Level value is invalid, use default level 2
D/CustomizationManager( 3064):  Read ACC file spent 0.076 (s)
D/CIDMapFileReader( 3064): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3064): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3064): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3064): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3064): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3064): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3064): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3064): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3064): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3064): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3064): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3064): Parsing tag category name = system
I/CustomizationCIDLoader( 3064): Parsing tag category name = application
I/CustomizationCIDLoader( 3064): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3064): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3064): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3064): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3064): Parsing tag category name = Settings
D/CustomizationManager( 3064):  Read CID file spent 0.136 (s)
D/CustomizationManager( 3064):  All configurations done spent 0.136 (s)
W/HtcNativeFlag( 3064): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3064): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3064): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3064): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3064
D/PMS     (  903): acquireHCC(42466508): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(42705760): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
W/asset   (  903): Copying FileAsset 0x6746bf78 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1113653960
I/FeedHostManager( 1247): [onPause]
D/PMS     (  903): acquireWL(4255ac80): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/FeedProviderManager( 1247): onPause
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42306998
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
I/ActivityManager(  903): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3075 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
W/asset   ( 3075): Copying FileAsset 0x5c796428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1247): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3075): Binding Chromium to main looper Looper (main, tid 1) {41b214b0}
I/LibraryLoader( 3075): Expected native library version number "",actual native library version number ""
I/chromium( 3075): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3075): Initializing chromium process, renderers=0
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42509b88:true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  903): acquireWL(42606e78): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  903): acquireWL(42441c58): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  903): releaseWL(42441c58): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 3075): 1102282224: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3075): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3075): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3075): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3075): Local Branch: 
I/Adreno-EGL( 3075): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3075): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3075):                  aa63bbd948f41d15fc72f585e
W/PackageManager(  903): Unable to load service info ResolveInfo{42450b48 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
W/chromium( 3075): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3075): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3075): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3075): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3075): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3075): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3075): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3075): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3075): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3075): CordovaWebView is running on device made by: HTC
,D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
W/AwContents( 3075): nativeOnDraw failed; clearing to background color.
D/RemoteDisplayProvider(  903): start
W/WeatherUtility( 1107): can't get weather sync account
W/ResourceType( 3075): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3075): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b69178, mServedView=org.apache.cordova.engine.SystemWebView{41b2f110 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  903): Disable input method client, pid=1247
I/InputMethodManagerService(  903): Enable input method client, pid=3075
W/AwContents( 3075): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  903): Displayed com.example.hello/.MainActivity: +271ms
W/XT9_C   ( 1183): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1183): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  903): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3115 uid=10038 gids={50038}
D/PMS     (  903): releaseWL(4255ac80): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/WeatherRequest( 1107): request cur loc, but there is no sys cur
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
I/ActivityManager(  903): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3128 uid=10077 gids={50077}
D/Process (  903): killProcessQuiet, pid=2773
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 2773:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2773
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SMSBackup( 3128): Got a database change event
I/ActivityManager(  903): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3140 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
D/Process (  903): killProcessQuiet, pid=2183
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 2183:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2183
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bb7010 +
I/Prism.WidgetManager( 1247): onLoadItems() +
D/browser ( 3140): Browser versionCode = 760001523 versionName = 7.0.2512153020
D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC <<
I/chromium( 3075): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3075): Unable to open asset URL: file:///android_asset/www/jxcore.js
W/SWE_UI  ( 3140): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3140): Loading: swewebviewchromium
I/LibraryLoader( 3140): Time to load native libraries: 35 ms (timestamps 748-783)
I/LibraryLoader( 3140): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3140): Initializing chromium process, renderers=9
I/LibraryLoader( 3140): Expected native library version number "",actual native library version number ""
I/chromium( 3140): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
D/JsMessageQueue( 3075): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3075): JniHelper::setJavaVM(0x415fc048), pthread_self() = 1658887520
D/JX-Cordova( 3075): jxcore cordova android initializing
W/jxcore-log( 3075): Initializing JXcore engine
W/jxcore-log( 3075): JXcore engine is ready
E/Prism.WidgetManager( 1247): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1247): onLoadItems() -
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bb7010 -
W/jxcore-log( 3075): Starting JXcore engine
W/chromium( 3140): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
I/Adreno-EGL( 3140): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3140): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3140): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3140): Local Branch: 
I/Adreno-EGL( 3140): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3140): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3140):                  aa63bbd948f41d15fc72f585e
D/Process (  903): killProcessQuiet, pid=2805
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 2805:com.google.android.gm/u0a107 (adj 15): empty #17
V/IccIntentReceiver( 1273): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1472): SIM state: ABSENT
I/SIMStateChangeReceiver( 1472): phoneType = 0
I/SIMStateChangeReceiver( 1472): remove notification
I/ActivityManager(  903): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3182 uid=10031 gids={50031, 3003, 5012}
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2805
I/ActivityManager(  903): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3195 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
D/Process (  903): killProcessQuiet, pid=2843
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 2843:com.htc.backup/1000 (adj 15): empty #17
W/jxcore-log( 3075): Platform android
W/jxcore-log( 3075): 
W/jxcore-log( 3075): Process ARCH arm
W/jxcore-log( 3075): 
W/SystemReader( 2556): Cannot find message_ambs_application_id, use default value instead
D/SmsReceiver( 2556): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2556): onReceive()
D/ExchangePolicystatus( 2556): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2556): onReceive(): else
D/Process (  903): killProcessQuiet, pid=2788
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/HtcBroadcastReceiver( 1218): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  903): Killing 2788:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/ActivityManager(  903): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3210 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/jxcore-log( 3075): JXcore Cordova bridge is ready!
I/jxcore-log( 3075): 
W/jxcore-log( 3075): JXcore engine is started
I/ActivityManager(  903): Recipient 2843
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AccTypeManager( 3195): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3195): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/jxcore-log( 3075): >> HTC-HTC Desire 820
E/jxcore-log( 3075): 
D/CalendarApplication( 3210): onCreate
D/ProviderChangeReceiver( 3210): ---------------------------------------------------
D/ProviderChangeReceiver( 3210): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3210): start to updateAlertNotification!
I/jxcore-log( 3075): Total memory 1964650496
I/jxcore-log( 3075): 
I/jxcore-log( 3075): Free memory 725643264
I/jxcore-log( 3075): 
I/jxcore-log( 3075): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3075): 
I/jxcore-log( 3075): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3075): 
W/ContextImpl( 2942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/jxcore-log( 3075): userPath [ 'www' ]
I/jxcore-log( 3075): 
I/jxcore-log( 3075): Size 720 1184
I/jxcore-log( 3075): 
I/jxcore-log( 3075): Screen Brightness 10
I/jxcore-log( 3075): 
D/GCM     ( 1343): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/jxcore-log( 3075): Dummy Error Log.
E/jxcore-log( 3075): 
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2788
D/AlertService( 3210): No fired or scheduled alerts
D/HtcAlertUtils( 3210): -- cancelReminderNotification --
D/HtcAlertUtils( 3210): broadcastExistReminder!
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/AdsMeasurementBroadcastReceiver( 1200): Reporting settings might have changed, alerting AdsMeasurementService
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  903): Resuming delayed broadcast
D/AdsMeasurementBroadcastReceiver( 1200): Unauthorized to start the main service
D/Process (  903): killProcessQuiet, pid=2866
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 2866:com.google.android.talk/u0a111 (adj 15): empty #17
I/ActivityManager(  903): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3229 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
D/AccTypeManager( 3195): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/ExternalAccountType( 3195): Unsupported attribute readOnly
I/ActivityManager(  903): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3244 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3229): can't get weather sync account
W/AccTypeManager( 3195): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3195): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/WeatherRequest( 3229): request cur loc, but there is no sys cur
W/Settings( 3229): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AccTypeManager( 3195): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/DemoRecovery.RestoreReceiver( 3244): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/ContextImpl( 3244): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/RestoreService( 3244): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  903): Resuming delayed broadcast
E/ExternalAccountType( 3195): Unsupported attribute readOnly
I/ActivityManager(  903): Recipient 2866
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 0 17 17
I/ActivityManager(  903): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3259 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
D/Process (  903): killProcessQuiet, pid=2893
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 2893:com.htc.backupreset/1000 (adj 15): empty #17
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2893
D/PMS     (  903): acquireWL(425eec80): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3259 10070 null
D/PMS     (  903): acquireWL(42784c60): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3259 10070 null
I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 3259): update TASK shortcut>
D/PMS     (  903): releaseWL(425eec80): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PhoneApp( 1218): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1218): -- N1 =0
D/PhoneApp( 1218): -- N2 =0
D/PhoneApp( 1218): -- N3 =0
I/TodoTaskNotifyService( 3259): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  903): releaseWL(42784c60): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3274 uid=10081 gids={50081, 3003, 5012}
D/Process (  903): killProcessQuiet, pid=2910
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/NotifyReceiver( 3259): stopSelfResult true
I/ActivityManager(  903): Killing 2910:com.htc.htccupd/u0a17 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2910
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3286 uid=10081 gids={50081, 3003, 5012}
D/Process (  903): killProcessQuiet, pid=2927
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/SMSBackup( 3128): Got a database change event
D/Process (  903): killProcessQuiet, pid=2965
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/AdsMeasurementBroadcastReceiver( 1200): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1200): Unauthorized to start the main service
I/ActivityManager(  903): Killing 2927:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/ActivityManager(  903): Killing 2965:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2965
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3298 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
I/ImageRamCache( 3298): create image Cache, size: 31457280.
I/ImageRamCache( 3298): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3298): create image Cache, size: 12582912.
I/FeedSettings( 3298): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3298): GroupBudget 0.500000 0.380000
I/FeedSettings( 3298): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 3298): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 3298): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3298): loadGridSize() with Alternative
D/CustomHighlightReceiver( 3298): [custom highlight] onReceive
D/CustomHighlightService( 3298): [custom highlight] onHandleIntent
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2927
I/ActivityManager(  903): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/NewsDB  ( 3298): set custom highlight []
D/CustomHighlightService( 3298): [custom highlight] set tags 
D/MessagingShortcutReceiver( 2556): keep hiding shortcut bubble
D/MessagingShortcut( 2556): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2556): After query: 0
D/MessagingShortcut( 2556): mPresentUnreadCount: -1
D/MessagingShortcut( 2556): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2556): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderNotification, total:0
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  903): Resuming delayed broadcast
D/TodoTaskshortcut( 3259): update TASK shortcut>
D/HtcBroadcastReceiver( 1218): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
D/Process (  903): killProcessQuiet, pid=2982
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 2982:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2982
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3314 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  903): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
I/HtcModeClient( 1472): handler message = 4011
I/ActivityManager(  903): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3328 uid=10091 gids={50091, 3003, 5012}
E/HtcModeClient( 1472): Check connection and retry 5 times.
I/jxcore-log( 3075): getBuffer is called!!!!
I/jxcore-log( 3075): 
D/MdScBoot( 3314): [828.1.] 30@-155911 -> 40@-155941
D/Process (  903): killProcessQuiet, pid=2996
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/Process (  903): killProcessQuiet, pid=3008
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/GCM     ( 1343): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 2996:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  903): Killing 3008:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2996
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3341 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
D/MessagingNotification( 2556): New incoming message, can't cancel notification now
D/MessagingNotification( 2556): newMsgCnt: 0, false
I/ActivityManager(  903): Recipient 3008
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  903): Client com.google.android.youtube (pid 3008): Died!
I/Babel   ( 3341): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3341): MmsConfig.loadMmsSettings
E/dalvikvm( 3341): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 3341): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 3341): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 3341): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 3341): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/MmsCustomizationProvider( 2556): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2556): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3341): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3341): MmsConfig.loadFromDatabase
E/Babel   ( 3341): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3341): MmsConfig.loadFromResources
,E/Babel   ( 3341): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3341): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3341, uid=10111, userID:0
,W/Settings( 3341): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3341, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3341, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3341, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3341, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3341, uid=10111, userID:0
,D/Process (  903): killProcessQuiet, pid=2955
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  903): Killing 2955:com.android.settings/1000 (adj 15): empty #17
,D/MtpReceiver( 2237): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2237): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2237): [MTP][handleMessage][startService]
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1757/10178)
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2955
,D/MtpReceiver( 2237): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2237): [MTP][handleMessage]-
,I/ActivityManager(  903): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3367 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
I/RemoteViews( 1107): com.android.providers.media (false,0)
D/MtpService( 2237): [MTP] startForeground
I/RemoteViews.Performance( 1107): com.android.providers.media 0 1 10
I/ProviderInstaller( 3341): Installed default security provider GmsCore_OpenSSL
I/RemoteViews( 1107): com.android.providers.media (false,0)
D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews.Performance( 1107): com.android.providers.media 1 1 15
D/MtpService( 2237): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2237): TotalSize=1918604,MediaCacheLimit=6000
D/MtpService( 2237): [isMtpConnected] connected: true
,D/SyncApplication( 3367): Loading default preferences
,W/Resources( 3367): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  903): New client listening to asynchronous messages
,D/SyncApplication( 3367): Overriding preferences with custom values
,D/SyncApplication( 3367): Updating preferences succeeded
,E/SyncApplication( 3367): Application created.
D/VolumeInfo( 3367): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3367): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3367): Found 0 mount point(s)
,V/VolumeInfo( 3367): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3367): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3367): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3367): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3367): getNewCalendarAuthority()...
,D/SyncApplication( 3367): enableAppOperation()+
,D/SyncApplication( 3367): enableAppOperation()-
,D/HTCUtilities( 3367): isNeorSinged() + 
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3367, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3367, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3367): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3367): isNeorSinged() return false
D/CDMountReceiver( 3367): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3367): USB connected to PC
,D/FOTAReceiver( 3367): onReceive() enter 
,D/FOTAReceiver( 3367): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  903): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3386 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  903): killProcessQuiet, pid=3140
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3140:com.htc.sense.browser/u0a12 (adj 15): empty #17
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
,D/PMS     (  903): releaseHCC(42466508): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(42705760): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/HtcFingerPrintQuickLaunchProvider( 3386): -onCreate()
,V/Settings:HtcSettingsApplication( 3386): [3386/3386] onCreate()
,D/TetherSettings( 3386): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3386): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3386): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3386): Cust_ConnectToPC   : spcsc>false
D/        ( 3386): Cust_ConnectToPC   : IPT>true
D/        ( 3386): Cust_ConnectToPC   : Singel_USB>false
D/Process (  903): killProcessQuiet, pid=3182
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/Settings( 3386): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  903): Killing 3182:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/TetherSettings( 3386): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3386): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3386): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3386): Cust_ConnectToPC   : spcsc>false
D/        ( 3386): Cust_ConnectToPC   : IPT>true
D/        ( 3386): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3386): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3386): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3386): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3386): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3386): usb_cable_connect = 1
,D/SmartNS_Utility( 3386): usb_denied = 0
I/SmartNS_NSReceiver( 3386): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3386): USB = true hasTethered = false isNSOpening: false
I/ActivityManager(  903): Recipient 3182
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PSReceiver( 3386): onReceive:com.htc.intent.action.USB_CONNECT2PC
,I/SmartNS_PSService( 3386): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3386): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3386):  defaultType:0
,I/SmartNS_PSService( 3386): fail notificaiton:false
D/SmartNS_Utility( 3386): usb_cable_connect = 1
D/SmartNS_Utility( 3386): usb_denied = 0
,I/SmartNS_PSService( 3386): usb notificaiton:true
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
W/ContextImpl( 3386): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3140
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (3386/1000)
V/Tethering(  903): bSetPropertyMultiRAB:false
,I/ActivityManager(  903): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/RemoteViews( 1107): com.android.settings (true,33751552)
D/SmartNS_Utility( 3386): usb_cable_connect = 1
I/RemoteViews.Performance( 1107): com.android.settings 1 1 10
D/SmartNS_Utility( 3386): usb_denied = 0
I/SmartNS_PSService( 3386): usb notificaiton:true
V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  903): bSetPropertyMultiRAB:false
,D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (3386/1000)
I/ActivityManager(  903): Resuming delayed broadcast
,D/SmartNS_Utility( 3386): usb_cable_connect = 1
,D/SmartNS_Utility( 3386): usb_denied = 0
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
I/SmartNS_PSService( 3386): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3386): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/RemoteViews( 1107): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1107): com.android.settings 1 1 10
D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,W/WeatherUtility( 3229): can't get weather sync account
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1247): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1247): com.google.android.googlequicksearchbox 0 0 5
,I/ActivityManager(  903): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
,I/ActivityManager(  903): Resuming delayed broadcast
D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/RemoteViews( 1247): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1247): pl.k2.droidoaudioteka 1 0 8
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,D/LocationManagerService(  903): getAllProviders()=[passive, gps, network]
,W/WeatherRequest( 3229): request cur loc, but there is no sys cur
,W/Settings( 3229): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  903): Resuming delayed broadcast
,I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 0 7 17
,V/AlarmManager(  903): sending alarm PendingIntent{425a9610: PendingIntentRecord{4273f6b0 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1449413982710, Int=0
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/AdsMeasurementBroadcastReceiver( 1200): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1200): Unauthorized to start the main service
V/AlarmManager(  903): sending alarm PendingIntent{4258f900: PendingIntentRecord{427194b8 com.google.android.gms startService}}, i=null, t=0, cnt=17068, w=84918423, Int=84918423
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/SnetService( 1200): snet destroyed
,D/PackageBroadcastService( 1200): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  903): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  903): acquireWL(42707f38): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  903): releaseWL(42707f38): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 1200): CP2 sync disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1200, uid=10028, userID:0
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3423 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  903): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3195
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3195:com.htc.contacts/u0a41 (adj 15): empty #17
I/[PluginManager]RegisterService( 1395): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1395): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3439 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3439, uid=10073, userID:0
,D/PMS     (  903): releaseWL(42606e78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  903): Recipient 3195
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3439): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (3439/10073)
,D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (3439/10073)
,D/Finsky  ( 3439): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3439): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3439): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3439, uid=10073, userID:0
,D/Process (  903): killProcessQuiet, pid=3210
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1247): action: android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  903): Killing 3210:com.htc.calendar/u0a13 (adj 15): empty #17
D/Finsky  ( 3439): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3439): [1] 2.run: Finished loading 1 libraries.
,I/IcingCorporaProvider( 2673): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  903): Recipient 3210
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Finsky  ( 3439): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  903): Delaying start of: ServiceRecord{42713100 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,D/PMS     (  903): acquireWL(41c88ed0): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  903): releaseWL(41c88ed0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(423aa148): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  903): releaseWL(423aa148): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(4200f358): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  903): releaseWL(4200f358): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(423b06a8): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/Process (  903): killProcessQuiet, pid=2942
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 2942:com.android.settings:remote/1000 (adj 15): empty #17
,D/PMS     (  903): releaseWL(423b06a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  903): Recipient 2942
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3439): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PMS     (  903): acquireWL(424d8198): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  903): releaseWL(424d8198): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): acquireWL(422bf378): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  903): releaseWL(422bf378): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3476 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  903): acquireWL(423f80b8): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  903): releaseWL(423f80b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(41e69b40): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  903): releaseWL(41e69b40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/DeviceManagement( 3476): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3476 dbg=false s=true
,I/DeviceManagement( 3476): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,D/Process (  903): killProcessQuiet, pid=3244
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3489 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  903): Killing 3244:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,D/PMS     (  903): acquireWL(42592970): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,I/ActivityManager(  903): Recipient 3244
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): releaseWL(42592970): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(425e5cf0): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  903): releaseWL(425e5cf0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(427eef20): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  903): releaseWL(427eef20): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(4275bb90): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  903): releaseWL(4275bb90): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2673): Copying FileAsset 0x63ece078 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2673): UpdateCorporaTask done [took 419 ms] updated apps [took 419 ms] 
,W/GAV2    ( 3489): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  903): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3509 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/htcbackup-core( 3509): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3509): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
W/ContextImpl( 3509): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/DeviceManagement( 3476): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3476): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.cirmodule, com.htc.backupreset, com.qualcomm.timeservice, com.htc.android.htcloglevel, com.htc.home.personalize, com.htc.guide, com.htc.smartdim, com.android.location.fused, com.qualcomm.privinit, com.htc.drive.activator, com.android.settings, com.android.providers.settings, com.htc.feedback, com.htc.lockscreen, com.htc.android.htcsetupwizard, com.htc.backup, com.htc.autobot.cargps.provider, com.htc.mirrorlinkserver, com.android.CSDFunctionG, com.htc.checkinprovider, com.android.inputdevices, com.htc.usage, com.android.keychain, android, com.htc.htcpowermanager]
,I/DeviceManagement( 3476): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/ActivityManager(  903): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3526 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  903): killProcessQuiet, pid=3274
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/DeviceManagement( 3476): WorkflowService: Starting workflow service
I/DeviceManagement( 3476): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b62590] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3476): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/ActivityManager(  903): Killing 3274:com.htc.stock/u0a81 (adj 15): empty #17
I/DeviceManagement( 3476): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  903): Recipient 3274
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 3476): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3476): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3526):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
V/AlarmManager(  903): sending alarm PendingIntent{41d73468: PendingIntentRecord{42812530 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449413984470, Int=0
I/ActivityManager(  903): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,I/SensorManager(  903): mEventCount = 450
,W/GLSUser ( 1343): GoogleAccountDataService.getToken()
,I/GoogleHttpClient( 1343): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1343): Using GMS GoogleHttpClient
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
I/ActivityManager(  903): Resuming delayed broadcast
,I/DeviceManagement( 3476): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,W/GAV2    ( 3489): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager(  903): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3543 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1343): GoogleAccountDataService.getToken()
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3439): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3439): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/DeviceManagement( 3476): SessionStateController: Checking invariants...
,I/DeviceManagement( 3476): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3476): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b62590]
,I/DeviceManagement( 3476): WorkflowService: Stopping workflow service
,D/Process (  903): killProcessQuiet, pid=3286
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3286:com.htc.stock:remote/u0a81 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3286
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(427f7b58): PARTIAL_WAKE_LOCK  AsyncService 0x1 3543 10160 null
,D/PMS     (  903): releaseWL(427f7b58): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  903): acquireWL(427e1790): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3543 10160 null
,D/PMS     (  903): acquireWL(42779310): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3543 10160 null
,D/PMS     (  903): releaseWL(427e1790): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3569 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3543/10160)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3543/10160)
,D/Settings:HtcWirelessFeatureFlags( 3386): id/is att sku: 99/false
,W/SystemReader( 3386): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3386): Cannot find support_harman, use default value instead
,W/SystemReader( 3386): Cannot find effect_manager_id, use default value instead
W/ContextImpl( 3569): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
D/PMS     (  903): releaseWL(42779310): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/PowerUsageService( 3569): call getInstance()
I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3115
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Killing 3115:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
D/PowerUsageList:PowerUsageHelper( 3569): MY_DEBUG = false
,E/Settings:HtcWrapHeaderInfo( 3386): no such activity!
I/ActivityManager(  903): Recipient 3115
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(41e159f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3569 1000 null
W/WeatherUtility( 1107): can't get weather sync account
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3386): The wrap header doesn't exist in header list.
,D/WeatherUtility( 1395): Weather sync is On
,W/BatSI   (  903): Couldn't get kernel wake lock stats
W/GLSUser ( 1343): GoogleAccountDataService.getToken()
I/SocialFeedProvider( 1247): +disConnect socialManager
I/SocialFeedProvider( 1247): disconnect socialManager
I/SocialFeedProvider( 1247): -disConnect socialManager
,D/WSP     ( 1395): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,E/Settings:HtcWrapHeaderInfo( 3386): updateDevelopment, bPrefShow = true
I/ActivityManager(  903): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,W/WeatherUtility( 3229): can't get weather sync account
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/Settings:HtcUmcWidgetEnabler( 3386): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportHomeButton]support         :false
W/Finsky  ( 3439): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 3439): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3439): [1] DailyHygiene.reschedule: Scheduling new run in 252 minutes (failures=4)
W/FingerprintManager( 3386): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
W/WeatherRequest( 3229): request cur loc, but there is no sys cur
W/Settings( 3229): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Settings:HtcVoWifiWidgetEnabler( 3386): isSupportVoWifi: null
I/ActivityManager(  903): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3386): Failed to find provider info for com.htc.vowifi
,V/AlarmManager(  903): sending alarm PendingIntent{41e757d0: PendingIntentRecord{4246eec8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1449413985231, Int=0
,I/SocialManager[SocialBiLogHelper]( 3298): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3298): last commit ulog time 1449380062667
,I/SocialManager[SocialBiLogHelper]( 3298): skip commit this time
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 1 5 17
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3386): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3386): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3386): isSupportMusicChannel(): false
W/BatSI   (  903): Couldn't get kernel wake lock stats
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3386): [supportHomeButton]support         :false
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/FingerprintManager( 3386): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3386): isSupportVoWifi: null
I/ActivityManager(  903): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3386): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3595 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,D/Process (  903): killProcessQuiet, pid=3128
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3128:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3128
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,V/AlarmManager(  903): sending alarm PendingIntent{41d1b310: PendingIntentRecord{4234a0b8 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1449413986193, Int=0
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3612 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3259
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3259:com.htc.task/u0a70 (adj 15): empty #17
,D/Process (  903): killProcessQuiet, pid=3314
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3314:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3314
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  903): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1259
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
,W/Settings:Agent(  903): << traceCallingStack(): 2(ms)
,D/BluetoothManagerService(  903): Message: MESSAGE_DISABLE
,D/WifiManager( 3075): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1245
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
,W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
,W/Settings:Agent(  903): << traceCallingStack(): 1(ms)
,I/jxcore-log( 3075): ****TEST TOOK:  5051  ms ****
I/jxcore-log( 3075): 
,I/jxcore-log( 3075): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3075): 
D/WifiService(  903): New client listening to asynchronous messages
D/WifiService(  903): setWifiEnabled: false pid=3075, uid=10355
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3259
,I/MusicStore( 3612): Database version: 95
,W/ContextImpl( 3612): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3612): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3612): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3612): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3612): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3612, uid=10154, userID:0
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/MediaRouterService(  903): Client com.google.android.music (pid 3612): Registered
,I/MediaRouter( 3612): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,I/ActivityManager(  903): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3634 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (3612/10154)
,D/MediaRouter( 3612): getSelectedRoute
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3612, uid=10154, userID:0
,D/Process (  903): killProcessQuiet, pid=3328
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Killing 3328:com.htc.mobiledata/u0a91 (adj 15): empty #17
,D/DFPI.PIReciver( 3634): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  903): Recipient 3328
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DFPI.ApkInstallService( 3634): onHandleIntent
,I/DFPI.ApkInstallService( 3634): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3634): check CID = HTC__032
,I/DFPI.ApkInstallService( 3634): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  903): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3649 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  903): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3649/10051)
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3649): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,E/cutils-trace( 3625): Error opening trace file: No such file or directory (2)
,I/HtcModeClient( 1472): handler message = 4011
,E/HtcModeClient( 1472): Check connection and retry 6 times.
,D/CustomizationManager( 3625): ====startRecUseTime====
D/htc.customization.log.level( 3625):  is 
,W/CustomizationLogLevel( 3625): Level value is invalid, use default level 2
,D/PMS     (  903): releaseWL(41e159f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/CustomizationManager( 3625):  Read ACC file spent 0.061 (s)
,D/CIDMapFileReader( 3625): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3625): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3625): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3625): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3625): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3625): Parsing tag item name = HTC__J15
,D/CIDMapFileReader( 3625): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3625): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3625): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3625): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3625): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3625): Parsing tag category name = system
,I/CustomizationCIDLoader( 3625): Parsing tag category name = application
,I/CustomizationCIDLoader( 3625): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3625): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3625): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3625): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3625): Parsing tag category name = Settings
,D/CustomizationManager( 3625):  Read CID file spent 0.111 (s)
,D/CustomizationManager( 3625):  All configurations done spent 0.111 (s),
W/HtcNativeFlag( 3625): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3625): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3625): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3625): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  903): deletePackageAsUser: pkg=com.example.hello, pid=3625, uid=2000 user=0
,I/ActivityManager(  903): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,D/Process (  903): killProcessQuiet, pid=3075
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/asset   (  903): Copying FileAsset 0x6af09e80 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  903): Killing 3075:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  903): Force removing ActivityRecord{420e9798 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  903): Skipping PackageSetting{422715c0 com.test.thalitest/10348} due to missing metadata
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  903): channel '42704ee0 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  903): channel '42704ee0 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  903): Attempted to unregister already unregistered input channel '42704ee0 com.example.hello.MainActivity (s)'
I/WindowState(  903): WIN DEATH: Window{42704ee0 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  903): Client connection lost with reason: 4
,I/WindowManager(  903): WINDOW DIED Window{42704ee0 u0 com.example.hello/com.example.hello.MainActivity}
,I/ActivityManager(  903): Force stopping com.example.hello appid=10355 user=0: pkg removed
,D/DotMatrix( 1525): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1525): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1525): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
I/acms    ( 1775): Unregistering com.example.hello
,E/acms    ( 1775): Could not unregister removed application com.example.hello
,W/GeofencerStateMachine( 1407): Ignoring removeGeofence because network location is disabled.
D/PMS     (  903): acquireWL(428349b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1407 10028 null
I/FeedHostManager( 1247): [onResume]
,I/FeedProviderManager( 1247): onResume
I/SocialFeedProvider( 1247): +onResume
I/SocialFeedProvider( 1247): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1247): -onResume
,I/ConnectivityHelper( 1247): [getCurrentConnectionType] no network connection
,W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 3298): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3298): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  903): releaseWL(428349b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.launcher (1247/10075)
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
W/AccTypeManager( 1306): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1306): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/AccTypeManager( 1306): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 3075 uid 10355
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,W/Binder  ( 1183): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1183): java.lang.NullPointerException
W/Binder  ( 1183): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1183): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1183): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1183): 	at dalvik.system.NativeStart.run(Native Method)
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
,I/InputMethodManagerService(  903): Enable input method client, pid=1247
E/ExternalAccountType( 1306): Unsupported attribute readOnly
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{427f2f30 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3680 uid=10080 gids={50080, 5001, 1028, 1015}
,I/SoundPicker( 3680): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3680): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3680): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3680): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3680): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3680): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3680): MODE_GSM access default DB
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3680): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3680): MODE_GSM access default DB
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3341
,I/ActivityManager(  903): Killing 3341:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/DFPI.PIReciver( 3634): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3634): onHandleIntent
,I/DFPI.ApkInstallService( 3634): Media Scan Finished Case 
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,D/DFPI.ApkInstallService( 3634): check CID = HTC__032
,I/DFPI.ApkInstallService( 3634): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  903): Resuming delayed broadcast
,I/SoundPicker( 3680): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3680): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3680): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3680): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 3680): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3680): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3680): MODE_GSM access default DB
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3680): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3680): MODE_GSM access default DB
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,W/PackageManager(  903): Unable to load service info ResolveInfo{426b1a90 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  903): Recipient 3341
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/DFPI.PIReciver( 3634): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3634): onHandleIntent
,I/DFPI.ApkInstallService( 3634): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3634): check CID = HTC__032
,I/DFPI.ApkInstallService( 3634): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,I/SoundPicker( 3680): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3680): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3680): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 3680): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3680): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3680): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3680): MODE_GSM access default DB
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3680): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3680): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3680): MODE_GSM access default DB
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3680): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content:/,/media/internal/audio/media/94 type=8
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3680): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3680): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3680): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  903): Resuming delayed broadcast
E/SharedPreferencesImpl( 3612): Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
E/SQLiteDatabase( 3612): Failed to open database '/data/data/com.google.android.music/databases/music.db'.
E/SQLiteDatabase( 3612): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3612): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3612): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3612): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3612): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3612): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3612): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3612): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3612): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3612): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3612): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3612): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3612): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3612): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3612): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/SQLiteDatabase( 3612): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 3612): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/SQLiteDatabase( 3612): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/SQLiteDatabase( 3612): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/SQLiteDatabase( 3612): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/SQLiteDatabase( 3612): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/SQLiteDatabase( 3612): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/SQLiteDatabase( 3612): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 3612): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3612): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/SQLiteDatabase( 3612): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3612): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 3612): threadid=16: thread exiting with uncaught exception (group=0x416f4e30)
E/AndroidRuntime( 3612): FATAL EXCEPTION: MediaStoreImportService
E/AndroidRuntime( 3612): Process: com.google.android.music:main, PID: 3612
E/AndroidRuntime( 3612): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3612): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3612): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3612): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3612): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3612): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3612): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3612): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3612): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3612): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3612): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3612): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3612): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3612): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3612): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/AndroidRuntime( 3612): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 3612): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/AndroidRuntime( 3612): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/AndroidRuntime( 3612): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/AndroidRuntime( 3612): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/AndroidRuntime( 3612): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/AndroidRuntime( 3612): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/AndroidRuntime( 3612): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3612): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3612): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/AndroidRuntime( 3612): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3612): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  903): App crashed! Process: com.google.android.music:main
,E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  903): start
,W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml

```
