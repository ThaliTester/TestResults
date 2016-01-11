#### Test 50242285feafdeb_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
I/iu.UploadsManager( 4243): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/iu.UploadsManager( 4243): End new media; added: 0, uploading: 0, time: 51 ms
--------- beginning of system
W/ActivityManager(  948): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 4457): getAccountsCursor
V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4457): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4457, uid=10106, userID:0
W/ActivityManager(  948): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 4457): Observing account changes for notifications
W/ActivityManager(  948): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4457, uid=10106, userID:0
W/ActivityManager(  948): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4457, uid=10106, userID:0
E/Gmail   ( 4457): Error finding the version of the Email provider.....
E/Gmail   ( 4457): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4457): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4457): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4457): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4457): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4457): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4457): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4457): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4457): We do not support migrating this version of the Email provider.
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4457, uid=10106, userID:0
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4457, uid=10106, userID:0
I/Gmail   ( 4457): getAccountsCursor
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4457, uid=10106, userID:0
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4457, uid=10106, userID:0
V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/cutils-trace( 4489): Error opening trace file: Permission denied (13)
I/ActivityManager(  948): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4520 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
W/ActivityManager(  948): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4457, uid=10106, userID:0
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4457, uid=10106, userID:0
W/ActivityManager(  948): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityThread( 4457): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3610e731 that was originally bound here
E/ActivityThread( 4457): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3610e731 that was originally bound here
E/ActivityThread( 4457): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4457): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4457): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 4457): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 4457): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4457): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4457): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4457): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4457): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4457): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4457): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4457): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4457): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4457): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4457): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4457): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/CustomizationManager( 4489): ====startRecUseTime====
W/ActivityManager(  948): Unbind failed: could not find connection for android.os.BinderProxy@2f279804
D/htc.customization.log.level( 4489):  is 
W/CustomizationLogLevel( 4489): Level value is invalid, use default level 2
D/CustomizationManager( 4489):  Read ACC file spent 0.037 (s)
D/CIDMapFileReader( 4489): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4489): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4489): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4489): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4489): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4489): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4489): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4489): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4489): Parsing tag category name = system
I/CustomizationCIDLoader( 4489): Parsing tag category name = application
I/CustomizationCIDLoader( 4489): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4489): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4489): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4489): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4489): Parsing tag category name = ACC
E/SQLiteLog( 4457): (283) recovered 1004 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/CustomizationCIDLoader( 4489): add string-array item, value = 42507
I/CustomizationCIDLoader( 4489): add string-array item, value = 21902
I/CustomizationCIDLoader( 4489): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4489): add string-array item, value = 23420
I/CustomizationCIDLoader( 4489): add string-array item, value = 22299
I/CustomizationCIDLoader( 4489): add string-array item, value = 24002
I/CustomizationCIDLoader( 4489): add string-array item, value = 23210
I/CustomizationCIDLoader( 4489): add string-array item, value = 23205
I/CustomizationCIDLoader( 4489): add string-array item, value = 23806
I/CustomizationCIDLoader( 4489): add string-array item, value = 23430
I/CustomizationCIDLoader( 4489): add string-array item, value = 23408
I/CustomizationCIDLoader( 4489): add string-array item, value = 27205
I/CustomizationCIDLoader( 4489): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4489): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4489): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4489): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4489): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4489): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4489): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4489): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4489): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4489): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4489): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4489): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4489):  Read CID file spent 0.080 (s)
D/CustomizationManager( 4489):  All configurations done spent 0.080 (s)
I/art     (  948): Explicit concurrent mark sweep GC freed 14199(794KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 1.952ms total 144.496ms
V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/AndroidHttpClient( 4180): Leak found
E/AndroidHttpClient( 4180): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4180): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4180): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4180): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4180): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4180): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4180): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4180): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4180): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4180): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4180): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4180): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4180): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4180): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4180): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4180): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4180): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/ActivityManager(  948): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4489 on display 0
D/PMS     (  948): acquireHCC(24883070): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 948 1000 null
D/PMS     (  948): acquireHCC(335eefe9): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 948 1000 null
W/asset   (  948): Copying FileAsset 0x55b77736d0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  948): acquireWL(1617e39c): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 948 1000 null
I/FeedHostManager( 1518): [onPause]
I/FeedProviderManager( 1518): onPause
I/FeedHostManager( 1518): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3feef05e
I/SocialFeedProvider( 1518): +onPause
I/SocialFeedProvider( 1518): -onPause
I/AnimationUtil(  948): isHTCRecent(HelloWorld/Recent screens.)/4
W/HtcSystemUPManager(  948): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  948): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4549 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/art     (  438): Explicit concurrent mark sweep GC freed 8672(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 248us total 18.479ms
I/art     (  438): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 234us total 13.913ms
I/TrimMemoryManager( 1518): [trimMemory] 20
I/art     (  438): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 345us total 17.070ms
W/asset   ( 4549): Copying FileAsset 0xac427a48 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/StatusBarManagerService(  948): setSystemUiVisibility(0x0)
I/Gmail   ( 4457): notifyAccountChanged
D/StatusBarManagerService(  948): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  948): hiding MENU key
I/Gmail   ( 4457): getAccountsCursor
I/Gmail   ( 4457): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4457): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4457): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PMS     (  948): acquireWL(2c833e15): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4457 10106 null
I/Gmail   ( 4457): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
D/PMS     (  948): acquireWL(2c833e15): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4457 10106 null
I/Gmail   ( 4457): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
I/Gmail   ( 4457): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PMS     (  948): acquireWL(2c833e15): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4457 10106 null
I/Gmail   ( 4457): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4457, uid=10106, userID:0
D/Process (  948): killProcessQuiet, pid=3879
I/ActivityManager(  948): Killing 3879:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 3879
I/WebViewFactory( 4549): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/Gmail   ( 4457): master sync=false, engine sync=true
I/LibraryLoader( 4549): Time to load native libraries: 14 ms (timestamps 6450-6464)
I/Gmail   ( 4457): getAccountsCursor
I/LibraryLoader( 4549): Expected native library version number "",actual native library version number ""
V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4457): master sync=false, engine sync=true
V/WebViewChromiumFactoryProvider( 4549): Binding Chromium to main looper Looper (main, tid 1) {92d4fde}
I/LibraryLoader( 4549): Expected native library version number "",actual native library version number ""
I/chromium( 4549): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4549): Initializing chromium process, singleProcess=true
W/art     ( 4549): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4549): ApplicationContext is null in ApplicationStatus
D/LocationManagerService(  948): getProviders()=[passive]
W/chromium( 4549): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 4549): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4549): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4549): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4549): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4549): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4549): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4549): Local Branch: 
I/Adreno-EGL( 4549): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4549): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4549):                  d74aa161a12b9c6fc6332151
I/ActivityManager(  948): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4585 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4520, uid=10085, userID:0
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4520, uid=10085, userID:0
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4520, uid=10085, userID:0
W/System.err(  948): java.lang.Throwable: stack dump
D/BluetoothManagerService(  948): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  948): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/BluetoothManagerService(  948): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@118e1a83:true
W/System.err(  948): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  948): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  948): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 4549): 840842616: getState() :  mService = null. Returning STATE_OFF
W/BroadcastQueue(  948): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
W/art     ( 4549): Attempt to remove local handle scope entry from IRT, ignoring
D/WifiService(  948): New client listening to asynchronous messages
E/WifiTrafficPoller(  948): ADD_CLIENT: 6
I/ActivityManager(  948): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4636 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  948): killProcessQuiet, pid=3927
I/ActivityManager(  948): Killing 3927:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
W/AwContents( 4549): onDetachedFromWindow called when already detached. Ignoring
I/VelvetNetworkClient( 4520): Network connection not availble
D/SystemWebViewEngine( 4549): CordovaWebView is running on device made by: HTC
I/ActivityManager(  948): Recipient 3927
W/art     ( 4549): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4549): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  948): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=4671 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
W/chromium( 4549): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/GLSUser ( 1909): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1909): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1909): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1909): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 4671): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/FindExtension( 4549): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/WebViewFactory( 4520): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/ActionCombine( 1909): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/LibraryLoader( 4520): Time to load native libraries: 24 ms (timestamps 7207-7231)
W/ResourcesManager( 1218): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1218): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/LibraryLoader( 4520): Expected native library version number "",actual native library version number ""
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/Search.LoginHelper( 4520): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4520): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4520): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4520): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4520): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4520): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 4520): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4520): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4520): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4520): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4520): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4520): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4520): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
I/RemoteViews( 1218): apply : com.google.android.gms 0 10 4 40
W/art     ( 4520): Attempt to remove local handle scope entry from IRT, ignoring
I/InputMethodManager( 4549): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@262964cb, mServedView=org.apache.cordova.engine.SystemWebView{1c57f4a8 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3fee8bc1
I/InputMethodManagerService(  948): Disable input method client, pid=1518
D/StatusBarManagerService(  948): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  948): Enable input method client, pid=4549
I/CalendarProvider2( 4671): Created com.android.providers.calendar.CalendarAlarmManager@f16f319(com.htc.providers.calendar.HtcCalendarProvider@92d4fde)
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
D/PMS     (  948): releaseWL(1617e39c): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  948): Displayed com.example.hello/.MainActivity: +1s134ms
D/CalendarProvider2( 4671): wait start:true
W/XT9_C   ( 1356): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1356): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1356): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1356): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
D/CalendarProvider2( 4671): wait end:false
W/BindingManager( 4549): Cannot call determinedVisibility() - never saw a connection for the pid: 4549
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
I/chromium( 4549): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/art     ( 4520): Attempt to remove local handle scope entry from IRT, ignoring
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
I/ActivityManager(  948): Killing 3966:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  948): killProcessQuiet, pid=3966
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
D/JsMessageQueue( 4549): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4549): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ActivityManager(  948): Recipient 3966
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
I/ActivityManager(  948): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=4717 uid=10009 gids={50009, 9997, 5001, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/jxcore_app_log( 4549): JniHelper::setJavaVM(0xab2b98f8), pthread_self() = -1402982408
W/jxcore-log( 4549): Initializing JXcore engine
W/jxcore-log( 4549): JXcore engine is ready
D/browser ( 4717): Browser versionCode = 760001576 versionName = 7.0.2514321356
W/jxcore-log( 4549): Starting JXcore engine
I/art     ( 1909): Explicit concurrent mark sweep GC freed 11983(682KB) AllocSpace objects, 3(252KB) LOS objects, 50% free, 3MB/7MB, paused 999us total 41.778ms
W/SWE_UI  ( 4717): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 4717): Loading: swewebviewchromium
I/LibraryLoader( 4717): Time to load native libraries: 51 ms (timestamps 1803-1854)
I/LibraryLoader( 4717): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 4717): Initializing chromium process, renderers=9
I/LibraryLoader( 4717): Expected native library version number "",actual native library version number ""
I/chromium( 4717): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
W/jxcore-log( 4549): Platform android
W/jxcore-log( 4549): 
W/jxcore-log( 4549): Process ARCH arm
W/jxcore-log( 4549): 
W/art     ( 4717): Attempt to remove local handle scope entry from IRT, ignoring
I/jxcore-log( 4549): JXcore Cordova bridge is ready!
I/jxcore-log( 4549): 
W/jxcore-log( 4549): JXcore engine is started
W/chromium( 4717): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
E/jxcore  ( 4549): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 4549): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
I/Adreno-EGL( 4717): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4717): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4717): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4717): Local Branch: 
I/Adreno-EGL( 4717): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4717): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4717):                  d74aa161a12b9c6fc6332151
D/Process (  948): killProcessQuiet, pid=3991
I/ActivityManager(  948): Killing 3991:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/FindExtension( 4549): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ActivityManager(  948): Recipient 3991
V/IccIntentReceiver( 1637): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT icc slot: 0
I/SIMStateChangeReceiver( 4671): SIM state: ABSENT
I/SIMStateChangeReceiver( 4671): remove notification
D/FlexNetS( 4671): updateSvcAllowedInSettings:false
I/ActivityManager(  948): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=4771 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/PMS     (  948): releaseHCC(24883070): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  948): releaseHCC(335eefe9): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,D/SmsReceiver( 3718): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 3718): onReceive()
D/ExchangePolicystatus( 3718): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 3718): onReceive(): else
I/ActivityManager(  948): Killing 4021:com.htc.htccupd/u0a13 (adj 15): empty #17
,D/Process (  948): killProcessQuiet, pid=4021
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  948): Recipient 4021
,D/ContactMessageStore( 1476): MSG_NOTIFY_CS_TO_SYNC >>,
,D/ContactMessageStore( 1476): MSG_NOTIFY_CS_TO_SYNC <<
D/PMS     (  948): releaseWL(2c833e15): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null,
I/CalendarProvider2( 4671): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4671): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Process (  948): killProcessQuiet, pid=4069,
I/ActivityManager(  948): Killing 4069:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/AccTypeManager( 4771): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 4771): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 4771): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  948): Recipient 4069,
,E/ExternalAccountType( 4771): Unsupported attribute readOnly,
,D/GCM     ( 1909): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
D/AuthorizationBluetoothService( 1909): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4243): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/AccTypeManager( 4771): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 4771): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  948): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4801 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,D/AccTypeManager( 4771): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4243, uid=10024, userID:0
,E/ExternalAccountType( 4771): Unsupported attribute readOnly
,I/art     (  948): Explicit concurrent mark sweep GC freed 12045(634KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.635ms total 159.747ms,
,D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
,D/AccFlag ( 1476): sku_id=118
,W/ResourcesManager( 4801): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4801): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1476): sku_id=118
,V/IccIntentReceiver( 1637): IccIntent: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED icc state: null icc slot: 0
,I/MultiDex( 4801): VM with version 2.1.0 has multidex support
,I/MultiDex( 4801): install
I/MultiDex( 4801): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  948): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4825 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,D/LocationInitializer( 4243): Restart initialization of location
,I/art     (  436): Explicit concurrent mark sweep GC freed 8690(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 187us total 28.127ms
,V/JNIHelp ( 4801): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
D/AccFlag ( 1476): sku_id=118
,D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
,D/AccFlag ( 1476): sku_id=118
,I/art     (  436): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 142us total 25.363ms,
,W/ActivityThread( 4801): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4801): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@306124ab: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4801): Installed default security provider GmsCore_OpenSSL
,I/art     (  436): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 139us total 16.477ms,
,D/WearableService( 4801): callingUid 10024, callindPid: 4801,
,E/MDM     ( 1819): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/ImageRamCache( 4825): create image Cache, size: 31457280.,
I/ImageRamCache( 4825): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4825): create image Cache, size: 31457280.
,I/FeedSettings( 4825): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true,
I/FeedSettings( 4825): GroupBudget 0.500000 0.380000
I/FeedSettings( 4825): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 4825): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4825): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 4825): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 4825): [custom highlight] onReceive,
,D/CustomHighlightService( 4825): [custom highlight] onHandleIntent
,D/NewsDB  ( 4825): set custom highlight []
,I/ActivityManager(  948): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4856 uid=10035 gids={50035, 9997} abi=arm64-v8a
,D/CustomHighlightService( 4825): [custom highlight] set tags ,
,I/ActivityManager(  948): Killing 4112:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  948): killProcessQuiet, pid=4112
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 4112
,I/ActivityManager(  948): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4878 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Process (  948): killProcessQuiet, pid=4136,
I/ActivityManager(  948): Killing 4136:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  948): Recipient 4136,
,D/SMSBackup( 4878): Got a database change event
,I/ActivityManager(  948): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4899 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
D/Process (  948): killProcessQuiet, pid=4159
I/ActivityManager(  948): Killing 4159:com.android.smith/1000 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  948): Recipient 4159
,I/ActivityManager(  948): Waited long enough for: ServiceRecord{3e988920 u0 com.htc.HTCSpeaker/.NGFService}
,D/MessagingShortcutReceiver( 3718): keep hiding shortcut bubble
V/AlarmManager(  948): sending alarm PendingIntent{b1d5e4d: PendingIntentRecord{2acacd02 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=59743, Int=0
,D/MessagingShortcut( 3718): updateMsgShortcut, msg count> -1,
D/MessagingShortcut( 3718): After query: 0,
,D/MessagingShortcut( 3718): mPresentUnreadCount: -1
,D/MessageUtils( 3718): [getShortcut] com.htc.sense.mms.ui.ConversationList, false,
D/MessagingShortcut( 3718): setMsgShortcutDrawable> 0, false,
,D/MessagingShortcut( 3718): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1304): [EventService] reorderNotification, total:0
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  948): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4922 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  948): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4944 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,W/ResourcesManager( 4922): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,D/TodoTaskshortcut( 4922): update TASK shortcut>,
,D/Process (  948): killProcessQuiet, pid=4091,
I/ActivityManager(  948): Killing 4091:com.android.settings/1000 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  948): acquireWL(1fa16050): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1909 10024 WorkSource{10024 com.google.android.gms}
,D/MdScBoot( 4899): [21d.1.] 30@-224803 -> 40,
,D/MdScBootUi( 4899): [21d.1.2.] boot 118,
,D/MdScSimSt( 4899): [21d.1.2.] qry 118: 0+1 running 0
,I/ActivityManager(  948): Recipient 4091,
,D/PMS     (  948): acquireWL(30ee9249): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4922 10069 null,
,D/PMS     (  948): acquireWL(339cb74e): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4922 10069 null
,D/PMS     (  948): releaseWL(30ee9249): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  948): releaseWL(1fa16050): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/MtpReceiver( 3653): [MTP][handleUsbStateAsync]+
,D/MtpReceiver( 3653): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3653): [MTP][handleUsbState]+
,E/TodoTaskNotifyService( 4922): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4922): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 4922): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4922): ,	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/PMS     (  948): releaseWL(339cb74e): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 4922): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  948): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4972 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a,
W/NotifyReceiver( 4922): stopSelfResult true
,D/MtpReceiver( 3653): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpReceiver( 3653): [MTP][handleUsbState]-
D/MtpReceiver( 3653): [MTP][handleMessage]-
D/MtpService( 3653): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 3653): TotalSize=1886532,MediaCacheLimit=6000
D/MtpService( 3653): [isMtpConnected] connected: true
,D/Process (  948): killProcessQuiet, pid=4217,
I/ActivityManager(  948): Killing 4217:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,E/MediaScannerService( 3653): [onStartCommand] --- Should not be here, redirect request. ----,
E/MediaScannerService( 3653): [handleMessage] --- Should not be here, ignore request. ----
,I/ActivityManager(  948): Recipient 4217
,D/SyncApplication( 4972): Loading default preferences
,D/Process (  948): killProcessQuiet, pid=3264
I/ActivityManager(  948): Killing 3264:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/Resources( 4972): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,D/WifiService(  948): New client listening to asynchronous messages
,E/WifiTrafficPoller(  948): ADD_CLIENT: 7
,D/SyncApplication( 4972): Overriding preferences with custom values,
,I/HtcModeClient( 3155): handler message = 4011
E/HtcModeClient( 3155): Check connection and retry 4 times.
,D/SyncApplication( 4972): Updating preferences succeeded,
,E/MediaScannerServiceEx( 3653): [getStorageMaskIdFromPath] path is null,
D/MediaScannerServiceEx( 3653): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,D/MediaScannerServiceEx( 3653): [handleExternalVolume] ext storage,
,D/MediaProviderUtils( 3653): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3653): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3653): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3653): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3653): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 3653): [update][6]#0#
,D/MediaProvider( 3653): [update][2]#0#
,D/MediaProvider( 3653): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted,
D/MtpService( 3653): [sendStorageAdded] Already send to MTP: /storage/emulated/0,
,D/MediaProvider( 3653): [update][10]#1#
,D/MediaScannerServiceEx( 3653): [AliveExtStorageRows]-0, 0,
,D/PMS     (  948): acquireWL(8546226): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3653 10017 null
,I/ActivityManager(  948): Recipient 3264,
,E/SyncApplication( 4972): Application created.,
,D/MediaScanner( 3653): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,W/VolumeInfo( 4972): Unable to read mount points
W/VolumeInfo( 4972): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 4972): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 4972): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 4972): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 4972): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 4972): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 4972): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 4972): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 4972): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 4972): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 4972): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 4972): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 4972): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 4972): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 4972): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4972): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 4972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 4972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 4972): 	... 13 more
,V/VolumeInfo( 4972): Found 0 mount point(s)
V/VolumeInfo( 4972): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4972): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4972): getNewCalendarAuthority()...
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4972, uid=10005, userID:0,
,W/PackageManager(  948): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4972, uid=10005, userID:0
W/PackageManager(  948): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 4972): enableAppOperation()+
,D/VolumeInfo( 4972): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 4972): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4972): enableAppOperation()-
,D/HTCUtilities( 4972): isNeorSinged() + ,
,D/HTCUtilities( 4972): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4972): isNeorSinged() return false
,D/CDMountReceiver( 4972): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 4972): USB connected to PC
,D/FOTAReceiver( 4972): onReceive() enter 
D/FOTAReceiver( 4972): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  948): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5002 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
I/ActivityManager(  948): Killing 4180:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  948): killProcessQuiet, pid=4180
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  948): Recipient 4180,
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5002): -onCreate()
,V/Settings:HtcSettingsApplication( 5002): [5002/5002] onCreate(),
,D/TetherSettings( 5002): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 5002): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 5002): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5002): Cust_ConnectToPC   : spcsc>false
D/        ( 5002): Cust_ConnectToPC   : IPT>true
D/        ( 5002): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5002): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5002): hasRemovableStorageSlot: true,
D/SmartNS_Utility( 5002): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5002): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 5002): usb_cable_connect = 1
,D/SmartNS_Utility( 5002): usb_denied = 0
,I/SmartNS_NSReceiver( 5002): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 5002): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 5002): onReceive:com.htc.intent.action.USB_CONNECT2PC,
,W/ContextImpl( 5002): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 ,
,I/SmartNS_PSService( 5002): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 5002): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
I/SmartNS_PSService( 5002):  defaultType:0
I/SmartNS_PSService( 5002): fail notificaiton:false
D/SmartNS_Utility( 5002): usb_cable_connect = 1,
D/SmartNS_Utility( 5002): usb_denied = 0
I/SmartNS_PSService( 5002): usb notificaiton:true
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
I/ActivityManager(  948): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5026 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActionCombine( 5002): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/GAV2    ( 4457): Thread[GAThread,5,main]: No campaign data found.
,D/SmartNS_Utility( 5002): usb_cable_connect = 1
D/SmartNS_Utility( 5002): usb_denied = 0
,I/SmartNS_PSService( 5002): usb notificaiton:true
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1218): reapply : com.android.settings 2 36
,D/SmartNS_Utility( 5002): usb_cable_connect = 1
,D/SmartNS_Utility( 5002): usb_denied = 0
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1218): reapply : com.android.settings 1 36
,I/SmartNS_PSService( 5002): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 5002): USB Plugged, Set USBPlugged=  truePSenabled:false
,D/Process (  948): killProcessQuiet, pid=4378
I/ActivityManager(  948): Killing 4378:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 4378
,I/GAv4-SVC( 4243): Google Analytics 7.8.99 is starting up.
,W/ContextImpl( 5026): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
,D/Process (  948): killProcessQuiet, pid=4457,
I/ActivityManager(  948): Killing 4457:com.google.android.gm/u0a106 (adj 15): empty #17,
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 4457
,D/MediaProvider( 3653): [update][10]#1#,
,D/MediaScanner( 3653):  prescan time: 509ms
,D/MediaScanner( 3653):     scan time: 528ms,
D/MediaScanner( 3653): postscan time: 10ms
D/MediaScanner( 3653):    total time: 1047ms
D/MediaScanner( 3653): -----------------------------------------------------------------
D/MediaScanner( 3653): firstscan(media) time: 294ms
D/MediaScanner( 3653): secondscan(non-media) time: 234ms
D/MediaScanner( 3653):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3653):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3653):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3653):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,D/FlexNetS( 4671): updateSvcAllowedInSettings:false
,D/MediaProvider( 3653): [delete][14]
D/MediaProvider( 3653): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 3653): [recoverParentNodes] - 0
,D/MediaProvider( 3653): [update][5]
D/MediaScannerServiceEx( 3653): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3653): [updateImage]+
,D/MediaScannerServiceEx( 3653): [updateImage]-0
,D/PMS     (  948): releaseWL(8546226): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 3653): [1] scan finished
,D/MediaProviderUtils( 3653): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3653): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3653): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3653): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1,
W/MediaScannerServiceEx( 3653): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 3653): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3653): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/MediaProvider( 3653): [update][4]#1#,
,D/Prism.PackageStateRece_( 1518): action: android.intent.action.PACKAGE_ADDED
,I/[PluginManager]RegisterService( 1442): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/[PluginManager]RegisterService( 1442): handle notify Blinkfeed plugin client changed
,D/MediaProvider( 3653): [update][21]#0#
,D/MediaScannerServiceEx( 3653): [disAliveExtStorageRows]--1, 0
,I/ActivityManager(  948): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5056 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,D/MediaProviderUtils( 3653): calcVolumeId: /storage/emulated/0,
D/MediaProviderUtils( 3653): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3653): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3653): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3653): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3653): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3653): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3653): [update][8]#1#
,D/MediaProvider( 3653): [update][33]#0#
,D/MediaScannerServiceEx( 3653): [disAliveExtStorageRows]--1, 0
,I/DeviceManagement( 5056): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5056 dbg=false s=true,
,I/DeviceManagement( 5056): PackageUpdateReceiver: vvv Package added: [com.example.hello],
,D/Process (  948): killProcessQuiet, pid=4520
I/ActivityManager(  948): Killing 4520:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17,
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  948): Recipient 4520
,D/WifiService(  948): Client connection lost with reason: 4
,I/ActivityManager(  948): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5078 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/HtcCupdReceiver(Provider)( 5078):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  948): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5100 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  948): killProcessQuiet, pid=4717
I/ActivityManager(  948): Killing 4717:com.htc.sense.browser/u0a9 (adj 15): empty #17
,D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  436): Explicit concurrent mark sweep GC freed 8636(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 211us total 31.121ms
,I/art     (  436): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 167us total 22.396ms
,D/Settings:HtcWirelessFeatureFlags( 5002): id/is att sku: 118/false,
,I/art     (  436): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 225us total 21.929ms
,I/ActivityManager(  948): Recipient 4717
,E/Settings:HtcWrapHeaderInfo( 5002): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5002): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5002): updateDevelopment, bPrefShow = true
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5100, uid=10072, userID:0
,E/Settings:HtcUmcWidgetEnabler( 5002): isSupportMusicChannel(): false
,W/global  ( 5100): [apache-http] Connection GC has been deprecated!
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportHomeButton]support         :false
,D/Finsky  ( 5100): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 5100): [apache-http] Connection GC has been deprecated!,
,I/ActivityManager(  948): Cannot resolve ContentProvider=com.htc.vowifi,
E/Settings:HtcVoWifiWidgetEnabler( 5002): isSupportVoWifi: null
E/ActivityThread( 5002): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5002): The wrap header doesn't exist in header list.,
E/Settings:HtcWrapHeaderInfo( 5002): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5002): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5002): [supportHomeButton]support         :false
,I/ActivityManager(  948): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 5002): isSupportVoWifi: null
E/ActivityThread( 5002): Failed to find provider info for com.htc.vowifi
,W/global  ( 5100): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5100): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  948): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5141 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/Settings( 5100): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5100): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5100, uid=10072, userID:0
,W/ResourcesManager( 5141): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5141): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5141): VM with version 2.1.0 has multidex support
,I/MultiDex( 5141): install
I/MultiDex( 5141): VM has multidex support, MultiDex support library is disabled.
,D/Process (  948): killProcessQuiet, pid=4771,
I/ActivityManager(  948): Killing 4771:com.htc.contacts/u0a38 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  948): Recipient 4771
,I/SocialFeedProvider( 1518): +disConnect socialManager,
I/SocialFeedProvider( 1518): disconnect socialManager
,D/Finsky  ( 5100): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 5100): [1] 2.run: Finished loading 1 libraries.
,I/SocialFeedProvider( 1518): -disConnect socialManager
,D/Finsky  ( 5100): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/AlarmManager(  948): sending alarm PendingIntent{1beee929: PendingIntentRecord{2e79f4ae com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452552516633, Int=0
,D/ChimeraCfgMgr( 4243): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4243): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 4243): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/SocialManager[SocialBiLogHelper]( 4825): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4825): last commit ulog time 1452491432917
I/SocialManager[SocialBiLogHelper]( 4825): skip commit this time
,D/Finsky  ( 5100): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/JNIHelp ( 5141): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 5141): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5141): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@306124ab: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5141): Installed default security provider GmsCore_OpenSSL
,I/art     (  948): Explicit concurrent mark sweep GC freed 14633(718KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.207ms total 143.433ms
D/PMS     (  948): acquireWL(2cf4adba): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4243 10024 null
,I/ConfigFetchService( 4243): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  948): acquireWL(332feb86): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4243 10024 WorkSource{10374 com.example.hello}
,I/ConfigFetchService( 4243): launchTask
,D/PMS     (  948): releaseWL(2cf4adba): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/ChimeraCfgMgr( 4243): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4243): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4243): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/ConfigFetchTask( 4243): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1V0l3IUrcv1Rb0hg1ufmPhG9qULOI7jcYasXgP6vCm_KMstPGI4I4kYrCjw2V3aizNJZCP93ecSLDdpXcrM8PkMooS_QwCI_oaTAaNWHK3DqqU8CA51LDP-cOFlcreZfaQ2WkGYalEf0MsYcADUeMmdVbazmJn6xBM2ubrk-b31CPAxeMAY-OWOxispL0TNvwy8bE8jypTnLghBRCnQmZ-Sf4ETz8tpiqQV0pTG-S00RqvUx1IUonAMCsH4A_h8-MJdErTBe0_nUlIElONqR_ckEVCJmfoAOmzvEkOvkOkkM1FlGL8
,I/PeopleContactsSync( 4243): CP2 sync disabled,
I/GoogleURLConnFactory( 4243): Using platform SSLCertificateSocketFactory,
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4243, uid=10024, userID:0
,D/Vision  ( 4243): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 4243): Failed to find package metadata for com.example.hello,
D/Vision  ( 4243): No vision deps
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4243, uid=10024, userID:0
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4243, uid=10024, userID:0
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4243, uid=10024, userID:0
I/ActivityManager(  948): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5180 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4243, uid=10024, userID:0,
D/PMS     (  948): acquireWL(14ce4c47): PARTIAL_WAKE_LOCK  Icing 0x1 4243 10024 WorkSource{10024 com.google.android.gms}
,I/Icing   ( 4243): Storage manager: low false usage 1.77MB avail 5.80GB capacity 7.95GB,
,D/libc    ( 4243): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4243): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 4243): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4243): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4243): [NET] android_getaddrinfo_proxy+
D/libc    ( 4243): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4243): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4243): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname,
,I/ConfigFetchService( 4243): fetch service done; releasing wakelock
,I/ConfigFetchService( 4243): stopping self
D/PMS     (  948): releaseWL(332feb86): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10374 com.example.hello}
,W/Icing   ( 4243): Received bad json for section weights override -- ignoring.,
,D/AccTypeManager( 1684): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/Icing   ( 4243): Received bad json for corpus context scoring override -- ignoring.
W/ResourcesManager( 1476): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/Icing   ( 4243): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4243): Received bad json for corpus context scoring override -- ignoring.
W/SystemReader(  948): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1684): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1518): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1518): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1518): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1518): Deferring update until onResume
D/Launcher( 1518): waitUntilResume // bindAppsUpdated
,I/Prism.ItemManager( 4825): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4825): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/ResourcesManager(  948): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/AccTypeManager( 1684): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/art     ( 4243): Background sticky concurrent mark sweep GC freed 16955(1478KB) AllocSpace objects, 25(500KB) LOS objects, 20% free, 6MB/7MB, paused 5.513ms total 116.690ms
,D/PhoneApp( 1476): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1684): Unsupported attribute readOnly
,I/ActivityManager(  948): Killing 4856:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,D/Process (  948): killProcessQuiet, pid=4856
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/PackageManager(  948): Unable to load service info ResolveInfo{3a6474ca com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  948): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  948): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  948): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  948): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  948): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  948): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  948): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  948): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  948): 	,at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  948): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  948): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  948): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  948): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  948): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  948): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  948): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/BackupManagerService(  948): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,E/libprocessgroup(  948): failed to kill 1 processes for processgroup 4856
I/ActivityManager(  948): Recipient 4856
,E/Icing   ( 4243): Loading extension by file descriptor -1 failed
,V/AlarmManager(  948): sending alarm PendingIntent{8a7abc4: PendingIntentRecord{23520aad com.android.vending startService}}, i=null, t=0, cnt=1, w=1452552517288, Int=0
,D/Finsky  ( 5100): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/BaseAppContext( 4243): Using Auth Proxy for data requests.
,W/BaseAppContext( 4243): Using Auth Proxy for data requests.
,V/Finsky  ( 5100): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GmsNetworkLocationProvi( 1819): DISABLE
,I/GCoreNlp( 1819): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationProviderProxy(  948): applying state to connected service
D/PMS     (  948): acquireWL(14638942): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(14638942): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
W/BaseAppContext( 4243): Using Auth Proxy for data requests.
,D/LocationProviderProxy(  948): applying state to connected service
,D/PMS     (  948): acquireWL(2f6aab89): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): acquireWL(25a4f78e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(2f6aab89): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(25a4f78e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSUser ( 1909): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,D/PMS     (  948): acquireWL(107edbaf): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
I/GLSUser ( 1909): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1909): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1909): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/BaseAppContext( 4243): Using Auth Proxy for data requests.
D/PMS     (  948): releaseWL(107edbaf): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4243): Using Auth Proxy for data requests.,
,W/Finsky  ( 5100): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/BaseAppContext( 4243): Using Auth Proxy for data requests.,
V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1909): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1909): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1909): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1909): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 4243): updateResources: need to parse f{com.google.android.gms}
,V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1909): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1909): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1909): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1909): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5100): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,I/Icing   ( 4243): Internal init done: storage state 0
,I/art     ( 1909): Explicit concurrent mark sweep GC freed 11906(639KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 616us total 42.487ms
,I/Icing   ( 4243): Post-init done
,D/PMS     (  948): releaseWL(14ce4c47): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,E/AndroidHttpClient( 5100): Leak found,
E/AndroidHttpClient( 5100): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5100): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5100): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5100): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5100): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5100): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5100): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5100): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5100): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5100): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5100): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,E/AndroidHttpClient( 5100): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5100): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5100): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5100): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5100): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5100): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/GAv4    ( 5180): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5180):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5180):   adb logcat -s GAv4
,W/GAv4    ( 5180): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5180): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 5180): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/AnalyticsTrackerProxyImpl( 5180): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45,
,V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1909): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1909): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1909): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1909): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 4243): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4243): Module APK com.google.android.play.games already loaded
,W/Finsky  ( 5100): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5100): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5100): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 5100): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/VoldConnector(  948): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 5180): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,I/ActivityManager(  948): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5235 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  948): Killing 4878:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,D/Process (  948): killProcessQuiet, pid=4878
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/DeviceConnectionService( 1819): client connected with version: 7571000
,W/ResourcesManager( 5180): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5180): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  948): Recipient 4878,
,D/Process (  948): killProcessQuiet, pid=4899
I/ActivityManager(  948): Killing 4899:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 5235): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,V/JNIHelp ( 5180): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PMS     (  948): acquireWL(3c1a8add): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(3c1a8add): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,W/System  ( 5180): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5180): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  948): Recipient 4899,
,D/HtcPowerSaver(  948): updateBatteryInfo
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/PMS     (  948): runPSCheck
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  948): Checking...
D/UsbnetService(  948): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  948): >> updateStatus
D/WifiController(  948): handleMessage: E msg.what=155652
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): processMsg: ApStaDisabledState
,D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,I/Prism.ItemManager( 1518): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1518): loadItems() com.htc.launcher.pageview.WidgetManager@35b68873 +
I/Prism.WidgetManager( 1518): onLoadItems() +
,I/Prism.ItemManager( 4825): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 4825): loadItems() com.htc.launcher.pageview.WidgetManager@38cae42 +
I/Prism.WidgetManager( 4825): onLoadItems() +
,W/ResourcesManager( 1518): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 4825): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PMS     (  948): acquireWL(14f8c04c): PARTIAL_WAKE_LOCK  AsyncService 0x1 5235 10167 null
,D/PMS     (  948): acquireWL(19a8adaa): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5235 10167 null,
,D/PMS     (  948): releaseWL(14f8c04c): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  948): releaseWL(19a8adaa): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,W/ResourcesManager( 1518): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4825): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/ActivityManager(  948): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5266 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,D/Process (  948): killProcessQuiet, pid=3718
I/ActivityManager(  948): Killing 3718:com.htc.sense.mms/u0a64 (adj 15): empty #17,
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/asset   ( 1518): Copying FileAsset 0x55b794f210 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,W/asset   ( 4825): Copying FileAsset 0x55b74f1e20 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/ActivityManager(  948): Recipient 3718
,E/Prism.WidgetManager( 1518): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1518): onLoadItems() -
I/Prism.ItemManager( 1518): loadItems() com.htc.launcher.pageview.WidgetManager@35b68873 -
,D/PhoneApp( 1476): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1476): -- N1 =0
,D/PhoneApp( 1476): -- N2 =0
,D/PhoneApp( 1476): -- N3 =0,
,I/Prism.WidgetManager( 4825): onLoadItems() -
,I/Prism.ItemManager( 4825): loadItems() com.htc.launcher.pageview.WidgetManager@38cae42 -
,I/ActivityManager(  948): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5288 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,W/ContextImpl( 5288): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5288): MY_DEBUG = false,
,D/PMS     (  948): acquireWL(36d1c911): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5288 1000 null
,I/ActivityManager(  948): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5315 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
,D/WeatherUtility( 1442): Weather sync is On
,D/WSP     ( 1442): [Receiver] auto sync agent, auto sync is enabled, reset schedule,
,I/HtcModeClient( 3155): handler message = 4011,
E/HtcModeClient( 3155): Check connection and retry 5 times.
,D/LocationManagerService(  948): getProviders()=[passive]
,I/ActivityManager(  948): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5341 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a,
,D/WeatherUtility( 5315): Weather sync is On,
,W/ResourcesManager( 5341): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/WeatherRequest( 5315): request cur loc, but there is no sys cur
W/Settings( 5315): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActionCombine( 5315): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,I/ActivityManager(  948): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5366 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,I/UpdateIcingCorporaServi( 5266): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE,
,I/art     (  948): Explicit concurrent mark sweep GC freed 25529(1364KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 12.756ms total 185.386ms,
D/PowerUsageService( 5288): repeat time = 1452553419346
,I/RemoteViews( 1518): reapply : com.htc.widget.weatherclock 11 17
,W/asset   ( 5266): Copying FileAsset 0x55b7367970 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.,
,I/UpdateIcingCorporaServi( 5266): UpdateCorporaTask done [took 133 ms] updated apps [took 133 ms] 
,D/Process (  948): killProcessQuiet, pid=4944,
I/ActivityManager(  948): Killing 4944:com.htc.mobiledata/u0a46 (adj 15): empty #17,
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 4944
,I/PowerUsageList:PowerUsageHelper( 5288): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/EASAppSvc( 5366): [ NA ]onCreate
,D/PowerUsageList:BatterySipperExt( 5288): gen(), null == sipper.uidObj, userId = 0,
,I/VersionUtil( 5366): [ NA ]setIsFOTAing: true
,I/VersionUtil( 5366): [ NA ]onUpgrade: current version=100, latest version=100,
I/VersionUtil( 5366): [ NA ]setIsFOTAing: false
,D/HtcAdjCursorFactory( 5366): Set CursorWindow size to: 4194304 KB, Tid: 5390
,D/ORMLib  ( 4922): put()
,I/ActivityManager(  948): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5396 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  948): killProcessQuiet, pid=4346
,I/ActivityManager(  948): Killing 4346:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 4346
,D/Process (  948): killProcessQuiet, pid=4972,
I/ActivityManager(  948): Killing 4972:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/SQLiteLog( 5341): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal
,I/ActivityManager(  948): Recipient 4972,
D/WifiService(  948): Client connection lost with reason: 4
,V/AlarmManager(  948): sending alarm PendingIntent{1abc56b9: PendingIntentRecord{10b37afe com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1452552520383, Int=0
,I/EASAppSvc( 5366): [ NA ]onDestroy
D/WifiService(  948): New client listening to asynchronous messages
E/WifiTrafficPoller(  948): ADD_CLIENT: 6
I/EASAppSvc( 5366): [ NA ]onCreate
,W/EAS_NetworkUtil( 5366): [ NA ]getNetworkInfo: NetworkInfo is null
,I/VersionUtil( 5366): [ NA ]setIsFOTAing: true
I/EASAppSvc( 5366): [ NA ]> uninitEASService
I/MusicStore( 5396): Database version: 120
I/EASRequestController( 5366): [ NA ]release
,I/VersionUtil( 5366): [ NA ]onUpgrade: current version=100, latest version=100
,I/VersionUtil( 5366): [ NA ]setIsFOTAing: false
,W/EAS_NetworkUtil( 5366): [ NA ]getNetworkInfo: NetworkInfo is null
,D/ORMLib  ( 4922): put(),
,D/EASPublicBinder( 5366): [ NA ]release
,D/TaskBinder( 5366): [ NA ]release
D/TaskBinder( 5366): [ NA ]release
I/EASAppSvc( 5366): [ NA ]< uninitEASService
,I/EASAppSvc( 5366): [ NA ]onDestroy,
I/EASAppSvc( 5366): [ NA ]> uninitEASService
,I/EASRequestController( 5366): [ NA ]release
,D/EASPublicBinder( 5366): [ NA ]release
,D/TaskBinder( 5366): [ NA ]release
D/TaskBinder( 5366): [ NA ]release
,I/EASAppSvc( 5366): [ NA ]< uninitEASService
,I/ActivityManager(  948): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5442 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,D/Process (  948): killProcessQuiet, pid=5026,
I/ActivityManager(  948): Killing 5026:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5026,
,D/VoldConnector(  948): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 5396): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/Process (  948): killProcessQuiet, pid=4671
,I/ActivityManager(  948): Killing 4671:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/ORMLib  ( 4922): put()
,D/VoldConnector(  948): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5396): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  948): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5396): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,I/ActivityManager(  948): Recipient 4671
,D/Process (  948): killProcessQuiet, pid=4585,
I/ActivityManager(  948): Killing 4585:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 4585,
,W/ResourcesManager( 5396): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5396): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5396): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 5396): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5396): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15a694bd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 5396): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5396): GMSCore installation verified
,I/ConfigStore( 5396): Config Database version: 1,
,D/PMS     (  948): releaseWL(36d1c911): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5396, uid=10159, userID:0,
,D/WifiDisplayAdapter(  948): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  948):     Client/Owner: Client
D/WifiDisplayAdapter(  948):     GroupId: 
D/WifiDisplayAdapter(  948):     Passphrase: 
D/WifiDisplayAdapter(  948):     SessionId: 0
D/WifiDisplayAdapter(  948):     IP Address: }
,D/MediaRouterService(  948): Client com.google.android.music (pid 5396): Registered,
,D/WifiDisplayAdapter(  948): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  948):     Client/Owner: Client
D/WifiDisplayAdapter(  948):     GroupId: 
D/WifiDisplayAdapter(  948):     Passphrase: 
D/WifiDisplayAdapter(  948):     SessionId: 0
D/WifiDisplayAdapter(  948):     IP Address: }
,I/MediaRouter( 5396): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,D/TelephonyReceiver( 1476): bind: true
,I/ActivityManager(  948): Start proc com.htc.bgp for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5472 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,I/ActivityManager(  948): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5486 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5396, uid=10159, userID:0
,W/ResourcesManager( 5472): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 5396): Using our fixed implementation of GMSCore's GoogleHttpClient,
,I/GoogleURLConnFactory( 5396): Using platform SSLCertificateSocketFactory
,W/HtcWrapAdjustableCursorFactory( 5486): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 5486): onCreate
,V/GetPrviateResource( 5486): GetPrviateResource
V/GetPrviateResource( 5486): GetPrviateResource
,I/CalendarProvider2( 5472): Created com.android.providers.calendar.CalendarAlarmManager@f16f319(com.htc.providers.calendar.HtcCalendarProvider@92d4fde)
,I/ActivityManager(  948): Killing 5056:com.htc.cs.dm/u0a99 (adj 15): empty #17
,D/Process (  948): killProcessQuiet, pid=5056
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MessageCustFlag( 5486): sense_version=6.0
,D/BTAccessoryUtil( 5486): createReceiver,
,D/GenericMessagesProvider( 5486): query uri: content://htc-messages/wappush/count,
,E/SQLiteLog( 5486): (14) cannot open file at line 30058 of [9491ba7d73],
E/SQLiteLog( 5486): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 5486): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5486): DB info: errno = 2, errno message = No such file or directory
,E/SQLiteDatabase( 5486): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.,
E/SQLiteDatabase( 5486): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5486): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5486): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5486): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5486): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5486): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5486): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5486): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5486): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5486): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5486): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5486): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 5486): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5486): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5486): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5486): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 5486): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5486): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5486): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/System.err( 5486): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5486): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 5486): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5486): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5486): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/System.err( 5486): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5486): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 5486): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 5486): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 5486): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5486): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5486): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
W/System.err( 5486): 	at android.os.Binder.execTransact(Binder.java:454)
,I/ActivityManager(  948): Recipient 5056
,D/BTAccessoryUtil( 5486): registerReceiver return intent = null,
D/CalendarProvider2( 5472): wait start:true
I/ActivityManager(  948): Killing 5078:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  948): killProcessQuiet, pid=5078
,D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/MessageCustFlag( 5486): sku_id=118
D/HtcBuildUtils( 5486): getRATByHtcTelephonyCapability:1
,W/SystemReader( 5486): Cannot find qct_8960_interface, use default value instead
,I/ActivityManager(  948): Recipient 5078
,D/TelephonyReceiver( 1476): switchBindHtcMsgCursor: null
,I/ConfigService( 1909): onDestroy
,D/PMS     (  948): acquireWL(1909753b): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5472 10011 null
,D/CalendarProvider2( 5472): wait end:false
,E/SQLiteLog( 5472): (284) automatic index on view_events(_id),
,I/ActivityManager(  948): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5522 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/PMS     (  948): releaseWL(1909753b): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/DFPI.PIReciver( 5522): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,I/DFPI.ApkInstallService( 5522): onHandleIntent,
I/DFPI.ApkInstallService( 5522): Media Scan Finished Case ,
,D/DFPI.ApkInstallService( 5522): check CID = HTC__102,
I/DFPI.ApkInstallService( 5522): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  948): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5545 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  948): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5570 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,D/VoldConnector(  948): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/},
W/ContextImpl( 5545): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5570): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5570): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5570): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/PMS     (  948): acquireWL(459946): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1909 10024 WorkSource{10024 com.google.android.gms},
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm),
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
D/libc    ( 1909): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1909): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1909): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1909): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1909): [NET] android_getaddrinfo_proxy+
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
D/libc    ( 1909): [NET] android_getaddrinfo_proxy get netid:0
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1909): [NET] android_getaddrinfo_proxy-, NODATA
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
D/PMS     (  948): releaseWL(459946): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  948): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5598 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5570): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/art     (  436): Explicit concurrent mark sweep GC freed 8679(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 272us total 28.395ms
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
I/art     (  436): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 204us total 22.579ms
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/art     (  436): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 172us total 22.301ms
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,D/Process (  948): killProcessQuiet, pid=5002,
I/ActivityManager(  948): Killing 5002:com.android.settings/1000 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  948): Recipient 5002
,I/art     (  948): Explicit concurrent mark sweep GC freed 23188(1123KB) AllocSpace objects, 2(560KB) LOS objects, 33% free, 16MB/24MB, paused 1.592ms total 169.848ms
,D/TelephonyReceiver( 1476): bind: false
D/TelephonyReceiver( 1476): switchBindHtcMsgCursor: null
,D/DFPI.PIReciver( 5522): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,V/AlarmManager(  948): sending alarm PendingIntent{18e81034: PendingIntentRecord{bf6ee5d com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1452552522602, Int=0
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98,
I/DFPI.ApkInstallService( 5522): onHandleIntent
I/DFPI.ApkInstallService( 5522): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5522): check CID = HTC__102
I/DFPI.ApkInstallService( 5522): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5570): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5570): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5570): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5570): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/DFPI.PIReciver( 5522): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,I/ActivityManager(  948): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 5522): onHandleIntent
I/DFPI.ApkInstallService( 5522): Media Scan Finished Case 
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/DFPI.ApkInstallService( 5522): check CID = HTC__102
I/DFPI.ApkInstallService( 5522): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  948): Resuming delayed broadcast
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4,
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/DFPI.PIReciver( 5522): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  948): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/DFPI.ApkInstallService( 5522): onHandleIntent
I/DFPI.ApkInstallService( 5522): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5522): check CID = HTC__102,
I/DFPI.ApkInstallService( 5522): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/ActivityManager(  948): Resuming delayed broadcast
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
I/SoundPicker( 5570): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/DFPI.PIReciver( 5522): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/ActivityManager(  948): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/DFPI.ApkInstallService( 5522): onHandleIntent
I/DFPI.ApkInstallService( 5522): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5522): check CID = HTC__102
I/DFPI.ApkInstallService( 5522): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  948): Resuming delayed broadcast
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5570): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5570): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98,
I/SoundPicker( 5570): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/DFPI.PIReciver( 5522): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
I/ActivityManager(  948): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/DFPI.ApkInstallService( 5522): onHandleIntent
I/DFPI.ApkInstallService( 5522): Media Scan Finished Case 
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/DFPI.ApkInstallService( 5522): check CID = HTC__102
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/DFPI.ApkInstallService( 5522): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  948): Resuming delayed broadcast
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/MediaStoreImporter( 5396): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/ActionCombine( 5598): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/DFPI.PIReciver( 5522): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/ActivityManager(  948): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/DFPI.ApkInstallService( 5522): onHandleIntent,
I/DFPI.ApkInstallService( 5522): Media Scan Finished Case 
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
D/DFPI.ApkInstallService( 5522): check CID = HTC__102
I/DFPI.ApkInstallService( 5522): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  948): Resuming delayed broadcast
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): SoundPickerReceiver [onReceive] startService
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
I/SoundPicker( 5570): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5570): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5570): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96,
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5570): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/RemoteViews( 1218): setHTCTheme(com.htc.updater,true,33751145)
,D/GCM     ( 1909): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/RemoteViews( 1218): apply : com.htc.updater 1 13 3 36
D/AuthorizationBluetoothService( 1909): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4243): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4243, uid=10024, userID:0
I/CalendarProvider2( 5472): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 5472): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar),
D/WearableService( 4801): callingUid 10024, callindPid: 4801
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/MediaStoreImporter( 5396): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,E/MDM     ( 1819): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4243): Restart initialization of location
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,D/FindExtension( 1218): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/ThreadedRenderer( 1218): Defer allocateBuffers to drawing time
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/GCM     ( 1909): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1909): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,V/GmsCoreStatsServiceLauncher( 4243): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,E/MDM     ( 1819): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4243, uid=10024, userID:0
,D/LocationInitializer( 4243): Restart initialization of location
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5570): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5570): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122,
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4),
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5570): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/MediaStoreImporter( 5396): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0,
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
D/PMS     (  948): acquireWL(922a5fc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1909 10024 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5570): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5570): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5570): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/PMS     (  948): releaseWL(922a5fc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/PMS     (  948): acquireWL(f3ba485): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1909 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/MediaStoreImporter( 5396): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/PMS     (  948): releaseWL(f3ba485): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/art     (  948): Explicit concurrent mark sweep GC freed 9542(433KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.337ms total 149.175ms,
,D/PMS     (  948): acquireWL(31170401): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1909 10024 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,D/PMS     (  948): releaseWL(31170401): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/MediaStoreImporter( 5396): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5570): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5570): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5570): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/ActivityManager(  948): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5647 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2),
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/PhoneMonitor( 5647): Register our PhoneStateListener
,I/MediaStoreImporter( 5396): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/Process (  948): killProcessQuiet, pid=4825
I/ActivityManager(  948): Killing 4825:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 4825
,D/Process (  948): killProcessQuiet, pid=5180,
I/ActivityManager(  948): Killing 5180:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 5647): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 5647): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
,D/Messaging( 5486): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 5486): networkCode: 
D/MessageCustFlag( 5486): sku_id=118
,D/MmsConfig( 5486): SIE smsPri: null
,D/MmsConfig( 5486): networkCode: 
,D/MmsConfig( 5486): packageName: com.htc.vvm.att does not exist,
D/Messaging( 5486): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 5486): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 5486): 
D/MmsAsyncWorkHandler( 5486): HM tk = 20001
,D/ReportIndicatorCache( 5486): MSG_QUERY_REPORTS >>
,D/SettingsManager( 5486): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@1a54d5bf
,I/ActivityManager(  948): Recipient 5180
,D/DraftCache( 5486): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5486): [DraftCache/1] refresh
,D/MmsConfig( 5486): networkCode: ,
I/Messaging( 5486): mccmnc> 
,D/Messaging( 5486): ViewCache CreatePreloadOnlyConversationList
,D/MessageCustFlag( 5486): sense_version=6.0,
,D/Jerry   ( 5486): start to preload cursor >>>>>>>,
,D/PhoneStorageUtil( 5486): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5486): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5486): createReceiver
,D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/GCM     ( 1909): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/AccFlag ( 1476): sku_id=118
,D/DraftCache( 5486): [DraftCache/121] rebuildCache
,D/ChimeraCfgMgr( 4243): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/TelephUtils( 1476): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
V/MmsProvider( 1476): Update uri=content://mms, match=0
V/MmsProvider( 1476): selection=st=129 AND m_type!=134
D/Messaging( 5486): Reset downloading state: 0
,D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/MmsSmsV2Provider( 1476):  slotId = -1000
D/MmsSmsV2Provider( 1476): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,V/MmsSystemEventReceiver( 5486): TransactionService is going to be woken up.
,D/ChimeraCfgMgr( 4243): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1476):  slotId = -1000
D/MmsSmsV2Provider( 1476): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
V/TransactionService( 5486): 1-Creating TransactionService
,I/Kids    ( 4243): [KidAccountFixer] No network connection
,D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/MmsSmsV2Provider( 1476):  slotId = -1000
,D/Messaging( 5486): ViewCache CreatePreload,
D/Messaging( 5486): ViewCache CreatePreloadOnlyMultipleOpsList
D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/Jerry   ( 1476): URI_DRAFT
,V/TransactionService( 5486): onStartCommand: 1
D/MmsSystemEventReceiver( 5486): unRegisterForConnectionStateChanges
,V/TransactionService( 5486): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5486): Loading previous transactions.
D/DraftCache( 5486): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 5486): [DraftCache/121] rebuildCache time: 2
D/MmsAsyncWorkHandler( 5486): 
D/MmsAsyncWorkHandler( 5486): HM tk = 20002
,I/ActivityManager(  948): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5683 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/Cust_MMSMS( 5486): _has_set_default_values_2=true
,D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/AccFlag ( 1476): device_type: 1
,D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1476):  slotId = -1000
D/TransactionService( 5486): Force clearing mTransactionList
D/MmsSmsV2Provider( 1476): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/TransactionService( 5486): Force set service start id to 1
V/TransactionService( 5486): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5486): unRegisterForConnectionStateChanges
,D/TransactionService( 5486): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 5486): Destroying TransactionService
,D/Messaging( 5486): mNeedToUpdateDate2: false
V/TransactionService( 5486): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/MsgPreferenceUtils( 5486): def_index: 0
D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91,
D/MmsSmsV2Provider( 1476):  slotId = -1000,
D/MmsSmsV2Provider( 1476): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 5486): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MsgPreferenceUtils( 5486): globalIndex = 1
D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1476): sku_id=118
,D/MsgPreferenceUtils( 5486): phone state: true
,D/MsgPreferenceUtils( 5486): sd state: false
D/MsgPreferenceUtils( 5486): vIndex = 0
,D/TelephUtils( 1476): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/AccFlag ( 1476): sku_id=118
,W/ResourcesManager( 5683): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5683): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5683): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 5486): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 5486): query uri: content://htc-mms-customization/mms-ua/ua_profile,
,I/Babel_SMS( 5683): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 5683): MmsConfig.loadFromDatabase
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5683, uid=10112, userID:0,
,E/Babel_SMS( 5683): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5683): MmsConfig.loadFromResources
,E/Babel_SMS( 5683): canonicalizeMccMnc: invalid mccmnc nullnull,
,I/Babel_SMS( 5683): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,W/Settings( 5683): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/Babel_Crash( 5683): startup - clean
,I/Babel   ( 5683): deleted: false for 0,
,I/HtcModeClient( 3155): handler message = 4011
E/HtcModeClient( 3155): Check connection and retry 6 times.
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5683, uid=10112, userID:0
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5683, uid=10112, userID:0,
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5683, uid=10112, userID:0,
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5683, uid=10112, userID:0
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5683, uid=10112, userID:0,
,W/art     ( 5683): Suspending all threads took: 5.821ms,
,D/PMS     (  948): acquireWL(138dfa51): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5683 10112 null,
,I/ActivityManager(  948): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5730 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,W/VideoCapabilities( 5683): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5683): Unsupported mime video/x-ms-wmv
,W/Utils   ( 5683): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 5683): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5683): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5683): Unsupported mime audio/qcelp
,W/VideoCapabilities( 5683): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 5683): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 5683): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5683): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5683): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager(  948): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/VideoCapabilities( 5683): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5683): onServiceConnected
,W/Babel   ( 5683): Attempted to change video mute state without an active call.
,I/Gmail   ( 5730): getAccountsCursor,
,W/GAV2    ( 5730): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5683): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=5730, uid=10106, userID:0,
W/ActivityManager(  948): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5730): Observing account changes for notifications,
,W/ActivityManager(  948): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  948): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5730, uid=10106, userID:0
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5730, uid=10106, userID:0
,I/Gmail   ( 5730): getAccountsCursor
,E/Gmail   ( 5730): Error finding the version of the Email provider.....
E/Gmail   ( 5730): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5730): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5730): 	,at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5730): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5730): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5730): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 5730): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 5730): We do not support migrating this version of the Email provider.
V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  948): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5774 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 5730): (283) recovered 1005 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ResourcesManager( 5774): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 5774): onCreate,
,D/ProviderChangeReceiver( 5774): ---------------------------------------------------
D/ProviderChangeReceiver( 5774): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!,
,D/Process (  948): killProcessQuiet, pid=5141
,I/ActivityManager(  948): Killing 5141:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/HtcAlertService( 5774): start to updateAlertNotification!
,I/Gmail   ( 5730): notifyAccountChanged
,V/JNIHelp ( 5683): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/Gmail   ( 5730): getAccountsCursor
,I/Gmail   ( 5730): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5730): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5730): calculateUnknownSyncRationalesAndPurgeInBackground: running,
I/Gmail   ( 5730): calculateUnknownSyncRationalesAndPurgeInBackground: running,
,I/ActivityManager(  948): Recipient 5141,
,V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
D/HtcAlertService( 5774): No fired or scheduled alerts
D/HtcAlertUtils( 5774): -- cancelReminderNotification --
D/AuthorizationBluetoothService( 1909): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/GCM     ( 1909): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/HtcAlertUtils( 5774): broadcastExistReminder!
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/GmsCoreStatsServiceLauncher( 4243): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4243, uid=10024, userID:0,
,E/MDM     ( 1819): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4243): Restart initialization of location,
W/System  ( 5683): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5683): Installed default security provider GmsCore_OpenSSL
,I/art     (  948): Explicit concurrent mark sweep GC freed 8160(391KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.672ms total 172.021ms
,D/DFPI.PIReciver( 5522): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,I/DFPI.ApkInstallService( 5522): onHandleIntent
,I/DFPI.ApkInstallService( 5522): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5522): check CID = HTC__102
I/DFPI.ApkInstallService( 5522): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
I/SoundPicker( 5570): SoundPickerReceiver [onReceive] startService
,E/PhoneInterfaceManager( 1476): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/ActivityManager(  948): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/SoundPicker( 5570): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5570): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5570): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5570): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,W/VideoCapabilities( 5683): Unrecognized profile 2130706433 for video/avc
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
W/VideoCapabilities( 5683): Unrecognized profile 2130706433 for video/avc
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
W/VideoCapabilities( 5683): Unrecognized profile 2130706433 for video/avc
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/Babel   ( 5683): connection state changed from UNKNOWN to DISCONNECTED
I/ActivityManager(  948): Resuming delayed broadcast
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/DFPI.PIReciver( 5522): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5522): onHandleIntent
I/ActivityManager(  948): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 5522): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5522): check CID = HTC__102
,I/DFPI.ApkInstallService( 5522): There is no Demo.apk in sd card or phone storage,
I/ActivityManager(  948): Resuming delayed broadcast
,I/NotifUtils( 5730): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false,
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] startService
,D/PMS     (  948): releaseWL(138dfa51): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/art     ( 5570): Explicit concurrent mark sweep GC freed 17420(1006KB) AllocSpace objects, 2(40KB) LOS objects, 87% free, 300KB/2MB, paused 331us total 30.996ms
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/DFPI.PIReciver( 5522): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/MediaStoreImporter( 5396): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/NotifUtils( 5730): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/DFPI.ApkInstallService( 5522): onHandleIntent
I/DFPI.ApkInstallService( 5522): Media Scan Finished Case 
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,D/DFPI.ApkInstallService( 5522): check CID = HTC__102
I/DFPI.ApkInstallService( 5522): There is no Demo.apk in sd card or phone storage
,I/Gmail   ( 5730): master sync=false, engine sync=true
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5570): SoundPickerReceiver [onReceive] startService
,I/Gmail   ( 5730): getAccountsCursor
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,V/GLSActivity( 1909): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,D/GCM     ( 1909): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Gmail   ( 5730): master sync=false, engine sync=true
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,D/AuthorizationBluetoothService( 1909): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,V/GmsCoreStatsServiceLauncher( 4243): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5570): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5570): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5570): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4243, uid=10024, userID:0
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
E/MDM     ( 1819): [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/LocationInitializer( 4243): Restart initialization of location
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/PMS     (  948): acquireWL(3e472ed9): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5683 10112 null
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/MediaStoreImporter( 5396): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/PMS     (  948): releaseWL(3e472ed9): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/[PluginManager]RegisterService( 1442): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1442): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  948): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5830 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102,
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5570): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 5570): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122,
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5570): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/MediaStoreImporter( 5396): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5830): -onCreate()
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5570): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,V/Settings:HtcSettingsApplication( 5830): [5830/5830] onCreate(),
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/ActivityManager(  948): Killing 5235:com.google.android.apps.plus/u0a167 (adj 15): empty #17
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
D/Process (  948): killProcessQuiet, pid=5235
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/Settings:HtcWirelessFeatureFlags( 5830): id/is att sku: 118/false,
,E/Settings:HtcWrapHeaderInfo( 5830): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5830): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 5830): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5830): isSupportMusicChannel(): false
,I/ActivityManager(  948): Recipient 5235
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportRecentAppsButton]support         :false
D/PackageBroadcastService( 4243): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportHomeButton]support         :false
,I/ActivityManager(  948): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5857 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 4243): Null package name or gms related package.  Ignoreing.
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
D/PMS     (  948): acquireWL(3e6ee011): PARTIAL_WAKE_LOCK  Icing 0x1 4243 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
I/Icing   ( 4243): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  948): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5830): isSupportVoWifi: null
E/ActivityThread( 5830): Failed to find provider info for com.htc.vowifi
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5570): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5830): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 5830): updateDevelopment, bPrefShow = true
,I/SoundPicker( 5570): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
E/Settings:HtcUmcWidgetEnabler( 5830): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportRecentAppsButton]support         :false
I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5570): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/Process (  948): killProcessQuiet, pid=5288
I/ActivityManager(  948): Killing 5288:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5830): [supportHomeButton]support         :false
,W/ResourcesManager( 5857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PMS     (  948): releaseWL(3e6ee011): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  948): Recipient 5288,
,I/ActivityManager(  948): Waited long enough for: ServiceRecord{1fef76e2 u0 com.htc.club/com.mcrm.autonotification.NotificationService}
,E/Settings:HtcVoWifiWidgetEnabler( 5830): isSupportVoWifi: null
,I/ActivityManager(  948): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5830): Failed to find provider info for com.htc.vowifi
,D/PMS     (  948): acquireWL(20420fe4): PARTIAL_WAKE_LOCK  AsyncService 0x1 5857 10167 null,
,D/PMS     (  948): acquireWL(22cbc302): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5857 10167 null,
,D/PMS     (  948): releaseWL(20420fe4): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/UpdateIcingCorporaServi( 5266): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
,I/ActivityManager(  948): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=5889 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/PMS     (  948): releaseWL(22cbc302): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5266): UpdateCorporaTask done [took 127 ms] updated apps [took 127 ms] ,
,D/Process (  948): killProcessQuiet, pid=5315
I/ActivityManager(  948): Killing 5315:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5315
,W/ContextImpl( 5889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 5830): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 5830): Cust_ConnectToPC   : Internet_Sharing>true,
D/        ( 5830): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 5830): Cust_ConnectToPC   : spcsc>false
D/        ( 5830): Cust_ConnectToPC   : IPT>true
D/        ( 5830): Cust_ConnectToPC   : Singel_USB>false,
D/SmartNS_NSReceiver( 5830): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5830): Index of the first 1 = -1
,W/ContextImpl( 5830): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5830): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 5830): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5830): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5830): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5830): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5830): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 5830): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead,
,I/ActivityManager(  948): Killing 4922:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  948): killProcessQuiet, pid=4922
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  948): Recipient 4922
,I/WSP     ( 1442): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC),
,D/WeatherUtility( 1442): Weather sync is On
,I/ActivityManager(  948): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5914 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/WSP     ( 1442): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Jan 12 00:48:46 CET 2016
,W/WSP     ( 1442): [Receiver] can't get active network info
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4243, uid=10024, userID:0
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4243, uid=10024, userID:0
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4243, uid=10024, userID:0
I/CheckinService( 4243): Done disabling old GoogleServicesFramework version
,V/WSP     ( 1442): [SyncService] no data connection, stop sync service
,W/ResourcesManager( 5914): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/ActivityManager(  948): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5936 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,I/Task_Calendar( 5914): Set ICALENDAR_UID to sync_data7 due to SDK_INT is 21,
,D/TodoTaskshortcut( 5914): update TASK shortcut>,
,D/Process (  948): killProcessQuiet, pid=5366
,I/ActivityManager(  948): Killing 5366:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5366
,D/WifiService(  948): Client connection lost with reason: 4
,D/SyncApplication( 5936): Loading default preferences,
,W/Resources( 5936): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,E/WifiTrafficPoller(  948): ADD_CLIENT: 6,
D/WifiService(  948): New client listening to asynchronous messages
,D/SyncApplication( 5936): Overriding preferences with custom values,
,D/SyncApplication( 5936): Updating preferences succeeded,
,E/SyncApplication( 5936): Application created.,
,W/VolumeInfo( 5936): Unable to read mount points,
W/VolumeInfo( 5936): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5936): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5936): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5936): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5936): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5936): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5936): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5936): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5936): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5936): 	,at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5936): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5936): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5936): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5936): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5936): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5936): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5936): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5936): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5936): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5936): 	... 13 more
,V/VolumeInfo( 5936): Found 0 mount point(s),
,V/VolumeInfo( 5936): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 5936): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 5936): getNewCalendarAuthority()...
,D/VolumeInfo( 5936): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5936, uid=10005, userID:0
,D/SyncApplication( 5936): enableAppOperation()+
W/PackageManager(  948): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
W/VolumeInfo( 5936): Can not create volume ID for unmounted volume null
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5936, uid=10005, userID:0,
W/PackageManager(  948): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 5936): enableAppOperation()-
,D/HTCUtilities( 5936): isNeorSinged() + 
,D/HTCUtilities( 5936): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>,
D/HTCUtilities( 5936): isNeorSinged() return false
,D/CDMountReceiver( 5936): whether to enable CD Auto-mount: true,
D/CDMountReceiver( 5936): showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,I/ActionCombine( 5936): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true,
D/CDMountReceiver( 5936): enable CD Auto-mount: true
,D/ProviderChangeReceiver( 5774): ---------------------------------------------------
D/ProviderChangeReceiver( 5774): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!,
,D/HtcAlertService( 5774): start to updateAlertNotification!
,D/HTCUtilities( 5936): enable auto-mount
I/HtcMountManagerAdapter( 5936): mHtcMountManager is  null
I/HtcMountManagerAdapter( 5936): mStorageManager is  not null
,D/HTCUtilities( 5936): enable auto-mount
D/VoldConnector(  948): SND -> {21 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
I/HtcMountManagerAdapter( 5936): mHtcMountManager is  null
D/VoldConnector(  948): SND -> {22 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
I/HtcMountManagerAdapter( 5936): mStorageManager is  not null
D/MountService(  948): mountISO: /system/etc/PCTOOL.ISO
,D/MountService(  948): mountISO: /system/etc/PCTOOL.ISO
,D/HtcAlertService( 5774): No fired or scheduled alerts
D/HtcAlertUtils( 5774): -- cancelReminderNotification --
,D/HtcAlertUtils( 5774): broadcastExistReminder!
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  948): acquireWL(313b3a14): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5396 10159 null
,I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5396, uid=10159, userID:0
,D/PMS     (  948): releaseWL(313b3a14): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
I/MusicLeanback( 5396): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 5396): Stop autocaching.
,E/GmsUtils( 5396): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5396): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Process (  948): killProcessQuiet, pid=5442
I/ActivityManager(  948): Killing 5442:com.htc.task.gtask/u0a66 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  948): Explicit concurrent mark sweep GC freed 12109(634KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.229ms total 186.522ms
D/PMS     (  948): releaseWL(9f0315b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10005},
,I/RemoteViews( 1218): apply : com.nero.android.htc.sync 1 6 2 38
,I/RemoteViews( 1218): apply : com.nero.android.htc.sync 0 7 2 53
,I/ActivityManager(  948): Recipient 5442
,D/AutoSetting( 1442): service - handleMessage() stop self
,D/AutoSetting( 1442): service - handleMessage() quit looper,
D/AutoSetting( 1442): service - onDestroy() END
,I/HtcModeClient( 3155): handler message = 4011,
E/HtcModeClient( 3155): Check connection and retry 7 times.
,I/GAV2    ( 5730): Thread[GAThread,5,main]: No campaign data found.,
,I/ActivityManager(  948): Killing 5472:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  948): killProcessQuiet, pid=5472
,D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5472
,D/Process (  948): killProcessQuiet, pid=5598
I/ActivityManager(  948): Killing 5598:com.htc.updater/u0a84 (adj 15): empty #17
,D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5598
,D/PMS     (  948): acquireWL(2cd3d729): PARTIAL_WAKE_LOCK  *alarm* 0x1 948 1000 WorkSource{10072}
V/AlarmManager(  948): sending alarm PendingIntent{34774aae: PendingIntentRecord{2020004f com.android.vending startService}}, i=null, t=0, cnt=1, w=1452552532630, Int=0
,D/PMS     (  948): releaseWL(2cd3d729): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 5100): [517] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5100): [1] 5.onFinished: Installation state replication succeeded.,
,I/HtcModeClient( 3155): handler message = 4011
,E/HtcModeClient( 3155): Check connection and retry 8 times.
,W/MediaManager( 5341): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  948): killProcessQuiet, pid=5647,
I/ActivityManager(  948): Killing 5647:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5647,
,I/ActivityManager(  948): Waited long enough for: ServiceRecord{b15ce22 u0 com.htc.musicenhancer/.EnhancerService},
,D/Process (  948): killProcessQuiet, pid=5486
,I/ActivityManager(  948): Killing 5486:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5486
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  948): acquireWL(1129bce5): PARTIAL_WAKE_LOCK  *alarm* 0x1 948 1000 WorkSource{1000}
V/AlarmManager(  948): sending alarm PendingIntent{47163ba: PendingIntentRecord{c86526b android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=85049, Int=0
,D/libc    (  948): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
V/AlarmManager(  948): sending alarm PendingIntent{2c0fe1c8: PendingIntentRecord{23e4261 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=85419, Int=0
D/libc    (  948): [NET] android_getaddrinfofornet-, err=8
D/PMS     (  948): releaseWL(1129bce5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  948): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  948): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  948): [NET] android_getaddrinfo_proxy+
,D/libc    (  948): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    (  948): [NET] android_getaddrinfo_proxy-, NODATA
,I/HtcModeClient( 3155): handler message = 4011
,E/HtcModeClient( 3155): Check connection and retry 9 times.
,D/PMS     (  948): acquireWL(24c20186): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 948 1000 WorkSource{1000}
V/AlarmManager(  948): sending alarm PendingIntent{1dfc6de3: PendingIntentRecord{e8823e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=85960, Int=0
,D/PMS     (  948): releaseWL(24c20186): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1218): Weather sync is On,
,W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data,
,I/ClockController( 1218): schedule update now=1452552540052 next=59948,
,I/Clock   ( 1218): updateClock:23:49 Europe/Warsaw,
I/Clock   ( 1218): updateClock:23:49 Europe/Warsaw
,I/Clock   ( 1218): updateClock:23:49 Europe/Warsaw,
,D/ContactMessageStore( 1476): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1476): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 3155): handler message = 4011
,E/HtcModeClient( 3155): Check connection and retry 10 times.
,I/HtcModeClient( 3155): handler message = 4011,
,E/HtcModeClient( 3155): Check connection and retry 11 times.
,W/ContextImpl(  948): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/HtcModeClient( 3155): handler message = 4011
,E/HtcModeClient( 3155): Check connection and retry 12 times.
,D/PMS     (  948): acquireWL(1798a3e3): PARTIAL_WAKE_LOCK  Icing 0x1 4243 10024 WorkSource{10024 com.google.android.gms},
,I/art     ( 1909): Explicit concurrent mark sweep GC freed 13688(706KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 880us total 51.125ms,
,D/PMS     (  948): releaseWL(1798a3e3): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/HtcModeClient( 3155): handler message = 4011
,E/HtcModeClient( 3155): Check connection and retry 12 times. Stop service and kill this process.,
D/HtcModeClient( 3155): Don't start project servcice,
D/HtcModeClient( 3155): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3155): connectState: CONNECTION_READY = false
,D/SilentMusic( 3155): call stop
,D/HtcModeClient( 3155): close connection
,W/HtcModeClient( 3155): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3155): read the terminate packet, so break
,D/Process (  948): killProcessQuiet, pid=3155,
I/ActivityManager(  948): Killing 3155:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 3155
,I/ActivityManager(  948): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5993 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  948): acquireWL(de47c0c): PARTIAL_WAKE_LOCK  *alarm* 0x1 948 1000 WorkSource{10076}
,V/AlarmManager(  948): sending alarm PendingIntent{55ca955: PendingIntentRecord{10ca2f6a com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452552561022, Int=60000
D/PMS     (  948): releaseWL(de47c0c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 5993): SMSBackupAgentService started
,D/SMSBackup( 5993): Checking restore status,
,D/SMSBackup( 5993): Restore complete
,D/SMSBackup( 5993): cancelCheckAlarm
,D/SMSBackup( 5993): SMSBackupAgentService completed: completed in 0.0 seconds,
D/PMS     (  948): acquireWL(2c634cf8): PARTIAL_WAKE_LOCK  *alarm* 0x1 948 1000 WorkSource{10024}
V/AlarmManager(  948): sending alarm PendingIntent{278b85d1: PendingIntentRecord{124760b0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=106271, Int=0
,D/Process (  948): killProcessQuiet, pid=5522
,D/PMS     (  948): acquireWL(29d3d836): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1909 10024 WorkSource{10024 com.google.android.gms}
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  948): Killing 5522:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
,D/libc    ( 1909): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1909): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1909): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1909): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1909): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1909): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1909): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  948): releaseWL(29d3d836): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  948): Recipient 5522
,D/PMS     (  948): releaseWL(2c634cf8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,I/PMS     (  948): Going to sleep due to screen timeout (uid 1000)...
,I/SensorManager(  948): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1cb152f6
W/SensorService(  948): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  948): disable: get sensor name = Accelerometer Sensor
W/SensorService(  948): pid=948, uid=1000
W/SensorService(  948): Active sensors: size = 4
W/SensorService(  948): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  948): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  948): CM36686 Proximity sensor (handle=0x00000004, connections=1)
,W/SensorService(  948): Significant Motion (handle=0x0000000d, connections=1)
W/PMN     (  948): goingToSleep
W/SensorService(  948): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1cb152f6, eanble = 0, strlen(mName) = 91
W/SensorService(  948): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  948): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@288ffdc8
W/SensorService(  948): Listener[1] = com.htc.smartdim.sensor_eye@b8c2232
W/SensorService(  948): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1218): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMS     (  948): mWirelessDisplayManager is null
,D/PMS     (  948): acquireWL(ad7b337): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 948 1000 null
W/PMS     (  948): mWirelessDisplayManager is still null
,I/PMS     (  948): Sleeping (uid 1000)...
D/XAN-DPS (  948): prepareColorFade 1
,W/PMN     (  948): goingToSleep done
,W/HtcSystemUPManager(  948): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/ActivityManager(  948): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6018 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
D/PMS     (  948): releaseWL(ad7b337): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  948): ACTION_SCREEN_ON
I/Adreno-EGL(  948): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  948): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  948): Build Date: 03/09/15 Mon
I/Adreno-EGL(  948): Local Branch: 
I/Adreno-EGL(  948): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  948): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  948):                  d74aa161a12b9c6fc6332151
,I/AlarmManager(  948): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  948): [AlarmQueuing] done recovering,
I/AlarmManager(  948): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  948): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiStateMachine(  948): handleMessage: E msg.what=131167
E/WifiStateMachine(  948): processMsg: InitialState
E/WifiStateMachine(  948):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  948): processMsg: DefaultState
E/WifiStateMachine(  948):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  948):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
,V/SRS_Proc(  402): ParamSet string: screen_state=on
,E/audio_a2dp_hw(  402): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  948): handleMessage: E msg.what=155650
D/WifiController(  948): processMsg: ApStaDisabledState
D/NetworkPolicy(  948): updateScreenOn: false
D/WifiController(  948): processMsg: DefaultState
V/NetworkPolicy(  948): updateIfacesLocked()
D/WifiController(  948): handleMessage: X
D/NetworkManagementService(  948): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/WifiStateMachine(  948): getWifiLinkLayerStats: WIFI is not enbled
D/WifiStateMachine(  948): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  948): handleScreenStateChanged Exit: true
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131154
E/WifiStateMachine(  948): processMsg: InitialState
E/WifiStateMachine(  948):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  948): processMsg: DefaultState
E/WifiStateMachine(  948):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131127
E/WifiStateMachine(  948): processMsg: InitialState
E/WifiStateMachine(  948):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  948): processMsg: DefaultState
D/GpsLocationProvider(  948): receive broadcast intent, action: android.intent.action.SCREEN_ON
E/WifiStateMachine(  948):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  948): handleMessage: X
,E/WifiStateMachine(  948): handleMessage: E msg.what=131129
E/WifiStateMachine(  948): processMsg: InitialState
E/WifiStateMachine(  948):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  948): processMsg: DefaultState
E/WifiStateMachine(  948):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  948): handleMessage: X
,W/ResourcesManager( 6018): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/CalendarProvider2( 6018): Created com.android.providers.calendar.CalendarAlarmManager@f16f319(com.htc.providers.calendar.HtcCalendarProvider@92d4fde),
I/IntentController( 1218): receive(android.intent.action.SCREEN_ON,1,false)
,D/CalendarProvider2( 6018): wait start:true
,D/PMS     (  948): acquireWL(3fbfe428): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1819 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  948): acquireWL(3b288541): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  948): releaseWL(3fbfe428): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  948): prepareColorFade done
D/XAN-DPS (  948): setBrightness to 0
D/PMS     (  948): releaseWL(3b288541): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/DisplayManagerService(  948): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,I/SensorManager(  948): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@288ffdc8
W/SensorService(  948): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  948): disable: get sensor name = CM32181 Light sensor
,W/SensorService(  948): pid=948, uid=1000
W/SensorService(  948): Active sensors: size = 3
W/SensorService(  948): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  948): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  948): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  948): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@288ffdc8, eanble = 0, strlen(mName) = 67
W/SensorService(  948): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  948): Listener[0] = com.htc.smartdim.sensor_eye@b8c2232
W/SensorService(  948): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1304): [EventService]  onDisplayChanged: 0
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
V/ActivityManager(  948): Display changed displayId=0
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
D/AlarmManager(  948): ACTION_SCREEN_OFF
D/DotMatrix( 1304): [EventService] mbHDMIConnect: false, mCoverOn:false
,I/AlarmManager(  948): [AlarmQueuing] screen off now: 
I/AlarmManager(  948): [AlarmQueuing] data connection: true
I/AlarmManager(  948): [AlarmQueuing] wifi connection: false
,D/WifiDataStallTracker(  948): stopDataStallAlarm 
,E/WifiDataStallTracker(  948): ENABLE_DATA_MONITOR_POLL false Token 0
E/WifiStateMachine(  948): handleMessage: E msg.what=131167
E/WifiStateMachine(  948): processMsg: InitialState
E/WifiStateMachine(  948):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  948): processMsg: DefaultState
,E/WifiStateMachine(  948):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
V/SRS_Proc(  402): ParamSet string: screen_state=off
E/WifiStateMachine(  948):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
E/audio_a2dp_hw(  402): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiStateMachine(  948): getWifiLinkLayerStats: WIFI is not enbled
D/WifiDisplayAdapter(  948): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  948):     Client/Owner: Client
D/WifiDisplayAdapter(  948):     GroupId: 
D/WifiDisplayAdapter(  948):     Passphrase: 
D/WifiDisplayAdapter(  948):     SessionId: 0
D/WifiDisplayAdapter(  948):     IP Address: }
E/WifiStateMachine(  948): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  948): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  948): handleScreenStateChanged Exit: false
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131154
E/WifiStateMachine(  948): processMsg: InitialState
E/WifiStateMachine(  948):  InitialState CMD_ENABLE_RSSI_POLL 0 0
D/WifiController(  948): handleMessage: E msg.what=155651
E/WifiStateMachine(  948): processMsg: DefaultState
D/WifiController(  948): processMsg: ApStaDisabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
E/WifiStateMachine(  948):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
D/NetworkPolicy(  948): updateScreenOn: false
E/WifiStateMachine(  948): handleMessage: X
V/NetworkPolicy(  948): updateIfacesLocked()
D/NetworkManagementService(  948): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/CalendarProvider2( 6018): wait end:false
,W/ContextImpl( 5889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager( 1218): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@13df5be, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  948): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  948): enable: get sensor name = hTC Gesture Motion HIDI
,W/ContextImpl( 5889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5889): MY_DEBUG = false
,W/SensorService(  948): pid=1218, uid=10041
W/SensorService(  948): Active sensors: size = 4
W/SensorService(  948): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  948): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  948): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  948): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  948): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@13df5be, eanble = 1, strlen(mName) = 56
W/SensorService(  948): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  948): Listener[0] = com.htc.smartdim.sensor_eye@b8c2232
W/SensorService(  948): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@13df5be
W/SensorService(  948): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  948): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1304): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1476): start background delete task...,
,D/PMS     (  948): acquireWL(28adcfc3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5889 1000 null
I/IntentController( 1218): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1476): size: 0 , 0
,D/PMS     (  948): acquireWL(3b211040): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
D/ContactMessageStore( 1476): Background delete complete
D/SmartSyncUtils( 5889): isEpsOn(), nState = 0
,D/PMS     (  948): releaseWL(3b211040): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  948): acquireWL(11879b79): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(11879b79): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(28adcfc3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,W/ContextImpl(  948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  948): Init customizeScreenOffDelayClass error,
,I/RemoteViews( 1218): setHTCTheme(com.htc.updater,true,33751145),
,I/RemoteViews( 1218): apply : com.htc.updater 1 8 1 36,
,W/ContextImpl( 5889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 5889): isEpsOn(), nState = 0
,D/SmartSyncUtils( 5889): isEpsOn(), nState = 0
,W/ContextImpl( 5889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  948): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  948): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@b8c2232
W/SensorService(  948): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  948): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  948): pid=948, uid=1000
W/SensorService(  948): Active sensors: size = 3,
W/SensorService(  948): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  948): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  948): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  948): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@b8c2232, eanble = 0, strlen(mName) = 35
W/SensorService(  948): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  948): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@13df5be
W/SensorService(  948): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  948): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  948): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  948): pid=948, uid=1000
,W/SensorService(  948): Active sensors: size = 2
W/SensorService(  948): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  948): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  948): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@b8c2232, eanble = 0, strlen(mName) = 35
W/SensorService(  948): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  948): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@13df5be
W/SensorService(  948): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  948): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@b8c2232
E/ActivityThread(  948): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1c1fb83 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  948): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1c1fb83 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  948): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  948): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767),
E/ActivityThread(  948): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  948): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  948): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  948): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  948): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  948): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  948): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  948): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  948): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  948): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  948): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  948): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  948): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  948): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  948): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  948): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  948): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/PowerUsageList:PowerUsageHelper( 5889): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5889): gen(), null == sipper.uidObj, userId = 0,
,I/ActivityManager(  948): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6058 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2,
D/PMS     (  948): Setting HAL interactive mode to false
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  948): Setting HAL interactive mode to false done
D/SurfaceControl(  948): Excessive delay in setPowerMode(): 294ms
D/PMS     (  948): Setting HAL auto-suspend mode to true
W/HtcSystemUPManager(  948): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  948): Setting HAL auto-suspend mode done
D/HABCtrl (  948): TPE algorithm. remove timeout.
D/PMS     (  948): OOBE c monitor 11
,I/InputMethodManagerService(  948): screenObserver, isScreenOn=false
I/InputManager(  948): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
D/StatusBarManagerService(  948): swetImeWindowStatus vis=0 backDisposition=0
I/IntentController( 1218): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  948): Disable input method client, pid=4549
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
,D/NfcService( 1491): ScreenObserver: OFF
,D/NfcService( 1491): applyRouting - 0
,D/PMS     (  948): acquireWL(c26f06c): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1491 1027 null
D/PMS     (  948): acquireWL(295d7635): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
,I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(295d7635): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/WifiController(  948): battery changed pluggedType: 2
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/WifiController(  948): handleMessage: E msg.what=155652
D/WifiController(  948): processMsg: ApStaDisabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  948): runPSCheck
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  948): Checking...
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  948): >> updateStatus,
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NfcService( 1491): applyRouting -2
D/NfcService( 1491): applyRouting
D/NfcService( 1491): Ignore this applyRouting...
,D/SmartSyncUtils( 5889): getMobilePolicyEnabled, result = true
D/PowerUI ( 1218): closing low battery warning: level=100
D/PMS     (  948): releaseWL(c26f06c): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
,D/WifiService(  948): New client listening to asynchronous messages
,E/WifiTrafficPoller(  948): ADD_CLIENT: 7
,I/ClockController( 1218): stop clock update:screen off,
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/PowerUsageList:PowerUsageHelper( 5889): MY_DEBUG = false
,D/Process (  948): killProcessQuiet, pid=5570,
I/ActivityManager(  948): Killing 5570:com.htc.sdm/u0a79 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5570
,I/CalendarProvider2( 6018): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 6018): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 5774): ---------------------------------------------------,
D/ProviderChangeReceiver( 5774): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!,
,D/HtcAlertService( 5774): start to updateAlertNotification!
,D/Process (  948): killProcessQuiet, pid=5857
I/ActivityManager(  948): Killing 5857:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  948): releaseWL(3d6c8a78): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  948): Recipient 5857
,D/HtcAlertService( 5774): No fired or scheduled alerts
D/HtcAlertUtils( 5774): -- cancelReminderNotification --
D/HtcAlertUtils( 5774): broadcastExistReminder!
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcUPManager( 1218): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,D/ContactMessageStore( 1476): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1476): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  948): acquireWL(38cdaaca): PARTIAL_WAKE_LOCK  *alarm* 0x1 948 1000 WorkSource{1000},
V/AlarmManager(  948): sending alarm PendingIntent{3bd7743b: PendingIntentRecord{c8a758 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452552577371, Int=0
D/PMS     (  948): acquireWL(3e7c40b1): PARTIAL_WAKE_LOCK  *backup* 0x1 948 1000 null,
,D/PMS     (  948): releaseWL(38cdaaca): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  948): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  948): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  948): releaseWL(3e7c40b1): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,D/Process (  948): killProcessQuiet, pid=5545
,I/ActivityManager(  948): Killing 5545:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5545
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  948): acquireWL(3083a996): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(3083a996): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  948): updateBatteryInfo
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/PMS     (  948): runPSCheck
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  948): Checking...
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/HtcPowerSaver(  948): >> updateStatus
,D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/PowerUI ( 1218): closing low battery warning: level=100
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  948): handleMessage: E msg.what=155652
,D/WifiController(  948): processMsg: ApStaDisabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): handleMessage: X
,I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  948): acquireWL(5bf1917): PARTIAL_WAKE_LOCK  *alarm* 0x1 948 1000 WorkSource{10024},
V/AlarmManager(  948): sending alarm PendingIntent{2acce104: PendingIntentRecord{32e336ed com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141843, Int=0
,D/PMS     (  948): releaseWL(5bf1917): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  948): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  948): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
,W/ContextImpl(  948): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  948): acquireWL(dc8c922): PARTIAL_WAKE_LOCK  *alarm* 0x1 948 1000 WorkSource{1000}
V/AlarmManager(  948): sending alarm PendingIntent{2c0fe1c8: PendingIntentRecord{23e4261 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145433, Int=0
V/AlarmManager(  948): sending alarm PendingIntent{1dfc6de3: PendingIntentRecord{e8823e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=145959, Int=0,
,V/AlarmManager(  948): sending alarm PendingIntent{3e122fb3: PendingIntentRecord{fb90970 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=166232, Int=0
D/libc    (  948): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  948): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  948): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  948): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  948): [NET] android_getaddrinfo_proxy+
D/libc    (  948): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
,D/libc    (  948): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  948): releaseWL(dc8c922): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1218): Weather sync is On
,W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,D/TelephonyReceiver( 1476): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 5
,D/HtcUPManager( 1218): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1218): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1442): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@28a2238
,I/ActivityManager(  948): Killing 5266:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  948): killProcessQuiet, pid=5266
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5266
,TIME-OUT KILL (timeout was 150000ms)
```
