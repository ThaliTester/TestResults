#### Test 613623665d5a4d6_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
I/art     (  414): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 178us total 22.002ms
D/Process (  954): killProcessQuiet, pid=5077
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
--------- beginning of system
I/ActivityManager(  954): Killing 5077:com.htc.backupreset/1000 (adj 15): empty #17
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5600): -onCreate()
I/ActivityManager(  954): Recipient 5077
,V/Settings:HtcSettingsApplication( 5600): [5600/5600] onCreate()
I/ActivityManager(  954): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5652 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  954): killProcessQuiet, pid=5099
I/ActivityManager(  954): Killing 5099:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/Settings:HtcWirelessFeatureFlags( 5600): id/is att sku: 118/false
I/ActivityManager(  954): Recipient 5099
E/Settings:HtcWrapHeaderInfo( 5600): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5600): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 5600): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 5600): isSupportMusicChannel(): false
I/Prism.ItemManager( 1547): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1547): loadItems() com.htc.launcher.pageview.WidgetManager@2f0cda9c +
I/Prism.WidgetManager( 1547): onLoadItems() +
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportHomeButton]support         :false
E/cutils-trace( 5647): Error opening trace file: Permission denied (13)
I/ActivityManager(  954): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5600): isSupportVoWifi: null
E/ActivityThread( 5600): Failed to find provider info for com.htc.vowifi
W/ResourcesManager( 1547): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5600): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 5600): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 5600): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5600): [supportHomeButton]support         :false
I/ActivityManager(  954): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5600): isSupportVoWifi: null
E/ActivityThread( 5600): Failed to find provider info for com.htc.vowifi
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5652, uid=10072, userID:0
W/global  ( 5652): [apache-http] Connection GC has been deprecated!
D/CustomizationManager( 5647): ====startRecUseTime====
D/htc.customization.log.level( 5647):  is 
W/CustomizationLogLevel( 5647): Level value is invalid, use default level 2
D/Finsky  ( 5652): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 5652): [apache-http] Connection GC has been deprecated!
D/CustomizationManager( 5647):  Read ACC file spent 0.039 (s)
D/CIDMapFileReader( 5647): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5647): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5647): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5647): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5647): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5647): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5647): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5647): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5647): Parsing tag category name = system
I/CustomizationCIDLoader( 5647): Parsing tag category name = application
I/CustomizationCIDLoader( 5647): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5647): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5647): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5647): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5647): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5647): add string-array item, value = 42507
I/CustomizationCIDLoader( 5647): add string-array item, value = 21902
I/CustomizationCIDLoader( 5647): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5647): add string-array item, value = 23420
I/CustomizationCIDLoader( 5647): add string-array item, value = 22299
I/CustomizationCIDLoader( 5647): add string-array item, value = 24002
I/CustomizationCIDLoader( 5647): add string-array item, value = 23210
I/CustomizationCIDLoader( 5647): add string-array item, value = 23205
I/CustomizationCIDLoader( 5647): add string-array item, value = 23806
I/CustomizationCIDLoader( 5647): add string-array item, value = 23430
I/CustomizationCIDLoader( 5647): add string-array item, value = 23408
I/CustomizationCIDLoader( 5647): add string-array item, value = 27205
I/CustomizationCIDLoader( 5647): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5647): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5647): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5647): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5647): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5647): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5647): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5647): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5647): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5647): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5647): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5647): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5647):  Read CID file spent 0.082 (s)
D/CustomizationManager( 5647):  All configurations done spent 0.083 (s)
I/ActivityManager(  954): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5647 on display 0
D/PMS     (  954): acquireHCC(2fcd5047): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 954 1000 null
D/PMS     (  954): acquireHCC(6cb0074): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 954 1000 null
W/global  ( 5652): [apache-http] Connection GC has been deprecated!
W/asset   (  954): Copying FileAsset 0x5575e44b90 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  954): acquireWL(184a9e3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 954 1000 null
W/ResourcesManager( 1547): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/FeedHostManager( 1547): [onPause]
I/FeedProviderManager( 1547): onPause
I/FeedHostManager( 1547): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@350386aa
I/SocialFeedProvider( 1547): +onPause
I/SocialFeedProvider( 1547): -onPause
I/AnimationUtil(  954): isHTCRecent(ThaliTest/Recent screens.)/5
W/HtcSystemUPManager(  954): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/Finsky  ( 5652): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager(  954): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5708 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  954): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  954): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  954): hiding MENU key
W/asset   ( 5708): Copying FileAsset 0xac3ca0f0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  954): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5730 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
D/Process (  954): killProcessQuiet, pid=5124
I/ActivityManager(  954): Killing 5124:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/TrimMemoryManager( 1547): [trimMemory] 20
W/Settings( 5652): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5652): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5652, uid=10072, userID:0
W/asset   ( 1547): Copying FileAsset 0x5575d08a90 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
I/ActivityManager(  954): Recipient 5124
,W/ResourcesManager( 5730): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5730): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 5652): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5652): [1] 2.run: Finished loading 1 libraries.
,I/MultiDex( 5730): VM with version 2.1.0 has multidex support
,I/MultiDex( 5730): install
I/MultiDex( 5730): VM has multidex support, MultiDex support library is disabled.
I/Prism.WidgetManager( 1547): onLoadItems() -
I/Prism.ItemManager( 1547): loadItems() com.htc.launcher.pageview.WidgetManager@2f0cda9c -
D/Finsky  ( 5652): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 5730): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/PhoneApp( 1499): EVENT_QUERY_MO_PACKAGES
,D/Finsky  ( 5652): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PackageBroadcastService( 4269): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/PhoneApp( 1499): -- N1 =0
D/PhoneApp( 1499): -- N2 =0
,D/PhoneApp( 1499): -- N3 =0
,I/ActivityManager(  954): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5758 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 4269): Null package name or gms related package.  Ignoreing.
,D/Process (  954): killProcessQuiet, pid=4624,
I/ActivityManager(  954): Killing 4624:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/System  ( 5730): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23ca2f1d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,W/ActivityThread( 5730): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 5730): Installed default security provider GmsCore_OpenSSL
,I/WebViewFactory( 5708): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/ActivityManager(  954): Recipient 4624
,V/AlarmManager(  954): sending alarm PendingIntent{36e53b41: PendingIntentRecord{cee38e6 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457344287864, Int=0,
,D/PMS     (  954): acquireWL(3ea87e27): PARTIAL_WAKE_LOCK  Icing 0x1 4269 10024 WorkSource{10024 com.google.android.gms}
,W/ResourcesManager( 5758): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 4269): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  954): releaseWL(3ea87e27): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/LibraryLoader( 5708): Time to load native libraries: 12 ms (timestamps 2054-2066)
,I/LibraryLoader( 5708): Expected native library version number "",actual native library version number "",
,I/art     ( 3654): Explicit concurrent mark sweep GC freed 4237(214KB) AllocSpace objects, 0(0B) LOS objects, 73% free, 1505KB/5MB, paused 1.260ms total 24.748ms
,V/WebViewChromiumFactoryProvider( 5708): Binding Chromium to main looper Looper (main, tid 1) {3fc01391}
I/LibraryLoader( 5708): Expected native library version number "",actual native library version number ""
,I/chromium( 5708): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5708): Initializing chromium process, singleProcess=true
,W/art     ( 5708): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5708): ApplicationContext is null in ApplicationStatus
,I/art     ( 4269): Explicit concurrent mark sweep GC freed 20801(1485KB) AllocSpace objects, 17(340KB) LOS objects, 46% free, 4MB/8MB, paused 3.401ms total 69.934ms
,I/iu.UploadsManager( 4269): End new media; added: 0, uploading: 0, time: 175 ms
,W/chromium( 5708): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5708): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 5708): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 5708): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5708): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5708): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5708): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5708): Local Branch: 
I/Adreno-EGL( 5708): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5708): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5708):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  954): Message: MESSAGE_REGISTER_ADAPTER,
D/BluetoothManagerService(  954): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8aca796:true
W/System.err(  954): java.lang.Throwable: stack dump
W/System.err(  954): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  954): ,	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  954): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  954): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 5708): 524376013: getState() :  mService = null. Returning STATE_OFF
,D/Process (  954): killProcessQuiet, pid=5171
I/ActivityManager(  954): Killing 5171:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5171
,D/WifiService(  954): Client connection lost with reason: 4
,W/art     ( 5708): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5708): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5708): CordovaWebView is running on device made by: HTC
,I/art     (  954): Explicit concurrent mark sweep GC freed 18378(1016KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.793ms total 131.172ms,
,V/AlarmManager(  954): sending alarm PendingIntent{2c09282b: PendingIntentRecord{6656488 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457344288376, Int=0
,W/art     ( 5708): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5708): Attempt to remove local handle scope entry from IRT, ignoring
D/Finsky  ( 5652): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PMS     (  954): acquireWL(1b304134): PARTIAL_WAKE_LOCK  AsyncService 0x1 5758 10167 null
D/PMS     (  954): releaseWL(1b304134): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  954): acquireWL(2cc81cd2): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5758 10167 null
V/Finsky  ( 5652): [1] GearheadStateMonitor.onReady: sIsProjecting:false
V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UpdateIcingCorporaServi( 5567): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/PMS     (  954): releaseWL(2cc81cd2): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
W/chromium( 5708): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/GLSUser ( 1942): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1942): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1942): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1942): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[PluginManager]RegisterService( 1466): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1466): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1547): action: android.intent.action.PACKAGE_ADDED
I/ActivityManager(  954): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5831 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
D/FindExtension( 5708): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
W/Finsky  ( 5652): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1942): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1942): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1942): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1942): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/UpdateIcingCorporaServi( 5567): UpdateCorporaTask done [took 140 ms] updated apps [took 140 ms] 
V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DeviceManagement( 5831): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5831 dbg=false s=true
I/DeviceManagement( 5831): PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
I/InputMethodManager( 5708): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@35951139, mServedView=org.apache.cordova.engine.SystemWebView{6cde37e VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@126e70df
I/InputMethodManagerService(  954): Disable input method client, pid=1547
D/StatusBarManagerService(  954): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  954): Enable input method client, pid=5708
I/PhoneStatusBar( 1246): setImeWindowStatus(false,false)
I/ActivityManager(  954): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5857 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
D/PMS     (  954): releaseWL(184a9e3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  954): Displayed com.test.thalitest/.MainActivity: +1s411ms
I/ActivityManager(  954): Waited long enough for: ServiceRecord{70c4919 u0 com.htc.club/com.mcrm.autonotification.NotificationService}
D/HtcCupdReceiver(Provider)( 5857):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
D/Process (  954): killProcessQuiet, pid=5247
I/ActivityManager(  954): Killing 5247:com.htc.task.gtask/u0a66 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
W/XT9_C   ( 1388): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1388): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1388): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1388): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 5708): Cannot call determinedVisibility() - never saw a connection for the pid: 5708
I/ActivityManager(  954): Recipient 5247
V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/JsMessageQueue( 5708): Set native->JS mode to OnlineEventsBridgeMode
D/PackageBroadcastService( 4269): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 4269): Loading module com.google.android.gms.games from APK com.google.android.play.games
I/GLSUser ( 1942): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1942): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1942): [GLSUser] Extracting token using key: Auth
D/ChimeraModuleLdr( 4269): Loading module APK com.google.android.play.games
W/GLSActivity( 1942): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  954): acquireWL(3cad5ad7): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4269 10024 null
W/Finsky  ( 5652): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/Prism.ItemManager( 1547): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1547): loadItems() com.htc.launcher.pageview.WidgetManager@2f0cda9c +
I/Prism.WidgetManager( 1547): onLoadItems() +
E/AndroidHttpClient( 5652): Leak found
E/AndroidHttpClient( 5652): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5652): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5652): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5652): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5652): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5652): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5652): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5652): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5652): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5652): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5652): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5652): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5652): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5652): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5652): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5652): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/jxcore_app_log( 5708): JniHelper::setJavaVM(0xab2708f8), pthread_self() = -1403513712
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5708): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5708):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5708):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5708):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5708):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5708): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277fbaa9 added. We now have 1 listener(s)
D/BluetoothManagerService(  954): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708): setBluetoothMacAddress: 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5708): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5708): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11705865 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5708): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  954): New client listening to asynchronous messages
,E/WifiTrafficPoller(  954): ADD_CLIENT: 6
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5708): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5708): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5708): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5708): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5708): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/ConfigFetchService( 4269): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  954): acquireWL(297f0665): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4269 10024 WorkSource{10366 com.test.thalitest}
,I/ConfigFetchService( 4269): launchTask
D/PMS     (  954): releaseWL(3cad5ad7): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  954): acquireWL(3626af3a): PARTIAL_WAKE_LOCK  Icing 0x1 4269 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4269): Loading module com.google.android.gms.games from APK com.google.android.play.games,
D/ChimeraModuleLdr( 4269): Module APK com.google.android.play.games already loaded
,D/PMS     (  954): releaseHCC(2fcd5047): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
I/chromium( 5708): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/PMS     (  954): releaseHCC(6cb0074): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
D/PMS     (  954): releaseWL(3626af3a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4269): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/Vision  ( 4269): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,I/PeopleContactsSync( 4269): CP2 sync disabled
,D/Vision  ( 4269): Failed to find package metadata for com.test.thalitest
,D/Vision  ( 4269): No vision deps
,I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4269, uid=10024, userID:0
,I/ActivityManager(  954): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5892 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4269, uid=10024, userID:0
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4269, uid=10024, userID:0
,V/ConfigFetchTask( 4269): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WKcWMWvCU23ME-060oMI-0Nt2IjOb3iC_tLRYeRUCexn4OtPmmJcXEgqD3ZCQtJ-bFpFS_Ud9Gl0JMrv656wJP4FJRw9Yser-Q7_IOhdj7HzT8Olja7A3gGIHINz5t70wYo6olADobN6Ier3TB-mXNIhOx9wtE1MCFa8SbOLKn9wnkIVvfXavfqa9XQEjp-EPn0pB_
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4269, uid=10024, userID:0
I/CheckinService( 4269): Done disabling old GoogleServicesFramework version
,I/GoogleURLConnFactory( 4269): Using platform SSLCertificateSocketFactory
,D/libc    ( 4269): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4269): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4269): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4269): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4269): [NET] android_getaddrinfo_proxy+
D/libc    ( 4269): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 4269): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4269): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 4269): fetch service done; releasing wakelock
,D/PMS     (  954): releaseWL(297f0665): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10366 com.test.thalitest}
I/ConfigFetchService( 4269): stopping self
,W/BaseAppContext( 4269): Using Auth Proxy for data requests.
,W/BaseAppContext( 4269): Using Auth Proxy for data requests.
,E/Prism.WidgetManager( 1547): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1547): onLoadItems() -
I/Prism.ItemManager( 1547): loadItems() com.htc.launcher.pageview.WidgetManager@2f0cda9c -
,W/BaseAppContext( 4269): Using Auth Proxy for data requests.
,I/GAV2    ( 5464): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 1942): Explicit concurrent mark sweep GC freed 14238(769KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 669us total 38.016ms
,W/BaseAppContext( 4269): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4269): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4269): Using Auth Proxy for data requests.,
,V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Process (  954): killProcessQuiet, pid=5356,
I/ActivityManager(  954): Killing 5356:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/GLSUser ( 1942): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1942): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1942): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1942): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  954): Recipient 5356
,V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5652): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5652): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5652): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5652): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/Process (  954): killProcessQuiet, pid=3706
I/ActivityManager(  954): Killing 3706:com.htc.sense.mms/u0a64 (adj 15): empty #17,
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/DeviceConnectionService( 1858): client connected with version: 7571000
,I/GAv4    ( 5892): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5892):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5892):   adb logcat -s GAv4
,I/ActivityManager(  954): Recipient 3706
,I/ActivityManager(  954): Killing 5409:com.google.android.setupwizard/u0a77 (adj 15): empty #18
D/Process (  954): killProcessQuiet, pid=5409
,D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5409,
,W/GAv4    ( 5892): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 5892): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5892): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5892): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45,
,W/jxcore-log( 5708): Initializing JXcore engine
,W/jxcore-log( 5708): JXcore engine is ready
,W/jxcore-log( 5708): Starting JXcore engine
,D/AutoSetting( 1466): service - handleMessage() stop self
,D/VoldConnector(  954): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 5892): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,D/PMS     (  954): acquireWL(3c0b5faf): PARTIAL_WAKE_LOCK  AsyncService 0x1 5758 10167 null
,D/PMS     (  954): acquireWL(36d39b45): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5758 10167 null
,D/PMS     (  954): releaseWL(3c0b5faf): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/AutoSetting( 1466): service - handleMessage() quit looper,
D/AutoSetting( 1466): service - onDestroy() END
,D/PMS     (  954): releaseWL(36d39b45): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,W/ResourcesManager( 5892): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5892): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/jxcore-log( 5708): Platform android,
W/jxcore-log( 5708): 
W/jxcore-log( 5708): Process ARCH arm
W/jxcore-log( 5708): 
,V/JNIHelp ( 5892): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/UpdateIcingCorporaServi( 5567): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/ChimeraCfgMgr( 4269): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PMS     (  954): acquireWL(836edfd): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5201 10159 null
D/ChimeraModuleLdr( 4269): Module APK com.google.android.play.games already loaded
,W/asset   ( 5567): Copying FileAsset 0x55758baff0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.,
W/System  ( 5892): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5201, uid=10159, userID:0
I/ProviderInstaller( 5892): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  954): releaseWL(836edfd): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 5201): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5201): Stop autocaching.
,D/WearableService( 4757): callingUid 10024, callindPid: 4757
,I/ActivityManager(  954): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5952 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a,
,I/art     (  954): Explicit concurrent mark sweep GC freed 17555(870KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.432ms total 143.942ms
,I/art     (  954): WaitForGcToComplete blocked for 39.120ms for cause HeapTrim
,D/PMS     (  954): acquireWL(24a28669): PARTIAL_WAKE_LOCK  Icing 0x1 4269 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): releaseWL(24a28669): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  954): acquireWL(2d1d87ab): PARTIAL_WAKE_LOCK  Icing 0x1 4269 10024 WorkSource{10024 com.google.android.gms},
D/SyncApplication( 5952): Loading default preferences
E/GmsUtils( 5201): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 5201): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Resources( 5952): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/PMS     (  954): releaseWL(2d1d87ab): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 5708): JXcore Cordova bridge is ready!
I/jxcore-log( 5708): 
,W/jxcore-log( 5708): JXcore engine is started
,D/WifiService(  954): New client listening to asynchronous messages
,E/WifiTrafficPoller(  954): ADD_CLIENT: 7
,I/org.thaliproject.p2p.ThaliPermissions( 5708): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/PMS     (  954): acquireWL(12a47a52): PARTIAL_WAKE_LOCK  Icing 0x1 4269 10024 WorkSource{10024 com.google.android.gms}
,I/UpdateIcingCorporaServi( 5567): UpdateCorporaTask done [took 325 ms] updated apps [took 325 ms] 
,D/Process (  954): killProcessQuiet, pid=5518
,I/ActivityManager(  954): Killing 5518:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/SyncApplication( 5952): Overriding preferences with custom values
E/jxcore  ( 5708): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5708): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5708): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,D/SyncApplication( 5952): Updating preferences succeeded,
,I/HtcModeClient( 3188): handler message = 4011,
E/HtcModeClient( 3188): Check connection and retry 7 times.
,I/ActivityManager(  954): Recipient 5518,
,D/PMS     (  954): acquireWL(3ab94123): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 954 1000 null
W/PluginManager( 5708): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 249ms. Plugin should use CordovaInterface.getThreadPool().
E/SyncApplication( 5952): Application created.
,W/HtcSystemUPManager(  954): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/VolumeInfo( 5952): Unable to read mount points
W/VolumeInfo( 5952): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5952): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5952): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5952): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5952): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5952): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5952): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5952): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5952): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5952): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5952): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5952): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5952): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5952): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5952): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5952): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5952): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5952): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5952): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5952): 	... 13 more
V/VolumeInfo( 5952): Found 0 mount point(s)
V/VolumeInfo( 5952): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,I/CalendarDefines( 5952): getNewCalendarAuthority()...
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5952, uid=10005, userID:0
,W/PackageManager(  954): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
D/VolumeInfo( 5952): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/SyncApplication( 5952): enableAppOperation()+
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5952, uid=10005, userID:0,
W/PackageManager(  954): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 5952): enableAppOperation()-
,D/HTCUtilities( 5952): isNeorSinged() + ,
,D/VolumeInfo( 5952): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/VolumeInfo( 5952): Can not create volume ID for unmounted volume null
,D/HTCUtilities( 5952): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 5952): isNeorSinged() return false
I/FeedHostManager( 1547): [onResume]
I/FeedProviderManager( 1547): onResume
,I/SocialFeedProvider( 1547): +onResume
I/SocialFeedProvider( 1547): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1547): -onResume
I/ConnectivityHelper( 1547): [getCurrentConnectionType] no network connection
,D/StatusBarManagerService(  954): setSystemUiVisibility(0x8700),
D/StatusBarManagerService(  954): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  954): hiding MENU key
,D/CDMountReceiver( 5952): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 5952): showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,D/FindExtension( 1547): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1547): Defer allocateBuffers to drawing time
,I/ActionCombine( 5952): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,I/InputMethodManagerService(  954): Disable input method client, pid=5708
D/StatusBarManagerService(  954): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  954): Enable input method client, pid=1547
D/CDMountReceiver( 5952): enable CD Auto-mount: true
,I/PhoneStatusBar( 1246): setImeWindowStatus(false,false)
D/PMS     (  954): releaseWL(78412e5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10005}
W/IInputConnectionWrapper( 5708): reportFullscreenMode on inactive InputConnection
D/HTCUtilities( 5952): enable auto-mount
,D/GCM     ( 1942): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/DotMatrix( 1335): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 5952): enable auto-mount
,I/HtcMountManagerAdapter( 5952): mHtcMountManager is  null
I/HtcMountManagerAdapter( 5952): mStorageManager is  not null
I/HtcMountManagerAdapter( 5952): mHtcMountManager is  null
I/HtcMountManagerAdapter( 5952): mStorageManager is  not null
D/AuthorizationBluetoothService( 1942): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/VoldConnector(  954): SND -> {22 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
D/VoldConnector(  954): SND -> {21 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
V/GmsCoreStatsServiceLauncher( 4269): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/MountService(  954): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  954): mountISO: /system/etc/PCTOOL.ISO
,D/Process (  954): killProcessQuiet, pid=4988
,I/ActivityManager(  954): Killing 4988:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/RemoteViews( 1246): apply : com.nero.android.htc.sync 0 16 6 38
,I/RemoteViews( 1246): apply : com.nero.android.htc.sync 0 14 3 53,
,D/StatusBarManagerService(  954): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  954): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  954): hiding MENU key
,I/ActivityManager(  954): Recipient 4988
,D/PMS     (  954): releaseWL(3ab94123): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4269, uid=10024, userID:0
,E/MDM     ( 1858): [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/LocationInitializer( 4269): Restart initialization of location
,D/Finsky  ( 5652): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive
,W/BindingManager( 5708): Cannot call determinedVisibility() - never saw a connection for the pid: 5708,
,W/OpenGLRenderer( 1547): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,I/Icing   ( 4269): Indexing FBE7E5D8BA1B80556F1315772AF6A2582D6BF376 from com.google.android.googlequicksearchbox,
,I/Icing   ( 4269): Indexing done FBE7E5D8BA1B80556F1315772AF6A2582D6BF376,
,D/PMS     (  954): releaseWL(12a47a52): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/ConfigService( 1942): onDestroy
,I/ActivityManager(  954): Waited long enough for: ServiceRecord{10d3865 u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
,I/HtcModeClient( 3188): handler message = 4011
E/HtcModeClient( 3188): Check connection and retry 8 times.
,I/ActivityManager(  954): Waited long enough for: ServiceRecord{3bf149c7 u0 com.htc.musicenhancer/.EnhancerService},
,D/Process (  954): killProcessQuiet, pid=5279,
I/ActivityManager(  954): Killing 5279:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5279,
,I/ActivityManager(  954): Killing 5328:com.htc.sdm/u0a79 (adj 15): empty #17
,D/Process (  954): killProcessQuiet, pid=5328
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5328
,W/MediaManager( 5150): [DualLensScanUtil],	mmpCursor count is 0
,D/Process (  954): killProcessQuiet, pid=4735
,I/ActivityManager(  954): Killing 4735:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 4735
,D/Process (  954): killProcessQuiet, pid=5433
I/ActivityManager(  954): Killing 5433:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5433
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  954): acquireWL(1add295a): PARTIAL_WAKE_LOCK  *alarm* 0x1 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{2860378b: PendingIntentRecord{2663068 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=84850, Int=0,
D/PMS     (  954): releaseWL(1add295a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  954): acquireWL(b27c81): PARTIAL_WAKE_LOCK  *alarm* 0x1 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{3ab48126: PendingIntentRecord{798c167 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=85215, Int=0
D/PMS     (  954): releaseWL(b27c81): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  954): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
,D/libc    (  954): [NET] android_getaddrinfofornet-, err=8
D/libc    (  954): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  954): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  954): [NET] android_getaddrinfo_proxy+
D/libc    (  954): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  954): [NET] android_getaddrinfo_proxy-, NODATA
,I/HtcModeClient( 3188): handler message = 4011,
E/HtcModeClient( 3188): Check connection and retry 9 times.
,D/PMS     (  954): acquireWL(7095fbd): PARTIAL_WAKE_LOCK  *alarm* 0x1 954 1000 WorkSource{10072},
V/AlarmManager(  954): sending alarm PendingIntent{235789b2: PendingIntentRecord{29e60d03 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457344304031, Int=0
D/PMS     (  954): releaseWL(7095fbd): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/ContactMessageStore( 1499): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1499): MSG_NOTIFY_CS_TO_SYNC <<
,D/Finsky  ( 5652): [577] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5652): [1] 5.onFinished: Installation state replication succeeded.,
,I/HtcModeClient( 3188): handler message = 4011
,E/HtcModeClient( 3188): Check connection and retry 10 times.
,I/HtcModeClient( 3188): handler message = 4011,
E/HtcModeClient( 3188): Check connection and retry 11 times.
,W/ContextImpl(  954): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/PMS     (  954): acquireWL(2d0788ac): PARTIAL_WAKE_LOCK  Icing 0x1 4269 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  954): releaseWL(2d0788ac): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  954): acquireWL(29029d0a): PARTIAL_WAKE_LOCK  Icing 0x1 4269 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): releaseWL(29029d0a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  954): acquireWL(3ba04144): PARTIAL_WAKE_LOCK  Icing 0x1 4269 10024 WorkSource{10024 com.google.android.gms},
,I/HtcModeClient( 3188): handler message = 4011,
,E/HtcModeClient( 3188): Check connection and retry 12 times.
,D/PMS     (  954): releaseWL(3ba04144): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  954): acquireWL(4e1c362): PARTIAL_WAKE_LOCK  Icing 0x1 4269 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  954): releaseWL(4e1c362): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): acquireWL(c022db0): PARTIAL_WAKE_LOCK  Icing 0x1 4269 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): releaseWL(c022db0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  954): acquireWL(cf94429): PARTIAL_WAKE_LOCK  *alarm* 0x1 954 1000 WorkSource{10024}
V/AlarmManager(  954): sending alarm PendingIntent{199cb3ae: PendingIntentRecord{3e4cae9c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=103664, Int=0
D/PMS     (  954): acquireWL(d0bb54f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1942 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  954): releaseWL(cf94429): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
D/libc    ( 1942): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1942): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1942): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1942): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1942): [NET] android_getaddrinfo_proxy+
D/libc    ( 1942): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND),
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7,
,D/PMS     (  954): releaseWL(d0bb54f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1942): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  954): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6004 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6004): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6004): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6004): MmsConfig.loadMmsSettings
,I/ActivityManager(  954): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6034 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6004, uid=10112, userID:0
,W/HtcWrapAdjustableCursorFactory( 6034): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 6034): onCreate
,W/Settings( 6004): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/GetPrviateResource( 6034): GetPrviateResource
,V/GetPrviateResource( 6034): GetPrviateResource
,D/MmsCustomizationProvider( 6034): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/Babel_Crash( 6004): startup - clean
,D/MessageCustFlag( 6034): sense_version=6.0,
,D/BTAccessoryUtil( 6034): createReceiver
,D/BTAccessoryUtil( 6034): registerReceiver return intent = null
,D/MessageCustFlag( 6034): sku_id=118
,D/HtcBuildUtils( 6034): getRATByHtcTelephonyCapability:1
,W/SystemReader( 6034): Cannot find qct_8960_interface, use default value instead
,D/MmsCustomizationProvider( 6034): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 6004): deleted: false for 0
,I/Babel_SMS( 6004): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 6004): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6004): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6004): MmsConfig.loadFromResources
,E/Babel_SMS( 6004): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6004): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6004, uid=10112, userID:0,
,I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6004, uid=10112, userID:0
,I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6004, uid=10112, userID:0,
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6004, uid=10112, userID:0,
,I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6004, uid=10112, userID:0
,W/VideoCapabilities( 6004): Unrecognized profile 2130706433 for video/avc,
,D/PMS     (  954): acquireWL(1e8ccd0c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{204cf474: PendingIntentRecord{38f79d9d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=104072, Int=0
,D/PMS     (  954): releaseWL(1e8ccd0c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1246): Weather sync is On,
,W/WeatherTimeKeeper( 1246): [refreshWeatherData] no weather data
,I/ClockController( 1246): schedule update now=1457344320033 next=59967
,I/Clock   ( 1246): updateClock:10:52 Europe/Warsaw
I/Clock   ( 1246): updateClock:10:52 Europe/Warsaw
I/Clock   ( 1246): updateClock:10:52 Europe/Warsaw
,W/VideoCapabilities( 6004): Unsupported mime video/x-ms-wmv
,W/Utils   ( 6004): could not parse size range '64x64-1920X1080',
,W/AudioCapabilities( 6004): Unsupported mime audio/qcelp,
,W/AudioCapabilities( 6004): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6004): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6004): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 6004): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6004): Unrecognized profile 2130706433 for video/avc,
W/VideoCapabilities( 6004): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6004): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6004): Unrecognized profile 2130706433 for video/avc
,D/Process (  954): killProcessQuiet, pid=5831
I/ActivityManager(  954): Killing 5831:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5831
,D/Process (  954): killProcessQuiet, pid=5620
I/ActivityManager(  954): Killing 5620:com.google.android.partnersetup/u0a27 (adj 15): empty #18
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5620,
,I/vclib   ( 6004): onServiceConnected,
,W/Babel   ( 6004): Attempted to change video mute state without an active call.,
,I/HtcModeClient( 3188): handler message = 4011,
,E/HtcModeClient( 3188): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3188): Don't start project servcice,
,D/HtcModeClient( 3188): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3188): connectState: CONNECTION_READY = false,
D/SilentMusic( 3188): call stop
,D/HtcModeClient( 3188): close connection
,W/HtcModeClient( 3188): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3188): read the terminate packet, so break
,D/Process (  954): killProcessQuiet, pid=3188,
I/ActivityManager(  954): Killing 3188:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 3188
,D/Messaging( 6034): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6034): networkCode: 
D/MessageCustFlag( 6034): sku_id=118
D/MmsConfig( 6034): SIE smsPri: null
D/MmsConfig( 6034): networkCode: 
,D/MmsConfig( 6034): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 6034): startAsyncQueryReports ---,
D/MmsAsyncWorkHandler( 6034): 
D/MmsAsyncWorkHandler( 6034): HM tk = 20001
D/ReportIndicatorCache( 6034): MSG_QUERY_REPORTS >>
,D/SettingsManager( 6034): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@3fc01391
D/Messaging( 6034): mNeedToUpdateDate2 start
,D/DraftCache( 6034): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6034): [DraftCache/1] refresh
,D/TelephUtils( 1499): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
D/MmsSmsV2Provider( 1499):  slotId = -1000
D/MmsSmsV2Provider( 1499): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,I/Messaging( 6034): mccmnc> 
,D/TelephUtils( 1499): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
,D/AccFlag ( 1499): sku_id=118
,D/MmsConfig( 6034): networkCode: 
D/TelephUtils( 1499): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1499):  slotId = -1000
D/MmsSmsV2Provider( 1499): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 6034): [DraftCache/141] rebuildCache
,D/TelephUtils( 1499): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1499):  slotId = -1000
D/MmsSmsV2Provider( 1499): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/TelephUtils( 1499): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/MmsSmsV2Provider( 1499):  slotId = -1000
D/MmsSmsV2Provider( 1499): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 6034): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/Messaging( 6034): ViewCache CreatePreloadOnlyConversationList
,D/MessageCustFlag( 6034): sense_version=6.0
,D/Jerry   ( 6034): start to preload cursor >>>>>>>
,D/PhoneStorageUtil( 6034): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 6034): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6034): createReceiver
,D/TelephUtils( 1499): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
,V/MmsProvider( 1499): Update uri=content://mms, match=0
V/MmsProvider( 1499): selection=st=129 AND m_type!=134
,D/Messaging( 6034): Reset downloading state: 0,
V/MmsSystemEventReceiver( 6034): TransactionService is going to be woken up.
,V/TransactionService( 6034): 1-Creating TransactionService,
,V/TransactionService( 6034): onStartCommand: 1,
D/MmsSystemEventReceiver( 6034): unRegisterForConnectionStateChanges
V/TransactionService( 6034): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6034): Loading previous transactions.
,I/art     (  954): Explicit concurrent mark sweep GC freed 21402(1048KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 18MB/27MB, paused 1.494ms total 165.542ms,
D/TelephUtils( 1499): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/AccFlag ( 1499): device_type: 1
,D/TransactionService( 6034): Force clearing mTransactionList
,D/TransactionService( 6034): Force set service start id to 1
,V/TransactionService( 6034): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6034): unRegisterForConnectionStateChanges
D/TransactionService( 6034): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 6034): Destroying TransactionService
D/Messaging( 6034): mNeedToUpdateDate2: false
,V/TransactionService( 6034): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1499): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/Jerry   ( 1499): URI_DRAFT
,D/DraftCache( 6034): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 6034): [DraftCache/141] rebuildCache time: 9
D/MmsAsyncWorkHandler( 6034): 
D/MmsAsyncWorkHandler( 6034): HM tk = 20002
,D/TelephUtils( 1499): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1499):  slotId = -1000
,D/TelephUtils( 1499): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/AccFlag ( 1499): sku_id=118
,D/Messaging( 6034): ViewCache CreatePreload
,D/Messaging( 6034): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1499): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
,D/AccFlag ( 1499): sku_id=118
,D/Cust_MMSMS( 6034): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 6034): def_index: 0
,D/MsgPreferenceUtils( 6034): globalIndex = 1
,D/MsgPreferenceUtils( 6034): phone state: true
,D/MsgPreferenceUtils( 6034): sd state: false
D/MsgPreferenceUtils( 6034): vIndex = 0
,I/ActivityManager(  954): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6086 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/PMS     (  954): acquireWL(393cc879): PARTIAL_WAKE_LOCK  *alarm* 0x1 954 1000 WorkSource{10076}
V/AlarmManager(  954): sending alarm PendingIntent{2a8c69be: PendingIntentRecord{2cf51a1f com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457344323138, Int=60000
D/PMS     (  954): releaseWL(393cc879): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6086): SMSBackupAgentService started,
D/SMSBackup( 6086): Checking restore status
,D/SMSBackup( 6086): Restore complete,
D/SMSBackup( 6086): cancelCheckAlarm
,D/SMSBackup( 6086): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  954): killProcessQuiet, pid=5857
,I/ActivityManager(  954): Killing 5857:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5857
,I/PMS     (  954): Going to sleep due to screen timeout (uid 1000)...
D/ActivityManager(  954): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{3bb87335 #11 A=.Prism U=0 sz=1}
W/PMS     (  954): mWirelessDisplayManager is null
,W/PMS     (  954): mWirelessDisplayManager is still null
,I/SensorManager(  954): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@58df07c,
W/SensorService(  954): Following SensorService logs are not warning, just make sure they are printed
I/PMS     (  954): Sleeping (uid 1000)...
W/SensorService(  954): disable: get sensor name = Accelerometer Sensor
D/XAN-DPS (  954): prepareColorFade 1
W/SensorService(  954): pid=954, uid=1000
W/PMN     (  954): goingToSleep
W/SensorService(  954): Active sensors: size = 4
D/PMS     (  954): acquireWL(30a163ca): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 954 1000 null
W/SensorService(  954): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  954): CM32181 Light sensor (handle=0x00000003, connections=1),
W/SensorService(  954): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  954): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  954): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@58df07c, eanble = 0, strlen(mName) = 90
W/SensorService(  954): Active Listeners: mActiveListeners.size() = 2,
W/SensorService(  954): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1cf7b652
W/SensorService(  954): Listener[1] = com.htc.smartdim.sensor_eye@1d79569f
W/SensorService(  954): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/PMN     (  954): goingToSleep done
,I/FeedHostManager( 1547): [onPause]
I/FeedProviderManager( 1547): onPause,
I/FeedHostManager( 1547): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@350386aa
I/Adreno-EGL(  954): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  954): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  954): Build Date: 03/09/15 Mon
I/Adreno-EGL(  954): Local Branch: 
I/Adreno-EGL(  954): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  954): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  954):                  d74aa161a12b9c6fc6332151
I/SocialFeedProvider( 1547): +onPause
I/SocialFeedProvider( 1547): -onPause
,W/HtcLockScreen( 1246): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/ActivityManager(  954): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6110 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
W/HtcSystemUPManager(  954): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/AlarmManager(  954): ACTION_SCREEN_ON
I/AlarmManager(  954): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  954): [AlarmQueuing] done recovering,
I/AlarmManager(  954): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  954): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  954): releaseWL(30a163ca): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/WifiStateMachine(  954): handleMessage: E msg.what=131167
E/WifiStateMachine(  954): processMsg: InitialState
E/WifiStateMachine(  954):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  954): processMsg: DefaultState
E/WifiStateMachine(  954):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  954):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState,
V/SRS_Proc(  401): ParamSet string: screen_state=on,
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  954): handleMessage: E msg.what=155650,
,D/WifiController(  954): processMsg: ApStaDisabledState
D/NetworkPolicy(  954): updateScreenOn: false
D/WifiController(  954): processMsg: DefaultState
V/NetworkPolicy(  954): updateIfacesLocked()
D/WifiController(  954): handleMessage: X
,D/NetworkManagementService(  954): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiStateMachine(  954): getWifiLinkLayerStats: WIFI is not enbled
D/WifiStateMachine(  954): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  954): handleScreenStateChanged Exit: true
E/WifiStateMachine(  954): handleMessage: X
E/WifiStateMachine(  954): handleMessage: E msg.what=131154
E/WifiStateMachine(  954): processMsg: InitialState
E/WifiStateMachine(  954):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  954): processMsg: DefaultState
,E/WifiStateMachine(  954):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  954): handleMessage: X
E/WifiStateMachine(  954): handleMessage: E msg.what=131127
E/WifiStateMachine(  954): processMsg: InitialState
,E/WifiStateMachine(  954):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  954): processMsg: DefaultState
,E/WifiStateMachine(  954):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  954): handleMessage: X
E/WifiStateMachine(  954): handleMessage: E msg.what=131129
E/WifiStateMachine(  954): processMsg: InitialState
E/WifiStateMachine(  954):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  954): processMsg: DefaultState
E/WifiStateMachine(  954):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  954): handleMessage: X
,W/ResourcesManager( 6110): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/GpsLocationProvider(  954): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
,I/IntentController( 1246): receive(android.intent.action.SCREEN_ON,1,false),
,D/XAN-DPS (  954): prepareColorFade done,
D/XAN-DPS (  954): setBrightness to 0
,I/CalendarProvider2( 6110): Created com.android.providers.calendar.CalendarAlarmManager@3e91941b(com.htc.providers.calendar.HtcCalendarProvider@26fe79b8)
,D/PMS     (  954): acquireWL(29f50a70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1858 10024 WorkSource{10024 com.google.android.gms}
I/SensorManager(  954): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@1cf7b652
I/DisplayManagerService(  954): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  954): Following SensorService logs are not warning, just make sure they are printed
V/ActivityManager(  954): Display changed displayId=0
W/SensorService(  954): disable: get sensor name = CM32181 Light sensor
,D/PMS     (  954): acquireWL(923c1e9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1858 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1335): [EventService]  onDisplayChanged: 0
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
W/SensorService(  954): pid=954, uid=1000
W/SensorService(  954): Active sensors: size = 3
W/SensorService(  954): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  954): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  954): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  954): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@1cf7b652, eanble = 0, strlen(mName) = 67
W/SensorService(  954): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  954): Listener[0] = com.htc.smartdim.sensor_eye@1d79569f
W/SensorService(  954): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1335): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/PMS     (  954): releaseWL(29f50a70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/CalendarProvider2( 6110): wait start:true
,D/PMS     (  954): releaseWL(923c1e9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/AlarmManager(  954): ACTION_SCREEN_OFF,
I/AlarmManager(  954): [AlarmQueuing] screen off now: 
I/AlarmManager(  954): [AlarmQueuing] data connection: true
I/AlarmManager(  954): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  954): stopDataStallAlarm ,
E/WifiDataStallTracker(  954): ENABLE_DATA_MONITOR_POLL false Token 0
,E/WifiStateMachine(  954): handleMessage: E msg.what=131167
E/WifiStateMachine(  954): processMsg: InitialState
E/WifiStateMachine(  954):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  954): processMsg: DefaultState
E/WifiStateMachine(  954):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  954):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiStateMachine(  954): getWifiLinkLayerStats: WIFI is not enbled
,E/WifiStateMachine(  954): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiDisplayAdapter(  954): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  954):     Client/Owner: Client
D/WifiDisplayAdapter(  954):     GroupId: 
D/WifiDisplayAdapter(  954):     Passphrase: 
D/WifiDisplayAdapter(  954):     SessionId: 0
D/WifiDisplayAdapter(  954):     IP Address: }
V/SRS_Proc(  401): ParamSet string: screen_state=off
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiStateMachine(  954): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  954): handleScreenStateChanged Exit: false
E/WifiStateMachine(  954): handleMessage: X
,E/WifiStateMachine(  954): handleMessage: E msg.what=131154
E/WifiStateMachine(  954): processMsg: InitialState
E/WifiStateMachine(  954):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  954): processMsg: DefaultState
E/WifiStateMachine(  954):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  954): handleMessage: X
,D/WifiController(  954): handleMessage: E msg.what=155651
,D/WifiController(  954): processMsg: ApStaDisabledState
D/NetworkPolicy(  954): updateScreenOn: false
D/WifiController(  954): processMsg: DefaultState
,V/NetworkPolicy(  954): updateIfacesLocked()
D/WifiController(  954): handleMessage: X
D/NetworkManagementService(  954): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/SensorManager( 1246): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@153b43fe, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  954): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  954): enable: get sensor name = hTC Gesture Motion HIDI
,D/CalendarProvider2( 6110): wait end:false
,W/SensorService(  954): pid=1246, uid=10041
,W/SensorService(  954): Active sensors: size = 4
W/SensorService(  954): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  954): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  954): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  954): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  954): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@153b43fe, eanble = 1, strlen(mName) = 57
W/SensorService(  954): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  954): Listener[0] = com.htc.smartdim.sensor_eye@1d79569f
W/SensorService(  954): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@153b43fe
W/SensorService(  954): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  954): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1335): [EventService] getTotalRam: 1842 Mb
,I/ActivityManager(  954): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6140 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/ContactMessageStore( 1499): start background delete task...
,I/IntentController( 1246): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1499): size: 0 , 0
,D/ContactMessageStore( 1499): Background delete complete
,D/PMS     (  954): acquireWL(3c7bb788): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1858 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  954): releaseWL(3c7bb788): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): acquireWL(2dc8c521): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1858 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): releaseWL(2dc8c521): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/RemoteViews( 1246): setHTCTheme(com.htc.updater,true,33751145),
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2,
D/PMS     (  954): Setting HAL interactive mode to false
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  954): Setting HAL interactive mode to false done
D/SurfaceControl(  954): Excessive delay in setPowerMode(): 283ms
,D/PMS     (  954): Setting HAL auto-suspend mode to true
W/HtcSystemUPManager(  954): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  954): Setting HAL auto-suspend mode done,
I/InputMethodManagerService(  954): screenObserver, isScreenOn=false
D/StatusBarManagerService(  954): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  954): Disable input method client, pid=1547
D/HABCtrl (  954): TPE algorithm. remove timeout.
D/PMS     (  954): OOBE c monitor 11
I/InputManager(  954): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
I/IntentController( 1246): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,I/RemoteViews( 1246): apply : com.htc.updater 1 33 3 36
,D/PMS     (  954): acquireWL(3122d46): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
D/NfcService( 1515): ScreenObserver: OFF
I/BatteryService(  954): n_update end
D/NfcService( 1515): applyRouting - 0
D/PMS     (  954): releaseWL(3122d46): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  954): updateBatteryInfo
D/PMS     (  954): acquireWL(22accb07): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1515 1027 null
D/NfcService( 1515): applyRouting -2
D/NfcService( 1515): applyRouting
D/NfcService( 1515): Ignore this applyRouting...
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  954): Checking...
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  954): >> updateStatus,
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
W/ContextImpl( 6140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  954): releaseWL(22accb07): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): battery changed pluggedType: 2
,D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
,I/PhoneStatusBar( 1246): setImeWindowStatus(false,false)
,D/PowerUI ( 1246): closing low battery warning: level=100
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl( 6140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6140): MY_DEBUG = false,
,I/ClockController( 1246): stop clock update:screen off,
I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true
,D/SmartSyncUtils( 6140): isEpsOn(), nState = 0
,D/PMS     (  954): acquireWL(32b3d7d2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6140 1000 null
,D/SmartDim(  954): Init customizeScreenOffDelayClass error
W/ContextImpl(  954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  954): releaseWL(32b3d7d2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 6140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncUtils( 6140): isEpsOn(), nState = 0
D/SmartSyncUtils( 6140): isEpsOn(), nState = 0
,W/ContextImpl( 6140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  954): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
I/SensorManager(  954): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@1d79569f
W/SensorService(  954): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  954): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  954): pid=954, uid=1000,
W/SensorService(  954): Active sensors: size = 3
W/SensorService(  954): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  954): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  954): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  954): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1d79569f, eanble = 0, strlen(mName) = 36
W/SensorService(  954): Active Listeners: mActiveListeners.size() = 1,
W/SensorService(  954): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@153b43fe
,W/SensorService(  954): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  954): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  954): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  954): pid=954, uid=1000
W/SensorService(  954): Active sensors: size = 2
,E/ActivityThread(  954): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@230883ec that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  954): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@230883ec that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  954): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  954): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  954): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  954): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  954): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  954): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  954): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  954): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  954): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  954): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  954): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  954): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  954): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  954): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  954): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  954): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/SensorService(  954): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  954): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  954): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1d79569f, eanble = 0, strlen(mName) = 36
W/SensorService(  954): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  954): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@153b43fe
W/SensorService(  954): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  954): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@1d79569f
,I/ActivityManager(  954): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6173 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
I/PowerUsageList:PowerUsageHelper( 6140): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6140): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 6140): calcPower(), no data
,D/PowerUsageList:PowerUsageHelper( 6140): MY_DEBUG = false
,D/SmartSyncUtils( 6140): getMobilePolicyEnabled, result = true,
,D/Process (  954): killProcessQuiet, pid=5600
I/ActivityManager(  954): Killing 5600:com.android.settings/1000 (adj 15): empty #17,
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/WifiService(  954): New client listening to asynchronous messages
,E/WifiTrafficPoller(  954): ADD_CLIENT: 8
,I/ActivityManager(  954): Recipient 5600
,D/Process (  954): killProcessQuiet, pid=5892
,I/ActivityManager(  954): Killing 5892:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5892
,I/CalendarProvider2( 6110): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 6110): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  954): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6198 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  954): killProcessQuiet, pid=5758
I/ActivityManager(  954): Killing 5758:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  954): releaseWL(1c07c7c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  954): Recipient 5758
,W/ResourcesManager( 6198): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6198): onCreate
,D/ProviderChangeReceiver( 6198): ---------------------------------------------------
,D/ProviderChangeReceiver( 6198): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  954): killProcessQuiet, pid=5464
I/ActivityManager(  954): Killing 5464:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6198): start to updateAlertNotification!
,I/ActivityManager(  954): Recipient 5464
,D/HtcAlertService( 6198): No fired or scheduled alerts
,D/HtcAlertUtils( 6198): -- cancelReminderNotification --
,D/HtcAlertUtils( 6198): broadcastExistReminder!
,D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcUPManager( 1246): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  954): killProcessQuiet, pid=5304
I/ActivityManager(  954): Killing 5304:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5304
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/ContactMessageStore( 1499): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1499): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  954): acquireWL(3433f759): PARTIAL_WAKE_LOCK  *alarm* 0x1 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{37539f1e: PendingIntentRecord{384a13ff android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457344346248, Int=0
D/PMS     (  954): acquireWL(3fdc65cc): PARTIAL_WAKE_LOCK  *backup* 0x1 954 1000 null
,V/AlarmManager(  954): sending alarm PendingIntent{1fa3b015: PendingIntentRecord{1d968f2a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142467, Int=0
V/AlarmManager(  954): sending alarm PendingIntent{3ab48126: PendingIntentRecord{798c167 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145222, Int=0
W/BackupManagerService(  954): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
D/libc    (  954): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
,D/libc    (  954): [NET] android_getaddrinfofornet-, err=8,
D/PMS     (  954): releaseWL(3433f759): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  954): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
E/BackupManagerService(  954): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/libc    (  954): [NET] android_getaddrinfofornet-, pass to proxy
D/PMS     (  954): releaseWL(3fdc65cc): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/libc    (  954): [NET] android_getaddrinfo_proxy+
D/libc    (  954): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  954): [NET] android_getaddrinfo_proxy-, NODATA
,D/GpsLocationProvider(  954): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  954): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,W/ContextImpl(  954): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  954): acquireWL(1d35f11b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/BatteryService(  954): n_update end
,D/PMS     (  954): releaseWL(1d35f11b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  954): updateBatteryInfo
D/PMS     (  954): runPSCheck
D/HtcPowerSaver(  954): Checking...
I/HtcPowerSaver(  954): >> updateStatus
,I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1246): closing low battery warning: level=100
,D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  954): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  954): << updateStatus
D/UsbnetService(  954): onReceive BATTERY_CHANGED
,D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  954): battery changed pluggedType: 2
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1499): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  954): acquireWL(355012b8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{204cf474: PendingIntentRecord{38f79d9d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=164072, Int=0
,D/libc    (  954): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4,
V/AlarmManager(  954): sending alarm PendingIntent{b1c3891: PendingIntentRecord{256673f6 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=192783, Int=0
D/libc    (  954): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  954): sending alarm PendingIntent{3ab48126: PendingIntentRecord{798c167 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=205248, Int=0
D/libc    (  954): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
V/AlarmManager(  954): sending alarm PendingIntent{a3883f7: PendingIntentRecord{3e4cae9c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=180683, Int=0
V/AlarmManager(  954): sending alarm PendingIntent{1a4fa264: PendingIntentRecord{34bacccd com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=187381, Int=0
D/libc    (  954): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  954): [NET] android_getaddrinfo_proxy+
D/libc    (  954): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  954): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  954): acquireWL(117dd982): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1942 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1942): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1942): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1942): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1942): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1942): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1942): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1942): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  954): acquireWL(7676893): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1942 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): releaseWL(355012b8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  954): releaseWL(117dd982): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  954): releaseWL(7676893): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/WeatherUtility( 1246): Weather sync is On
W/WeatherTimeKeeper( 1246): [refreshWeatherData] no weather data
,D/HtcUPManager( 1246): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1246): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1466): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3ed40742
,D/Process (  954): killProcessQuiet, pid=5201
I/ActivityManager(  954): Killing 5201:com.google.android.music:main/u0a159 (adj 15): empty #17
,D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5201
D/MediaRouterService(  954): Client com.google.android.music (pid 5201): Died!
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  954): acquireWL(1d9680d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null,
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(1d9680d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  954): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  954): runPSCheck
,D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  954): Checking...
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  954): >> updateStatus
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1246): closing low battery warning: level=100
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): processMsg: ApStaDisabledState
,D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 1
,I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  954): acquireWL(253468c9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  954): n_update end
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  954): releaseWL(253468c9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1246): closing low battery warning: level=100
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/WifiController(  954): battery changed pluggedType: 2
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
D/HtcPowerSaver(  954): updateBatteryInfo
,D/PMS     (  954): runPSCheck
D/HtcPowerSaver(  954): Checking...
I/HtcPowerSaver(  954): >> updateStatus
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  954): acquireWL(23b40bce): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{204cf474: PendingIntentRecord{38f79d9d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=224072, Int=0
V/AlarmManager(  954): sending alarm PendingIntent{1c2ad9fc: PendingIntentRecord{2191c885 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457344556548, Int=0,
,V/AlarmManager(  954): sending alarm PendingIntent{120916da: PendingIntentRecord{3e4cae9c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=359304, Int=0
,D/PMS     (  954): acquireWL(3971570b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1942 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1942): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1942): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1942): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1942): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1942): [NET] android_getaddrinfo_proxy+
D/libc    ( 1942): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1942): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  954): releaseWL(3971570b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): releaseWL(23b40bce): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1246): Weather sync is On
W/WeatherTimeKeeper( 1246): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1942): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1942): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1942): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1942): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1942): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1942): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1942): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1942): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1942): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1942): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1942): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1335): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true
D/DotMatrix( 1335): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1246): reapply : com.google.android.gms 4 40
E/PlayEventLogger( 5652): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5652): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5652): Ignoring header User-Agent because its value was null.
,D/libc    ( 5652): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5652): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5652): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5652): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5652): [NET] android_getaddrinfo_proxy+
D/libc    ( 5652): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5652): [NET] android_getaddrinfo_proxy-, NODATA
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  954): acquireWL(2a2edcf5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/BatteryService(  954): n_update end
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  954): releaseWL(2a2edcf5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/PMS     (  954): runPSCheck
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  954): Checking...
D/UsbnetService(  954): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): processMsg: ApStaDisabledState
D/PowerUI ( 1246): closing low battery warning: level=100
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  954): acquireWL(17c4ea8a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(17c4ea8a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  954): Checking...
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  954): >> updateStatus
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  954): battery changed pluggedType: 2
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  954): handleMessage: E msg.what=155652
I/HtcPowerSaver(  954): << updateStatus
D/WifiController(  954): processMsg: ApStaDisabledState
D/PowerUI ( 1246): closing low battery warning: level=100
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  954): acquireWL(f0a18fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(f0a18fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  954): updateBatteryInfo
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  954): runPSCheck
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  954): Checking...
I/HtcPowerSaver(  954): >> updateStatus
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1246): closing low battery warning: level=100
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  954): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  954): << updateStatus
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/WifiController(  954): handleMessage: E msg.what=155652
,D/WifiController(  954): processMsg: ApStaDisabledState,
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1499): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1499): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1499): sku_id=118
,D/ContactMessageStore( 1499): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1499): start background delete task...
D/ContactMessageStore( 1499): size: 0 , 0
D/ContactMessageStore( 1499): Background delete complete,
,D/PMS     (  954): acquireWL(80b4d18): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 954 1000 WorkSource{1000}
V/AlarmManager(  954): sending alarm PendingIntent{204cf474: PendingIntentRecord{38f79d9d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=404073, Int=0
,V/AlarmManager(  954): sending alarm PendingIntent{16dd5371: PendingIntentRecord{3e4cae9c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=667367, Int=0
D/PMS     (  954): acquireWL(260f2556): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1942 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1942): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1942): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1942): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1942): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1942): [NET] android_getaddrinfo_proxy+
D/libc    ( 1942): [NET] android_getaddrinfo_proxy get netid:0
,D/PMS     (  954): releaseWL(80b4d18): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1942): [NET] android_getaddrinfo_proxy-, NODATA
D/WeatherUtility( 1246): Weather sync is On
W/WeatherTimeKeeper( 1246): [refreshWeatherData] no weather data
,D/PMS     (  954): releaseWL(260f2556): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1942): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1942): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1942): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1942): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1942): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1942): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1942): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1942): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1942): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1942): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1942): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1335): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true
D/DotMatrix( 1335): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5652): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5652): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1246): reapply : com.google.android.gms 3 40
W/System  ( 5652): Ignoring header User-Agent because its value was null.
D/libc    ( 5652): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5652): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5652): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5652): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5652): [NET] android_getaddrinfo_proxy+
D/libc    ( 5652): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5652): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  954): acquireWL(3f82c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(3f82c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  954): updateBatteryInfo
D/NotificationService(  954): plugged=true pluggin=true
,I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  954): Checking...
D/UsbnetService(  954): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  954): >> updateStatus
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1246): closing low battery warning: level=100
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): handleMessage: E msg.what=155652
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  954): processMsg: ApStaDisabledState
,D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  954): acquireWL(15d8fae1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  954): n_update end
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  954): releaseWL(15d8fae1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/PMS     (  954): runPSCheck
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  954): Checking...
D/UsbnetService(  954): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): handleMessage: E msg.what=155652
D/PowerUI ( 1246): closing low battery warning: level=100
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): processMsg: DefaultState
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  954): handleMessage: X
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  954): acquireWL(14d99006): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 954 1000 WorkSource{1000}
V/AlarmManager(  954): sending alarm PendingIntent{204cf474: PendingIntentRecord{38f79d9d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=704072, Int=0
V/AlarmManager(  954): sending alarm PendingIntent{2860378b: PendingIntentRecord{2663068 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804880, Int=0
,I/ActivityManager(  954): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6239 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  954): sending alarm PendingIntent{152856c7: PendingIntentRecord{3187c4f4 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457344952877, Int=0
,V/AlarmManager(  954): sending alarm PendingIntent{3d89641d: PendingIntentRecord{141e5e0c com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457345179293, Int=0
,W/ContextImpl( 6140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  954): releaseWL(14d99006): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1246): Weather sync is On
D/PowerUsageList:PowerUsageHelper( 6140): MY_DEBUG = false
W/WeatherTimeKeeper( 1246): [refreshWeatherData] no weather data
,I/art     (  415): Explicit concurrent mark sweep GC freed 8652(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 435us total 37.096ms
,D/PowerUsageService( 6140): repeat time = 1457346079362
,I/art     (  415): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 339us total 22.717ms,
,I/art     (  415): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 239us total 23.620ms
,I/PowerUsageList:PowerUsageHelper( 6140): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6140): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 6140): calcPower(), no data,
,E/cutils-trace( 6261): Error opening trace file: Permission denied (13),
I/dex2oat ( 6261): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6261): dex2oat: override thread count:4,
,I/dex2oat ( 6261): dex2oat took 558.828ms (threads: 4),
,I/PushClient( 6239): ApplicationMonitor {2d210882}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6239): ApplicationMonitor {2d210882}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6239): ApplicationMonitor {2d210882}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6239): ApplicationMonitor {2d210882}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6239): ApplicationMonitor {2d210882}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6239): ApplicationMonitor {2d210882}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6239): ApplicationMonitor {2d210882}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6239): ApplicationMonitor {2d210882}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6239): ApplicationMonitor {2d210882}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6239): PnsModel {1f4157cd}: update(): Update registration caused by: alarm,
,I/PushClient( 6239): PnsConfigModel {34dfc0e8}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6239): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6239): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6239): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6239): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  954): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6269 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/art     (  414): Explicit concurrent mark sweep GC freed 8647(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 187us total 35.083ms,
,I/art     (  414): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 177us total 22.093ms,
,I/DeviceManagement( 6269): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6269 dbg=false s=true
,I/DeviceManagement( 6269): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6269): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/art     (  414): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 170us total 23.607ms
I/DeviceManagement( 6269): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6269): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6269): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@15fd7964] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 6269): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6269): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6269): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6269): SessionStateController: Checking invariants...
,I/DeviceManagement( 6269): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6269): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6269): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6269): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@15fd7964],
,I/DeviceManagement( 6269): WorkflowService: Stopping workflow service,
,I/ActivityManager(  954): Killing 5952:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  954): killProcessQuiet, pid=5952
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5952
,D/WifiService(  954): Client connection lost with reason: 4
,I/PushClient( 6239): PnsModel {1f4157cd}: update(): Start updating since the registration has expired.,
,W/PushClient( 6239): GCMRegistrator {10f33bfb}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.
W/PushClient( 6239):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
W/PushClient( 6239):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
,W/PushClient( 6239):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
W/PushClient( 6239):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
W/PushClient( 6239):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
W/PushClient( 6239):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/PushClient( 6239):   	at android.os.Handler.dispatchMessage(Handler.java:102)
W/PushClient( 6239):   	at android.os.Looper.loop(Looper.java:155)
W/PushClient( 6239):   	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PushClient( 6239):   
,D/GCM     ( 1942): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER,
,D/libc    ( 1942): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 1942): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1942): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 1942): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1942): [NET] android_getaddrinfo_proxy+
D/libc    ( 1942): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504,
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1942): [NET] android_getaddrinfo_proxy-, NODATA
,E/PushClient( 6239): PnsModel {1f4157cd}: update(): com.htc.lib1.cs.push.exception.UpdateRegistrationFailedException: SERVICE_NOT_AVAILABLE,
E/PushClient( 6239):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:198)
E/PushClient( 6239):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
E/PushClient( 6239):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
E/PushClient( 6239):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PushClient( 6239):   	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PushClient( 6239):   	at android.os.Looper.loop(Looper.java:155)
E/PushClient( 6239):   	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PushClient( 6239):   Caused by: java.io.IOException: SERVICE_NOT_AVAILABLE
E/PushClient( 6239):   	at com.google.android.gms.gcm.GoogleCloudMessaging.register(Unknown Source)
E/PushClient( 6239):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.registerGCM(GCMRegistrator.java:301)
E/PushClient( 6239):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:196)
E/PushClient( 6239):   	... 6 more
E/PushClient( 6239):   
,I/PushClient( 6239): CentralClientRetryPolicy {26fe79b8}: scheduleUpdateRetry(): Waiting for network connectivity...
,I/PackageManager(  954):  setEnabledSetting(), pkgName=com.htc.cs.pns, clsName=com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver, state=1, flag=1, pid=6239, uid=10071, userID:0,
,I/ActivityManager(  954): Killing 5708:com.test.thalitest/u0a366 (adj 15): empty #17
,D/Process (  954): killProcessQuiet, pid=5708
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5708,
D/WifiService(  954): Client connection lost with reason: 4
E/InputEventReceiver( 1388): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{afe6c32 uid 10366 pid 5708} (c)'
,I/art     (  954): Explicit concurrent mark sweep GC freed 27690(1578KB) AllocSpace objects, 9(1028KB) LOS objects, 33% free, 18MB/27MB, paused 1.973ms total 198.935ms
,V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1942): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1942): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1942): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1942): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1942): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1942): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1942): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1942): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1942): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1942): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1942): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1335): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true
D/DotMatrix( 1335): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5652): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5652): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5652): Ignoring header User-Agent because its value was null.
D/libc    ( 5652): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5652): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5652): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5652): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5652): [NET] android_getaddrinfo_proxy+
D/libc    ( 5652): [NET] android_getaddrinfo_proxy get netid:0
I/RemoteViews( 1246): reapply : com.google.android.gms 3 40
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5652): [NET] android_getaddrinfo_proxy-, NODATA
,I/Prism.ItemManager( 1547): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1547): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1727): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1727): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana,
,W/ResourcesManager(  954): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/SystemReader(  954): Cannot find grip_rejection_width, use default value instead
,I/[PluginManager]RegisterService( 1466): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.pns
,I/[PluginManager]RegisterService( 1466): handle notify Blinkfeed plugin client changed
,D/AccTypeManager( 1727): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  954): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=6306 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/PhoneApp( 1499): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,E/ExternalAccountType( 1727): Unsupported attribute readOnly
,W/PackageManager(  954): Unable to load service info ResolveInfo{374a12d9 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  954): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  954): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  954): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  954): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  954): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  954): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  954): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  954): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  954): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  954): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  954): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  954): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  954): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  954): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 6306): -onCreate(),
,V/Settings:HtcSettingsApplication( 6306): [6306/6306] onCreate()
,D/Process (  954): killProcessQuiet, pid=5730
I/ActivityManager(  954): Killing 5730:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/Settings:HtcWirelessFeatureFlags( 6306): id/is att sku: 118/false
,E/Settings:HtcWrapHeaderInfo( 6306): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6306): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 6306): updateDevelopment, bPrefShow = true,
,E/Settings:HtcUmcWidgetEnabler( 6306): isSupportMusicChannel(): false
,I/ActivityManager(  954): Recipient 5730
,D/PackageBroadcastService( 4269): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.pns
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportRecentAppsButton]hasNavigationBar:true
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportHomeButton]support         :false
,I/ActivityManager(  954): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6334 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PeopleContactsSync( 4269): CP2 sync disabled
,I/ActivityManager(  954): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 6306): isSupportVoWifi: null,
E/ActivityThread( 6306): Failed to find provider info for com.htc.vowifi
,D/PMS     (  954): acquireWL(26f1c0f8): PARTIAL_WAKE_LOCK  Icing 0x1 4269 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4269, uid=10024, userID:0
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6306): The wrap header doesn't exist in header list.,
E/Settings:HtcWrapHeaderInfo( 6306): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 6306): isSupportMusicChannel(): false,
D/PMS     (  954): releaseWL(26f1c0f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6306): [supportHomeButton]support         :false
,E/Settings:HtcVoWifiWidgetEnabler( 6306): isSupportVoWifi: null
I/ActivityManager(  954): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 6306): Failed to find provider info for com.htc.vowifi
,W/ResourcesManager( 6334): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PMS     (  954): acquireWL(8096c36): PARTIAL_WAKE_LOCK  AsyncService 0x1 6334 10167 null,
,D/PMS     (  954): releaseWL(8096c36): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,D/PMS     (  954): acquireWL(30fdf4a4): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6334 10167 null,
,I/UpdateIcingCorporaServi( 5567): Updating corpora: APPS=com.htc.cs.pns, CONTACTS=MAYBE
,D/PMS     (  954): releaseWL(30fdf4a4): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5567): UpdateCorporaTask done [took 80 ms] updated apps [took 80 ms] 
,D/Process (  954): killProcessQuiet, pid=5150
I/ActivityManager(  954): Killing 5150:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5150
,I/Prism.ItemManager( 1547): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1547): loadItems() com.htc.launcher.pageview.WidgetManager@2f0cda9c +
I/Prism.WidgetManager( 1547): onLoadItems() +
,E/Prism.WidgetManager( 1547): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1547): onLoadItems() -
I/Prism.ItemManager( 1547): loadItems() com.htc.launcher.pageview.WidgetManager@2f0cda9c -
,D/PhoneApp( 1499): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1499): -- N1 =0
,D/PhoneApp( 1499): -- N2 =0,
,D/PhoneApp( 1499): -- N3 =0
,D/PMS     (  954): acquireWL(8f815c2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{204cf474: PendingIntentRecord{38f79d9d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1004073, Int=0
V/AlarmManager(  954): sending alarm PendingIntent{3e4e8fd3: PendingIntentRecord{777b710 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457345228730, Int=0
,D/SmartSyncUtils( 6140): isEpsOn(), nState = 0
,D/PMS     (  954): acquireWL(e200209): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6140 1000 null,
,D/PMS     (  954): releaseWL(8f815c2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1246): Weather sync is On
,W/WeatherTimeKeeper( 1246): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6140): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6140): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6140): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6140): SettingOnTime = 1457416800000, randomSettingOnTime = 1457413916000
,D/SmartSyncScreenOnOffTimeReceiver( 6140): SettingOffTime = 1457395200000, randomSettingOffTime = 1457397021000
,D/SmartSyncScreenOnOffTimeReceiver( 6140): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6140): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6140): bNightModeTurnOffOnce = false
,D/PMS     (  954): releaseWL(e200209): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  954): acquireWL(2035cc0e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null,
,D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  954): n_update end
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  954): releaseWL(2035cc0e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1246): closing low battery warning: level=100
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/PMS     (  954): runPSCheck
D/HtcPowerSaver(  954): Checking...
D/WifiController(  954): handleMessage: E msg.what=155652
,I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): handleMessage: X
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  954): acquireWL(3be8562f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(3be8562f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  954): updateBatteryInfo
,D/UsbnetService(  954): BroadcastReceiver::onReceive+,
D/NotificationService(  954): plugged=true pluggin=true
,D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/PMS     (  954): runPSCheck
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  954): Checking...
D/UsbnetService(  954): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): handleMessage: E msg.what=155652
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  954): processMsg: ApStaDisabledState
I/HtcPowerSaver(  954): << updateStatus
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): handleMessage: X
D/PowerUI ( 1246): closing low battery warning: level=100
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  954): acquireWL(2389343c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
,I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(2389343c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  954): updateBatteryInfo
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  954): Checking...
D/UsbnetService(  954): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  954): >> updateStatus
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  954): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  954): handleMessage: E msg.what=155652
,I/HtcPowerSaver(  954): << updateStatus
D/WifiController(  954): processMsg: ApStaDisabledState
D/PowerUI ( 1246): closing low battery warning: level=100
D/WifiController(  954): processMsg: DefaultState
D/NotificationService(  954): plugged=true pluggin=true
D/WifiController(  954): handleMessage: X
D/WifiController(  954): battery changed pluggedType: 2
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  954): acquireWL(11bdb5c5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
D/UsbnetService(  954): BroadcastReceiver::onReceive+
I/BatteryService(  954): n_update end
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/PMS     (  954): releaseWL(11bdb5c5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  954): updateBatteryInfo
D/NotificationService(  954): plugged=true pluggin=true
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  954): runPSCheck
D/WifiController(  954): handleMessage: E msg.what=155652
D/HtcPowerSaver(  954): Checking...
D/WifiController(  954): processMsg: ApStaDisabledState
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): handleMessage: X
D/PowerUI ( 1246): closing low battery warning: level=100
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  954): User[0] Flushing usage stats to disk
,D/PMS     (  954): acquireWL(36869b1a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null,
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(36869b1a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  954): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  954): Checking...
D/WifiController(  954): handleMessage: E msg.what=155652
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): processMsg: ApStaDisabledState
D/PowerUI ( 1246): closing low battery warning: level=100
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): handleMessage: X
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  954): << updateStatus
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true,
,V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1942): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1942): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1942): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1942): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1942): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1942): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1942): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1942): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1942): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1942): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1942): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5652): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5652): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5652): Ignoring header User-Agent because its value was null.
D/libc    ( 5652): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5652): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5652): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5652): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5652): [NET] android_getaddrinfo_proxy+
D/libc    ( 5652): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND),
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5652): [NET] android_getaddrinfo_proxy-, NODATA
,D/DotMatrix( 1335): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true
D/DotMatrix( 1335): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1246): reapply : com.google.android.gms 2 40
,D/PMS     (  954): acquireWL(6a0246c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
,I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(6a0246c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  954): plugged=true pluggin=true
,D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/PMS     (  954): runPSCheck
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  954): Checking...
D/UsbnetService(  954): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  954): >> updateStatus
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  954): battery changed pluggedType: 2
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1246): closing low battery warning: level=100
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  954): acquireWL(34d09a35): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
,I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(34d09a35): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  954): Checking...
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1246): closing low battery warning: level=100
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  954): acquireWL(5cbfeca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(5cbfeca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  954): updateBatteryInfo
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  954): Checking...
D/UsbnetService(  954): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  954): >> updateStatus
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  954): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  954): << updateStatus
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): processMsg: ApStaDisabledState
D/NotificationService(  954): plugged=true pluggin=true
D/WifiController(  954): processMsg: DefaultState
,D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): handleMessage: X
D/PowerUI ( 1246): closing low battery warning: level=100
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1246): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1246): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1246): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1400000ms),E/cutils-trace( 6368): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6368): ====startRecUseTime====
D/htc.customization.log.level( 6368):  is 
W/CustomizationLogLevel( 6368): Level value is invalid, use default level 2
D/CustomizationManager( 6368):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 6368): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6368): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6368): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6368): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6368): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6368): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6368): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6368): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6368): Parsing tag category name = system
I/CustomizationCIDLoader( 6368): Parsing tag category name = application
I/CustomizationCIDLoader( 6368): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6368): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6368): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6368): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6368): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6368): add string-array item, value = 42507
I/CustomizationCIDLoader( 6368): add string-array item, value = 21902
I/CustomizationCIDLoader( 6368): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6368): add string-array item, value = 23420
I/CustomizationCIDLoader( 6368): add string-array item, value = 22299
I/CustomizationCIDLoader( 6368): add string-array item, value = 24002
I/CustomizationCIDLoader( 6368): add string-array item, value = 23210
I/CustomizationCIDLoader( 6368): add string-array item, value = 23205
I/CustomizationCIDLoader( 6368): add string-array item, value = 23806
I/CustomizationCIDLoader( 6368): add string-array item, value = 23430
I/CustomizationCIDLoader( 6368): add string-array item, value = 23408
I/CustomizationCIDLoader( 6368): add string-array item, value = 27205
I/CustomizationCIDLoader( 6368): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6368): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6368): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6368): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6368): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6368): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6368): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6368): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6368): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6368): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6368): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6368): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6368):  Read CID file spent 0.126 (s)
D/CustomizationManager( 6368):  All configurations done spent 0.126 (s)
D/PackageManager(  954): deletePackageAsUser: pkg=com.test.thalitest, pid=6368, uid=2000 userid=0
I/ActivityManager(  954): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
W/PackageSettings(  954): Skipping PackageSetting{2ee9ac83 com.example.hello/10374} due to missing metadata
I/ActivityManager(  954): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
W/SystemReader(  954): Cannot find grip_rejection_width, use default value instead
D/DotMatrix( 1335): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/InputMethodManagerService(  954): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/DotMatrix( 1335): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1335): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  954): acquireWL(2cb89504): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1858 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1858): Ignoring removeGeofence because network location is disabled.
D/PMS     (  954): releaseWL(2cb89504): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/PackageManager(  954): Unable to load service info ResolveInfo{16abfd70 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  954): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  954): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  954): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  954): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  954): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  954): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  954): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  954): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  954): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  954): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  954): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  954): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  954): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  954): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/AccTypeManager( 1727): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/AccTypeManager( 1727): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1665): Cleaning up data for package: com.test.thalitest
I/art     ( 5567): Explicit concurrent mark sweep GC freed 9218(561KB) AllocSpace objects, 0(0B) LOS objects, 44% free, 2MB/4MB, paused 795us total 98.254ms
I/[PluginManager]RegisterService( 1466): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/AccTypeManager( 1727): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/art     ( 1547): Explicit concurrent mark sweep GC freed 53265(3MB) AllocSpace objects, 16(1776KB) LOS objects, 34% free, 30MB/46MB, paused 1.135ms total 146.685ms
D/Prism.PackageStateRece_( 1547): action: android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService(  954): Receieved: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1466): handle notify Blinkfeed plugin client changed
I/Prism.ItemManager( 1547): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1547): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
E/ExternalAccountType( 1727): Unsupported attribute readOnly
D/PhoneApp( 1499): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/Launcher( 1547): Deferring update until onResume
D/Launcher( 1547): waitUntilResume // bindAppsRemoved
I/ActivityManager(  954): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/TaskPersister(  954): removeObsoleteFile: deleting file=12_task.xml
D/TaskPersister(  954): removeObsoleteFile: deleting file=12_task_thumbnail.png
I/art     (  954): Explicit concurrent mark sweep GC freed 29983(2MB) AllocSpace objects, 8(288KB) LOS objects, 33% free, 18MB/27MB, paused 1.572ms total 212.879ms
W/asset   (  954): Copying FileAsset 0x5576219580 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/ContextImpl( 6388): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/Process (  954): killProcessQuiet, pid=6034
I/ActivityManager(  954): Killing 6034:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  954): Recipient 6034
E/NetworkScheduler.SchedulerReceiver( 1942): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1942): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PMS     (  954): acquireWL(2294e232): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1942 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  954): acquireWL(3afbbb83): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 954 1000 WorkSource{1000}
V/AlarmManager(  954): sending alarm PendingIntent{204cf474: PendingIntentRecord{38f79d9d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1064072, Int=0
V/AlarmManager(  954): sending alarm PendingIntent{1aa2f100: PendingIntentRecord{3e4cae9c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1283459, Int=0
D/PMS     (  954): releaseWL(2294e232): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/WeatherUtility( 1246): Weather sync is On
W/WeatherTimeKeeper( 1246): [refreshWeatherData] no weather data
D/ChimeraCfgMgr( 4269): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4269): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 4269): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4269): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4269): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4269): Module APK com.google.android.play.games already loaded
I/ActivityManager(  954): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6420 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
I/LocationSettingsChecker( 4269): Removing dialog suppression flag for package com.test.thalitest
D/GOOGLEHELP_CompatibleDatabase( 4269): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4269): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4269): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 4269): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4269): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4269): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4269): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4269): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4269): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4269): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4269): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4269): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4269): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/PMS     (  954): acquireWL(417bcad): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4269 10024 null
I/ConfigService( 1942): onCreate
I/ConfigFetchService( 4269): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/PMS     (  954): releaseWL(417bcad): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
W/BaseAppContext( 4269): Using Auth Proxy for data requests.
W/BaseAppContext( 4269): Using Auth Proxy for data requests.
D/PMS     (  954): acquireWL(2c8f653a): PARTIAL_WAKE_LOCK  Icing 0x1 4269 10024 WorkSource{10024 com.google.android.gms}
I/PeopleContactsSync( 4269): CP2 sync disabled
I/Icing   ( 4269): doRemovePackageData com.test.thalitest
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4269, uid=10024, userID:0
D/PMS     (  954): releaseWL(2c8f653a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
I/art     ( 1942): Explicit concurrent mark sweep GC freed 21778(1253KB) AllocSpace objects, 15(876KB) LOS objects, 49% free, 4MB/8MB, paused 786us total 67.747ms
W/DriveInitializer( 4269): Awaiting to be initialized
W/DriveInitializer( 4269): Background init thread started
E/SQLiteLog( 4269): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error
E/SQLiteDBG( 4269): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5575b143d0
E/DocListDatabase( 4269): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 4269): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4269): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4269): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/DocListDatabase( 4269): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4269): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4269): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/DocListDatabase( 4269): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 4269): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 4269): 	at com.google.android.gms.drive.r.run(SourceFile:69)
W/DriveInitializer( 4269): Background init thread ended
E/SQLiteLog( 4269): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AndroidRuntime( 4269): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4269): Process: com.google.android.gms, PID: 4269
E/AndroidRuntime( 4269): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4269): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4269): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 4269): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4269): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4269): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 4269): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 4269): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 4269): 	at com.google.android.gms.drive.r.run(SourceFile:69)
E/SQLiteDBG( 4269): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5575b143d0
E/ActivityManager(  954): App crashed! Process: com.google.android.gms
E/DriveAsyncService( 4269): disk I/O error (code 3850)
E/DriveAsyncService( 4269): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4269): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4269): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/DriveAsyncService( 4269): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4269): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4269): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/DriveAsyncService( 4269): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/DriveAsyncService( 4269): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 4269): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 4269): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 4269): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 4269): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 4269): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4269): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4269): 	at java.lang.Thread.run(Thread.java:818)
D/Process ( 4269): killProcess, pid=4269
D/Process ( 4269): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/GAv4    ( 6420): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6420):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6420):   adb logcat -s GAv4
E/DropBoxManagerService(  954): Can't write: system_app_crash
E/DropBoxManagerService(  954): java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  954): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  954): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  954): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  954): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  954): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  954): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  954): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  954): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  954): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  954): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  954): 	... 5 more
W/GAv4    ( 6420): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6420): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 6420): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6420): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 6420): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 6420): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 6420): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
E/SQLiteDatabase( 6420): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6420): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6420): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6420): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6420): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6420): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6420): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6420): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6420): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6420): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6420): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6420): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6420): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6420): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 6420): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 6420): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6420): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6420): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6420): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6420): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6420): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6420): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6420): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6420): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6420): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6420): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6420): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6420): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6420): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/ActivityManager(  954): Recipient 4269
E/SharedPreferencesImpl( 6420): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/ActivityManager(  954): Process com.google.android.gms (pid 4269) has died
W/GAv4    ( 6420): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/ActivityManager(  954): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
E/SQLiteDatabase( 6420): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6420): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6420): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6420): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6420): 	at aen.run(PG:536)
W/ActivityManager(  954): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
E/GAv4    ( 6420): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/ActivityManager(  954): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
E/SharedPreferencesImpl( 6420): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/ConfigService( 1942): onDestroy
E/SharedPreferencesImpl( 6420): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/ActivityManager(  954): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=6463 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ResourcesManager( 6463): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6463): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/VoldConnector(  954): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 6420): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
E/SQLiteDatabase( 6420): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6420): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6420): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6420): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6420): 	at aej.c(PG:139)
E/SQLiteDatabase( 6420): 	at aej.b(PG:398)
E/SQLiteDatabase( 6420): 	at agf.f(PG:417)
E/SQLiteDatabase( 6420): 	at oe.run(PG:1112)
E/SQLiteDatabase( 6420): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6420): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6420): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6420): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6420): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 6420): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 6420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 6420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 6420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 6420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 6420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 6420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 6420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 6420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 6420): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 6420): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 6420): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 6420): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 6420): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 6420): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 6420): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 6420): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 6420): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 6420): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 6420): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 6420): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 6420): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6420): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/PMS     (  954): acquireWL(ea804de): PARTIAL_WAKE_LOCK  AsyncService 0x1 6334 10167 null
D/PMS     (  954): releaseWL(ea804de): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  954): acquireWL(3a2fa18c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6334 10167 null
D/PMS     (  954): releaseWL(3a2fa18c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
I/MultiDex( 6463): VM with version 2.1.0 has multidex support
I/MultiDex( 6463): install
I/MultiDex( 6463): VM has multidex support, MultiDex support library is disabled.
I/UpdateIcingCorporaServi( 5567): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
V/JNIHelp ( 6420): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/DeviceManagement( 6269): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 6269): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 6269): WorkflowService: Starting workflow service
I/DeviceManagement( 6269): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@399db39e] args=[Bundle[mParcelledData.dataSize=112]]
I/DeviceManagement( 6269): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 6269): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 6269): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 6269): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/ActivityManager(  954): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6494 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a
I/DeviceManagement( 6269): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 5567): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 5567): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55758bc720
E/SQLiteLog( 6269): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 6269): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.cs.dm/databases/provisioning.db, handle: 0x55758c1630
E/SQLiteDatabase( 6463): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 6463): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6463): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6463): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6463): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 6463): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 6463): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 6463): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6463): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6463): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6463): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6463): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6463): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6463): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 6463): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6463): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6463): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6463): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6463): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 6463): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 6463): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 6463): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6463): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6463): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6463): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6463): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6463): 	at java.lang.Thread.run(Thread.java:818)
W/DeviceManagement( 6269): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@399db39e]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 6269): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 6269): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 6269): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
W/DeviceManagement( 6269): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 6269): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 6269): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 6269): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/DeviceManagement( 6269): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 6269): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 6269): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 6269): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 6269): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 6269): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 6269): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 6269): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 6269): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 6269): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 6269): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 6269): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 6269): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 6269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 6269): 	at android.os.Looper.loop(Looper.java:155)
W/DeviceManagement( 6269): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System  ( 6420): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6420): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  954): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=6517 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
I/DeviceManagement( 6269): WorkflowService: Stopping workflow service
E/SharedPreferencesImpl( 5567): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
V/GLSActivity( 1942): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/AndroidRuntime( 5567): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5567): Process: com.google.android.googlequicksearchbox:search, PID: 5567
E/AndroidRuntime( 5567): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5567): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 5567): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 5567): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 5567): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 5567): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 5567): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 5567): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 5567): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 5567): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 5567): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/AndroidRuntime( 5567): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 5567): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 5567): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 5567): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 5567): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 5567): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 5567): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5567): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5567): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5567): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  954): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 5567): killProcess, pid=5567
E/DropBoxManagerService(  954): Can't write: system_app_crash
E/DropBoxManagerService(  954): java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  954): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  954): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  954): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  954): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  954): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  954): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  954): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  954): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  954): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  954): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  954): 	... 5 more
E/SharedPreferencesImpl( 6420): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
D/Process ( 5567): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.y.uncaughtException:113 java.lang.ThreadGroup.uncaughtException:693 
V/JNIHelp ( 6463): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
```
