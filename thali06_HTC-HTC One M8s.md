#### Test 6216742584ac8ae_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
W/BaseAppContext( 4247): Using Auth Proxy for data requests.
W/BaseAppContext( 4247): Using Auth Proxy for data requests.
W/BaseAppContext( 4247): Using Auth Proxy for data requests.
W/BaseAppContext( 4247): Using Auth Proxy for data requests.
W/BaseAppContext( 4247): Using Auth Proxy for data requests.
W/BaseAppContext( 4247): Using Auth Proxy for data requests.
I/Prism.ItemManager( 1519): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1519): loadItems() com.htc.launcher.pageview.WidgetManager@33801f0e +
I/Prism.WidgetManager( 1519): onLoadItems() +
I/GAv4    ( 5689): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5689):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5689):   adb logcat -s GAv4
W/GAv4    ( 5689): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5689): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5689): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5689): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
--------- beginning of system
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4247, uid=10024, userID:0
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4247, uid=10024, userID:0
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4247, uid=10024, userID:0
I/CheckinService( 4247): Done disabling old GoogleServicesFramework version
W/art     ( 5689): Suspending all threads took: 10.065ms
D/ChimeraCfgMgr( 4247): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4247): Module APK com.google.android.play.games already loaded
I/ActivityManager(  970): Killing 3689:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=3689
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/Prism.WidgetManager( 1519): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1519): onLoadItems() -
I/Prism.ItemManager( 1519): loadItems() com.htc.launcher.pageview.WidgetManager@33801f0e -
I/ActivityManager(  970): Recipient 3689
,D/VoldConnector(  970): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 5689): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
D/PMS     (  970): acquireWL(33c64547): PARTIAL_WAKE_LOCK  AsyncService 0x1 5500 10167 null
D/PMS     (  970): releaseWL(33c64547): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  970): acquireWL(3ac9369d): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5500 10167 null
D/PMS     (  970): releaseWL(3ac9369d): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
W/ResourcesManager( 5689): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5689): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 5689): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/UpdateIcingCorporaServi( 5356): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/System  ( 5689): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5689): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneApp( 1472): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1472): -- N1 =0
D/PhoneApp( 1472): -- N2 =0
D/PhoneApp( 1472): -- N3 =0
I/UpdateIcingCorporaServi( 5356): UpdateCorporaTask done [took 61 ms] updated apps [took 61 ms] 
D/Process (  970): killProcessQuiet, pid=5318
I/ActivityManager(  970): Killing 5318:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/cutils-trace( 5736): Error opening trace file: Permission denied (13)
I/ActivityManager(  970): Recipient 5318
D/CustomizationManager( 5736): ====startRecUseTime====
D/htc.customization.log.level( 5736):  is 
W/CustomizationLogLevel( 5736): Level value is invalid, use default level 2
D/CustomizationManager( 5736):  Read ACC file spent 0.037 (s)
D/CIDMapFileReader( 5736): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5736): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5736): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5736): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5736): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5736): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5736): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5736): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5736): Parsing tag category name = system
I/CustomizationCIDLoader( 5736): Parsing tag category name = application
I/CustomizationCIDLoader( 5736): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5736): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5736): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5736): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5736): Parsing tag category name = ACC
D/AutoSetting( 1437): service - handleMessage() stop self
I/CustomizationCIDLoader( 5736): add string-array item, value = 42507
I/CustomizationCIDLoader( 5736): add string-array item, value = 21902
I/CustomizationCIDLoader( 5736): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5736): add string-array item, value = 23420
I/CustomizationCIDLoader( 5736): add string-array item, value = 22299
I/CustomizationCIDLoader( 5736): add string-array item, value = 24002
I/CustomizationCIDLoader( 5736): add string-array item, value = 23210
I/CustomizationCIDLoader( 5736): add string-array item, value = 23205
I/CustomizationCIDLoader( 5736): add string-array item, value = 23806
I/CustomizationCIDLoader( 5736): add string-array item, value = 23430
I/CustomizationCIDLoader( 5736): add string-array item, value = 23408
I/CustomizationCIDLoader( 5736): add string-array item, value = 27205
I/CustomizationCIDLoader( 5736): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5736): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5736): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5736): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5736): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5736): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5736): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5736): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5736): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5736): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5736): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5736): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5736):  Read CID file spent 0.074 (s)
D/CustomizationManager( 5736):  All configurations done spent 0.074 (s)
D/AutoSetting( 1437): service - onDestroy() END
D/AutoSetting( 1437): service - handleMessage() quit looper
I/ActivityManager(  970): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5736 on display 0
D/PMS     (  970): acquireHCC(3ed15b0c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 970 1000 null
D/PMS     (  970): acquireHCC(299c55): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 970 1000 null
D/PMS     (  970): acquireWL(28bf1bf8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 970 1000 null
I/FeedHostManager( 1519): [onPause]
I/FeedProviderManager( 1519): onPause
I/FeedHostManager( 1519): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2c4e3fbb
I/SocialFeedProvider( 1519): +onPause
I/SocialFeedProvider( 1519): -onPause
I/AnimationUtil(  970): isHTCRecent(ThaliTest/Recent screens.)/9
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  970): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5757 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  970): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
I/TrimMemoryManager( 1519): [trimMemory] 20
,I/WebViewFactory( 5757): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 5757): Time to load native libraries: 9 ms (timestamps 6038-6047),
,I/LibraryLoader( 5757): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5757): Binding Chromium to main looper Looper (main, tid 1) {1e1e9079},
I/LibraryLoader( 5757): Expected native library version number "",actual native library version number ""
,I/chromium( 5757): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 5757): Initializing chromium process, singleProcess=true
,W/art     ( 5757): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5757): ApplicationContext is null in ApplicationStatus,
,W/chromium( 5757): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.,
,W/chromium( 5757): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 5757): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5757): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5757): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5757): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5757): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5757): Local Branch: 
I/Adreno-EGL( 5757): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5757): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5757):                  d74aa161a12b9c6fc6332151
,W/System.err(  970): java.lang.Throwable: stack dump
W/System.err(  970): 	,at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  970): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@267a99d4:true
,D/BluetoothAdapter( 5757): 552516405: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5757): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 5757): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5757): CordovaWebView is running on device made by: HTC
W/art     ( 5757): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5757): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 5757): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/FindExtension( 5757): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 5757): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@25d8d21, mServedView=org.apache.cordova.engine.SystemWebView{b5b5546 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2402d307,
,I/InputMethodManagerService(  970): Disable input method client, pid=1519,
,D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  970): Enable input method client, pid=5757
,I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
,D/PMS     (  970): releaseWL(28bf1bf8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  970): Displayed com.test.thalitest/.MainActivity: +850ms
,W/XT9_C   ( 1357): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
,I/XT9_C   ( 1357): [T9_ReleaseBuffer] Reset LDB#0,
I/XT9_C   ( 1357): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1357): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/BindingManager( 5757): Cannot call determinedVisibility() - never saw a connection for the pid: 5757
,I/HtcModeClient( 3173): handler message = 4011,
E/HtcModeClient( 3173): Check connection and retry 7 times.
,D/JsMessageQueue( 5757): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5757): JniHelper::setJavaVM(0xab3508f8), pthread_self() = -1402537480
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5757): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5757):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5757):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5757):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5757):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5757): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32730091 added. We now have 1 listener(s)
,D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757): setBluetoothMacAddress: 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5757): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5757): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"},
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb614cd added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5757): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  970): New client listening to asynchronous messages
,E/WifiTrafficPoller(  970): ADD_CLIENT: 7
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5757): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5757): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5757): setDiscoveryMode: Discovery mode BLE is supported,
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5757): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5757): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5757): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,D/Process (  970): killProcessQuiet, pid=5076,
,I/ActivityManager(  970): Killing 5076:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5076,
,I/ActivityManager(  970): Killing 5126:com.htc.sdm/u0a79 (adj 15): empty #17
,D/Process (  970): killProcessQuiet, pid=5126
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5126
,D/PMS     (  970): releaseHCC(3ed15b0c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  970): releaseHCC(299c55): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 5757): Initializing JXcore engine,
W/jxcore-log( 5757): JXcore engine is ready
,W/jxcore-log( 5757): Starting JXcore engine,
,W/jxcore-log( 5757): Platform android
W/jxcore-log( 5757): 
W/jxcore-log( 5757): Process ARCH arm
W/jxcore-log( 5757): 
,I/jxcore-log( 5757): JXcore Cordova bridge is ready!,
I/jxcore-log( 5757): 
W/jxcore-log( 5757): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5757): execute: REQUEST_ACCESS_COARSE_LOCATION,
,E/jxcore  ( 5757): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5757): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5757): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,W/PluginManager( 5757): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 61ms. Plugin should use CordovaInterface.getThreadPool().,
D/PMS     (  970): acquireWL(3f1b6b9c): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 970 1000 null
,W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1519): [onResume],
I/FeedProviderManager( 1519): onResume
I/SocialFeedProvider( 1519): +onResume
I/SocialFeedProvider( 1519): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1519): -onResume
I/ConnectivityHelper( 1519): [getCurrentConnectionType] no network connection
,D/StatusBarManagerService(  970): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
D/FindExtension( 1519): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1519): Defer allocateBuffers to drawing time,
,I/InputMethodManagerService(  970): Disable input method client, pid=5757,
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  970): Enable input method client, pid=1519
I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
W/IInputConnectionWrapper( 5757): reportFullscreenMode on inactive InputConnection
,D/PMS     (  970): releaseWL(3f1b6b9c): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/StatusBarManagerService(  970): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
D/StatusBarManagerService(  970): hiding MENU key
,D/Process (  970): killProcessQuiet, pid=5551,
I/ActivityManager(  970): Killing 5551:com.htc.task/u0a69 (adj 15): empty #17,
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  970): Recipient 5551
,W/OpenGLRenderer( 1519): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/ConfigService( 1880): onDestroy,
,D/Process (  970): killProcessQuiet, pid=5578,
I/ActivityManager(  970): Killing 5578:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5578
D/WifiService(  970): Client connection lost with reason: 4
,I/ActivityManager(  970): Waited long enough for: ServiceRecord{3dfc3ec7 u0 com.htc.musicenhancer/.EnhancerService},
,W/MediaManager( 4938): [DualLensScanUtil],	mmpCursor count is 0
,I/ActivityManager(  970): Killing 4998:com.google.android.music:main/u0a159 (adj 15): empty #17
,D/Process (  970): killProcessQuiet, pid=4998
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 4998
,D/MediaRouterService(  970): Client com.google.android.music (pid 4998): Died!,
,I/HtcModeClient( 3173): handler message = 4011,
E/HtcModeClient( 3173): Check connection and retry 8 times.
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  970): acquireWL(10c8b6a3): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{322d9da0: PendingIntentRecord{d330d59 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=85622, Int=0
,D/PMS     (  970): releaseWL(10c8b6a3): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  970): acquireWL(18a3fd1e): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{182619ff: PendingIntentRecord{3e5ef3cc android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=85983, Int=0
,D/PMS     (  970): releaseWL(18a3fd1e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    (  970): [NET] android_getaddrinfo_proxy-, NODATA
,I/HtcModeClient( 3173): handler message = 4011,
E/HtcModeClient( 3173): Check connection and retry 9 times.
,D/PMS     (  970): acquireWL(268ecd2a): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10072},
V/AlarmManager(  970): sending alarm PendingIntent{5cc571b: PendingIntentRecord{346d80b8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457489119482, Int=0
D/PMS     (  970): releaseWL(268ecd2a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/ContactMessageStore( 1472): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1472): MSG_NOTIFY_CS_TO_SYNC <<
,I/art     (  970): Explicit concurrent mark sweep GC freed 23883(1319KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 18MB/27MB, paused 1.752ms total 168.295ms,
,D/Finsky  ( 5431): [562] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5431): [1] 5.onFinished: Installation state replication succeeded.,
,I/HtcModeClient( 3173): handler message = 4011,
E/HtcModeClient( 3173): Check connection and retry 10 times.
,I/HtcModeClient( 3173): handler message = 4011,
E/HtcModeClient( 3173): Check connection and retry 11 times.
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/HtcModeClient( 3173): handler message = 4011,
E/HtcModeClient( 3173): Check connection and retry 12 times.
,I/HtcModeClient( 3173): handler message = 4011
,E/HtcModeClient( 3173): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3173): Don't start project servcice,
,D/HtcModeClient( 3173): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 3173): connectState: CONNECTION_READY = false,
D/SilentMusic( 3173): call stop
,D/HtcModeClient( 3173): close connection
W/HtcModeClient( 3173): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3173): read the terminate packet, so break,
,I/ActivityManager(  970): Killing 3173:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=3173
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 3173
,I/ActivityManager(  970): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5820 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  970): acquireWL(36280e91): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10076}
V/AlarmManager(  970): sending alarm PendingIntent{18a491f6: PendingIntentRecord{3ccf49f7 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457489139273, Int=60000
D/PMS     (  970): releaseWL(36280e91): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 5820): SMSBackupAgentService started
D/SMSBackup( 5820): Checking restore status
,D/SMSBackup( 5820): Restore complete
D/SMSBackup( 5820): cancelCheckAlarm
,D/SMSBackup( 5820): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  970): killProcessQuiet, pid=5228,
I/ActivityManager(  970): Killing 5228:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5228
,I/PMS     (  970): Going to sleep due to screen timeout (uid 1000)...
D/ActivityManager(  970): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{33ae02cd #11 A=.Prism U=0 sz=1}
W/PMS     (  970): mWirelessDisplayManager is null
W/PMS     (  970): mWirelessDisplayManager is still null
I/SensorManager(  970): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1c07648b
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  970): pid=970, uid=1000
W/PMN     (  970): goingToSleep
W/SensorService(  970): Active sensors: size = 4
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1c07648b, eanble = 0, strlen(mName) = 91
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  970): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@16cb2445
W/SensorService(  970): Listener[1] = com.htc.smartdim.sensor_eye@e854765
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/PMS     (  970): Sleeping (uid 1000)...
D/XAN-DPS (  970): prepareColorFade 1
,D/PMS     (  970): acquireWL(3d7fd782): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 970 1000 null
,W/PMN     (  970): goingToSleep done
,I/FeedHostManager( 1519): [onPause]
I/FeedProviderManager( 1519): onPause
I/FeedHostManager( 1519): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2c4e3fbb
I/SocialFeedProvider( 1519): +onPause
I/SocialFeedProvider( 1519): -onPause
,W/HtcLockScreen( 1220): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
D/AlarmManager(  970): ACTION_SCREEN_ON
,I/Adreno-EGL(  970): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  970): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  970): Build Date: 03/09/15 Mon
I/Adreno-EGL(  970): Local Branch: 
I/Adreno-EGL(  970): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  970): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  970):                  d74aa161a12b9c6fc6332151
I/ActivityManager(  970): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5842 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/PMS     (  970): releaseWL(3d7fd782): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/AlarmManager(  970): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  970): [AlarmQueuing] done recovering
I/AlarmManager(  970): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  970): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiStateMachine(  970): handleMessage: E msg.what=131167
E/WifiStateMachine(  970): processMsg: InitialState
E/WifiStateMachine(  970):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
V/SRS_Proc(  409): ParamSet string: screen_state=on
E/audio_a2dp_hw(  409): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  970):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/NetworkPolicy(  970): updateScreenOn: false
D/WifiController(  970): handleMessage: E msg.what=155650
V/NetworkPolicy(  970): updateIfacesLocked()
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0,
D/WifiStateMachine(  970): getWifiLinkLayerStats: WIFI is not enbled
W/ResourcesManager( 5842): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/WifiStateMachine(  970): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  970): handleScreenStateChanged Exit: true
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131154
E/WifiStateMachine(  970): processMsg: InitialState
,E/WifiStateMachine(  970):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131127
E/WifiStateMachine(  970): processMsg: InitialState
,E/WifiStateMachine(  970):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131129
E/WifiStateMachine(  970): processMsg: InitialState
E/WifiStateMachine(  970):  InitialState !CMD_CLEAR_BLACKLIST 0 0
,E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  970): handleMessage: X
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
I/CalendarProvider2( 5842): Created com.android.providers.calendar.CalendarAlarmManager@2ec6e072(com.htc.providers.calendar.HtcCalendarProvider@d3c7cc3)
,D/CalendarProvider2( 5842): wait start:true
,I/IntentController( 1220): receive(android.intent.action.SCREEN_ON,1,false),
,D/PMS     (  970): acquireWL(c83a94): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1794 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(3992393d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1794 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(c83a94): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(3992393d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 5842): wait end:false
,D/XAN-DPS (  970): prepareColorFade done
D/XAN-DPS (  970): setBrightness to 0
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@16cb2445,
I/DisplayManagerService(  970): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = CM32181 Light sensor
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
W/SensorService(  970): pid=970, uid=1000
,W/SensorService(  970): Active sensors: size = 3
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
,W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@16cb2445, eanble = 0, strlen(mName) = 67,
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.smartdim.sensor_eye@e854765
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1304): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1304): [EventService] mbHDMIConnect: false, mCoverOn:false
,I/ActivityManager(  970): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5871 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,V/ActivityManager(  970): Display changed displayId=0
,D/AlarmManager(  970): ACTION_SCREEN_OFF
,I/AlarmManager(  970): [AlarmQueuing] screen off now: 
I/AlarmManager(  970): [AlarmQueuing] data connection: true
I/AlarmManager(  970): [AlarmQueuing] wifi connection: false
,D/WifiDataStallTracker(  970): stopDataStallAlarm 
,E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL false Token 0
E/WifiStateMachine(  970): handleMessage: E msg.what=131167
E/WifiStateMachine(  970): processMsg: InitialState
E/WifiStateMachine(  970):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/WifiStateMachine(  970): getWifiLinkLayerStats: WIFI is not enbled
E/WifiStateMachine(  970): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  970): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  970): handleScreenStateChanged Exit: false
E/WifiStateMachine(  970): handleMessage: X
,E/WifiStateMachine(  970): handleMessage: E msg.what=131154
E/WifiStateMachine(  970): processMsg: InitialState
E/WifiStateMachine(  970):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
V/SRS_Proc(  409): ParamSet string: screen_state=off
E/audio_a2dp_hw(  409): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  970):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  970): handleMessage: X
,D/WifiController(  970): handleMessage: E msg.what=155651
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): processMsg: DefaultState
,D/WifiController(  970): handleMessage: X
D/NetworkPolicy(  970): updateScreenOn: false
V/NetworkPolicy(  970): updateIfacesLocked()
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/SensorManager( 1220): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@36625987, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  970): pid=1220, uid=10041
,W/SensorService(  970): Active sensors: size = 4
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@36625987, eanble = 1, strlen(mName) = 57,
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  970): Listener[0] = com.htc.smartdim.sensor_eye@e854765
W/SensorService(  970): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@36625987
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1304): [EventService] getTotalRam: 1842 Mb,
,W/ContextImpl( 5871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/ContactMessageStore( 1472): start background delete task...
,I/IntentController( 1220): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1472): size: 0 , 0
D/ContactMessageStore( 1472): Background delete complete
,D/PMS     (  970): acquireWL(ee2c39): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1794 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): releaseWL(ee2c39): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 5871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  970): acquireWL(23f8627e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1794 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(23f8627e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 5871): MY_DEBUG = false
,D/PMS     (  970): acquireWL(fb8482c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5871 1000 null,
,D/SmartSyncUtils( 5871): isEpsOn(), nState = 0
,I/RemoteViews( 1220): setHTCTheme(com.htc.updater,true,33751145)
,D/PMS     (  970): releaseWL(fb8482c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/RemoteViews( 1220): apply : com.htc.updater 0 18 0 36,
D/SurfaceControl(  970): Excessive delay in setPowerMode(): 284ms,
W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  970): Setting HAL interactive mode to false
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  970): Setting HAL interactive mode to false done
D/PMS     (  970): Setting HAL auto-suspend mode to true
D/PMS     (  970): Setting HAL auto-suspend mode done
,I/InputMethodManagerService(  970): screenObserver, isScreenOn=false
,D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
D/SmartDim(  970): Init customizeScreenOffDelayClass error
I/InputMethodManagerService(  970): Disable input method client, pid=1519
D/HABCtrl (  970): TPE algorithm. remove timeout.
D/PMS     (  970): OOBE c monitor 11
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,D/NfcService( 1481): ScreenObserver: OFF,
D/NfcService( 1481): applyRouting - 0
I/InputManager(  970): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
I/IntentController( 1220): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  970): acquireWL(157c52f5): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1481 1027 null
,D/PMS     (  970): acquireWL(25b4288a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
,I/BatteryService(  970): n_update end
D/NfcService( 1481): applyRouting -2
D/PMS     (  970): releaseWL(25b4288a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NfcService( 1481): applyRouting
D/NfcService( 1481): Ignore this applyRouting...
D/HtcPowerSaver(  970): updateBatteryInfo
,D/PMS     (  970): releaseWL(157c52f5): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  970): plugged=true pluggin=true
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,W/ContextImpl( 5871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
,D/PowerUI ( 1220): closing low battery warning: level=100
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/SmartSyncUtils( 5871): isEpsOn(), nState = 0,
D/SmartSyncUtils( 5871): isEpsOn(), nState = 0
,W/ContextImpl( 5871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@e854765
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = Accelerometer Sensor
,I/ClockController( 1220): stop clock update:screen off
,W/SensorService(  970): pid=970, uid=1000
,W/SensorService(  970): Active sensors: size = 3
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
,W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@e854765, eanble = 0, strlen(mName) = 35
E/ActivityThread(  970): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@279e5c3a that was originally registered here. Are you missing a call to unregisterReceiver()?,
E/ActivityThread(  970): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@279e5c3a that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  970): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  970): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  970): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  970): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  970): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  970): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  970): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  970): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  970): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  970): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  970): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  970): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  970): 	at java.lang.reflect.Method.invoke(Native Method)
,E/ActivityThread(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@36625987
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = CM36686 Proximity sensor
I/PowerUsageList:PowerUsageHelper( 5871): PowerProfile::POWER_SCREEN_FULL = 154.8
I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 2
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@e854765, eanble = 0, strlen(mName) = 35
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@36625987
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  970): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@e854765
I/ActivityManager(  970): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5904 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/PowerUsageList:BatterySipperExt( 5871): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 5871): calcPower(), no data
,D/PowerUsageList:PowerUsageHelper( 5871): MY_DEBUG = false
,D/SmartSyncUtils( 5871): getMobilePolicyEnabled, result = true
,D/Process (  970): killProcessQuiet, pid=5262
I/ActivityManager(  970): Killing 5262:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/WifiService(  970): New client listening to asynchronous messages
E/WifiTrafficPoller(  970): ADD_CLIENT: 7
,I/ActivityManager(  970): Recipient 5262
,I/ActivityManager(  970): Killing 5383:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,D/Process (  970): killProcessQuiet, pid=5383
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5383
,I/CalendarProvider2( 5842): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 5842): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  970): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5928 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  970): Killing 5635:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=5635
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5635
,W/ResourcesManager( 5928): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 5928): onCreate
,D/ProviderChangeReceiver( 5928): ---------------------------------------------------
,D/ProviderChangeReceiver( 5928): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  970): killProcessQuiet, pid=5657,
I/ActivityManager(  970): Killing 5657:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 5928): start to updateAlertNotification!
,D/PMS     (  970): releaseWL(11785df9): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  970): Recipient 5657
,D/HtcAlertService( 5928): No fired or scheduled alerts
,D/HtcAlertUtils( 5928): -- cancelReminderNotification --
,D/HtcAlertUtils( 5928): broadcastExistReminder!
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcUPManager( 1220): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  970): acquireWL(288c2971): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024}
,V/AlarmManager(  970): sending alarm PendingIntent{36b44356: PendingIntentRecord{fed9ba3 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=124397, Int=0
,D/PMS     (  970): acquireWL(21c90fd7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
V/AlarmManager(  970): sending alarm PendingIntent{3cb970c4: PendingIntentRecord{16e8ebad android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457489156254, Int=0
D/libc    ( 1880): [NET] android_getaddrinfofornet-, err=8
D/PMS     (  970): acquireWL(2dc93ee2): PARTIAL_WAKE_LOCK  *backup* 0x1 970 1000 null
D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/PMS     (  970): releaseWL(288c2971): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    ( 1880): [NET] android_getaddrinfofornet-, pass to proxy
W/BackupManagerService(  970): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
D/libc    ( 1880): [NET] android_getaddrinfo_proxy+
D/libc    ( 1880): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
E/BackupManagerService(  970): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/libc    ( 1880): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  970): releaseWL(2dc93ee2): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  970): releaseWL(21c90fd7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  970): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5953 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5953): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/Babel_SMS( 5953): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 5953): MmsConfig.loadMmsSettings
,I/ActivityManager(  970): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=5982 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5953, uid=10112, userID:0
,D/Process (  970): killProcessQuiet, pid=5101
I/ActivityManager(  970): Killing 5101:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/HtcWrapAdjustableCursorFactory( 5982): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 5982): onCreate,
,I/ActivityManager(  970): Recipient 5101,
,V/GetPrviateResource( 5982): GetPrviateResource
,V/GetPrviateResource( 5982): GetPrviateResource
,D/MmsCustomizationProvider( 5982): query uri: content://htc-mms-customization/mms-ua/ua_string,
,D/MessageCustFlag( 5982): sense_version=6.0,
D/BTAccessoryUtil( 5982): createReceiver
,D/BTAccessoryUtil( 5982): registerReceiver return intent = null,
,D/MessageCustFlag( 5982): sku_id=118,
,D/HtcBuildUtils( 5982): getRATByHtcTelephonyCapability:1
,W/SystemReader( 5982): Cannot find qct_8960_interface, use default value instead
,D/MmsCustomizationProvider( 5982): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 5953): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 5953): MmsConfig.loadFromDatabase
W/Settings( 5953): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel_SMS( 5953): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5953): MmsConfig.loadFromResources
,E/Babel_SMS( 5953): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_Crash( 5953): startup - clean
,I/Babel_SMS( 5953): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel   ( 5953): deleted: false for 0,
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5953, uid=10112, userID:0,
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5953, uid=10112, userID:0
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5953, uid=10112, userID:0
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5953, uid=10112, userID:0
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5953, uid=10112, userID:0
,W/VideoCapabilities( 5953): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5953): Unsupported mime video/x-ms-wmv,
,W/Utils   ( 5953): could not parse size range '64x64-1920X1080',
,W/AudioCapabilities( 5953): Unsupported mime audio/qcelp,
,W/AudioCapabilities( 5953): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5953): Unsupported mime audio/qcelp,
,W/VideoCapabilities( 5953): Unsupported mime video/x-ms-wmv,
,I/VideoCapabilities( 5953): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 5953): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5953): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5953): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5953): Unrecognized profile 2130706433 for video/avc,
,I/ActivityManager(  970): Killing 5406:com.android.settings/1000 (adj 15): empty #17,
D/Process (  970): killProcessQuiet, pid=5406
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5406,
,I/ActivityManager(  970): Killing 5472:com.google.android.gms:car/u0a24 (adj 15): empty #18
,D/Process (  970): killProcessQuiet, pid=5472
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5472
,I/vclib   ( 5953): onServiceConnected,
,W/Babel   ( 5953): Attempted to change video mute state without an active call.
,D/Messaging( 5982): supportCMAS(SIE)/init? false/true
D/MmsConfig( 5982): networkCode: 
,D/MessageCustFlag( 5982): sku_id=118
,D/MmsConfig( 5982): SIE smsPri: null
,D/MmsConfig( 5982): networkCode: 
,D/MmsConfig( 5982): packageName: com.htc.vvm.att does not exist
,D/Messaging( 5982): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 5982): startAsyncQueryReports ---
,D/TelephUtils( 1472): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 79
,D/MmsSmsV2Provider( 1472):  slotId = -1000
D/MmsSmsV2Provider( 1472): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/MmsAsyncWorkHandler( 5982): 
D/MmsAsyncWorkHandler( 5982): HM tk = 20001
,D/ReportIndicatorCache( 5982): MSG_QUERY_REPORTS >>
D/SettingsManager( 5982): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@1e1e9079
,D/TelephUtils( 1472): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1472): sku_id=118
,D/DraftCache( 5982): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5982): [DraftCache/1] refresh
,D/DraftCache( 5982): [DraftCache/146] DraftCache.constructor
,D/DraftCache( 5982): [DraftCache/146] refresh
,D/TelephUtils( 1472): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 79
D/MmsSmsV2Provider( 1472):  slotId = -1000
D/MmsSmsV2Provider( 1472): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/DraftCache( 5982): [DraftCache/146] rebuildCache
,D/TelephUtils( 1472): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1472):  slotId = -1000
D/MmsSmsV2Provider( 1472): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 5982): mNeedToUpdateDate2: false
,D/MmsConfig( 5982): networkCode: 
,D/TelephUtils( 1472): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 79
,D/MmsSmsV2Provider( 1472):  slotId = -1000
D/MmsSmsV2Provider( 1472): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,I/Messaging( 5982): mccmnc> 
,D/Messaging( 5982): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,W/ContentService(  970): Observer android.database.IContentObserver$Stub$Proxy@109ea60 is already registered.
,W/ContentService(  970): Observer android.database.IContentObserver$Stub$Proxy@1ce23b19 is already registered.
,D/Messaging( 5982): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1472): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/Jerry   ( 1472): URI_DRAFT
,D/DraftCache( 5982): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 5982): [DraftCache/146] rebuildCache time: 25
D/DraftCache( 5982): [DraftCache/146] rebuildCache
D/PhoneStorageUtil( 5982): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5982): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5982): createReceiver
D/MessageCustFlag( 5982): sense_version=6.0
,D/Jerry   ( 5982): start to preload cursor >>>>>>>
D/TelephUtils( 1472): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 79
D/Jerry   ( 1472): URI_DRAFT
,D/TelephUtils( 1472): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
,V/MmsProvider( 1472): Update uri=content://mms, match=0
V/MmsProvider( 1472): selection=st=129 AND m_type!=134
,D/Messaging( 5982): Reset downloading state: 0
,V/MmsSystemEventReceiver( 5982): TransactionService is going to be woken up.
,D/DraftCache( 5982): hasDraft() = false mNeedNotifyChange = false,
D/DraftCache( 5982): [DraftCache/146] rebuildCache time: 2
D/MmsAsyncWorkHandler( 5982): 
D/MmsAsyncWorkHandler( 5982): HM tk = 20002
D/TelephUtils( 1472): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1472):  slotId = -1000
,V/TransactionService( 5982): 1-Creating TransactionService
,D/TelephUtils( 1472): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 79,
D/AccFlag ( 1472): sku_id=118
,D/Messaging( 5982): ViewCache CreatePreload
,D/Messaging( 5982): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1472): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1472): sku_id=118
,D/Cust_MMSMS( 5982): _has_set_default_values_2=true
,V/TransactionService( 5982): onStartCommand: 1
,D/MmsSystemEventReceiver( 5982): unRegisterForConnectionStateChanges
,V/TransactionService( 5982): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5982): Loading previous transactions.
,D/MsgPreferenceUtils( 5982): def_index: 0
D/MsgPreferenceUtils( 5982): globalIndex = 1
D/TelephUtils( 1472): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 79
D/AccFlag ( 1472): device_type: 1
,D/MsgPreferenceUtils( 5982): phone state: true
D/MsgPreferenceUtils( 5982): sd state: false,
D/MsgPreferenceUtils( 5982): vIndex = 0
D/TransactionService( 5982): Force clearing mTransactionList
D/TransactionService( 5982): Force set service start id to 1
V/TransactionService( 5982): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5982): unRegisterForConnectionStateChanges
D/TransactionService( 5982): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 5982): Destroying TransactionService
,V/TransactionService( 5982): 4-Handling incoming message: { when=-1ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  970): acquireWL(2a41eafd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{1c1e4fe3: PendingIntentRecord{21d15de0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=129353, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{182619ff: PendingIntentRecord{3e5ef3cc android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145991, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{105853f2: PendingIntentRecord{3e5baa43 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143882, Int=0
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    (  970): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  970): releaseWL(2a41eafd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1220): Weather sync is On
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  970): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/ContactMessageStore( 1472): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1472): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  970): acquireWL(2dba18c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(2dba18c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): BroadcastReceiver::onReceive-,
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1472): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5
,D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1437): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@12ed24f5
,D/Process (  970): killProcessQuiet, pid=4594
I/ActivityManager(  970): Killing 4594:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 4594
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  970): acquireWL(104739f9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{1c1e4fe3: PendingIntentRecord{21d15de0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=189354, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{3193bd3e: PendingIntentRecord{3b84a79f android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=196174, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{182619ff: PendingIntentRecord{3e5ef3cc android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=206004, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{68800ec: PendingIntentRecord{1ab87cb5 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=187042, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{3f8a6f4a: PendingIntentRecord{fed9ba3 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=230842, Int=0
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    (  970): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  970): acquireWL(19161ebb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(19161ebb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(2b6a3fd8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1880): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1880): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1880): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1880): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1880): [NET] android_getaddrinfo_proxy-, NODATA,
D/PMS     (  970): releaseWL(104739f9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1220): Weather sync is On
,W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/PMS     (  970): releaseWL(2b6a3fd8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(14c12f31): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(14c12f31): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  970): updateBatteryInfo
D/PowerUI ( 1220): closing low battery warning: level=100
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X,
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  970): << updateStatus,
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  970): acquireWL(23883616): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(23883616): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  970): acquireWL(c7deb97): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
,I/BatteryService(  970): n_update end,
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): releaseWL(c7deb97): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  970): updateBatteryInfo
D/WifiController(  970): handleMessage: E msg.what=155652
D/PMS     (  970): runPSCheck
D/WifiController(  970): processMsg: ApStaDisabledState
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: X
D/WifiController(  970): battery changed pluggedType: 2
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  970): << updateStatus
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3,
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1880): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1880): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1880): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1880): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActionCombine( 1880): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,W/ResourcesManager( 1220): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1220): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/GLSActivity( 1880): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1880): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1880): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1880): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
,W/GLSActivity( 1880): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1880): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1880): 	at android.os.Binder.execTransact(Binder.java:454)
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5431): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5431): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5431): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5431): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1220): apply : com.google.android.gms 0 12 5 40,
,W/System  ( 5431): Ignoring header User-Agent because its value was null.
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5431): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5431): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5431): [NET] android_getaddrinfo_proxy+
D/libc    ( 5431): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5431): [NET] android_getaddrinfo_proxy-, NODATA
,I/art     (  970): Explicit concurrent mark sweep GC freed 26783(1515KB) AllocSpace objects, 3(516KB) LOS objects, 33% free, 18MB/27MB, paused 1.570ms total 163.405ms
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  970): acquireWL(154b46a1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  970): n_update end
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): releaseWL(154b46a1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
,D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5
I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(21850c6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
,V/AlarmManager(  970): sending alarm PendingIntent{1c1e4fe3: PendingIntentRecord{21d15de0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=249354, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{39b853b4: PendingIntentRecord{2e34abdd com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457489372601, Int=0,
,V/AlarmManager(  970): sending alarm PendingIntent{2b8b352: PendingIntentRecord{fed9ba3 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=441319, Int=0
,D/PMS     (  970): acquireWL(32b38623): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1880): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1880): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1880): [NET] android_getaddrinfo_proxy+
D/libc    ( 1880): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1880): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  970): releaseWL(32b38623): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): releaseWL(21850c6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1220): Weather sync is On
,W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  970): acquireWL(2b60f720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(2b60f720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): runPSCheck
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  970): Checking...
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  970): >> updateStatus
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  970): << updateStatus
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  970): acquireWL(65528d9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(65528d9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
,D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  970): updateBatteryInfo
D/WifiController(  970): processMsg: ApStaDisabledState
D/PMS     (  970): runPSCheck
D/WifiController(  970): processMsg: DefaultState
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): >> updateStatus
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  970): battery changed pluggedType: 2
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(158ab29e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(158ab29e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  970): runPSCheck
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): onReceive BATTERY_CHANGED
,I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1472): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1472): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1472): sku_id=118
,D/ContactMessageStore( 1472): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1472): start background delete task...
,D/ContactMessageStore( 1472): size: 0 , 0
,D/ContactMessageStore( 1472): Background delete complete
,D/PMS     (  970): acquireWL(32ae617f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
,I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(32ae617f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: ApStaDisabledState,
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DefaultState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): << updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1880): Explicit concurrent mark sweep GC freed 17929(1009KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 978us total 54.454ms
,I/GLSUser ( 1880): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1880): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1880): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1880): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1880): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1880): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1880): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1880): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1880): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1880): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1880): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1220): reapply : com.google.android.gms 4 40
E/PlayEventLogger( 5431): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5431): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5431): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5431): Ignoring header User-Agent because its value was null.
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/libc    ( 5431): [NET] android_getaddrinfofornet-, err=8
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5431): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5431): [NET] android_getaddrinfo_proxy+
D/libc    ( 5431): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5431): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  970): acquireWL(8c4fa49): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(8c4fa49): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
,D/HtcPowerSaver(  970): Checking...
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): >> updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(1d96ff4e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(1d96ff4e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): updateBatteryInfo
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(1f68a86f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
,V/AlarmManager(  970): sending alarm PendingIntent{1c1e4fe3: PendingIntentRecord{21d15de0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=489354, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{322d9da0: PendingIntentRecord{d330d59 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805653, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{37bbb97c: PendingIntentRecord{fed9ba3 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=862212, Int=0
,I/ActivityManager(  970): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6049 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  970): sending alarm PendingIntent{1f59f205: PendingIntentRecord{35e7c25a com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457489680276, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{3c815c8b: PendingIntentRecord{3402ef05 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457489992908, Int=0
D/PMS     (  970): acquireWL(bc8f168): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1880): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1880): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1880): [NET] android_getaddrinfo_proxy+
D/libc    ( 1880): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1880): [NET] android_getaddrinfo_proxy-, NODATA,
W/ContextImpl( 5871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  970): releaseWL(bc8f168): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
D/WeatherUtility( 1220): Weather sync is On
D/PMS     (  970): releaseWL(1f68a86f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 5871): MY_DEBUG = false
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
I/art     (  416): Explicit concurrent mark sweep GC freed 8682(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 591us total 47.166ms
,D/PowerUsageService( 5871): repeat time = 1457490892987
,I/art     (  416): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 434us total 22.577ms,
,I/art     (  416): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 237us total 20.483ms
,I/PowerUsageList:PowerUsageHelper( 5871): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5871): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 5871): calcPower(), no data,
,E/cutils-trace( 6073): Error opening trace file: Permission denied (13),
I/dex2oat ( 6073): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6073): dex2oat: override thread count:4,
,I/dex2oat ( 6073): dex2oat took 556.219ms (threads: 4),
,I/PushClient( 6049): ApplicationMonitor {2ae0bca}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6049): ApplicationMonitor {2ae0bca}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6049): ApplicationMonitor {2ae0bca}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6049): ApplicationMonitor {2ae0bca}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6049): ApplicationMonitor {2ae0bca}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6049): ApplicationMonitor {2ae0bca}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6049): ApplicationMonitor {2ae0bca}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6049): ApplicationMonitor {2ae0bca}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6049): ApplicationMonitor {2ae0bca}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6049): PnsModel {20eebb35}: update(): Update registration caused by: alarm,
,I/PushClient( 6049): PnsConfigModel {186af270}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6049): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6049): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6049): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6049): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  970): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6081 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 6081): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6081 dbg=false s=true,
,I/DeviceManagement( 6081): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6081): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6081): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6081): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6081): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2fe0221f] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6081): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6081): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6081): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6081): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6081): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6081): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6081): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6081): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2fe0221f],
,I/DeviceManagement( 6081): WorkflowService: Stopping workflow service,
,D/Process (  970): killProcessQuiet, pid=5689,
,I/ActivityManager(  970): Killing 5689:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5689,
,I/PushClient( 6049): PnsModel {20eebb35}: update(): Start updating since the registration has expired.,
,W/PushClient( 6049): GCMRegistrator {156f98a3}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.,
W/PushClient( 6049):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
W/PushClient( 6049):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
W/PushClient( 6049):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
W/PushClient( 6049):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
W/PushClient( 6049):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
W/PushClient( 6049):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/PushClient( 6049):   	at android.os.Handler.dispatchMessage(Handler.java:102),
W/PushClient( 6049):   	at android.os.Looper.loop(Looper.java:155)
W/PushClient( 6049):   	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PushClient( 6049):   
,D/GCM     ( 1880): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 1880): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 1880): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1880): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1880): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7,
D/libc    ( 1880): [NET] android_getaddrinfo_proxy-, NODATA
,E/PushClient( 6049): PnsModel {20eebb35}: update(): com.htc.lib1.cs.push.exception.UpdateRegistrationFailedException: SERVICE_NOT_AVAILABLE,
E/PushClient( 6049):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:198)
E/PushClient( 6049):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
E/PushClient( 6049):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
E/PushClient( 6049):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PushClient( 6049):   	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PushClient( 6049):   	at android.os.Looper.loop(Looper.java:155)
E/PushClient( 6049):   	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PushClient( 6049):   Caused by: java.io.IOException: SERVICE_NOT_AVAILABLE
E/PushClient( 6049):   	at com.google.android.gms.gcm.GoogleCloudMessaging.register(Unknown Source)
E/PushClient( 6049):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.registerGCM(GCMRegistrator.java:301)
E/PushClient( 6049):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:196)
E/PushClient( 6049):   	... 6 more
E/PushClient( 6049):   
,I/PushClient( 6049): CentralClientRetryPolicy {1296b940}: scheduleUpdateRetry(): Waiting for network connectivity...,
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.htc.cs.pns, clsName=com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver, state=1, flag=1, pid=6049, uid=10071, userID:0,
,D/Process (  970): killProcessQuiet, pid=4839
I/ActivityManager(  970): Killing 4839:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 4839,
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1880): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1880): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1880): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1880): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1880): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1880): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1880): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1880): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1880): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1880): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1880): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5431): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5431): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5431): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5431): Ignoring header User-Agent because its value was null.
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5431): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5431): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 5431): [NET] android_getaddrinfo_proxy+
D/libc    ( 5431): [NET] android_getaddrinfo_proxy get netid:0
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5431): [NET] android_getaddrinfo_proxy-, NODATA
I/RemoteViews( 1220): reapply : com.google.android.gms 4 40
,D/PMS     (  970): acquireWL(168ffc6b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
,V/AlarmManager(  970): sending alarm PendingIntent{1c1e4fe3: PendingIntentRecord{21d15de0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=969354, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{1ff943c8: PendingIntentRecord{478fc61 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457490044648, Int=0
,D/SmartSyncUtils( 5871): isEpsOn(), nState = 0,
,D/PMS     (  970): acquireWL(186f3386): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5871 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 5871): [updateNmRange] bManual = false,
D/SmartSyncScreenOnOffTimeReceiver( 5871): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5871): AlarmOnTime = -1
D/PMS     (  970): releaseWL(168ffc6b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 5871): SettingOnTime = 1457503200000, randomSettingOnTime = 1457502226000
D/SmartSyncScreenOnOffTimeReceiver( 5871): SettingOffTime = 1457568000000, randomSettingOffTime = 1457573997000
,D/WeatherUtility( 1220): Weather sync is On
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
D/SmartSyncScreenOnOffTimeReceiver( 5871): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5871): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 5871): bNightModeTurnOffOnce = false
,D/PMS     (  970): acquireWL(28aff447): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{2542d474: PendingIntentRecord{3fe7fd9d com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1457490044697, Int=0
D/PMS     (  970): releaseWL(186f3386): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 5871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncDataLinkTurnOffService( 5871): SMARTSYNC_TURN_OFF_NETWORK, current time = 1457490044713, randomOffTime = 1457573997000, newRandomOffTime = 1457573997000,
D/SmartSyncDataLinkTurnOffService( 5871): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 0, randomMobileOnTime = 1457502226000
,D/PMS     (  970): releaseWL(28aff447): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/SmartSyncUtils( 5871): getMobilePolicyEnabled, result = true
D/SmartSyncDataLinkTurnOffService( 5871): turnOffMobile bPolicyEnabled = true
,D/SmartSyncUtils( 5871): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 5871): turnOffMobile bCheckMobileData = false
,D/LocationManagerService(  970): getProviders()=[gps, network]
D/LocationManagerService(  970): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  970): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 5871): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 5871): isCharging status = 5
,D/SmartSyncDataLinkTurnOffService( 5871): turnOffWifi ui setting = false,
,D/PMS     (  970): acquireWL(fed8de3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false),
I/BatteryService(  970): n_update end
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): releaseWL(fed8de3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  970): updateBatteryInfo
D/WifiController(  970): handleMessage: E msg.what=155652
D/PMS     (  970): runPSCheck
D/WifiController(  970): processMsg: ApStaDisabledState
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): acquireWL(9f2c3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  970): n_update end
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  970): releaseWL(9f2c3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: ApStaDisabledState
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  970): User[0] Flushing usage stats to disk
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1880): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1880): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1880): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1880): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1880): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1880): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1880): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1880): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1880): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1880): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1880): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/PlayEventLogger( 5431): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5431): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5431): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5431): Ignoring header User-Agent because its value was null.
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5431): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5431): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5431): [NET] android_getaddrinfo_proxy+
D/libc    ( 5431): [NET] android_getaddrinfo_proxy get netid:0
I/RemoteViews( 1220): reapply : com.google.android.gms 3 40,
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5431): [NET] android_getaddrinfo_proxy-, NODATA
,TIME-OUT KILL (timeout was 1200000ms)
```
