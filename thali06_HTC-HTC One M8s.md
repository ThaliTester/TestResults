#### Test 623288225dc9f88_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
I/ActivityManager(  964): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5547 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
--------- beginning of main
W/Settings( 5504): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5504): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/GAV2    ( 5302): Thread[GAThread,5,main]: No campaign data found.
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5504, uid=10072, userID:0
W/ResourcesManager( 5547): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5547): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5547): VM with version 2.1.0 has multidex support
I/MultiDex( 5547): install
I/MultiDex( 5547): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 5504): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5504): [1] 2.run: Finished loading 1 libraries.
I/ActivityManager(  964): Killing 5002:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=5002
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/WifiService(  964): Client connection lost with reason: 4
I/ActivityManager(  964): Recipient 5002
D/Finsky  ( 5504): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4177): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  964): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5580 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/PackageBroadcastService( 4177): Null package name or gms related package.  Ignoreing.
D/PMS     (  964): acquireWL(221448ee): PARTIAL_WAKE_LOCK  Icing 0x1 4177 10024 WorkSource{10024 com.google.android.gms}
V/JNIHelp ( 5547): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/Prism.ItemManager( 1540): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1540): loadItems() com.htc.launcher.pageview.WidgetManager@1c485204 +
I/Prism.WidgetManager( 1540): onLoadItems() +
D/Finsky  ( 5504): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ResourcesManager( 5580): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ActivityThread( 5547): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5547): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d0c27ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5547): Installed default security provider GmsCore_OpenSSL
W/ResourcesManager( 1540): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  964): Waited long enough for: ServiceRecord{31ec00ad u0 com.htc.club/com.mcrm.autonotification.NotificationService}
E/cutils-trace( 5577): Error opening trace file: Permission denied (13)
D/Process (  964): killProcessQuiet, pid=5160
I/ActivityManager(  964): Killing 5160:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/Icing   ( 4177): Storage manager: low false usage 2.04MB avail 5.77GB capacity 7.95GB
W/Icing   ( 4177): Received bad json for section weights override -- ignoring.
D/CustomizationManager( 5577): ====startRecUseTime====
D/htc.customization.log.level( 5577):  is 
W/CustomizationLogLevel( 5577): Level value is invalid, use default level 2
W/Icing   ( 4177): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4177): Received bad json for section weights override -- ignoring.
W/Icing   ( 4177): Received bad json for corpus context scoring override -- ignoring.
I/ActivityManager(  964): Recipient 5160
D/CustomizationManager( 5577):  Read ACC file spent 0.040 (s)
D/CIDMapFileReader( 5577): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5577): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5577): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5577): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5577): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5577): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5577): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5577): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5577): Parsing tag category name = system
I/CustomizationCIDLoader( 5577): Parsing tag category name = application
I/CustomizationCIDLoader( 5577): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5577): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5577): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5577): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5577): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5577): add string-array item, value = 42507
I/CustomizationCIDLoader( 5577): add string-array item, value = 21902
I/CustomizationCIDLoader( 5577): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5577): add string-array item, value = 23420
I/CustomizationCIDLoader( 5577): add string-array item, value = 22299
I/CustomizationCIDLoader( 5577): add string-array item, value = 24002
I/CustomizationCIDLoader( 5577): add string-array item, value = 23210
I/CustomizationCIDLoader( 5577): add string-array item, value = 23205
I/CustomizationCIDLoader( 5577): add string-array item, value = 23806
I/CustomizationCIDLoader( 5577): add string-array item, value = 23430
I/CustomizationCIDLoader( 5577): add string-array item, value = 23408
I/CustomizationCIDLoader( 5577): add string-array item, value = 27205
I/CustomizationCIDLoader( 5577): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5577): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5577): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5577): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5577): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5577): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5577): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5577): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5577): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5577): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5577): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5577): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5577):  Read CID file spent 0.081 (s)
D/CustomizationManager( 5577):  All configurations done spent 0.082 (s)
W/ResourcesManager( 1540): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5577 on display 0
D/PMS     (  964): acquireHCC(6efc18f): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 964 1000 null
D/PMS     (  964): acquireHCC(4a92c1c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 964 1000 null
D/PMS     (  964): acquireWL(38b0e7ab): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 964 1000 null
I/art     ( 1874): Explicit concurrent mark sweep GC freed 11107(546KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 1.521ms total 39.166ms
I/FeedHostManager( 1540): [onPause]
I/FeedProviderManager( 1540): onPause
I/FeedHostManager( 1540): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@30645bd9
I/SocialFeedProvider( 1540): +onPause
I/SocialFeedProvider( 1540): -onPause
I/AnimationUtil(  964): isHTCRecent(ThaliTest/Recent screens.)/9
W/HtcSystemUPManager(  964): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5630 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/asset   ( 1540): Copying FileAsset 0x5593732bd0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
E/Icing   ( 4177): Loading extension by file descriptor -1 failed
D/StatusBarManagerService(  964): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
I/TrimMemoryManager( 1540): [trimMemory] 20
D/PMS     (  964): acquireWL(2e0a2c7f): PARTIAL_WAKE_LOCK  *alarm* 0x1 964 1000 WorkSource{10072}
V/AlarmManager(  964): sending alarm PendingIntent{1d1dd44c: PendingIntentRecord{3b2abc95 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457577239095, Int=0
D/PMS     (  964): releaseWL(2e0a2c7f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
D/Finsky  ( 5504): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/Prism.WidgetManager( 1540): onLoadItems() -
,I/Prism.ItemManager( 1540): loadItems() com.htc.launcher.pageview.WidgetManager@1c485204 -
,D/PhoneApp( 1483): EVENT_QUERY_MO_PACKAGES
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneApp( 1483): -- N1 =0
,D/PhoneApp( 1483): -- N2 =0,
,D/PhoneApp( 1483): -- N3 =0
,I/GLSUser ( 1874): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1874): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1874): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1874): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  964): acquireWL(15e4e87c): PARTIAL_WAKE_LOCK  AsyncService 0x1 5580 10167 null
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  964): acquireWL(1912095a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5580 10167 null
,D/PMS     (  964): releaseWL(15e4e87c): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/UpdateIcingCorporaServi( 5449): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  964): releaseWL(1912095a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,I/WebViewFactory( 5630): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,W/Finsky  ( 5504): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1874): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1874): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1874): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1874): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Prism.PackageStateRece_( 1540): action: android.intent.action.PACKAGE_ADDED
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[PluginManager]RegisterService( 1454): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest,
,I/[PluginManager]RegisterService( 1454): handle notify Blinkfeed plugin client changed
,I/LibraryLoader( 5630): Time to load native libraries: 19 ms (timestamps 3203-3222)
,I/LibraryLoader( 5630): Expected native library version number "",actual native library version number ""
,I/ActivityManager(  964): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5668 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,V/Finsky  ( 5504): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/WebViewChromiumFactoryProvider( 5630): Binding Chromium to main looper Looper (main, tid 1) {23b09188}
I/LibraryLoader( 5630): Expected native library version number "",actual native library version number ""
,I/art     (  422): Explicit concurrent mark sweep GC freed 8641(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 169us total 18.553ms,
,I/chromium( 5630): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/art     (  422): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 136us total 16.109ms
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  422): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 138us total 16.627ms,
I/BrowserStartupController( 5630): Initializing chromium process, singleProcess=true
W/art     ( 5630): Attempt to remove local handle scope entry from IRT, ignoring
,I/UpdateIcingCorporaServi( 5449): UpdateCorporaTask done [took 166 ms] updated apps [took 165 ms] 
,D/Process (  964): killProcessQuiet, pid=5186
,I/ActivityManager(  964): Killing 5186:com.htc.task.gtask/u0a66 (adj 15): empty #17
E/SysUtils( 5630): ApplicationContext is null in ApplicationStatus
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/GLSUser ( 1874): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1874): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1874): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1874): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/chromium( 5630): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5630): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5630): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5630): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5630): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5630): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5630): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5630): Local Branch: 
I/Adreno-EGL( 5630): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5630): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5630):                  d74aa161a12b9c6fc6332151
I/ActivityManager(  964): Recipient 5186
W/System.err(  964): java.lang.Throwable: stack dump
D/BluetoothManagerService(  964): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28f654dc:true
W/System.err(  964): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  964): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  964): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 5630): 488828167: getState() :  mService = null. Returning STATE_OFF
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4177, uid=10024, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4177, uid=10024, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4177, uid=10024, userID:0
I/CheckinService( 4177): Done disabling old GoogleServicesFramework version
V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DeviceManagement( 5668): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5668 dbg=false s=true
I/DeviceManagement( 5668): PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
I/ActivityManager(  964): Killing 5245:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=5245
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/Icing   ( 4177): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  964): Recipient 5245
I/ActivityManager(  964): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5706 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
I/Icing   ( 4177): Internal init done: storage state 0
D/AutoSetting( 1454): service - handleMessage() stop self
I/Icing   ( 4177): Post-init done
I/Icing   ( 4177): updateResources: need to parse f{com.google.android.gms}
D/AutoSetting( 1454): service - handleMessage() quit looper
D/AutoSetting( 1454): service - onDestroy() END
W/art     ( 5630): Attempt to remove local handle scope entry from IRT, ignoring
D/PMS     (  964): releaseWL(221448ee): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
D/HtcCupdReceiver(Provider)( 5706):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  964): Killing 3620:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=3620
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
W/AwContents( 5630): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5630): CordovaWebView is running on device made by: HTC
I/art     (  964): Explicit concurrent mark sweep GC freed 26392(1479KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.443ms total 148.222ms
I/ClockController( 1210): schedule update now=1457577240051 next=59949
I/Clock   ( 1210): updateClock:03:34 Europe/Warsaw
I/Clock   ( 1210): updateClock:03:34 Europe/Warsaw
I/Clock   ( 1210): updateClock:03:34 Europe/Warsaw
I/ActivityManager(  964): Recipient 3620
D/PMS     (  964): acquireWL(f1c8136): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000}
V/AlarmManager(  964): sending alarm PendingIntent{445a837: PendingIntentRecord{1c7391a4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=73906, Int=0
W/art     ( 5630): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5630): Attempt to remove local handle scope entry from IRT, ignoring
W/Finsky  ( 5504): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/PackageBroadcastService( 4177): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 4177): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4177): Loading module APK com.google.android.play.games,
D/PMS     (  964): releaseWL(f1c8136): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1210): Weather sync is On
,D/PMS     (  964): acquireWL(c290d3): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4177 10024 null
,W/WeatherTimeKeeper( 1210): [refreshWeatherData] no weather data,
,W/chromium( 5630): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,E/AndroidHttpClient( 5504): Leak found
E/AndroidHttpClient( 5504): java.lang.IllegalStateException: AndroidHttpClient created and never closed,
E/AndroidHttpClient( 5504): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5504): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5504): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5504): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5504): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5504): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5504): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5504): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5504): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5504): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5504): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5504): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5504): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5504): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5504): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5504): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/FindExtension( 5630): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 5630): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@16071ad0, mServedView=org.apache.cordova.engine.SystemWebView{1811fac9 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3a8735ce,
,I/InputMethodManagerService(  964): Disable input method client, pid=1540
D/StatusBarManagerService(  964): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  964): Enable input method client, pid=5630
,I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +1s515ms
I/PhoneStatusBar( 1210): setImeWindowStatus(false,false)
,D/PMS     (  964): releaseWL(38b0e7ab): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ConfigFetchService( 4177): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 4177): launchTask
D/PMS     (  964): acquireWL(28b0abd4): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4177 10024 WorkSource{10366 com.test.thalitest}
,D/PMS     (  964): releaseWL(c290d3): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  964): acquireWL(218bf17d): PARTIAL_WAKE_LOCK  Icing 0x1 4177 10024 WorkSource{10024 com.google.android.gms},
,D/ChimeraCfgMgr( 4177): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4177): Module APK com.google.android.play.games already loaded
,D/PMS     (  964): releaseWL(218bf17d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4177): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/XT9_C   ( 1353): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1353): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1353): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1353): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/Vision  ( 4177): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 4177): Failed to find package metadata for com.test.thalitest
D/Vision  ( 4177): No vision deps
,V/ConfigFetchTask( 4177): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WKcWMWvCU23ME-060oMI-0Nt2IjOb3iC_tLRYeRUCexn4OtPmmJcXEgqD3ZCQtJ-bFpFS_Ud9Gl0JMrv656wJP4FJRw9Yser-Q7_IOhdj7HzT8Olja7A3gGIHINz5t70wYo6olADobN6Ier3TB-mXNIhOx9wtE1MCFa8SbOLKn9wnkIVvfXavfqa9XQEjp-EPn0pB_
,W/BindingManager( 5630): Cannot call determinedVisibility() - never saw a connection for the pid: 5630,
I/GoogleURLConnFactory( 4177): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  964): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5748 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/PeopleContactsSync( 4177): CP2 sync disabled
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4177, uid=10024, userID:0
,D/libc    ( 4177): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4177): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4177): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4177): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4177): [NET] android_getaddrinfo_proxy+
D/libc    ( 4177): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 4177): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4177): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 4177): fetch service done; releasing wakelock
,D/PMS     (  964): releaseWL(28b0abd4): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10366 com.test.thalitest}
,I/ConfigFetchService( 4177): stopping self
,I/Prism.ItemManager( 1540): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1540): loadItems() com.htc.launcher.pageview.WidgetManager@1c485204 +
I/Prism.WidgetManager( 1540): onLoadItems() +
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1874): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1874): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1874): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1874): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/JsMessageQueue( 5630): Set native->JS mode to OnlineEventsBridgeMode,
,W/BaseAppContext( 4177): Using Auth Proxy for data requests.
,W/BaseAppContext( 4177): Using Auth Proxy for data requests.
,W/Finsky  ( 5504): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5504): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,W/BaseAppContext( 4177): Using Auth Proxy for data requests.
,D/PMS     (  964): releaseHCC(6efc18f): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  964): releaseHCC(4a92c1c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/BaseAppContext( 4177): Using Auth Proxy for data requests.
,D/Finsky  ( 5504): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,W/BaseAppContext( 4177): Using Auth Proxy for data requests.
,D/Finsky  ( 5504): [1] DailyHygiene.reschedule: Scheduling new run in 96 minutes (failures=3)
,W/BaseAppContext( 4177): Using Auth Proxy for data requests.
,D/DeviceConnectionService( 1822): client connected with version: 7571000
D/Process (  964): killProcessQuiet, pid=5075
,I/ActivityManager(  964): Killing 5075:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/Prism.WidgetManager( 1540): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1540): onLoadItems() -
I/Prism.ItemManager( 1540): loadItems() com.htc.launcher.pageview.WidgetManager@1c485204 -
,I/HtcModeClient( 3108): handler message = 4011,
E/HtcModeClient( 3108): Check connection and retry 7 times.
,I/ActivityManager(  964): Recipient 5075
,D/Process (  964): killProcessQuiet, pid=5344
I/ActivityManager(  964): Killing 5344:com.htc.calendar/u0a10 (adj 15): empty #18
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 5344
,D/jxcore_app_log( 5630): JniHelper::setJavaVM(0xab5f68f8), pthread_self() = -1399774080,
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5630): load: ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5630):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5630):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5630):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5630):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5630): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ebed800 added. We now have 1 listener(s)
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630): setBluetoothMacAddress: 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5630): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"},
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5630): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e39742c added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5630): addListener: New listener added - the number of listeners is now 1
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5630): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved",
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5630): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
D/WifiService(  964): New client listening to asynchronous messages
E/WifiTrafficPoller(  964): ADD_CLIENT: 7
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5630): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5630): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5630): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5630): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/GAv4    ( 5748): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5748):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5748):   adb logcat -s GAv4
,W/GAv4    ( 5748): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5748): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5748): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5748): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45,
,D/VoldConnector(  964): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 5748): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache,
,D/PMS     (  964): acquireWL(173b9788): PARTIAL_WAKE_LOCK  AsyncService 0x1 5580 10167 null
,D/PMS     (  964): releaseWL(173b9788): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  964): acquireWL(28850d46): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5580 10167 null
,D/PMS     (  964): releaseWL(28850d46): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,W/ResourcesManager( 5748): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5748): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5748): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/ChimeraCfgMgr( 4177): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4177): Module APK com.google.android.play.games already loaded
,W/System  ( 5748): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5748): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1874): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1874): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/UpdateIcingCorporaServi( 5449): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,V/GmsCoreStatsServiceLauncher( 4177): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 4636): callingUid 10024, callindPid: 4636,
,W/art     ( 4177): Suspending all threads took: 7.618ms,
E/MDM     ( 1822): [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4177, uid=10024, userID:0,
,I/art     ( 4177): Background sticky concurrent mark sweep GC freed 23410(1776KB) AllocSpace objects, 14(280KB) LOS objects, 24% free, 6MB/8MB, paused 11.964ms total 89.861ms,
,D/LocationInitializer( 4177): Restart initialization of location
,I/UpdateIcingCorporaServi( 5449): UpdateCorporaTask done [took 65 ms] updated apps [took 65 ms] 
,D/Finsky  ( 5504): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive,
,W/jxcore-log( 5630): Initializing JXcore engine,
W/jxcore-log( 5630): JXcore engine is ready
,W/jxcore-log( 5630): Starting JXcore engine,
,W/jxcore-log( 5630): Platform android,
W/jxcore-log( 5630): 
W/jxcore-log( 5630): Process ARCH arm
W/jxcore-log( 5630): 
,I/jxcore-log( 5630): JXcore Cordova bridge is ready!,
I/jxcore-log( 5630): 
W/jxcore-log( 5630): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5630): execute: REQUEST_ACCESS_COARSE_LOCATION,
,E/jxcore  ( 5630): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 5630): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5630): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/PluginManager( 5630): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 46ms. Plugin should use CordovaInterface.getThreadPool().,
D/PMS     (  964): acquireWL(1921511b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 964 1000 null
W/HtcSystemUPManager(  964): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1540): [onResume],
I/FeedProviderManager( 1540): onResume
I/SocialFeedProvider( 1540): +onResume
I/SocialFeedProvider( 1540): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1540): -onResume
I/ConnectivityHelper( 1540): [getCurrentConnectionType] no network connection
,D/FindExtension( 1540): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
D/StatusBarManagerService(  964): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
I/ThreadedRenderer( 1540): Defer allocateBuffers to drawing time
I/InputMethodManagerService(  964): Disable input method client, pid=5630
D/StatusBarManagerService(  964): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  964): Enable input method client, pid=1540
,W/IInputConnectionWrapper( 5630): reportFullscreenMode on inactive InputConnection
I/PhoneStatusBar( 1210): setImeWindowStatus(false,false)
,D/PMS     (  964): releaseWL(1921511b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/StatusBarManagerService(  964): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
D/StatusBarManagerService(  964): hiding MENU key
,D/Process (  964): killProcessQuiet, pid=5133
,I/ActivityManager(  964): Killing 5133:com.htc.sdm/u0a79 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  964): Recipient 5133
,W/OpenGLRenderer( 1540): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,I/ConfigService( 1874): onDestroy,
,I/ActivityManager(  964): Waited long enough for: ServiceRecord{25e173be u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
,I/ActivityManager(  964): Waited long enough for: ServiceRecord{d3d0dca u0 com.htc.musicenhancer/.EnhancerService},
,D/Process (  964): killProcessQuiet, pid=4756
I/ActivityManager(  964): Killing 4756:com.htc.task/u0a69 (adj 15): empty #17
,D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 4756,
,I/HtcModeClient( 3108): handler message = 4011,
E/HtcModeClient( 3108): Check connection and retry 8 times.
,W/MediaManager( 4981): [DualLensScanUtil],	mmpCursor count is 0
,D/Process (  964): killProcessQuiet, pid=4904
I/ActivityManager(  964): Killing 4904:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 4904
,D/Process (  964): killProcessQuiet, pid=5302
I/ActivityManager(  964): Killing 5302:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 5302
,D/Process (  964): killProcessQuiet, pid=5401
I/ActivityManager(  964): Killing 5401:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 5401
D/WifiService(  964): Client connection lost with reason: 4
,D/PMS     (  964): acquireWL(321aebce): PARTIAL_WAKE_LOCK  *alarm* 0x1 964 1000 WorkSource{10024},
,V/AlarmManager(  964): sending alarm PendingIntent{38a35aef: PendingIntentRecord{19f7bf14 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=81798, Int=0
D/PMS     (  964): acquireWL(271cb9fc): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1874 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  964): releaseWL(321aebce): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1874): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1874): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1874): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1874): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1874): [NET] android_getaddrinfo_proxy+
D/libc    ( 1874): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1874): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  964): releaseWL(271cb9fc): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/HtcModeClient( 3108): handler message = 4011,
E/HtcModeClient( 3108): Check connection and retry 9 times.
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  964): acquireWL(3cce2885): PARTIAL_WAKE_LOCK  *alarm* 0x1 964 1000 WorkSource{1000}
,V/AlarmManager(  964): sending alarm PendingIntent{ffdf6da: PendingIntentRecord{36f4b70b android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=85667, Int=0,
,D/PMS     (  964): releaseWL(3cce2885): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/ContactMessageStore( 1483): MSG_NOTIFY_CS_TO_SYNC >>
D/PMS     (  964): acquireWL(3f4dc801): PARTIAL_WAKE_LOCK  *alarm* 0x1 964 1000 WorkSource{10072}
D/ContactMessageStore( 1483): MSG_NOTIFY_CS_TO_SYNC <<
V/AlarmManager(  964): sending alarm PendingIntent{18d4a6a6: PendingIntentRecord{27b5b8e7 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457577255174, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{30604c94: PendingIntentRecord{3ecde33d android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=86042, Int=0
,D/libc    (  964): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  964): releaseWL(3f4dc801): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/libc    (  964): [NET] android_getaddrinfofornet-, err=8
D/libc    (  964): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  964): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  964): [NET] android_getaddrinfo_proxy+
,D/libc    (  964): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
,D/libc    (  964): [NET] android_getaddrinfo_proxy-, NODATA
,I/art     (  964): Explicit concurrent mark sweep GC freed 22405(1138KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 18MB/27MB, paused 1.622ms total 161.898ms
,D/Finsky  ( 5504): [562] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5504): [1] 5.onFinished: Installation state replication succeeded.,
,I/HtcModeClient( 3108): handler message = 4011
E/HtcModeClient( 3108): Check connection and retry 10 times.
,I/HtcModeClient( 3108): handler message = 4011,
,E/HtcModeClient( 3108): Check connection and retry 11 times.
,D/PMS     (  964): acquireWL(14ffe47e): PARTIAL_WAKE_LOCK  Icing 0x1 4177 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  964): releaseWL(14ffe47e): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  964): acquireWL(34009a2c): PARTIAL_WAKE_LOCK  Icing 0x1 4177 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  964): releaseWL(34009a2c): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  964): acquireWL(cea0556): PARTIAL_WAKE_LOCK  Icing 0x1 4177 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  964): releaseWL(cea0556): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/HtcModeClient( 3108): handler message = 4011,
,E/HtcModeClient( 3108): Check connection and retry 12 times.
,I/HtcModeClient( 3108): handler message = 4011,
,E/HtcModeClient( 3108): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3108): Don't start project servcice,
,D/HtcModeClient( 3108): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3108): connectState: CONNECTION_READY = false
,D/SilentMusic( 3108): call stop
D/HtcModeClient( 3108): close connection
W/HtcModeClient( 3108): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3108): read the terminate packet, so break
,D/Process (  964): killProcessQuiet, pid=3108
I/ActivityManager(  964): Killing 3108:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 3108
,I/ActivityManager(  964): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5817 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  964): acquireWL(3c8a9d7): PARTIAL_WAKE_LOCK  *alarm* 0x1 964 1000 WorkSource{10076}
V/AlarmManager(  964): sending alarm PendingIntent{337a02c4: PendingIntentRecord{3f6315ad com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457577272666, Int=60000
D/PMS     (  964): releaseWL(3c8a9d7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 5817): SMSBackupAgentService started,
D/SMSBackup( 5817): Checking restore status
,D/SMSBackup( 5817): Restore complete,
D/SMSBackup( 5817): cancelCheckAlarm
,D/SMSBackup( 5817): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  964): killProcessQuiet, pid=5033
I/ActivityManager(  964): Killing 5033:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 5033
,D/MediaRouterService(  964): Client com.google.android.music (pid 5033): Died!
,I/SensorManager(  964): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@a5ecebd,
,I/PMS     (  964): Going to sleep due to screen timeout (uid 1000)...
W/SensorService(  964): Following SensorService logs are not warning, just make sure they are printed
D/ActivityManager(  964): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{40c73 #11 A=.Prism U=0 sz=1}
W/SensorService(  964): disable: get sensor name = Accelerometer Sensor
W/PMS     (  964): mWirelessDisplayManager is null
W/SensorService(  964): pid=964, uid=1000
W/PMS     (  964): mWirelessDisplayManager is still null
W/SensorService(  964): Active sensors: size = 4
W/PMN     (  964): goingToSleep
W/SensorService(  964): Accelerometer Sensor (handle=0x00000000, connections=1)
D/PMS     (  964): acquireWL(11768730): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 964 1000 null
W/SensorService(  964): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  964): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  964): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  964): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@a5ecebd, eanble = 0, strlen(mName) = 90
W/SensorService(  964): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  964): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@2387bba2
W/SensorService(  964): Listener[1] = com.htc.smartdim.sensor_eye@10067bbf
W/SensorService(  964): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/PMS     (  964): Sleeping (uid 1000)...
W/PMN     (  964): goingToSleep done
,I/FeedHostManager( 1540): [onPause]
D/XAN-DPS (  964): prepareColorFade 1
,I/FeedProviderManager( 1540): onPause
I/FeedHostManager( 1540): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@30645bd9
I/SocialFeedProvider( 1540): +onPause
I/SocialFeedProvider( 1540): -onPause
,I/ActivityManager(  964): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5840 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/AlarmManager(  964): ACTION_SCREEN_ON
W/HtcSystemUPManager(  964): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/PMS     (  964): releaseWL(11768730): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/AlarmManager(  964): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  964): [AlarmQueuing] done recovering
I/AlarmManager(  964): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  964): [AlarmQueuing] done EPS screen off alarm recovering
,W/HtcLockScreen( 1210): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/Adreno-EGL(  964): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  964): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  964): Build Date: 03/09/15 Mon
I/Adreno-EGL(  964): Local Branch: 
I/Adreno-EGL(  964): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  964): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  964):                  d74aa161a12b9c6fc6332151
,E/WifiStateMachine(  964): handleMessage: E msg.what=131167
E/WifiStateMachine(  964): processMsg: InitialState,
E/WifiStateMachine(  964):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  964): processMsg: DefaultState
,E/WifiStateMachine(  964):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  964):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState,
,D/WifiStateMachine(  964): getWifiLinkLayerStats: WIFI is not enbled,
D/WifiStateMachine(  964): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  964): handleScreenStateChanged Exit: true
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=131154
V/SRS_Proc(  401): ParamSet string: screen_state=on
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  964): processMsg: InitialState
E/WifiStateMachine(  964):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  964): processMsg: DefaultState
E/WifiStateMachine(  964):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=131127
E/WifiStateMachine(  964): processMsg: InitialState
,E/WifiStateMachine(  964):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  964): processMsg: DefaultState
E/WifiStateMachine(  964):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=131129
E/WifiStateMachine(  964): processMsg: InitialState
E/WifiStateMachine(  964):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  964): processMsg: DefaultState
E/WifiStateMachine(  964):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  964): handleMessage: X
,D/WifiController(  964): handleMessage: E msg.what=155650
D/WifiController(  964): processMsg: ApStaDisabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
,D/NetworkPolicy(  964): updateScreenOn: false
V/NetworkPolicy(  964): updateIfacesLocked()
,D/NetworkManagementService(  964): isBandwidthControlEnabled: doneSignal.getCount()= 0
,W/ResourcesManager( 5840): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/GpsLocationProvider(  964): receive broadcast intent, action: android.intent.action.SCREEN_ON,
,I/CalendarProvider2( 5840): Created com.android.providers.calendar.CalendarAlarmManager@200e92b(com.htc.providers.calendar.HtcCalendarProvider@23b09188),
,D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/CalendarProvider2( 5840): wait start:true
,I/IntentController( 1210): receive(android.intent.action.SCREEN_ON,1,false),
,D/PMS     (  964): acquireWL(310f8692): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1822 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  964): acquireWL(588f863): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1822 10024 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  964): prepareColorFade done
D/XAN-DPS (  964): setBrightness to 0,
D/PMS     (  964): releaseWL(310f8692): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  964): releaseWL(588f863): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 5840): wait end:false
,I/SensorManager(  964): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@2387bba2
W/SensorService(  964): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  964): disable: get sensor name = CM32181 Light sensor
,I/DisplayManagerService(  964): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  964): Display changed displayId=0
D/DotMatrix( 1303): [EventService]  onDisplayChanged: 0
E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
W/SensorService(  964): pid=964, uid=1000
W/SensorService(  964): Active sensors: size = 3
,W/SensorService(  964): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  964): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  964): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  964): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@2387bba2, eanble = 0, strlen(mName) = 67
W/SensorService(  964): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  964): Listener[0] = com.htc.smartdim.sensor_eye@10067bbf
W/SensorService(  964): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1303): [EventService] mbHDMIConnect: false, mCoverOn:false
,I/ActivityManager(  964): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5869 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/AlarmManager(  964): ACTION_SCREEN_OFF,
,I/AlarmManager(  964): [AlarmQueuing] screen off now: 
I/AlarmManager(  964): [AlarmQueuing] data connection: true
I/AlarmManager(  964): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  964): stopDataStallAlarm 
E/WifiDataStallTracker(  964): ENABLE_DATA_MONITOR_POLL false Token 0
,D/WifiDisplayAdapter(  964): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  964):     Client/Owner: Client
D/WifiDisplayAdapter(  964):     GroupId: 
D/WifiDisplayAdapter(  964):     Passphrase: 
D/WifiDisplayAdapter(  964):     SessionId: 0
D/WifiDisplayAdapter(  964):     IP Address: }
E/WifiStateMachine(  964): handleMessage: E msg.what=131167
E/WifiStateMachine(  964): processMsg: InitialState
E/WifiStateMachine(  964):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  964): processMsg: DefaultState
,E/WifiStateMachine(  964):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  964):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiStateMachine(  964): getWifiLinkLayerStats: WIFI is not enbled
E/WifiStateMachine(  964): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  964): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  964): handleScreenStateChanged Exit: false
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=131154
,E/WifiStateMachine(  964): processMsg: InitialState
V/SRS_Proc(  401): ParamSet string: screen_state=off
E/WifiStateMachine(  964):  InitialState CMD_ENABLE_RSSI_POLL 0 0
D/NetworkPolicy(  964): updateScreenOn: false
E/WifiStateMachine(  964): processMsg: DefaultState
V/NetworkPolicy(  964): updateIfacesLocked()
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  964):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  964): handleMessage: X
D/WifiController(  964): handleMessage: E msg.what=155651
D/WifiController(  964): processMsg: ApStaDisabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
D/NetworkManagementService(  964): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/SensorManager( 1210): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@2735764e, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  964): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  964): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  964): pid=1210, uid=10041,
W/SensorService(  964): Active sensors: size = 4
W/SensorService(  964): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  964): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  964): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  964): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  964): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@2735764e, eanble = 1, strlen(mName) = 57
W/SensorService(  964): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  964): Listener[0] = com.htc.smartdim.sensor_eye@10067bbf
W/SensorService(  964): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@2735764e
W/SensorService(  964): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  964): receive broadcast intent, action: android.intent.action.SCREEN_OFF,
,D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1303): [EventService] getTotalRam: 1842 Mb
,I/IntentController( 1210): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1483): start background delete task...
W/ContextImpl( 5869): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  964): acquireWL(408b7bf): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1822 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  964): releaseWL(408b7bf): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  964): Excessive delay in setPowerMode(): 289ms
D/PMS     (  964): Setting HAL interactive mode to false
D/PMS     (  964): Setting HAL interactive mode to false done
D/PMS     (  964): Setting HAL auto-suspend mode to true
D/PMS     (  964): Setting HAL auto-suspend mode done
D/ContactMessageStore( 1483): size: 0 , 0
D/PMS     (  964): acquireWL(3c6c9e8c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1822 10024 WorkSource{10024 com.google.android.gms}
D/ContactMessageStore( 1483): Background delete complete
I/InputMethodManagerService(  964): screenObserver, isScreenOn=false
,W/HtcSystemUPManager(  964): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,D/StatusBarManagerService(  964): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1210): setImeWindowStatus(false,false),
I/InputMethodManagerService(  964): Disable input method client, pid=1540
D/PowerUsageList:PowerUsageHelper( 5869): MY_DEBUG = false
,D/HABCtrl (  964): TPE algorithm. remove timeout.
D/PMS     (  964): OOBE c monitor 11
,D/NfcService( 1503): ScreenObserver: OFF,
,D/PMS     (  964): releaseWL(3c6c9e8c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/NfcService( 1503): applyRouting - 0
,D/PMS     (  964): acquireWL(3ed659d5): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1503 1027 null
D/PMS     (  964): acquireWL(206155ea): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
W/ContextImpl( 5869): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
I/BatteryService(  964): n_update end,
,D/PMS     (  964): releaseWL(206155ea): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NfcService( 1503): applyRouting -2
,D/PMS     (  964): releaseWL(3ed659d5): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/NfcService( 1503): applyRouting
D/HtcPowerSaver(  964): updateBatteryInfo
D/NfcService( 1503): Ignore this applyRouting...
D/NotificationService(  964): plugged=true pluggin=true
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  964): BroadcastReceiver::onReceive+
,D/PMS     (  964): runPSCheck
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  964): Checking...
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  964): >> updateStatus
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/WifiController(  964): battery changed pluggedType: 2
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): processMsg: ApStaDisabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
,I/IntentController( 1210): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1210): closing low battery warning: level=100
D/PowerUI ( 1210): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,D/SmartSyncUtils( 5869): isEpsOn(), nState = 0
,I/RemoteViews( 1210): setHTCTheme(com.htc.updater,true,33751145),
D/PMS     (  964): acquireWL(1b8b1778): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5869 1000 null
,I/InputManager(  964): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false,
I/IntentController( 1210): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,I/RemoteViews( 1210): apply : com.htc.updater 0 23 1 36,
D/PMS     (  964): releaseWL(1b8b1778): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartDim(  964): Init customizeScreenOffDelayClass error
,I/BatteryController( 1210): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 5869): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5869): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncUtils( 5869): isEpsOn(), nState = 0
D/SmartSyncUtils( 5869): isEpsOn(), nState = 0
,W/ContextImpl( 5869): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  964): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@10067bbf
W/SensorService(  964): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  964): disable: get sensor name = Accelerometer Sensor
,I/ClockController( 1210): stop clock update:screen off
,W/SensorService(  964): pid=964, uid=1000
W/SensorService(  964): Active sensors: size = 3
W/SensorService(  964): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  964): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  964): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  964): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@10067bbf, eanble = 0, strlen(mName) = 36
W/SensorService(  964): Active Listeners: mActiveListeners.size() = 1,
W/SensorService(  964): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2735764e
W/SensorService(  964): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  964): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  964): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  964): pid=964, uid=1000,
W/SensorService(  964): Active sensors: size = 2
W/SensorService(  964): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  964): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  964): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@10067bbf, eanble = 0, strlen(mName) = 36
W/SensorService(  964): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  964): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2735764e
W/SensorService(  964): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  964): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@10067bbf
E/ActivityThread(  964): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@131128c that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  964): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@131128c that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  964): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  964): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  964): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  964): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  964): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  964): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  964): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  964): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  964): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  964): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  964): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  964): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  964): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  964): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  964): 	at java.lang.reflect.Method.invoke(Native Method)
,E/ActivityThread(  964): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  964): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  964): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/ActivityManager(  964): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5902 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
I/PowerUsageList:PowerUsageHelper( 5869): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5869): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 5869): calcPower(), no data
,D/SmartSyncUtils( 5869): getMobilePolicyEnabled, result = true,
,D/Process (  964): killProcessQuiet, pid=5477
I/ActivityManager(  964): Killing 5477:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,E/WifiTrafficPoller(  964): ADD_CLIENT: 7,
D/WifiService(  964): New client listening to asynchronous messages
,I/ActivityManager(  964): Recipient 5477
,D/PowerUsageList:PowerUsageHelper( 5869): MY_DEBUG = false
,I/ActivityManager(  964): Killing 4929:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  964): killProcessQuiet, pid=4929
,D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  964): Recipient 4929
,I/CalendarProvider2( 5840): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 5840): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  964): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5926 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  964): killProcessQuiet, pid=5668
I/ActivityManager(  964): Killing 5668:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 5668
,W/ResourcesManager( 5926): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 5926): onCreate
,D/ProviderChangeReceiver( 5926): ---------------------------------------------------
D/ProviderChangeReceiver( 5926): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/HtcAlertService( 5926): start to updateAlertNotification!
,I/ActivityManager(  964): Killing 5706:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=5706
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/PMS     (  964): releaseWL(14a317f0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  964): Recipient 5706,
,D/HtcAlertService( 5926): No fired or scheduled alerts,
D/HtcAlertUtils( 5926): -- cancelReminderNotification --
,D/HtcAlertUtils( 5926): broadcastExistReminder!,
,D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcUPManager( 1210): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/Process (  964): killProcessQuiet, pid=5109
I/ActivityManager(  964): Killing 5109:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 5109
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  964): acquireWL(3b2fdfb7): PARTIAL_WAKE_LOCK  *alarm* 0x1 964 1000 WorkSource{10024},
V/AlarmManager(  964): sending alarm PendingIntent{8163324: PendingIntentRecord{19f7bf14 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=122090, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{2482b842: PendingIntentRecord{24d8c053 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457577297868, Int=0
D/PMS     (  964): acquireWL(26e0ee8d): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1874 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1874): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/PMS     (  964): acquireWL(e155d90): PARTIAL_WAKE_LOCK  *backup* 0x1 964 1000 null
D/libc    ( 1874): [NET] android_getaddrinfofornet-, err=8
D/PMS     (  964): releaseWL(3b2fdfb7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    ( 1874): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
W/BackupManagerService(  964): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,D/libc    ( 1874): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1874): [NET] android_getaddrinfo_proxy+
D/libc    ( 1874): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
E/BackupManagerService(  964): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/PMS     (  964): releaseWL(e155d90): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/libc    ( 1874): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  964): releaseWL(26e0ee8d): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  964): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  964): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  964): acquireWL(2efae689): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null,
I/BatteryService(  964): n_update end
,D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/PMS     (  964): releaseWL(2efae689): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  964): battery changed pluggedType: 2
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  964): updateBatteryInfo
,D/WifiController(  964): handleMessage: E msg.what=155652
D/PMS     (  964): runPSCheck
D/WifiController(  964): processMsg: ApStaDisabledState
D/HtcPowerSaver(  964): Checking...
D/WifiController(  964): processMsg: DefaultState
I/HtcPowerSaver(  964): >> updateStatus
D/WifiController(  964): handleMessage: X
D/PowerUI ( 1210): closing low battery warning: level=100
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1210): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1210): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1210): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  964): acquireWL(a08168e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000},
D/libc    (  964): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
V/AlarmManager(  964): sending alarm PendingIntent{445a837: PendingIntentRecord{1c7391a4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=133907, Int=0
D/libc    (  964): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  964): sending alarm PendingIntent{30604c94: PendingIntentRecord{3ecde33d android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=149098, Int=0
D/libc    (  964): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,V/AlarmManager(  964): sending alarm PendingIntent{3c250eaf: PendingIntentRecord{309ac2bc com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142462, Int=0
D/libc    (  964): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  964): [NET] android_getaddrinfo_proxy+
D/libc    (  964): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    (  964): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  964): releaseWL(a08168e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1210): Weather sync is On
,W/WeatherTimeKeeper( 1210): [refreshWeatherData] no weather data
,W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/TelephonyReceiver( 1483): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  964): acquireWL(32a26245): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null,
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(32a26245): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  964): updateBatteryInfo
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1210): closing low battery warning: level=100
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  964): plugged=true pluggin=true
I/IntentController( 1210): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  964): runPSCheck
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  964): Checking...
D/UsbnetService(  964): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  964): >> updateStatus
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  964): battery changed pluggedType: 2
D/UsbnetService(  964): BroadcastReceiver::onReceive-
,D/PowerUI ( 1210): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): processMsg: ApStaDisabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
,I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1210): status:5 level:100 unsupport:false plugged:true
,D/HtcUPManager( 1210): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1210): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
I/ActivityManager(  964): Killing 4835:com.android.settings/1000 (adj 15): empty #17
,D/HtcAppUPService( 1454): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3e06b092
D/Process (  964): killProcessQuiet, pid=4835
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 4835,
,D/PMS     (  964): acquireWL(f730d9a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000},
V/AlarmManager(  964): sending alarm PendingIntent{445a837: PendingIntentRecord{1c7391a4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=193907, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{13de6cb: PendingIntentRecord{2faf4ea8 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=194262, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{30604c94: PendingIntentRecord{3ecde33d android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=209109, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{358bddc1: PendingIntentRecord{2e646966 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=185895, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{3c224a7: PendingIntentRecord{fead54 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457577367035, Int=1800000
,D/libc    (  964): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
V/AlarmManager(  964): sending alarm PendingIntent{283794fd: PendingIntentRecord{19f7bf14 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=212356, Int=0
D/libc    (  964): [NET] android_getaddrinfofornet-, err=8
D/libc    (  964): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  964): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  964): [NET] android_getaddrinfo_proxy+
D/PMS     (  964): acquireWL(7bdb5f2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1874 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  964): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    (  964): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  964): releaseWL(7bdb5f2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  964): acquireWL(4626443): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4177 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1210): Weather sync is On
D/PMS     (  964): acquireWL(8ed83f9): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1874 10024 WorkSource{10024 com.google.android.gms}
W/WeatherTimeKeeper( 1210): [refreshWeatherData] no weather data,
D/libc    ( 1874): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/PMS     (  964): releaseWL(f730d9a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
D/libc    ( 1874): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1874): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1874): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1874): [NET] android_getaddrinfo_proxy+
D/libc    ( 1874): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1874): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  964): releaseWL(8ed83f9): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  964): acquireWL(36ed3f3e): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4177 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  964): releaseWL(4626443): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 4177): Aggregate from 1457575566939 (log), 1457575566939 (data)
,I/art     ( 1874): Explicit concurrent mark sweep GC freed 15063(823KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 1.294ms total 65.935ms,
,D/PMS     (  964): releaseWL(36ed3f3e): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1874): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1874): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1874): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1874): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActionCombine( 1874): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,W/ResourcesManager( 1210): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 1210): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 1303): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 1303): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1303): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1303): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1874): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1874): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1874): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1874): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1874): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1874): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1874): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5504): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5504): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5504): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5504): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5504): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5504): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5504): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1210): apply : com.google.android.gms 0 12 4 40
,W/System  ( 5504): Ignoring header User-Agent because its value was null.
,D/libc    ( 5504): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5504): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5504): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5504): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5504): [NET] android_getaddrinfo_proxy+
D/libc    ( 5504): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5504): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  964): acquireWL(39e160fa): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000},
V/AlarmManager(  964): sending alarm PendingIntent{445a837: PendingIntentRecord{1c7391a4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=253906, Int=0
,V/AlarmManager(  964): sending alarm PendingIntent{37d74108: PendingIntentRecord{30a750a1 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457577523872, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{2f5492c6: PendingIntentRecord{19f7bf14 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=373524, Int=0
,D/PMS     (  964): acquireWL(36df0287): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1874 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1874): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1874): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1874): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1874): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1874): [NET] android_getaddrinfo_proxy+
D/libc    ( 1874): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1874): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  964): releaseWL(36df0287): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  964): releaseWL(39e160fa): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1210): Weather sync is On,
W/WeatherTimeKeeper( 1210): [refreshWeatherData] no weather data
,D/PMS     (  964): acquireWL(b2365b4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/BatteryService(  964): n_update end
,D/PMS     (  964): releaseWL(b2365b4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  964): BroadcastReceiver::onReceive+
,D/NotificationService(  964): plugged=true pluggin=true,
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  964): updateBatteryInfo
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/PMS     (  964): runPSCheck
D/WifiController(  964): handleMessage: E msg.what=155652
D/HtcPowerSaver(  964): Checking...
D/WifiController(  964): processMsg: ApStaDisabledState
I/HtcPowerSaver(  964): >> updateStatus
D/WifiController(  964): processMsg: DefaultState
D/PowerUI ( 1210): closing low battery warning: level=100
D/WifiController(  964): handleMessage: X
,I/IntentController( 1210): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1210): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1210): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  458): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  964): acquireWL(244755dd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(244755dd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  964): updateBatteryInfo
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1210): closing low battery warning: level=100
,D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/PMS     (  964): runPSCheck
I/IntentController( 1210): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  964): Checking...
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  964): >> updateStatus
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  964): battery changed pluggedType: 2
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): processMsg: ApStaDisabledState
D/PowerUI ( 1210): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
,I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1210): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1483): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1483): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1483): sku_id=118
D/ContactMessageStore( 1483): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1483): start background delete task...
,D/ContactMessageStore( 1483): size: 0 , 0
,D/ContactMessageStore( 1483): Background delete complete
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1874): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1874): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1874): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1874): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1874): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1874): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1874): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1874): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
,W/GLSActivity( 1874): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1874): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1874): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1210): reapply : com.google.android.gms 3 40
E/PlayEventLogger( 5504): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5504): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5504): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5504): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5504): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5504): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5504): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5504): Ignoring header User-Agent because its value was null.
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    ( 5504): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5504): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5504): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5504): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5504): [NET] android_getaddrinfo_proxy+
D/libc    ( 5504): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5504): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  964): acquireWL(11279b77): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000}
V/AlarmManager(  964): sending alarm PendingIntent{445a837: PendingIntentRecord{1c7391a4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=373907, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{1445a3e4: PendingIntentRecord{19f7bf14 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=695794, Int=0
D/PMS     (  964): acquireWL(3fee704d): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1874 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1874): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1874): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1874): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1874): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1874): [NET] android_getaddrinfo_proxy+
D/libc    ( 1874): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1874): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  964): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=5970 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  964): sending alarm PendingIntent{74b7702: PendingIntentRecord{26f07813 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457577684016, Int=0
,D/PMS     (  964): releaseWL(3fee704d): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  964): releaseWL(11279b77): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1210): Weather sync is On
W/WeatherTimeKeeper( 1210): [refreshWeatherData] no weather data
,E/cutils-trace( 5991): Error opening trace file: Permission denied (13)
,I/dex2oat ( 5991): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
I/dex2oat ( 5991): dex2oat: override thread count:4
,I/dex2oat ( 5991): dex2oat took 786.084ms (threads: 4)
,I/PushClient( 5970): ApplicationMonitor {1633845d}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 5970): ApplicationMonitor {1633845d}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 5970): ApplicationMonitor {1633845d}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 5970): ApplicationMonitor {1633845d}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 5970): ApplicationMonitor {1633845d}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 5970): ApplicationMonitor {1633845d}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 5970): ApplicationMonitor {1633845d}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 5970): ApplicationMonitor {1633845d}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 5970): ApplicationMonitor {1633845d}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 5970): PnsModel {26813e34}: update(): Update registration caused by: alarm
,I/PushClient( 5970): PnsConfigModel {3a32731b}: <init>(): Use dm-client for provisioning.
,W/System.err( 5970): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 5970): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 5970): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 5970): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  964): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=5998 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 5998): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5998 dbg=false s=true,
,I/DeviceManagement( 5998): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 5998): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 5998): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 5998): WorkflowService: Starting workflow service,
,I/DeviceManagement( 5998): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@26813e34] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 5998): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 5998): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 5998): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 5998): SessionStateController: Checking invariants...,
,I/art     (  964): Explicit concurrent mark sweep GC freed 28202(1592KB) AllocSpace objects, 4(612KB) LOS objects, 33% free, 18MB/27MB, paused 1.889ms total 201.780ms
,I/DeviceManagement( 5998): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 5998): SessionStateController: Checking invariants...,
,I/DeviceManagement( 5998): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 5998): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@26813e34],
,I/DeviceManagement( 5998): WorkflowService: Stopping workflow service
,D/Process (  964): killProcessQuiet, pid=5748,
I/ActivityManager(  964): Killing 5748:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 5970): PnsModel {26813e34}: update(): Start updating since the registration has expired.,
,I/ActivityManager(  964): Recipient 5748,
,W/PushClient( 5970): GCMRegistrator {13e4e0da}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.,
W/PushClient( 5970):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
W/PushClient( 5970):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
W/PushClient( 5970):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
W/PushClient( 5970):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
W/PushClient( 5970):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
W/PushClient( 5970):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/PushClient( 5970):   	at android.os.Handler.dispatchMessage(Handler.java:102)
W/PushClient( 5970):   	at android.os.Looper.loop(Looper.java:155)
W/PushClient( 5970):   	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PushClient( 5970):   
,D/GCM     ( 1874): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,D/libc    ( 1874): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 1874): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1874): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1874): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1874): [NET] android_getaddrinfo_proxy+
D/libc    ( 1874): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1874): [NET] android_getaddrinfo_proxy-, NODATA
,E/PushClient( 5970): PnsModel {26813e34}: update(): com.htc.lib1.cs.push.exception.UpdateRegistrationFailedException: SERVICE_NOT_AVAILABLE,
E/PushClient( 5970):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:198)
E/PushClient( 5970):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
E/PushClient( 5970):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
E/PushClient( 5970):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PushClient( 5970):   	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PushClient( 5970):   	at android.os.Looper.loop(Looper.java:155)
E/PushClient( 5970):   	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PushClient( 5970):   Caused by: java.io.IOException: SERVICE_NOT_AVAILABLE
E/PushClient( 5970):   	at com.google.android.gms.gcm.GoogleCloudMessaging.register(Unknown Source)
E/PushClient( 5970):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.registerGCM(GCMRegistrator.java:301)
E/PushClient( 5970):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:196)
E/PushClient( 5970):   	... 6 more
E/PushClient( 5970):   
,I/PushClient( 5970): CentralClientRetryPolicy {200e92b}: scheduleUpdateRetry(): Waiting for network connectivity...,
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.htc.cs.pns, clsName=com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver, state=1, flag=1, pid=5970, uid=10071, userID:0,
,I/ActivityManager(  964): Killing 5580:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=5580
,D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 5580
,D/PMS     (  964): acquireWL(1a21b780): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000}
V/AlarmManager(  964): sending alarm PendingIntent{445a837: PendingIntentRecord{1c7391a4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=733907, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{ffdf6da: PendingIntentRecord{36f4b70b android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805695, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{134451b9: PendingIntentRecord{15c3dcac com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457578128148, Int=0
,W/ContextImpl( 5869): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  964): releaseWL(1a21b780): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 5869): MY_DEBUG = false
,D/WeatherUtility( 1210): Weather sync is On
W/WeatherTimeKeeper( 1210): [refreshWeatherData] no weather data
,D/PowerUsageService( 5869): repeat time = 1457579028183
,I/PowerUsageList:PowerUsageHelper( 5869): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 5869): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 5869): calcPower(), no data,
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1874): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1874): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1874): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1874): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1874): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1874): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1874): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1874): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1874): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1874): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1874): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,E/PlayEventLogger( 5504): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5504): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5504): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5504): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5504): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5504): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5504): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/System  ( 5504): Ignoring header User-Agent because its value was null.
D/libc    ( 5504): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5504): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5504): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5504): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5504): [NET] android_getaddrinfo_proxy+
D/libc    ( 5504): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
,I/RemoteViews( 1210): reapply : com.google.android.gms 3 40
D/libc    ( 5504): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  964): acquireWL(cd200b0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000},
V/AlarmManager(  964): sending alarm PendingIntent{445a837: PendingIntentRecord{1c7391a4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=973906, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{29c01b29: PendingIntentRecord{39c83eae com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457578178634, Int=0
,D/SmartSyncUtils( 5869): isEpsOn(), nState = 0,
,D/PMS     (  964): acquireWL(5efe44f): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5869 1000 null,
D/SmartSyncScreenOnOffTimeReceiver( 5869): [updateNmRange] bManual = false,
D/PMS     (  964): releaseWL(cd200b0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 5869): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/WeatherUtility( 1210): Weather sync is On
W/WeatherTimeKeeper( 1210): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 5869): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 5869): SettingOnTime = 1457589600000, randomSettingOnTime = 1457587156000
D/SmartSyncScreenOnOffTimeReceiver( 5869): SettingOffTime = 1457654400000, randomSettingOffTime = 1457661096000
,D/SmartSyncScreenOnOffTimeReceiver( 5869): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5869): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 5869): bNightModeTurnOffOnce = false
,D/PMS     (  964): acquireWL(2ce77dc): PARTIAL_WAKE_LOCK  *alarm* 0x1 964 1000 WorkSource{1000}
V/AlarmManager(  964): sending alarm PendingIntent{2a9640e5: PendingIntentRecord{3fdd97ba com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1457578178682, Int=0
,D/PMS     (  964): releaseWL(5efe44f): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 5869): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncDataLinkTurnOffService( 5869): SMARTSYNC_TURN_OFF_NETWORK, current time = 1457578178700, randomOffTime = 1457661096000, newRandomOffTime = 1457661096000
,D/SmartSyncDataLinkTurnOffService( 5869): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 0, randomMobileOnTime = 1457587156000
,D/PMS     (  964): releaseWL(2ce77dc): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/SmartSyncUtils( 5869): getMobilePolicyEnabled, result = true,
D/SmartSyncDataLinkTurnOffService( 5869): turnOffMobile bPolicyEnabled = true
,D/SmartSyncUtils( 5869): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 5869): turnOffMobile bCheckMobileData = false
,D/LocationManagerService(  964): getProviders()=[gps, network]
D/LocationManagerService(  964): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 5869): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 5869): isCharging status = 5
,D/SmartSyncDataLinkTurnOffService( 5869): turnOffWifi ui setting = false
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  964): User[0] Flushing usage stats to disk
,V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1874): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1874): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1874): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1874): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1874): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1874): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1874): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1874): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1874): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1874): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1874): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1874): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5504): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5504): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5504): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5504): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5504): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5504): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5504): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5504): Ignoring header User-Agent because its value was null.
I/RemoteViews( 1210): reapply : com.google.android.gms 3 40
D/libc    ( 5504): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5504): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5504): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5504): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5504): [NET] android_getaddrinfo_proxy+
D/libc    ( 5504): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5504): [NET] android_getaddrinfo_proxy-, NODATA
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,TIME-OUT KILL (timeout was 1200000ms)
```
