#### Test 50650278352fc1f_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  295): DCD ON
I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 6183): 
D/AndroidRuntime( 6183): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6183): CheckJNI is OFF
D/AndroidRuntime( 6183): readGMSProperty: start
D/AndroidRuntime( 6183): readGMSProperty: already setted!!
D/AndroidRuntime( 6183): readGMSProperty: end
D/AndroidRuntime( 6183): addProductProperty: start
E/AffinityControl( 6183): AffinityControl: registerfunction enter
D/AndroidRuntime( 6183): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  898): inState():  stateMachine is null !!
I/PersonaManagerService(  898): PersonaId don't exist
I/ActivityManager(  898): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  898): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  898): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  898): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  898): mDVFSHelper.acquire()
D/FocusedStackFrame(  898): Set to : 0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6199): MountEmulatedStorage()
E/Zygote  ( 6199): v2
I/libpersona( 6199): KNOX_SDCARD checking this for 10269
I/libpersona( 6199): KNOX_SDCARD not a persona
I/SELinux ( 6199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  898): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6199 uid=10269 gids={50269, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6199): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 6183): Shutting down VM
D/PointerIcon(  898): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  898): setMouseCustomIcon IconType is same.101
D/PointerIcon(  898): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  898): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider( 6199): TimaSignature is unavailable
D/ActivityThread( 6199): Added TimaKeyStore provider
V/WindowOrientationListener(  898): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  898): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  898): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  898): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  898): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  898): Display changed displayId=0
D/SurfaceWidgetView( 1433): destroyHardwareResources():842267577
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6199): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1849): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1433): updateVisibility : ActivityRecord{23d153a6 token=android.os.BinderProxy@313b84ec {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1433): onTrimMemory. Level: 20
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/WebViewFactory( 6199): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6199): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6199): Loading: webviewchromium
,I/LibraryLoader( 6199): Time to load native libraries: 6 ms (timestamps 9544-9550)
,I/LibraryLoader( 6199): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6199): Binding Chromium to main looper Looper (main, tid 1) {1df10b5a}
,I/LibraryLoader( 6199): Expected native library version number "",actual native library version number ""
,I/chromium( 6199): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6199): Initializing chromium process, renderers=0
,W/art     ( 6199): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6199): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6199): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6199): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
,I/chromium( 6199): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,D/BluetoothAdapter( 6199): 313749899: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6199): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6199): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6199): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6199): Local Branch: mybranch5813579
I/Adreno-EGL( 6199): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6199): Local Patches: NONE
I/Adreno-EGL( 6199): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/chromium( 6199): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6199): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6199): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6199): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6199): CordovaWebView is running on device made by: samsung
,W/art     ( 6199): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6199): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  898): Activity pause timeout for ActivityRecord{2e5fc4d2 u0 com.test.thalitest/.MainActivity t3}
,D/Activity( 6199): performCreate Call secproduct feature valuefalse
D/Activity( 6199): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6199): Render dirty regions requested: true
,D/Atlas   ( 6199): Validating map...
,D/ActivityManager(  898): post active user change for 0
,D/KnoxTimeoutHandler(  898): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  898): handleActiveUserChange for user 0
,V/ActivityThread( 6199): updateVisibility : ActivityRecord{2926b598 token=android.os.BinderProxy@31d2ff0a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  898): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  898): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  898): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon(  898): setMouseCustomIcon IconType is same.101
D/PointerIcon(  898): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,I/OpenGLRenderer( 6199): Initialized EGL, version 1.4
D/PointerIcon(  898): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6199): HWUI protection enabled for context ,  &this =0xa1753060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6199): Enabling debug mode 0
,D/InputMethodManagerService(  898): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  898): mDVFSHelper.release()
I/Timeline(  898): Timeline: Activity_windows_visible id: ActivityRecord{2e5fc4d2 u0 com.test.thalitest/.MainActivity t3} time:160080
,I/SamsungIME( 1745): getCurrentCandidateView
,W/IInputConnectionWrapper( 6199): showStatusIcon on inactive InputConnection
,I/Timeline( 6199): Timeline: Activity_idle id: android.os.BinderProxy@31d2ff0a time:160092
,D/SamsungIME( 1745): Dismiss ExpandCandiate
,I/chromium( 6199): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6199): 
,I/SamsungIME( 1745): getDebugLevel  : 0x4f4c
,D/JsMessageQueue( 6199): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1745): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1745): KeybaordView init() : load resources
,I/SamsungIME( 1745): getCurrentKeyboard
I/SamsungIME( 1745): getTextKeyboard
,D/SamsungIME( 1745): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6199): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259431680
,D/JX-Cordova( 6199): jxcore cordova android initializing
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SamsungIME( 1745): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/jxcore-log( 6199): Initializing JXcore engine
W/jxcore-log( 6199): JXcore engine is ready
,W/jxcore-log( 6199): Starting JXcore engine
,E/auditd  ( 1889): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  898): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService(  898): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,I/ActivityManager(  898): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6271 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,E/Zygote  ( 6271): MountEmulatedStorage()
,E/Zygote  ( 6271): v2
,I/libpersona( 6271): KNOX_SDCARD checking this for 1000
,I/libpersona( 6271): KNOX_SDCARD not a persona
,I/art     (  328): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 1.480ms total 19.120ms
,I/SELinux ( 6271): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6271): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 266us total 9.585ms
,E/SELinux ( 6271): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 266us total 9.443ms
,D/TimaKeyStoreProvider( 6271): TimaSignature is unavailable
,D/ActivityThread( 6271): Added TimaKeyStore provider
,D/ResourcesManager( 6271): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6271):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6271):  SeDenialReceiver : File path = null
,W/jxcore-log( 6199): Platform android
W/jxcore-log( 6199): 
,W/jxcore-log( 6199): Process ARCH arm
W/jxcore-log( 6199): 
,I/ActivityManager(  898): Killing 5033:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/jxcore-log( 6199): JXcore Cordova bridge is ready!
I/jxcore-log( 6199): 
,W/jxcore-log( 6199): JXcore engine is started
,E/jxcore  ( 6199): Error!: missing ) after argument list
E/jxcore  ( 6199): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6199): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame(  898): Set to : 0
,D/PointerIcon(  898): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  898): setMouseCustomIcon IconType is same.101
D/PointerIcon(  898): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  898): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager(  898): Killing 4372:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PluginManager( 6199): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,W/ScreenOrientationListener( 6199): Removing an inexistent observer!
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 5
,D/SSRM:n  (  898): SIOP:: AP = 310, PST = 321, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 313, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 75s ago
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 308, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 6
,I/ClearcutLoggerApiImpl( 1486): disconnect managed GoogleApiClient
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 306, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,V/AlarmManager(  898): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1193): handleTimeUpdate
,D/KeyguardEffectViewController( 1193): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1193): *** don't update sliding image ***
,D/NtpTrustedTime(  898): forceRefresh() from cache miss
,D/NtpTrustedTime(  898): forceRefresh Fail.
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 303, CUR = 450,
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  898): [PWL] Off : 105s ago
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  362): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  362): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 301, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/Watchdog(  898): !@Sync 7
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 299, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 298, CUR = 450
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 140s ago
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 297, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 8
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  295): DCD ON
,V/AlarmManager(  898): waitForAlarm result :8
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 294, CUR = 450
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 9
,I/PowerManagerService(  898): [PWL] Off : 180s ago
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/TimaService(  898): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  898): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  898): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  898): initializing...
,I/TLC_TIMA_PKM_initialize(  898): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  898): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  898): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  898): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  898): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  898): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  898): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  898): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  898): App is not loaded in QSEE
,D/QSEECOMAPI: (  898): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  898): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  898): Trustlet response is completed
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  898): !@Sync 10
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  362): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  362): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  898): [PWL] Off : 225s ago
,V/AlarmManager(  898): waitForAlarm result :4
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,E/Zygote  ( 6321): MountEmulatedStorage()
,E/Zygote  ( 6321): v2
I/libpersona( 6321): KNOX_SDCARD checking this for 10096
I/libpersona( 6321): KNOX_SDCARD not a persona
,I/ActivityManager(  898): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=6321 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,I/SELinux ( 6321): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6321): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleTimeUpdate
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardEffectViewController( 1193): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1193): *** don't update sliding image ***
,E/SELinux ( 6321): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6321): TimaSignature is unavailable
,D/ActivityThread( 6321): Added TimaKeyStore provider
,D/ResourcesManager( 6321): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SurfaceWidgetView( 1433): destroyHardwareResources():842267577
V/WindowOrientationListener(  898): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  898): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  898): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  898): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  898): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/Launcher( 1433): onRestart, Launcher: 1002880276
,D/Launcher( 1433): onStart, Launcher: 1002880276
D/Launcher.HomeView( 1433): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1849): [237392/8] Surface widget visibility changed visibility = true on instance = 1
V/ActivityThread( 1433): updateVisibility : ActivityRecord{23d153a6 token=android.os.BinderProxy@313b84ec {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/SurfaceWidget.Renderer( 1849): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1849): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,I/SurfaceFlinger(  254): id=14 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  898): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  898): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  898): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  898): setMouseCustomIcon IconType is same.101
D/PointerIcon(  898): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  898): setHoveringSpenCustomIcon IconType is same.1
,E/SMD     (  295): DCD ON
,D/InputMethodManagerService(  898): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/IInputConnectionWrapper( 6199): showStatusIcon on inactive InputConnection
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  898): Killing 5069:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,I/Timeline(  898): Timeline: Activity_windows_visible id: ActivityRecord{3053370a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:332358
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450,
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 11
,I/art     (  898): Explicit concurrent mark sweep GC freed 260645(18MB) AllocSpace objects, 88(5MB) LOS objects, 17% free, 37MB/45MB, paused 1.462ms total 179.565ms
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5441): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 12
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  295): DCD ON
,V/AlarmManager(  898): waitForAlarm result :8
,I/PowerManagerService(  898): [PWL] Off : 275s ago
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 13
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 288, CUR = 450
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 14
,I/PowerManagerService(  898): [PWL] Off : 330s ago
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 285, CUR = 450
,I/Atfwd_Sendcmd(  362): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  362): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 283, CUR = 450
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 15
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 282, CUR = 450
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/bootchecker(  357): bootchecker wake up!!
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 16
,I/PowerManagerService(  898): [PWL] Off : 390s ago
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 17
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  898): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 18
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  362): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  362): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,V/AlarmManager(  898): waitForAlarm result :8
,I/PowerManagerService(  898): [PWL] Off : 455s ago
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Daemon(  362): Stop the daemon....
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 19
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  898): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  898): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  898): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  898): !@Sync 20
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  898): [PWL] Off : 525s ago
,E/SMD     (  295): DCD ON
,I/ActivityManager(  898): Killing 5322:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  898): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 21
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5441): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 22
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/Watchdog(  898): !@Sync 23
,I/PowerManagerService(  898): [PWL] Off : 600s ago
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  898): !@Sync 24
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/Watchdog(  898): !@Sync 25
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 680s ago
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 26
,V/AlarmManager(  898): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1193): handleTimeUpdate
,D/KeyguardEffectViewController( 1193): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1193): *** don't update sliding image ***
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): stay LED for fully charged
,D/LightsService(  898): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  898): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  898): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1739): Aggregate from 1449587362349 (log), 1449587362349 (data)
,D/LightsService(  898): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  898): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  898): unregisterListener ::   
D/LightsService(  898): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,V/AlarmManager(  898): waitForAlarm result :8,
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 27
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 28
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  898): [PWL] Off : 765s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 29
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,D/TimaService(  898): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  898): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  898): TimaServiceHandler.handleMessage what =1,
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  898): !@Sync 30
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 31
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5441): (HTTPLog)-Static: isSBSettingEnabled false
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  898): [PWL] Off : 855s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 32
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 33
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 34
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 950s ago
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 35
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 36
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 37
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 38
,I/PowerManagerService(  898): [PWL] Off : 1050s ago
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 39
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  898): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  898): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  898): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  898): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  898): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  898): Updating Usage Statistics in DB @ 1449589612651
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  898): Done Updating Usage Statistics in DB @ 1449589612867
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  898): !@Sync 40
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 41
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5441): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 1155s ago
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 42
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 43
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 44
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 45
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 1265s ago
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450,
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 46
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 47
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 48
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 49
,I/PowerManagerService(  898): [PWL] Off : 1380s ago
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/TimaService(  898): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  898): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  898): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  898): !@Sync 50
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 51
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5441): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 52
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 53
,I/PowerManagerService(  898): [PWL] Off : 1500s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  898): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 54
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 55
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 56
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  898): !@Sync 57
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 1625s ago
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 58
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  898): stay LED for fully charged
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 59
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/TimaService(  898): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  898): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  898): TimaServiceHandler.handleMessage what =1
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  898): !@Sync 60
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,V/AlarmManager(  898): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1193): handleTimeUpdate
,D/KeyguardEffectViewController( 1193): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1193): *** don't update sliding image ***
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): stay LED for fully charged
,D/LightsService(  898): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  898): Light old sensor_state 0, new sensor_state : 512 en : 1
,I/ProcessStatsService(  898): Prepared write state in 9ms
,D/SensorManager(  898): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/ProcessStatsService(  898): Prepared write state in 7ms
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/NtpTrustedTime(  898): forceRefresh() from cache miss
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  898): Plugged
,D/NtpTrustedTime(  898): forceRefresh Fail.
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/NetworkStats(  898): performPollLocked(flags=0x3)
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/NetworkStatsFactory(  898): UpdateStatsForKnox
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  898): performPollLocked() took 9ms
,D/NtpTrustedTime(  898): forceRefresh() from cache miss
,D/NtpTrustedTime(  898): forceRefresh Fail.
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  898): Pruning old procstats: /data/system/procstats/state-2015-12-07-16-12-16.bin
,I/System.out( 1591): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1591): (HTTPLog)-Static: isShipBuild true
I/System.out( 1591): (HTTPLog)-Thread-120-1007517934: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1591): (HTTPLog)-Static: isSBSettingEnabled false
,D/LightsService(  898): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  898): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  898): unregisterListener ::   
D/LightsService(  898): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SQLiteLog( 1591): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 61
,I/ActivityManager(  898): Killing 5515:flipboard.app/u0a125 (adj 13): empty for 1800s
,I/ActivityManager(  898): Killing 4916:com.sec.android.app.myfiles/u0a56 (adj 13): empty for 1800s
,I/ActivityManager(  898): Killing 4845:com.sec.android.app.music:service/u0a49 (adj 15): empty for 1800s
,I/ActivityManager(  898): Killing 4999:com.google.android.gm/u0a128 (adj 15): empty for 1800s
,I/ActivityManager(  898): Killing 5402:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty for 1801s
,I/ActivityManager(  898): Killing 5351:com.sec.knox.bridge/1000 (adj 15): empty for 1801s
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  898): failed to open /acct/uid_10125/pid_5515/cgroup.procs: No such file or directory
,W/libprocessgroup(  898): failed to open /acct/uid_10056/pid_4916/cgroup.procs: No such file or directory
,W/libprocessgroup(  898): failed to open /acct/uid_10049/pid_4845/cgroup.procs: No such file or directory
,W/libprocessgroup(  898): failed to open /acct/uid_10128/pid_4999/cgroup.procs: No such file or directory
,W/libprocessgroup(  898): failed to open /acct/uid_1000/pid_5402/cgroup.procs: No such file or directory
,W/libprocessgroup(  898): failed to open /acct/uid_1000/pid_5351/cgroup.procs: No such file or directory
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1591): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5441): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 1755s ago
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 62
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,V/AlarmManager(  898): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 63
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 64
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 65
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  295): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 6565): 
D/AndroidRuntime( 6565): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6565): CheckJNI is OFF
D/AndroidRuntime( 6565): readGMSProperty: start
D/AndroidRuntime( 6565): readGMSProperty: already setted!!
D/AndroidRuntime( 6565): readGMSProperty: end
D/AndroidRuntime( 6565): addProductProperty: start
E/AffinityControl( 6565): AffinityControl: registerfunction enter
D/AndroidRuntime( 6565): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  898): START PACKAGE DELETE: observer{248947673}
D/PackageManager(  898): pkg{<packageName>}
D/PackageManager(  898): user{0}
D/PackageManager(  898): caller{2000}
D/PackageManager(  898): flags{3}
D/PersonaManagerService(  898): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  898): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  898): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  898): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  898): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  898): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  898): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  898): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  898): getApplicationUninstallationEnabled
D/ApplicationPolicy(  898): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  898): !@killApplicatoin: 10269, uninstall pkg
I/ActivityManager(  898): Force stopping com.test.thalitest appid=10269 user=-1: uninstall pkg
I/ActivityManager(  898): Killing 6199:com.test.thalitest/u0a269 (adj 9): stop com.test.thalitest
W/PackageSettings(  898): Skipping PackageSetting{2fdb8ea0 com.example.hello/10268} due to missing metadata
I/ActivityManager(  898): Killing 6066:com.sec.kidsplat.installer/u0a189 (adj 11): empty for 1905s
I/ActivityManager(  898): Killing 5417:com.google.android.apps.plus/u0a155 (adj 11): empty for 1905s
I/ActivityManager(  898): Killing 5387:com.sec.android.app.controlpanel/u0a134 (adj 11): empty for 1905s
I/ActivityManager(  898): Killing 6048:com.samsung.helphub/1000 (adj 11): empty for 1905s
I/ActivityManager(  898): Killing 6033:com.samsung.android.app.watchmanagerstub/u0a126 (adj 11): empty for 1905s
I/ActivityManager(  898): Killing 6012:com.samsung.android.app.filterinstaller/1000 (adj 11): empty for 1905s
I/ActivityManager(  898): Killing 5985:com.google.android.apps.docs/u0a112 (adj 11): empty for 1905s
I/ActivityManager(  898): Killing 5367:com.sec.chaton/u0a102 (adj 11): empty for 1907s
I/ActivityManager(  898): Killing 5054:com.samsung.android.app.assistantmenu/1000 (adj 13): empty for 1907s
I/ActivityManager(  898): Killing 5965:com.sec.android.app.soundalive/u0a64 (adj 13): empty for 1907s
I/ActivityManager(  898): Killing 5944:com.osp.app.signin/u0a50 (adj 13): empty for 1907s
I/ActivityManager(  898): Killing 5919:com.samsung.android.sdk.samsunglink/u0a48 (adj 13): empty for 1907s
I/ActivityManager(  898): Killing 4589:com.sec.spp.push/u0a43 (adj 13): empty for 1908s
I/ActivityManager(  898): Killing 5899:com.policydm/1000 (adj 13): empty for 1908s
I/ActivityManager(  898): Killing 4135:com.sec.android.app.shealth/u0a40 (adj 13): empty for 1908s
I/ActivityManager(  898): Killing 5300:com.samsung.android.app.galaxyfinder/u0a39 (adj 13): empty for 1908s
I/ActivityManager(  898): Killing 5866:com.sec.pcw.device/1000 (adj 13): empty for 1908s
I/ActivityManager(  898): Killing 5261:sstream.app/u0a25 (adj 15): empty for 1908s
I/ActivityManager(  898): Killing 5850:com.samsung.groupcast/u0a20 (adj 15): empty for 1908s
I/ActivityManager(  898): Killing 5831:com.google.android.partnersetup/u0a19 (adj 15): empty for 1908s
I/ActivityManager(  898): Killing 5698:com.android.defcontainer/u0a7 (adj 15): empty for 1908s
I/ActivityManager(  898): Killing 5782:com.google.android.gms:car/u0a15 (adj 15): empty for 1910s
E/SMD     (  295): DCD ON
W/ActivityManager(  898): Spurious death for ProcessRecord{a26119e 6199:com.test.thalitest/u0a269}, curProc for 6199: null
W/libprocessgroup(  898): failed to open /acct/uid_10039/pid_5300/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10189/pid_6066/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10155/pid_5417/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10134/pid_5387/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_1000/pid_6048/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10126/pid_6033/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_1000/pid_6012/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10112/pid_5985/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10102/pid_5367/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_1000/pid_5054/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10064/pid_5965/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10050/pid_5944/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10048/pid_5919/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10043/pid_4589/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_1000/pid_5899/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10040/pid_4135/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10019/pid_5831/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10007/pid_5698/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10015/pid_5782/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10025/pid_5261/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_1000/pid_5866/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10020/pid_5850/cgroup.procs: No such file or directory
I/ActivityManager(  898): Force stopping com.test.thalitest appid=10269 user=0: pkg removed
I/art     ( 4276): Explicit concurrent mark sweep GC freed 8085(483KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 335us total 28.470ms
I/art     ( 1478): Explicit concurrent mark sweep GC freed 4882(320KB) AllocSpace objects, 2(689KB) LOS objects, 39% free, 18MB/31MB, paused 620us total 45.709ms
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/SamsungIME( 1745): mOCRHelper is null
W/GeofencerStateMachine( 1486): Ignoring removeGeofence because network location is disabled.
I/art     ( 4060): Explicit concurrent mark sweep GC freed 37736(2046KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 524us total 43.078ms
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
I/InputReader(  898): Reconfiguring input devices.  changes=0x00000010
E/Zygote  ( 6602): MountEmulatedStorage()
E/Zygote  ( 6602): v2
I/libpersona( 6602): KNOX_SDCARD checking this for 10023
I/libpersona( 6602): KNOX_SDCARD not a persona
I/ActivityManager(  898): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6602 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2(  898): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  898): mCursor = null
D/TimaKeyStoreProvider( 6602): TimaSignature is unavailable
D/ActivityThread( 6602): Added TimaKeyStore provider
I/art     (  898): Explicit concurrent mark sweep GC freed 36419(3MB) AllocSpace objects, 87(1531KB) LOS objects, 17% free, 36MB/44MB, paused 1.522ms total 190.725ms
D/ResourcesManager(  898): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
I/art     (  898): WaitForGcToComplete blocked for 90.771ms for cause Explicit
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/RegisteredServicesCache( 1413): empty dynamic service
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 6602): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/KLMS-2.4.511: ( 6602): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 6602): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449590387897
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/KLMS-2.4.511: ( 6602): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6602): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/RCPManagerService(  898): PackageReceiver onReceive()
I/HarmonyEASService(  898): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  898): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  898): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  898): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  898): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  898): uID is 10269
V/EnterpriseBillingPolicy(  898): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  898): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  898): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  898): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  898): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  898): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  898): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  898): removeObsoleteFile: deleting file=3_task.xml
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
I/art     (  898): Explicit concurrent mark sweep GC freed 14080(782KB) AllocSpace objects, 2(32KB) LOS objects, 17% free, 36MB/44MB, paused 1.704ms total 182.447ms
E/Zygote  ( 6618): MountEmulatedStorage()
E/Zygote  ( 6618): v2
I/libpersona( 6618): KNOX_SDCARD checking this for 10116
I/libpersona( 6618): KNOX_SDCARD not a persona
D/PackageManager(  898): delete codoeFile: 
I/ActivityManager(  898): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6618 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/AASAUninstall(  898):  com.test.thalitest not target!
I/ActivityManager(  898): Killing 6087:com.sec.android.app.samsungapps/u0a45 (adj 15): empty for 1906s
D/PackageManager(  898): result of delete: 1{248947673}
I/SELinux ( 6618): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/AndroidRuntime( 6565): Shutting down VM
I/SELinux ( 6618): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6618): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6618): TimaSignature is unavailable
D/ActivityThread( 6618): Added TimaKeyStore provider
W/libprocessgroup(  898): failed to open /acct/uid_10045/pid_6087/cgroup.procs: No such file or directory
D/ResourcesManager( 6618): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/elm:14491( 6618): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 6618): ELMEngine.ELMEngine( context ).
D/elm:14491( 6618): MDMBridge.setEnterpriseBridge()
D/elm:14491( 6618): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
D/elm:14491( 6618): ElmAgentService : onCreate()
D/elm:14491( 6618): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 6618): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6618): MDMBridge.getInstance()
D/elm:14491( 6618): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 6618): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 6636): MountEmulatedStorage()
E/Zygote  ( 6636): v2
I/libpersona( 6636): KNOX_SDCARD checking this for 10021
I/libpersona( 6636): KNOX_SDCARD not a persona
I/ActivityManager(  898): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6636 uid=10021 gids={50021, 9997} abi=armeabi-v7a
D/elm:14491( 6618): ElmAgentService : onDestroy().
I/SELinux ( 6636): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6636): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6636): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  898): Killing 4862:com.sec.android.gallery3d/u0a53 (adj 15): empty for 1885s
D/TimaKeyStoreProvider( 6636): TimaSignature is unavailable
D/ActivityThread( 6636): Added TimaKeyStore provider
W/libprocessgroup(  898): failed to open /acct/uid_10053/pid_4862/cgroup.procs: No such file or directory
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 6636): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6636): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6636): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6636): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
D/EnterpriseDeviceManagerService(  898): Package has changed for user 0
D/EnterpriseDeviceManagerService(  898): Admin package name: com.google.android.gms
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
E/Zygote  ( 6654): MountEmulatedStorage()
I/libpersona( 6654): KNOX_SDCARD checking this for 10025
E/Zygote  ( 6654): v2
I/libpersona( 6654): KNOX_SDCARD not a persona
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Books/Books.apk
I/ActivityManager(  898): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=6654 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  898): Killing 4783:com.android.mms/u0a55 (adj 15): empty for 1885s
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux ( 6654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6654): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CountryDetector(  898): No listener is left
D/TimaKeyStoreProvider( 6654): TimaSignature is unavailable
D/ActivityThread( 6654): Added TimaKeyStore provider
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
W/libprocessgroup(  898): failed to open /acct/uid_10055/pid_4783/cgroup.procs: No such file or directory
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 6654): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
W/ResourcesManager( 6654): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/linker  ( 6654): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
W/ResourcesManager(  898): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  898): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/MVFD_interface( 6654): <<<  caMVFace_FaceInit
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  898): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6654): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
D/UsbSettingsManager(  898): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  898): onPackageRemoved : com.test.thalitest
W/ContextImpl( 6654): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
I/EventHub(  898): Removing device '/dev/input/event6' due to inotify event
E/SharedPreferencesImpl( 6654): Couldn't rename file /data/data/sstream.app/shared_prefs/shared_prefs.xml to backup file /data/data/sstream.app/shared_prefs/shared_prefs.xml.bak
D/HockeyApp( 6654): Current handler class = sstream.app.util.Log$1
I/EventHub(  898): Removing device '/dev/input/event7' due to inotify event
I/EventHub(  898): Removing device '/dev/input/event8' due to inotify event
I/EventHub(  898): Removing device '/dev/input/event9' due to inotify event
E/SQLiteLog( 6654): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6654): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 6654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6654): 	at sstream.app.provider.StoryProvider.delete(StoryProvider.java:90)
E/SQLiteDatabase( 6654): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:314)
E/SQLiteDatabase( 6654): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/SQLiteDatabase( 6654): 	at sstream.app.provider.DatabaseUtil.deleteConfigSettingForApp(DatabaseUtil.java:985)
E/SQLiteDatabase( 6654): 	at sstream.app.receiver.ApplicationCompatibleReceiver.onReceive(ApplicationCompatibleReceiver.java:216)
E/SQLiteDatabase( 6654): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 6654): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6654): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6654): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6654): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6654): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 6654): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6654): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6654): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 6654): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 6654): Shutting down VM
D/HockeyApp( 6654): Writing unhandled exception to: /data/data/sstream.app/files/ff4430da-e1ee-4dd6-ac7e-ca598b11ab3e.stacktrace
E/HockeyApp( 6654): Error saving exception stacktrace!
E/HockeyApp( 6654): 
E/HockeyApp( 6654): java.io.FileNotFoundException: /data/data/sstream.app/files/ff4430da-e1ee-4dd6-ac7e-ca598b11ab3e.stacktrace: open failed: EROFS (Read-only file system)
E/HockeyApp( 6654): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/HockeyApp( 6654): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/HockeyApp( 6654): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/HockeyApp( 6654): 	at java.io.FileWriter.<init>(FileWriter.java:80)
E/HockeyApp( 6654): 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
E/HockeyApp( 6654): 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
E/HockeyApp( 6654): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/HockeyApp( 6654): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/HockeyApp( 6654): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/HockeyApp( 6654): 	at libcore.io.Posix.open(Native Method)
E/HockeyApp( 6654): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/HockeyApp( 6654): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/HockeyApp( 6654): 	... 7 more
D/ResourcesManager( 6654): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 6654): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SQLiteLog( 6654): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6654): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 6654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6654): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6654): 	at sstream.app.provider.StoryProvider.query(StoryProvider.java:386)
E/SQLiteDatabase( 6654): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteDatabase( 6654): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 6654): 	at andr
```
