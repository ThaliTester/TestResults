#### Test 50388019f33194e_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
E/SMD     (  292): DCD ON
D/AndroidRuntime( 6102): 
D/AndroidRuntime( 6102): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6102): CheckJNI is OFF
D/AndroidRuntime( 6102): readGMSProperty: start
D/AndroidRuntime( 6102): readGMSProperty: already setted!!
D/AndroidRuntime( 6102): readGMSProperty: end
D/AndroidRuntime( 6102): addProductProperty: start
E/AffinityControl( 6102): AffinityControl: registerfunction enter
D/AndroidRuntime( 6102): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  756): inState():  stateMachine is null !!
I/PersonaManagerService(  756): PersonaId don't exist
I/ActivityManager(  756): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  756): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  756): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager(  756): mDVFSHelper.acquire()
I/SurfaceFlinger(  254): id=9 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger(  254): id=10 createSurf (16x16),-1 flag=20004, EimLayer
D/FocusedStackFrame(  756): Set to : 0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
I/TemperatureHumiditySensor(  756): Accuracy has been changed to 3
E/Zygote  ( 6117): MountEmulatedStorage()
E/Zygote  ( 6117): v2
I/libpersona( 6117): KNOX_SDCARD checking this for 10256
I/libpersona( 6117): KNOX_SDCARD not a persona
I/ActivityManager(  756): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6117 uid=10256 gids={50256, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 6102): Shutting down VM
I/SELinux ( 6117): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6117): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6117): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon(  756): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  756): setMouseCustomIcon IconType is same.101
D/PointerIcon(  756): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  756): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider( 6117): TimaSignature is unavailable
D/ActivityThread( 6117): Added TimaKeyStore provider
V/WindowOrientationListener(  756): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  756): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  756): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  756): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  756): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  756): Display changed displayId=0
D/SurfaceWidgetView( 1449): destroyHardwareResources():305403449
D/ConnectivityService(  756): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6117): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1776): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1449): updateVisibility : ActivityRecord{3a9a0c26 token=android.os.BinderProxy@3cc4c879 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1449): onTrimMemory. Level: 20
,I/WebViewFactory( 6117): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 6117): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 6117): Loading: webviewchromium
I/LibraryLoader( 6117): Time to load native libraries: 5 ms (timestamps 2072-2077)
I/LibraryLoader( 6117): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6117): Binding Chromium to main looper Looper (main, tid 1) {116c3bda}
I/LibraryLoader( 6117): Expected native library version number "",actual native library version number ""
I/chromium( 6117): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6117): Initializing chromium process, renderers=0
W/art     ( 6117): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6117): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6117): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6117): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6117): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
D/BluetoothAdapter( 6117): 166598667: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6117): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6117): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6117): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6117): Local Branch: mybranch5813579
I/Adreno-EGL( 6117): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6117): Local Patches: NONE
I/Adreno-EGL( 6117): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/chromium( 6117): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6117): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6117): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6117): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6117): CordovaWebView is running on device made by: samsung
W/art     ( 6117): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6117): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager(  756): Activity pause timeout for ActivityRecord{38409440 u0 com.example.hello/.MainActivity t2}
D/Activity( 6117): performCreate Call secproduct feature valuefalse
D/Activity( 6117): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 6117): Render dirty regions requested: true
D/Atlas   ( 6117): Validating map...
D/ActivityManager(  756): post active user change for 0
D/KnoxTimeoutHandler(  756): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  756): handleActiveUserChange for user 0
V/ActivityThread( 6117): updateVisibility : ActivityRecord{23dcba18 token=android.os.BinderProxy@cbb4f8a {com.example.hello/com.example.hello.MainActivity}} show : true
I/SurfaceFlinger(  254): id=11 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  756): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  756): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  756): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  756): setMouseCustomIcon IconType is same.101
D/PointerIcon(  756): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
I/OpenGLRenderer( 6117): Initialized EGL, version 1.4
D/PointerIcon(  756): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6117): HWUI protection enabled for context ,  &this =0xa1853060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6117): Enabling debug mode 0
D/InputMethodManagerService(  756): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  756): mDVFSHelper.release()
I/Timeline(  756): Timeline: Activity_windows_visible id: ActivityRecord{38409440 u0 com.example.hello/.MainActivity t2} time:72646
W/IInputConnectionWrapper( 6117): showStatusIcon on inactive InputConnection
I/Timeline( 6117): Timeline: Activity_idle id: android.os.BinderProxy@cbb4f8a time:72664
I/SamsungIME( 1731): getCurrentCandidateView
W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/chromium( 6117): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 6117): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/SamsungIME( 1731): Dismiss ExpandCandiate
I/chromium( 6117): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6117): 
D/JsMessageQueue( 6117): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1731): getDebugLevel  : 0x4f4c
I/SamsungIME( 1731): getDebugLevel  : 0x4f4c
I/SamsungIME( 1731): KeybaordView init() : load resources
I/SamsungIME( 1731): getCurrentKeyboard
I/SamsungIME( 1731): getTextKeyboard
D/SamsungIME( 1731): [SwiftkeyWrapper] currentLangauge : 1701729619
D/jxcore_app_log( 6117): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1355727488
D/JX-Cordova( 6117): jxcore cordova android initializing
W/jxcore-log( 6117): Initializing JXcore engine
W/jxcore-log( 6117): JXcore engine is ready
W/jxcore-log( 6117): Starting JXcore engine
E/auditd  ( 1807): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  756): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  756): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
E/Zygote  ( 6188): MountEmulatedStorage()
E/Zygote  ( 6188): v2
I/libpersona( 6188): KNOX_SDCARD checking this for 1000
I/libpersona( 6188): KNOX_SDCARD not a persona
I/ActivityManager(  756): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6188 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6188): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/jxcore-log( 6117): Platform android
W/jxcore-log( 6117): 
W/jxcore-log( 6117): Process ARCH arm
W/jxcore-log( 6117): 
I/jxcore-log( 6117): JXcore Cordova bridge is ready!
I/jxcore-log( 6117): 
W/jxcore-log( 6117): JXcore engine is started
D/TimaKeyStoreProvider( 6188): TimaSignature is unavailable
D/ActivityThread( 6188): Added TimaKeyStore provider
D/ResourcesManager( 6188): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
D/SecurityLogAgent( 6188):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
D/SecurityLogAgent( 6188):  SeDenialReceiver : File path = null
I/ActivityManager(  756): Killing 5182:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
E/jxcore-log( 6117): >> samsung-SM-N9005
E/jxcore-log( 6117): 
I/jxcore-log( 6117): Total memory 2971471872
I/jxcore-log( 6117): 
I/jxcore-log( 6117): Free memory 431931392
I/jxcore-log( 6117): 
I/jxcore-log( 6117): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6117): 
I/jxcore-log( 6117): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6117): 
I/jxcore-log( 6117): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6117): 
I/jxcore-log( 6117): Size 1080 1920
I/jxcore-log( 6117): 
I/jxcore-log( 6117): Screen Brightness 162
I/jxcore-log( 6117): 
E/jxcore-log( 6117): Dummy Error Log.
E/jxcore-log( 6117): 
D/SamsungIME( 1731): [SwiftkeyWrapper] currentLangauge : 1701729619
I/jxcore-log( 6117): getBuffer is called!!!!
I/jxcore-log( 6117): 
,E/SMD     (  292): DCD ON
,E/Watchdog(  756): !@Sync 2
,V/AlarmManager(  756): waitForAlarm result :8
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,I/art     ( 1751): Explicit concurrent mark sweep GC freed 35340(2MB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 21MB/35MB, paused 3.624ms total 124.290ms
,I/ServiceManager(  340): Waiting for service AtCmdFwd...
,D/BluetoothAdapter( 6117): disable()
,E/BluetoothManagerService(  756): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 6117): packageName : com.example.hello
,D/SecContentProvider(  756): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  756): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  756): mCursor = null
,D/WifiService(  756): setWifiEnabled: false pid=6117, uid=10256
,D/SettingsProvider(  756): name = wifi_on
,I/jxcore-log( 6117): ****TEST TOOK:  5070  ms ****
I/jxcore-log( 6117): 
,I/jxcore-log( 6117): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6117): 
,D/AndroidRuntime( 6241): 
D/AndroidRuntime( 6241): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6241): CheckJNI is OFF
,D/AndroidRuntime( 6241): readGMSProperty: start
,D/AndroidRuntime( 6241): readGMSProperty: already setted!!
,D/AndroidRuntime( 6241): readGMSProperty: end
D/AndroidRuntime( 6241): addProductProperty: start
,E/AffinityControl( 6241): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6241): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  756): START PACKAGE DELETE: observer{372195355}
D/PackageManager(  756): pkg{<packageName>}
D/PackageManager(  756): user{0}
D/PackageManager(  756): caller{2000}
D/PackageManager(  756): flags{3}
D/PersonaManagerService(  756): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  756): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  756): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  756): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  756): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  756): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  756): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  756): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  756): getApplicationUninstallationEnabled
D/ApplicationPolicy(  756): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  756): !@killApplicatoin: 10256, uninstall pkg
,I/ActivityManager(  756): Force stopping com.example.hello appid=10256 user=-1: uninstall pkg
,I/ActivityManager(  756): Killing 6117:com.example.hello/u0a256 (adj 0): stop com.example.hello
,W/PackageSettings(  756): Skipping PackageSetting{165a2487 com.test.thalitest/10264} due to missing metadata
,I/WindowState(  756): WIN DEATH: Window{2f9e4846 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (-2/8)
I/SurfaceFlinger(  254): id=11 Removed NainActivit (-2/8)
,D/PointerIcon(  756): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  756): setMouseCustomIcon IconType is same.101
D/PointerIcon(  756): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  756): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager(  756):   Force finishing activity ActivityRecord{38409440 u0 com.example.hello/.MainActivity t2}
,D/FocusedStackFrame(  756): Set to : 0
,W/ActivityManager(  756): Spurious death for ProcessRecord{788b5b8 6117:com.example.hello/u0a256}, curProc for 6117: null
,I/ActivityManager(  756): Force stopping com.example.hello appid=10256 user=0: pkg removed
,I/PowerManagerService(  756): [PWL] Off : 30s ago
,I/ActivityManager(  756):   Force finishing activity ActivityRecord{38409440 u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager(  756): Duplicate finish request for ActivityRecord{38409440 u0 com.example.hello/.MainActivity t2 f}
,I/art     ( 4248): Explicit concurrent mark sweep GC freed 6352(408KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 16MB/21MB, paused 616us total 35.225ms
,I/ServiceManager(  340): Waiting for service AtCmdFwd...
,I/art     ( 5882): Explicit concurrent mark sweep GC freed 2150(127KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 572us total 63.103ms
,D/SSRM:n  (  756): SIOP:: AP = 330, PST = 388, CUR = 450
,D/ConnectivityService(  756): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1449): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1449): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1449): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/GeofencerStateMachine( 1480): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1731): mOCRHelper is null
D/ResourcesManager( 1449): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1449): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager( 1449): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1449): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1449): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/ActivityManager(  756): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6263 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 6263): MountEmulatedStorage()
I/libpersona( 6263): KNOX_SDCARD checking this for 10023
E/Zygote  ( 6263): v2
I/libpersona( 6263): KNOX_SDCARD not a persona
,I/art     ( 4057): Explicit concurrent mark sweep GC freed 39191(2MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 664us total 94.642ms
,I/art     (  756): Explicit concurrent mark sweep GC freed 49713(3MB) AllocSpace objects, 12(192KB) LOS objects, 17% free, 37MB/45MB, paused 1.274ms total 122.688ms
,D/ResourcesManager(  756): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     (  756): WaitForGcToComplete blocked for 20.090ms for cause Explicit
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SELinux ( 6263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6263): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/TimaKeyStoreProvider( 6263): TimaSignature is unavailable
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ActivityThread( 6263): Added TimaKeyStore provider
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/SurfaceWidgetView( 1449): destroyHardwareResources():305403449
,V/WindowOrientationListener(  756): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  756): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  756): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  756): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  756): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/Launcher( 1449): onRestart, Launcher: 437545364
,D/Launcher( 1449): onStart, Launcher: 437545364
D/Launcher.HomeView( 1449): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1776): [237392/8] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1776): [237392/8] SurfaceWidget drawing first frame
V/ActivityThread( 1449): updateVisibility : ActivityRecord{3a9a0c26 token=android.os.BinderProxy@3cc4c879 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/accuweather( 1776): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,D/ResourcesManager( 6263): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/SurfaceFlinger(  254): id=12 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  756): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  756): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  756): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  756): setMouseCustomIcon IconType is same.101
D/PointerIcon(  756): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  756): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/SecContentProvider2(  756): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  756): mCursor = null
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,I/KLMS-2.4.511: ( 6263): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/InputMethodManagerService(  756): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/KLMS-2.4.511: ( 6263): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449275263043
,W/InputMethodManagerService(  756): Got RemoteException sending setActive(false) notification to pid 6117 uid 10256
W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/RegisteredServicesCache( 1416): empty dynamic service
,I/KLMS-2.4.511: ( 6263): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.511: ( 6263): MainReciver(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/EnterpriseDeviceManagerService(  756): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  756): Admin package name: com.google.android.gms
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/Timeline(  756): Timeline: Activity_windows_visible id: ActivityRecord{1bb45583 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:79884
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  756): PackageReceiver onReceive()
,I/HarmonyEASService(  756): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  756): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  756): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  756): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  756): uID is 10256
V/EnterpriseBillingPolicy(  756): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  756): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  756): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  756): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  756): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  756): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  756): getBillingProfileForVpnEngine - end - null
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/Zygote  ( 6289): MountEmulatedStorage()
E/Zygote  ( 6289): v2
I/libpersona( 6289): KNOX_SDCARD checking this for 10116
I/libpersona( 6289): KNOX_SDCARD not a persona
I/ActivityManager(  756): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6289 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/ActivityManager(  756): Killing 5225:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,D/TaskPersister(  756): removeObsoleteFile: deleting file=2_task.xml
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/SELinux ( 6289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Maps/Maps.apk
,V/AlarmManager(  756): waitForAlarm result :4
E/SELinux ( 6289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6289): TimaSignature is unavailable
,D/ActivityThread( 6289): Added TimaKeyStore provider
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,I/art     (  756): Explicit concurrent mark sweep GC freed 17888(1060KB) AllocSpace objects, 4(64KB) LOS objects, 17% free, 37MB/45MB, paused 2.689ms total 418.031ms
,D/BatteryService(  756): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4313, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  756): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/LightsService(  756): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 756) 
D/LightsService(  756): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,E/LightSensor(  756): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  756): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  756): turn on LED for fully charged
,I/MotionRecognitionService(  756): Plugged
I/MotionRecognitionService(  756): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1194): received broadcast android.intent.action.BATTERY_CHANGED
,D/SecContentProvider2(  756): uri = 14 selection = getSealedState
,D/SecContentProvider2(  756): mCursor = null
,D/ResourcesManager( 6289): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ApplicationPolicy(  756): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
V/ApplicationPolicy(  756): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,D/WindowManager(  756): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService(  756): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10067 pid=1194
I/PowerManagerService(  756): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification
I/PowerManagerService(  756): Waking up from sleep (uid 10067)...
,D/PowerManagerService(  756): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  756): [s] UserActivityState : 0 -> 1
,V/KeyguardServiceDelegate(  756): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@14419753)
I/AudioService(  756): getStreamVolume 1 index 0
D/NotificationService(  756): Noti Alert - doVibrate false convertStoV=true
V/Vibrator(  756): Called vibrateNotification() API - PUID: 1000, PackageName: android, type: 13
V/Vibrator(  756): Called vibrateImmVibe(int, MagnitudeType) API - PUID: 1000, PackageName: android
V/Vibrator(  756): vibrateImmVibe - PUID: 1000, PackageName: android, type: 13, mag: 0
D/VibratorService(  756): Turning vibrator off - ImmVibe.
,D/KeyguardViewMediator( 1194): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1194): notifyScreenOnLocked
,I/DisplayPowerController(  756): Blocking screen on until initial contents have been drawn.
,D/PowerManagerService(  756): [PWL] sb acquire: PowerManagerService.Display
D/SContextService(  756): 	.registerCallback : 1, client=
,W/CAE     (  756): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
D/AutomaticBrightnessController(  756): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController(  756): getFinalBrightness : 0 -> 0
D/DisplayPowerController(  756): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)), PendingAutoBrightness)
D/AutomaticBrightnessController(  756): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/STATUSBAR-PhoneStatusBar( 1194):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1194): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1194): handleBatteryUpdate
D/BatteryMeterView( 1194): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/PowerManagerService(  756): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,I/CAE     (  756): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
D/MISC PowerHAL(  756): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
I/CAE     (  756): setCAProperty(ContextAwareService.java:469) - result : true
D/MISC PowerHAL(  756): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
,I/QCOM PowerHAL(  756): Got set_interactive hint
,D/AutomaticBrightnessController(  756): [api] [DAB] onSensorChanged : 1st lux : 1.2416
D/AutomaticBrightnessController(  756): [DAB] updateAutoBrightnessSEC : 10(10.0)    0.0 < 1.2416 < 15.0 (0.0)
D/AutomaticBrightnessController(  756): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  756): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
I/AutomaticBrightnessController(  756): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/AutomaticBrightnessController(  756): [DAB] fileWriteInt : /sys/class/lcd/panel/lux  value : 1
,D/DisplayPowerController(  756): getFinalBrightness : 10 -> 10
D/DisplayPowerController(  756): animation target = 10, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/BatteryMeterView( 1194): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/CAE     (  756): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  756): sendAttribute() : service = Auto Rotation
W/CAE     (  756): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  756): start(ContextProvider.java:126)
,V/CAE     (  756): clear(AutoRotationRunner.java:182)
V/CAE     (  756): enable(AutoRotationRunner.java:158)
,I/CAE     (  756): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  756): SendSensorHubData: send data = -79, 7, 0, 0
,D/Sensorhubs(  305): sendContextData: -79, 7, 0, 0
D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  254): hwc_blank: Unblanking display: 0
,I/DisplayManagerService(  756): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SensorManager(  756): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,V/ActivityManager(  756): Display changed displayId=0
,D/PowerManagerService(  756): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 13ms
E/Sensors (  756): Acc old sensor_state 512, new sensor_state : 513 en : 1
,D/CAE     (  756): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  756): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/SensorManager(  756): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
,D/PowerManagerService(  756): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 13ms
,D/DisplayPowerController(  756): getFinalBrightness : 10 -> 10
,D/DisplayPowerController(  756): animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/elm:14491( 6289): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491( 6289): ELMEngine.ELMEngine( context ).
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  756): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
D/elm:14491( 6289): MDMBridge.setEnterpriseBridge()
,D/PackageManager(  756): delete codoeFile: 
,I/AASAUninstall(  756):  com.example.hello not target!
W/ResourcesManager(  756): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  756): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  756): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/CAE     (  756): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/CAE     (  756): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     (  756): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
I/CAE     (  756): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@50297a1, Service : AUTO_ROTATION(1)
,W/CAE     (  756): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  756): addSContextService() : service = Auto Rotation
D/SContextService(  756): ===== SContext Service List =====
D/SContextService(  756): Listener : android.hardware.scontext.SContextService$Listener@27052187, Service : Auto Rotation
D/SContextManager(  756):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@393ae890, service=Auto Rotation
,D/Launcher( 1449): onResume, Launcher: 437545364
,D/PackageManager(  756): result of delete: 1{372195355}
D/SettingsProvider(  756): name = kids_home_mode
D/SettingsProvider(  756): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  756): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  756): selectionArgs: false
D/SettingsProvider(  756): selectionArgs: 10010
D/SecContentProvider(  756): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  756): ret = -1
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Launcher.HomeView( 1449): onResume
D/ResourcesManager(  756): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1776): [237392/8] Surface widget resume on instance = 1
,D/accuweather( 1776): [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
D/accuweather( 1776): [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
D/accuweather( 1776): [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
,D/accuweather( 1776): [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
,D/accuweather( 1776): [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
D/AndroidRuntime( 6241): Shutting down VM
,D/Launcher( 1449): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1449): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/accuweather( 1776): [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
,D/accuweather( 1776): [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
,D/accuweather( 1776): [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
,D/accuweather( 1776): [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
D/accuweather( 1776): [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
D/accuweather( 1776): [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
,D/accuweather( 1776): [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
,E/SMD     (  292): DCD ON
,D/InputManager-JNI(  756): setDeviceInteractive: 1
,D/KeyguardViewMediator( 1194): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1194): onScreenTurnedOn()
,D/InputManager-JNI(  756): sysfs_write +: /sys/class/input/event3/device/enabled: 1
D/InputManager-JNI(  756): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,D/InputManager-JNI(  756): sysfs_write +: /sys/class/input/event4/device/enabled: 1
,D/InputManager-JNI(  756): sysfs_write +: /sys/class/input/event2/device/enabled: 1
,D/elm:14491( 6289): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/accuweather( 1776): [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
D/comsamsunglog( 1776): [Accuweather J]>>> ==============================================================================================
D/comsamsunglog( 1776): [Accuweather J]>>> widgetappapheroaccuweather [Version : 14121502] [ 1 ] 
D/comsamsunglog( 1776): [Accuweather J]>>> Header set to : ===> "accuweather" <===
D/comsamsunglog( 1776): [Accuweather J]>>> ==============================================================================================
D/accuweather( 1776): [Accuweather J]>>> SM:1134 [0:0] updateCurrentCityTime : [1]0/1
D/accuweather( 1776): [Accuweather J]>>> SM:1151 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
D/accuweather( 1776): [Accuweather J]>>> SM:2053 [0:0] drw 1nd Tm dt = Sat, 5 December
D/accuweather( 1776): [Accuweather J]>>> SM:3422 [0:0] onR : isAni = false
D/accuweather( 1776): [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
D/MenuAppsGridFragment( 1449): onResume
D/WallpaperManager( 1449): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1449): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/SamsungIME( 1731): showDlgMsgBox : false true true
D/NativeNfcManager( 1416): power state=4
I/MicrophoneInputStream( 1591): mic_starting gfk@52c4837
D/KnoxNotification( 1194): ----- inflateViews : modified publicViewLocal -----
V/AudioPolicyManager(  299): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  299): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  299): adev_open_input_stream: enter
E/audio_hw_primary(  299): adev_open_input_stream : jack_config 0
E/audio_hw_primary(  299): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  299): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  299): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  299): adev_open_input_stream input is null, set new input stream
,V/audio_hw_primary(  299): adev_open_input_stream: exit
,I/AudioFlinger(  299): AudioFlinger's thread 0xb0601000 ready to run
V/audio_hw_primary(  299): in_standby: enter
V/audio_hw_primary(  299): in_standby: exit:  status(0)
,V/audio_hw_primary(  299): in_standby: enter
V/audio_hw_primary(  299): in_standby: exit:  status(0)
,D/elm:14491( 6289): ElmAgentService : onCreate()
,D/elm:14491( 6289): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/HotwordRecognitionRnr( 1591): Starting hotword detection.
E/Zygote  ( 6314): MountEmulatedStorage()
E/Zygote  ( 6314): v2
I/libpersona( 6314): KNOX_SDCARD checking this for 10021
I/libpersona( 6314): KNOX_SDCARD not a persona
,D/elm:14491( 6289): MainReceiver.listeningToPackageRemoved()
,D/elm:14491( 6289): MDMBridge.getInstance()
D/elm:14491( 6289): MDMBridge.getAllLicenseInfoFromSDK()
,D/KnoxNotification( 1194): ----- inflateViews : modified KnoxViewLocal -----
,I/ActivityManager(  756): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6314 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/PalmMotion(  756): 2013 - SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
D/PalmMotion(  756): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  756):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService(  756): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 756) 
D/LightsService(  756): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/SSRM:a  (  756): DeviceInfo:: 000000100000
D/SSRM:a  (  756): SettingsAirViewInfo:: 010100000
,D/LightsService(  756): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 756) 
D/LightsService(  756): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/LightsService(  756): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/ResourcesManager(  756): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/SensorManager(  756): unregisterListener ::   
D/lights  (  756): led_pattern : 0 +
D/lights  (  756): led_pattern : 0 -
D/LightsService(  756): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService(  756): turn off LED
,I/art     (  331): Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 389us total 17.211ms
,I/SELinux ( 6314): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/CAE     (  756): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
I/SELinux ( 6314): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/CAE     (  756): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  756): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  756): SendSensorHubData: send data = -76, 13, -47, 0
E/SELinux ( 6314): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Sensorhubs(  305): sendContextData: -76, 13, -47, 0
,D/NfcService( 1416): call the applyRotuiing
,I/EDMNativeHelperService(  756): isMicrophoneEnabled
,D/ActivityManager(  756): handle home activity for 0
I/WallpaperManagerService(  756): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler(  756): post home show event for user 0
,D/ActivityManager(  756): post active user change for 0
D/KnoxTimeoutHandler(  756): postActiveUserChange for user 0
,I/art     (  331): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 346us total 12.267ms
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     (  331): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 326us total 12.714ms
,D/PersonaManager( 1194): PersonaID is invalid or persona doesn't exists. : 0
,D/InputMethodManagerService(  756): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
V/AudioPolicyManager(  299): startInput() input 14
V/AudioPolicyManager(  299): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  299): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  299): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  299): DeviceVector::getDevicesFromType() for type 80000004 found 0xb315b3c0
V/audio_hw_primary(  299): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  299): in_set_parameters: exit: status(11)
,V/AudioPolicyManager(  299): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  299): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1591): mic_started gfk@52c4837
,D/WallpaperManagerService(  756):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler(  756): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler(  756): handleActiveUserChange for user 0
,D/elm:14491( 6289): MDMBridge.getAllLicenseInfoFromSDK()
,D/InputManager-JNI(  756): sysfs_write -: /sys/class/input/event4/device/enabled: 1
,D/MotionRecognitionService(  756):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  756):  handler : SCREEN_ON end
,V/msm8974_platform(  299): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  299): start_input_stream: enter: usecase(7)
V/voice   (  299): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  299): start_input_stream: usecase(7)
D/PreProcess(  299): new SamsungRecord
D/PreProcess(  299): new NS
I/samsungRecord(  299): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  299): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  299): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  299): 1
D/SamsungRecord_NS(  299): [SamsungRecord_NS] Init SR 16000
,D/SamsungRecord_NS(  299): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  299): select_devices: ENTER
V/audio_hw_primary(  299): select_devices: usecase(normal)
D/TimaKeyStoreProvider( 6314): TimaSignature is unavailable
D/StatusBar.NetworkController( 1194): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1194): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1194): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/ActivityThread( 6314): Added TimaKeyStore provider
V/audio_hw_primary(  299): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  299): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  299): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  299): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  299): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  299): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  299): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  299): select_devices: in_snd_device(128: vr-main-mic)
D/ACDB-LOADER(  299): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  299): ACDB -> send_adm_topology
D/ACDB-LOADER(  299): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  299): ACDB -> send_asm_topology
D/ACDB-LOADER(  299): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  299): ACDB -> send_audtable
D/ACDB-LOADER(  299): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  299): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  299): ACDB -> send_audvoltable
D/ACDB-LOADER(  299): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  299): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  299): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  299): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  299): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  299): enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
D/audio_route(  299): ++++ audio_route_update_mixer ==============
D/audio_route(  299): Setting mixer control: ADC1 Volume
D/audio_route(  299): Setting mixer control: value: 19
,D/StatusBar.NetworkController( 1194): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1194): onWifiSignalChanged enabled=false enabledDesc:null
,I/WifiNative-HAL(  756): startHal
E/wifi    (  756): getStaticLongField sWifiHalHandle 0x9c0cc80c
D/wifi    (  756): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x401d56
I/WifiNative-HAL(  756): Could not start hal
V/KeyguardServiceDelegate(  756): **** SHOWN CALLED ****
,D/StatusBarKeyguardViewManager( 1194): callback.onShown()
D/DisplayPowerController(  756): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController(  756): Unblocked screen on after 218 ms
D/DisplayPowerState(  756): !@ ColorFade exit
,D/audio_route(  299): Setting mixer control: DEC6 Volume
D/audio_route(  299): Setting mixer control: value: 84
D/audio_route(  299): Setting mixer control: SLIM TX7 MUX, value: 13
,D/BatteryMeterView( 1194): onDraw batteryColor : -1
,D/audio_route(  299): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  299): Setting mixer control: value: 1
,D/audio_route(  299): Setting mixer control: DEC6 MUX, value: 2
,D/audio_route(  299): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  299): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  299): enable_audio_route: apply mixer path: audio-record
D/audio_route(  299): ++++ audio_route_update_mixer ==============
D/audio_route(  299): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  299): Setting mixer control: value: 1
,D/audio_route(  299): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  299): enable_audio_route: exit
V/audio_hw_primary(  299): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  299): start_input_stream: exit
,D/NotificationService(  756): ACTION_SCREEN_ON
D/LightsService(  756): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 756) 
D/LightsService(  756): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService(  756): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  756): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/SurfaceFlinger(  254): id=8 Removed DolorFade (8/8)
,E/libEGL  (  756): call to OpenGL ES API with no current context (logged once per thread)
D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/DisplayPowerController(  756): getFinalBrightness : 10 -> 10
D/DisplayPowerController(  756): animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SurfaceFlinger(  254): id=8 Removed DolorFade (-2/8)
D/lights  (  756): lcd : 10 +
D/lights  (  756): lcd : 10 -
,D/DisplayPowerController(  756): getFinalBrightness : 10 -> 10
D/DisplayPowerController(  756): animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService(  756): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  756): SecHardwareInterface.setBatteryADC : true
,D/PowerManagerService(  756): [input device light] setInputDeviceLightOn is called : 1
D/audio_hw_primary(  299): adev_set_parameters: enter: screen_state=on
V/voice   (  299): voice_set_parameters: enter: screen_state=on
V/voice   (  299): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  299): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  299): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  299): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  299): adev_set_parameters: exit
,D/StatusBarManagerService(  756): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SecExternalDisplayIntents_Java(  756): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/PowerManagerService(  756): [input device light] handleInputDeviceLightOn
D/lights  (  756): button : 1 +
,D/elm:14491( 6289): ElmAgentService : onDestroy().
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/ResourcesManager( 6314): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/StatusBar.NetworkController( 1194): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1194): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1194): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/IpRemoteDisplayController(  756): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  756): Bridge Server is not available
D/StatusBar.NetworkController( 1194): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1194): onWifiSignalChanged enabled=false enabledDesc:null
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,E/qdexternal(  254): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  254): hwc_blank: Done unblanking display: 0
I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 1
,I/Timeline( 1449): Timeline: Activity_idle id: android.os.BinderProxy@3cc4c879 time:80367
I/SurfaceFlinger(  254): id=13 createSurf (1080x750),1 flag=4, Ieads Up
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SurfaceControl(  756): Excessive delay in setPowerMode(): 272ms
D/PowerManagerService(  756): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 277ms
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  756): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/lights  (  756): button : 1 -
,D/UsbSettingsManager(  756): clearDefaults: com.example.hello
,I/CrashAnrDetector(  756): onPackageRemoved : com.example.hello
D/InputManager-JNI(  756): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,I/HotwordWorker( 1591): onReady
,D/GpsLocationProvider(  756): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6314): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6314): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6314): onReceive() : package name is not s health. Return !!!
,D/PersonaManagerService(  756): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler(  756): MSG_ACTION_SCREEN_ON called
,I/NfcService( 1416): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1416): call the applyRotuiing
,I/PCWCLIENTTRACE_PushUtil( 5691): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5691): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5691): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5691): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  756): creating new AssetManager and set to /system/priv-app/SystemUI/SystemUI.apk
,W/ResourcesManager(  756): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,D/accuweather( 1776): [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
,D/accuweather( 1776): [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
,E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  340): Waiting for service AtCmdFwd...
,E/Zygote  ( 6337): MountEmulatedStorage()
E/Zygote  ( 6337): v2
I/libpersona( 6337): KNOX_SDCARD checking this for 10043
I/libpersona( 6337): KNOX_SDCARD not a persona
,I/ActivityManager(  756): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6337 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  756): Killing 5034:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,I/SELinux ( 6337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6337): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/SamsungIME( 1731): getNextShiftState() cursorCapsMode : 0
,I/EventHub(  756): Removing device '/dev/input/event6' due to inotify event
,D/TimaKeyStoreProvider( 6337): TimaSignature is unavailable
,D/ActivityThread( 6337): Added TimaKeyStore provider
,I/EventHub(  756): Removing device '/dev/input/event7' due to inotify event
,D/ConnectivityService(  756): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.samsung.app( 3279): [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
,E/com.samsung.app( 3279): [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,W/com.samsung.app( 3279): [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25161492k
,D/com.samsung.app( 3279): [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
,I/com.samsung.app( 3279): [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
D/com.samsung.app( 3279): [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
,D/com.samsung.app( 3279): [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
D/com.samsung.app( 3279): [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1449275263816
,D/ResourcesManager( 6337): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ContextImpl( 6337): Unable to create files subdir /data/data/com.sec.spp.push/cache
,E/ActivityThread( 6337): Unable to setupGraphicsSupport due to missing cache directory
,E/SharedPreferencesImpl( 5301): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,I/EventHub(  756): Removing device '/dev/input/event8' due to inotify event
,D/PowerManagerService(  756): [PWL] sb release: PowerManagerService.Broadcasts
,E/SPPClientService( 6337): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6337): [PushClientApplication] Push log off : This is Ship build version
,W/ContextImpl( 6337): Unable to create files subdir /data/data/com.sec.spp.push/files
,D/SPPClientService( 6337): PushLog.txt file is not deleted.
W/ContextImpl( 6337): Unable to create files subdir /data/data/com.sec.spp.push/files
D/SPPClientService( 6337): PushLog.txt file is not deleted.
,D/SPPClientService( 6337): ============PushLog. stop!
,I/EventHub(  756): Removing device '/dev/input/event9' due to inotify event
,E/SQLiteLog( 6337): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteLog( 6337): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6337): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6337): (14) os_unix.c:32503: (2) open(/data/data/com.sec.spp.push/databases/push_noti_db) - 
,E/SQLiteDatabase( 6337): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6337): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6337): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6337): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6337): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6337): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 6337): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 6337): 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
E/SQLiteDatabase( 6337): 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
E/SQLiteDatabase( 6337): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 6337): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 6337): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 6337): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6337): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6337): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6337): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6337): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 6337): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6337): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6337): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 6337): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
,E/LNoti   ( 6337): [b] open fail. SQLException occured
I/SA      ( 5773): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
I/SA      ( 5773): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10256 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  756): Killing 4337:com.android.providers.calendar/u0a51 (adj 13): bgCount ##41
E/SharedPreferencesImpl( 4862): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
I/EventHub(  756): Removing device '/dev/input/event10' due to inotify event
D/Mms/FreeMessageReceiver( 4783): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/TactileAssist(  756): enable value -1
I/TactileAssist(  756): internal enable value -1
I/TactileAssist(  756): intensity value -1
I/TactileAssist(  756): saveAppList value true
,I/TactileAssist(  756): List of disabled apps :
,E/SharedPreferencesImpl(  756): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,D/SettingsProvider(  756): name = reading_mode_app_list
D/Mms/FreeMessageReceiverService( 4783): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4783): onHandleIntent: ACTION_PACKAGE_REMOVED
D/Compatibility( 5810): onReceive() it will make start service
,I/UpdateIcingCorporaServi( 1591): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Compatibility( 5810): onHandleIntent()
,D/Compatibility( 5810): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10256, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5810): found: 2
D/Compatibility( 5810): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5810): skipping ResolveInfo{276429e7 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5810): considering ResolveInfo{1a146994 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
,D/Compatibility( 5810): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5810): enabling receiver ResolveInfo{f543c3d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5810): enabling receiver ResolveInfo{5666c32 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5810): enabling receiver ResolveInfo{223f7d83 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5810): enabling receiver ResolveInfo{3988b00 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/SharedPreferencesImpl( 5810): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
,I/EventHub(  756): Removing device '/dev/input/event11' due to inotify event
E/SharedPreferencesImpl( 5810): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 5810): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/SQLiteLog( 1591): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1591): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AndroidRuntime( 1591): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1591): Process: com.google.android.googlequicksearchbox:search, PID: 1591
E/AndroidRuntime( 1591): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1591): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1591): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 1591): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1591): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1591): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 1591): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime( 1591): 	at csx.d(PG:186)
E/AndroidRuntime( 1591): 	at cun.g(PG:594)
E/AndroidRuntime( 1591): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 1591): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:330)
E/AndroidRuntime( 1591): 	at android.content.ContentResolver.update(ContentResolver.java:1343)
E/AndroidRuntime( 1591): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 1591): 	at cuy.ub(PG:301)
E/AndroidRuntime( 1591): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 1591): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 1591): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1591): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 1591): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ContextImpl( 5053): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
,V/ApplicationPolicy(  756): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox:search
,I/EventHub(  756): Removing device '/dev/input/event12' due to inotify event
,E/AndroidRuntime(  756): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  756): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  756): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  756): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  756): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  756): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  756): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  756): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/AndroidRuntime(  756): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  756): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  756): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  756): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  756): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  756): 	... 5 more
,D/SSRM:n  (  756): SIOP:: AP = 340, PST = 382, CUR = 450
,D/RCPManager( 5342):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService(  756):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService(  756): queryAllProviders():  providerCallBack is not register for 0
,E/SQLiteLog( 5053): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (2)
,E/SQLiteLog( 5053): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 5053): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 5053): (14) os_unix.c:32503: (2) open(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu) - 
,D/StatusBarManagerService(  756): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/SQLiteDatabase( 5053): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5053): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5053): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 5053): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5053): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5053): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 5053): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5053): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5053): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5053): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5053): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
D/PointerIcon(  756): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  756): setMouseCustomIcon IconType is same.101
,D/PointerIcon(  756): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
W/System.err( 5053): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
D/PointerIcon(  756): setHoveringSpenCustomIcon IconType is same.1
W/System.err( 5053): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5053): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5053): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5053): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,W/System.err( 5053): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5053): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err( 5053): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err( 5053): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5053): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
W/System.err( 5053): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5053): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5053): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
,W/System.err( 5053): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5053): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 5053): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5053): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5053): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5053): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub(  756): Removing device '/dev/input/event13' due to inotify event
,F/libc    (  756): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa97eb028 in tid 957 (ActivityManager)
,W/ContextImpl( 5882): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
,I/EventHub(  756): Removing device '/dev/input/event14' due to inotify event
,E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 5438): [895] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,E/Zygote  ( 6363): MountEmulatedStorage()
E/Zygote  ( 6363): v2
I/libpersona( 6363): KNOX_SDCARD checking this for 10121
I/libpersona( 6363): KNOX_SDCARD not a persona
,I/ActivityManager(  756): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6363 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  756): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 5438): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SharedPreferencesImpl( 5438): Couldn't create directory for SharedPreferences file /data/data/com.android.vending/shared_prefs/finsky.xml
,I/SELinux ( 6363): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  756): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6369 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6363): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6363): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 6369): MountEmulatedStorage()
E/Zygote  ( 6369): v2
I/libpersona( 6369): KNOX_SDCARD checking this for 1000
I/libpersona( 6369): KNOX_SDCARD not a persona
,I/DEBUG   (  286): failed to change ownership of /data/tombstones: Read-only file system
E/        (  286): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 756
,I/SELinux ( 6369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6369): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dumpstate( 6376): begin
,I/dumpstate( 6376): open lockfile failed Read-only file system
,E/libsuspend(  756): Error reading from /sys/power/wakeup_count: Interrupted system call
,E/audit_log( 1807): File locking failed. error= Bad file number
,E/installd(  302): eof
E/installd(  302): failed to read size
I/installd(  302): closing connection
,F/libc    ( 6369): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7428c9c3 in tid 6369 (ndroid.keychain)
,E/WifiManager( 1591): Channel connection lost
,W/Sensors ( 4862): sensorservice died [0xaf3e1240]
,E/WifiManager( 1480): Channel connection lost
W/Sensors ( 1480): sensorservice died [0xaf3ed300]
,E/AndroidRuntime( 1591): Error reporting crash
E/AndroidRuntime( 1591): android.os.DeadObjectException
E/AndroidRuntime( 1591): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 1591): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 1591): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 1591): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 1591): 	at gqq.uncaughtException(PG:58)
E/AndroidRuntime( 1591): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 1591): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 1591): Sending signal. PID: 1591 SIG: 9
,F/libc    ( 6363): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7428c9c3 in tid 6363 (.filterprovider)
,E/WifiManager( 1570): Channel connection lost
I/ServiceManager(  252): service 'connectivity' died
I/ServiceManager(  252): service 'sb_service' died
I/ServiceManager(  252): service 'servicediscovery' died
I/ServiceManager(  252): service 'updatelock' died
I/ServiceManager(  252): service 'notification' died
E/ActivityThread( 5882): Failed to find provider info for com.samsung.android.provider.filterprovider
I/ServiceManager(  252): service 'devicestoragemonitor' died
I/ServiceManager(  252): service 'location' died
I/ServiceManager(  252): service 'country_detector' died
I/ServiceManager(  252): service 'search' died
E/ActivityThread( 5882): Failed to find provider info for com.samsung.android.provider.filterprovider
I/ServiceManager(  252): service 'dropbox' died
I/ServiceManager(  252): service 'wallpaper' died
I/ServiceManager(  252): service 'audio' died
I/ServiceManager(  252): service 'DockObserver' died
I/ServiceManager(  252): service 'motion_recognition' died
I/ServiceManager(  252): service 'cover' died
I/ServiceManager(  252): service 'mount' died
I/ServiceManager(  252): service 'lock_settings' died
I/ServiceManager(  252): service 'device_policy' died
I/ServiceManager(  252): service 'harmony_eas_service' died
I/ServiceManager(  252): service 'sdp' died
I/ServiceManager(  252): service 'log_manager_service' died
I/ServiceManager(  252): service 'wifip2p' died
I/ServiceManager(  252): service 'mum_container_policy' died
I/ServiceManager(  252): service 'enterprise_billing_policy' died
I/ServiceManager(  252): service 'knox_timakeystore_policy' died
I/ServiceManager(  252): service 'enterprise_policy' died
I/ServiceManager(  252): service 'statusbar' died
I/ServiceManager(  252): service 'clipboard' died
I/ServiceManager(  252): service 'clipboardEx' died
I/ServiceManager(  252): service 'network_management' died
I/ServiceManager(  252): service 'ABTPersistenceService' died
I/ServiceManager(  252): service 'textservices' died
I/ServiceManager(  252): service 'network_score' died
I/ServiceManager(  252): service 'netstats' died
I/ServiceManager(  252): service 'netpolicy' died
I/ServiceManager(  252): service 'wifi' died
I/ServiceManager(  252): service 'msapwifi' died
I/ServiceManager(  252): service 'wifiscanner' died
I/ServiceManager(  252): service 'rttmanager' died
I/ServiceManager(  252): service 'backup' died
I/ServiceManager(  252): service 'appwidget' died
I/ServiceManager(  252): service 'voiceinteraction' died
I/ServiceManager(  252): service 'SecExternalDisplayService' died
I/ServiceManager(  252): service 'diskstats' died
I/ServiceManager(  252): service 'mDNIe' died
I/ServiceManager(  252): service 'spengestureservice' died
I/ServiceManager(  252): service 'quickconnect' died
I/ServiceManager(  252): service 'samplingprofiler' died
I/ServiceManager(  252): service 'commontime_management' died
I/ServiceManager(  252): service 'dreams' died
I/ServiceManager(  252): service 'assetatlas' died
I/ServiceManager(  252): service 'print' died
I/ServiceManager(  252): service 'restrictions' died
I/ServiceManager(  252): service 'media_session' died
I/ServiceManager(  252): service 'media_router' died
I/ServiceManager(  252): service 'trust' died
I/ServiceManager(  252): service 'fingerprint' died
I/ServiceManager(  252): service 'launcherapps' died
I/ServiceManager(  252): service 'voip' died
I/ServiceManager(  252): service 'media_projection' died
I/ServiceManager(  252): service 'imms' died
I/ServiceManager(  252): service 'usb' died
I/ServiceManager(  252): service 'serial' died
I/ServiceManager(  252): service 'uimode' died
I/ServiceManager(  252): service 'jobscheduler' died
I/ServiceManager(  252): service 'sec_analytics' died
I/ServiceManager(  252): service 'permission' died
I/ServiceManager(  252): service 'context_aware' died
I/ServiceManager(  252): service 'scontext' died
I/ServiceManager(  252): service 'barbeam' died
I/ServiceManager(  252): service 'multiwindow_facade' died
I/ServiceManager(  252): service 'window' di,ed
I/ServiceManager(  252): service 'input' died
I/ServiceManager(  252): service 'enterprise_license_policy' died
I/ServiceManager(  252): service 'application_policy' died
I/ServiceManager(  252): service 'wifi_policy' died
I/ServiceManager(  252): service 'phone_restriction_policy' died
I/ServiceManager(  252): service 'remoteinjection' died
I/ServiceManager(  252): service 'tactileassist' died
I/ServiceManager(  252): service 'bluetooth_manager' died
I/ServiceManager(  252): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  252): service 'rcp' died
I/ServiceManager(  252): service 'input_method' died
I/ServiceManager(  252): service 'accessibility' died
I/ServiceManager(  252): service 'CustomFrequencyManagerService' died
I/ServiceManager(  252): service 'samsung.smartfaceservice' died
I/ServiceManager(  252): service 'consumer_ir' died
I/ServiceManager(  252): service 'alarm' died
I/ServiceManager(  252): service 'webviewupdate' died
I/ServiceManager(  252): service 'usagestats' died
I/ServiceManager(  252): service 'battery' died
I/ServiceManager(  252): service 'telephony.registry' died
I/ServiceManager(  252): service 'entropy' died
I/ServiceManager(  252): service 'SEAMService' died
I/ServiceManager(  252): service 'persona' died
I/ServiceManager(  252): service 'account' died
I/ServiceManager(  252): service 'content' died
E/AndroidRuntime( 5882): FATAL EXCEPTION: FilterPackageServiceHandler
E/AndroidRuntime( 5882): Process: com.samsung.android.app.filterinstaller, PID: 5882
E/AndroidRuntime( 5882): java.lang.IllegalArgumentException: Unknown URL content://com.samsung.android.provider.filterprovider/packages/com.example.hello
E/AndroidRuntime( 5882): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 5882): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromDB(FilterUninstaller.java:52)
E/AndroidRuntime( 5882): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:43)
E/AndroidRuntime( 5882): 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
E/AndroidRuntime( 5882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5882): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5882): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ServiceManager(  252): service 'DirEncryptService' died
I/ServiceManager(  252): service 'meminfo' died
I/ServiceManager(  252): service 'hardware' died
I/ServiceManager(  252): service 'activity' died
I/ServiceManager(  252): service 'gfxinfo' died
I/ServiceManager(  252): service 'cpuinfo' died
I/ServiceManager(  252): service 'user' died
I/ServiceManager(  252): service 'procstats' died
I/ServiceManager(  252): service 'package' died
I/ServiceManager(  252): service 'dbinfo' died
I/ServiceManager(  252): service 'ReactiveService' died
I/ServiceManager(  252): service 'sedenial' died
I/ServiceManager(  252): service 'vibrator' died
I/ServiceManager(  252): service 'tima' died
I/ServiceManager(  252): service 'cepproxyks' died
I/ServiceManager(  252): service 'scheduling_policy' died
I/ServiceManager(  252): service 'mdm.remotedesktop' died
I/ServiceManager(  252): service 'sensorservice' died
I/ServiceManager(  252): service 'batterystats' died
I/ServiceManager(  252): service 'appops' died
I/ServiceManager(  252): service 'power' died
I/ServiceManager(  252): service 'display' died
I/ServiceManager(  252): service 'persona_policy' died
I/ServiceManager(  252): service 'edmnativehelper' died
E/AndroidRuntime( 5882): Error reporting crash
E/AndroidRuntime( 5882): android.os.DeadObjectException
E/AndroidRuntime( 5882): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5882): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5882): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 5882): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 5882): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 5882): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 5882): Sending signal. PID: 5882 SIG: 9
W/Sensors ( 1449): sensorservice died [0xaf3db280]
E/WifiManager( 1317): Channel connection lost
W/Sensors ( 1400): sensorservice died [0xaf3d99c0]
W/Sensors ( 1194): sensorservice died [0xaf3dc1c0]
E/WifiManager( 1194): Channel connection lost
W/AudioFlinger(  299): power manager service died !!!
W/AudioCache(  299): clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
W/AudioFlinger(  299): power manager service died !!!
W/Sensors ( 1423): sensorservice died [0xaf3db200]
E/WifiManager( 1423): Channel connection lost
W/Sensors ( 1776): sensorservice died [0xaf3a1680]
I/SurfaceFlinger(  254): restart the boot-animation @ binderDied
D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
D/SurfaceFlinger(  254): Screen type=0 is already mode=2
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (5/8)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (0/7)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (0/6)
I/SurfaceFlinger(  254): id=9 Removed EimLayer (0/5)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (0/4)
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (-2/4)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (-2/4)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (-2/4)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (0/3)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (-2/3)
W/Sensors ( 1914): sensorservice died [0xaf3caa00]
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (1/2)
I/SurfaceFlinger(  254): id=13 Removed Ieads Up (1/1)
I/SurfaceFlinger(  254): id=12 Removed Mauncher (0/0)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (-2/0)
I/SurfaceFlinger(  254): id=12 Removed Mauncher (-2/0)
I/SurfaceFlinger(  254): id=13 Removed Ieads Up (-2/0)
I/SurfaceFlinger(  254): id=9 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (-2/0)
,I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 0
I/DEBUG   (  286): failed to change ownership of /data/tombstones: Read-only file system
E/        (  286): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 6369
I/dumpstate( 6397): begin
I/dumpstate( 6397): open lockfile failed Read-only file system
V/AudioPolicyManager(  299): stopInput() input 14
V/AudioPolicyManager(  299): releaseInput() 14
V/AudioPolicyManager(  299): closeInput(14)

```
