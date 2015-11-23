#### Test 5038801932cd575_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
I/ActivityManager(  909): Recipient 3885
,W/ActivityManager(  909): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
--------- beginning of main
E/cutils-trace( 4492): Error opening trace file: Permission denied (13)
I/Gmail   ( 4466): getAccountsCursor
W/GAV2    ( 4466): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/AndroidHttpClient( 4189): Leak found
E/AndroidHttpClient( 4189): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4189): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4189): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4189): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4189): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4189): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4189): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4189): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4189): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4189): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4189): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4189): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4189): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4189): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4189): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4189): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4466, uid=10106, userID:0
W/ActivityManager(  909): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  909): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/CustomizationManager( 4492): ====startRecUseTime====
D/htc.customization.log.level( 4492):  is 
W/CustomizationLogLevel( 4492): Level value is invalid, use default level 2
I/Gmail   ( 4466): Observing account changes for notifications
W/ActivityManager(  909): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4466, uid=10106, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4466, uid=10106, userID:0
E/Gmail   ( 4466): Error finding the version of the Email provider.....
E/Gmail   ( 4466): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4466): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4466): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4466): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4466): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4466): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4466): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4466): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4466): We do not support migrating this version of the Email provider.
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4466, uid=10106, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4466, uid=10106, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4466, uid=10106, userID:0
I/Gmail   ( 4466): getAccountsCursor
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4466, uid=10106, userID:0
V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  909): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4527 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
W/ActivityManager(  909): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4466, uid=10106, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4466, uid=10106, userID:0
W/ActivityManager(  909): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CustomizationManager( 4492):  Read ACC file spent 0.037 (s)
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4492): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4492): Parsing tag category name = system
I/CustomizationCIDLoader( 4492): Parsing tag category name = application
I/CustomizationCIDLoader( 4492): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4492): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4492): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4492): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4492): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4492): add string-array item, value = 42507
I/CustomizationCIDLoader( 4492): add string-array item, value = 21902
I/CustomizationCIDLoader( 4492): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4492): add string-array item, value = 23420
I/CustomizationCIDLoader( 4492): add string-array item, value = 22299
I/CustomizationCIDLoader( 4492): add string-array item, value = 24002
I/CustomizationCIDLoader( 4492): add string-array item, value = 23210
I/CustomizationCIDLoader( 4492): add string-array item, value = 23205
I/CustomizationCIDLoader( 4492): add string-array item, value = 23806
I/CustomizationCIDLoader( 4492): add string-array item, value = 23430
I/CustomizationCIDLoader( 4492): add string-array item, value = 23408
I/CustomizationCIDLoader( 4492): add string-array item, value = 27205
I/CustomizationCIDLoader( 4492): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4492): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4492): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4492): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4492): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4492): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4492): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4492): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4492): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4492): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4492): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4492): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4492):  Read CID file spent 0.085 (s)
D/CustomizationManager( 4492):  All configurations done spent 0.085 (s)
E/SQLiteLog( 4466): (283) recovered 437 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4492 on display 0
D/PMS     (  909): acquireHCC(f81022): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 909 1000 null
D/PMS     (  909): acquireHCC(1ad56ab3): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 909 1000 null
W/asset   (  909): Copying FileAsset 0x559c91b320 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  909): acquireWL(33ab0c6e): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/AnimationUtil(  909): isHTCRecent(HelloWorld/Recent screens.)/5
I/FeedHostManager( 1525): [onPause]
I/FeedProviderManager( 1525): onPause
I/FeedHostManager( 1525): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2aeeec6a
I/SocialFeedProvider( 1525): +onPause
I/SocialFeedProvider( 1525): -onPause
I/ActivityManager(  909): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4553 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/HtcSystemUPManager(  909): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/art     (  408): Explicit concurrent mark sweep GC freed 8672(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 249us total 18.788ms
I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 296us total 14.395ms
I/TrimMemoryManager( 1525): [trimMemory] 20
I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 220us total 19.722ms
I/art     (  909): Explicit concurrent mark sweep GC freed 14190(762KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 4.886ms total 176.719ms
W/asset   ( 4553): Copying FileAsset 0xac49c020 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/StatusBarManagerService(  909): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  909): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  909): hiding MENU key
E/ActivityThread( 4466): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@350a4616 that was originally bound here
E/ActivityThread( 4466): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@350a4616 that was originally bound here
E/ActivityThread( 4466): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4466): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4466): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 4466): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 4466): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4466): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4466): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4466): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4466): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4466): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4466): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4466): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4466): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4466): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4466): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4466): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  909): Unbind failed: could not find connection for android.os.BinderProxy@23fc8234
,I/WebViewFactory( 4553): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 4553): Time to load native libraries: 16 ms (timestamps 7478-7494)
I/LibraryLoader( 4553): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4553): Binding Chromium to main looper Looper (main, tid 1) {c008b19}
I/LibraryLoader( 4553): Expected native library version number "",actual native library version number ""
I/Gmail   ( 4466): notifyAccountChanged
I/chromium( 4553): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/Gmail   ( 4466): getAccountsCursor
I/Gmail   ( 4466): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/BrowserStartupController( 4553): Initializing chromium process, singleProcess=true
I/Gmail   ( 4466): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/PMS     (  909): acquireWL(1965615): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4466 10106 null
W/art     ( 4553): Attempt to remove local handle scope entry from IRT, ignoring
I/Gmail   ( 4466): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
E/SysUtils( 4553): ApplicationContext is null in ApplicationStatus
D/PMS     (  909): acquireWL(1965615): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4466 10106 null
I/Gmail   ( 4466): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
D/PMS     (  909): acquireWL(1965615): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4466 10106 null
I/Gmail   ( 4466): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
I/Gmail   ( 4466): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4466): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4466, uid=10106, userID:0
D/Process (  909): killProcessQuiet, pid=3919
I/ActivityManager(  909): Killing 3919:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/chromium( 4553): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 4553): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4553): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4553): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4553): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4553): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4553): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4553): Local Branch: 
I/Adreno-EGL( 4553): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4553): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4553):                  d74aa161a12b9c6fc6332151
I/ActivityManager(  909): Recipient 3919
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20e801f6:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 4553): 885120140: getState() :  mService = null. Returning STATE_OFF
D/LocationManagerService(  909): getProviders()=[passive]
I/Gmail   ( 4466): master sync=false, engine sync=true
I/ActivityManager(  909): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4602 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
I/Gmail   ( 4466): getAccountsCursor
W/art     ( 4553): Attempt to remove local handle scope entry from IRT, ignoring
V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4466): master sync=false, engine sync=true
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4527, uid=10085, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4527, uid=10085, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4527, uid=10085, userID:0
W/AwContents( 4553): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 4553): CordovaWebView is running on device made by: HTC
W/art     ( 4553): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4553): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 4553): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/BroadcastQueue(  909): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
D/WifiService(  909): New client listening to asynchronous messages
E/WifiTrafficPoller(  909): ADD_CLIENT: 6
I/ActivityManager(  909): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4644 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  909): Killing 3958:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=3958
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
I/VelvetNetworkClient( 4527): Network connection not availble
D/FindExtension( 4553): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ActivityManager(  909): Recipient 3958
I/InputMethodManager( 4553): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@122cfb9a, mServedView=org.apache.cordova.engine.SystemWebView{24ec3ccb VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@31deca8
I/InputMethodManagerService(  909): Disable input method client, pid=1525
D/StatusBarManagerService(  909): swetImeWindowStatus vis=0 backDisposition=0
I/ActivityManager(  909): Displayed com.example.hello/.MainActivity: +865ms
I/InputMethodManagerService(  909): Enable input method client, pid=4553
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/PMS     (  909): releaseWL(33ab0c6e): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  909): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=4677 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
W/XT9_C   ( 1354): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1354): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1354): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1354): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 4553): Cannot call determinedVisibility() - never saw a connection for the pid: 4553
I/chromium( 4553): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/ResourcesManager( 4677): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/WebViewFactory( 4527): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/JsMessageQueue( 4553): Set native->JS mode to OnlineEventsBridgeMode
I/CalendarProvider2( 4677): Created com.android.providers.calendar.CalendarAlarmManager@34f307de(com.htc.providers.calendar.HtcCalendarProvider@b942dbf)
E/AndroidProtocolHandler( 4553): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/LibraryLoader( 4527): Time to load native libraries: 18 ms (timestamps 8261-8279)
I/LibraryLoader( 4527): Expected native library version number "",actual native library version number ""
D/CalendarProvider2( 4677): wait start:true
W/art     ( 4527): Attempt to remove local handle scope entry from IRT, ignoring
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
D/CalendarProvider2( 4677): wait end:false
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
W/art     ( 4527): Attempt to remove local handle scope entry from IRT, ignoring
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
,D/FlexNetS( 4677): updateSvcAllowedInSettings:false
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
D/jxcore_app_log( 4553): JniHelper::setJavaVM(0xab32d8f8), pthread_self() = -1402711736
D/JX-Cordova( 4553): jxcore cordova android initializing
I/ActivityManager(  909): Start proc com.htc.showme for broadcast com.htc.showme/.update.MobileNetworkTurnOnReceiver: pid=4716 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/ContactMessageStore( 1473): MSG_NOTIFY_CS_TO_SYNC >>
I/ActivityManager(  909): Killing 3055:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=3055
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/ContactMessageStore( 1473): MSG_NOTIFY_CS_TO_SYNC <<
W/jxcore-log( 4553): Initializing JXcore engine
W/jxcore-log( 4553): JXcore engine is ready
W/jxcore-log( 4553): Starting JXcore engine
I/ActivityManager(  909): Recipient 3055
I/[AppShowMeDebug]MobileNetworkTurnOnReceiver( 4716): onReceive statefalse
I/ActivityManager(  909): Killing 4001:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=4001
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
W/jxcore-log( 4553): Platform android
W/jxcore-log( 4553): 
W/jxcore-log( 4553): Process ARCH arm
W/jxcore-log( 4553): 
I/ActivityManager(  909): Recipient 4001
I/jxcore-log( 4553): JXcore Cordova bridge is ready!
I/jxcore-log( 4553): 
W/jxcore-log( 4553): JXcore engine is started
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
D/FlexNetS( 4677): updateSvcAllowedInSettings:false
I/ActivityManager(  909): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=4738 uid=10009 gids={50009, 9997, 5001, 3003, 1028, 1015, 1023} abi=armeabi-v7a
E/jxcore-log( 4553): >> HTC-HTC One M8s
E/jxcore-log( 4553): 
I/jxcore-log( 4553): Total memory 1931808768
I/jxcore-log( 4553): 
I/jxcore-log( 4553): Free memory 88137728
I/jxcore-log( 4553): 
I/jxcore-log( 4553): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4553): 
I/jxcore-log( 4553): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4553): 
I/jxcore-log( 4553): userPath [ 'www' ]
I/jxcore-log( 4553): 
I/jxcore-log( 4553): Size 1080 1776
I/jxcore-log( 4553): 
I/jxcore-log( 4553): Screen Brightness 142
I/jxcore-log( 4553): 
E/jxcore-log( 4553): Dummy Error Log.
E/jxcore-log( 4553): 
D/browser ( 4738): Browser versionCode = 760001576 versionName = 7.0.2514321356
W/SWE_UI  ( 4738): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 4738): Loading: swewebviewchromium
I/LibraryLoader( 4738): Time to load native libraries: 43 ms (timestamps 1004-1047)
I/LibraryLoader( 4738): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 4738): Initializing chromium process, renderers=9
I/LibraryLoader( 4738): Expected native library version number "",actual native library version number ""
I/chromium( 4738): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 4738): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 4738): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
I/Adreno-EGL( 4738): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4738): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4738): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4738): Local Branch: 
I/Adreno-EGL( 4738): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4738): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4738):                  d74aa161a12b9c6fc6332151
D/Process (  909): killProcessQuiet, pid=4029
I/ActivityManager(  909): Killing 4029:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 4
I/ActivityManager(  909): Recipient 4029
,V/IccIntentReceiver( 1646): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT icc slot: 0,
D/PMS     (  909): releaseHCC(f81022): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  909): releaseHCC(1ad56ab3): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/SIMStateChangeReceiver( 4677): SIM state: ABSENT,
I/SIMStateChangeReceiver( 4677): remove notification
,D/FlexNetS( 4677): updateSvcAllowedInSettings:false
,I/ActivityManager(  909): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=4787 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a,
,I/jxcore-log( 4553): getBuffer is called!!!!,
I/jxcore-log( 4553): 
,I/CalendarProvider2( 4677): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4677): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Process (  909): killProcessQuiet, pid=4092,
I/ActivityManager(  909): Killing 4092:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  909): Recipient 4092
,D/ExchangePolicystatus( 3747): onReceive()
I/ActivityManager(  909): Killing 4121:com.android.settings:remote/1000 (adj 15): empty #17
D/ExchangePolicystatus( 3747): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 3747): onReceive(): else
D/Process (  909): killProcessQuiet, pid=4121
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/SmsReceiver( 3747): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/PMS     (  909): releaseWL(1965615): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null,
,I/ActivityManager(  909): Recipient 4121
,D/GCM     ( 1918): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1918): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4252): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/AccTypeManager( 4787): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 4787): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana,
I/ActivityManager(  909): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4817 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4252, uid=10024, userID:0,
,I/art     (  407): Explicit concurrent mark sweep GC freed 8675(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 215us total 31.207ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 180us total 22.220ms
W/ResourcesManager( 4817): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4817): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 168us total 20.425ms
I/MultiDex( 4817): VM with version 2.1.0 has multidex support
I/MultiDex( 4817): install
I/MultiDex( 4817): VM has multidex support, MultiDex support library is disabled.
,D/TelephUtils( 1473): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
V/IccIntentReceiver( 1646): IccIntent: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED icc state: null icc slot: 0
D/AccFlag ( 1473): sku_id=118
,D/AccTypeManager( 4787): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  909): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4843 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,D/LocationInitializer( 4252): Restart initialization of location
,E/ExternalAccountType( 4787): Unsupported attribute readOnly,
D/TelephUtils( 1473): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 83
D/AccFlag ( 1473): sku_id=118
,D/AccTypeManager( 4787): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 4787): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana,
,D/AccTypeManager( 4787): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/art     ( 1918): Explicit concurrent mark sweep GC freed 9175(499KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 14.760ms total 61.929ms
,E/ExternalAccountType( 4787): Unsupported attribute readOnly,
,V/JNIHelp ( 4817): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 4817): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 4817): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@aecdf08: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4817): Installed default security provider GmsCore_OpenSSL
,I/ImageRamCache( 4843): create image Cache, size: 31457280.,
I/ImageRamCache( 4843): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4843): create image Cache, size: 31457280.
D/WearableService( 4817): callingUid 10024, callindPid: 4817
,I/FeedSettings( 4843): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 4843): GroupBudget 0.500000 0.380000
I/FeedSettings( 4843): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4843): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4843): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 4843): loadGridSize() with Alternative
,E/MDM     ( 1821): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/art     (  909): Explicit concurrent mark sweep GC freed 11656(603KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.374ms total 137.442ms
,D/TelephUtils( 1473): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50,
,D/AccFlag ( 1473): sku_id=118
,D/CustomHighlightReceiver( 4843): [custom highlight] onReceive,
,D/CustomHighlightService( 4843): [custom highlight] onHandleIntent
D/NewsDB  ( 4843): set custom highlight []
,I/ActivityManager(  909): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4873 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,D/TelephUtils( 1473): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
D/AccFlag ( 1473): sku_id=118
,D/CustomHighlightService( 4843): [custom highlight] set tags 
,D/Process (  909): killProcessQuiet, pid=4145
I/ActivityManager(  909): Killing 4145:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  909): Recipient 4145
,V/AlarmManager(  909): sending alarm PendingIntent{33272352: PendingIntentRecord{17d93623 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=60157, Int=0
,D/MessagingShortcutReceiver( 3747): keep hiding shortcut bubble,
,D/MessagingShortcut( 3747): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 3747): After query: 0
D/MessagingShortcut( 3747): mPresentUnreadCount: -1
,D/MessageUtils( 3747): [getShortcut] com.htc.sense.mms.ui.ConversationList, false,
D/MessagingShortcut( 3747): setMsgShortcutDrawable> 0, false
,D/MessagingShortcut( 3747): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderNotification, total:0
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  909): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4895 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
,W/ResourcesManager( 4895): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/ActivityManager(  909): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4918 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{bb75b95 u0 com.htc.HTCSpeaker/.NGFService},
,D/TodoTaskshortcut( 4895): update TASK shortcut>
,I/ActivityManager(  909): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4941 uid=10035 gids={50035, 9997} abi=arm64-v8a
,D/Process (  909): killProcessQuiet, pid=4168
I/ActivityManager(  909): Killing 4168:com.android.smith/1000 (adj 15): empty #17
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MdScBoot( 4873): [492.1.] 30@-214612 -> 40
,D/MdScBootUi( 4873): [492.1.2.] boot 118,
I/HtcModeClient( 3156): handler message = 4011
E/HtcModeClient( 3156): Check connection and retry 4 times.
D/MdScSimSt( 4873): [492.1.2.] qry 118: 0+1 running 0
,I/ActivityManager(  909): Recipient 4168
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4966 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Process (  909): killProcessQuiet, pid=4079,
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  909): Killing 4079:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4079,
,V/AlarmManager(  909): sending alarm PendingIntent{eaa58d9: PendingIntentRecord{bc4283f com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=60526, Int=0,
,D/Process (  909): killProcessQuiet, pid=4226,
I/ActivityManager(  909): Killing 4226:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  909): Recipient 4226
,D/SMSBackup( 4966): Got a database change event
D/Process (  909): killProcessQuiet, pid=4189
I/ActivityManager(  909): Killing 4189:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  909): Recipient 4189,
,D/Process (  909): killProcessQuiet, pid=3339,
I/ActivityManager(  909): Killing 3339:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  909): Recipient 3339,
,D/PMS     (  909): acquireWL(3670229e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1918 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  909): acquireWL(3c7f117f): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4895 10069 null,
,D/PMS     (  909): acquireWL(a9554c): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4895 10069 null,
,D/PMS     (  909): releaseWL(3c7f117f): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  909): releaseWL(3670229e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,E/TodoTaskNotifyService( 4895): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 4895): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 4895): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4895): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4895): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4895): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  909): releaseWL(a9554c): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4895): stopSelfResult true
,D/MtpReceiver( 3709): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3709): [MTP][handleUsbStateAsync]1:1-
,D/MtpReceiver( 3709): [MTP][handleUsbState]+
,I/ActivityManager(  909): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4990 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,D/MtpReceiver( 3709): [MTP][scanExternalVolumeIfNeed] scan external volume,
,D/MtpReceiver( 3709): [MTP][handleUsbState]-
D/MtpReceiver( 3709): [MTP][handleMessage]-
D/MtpService( 3709): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 3709): TotalSize=1886532,MediaCacheLimit=6000,
,D/MtpService( 3709): [isMtpConnected] connected: true
,D/SyncApplication( 4990): Loading default preferences
,W/Resources( 4990): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,E/MediaScannerService( 3709): [onStartCommand] --- Should not be here, redirect request. ----,
E/MediaScannerService( 3709): [handleMessage] --- Should not be here, ignore request. ----
,E/WifiTrafficPoller(  909): ADD_CLIENT: 7,
D/WifiService(  909): New client listening to asynchronous messages
,D/SyncApplication( 4990): Overriding preferences with custom values,
,D/SyncApplication( 4990): Updating preferences succeeded,
,E/SyncApplication( 4990): Application created.
,W/VolumeInfo( 4990): Unable to read mount points
W/VolumeInfo( 4990): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4990): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 4990): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 4990): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 4990): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 4990): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 4990): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 4990): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 4990): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 4990): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 4990): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 4990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 4990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 4990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 4990): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 4990): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4990): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 4990): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 4990): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 4990): 	... 13 more
I/CalendarDefines( 4990): getNewCalendarAuthority()...
V/VolumeInfo( 4990): Found 0 mount point(s)
,V/VolumeInfo( 4990): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4990, uid=10005, userID:0
,W/PackageManager(  909): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync,
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4990, uid=10005, userID:0
D/SyncApplication( 4990): enableAppOperation()+
W/PackageManager(  909): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/VolumeInfo( 4990): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/SyncApplication( 4990): enableAppOperation()-
,D/HTCUtilities( 4990): isNeorSinged() + 
,D/VolumeInfo( 4990): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355},
,W/VolumeInfo( 4990): Can not create volume ID for unmounted volume null
,E/MediaScannerServiceEx( 3709): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3709): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,D/HTCUtilities( 4990): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/MediaScannerServiceEx( 3709): [handleExternalVolume] ext storage
D/HTCUtilities( 4990): isNeorSinged() return false
,D/MediaProviderUtils( 3709): calcVolumeId: /storage/emulated/0
D/CDMountReceiver( 4990): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 4990): USB connected to PC
D/MediaProviderUtils( 3709): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3709): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3709): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3709): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 3709): [update][6]#0#
D/MediaProvider( 3709): [update][1]#0#
,D/MediaProvider( 3709): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted,
D/MtpService( 3709): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3709): [update][8]#1#
,D/MediaScannerServiceEx( 3709): [AliveExtStorageRows]-0, 0
,D/PMS     (  909): acquireWL(593ee13): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3709 10017 null
,D/MediaScanner( 3709): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1,
D/FOTAReceiver( 4990): onReceive() enter 
D/FOTAReceiver( 4990): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  909): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5022 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
D/Process (  909): killProcessQuiet, pid=4383
I/ActivityManager(  909): Killing 4383:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  909): Recipient 4383
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5022): -onCreate()
,V/Settings:HtcSettingsApplication( 5022): [5022/5022] onCreate(),
,D/TetherSettings( 5022): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 5022): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5022): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5022): Cust_ConnectToPC   : spcsc>false
D/        ( 5022): Cust_ConnectToPC   : IPT>true
D/        ( 5022): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5022): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/SmartNS_Utility( 5022): hasRemovableStorageSlot: true,
D/SmartNS_Utility( 5022): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5022): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 5022): usb_cable_connect = 1
,D/SmartNS_Utility( 5022): usb_denied = 0
,I/SmartNS_NSReceiver( 5022): locked:falsesecurity:falseisLocked:false,
D/SmartNS_NSReceiver( 5022): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 5022): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 5022): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 ,
,I/SmartNS_PSService( 5022): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 5022): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
I/SmartNS_PSService( 5022):  defaultType:0
I/SmartNS_PSService( 5022): fail notificaiton:false
D/SmartNS_Utility( 5022): usb_cable_connect = 1
D/SmartNS_Utility( 5022): usb_denied = 0
I/SmartNS_PSService( 5022): usb notificaiton:true
E/WifiStateMachine(  909): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  909): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5045 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActionCombine( 5022): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 5022): usb_cable_connect = 1,
D/SmartNS_Utility( 5022): usb_denied = 0
I/SmartNS_PSService( 5022): usb notificaiton:true
E/WifiStateMachine(  909): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1223): reapply : com.android.settings 1 36
,D/SmartNS_Utility( 5022): usb_cable_connect = 1
,D/SmartNS_Utility( 5022): usb_denied = 0
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/SmartNS_PSService( 5022): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 5022): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/RemoteViews( 1223): reapply : com.android.settings 1 36
,I/SocialFeedProvider( 1525): +disConnect socialManager,
I/SocialFeedProvider( 1525): disconnect socialManager
,V/AlarmManager(  909): sending alarm PendingIntent{3ab86f4e: PendingIntentRecord{16c5586f com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448315204216, Int=0
,I/SocialFeedProvider( 1525): -disConnect socialManager
,I/GAV2    ( 4466): Thread[GAThread,5,main]: No campaign data found.
,I/SocialManager[SocialBiLogHelper]( 4843): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4843): last commit ulog time 1448258067684
I/SocialManager[SocialBiLogHelper]( 4843): skip commit this time
,I/ActivityManager(  909): Killing 4466:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=4466
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  909): Recipient 4466
,I/GAv4-SVC( 4252): Google Analytics 7.8.99 is starting up.
,W/ContextImpl( 5045): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  909): acquireWL(3e5ee168): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1918 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1918): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1918): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1918): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1918): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1918): [NET] android_getaddrinfo_proxy+
D/libc    ( 1918): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1918): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  909): releaseWL(3e5ee168): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/FlexNetS( 4677): updateSvcAllowedInSettings:false
,I/ActivityManager(  909): Killing 4527:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  909): killProcessQuiet, pid=4527
,D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  909): Recipient 4527
D/WifiService(  909): Client connection lost with reason: 4
,I/[PluginManager]RegisterService( 1440): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/[PluginManager]RegisterService( 1440): handle notify Blinkfeed plugin client changed,
D/Prism.PackageStateRece_( 1525): action: android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  909): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5081 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,D/MediaProvider( 3709): [update][10]#1#,
,D/MediaScanner( 3709):  prescan time: 587ms,
D/MediaScanner( 3709):     scan time: 584ms
D/MediaScanner( 3709): postscan time: 5ms
,D/MediaScanner( 3709):    total time: 1176ms
D/MediaScanner( 3709): -----------------------------------------------------------------
D/MediaScanner( 3709): firstscan(media) time: 299ms
,D/MediaScanner( 3709): secondscan(non-media) time: 285ms
D/MediaScanner( 3709):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3709):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
,D/MediaScanner( 3709):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3709):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,D/MediaProvider( 3709): [delete][6],
D/MediaProvider( 3709): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3709): [recoverParentNodes] - 0,
D/MediaProvider( 3709): [update][6]
D/MediaScannerServiceEx( 3709): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3709): [updateImage]+
,D/MediaScannerServiceEx( 3709): [updateImage]-0
,D/PMS     (  909): releaseWL(593ee13): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3709): [1] scan finished
D/MediaProviderUtils( 3709): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3709): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3709): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3709): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3709): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 3709): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3709): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3709): [update][8]#1#
,I/DeviceManagement( 5081): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5081 dbg=false s=true
I/DeviceManagement( 5081): PackageUpdateReceiver: vvv Package added: [com.example.hello]
D/Process (  909): killProcessQuiet, pid=4716
I/ActivityManager(  909): Killing 4716:com.htc.showme/u0a81 (adj 15): empty #17
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/MediaProvider( 3709): [update][28]#0#
D/MediaScannerServiceEx( 3709): [disAliveExtStorageRows]--1, 0
,I/ActivityManager(  909): Recipient 4716
,D/MediaProviderUtils( 3709): calcVolumeId: /storage/emulated/0,
D/MediaProviderUtils( 3709): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3709): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3709): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3709): Process mounted intent for unmounted storage: /storage/usb
,I/ActivityManager(  909): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5103 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/MediaScannerServiceEx( 3709): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3709): [sendStorageAddedIfNeed]: /storage/usb : unmounted,
D/MediaProvider( 3709): [update][10]#1#
,I/art     (  407): Explicit concurrent mark sweep GC freed 8628(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 232us total 28.706ms
,D/MediaProvider( 3709): [update][30]#0#
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 345us total 23.549ms,
D/MediaScannerServiceEx( 3709): [disAliveExtStorageRows]--1, 0,
,D/HtcCupdReceiver(Provider)( 5103):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 190us total 23.606ms
,D/Process (  909): killProcessQuiet, pid=4738,
I/ActivityManager(  909): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5125 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  909): Killing 4738:com.htc.sense.browser/u0a9 (adj 15): empty #17
,D/Settings:HtcWirelessFeatureFlags( 5022): id/is att sku: 118/false
,I/ActivityManager(  909): Recipient 4738,
,E/Settings:HtcWrapHeaderInfo( 5022): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5022): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5022): updateDevelopment, bPrefShow = true,
,E/Settings:HtcUmcWidgetEnabler( 5022): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportHomeButton]support         :false
,I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi,
E/ActivityThread( 5022): Failed to find provider info for com.htc.vowifi,
E/Settings:HtcVoWifiWidgetEnabler( 5022): isSupportVoWifi: null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5022): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5022): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5022): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5022): [supportHomeButton]support         :false
,I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 5022): isSupportVoWifi: null
E/ActivityThread( 5022): Failed to find provider info for com.htc.vowifi
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5125, uid=10072, userID:0,
,W/global  ( 5125): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5125): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 5125): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5125): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5125): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  909): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5166 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/Settings( 5125): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5125): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5125, uid=10072, userID:0,
,W/ResourcesManager( 5166): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5166): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5166): VM with version 2.1.0 has multidex support,
I/MultiDex( 5166): install
I/MultiDex( 5166): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  909): Killing 4787:com.htc.contacts/u0a38 (adj 15): empty #17,
D/Process (  909): killProcessQuiet, pid=4787
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  909): Recipient 4787
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4252, uid=10024, userID:0,
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4252, uid=10024, userID:0
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4252, uid=10024, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4252, uid=10024, userID:0
,D/Finsky  ( 5125): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5125): [1] 2.run: Finished loading 1 libraries.
,D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  909): disable(): mBluetooth = null mBinding = false
W/Settings:Agent(  909): MONITOR_LOG
W/Settings:Agent(  909): name: bluetooth_on
,W/Settings:Agent(  909): value: 0
W/Settings:Agent(  909): >> traceCallingStack()
W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 936
W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
W/System.err(  909): java.lang.Throwable: stack dump
,D/Finsky  ( 5125): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  909): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  909): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  909): 
W/Settings:Agent(  909): << traceCallingStack(): 13(ms)
D/BluetoothManagerService(  909): Message: MESSAGE_DISABLE
,D/ChimeraCfgMgr( 4252): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/WifiService(  909): New client listening to asynchronous messages
D/PackageBroadcastService( 4252): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraModuleLdr( 4252): Loading module APK com.google.android.play.games
,E/WifiTrafficPoller(  909): ADD_CLIENT: 7
D/WifiManager( 4553): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
,D/PMS     (  909): acquireWL(1d7524f1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4252 10024 null
V/JNIHelp ( 5166): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 5125): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
D/WifiService(  909): setWifiEnabled: false pid=4553, uid=10373
E/WifiService(  909): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  909): isSprintWifiRestricted(): false
I/WifiService(  909): isMdmWifiRestricted(): false
,W/Settings:Agent(  909): MONITOR_LOG
W/Settings:Agent(  909): name: wifi_on
,W/Settings:Agent(  909): value: 0
W/Settings:Agent(  909): >> traceCallingStack()
W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 1162
W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
W/System.err(  909): java.lang.Throwable: stack dump
,D/AccTypeManager( 1686): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/System.err(  909): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  909): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  909): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  909): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  909): 
W/Settings:Agent(  909): << traceCallingStack(): 10(ms)
,W/SystemReader(  909): Cannot find grip_rejection_width, use default value instead
D/WifiController(  909): handleMessage: E msg.what=155656
D/WifiController(  909): processMsg: ApStaDisabledState
D/WifiController(  909): handleMessage: X
I/jxcore-log( 4553): ****TEST TOOK:  5269  ms ****
I/jxcore-log( 4553): 
I/jxcore-log( 4553): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4553): 
D/AccTypeManager( 1686): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  909): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ActivityThread( 5166): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5166): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@aecdf08: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5166): Installed default security provider GmsCore_OpenSSL
W/Prism.AllAppsManager( 1525): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1525): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1525): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4843): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4843): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PhoneApp( 1473): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
I/Launcher( 1525): Deferring update until onResume
D/Launcher( 1525): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1686): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1686): Unsupported attribute readOnly
,W/PackageManager(  909): Unable to load service info ResolveInfo{3fd732a4 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169),
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  909): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/PMS     (  909): acquireWL(df65591): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 909 1000 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(df65591): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ConfigFetchService( 4252): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 4252): launchTask
,I/BackupManagerService(  909): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/PMS     (  909): acquireWL(29b72d94): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4252 10024 WorkSource{10373 com.example.hello}
D/PMS     (  909): releaseWL(1d7524f1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/PMS     (  909): acquireWL(14cb23c4): PARTIAL_WAKE_LOCK  Icing 0x1 4252 10024 WorkSource{10024 com.google.android.gms}
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  909): plugged=true pluggin=true
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/PMS     (  909): runPSCheck
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  909): Checking...
D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  909): >> updateStatus
D/WifiController(  909): handleMessage: E msg.what=155652
D/WifiController(  909): battery changed pluggedType: 2
D/WifiController(  909): processMsg: ApStaDisabledState
D/WifiController(  909): processMsg: DefaultState
D/WifiController(  909): handleMessage: X
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/GmsNetworkLocationProvi( 1821): DISABLE
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
D/ChimeraCfgMgr( 4252): Loading module com.google.android.gms.games from APK com.google.android.play.games
I/HtcPowerSaver(  909): << updateStatus
D/ChimeraModuleLdr( 4252): Module APK com.google.android.play.games already loaded
I/GCoreNlp( 1821): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/ChimeraCfgMgr( 4252): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/PeopleContactsSync( 4252): CP2 sync disabled
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4252, uid=10024, userID:0
D/Vision  ( 4252): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
V/ConfigFetchTask( 4252): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Xna6Zn8O8ZM2DGUMUqat69UOsJXBLyTpHUD033sc4Z0-v6dcJVQDhqmwgbjZGIo9ANiEm234lINoThzo7YmcLU4h38vTg7Skh2QtEGNVvj7z5EvmaI-3xLwNGlYvTrXTw_U1OEo7Ta1VN7FXyl1DH56vW60OWTW07jmvtFPM8vAg9Y1yHr2q_tYvar_-fkHxn7Kcpo
,D/Vision  ( 4252): Failed to find package metadata for com.example.hello
D/Vision  ( 4252): No vision deps
,I/GoogleURLConnFactory( 4252): Using platform SSLCertificateSocketFactory
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5210 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,E/cutils-trace( 5200): Error opening trace file: Permission denied (13),
,D/CustomizationManager( 5200): ====startRecUseTime====
D/htc.customization.log.level( 5200):  is ,
W/CustomizationLogLevel( 5200): Level value is invalid, use default level 2
,I/art     (  909): Explicit concurrent mark sweep GC freed 22998(1220KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.517ms total 148.113ms,
,I/Icing   ( 4252): Storage manager: low false usage 1.98MB avail 5.80GB capacity 7.95GB
,D/LocationProviderProxy(  909): applying state to connected service
,D/PMS     (  909): acquireWL(e2bfa65): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1821 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  909): releaseWL(e2bfa65): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  909): applying state to connected service
,D/PMS     (  909): acquireWL(1ce6d7e1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1821 10024 WorkSource{10024 com.google.android.gms}
,D/Process (  909): killProcessQuiet, pid=4873
I/ActivityManager(  909): Killing 4873:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  909): releaseWL(1ce6d7e1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/CustomizationManager( 5200):  Read ACC file spent 0.036 (s)
,D/CIDMapFileReader( 5200): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5200): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5200): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5200): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5200): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5200): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 5200): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5200): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5200): Parsing tag category name = system
,I/CustomizationCIDLoader( 5200): Parsing tag category name = application
,I/CustomizationCIDLoader( 5200): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5200): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5200): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5200): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5200): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 5200): add string-array item, value = 42507,
I/CustomizationCIDLoader( 5200): add string-array item, value = 21902
I/CustomizationCIDLoader( 5200): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5200): add string-array item, value = 23420
I/CustomizationCIDLoader( 5200): add string-array item, value = 22299
I/CustomizationCIDLoader( 5200): add string-array item, value = 24002
I/CustomizationCIDLoader( 5200): add string-array item, value = 23210
I/CustomizationCIDLoader( 5200): add string-array item, value = 23205
I/CustomizationCIDLoader( 5200): add string-array item, value = 23806
I/CustomizationCIDLoader( 5200): add string-array item, value = 23430
,I/CustomizationCIDLoader( 5200): add string-array item, value = 23408
I/CustomizationCIDLoader( 5200): add string-array item, value = 27205
I/CustomizationCIDLoader( 5200): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5200): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5200): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5200): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5200): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5200): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5200): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5200): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5200): add string-array item, value = 23806:D:0:0
,I/CustomizationCIDLoader( 5200): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5200): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5200): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5200):  Read CID file spent 0.083 (s)
D/CustomizationManager( 5200):  All configurations done spent 0.083 (s)
,W/Icing   ( 4252): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4252): Received bad json for corpus context scoring override -- ignoring.,
W/Icing   ( 4252): Received bad json for section weights override -- ignoring.
W/Icing   ( 4252): Received bad json for corpus context scoring override -- ignoring.
,D/PackageManager(  909): deletePackageAsUser: pkg=com.example.hello, pid=5200, uid=2000 userid=0
,I/art     ( 4252): Background partial concurrent mark sweep GC freed 28923(2MB) AllocSpace objects, 26(520KB) LOS objects, 42% free, 5MB/9MB, paused 7.623ms total 101.694ms
,D/libc    ( 4252): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4252): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4252): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4252): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4252): [NET] android_getaddrinfo_proxy+
D/libc    ( 4252): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4252): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4252): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname,
I/ConfigFetchService( 4252): fetch service done; releasing wakelock
,I/ActivityManager(  909): Recipient 4873
,D/Process (  909): killProcessQuiet, pid=4553,
W/PackageSettings(  909): Skipping PackageSetting{334c18c1 com.test.thalitest/10366} due to missing metadata
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
I/ActivityManager(  909): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
I/ActivityManager(  909): Killing 4553:com.example.hello/u0a373 (adj 0): stop com.example.hello
,D/PMS     (  909): releaseWL(29b72d94): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10373 com.example.hello},
I/ConfigFetchService( 4252): stopping self
,E/InputEventReceiver( 1354): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{28f9d72e uid 10373 pid 4553} (c)'
I/ActivityManager(  909): Recipient 4553
I/WindowState(  909): WIN DEATH: Window{4cbaee2 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  909): Client connection lost with reason: 4
,W/ActivityManager(  909): Force removing ActivityRecord{2cd32870 u0 com.example.hello/.MainActivity t8}: app died, no saved state,
,D/PMS     (  909): acquireWL(3d16a906): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1821 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  909): releaseWL(3d16a906): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  909): Force stopping com.example.hello appid=10373 user=0: pkg removed,
,W/ActivityManager(  909): Spurious death for ProcessRecord{2ac9fbc7 4553:com.example.hello/u0a373}, curProc for 4553: null,
,V/AlarmManager(  909): sending alarm PendingIntent{418111d: PendingIntentRecord{2ce44f92 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448315206738, Int=0
,I/FeedHostManager( 1525): [onResume],
I/FeedProviderManager( 1525): onResume
I/SocialFeedProvider( 1525): +onResume
I/SocialFeedProvider( 1525): updateAccounts - Accounts is no change
D/PMS     (  909): acquireWL(2e73d2de): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1821 10024 WorkSource{10024 com.google.android.gms}
I/SocialFeedProvider( 1525): -onResume
I/ConnectivityHelper( 1525): [getCurrentConnectionType] no network connection
D/DotMatrix( 1307): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1307): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
W/GeofencerStateMachine( 1821): Ignoring removeGeofence because network location is disabled.
D/PMS     (  909): releaseWL(2e73d2de): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/AccTypeManager( 1686): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/Finsky  ( 5125): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/SystemReader(  909): Cannot find grip_rejection_width, use default value instead
,W/BaseAppContext( 4252): Using Auth Proxy for data requests.
,W/BaseAppContext( 4252): Using Auth Proxy for data requests.
D/StatusBarManagerService(  909): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  909): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  909): hiding MENU key
,D/AccTypeManager( 1686): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/FindExtension( 1525): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,V/Finsky  ( 5125): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/ThreadedRenderer( 1525): Defer allocateBuffers to drawing time,
,V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 4553 uid 10373
D/AccTypeManager( 1686): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/StatusBarManagerService(  909): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  909): Enable input method client, pid=1525
,D/PhoneApp( 1473): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,E/ExternalAccountType( 1686): Unsupported attribute readOnly
,W/BaseAppContext( 4252): Using Auth Proxy for data requests.
,D/StatusBarManagerService(  909): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  909): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  909): hiding MENU key
,E/Icing   ( 4252): Loading extension by file descriptor -1 failed,
,W/BaseAppContext( 4252): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4252): Using Auth Proxy for data requests.
,W/BaseAppContext( 4252): Using Auth Proxy for data requests.
,W/ResourcesManager(  909): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/PackageManager(  909): Unable to load service info ResolveInfo{9ddf631 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  909): 	,at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  909): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     (  909): Explicit concurrent mark sweep GC freed 16634(1307KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 2.097ms total 220.064ms
,W/asset   (  909): Copying FileAsset 0x559cfb7c10 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/Icing   ( 4252): updateResources: need to parse f{com.google.android.gms}
,D/JobSchedulerService(  909): Receieved: android.intent.action.PACKAGE_REMOVED,
,I/PhoneStatusBar( 1223): setImeWindowStatus(false,false),
D/TaskPersister(  909): removeObsoleteFile: deleting file=8_task.xml
,I/Icing   ( 4252): Internal init done: storage state 0
,I/Icing   ( 4252): Post-init done
,E/Icing   ( 4252): Package com.example.hello not found,
,I/GLSUser ( 1918): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
D/PMS     (  909): releaseWL(14cb23c4): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
I/GLSUser ( 1918): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1918): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1918): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5125): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/HtcModeClient( 3156): handler message = 4011
E/HtcModeClient( 3156): Check connection and retry 5 times.
,V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1918): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1918): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1918): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1918): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/Prism.ItemManager( 1525): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1525): loadItems() com.htc.launcher.pageview.WidgetManager@3b358e3a +
I/Prism.WidgetManager( 1525): onLoadItems() +
,I/GAv4    ( 5210): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5210):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5210):   adb logcat -s GAv4
I/Prism.ItemManager( 4843): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4843): loadItems() com.htc.launcher.pageview.WidgetManager@3eaa5653 +
I/Prism.WidgetManager( 4843): onLoadItems() +
,W/GAv4    ( 5210): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 1525): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAv4    ( 5210): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/OpenGLRenderer( 1525): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,W/GAv4    ( 5210): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 4843): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/AnalyticsTrackerProxyImpl( 5210): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,I/GLSUser ( 1918): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1918): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1918): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1918): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5125): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/SQLiteDatabase( 5125): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 5125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5125): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5125): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 5125): 	at com.google.android.finsky.library.Libraries$3.run(Libraries.java:234)
E/SQLiteDatabase( 5125): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5125): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5125): 	at android.os.Looper.loo,p(Looper.java:155)
E/SQLiteDatabase( 5125): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5125): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 5125): Process: com.android.vending, PID: 5125
E/AndroidRuntime( 5125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5125): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 5125): 	at com.google.android.finsky.library.Libraries$3.run(Libraries.java:234)
E/AndroidRuntime( 5125): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5125): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5125): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5125): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.android.vending
,E/SQLiteDatabase( 5210): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5210): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
,E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5210): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5210): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5210): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 5210): 	at ael.a(PG:1521)
E/SQLiteDatabase( 5210): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 5210): 	at aen.run(PG:536)
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  909): ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  909): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  909): 	... 5 more
,D/ChimeraCfgMgr( 4252): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4252): Module APK com.google.android.play.games already loaded
,D/StatusBarManagerService(  909): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  909): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  909): hiding MENU key
,E/SQLiteDatabase( 4252): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.,
E/SQLiteDatabase( 4252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 4252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 4252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 4252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4252): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4252): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4252): 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
E/SQLiteDatabase( 4252): 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:345)
E/SQLiteDatabase( 4252): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 4252): 	at com.google.android.chimera.ContentProviderProxy.superQuery(SourceFile:477)
E/SQLiteDatabase( 4252): 	at com.google.android.chimera.ContentProvider.query(SourceFile:142)
E/SQLiteDatabase( 4252): 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:357)
E/SQLiteDatabase( 4252): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 4252): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 4252): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 4252): 	at com.google.android.gms.games.broker.AccountAgent.getAccountName(AccountAgent.java:80)
E/SQLiteDatabase( 4252): 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3442)
E/SQLiteDatabase( 4252): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:24)
E/SQLiteDatabase( 4252): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/SQLiteDatabase( 4252): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/SQLiteDatabase( 4252): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4252): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4252): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 4252): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 4252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 4252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 4252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 4252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 4252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 4252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 4252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 4252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 4252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4252): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4252): 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
E/SQLite,OpenHelper( 4252): 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:345)
E/SQLiteOpenHelper( 4252): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 4252): 	at com.google.android.chimera.ContentProviderProxy.superQuery(SourceFile:477)
E/SQLiteOpenHelper( 4252): 	at com.google.android.chimera.ContentProvider.query(SourceFile:142)
E/SQLiteOpenHelper( 4252): 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:357)
E/SQLiteOpenHelper( 4252): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 4252): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 4252): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 4252): 	at com.google.android.gms.games.broker.AccountAgent.getAccountName(AccountAgent.java:80)
E/SQLiteOpenHelper( 4252): 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3442)
E/SQLiteOpenHelper( 4252): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:24)
E/SQLiteOpenHelper( 4252): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/SQLiteOpenHelper( 4252): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/SQLiteOpenHelper( 4252): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4252): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4252): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 4252): Opened games_3a3529a.db in read-only mode
E/AndroidRuntime( 4252): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 4252): Process: com.google.android.gms, PID: 4252
E/AndroidRuntime( 4252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4252): 	at com.google.android.gms.games.provider.ImageStore.initialize(ImageStore.java:149)
E/AndroidRuntime( 4252): 	at com.google.android.gms.games.provider.ImageStore.<init>(ImageStore.java:78)
E/AndroidRuntime( 4252): 	at com.google.android.gms.games.provider.GamesDataStore.initialize(GamesDataStore.java:111)
E/AndroidRuntime( 4252): 	at com.google.android.gms.games.provider.PlayGamesContentProvider.performBackgroundTask(PlayGamesContentProvider.java:1577)
E/AndroidRuntime( 4252): 	at com.google.android.gms.games.provider.PlayGamesContentProvider$1.handleMessage(PlayGamesContentProvider.java:1510)
E/AndroidRuntime( 4252): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4252): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 4252): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.google.android.gms
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  909): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  909): 	... 5 more
,E/AndroidHttpClient( 5125): Leak found
E/AndroidHttpClient( 5125): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5125): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5125): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5125): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5125): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5125): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5125): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5125): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5125): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5125): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5125): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5125): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5125): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/VoldConnector(  909): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 5210): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,E/SQLiteDatabase( 5210): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5210): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5210): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5210): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5210): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 5210): 	at ael.a(PG:1521)
E/SQLiteDatabase( 5210): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 5210): 	at aej.c(PG:139)
E/SQLiteDatabase( 5210): 	at aej.b(PG:398)
E/SQLiteDatabase( 5210): 	at agf.f(PG:417)
E/SQLiteDatabase( 5210): 	at oe.run(PG:1112)
E/SQLiteDatabase( 5210): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5210): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5210): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5210): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5210): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 5210): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 5210): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 5210): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 5210): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 5210): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 5210): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 5210): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 5210): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 5210): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 5210): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 5210): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 5210): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 5210): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 5210): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/Abstract,DatabaseInstance( 5210): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 5210): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 5210): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 5210): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 5210): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 5210): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 5210): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 5210): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 5210): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 5210): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 5210): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 5210): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 5210): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager(  909): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5281 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/SQLiteLog( 5210): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 5210): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.apps.docs/databases/google_analytics_v4.db, handle: 0x559ccf57a0
E/GAv4    ( 5210): Local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/ResourcesManager( 1525): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/SharedPreferencesImpl( 5210): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 5210): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 5210): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 5210): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.apps.docs/databases/google_analytics_v4.db, handle: 0x559ccf57a0
E/GAv4    ( 5210): Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
,E/SharedPreferencesImpl( 5210): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/CAKEMIX_CRASHED( 5210): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 5210): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 5210): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 5210): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 5210): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 5210): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 5210): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 5210): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/CAKEMIX_CRASHED( 5210): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 5210): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 5210): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/CAKEMIX_CRASHED( 5210): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 5210): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 5210): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 5210): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 5210): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 5210): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 5210): 	at aen.run(PG:536)
,W/ResourcesManager( 5210): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5210): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  909): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 5210 on display 0
,D/PMS     (  909): acquireWL(3a8aab59): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
,I/FeedHostManager( 1525): [onPause]
I/FeedProviderManager( 1525): onPause
I/FeedHostManager( 1525): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2aeeec6a
I/SocialFeedProvider( 1525): +onPause
I/SocialFeedProvider( 1525): -onPause
D/Process ( 5210): killProcess, pid=5210
D/Process ( 5210): vf.uncaughtException:213 fct.uncaughtException:0 java.lang.ThreadGroup.uncaughtException:693 
,W/ResourcesManager( 4843): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
W/ResourcesManager( 5281): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/AnimationUtil(  909): isHTCRecent(Drive/Recent screens.)/8,
,W/HtcSystemUPManager(  909): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,E/lowmemorykiller(  382): Error writing /proc/5210/oom_score_adj; errno=22
E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
E/ActivityManager(  909): TransactionSize: scheduleLaunchActivity(), TransactionTooLargeException, data size = 4316, Intent = Intent { act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras) }
W/ActivityManager(  909): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  909): android.os.TransactionTooLargeException
W/ActivityManager(  909): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  909): 	at android.os.BinderProxy.transact(Binder.java:504)
W/ActivityManager(  909): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:851)
W/ActivityManager(  909): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1203)
W/ActivityManager(  909): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1303)
W/ActivityManager(  909): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2014)
W/ActivityManager(  909): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1552)
W/ActivityManager(  909): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2536)
W/ActivityManager(  909): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:1065)
W/ActivityManager(  909): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:963)
W/ActivityManager(  909): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6882)
W/ActivityManager(  909): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:518)
W/ActivityManager(  909): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/ActivityManager(  909): 	at android.os.Binder.execTransact(Binder.java:454)
,I/ActivityManager(  909): Recipient 5210
,I/ActivityManager(  909): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=5302 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,W/ActivityManager(  909): Spurious death for ProcessRecord{145941b1 5302:com.google.android.apps.docs/u0a101}, curProc for 5210: null
,W/asset   ( 1525): Copying FileAsset 0x559ce1f9e0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,D/StatusBarManagerService(  909): setSystemUiVisibility(0x8000)
D/StatusBarManagerService(  909): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  909): hiding MENU key
,W/asset   ( 4843): Copying FileAsset 0x559ceb3e00 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1525): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1525): onLoadItems() -
I/Prism.ItemManager( 1525): loadItems() com.htc.launcher.pageview.WidgetManager@3b358e3a -
I/Prism.ItemManager( 1525): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1525): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/TrimMemoryManager( 1525): [trimMemory] 20
,I/Prism.WidgetManager( 4843): onLoadItems() -
,I/Prism.ItemManager( 4843): loadItems() com.htc.launcher.pageview.WidgetManager@3eaa5653 -
I/Prism.ItemManager( 4843): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4843): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1525): Deferring update until onResume
D/Launcher( 1525): waitUntilResume // bindAppsRemoved
,V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1918): Explicit concurrent mark sweep GC freed 11756(627KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 752us total 36.405ms
,I/GLSUser ( 1918): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1918): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1918): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1918): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1918): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5125): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5125): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/PMS     (  909): acquireWL(2c283083): PARTIAL_WAKE_LOCK  AsyncService 0x1 5281 10167 null
,D/Finsky  ( 5125): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/PMS     (  909): releaseWL(2c283083): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  909): acquireWL(223351df): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5281 10167 null
D/Finsky  ( 5125): [1] DailyHygiene.reschedule: Scheduling new run in 283 minutes (failures=4)
,E/SharedPreferencesImpl( 5125): Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
I/ActivityManager(  909): Killing 3747:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=3747
D/Process (  909): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/DeviceConnectionService( 1821): client connected with version: 7571000
,I/GAv4    ( 5302): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5302):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5302):   adb logcat -s GAv4
,I/ActivityManager(  909): Recipient 3747

```
