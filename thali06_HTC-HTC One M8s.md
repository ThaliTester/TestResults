#### Test 60124347d4f5b03_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
I/SoundPicker( 5131): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5131): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5131): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5131): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5131): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/[PluginManager]RegisterService( 1481): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1481): handle notify Blinkfeed plugin client changed
I/SoundPicker( 5131): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
--------- beginning of system
I/ActivityManager(  967): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5430 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/PMS     (  967): acquireWL(10e8777f): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10005}
I/SoundPicker( 5131): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5131): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/Process (  967): killProcessQuiet, pid=4895
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
V/AlarmManager(  967): sending alarm PendingIntent{329dc34c: PendingIntentRecord{37757f95 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1457399572751, Int=0
I/ActivityManager(  967): Killing 4895:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  967): Recipient 4895
I/ActivityManager(  967): Waited long enough for: ServiceRecord{2998b90d u0 com.google.android.gms/.config.ConfigFetchService}
I/Prism.ItemManager( 1566): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1566): loadItems() com.htc.launcher.pageview.WidgetManager@351ccb48 +
I/Prism.WidgetManager( 1566): onLoadItems() +
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5430): -onCreate()
I/Prism.ItemManager( 4613): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4613): loadItems() com.htc.launcher.pageview.WidgetManager@39c209fd +
I/Prism.WidgetManager( 4613): onLoadItems() +
W/ResourcesManager( 1566): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/Settings:HtcSettingsApplication( 5430): [5430/5430] onCreate()
E/cutils-trace( 5455): Error opening trace file: Permission denied (13)
W/ResourcesManager( 4613): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/Process (  967): killProcessQuiet, pid=4923
I/ActivityManager(  967): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5464 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  967): Killing 4923:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
I/ActivityManager(  967): Recipient 4923
D/Settings:HtcWirelessFeatureFlags( 5430): id/is att sku: 118/false
D/CustomizationManager( 5455): ====startRecUseTime====
D/htc.customization.log.level( 5455):  is 
W/CustomizationLogLevel( 5455): Level value is invalid, use default level 2
E/Settings:HtcWrapHeaderInfo( 5430): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5430): The wrap header doesn't exist in header list.
D/CustomizationManager( 5455):  Read ACC file spent 0.041 (s)
D/CIDMapFileReader( 5455): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5455): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5455): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5455): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5455): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5455): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5455): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5455): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5455): Parsing tag category name = system
I/CustomizationCIDLoader( 5455): Parsing tag category name = application
I/CustomizationCIDLoader( 5455): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5455): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5455): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5455): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5455): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5455): add string-array item, value = 42507
I/CustomizationCIDLoader( 5455): add string-array item, value = 21902
I/CustomizationCIDLoader( 5455): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5455): add string-array item, value = 23420
I/CustomizationCIDLoader( 5455): add string-array item, value = 22299
I/CustomizationCIDLoader( 5455): add string-array item, value = 24002
I/CustomizationCIDLoader( 5455): add string-array item, value = 23210
I/CustomizationCIDLoader( 5455): add string-array item, value = 23205
I/CustomizationCIDLoader( 5455): add string-array item, value = 23806
I/CustomizationCIDLoader( 5455): add string-array item, value = 23430
I/CustomizationCIDLoader( 5455): add string-array item, value = 23408
I/CustomizationCIDLoader( 5455): add string-array item, value = 27205
I/CustomizationCIDLoader( 5455): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5455): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5455): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5455): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5455): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5455): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5455): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5455): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5455): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5455): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5455): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5455): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5455):  Read CID file spent 0.089 (s)
D/CustomizationManager( 5455):  All configurations done spent 0.090 (s)
E/Settings:HtcWrapHeaderInfo( 5430): updateDevelopment, bPrefShow = true
W/ResourcesManager( 1566): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5464, uid=10072, userID:0
W/global  ( 5464): [apache-http] Connection GC has been deprecated!
E/Settings:HtcUmcWidgetEnabler( 5430): isSupportMusicChannel(): false
D/Finsky  ( 5464): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5455 on display 0
W/global  ( 5464): [apache-http] Connection GC has been deprecated!
D/PMS     (  967): acquireHCC(2c24e8aa): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 967 1000 null
D/PMS     (  967): acquireHCC(28170c9b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 967 1000 null
W/asset   (  967): Copying FileAsset 0x55a0fc9e70 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportHomeButton]support         :false
D/PMS     (  967): acquireWL(1440e576): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 967 1000 null
I/AnimationUtil(  967): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1566): [onPause]
I/FeedProviderManager( 1566): onPause
I/FeedHostManager( 1566): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2cb001c2
I/SocialFeedProvider( 1566): +onPause
I/SocialFeedProvider( 1566): -onPause
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5506 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  967): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5430): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5430): isSupportVoWifi: null
D/StatusBarManagerService(  967): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5430): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 5430): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 5430): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5430): [supportHomeButton]support         :false
W/asset   ( 5506): Copying FileAsset 0xac320fe8 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/ResourcesManager( 4613): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/global  ( 5464): [apache-http] Connection GC has been deprecated!
I/ActivityManager(  967): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5430): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5430): isSupportVoWifi: null
I/TrimMemoryManager( 1566): [trimMemory] 20
D/PhoneApp( 1516): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1516): -- N1 =0
D/PhoneApp( 1516): -- N2 =0
D/PhoneApp( 1516): -- N3 =0
D/Finsky  ( 5464): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/asset   ( 1566): Copying FileAsset 0x55a0f212a0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/ActivityManager(  967): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5536 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/Settings( 5464): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/WebViewFactory( 5506): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
W/Settings( 5464): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ResourcesManager( 5536): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5536): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5464, uid=10072, userID:0
I/Prism.WidgetManager( 1566): onLoadItems() -
I/Prism.ItemManager( 1566): loadItems() com.htc.launcher.pageview.WidgetManager@351ccb48 -
W/asset   ( 1566): Copying FileAsset 0x55a0cee730 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Prism.ItemManager( 1566): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1566): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/MultiDex( 5536): VM with version 2.1.0 has multidex support
I/MultiDex( 5536): install
I/MultiDex( 5536): VM has multidex support, MultiDex support library is disabled.
I/Launcher( 1566): Deferring update until onResume
D/Launcher( 1566): waitUntilResume // bindAppsAdded
D/Finsky  ( 5464): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
W/asset   ( 4613): Copying FileAsset 0x55a0b06a90 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
D/Finsky  ( 5464): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 5464): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/LibraryLoader( 5506): Time to load native libraries: 14 ms (timestamps 9808-9822)
I/LibraryLoader( 5506): Expected native library version number "",actual native library version number ""
V/JNIHelp ( 5536): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 5464): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/WebViewChromiumFactoryProvider( 5506): Binding Chromium to main looper Looper (main, tid 1) {94c6b89}
I/LibraryLoader( 5506): Expected native library version number "",actual native library version number ""
I/ActivityManager(  967): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5566 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/PackageBroadcastService( 4227): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  967): Killing 4870:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=4870
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/chromium( 5506): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ActivityThread( 5536): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5536): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a56f895: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5536): Installed default security provider GmsCore_OpenSSL
I/Prism.WidgetManager( 4613): onLoadItems() -
I/Prism.ItemManager( 4613): loadItems() com.htc.launcher.pageview.WidgetManager@39c209fd -
I/BrowserStartupController( 5506): Initializing chromium process, singleProcess=true
W/art     ( 5506): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5506): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  967): Recipient 4870
W/chromium( 5506): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5506): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5506): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5506): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5506): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5506): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5506): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5506): Local Branch: 
I/Adreno-EGL( 5506): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5506): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5506):                  d74aa161a12b9c6fc6332151
I/PackageBroadcastService( 4227): Null package name or gms related package.  Ignoreing.
D/PMS     (  967): acquireWL(1494d7ac): PARTIAL_WAKE_LOCK  Icing 0x1 4227 10024 WorkSource{10024 com.google.android.gms}
W/ResourcesManager( 5566): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/System.err(  967): java.lang.Throwable: stack dump
W/System.err(  967): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  967): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  967): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  967): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  967): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fa87044:true
D/BluetoothAdapter( 5506): 17250117: getState() :  mService = null. Returning STATE_OFF
I/Icing   ( 4227): Storage manager: low false usage 2.04MB avail 5.77GB capacity 7.95GB
W/Icing   ( 4227): Received bad json for section weights override -- ignoring.
W/Icing   ( 4227): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4227): Received bad json for section weights override -- ignoring.
W/Icing   ( 4227): Received bad json for corpus context scoring override -- ignoring.
W/art     ( 5506): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 1828): Explicit concurrent mark sweep GC freed 10936(539KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 1.616ms total 47.392ms
W/AwContents( 5506): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5506): CordovaWebView is running on device made by: HTC
W/art     ( 5506): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5506): Attempt to remove local handle scope entry from IRT, ignoring
D/Process (  967): killProcessQuiet, pid=4613
I/ActivityManager(  967): Killing 4613:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  967): Recipient 4613
I/HtcModeClient( 3156): handler message = 4011
E/HtcModeClient( 3156): Check connection and retry 6 times.
E/Icing   ( 4227): Loading extension by file descriptor -1 failed
W/chromium( 5506): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/ActivityManager(  967): Killing 4968:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=4968
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 4968
,D/WifiService(  967): Client connection lost with reason: 4
,D/PMS     (  967): acquireWL(4c84f6a): PARTIAL_WAKE_LOCK  AsyncService 0x1 5566 10167 null
V/Finsky  ( 5464): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/AlarmManager(  967): sending alarm PendingIntent{1ede6cf8: PendingIntentRecord{29b825d1 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457399574647, Int=0
,D/PMS     (  967): releaseWL(4c84f6a): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Finsky  ( 5464): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/PMS     (  967): acquireWL(7655337): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5566 10167 null,
,I/UpdateIcingCorporaServi( 5377): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/FindExtension( 5506): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  967): releaseWL(7655337): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/Icing   ( 4227): updateResources: need to parse f{com.google.android.gms}
,I/GLSUser ( 1828): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1828): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1828): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1828): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/InputMethodManager( 5506): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3f171e31, mServedView=org.apache.cordova.engine.SystemWebView{32f0f916 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1982f297
,I/InputMethodManagerService(  967): Disable input method client, pid=1566
D/StatusBarManagerService(  967): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  967): Enable input method client, pid=5506
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,W/BindingManager( 5506): Cannot call determinedVisibility() - never saw a connection for the pid: 5506
,I/UpdateIcingCorporaServi( 5377): UpdateCorporaTask done [took 151 ms] updated apps [took 151 ms] 
,W/XT9_C   ( 1364): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,I/XT9_C   ( 1364): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1364): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1364): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/art     (  967): Explicit concurrent mark sweep GC freed 19190(1011KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.530ms total 159.160ms,
D/PMS     (  967): releaseWL(1440e576): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[PluginManager]RegisterService( 1481): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1481): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1566): action: android.intent.action.PACKAGE_ADDED
I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +1s467ms
,I/ActivityManager(  967): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5647 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,D/JsMessageQueue( 5506): Set native->JS mode to OnlineEventsBridgeMode,
I/Icing   ( 4227): Internal init done: storage state 0
,W/Finsky  ( 5464): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
I/Icing   ( 4227): Post-init done,
I/Icing   ( 4227): updateResources: need to parse f{com.google.android.gms}
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  967): releaseWL(1494d7ac): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSUser ( 1828): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1828): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1828): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1828): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DeviceManagement( 5647): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5647 dbg=false s=true
,I/DeviceManagement( 5647): PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  967): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5670 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,I/art     (  415): Explicit concurrent mark sweep GC freed 8652(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 182us total 23.481ms
,I/GLSUser ( 1828): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1828): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1828): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1828): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/art     (  415): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 363us total 23.604ms
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  415): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 262us total 22.247ms
,D/jxcore_app_log( 5506): JniHelper::setJavaVM(0xab1c78f8), pthread_self() = -1404185808
,W/Finsky  ( 5464): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/HtcCupdReceiver(Provider)( 5670):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  967): Killing 5050:com.htc.task.gtask/u0a66 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=5050
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5506): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5506):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5506):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5506):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5506):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5506): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fce5a08 added. We now have 1 listener(s)
,I/Prism.ItemManager( 1566): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1566): loadItems() com.htc.launcher.pageview.WidgetManager@351ccb48 +
I/Prism.WidgetManager( 1566): onLoadItems() +
,W/ResourcesManager( 1566): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  967): Recipient 5050
,E/AndroidHttpClient( 5464): Leak found
E/AndroidHttpClient( 5464): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5464): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5464): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5464): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5464): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5464): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5464): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5464): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5464): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5464): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5464): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5464): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5464): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5464): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5464): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5464): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5464): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506): setBluetoothMacAddress: 90:E7:C4:F6:69:77
D/PMS     (  967): releaseHCC(2c24e8aa): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5506): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/PMS     (  967): releaseHCC(28170c9b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5506): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12304add added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5506): addListener: New listener added - the number of listeners is now 1
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5506): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
D/WifiService(  967): New client listening to asynchronous messages
E/WifiTrafficPoller(  967): ADD_CLIENT: 6
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5506): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5506): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5506): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved",
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5506): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,D/PackageBroadcastService( 4227): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 4227): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4227): Loading module APK com.google.android.play.games,
,D/PMS     (  967): acquireWL(38125821): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4227 10024 null
,I/chromium( 5506): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ResourcesManager( 1566): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/ConfigFetchService( 4227): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  967): acquireWL(281b555d): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4227 10024 WorkSource{10366 com.test.thalitest}
I/ConfigFetchService( 4227): launchTask
,D/PMS     (  967): releaseWL(38125821): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  967): acquireWL(a93ded2): PARTIAL_WAKE_LOCK  Icing 0x1 4227 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4227): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4227): Module APK com.google.android.play.games already loaded
D/PMS     (  967): releaseWL(a93ded2): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4227): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/PeopleContactsSync( 4227): CP2 sync disabled
D/Vision  ( 4227): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 4227): Failed to find package metadata for com.test.thalitest
D/Vision  ( 4227): No vision deps
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4227, uid=10024, userID:0
V/ConfigFetchTask( 4227): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WKcWMWvCU23ME-060oMI-0Nt2IjOb3iC_tLRYeRUCexn4OtPmmJcXEgqD3ZCQtJ-bFpFS_Ud9Gl0JMrv656wJP4FJRw9Yser-Q7_IOhdj7HzT8Olja7A3gGIHINz5t70wYo6olADobN6Ier3TB-mXNIhOx9wtE1MCFa8SbOLKn9wnkIVvfXavfqa9XQEjp-EPn0pB_
E/Prism.WidgetManager( 1566): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1566): onLoadItems() -
I/Prism.ItemManager( 1566): loadItems() com.htc.launcher.pageview.WidgetManager@351ccb48 -
I/GoogleURLConnFactory( 4227): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  967): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5704 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1828): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1828): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1828): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1828): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 5464): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
D/libc    ( 4227): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4227): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4227): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4227): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4227): [NET] android_getaddrinfo_proxy+
D/libc    ( 4227): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4227): [NET] android_getaddrinfo_proxy-, NODATA
,I/GAV2    ( 5270): Thread[GAThread,5,main]: No campaign data found.
,W/ConfigFetchTask( 4227): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname,
I/ConfigFetchService( 4227): fetch service done; releasing wakelock
D/PMS     (  967): releaseWL(281b555d): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10366 com.test.thalitest}
D/Finsky  ( 5464): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
I/ConfigFetchService( 4227): stopping self
,D/Finsky  ( 5464): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5464): [1] DailyHygiene.reschedule: Scheduling new run in 751 minutes (failures=5)
,W/BaseAppContext( 4227): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4227): Using Auth Proxy for data requests.
,I/ActivityManager(  967): Killing 5158:com.htc.updater/u0a84 (adj 15): empty #17
,D/Process (  967): killProcessQuiet, pid=5158
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/DeviceConnectionService( 1792): client connected with version: 7571000
,I/ActivityManager(  967): Recipient 5158,
,D/Process (  967): killProcessQuiet, pid=3672
,I/ActivityManager(  967): Killing 3672:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 3672
,D/Process (  967): killProcessQuiet, pid=5215
,I/ActivityManager(  967): Killing 5215:com.google.android.setupwizard/u0a77 (adj 15): empty #18
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  967): Recipient 5215
,W/BaseAppContext( 4227): Using Auth Proxy for data requests.
,W/BaseAppContext( 4227): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4227): Using Auth Proxy for data requests.
,W/BaseAppContext( 4227): Using Auth Proxy for data requests.
,W/jxcore-log( 5506): Initializing JXcore engine
,W/jxcore-log( 5506): JXcore engine is ready
,I/ActivityManager(  967): Waited long enough for: ServiceRecord{1562f977 u0 com.htc.club/com.mcrm.autonotification.NotificationService}
,W/jxcore-log( 5506): Starting JXcore engine
,I/GAv4    ( 5704): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5704):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5704):   adb logcat -s GAv4
,W/GAv4    ( 5704): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/jxcore-log( 5506): Platform android
W/jxcore-log( 5506): 
,W/jxcore-log( 5506): Process ARCH arm
W/jxcore-log( 5506): 
W/GAv4    ( 5704): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5704): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/AnalyticsTrackerProxyImpl( 5704): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,D/ChimeraCfgMgr( 4227): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4227): Module APK com.google.android.play.games already loaded
,D/VoldConnector(  967): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 5704): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,D/PMS     (  967): acquireWL(1d2d18e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 5566 10167 null
,D/PMS     (  967): acquireWL(3f26dda6): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5566 10167 null,
D/PMS     (  967): releaseWL(1d2d18e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  967): releaseWL(3f26dda6): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,W/ResourcesManager( 5704): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5704): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5704): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/UpdateIcingCorporaServi( 5377): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  967): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5754 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,W/System  ( 5704): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5704): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncApplication( 5754): Loading default preferences
,W/asset   ( 5377): Copying FileAsset 0x55a0967c40 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.,
,W/Resources( 5754): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
I/UpdateIcingCorporaServi( 5377): UpdateCorporaTask done [took 70 ms] updated apps [took 70 ms] 
I/ActivityManager(  967): Killing 5082:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=5082
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  967): ADD_CLIENT: 7,
D/WifiService(  967): New client listening to asynchronous messages
,D/SyncApplication( 5754): Overriding preferences with custom values,
,D/SyncApplication( 5754): Updating preferences succeeded
,I/jxcore-log( 5506): JXcore Cordova bridge is ready!
I/jxcore-log( 5506): 
W/jxcore-log( 5506): JXcore engine is started,
,I/org.thaliproject.p2p.ThaliPermissions( 5506): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5506): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 5506): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5506): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,I/ActivityManager(  967): Recipient 5082
,E/SyncApplication( 5754): Application created.
,W/VolumeInfo( 5754): Unable to read mount points
W/VolumeInfo( 5754): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5754): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5754): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5754): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5754): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5754): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5754): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5754): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5754): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5754): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5754): ,	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5754): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5754): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5754): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5754): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5754): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5754): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5754): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5754): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5754): 	... 13 more
V/VolumeInfo( 5754): Found 0 mount point(s)
V/VolumeInfo( 5754): New VolumeInfo with mount point /storage/emulated/0 and sys path null created,
D/VolumeInfo( 5754): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 5754): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/VolumeInfo( 5754): Can not create volume ID for unmounted volume null
I/CalendarDefines( 5754): getNewCalendarAuthority()...
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5754, uid=10005, userID:0,
D/SyncApplication( 5754): enableAppOperation()+
W/PackageManager(  967): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5754, uid=10005, userID:0
W/PackageManager(  967): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 5754): enableAppOperation()-,
,D/HTCUtilities( 5754): isNeorSinged() + 
D/PMS     (  967): acquireWL(3a217ff5): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 967 1000 null
,W/PluginManager( 5506): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 166ms. Plugin should use CordovaInterface.getThreadPool().
,W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/HTCUtilities( 5754): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>,
D/HTCUtilities( 5754): isNeorSinged() return false
,I/FeedHostManager( 1566): [onResume]
I/FeedProviderManager( 1566): onResume
,I/SocialFeedProvider( 1566): +onResume
I/SocialFeedProvider( 1566): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1566): -onResume
,I/ConnectivityHelper( 1566): [getCurrentConnectionType] no network connection
,D/StatusBarManagerService(  967): setSystemUiVisibility(0x8700),
D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
,D/FindExtension( 1566): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,D/CDMountReceiver( 5754): whether to enable CD Auto-mount: true
D/CDMountReceiver( 5754): showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,I/ThreadedRenderer( 1566): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  967): Disable input method client, pid=5506
D/StatusBarManagerService(  967): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  967): Enable input method client, pid=1566
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
I/ActionCombine( 5754): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
W/IInputConnectionWrapper( 5506): reportFullscreenMode on inactive InputConnection
,D/Process (  967): killProcessQuiet, pid=5131
I/ActivityManager(  967): Killing 5131:com.htc.sdm/u0a79 (adj 15): empty #17,
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/StatusBarManagerService(  967): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
,D/CDMountReceiver( 5754): enable CD Auto-mount: true
,I/ActivityManager(  967): Recipient 5131,
,D/PMS     (  967): releaseWL(3a217ff5): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/PMS     (  967): releaseWL(10e8777f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10005}
D/HTCUtilities( 5754): enable auto-mount
D/HTCUtilities( 5754): enable auto-mount
I/HtcMountManagerAdapter( 5754): mHtcMountManager is  null
I/HtcMountManagerAdapter( 5754): mStorageManager is  not null
I/HtcMountManagerAdapter( 5754): mHtcMountManager is  null
D/VoldConnector(  967): SND -> {21 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
I/HtcMountManagerAdapter( 5754): mStorageManager is  not null
,D/VoldConnector(  967): SND -> {22 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
D/MountService(  967): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  967): mountISO: /system/etc/PCTOOL.ISO
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/PMS     (  967): acquireWL(37e332a9): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5004 10159 null
,I/ActivityManager(  967): Killing 5344:com.htc.calendar/u0a10 (adj 15): empty #17
,D/Process (  967): killProcessQuiet, pid=5344
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/RemoteViews( 1221): apply : com.nero.android.htc.sync 0 14 4 38
,I/RemoteViews( 1221): apply : com.nero.android.htc.sync 0 9 2 53,
,I/ActivityManager(  967): Recipient 5344
,D/WearableService( 4588): callingUid 10024, callindPid: 4588,
D/GCM     ( 1828): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1828): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5004, uid=10159, userID:0,
,D/PMS     (  967): releaseWL(37e332a9): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 5004): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5004): Stop autocaching.
,V/GmsCoreStatsServiceLauncher( 4227): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4227, uid=10024, userID:0,
E/MDM     ( 1792): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 4227): Restart initialization of location
E/GmsUtils( 5004): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 5004): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/Finsky  ( 5464): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4227, uid=10024, userID:0
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4227, uid=10024, userID:0
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4227, uid=10024, userID:0
I/CheckinService( 4227): Done disabling old GoogleServicesFramework version
,W/OpenGLRenderer( 1566): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/art     (  967): Explicit concurrent mark sweep GC freed 17124(848KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 18MB/27MB, paused 1.493ms total 148.652ms,
,D/AutoSetting( 1481): service - handleMessage() stop self,
,D/AutoSetting( 1481): service - onDestroy() END,
,D/AutoSetting( 1481): service - handleMessage() quit looper
,I/HtcModeClient( 3156): handler message = 4011,
,E/HtcModeClient( 3156): Check connection and retry 7 times.
,D/PMS     (  967): acquireWL(efff678): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000}
V/AlarmManager(  967): sending alarm PendingIntent{38e4b151: PendingIntentRecord{1d0c5db6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=76024, Int=0
,I/ClockController( 1221): schedule update now=1457399580049 next=59951
I/Clock   ( 1221): updateClock:02:13 Europe/Warsaw
D/PMS     (  967): releaseWL(efff678): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
I/Clock   ( 1221): updateClock:02:13 Europe/Warsaw
I/Clock   ( 1221): updateClock:02:13 Europe/Warsaw
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/ConfigService( 1828): onDestroy
,D/Process (  967): killProcessQuiet, pid=4763
,I/ActivityManager(  967): Killing 4763:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 4763,
,I/ActivityManager(  967): Waited long enough for: ServiceRecord{f0f31f5 u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
,I/ActivityManager(  967): Waited long enough for: ServiceRecord{11edf871 u0 com.htc.musicenhancer/.EnhancerService},
,I/ActivityManager(  967): Killing 5239:com.google.android.talk/u0a112 (adj 15): empty #17,
D/Process (  967): killProcessQuiet, pid=5239
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5239
,W/MediaManager( 4951): [DualLensScanUtil],	mmpCursor count is 0
,D/Process (  967): killProcessQuiet, pid=4718
I/ActivityManager(  967): Killing 4718:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 4718,
,I/HtcModeClient( 3156): handler message = 4011,
E/HtcModeClient( 3156): Check connection and retry 8 times.
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/HtcModeClient( 3156): handler message = 4011,
E/HtcModeClient( 3156): Check connection and retry 9 times.
,D/PMS     (  967): acquireWL(772118d): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10072}
,V/AlarmManager(  967): sending alarm PendingIntent{cf89f42: PendingIntentRecord{356e1b53 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457399590438, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{1671c90: PendingIntentRecord{2afb3989 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=84895, Int=0,
V/AlarmManager(  967): sending alarm PendingIntent{21756d8e: PendingIntentRecord{103519af android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=85326, Int=0
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, err=8
D/PMS     (  967): releaseWL(772118d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024,
D/libc    (  967): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  967): [NET] android_getaddrinfo_proxy+
D/libc    (  967): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    (  967): [NET] android_getaddrinfo_proxy-, NODATA
,D/Finsky  ( 5464): [557] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5464): [1] 5.onFinished: Installation state replication succeeded.,
,D/ContactMessageStore( 1516): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1516): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 3156): handler message = 4011,
E/HtcModeClient( 3156): Check connection and retry 10 times.
,D/PMS     (  967): acquireWL(20c971bc): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10024}
V/AlarmManager(  967): sending alarm PendingIntent{9d4e545: PendingIntentRecord{28338eaf com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=93628, Int=0
,D/PMS     (  967): acquireWL(25ded49a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1828 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  967): releaseWL(20c971bc): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1828): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1828): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1828): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1828): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1828): [NET] android_getaddrinfo_proxy+
D/libc    ( 1828): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1828): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  967): releaseWL(25ded49a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5805 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5805): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5805): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5805): MmsConfig.loadMmsSettings
,I/ActivityManager(  967): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=5835 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5805, uid=10112, userID:0
,W/HtcWrapAdjustableCursorFactory( 5835): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 5835): onCreate
,V/GetPrviateResource( 5835): GetPrviateResource
V/GetPrviateResource( 5835): GetPrviateResource
,D/MmsCustomizationProvider( 5835): query uri: content://htc-mms-customization/mms-ua/ua_string,
,D/MessageCustFlag( 5835): sense_version=6.0
,D/MmsCustomizationProvider( 5835): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/BTAccessoryUtil( 5835): createReceiver
,D/BTAccessoryUtil( 5835): registerReceiver return intent = null,
D/MessageCustFlag( 5835): sku_id=118
,I/Babel_SMS( 5805): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml,
I/Babel_SMS( 5805): MmsConfig.loadFromDatabase
,D/HtcBuildUtils( 5835): getRATByHtcTelephonyCapability:1,
W/SystemReader( 5835): Cannot find qct_8960_interface, use default value instead,
,E/Babel_SMS( 5805): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5805): MmsConfig.loadFromResources
,W/Settings( 5805): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel_SMS( 5805): canonicalizeMccMnc: invalid mccmnc nullnull,
I/Babel_SMS( 5805): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_Crash( 5805): startup - clean,
,I/Babel   ( 5805): deleted: false for 0,
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5805, uid=10112, userID:0
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5805, uid=10112, userID:0
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5805, uid=10112, userID:0
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5805, uid=10112, userID:0
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5805, uid=10112, userID:0
,W/VideoCapabilities( 5805): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5805): Unsupported mime video/x-ms-wmv
,W/Utils   ( 5805): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 5805): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5805): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5805): Unsupported mime audio/qcelp
,W/VideoCapabilities( 5805): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 5805): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 5805): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5805): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5805): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5805): Unrecognized profile 2130706433 for video/avc
,D/Process (  967): killProcessQuiet, pid=5647
I/ActivityManager(  967): Killing 5647:com.htc.cs.dm/u0a99 (adj 15): empty #17
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5647,
,D/Process (  967): killProcessQuiet, pid=5405
I/ActivityManager(  967): Killing 5405:com.google.android.partnersetup/u0a27 (adj 15): empty #18
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5405
,I/vclib   ( 5805): onServiceConnected,
,W/Babel   ( 5805): Attempted to change video mute state without an active call.,
,I/HtcModeClient( 3156): handler message = 4011
E/HtcModeClient( 3156): Check connection and retry 11 times.
,D/Messaging( 5835): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 5835): networkCode: 
,D/MessageCustFlag( 5835): sku_id=118
,D/MmsConfig( 5835): SIE smsPri: null
D/MmsConfig( 5835): networkCode: 
,D/MmsConfig( 5835): packageName: com.htc.vvm.att does not exist,
,D/ReportIndicatorCache( 5835): startAsyncQueryReports ---,
D/MmsAsyncWorkHandler( 5835): 
D/MmsAsyncWorkHandler( 5835): HM tk = 20001
D/ReportIndicatorCache( 5835): MSG_QUERY_REPORTS >>,
D/SettingsManager( 5835): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@94c6b89
,D/DraftCache( 5835): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 5835): [DraftCache/1] refresh
,D/Messaging( 5835): mNeedToUpdateDate2 start
,D/TelephUtils( 1516): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1516):  slotId = -1000
D/MmsSmsV2Provider( 1516): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null,
,I/Messaging( 5835): mccmnc> ,
D/TelephUtils( 1516): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1516): sku_id=118
D/MmsConfig( 5835): networkCode: 
,D/Messaging( 5835): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1516): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1516):  slotId = -1000
D/MmsSmsV2Provider( 1516): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 5835): [DraftCache/141] rebuildCache
,D/TelephUtils( 1516): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/MmsSmsV2Provider( 1516):  slotId = -1000
D/MmsSmsV2Provider( 1516): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 5835): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1516): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1516):  slotId = -1000
,D/MmsSmsV2Provider( 1516): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 5835): mNeedToUpdateDate2: false
,D/PhoneStorageUtil( 5835): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5835): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5835): createReceiver
,D/TelephUtils( 1516): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49,
D/Jerry   ( 1516): URI_DRAFT
,D/DraftCache( 5835): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 5835): [DraftCache/141] rebuildCache time: 10,
D/MmsAsyncWorkHandler( 5835): 
D/MmsAsyncWorkHandler( 5835): HM tk = 20002
,D/TelephUtils( 1516): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1516): sku_id=118
,D/TelephUtils( 1516): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
,V/MmsProvider( 1516): Update uri=content://mms, match=0
V/MmsProvider( 1516): selection=st=129 AND m_type!=134
,D/Messaging( 5835): Reset downloading state: 0
D/MessageCustFlag( 5835): sense_version=6.0
D/Jerry   ( 5835): start to preload cursor >>>>>>>
V/MmsSystemEventReceiver( 5835): TransactionService is going to be woken up.
,D/TelephUtils( 1516): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/MmsSmsV2Provider( 1516):  slotId = -1000
V/TransactionService( 5835): 1-Creating TransactionService
,D/TelephUtils( 1516): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65,
D/AccFlag ( 1516): sku_id=118
D/Messaging( 5835): ViewCache CreatePreload
D/Messaging( 5835): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 5835): onStartCommand: 1
,D/MmsSystemEventReceiver( 5835): unRegisterForConnectionStateChanges
V/TransactionService( 5835): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
V/TransactionService( 5835): Loading previous transactions.
,D/TelephUtils( 1516): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/AccFlag ( 1516): device_type: 1
,D/TransactionService( 5835): Force clearing mTransactionList
,D/TransactionService( 5835): Force set service start id to 1
V/TransactionService( 5835): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5835): unRegisterForConnectionStateChanges
,D/TransactionService( 5835): stopSelfResult: true, mLastHandledServiceId: 1
D/Cust_MMSMS( 5835): _has_set_default_values_2=true
V/TransactionService( 5835): Destroying TransactionService
D/MsgPreferenceUtils( 5835): def_index: 0
,V/TransactionService( 5835): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/MsgPreferenceUtils( 5835): globalIndex = 1
,D/MsgPreferenceUtils( 5835): phone state: true
,D/MsgPreferenceUtils( 5835): sd state: false
D/MsgPreferenceUtils( 5835): vIndex = 0
,D/PMS     (  967): acquireWL(277e8b9b): PARTIAL_WAKE_LOCK  Icing 0x1 4227 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(277e8b9b): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(27da934d): PARTIAL_WAKE_LOCK  Icing 0x1 4227 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(27da934d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/HtcModeClient( 3156): handler message = 4011,
E/HtcModeClient( 3156): Check connection and retry 12 times.
,I/HtcModeClient( 3156): handler message = 4011,
,E/HtcModeClient( 3156): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3156): Don't start project servcice
,D/HtcModeClient( 3156): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3156): connectState: CONNECTION_READY = false
D/SilentMusic( 3156): call stop,
D/HtcModeClient( 3156): close connection
W/HtcModeClient( 3156): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3156): read the terminate packet, so break
,I/ActivityManager(  967): Killing 3156:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=3156
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 3156,
,I/ActivityManager(  967): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5890 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  967): acquireWL(b805e02): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10076}
V/AlarmManager(  967): sending alarm PendingIntent{39d8d313: PendingIntentRecord{553d950 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457399611299, Int=60000
D/PMS     (  967): releaseWL(b805e02): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 5890): SMSBackupAgentService started,
D/SMSBackup( 5890): Checking restore status
,D/SMSBackup( 5890): Restore complete
D/SMSBackup( 5890): cancelCheckAlarm
,D/SMSBackup( 5890): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  967): killProcessQuiet, pid=5670
I/ActivityManager(  967): Killing 5670:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  967): Recipient 5670,
,I/PMS     (  967): Going to sleep due to screen timeout (uid 1000)...,
D/ActivityManager(  967): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{189a584e #11 A=.Prism U=0 sz=1}
,I/SensorManager(  967): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2f7cfd09
W/PMS     (  967): mWirelessDisplayManager is null
W/SensorService(  967): Following SensorService logs are not warning, just make sure they are printed
W/PMS     (  967): mWirelessDisplayManager is still null
W/SensorService(  967): disable: get sensor name = Accelerometer Sensor
W/SensorService(  967): pid=967, uid=1000
I/PMS     (  967): Sleeping (uid 1000)...
W/SensorService(  967): Active sensors: size = 4
D/XAN-DPS (  967): prepareColorFade 1
W/SensorService(  967): Accelerometer Sensor (handle=0x00000000, connections=1)
W/PMN     (  967): goingToSleep
W/SensorService(  967): CM32181 Light sensor (handle=0x00000003, connections=1)
D/PMS     (  967): acquireWL(1af38d6f): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 967 1000 null
W/SensorService(  967): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  967): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  967): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2f7cfd09, eanble = 0, strlen(mName) = 91
W/SensorService(  967): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  967): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@3c00266a
W/SensorService(  967): Listener[1] = com.htc.smartdim.sensor_eye@1a8b330a
W/SensorService(  967): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMN     (  967): goingToSleep done
W/HtcLockScreen( 1221): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,D/AlarmManager(  967): ACTION_SCREEN_ON
I/AlarmManager(  967): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  967): [AlarmQueuing] done recovering
I/AlarmManager(  967): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  967): [AlarmQueuing] done EPS screen off alarm recovering
,I/Adreno-EGL(  967): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  967): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  967): Build Date: 03/09/15 Mon
I/Adreno-EGL(  967): Local Branch: 
I/Adreno-EGL(  967): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  967): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  967):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  967): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5912 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/FeedHostManager( 1566): [onPause]
I/FeedProviderManager( 1566): onPause
I/FeedHostManager( 1566): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2cb001c2
,I/SocialFeedProvider( 1566): +onPause
,I/SocialFeedProvider( 1566): -onPause
,W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
D/PMS     (  967): releaseWL(1af38d6f): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/WifiStateMachine(  967): handleMessage: E msg.what=131167
E/WifiStateMachine(  967): processMsg: InitialState
E/WifiStateMachine(  967):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  967):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
,V/SRS_Proc(  402): ParamSet string: screen_state=on,
E/audio_a2dp_hw(  402): adev_set_parameters: ERROR: set param called even when stream out is null
D/NetworkPolicy(  967): updateScreenOn: false
D/WifiController(  967): handleMessage: E msg.what=155650
V/NetworkPolicy(  967): updateIfacesLocked()
D/WifiController(  967): processMsg: ApStaDisabledState
D/NetworkManagementService(  967): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,D/WifiStateMachine(  967): getWifiLinkLayerStats: WIFI is not enbled,
D/WifiStateMachine(  967): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  967): handleScreenStateChanged Exit: true
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131154
E/WifiStateMachine(  967): processMsg: InitialState
E/WifiStateMachine(  967):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131127
E/WifiStateMachine(  967): processMsg: InitialState
E/WifiStateMachine(  967):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
,E/WifiStateMachine(  967):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131129
E/WifiStateMachine(  967): processMsg: InitialState
E/WifiStateMachine(  967):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
,E/WifiStateMachine(  967): handleMessage: X
,D/GpsLocationProvider(  967): receive broadcast intent, action: android.intent.action.SCREEN_ON
,W/ResourcesManager( 5912): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1221): receive(android.intent.action.SCREEN_ON,1,false),
,I/CalendarProvider2( 5912): Created com.android.providers.calendar.CalendarAlarmManager@25b7d53(com.htc.providers.calendar.HtcCalendarProvider@2255d690),
,D/CalendarProvider2( 5912): wait start:true
,D/PMS     (  967): acquireWL(3bf83680): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1792 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  967): acquireWL(104a64b9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1792 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(3bf83680): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(104a64b9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  967): prepareColorFade done
,D/XAN-DPS (  967): setBrightness to 0
,D/AlarmManager(  967): ACTION_SCREEN_OFF,
I/SensorManager(  967): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@3c00266a
,W/SensorService(  967): Following SensorService logs are not warning, just make sure they are printed
,I/DisplayManagerService(  967): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  967): disable: get sensor name = CM32181 Light sensor
I/AlarmManager(  967): [AlarmQueuing] screen off now: 
,I/AlarmManager(  967): [AlarmQueuing] data connection: true
I/AlarmManager(  967): [AlarmQueuing] wifi connection: false
,D/WifiDataStallTracker(  967): stopDataStallAlarm 
W/SensorService(  967): pid=967, uid=1000
W/SensorService(  967): Active sensors: size = 3,
E/WifiDataStallTracker(  967): ENABLE_DATA_MONITOR_POLL false Token 0
,W/SensorService(  967): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  967): CM36686 Proximity sensor (handle=0x00000004, connections=1)
D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
,D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
W/SensorService(  967): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  967): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@3c00266a, eanble = 0, strlen(mName) = 67
W/SensorService(  967): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  967): Listener[0] = com.htc.smartdim.sensor_eye@1a8b330a
W/SensorService(  967): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/WifiStateMachine(  967): handleMessage: E msg.what=131167
,E/WifiStateMachine(  967): processMsg: InitialState
E/WifiStateMachine(  967):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  967):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiStateMachine(  967): getWifiLinkLayerStats: WIFI is not enbled
E/WifiStateMachine(  967): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  967): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  967): handleScreenStateChanged Exit: false
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131154
E/WifiStateMachine(  967): processMsg: InitialState
E/WifiStateMachine(  967):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
V/SRS_Proc(  402): ParamSet string: screen_state=off
E/WifiStateMachine(  967):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  967): handleMessage: X
V/ActivityManager(  967): Display changed displayId=0
E/audio_a2dp_hw(  402): adev_set_parameters: ERROR: set param called even when stream out is null
D/DotMatrix( 1306): [EventService]  onDisplayChanged: 0
D/WifiController(  967): handleMessage: E msg.what=155651
D/WifiController(  967): processMsg: ApStaDisabledState
D/WifiController(  967): processMsg: DefaultState
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/WifiController(  967): handleMessage: X
D/NetworkPolicy(  967): updateScreenOn: false
V/NetworkPolicy(  967): updateIfacesLocked()
D/NetworkManagementService(  967): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/DotMatrix( 1306): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/CalendarProvider2( 5912): wait end:false
,I/SensorManager( 1221): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@1671a104, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,I/ActivityManager(  967): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5942 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
W/SensorService(  967): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  967): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  967): pid=1221, uid=10041,
,W/SensorService(  967): Active sensors: size = 4
W/SensorService(  967): Accelerometer Sensor (handle=0x00000000, connections=1)
,W/SensorService(  967): CM36686 Proximity sensor (handle=0x00000004, connections=1),
W/SensorService(  967): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  967): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  967): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@1671a104, eanble = 1, strlen(mName) = 57
W/SensorService(  967): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  967): Listener[0] = com.htc.smartdim.sensor_eye@1a8b330a,
W/SensorService(  967): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@1671a104
W/SensorService(  967): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  967): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1306): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1516): start background delete task...
,I/IntentController( 1221): receive(android.intent.action.SCREEN_OFF,1,false),
,D/ContactMessageStore( 1516): size: 0 , 0,
,D/ContactMessageStore( 1516): Background delete complete,
,W/ContextImpl( 5942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145),
,D/PowerUsageList:PowerUsageHelper( 5942): MY_DEBUG = false
,D/SmartSyncUtils( 5942): isEpsOn(), nState = 0
,I/RemoteViews( 1221): apply : com.htc.updater 1 18 1 36,
,D/SurfaceControl(  967): Excessive delay in setPowerMode(): 298ms
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node,
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
D/SmartDim(  967): Init customizeScreenOffDelayClass error
,W/ContextImpl( 5942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 5942): isEpsOn(), nState = 0
,D/SmartSyncUtils( 5942): isEpsOn(), nState = 0
,W/ContextImpl( 5942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  967): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@1a8b330a
W/SensorService(  967): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  967): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  967): pid=967, uid=1000
W/SensorService(  967): Active sensors: size = 3
W/SensorService(  967): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  967): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  967): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  967): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1a8b330a, eanble = 0, strlen(mName) = 36
,W/SensorService(  967): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  967): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@1671a104
W/SensorService(  967): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  967): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  967): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  967): pid=967, uid=1000,
W/SensorService(  967): Active sensors: size = 2
W/SensorService(  967): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  967): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  967): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1a8b330a, eanble = 0, strlen(mName) = 36
W/SensorService(  967): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  967): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@1671a104
W/SensorService(  967): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  967): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@1a8b330a
E/ActivityThread(  967): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3a8df77b that was originally registered here. Are you missing a call to unregisterReceiver()?,
E/ActivityThread(  967): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3a8df77b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  967): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  967): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  967): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  967): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  967): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  967): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  967): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  967): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  967): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  967): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  967): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  967): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  967): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  967): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  967): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  967): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  967): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  967): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     (  967): Explicit concurrent mark sweep GC freed 23441(1246KB) AllocSpace objects, 4(376KB) LOS objects, 33% free, 18MB/27MB, paused 1.989ms total 201.690ms,
D/PMS     (  967): acquireWL(3f26f1f1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1792 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  967): acquireWL(12b2a1d6): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5942 1000 null
D/PMS     (  967): Setting HAL interactive mode to false
D/PMS     (  967): Setting HAL interactive mode to false done
D/PMS     (  967): Setting HAL auto-suspend mode to true
D/PMS     (  967): Setting HAL auto-suspend mode done
D/PMS     (  967): acquireWL(24e24c57): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
D/PMS     (  967): releaseWL(3f26f1f1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(24e24c57): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/ActivityManager(  967): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5975 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/PowerUsageList:PowerUsageHelper( 5942): PowerProfile::POWER_SCREEN_FULL = 154.8
W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,D/PMS     (  967): acquireWL(9e73344): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1792 10024 WorkSource{10024 com.google.android.gms}
I/InputMethodManagerService(  967): screenObserver, isScreenOn=false
D/StatusBarManagerService(  967): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  967): Disable input method client, pid=1566
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/NotificationService(  967): plugged=true pluggin=true
,D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  967): Checking...
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
I/HtcPowerSaver(  967): >> updateStatus
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=97
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HABCtrl (  967): TPE algorithm. remove timeout.
D/PMS     (  967): OOBE c monitor 11
,D/PMS     (  967): releaseWL(9e73344): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
I/HtcPowerSaver(  967): updateStatus (8000,97,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: ApStaDisabledState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,D/NfcService( 1539): ScreenObserver: OFF
,D/PMS     (  967): releaseWL(12b2a1d6): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/NfcService( 1539): applyRouting - 0
D/PMS     (  967): acquireWL(13a7bc2d): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1539 1027 null
,D/NfcService( 1539): applyRouting -2
D/NfcService( 1539): applyRouting
D/NfcService( 1539): Ignore this applyRouting...
D/PMS     (  967): releaseWL(13a7bc2d): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PowerUsageList:BatterySipperExt( 5942): gen(), null == sipper.uidObj, userId = 0
,I/InputManager(  967): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false,
I/BatteryController( 1221): status:2 level:97 unsupport:false plugged:true
I/IntentController( 1221): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/PowerUsageService( 5942): calcPower(), no data,
,I/ClockController( 1221): stop clock update:screen off
,D/Process (  967): killProcessQuiet, pid=5430,
I/ActivityManager(  967): Killing 5430:com.android.settings/1000 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/SmartSyncUtils( 5942): getMobilePolicyEnabled, result = true
,D/WifiService(  967): New client listening to asynchronous messages
,E/WifiTrafficPoller(  967): ADD_CLIENT: 8
,I/ActivityManager(  967): Recipient 5430
,D/PowerUsageList:PowerUsageHelper( 5942): MY_DEBUG = false
,D/Process (  967): killProcessQuiet, pid=5704
I/ActivityManager(  967): Killing 5704:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5704,
,I/CalendarProvider2( 5912): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 5912): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  967): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6000 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
I/ActivityManager(  967): Killing 5566:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=5566
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5566
,D/PMS     (  967): releaseWL(2b76f0c2): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,W/ResourcesManager( 6000): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/CalendarApplication( 6000): onCreate,
,D/ProviderChangeReceiver( 6000): ---------------------------------------------------
,D/ProviderChangeReceiver( 6000): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  967): killProcessQuiet, pid=5377
I/ActivityManager(  967): Killing 5377:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/HtcAlertService( 6000): start to updateAlertNotification!
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  967): Recipient 5377
,D/HtcAlertService( 6000): No fired or scheduled alerts
D/HtcAlertUtils( 6000): -- cancelReminderNotification --,
,D/HtcAlertUtils( 6000): broadcastExistReminder!
,D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/ActivityManager(  967): Killing 5107:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=5107
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5107
,D/ContactMessageStore( 1516): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1516): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  967): acquireWL(318f0562): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000}
V/AlarmManager(  967): sending alarm PendingIntent{395556f3: PendingIntentRecord{1cc63fb0 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457399632189, Int=0
D/PMS     (  967): acquireWL(19f0ee29): PARTIAL_WAKE_LOCK  *backup* 0x1 967 1000 null
V/AlarmManager(  967): sending alarm PendingIntent{38e4b151: PendingIntentRecord{1d0c5db6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=136024, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{10dc15ae: PendingIntentRecord{2ee46f4f com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143226, Int=0
W/BackupManagerService(  967): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  967): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  967): releaseWL(19f0ee29): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/WeatherUtility( 1221): Weather sync is On
D/PMS     (  967): releaseWL(318f0562): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  967): acquireWL(3747a6dc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/UsbnetService(  967): onReceive BATTERY_CHANGED
I/BatteryService(  967): n_update end
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  967): releaseWL(3747a6dc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/NotificationService(  967): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=97
D/WifiController(  967): processMsg: ApStaDisabledState
D/HtcPowerSaver(  967): updateBatteryInfo
D/WifiController(  967): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): handleMessage: X
D/PMS     (  967): runPSCheck
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  967): Checking...
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  967): >> updateStatus
,I/HtcPowerSaver(  967): updateStatus (8000,97,-1,false,false,false,-1),
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:2 level:97 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  967): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  967): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
,D/PMS     (  967): acquireWL(88143e5): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10024},
,V/AlarmManager(  967): sending alarm PendingIntent{29d7deba: PendingIntentRecord{28338eaf com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=158444, Int=0,
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  967): acquireWL(14a2b16b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1828 10024 WorkSource{10024 com.google.android.gms}
,D/libc    (  967): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  967): sending alarm PendingIntent{21756d8e: PendingIntentRecord{103519af android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=146501, Int=0
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/PMS     (  967): releaseWL(88143e5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  967): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  967): [NET] android_getaddrinfo_proxy+
,D/libc    (  967): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    ( 1828): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1828): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  967): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    ( 1828): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1828): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1828): [NET] android_getaddrinfo_proxy+
D/libc    ( 1828): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1828): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  967): releaseWL(14a2b16b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1516): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  967): acquireWL(3f1654c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
D/UsbnetService(  967): BroadcastReceiver::onReceive+
I/BatteryService(  967): n_update end
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PMS     (  967): releaseWL(3f1654c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/NotificationService(  967): plugged=true pluggin=true
D/WifiController(  967): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=98
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/WifiController(  967): battery changed pluggedType: 2
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  967): updateBatteryInfo
D/WifiController(  967): processMsg: ApStaDisabledState
D/PMS     (  967): runPSCheck
D/WifiController(  967): processMsg: DefaultState
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): handleMessage: X
I/HtcPowerSaver(  967): >> updateStatus
I/HtcPowerSaver(  967): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:2 level:98 unsupport:false plugged:true,
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcAppUPService( 1481): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@29aa955a,
D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/Process (  967): killProcessQuiet, pid=5270
I/ActivityManager(  967): Killing 5270:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5270
,D/PMS     (  967): acquireWL(5073961): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000}
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
V/AlarmManager(  967): sending alarm PendingIntent{19952c86: PendingIntentRecord{db8f947 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=190573, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{38e4b151: PendingIntentRecord{1d0c5db6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=196024, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{21756d8e: PendingIntentRecord{103519af android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=218461, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{79ff574: PendingIntentRecord{79d0a9d com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=185799, Int=0
,D/libc    (  967): [NET] android_getaddrinfofornet-, err=8
D/PMS     (  967): acquireWL(29878b12): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1828 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  967): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  967): [NET] android_getaddrinfo_proxy+
D/libc    (  967): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    (  967): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  967): releaseWL(5073961): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
D/PMS     (  967): releaseWL(29878b12): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  967): acquireWL(1d01e2e3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000}
V/AlarmManager(  967): sending alarm PendingIntent{38e4b151: PendingIntentRecord{1d0c5db6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=256024, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{b80f4e0: PendingIntentRecord{28338eaf com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=288067, Int=0,
,D/PMS     (  967): acquireWL(14cf465e): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1828 10024 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  967): sending alarm PendingIntent{e65ca3f: PendingIntentRecord{10b07f0c com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457399845062, Int=0
,D/libc    ( 1828): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1828): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1828): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1828): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1828): [NET] android_getaddrinfo_proxy+
D/libc    ( 1828): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1828): [NET] android_getaddrinfo_proxy-, NODATA,
,D/PMS     (  967): releaseWL(14cf465e): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(1d01e2e3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data,
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1828): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1828): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1828): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1828): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActionCombine( 1828): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,W/ResourcesManager( 1221): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1221): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 1306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/GLSActivity( 1828): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1828): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1828): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1828): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1828): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1828): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1828): 	at android.os.Binder.execTransact(Binder.java:454)
W/ResourcesManager( 1306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/ResourcesManager( 1306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/PlayEventLogger( 5464): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5464): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5464): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889),
E/PlayEventLogger( 5464): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5464): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5464): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5464): 	at android.os.Binder.execTransact(Binder.java:454)
W/ResourcesManager( 1306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/RemoteViews( 1221): apply : com.google.android.gms 0 21 7 40
,W/System  ( 5464): Ignoring header User-Agent because its value was null.
,D/libc    ( 5464): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5464): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5464): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5464): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5464): [NET] android_getaddrinfo_proxy+
D/libc    ( 5464): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5464): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  967): acquireWL(3408030e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(3408030e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/HtcPowerSaver(  967): updateBatteryInfo,
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NotificationService(  967): plugged=true pluggin=true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  967): >> updateStatus
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): closing low battery warning: level=99
D/WifiController(  967): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): processMsg: ApStaDisabledState
I/HtcPowerSaver(  967): updateStatus (8000,99,-1,false,false,false,-1)
D/WifiController(  967): processMsg: DefaultState
I/HtcPowerSaver(  967): << updateStatus
D/WifiController(  967): handleMessage: X
,I/BatteryController( 1221): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  457): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  967): acquireWL(32bc12f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(32bc12f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] reorderNotification, total:0
D/HtcPowerSaver(  967): updateBatteryInfo
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  967): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PMS     (  967): runPSCheck
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: ApStaDisabledState
W/ContextImpl( 5942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/ActivityManager(  967): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=6037 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 6037): -onCreate(),
,V/Settings:HtcSettingsApplication( 6037): [6037/6037] onCreate()
,D/TetherSettings( 6037): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 6037): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 6037): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6037): Cust_ConnectToPC   : spcsc>false
D/        ( 6037): Cust_ConnectToPC   : IPT>true
D/        ( 6037): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 6037): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 6037): Index of the first 1 = -1
,W/ContextImpl( 6037): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6037): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 6037): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 6037): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 6037): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 6037): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 6037): [ACC]android_networking:tethering_guard_support=false
,W/SystemReader( 6037): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,D/Process (  967): killProcessQuiet, pid=5754,
I/ActivityManager(  967): Killing 5754:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  967): Recipient 5754
D/WifiService(  967): Client connection lost with reason: 4
,D/PMS     (  967): acquireWL(10c298c5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{38e4b151: PendingIntentRecord{1d0c5db6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=376024, Int=0
,V/AlarmManager(  967): sending alarm PendingIntent{1ac5421a: PendingIntentRecord{28338eaf com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=600318, Int=0,
,D/PMS     (  967): acquireWL(3a3d414b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1828 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1828): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1828): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1828): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1828): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1828): [NET] android_getaddrinfo_proxy+
D/libc    ( 1828): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1828): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  967): releaseWL(10c298c5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/PMS     (  967): releaseWL(3a3d414b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  967): acquireWL(fbd728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(fbd728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: ApStaDisabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  967): updateBatteryInfo
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  967): runPSCheck
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  967): Checking...
I/HtcPowerSaver(  967): >> updateStatus,
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/ContactMessageStore( 1516): MSG_CHECK_DELETION >>,
D/ContactMessageStore( 1516): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1516): sku_id=118
D/ContactMessageStore( 1516): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1516): start background delete task...
D/ContactMessageStore( 1516): size: 0 , 0
,D/ContactMessageStore( 1516): Background delete complete
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1828): Explicit concurrent mark sweep GC freed 18516(1045KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 1.018ms total 74.822ms
,I/GLSUser ( 1828): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1828): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1828): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1828): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1828): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1828): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1828): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1828): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1828): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1828): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1828): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5464): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5464): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5464): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5464): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5464): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5464): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5464): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5464): Ignoring header User-Agent because its value was null.
,D/libc    ( 5464): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5464): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5464): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5464): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5464): [NET] android_getaddrinfo_proxy+
D/libc    ( 5464): [NET] android_getaddrinfo_proxy get netid:0
,I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5464): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  967): acquireWL(368265ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
,I/BatteryService(  967): n_update end
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PMS     (  967): releaseWL(368265ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/PMS     (  967): runPSCheck
D/HtcPowerSaver(  967): Checking...
I/HtcPowerSaver(  967): >> updateStatus
,D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: ApStaDisabledState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  967): << updateStatus
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  967): acquireWL(34c5133b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(34c5133b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): updateBatteryInfo
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  967): >> updateStatus
D/UsbnetService(  967): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  967): << updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  967): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  967): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  967): processMsg: ApStaDisabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  967): acquireWL(1e675a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
D/UsbnetService(  967): BroadcastReceiver::onReceive+
I/BatteryService(  967): n_update end
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PMS     (  967): releaseWL(1e675a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  967): updateBatteryInfo
D/WifiController(  967): handleMessage: E msg.what=155652
D/PMS     (  967): runPSCheck
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  967): Checking...
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  967): processMsg: ApStaDisabledState
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  967): acquireWL(279877b1): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{14491496: PendingIntentRecord{2967a817 android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=583434, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{38e4b151: PendingIntentRecord{1d0c5db6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=616024, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{1671c90: PendingIntentRecord{2afb3989 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806507, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{f23c404: PendingIntentRecord{370bdded com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457400360708, Int=1800000
,D/HtcSystemUPManager(  967): UPAlarmListener onAlarmArrival
D/HtcSystemUPManager(  967): UPAlarmListener [SYSTEM_UP_FLUSH] cur = 1457400370911, last = 1457378487409, freq = 21600000
,I/ActivityManager(  967): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6067 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  967): sending alarm PendingIntent{1ff9e422: PendingIntentRecord{1534aeb3 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457400370895, Int=0
,D/HtcSystemUPManager(  967): AlarmScheduler_INEXACT [onReceive] end
D/HtcSystemUPManager(  967): com.htc.upm.AlarmScheduler$SchedulerBase$1@bfa6cbf
,D/HtcSystemUPManager(  967): HtcSystemUPHandler sendService() has been called,
,D/HtcSystemUPManager(  967): HtcSystemUPDataStore [sendToService] No data needs to be sent to service
D/HtcSystemUPManager(  967): HtcSystemUPHandler send to UPService takes: 3 ms
D/PMS     (  967): acquireWL(261b1c70): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4227 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(279877b1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  967): acquireWL(22f6206e): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4227 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(261b1c70): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/art     (  416): Explicit concurrent mark sweep GC freed 8662(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 425us total 44.433ms
,I/art     (  416): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 312us total 22.076ms,
,I/EventLogService( 4227): Aggregate from 1457398560673 (log), 1457398560673 (data)
,I/art     (  416): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 300us total 21.766ms,
,D/PMS     (  967): releaseWL(22f6206e): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,E/cutils-trace( 6089): Error opening trace file: Permission denied (13),
I/dex2oat ( 6089): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6089): dex2oat: override thread count:4
,I/dex2oat ( 6089): dex2oat took 732.131ms (threads: 4),
,I/PushClient( 6067): ApplicationMonitor {2747be9a}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6067): ApplicationMonitor {2747be9a}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6067): ApplicationMonitor {2747be9a}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6067): ApplicationMonitor {2747be9a}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6067): ApplicationMonitor {2747be9a}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6067): ApplicationMonitor {2747be9a}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
I/PushClient( 6067): ApplicationMonitor {2747be9a}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6067): ApplicationMonitor {2747be9a}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6067): ApplicationMonitor {2747be9a}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6067): PnsModel {1073745}: update(): Update registration caused by: alarm
,I/PushClient( 6067): PnsConfigModel {1d1403c0}: <init>(): Use dm-client for provisioning.
,W/System.err( 6067): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6067): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6067): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6067): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  967): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6096 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6096): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6096 dbg=false s=true,
,I/DeviceManagement( 6096): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6096): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6096): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6096): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6096): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1ae9cbbc] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6096): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6096): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6096): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6096): SessionStateController: Checking invariants...
,I/DeviceManagement( 6096): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6096): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6096): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6096): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1ae9cbbc],
,I/DeviceManagement( 6096): WorkflowService: Stopping workflow service,
,D/Process (  967): killProcessQuiet, pid=5506
I/ActivityManager(  967): Killing 5506:com.test.thalitest/u0a366 (adj 15): empty #17
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5506
D/WifiService(  967): Client connection lost with reason: 4
E/InputEventReceiver( 1364): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{31bd2541 uid 10366 pid 5506} (c)'
,I/PushClient( 6067): PnsModel {1073745}: update(): Start updating since the registration has expired.,
,W/PushClient( 6067): GCMRegistrator {ffa2133}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.,
W/PushClient( 6067):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
W/PushClient( 6067):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
W/PushClient( 6067):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
W/PushClient( 6067):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
W/PushClient( 6067):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
W/PushClient( 6067):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/PushClient( 6067):   	at android.os.Handler.dispatchMessage(Handler.java:102)
W/PushClient( 6067):   	at android.os.Looper.loop(Looper.java:155)
W/PushClient( 6067):   	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PushClient( 6067):   
,D/GCM     ( 1828): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER,
,D/libc    ( 1828): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 1828): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1828): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 1828): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1828): [NET] android_getaddrinfo_proxy+,
D/libc    ( 1828): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1828): [NET] android_getaddrinfo_proxy-, NODATA
,E/PushClient( 6067): PnsModel {1073745}: update(): com.htc.lib1.cs.push.exception.UpdateRegistrationFailedException: SERVICE_NOT_AVAILABLE,
E/PushClient( 6067):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:198)
E/PushClient( 6067):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
E/PushClient( 6067):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
E/PushClient( 6067):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PushClient( 6067):   	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PushClient( 6067):   	at android.os.Looper.loop(Looper.java:155)
E/PushClient( 6067):   	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PushClient( 6067):   Caused by: java.io.IOException: SERVICE_NOT_AVAILABLE
E/PushClient( 6067):   	at com.google.android.gms.gcm.GoogleCloudMessaging.register(Unknown Source)
E/PushClient( 6067):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.registerGCM(GCMRegistrator.java:301)
E/PushClient( 6067):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:196)
E/PushClient( 6067):   	... 6 more
E/PushClient( 6067):   
,I/PushClient( 6067): CentralClientRetryPolicy {2255d690}: scheduleUpdateRetry(): Waiting for network connectivity...,
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.htc.cs.pns, clsName=com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver, state=1, flag=1, pid=6067, uid=10071, userID:0
,I/ActivityManager(  967): Killing 5004:com.google.android.music:main/u0a159 (adj 15): empty #17,
D/Process (  967): killProcessQuiet, pid=5004
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5004
,D/MediaRouterService(  967): Client com.google.android.music (pid 5004): Died!
,D/PMS     (  967): acquireWL(35ec7a15): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000}
V/AlarmManager(  967): sending alarm PendingIntent{38e4b151: PendingIntentRecord{1d0c5db6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=916024, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{420912a: PendingIntentRecord{380d82ff com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457400465700, Int=0
,W/ContextImpl( 5942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  967): releaseWL(35ec7a15): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PowerUsageList:PowerUsageHelper( 5942): MY_DEBUG = false,
,D/PowerUsageService( 5942): repeat time = 1457401365750,
,I/PowerUsageList:PowerUsageHelper( 5942): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5942): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 5942): calcPower(), no data
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1828): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1828): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1828): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1828): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1828): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1828): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1828): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1828): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1828): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1828): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1828): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,E/PlayEventLogger( 5464): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5464): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5464): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5464): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5464): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5464): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5464): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5464): Ignoring header User-Agent because its value was null.
D/libc    ( 5464): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5464): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5464): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5464): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5464): [NET] android_getaddrinfo_proxy+
D/libc    ( 5464): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND),
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5464): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  967): acquireWL(8a11285): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{38e4b151: PendingIntentRecord{1d0c5db6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=976024, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{181798da: PendingIntentRecord{53ab10b com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457400517131, Int=0
,D/SmartSyncUtils( 5942): isEpsOn(), nState = 0
D/PMS     (  967): acquireWL(1570ebe8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5942 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 5942): [updateNmRange] bManual = false
,D/PMS     (  967): releaseWL(8a11285): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 5942): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5942): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 5942): SettingOnTime = 1457416800000, randomSettingOnTime = 1457414507000,
D/SmartSyncScreenOnOffTimeReceiver( 5942): SettingOffTime = 1457481600000, randomSettingOffTime = 1457484069000
D/WeatherUtility( 1221): Weather sync is On
D/SmartSyncScreenOnOffTimeReceiver( 5942): bDayMode = false
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 5942): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 5942): bNightModeTurnOffOnce = false
,D/PMS     (  967): acquireWL(26655201): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000}
,V/AlarmManager(  967): sending alarm PendingIntent{25e668a6: PendingIntentRecord{2d6152e7 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1457400517179, Int=0,
D/PMS     (  967): releaseWL(1570ebe8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 5942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncDataLinkTurnOffService( 5942): SMARTSYNC_TURN_OFF_NETWORK, current time = 1457400517195, randomOffTime = 1457484069000, newRandomOffTime = 1457484069000,
D/SmartSyncDataLinkTurnOffService( 5942): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 0, randomMobileOnTime = 1457414507000
,D/PMS     (  967): releaseWL(26655201): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/SmartSyncUtils( 5942): getMobilePolicyEnabled, result = true,
D/SmartSyncDataLinkTurnOffService( 5942): turnOffMobile bPolicyEnabled = true
,D/SmartSyncUtils( 5942): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 5942): turnOffMobile bCheckMobileData = false,
,W/art     ( 5942): Suspending all threads took: 7.830ms,
,D/LocationManagerService(  967): getProviders()=[gps, network],
D/LocationManagerService(  967): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 5942): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 5942): isCharging status = 5,
,D/SmartSyncDataLinkTurnOffService( 5942): turnOffWifi ui setting = false
,D/PMS     (  967): acquireWL(d40d3d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000}
V/AlarmManager(  967): sending alarm PendingIntent{38e4b151: PendingIntentRecord{1d0c5db6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1036024, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{30806932: PendingIntentRecord{28338eaf com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1118743, Int=0
,D/PMS     (  967): acquireWL(15663683): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1828 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1828): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1828): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1828): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1828): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1828): [NET] android_getaddrinfo_proxy+
D/libc    ( 1828): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1828): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  967): releaseWL(15663683): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(d40d3d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  967): User[0] Flushing usage stats to disk
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1828): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1828): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1828): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1828): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1828): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1828): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1828): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1828): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1828): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1828): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1828): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1828): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5464): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5464): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5464): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5464): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5464): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5464): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5464): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5464): Ignoring header User-Agent because its value was null.
,D/libc    ( 5464): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5464): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5464): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5464): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5464): [NET] android_getaddrinfo_proxy+
D/libc    ( 5464): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5464): [NET] android_getaddrinfo_proxy-, NODATA
I/RemoteViews( 1221): reapply : com.google.android.gms 6 40
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,TIME-OUT KILL (timeout was 1200000ms)
```
