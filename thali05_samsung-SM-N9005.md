#### Test 5065027865f659b_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
D/SSRM:n  (  760): SIOP:: AP = 300, PST = 329, CUR = 450
W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
D/AndroidRuntime( 6259): 
D/AndroidRuntime( 6259): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6259): CheckJNI is OFF
D/AndroidRuntime( 6259): readGMSProperty: start
D/AndroidRuntime( 6259): readGMSProperty: already setted!!
D/AndroidRuntime( 6259): readGMSProperty: end
D/AndroidRuntime( 6259): addProductProperty: start
E/AffinityControl( 6259): AffinityControl: registerfunction enter
D/AndroidRuntime( 6259): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  760): inState():  stateMachine is null !!
I/PersonaManagerService(  760): PersonaId don't exist
I/ActivityManager(  760): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  760): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  760): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  760): mDVFSHelper.acquire()
D/FocusedStackFrame(  760): Set to : 0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6276 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6276): MountEmulatedStorage()
E/Zygote  ( 6276): v2
I/libpersona( 6276): KNOX_SDCARD checking this for 10270
I/libpersona( 6276): KNOX_SDCARD not a persona
D/PointerIcon(  760): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  760): setMouseCustomIcon IconType is same.101
D/PointerIcon(  760): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  760): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6259): Shutting down VM
I/SELinux ( 6276): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6276): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6276): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6276): TimaSignature is unavailable
D/ActivityThread( 6276): Added TimaKeyStore provider
V/WindowOrientationListener(  760): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  760): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener(  760): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager(  760): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  760): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  760): Display changed displayId=0
D/SurfaceWidgetView( 1443): destroyHardwareResources():925363262
D/ConnectivityService(  760): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/ResourcesManager( 6276): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 1443): updateVisibility : ActivityRecord{6bbc527 token=android.os.BinderProxy@7004300 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1760): [237392/8] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1443): onTrimMemory. Level: 20
,E/SMD     (  286): DCD ON
,I/WebViewFactory( 6276): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6276): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6276): Loading: webviewchromium
,I/LibraryLoader( 6276): Time to load native libraries: 6 ms (timestamps 2302-2308)
,I/LibraryLoader( 6276): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6276): Binding Chromium to main looper Looper (main, tid 1) {aa0cb}
,I/LibraryLoader( 6276): Expected native library version number "",actual native library version number ""
,I/chromium( 6276): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6276): Initializing chromium process, renderers=0
,W/art     ( 6276): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6276): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6276): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6276): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6276): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
D/BluetoothAdapter( 6276): 696680616: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6276): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6276): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6276): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6276): Local Branch: mybranch5813579
I/Adreno-EGL( 6276): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6276): Local Patches: NONE
I/Adreno-EGL( 6276): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/chromium( 6276): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6276): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6276): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  760): Activity pause timeout for ActivityRecord{d2d07d6 u0 com.test.thalitest/.MainActivity t3}
,W/AwContents( 6276): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6276): CordovaWebView is running on device made by: samsung
,W/art     ( 6276): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6276): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 6276): performCreate Call secproduct feature valuefalse
D/Activity( 6276): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6276): Render dirty regions requested: true
,D/Atlas   ( 6276): Validating map...
,D/ActivityManager(  760): post active user change for 0
D/KnoxTimeoutHandler(  760): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  760): handleActiveUserChange for user 0
,V/ActivityThread( 6276): updateVisibility : ActivityRecord{19298331 token=android.os.BinderProxy@3e6952bb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  760): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  760): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  760): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  760): setMouseCustomIcon IconType is same.101
,D/PointerIcon(  760): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  760): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6276): Initialized EGL, version 1.4
,I/OpenGLRenderer( 6276): HWUI protection enabled for context ,  &this =0xa1753060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6276): Enabling debug mode 0
,D/InputMethodManagerService(  760): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  760): mDVFSHelper.release()
,I/Timeline(  760): Timeline: Activity_windows_visible id: ActivityRecord{d2d07d6 u0 com.test.thalitest/.MainActivity t3} time:152762
,W/IInputConnectionWrapper( 6276): showStatusIcon on inactive InputConnection
,I/Timeline( 6276): Timeline: Activity_idle id: android.os.BinderProxy@3e6952bb time:152771
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1705): getCurrentCandidateView
,D/SamsungIME( 1705): Dismiss ExpandCandiate
,D/JsMessageQueue( 6276): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6276): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6276): 
,I/SamsungIME( 1705): getDebugLevel  : 0x4f4c
,D/jxcore_app_log( 6276): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1360965888
,D/JX-Cordova( 6276): jxcore cordova android initializing
,I/SamsungIME( 1705): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1705): KeybaordView init() : load resources
,I/SamsungIME( 1705): getCurrentKeyboard
I/SamsungIME( 1705): getTextKeyboard
,D/SamsungIME( 1705): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/SamsungIME( 1705): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/jxcore-log( 6276): Initializing JXcore engine
,W/jxcore-log( 6276): JXcore engine is ready
,W/jxcore-log( 6276): Starting JXcore engine
,E/auditd  ( 1799): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  760): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService(  760): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/Zygote  ( 6348): MountEmulatedStorage()
I/ActivityManager(  760): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6348 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6348): v2
I/libpersona( 6348): KNOX_SDCARD checking this for 1000
I/libpersona( 6348): KNOX_SDCARD not a persona
,I/SELinux ( 6348): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6348): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6348): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 6276): Platform android
W/jxcore-log( 6276): 
W/jxcore-log( 6276): Process ARCH arm
W/jxcore-log( 6276): 
,D/TimaKeyStoreProvider( 6348): TimaSignature is unavailable
,D/ActivityThread( 6348): Added TimaKeyStore provider
,D/ResourcesManager( 6348): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6348):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6348):  SeDenialReceiver : File path = null
,I/ActivityManager(  760): Killing 5063:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,E/SMD     (  286): DCD ON
,I/jxcore-log( 6276): JXcore Cordova bridge is ready!
I/jxcore-log( 6276): 
W/jxcore-log( 6276): JXcore engine is started
,E/jxcore  ( 6276): Error!: missing ) after argument list
E/jxcore  ( 6276): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6276): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame(  760): Set to : 0
,D/PointerIcon(  760): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  760): setMouseCustomIcon IconType is same.101
,D/PointerIcon(  760): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  760): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager(  760): Killing 5320:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,D/ConnectivityService(  760): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ScreenOrientationListener( 6276): Removing an inexistent observer!
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/PowerManagerService(  760): [PWL] Off : 50s ago
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/SSRM:n  (  760): SIOP:: AP = 310, PST = 322, CUR = 450
,E/SMD     (  286): DCD ON
V/AlarmManager(  760): waitForAlarm result :4
D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  760): stay LED for fully charged
I/ServiceManager(  363): Waiting for service AtCmdFwd...
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/NtpTrustedTime(  760): forceRefresh() from cache miss
D/NtpTrustedTime(  760): forceRefresh Fail.
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 5
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 300, PST = 314, CUR = 450
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 300, PST = 311, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,V/AlarmManager(  760): waitForAlarm result :8
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/PowerManagerService(  760): [PWL] Off : 75s ago
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  760): SIOP:: AP = 300, PST = 309, CUR = 450
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 6
,E/SMD     (  286): DCD ON
,I/ClearcutLoggerApiImpl( 1480): disconnect managed GoogleApiClient
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 300, PST = 306, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 300, PST = 303, CUR = 450
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  363): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  363): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  760): [PWL] Off : 105s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 301, CUR = 450
,E/SMD     (  286): DCD ON
,V/AlarmManager(  760): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/NtpTrustedTime(  760): forceRefresh() from cache miss
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NtpTrustedTime(  760): forceRefresh Fail.
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1741): Aggregate from 1449596657440 (log), 1449596657440 (data)
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/Watchdog(  760): !@Sync 7
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 299, CUR = 450
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 298, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/PowerManagerService(  760): [PWL] Off : 140s ago
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 297, CUR = 450
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 295, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 294, CUR = 450
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 293, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 9
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 180s ago
,E/SMD     (  286): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 292, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,D/TimaService(  760): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  760): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  760): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  760): initializing...
,I/TLC_TIMA_PKM_initialize(  760): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  760): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  760): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  760): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  760): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  760): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  760): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  760): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  760): App is not loaded in QSEE
,D/QSEECOMAPI: (  760): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  760): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  760): Trustlet response is completed
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  760): !@Sync 10
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  363): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  363): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,V/AlarmManager(  760): waitForAlarm result :4
,E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): stay LED for fully charged
,I/ActivityManager(  760): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=6401 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,E/Zygote  ( 6401): MountEmulatedStorage()
,E/Zygote  ( 6401): v2
I/libpersona( 6401): KNOX_SDCARD checking this for 10096
,I/libpersona( 6401): KNOX_SDCARD not a persona
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,I/SELinux ( 6401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
I/SELinux ( 6401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6401): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/TimaKeyStoreProvider( 6401): TimaSignature is unavailable
,D/ActivityThread( 6401): Added TimaKeyStore provider
,E/SMD     (  286): DCD ON
,D/ResourcesManager( 6401): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/SurfaceWidgetView( 1443): destroyHardwareResources():925363262
,V/WindowOrientationListener(  760): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  760): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  760): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  760): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  760): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/Launcher( 1443): onRestart, Launcher: 680427261
,D/Launcher( 1443): onStart, Launcher: 680427261
D/Launcher.HomeView( 1443): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1760): [237392/8] Surface widget visibility changed visibility = true on instance = 1
,V/ActivityThread( 1443): updateVisibility : ActivityRecord{6bbc527 token=android.os.BinderProxy@7004300 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/SurfaceWidget.Renderer( 1760): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1760): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,I/SurfaceFlinger(  254): id=14 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  760): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  760): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  760): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  760): setMouseCustomIcon IconType is same.101
D/PointerIcon(  760): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  760): setHoveringSpenCustomIcon IconType is same.1
,D/InputMethodManagerService(  760): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6276): showStatusIcon on inactive InputConnection
,I/ActivityManager(  760): Killing 5343:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,I/Timeline(  760): Timeline: Activity_windows_visible id: ActivityRecord{3a1bfc1 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:332393
,I/PowerManagerService(  760): [PWL] Off : 225s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 11
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5438): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,V/AlarmManager(  760): waitForAlarm result :8
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 12
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/PowerManagerService(  760): [PWL] Off : 275s ago
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 13
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  760): Plugged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 14
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  363): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  363): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  760): [PWL] Off : 330s ago
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 288, CUR = 450
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 15
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 287, CUR = 450
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 286, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/bootchecker(  359): bootchecker wake up!!
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 285, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 16
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 390s ago
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 284, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 283, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 282, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 17
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 281, CUR = 450
,I/ServiceManager(  363): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  363): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,V/AlarmManager(  760): waitForAlarm result :8
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  760): !@Sync 18
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  363): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  363): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  760): [PWL] Off : 455s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,I/Atfwd_Daemon(  363): Stop the daemon....
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  760): stay LED for fully charged
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  760): !@Sync 19
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  760): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  760): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  760): TimaServiceHandler.handleMessage what =1
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  760): !@Sync 20
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON,
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,I/PowerManagerService(  760): [PWL] Off : 525s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  760): !@Sync 21
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5438): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  760): !@Sync 22
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  760): !@Sync 23
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 600s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  760): !@Sync 24
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  760): !@Sync 25
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 680s ago
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  760): !@Sync 26
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 27
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 28
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  760): [PWL] Off : 765s ago
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 29
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/TimaService(  760): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  760): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  760): TimaServiceHandler.handleMessage what =1
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  760): !@Sync 30
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): stay LED for fully charged
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  760): !@Sync 31
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5438): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  760): [PWL] Off : 855s ago
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  760): !@Sync 32
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  760): !@Sync 33
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  760): !@Sync 34
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 950s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  760): !@Sync 35
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  760): !@Sync 36
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  760): !@Sync 37
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  760): !@Sync 38
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  760): [PWL] Off : 1050s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  760): !@Sync 39
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/TimaService(  760): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  760): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  760): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  760): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  760): Updating Usage Statistics in DB @ 1449599469721
,I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
,W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
,W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
,W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
,W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
,W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  760): ::getAppControlDB: Exception to create DB
W/System.err(  760): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  760): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  760): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  760): Done Updating Usage Statistics in DB @ 1449599469902
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  760): !@Sync 40
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): stay LED for fully charged
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 41
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5438): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 1155s ago
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 42
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 43
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): stay LED for fully charged
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 44
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 45
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 1265s ago
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 46
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 47
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 48
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 49
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 1380s ago
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/TimaService(  760): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  760): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  760): TimaServiceHandler.handleMessage what =1
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  760): !@Sync 50
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 51
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5438): (HTTPLog)-Static: isSBSettingEnabled false
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 52
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 53
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  760): [PWL] Off : 1500s ago
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 54
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 55
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 56
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 57
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 1625s ago
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): stay LED for fully charged
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 58
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 59
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService(  760): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  760): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  760): TimaServiceHandler.handleMessage what =1
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  760): !@Sync 60
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  760): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/LightsService(  760): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  760): Light old sensor_state 0, new sensor_state : 512 en : 1
,I/ProcessStatsService(  760): Prepared write state in 10ms
,D/SensorManager(  760): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,I/ProcessStatsService(  760): Prepared write state in 13ms
,D/NtpTrustedTime(  760): forceRefresh() from cache miss
,D/NtpTrustedTime(  760): forceRefresh Fail.
,V/NetworkStats(  760): performPollLocked(flags=0x3)
,D/NetworkStatsFactory(  760): UpdateStatsForKnox
,D/ConnectivityService(  760): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  760): performPollLocked() took 11ms
,D/NtpTrustedTime(  760): forceRefresh() from cache miss
,D/NtpTrustedTime(  760): forceRefresh Fail.
,V/AlarmManager(  760): OOI=Alarm{297e10c9 type 0 when 1449601889614 com.google.android.gms}
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ProcessStatsService(  760): Pruning old procstats: /data/system/procstats/state-2015-12-07-22-13-10.bin
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1569): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1569): (HTTPLog)-Static: isShipBuild true
I/System.out( 1569): (HTTPLog)-Thread-111-906268077: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1569): (HTTPLog)-Static: isSBSettingEnabled false
,D/LightsService(  760): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  760): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  760): unregisterListener ::   
D/LightsService(  760): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SQLiteLog( 1569): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 61
,I/ActivityManager(  760): Killing 5512:flipboard.app/u0a125 (adj 13): empty for 1800s
,I/ActivityManager(  760): Killing 4990:com.google.android.gm/u0a128 (adj 13): empty for 1800s
,I/ActivityManager(  760): Killing 4909:com.sec.android.app.myfiles/u0a56 (adj 15): empty for 1800s
,I/ActivityManager(  760): Killing 4839:com.sec.android.app.music:service/u0a49 (adj 15): empty for 1800s
,I/ActivityManager(  760): Killing 5399:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty for 1801s
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  760): failed to open /acct/uid_10125/pid_5512/cgroup.procs: No such file or directory
,W/libprocessgroup(  760): failed to open /acct/uid_10128/pid_4990/cgroup.procs: No such file or directory
,W/libprocessgroup(  760): failed to open /acct/uid_10056/pid_4909/cgroup.procs: No such file or directory
,W/libprocessgroup(  760): failed to open /acct/uid_10049/pid_4839/cgroup.procs: No such file or directory
,E/SMD     (  286): DCD ON
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_5399/cgroup.procs: No such file or directory
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5438): (HTTPLog)-Static: isSBSettingEnabled false
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  760): [PWL] Off : 1755s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  760): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 62
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/Watchdog(  760): !@Sync 63
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  760): !@Sync 64
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  760): Plugged
,I/MotionRecognitionService(  760): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  760): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  760): Plugged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  760): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  760): stay LED for fully charged
,E/Watchdog(  760): !@Sync 65
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  760): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 6615): 
D/AndroidRuntime( 6615): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6615): CheckJNI is OFF
D/AndroidRuntime( 6615): readGMSProperty: start
D/AndroidRuntime( 6615): readGMSProperty: already setted!!
D/AndroidRuntime( 6615): readGMSProperty: end
D/AndroidRuntime( 6615): addProductProperty: start
E/AffinityControl( 6615): AffinityControl: registerfunction enter
D/AndroidRuntime( 6615): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService(  760): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  760): START PACKAGE DELETE: observer{1055410402}
D/PackageManager(  760): pkg{<packageName>}
D/PackageManager(  760): user{0}
D/PackageManager(  760): caller{2000}
D/PackageManager(  760): flags{3}
D/PersonaManagerService(  760): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  760): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  760): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  760): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  760): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  760): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  760): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  760): getApplicationUninstallationEnabled
D/ApplicationPolicy(  760): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  760): !@killApplicatoin: 10270, uninstall pkg
I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 6276:com.test.thalitest/u0a270 (adj 9): stop com.test.thalitest
W/PackageSettings(  760): Skipping PackageSetting{a9cd961 com.example.hello/10268} due to missing metadata
I/ActivityManager(  760): Killing 6040:com.sec.kidsplat.installer/u0a189 (adj 11): empty for 1893s
I/ActivityManager(  760): Killing 6022:com.samsung.android.snote:provider/u0a168 (adj 11): empty for 1893s
I/ActivityManager(  760): Killing 5415:com.google.android.apps.plus/u0a155 (adj 11): empty for 1893s
I/ActivityManager(  760): Killing 5384:com.sec.android.app.controlpanel/u0a134 (adj 11): empty for 1893s
I/ActivityManager(  760): Killing 5987:com.samsung.helphub/1000 (adj 11): empty for 1894s
I/ActivityManager(  760): Killing 5968:com.samsung.android.app.watchmanagerstub/u0a126 (adj 11): empty for 1894s
I/ActivityManager(  760): Killing 5948:com.samsung.android.app.filterinstaller/1000 (adj 11): empty for 1894s
I/ActivityManager(  760): Killing 5910:com.google.android.apps.docs/u0a112 (adj 11): empty for 1894s
I/ActivityManager(  760): Killing 5365:com.sec.chaton/u0a102 (adj 11): empty for 1896s
I/ActivityManager(  760): Killing 5048:com.samsung.android.app.assistantmenu/1000 (adj 13): empty for 1896s
I/ActivityManager(  760): Killing 5890:com.sec.android.app.soundalive/u0a64 (adj 13): empty for 1896s
I/ActivityManager(  760): Killing 5864:com.osp.app.signin/u0a50 (adj 13): empty for 1896s
I/ActivityManager(  760): Killing 5832:com.samsung.android.sdk.samsunglink/u0a48 (adj 13): empty for 1896s
I/ActivityManager(  760): Killing 4618:com.sec.spp.push/u0a43 (adj 13): empty for 1896s
I/ActivityManager(  760): Killing 5812:com.policydm/1000 (adj 13): empty for 1896s
I/ActivityManager(  760): Killing 4143:com.sec.android.app.shealth/u0a40 (adj 13): empty for 1896s
I/ActivityManager(  760): Killing 5298:com.samsung.android.app.galaxyfinder/u0a39 (adj 13): empty for 1896s
I/ActivityManager(  760): Killing 5779:com.sec.pcw.device/1000 (adj 13): empty for 1897s
I/ActivityManager(  760): Killing 5261:sstream.app/u0a25 (adj 13): empty for 1897s
I/ActivityManager(  760): Killing 5763:com.samsung.groupcast/u0a20 (adj 15): empty for 1897s
I/ActivityManager(  760): Killing 5745:com.google.android.partnersetup/u0a19 (adj 15): empty for 1897s
I/ActivityManager(  760): Killing 5647:com.android.defcontainer/u0a7 (adj 15): empty for 1897s
I/ActivityManager(  760): Killing 5682:com.google.android.gms:car/u0a15 (adj 15): empty for 1907s
E/SMD     (  286): DCD ON
W/ActivityManager(  760): Spurious death for ProcessRecord{fe81473 6276:com.test.thalitest/u0a270}, curProc for 6276: null
W/libprocessgroup(  760): failed to open /acct/uid_10040/pid_4143/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10189/pid_6040/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10168/pid_6022/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10155/pid_5415/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10134/pid_5384/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_5987/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10126/pid_5968/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_5948/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10112/pid_5910/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10102/pid_5365/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_5048/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10064/pid_5890/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10050/pid_5864/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10048/pid_5832/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10043/pid_4618/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_5812/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10039/pid_5298/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_5779/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10025/pid_5261/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10020/pid_5763/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10019/pid_5745/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10007/pid_5647/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10015/pid_5682/cgroup.procs: No such file or directory
I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1592): Explicit concurrent mark sweep GC freed 4823(314KB) AllocSpace objects, 2(689KB) LOS objects, 40% free, 18MB/31MB, paused 705us total 50.620ms
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
W/GeofencerStateMachine( 1480): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1705): mOCRHelper is null
I/art     ( 4065): Explicit concurrent mark sweep GC freed 39308(2MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 550us total 58.075ms
E/Zygote  ( 6660): MountEmulatedStorage()
I/libpersona( 6660): KNOX_SDCARD checking this for 10023
E/Zygote  ( 6660): v2
I/libpersona( 6660): KNOX_SDCARD not a persona
I/ActivityManager(  760): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6660 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/art     ( 6005): Explicit concurrent mark sweep GC freed 8465(496KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 1.792ms total 115.154ms
I/SELinux ( 6660): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6660): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6660): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  760): Explicit concurrent mark sweep GC freed 20472(1943KB) AllocSpace objects, 20(320KB) LOS objects, 17% free, 36MB/44MB, paused 1.216ms total 139.973ms
I/art     (  760): WaitForGcToComplete blocked for 117.919ms for cause Explicit
D/ResourcesManager(  760): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/TimaKeyStoreProvider( 6660): TimaSignature is unavailable
D/ActivityThread( 6660): Added TimaKeyStore provider
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/SecContentProvider2(  760): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  760): mCursor = null
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 6660): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Books/Books.apk
I/KLMS-2.4.511: ( 6660): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/RegisteredServicesCache( 1413): empty dynamic service
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/KLMS-2.4.511: ( 6660): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449600229884
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/KLMS-2.4.511: ( 6660): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6660): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/RCPManagerService(  760): PackageReceiver onReceive()
I/HarmonyEASService(  760): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  760): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  760): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  760): uID is 10270
V/EnterpriseBillingPolicy(  760): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  760): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  760): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  760): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  760): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  760): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  760): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  760): removeObsoleteFile: deleting file=3_task.xml
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6677): MountEmulatedStorage()
E/Zygote  ( 6677): v2
I/libpersona( 6677): KNOX_SDCARD checking this for 10116
I/libpersona( 6677): KNOX_SDCARD not a persona
I/art     (  760): Explicit concurrent mark sweep GC freed 12699(763KB) AllocSpace objects, 4(64KB) LOS objects, 17% free, 36MB/44MB, paused 1.615ms total 266.541ms
I/ActivityManager(  760): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6677 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  760): Killing 6063:com.sec.android.app.samsungapps/u0a45 (adj 15): empty for 1895s
I/SELinux ( 6677): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6677): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6677): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager(  760): delete codoeFile: 
I/AASAUninstall(  760):  com.test.thalitest not target!
D/PackageManager(  760): result of delete: 1{1055410402}
D/AndroidRuntime( 6615): Shutting down VM
W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_6063/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 6677): TimaSignature is unavailable
D/ActivityThread( 6677): Added TimaKeyStore provider
D/ResourcesManager( 6677): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/elm:14491( 6677): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 6677): ELMEngine.ELMEngine( context ).
D/elm:14491( 6677): MDMBridge.setEnterpriseBridge()
D/elm:14491( 6677): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
D/elm:14491( 6677): ElmAgentService : onCreate()
D/elm:14491( 6677): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 6677): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6677): MDMBridge.getInstance()
D/elm:14491( 6677): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 6677): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 6695): MountEmulatedStorage()
E/Zygote  ( 6695): v2
I/libpersona( 6695): KNOX_SDCARD checking this for 10021
I/libpersona( 6695): KNOX_SDCARD not a persona
I/SELinux ( 6695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6695): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  760): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6695 uid=10021 gids={50021, 9997} abi=armeabi-v7a
D/elm:14491( 6677): ElmAgentService : onDestroy().
I/ActivityManager(  760): Killing 5438:com.android.vending/u0a33 (adj 15): empty for 1872s
D/TimaKeyStoreProvider( 6695): TimaSignature is unavailable
D/ActivityThread( 6695): Added TimaKeyStore provider
W/libprocessgroup(  760): failed to open /acct/uid_10033/pid_5438/cgroup.procs: No such file or directory
D/ResourcesManager( 6695): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6695): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6695): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6695): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6713): MountEmulatedStorage()
E/Zygote  ( 6713): v2
I/libpersona( 6713): KNOX_SDCARD checking this for 10025
I/libpersona( 6713): KNOX_SDCARD not a persona
I/SELinux ( 6713): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  760): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=6713 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  760): Killing 4856:com.sec.android.gallery3d/u0a53 (adj 15): empty for 1870s
I/SELinux ( 6713): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6713): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/EventHub(  760): Removing device '/dev/input/event6' due to inotify event
D/TimaKeyStoreProvider( 6713): TimaSignature is unavailable
D/ActivityThread( 6713): Added TimaKeyStore provider
I/EventHub(  760): Removing device '/dev/input/event7' due to inotify event
W/libprocessgroup(  760): failed to open /acct/uid_10053/pid_4856/cgroup.procs: No such file or directory
D/ResourcesManager( 6713): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
W/ResourcesManager( 6713): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ContextImpl( 6713): Unable to create files subdir /data/data/sstream.app/cache
E/ActivityThread( 6713): Unable to setupGraphicsSupport due to missing cache directory
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
W/        ( 6713): Zip: inflate read failed (8070 vs 32768)
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/EventHub(  760): Removing device '/dev/input/event8' due to inotify event
D/AndroidRuntime( 6713): Shutting down VM
D/EnterpriseDeviceManagerService(  760): Package has changed for user 0
D/EnterpriseDeviceManagerService(  760): Admin package name: com.google.android.gms
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
E/AndroidRuntime( 6713): FATAL EXCEPTION: main
E/AndroidRuntime( 6713): Process: sstream.app, PID: 6713
E/AndroidRuntime( 6713): java.lang.RuntimeException: Unable to instantiate application sstream.app.StreamApplication: java.lang.ClassNotFoundException: Didn't find class "sstream.app.StreamApplication" on path: DexPathList[[zip file "/system/framework/twframework.jar", zip file "/system/priv-app/MagazineHome/MagazineHome.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6713): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime( 6713): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5084)
E/AndroidRuntime( 6713): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6713): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6713): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6713): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6713): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6713): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6713): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6713): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6713): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6713): Caused by: java.lang.ClassNotFoundException: Didn't find class "sstream.app.StreamApplication" on path: DexPathList[[zip file "/system/framework/twframework.jar", zip file "/system/priv-app/MagazineHome/MagazineHome.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6713): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 6713): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 6713): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 6713): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime( 6713): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime( 6713): 	... 10 more
E/AndroidRuntime( 6713): 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/priv-app/MagazineHome/MagazineHome.apk': I/O Error
E/AndroidRuntime( 6713): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 6713): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 6713): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 6713): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 6713): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 6713): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 6713): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 6713): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 6713): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 6713): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 6713): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6713): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6713): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 6713): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 6713): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 6713): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 6713): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 6713): 		... 10 more
E/AndroidRuntime( 6713): 	Caused by: java.io.IOException: Failed to open file '/data/dalvik-cache/arm/system@priv-app@MagazineHome@MagazineHome.apk@classes.dex': Read-only file system
E/AndroidRuntime( 6713): 		... 27 more
E/AndroidRuntime( 6713): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/MagazineHome/MagazineHome.apk'
E/AndroidRuntime( 6713): 		... 27 more
E/AndroidRuntime( 6713): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/MagazineHome/arm/MagazineHome.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 6713): 		... 27 more
E/AndroidRuntime( 6713): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 6713): 		... 27 more
E/AndroidRuntime( 6713): 	Suppressed: java.lang.ClassNotFoundException: sstream.app.StreamApplication
E/AndroidRuntime( 6713): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 6713): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 6713): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 6713): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 6713): 		... 13 more
E/AndroidRuntime( 6713): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
V/ApplicationPolicy(  760): isApplicationStateBlocked userId 0 pkgname sstream.app
E/AndroidRuntime(  760): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  760): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  760): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  760): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  760): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  760): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  760): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  760): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/AndroidRuntime(  760): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  760): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  760): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  760): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  760): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  760): 	... 5 more
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  760): checkUser: useridlist=null, currentuser=0
I/EventHub(  760): Removing device '/dev/input/event9' due to inotify event
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/Zygote  ( 6730): MountEmulatedStorage()
I/ActivityManager(  760): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6730 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6730): v2
I/libpersona( 6730): KNOX_SDCARD checking this for 1000
I/libpersona( 6730): KNOX_SDCARD not a persona
I/Process ( 6713): Sending signal. PID: 6713 SIG: 9
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux ( 6730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BatteryService(  760): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  760): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  760): stay LED for fully charged
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
I/EventHub(  760): Removing device '/dev/input/event10' due to inotify event
D/TimaKeyStoreProvider( 6730): TimaSignature is unavailable
D/ActivityThread( 6730): Added TimaKeyStore provider
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/ActivityManager(  760): Process sstream.app (pid 6713)(adj 0) has died(591,1417)
I/EventHub(  760): Removing device '/dev/input/event11' due to inotify event
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
I/MotionRecognitionService(  760): Plugged
I/MotionRecognitionService(  760): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/ResourcesManager( 6730): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  760): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/ContextImpl( 6730): Unable to create files subdir /data/data/com.sec.pcw.device/cache
E/ActivityThread( 6730): Unable to setupGraphicsSupport due to missing cache directory
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/AndroidRuntime( 6730): Shutting down VM
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  760): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/AndroidRuntime( 6730): FATAL EXCEPTION: main
E/AndroidRuntime( 6730): Process: com.sec.pcw.device, PID: 6730
E/AndroidRuntime( 6730): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: java.lang.ClassNotFoundException: Didn't find class "com.sec.pcw.device.contentprovider.DMProvider" on path: DexPathList[[zip file "/system/priv-app/PCWClientS18/PCWClientS18.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6730): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5560)
E/AndroidRuntime( 6730): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5152)
E/AndroidRuntime( 6730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5092)
E/AndroidRuntime( 6730): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6730): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6730): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6730): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6730): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6730): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.pcw.device.contentprovider.DMProvider" on path: DexPathList[[zip file "/system/priv-app/PCWClientS18/PCWClientS18.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6730): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 6730): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 6730): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 6730): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5545)
E/AndroidRuntime( 6730): 	... 11 more
E/AndroidRuntime( 6730): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/PCWClientS18/PCWClientS18.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 6730): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 6730): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 6730): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 6730): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 6730): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 6730): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 6730): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 6730): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 6730): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 6730): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 6730): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6730): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6730): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 6730): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 6730): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 6730): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 6730): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 6730): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5084)
E/AndroidRuntime( 6730): 	
```
