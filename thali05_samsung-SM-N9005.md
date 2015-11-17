#### Test 50388019c82294c_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
I/ServiceManager(  355): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 6199): 
D/AndroidRuntime( 6199): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6199): CheckJNI is OFF
D/AndroidRuntime( 6199): readGMSProperty: start
D/AndroidRuntime( 6199): readGMSProperty: already setted!!
D/AndroidRuntime( 6199): readGMSProperty: end
D/AndroidRuntime( 6199): addProductProperty: start
I/ServiceManager(  355): Waiting for service AtCmdFwd...
E/AffinityControl( 6199): AffinityControl: registerfunction enter
D/AndroidRuntime( 6199): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  888): inState():  stateMachine is null !!
I/PersonaManagerService(  888): PersonaId don't exist
I/ActivityManager(  888): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
I/ActivityManager(  888): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  888): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager(  888): mDVFSHelper.acquire()
I/SurfaceFlinger(  254): id=10 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger(  254): id=11 createSurf (16x16),-1 flag=20004, EimLayer
D/FocusedStackFrame(  888): Set to : 0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  888): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6214 uid=10233 gids={50233, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 6199): Shutting down VM
E/Zygote  ( 6214): MountEmulatedStorage()
E/Zygote  ( 6214): v2
I/libpersona( 6214): KNOX_SDCARD checking this for 10233
I/libpersona( 6214): KNOX_SDCARD not a persona
I/SELinux ( 6214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/PointerIcon(  888): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  888): setMouseCustomIcon IconType is same.101
D/PointerIcon(  888): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  888): setHoveringSpenCustomIcon IconType is same.1
I/SELinux ( 6214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6214): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6214): TimaSignature is unavailable
D/ActivityThread( 6214): Added TimaKeyStore provider
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  888): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  888): Display changed displayId=0
D/SurfaceWidgetView( 1437): destroyHardwareResources():750826352
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6214): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1776): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1437): updateVisibility : ActivityRecord{645ae31 token=android.os.BinderProxy@3d69572d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1437): onTrimMemory. Level: 20
I/WebViewFactory( 6214): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 6214): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 6214): Loading: webviewchromium
I/LibraryLoader( 6214): Time to load native libraries: 5 ms (timestamps 9977-9982)
I/LibraryLoader( 6214): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6214): Binding Chromium to main looper Looper (main, tid 1) {165ae9ca}
I/LibraryLoader( 6214): Expected native library version number "",actual native library version number ""
I/chromium( 6214): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6214): Initializing chromium process, renderers=0
W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6214): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6214): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6214): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6214): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
I/Adreno-EGL( 6214): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6214): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6214): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6214): Local Branch: mybranch5813579
I/Adreno-EGL( 6214): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6214): Local Patches: NONE
I/Adreno-EGL( 6214): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
D/BluetoothAdapter( 6214): 338511675: getState() :  mService = null. Returning STATE_OFF
E/SMD     (  292): DCD ON
W/chromium( 6214): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6214): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6214): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6214): CordovaWebView is running on device made by: samsung
W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager(  888): Activity pause timeout for ActivityRecord{3a84dfe1 u0 com.example.hello/.MainActivity t2}
D/Activity( 6214): performCreate Call secproduct feature valuefalse
D/Activity( 6214): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 6214): Render dirty regions requested: true
D/Atlas   ( 6214): Validating map...
I/ServiceManager(  355): Waiting for service AtCmdFwd...
D/ActivityManager(  888): post active user change for 0
D/KnoxTimeoutHandler(  888): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  888): handleActiveUserChange for user 0
V/ActivityThread( 6214): updateVisibility : ActivityRecord{24192d88 token=android.os.BinderProxy@2269597a {com.example.hello/com.example.hello.MainActivity}} show : true
I/SurfaceFlinger(  254): id=12 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  888): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  888): setMouseCustomIcon IconType is same.101
D/PointerIcon(  888): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  888): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6214): Initialized EGL, version 1.4
,I/OpenGLRenderer( 6214): HWUI protection enabled for context ,  &this =0xafa76038 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6214): Enabling debug mode 0
,D/InputMethodManagerService(  888): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  888): mDVFSHelper.release(),
I/Timeline(  888): Timeline: Activity_windows_visible id: ActivityRecord{3a84dfe1 u0 com.example.hello/.MainActivity t2} time:80752
,W/IInputConnectionWrapper( 6214): showStatusIcon on inactive InputConnection
,I/Timeline( 6214): Timeline: Activity_idle id: android.os.BinderProxy@2269597a time:80770
,I/SamsungIME( 1728): getCurrentCandidateView
,D/SamsungIME( 1728): Dismiss ExpandCandiate
,I/chromium( 6214): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6214): 
,I/chromium( 6214): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 6214): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 6214): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1728): getDebugLevel  : 0x4f4c
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1728): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1728): KeybaordView init() : load resources
,I/SamsungIME( 1728): getCurrentKeyboard
,I/SamsungIME( 1728): getTextKeyboard
,D/SamsungIME( 1728): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6214): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258378624
,D/JX-Cordova( 6214): jxcore cordova android initializing
,W/jxcore-log( 6214): Initializing JXcore engine
W/jxcore-log( 6214): JXcore engine is ready
,W/jxcore-log( 6214): Starting JXcore engine
,E/auditd  ( 1864): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  888): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  888): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  888): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6312 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6312): MountEmulatedStorage()
E/Zygote  ( 6312): v2
I/libpersona( 6312): KNOX_SDCARD checking this for 1000
I/libpersona( 6312): KNOX_SDCARD not a persona
,I/art     (  330): Explicit concurrent mark sweep GC freed 8742(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 3.247ms total 18.972ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 265us total 9.820ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 265us total 9.845ms
,I/SELinux ( 6312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6312): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 6214): Platform android
W/jxcore-log( 6214): 
W/jxcore-log( 6214): Process ARCH arm
W/jxcore-log( 6214): 
,I/ServiceManager(  355): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 6312): TimaSignature is unavailable
,D/ActivityThread( 6312): Added TimaKeyStore provider
,I/jxcore-log( 6214): JXcore Cordova bridge is ready!
I/jxcore-log( 6214): 
,W/jxcore-log( 6214): JXcore engine is started
,D/ResourcesManager( 6312): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6312):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6312):  SeDenialReceiver : File path = null
,E/jxcore-log( 6214): >> samsung-SM-N9005
E/jxcore-log( 6214): 
,I/jxcore-log( 6214): Total memory 2971471872
I/jxcore-log( 6214): 
,I/jxcore-log( 6214): Free memory 424779776
I/jxcore-log( 6214): 
,I/jxcore-log( 6214): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6214): 
I/jxcore-log( 6214): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6214): 
,I/jxcore-log( 6214): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6214): 
,I/jxcore-log( 6214): Size 1080 1920
I/jxcore-log( 6214): 
,I/jxcore-log( 6214): Screen Brightness 162
I/jxcore-log( 6214): 
,E/jxcore-log( 6214): Dummy Error Log.
E/jxcore-log( 6214): 
,D/SamsungIME( 1728): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/jxcore-log( 6214): getBuffer is called!!!!
I/jxcore-log( 6214): 
,I/ServiceManager(  355): Waiting for service AtCmdFwd...
,I/ActivityManager(  888): Killing 5217:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,E/SMD     (  292): DCD ON
,W/Atfwd_Sendcmd(  355): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager(  888): waitForAlarm result :8
,D/NtpTrustedTime(  888): forceRefresh() from cache miss
,D/NtpTrustedTime(  888): forceRefresh Fail.
,V/AlarmManager(  888): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  888): <AppSync3 Whitelist>
,V/AlarmManager(  888): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,D/BluetoothAdapter( 6214): disable()
,E/BluetoothManagerService(  888): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 6214): packageName : com.example.hello
,D/SecContentProvider(  888): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  888): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2(  888): mCursor = null
,D/WifiService(  888): setWifiEnabled: false pid=6214, uid=10233
,D/SettingsProvider(  888): name = wifi_on
,I/jxcore-log( 6214): ****TEST TOOK:  5092  ms ****
I/jxcore-log( 6214): 
,I/jxcore-log( 6214): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6214): 
,D/AndroidRuntime( 6344): 
D/AndroidRuntime( 6344): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6344): CheckJNI is OFF
,D/AndroidRuntime( 6344): readGMSProperty: start
D/AndroidRuntime( 6344): readGMSProperty: already setted!!
,D/AndroidRuntime( 6344): readGMSProperty: end
,D/AndroidRuntime( 6344): addProductProperty: start
,E/AffinityControl( 6344): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6344): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService(  888): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  888): START PACKAGE DELETE: observer{241994342}
D/PackageManager(  888): pkg{<packageName>}
D/PackageManager(  888): user{0}
D/PackageManager(  888): caller{2000}
D/PackageManager(  888): flags{3}
D/PersonaManagerService(  888): isFromApprovedUnInstaller: isApproved : true
D/PackageManager(  888): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService(  888): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  888): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  888): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService(  888): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  888): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  888): getApplicationUninstallationEnabled
D/ApplicationPolicy(  888): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  888): !@killApplicatoin: 10233, uninstall pkg
,I/ActivityManager(  888): Force stopping com.example.hello appid=10233 user=-1: uninstall pkg
I/ActivityManager(  888): Killing 6214:com.example.hello/u0a233 (adj 0): stop com.example.hello
,W/PackageSettings(  888): Skipping PackageSetting{3dcae551 com.test.thalitest/10224} due to missing metadata
,I/WindowState(  888): WIN DEATH: Window{26487baf u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  254): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=12 Removed NainActivit (-2/8)
,I/SurfaceFlinger(  254): id=12 Removed NainActivit (-2/8)
,D/PointerIcon(  888): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  888): setMouseCustomIcon IconType is same.101
D/PointerIcon(  888): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  888): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager(  888):   Force finishing activity ActivityRecord{3a84dfe1 u0 com.example.hello/.MainActivity t2}
,D/FocusedStackFrame(  888): Set to : 0
,W/ActivityManager(  888): Spurious death for ProcessRecord{274631a7 6214:com.example.hello/u0a233}, curProc for 6214: null
,I/ActivityManager(  888): Force stopping com.example.hello appid=10233 user=0: pkg removed
,I/art     ( 6027): Explicit concurrent mark sweep GC freed 5325(262KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 547us total 19.055ms
,I/art     ( 4120): Explicit concurrent mark sweep GC freed 32159(1809KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 387us total 23.301ms
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  888): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1473): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/SamsungIME( 1728): mOCRHelper is null
,E/Zygote  ( 6365): MountEmulatedStorage()
E/Zygote  ( 6365): v2
I/libpersona( 6365): KNOX_SDCARD checking this for 10023
I/libpersona( 6365): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6365 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/SELinux ( 6365): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/art     (  888): Explicit concurrent mark sweep GC freed 24901(1987KB) AllocSpace objects, 11(176KB) LOS objects, 17% free, 37MB/45MB, paused 1.343ms total 140.646ms
,I/art     (  888): WaitForGcToComplete blocked for 60.401ms for cause Explicit
,D/ResourcesManager(  888): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/SELinux ( 6365): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6365): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/TimaKeyStoreProvider( 6365): TimaSignature is unavailable
,D/ActivityThread( 6365): Added TimaKeyStore provider
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/SurfaceWidgetView( 1437): destroyHardwareResources():750826352
,V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  888): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/RegisteredServicesCache( 1416): empty dynamic service
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/SecContentProvider2(  888): mCursor = null
D/Launcher( 1437): onRestart, Launcher: 689904663
D/Launcher( 1437): onStart, Launcher: 689904663
D/Launcher.HomeView( 1437): onStart
,V/ActivityThread( 1437): updateVisibility : ActivityRecord{645ae31 token=android.os.BinderProxy@3d69572d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1776): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/SurfaceWidget.Renderer( 1776): [237392/8] SurfaceWidget drawing first frame
,D/accuweather( 1776): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,I/SurfaceFlinger(  254): id=13 createSurf (1080x1920),1 flag=4, Mauncher
,D/ResourcesManager( 6365): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/EnterpriseDeviceManagerService(  888): Package has changed for user 0
D/EnterpriseDeviceManagerService(  888): Admin package name: com.google.android.gms
,D/PointerIcon(  888): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  888): setMouseCustomIcon IconType is same.101
D/PointerIcon(  888): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  888): setHoveringSpenCustomIcon IconType is same.1
D/InputMethodManagerService(  888): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  888): Got RemoteException sending setActive(false) notification to pid 6214 uid 10233
W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/PowerManagerService(  888): [PWL] Off : 30s ago
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/KLMS-2.4.511: ( 6365): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/KLMS-2.4.511: ( 6365): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1447782182398
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/Timeline(  888): Timeline: Activity_windows_visible id: ActivityRecord{35d23ab3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:87805
,I/KLMS-2.4.511: ( 6365): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.511: ( 6365): MainReciver(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,V/AlarmManager(  888): waitForAlarm result :4
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/BatteryService(  888): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4295, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  888): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  888): stay LED for fully charged
,D/RCPManagerService(  888): PackageReceiver onReceive()
,I/HarmonyEASService(  888): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  888): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  888): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  888): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  888): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  888): uID is 10233
V/EnterpriseBillingPolicy(  888): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  888): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  888): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  888): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  888): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  888): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  888): getBillingProfileForVpnEngine - end - null
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Books/Books.apk
,D/TaskPersister(  888): removeObsoleteFile: deleting file=2_task.xml
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/art     (  888): Explicit concurrent mark sweep GC freed 11296(647KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 37MB/45MB, paused 1.750ms total 308.544ms
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,I/ActivityManager(  888): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6392 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 6392): MountEmulatedStorage()
E/Zygote  ( 6392): v2
I/libpersona( 6392): KNOX_SDCARD checking this for 10116
I/libpersona( 6392): KNOX_SDCARD not a persona
,D/PackageManager(  888): delete codoeFile: 
,I/AASAUninstall(  888):  com.example.hello not target!
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/PackageManager(  888): result of delete: 1{241994342}
,I/SELinux ( 6392): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/AndroidRuntime( 6344): Shutting down VM
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/SELinux ( 6392): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6392): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6392): TimaSignature is unavailable
,D/ActivityThread( 6392): Added TimaKeyStore provider
,D/ResourcesManager( 6392): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/elm:14491( 6392): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14491( 6392): ELMEngine.ELMEngine( context ).
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/elm:14491( 6392): MDMBridge.setEnterpriseBridge()
,D/SSRM:n  (  888): SIOP:: AP = 350, PST = 388, CUR = 450
,D/elm:14491( 6392): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,D/elm:14491( 6392): ElmAgentService : onCreate()
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14491( 6392): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491( 6392): MainReceiver.listeningToPackageRemoved()
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/elm:14491( 6392): MDMBridge.getInstance()
D/elm:14491( 6392): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491( 6392): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/Zygote  ( 6409): MountEmulatedStorage()
E/Zygote  ( 6409): v2
I/libpersona( 6409): KNOX_SDCARD checking this for 10021
I/libpersona( 6409): KNOX_SDCARD not a persona
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/ActivityManager(  888): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6409 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager(  888): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  888): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  888): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,I/SELinux ( 6409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/elm:14491( 6392): ElmAgentService : onDestroy().
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
I/SELinux ( 6409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6409): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
I/ActivityManager(  888): Killing 5259:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  888): clearDefaults: com.example.hello
,I/CrashAnrDetector(  888): onPackageRemoved : com.example.hello
,D/TimaKeyStoreProvider( 6409): TimaSignature is unavailable
,D/ActivityThread( 6409): Added TimaKeyStore provider
,D/ResourcesManager( 6409): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6409): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6409): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6409): onReceive() : package name is not s health. Return !!!
,I/PCWCLIENTTRACE_PushUtil( 5784): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5784): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5784): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5784): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6427): MountEmulatedStorage()
,E/Zygote  ( 6427): v2
I/libpersona( 6427): KNOX_SDCARD checking this for 10043
I/libpersona( 6427): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6427 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ActivityManager(  888): Killing 5065:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
E/SELinux ( 6427): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6427): TimaSignature is unavailable
,D/ActivityThread( 6427): Added TimaKeyStore provider
,I/EventHub(  888): Removing device '/dev/input/event6' due to inotify event
,D/ResourcesManager( 6427): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ContextImpl( 6427): Unable to create files subdir /data/data/com.sec.spp.push/cache
E/ActivityThread( 6427): Unable to setupGraphicsSupport due to missing cache directory
,E/SharedPreferencesImpl( 5327): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,I/EventHub(  888): Removing device '/dev/input/event7' due to inotify event
,E/SPPClientService( 6427): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6427): [PushClientApplication] Push log off : This is Ship build version
,W/ContextImpl( 6427): Unable to create files subdir /data/data/com.sec.spp.push/files
,D/SPPClientService( 6427): PushLog.txt file is not deleted.
,W/ContextImpl( 6427): Unable to create files subdir /data/data/com.sec.spp.push/files
,D/SPPClientService( 6427): PushLog.txt file is not deleted.
D/SPPClientService( 6427): ============PushLog. stop!
,I/EventHub(  888): Removing device '/dev/input/event8' due to inotify event
,E/SQLiteLog( 6427): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 6427): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6427): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6427): (14) os_unix.c:32503: (2) open(/data/data/com.sec.spp.push/databases/push_noti_db) - 
E/SQLiteDatabase( 6427): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6427): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6427): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6427): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6427): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 6427): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 6427): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6427): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6427): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6427): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6427): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 6427): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6427): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6427): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 6427): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/LNoti   ( 6427): [b] open fail. SQLException occured
,I/SA      ( 5878): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5878): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10233 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,D/Finsky  ( 5465): [910] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5465): [1] 5.onFinished: Installation state replication succeeded.
,E/SharedPreferencesImpl( 5465): Couldn't create directory for SharedPreferences file /data/data/com.android.vending/shared_prefs/finsky.xml
,I/ActivityManager(  888): Killing 4369:com.android.providers.calendar/u0a51 (adj 13): bgCount ##41
,I/ActivityManager(  888): Killing 5102:com.google.android.talk/u0a131 (adj 13): bgCount ##41
,I/EventHub(  888): Removing device '/dev/input/event9' due to inotify event
,E/SharedPreferencesImpl( 4895): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
,D/Mms/FreeMessageReceiver( 4816): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/TactileAssist(  888): enable value -1
,I/TactileAssist(  888): internal enable value -1
I/TactileAssist(  888): intensity value -1
I/TactileAssist(  888): saveAppList value true
,I/TactileAssist(  888): List of disabled apps :
,E/SharedPreferencesImpl(  888): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,I/EventHub(  888): Removing device '/dev/input/event10' due to inotify event
,D/Mms/FreeMessageReceiverService( 4816): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4816): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/SettingsProvider(  888): name = reading_mode_app_list
,D/Compatibility( 5912): onReceive() it will make start service
,I/EventHub(  888): Removing device '/dev/input/event11' due to inotify event
,I/EventHub(  888): Removing device '/dev/input/event12' due to inotify event
,I/EventHub(  888): Removing device '/dev/input/event13' due to inotify event
,I/UpdateIcingCorporaServi( 1612): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Compatibility( 5912): onHandleIntent()
,D/Compatibility( 5912): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10233, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,W/ContextImpl( 5087): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
,D/RCPManager( 5367):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService(  888):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService(  888): queryAllProviders():  providerCallBack is not register for 0
,D/Compatibility( 5912): found: 2
D/Compatibility( 5912): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5912): skipping ResolveInfo{3325d896 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5912): considering ResolveInfo{291f1c17 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5912): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5912): enabling receiver ResolveInfo{d982804 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/EventHub(  888): Removing device '/dev/input/event14' due to inotify event
,D/Compatibility( 5912): enabling receiver ResolveInfo{1d1271ed com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ContextImpl( 6027): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
,E/SQLiteLog( 1612): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1612): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,F/libc    ( 1612): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa04d24e1 in tid 6447 (IntentService[U)
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5912): enabling receiver ResolveInfo{9dee822 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5912): enabling receiver ResolveInfo{aef62b3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/SharedPreferencesImpl( 5912): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
,E/SharedPreferencesImpl( 5912): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 5912): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/SQLiteLog( 5087): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (2)
,E/SQLiteLog( 5087): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 5087): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 5087): (14) os_unix.c:32503: (2) open(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu) - 
,E/SQLiteDatabase( 5087): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5087): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5087): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 5087): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5087): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5087): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 5087): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5087): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5087): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5087): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err( 5087): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
,W/System.err( 5087): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5087): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,W/System.err( 5087): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err( 5087): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err( 5087): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5087): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
W/System.err( 5087): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5087): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,W/System.err( 5087): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5087): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5087): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 5087): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5087): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 5087): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5087): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  888): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6450 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6450): MountEmulatedStorage()
E/Zygote  ( 6450): v2
I/libpersona( 6450): KNOX_SDCARD checking this for 1000
I/libpersona( 6450): KNOX_SDCARD not a persona
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6456): MountEmulatedStorage()
E/Zygote  ( 6456): v2
I/libpersona( 6456): KNOX_SDCARD checking this for 10121
I/libpersona( 6456): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6456 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 6450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/DEBUG   (  283): failed to change ownership of /data/tombstones: Read-only file system
E/        (  283): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 1612
,I/SELinux ( 6456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/dumpstate( 6462): begin
I/SELinux ( 6456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/dumpstate( 6462): open lockfile failed Read-only file system
E/SELinux ( 6456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SELinux ( 6450): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 0
,D/TimaKeyStoreProvider( 6456): TimaSignature is unavailable
,D/ActivityThread( 6456): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6450): TimaSignature is unavailable
,D/ActivityThread( 6450): Added TimaKeyStore provider
,D/ResourcesManager( 6456): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,W/ContextImpl( 6456): Unable to create files subdir /data/user/0/com.samsung.android.provider.filterprovider/cache
E/ActivityThread( 6456): Unable to setupGraphicsSupport due to missing cache directory
,E/audit_log( 1864): File locking failed. error= Bad file number
,D/ResourcesManager( 6450): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,W/ContextImpl( 6450): Unable to create files subdir /data/data/com.android.keychain/cache
E/ActivityThread( 6450): Unable to setupGraphicsSupport due to missing cache directory

```
