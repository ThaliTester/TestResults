#### Test 50242285e707819_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
W/BroadcastQueue(  970): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
I/ActivityManager(  970): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4558 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  970): Killing 3918:com.google.android.configupdater/u0a98 (adj 15): empty #17
--------- beginning of main
D/Process (  970): killProcessQuiet, pid=3918
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/SearchBackgroundTaskFac( 4484): Checking for language pack updates
I/ActivityManager(  970): Recipient 3918
D/Process (  970): killProcessQuiet, pid=3080
I/ActivityManager(  970): Killing 3080:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/art     (  970): Explicit concurrent mark sweep GC freed 11854(597KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 2.243ms total 158.753ms
D/WifiService(  970): New client listening to asynchronous messages
E/WifiTrafficPoller(  970): ADD_CLIENT: 6
I/VelvetNetworkClient( 4484): Network connection not availble
I/ActivityManager(  970): Recipient 3080
E/cutils-trace( 4580): Error opening trace file: Permission denied (13)
I/VelvetNetworkClient( 4484): Network connection not availble
I/GservicesUpdateTask( 4484): Updating Gservices keys
I/VelvetNetworkClient( 4484): Network connection not availble
D/CustomizationManager( 4580): ====startRecUseTime====
D/htc.customization.log.level( 4580):  is 
W/CustomizationLogLevel( 4580): Level value is invalid, use default level 2
D/AuthorizationBluetoothService( 1872): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/GCM     ( 1872): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
V/GmsCoreStatsServiceLauncher( 4228): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  970): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4616 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4228, uid=10024, userID:0
D/CustomizationManager( 4580):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 4580): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4580): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4580): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4580): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4580): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4580): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4580): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4580): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4580): Parsing tag category name = system
I/CustomizationCIDLoader( 4580): Parsing tag category name = application
I/CustomizationCIDLoader( 4580): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4580): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4580): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4580): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4580): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4580): add string-array item, value = 42507
I/CustomizationCIDLoader( 4580): add string-array item, value = 21902
I/CustomizationCIDLoader( 4580): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4580): add string-array item, value = 23420
I/CustomizationCIDLoader( 4580): add string-array item, value = 22299
I/CustomizationCIDLoader( 4580): add string-array item, value = 24002
I/CustomizationCIDLoader( 4580): add string-array item, value = 23210
I/CustomizationCIDLoader( 4580): add string-array item, value = 23205
I/CustomizationCIDLoader( 4580): add string-array item, value = 23806
I/CustomizationCIDLoader( 4580): add string-array item, value = 23430
I/CustomizationCIDLoader( 4580): add string-array item, value = 23408
I/CustomizationCIDLoader( 4580): add string-array item, value = 27205
I/CustomizationCIDLoader( 4580): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4580): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4580): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4580): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4580): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4580): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4580): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4580): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4580): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4580): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4580): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4580): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4580):  Read CID file spent 0.107 (s)
D/CustomizationManager( 4580):  All configurations done spent 0.107 (s)
W/ResourcesManager( 4616): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4616): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/TelephUtils( 1461): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
D/AccFlag ( 1461): sku_id=118
I/MultiDex( 4616): VM with version 2.1.0 has multidex support
I/MultiDex( 4616): install
I/MultiDex( 4616): VM has multidex support, MultiDex support library is disabled.
I/WebViewFactory( 4484): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
W/art     ( 4228): Suspending all threads took: 15.292ms
I/ActivityManager(  970): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4644 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
I/art     ( 4228): Background sticky concurrent mark sweep GC freed 4976(475KB) AllocSpace objects, 7(140KB) LOS objects, 12% free, 4MB/5MB, paused 20.604ms total 64.760ms
D/PMS     (  970): acquireHCC(14c37f76): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 970 1000 null
D/PMS     (  970): acquireHCC(76459e4): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 970 1000 null
I/ActivityManager(  970): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4580 on display 0
W/asset   (  970): Copying FileAsset 0x55b8922be0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  970): acquireWL(374f2613): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 970 1000 null
I/AnimationUtil(  970): isHTCRecent(HelloWorld/Recent screens.)/5
D/LocationInitializer( 4228): Restart initialization of location
I/FeedHostManager( 1519): [onPause]
I/FeedProviderManager( 1519): onPause
I/FeedHostManager( 1519): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@49f7965
I/SocialFeedProvider( 1519): +onPause
I/SocialFeedProvider( 1519): -onPause
D/TelephUtils( 1461): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64
D/AccFlag ( 1461): sku_id=118
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  970): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4671 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/LibraryLoader( 4484): Time to load native libraries: 13 ms (timestamps 7295-7308)
I/LibraryLoader( 4484): Expected native library version number "",actual native library version number ""
I/art     (  449): Explicit concurrent mark sweep GC freed 8672(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 309us total 21.952ms
W/art     ( 4484): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4484): Suspending all threads took: 6.108ms
I/art     (  449): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 252us total 17.358ms
V/JNIHelp ( 4616): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/art     (  449): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 421us total 21.497ms
W/asset   ( 4671): Copying FileAsset 0xac1cbc80 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/TelephUtils( 1461): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
D/AccFlag ( 1461): sku_id=118
D/StatusBarManagerService(  970): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
D/TelephUtils( 1461): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64
D/AccFlag ( 1461): sku_id=118
W/ActivityThread( 4616): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4616): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d45c2b1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4616): Installed default security provider GmsCore_OpenSSL
I/TrimMemoryManager( 1519): [trimMemory] 20
D/WearableService( 4616): callingUid 10024, callindPid: 4616
E/MDM     ( 1805): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/ImageRamCache( 4644): create image Cache, size: 31457280.
I/ImageRamCache( 4644): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4644): create image Cache, size: 31457280.
I/FeedSettings( 4644): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4644): GroupBudget 0.500000 0.380000
I/FeedSettings( 4644): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 4644): changeLocale(): en_GB
,W/art     ( 4484): Attempt to remove local handle scope entry from IRT, ignoring
I/Prism.AllAppsOptionsMa_( 4644): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 4644): loadGridSize() with Alternative
I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/WebViewFactory( 4671): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/RefreshDomainCookieTask( 4484): Search parameters fetch failed: com.google.android.apps.gsa.shared.api.io.GsaIOException: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
W/RefreshDomainCookieTask( 4484): Search parameters fetch failed
D/CustomHighlightReceiver( 4644): [custom highlight] onReceive
D/CustomHighlightService( 4644): [custom highlight] onHandleIntent
D/NewsDB  ( 4644): set custom highlight []
I/ActivityManager(  970): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4711 uid=10035 gids={50035, 9997} abi=arm64-v8a
I/art     ( 1872): Explicit concurrent mark sweep GC freed 12452(711KB) AllocSpace objects, 1(20KB) LOS objects, 50% free, 3MB/7MB, paused 930us total 46.777ms
D/CustomHighlightService( 4644): [custom highlight] set tags 
I/LibraryLoader( 4671): Time to load native libraries: 11 ms (timestamps 7586-7597)
I/LibraryLoader( 4671): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4671): Binding Chromium to main looper Looper (main, tid 1) {1126e4ae}
I/LibraryLoader( 4671): Expected native library version number "",actual native library version number ""
I/chromium( 4671): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  970): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4738 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Process (  970): killProcessQuiet, pid=3979
I/ActivityManager(  970): Killing 3979:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActionCombine( 1872): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/BrowserStartupController( 4671): Initializing chromium process, singleProcess=true
W/art     ( 4671): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4671): ApplicationContext is null in ApplicationStatus
W/Search.LoginHelper( 4484): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4484): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4484): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4484): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4484): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4484): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4484): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 4484): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4484): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4484): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4484): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4484): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4484): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4484): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4484): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/chromium( 4671): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 4671): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4671): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4671): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4671): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4671): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4671): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4671): Local Branch: 
I/Adreno-EGL( 4671): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4671): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4671):                  d74aa161a12b9c6fc6332151
I/ActivityManager(  970): Recipient 3979
W/ResourcesManager( 1221): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1221): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Process (  970): killProcessQuiet, pid=4007
I/ActivityManager(  970): Killing 4007:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  970): java.lang.Throwable: stack dump
W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  970): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cbfdba:true
I/RemoteViews( 1221): apply : com.google.android.gms 0 12 4 40
D/BluetoothAdapter( 4671): 6921957: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  970): Recipient 4007
D/SMSBackup( 4738): Got a database change event
D/Process (  970): killProcessQuiet, pid=4076
I/ActivityManager(  970): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4775 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  970): Killing 4076:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
I/art     (  448): Explicit concurrent mark sweep GC freed 8647(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 236us total 23.154ms
I/art     (  448): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 165us total 17.517ms
I/art     (  448): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 213us total 17.203ms
I/ActivityManager(  970): Recipient 4076
D/MessagingShortcutReceiver( 3721): keep hiding shortcut bubble
D/MessagingShortcut( 3721): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 3721): After query: 0
D/MessagingShortcut( 3721): mPresentUnreadCount: -1
D/MessageUtils( 3721): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 3721): setMsgShortcutDrawable> 0, false
D/MessagingShortcut( 3721): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderNotification, total:0
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  970): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4803 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
W/art     ( 4671): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  970): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4825 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
W/AwContents( 4671): onDetachedFromWindow called when already detached. Ignoring
D/PMS     (  970): releaseWL(e9a06bb): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
W/ResourcesManager( 4803): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/SystemWebViewEngine( 4671): CordovaWebView is running on device made by: HTC
W/art     ( 4671): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4671): Attempt to remove local handle scope entry from IRT, ignoring
D/TodoTaskshortcut( 4803): update TASK shortcut>
D/PMS     (  970): acquireWL(cee537): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4803 10069 null
D/PMS     (  970): acquireWL(157b9bc2): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4803 10069 null
D/PMS     (  970): releaseWL(cee537): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/chromium( 4671): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
E/TodoTaskNotifyService( 4803): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4803): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
D/MdScBoot( 4775): [9f3.1.] 30@-143544 -> 40
D/MdScBootUi( 4775): [9f3.1.2.] boot 118
W/System.err( 4803): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4803): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4803): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4803): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4803): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  970): releaseWL(157b9bc2): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 4803): stopSelfResult true
D/MdScSimSt( 4775): [9f3.1.2.] qry 118: 0+1 running 0
I/ActivityManager(  970): Killing 4097:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=4097
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/FindExtension( 4671): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ActivityManager(  970): Recipient 4097
I/InputMethodManager( 4671): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3fcde5b, mServedView=org.apache.cordova.engine.SystemWebView{13cc96f8 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3fec07d1
I/InputMethodManagerService(  970): Disable input method client, pid=1519
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  970): Enable input method client, pid=4671
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
I/ActivityManager(  970): Displayed com.example.hello/.MainActivity: +1s107ms
D/Process (  970): killProcessQuiet, pid=4121
I/ActivityManager(  970): Killing 4121:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,W/XT9_C   ( 1349): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1349): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1349): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1349): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  970): acquireWL(1334e11a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
W/BindingManager( 4671): Cannot call determinedVisibility() - never saw a connection for the pid: 4671
I/chromium( 4671): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager(  970): Recipient 4121
D/PMS     (  970): releaseWL(374f2613): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/MtpReceiver( 3650): [MTP][handleUsbStateAsync]+
I/ActivityManager(  970): Killing 4144:com.android.smith/1000 (adj 15): empty #17
D/MtpReceiver( 3650): [MTP][handleUsbStateAsync]1:1-
D/Process (  970): killProcessQuiet, pid=4144
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/MtpReceiver( 3650): [MTP][handleUsbState]+
D/JsMessageQueue( 4671): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4671): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ActivityManager(  970): Recipient 4144
D/ContactMessageStore( 1461): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1461): MSG_NOTIFY_CS_TO_SYNC <<
I/ActivityManager(  970): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4864 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
D/MtpReceiver( 3650): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpService( 3650): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpReceiver( 3650): [MTP][handleUsbState]-
D/MtpReceiver( 3650): [MTP][handleMessage]-
D/MtpDatabase( 3650): TotalSize=1886532,MediaCacheLimit=6000
D/PMS     (  970): releaseWL(1334e11a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/MtpService( 3650): [isMtpConnected] connected: true
D/jxcore_app_log( 4671): JniHelper::setJavaVM(0xab05d8f8), pthread_self() = -1405635304
D/JX-Cordova( 4671): jxcore cordova android initializing
E/MediaScannerService( 3650): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3650): [handleMessage] --- Should not be here, ignore request. ----
D/SyncApplication( 4864): Loading default preferences
W/Resources( 4864): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
W/jxcore-log( 4671): Initializing JXcore engine
W/jxcore-log( 4671): JXcore engine is ready
W/jxcore-log( 4671): Starting JXcore engine
D/WifiService(  970): New client listening to asynchronous messages
E/WifiTrafficPoller(  970): ADD_CLIENT: 7
D/SyncApplication( 4864): Overriding preferences with custom values
D/SyncApplication( 4864): Updating preferences succeeded
E/SyncApplication( 4864): Application created.
W/VolumeInfo( 4864): Unable to read mount points
W/VolumeInfo( 4864): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4864): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 4864): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 4864): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 4864): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 4864): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 4864): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 4864): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 4864): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 4864): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 4864): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 4864): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 4864): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 4864): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 4864): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 4864): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4864): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 4864): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 4864): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 4864): 	... 13 more
I/CalendarDefines( 4864): getNewCalendarAuthority()...
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4864, uid=10005, userID:0
V/VolumeInfo( 4864): Found 0 mount point(s)
W/PackageManager(  970): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
V/VolumeInfo( 4864): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4864, uid=10005, userID:0
W/PackageManager(  970): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4864): enableAppOperation()+
D/VolumeInfo( 4864): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/SyncApplication( 4864): enableAppOperation()-
D/HTCUtilities( 4864): isNeorSinged() + 
D/VolumeInfo( 4864): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/VolumeInfo( 4864): Can not create volume ID for unmounted volume null
E/MediaScannerServiceEx( 3650): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3650): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3650): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3650): calcVolumeId: /storage/emulated/0
D/HTCUtilities( 4864): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/MediaProviderUtils( 3650): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3650): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3650): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3650): [AliveExtStorageRows]+65537, 11223344
D/HTCUtilities( 4864): isNeorSinged() return false
D/CDMountReceiver( 4864): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 4864): USB connected to PC
D/MediaProvider( 3650): [update][6]#0#
D/MediaProvider( 3650): [update][1]#0#
D/MediaProvider( 3650): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3650): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3650): [update][10]#1#
D/FOTAReceiver( 4864): onReceive() enter 
D/FOTAReceiver( 4864): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/MediaScannerServiceEx( 3650): [AliveExtStorageRows]-0, 0
D/PMS     (  970): acquireWL(32bf971f): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3650 10017 null
D/TetherSettings( 4055): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4055): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4055): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4055): Cust_ConnectToPC   : spcsc>false
D/        ( 4055): Cust_ConnectToPC   : IPT>true
D/        ( 4055): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4055): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4055): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4055): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4055): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4055): usb_cable_connect = 1
D/SmartNS_Utility( 4055): usb_denied = 0
D/MediaScanner( 3650): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
I/SmartNS_NSReceiver( 4055): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 4055): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 4055): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 4055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_PSService( 4055): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 4055): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4055):  defaultType:0
I/SmartNS_PSService( 4055): fail notificaiton:false
D/SmartNS_Utility( 4055): usb_cable_connect = 1
D/SmartNS_Utility( 4055): usb_denied = 0
I/SmartNS_PSService( 4055): usb notificaiton:true
I/ActivityManager(  970): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4894 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
W/jxcore-log( 4671): Platform android
W/jxcore-log( 4671): 
W/jxcore-log( 4671): Process ARCH arm
W/jxcore-log( 4671): 
I/jxcore-log( 4671): JXcore Cordova bridge is ready!
I/jxcore-log( 4671): 
W/jxcore-log( 4671): JXcore engine is started
D/SmartNS_Utility( 4055): usb_cable_connect = 1
D/SmartNS_Utility( 4055): usb_denied = 0
I/SmartNS_PSService( 4055): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartNS_Utility( 4055): usb_cable_connect = 1
D/SmartNS_Utility( 4055): usb_denied = 0
I/SmartNS_PSService( 4055): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 4055): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  970): Killing 4202:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=4202
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/jxcore-log( 4671): >> HTC-HTC One M8s
E/jxcore-log( 4671): 
I/jxcore-log( 4671): Total memory 1931808768
I/jxcore-log( 4671): 
I/jxcore-log( 4671): Free memory 92856320
I/jxcore-log( 4671): 
I/jxcore-log( 4671): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4671): 
I/jxcore-log( 4671): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4671): 
I/jxcore-log( 4671): userPath [ 'www' ]
I/jxcore-log( 4671): 
I/jxcore-log( 4671): Size 1080 1776
I/jxcore-log( 4671): 
I/jxcore-log( 4671): Screen Brightness 142
I/jxcore-log( 4671): 
E/jxcore-log( 4671): Dummy Error Log.
E/jxcore-log( 4671): 
I/art     (  970): Explicit concurrent mark sweep GC freed 12029(570KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.504ms total 142.187ms
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1221): reapply : com.android.settings 1 36
I/ActivityManager(  970): Recipient 4202
W/ContextImpl( 4894): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1221): reapply : com.android.settings 1 36
,I/ActivityManager(  970): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4917 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/Process (  970): killProcessQuiet, pid=4165
,I/ActivityManager(  970): Killing 4165:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 4165
,D/PMS     (  970): releaseHCC(14c37f76): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  970): releaseHCC(76459e4): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/ResourcesManager( 4917): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/CalendarProvider2( 4917): Created com.android.providers.calendar.CalendarAlarmManager@33d0924f(com.htc.providers.calendar.HtcCalendarProvider@147c8ddc)
,D/CalendarProvider2( 4917): wait start:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/FlexNetS( 4917): updateSvcAllowedInSettings:false
,D/CalendarProvider2( 4917): wait end:false
,I/ActivityManager(  970): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4942 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/jxcore-log( 4671): getBuffer is called!!!!
I/jxcore-log( 4671): 
,W/ContextImpl( 4942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  970): acquireWL(2a2ff6e9): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4942 1000 null
,D/PowerUsageList:PowerUsageHelper( 4942): MY_DEBUG = false
,I/ActivityManager(  970): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4968 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
,D/PowerUsageService( 4942): repeat time = 1449499874569
,D/WeatherUtility( 1435): Weather sync is On,
,D/WSP     ( 1435): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,I/ActivityManager(  970): Waited long enough for: ServiceRecord{16d21411 u0 com.htc.HTCSpeaker/.NGFService},
,D/Prism.PackageStateRece_( 1519): action: android.intent.action.PACKAGE_ADDED,
I/[PluginManager]RegisterService( 1435): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1435): handle notify Blinkfeed plugin client changed
,D/WeatherUtility( 4968): Weather sync is On
,I/ActivityManager(  970): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4996 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/PowerUsageList:PowerUsageHelper( 4942): PowerProfile::POWER_SCREEN_FULL = 154.8
,W/WeatherRequest( 4968): request cur loc, but there is no sys cur
W/Settings( 4968): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActionCombine( 4968): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
D/PowerUsageList:BatterySipperExt( 4942): gen(), null == sipper.uidObj, userId = 0,
,I/RemoteViews( 1519): reapply : com.htc.widget.weatherclock 11 17,
,I/DeviceManagement( 4996): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4996 dbg=false s=true,
,I/DeviceManagement( 4996): PackageUpdateReceiver: vvv Package added: [com.example.hello],
,D/Process (  970): killProcessQuiet, pid=3345
I/ActivityManager(  970): Killing 3345:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
,I/ActivityManager(  970): Recipient 3345
,I/ActivityManager(  970): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5018 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/Process (  970): killProcessQuiet, pid=4360
I/ActivityManager(  970): Killing 4360:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 4360,
,D/HtcCupdReceiver(Provider)( 5018):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  970): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5040 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  970): killProcessQuiet, pid=4439
I/ActivityManager(  970): Killing 4439:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/CalendarProvider2( 4917): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 4917): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  970): Recipient 4439
,D/Settings:HtcWirelessFeatureFlags( 4055): id/is att sku: 118/false,
,I/ActivityManager(  970): Killing 4484:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  970): killProcessQuiet, pid=4484
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/Settings:HtcWrapHeaderInfo( 4055): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4055): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4055): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4055): isSupportMusicChannel(): false,
I/ActivityManager(  970): Recipient 4484
D/WifiService(  970): Client connection lost with reason: 4
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportHomeButton]support         :false
,I/HtcModeClient( 3156): handler message = 4011,
E/HtcModeClient( 3156): Check connection and retry 4 times.
,I/ActivityManager(  970): Cannot resolve ContentProvider=com.htc.vowifi,
E/Settings:HtcVoWifiWidgetEnabler( 4055): isSupportVoWifi: null
E/ActivityThread( 4055): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4055): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4055): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4055): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportHomeButton]hasRecentAppKey :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4055): [supportHomeButton]support         :false
,I/ActivityManager(  970): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 4055): isSupportVoWifi: null
,E/ActivityThread( 4055): Failed to find provider info for com.htc.vowifi
,V/AlarmManager(  970): sending alarm PendingIntent{412f47a: PendingIntentRecord{12eb742b com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1449498975617, Int=0
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5040, uid=10072, userID:0
,W/global  ( 5040): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 5040): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 5040): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5040): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5040): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,D/Process (  970): killProcessQuiet, pid=4644
I/ActivityManager(  970): Killing 4644:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 4644
,I/ActivityManager(  970): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5081 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/Settings( 5040): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5040): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     (  448): Explicit concurrent mark sweep GC freed 8673(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 295us total 32.791ms
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5040, uid=10072, userID:0
,I/art     (  448): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 184us total 24.565ms
,W/ResourcesManager( 5081): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5081): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  448): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 412us total 24.867ms,
,D/Process (  970): killProcessQuiet, pid=4711
I/ActivityManager(  970): Killing 4711:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17,
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/MultiDex( 5081): VM with version 2.1.0 has multidex support
I/MultiDex( 5081): install
I/MultiDex( 5081): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  970): Recipient 4711,
,D/Finsky  ( 5040): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 5040): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5040): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,D/MediaProvider( 3650): [update][16]#1#
D/PackageBroadcastService( 4228): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/MediaScanner( 3650):  prescan time: 368ms
D/MediaScanner( 3650):     scan time: 2224ms
D/MediaScanner( 3650): postscan time: 5ms
D/MediaScanner( 3650):    total time: 2597ms
D/MediaScanner( 3650): -----------------------------------------------------------------
D/MediaScanner( 3650): firstscan(media) time: 1093ms
D/MediaScanner( 3650): secondscan(non-media) time: 1131ms
D/MediaScanner( 3650):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3650):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3650):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3650):  [Total]    File(Image+Video+Audio+Others) in database : 1546
D/ChimeraCfgMgr( 4228): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4228): Loading module APK com.google.android.play.games
,V/JNIHelp ( 5081): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PMS     (  970): acquireWL(1fe97515): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4228 10024 null
,D/Finsky  ( 5040): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,W/ActivityThread( 5081): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5081): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d45c2b1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5081): Installed default security provider GmsCore_OpenSSL
,D/MediaProvider( 3650): [delete][89]
,D/MediaProvider( 3650): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3650): [recoverParentNodes] - 0
,D/MediaProvider( 3650): [update][15]
D/MediaScannerServiceEx( 3650): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3650): [updateImage]+
,D/MediaScannerServiceEx( 3650): [updateImage]-0,
D/PMS     (  970): releaseWL(32bf971f): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 3650): [1] scan finished
,D/MediaProviderUtils( 3650): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3650): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3650): calcVolumeId: /storage/usb
,D/MediaScannerServiceEx( 3650): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3650): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 3650): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3650): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted,
D/MediaProvider( 3650): [update][16]#1#
,D/MediaProvider( 3650): [update][32]#0#,
,D/MediaScannerServiceEx( 3650): [disAliveExtStorageRows]--1, 0
,D/MediaProviderUtils( 3650): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3650): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3650): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3650): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3650): Process mounted intent for unmounted storage: /storage/usb
,D/MediaScannerServiceEx( 3650): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3650): [sendStorageAddedIfNeed]: /storage/usb : unmounted,
,D/MediaProvider( 3650): [update][5]#1#
,D/MediaProvider( 3650): [update][28]#0#
,D/MediaScannerServiceEx( 3650): [disAliveExtStorageRows]--1, 0
,I/ConfigFetchService( 4228): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  970): acquireWL(38b7b64): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4228 10024 WorkSource{10373 com.example.hello}
I/ConfigFetchService( 4228): launchTask
,D/PMS     (  970): releaseWL(1fe97515): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/ChimeraCfgMgr( 4228): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PMS     (  970): acquireWL(155431cd): PARTIAL_WAKE_LOCK  Icing 0x1 4228 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraModuleLdr( 4228): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4228): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/ConfigFetchTask( 4228): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1U_Vm09PQXBI7xeLsfvfugZgnIAEbBTTpvkI3KjWuig-spo3EAIzBX-fZFzmoTBSLe7ZzKcOCsAAsBube7CCKMIFKSdclADtl1IDDiYZC8MT96uWYunyqVRLTS2xeQG1aJacWQOBIhL2Ki5nV7QYwqzK5ATJa1sNlc3YzJio_eCUjCsgTIxcYyS8AQgd4VdEVQ4eT-t
,I/GoogleURLConnFactory( 4228): Using platform SSLCertificateSocketFactory
,I/PeopleContactsSync( 4228): CP2 sync disabled
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4228, uid=10024, userID:0
,D/Vision  ( 4228): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 4228): Failed to find package metadata for com.example.hello
D/Vision  ( 4228): No vision deps
,I/ActivityManager(  970): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5119 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,D/Process (  970): killProcessQuiet, pid=4738
I/ActivityManager(  970): Killing 4738:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    ( 4228): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4228): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4228): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4228): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4228): [NET] android_getaddrinfo_proxy+
D/libc    ( 4228): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4228): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4228): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 4228): fetch service done; releasing wakelock
,D/PMS     (  970): releaseWL(38b7b64): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10373 com.example.hello}
I/ConfigFetchService( 4228): stopping self
,I/ActivityManager(  970): Recipient 4738,
,V/AlarmManager(  970): sending alarm PendingIntent{2552cd85: PendingIntentRecord{18be37da com.android.vending startService}}, i=null, t=0, cnt=1, w=1449498976796, Int=0
,I/Icing   ( 4228): Storage manager: low false usage 1.98MB avail 5.80GB capacity 7.95GB
,D/Finsky  ( 5040): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/BaseAppContext( 4228): Using Auth Proxy for data requests.
,W/BaseAppContext( 4228): Using Auth Proxy for data requests.
,W/Icing   ( 4228): Received bad json for section weights override -- ignoring.,
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Finsky  ( 5040): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/BaseAppContext( 4228): Using Auth Proxy for data requests.
W/Icing   ( 4228): Received bad json for corpus context scoring override -- ignoring.,
W/Icing   ( 4228): Received bad json for section weights override -- ignoring.
W/Icing   ( 4228): Received bad json for corpus context scoring override -- ignoring.
V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4228): Using Auth Proxy for data requests.
,W/Finsky  ( 5040): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/BaseAppContext( 4228): Using Auth Proxy for data requests.
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/BaseAppContext( 4228): Using Auth Proxy for data requests.,
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 5040): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,E/Icing   ( 4228): Loading extension by file descriptor -1 failed
,E/AndroidHttpClient( 5040): Leak found
E/AndroidHttpClient( 5040): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5040): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5040): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5040): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5040): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5040): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5040): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5040): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5040): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5040): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5040): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5040): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5040): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5040): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5040): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5040): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5040): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/Icing   ( 4228): updateResources: need to parse f{com.google.android.gms}
,I/SocialFeedProvider( 1519): +disConnect socialManager,
I/SocialFeedProvider( 1519): disconnect socialManager
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4228, uid=10024, userID:0
,I/ActivityManager(  970): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5153 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,V/AlarmManager(  970): sending alarm PendingIntent{27153548: PendingIntentRecord{17f3cfe1 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1449498977443, Int=0
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4228, uid=10024, userID:0
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4228, uid=10024, userID:0
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4228, uid=10024, userID:0
,D/ChimeraCfgMgr( 4228): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4228): Module APK com.google.android.play.games already loaded
,I/art     (  970): Explicit concurrent mark sweep GC freed 26234(1229KB) AllocSpace objects, 3(380KB) LOS objects, 33% free, 16MB/24MB, paused 1.584ms total 176.548ms
I/SocialFeedProvider( 1519): -disConnect socialManager
,D/AccTypeManager( 1672): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,D/AccTypeManager( 1672): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader(  970): Cannot find grip_rejection_width, use default value instead
,W/Prism.AllAppsManager( 1519): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1519): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1519): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1672): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/ResourcesManager(  970): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Launcher( 1519): Deferring update until onResume
,D/Launcher( 1519): waitUntilResume // bindAppsUpdated
,D/PMS     (  970): releaseWL(2a2ff6e9): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
E/ExternalAccountType( 1672): Unsupported attribute readOnly
D/PhoneApp( 1461): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Icing   ( 4228): Internal init done: storage state 0
,I/ImageRamCache( 5153): create image Cache, size: 31457280.
I/ImageRamCache( 5153): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5153): create image Cache, size: 31457280.
,I/FeedSettings( 5153): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 5153): GroupBudget 0.500000 0.380000
I/FeedSettings( 5153): GroupBudget 60 45 15
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Prism.ExternalStringMa_( 5153): changeLocale(): en_GB
,I/Icing   ( 4228): Post-init done
,I/Prism.AllAppsOptionsMa_( 5153): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 5153): loadGridSize() with Alternative
,D/PMS     (  970): releaseWL(155431cd): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/GAv4    ( 5119): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5119):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5119):   adb logcat -s GAv4
,W/PackageManager(  970): Unable to load service info ResolveInfo{31f93c6d com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  970): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  970): ,	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  970): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  970): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  970): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  970): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029),
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/SocialManager[SocialBiLogHelper]( 5153): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 5153): last commit ulog time 1449470898364
I/SocialManager[SocialBiLogHelper]( 5153): skip commit this time
,W/GAv4    ( 5119): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 5119): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5119): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/AnalyticsTrackerProxyImpl( 5119): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,I/BackupManagerService(  970): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/GmsNetworkLocationProvi( 1805): DISABLE
,I/GCoreNlp( 1805): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 5040): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 5040): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/LocationProviderProxy(  970): applying state to connected service
,D/Finsky  ( 5040): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/PMS     (  970): acquireWL(15a5bac5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1805 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(15a5bac5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/Finsky  ( 5040): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/LocationProviderProxy(  970): applying state to connected service
,D/PMS     (  970): acquireWL(2fd6bc1a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1805 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(21da334b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1805 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(2fd6bc1a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(21da334b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/Process (  970): killProcessQuiet, pid=3721
I/ActivityManager(  970): Killing 3721:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/PMS     (  970): acquireWL(1c8ae128): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1805 10024 WorkSource{10024 com.google.android.gms}
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/DeviceConnectionService( 1805): client connected with version: 7571000
,D/PMS     (  970): releaseWL(1c8ae128): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  970): Recipient 3721
,I/ActivityManager(  970): Killing 4775:com.htc.mobiledata:remote/u0a46 (adj 15): empty #18
D/Process (  970): killProcessQuiet, pid=4775
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 4775,
,D/VoldConnector(  970): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
,W/ContextImpl( 5119): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,I/ActivityManager(  970): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5200 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Process (  970): killProcessQuiet, pid=4825
I/ActivityManager(  970): Killing 4825:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
W/ResourcesManager( 5119): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5119): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1872): Explicit concurrent mark sweep GC freed 14838(830KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 901us total 86.932ms,
,I/ActivityManager(  970): Recipient 4825,
,W/ResourcesManager( 5200): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,V/JNIHelp ( 5119): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 5119): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5119): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  970): disable(): mBluetooth = null mBinding = false
W/Settings:Agent(  970): MONITOR_LOG
W/Settings:Agent(  970): name: bluetooth_on
W/Settings:Agent(  970): value: 0
W/Settings:Agent(  970): >> traceCallingStack()
W/Settings:Agent(  970): Process.myPid(): 970
W/Settings:Agent(  970): Process.myTid(): 990
W/Settings:Agent(  970): Process.myUid(): 1000,
W/Settings:Agent(  970): 
W/Settings:Agent(  970): 
,W/System.err(  970): java.lang.Throwable: stack dump
,W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  970): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  970): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  970): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  970): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  970): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  970): 
W/Settings:Agent(  970): << traceCallingStack(): 11(ms)
,D/BluetoothManagerService(  970): Message: MESSAGE_DISABLE
,D/WifiService(  970): New client listening to asynchronous messages,
E/WifiTrafficPoller(  970): ADD_CLIENT: 7
D/WifiManager( 4671): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
,D/PMS     (  970): acquireWL(37e65fca): PARTIAL_WAKE_LOCK  AsyncService 0x1 5200 10167 null
,D/PMS     (  970): acquireWL(8cce458): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5200 10167 null,
,D/WifiService(  970): setWifiEnabled: false pid=4671, uid=10373
E/WifiService(  970): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings:Agent(  970): MONITOR_LOG
I/WifiService(  970): isSprintWifiRestricted(): false
W/Settings:Agent(  970): name: wifi_on
I/WifiService(  970): isMdmWifiRestricted(): false
W/Settings:Agent(  970): value: 0
D/PMS     (  970): releaseWL(37e65fca): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/Settings:Agent(  970): >> traceCallingStack()
W/Settings:Agent(  970): Process.myPid(): 970
W/Settings:Agent(  970): Process.myTid(): 1558
W/Settings:Agent(  970): Process.myUid(): 1000
W/Settings:Agent(  970): 
W/Settings:Agent(  970): 
W/System.err(  970): java.lang.Throwable: stack dump
,W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  970): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
,W/System.err(  970): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  970): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  970): 	at android.provider.Settings$Global.putString(Settings.java:7403)
,W/System.err(  970): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  970): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  970): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  970): ,	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  970): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
,W/Settings:Agent(  970): 
W/Settings:Agent(  970): << traceCallingStack(): 7(ms)
,D/WifiController(  970): handleMessage: E msg.what=155656
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): handleMessage: X
I/jxcore-log( 4671): ****TEST TOOK:  5095  ms ****
I/jxcore-log( 4671): 
,I/jxcore-log( 4671): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4671): 
,D/PMS     (  970): releaseWL(8cce458): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/ActivityManager(  970): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5235 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
I/ActivityManager(  970): Killing 4327:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=4327
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/Prism.ItemManager( 1519): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1519): loadItems() com.htc.launcher.pageview.WidgetManager@2eafbdb9 +
I/Prism.WidgetManager( 1519): onLoadItems() +
,I/ActivityManager(  970): Recipient 4327
,W/ResourcesManager( 1519): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/PMS     (  970): acquireWL(20f2ae96): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1872): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1872): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1872): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1872): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1872): [NET] android_getaddrinfo_proxy+
D/libc    ( 1872): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1872): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  970): releaseWL(20f2ae96): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  970): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5262 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a,
,W/ResourcesManager( 5262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/cutils-trace( 5248): Error opening trace file: Permission denied (13)
,D/LocationManagerService(  970): getProviders()=[passive]
,D/CustomizationManager( 5248): ====startRecUseTime====,
D/htc.customization.log.level( 5248):  is 
W/CustomizationLogLevel( 5248): Level value is invalid, use default level 2,
,W/ResourcesManager( 1519): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/UpdateIcingCorporaServi( 5235): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/CustomizationManager( 5248):  Read ACC file spent 0.041 (s),
,D/CIDMapFileReader( 5248): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5248): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5248): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5248): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5248): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5248): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5248): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 5248): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5248): Parsing tag category name = system
,I/CustomizationCIDLoader( 5248): Parsing tag category name = application
,I/CustomizationCIDLoader( 5248): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5248): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5248): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5248): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5248): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 5248): add string-array item, value = 42507,
I/CustomizationCIDLoader( 5248): add string-array item, value = 21902
I/CustomizationCIDLoader( 5248): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5248): add string-array item, value = 23420
I/CustomizationCIDLoader( 5248): add string-array item, value = 22299
,I/CustomizationCIDLoader( 5248): add string-array item, value = 24002
I/CustomizationCIDLoader( 5248): add string-array item, value = 23210
,I/CustomizationCIDLoader( 5248): add string-array item, value = 23205
I/CustomizationCIDLoader( 5248): add string-array item, value = 23806
I/CustomizationCIDLoader( 5248): add string-array item, value = 23430
I/CustomizationCIDLoader( 5248): add string-array item, value = 23408
I/CustomizationCIDLoader( 5248): add string-array item, value = 27205
I/CustomizationCIDLoader( 5248): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5248): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5248): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5248): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5248): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5248): add string-array item, value = 24002:D:0:0
,I/CustomizationCIDLoader( 5248): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5248): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5248): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5248): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5248): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5248): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5248):  Read CID file spent 0.088 (s)
D/CustomizationManager( 5248):  All configurations done spent 0.088 (s)
,D/PackageManager(  970): deletePackageAsUser: pkg=com.example.hello, pid=5248, uid=2000 userid=0
,I/ActivityManager(  970): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5308 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  970): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
,I/ActivityManager(  970): Killing 4671:com.example.hello/u0a373 (adj 0): stop com.example.hello
D/Process (  970): killProcessQuiet, pid=4671
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,D/PMS     (  970): acquireWL(33f8fa6e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
,W/asset   ( 5235): Copying FileAsset 0x55b8407a70 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/UpdateIcingCorporaServi( 5235): UpdateCorporaTask done [took 144 ms] updated apps [took 144 ms] ,
D/PhoneApp( 1461): EVENT_QUERY_MO_PACKAGES
,W/PackageSettings(  970): Skipping PackageSetting{15db4336 com.test.thalitest/10366} due to missing metadata
,D/PhoneApp( 1461): -- N1 =0
,I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(33f8fa6e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PhoneApp( 1461): -- N2 =0
,D/PhoneApp( 1461): -- N3 =0
,W/asset   ( 1519): Copying FileAsset 0x55b86ee590 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/ActivityManager(  970): Recipient 4671
I/WindowState(  970): WIN DEATH: Window{2b85c009 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  970): Client connection lost with reason: 4
,E/InputEventReceiver( 1349): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{186bb20e uid 10373 pid 4671} (c)'
,E/Prism.WidgetManager( 1519): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1519): onLoadItems() -
I/Prism.ItemManager( 1519): loadItems() com.htc.launcher.pageview.WidgetManager@2eafbdb9 -
,W/ActivityManager(  970): Force removing ActivityRecord{2375ee4d u0 com.example.hello/.MainActivity t8}: app died, no saved state,
,W/ActivityManager(  970): Spurious death for ProcessRecord{30be4f7a 4671:com.example.hello/u0a373}, curProc for 4671: null,
I/ActivityManager(  970): Force stopping com.example.hello appid=10373 user=0: pkg removed
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  970): battery changed pluggedType: 2
D/DotMatrix( 1304): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/PMS     (  970): acquireWL(2f9b332b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1805 10024 WorkSource{10024 com.google.android.gms}
W/SystemReader(  970): Cannot find grip_rejection_width, use default value instead
,D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/FeedHostManager( 1519): [onResume]
I/FeedProviderManager( 1519): onResume
I/SocialFeedProvider( 1519): +onResume
I/SocialFeedProvider( 1519): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1519): -onResume
W/GeofencerStateMachine( 1805): Ignoring removeGeofence because network location is disabled.
,I/ConnectivityHelper( 1519): [getCurrentConnectionType] no network connection
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  970): releaseWL(2f9b332b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  970): Killing 4803:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=4803
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/Prism.ItemManager( 5153): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1672): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/Prism.ItemManager( 5153): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,E/SQLiteLog( 5262): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal,
,D/AccTypeManager( 1672): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/PackageManager(  970): Unable to load service info ResolveInfo{1566a359 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  970): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  970): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  970): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  970): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  970): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
,W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/InputMethodManagerService(  970): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/AccTypeManager( 1672): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1461): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/JobSchedulerService(  970): Receieved: android.intent.action.PACKAGE_REMOVED
,E/ExternalAccountType( 1672): Unsupported attribute readOnly
,I/ActivityManager(  970): Recipient 4803
,I/art     (  970): Explicit concurrent mark sweep GC freed 30584(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 1.544ms total 211.791ms,
,I/MusicStore( 5308): Database version: 120,
,D/PMS     (  970): runPSCheck
D/HtcPowerSaver(  970): Checking...,
I/HtcPowerSaver(  970): >> updateStatus
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus,
,D/TaskPersister(  970): removeObsoleteFile: deleting file=8_task.xml,
,D/StatusBarManagerService(  970): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  970): hiding MENU key
D/FindExtension( 1519): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1519): Defer allocateBuffers to drawing time
,I/Prism.ItemManager( 1519): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1519): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/InputMethodManagerService(  970): Got RemoteException sending setActive(false) notification to pid 4671 uid 10373
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  970): Enable input method client, pid=1519
,D/StatusBarManagerService(  970): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  970): hiding MENU key
,D/VoldConnector(  970): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5308): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  970): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 5308): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  970): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5308): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 5308): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5308): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5308): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/HtcModeClient( 3156): handler message = 4011,
,E/HtcModeClient( 3156): Check connection and retry 5 times.
,W/ActivityThread( 5308): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5308): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f07f593: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 5308): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5308): GMSCore installation verified
,I/ConfigStore( 5308): Config Database version: 1,
,E/SQLiteDatabase( 5308): Failed to open database '/data/data/com.google.android.music/databases/config.db'.,
E/SQLiteDatabase( 5308): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5308): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
,E/SQLiteDatabase( 5308): 	at com.google.android.music.store.ConfigStore.getDatabase(ConfigStore.java:64)
E/SQLiteDatabase( 5308): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 5308): 	at com.google.android.music.store.ConfigContentProvider.query(ConfigContentProvider.java:129)
E/SQLiteDatabase( 5308): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5308): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5308): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5308): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5308): 	at com.google.android.music.utils.ConfigCache.get(ConfigCache.java:136)
E/SQLiteDatabase( 5308): 	at com.google.android.music.utils.ConfigUtils.getString(ConfigUtils.java:673)
E/SQLiteDatabase( 5308): 	at com.google.android.music.utils.ConfigUtils.getBoolean(ConfigUtils.java:709)
E/SQLiteDatabase( 5308): 	at com.google.android.music.utils.ConfigUtils.isPlayLoggingEnabled(ConfigUtils.java:399)
E/SQLiteDatabase( 5308): 	at com.google.android.music.eventlog.MusicEventLogger.<init>(MusicEventLogger.java:152)
E/SQLiteDatabase( 5308): 	at com.google.android.music.eventlog.MusicEventLogger.getInstance(MusicEventLogger.java:270),
E/SQLiteDatabase( 5308): 	at com.google.android.music.MusicApplication.onCreate(MusicApplication.java:87)
E/SQLiteDatabase( 5308): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/SQLiteDatabase( 5308): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/SQLiteDatabase( 5308): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 5308): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 5308): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5308): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5308): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
,E/SQLiteDatabase( 5308): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5308): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5308): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 5308): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/AndroidRuntime( 5308): FATAL EXCEPTION: main,
E/AndroidRuntime( 5308): Process: com.google.android.music:main, PID: 5308
E/AndroidRuntime( 5308): java.lang.RuntimeException: Unable to create application com.google.android.music.MusicApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5308): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4954)
E/AndroidRuntime( 5308): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 5308): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 5308): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5308): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5308): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 5308): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5308): 	,at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5308): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 5308): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 5308): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5308): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/AndroidRuntime( 5308): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5308): 	at com.google.android.music.store.ConfigStore.getDatabase(ConfigStore.java:64),
E/AndroidRuntime( 5308): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 5308): 	at com.google.android.music.store.ConfigContentProvider.query(ConfigContentProvider.java:129)
E/AndroidRuntime( 5308): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/AndroidRuntime( 5308): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/AndroidRuntime( 5308): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/AndroidRuntime( 5308): 	at android.content.ContentResolver.query(ContentResolver.java:435),
E/AndroidRuntime( 5308): 	at com.google.android.music.utils.ConfigCache.get(ConfigCache.java:136)
E/AndroidRuntime( 5308): 	at com.google.android.music.utils.ConfigUtils.getString(ConfigUtils.java:673)
E/AndroidRuntime( 5308): 	at com.google.android.music.utils.ConfigUtils.getBoolean(ConfigUtils.java:709)
E/AndroidRuntime( 5308): 	at com.google.android.music.utils.ConfigUtils.isPlayLoggingEnabled(ConfigUtils.java:399)
E/AndroidRuntime( 5308): 	at com.google.android.music.eventlog.MusicEventLogger.<init>(MusicEventLogger.java:152),
E/AndroidRuntime( 5308): 	at com.google.android.music.eventlog.MusicEventLogger.getInstance(MusicEventLogger.java:270)
E/AndroidRuntime( 5308): 	at com.google.android.music.MusicApplication.onCreate(MusicApplication.java:87)
E/AndroidRuntime( 5308): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidRuntime( 5308): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidRuntime( 5308): 	... 9 more
,E/ActivityManager(  970): App crashed! Process: com.google.android.music:main
,E/DropBoxManagerService(  970): Can't write: system_app_crash,
E/DropBoxManagerService(  970): java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  970): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  970): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  970): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  970): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  970): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  970): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  970): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  970): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  970): 	... 5 more
,W/OpenGLRenderer( 1519): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,D/StatusBarManagerService(  970): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
,D/Process (  970): killProcessQuiet, pid=4864,
I/ActivityManager(  970): Killing 4864:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 4864
D/WifiService(  970): Client connection lost with reason: 4
,I/Prism.ItemManager( 5153): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 5153): loadItems() com.htc.launcher.pageview.WidgetManager@19a67c47 +
I/Prism.WidgetManager( 5153): onLoadItems() +
,W/ResourcesManager( 5153): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.

```
