#### Test 50388019c82294c_thali02_HTC-HTC One M9 Logs


```
--------- beginning of main
D/HtcModeClient( 4868): onDestroy
,E/cutils-trace( 5434): Error opening trace file: Permission denied (13)
D/CustomizationManager( 5434): ====startRecUseTime====
D/htc.customization.log.level( 5434):  is 
W/CustomizationLogLevel( 5434): Level value is invalid, use default level 2
D/CustomizationManager( 5434):  Read ACC file spent 0.048 (s)
D/CIDMapFileReader( 5434): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5434): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5434): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5434): Parsing tag item name = HTC__031
D/CIDMapFileReader( 5434): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5434): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5434): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5434): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5434): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5434): Parsing tag item name = HTC__Y13
V/CustomizationCIDLoader( 5434): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5434): Parsing tag category name = application
I/CustomizationCIDLoader( 5434): Parsing tag category name = system
I/CustomizationCIDLoader( 5434): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5434): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5434): add string-array item, value = 42507
I/CustomizationCIDLoader( 5434): add string-array item, value = 21902
I/CustomizationCIDLoader( 5434): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5434): add string-array item, value = 23420
I/CustomizationCIDLoader( 5434): add string-array item, value = 22299
I/CustomizationCIDLoader( 5434): add string-array item, value = 24002
I/CustomizationCIDLoader( 5434): add string-array item, value = 23210
I/CustomizationCIDLoader( 5434): add string-array item, value = 23205
I/CustomizationCIDLoader( 5434): add string-array item, value = 23806
I/CustomizationCIDLoader( 5434): add string-array item, value = 23430
I/CustomizationCIDLoader( 5434): add string-array item, value = 23408
I/CustomizationCIDLoader( 5434): add string-array item, value = 27205
I/CustomizationCIDLoader( 5434): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5434): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5434): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5434): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5434): add string-array item, value = 27205:C:1:0
I/CustomizationCIDLoader( 5434): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5434): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5434): add string-array item, value = 23210:D:0:0
I/CustomizationCIDLoader( 5434): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5434): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5434): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5434): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5434): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5434): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5434): Parsing tag category name = AudioService
D/CustomizationManager( 5434):  Read CID file spent 0.085 (s)
D/CustomizationManager( 5434):  All configurations done spent 0.085 (s)
--------- beginning of system
I/ActivityManager( 1052): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 5434 on display 0
D/PMS     ( 1052): acquireHCC(11246041): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1052 1000 null
W/asset   ( 1052): Copying FileAsset 0x5588c336c0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     ( 1052): acquireHCC(1516f9e6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1052 1000 null
D/PMS     ( 1052): acquireWL(3515bf7d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1052 1000 null
I/FeedHostManager( 1801): [onPause]
I/FeedProviderManager( 1801): onPause
I/AnimationUtil( 1052): isHTCRecent(HelloWorld/Recent screens.)/1
I/FeedHostManager( 1801): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@1419547c
I/SocialFeedProvider( 1801): +onPause
I/SocialFeedProvider( 1801): -onPause
D/HtcSystemUPManager( 1052): HtcSystemUPolicy [canLog (default)] category: launch, enable: true
I/ActivityManager( 1052): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5452 uid=10193 gids={50193, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/art     (  550): Explicit concurrent mark sweep GC freed 8665(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 141KB/4MB, paused 125us total 10.956ms
I/art     (  550): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 141KB/4MB, paused 99us total 7.635ms
I/TrimMemoryManager( 1801): [trimMemory] 20
I/art     (  550): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 141KB/4MB, paused 103us total 7.775ms
W/asset   ( 5452): Copying FileAsset 0xabba12e8 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/StatusBarManagerService( 1052): setSystemUiVisibility(0x0)
D/StatusBarManagerService( 1052): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 1052): hiding MENU key
I/PhoneStatusBar( 1426): setSystemUiNavVisibility(false,false,false)
I/WebViewFactory( 5452): Loading com.google.android.webview version 37 (1602158-arm) (code 111201)
I/LibraryLoader( 5452): Loading: webviewchromium
I/LibraryLoader( 5452): Time to load native libraries: 46 ms (timestamps 6439-6485)
I/LibraryLoader( 5452): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5452): Binding Chromium to main looper Looper (main, tid 1) {330a7eee}
I/LibraryLoader( 5452): Expected native library version number "",actual native library version number ""
I/chromium( 5452): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5452): Initializing chromium process, renderers=0
W/art     ( 5452): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5452): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 5452): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5452): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46784 len=2953
I/chromium( 5452): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:34 off:229540 len:643667
D/BluetoothAdapter( 5452): 137936783: getState() :  mService = null. Returning STATE_OFF
I/Adreno  ( 5452): EGLInit: QTI Build: 02/02/15, 7356efb, I9716ce229b
W/chromium( 5452): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5452): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5452): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5452): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5452): CordovaWebView is running on device made by: HTC
W/art     ( 5452): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5452): Attempt to remove local handle scope entry from IRT, ignoring
D/FindExtension( 5452): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 5452): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@33eb7a4c, mServedView=org.apache.cordova.engine.SystemWebView{3d4e6a95 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@31af7aa
I/InputMethodManagerService( 1052): Disable input method client, pid=1801
D/StatusBarManagerService( 1052): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService( 1052): Enable input method client, pid=5452
I/PhoneStatusBar( 1426): setImeWindowStatus(false,false)
I/ActivityManager( 1052): Displayed com.example.hello/.MainActivity: +393ms
D/PMS     ( 1052): releaseWL(3515bf7d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/chromium( 5452): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 5452): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 5452): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 5452): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5452): 
I/chromium( 5452): [INFO:SkFontConfigInterface_android.cpp(227)] ---- system font and fallback font files specify a duplicate font /system/fonts/XinGothic-HTC-Regular.ttf, skipping the second occurrence
I/chromium( 5452): [INFO:SkFontConfigInterface_android.cpp(227)] ---- system font and fallback font files specify a duplicate font /system/fonts/XinGothic-HTC-Bold.ttf, skipping the second occurrence
I/chromium( 5452): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5452): 
D/jxcore_app_log( 5452): JniHelper::setJavaVM(0xaaddb9d0), pthread_self() = -1410563216
D/JX-Cordova( 5452): jxcore cordova android initializing
W/jxcore-log( 5452): Initializing JXcore engine
W/jxcore-log( 5452): JXcore engine is ready
W/jxcore-log( 5452): Starting JXcore engine
W/jxcore-log( 5452): Platform android
W/jxcore-log( 5452): 
W/jxcore-log( 5452): Process ARCH arm
W/jxcore-log( 5452): 
I/jxcore-log( 5452): JXcore Cordova bridge is ready!
I/jxcore-log( 5452): 
W/jxcore-log( 5452): JXcore engine is started
E/jxcore-log( 5452): >> HTC-HTC One M9
E/jxcore-log( 5452): 
I/jxcore-log( 5452): Total memory 2860257280
I/jxcore-log( 5452): 
I/jxcore-log( 5452): Free memory 182329344
I/jxcore-log( 5452): 
I/jxcore-log( 5452): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5452): 
I/jxcore-log( 5452): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5452): 
I/jxcore-log( 5452): userPath [ 'www' ]
I/jxcore-log( 5452): 
I/jxcore-log( 5452): Size 1080 1776
I/jxcore-log( 5452): 
I/jxcore-log( 5452): Screen Brightness 142
I/jxcore-log( 5452): 
E/jxcore-log( 5452): Dummy Error Log.
E/jxcore-log( 5452): 
D/PMS     ( 1052): releaseHCC(11246041): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     ( 1052): releaseHCC(1516f9e6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 5452): getBuffer is called!!!!
I/jxcore-log( 5452): 
,D/PMS     ( 1052): acquireWL(997e52a): PARTIAL_WAKE_LOCK  *alarm* 0x1 1052 1000 WorkSource{10057},
V/AlarmManager( 1052): sending alarm PendingIntent{5fb8f1b: PendingIntentRecord{3b9858b8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1447782129470, Int=0
,D/Finsky  ( 5263): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1052): sending alarm PendingIntent{3f2729f6: PendingIntentRecord{3cba01f7 com.android.vending startService}}, i=null, t=0, cnt=1, w=1447782134209, Int=0
,V/AlarmManager( 1052): sending alarm PendingIntent{3d64864: PendingIntentRecord{3dbde2a1 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=68345, Int=0,
,D/AlarmReceiver( 4868): ACTION_RESTART_INTENT
,D/LocalBluetoothProfile( 4868): getPriorityOnValue = 100
D/PMS     ( 1052): releaseWL(997e52a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
D/LocalBluetoothProfile( 4868): getPriorityOffValue = 0
D/Utils   ( 4868): CMD:getprop ro.htc.htcmode.socket.type
I/System  ( 4868): exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/HtcModeClient( 4868): start the htcmodeservice thread
D/HtcModeClient( 4868): initCanAgent
I/CANMesgAgentLocalSocket( 4868): CANAgent Id = 0
V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/HtcModeClient( 4868): sense info: version = none, id = 2
,D/HtcModeClient( 4868): onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
D/HtcModeClient( 4868): connectState: BT_TURNON_BYME = false
D/HtcModeClient( 4868): connectState: CONNECTION_READY = false
D/HtcModeClient( 4868): connectState: ENABLE_PROJECTBYAPP = false
D/HtcModeClient( 4868): connectState: ENTER_PROJECTMODE = false
D/HtcModeClient( 4868): connectState: PHONE_PULGIN = false
D/HtcModeClient( 4868): connectState: Force_AWAKE = false
D/HtcModeClient( 4868): connectState: PHONE_PULGIN = true
D/HtcModeClient( 4868): connectState: POWERCONNECTED_READY = true,
V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/HtcModeClient( 4868): display info: width = 1080, height = 1776
D/HtcModeClient( 4868): display info: mode = 10
,D/libc    ( 5263): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 5263): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5263): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5263): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5263): [NET] android_getaddrinfo_proxy+
D/libc    ( 5263): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  513): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  513): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  513): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  513): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5263): [NET] android_getaddrinfo_proxy-, NODATA
,D/Finsky  ( 5263): [447] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 5263): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.,
,I/art     ( 1052): Explicit concurrent mark sweep GC freed 25798(1234KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.977ms total 156.199ms
,I/ActivityManager( 1052): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5517 uid=10020 gids={50020, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  549): Explicit concurrent mark sweep GC freed 8638(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 155KB/4MB, paused 184us total 23.629ms
,W/ResourcesManager( 5517): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5517): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  549): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 155KB/4MB, paused 110us total 15.719ms
,D/GmsApplication( 5517): Forcing legacy multidex for PROD_LMP build.
,I/art     (  549): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 155KB/4MB, paused 112us total 14.994ms
,D/GmsApplication( 5517): SignalHandler installed.
D/libc    ( 5263): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 5263): [NET] android_getaddrinfofornet-, err=8
I/MultiDex( 5517): VM with version 2.1.0 has multidex support
I/MultiDex( 5517): install
W/Finsky  ( 5263): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/MultiDex( 5517): MultiDexExtractor.load(/data/app/com.google.android.gms-1/base.apk, false)
,I/MultiDex( 5517): loading existing secondary dex files,
I/MultiDex( 5517): load found 3 secondary dex files,
,I/MultiDex( 5517): install done,
,V/JNIHelp ( 5517): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...,
,W/ActivityThread( 5517): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5517): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ee368b9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5517): Installed default security provider GmsCore_OpenSSL
,I/PackageManager( 1052):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2270, uid=10020, userID:0
,I/PackageManager( 1052):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=2270, uid=10020, userID:0
I/PackageManager( 1052):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=2270, uid=10020, userID:0
D/WearableService( 2093): callingUid 10020, callindPid: 2093
,E/MDM     ( 2093): [157] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2270): Restart initialization of location
,D/GCM     ( 2015): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2015): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 2270): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/PMS     ( 1052): acquireWL(185c54c7): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 2093 10020 WorkSource{10020 com.google.android.gms}
W/GCoreFlp( 2093): No location to return for getLastLocation()
D/PMS     ( 1052): releaseWL(185c54c7): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10020 com.google.android.gms}
,W/FusedLocationProvider( 2015): location=null
,D/PMS     ( 1052): acquireWL(1a0eeaf4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2015 10020 WorkSource{10020 com.google.android.gms}
,D/PMS     ( 1052): releaseWL(1a0eeaf4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
,D/NativeLibraryUtils( 5517): Install completed successfully. count=17 extracted=0
,I/art     ( 5517): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 5517): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/art     ( 2015): Explicit concurrent mark sweep GC freed 14292(800KB) AllocSpace objects, 1(20KB) LOS objects, 42% free, 5MB/9MB, paused 1.120ms total 51.674ms
,V/Finsky  ( 5263): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/libc    ( 5263): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 5263): [NET] android_getaddrinfofornet-, err=8
,W/Finsky  ( 5263): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 5263): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 5263): [1] DailyHygiene.access$600: Logging device features
,D/Finsky  ( 5263): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 2093): client connected with version: 8296000,
,I/HtcModeClient( 4868): handler message = 4011,
D/HtcModeClient( 4868): getConnectionCheckCount first 0,
,D/HtcModeClient( 4868): getConnectionCheckCount count = 6
,E/HtcModeClient( 4868): Check connection and retry 7 times.
,D/HtcModeClient( 4868): setConnectionCheckCount count = 7
,D/HtcModeClient( 4868): setupRestart delayedTime = 3000
,D/HtcModeClient( 4868): setBtPriority priority = on
D/HtcModeClient( 4868): unbindBlueToothService
,D/HtcModeClient( 4868): Don't start project servcice
D/HtcModeClient( 4868): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 4868): connectState: CONNECTION_READY = false
D/SilentMusic( 4868): call stop
W/HtcModeClient( 4868): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 4868): read the terminate packet, so break
,D/HtcModeClient( 4868): onDestroy
,D/Process ( 1052): killProcessQuiet, pid=5068
I/ActivityManager( 1052): Killing 5068:com.htc.calendar/u0a7 (adj 15): empty #17
D/Process ( 1052): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
,I/ActivityManager( 1052): Recipient 5068
,D/Process ( 1052): killProcessQuiet, pid=5068
D/Process ( 1052): com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup( 1052): failed to open /acct/uid_10007/pid_5068/cgroup.procs: No such file or directory
,I/IntentController( 1426): receive(android.intent.action.BATTERY_CHANGED,2,false),
D/PMS     ( 1052): acquireWL(9628390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1052 1000 null
D/DotMatrix( 1495): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/BatteryService( 1052): n_update end
D/PMS     ( 1052): releaseWL(9628390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1495): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver( 1052): updateBatteryInfo
D/UsbnetService( 1052): BroadcastReceiver::onReceive+
D/PowerUI ( 1426): closing low battery warning: level=37
D/UsbnetService( 1052): onReceive BATTERY_CHANGED
D/UsbnetService( 1052):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/NotificationService( 1052): plugged=true pluggin=true
D/UsbnetService( 1052): BroadcastReceiver::onReceive-
D/PMS     ( 1052): runPSCheck
D/WifiController( 1052): handleMessage: E msg.what=155652
D/HtcPowerSaver( 1052): Checking...
D/WifiController( 1052): processMsg: ApStaDisabledState
I/HtcPowerSaver( 1052): >> updateStatus
D/WifiController( 1052): processMsg: DefaultState
D/WifiController( 1052): battery changed pluggedType: 2
D/WifiController( 1052): handleMessage: X
D/PowerUI ( 1426): plugged = true, health = 2, mBatteryLevel = 37, mPluggedBatteryLevel = 37, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver( 1052): updateStatus (8000,37,-1,false,false,false,-1)
I/HtcPowerSaver( 1052): << updateStatus
,I/BatteryController( 1426): status:2 level:37 unsupport:false plugged:true,
I/FlashlightController( 1426): batteryLevelChange:37
,D/BluetoothManagerService( 1052): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService( 1052): disable(): mBluetooth = null mBinding = false
W/Settings:Agent( 1052): MONITOR_LOG
W/Settings:Agent( 1052): name: bluetooth_on
W/Settings:Agent( 1052): value: 0,
W/Settings:Agent( 1052): >> traceCallingStack()
W/Settings:Agent( 1052): Process.myPid(): 1052,
W/Settings:Agent( 1052): Process.myTid(): 2169,
W/Settings:Agent( 1052): Process.myUid(): 1000
W/Settings:Agent( 1052): 
W/Settings:Agent( 1052): 
W/System.err( 1052): java.lang.Throwable: stack dump
,W/System.err( 1052): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err( 1052): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56),
W/System.err( 1052): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err( 1052): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err( 1052): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err( 1052): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err( 1052): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:360)
W/System.err( 1052): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:644)
W/System.err( 1052): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err( 1052): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent( 1052): 
W/Settings:Agent( 1052): << traceCallingStack(): 8(ms)
D/BluetoothManagerService( 1052): Message: 2
,D/WifiManager( 5452): setWifiEnabled: Base Package Name=com.example.hello, uid=10193
D/WifiService( 1052): New client listening to asynchronous messages
,E/WifiTrafficPoller( 1052): ADD_CLIENT: 9
,D/WifiService( 1052): setWifiEnabled: false pid=5452, uid=10193
W/Settings:Agent( 1052): MONITOR_LOG
E/WifiService( 1052): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent( 1052): name: wifi_on
I/WifiService( 1052): isSprintWifiRestricted(): false
W/Settings:Agent( 1052): value: 0
,I/WifiService( 1052): isMdmWifiRestricted(): false
W/Settings:Agent( 1052): >> traceCallingStack()
W/Settings:Agent( 1052): Process.myPid(): 1052
W/Settings:Agent( 1052): Process.myTid(): 1786
W/Settings:Agent( 1052): Process.myUid(): 1000
W/Settings:Agent( 1052): 
W/Settings:Agent( 1052): 
W/System.err( 1052): java.lang.Throwable: stack dump
W/System.err( 1052): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err( 1052): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err( 1052): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err( 1052): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err( 1052): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err( 1052): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err( 1052): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151)
W/System.err( 1052): 	,at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err( 1052): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1170)
W/System.err( 1052): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err( 1052): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent( 1052): 
W/Settings:Agent( 1052): << traceCallingStack(): 2(ms)
D/WifiController( 1052): handleMessage: E msg.what=155656
D/WifiController( 1052): processMsg: ApStaDisabledState
D/WifiController( 1052): handleMessage: X
I/jxcore-log( 5452): ****TEST TOOK:  5044  ms ****
I/jxcore-log( 5452): 
,I/jxcore-log( 5452): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5452): 
,D/AutomaticBrightnessController( 1052): setAmbientLux to brighter = 0.6,
,E/cutils-trace( 5560): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 5560): ====startRecUseTime====,
D/htc.customization.log.level( 5560):  is ,
W/CustomizationLogLevel( 5560): Level value is invalid, use default level 2
,D/CustomizationManager( 5560):  Read ACC file spent 0.028 (s),
D/CIDMapFileReader( 5560): Parsing tag item name = HTC__001,
D/CIDMapFileReader( 5560): Parsing tag item name = HTC__002,
D/CIDMapFileReader( 5560): Parsing tag item name = HTC__016,
D/CIDMapFileReader( 5560): Parsing tag item name = HTC__031
,D/CIDMapFileReader( 5560): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5560): Parsing tag item name = HTC__102,
D/CIDMapFileReader( 5560): Parsing tag item name = HTC__A07,
D/CIDMapFileReader( 5560): Parsing tag item name = HTC__J15
,D/CIDMapFileReader( 5560): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5560): Parsing tag item name = HTC__Y13
,V/CustomizationCIDLoader( 5560): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5560): Parsing tag category name = application,
I/CustomizationCIDLoader( 5560): Parsing tag category name = system,
I/CustomizationCIDLoader( 5560): Parsing tag category name = Settings,
I/CustomizationCIDLoader( 5560): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 5560): add string-array item, value = 42507
I/CustomizationCIDLoader( 5560): add string-array item, value = 21902
,I/CustomizationCIDLoader( 5560): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5560): add string-array item, value = 23420
,I/CustomizationCIDLoader( 5560): add string-array item, value = 22299
I/CustomizationCIDLoader( 5560): add string-array item, value = 24002
,I/CustomizationCIDLoader( 5560): add string-array item, value = 23210
I/CustomizationCIDLoader( 5560): add string-array item, value = 23205
,I/CustomizationCIDLoader( 5560): add string-array item, value = 23806
I/CustomizationCIDLoader( 5560): add string-array item, value = 23430
,I/CustomizationCIDLoader( 5560): add string-array item, value = 23408
I/CustomizationCIDLoader( 5560): add string-array item, value = 27205
I/CustomizationCIDLoader( 5560): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5560): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5560): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5560): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5560): add string-array item, value = 27205:C:1:0
I/CustomizationCIDLoader( 5560): add string-array item, value = 22299:D:0:0
,I/CustomizationCIDLoader( 5560): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5560): add string-array item, value = 23210:D:0:0
I/CustomizationCIDLoader( 5560): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5560): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5560): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5560): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5560): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5560): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5560): Parsing tag category name = AudioService
D/CustomizationManager( 5560):  Read CID file spent 0.048 (s)
D/CustomizationManager( 5560):  All configurations done spent 0.048 (s)
,D/PackageManager( 1052): deletePackageAsUser: pkg=com.example.hello, pid=5560, uid=2000 userid=0
,I/ActivityManager( 1052): Force stopping com.example.hello appid=10193 user=-1: uninstall pkg
,D/Process ( 1052): killProcessQuiet, pid=5452
I/ActivityManager( 1052): Killing 5452:com.example.hello/u0a193 (adj 0): stop com.example.hello
D/Process ( 1052): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6354 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6152 
,W/PackageSettings( 1052): Skipping PackageSetting{160891cd com.test.thalitest/10192} due to missing metadata,
,I/ActivityManager( 1052): Recipient 5452,
I/WindowState( 1052): WIN DEATH: Window{1e8cc05d u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService( 1052): Client connection lost with reason: 4
E/InputEventReceiver( 1548): Looper::removeFd(34) is failed, result(0), input channel 'ClientState{9786dd2 uid 10193 pid 5452} (c)'
,W/ActivityManager( 1052): Force removing ActivityRecord{28d0ab27 u0 com.example.hello/.MainActivity t67}: app died, no saved state
,I/ActivityManager( 1052): Force stopping com.example.hello appid=10193 user=0: pkg removed
,W/ActivityManager( 1052): Spurious death for ProcessRecord{14681489 5452:com.example.hello/u0a193}, curProc for 5452: null
,D/DotMatrix( 1495): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1495): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1495): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,I/[MirrorLinkServer]MirrorLinkServer( 2674): Broadcast Received::Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/[MirrorLinkServer]MirrorLinkServer( 2674): ACTION_PACKAGE_REMOVED intent received
D/[MirrorLinkServer]MirrorLinkServer( 2674): Counter : 1
D/[MirrorLinkServer]MirrorLinkConnectionReceiver( 2674): notifyMlSevrer
,I/FeedHostManager( 1801): [onResume],
D/PMS     ( 1052): acquireWL(2cb47045): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 2093 10020 WorkSource{10020 com.google.android.gms}
I/FeedProviderManager( 1801): onResume
I/SocialFeedProvider( 1801): +onResume
I/SocialFeedProvider( 1801): updateAccounts - Accounts is no change,
,I/SocialFeedProvider( 1801): -onResume
D/AccTypeManager( 2032): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/ConnectivityHelper( 1801): [getCurrentConnectionType] no network connection
,W/GeofencerStateMachine( 2093): Ignoring removeGeofence because network location is disabled.,
,D/PMS     ( 1052): releaseWL(2cb47045): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
I/[MirrorLinkServer]MirrorLinkServer( 2674): onStartCommand() Action : android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService( 1052): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/[MirrorLinkServer]MirrorLinkServer( 2674): Application Removed
D/[MirrorLinkServer]MirrorLinkServer( 2674):  Application removed : com.example.hello
D/[MirrorLinkServer]d( 2674): onApplicationRemoved
I/[MirrorLinkServer]d( 2674): Package name found : com.example.hello
W/SystemReader( 1052): Cannot find grip_rejection_width, use default value instead
I/art     ( 3799): Explicit concurrent mark sweep GC freed 575(38KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 3MB/5MB, paused 1.116ms total 44.940ms
D/AccTypeManager( 2032): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/[MirrorLinkServer]c( 2674): onApplicationUpdationCompleted, sending broadcast
I/[MirrorLinkServer]MirrorLinkServer( 2674): Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
D/[MirrorLinkServer]MirrorLinkServer( 2674): ML_PACKAGE_UPDATE_COMPLETED intent received
D/[MirrorLinkServer]MirrorLinkServer( 2674): Counter : 0
I/[MirrorLinkServer]MirrorLinkConnectionReceiver( 2674): checkAndStopMLSession
I/[MirrorLinkServer]MirrorLinkConnectionReceiver( 2674): Stopping Service
I/ActivityManager( 1052): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver: pid=5580 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a
,D/VoicemailCleanupService( 2075): Cleaning up data for package: com.example.hello
D/StatusBarManagerService( 1052): setSystemUiVisibility(0x700)
,D/StatusBarManagerService( 1052): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 1052): hiding MENU key
,D/FindExtension( 1801): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,D/PhoneApp( 1771): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/AccTypeManager( 2032): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ThreadedRenderer( 1801): Defer allocateBuffers to drawing time
I/Prism.ItemManager( 1801): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1801): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/InputMethodManagerService( 1052): Got RemoteException sending setActive(false) notification to pid 5452 uid 10193
D/StatusBarManagerService( 1052): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService( 1052): Enable input method client, pid=1801
I/ConfigManager( 1801): [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447782139657
,E/ExternalAccountType( 2032): Unsupported attribute readOnly
,I/ConfigManager( 1801): [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,I/art     ( 1052): Explicit concurrent mark sweep GC freed 20729(1542KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 15MB/23MB, paused 1.491ms total 149.566ms
,D/Process ( 1052): killProcessQuiet, pid=4787,
W/ResourcesManager( 1052): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Process ( 1052): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/ActivityManager( 1052): Killing 4787:com.google.android.gm/u0a95 (adj 15): empty #17
,D/StatusBarManagerService( 1052): setSystemUiVisibility(0xc0000700),
W/PackageManager( 1052): Unable to load service info ResolveInfo{a57a087 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager( 1052): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager( 1052): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager( 1052): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager( 1052): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager( 1052): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager( 1052): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager( 1052): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager( 1052): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager( 1052): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager( 1052): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager( 1052): 	at com.android.server.SystemServer.run(SystemServer.java:331)
W/PackageManager( 1052): 	at com.android.server.SystemServer.main(SystemServer.java:232)
W/PackageManager( 1052): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager( 1052): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager( 1052): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager( 1052): 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/StatusBarManagerService( 1052): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/ConfigManager( 1801): [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
D/StatusBarManagerService( 1052): hiding MENU key
,I/ConfigManager( 1801): [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447782139762,
,I/ConfigManager( 1801): [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,I/ConfigManager( 1801): [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,D/JobSchedulerService( 1052): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ConfigManager( 1801): [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447782139815
,I/ActivityManager( 1052): Recipient 4787
,D/Process ( 1052): killProcessQuiet, pid=4787
W/libprocessgroup( 1052): failed to open /acct/uid_10095/pid_4787/cgroup.procs: No such file or directory
D/Process ( 1052): com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
I/PhoneStatusBar( 1426): setSystemUiNavVisibility(false,false,false)
I/PhoneStatusBar( 1426): setImeWindowStatus(false,false)
D/TaskPersister( 1052): removeObsoleteFile: deleting file=67_task.xml
I/PhoneStatusBar( 1426): setSystemUiNavVisibility(false,false,false)
I/ConfigManager( 1801): [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
D/Prism.PackageStateRece_( 1801): action: android.intent.action.PACKAGE_REMOVED
,I/[PluginManager]RegisterService( 1594): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
,I/UpdateIcingCorporaServi( 3799): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE,
,I/[PluginManager]RegisterService( 1594): handle notify Blinkfeed plugin client changed
,I/ActivityManager( 1052): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5605 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a
I/ConfigManager( 1801): [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,I/ConfigManager( 1801): [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447782139899
,D/PMS     ( 1052): acquireWL(3c24bd10): PARTIAL_WAKE_LOCK  Icing 0x1 2270 10020 WorkSource{10020 com.google.android.gms},
,I/ConfigManager( 1801): [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,W/ContextImpl( 5605): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 ,
,I/ConfigManager( 1801): [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.,
,D/PMS     ( 1052): acquireWL(2901444b): PARTIAL_WAKE_LOCK  AsyncService 0x1 5227 10126 null,
I/ApplicationLogger( 3799): canRun() : Opted Out,
,D/PMS     ( 1052): releaseWL(2901444b): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
I/UpdateIcingCorporaServi( 3799): UpdateCorporaTask done [took 120 ms] updated apps [took 119 ms] 
,D/Process ( 1052): killProcessQuiet, pid=5131
I/ActivityManager( 1052): Killing 5131:com.htc.themepicker/u0a59 (adj 15): empty #17
D/Process ( 1052): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/ConfigManager( 1801): [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447782139982
,I/ConfigManager( 1801): [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,I/ConfigManager( 1801): [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,I/ConfigManager( 1801): [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447782140046
,I/ConfigManager( 1801): [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,I/ActivityManager( 1052): Recipient 5131
,I/ConfigManager( 1801): [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,D/Process ( 1052): killProcessQuiet, pid=5131
W/libprocessgroup( 1052): failed to open /acct/uid_10059/pid_5131/cgroup.procs: No such file or directory
D/Process ( 1052): com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PackageBroadcastService( 2270): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 2270): Clearing selected account for com.example.hello
,I/ConfigManager( 1801): [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447782140096
D/ChimeraCfgMgr( 2270): Loading module com.google.android.gms.games from APK com.google.android.gms
,E/SQLiteLog( 2015): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 2015): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x5588785db0
,I/LocationSettingsChecker( 2270): Removing dialog suppression flag for package com.example.hello,
,E/AndroidRuntime( 2015): FATAL EXCEPTION: main
E/AndroidRuntime( 2015): Process: com.google.process.gapps, PID: 2015
E/AndroidRuntime( 2015): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2015): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 2015): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 2015): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 2015): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2015): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 2015): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 2015): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 2015): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 2015): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 2015): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 2015): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2015): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2015): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 2015): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2015): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2015): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 2015): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 2015): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2015): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2015): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 2015): 	... 9 more
,E/SQLiteDatabase( 2270): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2270): ,	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2270): 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2270): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2270): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 2270): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2270): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2270): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2270): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 2270): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2270): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2270): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
,E/SQLiteOpenHelper( 2270): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2270): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2270): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2270): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteOpenHelper( 2270): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2270): Opened metrics.db in read-only mode
E/DropBoxManagerService( 1052): Can't write: system_app_crash
E/DropBoxManagerService( 1052): java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1052): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService( 1052): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1052): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12649)
E/DropBoxManagerService( 1052): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1052): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1052): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1052): 	... 5 more
D/gH_CompatibleDatabase( 2270): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2270): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/ActivityManager( 1052): App crashed! Process: com.google.process.gapps
E/SQLiteLog( 2270): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
D/gH_CompatibleDatabase( 2270): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 2270): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 2270): Process: com.google.android.gms, PID: 2270
E/AndroidRuntime( 2270): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 2270): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2270): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 2270): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2270): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2270): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 2270): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 2270): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 2270): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2270): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2270): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 2270): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ConfigManager( 1801): [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
E/ActivityManager( 1052): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 2270): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.,db'.
E/SQLiteDatabase( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 2270): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2270): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2270): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 2270): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2270): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 2270): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 2270): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2270): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2270): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteOpenHelper( 2270): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2270): Opened phenotype.db in read-only mode
E/DropBoxManagerService( 1052): Can't write: system_app_crash
E/DropBoxManagerService( 1052): java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1052): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService( 1052): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1052): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12649)
E/DropBoxManagerService( 1052): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1052): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1052): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1052): 	... 5 more
W/OpenGLRenderer( 1801): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
D/StatusBarManagerService( 1052): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService( 1052): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 1052): hiding MENU key
I/ConfigManager( 1801): [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,I/PhoneStatusBar( 1426): setSystemUiNavVisibility(false,false,false)
I/ConfigManager( 1801): [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447782140196
D/PMS     ( 1052): acquireWL(142a875d): PARTIAL_WAKE_LOCK  *alarm* 0x1 1052 1000 WorkSource{10027}
V/AlarmManager( 1052): sending alarm PendingIntent{1a4828d2: PendingIntentRecord{3dbde2a1 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=73408, Int=0
W/BaseAppContext( 2270): Using Auth Proxy for data requests.
W/BaseAppContext( 2270): Using Auth Proxy for data requests.
,E/SQLiteDatabase( 2270): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 2270): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/SQLiteDatabase( 2270): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/SQLiteDatabase( 2270): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2270): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 2270): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 2270): Runtime exception while performing operation
E/ClearPendingStateOp( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/ClearPendingStateOp( 2270): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/ClearPendingStateOp( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/ClearPendingStateOp( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 2270): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 2270): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/ClearPendingStateOp( 2270): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/ClearPendingStateOp( 2270): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 2270): ,	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 2270): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/ClearPendingStateOp( 2270): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 2270): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 2270): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 2270): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 2270): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
F/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
F/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
F/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
F/ClearPendingStateOp( 2270): ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
F/ClearPendingStateOp( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
F/ClearPendingStateOp( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
F/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 2270): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 2270): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
F/ClearPendingStateOp( 2270): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
F/ClearPendingStateOp( 2270): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 2270): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 2270): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
F/ClearPendingStateOp( 2270): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 2270): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 2270): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 2270): 	at java.lang.Thread.run(Thread.java:818)
,I/ConfigManager( 1801): [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
E/DropBoxManagerService( 1052): Can't write: system_app_wtf
E/DropBoxManagerService( 1052): java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1052): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService( 1052): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1052): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12649)
E/DropBoxManagerService( 1052): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1052): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1052): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1052): 	... 5 more
,E/AndroidRuntime_2_crash( 2270): crash in the same process: IntentService[PackageBroadcastService]
E/AndroidRuntime_2_crash( 2270): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean com.google.android.gms.measurement.internal.ag.h()' on a null object reference
E/AndroidRuntime_2_crash( 2270): 	at com.google.android.gms.measurement.internal.u.a(SourceFile:141)
E/AndroidRuntime_2_crash( 2270): 	at com.google.android.gms.measurement.internal.w.a(SourceFile:34)
E/AndroidRuntime_2_crash( 2270): 	at com.google.android.gms.measurement.internal.d.l(SourceFile:304)
E/AndroidRuntime_2_crash( 2270): 	at com.google.android.gms.measurement.internal.d.<init>(SourceFile:150)
E/AndroidRuntime_2_crash( 2270): 	at com.google.android.gms.measurement.internal.ak.<init>(SourceFile:107)
E/AndroidRuntime_2_crash( 2270): 	at com.google.android.gms.measurement.internal.ak.a(SourceFile:405)
E/AndroidRuntime_2_crash( 2270): 	at com.google.android.gms.measurement.internal.ak.a(SourceFile:416)
E/AndroidRuntime_2_crash( 2270): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/AndroidRuntime_2_crash( 2270): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime_2_crash( 2270): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime_2_crash( 2270): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime_2_crash( 2270): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ConfigManager( 1801): [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,I/ConfigManager( 1801): [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447782140286
,E/SQLiteDatabase( 2270): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
,E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.o.run(SourceFile:615)
E/AndroidRuntime_3_crash( 2270): crash in the same process: Open database in background
E/AndroidRuntime_3_crash( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_3_crash( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_3_crash( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_3_crash( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_3_crash( 2270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_3_crash( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_3_crash( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_3_crash( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_3_crash( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_3_crash( 2270): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/AndroidRuntime_3_crash( 2270): 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
E/AndroidRuntime_3_crash( 2270): 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
E/AndroidRuntime_3_crash( 2270): 	at com.google.android.gms.drive.database.o.run(SourceFile:615)
,I/ConfigManager( 1801): [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,I/HtcContextualWidgetDataManager( 1801): onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId 136e11db-f190-482e-a19a-b656cd241ac8, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null))]
,I/DeviceManagement( 5167): PackageUpdateReceiver: vvv Package removed: [com.example.hello]
,I/DeviceManagement( 5167): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.example.hello, operation=3}]]
,I/DeviceManagement( 5167): WorkflowService: Starting workflow service
,I/DeviceManagement( 5167): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@388bc5ab] args=[Bundle[mParcelledData.dataSize=108]]
I/DeviceManagement( 5167): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5167): PackageUpdateWorkflow: Package update: package=com.example.hello, operation=REMOVE
I/DeviceManagement( 5167): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 5167): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager( 1052): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5644 uid=10089 gids={50089, 9997, 3003} abi=arm64-v8a
,I/ConfigManager( 1801): [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.,
,D/ConnectivityService( 1052): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/DeviceManagement( 5167): BackgroundController: *** Processing package remove for appID=com.example.hello,
,I/DeviceManagement( 5167): SessionStateController: Checking invariants...
,E/SQLiteDatabase( 5644): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5644): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5644): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5644): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5644): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5644): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5644): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5644): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5644): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5644): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5644): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5644): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5644): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5644): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5644): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5644): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5644): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5644): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase( 5644): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/SQLiteDatabase( 5644): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5644): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 5644): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 5644): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5644): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5644): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5644): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 5644): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5644): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5644): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 5644): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 5644): FATAL EXCEPTION: main
E/AndroidRuntime( 5644): Process: com.android.documentsui, PID: 5644
E/AndroidRuntime( 5644): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5644): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 5644): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 5644): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 5644): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5644): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5644): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 5644): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5644): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5644): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 5644): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 5644): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5644,): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5644): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5644): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5644): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5644): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5644): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5644): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5644): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5644): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5644): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5644): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5644): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5644): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5644): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5644): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5644): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/AndroidRuntime( 5644): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/AndroidRuntime( 5644): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5644): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 5644): 	... 9 more
D/ErrorReport( 1052): HtcErrorReportManager Begin---add error logs to dropbox
E/ActivityManager( 1052): App crashed! Process: com.android.documentsui
W/System.err( 1052): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err( 1052): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err( 1052): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err( 1052): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err( 1052): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err( 1052): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err( 1052): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err( 1052): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 1052): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 1052): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1052): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 1052): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1052): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1052): 	... 12 more
W/System.err( 1052): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1052): 	at java.io.FileOutputStream.<init>(FileO,utputStream.java:87)
W/System.err( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err( 1052): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err( 1052): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err( 1052): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err( 1052): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err( 1052): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err( 1052): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12569)
W/System.err( 1052): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12233)
W/System.err( 1052): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12205)
W/System.err( 1052): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err( 1052): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2566)
W/System.err( 1052): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 1052): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 1052): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1052): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1052): 	... 14 more
W/System.err( 1052): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err( 1052): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err( 1052): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err( 1052): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err( 1052): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err( 1052): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err( 1052): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12569)
W/System.err( 1052): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12233)
W/System.err( 1052): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12205)
W/System.err( 1052): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err( 1052): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2566)
W/System.err( 1052): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 1052): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 1052): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1052): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1052): 	... 14 more
D/AlarmReceiver( 4868): ACTION_RESTART_INTENT
D/LocalBluetoothProfile( 4868): getPriorityOnValue = 100
E/ErrorReport( 1052): HtcErrorReportManager.Error in dumping error information
E/ErrorReport( 1052): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1447782140463.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport( 1052): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport( 1052): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport( 1052): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport( 1052): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport( 1052): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport( 1052): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport( 1052): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport( 1052): 	... 4 more
D/LocalBluetoothProfile( 4868): getPriorityOffValue = 0
W/ActivityManager( 1052): Can't addPackageDependency on system process
D/Utils   ( 4868): CMD:getprop ro.htc.htcmode.socket.type
I/System  ( 4868): exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
D/HtcModeClient( 4868): start the htcmodeservice thread
,D/HtcModeClient( 4868): initCanAgent
D/PMS     ( 1052): releaseWL(142a875d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
I/CANMesgAgentLocalSocket( 4868): CANAgent Id = 0
D/HtcModeClient( 4868): sense info: version = none, id = 2
D/HtcModeClient( 4868): display info: width = 1080, height = 1776
D/HtcModeClient( 4868): display info: mode = 10
I/ActivityManager( 1052): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5674 uid=10016 gids={50016, 9997, 1028, 1015, 1023} abi=arm64-v8a
D/HtcModeClient( 4868): onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
D/HtcModeClient( 4868): connectState: BT_TURNON_BYME = false
D/HtcModeClient( 4868): connectState: CONNECTION_READY = false
D/HtcModeClient( 4868): connectState: ENABLE_PROJECTBYAPP = false
D/HtcModeClient( 4868): connectState: ENTER_PROJECTMODE = false
D/HtcModeClient( 4868): connectState: PHONE_PULGIN = false
D/HtcModeClient( 4868): connectState: Force_AWAKE = false
D/HtcModeClient( 4868): connectState: PHONE_PULGIN = true
D/HtcModeClient( 4868): connectState: POWERCONNECTED_READY = true
E/SharedPreferencesImpl( 4868): Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
E/SharedPreferencesImpl( 4868): Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
,E/SQLiteDatabase( 5167): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5167): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5167): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5167): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 5167): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5167): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5167): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5167): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 5167): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197),
E/SQLiteDatabase( 5167): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 5167): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5167): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 5167): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 5167): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 5167): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5167): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5167): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5167): 	at java.lang.Thread.run(Thread.java:818)
W/DriveInitializer( 2270): Awaiting to be initialized
E/AndroidRuntime_4_crash( 2270): crash in the same process: Background initialization thread
E/AndroidRuntime_4_crash( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_4_crash( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_4_crash( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_4_crash( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_4_crash( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_4_crash( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_4_crash( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_4_crash( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
,E/AndroidRuntime_4_crash( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_4_crash( 2270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_4_crash( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_4_crash( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_4_crash( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_4_crash( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_4_crash( 2270): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/AndroidRuntime_4_crash( 2270): 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
E/AndroidRuntime_4_crash( 2270): 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
E/AndroidRuntime_4_crash( 2270): 	at com.google.android.gms.drive.database.k.a(SourceFile:248)
E/AndroidRuntime_4_crash( 2270): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/AndroidRuntime_4_crash( 2270): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/AndroidRuntime_4_crash( 2270): 	at com.google.android.gms.drive.s.run(SourceFile:62)
W/DriveInitializer( 2270): Background init thread started
E/SQLiteDatabase( 2270): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.k.a(SourceFile:248)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.s.run(SourceFile:62)
E/DocListDatabase( 2270): Failed to delete from ContentFileDeletionLock154 table
E/DocListDatabase( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DocListDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DocListDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/DocListDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/DocListDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DocListDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DocListDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DocListDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/DocListDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/DocListDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/DocListDatabase( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/DocListDatabase( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/DocListDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DocListDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DocListDatabase( 2270): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/DocListDatabase( 2270): 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
E/DocListDatabase( 2270): 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
E/DocListDatabase( 2270): 	at com.google.android.gms.drive.database.k.a(SourceFile:248)
E/DocListDatabase( 2270): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/DocListDatabase( 2270): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/DocListDatabase( 2270): 	at com.google.android.gms.drive.s.run(SourceFile:62)
W/DriveInitializer( 2270): Background init thread ended
E/SQLiteDatabase( 2270): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.k.a(SourceFile:248)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/SQLiteDatabase( 2270): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2270): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2270): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 2270): 	at java.lang.Thread.run(Thread.java:818)
E/DriveAsyncService( 2270): not an error (code 0): Could not open the database in read/write mode.
E/DriveAsyncService( 2270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DriveAsyncService( 2270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DriveAsyncService( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/DriveAsyncService( 2270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/DriveAsyncService( 2270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DriveAsyncService( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DriveAsyncService( 2270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DriveAsyncService( 2270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/DriveAsyncService( 2270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/DriveAsyncService( 2270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/DriveAsyncService( 2270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/DriveAsyncService( 2270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/DriveAsyncService( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DriveAsyncService( 2270): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DriveAsyncService( 2270): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/DriveAsyncService( 2270): 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
E/DriveAsyncService( 2270): 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
E/DriveAsyncService( 2270): 	at com.google.android.gms.drive.database.k.a(SourceFile:248)
E/DriveAsyncService( 2270): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 2270): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 2270): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 2270): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2270): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 2270): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2270): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2270): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2270): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager( 1052): Killing 5111:com.google.android.partnersetup/u0a23 (adj 15): empty #17
I/DeviceManagement( 5167): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5167): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5167): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.example.hello
E/SQLiteDatabase( 5167): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5167): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5167): 	at androi,d.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5167): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5167): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5167): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 5167): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/SQLiteDatabase( 5167): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 5167): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 5167): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 5167): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 5167): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5167): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5167): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 5167): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@388bc5ab]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 5167): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 5167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/DeviceManagement( 5167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/DeviceManagement( 5167): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 5167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 5167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 5167): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/DeviceManagement( 5167): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/DeviceManagement( 5167): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/DeviceManagement( 5167): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
W/DeviceManagement( 5167): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/DeviceManagement( 5167): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/DeviceManagement( 5167): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/DeviceManagement( 5167): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 5167): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 5167): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 5167): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/DeviceManagement( 5167): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 5167): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 5167): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 5167): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 5167): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 5167): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 5167): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 5167): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 5167): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 5167): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 5167): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 5167): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 5167): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 5167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 5167): 	at android.os.Looper.loop(Looper.java:155)
W/DeviceManagement( 5167): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 5167): WorkflowService: Stopping workflow service
D/Process ( 1052): killProcessQuiet, pid=5111
D/Process ( 1052): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
D/ExternalStorage( 5674): After updating volumes, found 1 active roots
,I/ActivityManager( 1052): Recipient 5111
,D/Process ( 1052): killProcessQuiet, pid=5111
D/Process ( 1052): com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/libprocessgroup( 1052): failed to open /acct/uid_10023/pid_5111/cgroup.procs: No such file or directory
,D/Documents( 5644): Update found 7 roots in 408ms,
,I/Icing   ( 2270): Indexing CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF from com.google.android.googlequicksearchbox,
,E/Icing   ( 2270): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system,
E/Icing   ( 2270): Could not init tag ds.tag.deleted
,I/Icing   ( 2270): Indexing done CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF
D/PMS     ( 1052): releaseWL(3c24bd10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,I/Prism.ItemManager( 1801): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1801): loadItems() com.htc.launcher.pageview.WidgetManager@36be9034 +,
I/Prism.WidgetManager( 1801): onLoadItems() +,
,W/ResourcesManager( 1801): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,E/qdoverlay(  485): Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=8
,E/qdoverlay(  485): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  485): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  485): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  485): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  485): MdpCtrl close error in unset
,E/qdhwcomposer(  485): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
E/SurfaceFlinger(  485): eventControl(0, 1) failed Operation not permitted
,W/ResourcesManager( 1801): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,

```
