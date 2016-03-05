#### Test 6165819876c87fb_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5515): -onCreate()
V/Settings:HtcSettingsApplication( 5515): [5515/5515] onCreate()
--------- beginning of system
I/ActivityManager(  940): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5544 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  940): killProcessQuiet, pid=4988
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  940): Killing 4988:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/LocationProviderProxy(  940): applying state to connected service
D/LocationProviderProxy(  940): applying state to connected service
D/PMS     (  940): acquireWL(16e99c41): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1820 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  940): releaseWL(16e99c41): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  940): acquireWL(a5985e6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1820 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  940): releaseWL(a5985e6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/Settings:HtcWirelessFeatureFlags( 5515): id/is att sku: 118/false
I/ActivityManager(  940): Recipient 4988
E/Settings:HtcWrapHeaderInfo( 5515): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5515): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 5515): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 5515): isSupportMusicChannel(): false
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5544, uid=10072, userID:0
W/global  ( 5544): [apache-http] Connection GC has been deprecated!
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportHomeButton]support         :false
D/Finsky  ( 5544): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/ActivityManager(  940): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5515): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5515): isSupportVoWifi: null
W/global  ( 5544): [apache-http] Connection GC has been deprecated!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5515): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 5515): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 5515): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5515): [supportHomeButton]support         :false
I/ActivityManager(  940): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5515): isSupportVoWifi: null
E/ActivityThread( 5515): Failed to find provider info for com.htc.vowifi
W/global  ( 5544): [apache-http] Connection GC has been deprecated!
E/cutils-trace( 5568): Error opening trace file: Permission denied (13)
I/Prism.ItemManager( 1557): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1557): loadItems() com.htc.launcher.pageview.WidgetManager@105bcc0 +
I/Prism.WidgetManager( 1557): onLoadItems() +
D/Finsky  ( 5544): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/ResourcesManager( 1557): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/Prism.ItemManager( 4783): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4783): loadItems() com.htc.launcher.pageview.WidgetManager@2c42209e +
I/Prism.WidgetManager( 4783): onLoadItems() +
D/CustomizationManager( 5568): ====startRecUseTime====
D/htc.customization.log.level( 5568):  is 
W/CustomizationLogLevel( 5568): Level value is invalid, use default level 2
I/ActivityManager(  940): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5601 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ResourcesManager( 4783): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/Settings( 5544): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5544): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5544, uid=10072, userID:0
D/CustomizationManager( 5568):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 5568): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5568): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5568): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5568): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5568): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5568): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5568): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5568): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5568): Parsing tag category name = system
I/CustomizationCIDLoader( 5568): Parsing tag category name = application
I/CustomizationCIDLoader( 5568): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5568): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5568): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5568): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5568): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5568): add string-array item, value = 42507
I/CustomizationCIDLoader( 5568): add string-array item, value = 21902
I/CustomizationCIDLoader( 5568): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5568): add string-array item, value = 23420
I/CustomizationCIDLoader( 5568): add string-array item, value = 22299
I/CustomizationCIDLoader( 5568): add string-array item, value = 24002
I/CustomizationCIDLoader( 5568): add string-array item, value = 23210
I/CustomizationCIDLoader( 5568): add string-array item, value = 23205
I/CustomizationCIDLoader( 5568): add string-array item, value = 23806
I/CustomizationCIDLoader( 5568): add string-array item, value = 23430
I/CustomizationCIDLoader( 5568): add string-array item, value = 23408
I/CustomizationCIDLoader( 5568): add string-array item, value = 27205
I/CustomizationCIDLoader( 5568): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5568): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5568): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5568): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5568): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5568): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5568): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5568): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5568): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5568): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5568): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5568): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5568):  Read CID file spent 0.116 (s)
D/CustomizationManager( 5568):  All configurations done spent 0.116 (s)
W/ResourcesManager( 5601): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/HtcModeClient( 3105): handler message = 4011
E/HtcModeClient( 3105): Check connection and retry 6 times.
I/MultiDex( 5601): VM with version 2.1.0 has multidex support
I/MultiDex( 5601): install
I/MultiDex( 5601): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 5544): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5544): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 5544): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/JNIHelp ( 5601): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  940): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5568 on display 0
D/PMS     (  940): acquireHCC(abc85ca): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 940 1000 null
D/PMS     (  940): acquireHCC(744b33b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 940 1000 null
W/asset   (  940): Copying FileAsset 0x557ff79540 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/Finsky  ( 5544): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PMS     (  940): acquireWL(2053496): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 940 1000 null
D/Process (  940): killProcessQuiet, pid=4544
I/ActivityManager(  940): Killing 4544:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/AnimationUtil(  940): isHTCRecent(ThaliTest/Recent screens.)/10
W/ActivityThread( 5601): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5601): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a9316d6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5601): Installed default security provider GmsCore_OpenSSL
W/ResourcesManager( 1557): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  940): Recipient 4544
I/FeedHostManager( 1557): [onPause]
I/FeedProviderManager( 1557): onPause
I/FeedHostManager( 1557): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@333e957a
I/SocialFeedProvider( 1557): +onPause
I/SocialFeedProvider( 1557): -onPause
D/PackageBroadcastService( 4199): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  940): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5632 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/PackageBroadcastService( 4199): Null package name or gms related package.  Ignoreing.
W/ResourcesManager( 4783): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/HtcSystemUPManager(  940): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  940): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5648 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PMS     (  940): acquireWL(295aaf9c): PARTIAL_WAKE_LOCK  Icing 0x1 4199 10024 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  940): Killing 4783:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  940): killProcessQuiet, pid=4783
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/asset   ( 1557): Copying FileAsset 0x557fd0a160 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/Prism.WidgetManager( 1557): onLoadItems() -,
I/Prism.ItemManager( 1557): loadItems() com.htc.launcher.pageview.WidgetManager@105bcc0 -
,W/asset   ( 1557): Copying FileAsset 0x557fd1a0f0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.,
,I/Prism.ItemManager( 1557): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
I/Prism.ItemManager( 1557): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1557): Deferring update until onResume
D/Launcher( 1557): waitUntilResume // bindAppsAdded
,I/ActivityManager(  940): Recipient 4783
,D/PhoneApp( 1525): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1525): -- N1 =0
,D/PhoneApp( 1525): -- N2 =0
,D/PhoneApp( 1525): -- N3 =0
,W/ResourcesManager( 5632): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/StatusBarManagerService(  940): setSystemUiVisibility(0x8600),
,D/StatusBarManagerService(  940): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  940): hiding MENU key
,V/AlarmManager(  940): sending alarm PendingIntent{3ae6507: PendingIntentRecord{1e735634 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457141895352, Int=0
,I/TrimMemoryManager( 1557): [trimMemory] 20
,W/asset   ( 5648): Copying FileAsset 0xac71d6f8 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/art     ( 1904): Explicit concurrent mark sweep GC freed 11375(558KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 1.206ms total 54.120ms
,I/Icing   ( 4199): Storage manager: low false usage 1.98MB avail 5.77GB capacity 7.95GB
,I/iu.UploadsManager( 4199): End new media; added: 0, uploading: 0, time: 89 ms
,W/Icing   ( 4199): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4199): Received bad json for corpus context scoring override -- ignoring.
,W/Icing   ( 4199): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4199): Received bad json for corpus context scoring override -- ignoring.
,I/WebViewFactory( 5648): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,D/Process (  940): killProcessQuiet, pid=5060,
I/ActivityManager(  940): Killing 5060:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/LibraryLoader( 5648): Time to load native libraries: 11 ms (timestamps 1662-1673)
,I/LibraryLoader( 5648): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 5648): Binding Chromium to main looper Looper (main, tid 1) {30360cfa},
I/LibraryLoader( 5648): Expected native library version number "",actual native library version number ""
,I/chromium( 5648): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager(  940): Recipient 5060
D/WifiService(  940): Client connection lost with reason: 4
,I/BrowserStartupController( 5648): Initializing chromium process, singleProcess=true,
W/art     ( 5648): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5648): ApplicationContext is null in ApplicationStatus
,V/AlarmManager(  940): sending alarm PendingIntent{380b1a15: PendingIntentRecord{3feab12a com.android.vending startService}}, i=null, t=0, cnt=1, w=1457141895799, Int=0,
,E/Icing   ( 4199): Loading extension by file descriptor -1 failed
,D/Finsky  ( 5544): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/chromium( 5648): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,V/Finsky  ( 5544): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,W/chromium( 5648): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/libEGL  ( 5648): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5648): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5648): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5648): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5648): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5648): Local Branch: 
I/Adreno-EGL( 5648): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5648): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5648):                  d74aa161a12b9c6fc6332151
,I/GLSUser ( 1904): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1904): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1904): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1904): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/System.err(  940): java.lang.Throwable: stack dump
D/BluetoothManagerService(  940): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  940): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  940): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  940): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  940): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  940): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f7a88a6:true
D/BluetoothAdapter( 5648): 340262598: getState() :  mService = null. Returning STATE_OFF
,W/Finsky  ( 5544): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1904): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1904): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1904): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1904): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 4199): updateResources: need to parse f{com.google.android.gms}
,W/art     ( 5648): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 5648): onDetachedFromWindow called when already detached. Ignoring
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  940): acquireWL(14c5f6cf): PARTIAL_WAKE_LOCK  AsyncService 0x1 5632 10167 null,
,D/PMS     (  940): releaseWL(14c5f6cf): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/SystemWebViewEngine( 5648): CordovaWebView is running on device made by: HTC
,I/art     (  940): Explicit concurrent mark sweep GC freed 25781(1443KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.461ms total 135.443ms,
D/PMS     (  940): acquireWL(3c84d765): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5632 10167 null
,W/art     ( 5648): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5648): Attempt to remove local handle scope entry from IRT, ignoring
,D/PMS     (  940): releaseWL(3c84d765): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5463): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/GLSUser ( 1904): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1904): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1904): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1904): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 4199): Internal init done: storage state 0
,I/Icing   ( 4199): Post-init done
,I/Icing   ( 4199): updateResources: need to parse f{com.google.android.gms}
W/Finsky  ( 5544): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/chromium( 5648): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/Prism.PackageStateRece_( 1557): action: android.intent.action.PACKAGE_ADDED
,I/[PluginManager]RegisterService( 1483): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1483): handle notify Blinkfeed plugin client changed
D/PMS     (  940): releaseWL(295aaf9c): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  940): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5728 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,D/FindExtension( 5648): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,E/AndroidHttpClient( 5544): Leak found,
E/AndroidHttpClient( 5544): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5544): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5544): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5544): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5544): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5544): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5544): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5544): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5544): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5544): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5544): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5544): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5544): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5544): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5544): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5544): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5544): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/DeviceManagement( 5728): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5728 dbg=false s=true
,I/DeviceManagement( 5728): PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
,I/UpdateIcingCorporaServi( 5463): UpdateCorporaTask done [took 216 ms] updated apps [took 216 ms] 
,I/ActivityManager(  940): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5752 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,I/InputMethodManager( 5648): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@37eca302, mServedView=org.apache.cordova.engine.SystemWebView{3ef83413 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@93e2650
,I/InputMethodManagerService(  940): Disable input method client, pid=1557,
D/StatusBarManagerService(  940): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
,I/InputMethodManagerService(  940): Enable input method client, pid=5648
,D/PMS     (  940): releaseWL(2053496): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  940): Displayed com.test.thalitest/.MainActivity: +1s401ms
,I/ActivityManager(  940): Waited long enough for: ServiceRecord{13d38f3 u0 com.htc.club/com.mcrm.autonotification.NotificationService}
,D/HtcCupdReceiver(Provider)( 5752):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED,
D/Process (  940): killProcessQuiet, pid=5139,
I/ActivityManager(  940): Killing 5139:com.htc.task.gtask/u0a66 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,W/XT9_C   ( 1371): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1371): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1371): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1371): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/BindingManager( 5648): Cannot call determinedVisibility() - never saw a connection for the pid: 5648
,I/ActivityManager(  940): Recipient 5139
,D/PackageBroadcastService( 4199): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 4199): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4199): Loading module APK com.google.android.play.games
,D/PMS     (  940): acquireWL(2655388d): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4199 10024 null
,I/GAV2    ( 5351): Thread[GAThread,5,main]: No campaign data found.,
,D/JsMessageQueue( 5648): Set native->JS mode to OnlineEventsBridgeMode,
I/Prism.ItemManager( 1557): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1557): loadItems() com.htc.launcher.pageview.WidgetManager@105bcc0 +
I/Prism.WidgetManager( 1557): onLoadItems() +
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1904): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1904): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1904): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1904): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  940): releaseHCC(abc85ca): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  940): releaseHCC(744b33b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
D/jxcore_app_log( 5648): JniHelper::setJavaVM(0xab5b18f8), pthread_self() = -1399818720
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5648): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5648):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5648):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5648):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5648):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5648): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dd7d0b2 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5648): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5648):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5648):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5648):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5648):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5648):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5648):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5648):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5648):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5648):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5648): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c76db9 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5648): addListener: New listener added - the number of listeners is now 1
I/ConfigFetchService( 4199): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/PMS     (  940): acquireWL(3a1f613e): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4199 10024 WorkSource{10366 com.test.thalitest}
I/ConfigFetchService( 4199): launchTask
D/WifiService(  940): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5648): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
E/WifiTrafficPoller(  940): ADD_CLIENT: 6
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5648): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
D/PMS     (  940): releaseWL(2655388d): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
W/Finsky  ( 5544): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5648): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5648): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5648): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
D/Finsky  ( 5544): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
I/chromium( 5648): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
V/ConfigFetchTask( 4199): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WKcWMWvCU23ME-060oMI-0Nt2IjOb3iC_tLRYeRUCexn4OtPmmJcXEgqD3ZCQtJ-bFpFS_Ud9Gl0JMrv656wJP4FJRw9Yser-Q7_IOhdj7HzT8Olja7A3gGIHINz5t70wYo6olADobN6Ier3TB-mXNIhOx9wtE1MCFa8SbOLKn9wnkIVvfXavfqa9XQEjp-EPn0pB_
I/GoogleURLConnFactory( 4199): Using platform SSLCertificateSocketFactory
D/Finsky  ( 5544): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5544): [1] DailyHygiene.reschedule: Giving up. (failures=6)
D/PMS     (  940): acquireWL(c7c32bb): PARTIAL_WAKE_LOCK  Icing 0x1 4199 10024 WorkSource{10024 com.google.android.gms}
D/Process (  940): killProcessQuiet, pid=5246
I/ActivityManager(  940): Killing 5246:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  940): releaseWL(c7c32bb): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
D/DeviceConnectionService( 1820): client connected with version: 7571000
E/Prism.WidgetManager( 1557): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1557): onLoadItems() -
I/Prism.ItemManager( 1557): loadItems() com.htc.launcher.pageview.WidgetManager@105bcc0 -
I/ActivityManager(  940): Recipient 5246
D/ChimeraCfgMgr( 4199): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4199): Module APK com.google.android.play.games already loaded
D/Process (  940): killProcessQuiet, pid=3644
I/ActivityManager(  940): Killing 3644:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/ChimeraCfgMgr( 4199): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 4199): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 4199): Failed to find package metadata for com.test.thalitest
D/Vision  ( 4199): No vision deps
D/libc    ( 4199): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4199): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4199): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4199): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4199): [NET] android_getaddrinfo_proxy+
D/libc    ( 4199): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4199): [NET] android_getaddrinfo_proxy-, NODATA
W/ConfigFetchTask( 4199): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 4199): fetch service done; releasing wakelock
D/PMS     (  940): releaseWL(3a1f613e): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10366 com.test.thalitest}
I/ConfigFetchService( 4199): stopping self
I/ActivityManager(  940): Recipient 3644
I/ActivityManager(  940): Killing 5295:com.google.android.setupwizard/u0a77 (adj 15): empty #18
D/Process (  940): killProcessQuiet, pid=5295
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  940): Recipient 5295
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4199, uid=10024, userID:0
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4199, uid=10024, userID:0
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4199, uid=10024, userID:0
I/CheckinService( 4199): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  940): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5794 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/PeopleContactsSync( 4199): CP2 sync disabled
,I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4199, uid=10024, userID:0
,W/BaseAppContext( 4199): Using Auth Proxy for data requests.
,W/BaseAppContext( 4199): Using Auth Proxy for data requests.
,W/BaseAppContext( 4199): Using Auth Proxy for data requests.
,W/BaseAppContext( 4199): Using Auth Proxy for data requests.
,W/BaseAppContext( 4199): Using Auth Proxy for data requests.
,W/BaseAppContext( 4199): Using Auth Proxy for data requests.
,W/jxcore-log( 5648): Initializing JXcore engine
,W/jxcore-log( 5648): JXcore engine is ready
,W/jxcore-log( 5648): Starting JXcore engine
,D/ChimeraCfgMgr( 4199): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4199): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 5794): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5794):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5794):   adb logcat -s GAv4
,W/GAv4    ( 5794): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 5794): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5794): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/AnalyticsTrackerProxyImpl( 5794): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,D/VoldConnector(  940): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 5794): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,D/PMS     (  940): acquireWL(184035f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 5632 10167 null
,D/PMS     (  940): acquireWL(288495ee): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5632 10167 null,
D/PMS     (  940): releaseWL(184035f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  940): releaseWL(288495ee): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,W/ResourcesManager( 5794): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5794): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5794): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  940): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5837 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a,
,I/UpdateIcingCorporaServi( 5463): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/System  ( 5794): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5794): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/SyncApplication( 5837): Loading default preferences,
,W/Resources( 5837): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,W/asset   ( 5463): Copying FileAsset 0x557f6f8700 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/UpdateIcingCorporaServi( 5463): UpdateCorporaTask done [took 60 ms] updated apps [took 60 ms] 
,I/ActivityManager(  940): Killing 5401:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  940): killProcessQuiet, pid=5401
,D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  940): ADD_CLIENT: 7
,D/WifiService(  940): New client listening to asynchronous messages
,D/SyncApplication( 5837): Overriding preferences with custom values,
,D/SyncApplication( 5837): Updating preferences succeeded,
,I/ActivityManager(  940): Recipient 5401,
,E/SyncApplication( 5837): Application created.,
,W/VolumeInfo( 5837): Unable to read mount points,
W/VolumeInfo( 5837): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5837): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5837): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5837): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5837): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5837): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5837): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5837): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5837): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5837): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5837): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5837): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5837): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5837): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5837): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5837): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
,W/VolumeInfo( 5837): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5837): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5837): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5837): 	... 13 more
V/VolumeInfo( 5837): Found 0 mount point(s)
,V/VolumeInfo( 5837): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 5837): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/,
,I/CalendarDefines( 5837): getNewCalendarAuthority()...,
,I/PackageManager(  940):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5837, uid=10005, userID:0
D/VolumeInfo( 5837): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/PackageManager(  940): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
W/VolumeInfo( 5837): Can not create volume ID for unmounted volume null,
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5837, uid=10005, userID:0
D/SyncApplication( 5837): enableAppOperation()+
W/PackageManager(  940): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 5837): enableAppOperation()-
D/HTCUtilities( 5837): isNeorSinged() + 
,D/HTCUtilities( 5837): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 5837): isNeorSinged() return false
,D/CDMountReceiver( 5837): whether to enable CD Auto-mount: true
D/CDMountReceiver( 5837): showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
D/AutoSetting( 1483): service - handleMessage() stop self
,I/ActionCombine( 5837): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/AutoSetting( 1483): service - handleMessage() quit looper
,D/AutoSetting( 1483): service - onDestroy() END
D/CDMountReceiver( 5837): enable CD Auto-mount: true
,D/PMS     (  940): releaseWL(1c6b6c9f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10005},
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/PMS     (  940): acquireWL(15941752): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5093 10159 null,
,D/HTCUtilities( 5837): enable auto-mount
,D/HTCUtilities( 5837): enable auto-mount
,I/HtcMountManagerAdapter( 5837): mHtcMountManager is  null
,I/HtcMountManagerAdapter( 5837): mStorageManager is  not null
I/HtcMountManagerAdapter( 5837): mHtcMountManager is  null
I/HtcMountManagerAdapter( 5837): mStorageManager is  not null
,D/VoldConnector(  940): SND -> {22 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
D/VoldConnector(  940): SND -> {21 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
I/RemoteViews( 1218): apply : com.nero.android.htc.sync 1 10 4 38
,D/MountService(  940): mountISO: /system/etc/PCTOOL.ISO
,D/MountService(  940): mountISO: /system/etc/PCTOOL.ISO
,I/RemoteViews( 1218): apply : com.nero.android.htc.sync 0 11 3 53
,I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5093, uid=10159, userID:0,
,I/MusicLeanback( 5093): Conditions not met for autocaching. okToAttempt=false,
D/PMS     (  940): releaseWL(15941752): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 5093): Stop autocaching.
D/GCM     ( 1904): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/WearableService( 4680): callingUid 10024, callindPid: 4680
D/AuthorizationBluetoothService( 1904): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4199): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4199, uid=10024, userID:0
,E/MDM     ( 1820): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4199): Restart initialization of location
,E/GmsUtils( 5093): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 5093): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/Finsky  ( 5544): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive
,I/HtcModeClient( 3105): handler message = 4011
,E/HtcModeClient( 3105): Check connection and retry 7 times.
,I/ConfigService( 1904): onDestroy
,I/ActivityManager(  940): Waited long enough for: ServiceRecord{2834bb u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
,I/art     (  940): Explicit concurrent mark sweep GC freed 19074(952KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.619ms total 131.429ms,
,I/ActivityManager(  940): Waited long enough for: ServiceRecord{219b6197 u0 com.htc.musicenhancer/.EnhancerService},
,D/Process (  940): killProcessQuiet, pid=5168,
I/ActivityManager(  940): Killing 5168:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 5168
,D/Process (  940): killProcessQuiet, pid=5217
I/ActivityManager(  940): Killing 5217:com.htc.sdm/u0a79 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 5217
,W/MediaManager( 5039): [DualLensScanUtil],	mmpCursor count is 0
,D/Process (  940): killProcessQuiet, pid=4593
I/ActivityManager(  940): Killing 4593:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 4593
,I/ActivityManager(  940): Killing 5351:com.google.android.gm/u0a106 (adj 15): empty #17,
D/Process (  940): killProcessQuiet, pid=5351
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 5351
,I/HtcModeClient( 3105): handler message = 4011,
E/HtcModeClient( 3105): Check connection and retry 8 times.
,W/jxcore-log( 5648): Platform android,
W/jxcore-log( 5648): 
W/jxcore-log( 5648): Process ARCH arm
W/jxcore-log( 5648): 
,I/jxcore-log( 5648): JXcore Cordova bridge is ready!,
I/jxcore-log( 5648): 
,W/jxcore-log( 5648): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5648): execute: REQUEST_ACCESS_COARSE_LOCATION,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/HtcModeClient( 3105): handler message = 4011,
E/HtcModeClient( 3105): Check connection and retry 9 times.,
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5648): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved",
V/io.jxcore.node.JXcoreExtension( 5648): isBleMultipleAdvertisementSupported: NOT_RESOLVED
,I/jxcore-log( 5648): BLE multiple advertisement supported
I/jxcore-log( 5648): 
,D/PMS     (  940): acquireWL(370ca65a): PARTIAL_WAKE_LOCK  *alarm* 0x1 940 1000 WorkSource{10072}
V/AlarmManager(  940): sending alarm PendingIntent{eae708b: PendingIntentRecord{3d127568 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457141911726, Int=0
V/AlarmManager(  940): sending alarm PendingIntent{1711dd81: PendingIntentRecord{16dece26 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=85733, Int=0
,V/AlarmManager(  940): sending alarm PendingIntent{37118a67: PendingIntentRecord{3d4d8014 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=86183, Int=0
,D/libc    (  940): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  940): releaseWL(370ca65a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  940): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  940): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  940): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  940): [NET] android_getaddrinfo_proxy+
D/libc    (  940): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
,D/libc    (  940): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 5648): My device name is: HTC-HTC One M8s
I/jxcore-log( 5648): 
,D/Finsky  ( 5544): [577] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5544): [1] 5.onFinished: Installation state replication succeeded.,
,D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 3105): handler message = 4011
,E/HtcModeClient( 3105): Check connection and retry 10 times.
,I/HtcModeClient( 3105): handler message = 4011
,E/HtcModeClient( 3105): Check connection and retry 11 times.
,D/PMS     (  940): acquireWL(1dbbbbb9): PARTIAL_WAKE_LOCK  Icing 0x1 4199 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  940): releaseWL(1dbbbbb9): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  940): acquireWL(880927b): PARTIAL_WAKE_LOCK  Icing 0x1 4199 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  940): releaseWL(880927b): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  940): acquireWL(108c28f1): PARTIAL_WAKE_LOCK  Icing 0x1 4199 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): releaseWL(108c28f1): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl(  940): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/HtcModeClient( 3105): handler message = 4011,
E/HtcModeClient( 3105): Check connection and retry 12 times.
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native,
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 5648): ,
,I/io.jxcore.node.ConnectivityInfo( 5648): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 5648):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5648):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 5648):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo( 5648):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5648):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 5648):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 5648):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 5648):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 5648): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,I/jxcore-log( 5648): INFO thaliMobileNativeWrapper Method networkChanged registered to native,
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native,
I/jxcore-log( 5648): 
,D/PMS     (  940): acquireWL(1b8d0cd6): PARTIAL_WAKE_LOCK  *alarm* 0x1 940 1000 WorkSource{10024}
V/AlarmManager(  940): sending alarm PendingIntent{387bdb57: PendingIntentRecord{6848e9d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=103963, Int=0
,D/PMS     (  940): acquireWL(5db1644): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1904 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  940): releaseWL(1b8d0cd6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1904): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1904): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1904): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1904): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1904): [NET] android_getaddrinfo_proxy+
D/libc    ( 1904): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1904): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  940): releaseWL(5db1644): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/HtcModeClient( 3105): handler message = 4011
,E/HtcModeClient( 3105): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3105): Don't start project servcice
,D/HtcModeClient( 3105): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 3105): connectState: CONNECTION_READY = false
,D/SilentMusic( 3105): call stop
D/HtcModeClient( 3105): close connection
W/HtcModeClient( 3105): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3105): read the terminate packet, so break
,I/ActivityManager(  940): Killing 3105:com.htc.autobot/u0a47 (adj 15): empty #17
,D/Process (  940): killProcessQuiet, pid=3105
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 3105
,I/ActivityManager(  940): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5889 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  940): acquireWL(3ba9632d): PARTIAL_WAKE_LOCK  *alarm* 0x1 940 1000 WorkSource{10076}
V/AlarmManager(  940): sending alarm PendingIntent{25252062: PendingIntentRecord{e78d5f3 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457141931311, Int=60000
D/PMS     (  940): releaseWL(3ba9632d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 5889): SMSBackupAgentService started
,D/SMSBackup( 5889): Checking restore status
,D/SMSBackup( 5889): Restore complete
,D/SMSBackup( 5889): cancelCheckAlarm
,D/SMSBackup( 5889): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  940): killProcessQuiet, pid=4656
I/ActivityManager(  940): Killing 4656:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 4656,
,I/SensorManager(  940): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@c2bdf64
,I/PMS     (  940): Going to sleep due to screen timeout (uid 1000)...
W/SensorService(  940): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  940): disable: get sensor name = Accelerometer Sensor
W/SensorService(  940): pid=940, uid=1000
,W/SensorService(  940): Active sensors: size = 4
W/SensorService(  940): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  940): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  940): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  940): Significant Motion (handle=0x0000000d, connections=1)
,W/SensorService(  940): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@c2bdf64, eanble = 0, strlen(mName) = 90
W/PMN     (  940): goingToSleep
W/SensorService(  940): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  940): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1f0d0317
W/SensorService(  940): Listener[1] = com.htc.smartdim.sensor_eye@30cd66f8
W/SensorService(  940): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1218): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off,
,W/PMS     (  940): mWirelessDisplayManager is null
,W/PMS     (  940): mWirelessDisplayManager is still null
D/PMS     (  940): acquireWL(3de60529): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 940 1000 null
W/PMN     (  940): goingToSleep done
W/HtcSystemUPManager(  940): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/PMS     (  940): Sleeping (uid 1000)...
D/XAN-DPS (  940): prepareColorFade 1
,D/PMS     (  940): releaseWL(3de60529): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/ActivityManager(  940): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5911 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/AlarmManager(  940): ACTION_SCREEN_ON
,I/Adreno-EGL(  940): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  940): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  940): Build Date: 03/09/15 Mon
I/Adreno-EGL(  940): Local Branch: 
I/Adreno-EGL(  940): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  940): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  940):                  d74aa161a12b9c6fc6332151
,I/AlarmManager(  940): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  940): [AlarmQueuing] done recovering
I/AlarmManager(  940): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  940): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiStateMachine(  940): handleMessage: E msg.what=131167
E/WifiStateMachine(  940): processMsg: InitialState
E/WifiStateMachine(  940):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  940): processMsg: DefaultState
,E/WifiStateMachine(  940):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
,W/ResourcesManager( 5911): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/WifiStateMachine(  940):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
,V/SRS_Proc(  436): ParamSet string: screen_state=on
,E/audio_a2dp_hw(  436): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  940): handleMessage: E msg.what=155650
D/WifiStateMachine(  940): getWifiLinkLayerStats: WIFI is not enbled
D/WifiStateMachine(  940): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  940): handleScreenStateChanged Exit: true
E/WifiStateMachine(  940): handleMessage: X
E/WifiStateMachine(  940): handleMessage: E msg.what=131154
E/WifiStateMachine(  940): processMsg: InitialState
D/WifiController(  940): processMsg: ApStaDisabledState
D/WifiController(  940): processMsg: DefaultState
E/WifiStateMachine(  940):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
D/NetworkPolicy(  940): updateScreenOn: false
E/WifiStateMachine(  940): processMsg: DefaultState
D/WifiController(  940): handleMessage: X
E/WifiStateMachine(  940):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  940): handleMessage: X
E/WifiStateMachine(  940): handleMessage: E msg.what=131127
E/WifiStateMachine(  940): processMsg: InitialState
E/WifiStateMachine(  940):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  940): processMsg: DefaultState
E/WifiStateMachine(  940):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  940): handleMessage: X
V/NetworkPolicy(  940): updateIfacesLocked()
E/WifiStateMachine(  940): handleMessage: E msg.what=131129
E/WifiStateMachine(  940): processMsg: InitialState
E/WifiStateMachine(  940):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  940): processMsg: DefaultState
E/WifiStateMachine(  940):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  940): handleMessage: X
,D/NetworkManagementService(  940): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/CalendarProvider2( 5911): Created com.android.providers.calendar.CalendarAlarmManager@31081b1c(com.htc.providers.calendar.HtcCalendarProvider@2c5e4325)
D/GpsLocationProvider(  940): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/CalendarProvider2( 5911): wait start:true
,D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1218): receive(android.intent.action.SCREEN_ON,1,false)
,D/CalendarProvider2( 5911): wait end:false
,D/XAN-DPS (  940): prepareColorFade done
D/PMS     (  940): acquireWL(d8321e3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1820 10024 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  940): setBrightness to 0
,D/PMS     (  940): acquireWL(dbac7e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1820 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  940): releaseWL(d8321e3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/DisplayManagerService(  940): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  940): Display changed displayId=0
D/PMS     (  940): releaseWL(dbac7e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
I/SensorManager(  940): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@1f0d0317
W/SensorService(  940): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  940): disable: get sensor name = CM32181 Light sensor
D/DotMatrix( 1309): [EventService]  onDisplayChanged: 0
,W/SensorService(  940): pid=940, uid=1000
W/SensorService(  940): Active sensors: size = 3
W/SensorService(  940): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  940): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  940): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  940): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@1f0d0317, eanble = 0, strlen(mName) = 67
W/SensorService(  940): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  940): Listener[0] = com.htc.smartdim.sensor_eye@30cd66f8
W/SensorService(  940): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,D/DotMatrix( 1309): [EventService] mbHDMIConnect: false, mCoverOn:false,
,I/SensorManager( 1218): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@18f174ef, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
,W/SensorService(  940): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  940): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  940): pid=1218, uid=10041,
W/SensorService(  940): Active sensors: size = 4
I/ActivityManager(  940): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5941 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
W/SensorService(  940): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  940): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  940): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  940): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  940): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@18f174ef, eanble = 1, strlen(mName) = 57
W/SensorService(  940): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  940): Listener[0] = com.htc.smartdim.sensor_eye@30cd66f8
W/SensorService(  940): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@18f174ef
,W/SensorService(  940): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/AlarmManager(  940): ACTION_SCREEN_OFF
,D/WifiDataStallTracker(  940): stopDataStallAlarm ,
I/AlarmManager(  940): [AlarmQueuing] screen off now: 
E/WifiDataStallTracker(  940): ENABLE_DATA_MONITOR_POLL false Token 0
I/AlarmManager(  940): [AlarmQueuing] data connection: true
E/WifiStateMachine(  940): handleMessage: E msg.what=131167
I/AlarmManager(  940): [AlarmQueuing] wifi connection: false
E/WifiStateMachine(  940): processMsg: InitialState
D/WifiDisplayAdapter(  940): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  940):     Client/Owner: Client
D/WifiDisplayAdapter(  940):     GroupId: 
D/WifiDisplayAdapter(  940):     Passphrase: 
D/WifiDisplayAdapter(  940):     SessionId: 0
D/WifiDisplayAdapter(  940):     IP Address: }
E/WifiStateMachine(  940):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  940): processMsg: DefaultState
E/WifiStateMachine(  940):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  940):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiStateMachine(  940): getWifiLinkLayerStats: WIFI is not enbled
E/WifiStateMachine(  940): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  940): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  940): handleScreenStateChanged Exit: false
E/WifiStateMachine(  940): handleMessage: X
E/WifiStateMachine(  940): handleMessage: E msg.what=131154
E/WifiStateMachine(  940): processMsg: InitialState
E/WifiStateMachine(  940):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  940): processMsg: DefaultState
E/WifiStateMachine(  940):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  940): handleMessage: X
,V/SRS_Proc(  436): ParamSet string: screen_state=off
E/audio_a2dp_hw(  436): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  940): handleMessage: E msg.what=155651
D/WifiController(  940): processMsg: ApStaDisabledState
D/WifiController(  940): processMsg: DefaultState
D/WifiController(  940): handleMessage: X
D/NetworkPolicy(  940): updateScreenOn: false
V/NetworkPolicy(  940): updateIfacesLocked()
D/NetworkManagementService(  940): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/GpsLocationProvider(  940): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1525): start background delete task...
,I/IntentController( 1218): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1525): size: 0 , 0
,D/ContactMessageStore( 1525): Background delete complete
,D/PMS     (  940): acquireWL(1f3bf93f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1820 10024 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 5941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  940): releaseWL(1f3bf93f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): acquireWL(2f433755): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1820 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): releaseWL(2f433755): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 5941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5941): MY_DEBUG = false
,I/RemoteViews( 1218): setHTCTheme(com.htc.updater,true,33751145)
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  940): Setting HAL interactive mode to false
D/SurfaceControl(  940): Excessive delay in setPowerMode(): 296ms
D/PMS     (  940): Setting HAL interactive mode to false done
D/PMS     (  940): Setting HAL auto-suspend mode to true
D/PMS     (  940): Setting HAL auto-suspend mode done
,W/HtcSystemUPManager(  940): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
I/InputMethodManagerService(  940): screenObserver, isScreenOn=false
D/StatusBarManagerService(  940): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  940): Disable input method client, pid=5648
I/InputMethodManager( 5648): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{3ef83413 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@c1935b4
D/SmartSyncUtils( 5941): isEpsOn(), nState = 0
,I/InputManager(  940): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,D/PMS     (  940): acquireWL(1380ea5b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null
,I/BatteryService(  940): n_update end
I/RemoteViews( 1218): apply : com.htc.updater 1 17 1 36
,D/PMS     (  940): releaseWL(1380ea5b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HABCtrl (  940): TPE algorithm. remove timeout.
D/PMS     (  940): OOBE c monitor 11
,D/PMS     (  940): acquireWL(32adb2f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5941 1000 null
,I/IntentController( 1218): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1537): ScreenObserver: OFF
,D/NfcService( 1537): applyRouting - 0,
D/HtcPowerSaver(  940): updateBatteryInfo
D/UsbnetService(  940): BroadcastReceiver::onReceive+
D/NotificationService(  940): plugged=true pluggin=true
D/UsbnetService(  940): onReceive BATTERY_CHANGED
D/PMS     (  940): runPSCheck
D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  940): battery changed pluggedType: 2
D/UsbnetService(  940): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  940): Checking...,
D/WifiController(  940): handleMessage: E msg.what=155652
,I/HtcPowerSaver(  940): >> updateStatus
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  940): acquireWL(244cf3d1): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1537 1027 null
D/WifiController(  940): processMsg: ApStaDisabledState
I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  940): processMsg: DefaultState
I/HtcPowerSaver(  940): << updateStatus,
,D/WifiController(  940): handleMessage: X
D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
D/NfcService( 1537): applyRouting -2
D/PMS     (  940): releaseWL(244cf3d1): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/NfcService( 1537): applyRouting
D/NfcService( 1537): Ignore this applyRouting...
,W/ContextImpl(  940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  940): releaseWL(32adb2f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartDim(  940): Init customizeScreenOffDelayClass error,
,W/ContextImpl( 5941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,I/ClockController( 1218): stop clock update:screen off,
W/ContextImpl( 5941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
D/SmartSyncUtils( 5941): isEpsOn(), nState = 0
,D/SmartSyncUtils( 5941): isEpsOn(), nState = 0,
,W/ContextImpl( 5941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  940): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@30cd66f8,
W/ContextImpl(  940): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
W/SensorService(  940): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  940): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  940): pid=940, uid=1000
W/SensorService(  940): Active sensors: size = 3
W/SensorService(  940): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  940): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  940): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  940): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@30cd66f8, eanble = 0, strlen(mName) = 36
W/SensorService(  940): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  940): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@18f174ef
W/SensorService(  940): void android::SensorService::listenerSensor(const char*, int32_t)--:,
W/SensorService(  940): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  940): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  940): pid=940, uid=1000
W/SensorService(  940): Active sensors: size = 2
W/SensorService(  940): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  940): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  940): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@30cd66f8, eanble = 0, strlen(mName) = 36
W/SensorService(  940): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  940): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@18f174ef
W/SensorService(  940): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  940): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@30cd66f8
,E/ActivityThread(  940): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@38a497d1 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  940): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@38a497d1 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  940): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  940): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  940): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  940): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  940): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  940): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  940): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  940): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  940): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  940): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  940): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  940): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  940): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  940): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  940): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  940): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  940): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  940): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  940): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5973 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
I/PowerUsageList:PowerUsageHelper( 5941): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5941): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 5941): calcPower(), no data,
,D/PowerUsageList:PowerUsageHelper( 5941): MY_DEBUG = false,
,D/SmartSyncUtils( 5941): getMobilePolicyEnabled, result = true
,I/ActivityManager(  940): Killing 5491:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  940): killProcessQuiet, pid=5491
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/WifiService(  940): New client listening to asynchronous messages,
E/WifiTrafficPoller(  940): ADD_CLIENT: 8
,I/ActivityManager(  940): Recipient 5491,
,D/PMS     (  940): releaseWL(18c16370): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,D/Process (  940): killProcessQuiet, pid=5728
,I/ActivityManager(  940): Killing 5728:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 5728,
,I/CalendarProvider2( 5911): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 5911): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar),
,I/ActivityManager(  940): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5998 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  940): Killing 5752:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  940): killProcessQuiet, pid=5752,
,D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 5752,
,W/ResourcesManager( 5998): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 5998): onCreate,
,D/ProviderChangeReceiver( 5998): ---------------------------------------------------
D/ProviderChangeReceiver( 5998): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  940): killProcessQuiet, pid=5515,
I/ActivityManager(  940): Killing 5515:com.android.settings/1000 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 5998): start to updateAlertNotification!
,I/ActivityManager(  940): Recipient 5515
,D/HtcAlertService( 5998): No fired or scheduled alerts
,D/HtcAlertUtils( 5998): -- cancelReminderNotification --
,D/HtcAlertUtils( 5998): broadcastExistReminder!
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
,D/HtcUPManager( 1218): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5648): 
,I/jxcore-log( 5648): Unit Test app is loaded,
I/jxcore-log( 5648): 
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 5648): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"},
I/jxcore-log( 5648): 
,I/chromium( 5648): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/ActivityManager(  940): Killing 5194:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  940): killProcessQuiet, pid=5194
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 5194,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  940): acquireWL(218706a4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 940 1000 WorkSource{1000},
V/AlarmManager(  940): sending alarm PendingIntent{1df93c25: PendingIntentRecord{1d1011fa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=115882, Int=0
V/AlarmManager(  940): sending alarm PendingIntent{315bfc0d: PendingIntentRecord{a0477c2 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457141954427, Int=0
V/AlarmManager(  940): sending alarm PendingIntent{27049d3: PendingIntentRecord{2c7fe910 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143057, Int=0
D/PMS     (  940): acquireWL(3dd94c09): PARTIAL_WAKE_LOCK  *backup* 0x1 940 1000 null
,W/BackupManagerService(  940): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  940): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  940): releaseWL(3dd94c09): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  940): releaseWL(218706a4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1218): Weather sync is On
,W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  940): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  940): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,W/ContextImpl(  940): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  940): acquireWL(22a64e0e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null
I/BatteryService(  940): n_update end
D/PMS     (  940): releaseWL(22a64e0e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  940): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  940): battery changed pluggedType: 2,
,D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1218): closing low battery warning: level=100
D/UsbnetService(  940): BroadcastReceiver::onReceive+
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  940): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  940): updateBatteryInfo
D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  940): runPSCheck
D/UsbnetService(  940): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  940): Checking...
D/WifiController(  940): handleMessage: E msg.what=155652
I/HtcPowerSaver(  940): >> updateStatus
D/WifiController(  940): processMsg: ApStaDisabledState
D/WifiController(  940): processMsg: DefaultState
D/WifiController(  940): handleMessage: X
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  940): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  940): acquireWL(196bb02f): PARTIAL_WAKE_LOCK  *alarm* 0x1 940 1000 WorkSource{1000},
D/libc    (  940): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  940): [NET] android_getaddrinfofornet-, err=8
D/libc    (  940): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  940): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    (  940): [NET] android_getaddrinfo_proxy+
V/AlarmManager(  940): sending alarm PendingIntent{37118a67: PendingIntentRecord{3d4d8014 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=147639, Int=0
D/libc    (  940): [NET] android_getaddrinfo_proxy get netid:0
,V/AlarmManager(  940): sending alarm PendingIntent{1df93c25: PendingIntentRecord{1d1011fa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=175881, Int=0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
V/AlarmManager(  940): sending alarm PendingIntent{15e2863c: PendingIntentRecord{6848e9d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=176295, Int=0
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    (  940): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  940): acquireWL(24c19fc5): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1904 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1904): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1904): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1904): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1904): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1904): [NET] android_getaddrinfo_proxy+
D/libc    ( 1904): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1904): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  940): releaseWL(24c19fc5): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1218): Weather sync is On,
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
D/PMS     (  940): releaseWL(196bb02f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1525): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/HtcUPManager( 1218): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcAppUPService( 1483): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@4070a47,
D/HtcUPManager( 1218): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/Process (  940): killProcessQuiet, pid=5794
I/ActivityManager(  940): Killing 5794:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 5794
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  940): acquireWL(3c7d3d1a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null
D/UsbnetService(  940): BroadcastReceiver::onReceive+
,I/BatteryService(  940): n_update end
D/UsbnetService(  940): onReceive BATTERY_CHANGED
D/PMS     (  940): releaseWL(3c7d3d1a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  940): updateBatteryInfo
D/UsbnetService(  940): BroadcastReceiver::onReceive-
D/NotificationService(  940): plugged=true pluggin=true
D/WifiController(  940): handleMessage: E msg.what=155652
D/PMS     (  940): runPSCheck
D/WifiController(  940): processMsg: ApStaDisabledState
D/HtcPowerSaver(  940): Checking...
D/WifiController(  940): processMsg: DefaultState
,I/HtcPowerSaver(  940): >> updateStatus
D/WifiController(  940): handleMessage: X
D/WifiController(  940): battery changed pluggedType: 2
D/PowerUI ( 1218): closing low battery warning: level=100
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  940): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  940): acquireWL(60d204b): PARTIAL_WAKE_LOCK  *alarm* 0x1 940 1000 WorkSource{1000}
V/AlarmManager(  940): sending alarm PendingIntent{186fca28: PendingIntentRecord{3a217341 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=192741, Int=0
,V/AlarmManager(  940): sending alarm PendingIntent{1df93c25: PendingIntentRecord{1d1011fa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=235881, Int=0
V/AlarmManager(  940): sending alarm PendingIntent{37118a67: PendingIntentRecord{3d4d8014 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=236304, Int=0
V/AlarmManager(  940): sending alarm PendingIntent{16a210e6: PendingIntentRecord{3c0b7627 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186086, Int=0
,D/libc    (  940): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
,D/PMS     (  940): acquireWL(180b60d4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1904 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  940): [NET] android_getaddrinfofornet-, err=8
D/libc    (  940): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  940): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  940): [NET] android_getaddrinfo_proxy+
,D/libc    (  940): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    (  940): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  940): releaseWL(180b60d4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): releaseWL(60d204b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1218): Weather sync is On
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  940): acquireWL(2c51027d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null
I/BatteryService(  940): n_update end
D/PMS     (  940): releaseWL(2c51027d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  940): BroadcastReceiver::onReceive+
D/NotificationService(  940): plugged=true pluggin=true
D/UsbnetService(  940): onReceive BATTERY_CHANGED
D/PowerUI ( 1218): closing low battery warning: level=100
D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  940): BroadcastReceiver::onReceive-
D/WifiController(  940): battery changed pluggedType: 2
D/WifiController(  940): handleMessage: E msg.what=155652
D/HtcPowerSaver(  940): updateBatteryInfo
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  940): runPSCheck
D/WifiController(  940): processMsg: ApStaDisabledState
D/HtcPowerSaver(  940): Checking...
D/WifiController(  940): processMsg: DefaultState
I/HtcPowerSaver(  940): >> updateStatus
D/WifiController(  940): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  940): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  940): acquireWL(36ee5572): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 940 1000 WorkSource{1000},
V/AlarmManager(  940): sending alarm PendingIntent{1df93c25: PendingIntentRecord{1d1011fa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=295882, Int=0
V/AlarmManager(  940): sending alarm PendingIntent{9af4dc3: PendingIntentRecord{6848e9d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=320966, Int=0
,D/PMS     (  940): acquireWL(3cf04979): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1904 10024 WorkSource{10024 com.google.android.gms},
V/AlarmManager(  940): sending alarm PendingIntent{354856be: PendingIntentRecord{f2f031f com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457142165530, Int=0
,D/libc    ( 1904): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1904): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1904): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1904): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 1904): [NET] android_getaddrinfo_proxy+
D/libc    ( 1904): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1904): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  940): releaseWL(3cf04979): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): releaseWL(36ee5572): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1218): Weather sync is On
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  940): acquireWL(12f1f66c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null
I/BatteryService(  940): n_update end
,D/PMS     (  940): releaseWL(12f1f66c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  940): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  940): updateBatteryInfo
D/UsbnetService(  940): onReceive BATTERY_CHANGED
D/NotificationService(  940): plugged=true pluggin=true
,D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  940): runPSCheck
D/UsbnetService(  940): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  940): Checking...
D/WifiController(  940): handleMessage: E msg.what=155652
I/HtcPowerSaver(  940): >> updateStatus
D/WifiController(  940): processMsg: ApStaDisabledState
D/PowerUI ( 1218): closing low battery warning: level=100
D/WifiController(  940): processMsg: DefaultState
D/WifiController(  940): battery changed pluggedType: 2
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  940): handleMessage: X
I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  940): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1904): Explicit concurrent mark sweep GC freed 15511(861KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 1.075ms total 77.128ms
,I/GLSUser ( 1904): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1904): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1904): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1904): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/ActionCombine( 1904): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,W/ResourcesManager( 1218): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 1218): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1309): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1309): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GLSActivity( 1904): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1904): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1904): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1904): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1904): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1904): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1904): 	at android.os.Binder.execTransact(Binder.java:454)
,W/ResourcesManager( 1309): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1309): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/PlayEventLogger( 5544): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5544): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5544): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5544): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5544): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5544): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5544): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1218): apply : com.google.android.gms 1 14 5 40
,W/System  ( 5544): Ignoring header User-Agent because its value was null.
,D/libc    ( 5544): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5544): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5544): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5544): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5544): [NET] android_getaddrinfo_proxy+
D/libc    ( 5544): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5544): [NET] android_getaddrinfo_proxy-, NODATA
,I/art     (  940): Explicit concurrent mark sweep GC freed 29358(1611KB) AllocSpace objects, 4(512KB) LOS objects, 33% free, 18MB/27MB, paused 1.696ms total 169.435ms,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  940): acquireWL(3895eb6e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null
I/BatteryService(  940): n_update end
D/PMS     (  940): releaseWL(3895eb6e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  940): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  940): updateBatteryInfo
D/UsbnetService(  940): onReceive BATTERY_CHANGED
,D/NotificationService(  940): plugged=true pluggin=true
D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  940): runPSCheck
D/UsbnetService(  940): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  940): Checking...
D/WifiController(  940): handleMessage: E msg.what=155652
,I/HtcPowerSaver(  940): >> updateStatus
D/WifiController(  940): processMsg: ApStaDisabledState
D/WifiController(  940): battery changed pluggedType: 2
D/WifiController(  940): processMsg: DefaultState
D/PowerUI ( 1218): closing low battery warning: level=100
D/WifiController(  940): handleMessage: X
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  940): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  940): acquireWL(aa4f20f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null,
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  940): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  940): releaseWL(aa4f20f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  940): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  940): updateBatteryInfo
D/UsbnetService(  940): onReceive BATTERY_CHANGED
D/NotificationService(  940): plugged=true pluggin=true
D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  940): runPSCheck
D/UsbnetService(  940): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  940): Checking...
D/WifiController(  940): handleMessage: E msg.what=155652
I/HtcPowerSaver(  940): >> updateStatus,
D/WifiController(  940): processMsg: ApStaDisabledState
D/WifiController(  940): battery changed pluggedType: 2
D/WifiController(  940): processMsg: DefaultState
D/PowerUI ( 1218): closing low battery warning: level=100
D/WifiController(  940): handleMessage: X
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  940): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1525): MSG_CHECK_DELETION >>,
D/ContactMessageStore( 1525): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1525): sku_id=118
D/ContactMessageStore( 1525): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1525): start background delete task...
,D/ContactMessageStore( 1525): size: 0 , 0,
D/ContactMessageStore( 1525): Background delete complete
,D/PMS     (  940): acquireWL(1095d29c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 940 1000 WorkSource{1000}
,V/AlarmManager(  940): sending alarm PendingIntent{1df93c25: PendingIntentRecord{1d1011fa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=355881, Int=0
V/AlarmManager(  940): sending alarm PendingIntent{369e64a5: PendingIntentRecord{6848e9d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=630720, Int=0
D/PMS     (  940): acquireWL(b9507a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1904 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1904): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1904): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1904): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1904): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1904): [NET] android_getaddrinfo_proxy+
D/libc    ( 1904): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1904): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  940): releaseWL(b9507a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1218): Weather sync is On
D/PMS     (  940): releaseWL(1095d29c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1904): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1904): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1904): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1904): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1904): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1904): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1904): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1904): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1904): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1904): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1904): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5544): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5544): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5544): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5544): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5544): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5544): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5544): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5544): Ignoring header User-Agent because its value was null.
D/libc    ( 5544): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5544): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5544): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5544): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5544): [NET] android_getaddrinfo_proxy+
D/libc    ( 5544): [NET] android_getaddrinfo_proxy get netid:0
I/RemoteViews( 1218): reapply : com.google.android.gms 3 40,
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5544): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  940): acquireWL(2c11acc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null
,I/BatteryService(  940): n_update end
,D/PMS     (  940): releaseWL(2c11acc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  940): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  940): updateBatteryInfo
D/UsbnetService(  940): onReceive BATTERY_CHANGED
D/NotificationService(  940): plugged=true pluggin=true
D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  940): runPSCheck
D/UsbnetService(  940): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  940): Checking...
I/HtcPowerSaver(  940): >> updateStatus
D/WifiController(  940): handleMessage: E msg.what=155652
D/WifiController(  940): processMsg: ApStaDisabledState
D/WifiController(  940): battery changed pluggedType: 2
D/WifiController(  940): processMsg: DefaultState
D/WifiController(  940): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1218): closing low battery warning: level=100
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  940): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  940): acquireWL(82ac115): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null
I/BatteryService(  940): n_update end
D/PMS     (  940): releaseWL(82ac115): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  940): updateBatteryInfo,
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1218): closing low battery warning: level=100
D/UsbnetService(  940): BroadcastReceiver::onReceive+
D/NotificationService(  940): plugged=true pluggin=true
D/UsbnetService(  940): onReceive BATTERY_CHANGED
,D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  940): runPSCheck
D/UsbnetService(  940): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  940): Checking...
I/HtcPowerSaver(  940): >> updateStatus
D/WifiController(  940): handleMessage: E msg.what=155652
D/WifiController(  940): processMsg: ApStaDisabledState
D/WifiController(  940): battery changed pluggedType: 2
D/WifiController(  940): processMsg: DefaultState
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  940): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  940): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  940): acquireWL(2c46cc2a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 940 1000 WorkSource{1000}
,V/AlarmManager(  940): sending alarm PendingIntent{1df93c25: PendingIntentRecord{1d1011fa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=655881, Int=0,
V/AlarmManager(  940): sending alarm PendingIntent{1711dd81: PendingIntentRecord{16dece26 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=807646, Int=0
,V/AlarmManager(  940): sending alarm PendingIntent{3ed5ea1b: PendingIntentRecord{3c0b7627 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=656273, Int=0,
,I/ActivityManager(  940): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6040 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  940): sending alarm PendingIntent{1a4b17b8: PendingIntentRecord{23835991 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457142542065, Int=0
V/AlarmManager(  940): sending alarm PendingIntent{3b5d80f6: PendingIntentRecord{266eaaf5 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457142786856, Int=0
,D/PMS     (  940): acquireWL(385f0cf7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1904 10024 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 5941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 5941): MY_DEBUG = false,
D/WeatherUtility( 1218): Weather sync is On
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
D/PMS     (  940): releaseWL(2c46cc2a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PowerUsageService( 5941): repeat time = 1457143686937
,D/PMS     (  940): acquireWL(2458b682): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1904 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): releaseWL(385f0cf7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  940): releaseWL(2458b682): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  940): acquireWL(1c4d25d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1904 10024 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 5941): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5941): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  940): releaseWL(1c4d25d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): acquireWL(1d3ea9c9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1904 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): releaseWL(1d3ea9c9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  940): acquireWL(25dfb8ce): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1904 10024 WorkSource{10024 com.google.android.gms}
,D/PowerUsageService( 5941): calcPower(), no data,
,D/PMS     (  940): acquireWL(7e4a3ef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1904 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): releaseWL(25dfb8ce): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1904): Vacuum at: now=1457142787123 tag=VacuumService,
,D/PMS     (  940): releaseWL(7e4a3ef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  940): acquireWL(367f1985): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1904 10024 WorkSource{10024 com.google.android.gms}
,E/cutils-trace( 6064): Error opening trace file: Permission denied (13),
I/dex2oat ( 6064): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6064): dex2oat: override thread count:4
,D/PMS     (  940): releaseWL(367f1985): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): acquireWL(2fc293da): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1904 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): releaseWL(2fc293da): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/dex2oat ( 6064): dex2oat took 990.121ms (threads: 4),
,I/PushClient( 6040): ApplicationMonitor {256bfe87}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6040): ApplicationMonitor {256bfe87}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6040): ApplicationMonitor {256bfe87}: logBasicAppInfo(): VersionName:             1.2.853019,
I/PushClient( 6040): ApplicationMonitor {256bfe87}: logBasicAppInfo(): VersionCode:             148001224,
,I/PushClient( 6040): ApplicationMonitor {256bfe87}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6040): ApplicationMonitor {256bfe87}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6040): ApplicationMonitor {256bfe87}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6040): ApplicationMonitor {256bfe87}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6040): ApplicationMonitor {256bfe87}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6040): PnsModel {1447fec6}: update(): Update registration caused by: alarm
,I/PushClient( 6040): PnsConfigModel {2edf3f95}: <init>(): Use dm-client for provisioning.
,W/System.err( 6040): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6040): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6040): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6040): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  940): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6072 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/art     (  445): Explicit concurrent mark sweep GC freed 8650(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 213us total 47.029ms
,I/art     (  445): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 350us total 28.341ms
,I/art     (  445): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 175us total 25.367ms
,I/DeviceManagement( 6072): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6072 dbg=false s=true
,I/DeviceManagement( 6072): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6072): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6072): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6072): WorkflowService: Starting workflow service
,I/DeviceManagement( 6072): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@4d4eca1] args=[Bundle[mParcelledData.dataSize=88]]
I/DeviceManagement( 6072): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6072): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6072): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6072): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6072): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6072): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6072): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6072): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@4d4eca1],
,I/DeviceManagement( 6072): WorkflowService: Stopping workflow service
,D/Process (  940): killProcessQuiet, pid=5632
I/ActivityManager(  940): Killing 5632:com.google.android.apps.plus/u0a167 (adj 15): empty #17,
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 5632
,I/PushClient( 6040): PnsModel {1447fec6}: update(): The registration record has not expired yet. No need to update.
,D/Process (  940): killProcessQuiet, pid=5463
I/ActivityManager(  940): Killing 5463:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 5463
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1904): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1904): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1904): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1904): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1904): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1904): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1904): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1904): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1904): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1904): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1904): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5544): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5544): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5544): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5544): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5544): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5544): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5544): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5544): Ignoring header User-Agent because its value was null.
I/RemoteViews( 1218): reapply : com.google.android.gms 2 40
D/libc    ( 5544): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5544): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5544): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5544): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5544): [NET] android_getaddrinfo_proxy+,
D/libc    ( 5544): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5544): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  940): acquireWL(2e634573): PARTIAL_WAKE_LOCK  *alarm* 0x1 940 1000 WorkSource{1000},
V/AlarmManager(  940): sending alarm PendingIntent{295fcc30: PendingIntentRecord{2b20c0a9 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457142837292, Int=0
,D/SmartSyncUtils( 5941): isEpsOn(), nState = 0,
,D/PMS     (  940): releaseWL(2e634573): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  940): acquireWL(35bb62e): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5941 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 5941): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 5941): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5941): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 5941): SettingOnTime = 1457157600000, randomSettingOnTime = 1457155132000
D/SmartSyncScreenOnOffTimeReceiver( 5941): SettingOffTime = 1457222400000, randomSettingOffTime = 1457225244000
,D/SmartSyncScreenOnOffTimeReceiver( 5941): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5941): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 5941): bNightModeTurnOffOnce = false
,D/PMS     (  940): releaseWL(35bb62e): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  940): acquireWL(3522c5cf): PARTIAL_WAKE_LOCK  *alarm* 0x1 940 1000 WorkSource{1000}
V/AlarmManager(  940): sending alarm PendingIntent{52d7b5c: PendingIntentRecord{151bbe65 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1457142837326, Int=0
,W/ContextImpl( 5941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncDataLinkTurnOffService( 5941): SMARTSYNC_TURN_OFF_NETWORK, current time = 1457142837346, randomOffTime = 1457225244000, newRandomOffTime = 1457225244000,
,D/SmartSyncDataLinkTurnOffService( 5941): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 0, randomMobileOnTime = 1457155132000
,D/PMS     (  940): releaseWL(3522c5cf): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/SmartSyncUtils( 5941): getMobilePolicyEnabled, result = true
D/SmartSyncDataLinkTurnOffService( 5941): turnOffMobile bPolicyEnabled = true
,D/SmartSyncUtils( 5941): isWifiHotSpotEnabled = false,
,D/SmartSyncDataLinkTurnOffService( 5941): turnOffMobile bCheckMobileData = false,
,D/LocationManagerService(  940): getProviders()=[gps, network]
D/LocationManagerService(  940): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  940): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1],
D/SmartSyncDataLinkTurnOffService( 5941): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0,
,D/SmartSyncUtils( 5941): isCharging status = 5,
,D/SmartSyncDataLinkTurnOffService( 5941): turnOffWifi ui setting = false
,D/PMS     (  940): acquireWL(32afefeb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null,
I/BatteryService(  940): n_update end
D/PMS     (  940): releaseWL(32afefeb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  940): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  940): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  940): runPSCheck
D/UsbnetService(  940): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  940): Checking...
D/UsbnetService(  940): onReceive BATTERY_CHANGED
,I/HtcPowerSaver(  940): >> updateStatus
D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  940): BroadcastReceiver::onReceive-
D/WifiController(  940): battery changed pluggedType: 2,
D/WifiController(  940): handleMessage: E msg.what=155652
I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  940): processMsg: ApStaDisabledState
I/HtcPowerSaver(  940): << updateStatus
D/WifiController(  940): processMsg: DefaultState
D/WifiController(  940): handleMessage: X
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  940): acquireWL(2ac4f148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null
I/BatteryService(  940): n_update end
D/PMS     (  940): releaseWL(2ac4f148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  940): updateBatteryInfo
D/NotificationService(  940): plugged=true pluggin=true
D/PowerUI ( 1218): closing low battery warning: level=100
,D/UsbnetService(  940): BroadcastReceiver::onReceive+
D/PMS     (  940): runPSCheck
D/UsbnetService(  940): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  940): Checking...
D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  940): battery changed pluggedType: 2
D/UsbnetService(  940): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  940): >> updateStatus
D/WifiController(  940): handleMessage: E msg.what=155652
D/WifiController(  940): processMsg: ApStaDisabledState
D/WifiController(  940): processMsg: DefaultState
D/WifiController(  940): handleMessage: X
,D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  940): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  940): acquireWL(1d0edbe1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 940 1000 WorkSource{1000},
V/AlarmManager(  940): sending alarm PendingIntent{1df93c25: PendingIntentRecord{1d1011fa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1015881, Int=0
V/AlarmManager(  940): sending alarm PendingIntent{17585d06: PendingIntentRecord{6848e9d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1209304, Int=0,
,D/PMS     (  940): acquireWL(159b9fc7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1904 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1904): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1904): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1904): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1904): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1904): [NET] android_getaddrinfo_proxy+
D/libc    ( 1904): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1904): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  940): releaseWL(1d0edbe1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/PMS     (  940): releaseWL(159b9fc7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1218): Weather sync is On
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,I/UsageStatsService(  940): User[0] Flushing usage stats to disk
,D/PMS     (  940): acquireWL(38dbd9f4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null,
I/BatteryService(  940): n_update end
D/PMS     (  940): releaseWL(38dbd9f4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  940): BroadcastReceiver::onReceive+,
D/NotificationService(  940): plugged=true pluggin=true
D/UsbnetService(  940): onReceive BATTERY_CHANGED
D/WifiController(  940): battery changed pluggedType: 2
D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  940): updateBatteryInfo
D/UsbnetService(  940): BroadcastReceiver::onReceive-
D/PMS     (  940): runPSCheck
,D/WifiController(  940): handleMessage: E msg.what=155652
D/HtcPowerSaver(  940): Checking...
D/WifiController(  940): processMsg: ApStaDisabledState
I/HtcPowerSaver(  940): >> updateStatus
D/WifiController(  940): processMsg: DefaultState
D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  940): handleMessage: X
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  940): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1904): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1904): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1904): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1904): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1904): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1904): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1904): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1904): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1904): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1904): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1904): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1904): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5544): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5544): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5544): ,	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5544): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5544): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5544): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5544): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5544): Ignoring header User-Agent because its value was null.
D/libc    ( 5544): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5544): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5544): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5544): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5544): [NET] android_getaddrinfo_proxy+
D/libc    ( 5544): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5544): [NET] android_getaddrinfo_proxy-, NODATA
,I/RemoteViews( 1218): reapply : com.google.android.gms 8 40
,TIME-OUT KILL (timeout was 1200000ms)
```
