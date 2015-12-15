#### Test 5038801913f4183_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
I/art     (  935): Explicit concurrent mark sweep GC freed 10524(514KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.363ms total 129.273ms
D/LocationInitializer( 4467): Restart initialization of location
--------- beginning of system
I/ActivityManager(  935): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4856 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 100
D/AccFlag ( 1564): sku_id=118
V/JNIHelp ( 4827): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 55
D/AccFlag ( 1564): sku_id=118
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 54
D/AccFlag ( 1564): sku_id=118
W/ActivityThread( 4827): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4827): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e7cbd3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4827): Installed default security provider GmsCore_OpenSSL
D/WearableService( 4827): callingUid 10024, callindPid: 4827
E/MDM     ( 1800): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/libc    ( 4801): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 4801): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4801): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4801): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4801): [NET] android_getaddrinfo_proxy+
D/libc    ( 4801): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
I/ImageRamCache( 4856): create image Cache, size: 31457280.
I/ImageRamCache( 4856): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4856): create image Cache, size: 31457280.
I/GLSUser ( 1845): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1845): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1845): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1845): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/FeedSettings( 4856): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4856): GroupBudget 0.500000 0.380000
I/FeedSettings( 4856): GroupBudget 60 45 15
V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Prism.ExternalStringMa_( 4856): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 4856): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 4856): loadGridSize() with Alternative
D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4801): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4801): [NET] android_getaddrinfofornet+,hn 13(0x32332e35392e31),sn(),hints(known),family 0,flags 4
D/libc    ( 4801): [NET] android_getaddrinfofornet-, SUCCESS
D/DotMatrix( 1334): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1334): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/CustomHighlightReceiver( 4856): [custom highlight] onReceive
I/RemoteViews( 1216): reapply : com.google.android.gms 2 40
D/CustomHighlightService( 4856): [custom highlight] onHandleIntent
W/Search.LoginHelper( 4731): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4731): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4731): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4731): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4731): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4731): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4731): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4731): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4731): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4731): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4731): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4731): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4731): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4731): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4731): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4731): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4731): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4731): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/VelvetNetworkClient( 4731): Failed to get auth token
D/NewsDB  ( 4856): set custom highlight []
I/ActivityManager(  935): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4892 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/CustomHighlightService( 4856): [custom highlight] set tags 
D/Process (  935): killProcessQuiet, pid=4213
I/ActivityManager(  935): Killing 4213:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/cutils-trace( 4884): Error opening trace file: Permission denied (13)
I/ActivityManager(  935): Recipient 4213
D/CustomizationManager( 4884): ====startRecUseTime====
D/htc.customization.log.level( 4884):  is 
W/CustomizationLogLevel( 4884): Level value is invalid, use default level 2
D/CustomizationManager( 4884):  Read ACC file spent 0.071 (s)
D/CIDMapFileReader( 4884): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4884): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4884): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4884): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4884): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4884): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4884): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4884): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4884): Parsing tag category name = system
I/CustomizationCIDLoader( 4884): Parsing tag category name = application
I/CustomizationCIDLoader( 4884): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4884): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4884): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4884): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4884): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4884): add string-array item, value = 42507
I/CustomizationCIDLoader( 4884): add string-array item, value = 21902
I/CustomizationCIDLoader( 4884): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4884): add string-array item, value = 23420
I/CustomizationCIDLoader( 4884): add string-array item, value = 22299
I/CustomizationCIDLoader( 4884): add string-array item, value = 24002
I/CustomizationCIDLoader( 4884): add string-array item, value = 23210
I/CustomizationCIDLoader( 4884): add string-array item, value = 23205
I/CustomizationCIDLoader( 4884): add string-array item, value = 23806
I/CustomizationCIDLoader( 4884): add string-array item, value = 23430
I/CustomizationCIDLoader( 4884): add string-array item, value = 23408
I/CustomizationCIDLoader( 4884): add string-array item, value = 27205
I/CustomizationCIDLoader( 4884): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4884): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4884): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4884): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4884): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4884): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4884): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4884): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4884): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4884): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4884): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4884): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4884):  Read CID file spent 0.120 (s)
D/CustomizationManager( 4884):  All configurations done spent 0.120 (s)
I/ActivityManager(  935): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4884 on display 0
D/PMS     (  935): acquireHCC(8da68df): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 935 1000 null
W/asset   (  935): Copying FileAsset 0x5595851480 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  935): acquireHCC(c6cc92c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 935 1000 null
D/PMS     (  935): acquireWL(e26b3fb): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 935 1000 null
I/FeedHostManager( 1627): [onPause]
I/FeedProviderManager( 1627): onPause
I/FeedHostManager( 1627): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2aa2039
I/SocialFeedProvider( 1627): +onPause
I/SocialFeedProvider( 1627): -onPause
W/HtcSystemUPManager(  935): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
E/WifiTrafficPoller(  935): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1216): WifiActivity: 3
E/WifiTrafficPoller(  935):  packet count Tx=76 Rx=135
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  935): notifying of data activity 3
I/AnimationUtil(  935): isHTCRecent(HelloWorld/Recent screens.)/4
I/ActivityManager(  935): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4929 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/asset   ( 4929): Copying FileAsset 0xab313ec0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/StatusBarManagerService(  935): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  935): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  935): hiding MENU key
I/TrimMemoryManager( 1627): [trimMemory] 20
I/MusicStore( 4892): Database version: 120
I/WebViewFactory( 4929): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 4929): Time to load native libraries: 11 ms (timestamps 8232-8243)
I/LibraryLoader( 4929): Expected native library version number "",actual native library version number ""
D/VoldConnector(  935): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4892): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
V/WebViewChromiumFactoryProvider( 4929): Binding Chromium to main looper Looper (main, tid 1) {294ef826}
I/LibraryLoader( 4929): Expected native library version number "",actual native library version number ""
I/chromium( 4929): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/PMS     (  935): releaseWL(34ff356e): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
I/BrowserStartupController( 4929): Initializing chromium process, singleProcess=true
W/art     ( 4929): Attempt to remove local handle scope entry from IRT, ignoring
D/ContactMessageStore( 1564): MSG_NOTIFY_CS_TO_SYNC >>
E/SysUtils( 4929): ApplicationContext is null in ApplicationStatus
D/ContactMessageStore( 1564): MSG_NOTIFY_CS_TO_SYNC <<
D/VoldConnector(  935): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4892): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/VoldConnector(  935): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4892): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/ResourcesManager( 4892): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4892): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/chromium( 4929): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4929): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4929): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4929): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4929): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4929): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4929): Local Branch: 
I/Adreno-EGL( 4929): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4929): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4929):                  d74aa161a12b9c6fc6332151
V/JNIHelp ( 4892): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/System.err(  935): java.lang.Throwable: stack dump
D/BluetoothManagerService(  935): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  935): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@177dc2bf:true
W/System.err(  935): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  935): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  935): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  935): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 4929): 648179890: getState(). Returning 12
W/ActivityThread( 4892): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4892): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1daad6a5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4892): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4892): GMSCore installation verified
I/ConfigStore( 4892): Config Database version: 1
W/art     ( 4929): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4929): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 4929): CordovaWebView is running on device made by: HTC
W/art     ( 4929): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4929): Attempt to remove local handle scope entry from IRT, ignoring
I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4892, uid=10159, userID:0
D/WifiDisplayAdapter(  935): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  935):     Client/Owner: Client
D/WifiDisplayAdapter(  935):     GroupId: 
D/WifiDisplayAdapter(  935):     Passphrase: 
D/WifiDisplayAdapter(  935):     SessionId: 0
D/WifiDisplayAdapter(  935):     IP Address: }
D/MediaRouterService(  935): Client com.google.android.music (pid 4892): Registered
D/WifiDisplayAdapter(  935): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  935):     Client/Owner: Client
D/WifiDisplayAdapter(  935):     GroupId: 
D/WifiDisplayAdapter(  935):     Passphrase: 
D/WifiDisplayAdapter(  935):     SessionId: 0
D/WifiDisplayAdapter(  935):     IP Address: }
I/MediaRouter( 4892): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 4892): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 4892): type=WIFI subType= reason=null isConnected=true
W/chromium( 4929): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 4929): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/NetworkMonitor( 4892): type=WIFI subType= reason=null isConnected=true
I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4892, uid=10159, userID:0
I/ActivityManager(  935): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4990 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
I/art     (  406): Explicit concurrent mark sweep GC freed 8674(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 161us total 28.450ms
I/GHttpClientFactory( 4892): Using our fixed implementation of GMSCore's GoogleHttpClient
I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 146us total 17.605ms
I/GoogleURLConnFactory( 4892): Using platform SSLCertificateSocketFactory
I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 171us total 18.840ms
W/ResourcesManager( 4990): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/InputMethodManager( 4929): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@88757f3, mServedView=org.apache.cordova.engine.SystemWebView{175eacb0 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@c0d5729
I/InputMethodManagerService(  935): Disable input method client, pid=1627
D/StatusBarManagerService(  935): swetImeWindowStatus vis=0 backDisposition=0
D/Process (  935): killProcessQuiet, pid=4244
I/ActivityManager(  935): Killing 4244:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/InputMethodManagerService(  935): Enable input method client, pid=4929
I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
W/XT9_C   ( 1400): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1400): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1400): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1400): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
E/WifiDataStallTracker(  935): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  935): updateDataStallInfo: mDataStallTxRxSum={txSum=62 rxSum=63} preTxRxSum={txSum=22 rxSum=16}
D/WifiDataStallTracker(  935): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  935): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
W/BindingManager( 4929): Cannot call determinedVisibility() - never saw a connection for the pid: 4929
I/ActivityManager(  935): Recipient 4244
I/chromium( 4929): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/PMS     (  935): releaseWL(e26b3fb): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/CalendarProvider2( 4990): Created com.android.providers.calendar.CalendarAlarmManager@2de06f81(com.htc.providers.calendar.HtcCalendarProvider@294ef826)
I/ActivityManager(  935): Displayed com.example.hello/.MainActivity: +963ms
D/CalendarProvider2( 4990): wait start:true
E/WifiTrafficPoller(  935): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  935):  packet count Tx=76 Rx=137
E/WifiTrafficPoller(  935): notifying of data activity 1
D/WIFI_ICON( 1216): WifiActivity: 1
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/CalendarProvider2( 4990): wait end:false
D/AutoSetting( 1538): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/JsMessageQueue( 4929): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  935): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5024 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
D/AutoSetting( 1538): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1538): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1538): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1538): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1538): service - handleMessage() setting current location null
E/AndroidProtocolHandler( 4929): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/Process (  935): killProcessQuiet, pid=4315
I/ActivityManager(  935): Killing 4315:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PhoneMonitor( 5024): Register our PhoneStateListener
I/ActivityManager(  935): Recipient 4315
D/jxcore_app_log( 4929): JniHelper::setJavaVM(0xab2818f8), pthread_self() = -1403215504
D/JX-Cordova( 4929): jxcore cordova android initializing
D/MobileConnectivityChangeReceiver( 5024): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5024): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  935): Killing 4337:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  935): killProcessQuiet, pid=4337
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/PhoneMonitor( 5024): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/PhoneMonitor( 5024): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/jxcore-log( 4929): Initializing JXcore engine
W/jxcore-log( 4929): JXcore engine is ready
W/jxcore-log( 4929): Starting JXcore engine
W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 4
I/ActivityManager(  935): Recipient 4337
W/jxcore-log( 4929): Platform android
W/jxcore-log( 4929): 
W/jxcore-log( 4929): Process ARCH arm
W/jxcore-log( 4929): 
I/jxcore-log( 4929): JXcore Cordova bridge is ready!
I/jxcore-log( 4929): 
W/jxcore-log( 4929): JXcore engine is started
D/PMS     (  935): acquireWL(39b29950): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4467 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  935): acquireWL(12f7184e): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4467 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  935): releaseWL(39b29950): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
I/CheckinService( 4467): Checking schedule, now: 1450199018157 next: 1450197016109
I/CheckinService( 4467): active receiver: enabled
I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4467, uid=10024, userID:0
E/jxcore-log( 4929): >> HTC-HTC One M8s
E/jxcore-log( 4929): 
I/jxcore-log( 4929): Total memory 1931808768
I/jxcore-log( 4929): 
I/jxcore-log( 4929): Free memory 86368256
I/jxcore-log( 4929): 
I/jxcore-log( 4929): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4929): 
I/jxcore-log( 4929): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4929): 
I/CheckinService( 4467): Preparing to send checkin request
I/EventLogService( 4467): Accumulating logs since 1450198753667
I/jxcore-log( 4929): userPath [ 'www' ]
I/jxcore-log( 4929): 
I/jxcore-log( 4929): Size 1080 1776
I/jxcore-log( 4929): 
I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4467, uid=10024, userID:0
I/jxcore-log( 4929): Screen Brightness 142
I/jxcore-log( 4929): 
E/jxcore-log( 4929): Dummy Error Log.
E/jxcore-log( 4929): 
I/ActivityManager(  935): Waited long enough for: ServiceRecord{2625d60f u0 com.htc.HTCSpeaker/.NGFService}
I/iu.SyncManager( 4467): SYNC; picasa accounts
D/NetworkLogImpl( 4467): Loaded NetworkSpeedPredictor
I/iu.Environment( 4467): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 4467): num queued entries: 0
I/iu.UploadsManager( 4467): num updated entries: 0
I/iu.SyncManager( 4467): NEXT; no task
D/ChimeraCfgMgr( 4467): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 4467): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/ActivityManager(  935): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5055 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/libc    ( 4569): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4569): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4569): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4569): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4569): [NET] android_getaddrinfo_proxy+
D/libc    ( 4569): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
I/CheckinRequestBuilder( 4467): Checkin reason type: 8 attempt count: 1
E/WifiTrafficPoller(  935): ADD_CLIENT: 7
D/WifiService(  935): New client listening to asynchronous messages
I/ActivityManager(  935): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4467): Failed to find provider info for com.google.android.wearable.settings
I/GLSUser ( 1845): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1845): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1845): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1845): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4569): [NET] android_getaddrinfo_proxy-, success
I/Babel   ( 4569): connection state changed from UNKNOWN to CONNECTED
I/art     (  935): Explicit concurrent mark sweep GC freed 11605(610KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/24MB, paused 1.498ms total 133.979ms
,W/Kids    ( 4467): [AccountUtils] Account not ready
W/Kids    ( 4467): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4467): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4467): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4467): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4467): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4467): 	at com.google.android.gms.kids.account.k.d(SourceFile:103),
W/Kids    ( 4467): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4467): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4467): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4467): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4467): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4467): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1334): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1334): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1216): reapply : com.google.android.gms 4 40
E/WifiStateMachine(  935): handleMessage: E msg.what=131155
E/WifiStateMachine(  935): processMsg: ConnectedState
,E/WifiStateMachine(  935):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=6.6, 0.0, 0.0  rx=11.2 bcn=0 [on:0 tx:0 rx:0 period:2949] from screen [on:0 period:-1499927536] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  935): processMsg: L2ConnectedState
E/WifiStateMachine(  935):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=6.6, 0.0, 0.0  rx=11.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1499927534] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  935):  get link layer stats 0
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1327): environment dirty rate=11 [36][4][0]
E/WifiStateMachine(  935): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  935): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  935): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  935): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=21.31 txretriesrate=0.00 rxrate=31.10 userTriggerdPenalty0
E/WifiStateMachine(  935):  good link -> stuck count =0
E/WifiStateMachine(  935):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  935):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  935): RSSI current: 3 new: -59, 3
,E/WifiStateMachine(  935): handleMessage: X
,D/WIFI_ICON( 1216): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/VoldConnector(  935): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 5055): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  935): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 5055): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files,
,I/GAv4    ( 5055): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5055):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5055):   adb logcat -s GAv4
,D/VoldConnector(  935): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 5055): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/VoldConnector(  935): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 5055): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 5055): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5055): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/PMS     (  935): releaseHCC(8da68df): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  935): releaseHCC(c6cc92c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/art     ( 4467): Explicit concurrent mark sweep GC freed 23670(1830KB) AllocSpace objects, 26(520KB) LOS objects, 47% free, 4MB/8MB, paused 1.439ms total 65.463ms,
I/CalendarProvider2( 4990): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4990): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/GAv4    ( 5055): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Process (  935): killProcessQuiet, pid=4362
I/ActivityManager(  935): Killing 4362:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/HtcModeClient( 3224): handler message = 4011
E/HtcModeClient( 3224): Check connection and retry 4 times.
,E/WifiTrafficPoller(  935): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  935):  packet count Tx=82 Rx=144,
E/WifiTrafficPoller(  935): notifying of data activity 3
D/WIFI_ICON( 1216): WifiActivity: 3
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/jxcore-log( 4929): getBuffer is called!!!!
I/jxcore-log( 4929): 
,I/ActivityManager(  935): Recipient 4362
,I/GLSUser ( 1845): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1845): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1845): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1845): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/CheckinRequestBuilder( 4467): awaiting user notification for token,
,D/DotMatrix( 1334): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1334): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1216): reapply : com.google.android.gms 2 40
,W/global  ( 5055): [apache-http] Connection GC has been deprecated!
,W/global  ( 5055): [apache-http] Connection GC has been deprecated!
,I/ActivityManager(  935): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5100 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 5100): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5100): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  935): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5122 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
V/AlarmManager(  935): sending alarm PendingIntent{229c716b: PendingIntentRecord{aed14c8 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=60251, Int=0
,I/MultiDex( 5100): VM with version 2.1.0 has multidex support
I/MultiDex( 5100): install
I/MultiDex( 5100): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5100): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/WebViewFactory( 5055): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,W/ActivityThread( 5100): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5100): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e7cbd3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 5100): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  935): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5147 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/LibraryLoader( 5055): Time to load native libraries: 44 ms (timestamps 445-489)
,I/LibraryLoader( 5055): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5055): Binding Chromium to main looper Looper (main, tid 1) {22f8c71a},
I/LibraryLoader( 5055): Expected native library version number "",actual native library version number ""
,I/chromium( 5055): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/MdScBoot( 5122): [805.1.] 30@-170308 -> 40
,D/MdScBootUi( 5122): [805.1.2.] boot 118
,D/MdScSimSt( 5122): [805.1.2.] qry 118: 0+1 running 0
,I/BrowserStartupController( 5055): Initializing chromium process, singleProcess=true
,W/art     ( 5055): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 5055): ApplicationContext is null in ApplicationStatus,
,I/WVCdm   (  399): CdmEngine::OpenSession
I/WVCdm   (  399): Level3 Library Sep 25 2014 17:10:03,
,W/WVCdm   (  399): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,D/DrmWidevineDash(  399): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
D/DrmWidevineDash(  399): Service_Initialize: starts!
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
E/QSEECOMAPI: (  399): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  399): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
,D/QSEECOMAPI: (  399): Loaded image: APP id = 6
,D/DrmWidevineDash(  399): Service_Initialize: ends! returns 0,
,D/QSAPPSVER(  399): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  399): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b85000,
E/DrmWidevineDash(  399): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b85000
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  491): got the req here! ret=0
D/DrmLibTime(  491): command id, time_cmd_id = 770
D/DrmLibTime(  491): time_getutcsec starts!
D/DrmLibTime(  491): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  491): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  491): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  491): QSEE Time Listener: Checking if ATS_MODEM is set or not.
,E/QC-time-services(  491): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  491): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  491): QSEE Time Listener: Retrieved Android system time: 1450199019
D/DrmLibTime(  491): time_getutcsec returns 0, sec = 1450199019; nsec = 0
D/DrmLibTime(  491): time_getutcsec finished! 
D/DrmLibTime(  491): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  491): before calling ioctl to read the next time_cmd
E/QC-time-services(  434): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/ActivityManager(  935): Killing 4385:com.android.smith/1000 (adj 15): empty #17
D/Process (  935): killProcessQuiet, pid=4385
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: ends! returns 0,
D/WVCdm   (  399): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: starts! SID=0xf4eae928
D/DrmWidevineDash(  399): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: ends! returns 0,
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: starts! randomData=0xaabec758, dataLength=8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaac02060, wrapped_rsa_key_length=1280,
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  399): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  399): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  399): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  399): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: starts! deviceID=0xaac05928, idLength=0xf4dae6f8,
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4dae70e, maximum = 0xf4dae70f
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9,
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4dae77c
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  399): PrepareKeyRequest: nonce=1985069867
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaac1a8a0
D/DrmWidevineDash(  399): message_length=1611, signature=0xaac134f0, signature_length=0xf4dae6dc
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
W/chromium( 5055): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5055): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5055): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5055): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5055): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5055): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5055): Local Branch: 
I/Adreno-EGL( 5055): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5055): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5055):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  935): Recipient 4385
,D/Process (  935): killProcessQuiet, pid=4294
,I/ActivityManager(  935): Killing 4294:com.android.settings/1000 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  399): CdmEngine::CloseSession
,D/DrmWidevineDash(  399): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  399): L3 Terminate.
D/DrmWidevineDash(  399): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): Service_Uninitialize: starts!
D/QSEECOMAPI: (  399): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  399): QSEECom_shutdown_app, app_id = 6
D/DrmWidevineDash(  399): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  399): OEMCrypto_Terminate: ends! returns 0
,W/AudioManagerAndroid( 5055): Requires BLUETOOTH permission,
,I/ActivityManager(  935): Recipient 4294,
,E/WifiTrafficPoller(  935): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  935):  packet count Tx=82 Rx=145
E/WifiTrafficPoller(  935): notifying of data activity 1
D/WIFI_ICON( 1216): WifiActivity: 1
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAV2    ( 4685): Thread[GAThread,5,main]: No campaign data found.,
,I/GAv4-SVC( 4467): Google Analytics 7.8.99 is starting up.
,I/NSApplication( 5055): Starting up...
,I/ActivityManager(  935): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5198 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  935): killProcessQuiet, pid=4443
I/ActivityManager(  935): Killing 4443:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/cutils-trace( 5219): Error opening trace file: Permission denied (13),
I/dex2oat ( 5219): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 5219): dex2oat: override thread count:4
,I/dex2oat ( 5219): dex2oat took 44.573ms (threads: 4),
,I/Adreno-EGL( 5100): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5100): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5100): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5100): Local Branch: 
I/Adreno-EGL( 5100): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5100): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5100):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  935): Recipient 4443
,I/Adreno-EGL( 5100): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5100): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5100): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5100): Local Branch: 
I/Adreno-EGL( 5100): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5100): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5100):                  d74aa161a12b9c6fc6332151
,I/art     ( 1845): Explicit concurrent mark sweep GC freed 11758(632KB) AllocSpace objects, 8(672KB) LOS objects, 49% free, 4MB/8MB, paused 1.108ms total 56.825ms,
,I/WVCdm   (  399): CdmEngine::OpenSession
I/WVCdm   (  399): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  399): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  399): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,D/DrmWidevineDash(  399): Service_Initialize: starts!
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
E/QSEECOMAPI: (  399): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  399): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
,D/QSEECOMAPI: (  399): Loaded image: APP id = 7
,D/DrmWidevineDash(  399): Service_Initialize: ends! returns 0,
,D/QSAPPSVER(  399): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  399): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b85000
E/DrmWidevineDash(  399): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b85000
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  491): got the req here! ret=0
D/DrmLibTime(  491): command id, time_cmd_id = 770
D/DrmLibTime(  491): time_getutcsec starts!
D/DrmLibTime(  491): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  491): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  491): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  491): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  491): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  491): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  491): QSEE Time Listener: Retrieved Android system time: 1450199020
D/DrmLibTime(  491): time_getutcsec returns 0, sec = 1450199020; nsec = 0
D/DrmLibTime(  491): time_getutcsec finished! 
D/DrmLibTime(  491): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  491): before calling ioctl to read the next time_cmd
E/QC-time-services(  434): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!,
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  399): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: starts! SID=0xf4cae928
D/DrmWidevineDash(  399): OEMCrypto_OpenSession Session ID = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: starts! randomData=0xaac1abd8, dataLength=8
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaabfd318, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  399): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  399): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  399): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  399): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: starts! deviceID=0xaac05968, idLength=0xffd5fc38
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: starts!, current = 0xffd5fc4e, maximum = 0xffd5fc4f
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9,
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xffd5fcbc
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  399): PrepareKeyRequest: nonce=2810513952
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaad1b950
D/DrmWidevineDash(  399): message_length=1646, signature=0xaad1bfc8, signature_length=0xffd5fc1c
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/ActivityManager(  935): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5232 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/Process (  935): killProcessQuiet, pid=4406
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  935): Killing 4406:com.android.vending/u0a72 (adj 15): empty #17
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  399): CdmEngine::CloseSession
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  399): L3 Terminate.
,D/DrmWidevineDash(  399): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): Service_Uninitialize: starts!,
D/QSEECOMAPI: (  399): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  399): QSEECom_shutdown_app, app_id = 7
D/DrmWidevineDash(  399): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  399): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  935): Recipient 4406
,I/CheckinRequestBuilder( 4467): Classify the device as Phone.,
,W/ResourcesManager( 5232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,D/libc    ( 4467): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4467): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 4467): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4467): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4467): [NET] android_getaddrinfo_proxy+
D/libc    ( 4467): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 4467): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4467): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4467): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4467): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4467): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4467): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4467): [NET] android_getaddrinfofornet-, err=8
,E/WifiTrafficPoller(  935): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1216): WifiActivity: 3
E/WifiTrafficPoller(  935):  packet count Tx=88 Rx=152
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  935): notifying of data activity 3
,I/CheckinTask( 4467): Sending checkin request (8426 bytes),
,I/ActivityManager(  935): Killing 3946:com.htc.sense.mms/u0a64 (adj 15): empty #17,
D/Process (  935): killProcessQuiet, pid=3946
,D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/SocialFeedProvider( 1627): +disConnect socialManager
,I/SocialFeedProvider( 1627): disconnect socialManager
,I/CheckinRequestBuilder( 4467): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  935): Recipient 3946
,I/ActivityManager(  935): Cannot resolve ContentProvider=com.google.android.wearable.settings,
E/ActivityThread( 4467): Failed to find provider info for com.google.android.wearable.settings
,I/SocialFeedProvider( 1627): -disConnect socialManager
,D/Process (  935): killProcessQuiet, pid=3592
I/ActivityManager(  935): Killing 3592:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4467, uid=10024, userID:0,
I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4467, uid=10024, userID:0
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4467, uid=10024, userID:0,
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4467, uid=10024, userID:0
,I/ActivityManager(  935): Recipient 3592,
,I/ActivityManager(  935): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5266 uid=10035 gids={50035, 9997} abi=arm64-v8a
,V/AlarmManager(  935): sending alarm PendingIntent{3924c30e: PendingIntentRecord{32e9812f com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1450199021326, Int=0,
,W/SystemReader(  935): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1766): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
I/SocialManager[SocialBiLogHelper]( 4856): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4856): last commit ulog time 1450189405027
I/SocialManager[SocialBiLogHelper]( 4856): skip commit this time
W/ResourcesManager( 1564): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AccTypeManager( 1766): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  935): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 1627): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1627): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1627): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Launcher( 1627): Deferring update until onResume,
,D/Launcher( 1627): waitUntilResume // bindAppsUpdated
I/Prism.ItemManager( 4856): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4856): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1766): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1564): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1766): Unsupported attribute readOnly
,D/Process (  935): killProcessQuiet, pid=4603,
I/ActivityManager(  935): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5291 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  935): Killing 4603:com.google.android.youtube/u0a176 (adj 15): empty #17
,W/PackageManager(  935): Unable to load service info ResolveInfo{23c39da5 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  935): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  935): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  935): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  935): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  935): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  935): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  935): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  935): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  935): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  935): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  935): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/WifiStateMachine(  935): handleMessage: E msg.what=131155,
E/WifiStateMachine(  935): processMsg: ConnectedState
E/WifiStateMachine(  935):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=21.3, 0.0, 0.0  rx=31.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1499924525] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
,E/WifiStateMachine(  935): processMsg: L2ConnectedState,
E/WifiStateMachine(  935):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=21.3, 0.0, 0.0  rx=31.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1499924524] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  935):  get link layer stats 0
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1327): environment dirty rate=20 [20][4][0]
E/WifiStateMachine(  935): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  935): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  935): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  935): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=20.65 txretriesrate=0.00 rxrate=25.05 userTriggerdPenalty0
E/WifiStateMachine(  935):  good link -> stuck count =0
E/WifiStateMachine(  935):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  935):  isHighRSSI       ---> score=65
,I/ActivityManager(  935): Recipient 4603
,I/BackupManagerService(  935): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,E/WifiStateMachine(  935): handleMessage: X
,D/WIFI_ICON( 1216): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/SMSBackup( 5291): Got a database change event,
D/WifiWatchdogStateMachine(  935): RSSI current: 3 new: -59, 3
,V/GmsNetworkLocationProvi( 1800): DISABLE
,I/ActivityManager(  935): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=5312 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/GCoreNlp( 1800): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  935): applying state to connected service
,D/PMS     (  935): acquireWL(24728af): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1800 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): releaseWL(24728af): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  935): Killing 4685:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  935): killProcessQuiet, pid=4685
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/HtcWrapAdjustableCursorFactory( 5312): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
D/MessageFrequencyProvider( 5312): onCreate
,E/WifiTrafficPoller(  935): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  935):  packet count Tx=102 Rx=163,
,I/ActivityManager(  935): Recipient 4685
,D/LocationProviderProxy(  935): applying state to connected service
,V/GetPrviateResource( 5312): GetPrviateResource
V/GetPrviateResource( 5312): GetPrviateResource
D/PMS     (  935): acquireWL(d0bd4bc): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1800 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): acquireWL(2e430c45): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1800 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): releaseWL(2e430c45): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): releaseWL(d0bd4bc): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/MessageCustFlag( 5312): sense_version=6.0
D/BTAccessoryUtil( 5312): createReceiver
,D/BTAccessoryUtil( 5312): registerReceiver return intent = null,
,D/MessageCustFlag( 5312): sku_id=118,
,D/PMS     (  935): acquireWL(1b8d27c1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1800 10024 WorkSource{10024 com.google.android.gms},
D/HtcBuildUtils( 5312): getRATByHtcTelephonyCapability:1
W/SystemReader( 5312): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  935): releaseWL(1b8d27c1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/MmsConfig( 5312): packageName: com.htc.vvm.att does not exist,
D/MessageCustFlag( 5312): sku_id=118
,D/MessagingShortcutReceiver( 5312): keep hiding shortcut bubble,
,D/MessagingShortcut( 5312): updateMsgShortcut, msg count> -1,
,D/SettingsManager( 5312): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@399f6c67
,D/MessagingShortcut( 5312): After query: 0
D/MessagingShortcut( 5312): mPresentUnreadCount: -1
,D/MessageUtils( 5312): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 5312): setMsgShortcutDrawable> 0, false
,D/MessagingShortcut( 5312): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1334): [EventService] reorderNotification, total:0
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1334): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  935): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5339 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  935): killProcessQuiet, pid=4764
I/ActivityManager(  935): Killing 4764:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  935): Explicit concurrent mark sweep GC freed 23890(1283KB) AllocSpace objects, 3(188KB) LOS objects, 33% free, 16MB/24MB, paused 1.746ms total 184.009ms
,I/ActivityManager(  935): Recipient 4764
,W/ResourcesManager( 5339): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/GLSUser ( 1845): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1845): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1845): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1845): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/TodoTaskshortcut( 5339): update TASK shortcut>,
,D/DotMatrix( 1334): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
,W/CheckinRequestBuilder( 4467): awaiting user notification for token
,I/RemoteViews( 1216): reapply : com.google.android.gms 4 40
,D/DotMatrix( 1334): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/CheckinRequestBuilder( 4467): Classify the device as Phone.,
,D/PMS     (  935): acquireWL(308e0df9): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5339 10069 null
,D/PMS     (  935): acquireWL(3c54013e): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5339 10069 null
,D/PMS     (  935): releaseWL(308e0df9): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 5339): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference,
D/PMS     (  935): releaseWL(3c54013e): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 5339): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5339): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 5339): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
,W/System.err( 5339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5339): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 5339): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 5339): stopSelfResult true
I/ActivityManager(  935): Killing 4731:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  935): killProcessQuiet, pid=4731
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/CheckinTask( 4467): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/PMS     (  935): acquireWL(204be4ec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1845 10024 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  935): Recipient 4731
,D/WifiService(  935): Client connection lost with reason: 4
,I/CheckinService( 4467): Checking schedule, now: 1450199022572 next: 1450735854361
I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4467, uid=10024, userID:0
I/CheckinService( 4467): active receiver: disabled
D/MtpReceiver( 3849): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3849): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3849): [MTP][handleUsbState]+
,E/WifiDataStallTracker(  935): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  935): updateDataStallInfo: mDataStallTxRxSum={txSum=86 rxSum=81} preTxRxSum={txSum=62 rxSum=63}
D/WifiDataStallTracker(  935): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  935): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
D/PMS     (  935): releaseWL(204be4ec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  935): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5367 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,D/MtpReceiver( 3849): [MTP][scanExternalVolumeIfNeed] scan external volume
D/PMS     (  935): releaseWL(12f7184e): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/MtpService( 3849): updating state; isCurrentUser=true, mMtpLocked=false,
D/MtpReceiver( 3849): [MTP][handleUsbState]-,
D/MtpReceiver( 3849): [MTP][handleMessage]-
D/MtpDatabase( 3849): TotalSize=1886532,MediaCacheLimit=6000
,D/MtpService( 3849): [isMtpConnected] connected: true
D/PMS     (  935): acquireWL(652bb): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 4467 10024 null
,I/iu.UploadsManager( 4467): End new media; added: 0, uploading: 0, time: 61 ms
,D/PMS     (  935): releaseWL(652bb): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,E/WifiTrafficPoller(  935): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  935):  packet count Tx=102 Rx=163
,D/WIFI_ICON( 1216): WifiActivity: 0
E/WifiTrafficPoller(  935): notifying of data activity 0
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/MediaScannerService( 3849): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3849): [handleMessage] --- Should not be here, ignore request. ----
,D/SyncApplication( 5367): Loading default preferences
,W/Resources( 5367): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,D/WifiService(  935): New client listening to asynchronous messages
E/WifiTrafficPoller(  935): ADD_CLIENT: 7
,E/MediaScannerServiceEx( 3849): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3849): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0,
D/MediaScannerServiceEx( 3849): [handleExternalVolume] ext storage
D/SyncApplication( 5367): Overriding preferences with custom values
,D/MediaProviderUtils( 3849): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3849): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3849): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3849): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3849): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 3849): [update][6]#0#
,D/MediaProvider( 3849): [update][1]#0#
,D/SyncApplication( 5367): Updating preferences succeeded
,E/SyncApplication( 5367): Application created.
,D/MediaProvider( 3849): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted,
D/MtpService( 3849): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3849): [update][10]#1#
,D/MediaScannerServiceEx( 3849): [AliveExtStorageRows]-0, 0,
,I/CalendarDefines( 5367): getNewCalendarAuthority()...
,D/PMS     (  935): acquireWL(2817216d): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3849 10017 null
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5367, uid=10005, userID:0
W/PackageManager(  935): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
W/VolumeInfo( 5367): Unable to read mount points
W/VolumeInfo( 5367): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5367): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5367): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5367): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5367): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5367): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5367): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5367): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5367): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5367): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5367): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5367): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5367): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
,W/VolumeInfo( 5367): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5367): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5367): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5367): 	... 13 more
I/PackageManager(  935):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5367, uid=10005, userID:0
V/VolumeInfo( 5367): Found 0 mount point(s)
W/PackageManager(  935): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
V/VolumeInfo( 5367): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/SyncApplication( 5367): enableAppOperation()+
,D/SyncApplication( 5367): enableAppOperation()-
,D/VolumeInfo( 5367): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/MediaScanner( 3849): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
D/HTCUtilities( 5367): isNeorSinged() + 
,D/VolumeInfo( 5367): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 5367): Can not create volume ID for unmounted volume null,
,D/HTCUtilities( 5367): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 5367): isNeorSinged() return false
,D/CDMountReceiver( 5367): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 5367): USB connected to PC
,I/Prism.ItemManager( 1627): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1627): loadItems() com.htc.launcher.pageview.WidgetManager@22942605 +
I/Prism.WidgetManager( 1627): onLoadItems() +
,D/FOTAReceiver( 5367): onReceive() enter 
,D/FOTAReceiver( 5367): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/Prism.ItemManager( 4856): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4856): loadItems() com.htc.launcher.pageview.WidgetManager@3fe3640a +,
,I/Prism.WidgetManager( 4856): onLoadItems() +
,I/ActivityManager(  935): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5399 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActivityManager(  935): Killing 4801:com.htc.club/u0a181 (adj 15): empty #17
D/Process (  935): killProcessQuiet, pid=4801
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 ,
W/ResourcesManager( 1627): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  406): Explicit concurrent mark sweep GC freed 8644(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 227us total 26.592ms,
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 204us total 23.908ms
,W/ResourcesManager( 4856): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 21.409ms
,I/ActivityManager(  935): Recipient 4801,
,D/PMS     (  935): acquireWL(2556a1a2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 935 1000 null,
I/BatteryService(  935): n_update end
D/PMS     (  935): releaseWL(2556a1a2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  935): BroadcastReceiver::onReceive+
D/UsbnetService(  935): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  935): updateBatteryInfo
D/UsbnetService(  935):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  935): plugged=true pluggin=true
D/UsbnetService(  935): BroadcastReceiver::onReceive-
D/WifiController(  935): battery changed pluggedType: 2
D/WifiController(  935): handleMessage: E msg.what=155652
D/PMS     (  935): runPSCheck
D/WifiController(  935): processMsg: DeviceActiveState
D/HtcPowerSaver(  935): Checking...
D/WifiController(  935): processMsg: StaEnabledState
I/HtcPowerSaver(  935): >> updateStatus
D/WifiController(  935): processMsg: DefaultState
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  935): handleMessage: X
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1334): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3109): Disconnected process message: 10, size: 0
D/BluetoothManagerService(  935): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  935): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1fb548bc mBinding = false
I/HtcPowerSaver(  935): updateStatus (8000,100,-1,false,false,false,-1)
W/Settings:Agent(  935): MONITOR_LOG
W/Settings:Agent(  935): name: bluetooth_on
W/Settings:Agent(  935): value: 0
W/Settings:Agent(  935): >> traceCallingStack()
,I/HtcPowerSaver(  935): << updateStatus
W/Settings:Agent(  935): Process.myPid(): 935
W/Settings:Agent(  935): Process.myTid(): 1623
W/Settings:Agent(  935): Process.myUid(): 1000
W/Settings:Agent(  935): 
W/Settings:Agent(  935): 
W/System.err(  935): java.lang.Throwable: stack dump
,D/PowerUI ( 1216): closing low battery warning: level=100
,D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/System.err(  935): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  935): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  935): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  935): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  935): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  935): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  935): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
,W/System.err(  935): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  935): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  935): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  935): 
W/Settings:Agent(  935): << traceCallingStack(): 18(ms)
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5399): -onCreate()
,D/BluetoothManagerService(  935): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  935): Sending off request.
,D/BluetoothAdapterState( 3109): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3109): Setting state to 13
I/BluetoothAdapterState( 3109): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  935): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 3109): onBluetoothDisable()
I/bt-btm  ( 3109): BTM_SetDiscoverab->adapter_properties_cb
I/bt-btif ( 3109): BTM_SetDiscoverab->adapter_properties_cb
I/BluetoothAdapterState( 3109): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService(  935): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  935): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  935): Bluetooth State Change Intent: 12 -> 13
I/bt-btm  ( 3109): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3109): disc_mode 0000
I/bt-btm  ( 3109): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3109): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/IntentController( 1216): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/PMS     (  935): acquireWL(306e5e33): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3109 1002 null
I/bt-btm  ( 3109): BTM_SetConnectability
I/bt-btm  ( 3109): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3109): disc_mode 0000
I/bt-btm  ( 3109): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/NGFService( 3737): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,D/WifiManager( 4929): setWifiEnabled: Base Package Name=com.example.hello, uid=10374
D/WifiService(  935): New client listening to asynchronous messages
E/WifiTrafficPoller(  935): ADD_CLIENT: 8
,D/WifiService(  935): setWifiEnabled: false pid=4929, uid=10374
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiService(  935): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  935): MONITOR_LOG
I/WifiService(  935): isSprintWifiRestricted(): false
W/Settings:Agent(  935): name: wifi_on
I/WifiService(  935): isMdmWifiRestricted(): false
W/Settings:Agent(  935): value: 0
W/Settings:Agent(  935): >> traceCallingStack()
W/Settings:Agent(  935): Process.myPid(): 935
,W/Settings:Agent(  935): Process.myTid(): 1624
W/Settings:Agent(  935): Process.myUid(): 1000
W/Settings:Agent(  935): 
W/Settings:Agent(  935): 
D/BluetoothAdapterProperties( 3109): Scan Mode:21
,W/System.err(  935): java.lang.Throwable: stack dump
,V/Settings:HtcSettingsApplication( 5399): [5399/5399] onCreate()
,D/BluetoothAdapterState( 3109): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,I/bt-btif ( 3109): BTA_JvDeleteRecord
I/bt-btif ( 3109): BTA_JvRfcommStopServer
D/bt-btm  ( 3109): BTM_FreeSCN 
I/bt-btif ( 3109): BTA_JvDeleteRecord
I/bt-btif ( 3109): BTA_JvRfcommStopServer
D/bt-btm  ( 3109): BTM_FreeSCN 
I/bt-btif ( 3109): BTA_JvDeleteRecord
I/bt-btif ( 3109): BTA_JvRfcommStopServer
D/bt-btm  ( 3109): BTM_FreeSCN 
I/bt-btif ( 3109): BTA_JvDeleteRecord
I/bt-btif ( 3109): BTA_JvRfcommStopServer
D/bt-btm  ( 3109): BTM_FreeSCN 
I/bt-btif ( 3109): BTA_JvDeleteRecord
,I/bt-btif ( 3109): BTA_JvRfcommStopServer
D/bt-btm  ( 3109): BTM_FreeSCN 
I/bt-btif ( 3109): BTA_JvDeleteRecord
I/bt-btif ( 3109): BTA_JvRfcommStopServer
D/bt-btm  ( 3109): BTM_FreeSCN 
E/bt-btif ( 3109): cmd socket is not created
D/bt-sdp  ( 3109): SDP_DeleteRecord ok, num_records:14
V/BluetoothSapService( 3109): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BtOppRfcommListener( 3109): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/ResourcesManager( 1627): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/BluetoothPbapReceiver( 3109): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3109): ***********state = 13
,I/BtOppRfcommListener( 3109): stopping Accept Thread,
I/BtOppRfcommListener( 3109): BluetoothSocket listen thread finished
,I/bt-btm  ( 3109): BTM_SEC_CLR[13]: id 55
D/bt-sdp  ( 3109): SDP_DeleteRecord ok, num_records:13,
I/bt-btm  ( 3109): BTM_SEC_CLR[14]: id 56
D/bt-sdp  ( 3109): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3109): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3109): SDP_DeleteRecord ok, num_records:11
,I/bt-btm  ( 3109): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3109): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3109): BTM_SEC_CLR[17]: id 59
D/bt-sdp  ( 3109): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3109): BTM_SEC_CLR[18]: id 60
,D/bt-sdp  ( 3109): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3109): Write Extended Inquiry Response to controller
I/bt-btm  ( 3109): Write Extended Inquiry Response to controller
I/bt-btm  ( 3109): Write Extended Inquiry Response to controller
I/bt-btm  ( 3109): Write Extended Inquiry Response to controller
D/TetherSettings( 5399): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5399): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5399): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5399): Cust_ConnectToPC   : spcsc>false
D/        ( 5399): Cust_ConnectToPC   : IPT>true
D/        ( 5399): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5399): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/QuickSettingBluetooth( 1216): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
,V/BluetoothPbapService( 3109): Pbap Service closeService in
,V/BluetoothPbapService( 3109): successfully stopped pbap service,
V/BluetoothPbapService( 3109): Pbap Service closeService out
,E/SmartNS_Utility( 5399): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5399): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5399): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 5399): usb_cable_connect = 1
V/BluetoothPbapService( 3109): Pbap Service onDestroy
,W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x000f
I/bt-btm  ( 3109): BTM_SetDiscoverability
I/bt-btm  ( 3109): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3109): disc_mode 0000,
I/bt-btm  ( 3109): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3109): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3109): BTM_SetConnectability
I/bt-btm  ( 3109): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3109): disc_mode 0000
D/bt-btm  ( 3109): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3109): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3109): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3109): BTM_IsInquiryActive
I/bt-btm  ( 3109): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3109): btm_ble_clear_white_list
W/bt-btif ( 3109): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/SmartNS_Utility( 5399): usb_denied = 0
D/bt-btif ( 3109): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3109): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3109): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3109): BTM_FreeSCN 
,I/bt-btm  ( 3109): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3109): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3109): BTM_FreeSCN 
I/bt-btm  ( 3109): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3109): AVRC_Close handle:0
D/bt-btif ( 3109): AV Sevent(0x41)=0x120a(API_CLOSE) state=0(INIT)
D/bt-btif ( 3109): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
,I/SmartNS_NSReceiver( 5399): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 5399): USB = true hasTethered = false isNSOpening: false
,V/BluetoothPbapService( 3109): Pbap Service closeService in
,V/BluetoothPbapService( 3109): Pbap Service closeService out
,D/bt-sdp  ( 3109): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3109): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3109): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3109): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3109): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3109): GATT_Deregister gatt_if=3
I/bt-att  ( 3109): GATT_Listen gatt_if=3
I/bt-btm  ( 3109): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3109): BTM_ReadConnectability
,I/bt-btm  ( 3109): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3109): disc_mode 0000
I/bt-att  ( 3109): GATT_Deregister gatt_if=4
I/bt-att  ( 3109): GATT_Listen gatt_if=4
I/bt-btm  ( 3109): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3109): BTM_ReadConnectability
I/bt-btm  ( 3109): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3109): disc_mode 0000
E/bt-btif ( 3109): bta_gattc_deregister Deregister Failedm unknown client cif
,W/System.err(  935): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  935): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  935): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  935): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  935): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  935): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
,W/System.err(  935): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  935): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  935): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  935): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  935): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  935): 
W/Settings:Agent(  935): << traceCallingStack(): 64(ms)
,W/ResourcesManager( 4856): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  935): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5424 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,D/PMS     (  935): acquireWL(e23d5f0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5399 1000 null
I/ActivityManager(  935): Killing 4892:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  935): killProcessQuiet, pid=4892
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 ,
,D/PhoneApp( 1564): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1564): -- N1 =0
D/PhoneApp( 1564): -- N2 =0
,W/ContextImpl( 5399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/PhoneApp( 1564): -- N3 =0
I/bt-btm  ( 3109): btm_ble_clear_white_list_complete
,D/WifiController(  935): handleMessage: E msg.what=155656
D/WifiController(  935): processMsg: DeviceActiveState
D/WifiController(  935): processMsg: StaEnabledState
D/WifiController(  935): transitionTo: destState=ApStaDisabledState
D/WifiController(  935): handleMessage: new destination call exit/enter
D/WifiController(  935): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
,D/WifiController(  935): invokeExitMethods: DeviceActiveState
D/WifiController(  935): invokeExitMethods: StaEnabledState
D/WifiController(  935): moveTempStackToStateStack: i=0,j=1
D/WifiController(  935): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  935): invokeEnterMethods: ApStaDisabledState
I/jxcore-log( 4929): ****TEST TOOK:  5318  ms ****
I/jxcore-log( 4929): 
I/jxcore-log( 4929): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4929): 
D/WifiController(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=131084,
E/WifiStateMachine(  935): processMsg: ConnectedState
E/WifiStateMachine(  935):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  935): processMsg: L2ConnectedState
E/WifiStateMachine(  935):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  935): processMsg: DriverStartedState
E/WifiStateMachine(  935):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
D/WifiDisplayAdapter(  935): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  935):     Client/Owner: Client
D/WifiDisplayAdapter(  935):     GroupId: 
D/WifiDisplayAdapter(  935):     Passphrase: 
D/WifiDisplayAdapter(  935):     SessionId: 0
D/WifiDisplayAdapter(  935):     IP Address: }
E/WifiStateMachine(  935): processMsg: SupplicantStartedState
E/WifiStateMachine(  935):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  935): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  935): handleMessage: new destination call exit/enter
E/WifiStateMachine(  935): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  935): invokeExitMethods: ConnectedState
E/WifiStateMachine(  935): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  935): release()
E/WifiStateMachine(  935): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  935): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  935): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  935): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  935): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  935): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  935): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  935): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1327): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1327): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1327): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1327): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1327): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1327): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  935): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1327): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1327): Power_Mode_Type mode = 0
I/wpa_supplicant( 1327): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1327): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1327): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  935): setDhcpActive: false
D/WifiP2pService(  935): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  935): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 1845): Read error: ssl=0x559573a650: I/O error during system call, Connection timed out
,D/libc    (  935): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/PMS     (  935): acquireWL(18116769): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
V/NativeCrypto( 1845): SSL shutdown failed: ssl=0x559573a650: I/O error during system call, Broken pipe
E/WifiStateMachine(  935): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  935): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  935): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  935): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  935): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): Validated
D/ConnectivityService(  935): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  935): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  935):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  935):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  935): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  935): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  935): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1216): CM callback handler got msg 524290
I/SecurityController( 1216): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/asset   ( 1627): Copying FileAsset 0x5595ac6b60 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/ActivityManager(  935): Recipient 4892
D/MediaRouterService(  935): Client com.google.android.music (pid 4892): Died!
,W/asset   ( 4856): Copying FileAsset 0x55957f76f0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1627): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1627): onLoadItems() -
I/Prism.ItemManager( 1627): loadItems() com.htc.launcher.pageview.WidgetManager@22942605 -
,D/bt-btm  ( 3109): BTM_BleGetVendorCapabilities,
W/bt-btif ( 3109): ag scb idx 1 not allocated
W/bt-btif ( 3109): ag scb idx 2 not allocated
E/bt-btif ( 3109): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3109): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3109): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x0019,
W/bt-l2cap( 3109): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3109): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3109): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3109): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3109): L2CAP - PSM: 0x0017 not found for deregistration
E/bt-btif ( 3109): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt_userial_mct( 3109): pthread_join() FAILED result:3
,D/MediaProvider( 3849): [update][12]#1#
,I/Prism.WidgetManager( 4856): onLoadItems() -,
I/Prism.ItemManager( 4856): loadItems() com.htc.launcher.pageview.WidgetManager@3fe3640a -
,E/WifiStateMachine(  935): NetworkAgent != null
D/ConnectivityService(  935): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/PMS     (  935): releaseWL(18116769): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  935): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  935): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  935): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  935): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1327): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1327): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1327): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1327): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1327): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
V/NetworkPolicy(  935): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/wpa_supplicant( 1327): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/PMS     (  935): releaseWL(e23d5f0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
E/WifiStateMachine(  935): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  935): invokeExitMethods: DriverStartedState
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1327): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1327): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  935): Unexpected BatchedScanResults :null
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1327): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1327): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiStateMachine(  935): noteBatchedScanstop()
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiDataStallTracker(  935): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  935): stopDataStallAlarm 
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  935):  packet count Tx=102 Rx=165
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  935): notifying of data activity 1
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  935): ENABLE_DATA_MONITOR_POLL false Token 1
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 13
,E/WifiStateMachine(  935): [1,450,199,023,679 ms] noteScanEnd no scan source
E/WifiStateMachine(  935): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  935): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  935): invokeEnterMethods: WaitForP2pDisableState
D/WifiScanningService(  935): SCAN_AVAILABLE : 1
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=131212
D/RttService(  935): SCAN_AVAILABLE : 1
E/WifiStateMachine(  935): processMsg: WaitForP2pDisableState
D/RttService(  935): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  935):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: SupplicantStartedState
D/WifiP2pService(  935): InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  935):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiP2pService(  935): P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  935): processMsg: DefaultState
D/PMS     (  935): acquireWL(2da6aa8f): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5399 1000 null
D/WifiMonitor(  935): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@247706f1
D/WifiScanningService(  935): DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  935):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  935): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=131212
E/WifiStateMachine(  935): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  935):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: SupplicantStartedState
E/WifiStateMachine(  935):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: DefaultState
E/WifiStateMachine(  935):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  935): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiP2pService(  935): P2pDisablingState
E/WifiStateMachine(  935): handleMessage: X
D/WifiP2pService(  935): P2pDisablingState{ when=-10ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  935): handleMessage: E msg.what=131212
D/WifiP2pService(  935): p2p socket connection lost
E/WifiStateMachine(  935): processMsg: WaitForP2pDisableState
D/WifiP2pService(  935): P2pDisabledState
E/WifiStateMachine(  935):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiDisplayController(  935): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
E/WifiStateMachine(  935): processMsg: SupplicantStartedState
D/WifiDisplayAdapter(  935): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  935):     Client/Owner: Client
D/WifiDisplayAdapter(  935):     GroupId: 
D/WifiDisplayAdapter(  935):     Passphrase: 
D/WifiDisplayAdapter(  935):     SessionId: 0
D/WifiDisplayAdapter(  935):     IP Address: }
E/WifiStateMachine(  935):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: DefaultState
E/WifiStateMachine(  935):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  935): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  935): handleMessage: X
D/WIFI_ICON( 1216): WifiActivity: 1
D/WifiNetworkAgent(  935): NetworkAgent: NetworkAgent channel lost
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  935): handleMessage: E msg.what=131205
E/WifiStateMachine(  935): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  935):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
E/WifiStateMachine(  935): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  935): handleMessage: new destination call exit/enter
E/WifiStateMachine(  935): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  935): invokeExitMethods: WaitForP2pDisableState
E/WifiStateMachine(  935): invokeExitMethods: SupplicantStartedState
E/WifiStateMachine(  935): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  935): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
E/WifiStateMachine(  935): invokeEnterMethods: SupplicantStoppingState
E/WifiStateMachine(  935): Call handleNetworkDisconnect() in SupplicantStoppingState
V/AudioService(  935): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  935):     Client/Owner: Client
V/AudioService(  935):     GroupId: 
V/AudioService(  935):     Passphrase: 
V/AudioService(  935):     SessionId: 0
V/AudioService(  935):     IP Address: }
D/HtcEffectManagerBase(  935): onEventChanged id=5 status=false
D/WifiP2pService(  935): P2pDisabledState{ when=-12ms what=131333 target=com.android.internal.util.StateMachine$SmHandler }
D/HtcEffectManager(  935): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/WifiP2pService(  935): DefaultState{ when=-12ms what=131333 target=com.android.internal.util.StateMachine$SmHandler }
D/HtcEffectManager(  935): convertEffect before=902
D/WifiP2pService(  935): P2pDisabledState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/HtcEffectManager(  935): convertEffect after=902
D/WifiP2pService(  935): DefaultState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/HtcModeClient( 3224): handler message = 4011
E/WifiStateMachine(  935): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
E/HtcModeClient( 3224): Check connection and retry 5 times.
E/WifiStateMachine(  935): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1327): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1327): Power_Mode_Type mode = 0
I/wpa_supplicant( 1327): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/HtcBtWidget_BTWidgetProvider( 5424): onBTStateChanged() for widget: 
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/BluetoothManagerService(  935): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  935): java.lang.Throwable: stack dump
D/wpa_supplicant( 1327): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/BluetoothManagerService(  935): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1aeec2fa:true
D/wpa_supplicant( 1327): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
W/System.err(  935): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  935): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  935): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  935): 	at android.os.Binder.execTransact(Binder.java:454)
D/WifiDataStallTracker(  935): setDhcpActive: false
D/HtcBtWidget_BTWidgetProvider( 5424): updateWidget(context) for widget: 
E/WifiTrafficPoller(  935): TRAFFIC_STATS_POLL false Token 14 num clients 8
D/BluetoothAdapter( 5399): 648179890: getState(). Returning 13
,D/BluetoothFtpService( 3109): ACTION_STATE_CHANGED: state: 13mHasStarted: true
E/BluetoothFtpService:RfcommSocketAcceptThread( 3109): Shutdown
D/BluetoothMasReceiver( 3109): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 3109): SapReceiver onReceive 
V/BluetoothSapReceiver( 3109): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3109):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3109): startService = false
D/BluetoothInputDevice( 5399): BluetoothInputDevice()
D/BluetoothManagerService(  935): registerStateChangeCallback+
D/BluetoothManagerService(  935): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  935): Registered receivers: 9
D/AuthorizationBluetoothService( 1845): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/PMS     (  935): releaseWL(306e5e33): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
I/QuickSettingWifi( 1216): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:0
D/BluetoothPan( 5399): BluetoothPan()
D/BluetoothManagerService(  935): registerStateChangeCallback+
D/BluetoothManagerService(  935): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  935): Registered receivers: 10
D/ConnectivityService(  935): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  935): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/BluetoothMap( 5399): Create BluetoothMap proxy object
D/BluetoothManagerService(  935): registerStateChangeCallback+
D/Nat464Xlat(  935): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
E/WifiStateMachine(  935): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  935): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  935): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/BluetoothManagerService(  935): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothManagerService(  935): Registered receivers: 11
D/usbnet  (  935): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  935): Removing idletimer
D/usbnet  (  935):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  935): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1216): CM callback handler got msg 524292
I/SecurityController( 1216): onLost 100
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  935): stopping supplicant
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): Disconnected - quitting
W/WifiHW  (  935): QCOM Debug wifi_send_command "TERMINATE"
D/wpa_supplicant( 1327): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/wpa_supplicant( 1327): wlan0: Removing interface wlan0
D/wpa_supplicant( 1327): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1327): TDLS: Tear down peers
D/wpa_supplicant( 1327): wpa_driver_nl80211_disconnect(reason_code=3)
E/BluetoothMap( 5399): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  935): setWifiState: disabling
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  935): acquireWL(38cd557f): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 935 1000 null
E/WifiStateMachine(  935): handleMessage: X
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WIFI    (  935): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI    (  935):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/CSLegacyTypeTracker(  935): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/WIFI    (  935): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/ConnectivityService(  935): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  935): enter WifiNetworkFactory startNetwork. mIPTStart:false
E/WifiStateMachine(  935): handleMessage: E msg.what=196614
E/WifiStateMachine(  935): processMsg: SupplicantStoppingState
E/WifiStateMachine(  935):  SupplicantStoppingState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  935): processMsg: DefaultState
E/WifiStateMachine(  935):  DefaultState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  935): handleMessage: X
D/WIFI_ICON( 1216): updateWifiState: WIFI_STATE_CHANGED disabled
I/IntentController( 1216): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/Tethering(  935): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  935): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  935): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
E/ConnectivityService(  935): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/BluetoothManagerService(  935): registerStateChangeCallback+
V/NetworkPolicy(  935): ensureActiveMobilePolicyLocked()
D/BluetoothSap( 5399): BluetoothSap() call bindService
D/PMS     (  935): acquireWL(1eb4494c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 935 1000 null
D/BluetoothManagerService(  935): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/DATA_ICON( 1216): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/BluetoothManagerService(  935): Registered receivers: 12
,D/NetworkPolicy(  935): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  935): updateNetworkEnabledLocked()
V/NetworkPolicy(  935): updateIfacesLocked()
V/NetworkPolicy(  935): updateNotificationsLocked()
,D/DATA_ICON( 1216): dataConnected: false/false
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,W/ContextImpl( 5399): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
D/PMS     (  935): releaseWL(1eb4494c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/NetworkManagementService(  935): isBandwidthControlEnabled: doneSignal.getCount()= 0
,V/NetworkPolicy(  935): updateNetworkEnabledLocked()
V/NetworkPolicy(  935): updateNotificationsLocked()
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
,D/BluetoothPbap( 5399): BluetoothPbap()
,D/BluetoothManagerService(  935): registerStateChangeCallback+
D/BluetoothManagerService(  935): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  935): Registered receivers: 13
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/LocalBluetoothProfileManager( 5399): LocalBluetoothProfileManager construction complete
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/DockEventReceiver( 5399): finishStartingService: stopping service
,D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/MdService( 5122): [6d6.] v648303190-6.1.860197 onStartCommand(dying) flag:0, id:2, failed(resend)
,D/wpa_supplicant( 1327): wlan0: Event DEAUTH (12) received
W/ContextImpl( 5399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 1327): wlan0: Deauthentication notification
D/wpa_supplicant( 1327): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1327): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1327): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1327): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1327): enter disconnect check
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
I/wpa_supplicant( 1327): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1327): wlan0: Auto connect disabled: do not try to re-connect
D/Tethering(  935): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1327): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  935): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/PSReceiver( 5399): onReceive:com.htc.intent.action.USB_CONNECT2PC
E/WifiMonitor(  935): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  935): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  935): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  935): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
E/WifiStateMachine(  935): handleMessage: E msg.what=147460
V/Tethering(  935): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  935): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  935): processMsg: SupplicantStoppingState
E/WifiStateMachine(  935):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=65093
E/WifiStateMachine(  935): processMsg: DefaultState
D/Tethering(  935): interfaceLinkStateChanged wlan0, false
D/Tethering(  935): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  935):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=65093
E/WifiStateMachine(  935): handleMessage: X
D/wpa_supplicant( 1327): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1327): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1327): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1327): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1327): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55804a4f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1327):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1327): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1327): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1327): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1327): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1327): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 1327): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1327): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1327): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1327): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1327): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1327): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1327): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1327): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1327): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1327): EAPOL: External notification - portValid=0
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  935): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  935): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  935): handleMessage: E msg.what=147462
E/WifiStateMachine(  935): processMsg: SupplicantStoppingState
E/WifiStateMachine(  935):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=65099  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  935): processMsg: DefaultState
E/WifiStateMachine(  935):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=65100  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  935): handleMessage: X
I/QuickSettingWifi( 1216): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
E/cutils-trace( 5446): Error opening trace file: Permission denied (13)
,D/BluetoothInputDevice( 5399): Proxy object connected
,D/WISPrService( 5399): >>>>>WISPrService start isConnected = true<<<<<,
D/HidProfile( 5399): Bluetooth service connected
I/ActivityManager(  935): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5470 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/BluetoothAdapter( 5399): 648179890: getState(). Returning 13
D/Tethering(  935): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothPan( 5399): BluetoothPAN Proxy object connected
D/PanProfile( 5399): Bluetooth service connected
D/UsbnetService(  935): BroadcastReceiver::onReceive+
E/WifiStateMachine(  935): handleMessage: E msg.what=131101
D/UsbDeviceManager(  935): [USBNET] bCheckSuppFunc: cdc_network
E/WifiStateMachine(  935): processMsg: SupplicantStoppingState
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/UsbnetService(  935): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/PMS     (  935): acquireWL(3a8f9902): PARTIAL_WAKE_LOCK  NetworkStats 0x1 935 1000 null
D/UsbnetService(  935): BroadcastReceiver::onReceive-
D/SapServerProfile( 5399): Bluetooth service connected
,E/WifiStateMachine(  935):  SupplicantStoppingState !CMD_TETHER_STATE_CHANGE 0 0
D/PMS     (  935): releaseWL(2da6aa8f): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
E/WifiStateMachine(  935): processMsg: DefaultState
E/WifiStateMachine(  935):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  935): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  935): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  935): handleMessage: X
,D/PMS     (  935): releaseWL(3a8f9902): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  935): updateNetworkEnabledLocked()
I/SmartNS_PSService( 5399): onReceive:com.htc.intent.action.USB_CONNECT2PC
V/NetworkPolicy(  935): updateNotificationsLocked()
,D/WifiService(  935): New client listening to asynchronous messages
E/WifiTrafficPoller(  935): ADD_CLIENT: 9
,D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,W/Settings( 5399): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 5399):  defaultType:0
I/SmartNS_PSService( 5399): fail notificaiton:false
D/SmartNS_Utility( 5399): usb_cable_connect = 1
D/SmartNS_Utility( 5399): usb_denied = 0
I/SmartNS_PSService( 5399): usb notificaiton:true
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
I/ActionCombine( 5399): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/MdScPhnSt( 5122): [52d.1.]  listen tmrbb8
E/WifiStateMachine(  935): handleMessage: E msg.what=131131
,E/WifiStateMachine(  935): processMsg: SupplicantStoppingState
E/WifiStateMachine(  935):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms,
E/WifiStateMachine(  935): processMsg: DefaultState
E/WifiStateMachine(  935):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  935): handleMessage: X
,D/SmartNS_Utility( 5399): usb_cable_connect = 1
,D/SmartNS_Utility( 5399): usb_denied = 0
I/SmartNS_PSService( 5399): usb notificaiton:true
,I/bt-btif ( 3109): HAL bt_hal_cbacks->adapter_state_changed_cb,
D/BluetoothAdapterState( 3109): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 3109): mProfilesStarted : true supportedProfileServices.length : 6,
,D/CustomizationManager( 5446): ====startRecUseTime====,
D/htc.customization.log.level( 5446):  is 
W/CustomizationLogLevel( 5446): Level value is invalid, use default level 2
,D/Messaging( 5312): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 5312): networkCode: 
D/MmsConfig( 5312): SIE smsPri: null
D/MmsConfig( 5312): networkCode: 
,D/WISPrService( 5399): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
D/HeadsetService( 3109): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3109): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f6c67
D/HeadsetStateMachine( 3109): Exit Disconnected: -1
D/WISPrService( 5399): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothHeadset(  935): Proxy object disconnected
D/BluetoothHeadset( 1216): Proxy object disconnected
I/QuickSettingMiniLite( 1216): btListener.disconnect:HEADSET
D/A2dpService( 3109): Received stop request...Stopping profile...
D/ReportIndicatorCache( 5312): startAsyncQueryReports ---
D/A2dpStateMachine( 3109): Exit Disconnected: -1
D/BluetoothAdapterService( 3109): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f6c67
D/MmsAsyncWorkHandler( 5312): 
D/MmsAsyncWorkHandler( 5312): HM tk = 20001
D/BluetoothHeadset( 3737): Proxy object disconnected
D/NGFService( 3737): BluetoothHeadset onServiceDisconnected: main
,D/BluetoothA2dp( 3737): Proxy object disconnected
D/BluetoothA2dp(  935): Proxy object disconnected
D/DotMatrix( 1334): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/NGFService( 3737): BluetoothA2dp onServiceDisconnected: main
,D/HidService( 3109): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3109): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f6c67
D/WISPrService( 5399): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5399): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/BluetoothAdapterState( 3109): Stopping profile services that were post enabled
D/ReportIndicatorCache( 5312): MSG_QUERY_REPORTS >>
,I/RemoteViews( 1216): reapply : com.android.settings 2 36
D/WISPrService( 5399): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5399): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/SmartNS_Utility( 5399): usb_cable_connect = 1
D/Messaging( 5312): mNeedToUpdateDate2 start
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
D/SmartNS_Utility( 5399): usb_denied = 0
W/BluetoothHeadsetServiceJni( 3109): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3109): Cleaning up Bluetooth Handsfree callback object
,E/wpa_supplicant( 1327): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1327): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush
D/wpa_supplicant( 1327): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1327): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush
D/wpa_supplicant( 1327): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1327): wlan0: Cancelling scan request
D/wpa_supplicant( 1327): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1327): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  935): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=27 dispatchEvent: BLACKLIST CLEAR 
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1327): Remove interface wlan0 from radio phy0
D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/AccFlag ( 1564): sku_id=118
D/DotMatrix( 1334): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11],
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/WifiMonitor(  935): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=31 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
D/DraftCache( 5312): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5312): [DraftCache/1] refresh
,I/SmartNS_PSService( 5399): KeyGuard locked:falseKeyGuard is secured:false
,D/HealthService( 3109): Received stop request...Stopping profile...
D/SmartNS_PSService( 5399): USB Plugged, Set USBPlugged=  truePSenabled:false
D/BluetoothAdapterService( 3109): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f6c67
D/BluetoothInputDevice( 5399): Proxy object disconnected
D/HidProfile( 5399): Bluetooth service disconnected
,D/PanService( 3109): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3109): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f6c67
,I/Messaging( 5312): mccmnc> 
,D/MmsConfig( 5312): networkCode: 
D/BluetoothPan( 5399): BluetoothPAN Proxy object disconnected
D/PanProfile( 5399): Bluetooth service disconnected
D/CustomizationManager( 5446):  Read ACC file spent 0.037 (s)
,D/DraftCache( 5312): [DraftCache/121] rebuildCache
D/BtGatt.DebugUtils( 3109): handleDebugAction() action=null
W/ContextImpl( 5470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
D/BtGatt.GattService( 3109): Received stop request...Stopping profile...
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/BtGatt.GattService( 3109): stop()
D/CIDMapFileReader( 5446): Parsing tag item name = HTC__001
D/BtGatt.AdvertiseManager( 3109): advertise clients cleared
D/CIDMapFileReader( 5446): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5446): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5446): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5446): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5446): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5446): Parsing tag item name = HTC__031
I/RemoteViews( 1216): reapply : com.android.settings 8 36
,V/CustomizationCIDLoader( 5446): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5446): Parsing tag category name = system
,I/CustomizationCIDLoader( 5446): Parsing tag category name = application
I/CustomizationCIDLoader( 5446): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5446): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5446): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5446): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5446): Parsing tag category name = ACC
,D/Messaging( 5312): ViewCache CreatePreloadOnlyConversationList
I/CustomizationCIDLoader( 5446): add string-array item, value = 42507
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
I/CustomizationCIDLoader( 5446): add string-array item, value = 21902
I/CustomizationCIDLoader( 5446): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5446): add string-array item, value = 23420
I/CustomizationCIDLoader( 5446): add string-array item, value = 22299
I/CustomizationCIDLoader( 5446): add string-array item, value = 24002
I/CustomizationCIDLoader( 5446): add string-array item, value = 23210
I/CustomizationCIDLoader( 5446): add string-array item, value = 23205
I/CustomizationCIDLoader( 5446): add string-array item, value = 23806
I/CustomizationCIDLoader( 5446): add string-array item, value = 23430
I/CustomizationCIDLoader( 5446): add string-array item, value = 23408
I/CustomizationCIDLoader( 5446): add string-array item, value = 27205
I/CustomizationCIDLoader( 5446): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5446): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5446): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5446): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5446): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5446): add string-array item, value = 24002:D:0:0
,I/CustomizationCIDLoader( 5446): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5446): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5446): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5446): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5446): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5446): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5446):  Read CID file spent 0.089 (s)
D/CustomizationManager( 5446):  All configurations done spent 0.089 (s)
D/BluetoothHeadset( 1564): Proxy object disconnected
D/BluetoothHeadset( 1564): Proxy object disconnected
D/BluetoothHeadset( 1564): Proxy object disconnected
D/BluetoothPhoneService( 1564): BluetoothHeadset onServiceDisconnected
D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 97
D/MmsSmsV2Provider( 1564):  slotId = -1000
D/MmsSmsV2Provider( 1564): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/BluetoothAdapterService( 3109): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f6c67
,W/BluetoothHidServiceJni( 3109): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3109): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3109): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3109): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3109): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3109): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterState( 3109): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 3109): Setting state to 10
I/BluetoothAdapterState( 3109): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService(  935): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  935): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  935): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  935): Broadcasting onBluetoothStateChange(false) to 13 receivers.
I/BluetoothAdapterState( 3109): Entering OffState
,D/BluetoothHeadset( 1564): onBluetoothStateChange: up=false
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 97
D/MmsSmsV2Provider( 1564):  slotId = -1000
D/MmsSmsV2Provider( 1564): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/BluetoothA2dp(  935): onBluetoothStateChange: up=false
D/MessageCustFlag( 5312): sense_version=6.0
D/BluetoothHeadset( 1564): onBluetoothStateChange: up=false
D/Jerry   ( 5312): start to preload cursor >>>>>>>
D/PhoneStorageUtil( 5312): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5312): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5312): createReceiver
,D/FlexNetS( 4990): updateSvcAllowedInSettings:false
,D/BluetoothHeadset( 1216): onBluetoothStateChange: up=false
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/Jerry   ( 1564): URI_DRAFT
,I/ActivityManager(  935): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5508 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/BluetoothPan( 5399): onBluetoothStateChange on: false
W/BluetoothHeadset( 1216): Proxy not attached to service
I/QuickSettingMiniLite( 1216): updateLiteState:no connect device!
,D/TelephUtils( 1564): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
V/MmsProvider( 1564): Update uri=content://mms, match=0
V/MmsProvider( 1564): selection=st=129 AND m_type!=134
,D/BluetoothA2dp( 3737): onBluetoothStateChange: up=false
D/DraftCache( 5312): hasDraft() = false mNeedNotifyChange = true,
D/DraftCache( 5312): [DraftCache/121] rebuildCache time: 11
D/MmsAsyncWorkHandler( 5312): 
D/MmsAsyncWorkHandler( 5312): HM tk = 20002
D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54,
D/MmsSmsV2Provider( 1564):  slotId = -1000
D/MmsSmsV2Provider( 1564): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/BluetoothHeadset( 3737): onBluetoothStateChange: up=false
D/BluetoothHeadset(  935): onBluetoothStateChange: up=false
D/BluetoothPbap( 5399): onBluetoothStateChange: up=false
D/Messaging( 5312): Reset downloading state: 0
D/PackageManager(  935): deletePackageAsUser: pkg=com.example.hello, pid=5446, uid=2000 userid=0
D/Messaging( 5312): mNeedToUpdateDate2: false
D/BluetoothHeadset( 1564): onBluetoothStateChange: up=false
D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/MmsSmsV2Provider( 1564):  slotId = -1000
V/MmsSystemEventReceiver( 5312): TransactionService is going to be woken up.
D/BluetoothInputDevice( 5399): onBluetoothStateChange: up=false
,D/BluetoothMap( 5399): onBluetoothStateChange: up=false
,I/ActivityManager(  935): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
E/BluetoothMap( 5399): 
E/BluetoothMap( 5399): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@10346a62
E/BluetoothMap( 5399): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 5399): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1940)
E/BluetoothMap( 5399): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 5399): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 5399): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 5399): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothSap( 5399): onBluetoothStateChange on: false
V/BluetoothSapService( 3109): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@1e7cbd3
D/wpa_supplicant( 1327): nl80211: Remove monitor interface: refcount=0
D/wpa_supplicant( 1327): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
,D/Messaging( 5312): ViewCache CreatePreload
,D/Messaging( 5312): ViewCache CreatePreloadOnlyMultipleOpsList
,I/ActivityManager(  935): Killing 4929:com.example.hello/u0a374 (adj 0): stop com.example.hello
,D/Process (  935): killProcessQuiet, pid=4929
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,D/Cust_MMSMS( 5312): _has_set_default_values_2=true
D/MsgPreferenceUtils( 5312): def_index: 0
,W/PackageSettings(  935): Skipping PackageSetting{15f9b5b0 com.test.thalitest/10366} due to missing metadata
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 97
D/MmsSmsV2Provider( 1564):  slotId = -1000
D/MmsSmsV2Provider( 1564): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 5312): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1564): sku_id=118
,D/wpa_supplicant( 1327): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1327): nl80211: Unsubscribe mgmt frames handle 0x888888dd08c2e989 (mode change)
I/wpa_supplicant( 1327): htc_wext_command_deinit +
I/wpa_supplicant( 1327): htc_wext_command_deinit -
I/wpa_supplicant( 1327): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1327): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 1327): p2p0: Removing interface p2p0
,D/wpa_supplicant( 1327): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1327): TDLS: Tear down peers
D/wpa_supplicant( 1327): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1327): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1327): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1327): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1327): EAPOL: External notification - portValid=0
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-TERMINATING 
D/Tethering(  935): interfaceLinkStateChanged wlan0, false
D/Tethering(  935): interfaceStatusChanged wlan0, false
D/WifiMonitor(  935): Disconnecting from the supplicant, no more events
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  935): handleMessage: E msg.what=147458
E/WifiStateMachine(  935): processMsg: SupplicantStoppingState
E/WifiStateMachine(  935):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 32 0
E/WifiStateMachine(  935): Supplicant connection lost
,I/ActivityManager(  935): Recipient 4929
,E/InputEventReceiver( 1400): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{2f0443a1 uid 10374 pid 4929} (c)'
I/WindowState(  935): WIN DEATH: Window{21669b5 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  935): Client connection lost with reason: 4
,W/ActivityManager(  935): Force removing ActivityRecord{33a53ff5 u0 com.example.hello/.MainActivity t8}: app died, no saved state,
,V/TransactionService( 5312): 1-Creating TransactionService
,D/BluetoothManagerService(  935): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  935): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothAdapter( 1800): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2d20d279
D/BluetoothAdapter( 1800): onBluetoothServiceDown: done
D/BluetoothAdapter( 5399): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@88757f3
D/BluetoothAdapter( 5399): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1564): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@23d0eb12
D/BluetoothAdapter( 1564): onBluetoothServiceDown: done
D/BluetoothAdapter( 2339): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2c5d1076
D/BluetoothAdapter( 2339): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3109): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@d2c6803
D/BluetoothAdapter( 3109): onBluetoothServiceDown: done
V/TransactionService( 5312): onStartCommand: 1
D/MmsSystemEventReceiver( 5312): unRegisterForConnectionStateChanges
,D/BluetoothAdapter( 1216): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@95fc0cb
D/BluetoothAdapter( 1216): onBluetoothServiceDown: done
D/BluetoothAdapter(  935): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1fb548bc
D/BluetoothAdapter(  935): onBluetoothServiceDown: done
V/TransactionService( 5312): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5312): Loading previous transactions.
D/BluetoothAdapter( 1583): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2608d47b
D/BluetoothAdapter( 1583): onBluetoothServiceDown: done
D/BluetoothAdapter( 3737): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@23e2d044
D/BluetoothAdapter( 3737): onBluetoothServiceDown: done
D/BluetoothManagerService(  935): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1fb548bc mBinding = false
D/BluetoothManagerService(  935): Sending unbind request.
,D/MediaProvider( 3849): [update][8]#1#
,I/art     (  935): Explicit concurrent mark sweep GC freed 37244(2MB) AllocSpace objects, 4(144KB) LOS objects, 33% free, 16MB/24MB, paused 1.891ms total 184.487ms
,I/wpa_ctrl(  935): [wpa_ctrl_close] ctrl=0x55958aa0c0,
I/wpa_ctrl(  935): [wpa_ctrl_close] ctrl=0x5595659630
,D/MsgPreferenceUtils( 5312): globalIndex = 1,
I/ActivityManager(  935): Force stopping com.example.hello appid=10374 user=0: pkg removed
D/MdProvGlob( 5147): remove item 101 (p2d14in305) for 15:android.intent.action.ANY_DATA_STATE
D/MediaProvider( 3849): [update][27]#1#,
D/MdScDataSum( 5122): [52d.1.] summary 118:p2 ignore
,D/MsgPreferenceUtils( 5312): phone state: true
D/MsgPreferenceUtils( 5312): sd state: false
D/MsgPreferenceUtils( 5312): vIndex = 0
,D/MediaScanner( 3849):  prescan time: 715ms
D/MediaScanner( 3849):     scan time: 981ms
,D/MediaScanner( 3849): postscan time: 9ms
D/MediaScanner( 3849):    total time: 1705ms
D/MediaScanner( 3849): -----------------------------------------------------------------
D/MediaScanner( 3849): firstscan(media) time: 713ms
D/MediaScanner( 3849): secondscan(non-media) time: 268ms
D/MediaScanner( 3849):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
,D/MediaScanner( 3849):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3849):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3849):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,W/ActivityManager(  935): Spurious death for ProcessRecord{32d7c062 4929:com.example.hello/u0a374}, curProc for 4929: null
,D/MediaProvider( 3849): [delete][24]
D/MediaProvider( 3849): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,E/WifiStateMachine(  935): setWifiState: disabled
,D/MdProvGlob( 5147): add item 101 (1:g3d1) for 15:android.intent.action.PRECISE_DATA_CONNECTION_STATE_CHANGED,
D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/AccFlag ( 1564): sku_id=118,
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/AccFlag ( 1564): device_type: 1
D/MediaProvider( 3849): [recoverParentNodes] - 0
D/MediaProvider( 3849): [update][17]
D/MediaScannerServiceEx( 3849): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3849): [updateImage]+
,D/BluetoothManagerService(  935): Bluetooth State Change Intent: 13 -> 10,
,W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/WifiStateMachine(  935): Enter handleNetworkDisconnect
,E/WifiStateMachine(  935): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
,I/FeedHostManager( 1627): [onResume],
I/FeedProviderManager( 1627): onResume
I/SocialFeedProvider( 1627): +onResume
I/SocialFeedProvider( 1627): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1627): -onResume
I/ConnectivityHelper( 1627): [getCurrentConnectionType] no network connection
D/MediaScannerServiceEx( 3849): [updateImage]-0
E/WifiStateMachine(  935): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/TransactionService( 5312): Force clearing mTransactionList
D/DotMatrix( 1334): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
I/bt-btif ( 3109): HAL bt_hal_cbacks->thread_evt_cb
D/DotMatrix( 1334): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1334): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
D/TransactionService( 5312): Force set service start id to 1
V/TransactionService( 5312): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 5312): unRegisterForConnectionStateChanges
,W/Settings( 4569): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI_ICON( 1216): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/Prism.ItemManager( 4856): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false,
I/IntentController( 1216): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,I/Prism.ItemManager( 4856): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  935): acquireWL(cd0fe4f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1800 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1800): Ignoring removeGeofence because network location is disabled.
,D/PMS     (  935): releaseWL(cd0fe4f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,W/Settings( 1800): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  935): Exit handleNetworkDisconnect
D/PMS     (  935): acquireWL(649306b): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 935 1000 null
E/WifiStateMachine(  935): [MLHD] Error! unhandled message 6 { when=-522ms what=147458 arg1=32 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  935): transitionTo: destState=InitialState
E/WifiStateMachine(  935): handleMessage: new destination call exit/enter
E/WifiStateMachine(  935): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  935): invokeExitMethods: SupplicantStoppingState
E/WifiStateMachine(  935): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  935): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,E/WifiStateMachine(  935): invokeEnterMethods: InitialState
D/TransactionService( 5312): stopSelfResult: true, mLastHandledServiceId: 1
,D/MediaScannerServiceEx( 3849): [1] scan finished
D/PMS     (  935): releaseWL(2817216d): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,I/art     ( 3109): System.exit called, status: 0
D/MediaProviderUtils( 3849): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3849): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3849): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3849): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3849): Process mounted intent for unmounted storage: /storage/ext_sd
,W/SystemReader(  935): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1766): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/PMS     (  935): acquireWL(2cc86847): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5508 1000 null
I/IntentController( 1216): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/StatusBarManagerService(  935): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  935): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  935): hiding MENU key
,D/PowerUsageList:PowerUsageHelper( 5508): MY_DEBUG = false
,D/LocalBluetoothProfileManager( 5399): setBluetoothStateOff
W/BluetoothEventManager( 5399): unregister mProfileBroadcastReceiver fail
D/NGFService( 3737): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3737): Bluetooth Adapter: OFF
D/FindExtension( 1627): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
E/JavaBinder(  935): !!! FAILED BINDER TRANSACTION !!!
D/AccTypeManager( 1766): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ThreadedRenderer( 1627): Defer allocateBuffers to drawing time
W/BroadcastQueue(  935): Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver},
W/BroadcastQueue(  935): android.os.TransactionTooLargeException
W/BroadcastQueue(  935): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  935): 	at android.os.BinderProxy.transact(Binder.java:504)
W/BroadcastQueue(  935): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:921)
W/BroadcastQueue(  935): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:254)
W/BroadcastQueue(  935): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:989)
W/BroadcastQueue(  935): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:152)
W/BroadcastQueue(  935): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  935): 	at android.os.Looper.loop(Looper.java:155)
W/BroadcastQueue(  935): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue(  935): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
I/Prism.ItemManager( 1627): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/InputMethodManagerService(  935): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/Prism.ItemManager( 1627): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/TetherPref( 5399): persistRestoreBluetoothState false
I/QuickSettingWifi( 1216): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
W/InputMethodManagerService(  935): Got RemoteException sending setActive(false) notification to pid 4929 uid 10374
D/StatusBarManagerService(  935): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  935): Enable input method client, pid=1627
,D/AccTypeManager( 1766): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1564): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/BluetoothAdapter( 1216): 803743351: getState() :  mService = null. Returning STATE_OFF
I/QuickSettingBluetooth( 1216): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,E/ExternalAccountType( 1766): Unsupported attribute readOnly,
,I/ActivityManager(  935): Recipient 3109
,W/ActivityManager(  935): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 1000ms
W/ActivityManager(  935): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
,I/ActivityManager(  935): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=5560 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,D/MediaScannerServiceEx( 3849): [disAliveExtStorageRows]+131073
W/ActivityManager(  935): Spurious death for ProcessRecord{39ff056d 5560:com.android.bluetooth/1002}, curProc for 3109: null
D/MdProvGlob( 5147): remove item 101 (p3in150) for 15:android.intent.action.ANY_DATA_STATE
,D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
,V/TransactionService( 5312): Destroying TransactionService
V/TransactionService( 5312): 4-Handling incoming message: { when=0 what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MediaProvider( 3849): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3849): [update][4]#1#
D/PowerUsageService( 5508): repeat time = 1450199924719
D/MdScDataSum( 5122): [52d.1.4.] summary 118:p2 ignore
,D/WISPrService( 5399): >>>>>WISPrService start isConnected = false<<<<<
W/ResourcesManager(  935): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/PackageManager(  935): Unable to load service info ResolveInfo{8176a28 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  935): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  935): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  935): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  935): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  935): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  935): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  935): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  935): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  935): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  935): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  935): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/WISPrService( 5399): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/StatusBarManagerService(  935): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  935): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  935): hiding MENU key
,D/WeatherUtility( 1538): Weather sync is On
,I/ActivityManager(  935): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5583 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
,I/art     (  935): Explicit concurrent mark sweep GC freed 10025(628KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 6.709ms total 226.204ms
,D/WSP     ( 1538): [Receiver] auto sync agent, auto sync is enabled, reset schedule,
D/MediaProvider( 3849): [update][59]#0#
W/asset   (  935): Copying FileAsset 0x5595c96f30 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/MediaScannerServiceEx( 3849): [disAliveExtStorageRows]--1, 0
D/MediaProviderUtils( 3849): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3849): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3849): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3849): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3849): Process mounted intent for unmounted storage: /storage/usb
,W/ResourcesManager( 5560): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/MediaScannerServiceEx( 3849): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3849): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3849): [update][19]#1#
,D/MdProvGlob( 5147): remove item 101 (p2in15) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 5122): [52d.f.] summary 118:p1 ignore
,D/MdProvGlob( 5147): remove item 101 (p2in13) for 15:android.intent.action.ANY_DATA_STATE
,D/MediaProvider( 3849): [update][29]#0#
,D/MediaScannerServiceEx( 3849): [disAliveExtStorageRows]--1, 0
,D/AdapterServiceConfig( 5560): Adding HeadsetService
D/AdapterServiceConfig( 5560): Adding A2dpService
D/AdapterServiceConfig( 5560): Adding HidService,
D/AdapterServiceConfig( 5560): Adding HealthService
D/AdapterServiceConfig( 5560): Adding PanService
D/AdapterServiceConfig( 5560): Adding GattService
,V/BluetoothPbapReceiver( 5560): ***********action = android.bluetooth.adapter.action.STATE_CHANGED,
,V/BluetoothPbapReceiver( 5560): ***********state = 10
D/MdProvGlob( 5147): remove item 101 (p2in27) for 15:android.intent.action.ANY_DATA_STATE
,E/BluetoothMasService( 5560): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/PMS     (  935): acquireWL(1eb01471): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5399 1000 null
,W/ContextImpl( 5399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/BluetoothMasService( 5560): Add permission for SmsProvider.,
,D/BluetoothManagerService(  935): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  935): java.lang.Throwable: stack dump
W/System.err(  935): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  935): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  935): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  935): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothManagerService(  935): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e086ad:true
I/ActivityManager(  935): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5608 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
V/BluetoothMasService( 5560): Starting MAS instances
,D/BluetoothAdapter( 5560): 468594778: getState() :  mService = null. Returning STATE_OFF
,I/MailMessageReceiver( 5560): reg:com.android.bluetooth.btservice.AdapterApp@36c2328b with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@1e980f68
,D/PMS     (  935): releaseWL(1eb01471): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/MdProvGlob( 5147): remove item 101 (p2in26) for 15:android.intent.action.ANY_DATA_STATE
I/PowerUsageList:PowerUsageHelper( 5508): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/MailManager( 5560): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@1e980f68
,D/PMS     (  935): acquireWL(24d8562e): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5399 1000 null
V/EmailUtils( 5560): Manager Instance is not NULL
D/HtcBtWidget_BTWidgetProvider( 5424): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 5424): updateWidget(context) for widget: 
,I/ActivityManager(  935): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5630 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/WeatherUtility( 5583): Weather sync is On
,D/JobSchedulerService(  935): Receieved: android.intent.action.PACKAGE_REMOVED
,D/MdProvGlob( 5147): remove item 101 (p2in49) for 15:android.intent.action.ANY_DATA_STATE
,D/PowerUsageList:BatterySipperExt( 5508): gen(), null == sipper.uidObj, userId = 0
,E/WifiTrafficPoller(  935): TRAFFIC_STATS_POLL false Token 15 num clients 8
,I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
D/TaskPersister(  935): removeObsoleteFile: deleting file=8_task.xml
D/DockEventReceiver( 5399): finishStartingService: stopping service
D/PMS     (  935): releaseWL(24d8562e): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 15
,W/ResourcesManager( 5608): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/WeatherRequest( 5583): request cur loc, but there is no sys cur
W/Settings( 5583): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MdProvGlob( 5147): remove item 101 (p2in31) for 15:android.intent.action.ANY_DATA_STATE
,I/ActionCombine( 5583): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/RemoteViews( 1627): reapply : com.htc.widget.weatherclock 11 17
,D/Process (  935): killProcessQuiet, pid=5024
,I/ActivityManager(  935): Killing 5024:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/Tethering(  935): interfaceRemoved wlan0
E/Tethering(  935): attempting to remove unknown iface (wlan0), ignoring
,I/ActivityManager(  935): Recipient 5024,
,W/OpenGLRenderer( 1627): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,D/NfcHandover( 1583): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
,I/ActivityManager(  935): Killing 5055:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  935): killProcessQuiet, pid=5055
D/Tethering(  935): interfaceLinkStateChanged p2p0, false
D/Tethering(  935): interfaceStatusChanged p2p0, false
,E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
,D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40,
,E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error,
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...,
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
,E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/PowerUsageList:PowerUsageHelper( 5508): bulkInsertData(), Exception: 
E/PowerUsageList:PowerUsageHelper( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/PowerUsageList:PowerUsageHelper( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/PowerUsageList:PowerUsageHelper( 5508): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/PowerUsageList:PowerUsageHelper( 5508): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/PowerUsageList:PowerUsageHelper( 5508): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/PowerUsageList:PowerUsageHelper( 5508): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
E/PowerUsageList:PowerUsageHelper( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.bulkInsert(SmartSyncProvider.java:365)
E/PowerUsageList:PowerUsageHelper( 5508): 	at android.content.ContentProvider$Transport.bulkInsert(ContentProvider.java:260)
E/PowerUsageList:PowerUsageHelper( 5508): 	at android.content.ContentResolver.bulkInsert(ContentResolver.java:1289)
E/PowerUsageList:PowerUsageHelper( 5508): 	at com.htc.htcpowermanager.battery.PowerUsageHelper.bulkInsertData(PowerUsageHelper.java:1814)
E/PowerUsageList:PowerUsageHelper( 5508),: 	at com.htc.htcpowermanager.battery.PowerUsageService.calcPower(PowerUsageService.java:286)
E/PowerUsageList:PowerUsageHelper( 5508): 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:110)
E/PowerUsageList:PowerUsageHelper( 5508): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PowerUsageList:PowerUsageHelper( 5508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PowerUsageList:PowerUsageHelper( 5508): 	at android.os.Looper.loop(Looper.java:155)
E/PowerUsageList:PowerUsageHelper( 5508): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PowerUsageService( 5508): bulk insert error
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549),
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
,E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
,E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128),
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	,at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818),
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
,E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	,at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): ,	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	,at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	,at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	,at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	,at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	,at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	,at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
,E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	,at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	,at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
,E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager(  935): Recipient 5055
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(,ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at jav,a.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
D/Tethering(  935): interfaceRemoved p2p0
E/Tethering(  935): attempting to remove unknown iface (p2p0), ignoring
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transp,ort.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
I/ActivityManager(  935): Killing 5198:com.android.chrome/u0a96 (adj 15): empty #17
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
D/Process (  935): killProcessQuiet, pid=5198
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(,AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
D/HtcAdjCursorFactory( 5630): Set CursorWindow size to: 4194304 KB, Tid: 5651
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
I/EASAppSvc( 5630): [ NA ]onCreate
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLit,eConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 5630): Failed to open database '/data/user/0/com.htc.android.mail/databases/mail.db'.
E/SQLiteDatabase( 5630): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5630): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5630): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5630): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5630): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5630): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5630): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5630): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5630): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5630): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteDatabase( 5630): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteDatabase( 5630): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteDatabase( 5630): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5630): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5630): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5630): 	at android.os.Binder.execTransact(Binder.java:454)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteOpenHelper( 5630): Couldn't open mail.db for writing (will try read-only):
E/SQLiteOpenHelper( 5630): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5630): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5630): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5630): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5630): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5630): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5630): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5630): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5630): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5630): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteOpenHelper( 5630): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteOpenHelper( 5630): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteOpenHelper( 5630): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5630): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5630): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteOpenHelper( 5630): 	at android.os.Binder.execTransact(Binder.java:454)
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
W/SQLiteOpenHelper( 5630): Opened mail.db in read-only mode
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQ,LiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTi,meReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: execut,eNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
I/VersionUtil( 5630): [ NA ]setIsFOTAing: true
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at an,droid.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
I/VersionUtil( 5630): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5630): [ NA ]setIsFOTAing: false
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( ,5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteD,atabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO sm,artsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	,at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	,at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	,at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
,E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	,at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
,E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDataba,se( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWo,rker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5508): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5508): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteDatabase( 5508): Error inserting ...
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5508): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5508): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5508): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5508): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5508): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5508): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager(  935): Recipient 5198
E/SQLiteLog( 5508): (3850) statement aborts at 32: [SELECT * FROM smartsync_golden_tue ORDER BY date] disk I/O error
E/SQLiteDBG( 5508): func: nativeExecuteForCursorWindow, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55955eaf40
E/SQLiteQuery( 5508): exception: disk I/O error (code 3850); query: SELECT * FROM smartsync_golden_tue ORDER BY date
D/PMS     (  935): releaseWL(2cc86847): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  935): Killing 5232:com.google.android.apps.plus/u0a167 (adj 15): empty #17,
D/Process (  935): killProcessQuiet, pid=5232
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  935): Recipient 5232
,D/EmailUtils( 5560): ============NULL aList========,
,V/EmailUtils( 5560): <-getEmailAccountIdList,
V/AlarmManager(  935): sending alarm PendingIntent{23e14619: PendingIntentRecord{3a9ca6de com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1450199025868, Int=0
V/BluetoothMasService( 5560): onCreate: mIsEmailEnabled: true
,D/WifiService(  935): New client listening to asynchronous messages
E/WifiTrafficPoller(  935): ADD_CLIENT: 9
,W/EAS_NetworkUtil( 5630): [ NA ]getNetworkInfo: NetworkInfo is null
,I/ActivityManager(  935): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5665 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ORMLib  ( 5339): put()
,E/SQLiteLog( 5339): (3850) statement aborts at 25: [UPDATE TaskSource SET SupportedColumns=?,IsTimePrecision2Sec=?,Description=?,PackageName=?,ServiceClassPath=?,last_update=?,VersionName=?,VersionCode=?,AccountType=? WHERE _id=2] disk 
,E/SQLiteDBG( 5339): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.task/databases/MyDB.db, handle: 0x55955ec030
D/BluetoothMasReceiver( 5560): Bluetooth STATE CHANGED to 10
E/DBProvider( 5339): disk I/O error (code 3850)
W/System.err( 5339): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/System.err( 5339): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
,W/System.err( 5339): ,	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
W/System.err( 5339): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/System.err( 5339): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 5339): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1654)
W/System.err( 5339): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1600)
W/System.err( 5339): 	,at com.htc.task.dm.DBProvider.update(DBProvider.java:552)
V/BluetoothMasService( 5560): onDestroy: mIsEmailEnabled: true
W/System.err( 5339): 	at com.htc.task.APICProviderDecorator.update(APICProviderDecorator.java:490)
W/System.err( 5339): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
W/System.err( 5339): 	at android.content.ContentProviderClient.update(ContentProviderClient.java:251)
W/System.err( 5339): 	at com.htc.orm.Model.put(Model.java:143)
W/System.err( 5339): 	at com.htc.orm.Model.put(Model.java:170)
W/System.err( 5339): 	at com.htc.task.sm.PluginUpdatedServiceConnection.updateDB(PluginUpdatedServiceConnection.java:195)
W/System.err( 5339): 	at com.htc.task.sm.PluginUpdatedServiceConnection$1.run(PluginUpdatedServiceConnection.java:125)
W/System.err( 5339): 	at java.lang.Thread.run(Thread.java:818)
I/EASAppSvc( 5630): [ NA ]onDestroy
V/BluetoothSapReceiver( 5560): SapReceiver onReceive 
I/EASAppSvc( 5630): [ NA ]> uninitEASService
I/ActivityManager(  935): Killing 4827:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
V/BluetoothSapReceiver( 5560): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5560):  Bluetooth Adapter state = 10
V/BluetoothSapReceiver( 5560): startService = false
,I/EASRequestController( 5630): [ NA ]release
I/EASAppSvc( 5630): [ NA ]onCreate
D/Process (  935): killProcessQuiet, pid=4827
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/VersionUtil( 5630): [ NA ]setIsFOTAing: true
,I/VersionUtil( 5630): [ NA ]onUpgrade: current version=100, latest version=100
,I/VersionUtil( 5630): [ NA ]setIsFOTAing: false
,D/EASPublicBinder( 5630): [ NA ]release
,D/TaskBinder( 5630): [ NA ]release
D/TaskBinder( 5630): [ NA ]release
I/EASAppSvc( 5630): [ NA ]< uninitEASService
,I/ActivityManager(  935): Recipient 4827
,I/Prism.ItemManager( 4856): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 4856): loadItems() com.htc.launcher.pageview.WidgetManager@3fe3640a +
I/Prism.WidgetManager( 4856): onLoadItems() +
,D/AuthorizationBluetoothService( 1845): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  935): Killing 4856:com.htc.sense.news/u0a74 (adj 15): empty #17
,D/Process (  935): killProcessQuiet, pid=4856
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/SQLiteDatabase( 5608): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 5608): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5608): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5608): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5608): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5608): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5608): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5608): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5608): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5608): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5608): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5608): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 5608): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 5608): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5608): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5608): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5608): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5608): 	at com.htc.mediamanager.providers.media.MMPScanner.syncMP2MMP(MMPScanner.java:206)
E/SQLiteDatabase( 5608): 	at com.htc.mediamanager.providers.media.MMPScanService$ServiceHandler.handleMessage(MMPScanService.java:426)
E/SQLiteDatabase( 5608): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5608): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5608): 	at com.htc.mediamanager.providers.media.MMPScanService.run(MMPScanService.java:352)
E/SQLiteDatabase( 5608): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 5608): Couldn't open MMexternal.db for writing (will try read-only):,
E/SQLiteOpenHelper( 5608): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5608): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5608): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5608): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5608): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5608): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5608): 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5608): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5608): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5608): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5608): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 5608): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 5608): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5608): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5608): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 5608): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 5608): 	at com.htc.mediamanager.providers.media.MMPScanner.syncMP2MMP(MMPScanner.java:206),
E/SQLiteOpenHelper( 5608): 	at com.htc.mediamanager.providers.media.MMPScanService$ServiceHandler.handleMessage(MMPScanService.java:426)
E/SQLiteOpenHelper( 5608): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5608): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteOpenHelper( 5608): 	at com.htc.mediamanager.providers.media.MMPScanService.run(MMPScanService.java:352)
E/SQLiteOpenHelper( 5608): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5608): (14) cannot open file at line 28586 of [9491ba7d73],
E/SQLiteLog( 5608): (14) os_unix.c:28586: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 5608): (14) statement aborts at 1: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 5608): func: executeOneRowQuery, errno: 30, error msg: Read-only file system, path: /data/data/com.htc.album/databases/MMexternal.db, handle: 0xac3ff418
,W/System.err( 5608): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,W/System.err( 5608): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 5608): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:626)
W/System.err( 5608): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:652)
W/System.err( 5608): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 5608): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 5608): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 5608): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:927)
,W/System.err( 5608): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:241)
W/System.err( 5608): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
W/System.err( 5608): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
W/System.err( 5608): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
W/System.err( 5608): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5608): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5608): 	at android.content.ContentResolver.query(ContentResolver.java:491)
W/System.err( 5608): 	at android.content.ContentResolver.query(ContentResolver.java:435)
,W/System.err( 5608): 	at com.htc.mediamanager.providers.media.MMPScanner.syncMP2MMP(MMPScanner.java:206)
W/System.err( 5608): 	at com.htc.mediamanager.providers.media.MMPScanService$ServiceHandler.handleMessage(MMPScanService.java:426)
W/System.err( 5608): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5608): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 5608): 	at com.htc.mediamanager.providers.media.MMPScanService.run(MMPScanService.java:352)
W/System.err( 5608): 	at java.lang.Thread.run(Thread.java:818)
,I/Prism.ItemManager( 1627): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1627): loadItems() com.htc.launcher.pageview.WidgetManager@22942605 +
I/Prism.WidgetManager( 1627): onLoadItems() +
,D/ORMLib  ( 5339): put(),
,E/SQLiteLog( 5339): (3850) statement aborts at 25: [UPDATE TaskSource SET SupportedColumns=?,IsTimePrecision2Sec=?,Description=?,PackageName=?,ServiceClassPath=?,last_update=?,VersionName=?,VersionCode=?,AccountType=? WHERE _id=3] disk 
E/SQLiteDBG( 5339): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.task/databases/MyDB.db, handle: 0x55955ec030
,E/DBProvider( 5339): disk I/O error (code 3850)
,W/System.err( 5339): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/System.err( 5339): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/System.err( 5339): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
W/System.err( 5339): 	,at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754),
W/System.err( 5339): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 5339): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1654)
W/System.err( 5339): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1600)
W/System.err( 5339): 	at com.htc.task.dm.DBProvider.update(DBProvider.java:552)
W/System.err( 5339): 	at com.htc.task.APICProviderDecorator.update(APICProviderDecorator.java:490)
W/System.err( 5339): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
W/System.err( 5339): 	at android.content.ContentProviderClient.update(ContentProviderClient.java:251)
W/System.err( 5339): 	at com.htc.orm.Model.put(Model.java:143)
W/System.err( 5339): 	at com.htc.orm.Model.put(Model.java:170)
W/System.err( 5339): 	at com.htc.task.sm.PluginUpdatedServiceConnection.updateDB(PluginUpdatedServiceConnection.java:195)
W/System.err( 5339): 	at com.htc.task.sm.PluginUpdatedServiceConnection$1.run(PluginUpdatedServiceConnection.java:125)
W/System.err( 5339): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  935): Recipient 4856,
,I/ActivityManager(  935): Waited long enough for: ServiceRecord{3c609848 u0 com.google.android.gms/.config.ConfigFetchService},
V/AlarmManager(  935): sending alarm PendingIntent{23cc9f51: PendingIntentRecord{2050b3b6 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=67405, Int=0
,W/EAS_NetworkUtil( 5630): [ NA ]getNetworkInfo: NetworkInfo is null
,I/EASAppSvc( 5630): [ NA ]onDestroy
I/EASAppSvc( 5630): [ NA ]> uninitEASService
,I/ActivityManager(  935): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5698 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a

```
