#### Test 50650278cc6513d_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main,
E/SMD     (  307): DCD ON
D/AndroidRuntime( 6250): 
D/AndroidRuntime( 6250): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6250): CheckJNI is OFF
D/AndroidRuntime( 6250): readGMSProperty: start
D/AndroidRuntime( 6250): readGMSProperty: already setted!!
D/AndroidRuntime( 6250): readGMSProperty: end
D/AndroidRuntime( 6250): addProductProperty: start
E/AffinityControl( 6250): AffinityControl: registerfunction enter
D/AndroidRuntime( 6250): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  870): inState():  stateMachine is null !!
I/PersonaManagerService(  870): PersonaId don't exist
I/ActivityManager(  870): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  870): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  870): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  870): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  870): mDVFSHelper.acquire()
D/FocusedStackFrame(  870): Set to : 0
E/ActivityManager(  870): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  870): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  870): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  870): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  870): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6265 uid=10269 gids={50269, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PointerIcon(  870): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  870): setMouseCustomIcon IconType is same.101
D/PointerIcon(  870): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  870): setHoveringSpenCustomIcon IconType is same.1
E/Zygote  ( 6265): MountEmulatedStorage()
E/Zygote  ( 6265): v2
I/libpersona( 6265): KNOX_SDCARD checking this for 10269
I/libpersona( 6265): KNOX_SDCARD not a persona
D/AndroidRuntime( 6250): Shutting down VM
I/SELinux ( 6265): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6265): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6265): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6265): TimaSignature is unavailable
D/ActivityThread( 6265): Added TimaKeyStore provider
V/WindowOrientationListener(  870): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  870): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  870): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  870): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  870): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  870): Display changed displayId=0
D/SurfaceWidgetView( 1443): destroyHardwareResources():910939705
D/ConnectivityService(  870): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6265): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1833): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1443): updateVisibility : ActivityRecord{3edecc26 token=android.os.BinderProxy@25719140 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1443): onTrimMemory. Level: 20
I/WebViewFactory( 6265): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 6265): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 6265): Loading: webviewchromium
I/LibraryLoader( 6265): Time to load native libraries: 6 ms (timestamps 6264-6270)
I/LibraryLoader( 6265): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6265): Binding Chromium to main looper Looper (main, tid 1) {2a57d80b}
I/LibraryLoader( 6265): Expected native library version number "",actual native library version number ""
I/chromium( 6265): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6265): Initializing chromium process, renderers=0
W/art     ( 6265): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6265): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6265): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6265): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6265): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
D/BluetoothAdapter( 6265): 784107240: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6265): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6265): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6265): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6265): Local Branch: mybranch5813579
I/Adreno-EGL( 6265): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6265): Local Patches: NONE
I/Adreno-EGL( 6265): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/ActivityManager(  870): Activity pause timeout for ActivityRecord{89d274c u0 com.test.thalitest/.MainActivity t3}
W/chromium( 6265): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6265): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6265): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6265): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6265): CordovaWebView is running on device made by: samsung
W/art     ( 6265): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6265): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 6265): performCreate Call secproduct feature valuefalse
D/Activity( 6265): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 6265): Render dirty regions requested: true
D/Atlas   ( 6265): Validating map...
D/ActivityManager(  870): post active user change for 0
D/KnoxTimeoutHandler(  870): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  870): handleActiveUserChange for user 0
V/ActivityThread( 6265): updateVisibility : ActivityRecord{c8e7c71 token=android.os.BinderProxy@3b12d9fb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  870): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  870): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  870): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  870): setMouseCustomIcon IconType is same.101
D/PointerIcon(  870): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  870): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6265): Initialized EGL, version 1.4
I/OpenGLRenderer( 6265): HWUI protection enabled for context ,  &this =0xb3b4fb28 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6265): Enabling debug mode 0
D/InputMethodManagerService(  870): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline(  870): Timeline: Activity_windows_visible id: ActivityRecord{89d274c u0 com.test.thalitest/.MainActivity t3} time:156890
W/ActivityManager(  870): mDVFSHelper.release()
W/IInputConnectionWrapper( 6265): showStatusIcon on inactive InputConnection
I/Timeline( 6265): Timeline: Activity_idle id: android.os.BinderProxy@3b12d9fb time:156900
W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SamsungIME( 1745): getCurrentCandidateView
D/SamsungIME( 1745): Dismiss ExpandCandiate
D/JsMessageQueue( 6265): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6265): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6265): 
I/SamsungIME( 1745): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1745): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1745): KeybaordView init() : load resources
,I/SamsungIME( 1745): getCurrentKeyboard
I/SamsungIME( 1745): getTextKeyboard
,D/SamsungIME( 1745): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6265): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258383744
,D/JX-Cordova( 6265): jxcore cordova android initializing
,D/SamsungIME( 1745): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/jxcore-log( 6265): Initializing JXcore engine
,W/jxcore-log( 6265): JXcore engine is ready
,W/jxcore-log( 6265): Starting JXcore engine
,E/auditd  ( 1875): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  870): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  870): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  870): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  870): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  870): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService(  870): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,I/ActivityManager(  870): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6349 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6349): MountEmulatedStorage()
E/Zygote  ( 6349): v2
I/libpersona( 6349): KNOX_SDCARD checking this for 1000
I/libpersona( 6349): KNOX_SDCARD not a persona
,I/SELinux ( 6349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 6265): Platform android
W/jxcore-log( 6265): 
,W/jxcore-log( 6265): Process ARCH arm
W/jxcore-log( 6265): 
,D/TimaKeyStoreProvider( 6349): TimaSignature is unavailable
,D/ActivityThread( 6349): Added TimaKeyStore provider
,D/ResourcesManager( 6349): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6349):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6349):  SeDenialReceiver : File path = null
,I/ActivityManager(  870): Killing 4376:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,I/jxcore-log( 6265): JXcore Cordova bridge is ready!
I/jxcore-log( 6265): 
W/jxcore-log( 6265): JXcore engine is started
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/jxcore  ( 6265): Error!: missing ) after argument list
E/jxcore  ( 6265): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6265): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame(  870): Set to : 0
,D/PointerIcon(  870): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  870): setMouseCustomIcon IconType is same.101
D/PointerIcon(  870): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  870): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager(  870): Killing 5087:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,D/ConnectivityService(  870): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ScreenOrientationListener( 6265): Removing an inexistent observer!
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
,I/PowerManagerService(  870): [PWL] Off : 50s ago
,D/SSRM:n  (  870): SIOP:: AP = 330, PST = 322, CUR = 450
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,V/AlarmManager(  870): waitForAlarm result :4
,D/NtpTrustedTime(  870): forceRefresh() from cache miss
,D/NtpTrustedTime(  870): forceRefresh Fail.
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  870): stay LED for fully charged
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  870): Plugged
,I/MotionRecognitionService(  870): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  307): DCD ON
,E/Watchdog(  870): !@Sync 5
,D/PackageManager(  870): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 300, PST = 314, CUR = 450
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 300, PST = 310, CUR = 450
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/PowerManagerService(  870): [PWL] Off : 75s ago
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 307, CUR = 450
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/Watchdog(  870): !@Sync 6
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 304, CUR = 450
,V/AlarmManager(  870): waitForAlarm result :8
,I/ClearcutLoggerApiImpl( 1477): disconnect managed GoogleApiClient
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 301, CUR = 450
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,I/Atfwd_Sendcmd(  357): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  357): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  870): [PWL] Off : 105s ago
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 299, CUR = 450
,E/SMD     (  307): DCD ON
,V/AlarmManager(  870): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/NtpTrustedTime(  870): forceRefresh() from cache miss
,D/NtpTrustedTime(  870): forceRefresh Fail.
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/Watchdog(  870): !@Sync 7
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON,
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 298, CUR = 450
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  870): Plugged,
,I/MotionRecognitionService(  870): setPowerConnected  = true,
,D/BatteryService(  870): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 297, CUR = 450
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  870): Plugged
I/MotionRecognitionService(  870): setPowerConnected  = true
,D/BatteryService(  870): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/PowerManagerService(  870): [PWL] Off : 140s ago
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 296, CUR = 450
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  870): Plugged
,I/MotionRecognitionService(  870): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  870): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  307): DCD ON
,E/Watchdog(  870): !@Sync 8
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 292, CUR = 450
,V/AlarmManager(  870): waitForAlarm result :8
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  870): Plugged
,I/MotionRecognitionService(  870): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  870): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 291, CUR = 450
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/Watchdog(  870): !@Sync 9
,E/SMD     (  307): DCD ON
,I/PowerManagerService(  870): [PWL] Off : 180s ago
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  870): Plugged
I/MotionRecognitionService(  870): setPowerConnected  = true
,D/BatteryService(  870): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  870): Plugged
,I/MotionRecognitionService(  870): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  870): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService(  870): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  870): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  870): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  870): initializing...
,I/TLC_TIMA_PKM_initialize(  870): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  870): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  870): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  870): process = tima_pkm, process_strlen = 8,
I/TZ: qc_tlc_communication(  870): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  870): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  870): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  870): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  870): App is not loaded in QSEE
,D/QSEECOMAPI: (  870): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  870): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  870): Trustlet response is completed
,E/SMD     (  307): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  870): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  870): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  870): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  870): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  870): !@Sync 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,I/Atfwd_Sendcmd(  357): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  357): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  870): waitForAlarm result :4
,E/ActivityManager(  870): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  870): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  870): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  870): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,E/Zygote  ( 6383): MountEmulatedStorage()
,E/Zygote  ( 6383): v2
I/libpersona( 6383): KNOX_SDCARD checking this for 10096
I/libpersona( 6383): KNOX_SDCARD not a persona
,I/ActivityManager(  870): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=6383 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6383): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 6383): TimaSignature is unavailable
,D/ActivityThread( 6383): Added TimaKeyStore provider
,D/SurfaceWidgetView( 1443): destroyHardwareResources():910939705
,V/WindowOrientationListener(  870): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  870): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  870): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  870): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  870): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/Launcher( 1443): onRestart, Launcher: 289876372
,D/Launcher( 1443): onStart, Launcher: 289876372
D/Launcher.HomeView( 1443): onStart
,D/ResourcesManager( 6383): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1833): [237392/8] Surface widget visibility changed visibility = true on instance = 1
V/ActivityThread( 1443): updateVisibility : ActivityRecord{3edecc26 token=android.os.BinderProxy@25719140 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/SurfaceWidget.Renderer( 1833): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1833): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,I/SurfaceFlinger(  254): id=14 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  870): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/SMD     (  307): DCD ON
,D/StatusBarManagerService(  870): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  870): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  870): setMouseCustomIcon IconType is same.101
D/PointerIcon(  870): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  870): setHoveringSpenCustomIcon IconType is same.1
,D/InputMethodManagerService(  870): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/IInputConnectionWrapper( 6265): showStatusIcon on inactive InputConnection
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  870): Killing 5342:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,I/Timeline(  870): Timeline: Activity_windows_visible id: ActivityRecord{38afc9c9 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:332377
,I/PowerManagerService(  870): [PWL] Off : 225s ago
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  870): Plugged
,I/MotionRecognitionService(  870): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  870): stay LED for fully charged
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  307): DCD ON
,E/Watchdog(  870): !@Sync 11
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5462): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  870): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  870): stay LED for fully charged
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  870): Plugged
I/MotionRecognitionService(  870): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  870): Plugged
,I/MotionRecognitionService(  870): setPowerConnected  = true
,D/BatteryService(  870): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 280, PST = 288, CUR = 450
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  870): Plugged
I/MotionRecognitionService(  870): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  870): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/Watchdog(  870): !@Sync 12
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,V/AlarmManager(  870): waitForAlarm result :8
,D/SSRM:n  (  870): SIOP:: AP = 280, PST = 287, CUR = 450
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  870): Plugged
I/MotionRecognitionService(  870): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  870): stay LED for fully charged
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/PowerManagerService(  870): [PWL] Off : 275s ago
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  307): DCD ON
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  870): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  870): Plugged
I/MotionRecognitionService(  870): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  870): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 280, PST = 285, CUR = 450
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  870): Plugged
,I/MotionRecognitionService(  870): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  870): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/Watchdog(  870): !@Sync 13
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/SSRM:n  (  870): SIOP:: AP = 280, PST = 284, CUR = 450
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  870): Plugged
,I/MotionRecognitionService(  870): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  870): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  870): Plugged
,I/MotionRecognitionService(  870): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  870): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 280, PST = 282, CUR = 450
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/Watchdog(  870): !@Sync 14
,E/SMD     (  307): DCD ON
,I/Atfwd_Sendcmd(  357): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  357): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  870): [PWL] Off : 330s ago
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  870): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  870): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  870): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  870): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  870): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  870): Plugged
I/MotionRecognitionService(  870): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  870): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON

```
